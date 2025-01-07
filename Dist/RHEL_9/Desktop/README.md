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

Total: 69

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X570 Steel Legend           | [2b29fc224e](https://linux-hardware.org/?probe=2b29fc224e) | Jan 04, 2025 |
| MSI           | MPG B550 GAMING PLUS        | [8c9e4bdd75](https://linux-hardware.org/?probe=8c9e4bdd75) | Dec 26, 2024 |
| ASRock        | X570 Steel Legend           | [eab49b95cc](https://linux-hardware.org/?probe=eab49b95cc) | Dec 24, 2024 |
| Dell          | 0HHV7N A00                  | [36a5d324c6](https://linux-hardware.org/?probe=36a5d324c6) | Nov 20, 2024 |
| Dell          | 0HHV7N A00                  | [2724eb028f](https://linux-hardware.org/?probe=2724eb028f) | Nov 20, 2024 |
| ASRock        | X570 Steel Legend           | [5b8dc636f4](https://linux-hardware.org/?probe=5b8dc636f4) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [087f372f3b](https://linux-hardware.org/?probe=087f372f3b) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [28e20675ef](https://linux-hardware.org/?probe=28e20675ef) | Nov 16, 2024 |
| ASRock        | H310CM-HG4                  | [947520025d](https://linux-hardware.org/?probe=947520025d) | Nov 12, 2024 |
| ASRock        | H310CM-HG4                  | [11021e8d32](https://linux-hardware.org/?probe=11021e8d32) | Nov 12, 2024 |
| ASRock        | H310CM-HG4                  | [63b0d341db](https://linux-hardware.org/?probe=63b0d341db) | Nov 12, 2024 |
| Dell          | 0HHV7N A00                  | [dac9fa757b](https://linux-hardware.org/?probe=dac9fa757b) | Oct 09, 2024 |
| HP            | 8949 11                     | [e10c4e5057](https://linux-hardware.org/?probe=e10c4e5057) | Oct 02, 2024 |
| MSI           | H310M PRO-VD                | [7a1624219e](https://linux-hardware.org/?probe=7a1624219e) | Sep 07, 2024 |
| ASRock        | B450 Pro4                   | [fe4942ef99](https://linux-hardware.org/?probe=fe4942ef99) | Aug 16, 2024 |
| Supermicro    | X10DRH-CT                   | [dd4b138c6e](https://linux-hardware.org/?probe=dd4b138c6e) | Jun 27, 2024 |
| Dell          | 0MWYPT A01                  | [4e18ec8df0](https://linux-hardware.org/?probe=4e18ec8df0) | May 15, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | [c5ad34b5f5](https://linux-hardware.org/?probe=c5ad34b5f5) | May 14, 2024 |
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


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.14.0-362.24.1.el9_3.x86_64    | 7        | 14.29%  |
| 5.14.0-162.6.1.el9_1.x86_64     | 5        | 10.2%   |
| 5.14.0-362.13.1.el9_3.x86_64    | 4        | 8.16%   |
| 5.14.0-284.11.1.el9_2.x86_64    | 4        | 8.16%   |
| 5.14.0-70.17.1.el9_0.x86_64     | 3        | 6.12%   |
| 5.14.0-284.25.1.el9_2.x86_64    | 3        | 6.12%   |
| 5.14.0-162.22.2.el9_1.x86_64    | 3        | 6.12%   |
| 5.14.0-70.22.1.el9_0.x86_64     | 2        | 4.08%   |
| 5.14.0-503.14.1.el9_5.x86_64    | 2        | 4.08%   |
| 5.14.0-284.30.1.el9_2.x86_64    | 2        | 4.08%   |
| 5.14.0-162.12.1.el9_1.x86_64    | 2        | 4.08%   |
| 5.14.0-70.5.1.el9_0.x86_64      | 1        | 2.04%   |
| 5.14.0-503.19.1.el9_5.x86_64+rt | 1        | 2.04%   |
| 5.14.0-427.42.1.el9_4.x86_64    | 1        | 2.04%   |
| 5.14.0-427.37.1.el9_4.x86_64    | 1        | 2.04%   |
| 5.14.0-427.31.1.el9_4.x86_64    | 1        | 2.04%   |
| 5.14.0-427.22.1.el9_4.x86_64    | 1        | 2.04%   |
| 5.14.0-427.16.1.el9_4.x86_64    | 1        | 2.04%   |
| 5.14.0-427.13.1.el9_4.x86_64    | 1        | 2.04%   |
| 5.14.0-362.8.1.el9_3.x86_64     | 1        | 2.04%   |
| 5.14.0-362.18.1.el9_3.x86_64    | 1        | 2.04%   |
| 5.14.0-284.18.1.el9_2.x86_64    | 1        | 2.04%   |
| 5.14.0-162.23.1.el9_1.x86_64    | 1        | 2.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 47       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 47       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 47       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 38       | 80.85%  |
| KDE5          | 3        | 6.38%   |
| Unknown       | 2        | 4.26%   |
| X-Cinnamon    | 1        | 2.13%   |
| MATE          | 1        | 2.13%   |
| GNOME Classic | 1        | 2.13%   |
| Cinnamon      | 1        | 2.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 33       | 70.21%  |
| X11     | 10       | 21.28%  |
| Tty     | 3        | 6.38%   |
| Unknown | 1        | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 51.06%  |
| GDM     | 20       | 42.55%  |
| SDDM    | 3        | 6.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 27       | 57.45%  |
| en_GB   | 3        | 6.38%   |
| pt_BR   | 2        | 4.26%   |
| en_NZ   | 2        | 4.26%   |
| en_IN   | 2        | 4.26%   |
| ru_RU   | 1        | 2.13%   |
| pl_PL   | 1        | 2.13%   |
| ja_JP   | 1        | 2.13%   |
| es_ES   | 1        | 2.13%   |
| es_AR   | 1        | 2.13%   |
| en_ZA   | 1        | 2.13%   |
| en_CA   | 1        | 2.13%   |
| en_AU   | 1        | 2.13%   |
| de_DE   | 1        | 2.13%   |
| C       | 1        | 2.13%   |
| Unknown | 1        | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 38       | 80.85%  |
| BIOS | 9        | 19.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 44       | 93.62%  |
| Ext4 | 3        | 6.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 24       | 51.06%  |
| Unknown | 21       | 44.68%  |
| MBR     | 2        | 4.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 80.85%  |
| Yes       | 9        | 19.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 87.23%  |
| Yes       | 6        | 12.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 23.4%   |
| MSI                 | 8        | 17.02%  |
| ASRock              | 7        | 14.89%  |
| Dell                | 5        | 10.64%  |
| Gigabyte Technology | 4        | 8.51%   |
| Hewlett-Packard     | 3        | 6.38%   |
| Unknown             | 3        | 6.38%   |
| Intel               | 2        | 4.26%   |
| Supermicro          | 1        | 2.13%   |
| Hardkernel          | 1        | 2.13%   |
| CX / Air Computers. | 1        | 2.13%   |
| Acer                | 1        | 2.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 3        | 6.38%   |
| Gigabyte B550M AORUS PRO-P              | 2        | 4.26%   |
| Dell Precision Tower 5810               | 2        | 4.26%   |
| Supermicro SSG-6028R-E1CR12T            | 1        | 2.13%   |
| MSI MS-7D86                             | 1        | 2.13%   |
| MSI MS-7D54                             | 1        | 2.13%   |
| MSI MS-7D52                             | 1        | 2.13%   |
| MSI MS-7D25                             | 1        | 2.13%   |
| MSI MS-7C95                             | 1        | 2.13%   |
| MSI MS-7C56                             | 1        | 2.13%   |
| MSI MS-7B89                             | 1        | 2.13%   |
| MSI MS-7A71                             | 1        | 2.13%   |
| Intel H81                               | 1        | 2.13%   |
| Intel DQ77MK AAG39642-400               | 1        | 2.13%   |
| HP Z800 Workstation                     | 1        | 2.13%   |
| HP ProLiant ML310e Gen8                 | 1        | 2.13%   |
| HP OMEN by 40L Gaming Desktop GT21-0xxx | 1        | 2.13%   |
| Hardkernel ODROID-H3                    | 1        | 2.13%   |
| Gigabyte X670E AORUS MASTER             | 1        | 2.13%   |
| Gigabyte H510M H                        | 1        | 2.13%   |
| Dell Precision Tower 3620               | 1        | 2.13%   |
| Dell PowerEdge T30                      | 1        | 2.13%   |
| Dell OptiPlex 3070                      | 1        | 2.13%   |
| CX / Air Computers. H87-M1              | 1        | 2.13%   |
| ASUS TUF Gaming X670E-PLUS WIFI         | 1        | 2.13%   |
| ASUS TUF Gaming X570-PLUS               | 1        | 2.13%   |
| ASUS ROG STRIX Z590-E GAMING WIFI       | 1        | 2.13%   |
| ASUS ROG STRIX Z590-A GAMING WIFI       | 1        | 2.13%   |
| ASUS ROG STRIX G16CH_G16CH              | 1        | 2.13%   |
| ASUS ROG STRIX B550-E GAMING            | 1        | 2.13%   |
| ASUS ROG Maximus Z790 HERO              | 1        | 2.13%   |
| ASUS ROG CROSSHAIR VIII DARK HERO       | 1        | 2.13%   |
| ASUS PRIME Z690-P WIFI                  | 1        | 2.13%   |
| ASUS PRIME Z690-A                       | 1        | 2.13%   |
| ASUS PRIME Z590-A                       | 1        | 2.13%   |
| ASRock Z370 Professional Gaming i7      | 1        | 2.13%   |
| ASRock X570 Steel Legend                | 1        | 2.13%   |
| ASRock X570 Creator                     | 1        | 2.13%   |
| ASRock X399 Taichi                      | 1        | 2.13%   |
| ASRock H310CM-HG4                       | 1        | 2.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS ROG                     | 6        | 12.77%  |
| Dell Precision               | 3        | 6.38%   |
| ASUS PRIME                   | 3        | 6.38%   |
| Unknown                      | 3        | 6.38%   |
| Gigabyte B550M               | 2        | 4.26%   |
| ASUS TUF                     | 2        | 4.26%   |
| ASRock X570                  | 2        | 4.26%   |
| Supermicro SSG-6028R-E1CR12T | 1        | 2.13%   |
| MSI MS-7D86                  | 1        | 2.13%   |
| MSI MS-7D54                  | 1        | 2.13%   |
| MSI MS-7D52                  | 1        | 2.13%   |
| MSI MS-7D25                  | 1        | 2.13%   |
| MSI MS-7C95                  | 1        | 2.13%   |
| MSI MS-7C56                  | 1        | 2.13%   |
| MSI MS-7B89                  | 1        | 2.13%   |
| MSI MS-7A71                  | 1        | 2.13%   |
| Intel H81                    | 1        | 2.13%   |
| Intel DQ77MK                 | 1        | 2.13%   |
| HP Z800                      | 1        | 2.13%   |
| HP ProLiant                  | 1        | 2.13%   |
| HP OMEN                      | 1        | 2.13%   |
| Hardkernel ODROID-H3         | 1        | 2.13%   |
| Gigabyte X670E               | 1        | 2.13%   |
| Gigabyte H510M               | 1        | 2.13%   |
| Dell PowerEdge               | 1        | 2.13%   |
| Dell OptiPlex                | 1        | 2.13%   |
| CX / Air Computers. H87-M1   | 1        | 2.13%   |
| ASRock Z370                  | 1        | 2.13%   |
| ASRock X399                  | 1        | 2.13%   |
| ASRock H310CM-HG4            | 1        | 2.13%   |
| ASRock G705                  | 1        | 2.13%   |
| ASRock A320M-HDV             | 1        | 2.13%   |
| Acer Aspire                  | 1        | 2.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 11       | 23.4%   |
| 2022 | 6        | 12.77%  |
| 2019 | 5        | 10.64%  |
| 2017 | 5        | 10.64%  |
| 2023 | 4        | 8.51%   |
| 2020 | 4        | 8.51%   |
| 2016 | 4        | 8.51%   |
| 2018 | 3        | 6.38%   |
| 2015 | 1        | 2.13%   |
| 2014 | 1        | 2.13%   |
| 2013 | 1        | 2.13%   |
| 2012 | 1        | 2.13%   |
| 2010 | 1        | 2.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 47       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 44       | 93.62%  |
| Enabled  | 3        | 6.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 16       | 34.04%  |
| 8.01-16.0       | 12       | 25.53%  |
| 64.01-256.0     | 9        | 19.15%  |
| 4.01-8.0        | 3        | 6.38%   |
| 3.01-4.0        | 2        | 4.26%   |
| 24.01-32.0      | 2        | 4.26%   |
| 16.01-24.0      | 2        | 4.26%   |
| More than 256.0 | 1        | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 17       | 33.33%  |
| 4.01-8.0  | 13       | 25.49%  |
| 3.01-4.0  | 9        | 17.65%  |
| 8.01-16.0 | 8        | 15.69%  |
| 1.01-2.0  | 4        | 7.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 27.66%  |
| 3      | 11       | 23.4%   |
| 1      | 9        | 19.15%  |
| 5      | 4        | 8.51%   |
| 4      | 4        | 8.51%   |
| 6      | 2        | 4.26%   |
| 15     | 1        | 2.13%   |
| 14     | 1        | 2.13%   |
| 7      | 1        | 2.13%   |
| 0      | 1        | 2.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 74.47%  |
| Yes       | 12       | 25.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 47       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 57.14%  |
| No        | 21       | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 27       | 56.25%  |
| No        | 21       | 43.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 18       | 38.3%   |
| India        | 5        | 10.64%  |
| Brazil       | 4        | 8.51%   |
| UK           | 3        | 6.38%   |
| Canada       | 3        | 6.38%   |
| Spain        | 2        | 4.26%   |
| New Zealand  | 2        | 4.26%   |
| Germany      | 2        | 4.26%   |
| Switzerland  | 1        | 2.13%   |
| Sweden       | 1        | 2.13%   |
| South Africa | 1        | 2.13%   |
| Russia       | 1        | 2.13%   |
| Poland       | 1        | 2.13%   |
| Japan        | 1        | 2.13%   |
| Australia    | 1        | 2.13%   |
| Argentina    | 1        | 2.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| Wellington                | 2        | 4.08%   |
| Wildomar                  | 1        | 2.04%   |
| Valencia                  | 1        | 2.04%   |
| Tokyo                     | 1        | 2.04%   |
| Sutton                    | 1        | 2.04%   |
| Sterling Heights          | 1        | 2.04%   |
| Stavropol                 | 1        | 2.04%   |
| Sierra Vista              | 1        | 2.04%   |
| Sainte-Marie              | 1        | 2.04%   |
| Roseville                 | 1        | 2.04%   |
| Rosario                   | 1        | 2.04%   |
| Rio de Janeiro            | 1        | 2.04%   |
| Ribeirao Preto            | 1        | 2.04%   |
| Poznan                    | 1        | 2.04%   |
| Phoenix                   | 1        | 2.04%   |
| Pforzheim                 | 1        | 2.04%   |
| Oldham                    | 1        | 2.04%   |
| Newham                    | 1        | 2.04%   |
| Minneapolis               | 1        | 2.04%   |
| McKinney                  | 1        | 2.04%   |
| Los Angeles               | 1        | 2.04%   |
| Lansing                   | 1        | 2.04%   |
| L'Hospitalet de Llobregat | 1        | 2.04%   |
| Kochi                     | 1        | 2.04%   |
| Johannesburg              | 1        | 2.04%   |
| Houston                   | 1        | 2.04%   |
| Halmstad                  | 1        | 2.04%   |
| Groves                    | 1        | 2.04%   |
| Ghaziabad                 | 1        | 2.04%   |
| Geneva                    | 1        | 2.04%   |
| Foz do Iguaçu            | 1        | 2.04%   |
| Ernakulam                 | 1        | 2.04%   |
| East Peoria               | 1        | 2.04%   |
| Delhi                     | 1        | 2.04%   |
| Cuiabá                   | 1        | 2.04%   |
| Crowley                   | 1        | 2.04%   |
| Cliffside Park            | 1        | 2.04%   |
| Cherry Hill               | 1        | 2.04%   |
| Canton                    | 1        | 2.04%   |
| Canning Town              | 1        | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 17       | 31     | 16.5%   |
| Seagate                   | 16       | 41     | 15.53%  |
| Samsung Electronics       | 16       | 27     | 15.53%  |
| Sandisk                   | 7        | 11     | 6.8%    |
| Micron/Crucial Technology | 5        | 7      | 4.85%   |
| Toshiba                   | 4        | 5      | 3.88%   |
| Intel                     | 4        | 9      | 3.88%   |
| Phison Electronics        | 3        | 4      | 2.91%   |
| Kingston                  | 3        | 4      | 2.91%   |
| Unknown                   | 2        | 5      | 1.94%   |
| Phison                    | 2        | 2      | 1.94%   |
| HGST                      | 2        | 2      | 1.94%   |
| Crucial                   | 2        | 3      | 1.94%   |
| China                     | 2        | 2      | 1.94%   |
| XUM                       | 1        | 1      | 0.97%   |
| SPCC                      | 1        | 1      | 0.97%   |
| SK hynix                  | 1        | 1      | 0.97%   |
| Silicon Motion            | 1        | 1      | 0.97%   |
| SABRENT                   | 1        | 1      | 0.97%   |
| Realtek                   | 1        | 1      | 0.97%   |
| PNY                       | 1        | 1      | 0.97%   |
| Micron Technology         | 1        | 1      | 0.97%   |
| Lexar                     | 1        | 1      | 0.97%   |
| KingSpec                  | 1        | 1      | 0.97%   |
| KingFast                  | 1        | 1      | 0.97%   |
| Kimtigo                   | 1        | 1      | 0.97%   |
| Inland                    | 1        | 1      | 0.97%   |
| HUSKY                     | 1        | 1      | 0.97%   |
| Hitachi                   | 1        | 1      | 0.97%   |
| Gigabyte Technology       | 1        | 1      | 0.97%   |
| Fantom                    | 1        | 1      | 0.97%   |
| ADATA Technology          | 1        | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung SSD 980 1TB                                  | 3        | 2.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3        | 2.34%   |
| Phison E16 PCIe4 NVMe Controller 1TB                 | 3        | 2.34%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 3        | 2.34%   |
| Samsung SSD 990 PRO 2TB                              | 2        | 1.56%   |
| Intel SSD 660P Series 1024GB                         | 2        | 1.56%   |
| XUM HX256GSSDSATA3 256GB                             | 1        | 0.78%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 1        | 0.78%   |
| WDC WDBA3V5000ANC-WRSN 500GB                         | 1        | 0.78%   |
| WDC WD80EFAX-68KNBN0 8TB                             | 1        | 0.78%   |
| WDC WD5000AVDS-63U7B0 500GB                          | 1        | 0.78%   |
| WDC WD5000AVCS-632DY1 500GB                          | 1        | 0.78%   |
| WDC WD5000AAKX-75U6AA0 500GB                         | 1        | 0.78%   |
| WDC WD50 00LPVX-22V0TT0 500GB                        | 1        | 0.78%   |
| WDC WD40EFZX-68AWUN0 4TB                             | 1        | 0.78%   |
| WDC WD40EFRX-68N32N0 4TB                             | 1        | 0.78%   |
| WDC WD40EFPX-68C6CN0 4TB                             | 1        | 0.78%   |
| WDC WD4005FZBX-00K5WB0 4TB                           | 1        | 0.78%   |
| WDC WD20PURZ-85AKKY0 2TB                             | 1        | 0.78%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 1        | 0.78%   |
| WDC WD20EZRX-00D8PB0 2TB                             | 1        | 0.78%   |
| WDC WD20EZAZ-00GGJB0 2TB                             | 1        | 0.78%   |
| WDC WD20EARX-008FB0 2TB                              | 1        | 0.78%   |
| WDC WD2005FBYZ-01YCBB3 2TB                           | 1        | 0.78%   |
| WDC WD141KFGX-68FH9N0 14TB                           | 1        | 0.78%   |
| WDC WD140EFGX-68B0GN0 14TB                           | 1        | 0.78%   |
| WDC WD10SPSX-00A6WT0 1TB                             | 1        | 0.78%   |
| WDC WD10JPLX-00MBPT0 1TB                             | 1        | 0.78%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 1        | 0.78%   |
| WDC WD10EZRX-00A3KB0 1TB                             | 1        | 0.78%   |
| WDC WD10EZEX-00BBHA0 1TB                             | 1        | 0.78%   |
| WDC WD100EFAX-68LHPN0 10TB                           | 1        | 0.78%   |
| WDC WD1003FZEX-00MK2A0 1TB                           | 1        | 0.78%   |
| Unknown SD/MMC/MS PRO 128GB                          | 1        | 0.78%   |
| Unknown SD/MMC/M.S.PRO 32GB                          | 1        | 0.78%   |
| Unknown SD/MMC 1073GB                                | 1        | 0.78%   |
| Unknown M.S./M.S.Pro/HG 16GB                         | 1        | 0.78%   |
| Unknown Compact Flash 977MB                          | 1        | 0.78%   |
| Toshiba MK3261GSYN 320GB                             | 1        | 0.78%   |
| Toshiba MG06ACA800E 8TB                              | 1        | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 29     | 37.21%  |
| Seagate             | 16       | 41     | 37.21%  |
| Toshiba             | 4        | 5      | 9.3%    |
| HGST                | 2        | 2      | 4.65%   |
| Unknown             | 1        | 1      | 2.33%   |
| Samsung Electronics | 1        | 1      | 2.33%   |
| SABRENT             | 1        | 1      | 2.33%   |
| Hitachi             | 1        | 1      | 2.33%   |
| Fantom              | 1        | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 8      | 18.52%  |
| Kingston            | 3        | 4      | 11.11%  |
| SanDisk             | 2        | 2      | 7.41%   |
| Intel               | 2        | 4      | 7.41%   |
| Crucial             | 2        | 2      | 7.41%   |
| China               | 2        | 2      | 7.41%   |
| XUM                 | 1        | 1      | 3.7%    |
| WDC                 | 1        | 1      | 3.7%    |
| SPCC                | 1        | 1      | 3.7%    |
| SK hynix            | 1        | 1      | 3.7%    |
| PNY                 | 1        | 1      | 3.7%    |
| Lexar               | 1        | 1      | 3.7%    |
| KingSpec            | 1        | 1      | 3.7%    |
| Kimtigo             | 1        | 1      | 3.7%    |
| Inland              | 1        | 1      | 3.7%    |
| HUSKY               | 1        | 1      | 3.7%    |
| Gigabyte Technology | 1        | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| NVMe    | 31       | 51     | 35.23%  |
| HDD     | 30       | 82     | 34.09%  |
| SSD     | 25       | 33     | 28.41%  |
| Unknown | 2        | 5      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 37       | 110    | 50%     |
| NVMe | 31       | 50     | 41.89%  |
| SAS  | 6        | 11     | 8.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 37     | 35.82%  |
| 0.51-1.0   | 15       | 19     | 22.39%  |
| 1.01-2.0   | 11       | 17     | 16.42%  |
| 3.01-4.0   | 5        | 14     | 7.46%   |
| 4.01-10.0  | 5        | 18     | 7.46%   |
| 10.01-20.0 | 4        | 6      | 5.97%   |
| 2.01-3.0   | 3        | 4      | 4.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 12       | 25%     |
| 101-250        | 12       | 25%     |
| More than 3000 | 8        | 16.67%  |
| 1001-2000      | 7        | 14.58%  |
| 501-1000       | 5        | 10.42%  |
| 2001-3000      | 2        | 4.17%   |
| 21-50          | 1        | 2.08%   |
| Unknown        | 1        | 2.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 14       | 29.17%  |
| 21-50          | 11       | 22.92%  |
| 51-100         | 6        | 12.5%   |
| 101-250        | 5        | 10.42%  |
| More than 3000 | 3        | 6.25%   |
| 251-500        | 3        | 6.25%   |
| 501-1000       | 3        | 6.25%   |
| 2001-3000      | 1        | 2.08%   |
| 1001-2000      | 1        | 2.08%   |
| Unknown        | 1        | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                             | Desktops | Drives | Percent |
|---------------------------------------------------|----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB                     | 1        | 1      | 16.67%  |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1        | 1      | 16.67%  |
| Seagate ST14000NM0018-2H4101 14TB                 | 1        | 1      | 16.67%  |
| Seagate ST1000DM010-2EP102 1TB                    | 1        | 1      | 16.67%  |
| Intel SSDSC2BB480G7 480GB                         | 1        | 2      | 16.67%  |
| Crucial CT1000BX500SSD1 1TB                       | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor         | Desktops | Drives | Percent |
|----------------|----------|--------|---------|
| Seagate        | 2        | 2      | 33.33%  |
| WDC            | 1        | 1      | 16.67%  |
| Silicon Motion | 1        | 1      | 16.67%  |
| Intel          | 1        | 2      | 16.67%  |
| Crucial        | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 3      | 40%     |
| HDD  | 2        | 3      | 40%     |
| NVMe | 1        | 1      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 25       | 90     | 46.3%   |
| Works    | 23       | 73     | 42.59%  |
| Malfunc  | 5        | 7      | 9.26%   |
| Failed   | 1        | 1      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 31       | 34.07%  |
| AMD                       | 19       | 20.88%  |
| Samsung Electronics       | 12       | 13.19%  |
| SanDisk                   | 6        | 6.59%   |
| ASMedia Technology        | 6        | 6.59%   |
| Phison Electronics        | 5        | 5.49%   |
| Micron/Crucial Technology | 5        | 5.49%   |
| Broadcom / LSI            | 2        | 2.2%    |
| Silicon Motion            | 1        | 1.1%    |
| Micron Technology         | 1        | 1.1%    |
| LSI Logic / Symbios Logic | 1        | 1.1%    |
| JMicron Technology        | 1        | 1.1%    |
| ADATA Technology          | 1        | 1.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 9.71%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6        | 5.83%   |
| AMD 500 Series Chipset SATA Controller                                         | 6        | 5.83%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4        | 3.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 2.91%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3        | 2.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 2.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 2.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 2.91%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3        | 2.91%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3        | 2.91%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 2.91%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 2.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 2.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.91%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 1.94%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2        | 1.94%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2        | 1.94%   |
| Intel SSD 660P Series                                                          | 2        | 1.94%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.94%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 1.94%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.94%   |
| AMD 600 Series Chipset SATA Controller                                         | 2        | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.94%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.97%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.97%   |
| Phison E7 NVMe Controller                                                      | 1        | 0.97%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.97%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 0.97%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 1        | 0.97%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 1        | 0.97%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 1        | 0.97%   |
| JMicron JMB58x AHCI SATA controller                                            | 1        | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 0.97%   |
| Intel Optane NVME SSD P1600X Series                                            | 1        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 43       | 50.59%  |
| NVMe | 30       | 35.29%  |
| RAID | 9        | 10.59%  |
| SAS  | 2        | 2.35%   |
| SCSI | 1        | 1.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 28       | 59.57%  |
| AMD    | 19       | 40.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 8.51%   |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 6.38%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz        | 2        | 4.26%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 4.26%   |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 4.26%   |
| Intel Xeon CPU X5570 @ 2.93GHz                 | 1        | 2.13%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz            | 1        | 2.13%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz            | 1        | 2.13%   |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz            | 1        | 2.13%   |
| Intel Xeon CPU E3-1240 v5 @ 3.50GHz            | 1        | 2.13%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz            | 1        | 2.13%   |
| Intel Pentium Silver N6005 @ 2.00GHz           | 1        | 2.13%   |
| Intel Core i9-14900KS                          | 1        | 2.13%   |
| Intel Core i7-9700 CPU @ 3.00GHz               | 1        | 2.13%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 2.13%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 1        | 2.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.13%   |
| Intel Core i5-9400F CPU @ 2.90GHz              | 1        | 2.13%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 1        | 2.13%   |
| Intel Core i5-3570 CPU @ 3.40GHz               | 1        | 2.13%   |
| Intel Core i5-3470S CPU @ 2.90GHz              | 1        | 2.13%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 1        | 2.13%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1        | 2.13%   |
| Intel Celeron N5105 @ 2.00GHz                  | 1        | 2.13%   |
| Intel 13th Gen Core i9-13900K                  | 1        | 2.13%   |
| Intel 13th Gen Core i7-13700F                  | 1        | 2.13%   |
| Intel 13th Gen Core i5-13600K                  | 1        | 2.13%   |
| Intel 12th Gen Core i9-12900K                  | 1        | 2.13%   |
| Intel 12th Gen Core i5-12600K                  | 1        | 2.13%   |
| Intel 11th Gen Core i9-11900 @ 2.50GHz         | 1        | 2.13%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz        | 1        | 2.13%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 1        | 2.13%   |
| AMD Ryzen 9 7900X 12-Core Processor            | 1        | 2.13%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 2.13%   |
| AMD Ryzen 7 7700X 8-Core Processor             | 1        | 2.13%   |
| AMD Ryzen 7 5800X3D 8-Core Processor           | 1        | 2.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1        | 2.13%   |
| AMD Athlon X4 950 Quad Core Processor          | 1        | 2.13%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G   | 1        | 2.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Other                  | 9        | 19.15%  |
| AMD Ryzen 9            | 8        | 17.02%  |
| Intel Xeon             | 6        | 12.77%  |
| AMD Ryzen 5            | 5        | 10.64%  |
| Intel Core i7          | 4        | 8.51%   |
| Intel Core i5          | 4        | 8.51%   |
| AMD Ryzen 7            | 3        | 6.38%   |
| Intel Core i3          | 2        | 4.26%   |
| Intel Pentium Silver   | 1        | 2.13%   |
| Intel Core i9          | 1        | 2.13%   |
| Intel Celeron          | 1        | 2.13%   |
| AMD Ryzen Threadripper | 1        | 2.13%   |
| AMD Athlon X4          | 1        | 2.13%   |
| AMD A4                 | 1        | 2.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 11       | 23.4%   |
| 8      | 9        | 19.15%  |
| 12     | 7        | 14.89%  |
| 6      | 7        | 14.89%  |
| 16     | 5        | 10.64%  |
| 2      | 3        | 6.38%   |
| 24     | 2        | 4.26%   |
| 14     | 1        | 2.13%   |
| 10     | 1        | 2.13%   |
| 1      | 1        | 2.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 95.74%  |
| 2      | 2        | 4.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 34       | 72.34%  |
| 1      | 13       | 27.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 47       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 29.79%  |
| 0xa0671    | 3        | 6.38%   |
| 0x306a9    | 3        | 6.38%   |
| 0x08701021 | 3        | 6.38%   |
| 0x906c0    | 2        | 4.26%   |
| 0x0a50000f | 2        | 4.26%   |
| 0x0a20120a | 2        | 4.26%   |
| 0xb0671    | 1        | 2.13%   |
| 0x906ea    | 1        | 2.13%   |
| 0x906e9    | 1        | 2.13%   |
| 0x90672    | 1        | 2.13%   |
| 0x506e3    | 1        | 2.13%   |
| 0x406f1    | 1        | 2.13%   |
| 0x306c3    | 1        | 2.13%   |
| 0x106a5    | 1        | 2.13%   |
| 0x0a601206 | 1        | 2.13%   |
| 0x0a601203 | 1        | 2.13%   |
| 0x0a50000c | 1        | 2.13%   |
| 0x0a201204 | 1        | 2.13%   |
| 0x0a20102b | 1        | 2.13%   |
| 0x08701030 | 1        | 2.13%   |
| 0x0800820d | 1        | 2.13%   |
| 0x08001138 | 1        | 2.13%   |
| 0x06006705 | 1        | 2.13%   |
| 0x0600611a | 1        | 2.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 9        | 19.15%  |
| Alderlake Hybrid | 6        | 12.77%  |
| Zen 2            | 4        | 8.51%   |
| KabyLake         | 4        | 8.51%   |
| IvyBridge        | 4        | 8.51%   |
| Icelake          | 4        | 8.51%   |
| Broadwell        | 3        | 6.38%   |
| Tremont          | 2        | 4.26%   |
| Skylake          | 2        | 4.26%   |
| Haswell          | 2        | 4.26%   |
| Excavator        | 2        | 4.26%   |
| Unknown          | 2        | 4.26%   |
| Zen+             | 1        | 2.13%   |
| Zen              | 1        | 2.13%   |
| Nehalem          | 1        | 2.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 23       | 42.59%  |
| AMD                        | 16       | 29.63%  |
| Intel                      | 13       | 24.07%  |
| Matrox Electronics Systems | 1        | 1.85%   |
| ASPEED Technology          | 1        | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 4        | 7.02%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 3        | 5.26%   |
| Nvidia TU117GL [T400 4GB / T400E]                                         | 2        | 3.51%   |
| Nvidia AD102 [GeForce RTX 4090]                                           | 2        | 3.51%   |
| Intel JasperLake [UHD Graphics]                                           | 2        | 3.51%   |
| Intel AlderLake-S GT1                                                     | 2        | 3.51%   |
| AMD Raphael                                                               | 2        | 3.51%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 2        | 3.51%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 2        | 3.51%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 3.51%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 1.75%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                     | 1        | 1.75%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 1.75%   |
| Nvidia GP107GL [Quadro P400]                                              | 1        | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 1        | 1.75%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1        | 1.75%   |
| Nvidia GM206GL [Quadro M2000]                                             | 1        | 1.75%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1        | 1.75%   |
| Nvidia GM107GL [Quadro K620]                                              | 1        | 1.75%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 1.75%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1        | 1.75%   |
| Nvidia GF119 [NVS 315]                                                    | 1        | 1.75%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                            | 1        | 1.75%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 1        | 1.75%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                            | 1        | 1.75%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                         | 1        | 1.75%   |
| Nvidia GA102 [GeForce RTX 3090 Ti]                                        | 1        | 1.75%   |
| Nvidia G96C [GeForce 9500 GT]                                             | 1        | 1.75%   |
| Nvidia G92 [GeForce 9800 GT]                                              | 1        | 1.75%   |
| Matrox Electronics Systems MGA G200EH                                     | 1        | 1.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 1.75%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 1.75%   |
| Intel HD Graphics P530                                                    | 1        | 1.75%   |
| Intel HD Graphics 630                                                     | 1        | 1.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 1.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 1.75%   |
| ASPEED Technology ASPEED Graphics Family                                  | 1        | 1.75%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                  | 1        | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 19       | 40.43%  |
| 1 x AMD         | 12       | 25.53%  |
| 1 x Intel       | 8        | 17.02%  |
| 2 x AMD         | 2        | 4.26%   |
| 2 x Nvidia      | 1        | 2.13%   |
| Nvidia + ASPEED | 1        | 2.13%   |
| 1 x Matrox      | 1        | 2.13%   |
| Intel + Nvidia  | 1        | 2.13%   |
| Intel + AMD     | 1        | 2.13%   |
| AMD + Nvidia    | 1        | 2.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 37       | 78.72%  |
| Proprietary | 8        | 17.02%  |
| Unknown     | 2        | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 25.53%  |
| 7.01-8.0   | 11       | 23.4%   |
| 3.01-4.0   | 6        | 12.77%  |
| 8.01-16.0  | 5        | 10.64%  |
| 1.01-2.0   | 4        | 8.51%   |
| 16.01-24.0 | 3        | 6.38%   |
| 0.51-1.0   | 3        | 6.38%   |
| 0.01-0.5   | 3        | 6.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 11       | 22.45%  |
| Dell                | 11       | 22.45%  |
| Acer                | 7        | 14.29%  |
| Goldstar            | 4        | 8.16%   |
| Philips             | 2        | 4.08%   |
| Unknown             | 2        | 4.08%   |
| Vizio               | 1        | 2.04%   |
| STD                 | 1        | 2.04%   |
| Sony                | 1        | 2.04%   |
| Panasonic           | 1        | 2.04%   |
| OUT                 | 1        | 2.04%   |
| Iiyama              | 1        | 2.04%   |
| Hewlett-Packard     | 1        | 2.04%   |
| Haier               | 1        | 2.04%   |
| Gigabyte Technology | 1        | 2.04%   |
| Deco Gear           | 1        | 2.04%   |
| BenQ                | 1        | 2.04%   |
| AOC                 | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                | 2        | 3.85%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                      | 2        | 3.85%   |
| Unknown                                                                 | 2        | 3.85%   |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                     | 1        | 1.92%   |
| STD VGA STD0110 1600x900 440x230mm 19.5-inch                            | 1        | 1.92%   |
| Sony TV SNYD703 1360x768                                                | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch    | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM0380 1680x1050 459x296mm 21.5-inch    | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch    | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch    | 1        | 1.92%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch    | 1        | 1.92%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch    | 1        | 1.92%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch       | 1        | 1.92%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1        | 1.92%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch       | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 700x390mm 31.5-inch   | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1110x620mm 50.1-inch  | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1050x590mm 47.4-inch  | 1        | 1.92%   |
| Philips PHL 322E1 PHLC20F 1920x1080 700x390mm 31.5-inch                 | 1        | 1.92%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1        | 1.92%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                      | 1        | 1.92%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                         | 1        | 1.92%   |
| Iiyama PL3480WQ IVM7634 3440x1440 797x334mm 34.0-inch                   | 1        | 1.92%   |
| Hewlett-Packard OMEN 27qs HPN3968 2560x1440 597x336mm 27.0-inch         | 1        | 1.92%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                 | 1        | 1.92%   |
| Goldstar webOS TV GSM0307 1360x768                                      | 1        | 1.92%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                   | 1        | 1.92%   |
| Gigabyte Technology AORUS FI27Q-P GBT2707 2560x1440 596x335mm 26.9-inch | 1        | 1.92%   |
| Dell U3014 DEL4081 2560x1600 640x400mm 29.7-inch                        | 1        | 1.92%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                       | 1        | 1.92%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 1        | 1.92%   |
| Dell ST2321L DELF033 1920x1080 509x286mm 23.0-inch                      | 1        | 1.92%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                      | 1        | 1.92%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                      | 1        | 1.92%   |
| Dell S2340M DELD05A 1920x1080 510x290mm 23.1-inch                       | 1        | 1.92%   |
| Dell S2318HN/NX DELD0BF 1920x1080 509x286mm 23.0-inch                   | 1        | 1.92%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                        | 1        | 1.92%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                       | 1        | 1.92%   |
| Dell E2418HN DELA105 1920x1080 530x300mm 24.0-inch                      | 1        | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 40.43%  |
| 3840x2160 (4K)     | 8        | 17.02%  |
| 2560x1440 (QHD)    | 5        | 10.64%  |
| 1680x1050 (WSXGA+) | 3        | 6.38%   |
| 1280x1024 (SXGA)   | 3        | 6.38%   |
| 3440x1440          | 2        | 4.26%   |
| 2560x1080          | 2        | 4.26%   |
| 2560x1600          | 1        | 2.13%   |
| 1920x1200 (WUXGA)  | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1360x768           | 1        | 2.13%   |
| 1280x768           | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 6        | 12.24%  |
| 24      | 6        | 12.24%  |
| 23      | 6        | 12.24%  |
| 21      | 5        | 10.2%   |
| 34      | 3        | 6.12%   |
| Unknown | 3        | 6.12%   |
| 84      | 2        | 4.08%   |
| 43      | 2        | 4.08%   |
| 31      | 2        | 4.08%   |
| 17      | 2        | 4.08%   |
| 72      | 1        | 2.04%   |
| 64      | 1        | 2.04%   |
| 54      | 1        | 2.04%   |
| 52      | 1        | 2.04%   |
| 35      | 1        | 2.04%   |
| 33      | 1        | 2.04%   |
| 29      | 1        | 2.04%   |
| 28      | 1        | 2.04%   |
| 26      | 1        | 2.04%   |
| 20      | 1        | 2.04%   |
| 19      | 1        | 2.04%   |
| 16      | 1        | 2.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 37.5%   |
| 401-500     | 6        | 12.5%   |
| 701-800     | 4        | 8.33%   |
| 601-700     | 4        | 8.33%   |
| 301-350     | 3        | 6.25%   |
| 1501-2000   | 3        | 6.25%   |
| 1001-1500   | 3        | 6.25%   |
| Unknown     | 3        | 6.25%   |
| 901-1000    | 2        | 4.17%   |
| 801-900     | 1        | 2.08%   |
| 351-400     | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 65.91%  |
| 16/10   | 5        | 11.36%  |
| 21/9    | 4        | 9.09%   |
| 5/4     | 3        | 6.82%   |
| Unknown | 2        | 4.55%   |
| 4/3     | 1        | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 27.08%  |
| 351-500        | 9        | 18.75%  |
| 301-350        | 7        | 14.58%  |
| More than 1000 | 6        | 12.5%   |
| 151-200        | 3        | 6.25%   |
| Unknown        | 3        | 6.25%   |
| 251-300        | 2        | 4.17%   |
| 141-150        | 2        | 4.17%   |
| 501-1000       | 2        | 4.17%   |
| 131-140        | 1        | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 26       | 56.52%  |
| 101-120 | 12       | 26.09%  |
| 1-50    | 3        | 6.52%   |
| Unknown | 3        | 6.52%   |
| 161-240 | 1        | 2.17%   |
| 121-160 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 72.34%  |
| 2     | 8        | 17.02%  |
| 0     | 4        | 8.51%   |
| 3     | 1        | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 30       | 44.78%  |
| Realtek Semiconductor | 26       | 38.81%  |
| Broadcom              | 3        | 4.48%   |
| Edimax Technology     | 2        | 2.99%   |
| Aquantia              | 2        | 2.99%   |
| Mellanox Technologies | 1        | 1.49%   |
| MediaTek              | 1        | 1.49%   |
| ASUSTek Computer      | 1        | 1.49%   |
| AMD                   | 1        | 1.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 13       | 14.44%  |
| Realtek RTL8125 2.5GbE Controller                                              | 9        | 10%     |
| Intel Ethernet Controller I225-V                                               | 8        | 8.89%   |
| Intel Wi-Fi 6 AX200                                                            | 6        | 6.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 5        | 5.56%   |
| Intel I211 Gigabit Network Connection                                          | 5        | 5.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 5        | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 3.33%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 3.33%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 2        | 2.22%   |
| Intel Ethernet Controller I226-V                                               | 2        | 2.22%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2        | 2.22%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 2.22%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1        | 1.11%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 1        | 1.11%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 1        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1        | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 1.11%   |
| Realtek 802.11n WLAN Adapter                                                   | 1        | 1.11%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 1        | 1.11%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                | 1        | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 1        | 1.11%   |
| Intel I210 Gigabit Network Connection                                          | 1        | 1.11%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 1        | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 1.11%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                 | 1        | 1.11%   |
| Edimax AC1200 MU-MIMO USB3.0 Adapter                                           | 1        | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 1.11%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1        | 1.11%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 1        | 1.11%   |
| Broadcom BCM4321 802.11b/g/n                                                   | 1        | 1.11%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]                            | 1        | 1.11%   |
| AMD 79C97x [PCnet32 LANCE]                                                     | 1        | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 64.52%  |
| Realtek Semiconductor | 5        | 16.13%  |
| Edimax Technology     | 2        | 6.45%   |
| Broadcom              | 2        | 6.45%   |
| MediaTek              | 1        | 3.23%   |
| ASUSTek Computer      | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6        | 19.35%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 5        | 16.13%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5        | 16.13%  |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 2        | 6.45%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller    | 1        | 3.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1        | 3.23%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1        | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 3.23%   |
| Realtek 802.11n WLAN Adapter                                   | 1        | 3.23%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 3.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1        | 3.23%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 1        | 3.23%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 3.23%   |
| Edimax AC1200 MU-MIMO USB3.0 Adapter                           | 1        | 3.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 1        | 3.23%   |
| Broadcom BCM4321 802.11b/g/n                                   | 1        | 3.23%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]            | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 26       | 48.15%  |
| Intel                 | 23       | 42.59%  |
| Broadcom              | 2        | 3.7%    |
| Aquantia              | 2        | 3.7%    |
| Mellanox Technologies | 1        | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 13       | 22.41%  |
| Realtek RTL8125 2.5GbE Controller                                              | 9        | 15.52%  |
| Intel Ethernet Controller I225-V                                               | 8        | 13.79%  |
| Intel I211 Gigabit Network Connection                                          | 5        | 8.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3        | 5.17%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 5.17%   |
| Intel Ethernet Controller I226-V                                               | 2        | 3.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2        | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2        | 3.45%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1        | 1.72%   |
| Mellanox MT27500 Family [ConnectX-3]                                           | 1        | 1.72%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2                | 1        | 1.72%   |
| Intel I210 Gigabit Network Connection                                          | 1        | 1.72%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1        | 1.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1        | 1.72%   |
| Broadcom NetXtreme BCM5717 Gigabit Ethernet PCIe                               | 1        | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 61.84%  |
| WiFi     | 28       | 36.84%  |
| Unknown  | 1        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 41       | 83.67%  |
| WiFi     | 8        | 16.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 24       | 50%     |
| 1     | 15       | 31.25%  |
| 3     | 5        | 10.42%  |
| 4     | 3        | 6.25%   |
| 5     | 1        | 2.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 60%     |
| Yes  | 20       | 40%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 21       | 75%     |
| Realtek Semiconductor      | 2        | 7.14%   |
| Cambridge Silicon Radio    | 2        | 7.14%   |
| MediaTek                   | 1        | 3.57%   |
| Integrated System Solution | 1        | 3.57%   |
| Foxconn / Hon Hai          | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                 | 6        | 21.43%  |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 17.86%  |
| Intel AX210 Bluetooth                                 | 5        | 17.86%  |
| Intel AX201 Bluetooth                                 | 3        | 10.71%  |
| Realtek Bluetooth Radio                               | 2        | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 7.14%   |
| MediaTek Wireless_Device                              | 1        | 3.57%   |
| Intel Bluetooth Device                                | 1        | 3.57%   |
| Intel AX211 Bluetooth                                 | 1        | 3.57%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 3.57%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 26       | 30.59%  |
| Nvidia                                       | 21       | 24.71%  |
| AMD                                          | 21       | 24.71%  |
| ASUSTek Computer                             | 3        | 3.53%   |
| Texas Instruments                            | 2        | 2.35%   |
| Micro Star International                     | 2        | 2.35%   |
| Logitech                                     | 2        | 2.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.18%   |
| Valve Software                               | 1        | 1.18%   |
| Unknown                                      | 1        | 1.18%   |
| Elgato Systems                               | 1        | 1.18%   |
| Creative Labs                                | 1        | 1.18%   |
| C-Media Electronics                          | 1        | 1.18%   |
| Blue Microphones                             | 1        | 1.18%   |
| Astro Gaming                                 | 1        | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 8.82%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 5        | 4.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 3.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 3.92%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3        | 2.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 2.94%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.94%   |
| ASUSTek Computer USB Audio                                                 | 3        | 2.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 2.94%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 2.94%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2        | 1.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 1.96%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 1.96%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 1.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 1.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 1.96%   |
| Nvidia AD102 High Definition Audio Controller                              | 2        | 1.96%   |
| Micro Star International USB Audio                                         | 2        | 1.96%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 1.96%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 1.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2        | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2        | 1.96%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 0.98%   |
| Valve Software Valve VR Radio & HMD Mic                                    | 1        | 0.98%   |
| Unknown Konftel Ego                                                        | 1        | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.98%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 0.98%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 0.98%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.98%   |
| Nvidia GA102 High Definition Audio Controller                              | 1        | 0.98%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 6        | 22.22%  |
| Corsair             | 6        | 22.22%  |
| SK hynix            | 5        | 18.52%  |
| Unknown             | 2        | 7.41%   |
| Samsung Electronics | 2        | 7.41%   |
| Crucial             | 2        | 7.41%   |
| Team                | 1        | 3.7%    |
| Micron Technology   | 1        | 3.7%    |
| Kingston            | 1        | 3.7%    |
| Hewlett-Packard     | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s | 2        | 7.14%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 7.14%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 3.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s              | 1        | 3.57%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s    | 1        | 3.57%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s  | 1        | 3.57%   |
| SK hynix RAM HMA84GR7MFR4N-UH 32GB RIMM DDR4 2400MT/s  | 1        | 3.57%   |
| SK hynix RAM HMA82GU7AFR8N-UH 16GB DIMM DDR4 2400MT/s  | 1        | 3.57%   |
| SK hynix RAM HMA82GU6CJR8N-VK 16GB DIMM DDR4 2667MT/s  | 1        | 3.57%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 3.57%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s    | 1        | 3.57%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s    | 1        | 3.57%   |
| Micron RAM 18ASF2G72AZ-2G6D1 16GB DIMM DDR4 2667MT/s   | 1        | 3.57%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 3.57%   |
| HP RAM 669237-071 2GB DIMM DDR3 1600MT/s               | 1        | 3.57%   |
| G.Skill RAM F5-6400J3239F48G 48GB DIMM DDR5 6400MT/s   | 1        | 3.57%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s   | 1        | 3.57%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s    | 1        | 3.57%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 1        | 3.57%   |
| Crucial RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 3.57%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s   | 1        | 3.57%   |
| Corsair RAM CMW32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s  | 1        | 3.57%   |
| Corsair RAM CMU32GX4M2A2666C16 16GB DIMM DDR4 2133MT/s | 1        | 3.57%   |
| Corsair RAM CMK8GX4M1Z3200C16 8GB DIMM DDR4 3200MT/s   | 1        | 3.57%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3200MT/s   | 1        | 3.57%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 18       | 72%     |
| DDR3   | 4        | 16%     |
| DDR5   | 2        | 8%      |
| LPDDR4 | 1        | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 22       | 88%     |
| SODIMM       | 1        | 4%      |
| Row Of Chips | 1        | 4%      |
| RIMM         | 1        | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 11       | 42.31%  |
| 8192  | 11       | 42.31%  |
| 49152 | 1        | 3.85%   |
| 32768 | 1        | 3.85%   |
| 4096  | 1        | 3.85%   |
| 2048  | 1        | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 5        | 20%     |
| 3600  | 4        | 16%     |
| 2667  | 3        | 12%     |
| 6400  | 2        | 8%      |
| 3866  | 2        | 8%      |
| 1600  | 2        | 8%      |
| 4000  | 1        | 4%      |
| 3534  | 1        | 4%      |
| 3200  | 1        | 4%      |
| 2933  | 1        | 4%      |
| 2133  | 1        | 4%      |
| 1867  | 1        | 4%      |
| 1333  | 1        | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 40%     |
| Kyocera         | 1        | 20%     |
| Hewlett-Packard | 1        | 20%     |
| Canon           | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-4100 Series | 1        | 20%     |
| Seiko Epson WF-3520 Series | 1        | 20%     |
| Kyocera FS-1030D printer   | 1        | 20%     |
| HP DeskJet 3700 series     | 1        | 20%     |
| Canon PIXMA MG2500 Series  | 1        | 20%     |

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
| Samsung Electronics    | 2        | 14.29%  |
| Logitech               | 2        | 14.29%  |
| Apple                  | 2        | 14.29%  |
| vivo                   | 1        | 7.14%   |
| Valve Software         | 1        | 7.14%   |
| Realtek Semiconductor  | 1        | 7.14%   |
| Owon                   | 1        | 7.14%   |
| Microdia               | 1        | 7.14%   |
| IMC Networks           | 1        | 7.14%   |
| Hewlett-Packard        | 1        | 7.14%   |
| Generalplus Technology | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode) | 2        | 14.29%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 2        | 14.29%  |
| vivo 1906                               | 1        | 7.14%   |
| Valve Software 3D Camera                | 1        | 7.14%   |
| Realtek FULL HD 1080P Webcam            | 1        | 7.14%   |
| Owon USB CAMERA                         | 1        | 7.14%   |
| Microdia USB 2.0 Camera                 | 1        | 7.14%   |
| Logitech Webcam C310                    | 1        | 7.14%   |
| Logitech Webcam C250                    | 1        | 7.14%   |
| IMC Networks HD Camera                  | 1        | 7.14%   |
| HP Webcam HD 4310                       | 1        | 7.14%   |
| Generalplus GENERAL WEBCAM              | 1        | 7.14%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Giesecke & Devrient | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Giesecke & Devrient StarSign CUT S | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 37       | 77.08%  |
| 1     | 6        | 12.5%   |
| 2     | 4        | 8.33%   |
| 3     | 1        | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 37.5%   |
| Unassigned class         | 3        | 18.75%  |
| Graphics card            | 3        | 18.75%  |
| Net/ethernet             | 1        | 6.25%   |
| Firewire controller      | 1        | 6.25%   |
| Communication controller | 1        | 6.25%   |
| Bluetooth                | 1        | 6.25%   |

