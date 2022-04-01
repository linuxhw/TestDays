MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 20

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
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
| 5.14.0-4mx-amd64          | 3        | 20%     |
| 5.14.0-3mx-amd64          | 2        | 13.33%  |
| 5.10.0-9-amd64            | 2        | 13.33%  |
| 5.10.0-11-amd64           | 2        | 13.33%  |
| 5.16.0-rc5-hwmon-next+    | 1        | 6.67%   |
| 5.15.0-2-amd64            | 1        | 6.67%   |
| 5.15.0-0.bpo.2-amd64      | 1        | 6.67%   |
| 5.14.0-2mx-amd64          | 1        | 6.67%   |
| 5.10.52-antix.1-amd64-smp | 1        | 6.67%   |
| 5.10.0-10-amd64           | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 6        | 40%     |
| 5.10.0  | 5        | 33.33%  |
| 5.15.0  | 2        | 13.33%  |
| 5.16.0  | 1        | 6.67%   |
| 5.10.52 | 1        | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 6        | 40%     |
| 5.10    | 6        | 40%     |
| 5.15    | 2        | 13.33%  |
| 5.16    | 1        | 6.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 15       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 11       | 73.33%  |
| KDE5             | 3        | 20%     |
| lightdm-xsession | 1        | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 15       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 12       | 80%     |
| SDDM    | 3        | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 6        | 40%     |
| de_DE | 4        | 26.67%  |
| en_GB | 2        | 13.33%  |
| de_CH | 2        | 13.33%  |
| fr_FR | 1        | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 8        | 53.33%  |
| BIOS | 7        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 13       | 86.67%  |
| Overlay | 1        | 6.67%   |
| Btrfs   | 1        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 13       | 86.67%  |
| MBR  | 2        | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 60%     |
| No        | 6        | 40%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 53.33%  |
| Yes       | 7        | 46.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 3        | 20%     |
| ASUSTek Computer    | 3        | 20%     |
| Lenovo              | 2        | 13.33%  |
| Hewlett-Packard     | 2        | 13.33%  |
| MSI                 | 1        | 6.67%   |
| Huanan              | 1        | 6.67%   |
| GALAX               | 1        | 6.67%   |
| Fujitsu             | 1        | 6.67%   |
| ASRock              | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7917                         | 1        | 6.67%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 6.67%   |
| Lenovo 10AAS1QB0B                   | 1        | 6.67%   |
| Huanan X99-F8                       | 1        | 6.67%   |
| HP Z400 Workstation                 | 1        | 6.67%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 6.67%   |
| Gigabyte Z390 UD                    | 1        | 6.67%   |
| Gigabyte X570 AORUS PRO             | 1        | 6.67%   |
| Gigabyte B550M DS3H                 | 1        | 6.67%   |
| GALAX B550M                         | 1        | 6.67%   |
| Fujitsu ESPRIMO P720                | 1        | 6.67%   |
| ASUS ROG Maximus XIII HERO          | 1        | 6.67%   |
| ASUS P5GC-MX/MEDION/SI              | 1        | 6.67%   |
| ASUS All Series                     | 1        | 6.67%   |
| ASRock X570 Steel Legend            | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7917         | 1        | 6.67%   |
| Lenovo ThinkStation | 1        | 6.67%   |
| Lenovo 10AAS1QB0B   | 1        | 6.67%   |
| Huanan X99-F8       | 1        | 6.67%   |
| HP Z400             | 1        | 6.67%   |
| HP Compaq           | 1        | 6.67%   |
| Gigabyte Z390       | 1        | 6.67%   |
| Gigabyte X570       | 1        | 6.67%   |
| Gigabyte B550M      | 1        | 6.67%   |
| GALAX B550M         | 1        | 6.67%   |
| Fujitsu ESPRIMO     | 1        | 6.67%   |
| ASUS ROG            | 1        | 6.67%   |
| ASUS P5GC-MX        | 1        | 6.67%   |
| ASUS All            | 1        | 6.67%   |
| ASRock X570         | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 26.67%  |
| 2019 | 2        | 13.33%  |
| 2018 | 2        | 13.33%  |
| 2014 | 2        | 13.33%  |
| 2021 | 1        | 6.67%   |
| 2013 | 1        | 6.67%   |
| 2010 | 1        | 6.67%   |
| 2009 | 1        | 6.67%   |
| 2007 | 1        | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 15       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 15       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 6        | 40%     |
| 4.01-8.0    | 2        | 13.33%  |
| 16.01-24.0  | 2        | 13.33%  |
| 8.01-16.0   | 2        | 13.33%  |
| 3.01-4.0    | 1        | 6.67%   |
| 2.01-3.0    | 1        | 6.67%   |
| 64.01-256.0 | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 7        | 46.67%  |
| 2.01-3.0   | 3        | 20%     |
| 3.01-4.0   | 2        | 13.33%  |
| 4.01-8.0   | 1        | 6.67%   |
| 16.01-24.0 | 1        | 6.67%   |
| 8.01-16.0  | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 5        | 33.33%  |
| 2      | 4        | 26.67%  |
| 1      | 3        | 20%     |
| 8      | 1        | 6.67%   |
| 5      | 1        | 6.67%   |
| 4      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 86.67%  |
| Yes       | 2        | 13.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 33.33%  |
| Germany     | 3        | 20%     |
| Switzerland | 2        | 13.33%  |
| UK          | 1        | 6.67%   |
| India       | 1        | 6.67%   |
| Greece      | 1        | 6.67%   |
| France      | 1        | 6.67%   |
| Australia   | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Desktops | Percent |
|------------|----------|---------|
| Lausen     | 2        | 13.33%  |
| Volos      | 1        | 6.67%   |
| San Diego  | 1        | 6.67%   |
| Rosporden  | 1        | 6.67%   |
| Portland   | 1        | 6.67%   |
| Normal     | 1        | 6.67%   |
| Munster    | 1        | 6.67%   |
| Milwaukee  | 1        | 6.67%   |
| London     | 1        | 6.67%   |
| Houston    | 1        | 6.67%   |
| Göttingen | 1        | 6.67%   |
| Freital    | 1        | 6.67%   |
| Brisbane   | 1        | 6.67%   |
| Bengaluru  | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 11     | 21.21%  |
| WDC                 | 6        | 9      | 18.18%  |
| Seagate             | 4        | 6      | 12.12%  |
| Kingston            | 3        | 3      | 9.09%   |
| PNY                 | 2        | 3      | 6.06%   |
| Crucial             | 2        | 2      | 6.06%   |
| Corsair             | 2        | 2      | 6.06%   |
| Transcend           | 1        | 1      | 3.03%   |
| SPCC                | 1        | 1      | 3.03%   |
| OCZ                 | 1        | 1      | 3.03%   |
| Micron Technology   | 1        | 1      | 3.03%   |
| MAXTOR              | 1        | 1      | 3.03%   |
| Hitachi             | 1        | 1      | 3.03%   |
| GOODRAM             | 1        | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD          | 3        | 7.32%   |
| Seagate ST2000DM008-2FR102 2TB           | 2        | 4.88%   |
| Corsair MP400 2TB                        | 2        | 4.88%   |
| WDC WDS500G2B0C-00PXH0 500GB             | 1        | 2.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 2.44%   |
| WDC WD60EZRZ-00RWYB1 6TB                 | 1        | 2.44%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1        | 2.44%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1        | 2.44%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1        | 2.44%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 2.44%   |
| WDC WD10EVDS-63U8B1 1TB                  | 1        | 2.44%   |
| Transcend TS128GSSD370S 128GB            | 1        | 2.44%   |
| SPCC Solid State Disk 256GB              | 1        | 2.44%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 2.44%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 2.44%   |
| Seagate ST3360320AS 360GB                | 1        | 2.44%   |
| Samsung SSD 980 PRO 1TB                  | 1        | 2.44%   |
| Samsung SSD 970 PRO 512GB                | 1        | 2.44%   |
| Samsung SSD 870 EVO 500GB                | 1        | 2.44%   |
| Samsung SSD 850 EVO 500GB                | 1        | 2.44%   |
| Samsung SSD 840 Series 120GB             | 1        | 2.44%   |
| Samsung SSD 840 EVO 250GB                | 1        | 2.44%   |
| Samsung MZVPW256HEGL-00000 256GB         | 1        | 2.44%   |
| Samsung MZVLW256HEHP-000L2 256GB         | 1        | 2.44%   |
| Samsung MZVL21T0HCLR-00BL7 1TB           | 1        | 2.44%   |
| Samsung HD501LJ 500GB                    | 1        | 2.44%   |
| Samsung HD204UI 2TB                      | 1        | 2.44%   |
| PNY CS900 250GB SSD                      | 1        | 2.44%   |
| PNY CS3030 1TB SSD                       | 1        | 2.44%   |
| PNY CS2130 2TB SSD                       | 1        | 2.44%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 2.44%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1        | 2.44%   |
| MAXTOR 4K040H2 40GB                      | 1        | 2.44%   |
| Hitachi HDS721050CLA360 500GB            | 1        | 2.44%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 2.44%   |
| Crucial CT500P2SSD8 500GB                | 1        | 2.44%   |
| Crucial CT120BX500SSD1 120GB             | 1        | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 33.33%  |
| Seagate             | 4        | 6      | 33.33%  |
| Samsung Electronics | 2        | 2      | 16.67%  |
| MAXTOR              | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 26.67%  |
| Kingston            | 3        | 3      | 20%     |
| WDC                 | 1        | 1      | 6.67%   |
| Transcend           | 1        | 1      | 6.67%   |
| SPCC                | 1        | 1      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| OCZ                 | 1        | 1      | 6.67%   |
| Micron Technology   | 1        | 1      | 6.67%   |
| GOODRAM             | 1        | 1      | 6.67%   |
| Crucial             | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 11       | 15     | 37.93%  |
| NVMe | 9        | 11     | 31.03%  |
| HDD  | 9        | 17     | 31.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 32     | 60.87%  |
| NVMe | 9        | 11     | 39.13%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 19     | 54.55%  |
| 1.01-2.0   | 3        | 4      | 13.64%  |
| 0.51-1.0   | 3        | 3      | 13.64%  |
| 3.01-4.0   | 2        | 2      | 9.09%   |
| 2.01-3.0   | 1        | 1      | 4.55%   |
| 4.01-10.0  | 1        | 3      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 5        | 33.33%  |
| More than 3000 | 3        | 20%     |
| 1001-2000      | 3        | 20%     |
| 501-1000       | 2        | 13.33%  |
| 2001-3000      | 1        | 6.67%   |
| 101-250        | 1        | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 4        | 26.67%  |
| 1001-2000      | 3        | 20%     |
| 51-100         | 3        | 20%     |
| 101-250        | 2        | 13.33%  |
| 1-20           | 2        | 13.33%  |
| More than 3000 | 1        | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 14.29%  |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 14.29%  |
| Seagate ST3360320AS 360GB                | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 14.29%  |
| MAXTOR 4K040H2 40GB                      | 1        | 1      | 14.29%  |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 2      | 28.57%  |
| Samsung Electronics | 2        | 2      | 28.57%  |
| WDC                 | 1        | 1      | 14.29%  |
| MAXTOR              | 1        | 1      | 14.29%  |
| GOODRAM             | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| MAXTOR  | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 4        | 4      | 66.67%  |
| HDD  | 2        | 3      | 33.33%  |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 13       | 36     | 68.42%  |
| Malfunc | 6        | 7      | 31.58%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 10       | 38.46%  |
| AMD                       | 5        | 19.23%  |
| Samsung Electronics       | 4        | 15.38%  |
| Phison Electronics        | 3        | 11.54%  |
| ASMedia Technology        | 2        | 7.69%   |
| Sandisk                   | 1        | 3.85%   |
| Micron/Crucial Technology | 1        | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Phison E12 NVMe Controller                                                     | 3        | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 10%     |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 6.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 6.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 6.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 6.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 6.67%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 6.67%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 6.67%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1        | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 3.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 3.33%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 3.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 3.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 3.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 3.33%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 3.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 3.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 54.17%  |
| NVMe | 9        | 37.5%   |
| RAID | 1        | 4.17%   |
| IDE  | 1        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 10       | 66.67%  |
| AMD    | 5        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Xeon CPU W3565 @ 3.20GHz             | 1        | 6.67%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz        | 1        | 6.67%   |
| Intel Core i9-10850K CPU @ 3.60GHz         | 1        | 6.67%   |
| Intel Core i7-5820K CPU @ 3.30GHz          | 1        | 6.67%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 1        | 6.67%   |
| Intel Core i5-4690K CPU @ 3.50GHz          | 1        | 6.67%   |
| Intel Core i5-4570T CPU @ 2.90GHz          | 1        | 6.67%   |
| Intel Core i3-4130 CPU @ 3.40GHz           | 1        | 6.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 1        | 6.67%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz       | 1        | 6.67%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores | 1        | 6.67%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 6.67%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 6.67%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 6.67%   |
| AMD Ryzen 3 3100 4-Core Processor          | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 3        | 20%     |
| Intel Xeon             | 2        | 13.33%  |
| Intel Core 2 Duo       | 2        | 13.33%  |
| AMD Ryzen 5            | 2        | 13.33%  |
| Intel Core i9          | 1        | 6.67%   |
| Intel Core i7          | 1        | 6.67%   |
| Intel Core i3          | 1        | 6.67%   |
| AMD Ryzen Threadripper | 1        | 6.67%   |
| AMD Ryzen 7            | 1        | 6.67%   |
| AMD Ryzen 3            | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 4        | 26.67%  |
| 2      | 4        | 26.67%  |
| 4      | 3        | 20%     |
| 12     | 2        | 13.33%  |
| 10     | 1        | 6.67%   |
| 8      | 1        | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 66.67%  |
| 1      | 5        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 15       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 26.67%  |
| 0xa0655    | 1        | 6.67%   |
| 0x906ed    | 1        | 6.67%   |
| 0x6fd      | 1        | 6.67%   |
| 0x306f2    | 1        | 6.67%   |
| 0x306c3    | 1        | 6.67%   |
| 0x1067a    | 1        | 6.67%   |
| 0x0a201016 | 1        | 6.67%   |
| 0x0a201009 | 1        | 6.67%   |
| 0x08701021 | 1        | 6.67%   |
| 0x08301039 | 1        | 6.67%   |
| 0x0800820d | 1        | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Haswell   | 5        | 33.33%  |
| Zen 3     | 2        | 13.33%  |
| Zen 2     | 2        | 13.33%  |
| Zen+      | 1        | 6.67%   |
| Penryn    | 1        | 6.67%   |
| Nehalem   | 1        | 6.67%   |
| KabyLake  | 1        | 6.67%   |
| Core      | 1        | 6.67%   |
| CometLake | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 7        | 41.18%  |
| Nvidia | 6        | 35.29%  |
| Intel  | 4        | 23.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 11.76%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 2        | 11.76%  |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 5.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 5.88%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 5.88%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 5.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 5.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 5.88%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                            | 1        | 5.88%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 5.88%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.88%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 6        | 40%     |
| 1 x AMD     | 6        | 40%     |
| 1 x Intel   | 2        | 13.33%  |
| Intel + AMD | 1        | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 10       | 66.67%  |
| Proprietary | 5        | 33.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 4        | 26.67%  |
| 3.01-4.0   | 4        | 26.67%  |
| Unknown    | 3        | 20%     |
| 8.01-16.0  | 2        | 13.33%  |
| 0.51-1.0   | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 3        | 15.79%  |
| Samsung Electronics  | 2        | 10.53%  |
| Medion               | 2        | 10.53%  |
| Fujitsu Siemens      | 2        | 10.53%  |
| Ancor Communications | 2        | 10.53%  |
| Vizio                | 1        | 5.26%   |
| Philips              | 1        | 5.26%   |
| NEC Computers        | 1        | 5.26%   |
| Iiyama               | 1        | 5.26%   |
| Grundig              | 1        | 5.26%   |
| Gigabyte Technology  | 1        | 5.26%   |
| AOC                  | 1        | 5.26%   |
| Acer                 | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 10.53%  |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1        | 5.26%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 5.26%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch     | 1        | 5.26%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 5.26%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch           | 1        | 5.26%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 1        | 5.26%   |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                     | 1        | 5.26%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch      | 1        | 5.26%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 1        | 5.26%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch      | 1        | 5.26%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                     | 1        | 5.26%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                    | 1        | 5.26%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                    | 1        | 5.26%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 1        | 5.26%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch      | 1        | 5.26%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 5.26%   |
| Acer AL1717 ACRAD54 1280x1024 338x270mm 17.0-inch                     | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 33.33%  |
| 2560x1440 (QHD)    | 4        | 22.22%  |
| 3840x2160 (4K)     | 2        | 11.11%  |
| 3440x1440          | 2        | 11.11%  |
| 1680x1050 (WSXGA+) | 2        | 11.11%  |
| 1920x1200 (WUXGA)  | 1        | 5.56%   |
| 1280x1024 (SXGA)   | 1        | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 22.22%  |
| 31      | 3        | 16.67%  |
| 34      | 2        | 11.11%  |
| 23      | 2        | 11.11%  |
| 22      | 2        | 11.11%  |
| 54      | 1        | 5.56%   |
| 26      | 1        | 5.56%   |
| 24      | 1        | 5.56%   |
| 17      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 44.44%  |
| 601-700     | 3        | 16.67%  |
| 701-800     | 2        | 11.11%  |
| 401-500     | 2        | 11.11%  |
| 301-350     | 1        | 5.56%   |
| 1001-1500   | 1        | 5.56%   |
| Unknown     | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 64.71%  |
| 16/10 | 3        | 17.65%  |
| 21/9  | 2        | 11.76%  |
| 5/4   | 1        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 5        | 27.78%  |
| 301-350        | 4        | 22.22%  |
| 201-250        | 4        | 22.22%  |
| 251-300        | 2        | 11.11%  |
| More than 1000 | 1        | 5.56%   |
| 141-150        | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 75%     |
| 101-120 | 3        | 18.75%  |
| Unknown | 1        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 73.33%  |
| 2     | 3        | 20%     |
| 3     | 1        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 35%     |
| Realtek Semiconductor | 5        | 25%     |
| Qualcomm Atheros      | 2        | 10%     |
| Broadcom              | 2        | 10%     |
| TP-Link               | 1        | 5%      |
| Edimax Technology     | 1        | 5%      |
| Broadcom Limited      | 1        | 5%      |
| Aquantia              | 1        | 5%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 18.18%  |
| Intel I211 Gigabit Network Connection                             | 3        | 13.64%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 4.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 4.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4.55%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 4.55%   |
| Intel Wireless 8260                                               | 1        | 4.55%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.55%   |
| Intel Ethernet Connection I217-V                                  | 1        | 4.55%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 4.55%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 4.55%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 4.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 4.55%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 4.55%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 1        | 16.67%  |
| Realtek Semiconductor | 1        | 16.67%  |
| Intel                 | 1        | 16.67%  |
| Edimax Technology     | 1        | 16.67%  |
| Broadcom Limited      | 1        | 16.67%  |
| Broadcom              | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 16.67%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 16.67%  |
| Intel Wireless 8260                                        | 1        | 16.67%  |
| Edimax RTL8192S WLAN Adapter                               | 1        | 16.67%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 16.67%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 46.67%  |
| Realtek Semiconductor | 4        | 26.67%  |
| Qualcomm Atheros      | 2        | 13.33%  |
| Broadcom              | 1        | 6.67%   |
| Aquantia              | 1        | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 25%     |
| Intel I211 Gigabit Network Connection                             | 3        | 18.75%  |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 6.25%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 6.25%   |
| Intel Ethernet Controller I225-V                                  | 1        | 6.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 6.25%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 6.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 6.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 6.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 71.43%  |
| WiFi     | 6        | 28.57%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 62.5%   |
| WiFi     | 6        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 73.33%  |
| 2     | 3        | 20%     |
| 3     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 53.33%  |
| Yes  | 7        | 46.67%  |

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


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 9        | 33.33%  |
| AMD           | 8        | 29.63%  |
| Nvidia        | 4        | 14.81%  |
| ROCCAT        | 2        | 7.41%   |
| Creative Labs | 2        | 7.41%   |
| Unknown       | 1        | 3.7%    |
| Razer USA     | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3        | 8.82%   |
| AMD Starship/Matisse HD Audio Controller                            | 3        | 8.82%   |
| ROCCAT Khan AIMO                                                    | 2        | 5.88%   |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 5.88%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2        | 5.88%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]       | 2        | 5.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 2        | 5.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2        | 5.88%   |
| Unknown Realtek USB Audio Rear                                      | 1        | 2.94%   |
| Unknown Realtek USB Audio Front                                     | 1        | 2.94%   |
| Razer USA Razer Kraken Tournament Edition                           | 1        | 2.94%   |
| Nvidia TU104 HD Audio Controller                                    | 1        | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 2.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 2.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1        | 2.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 2.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                 | 1        | 2.94%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]               | 1        | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 2.94%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]              | 1        | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 5        | 35.71%  |
| G.Skill             | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| Kingston            | 2        | 14.29%  |
| Unknown             | 1        | 7.14%   |
| SK Hynix            | 1        | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s | 2        | 14.29%  |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                  | 1        | 7.14%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1        | 7.14%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s      | 1        | 7.14%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s      | 1        | 7.14%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s      | 1        | 7.14%   |
| Kingston RAM 99U5471-033.A00LF 4096MB DIMM DDR3           | 1        | 7.14%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s     | 1        | 7.14%   |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s        | 1        | 7.14%   |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s   | 1        | 7.14%   |
| Corsair RAM CMK32GX4M4A2666C16 8192MB DIMM 2667MT/s       | 1        | 7.14%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s  | 1        | 7.14%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s     | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 9        | 64.29%  |
| DDR3 | 4        | 28.57%  |
| DDR2 | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 92.86%  |
| SODIMM | 1        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 28.57%  |
| 4096  | 4        | 28.57%  |
| 16384 | 3        | 21.43%  |
| 32768 | 2        | 14.29%  |
| 2048  | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2133  | 3        | 21.43%  |
| 3600  | 2        | 14.29%  |
| 3400  | 2        | 14.29%  |
| 1600  | 2        | 14.29%  |
| 3466  | 1        | 7.14%   |
| 3200  | 1        | 7.14%   |
| 2667  | 1        | 7.14%   |
| 1400  | 1        | 7.14%   |
| 333   | 1        | 7.14%   |

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
| Logitech               | 3        | 75%     |
| Generalplus Technology | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Logitech Webcam C930e      | 2        | 50%     |
| Logitech Webcam C270       | 1        | 25%     |
| Generalplus GENERAL WEBCAM | 1        | 25%     |

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
| 0     | 13       | 86.67%  |
| 1     | 2        | 13.33%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 2        | 100%    |

