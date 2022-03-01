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

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
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
| 5.14.0-4mx-amd64          | 2        | 18.18%  |
| 5.14.0-3mx-amd64          | 2        | 18.18%  |
| 5.10.0-11-amd64           | 2        | 18.18%  |
| 5.16.0-rc5-hwmon-next+    | 1        | 9.09%   |
| 5.15.0-2-amd64            | 1        | 9.09%   |
| 5.15.0-0.bpo.2-amd64      | 1        | 9.09%   |
| 5.14.0-2mx-amd64          | 1        | 9.09%   |
| 5.10.52-antix.1-amd64-smp | 1        | 9.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 5        | 45.45%  |
| 5.15.0  | 2        | 18.18%  |
| 5.10.0  | 2        | 18.18%  |
| 5.16.0  | 1        | 9.09%   |
| 5.10.52 | 1        | 9.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 5        | 45.45%  |
| 5.10    | 3        | 27.27%  |
| 5.15    | 2        | 18.18%  |
| 5.16    | 1        | 9.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 11       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| XFCE | 8        | 72.73%  |
| KDE5 | 3        | 27.27%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 11       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 8        | 72.73%  |
| SDDM    | 3        | 27.27%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 5        | 45.45%  |
| de_DE | 2        | 18.18%  |
| de_CH | 2        | 18.18%  |
| fr_FR | 1        | 9.09%   |
| en_GB | 1        | 9.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 7        | 63.64%  |
| BIOS | 4        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 9        | 81.82%  |
| Overlay | 1        | 9.09%   |
| Btrfs   | 1        | 9.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 10       | 90.91%  |
| MBR  | 1        | 9.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 54.55%  |
| No        | 5        | 45.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 54.55%  |
| No        | 5        | 45.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 2        | 18.18%  |
| ASUSTek Computer    | 2        | 18.18%  |
| MSI                 | 1        | 9.09%   |
| Lenovo              | 1        | 9.09%   |
| Huanan              | 1        | 9.09%   |
| Hewlett-Packard     | 1        | 9.09%   |
| GALAX               | 1        | 9.09%   |
| Fujitsu             | 1        | 9.09%   |
| ASRock              | 1        | 9.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| MSI MS-7917                | 1        | 9.09%   |
| Lenovo 10AAS1QB0B          | 1        | 9.09%   |
| Huanan X99-F8              | 1        | 9.09%   |
| HP Z400 Workstation        | 1        | 9.09%   |
| Gigabyte X570 AORUS PRO    | 1        | 9.09%   |
| Gigabyte B550M DS3H        | 1        | 9.09%   |
| GALAX B550M                | 1        | 9.09%   |
| Fujitsu ESPRIMO P720       | 1        | 9.09%   |
| ASUS ROG Maximus XIII HERO | 1        | 9.09%   |
| ASUS All Series            | 1        | 9.09%   |
| ASRock X570 Steel Legend   | 1        | 9.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| MSI MS-7917       | 1        | 9.09%   |
| Lenovo 10AAS1QB0B | 1        | 9.09%   |
| Huanan X99-F8     | 1        | 9.09%   |
| HP Z400           | 1        | 9.09%   |
| Gigabyte X570     | 1        | 9.09%   |
| Gigabyte B550M    | 1        | 9.09%   |
| GALAX B550M       | 1        | 9.09%   |
| Fujitsu ESPRIMO   | 1        | 9.09%   |
| ASUS ROG          | 1        | 9.09%   |
| ASUS All          | 1        | 9.09%   |
| ASRock X570       | 1        | 9.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 27.27%  |
| 2019 | 2        | 18.18%  |
| 2014 | 2        | 18.18%  |
| 2021 | 1        | 9.09%   |
| 2018 | 1        | 9.09%   |
| 2013 | 1        | 9.09%   |
| 2010 | 1        | 9.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 11       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 5        | 45.45%  |
| 8.01-16.0   | 2        | 18.18%  |
| 4.01-8.0    | 1        | 9.09%   |
| 3.01-4.0    | 1        | 9.09%   |
| 64.01-256.0 | 1        | 9.09%   |
| 16.01-24.0  | 1        | 9.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 4        | 36.36%  |
| 3.01-4.0   | 2        | 18.18%  |
| 2.01-3.0   | 2        | 18.18%  |
| 4.01-8.0   | 1        | 9.09%   |
| 16.01-24.0 | 1        | 9.09%   |
| 8.01-16.0  | 1        | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 4        | 36.36%  |
| 3      | 3        | 27.27%  |
| 1      | 2        | 18.18%  |
| 8      | 1        | 9.09%   |
| 5      | 1        | 9.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 72.73%  |
| Yes       | 3        | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 63.64%  |
| Yes       | 4        | 36.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 90.91%  |
| Yes       | 1        | 9.09%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 4        | 36.36%  |
| Switzerland | 2        | 18.18%  |
| Germany     | 2        | 18.18%  |
| UK          | 1        | 9.09%   |
| India       | 1        | 9.09%   |
| France      | 1        | 9.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Desktops | Percent |
|-----------|----------|---------|
| Lausen    | 2        | 18.18%  |
| San Diego | 1        | 9.09%   |
| Rosporden | 1        | 9.09%   |
| Normal    | 1        | 9.09%   |
| Munster   | 1        | 9.09%   |
| Milwaukee | 1        | 9.09%   |
| London    | 1        | 9.09%   |
| Houston   | 1        | 9.09%   |
| Freital   | 1        | 9.09%   |
| Bengaluru | 1        | 9.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 9      | 25%     |
| Samsung Electronics | 6        | 10     | 25%     |
| Kingston            | 3        | 3      | 12.5%   |
| Crucial             | 2        | 2      | 8.33%   |
| Corsair             | 2        | 2      | 8.33%   |
| Transcend           | 1        | 1      | 4.17%   |
| Seagate             | 1        | 1      | 4.17%   |
| PNY                 | 1        | 2      | 4.17%   |
| OCZ                 | 1        | 1      | 4.17%   |
| GOODRAM             | 1        | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 3        | 9.68%   |
| Corsair MP400 2TB                | 2        | 6.45%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 3.23%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 3.23%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 1        | 3.23%   |
| WDC WD60EFRX-68L0BN1 6TB         | 1        | 3.23%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 3.23%   |
| WDC WD30EFRX-68AX9N0 3TB         | 1        | 3.23%   |
| WDC WD10EZEX-08M2NA0 1TB         | 1        | 3.23%   |
| WDC WD10EVDS-63U8B1 1TB          | 1        | 3.23%   |
| Transcend TS128GSSD370S 128GB    | 1        | 3.23%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 3.23%   |
| Samsung SSD 980 PRO 1TB          | 1        | 3.23%   |
| Samsung SSD 970 PRO 512GB        | 1        | 3.23%   |
| Samsung SSD 870 EVO 500GB        | 1        | 3.23%   |
| Samsung SSD 850 EVO 500GB        | 1        | 3.23%   |
| Samsung SSD 840 Series 120GB     | 1        | 3.23%   |
| Samsung SSD 840 EVO 250GB        | 1        | 3.23%   |
| Samsung MZVPW256HEGL-00000 256GB | 1        | 3.23%   |
| Samsung MZVLW256HEHP-000L2 256GB | 1        | 3.23%   |
| Samsung HD501LJ 500GB            | 1        | 3.23%   |
| Samsung HD204UI 2TB              | 1        | 3.23%   |
| PNY CS3030 1TB SSD               | 1        | 3.23%   |
| PNY CS2130 2TB SSD               | 1        | 3.23%   |
| OCZ VERTEX3 120GB SSD            | 1        | 3.23%   |
| GOODRAM SSDPR-CL100-480-G3 480GB | 1        | 3.23%   |
| Crucial CT500P2SSD8 500GB        | 1        | 3.23%   |
| Crucial CT120BX500SSD1 120GB     | 1        | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 57.14%  |
| Samsung Electronics | 2        | 2      | 28.57%  |
| Seagate             | 1        | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 33.33%  |
| Kingston            | 3        | 3      | 25%     |
| WDC                 | 1        | 1      | 8.33%   |
| Transcend           | 1        | 1      | 8.33%   |
| OCZ                 | 1        | 1      | 8.33%   |
| GOODRAM             | 1        | 1      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 9        | 12     | 39.13%  |
| NVMe | 8        | 10     | 34.78%  |
| HDD  | 6        | 10     | 26.09%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 22     | 57.89%  |
| NVMe | 8        | 10     | 42.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 13     | 56.25%  |
| 0.51-1.0   | 3        | 3      | 18.75%  |
| 3.01-4.0   | 1        | 1      | 6.25%   |
| 2.01-3.0   | 1        | 1      | 6.25%   |
| 1.01-2.0   | 1        | 1      | 6.25%   |
| 4.01-10.0  | 1        | 3      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 36.36%  |
| 1001-2000      | 3        | 27.27%  |
| More than 3000 | 2        | 18.18%  |
| 2001-3000      | 1        | 9.09%   |
| 501-1000       | 1        | 9.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 3        | 27.27%  |
| 51-100         | 3        | 27.27%  |
| 101-250        | 2        | 18.18%  |
| 1001-2000      | 2        | 18.18%  |
| More than 3000 | 1        | 9.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 20%     |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 20%     |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 20%     |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 20%     |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |
| Seagate             | 1        | 1      | 20%     |
| GOODRAM             | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 4        | 4      | 80%     |
| HDD  | 1        | 1      | 20%     |

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
| Works   | 9        | 27     | 64.29%  |
| Malfunc | 5        | 5      | 35.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 7        | 35%     |
| AMD                       | 4        | 20%     |
| Samsung Electronics       | 3        | 15%     |
| Phison Electronics        | 3        | 15%     |
| Sandisk                   | 1        | 5%      |
| Micron/Crucial Technology | 1        | 5%      |
| ASMedia Technology        | 1        | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Phison E12 NVMe Controller                                                     | 3        | 13.04%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2        | 8.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 8.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2        | 8.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 8.7%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 2        | 8.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 8.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1        | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 4.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 4.35%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 4.35%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 4.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 4.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 4.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 4.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 10       | 52.63%  |
| NVMe | 8        | 42.11%  |
| RAID | 1        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 63.64%  |
| AMD    | 4        | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Intel Xeon CPU W3565 @ 3.20GHz      | 1        | 9.09%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz | 1        | 9.09%   |
| Intel Core i9-10850K CPU @ 3.60GHz  | 1        | 9.09%   |
| Intel Core i7-5820K CPU @ 3.30GHz   | 1        | 9.09%   |
| Intel Core i5-4690K CPU @ 3.50GHz   | 1        | 9.09%   |
| Intel Core i5-4570T CPU @ 2.90GHz   | 1        | 9.09%   |
| Intel Core i3-4130 CPU @ 3.40GHz    | 1        | 9.09%   |
| AMD Ryzen 7 5800X 8-Core Processor  | 1        | 9.09%   |
| AMD Ryzen 5 5600X 6-Core Processor  | 1        | 9.09%   |
| AMD Ryzen 5 1600 Six-Core Processor | 1        | 9.09%   |
| AMD Ryzen 3 3100 4-Core Processor   | 1        | 9.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Xeon    | 2        | 18.18%  |
| Intel Core i5 | 2        | 18.18%  |
| AMD Ryzen 5   | 2        | 18.18%  |
| Intel Core i9 | 1        | 9.09%   |
| Intel Core i7 | 1        | 9.09%   |
| Intel Core i3 | 1        | 9.09%   |
| AMD Ryzen 7   | 1        | 9.09%   |
| AMD Ryzen 3   | 1        | 9.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 3        | 27.27%  |
| 4      | 3        | 27.27%  |
| 2      | 2        | 18.18%  |
| 12     | 1        | 9.09%   |
| 10     | 1        | 9.09%   |
| 8      | 1        | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 81.82%  |
| 1      | 2        | 18.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 11       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 36.36%  |
| 0xa0655    | 1        | 9.09%   |
| 0x306f2    | 1        | 9.09%   |
| 0x306c3    | 1        | 9.09%   |
| 0x0a201016 | 1        | 9.09%   |
| 0x0a201009 | 1        | 9.09%   |
| 0x08701021 | 1        | 9.09%   |
| 0x0800820d | 1        | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Haswell   | 5        | 45.45%  |
| Zen 3     | 2        | 18.18%  |
| Zen+      | 1        | 9.09%   |
| Zen 2     | 1        | 9.09%   |
| Nehalem   | 1        | 9.09%   |
| CometLake | 1        | 9.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 5        | 38.46%  |
| AMD    | 5        | 38.46%  |
| Intel  | 3        | 23.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 15.38%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                | 2        | 15.38%  |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 7.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 7.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 7.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 7.69%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1        | 7.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 7.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 7.69%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 7.69%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                    | 1        | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 5        | 45.45%  |
| 1 x AMD     | 4        | 36.36%  |
| Intel + AMD | 1        | 9.09%   |
| 1 x Intel   | 1        | 9.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 6        | 54.55%  |
| Proprietary | 5        | 45.45%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 3        | 27.27%  |
| 3.01-4.0   | 3        | 27.27%  |
| 8.01-16.0  | 2        | 18.18%  |
| Unknown    | 2        | 18.18%  |
| 0.51-1.0   | 1        | 9.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Medion               | 2        | 14.29%  |
| Dell                 | 2        | 14.29%  |
| Vizio                | 1        | 7.14%   |
| Samsung Electronics  | 1        | 7.14%   |
| Philips              | 1        | 7.14%   |
| NEC Computers        | 1        | 7.14%   |
| Iiyama               | 1        | 7.14%   |
| Grundig              | 1        | 7.14%   |
| Gigabyte Technology  | 1        | 7.14%   |
| Fujitsu Siemens      | 1        | 7.14%   |
| Ancor Communications | 1        | 7.14%   |
| Acer                 | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch              | 2        | 14.29%  |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                | 1        | 7.14%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch | 1        | 7.14%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch          | 1        | 7.14%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch       | 1        | 7.14%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch             | 1        | 7.14%   |
| Grundig UHD GRU4448 3840x2160 1210x680mm 54.6-inch                | 1        | 7.14%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch  | 1        | 7.14%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch  | 1        | 7.14%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                | 1        | 7.14%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                | 1        | 7.14%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch  | 1        | 7.14%   |
| Acer AL1717 ACRAD54 1280x1024 338x270mm 17.0-inch                 | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 4        | 30.77%  |
| 2560x1440 (QHD)    | 3        | 23.08%  |
| 3440x1440          | 2        | 15.38%  |
| 3840x2160 (4K)     | 1        | 7.69%   |
| 1920x1200 (WUXGA)  | 1        | 7.69%   |
| 1680x1050 (WSXGA+) | 1        | 7.69%   |
| 1280x1024 (SXGA)   | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 31     | 3        | 23.08%  |
| 34     | 2        | 15.38%  |
| 27     | 2        | 15.38%  |
| 54     | 1        | 7.69%   |
| 26     | 1        | 7.69%   |
| 24     | 1        | 7.69%   |
| 23     | 1        | 7.69%   |
| 22     | 1        | 7.69%   |
| 17     | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 38.46%  |
| 601-700     | 3        | 23.08%  |
| 701-800     | 2        | 15.38%  |
| 401-500     | 1        | 7.69%   |
| 301-350     | 1        | 7.69%   |
| 1001-1500   | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 61.54%  |
| 21/9  | 2        | 15.38%  |
| 16/10 | 2        | 15.38%  |
| 5/4   | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 5        | 38.46%  |
| 301-350        | 2        | 15.38%  |
| 251-300        | 2        | 15.38%  |
| 201-250        | 2        | 15.38%  |
| More than 1000 | 1        | 7.69%   |
| 141-150        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 81.82%  |
| 101-120 | 2        | 18.18%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 72.73%  |
| 2     | 2        | 18.18%  |
| 3     | 1        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 40%     |
| Realtek Semiconductor | 4        | 26.67%  |
| Broadcom              | 2        | 13.33%  |
| TP-Link               | 1        | 6.67%   |
| Qualcomm Atheros      | 1        | 6.67%   |
| Edimax Technology     | 1        | 6.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 18.75%  |
| Intel I211 Gigabit Network Connection                             | 3        | 18.75%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 6.25%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 6.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 6.25%   |
| Intel Ethernet Controller I225-V                                  | 1        | 6.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 6.25%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 6.25%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 6.25%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 6.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 6.25%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 6.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 1        | 25%     |
| Realtek Semiconductor | 1        | 25%     |
| Edimax Technology     | 1        | 25%     |
| Broadcom              | 1        | 25%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]        | 1        | 25%     |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter | 1        | 25%     |
| Edimax RTL8192S WLAN Adapter                        | 1        | 25%     |
| Broadcom BCM4360 802.11ac Wireless Network Adapter  | 1        | 25%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 54.55%  |
| Realtek Semiconductor | 3        | 27.27%  |
| Qualcomm Atheros      | 1        | 9.09%   |
| Broadcom              | 1        | 9.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 25%     |
| Intel I211 Gigabit Network Connection                             | 3        | 25%     |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 8.33%   |
| Intel Ethernet Controller I225-V                                  | 1        | 8.33%   |
| Intel Ethernet Connection I217-V                                  | 1        | 8.33%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 8.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 8.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 73.33%  |
| WiFi     | 4        | 26.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 66.67%  |
| WiFi     | 4        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 81.82%  |
| 3     | 1        | 9.09%   |
| 2     | 1        | 9.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6        | 54.55%  |
| Yes  | 5        | 45.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| ASUSTek Computer | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 6        | 28.57%  |
| AMD           | 6        | 28.57%  |
| Nvidia        | 4        | 19.05%  |
| ROCCAT        | 2        | 9.52%   |
| Creative Labs | 2        | 9.52%   |
| Razer USA     | 1        | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 3        | 11.11%  |
| AMD Starship/Matisse HD Audio Controller                            | 3        | 11.11%  |
| ROCCAT Khan AIMO                                                    | 2        | 7.41%   |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 7.41%   |
| Intel C610/X99 series chipset HD Audio Controller                   | 2        | 7.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 2        | 7.41%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]       | 2        | 7.41%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]           | 2        | 7.41%   |
| Razer USA Razer Kraken Tournament Edition                           | 1        | 3.7%    |
| Nvidia TU104 HD Audio Controller                                    | 1        | 3.7%    |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 3.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1        | 3.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 3.7%    |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]               | 1        | 3.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 3.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]              | 1        | 3.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 1        | 3.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 4        | 40%     |
| Kingston            | 2        | 20%     |
| G.Skill             | 2        | 20%     |
| SK Hynix            | 1        | 10%     |
| Samsung Electronics | 1        | 10%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 20%     |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 10%     |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s     | 1        | 10%     |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s     | 1        | 10%     |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 10%     |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s    | 1        | 10%     |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s       | 1        | 10%     |
| Corsair RAM CMK32GX4M4A2666C16 8192MB DIMM 2667MT/s      | 1        | 10%     |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 7        | 70%     |
| DDR3 | 3        | 30%     |

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
| 16384 | 3        | 30%     |
| 8192  | 3        | 30%     |
| 4096  | 3        | 30%     |
| 32768 | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2133  | 3        | 30%     |
| 3600  | 2        | 20%     |
| 3400  | 2        | 20%     |
| 1600  | 2        | 20%     |
| 2667  | 1        | 10%     |

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
| 0     | 9        | 81.82%  |
| 1     | 2        | 18.18%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 2        | 100%    |

