Fedora 37 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 22

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek  | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Gigabyte | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek  | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek  | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| HP       | 2B05                        | [c2dcdaa38a](https://linux-hardware.org/?probe=c2dcdaa38a) | Sep 19, 2022 |
| HP       | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Gigabyte | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek  | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| HP       | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Gigabyte | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| ASUSTek  | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| ASUSTek  | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP       | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| MSI      | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Dell     | 08NPPY A00                  | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek  | P8Z68-V LX                  | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HP       | 0B54h D                     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP       | 0B54h D                     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| 5.19.9-300.fc37.x86_64                                 | 8        | 44.44%  |
| 5.19.8-300.fc37.x86_64                                 | 3        | 16.67%  |
| 5.19.8-501.chinfo.fc37.x86_64                          | 1        | 5.56%   |
| 5.19.7-300.fc37.x86_64                                 | 1        | 5.56%   |
| 5.19.10-300.fc37.x86_64                                | 1        | 5.56%   |
| 5.19.0-65.fc37.x86_64                                  | 1        | 5.56%   |
| 5.19.0-0.rc1.20220610git874c8ca1e60b.18.fc37.x86_64    | 1        | 5.56%   |
| 5.18.0-0.rc5.20220505gita7391ad3572431a.43.fc37.x86_64 | 1        | 5.56%   |
| 5.17.0-0.rc6.109.fc37.x86_64                           | 1        | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19.9  | 8        | 44.44%  |
| 5.19.8  | 4        | 22.22%  |
| 5.19.0  | 2        | 11.11%  |
| 5.19.7  | 1        | 5.56%   |
| 5.19.10 | 1        | 5.56%   |
| 5.18.0  | 1        | 5.56%   |
| 5.17.0  | 1        | 5.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 16       | 88.89%  |
| 5.18    | 1        | 5.56%   |
| 5.17    | 1        | 5.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 18       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 12       | 66.67%  |
| KDE5       | 3        | 16.67%  |
| XFCE       | 2        | 11.11%  |
| X-Cinnamon | 1        | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 10       | 55.56%  |
| X11     | 8        | 44.44%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 50%     |
| SDDM    | 3        | 16.67%  |
| LightDM | 3        | 16.67%  |
| GDM     | 3        | 16.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 38.89%  |
| pt_BR | 2        | 11.11%  |
| en_GB | 2        | 11.11%  |
| en_CA | 2        | 11.11%  |
| de_DE | 2        | 11.11%  |
| ru_RU | 1        | 5.56%   |
| nl_NL | 1        | 5.56%   |
| fi_FI | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 14       | 77.78%  |
| BIOS | 4        | 22.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 13       | 72.22%  |
| Ext4  | 3        | 16.67%  |
| Xfs   | 2        | 11.11%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 9        | 50%     |
| Unknown | 9        | 50%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 83.33%  |
| Yes       | 3        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 83.33%  |
| Yes       | 3        | 16.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 50%     |
| Gigabyte Technology | 4        | 22.22%  |
| Hewlett-Packard     | 3        | 16.67%  |
| MSI                 | 1        | 5.56%   |
| Dell                | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS TUF Gaming B550M-PLUS      | 2        | 11.11%  |
| MSI MS-7B47                     | 1        | 5.56%   |
| HP Z600 Workstation             | 1        | 5.56%   |
| HP Compaq Elite 8300 SFF        | 1        | 5.56%   |
| HP 110-516no                    | 1        | 5.56%   |
| Gigabyte X570 I AORUS PRO WIFI  | 1        | 5.56%   |
| Gigabyte X570 AORUS MASTER      | 1        | 5.56%   |
| Gigabyte B85M-D3V-A             | 1        | 5.56%   |
| Gigabyte AB350N-Gaming WIFI     | 1        | 5.56%   |
| Dell OptiPlex 3050              | 1        | 5.56%   |
| ASUS Z170-A                     | 1        | 5.56%   |
| ASUS TUF Gaming X570-PLUS       | 1        | 5.56%   |
| ASUS ProArt Z690-CREATOR WIFI   | 1        | 5.56%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI | 1        | 5.56%   |
| ASUS PRIME Z270-A               | 1        | 5.56%   |
| ASUS PRIME X470-PRO             | 1        | 5.56%   |
| ASUS P8Z68-V LX                 | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS TUF               | 3        | 16.67%  |
| Gigabyte X570          | 2        | 11.11%  |
| ASUS PRIME             | 2        | 11.11%  |
| MSI MS-7B47            | 1        | 5.56%   |
| HP Z600                | 1        | 5.56%   |
| HP Compaq              | 1        | 5.56%   |
| HP 110-516no           | 1        | 5.56%   |
| Gigabyte B85M-D3V-A    | 1        | 5.56%   |
| Gigabyte AB350N-Gaming | 1        | 5.56%   |
| Dell OptiPlex          | 1        | 5.56%   |
| ASUS Z170-A            | 1        | 5.56%   |
| ASUS ProArt            | 1        | 5.56%   |
| ASUS Pro               | 1        | 5.56%   |
| ASUS P8Z68-V           | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 16.67%  |
| 2017 | 3        | 16.67%  |
| 2019 | 2        | 11.11%  |
| 2015 | 2        | 11.11%  |
| 2022 | 1        | 5.56%   |
| 2021 | 1        | 5.56%   |
| 2018 | 1        | 5.56%   |
| 2016 | 1        | 5.56%   |
| 2014 | 1        | 5.56%   |
| 2012 | 1        | 5.56%   |
| 2011 | 1        | 5.56%   |
| 2010 | 1        | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 18       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 16       | 88.89%  |
| Enabled  | 2        | 11.11%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 5        | 27.78%  |
| 16.01-24.0      | 4        | 22.22%  |
| 4.01-8.0        | 3        | 16.67%  |
| 64.01-256.0     | 3        | 16.67%  |
| More than 256.0 | 1        | 5.56%   |
| 24.01-32.0      | 1        | 5.56%   |
| 8.01-16.0       | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 6        | 33.33%  |
| 8.01-16.0  | 4        | 22.22%  |
| 3.01-4.0   | 3        | 16.67%  |
| 2.01-3.0   | 2        | 11.11%  |
| 1.01-2.0   | 2        | 11.11%  |
| 24.01-32.0 | 1        | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 33.33%  |
| 4      | 5        | 27.78%  |
| 3      | 3        | 16.67%  |
| 1      | 2        | 11.11%  |
| 5      | 1        | 5.56%   |
| 0      | 1        | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 61.11%  |
| Yes       | 7        | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 50%     |
| No        | 9        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 55.56%  |
| No        | 8        | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 4        | 22.22%  |
| Germany      | 3        | 16.67%  |
| Canada       | 2        | 11.11%  |
| Brazil       | 2        | 11.11%  |
| UK           | 1        | 5.56%   |
| Sweden       | 1        | 5.56%   |
| South Africa | 1        | 5.56%   |
| Netherlands  | 1        | 5.56%   |
| Malaysia     | 1        | 5.56%   |
| Finland      | 1        | 5.56%   |
| Belarus      | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Goiânia     | 2        | 11.11%  |
| Berlin       | 2        | 11.11%  |
| Zierikzee    | 1        | 5.56%   |
| Vaxjo        | 1        | 5.56%   |
| Vancouver    | 1        | 5.56%   |
| San Antonio  | 1        | 5.56%   |
| Mt. Pleasant | 1        | 5.56%   |
| Mokena       | 1        | 5.56%   |
| Minsk        | 1        | 5.56%   |
| Kuala Lumpur | 1        | 5.56%   |
| Kingston     | 1        | 5.56%   |
| Houston      | 1        | 5.56%   |
| Helsinki     | 1        | 5.56%   |
| Erfurt       | 1        | 5.56%   |
| Centurion    | 1        | 5.56%   |
| Bristol      | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 17     | 31.25%  |
| Seagate             | 7        | 10     | 21.88%  |
| WDC                 | 6        | 11     | 18.75%  |
| Kingston            | 3        | 3      | 9.38%   |
| Toshiba             | 2        | 2      | 6.25%   |
| A-DATA Technology   | 2        | 2      | 6.25%   |
| SanDisk             | 1        | 1      | 3.13%   |
| Crucial             | 1        | 1      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3        | 7.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2        | 4.88%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1        | 2.44%   |
| WDC WDS500G1B0C-00S6U0 500GB                        | 1        | 2.44%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 1        | 2.44%   |
| WDC WD40PURX-64GVNY0 4TB                            | 1        | 2.44%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1        | 2.44%   |
| WDC WD40EFZX-68AWUN0 4TB                            | 1        | 2.44%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 1        | 2.44%   |
| WDC WD10EZEX-60M2NA0 1TB                            | 1        | 2.44%   |
| WDC WD10EVDS-63U8B1 1TB                             | 1        | 2.44%   |
| WDC WD10EFRX-68FYTN0 1TB                            | 1        | 2.44%   |
| WDC WD My Passport 25F3 512GB                       | 1        | 2.44%   |
| Toshiba THNSN5256GPU7 256GB                         | 1        | 2.44%   |
| Toshiba DT01ACA200 2TB                              | 1        | 2.44%   |
| Seagate ST4000DM000-1F2168 4TB                      | 1        | 2.44%   |
| Seagate ST3500413AS 500GB                           | 1        | 2.44%   |
| Seagate ST31000528AS 1TB                            | 1        | 2.44%   |
| Seagate ST2000DM008-2UB102 2TB                      | 1        | 2.44%   |
| Seagate ST2000DM008-2FR102 2TB                      | 1        | 2.44%   |
| Seagate ST1000DM003-1SB102 1TB                      | 1        | 2.44%   |
| Seagate One Touch HDD 5TB                           | 1        | 2.44%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB          | 1        | 2.44%   |
| SanDisk SDSSDRC032G 32GB                            | 1        | 2.44%   |
| Samsung SSD 970 EVO 250GB                           | 1        | 2.44%   |
| Samsung SSD 870 QVO 2TB                             | 1        | 2.44%   |
| Samsung SSD 860 PRO 512GB                           | 1        | 2.44%   |
| Samsung SSD 860 EVO 1TB                             | 1        | 2.44%   |
| Samsung SSD 850 EVO 1TB                             | 1        | 2.44%   |
| Samsung PM963 2.5" NVMe PCIe SSD 1TB                | 1        | 2.44%   |
| Samsung NVMe SSD Drive 1024GB                       | 1        | 2.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB | 1        | 2.44%   |
| Kingston SNVS2000GB 2TB                             | 1        | 2.44%   |
| Kingston SKC3000D2048G 2TB                          | 1        | 2.44%   |
| Kingston SFYRS1000G 1TB                             | 1        | 2.44%   |
| Crucial CT250MX500SSD1 250GB                        | 1        | 2.44%   |
| A-DATA SX8200PNP 1TB                                | 1        | 2.44%   |
| A-DATA SWORDFISH 1TB                                | 1        | 2.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 9      | 50%     |
| WDC     | 5        | 8      | 41.67%  |
| Toshiba | 1        | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 57.14%  |
| WDC                 | 1        | 1      | 14.29%  |
| SanDisk             | 1        | 1      | 14.29%  |
| Crucial             | 1        | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 13       | 20     | 41.94%  |
| HDD     | 11       | 18     | 35.48%  |
| SSD     | 6        | 8      | 19.35%  |
| Unknown | 1        | 1      | 3.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 25     | 48.28%  |
| NVMe | 13       | 20     | 44.83%  |
| SAS  | 2        | 2      | 6.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 7        | 10     | 36.84%  |
| 1.01-2.0   | 4        | 5      | 21.05%  |
| 0.01-0.5   | 3        | 4      | 15.79%  |
| 3.01-4.0   | 2        | 4      | 10.53%  |
| 4.01-10.0  | 2        | 2      | 10.53%  |
| 2.01-3.0   | 1        | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 6        | 33.33%  |
| More than 3000 | 4        | 22.22%  |
| 2001-3000      | 3        | 16.67%  |
| 501-1000       | 2        | 11.11%  |
| 101-250        | 1        | 5.56%   |
| 1-20           | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 3        | 16.67%  |
| 251-500        | 3        | 16.67%  |
| 1001-2000      | 3        | 16.67%  |
| 21-50          | 2        | 11.11%  |
| 1-20           | 2        | 11.11%  |
| 501-1000       | 2        | 11.11%  |
| 101-250        | 1        | 5.56%   |
| 51-100         | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| WDC WD10EFRX-68FYTN0 1TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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
| Detected | 11       | 27     | 55%     |
| Works    | 8        | 19     | 40%     |
| Malfunc  | 1        | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 9        | 26.47%  |
| Samsung Electronics          | 8        | 23.53%  |
| AMD                          | 8        | 23.53%  |
| Kingston Technology Company  | 3        | 8.82%   |
| Toshiba America Info Systems | 1        | 2.94%   |
| Seagate Technology           | 1        | 2.94%   |
| SanDisk                      | 1        | 2.94%   |
| Realtek Semiconductor        | 1        | 2.94%   |
| ASMedia Technology           | 1        | 2.94%   |
| ADATA Technology             | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 13.51%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 13.51%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 8.11%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 8.11%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 5.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 5.41%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 5.41%   |
| Toshiba America Info Systems NVMe Controller                                   | 1        | 2.7%    |
| Seagate FireCuda 520 SSD                                                       | 1        | 2.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.7%    |
| Realtek Realtek Non-Volatile memory controller                                 | 1        | 2.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.7%    |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 50%     |
| NVMe | 13       | 40.63%  |
| RAID | 3        | 9.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 50%     |
| AMD    | 9        | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Xeon CPU X5675 @ 3.07GHz             | 1        | 5.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 1        | 5.56%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 1        | 5.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 1        | 5.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 1        | 5.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz          | 1        | 5.56%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 1        | 5.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 1        | 5.56%   |
| Intel 12th Gen Core i9-12900K              | 1        | 5.56%   |
| AMD Ryzen Threadripper PRO 3975WX 32-Cores | 1        | 5.56%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 1        | 5.56%   |
| AMD Ryzen 7 5700X 8-Core Processor         | 1        | 5.56%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 1        | 5.56%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 5.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 1        | 5.56%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 1        | 5.56%   |
| AMD Ryzen 5 3600 6-Core Processor          | 1        | 5.56%   |
| AMD A6-5200 APU with Radeon HD Graphics    | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 5        | 27.78%  |
| AMD Ryzen 5            | 4        | 22.22%  |
| AMD Ryzen 7            | 2        | 11.11%  |
| Other                  | 1        | 5.56%   |
| Intel Xeon             | 1        | 5.56%   |
| Intel Core i5          | 1        | 5.56%   |
| Intel Core i3          | 1        | 5.56%   |
| AMD Ryzen Threadripper | 1        | 5.56%   |
| AMD Ryzen 9            | 1        | 5.56%   |
| AMD A6                 | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 33.33%  |
| 6      | 5        | 27.78%  |
| 12     | 2        | 11.11%  |
| 8      | 2        | 11.11%  |
| 32     | 1        | 5.56%   |
| 16     | 1        | 5.56%   |
| 2      | 1        | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 94.44%  |
| 2      | 1        | 5.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 16       | 88.89%  |
| 1      | 2        | 11.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 18       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x906e9    | 2        | 11.11%  |
| 0x0a201016 | 2        | 11.11%  |
| 0x08701021 | 2        | 11.11%  |
| 0x906ea    | 1        | 5.56%   |
| 0x90672    | 1        | 5.56%   |
| 0x506e3    | 1        | 5.56%   |
| 0x306c3    | 1        | 5.56%   |
| 0x306a9    | 1        | 5.56%   |
| 0x206c2    | 1        | 5.56%   |
| 0x206a7    | 1        | 5.56%   |
| 0x0a50000d | 1        | 5.56%   |
| 0x0a20120a | 1        | 5.56%   |
| 0x0830104d | 1        | 5.56%   |
| 0x0800820d | 1        | 5.56%   |
| 0x0700010b | 1        | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 4        | 22.22%  |
| Zen 2            | 3        | 16.67%  |
| KabyLake         | 3        | 16.67%  |
| Zen+             | 1        | 5.56%   |
| Westmere         | 1        | 5.56%   |
| Skylake          | 1        | 5.56%   |
| SandyBridge      | 1        | 5.56%   |
| Jaguar           | 1        | 5.56%   |
| IvyBridge        | 1        | 5.56%   |
| Haswell          | 1        | 5.56%   |
| Alderlake Hybrid | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 9        | 40.91%  |
| AMD               | 8        | 36.36%  |
| Intel             | 4        | 18.18%  |
| ASPEED Technology | 1        | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 1        | 4.55%   |
| Nvidia GT218 [GeForce 210]                                                | 1        | 4.55%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 4.55%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 4.55%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1        | 4.55%   |
| Nvidia GF114 [GeForce GTX 560]                                            | 1        | 4.55%   |
| Nvidia GF106 [GeForce GTS 450]                                            | 1        | 4.55%   |
| Nvidia GA103 [GeForce RTX 3060 Ti]                                        | 1        | 4.55%   |
| Nvidia GA102 [GeForce RTX 3090]                                           | 1        | 4.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 4.55%   |
| Intel HD Graphics 630                                                     | 1        | 4.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 4.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 4.55%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1        | 4.55%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                    | 1        | 4.55%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 1        | 4.55%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                      | 1        | 4.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 1        | 4.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 1        | 4.55%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                   | 1        | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 4.55%   |
| AMD Cezanne                                                               | 1        | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x AMD                 | 8        | 44.44%  |
| 1 x Nvidia              | 6        | 33.33%  |
| Intel + Nvidia          | 2        | 11.11%  |
| 2 x Nvidia + 1 x ASPEED | 1        | 5.56%   |
| 1 x Intel               | 1        | 5.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 66.67%  |
| Proprietary | 6        | 33.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 4        | 22.22%  |
| 0.51-1.0   | 4        | 22.22%  |
| Unknown    | 4        | 22.22%  |
| 3.01-4.0   | 2        | 11.11%  |
| 8.01-16.0  | 2        | 11.11%  |
| 1.01-2.0   | 1        | 5.56%   |
| 0.01-0.5   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 5        | 21.74%  |
| Hewlett-Packard      | 3        | 13.04%  |
| Goldstar             | 2        | 8.7%    |
| Dell                 | 2        | 8.7%    |
| AOC                  | 2        | 8.7%    |
| Ancor Communications | 2        | 8.7%    |
| ViewSonic            | 1        | 4.35%   |
| Unknown              | 1        | 4.35%   |
| Philips              | 1        | 4.35%   |
| NEC Computers        | 1        | 4.35%   |
| KTC                  | 1        | 4.35%   |
| BenQ                 | 1        | 4.35%   |
| ASUSTek Computer     | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ViewSonic XG270QC VSCC438 2560x1440 597x336mm 27.0-inch                | 1        | 3.7%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1        | 3.7%    |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch     | 1        | 3.7%    |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch     | 1        | 3.7%    |
| Samsung Electronics LS27A800U SAM71A4 3840x2160 597x336mm 27.0-inch    | 1        | 3.7%    |
| Samsung Electronics LS27A800U SAM71A2 3840x2160 600x340mm 27.2-inch    | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 1020x570mm 46.0-inch | 1        | 3.7%    |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch      | 1        | 3.7%    |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch              | 1        | 3.7%    |
| NEC Computers EA231WU NEC2E9F 1920x1200 488x297mm 22.5-inch            | 1        | 3.7%    |
| NEC Computers 20WGX2 NEC6699 1680x1050 433x270mm 20.1-inch             | 1        | 3.7%    |
| KTC 42 TV KTC4200 1920x1080 983x576mm 44.9-inch                        | 1        | 3.7%    |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch          | 1        | 3.7%    |
| Hewlett-Packard Z30i HWP3099 2560x1600 641x400mm 29.7-inch             | 1        | 3.7%    |
| Hewlett-Packard 24mh HPN366C 1920x1080 527x296mm 23.8-inch             | 1        | 3.7%    |
| Goldstar M2280A GSM57EC 1920x1080 476x268mm 21.5-inch                  | 1        | 3.7%    |
| Goldstar BK550Y GSM5B42 1920x1080 600x340mm 27.2-inch                  | 1        | 3.7%    |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                     | 1        | 3.7%    |
| Dell AW2518HF DELA101 1920x1080 544x303mm 24.5-inch                    | 1        | 3.7%    |
| Dell AW2518H DELA0F6 1920x1080 544x303mm 24.5-inch                     | 1        | 3.7%    |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                     | 1        | 3.7%    |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch           | 1        | 3.7%    |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 1        | 3.7%    |
| AOC 2251WH AOC2251 1920x1080 480x270mm 21.7-inch                       | 1        | 3.7%    |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch  | 1        | 3.7%    |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch       | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 52.38%  |
| 3840x2160 (4K)     | 2        | 9.52%   |
| 3440x1440          | 2        | 9.52%   |
| 1920x1200 (WUXGA)  | 2        | 9.52%   |
| 2560x1600          | 1        | 4.76%   |
| 2560x1440 (QHD)    | 1        | 4.76%   |
| 2288x1287          | 1        | 4.76%   |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 6        | 25%     |
| 27     | 4        | 16.67%  |
| 34     | 2        | 8.33%   |
| 23     | 2        | 8.33%   |
| 21     | 2        | 8.33%   |
| 142    | 1        | 4.17%   |
| 54     | 1        | 4.17%   |
| 44     | 1        | 4.17%   |
| 32     | 1        | 4.17%   |
| 29     | 1        | 4.17%   |
| 25     | 1        | 4.17%   |
| 22     | 1        | 4.17%   |
| 20     | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 11       | 52.38%  |
| 701-800        | 3        | 14.29%  |
| 401-500        | 3        | 14.29%  |
| More than 2000 | 1        | 4.76%   |
| 601-700        | 1        | 4.76%   |
| 1001-1500      | 1        | 4.76%   |
| 901-1000       | 1        | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 13       | 65%     |
| 16/10 | 4        | 20%     |
| 21/9  | 2        | 10%     |
| 1.00  | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 28.57%  |
| 301-350        | 4        | 19.05%  |
| 351-500        | 3        | 14.29%  |
| 251-300        | 3        | 14.29%  |
| More than 1000 | 2        | 9.52%   |
| 151-200        | 2        | 9.52%   |
| 501-1000       | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 47.62%  |
| 101-120 | 6        | 28.57%  |
| 1-50    | 3        | 14.29%  |
| 161-240 | 1        | 4.76%   |
| 121-160 | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 50%     |
| 2     | 6        | 33.33%  |
| 4     | 1        | 5.56%   |
| 3     | 1        | 5.56%   |
| 0     | 1        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 44.44%  |
| Realtek Semiconductor | 9        | 33.33%  |
| Broadcom              | 2        | 7.41%   |
| TP-Link               | 1        | 3.7%    |
| Qualcomm Atheros      | 1        | 3.7%    |
| NetGear               | 1        | 3.7%    |
| Aquantia              | 1        | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 5        | 16.13%  |
| Intel Wi-Fi 6 AX200                                                 | 4        | 12.9%   |
| Realtek RTL8125 2.5GbE Controller                                   | 3        | 9.68%   |
| Intel I211 Gigabit Network Connection                               | 3        | 9.68%   |
| Intel Ethernet Connection (2) I219-V                                | 3        | 9.68%   |
| TP-Link USB 10/100 LAN                                              | 1        | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1        | 3.23%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]              | 1        | 3.23%   |
| Intel Wireless-AC 9260                                              | 1        | 3.23%   |
| Intel Wireless 3165                                                 | 1        | 3.23%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 3.23%   |
| Intel Ethernet Controller X550                                      | 1        | 3.23%   |
| Intel Ethernet Controller I225-V                                    | 1        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 3.23%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet Multi Function   | 1        | 3.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 1        | 3.23%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 7        | 77.78%  |
| Qualcomm Atheros | 1        | 11.11%  |
| NetGear          | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                    | 4        | 44.44%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter       | 1        | 11.11%  |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231] | 1        | 11.11%  |
| Intel Wireless-AC 9260                                 | 1        | 11.11%  |
| Intel Wireless 3165                                    | 1        | 11.11%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                 | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 40.91%  |
| Intel                 | 9        | 40.91%  |
| Broadcom              | 2        | 9.09%   |
| TP-Link               | 1        | 4.55%   |
| Aquantia              | 1        | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 5        | 22.73%  |
| Realtek RTL8125 2.5GbE Controller                                   | 3        | 13.64%  |
| Intel I211 Gigabit Network Connection                               | 3        | 13.64%  |
| Intel Ethernet Connection (2) I219-V                                | 3        | 13.64%  |
| TP-Link USB 10/100 LAN                                              | 1        | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 4.55%   |
| Intel Ethernet Controller X550                                      | 1        | 4.55%   |
| Intel Ethernet Controller I225-V                                    | 1        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 4.55%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet Multi Function   | 1        | 4.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 1        | 4.55%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 66.67%  |
| WiFi     | 9        | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 75%     |
| WiFi     | 5        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 50%     |
| 3     | 4        | 22.22%  |
| 2     | 4        | 22.22%  |
| 9     | 1        | 5.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 83.33%  |
| Yes  | 3        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 70%     |
| Broadcom              | 2        | 20%     |
| Realtek Semiconductor | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                    | 4        | 40%     |
| Broadcom BCM20702A0 Bluetooth 4.0        | 2        | 20%     |
| Realtek Bluetooth Radio                  | 1        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 10%     |
| Intel Bluetooth wireless interface       | 1        | 10%     |
| Intel Bluetooth Device                   | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 10       | 29.41%  |
| Nvidia              | 9        | 26.47%  |
| Intel               | 9        | 26.47%  |
| Shure               | 1        | 2.94%   |
| Razer USA           | 1        | 2.94%   |
| Logitech            | 1        | 2.94%   |
| C-Media Electronics | 1        | 2.94%   |
| AudioQuest          | 1        | 2.94%   |
| ASUSTek Computer    | 1        | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 14.63%  |
| Intel 200 Series PCH HD Audio                                              | 3        | 7.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 7.32%   |
| Shure MV7                                                                  | 1        | 2.44%   |
| Razer USA Razer Seiren Mini                                                | 1        | 2.44%   |
| Nvidia TU104 HD Audio Controller                                           | 1        | 2.44%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.44%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 2.44%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 2.44%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 2.44%   |
| Nvidia Audio device                                                        | 1        | 2.44%   |
| Logitech G635 Gaming Headset                                               | 1        | 2.44%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.44%   |
| C-Media Electronics Amazonbasics Desktop Mini Mic 2                        | 1        | 2.44%   |
| AudioQuest m9XX                                                            | 1        | 2.44%   |
| ASUSTek Computer USB Audio                                                 | 1        | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.44%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2.44%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 2.44%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 3        | 30%     |
| Kingston            | 2        | 20%     |
| Corsair             | 2        | 20%     |
| Samsung Electronics | 1        | 10%     |
| GOODRAM             | 1        | 10%     |
| Crucial             | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s   | 1        | 10%     |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s | 1        | 10%     |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s | 1        | 10%     |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s  | 1        | 10%     |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s    | 1        | 10%     |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3333MT/s | 1        | 10%     |
| G.Skill RAM F4-3200C14-8GTZR 8GB DIMM DDR4 3200MT/s   | 1        | 10%     |
| Crucial RAM CT51264BA160BJ.M8F 4GB DIMM DDR3 1600MT/s | 1        | 10%     |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s   | 1        | 10%     |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 66.67%  |
| DDR3 | 3        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 9        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 3        | 33.33%  |
| 4096  | 3        | 33.33%  |
| 16384 | 2        | 22.22%  |
| 32768 | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 3        | 33.33%  |
| 3600  | 1        | 11.11%  |
| 3466  | 1        | 11.11%  |
| 3333  | 1        | 11.11%  |
| 1866  | 1        | 11.11%  |
| 1800  | 1        | 11.11%  |
| 1600  | 1        | 11.11%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson Printer | 1        | 100%    |

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
| Logitech            | 3        | 42.86%  |
| Microsoft           | 2        | 28.57%  |
| Samsung Electronics | 1        | 14.29%  |
| Hewlett-Packard     | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)         | 1        | 14.29%  |
| Microsoft LifeCam VX-5000       | 1        | 14.29%  |
| Microsoft LifeCam VX-2000       | 1        | 14.29%  |
| Logitech HD Pro Webcam C920     | 1        | 14.29%  |
| Logitech C922 Pro Stream Webcam | 1        | 14.29%  |
| Logitech BRIO Ultra HD Webcam   | 1        | 14.29%  |
| HP HD-4110 Webcam               | 1        | 14.29%  |

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
| 0     | 15       | 83.33%  |
| 1     | 3        | 16.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Sound         | 1        | 33.33%  |
| Net/wireless  | 1        | 33.33%  |
| Graphics card | 1        | 33.33%  |

