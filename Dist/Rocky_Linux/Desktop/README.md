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
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 22

| Vendor   | Model             | Probe                                                      | Date         |
|----------|-------------------|------------------------------------------------------------|--------------|
| Dell     | 0NK70N A03        | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
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

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Rocky Linux 8.5 | 8        | 47.06%  |
| Rocky Linux 8.4 | 8        | 47.06%  |
| Rocky Linux 8.3 | 1        | 5.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 17       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64 | 4        | 23.53%  |
| 4.18.0-348.7.1.el8_5.x86_64  | 3        | 17.65%  |
| 4.18.0-305.19.1.el8_4.x86_64 | 2        | 11.76%  |
| 4.18.0-305.12.1.el8_4.x86_64 | 2        | 11.76%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 2        | 11.76%  |
| 5.14.1-1.el8.elrepo.x86_64   | 1        | 5.88%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1        | 5.88%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 1        | 5.88%   |
| 4.18.0-240.22.1.el8.x86_64   | 1        | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 16       | 94.12%  |
| 5.14.1  | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 16       | 94.12%  |
| 5.14    | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 17       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GNOME   | 8        | 47.06%  |
| Unknown | 5        | 29.41%  |
| KDE5    | 3        | 17.65%  |
| MATE    | 1        | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 8        | 47.06%  |
| Wayland | 6        | 35.29%  |
| Unknown | 3        | 17.65%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 58.82%  |
| GDM     | 5        | 29.41%  |
| SDDM    | 2        | 11.76%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 52.94%  |
| en_IL | 3        | 17.65%  |
| en_SG | 2        | 11.76%  |
| ru_RU | 1        | 5.88%   |
| ja_JP | 1        | 5.88%   |
| es_CO | 1        | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 10       | 58.82%  |
| EFI  | 7        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 16       | 94.12%  |
| Ext4 | 1        | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 8        | 47.06%  |
| Unknown | 6        | 35.29%  |
| MBR     | 3        | 17.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 94.12%  |
| Yes       | 1        | 5.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 29.41%  |
| ASUSTek Computer    | 4        | 23.53%  |
| Gigabyte Technology | 2        | 11.76%  |
| MSI                 | 1        | 5.88%   |
| Lenovo              | 1        | 5.88%   |
| Hewlett-Packard     | 1        | 5.88%   |
| Google              | 1        | 5.88%   |
| AZW                 | 1        | 5.88%   |
| ASRock              | 1        | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Dell OptiPlex 9020              | 2        | 11.76%  |
| MSI MS-7917                     | 1        | 5.88%   |
| Lenovo ThinkCentre M72e 36601Y8 | 1        | 5.88%   |
| HP Z600 Workstation             | 1        | 5.88%   |
| Google Panther                  | 1        | 5.88%   |
| Gigabyte X570 AORUS ULTRA       | 1        | 5.88%   |
| Gigabyte H87-D3H                | 1        | 5.88%   |
| Dell Precision T7610            | 1        | 5.88%   |
| Dell Precision T5610            | 1        | 5.88%   |
| Dell OptiPlex 390               | 1        | 5.88%   |
| AZW Gemini M                    | 1        | 5.88%   |
| ASUS PRIME TRX40-PRO S          | 1        | 5.88%   |
| ASUS PRIME B450M-A II           | 1        | 5.88%   |
| ASUS PRIME B450-PLUS            | 1        | 5.88%   |
| ASUS P5Q DELUXE                 | 1        | 5.88%   |
| ASRock B450M Pro4               | 1        | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 3        | 17.65%  |
| ASUS PRIME         | 3        | 17.65%  |
| Dell Precision     | 2        | 11.76%  |
| MSI MS-7917        | 1        | 5.88%   |
| Lenovo ThinkCentre | 1        | 5.88%   |
| HP Z600            | 1        | 5.88%   |
| Google Panther     | 1        | 5.88%   |
| Gigabyte X570      | 1        | 5.88%   |
| Gigabyte H87-D3H   | 1        | 5.88%   |
| AZW Gemini         | 1        | 5.88%   |
| ASUS P5Q           | 1        | 5.88%   |
| ASRock B450M       | 1        | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 3        | 17.65%  |
| 2013 | 3        | 17.65%  |
| 2020 | 2        | 11.76%  |
| 2018 | 2        | 11.76%  |
| 2015 | 2        | 11.76%  |
| 2021 | 1        | 5.88%   |
| 2019 | 1        | 5.88%   |
| 2011 | 1        | 5.88%   |
| 2010 | 1        | 5.88%   |
| 2008 | 1        | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 17       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 17       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 94.12%  |
| Yes  | 1        | 5.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 4        | 23.53%  |
| 16.01-24.0  | 4        | 23.53%  |
| 4.01-8.0    | 3        | 17.65%  |
| 3.01-4.0    | 2        | 11.76%  |
| 64.01-256.0 | 2        | 11.76%  |
| 1.01-2.0    | 1        | 5.88%   |
| 8.01-16.0   | 1        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 6        | 35.29%  |
| 3.01-4.0  | 4        | 23.53%  |
| 4.01-8.0  | 2        | 11.76%  |
| 1.01-2.0  | 2        | 11.76%  |
| 8.01-16.0 | 1        | 5.88%   |
| 0.51-1.0  | 1        | 5.88%   |
| 0.01-0.5  | 1        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 47.06%  |
| 2      | 4        | 23.53%  |
| 4      | 2        | 11.76%  |
| 3      | 2        | 11.76%  |
| 8      | 1        | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 52.94%  |
| No        | 8        | 47.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 52.94%  |
| Yes       | 8        | 47.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 70.59%  |
| Yes       | 5        | 29.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 6        | 35.29%  |
| Israel    | 3        | 17.65%  |
| Singapore | 2        | 11.76%  |
| Russia    | 1        | 5.88%   |
| Portugal  | 1        | 5.88%   |
| Japan     | 1        | 5.88%   |
| France    | 1        | 5.88%   |
| Czechia   | 1        | 5.88%   |
| Colombia  | 1        | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Singapore      | 2        | 11.76%  |
| Haifa          | 2        | 11.76%  |
| St Petersburg  | 1        | 5.88%   |
| Saint Albans   | 1        | 5.88%   |
| Rehovot        | 1        | 5.88%   |
| Prague         | 1        | 5.88%   |
| Paris          | 1        | 5.88%   |
| Mequon         | 1        | 5.88%   |
| Lisbon         | 1        | 5.88%   |
| Lebanon        | 1        | 5.88%   |
| Fredericksburg | 1        | 5.88%   |
| Corvallis      | 1        | 5.88%   |
| Burlington     | 1        | 5.88%   |
| Bucaramanga    | 1        | 5.88%   |
| ÅŒtsu        | 1        | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 10     | 19.23%  |
| Seagate             | 4        | 10     | 15.38%  |
| Toshiba             | 3        | 3      | 11.54%  |
| Samsung Electronics | 2        | 2      | 7.69%   |
| Hitachi             | 2        | 3      | 7.69%   |
| Crucial             | 2        | 2      | 7.69%   |
| SK Hynix            | 1        | 1      | 3.85%   |
| SanDisk             | 1        | 1      | 3.85%   |
| PNY                 | 1        | 1      | 3.85%   |
| Phison              | 1        | 1      | 3.85%   |
| Intel               | 1        | 1      | 3.85%   |
| HGST                | 1        | 1      | 3.85%   |
| Corsair             | 1        | 1      | 3.85%   |
| China               | 1        | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1        | 3.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 3.45%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 1        | 3.45%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 1        | 3.45%   |
| WDC WD5000AAKX-001CA0 500GB      | 1        | 3.45%   |
| WDC WD20EZRX-00DC0B0 2TB         | 1        | 3.45%   |
| WDC WD1001FALS-00J7B0 1TB        | 1        | 3.45%   |
| Toshiba MG04ACA400E 4TB          | 1        | 3.45%   |
| Toshiba DT01ACA100 1TB           | 1        | 3.45%   |
| Toshiba DT01ACA050 500GB         | 1        | 3.45%   |
| SK Hynix SH920 2.5 7MM 256GB SSD | 1        | 3.45%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 3.45%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 3.45%   |
| Seagate ST3160318AS 160GB        | 1        | 3.45%   |
| Seagate ST1000VX005-2EZ102 1TB   | 1        | 3.45%   |
| SanDisk SSD U110 16GB            | 1        | 3.45%   |
| Samsung SSD 980 PRO 1TB          | 1        | 3.45%   |
| Samsung SSD 860 EVO 1TB          | 1        | 3.45%   |
| PNY CS900 120GB SSD              | 1        | 3.45%   |
| Phison Sabrent 1TB               | 1        | 3.45%   |
| Intel SSDPEDMW012T4 1TB          | 1        | 3.45%   |
| Hitachi HTS727575A9E364 752GB    | 1        | 3.45%   |
| Hitachi HDS721010CLA632 1TB      | 1        | 3.45%   |
| Hitachi HDP725050GLA360 500GB    | 1        | 3.45%   |
| HGST HTS721010A9E630 1TB         | 1        | 3.45%   |
| Crucial CT240BX500SSD1 240GB     | 1        | 3.45%   |
| Crucial CT1000P2SSD8 1TB         | 1        | 3.45%   |
| Corsair Neutron SSD 64GB         | 1        | 3.45%   |
| China M.2 SSD 256GB              | 1        | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 8      | 28.57%  |
| Seagate | 4        | 10     | 28.57%  |
| Toshiba | 3        | 3      | 21.43%  |
| Hitachi | 2        | 3      | 14.29%  |
| HGST    | 1        | 1      | 7.14%   |

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
| HDD  | 11       | 25     | 45.83%  |
| SSD  | 9        | 9      | 37.5%   |
| NVMe | 4        | 4      | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 15       | 34     | 78.95%  |
| NVMe | 4        | 4      | 21.05%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 16     | 55.56%  |
| 0.51-1.0   | 5        | 10     | 27.78%  |
| 3.01-4.0   | 2        | 7      | 11.11%  |
| 1.01-2.0   | 1        | 1      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 5        | 29.41%  |
| 501-1000       | 5        | 29.41%  |
| More than 3000 | 2        | 11.76%  |
| 1001-2000      | 2        | 11.76%  |
| 251-500        | 1        | 5.88%   |
| 2001-3000      | 1        | 5.88%   |
| 1-20           | 1        | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 7        | 41.18%  |
| 21-50          | 4        | 23.53%  |
| 51-100         | 3        | 17.65%  |
| More than 3000 | 1        | 5.88%   |
| 251-500        | 1        | 5.88%   |
| 1001-2000      | 1        | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB     | 1        | 4      | 25%     |
| Hitachi HTS727575A9E364 752GB | 1        | 1      | 25%     |
| Hitachi HDS721010CLA632 1TB   | 1        | 1      | 25%     |
| Corsair Neutron SSD 64GB      | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 2        | 2      | 50%     |
| WDC     | 1        | 4      | 25%     |
| Corsair | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 2        | 2      | 66.67%  |
| WDC     | 1        | 4      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 6      | 75%     |
| SSD  | 1        | 1      | 25%     |

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
| Works    | 10       | 21     | 50%     |
| Detected | 6        | 10     | 30%     |
| Malfunc  | 4        | 7      | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 12       | 50%     |
| AMD                       | 5        | 20.83%  |
| Samsung Electronics       | 1        | 4.17%   |
| Phison Electronics        | 1        | 4.17%   |
| Micron/Crucial Technology | 1        | 4.17%   |
| Marvell Technology Group  | 1        | 4.17%   |
| Broadcom / LSI            | 1        | 4.17%   |
| ASMedia Technology        | 1        | 4.17%   |
| Adaptec                   | 1        | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 13.33%  |
| Intel SATA Controller [RAID mode]                                                       | 3        | 10%     |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 10%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 3.33%   |
| Phison E12 NVMe Controller                                                              | 1        | 3.33%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 3.33%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 3.33%   |
| Intel PCIe Data Center SSD                                                              | 1        | 3.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 3.33%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 3.33%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 3.33%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 3.33%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 3.33%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 3.33%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.33%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 3.33%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 3.33%   |
| Adaptec ASC-39320A U320                                                                 | 1        | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 45.83%  |
| RAID | 4        | 16.67%  |
| NVMe | 4        | 16.67%  |
| IDE  | 3        | 12.5%   |
| SAS  | 1        | 4.17%   |
| SCSI | 1        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 12       | 70.59%  |
| AMD    | 5        | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 11.76%  |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 5.88%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 5.88%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 5.88%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 5.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 5.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 5.88%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 5.88%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 5.88%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 5.88%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 5.88%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 5.88%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 5.88%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 5.88%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 5.88%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 4        | 23.53%  |
| Intel Xeon             | 3        | 17.65%  |
| Intel Celeron          | 2        | 11.76%  |
| Intel Core i5          | 1        | 5.88%   |
| Intel Core i3          | 1        | 5.88%   |
| Intel Core 2 Quad      | 1        | 5.88%   |
| AMD Ryzen Threadripper | 1        | 5.88%   |
| AMD Ryzen 9            | 1        | 5.88%   |
| AMD Ryzen 7            | 1        | 5.88%   |
| AMD Ryzen 5            | 1        | 5.88%   |
| AMD Ryzen 3            | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 47.06%  |
| 8      | 3        | 17.65%  |
| 12     | 2        | 11.76%  |
| 2      | 2        | 11.76%  |
| 24     | 1        | 5.88%   |
| 6      | 1        | 5.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 88.24%  |
| 2      | 2        | 11.76%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 64.71%  |
| 1      | 6        | 35.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 17       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 3        | 17.65%  |
| 0x306e4    | 2        | 11.76%  |
| 0x706a8    | 1        | 5.88%   |
| 0x40651    | 1        | 5.88%   |
| 0x306a9    | 1        | 5.88%   |
| 0x206c2    | 1        | 5.88%   |
| 0x206a7    | 1        | 5.88%   |
| 0x10677    | 1        | 5.88%   |
| 0x0a201009 | 1        | 5.88%   |
| 0x0870100a | 1        | 5.88%   |
| 0x08301039 | 1        | 5.88%   |
| 0x08108109 | 1        | 5.88%   |
| 0x0800820d | 1        | 5.88%   |
| Unknown    | 1        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 5        | 29.41%  |
| IvyBridge     | 3        | 17.65%  |
| Zen+          | 2        | 11.76%  |
| Zen 2         | 2        | 11.76%  |
| Zen 3         | 1        | 5.88%   |
| Westmere      | 1        | 5.88%   |
| SandyBridge   | 1        | 5.88%   |
| Penryn        | 1        | 5.88%   |
| Goldmont plus | 1        | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 50%     |
| Intel  | 6        | 33.33%  |
| AMD    | 3        | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 11.11%  |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 11.11%  |
| Nvidia TU117GL [T600]                                                       | 1        | 5.56%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 5.56%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 5.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 5.56%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 5.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 5.56%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 5.56%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 5.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 5.56%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 8        | 47.06%  |
| 1 x Intel      | 5        | 29.41%  |
| 1 x AMD        | 3        | 17.65%  |
| Intel + Nvidia | 1        | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 70.59%  |
| Proprietary | 4        | 23.53%  |
| Unknown     | 1        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 35.29%  |
| 1.01-2.0   | 4        | 23.53%  |
| 0.01-0.5   | 3        | 17.65%  |
| 5.01-6.0   | 1        | 5.88%   |
| 3.01-4.0   | 1        | 5.88%   |
| 8.01-16.0  | 1        | 5.88%   |
| 0.51-1.0   | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 46.15%  |
| Samsung Electronics | 3        | 23.08%  |
| Iiyama              | 2        | 15.38%  |
| Sony                | 1        | 7.69%   |
| ASUSTek Computer    | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sony LG TV SNY045B 1920x540                                         | 1        | 7.14%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch   | 1        | 7.14%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch | 1        | 7.14%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch  | 1        | 7.14%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                | 1        | 7.14%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                 | 1        | 7.14%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                    | 1        | 7.14%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                     | 1        | 7.14%   |
| Dell LCD Monitor U2414H 3840x1080                                   | 1        | 7.14%   |
| Dell LCD Monitor U2414H                                             | 1        | 7.14%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                   | 1        | 7.14%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                   | 1        | 7.14%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                   | 1        | 7.14%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch        | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 4        | 28.57%  |
| 3840x1080        | 2        | 14.29%  |
| 1600x900 (HD+)   | 2        | 14.29%  |
| 1280x1024 (SXGA) | 2        | 14.29%  |
| 3840x2160 (4K)   | 1        | 7.14%   |
| 1920x540         | 1        | 7.14%   |
| 1440x900 (WXGA+) | 1        | 7.14%   |
| Unknown          | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 2        | 15.38%  |
| 19      | 2        | 15.38%  |
| 17      | 2        | 15.38%  |
| 65      | 1        | 7.69%   |
| 48      | 1        | 7.69%   |
| 31      | 1        | 7.69%   |
| 27      | 1        | 7.69%   |
| 24      | 1        | 7.69%   |
| 20      | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 30.77%  |
| 401-500     | 3        | 23.08%  |
| 301-350     | 2        | 15.38%  |
| 1001-1500   | 2        | 15.38%  |
| 601-700     | 1        | 7.69%   |
| Unknown     | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 61.54%  |
| 5/4     | 2        | 15.38%  |
| 32/9    | 1        | 7.69%   |
| 16/10   | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 23.08%  |
| 151-200        | 3        | 23.08%  |
| 141-150        | 2        | 15.38%  |
| More than 1000 | 1        | 7.69%   |
| 351-500        | 1        | 7.69%   |
| 301-350        | 1        | 7.69%   |
| 501-1000       | 1        | 7.69%   |
| Unknown        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 76.92%  |
| 1-50    | 1        | 7.69%   |
| 121-160 | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 70.59%  |
| 0     | 4        | 23.53%  |
| 2     | 1        | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 8        | 34.78%  |
| Realtek Semiconductor     | 7        | 30.43%  |
| Qualcomm Atheros          | 2        | 8.7%    |
| Solarflare Communications | 1        | 4.35%   |
| Microsoft                 | 1        | 4.35%   |
| Marvell Technology Group  | 1        | 4.35%   |
| Linksys                   | 1        | 4.35%   |
| BUFFALO                   | 1        | 4.35%   |
| Broadcom                  | 1        | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 25.93%  |
| Intel I211 Gigabit Network Connection                             | 2        | 7.41%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 7.41%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 3.7%    |
| Realtek 802.11ac NIC                                              | 1        | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 3.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 3.7%    |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 3.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 3.7%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 3.7%    |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 3.7%    |
| Intel Wireless 3165                                               | 1        | 3.7%    |
| Intel Wi-Fi 6 AX200                                               | 1        | 3.7%    |
| Intel Ethernet Connection I217-V                                  | 1        | 3.7%    |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 3.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 2        | 25%     |
| Intel                 | 2        | 25%     |
| Realtek Semiconductor | 1        | 12.5%   |
| Microsoft             | 1        | 12.5%   |
| Linksys               | 1        | 12.5%   |
| BUFFALO               | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                       | 1        | 11.11%  |
| Realtek 802.11ac NIC                                     | 1        | 11.11%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter         | 1        | 11.11%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter         | 1        | 11.11%  |
| Microsoft Xbox 360 Wireless Adapter                      | 1        | 11.11%  |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter      | 1        | 11.11%  |
| Intel Wireless 3165                                      | 1        | 11.11%  |
| Intel Wi-Fi 6 AX200                                      | 1        | 11.11%  |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070] | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 7        | 41.18%  |
| Intel                     | 7        | 41.18%  |
| Solarflare Communications | 1        | 5.88%   |
| Marvell Technology Group  | 1        | 5.88%   |
| Broadcom                  | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 38.89%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.11%  |
| Intel Ethernet Connection I217-LM                                 | 2        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 11.11%  |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 5.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 5.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 5.56%   |
| Intel Ethernet Connection I217-V                                  | 1        | 5.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 68%     |
| WiFi     | 8        | 32%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 83.33%  |
| WiFi     | 3        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 64.71%  |
| 2     | 6        | 35.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 88.24%  |
| Yes  | 2        | 11.76%  |

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
| Intel               | 12       | 41.38%  |
| Nvidia              | 9        | 31.03%  |
| AMD                 | 6        | 20.69%  |
| C-Media Electronics | 1        | 3.45%   |
| ASUSTek Computer    | 1        | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 8.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 8.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 8.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 5.88%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 5.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 5.88%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 5.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 2.94%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.94%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 2.94%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 2.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 2.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 2.94%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 2.94%   |
| C-Media Electronics Anua Mic CM 900                                        | 1        | 2.94%   |
| ASUSTek Computer USB Audio                                                 | 1        | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 3        | 25%     |
| Unknown             | 2        | 16.67%  |
| Samsung Electronics | 2        | 16.67%  |
| Micron Technology   | 2        | 16.67%  |
| SK Hynix            | 1        | 8.33%   |
| Kingston            | 1        | 8.33%   |
| Corsair             | 1        | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s       | 1        | 8.33%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s             | 1        | 8.33%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s | 1        | 8.33%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s  | 1        | 8.33%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s | 1        | 8.33%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s             | 1        | 8.33%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s  | 1        | 8.33%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 1600MT/s  | 1        | 8.33%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s  | 1        | 8.33%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s | 1        | 8.33%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s   | 1        | 8.33%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s | 1        | 8.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 5        | 45.45%  |
| DDR3 | 5        | 45.45%  |
| DDR2 | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 10       | 90.91%  |
| SODIMM | 1        | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 5        | 45.45%  |
| 32768 | 2        | 18.18%  |
| 4096  | 2        | 18.18%  |
| 2048  | 1        | 9.09%   |
| 1024  | 1        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 3        | 25%     |
| 1600  | 2        | 16.67%  |
| 2933  | 1        | 8.33%   |
| 2666  | 1        | 8.33%   |
| 2400  | 1        | 8.33%   |
| 2200  | 1        | 8.33%   |
| 1866  | 1        | 8.33%   |
| 1800  | 1        | 8.33%   |
| 667   | 1        | 8.33%   |

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
| Huawei UVC Camera           | 1        | 33.33%  |

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
| 0     | 13       | 76.47%  |
| 1     | 3        | 17.65%  |
| 2     | 1        | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 3        | 75%     |
| Graphics card | 1        | 25%     |

