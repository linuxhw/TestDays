Elementary 6 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=elementary-6

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte | B450M DS3H V2               | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| ASUSTek  | ROG STRIX Z590-F GAMING ... | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Gigabyte | F2A55M-HD2                  | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| ASRock   | H81TM-ITX R2.0              | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| ASUSTek  | M5A78L-M LX/BR              | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| ASUSTek  | P6X58D-E                    | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| MSI      | X470 GAMING PLUS MAX        | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| ASUSTek  | TUF GAMING B450M-PRO II     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Gigabyte | X570 I AORUS PRO WIFI       | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Gigabyte | H310M M.2 x.x               | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte | H310M M.2 x.x               | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| ASUSTek  | P5KPL-AM SE                 | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| ASRock   | B450 Pro4                   | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| ASUSTek  | ROG STRIX B450-I GAMING     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| ASUSTek  | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP       | 8433 11                     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.11.0-27-generic | 6        | 37.5%   |
| 5.8.0-50-generic  | 3        | 18.75%  |
| 5.11.0-25-generic | 3        | 18.75%  |
| 5.8.0-63-generic  | 1        | 6.25%   |
| 5.8.0-55-generic  | 1        | 6.25%   |
| 5.4.0-58-generic  | 1        | 6.25%   |
| 5.4.0-56-generic  | 1        | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 9        | 56.25%  |
| 5.8.0   | 5        | 31.25%  |
| 5.4.0   | 2        | 12.5%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 9        | 56.25%  |
| 5.8     | 5        | 31.25%  |
| 5.4     | 2        | 12.5%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 13       | 81.25%  |
| MATE     | 1        | 6.25%   |
| GNOME    | 1        | 6.25%   |
| Unknown  | 1        | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 16       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 81.25%  |
| TDM     | 3        | 18.75%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 43.75%  |
| de_DE | 3        | 18.75%  |
| es_ES | 2        | 12.5%   |
| pt_BR | 1        | 6.25%   |
| it_IT | 1        | 6.25%   |
| es_MX | 1        | 6.25%   |
| en_GB | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 9        | 56.25%  |
| BIOS | 7        | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 15       | 93.75%  |
| Btrfs | 1        | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 81.25%  |
| GPT     | 2        | 12.5%   |
| MBR     | 1        | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 87.5%   |
| Yes       | 2        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 50%     |
| Gigabyte Technology | 4        | 25%     |
| ASRock              | 2        | 12.5%   |
| MSI                 | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7B79                       | 1        | 6.25%   |
| HP Pavilion Desktop 590-p0xxx     | 1        | 6.25%   |
| Gigabyte X570 I AORUS PRO WIFI    | 1        | 6.25%   |
| Gigabyte H310M M.2 2.0            | 1        | 6.25%   |
| Gigabyte F2A55M-HD2               | 1        | 6.25%   |
| Gigabyte B450M DS3H V2            | 1        | 6.25%   |
| ASUS TUF GAMING B550M-PLUS        | 1        | 6.25%   |
| ASUS TUF GAMING B450M-PRO II      | 1        | 6.25%   |
| ASUS ROG STRIX Z590-F GAMING WIFI | 1        | 6.25%   |
| ASUS ROG STRIX B450-I GAMING      | 1        | 6.25%   |
| ASUS P6X58D-E                     | 1        | 6.25%   |
| ASUS P5KPL-AM SE                  | 1        | 6.25%   |
| ASUS M5A99X EVO R2.0              | 1        | 6.25%   |
| ASUS M5A78L-M LX/BR               | 1        | 6.25%   |
| ASRock H81TM-ITX R2.0             | 1        | 6.25%   |
| ASRock B450 Pro4                  | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS TUF            | 2        | 12.5%   |
| ASUS ROG            | 2        | 12.5%   |
| MSI MS-7B79         | 1        | 6.25%   |
| HP Pavilion         | 1        | 6.25%   |
| Gigabyte X570       | 1        | 6.25%   |
| Gigabyte H310M      | 1        | 6.25%   |
| Gigabyte F2A55M-HD2 | 1        | 6.25%   |
| Gigabyte B450M      | 1        | 6.25%   |
| ASUS P6X58D-E       | 1        | 6.25%   |
| ASUS P5KPL-AM       | 1        | 6.25%   |
| ASUS M5A99X         | 1        | 6.25%   |
| ASUS M5A78L-M       | 1        | 6.25%   |
| ASRock H81TM-ITX    | 1        | 6.25%   |
| ASRock B450         | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 5        | 31.25%  |
| 2019 | 3        | 18.75%  |
| 2013 | 3        | 18.75%  |
| 2020 | 2        | 12.5%   |
| 2015 | 1        | 6.25%   |
| 2012 | 1        | 6.25%   |
| 2009 | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 14       | 87.5%   |
| Enabled  | 2        | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 32.01-64.0 | 6        | 37.5%   |
| 16.01-24.0 | 4        | 25%     |
| 4.01-8.0   | 3        | 18.75%  |
| 3.01-4.0   | 2        | 12.5%   |
| 8.01-16.0  | 1        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 7        | 43.75%  |
| 1.01-2.0  | 5        | 31.25%  |
| 3.01-4.0  | 2        | 12.5%   |
| 4.01-8.0  | 1        | 6.25%   |
| 8.01-16.0 | 1        | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 43.75%  |
| 2      | 5        | 31.25%  |
| 3      | 2        | 12.5%   |
| 5      | 1        | 6.25%   |
| 4      | 1        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 87.5%   |
| Yes       | 2        | 12.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| UK          | 2        | 12.5%   |
| Germany     | 2        | 12.5%   |
| Argentina   | 2        | 12.5%   |
| USA         | 1        | 6.25%   |
| Russia      | 1        | 6.25%   |
| Netherlands | 1        | 6.25%   |
| Mexico      | 1        | 6.25%   |
| Italy       | 1        | 6.25%   |
| Indonesia   | 1        | 6.25%   |
| Finland     | 1        | 6.25%   |
| Czechia     | 1        | 6.25%   |
| Brazil      | 1        | 6.25%   |
| Austria     | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Znojmo         | 1        | 6.25%   |
| Vienna         | 1        | 6.25%   |
| Staropyshminsk | 1        | 6.25%   |
| S??o Paulo     | 1        | 6.25%   |
| Rosario        | 1        | 6.25%   |
| Roermond       | 1        | 6.25%   |
| Rheinberg      | 1        | 6.25%   |
| Potsdam        | 1        | 6.25%   |
| Morelia        | 1        | 6.25%   |
| Milan          | 1        | 6.25%   |
| Medan          | 1        | 6.25%   |
| Klaukkala      | 1        | 6.25%   |
| Hephzibah      | 1        | 6.25%   |
| Bonnybridge    | 1        | 6.25%   |
| Berazategui    | 1        | 6.25%   |
| Bathgate       | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 5        | 7      | 20%     |
| Samsung Electronics       | 5        | 9      | 20%     |
| Kingston                  | 4        | 4      | 16%     |
| SanDisk                   | 3        | 3      | 12%     |
| Seagate                   | 2        | 2      | 8%      |
| USB3.1                    | 1        | 1      | 4%      |
| Phison                    | 1        | 1      | 4%      |
| OCZ                       | 1        | 1      | 4%      |
| Micron/Crucial Technology | 1        | 2      | 4%      |
| Micron Technology         | 1        | 1      | 4%      |
| Gigabyte Technology       | 1        | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD   | 2        | 6.45%   |
| WDC WD5000AAKX-001CA0 500GB       | 1        | 3.23%   |
| WDC WD3200AAJS-56B4A0 320GB       | 1        | 3.23%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 3.23%   |
| WDC WD10EZRX-00L4HB0 1TB          | 1        | 3.23%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 3.23%   |
| WDC WD10EZEX-00RKKA0 1TB          | 1        | 3.23%   |
| WDC WD10EZEX-00KUWA0 1TB          | 1        | 3.23%   |
| USB3.1 Disk 500GB                 | 1        | 3.23%   |
| Seagate ST940210AS 40GB           | 1        | 3.23%   |
| Seagate NVMe SSD Drive 2TB        | 1        | 3.23%   |
| SanDisk SDSSDA-1T00 1TB           | 1        | 3.23%   |
| Sandisk NVMe SSD Drive 500GB      | 1        | 3.23%   |
| Sandisk NVMe SSD Drive 1TB        | 1        | 3.23%   |
| Samsung SSD 980 PRO 1TB           | 1        | 3.23%   |
| Samsung SSD 960 EVO 500GB         | 1        | 3.23%   |
| Samsung SSD 870 QVO 1TB           | 1        | 3.23%   |
| Samsung SSD 850 EVO 250GB         | 1        | 3.23%   |
| Samsung SSD 840 Series 500GB      | 1        | 3.23%   |
| Samsung Portable SSD T5 500GB     | 1        | 3.23%   |
| Samsung NVMe SSD Drive 500GB      | 1        | 3.23%   |
| Samsung NVMe SSD Drive 1TB        | 1        | 3.23%   |
| Samsung HD154UI 1TB               | 1        | 3.23%   |
| Phison NVMe SSD Drive 256GB       | 1        | 3.23%   |
| OCZ AGILITY3 240GB SSD            | 1        | 3.23%   |
| Micron/Crucial NVMe SSD Drive 1TB | 1        | 3.23%   |
| Micron NVMe SSD Drive 500GB       | 1        | 3.23%   |
| Kingston NVMe SSD Drive 500GB     | 1        | 3.23%   |
| Kingston NVMe SSD Drive 1TB       | 1        | 3.23%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB  | 1        | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 7      | 71.43%  |
| Seagate             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 42.86%  |
| Kingston            | 2        | 2      | 28.57%  |
| SanDisk             | 1        | 1      | 14.29%  |
| OCZ                 | 1        | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 8        | 14     | 36.36%  |
| HDD     | 7        | 9      | 31.82%  |
| SSD     | 6        | 8      | 27.27%  |
| Unknown | 1        | 1      | 4.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 16     | 55%     |
| NVMe | 8        | 14     | 40%     |
| SAS  | 1        | 2      | 5%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 9      | 60%     |
| 0.51-1.0   | 5        | 7      | 33.33%  |
| 1.01-2.0   | 1        | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 7        | 43.75%  |
| 101-250    | 5        | 31.25%  |
| 21-50      | 2        | 12.5%   |
| 1001-2000  | 1        | 6.25%   |
| 501-1000   | 1        | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 11       | 68.75%  |
| 101-250 | 2        | 12.5%   |
| 51-100  | 2        | 12.5%   |
| 21-50   | 1        | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD3200AAJS-56B4A0 320GB | 1        | 1      | 50%     |
| WDC WD10EZEX-00KUWA0 1TB    | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Detected | 13       | 22     | 68.42%  |
| Works    | 4        | 8      | 21.05%  |
| Malfunc  | 2        | 2      | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 10       | 34.48%  |
| Intel                       | 5        | 17.24%  |
| Samsung Electronics         | 3        | 10.34%  |
| Sandisk                     | 2        | 6.9%    |
| Kingston Technology Company | 2        | 6.9%    |
| ASMedia Technology          | 2        | 6.9%    |
| Seagate Technology          | 1        | 3.45%   |
| Phison Electronics          | 1        | 3.45%   |
| Micron/Crucial Technology   | 1        | 3.45%   |
| Micron Technology           | 1        | 3.45%   |
| Marvell Technology Group    | 1        | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 15.38%  |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 10.26%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 5.13%   |
| Kingston Company A2000 NVMe SSD                                                | 2        | 5.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 5.13%   |
| Seagate FireCuda 510 SSD                                                       | 1        | 2.56%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1        | 2.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.56%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 2.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 2.56%   |
| Micron Non-Volatile memory controller                                          | 1        | 2.56%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                     | 1        | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 2.56%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 2.56%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 2.56%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 2.56%   |
| AMD FCH IDE Controller                                                         | 1        | 2.56%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 52%     |
| NVMe | 8        | 32%     |
| IDE  | 4        | 16%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 11       | 68.75%  |
| Intel  | 5        | 31.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 4        | 25%     |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 12.5%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 6.25%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 6.25%   |
| Intel Core 2 Quad CPU Q9500 @ 2.83GHz          | 1        | 6.25%   |
| Intel Celeron G4930 CPU @ 3.20GHz              | 1        | 6.25%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 1        | 6.25%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 1        | 6.25%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 6.25%   |
| AMD FX-6100 Six-Core Processor                 | 1        | 6.25%   |
| AMD A4-4000 APU with Radeon HD Graphics        | 1        | 6.25%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 7       | 4        | 25%     |
| AMD Ryzen 5       | 3        | 18.75%  |
| AMD FX            | 2        | 12.5%   |
| Other             | 1        | 6.25%   |
| Intel Core i7     | 1        | 6.25%   |
| Intel Core i5     | 1        | 6.25%   |
| Intel Core 2 Quad | 1        | 6.25%   |
| Intel Celeron     | 1        | 6.25%   |
| AMD A4            | 1        | 6.25%   |
| AMD A10           | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 5        | 31.25%  |
| 4      | 4        | 25%     |
| 6      | 3        | 18.75%  |
| 2      | 2        | 12.5%   |
| 3      | 1        | 6.25%   |
| 1      | 1        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 81.25%  |
| 1      | 3        | 18.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 16       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 4        | 25%     |
| 0x08701013 | 2        | 12.5%   |
| 0xa0671    | 1        | 6.25%   |
| 0x906eb    | 1        | 6.25%   |
| 0x306c3    | 1        | 6.25%   |
| 0x106a5    | 1        | 6.25%   |
| 0x1067a    | 1        | 6.25%   |
| 0x0800820d | 1        | 6.25%   |
| 0x0600611a | 1        | 6.25%   |
| 0x06001119 | 1        | 6.25%   |
| 0x06000852 | 1        | 6.25%   |
| 0x0600063e | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Zen 2      | 6        | 37.5%   |
| Piledriver | 2        | 12.5%   |
| Zen+       | 1        | 6.25%   |
| Penryn     | 1        | 6.25%   |
| Nehalem    | 1        | 6.25%   |
| KabyLake   | 1        | 6.25%   |
| Icelake    | 1        | 6.25%   |
| Haswell    | 1        | 6.25%   |
| Excavator  | 1        | 6.25%   |
| Bulldozer  | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 7        | 41.18%  |
| AMD    | 7        | 41.18%  |
| Intel  | 3        | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 11.76%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 11.76%  |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 5.88%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 5.88%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 5.88%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 5.88%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.88%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 5.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 5.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 5.88%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 5.88%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 5.88%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 5.88%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 6        | 37.5%   |
| 1 x AMD      | 6        | 37.5%   |
| 1 x Intel    | 3        | 18.75%  |
| AMD + Nvidia | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 13       | 81.25%  |
| Proprietary | 3        | 18.75%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 5        | 31.25%  |
| Unknown    | 4        | 25%     |
| 7.01-8.0   | 2        | 12.5%   |
| 3.01-4.0   | 2        | 12.5%   |
| 0.51-1.0   | 2        | 12.5%   |
| 8.01-16.0  | 1        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 3        | 18.75%  |
| Goldstar             | 3        | 18.75%  |
| AOC                  | 3        | 18.75%  |
| Dell                 | 2        | 12.5%   |
| SKY                  | 1        | 6.25%   |
| Hewlett-Packard      | 1        | 6.25%   |
| BenQ                 | 1        | 6.25%   |
| Ancor Communications | 1        | 6.25%   |
| Acer                 | 1        | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 2        | 10.53%  |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                  | 1        | 5.26%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch     | 1        | 5.26%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch | 1        | 5.26%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch    | 1        | 5.26%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch            | 1        | 5.26%   |
| Goldstar TV SSCR GSMC0C8 3840x2160 1600x900mm 72.3-inch               | 1        | 5.26%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1        | 5.26%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch                | 1        | 5.26%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 1        | 5.26%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 1        | 5.26%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                     | 1        | 5.26%   |
| BenQ LCD Monitor PD2700U 3840x2160                                    | 1        | 5.26%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 1        | 5.26%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 1        | 5.26%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1        | 5.26%   |
| Acer LCD Monitor XV270U 5120x1440                                     | 1        | 5.26%   |
| Acer LCD Monitor VG272U                                               | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 8        | 50%     |
| 3840x2160 (4K)  | 3        | 18.75%  |
| 5120x1440       | 1        | 6.25%   |
| 3840x1080       | 1        | 6.25%   |
| 2560x1440 (QHD) | 1        | 6.25%   |
| 2560x1080       | 1        | 6.25%   |
| Unknown         | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 4        | 23.53%  |
| 23      | 3        | 17.65%  |
| 40      | 2        | 11.76%  |
| Unknown | 2        | 11.76%  |
| 72      | 1        | 5.88%   |
| 49      | 1        | 5.88%   |
| 33      | 1        | 5.88%   |
| 28      | 1        | 5.88%   |
| 27      | 1        | 5.88%   |
| 24      | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 25%     |
| 401-500     | 4        | 25%     |
| 801-900     | 2        | 12.5%   |
| Unknown     | 2        | 12.5%   |
| 701-800     | 1        | 6.25%   |
| 601-700     | 1        | 6.25%   |
| 1501-2000   | 1        | 6.25%   |
| 1001-1500   | 1        | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 10       | 71.43%  |
| Unknown | 2        | 14.29%  |
| 32/9    | 1        | 7.14%   |
| 21/9    | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 31.25%  |
| 501-1000       | 3        | 18.75%  |
| 151-200        | 2        | 12.5%   |
| Unknown        | 2        | 12.5%   |
| More than 1000 | 1        | 6.25%   |
| 351-500        | 1        | 6.25%   |
| 301-350        | 1        | 6.25%   |
| 251-300        | 1        | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 53.33%  |
| 101-120 | 4        | 26.67%  |
| Unknown | 2        | 13.33%  |
| 1-50    | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 75%     |
| 2     | 3        | 18.75%  |
| 3     | 1        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 12       | 60%     |
| Intel                    | 4        | 20%     |
| Xiaomi                   | 2        | 10%     |
| Ralink Technology        | 1        | 5%      |
| Marvell Technology Group | 1        | 5%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 37.5%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 8.33%   |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.17%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 4.17%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 4.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 4.17%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 4.17%   |
| Intel Ethernet Controller I225-V                                  | 1        | 4.17%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 50%     |
| Intel                 | 2        | 33.33%  |
| Ralink Technology     | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter          | 1        | 16.67%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1        | 16.67%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 1        | 16.67%  |
| Ralink MT7601U Wireless Adapter                          | 1        | 16.67%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 1        | 16.67%  |
| Intel Wi-Fi 6 AX200                                      | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 11       | 61.11%  |
| Intel                    | 4        | 22.22%  |
| Xiaomi                   | 2        | 11.11%  |
| Marvell Technology Group | 1        | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 50%     |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 11.11%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 5.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 1        | 5.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 72.73%  |
| WiFi     | 6        | 27.27%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 78.95%  |
| WiFi     | 4        | 21.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 75%     |
| 2     | 4        | 25%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 68.75%  |
| Yes  | 5        | 31.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 28.57%  |
| Cambridge Silicon Radio | 2        | 28.57%  |
| Realtek Semiconductor   | 1        | 14.29%  |
| Broadcom                | 1        | 14.29%  |
| ASUSTek Computer        | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 2        | 28.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 28.57%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 14.29%  |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 14.29%  |
| ASUS Bluetooth Radio                                | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 11       | 39.29%  |
| Nvidia                               | 7        | 25%     |
| Intel                                | 4        | 14.29%  |
| Thesycon Systemsoftware & Consulting | 1        | 3.57%   |
| Razer USA                            | 1        | 3.57%   |
| JMTek                                | 1        | 3.57%   |
| Creative Technology                  | 1        | 3.57%   |
| Creative Labs                        | 1        | 3.57%   |
| ASUSTek Computer                     | 1        | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 6        | 16.67%  |
| Nvidia GA102 High Definition Audio Controller                           | 2        | 5.56%   |
| AMD SBx00 Azalia (Intel HDA)                                            | 2        | 5.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 2        | 5.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2        | 5.56%   |
| Thesycon Systemsoftware & Consulting E30                                | 1        | 2.78%   |
| Razer USA Kraken Tournament Edition                                     | 1        | 2.78%   |
| Nvidia TU104 HD Audio Controller                                        | 1        | 2.78%   |
| Nvidia GP108 High Definition Audio Controller                           | 1        | 2.78%   |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 2.78%   |
| Nvidia GK104 HDMI Audio Controller                                      | 1        | 2.78%   |
| Nvidia GF116 High Definition Audio Controller                           | 1        | 2.78%   |
| JMTek USB PnP Audio Device                                              | 1        | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1        | 2.78%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 1        | 2.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1        | 2.78%   |
| Intel 200 Series PCH HD Audio                                           | 1        | 2.78%   |
| Creative Technology Sound BlasterX Kratos S5                            | 1        | 2.78%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]              | 1        | 2.78%   |
| ASUSTek Computer USB Audio                                              | 1        | 2.78%   |
| AMD Trinity HDMI Audio Controller                                       | 1        | 2.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                | 1        | 2.78%   |
| AMD FCH Azalia Controller                                               | 1        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 1        | 2.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                        | 1        | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 2        | 28.57%  |
| Unknown             | 1        | 14.29%  |
| Samsung Electronics | 1        | 14.29%  |
| Kingston            | 1        | 14.29%  |
| G.Skill             | 1        | 14.29%  |
| Crucial             | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 14.29%  |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s    | 1        | 14.29%  |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s      | 1        | 14.29%  |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 1        | 14.29%  |
| Crucial RAM BLS8G4D26BFSCK.8FD 8GB DIMM DDR4           | 1        | 14.29%  |
| Corsair RAM CMK4GX4M1A2400C14 4GB DIMM DDR4 3007MT/s   | 1        | 14.29%  |
| Corsair RAM CMH32GX4M2D3600C18 16GB DIMM DDR4 2133MT/s | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 66.67%  |
| DDR3 | 1        | 16.67%  |
| DDR2 | 1        | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 2        | 33.33%  |
| 8192  | 2        | 33.33%  |
| 4096  | 1        | 16.67%  |
| 2048  | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 14.29%  |
| 3200  | 1        | 14.29%  |
| 3007  | 1        | 14.29%  |
| 3000  | 1        | 14.29%  |
| 2133  | 1        | 14.29%  |
| 1333  | 1        | 14.29%  |
| 800   | 1        | 14.29%  |

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
| Microsoft | 1        | 33.33%  |
| Microdia  | 1        | 33.33%  |
| Logitech  | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Microsoft LifeCam HD-3000       | 1        | 33.33%  |
| Microdia Integrated Camera      | 1        | 33.33%  |
| Logitech BRIO 4K Stream Edition | 1        | 33.33%  |

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
| 0     | 15       | 93.75%  |
| 1     | 1        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 100%    |

