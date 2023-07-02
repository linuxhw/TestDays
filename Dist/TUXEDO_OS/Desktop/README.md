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

Total: 14

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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
| TUXEDO OS 22.04 | 12       | 100%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| TUXEDO OS | 12       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 6.1.0-1009-tuxedo   | 4        | 33.33%  |
| 6.2.0-10007-tuxedo  | 3        | 25%     |
| 5.15.0-10058-tuxedo | 3        | 25%     |
| 5.15.0-10057-tuxedo | 1        | 8.33%   |
| 5.15.0-10056-tuxedo | 1        | 8.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 5        | 41.67%  |
| 6.1.0   | 4        | 33.33%  |
| 6.2.0   | 3        | 25%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 5        | 41.67%  |
| 6.1     | 4        | 33.33%  |
| 6.2     | 3        | 25%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 12       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 12       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 11       | 91.67%  |
| Wayland | 1        | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 91.67%  |
| SDDM    | 1        | 8.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| de_DE | 4        | 33.33%  |
| en_ZA | 2        | 16.67%  |
| en_US | 2        | 16.67%  |
| pl_PL | 1        | 8.33%   |
| en_AG | 1        | 8.33%   |
| de_CH | 1        | 8.33%   |
| de_AT | 1        | 8.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 91.67%  |
| EFI  | 1        | 8.33%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 12       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 91.67%  |
| GPT     | 1        | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 91.67%  |
| Yes       | 1        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 91.67%  |
| Yes       | 1        | 8.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 3        | 25%     |
| MSI                 | 2        | 16.67%  |
| Hewlett-Packard     | 2        | 16.67%  |
| ASRock              | 2        | 16.67%  |
| Lenovo              | 1        | 8.33%   |
| Gigabyte Technology | 1        | 8.33%   |
| Dell                | 1        | 8.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI MS-7D25                          | 1        | 8.33%   |
| MSI MS-7D17                          | 1        | 8.33%   |
| Lenovo ThinkCentre M700 10GSS05X48   | 1        | 8.33%   |
| HP Pavilion Gaming Desktop TG01-2xxx | 1        | 8.33%   |
| HP 280 G1 MT                         | 1        | 8.33%   |
| Gigabyte H81M-HD3                    | 1        | 8.33%   |
| Dell OptiPlex 9010                   | 1        | 8.33%   |
| ASUS TUF Gaming H470-PRO             | 1        | 8.33%   |
| ASUS PRIME H410M-K                   | 1        | 8.33%   |
| ASUS P8H61-M LX                      | 1        | 8.33%   |
| ASRock Z270M-ITX/ac                  | 1        | 8.33%   |
| ASRock H170M Pro4                    | 1        | 8.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| MSI MS-7D25        | 1        | 8.33%   |
| MSI MS-7D17        | 1        | 8.33%   |
| Lenovo ThinkCentre | 1        | 8.33%   |
| HP Pavilion        | 1        | 8.33%   |
| HP 280             | 1        | 8.33%   |
| Gigabyte H81M-HD3  | 1        | 8.33%   |
| Dell OptiPlex      | 1        | 8.33%   |
| ASUS TUF           | 1        | 8.33%   |
| ASUS PRIME         | 1        | 8.33%   |
| ASUS P8H61-M       | 1        | 8.33%   |
| ASRock Z270M-ITX   | 1        | 8.33%   |
| ASRock H170M       | 1        | 8.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 3        | 25%     |
| 2020 | 2        | 16.67%  |
| 2015 | 2        | 16.67%  |
| 2013 | 2        | 16.67%  |
| 2022 | 1        | 8.33%   |
| 2016 | 1        | 8.33%   |
| 2011 | 1        | 8.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 12       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 12       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 3        | 25%     |
| 16.01-24.0  | 3        | 25%     |
| 4.01-8.0    | 2        | 16.67%  |
| 32.01-64.0  | 1        | 8.33%   |
| 24.01-32.0  | 1        | 8.33%   |
| 64.01-256.0 | 1        | 8.33%   |
| 8.01-16.0   | 1        | 8.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 6        | 50%     |
| 1.01-2.0 | 5        | 41.67%  |
| 3.01-4.0 | 1        | 8.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 41.67%  |
| 4      | 3        | 25%     |
| 1      | 3        | 25%     |
| 5      | 1        | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 58.33%  |
| Yes       | 5        | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 58.33%  |
| No        | 5        | 41.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 50%     |
| No        | 6        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Germany      | 4        | 33.33%  |
| South Africa | 2        | 16.67%  |
| Switzerland  | 1        | 8.33%   |
| Romania      | 1        | 8.33%   |
| Poland       | 1        | 8.33%   |
| Netherlands  | 1        | 8.33%   |
| Egypt        | 1        | 8.33%   |
| Austria      | 1        | 8.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Zurich                    | 1        | 8.33%   |
| Zalău                    | 1        | 8.33%   |
| Vienna                    | 1        | 8.33%   |
| Offenbach                 | 1        | 8.33%   |
| Lublin                    | 1        | 8.33%   |
| Leipzig                   | 1        | 8.33%   |
| Johannesburg              | 1        | 8.33%   |
| Frankfurt am Main         | 1        | 8.33%   |
| Cairo                     | 1        | 8.33%   |
| Bloemfontein              | 1        | 8.33%   |
| Bad Neustadt an der Saale | 1        | 8.33%   |
| Amsterdam                 | 1        | 8.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 20%     |
| Samsung Electronics | 5        | 8      | 20%     |
| WDC                 | 2        | 3      | 8%      |
| GOODRAM             | 2        | 2      | 8%      |
| Silicon Motion      | 1        | 2      | 4%      |
| Sandisk             | 1        | 1      | 4%      |
| Lite-On Technology  | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |
| HS-SSD-E100         | 1        | 1      | 4%      |
| Hikvision           | 1        | 2      | 4%      |
| HGST HTS            | 1        | 1      | 4%      |
| HGST                | 1        | 1      | 4%      |
| China               | 1        | 1      | 4%      |
| ASMT                | 1        | 1      | 4%      |
| Apacer              | 1        | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung SSD 980 500GB                               | 2        | 6.9%    |
| WDC WD80EAZZ-00BKLB0 8TB                            | 1        | 3.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 3.45%   |
| WDC WD10JPVX-11JC3T0 1TB                            | 1        | 3.45%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 480GB | 1        | 3.45%   |
| Seagate ST500DM002-1BD142 500GB                     | 1        | 3.45%   |
| Seagate ST3500413AS 500GB                           | 1        | 3.45%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1        | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1        | 3.45%   |
| Seagate ST1000DX001-1NS162-SSHD 1TB                 | 1        | 3.45%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 3.45%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 1        | 3.45%   |
| Samsung SSD 980 1TB                                 | 1        | 3.45%   |
| Samsung SSD 860 QVO 1TB                             | 1        | 3.45%   |
| Samsung SSD 860 EVO 1TB                             | 1        | 3.45%   |
| Samsung SSD 850 EVO 500GB                           | 1        | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1        | 3.45%   |
| Lite-On PLEXTOR PX-256M9PeY 256GB                   | 1        | 3.45%   |
| Kingston SUV400S37120G 120GB SSD                    | 1        | 3.45%   |
| HS-SSD-E100 128G                                    | 1        | 3.45%   |
| Hikvision HS-SSD-E2000 256G                         | 1        | 3.45%   |
| HGST HTS725050A7E630 500GB                          | 1        | 3.45%   |
| HGST HTS 725050A7E630 500GB                         | 1        | 3.45%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 1        | 3.45%   |
| GOODRAM SSDPR-CX400-01T-G2 1024GB                   | 1        | 3.45%   |
| China SSD 256GB                                     | 1        | 3.45%   |
| ASMT 2115 160GB                                     | 1        | 3.45%   |
| Apacer AS350 512GB SSD                              | 1        | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 5        | 6      | 55.56%  |
| WDC      | 2        | 3      | 22.22%  |
| HGST HTS | 1        | 1      | 11.11%  |
| HGST     | 1        | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 25%     |
| GOODRAM             | 2        | 2      | 25%     |
| Kingston            | 1        | 1      | 12.5%   |
| China               | 1        | 1      | 12.5%   |
| ASMT                | 1        | 1      | 12.5%   |
| Apacer              | 1        | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 9        | 11     | 39.13%  |
| NVMe    | 7        | 11     | 30.43%  |
| SSD     | 6        | 9      | 26.09%  |
| Unknown | 1        | 1      | 4.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 19     | 57.89%  |
| NVMe | 7        | 11     | 36.84%  |
| SAS  | 1        | 2      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 7        | 9      | 41.18%  |
| 0.51-1.0   | 6        | 7      | 35.29%  |
| 1.01-2.0   | 3        | 3      | 17.65%  |
| 4.01-10.0  | 1        | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 4        | 33.33%  |
| 501-1000   | 3        | 25%     |
| 251-500    | 2        | 16.67%  |
| 1001-2000  | 2        | 16.67%  |
| 21-50      | 1        | 8.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 4        | 33.33%  |
| 21-50   | 3        | 25%     |
| 251-500 | 2        | 16.67%  |
| 101-250 | 2        | 16.67%  |
| 51-100  | 1        | 8.33%   |

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
| Detected | 11       | 26     | 84.62%  |
| Works    | 2        | 6      | 15.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 11       | 57.89%  |
| Samsung Electronics | 4        | 21.05%  |
| Silicon Motion      | 1        | 5.26%   |
| SanDisk             | 1        | 5.26%   |
| Lite-On Technology  | 1        | 5.26%   |
| AMD                 | 1        | 5.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller 980                                                         | 3        | 14.29%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 9.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 9.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 4.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 4.76%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 4.76%   |
| Intel Comet Lake PCH-H RAID                                                             | 1        | 4.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 4.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 4.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 4.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 4.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 4.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 4.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 10       | 52.63%  |
| NVMe | 7        | 36.84%  |
| RAID | 1        | 5.26%   |
| IDE  | 1        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 91.67%  |
| AMD    | 1        | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 16.67%  |
| Intel Pentium CPU G3420 @ 3.20GHz      | 1        | 8.33%   |
| Intel Core i5-7600T CPU @ 2.80GHz      | 1        | 8.33%   |
| Intel Core i5-4590S CPU @ 3.00GHz      | 1        | 8.33%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 8.33%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 1        | 8.33%   |
| Intel Core i3-6300 CPU @ 3.80GHz       | 1        | 8.33%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 1        | 8.33%   |
| Intel 12th Gen Core i9-12900KS         | 1        | 8.33%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz | 1        | 8.33%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 1        | 8.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i5 | 6        | 50%     |
| Other         | 2        | 16.67%  |
| Intel Core i3 | 2        | 16.67%  |
| Intel Pentium | 1        | 8.33%   |
| AMD Ryzen 7   | 1        | 8.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 33.33%  |
| 2      | 3        | 25%     |
| 8      | 2        | 16.67%  |
| 6      | 2        | 16.67%  |
| 16     | 1        | 8.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 58.33%  |
| 1      | 5        | 41.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 83.33%  |
| 0xa0653    | 1        | 8.33%   |
| 0x0a50000d | 1        | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Skylake   | 2        | 16.67%  |
| IvyBridge | 2        | 16.67%  |
| Haswell   | 2        | 16.67%  |
| CometLake | 2        | 16.67%  |
| Unknown   | 2        | 16.67%  |
| Zen 3     | 1        | 8.33%   |
| KabyLake  | 1        | 8.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 66.67%  |
| Nvidia | 3        | 25%     |
| AMD    | 1        | 8.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 16.67%  |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 16.67%  |
| Intel HD Graphics 530                                                       | 2        | 16.67%  |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 8.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 8.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 8.33%   |
| Intel HD Graphics 630                                                       | 1        | 8.33%   |
| Intel AlderLake-S GT1                                                       | 1        | 8.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 8.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 8        | 66.67%  |
| 1 x Nvidia | 3        | 25%     |
| 1 x AMD    | 1        | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 75%     |
| Proprietary | 3        | 25%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 66.67%  |
| 7.01-8.0   | 1        | 8.33%   |
| 5.01-6.0   | 1        | 8.33%   |
| 1.01-2.0   | 1        | 8.33%   |
| 0.01-0.5   | 1        | 8.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 20%     |
| ViewSonic           | 1        | 10%     |
| Philips             | 1        | 10%     |
| Hewlett-Packard     | 1        | 10%     |
| Goldstar            | 1        | 10%     |
| Eizo                | 1        | 10%     |
| Dell                | 1        | 10%     |
| BenQ                | 1        | 10%     |
| Acer                | 1        | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch            | 1        | 9.09%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch | 1        | 9.09%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 1        | 9.09%   |
| Philips 170S4 PHL0818 1280x1024 338x270mm 17.0-inch               | 1        | 9.09%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch      | 1        | 9.09%   |
| Goldstar E2041 GSM4EC9 1600x900 443x249mm 20.0-inch               | 1        | 9.09%   |
| Eizo EV2736W ENC2383 2560x1440 597x336mm 27.0-inch                | 1        | 9.09%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch               | 1        | 9.09%   |
| Dell S2421HN DEL41F2 1920x1080 527x296mm 23.8-inch                | 1        | 9.09%   |
| BenQ LCD BNQ8024 2560x1440 597x336mm 27.0-inch                    | 1        | 9.09%   |
| Acer VG270 ACR06C0 1920x1080 598x336mm 27.0-inch                  | 1        | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 5        | 50%     |
| 2560x1440 (QHD)   | 2        | 20%     |
| 1920x1200 (WUXGA) | 1        | 10%     |
| 1600x900 (HD+)    | 1        | 10%     |
| 1280x1024 (SXGA)  | 1        | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 4        | 36.36%  |
| 24     | 3        | 27.27%  |
| 23     | 2        | 18.18%  |
| 20     | 1        | 9.09%   |
| 17     | 1        | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 80%     |
| 401-500     | 1        | 10%     |
| 301-350     | 1        | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 80%     |
| 5/4   | 1        | 10%     |
| 16/10 | 1        | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 4        | 40%     |
| 201-250        | 3        | 30%     |
| 251-300        | 1        | 10%     |
| 151-200        | 1        | 10%     |
| 141-150        | 1        | 10%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 80%     |
| 101-120 | 2        | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 83.33%  |
| 2     | 2        | 16.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 50%     |
| Intel                 | 6        | 37.5%   |
| Qualcomm Atheros      | 1        | 6.25%   |
| D-Link                | 1        | 6.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 6        | 30%     |
| Intel Ethernet Connection (2) I219-V                                 | 2        | 10%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 5%      |
| Realtek RTL8125 2.5GbE Controller                                    | 1        | 5%      |
| Realtek 802.11ac NIC                                                 | 1        | 5%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1        | 5%      |
| Intel Wireless 3160                                                  | 1        | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 5%      |
| Intel I211 Gigabit Network Connection                                | 1        | 5%      |
| Intel Ethernet Controller I225-V                                     | 1        | 5%      |
| Intel Ethernet Connection (11) I219-V                                | 1        | 5%      |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 1        | 5%      |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 5%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 42.86%  |
| Realtek Semiconductor | 2        | 28.57%  |
| Qualcomm Atheros      | 1        | 14.29%  |
| D-Link                | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 14.29%  |
| Realtek 802.11ac NIC                                                 | 1        | 14.29%  |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1        | 14.29%  |
| Intel Wireless 3160                                                  | 1        | 14.29%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 14.29%  |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 1        | 14.29%  |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 58.33%  |
| Intel                 | 5        | 41.67%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 46.15%  |
| Intel Ethernet Connection (2) I219-V                              | 2        | 15.38%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 7.69%   |
| Intel I211 Gigabit Network Connection                             | 1        | 7.69%   |
| Intel Ethernet Controller I225-V                                  | 1        | 7.69%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 7.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 63.16%  |
| WiFi     | 7        | 36.84%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 76.92%  |
| WiFi     | 3        | 23.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 58.33%  |
| 2     | 4        | 33.33%  |
| 3     | 1        | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 66.67%  |
| Yes  | 4        | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 50%     |
| Cambridge Silicon Radio | 2        | 33.33%  |
| Realtek Semiconductor   | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 33.33%  |
| Realtek Bluetooth Radio                             | 1        | 16.67%  |
| Intel Bluetooth wireless interface                  | 1        | 16.67%  |
| Intel Bluetooth Device                              | 1        | 16.67%  |
| Intel AX210 Bluetooth                               | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 68.75%  |
| Nvidia | 3        | 18.75%  |
| JMTek  | 1        | 6.25%   |
| AMD    | 1        | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 11.11%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 11.11%  |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 5.56%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 5.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 5.56%   |
| JMTek SADES Audio Device                                                   | 1        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 5.56%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 5.56%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 5.56%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 5.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 5.56%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 5.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 5.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 5.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Micron Technology | 1        | 33.33%  |
| KLEVV             | 1        | 33.33%  |
| Crucial           | 1        | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s    | 1        | 33.33%  |
| KLEVV RAM KD48GU880-32A160X 8GB DIMM DDR4 2666MT/s     | 1        | 33.33%  |
| Crucial RAM CT16G4DFRA32A.C8FE 16GB DIMM DDR4 3200MT/s | 1        | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 2        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 2        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 1        | 50%     |
| 8192  | 1        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 1        | 50%     |
| 2666  | 1        | 50%     |

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
| Sony Ericsson Mobile Communications AB | 1        | 50%     |
| Microdia                               | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sony Ericsson Mobile AB XQ-CC54 | 1        | 50%     |
| Microdia Sonix USB 2.0 Camera   | 1        | 50%     |

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
| 0     | 10       | 83.33%  |
| 1     | 2        | 16.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 50%     |
| Camera       | 1        | 50%     |

