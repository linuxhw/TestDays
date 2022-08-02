Parrot 4.11 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

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

Total: 78

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 850 G6            | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Timi          | TM1613                      | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| Dell          | Inspiron 15 5510            | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Sony          | SVP1321L1EBI                | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| GPU Compan... | GWTN141-10                  | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| HP            | EliteBook 8470p             | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Dell          | Precision M4600             | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Toxic         | GM7MQ8P                     | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| Toshiba       | Satellite L655              | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Dell          | Vostro 5470                 | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
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
| HP            | HDX PREMIUM SERIES          | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
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
| 5.10.0-6parrot1-amd64    | 24        | 38.1%   |
| 5.10.0-8parrot1-amd64    | 14        | 22.22%  |
| 5.14.0-9parrot1-amd64    | 9         | 14.29%  |
| 5.7.0-2parrot2-amd64     | 3         | 4.76%   |
| 5.10.0-5parrot1-amd64    | 3         | 4.76%   |
| 5.10.0-3parrot1-amd64    | 3         | 4.76%   |
| 5.14.0-2parrot1-amd64    | 2         | 3.17%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.59%   |
| 5.16.0-12parrot1-amd64   | 1         | 1.59%   |
| 5.15.0-15parrot1-amd64   | 1         | 1.59%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.59%   |
| Unknown                  | 1         | 1.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 45        | 71.43%  |
| 5.14.0  | 11        | 17.46%  |
| 5.7.0   | 3         | 4.76%   |
| 5.6.0   | 1         | 1.59%   |
| 5.16.0  | 1         | 1.59%   |
| 5.15.0  | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 45        | 71.43%  |
| 5.14    | 11        | 17.46%  |
| 5.7     | 3         | 4.76%   |
| 5.6     | 1         | 1.59%   |
| 5.16    | 1         | 1.59%   |
| 5.15    | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 62        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 39        | 62.9%   |
| KDE5    | 12        | 19.35%  |
| KDE     | 6         | 9.68%   |
| Unknown | 3         | 4.84%   |
| XFCE    | 1         | 1.61%   |
| LXDE    | 1         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 62        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 26        | 41.27%  |
| Unknown | 19        | 30.16%  |
| TDM     | 17        | 26.98%  |
| SDDM    | 1         | 1.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 32        | 51.61%  |
| en_GB   | 6         | 9.68%   |
| fr_FR   | 5         | 8.06%   |
| ru_RU   | 3         | 4.84%   |
| pt_BR   | 3         | 4.84%   |
| Unknown | 3         | 4.84%   |
| es_ES   | 2         | 3.23%   |
| de_DE   | 2         | 3.23%   |
| nl_BE   | 1         | 1.61%   |
| id_ID   | 1         | 1.61%   |
| es_CO   | 1         | 1.61%   |
| en_NG   | 1         | 1.61%   |
| en_AU   | 1         | 1.61%   |
| cs_CZ   | 1         | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 36        | 57.14%  |
| EFI  | 27        | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 48        | 77.42%  |
| Ext4    | 8         | 12.9%   |
| Xfs     | 5         | 8.06%   |
| Overlay | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 27        | 43.55%  |
| Unknown | 19        | 30.65%  |
| MBR     | 16        | 25.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 79.03%  |
| Yes       | 13        | 20.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 62.9%   |
| Yes       | 23        | 37.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 24.19%  |
| Dell                | 10        | 16.13%  |
| Lenovo              | 9         | 14.52%  |
| ASUSTek Computer    | 6         | 9.68%   |
| MSI                 | 4         | 6.45%   |
| Acer                | 3         | 4.84%   |
| Samsung Electronics | 2         | 3.23%   |
| Apple               | 2         | 3.23%   |
| Wortmann AG         | 1         | 1.61%   |
| Toxic               | 1         | 1.61%   |
| Toshiba             | 1         | 1.61%   |
| Timi                | 1         | 1.61%   |
| Sony                | 1         | 1.61%   |
| Positivo            | 1         | 1.61%   |
| GPU Company         | 1         | 1.61%   |
| Gateway             | 1         | 1.61%   |
| Fujitsu             | 1         | 1.61%   |
| Eluktronics         | 1         | 1.61%   |
| Alienware           | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP ProBook 650 G1                        | 2         | 3.23%   |
| ASUS Q524UQ                              | 2         | 3.23%   |
| Wortmann AG TERRA_MOBILE_1542            | 1         | 1.61%   |
| Toxic GM7MQ8P                            | 1         | 1.61%   |
| Toshiba Satellite L655                   | 1         | 1.61%   |
| Timi TM1613                              | 1         | 1.61%   |
| Sony SVP1321L1EBI                        | 1         | 1.61%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 1.61%   |
| Samsung 300E4C/300E5C/300E7C             | 1         | 1.61%   |
| Positivo Q232A                           | 1         | 1.61%   |
| MSI GT60 2OC/2OD                         | 1         | 1.61%   |
| MSI GE75 Raider 10SF                     | 1         | 1.61%   |
| MSI GE73 Raider RGB 8RE                  | 1         | 1.61%   |
| MSI GE63 Raider RGB 8RE                  | 1         | 1.61%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.61%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 1.61%   |
| Lenovo ThinkPad X260 20F5S5QT00          | 1         | 1.61%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 1.61%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003AMC | 1         | 1.61%   |
| Lenovo ThinkPad E15 20RD0086UE           | 1         | 1.61%   |
| Lenovo ThinkBook 15 G2 ARE 20VG          | 1         | 1.61%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 1         | 1.61%   |
| Lenovo B50-80 80EW                       | 1         | 1.61%   |
| HP ZBook 15 G5                           | 1         | 1.61%   |
| HP Pavilion Notebook                     | 1         | 1.61%   |
| HP Pavilion dv7                          | 1         | 1.61%   |
| HP Pavilion dv6700                       | 1         | 1.61%   |
| HP Pavilion dv6                          | 1         | 1.61%   |
| HP Pavilion dv4                          | 1         | 1.61%   |
| HP Laptop 15s-eq1xxx                     | 1         | 1.61%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.61%   |
| HP HDX PREMIUM SERIES                    | 1         | 1.61%   |
| HP EliteBook 850 G6                      | 1         | 1.61%   |
| HP EliteBook 8470p                       | 1         | 1.61%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.61%   |
| HP 250 G7 Notebook PC                    | 1         | 1.61%   |
| GPU Company GWTN141-10                   | 1         | 1.61%   |
| Gateway MP8708                           | 1         | 1.61%   |
| Fujitsu LIFEBOOK T731                    | 1         | 1.61%   |
| Eluktronics MAG-15u                      | 1         | 1.61%   |
| Dell Vostro 5470                         | 1         | 1.61%   |
| Dell Precision M4600                     | 1         | 1.61%   |
| Dell Latitude E7440                      | 1         | 1.61%   |
| Dell Latitude E6420                      | 1         | 1.61%   |
| Dell Latitude E6410                      | 1         | 1.61%   |
| Dell Inspiron 7501                       | 1         | 1.61%   |
| Dell Inspiron 5593                       | 1         | 1.61%   |
| Dell Inspiron 5558                       | 1         | 1.61%   |
| Dell Inspiron 5420                       | 1         | 1.61%   |
| Dell Inspiron 15 5510                    | 1         | 1.61%   |
| ASUS X75VB                               | 1         | 1.61%   |
| ASUS X450EA                              | 1         | 1.61%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA  | 1         | 1.61%   |
| ASUS G74Sx                               | 1         | 1.61%   |
| Apple MacBookPro8,1                      | 1         | 1.61%   |
| Apple MacBookPro11,1                     | 1         | 1.61%   |
| Alienware m15 R6                         | 1         | 1.61%   |
| Acer TravelMate 5720                     | 1         | 1.61%   |
| Acer Swift SF114-33                      | 1         | 1.61%   |
| Acer Aspire E1-571G                      | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP Pavilion            | 5         | 8.06%   |
| Dell Inspiron          | 5         | 8.06%   |
| Lenovo ThinkPad        | 4         | 6.45%   |
| HP EliteBook           | 3         | 4.84%   |
| Dell Latitude          | 3         | 4.84%   |
| HP ProBook             | 2         | 3.23%   |
| HP Laptop              | 2         | 3.23%   |
| ASUS Q524UQ            | 2         | 3.23%   |
| Wortmann AG TERRA      | 1         | 1.61%   |
| Toxic GM7MQ8P          | 1         | 1.61%   |
| Toshiba Satellite      | 1         | 1.61%   |
| Timi TM1613            | 1         | 1.61%   |
| Sony SVP1321L1EBI      | 1         | 1.61%   |
| Samsung 350V5C         | 1         | 1.61%   |
| Samsung 300E4C         | 1         | 1.61%   |
| Positivo Q232A         | 1         | 1.61%   |
| MSI GT60               | 1         | 1.61%   |
| MSI GE75               | 1         | 1.61%   |
| MSI GE73               | 1         | 1.61%   |
| MSI GE63               | 1         | 1.61%   |
| Lenovo Yoga            | 1         | 1.61%   |
| Lenovo Y520-15IKBN     | 1         | 1.61%   |
| Lenovo ThinkBook       | 1         | 1.61%   |
| Lenovo IdeaPad         | 1         | 1.61%   |
| Lenovo B50-80          | 1         | 1.61%   |
| HP ZBook               | 1         | 1.61%   |
| HP HDX                 | 1         | 1.61%   |
| HP 250                 | 1         | 1.61%   |
| GPU Company GWTN141-10 | 1         | 1.61%   |
| Gateway MP8708         | 1         | 1.61%   |
| Fujitsu LIFEBOOK       | 1         | 1.61%   |
| Eluktronics MAG-15u    | 1         | 1.61%   |
| Dell Vostro            | 1         | 1.61%   |
| Dell Precision         | 1         | 1.61%   |
| ASUS X75VB             | 1         | 1.61%   |
| ASUS X450EA            | 1         | 1.61%   |
| ASUS VivoBook          | 1         | 1.61%   |
| ASUS G74Sx             | 1         | 1.61%   |
| Apple MacBookPro8      | 1         | 1.61%   |
| Apple MacBookPro11     | 1         | 1.61%   |
| Alienware m15          | 1         | 1.61%   |
| Acer TravelMate        | 1         | 1.61%   |
| Acer Swift             | 1         | 1.61%   |
| Acer Aspire            | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 9         | 14.52%  |
| 2013 | 9         | 14.52%  |
| 2020 | 7         | 11.29%  |
| 2011 | 6         | 9.68%   |
| 2018 | 5         | 8.06%   |
| 2016 | 5         | 8.06%   |
| 2021 | 4         | 6.45%   |
| 2015 | 3         | 4.84%   |
| 2012 | 3         | 4.84%   |
| 2010 | 3         | 4.84%   |
| 2008 | 3         | 4.84%   |
| 2007 | 2         | 3.23%   |
| 2017 | 1         | 1.61%   |
| 2014 | 1         | 1.61%   |
| 2006 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 62        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 62        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 16        | 25.81%  |
| 8.01-16.0   | 14        | 22.58%  |
| 16.01-24.0  | 13        | 20.97%  |
| 3.01-4.0    | 10        | 16.13%  |
| 32.01-64.0  | 3         | 4.84%   |
| 64.01-256.0 | 2         | 3.23%   |
| 1.01-2.0    | 2         | 3.23%   |
| 24.01-32.0  | 1         | 1.61%   |
| 2.01-3.0    | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 24        | 37.5%   |
| 2.01-3.0  | 21        | 32.81%  |
| 3.01-4.0  | 11        | 17.19%  |
| 4.01-8.0  | 7         | 10.94%  |
| 8.01-16.0 | 1         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 41        | 66.13%  |
| 2      | 18        | 29.03%  |
| 3      | 3         | 4.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 39        | 62.9%   |
| Yes       | 23        | 37.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 77.42%  |
| No        | 14        | 22.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 98.39%  |
| No        | 1         | 1.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 75.81%  |
| No        | 15        | 24.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 19        | 30.65%  |
| Germany      | 5         | 8.06%   |
| France       | 5         | 8.06%   |
| Spain        | 4         | 6.45%   |
| UK           | 3         | 4.84%   |
| Russia       | 3         | 4.84%   |
| Brazil       | 3         | 4.84%   |
| Netherlands  | 2         | 3.23%   |
| Iraq         | 2         | 3.23%   |
| Czechia      | 2         | 3.23%   |
| Sweden       | 1         | 1.61%   |
| South Africa | 1         | 1.61%   |
| Puerto Rico  | 1         | 1.61%   |
| Nigeria      | 1         | 1.61%   |
| Mexico       | 1         | 1.61%   |
| Kenya        | 1         | 1.61%   |
| Indonesia    | 1         | 1.61%   |
| Hungary      | 1         | 1.61%   |
| Colombia     | 1         | 1.61%   |
| Canada       | 1         | 1.61%   |
| Belgium      | 1         | 1.61%   |
| Bangladesh   | 1         | 1.61%   |
| Azerbaijan   | 1         | 1.61%   |
| Australia    | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Dallas                   | 2         | 3.17%   |
| Chicago                  | 2         | 3.17%   |
| West Jordan              | 1         | 1.59%   |
| Visalia                  | 1         | 1.59%   |
| Veitsbronn               | 1         | 1.59%   |
| Tangerang                | 1         | 1.59%   |
| Stockholm                | 1         | 1.59%   |
| St Petersburg            | 1         | 1.59%   |
| Sinntal                  | 1         | 1.59%   |
| Shelbyville              | 1         | 1.59%   |
| Secaucus                 | 1         | 1.59%   |
| Santo André             | 1         | 1.59%   |
| Sant Boi de Llobregat    | 1         | 1.59%   |
| Sannois                  | 1         | 1.59%   |
| Rotterdam                | 1         | 1.59%   |
| Rialma                   | 1         | 1.59%   |
| Reus                     | 1         | 1.59%   |
| Regensburg               | 1         | 1.59%   |
| Reading                  | 1         | 1.59%   |
| Pretoria                 | 1         | 1.59%   |
| Prague                   | 1         | 1.59%   |
| Ponce                    | 1         | 1.59%   |
| Paris                    | 1         | 1.59%   |
| Omaha                    | 1         | 1.59%   |
| New Orleans              | 1         | 1.59%   |
| Nairobi                  | 1         | 1.59%   |
| Munich                   | 1         | 1.59%   |
| Melbourne                | 1         | 1.59%   |
| Marietta                 | 1         | 1.59%   |
| Manaus                   | 1         | 1.59%   |
| Maggie Valley            | 1         | 1.59%   |
| Lyon                     | 1         | 1.59%   |
| Los Mochis               | 1         | 1.59%   |
| Long Beach               | 1         | 1.59%   |
| London                   | 1         | 1.59%   |
| Lancaster                | 1         | 1.59%   |
| Khabarovsk               | 1         | 1.59%   |
| Kano                     | 1         | 1.59%   |
| Jihlava                  | 1         | 1.59%   |
| Houston                  | 1         | 1.59%   |
| Guignicourt              | 1         | 1.59%   |
| Fusagasuga               | 1         | 1.59%   |
| Fort Lauderdale          | 1         | 1.59%   |
| Fallbrook                | 1         | 1.59%   |
| Erbil                    | 1         | 1.59%   |
| Edmonton                 | 1         | 1.59%   |
| Dortmund                 | 1         | 1.59%   |
| Donostia / San Sebastian | 1         | 1.59%   |
| Dhaka                    | 1         | 1.59%   |
| De Pere                  | 1         | 1.59%   |
| Concord                  | 1         | 1.59%   |
| Bussum                   | 1         | 1.59%   |
| Budapest                 | 1         | 1.59%   |
| Brno                     | 1         | 1.59%   |
| Blagoveshchensk          | 1         | 1.59%   |
| Bay Saint Louis          | 1         | 1.59%   |
| Barcelona                | 1         | 1.59%   |
| Baku                     | 1         | 1.59%   |
| Baghdad                  | 1         | 1.59%   |
| Aix-les-Bains            | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 13.41%  |
| WDC                 | 10        | 12     | 12.2%   |
| Crucial             | 7         | 10     | 8.54%   |
| Unknown             | 6         | 6      | 7.32%   |
| Toshiba             | 6         | 7      | 7.32%   |
| Seagate             | 6         | 6      | 7.32%   |
| Kingston            | 6         | 6      | 7.32%   |
| SanDisk             | 4         | 4      | 4.88%   |
| SK hynix            | 3         | 3      | 3.66%   |
| Micron Technology   | 3         | 3      | 3.66%   |
| Hitachi             | 3         | 3      | 3.66%   |
| HGST                | 3         | 3      | 3.66%   |
| A-DATA Technology   | 3         | 3      | 3.66%   |
| KIOXIA              | 2         | 2      | 2.44%   |
| China               | 2         | 2      | 2.44%   |
| W800SH              | 1         | 1      | 1.22%   |
| Team                | 1         | 1      | 1.22%   |
| Patriot             | 1         | 1      | 1.22%   |
| Lexar               | 1         | 1      | 1.22%   |
| Intel               | 1         | 1      | 1.22%   |
| Corsair             | 1         | 1      | 1.22%   |
| Apple               | 1         | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 2.35%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 2         | 2.35%   |
| SanDisk SSD PLUS 1000GB                  | 2         | 2.35%   |
| Samsung SSD 860 EVO 500GB                | 2         | 2.35%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 2.35%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2.35%   |
| Crucial CT1000MX500SSD1 1TB              | 2         | 2.35%   |
| WDC WDS100T2B0C-00PXH0 1TB               | 1         | 1.18%   |
| WDC WDBNCE2500PNC 250GB SSD              | 1         | 1.18%   |
| WDC WD800BEVS-22RST0 80GB                | 1         | 1.18%   |
| WDC WD3200LPVX-00V0TT0 320GB             | 1         | 1.18%   |
| WDC WD2500BPVT-00JJ5T0 250GB             | 1         | 1.18%   |
| WDC WD10SPZX-17Z10T1 1TB                 | 1         | 1.18%   |
| WDC WD10SPZX-08Z10 1TB                   | 1         | 1.18%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB     | 1         | 1.18%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB     | 1         | 1.18%   |
| W800SH 512GB SSD                         | 1         | 1.18%   |
| Unknown Y016B  16GB                      | 1         | 1.18%   |
| Unknown xD/SD/M.S.                       | 1         | 1.18%   |
| Unknown SS16G  16GB                      | 1         | 1.18%   |
| Unknown SS08G  8GB                       | 1         | 1.18%   |
| Unknown SDU1  64GB                       | 1         | 1.18%   |
| Unknown MMC Card  128GB                  | 1         | 1.18%   |
| Toshiba THNSNH128G8NT 128GB SSD          | 1         | 1.18%   |
| Toshiba THNSNF128GMCS 128GB SSD          | 1         | 1.18%   |
| Toshiba Q300. 480GB SSD                  | 1         | 1.18%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 1.18%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1.18%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1.18%   |
| Team TM8PS7512G 512GB SSD                | 1         | 1.18%   |
| SK hynix NVMe SSD Drive 512GB            | 1         | 1.18%   |
| SK hynix HFM256GDJTNI-82A0A 256GB        | 1         | 1.18%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 1.18%   |
| Seagate ST9500420AS 500GB                | 1         | 1.18%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1.18%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.18%   |
| SanDisk Extreme SSD 500GB                | 1         | 1.18%   |
| SanDisk DF4032  32GB                     | 1         | 1.18%   |
| Samsung SSD 980 1TB                      | 1         | 1.18%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.18%   |
| Samsung MZVLW256HEHP-00000 256GB         | 1         | 1.18%   |
| Samsung MZVLV256HCHP-00000 256GB         | 1         | 1.18%   |
| Samsung MZVLQ256HAJD-00000 256GB         | 1         | 1.18%   |
| Samsung MZVLB512HBJQ-000L2 512GB         | 1         | 1.18%   |
| Samsung MZVLB1T0HBLR-000L2 1TB           | 1         | 1.18%   |
| Samsung MZVLB1T0HALR 1TB SSD             | 1         | 1.18%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD     | 1         | 1.18%   |
| Samsung MZALQ512HALU-000L2 512GB         | 1         | 1.18%   |
| Patriot P210 256GB SSD                   | 1         | 1.18%   |
| Micron MTFDHBA256TDV-1AY1AABHA 256GB     | 1         | 1.18%   |
| Micron MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1.18%   |
| Micron 2200_MTFDHBA512TCK 512GB          | 1         | 1.18%   |
| Lexar 250GB SSD                          | 1         | 1.18%   |
| KIOXIA KBG40ZNV256G 256GB                | 1         | 1.18%   |
| KIOXIA KBG40ZNS512G NVMe 512GB           | 1         | 1.18%   |
| Kingston SV300S37A240G 240GB SSD         | 1         | 1.18%   |
| Kingston SKC400S37512G 512GB SSD         | 1         | 1.18%   |
| Kingston SA2000M8500G 500GB              | 1         | 1.18%   |
| Kingston NVMe SSD Drive 512GB            | 1         | 1.18%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 8      | 31.82%  |
| Seagate | 6         | 6      | 27.27%  |
| Toshiba | 3         | 3      | 13.64%  |
| Hitachi | 3         | 3      | 13.64%  |
| HGST    | 3         | 3      | 13.64%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 9      | 19.35%  |
| Samsung Electronics | 4         | 4      | 12.9%   |
| Kingston            | 4         | 4      | 12.9%   |
| Toshiba             | 3         | 4      | 9.68%   |
| SanDisk             | 3         | 3      | 9.68%   |
| China               | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| W800SH              | 1         | 1      | 3.23%   |
| Team                | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 27        | 35     | 35.53%  |
| NVMe    | 22        | 24     | 28.95%  |
| HDD     | 21        | 23     | 27.63%  |
| MMC     | 5         | 6      | 6.58%   |
| Unknown | 1         | 1      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 55     | 59.46%  |
| NVMe | 22        | 24     | 29.73%  |
| MMC  | 5         | 6      | 6.76%   |
| SAS  | 3         | 4      | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 37     | 60.42%  |
| 0.51-1.0   | 16        | 18     | 33.33%  |
| 1.01-2.0   | 3         | 3      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 29.03%  |
| 101-250        | 15        | 24.19%  |
| 501-1000       | 9         | 14.52%  |
| 1001-2000      | 7         | 11.29%  |
| Unknown        | 6         | 9.68%   |
| 51-100         | 3         | 4.84%   |
| More than 3000 | 2         | 3.23%   |
| 21-50          | 1         | 1.61%   |
| 2001-3000      | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 17        | 26.98%  |
| 21-50     | 14        | 22.22%  |
| 251-500   | 8         | 12.7%   |
| 1-20      | 8         | 12.7%   |
| 101-250   | 7         | 11.11%  |
| Unknown   | 6         | 9.52%   |
| 501-1000  | 2         | 3.17%   |
| 1001-2000 | 1         | 1.59%   |

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
| Works    | 37        | 46     | 55.22%  |
| Detected | 25        | 37     | 37.31%  |
| Malfunc  | 5         | 6      | 7.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 52        | 65.82%  |
| Samsung Electronics         | 8         | 10.13%  |
| SK hynix                    | 3         | 3.8%    |
| SanDisk                     | 3         | 3.8%    |
| AMD                         | 3         | 3.8%    |
| Micron Technology           | 2         | 2.53%   |
| KIOXIA                      | 2         | 2.53%   |
| Kingston Technology Company | 2         | 2.53%   |
| Silicon Motion              | 1         | 1.27%   |
| Realtek Semiconductor       | 1         | 1.27%   |
| Micron/Crucial Technology   | 1         | 1.27%   |
| ADATA Technology            | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 7.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.53%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 3.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 3.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 3.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 3.53%   |
| SK hynix BC511                                                                         | 2         | 2.35%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 2.35%   |
| Micron Non-Volatile memory controller                                                  | 2         | 2.35%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 2.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.35%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 2.35%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.18%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 1.18%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.18%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 1.18%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 1.18%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.18%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 1         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.18%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.18%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.18%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.18%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 50        | 61.73%  |
| NVMe | 22        | 27.16%  |
| IDE  | 5         | 6.17%   |
| RAID | 4         | 4.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 93.55%  |
| AMD    | 4         | 6.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 4.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 3.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 3.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 3.23%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 3.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 3.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 3.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 3.23%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 3.23%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.61%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.61%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.61%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.61%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.61%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.61%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.61%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.61%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.61%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.61%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.61%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.61%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.61%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 1.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.61%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.61%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 1.61%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.61%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.61%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.61%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.61%   |
| Intel 11th Gen Core i7-11390H @ 3.40GHz     | 1         | 1.61%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 1         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 1.61%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 1         | 1.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 1         | 1.61%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 1         | 1.61%   |
| AMD E1-2500 APU with Radeon HD Graphics     | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 35.48%  |
| Intel Core i7           | 20        | 32.26%  |
| Other                   | 5         | 8.06%   |
| Intel Core i3           | 3         | 4.84%   |
| Intel Pentium Silver    | 2         | 3.23%   |
| Intel Core 2 Duo        | 2         | 3.23%   |
| Intel Pentium Dual-Core | 1         | 1.61%   |
| Intel Core 2 Quad       | 1         | 1.61%   |
| Intel Core 2            | 1         | 1.61%   |
| Intel Atom              | 1         | 1.61%   |
| AMD Ryzen 7             | 1         | 1.61%   |
| AMD Ryzen 5             | 1         | 1.61%   |
| AMD Ryzen 3             | 1         | 1.61%   |
| AMD E1                  | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 30        | 48.39%  |
| 4      | 23        | 37.1%   |
| 6      | 5         | 8.06%   |
| 8      | 4         | 6.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 62        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 79.03%  |
| 1      | 13        | 20.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 62        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 36.51%  |
| 0x206a7    | 5         | 7.94%   |
| 0x806ec    | 4         | 6.35%   |
| 0xa0652    | 3         | 4.76%   |
| 0x806c1    | 3         | 4.76%   |
| 0x306c3    | 3         | 4.76%   |
| 0x706e5    | 2         | 3.17%   |
| 0x306d4    | 2         | 3.17%   |
| 0x306a9    | 2         | 3.17%   |
| 0x1067a    | 2         | 3.17%   |
| 0x08600106 | 2         | 3.17%   |
| 0x906e9    | 1         | 1.59%   |
| 0x806d1    | 1         | 1.59%   |
| 0x806c2    | 1         | 1.59%   |
| 0x706a8    | 1         | 1.59%   |
| 0x706a1    | 1         | 1.59%   |
| 0x6fd      | 1         | 1.59%   |
| 0x6f6      | 1         | 1.59%   |
| 0x506e3    | 1         | 1.59%   |
| 0x406e3    | 1         | 1.59%   |
| 0x40651    | 1         | 1.59%   |
| 0x20655    | 1         | 1.59%   |
| 0x08108109 | 1         | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 14.52%  |
| SandyBridge   | 7         | 11.29%  |
| Skylake       | 6         | 9.68%   |
| IvyBridge     | 6         | 9.68%   |
| Haswell       | 6         | 9.68%   |
| TigerLake     | 4         | 6.45%   |
| CometLake     | 4         | 6.45%   |
| Penryn        | 3         | 4.84%   |
| Icelake       | 3         | 4.84%   |
| Broadwell     | 3         | 4.84%   |
| Zen 2         | 2         | 3.23%   |
| Westmere      | 2         | 3.23%   |
| Goldmont plus | 2         | 3.23%   |
| Core          | 2         | 3.23%   |
| Zen+          | 1         | 1.61%   |
| Silvermont    | 1         | 1.61%   |
| Jaguar        | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 53        | 63.86%  |
| Nvidia | 20        | 24.1%   |
| AMD    | 10        | 12.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 5.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 4.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 4.65%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 2.33%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.33%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.33%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.33%   |
| AMD Renoir                                                                               | 2         | 2.33%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.16%   |
| Nvidia TU117M                                                                            | 1         | 1.16%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.16%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.16%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.16%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.16%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.16%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.16%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.16%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.16%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.16%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.16%   |
| Intel HD Graphics 630                                                                    | 1         | 1.16%   |
| Intel HD Graphics 530                                                                    | 1         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.16%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.16%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.16%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.16%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 1.16%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 51.61%  |
| Intel + Nvidia | 17        | 27.42%  |
| 1 x AMD        | 6         | 9.68%   |
| Intel + AMD    | 4         | 6.45%   |
| 1 x Nvidia     | 3         | 4.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 59        | 95.16%  |
| Proprietary | 3         | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 77.42%  |
| 0.51-1.0   | 5         | 8.06%   |
| 1.01-2.0   | 4         | 6.45%   |
| 3.01-4.0   | 2         | 3.23%   |
| 7.01-8.0   | 1         | 1.61%   |
| 2.01-3.0   | 1         | 1.61%   |
| 0.01-0.5   | 1         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 19.44%  |
| LG Display              | 13        | 18.06%  |
| BOE                     | 10        | 13.89%  |
| Samsung Electronics     | 9         | 12.5%   |
| Chimei Innolux          | 9         | 12.5%   |
| Chi Mei Optoelectronics | 4         | 5.56%   |
| Sceptre Tech            | 2         | 2.78%   |
| Dell                    | 2         | 2.78%   |
| Apple                   | 2         | 2.78%   |
| STA                     | 1         | 1.39%   |
| Sharp                   | 1         | 1.39%   |
| Philips                 | 1         | 1.39%   |
| Panasonic               | 1         | 1.39%   |
| Lenovo                  | 1         | 1.39%   |
| Hewlett-Packard         | 1         | 1.39%   |
| Ancor Communications    | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 2         | 2.78%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                        | 1         | 1.39%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                   | 1         | 1.39%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch            | 1         | 1.39%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch            | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.39%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                  | 1         | 1.39%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                  | 1         | 1.39%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.39%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD0683 1920x1080 344x194mm 15.5-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD066D 1920x1080 344x194mm 15.5-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 1         | 1.39%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 698x393mm 31.5-inch                  | 1         | 1.39%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch               | 1         | 1.39%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.39%   |
| Dell 1905FP DEL400D 1280x1024 380x310mm 19.3-inch                         | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch           | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch           | 1         | 1.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 381x214mm 17.2-inch | 1         | 1.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.39%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE08B5 1920x1080 309x174mm 14.0-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE089B 1280x800 261x163mm 12.1-inch                      | 1         | 1.39%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE07B6 1920x1080 382x215mm 17.3-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.39%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 1.39%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.39%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.39%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch            | 1         | 1.39%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch             | 1         | 1.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 1         | 1.39%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.39%   |
| AU Optronics LCD Monitor AUO328E 1920x1080 344x193mm 15.5-inch            | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 48.53%  |
| 1366x768 (WXGA)    | 19        | 27.94%  |
| 1280x800 (WXGA)    | 5         | 7.35%   |
| 1600x900 (HD+)     | 3         | 4.41%   |
| 2560x1440 (QHD)    | 2         | 2.94%   |
| 3840x2160 (4K)     | 1         | 1.47%   |
| 2560x1600          | 1         | 1.47%   |
| 2560x1080          | 1         | 1.47%   |
| 1680x1050 (WSXGA+) | 1         | 1.47%   |
| 1440x900 (WXGA+)   | 1         | 1.47%   |
| 1280x1024 (SXGA)   | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 30        | 41.67%  |
| 14     | 15        | 20.83%  |
| 17     | 8         | 11.11%  |
| 13     | 5         | 6.94%   |
| 31     | 2         | 2.78%   |
| 27     | 2         | 2.78%   |
| 18     | 2         | 2.78%   |
| 12     | 2         | 2.78%   |
| 32     | 1         | 1.39%   |
| 29     | 1         | 1.39%   |
| 23     | 1         | 1.39%   |
| 22     | 1         | 1.39%   |
| 21     | 1         | 1.39%   |
| 19     | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 66.2%   |
| 351-400     | 9         | 12.68%  |
| 201-300     | 5         | 7.04%   |
| 601-700     | 3         | 4.23%   |
| 501-600     | 3         | 4.23%   |
| 401-500     | 3         | 4.23%   |
| 701-800     | 1         | 1.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 55        | 84.62%  |
| 16/10 | 8         | 12.31%  |
| 6/5   | 1         | 1.54%   |
| 21/9  | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 41.67%  |
| 81-90          | 18        | 25%     |
| 121-130        | 7         | 9.72%   |
| 351-500        | 3         | 4.17%   |
| 301-350        | 3         | 4.17%   |
| 201-250        | 3         | 4.17%   |
| 71-80          | 2         | 2.78%   |
| 61-70          | 2         | 2.78%   |
| 141-150        | 2         | 2.78%   |
| 151-200        | 1         | 1.39%   |
| 131-140        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 45.07%  |
| 101-120       | 23        | 32.39%  |
| 51-100        | 11        | 15.49%  |
| 161-240       | 3         | 4.23%   |
| More than 240 | 1         | 1.41%   |
| 1-50          | 1         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 53        | 85.48%  |
| 2     | 7         | 11.29%  |
| 3     | 2         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 38        | 37.62%  |
| Realtek Semiconductor             | 29        | 28.71%  |
| Qualcomm Atheros                  | 15        | 14.85%  |
| Broadcom                          | 7         | 6.93%   |
| TP-Link                           | 2         | 1.98%   |
| Samsung Electronics               | 2         | 1.98%   |
| Xiaomi                            | 1         | 0.99%   |
| Ralink Technology                 | 1         | 0.99%   |
| Qualcomm Atheros Communications   | 1         | 0.99%   |
| NetGear                           | 1         | 0.99%   |
| Lenovo                            | 1         | 0.99%   |
| Huawei Technologies               | 1         | 0.99%   |
| Ericsson Business Mobile Networks | 1         | 0.99%   |
| Broadcom Limited                  | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 15        | 12.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 5         | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 4         | 3.28%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 3.28%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 3.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 2.46%   |
| Intel Wireless 8260                                                       | 3         | 2.46%   |
| Intel Wireless 7265                                                       | 3         | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 2.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 1.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.64%   |
| Intel Wireless 3160                                                       | 2         | 1.64%   |
| Intel Wi-Fi 6 AX200                                                       | 2         | 1.64%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 1.64%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1         | 0.82%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 0.82%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 1         | 0.82%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.82%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.82%   |
| Lenovo ThinkPad TBT 3 Dock                                                | 1         | 0.82%   |
| Intel Wireless 7260                                                       | 1         | 0.82%   |
| Intel Wireless 3165                                                       | 1         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.82%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.82%   |
| Intel Ethernet controller                                                 | 1         | 0.82%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.82%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                                      | 1         | 0.82%   |
| Intel Ethernet Connection (6) I219-LM                                     | 1         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 0.82%   |
| Intel Centrino Wireless-N 105                                             | 1         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 0.82%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 0.82%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                                  | 1         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 52.94%  |
| Qualcomm Atheros                | 12        | 17.65%  |
| Realtek Semiconductor           | 9         | 13.24%  |
| Broadcom                        | 5         | 7.35%   |
| TP-Link                         | 2         | 2.94%   |
| Ralink Technology               | 1         | 1.47%   |
| Qualcomm Atheros Communications | 1         | 1.47%   |
| NetGear                         | 1         | 1.47%   |
| Broadcom Limited                | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 7.35%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 5.88%   |
| Intel Wireless 8260                                                       | 3         | 4.41%   |
| Intel Wireless 7265                                                       | 3         | 4.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 4.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 4.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 2.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.94%   |
| Intel Wireless 3160                                                       | 2         | 2.94%   |
| Intel Wi-Fi 6 AX200                                                       | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 2.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1         | 1.47%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 1.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.47%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.47%   |
| Intel Wireless 7260                                                       | 1         | 1.47%   |
| Intel Wireless 3165                                                       | 1         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 1.47%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.47%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.47%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 46.15%  |
| Intel                 | 14        | 26.92%  |
| Qualcomm Atheros      | 6         | 11.54%  |
| Broadcom              | 3         | 5.77%   |
| Samsung Electronics   | 2         | 3.85%   |
| Xiaomi                | 1         | 1.92%   |
| Lenovo                | 1         | 1.92%   |
| Huawei Technologies   | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 28.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 7.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 5.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.66%   |
| Intel Ethernet Connection I217-V                                  | 2         | 3.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.89%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.89%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.89%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.89%   |
| Intel Ethernet controller                                         | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.89%   |
| Huawei LYA-L09                                                    | 1         | 1.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 55.45%  |
| Ethernet | 48        | 43.64%  |
| Modem    | 1         | 0.91%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 73.13%  |
| Ethernet | 18        | 26.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 69.35%  |
| 1     | 18        | 29.03%  |
| 0     | 1         | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 46        | 73.02%  |
| Yes  | 17        | 26.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 57.45%  |
| Qualcomm Atheros Communications | 8         | 17.02%  |
| Broadcom                        | 4         | 8.51%   |
| Realtek Semiconductor           | 3         | 6.38%   |
| Lite-On Technology              | 1         | 2.13%   |
| Foxconn / Hon Hai               | 1         | 2.13%   |
| Dell                            | 1         | 2.13%   |
| Cambridge Silicon Radio         | 1         | 2.13%   |
| Apple                           | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 17.02%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 17.02%  |
| Intel AX201 Bluetooth                               | 8         | 17.02%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 6.38%   |
| Realtek Bluetooth Radio                             | 2         | 4.26%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 4.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.26%   |
| Intel AX200 Bluetooth                               | 2         | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.13%   |
| Qualcomm Atheros Bluetooth                          | 1         | 2.13%   |
| Lite-On Bluetooth Radio                             | 1         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.13%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.13%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.13%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.13%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.13%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.13%   |
| Apple Bluetooth Host Controller                     | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 57        | 74.03%  |
| Nvidia    | 12        | 15.58%  |
| AMD       | 6         | 7.79%   |
| Lenovo    | 1         | 1.3%    |
| GN Netcom | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 6.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 5.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 4.4%    |
| Intel Comet Lake PCH cAVS                                                  | 4         | 4.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 4.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.3%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.3%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.2%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 2.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.2%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 2.2%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.1%    |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.1%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.1%    |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.1%    |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.1%    |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.1%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 1.1%    |
| Intel USB PnP Sound Device                                                 | 1         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.1%    |
| Intel CM238 HD Audio Controller                                            | 1         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.1%    |
| GN Netcom Jabra EVOLVE 65                                                  | 1         | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.1%    |
| AMD FCH Azalia Controller                                                  | 1         | 1.1%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 34.62%  |
| SK hynix            | 8         | 15.38%  |
| Micron Technology   | 5         | 9.62%   |
| Unknown             | 4         | 7.69%   |
| Crucial             | 4         | 7.69%   |
| Kingston            | 3         | 5.77%   |
| Elpida              | 3         | 5.77%   |
| Ramaxel Technology  | 2         | 3.85%   |
| A-DATA Technology   | 2         | 3.85%   |
| Team                | 1         | 1.92%   |
| G.Skill             | 1         | 1.92%   |
| Corsair             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 3.57%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 3.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.79%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 1.79%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.79%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 1.79%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 1.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 1.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.79%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| SK hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.79%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.79%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                         | 1         | 1.79%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 1.79%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.79%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 1         | 1.79%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.79%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.79%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.79%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s                  | 1         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 1.79%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.79%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 1.79%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s             | 1         | 1.79%   |
| Kingston RAM 9905469-066.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.79%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 1         | 1.79%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 1         | 1.79%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Crucial RAM CT16G4SFRA32A.M8FB 16GB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s                   | 1         | 1.79%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                         | 1         | 1.79%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8192MB SODIMM DDR4 2667MT/s             | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 21        | 46.67%  |
| DDR3   | 18        | 40%     |
| LPDDR4 | 3         | 6.67%   |
| DDR2   | 2         | 4.44%   |
| LPDDR3 | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 91.11%  |
| Row Of Chips | 4         | 8.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 33.33%  |
| 4096  | 17        | 33.33%  |
| 16384 | 7         | 13.73%  |
| 2048  | 6         | 11.76%  |
| 32768 | 2         | 3.92%   |
| 1024  | 2         | 3.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 12        | 24.49%  |
| 1600    | 11        | 22.45%  |
| 3200    | 8         | 16.33%  |
| 1334    | 4         | 8.16%   |
| 3266    | 2         | 4.08%   |
| 2400    | 2         | 4.08%   |
| 2133    | 2         | 4.08%   |
| 8400    | 1         | 2.04%   |
| 4267    | 1         | 2.04%   |
| 1333    | 1         | 2.04%   |
| 1067    | 1         | 2.04%   |
| 1066    | 1         | 2.04%   |
| 667     | 1         | 2.04%   |
| 533     | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

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
| Chicony Electronics                    | 17        | 31.48%  |
| Acer                                   | 8         | 14.81%  |
| Microdia                               | 6         | 11.11%  |
| IMC Networks                           | 4         | 7.41%   |
| Sunplus Innovation Technology          | 3         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Ricoh                                  | 2         | 3.7%    |
| Realtek Semiconductor                  | 2         | 3.7%    |
| Luxvisions Innotech Limited            | 2         | 3.7%    |
| Syntek                                 | 1         | 1.85%   |
| Suyin                                  | 1         | 1.85%   |
| Silicon Motion                         | 1         | 1.85%   |
| Samsung Electronics                    | 1         | 1.85%   |
| Quanta                                 | 1         | 1.85%   |
| Apple                                  | 1         | 1.85%   |
| Alcor Micro                            | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 5.56%   |
| Acer HD Webcam                                                             | 3         | 5.56%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 3.7%    |
| IMC Networks Integrated Camera                                             | 2         | 3.7%    |
| Chicony Integrated Camera                                                  | 2         | 3.7%    |
| Chicony HD Webcam                                                          | 2         | 3.7%    |
| Acer Integrated Camera                                                     | 2         | 3.7%    |
| Syntek Integrated Camera                                                   | 1         | 1.85%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.85%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.85%   |
| Sunplus HD Webcam                                                          | 1         | 1.85%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 1.85%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.85%   |
| Ricoh Pavilion Webcam                                                      | 1         | 1.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.85%   |
| Quanta HP HD Camera                                                        | 1         | 1.85%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 1.85%   |
| Microdia PC Microscope camera                                              | 1         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 1.85%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.85%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.85%   |
| Microdia Amcrest AWC2198 USB Webcam                                        | 1         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.85%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.85%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.85%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 1.85%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.85%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.85%   |
| Chicony HP Webcam                                                          | 1         | 1.85%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.85%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.85%   |
| Chicony HP HD Camera                                                       | 1         | 1.85%   |
| Chicony HD User Facing                                                     | 1         | 1.85%   |
| Chicony CNF8248                                                            | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.85%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.85%   |
| Alcor Micro USB 2.0 PC cam                                                 | 1         | 1.85%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.85%   |
| Acer HD Camera                                                             | 1         | 1.85%   |
| Acer EasyCamera                                                            | 1         | 1.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 53.85%  |
| Synaptics             | 3         | 23.08%  |
| LighTuning Technology | 1         | 7.69%   |
| Elan Microelectronics | 1         | 7.69%   |
| AuthenTec             | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner                                       | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 7.69%   |
| Validity Sensors VFS491                                                    | 1         | 7.69%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 7.69%   |
| Elan ELAN:Fingerprint                                                      | 1         | 7.69%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 7.69%   |
| Unknown                                                                    | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Alcor Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 40%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 36        | 58.06%  |
| 1     | 17        | 27.42%  |
| 2     | 8         | 12.9%   |
| 3     | 1         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 38.24%  |
| Graphics card         | 5         | 14.71%  |
| Chipcard              | 5         | 14.71%  |
| Net/wireless          | 4         | 11.76%  |
| Storage               | 3         | 8.82%   |
| Multimedia controller | 2         | 5.88%   |
| Modem                 | 1         | 2.94%   |
| Camera                | 1         | 2.94%   |

