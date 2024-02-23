RHEL 9 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

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

Total: 42

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | TUF Gaming X670E-PLUS WI... | [23c12f49f6](https://linux-hardware.org/?probe=23c12f49f6) | Jan 27, 2024 |
| Intel      | DQ77MK AAG39642-400         | [6d4d5ee6c7](https://linux-hardware.org/?probe=6d4d5ee6c7) | Jan 25, 2024 |
| Gigabyte   | B550M AORUS PRO-P           | [cb116dae9c](https://linux-hardware.org/?probe=cb116dae9c) | Jan 20, 2024 |
| MSI        | PRO Z690-A DDR4             | [55f164e414](https://linux-hardware.org/?probe=55f164e414) | Dec 20, 2023 |
| MSI        | PRO Z690-A DDR4             | [b758a439b8](https://linux-hardware.org/?probe=b758a439b8) | Dec 20, 2023 |
| ASUSTek    | ROG Maximus Z790 HERO       | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek    | PRIME Z690-A                | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| HP         | ProLiant ML310e Gen8        | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| ASRock     | A320M-HDV R4.0              | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek    | ROG STRIX Z590-E GAMING ... | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASRock     | A320M-HDV R4.0              | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| ASRock     | A320M-HDV R4.0              | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP         | 0AECh D                     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP         | 0AECh D                     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI        | Z270-A PRO                  | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Dell       | 07T4MC A02                  | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell       | 0HHV7N A00                  | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI        | MAG X570S TOMAHAWK MAX W... | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| ASUSTek    | TUF Gaming X570-PLUS        | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| Gigabyte   | B550M AORUS PRO-P           | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| MSI        | B450M MORTAR MAX            | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte   | X670E AORUS MASTER          | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek    | PRIME Z690-P WIFI           | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI        | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek    | PRIME Z690-P WIFI           | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI        | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI        | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Gigabyte   | H510M H                     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek    | PRIME Z590-A                | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel | ODROID-H3                   | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Unknown    | Unknown                     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI        | B550M PRO-VDH WIFI          | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| MSI        | B550M PRO-VDH WIFI          | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Acer       | Aspire XC-330               | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Unknown    | Unknown                     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Intel      | H81                         | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown    | Unknown                     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown    | Unknown                     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| ASRock     | Z370 Professional Gaming... | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 15.63%  |
| 5.14.0-284.11.1.el9_2.x86_64 | 4        | 12.5%   |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 9.38%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3        | 9.38%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3        | 9.38%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3        | 9.38%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 6.25%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 2        | 6.25%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2        | 6.25%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 3.13%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 1        | 3.13%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 1        | 3.13%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1        | 3.13%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 1        | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 30       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 30       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 30       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 26       | 86.67%  |
| KDE5          | 1        | 3.33%   |
| GNOME Classic | 1        | 3.33%   |
| Cinnamon      | 1        | 3.33%   |
| Unknown       | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 21       | 70%     |
| X11     | 8        | 26.67%  |
| Tty     | 1        | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 53.33%  |
| GDM     | 13       | 43.33%  |
| SDDM    | 1        | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 16       | 53.33%  |
| en_GB | 3        | 10%     |
| pt_BR | 2        | 6.67%   |
| en_NZ | 2        | 6.67%   |
| en_IN | 2        | 6.67%   |
| ru_RU | 1        | 3.33%   |
| ja_JP | 1        | 3.33%   |
| es_ES | 1        | 3.33%   |
| en_ZA | 1        | 3.33%   |
| en_CA | 1        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 24       | 80%     |
| BIOS | 6        | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 28       | 93.33%  |
| Ext4 | 2        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 14       | 46.67%  |
| Unknown | 14       | 46.67%  |
| MBR     | 2        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 76.67%  |
| Yes       | 7        | 23.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 90%     |
| Yes       | 3        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 26.67%  |
| MSI                 | 5        | 16.67%  |
| Gigabyte Technology | 4        | 13.33%  |
| Unknown             | 3        | 10%     |
| Intel               | 2        | 6.67%   |
| Hewlett-Packard     | 2        | 6.67%   |
| Dell                | 2        | 6.67%   |
| ASRock              | 2        | 6.67%   |
| Hardkernel          | 1        | 3.33%   |
| Acer                | 1        | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 3        | 10%     |
| Gigabyte B550M AORUS PRO-P         | 2        | 6.67%   |
| MSI MS-7D54                        | 1        | 3.33%   |
| MSI MS-7D25                        | 1        | 3.33%   |
| MSI MS-7C95                        | 1        | 3.33%   |
| MSI MS-7B89                        | 1        | 3.33%   |
| MSI MS-7A71                        | 1        | 3.33%   |
| Intel H81                          | 1        | 3.33%   |
| Intel DQ77MK AAG39642-400          | 1        | 3.33%   |
| HP Z800 Workstation                | 1        | 3.33%   |
| HP ProLiant ML310e Gen8            | 1        | 3.33%   |
| Hardkernel ODROID-H3               | 1        | 3.33%   |
| Gigabyte X670E AORUS MASTER        | 1        | 3.33%   |
| Gigabyte H510M H                   | 1        | 3.33%   |
| Dell Precision Tower 5810          | 1        | 3.33%   |
| Dell PowerEdge T30                 | 1        | 3.33%   |
| ASUS TUF Gaming X670E-PLUS WIFI    | 1        | 3.33%   |
| ASUS TUF Gaming X570-PLUS          | 1        | 3.33%   |
| ASUS ROG STRIX Z590-E GAMING WIFI  | 1        | 3.33%   |
| ASUS ROG Maximus Z790 HERO         | 1        | 3.33%   |
| ASUS ROG CROSSHAIR VIII DARK HERO  | 1        | 3.33%   |
| ASUS PRIME Z690-P WIFI             | 1        | 3.33%   |
| ASUS PRIME Z690-A                  | 1        | 3.33%   |
| ASUS PRIME Z590-A                  | 1        | 3.33%   |
| ASRock Z370 Professional Gaming i7 | 1        | 3.33%   |
| ASRock A320M-HDV R4.0              | 1        | 3.33%   |
| Acer Aspire XC-330                 | 1        | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS ROG             | 3        | 10%     |
| ASUS PRIME           | 3        | 10%     |
| Unknown              | 3        | 10%     |
| Gigabyte B550M       | 2        | 6.67%   |
| ASUS TUF             | 2        | 6.67%   |
| MSI MS-7D54          | 1        | 3.33%   |
| MSI MS-7D25          | 1        | 3.33%   |
| MSI MS-7C95          | 1        | 3.33%   |
| MSI MS-7B89          | 1        | 3.33%   |
| MSI MS-7A71          | 1        | 3.33%   |
| Intel H81            | 1        | 3.33%   |
| Intel DQ77MK         | 1        | 3.33%   |
| HP Z800              | 1        | 3.33%   |
| HP ProLiant          | 1        | 3.33%   |
| Hardkernel ODROID-H3 | 1        | 3.33%   |
| Gigabyte X670E       | 1        | 3.33%   |
| Gigabyte H510M       | 1        | 3.33%   |
| Dell Precision       | 1        | 3.33%   |
| Dell PowerEdge       | 1        | 3.33%   |
| ASRock Z370          | 1        | 3.33%   |
| ASRock A320M-HDV     | 1        | 3.33%   |
| Acer Aspire          | 1        | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 23.33%  |
| 2022 | 5        | 16.67%  |
| 2018 | 3        | 10%     |
| 2017 | 3        | 10%     |
| 2023 | 2        | 6.67%   |
| 2020 | 2        | 6.67%   |
| 2019 | 2        | 6.67%   |
| 2016 | 2        | 6.67%   |
| 2015 | 1        | 3.33%   |
| 2014 | 1        | 3.33%   |
| 2012 | 1        | 3.33%   |
| 2010 | 1        | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 30       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 29       | 96.67%  |
| Enabled  | 1        | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 10       | 33.33%  |
| 8.01-16.0   | 9        | 30%     |
| 4.01-8.0    | 3        | 10%     |
| 64.01-256.0 | 3        | 10%     |
| 3.01-4.0    | 2        | 6.67%   |
| 24.01-32.0  | 2        | 6.67%   |
| 16.01-24.0  | 1        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 12       | 36.36%  |
| 4.01-8.0  | 7        | 21.21%  |
| 3.01-4.0  | 7        | 21.21%  |
| 1.01-2.0  | 4        | 12.12%  |
| 8.01-16.0 | 3        | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 30%     |
| 1      | 8        | 26.67%  |
| 3      | 5        | 16.67%  |
| 5      | 3        | 10%     |
| 4      | 2        | 6.67%   |
| 14     | 1        | 3.33%   |
| 6      | 1        | 3.33%   |
| 0      | 1        | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 76.67%  |
| Yes       | 7        | 23.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 58.06%  |
| No        | 13       | 41.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 51.61%  |
| No        | 15       | 48.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 10       | 33.33%  |
| India        | 4        | 13.33%  |
| UK           | 3        | 10%     |
| Canada       | 3        | 10%     |
| Spain        | 2        | 6.67%   |
| New Zealand  | 2        | 6.67%   |
| Brazil       | 2        | 6.67%   |
| South Africa | 1        | 3.33%   |
| Russia       | 1        | 3.33%   |
| Japan        | 1        | 3.33%   |
| Germany      | 1        | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Wellington                | 2        | 6.45%   |
| Wildomar                  | 1        | 3.23%   |
| Valencia                  | 1        | 3.23%   |
| Tokyo                     | 1        | 3.23%   |
| Sutton                    | 1        | 3.23%   |
| Stavropol                 | 1        | 3.23%   |
| Sierra Vista              | 1        | 3.23%   |
| Sainte-Marie              | 1        | 3.23%   |
| Rio de Janeiro            | 1        | 3.23%   |
| Ribeirao Preto            | 1        | 3.23%   |
| Phoenix                   | 1        | 3.23%   |
| Pforzheim                 | 1        | 3.23%   |
| Oldham                    | 1        | 3.23%   |
| Newham                    | 1        | 3.23%   |
| Lansing                   | 1        | 3.23%   |
| L'Hospitalet de Llobregat | 1        | 3.23%   |
| Kochi                     | 1        | 3.23%   |
| Johannesburg              | 1        | 3.23%   |
| Ghaziabad                 | 1        | 3.23%   |
| Ernakulam                 | 1        | 3.23%   |
| East Peoria               | 1        | 3.23%   |
| Crowley                   | 1        | 3.23%   |
| Cliffside Park            | 1        | 3.23%   |
| Cherry Hill               | 1        | 3.23%   |
| Canton                    | 1        | 3.23%   |
| Canning Town              | 1        | 3.23%   |
| Birmingham                | 1        | 3.23%   |
| Bengaluru                 | 1        | 3.23%   |
| Beeton                    | 1        | 3.23%   |
| Alliston                  | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 11       | 19     | 18.03%  |
| Seagate                   | 10       | 16     | 16.39%  |
| Samsung Electronics       | 10       | 13     | 16.39%  |
| Sandisk                   | 4        | 7      | 6.56%   |
| Unknown                   | 2        | 5      | 3.28%   |
| Phison Electronics        | 2        | 3      | 3.28%   |
| Phison                    | 2        | 2      | 3.28%   |
| Micron/Crucial Technology | 2        | 3      | 3.28%   |
| Kingston                  | 2        | 2      | 3.28%   |
| Intel                     | 2        | 6      | 3.28%   |
| Crucial                   | 2        | 3      | 3.28%   |
| China                     | 2        | 2      | 3.28%   |
| XUM                       | 1        | 1      | 1.64%   |
| Toshiba                   | 1        | 1      | 1.64%   |
| SABRENT                   | 1        | 1      | 1.64%   |
| PNY                       | 1        | 1      | 1.64%   |
| KingSpec                  | 1        | 1      | 1.64%   |
| Hitachi                   | 1        | 1      | 1.64%   |
| HGST                      | 1        | 1      | 1.64%   |
| Gigabyte Technology       | 1        | 1      | 1.64%   |
| Fantom                    | 1        | 1      | 1.64%   |
| ADATA Technology          | 1        | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung SSD 990 PRO 2TB                            | 2        | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2        | 2.53%   |
| Phison E16 PCIe4 NVMe Controller 2TB               | 2        | 2.53%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 2        | 2.53%   |
| Intel SSD 660P Series 1024GB                       | 2        | 2.53%   |
| XUM HX256GSSDSATA3 256GB                           | 1        | 1.27%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 1        | 1.27%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1        | 1.27%   |
| WDC WD80EFAX-68KNBN0 8TB                           | 1        | 1.27%   |
| WDC WD5000AVDS-63U7B0 500GB                        | 1        | 1.27%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1        | 1.27%   |
| WDC WD50 00LPVX-22V0TT0 500GB                      | 1        | 1.27%   |
| WDC WD40EFRX-68N32N0 4TB                           | 1        | 1.27%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1        | 1.27%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1        | 1.27%   |
| WDC WD20EZAZ-00GGJB0 2TB                           | 1        | 1.27%   |
| WDC WD20EARX-008FB0 2TB                            | 1        | 1.27%   |
| WDC WD141KFGX-68FH9N0 14TB                         | 1        | 1.27%   |
| WDC WD140EFGX-68B0GN0 14TB                         | 1        | 1.27%   |
| WDC WD10SPSX-00A6WT0 1TB                           | 1        | 1.27%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1        | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1        | 1.27%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1        | 1.27%   |
| WDC WD100EFAX-68LHPN0 10TB                         | 1        | 1.27%   |
| Unknown SD/MMC/MS PRO 256GB                        | 1        | 1.27%   |
| Unknown SD/MMC/M.S.PRO 32GB                        | 1        | 1.27%   |
| Unknown SD/MMC 2GB                                 | 1        | 1.27%   |
| Unknown M.S./M.S.Pro/HG 16GB                       | 1        | 1.27%   |
| Unknown Compact Flash 977MB                        | 1        | 1.27%   |
| Toshiba MK3261GSYN 320GB                           | 1        | 1.27%   |
| Seagate ST9250315AS 250GB                          | 1        | 1.27%   |
| Seagate ST8000DM004-2U9188 8TB                     | 1        | 1.27%   |
| Seagate ST6000DM003-2CY186 6TB                     | 1        | 1.27%   |
| Seagate ST4000DM004-2CV104 4TB                     | 1        | 1.27%   |
| Seagate ST4000DM000-2AE166 4TB                     | 1        | 1.27%   |
| Seagate ST3500312CS 500GB                          | 1        | 1.27%   |
| Seagate ST31000528AS 1TB                           | 1        | 1.27%   |
| Seagate ST3000VN000-1HJ166 3TB                     | 1        | 1.27%   |
| Seagate ST3000DM008-2DM166 3TB                     | 1        | 1.27%   |
| Seagate ST2000DM001-1ER164 2TB                     | 1        | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 10       | 17     | 40%     |
| Seagate | 10       | 16     | 40%     |
| Unknown | 1        | 1      | 4%      |
| Toshiba | 1        | 1      | 4%      |
| Hitachi | 1        | 1      | 4%      |
| HGST    | 1        | 1      | 4%      |
| Fantom  | 1        | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 21.05%  |
| SanDisk             | 2        | 2      | 10.53%  |
| Kingston            | 2        | 2      | 10.53%  |
| Crucial             | 2        | 2      | 10.53%  |
| China               | 2        | 2      | 10.53%  |
| XUM                 | 1        | 1      | 5.26%   |
| WDC                 | 1        | 1      | 5.26%   |
| SABRENT             | 1        | 1      | 5.26%   |
| PNY                 | 1        | 1      | 5.26%   |
| KingSpec            | 1        | 1      | 5.26%   |
| Intel               | 1        | 2      | 5.26%   |
| Gigabyte Technology | 1        | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 19       | 28     | 35.19%  |
| HDD     | 18       | 38     | 33.33%  |
| SSD     | 16       | 21     | 29.63%  |
| Unknown | 1        | 4      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 55     | 51.06%  |
| NVMe | 19       | 28     | 40.43%  |
| SAS  | 4        | 8      | 8.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 16       | 24     | 41.03%  |
| 0.51-1.0   | 7        | 9      | 17.95%  |
| 1.01-2.0   | 6        | 7      | 15.38%  |
| 3.01-4.0   | 3        | 7      | 7.69%   |
| 4.01-10.0  | 3        | 5      | 7.69%   |
| 2.01-3.0   | 2        | 3      | 5.13%   |
| 10.01-20.0 | 2        | 4      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 32.26%  |
| 101-250        | 9        | 29.03%  |
| 1001-2000      | 5        | 16.13%  |
| More than 3000 | 3        | 9.68%   |
| 501-1000       | 3        | 9.68%   |
| 21-50          | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 12       | 38.71%  |
| 21-50          | 9        | 29.03%  |
| 51-100         | 4        | 12.9%   |
| 251-500        | 2        | 6.45%   |
| 101-250        | 2        | 6.45%   |
| More than 3000 | 1        | 3.23%   |
| 2001-3000      | 1        | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB  | 1        | 1      | 33.33%  |
| Seagate ST1000DM010-2EP102 1TB | 1        | 1      | 33.33%  |
| Crucial CT1000BX500SSD1 1TB    | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| Crucial | 1        | 1      | 33.33%  |

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
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 2      | 50%     |

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
| Detected | 17       | 52     | 53.13%  |
| Works    | 13       | 36     | 40.63%  |
| Malfunc  | 2        | 3      | 6.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 21       | 39.62%  |
| AMD                       | 11       | 20.75%  |
| Samsung Electronics       | 7        | 13.21%  |
| Phison Electronics        | 4        | 7.55%   |
| SanDisk                   | 3        | 5.66%   |
| Micron/Crucial Technology | 3        | 5.66%   |
| ASMedia Technology        | 2        | 3.77%   |
| Broadcom / LSI            | 1        | 1.89%   |
| ADATA Technology          | 1        | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 5        | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3        | 5%      |
| Phison E16 PCIe4 NVMe Controller                                                       | 3        | 5%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                     | 3        | 5%      |
| AMD 500 Series Chipset SATA Controller                                                 | 3        | 5%      |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                            | 2        | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2        | 3.33%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                   | 2        | 3.33%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 2        | 3.33%   |
| Intel SSD 660P Series                                                                  | 2        | 3.33%   |
| Intel SATA Controller [RAID mode]                                                      | 2        | 3.33%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 2        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 2        | 3.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 2        | 3.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2        | 3.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                          | 2        | 3.33%   |
| AMD 600 Series Chipset SATA Controller                                                 | 2        | 3.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1        | 1.67%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 1        | 1.67%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                  | 1        | 1.67%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 1        | 1.67%   |
| Phison E7 NVMe Controller                                                              | 1        | 1.67%   |
| Phison E12 NVMe Controller                                                             | 1        | 1.67%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                   | 1        | 1.67%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1        | 1.67%   |
| Intel Raptor Lake SATA AHCI Controller                                                 | 1        | 1.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                             | 1        | 1.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                       | 1        | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1        | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 1        | 1.67%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                                | 1        | 1.67%   |
| Intel 500 Series Chipset Family SATA RAID Controller                                   | 1        | 1.67%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                                    | 1        | 1.67%   |
| AMD FCH SATA Controller D                                                              | 1        | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                                 | 1        | 1.67%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less) | 1        | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 49.06%  |
| NVMe | 19       | 35.85%  |
| RAID | 7        | 13.21%  |
| SAS  | 1        | 1.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 19       | 63.33%  |
| AMD    | 11       | 36.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel 11th Gen Core i7-11700K @ 3.60GHz      | 2        | 6.67%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 2        | 6.67%   |
| AMD Ryzen 5 3600 6-Core Processor            | 2        | 6.67%   |
| Intel Xeon CPU X5570 @ 2.93GHz               | 1        | 3.33%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz          | 1        | 3.33%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz          | 1        | 3.33%   |
| Intel Pentium Silver N6005 @ 2.00GHz         | 1        | 3.33%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 1        | 3.33%   |
| Intel Core i7-7700K CPU @ 4.20GHz            | 1        | 3.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz             | 1        | 3.33%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 1        | 3.33%   |
| Intel Core i5-3470S CPU @ 2.90GHz            | 1        | 3.33%   |
| Intel Core i3-4130 CPU @ 3.40GHz             | 1        | 3.33%   |
| Intel Core i3-3220 CPU @ 3.30GHz             | 1        | 3.33%   |
| Intel Celeron N5105 @ 2.00GHz                | 1        | 3.33%   |
| Intel 13th Gen Core i9-13900K                | 1        | 3.33%   |
| Intel 13th Gen Core i5-13600K                | 1        | 3.33%   |
| Intel 12th Gen Core i9-12900K                | 1        | 3.33%   |
| Intel 12th Gen Core i5-12600K                | 1        | 3.33%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 1        | 3.33%   |
| AMD Ryzen 9 7900X 12-Core Processor          | 1        | 3.33%   |
| AMD Ryzen 9 5950X 16-Core Processor          | 1        | 3.33%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 3.33%   |
| AMD Ryzen 9 3900X 12-Core Processor          | 1        | 3.33%   |
| AMD Ryzen 7 7700X 8-Core Processor           | 1        | 3.33%   |
| AMD Athlon X4 950 Quad Core Processor        | 1        | 3.33%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Other                | 7        | 23.33%  |
| AMD Ryzen 9          | 4        | 13.33%  |
| AMD Ryzen 5          | 4        | 13.33%  |
| Intel Xeon           | 3        | 10%     |
| Intel Core i7        | 3        | 10%     |
| Intel Core i5        | 2        | 6.67%   |
| Intel Core i3        | 2        | 6.67%   |
| Intel Pentium Silver | 1        | 3.33%   |
| Intel Celeron        | 1        | 3.33%   |
| AMD Ryzen 7          | 1        | 3.33%   |
| AMD Athlon X4        | 1        | 3.33%   |
| AMD A4               | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 26.67%  |
| 8      | 5        | 16.67%  |
| 6      | 5        | 16.67%  |
| 12     | 3        | 10%     |
| 2      | 3        | 10%     |
| 16     | 2        | 6.67%   |
| 24     | 1        | 3.33%   |
| 14     | 1        | 3.33%   |
| 10     | 1        | 3.33%   |
| 1      | 1        | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 29       | 96.67%  |
| 2      | 1        | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 70%     |
| 1      | 9        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 30       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0671    | 3        | 10%     |
| 0x306a9    | 3        | 10%     |
| 0x08701021 | 3        | 10%     |
| Unknown    | 3        | 10%     |
| 0x906c0    | 2        | 6.67%   |
| 0x0a20120a | 2        | 6.67%   |
| 0xb0671    | 1        | 3.33%   |
| 0x906ea    | 1        | 3.33%   |
| 0x906e9    | 1        | 3.33%   |
| 0x90672    | 1        | 3.33%   |
| 0x506e3    | 1        | 3.33%   |
| 0x406f1    | 1        | 3.33%   |
| 0x306c3    | 1        | 3.33%   |
| 0x106a5    | 1        | 3.33%   |
| 0x0a601206 | 1        | 3.33%   |
| 0x0a601203 | 1        | 3.33%   |
| 0x0a50000f | 1        | 3.33%   |
| 0x0a50000c | 1        | 3.33%   |
| 0x06006705 | 1        | 3.33%   |
| 0x0600611a | 1        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 4        | 13.33%  |
| IvyBridge        | 4        | 13.33%  |
| Alderlake Hybrid | 4        | 13.33%  |
| Zen 2            | 3        | 10%     |
| Icelake          | 3        | 10%     |
| Tremont          | 2        | 6.67%   |
| KabyLake         | 2        | 6.67%   |
| Excavator        | 2        | 6.67%   |
| Unknown          | 2        | 6.67%   |
| Skylake          | 1        | 3.33%   |
| Nehalem          | 1        | 3.33%   |
| Haswell          | 1        | 3.33%   |
| Broadwell        | 1        | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 12       | 35.29%  |
| AMD                        | 11       | 32.35%  |
| Intel                      | 10       | 29.41%  |
| Matrox Electronics Systems | 1        | 2.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 8.11%   |
| Nvidia TU117GL [T400 4GB]                                                 | 2        | 5.41%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 2        | 5.41%   |
| Intel JasperLake [UHD Graphics]                                           | 2        | 5.41%   |
| Intel AlderLake-S GT1                                                     | 2        | 5.41%   |
| AMD Raphael                                                               | 2        | 5.41%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 2        | 5.41%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 5.41%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 2.7%    |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 2.7%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 1        | 2.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1        | 2.7%    |
| Nvidia GM206GL [Quadro M2000]                                             | 1        | 2.7%    |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 2.7%    |
| Nvidia GK106 [GeForce GTX 660]                                            | 1        | 2.7%    |
| Nvidia GA106 [Geforce RTX 3050]                                           | 1        | 2.7%    |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 2.7%    |
| Nvidia G92 [GeForce 9800 GT]                                              | 1        | 2.7%    |
| Nvidia AD102 [GeForce RTX 4090]                                           | 1        | 2.7%    |
| Matrox Electronics Systems MGA G200EH                                     | 1        | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 2.7%    |
| Intel HD Graphics P530                                                    | 1        | 2.7%    |
| Intel HD Graphics 630                                                     | 1        | 2.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 2.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 2.7%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 1        | 2.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 1        | 2.7%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 1        | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 10       | 33.33%  |
| 1 x AMD        | 8        | 26.67%  |
| 1 x Intel      | 6        | 20%     |
| 2 x AMD        | 2        | 6.67%   |
| 2 x Nvidia     | 1        | 3.33%   |
| 1 x Matrox     | 1        | 3.33%   |
| Intel + Nvidia | 1        | 3.33%   |
| Intel + AMD    | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 25       | 83.33%  |
| Proprietary | 4        | 13.33%  |
| Unknown     | 1        | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 23.33%  |
| 7.01-8.0   | 6        | 20%     |
| 3.01-4.0   | 5        | 16.67%  |
| 1.01-2.0   | 3        | 10%     |
| 8.01-16.0  | 3        | 10%     |
| 0.01-0.5   | 3        | 10%     |
| 16.01-24.0 | 2        | 6.67%   |
| 0.51-1.0   | 1        | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 7        | 22.58%  |
| Dell                | 6        | 19.35%  |
| Acer                | 4        | 12.9%   |
| Unknown             | 2        | 6.45%   |
| Vizio               | 1        | 3.23%   |
| STD                 | 1        | 3.23%   |
| Sony                | 1        | 3.23%   |
| Philips             | 1        | 3.23%   |
| Panasonic           | 1        | 3.23%   |
| OUT                 | 1        | 3.23%   |
| Haier               | 1        | 3.23%   |
| Goldstar            | 1        | 3.23%   |
| Gigabyte Technology | 1        | 3.23%   |
| Deco Gear           | 1        | 3.23%   |
| BenQ                | 1        | 3.23%   |
| AOC                 | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                      | 2        | 6.06%   |
| Unknown                                                                 | 2        | 6.06%   |
| Vizio E32-C1 VIZ1004 1920x1080 698x392mm 31.5-inch                      | 1        | 3.03%   |
| STD HDMI STD0110 1440x900 420x240mm 19.0-inch                           | 1        | 3.03%   |
| Sony TV SNYD703 1360x768                                                | 1        | 3.03%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch    | 1        | 3.03%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch    | 1        | 3.03%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch    | 1        | 3.03%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch    | 1        | 3.03%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch       | 1        | 3.03%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch       | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1        | 3.03%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch  | 1        | 3.03%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                 | 1        | 3.03%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 1        | 3.03%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                         | 1        | 3.03%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                 | 1        | 3.03%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                   | 1        | 3.03%   |
| Gigabyte Technology AORUS FI27Q-P GBT2707 2560x1440 596x335mm 26.9-inch | 1        | 3.03%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                      | 1        | 3.03%   |
| Dell S2340M DELD05A 1920x1080 509x286mm 23.0-inch                       | 1        | 3.03%   |
| Dell S2318HN/NX DELD0BF 1920x1080 509x286mm 23.0-inch                   | 1        | 3.03%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                        | 1        | 3.03%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                       | 1        | 3.03%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                       | 1        | 3.03%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch               | 1        | 3.03%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                       | 1        | 3.03%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 1        | 3.03%   |
| Acer SA241Y ACR0923 1920x1080 530x300mm 24.0-inch                       | 1        | 3.03%   |
| Acer ED270U P2 ACR0B3A 2560x1440 597x336mm 27.0-inch                    | 1        | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 46.67%  |
| 3840x2160 (4K)     | 6        | 20%     |
| 2560x1440 (QHD)    | 3        | 10%     |
| 1680x1050 (WSXGA+) | 2        | 6.67%   |
| 1280x1024 (SXGA)   | 2        | 6.67%   |
| 3440x1440          | 1        | 3.33%   |
| 1600x900 (HD+)     | 1        | 3.33%   |
| 1280x768           | 1        | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 12.9%   |
| 21      | 4        | 12.9%   |
| 27      | 3        | 9.68%   |
| 84      | 2        | 6.45%   |
| 31      | 2        | 6.45%   |
| 24      | 2        | 6.45%   |
| Unknown | 2        | 6.45%   |
| 72      | 1        | 3.23%   |
| 64      | 1        | 3.23%   |
| 54      | 1        | 3.23%   |
| 52      | 1        | 3.23%   |
| 43      | 1        | 3.23%   |
| 35      | 1        | 3.23%   |
| 33      | 1        | 3.23%   |
| 26      | 1        | 3.23%   |
| 20      | 1        | 3.23%   |
| 19      | 1        | 3.23%   |
| 17      | 1        | 3.23%   |
| 16      | 1        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 32.26%  |
| 401-500     | 5        | 16.13%  |
| 1501-2000   | 3        | 9.68%   |
| 1001-1500   | 3        | 9.68%   |
| 601-700     | 2        | 6.45%   |
| 301-350     | 2        | 6.45%   |
| Unknown     | 2        | 6.45%   |
| 801-900     | 1        | 3.23%   |
| 701-800     | 1        | 3.23%   |
| 351-400     | 1        | 3.23%   |
| 901-1000    | 1        | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 75%     |
| 5/4     | 2        | 7.14%   |
| Unknown | 2        | 7.14%   |
| 4/3     | 1        | 3.57%   |
| 21/9    | 1        | 3.57%   |
| 16/10   | 1        | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 26.67%  |
| More than 1000 | 6        | 20%     |
| 351-500        | 4        | 13.33%  |
| 301-350        | 4        | 13.33%  |
| 151-200        | 3        | 10%     |
| Unknown        | 2        | 6.67%   |
| 141-150        | 1        | 3.33%   |
| 131-140        | 1        | 3.33%   |
| 501-1000       | 1        | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 55.17%  |
| 101-120 | 7        | 24.14%  |
| 1-50    | 3        | 10.34%  |
| Unknown | 2        | 6.9%    |
| 161-240 | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 73.33%  |
| 2     | 4        | 13.33%  |
| 0     | 3        | 10%     |
| 3     | 1        | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 18       | 45%     |
| Realtek Semiconductor | 17       | 42.5%   |
| Broadcom              | 2        | 5%      |
| MediaTek              | 1        | 2.5%    |
| ASUSTek Computer      | 1        | 2.5%    |
| Aquantia              | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8125 2.5GbE Controller                                              | 7        | 12.5%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 7        | 12.5%   |
| Intel Ethernet Controller I225-V                                               | 6        | 10.71%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 4        | 7.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 5.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3        | 5.36%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 5.36%   |
| Intel Wi-Fi 6 AX200                                                            | 2        | 3.57%   |
| Intel I211 Gigabit Network Connection                                          | 2        | 3.57%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1        | 1.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 1.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 1.79%   |
| Realtek 802.11n WLAN Adapter                                                   | 1        | 1.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1        | 1.79%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 1        | 1.79%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 1        | 1.79%   |
| Intel Ethernet Controller I226-V                                               | 1        | 1.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 1.79%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.79%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.79%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 1.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 1.79%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1        | 1.79%   |
| Broadcom BCM4321 802.11b/g/n                                                   | 1        | 1.79%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                            | 1        | 1.79%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 1.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 63.16%  |
| Realtek Semiconductor | 4        | 21.05%  |
| MediaTek              | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |
| ASUSTek Computer      | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]   | 4        | 21.05%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]            | 3        | 15.79%  |
| Intel Wi-Fi 6 AX200                                         | 2        | 10.53%  |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller | 1        | 5.26%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                  | 1        | 5.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter         | 1        | 5.26%   |
| Realtek 802.11n WLAN Adapter                                | 1        | 5.26%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                     | 1        | 5.26%   |
| Intel Wi-Fi 6 AX201 160MHz                                  | 1        | 5.26%   |
| Intel Raptor Lake-S PCH CNVi WiFi                           | 1        | 5.26%   |
| Intel Alder Lake-S PCH CNVi WiFi                            | 1        | 5.26%   |
| Broadcom BCM4321 802.11b/g/n                                | 1        | 5.26%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]         | 1        | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 50%     |
| Intel                 | 14       | 41.18%  |
| Broadcom              | 2        | 5.88%   |
| Aquantia              | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8125 2.5GbE Controller                                              | 7        | 18.92%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 7        | 18.92%  |
| Intel Ethernet Controller I225-V                                               | 6        | 16.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 8.11%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 8.11%   |
| Intel I211 Gigabit Network Connection                                          | 2        | 5.41%   |
| Intel Ethernet Controller I226-V                                               | 1        | 2.7%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 2.7%    |
| Intel Ethernet Connection I217-LM                                              | 1        | 2.7%    |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 2.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 2.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 2.7%    |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1        | 2.7%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 1        | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 62.5%   |
| WiFi     | 18       | 37.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 86.67%  |
| WiFi     | 4        | 13.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 12       | 38.71%  |
| 1     | 12       | 38.71%  |
| 3     | 4        | 12.9%   |
| 4     | 3        | 9.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 64.52%  |
| Yes  | 11       | 35.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 12       | 70.59%  |
| Cambridge Silicon Radio    | 2        | 11.76%  |
| Realtek Semiconductor      | 1        | 5.88%   |
| MediaTek                   | 1        | 5.88%   |
| Integrated System Solution | 1        | 5.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                                 | 4        | 23.53%  |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 17.65%  |
| Intel AX201 Bluetooth                                 | 2        | 11.76%  |
| Intel AX200 Bluetooth                                 | 2        | 11.76%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 11.76%  |
| Realtek Bluetooth Radio                               | 1        | 5.88%   |
| MediaTek Wireless_Device                              | 1        | 5.88%   |
| Intel Bluetooth Device                                | 1        | 5.88%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 5.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 18       | 34.62%  |
| AMD                                          | 13       | 25%     |
| Nvidia                                       | 11       | 21.15%  |
| Texas Instruments                            | 2        | 3.85%   |
| ASUSTek Computer                             | 2        | 3.85%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.92%   |
| Micro Star International                     | 1        | 1.92%   |
| Logitech                                     | 1        | 1.92%   |
| Creative Labs                                | 1        | 1.92%   |
| Blue Microphones                             | 1        | 1.92%   |
| Astro Gaming                                 | 1        | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 4        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 4        | 6.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 3        | 4.69%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 3        | 4.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 3        | 4.69%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 2        | 3.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 2        | 3.13%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 2        | 3.13%   |
| Intel Jasper Lake HD Audio                                                                      | 2        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2        | 3.13%   |
| Intel 200 Series PCH HD Audio                                                                   | 2        | 3.13%   |
| ASUSTek Computer USB Audio                                                                      | 2        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2        | 3.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 2        | 3.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 3.13%   |
| AMD Navi 10 HDMI Audio                                                                          | 2        | 3.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 2        | 3.13%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                  | 1        | 1.56%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.56%   |
| Nvidia GP102 HDMI Audio Controller                                                              | 1        | 1.56%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 1        | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 1        | 1.56%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 1        | 1.56%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 1        | 1.56%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 1        | 1.56%   |
| Nvidia AD102 High Definition Audio Controller                                                   | 1        | 1.56%   |
| Micro Star International USB Audio                                                              | 1        | 1.56%   |
| Logitech Headset H340                                                                           | 1        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.56%   |
| Intel Raptor Lake High Definition Audio Controller                                              | 1        | 1.56%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 1        | 1.56%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 1        | 1.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 1        | 1.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1        | 1.56%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.56%   |
| Blue Microphones Yeti Nano                                                                      | 1        | 1.56%   |
| Astro Gaming Astro MixAmp Pro                                                                   | 1        | 1.56%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 1        | 1.56%   |
| AMD High Definition Audio Controller                                                            | 1        | 1.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 3        | 18.75%  |
| Unknown             | 2        | 12.5%   |
| SK hynix            | 2        | 12.5%   |
| Crucial             | 2        | 12.5%   |
| Corsair             | 2        | 12.5%   |
| Team                | 1        | 6.25%   |
| Samsung Electronics | 1        | 6.25%   |
| Micron Technology   | 1        | 6.25%   |
| Kingston            | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 12.5%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 6.25%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s              | 1        | 6.25%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s    | 1        | 6.25%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s  | 1        | 6.25%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 6.25%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR2 1867MT/s    | 1        | 6.25%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s   | 1        | 6.25%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 6.25%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s               | 1        | 6.25%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s   | 1        | 6.25%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 1        | 6.25%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 1        | 6.25%   |
| Crucial RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 6.25%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s   | 1        | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 8        | 57.14%  |
| DDR3   | 4        | 28.57%  |
| LPDDR4 | 1        | 7.14%   |
| DDR5   | 1        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 12       | 85.71%  |
| SODIMM       | 1        | 7.14%   |
| Row Of Chips | 1        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 46.67%  |
| 16384 | 6        | 40%     |
| 4096  | 1        | 6.67%   |
| 2048  | 1        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 5        | 35.71%  |
| 2400  | 2        | 14.29%  |
| 1600  | 2        | 14.29%  |
| 6400  | 1        | 7.14%   |
| 2933  | 1        | 7.14%   |
| 2667  | 1        | 7.14%   |
| 1867  | 1        | 7.14%   |
| 1333  | 1        | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 50%     |
| Hewlett-Packard | 1        | 25%     |
| Canon           | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-4100 Series | 1        | 25%     |
| Seiko Epson WF-3520 Series | 1        | 25%     |
| HP DeskJet 3700 series     | 1        | 25%     |
| Canon PIXMA MG2500 Series  | 1        | 25%     |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Apple                 | 2        | 25%     |
| vivo                  | 1        | 12.5%   |
| Realtek Semiconductor | 1        | 12.5%   |
| Owon                  | 1        | 12.5%   |
| Microdia              | 1        | 12.5%   |
| Logitech              | 1        | 12.5%   |
| IMC Networks          | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR | 2        | 25%     |
| vivo V2036                         | 1        | 12.5%   |
| Realtek Full HD webcam             | 1        | 12.5%   |
| Owon USB CAMERA                    | 1        | 12.5%   |
| Microdia USB 2.0 Camera            | 1        | 12.5%   |
| Logitech Webcam C250               | 1        | 12.5%   |
| IMC Networks XHC Camera            | 1        | 12.5%   |

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
| 0     | 24       | 77.42%  |
| 1     | 5        | 16.13%  |
| 2     | 2        | 6.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Net/wireless        | 4        | 50%     |
| Unassigned class    | 1        | 12.5%   |
| Graphics card       | 1        | 12.5%   |
| Firewire controller | 1        | 12.5%   |
| Bluetooth           | 1        | 12.5%   |

