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

Total: 80

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire ES1-111M             | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 13-7359            | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
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
| 5.10.0-6parrot1-amd64    | 24        | 36.92%  |
| 5.10.0-8parrot1-amd64    | 14        | 21.54%  |
| 5.14.0-9parrot1-amd64    | 9         | 13.85%  |
| 5.7.0-2parrot2-amd64     | 3         | 4.62%   |
| 5.14.0-2parrot1-amd64    | 3         | 4.62%   |
| 5.10.0-5parrot1-amd64    | 3         | 4.62%   |
| 5.10.0-3parrot1-amd64    | 3         | 4.62%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.54%   |
| 5.18.0-14parrot1-amd64   | 1         | 1.54%   |
| 5.16.0-12parrot1-amd64   | 1         | 1.54%   |
| 5.15.0-15parrot1-amd64   | 1         | 1.54%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.54%   |
| Unknown                  | 1         | 1.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 45        | 69.23%  |
| 5.14.0  | 12        | 18.46%  |
| 5.7.0   | 3         | 4.62%   |
| 5.6.0   | 1         | 1.54%   |
| 5.18.0  | 1         | 1.54%   |
| 5.16.0  | 1         | 1.54%   |
| 5.15.0  | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 45        | 69.23%  |
| 5.14    | 12        | 18.46%  |
| 5.7     | 3         | 4.62%   |
| 5.6     | 1         | 1.54%   |
| 5.18    | 1         | 1.54%   |
| 5.16    | 1         | 1.54%   |
| 5.15    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 63        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 39        | 61.9%   |
| KDE5    | 13        | 20.63%  |
| KDE     | 6         | 9.52%   |
| Unknown | 3         | 4.76%   |
| XFCE    | 1         | 1.59%   |
| LXDE    | 1         | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 63        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 27        | 42.19%  |
| Unknown | 19        | 29.69%  |
| TDM     | 17        | 26.56%  |
| SDDM    | 1         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 32        | 50.79%  |
| en_GB   | 6         | 9.52%   |
| fr_FR   | 5         | 7.94%   |
| ru_RU   | 3         | 4.76%   |
| pt_BR   | 3         | 4.76%   |
| Unknown | 3         | 4.76%   |
| es_ES   | 2         | 3.17%   |
| de_DE   | 2         | 3.17%   |
| nl_BE   | 1         | 1.59%   |
| id_ID   | 1         | 1.59%   |
| es_CO   | 1         | 1.59%   |
| en_NG   | 1         | 1.59%   |
| en_AU   | 1         | 1.59%   |
| cs_CZ   | 1         | 1.59%   |
| arn_CL  | 1         | 1.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 36        | 56.25%  |
| EFI  | 28        | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 49        | 77.78%  |
| Ext4    | 8         | 12.7%   |
| Xfs     | 5         | 7.94%   |
| Overlay | 1         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 28        | 44.44%  |
| Unknown | 19        | 30.16%  |
| MBR     | 16        | 25.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 79.37%  |
| Yes       | 13        | 20.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 63.49%  |
| Yes       | 23        | 36.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 23.81%  |
| Dell                | 10        | 15.87%  |
| Lenovo              | 9         | 14.29%  |
| ASUSTek Computer    | 6         | 9.52%   |
| MSI                 | 4         | 6.35%   |
| Acer                | 4         | 6.35%   |
| Samsung Electronics | 2         | 3.17%   |
| Apple               | 2         | 3.17%   |
| Wortmann AG         | 1         | 1.59%   |
| Toxic               | 1         | 1.59%   |
| Toshiba             | 1         | 1.59%   |
| Timi                | 1         | 1.59%   |
| Sony                | 1         | 1.59%   |
| Positivo            | 1         | 1.59%   |
| GPU Company         | 1         | 1.59%   |
| Gateway             | 1         | 1.59%   |
| Fujitsu             | 1         | 1.59%   |
| Eluktronics         | 1         | 1.59%   |
| Alienware           | 1         | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP ProBook 650 G1                        | 2         | 3.17%   |
| ASUS Q524UQ                              | 2         | 3.17%   |
| Wortmann AG TERRA_MOBILE_1542            | 1         | 1.59%   |
| Toxic GM7MQ8P                            | 1         | 1.59%   |
| Toshiba Satellite L655                   | 1         | 1.59%   |
| Timi TM1613                              | 1         | 1.59%   |
| Sony SVP1321L1EBI                        | 1         | 1.59%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 1.59%   |
| Samsung 300E4C/300E5C/300E7C             | 1         | 1.59%   |
| Positivo Q232A                           | 1         | 1.59%   |
| MSI GT60 2OC/2OD                         | 1         | 1.59%   |
| MSI GE75 Raider 10SF                     | 1         | 1.59%   |
| MSI GE73 Raider RGB 8RE                  | 1         | 1.59%   |
| MSI GE63 Raider RGB 8RE                  | 1         | 1.59%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.59%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 1.59%   |
| Lenovo ThinkPad X260 20F5S5QT00          | 1         | 1.59%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 1.59%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003AMC | 1         | 1.59%   |
| Lenovo ThinkPad E15 20RD0086UE           | 1         | 1.59%   |
| Lenovo ThinkBook 15 G2 ARE 20VG          | 1         | 1.59%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 1         | 1.59%   |
| Lenovo B50-80 80EW                       | 1         | 1.59%   |
| HP ZBook 15 G5                           | 1         | 1.59%   |
| HP Pavilion Notebook                     | 1         | 1.59%   |
| HP Pavilion dv7                          | 1         | 1.59%   |
| HP Pavilion dv6700                       | 1         | 1.59%   |
| HP Pavilion dv6                          | 1         | 1.59%   |
| HP Pavilion dv4                          | 1         | 1.59%   |
| HP Laptop 15s-eq1xxx                     | 1         | 1.59%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.59%   |
| HP HDX PREMIUM SERIES                    | 1         | 1.59%   |
| HP EliteBook 850 G6                      | 1         | 1.59%   |
| HP EliteBook 8470p                       | 1         | 1.59%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.59%   |
| HP 250 G7 Notebook PC                    | 1         | 1.59%   |
| GPU Company GWTN141-10                   | 1         | 1.59%   |
| Gateway MP8708                           | 1         | 1.59%   |
| Fujitsu LIFEBOOK T731                    | 1         | 1.59%   |
| Eluktronics MAG-15u                      | 1         | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 6         | 9.52%   |
| HP Pavilion            | 5         | 7.94%   |
| Lenovo ThinkPad        | 4         | 6.35%   |
| HP EliteBook           | 3         | 4.76%   |
| Dell Latitude          | 3         | 4.76%   |
| HP ProBook             | 2         | 3.17%   |
| HP Laptop              | 2         | 3.17%   |
| ASUS Q524UQ            | 2         | 3.17%   |
| Acer Aspire            | 2         | 3.17%   |
| Wortmann AG TERRA      | 1         | 1.59%   |
| Toxic GM7MQ8P          | 1         | 1.59%   |
| Toshiba Satellite      | 1         | 1.59%   |
| Timi TM1613            | 1         | 1.59%   |
| Sony SVP1321L1EBI      | 1         | 1.59%   |
| Samsung 350V5C         | 1         | 1.59%   |
| Samsung 300E4C         | 1         | 1.59%   |
| Positivo Q232A         | 1         | 1.59%   |
| MSI GT60               | 1         | 1.59%   |
| MSI GE75               | 1         | 1.59%   |
| MSI GE73               | 1         | 1.59%   |
| MSI GE63               | 1         | 1.59%   |
| Lenovo Yoga            | 1         | 1.59%   |
| Lenovo Y520-15IKBN     | 1         | 1.59%   |
| Lenovo ThinkBook       | 1         | 1.59%   |
| Lenovo IdeaPad         | 1         | 1.59%   |
| Lenovo B50-80          | 1         | 1.59%   |
| HP ZBook               | 1         | 1.59%   |
| HP HDX                 | 1         | 1.59%   |
| HP 250                 | 1         | 1.59%   |
| GPU Company GWTN141-10 | 1         | 1.59%   |
| Gateway MP8708         | 1         | 1.59%   |
| Fujitsu LIFEBOOK       | 1         | 1.59%   |
| Eluktronics MAG-15u    | 1         | 1.59%   |
| Dell Precision         | 1         | 1.59%   |
| ASUS X75VB             | 1         | 1.59%   |
| ASUS X450EA            | 1         | 1.59%   |
| ASUS VivoBook          | 1         | 1.59%   |
| ASUS G74Sx             | 1         | 1.59%   |
| Apple MacBookPro8      | 1         | 1.59%   |
| Apple MacBookPro11     | 1         | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 9         | 14.29%  |
| 2013 | 8         | 12.7%   |
| 2020 | 7         | 11.11%  |
| 2011 | 6         | 9.52%   |
| 2018 | 5         | 7.94%   |
| 2016 | 5         | 7.94%   |
| 2021 | 4         | 6.35%   |
| 2015 | 4         | 6.35%   |
| 2012 | 3         | 4.76%   |
| 2010 | 3         | 4.76%   |
| 2008 | 3         | 4.76%   |
| 2014 | 2         | 3.17%   |
| 2007 | 2         | 3.17%   |
| 2017 | 1         | 1.59%   |
| 2006 | 1         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 63        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 63        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 63        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 17        | 26.98%  |
| 8.01-16.0   | 14        | 22.22%  |
| 16.01-24.0  | 13        | 20.63%  |
| 3.01-4.0    | 11        | 17.46%  |
| 32.01-64.0  | 3         | 4.76%   |
| 1.01-2.0    | 2         | 3.17%   |
| 24.01-32.0  | 1         | 1.59%   |
| 2.01-3.0    | 1         | 1.59%   |
| 64.01-256.0 | 1         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 25        | 37.88%  |
| 2.01-3.0  | 21        | 31.82%  |
| 3.01-4.0  | 12        | 18.18%  |
| 4.01-8.0  | 7         | 10.61%  |
| 8.01-16.0 | 1         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 42        | 66.67%  |
| 2      | 18        | 28.57%  |
| 3      | 3         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 40        | 63.49%  |
| Yes       | 23        | 36.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 76.19%  |
| No        | 15        | 23.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 98.41%  |
| No        | 1         | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 74.6%   |
| No        | 16        | 25.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 20        | 31.75%  |
| Germany      | 5         | 7.94%   |
| France       | 5         | 7.94%   |
| Spain        | 4         | 6.35%   |
| UK           | 3         | 4.76%   |
| Russia       | 3         | 4.76%   |
| Brazil       | 3         | 4.76%   |
| Netherlands  | 2         | 3.17%   |
| Iraq         | 2         | 3.17%   |
| Czechia      | 2         | 3.17%   |
| Sweden       | 1         | 1.59%   |
| South Africa | 1         | 1.59%   |
| Puerto Rico  | 1         | 1.59%   |
| Nigeria      | 1         | 1.59%   |
| Mexico       | 1         | 1.59%   |
| Kenya        | 1         | 1.59%   |
| Indonesia    | 1         | 1.59%   |
| Hungary      | 1         | 1.59%   |
| Colombia     | 1         | 1.59%   |
| Chile        | 1         | 1.59%   |
| Belgium      | 1         | 1.59%   |
| Bangladesh   | 1         | 1.59%   |
| Azerbaijan   | 1         | 1.59%   |
| Australia    | 1         | 1.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dallas                | 2         | 3.13%   |
| Chicago               | 2         | 3.13%   |
| West Jordan           | 1         | 1.56%   |
| Visalia               | 1         | 1.56%   |
| Veitsbronn            | 1         | 1.56%   |
| Tangerang             | 1         | 1.56%   |
| Stockholm             | 1         | 1.56%   |
| St Petersburg         | 1         | 1.56%   |
| Sinntal               | 1         | 1.56%   |
| Shelbyville           | 1         | 1.56%   |
| Secaucus              | 1         | 1.56%   |
| Santo André          | 1         | 1.56%   |
| Santiago              | 1         | 1.56%   |
| Sant Boi de Llobregat | 1         | 1.56%   |
| Sannois               | 1         | 1.56%   |
| Rotterdam             | 1         | 1.56%   |
| Rialma                | 1         | 1.56%   |
| Reus                  | 1         | 1.56%   |
| Regensburg            | 1         | 1.56%   |
| Reading               | 1         | 1.56%   |
| Pretoria              | 1         | 1.56%   |
| Prague                | 1         | 1.56%   |
| Ponce                 | 1         | 1.56%   |
| Paris                 | 1         | 1.56%   |
| Omaha                 | 1         | 1.56%   |
| New Orleans           | 1         | 1.56%   |
| Nairobi               | 1         | 1.56%   |
| Munich                | 1         | 1.56%   |
| Melbourne             | 1         | 1.56%   |
| Marietta              | 1         | 1.56%   |
| Manaus                | 1         | 1.56%   |
| Maggie Valley         | 1         | 1.56%   |
| Lyon                  | 1         | 1.56%   |
| Los Mochis            | 1         | 1.56%   |
| Longmont              | 1         | 1.56%   |
| Long Beach            | 1         | 1.56%   |
| London                | 1         | 1.56%   |
| Lancaster             | 1         | 1.56%   |
| Khabarovsk            | 1         | 1.56%   |
| Kano                  | 1         | 1.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 12.05%  |
| Samsung Electronics | 10        | 11     | 12.05%  |
| Unknown             | 7         | 7      | 8.43%   |
| Crucial             | 7         | 10     | 8.43%   |
| Seagate             | 6         | 6      | 7.23%   |
| Kingston            | 6         | 6      | 7.23%   |
| Toshiba             | 5         | 6      | 6.02%   |
| SanDisk             | 4         | 4      | 4.82%   |
| SK hynix            | 3         | 3      | 3.61%   |
| Micron Technology   | 3         | 3      | 3.61%   |
| Hitachi             | 3         | 3      | 3.61%   |
| HGST                | 3         | 3      | 3.61%   |
| A-DATA Technology   | 3         | 3      | 3.61%   |
| KIOXIA              | 2         | 3      | 2.41%   |
| China               | 2         | 2      | 2.41%   |
| W800SH              | 1         | 1      | 1.2%    |
| Team                | 1         | 1      | 1.2%    |
| PNY                 | 1         | 1      | 1.2%    |
| Patriot             | 1         | 1      | 1.2%    |
| Lexar               | 1         | 1      | 1.2%    |
| Intel               | 1         | 1      | 1.2%    |
| HS-SSD-C100         | 1         | 1      | 1.2%    |
| Corsair             | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 2.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 2         | 2.33%   |
| SanDisk SSD PLUS 1000GB                 | 2         | 2.33%   |
| Samsung SSD 860 EVO 500GB               | 2         | 2.33%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 2.33%   |
| HGST HTS541010A9E680 1TB                | 2         | 2.33%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 2.33%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 1.16%   |
| WDC WDBNCE2500PNC 250GB SSD             | 1         | 1.16%   |
| WDC WD800BEVS-22RST0 80GB               | 1         | 1.16%   |
| WDC WD3200LPVX-00V0TT0 320GB            | 1         | 1.16%   |
| WDC WD2500BPVT-00JJ5T0 250GB            | 1         | 1.16%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 1.16%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 1.16%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 1.16%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB    | 1         | 1.16%   |
| W800SH 512GB SSD                        | 1         | 1.16%   |
| Unknown Y016B  16GB                     | 1         | 1.16%   |
| Unknown xD/SD/M.S.                      | 1         | 1.16%   |
| Unknown SS16G  16GB                     | 1         | 1.16%   |
| Unknown SS08G  8GB                      | 1         | 1.16%   |
| Unknown SDU1  64GB                      | 1         | 1.16%   |
| Unknown SD/MMC/MS PRO 64GB              | 1         | 1.16%   |
| Unknown MMC Card  128GB                 | 1         | 1.16%   |
| Toshiba THNSNH128G8NT 128GB SSD         | 1         | 1.16%   |
| Toshiba THNSNF128GMCS 128GB SSD         | 1         | 1.16%   |
| Toshiba Q300 480GB SSD                  | 1         | 1.16%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1.16%   |
| Toshiba MK7575GSX 752GB                 | 1         | 1.16%   |
| Team TM8PS7512G 512GB SSD               | 1         | 1.16%   |
| SK hynix NVMe SSD Drive 512GB           | 1         | 1.16%   |
| SK hynix HFM256GDJTNI-82A0A 256GB       | 1         | 1.16%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 1.16%   |
| Seagate ST9500420AS 500GB               | 1         | 1.16%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 1.16%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 1.16%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 1.16%   |
| SanDisk Extreme SSD 500GB               | 1         | 1.16%   |
| SanDisk DF4032  32GB                    | 1         | 1.16%   |
| Samsung SSD 980 1TB                     | 1         | 1.16%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 8      | 31.82%  |
| Seagate | 6         | 6      | 27.27%  |
| Hitachi | 3         | 3      | 13.64%  |
| HGST    | 3         | 3      | 13.64%  |
| Toshiba | 2         | 2      | 9.09%   |
| Unknown | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 6         | 9      | 18.75%  |
| Kingston            | 4         | 4      | 12.5%   |
| Toshiba             | 3         | 4      | 9.38%   |
| SanDisk             | 3         | 3      | 9.38%   |
| Samsung Electronics | 3         | 3      | 9.38%   |
| China               | 2         | 2      | 6.25%   |
| WDC                 | 1         | 1      | 3.13%   |
| W800SH              | 1         | 1      | 3.13%   |
| Team                | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Patriot             | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| HS-SSD-C100         | 1         | 1      | 3.13%   |
| Corsair             | 1         | 1      | 3.13%   |
| Apple               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 28        | 36     | 36.36%  |
| NVMe    | 22        | 25     | 28.57%  |
| HDD     | 21        | 23     | 27.27%  |
| MMC     | 5         | 6      | 6.49%   |
| Unknown | 1         | 1      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 57     | 60.53%  |
| NVMe | 22        | 25     | 28.95%  |
| MMC  | 5         | 6      | 6.58%   |
| SAS  | 3         | 3      | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 40     | 63.27%  |
| 0.51-1.0   | 15        | 16     | 30.61%  |
| 1.01-2.0   | 3         | 3      | 6.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 18        | 28.57%  |
| 101-250        | 16        | 25.4%   |
| 501-1000       | 10        | 15.87%  |
| 1001-2000      | 6         | 9.52%   |
| Unknown        | 6         | 9.52%   |
| 51-100         | 3         | 4.76%   |
| More than 3000 | 2         | 3.17%   |
| 21-50          | 1         | 1.59%   |
| 2001-3000      | 1         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 17        | 26.56%  |
| 21-50     | 14        | 21.88%  |
| 1-20      | 9         | 14.06%  |
| 101-250   | 8         | 12.5%   |
| 251-500   | 7         | 10.94%  |
| Unknown   | 6         | 9.38%   |
| 501-1000  | 2         | 3.13%   |
| 1001-2000 | 1         | 1.56%   |

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
| Works    | 39        | 49     | 56.52%  |
| Detected | 25        | 36     | 36.23%  |
| Malfunc  | 5         | 6      | 7.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 53        | 66.25%  |
| Samsung Electronics         | 8         | 10%     |
| SK hynix                    | 3         | 3.75%   |
| SanDisk                     | 3         | 3.75%   |
| AMD                         | 3         | 3.75%   |
| Micron Technology           | 2         | 2.5%    |
| KIOXIA                      | 2         | 2.5%    |
| Kingston Technology Company | 2         | 2.5%    |
| Silicon Motion              | 1         | 1.25%   |
| Realtek Semiconductor       | 1         | 1.25%   |
| Micron/Crucial Technology   | 1         | 1.25%   |
| ADATA Technology            | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 5.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.49%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 3.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 3.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.49%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 3.49%   |
| SK hynix BC511                                                                 | 2         | 2.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 2.33%   |
| Micron Non-Volatile memory controller                                          | 2         | 2.33%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 2.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 2.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 2.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 1.16%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 1.16%   |
| Samsung Apple PCIe SSD                                                         | 1         | 1.16%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1         | 1.16%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 1.16%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 1.16%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.16%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 1         | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 52        | 63.41%  |
| NVMe | 22        | 26.83%  |
| IDE  | 5         | 6.1%    |
| RAID | 3         | 3.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 93.65%  |
| AMD    | 4         | 6.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 4.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 4.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 3.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 3.17%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 3.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 3.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 3.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 3.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 3.17%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.59%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.59%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.59%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.59%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.59%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.59%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.59%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.59%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.59%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.59%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.59%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.59%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.59%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.59%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.59%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 1.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.59%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.59%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.59%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 1.59%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.59%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 34.92%  |
| Intel Core i7           | 20        | 31.75%  |
| Other                   | 5         | 7.94%   |
| Intel Core i3           | 3         | 4.76%   |
| Intel Pentium Silver    | 2         | 3.17%   |
| Intel Core 2 Duo        | 2         | 3.17%   |
| Intel Pentium Dual-Core | 1         | 1.59%   |
| Intel Core 2 Quad       | 1         | 1.59%   |
| Intel Core 2            | 1         | 1.59%   |
| Intel Celeron           | 1         | 1.59%   |
| Intel Atom              | 1         | 1.59%   |
| AMD Ryzen 7             | 1         | 1.59%   |
| AMD Ryzen 5             | 1         | 1.59%   |
| AMD Ryzen 3             | 1         | 1.59%   |
| AMD E1                  | 1         | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 32        | 50.79%  |
| 4      | 23        | 36.51%  |
| 6      | 5         | 7.94%   |
| 8      | 3         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 63        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 77.78%  |
| 1      | 14        | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 63        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 35.94%  |
| 0x206a7    | 5         | 7.81%   |
| 0x806ec    | 4         | 6.25%   |
| 0x806c1    | 3         | 4.69%   |
| 0x306c3    | 3         | 4.69%   |
| 0xa0652    | 2         | 3.13%   |
| 0x706e5    | 2         | 3.13%   |
| 0x406e3    | 2         | 3.13%   |
| 0x306d4    | 2         | 3.13%   |
| 0x306a9    | 2         | 3.13%   |
| 0x1067a    | 2         | 3.13%   |
| 0x08600106 | 2         | 3.13%   |
| 0x906e9    | 1         | 1.56%   |
| 0x806d1    | 1         | 1.56%   |
| 0x806c2    | 1         | 1.56%   |
| 0x706a8    | 1         | 1.56%   |
| 0x706a1    | 1         | 1.56%   |
| 0x6fd      | 1         | 1.56%   |
| 0x6f6      | 1         | 1.56%   |
| 0x506e3    | 1         | 1.56%   |
| 0x40651    | 1         | 1.56%   |
| 0x30678    | 1         | 1.56%   |
| 0x20655    | 1         | 1.56%   |
| 0x08108109 | 1         | 1.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 14.29%  |
| Skylake       | 7         | 11.11%  |
| SandyBridge   | 7         | 11.11%  |
| IvyBridge     | 6         | 9.52%   |
| Haswell       | 6         | 9.52%   |
| TigerLake     | 4         | 6.35%   |
| Penryn        | 3         | 4.76%   |
| Icelake       | 3         | 4.76%   |
| CometLake     | 3         | 4.76%   |
| Broadwell     | 3         | 4.76%   |
| Zen 2         | 2         | 3.17%   |
| Westmere      | 2         | 3.17%   |
| Silvermont    | 2         | 3.17%   |
| Goldmont plus | 2         | 3.17%   |
| Core          | 2         | 3.17%   |
| Zen+          | 1         | 1.59%   |
| Jaguar        | 1         | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 65.06%  |
| Nvidia | 19        | 22.89%  |
| AMD    | 10        | 12.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 6         | 6.98%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 5.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 5.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.65%   |
| Intel HD Graphics 5500                                                        | 3         | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 3.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 3         | 3.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 3.49%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 2.33%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.33%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.33%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.33%   |
| AMD Renoir                                                                    | 2         | 2.33%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 1.16%   |
| Nvidia TU117M                                                                 | 1         | 1.16%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.16%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 1.16%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.16%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.16%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 1.16%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.16%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.16%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.16%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.16%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.16%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.16%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                        | 1         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.16%   |
| Intel HD Graphics 630                                                         | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 53.97%  |
| Intel + Nvidia | 16        | 25.4%   |
| 1 x AMD        | 6         | 9.52%   |
| Intel + AMD    | 4         | 6.35%   |
| 1 x Nvidia     | 3         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 60        | 95.24%  |
| Proprietary | 3         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 77.78%  |
| 0.51-1.0   | 5         | 7.94%   |
| 1.01-2.0   | 4         | 6.35%   |
| 3.01-4.0   | 2         | 3.17%   |
| 7.01-8.0   | 1         | 1.59%   |
| 2.01-3.0   | 1         | 1.59%   |
| 0.01-0.5   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 17.81%  |
| AU Optronics            | 13        | 17.81%  |
| BOE                     | 11        | 15.07%  |
| Samsung Electronics     | 10        | 13.7%   |
| Chimei Innolux          | 9         | 12.33%  |
| Chi Mei Optoelectronics | 4         | 5.48%   |
| Sceptre Tech            | 2         | 2.74%   |
| Dell                    | 2         | 2.74%   |
| Apple                   | 2         | 2.74%   |
| STA                     | 1         | 1.37%   |
| Sharp                   | 1         | 1.37%   |
| Philips                 | 1         | 1.37%   |
| Panasonic               | 1         | 1.37%   |
| Lenovo                  | 1         | 1.37%   |
| Hewlett-Packard         | 1         | 1.37%   |
| Ancor Communications    | 1         | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 2.74%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 1.37%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 1.37%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 1.37%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch        | 1         | 1.37%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 1.37%   |
| Samsung Electronics LCD Monitor SAM0F3D 1360x768 522x293mm 23.6-inch  | 1         | 1.37%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1         | 1.37%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 1.37%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 1.37%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0683 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD066D 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 1.37%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 1         | 1.37%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 1.37%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 698x393mm 31.5-inch              | 1         | 1.37%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 1.37%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                    | 1         | 1.37%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                     | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch       | 1         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch      | 1         | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 33        | 47.83%  |
| 1366x768 (WXGA)    | 20        | 28.99%  |
| 1280x800 (WXGA)    | 5         | 7.25%   |
| 1600x900 (HD+)     | 3         | 4.35%   |
| 2560x1440 (QHD)    | 2         | 2.9%    |
| 3840x2160 (4K)     | 1         | 1.45%   |
| 2560x1600          | 1         | 1.45%   |
| 2560x1080          | 1         | 1.45%   |
| 1680x1050 (WSXGA+) | 1         | 1.45%   |
| 1440x900 (WXGA+)   | 1         | 1.45%   |
| 1280x1024 (SXGA)   | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 29        | 39.73%  |
| 14     | 15        | 20.55%  |
| 17     | 8         | 10.96%  |
| 13     | 7         | 9.59%   |
| 31     | 2         | 2.74%   |
| 27     | 2         | 2.74%   |
| 18     | 2         | 2.74%   |
| 12     | 2         | 2.74%   |
| 32     | 1         | 1.37%   |
| 29     | 1         | 1.37%   |
| 23     | 1         | 1.37%   |
| 22     | 1         | 1.37%   |
| 21     | 1         | 1.37%   |
| 19     | 1         | 1.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 47        | 65.28%  |
| 351-400     | 9         | 12.5%   |
| 201-300     | 6         | 8.33%   |
| 601-700     | 3         | 4.17%   |
| 501-600     | 3         | 4.17%   |
| 401-500     | 3         | 4.17%   |
| 701-800     | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 56        | 84.85%  |
| 16/10 | 8         | 12.12%  |
| 6/5   | 1         | 1.52%   |
| 21/9  | 1         | 1.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 39.73%  |
| 81-90          | 19        | 26.03%  |
| 121-130        | 7         | 9.59%   |
| 71-80          | 3         | 4.11%   |
| 351-500        | 3         | 4.11%   |
| 301-350        | 3         | 4.11%   |
| 201-250        | 3         | 4.11%   |
| 61-70          | 2         | 2.74%   |
| 141-150        | 2         | 2.74%   |
| 151-200        | 1         | 1.37%   |
| 131-140        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 43.06%  |
| 101-120       | 24        | 33.33%  |
| 51-100        | 11        | 15.28%  |
| 161-240       | 4         | 5.56%   |
| More than 240 | 1         | 1.39%   |
| 1-50          | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 54        | 85.71%  |
| 2     | 7         | 11.11%  |
| 3     | 2         | 3.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 38.61%  |
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
| Ericsson Business Mobile Networks | 1         | 0.99%   |
| Broadcom Limited                  | 1         | 0.99%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 13.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 4.13%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 2.48%   |
| Intel Wireless 8260                                               | 3         | 2.48%   |
| Intel Wireless 7265                                               | 3         | 2.48%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 2.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.48%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.65%   |
| Intel Wireless 7260                                               | 2         | 1.65%   |
| Intel Wireless 3165                                               | 2         | 1.65%   |
| Intel Wireless 3160                                               | 2         | 1.65%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.65%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.65%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.83%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.83%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.83%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.83%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 53.62%  |
| Qualcomm Atheros                | 12        | 17.39%  |
| Realtek Semiconductor           | 9         | 13.04%  |
| Broadcom                        | 5         | 7.25%   |
| TP-Link                         | 2         | 2.9%    |
| Ralink Technology               | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| NetGear                         | 1         | 1.45%   |
| Broadcom Limited                | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 7.25%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 5.8%    |
| Intel Wireless 8260                                                       | 3         | 4.35%   |
| Intel Wireless 7265                                                       | 3         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 3         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 2.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 2.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.9%    |
| Intel Wireless 7260                                                       | 2         | 2.9%    |
| Intel Wireless 3165                                                       | 2         | 2.9%    |
| Intel Wireless 3160                                                       | 2         | 2.9%    |
| Intel Wi-Fi 6 AX200                                                       | 2         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 2.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1         | 1.45%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 1.45%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 1.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.45%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.45%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 1.45%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.45%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.45%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.45%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 24        | 48%     |
| Intel                 | 13        | 26%     |
| Qualcomm Atheros      | 6         | 12%     |
| Broadcom              | 3         | 6%      |
| Samsung Electronics   | 2         | 4%      |
| Xiaomi                | 1         | 2%      |
| Lenovo                | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 31.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 9.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.88%   |
| Intel Ethernet Connection I217-V                                  | 2         | 3.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.96%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.96%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.96%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.96%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.96%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.96%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.96%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 55.86%  |
| Ethernet | 48        | 43.24%  |
| Modem    | 1         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 75%     |
| Ethernet | 17        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 68.25%  |
| 1     | 19        | 30.16%  |
| 0     | 1         | 1.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 75%     |
| Yes  | 16        | 25%     |

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
| Intel Bluetooth wireless interface                  | 9         | 19.15%  |
| Intel AX201 Bluetooth                               | 8         | 17.02%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 14.89%  |
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
| Intel     | 58        | 75.32%  |
| Nvidia    | 11        | 14.29%  |
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
| Intel Sunrise Point-LP HD Audio                                            | 6         | 6.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 6.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 4.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 4.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.3%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 3.3%    |
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
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 1.1%    |
| Intel USB PnP Sound Device                                                 | 1         | 1.1%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.1%    |
| Intel CM238 HD Audio Controller                                            | 1         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.1%    |
| GN Netcom Jabra EVOLVE 65                                                  | 1         | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.1%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 32.69%  |
| SK hynix            | 8         | 15.38%  |
| Micron Technology   | 5         | 9.62%   |
| Unknown             | 4         | 7.69%   |
| Crucial             | 4         | 7.69%   |
| Kingston            | 3         | 5.77%   |
| Elpida              | 3         | 5.77%   |
| Team                | 2         | 3.85%   |
| Ramaxel Technology  | 2         | 3.85%   |
| A-DATA Technology   | 2         | 3.85%   |
| G.Skill             | 1         | 1.92%   |
| Corsair             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 1.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 1.82%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 1.82%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 1.82%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.82%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.82%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM H9HCNNNBKMALHR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.82%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                    | 1         | 1.82%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.82%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.82%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.82%   |
| Ramaxel RAM RMT3170MN68F9F1600 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.82%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.82%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s               | 1         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.82%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.82%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 44.44%  |
| DDR3   | 19        | 42.22%  |
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
| 8192  | 18        | 35.29%  |
| 4096  | 17        | 33.33%  |
| 16384 | 7         | 13.73%  |
| 2048  | 6         | 11.76%  |
| 1024  | 2         | 3.92%   |
| 32768 | 1         | 1.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 24.49%  |
| 2667    | 11        | 22.45%  |
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
| Chicony Electronics                    | 17        | 32.08%  |
| Acer                                   | 7         | 13.21%  |
| Microdia                               | 6         | 11.32%  |
| IMC Networks                           | 4         | 7.55%   |
| Sunplus Innovation Technology          | 3         | 5.66%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.66%   |
| Ricoh                                  | 2         | 3.77%   |
| Realtek Semiconductor                  | 2         | 3.77%   |
| Luxvisions Innotech Limited            | 2         | 3.77%   |
| Syntek                                 | 1         | 1.89%   |
| Suyin                                  | 1         | 1.89%   |
| Silicon Motion                         | 1         | 1.89%   |
| Samsung Electronics                    | 1         | 1.89%   |
| Quanta                                 | 1         | 1.89%   |
| Apple                                  | 1         | 1.89%   |
| Alcor Micro                            | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 5.66%   |
| Acer HD Webcam                                                             | 3         | 5.66%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.77%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 3.77%   |
| IMC Networks Integrated Camera                                             | 2         | 3.77%   |
| Chicony Integrated Camera                                                  | 2         | 3.77%   |
| Chicony HD Webcam                                                          | 2         | 3.77%   |
| Acer Integrated Camera                                                     | 2         | 3.77%   |
| Syntek Integrated Camera                                                   | 1         | 1.89%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.89%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.89%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.89%   |
| Sunplus HD WebCam                                                          | 1         | 1.89%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 1.89%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.89%   |
| Ricoh Pavilion Webcam                                                      | 1         | 1.89%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.89%   |
| Quanta HP HD Camera                                                        | 1         | 1.89%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.89%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 1.89%   |
| Microdia PC Microscope camera                                              | 1         | 1.89%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 1.89%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.89%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.89%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.89%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.89%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 1.89%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.89%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.89%   |
| Chicony HP Webcam                                                          | 1         | 1.89%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.89%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.89%   |
| Chicony HP HD Camera                                                       | 1         | 1.89%   |
| Chicony HD User Facing                                                     | 1         | 1.89%   |
| Chicony CNF8248                                                            | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.89%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.89%   |

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
| 0     | 38        | 60.32%  |
| 1     | 16        | 25.4%   |
| 2     | 8         | 12.7%   |
| 3     | 1         | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 39.39%  |
| Chipcard              | 5         | 15.15%  |
| Net/wireless          | 4         | 12.12%  |
| Graphics card         | 4         | 12.12%  |
| Storage               | 3         | 9.09%   |
| Multimedia controller | 2         | 6.06%   |
| Modem                 | 1         | 3.03%   |
| Camera                | 1         | 3.03%   |

