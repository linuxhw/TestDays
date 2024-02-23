Elementary 7.1 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.1.

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

Total: 49

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B75M-DGS R2.0               | [cff86cc0d9](https://linux-hardware.org/?probe=cff86cc0d9) | Jan 27, 2024 |
| Dell          | 00V62H A01                  | [83f7e8b344](https://linux-hardware.org/?probe=83f7e8b344) | Jan 24, 2024 |
| Gigabyte      | EP43-UD3L                   | [6a2153a6b9](https://linux-hardware.org/?probe=6a2153a6b9) | Jan 21, 2024 |
| Dell          | 00V62H A01                  | [7104f7e7cf](https://linux-hardware.org/?probe=7104f7e7cf) | Jan 21, 2024 |
| Gigabyte      | B560M DS3H                  | [8ffb8f68ca](https://linux-hardware.org/?probe=8ffb8f68ca) | Jan 19, 2024 |
| Gigabyte      | EP43-UD3L                   | [8dc280e4fc](https://linux-hardware.org/?probe=8dc280e4fc) | Jan 13, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [62374d5cbd](https://linux-hardware.org/?probe=62374d5cbd) | Jan 11, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | [f24b7483b8](https://linux-hardware.org/?probe=f24b7483b8) | Jan 11, 2024 |
| HP            | 3397                        | [3339eb00ce](https://linux-hardware.org/?probe=3339eb00ce) | Jan 03, 2024 |
| HP            | 0AA8h                       | [49435a98d1](https://linux-hardware.org/?probe=49435a98d1) | Dec 19, 2023 |
| HP            | 3397                        | [7b379848f1](https://linux-hardware.org/?probe=7b379848f1) | Dec 16, 2023 |
| HP            | 0AA8h                       | [5264c3d3e1](https://linux-hardware.org/?probe=5264c3d3e1) | Dec 16, 2023 |
| HP            | 0AA8h                       | [e20c0fc21b](https://linux-hardware.org/?probe=e20c0fc21b) | Dec 16, 2023 |
| ECS           | G41T-M                      | [a0017f196c](https://linux-hardware.org/?probe=a0017f196c) | Dec 14, 2023 |
| ASUSTek       | Z97-AR                      | [70936627e8](https://linux-hardware.org/?probe=70936627e8) | Dec 05, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cfc7698579](https://linux-hardware.org/?probe=cfc7698579) | Dec 04, 2023 |
| ASUSTek       | PRIME A320M-K               | [5bbcf82cf2](https://linux-hardware.org/?probe=5bbcf82cf2) | Nov 30, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [541efb8e16](https://linux-hardware.org/?probe=541efb8e16) | Nov 24, 2023 |
| Dell          | 0XPDFK A01                  | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| Gigabyte      | B550M DS3H                  | [8def310709](https://linux-hardware.org/?probe=8def310709) | Nov 16, 2023 |
| Dell          | 03KWTV A00                  | [794f73f426](https://linux-hardware.org/?probe=794f73f426) | Nov 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [5ddcb0cf64](https://linux-hardware.org/?probe=5ddcb0cf64) | Nov 15, 2023 |
| Intel         | DH67BL AAG10189-206         | [334569cac2](https://linux-hardware.org/?probe=334569cac2) | Nov 15, 2023 |
| MSI           | H77MA-G43                   | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| Gigabyte      | B550M DS3H                  | [882de5a591](https://linux-hardware.org/?probe=882de5a591) | Nov 13, 2023 |
| MSI           | H77MA-G43                   | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| HC Technol... | HCAR5000-MI                 | [ab41e88ca3](https://linux-hardware.org/?probe=ab41e88ca3) | Nov 07, 2023 |
| ASUSTek       | PRIME A320M-K               | [99b0c9edcf](https://linux-hardware.org/?probe=99b0c9edcf) | Nov 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | [2cc662a279](https://linux-hardware.org/?probe=2cc662a279) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | [2053de6443](https://linux-hardware.org/?probe=2053de6443) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | [a81d5bbd02](https://linux-hardware.org/?probe=a81d5bbd02) | Nov 03, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [72a5b8f06a](https://linux-hardware.org/?probe=72a5b8f06a) | Nov 02, 2023 |
| Dell          | 0J3C2F A00                  | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b5e0b9a020](https://linux-hardware.org/?probe=b5e0b9a020) | Oct 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [38ed4f25af](https://linux-hardware.org/?probe=38ed4f25af) | Oct 27, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | [b9ec438e43](https://linux-hardware.org/?probe=b9ec438e43) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [3b82b142b1](https://linux-hardware.org/?probe=3b82b142b1) | Oct 26, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | [ffc0782186](https://linux-hardware.org/?probe=ffc0782186) | Oct 23, 2023 |
| Gigabyte      | B560M DS3H                  | [2100dab18e](https://linux-hardware.org/?probe=2100dab18e) | Oct 23, 2023 |
| Acer          | G33T-AM                     | [7b42f4db1d](https://linux-hardware.org/?probe=7b42f4db1d) | Oct 23, 2023 |
| Acer          | G33T-AM                     | [70f67a6f11](https://linux-hardware.org/?probe=70f67a6f11) | Oct 22, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [7ad6760006](https://linux-hardware.org/?probe=7ad6760006) | Oct 19, 2023 |
| MACHINIST     | X79 Z9-D7 V1.2              | [bc7e7d2817](https://linux-hardware.org/?probe=bc7e7d2817) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [47f6f3760d](https://linux-hardware.org/?probe=47f6f3760d) | Oct 17, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | [23c3f61285](https://linux-hardware.org/?probe=23c3f61285) | Oct 14, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [a654820b23](https://linux-hardware.org/?probe=a654820b23) | Oct 13, 2023 |
| Dell          | 0GTK4K A02                  | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | 0GTK4K A02                  | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| ASUSTek       | P5G41T-M LX                 | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 6.2.0-36-generic     | 8        | 24.24%  |
| 6.2.0-35-generic     | 6        | 18.18%  |
| 6.2.0-39-generic     | 5        | 15.15%  |
| 6.2.0-33-generic     | 4        | 12.12%  |
| 6.2.0-34-generic     | 3        | 9.09%   |
| 6.5.0-14-generic     | 2        | 6.06%   |
| 6.2.0-37-generic     | 2        | 6.06%   |
| 6.5.0-15-generic     | 1        | 3.03%   |
| 6.2.0-060200-generic | 1        | 3.03%   |
| 5.19.0-41-generic    | 1        | 3.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 29       | 87.88%  |
| 6.5.0   | 3        | 9.09%   |
| 5.19.0  | 1        | 3.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 29       | 87.88%  |
| 6.5     | 3        | 9.09%   |
| 5.19    | 1        | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 32       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 32       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 32       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 84.38%  |
| LightDM | 5        | 15.63%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 19       | 59.38%  |
| de_DE | 3        | 9.38%   |
| pl_PL | 2        | 6.25%   |
| es_ES | 2        | 6.25%   |
| ru_RU | 1        | 3.13%   |
| pt_PT | 1        | 3.13%   |
| it_IT | 1        | 3.13%   |
| hu_HU | 1        | 3.13%   |
| fr_FR | 1        | 3.13%   |
| en_AU | 1        | 3.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 31       | 96.88%  |
| EFI  | 1        | 3.13%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 31       | 93.94%  |
| Tmpfs | 1        | 3.03%   |
| Btrfs | 1        | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 27       | 84.38%  |
| GPT     | 3        | 9.38%   |
| MBR     | 2        | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 96.88%  |
| Yes       | 1        | 3.13%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 90.63%  |
| Yes       | 3        | 9.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 28.13%  |
| Dell                | 6        | 18.75%  |
| Gigabyte Technology | 3        | 9.38%   |
| MSI                 | 2        | 6.25%   |
| MACHINIST           | 2        | 6.25%   |
| Hewlett-Packard     | 2        | 6.25%   |
| ASRock              | 2        | 6.25%   |
| Lenovo              | 1        | 3.13%   |
| Intel               | 1        | 3.13%   |
| HC Technology.      | 1        | 3.13%   |
| Fujitsu             | 1        | 3.13%   |
| ECS                 | 1        | 3.13%   |
| Acer                | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS PRIME A320M-K                      | 2        | 6.25%   |
| MSI MS-7A63                             | 1        | 3.13%   |
| MSI MS-7756                             | 1        | 3.13%   |
| MACHINIST X79 Z9-D7 V1.2                | 1        | 3.13%   |
| MACHINIST H81M-PRO S1 V2.0              | 1        | 3.13%   |
| Lenovo IdeaCentre 310S-08ASR 90G90073GE | 1        | 3.13%   |
| Intel Nobilis                           | 1        | 3.13%   |
| HP Compaq Elite 8300 SFF                | 1        | 3.13%   |
| HP Compaq dc7800 Small Form Factor      | 1        | 3.13%   |
| HC Technology. HCAR5000-MI              | 1        | 3.13%   |
| Gigabyte EP43-UD3L                      | 1        | 3.13%   |
| Gigabyte B560M DS3H                     | 1        | 3.13%   |
| Gigabyte B550M DS3H                     | 1        | 3.13%   |
| Fujitsu ESPRIMO E720                    | 1        | 3.13%   |
| ECS G41T-M                              | 1        | 3.13%   |
| Dell Precision WorkStation T3500        | 1        | 3.13%   |
| Dell PowerEdge T40                      | 1        | 3.13%   |
| Dell OptiPlex 9020                      | 1        | 3.13%   |
| Dell OptiPlex 790                       | 1        | 3.13%   |
| Dell OptiPlex 5040                      | 1        | 3.13%   |
| Dell OptiPlex 3060                      | 1        | 3.13%   |
| ASUS ROG STRIX X570-E GAMING WIFI II    | 1        | 3.13%   |
| ASUS ROG STRIX B360-F GAMING            | 1        | 3.13%   |
| ASUS P8H61-MX R2.0                      | 1        | 3.13%   |
| ASUS P5G41T-M LX                        | 1        | 3.13%   |
| ASUS P5G41-M LX2/GB                     | 1        | 3.13%   |
| ASUS H110M-A/M.2                        | 1        | 3.13%   |
| ASUS All Series                         | 1        | 3.13%   |
| ASRock Z390 Phantom Gaming-ITX/ac       | 1        | 3.13%   |
| ASRock B75M-DGS R2.0                    | 1        | 3.13%   |
| Acer Aspire M5620                       | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Dell OptiPlex              | 4        | 12.5%   |
| HP Compaq                  | 2        | 6.25%   |
| ASUS ROG                   | 2        | 6.25%   |
| ASUS PRIME                 | 2        | 6.25%   |
| MSI MS-7A63                | 1        | 3.13%   |
| MSI MS-7756                | 1        | 3.13%   |
| MACHINIST X79              | 1        | 3.13%   |
| MACHINIST H81M-PRO         | 1        | 3.13%   |
| Lenovo IdeaCentre          | 1        | 3.13%   |
| Intel Nobilis              | 1        | 3.13%   |
| HC Technology. HCAR5000-MI | 1        | 3.13%   |
| Gigabyte EP43-UD3L         | 1        | 3.13%   |
| Gigabyte B560M             | 1        | 3.13%   |
| Gigabyte B550M             | 1        | 3.13%   |
| Fujitsu ESPRIMO            | 1        | 3.13%   |
| ECS G41T-M                 | 1        | 3.13%   |
| Dell Precision             | 1        | 3.13%   |
| Dell PowerEdge             | 1        | 3.13%   |
| ASUS P8H61-MX              | 1        | 3.13%   |
| ASUS P5G41T-M              | 1        | 3.13%   |
| ASUS P5G41-M               | 1        | 3.13%   |
| ASUS H110M-A               | 1        | 3.13%   |
| ASUS All                   | 1        | 3.13%   |
| ASRock Z390                | 1        | 3.13%   |
| ASRock B75M-DGS            | 1        | 3.13%   |
| Acer Aspire                | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 5        | 15.63%  |
| 2021 | 4        | 12.5%   |
| 2009 | 4        | 12.5%   |
| 2012 | 3        | 9.38%   |
| 2017 | 2        | 6.25%   |
| 2016 | 2        | 6.25%   |
| 2014 | 2        | 6.25%   |
| 2013 | 2        | 6.25%   |
| 2011 | 2        | 6.25%   |
| 2007 | 2        | 6.25%   |
| 2022 | 1        | 3.13%   |
| 2020 | 1        | 3.13%   |
| 2019 | 1        | 3.13%   |
| 2010 | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 96.88%  |
| Enabled  | 1        | 3.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 11       | 33.33%  |
| 4.01-8.0    | 9        | 27.27%  |
| 32.01-64.0  | 5        | 15.15%  |
| 3.01-4.0    | 4        | 12.12%  |
| 24.01-32.0  | 1        | 3.03%   |
| 64.01-256.0 | 1        | 3.03%   |
| 1.01-2.0    | 1        | 3.03%   |
| 8.01-16.0   | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 12       | 34.29%  |
| 1.01-2.0 | 9        | 25.71%  |
| 4.01-8.0 | 7        | 20%     |
| 3.01-4.0 | 6        | 17.14%  |
| 0.51-1.0 | 1        | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 55.88%  |
| 1      | 9        | 26.47%  |
| 3      | 6        | 17.65%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 57.58%  |
| Yes       | 14       | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 32       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 50%     |
| No        | 16       | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 68.75%  |
| Yes       | 10       | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 7        | 21.88%  |
| Russia                 | 3        | 9.38%   |
| UK                     | 2        | 6.25%   |
| Poland                 | 2        | 6.25%   |
| Israel                 | 2        | 6.25%   |
| Germany                | 2        | 6.25%   |
| Canada                 | 2        | 6.25%   |
| Bosnia and Herzegovina | 2        | 6.25%   |
| Argentina              | 2        | 6.25%   |
| Spain                  | 1        | 3.13%   |
| Portugal               | 1        | 3.13%   |
| Morocco                | 1        | 3.13%   |
| Italy                  | 1        | 3.13%   |
| Hungary                | 1        | 3.13%   |
| Belgium                | 1        | 3.13%   |
| Austria                | 1        | 3.13%   |
| Australia              | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Warsaw         | 2        | 6.06%   |
| Sarajevo       | 2        | 6.06%   |
| Petah Tikva    | 2        | 6.06%   |
| Moscow         | 2        | 6.06%   |
| Victoria       | 1        | 3.03%   |
| Van Vleck      | 1        | 3.03%   |
| Ummendorf      | 1        | 3.03%   |
| Toronto        | 1        | 3.03%   |
| Tahitotfalu    | 1        | 3.03%   |
| Rome           | 1        | 3.03%   |
| Resistencia    | 1        | 3.03%   |
| Redding        | 1        | 3.03%   |
| Ponte de Lima  | 1        | 3.03%   |
| Nivelles       | 1        | 3.03%   |
| New Egypt      | 1        | 3.03%   |
| Munich         | 1        | 3.03%   |
| Mikhaylovsk    | 1        | 3.03%   |
| Melbourne      | 1        | 3.03%   |
| Los Angeles    | 1        | 3.03%   |
| London         | 1        | 3.03%   |
| Lanus          | 1        | 3.03%   |
| Jacksonville   | 1        | 3.03%   |
| Greenwich      | 1        | 3.03%   |
| Chinchón      | 1        | 3.03%   |
| Chicago        | 1        | 3.03%   |
| Casablanca     | 1        | 3.03%   |
| Bremen         | 1        | 3.03%   |
| Baumgartenberg | 1        | 3.03%   |
| Alexandria     | 1        | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 11       | 15     | 18.97%  |
| Seagate                     | 11       | 13     | 18.97%  |
| Samsung Electronics         | 6        | 7      | 10.34%  |
| Toshiba                     | 3        | 3      | 5.17%   |
| SanDisk                     | 3        | 3      | 5.17%   |
| Hitachi                     | 2        | 2      | 3.45%   |
| Gigabyte Technology         | 2        | 2      | 3.45%   |
| Crucial                     | 2        | 3      | 3.45%   |
| China                       | 2        | 2      | 3.45%   |
| XrayDisk                    | 1        | 1      | 1.72%   |
| SPCC                        | 1        | 1      | 1.72%   |
| SK hynix                    | 1        | 1      | 1.72%   |
| Plextor                     | 1        | 1      | 1.72%   |
| Patriot                     | 1        | 1      | 1.72%   |
| Netac                       | 1        | 1      | 1.72%   |
| Micron/Crucial Technology   | 1        | 2      | 1.72%   |
| Maxtor                      | 1        | 1      | 1.72%   |
| MAXIO Technology (Hangzhou) | 1        | 2      | 1.72%   |
| KIOXIA-EXCERIA              | 1        | 2      | 1.72%   |
| Kingston                    | 1        | 1      | 1.72%   |
| KingSpec                    | 1        | 1      | 1.72%   |
| KingFast                    | 1        | 1      | 1.72%   |
| Intel                       | 1        | 1      | 1.72%   |
| HGST                        | 1        | 1      | 1.72%   |
| FC-1307                     | 1        | 1      | 1.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                   | 3        | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2        | 3.17%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD              | 2        | 3.17%   |
| XrayDisk 512GB SSD                                | 1        | 1.59%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                    | 1        | 1.59%   |
| WDC WDBNCE5000PNC 500GB SSD                       | 1        | 1.59%   |
| WDC WD800JD-00MSA1 80GB                           | 1        | 1.59%   |
| WDC WD50 00AZLX-60K2TA0 500GB                     | 1        | 1.59%   |
| WDC WD20EZRZ-22Z5HB0 2TB                          | 1        | 1.59%   |
| WDC WD1600AAJS-60M0A0 160GB                       | 1        | 1.59%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 1        | 1.59%   |
| WDC WD10EZEX-60WN4A0 1TB                          | 1        | 1.59%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 1        | 1.59%   |
| WDC WD10EZEX-21M2NA0 1TB                          | 1        | 1.59%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 1        | 1.59%   |
| WDC WD1002FAEX-00Z3A0 1TB                         | 1        | 1.59%   |
| Toshiba HDWD110 1TB                               | 1        | 1.59%   |
| Toshiba DT01ACA300 3TB                            | 1        | 1.59%   |
| Toshiba DT01ACA050 500GB                          | 1        | 1.59%   |
| SPCC Solid State Disk 256GB                       | 1        | 1.59%   |
| SK hynix SC311 SATA 128GB SSD                     | 1        | 1.59%   |
| Seagate ST3500413AS 500GB                         | 1        | 1.59%   |
| Seagate ST3320413AS 320GB                         | 1        | 1.59%   |
| Seagate ST3250312AS 250GB                         | 1        | 1.59%   |
| Seagate ST3160318AS 160GB                         | 1        | 1.59%   |
| Seagate ST3000DM008-2DM166 3TB                    | 1        | 1.59%   |
| Seagate ST2000LM007-1R8174 2TB                    | 1        | 1.59%   |
| Seagate ST2000DM008-2FR102 2TB                    | 1        | 1.59%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1        | 1.59%   |
| Seagate ST1000DM003-9YN162 1TB                    | 1        | 1.59%   |
| Seagate ST1000DM003-1ER162 1TB                    | 1        | 1.59%   |
| Sandisk WD_BLACK SN770 1TB                        | 1        | 1.59%   |
| Sandisk WD Blue SN570 500GB                       | 1        | 1.59%   |
| SanDisk SSD PLUS 240GB                            | 1        | 1.59%   |
| Samsung SSD 850 EVO M.2 250GB                     | 1        | 1.59%   |
| Samsung MZ7TY256HDHP-000H1 256GB SSD              | 1        | 1.59%   |
| Samsung HD501LJ 500GB                             | 1        | 1.59%   |
| Samsung HD251HJ 250GB                             | 1        | 1.59%   |
| Samsung HD250HJ 250GB                             | 1        | 1.59%   |
| Plextor PH6-CE120-L1 120GB SSD                    | 1        | 1.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 13     | 36.67%  |
| WDC                 | 9        | 13     | 30%     |
| Toshiba             | 3        | 3      | 10%     |
| Samsung Electronics | 2        | 3      | 6.67%   |
| Hitachi             | 2        | 2      | 6.67%   |
| Maxtor              | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |
| FC-1307             | 1        | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 10%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Gigabyte Technology | 2        | 2      | 10%     |
| Crucial             | 2        | 3      | 10%     |
| China               | 2        | 2      | 10%     |
| XrayDisk            | 1        | 1      | 5%      |
| SPCC                | 1        | 1      | 5%      |
| SK hynix            | 1        | 1      | 5%      |
| SanDisk             | 1        | 1      | 5%      |
| Plextor             | 1        | 1      | 5%      |
| Patriot             | 1        | 1      | 5%      |
| Netac               | 1        | 1      | 5%      |
| KIOXIA-EXCERIA      | 1        | 2      | 5%      |
| Kingston            | 1        | 1      | 5%      |
| KingSpec            | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 24       | 37     | 48.98%  |
| SSD     | 18       | 22     | 36.73%  |
| NVMe    | 6        | 9      | 12.24%  |
| Unknown | 1        | 1      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 59     | 81.08%  |
| NVMe | 6        | 9      | 16.22%  |
| SAS  | 1        | 1      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 38     | 57.5%   |
| 0.51-1.0   | 10       | 14     | 25%     |
| 1.01-2.0   | 5        | 5      | 12.5%   |
| 2.01-3.0   | 2        | 2      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 9        | 26.47%  |
| 251-500        | 7        | 20.59%  |
| 1001-2000      | 6        | 17.65%  |
| 501-1000       | 5        | 14.71%  |
| 2001-3000      | 3        | 8.82%   |
| 51-100         | 3        | 8.82%   |
| More than 3000 | 1        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 13       | 38.24%  |
| 21-50     | 7        | 20.59%  |
| 1001-2000 | 4        | 11.76%  |
| 501-1000  | 4        | 11.76%  |
| 251-500   | 3        | 8.82%   |
| 101-250   | 2        | 5.88%   |
| 51-100    | 1        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3250312AS 250GB | 1        | 1      | 50%     |
| Seagate ST3160318AS 160GB | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

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
| Detected | 28       | 59     | 82.35%  |
| Works    | 4        | 8      | 11.76%  |
| Malfunc  | 2        | 2      | 5.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 26       | 66.67%  |
| AMD                         | 6        | 15.38%  |
| SanDisk                     | 2        | 5.13%   |
| Samsung Electronics         | 2        | 5.13%   |
| Micron/Crucial Technology   | 1        | 2.56%   |
| MAXIO Technology (Hangzhou) | 1        | 2.56%   |
| JMicron Technology          | 1        | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 9.62%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 5.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 5.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 5.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 5.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 3.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 3.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 3.85%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 3.85%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 3.85%   |
| AMD FCH SATA Controller D                                                               | 2        | 3.85%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 1        | 1.92%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 1        | 1.92%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 1        | 1.92%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 1        | 1.92%   |
| JMicron JMB368 IDE controller                                                           | 1        | 1.92%   |
| Intel SSD 660P Series                                                                   | 1        | 1.92%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 1        | 1.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.92%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 1.92%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 1.92%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 1.92%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 1.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.92%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 53.85%  |
| IDE  | 9        | 23.08%  |
| NVMe | 6        | 15.38%  |
| RAID | 3        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 26       | 81.25%  |
| AMD    | 6        | 18.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz             | 2        | 6.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz             | 2        | 6.25%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics  | 2        | 6.25%   |
| Intel Xeon E-2224G CPU @ 3.50GHz             | 1        | 3.13%   |
| Intel Xeon CPU W3540 @ 2.93GHz               | 1        | 3.13%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz           | 1        | 3.13%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz  | 1        | 3.13%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz  | 1        | 3.13%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz       | 1        | 3.13%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 1        | 3.13%   |
| Intel Core i7-7700 CPU @ 3.60GHz             | 1        | 3.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz            | 1        | 3.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz             | 1        | 3.13%   |
| Intel Core i7-4770 CPU @ 3.40GHz             | 1        | 3.13%   |
| Intel Core i7-3770S CPU @ 3.10GHz            | 1        | 3.13%   |
| Intel Core i7-10700 CPU @ 2.90GHz            | 1        | 3.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz             | 1        | 3.13%   |
| Intel Core i5-3450 CPU @ 3.10GHz             | 1        | 3.13%   |
| Intel Core i5-2300 CPU @ 2.80GHz             | 1        | 3.13%   |
| Intel Core i3-8100T CPU @ 3.10GHz            | 1        | 3.13%   |
| Intel Core i3-8100 CPU @ 3.60GHz             | 1        | 3.13%   |
| Intel Core i3-4170 CPU @ 3.70GHz             | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz        | 1        | 3.13%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 1        | 3.13%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz         | 1        | 3.13%   |
| AMD Ryzen 9 5950X 16-Core Processor          | 1        | 3.13%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 1        | 3.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 1        | 3.13%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 7        | 21.88%  |
| Intel Core i5           | 7        | 21.88%  |
| Intel Xeon              | 3        | 9.38%   |
| Intel Core i3           | 3        | 9.38%   |
| Intel Pentium Dual-Core | 2        | 6.25%   |
| Intel Core 2 Quad       | 2        | 6.25%   |
| AMD Ryzen 5             | 2        | 6.25%   |
| AMD Ryzen 3             | 2        | 6.25%   |
| Other                   | 1        | 3.13%   |
| Intel Pentium Dual      | 1        | 3.13%   |
| Intel Core 2 Duo        | 1        | 3.13%   |
| AMD Ryzen 9             | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 21       | 65.63%  |
| 2      | 6        | 18.75%  |
| 6      | 3        | 9.38%   |
| 16     | 1        | 3.13%   |
| 8      | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 62.5%   |
| 2      | 12       | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 32       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 93.75%  |
| 0x306a9    | 1        | 3.13%   |
| 0x06006704 | 1        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 5        | 15.63%  |
| SandyBridge | 4        | 12.5%   |
| Penryn      | 4        | 12.5%   |
| Haswell     | 4        | 12.5%   |
| IvyBridge   | 3        | 9.38%   |
| Zen 3       | 2        | 6.25%   |
| Zen         | 2        | 6.25%   |
| Skylake     | 2        | 6.25%   |
| Core        | 2        | 6.25%   |
| Nehalem     | 1        | 3.13%   |
| Excavator   | 1        | 3.13%   |
| CometLake   | 1        | 3.13%   |
| Unknown     | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 42.42%  |
| Intel  | 12       | 36.36%  |
| AMD    | 7        | 21.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 9.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 6.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 6.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 3.03%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.03%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 3.03%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 3.03%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.03%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 3.03%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1        | 3.03%   |
| Intel HD Graphics 630                                                       | 1        | 3.03%   |
| Intel HD Graphics 530                                                       | 1        | 3.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics P630]                                  | 1        | 3.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.03%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 3.03%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 3.03%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                           | 1        | 3.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 1        | 3.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 3.03%   |
| AMD Lucienne                                                                | 1        | 3.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 3.03%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 13       | 40.63%  |
| 1 x Intel      | 11       | 34.38%  |
| 1 x AMD        | 7        | 21.88%  |
| Intel + Nvidia | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 84.38%  |
| Proprietary | 4        | 12.5%   |
| Unknown     | 1        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 26       | 81.25%  |
| 3.01-4.0   | 4        | 12.5%   |
| 7.01-8.0   | 1        | 3.13%   |
| 0.51-1.0   | 1        | 3.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 6        | 18.18%  |
| Goldstar             | 5        | 15.15%  |
| Philips              | 4        | 12.12%  |
| Samsung Electronics  | 3        | 9.09%   |
| Acer                 | 3        | 9.09%   |
| Vizio                | 2        | 6.06%   |
| Dell                 | 2        | 6.06%   |
| BenQ                 | 2        | 6.06%   |
| Skyworth             | 1        | 3.03%   |
| NEC Computers        | 1        | 3.03%   |
| Medion               | 1        | 3.03%   |
| LTM                  | 1        | 3.03%   |
| Kogan                | 1        | 3.03%   |
| Ancor Communications | 1        | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                   | 1        | 2.94%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                  | 1        | 2.94%   |
| Skyworth CP9687 SII9687 1920x1080 708x398mm 32.0-inch                | 1        | 2.94%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                     | 1        | 2.94%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 1        | 2.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 1        | 2.94%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 600x340mm 27.2-inch             | 1        | 2.94%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 1        | 2.94%   |
| Philips 244E PHLC036 1920x1080 521x293mm 23.5-inch                   | 1        | 2.94%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                  | 1        | 2.94%   |
| NEC Computers LCD224WM NEC6733 1680x1050 474x296mm 22.0-inch         | 1        | 2.94%   |
| Medion MD21274 MED36B5 1920x1080 598x336mm 27.0-inch                 | 1        | 2.94%   |
| LTM LONTIUM LTM0401 1920x1080 890x500mm 40.2-inch                    | 1        | 2.94%   |
| Kogan KAMN27QF7TA KGN0270 2560x1440 698x393mm 31.5-inch              | 1        | 2.94%   |
| Hewlett-Packard ENVY 27 HPN3367 3840x2160 597x336mm 27.0-inch        | 1        | 2.94%   |
| Hewlett-Packard 27mq HPN3671 2560x1440 597x336mm 27.0-inch           | 1        | 2.94%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch            | 1        | 2.94%   |
| Hewlett-Packard 2711 HWP2941 1920x1080 598x337mm 27.0-inch           | 1        | 2.94%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch           | 1        | 2.94%   |
| Hewlett-Packard 22xi HWP302E 1920x1080 480x270mm 21.7-inch           | 1        | 2.94%   |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch           | 1        | 2.94%   |
| Goldstar W2443 GSM571B 1920x1080 474x296mm 22.0-inch                 | 1        | 2.94%   |
| Goldstar ULTRAGEAR GSM5C08 1920x1080 530x300mm 24.0-inch             | 1        | 2.94%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 1        | 2.94%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 2.94%   |
| Goldstar 2D HD TV GSM59C8 1366x768 509x286mm 23.0-inch               | 1        | 2.94%   |
| Dell S2718H/HX DELD0B2 1920x1080 598x336mm 27.0-inch                 | 1        | 2.94%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                   | 1        | 2.94%   |
| BenQ GW2406Z BNQ78E1 1920x1080 527x296mm 23.8-inch                   | 1        | 2.94%   |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                    | 1        | 2.94%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 1        | 2.94%   |
| Acer S230HL ACR0282 1920x1080 509x286mm 23.0-inch                    | 1        | 2.94%   |
| Acer ED273UR ACR0692 2560x1440 596x335mm 26.9-inch                   | 1        | 2.94%   |
| Acer ED270R S ACR0804 1920x1080 609x348mm 27.6-inch                  | 1        | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 19       | 61.29%  |
| 2560x1440 (QHD)    | 3        | 9.68%   |
| 1366x768 (WXGA)    | 3        | 9.68%   |
| 3840x2160 (4K)     | 2        | 6.45%   |
| 1920x540           | 1        | 3.23%   |
| 1680x1050 (WSXGA+) | 1        | 3.23%   |
| 1440x900 (WXGA+)   | 1        | 3.23%   |
| 1280x1024 (SXGA)   | 1        | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 9        | 26.47%  |
| 23      | 4        | 11.76%  |
| 24      | 3        | 8.82%   |
| 21      | 3        | 8.82%   |
| 40      | 2        | 5.88%   |
| 26      | 2        | 5.88%   |
| 22      | 2        | 5.88%   |
| 18      | 2        | 5.88%   |
| 49      | 1        | 2.94%   |
| 42      | 1        | 2.94%   |
| 32      | 1        | 2.94%   |
| 31      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 17      | 1        | 2.94%   |
| Unknown | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 45.45%  |
| 401-500     | 9        | 27.27%  |
| 801-900     | 2        | 6.06%   |
| 601-700     | 2        | 6.06%   |
| 701-800     | 1        | 3.03%   |
| 301-350     | 1        | 3.03%   |
| 1001-1500   | 1        | 3.03%   |
| 901-1000    | 1        | 3.03%   |
| Unknown     | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 25       | 86.21%  |
| 16/10 | 3        | 10.34%  |
| 5/4   | 1        | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 33.33%  |
| 301-350        | 10       | 30.3%   |
| 141-150        | 3        | 9.09%   |
| 501-1000       | 3        | 9.09%   |
| 351-500        | 2        | 6.06%   |
| More than 1000 | 1        | 3.03%   |
| 251-300        | 1        | 3.03%   |
| 151-200        | 1        | 3.03%   |
| Unknown        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 68.97%  |
| 101-120 | 6        | 20.69%  |
| 1-50    | 1        | 3.45%   |
| 161-240 | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 81.25%  |
| 2     | 5        | 15.63%  |
| 0     | 1        | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 37.5%   |
| Intel                 | 16       | 33.33%  |
| TP-Link               | 2        | 4.17%   |
| Ralink Technology     | 2        | 4.17%   |
| Qualcomm Atheros      | 2        | 4.17%   |
| Broadcom              | 2        | 4.17%   |
| Ralink                | 1        | 2.08%   |
| NetGear               | 1        | 2.08%   |
| MediaTek              | 1        | 2.08%   |
| ICS Advent            | 1        | 2.08%   |
| D-Link System         | 1        | 2.08%   |
| ASIX Electronics      | 1        | 2.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller      | 14       | 26.92%  |
| Intel Ethernet Connection (2) I219-V                                        | 3        | 5.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 3.85%   |
| Ralink MT7601U Wireless Adapter                                             | 2        | 3.85%   |
| Intel Ethernet Connection (7) I219-V                                        | 2        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 2        | 3.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1        | 1.92%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                       | 1        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 1        | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                           | 1        | 1.92%   |
| Realtek 802.11ac NIC                                                        | 1        | 1.92%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 1        | 1.92%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                  | 1        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 1.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 1        | 1.92%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                 | 1        | 1.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                     | 1        | 1.92%   |
| Intel I211 Gigabit Network Connection                                       | 1        | 1.92%   |
| Intel Ethernet Controller I226-V                                            | 1        | 1.92%   |
| Intel Ethernet Connection I217-V                                            | 1        | 1.92%   |
| Intel Ethernet Connection I217-LM                                           | 1        | 1.92%   |
| Intel Ethernet Connection (7) I219-LM                                       | 1        | 1.92%   |
| Intel Ethernet Connection (2) I218-V                                        | 1        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1        | 1.92%   |
| Intel 82579V Gigabit Network Connection                                     | 1        | 1.92%   |
| Intel 82566DM-2 Gigabit Network Connection                                  | 1        | 1.92%   |
| Intel 82566DC-2 Gigabit Network Connection                                  | 1        | 1.92%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                     | 1        | 1.92%   |
| D-Link System DWA-130 802.11n Wireless N Adapter(rev.E) [Realtek RTL8191SU] | 1        | 1.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                            | 1        | 1.92%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 1        | 1.92%   |
| ASIX AX88772B                                                               | 1        | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 31.25%  |
| TP-Link               | 2        | 12.5%   |
| Ralink Technology     | 2        | 12.5%   |
| Ralink                | 1        | 6.25%   |
| Qualcomm Atheros      | 1        | 6.25%   |
| NetGear               | 1        | 6.25%   |
| MediaTek              | 1        | 6.25%   |
| Intel                 | 1        | 6.25%   |
| D-Link System         | 1        | 6.25%   |
| Broadcom              | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 12.5%   |
| Ralink MT7601U Wireless Adapter                                             | 2        | 12.5%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1        | 6.25%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                       | 1        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 1        | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1        | 6.25%   |
| Realtek 802.11ac NIC                                                        | 1        | 6.25%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                        | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 6.25%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                 | 1        | 6.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                     | 1        | 6.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 1        | 6.25%   |
| D-Link System DWA-130 802.11n Wireless N Adapter(rev.E) [Realtek RTL8191SU] | 1        | 6.25%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 44.44%  |
| Realtek Semiconductor | 15       | 41.67%  |
| Qualcomm Atheros      | 2        | 5.56%   |
| ICS Advent            | 1        | 2.78%   |
| Broadcom              | 1        | 2.78%   |
| ASIX Electronics      | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14       | 38.89%  |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 8.33%   |
| Intel Ethernet Connection (7) I219-V                                   | 2        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 5.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 2.78%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 1        | 2.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1        | 2.78%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 2.78%   |
| Intel Ethernet Controller I226-V                                       | 1        | 2.78%   |
| Intel Ethernet Connection I217-V                                       | 1        | 2.78%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 2.78%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 2.78%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 2.78%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 2.78%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 2.78%   |
| Intel 82566DC-2 Gigabit Network Connection                             | 1        | 2.78%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1        | 2.78%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 2.78%   |
| ASIX AX88772B                                                          | 1        | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 66.67%  |
| WiFi     | 16       | 33.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 63.64%  |
| WiFi     | 12       | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 75%     |
| 2     | 6        | 18.75%  |
| 3     | 2        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 59.38%  |
| Yes  | 13       | 40.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 4        | 40%     |
| TP-Link                 | 2        | 20%     |
| MediaTek                | 1        | 10%     |
| Intel                   | 1        | 10%     |
| Cambridge Silicon Radio | 1        | 10%     |
| ASUSTek Computer        | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 4        | 40%     |
| TP-Link UB500 Adapter                               | 2        | 20%     |
| MediaTek Wireless_Device                            | 1        | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 10%     |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 26       | 52%     |
| Nvidia              | 13       | 26%     |
| AMD                 | 9        | 18%     |
| Logitech            | 1        | 2%      |
| C-Media Electronics | 1        | 2%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 7.14%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 7.14%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 7.14%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 5.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 5.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 5.36%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2        | 3.57%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 3.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 2        | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.79%   |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.79%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.79%   |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 1.79%   |
| Logitech H390 headset with microphone                                             | 1        | 1.79%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 1        | 1.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 1.79%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 1.79%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 1        | 1.79%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                        | 1        | 1.79%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 1        | 1.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.79%   |
| AMD High Definition Audio Controller                                              | 1        | 1.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1        | 1.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Kingston           | 3        | 50%     |
| Ramaxel Technology | 1        | 16.67%  |
| Nanya Technology   | 1        | 16.67%  |
| Crucial            | 1        | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s | 1        | 16.67%  |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s      | 1        | 16.67%  |
| Kingston RAM Module 2GB DIMM DDR2 667MT/s               | 1        | 16.67%  |
| Kingston RAM KTW149-ELD 1GB DIMM DDR3 1333MT/s          | 1        | 16.67%  |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s         | 1        | 16.67%  |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s   | 1        | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 3        | 60%     |
| DDR4 | 1        | 20%     |
| DDR2 | 1        | 20%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 5        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 3        | 50%     |
| 2048 | 2        | 33.33%  |
| 1024 | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 1        | 20%     |
| 1800  | 1        | 20%     |
| 1600  | 1        | 20%     |
| 1333  | 1        | 20%     |
| 667   | 1        | 20%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Canon               | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung M2070 Series    | 1        | 50%     |
| Canon CanoScan LiDE 300 | 1        | 50%     |

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


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Logitech     | 2        | 33.33%  |
| Trust        | 1        | 16.67%  |
| MacroSilicon | 1        | 16.67%  |
| GEMBIRD      | 1        | 16.67%  |
| Apple        | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Trust USB Camera                   | 1        | 16.67%  |
| MacroSilicon USB3. 0 capture       | 1        | 16.67%  |
| Logitech Webcam C925e              | 1        | 16.67%  |
| Logitech C922 Pro Stream Webcam    | 1        | 16.67%  |
| GEMBIRD USB2.0 PC CAMERA           | 1        | 16.67%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR | 1        | 16.67%  |

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
| 0     | 29       | 90.63%  |
| 1     | 3        | 9.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 1        | 33.33%  |
| Multimedia controller | 1        | 33.33%  |
| Graphics card         | 1        | 33.33%  |

