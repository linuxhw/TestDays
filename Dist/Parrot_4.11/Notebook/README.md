Parrot 4.11 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| MSI           | GT60 2OC/2OD                | [5347580c37](https://linux-hardware.org/?probe=5347580c37) | Oct 08, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| MSI           | GS66 Stealth 10UG           | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Lenovo        | B50-80 80EW                 | [e3fd336b60](https://linux-hardware.org/?probe=e3fd336b60) | Aug 24, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| HP            | Pavilion dv6700             | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| HP            | Pavilion dv7                | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | Q524UQ                      | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| MSI           | GE73 Raider RGB 8RE         | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Quanta        | 3610D                       | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| Quanta        | 3610D                       | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| Acer          | Aspire E1-571G              | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Dell          | Inspiron 5420               | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| HP            | Pavilion dv6                | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.0-6parrot1-amd64    | 20        | 44.44%  |
| 5.10.0-8parrot1-amd64    | 13        | 28.89%  |
| 5.7.0-2parrot2-amd64     | 3         | 6.67%   |
| 5.10.0-5parrot1-amd64    | 3         | 6.67%   |
| 5.10.0-3parrot1-amd64    | 3         | 6.67%   |
| 5.14.0-2parrot1-amd64    | 1         | 2.22%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 2.22%   |
| Unknown                  | 1         | 2.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 40        | 88.89%  |
| 5.7.0   | 3         | 6.67%   |
| 5.14.0  | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 40        | 88.89%  |
| 5.7     | 3         | 6.67%   |
| 5.14    | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 44        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 25        | 56.82%  |
| KDE5    | 8         | 18.18%  |
| KDE     | 6         | 13.64%  |
| Unknown | 3         | 6.82%   |
| XFCE    | 1         | 2.27%   |
| LXDE    | 1         | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 44        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 42.22%  |
| TDM     | 17        | 37.78%  |
| LightDM | 8         | 17.78%  |
| SDDM    | 1         | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 20        | 45.45%  |
| en_GB   | 4         | 9.09%   |
| ru_RU   | 3         | 6.82%   |
| pt_BR   | 3         | 6.82%   |
| fr_FR   | 3         | 6.82%   |
| Unknown | 3         | 6.82%   |
| es_ES   | 2         | 4.55%   |
| nl_BE   | 1         | 2.27%   |
| id_ID   | 1         | 2.27%   |
| es_CO   | 1         | 2.27%   |
| en_AU   | 1         | 2.27%   |
| de_DE   | 1         | 2.27%   |
| cs_CZ   | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 31        | 68.89%  |
| EFI  | 14        | 31.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 35        | 79.55%  |
| Ext4  | 5         | 11.36%  |
| Xfs   | 4         | 9.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 16        | 36.36%  |
| Unknown | 16        | 36.36%  |
| MBR     | 12        | 27.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 81.82%  |
| Yes       | 8         | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 68.18%  |
| Yes       | 14        | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 25%     |
| Dell                | 6         | 13.64%  |
| ASUSTek Computer    | 6         | 13.64%  |
| MSI                 | 5         | 11.36%  |
| Lenovo              | 4         | 9.09%   |
| Acer                | 3         | 6.82%   |
| Samsung Electronics | 2         | 4.55%   |
| Apple               | 2         | 4.55%   |
| Wortmann AG         | 1         | 2.27%   |
| Quanta              | 1         | 2.27%   |
| Gateway             | 1         | 2.27%   |
| Fujitsu             | 1         | 2.27%   |
| Eluktronics         | 1         | 2.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 4.55%   |
| ASUS Q524UQ                             | 2         | 4.55%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 2.27%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 2.27%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 2.27%   |
| Quanta HDX PREMIUM SERIES               | 1         | 2.27%   |
| MSI GT60 2OC/2OD                        | 1         | 2.27%   |
| MSI GS66 Stealth 10UG                   | 1         | 2.27%   |
| MSI GE75 Raider 10SF                    | 1         | 2.27%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 2.27%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 2.27%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 2.27%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 2.27%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 2.27%   |
| Lenovo B50-80 80EW                      | 1         | 2.27%   |
| HP ZBook 15 G5                          | 1         | 2.27%   |
| HP Pavilion Notebook                    | 1         | 2.27%   |
| HP Pavilion dv7                         | 1         | 2.27%   |
| HP Pavilion dv6700                      | 1         | 2.27%   |
| HP Pavilion dv6                         | 1         | 2.27%   |
| HP Pavilion dv4                         | 1         | 2.27%   |
| HP Laptop 15s-eq1xxx                    | 1         | 2.27%   |
| HP Laptop 15-dw0xxx                     | 1         | 2.27%   |
| HP 250 G7 Notebook PC                   | 1         | 2.27%   |
| Gateway MP8708                          | 1         | 2.27%   |
| Fujitsu LIFEBOOK T731                   | 1         | 2.27%   |
| Eluktronics MAG-15u                     | 1         | 2.27%   |
| Dell Latitude E7440                     | 1         | 2.27%   |
| Dell Latitude E6420                     | 1         | 2.27%   |
| Dell Inspiron 7501                      | 1         | 2.27%   |
| Dell Inspiron 5593                      | 1         | 2.27%   |
| Dell Inspiron 5558                      | 1         | 2.27%   |
| Dell Inspiron 5420                      | 1         | 2.27%   |
| ASUS X75VB                              | 1         | 2.27%   |
| ASUS X450EA                             | 1         | 2.27%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 2.27%   |
| ASUS G74Sx                              | 1         | 2.27%   |
| Apple MacBookPro8,1                     | 1         | 2.27%   |
| Apple MacBookPro11,1                    | 1         | 2.27%   |
| Acer TravelMate 5720                    | 1         | 2.27%   |
| Acer Swift SF114-33                     | 1         | 2.27%   |
| Acer Aspire E1-571G                     | 1         | 2.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| HP Pavilion         | 5         | 11.36%  |
| Dell Inspiron       | 4         | 9.09%   |
| Lenovo ThinkPad     | 2         | 4.55%   |
| HP ProBook          | 2         | 4.55%   |
| HP Laptop           | 2         | 4.55%   |
| Dell Latitude       | 2         | 4.55%   |
| ASUS Q524UQ         | 2         | 4.55%   |
| Wortmann AG TERRA   | 1         | 2.27%   |
| Samsung 350V5C      | 1         | 2.27%   |
| Samsung 300E4C      | 1         | 2.27%   |
| Quanta HDX          | 1         | 2.27%   |
| MSI GT60            | 1         | 2.27%   |
| MSI GS66            | 1         | 2.27%   |
| MSI GE75            | 1         | 2.27%   |
| MSI GE73            | 1         | 2.27%   |
| MSI GE63            | 1         | 2.27%   |
| Lenovo Y520-15IKBN  | 1         | 2.27%   |
| Lenovo B50-80       | 1         | 2.27%   |
| HP ZBook            | 1         | 2.27%   |
| HP 250              | 1         | 2.27%   |
| Gateway MP8708      | 1         | 2.27%   |
| Fujitsu LIFEBOOK    | 1         | 2.27%   |
| Eluktronics MAG-15u | 1         | 2.27%   |
| ASUS X75VB          | 1         | 2.27%   |
| ASUS X450EA         | 1         | 2.27%   |
| ASUS VivoBook       | 1         | 2.27%   |
| ASUS G74Sx          | 1         | 2.27%   |
| Apple MacBookPro8   | 1         | 2.27%   |
| Apple MacBookPro11  | 1         | 2.27%   |
| Acer TravelMate     | 1         | 2.27%   |
| Acer Swift          | 1         | 2.27%   |
| Acer Aspire         | 1         | 2.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 18.18%  |
| 2019 | 6         | 13.64%  |
| 2018 | 5         | 11.36%  |
| 2013 | 5         | 11.36%  |
| 2021 | 3         | 6.82%   |
| 2016 | 3         | 6.82%   |
| 2015 | 3         | 6.82%   |
| 2012 | 3         | 6.82%   |
| 2011 | 2         | 4.55%   |
| 2010 | 2         | 4.55%   |
| 2008 | 2         | 4.55%   |
| 2017 | 1         | 2.27%   |
| 2006 | 1         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 44        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 44        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 44        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 29.55%  |
| 8.01-16.0   | 11        | 25%     |
| 3.01-4.0    | 8         | 18.18%  |
| 16.01-24.0  | 6         | 13.64%  |
| 64.01-256.0 | 2         | 4.55%   |
| 32.01-64.0  | 1         | 2.27%   |
| 24.01-32.0  | 1         | 2.27%   |
| 2.01-3.0    | 1         | 2.27%   |
| 1.01-2.0    | 1         | 2.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 2.01-3.0 | 17        | 36.96%  |
| 1.01-2.0 | 17        | 36.96%  |
| 3.01-4.0 | 7         | 15.22%  |
| 4.01-8.0 | 5         | 10.87%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 61.36%  |
| 2      | 14        | 31.82%  |
| 3      | 3         | 6.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 56.82%  |
| Yes       | 19        | 43.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 81.82%  |
| No        | 8         | 18.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 97.73%  |
| No        | 1         | 2.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 75%     |
| No        | 11        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 13        | 29.55%  |
| Spain        | 4         | 9.09%   |
| Germany      | 3         | 6.82%   |
| France       | 3         | 6.82%   |
| UK           | 2         | 4.55%   |
| Russia       | 2         | 4.55%   |
| Brazil       | 2         | 4.55%   |
| Sweden       | 1         | 2.27%   |
| South Africa | 1         | 2.27%   |
| Puerto Rico  | 1         | 2.27%   |
| Mexico       | 1         | 2.27%   |
| Kenya        | 1         | 2.27%   |
| Iraq         | 1         | 2.27%   |
| Indonesia    | 1         | 2.27%   |
| Hungary      | 1         | 2.27%   |
| Czechia      | 1         | 2.27%   |
| Colombia     | 1         | 2.27%   |
| Canada       | 1         | 2.27%   |
| Belgium      | 1         | 2.27%   |
| Bangladesh   | 1         | 2.27%   |
| Azerbaijan   | 1         | 2.27%   |
| Australia    | 1         | 2.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chicago                  | 2         | 4.44%   |
| Witbank                  | 1         | 2.22%   |
| West Jordan              | 1         | 2.22%   |
| Visalia                  | 1         | 2.22%   |
| Stockholm                | 1         | 2.22%   |
| Sinntal                  | 1         | 2.22%   |
| Sheffield                | 1         | 2.22%   |
| Secaucus                 | 1         | 2.22%   |
| Santo André             | 1         | 2.22%   |
| Sannois                  | 1         | 2.22%   |
| Regensburg               | 1         | 2.22%   |
| Prague                   | 1         | 2.22%   |
| Ponce                    | 1         | 2.22%   |
| Oklahoma City            | 1         | 2.22%   |
| Nairobi                  | 1         | 2.22%   |
| Mostoles                 | 1         | 2.22%   |
| Marietta                 | 1         | 2.22%   |
| Majadahonda              | 1         | 2.22%   |
| Lyon                     | 1         | 2.22%   |
| Los Mochis               | 1         | 2.22%   |
| Long Beach               | 1         | 2.22%   |
| London                   | 1         | 2.22%   |
| Kazan?��                 | 1         | 2.22%   |
| Jihlava                  | 1         | 2.22%   |
| Jaragua                  | 1         | 2.22%   |
| Jakarta                  | 1         | 2.22%   |
| Houston                  | 1         | 2.22%   |
| Frankfurt am Main        | 1         | 2.22%   |
| Fort Lauderdale          | 1         | 2.22%   |
| Erbil                    | 1         | 2.22%   |
| Edmonton                 | 1         | 2.22%   |
| East Malvern             | 1         | 2.22%   |
| Donostia / San Sebastian | 1         | 2.22%   |
| Dhaka                    | 1         | 2.22%   |
| Denham Springs           | 1         | 2.22%   |
| Concord                  | 1         | 2.22%   |
| Budapest                 | 1         | 2.22%   |
| Bogotá                  | 1         | 2.22%   |
| Blagoveshchensk          | 1         | 2.22%   |
| Bay Saint Louis          | 1         | 2.22%   |
| Barcelona                | 1         | 2.22%   |
| Baku                     | 1         | 2.22%   |
| Aix-les-Bains            | 1         | 2.22%   |
| Aalst                    | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 8      | 9.84%   |
| Seagate             | 6         | 6      | 9.84%   |
| Samsung Electronics | 6         | 7      | 9.84%   |
| Crucial             | 6         | 9      | 9.84%   |
| Unknown             | 5         | 5      | 8.2%    |
| Toshiba             | 5         | 6      | 8.2%    |
| Kingston            | 5         | 5      | 8.2%    |
| Hitachi             | 3         | 3      | 4.92%   |
| HGST                | 3         | 3      | 4.92%   |
| A-DATA Technology   | 3         | 3      | 4.92%   |
| SK Hynix            | 2         | 2      | 3.28%   |
| SanDisk             | 2         | 2      | 3.28%   |
| Micron Technology   | 2         | 2      | 3.28%   |
| KIOXIA              | 2         | 2      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| Patriot             | 1         | 1      | 1.64%   |
| Corsair             | 1         | 1      | 1.64%   |
| Apple               | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 3.13%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 2         | 3.13%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 3.13%   |
| HGST HTS541010A9E680 1TB                 | 2         | 3.13%   |
| Crucial CT1000MX500SSD1 1TB              | 2         | 3.13%   |
| WDC WD800BEVS-22RST0 80GB                | 1         | 1.56%   |
| WDC WD3200LPVX-00V0TT0 320GB             | 1         | 1.56%   |
| WDC WD2500BPVT-00JJ5T0 250GB             | 1         | 1.56%   |
| WDC WD10SPZX-17Z10T1 1TB                 | 1         | 1.56%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB     | 1         | 1.56%   |
| Unknown Y016B  16GB                      | 1         | 1.56%   |
| Unknown xD/SD/M.S.                       | 1         | 1.56%   |
| Unknown SS16G  16GB                      | 1         | 1.56%   |
| Unknown SDU1  64GB                       | 1         | 1.56%   |
| Unknown MMC Card  128GB                  | 1         | 1.56%   |
| Toshiba THNSNF128GMCS 128GB SSD          | 1         | 1.56%   |
| Toshiba Q300. 480GB SSD                  | 1         | 1.56%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 1.56%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1.56%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1.56%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB        | 1         | 1.56%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 1.56%   |
| Seagate ST9500420AS 500GB                | 1         | 1.56%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1.56%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.56%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1.56%   |
| SanDisk Extreme SSD 1TB                  | 1         | 1.56%   |
| Samsung SSD 980 1TB                      | 1         | 1.56%   |
| Samsung SSD 860 EVO 500GB                | 1         | 1.56%   |
| Samsung PM963 2.5" NVMe PCIe SSD 512GB   | 1         | 1.56%   |
| Samsung MZVLW256HEHP-00000 256GB         | 1         | 1.56%   |
| Samsung MZVLQ256HAJD-00000 256GB         | 1         | 1.56%   |
| Samsung MZVLB1T0HALR 1TB SSD             | 1         | 1.56%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD     | 1         | 1.56%   |
| Patriot P210 256GB SSD                   | 1         | 1.56%   |
| Micron MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1.56%   |
| Micron 2200_MTFDHBA512TCK 512GB          | 1         | 1.56%   |
| KIOXIA KBG40ZNV256G 256GB                | 1         | 1.56%   |
| KIOXIA KBG40ZNS512G NVMe 512GB           | 1         | 1.56%   |
| Kingston SV300S37A240G 240GB SSD         | 1         | 1.56%   |
| Kingston SKC400S37512G 512GB SSD         | 1         | 1.56%   |
| Kingston SA2000M8500G 500GB              | 1         | 1.56%   |
| Hitachi HTS545025A7E380 250GB            | 1         | 1.56%   |
| Hitachi HTS542525K9SA00 250GB            | 1         | 1.56%   |
| Hitachi HTS542512K9SA00 120GB            | 1         | 1.56%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1.56%   |
| Crucial CT500MX500SSD1 500GB             | 1         | 1.56%   |
| Crucial CT480BX500SSD1 480GB             | 1         | 1.56%   |
| Crucial CT275MX300SSD1 275GB             | 1         | 1.56%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 1.56%   |
| Crucial CT250MX200SSD1 250GB             | 1         | 1.56%   |
| Corsair Force 3 SSD 180GB                | 1         | 1.56%   |
| China SATA SSD 120GB                     | 1         | 1.56%   |
| China MSATA 480GB SSD                    | 1         | 1.56%   |
| Apple SSD SM0512F 500GB                  | 1         | 1.56%   |
| A-DATA SX6000LNP 1TB                     | 1         | 1.56%   |
| A-DATA SU650 120GB SSD                   | 1         | 1.56%   |
| A-DATA IM2P33F3 NVMe 512GB               | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 7      | 28.57%  |
| Seagate | 6         | 6      | 28.57%  |
| Toshiba | 3         | 3      | 14.29%  |
| Hitachi | 3         | 3      | 14.29%  |
| HGST    | 3         | 3      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 9      | 25%     |
| Kingston            | 4         | 4      | 16.67%  |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Toshiba             | 2         | 3      | 8.33%   |
| SanDisk             | 2         | 2      | 8.33%   |
| China               | 2         | 2      | 8.33%   |
| Patriot             | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| Corsair             | 1         | 1      | 4.17%   |
| Apple               | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 20        | 28     | 35.09%  |
| HDD     | 20        | 22     | 35.09%  |
| NVMe    | 12        | 13     | 21.05%  |
| MMC     | 4         | 4      | 7.02%   |
| Unknown | 1         | 1      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 36        | 47     | 65.45%  |
| NVMe | 12        | 13     | 21.82%  |
| MMC  | 4         | 4      | 7.27%   |
| SAS  | 3         | 4      | 5.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 32     | 60.98%  |
| 0.51-1.0   | 13        | 15     | 31.71%  |
| 1.01-2.0   | 3         | 3      | 7.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 11        | 25%     |
| 101-250        | 10        | 22.73%  |
| 501-1000       | 7         | 15.91%  |
| 1001-2000      | 6         | 13.64%  |
| Unknown        | 5         | 11.36%  |
| More than 3000 | 2         | 4.55%   |
| 51-100         | 2         | 4.55%   |
| 2001-3000      | 1         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 13        | 28.89%  |
| 21-50     | 11        | 24.44%  |
| 251-500   | 6         | 13.33%  |
| Unknown   | 5         | 11.11%  |
| 101-250   | 4         | 8.89%   |
| 1-20      | 4         | 8.89%   |
| 1001-2000 | 1         | 2.22%   |
| 501-1000  | 1         | 2.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 16.67%  |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 16.67%  |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 16.67%  |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 16.67%  |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 16.67%  |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 16.67%  |
| Seagate             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |
| A-DATA Technology   | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 50%     |
| SSD  | 2         | 2      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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
| Works    | 23        | 30     | 46.94%  |
| Detected | 21        | 32     | 42.86%  |
| Malfunc  | 5         | 6      | 10.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 72.73%  |
| Samsung Electronics         | 4         | 7.27%   |
| SK Hynix                    | 2         | 3.64%   |
| KIOXIA                      | 2         | 3.64%   |
| AMD                         | 2         | 3.64%   |
| Sandisk                     | 1         | 1.82%   |
| Realtek Semiconductor       | 1         | 1.82%   |
| Micron Technology           | 1         | 1.82%   |
| Kingston Technology Company | 1         | 1.82%   |
| ADATA Technology            | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 6.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 5%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 5%      |
| SK Hynix BC511                                                                         | 2         | 3.33%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 3.33%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 3.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 3.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 3.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 3.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.67%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.67%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 1.67%   |
| Micron Non-Volatile memory controller                                                  | 1         | 1.67%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.67%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.67%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.67%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 1.67%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 68.97%  |
| NVMe | 12        | 20.69%  |
| IDE  | 4         | 6.9%    |
| RAID | 2         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 93.18%  |
| AMD    | 3         | 6.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 4.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 4.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 4.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 4.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 4.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 4.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 4.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 4.55%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 2.27%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 2.27%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 2.27%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 2.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 2.27%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 2.27%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 2.27%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 2.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 2.27%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 2.27%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 2.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 2.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 2.27%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 2.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 2.27%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 2.27%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 2.27%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 2.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 2.27%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 2.27%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 2.27%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 2.27%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 2.27%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 2.27%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 1         | 2.27%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 1         | 2.27%   |
| AMD E1-2500 APU with Radeon HD Graphics     | 1         | 2.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 16        | 36.36%  |
| Intel Core i5           | 16        | 36.36%  |
| Intel Pentium Silver    | 2         | 4.55%   |
| Intel Core i3           | 2         | 4.55%   |
| Intel Core 2 Duo        | 2         | 4.55%   |
| Intel Pentium Dual-Core | 1         | 2.27%   |
| Intel Core 2 Quad       | 1         | 2.27%   |
| Intel Core 2            | 1         | 2.27%   |
| AMD Ryzen 7             | 1         | 2.27%   |
| AMD Ryzen 3             | 1         | 2.27%   |
| AMD E1                  | 1         | 2.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 25        | 56.82%  |
| 4      | 13        | 29.55%  |
| 6      | 4         | 9.09%   |
| 8      | 2         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 33        | 75%     |
| 1      | 11        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 44        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 46.67%  |
| 0x206a7    | 4         | 8.89%   |
| 0x306c3    | 3         | 6.67%   |
| 0xa0652    | 2         | 4.44%   |
| 0x306d4    | 2         | 4.44%   |
| 0x1067a    | 2         | 4.44%   |
| 0x906e9    | 1         | 2.22%   |
| 0x806ec    | 1         | 2.22%   |
| 0x706e5    | 1         | 2.22%   |
| 0x706a8    | 1         | 2.22%   |
| 0x706a1    | 1         | 2.22%   |
| 0x6fd      | 1         | 2.22%   |
| 0x6f6      | 1         | 2.22%   |
| 0x506e3    | 1         | 2.22%   |
| 0x306a9    | 1         | 2.22%   |
| 0x08600106 | 1         | 2.22%   |
| 0x08108109 | 1         | 2.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 6         | 13.64%  |
| KabyLake      | 6         | 13.64%  |
| Skylake       | 5         | 11.36%  |
| IvyBridge     | 5         | 11.36%  |
| Haswell       | 5         | 11.36%  |
| Penryn        | 3         | 6.82%   |
| CometLake     | 3         | 6.82%   |
| Broadwell     | 3         | 6.82%   |
| Goldmont plus | 2         | 4.55%   |
| Core          | 2         | 4.55%   |
| Zen+          | 1         | 2.27%   |
| Zen 2         | 1         | 2.27%   |
| Jaguar        | 1         | 2.27%   |
| IceLake       | 1         | 2.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 63.33%  |
| Nvidia | 16        | 26.67%  |
| AMD    | 6         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 7.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 7.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 6.35%   |
| Intel HD Graphics 5500                                                        | 3         | 4.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 4.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 4.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 3.17%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 3.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 3.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 3.17%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 3.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 3.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 3.17%   |
| Nvidia TU117M                                                                 | 1         | 1.59%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.59%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.59%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.59%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.59%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.59%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.59%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.59%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.59%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.59%   |
| Intel HD Graphics 630                                                         | 1         | 1.59%   |
| Intel HD Graphics 530                                                         | 1         | 1.59%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.59%   |
| AMD Renoir                                                                    | 1         | 1.59%   |
| AMD Picasso                                                                   | 1         | 1.59%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 50%     |
| Intel + Nvidia | 13        | 29.55%  |
| 1 x Nvidia     | 3         | 6.82%   |
| Intel + AMD    | 3         | 6.82%   |
| 1 x AMD        | 3         | 6.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 42        | 95.45%  |
| Proprietary | 2         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 79.55%  |
| 0.51-1.0   | 3         | 6.82%   |
| 3.01-4.0   | 2         | 4.55%   |
| 1.01-2.0   | 2         | 4.55%   |
| 2.01-3.0   | 1         | 2.27%   |
| 0.01-0.5   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 9         | 19.57%  |
| LG Display              | 8         | 17.39%  |
| Chimei Innolux          | 8         | 17.39%  |
| Samsung Electronics     | 7         | 15.22%  |
| BOE                     | 7         | 15.22%  |
| Chi Mei Optoelectronics | 4         | 8.7%    |
| Apple                   | 2         | 4.35%   |
| Dell                    | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 4.35%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 340x190mm 15.3-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 2.17%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch               | 1         | 2.17%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch              | 1         | 2.17%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 310x170mm 13.9-inch           | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 2.17%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE089B 1280x800 261x163mm 12.1-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 2.17%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO328E 1920x1080 344x193mm 15.5-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch            | 1         | 2.17%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 2.17%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                     | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 20        | 43.48%  |
| 1366x768 (WXGA)  | 17        | 36.96%  |
| 1280x800 (WXGA)  | 4         | 8.7%    |
| 1600x900 (HD+)   | 2         | 4.35%   |
| 2560x1600        | 1         | 2.17%   |
| 1440x900 (WXGA+) | 1         | 2.17%   |
| 1280x1024 (SXGA) | 1         | 2.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 24        | 52.17%  |
| 14     | 7         | 15.22%  |
| 17     | 6         | 13.04%  |
| 13     | 4         | 8.7%    |
| 12     | 2         | 4.35%   |
| 31     | 1         | 2.17%   |
| 19     | 1         | 2.17%   |
| 18     | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 71.74%  |
| 351-400     | 7         | 15.22%  |
| 201-300     | 4         | 8.7%    |
| 601-700     | 1         | 2.17%   |
| 401-500     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 38        | 84.44%  |
| 16/10 | 6         | 13.33%  |
| 6/5   | 1         | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 52.17%  |
| 81-90          | 10        | 21.74%  |
| 121-130        | 5         | 10.87%  |
| 61-70          | 2         | 4.35%   |
| 71-80          | 1         | 2.17%   |
| 351-500        | 1         | 2.17%   |
| 151-200        | 1         | 2.17%   |
| 141-150        | 1         | 2.17%   |
| 131-140        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 21        | 45.65%  |
| 101-120 | 18        | 39.13%  |
| 51-100  | 5         | 10.87%  |
| 1-50    | 1         | 2.17%   |
| 161-240 | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 41        | 93.18%  |
| 2     | 3         | 6.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 23        | 30.67%  |
| Realtek Semiconductor             | 21        | 28%     |
| Qualcomm Atheros                  | 14        | 18.67%  |
| Broadcom                          | 7         | 9.33%   |
| TP-Link                           | 2         | 2.67%   |
| Xiaomi                            | 1         | 1.33%   |
| Samsung Electronics               | 1         | 1.33%   |
| Ralink Technology                 | 1         | 1.33%   |
| Qualcomm Atheros Communications   | 1         | 1.33%   |
| NetGear                           | 1         | 1.33%   |
| Huawei Technologies               | 1         | 1.33%   |
| Ericsson Business Mobile Networks | 1         | 1.33%   |
| Broadcom Limited                  | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 12        | 13.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 5         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 4         | 4.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 3.33%   |
| Intel Wireless 7265                                                       | 3         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 3         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 3.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 2         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 2.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.22%   |
| Intel Wireless 8260                                                       | 2         | 2.22%   |
| Intel Wireless 3160                                                       | 2         | 2.22%   |
| Intel Ethernet Connection I217-V                                          | 2         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 2.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 1.11%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.11%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.11%   |
| Intel Wireless 3165                                                       | 1         | 1.11%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.11%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 1.11%   |
| Intel Ethernet controller                                                 | 1         | 1.11%   |
| Intel Ethernet Connection I219-V                                          | 1         | 1.11%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 1.11%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.11%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 1         | 1.11%   |
| Huawei BLA-L29                                                            | 1         | 1.11%   |
| Ericsson Business Mobile Networks N5321 gw                                | 1         | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                         | 1         | 1.11%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                    | 1         | 1.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                           | 1         | 1.11%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.11%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.11%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 42.86%  |
| Qualcomm Atheros                | 11        | 22.45%  |
| Realtek Semiconductor           | 6         | 12.24%  |
| Broadcom                        | 5         | 10.2%   |
| TP-Link                         | 2         | 4.08%   |
| Ralink Technology               | 1         | 2.04%   |
| Qualcomm Atheros Communications | 1         | 2.04%   |
| NetGear                         | 1         | 2.04%   |
| Broadcom Limited                | 1         | 2.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 4         | 8.16%   |
| Intel Wireless 7265                                                       | 3         | 6.12%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 3         | 6.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 6.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 4.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 4.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 4.08%   |
| Intel Wireless 8260                                                       | 2         | 4.08%   |
| Intel Wireless 3160                                                       | 2         | 4.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 4.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 4.08%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 2.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 2.04%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 2.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 2.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 2.04%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 2.04%   |
| Intel Wireless 3165                                                       | 1         | 2.04%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 2.04%   |
| Intel Centrino Wireless-N 105                                             | 1         | 2.04%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 2.04%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 2.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 2.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 18        | 46.15%  |
| Intel                 | 9         | 23.08%  |
| Qualcomm Atheros      | 6         | 15.38%  |
| Broadcom              | 3         | 7.69%   |
| Xiaomi                | 1         | 2.56%   |
| Samsung Electronics   | 1         | 2.56%   |
| Huawei Technologies   | 1         | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 30%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 12.5%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 7.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 5%      |
| Intel Ethernet Connection I217-V                                  | 2         | 5%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.5%    |
| Intel PRO/100 VE Network Connection                               | 1         | 2.5%    |
| Intel Ethernet controller                                         | 1         | 2.5%    |
| Intel Ethernet Connection I219-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.5%    |
| Huawei BLA-L29                                                    | 1         | 2.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 53.75%  |
| Ethernet | 36        | 45%     |
| Modem    | 1         | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 67.86%  |
| Ethernet | 18        | 32.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 34        | 77.27%  |
| 1     | 10        | 22.73%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 71.11%  |
| Yes  | 13        | 28.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 48.48%  |
| Qualcomm Atheros Communications | 7         | 21.21%  |
| Broadcom                        | 3         | 9.09%   |
| Realtek Semiconductor           | 2         | 6.06%   |
| Lite-On Technology              | 1         | 3.03%   |
| Foxconn / Hon Hai               | 1         | 3.03%   |
| Dell                            | 1         | 3.03%   |
| Cambridge Silicon Radio         | 1         | 3.03%   |
| Apple                           | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 18.18%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 15.15%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 9.09%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 6.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 6.06%   |
| Intel Bluetooth Device                              | 2         | 6.06%   |
| Intel AX201 Bluetooth                               | 2         | 6.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 3.03%   |
| Realtek Bluetooth Radio                             | 1         | 3.03%   |
| Lite-On Bluetooth Radio                             | 1         | 3.03%   |
| Intel AX200 Bluetooth                               | 1         | 3.03%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 3.03%   |
| Dell DW375 Bluetooth Module                         | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.03%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 3.03%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 3.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.03%   |
| Apple Bluetooth Host Controller                     | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 75.93%  |
| Nvidia | 10        | 18.52%  |
| AMD    | 3         | 5.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 7.58%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 4.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 4.55%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 4.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 4.55%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 4.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 3.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 3.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 3.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 3.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 3.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 3.03%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.03%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2         | 3.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.52%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.52%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.52%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.52%   |
| Intel USB PnP Sound Device                                                 | 1         | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.52%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.52%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 39.39%  |
| Unknown             | 3         | 9.09%   |
| SK Hynix            | 3         | 9.09%   |
| ELPIDA              | 3         | 9.09%   |
| Ramaxel Technology  | 2         | 6.06%   |
| Kingston            | 2         | 6.06%   |
| Crucial             | 2         | 6.06%   |
| A-DATA Technology   | 2         | 6.06%   |
| Micron Technology   | 1         | 3.03%   |
| G.Skill             | 1         | 3.03%   |
| Corsair             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 5.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 5.71%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 2.86%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 1         | 2.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                | 1         | 2.86%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 2.86%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 1         | 2.86%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s | 1         | 2.86%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s         | 1         | 2.86%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s   | 1         | 2.86%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.86%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s     | 1         | 2.86%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s        | 1         | 2.86%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s            | 1         | 2.86%   |
| Corsair RAM CMSO8GX3M1A1600C11 8192MB SODIMM DDR3 1600MT/s   | 1         | 2.86%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                  | 1         | 2.86%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s         | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 13        | 46.43%  |
| DDR4   | 12        | 42.86%  |
| DDR2   | 2         | 7.14%   |
| LPDDR4 | 1         | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 28        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 13        | 40.63%  |
| 8192  | 10        | 31.25%  |
| 16384 | 3         | 9.38%   |
| 2048  | 3         | 9.38%   |
| 1024  | 2         | 6.25%   |
| 32768 | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 9         | 31.03%  |
| 1600  | 8         | 27.59%  |
| 1334  | 3         | 10.34%  |
| 3266  | 2         | 6.9%    |
| 3200  | 2         | 6.9%    |
| 2400  | 1         | 3.45%   |
| 1333  | 1         | 3.45%   |
| 1067  | 1         | 3.45%   |
| 667   | 1         | 3.45%   |
| 533   | 1         | 3.45%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 28.95%  |
| Acer                                   | 7         | 18.42%  |
| Microdia                               | 4         | 10.53%  |
| Cheng Uei Precision Industry (Foxlink) | 3         | 7.89%   |
| Sunplus Innovation Technology          | 2         | 5.26%   |
| Realtek Semiconductor                  | 2         | 5.26%   |
| Luxvisions Innotech Limited            | 2         | 5.26%   |
| IMC Networks                           | 2         | 5.26%   |
| Suyin                                  | 1         | 2.63%   |
| Silicon Motion                         | 1         | 2.63%   |
| Samsung Electronics                    | 1         | 2.63%   |
| Ricoh                                  | 1         | 2.63%   |
| Apple                                  | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 7.89%   |
| Acer HD Webcam                                                             | 3         | 7.89%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 5.26%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 5.26%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 2.63%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.63%   |
| Sunplus HD WebCam                                                          | 1         | 2.63%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 2.63%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 2.63%   |
| Ricoh Pavilion Webcam                                                      | 1         | 2.63%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 2.63%   |
| Microdia PC Microscope camera                                              | 1         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 2.63%   |
| Microdia Integrated Webcam HD                                              | 1         | 2.63%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.63%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.63%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 2.63%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.63%   |
| Chicony Integrated Camera                                                  | 1         | 2.63%   |
| Chicony HP Webcam                                                          | 1         | 2.63%   |
| Chicony HP TrueVision HD                                                   | 1         | 2.63%   |
| Chicony HD Webcam                                                          | 1         | 2.63%   |
| Chicony HD User Facing                                                     | 1         | 2.63%   |
| Chicony CNF8248                                                            | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 2.63%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.63%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.63%   |
| Acer Integrated Camera                                                     | 1         | 2.63%   |
| Acer HD Camera                                                             | 1         | 2.63%   |
| Acer EasyCamera                                                            | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 66.67%  |
| LighTuning Technology | 1         | 11.11%  |
| Elan Microelectronics | 1         | 11.11%  |
| AuthenTec             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 26        | 57.78%  |
| 1     | 12        | 26.67%  |
| 2     | 6         | 13.33%  |
| 3     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
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

