TUXEDO OS - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for TUXEDO OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 26

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | X570-A PRO                  | [78df342ad3](https://linux-hardware.org/?probe=78df342ad3) | Oct 21, 2023 |
| Gigabyte | B560M AORUS PRO AX          | [5573fff3e6](https://linux-hardware.org/?probe=5573fff3e6) | Oct 17, 2023 |
| ASRock   | A520M-HVS                   | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| ASRock   | A520M-HVS                   | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| ASUSTek  | ROG STRIX Z590-A GAMING ... | [6d7c6c42f5](https://linux-hardware.org/?probe=6d7c6c42f5) | Sep 14, 2023 |
| ASUSTek  | ROG STRIX Z590-A GAMING ... | [fe64bd3017](https://linux-hardware.org/?probe=fe64bd3017) | Sep 13, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| ASUSTek  | ROG STRIX B550-I GAMING     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| ASUSTek  | PRIME B450-PLUS             | [fde0e0e94f](https://linux-hardware.org/?probe=fde0e0e94f) | Jul 29, 2023 |
| ASRock   | H170M Pro4                  | [818c9bc358](https://linux-hardware.org/?probe=818c9bc358) | Jun 14, 2023 |
| Lenovo   | 30D9 SDK0J40697 WIN 3305... | [7332acbb0e](https://linux-hardware.org/?probe=7332acbb0e) | May 15, 2023 |
| MSI      | PRO Z690-A WIFI DDR4        | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Gigabyte | H81M-HD3                    | [8aaef31933](https://linux-hardware.org/?probe=8aaef31933) | Mar 19, 2023 |
| Dell     | 051FJ8 A02                  | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek  | TUF Gaming H470-PRO         | [769cd87ebd](https://linux-hardware.org/?probe=769cd87ebd) | Mar 07, 2023 |
| ASUSTek  | TUF Gaming H470-PRO         | [e1846f2a68](https://linux-hardware.org/?probe=e1846f2a68) | Mar 07, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [886aa04456](https://linux-hardware.org/?probe=886aa04456) | Mar 07, 2023 |
| MSI      | MAG B560M MORTAR WIFI       | [9088ef4d11](https://linux-hardware.org/?probe=9088ef4d11) | Mar 06, 2023 |
| ASUSTek  | P8H61-M LX                  | [01f7386d8c](https://linux-hardware.org/?probe=01f7386d8c) | Mar 02, 2023 |
| ASRock   | Z270M-ITX/ac                | [4f507f4e5a](https://linux-hardware.org/?probe=4f507f4e5a) | Feb 20, 2023 |
| ASUSTek  | PRIME H410M-K               | [7cc71e6021](https://linux-hardware.org/?probe=7cc71e6021) | Feb 12, 2023 |
| HP       | 2B34                        | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| HP       | 8906 SMVB                   | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| TUXEDO OS 22.04 | 20       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| TUXEDO OS | 20       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 6.2.0-10018-tuxedo  | 4        | 20%     |
| 6.1.0-1009-tuxedo   | 4        | 20%     |
| 6.2.0-10007-tuxedo  | 3        | 15%     |
| 5.15.0-10058-tuxedo | 3        | 15%     |
| 6.2.0-10027-tuxedo  | 2        | 10%     |
| 6.2.0-10022-tuxedo  | 2        | 10%     |
| 5.15.0-10057-tuxedo | 1        | 5%      |
| 5.15.0-10056-tuxedo | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 11       | 55%     |
| 5.15.0  | 5        | 25%     |
| 6.1.0   | 4        | 20%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 11       | 55%     |
| 5.15    | 5        | 25%     |
| 6.1     | 4        | 20%     |

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


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 20       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 17       | 85%     |
| Wayland | 3        | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 90%     |
| SDDM    | 2        | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| de_DE | 9        | 45%     |
| en_US | 4        | 20%     |
| en_ZA | 2        | 10%     |
| pt_PT | 1        | 5%      |
| pl_PL | 1        | 5%      |
| en_AG | 1        | 5%      |
| de_CH | 1        | 5%      |
| de_AT | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 90%     |
| EFI  | 2        | 10%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 16       | 76.19%  |
| Btrfs | 3        | 14.29%  |
| Xfs   | 2        | 9.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 90%     |
| GPT     | 2        | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 95%     |
| Yes       | 1        | 5%      |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 90%     |
| Yes       | 2        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 7        | 35%     |
| MSI                 | 4        | 20%     |
| ASRock              | 3        | 15%     |
| Hewlett-Packard     | 2        | 10%     |
| Gigabyte Technology | 2        | 10%     |
| Lenovo              | 1        | 5%      |
| Dell                | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7D17                          | 2        | 10%     |
| ASUS PRIME B450-PLUS                 | 2        | 10%     |
| MSI MS-7D25                          | 1        | 5%      |
| MSI MS-7C37                          | 1        | 5%      |
| Lenovo ThinkCentre M700 10GSS05X48   | 1        | 5%      |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 5%      |
| HP 280 G1 MT                         | 1        | 5%      |
| Gigabyte H81M-HD3                    | 1        | 5%      |
| Gigabyte B560M AORUS PRO AX          | 1        | 5%      |
| Dell OptiPlex 9010                   | 1        | 5%      |
| ASUS TUF Gaming H470-PRO             | 1        | 5%      |
| ASUS ROG STRIX Z590-A GAMING WIFI    | 1        | 5%      |
| ASUS ROG STRIX B550-I GAMING         | 1        | 5%      |
| ASUS PRIME H410M-K                   | 1        | 5%      |
| ASUS P8H61-M LX                      | 1        | 5%      |
| ASRock Z270M-ITX/ac                  | 1        | 5%      |
| ASRock H170M Pro4                    | 1        | 5%      |
| ASRock A520M-HVS                     | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 3        | 15%     |
| MSI MS-7D17        | 2        | 10%     |
| ASUS ROG           | 2        | 10%     |
| MSI MS-7D25        | 1        | 5%      |
| MSI MS-7C37        | 1        | 5%      |
| Lenovo ThinkCentre | 1        | 5%      |
| HP Pavilion        | 1        | 5%      |
| HP 280             | 1        | 5%      |
| Gigabyte H81M-HD3  | 1        | 5%      |
| Gigabyte B560M     | 1        | 5%      |
| Dell OptiPlex      | 1        | 5%      |
| ASUS TUF           | 1        | 5%      |
| ASUS P8H61-M       | 1        | 5%      |
| ASRock Z270M-ITX   | 1        | 5%      |
| ASRock H170M       | 1        | 5%      |
| ASRock A520M-HVS   | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 6        | 30%     |
| 2020 | 4        | 20%     |
| 2018 | 2        | 10%     |
| 2013 | 2        | 10%     |
| 2022 | 1        | 5%      |
| 2019 | 1        | 5%      |
| 2016 | 1        | 5%      |
| 2015 | 1        | 5%      |
| 2014 | 1        | 5%      |
| 2011 | 1        | 5%      |

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
| 16.01-24.0  | 5        | 25%     |
| 32.01-64.0  | 4        | 20%     |
| 4.01-8.0    | 3        | 15%     |
| 3.01-4.0    | 3        | 15%     |
| 8.01-16.0   | 3        | 15%     |
| 24.01-32.0  | 1        | 5%      |
| 64.01-256.0 | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 8        | 38.1%   |
| 1.01-2.0  | 5        | 23.81%  |
| 4.01-8.0  | 4        | 19.05%  |
| 3.01-4.0  | 2        | 9.52%   |
| 8.01-16.0 | 2        | 9.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 40%     |
| 4      | 4        | 20%     |
| 1      | 4        | 20%     |
| 5      | 3        | 15%     |
| 6      | 1        | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 70%     |
| Yes       | 6        | 30%     |

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
| Yes       | 11       | 55%     |
| No        | 9        | 45%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 52.38%  |
| Yes       | 10       | 47.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 9        | 45%     |
| South Africa | 2        | 10%     |
| Switzerland  | 1        | 5%      |
| Romania      | 1        | 5%      |
| Portugal     | 1        | 5%      |
| Poland       | 1        | 5%      |
| Netherlands  | 1        | 5%      |
| Italy        | 1        | 5%      |
| Egypt        | 1        | 5%      |
| Austria      | 1        | 5%      |
| Aruba        | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Hürth                    | 2        | 10%     |
| Zurich                    | 1        | 5%      |
| Zalău                    | 1        | 5%      |
| Vienna                    | 1        | 5%      |
| Ulm                       | 1        | 5%      |
| Quarteira                 | 1        | 5%      |
| Peitz                     | 1        | 5%      |
| Oranjestad                | 1        | 5%      |
| Offenbach                 | 1        | 5%      |
| Lublin                    | 1        | 5%      |
| Leipzig                   | 1        | 5%      |
| Johannesburg              | 1        | 5%      |
| Frankfurt am Main         | 1        | 5%      |
| Florence                  | 1        | 5%      |
| Eberswalde                | 1        | 5%      |
| Cairo                     | 1        | 5%      |
| Bloemfontein              | 1        | 5%      |
| Bad Neustadt an der Saale | 1        | 5%      |
| Amsterdam                 | 1        | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 9        | 14     | 19.57%  |
| Samsung Electronics         | 8        | 12     | 17.39%  |
| SanDisk                     | 5        | 7      | 10.87%  |
| WDC                         | 3        | 4      | 6.52%   |
| Micron/Crucial Technology   | 2        | 4      | 4.35%   |
| Hitachi                     | 2        | 3      | 4.35%   |
| GOODRAM                     | 2        | 2      | 4.35%   |
| SK hynix                    | 1        | 1      | 2.17%   |
| Silicon Motion              | 1        | 2      | 2.17%   |
| Phison                      | 1        | 1      | 2.17%   |
| Lite-On Technology          | 1        | 1      | 2.17%   |
| Kingston Technology Company | 1        | 1      | 2.17%   |
| Kingston                    | 1        | 1      | 2.17%   |
| KingFast                    | 1        | 1      | 2.17%   |
| HS-SSD-E100                 | 1        | 1      | 2.17%   |
| Hikvision                   | 1        | 2      | 2.17%   |
| HGST HTS                    | 1        | 1      | 2.17%   |
| HGST                        | 1        | 1      | 2.17%   |
| China                       | 1        | 1      | 2.17%   |
| ASMT                        | 1        | 1      | 2.17%   |
| Apacer                      | 1        | 1      | 2.17%   |
| AMD                         | 1        | 2      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 980 500GB                             | 3        | 5.45%   |
| Seagate ST3500418AS 500GB                         | 2        | 3.64%   |
| Seagate ST1000VT001-1RE172 1TB                    | 2        | 3.64%   |
| Seagate ST1000DM010-2EP102 1TB                    | 2        | 3.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 2        | 3.64%   |
| SanDisk SSD PLUS 120GB                            | 2        | 3.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB             | 2        | 3.64%   |
| Hitachi HCS545050GLA380 500GB                     | 2        | 3.64%   |
| WDC WD80EAZZ-00BKLB0 8TB                          | 1        | 1.82%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 1        | 1.82%   |
| WDC WD10JPVX-11JC3T0 1TB                          | 1        | 1.82%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 1        | 1.82%   |
| SK hynix SHGP31-1000GM 1TB                        | 1        | 1.82%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1        | 1.82%   |
| Seagate ST500DM002-1BD142 500GB                   | 1        | 1.82%   |
| Seagate ST3500413AS 500GB                         | 1        | 1.82%   |
| Seagate ST2000LM007-1R8174 2TB                    | 1        | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB                    | 1        | 1.82%   |
| Seagate ST1000DX001-1NS162-SSHD 1TB               | 1        | 1.82%   |
| Seagate ST10000NM001G-2MW103 10TB                 | 1        | 1.82%   |
| Sandisk WD_BLACK SN770 2TB                        | 1        | 1.82%   |
| Sandisk WD Black SN850 1TB                        | 1        | 1.82%   |
| Samsung SSD 990 PRO 2TB                           | 1        | 1.82%   |
| Samsung SSD 980 1TB                               | 1        | 1.82%   |
| Samsung SSD 860 QVO 1TB                           | 1        | 1.82%   |
| Samsung SSD 860 EVO 1TB                           | 1        | 1.82%   |
| Samsung SSD 850 PRO 128GB                         | 1        | 1.82%   |
| Samsung SSD 850 EVO 500GB                         | 1        | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 1.82%   |
| Samsung HD321KJ 320GB                             | 1        | 1.82%   |
| Phison Sabrent Rocket Q4 1TB                      | 1        | 1.82%   |
| Micron/Crucial CT1000P5PSSD8 1TB                  | 1        | 1.82%   |
| Lite-On PLEXTOR PX-256M9PeY 256GB                 | 1        | 1.82%   |
| Kingston Company A2000 NVMe SSD 250GB             | 1        | 1.82%   |
| Kingston SUV400S37120G 120GB SSD                  | 1        | 1.82%   |
| KingFast 240GB                                    | 1        | 1.82%   |
| HS-SSD-E100 128G                                  | 1        | 1.82%   |
| Hikvision HS-SSD-E2000 256G                       | 1        | 1.82%   |
| HGST HTS725050A7E630 500GB                        | 1        | 1.82%   |
| HGST HTS 725050A7E630 500GB                       | 1        | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 14     | 52.94%  |
| WDC                 | 3        | 4      | 17.65%  |
| Hitachi             | 2        | 3      | 11.76%  |
| Samsung Electronics | 1        | 1      | 5.88%   |
| HGST HTS            | 1        | 1      | 5.88%   |
| HGST                | 1        | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 27.27%  |
| SanDisk             | 2        | 3      | 18.18%  |
| GOODRAM             | 2        | 2      | 18.18%  |
| Kingston            | 1        | 1      | 9.09%   |
| China               | 1        | 1      | 9.09%   |
| ASMT                | 1        | 1      | 9.09%   |
| Apacer              | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 14       | 25     | 35.9%   |
| HDD     | 14       | 24     | 35.9%   |
| SSD     | 9        | 13     | 23.08%  |
| Unknown | 2        | 2      | 5.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 37     | 51.61%  |
| NVMe | 14       | 25     | 45.16%  |
| SAS  | 1        | 2      | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 10       | 14     | 41.67%  |
| 0.01-0.5   | 10       | 19     | 41.67%  |
| 1.01-2.0   | 2        | 2      | 8.33%   |
| 4.01-10.0  | 2        | 2      | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 6        | 28.57%  |
| 251-500        | 4        | 19.05%  |
| 101-250        | 4        | 19.05%  |
| 1001-2000      | 3        | 14.29%  |
| 2001-3000      | 2        | 9.52%   |
| More than 3000 | 1        | 4.76%   |
| 21-50          | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 6        | 28.57%  |
| 1-20           | 4        | 19.05%  |
| 501-1000       | 3        | 14.29%  |
| 251-500        | 2        | 9.52%   |
| 101-250        | 2        | 9.52%   |
| 51-100         | 2        | 9.52%   |
| More than 3000 | 1        | 4.76%   |
| 1001-2000      | 1        | 4.76%   |

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
| Detected | 18       | 56     | 85.71%  |
| Works    | 3        | 8      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 14       | 37.84%  |
| Samsung Electronics         | 6        | 16.22%  |
| AMD                         | 6        | 16.22%  |
| SanDisk                     | 3        | 8.11%   |
| Micron/Crucial Technology   | 2        | 5.41%   |
| SK hynix                    | 1        | 2.7%    |
| Silicon Motion              | 1        | 2.7%    |
| Phison Electronics          | 1        | 2.7%    |
| Lite-On Technology          | 1        | 2.7%    |
| Kingston Technology Company | 1        | 2.7%    |
| ASMedia Technology          | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 9.09%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 9.09%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 6.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2        | 4.55%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 4.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 4.55%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 4.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 1        | 2.27%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 2.27%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 2.27%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 2.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.27%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 1        | 2.27%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 2.27%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 2.27%   |
| Lite-On M9PeG, M9PeGN, M9PeY NVMe SSD                                                   | 1        | 2.27%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 1        | 2.27%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 2.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 2.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.27%   |
| AMD FCH SATA Controller [RAID Bottom]                                                   | 1        | 2.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 52.94%  |
| NVMe | 14       | 41.18%  |
| RAID | 1        | 2.94%   |
| IDE  | 1        | 2.94%   |

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


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz         | 2        | 10%     |
| AMD Ryzen 5 5600G with Radeon Graphics   | 2        | 10%     |
| Intel Pentium CPU G3420 @ 3.20GHz        | 1        | 5%      |
| Intel Core i5-7600T CPU @ 2.80GHz        | 1        | 5%      |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 5%      |
| Intel Core i5-10500 CPU @ 3.10GHz        | 1        | 5%      |
| Intel Core i5-10400F CPU @ 2.90GHz       | 1        | 5%      |
| Intel Core i5-10400 CPU @ 2.90GHz        | 1        | 5%      |
| Intel Core i3-6300 CPU @ 3.80GHz         | 1        | 5%      |
| Intel Core i3-6100 CPU @ 3.70GHz         | 1        | 5%      |
| Intel 12th Gen Core i9-12900KS           | 1        | 5%      |
| Intel 11th Gen Core i7-11700 @ 2.50GHz   | 1        | 5%      |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz | 1        | 5%      |
| Intel 11th Gen Core i5-11400T @ 1.30GHz  | 1        | 5%      |
| AMD Ryzen 7 5700G with Radeon Graphics   | 1        | 5%      |
| AMD Ryzen 7 3700X 8-Core Processor       | 1        | 5%      |
| AMD Ryzen 5 3600X 6-Core Processor       | 1        | 5%      |
| AMD Ryzen 3 4100 4-Core Processor        | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i5 | 7        | 35%     |
| Other         | 4        | 20%     |
| AMD Ryzen 5   | 3        | 15%     |
| Intel Core i3 | 2        | 10%     |
| AMD Ryzen 7   | 2        | 10%     |
| Intel Pentium | 1        | 5%      |
| AMD Ryzen 3   | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 8        | 40%     |
| 4      | 5        | 25%     |
| 8      | 3        | 15%     |
| 2      | 3        | 15%     |
| 16     | 1        | 5%      |

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
| 2      | 15       | 75%     |
| 1      | 5        | 25%     |

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
| Unknown    | 17       | 85%     |
| 0xa0653    | 1        | 5%      |
| 0x0a50000d | 1        | 5%      |
| 0x08701030 | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 4        | 20%     |
| Zen 3     | 3        | 15%     |
| Zen 2     | 3        | 15%     |
| CometLake | 3        | 15%     |
| Skylake   | 2        | 10%     |
| IvyBridge | 2        | 10%     |
| Haswell   | 2        | 10%     |
| KabyLake  | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 42.86%  |
| Intel  | 9        | 42.86%  |
| AMD    | 3        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 14.29%  |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 9.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 9.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 9.52%   |
| Intel HD Graphics 530                                                       | 2        | 9.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 4.76%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 4.76%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 4.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 4.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 4.76%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 4.76%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 4.76%   |
| Intel HD Graphics 630                                                       | 1        | 4.76%   |
| Intel AlderLake-S GT1                                                       | 1        | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 9        | 45%     |
| 1 x Intel  | 8        | 40%     |
| 1 x AMD    | 3        | 15%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 11       | 55%     |
| Proprietary | 9        | 45%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 55%     |
| 7.01-8.0   | 2        | 10%     |
| 5.01-6.0   | 2        | 10%     |
| 3.01-4.0   | 2        | 10%     |
| 1.01-2.0   | 2        | 10%     |
| 0.01-0.5   | 1        | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 30%     |
| Acer                | 5        | 25%     |
| Dell                | 2        | 10%     |
| ViewSonic           | 1        | 5%      |
| Philips             | 1        | 5%      |
| Hewlett-Packard     | 1        | 5%      |
| Goldstar            | 1        | 5%      |
| Eizo                | 1        | 5%      |
| BenQ                | 1        | 5%      |
| AOC                 | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                   | 2        | 8%      |
| Acer EK240Y ACR0758 1920x1080 520x320mm 24.0-inch                     | 2        | 8%      |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                | 1        | 4%      |
| Samsung Electronics SyncMaster SAM0486 1920x1080                      | 1        | 4%      |
| Samsung Electronics SMB1930HD SAM0708 1360x768 410x230mm 18.5-inch    | 1        | 4%      |
| Samsung Electronics S27C36x SAM7315 1920x1080 598x336mm 27.0-inch     | 1        | 4%      |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch     | 1        | 4%      |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 4%      |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1        | 4%      |
| Samsung Electronics LC27T55 SAM701E 1920x1080 610x350mm 27.7-inch     | 1        | 4%      |
| Samsung Electronics C32R50x SAM7000 1920x1080 698x393mm 31.5-inch     | 1        | 4%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 4%      |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch                   | 1        | 4%      |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 1        | 4%      |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch                   | 1        | 4%      |
| Eizo EV2736W ENC2383 2560x1440 597x336mm 27.0-inch                    | 1        | 4%      |
| Dell S2421HN DEL41F2 1920x1080 527x296mm 23.8-inch                    | 1        | 4%      |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                        | 1        | 4%      |
| AOC LCD Monitor 25G3ZM 3840x1080                                      | 1        | 4%      |
| AOC LCD Monitor 25G3ZM                                                | 1        | 4%      |
| Acer Z35 ACR0478 2560x1080 814x346mm 34.8-inch                        | 1        | 4%      |
| Acer VG270 ACR06C0 1920x1080 598x336mm 27.0-inch                      | 1        | 4%      |
| Acer QG241Y ACR079C 1920x1080 527x296mm 23.8-inch                     | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 11       | 55%     |
| 2560x1440 (QHD)   | 2        | 10%     |
| 3840x1080         | 1        | 5%      |
| 2560x1080         | 1        | 5%      |
| 1920x1200 (WUXGA) | 1        | 5%      |
| 1600x900 (HD+)    | 1        | 5%      |
| 1360x768          | 1        | 5%      |
| 1280x1024 (SXGA)  | 1        | 5%      |
| Unknown           | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 26.09%  |
| 24      | 6        | 26.09%  |
| 23      | 2        | 8.7%    |
| Unknown | 2        | 8.7%    |
| 46      | 1        | 4.35%   |
| 34      | 1        | 4.35%   |
| 31      | 1        | 4.35%   |
| 21      | 1        | 4.35%   |
| 20      | 1        | 4.35%   |
| 18      | 1        | 4.35%   |
| 17      | 1        | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 55%     |
| 401-500     | 3        | 15%     |
| Unknown     | 2        | 10%     |
| 801-900     | 1        | 5%      |
| 601-700     | 1        | 5%      |
| 301-350     | 1        | 5%      |
| 1001-1500   | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 73.68%  |
| 16/10   | 2        | 10.53%  |
| 5/4     | 1        | 5.26%   |
| 21/9    | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 30.43%  |
| 301-350        | 6        | 26.09%  |
| 351-500        | 2        | 8.7%    |
| 251-300        | 2        | 8.7%    |
| 141-150        | 2        | 8.7%    |
| Unknown        | 2        | 8.7%    |
| 151-200        | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 70%     |
| 101-120 | 3        | 15%     |
| Unknown | 2        | 10%     |
| 1-50    | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 70%     |
| 2     | 4        | 20%     |
| 3     | 2        | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 50%     |
| Intel                 | 10       | 38.46%  |
| Qualcomm Atheros      | 1        | 3.85%   |
| D-Link                | 1        | 3.85%   |
| Broadcom              | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 10       | 30.3%   |
| Intel Ethernet Controller I225-V                                     | 4        | 12.12%  |
| Intel Wi-Fi 6 AX200                                                  | 3        | 9.09%   |
| Realtek RTL8125 2.5GbE Controller                                    | 2        | 6.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2        | 6.06%   |
| Intel Ethernet Connection (2) I219-V                                 | 2        | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 3.03%   |
| Realtek 802.11ac NIC                                                 | 1        | 3.03%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1        | 3.03%   |
| Intel Wireless 3160                                                  | 1        | 3.03%   |
| Intel I211 Gigabit Network Connection                                | 1        | 3.03%   |
| Intel Ethernet Connection (11) I219-V                                | 1        | 3.03%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 1        | 3.03%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 3.03%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                       | 1        | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 63.64%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Qualcomm Atheros      | 1        | 9.09%   |
| D-Link                | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 3        | 27.27%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2        | 18.18%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 9.09%   |
| Realtek 802.11ac NIC                                                 | 1        | 9.09%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1        | 9.09%   |
| Intel Wireless 3160                                                  | 1        | 9.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 9.09%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 57.14%  |
| Intel                 | 8        | 38.1%   |
| Broadcom              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 45.45%  |
| Intel Ethernet Controller I225-V                                  | 4        | 18.18%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 9.09%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 9.09%   |
| Intel I211 Gigabit Network Connection                             | 1        | 4.55%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.55%   |
| Broadcom NetXtreme II BCM5706 Gigabit Ethernet                    | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 64.52%  |
| WiFi     | 11       | 35.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 76.19%  |
| WiFi     | 5        | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 50%     |
| 2     | 8        | 40%     |
| 3     | 2        | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 75%     |
| Yes  | 5        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 6        | 60%     |
| Cambridge Silicon Radio | 2        | 20%     |
| Realtek Semiconductor   | 1        | 10%     |
| Unknown                 | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 2        | 20%     |
| Intel AX200 Bluetooth                               | 2        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 20%     |
| Realtek Bluetooth Radio                             | 1        | 10%     |
| Intel Bluetooth wireless interface                  | 1        | 10%     |
| Intel Bluetooth Device                              | 1        | 10%     |
| Unknown                                             | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 13       | 40.63%  |
| Nvidia              | 9        | 28.13%  |
| AMD                 | 5        | 15.63%  |
| Valve Software      | 1        | 3.13%   |
| Razer USA           | 1        | 3.13%   |
| JMTek               | 1        | 3.13%   |
| Creative Technology | 1        | 3.13%   |
| Creative Labs       | 1        | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                                              | 4        | 10.81%  |
| AMD Family 17h/19h HD Audio Controller                                                          | 4        | 10.81%  |
| Nvidia TU116 High Definition Audio Controller                                                   | 2        | 5.41%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 5.41%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 2        | 5.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 5.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 2        | 5.41%   |
| Valve Software Valve VR Radio & HMD Mic                                                         | 1        | 2.7%    |
| Razer USA Razer Seiren Mini                                                                     | 1        | 2.7%    |
| Nvidia TU106 High Definition Audio Controller                                                   | 1        | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                 | 1        | 2.7%    |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 2.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 1        | 2.7%    |
| JMTek USB Audio Device                                                                          | 1        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 2.7%    |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 1        | 2.7%    |
| Intel Comet Lake PCH-V cAVS                                                                     | 1        | 2.7%    |
| Intel Comet Lake PCH cAVS                                                                       | 1        | 2.7%    |
| Intel Alder Lake-S HD Audio Controller                                                          | 1        | 2.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 1        | 2.7%    |
| Intel 200 Series PCH HD Audio                                                                   | 1        | 2.7%    |
| Creative Technology SB X-Fi Surround 5.1 Pro                                                    | 1        | 2.7%    |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                                                        | 1        | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Micron Technology | 1        | 25%     |
| KLEVV             | 1        | 25%     |
| Kingston          | 1        | 25%     |
| Crucial           | 1        | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s    | 1        | 25%     |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s     | 1        | 25%     |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 1        | 25%     |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s | 1        | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 3        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 3        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2        | 66.67%  |
| 16384 | 1        | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3733  | 1        | 33.33%  |
| 3200  | 1        | 33.33%  |
| 2666  | 1        | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Prolific Technology | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 100%    |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Valve Software                         | 1        | 16.67%  |
| Sunplus Innovation Technology          | 1        | 16.67%  |
| Sony Ericsson Mobile Communications AB | 1        | 16.67%  |
| Microdia                               | 1        | 16.67%  |
| Lenovo                                 | 1        | 16.67%  |
| KYE Systems (Mouse Systems)            | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Valve Software 3D Camera                   | 1        | 16.67%  |
| Sunplus SPCA2281 Web Camera                | 1        | 16.67%  |
| Sony Ericsson Mobile AB XQ-CC54            | 1        | 16.67%  |
| Microdia Sonix USB 2.0 Camera              | 1        | 16.67%  |
| Lenovo FHD Webcam Audio                    | 1        | 16.67%  |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 16.67%  |

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
| 0     | 18       | 90%     |
| 1     | 2        | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 50%     |
| Camera       | 1        | 50%     |

