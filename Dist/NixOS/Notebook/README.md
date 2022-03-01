NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.13.7          | 2         | 9.52%   |
| 5.8.4           | 1         | 4.76%   |
| 5.8.16-hardened | 1         | 4.76%   |
| 5.8.11          | 1         | 4.76%   |
| 5.7.4           | 1         | 4.76%   |
| 5.7.17          | 1         | 4.76%   |
| 5.4.24          | 1         | 4.76%   |
| 5.16.8-zen1     | 1         | 4.76%   |
| 5.16.7          | 1         | 4.76%   |
| 5.16.3          | 1         | 4.76%   |
| 5.15.4          | 1         | 4.76%   |
| 5.15.3          | 1         | 4.76%   |
| 5.15.12         | 1         | 4.76%   |
| 5.15.0          | 1         | 4.76%   |
| 5.13.2          | 1         | 4.76%   |
| 5.12.7          | 1         | 4.76%   |
| 5.10.69         | 1         | 4.76%   |
| 5.10.30         | 1         | 4.76%   |
| 4.19.57         | 1         | 4.76%   |
| 4.19.116        | 1         | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.13.7   | 2         | 9.52%   |
| 5.8.4    | 1         | 4.76%   |
| 5.8.16   | 1         | 4.76%   |
| 5.8.11   | 1         | 4.76%   |
| 5.7.4    | 1         | 4.76%   |
| 5.7.17   | 1         | 4.76%   |
| 5.4.24   | 1         | 4.76%   |
| 5.16.8   | 1         | 4.76%   |
| 5.16.7   | 1         | 4.76%   |
| 5.16.3   | 1         | 4.76%   |
| 5.15.4   | 1         | 4.76%   |
| 5.15.3   | 1         | 4.76%   |
| 5.15.12  | 1         | 4.76%   |
| 5.15.0   | 1         | 4.76%   |
| 5.13.2   | 1         | 4.76%   |
| 5.12.7   | 1         | 4.76%   |
| 5.10.69  | 1         | 4.76%   |
| 5.10.30  | 1         | 4.76%   |
| 4.19.57  | 1         | 4.76%   |
| 4.19.116 | 1         | 4.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 4         | 19.05%  |
| 5.8     | 3         | 14.29%  |
| 5.16    | 3         | 14.29%  |
| 5.13    | 3         | 14.29%  |
| 5.7     | 2         | 9.52%   |
| 5.10    | 2         | 9.52%   |
| 4.19    | 2         | 9.52%   |
| 5.4     | 1         | 4.76%   |
| 5.12    | 1         | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 19        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 89.47%  |
| XFCE    | 1         | 5.26%   |
| GNOME   | 1         | 5.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 89.47%  |
| X11     | 1         | 5.26%   |
| Wayland | 1         | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 94.74%  |
| GDM     | 1         | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 78.95%  |
| en_US   | 3         | 15.79%  |
| ru_RU   | 1         | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 17        | 89.47%  |
| BIOS | 2         | 10.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 14        | 70%     |
| Btrfs   | 3         | 15%     |
| Unknown | 2         | 10%     |
| Tmpfs   | 1         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 16        | 84.21%  |
| Unknown | 3         | 15.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 68.42%  |
| Yes       | 6         | 31.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 68.42%  |
| Yes       | 6         | 31.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 42.11%  |
| ASUSTek Computer    | 3         | 15.79%  |
| Hewlett-Packard     | 2         | 10.53%  |
| Dell                | 2         | 10.53%  |
| OBSIDIAN-PC         | 1         | 5.26%   |
| MSI                 | 1         | 5.26%   |
| Gigabyte Technology | 1         | 5.26%   |
| Acer                | 1         | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| OBSIDIAN-PC N13_N140ZU                | 1         | 5.26%   |
| MSI Bravo 15 B5DD                     | 1         | 5.26%   |
| Lenovo ThinkPad X390 20Q0CTO1WW       | 1         | 5.26%   |
| Lenovo ThinkPad X250 20CLS18S0T       | 1         | 5.26%   |
| Lenovo ThinkPad T580 20L90024PB       | 1         | 5.26%   |
| Lenovo ThinkPad T480 20L5CTO1WW       | 1         | 5.26%   |
| Lenovo ThinkPad T460p 20FWCTO1WW      | 1         | 5.26%   |
| Lenovo ThinkPad T15 Gen 1 20S6CTO1WW  | 1         | 5.26%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013RT  | 1         | 5.26%   |
| Lenovo Legion 5 17ARH05H 82GN         | 1         | 5.26%   |
| HP ZBook Studio G5                    | 1         | 5.26%   |
| HP ProBook 445 G7                     | 1         | 5.26%   |
| Gigabyte Sabre 15                     | 1         | 5.26%   |
| Dell XPS 15 9550                      | 1         | 5.26%   |
| Dell Latitude 7420                    | 1         | 5.26%   |
| ASUS ZenBook UX391FA_UX391FA          | 1         | 5.26%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 1         | 5.26%   |
| ASUS ROG Strix G533QR_G533QR          | 1         | 5.26%   |
| Acer Aspire E5-576G                   | 1         | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 7         | 36.84%  |
| ASUS ROG        | 2         | 10.53%  |
| OBSIDIAN-PC N13 | 1         | 5.26%   |
| MSI Bravo       | 1         | 5.26%   |
| Lenovo Legion   | 1         | 5.26%   |
| HP ZBook        | 1         | 5.26%   |
| HP ProBook      | 1         | 5.26%   |
| Gigabyte Sabre  | 1         | 5.26%   |
| Dell XPS        | 1         | 5.26%   |
| Dell Latitude   | 1         | 5.26%   |
| ASUS ZenBook    | 1         | 5.26%   |
| Acer Aspire     | 1         | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 6         | 31.58%  |
| 2018 | 4         | 21.05%  |
| 2021 | 2         | 10.53%  |
| 2019 | 2         | 10.53%  |
| 2017 | 2         | 10.53%  |
| 2015 | 2         | 10.53%  |
| 2016 | 1         | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 19        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 19        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 32.01-64.0 | 9         | 47.37%  |
| 16.01-24.0 | 8         | 42.11%  |
| 8.01-16.0  | 2         | 10.53%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 33.33%  |
| 3.01-4.0   | 5         | 23.81%  |
| 2.01-3.0   | 3         | 14.29%  |
| 8.01-16.0  | 3         | 14.29%  |
| 24.01-32.0 | 2         | 9.52%   |
| 1.01-2.0   | 1         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 68.42%  |
| 2      | 6         | 31.58%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 80%     |
| No        | 4         | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 94.74%  |
| No        | 1         | 5.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 90%     |
| No        | 2         | 10%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Ukraine     | 3         | 15.79%  |
| UK          | 2         | 10.53%  |
| Russia      | 2         | 10.53%  |
| France      | 2         | 10.53%  |
| Canada      | 2         | 10.53%  |
| Uruguay     | 1         | 5.26%   |
| Switzerland | 1         | 5.26%   |
| Spain       | 1         | 5.26%   |
| Portugal    | 1         | 5.26%   |
| Netherlands | 1         | 5.26%   |
| Germany     | 1         | 5.26%   |
| Colombia    | 1         | 5.26%   |
| Austria     | 1         | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Vienna      | 1         | 5%      |
| Vernouillet | 1         | 5%      |
| Valpacos    | 1         | 5%      |
| Tottenham   | 1         | 5%      |
| Samara      | 1         | 5%      |
| QuÃ©bec   | 1         | 5%      |
| Mykolayiv   | 1         | 5%      |
| Montevideo  | 1         | 5%      |
| London      | 1         | 5%      |
| Kiel        | 1         | 5%      |
| Kharkiv     | 1         | 5%      |
| Irpin       | 1         | 5%      |
| Halifax     | 1         | 5%      |
| Getafe      | 1         | 5%      |
| Enschede    | 1         | 5%      |
| Chelyabinsk | 1         | 5%      |
| Cergy       | 1         | 5%      |
| Cartagena   | 1         | 5%      |
| Bedford     | 1         | 5%      |
| Arlesheim   | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 44%     |
| WDC                 | 2         | 2      | 8%      |
| Transcend           | 2         | 2      | 8%      |
| SK Hynix            | 2         | 3      | 8%      |
| Kingston            | 2         | 2      | 8%      |
| Seagate             | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| KIOXIA              | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| INNOVATION IT       | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 3.85%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 3.85%   |
| Transcend TS256GMTS800 256GB SSD     | 1         | 3.85%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 3.85%   |
| SK Hynix NVMe SSD Drive 1TB          | 1         | 3.85%   |
| SK Hynix NVMe SSD Drive 1024GB       | 1         | 3.85%   |
| SK Hynix HFM001TD3JX013N 1TB         | 1         | 3.85%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 3.85%   |
| Samsung SSD 970 EVO 500GB            | 1         | 3.85%   |
| Samsung SSD 860 EVO 1TB              | 1         | 3.85%   |
| Samsung Portable SSD T5 500GB        | 1         | 3.85%   |
| Samsung PM9A1 NVMe 1024GB            | 1         | 3.85%   |
| Samsung NVMe SSD Drive 512GB         | 1         | 3.85%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 1         | 3.85%   |
| Samsung MZVLB512HAJQ-000H1 512GB     | 1         | 3.85%   |
| Samsung MZVLB512HAJQ-00000 512GB     | 1         | 3.85%   |
| Samsung MZVLB256HAHQ-000L7 256GB     | 1         | 3.85%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 1         | 3.85%   |
| Samsung MZ7LN512HMJP-000L7 512GB SSD | 1         | 3.85%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 1         | 3.85%   |
| KIOXIA NVMe SSD Drive 256GB          | 1         | 3.85%   |
| Kingston SA400S37960G 960GB SSD      | 1         | 3.85%   |
| Kingston OM8PCP3512F-AI1 512GB       | 1         | 3.85%   |
| Intel SSDPEKKF010T8L 1TB             | 1         | 3.85%   |
| INNOVATION IT IT 512GB SSD           | 1         | 3.85%   |
| HGST HTS721010A9E630 1TB             | 1         | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 37.5%   |
| Transcend           | 2         | 2      | 25%     |
| Micron Technology   | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |
| INNOVATION IT       | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 18     | 65.22%  |
| SSD  | 6         | 8      | 26.09%  |
| HDD  | 2         | 2      | 8.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 18     | 68.18%  |
| SATA | 6         | 9      | 27.27%  |
| SAS  | 1         | 1      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 5         | 5      | 50%     |
| 0.01-0.5   | 4         | 4      | 40%     |
| 1.01-2.0   | 1         | 1      | 10%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 84.21%  |
| 251-500    | 1         | 5.26%   |
| 1001-2000  | 1         | 5.26%   |
| 501-1000   | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 84.21%  |
| 101-250 | 2         | 10.53%  |
| 251-500 | 1         | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 16        | 21     | 76.19%  |
| Detected | 4         | 6      | 19.05%  |
| Malfunc  | 1         | 1      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Samsung Electronics         | 8         | 33.33%  |
| Intel                       | 8         | 33.33%  |
| SK Hynix                    | 2         | 8.33%   |
| Sandisk                     | 2         | 8.33%   |
| AMD                         | 2         | 8.33%   |
| KIOXIA                      | 1         | 4.17%   |
| Kingston Technology Company | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983           | 6         | 25%     |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]   | 3         | 12.5%   |
| SK Hynix Gold P31 SSD                                   | 2         | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                     | 2         | 8.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD              | 1         | 4.17%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD         | 1         | 4.17%   |
| Samsung NVMe SSD Controller SM951/PM951                 | 1         | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO          | 1         | 4.17%   |
| KIOXIA Non-Volatile memory controller                   | 1         | 4.17%   |
| Kingston Company Company Non-Volatile memory controller | 1         | 4.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]      | 1         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]      | 1         | 4.17%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                 | 1         | 4.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]       | 1         | 4.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller       | 1         | 4.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 15        | 62.5%   |
| SATA | 9         | 37.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 13        | 68.42%  |
| AMD    | 6         | 31.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz          | 3         | 15.79%  |
| Intel Core i7-8565U CPU @ 1.80GHz          | 2         | 10.53%  |
| AMD Ryzen 7 5800H with Radeon Graphics     | 2         | 10.53%  |
| Intel Xeon E-2176M CPU @ 2.70GHz           | 1         | 5.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 1         | 5.26%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 1         | 5.26%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 1         | 5.26%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 1         | 5.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 1         | 5.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 1         | 5.26%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 1         | 5.26%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 1         | 5.26%   |
| AMD Ryzen 7 5800HS with Radeon Graphics    | 1         | 5.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics     | 1         | 5.26%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 1         | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i7   | 10        | 52.63%  |
| AMD Ryzen 7     | 5         | 26.32%  |
| Other           | 1         | 5.26%   |
| Intel Xeon      | 1         | 5.26%   |
| Intel Core i5   | 1         | 5.26%   |
| AMD Ryzen 7 PRO | 1         | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 11        | 57.89%  |
| 8      | 6         | 31.58%  |
| 6      | 1         | 5.26%   |
| 2      | 1         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 94.74%  |
| 1      | 1         | 5.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 3         | 15.79%  |
| 0x806ec    | 2         | 10.53%  |
| 0x806eb    | 2         | 10.53%  |
| 0x0a50000c | 2         | 10.53%  |
| 0x08600106 | 2         | 10.53%  |
| 0x906ea    | 1         | 5.26%   |
| 0x906e9    | 1         | 5.26%   |
| 0x806c1    | 1         | 5.26%   |
| 0x506e3    | 1         | 5.26%   |
| 0x306d4    | 1         | 5.26%   |
| 0x0a50000b | 1         | 5.26%   |
| 0x08600104 | 1         | 5.26%   |
| Unknown    | 1         | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| KabyLake  | 9         | 47.37%  |
| Zen 3     | 3         | 15.79%  |
| Zen 2     | 3         | 15.79%  |
| Skylake   | 2         | 10.53%  |
| TigerLake | 1         | 5.26%   |
| Broadwell | 1         | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 44.44%  |
| Nvidia | 9         | 33.33%  |
| AMD    | 6         | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]      | 3         | 10.71%  |
| Intel UHD Graphics 620                          | 3         | 10.71%  |
| AMD Renoir                                      | 3         | 10.71%  |
| AMD Cezanne                                     | 3         | 10.71%  |
| Nvidia GP108M [GeForce MX150]                   | 2         | 7.14%   |
| Intel HD Graphics 530                           | 2         | 7.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]      | 1         | 3.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]      | 1         | 3.57%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]           | 1         | 3.57%   |
| Nvidia GM108M [GeForce 940MX]                   | 1         | 3.57%   |
| Nvidia GM107M [GeForce GTX 960M]                | 1         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q] | 1         | 3.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q] | 1         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]       | 1         | 3.57%   |
| Intel HD Graphics 630                           | 1         | 3.57%   |
| Intel HD Graphics 5500                          | 1         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]            | 1         | 3.57%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]  | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 7         | 36.84%  |
| Intel + Nvidia | 5         | 26.32%  |
| AMD + Nvidia   | 3         | 15.79%  |
| 1 x AMD        | 2         | 10.53%  |
| 2 x AMD        | 1         | 5.26%   |
| 1 x Nvidia     | 1         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 16        | 84.21%  |
| Proprietary | 3         | 15.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 57.89%  |
| 0.01-0.5   | 5         | 26.32%  |
| 1.01-2.0   | 2         | 10.53%  |
| 3.01-4.0   | 1         | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 4         | 14.29%  |
| AU Optronics        | 4         | 14.29%  |
| Samsung Electronics | 3         | 10.71%  |
| Dell                | 3         | 10.71%  |
| Chimei Innolux      | 3         | 10.71%  |
| PANDA               | 2         | 7.14%   |
| BOE                 | 2         | 7.14%   |
| Sharp               | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| JDI                 | 1         | 3.57%   |
| Hewlett-Packard     | 1         | 3.57%   |
| Eizo                | 1         | 3.57%   |
| ASUSTek Computer    | 1         | 3.57%   |
| AOC                 | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch           | 1         | 3.57%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch | 1         | 3.57%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch | 1         | 3.57%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch | 1         | 3.57%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch           | 1         | 3.57%   |
| PANDA LCD Monitor NCP005E 1920x1080 309x174mm 14.0-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch      | 1         | 3.57%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch      | 1         | 3.57%   |
| LG Display LCD Monitor LGD049A 2560x1440 310x174mm 14.0-inch      | 1         | 3.57%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch      | 1         | 3.57%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 1         | 3.57%   |
| JDI LCD Monitor JDI385A 3840x2160 294x165mm 13.3-inch             | 1         | 3.57%   |
| Hewlett-Packard Z27 HPN3535 3840x2160 597x336mm 27.0-inch         | 1         | 3.57%   |
| Eizo L568 ENC1734 1280x1024 338x270mm 17.0-inch                   | 1         | 3.57%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                 | 1         | 3.57%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                 | 1         | 3.57%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                 | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN175C 1920x1080 381x214mm 17.2-inch  | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch  | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch  | 1         | 3.57%   |
| BOE LCD Monitor BOE0957 1920x1080 344x194mm 15.5-inch             | 1         | 3.57%   |
| BOE LCD Monitor BOE08D8 1920x1080 344x194mm 15.5-inch             | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch    | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch    | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch    | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch    | 1         | 3.57%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch      | 1         | 3.57%   |
| AOC G2770 AOC2770 1920x1080 598x336mm 27.0-inch                   | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 14        | 53.85%  |
| 3840x2160 (4K)   | 5         | 19.23%  |
| 2560x1440 (QHD)  | 5         | 19.23%  |
| 3440x1440        | 1         | 3.85%   |
| 1280x1024 (SXGA) | 1         | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 25%     |
| 14     | 6         | 21.43%  |
| 27     | 5         | 17.86%  |
| 13     | 3         | 10.71%  |
| 17     | 2         | 7.14%   |
| 34     | 1         | 3.57%   |
| 31     | 1         | 3.57%   |
| 24     | 1         | 3.57%   |
| 23     | 1         | 3.57%   |
| 12     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 51.85%  |
| 501-600     | 6         | 22.22%  |
| 201-300     | 3         | 11.11%  |
| 601-700     | 2         | 7.41%   |
| 701-800     | 1         | 3.7%    |
| 351-400     | 1         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 90%     |
| 5/4   | 1         | 5%      |
| 21/9  | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 25%     |
| 101-110        | 7         | 25%     |
| 301-350        | 5         | 17.86%  |
| 71-80          | 2         | 7.14%   |
| 351-500        | 2         | 7.14%   |
| 201-250        | 2         | 7.14%   |
| 61-70          | 1         | 3.57%   |
| 141-150        | 1         | 3.57%   |
| 121-130        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 44%     |
| 161-240       | 6         | 24%     |
| 51-100        | 4         | 16%     |
| More than 240 | 2         | 8%      |
| 101-120       | 2         | 8%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10        | 50%     |
| 2     | 8         | 40%     |
| 3     | 1         | 5%      |
| 0     | 1         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 56.25%  |
| Realtek Semiconductor | 12        | 37.5%   |
| Microsoft             | 1         | 3.13%   |
| Fibocom               | 1         | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 19.51%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 14.63%  |
| Intel Wi-Fi 6 AX200                                               | 5         | 12.2%   |
| Intel Wireless-AC 9260                                            | 2         | 4.88%   |
| Intel Wireless 8265 / 8275                                        | 2         | 4.88%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 4.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 4.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 4.88%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1         | 2.44%   |
| Intel Wireless 8260                                               | 1         | 2.44%   |
| Intel Wireless 7265                                               | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.44%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.44%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.44%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 1         | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 18        | 90%     |
| Microsoft | 1         | 5%      |
| Fibocom   | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                              | 5         | 25%     |
| Intel Wireless-AC 9260                           | 2         | 10%     |
| Intel Wireless 8265 / 8275                       | 2         | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak] | 2         | 10%     |
| Intel Cannon Point-LP CNVi [Wireless-AC]         | 2         | 10%     |
| Microsoft Xbox 360 Wireless Adapter              | 1         | 5%      |
| Intel Wireless 8260                              | 1         | 5%      |
| Intel Wireless 7265                              | 1         | 5%      |
| Intel Wi-Fi 6 AX201                              | 1         | 5%      |
| Intel Comet Lake PCH-LP CNVi WiFi                | 1         | 5%      |
| Intel Cannon Lake PCH CNVi WiFi                  | 1         | 5%      |
| Fibocom L830-EB-00 LTE WWAN Modem                | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 66.67%  |
| Intel                 | 6         | 33.33%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 38.1%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 28.57%  |
| Intel Ethernet Connection (4) I219-V                              | 2         | 9.52%   |
| Intel I210 Gigabit Network Connection                             | 1         | 4.76%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 4.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.76%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 52.94%  |
| Ethernet | 16        | 47.06%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 62.96%  |
| Ethernet | 10        | 37.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 63.16%  |
| 1     | 6         | 31.58%  |
| 3     | 1         | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 89.47%  |
| Yes  | 2         | 10.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Bluetooth Device                   | 6         | 33.33%  |
| Intel AX200 Bluetooth                    | 5         | 27.78%  |
| Intel Wireless-AC 9260 Bluetooth Adapter | 2         | 11.11%  |
| Intel Wireless-AC 3168 Bluetooth         | 2         | 11.11%  |
| Intel AX201 Bluetooth                    | 2         | 11.11%  |
| Intel Bluetooth wireless interface       | 1         | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 46.43%  |
| AMD                   | 6         | 21.43%  |
| Nvidia                | 3         | 10.71%  |
| Trust                 | 1         | 3.57%   |
| Realtek Semiconductor | 1         | 3.57%   |
| Lenovo                | 1         | 3.57%   |
| Kingston Technology   | 1         | 3.57%   |
| Corsair               | 1         | 3.57%   |
| C-Media Electronics   | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                          | 6         | 17.14%  |
| AMD Renoir Radeon High Definition Audio Controller              | 5         | 14.29%  |
| Intel Sunrise Point-LP HD Audio                                 | 3         | 8.57%   |
| Intel Cannon Point-LP High Definition Audio Controller          | 3         | 8.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller | 2         | 5.71%   |
| Trust USB microphone                                            | 1         | 2.86%   |
| Realtek Semiconductor USB Audio                                 | 1         | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                 | 1         | 2.86%   |
| Nvidia GA104 High Definition Audio Controller                   | 1         | 2.86%   |
| Nvidia Audio device                                             | 1         | 2.86%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                    | 1         | 2.86%   |
| Kingston Technology HyperX 7.1 Audio                            | 1         | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller         | 1         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller     | 1         | 2.86%   |
| Intel Comet Lake PCH-LP cAVS                                    | 1         | 2.86%   |
| Intel CM238 HD Audio Controller                                 | 1         | 2.86%   |
| Intel Cannon Lake PCH cAVS                                      | 1         | 2.86%   |
| Intel Broadwell-U Audio Controller                              | 1         | 2.86%   |
| Corsair HS70 Pro Wireless Gaming Headset                        | 1         | 2.86%   |
| C-Media Electronics USB Advanced Audio Device                   | 1         | 2.86%   |
| AMD Navi 10 HDMI Audio                                          | 1         | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 42.11%  |
| Micron Technology   | 4         | 21.05%  |
| Kingston            | 2         | 10.53%  |
| GOODRAM             | 1         | 5.26%   |
| G.Skill             | 1         | 5.26%   |
| Crucial             | 1         | 5.26%   |
| Avant               | 1         | 5.26%   |
| AMD                 | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 9.09%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s               | 1         | 4.55%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s        | 1         | 4.55%   |
| Samsung RAM M471A2K43BB1-CPB 16GB Chip DDR4 2133MT/s          | 1         | 4.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 4.55%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 4.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 4.55%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 4.55%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 4.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s       | 1         | 4.55%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s        | 1         | 4.55%   |
| Kingston RAM ACR16D3LS1KBGR/8G 8192MB SODIMM DDR3 1600MT/s    | 1         | 4.55%   |
| Kingston RAM 9905744-035.A00G 16GB SODIMM DDR4 3200MT/s       | 1         | 4.55%   |
| GOODRAM RAM GR2400S464L17S/8G 8GB SODIMM DDR4 2400MT/s        | 1         | 4.55%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s        | 1         | 4.55%   |
| Crucial RAM CT16G4SFD824A.C16FBD 16GB SODIMM DDR4 2667MT/s    | 1         | 4.55%   |
| Avant RAM J642GU42J2320NQ 16384MB SODIMM DDR4 3200MT/s        | 1         | 4.55%   |
| AMD RAM R9432G3206S2S 32GB SODIMM DDR4 3200MT/s               | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 13        | 76.47%  |
| DDR3   | 2         | 11.76%  |
| LPDDR4 | 1         | 5.88%   |
| LPDDR3 | 1         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 15        | 83.33%  |
| Row Of Chips | 2         | 11.11%  |
| Chip         | 1         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 16384 | 9         | 47.37%  |
| 8192  | 7         | 36.84%  |
| 32768 | 2         | 10.53%  |
| 4096  | 1         | 5.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 6         | 35.29%  |
| 2667  | 5         | 29.41%  |
| 2133  | 2         | 11.76%  |
| 1600  | 2         | 11.76%  |
| 4267  | 1         | 5.88%   |
| 2400  | 1         | 5.88%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 6         | 35.29%  |
| Acer                          | 3         | 17.65%  |
| Microdia                      | 2         | 11.76%  |
| IMC Networks                  | 2         | 11.76%  |
| Sunplus Innovation Technology | 1         | 5.88%   |
| Quanta                        | 1         | 5.88%   |
| Logitech                      | 1         | 5.88%   |
| Lite-On Technology            | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Chicony Integrated Camera         | 4         | 22.22%  |
| Sunplus Integrated_Webcam_FHD     | 1         | 5.56%   |
| Quanta HD WebCam                  | 1         | 5.56%   |
| Microdia USB 2.0 Camera           | 1         | 5.56%   |
| Microdia Integrated_Webcam_HD     | 1         | 5.56%   |
| Logitech Webcam C310              | 1         | 5.56%   |
| Lite-On HP HD Camera              | 1         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam | 1         | 5.56%   |
| IMC Networks Integrated Camera    | 1         | 5.56%   |
| Chicony USB2.0 Camera             | 1         | 5.56%   |
| Chicony HP HD Camera              | 1         | 5.56%   |
| Acer SunplusIT Integrated Camera  | 1         | 5.56%   |
| Acer Integrated IR Camera         | 1         | 5.56%   |
| Acer Integrated Camera            | 1         | 5.56%   |
| Acer HD Webcam                    | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 60%     |
| Validity Sensors           | 1         | 20%     |
| Shenzhen Goodix Technology | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 40%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader                | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 4         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8         | 42.11%  |
| 0     | 7         | 36.84%  |
| 2     | 3         | 15.79%  |
| 4     | 1         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 27.78%  |
| Fingerprint reader    | 4         | 22.22%  |
| Multimedia controller | 3         | 16.67%  |
| Chipcard              | 3         | 16.67%  |
| Network               | 1         | 5.56%   |
| Net/wireless          | 1         | 5.56%   |
| Camera                | 1         | 5.56%   |

