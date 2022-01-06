Elementary 6.1 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

| Vendor   | Model                 | Probe                                                      | Date         |
|----------|-----------------------|------------------------------------------------------------|--------------|
| ASRock   | B450M-HDV R4.0        | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Gigabyte | B85M-DS3H-A           | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI      | 2A9C                  | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP       | 3397                  | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek  | X79-DELUXE            | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP       | 1589                  | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn  | 2AB1                  | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte | Z390 UD               | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| Apple    | Mac-F42C88C8 Proto1   | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek  | H97-PLUS              | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI      | B450-A PRO MAX        | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte | H310M S2P             | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn  | 2AB1                  | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn  | 2AB1                  | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte | Z590 AORUS ELITE AX   | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek  | M5A78L-M LX3          | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-43-generic    | 8        | 53.33%  |
| 5.11.0-41-generic    | 4        | 26.67%  |
| 5.13.0-22-generic    | 1        | 6.67%   |
| 5.11.0-43-lowlatency | 1        | 6.67%   |
| 5.11.0-37-generic    | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 14       | 93.33%  |
| 5.13.0  | 1        | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 14       | 93.33%  |
| 5.13    | 1        | 6.67%   |

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


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 15       | 100%    |

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
| Unknown | 12       | 80%     |
| LightDM | 3        | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 8        | 53.33%  |
| de_DE | 2        | 13.33%  |
| ru_RU | 1        | 6.67%   |
| fr_FR | 1        | 6.67%   |
| es_ES | 1        | 6.67%   |
| en_GB | 1        | 6.67%   |
| en_CA | 1        | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 9        | 60%     |
| BIOS | 6        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 14       | 93.33%  |
| Xfs  | 1        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 93.33%  |
| GPT     | 1        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 4        | 26.67%  |
| ASUSTek Computer    | 4        | 26.67%  |
| MSI                 | 2        | 13.33%  |
| Hewlett-Packard     | 2        | 13.33%  |
| Foxconn             | 1        | 6.67%   |
| ASRock              | 1        | 6.67%   |
| Apple               | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| MSI PPPPP-CCC#MMMMMMMM       | 1        | 6.67%   |
| MSI MS-7B86                  | 1        | 6.67%   |
| HP Z420 Workstation          | 1        | 6.67%   |
| HP Compaq Elite 8300 SFF     | 1        | 6.67%   |
| Gigabyte Z590 AORUS ELITE AX | 1        | 6.67%   |
| Gigabyte Z390 UD             | 1        | 6.67%   |
| Gigabyte H310M S2P 2.0       | 1        | 6.67%   |
| Gigabyte B85M-DS3H-A         | 1        | 6.67%   |
| Foxconn p6616f               | 1        | 6.67%   |
| ASUS X79-DELUXE              | 1        | 6.67%   |
| ASUS TUF GAMING B550M-PLUS   | 1        | 6.67%   |
| ASUS M5A78L-M LX3            | 1        | 6.67%   |
| ASUS All Series              | 1        | 6.67%   |
| ASRock B450M-HDV R4.0        | 1        | 6.67%   |
| Apple MacPro3,1              | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| MSI PPPPP-CCC#MMMMMMMM | 1        | 6.67%   |
| MSI MS-7B86            | 1        | 6.67%   |
| HP Z420                | 1        | 6.67%   |
| HP Compaq              | 1        | 6.67%   |
| Gigabyte Z590          | 1        | 6.67%   |
| Gigabyte Z390          | 1        | 6.67%   |
| Gigabyte H310M         | 1        | 6.67%   |
| Gigabyte B85M-DS3H-A   | 1        | 6.67%   |
| Foxconn p6616f         | 1        | 6.67%   |
| ASUS X79-DELUXE        | 1        | 6.67%   |
| ASUS TUF               | 1        | 6.67%   |
| ASUS M5A78L-M          | 1        | 6.67%   |
| ASUS All               | 1        | 6.67%   |
| ASRock B450M-HDV       | 1        | 6.67%   |
| Apple MacPro3          | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 20%     |
| 2016 | 3        | 20%     |
| 2019 | 2        | 13.33%  |
| 2010 | 2        | 13.33%  |
| 2021 | 1        | 6.67%   |
| 2018 | 1        | 6.67%   |
| 2015 | 1        | 6.67%   |
| 2012 | 1        | 6.67%   |
| 2008 | 1        | 6.67%   |

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


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 32.01-64.0 | 7        | 46.67%  |
| 16.01-24.0 | 4        | 26.67%  |
| 8.01-16.0  | 2        | 13.33%  |
| 4.01-8.0   | 1        | 6.67%   |
| 3.01-4.0   | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 5        | 33.33%  |
| 4.01-8.0  | 4        | 26.67%  |
| 2.01-3.0  | 3        | 20%     |
| 3.01-4.0  | 2        | 13.33%  |
| 8.01-16.0 | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 33.33%  |
| 4      | 3        | 20%     |
| 1      | 3        | 20%     |
| 3      | 2        | 13.33%  |
| 7      | 1        | 6.67%   |
| 5      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 53.33%  |
| Yes       | 7        | 46.67%  |

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
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 2        | 13.33%  |
| Germany      | 2        | 13.33%  |
| UK           | 1        | 6.67%   |
| Thailand     | 1        | 6.67%   |
| Sweden       | 1        | 6.67%   |
| Sri Lanka    | 1        | 6.67%   |
| Spain        | 1        | 6.67%   |
| South Africa | 1        | 6.67%   |
| Russia       | 1        | 6.67%   |
| Iran         | 1        | 6.67%   |
| France       | 1        | 6.67%   |
| Canada       | 1        | 6.67%   |
| Argentina    | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Wattala               | 1        | 6.67%   |
| Vilanova i la Geltr?? | 1        | 6.67%   |
| Uppsala               | 1        | 6.67%   |
| Tehran                | 1        | 6.67%   |
| Southampton           | 1        | 6.67%   |
| Sornay                | 1        | 6.67%   |
| Rueso                 | 1        | 6.67%   |
| La Plata              | 1        | 6.67%   |
| Khimki                | 1        | 6.67%   |
| Johannesburg          | 1        | 6.67%   |
| Hennef                | 1        | 6.67%   |
| Hamburg               | 1        | 6.67%   |
| Edmonton              | 1        | 6.67%   |
| Denver                | 1        | 6.67%   |
| Bergenfield           | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 7      | 22.58%  |
| Samsung Electronics | 7        | 8      | 22.58%  |
| WDC                 | 6        | 11     | 19.35%  |
| Toshiba             | 2        | 3      | 6.45%   |
| Crucial             | 2        | 2      | 6.45%   |
| Unknown             | 1        | 3      | 3.23%   |
| MAXTOR              | 1        | 1      | 3.23%   |
| Kingston            | 1        | 1      | 3.23%   |
| JMicron             | 1        | 1      | 3.23%   |
| Intenso             | 1        | 1      | 3.23%   |
| Intel               | 1        | 1      | 3.23%   |
| A-DATA Technology   | 1        | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB      | 2        | 5.26%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 2.63%   |
| WDC WD6401AALS-00L3B2 640GB       | 1        | 2.63%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 1        | 2.63%   |
| WDC WD3003FZEX-00Z4SA0 3TB        | 1        | 2.63%   |
| WDC WD20EFRX-68EUZN0 2TB          | 1        | 2.63%   |
| WDC WD15EARX-00PASB0 1TB          | 1        | 2.63%   |
| WDC WD10EZEX-08WN4A0 1TB          | 1        | 2.63%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 2.63%   |
| WDC WD10EADS-00L5B1 1TB           | 1        | 2.63%   |
| Unknown SD/MMC/M.S.PRO 32GB       | 1        | 2.63%   |
| Unknown SD/MMC 16GB               | 1        | 2.63%   |
| Unknown M.S./M.S.Pro/HG 16GB      | 1        | 2.63%   |
| Toshiba HDWE140 4TB               | 1        | 2.63%   |
| Toshiba HDWD120 2TB               | 1        | 2.63%   |
| Toshiba HDWD110 1TB               | 1        | 2.63%   |
| Seagate ST4000DX001-1CE168 4TB    | 1        | 2.63%   |
| Seagate ST3750528AS 752GB         | 1        | 2.63%   |
| Seagate ST2000DX002-2DV164 2TB    | 1        | 2.63%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB    | 1        | 2.63%   |
| Seagate ST10000DM0004-1ZC101 10TB | 1        | 2.63%   |
| Seagate NVMe SSD Drive 500GB      | 1        | 2.63%   |
| Samsung SSD 870 QVO 2TB           | 1        | 2.63%   |
| Samsung SSD 870 QVO 1TB           | 1        | 2.63%   |
| Samsung SSD 860 EVO M.2 250GB     | 1        | 2.63%   |
| Samsung SSD 860 EVO 1TB           | 1        | 2.63%   |
| Samsung NVMe SSD Drive 512GB      | 1        | 2.63%   |
| Samsung HD322HJ 320GB             | 1        | 2.63%   |
| MAXTOR Z1 SSD 240GB               | 1        | 2.63%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 2.63%   |
| JMicron Tech 250GB                | 1        | 2.63%   |
| Intenso SSD SATAIII 128GB         | 1        | 2.63%   |
| Intel NVMe SSD Drive 512GB        | 1        | 2.63%   |
| Crucial CT525MX300SSD1 528GB      | 1        | 2.63%   |
| Crucial CT1000MX500SSD1 1TB       | 1        | 2.63%   |
| A-DATA SWORDFISH 250GB            | 1        | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 6      | 42.86%  |
| WDC                 | 5        | 9      | 35.71%  |
| Toshiba             | 2        | 3      | 14.29%  |
| Samsung Electronics | 1        | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 40%     |
| Crucial             | 2        | 2      | 20%     |
| WDC                 | 1        | 2      | 10%     |
| MAXTOR              | 1        | 1      | 10%     |
| Kingston            | 1        | 1      | 10%     |
| Intenso             | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 11       | 19     | 39.29%  |
| SSD     | 10       | 11     | 35.71%  |
| NVMe    | 5        | 6      | 17.86%  |
| Unknown | 2        | 4      | 7.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 30     | 66.67%  |
| NVMe | 5        | 6      | 23.81%  |
| SAS  | 2        | 4      | 9.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 8        | 13     | 38.1%   |
| 0.01-0.5   | 5        | 7      | 23.81%  |
| 3.01-4.0   | 3        | 3      | 14.29%  |
| 1.01-2.0   | 3        | 4      | 14.29%  |
| 2.01-3.0   | 1        | 2      | 4.76%   |
| 4.01-10.0  | 1        | 1      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 4        | 26.67%  |
| 251-500        | 4        | 26.67%  |
| 501-1000       | 3        | 20%     |
| 101-250        | 2        | 13.33%  |
| 21-50          | 1        | 6.67%   |
| 1001-2000      | 1        | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 3        | 20%     |
| 1-20           | 3        | 20%     |
| 101-250        | 2        | 13.33%  |
| 1001-2000      | 2        | 13.33%  |
| 51-100         | 2        | 13.33%  |
| More than 3000 | 1        | 6.67%   |
| 251-500        | 1        | 6.67%   |
| 501-1000       | 1        | 6.67%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 14       | 38     | 93.33%  |
| Works    | 1        | 2      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 45.45%  |
| AMD                      | 5        | 22.73%  |
| Samsung Electronics      | 3        | 13.64%  |
| Seagate Technology       | 1        | 4.55%   |
| Realtek Semiconductor    | 1        | 4.55%   |
| Marvell Technology Group | 1        | 4.55%   |
| ASMedia Technology       | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 6.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 6.9%    |
| Seagate Non-Volatile memory controller                                         | 1        | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 3.45%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 3.45%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 3.45%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller          | 1        | 3.45%   |
| Intel SSD 660P Series                                                          | 1        | 3.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 3.45%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 3.45%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 3.45%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1        | 3.45%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1        | 3.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 3.45%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                     | 1        | 3.45%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 3.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 3.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 3.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 3.45%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 14       | 58.33%  |
| NVMe | 5        | 20.83%  |
| IDE  | 3        | 12.5%   |
| RAID | 1        | 4.17%   |
| SAS  | 1        | 4.17%   |

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


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel Xeon CPU E5462 @ 2.80GHz          | 1        | 6.67%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1        | 6.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1        | 6.67%   |
| Intel Core i7-4930K CPU @ 3.40GHz       | 1        | 6.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 1        | 6.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 1        | 6.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 1        | 6.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1        | 6.67%   |
| Intel Core i3 CPU 550 @ 3.20GHz         | 1        | 6.67%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 1        | 6.67%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 1        | 6.67%   |
| AMD Ryzen 5 3600 6-Core Processor       | 1        | 6.67%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 1        | 6.67%   |
| AMD Phenom II X4 B55 Processor          | 1        | 6.67%   |
| AMD Phenom II X4 820 Processor          | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i7    | 4        | 26.67%  |
| Intel Xeon       | 2        | 13.33%  |
| Intel Core i5    | 2        | 13.33%  |
| AMD Ryzen 5      | 2        | 13.33%  |
| AMD Phenom II X4 | 2        | 13.33%  |
| Other            | 1        | 6.67%   |
| Intel Core i3    | 1        | 6.67%   |
| AMD Ryzen 7      | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 5        | 33.33%  |
| 4      | 5        | 33.33%  |
| 6      | 4        | 26.67%  |
| 2      | 1        | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 93.33%  |
| 2      | 1        | 6.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 60%     |
| 1      | 6        | 40%     |

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
| 0x306c3    | 2        | 13.33%  |
| 0xa0671    | 1        | 6.67%   |
| 0x906ec    | 1        | 6.67%   |
| 0x906ea    | 1        | 6.67%   |
| 0x306e4    | 1        | 6.67%   |
| 0x306a9    | 1        | 6.67%   |
| 0x206d7    | 1        | 6.67%   |
| 0x20655    | 1        | 6.67%   |
| 0x10676    | 1        | 6.67%   |
| 0x0a201009 | 1        | 6.67%   |
| 0x08701021 | 1        | 6.67%   |
| 0x0800820d | 1        | 6.67%   |
| 0x010000db | 1        | 6.67%   |
| 0x010000c8 | 1        | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 2        | 13.33%  |
| K10         | 2        | 13.33%  |
| IvyBridge   | 2        | 13.33%  |
| Haswell     | 2        | 13.33%  |
| Zen+        | 1        | 6.67%   |
| Zen 3       | 1        | 6.67%   |
| Zen 2       | 1        | 6.67%   |
| Westmere    | 1        | 6.67%   |
| SandyBridge | 1        | 6.67%   |
| Penryn      | 1        | 6.67%   |
| Icelake     | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 56.25%  |
| AMD    | 4        | 25%     |
| Intel  | 3        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 11.76%  |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 5.88%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 5.88%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 5.88%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 5.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 5.88%   |
| Nvidia GF119 [GeForce GT 625 OEM]                                           | 1        | 5.88%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.88%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 5.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 5.88%   |
| AMD RV630 XT [Radeon HD 2600 XT]                                            | 1        | 5.88%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 5.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.88%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 9        | 60%     |
| 1 x AMD    | 3        | 20%     |
| 1 x Intel  | 2        | 13.33%  |
| 2 x AMD    | 1        | 6.67%   |

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
| 3.01-4.0   | 5        | 33.33%  |
| 7.01-8.0   | 2        | 13.33%  |
| 0.51-1.0   | 2        | 13.33%  |
| Unknown    | 2        | 13.33%  |
| 5.01-6.0   | 1        | 6.67%   |
| 2.01-3.0   | 1        | 6.67%   |
| 1.01-2.0   | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 16.67%  |
| Goldstar            | 3        | 16.67%  |
| Samsung Electronics | 2        | 11.11%  |
| Acer                | 2        | 11.11%  |
| Philips             | 1        | 5.56%   |
| Iiyama              | 1        | 5.56%   |
| HPN                 | 1        | 5.56%   |
| Eizo                | 1        | 5.56%   |
| CHD                 | 1        | 5.56%   |
| AUS                 | 1        | 5.56%   |
| AOC                 | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch | 1        | 5%      |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch | 1        | 5%      |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch | 1        | 5%      |
| Philips LCD Monitor PHL 276E8V 7680x2160                             | 1        | 5%      |
| Philips LCD Monitor PHL 276E8V                                       | 1        | 5%      |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch               | 1        | 5%      |
| HPN LCD Monitor HP 27fw 1920x1080                                    | 1        | 5%      |
| Hewlett-Packard LCD Monitor w17e 1440x900                            | 1        | 5%      |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch           | 1        | 5%      |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch            | 1        | 5%      |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                   | 1        | 5%      |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 1        | 5%      |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 5%      |
| Eizo EV2455 ENC2533 1920x1200 519x324mm 24.1-inch                    | 1        | 5%      |
| CHD GDM-225JN CHD0220 1920x1080 490x270mm 22.0-inch                  | 1        | 5%      |
| AUS LCD Monitor VG27AQL1A 2560x1440                                  | 1        | 5%      |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                      | 1        | 5%      |
| Acer XV272U ACR06C1 2560x1440 597x336mm 27.0-inch                    | 1        | 5%      |
| Acer V233H ACR0090 1920x1080 510x287mm 23.0-inch                     | 1        | 5%      |
| Unknown                                                              | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 6        | 31.58%  |
| 2560x1440 (QHD)   | 4        | 21.05%  |
| 1600x900 (HD+)    | 2        | 10.53%  |
| 7680x2160         | 1        | 5.26%   |
| 3840x2160 (4K)    | 1        | 5.26%   |
| 1920x1200 (WUXGA) | 1        | 5.26%   |
| 1440x900 (WXGA+)  | 1        | 5.26%   |
| 1366x768 (WXGA)   | 1        | 5.26%   |
| 1360x768          | 1        | 5.26%   |
| Unknown           | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 5        | 27.78%  |
| 24      | 4        | 22.22%  |
| 27      | 2        | 11.11%  |
| 21      | 2        | 11.11%  |
| 20      | 2        | 11.11%  |
| 31      | 1        | 5.56%   |
| 23      | 1        | 5.56%   |
| 22      | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 31.25%  |
| Unknown     | 5        | 31.25%  |
| 401-500     | 4        | 25%     |
| 601-700     | 2        | 12.5%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 50%     |
| Unknown | 5        | 31.25%  |
| 16/10   | 3        | 18.75%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 27.78%  |
| Unknown        | 5        | 27.78%  |
| 251-300        | 3        | 16.67%  |
| 301-350        | 2        | 11.11%  |
| 151-200        | 2        | 11.11%  |
| 351-500        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 52.94%  |
| Unknown | 5        | 29.41%  |
| 101-120 | 3        | 17.65%  |

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
| Realtek Semiconductor | 12       | 54.55%  |
| Intel                 | 6        | 27.27%  |
| Ralink Technology     | 1        | 4.55%   |
| Ralink                | 1        | 4.55%   |
| Qualcomm Atheros      | 1        | 4.55%   |
| Broadcom              | 1        | 4.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 34.78%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 8.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.35%   |
| Realtek 802.11ac NIC                                              | 1        | 4.35%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 4.35%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 4.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 4.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 4.35%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 4.35%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 4.35%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 4.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 28.57%  |
| Intel                 | 2        | 28.57%  |
| Ralink Technology     | 1        | 14.29%  |
| Ralink                | 1        | 14.29%  |
| Broadcom              | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter | 1        | 14.29%  |
| Realtek 802.11ac NIC                                     | 1        | 14.29%  |
| Ralink MT7601U Wireless Adapter                          | 1        | 14.29%  |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                | 1        | 14.29%  |
| Intel Wi-Fi 6 AX200                                      | 1        | 14.29%  |
| Intel Tiger Lake PCH CNVi WiFi                           | 1        | 14.29%  |
| Broadcom BCM4352 802.11ac Wireless Network Adapter       | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 68.75%  |
| Intel                 | 4        | 25%     |
| Qualcomm Atheros      | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 50%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 6.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 6.25%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 6.25%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 6.25%   |

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
| Ethernet | 15       | 71.43%  |
| WiFi     | 6        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 60%     |
| 2     | 5        | 33.33%  |
| 3     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 66.67%  |
| Yes  | 5        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 33.33%  |
| Cambridge Silicon Radio | 2        | 33.33%  |
| ASUSTek Computer        | 1        | 16.67%  |
| Apple                   | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 33.33%  |
| Intel Bluetooth Device                              | 1        | 16.67%  |
| Intel AX200 Bluetooth                               | 1        | 16.67%  |
| ASUS BCM20702A0                                     | 1        | 16.67%  |
| Apple Bluetooth HCI                                 | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Nvidia              | 9        | 33.33%  |
| Intel               | 9        | 33.33%  |
| AMD                 | 6        | 22.22%  |
| Focusrite-Novation  | 1        | 3.7%    |
| Creative Labs       | 1        | 3.7%    |
| C-Media Electronics | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 2        | 6.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller      | 2        | 6.67%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 2        | 6.67%   |
| Nvidia TU116 High Definition Audio Controller                       | 1        | 3.33%   |
| Nvidia TU104 HD Audio Controller                                    | 1        | 3.33%   |
| Nvidia GP106 High Definition Audio Controller                       | 1        | 3.33%   |
| Nvidia GM204 High Definition Audio Controller                       | 1        | 3.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1        | 3.33%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1        | 3.33%   |
| Nvidia GF108 High Definition Audio Controller                       | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1        | 3.33%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1        | 3.33%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 3.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1        | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1        | 3.33%   |
| Intel 631xESB/632xESB High Definition Audio Controller              | 1        | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 1        | 3.33%   |
| Intel 200 Series PCH HD Audio                                       | 1        | 3.33%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                   | 1        | 3.33%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]          | 1        | 3.33%   |
| C-Media Electronics USB Audio Device                                | 1        | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                            | 1        | 3.33%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1        | 3.33%   |
| AMD Navi 10 HDMI Audio                                              | 1        | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 3.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1        | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| PNY    | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 1        | 100%    |

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


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 25%     |
| Microdia  | 1        | 25%     |
| Logitech  | 1        | 25%     |
| Apple     | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microsoft LifeCam VX-800        | 1        | 25%     |
| Microdia USB 2.0 Camera         | 1        | 25%     |
| Logitech BRIO 4K Stream Edition | 1        | 25%     |
| Apple iPhone 5/5C/5S/6/SE       | 1        | 25%     |

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
| 0     | 14       | 93.33%  |
| 1     | 1        | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 100%    |

