Parrot 4.11 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_4.11/Desktop/README.md) and [notebooks](/Dist/Parrot_4.11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=parrot-4.11

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [e3fd336b60](https://linux-hardware.org/?probe=e3fd336b60) | Aug 24, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6647d75cdb](https://linux-hardware.org/?probe=6647d75cdb) | Aug 20, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5363cc3efd](https://linux-hardware.org/?probe=5363cc3efd) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| Quanta        | 3610D                       | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| Quanta        | 3610D                       | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-6parrot1-amd64    | 22        | 41.51%  |
| 5.10.0-8parrot1-amd64    | 16        | 30.19%  |
| 5.10.0-3parrot1-amd64    | 5         | 9.43%   |
| 5.7.0-2parrot2-amd64     | 4         | 7.55%   |
| 5.10.0-5parrot1-amd64    | 4         | 7.55%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.89%   |
| Unknown                  | 1         | 1.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 48        | 90.57%  |
| 5.7.0   | 4         | 7.55%   |
| Unknown | 1         | 1.89%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 48        | 90.57%  |
| 5.7     | 4         | 7.55%   |
| Unknown | 1         | 1.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 53        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 28        | 51.85%  |
| KDE5    | 13        | 24.07%  |
| KDE     | 7         | 12.96%  |
| Unknown | 3         | 5.56%   |
| XFCE    | 2         | 3.7%    |
| LXDE    | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 53        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 24        | 44.44%  |
| TDM     | 23        | 42.59%  |
| LightDM | 6         | 11.11%  |
| SDDM    | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 24        | 45.28%  |
| ru_RU   | 4         | 7.55%   |
| fr_FR   | 4         | 7.55%   |
| en_AU   | 4         | 7.55%   |
| pt_BR   | 3         | 5.66%   |
| en_GB   | 3         | 5.66%   |
| Unknown | 3         | 5.66%   |
| es_ES   | 2         | 3.77%   |
| ru_UA   | 1         | 1.89%   |
| nl_BE   | 1         | 1.89%   |
| id_ID   | 1         | 1.89%   |
| es_CO   | 1         | 1.89%   |
| de_DE   | 1         | 1.89%   |
| cs_CZ   | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 37        | 68.52%  |
| EFI  | 17        | 31.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 43        | 81.13%  |
| Ext4  | 6         | 11.32%  |
| Xfs   | 4         | 7.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 22        | 40.74%  |
| GPT     | 19        | 35.19%  |
| MBR     | 13        | 24.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 83.33%  |
| Yes       | 9         | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 37        | 69.81%  |
| Yes       | 16        | 30.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 22.64%  |
| ASUSTek Computer    | 8         | 15.09%  |
| Dell                | 7         | 13.21%  |
| MSI                 | 5         | 9.43%   |
| Lenovo              | 4         | 7.55%   |
| Acer                | 4         | 7.55%   |
| Samsung Electronics | 2         | 3.77%   |
| Apple               | 2         | 3.77%   |
| ZOTAC               | 1         | 1.89%   |
| Wortmann AG         | 1         | 1.89%   |
| Quanta              | 1         | 1.89%   |
| Microsoft           | 1         | 1.89%   |
| Intel               | 1         | 1.89%   |
| Gigabyte Technology | 1         | 1.89%   |
| Gateway             | 1         | 1.89%   |
| Fujitsu             | 1         | 1.89%   |
| Eluktronics         | 1         | 1.89%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 3.77%   |
| ASUS Q524UQ                             | 2         | 3.77%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 1.89%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.89%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 1.89%   |
| Quanta HDX PREMIUM SERIES               | 1         | 1.89%   |
| MSI GT60 2OC/2OD                        | 1         | 1.89%   |
| MSI GS66 Stealth 10UG                   | 1         | 1.89%   |
| MSI GE75 Raider 10SF                    | 1         | 1.89%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 1.89%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 1.89%   |
| Microsoft Surface Pro 3                 | 1         | 1.89%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 1.89%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 1.89%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 1.89%   |
| Lenovo B50-80 80EW                      | 1         | 1.89%   |
| Intel NUC8i7HVK                         | 1         | 1.89%   |
| HP ZBook 15 G5                          | 1         | 1.89%   |
| HP Pavilion Notebook                    | 1         | 1.89%   |
| HP Pavilion dv7                         | 1         | 1.89%   |
| HP Pavilion dv6700                      | 1         | 1.89%   |
| HP Pavilion dv6                         | 1         | 1.89%   |
| HP Pavilion dv4                         | 1         | 1.89%   |
| HP Laptop 15s-eq1xxx                    | 1         | 1.89%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.89%   |
| HP Compaq Pro 6305 MT                   | 1         | 1.89%   |
| HP All-in-One 24-f0xx                   | 1         | 1.89%   |
| Gigabyte A320M-S2H                      | 1         | 1.89%   |
| Gateway MP8708                          | 1         | 1.89%   |
| Fujitsu LIFEBOOK T731                   | 1         | 1.89%   |
| Eluktronics MAG-15u                     | 1         | 1.89%   |
| Dell OptiPlex 7070                      | 1         | 1.89%   |
| Dell OptiPlex 3010                      | 1         | 1.89%   |
| Dell Latitude E7440                     | 1         | 1.89%   |
| Dell Latitude E6420                     | 1         | 1.89%   |
| Dell Inspiron 5593                      | 1         | 1.89%   |
| Dell Inspiron 5558                      | 1         | 1.89%   |
| Dell Inspiron 5420                      | 1         | 1.89%   |
| ASUS X75VB                              | 1         | 1.89%   |
| ASUS X450EA                             | 1         | 1.89%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 1.89%   |
| ASUS PRIME X399-A                       | 1         | 1.89%   |
| ASUS M5A78L-M/USB3                      | 1         | 1.89%   |
| ASUS G74Sx                              | 1         | 1.89%   |
| Apple MacBookPro8,1                     | 1         | 1.89%   |
| Apple MacBookPro11,1                    | 1         | 1.89%   |
| Acer TravelMate 5720                    | 1         | 1.89%   |
| Acer Swift SF114-33                     | 1         | 1.89%   |
| Acer Predator PO3-600                   | 1         | 1.89%   |
| Acer Aspire E1-571G                     | 1         | 1.89%   |
| Unknown                                 | 1         | 1.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| HP Pavilion         | 5         | 9.43%   |
| Dell Inspiron       | 3         | 5.66%   |
| Lenovo ThinkPad     | 2         | 3.77%   |
| HP ProBook          | 2         | 3.77%   |
| HP Laptop           | 2         | 3.77%   |
| Dell OptiPlex       | 2         | 3.77%   |
| Dell Latitude       | 2         | 3.77%   |
| ASUS Q524UQ         | 2         | 3.77%   |
| Wortmann AG TERRA   | 1         | 1.89%   |
| Samsung 350V5C      | 1         | 1.89%   |
| Samsung 300E4C      | 1         | 1.89%   |
| Quanta HDX          | 1         | 1.89%   |
| MSI GT60            | 1         | 1.89%   |
| MSI GS66            | 1         | 1.89%   |
| MSI GE75            | 1         | 1.89%   |
| MSI GE73            | 1         | 1.89%   |
| MSI GE63            | 1         | 1.89%   |
| Microsoft Surface   | 1         | 1.89%   |
| Lenovo Y520-15IKBN  | 1         | 1.89%   |
| Lenovo B50-80       | 1         | 1.89%   |
| Intel NUC8i7HVK     | 1         | 1.89%   |
| HP ZBook            | 1         | 1.89%   |
| HP Compaq           | 1         | 1.89%   |
| HP All-in-One       | 1         | 1.89%   |
| Gigabyte A320M-S2H  | 1         | 1.89%   |
| Gateway MP8708      | 1         | 1.89%   |
| Fujitsu LIFEBOOK    | 1         | 1.89%   |
| Eluktronics MAG-15u | 1         | 1.89%   |
| ASUS X75VB          | 1         | 1.89%   |
| ASUS X450EA         | 1         | 1.89%   |
| ASUS VivoBook       | 1         | 1.89%   |
| ASUS PRIME          | 1         | 1.89%   |
| ASUS M5A78L-M       | 1         | 1.89%   |
| ASUS G74Sx          | 1         | 1.89%   |
| Apple MacBookPro8   | 1         | 1.89%   |
| Apple MacBookPro11  | 1         | 1.89%   |
| Acer TravelMate     | 1         | 1.89%   |
| Acer Swift          | 1         | 1.89%   |
| Acer Predator       | 1         | 1.89%   |
| Acer Aspire         | 1         | 1.89%   |
| Unknown             | 1         | 1.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 9         | 16.98%  |
| 2019 | 9         | 16.98%  |
| 2018 | 7         | 13.21%  |
| 2013 | 6         | 11.32%  |
| 2016 | 4         | 7.55%   |
| 2021 | 3         | 5.66%   |
| 2015 | 3         | 5.66%   |
| 2012 | 3         | 5.66%   |
| 2011 | 2         | 3.77%   |
| 2010 | 2         | 3.77%   |
| 2008 | 2         | 3.77%   |
| 2017 | 1         | 1.89%   |
| 2014 | 1         | 1.89%   |
| 2006 | 1         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 42        | 79.25%  |
| Desktop    | 8         | 15.09%  |
| Tablet     | 1         | 1.89%   |
| Mini pc    | 1         | 1.89%   |
| All in one | 1         | 1.89%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 53        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 30.19%  |
| 8.01-16.0   | 14        | 26.42%  |
| 3.01-4.0    | 9         | 16.98%  |
| 16.01-24.0  | 6         | 11.32%  |
| 64.01-256.0 | 3         | 5.66%   |
| 32.01-64.0  | 2         | 3.77%   |
| 24.01-32.0  | 1         | 1.89%   |
| 2.01-3.0    | 1         | 1.89%   |
| 1.01-2.0    | 1         | 1.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 21        | 38.89%  |
| 1.01-2.0  | 19        | 35.19%  |
| 4.01-8.0  | 7         | 12.96%  |
| 3.01-4.0  | 6         | 11.11%  |
| 8.01-16.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 50.94%  |
| 2      | 17        | 32.08%  |
| 3      | 8         | 15.09%  |
| 4      | 1         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 35        | 66.04%  |
| Yes       | 18        | 33.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 83.02%  |
| No        | 9         | 16.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 90.74%  |
| No        | 5         | 9.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 71.7%   |
| No        | 15        | 28.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 30.19%  |
| Spain        | 4         | 7.55%   |
| Germany      | 4         | 7.55%   |
| Russia       | 3         | 5.66%   |
| France       | 3         | 5.66%   |
| Australia    | 3         | 5.66%   |
| Brazil       | 2         | 3.77%   |
| Ukraine      | 1         | 1.89%   |
| UK           | 1         | 1.89%   |
| Sweden       | 1         | 1.89%   |
| South Africa | 1         | 1.89%   |
| Puerto Rico  | 1         | 1.89%   |
| Netherlands  | 1         | 1.89%   |
| Mexico       | 1         | 1.89%   |
| Kenya        | 1         | 1.89%   |
| Iraq         | 1         | 1.89%   |
| Indonesia    | 1         | 1.89%   |
| Hungary      | 1         | 1.89%   |
| Czechia      | 1         | 1.89%   |
| Colombia     | 1         | 1.89%   |
| Canada       | 1         | 1.89%   |
| Belgium      | 1         | 1.89%   |
| Bangladesh   | 1         | 1.89%   |
| Azerbaijan   | 1         | 1.89%   |
| Algeria      | 1         | 1.89%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Chicago                  | 2         | 3.64%   |
| Witbank                  | 1         | 1.82%   |
| West Jordan              | 1         | 1.82%   |
| Visalia                  | 1         | 1.82%   |
| Ternopil                 | 1         | 1.82%   |
| Stockholm                | 1         | 1.82%   |
| Sinntal                  | 1         | 1.82%   |
| Secaucus                 | 1         | 1.82%   |
| S??o Paulo               | 1         | 1.82%   |
| Santo André             | 1         | 1.82%   |
| Sannois                  | 1         | 1.82%   |
| Regensburg               | 1         | 1.82%   |
| Prague                   | 1         | 1.82%   |
| Portsmouth               | 1         | 1.82%   |
| Ponce                    | 1         | 1.82%   |
| Oklahoma City            | 1         | 1.82%   |
| Offenbach                | 1         | 1.82%   |
| Nairobi                  | 1         | 1.82%   |
| Mostoles                 | 1         | 1.82%   |
| Marietta                 | 1         | 1.82%   |
| Majadahonda              | 1         | 1.82%   |
| Lyon                     | 1         | 1.82%   |
| Los Mochis               | 1         | 1.82%   |
| Los Angeles              | 1         | 1.82%   |
| Long Beach               | 1         | 1.82%   |
| London                   | 1         | 1.82%   |
| Khabarovsk               | 1         | 1.82%   |
| Kazan?��                 | 1         | 1.82%   |
| Jihlava                  | 1         | 1.82%   |
| Jakarta                  | 1         | 1.82%   |
| Houston                  | 1         | 1.82%   |
| Frankfurt am Main        | 1         | 1.82%   |
| Fort Lauderdale          | 1         | 1.82%   |
| Eugene                   | 1         | 1.82%   |
| Erbil                    | 1         | 1.82%   |
| Edmonton                 | 1         | 1.82%   |
| East Malvern             | 1         | 1.82%   |
| Dudenhofen               | 1         | 1.82%   |
| Donostia / San Sebastian | 1         | 1.82%   |
| Dhaka                    | 1         | 1.82%   |
| Denham Springs           | 1         | 1.82%   |
| Concord                  | 1         | 1.82%   |
| Budapest                 | 1         | 1.82%   |
| Brunswick                | 1         | 1.82%   |
| Bogotá                  | 1         | 1.82%   |
| Blagoveshchensk          | 1         | 1.82%   |
| Bay Saint Louis          | 1         | 1.82%   |
| Barcelona                | 1         | 1.82%   |
| Baku                     | 1         | 1.82%   |
| Amsterdam                | 1         | 1.82%   |
| Akbou                    | 1         | 1.82%   |
| Aix-les-Bains            | 1         | 1.82%   |
| Adelaide                 | 1         | 1.82%   |
| Aalst                    | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 13     | 11.9%   |
| Seagate             | 10        | 14     | 11.9%   |
| Samsung Electronics | 9         | 10     | 10.71%  |
| Unknown             | 7         | 7      | 8.33%   |
| Toshiba             | 7         | 7      | 8.33%   |
| Crucial             | 7         | 9      | 8.33%   |
| Kingston            | 5         | 5      | 5.95%   |
| Hitachi             | 5         | 6      | 5.95%   |
| HGST                | 3         | 3      | 3.57%   |
| China               | 3         | 4      | 3.57%   |
| A-DATA Technology   | 3         | 3      | 3.57%   |
| SK Hynix            | 2         | 2      | 2.38%   |
| SanDisk             | 2         | 2      | 2.38%   |
| Micron Technology   | 2         | 2      | 2.38%   |
| SPCC                | 1         | 1      | 1.19%   |
| ROG                 | 1         | 1      | 1.19%   |
| Phison              | 1         | 1      | 1.19%   |
| Patriot             | 1         | 1      | 1.19%   |
| KIOXIA              | 1         | 1      | 1.19%   |
| Intenso             | 1         | 1      | 1.19%   |
| FORESEE             | 1         | 1      | 1.19%   |
| Corsair             | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 2.22%   |
| Unknown SD/MMC/MS PRO 128GB              | 2         | 2.22%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 2         | 2.22%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 2.22%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2.22%   |
| Crucial CT1000MX500SSD1 1TB              | 2         | 2.22%   |
| WDC WDS100T2B0B-00YS70 1TB SSD           | 1         | 1.11%   |
| WDC WDBNCE0010PNC 1TB SSD                | 1         | 1.11%   |
| WDC WD800BEVS-22RST0 80GB                | 1         | 1.11%   |
| WDC WD3200LPVX-60V0TT0 320GB             | 1         | 1.11%   |
| WDC WD3200LPVX-00V0TT0 320GB             | 1         | 1.11%   |
| WDC WD2500BPVT-00JJ5T0 250GB             | 1         | 1.11%   |
| WDC WD10SPZX-17Z10T1 1TB                 | 1         | 1.11%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1         | 1.11%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB     | 1         | 1.11%   |
| Unknown Y016B  16GB                      | 1         | 1.11%   |
| Unknown xD/SD/M.S.                       | 1         | 1.11%   |
| Unknown SS16G  16GB                      | 1         | 1.11%   |
| Unknown SDU1  64GB                       | 1         | 1.11%   |
| Unknown MMC Card  128GB                  | 1         | 1.11%   |
| Toshiba THNSNF128GMCS 128GB SSD          | 1         | 1.11%   |
| Toshiba Q300. 480GB SSD                  | 1         | 1.11%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 1.11%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1.11%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1.11%   |
| Toshiba MK2552GSX 250GB                  | 1         | 1.11%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1.11%   |
| SPCC Solid State Disk 120GB              | 1         | 1.11%   |
| SK Hynix NVMe SSD Drive 256GB            | 1         | 1.11%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB        | 1         | 1.11%   |
| Seagate ST9500420AS 500GB                | 1         | 1.11%   |
| Seagate ST9250410AS 250GB                | 1         | 1.11%   |
| Seagate ST500NM0011 500GB                | 1         | 1.11%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1.11%   |
| Seagate ST500DM002-1SB10A 500GB          | 1         | 1.11%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1.11%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1.11%   |
| Seagate ST250DM000-1BD141 250GB          | 1         | 1.11%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.11%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1.11%   |
| SanDisk Extreme SSD 500GB                | 1         | 1.11%   |
| Samsung SSD 980 1TB                      | 1         | 1.11%   |
| Samsung SSD 860 EVO M.2 2TB              | 1         | 1.11%   |
| Samsung SSD 860 EVO 500GB                | 1         | 1.11%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.11%   |
| Samsung NVMe SSD Drive 1TB               | 1         | 1.11%   |
| Samsung MZVLW256HEHP-00000 256GB         | 1         | 1.11%   |
| Samsung MZVLQ256HAJD-00000 256GB         | 1         | 1.11%   |
| Samsung MZVLB1T0HALR 1TB SSD             | 1         | 1.11%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD     | 1         | 1.11%   |
| Samsung MZMTE512HMHP-000MV 512GB SSD     | 1         | 1.11%   |
| ROG ESD-S1C 256GB                        | 1         | 1.11%   |
| Phison NVMe SSD Drive 1TB                | 1         | 1.11%   |
| Patriot P210 256GB SSD                   | 1         | 1.11%   |
| Micron MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1.11%   |
| Micron 2200_MTFDHBA512TCK 512GB          | 1         | 1.11%   |
| KIOXIA KBG40ZNV256G 256GB                | 1         | 1.11%   |
| Kingston SV300S37A240G 240GB SSD         | 1         | 1.11%   |
| Kingston SKC400S37512G 512GB SSD         | 1         | 1.11%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 14     | 30.3%   |
| WDC     | 8         | 10     | 24.24%  |
| Toshiba | 5         | 5      | 15.15%  |
| Hitachi | 5         | 6      | 15.15%  |
| HGST    | 3         | 3      | 9.09%   |
| Unknown | 2         | 2      | 6.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 7         | 9      | 21.21%  |
| Samsung Electronics | 5         | 5      | 15.15%  |
| Kingston            | 4         | 4      | 12.12%  |
| China               | 3         | 4      | 9.09%   |
| WDC                 | 2         | 2      | 6.06%   |
| Toshiba             | 2         | 2      | 6.06%   |
| SanDisk             | 2         | 2      | 6.06%   |
| SPCC                | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| FORESEE             | 1         | 1      | 3.03%   |
| Corsair             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 28        | 36     | 37.33%  |
| HDD     | 28        | 40     | 37.33%  |
| NVMe    | 13        | 14     | 17.33%  |
| MMC     | 4         | 4      | 5.33%   |
| Unknown | 2         | 2      | 2.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 71     | 66.67%  |
| NVMe | 13        | 14     | 18.84%  |
| SAS  | 6         | 7      | 8.7%    |
| MMC  | 4         | 4      | 5.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 49     | 56.9%   |
| 0.51-1.0   | 20        | 22     | 34.48%  |
| 1.01-2.0   | 4         | 4      | 6.9%    |
| 3.01-4.0   | 1         | 1      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 13        | 23.64%  |
| 101-250        | 12        | 21.82%  |
| 501-1000       | 9         | 16.36%  |
| 1001-2000      | 8         | 14.55%  |
| Unknown        | 5         | 9.09%   |
| 2001-3000      | 3         | 5.45%   |
| 51-100         | 3         | 5.45%   |
| More than 3000 | 2         | 3.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 14        | 25.45%  |
| 51-100    | 11        | 20%     |
| 251-500   | 8         | 14.55%  |
| 101-250   | 8         | 14.55%  |
| 1-20      | 6         | 10.91%  |
| Unknown   | 5         | 9.09%   |
| 501-1000  | 2         | 3.64%   |
| 1001-2000 | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 12.5%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 12.5%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 12.5%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 12.5%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 12.5%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 12.5%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 12.5%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Micron Technology   | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| A-DATA Technology   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 2         | 2      | 25%     |
| NVMe | 1         | 1      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intenso SSD SATAIII 480GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intenso | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 29        | 48     | 44.62%  |
| Works    | 28        | 39     | 43.08%  |
| Malfunc  | 7         | 8      | 10.77%  |
| Failed   | 1         | 1      | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 67.69%  |
| AMD                         | 7         | 10.77%  |
| Samsung Electronics         | 5         | 7.69%   |
| SK Hynix                    | 2         | 3.08%   |
| Sandisk                     | 1         | 1.54%   |
| Realtek Semiconductor       | 1         | 1.54%   |
| Phison Electronics          | 1         | 1.54%   |
| Micron Technology           | 1         | 1.54%   |
| KIOXIA                      | 1         | 1.54%   |
| Kingston Technology Company | 1         | 1.54%   |
| ADATA Technology            | 1         | 1.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 6.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 6.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 5.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 4.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.11%   |
| SK Hynix BC511                                                                         | 2         | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.74%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 2.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 2.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.74%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.37%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.37%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 1.37%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 1         | 1.37%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.37%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.37%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.37%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.37%   |
| AMD X399 Series Chipset SATA Controller                                                | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.37%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.37%   |
| AMD FCH SATA Controller D                                                              | 1         | 1.37%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 50        | 72.46%  |
| NVMe | 13        | 18.84%  |
| IDE  | 5         | 7.25%   |
| RAID | 1         | 1.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 45        | 84.91%  |
| AMD    | 8         | 15.09%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz              | 2         | 3.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 2         | 3.77%   |
| Intel Core i7-2670QM CPU @ 2.20GHz             | 2         | 3.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 2         | 3.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 3.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 2         | 3.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 2         | 3.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 2         | 3.77%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 1.89%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 1         | 1.89%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 1         | 1.89%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1         | 1.89%   |
| Intel Core i7-8850H CPU @ 2.60GHz              | 1         | 1.89%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 1.89%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.89%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.89%   |
| Intel Core i7-4650U CPU @ 1.70GHz              | 1         | 1.89%   |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1         | 1.89%   |
| Intel Core i7-4558U CPU @ 2.80GHz              | 1         | 1.89%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 1.89%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 1.89%   |
| Intel Core i7-10870H CPU @ 2.20GHz             | 1         | 1.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.89%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1         | 1.89%   |
| Intel Core i5-6400T CPU @ 2.20GHz              | 1         | 1.89%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.89%   |
| Intel Core i5-4210M CPU @ 2.60GHz              | 1         | 1.89%   |
| Intel Core i5-4200M CPU @ 2.50GHz              | 1         | 1.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 1.89%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.89%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz          | 1         | 1.89%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz           | 1         | 1.89%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 1.89%   |
| Intel Core 2 CPU T7200 @ 2.00GHz               | 1         | 1.89%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 1.89%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.89%   |
| AMD Ryzen 3 3250U with Radeon Graphics         | 1         | 1.89%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1         | 1.89%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 1.89%   |
| AMD E1-2500 APU with Radeon HD Graphics        | 1         | 1.89%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 1.89%   |
| AMD A4-5300B APU with Radeon HD Graphics       | 1         | 1.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 19        | 35.85%  |
| Intel Core i5           | 16        | 30.19%  |
| Intel Pentium Silver    | 2         | 3.77%   |
| Intel Core i3           | 2         | 3.77%   |
| Intel Core 2 Duo        | 2         | 3.77%   |
| AMD Ryzen 3             | 2         | 3.77%   |
| Intel Pentium Dual-Core | 1         | 1.89%   |
| Intel Core M            | 1         | 1.89%   |
| Intel Core 2 Quad       | 1         | 1.89%   |
| Intel Core 2            | 1         | 1.89%   |
| AMD Ryzen Threadripper  | 1         | 1.89%   |
| AMD Ryzen 7             | 1         | 1.89%   |
| AMD FX                  | 1         | 1.89%   |
| AMD E1                  | 1         | 1.89%   |
| AMD A6                  | 1         | 1.89%   |
| AMD A4                  | 1         | 1.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 28        | 52.83%  |
| 4      | 14        | 26.42%  |
| 6      | 6         | 11.32%  |
| 8      | 2         | 3.77%   |
| 12     | 1         | 1.89%   |
| 3      | 1         | 1.89%   |
| 1      | 1         | 1.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 71.7%   |
| 1      | 15        | 28.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 53        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 50%     |
| 0x206a7    | 4         | 7.41%   |
| 0x906e9    | 2         | 3.7%    |
| 0x306d4    | 2         | 3.7%    |
| 0x306c3    | 2         | 3.7%    |
| 0x306a9    | 2         | 3.7%    |
| 0x1067a    | 2         | 3.7%    |
| 0xa0652    | 1         | 1.85%   |
| 0x706e5    | 1         | 1.85%   |
| 0x706a8    | 1         | 1.85%   |
| 0x706a1    | 1         | 1.85%   |
| 0x6fd      | 1         | 1.85%   |
| 0x6f6      | 1         | 1.85%   |
| 0x506e3    | 1         | 1.85%   |
| 0x40651    | 1         | 1.85%   |
| 0x08600106 | 1         | 1.85%   |
| 0x08108109 | 1         | 1.85%   |
| 0x06006705 | 1         | 1.85%   |
| 0x0600111f | 1         | 1.85%   |
| 0x06000852 | 1         | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 8         | 15.09%  |
| SandyBridge   | 6         | 11.32%  |
| IvyBridge     | 6         | 11.32%  |
| Haswell       | 6         | 11.32%  |
| Skylake       | 5         | 9.43%   |
| Broadwell     | 4         | 7.55%   |
| Penryn        | 3         | 5.66%   |
| Zen           | 2         | 3.77%   |
| Piledriver    | 2         | 3.77%   |
| Goldmont plus | 2         | 3.77%   |
| Core          | 2         | 3.77%   |
| CometLake     | 2         | 3.77%   |
| Zen+          | 1         | 1.89%   |
| Zen 2         | 1         | 1.89%   |
| Jaguar        | 1         | 1.89%   |
| IceLake       | 1         | 1.89%   |
| Excavator     | 1         | 1.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 59.42%  |
| Nvidia | 18        | 26.09%  |
| AMD    | 10        | 14.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 6.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 6.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 5.56%   |
| Intel HD Graphics 5500                                                        | 3         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 4.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 4.17%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 2.78%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.78%   |
| Intel HD Graphics 630                                                         | 2         | 2.78%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 2.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.78%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.39%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.39%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.39%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 1.39%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.39%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.39%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1         | 1.39%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.39%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.39%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.39%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 1.39%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.39%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.39%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.39%   |
| Intel HD Graphics 5300                                                        | 1         | 1.39%   |
| Intel HD Graphics 530                                                         | 1         | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 1.39%   |
| AMD Trinity 2 [Radeon HD 7480D]                                               | 1         | 1.39%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.39%   |
| AMD RS780L [Radeon 3000]                                                      | 1         | 1.39%   |
| AMD Renoir                                                                    | 1         | 1.39%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                                       | 1         | 1.39%   |
| AMD Picasso                                                                   | 1         | 1.39%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 47.17%  |
| Intel + Nvidia | 12        | 22.64%  |
| 1 x AMD        | 7         | 13.21%  |
| 1 x Nvidia     | 6         | 11.32%  |
| Intel + AMD    | 3         | 5.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 48        | 90.57%  |
| Proprietary | 5         | 9.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 74.07%  |
| 1.01-2.0   | 4         | 7.41%   |
| 0.51-1.0   | 4         | 7.41%   |
| 3.01-4.0   | 2         | 3.7%    |
| 0.01-0.5   | 2         | 3.7%    |
| 7.01-8.0   | 1         | 1.85%   |
| 2.01-3.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 9         | 16.36%  |
| AU Optronics            | 9         | 16.36%  |
| LG Display              | 8         | 14.55%  |
| Chimei Innolux          | 7         | 12.73%  |
| BOE                     | 6         | 10.91%  |
| Chi Mei Optoelectronics | 4         | 7.27%   |
| Hewlett-Packard         | 2         | 3.64%   |
| Apple                   | 2         | 3.64%   |
| Vizio                   | 1         | 1.82%   |
| Sony                    | 1         | 1.82%   |
| Sceptre                 | 1         | 1.82%   |
| Philips                 | 1         | 1.82%   |
| Goldstar                | 1         | 1.82%   |
| Dell                    | 1         | 1.82%   |
| AUS                     | 1         | 1.82%   |
| AOC                     | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 3.57%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                        | 1         | 1.79%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                       | 1         | 1.79%   |
| Sceptre LCD Monitor P30 2560x1080                                         | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 250x170mm 11.9-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 340x190mm 15.3-inch      | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.79%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch        | 1         | 1.79%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch        | 1         | 1.79%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                   | 1         | 1.79%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch               | 1         | 1.79%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.79%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch               | 1         | 1.79%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch              | 1         | 1.79%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch                | 1         | 1.79%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch          | 1         | 1.79%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                    | 1         | 1.79%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 310x170mm 13.9-inch           | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.79%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.79%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.79%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.79%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.79%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 1.79%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.79%   |
| AUS LCD Monitor VG259 1920x1080                                           | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO328E 1920x1080 344x193mm 15.5-inch            | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch             | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 1         | 1.79%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch            | 1         | 1.79%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 1.79%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                     | 1         | 1.79%   |
| AOC LCD Monitor 2217 1680x1050                                            | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 43.64%  |
| 1366x768 (WXGA)    | 16        | 29.09%  |
| 1280x800 (WXGA)    | 4         | 7.27%   |
| 1600x900 (HD+)     | 2         | 3.64%   |
| 1280x1024 (SXGA)   | 2         | 3.64%   |
| 3840x1080          | 1         | 1.82%   |
| 2560x1600          | 1         | 1.82%   |
| 2560x1440 (QHD)    | 1         | 1.82%   |
| 2560x1080          | 1         | 1.82%   |
| 2160x1440          | 1         | 1.82%   |
| 1680x1050 (WSXGA+) | 1         | 1.82%   |
| 1440x900 (WXGA+)   | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 41.07%  |
| 17      | 7         | 12.5%   |
| 14      | 7         | 12.5%   |
| 13      | 4         | 7.14%   |
| Unknown | 3         | 5.36%   |
| 31      | 2         | 3.57%   |
| 23      | 2         | 3.57%   |
| 12      | 2         | 3.57%   |
| 48      | 1         | 1.79%   |
| 42      | 1         | 1.79%   |
| 27      | 1         | 1.79%   |
| 24      | 1         | 1.79%   |
| 19      | 1         | 1.79%   |
| 18      | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 60%     |
| 351-400     | 7         | 12.73%  |
| 201-300     | 4         | 7.27%   |
| 501-600     | 3         | 5.45%   |
| Unknown     | 3         | 5.45%   |
| 601-700     | 2         | 3.64%   |
| 401-500     | 1         | 1.82%   |
| 1001-1500   | 1         | 1.82%   |
| 901-1000    | 1         | 1.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 77.78%  |
| 16/10   | 6         | 11.11%  |
| Unknown | 3         | 5.56%   |
| 6/5     | 1         | 1.85%   |
| 5/4     | 1         | 1.85%   |
| 32/9    | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 41.07%  |
| 81-90          | 10        | 17.86%  |
| 121-130        | 5         | 8.93%   |
| 201-250        | 3         | 5.36%   |
| Unknown        | 3         | 5.36%   |
| 61-70          | 2         | 3.57%   |
| 351-500        | 2         | 3.57%   |
| 141-150        | 2         | 3.57%   |
| 501-1000       | 2         | 3.57%   |
| 71-80          | 1         | 1.79%   |
| 301-350        | 1         | 1.79%   |
| 151-200        | 1         | 1.79%   |
| 131-140        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 20        | 37.04%  |
| 101-120 | 18        | 33.33%  |
| 51-100  | 11        | 20.37%  |
| Unknown | 3         | 5.56%   |
| 1-50    | 1         | 1.85%   |
| 161-240 | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 48        | 90.57%  |
| 2     | 5         | 9.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 29        | 32.22%  |
| Intel                             | 26        | 28.89%  |
| Qualcomm Atheros                  | 14        | 15.56%  |
| Broadcom                          | 7         | 7.78%   |
| TP-Link                           | 3         | 3.33%   |
| Ralink Technology                 | 2         | 2.22%   |
| Qualcomm Atheros Communications   | 2         | 2.22%   |
| Broadcom Limited                  | 2         | 2.22%   |
| Xiaomi                            | 1         | 1.11%   |
| Marvell Technology Group          | 1         | 1.11%   |
| Huawei Technologies               | 1         | 1.11%   |
| Ericsson Business Mobile Networks | 1         | 1.11%   |
| D-Link System                     | 1         | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 17        | 15.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 5         | 4.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.7%    |
| Intel Wireless 7265                                                     | 4         | 3.7%    |
| TP-Link TL-WN722N v2                                                    | 3         | 2.78%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 3         | 2.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 3         | 2.78%   |
| Intel Wireless 3160                                                     | 3         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 1.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.85%   |
| Intel Wireless 8260                                                     | 2         | 1.85%   |
| Intel Ethernet Connection I217-V                                        | 2         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.93%   |
| Intel Wireless 8265 / 8275                                              | 1         | 0.93%   |
| Intel Wireless 3165                                                     | 1         | 0.93%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.93%   |
| Intel PRO/100 VE Network Connection                                     | 1         | 0.93%   |
| Intel I211 Gigabit Network Connection                                   | 1         | 0.93%   |
| Intel I210 Gigabit Network Connection                                   | 1         | 0.93%   |
| Intel Ethernet controller                                               | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                        | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                    | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.93%   |
| Intel Centrino Wireless-N 105                                           | 1         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 0.93%   |
| Huawei SPN-AL00                                                         | 1         | 0.93%   |
| Ericsson Business Mobile Networks N5321 gw                              | 1         | 0.93%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 1         | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                | 1         | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 22        | 39.29%  |
| Qualcomm Atheros                | 11        | 19.64%  |
| Realtek Semiconductor           | 8         | 14.29%  |
| Broadcom                        | 5         | 8.93%   |
| TP-Link                         | 3         | 5.36%   |
| Ralink Technology               | 2         | 3.57%   |
| Qualcomm Atheros Communications | 2         | 3.57%   |
| Marvell Technology Group        | 1         | 1.79%   |
| D-Link System                   | 1         | 1.79%   |
| Broadcom Limited                | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 7.14%   |
| Intel Wireless 7265                                                     | 4         | 7.14%   |
| TP-Link TL-WN722N v2                                                    | 3         | 5.36%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 3         | 5.36%   |
| Intel Wireless 3160                                                     | 3         | 5.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 5.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 3.57%   |
| Intel Wireless 8260                                                     | 2         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 3.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 3.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.79%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.79%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.79%   |
| Intel Wireless 3165                                                     | 1         | 1.79%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.79%   |
| Intel Centrino Wireless-N 105                                           | 1         | 1.79%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.79%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 1.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 1         | 1.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 48.98%  |
| Intel                 | 13        | 26.53%  |
| Qualcomm Atheros      | 6         | 12.24%  |
| Broadcom              | 3         | 6.12%   |
| Xiaomi                | 1         | 2.04%   |
| Huawei Technologies   | 1         | 2.04%   |
| Broadcom Limited      | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.92%   |
| Intel Ethernet Connection I217-V                                  | 2         | 3.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.96%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.96%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.96%   |
| Intel Ethernet controller                                         | 1         | 1.96%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.96%   |
| Huawei SPN-AL00                                                   | 1         | 1.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.96%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 52.13%  |
| Ethernet | 44        | 46.81%  |
| Modem    | 1         | 1.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 67.16%  |
| Ethernet | 22        | 32.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 36        | 67.92%  |
| 1     | 15        | 28.3%   |
| 3     | 2         | 3.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 41        | 75.93%  |
| Yes  | 13        | 24.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 47.37%  |
| Qualcomm Atheros Communications | 7         | 18.42%  |
| Realtek Semiconductor           | 4         | 10.53%  |
| Broadcom                        | 3         | 7.89%   |
| Marvell Semiconductor           | 1         | 2.63%   |
| Lite-On Technology              | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| Dell                            | 1         | 2.63%   |
| Cambridge Silicon Radio         | 1         | 2.63%   |
| Apple                           | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 12        | 31.58%  |
| Intel Bluetooth wireless interface                  | 5         | 13.16%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 7.89%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5.26%   |
| Realtek Bluetooth Radio                             | 2         | 5.26%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.26%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.63%   |
| Lite-On Bluetooth Radio                             | 1         | 2.63%   |
| Intel AX200 Bluetooth                               | 1         | 2.63%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.63%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.63%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.63%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.63%   |
| Apple Bluetooth Host Controller                     | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 45        | 67.16%  |
| Nvidia              | 12        | 17.91%  |
| AMD                 | 9         | 13.43%  |
| C-Media Electronics | 1         | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 8.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 5.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.76%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 4.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.57%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 3.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 2.38%   |
| Intel CM238 HD Audio Controller                                            | 2         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.38%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.19%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.19%   |
| Intel USB PnP Sound Device                                                 | 1         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.19%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 1.19%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.19%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.19%   |
| AMD Polaris 22 HDMI Audio                                                  | 1         | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.19%   |
| AMD High Definition Audio Controller                                       | 1         | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 34.21%  |
| Unknown             | 4         | 10.53%  |
| SK Hynix            | 4         | 10.53%  |
| Kingston            | 3         | 7.89%   |
| Elpida              | 3         | 7.89%   |
| Crucial             | 3         | 7.89%   |
| Ramaxel Technology  | 2         | 5.26%   |
| S                   | 1         | 2.63%   |
| Nanya Technology    | 1         | 2.63%   |
| Micron Technology   | 1         | 2.63%   |
| G.Skill             | 1         | 2.63%   |
| Corsair             | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 5%      |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s     | 2         | 5%      |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.5%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1         | 2.5%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 2.5%    |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 2.5%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1         | 2.5%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.5%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.5%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.5%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s    | 1         | 2.5%    |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                | 1         | 2.5%    |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.5%    |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s     | 1         | 2.5%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 2.5%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 2.5%    |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 1         | 2.5%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s     | 1         | 2.5%    |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.5%    |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 1         | 2.5%    |
| S RAM Module 2GB DIMM DDR3 1600MT/s                          | 1         | 2.5%    |
| Ramaxel RAM RMT3170MN68F9F1600 4096MB SODIMM DDR3 1600MT/s   | 1         | 2.5%    |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s | 1         | 2.5%    |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s           | 1         | 2.5%    |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s    | 1         | 2.5%    |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s   | 1         | 2.5%    |
| Kingston RAM HP26D4S9S8MH-8 8GB SODIMM DDR4 2400MT/s         | 1         | 2.5%    |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 2.5%    |
| G.Skill RAM F4-2400C16-16GRS 16384MB SODIMM DDR4 2667MT/s    | 1         | 2.5%    |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.5%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s     | 1         | 2.5%    |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s     | 1         | 2.5%    |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s       | 1         | 2.5%    |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s    | 1         | 2.5%    |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s            | 1         | 2.5%    |
| Corsair RAM CMSO8GX3M1A1600C11 8192MB SODIMM DDR3 1600MT/s   | 1         | 2.5%    |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                  | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 48.48%  |
| DDR4    | 13        | 39.39%  |
| DDR2    | 2         | 6.06%   |
| LPDDR4  | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 30        | 90.91%  |
| DIMM   | 3         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 16        | 43.24%  |
| 8192  | 10        | 27.03%  |
| 2048  | 4         | 10.81%  |
| 16384 | 3         | 8.11%   |
| 32768 | 2         | 5.41%   |
| 1024  | 2         | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 12        | 35.29%  |
| 2667  | 9         | 26.47%  |
| 1334  | 3         | 8.82%   |
| 3266  | 2         | 5.88%   |
| 3200  | 2         | 5.88%   |
| 2400  | 2         | 5.88%   |
| 1333  | 1         | 2.94%   |
| 1067  | 1         | 2.94%   |
| 667   | 1         | 2.94%   |
| 533   | 1         | 2.94%   |

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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 28.95%  |
| Acer                                   | 7         | 18.42%  |
| Microdia                               | 4         | 10.53%  |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| IMC Networks                           | 2         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 5.26%   |
| Suyin                                  | 1         | 2.63%   |
| Silicon Motion                         | 1         | 2.63%   |
| Samsung Electronics                    | 1         | 2.63%   |
| Ricoh                                  | 1         | 2.63%   |
| Realtek Semiconductor                  | 1         | 2.63%   |
| Quanta                                 | 1         | 2.63%   |
| Microsoft                              | 1         | 2.63%   |
| Luxvisions Innotech Limited            | 1         | 2.63%   |
| DJKCVA1BIDQ8CL                         | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 7.69%   |
| Acer HD Webcam                                                             | 3         | 7.69%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 2.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.56%   |
| Sunplus HD WebCam                                                          | 1         | 2.56%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 2.56%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 2.56%   |
| Ricoh Pavilion Webcam                                                      | 1         | 2.56%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.56%   |
| Quanta HP High Definition 1MP Webcam                                       | 1         | 2.56%   |
| Microsoft LifeCam Rear                                                     | 1         | 2.56%   |
| Microsoft LifeCam Front                                                    | 1         | 2.56%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 2.56%   |
| Microdia PC Microscope camera                                              | 1         | 2.56%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 2.56%   |
| Microdia Integrated Webcam HD                                              | 1         | 2.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.56%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.56%   |
| DJKCVA1BIDQ8CL HP TrueVision HD Camera                                     | 1         | 2.56%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 2.56%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.56%   |
| Chicony Integrated Camera                                                  | 1         | 2.56%   |
| Chicony HP Webcam                                                          | 1         | 2.56%   |
| Chicony HP TrueVision HD                                                   | 1         | 2.56%   |
| Chicony HD Webcam                                                          | 1         | 2.56%   |
| Chicony HD User Facing                                                     | 1         | 2.56%   |
| Chicony CNF8248                                                            | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.56%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.56%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.56%   |
| Acer Integrated Camera                                                     | 1         | 2.56%   |
| Acer HD Camera                                                             | 1         | 2.56%   |
| Acer EasyCamera                                                            | 1         | 2.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 66.67%  |
| LighTuning Technology | 1         | 11.11%  |
| Elan Microelectronics | 1         | 11.11%  |
| AuthenTec             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner                                       | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 11.11%  |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 11.11%  |
| Elan ELAN:Fingerprint                                                      | 1         | 11.11%  |
| AuthenTec Fingerprint Sensor                                               | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 35        | 64.81%  |
| 1     | 12        | 22.22%  |
| 2     | 6         | 11.11%  |
| 3     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 36%     |
| Net/wireless          | 3         | 12%     |
| Graphics card         | 3         | 12%     |
| Chipcard              | 3         | 12%     |
| Storage               | 2         | 8%      |
| Multimedia controller | 2         | 8%      |
| Modem                 | 1         | 4%      |
| Camera                | 1         | 4%      |
| Bluetooth             | 1         | 4%      |

