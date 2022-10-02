Ubuntu Budgie 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

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

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Gigabyte | M68MT-S2                 | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Gigabyte | B75M-D3P                 | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte | M68MT-S2                 | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte | X570S AORUS PRO AX       | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel    | DP55WB AAE64798-206      | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek  | A88X-PRO                 | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Intel    | X79M-S                   | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| HP       | 828A                     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar  | A960D+V3                 | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock   | A300M-STX                | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock   | A300M-STX                | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel    | STK1A32SC H95551-301     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte | GA-890GPA-UD3H           | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP       | 212B                     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte | B75M-D3H                 | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte | F2A78M-HD2               | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek  | PRIME B560M-A            | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI      | X370 GAMING PRO CARBON   | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte | B75M-D3H                 | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte | B450 I AORUS PRO WIFI-CF | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP       | 1825                     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Gigabyte | B550 AORUS ELITE AX V2   | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.15.0-46-generic     | 3        | 15.79%  |
| 5.15.0-30-generic     | 3        | 15.79%  |
| 5.15.0-43-generic     | 2        | 10.53%  |
| 5.15.0-33-generic     | 2        | 10.53%  |
| 5.15.0-27-generic     | 2        | 10.53%  |
| 5.15.0-25-generic     | 2        | 10.53%  |
| 5.17.2-051702-generic | 1        | 5.26%   |
| 5.15.0-48-generic     | 1        | 5.26%   |
| 5.15.0-47-generic     | 1        | 5.26%   |
| 5.15.0-41-generic     | 1        | 5.26%   |
| 5.13.0-44-generic     | 1        | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 16       | 88.89%  |
| 5.17.2  | 1        | 5.56%   |
| 5.13.0  | 1        | 5.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 16       | 88.89%  |
| 5.17    | 1        | 5.56%   |
| 5.13    | 1        | 5.56%   |

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


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 18       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 18       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 14       | 77.78%  |
| Unknown | 3        | 16.67%  |
| GDM     | 1        | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 8        | 44.44%  |
| de_DE | 4        | 22.22%  |
| fr_FR | 2        | 11.11%  |
| es_ES | 2        | 11.11%  |
| es_MX | 1        | 5.56%   |
| en_GB | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 63.16%  |
| EFI  | 7        | 36.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 15       | 83.33%  |
| Overlay | 3        | 16.67%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 61.11%  |
| GPT     | 7        | 38.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 72.22%  |
| Yes       | 5        | 27.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 55.56%  |
| Yes       | 8        | 44.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 8        | 44.44%  |
| Hewlett-Packard     | 3        | 16.67%  |
| Intel               | 2        | 11.11%  |
| ASUSTek Computer    | 2        | 11.11%  |
| MSI                 | 1        | 5.56%   |
| Biostar             | 1        | 5.56%   |
| ASRock              | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| MSI MS-7A32                     | 1        | 5.56%   |
| Intel STK1A32SC                 | 1        | 5.56%   |
| Intel DP55WB AAE64798-206       | 1        | 5.56%   |
| HP Z440 Workstation             | 1        | 5.56%   |
| HP EliteDesk 800 G1 DM          | 1        | 5.56%   |
| HP 750-417c                     | 1        | 5.56%   |
| Gigabyte X570S AORUS PRO AX     | 1        | 5.56%   |
| Gigabyte M68MT-S2               | 1        | 5.56%   |
| Gigabyte GA-890GPA-UD3H         | 1        | 5.56%   |
| Gigabyte F2A78M-HD2             | 1        | 5.56%   |
| Gigabyte B75M-D3P               | 1        | 5.56%   |
| Gigabyte B75M-D3H               | 1        | 5.56%   |
| Gigabyte B550 AORUS ELITE AX V2 | 1        | 5.56%   |
| Gigabyte B450 I AORUS PRO WIFI  | 1        | 5.56%   |
| Biostar A960D+V3                | 1        | 5.56%   |
| ASUS PRIME B560M-A              | 1        | 5.56%   |
| ASUS A88X-PRO                   | 1        | 5.56%   |
| ASRock A300M-STX                | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7A32             | 1        | 5.56%   |
| Intel STK1A32SC         | 1        | 5.56%   |
| Intel DP55WB            | 1        | 5.56%   |
| HP Z440                 | 1        | 5.56%   |
| HP EliteDesk            | 1        | 5.56%   |
| HP 750-417c             | 1        | 5.56%   |
| Gigabyte X570S          | 1        | 5.56%   |
| Gigabyte M68MT-S2       | 1        | 5.56%   |
| Gigabyte GA-890GPA-UD3H | 1        | 5.56%   |
| Gigabyte F2A78M-HD2     | 1        | 5.56%   |
| Gigabyte B75M-D3P       | 1        | 5.56%   |
| Gigabyte B75M-D3H       | 1        | 5.56%   |
| Gigabyte B550           | 1        | 5.56%   |
| Gigabyte B450           | 1        | 5.56%   |
| Biostar A960D+V3        | 1        | 5.56%   |
| ASUS PRIME              | 1        | 5.56%   |
| ASUS A88X-PRO           | 1        | 5.56%   |
| ASRock A300M-STX        | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 16.67%  |
| 2021 | 2        | 11.11%  |
| 2016 | 2        | 11.11%  |
| 2015 | 2        | 11.11%  |
| 2014 | 2        | 11.11%  |
| 2010 | 2        | 11.11%  |
| 2020 | 1        | 5.56%   |
| 2017 | 1        | 5.56%   |
| 2013 | 1        | 5.56%   |
| 2012 | 1        | 5.56%   |
| 2009 | 1        | 5.56%   |

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
| Disabled | 18       | 100%    |

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


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 7        | 38.89%  |
| 4.01-8.0   | 4        | 22.22%  |
| 8.01-16.0  | 4        | 22.22%  |
| 32.01-64.0 | 2        | 11.11%  |
| 1.01-2.0   | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 9        | 47.37%  |
| 2.01-3.0 | 7        | 36.84%  |
| 4.01-8.0 | 2        | 10.53%  |
| 3.01-4.0 | 1        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 33.33%  |
| 2      | 5        | 27.78%  |
| 4      | 3        | 16.67%  |
| 6      | 2        | 11.11%  |
| 3      | 2        | 11.11%  |

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
| Yes       | 17       | 94.44%  |
| No        | 1        | 5.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 55.56%  |
| No        | 8        | 44.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 66.67%  |
| Yes       | 6        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 27.78%  |
| Germany     | 3        | 16.67%  |
| UK          | 1        | 5.56%   |
| Switzerland | 1        | 5.56%   |
| Spain       | 1        | 5.56%   |
| Slovenia    | 1        | 5.56%   |
| Norway      | 1        | 5.56%   |
| Mexico      | 1        | 5.56%   |
| France      | 1        | 5.56%   |
| Croatia     | 1        | 5.56%   |
| Brazil      | 1        | 5.56%   |
| Argentina   | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milwaukee             | 2        | 11.11%  |
| Walled Lake           | 1        | 5.56%   |
| Trondheim             | 1        | 5.56%   |
| Tocantins             | 1        | 5.56%   |
| San Luis Potosí City | 1        | 5.56%   |
| Rueil-Malmaison       | 1        | 5.56%   |
| Pula                  | 1        | 5.56%   |
| New York              | 1        | 5.56%   |
| Maribor               | 1        | 5.56%   |
| Madrid                | 1        | 5.56%   |
| Kirkcaldy             | 1        | 5.56%   |
| Hamburg               | 1        | 5.56%   |
| Ennepetal             | 1        | 5.56%   |
| Delbrueck             | 1        | 5.56%   |
| Colon                 | 1        | 5.56%   |
| Caslano               | 1        | 5.56%   |
| Bradenton             | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 13     | 21.05%  |
| SanDisk             | 4        | 5      | 10.53%  |
| WDC                 | 3        | 4      | 7.89%   |
| Samsung Electronics | 3        | 5      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| OCZ                 | 2        | 2      | 5.26%   |
| Kingston            | 2        | 3      | 5.26%   |
| Crucial             | 2        | 2      | 5.26%   |
| Unknown             | 1        | 1      | 2.63%   |
| Transcend           | 1        | 1      | 2.63%   |
| SPCC                | 1        | 1      | 2.63%   |
| SK hynix            | 1        | 1      | 2.63%   |
| Phison              | 1        | 1      | 2.63%   |
| Micron Technology   | 1        | 1      | 2.63%   |
| Maxtor              | 1        | 1      | 2.63%   |
| JMicron Technology  | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| ASMT109x            | 1        | 1      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| SanDisk SDSSDA120G 120GB           | 2        | 4.55%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 2.27%   |
| WDC WD40PURZ-85TTDY0 4TB           | 1        | 2.27%   |
| WDC WD10EARS-00Y5B1 1TB            | 1        | 2.27%   |
| WDC WD10EADS-00M2B0 1TB            | 1        | 2.27%   |
| Unknown SD/MMC/MS PRO 2GB          | 1        | 2.27%   |
| Transcend TS128GMTE110S 128GB      | 1        | 2.27%   |
| Toshiba HDWD240 4TB                | 1        | 2.27%   |
| Toshiba HDWD220 2TB                | 1        | 2.27%   |
| SPCC Solid State Disk 256GB        | 1        | 2.27%   |
| SK hynix SC210 2.5 7MM 128GB SSD   | 1        | 2.27%   |
| Seagate ST9500325AS 500GB          | 1        | 2.27%   |
| Seagate ST500LT012-1DG142 500GB    | 1        | 2.27%   |
| Seagate ST380815AS 80GB            | 1        | 2.27%   |
| Seagate ST3500418AS 500GB          | 1        | 2.27%   |
| Seagate ST3500412AS 500GB          | 1        | 2.27%   |
| Seagate ST3160815AS 160GB          | 1        | 2.27%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 2.27%   |
| Seagate ST2000DM001-1ER164 2TB     | 1        | 2.27%   |
| Seagate ST1000LM048-2E7172 1TB     | 1        | 2.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 2.27%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1        | 2.27%   |
| Seagate ST1000DM003-1SB10C 1TB     | 1        | 2.27%   |
| Seagate NVMe SSD Drive 500GB       | 1        | 2.27%   |
| SanDisk NVMe SSD Drive 500GB       | 1        | 2.27%   |
| SanDisk DF4032  32GB               | 1        | 2.27%   |
| Samsung SSD 870 EVO 250GB          | 1        | 2.27%   |
| Samsung MZVLW256HEHP-000H1 256GB   | 1        | 2.27%   |
| Samsung HD250HJ 250GB              | 1        | 2.27%   |
| Phison NVMe SSD Drive 512GB        | 1        | 2.27%   |
| OCZ TRION150 240GB SSD             | 1        | 2.27%   |
| OCZ NVMe SSD Drive 256GB           | 1        | 2.27%   |
| Micron NVMe SSD Drive 500GB        | 1        | 2.27%   |
| Maxtor 6V160E0 160GB               | 1        | 2.27%   |
| Kingston SUV400S37120G 120GB SSD   | 1        | 2.27%   |
| Kingston SA2000M8250G 250GB        | 1        | 2.27%   |
| JMicron Generic 120GB              | 1        | 2.27%   |
| Intel SSDPEKNU512GZ 512GB          | 1        | 2.27%   |
| HGST HUS726T4TALA6L4 4TB           | 1        | 2.27%   |
| Crucial CT240BX500SSD1 240GB       | 1        | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 12     | 44.44%  |
| WDC                 | 3        | 4      | 16.67%  |
| Toshiba             | 2        | 2      | 11.11%  |
| Unknown             | 1        | 1      | 5.56%   |
| Samsung Electronics | 1        | 2      | 5.56%   |
| Maxtor              | 1        | 1      | 5.56%   |
| HGST                | 1        | 1      | 5.56%   |
| ASMT109x            | 1        | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 2        | 2      | 20%     |
| Crucial             | 2        | 2      | 20%     |
| SPCC                | 1        | 1      | 10%     |
| SK hynix            | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 2      | 10%     |
| OCZ                 | 1        | 1      | 10%     |
| Kingston            | 1        | 2      | 10%     |
| A-DATA Technology   | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 24     | 40%     |
| SSD  | 9        | 12     | 30%     |
| NVMe | 8        | 11     | 26.67%  |
| MMC  | 1        | 1      | 3.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 34     | 59.26%  |
| NVMe | 7        | 10     | 25.93%  |
| SAS  | 3        | 3      | 11.11%  |
| MMC  | 1        | 1      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 23     | 57.69%  |
| 0.51-1.0   | 6        | 7      | 23.08%  |
| 3.01-4.0   | 3        | 3      | 11.54%  |
| 1.01-2.0   | 2        | 3      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 38.89%  |
| 251-500        | 3        | 16.67%  |
| 1-20           | 2        | 11.11%  |
| 51-100         | 2        | 11.11%  |
| More than 3000 | 1        | 5.56%   |
| 21-50          | 1        | 5.56%   |
| 1001-2000      | 1        | 5.56%   |
| 501-1000       | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 6        | 33.33%  |
| 1-20      | 6        | 33.33%  |
| 101-250   | 2        | 11.11%  |
| 51-100    | 2        | 11.11%  |
| 251-500   | 1        | 5.56%   |
| 2001-3000 | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

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
| Detected | 14       | 33     | 63.64%  |
| Works    | 6        | 13     | 27.27%  |
| Malfunc  | 2        | 2      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 9        | 32.14%  |
| Intel                       | 8        | 28.57%  |
| Transcend                   | 1        | 3.57%   |
| Seagate Technology          | 1        | 3.57%   |
| SanDisk                     | 1        | 3.57%   |
| Samsung Electronics         | 1        | 3.57%   |
| Phison Electronics          | 1        | 3.57%   |
| OCZ Technology Group        | 1        | 3.57%   |
| Nvidia                      | 1        | 3.57%   |
| Micron Technology           | 1        | 3.57%   |
| Marvell Technology Group    | 1        | 3.57%   |
| Kingston Technology Company | 1        | 3.57%   |
| JMicron Technology          | 1        | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 14.29%  |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 5.71%   |
| Transcend Non-Volatile memory controller                                       | 1        | 2.86%   |
| Seagate Non-Volatile memory controller                                         | 1        | 2.86%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1        | 2.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 2.86%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 2.86%   |
| OCZ Group RD400/400A SSD                                                       | 1        | 2.86%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.86%   |
| Micron Non-Volatile memory controller                                          | 1        | 2.86%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 2.86%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 2.86%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.86%   |
| Intel Non-Volatile memory controller                                           | 1        | 2.86%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1        | 2.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]    | 1        | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]    | 1        | 2.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 2.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 2.86%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 2.86%   |
| AMD FCH IDE Controller                                                         | 1        | 2.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 48.15%  |
| NVMe | 7        | 25.93%  |
| IDE  | 6        | 22.22%  |
| RAID | 1        | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 10       | 55.56%  |
| Intel  | 8        | 44.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz             | 1        | 5.56%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 5.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 5.56%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 5.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 5.56%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 1        | 5.56%   |
| Intel Atom x5-Z8330 CPU @ 1.44GHz               | 1        | 5.56%   |
| Intel 11th Gen Core i5-11600 @ 2.80GHz          | 1        | 5.56%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 5.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 5.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1        | 5.56%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 5.56%   |
| AMD Phenom II X4 965 Processor                  | 1        | 5.56%   |
| AMD FX-8150 Eight-Core Processor                | 1        | 5.56%   |
| AMD Athlon II X3 445 Processor                  | 1        | 5.56%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 1        | 5.56%   |
| AMD A4-4000 APU with Radeon HD Graphics         | 1        | 5.56%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 3        | 16.67%  |
| AMD Ryzen 5      | 3        | 16.67%  |
| Other            | 1        | 5.56%   |
| Intel Xeon       | 1        | 5.56%   |
| Intel Core i7    | 1        | 5.56%   |
| Intel Core i3    | 1        | 5.56%   |
| Intel Atom       | 1        | 5.56%   |
| AMD Ryzen 9      | 1        | 5.56%   |
| AMD Phenom II X4 | 1        | 5.56%   |
| AMD FX           | 1        | 5.56%   |
| AMD Athlon II X3 | 1        | 5.56%   |
| AMD Athlon       | 1        | 5.56%   |
| AMD A4           | 1        | 5.56%   |
| AMD A10          | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 50%     |
| 6      | 3        | 16.67%  |
| 2      | 3        | 16.67%  |
| 12     | 1        | 5.56%   |
| 3      | 1        | 5.56%   |
| 1      | 1        | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 66.67%  |
| 1      | 6        | 33.33%  |

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
| Unknown    | 11       | 57.89%  |
| 0x306a9    | 2        | 10.53%  |
| 0xa0671    | 1        | 5.26%   |
| 0x406f1    | 1        | 5.26%   |
| 0x406c4    | 1        | 5.26%   |
| 0x0a50000c | 1        | 5.26%   |
| 0x08108102 | 1        | 5.26%   |
| 0x06001119 | 1        | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen+        | 3        | 16.67%  |
| Zen 3       | 2        | 11.11%  |
| K10         | 2        | 11.11%  |
| IvyBridge   | 2        | 11.11%  |
| Steamroller | 1        | 5.56%   |
| Skylake     | 1        | 5.56%   |
| Silvermont  | 1        | 5.56%   |
| Piledriver  | 1        | 5.56%   |
| Nehalem     | 1        | 5.56%   |
| Icelake     | 1        | 5.56%   |
| Haswell     | 1        | 5.56%   |
| Bulldozer   | 1        | 5.56%   |
| Broadwell   | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 9        | 47.37%  |
| Nvidia | 5        | 26.32%  |
| Intel  | 5        | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2        | 10.53%  |
| Nvidia GP104GL [Quadro P4000]                                                            | 1        | 5.26%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 5.26%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 5.26%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 1        | 5.26%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 5.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 5.26%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 5.26%   |
| Intel HD Graphics 530                                                                    | 1        | 5.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 5.26%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 5.26%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 5.26%   |
| AMD Juniper PRO [Radeon HD 5750]                                                         | 1        | 5.26%   |
| AMD Cypress XT [Radeon HD 5870]                                                          | 1        | 5.26%   |
| AMD Cezanne                                                                              | 1        | 5.26%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 5.26%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x AMD    | 9        | 50%     |
| 1 x Nvidia | 5        | 27.78%  |
| 1 x Intel  | 4        | 22.22%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 77.78%  |
| Proprietary | 3        | 16.67%  |
| Unknown     | 1        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 61.11%  |
| 7.01-8.0   | 2        | 11.11%  |
| 1.01-2.0   | 2        | 11.11%  |
| 3.01-4.0   | 1        | 5.56%   |
| 0.51-1.0   | 1        | 5.56%   |
| 0.01-0.5   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 36.84%  |
| Hewlett-Packard     | 3        | 15.79%  |
| SANYO               | 2        | 10.53%  |
| Philips             | 2        | 10.53%  |
| Unknown (XXX)       | 1        | 5.26%   |
| Fujitsu Siemens     | 1        | 5.26%   |
| Dell                | 1        | 5.26%   |
| BenQ                | 1        | 5.26%   |
| AOC                 | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1        | 5%      |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch               | 1        | 5%      |
| SANYO LCD SAN0A12 1920x540                                           | 1        | 5%      |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch | 1        | 5%      |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch | 1        | 5%      |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 1        | 5%      |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch    | 1        | 5%      |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 1        | 5%      |
| Samsung Electronics LF22T35 SAM707B 1920x1080 480x270mm 21.7-inch    | 1        | 5%      |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 1        | 5%      |
| Philips PHL 241B7Q PHL0909 1920x1080 530x300mm 24.0-inch             | 1        | 5%      |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch              | 1        | 5%      |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                  | 1        | 5%      |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 1        | 5%      |
| Hewlett-Packard E232 HWP327A 1920x1080 509x286mm 23.0-inch           | 1        | 5%      |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch            | 1        | 5%      |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch         | 1        | 5%      |
| Dell LCD Monitor 1704FPV 1280x1024                                   | 1        | 5%      |
| BenQ GW2750H BNQ78C3 1920x1080 598x336mm 27.0-inch                   | 1        | 5%      |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 57.89%  |
| 1920x540           | 2        | 10.53%  |
| 1920x1200 (WUXGA)  | 2        | 10.53%  |
| 2560x1440 (QHD)    | 1        | 5.26%   |
| 1680x1050 (WSXGA+) | 1        | 5.26%   |
| 1366x768 (WXGA)    | 1        | 5.26%   |
| 1280x1024 (SXGA)   | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 30%     |
| 27      | 4        | 20%     |
| 23      | 3        | 15%     |
| 21      | 2        | 10%     |
| Unknown | 2        | 10%     |
| 54      | 1        | 5%      |
| 33      | 1        | 5%      |
| 18      | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 63.16%  |
| 401-500     | 3        | 15.79%  |
| Unknown     | 2        | 10.53%  |
| 701-800     | 1        | 5.26%   |
| 1001-1500   | 1        | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 72.22%  |
| 16/10   | 3        | 16.67%  |
| 32/9    | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 38.89%  |
| 301-350        | 4        | 22.22%  |
| 251-300        | 2        | 11.11%  |
| Unknown        | 2        | 11.11%  |
| More than 1000 | 1        | 5.56%   |
| 351-500        | 1        | 5.56%   |
| 141-150        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 77.78%  |
| Unknown | 2        | 11.11%  |
| 1-50    | 1        | 5.56%   |
| 101-120 | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 88.89%  |
| 2     | 2        | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 45.83%  |
| Realtek Semiconductor | 10       | 41.67%  |
| Nvidia                | 1        | 4.17%   |
| MediaTek              | 1        | 4.17%   |
| Broadcom              | 1        | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 28.57%  |
| Intel I211 Gigabit Network Connection                             | 2        | 7.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 7.14%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.57%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 3.57%   |
| Intel Wireless-AC 9260                                            | 1        | 3.57%   |
| Intel Wireless 7265                                               | 1        | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 3.57%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.57%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 3.57%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.57%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 3.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 3.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 60%     |
| Realtek Semiconductor | 2        | 20%     |
| MediaTek              | 1        | 10%     |
| Broadcom              | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]    | 2        | 20%     |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter | 1        | 10%     |
| Realtek RTL8188CUS 802.11n WLAN Adapter             | 1        | 10%     |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz             | 1        | 10%     |
| Intel Wireless-AC 9260                              | 1        | 10%     |
| Intel Wireless 7265                                 | 1        | 10%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz              | 1        | 10%     |
| Intel Wi-Fi 6 AX200                                 | 1        | 10%     |
| Broadcom BCM4360 802.11ac Wireless Network Adapter  | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 52.94%  |
| Intel                 | 7        | 41.18%  |
| Nvidia                | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8        | 44.44%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5.56%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 1        | 5.56%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 5.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 5.56%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 5.56%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 62.96%  |
| WiFi     | 10       | 37.04%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 72.22%  |
| WiFi     | 5        | 27.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 55.56%  |
| 2     | 8        | 44.44%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 88.89%  |
| Yes  | 2        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 5        | 83.33%  |
| MediaTek | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| MediaTek Wireless_Device                 | 1        | 16.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 16.67%  |
| Intel Wireless-AC 3168 Bluetooth         | 1        | 16.67%  |
| Intel Bluetooth wireless interface       | 1        | 16.67%  |
| Intel AX210 Bluetooth                    | 1        | 16.67%  |
| Intel AX200 Bluetooth                    | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AMD                   | 11       | 45.83%  |
| Intel                 | 7        | 29.17%  |
| Nvidia                | 5        | 20.83%  |
| Realtek Semiconductor | 1        | 4.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                | 3        | 9.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller   | 2        | 6.25%   |
| AMD SBx00 Azalia (Intel HDA)                                          | 2        | 6.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                   | 2        | 6.25%   |
| AMD FCH Azalia Controller                                             | 2        | 6.25%   |
| Realtek Semiconductor USB Audio                                       | 1        | 3.13%   |
| Nvidia MCP61 High Definition Audio                                    | 1        | 3.13%   |
| Nvidia GP104 High Definition Audio Controller                         | 1        | 3.13%   |
| Nvidia GK106 HDMI Audio Controller                                    | 1        | 3.13%   |
| Nvidia GF110 High Definition Audio Controller                         | 1        | 3.13%   |
| Nvidia GA106 High Definition Audio Controller                         | 1        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller      | 1        | 3.13%   |
| Intel Tiger Lake-H HD Audio Controller                                | 1        | 3.13%   |
| Intel C610/X99 series chipset HD Audio Controller                     | 1        | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller   | 1        | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio              | 1        | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller       | 1        | 3.13%   |
| AMD Trinity HDMI Audio Controller                                     | 1        | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                              | 1        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                    | 1        | 3.13%   |
| AMD Kaveri HDMI/DP Audio Controller                                   | 1        | 3.13%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                        | 1        | 3.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                   | 1        | 3.13%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand] | 1        | 3.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                | 1        | 3.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]          | 1        | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 3        | 37.5%   |
| SK hynix            | 2        | 25%     |
| Samsung Electronics | 1        | 12.5%   |
| Crucial             | 1        | 12.5%   |
| Corsair             | 1        | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 22.22%  |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 11.11%  |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 11.11%  |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 11.11%  |
| Kingston RAM 9905584-032.A 4GB DIMM DDR3 1600MT/s      | 1        | 11.11%  |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s | 1        | 11.11%  |
| Corsair RAM CMV8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s    | 1        | 11.11%  |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 4        | 50%     |
| DDR3  | 3        | 37.5%   |
| SDRAM | 1        | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 6        | 85.71%  |
| SODIMM | 1        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 3        | 37.5%   |
| 16384 | 2        | 25%     |
| 4096  | 2        | 25%     |
| 2048  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 37.5%   |
| 3200  | 2        | 25%     |
| 2667  | 1        | 12.5%   |
| 2400  | 1        | 12.5%   |
| 1333  | 1        | 12.5%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Logitech            | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)     | 1        | 50%     |
| Logitech HD Pro Webcam C920 | 1        | 50%     |

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
| 1     | 2        | 11.11%  |
| 4     | 1        | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 20%     |
| Sound            | 1        | 20%     |
| Net/wireless     | 1        | 20%     |
| Net/ethernet     | 1        | 20%     |
| Graphics card    | 1        | 20%     |

