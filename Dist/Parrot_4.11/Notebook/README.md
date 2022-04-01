Parrot 4.11 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

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

Total: 74

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-6parrot1-amd64    | 22        | 37.93%  |
| 5.10.0-8parrot1-amd64    | 13        | 22.41%  |
| 5.14.0-9parrot1-amd64    | 8         | 13.79%  |
| 5.7.0-2parrot2-amd64     | 3         | 5.17%   |
| 5.10.0-5parrot1-amd64    | 3         | 5.17%   |
| 5.10.0-3parrot1-amd64    | 3         | 5.17%   |
| 5.14.0-2parrot1-amd64    | 2         | 3.45%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.72%   |
| 5.15.0-15parrot1-amd64   | 1         | 1.72%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.72%   |
| Unknown                  | 1         | 1.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 42        | 72.41%  |
| 5.14.0  | 10        | 17.24%  |
| 5.7.0   | 3         | 5.17%   |
| 5.6.0   | 1         | 1.72%   |
| 5.15.0  | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 42        | 72.41%  |
| 5.14    | 10        | 17.24%  |
| 5.7     | 3         | 5.17%   |
| 5.6     | 1         | 1.72%   |
| 5.15    | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 57        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 36        | 63.16%  |
| KDE5    | 10        | 17.54%  |
| KDE     | 6         | 10.53%  |
| Unknown | 3         | 5.26%   |
| XFCE    | 1         | 1.75%   |
| LXDE    | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 57        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 21        | 36.21%  |
| Unknown | 19        | 32.76%  |
| TDM     | 17        | 29.31%  |
| SDDM    | 1         | 1.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 28        | 49.12%  |
| en_GB   | 6         | 10.53%  |
| fr_FR   | 4         | 7.02%   |
| ru_RU   | 3         | 5.26%   |
| pt_BR   | 3         | 5.26%   |
| Unknown | 3         | 5.26%   |
| es_ES   | 2         | 3.51%   |
| de_DE   | 2         | 3.51%   |
| nl_BE   | 1         | 1.75%   |
| id_ID   | 1         | 1.75%   |
| es_CO   | 1         | 1.75%   |
| en_NG   | 1         | 1.75%   |
| en_AU   | 1         | 1.75%   |
| cs_CZ   | 1         | 1.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 36        | 62.07%  |
| EFI  | 22        | 37.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 45        | 78.95%  |
| Ext4  | 7         | 12.28%  |
| Xfs   | 5         | 8.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 22        | 38.6%   |
| Unknown | 19        | 33.33%  |
| MBR     | 16        | 28.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 78.95%  |
| Yes       | 12        | 21.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 63.16%  |
| Yes       | 21        | 36.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 22.81%  |
| Dell                | 8         | 14.04%  |
| Lenovo              | 7         | 12.28%  |
| ASUSTek Computer    | 6         | 10.53%  |
| MSI                 | 5         | 8.77%   |
| Acer                | 3         | 5.26%   |
| Samsung Electronics | 2         | 3.51%   |
| Apple               | 2         | 3.51%   |
| Wortmann AG         | 1         | 1.75%   |
| Toxic               | 1         | 1.75%   |
| Toshiba             | 1         | 1.75%   |
| Sony                | 1         | 1.75%   |
| Quanta              | 1         | 1.75%   |
| Positivo            | 1         | 1.75%   |
| GPU Company         | 1         | 1.75%   |
| Gateway             | 1         | 1.75%   |
| Fujitsu             | 1         | 1.75%   |
| Eluktronics         | 1         | 1.75%   |
| Alienware           | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 3.51%   |
| ASUS Q524UQ                             | 2         | 3.51%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 1.75%   |
| Toxic GM7MQ8P                           | 1         | 1.75%   |
| Toshiba Satellite L655                  | 1         | 1.75%   |
| Sony SVP1321L1EBI                       | 1         | 1.75%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.75%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 1.75%   |
| Quanta HDX PREMIUM SERIES               | 1         | 1.75%   |
| Positivo Q232A                          | 1         | 1.75%   |
| MSI GT60 2OC/2OD                        | 1         | 1.75%   |
| MSI GS66 Stealth 10UG                   | 1         | 1.75%   |
| MSI GE75 Raider 10SF                    | 1         | 1.75%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 1.75%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 1.75%   |
| Lenovo Yoga S740-14IIL 81RS             | 1         | 1.75%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 1.75%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 1.75%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 1.75%   |
| Lenovo ThinkPad E15 20RD0086UE          | 1         | 1.75%   |
| Lenovo IdeaPad 5 14ITL05 82FE           | 1         | 1.75%   |
| Lenovo B50-80 80EW                      | 1         | 1.75%   |
| HP ZBook 15 G5                          | 1         | 1.75%   |
| HP Pavilion Notebook                    | 1         | 1.75%   |
| HP Pavilion dv7                         | 1         | 1.75%   |
| HP Pavilion dv6700                      | 1         | 1.75%   |
| HP Pavilion dv6                         | 1         | 1.75%   |
| HP Pavilion dv4                         | 1         | 1.75%   |
| HP Laptop 15s-eq1xxx                    | 1         | 1.75%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.75%   |
| HP EliteBook 8470p                      | 1         | 1.75%   |
| HP EliteBook 840 G8 Notebook PC         | 1         | 1.75%   |
| HP 250 G7 Notebook PC                   | 1         | 1.75%   |
| GPU Company GWTN141-10                  | 1         | 1.75%   |
| Gateway MP8708                          | 1         | 1.75%   |
| Fujitsu LIFEBOOK T731                   | 1         | 1.75%   |
| Eluktronics MAG-15u                     | 1         | 1.75%   |
| Dell Precision M4600                    | 1         | 1.75%   |
| Dell Latitude E7440                     | 1         | 1.75%   |
| Dell Latitude E6420                     | 1         | 1.75%   |
| Dell Latitude E6410                     | 1         | 1.75%   |
| Dell Inspiron 7501                      | 1         | 1.75%   |
| Dell Inspiron 5593                      | 1         | 1.75%   |
| Dell Inspiron 5558                      | 1         | 1.75%   |
| Dell Inspiron 5420                      | 1         | 1.75%   |
| ASUS X75VB                              | 1         | 1.75%   |
| ASUS X450EA                             | 1         | 1.75%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 1.75%   |
| ASUS G74Sx                              | 1         | 1.75%   |
| Apple MacBookPro8,1                     | 1         | 1.75%   |
| Apple MacBookPro11,1                    | 1         | 1.75%   |
| Alienware m15 R6                        | 1         | 1.75%   |
| Acer TravelMate 5720                    | 1         | 1.75%   |
| Acer Swift SF114-33                     | 1         | 1.75%   |
| Acer Aspire E1-571G                     | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP Pavilion            | 5         | 8.77%   |
| Dell Inspiron          | 4         | 7.02%   |
| Lenovo ThinkPad        | 3         | 5.26%   |
| Dell Latitude          | 3         | 5.26%   |
| HP ProBook             | 2         | 3.51%   |
| HP Laptop              | 2         | 3.51%   |
| HP EliteBook           | 2         | 3.51%   |
| ASUS Q524UQ            | 2         | 3.51%   |
| Wortmann AG TERRA      | 1         | 1.75%   |
| Toxic GM7MQ8P          | 1         | 1.75%   |
| Toshiba Satellite      | 1         | 1.75%   |
| Sony SVP1321L1EBI      | 1         | 1.75%   |
| Samsung 350V5C         | 1         | 1.75%   |
| Samsung 300E4C         | 1         | 1.75%   |
| Quanta HDX             | 1         | 1.75%   |
| Positivo Q232A         | 1         | 1.75%   |
| MSI GT60               | 1         | 1.75%   |
| MSI GS66               | 1         | 1.75%   |
| MSI GE75               | 1         | 1.75%   |
| MSI GE73               | 1         | 1.75%   |
| MSI GE63               | 1         | 1.75%   |
| Lenovo Yoga            | 1         | 1.75%   |
| Lenovo Y520-15IKBN     | 1         | 1.75%   |
| Lenovo IdeaPad         | 1         | 1.75%   |
| Lenovo B50-80          | 1         | 1.75%   |
| HP ZBook               | 1         | 1.75%   |
| HP 250                 | 1         | 1.75%   |
| GPU Company GWTN141-10 | 1         | 1.75%   |
| Gateway MP8708         | 1         | 1.75%   |
| Fujitsu LIFEBOOK       | 1         | 1.75%   |
| Eluktronics MAG-15u    | 1         | 1.75%   |
| Dell Precision         | 1         | 1.75%   |
| ASUS X75VB             | 1         | 1.75%   |
| ASUS X450EA            | 1         | 1.75%   |
| ASUS VivoBook          | 1         | 1.75%   |
| ASUS G74Sx             | 1         | 1.75%   |
| Apple MacBookPro8      | 1         | 1.75%   |
| Apple MacBookPro11     | 1         | 1.75%   |
| Alienware m15          | 1         | 1.75%   |
| Acer TravelMate        | 1         | 1.75%   |
| Acer Swift             | 1         | 1.75%   |
| Acer Aspire            | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 7         | 12.28%  |
| 2013 | 7         | 12.28%  |
| 2020 | 6         | 10.53%  |
| 2011 | 6         | 10.53%  |
| 2018 | 5         | 8.77%   |
| 2021 | 4         | 7.02%   |
| 2016 | 4         | 7.02%   |
| 2015 | 3         | 5.26%   |
| 2012 | 3         | 5.26%   |
| 2010 | 3         | 5.26%   |
| 2008 | 3         | 5.26%   |
| 2014 | 2         | 3.51%   |
| 2007 | 2         | 3.51%   |
| 2017 | 1         | 1.75%   |
| 2006 | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 57        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 57        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 26.32%  |
| 8.01-16.0   | 13        | 22.81%  |
| 16.01-24.0  | 11        | 19.3%   |
| 3.01-4.0    | 10        | 17.54%  |
| 32.01-64.0  | 2         | 3.51%   |
| 64.01-256.0 | 2         | 3.51%   |
| 1.01-2.0    | 2         | 3.51%   |
| 24.01-32.0  | 1         | 1.75%   |
| 2.01-3.0    | 1         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 23        | 38.98%  |
| 2.01-3.0 | 19        | 32.2%   |
| 3.01-4.0 | 11        | 18.64%  |
| 4.01-8.0 | 6         | 10.17%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 63.16%  |
| 2      | 18        | 31.58%  |
| 3      | 3         | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 34        | 59.65%  |
| Yes       | 23        | 40.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 98.25%  |
| No        | 1         | 1.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 73.68%  |
| No        | 15        | 26.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 17        | 29.82%  |
| Germany      | 5         | 8.77%   |
| Spain        | 4         | 7.02%   |
| France       | 4         | 7.02%   |
| UK           | 3         | 5.26%   |
| Brazil       | 3         | 5.26%   |
| Russia       | 2         | 3.51%   |
| Netherlands  | 2         | 3.51%   |
| Iraq         | 2         | 3.51%   |
| Sweden       | 1         | 1.75%   |
| South Africa | 1         | 1.75%   |
| Puerto Rico  | 1         | 1.75%   |
| Nigeria      | 1         | 1.75%   |
| Mexico       | 1         | 1.75%   |
| Kenya        | 1         | 1.75%   |
| Indonesia    | 1         | 1.75%   |
| Hungary      | 1         | 1.75%   |
| Czechia      | 1         | 1.75%   |
| Colombia     | 1         | 1.75%   |
| Canada       | 1         | 1.75%   |
| Belgium      | 1         | 1.75%   |
| Bangladesh   | 1         | 1.75%   |
| Azerbaijan   | 1         | 1.75%   |
| Australia    | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chicago                  | 2         | 3.45%   |
| Witbank                  | 1         | 1.72%   |
| Wichita                  | 1         | 1.72%   |
| West Jordan              | 1         | 1.72%   |
| Waveland                 | 1         | 1.72%   |
| Visalia                  | 1         | 1.72%   |
| Stockholm                | 1         | 1.72%   |
| Sinntal                  | 1         | 1.72%   |
| Sheffield                | 1         | 1.72%   |
| Secaucus                 | 1         | 1.72%   |
| Santo AndrГ©           | 1         | 1.72%   |
| Sannois                  | 1         | 1.72%   |
| Regensburg               | 1         | 1.72%   |
| Reading                  | 1         | 1.72%   |
| Prague                   | 1         | 1.72%   |
| Ponce                    | 1         | 1.72%   |
| Paris                    | 1         | 1.72%   |
| Nairobi                  | 1         | 1.72%   |
| Munich                   | 1         | 1.72%   |
| Mostoles                 | 1         | 1.72%   |
| Metairie                 | 1         | 1.72%   |
| Marietta                 | 1         | 1.72%   |
| Manchester               | 1         | 1.72%   |
| Manaus                   | 1         | 1.72%   |
| Majadahonda              | 1         | 1.72%   |
| Maggie Valley            | 1         | 1.72%   |
| Lyon                     | 1         | 1.72%   |
| Los Mochis               | 1         | 1.72%   |
| Long Beach               | 1         | 1.72%   |
| London                   | 1         | 1.72%   |
| Lagos                    | 1         | 1.72%   |
| Kobern-Gondorf           | 1         | 1.72%   |
| Kazanâ€™            | 1         | 1.72%   |
| Jihlava                  | 1         | 1.72%   |
| Jaragua                  | 1         | 1.72%   |
| Houston                  | 1         | 1.72%   |
| Haarlem                  | 1         | 1.72%   |
| Fusagasuga               | 1         | 1.72%   |
| Frankfurt am Main        | 1         | 1.72%   |
| Fort Lauderdale          | 1         | 1.72%   |
| Fallbrook                | 1         | 1.72%   |
| Erbil                    | 1         | 1.72%   |
| Edmonton                 | 1         | 1.72%   |
| East Malvern             | 1         | 1.72%   |
| Donostia / San Sebastian | 1         | 1.72%   |
| Dhaka                    | 1         | 1.72%   |
| Dallas                   | 1         | 1.72%   |
| Concord                  | 1         | 1.72%   |
| Bussum                   | 1         | 1.72%   |
| Budapest                 | 1         | 1.72%   |
| Blagoveshchensk          | 1         | 1.72%   |
| Barcelona                | 1         | 1.72%   |
| Banjarmasin              | 1         | 1.72%   |
| Baku                     | 1         | 1.72%   |
| Baghdad                  | 1         | 1.72%   |
| Aix-les-Bains            | 1         | 1.72%   |
| Aalst                    | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 11.69%  |
| Samsung Electronics | 9         | 10     | 11.69%  |
| Crucial             | 7         | 10     | 9.09%   |
| Unknown             | 6         | 6      | 7.79%   |
| Toshiba             | 6         | 7      | 7.79%   |
| Seagate             | 6         | 6      | 7.79%   |
| Kingston            | 5         | 5      | 6.49%   |
| SanDisk             | 4         | 4      | 5.19%   |
| SK Hynix            | 3         | 3      | 3.9%    |
| Micron Technology   | 3         | 3      | 3.9%    |
| Hitachi             | 3         | 3      | 3.9%    |
| HGST                | 3         | 3      | 3.9%    |
| A-DATA Technology   | 3         | 3      | 3.9%    |
| KIOXIA              | 2         | 2      | 2.6%    |
| China               | 2         | 2      | 2.6%    |
| W800SH              | 1         | 1      | 1.3%    |
| Patriot             | 1         | 1      | 1.3%    |
| Lexar               | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| Corsair             | 1         | 1      | 1.3%    |
| Apple               | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 2.5%    |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 2         | 2.5%    |
| SanDisk SSD PLUS 1000GB                  | 2         | 2.5%    |
| Samsung SSD 860 EVO 500GB                | 2         | 2.5%    |
| Kingston SA400S37240G 240GB SSD          | 2         | 2.5%    |
| HGST HTS541010A9E680 1TB                 | 2         | 2.5%    |
| Crucial CT1000MX500SSD1 1TB              | 2         | 2.5%    |
| WDC WDS100T2B0C-00PXH0 1TB               | 1         | 1.25%   |
| WDC WDBNCE2500PNC 250GB SSD              | 1         | 1.25%   |
| WDC WD800BEVS-22RST0 80GB                | 1         | 1.25%   |
| WDC WD3200LPVX-00V0TT0 320GB             | 1         | 1.25%   |
| WDC WD2500BPVT-00JJ5T0 250GB             | 1         | 1.25%   |
| WDC WD10SPZX-17Z10T1 1TB                 | 1         | 1.25%   |
| WDC WD10SPZX-08Z10 1TB                   | 1         | 1.25%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB     | 1         | 1.25%   |
| W800SH 512GB SSD                         | 1         | 1.25%   |
| Unknown Y016B  16GB                      | 1         | 1.25%   |
| Unknown xD/SD/M.S.                       | 1         | 1.25%   |
| Unknown SS16G  16GB                      | 1         | 1.25%   |
| Unknown SS08G  8GB                       | 1         | 1.25%   |
| Unknown SDU1  64GB                       | 1         | 1.25%   |
| Unknown MMC Card  128GB                  | 1         | 1.25%   |
| Toshiba THNSNH128G8NT 128GB SSD          | 1         | 1.25%   |
| Toshiba THNSNF128GMCS 128GB SSD          | 1         | 1.25%   |
| Toshiba Q300. 480GB SSD                  | 1         | 1.25%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 1.25%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1.25%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1.25%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 1.25%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB        | 1         | 1.25%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 1.25%   |
| Seagate ST9500420AS 500GB                | 1         | 1.25%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1.25%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.25%   |
| SanDisk Extreme SSD 2TB                  | 1         | 1.25%   |
| SanDisk DF4032  32GB                     | 1         | 1.25%   |
| Samsung SSD 980 1TB                      | 1         | 1.25%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.25%   |
| Samsung MZVLW256HEHP-00000 256GB         | 1         | 1.25%   |
| Samsung MZVLQ256HAJD-00000 256GB         | 1         | 1.25%   |
| Samsung MZVLB512HBJQ-000L2 512GB         | 1         | 1.25%   |
| Samsung MZVLB1T0HBLR-000L2 1TB           | 1         | 1.25%   |
| Samsung MZVLB1T0HALR 1TB SSD             | 1         | 1.25%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD     | 1         | 1.25%   |
| Patriot P210 256GB SSD                   | 1         | 1.25%   |
| Micron MTFDHBA256TDV-1AY1AABHA 256GB     | 1         | 1.25%   |
| Micron MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1.25%   |
| Micron 2200_MTFDHBA512TCK 512GB          | 1         | 1.25%   |
| Lexar 250GB SSD                          | 1         | 1.25%   |
| KIOXIA KBG40ZNV256G 256GB                | 1         | 1.25%   |
| KIOXIA KBG40ZNS512G NVMe 512GB           | 1         | 1.25%   |
| Kingston SV300S37A240G 240GB SSD         | 1         | 1.25%   |
| Kingston SKC400S37512G 512GB SSD         | 1         | 1.25%   |
| Kingston SA2000M8500G 500GB              | 1         | 1.25%   |
| Intel SSDSC2BW180A3H 180GB               | 1         | 1.25%   |
| Hitachi HTS545025A7E380 250GB            | 1         | 1.25%   |
| Hitachi HTS542525K9SA00 250GB            | 1         | 1.25%   |
| Hitachi HTS542512K9SA00 120GB            | 1         | 1.25%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1.25%   |

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
| Crucial             | 6         | 9      | 20%     |
| Samsung Electronics | 4         | 4      | 13.33%  |
| Kingston            | 4         | 4      | 13.33%  |
| Toshiba             | 3         | 4      | 10%     |
| SanDisk             | 3         | 3      | 10%     |
| China               | 2         | 2      | 6.67%   |
| WDC                 | 1         | 1      | 3.33%   |
| W800SH              | 1         | 1      | 3.33%   |
| Patriot             | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Corsair             | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 26        | 34     | 36.62%  |
| HDD     | 21        | 23     | 29.58%  |
| NVMe    | 18        | 20     | 25.35%  |
| MMC     | 5         | 6      | 7.04%   |
| Unknown | 1         | 1      | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 54     | 62.32%  |
| NVMe | 18        | 20     | 26.09%  |
| MMC  | 5         | 6      | 7.25%   |
| SAS  | 3         | 4      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 36     | 60.42%  |
| 0.51-1.0   | 15        | 17     | 31.25%  |
| 1.01-2.0   | 4         | 4      | 8.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 14        | 24.56%  |
| 101-250        | 14        | 24.56%  |
| 501-1000       | 9         | 15.79%  |
| 1001-2000      | 7         | 12.28%  |
| Unknown        | 6         | 10.53%  |
| 51-100         | 3         | 5.26%   |
| More than 3000 | 2         | 3.51%   |
| 21-50          | 1         | 1.75%   |
| 2001-3000      | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 17        | 29.31%  |
| 21-50     | 14        | 24.14%  |
| 251-500   | 7         | 12.07%  |
| 1-20      | 6         | 10.34%  |
| Unknown   | 6         | 10.34%  |
| 101-250   | 5         | 8.62%   |
| 501-1000  | 2         | 3.45%   |
| 1001-2000 | 1         | 1.72%   |

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
| Works    | 33        | 42     | 53.23%  |
| Detected | 24        | 36     | 38.71%  |
| Malfunc  | 5         | 6      | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 50        | 69.44%  |
| Samsung Electronics         | 6         | 8.33%   |
| SK Hynix                    | 3         | 4.17%   |
| Sandisk                     | 2         | 2.78%   |
| Micron Technology           | 2         | 2.78%   |
| KIOXIA                      | 2         | 2.78%   |
| AMD                         | 2         | 2.78%   |
| Silicon Motion              | 1         | 1.39%   |
| Realtek Semiconductor       | 1         | 1.39%   |
| Micron/Crucial Technology   | 1         | 1.39%   |
| Kingston Technology Company | 1         | 1.39%   |
| ADATA Technology            | 1         | 1.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 6.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 3.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 3.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 3.85%   |
| SK Hynix BC511                                                                         | 2         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.56%   |
| Micron Non-Volatile memory controller                                                  | 2         | 2.56%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 2.56%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 1.28%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 1.28%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.28%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.28%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 1.28%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.28%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 1.28%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.28%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.28%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 1.28%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 47        | 63.51%  |
| NVMe | 18        | 24.32%  |
| IDE  | 5         | 6.76%   |
| RAID | 4         | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 94.74%  |
| AMD    | 3         | 5.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 3.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 3.51%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 3.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 3.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 3.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 3.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 3.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 3.51%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.75%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.75%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.75%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.75%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.75%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.75%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.75%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.75%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.75%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.75%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.75%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.75%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.75%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.75%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.75%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 1.75%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.75%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.75%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.75%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.75%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.75%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 1         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 1.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 1         | 1.75%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 1         | 1.75%   |
| AMD E1-2500 APU with Radeon HD Graphics     | 1         | 1.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 35.09%  |
| Intel Core i7           | 19        | 33.33%  |
| Other                   | 4         | 7.02%   |
| Intel Core i3           | 3         | 5.26%   |
| Intel Pentium Silver    | 2         | 3.51%   |
| Intel Core 2 Duo        | 2         | 3.51%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Core 2 Quad       | 1         | 1.75%   |
| Intel Core 2            | 1         | 1.75%   |
| Intel Atom              | 1         | 1.75%   |
| AMD Ryzen 7             | 1         | 1.75%   |
| AMD Ryzen 3             | 1         | 1.75%   |
| AMD E1                  | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 29        | 50.88%  |
| 4      | 20        | 35.09%  |
| 8      | 4         | 7.02%   |
| 6      | 4         | 7.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 57        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 78.95%  |
| 1      | 12        | 21.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 57        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 39.66%  |
| 0x206a7    | 5         | 8.62%   |
| 0xa0652    | 3         | 5.17%   |
| 0x806c1    | 3         | 5.17%   |
| 0x306c3    | 3         | 5.17%   |
| 0x806ec    | 2         | 3.45%   |
| 0x706e5    | 2         | 3.45%   |
| 0x306d4    | 2         | 3.45%   |
| 0x306a9    | 2         | 3.45%   |
| 0x1067a    | 2         | 3.45%   |
| 0x906e9    | 1         | 1.72%   |
| 0x806d1    | 1         | 1.72%   |
| 0x706a8    | 1         | 1.72%   |
| 0x706a1    | 1         | 1.72%   |
| 0x6fd      | 1         | 1.72%   |
| 0x6f6      | 1         | 1.72%   |
| 0x506e3    | 1         | 1.72%   |
| 0x40651    | 1         | 1.72%   |
| 0x20655    | 1         | 1.72%   |
| 0x08600106 | 1         | 1.72%   |
| 0x08108109 | 1         | 1.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 7         | 12.28%  |
| KabyLake      | 7         | 12.28%  |
| IvyBridge     | 6         | 10.53%  |
| Haswell       | 6         | 10.53%  |
| Skylake       | 5         | 8.77%   |
| CometLake     | 4         | 7.02%   |
| TigerLake     | 3         | 5.26%   |
| Penryn        | 3         | 5.26%   |
| Icelake       | 3         | 5.26%   |
| Broadwell     | 3         | 5.26%   |
| Westmere      | 2         | 3.51%   |
| Goldmont plus | 2         | 3.51%   |
| Core          | 2         | 3.51%   |
| Zen+          | 1         | 1.75%   |
| Zen 2         | 1         | 1.75%   |
| Silvermont    | 1         | 1.75%   |
| Jaguar        | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 49        | 63.64%  |
| Nvidia | 19        | 24.68%  |
| AMD    | 9         | 11.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 6.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 5%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.75%   |
| Intel HD Graphics 5500                                                                   | 3         | 3.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.75%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 2.5%    |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.5%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 2.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.5%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 2.5%    |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.25%   |
| Nvidia TU117M                                                                            | 1         | 1.25%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 1.25%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.25%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 1.25%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 1.25%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1.25%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 1.25%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1.25%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.25%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 1.25%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.25%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 1.25%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 1.25%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.25%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.25%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 1.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1.25%   |
| Intel HD Graphics 630                                                                    | 1         | 1.25%   |
| Intel HD Graphics 530                                                                    | 1         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.25%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.25%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 1.25%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 1.25%   |
| AMD Renoir                                                                               | 1         | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.25%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 1.25%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 50.88%  |
| Intel + Nvidia | 16        | 28.07%  |
| 1 x AMD        | 5         | 8.77%   |
| Intel + AMD    | 4         | 7.02%   |
| 1 x Nvidia     | 3         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 55        | 96.49%  |
| Proprietary | 2         | 3.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 77.19%  |
| 0.51-1.0   | 5         | 8.77%   |
| 1.01-2.0   | 3         | 5.26%   |
| 3.01-4.0   | 2         | 3.51%   |
| 7.01-8.0   | 1         | 1.75%   |
| 2.01-3.0   | 1         | 1.75%   |
| 0.01-0.5   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 20.63%  |
| LG Display              | 10        | 15.87%  |
| BOE                     | 10        | 15.87%  |
| Samsung Electronics     | 9         | 14.29%  |
| Chimei Innolux          | 9         | 14.29%  |
| Chi Mei Optoelectronics | 4         | 6.35%   |
| Dell                    | 2         | 3.17%   |
| Apple                   | 2         | 3.17%   |
| STA                     | 1         | 1.59%   |
| Philips                 | 1         | 1.59%   |
| Panasonic               | 1         | 1.59%   |
| Ancor Communications    | 1         | 1.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 2         | 3.17%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                        | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch      | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.59%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                  | 1         | 1.59%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch              | 1         | 1.59%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.59%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.59%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch               | 1         | 1.59%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.59%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch               | 1         | 1.59%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 1         | 1.59%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.59%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch           | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch           | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.59%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE08B5 1920x1080 309x174mm 14.0-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE089B 1280x800 261x163mm 12.1-inch                      | 1         | 1.59%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE07B6 1920x1080 382x215mm 17.3-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.59%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 1.59%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch            | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO328E 1920x1080 344x193mm 15.5-inch            | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch            | 1         | 1.59%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch            | 1         | 1.59%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 45.9%   |
| 1366x768 (WXGA)    | 19        | 31.15%  |
| 1280x800 (WXGA)    | 5         | 8.2%    |
| 1600x900 (HD+)     | 3         | 4.92%   |
| 3840x2160 (4K)     | 1         | 1.64%   |
| 2560x1600          | 1         | 1.64%   |
| 2560x1440 (QHD)    | 1         | 1.64%   |
| 1680x1050 (WSXGA+) | 1         | 1.64%   |
| 1440x900 (WXGA+)   | 1         | 1.64%   |
| 1280x1024 (SXGA)   | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 27        | 42.86%  |
| 14     | 14        | 22.22%  |
| 17     | 8         | 12.7%   |
| 13     | 4         | 6.35%   |
| 27     | 2         | 3.17%   |
| 18     | 2         | 3.17%   |
| 12     | 2         | 3.17%   |
| 31     | 1         | 1.59%   |
| 23     | 1         | 1.59%   |
| 22     | 1         | 1.59%   |
| 19     | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 43        | 69.35%  |
| 351-400     | 9         | 14.52%  |
| 201-300     | 4         | 6.45%   |
| 501-600     | 3         | 4.84%   |
| 401-500     | 2         | 3.23%   |
| 601-700     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 50        | 84.75%  |
| 16/10 | 8         | 13.56%  |
| 6/5   | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 42.86%  |
| 81-90          | 17        | 26.98%  |
| 121-130        | 7         | 11.11%  |
| 61-70          | 2         | 3.17%   |
| 301-350        | 2         | 3.17%   |
| 201-250        | 2         | 3.17%   |
| 141-150        | 2         | 3.17%   |
| 71-80          | 1         | 1.59%   |
| 351-500        | 1         | 1.59%   |
| 151-200        | 1         | 1.59%   |
| 131-140        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 45.16%  |
| 101-120       | 22        | 35.48%  |
| 51-100        | 8         | 12.9%   |
| 161-240       | 2         | 3.23%   |
| More than 240 | 1         | 1.61%   |
| 1-50          | 1         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 51        | 89.47%  |
| 2     | 5         | 8.77%   |
| 3     | 1         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 34        | 35.79%  |
| Realtek Semiconductor             | 28        | 29.47%  |
| Qualcomm Atheros                  | 15        | 15.79%  |
| Broadcom                          | 7         | 7.37%   |
| TP-Link                           | 2         | 2.11%   |
| Samsung Electronics               | 2         | 2.11%   |
| Xiaomi                            | 1         | 1.05%   |
| Ralink Technology                 | 1         | 1.05%   |
| Qualcomm Atheros Communications   | 1         | 1.05%   |
| NetGear                           | 1         | 1.05%   |
| Huawei Technologies               | 1         | 1.05%   |
| Ericsson Business Mobile Networks | 1         | 1.05%   |
| Broadcom Limited                  | 1         | 1.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 14        | 12.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 5         | 4.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 4.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 4         | 3.54%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 3.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 2.65%   |
| Intel Wireless 7265                                                       | 3         | 2.65%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 2.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 2.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 1.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.77%   |
| Intel Wireless 8260                                                       | 2         | 1.77%   |
| Intel Wireless 3160                                                       | 2         | 1.77%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.77%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.88%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.88%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.88%   |
| Realtek 802.11n                                                           | 1         | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 1         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.88%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.88%   |
| Intel Wireless 7260                                                       | 1         | 0.88%   |
| Intel Wireless 3165                                                       | 1         | 0.88%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.88%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.88%   |
| Intel Ethernet controller                                                 | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 0.88%   |
| Intel Centrino Wireless-N 105                                             | 1         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 0.88%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 0.88%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                  | 1         | 0.88%   |
| Huawei SNE-LX3                                                            | 1         | 0.88%   |
| Ericsson Business Mobile Networks N5321 gw                                | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                         | 1         | 0.88%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                    | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 32        | 50%     |
| Qualcomm Atheros                  | 12        | 18.75%  |
| Realtek Semiconductor             | 8         | 12.5%   |
| Broadcom                          | 5         | 7.81%   |
| TP-Link                           | 2         | 3.13%   |
| Ralink Technology                 | 1         | 1.56%   |
| Qualcomm Atheros Communications   | 1         | 1.56%   |
| NetGear                           | 1         | 1.56%   |
| Ericsson Business Mobile Networks | 1         | 1.56%   |
| Broadcom Limited                  | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 7.81%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 6.25%   |
| Intel Wireless 7265                                                       | 3         | 4.69%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 4.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 4.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 4.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 3.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 3.13%   |
| Intel Wireless 8260                                                       | 2         | 3.13%   |
| Intel Wireless 3160                                                       | 2         | 3.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 3.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 1.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.56%   |
| Realtek 802.11n                                                           | 1         | 1.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 1.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.56%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.56%   |
| Intel Wireless 7260                                                       | 1         | 1.56%   |
| Intel Wireless 3165                                                       | 1         | 1.56%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 1.56%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.56%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.56%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.56%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 1.56%   |
| Ericsson Business Mobile Networks N5321 gw                                | 1         | 1.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 23        | 47.92%  |
| Intel                 | 12        | 25%     |
| Qualcomm Atheros      | 6         | 12.5%   |
| Broadcom              | 3         | 6.25%   |
| Samsung Electronics   | 2         | 4.17%   |
| Xiaomi                | 1         | 2.08%   |
| Huawei Technologies   | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 28.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 10.2%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 8.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 6.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.12%   |
| Intel Ethernet Connection I217-V                                  | 2         | 4.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.04%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.04%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.04%   |
| Intel PRO/100 VE Network Connection                               | 1         | 2.04%   |
| Intel Ethernet controller                                         | 1         | 2.04%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.04%   |
| Huawei SNE-LX3                                                    | 1         | 2.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 55.45%  |
| Ethernet | 45        | 44.55%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 46        | 67.65%  |
| Ethernet | 22        | 32.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 70.18%  |
| 1     | 16        | 28.07%  |
| 0     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 72.41%  |
| Yes  | 16        | 27.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 54.76%  |
| Qualcomm Atheros Communications | 8         | 19.05%  |
| Broadcom                        | 4         | 9.52%   |
| Realtek Semiconductor           | 2         | 4.76%   |
| Lite-On Technology              | 1         | 2.38%   |
| Foxconn / Hon Hai               | 1         | 2.38%   |
| Dell                            | 1         | 2.38%   |
| Cambridge Silicon Radio         | 1         | 2.38%   |
| Apple                           | 1         | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 16.67%  |
| Intel AX201 Bluetooth                               | 7         | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 7.14%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 7.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.38%   |
| Realtek Bluetooth Radio                             | 1         | 2.38%   |
| Lite-On Bluetooth Radio                             | 1         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.38%   |
| Intel AX200 Bluetooth                               | 1         | 2.38%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.38%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.38%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.38%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.38%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.38%   |
| Apple Bluetooth Host Controller                     | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 53        | 74.65%  |
| Nvidia    | 12        | 16.9%   |
| AMD       | 5         | 7.04%   |
| GN Netcom | 1         | 1.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 4.76%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.57%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 2.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.19%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.19%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.19%   |
| Nvidia Audio device                                                        | 1         | 1.19%   |
| Intel USB PnP Sound Device                                                 | 1         | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.19%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.19%   |
| GN Netcom Jabra Evolve 65                                                  | 1         | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.19%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 32.61%  |
| SK Hynix            | 7         | 15.22%  |
| Unknown             | 4         | 8.7%    |
| Micron Technology   | 4         | 8.7%    |
| Kingston            | 3         | 6.52%   |
| Elpida              | 3         | 6.52%   |
| Crucial             | 3         | 6.52%   |
| Ramaxel Technology  | 2         | 4.35%   |
| A-DATA Technology   | 2         | 4.35%   |
| Team                | 1         | 2.17%   |
| G.Skill             | 1         | 2.17%   |
| Corsair             | 1         | 2.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 4.08%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 4.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 2.04%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 2.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 2.04%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 2.04%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 2.04%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 2.04%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 2.04%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.04%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 2.04%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 2.04%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 2.04%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                   | 1         | 2.04%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| SK Hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 2.04%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 2.04%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 2.04%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 2.04%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 2.04%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 2.04%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 2.04%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 2.04%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s             | 1         | 2.04%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 2.04%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s                  | 1         | 2.04%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s             | 1         | 2.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 2.04%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 2.04%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 2.04%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 1         | 2.04%   |
| Kingston RAM 9905469-066.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 2.04%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 2.04%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 1         | 2.04%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 1         | 2.04%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 2.04%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s            | 1         | 2.04%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s                   | 1         | 2.04%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s             | 1         | 2.04%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                         | 1         | 2.04%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s                | 1         | 2.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 18        | 45%     |
| DDR4   | 17        | 42.5%   |
| LPDDR4 | 3         | 7.5%    |
| DDR2   | 2         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 92.5%   |
| Row Of Chips | 3         | 7.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 17        | 36.96%  |
| 8192  | 13        | 28.26%  |
| 16384 | 6         | 13.04%  |
| 2048  | 6         | 13.04%  |
| 32768 | 2         | 4.35%   |
| 1024  | 2         | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 11        | 26.19%  |
| 1600    | 11        | 26.19%  |
| 3200    | 6         | 14.29%  |
| 1334    | 4         | 9.52%   |
| 3266    | 2         | 4.76%   |
| 4267    | 1         | 2.38%   |
| 2400    | 1         | 2.38%   |
| 1333    | 1         | 2.38%   |
| 1067    | 1         | 2.38%   |
| 1066    | 1         | 2.38%   |
| 667     | 1         | 2.38%   |
| 533     | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

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
| Chicony Electronics                    | 16        | 32.65%  |
| Acer                                   | 8         | 16.33%  |
| Microdia                               | 6         | 12.24%  |
| IMC Networks                           | 3         | 6.12%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.12%   |
| Sunplus Innovation Technology          | 2         | 4.08%   |
| Ricoh                                  | 2         | 4.08%   |
| Realtek Semiconductor                  | 2         | 4.08%   |
| Luxvisions Innotech Limited            | 2         | 4.08%   |
| Suyin                                  | 1         | 2.04%   |
| Silicon Motion                         | 1         | 2.04%   |
| Samsung Electronics                    | 1         | 2.04%   |
| Apple                                  | 1         | 2.04%   |
| Alcor Micro                            | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 6.12%   |
| Acer HD Webcam                                                             | 3         | 6.12%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 4.08%   |
| Chicony Integrated Camera                                                  | 2         | 4.08%   |
| Chicony HD Webcam                                                          | 2         | 4.08%   |
| Acer Integrated Camera                                                     | 2         | 4.08%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.04%   |
| Sunplus HD WebCam                                                          | 1         | 2.04%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 2.04%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 2.04%   |
| Ricoh Pavilion Webcam                                                      | 1         | 2.04%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 2.04%   |
| Microdia Webcam Vitade AF                                                  | 1         | 2.04%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 2.04%   |
| Microdia PC Microscope camera                                              | 1         | 2.04%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.04%   |
| Microdia Integrated Webcam HD                                              | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.04%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.04%   |
| IMC Networks Integrated Camera                                             | 1         | 2.04%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 2.04%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.04%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.04%   |
| Chicony HP Webcam                                                          | 1         | 2.04%   |
| Chicony HP TrueVision HD                                                   | 1         | 2.04%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2.04%   |
| Chicony HP HD Camera                                                       | 1         | 2.04%   |
| Chicony HD User Facing                                                     | 1         | 2.04%   |
| Chicony CNF8248                                                            | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.04%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.04%   |
| Alcor Micro USB 2.0 PC cam                                                 | 1         | 2.04%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.04%   |
| Acer HD Camera                                                             | 1         | 2.04%   |
| Acer EasyCamera                                                            | 1         | 2.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 63.64%  |
| Synaptics             | 1         | 9.09%   |
| LighTuning Technology | 1         | 9.09%   |
| Elan Microelectronics | 1         | 9.09%   |
| AuthenTec             | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner                                       | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 9.09%   |
| Validity Sensors VFS491                                                    | 1         | 9.09%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 9.09%   |
| Elan ELAN:Fingerprint                                                      | 1         | 9.09%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 9.09%   |
| Unknown                                                                    | 1         | 9.09%   |

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
| 0     | 33        | 56.9%   |
| 1     | 16        | 27.59%  |
| 2     | 8         | 13.79%  |
| 3     | 1         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 34.38%  |
| Graphics card         | 5         | 15.63%  |
| Chipcard              | 5         | 15.63%  |
| Storage               | 3         | 9.38%   |
| Net/wireless          | 3         | 9.38%   |
| Multimedia controller | 2         | 6.25%   |
| Modem                 | 1         | 3.13%   |
| Camera                | 1         | 3.13%   |
| Bluetooth             | 1         | 3.13%   |

