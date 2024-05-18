GNOME OS - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for GNOME OS.

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

Total: 23

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450M DS3H-CF               | [c21a61a96d](https://linux-hardware.org/?probe=c21a61a96d) | Mar 23, 2024 |
| MSI           | Z97 GAMING 3                | [c8c107c355](https://linux-hardware.org/?probe=c8c107c355) | Jul 15, 2023 |
| MSI           | Z97 GAMING 3                | [3841eb7ba0](https://linux-hardware.org/?probe=3841eb7ba0) | Jul 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Intel         | H61                         | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| HP            | 82F2 A01                    | [b6cb9447df](https://linux-hardware.org/?probe=b6cb9447df) | Nov 19, 2022 |
| Unknown       | 1.0                         | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Gigabyte      | B450M S2H V2                | [cd6b701253](https://linux-hardware.org/?probe=cd6b701253) | Nov 03, 2021 |
| ASUSTek       | PRIME A320M-K               | [11c23a1f37](https://linux-hardware.org/?probe=11c23a1f37) | Sep 26, 2021 |
| ASUSTek       | PRIME A320M-K               | [b33430e135](https://linux-hardware.org/?probe=b33430e135) | Sep 26, 2021 |
| ASUSTek       | H61M-A/BR                   | [73b5c289e2](https://linux-hardware.org/?probe=73b5c289e2) | Sep 04, 2021 |
| HP            | 8767 A                      | [926ac56be9](https://linux-hardware.org/?probe=926ac56be9) | Aug 10, 2021 |
| Gigabyte      | X570 GAMING X               | [b751f6615d](https://linux-hardware.org/?probe=b751f6615d) | Jul 17, 2021 |
| Gigabyte      | B450M S2H V2                | [d8886335b1](https://linux-hardware.org/?probe=d8886335b1) | Jul 10, 2021 |
| Intel         | X79                         | [9f19896285](https://linux-hardware.org/?probe=9f19896285) | May 13, 2021 |
| Lenovo        | 317E NOK                    | [2ce2a68735](https://linux-hardware.org/?probe=2ce2a68735) | Apr 14, 2021 |
| ASUSTek       | PRIME H410M-K               | [f685fefbec](https://linux-hardware.org/?probe=f685fefbec) | Mar 04, 2021 |
| Acer          | Aspire GX-781               | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| ASUSTek       | SABERTOOTH X79              | [17acfc90d4](https://linux-hardware.org/?probe=17acfc90d4) | Oct 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME OS Nightly | 13       | 72.22%  |
| GNOME OS 3.38    | 2        | 11.11%  |
| GNOME OS 46      | 1        | 5.56%   |
| GNOME OS 43      | 1        | 5.56%   |
| GNOME OS 41      | 1        | 5.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME OS | 18       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.10 | 5        | 26.32%  |
| 5.7.14  | 2        | 10.53%  |
| 5.19.17 | 2        | 10.53%  |
| 5.19.16 | 2        | 10.53%  |
| 5.13.9  | 2        | 10.53%  |
| 6.6.10  | 1        | 5.26%   |
| 6.4.0   | 1        | 5.26%   |
| 5.18.16 | 1        | 5.26%   |
| 5.14.4  | 1        | 5.26%   |
| 5.12.12 | 1        | 5.26%   |
| 5.11.0  | 1        | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.10 | 5        | 26.32%  |
| 5.7.14  | 2        | 10.53%  |
| 5.19.17 | 2        | 10.53%  |
| 5.19.16 | 2        | 10.53%  |
| 5.13.9  | 2        | 10.53%  |
| 6.6.10  | 1        | 5.26%   |
| 6.4.0   | 1        | 5.26%   |
| 5.18.16 | 1        | 5.26%   |
| 5.14.4  | 1        | 5.26%   |
| 5.12.12 | 1        | 5.26%   |
| 5.11.0  | 1        | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 6        | 31.58%  |
| 5.19    | 4        | 21.05%  |
| 5.7     | 2        | 10.53%  |
| 5.13    | 2        | 10.53%  |
| 6.6     | 1        | 5.26%   |
| 6.4     | 1        | 5.26%   |
| 5.18    | 1        | 5.26%   |
| 5.14    | 1        | 5.26%   |
| 5.12    | 1        | 5.26%   |

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


| Name  | Desktops | Percent |
|-------|----------|---------|
| GNOME | 18       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 18       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 6        | 33.33%  |
| pt_BR | 3        | 16.67%  |
| de_DE | 3        | 16.67%  |
| cs_CZ | 2        | 11.11%  |
| ru_UA | 1        | 5.56%   |
| it_IT | 1        | 5.56%   |
| es_ES | 1        | 5.56%   |
| en_IN | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 18       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 18       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 100%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 27.78%  |
| Gigabyte Technology | 4        | 22.22%  |
| Intel               | 2        | 11.11%  |
| Hewlett-Packard     | 2        | 11.11%  |
| MSI                 | 1        | 5.56%   |
| Lenovo              | 1        | 5.56%   |
| Colorful Technology | 1        | 5.56%   |
| Acer                | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| MSI MS-7918                            | 1        | 5.56%   |
| Lenovo IdeaCentre 3 07IMB05 90NB0020IN | 1        | 5.56%   |
| Intel X79                              | 1        | 5.56%   |
| Intel H61                              | 1        | 5.56%   |
| HP Pavilion Gaming Desktop TG01-1xxx   | 1        | 5.56%   |
| HP Pavilion Desktop PC 570-p0xx        | 1        | 5.56%   |
| Gigabyte Z97X-Gaming 7                 | 1        | 5.56%   |
| Gigabyte X570 GAMING X                 | 1        | 5.56%   |
| Gigabyte B450M S2H V2                  | 1        | 5.56%   |
| Gigabyte B450M DS3H                    | 1        | 5.56%   |
| Colorful BATTLE-AX B660M-HD DELUXE     | 1        | 5.56%   |
| ASUS SABERTOOTH X79                    | 1        | 5.56%   |
| ASUS PRIME H410M-K                     | 1        | 5.56%   |
| ASUS PRIME A320M-K                     | 1        | 5.56%   |
| ASUS M5A97 R2.0                        | 1        | 5.56%   |
| ASUS H61M-A/BR                         | 1        | 5.56%   |
| Acer Aspire GX-781                     | 1        | 5.56%   |
| Unknown                                | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Pavilion          | 2        | 11.11%  |
| Gigabyte B450M       | 2        | 11.11%  |
| ASUS PRIME           | 2        | 11.11%  |
| MSI MS-7918          | 1        | 5.56%   |
| Lenovo IdeaCentre    | 1        | 5.56%   |
| Intel X79            | 1        | 5.56%   |
| Intel H61            | 1        | 5.56%   |
| Gigabyte Z97X-Gaming | 1        | 5.56%   |
| Gigabyte X570        | 1        | 5.56%   |
| Colorful BATTLE-AX   | 1        | 5.56%   |
| ASUS SABERTOOTH      | 1        | 5.56%   |
| ASUS M5A97           | 1        | 5.56%   |
| ASUS H61M-A          | 1        | 5.56%   |
| Acer Aspire          | 1        | 5.56%   |
| Unknown              | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 22.22%  |
| 2017 | 4        | 22.22%  |
| 2014 | 2        | 11.11%  |
| 2012 | 2        | 11.11%  |
| 2022 | 1        | 5.56%   |
| 2021 | 1        | 5.56%   |
| 2019 | 1        | 5.56%   |
| 2018 | 1        | 5.56%   |
| 2016 | 1        | 5.56%   |
| 2013 | 1        | 5.56%   |

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
| 16.01-24.0 | 6        | 33.33%  |
| 8.01-16.0  | 6        | 33.33%  |
| 32.01-64.0 | 3        | 16.67%  |
| 3.01-4.0   | 2        | 11.11%  |
| 4.01-8.0   | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 10       | 52.63%  |
| 2.01-3.0 | 4        | 21.05%  |
| 3.01-4.0 | 3        | 15.79%  |
| 4.01-8.0 | 1        | 5.26%   |
| 0.51-1.0 | 1        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 44.44%  |
| 1      | 5        | 27.78%  |
| 4      | 3        | 16.67%  |
| 3      | 2        | 11.11%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 77.78%  |
| Yes       | 4        | 22.22%  |

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
| Yes       | 11       | 61.11%  |
| No        | 7        | 38.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 50%     |
| No        | 9        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Brazil   | 4        | 22.22%  |
| Germany  | 3        | 16.67%  |
| USA      | 2        | 11.11%  |
| Czechia  | 2        | 11.11%  |
| Ukraine  | 1        | 5.56%   |
| Thailand | 1        | 5.56%   |
| Spain    | 1        | 5.56%   |
| Russia   | 1        | 5.56%   |
| Italy    | 1        | 5.56%   |
| India    | 1        | 5.56%   |
| Canada   | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Waldachtal            | 1        | 5.56%   |
| Verden an der Aller   | 1        | 5.56%   |
| Vancouver             | 1        | 5.56%   |
| Tyumen                | 1        | 5.56%   |
| St. Ingbert           | 1        | 5.56%   |
| Si Racha              | 1        | 5.56%   |
| Sesto Fiorentino      | 1        | 5.56%   |
| Sao Bernardo do Campo | 1        | 5.56%   |
| Rio de Janeiro        | 1        | 5.56%   |
| Prague                | 1        | 5.56%   |
| Ottawa                | 1        | 5.56%   |
| Novoyavorovske        | 1        | 5.56%   |
| Kolkata               | 1        | 5.56%   |
| Getxo                 | 1        | 5.56%   |
| Foz do Iguaçu        | 1        | 5.56%   |
| Columbia              | 1        | 5.56%   |
| Brdo                  | 1        | 5.56%   |
| Brasília             | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 10       | 10     | 27.78%  |
| Kingston                  | 6        | 7      | 16.67%  |
| WDC                       | 4        | 4      | 11.11%  |
| Samsung Electronics       | 4        | 6      | 11.11%  |
| Toshiba                   | 3        | 3      | 8.33%   |
| SanDisk                   | 2        | 3      | 5.56%   |
| SK hynix                  | 1        | 1      | 2.78%   |
| PNY                       | 1        | 1      | 2.78%   |
| Phison Electronics        | 1        | 1      | 2.78%   |
| Micron/Crucial Technology | 1        | 1      | 2.78%   |
| Fanxiang                  | 1        | 1      | 2.78%   |
| Apacer                    | 1        | 1      | 2.78%   |
| AirDisk                   | 1        | 1      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seagate ST1000DM003-1SB102 1TB          | 2        | 5.26%   |
| WDC WD5000AAKX-003CA0 500GB             | 1        | 2.63%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1        | 2.63%   |
| WDC WD1600AAJS-22L7A0 160GB             | 1        | 2.63%   |
| WDC WD10EALX-009BA0 1TB                 | 1        | 2.63%   |
| Toshiba HDWD120 2TB                     | 1        | 2.63%   |
| Toshiba DT01ACA100 1TB                  | 1        | 2.63%   |
| Toshiba DT01ACA050 500GB                | 1        | 2.63%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1        | 2.63%   |
| Seagate ST9500325AS 500GB               | 1        | 2.63%   |
| Seagate ST8000DM004-2CX188 8TB          | 1        | 2.63%   |
| Seagate ST4000DX001-1CE168 4TB          | 1        | 2.63%   |
| Seagate ST3500312CS 500GB               | 1        | 2.63%   |
| Seagate ST2000DM001-1ER164 2TB          | 1        | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB          | 1        | 2.63%   |
| Seagate ST1000DM010-2EP102 1TB          | 1        | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB          | 1        | 2.63%   |
| SanDisk Ultra II 240GB SSD              | 1        | 2.63%   |
| SanDisk NVMe SSD Drive 500GB            | 1        | 2.63%   |
| Samsung SSD 860 QVO 1TB                 | 1        | 2.63%   |
| Samsung SSD 840 EVO 250GB               | 1        | 2.63%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB  | 1        | 2.63%   |
| Samsung NVMe SSD Drive 512GB            | 1        | 2.63%   |
| Samsung NVMe SSD Drive 1024GB           | 1        | 2.63%   |
| PNY CS900 240GB SSD                     | 1        | 2.63%   |
| Phison PS5013 E13 NVMe Controller 512GB | 1        | 2.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB     | 1        | 2.63%   |
| Kingston SV300S37A240G 240GB SSD        | 1        | 2.63%   |
| Kingston SV300S37A120G 120GB SSD        | 1        | 2.63%   |
| Kingston SUV400S37120G 120GB SSD        | 1        | 2.63%   |
| Kingston SNVS500G 500GB                 | 1        | 2.63%   |
| Kingston SMS200S360G 64GB SSD           | 1        | 2.63%   |
| Kingston SA400S37120G 120GB SSD         | 1        | 2.63%   |
| Kingston SA400M8240G 240GB SSD          | 1        | 2.63%   |
| Fanxiang S101 1TB SSD                   | 1        | 2.63%   |
| Apacer AS350 120GB SSD                  | 1        | 2.63%   |
| AirDisk 128GB SSD                       | 1        | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 10     | 58.82%  |
| WDC     | 4        | 4      | 23.53%  |
| Toshiba | 3        | 3      | 17.65%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 42.86%  |
| Samsung Electronics | 2        | 3      | 14.29%  |
| SK hynix            | 1        | 1      | 7.14%   |
| SanDisk             | 1        | 1      | 7.14%   |
| PNY                 | 1        | 1      | 7.14%   |
| Fanxiang            | 1        | 1      | 7.14%   |
| Apacer              | 1        | 1      | 7.14%   |
| AirDisk             | 1        | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 17     | 43.75%  |
| SSD  | 11       | 15     | 34.38%  |
| NVMe | 7        | 8      | 21.88%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 17       | 32     | 70.83%  |
| NVMe | 7        | 8      | 29.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 17     | 46.15%  |
| 0.51-1.0   | 9        | 10     | 34.62%  |
| 3.01-4.0   | 2        | 2      | 7.69%   |
| 1.01-2.0   | 2        | 2      | 7.69%   |
| 4.01-10.0  | 1        | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 8        | 44.44%  |
| 501-1000   | 4        | 22.22%  |
| 251-500    | 3        | 16.67%  |
| 1001-2000  | 2        | 11.11%  |
| 51-100     | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 13       | 68.42%  |
| 101-250  | 2        | 10.53%  |
| 251-500  | 1        | 5.26%   |
| 21-50    | 1        | 5.26%   |
| 501-1000 | 1        | 5.26%   |
| 51-100   | 1        | 5.26%   |

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
| Detected | 18       | 40     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 13       | 46.43%  |
| AMD                         | 5        | 17.86%  |
| Samsung Electronics         | 3        | 10.71%  |
| Marvell Technology Group    | 2        | 7.14%   |
| SanDisk                     | 1        | 3.57%   |
| Phison Electronics          | 1        | 3.57%   |
| Micron/Crucial Technology   | 1        | 3.57%   |
| Kingston Technology Company | 1        | 3.57%   |
| ASMedia Technology          | 1        | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 12.5%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 6.25%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 6.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2        | 6.25%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 6.25%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 1        | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 3.13%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 1        | 3.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 3.13%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 3.13%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 3.13%   |
| Kingston Company NV1 NVMe SSD E13T (DRAM-less)                                          | 1        | 3.13%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 3.13%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 3.13%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 3.13%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 1        | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 3.13%   |
| AMD FCH SATA Controller D                                                               | 1        | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 64%     |
| NVMe | 7        | 28%     |
| RAID | 1        | 4%      |
| IDE  | 1        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 72.22%  |
| AMD    | 5        | 27.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2660 0 @ 2.20GHz          | 1        | 5.56%   |
| Intel Pentium CPU J4205 @ 1.50GHz           | 1        | 5.56%   |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1        | 5.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 5.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 5.56%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 5.56%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 5.56%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 5.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 5.56%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 1        | 5.56%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 5.56%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 5.56%   |
| Intel 12th Gen Core i3-12100                | 1        | 5.56%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 1        | 5.56%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 1        | 5.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 5.56%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 1        | 5.56%   |
| AMD FX-6300 Six-Core Processor              | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i3 | 4        | 22.22%  |
| AMD Ryzen 5   | 4        | 22.22%  |
| Intel Core i5 | 3        | 16.67%  |
| Intel Core i7 | 2        | 11.11%  |
| Other         | 1        | 5.56%   |
| Intel Xeon    | 1        | 5.56%   |
| Intel Pentium | 1        | 5.56%   |
| Intel Celeron | 1        | 5.56%   |
| AMD FX        | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 44.44%  |
| 6      | 5        | 27.78%  |
| 2      | 3        | 16.67%  |
| 8      | 1        | 5.56%   |
| 3      | 1        | 5.56%   |

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
| 2      | 14       | 77.78%  |
| 1      | 4        | 22.22%  |

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
| 0xa0653    | 3        | 16.67%  |
| 0x906e9    | 2        | 11.11%  |
| 0x90675    | 1        | 5.56%   |
| 0x506c9    | 1        | 5.56%   |
| 0x306e4    | 1        | 5.56%   |
| 0x306c3    | 1        | 5.56%   |
| 0x306a9    | 1        | 5.56%   |
| 0x206d7    | 1        | 5.56%   |
| 0x206a7    | 1        | 5.56%   |
| 0x0a201009 | 1        | 5.56%   |
| 0x08701021 | 1        | 5.56%   |
| 0x08108109 | 1        | 5.56%   |
| 0x0800820d | 1        | 5.56%   |
| 0x06000822 | 1        | 5.56%   |
| Unknown    | 1        | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| CometLake        | 3        | 16.67%  |
| Zen+             | 2        | 11.11%  |
| SandyBridge      | 2        | 11.11%  |
| KabyLake         | 2        | 11.11%  |
| IvyBridge        | 2        | 11.11%  |
| Haswell          | 2        | 11.11%  |
| Zen 3            | 1        | 5.56%   |
| Zen 2            | 1        | 5.56%   |
| Piledriver       | 1        | 5.56%   |
| Goldmont         | 1        | 5.56%   |
| Alderlake Hybrid | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 10       | 55.56%  |
| Intel  | 4        | 22.22%  |
| AMD    | 4        | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 3GB]                                       | 3        | 16.67%  |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2        | 11.11%  |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1        | 5.56%   |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1        | 5.56%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1        | 5.56%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 5.56%   |
| Intel HD Graphics 630                                                     | 1        | 5.56%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 5.56%   |
| Intel Apollo Lake [HD Graphics 505]                                       | 1        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 5.56%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                  | 1        | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 5.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 5.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 10       | 55.56%  |
| 1 x Intel  | 4        | 22.22%  |
| 1 x AMD    | 4        | 22.22%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Desktops | Percent |
|--------|----------|---------|
| Free   | 18       | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 22.22%  |
| 7.01-8.0   | 3        | 16.67%  |
| 3.01-4.0   | 3        | 16.67%  |
| 2.01-3.0   | 3        | 16.67%  |
| 1.01-2.0   | 3        | 16.67%  |
| 5.01-6.0   | 2        | 11.11%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 31.58%  |
| Goldstar            | 4        | 21.05%  |
| AOC                 | 3        | 15.79%  |
| Acer                | 2        | 10.53%  |
| Viotek              | 1        | 5.26%   |
| Sony                | 1        | 5.26%   |
| Philips             | 1        | 5.26%   |
| Iiyama              | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch   | 2        | 10%     |
| Viotek GNV34DBE VTK3400 3440x1440 797x334mm 34.0-inch               | 1        | 5%      |
| Sony TV SNY4803 1920x1080 930x523mm 42.0-inch                       | 1        | 5%      |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch | 1        | 5%      |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch  | 1        | 5%      |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch   | 1        | 5%      |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch   | 1        | 5%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch   | 1        | 5%      |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch             | 1        | 5%      |
| Iiyama X2485 IVM6122 1920x1200 518x324mm 24.1-inch                  | 1        | 5%      |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                 | 1        | 5%      |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                 | 1        | 5%      |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch            | 1        | 5%      |
| Goldstar 24GL600F GSM5B73 1920x1080 530x300mm 24.0-inch             | 1        | 5%      |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                    | 1        | 5%      |
| AOC 2260WG5 AOC2260 1920x1080 477x268mm 21.5-inch                   | 1        | 5%      |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                      | 1        | 5%      |
| Acer K222HQL ACR0512 1920x1080 477x268mm 21.5-inch                  | 1        | 5%      |
| Acer FT220HQL ACR03D2 1920x1080 476x268mm 21.5-inch                 | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 12       | 70.59%  |
| 3840x2160 (4K)    | 1        | 5.88%   |
| 3440x1440         | 1        | 5.88%   |
| 1920x1200 (WUXGA) | 1        | 5.88%   |
| 1440x900 (WXGA+)  | 1        | 5.88%   |
| 1366x768 (WXGA)   | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 4        | 21.05%  |
| 24     | 3        | 15.79%  |
| 23     | 3        | 15.79%  |
| 40     | 2        | 10.53%  |
| 72     | 1        | 5.26%   |
| 60     | 1        | 5.26%   |
| 34     | 1        | 5.26%   |
| 31     | 1        | 5.26%   |
| 22     | 1        | 5.26%   |
| 18     | 1        | 5.26%   |
| 17     | 1        | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 6        | 33.33%  |
| 501-600     | 5        | 27.78%  |
| 801-900     | 2        | 11.11%  |
| 701-800     | 1        | 5.56%   |
| 601-700     | 1        | 5.56%   |
| 351-400     | 1        | 5.56%   |
| 1501-2000   | 1        | 5.56%   |
| 1001-1500   | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 77.78%  |
| 16/10 | 3        | 16.67%  |
| 21/9  | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 50%     |
| More than 1000 | 2        | 11.11%  |
| 351-500        | 2        | 11.11%  |
| 501-1000       | 2        | 11.11%  |
| 251-300        | 1        | 5.56%   |
| 141-150        | 1        | 5.56%   |
| 131-140        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 66.67%  |
| 101-120 | 5        | 27.78%  |
| 1-50    | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 83.33%  |
| 2     | 3        | 16.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 14       | 48.28%  |
| Intel                           | 7        | 24.14%  |
| Qualcomm Atheros                | 2        | 6.9%    |
| Samsung Electronics             | 1        | 3.45%   |
| Ralink Technology               | 1        | 3.45%   |
| Qualcomm Atheros Communications | 1        | 3.45%   |
| Motorola PCS                    | 1        | 3.45%   |
| Google                          | 1        | 3.45%   |
| Broadcom Limited                | 1        | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 37.5%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 9.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 6.25%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 3.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 3.13%   |
| Ralink RT2770 Wireless Adapter                                         | 1        | 3.13%   |
| Qualcomm Atheros AR9271 802.11n                                        | 1        | 3.13%   |
| Motorola PCS moto g82 5G                                               | 1        | 3.13%   |
| Intel Wireless 8260                                                    | 1        | 3.13%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 3.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1        | 3.13%   |
| Intel Ethernet Controller I225-V                                       | 1        | 3.13%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 3.13%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 3.13%   |
| Google Nexus/Pixel Device (tether)                                     | 1        | 3.13%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 3.13%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 4        | 36.36%  |
| Intel                           | 4        | 36.36%  |
| Ralink Technology               | 1        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| Broadcom Limited                | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 27.27%  |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 9.09%   |
| Ralink RT2770 Wireless Adapter                                       | 1        | 9.09%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1        | 9.09%   |
| Intel Wireless 8260                                                  | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 9.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 9.09%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 65%     |
| Intel                 | 3        | 15%     |
| Qualcomm Atheros      | 2        | 10%     |
| Samsung Electronics   | 1        | 5%      |
| Google                | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 60%     |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 10%     |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 5%      |
| Intel Ethernet Controller I225-V                                       | 1        | 5%      |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 5%      |
| Intel 82579V Gigabit Network Connection                                | 1        | 5%      |
| Google Nexus/Pixel Device (tether)                                     | 1        | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 60%     |
| WiFi     | 11       | 36.67%  |
| Unknown  | 1        | 3.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 68.75%  |
| WiFi     | 5        | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 9        | 50%     |
| 1     | 9        | 50%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 72.22%  |
| Yes  | 5        | 27.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 3        | 30%     |
| Intel                   | 3        | 30%     |
| Cambridge Silicon Radio | 1        | 10%     |
| Broadcom                | 1        | 10%     |
| ASUSTek Computer        | 1        | 10%     |
| Apple                   | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 20%     |
| Realtek Bluetooth Radio                             | 1        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |
| Intel Bluetooth Device                              | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |
| Broadcom BCM2045 Bluetooth                          | 1        | 10%     |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 10%     |
| Apple Bluetooth USB Host Controller                 | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 13       | 39.39%  |
| Nvidia              | 10       | 30.3%   |
| AMD                 | 6        | 18.18%  |
| C-Media Electronics | 2        | 6.06%   |
| Guillemot           | 1        | 3.03%   |
| Creative Labs       | 1        | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                              | 5        | 13.89%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 8.33%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 5.56%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2        | 5.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 5.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 5.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.78%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 2.78%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 2.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 2.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 2.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.78%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.78%   |
| Guillemot Hercules DJ Console 4-Mx                                         | 1        | 2.78%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 2.78%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 2.78%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.78%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

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


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Microsoft     | 1        | 33.33%  |
| Logitech      | 1        | 33.33%  |
| 2M UVC CAMERA | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microsoft LifeCam Cinema            | 1        | 33.33%  |
| Logitech HD Pro Webcam C920         | 1        | 33.33%  |
| 2M UVC CAMERA NexiGo N60 FHD Webcam | 1        | 33.33%  |

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
| 1     | 9        | 50%     |
| 0     | 5        | 27.78%  |
| 2     | 3        | 16.67%  |
| 3     | 1        | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 11       | 61.11%  |
| Net/wireless             | 3        | 16.67%  |
| Net/ethernet             | 1        | 5.56%   |
| Graphics card            | 1        | 5.56%   |
| Firewire controller      | 1        | 5.56%   |
| Bluetooth                | 1        | 5.56%   |

