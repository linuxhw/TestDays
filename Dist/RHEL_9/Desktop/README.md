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

Total: 51

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [fba3144c06](https://linux-hardware.org/?probe=fba3144c06) | May 06, 2024 |
| MSI           | MEG Z790 ACE MAX            | [b10bbe2874](https://linux-hardware.org/?probe=b10bbe2874) | Apr 22, 2024 |
| Dell          | 07WP95 A02                  | [46e0a9d4d4](https://linux-hardware.org/?probe=46e0a9d4d4) | Apr 15, 2024 |
| CX / Air C... | CX-H87-M1                   | [6ca85693a6](https://linux-hardware.org/?probe=6ca85693a6) | Apr 12, 2024 |
| ASUSTek       | G16CH                       | [04a245fffe](https://linux-hardware.org/?probe=04a245fffe) | Apr 11, 2024 |
| ASRock        | X570 Creator                | [53aae5d4cb](https://linux-hardware.org/?probe=53aae5d4cb) | Apr 07, 2024 |
| ASRock        | X399 Taichi                 | [c57b1d4302](https://linux-hardware.org/?probe=c57b1d4302) | Apr 04, 2024 |
| ASRock        | X399 Taichi                 | [0f04c10bfa](https://linux-hardware.org/?probe=0f04c10bfa) | Apr 02, 2024 |
| HP            | 212A                        | [4a6e30808e](https://linux-hardware.org/?probe=4a6e30808e) | Mar 12, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [23c12f49f6](https://linux-hardware.org/?probe=23c12f49f6) | Jan 27, 2024 |
| Intel         | DQ77MK AAG39642-400         | [6d4d5ee6c7](https://linux-hardware.org/?probe=6d4d5ee6c7) | Jan 25, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | [cb116dae9c](https://linux-hardware.org/?probe=cb116dae9c) | Jan 20, 2024 |
| MSI           | PRO Z690-A DDR4             | [55f164e414](https://linux-hardware.org/?probe=55f164e414) | Dec 20, 2023 |
| MSI           | PRO Z690-A DDR4             | [b758a439b8](https://linux-hardware.org/?probe=b758a439b8) | Dec 20, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [c492be4899](https://linux-hardware.org/?probe=c492be4899) | Dec 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME Z690-A                | [e356c02979](https://linux-hardware.org/?probe=e356c02979) | Oct 30, 2023 |
| HP            | ProLiant ML310e Gen8        | [79f6aee2c7](https://linux-hardware.org/?probe=79f6aee2c7) | Oct 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| ASRock        | A320M-HDV R4.0              | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| ASRock        | A320M-HDV R4.0              | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| HP            | 0AECh D                     | [b9ea790e39](https://linux-hardware.org/?probe=b9ea790e39) | Jul 24, 2023 |
| HP            | 0AECh D                     | [078f0cd045](https://linux-hardware.org/?probe=078f0cd045) | Jul 24, 2023 |
| MSI           | Z270-A PRO                  | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Dell          | 07T4MC A02                  | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell          | 0HHV7N A00                  | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI           | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Gigabyte      | H510M H                     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek       | PRIME Z590-A                | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel    | ODROID-H3                   | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Unknown       | Unknown                     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Acer          | Aspire XC-330               | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Unknown       | Unknown                     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Intel         | H81                         | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown       | Unknown                     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| ASRock        | Z370 Professional Gaming... | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.14.0-362.24.1.el9_3.x86_64 | 7        | 17.95%  |
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 12.82%  |
| 5.14.0-284.11.1.el9_2.x86_64 | 4        | 10.26%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 7.69%   |
| 5.14.0-362.13.1.el9_3.x86_64 | 3        | 7.69%   |
| 5.14.0-284.25.1.el9_2.x86_64 | 3        | 7.69%   |
| 5.14.0-162.22.2.el9_1.x86_64 | 3        | 7.69%   |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 5.13%   |
| 5.14.0-284.30.1.el9_2.x86_64 | 2        | 5.13%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 2        | 5.13%   |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 2.56%   |
| 5.14.0-362.8.1.el9_3.x86_64  | 1        | 2.56%   |
| 5.14.0-362.18.1.el9_3.x86_64 | 1        | 2.56%   |
| 5.14.0-284.18.1.el9_2.x86_64 | 1        | 2.56%   |
| 5.14.0-162.23.1.el9_1.x86_64 | 1        | 2.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 37       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 37       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 37       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 32       | 86.49%  |
| KDE5          | 2        | 5.41%   |
| GNOME Classic | 1        | 2.7%    |
| Cinnamon      | 1        | 2.7%    |
| Unknown       | 1        | 2.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 27       | 72.97%  |
| X11     | 8        | 21.62%  |
| Tty     | 2        | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 54.05%  |
| GDM     | 15       | 40.54%  |
| SDDM    | 2        | 5.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 22       | 59.46%  |
| en_GB | 3        | 8.11%   |
| pt_BR | 2        | 5.41%   |
| en_NZ | 2        | 5.41%   |
| en_IN | 2        | 5.41%   |
| ru_RU | 1        | 2.7%    |
| ja_JP | 1        | 2.7%    |
| es_ES | 1        | 2.7%    |
| es_AR | 1        | 2.7%    |
| en_ZA | 1        | 2.7%    |
| en_CA | 1        | 2.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 31       | 83.78%  |
| BIOS | 6        | 16.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 35       | 94.59%  |
| Ext4 | 2        | 5.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 48.65%  |
| GPT     | 17       | 45.95%  |
| MBR     | 2        | 5.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 78.38%  |
| Yes       | 8        | 21.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 89.19%  |
| Yes       | 4        | 10.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 27.03%  |
| MSI                 | 6        | 16.22%  |
| Gigabyte Technology | 4        | 10.81%  |
| ASRock              | 4        | 10.81%  |
| Dell                | 3        | 8.11%   |
| Unknown             | 3        | 8.11%   |
| Intel               | 2        | 5.41%   |
| Hewlett-Packard     | 2        | 5.41%   |
| Hardkernel          | 1        | 2.7%    |
| CX / Air Computers. | 1        | 2.7%    |
| Acer                | 1        | 2.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 3        | 8.11%   |
| Gigabyte B550M AORUS PRO-P         | 2        | 5.41%   |
| MSI MS-7D86                        | 1        | 2.7%    |
| MSI MS-7D54                        | 1        | 2.7%    |
| MSI MS-7D25                        | 1        | 2.7%    |
| MSI MS-7C95                        | 1        | 2.7%    |
| MSI MS-7B89                        | 1        | 2.7%    |
| MSI MS-7A71                        | 1        | 2.7%    |
| Intel H81                          | 1        | 2.7%    |
| Intel DQ77MK AAG39642-400          | 1        | 2.7%    |
| HP Z800 Workstation                | 1        | 2.7%    |
| HP ProLiant ML310e Gen8            | 1        | 2.7%    |
| Hardkernel ODROID-H3               | 1        | 2.7%    |
| Gigabyte X670E AORUS MASTER        | 1        | 2.7%    |
| Gigabyte H510M H                   | 1        | 2.7%    |
| Dell Precision Tower 5810          | 1        | 2.7%    |
| Dell PowerEdge T30                 | 1        | 2.7%    |
| Dell OptiPlex 3070                 | 1        | 2.7%    |
| CX / Air Computers. H87-M1         | 1        | 2.7%    |
| ASUS TUF Gaming X670E-PLUS WIFI    | 1        | 2.7%    |
| ASUS TUF Gaming X570-PLUS          | 1        | 2.7%    |
| ASUS ROG STRIX Z590-E GAMING WIFI  | 1        | 2.7%    |
| ASUS ROG STRIX Z590-A GAMING WIFI  | 1        | 2.7%    |
| ASUS ROG STRIX G16CH_G16CH         | 1        | 2.7%    |
| ASUS ROG Maximus Z790 HERO         | 1        | 2.7%    |
| ASUS ROG CROSSHAIR VIII DARK HERO  | 1        | 2.7%    |
| ASUS PRIME Z690-P WIFI             | 1        | 2.7%    |
| ASUS PRIME Z690-A                  | 1        | 2.7%    |
| ASUS PRIME Z590-A                  | 1        | 2.7%    |
| ASRock Z370 Professional Gaming i7 | 1        | 2.7%    |
| ASRock X570 Creator                | 1        | 2.7%    |
| ASRock X399 Taichi                 | 1        | 2.7%    |
| ASRock A320M-HDV R4.0              | 1        | 2.7%    |
| Acer Aspire XC-330                 | 1        | 2.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS ROG                   | 5        | 13.51%  |
| ASUS PRIME                 | 3        | 8.11%   |
| Unknown                    | 3        | 8.11%   |
| Gigabyte B550M             | 2        | 5.41%   |
| ASUS TUF                   | 2        | 5.41%   |
| MSI MS-7D86                | 1        | 2.7%    |
| MSI MS-7D54                | 1        | 2.7%    |
| MSI MS-7D25                | 1        | 2.7%    |
| MSI MS-7C95                | 1        | 2.7%    |
| MSI MS-7B89                | 1        | 2.7%    |
| MSI MS-7A71                | 1        | 2.7%    |
| Intel H81                  | 1        | 2.7%    |
| Intel DQ77MK               | 1        | 2.7%    |
| HP Z800                    | 1        | 2.7%    |
| HP ProLiant                | 1        | 2.7%    |
| Hardkernel ODROID-H3       | 1        | 2.7%    |
| Gigabyte X670E             | 1        | 2.7%    |
| Gigabyte H510M             | 1        | 2.7%    |
| Dell Precision             | 1        | 2.7%    |
| Dell PowerEdge             | 1        | 2.7%    |
| Dell OptiPlex              | 1        | 2.7%    |
| CX / Air Computers. H87-M1 | 1        | 2.7%    |
| ASRock Z370                | 1        | 2.7%    |
| ASRock X570                | 1        | 2.7%    |
| ASRock X399                | 1        | 2.7%    |
| ASRock A320M-HDV           | 1        | 2.7%    |
| Acer Aspire                | 1        | 2.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 8        | 21.62%  |
| 2022 | 6        | 16.22%  |
| 2023 | 4        | 10.81%  |
| 2017 | 4        | 10.81%  |
| 2019 | 3        | 8.11%   |
| 2018 | 3        | 8.11%   |
| 2020 | 2        | 5.41%   |
| 2016 | 2        | 5.41%   |
| 2015 | 1        | 2.7%    |
| 2014 | 1        | 2.7%    |
| 2013 | 1        | 2.7%    |
| 2012 | 1        | 2.7%    |
| 2010 | 1        | 2.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 37       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 36       | 97.3%   |
| Enabled  | 1        | 2.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 12       | 32.43%  |
| 8.01-16.0   | 11       | 29.73%  |
| 64.01-256.0 | 5        | 13.51%  |
| 4.01-8.0    | 3        | 8.11%   |
| 3.01-4.0    | 2        | 5.41%   |
| 24.01-32.0  | 2        | 5.41%   |
| 16.01-24.0  | 2        | 5.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 13       | 32.5%   |
| 4.01-8.0  | 9        | 22.5%   |
| 3.01-4.0  | 8        | 20%     |
| 8.01-16.0 | 6        | 15%     |
| 1.01-2.0  | 4        | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 27.03%  |
| 1      | 9        | 24.32%  |
| 3      | 8        | 21.62%  |
| 5      | 3        | 8.11%   |
| 4      | 3        | 8.11%   |
| 14     | 1        | 2.7%    |
| 7      | 1        | 2.7%    |
| 6      | 1        | 2.7%    |
| 0      | 1        | 2.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 78.38%  |
| Yes       | 8        | 21.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 37       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 57.89%  |
| No        | 16       | 42.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 55.26%  |
| No        | 17       | 44.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 14       | 37.84%  |
| India        | 5        | 13.51%  |
| UK           | 3        | 8.11%   |
| Canada       | 3        | 8.11%   |
| Spain        | 2        | 5.41%   |
| New Zealand  | 2        | 5.41%   |
| Brazil       | 2        | 5.41%   |
| Sweden       | 1        | 2.7%    |
| South Africa | 1        | 2.7%    |
| Russia       | 1        | 2.7%    |
| Japan        | 1        | 2.7%    |
| Germany      | 1        | 2.7%    |
| Argentina    | 1        | 2.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Wellington                | 2        | 5.26%   |
| Wildomar                  | 1        | 2.63%   |
| Valencia                  | 1        | 2.63%   |
| Tokyo                     | 1        | 2.63%   |
| Sutton                    | 1        | 2.63%   |
| Stavropol                 | 1        | 2.63%   |
| Sierra Vista              | 1        | 2.63%   |
| Sainte-Marie              | 1        | 2.63%   |
| Rosario                   | 1        | 2.63%   |
| Rio de Janeiro            | 1        | 2.63%   |
| Ribeirao Preto            | 1        | 2.63%   |
| Phoenix                   | 1        | 2.63%   |
| Pforzheim                 | 1        | 2.63%   |
| Oldham                    | 1        | 2.63%   |
| Newham                    | 1        | 2.63%   |
| Minneapolis               | 1        | 2.63%   |
| McKinney                  | 1        | 2.63%   |
| Los Angeles               | 1        | 2.63%   |
| Lansing                   | 1        | 2.63%   |
| L'Hospitalet de Llobregat | 1        | 2.63%   |
| Kochi                     | 1        | 2.63%   |
| Johannesburg              | 1        | 2.63%   |
| Halmstad                  | 1        | 2.63%   |
| Groves                    | 1        | 2.63%   |
| Ghaziabad                 | 1        | 2.63%   |
| Ernakulam                 | 1        | 2.63%   |
| East Peoria               | 1        | 2.63%   |
| Delhi                     | 1        | 2.63%   |
| Crowley                   | 1        | 2.63%   |
| Cliffside Park            | 1        | 2.63%   |
| Cherry Hill               | 1        | 2.63%   |
| Canton                    | 1        | 2.63%   |
| Canning Town              | 1        | 2.63%   |
| Birmingham                | 1        | 2.63%   |
| Bengaluru                 | 1        | 2.63%   |
| Beeton                    | 1        | 2.63%   |
| Alliston                  | 1        | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 13       | 24     | 16.88%  |
| Seagate                   | 12       | 20     | 15.58%  |
| Samsung Electronics       | 12       | 20     | 15.58%  |
| Micron/Crucial Technology | 5        | 7      | 6.49%   |
| Sandisk                   | 4        | 7      | 5.19%   |
| Toshiba                   | 3        | 3      | 3.9%    |
| Kingston                  | 3        | 4      | 3.9%    |
| Intel                     | 3        | 7      | 3.9%    |
| Unknown                   | 2        | 5      | 2.6%    |
| Phison Electronics        | 2        | 3      | 2.6%    |
| Phison                    | 2        | 2      | 2.6%    |
| Crucial                   | 2        | 3      | 2.6%    |
| China                     | 2        | 2      | 2.6%    |
| XUM                       | 1        | 1      | 1.3%    |
| SABRENT                   | 1        | 1      | 1.3%    |
| PNY                       | 1        | 1      | 1.3%    |
| Micron Technology         | 1        | 1      | 1.3%    |
| KingSpec                  | 1        | 1      | 1.3%    |
| KingFast                  | 1        | 1      | 1.3%    |
| Inland                    | 1        | 1      | 1.3%    |
| Hitachi                   | 1        | 1      | 1.3%    |
| HGST                      | 1        | 1      | 1.3%    |
| Gigabyte Technology       | 1        | 1      | 1.3%    |
| Fantom                    | 1        | 1      | 1.3%    |
| ADATA Technology          | 1        | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3        | 3.03%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                | 3        | 3.03%   |
| Samsung SSD 990 PRO 2TB                            | 2        | 2.02%   |
| Phison E16 PCIe4 NVMe Controller 1TB               | 2        | 2.02%   |
| Intel SSD 660P Series 1024GB                       | 2        | 2.02%   |
| XUM HX256GSSDSATA3 256GB                           | 1        | 1.01%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 1        | 1.01%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1        | 1.01%   |
| WDC WD80EFAX-68KNBN0 8TB                           | 1        | 1.01%   |
| WDC WD5000AVDS-63U7B0 500GB                        | 1        | 1.01%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1        | 1.01%   |
| WDC WD50 00LPVX-22V0TT0 500GB                      | 1        | 1.01%   |
| WDC WD40EFZX-68AWUN0 4TB                           | 1        | 1.01%   |
| WDC WD40EFRX-68N32N0 4TB                           | 1        | 1.01%   |
| WDC WD40EFPX-68C6CN0 4TB                           | 1        | 1.01%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1        | 1.01%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1        | 1.01%   |
| WDC WD20EZAZ-00GGJB0 2TB                           | 1        | 1.01%   |
| WDC WD20EARX-008FB0 2TB                            | 1        | 1.01%   |
| WDC WD141KFGX-68FH9N0 14TB                         | 1        | 1.01%   |
| WDC WD140EFGX-68B0GN0 14TB                         | 1        | 1.01%   |
| WDC WD10SPSX-00A6WT0 1TB                           | 1        | 1.01%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1        | 1.01%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1        | 1.01%   |
| WDC WD10EZRX-00A3KB0 1TB                           | 1        | 1.01%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1        | 1.01%   |
| WDC WD100EFAX-68LHPN0 10TB                         | 1        | 1.01%   |
| WDC WD1003FZEX-00MK2A0 1TB                         | 1        | 1.01%   |
| Unknown SD/MMC/MS PRO 128GB                        | 1        | 1.01%   |
| Unknown SD/MMC/M.S.PRO 32GB                        | 1        | 1.01%   |
| Unknown SD/MMC 2GB                                 | 1        | 1.01%   |
| Unknown M.S./M.S.Pro/HG 16GB                       | 1        | 1.01%   |
| Unknown Compact Flash 977MB                        | 1        | 1.01%   |
| Toshiba MK3261GSYN 320GB                           | 1        | 1.01%   |
| Toshiba DT01ACA200 2TB                             | 1        | 1.01%   |
| Toshiba DT01ACA100 1TB                             | 1        | 1.01%   |
| Seagate ST9250315AS 250GB                          | 1        | 1.01%   |
| Seagate ST8000DM004-2U9188 8TB                     | 1        | 1.01%   |
| Seagate ST6000DM003-2CY186 6TB                     | 1        | 1.01%   |
| Seagate ST4000DM004-2CV104 4TB                     | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 12       | 22     | 37.5%   |
| Seagate | 12       | 20     | 37.5%   |
| Toshiba | 3        | 3      | 9.38%   |
| Unknown | 1        | 1      | 3.13%   |
| SABRENT | 1        | 1      | 3.13%   |
| Hitachi | 1        | 1      | 3.13%   |
| HGST    | 1        | 1      | 3.13%   |
| Fantom  | 1        | 1      | 3.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 23.81%  |
| Kingston            | 3        | 4      | 14.29%  |
| SanDisk             | 2        | 2      | 9.52%   |
| Crucial             | 2        | 2      | 9.52%   |
| China               | 2        | 2      | 9.52%   |
| XUM                 | 1        | 1      | 4.76%   |
| WDC                 | 1        | 1      | 4.76%   |
| PNY                 | 1        | 1      | 4.76%   |
| KingSpec            | 1        | 1      | 4.76%   |
| Intel               | 1        | 2      | 4.76%   |
| Inland              | 1        | 1      | 4.76%   |
| Gigabyte Technology | 1        | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 25       | 40     | 36.76%  |
| HDD     | 22       | 50     | 32.35%  |
| SSD     | 19       | 24     | 27.94%  |
| Unknown | 2        | 5      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 69     | 49.15%  |
| NVMe | 25       | 40     | 42.37%  |
| SAS  | 5        | 10     | 8.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 26     | 36.73%  |
| 0.51-1.0   | 12       | 14     | 24.49%  |
| 1.01-2.0   | 8        | 10     | 16.33%  |
| 3.01-4.0   | 4        | 12     | 8.16%   |
| 4.01-10.0  | 3        | 5      | 6.12%   |
| 2.01-3.0   | 2        | 3      | 4.08%   |
| 10.01-20.0 | 2        | 4      | 4.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 10       | 26.32%  |
| 101-250        | 10       | 26.32%  |
| More than 3000 | 6        | 15.79%  |
| 1001-2000      | 5        | 13.16%  |
| 501-1000       | 4        | 10.53%  |
| 2001-3000      | 2        | 5.26%   |
| 21-50          | 1        | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 12       | 31.58%  |
| 21-50          | 11       | 28.95%  |
| 101-250        | 4        | 10.53%  |
| 51-100         | 4        | 10.53%  |
| 251-500        | 2        | 5.26%   |
| 501-1000       | 2        | 5.26%   |
| More than 3000 | 1        | 2.63%   |
| 2001-3000      | 1        | 2.63%   |
| 1001-2000      | 1        | 2.63%   |

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
| Detected | 22       | 72     | 55%     |
| Works    | 16       | 44     | 40%     |
| Malfunc  | 2        | 3      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 27       | 39.13%  |
| AMD                       | 13       | 18.84%  |
| Samsung Electronics       | 9        | 13.04%  |
| Micron/Crucial Technology | 5        | 7.25%   |
| ASMedia Technology        | 5        | 7.25%   |
| Phison Electronics        | 4        | 5.8%    |
| SanDisk                   | 3        | 4.35%   |
| Micron Technology         | 1        | 1.45%   |
| Broadcom / LSI            | 1        | 1.45%   |
| ADATA Technology          | 1        | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 8.97%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5        | 6.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 3.85%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3        | 3.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 3.85%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3        | 3.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3        | 3.85%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 3.85%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 3.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 3.85%   |
| Intel SSD 660P Series                                                          | 2        | 2.56%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 2.56%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 2.56%   |
| AMD 600 Series Chipset SATA Controller                                         | 2        | 2.56%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.28%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 1.28%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1        | 1.28%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1        | 1.28%   |
| Phison E7 NVMe Controller                                                      | 1        | 1.28%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.28%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 1.28%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 1        | 1.28%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.28%   |
| Intel Optane NVME SSD P1600X Series                                            | 1        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.28%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 1.28%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 1.28%   |
| Intel 6 Series/C200 Series Desktop SATA RAID Controller                        | 1        | 1.28%   |
| Intel 500 Series Chipset Family SATA RAID Controller                           | 1        | 1.28%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 1        | 1.28%   |
| AMD X399 Series Chipset SATA Controller                                        | 1        | 1.28%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 50%     |
| NVMe | 24       | 36.36%  |
| RAID | 8        | 12.12%  |
| SAS  | 1        | 1.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 64.86%  |
| AMD    | 13       | 35.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 2        | 5.41%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 2        | 5.41%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 2        | 5.41%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 5.41%   |
| Intel Xeon CPU X5570 @ 2.93GHz                 | 1        | 2.7%    |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz            | 1        | 2.7%    |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz            | 1        | 2.7%    |
| Intel Pentium Silver N6005 @ 2.00GHz           | 1        | 2.7%    |
| Intel Core i9-14900KS                          | 1        | 2.7%    |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 2.7%    |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 2.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 2.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz               | 1        | 2.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 2.7%    |
| Intel Core i5-3470S CPU @ 2.90GHz              | 1        | 2.7%    |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 2.7%    |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 2.7%    |
| Intel Celeron N5105 @ 2.00GHz                  | 1        | 2.7%    |
| Intel 13th Gen Core i9-13900K                  | 1        | 2.7%    |
| Intel 13th Gen Core i7-13700F                  | 1        | 2.7%    |
| Intel 13th Gen Core i5-13600K                  | 1        | 2.7%    |
| Intel 12th Gen Core i9-12900K                  | 1        | 2.7%    |
| Intel 12th Gen Core i5-12600K                  | 1        | 2.7%    |
| Intel 11th Gen Core i9-11900 @ 2.50GHz         | 1        | 2.7%    |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 2.7%    |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 2.7%    |
| AMD Ryzen 9 7900X 12-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 2.7%    |
| AMD Ryzen 7 7700X 8-Core Processor             | 1        | 2.7%    |
| AMD Athlon X4 950 Quad Core Processor          | 1        | 2.7%    |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G   | 1        | 2.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Other                  | 9        | 24.32%  |
| AMD Ryzen 9            | 5        | 13.51%  |
| Intel Core i7          | 4        | 10.81%  |
| AMD Ryzen 5            | 4        | 10.81%  |
| Intel Xeon             | 3        | 8.11%   |
| Intel Core i5          | 3        | 8.11%   |
| Intel Core i3          | 2        | 5.41%   |
| Intel Pentium Silver   | 1        | 2.7%    |
| Intel Core i9          | 1        | 2.7%    |
| Intel Celeron          | 1        | 2.7%    |
| AMD Ryzen Threadripper | 1        | 2.7%    |
| AMD Ryzen 7            | 1        | 2.7%    |
| AMD Athlon X4          | 1        | 2.7%    |
| AMD A4                 | 1        | 2.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 24.32%  |
| 8      | 7        | 18.92%  |
| 6      | 5        | 13.51%  |
| 16     | 4        | 10.81%  |
| 12     | 4        | 10.81%  |
| 2      | 3        | 8.11%   |
| 24     | 2        | 5.41%   |
| 14     | 1        | 2.7%    |
| 10     | 1        | 2.7%    |
| 1      | 1        | 2.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 36       | 97.3%   |
| 2      | 1        | 2.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 26       | 70.27%  |
| 1      | 11       | 29.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 37       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 21.62%  |
| 0xa0671    | 3        | 8.11%   |
| 0x306a9    | 3        | 8.11%   |
| 0x08701021 | 3        | 8.11%   |
| 0x906c0    | 2        | 5.41%   |
| 0x0a20120a | 2        | 5.41%   |
| 0xb0671    | 1        | 2.7%    |
| 0x906ea    | 1        | 2.7%    |
| 0x906e9    | 1        | 2.7%    |
| 0x90672    | 1        | 2.7%    |
| 0x506e3    | 1        | 2.7%    |
| 0x406f1    | 1        | 2.7%    |
| 0x306c3    | 1        | 2.7%    |
| 0x106a5    | 1        | 2.7%    |
| 0x0a601206 | 1        | 2.7%    |
| 0x0a601203 | 1        | 2.7%    |
| 0x0a50000f | 1        | 2.7%    |
| 0x0a50000c | 1        | 2.7%    |
| 0x0a20102b | 1        | 2.7%    |
| 0x08001138 | 1        | 2.7%    |
| 0x06006705 | 1        | 2.7%    |
| 0x0600611a | 1        | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Alderlake Hybrid | 6        | 16.22%  |
| Zen 3            | 5        | 13.51%  |
| IvyBridge        | 4        | 10.81%  |
| Icelake          | 4        | 10.81%  |
| Zen 2            | 3        | 8.11%   |
| KabyLake         | 3        | 8.11%   |
| Tremont          | 2        | 5.41%   |
| Haswell          | 2        | 5.41%   |
| Excavator        | 2        | 5.41%   |
| Unknown          | 2        | 5.41%   |
| Zen              | 1        | 2.7%    |
| Skylake          | 1        | 2.7%    |
| Nehalem          | 1        | 2.7%    |
| Broadwell        | 1        | 2.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 16       | 37.21%  |
| Intel                      | 13       | 30.23%  |
| AMD                        | 13       | 30.23%  |
| Matrox Electronics Systems | 1        | 2.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 4        | 8.7%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 3        | 6.52%   |
| Nvidia TU117GL [T400 4GB]                                                 | 2        | 4.35%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 2        | 4.35%   |
| Intel JasperLake [UHD Graphics]                                           | 2        | 4.35%   |
| Intel AlderLake-S GT1                                                     | 2        | 4.35%   |
| AMD Raphael                                                               | 2        | 4.35%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 2        | 4.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 4.35%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 2.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 2.17%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 1        | 2.17%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1        | 2.17%   |
| Nvidia GM206GL [Quadro M2000]                                             | 1        | 2.17%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1        | 2.17%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 2.17%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1        | 2.17%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                            | 1        | 2.17%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 1        | 2.17%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 2.17%   |
| Nvidia G96C [GeForce 9500 GT]                                             | 1        | 2.17%   |
| Nvidia G92 [GeForce 9800 GT]                                              | 1        | 2.17%   |
| Matrox Electronics Systems MGA G200EH                                     | 1        | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 2.17%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 2.17%   |
| Intel HD Graphics P530                                                    | 1        | 2.17%   |
| Intel HD Graphics 630                                                     | 1        | 2.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 2.17%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1        | 2.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 2.17%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 1        | 2.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 1        | 2.17%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 1        | 2.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 13       | 35.14%  |
| 1 x AMD        | 9        | 24.32%  |
| 1 x Intel      | 8        | 21.62%  |
| 2 x AMD        | 2        | 5.41%   |
| 2 x Nvidia     | 1        | 2.7%    |
| 1 x Matrox     | 1        | 2.7%    |
| Intel + Nvidia | 1        | 2.7%    |
| Intel + AMD    | 1        | 2.7%    |
| AMD + Nvidia   | 1        | 2.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 31       | 83.78%  |
| Proprietary | 4        | 10.81%  |
| Unknown     | 2        | 5.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 27.03%  |
| 7.01-8.0   | 7        | 18.92%  |
| 3.01-4.0   | 6        | 16.22%  |
| 8.01-16.0  | 4        | 10.81%  |
| 1.01-2.0   | 3        | 8.11%   |
| 0.01-0.5   | 3        | 8.11%   |
| 16.01-24.0 | 2        | 5.41%   |
| 0.51-1.0   | 2        | 5.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 9        | 23.68%  |
| Samsung Electronics | 7        | 18.42%  |
| Acer                | 6        | 15.79%  |
| Philips             | 2        | 5.26%   |
| Goldstar            | 2        | 5.26%   |
| Unknown             | 2        | 5.26%   |
| Vizio               | 1        | 2.63%   |
| STD                 | 1        | 2.63%   |
| Sony                | 1        | 2.63%   |
| Panasonic           | 1        | 2.63%   |
| OUT                 | 1        | 2.63%   |
| Haier               | 1        | 2.63%   |
| Gigabyte Technology | 1        | 2.63%   |
| Deco Gear           | 1        | 2.63%   |
| BenQ                | 1        | 2.63%   |
| AOC                 | 1        | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                      | 2        | 4.88%   |
| Unknown                                                                 | 2        | 4.88%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1        | 2.44%   |
| STD HDMI STD0110 1440x900 420x240mm 19.0-inch                           | 1        | 2.44%   |
| Sony TV SNYD703 1360x768                                                | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch    | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch    | 1        | 2.44%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch    | 1        | 2.44%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch    | 1        | 2.44%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch       | 1        | 2.44%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 950x540mm 43.0-inch   | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1        | 2.44%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch  | 1        | 2.44%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                 | 1        | 2.44%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 2.44%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 1        | 2.44%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                         | 1        | 2.44%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                 | 1        | 2.44%   |
| Goldstar webOS TV GSM0307 1360x768                                      | 1        | 2.44%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                   | 1        | 2.44%   |
| Gigabyte Technology AORUS FI27Q-P GBT2707 2560x1440 596x335mm 26.9-inch | 1        | 2.44%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                       | 1        | 2.44%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 1        | 2.44%   |
| Dell ST2321L DELF033 1920x1080 509x286mm 23.0-inch                      | 1        | 2.44%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                      | 1        | 2.44%   |
| Dell S2340M DELD05A 1920x1080 510x290mm 23.1-inch                       | 1        | 2.44%   |
| Dell S2318HN/NX DELD0BF 1920x1080 509x286mm 23.0-inch                   | 1        | 2.44%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                        | 1        | 2.44%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                       | 1        | 2.44%   |
| Dell E2418HN DELA105 1920x1080 527x296mm 23.8-inch                      | 1        | 2.44%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                       | 1        | 2.44%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch               | 1        | 2.44%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                       | 1        | 2.44%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                     | 1        | 2.44%   |
| Acer SA241Y ACR0923 1920x1080 527x296mm 23.8-inch                       | 1        | 2.44%   |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                       | 1        | 2.44%   |
| Acer KA242Y A ACR078F 1920x1080 517x323mm 24.0-inch                     | 1        | 2.44%   |
| Acer ED270U P2 ACR0B3A 2560x1440 597x336mm 27.0-inch                    | 1        | 2.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 50%     |
| 3840x2160 (4K)     | 6        | 16.67%  |
| 2560x1440 (QHD)    | 3        | 8.33%   |
| 1680x1050 (WSXGA+) | 2        | 5.56%   |
| 1280x1024 (SXGA)   | 2        | 5.56%   |
| 3440x1440          | 1        | 2.78%   |
| 1920x1200 (WUXGA)  | 1        | 2.78%   |
| 1600x900 (HD+)     | 1        | 2.78%   |
| 1360x768           | 1        | 2.78%   |
| 1280x768           | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6        | 15.79%  |
| 24      | 5        | 13.16%  |
| 27      | 4        | 10.53%  |
| 21      | 4        | 10.53%  |
| Unknown | 3        | 7.89%   |
| 84      | 2        | 5.26%   |
| 31      | 2        | 5.26%   |
| 72      | 1        | 2.63%   |
| 64      | 1        | 2.63%   |
| 54      | 1        | 2.63%   |
| 52      | 1        | 2.63%   |
| 43      | 1        | 2.63%   |
| 35      | 1        | 2.63%   |
| 33      | 1        | 2.63%   |
| 26      | 1        | 2.63%   |
| 20      | 1        | 2.63%   |
| 19      | 1        | 2.63%   |
| 17      | 1        | 2.63%   |
| 16      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 40.54%  |
| 401-500     | 5        | 13.51%  |
| 1501-2000   | 3        | 8.11%   |
| 1001-1500   | 3        | 8.11%   |
| Unknown     | 3        | 8.11%   |
| 601-700     | 2        | 5.41%   |
| 301-350     | 2        | 5.41%   |
| 801-900     | 1        | 2.7%    |
| 701-800     | 1        | 2.7%    |
| 351-400     | 1        | 2.7%    |
| 901-1000    | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 73.53%  |
| 16/10   | 3        | 8.82%   |
| 5/4     | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 4/3     | 1        | 2.94%   |
| 21/9    | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 29.73%  |
| More than 1000 | 6        | 16.22%  |
| 301-350        | 5        | 13.51%  |
| 351-500        | 4        | 10.81%  |
| 151-200        | 3        | 8.11%   |
| Unknown        | 3        | 8.11%   |
| 251-300        | 2        | 5.41%   |
| 141-150        | 1        | 2.7%    |
| 131-140        | 1        | 2.7%    |
| 501-1000       | 1        | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 60%     |
| 101-120 | 7        | 20%     |
| 1-50    | 3        | 8.57%   |
| Unknown | 3        | 8.57%   |
| 161-240 | 1        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 70.27%  |
| 2     | 6        | 16.22%  |
| 0     | 4        | 10.81%  |
| 3     | 1        | 2.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 23       | 43.4%   |
| Realtek Semiconductor | 21       | 39.62%  |
| Broadcom              | 3        | 5.66%   |
| Aquantia              | 2        | 3.77%   |
| Mellanox Technologies | 1        | 1.89%   |
| MediaTek              | 1        | 1.89%   |
| Edimax Technology     | 1        | 1.89%   |
| ASUSTek Computer      | 1        | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 9        | 12.5%   |
| Realtek RTL8125 2.5GbE Controller                                              | 8        | 11.11%  |
| Intel Ethernet Controller I225-V                                               | 7        | 9.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 4        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                            | 4        | 5.56%   |
| Intel I211 Gigabit Network Connection                                          | 4        | 5.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 4        | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 4.17%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 4.17%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 2        | 2.78%   |
| Intel Ethernet Controller I226-V                                               | 2        | 2.78%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 2.78%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1        | 1.39%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 1.39%   |
| Realtek 802.11n WLAN Adapter                                                   | 1        | 1.39%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 1.39%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1        | 1.39%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 1        | 1.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 1.39%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 1.39%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 1.39%   |
| Edimax AC1200 MU-MIMO USB3.0 Adapter                                           | 1        | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 1.39%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1        | 1.39%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 1        | 1.39%   |
| Broadcom BCM4321 802.11b/g/n                                                   | 1        | 1.39%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                            | 1        | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 64%     |
| Realtek Semiconductor | 4        | 16%     |
| Broadcom              | 2        | 8%      |
| MediaTek              | 1        | 4%      |
| Edimax Technology     | 1        | 4%      |
| ASUSTek Computer      | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]    | 4        | 16%     |
| Intel Wi-Fi 6 AX200                                          | 4        | 16%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]             | 4        | 16%     |
| Intel Raptor Lake-S PCH CNVi WiFi                            | 2        | 8%      |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller  | 1        | 4%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                   | 1        | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter          | 1        | 4%      |
| Realtek 802.11n WLAN Adapter                                 | 1        | 4%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                      | 1        | 4%      |
| Intel Wi-Fi 6 AX201 160MHz                                   | 1        | 4%      |
| Intel Alder Lake-S PCH CNVi WiFi                             | 1        | 4%      |
| Edimax AC1200 MU-MIMO USB3.0 Adapter                         | 1        | 4%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter | 1        | 4%      |
| Broadcom BCM4321 802.11b/g/n                                 | 1        | 4%      |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]          | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 47.73%  |
| Intel                 | 18       | 40.91%  |
| Broadcom              | 2        | 4.55%   |
| Aquantia              | 2        | 4.55%   |
| Mellanox Technologies | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 9        | 19.15%  |
| Realtek RTL8125 2.5GbE Controller                                              | 8        | 17.02%  |
| Intel Ethernet Controller I225-V                                               | 7        | 14.89%  |
| Intel I211 Gigabit Network Connection                                          | 4        | 8.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 6.38%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 6.38%   |
| Intel Ethernet Controller I226-V                                               | 2        | 4.26%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 2.13%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 2.13%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 1        | 2.13%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 2.13%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 2.13%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 2.13%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1        | 2.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 62.71%  |
| WiFi     | 22       | 37.29%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 86.49%  |
| WiFi     | 5        | 13.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 16       | 42.11%  |
| 1     | 13       | 34.21%  |
| 3     | 5        | 13.16%  |
| 4     | 3        | 7.89%   |
| 5     | 1        | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 60.53%  |
| Yes  | 15       | 39.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 16       | 72.73%  |
| Cambridge Silicon Radio    | 2        | 9.09%   |
| Realtek Semiconductor      | 1        | 4.55%   |
| MediaTek                   | 1        | 4.55%   |
| Integrated System Solution | 1        | 4.55%   |
| Foxconn / Hon Hai          | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                      | 4        | 18.18%  |
| Intel AX210 Bluetooth                                 | 4        | 18.18%  |
| Intel AX200 Bluetooth                                 | 4        | 18.18%  |
| Intel AX201 Bluetooth                                 | 3        | 13.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 9.09%   |
| Realtek Bluetooth Radio                               | 1        | 4.55%   |
| MediaTek Wireless_Device                              | 1        | 4.55%   |
| Intel AX211 Bluetooth                                 | 1        | 4.55%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 4.55%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 23       | 34.85%  |
| AMD                                          | 15       | 22.73%  |
| Nvidia                                       | 14       | 21.21%  |
| ASUSTek Computer                             | 3        | 4.55%   |
| Texas Instruments                            | 2        | 3.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.52%   |
| Valve Software                               | 1        | 1.52%   |
| Unknown                                      | 1        | 1.52%   |
| Micro Star International                     | 1        | 1.52%   |
| Logitech                                     | 1        | 1.52%   |
| Elgato Systems                               | 1        | 1.52%   |
| Creative Labs                                | 1        | 1.52%   |
| Blue Microphones                             | 1        | 1.52%   |
| Astro Gaming                                 | 1        | 1.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 5        | 6.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 4        | 5%      |
| AMD Family 17h/19h HD Audio Controller                                                          | 4        | 5%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 4        | 5%      |
| Intel Raptor Lake High Definition Audio Controller                                              | 3        | 3.75%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 3        | 3.75%   |
| ASUSTek Computer USB Audio                                                                      | 3        | 3.75%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 2        | 2.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 2        | 2.5%    |
| Nvidia GP104 High Definition Audio Controller                                                   | 2        | 2.5%    |
| Nvidia GM206 High Definition Audio Controller                                                   | 2        | 2.5%    |
| Nvidia GA106 High Definition Audio Controller                                                   | 2        | 2.5%    |
| Nvidia AD102 High Definition Audio Controller                                                   | 2        | 2.5%    |
| Intel Jasper Lake HD Audio                                                                      | 2        | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2        | 2.5%    |
| Intel 200 Series PCH HD Audio                                                                   | 2        | 2.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2        | 2.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 2        | 2.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 2.5%    |
| AMD Navi 10 HDMI Audio                                                                          | 2        | 2.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 2        | 2.5%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                  | 1        | 1.25%   |
| Valve Software Valve VR Radio & HMD Mic                                                         | 1        | 1.25%   |
| Unknown Konftel Ego                                                                             | 1        | 1.25%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.25%   |
| Nvidia GP102 HDMI Audio Controller                                                              | 1        | 1.25%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 1        | 1.25%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 1        | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 1        | 1.25%   |
| Micro Star International USB Audio                                                              | 1        | 1.25%   |
| Logitech Headset H340                                                                           | 1        | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                      | 1        | 1.25%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 1        | 1.25%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 1        | 1.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1        | 1.25%   |
| Elgato Systems Elgato Wave:3                                                                    | 1        | 1.25%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 4        | 21.05%  |
| SK hynix            | 3        | 15.79%  |
| Corsair             | 3        | 15.79%  |
| Unknown             | 2        | 10.53%  |
| Crucial             | 2        | 10.53%  |
| Team                | 1        | 5.26%   |
| Samsung Electronics | 1        | 5.26%   |
| Micron Technology   | 1        | 5.26%   |
| Kingston            | 1        | 5.26%   |
| Hewlett-Packard     | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2        | 10.53%  |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 5.26%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s               | 1        | 5.26%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 5.26%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s   | 1        | 5.26%   |
| SK hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s   | 1        | 5.26%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s | 1        | 5.26%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 1        | 5.26%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s    | 1        | 5.26%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s  | 1        | 5.26%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s                | 1        | 5.26%   |
| G.Skill RAM F5-6400J3239F48G 48GB DIMM DDR5 5600MT/s    | 1        | 5.26%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s    | 1        | 5.26%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s  | 1        | 5.26%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 1        | 5.26%   |
| Crucial RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 5.26%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s    | 1        | 5.26%   |
| Corsair RAM CMU32GX4M2A2666C16 16GB DIMM DDR4 2133MT/s  | 1        | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 10       | 58.82%  |
| DDR3   | 4        | 23.53%  |
| DDR5   | 2        | 11.76%  |
| LPDDR4 | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 15       | 88.24%  |
| SODIMM       | 1        | 5.88%   |
| Row Of Chips | 1        | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 8        | 44.44%  |
| 8192  | 7        | 38.89%  |
| 49152 | 1        | 5.56%   |
| 4096  | 1        | 5.56%   |
| 2048  | 1        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 4        | 23.53%  |
| 2667  | 2        | 11.76%  |
| 2400  | 2        | 11.76%  |
| 1600  | 2        | 11.76%  |
| 6400  | 1        | 5.88%   |
| 5600  | 1        | 5.88%   |
| 3866  | 1        | 5.88%   |
| 2933  | 1        | 5.88%   |
| 2133  | 1        | 5.88%   |
| 1867  | 1        | 5.88%   |
| 1333  | 1        | 5.88%   |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Apple                  | 2        | 18.18%  |
| vivo                   | 1        | 9.09%   |
| Valve Software         | 1        | 9.09%   |
| Samsung Electronics    | 1        | 9.09%   |
| Realtek Semiconductor  | 1        | 9.09%   |
| Owon                   | 1        | 9.09%   |
| Microdia               | 1        | 9.09%   |
| Logitech               | 1        | 9.09%   |
| IMC Networks           | 1        | 9.09%   |
| Generalplus Technology | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 2        | 18.18%  |
| vivo V2053                              | 1        | 9.09%   |
| Valve Software 3D Camera                | 1        | 9.09%   |
| Samsung Galaxy series, misc. (MTP mode) | 1        | 9.09%   |
| Realtek FULL HD 1080P Webcam            | 1        | 9.09%   |
| Owon USB CAMERA                         | 1        | 9.09%   |
| Microdia USB 2.0 Camera                 | 1        | 9.09%   |
| Logitech Webcam C250                    | 1        | 9.09%   |
| IMC Networks XHC Camera                 | 1        | 9.09%   |
| Generalplus CAMERA - UVC                | 1        | 9.09%   |

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
| 0     | 29       | 76.32%  |
| 1     | 7        | 18.42%  |
| 2     | 2        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                | Desktops | Percent |
|---------------------|----------|---------|
| Net/wireless        | 5        | 50%     |
| Graphics card       | 2        | 20%     |
| Unassigned class    | 1        | 10%     |
| Firewire controller | 1        | 10%     |
| Bluetooth           | 1        | 10%     |

