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

Total: 26

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
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
| 5.14.0-4mx-amd64          | 3        | 15%     |
| 5.10.0-13-amd64           | 3        | 15%     |
| 5.14.0-3mx-amd64          | 2        | 10%     |
| 5.10.0-9-amd64            | 2        | 10%     |
| 5.10.0-11-amd64           | 2        | 10%     |
| 5.16.0-rc5-hwmon-next+    | 1        | 5%      |
| 5.16.0-5mx-amd64          | 1        | 5%      |
| 5.15.0-2-amd64            | 1        | 5%      |
| 5.15.0-0.bpo.2-amd64      | 1        | 5%      |
| 5.14.0-2mx-amd64          | 1        | 5%      |
| 5.10.52-antix.1-amd64-smp | 1        | 5%      |
| 5.10.111-tkg-cfs          | 1        | 5%      |
| 5.10.0-10-amd64           | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 8        | 40%     |
| 5.14.0   | 6        | 30%     |
| 5.16.0   | 2        | 10%     |
| 5.15.0   | 2        | 10%     |
| 5.10.52  | 1        | 5%      |
| 5.10.111 | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 50%     |
| 5.14    | 6        | 30%     |
| 5.16    | 2        | 10%     |
| 5.15    | 2        | 10%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 15       | 75%     |
| KDE5             | 3        | 15%     |
| lightdm-xsession | 1        | 5%      |
| Unknown          | 1        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 20       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 17       | 85%     |
| SDDM    | 3        | 15%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 45%     |
| de_DE | 5        | 25%     |
| en_GB | 2        | 10%     |
| de_CH | 2        | 10%     |
| sv_SE | 1        | 5%      |
| fr_FR | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 55%     |
| EFI  | 9        | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 17       | 85%     |
| Reiserfs | 1        | 5%      |
| Overlay  | 1        | 5%      |
| Btrfs    | 1        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 16       | 80%     |
| MBR  | 4        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 60%     |
| No        | 8        | 40%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 55%     |
| Yes       | 9        | 45%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 4        | 20%     |
| ASUSTek Computer    | 4        | 20%     |
| Lenovo              | 2        | 10%     |
| Hewlett-Packard     | 2        | 10%     |
| ASRock              | 2        | 10%     |
| MSI                 | 1        | 5%      |
| Intel               | 1        | 5%      |
| Huanan              | 1        | 5%      |
| GALAX               | 1        | 5%      |
| Fujitsu             | 1        | 5%      |
| Dell                | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 2        | 10%     |
| MSI MS-7917                         | 1        | 5%      |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 5%      |
| Lenovo 10AAS1QB0B                   | 1        | 5%      |
| Intel V1.3                          | 1        | 5%      |
| Huanan X99-F8                       | 1        | 5%      |
| HP Z400 Workstation                 | 1        | 5%      |
| HP Compaq 8000 Elite CMT PC         | 1        | 5%      |
| Gigabyte Z390 UD                    | 1        | 5%      |
| Gigabyte X570 AORUS PRO             | 1        | 5%      |
| Gigabyte B550M S2H                  | 1        | 5%      |
| Gigabyte B550M DS3H                 | 1        | 5%      |
| GALAX B550M                         | 1        | 5%      |
| Fujitsu ESPRIMO P720                | 1        | 5%      |
| Dell OptiPlex 7010                  | 1        | 5%      |
| ASUS ROG Maximus XIII HERO          | 1        | 5%      |
| ASUS P5GC-MX/MEDION/SI              | 1        | 5%      |
| ASRock X570 Steel Legend            | 1        | 5%      |
| ASRock N3150M                       | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte B550M      | 2        | 10%     |
| ASUS All            | 2        | 10%     |
| MSI MS-7917         | 1        | 5%      |
| Lenovo ThinkStation | 1        | 5%      |
| Lenovo 10AAS1QB0B   | 1        | 5%      |
| Intel V1.3          | 1        | 5%      |
| Huanan X99-F8       | 1        | 5%      |
| HP Z400             | 1        | 5%      |
| HP Compaq           | 1        | 5%      |
| Gigabyte Z390       | 1        | 5%      |
| Gigabyte X570       | 1        | 5%      |
| GALAX B550M         | 1        | 5%      |
| Fujitsu ESPRIMO     | 1        | 5%      |
| Dell OptiPlex       | 1        | 5%      |
| ASUS ROG            | 1        | 5%      |
| ASUS P5GC-MX        | 1        | 5%      |
| ASRock X570         | 1        | 5%      |
| ASRock N3150M       | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 25%     |
| 2019 | 2        | 10%     |
| 2018 | 2        | 10%     |
| 2016 | 2        | 10%     |
| 2014 | 2        | 10%     |
| 2013 | 2        | 10%     |
| 2021 | 1        | 5%      |
| 2015 | 1        | 5%      |
| 2010 | 1        | 5%      |
| 2009 | 1        | 5%      |
| 2007 | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 20       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 8        | 40%     |
| 4.01-8.0    | 4        | 20%     |
| 3.01-4.0    | 2        | 10%     |
| 16.01-24.0  | 2        | 10%     |
| 8.01-16.0   | 2        | 10%     |
| 2.01-3.0    | 1        | 5%      |
| 64.01-256.0 | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 9        | 45%     |
| 2.01-3.0   | 4        | 20%     |
| 3.01-4.0   | 3        | 15%     |
| 8.01-16.0  | 2        | 10%     |
| 4.01-8.0   | 1        | 5%      |
| 16.01-24.0 | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 6        | 30%     |
| 2      | 6        | 30%     |
| 1      | 3        | 15%     |
| 5      | 2        | 10%     |
| 4      | 2        | 10%     |
| 8      | 1        | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 60%     |
| Yes       | 8        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 90%     |
| Yes       | 2        | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 35%     |
| Germany     | 4        | 20%     |
| Switzerland | 2        | 10%     |
| UK          | 1        | 5%      |
| Sweden      | 1        | 5%      |
| Spain       | 1        | 5%      |
| India       | 1        | 5%      |
| Greece      | 1        | 5%      |
| France      | 1        | 5%      |
| Australia   | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Lausen              | 2        | 10%     |
| Volos               | 1        | 5%      |
| Vilhelmina          | 1        | 5%      |
| Seelbach            | 1        | 5%      |
| San Diego           | 1        | 5%      |
| Rosporden           | 1        | 5%      |
| Portland            | 1        | 5%      |
| Piedmont            | 1        | 5%      |
| Normal              | 1        | 5%      |
| Munster             | 1        | 5%      |
| Milwaukee           | 1        | 5%      |
| London              | 1        | 5%      |
| Houston             | 1        | 5%      |
| Granadilla de Abona | 1        | 5%      |
| Göttingen          | 1        | 5%      |
| Freital             | 1        | 5%      |
| Brisbane            | 1        | 5%      |
| Bengaluru           | 1        | 5%      |
| Belmont             | 1        | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 17     | 20.45%  |
| WDC                 | 7        | 11     | 15.91%  |
| Seagate             | 6        | 8      | 13.64%  |
| Kingston            | 5        | 5      | 11.36%  |
| PNY                 | 2        | 3      | 4.55%   |
| Hitachi             | 2        | 2      | 4.55%   |
| Crucial             | 2        | 2      | 4.55%   |
| Corsair             | 2        | 2      | 4.55%   |
| Transcend           | 1        | 1      | 2.27%   |
| Toshiba             | 1        | 1      | 2.27%   |
| SPCC                | 1        | 1      | 2.27%   |
| OCZ                 | 1        | 1      | 2.27%   |
| Micron Technology   | 1        | 1      | 2.27%   |
| MAXTOR              | 1        | 1      | 2.27%   |
| GOODRAM             | 1        | 1      | 2.27%   |
| Avant               | 1        | 1      | 2.27%   |
| A-DATA Technology   | 1        | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB           | 3        | 5.26%   |
| Kingston SA400S37480G 480GB SSD          | 3        | 5.26%   |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 3.51%   |
| Samsung SSD 850 EVO 1TB                  | 2        | 3.51%   |
| Corsair MP400 2TB                        | 2        | 3.51%   |
| WDC WDS500G2B0C-00PXH0 500GB             | 1        | 1.75%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1.75%   |
| WDC WD60EZRZ-00RWYB1 6TB                 | 1        | 1.75%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1        | 1.75%   |
| WDC WD5002AALX-00J37A0 500GB             | 1        | 1.75%   |
| WDC WD5000AVCS-632DY1 500GB              | 1        | 1.75%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1        | 1.75%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1        | 1.75%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1.75%   |
| WDC WD10EVDS-63U8B1 1TB                  | 1        | 1.75%   |
| Transcend TS128GSSD370S 128GB            | 1        | 1.75%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1.75%   |
| SPCC Solid State Disk 256GB              | 1        | 1.75%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1.75%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1.75%   |
| Seagate ST3500413AS 500GB                | 1        | 1.75%   |
| Seagate ST3360320AS 360GB                | 1        | 1.75%   |
| Samsung SSD 980 PRO 1TB                  | 1        | 1.75%   |
| Samsung SSD 970 PRO 512GB                | 1        | 1.75%   |
| Samsung SSD 870 EVO 500GB                | 1        | 1.75%   |
| Samsung SSD 860 QVO 1TB                  | 1        | 1.75%   |
| Samsung SSD 860 EVO 500G                 | 1        | 1.75%   |
| Samsung SSD 850 EVO 500GB                | 1        | 1.75%   |
| Samsung SSD 840 Series 120GB             | 1        | 1.75%   |
| Samsung SSD 840 EVO 250GB                | 1        | 1.75%   |
| Samsung MZVPW256HEGL-00000 256GB         | 1        | 1.75%   |
| Samsung MZVLW256HEHP-000L2 256GB         | 1        | 1.75%   |
| Samsung MZVL21T0HCLR-00BL7 1TB           | 1        | 1.75%   |
| Samsung HD501LJ 500GB                    | 1        | 1.75%   |
| Samsung HD204UI 2TB                      | 1        | 1.75%   |
| PNY CS900 250GB SSD                      | 1        | 1.75%   |
| PNY CS3030 1TB SSD                       | 1        | 1.75%   |
| PNY CS2130 2TB SSD                       | 1        | 1.75%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1.75%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1        | 1.75%   |
| MAXTOR 4K040H2 40GB                      | 1        | 1.75%   |
| Kingston SV300S37A240G 240GB SSD         | 1        | 1.75%   |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.75%   |
| Hitachi HUA722010CLA330 1TB              | 1        | 1.75%   |
| Hitachi HDS721050CLA360 500GB            | 1        | 1.75%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1.75%   |
| Crucial CT500P2SSD8 500GB                | 1        | 1.75%   |
| Crucial CT120BX500SSD1 120GB             | 1        | 1.75%   |
| Avant 60GB Client SSD                    | 1        | 1.75%   |
| A-DATA SP900 64GB SSD                    | 1        | 1.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 35.29%  |
| WDC                 | 5        | 9      | 29.41%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| Hitachi             | 2        | 2      | 11.76%  |
| Toshiba             | 1        | 1      | 5.88%   |
| MAXTOR              | 1        | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 28.57%  |
| Kingston            | 5        | 5      | 23.81%  |
| WDC                 | 1        | 1      | 4.76%   |
| Transcend           | 1        | 1      | 4.76%   |
| SPCC                | 1        | 1      | 4.76%   |
| PNY                 | 1        | 1      | 4.76%   |
| OCZ                 | 1        | 1      | 4.76%   |
| Micron Technology   | 1        | 1      | 4.76%   |
| GOODRAM             | 1        | 1      | 4.76%   |
| Crucial             | 1        | 1      | 4.76%   |
| Avant               | 1        | 1      | 4.76%   |
| A-DATA Technology   | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 16       | 23     | 40%     |
| HDD  | 13       | 23     | 32.5%   |
| NVMe | 11       | 13     | 27.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 19       | 44     | 61.29%  |
| NVMe | 11       | 13     | 35.48%  |
| SAS  | 1        | 2      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 16       | 27     | 51.61%  |
| 0.51-1.0   | 7        | 8      | 22.58%  |
| 1.01-2.0   | 4        | 5      | 12.9%   |
| 3.01-4.0   | 2        | 2      | 6.45%   |
| 2.01-3.0   | 1        | 1      | 3.23%   |
| 4.01-10.0  | 1        | 3      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 5        | 25%     |
| More than 3000 | 4        | 20%     |
| 1001-2000      | 3        | 15%     |
| 501-1000       | 3        | 15%     |
| 2001-3000      | 2        | 10%     |
| 101-250        | 2        | 10%     |
| 51-100         | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 5        | 25%     |
| 51-100         | 4        | 20%     |
| 101-250        | 3        | 15%     |
| 1001-2000      | 3        | 15%     |
| 1-20           | 2        | 10%     |
| More than 3000 | 1        | 5%      |
| 251-500        | 1        | 5%      |
| 2001-3000      | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 11.11%  |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 11.11%  |
| Seagate ST3500413AS 500GB                | 1        | 1      | 11.11%  |
| Seagate ST3360320AS 360GB                | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 11.11%  |
| MAXTOR 4K040H2 40GB                      | 1        | 1      | 11.11%  |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 33.33%  |
| Samsung Electronics | 3        | 3      | 33.33%  |
| WDC                 | 1        | 1      | 11.11%  |
| MAXTOR              | 1        | 1      | 11.11%  |
| GOODRAM             | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 75%     |
| MAXTOR  | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 5        | 5      | 62.5%   |
| HDD  | 3        | 4      | 37.5%   |

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
| Works    | 18       | 48     | 66.67%  |
| Malfunc  | 8        | 9      | 29.63%  |
| Detected | 1        | 2      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 14       | 41.18%  |
| Samsung Electronics       | 6        | 17.65%  |
| AMD                       | 6        | 17.65%  |
| Phison Electronics        | 3        | 8.82%   |
| ASMedia Technology        | 3        | 8.82%   |
| Sandisk                   | 1        | 2.94%   |
| Micron/Crucial Technology | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 7.5%    |
| Phison E12 NVMe Controller                                                       | 3        | 7.5%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3        | 7.5%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3        | 7.5%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 7.5%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 3        | 7.5%    |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 7.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 5%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2        | 5%      |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1        | 2.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 2.5%    |
| Intel SATA Controller [RAID mode]                                                | 1        | 2.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 2.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 2.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1        | 2.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1        | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 2.5%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 2.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 2.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1        | 2.5%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1        | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 54.84%  |
| NVMe | 11       | 35.48%  |
| IDE  | 2        | 6.45%   |
| RAID | 1        | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 70%     |
| AMD    | 6        | 30%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i7-5820K CPU @ 3.30GHz          | 2        | 10%     |
| Intel Xeon CPU W3565 @ 3.20GHz             | 1        | 5%      |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz        | 1        | 5%      |
| Intel Core i9-10850K CPU @ 3.60GHz         | 1        | 5%      |
| Intel Core i5-9600K CPU @ 3.70GHz          | 1        | 5%      |
| Intel Core i5-4690K CPU @ 3.50GHz          | 1        | 5%      |
| Intel Core i5-4570T CPU @ 2.90GHz          | 1        | 5%      |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 5%      |
| Intel Core i5 CPU M 520 @ 2.40GHz          | 1        | 5%      |
| Intel Core i3-4130 CPU @ 3.40GHz           | 1        | 5%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 1        | 5%      |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz       | 1        | 5%      |
| Intel Celeron CPU N3150 @ 1.60GHz          | 1        | 5%      |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores | 1        | 5%      |
| AMD Ryzen 9 3900X 12-Core Processor        | 1        | 5%      |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 5%      |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 5%      |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 5%      |
| AMD Ryzen 3 3100 4-Core Processor          | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 5        | 25%     |
| Intel Xeon             | 2        | 10%     |
| Intel Core i7          | 2        | 10%     |
| Intel Core 2 Duo       | 2        | 10%     |
| AMD Ryzen 5            | 2        | 10%     |
| Intel Core i9          | 1        | 5%      |
| Intel Core i3          | 1        | 5%      |
| Intel Celeron          | 1        | 5%      |
| AMD Ryzen Threadripper | 1        | 5%      |
| AMD Ryzen 9            | 1        | 5%      |
| AMD Ryzen 7            | 1        | 5%      |
| AMD Ryzen 3            | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 5        | 25%     |
| 4      | 5        | 25%     |
| 2      | 5        | 25%     |
| 12     | 3        | 15%     |
| 10     | 1        | 5%      |
| 8      | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 65%     |
| 1      | 7        | 35%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 20%     |
| 0x306f2    | 2        | 10%     |
| 0x08701021 | 2        | 10%     |
| 0xa0655    | 1        | 5%      |
| 0x906ed    | 1        | 5%      |
| 0x6fd      | 1        | 5%      |
| 0x406c3    | 1        | 5%      |
| 0x306c3    | 1        | 5%      |
| 0x306a9    | 1        | 5%      |
| 0x20655    | 1        | 5%      |
| 0x1067a    | 1        | 5%      |
| 0x0a201016 | 1        | 5%      |
| 0x0a201009 | 1        | 5%      |
| 0x08301039 | 1        | 5%      |
| 0x0800820d | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Haswell    | 6        | 30%     |
| Zen 2      | 3        | 15%     |
| Zen 3      | 2        | 10%     |
| Zen+       | 1        | 5%      |
| Westmere   | 1        | 5%      |
| Silvermont | 1        | 5%      |
| Penryn     | 1        | 5%      |
| Nehalem    | 1        | 5%      |
| KabyLake   | 1        | 5%      |
| IvyBridge  | 1        | 5%      |
| Core       | 1        | 5%      |
| CometLake  | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 39.13%  |
| Intel  | 7        | 30.43%  |
| AMD    | 7        | 30.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 8.7%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2        | 8.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 8.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 8.7%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 4.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 4.35%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 4.35%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 4.35%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 4.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 4.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 4.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 4.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 4.35%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                         | 1        | 4.35%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 4.35%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 4.35%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 9        | 45%     |
| 1 x AMD     | 6        | 30%     |
| 1 x Intel   | 4        | 20%     |
| Intel + AMD | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 60%     |
| Proprietary | 8        | 40%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 5        | 25%     |
| 3.01-4.0   | 5        | 25%     |
| Unknown    | 5        | 25%     |
| 8.01-16.0  | 2        | 10%     |
| 0.51-1.0   | 2        | 10%     |
| 0.01-0.5   | 1        | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 4        | 15.38%  |
| Fujitsu Siemens      | 3        | 11.54%  |
| Samsung Electronics  | 2        | 7.69%   |
| Medion               | 2        | 7.69%   |
| Hewlett-Packard      | 2        | 7.69%   |
| AOC                  | 2        | 7.69%   |
| Ancor Communications | 2        | 7.69%   |
| Acer                 | 2        | 7.69%   |
| Vizio                | 1        | 3.85%   |
| SAC                  | 1        | 3.85%   |
| Philips              | 1        | 3.85%   |
| NEC Computers        | 1        | 3.85%   |
| Iiyama               | 1        | 3.85%   |
| Grundig              | 1        | 3.85%   |
| Gigabyte Technology  | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 7.14%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 3.57%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch     | 1        | 3.57%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 3.57%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 3.57%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch           | 1        | 3.57%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 1        | 3.57%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch            | 1        | 3.57%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch            | 1        | 3.57%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 3.57%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                    | 1        | 3.57%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch      | 1        | 3.57%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 520x320mm 24.0-inch          | 1        | 3.57%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 1        | 3.57%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch      | 1        | 3.57%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                     | 1        | 3.57%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                    | 1        | 3.57%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                    | 1        | 3.57%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                      | 1        | 3.57%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1        | 3.57%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 1        | 3.57%   |
| AOC L32W961 AOC3296 1360x768 700x390mm 31.5-inch                      | 1        | 3.57%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch      | 1        | 3.57%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 3.57%   |
| Acer K272HL ACR0523 1920x1080 598x336mm 27.0-inch                     | 1        | 3.57%   |
| Acer AL1717 ACRAD54 1280x1024 338x270mm 17.0-inch                     | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 28%     |
| 2560x1440 (QHD)    | 6        | 24%     |
| 1680x1050 (WSXGA+) | 3        | 12%     |
| 3840x2160 (4K)     | 2        | 8%      |
| 3440x1440          | 2        | 8%      |
| 1920x1200 (WUXGA)  | 2        | 8%      |
| 1280x1024 (SXGA)   | 2        | 8%      |
| 1360x768           | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 25%     |
| 31      | 4        | 16.67%  |
| 22      | 3        | 12.5%   |
| 34      | 2        | 8.33%   |
| 24      | 2        | 8.33%   |
| 23      | 2        | 8.33%   |
| 54      | 1        | 4.17%   |
| 26      | 1        | 4.17%   |
| 19      | 1        | 4.17%   |
| 17      | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 43.48%  |
| 601-700     | 4        | 17.39%  |
| 401-500     | 3        | 13.04%  |
| 701-800     | 2        | 8.7%    |
| 351-400     | 1        | 4.35%   |
| 301-350     | 1        | 4.35%   |
| 1001-1500   | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 60.87%  |
| 16/10 | 5        | 21.74%  |
| 5/4   | 2        | 8.7%    |
| 21/9  | 2        | 8.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 6        | 25%     |
| 301-350        | 6        | 25%     |
| 201-250        | 5        | 20.83%  |
| 251-300        | 3        | 12.5%   |
| More than 1000 | 1        | 4.17%   |
| 151-200        | 1        | 4.17%   |
| 141-150        | 1        | 4.17%   |
| Unknown        | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 69.57%  |
| 101-120 | 5        | 21.74%  |
| 1-50    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 65%     |
| 2     | 5        | 25%     |
| 3     | 2        | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 33.33%  |
| Intel                 | 9        | 33.33%  |
| TP-Link               | 2        | 7.41%   |
| Qualcomm Atheros      | 2        | 7.41%   |
| Broadcom              | 2        | 7.41%   |
| Edimax Technology     | 1        | 3.7%    |
| Broadcom Limited      | 1        | 3.7%    |
| Aquantia              | 1        | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 24.14%  |
| Intel I211 Gigabit Network Connection                             | 3        | 10.34%  |
| Intel Ethernet Connection (2) I218-V                              | 2        | 6.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 3.45%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 3.45%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 3.45%   |
| Intel Wireless 8260                                               | 1        | 3.45%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.45%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.45%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 3.45%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 3.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.45%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 3.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 3.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 2        | 28.57%  |
| Realtek Semiconductor | 1        | 14.29%  |
| Intel                 | 1        | 14.29%  |
| Edimax Technology     | 1        | 14.29%  |
| Broadcom Limited      | 1        | 14.29%  |
| Broadcom              | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 14.29%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 14.29%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 14.29%  |
| Intel Wireless 8260                                        | 1        | 14.29%  |
| Edimax RTL8192S WLAN Adapter                               | 1        | 14.29%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 14.29%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 42.86%  |
| Realtek Semiconductor | 8        | 38.1%   |
| Qualcomm Atheros      | 2        | 9.52%   |
| Broadcom              | 1        | 4.76%   |
| Aquantia              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 31.82%  |
| Intel I211 Gigabit Network Connection                             | 3        | 13.64%  |
| Intel Ethernet Connection (2) I218-V                              | 2        | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.55%   |
| Intel Ethernet Connection I217-V                                  | 1        | 4.55%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 4.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 4.55%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 74.07%  |
| WiFi     | 7        | 25.93%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 66.67%  |
| WiFi     | 7        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 75%     |
| 2     | 4        | 20%     |
| 3     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 55%     |
| Yes  | 9        | 45%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| ASUSTek Computer | 1        | 50%     |
| Apple            | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 50%     |
| Apple Bluetooth USB Host Controller                   | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 13       | 34.21%  |
| AMD                 | 9        | 23.68%  |
| Nvidia              | 7        | 18.42%  |
| ROCCAT              | 2        | 5.26%   |
| Creative Labs       | 2        | 5.26%   |
| Unknown             | 1        | 2.63%   |
| Schiit Audio        | 1        | 2.63%   |
| Razer USA           | 1        | 2.63%   |
| GN Netcom           | 1        | 2.63%   |
| C-Media Electronics | 1        | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 8.89%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 6.67%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 6.67%   |
| ROCCAT Khan AIMO                                                                                  | 2        | 4.44%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 4.44%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2        | 4.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 4.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 4.44%   |
| Unknown Realtek USB Audio Rear                                                                    | 1        | 2.22%   |
| Unknown Realtek USB Audio Front                                                                   | 1        | 2.22%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1        | 2.22%   |
| Razer USA Kraken Tournament Edition                                                               | 1        | 2.22%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 2.22%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 2.22%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 2.22%   |
| GN Netcom Jabra BIZ 2300                                                                          | 1        | 2.22%   |
| C-Media Electronics Blue Snowball                                                                 | 1        | 2.22%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1        | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1        | 2.22%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 6        | 31.58%  |
| G.Skill             | 4        | 21.05%  |
| Kingston            | 3        | 15.79%  |
| Unknown             | 2        | 10.53%  |
| Samsung Electronics | 2        | 10.53%  |
| SK Hynix            | 1        | 5.26%   |
| Micron Technology   | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s | 2        | 10.53%  |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 10.53%  |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 5.26%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 1        | 5.26%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1        | 5.26%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s   | 1        | 5.26%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s   | 1        | 5.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 1        | 5.26%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s   | 1        | 5.26%   |
| Kingston RAM 99U5471-033.A00LF 4096MB DIMM DDR3        | 1        | 5.26%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 5.26%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s  | 1        | 5.26%   |
| G.Skill RAM F4-3600C19-16GSXWB 16GB DIMM DDR4 3600MT/s | 1        | 5.26%   |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s     | 1        | 5.26%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1400MT/s   | 1        | 5.26%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s  | 1        | 5.26%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s  | 1        | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 11       | 57.89%  |
| DDR3  | 6        | 31.58%  |
| SDRAM | 1        | 5.26%   |
| DDR2  | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 94.74%  |
| SODIMM | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 7        | 36.84%  |
| 8192  | 5        | 26.32%  |
| 16384 | 4        | 21.05%  |
| 32768 | 2        | 10.53%  |
| 2048  | 1        | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 4        | 21.05%  |
| 2133    | 3        | 15.79%  |
| 1600    | 3        | 15.79%  |
| 3400    | 2        | 10.53%  |
| 3466    | 1        | 5.26%   |
| 3200    | 1        | 5.26%   |
| 2667    | 1        | 5.26%   |
| 1400    | 1        | 5.26%   |
| 1333    | 1        | 5.26%   |
| 333     | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

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
| Logitech               | 3        | 60%     |
| Microsoft              | 1        | 20%     |
| Generalplus Technology | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Logitech Webcam C930e      | 2        | 40%     |
| Microsoft LifeCam HD-3000  | 1        | 20%     |
| Logitech Webcam C270       | 1        | 20%     |
| Generalplus GENERAL WEBCAM | 1        | 20%     |

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
| 0     | 17       | 85%     |
| 1     | 3        | 15%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 100%    |

