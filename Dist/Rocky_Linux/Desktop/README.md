Rocky Linux - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

| Vendor   | Model             | Probe                                                      | Date         |
|----------|-------------------|------------------------------------------------------------|--------------|
| Unknown  | X31_ICH7          | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell     | 0GWHMW A01        | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell     | 06CV2N A00        | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte | G41MT-USB3        | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte | G41MT-USB3        | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR      | Pocono BIOS.5.1   | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
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
| ASUSTek  | PRIME TRX40-PRO S | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
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
| Rocky Linux 8.5 | 11       | 50%     |
| Rocky Linux 8.4 | 9        | 40.91%  |
| Rocky Linux 8.6 | 1        | 4.55%   |
| Rocky Linux 8.3 | 1        | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Rocky Linux | 22       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 4.18.0-348.12.2.el8_5.x86_64 | 6        | 27.27%  |
| 4.18.0-348.7.1.el8_5.x86_64  | 3        | 13.64%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 3        | 13.64%  |
| 4.18.0-305.19.1.el8_4.x86_64 | 2        | 9.09%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 2        | 9.09%   |
| 5.14.1-1.el8.elrepo.x86_64   | 1        | 4.55%   |
| 4.18.0-372.9.1.el8.x86_64    | 1        | 4.55%   |
| 4.18.0-348.20.1.el8_5.x86_64 | 1        | 4.55%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1        | 4.55%   |
| 4.18.0-305.25.1.el8_4.x86_64 | 1        | 4.55%   |
| 4.18.0-240.22.1.el8.x86_64   | 1        | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.0  | 21       | 95.45%  |
| 5.14.1  | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 21       | 95.45%  |
| 5.14    | 1        | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 22       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 12       | 54.55%  |
| Unknown       | 5        | 22.73%  |
| KDE5          | 3        | 13.64%  |
| MATE          | 1        | 4.55%   |
| GNOME Classic | 1        | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 10       | 45.45%  |
| Wayland | 9        | 40.91%  |
| Unknown | 3        | 13.64%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 54.55%  |
| GDM     | 8        | 36.36%  |
| SDDM    | 2        | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 50%     |
| en_IL | 3        | 13.64%  |
| ru_RU | 2        | 9.09%   |
| en_SG | 2        | 9.09%   |
| pl_PL | 1        | 4.55%   |
| ja_JP | 1        | 4.55%   |
| es_CO | 1        | 4.55%   |
| af_ZA | 1        | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 63.64%  |
| EFI  | 8        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 18       | 81.82%  |
| Ext4 | 4        | 18.18%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 9        | 40.91%  |
| Unknown | 8        | 36.36%  |
| MBR     | 5        | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 81.82%  |
| Yes       | 4        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 95.45%  |
| Yes       | 1        | 4.55%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 7        | 31.82%  |
| ASUSTek Computer    | 4        | 18.18%  |
| Gigabyte Technology | 3        | 13.64%  |
| NCR                 | 1        | 4.55%   |
| MSI                 | 1        | 4.55%   |
| Lenovo              | 1        | 4.55%   |
| Hewlett-Packard     | 1        | 4.55%   |
| Google              | 1        | 4.55%   |
| AZW                 | 1        | 4.55%   |
| ASRock              | 1        | 4.55%   |
| Unknown             | 1        | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Dell OptiPlex 9020              | 2        | 9.09%   |
| NCR xxxx-xxxx-xxxx              | 1        | 4.55%   |
| MSI MS-7917                     | 1        | 4.55%   |
| Lenovo ThinkCentre M72e 36601Y8 | 1        | 4.55%   |
| HP Z600 Workstation             | 1        | 4.55%   |
| Google Panther                  | 1        | 4.55%   |
| Gigabyte X570 AORUS ULTRA       | 1        | 4.55%   |
| Gigabyte H87-D3H                | 1        | 4.55%   |
| Gigabyte G41MT-USB3             | 1        | 4.55%   |
| Dell Vostro 3681                | 1        | 4.55%   |
| Dell Precision Tower 7810       | 1        | 4.55%   |
| Dell Precision T7610            | 1        | 4.55%   |
| Dell Precision T5610            | 1        | 4.55%   |
| Dell OptiPlex 390               | 1        | 4.55%   |
| AZW Gemini M                    | 1        | 4.55%   |
| ASUS PRIME TRX40-PRO S          | 1        | 4.55%   |
| ASUS PRIME B450M-A II           | 1        | 4.55%   |
| ASUS PRIME B450-PLUS            | 1        | 4.55%   |
| ASUS P5Q DELUXE                 | 1        | 4.55%   |
| ASRock B450M Pro4               | 1        | 4.55%   |
| Unknown                         | 1        | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell Precision      | 3        | 13.64%  |
| Dell OptiPlex       | 3        | 13.64%  |
| ASUS PRIME          | 3        | 13.64%  |
| NCR xxxx-xxxx-xxxx  | 1        | 4.55%   |
| MSI MS-7917         | 1        | 4.55%   |
| Lenovo ThinkCentre  | 1        | 4.55%   |
| HP Z600             | 1        | 4.55%   |
| Google Panther      | 1        | 4.55%   |
| Gigabyte X570       | 1        | 4.55%   |
| Gigabyte H87-D3H    | 1        | 4.55%   |
| Gigabyte G41MT-USB3 | 1        | 4.55%   |
| Dell Vostro         | 1        | 4.55%   |
| AZW Gemini          | 1        | 4.55%   |
| ASUS P5Q            | 1        | 4.55%   |
| ASRock B450M        | 1        | 4.55%   |
| Unknown             | 1        | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 3        | 13.64%  |
| 2015 | 3        | 13.64%  |
| 2014 | 3        | 13.64%  |
| 2013 | 3        | 13.64%  |
| 2011 | 3        | 13.64%  |
| 2018 | 2        | 9.09%   |
| 2008 | 2        | 9.09%   |
| 2021 | 1        | 4.55%   |
| 2019 | 1        | 4.55%   |
| 2010 | 1        | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 22       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 22       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 95.45%  |
| Yes  | 1        | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 5        | 22.73%  |
| 32.01-64.0  | 5        | 22.73%  |
| 16.01-24.0  | 4        | 18.18%  |
| 3.01-4.0    | 2        | 9.09%   |
| 64.01-256.0 | 2        | 9.09%   |
| 1.01-2.0    | 2        | 9.09%   |
| 2.01-3.0    | 1        | 4.55%   |
| 8.01-16.0   | 1        | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 7        | 31.82%  |
| 3.01-4.0  | 6        | 27.27%  |
| 1.01-2.0  | 4        | 18.18%  |
| 4.01-8.0  | 2        | 9.09%   |
| 8.01-16.0 | 1        | 4.55%   |
| 0.51-1.0  | 1        | 4.55%   |
| 0.01-0.5  | 1        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 45.45%  |
| 2      | 6        | 27.27%  |
| 3      | 3        | 13.64%  |
| 4      | 2        | 9.09%   |
| 8      | 1        | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 59.09%  |
| No        | 9        | 40.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 54.55%  |
| Yes       | 10       | 45.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 68.18%  |
| Yes       | 7        | 31.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 6        | 27.27%  |
| Singapore    | 3        | 13.64%  |
| Israel       | 3        | 13.64%  |
| Russia       | 2        | 9.09%   |
| South Africa | 1        | 4.55%   |
| Portugal     | 1        | 4.55%   |
| Poland       | 1        | 4.55%   |
| Japan        | 1        | 4.55%   |
| India        | 1        | 4.55%   |
| France       | 1        | 4.55%   |
| Czechia      | 1        | 4.55%   |
| Colombia     | 1        | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Singapore              | 3        | 13.64%  |
| Haifa                  | 2        | 9.09%   |
| Waltham                | 1        | 4.55%   |
| St Petersburg          | 1        | 4.55%   |
| Sobral de Monte Agraco | 1        | 4.55%   |
| Rehovot                | 1        | 4.55%   |
| Prague                 | 1        | 4.55%   |
| Paris                  | 1        | 4.55%   |
| Ōtsu                  | 1        | 4.55%   |
| Moscow                 | 1        | 4.55%   |
| Mequon                 | 1        | 4.55%   |
| Lebanon                | 1        | 4.55%   |
| Krakow                 | 1        | 4.55%   |
| Imphal                 | 1        | 4.55%   |
| Fredericksburg         | 1        | 4.55%   |
| Corvallis              | 1        | 4.55%   |
| Centurion              | 1        | 4.55%   |
| Burlington             | 1        | 4.55%   |
| Bucaramanga            | 1        | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 12     | 20.59%  |
| Seagate             | 6        | 12     | 17.65%  |
| Toshiba             | 4        | 4      | 11.76%  |
| Samsung Electronics | 3        | 3      | 8.82%   |
| Hitachi             | 2        | 3      | 5.88%   |
| Crucial             | 2        | 2      | 5.88%   |
| SK hynix            | 1        | 1      | 2.94%   |
| SanDisk             | 1        | 1      | 2.94%   |
| PNY                 | 1        | 1      | 2.94%   |
| Phison              | 1        | 1      | 2.94%   |
| Intel               | 1        | 1      | 2.94%   |
| HGST                | 1        | 1      | 2.94%   |
| Gigabyte Technology | 1        | 1      | 2.94%   |
| Corsair             | 1        | 1      | 2.94%   |
| China               | 1        | 1      | 2.94%   |
| Apacer              | 1        | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 2        | 5.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1        | 2.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 2.7%    |
| WDC WD5000LPCX-24VHAT0 500GB         | 1        | 2.7%    |
| WDC WD5000AAKX-75U6AA0 500GB         | 1        | 2.7%    |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 2.7%    |
| WDC WD30EZRX-00D8PB0 3TB             | 1        | 2.7%    |
| WDC WD2500AAJS-22VTA0 250GB          | 1        | 2.7%    |
| WDC WD20EZRX-00DC0B0 2TB             | 1        | 2.7%    |
| WDC WD1001FALS-00J7B0 1TB            | 1        | 2.7%    |
| Toshiba MG07ACA12TE 12TB             | 1        | 2.7%    |
| Toshiba MG04ACA400E 4TB              | 1        | 2.7%    |
| Toshiba DT01ACA100 1TB               | 1        | 2.7%    |
| Toshiba DT01ACA050 500GB             | 1        | 2.7%    |
| SK hynix SH920 2.5 7MM 256GB SSD     | 1        | 2.7%    |
| Seagate ST4000DM004-2CV104 4TB       | 1        | 2.7%    |
| Seagate ST3160318AS 160GB            | 1        | 2.7%    |
| Seagate ST1000VX005-2EZ102 1TB       | 1        | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 2.7%    |
| SanDisk SSD U110 16GB                | 1        | 2.7%    |
| Samsung SSD 980 PRO 1TB              | 1        | 2.7%    |
| Samsung SSD 860 EVO 1TB              | 1        | 2.7%    |
| Samsung HD103SJ 1TB                  | 1        | 2.7%    |
| PNY CS900 120GB SSD                  | 1        | 2.7%    |
| Phison Sabrent 1TB                   | 1        | 2.7%    |
| Intel SSDPEDMW012T4 1TB              | 1        | 2.7%    |
| Hitachi HTS727575A9E364 752GB        | 1        | 2.7%    |
| Hitachi HDS721010CLA632 1TB          | 1        | 2.7%    |
| Hitachi HDP725050GLA360 500GB        | 1        | 2.7%    |
| HGST HTS721010A9E630 1TB             | 1        | 2.7%    |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD | 1        | 2.7%    |
| Crucial CT240BX500SSD1 240GB         | 1        | 2.7%    |
| Crucial CT1000P2SSD8 1TB             | 1        | 2.7%    |
| Corsair Neutron SSD 64GB             | 1        | 2.7%    |
| China M.2 SSD 256GB                  | 1        | 2.7%    |
| Apacer AS340 240GB SSD               | 1        | 2.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 10     | 30%     |
| Seagate             | 6        | 12     | 30%     |
| Toshiba             | 4        | 4      | 20%     |
| Hitachi             | 2        | 3      | 10%     |
| Samsung Electronics | 1        | 1      | 5%      |
| HGST                | 1        | 1      | 5%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 18.18%  |
| SK hynix            | 1        | 1      | 9.09%   |
| SanDisk             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |
| PNY                 | 1        | 1      | 9.09%   |
| Gigabyte Technology | 1        | 1      | 9.09%   |
| Crucial             | 1        | 1      | 9.09%   |
| Corsair             | 1        | 1      | 9.09%   |
| China               | 1        | 1      | 9.09%   |
| Apacer              | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 15       | 31     | 50%     |
| SSD  | 11       | 11     | 36.67%  |
| NVMe | 4        | 4      | 13.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 42     | 83.33%  |
| NVMe | 4        | 4      | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 20     | 52%     |
| 0.51-1.0   | 7        | 12     | 28%     |
| 3.01-4.0   | 2        | 7      | 8%      |
| 2.01-3.0   | 1        | 1      | 4%      |
| 10.01-20.0 | 1        | 1      | 4%      |
| 1.01-2.0   | 1        | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 31.82%  |
| 501-1000       | 5        | 22.73%  |
| 1001-2000      | 4        | 18.18%  |
| More than 3000 | 3        | 13.64%  |
| 251-500        | 1        | 4.55%   |
| 2001-3000      | 1        | 4.55%   |
| 1-20           | 1        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 8        | 36.36%  |
| 21-50          | 5        | 22.73%  |
| 51-100         | 3        | 13.64%  |
| More than 3000 | 2        | 9.09%   |
| 251-500        | 2        | 9.09%   |
| 1001-2000      | 1        | 4.55%   |
| 501-1000       | 1        | 4.55%   |

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
| Works    | 13       | 25     | 52%     |
| Detected | 8        | 14     | 32%     |
| Malfunc  | 4        | 7      | 16%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 17       | 56.67%  |
| AMD                       | 5        | 16.67%  |
| Broadcom / LSI            | 2        | 6.67%   |
| Samsung Electronics       | 1        | 3.33%   |
| Phison Electronics        | 1        | 3.33%   |
| Micron/Crucial Technology | 1        | 3.33%   |
| Marvell Technology Group  | 1        | 3.33%   |
| ASMedia Technology        | 1        | 3.33%   |
| Adaptec                   | 1        | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 10%     |
| Intel SATA Controller [RAID mode]                                                       | 3        | 7.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 7.5%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 5%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 5%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 5%      |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 2        | 5%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 2.5%    |
| Phison E12 NVMe Controller                                                              | 1        | 2.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 2.5%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1        | 2.5%    |
| Intel PCIe Data Center SSD                                                              | 1        | 2.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 2.5%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 2.5%    |
| Intel C610/X99 series chipset IDE-r Controller                                          | 1        | 2.5%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 2.5%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 2.5%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 2.5%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 2.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 2.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 2.5%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 2.5%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.5%    |
| Adaptec ASC-39320A U320                                                                 | 1        | 2.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 41.94%  |
| IDE  | 7        | 22.58%  |
| RAID | 4        | 12.9%   |
| NVMe | 4        | 12.9%   |
| SAS  | 2        | 6.45%   |
| SCSI | 1        | 3.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 77.27%  |
| AMD    | 5        | 22.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i7-4770 CPU @ 3.40GHz               | 2        | 9.09%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1        | 4.55%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz           | 1        | 4.55%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz            | 1        | 4.55%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz            | 1        | 4.55%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz    | 1        | 4.55%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 4.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 4.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 4.55%   |
| Intel Core i7-10700 CPU @ 2.90GHz              | 1        | 4.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 4.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz               | 1        | 4.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz               | 1        | 4.55%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz          | 1        | 4.55%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 4.55%   |
| Intel Celeron 2955U @ 1.40GHz                  | 1        | 4.55%   |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 4.55%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 1        | 4.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor          | 1        | 4.55%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 4.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics    | 1        | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 5        | 22.73%  |
| Intel Xeon              | 4        | 18.18%  |
| Intel Core i5           | 2        | 9.09%   |
| Intel Celeron           | 2        | 9.09%   |
| Intel Pentium Dual-Core | 1        | 4.55%   |
| Intel Pentium Dual      | 1        | 4.55%   |
| Intel Core i3           | 1        | 4.55%   |
| Intel Core 2 Quad       | 1        | 4.55%   |
| AMD Ryzen Threadripper  | 1        | 4.55%   |
| AMD Ryzen 9             | 1        | 4.55%   |
| AMD Ryzen 7             | 1        | 4.55%   |
| AMD Ryzen 5             | 1        | 4.55%   |
| AMD Ryzen 3             | 1        | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 40.91%  |
| 8      | 5        | 22.73%  |
| 2      | 4        | 18.18%  |
| 12     | 2        | 9.09%   |
| 24     | 1        | 4.55%   |
| 6      | 1        | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 90.91%  |
| 2      | 2        | 9.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 59.09%  |
| 1      | 9        | 40.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 22       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 3        | 13.64%  |
| 0x306e4    | 2        | 9.09%   |
| 0x206a7    | 2        | 9.09%   |
| 0xa0655    | 1        | 4.55%   |
| 0x706a8    | 1        | 4.55%   |
| 0x6fd      | 1        | 4.55%   |
| 0x40651    | 1        | 4.55%   |
| 0x306f2    | 1        | 4.55%   |
| 0x306a9    | 1        | 4.55%   |
| 0x206c2    | 1        | 4.55%   |
| 0x10677    | 1        | 4.55%   |
| 0x10676    | 1        | 4.55%   |
| 0x0a201009 | 1        | 4.55%   |
| 0x0870100a | 1        | 4.55%   |
| 0x08301039 | 1        | 4.55%   |
| 0x08108109 | 1        | 4.55%   |
| 0x0800820d | 1        | 4.55%   |
| Unknown    | 1        | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 6        | 27.27%  |
| IvyBridge     | 3        | 13.64%  |
| Zen+          | 2        | 9.09%   |
| Zen 2         | 2        | 9.09%   |
| SandyBridge   | 2        | 9.09%   |
| Penryn        | 2        | 9.09%   |
| Zen 3         | 1        | 4.55%   |
| Westmere      | 1        | 4.55%   |
| Goldmont plus | 1        | 4.55%   |
| Core          | 1        | 4.55%   |
| CometLake     | 1        | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 10       | 43.48%  |
| Intel  | 10       | 43.48%  |
| AMD    | 3        | 13.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 8.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 8.7%    |
| AMD RV620 LE [Radeon HD 3450]                                               | 2        | 8.7%    |
| Nvidia TU117GL [T600]                                                       | 1        | 4.35%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 4.35%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 4.35%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 4.35%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 4.35%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 4.35%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 4.35%   |
| Nvidia GK107GL [Quadro K2000]                                               | 1        | 4.35%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 4.35%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 4.35%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 4.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 4.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 4.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 9        | 40.91%  |
| 1 x Intel      | 9        | 40.91%  |
| 1 x AMD        | 3        | 13.64%  |
| Intel + Nvidia | 1        | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 77.27%  |
| Proprietary | 4        | 18.18%  |
| Unknown     | 1        | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 45.45%  |
| 1.01-2.0   | 4        | 18.18%  |
| 0.01-0.5   | 3        | 13.64%  |
| 0.51-1.0   | 2        | 9.09%   |
| 5.01-6.0   | 1        | 4.55%   |
| 3.01-4.0   | 1        | 4.55%   |
| 8.01-16.0  | 1        | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 6        | 33.33%  |
| Samsung Electronics | 4        | 22.22%  |
| Iiyama              | 2        | 11.11%  |
| Acer                | 2        | 11.11%  |
| Sony                | 1        | 5.56%   |
| Hewlett-Packard     | 1        | 5.56%   |
| HCL                 | 1        | 5.56%   |
| ASUSTek Computer    | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Sony LG TV SNY045B 1920x540                                         | 1        | 5.26%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch   | 1        | 5.26%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch   | 1        | 5.26%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch | 1        | 5.26%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch  | 1        | 5.26%   |
| Iiyama PL2483H IVM6138 1920x1080 531x299mm 24.0-inch                | 1        | 5.26%   |
| Iiyama PL2377 IVM561D 1920x1080 510x287mm 23.0-inch                 | 1        | 5.26%   |
| Hewlett-Packard LP2465 HWP2675 1920x1200 519x324mm 24.1-inch        | 1        | 5.26%   |
| HCL HCMELWBN11 HCME444 1366x768 410x230mm 18.5-inch                 | 1        | 5.26%   |
| Dell P2014H DEL4096 1600x900 434x236mm 19.4-inch                    | 1        | 5.26%   |
| Dell P1913 DELA088 1440x900 410x260mm 19.1-inch                     | 1        | 5.26%   |
| Dell LCD Monitor U2414H 3840x1080                                   | 1        | 5.26%   |
| Dell LCD Monitor U2414H                                             | 1        | 5.26%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                   | 1        | 5.26%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                   | 1        | 5.26%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                   | 1        | 5.26%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 521x293mm 23.5-inch        | 1        | 5.26%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                     | 1        | 5.26%   |
| Acer G277HL ACR03FB 1920x1080 598x336mm 27.0-inch                   | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 6        | 31.58%  |
| 3840x1080         | 2        | 10.53%  |
| 1600x900 (HD+)    | 2        | 10.53%  |
| 1440x900 (WXGA+)  | 2        | 10.53%  |
| 1280x1024 (SXGA)  | 2        | 10.53%  |
| 3840x2160 (4K)    | 1        | 5.26%   |
| 1920x540          | 1        | 5.26%   |
| 1920x1200 (WUXGA) | 1        | 5.26%   |
| 1366x768 (WXGA)   | 1        | 5.26%   |
| Unknown           | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 3        | 16.67%  |
| 19      | 3        | 16.67%  |
| 23      | 2        | 11.11%  |
| 17      | 2        | 11.11%  |
| 65      | 1        | 5.56%   |
| 48      | 1        | 5.56%   |
| 31      | 1        | 5.56%   |
| 28      | 1        | 5.56%   |
| 24      | 1        | 5.56%   |
| 20      | 1        | 5.56%   |
| 18      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 38.89%  |
| 401-500     | 5        | 27.78%  |
| 301-350     | 2        | 11.11%  |
| 1001-1500   | 2        | 11.11%  |
| 601-700     | 1        | 5.56%   |
| Unknown     | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 11       | 61.11%  |
| 5/4     | 2        | 11.11%  |
| 16/10   | 2        | 11.11%  |
| 32/9    | 1        | 5.56%   |
| 3/2     | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 4        | 22.22%  |
| 301-350        | 3        | 16.67%  |
| 201-250        | 3        | 16.67%  |
| 141-150        | 3        | 16.67%  |
| 351-500        | 2        | 11.11%  |
| More than 1000 | 1        | 5.56%   |
| 501-1000       | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 83.33%  |
| 1-50    | 1        | 5.56%   |
| 121-160 | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 77.27%  |
| 0     | 4        | 18.18%  |
| 2     | 1        | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 11       | 35.48%  |
| Realtek Semiconductor     | 10       | 32.26%  |
| Qualcomm Atheros          | 2        | 6.45%   |
| Marvell Technology Group  | 2        | 6.45%   |
| Solarflare Communications | 1        | 3.23%   |
| Ralink Technology         | 1        | 3.23%   |
| Microsoft                 | 1        | 3.23%   |
| Linksys                   | 1        | 3.23%   |
| BUFFALO                   | 1        | 3.23%   |
| Broadcom                  | 1        | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 25.71%  |
| Intel Ethernet Connection I217-LM                                 | 3        | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 8.57%   |
| Intel Wireless 3165                                               | 2        | 5.71%   |
| Intel I211 Gigabit Network Connection                             | 2        | 5.71%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 2.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 2.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 2.86%   |
| Realtek 802.11ac NIC                                              | 1        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 2.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 2.86%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 2.86%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 2.86%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 2.86%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.86%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.86%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]          | 1        | 2.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 30%     |
| Qualcomm Atheros      | 2        | 20%     |
| Realtek Semiconductor | 1        | 10%     |
| Ralink Technology     | 1        | 10%     |
| Microsoft             | 1        | 10%     |
| Linksys               | 1        | 10%     |
| BUFFALO               | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel Wireless 3165                                      | 2        | 18.18%  |
| Realtek RTL88x2bu [AC1200 Techkey]                       | 1        | 9.09%   |
| Realtek 802.11ac NIC                                     | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                          | 1        | 9.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter         | 1        | 9.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter         | 1        | 9.09%   |
| Microsoft Xbox 360 Wireless Adapter                      | 1        | 9.09%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter      | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                      | 1        | 9.09%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 10       | 43.48%  |
| Intel                     | 9        | 39.13%  |
| Marvell Technology Group  | 2        | 8.7%    |
| Solarflare Communications | 1        | 4.35%   |
| Broadcom                  | 1        | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 37.5%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 12.5%   |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 4.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.17%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 4.17%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1        | 4.17%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 4.17%   |
| Intel Ethernet Connection I217-V                                  | 1        | 4.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 68.75%  |
| WiFi     | 10       | 31.25%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 86.36%  |
| WiFi     | 3        | 13.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 63.64%  |
| 2     | 8        | 36.36%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 86.36%  |
| Yes  | 3        | 13.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 3        | 42.86%  |
| Integrated System Solution | 1        | 14.29%  |
| IMC Networks               | 1        | 14.29%  |
| Cambridge Silicon Radio    | 1        | 14.29%  |
| Broadcom                   | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                    | 2        | 28.57%  |
| Intel AX200 Bluetooth                                 | 1        | 14.29%  |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 14.29%  |
| IMC Networks Bluetooth Device                         | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 48.57%  |
| Nvidia              | 10       | 28.57%  |
| AMD                 | 6        | 17.14%  |
| C-Media Electronics | 1        | 2.86%   |
| ASUSTek Computer    | 1        | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 7.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3        | 7.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 7.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 7.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 5%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 5%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 5%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 5%      |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2        | 5%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 2.5%    |
| Nvidia High Definition Audio Controller                                    | 1        | 2.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.5%    |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 2.5%    |
| Nvidia GM200 High Definition Audio                                         | 1        | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.5%    |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 2.5%    |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 2.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 2.5%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2.5%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 2.5%    |
| Intel 8 Series HD Audio Controller                                         | 1        | 2.5%    |
| C-Media Electronics SKP PODCAST-300U                                       | 1        | 2.5%    |
| ASUSTek Computer USB Audio                                                 | 1        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.5%    |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 3        | 20%     |
| Micron Technology   | 3        | 20%     |
| G.Skill             | 3        | 20%     |
| Samsung Electronics | 2        | 13.33%  |
| Kingston            | 2        | 13.33%  |
| SK hynix            | 1        | 6.67%   |
| Corsair             | 1        | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 667MT/s                   | 1        | 5.88%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s        | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s              | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM 667MT/s                   | 1        | 5.88%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s  | 1        | 5.88%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s   | 1        | 5.88%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s  | 1        | 5.88%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s              | 1        | 5.88%   |
| Micron RAM 9JSF51272PZ-1G9E2 4GB DIMM DDR3 1866MT/s   | 1        | 5.88%   |
| Micron RAM 8ATF1G64AZ-3G2J1 8GB DIMM DDR4 3200MT/s    | 1        | 5.88%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s   | 1        | 5.88%   |
| Kingston RAM 9965600-012.A01G 16GB RIMM DDR4 2133MT/s | 1        | 5.88%   |
| Kingston RAM 9965600-011.A01G 16GB RIMM DDR4 2133MT/s | 1        | 5.88%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s   | 1        | 5.88%   |
| G.Skill RAM F4-2666C18-32GVK 32GB DIMM DDR4 2666MT/s  | 1        | 5.88%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s    | 1        | 5.88%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s  | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 7        | 50%     |
| DDR3    | 5        | 35.71%  |
| DDR2    | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 85.71%  |
| SODIMM | 1        | 7.14%   |
| RIMM   | 1        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 6        | 40%     |
| 32768 | 2        | 13.33%  |
| 4096  | 2        | 13.33%  |
| 2048  | 2        | 13.33%  |
| 1024  | 2        | 13.33%  |
| 16384 | 1        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 4        | 26.67%  |
| 2133  | 2        | 13.33%  |
| 667   | 2        | 13.33%  |
| 2933  | 1        | 6.67%   |
| 2666  | 1        | 6.67%   |
| 2400  | 1        | 6.67%   |
| 2200  | 1        | 6.67%   |
| 1866  | 1        | 6.67%   |
| 1800  | 1        | 6.67%   |
| 1600  | 1        | 6.67%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| HP OfficeJet 6110 | 1        | 100%    |

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
| 0     | 16       | 72.73%  |
| 1     | 5        | 22.73%  |
| 2     | 1        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 50%     |
| Unassigned class | 1        | 16.67%  |
| Net/ethernet     | 1        | 16.67%  |
| Graphics card    | 1        | 16.67%  |

