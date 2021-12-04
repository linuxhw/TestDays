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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-6parrot1-amd64    | 21        | 40.38%  |
| 5.10.0-8parrot1-amd64    | 13        | 25%     |
| 5.14.0-9parrot1-amd64    | 5         | 9.62%   |
| 5.7.0-2parrot2-amd64     | 3         | 5.77%   |
| 5.10.0-5parrot1-amd64    | 3         | 5.77%   |
| 5.10.0-3parrot1-amd64    | 3         | 5.77%   |
| 5.14.0-2parrot1-amd64    | 2         | 3.85%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.92%   |
| Unknown                  | 1         | 1.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 41        | 78.85%  |
| 5.14.0  | 7         | 13.46%  |
| 5.7.0   | 3         | 5.77%   |
| Unknown | 1         | 1.92%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 41        | 78.85%  |
| 5.14    | 7         | 13.46%  |
| 5.7     | 3         | 5.77%   |
| Unknown | 1         | 1.92%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 51        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 31        | 60.78%  |
| KDE5    | 9         | 17.65%  |
| KDE     | 6         | 11.76%  |
| Unknown | 3         | 5.88%   |
| XFCE    | 1         | 1.96%   |
| LXDE    | 1         | 1.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 51        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 36.54%  |
| TDM     | 17        | 32.69%  |
| LightDM | 15        | 28.85%  |
| SDDM    | 1         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 23        | 45.1%   |
| en_GB   | 5         | 9.8%    |
| fr_FR   | 4         | 7.84%   |
| ru_RU   | 3         | 5.88%   |
| pt_BR   | 3         | 5.88%   |
| Unknown | 3         | 5.88%   |
| es_ES   | 2         | 3.92%   |
| de_DE   | 2         | 3.92%   |
| nl_BE   | 1         | 1.96%   |
| id_ID   | 1         | 1.96%   |
| es_CO   | 1         | 1.96%   |
| en_NG   | 1         | 1.96%   |
| en_AU   | 1         | 1.96%   |
| cs_CZ   | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 34        | 65.38%  |
| EFI  | 18        | 34.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 40        | 78.43%  |
| Ext4  | 7         | 13.73%  |
| Xfs   | 4         | 7.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 19        | 37.25%  |
| GPT     | 18        | 35.29%  |
| MBR     | 14        | 27.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 42        | 82.35%  |
| Yes       | 9         | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 64.71%  |
| Yes       | 18        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 23.53%  |
| Dell                | 8         | 15.69%  |
| ASUSTek Computer    | 6         | 11.76%  |
| MSI                 | 5         | 9.8%    |
| Lenovo              | 5         | 9.8%    |
| Acer                | 3         | 5.88%   |
| Samsung Electronics | 2         | 3.92%   |
| Apple               | 2         | 3.92%   |
| Wortmann AG         | 1         | 1.96%   |
| Toxic               | 1         | 1.96%   |
| Toshiba             | 1         | 1.96%   |
| Quanta              | 1         | 1.96%   |
| Gateway             | 1         | 1.96%   |
| Fujitsu             | 1         | 1.96%   |
| Eluktronics         | 1         | 1.96%   |
| Alienware           | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 3.92%   |
| ASUS Q524UQ                             | 2         | 3.92%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 1.96%   |
| Toxic GM7MQ8P                           | 1         | 1.96%   |
| Toshiba Satellite L655                  | 1         | 1.96%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.96%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 1.96%   |
| Quanta HDX PREMIUM SERIES               | 1         | 1.96%   |
| MSI GT60 2OC/2OD                        | 1         | 1.96%   |
| MSI GS66 Stealth 10UG                   | 1         | 1.96%   |
| MSI GE75 Raider 10SF                    | 1         | 1.96%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 1.96%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 1.96%   |
| Lenovo Yoga S740-14IIL 81RS             | 1         | 1.96%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 1.96%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 1.96%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 1.96%   |
| Lenovo B50-80 80EW                      | 1         | 1.96%   |
| HP ZBook 15 G5                          | 1         | 1.96%   |
| HP Pavilion Notebook                    | 1         | 1.96%   |
| HP Pavilion dv7                         | 1         | 1.96%   |
| HP Pavilion dv6700                      | 1         | 1.96%   |
| HP Pavilion dv6                         | 1         | 1.96%   |
| HP Pavilion dv4                         | 1         | 1.96%   |
| HP Laptop 15s-eq1xxx                    | 1         | 1.96%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.96%   |
| HP EliteBook 840 G8 Notebook PC         | 1         | 1.96%   |
| HP 250 G7 Notebook PC                   | 1         | 1.96%   |
| Gateway MP8708                          | 1         | 1.96%   |
| Fujitsu LIFEBOOK T731                   | 1         | 1.96%   |
| Eluktronics MAG-15u                     | 1         | 1.96%   |
| Dell Precision M4600                    | 1         | 1.96%   |
| Dell Latitude E7440                     | 1         | 1.96%   |
| Dell Latitude E6420                     | 1         | 1.96%   |
| Dell Latitude E6410                     | 1         | 1.96%   |
| Dell Inspiron 7501                      | 1         | 1.96%   |
| Dell Inspiron 5593                      | 1         | 1.96%   |
| Dell Inspiron 5558                      | 1         | 1.96%   |
| Dell Inspiron 5420                      | 1         | 1.96%   |
| ASUS X75VB                              | 1         | 1.96%   |
| ASUS X450EA                             | 1         | 1.96%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 1.96%   |
| ASUS G74Sx                              | 1         | 1.96%   |
| Apple MacBookPro8,1                     | 1         | 1.96%   |
| Apple MacBookPro11,1                    | 1         | 1.96%   |
| Alienware m15 R6                        | 1         | 1.96%   |
| Acer TravelMate 5720                    | 1         | 1.96%   |
| Acer Swift SF114-33                     | 1         | 1.96%   |
| Acer Aspire E1-571G                     | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| HP Pavilion         | 5         | 9.8%    |
| Dell Inspiron       | 4         | 7.84%   |
| Dell Latitude       | 3         | 5.88%   |
| Lenovo ThinkPad     | 2         | 3.92%   |
| HP ProBook          | 2         | 3.92%   |
| HP Laptop           | 2         | 3.92%   |
| ASUS Q524UQ         | 2         | 3.92%   |
| Wortmann AG TERRA   | 1         | 1.96%   |
| Toxic GM7MQ8P       | 1         | 1.96%   |
| Toshiba Satellite   | 1         | 1.96%   |
| Samsung 350V5C      | 1         | 1.96%   |
| Samsung 300E4C      | 1         | 1.96%   |
| Quanta HDX          | 1         | 1.96%   |
| MSI GT60            | 1         | 1.96%   |
| MSI GS66            | 1         | 1.96%   |
| MSI GE75            | 1         | 1.96%   |
| MSI GE73            | 1         | 1.96%   |
| MSI GE63            | 1         | 1.96%   |
| Lenovo Yoga         | 1         | 1.96%   |
| Lenovo Y520-15IKBN  | 1         | 1.96%   |
| Lenovo B50-80       | 1         | 1.96%   |
| HP ZBook            | 1         | 1.96%   |
| HP EliteBook        | 1         | 1.96%   |
| HP 250              | 1         | 1.96%   |
| Gateway MP8708      | 1         | 1.96%   |
| Fujitsu LIFEBOOK    | 1         | 1.96%   |
| Eluktronics MAG-15u | 1         | 1.96%   |
| Dell Precision      | 1         | 1.96%   |
| ASUS X75VB          | 1         | 1.96%   |
| ASUS X450EA         | 1         | 1.96%   |
| ASUS VivoBook       | 1         | 1.96%   |
| ASUS G74Sx          | 1         | 1.96%   |
| Apple MacBookPro8   | 1         | 1.96%   |
| Apple MacBookPro11  | 1         | 1.96%   |
| Alienware m15       | 1         | 1.96%   |
| Acer TravelMate     | 1         | 1.96%   |
| Acer Swift          | 1         | 1.96%   |
| Acer Aspire         | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 17.65%  |
| 2019 | 7         | 13.73%  |
| 2018 | 6         | 11.76%  |
| 2021 | 5         | 9.8%    |
| 2013 | 5         | 9.8%    |
| 2016 | 3         | 5.88%   |
| 2015 | 3         | 5.88%   |
| 2012 | 3         | 5.88%   |
| 2010 | 3         | 5.88%   |
| 2017 | 2         | 3.92%   |
| 2011 | 2         | 3.92%   |
| 2008 | 2         | 3.92%   |
| 2006 | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 51        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 51        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 51        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 15        | 29.41%  |
| 8.01-16.0   | 12        | 23.53%  |
| 3.01-4.0    | 9         | 17.65%  |
| 16.01-24.0  | 8         | 15.69%  |
| 32.01-64.0  | 2         | 3.92%   |
| 64.01-256.0 | 2         | 3.92%   |
| 24.01-32.0  | 1         | 1.96%   |
| 2.01-3.0    | 1         | 1.96%   |
| 1.01-2.0    | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 20        | 37.74%  |
| 2.01-3.0 | 18        | 33.96%  |
| 3.01-4.0 | 9         | 16.98%  |
| 4.01-8.0 | 6         | 11.32%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 32        | 62.75%  |
| 2      | 16        | 31.37%  |
| 3      | 3         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 56.86%  |
| Yes       | 22        | 43.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 78.43%  |
| No        | 11        | 21.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 98.04%  |
| No        | 1         | 1.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 74.51%  |
| No        | 13        | 25.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 15        | 29.41%  |
| Spain        | 4         | 7.84%   |
| Germany      | 4         | 7.84%   |
| France       | 4         | 7.84%   |
| UK           | 3         | 5.88%   |
| Russia       | 2         | 3.92%   |
| Brazil       | 2         | 3.92%   |
| Sweden       | 1         | 1.96%   |
| South Africa | 1         | 1.96%   |
| Puerto Rico  | 1         | 1.96%   |
| Nigeria      | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Mexico       | 1         | 1.96%   |
| Kenya        | 1         | 1.96%   |
| Iraq         | 1         | 1.96%   |
| Indonesia    | 1         | 1.96%   |
| Hungary      | 1         | 1.96%   |
| Czechia      | 1         | 1.96%   |
| Colombia     | 1         | 1.96%   |
| Canada       | 1         | 1.96%   |
| Belgium      | 1         | 1.96%   |
| Bangladesh   | 1         | 1.96%   |
| Azerbaijan   | 1         | 1.96%   |
| Australia    | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Chicago                  | 2         | 3.85%   |
| Witbank                  | 1         | 1.92%   |
| Wichita                  | 1         | 1.92%   |
| West Jordan              | 1         | 1.92%   |
| Waveland                 | 1         | 1.92%   |
| Visalia                  | 1         | 1.92%   |
| Stockholm                | 1         | 1.92%   |
| Sinntal                  | 1         | 1.92%   |
| Sheffield                | 1         | 1.92%   |
| Secaucus                 | 1         | 1.92%   |
| Santo AndrÃ©             | 1         | 1.92%   |
| Sannois                  | 1         | 1.92%   |
| Regensburg               | 1         | 1.92%   |
| Reading                  | 1         | 1.92%   |
| Prague                   | 1         | 1.92%   |
| Ponce                    | 1         | 1.92%   |
| Paris                    | 1         | 1.92%   |
| Nairobi                  | 1         | 1.92%   |
| Mostoles                 | 1         | 1.92%   |
| Metairie                 | 1         | 1.92%   |
| Marietta                 | 1         | 1.92%   |
| Manchester               | 1         | 1.92%   |
| Majadahonda              | 1         | 1.92%   |
| Lyon                     | 1         | 1.92%   |
| Los Mochis               | 1         | 1.92%   |
| Long Beach               | 1         | 1.92%   |
| London                   | 1         | 1.92%   |
| Lagos                    | 1         | 1.92%   |
| Kobern-Gondorf           | 1         | 1.92%   |
| Kazan?ˆ™                 | 1         | 1.92%   |
| Jihlava                  | 1         | 1.92%   |
| Jaragua                  | 1         | 1.92%   |
| Houston                  | 1         | 1.92%   |
| Haarlem                  | 1         | 1.92%   |
| Fusagasuga               | 1         | 1.92%   |
| Frankfurt am Main        | 1         | 1.92%   |
| Fort Lauderdale          | 1         | 1.92%   |
| Erbil                    | 1         | 1.92%   |
| Edmonton                 | 1         | 1.92%   |
| East Malvern             | 1         | 1.92%   |
| Donostia / San Sebastian | 1         | 1.92%   |
| Dhaka                    | 1         | 1.92%   |
| Dallas                   | 1         | 1.92%   |
| Concord                  | 1         | 1.92%   |
| Budapest                 | 1         | 1.92%   |
| Blagoveshchensk          | 1         | 1.92%   |
| Barcelona                | 1         | 1.92%   |
| Banjarmasin              | 1         | 1.92%   |
| Baku                     | 1         | 1.92%   |
| Aix-les-Bains            | 1         | 1.92%   |
| Aalst                    | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 11.59%  |
| Samsung Electronics | 8         | 9      | 11.59%  |
| Crucial             | 7         | 10     | 10.14%  |
| Seagate             | 6         | 6      | 8.7%    |
| Unknown             | 5         | 5      | 7.25%   |
| Toshiba             | 5         | 6      | 7.25%   |
| Kingston            | 5         | 5      | 7.25%   |
| SK Hynix            | 3         | 3      | 4.35%   |
| SanDisk             | 3         | 3      | 4.35%   |
| Micron Technology   | 3         | 3      | 4.35%   |
| Hitachi             | 3         | 3      | 4.35%   |
| HGST                | 3         | 3      | 4.35%   |
| A-DATA Technology   | 3         | 3      | 4.35%   |
| KIOXIA              | 2         | 2      | 2.9%    |
| China               | 2         | 2      | 2.9%    |
| Patriot             | 1         | 1      | 1.45%   |
| Corsair             | 1         | 1      | 1.45%   |
| Apple               | 1         | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 2.78%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 2         | 2.78%   |
| SanDisk SSD PLUS 1000GB                  | 2         | 2.78%   |
| Samsung SSD 860 EVO 500GB                | 2         | 2.78%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 2.78%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2.78%   |
| Crucial CT1000MX500SSD1 1TB              | 2         | 2.78%   |
| WDC WDS100T2B0C-00PXH0 1TB               | 1         | 1.39%   |
| WDC WDBNCE2500PNC 250GB SSD              | 1         | 1.39%   |
| WDC WD800BEVS-22RST0 80GB                | 1         | 1.39%   |
| WDC WD3200LPVX-00V0TT0 320GB             | 1         | 1.39%   |
| WDC WD2500BPVT-00JJ5T0 250GB             | 1         | 1.39%   |
| WDC WD10SPZX-17Z10T1 1TB                 | 1         | 1.39%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB     | 1         | 1.39%   |
| Unknown Y016B  16GB                      | 1         | 1.39%   |
| Unknown xD/SD/M.S.                       | 1         | 1.39%   |
| Unknown SS16G  16GB                      | 1         | 1.39%   |
| Unknown SDU1  64GB                       | 1         | 1.39%   |
| Unknown MMC Card  128GB                  | 1         | 1.39%   |
| Toshiba THNSNF128GMCS 128GB SSD          | 1         | 1.39%   |
| Toshiba Q300. 480GB SSD                  | 1         | 1.39%   |
| Toshiba MQ01ABD100V -63 1TB              | 1         | 1.39%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1.39%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1.39%   |
| SK Hynix NVMe SSD Drive 512GB            | 1         | 1.39%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB        | 1         | 1.39%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB  | 1         | 1.39%   |
| Seagate ST9500420AS 500GB                | 1         | 1.39%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1.39%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.39%   |
| SanDisk Extreme SSD 1TB                  | 1         | 1.39%   |
| Samsung SSD 980 1TB                      | 1         | 1.39%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.39%   |
| Samsung MZVLW256HEHP-00000 256GB         | 1         | 1.39%   |
| Samsung MZVLQ256HAJD-00000 256GB         | 1         | 1.39%   |
| Samsung MZVLB512HBJQ-000L2 512GB         | 1         | 1.39%   |
| Samsung MZVLB1T0HALR 1TB SSD             | 1         | 1.39%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD     | 1         | 1.39%   |
| Patriot P210 256GB SSD                   | 1         | 1.39%   |
| Micron MTFDHBA256TDV-1AY1AABHA 256GB     | 1         | 1.39%   |
| Micron MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1.39%   |
| Micron 2200_MTFDHBA512TCK 512GB          | 1         | 1.39%   |
| KIOXIA KBG40ZNV256G 256GB                | 1         | 1.39%   |
| KIOXIA KBG40ZNS512G NVMe 512GB           | 1         | 1.39%   |
| Kingston SV300S37A240G 240GB SSD         | 1         | 1.39%   |
| Kingston SKC400S37512G 512GB SSD         | 1         | 1.39%   |
| Kingston SA2000M8500G 500GB              | 1         | 1.39%   |
| Hitachi HTS545025A7E380 250GB            | 1         | 1.39%   |
| Hitachi HTS542525K9SA00 250GB            | 1         | 1.39%   |
| Hitachi HTS542512K9SA00 120GB            | 1         | 1.39%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1.39%   |
| Crucial CT500MX500SSD1 500GB             | 1         | 1.39%   |
| Crucial CT480BX500SSD1 480GB             | 1         | 1.39%   |
| Crucial CT275MX300SSD1 275GB             | 1         | 1.39%   |
| Crucial CT250MX500SSD1 250GB             | 1         | 1.39%   |
| Crucial CT250MX200SSD1 250GB             | 1         | 1.39%   |
| Crucial CT1000P1SSD8 1TB                 | 1         | 1.39%   |
| Corsair Force 3 SSD 180GB                | 1         | 1.39%   |
| China SATA SSD 120GB                     | 1         | 1.39%   |

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
| Crucial             | 6         | 9      | 22.22%  |
| Samsung Electronics | 4         | 4      | 14.81%  |
| Kingston            | 4         | 4      | 14.81%  |
| SanDisk             | 3         | 3      | 11.11%  |
| Toshiba             | 2         | 3      | 7.41%   |
| China               | 2         | 2      | 7.41%   |
| WDC                 | 1         | 1      | 3.7%    |
| Patriot             | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Corsair             | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 23        | 31     | 35.94%  |
| HDD     | 20        | 22     | 31.25%  |
| NVMe    | 16        | 18     | 25%     |
| MMC     | 4         | 4      | 6.25%   |
| Unknown | 1         | 1      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 50     | 62.9%   |
| NVMe | 16        | 18     | 25.81%  |
| MMC  | 4         | 4      | 6.45%   |
| SAS  | 3         | 4      | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 34     | 61.36%  |
| 0.51-1.0   | 14        | 16     | 31.82%  |
| 1.01-2.0   | 3         | 3      | 6.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 12        | 23.53%  |
| 101-250        | 12        | 23.53%  |
| 501-1000       | 9         | 17.65%  |
| 1001-2000      | 6         | 11.76%  |
| Unknown        | 6         | 11.76%  |
| More than 3000 | 2         | 3.92%   |
| 51-100         | 2         | 3.92%   |
| 21-50          | 1         | 1.96%   |
| 2001-3000      | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 51-100    | 15        | 28.85%  |
| 21-50     | 13        | 25%     |
| 251-500   | 7         | 13.46%  |
| Unknown   | 6         | 11.54%  |
| 1-20      | 5         | 9.62%   |
| 101-250   | 4         | 7.69%   |
| 1001-2000 | 1         | 1.92%   |
| 501-1000  | 1         | 1.92%   |

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
| Works    | 28        | 36     | 50%     |
| Detected | 23        | 34     | 41.07%  |
| Malfunc  | 5         | 6      | 8.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 46        | 69.7%   |
| Samsung Electronics         | 5         | 7.58%   |
| SK Hynix                    | 3         | 4.55%   |
| Sandisk                     | 2         | 3.03%   |
| Micron Technology           | 2         | 3.03%   |
| KIOXIA                      | 2         | 3.03%   |
| AMD                         | 2         | 3.03%   |
| Realtek Semiconductor       | 1         | 1.52%   |
| Micron/Crucial Technology   | 1         | 1.52%   |
| Kingston Technology Company | 1         | 1.52%   |
| ADATA Technology            | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 6.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 6.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 5.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 4.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 4.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 4.17%   |
| SK Hynix BC511                                                                         | 2         | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.78%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 2.78%   |
| Micron Non-Volatile memory controller                                                  | 2         | 2.78%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 2.78%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 1.39%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 1         | 1.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.39%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.39%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 1.39%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 1.39%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.39%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.39%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.39%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.39%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 1.39%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 63.24%  |
| NVMe | 16        | 23.53%  |
| IDE  | 5         | 7.35%   |
| RAID | 4         | 5.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 48        | 94.12%  |
| AMD    | 3         | 5.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 3.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 3.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 3.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 3.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 3.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 3.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 3.92%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 3.92%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.96%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.96%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.96%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.96%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.96%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.96%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.96%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.96%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.96%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.96%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.96%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.96%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.96%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 1.96%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.96%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.96%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.96%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.96%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 1.96%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.96%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.96%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.96%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 1         | 1.96%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 1         | 1.96%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 1         | 1.96%   |
| AMD E1-2500 APU with Radeon HD Graphics     | 1         | 1.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 18        | 35.29%  |
| Intel Core i5           | 18        | 35.29%  |
| Intel Core i3           | 3         | 5.88%   |
| Other                   | 2         | 3.92%   |
| Intel Pentium Silver    | 2         | 3.92%   |
| Intel Core 2 Duo        | 2         | 3.92%   |
| Intel Pentium Dual-Core | 1         | 1.96%   |
| Intel Core 2 Quad       | 1         | 1.96%   |
| Intel Core 2            | 1         | 1.96%   |
| AMD Ryzen 7             | 1         | 1.96%   |
| AMD Ryzen 3             | 1         | 1.96%   |
| AMD E1                  | 1         | 1.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 27        | 52.94%  |
| 4      | 16        | 31.37%  |
| 8      | 4         | 7.84%   |
| 6      | 4         | 7.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 51        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 40        | 78.43%  |
| 1      | 11        | 21.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 42.31%  |
| 0x206a7    | 5         | 9.62%   |
| 0xa0652    | 3         | 5.77%   |
| 0x306c3    | 3         | 5.77%   |
| 0x706e5    | 2         | 3.85%   |
| 0x306d4    | 2         | 3.85%   |
| 0x1067a    | 2         | 3.85%   |
| 0x906e9    | 1         | 1.92%   |
| 0x806ec    | 1         | 1.92%   |
| 0x806d1    | 1         | 1.92%   |
| 0x806c1    | 1         | 1.92%   |
| 0x706a8    | 1         | 1.92%   |
| 0x706a1    | 1         | 1.92%   |
| 0x6fd      | 1         | 1.92%   |
| 0x6f6      | 1         | 1.92%   |
| 0x506e3    | 1         | 1.92%   |
| 0x306a9    | 1         | 1.92%   |
| 0x20655    | 1         | 1.92%   |
| 0x08600106 | 1         | 1.92%   |
| 0x08108109 | 1         | 1.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 7         | 13.73%  |
| KabyLake      | 6         | 11.76%  |
| Skylake       | 5         | 9.8%    |
| IvyBridge     | 5         | 9.8%    |
| Haswell       | 5         | 9.8%    |
| CometLake     | 4         | 7.84%   |
| Penryn        | 3         | 5.88%   |
| Icelake       | 3         | 5.88%   |
| Broadwell     | 3         | 5.88%   |
| Westmere      | 2         | 3.92%   |
| Goldmont plus | 2         | 3.92%   |
| Core          | 2         | 3.92%   |
| Zen+          | 1         | 1.96%   |
| Zen 2         | 1         | 1.96%   |
| TigerLake     | 1         | 1.96%   |
| Jaguar        | 1         | 1.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 63.77%  |
| Nvidia | 18        | 26.09%  |
| AMD    | 7         | 10.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 6.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 6.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 5.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 5.56%   |
| Intel HD Graphics 5500                                                        | 3         | 4.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 4.17%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 2.78%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 2.78%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.78%   |
| Nvidia TU117M                                                                 | 1         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.39%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 1.39%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.39%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.39%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.39%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.39%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.39%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.39%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.39%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.39%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.39%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.39%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.39%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                        | 1         | 1.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.39%   |
| Intel HD Graphics 630                                                         | 1         | 1.39%   |
| Intel HD Graphics 530                                                         | 1         | 1.39%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.39%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.39%   |
| AMD Renoir                                                                    | 1         | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.39%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 50.98%  |
| Intel + Nvidia | 15        | 29.41%  |
| 1 x AMD        | 4         | 7.84%   |
| 1 x Nvidia     | 3         | 5.88%   |
| Intel + AMD    | 3         | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 49        | 96.08%  |
| Proprietary | 2         | 3.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 78.43%  |
| 0.51-1.0   | 4         | 7.84%   |
| 3.01-4.0   | 2         | 3.92%   |
| 1.01-2.0   | 2         | 3.92%   |
| 7.01-8.0   | 1         | 1.96%   |
| 2.01-3.0   | 1         | 1.96%   |
| 0.01-0.5   | 1         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 21.82%  |
| LG Display              | 10        | 18.18%  |
| Samsung Electronics     | 8         | 14.55%  |
| Chimei Innolux          | 8         | 14.55%  |
| BOE                     | 8         | 14.55%  |
| Chi Mei Optoelectronics | 4         | 7.27%   |
| Dell                    | 2         | 3.64%   |
| Apple                   | 2         | 3.64%   |
| Ancor Communications    | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 3.64%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 340x190mm 15.3-inch      | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.82%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch               | 1         | 1.82%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.82%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch               | 1         | 1.82%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch              | 1         | 1.82%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.82%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 310x170mm 13.9-inch           | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.82%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE089B 1280x800 261x163mm 12.1-inch                      | 1         | 1.82%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE07B6 1920x1080 382x215mm 17.3-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.82%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO5544 1280x800 303x189mm 14.1-inch             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO328E 1920x1080 344x193mm 15.5-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch            | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch            | 1         | 1.82%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 1.82%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                     | 1         | 1.82%   |
| Ancor Communications VW225 ACI22A0 1680x1050 473x296mm 22.0-inch          | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 24        | 44.44%  |
| 1366x768 (WXGA)    | 18        | 33.33%  |
| 1280x800 (WXGA)    | 5         | 9.26%   |
| 1600x900 (HD+)     | 2         | 3.7%    |
| 2560x1600          | 1         | 1.85%   |
| 2560x1440 (QHD)    | 1         | 1.85%   |
| 1680x1050 (WSXGA+) | 1         | 1.85%   |
| 1440x900 (WXGA+)   | 1         | 1.85%   |
| 1280x1024 (SXGA)   | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 26        | 47.27%  |
| 14     | 10        | 18.18%  |
| 17     | 7         | 12.73%  |
| 13     | 4         | 7.27%   |
| 18     | 2         | 3.64%   |
| 12     | 2         | 3.64%   |
| 31     | 1         | 1.82%   |
| 27     | 1         | 1.82%   |
| 22     | 1         | 1.82%   |
| 19     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 70.37%  |
| 351-400     | 8         | 14.81%  |
| 201-300     | 4         | 7.41%   |
| 401-500     | 2         | 3.7%    |
| 601-700     | 1         | 1.85%   |
| 501-600     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 83.02%  |
| 16/10 | 8         | 15.09%  |
| 6/5   | 1         | 1.89%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 26        | 47.27%  |
| 81-90          | 13        | 23.64%  |
| 121-130        | 6         | 10.91%  |
| 61-70          | 2         | 3.64%   |
| 141-150        | 2         | 3.64%   |
| 71-80          | 1         | 1.82%   |
| 351-500        | 1         | 1.82%   |
| 301-350        | 1         | 1.82%   |
| 201-250        | 1         | 1.82%   |
| 151-200        | 1         | 1.82%   |
| 131-140        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 24        | 44.44%  |
| 101-120 | 21        | 38.89%  |
| 51-100  | 6         | 11.11%  |
| 161-240 | 2         | 3.7%    |
| 1-50    | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 92.16%  |
| 2     | 3         | 5.88%   |
| 3     | 1         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 29        | 34.12%  |
| Realtek Semiconductor             | 24        | 28.24%  |
| Qualcomm Atheros                  | 15        | 17.65%  |
| Broadcom                          | 7         | 8.24%   |
| TP-Link                           | 2         | 2.35%   |
| Xiaomi                            | 1         | 1.18%   |
| Samsung Electronics               | 1         | 1.18%   |
| Ralink Technology                 | 1         | 1.18%   |
| Qualcomm Atheros Communications   | 1         | 1.18%   |
| NetGear                           | 1         | 1.18%   |
| Huawei Technologies               | 1         | 1.18%   |
| Ericsson Business Mobile Networks | 1         | 1.18%   |
| Broadcom Limited                  | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 13        | 12.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 5         | 4.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 4.9%    |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 3.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 2.94%   |
| Intel Wireless 7265                                                       | 3         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 2         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 1.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.96%   |
| Intel Wireless 8260                                                       | 2         | 1.96%   |
| Intel Wireless 3160                                                       | 2         | 1.96%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 2         | 1.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.98%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 0.98%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 1         | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.98%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.98%   |
| Intel Wireless 3165                                                       | 1         | 0.98%   |
| Intel Wi-Fi 6 AX201                                                       | 1         | 0.98%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.98%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.98%   |
| Intel Ethernet controller                                                 | 1         | 0.98%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.98%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 0.98%   |
| Intel Centrino Wireless-N 105                                             | 1         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 0.98%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 0.98%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 0.98%   |
| Intel 82577LM Gigabit Network Connection                                  | 1         | 0.98%   |
| Huawei DRA-L01                                                            | 1         | 0.98%   |
| Ericsson Business Mobile Networks N5321 gw                                | 1         | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                         | 1         | 0.98%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                    | 1         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                           | 1         | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 0.98%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 47.37%  |
| Qualcomm Atheros                | 12        | 21.05%  |
| Realtek Semiconductor           | 7         | 12.28%  |
| Broadcom                        | 5         | 8.77%   |
| TP-Link                         | 2         | 3.51%   |
| Ralink Technology               | 1         | 1.75%   |
| Qualcomm Atheros Communications | 1         | 1.75%   |
| NetGear                         | 1         | 1.75%   |
| Broadcom Limited                | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 8.77%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 7.02%   |
| Intel Wireless 7265                                                       | 3         | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 5.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 2         | 3.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 2         | 3.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 3.51%   |
| Intel Wireless 8260                                                       | 2         | 3.51%   |
| Intel Wireless 3160                                                       | 2         | 3.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 3.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 3.51%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 1         | 1.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 1         | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.75%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.75%   |
| Intel Wireless 3165                                                       | 1         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                       | 1         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.75%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.75%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.75%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 1.75%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 20        | 46.51%  |
| Intel                 | 11        | 25.58%  |
| Qualcomm Atheros      | 6         | 13.95%  |
| Broadcom              | 3         | 6.98%   |
| Xiaomi                | 1         | 2.33%   |
| Samsung Electronics   | 1         | 2.33%   |
| Huawei Technologies   | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 29.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.36%  |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 6.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 4.55%   |
| Intel Ethernet Connection I217-V                                  | 2         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 2.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.27%   |
| Intel PRO/100 VE Network Connection                               | 1         | 2.27%   |
| Intel Ethernet controller                                         | 1         | 2.27%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.27%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.27%   |
| Huawei DRA-L01                                                    | 1         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 50        | 54.95%  |
| Ethernet | 40        | 43.96%  |
| Modem    | 1         | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 69.84%  |
| Ethernet | 19        | 30.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 38        | 74.51%  |
| 1     | 13        | 25.49%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 73.08%  |
| Yes  | 14        | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 52.63%  |
| Qualcomm Atheros Communications | 8         | 21.05%  |
| Broadcom                        | 3         | 7.89%   |
| Realtek Semiconductor           | 2         | 5.26%   |
| Lite-On Technology              | 1         | 2.63%   |
| Foxconn / Hon Hai               | 1         | 2.63%   |
| Dell                            | 1         | 2.63%   |
| Cambridge Silicon Radio         | 1         | 2.63%   |
| Apple                           | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 18.42%  |
| Intel Bluetooth Device                              | 6         | 15.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 15.79%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 7.89%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.63%   |
| Realtek Bluetooth Radio                             | 1         | 2.63%   |
| Qualcomm Atheros Bluetooth                          | 1         | 2.63%   |
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

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 48        | 73.85%  |
| Nvidia    | 12        | 18.46%  |
| AMD       | 4         | 6.15%   |
| GN Netcom | 1         | 1.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.49%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 5.19%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 5.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 3.9%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 2.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 2.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 2.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.6%    |
| Intel 8 Series HD Audio Controller                                         | 2         | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.6%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2         | 2.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.3%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.3%    |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.3%    |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.3%    |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.3%    |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.3%    |
| Nvidia Audio device                                                        | 1         | 1.3%    |
| Intel USB PnP Sound Device                                                 | 1         | 1.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.3%    |
| Intel CM238 HD Audio Controller                                            | 1         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.3%    |
| GN Netcom Jabra Evolve 65                                                  | 1         | 1.3%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.3%    |
| AMD FCH Azalia Controller                                                  | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 37.5%   |
| SK Hynix            | 6         | 15%     |
| Unknown             | 3         | 7.5%    |
| Elpida              | 3         | 7.5%    |
| Ramaxel Technology  | 2         | 5%      |
| Micron Technology   | 2         | 5%      |
| Kingston            | 2         | 5%      |
| Crucial             | 2         | 5%      |
| A-DATA Technology   | 2         | 5%      |
| Team                | 1         | 2.5%    |
| G.Skill             | 1         | 2.5%    |
| Corsair             | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 4.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 4.65%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 2.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 2.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 2.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 2.33%   |
| Team RAM TEAMGROUP-SD4-2666 16384MB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 2.33%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| SK Hynix RAM H9HCNNNBKMALHR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 2.33%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                    | 1         | 2.33%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.33%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 2.33%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 2.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 2.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 1         | 2.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.33%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 2.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.33%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 2.33%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 2.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s          | 1         | 2.33%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s             | 1         | 2.33%   |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s       | 1         | 2.33%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s       | 1         | 2.33%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 2.33%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s         | 1         | 2.33%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s         | 1         | 2.33%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s           | 1         | 2.33%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s                | 1         | 2.33%   |
| Corsair RAM CMSO8GX3M1A1600C11 8192MB SODIMM DDR3 1600MT/s       | 1         | 2.33%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                      | 1         | 2.33%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 44.12%  |
| DDR3   | 15        | 44.12%  |
| LPDDR4 | 2         | 5.88%   |
| DDR2   | 2         | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 97.06%  |
| Row Of Chips | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 15        | 37.5%   |
| 8192  | 12        | 30%     |
| 16384 | 5         | 12.5%   |
| 2048  | 4         | 10%     |
| 32768 | 2         | 5%      |
| 1024  | 2         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 10        | 27.78%  |
| 1600  | 10        | 27.78%  |
| 3200  | 4         | 11.11%  |
| 1334  | 4         | 11.11%  |
| 3266  | 2         | 5.56%   |
| 4267  | 1         | 2.78%   |
| 2400  | 1         | 2.78%   |
| 1333  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |
| 667   | 1         | 2.78%   |
| 533   | 1         | 2.78%   |

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
| Chicony Electronics                    | 13        | 30.23%  |
| Acer                                   | 7         | 16.28%  |
| Microdia                               | 5         | 11.63%  |
| IMC Networks                           | 3         | 6.98%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.98%   |
| Sunplus Innovation Technology          | 2         | 4.65%   |
| Ricoh                                  | 2         | 4.65%   |
| Realtek Semiconductor                  | 2         | 4.65%   |
| Suyin                                  | 1         | 2.33%   |
| Silicon Motion                         | 1         | 2.33%   |
| Samsung Electronics                    | 1         | 2.33%   |
| Luxvisions Innotech Limited            | 1         | 2.33%   |
| DLEQNA14PF8SVW                         | 1         | 2.33%   |
| Apple                                  | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 6.98%   |
| Acer HD Webcam                                                             | 3         | 6.98%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.65%   |
| Chicony HD Webcam                                                          | 2         | 4.65%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 2.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.33%   |
| Sunplus HD WebCam                                                          | 1         | 2.33%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 2.33%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 2.33%   |
| Ricoh Pavilion Webcam                                                      | 1         | 2.33%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 2.33%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 2.33%   |
| Microdia PC Microscope camera                                              | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 2.33%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.33%   |
| Microdia Integrated Webcam HD                                              | 1         | 2.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.33%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.33%   |
| IMC Networks Integrated Camera                                             | 1         | 2.33%   |
| DLEQNA14PF8SVW HP TrueVision HD Camera                                     | 1         | 2.33%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 2.33%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.33%   |
| Chicony Integrated Camera                                                  | 1         | 2.33%   |
| Chicony HP Webcam                                                          | 1         | 2.33%   |
| Chicony HP TrueVision HD                                                   | 1         | 2.33%   |
| Chicony HP HD Camera                                                       | 1         | 2.33%   |
| Chicony HD User Facing                                                     | 1         | 2.33%   |
| Chicony CNF8248                                                            | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.33%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.33%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.33%   |
| Acer Integrated Camera                                                     | 1         | 2.33%   |
| Acer HD Camera                                                             | 1         | 2.33%   |
| Acer EasyCamera                                                            | 1         | 2.33%   |

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
| 0     | 29        | 55.77%  |
| 1     | 15        | 28.85%  |
| 2     | 7         | 13.46%  |
| 3     | 1         | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 31.03%  |
| Chipcard              | 5         | 17.24%  |
| Graphics card         | 4         | 13.79%  |
| Storage               | 3         | 10.34%  |
| Net/wireless          | 3         | 10.34%  |
| Multimedia controller | 2         | 6.9%    |
| Modem                 | 1         | 3.45%   |
| Camera                | 1         | 3.45%   |
| Bluetooth             | 1         | 3.45%   |

