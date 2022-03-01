Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

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

| Vendor   | Model             | Probe                                                      | Date         |
|----------|-------------------|------------------------------------------------------------|--------------|
| Dell     | 0WN7Y6 A01        | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell     | 0PC5F7 A02        | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek  | PRIME B450-PLUS   | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| ASRock   | B450M Pro4        | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI      | Z97A GAMING 6     | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| AZW      | Gemini M          | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW      | Gemini M          | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google   | Panther           | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Gigabyte | X570 AORUS ULTRA  | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte | H87-D3H-CF        | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Dell     | 0N4YC8 A00        | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| ASUSTek  | PRIME B450M-A II  | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek  | PRIME B450M-A II  | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek  | P5Q DELUXE        | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo   | NOK               | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Dell     | 0M5DCD A00        | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| Dell     | 0M5DCD A00        | [d40f4d3bee](https://linux-hardware.org/?probe=d40f4d3bee) | Aug 06, 2021 |
| ASUSTek  | PRIME TRX40-PRO S | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell     | 0M5DCD A00        | [5ee09ac705](https://linux-hardware.org/?probe=5ee09ac705) | Aug 04, 2021 |
| Dell     | 0M5DCD A00        | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| HP       | 0B54h D           | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-348.7.1.el8_5.x86_64  | 3        | 18.75%  |
| 4.18.0-348.12.2.el8_5.x86_64 | 3        | 18.75%  |
| 4.18.0-305.19.1.el8_4.x86_64 | 2        | 12.5%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2        | 12.5%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 12.5%   |
| 5.14.1-1.el8.elrepo.x86_64   | 1        | 6.25%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1        | 6.25%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 1        | 6.25%   |
| 4.18.0-240.22.1.el8.x86_64   | 1        | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 15       | 93.75%  |
| 5.14.1  | 1        | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 15       | 93.75%  |
| 5.14    | 1        | 6.25%   |

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


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 7        | 43.75%  |
| Unknown | 5        | 31.25%  |
| KDE5    | 3        | 18.75%  |
| MATE    | 1        | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 7        | 43.75%  |
| Wayland | 6        | 37.5%   |
| Unknown | 3        | 18.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 62.5%   |
| GDM     | 4        | 25%     |
| SDDM    | 2        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 56.25%  |
| en_IL | 3        | 18.75%  |
| ru_RU | 1        | 6.25%   |
| ja_JP | 1        | 6.25%   |
| es_CO | 1        | 6.25%   |
| en_SG | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 9        | 56.25%  |
| EFI  | 7        | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 15       | 93.75%  |
| Ext4 | 1        | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 8        | 50%     |
| Unknown | 6        | 37.5%   |
| MBR     | 2        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 93.75%  |
| Yes       | 1        | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 4        | 25%     |
| ASUSTek Computer    | 4        | 25%     |
| Gigabyte Technology | 2        | 12.5%   |
| MSI                 | 1        | 6.25%   |
| Lenovo              | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |
| Google              | 1        | 6.25%   |
| AZW                 | 1        | 6.25%   |
| ASRock              | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Dell OptiPlex 9020              | 2        | 12.5%   |
| MSI MS-7917                     | 1        | 6.25%   |
| Lenovo ThinkCentre M72e 36601Y8 | 1        | 6.25%   |
| HP Z600 Workstation             | 1        | 6.25%   |
| Google Panther                  | 1        | 6.25%   |
| Gigabyte X570 AORUS ULTRA       | 1        | 6.25%   |
| Gigabyte H87-D3H                | 1        | 6.25%   |
| Dell Precision T5610            | 1        | 6.25%   |
| Dell OptiPlex 390               | 1        | 6.25%   |
| AZW Gemini M                    | 1        | 6.25%   |
| ASUS PRIME TRX40-PRO S          | 1        | 6.25%   |
| ASUS PRIME B450M-A II           | 1        | 6.25%   |
| ASUS PRIME B450-PLUS            | 1        | 6.25%   |
| ASUS P5Q DELUXE                 | 1        | 6.25%   |
| ASRock B450M Pro4               | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 3        | 18.75%  |
| ASUS PRIME         | 3        | 18.75%  |
| MSI MS-7917        | 1        | 6.25%   |
| Lenovo ThinkCentre | 1        | 6.25%   |
| HP Z600            | 1        | 6.25%   |
| Google Panther     | 1        | 6.25%   |
| Gigabyte X570      | 1        | 6.25%   |
| Gigabyte H87-D3H   | 1        | 6.25%   |
| Dell Precision     | 1        | 6.25%   |
| AZW Gemini         | 1        | 6.25%   |
| ASUS P5Q           | 1        | 6.25%   |
| ASRock B450M       | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 3        | 18.75%  |
| 2020 | 2        | 12.5%   |
| 2018 | 2        | 12.5%   |
| 2015 | 2        | 12.5%   |
| 2013 | 2        | 12.5%   |
| 2021 | 1        | 6.25%   |
| 2019 | 1        | 6.25%   |
| 2011 | 1        | 6.25%   |
| 2010 | 1        | 6.25%   |
| 2008 | 1        | 6.25%   |

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
| Disabled | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 93.75%  |
| Yes  | 1        | 6.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 4        | 25%     |
| 16.01-24.0  | 4        | 25%     |
| 4.01-8.0    | 2        | 12.5%   |
| 3.01-4.0    | 2        | 12.5%   |
| 64.01-256.0 | 2        | 12.5%   |
| 1.01-2.0    | 1        | 6.25%   |
| 8.01-16.0   | 1        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 6        | 37.5%   |
| 3.01-4.0  | 3        | 18.75%  |
| 4.01-8.0  | 2        | 12.5%   |
| 1.01-2.0  | 2        | 12.5%   |
| 8.01-16.0 | 1        | 6.25%   |
| 0.51-1.0  | 1        | 6.25%   |
| 0.01-0.5  | 1        | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 50%     |
| 2      | 3        | 18.75%  |
| 4      | 2        | 12.5%   |
| 3      | 2        | 12.5%   |
| 8      | 1        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 50%     |
| No        | 8        | 50%     |

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
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 68.75%  |
| Yes       | 5        | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 6        | 37.5%   |
| Israel    | 3        | 18.75%  |
| Singapore | 1        | 6.25%   |
| Russia    | 1        | 6.25%   |
| Portugal  | 1        | 6.25%   |
| Japan     | 1        | 6.25%   |
| France    | 1        | 6.25%   |
| Czechia   | 1        | 6.25%   |
| Colombia  | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Haifa          | 2        | 12.5%   |
| St Petersburg  | 1        | 6.25%   |
| Singapore      | 1        | 6.25%   |
| Saint Albans   | 1        | 6.25%   |
| Rehovot        | 1        | 6.25%   |
| Prague         | 1        | 6.25%   |
| Paris          | 1        | 6.25%   |
| Mequon         | 1        | 6.25%   |
| Lisbon         | 1        | 6.25%   |
| Lebanon        | 1        | 6.25%   |
| Fredericksburg | 1        | 6.25%   |
| Corvallis      | 1        | 6.25%   |
| Burlington     | 1        | 6.25%   |
| Bucaramanga    | 1        | 6.25%   |
| ÅŒtsu        | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 10     | 20.83%  |
| Seagate             | 4        | 10     | 16.67%  |
| Toshiba             | 2        | 2      | 8.33%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| Crucial             | 2        | 2      | 8.33%   |
| SK Hynix            | 1        | 1      | 4.17%   |
| SanDisk             | 1        | 1      | 4.17%   |
| PNY                 | 1        | 1      | 4.17%   |
| Phison              | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |
| Hitachi             | 1        | 2      | 4.17%   |
| HGST                | 1        | 1      | 4.17%   |
| Corsair             | 1        | 1      | 4.17%   |
| China               | 1        | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 3.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 3.7%    |
| WDC WD5000LPCX-24VHAT0 500GB     | 1        | 3.7%    |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 3.7%    |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 3.7%    |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 3.7%    |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 3.7%    |
| Toshiba MG04ACA400E 4TB          | 1        | 3.7%    |
| Toshiba DT01ACA050 500GB         | 1        | 3.7%    |
| SK Hynix SH920 2.5 7MM 256GB SSD | 1        | 3.7%    |
| Seagate ST500DM002-1BD142 500GB  | 1        | 3.7%    |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 3.7%    |
| Seagate ST3160318AS 160GB        | 1        | 3.7%    |
| Seagate ST1000VX005-2EZ102 1TB   | 1        | 3.7%    |
| SanDisk SSD U110 16GB            | 1        | 3.7%    |
| Samsung SSD 980 PRO 1TB          | 1        | 3.7%    |
| Samsung SSD 860 EVO 1TB          | 1        | 3.7%    |
| PNY CS900 120GB SSD              | 1        | 3.7%    |
| Phison Sabrent 1TB               | 1        | 3.7%    |
| Intel SSDPEDMW012T4 1TB          | 1        | 3.7%    |
| Hitachi HTS727575A9E364 752GB    | 1        | 3.7%    |
| Hitachi HDP725050GLA360 500GB    | 1        | 3.7%    |
| HGST HTS721010A9E630 1TB         | 1        | 3.7%    |
| Crucial CT240BX500SSD1 240GB     | 1        | 3.7%    |
| Crucial CT1000P2SSD8 1TB         | 1        | 3.7%    |
| Corsair Neutron SSD 64GB         | 1        | 3.7%    |
| China M.2 SSD 256GB              | 1        | 3.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 8      | 33.33%  |
| Seagate | 4        | 10     | 33.33%  |
| Toshiba | 2        | 2      | 16.67%  |
| Hitachi | 1        | 2      | 8.33%   |
| HGST    | 1        | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 22.22%  |
| SK Hynix            | 1        | 1      | 11.11%  |
| SanDisk             | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| PNY                 | 1        | 1      | 11.11%  |
| Crucial             | 1        | 1      | 11.11%  |
| Corsair             | 1        | 1      | 11.11%  |
| China               | 1        | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 23     | 43.48%  |
| SSD  | 9        | 9      | 39.13%  |
| NVMe | 4        | 4      | 17.39%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 32     | 77.78%  |
| NVMe | 4        | 4      | 22.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 16     | 58.82%  |
| 0.51-1.0   | 4        | 8      | 23.53%  |
| 3.01-4.0   | 2        | 7      | 11.76%  |
| 1.01-2.0   | 1        | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 5        | 31.25%  |
| 501-1000       | 4        | 25%     |
| More than 3000 | 2        | 12.5%   |
| 1001-2000      | 2        | 12.5%   |
| 251-500        | 1        | 6.25%   |
| 2001-3000      | 1        | 6.25%   |
| 1-20           | 1        | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 6        | 37.5%   |
| 21-50          | 4        | 25%     |
| 51-100         | 3        | 18.75%  |
| More than 3000 | 1        | 6.25%   |
| 251-500        | 1        | 6.25%   |
| 1001-2000      | 1        | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB     | 1        | 4      | 33.33%  |
| Hitachi HTS727575A9E364 752GB | 1        | 1      | 33.33%  |
| Corsair Neutron SSD 64GB      | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 4      | 33.33%  |
| Hitachi | 1        | 1      | 33.33%  |
| Corsair | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 4      | 50%     |
| Hitachi | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 5      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works    | 9        | 20     | 50%     |
| Detected | 6        | 10     | 33.33%  |
| Malfunc  | 3        | 6      | 16.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 11       | 50%     |
| AMD                       | 5        | 22.73%  |
| Samsung Electronics       | 1        | 4.55%   |
| Phison Electronics        | 1        | 4.55%   |
| Micron/Crucial Technology | 1        | 4.55%   |
| Marvell Technology Group  | 1        | 4.55%   |
| ASMedia Technology        | 1        | 4.55%   |
| Adaptec                   | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 14.81%  |
| Intel SATA Controller [RAID mode]                                                       | 3        | 11.11%  |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 11.11%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 3.7%    |
| Phison E12 NVMe Controller                                                              | 1        | 3.7%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 3.7%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 3.7%    |
| Intel PCIe Data Center SSD                                                              | 1        | 3.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 3.7%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 3.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 3.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 3.7%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 3.7%    |
| Adaptec ASC-39320A U320                                                                 | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 10       | 47.62%  |
| RAID | 4        | 19.05%  |
| NVMe | 4        | 19.05%  |
| IDE  | 2        | 9.52%   |
| SCSI | 1        | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 68.75%  |
| AMD    | 5        | 31.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 12.5%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 6.25%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 6.25%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 6.25%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 6.25%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 6.25%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 6.25%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 6.25%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 6.25%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 6.25%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 6.25%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 6.25%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 6.25%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 6.25%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 4        | 25%     |
| Intel Xeon             | 2        | 12.5%   |
| Intel Celeron          | 2        | 12.5%   |
| Intel Core i5          | 1        | 6.25%   |
| Intel Core i3          | 1        | 6.25%   |
| Intel Core 2 Quad      | 1        | 6.25%   |
| AMD Ryzen Threadripper | 1        | 6.25%   |
| AMD Ryzen 9            | 1        | 6.25%   |
| AMD Ryzen 7            | 1        | 6.25%   |
| AMD Ryzen 5            | 1        | 6.25%   |
| AMD Ryzen 3            | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 50%     |
| 12     | 2        | 12.5%   |
| 8      | 2        | 12.5%   |
| 2      | 2        | 12.5%   |
| 24     | 1        | 6.25%   |
| 6      | 1        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 87.5%   |
| 2      | 2        | 12.5%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 62.5%   |
| 1      | 6        | 37.5%   |

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
| 0x306c3    | 3        | 18.75%  |
| 0x706a8    | 1        | 6.25%   |
| 0x40651    | 1        | 6.25%   |
| 0x306e4    | 1        | 6.25%   |
| 0x306a9    | 1        | 6.25%   |
| 0x206c2    | 1        | 6.25%   |
| 0x206a7    | 1        | 6.25%   |
| 0x10677    | 1        | 6.25%   |
| 0x0a201009 | 1        | 6.25%   |
| 0x0870100a | 1        | 6.25%   |
| 0x08301039 | 1        | 6.25%   |
| 0x08108109 | 1        | 6.25%   |
| 0x0800820d | 1        | 6.25%   |
| Unknown    | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 5        | 31.25%  |
| Zen+          | 2        | 12.5%   |
| Zen 2         | 2        | 12.5%   |
| IvyBridge     | 2        | 12.5%   |
| Zen 3         | 1        | 6.25%   |
| Westmere      | 1        | 6.25%   |
| SandyBridge   | 1        | 6.25%   |
| Penryn        | 1        | 6.25%   |
| Goldmont plus | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 47.06%  |
| Intel  | 6        | 35.29%  |
| AMD    | 3        | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 11.76%  |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 11.76%  |
| Nvidia TU117GL [T600]                                                       | 1        | 5.88%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 5.88%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 5.88%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 5.88%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 5.88%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 5.88%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 5.88%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 5.88%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 5.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 7        | 43.75%  |
| 1 x Intel      | 5        | 31.25%  |
| 1 x AMD        | 3        | 18.75%  |
| Intel + Nvidia | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 75%     |
| Proprietary | 3        | 18.75%  |
| Unknown     | 1        | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 37.5%   |
| 1.01-2.0   | 4        | 25%     |
| 0.01-0.5   | 3        | 18.75%  |
| 5.01-6.0   | 1        | 6.25%   |
| 3.01-4.0   | 1        | 6.25%   |
| 8.01-16.0  | 1        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 41.67%  |
| Samsung Electronics | 3        | 25%     |
| Iiyama              | 2        | 16.67%  |
| Sony                | 1        | 8.33%   |
| ASUSTek Computer    | 1        | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sony LG TV SNY045B 1920x540                                         | 1        | 7.69%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch   | 1        | 7.69%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch | 1        | 7.69%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch  | 1        | 7.69%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                | 1        | 7.69%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                 | 1        | 7.69%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                    | 1        | 7.69%   |
| Dell LCD Monitor U2414H 3840x1080                                   | 1        | 7.69%   |
| Dell LCD Monitor U2414H                                             | 1        | 7.69%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                   | 1        | 7.69%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                   | 1        | 7.69%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                   | 1        | 7.69%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch        | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 4        | 30.77%  |
| 3840x1080        | 2        | 15.38%  |
| 1600x900 (HD+)   | 2        | 15.38%  |
| 1280x1024 (SXGA) | 2        | 15.38%  |
| 3840x2160 (4K)   | 1        | 7.69%   |
| 1920x540         | 1        | 7.69%   |
| Unknown          | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 2        | 16.67%  |
| 17      | 2        | 16.67%  |
| 65      | 1        | 8.33%   |
| 48      | 1        | 8.33%   |
| 31      | 1        | 8.33%   |
| 27      | 1        | 8.33%   |
| 24      | 1        | 8.33%   |
| 20      | 1        | 8.33%   |
| 19      | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 33.33%  |
| 401-500     | 2        | 16.67%  |
| 301-350     | 2        | 16.67%  |
| 1001-1500   | 2        | 16.67%  |
| 601-700     | 1        | 8.33%   |
| Unknown     | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 66.67%  |
| 5/4     | 2        | 16.67%  |
| 32/9    | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 25%     |
| 151-200        | 2        | 16.67%  |
| 141-150        | 2        | 16.67%  |
| More than 1000 | 1        | 8.33%   |
| 351-500        | 1        | 8.33%   |
| 301-350        | 1        | 8.33%   |
| 501-1000       | 1        | 8.33%   |
| Unknown        | 1        | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 75%     |
| 1-50    | 1        | 8.33%   |
| 121-160 | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 68.75%  |
| 0     | 4        | 25%     |
| 2     | 1        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 7        | 33.33%  |
| Intel                     | 7        | 33.33%  |
| Qualcomm Atheros          | 2        | 9.52%   |
| Solarflare Communications | 1        | 4.76%   |
| Microsoft                 | 1        | 4.76%   |
| Marvell Technology Group  | 1        | 4.76%   |
| BUFFALO                   | 1        | 4.76%   |
| Broadcom                  | 1        | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 28%     |
| Intel I211 Gigabit Network Connection                             | 2        | 8%      |
| Intel Ethernet Connection I217-LM                                 | 2        | 8%      |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 4%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 4%      |
| Realtek 802.11ac NIC                                              | 1        | 4%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 4%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 4%      |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 4%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 4%      |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 4%      |
| Intel Wireless 3165                                               | 1        | 4%      |
| Intel Wi-Fi 6 AX200                                               | 1        | 4%      |
| Intel Ethernet Connection I217-V                                  | 1        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4%      |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 4%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 4%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 2        | 28.57%  |
| Intel                 | 2        | 28.57%  |
| Realtek Semiconductor | 1        | 14.29%  |
| Microsoft             | 1        | 14.29%  |
| BUFFALO               | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                       | 1        | 12.5%   |
| Realtek 802.11ac NIC                                     | 1        | 12.5%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter         | 1        | 12.5%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter         | 1        | 12.5%   |
| Microsoft Xbox 360 Wireless Adapter                      | 1        | 12.5%   |
| Intel Wireless 3165                                      | 1        | 12.5%   |
| Intel Wi-Fi 6 AX200                                      | 1        | 12.5%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070] | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 7        | 43.75%  |
| Intel                     | 6        | 37.5%   |
| Solarflare Communications | 1        | 6.25%   |
| Marvell Technology Group  | 1        | 6.25%   |
| Broadcom                  | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 41.18%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.76%  |
| Intel Ethernet Connection I217-LM                                 | 2        | 11.76%  |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 5.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 5.88%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 5.88%   |
| Intel Ethernet Connection I217-V                                  | 1        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 69.57%  |
| WiFi     | 7        | 30.43%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 82.35%  |
| WiFi     | 3        | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 62.5%   |
| 2     | 6        | 37.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 87.5%   |
| Yes  | 2        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 40%     |
| IMC Networks            | 1        | 20%     |
| Cambridge Silicon Radio | 1        | 20%     |
| Broadcom                | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 1        | 20%     |
| Intel AX200 Bluetooth                               | 1        | 20%     |
| IMC Networks Bluetooth Device                       | 1        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 20%     |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 11       | 40.74%  |
| Nvidia              | 8        | 29.63%  |
| AMD                 | 6        | 22.22%  |
| C-Media Electronics | 1        | 3.7%    |
| ASUSTek Computer    | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 9.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 9.38%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 6.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.25%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 6.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 3.13%   |
| Nvidia High Definition Audio Controller                                    | 1        | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.13%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 3.13%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 3.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 3.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 3.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 3.13%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 3.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 3.13%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 3.13%   |
| C-Media Electronics TONOR TC30 Audio Device                                | 1        | 3.13%   |
| ASUSTek Computer USB Audio                                                 | 1        | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 3.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 3        | 27.27%  |
| Unknown             | 2        | 18.18%  |
| Samsung Electronics | 2        | 18.18%  |
| SK Hynix            | 1        | 9.09%   |
| Micron Technology   | 1        | 9.09%   |
| Kingston            | 1        | 9.09%   |
| Corsair             | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1        | 9.09%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 1        | 9.09%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 9.09%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s | 1        | 9.09%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s   | 1        | 9.09%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s               | 1        | 9.09%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 1600MT/s    | 1        | 9.09%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s    | 1        | 9.09%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s   | 1        | 9.09%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s     | 1        | 9.09%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s   | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 5        | 50%     |
| DDR3 | 4        | 40%     |
| DDR2 | 1        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 9        | 90%     |
| SODIMM | 1        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 50%     |
| 32768 | 2        | 20%     |
| 4096  | 1        | 10%     |
| 2048  | 1        | 10%     |
| 1024  | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 3        | 27.27%  |
| 1600  | 2        | 18.18%  |
| 2933  | 1        | 9.09%   |
| 2666  | 1        | 9.09%   |
| 2400  | 1        | 9.09%   |
| 2200  | 1        | 9.09%   |
| 1800  | 1        | 9.09%   |
| 667   | 1        | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-2030 Laser Printer | 1        | 100%    |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 2        | 66.67%  |
| Huawei Technologies | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech Webcam C270        | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |
| Huawei HiCamera             | 1        | 33.33%  |

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
| 0     | 13       | 81.25%  |
| 1     | 2        | 12.5%   |
| 2     | 1        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 2        | 66.67%  |
| Graphics card | 1        | 33.33%  |

