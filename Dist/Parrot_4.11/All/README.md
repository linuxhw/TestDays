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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-6parrot1-amd64    | 20        | 41.67%  |
| 5.10.0-8parrot1-amd64    | 13        | 27.08%  |
| 5.10.0-3parrot1-amd64    | 5         | 10.42%  |
| 5.7.0-2parrot2-amd64     | 4         | 8.33%   |
| 5.10.0-5parrot1-amd64    | 4         | 8.33%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 2.08%   |
| Unknown                  | 1         | 2.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 43        | 89.58%  |
| 5.7.0   | 4         | 8.33%   |
| Unknown | 1         | 2.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 43        | 89.58%  |
| 5.7     | 4         | 8.33%   |
| Unknown | 1         | 2.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 48        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 24        | 48.98%  |
| KDE5    | 13        | 26.53%  |
| KDE     | 6         | 12.24%  |
| Unknown | 3         | 6.12%   |
| XFCE    | 2         | 4.08%   |
| LXDE    | 1         | 2.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 48        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 23        | 46.94%  |
| Unknown | 23        | 46.94%  |
| LightDM | 2         | 4.08%   |
| SDDM    | 1         | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 21        | 43.75%  |
| ru_RU   | 4         | 8.33%   |
| fr_FR   | 4         | 8.33%   |
| en_AU   | 4         | 8.33%   |
| pt_BR   | 3         | 6.25%   |
| Unknown | 3         | 6.25%   |
| en_GB   | 2         | 4.17%   |
| ru_UA   | 1         | 2.08%   |
| nl_BE   | 1         | 2.08%   |
| id_ID   | 1         | 2.08%   |
| es_ES   | 1         | 2.08%   |
| es_CO   | 1         | 2.08%   |
| de_DE   | 1         | 2.08%   |
| cs_CZ   | 1         | 2.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 35        | 71.43%  |
| EFI  | 14        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 40        | 83.33%  |
| Xfs   | 4         | 8.33%   |
| Ext4  | 4         | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 42.86%  |
| GPT     | 15        | 30.61%  |
| MBR     | 13        | 26.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 83.67%  |
| Yes       | 8         | 16.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 34        | 70.83%  |
| Yes       | 14        | 29.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 25%     |
| ASUSTek Computer    | 8         | 16.67%  |
| Dell                | 7         | 14.58%  |
| MSI                 | 4         | 8.33%   |
| Lenovo              | 3         | 6.25%   |
| Samsung Electronics | 2         | 4.17%   |
| Apple               | 2         | 4.17%   |
| Acer                | 2         | 4.17%   |
| ZOTAC               | 1         | 2.08%   |
| Wortmann AG         | 1         | 2.08%   |
| Quanta              | 1         | 2.08%   |
| Microsoft           | 1         | 2.08%   |
| Intel               | 1         | 2.08%   |
| Gigabyte Technology | 1         | 2.08%   |
| Gateway             | 1         | 2.08%   |
| Fujitsu             | 1         | 2.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 4.17%   |
| ASUS Q524UQ                             | 2         | 4.17%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 2.08%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 2.08%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 2.08%   |
| Quanta HDX PREMIUM SERIES               | 1         | 2.08%   |
| MSI GT60 2OC/2OD                        | 1         | 2.08%   |
| MSI GE75 Raider 10SF                    | 1         | 2.08%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 2.08%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 2.08%   |
| Microsoft Surface Pro 3                 | 1         | 2.08%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 2.08%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 2.08%   |
| Lenovo B50-80 80EW                      | 1         | 2.08%   |
| Intel NUC8i7HVK                         | 1         | 2.08%   |
| HP ZBook 15 G5                          | 1         | 2.08%   |
| HP Pavilion Notebook                    | 1         | 2.08%   |
| HP Pavilion dv7                         | 1         | 2.08%   |
| HP Pavilion dv6700                      | 1         | 2.08%   |
| HP Pavilion dv6                         | 1         | 2.08%   |
| HP Pavilion dv4                         | 1         | 2.08%   |
| HP Laptop 15s-eq1xxx                    | 1         | 2.08%   |
| HP Laptop 15-dw0xxx                     | 1         | 2.08%   |
| HP Compaq Pro 6305 MT                   | 1         | 2.08%   |
| HP All-in-One 24-f0xx                   | 1         | 2.08%   |
| Gigabyte A320M-S2H                      | 1         | 2.08%   |
| Gateway MP8708                          | 1         | 2.08%   |
| Fujitsu LIFEBOOK T731                   | 1         | 2.08%   |
| Dell OptiPlex 7070                      | 1         | 2.08%   |
| Dell OptiPlex 3010                      | 1         | 2.08%   |
| Dell Latitude E7440                     | 1         | 2.08%   |
| Dell Latitude E6420                     | 1         | 2.08%   |
| Dell Inspiron 5593                      | 1         | 2.08%   |
| Dell Inspiron 5558                      | 1         | 2.08%   |
| Dell Inspiron 5420                      | 1         | 2.08%   |
| ASUS X75VB                              | 1         | 2.08%   |
| ASUS X450EA                             | 1         | 2.08%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 2.08%   |
| ASUS PRIME X399-A                       | 1         | 2.08%   |
| ASUS M5A78L-M/USB3                      | 1         | 2.08%   |
| ASUS G74Sx                              | 1         | 2.08%   |
| Apple MacBookPro8,1                     | 1         | 2.08%   |
| Apple MacBookPro11,1                    | 1         | 2.08%   |
| Acer Predator PO3-600                   | 1         | 2.08%   |
| Acer Aspire E1-571G                     | 1         | 2.08%   |
| Unknown                                 | 1         | 2.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 5         | 10.42%  |
| Dell Inspiron      | 3         | 6.25%   |
| Lenovo ThinkPad    | 2         | 4.17%   |
| HP ProBook         | 2         | 4.17%   |
| HP Laptop          | 2         | 4.17%   |
| Dell OptiPlex      | 2         | 4.17%   |
| Dell Latitude      | 2         | 4.17%   |
| ASUS Q524UQ        | 2         | 4.17%   |
| Wortmann AG TERRA  | 1         | 2.08%   |
| Samsung 350V5C     | 1         | 2.08%   |
| Samsung 300E4C     | 1         | 2.08%   |
| Quanta HDX         | 1         | 2.08%   |
| MSI GT60           | 1         | 2.08%   |
| MSI GE75           | 1         | 2.08%   |
| MSI GE73           | 1         | 2.08%   |
| MSI GE63           | 1         | 2.08%   |
| Microsoft Surface  | 1         | 2.08%   |
| Lenovo B50-80      | 1         | 2.08%   |
| Intel NUC8i7HVK    | 1         | 2.08%   |
| HP ZBook           | 1         | 2.08%   |
| HP Compaq          | 1         | 2.08%   |
| HP All-in-One      | 1         | 2.08%   |
| Gigabyte A320M-S2H | 1         | 2.08%   |
| Gateway MP8708     | 1         | 2.08%   |
| Fujitsu LIFEBOOK   | 1         | 2.08%   |
| ASUS X75VB         | 1         | 2.08%   |
| ASUS X450EA        | 1         | 2.08%   |
| ASUS VivoBook      | 1         | 2.08%   |
| ASUS PRIME         | 1         | 2.08%   |
| ASUS M5A78L-M      | 1         | 2.08%   |
| ASUS G74Sx         | 1         | 2.08%   |
| Apple MacBookPro8  | 1         | 2.08%   |
| Apple MacBookPro11 | 1         | 2.08%   |
| Acer Predator      | 1         | 2.08%   |
| Acer Aspire        | 1         | 2.08%   |
| Unknown            | 1         | 2.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 8         | 16.67%  |
| 2019 | 8         | 16.67%  |
| 2018 | 7         | 14.58%  |
| 2013 | 6         | 12.5%   |
| 2016 | 4         | 8.33%   |
| 2015 | 3         | 6.25%   |
| 2012 | 3         | 6.25%   |
| 2021 | 2         | 4.17%   |
| 2011 | 2         | 4.17%   |
| 2010 | 2         | 4.17%   |
| 2014 | 1         | 2.08%   |
| 2008 | 1         | 2.08%   |
| 2006 | 1         | 2.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 37        | 77.08%  |
| Desktop    | 8         | 16.67%  |
| Tablet     | 1         | 2.08%   |
| Mini pc    | 1         | 2.08%   |
| All in one | 1         | 2.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 48        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 48        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 14        | 29.17%  |
| 8.01-16.0   | 14        | 29.17%  |
| 3.01-4.0    | 8         | 16.67%  |
| 16.01-24.0  | 5         | 10.42%  |
| 32.01-64.0  | 2         | 4.17%   |
| 64.01-256.0 | 2         | 4.17%   |
| 24.01-32.0  | 1         | 2.08%   |
| 2.01-3.0    | 1         | 2.08%   |
| 1.01-2.0    | 1         | 2.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 19        | 38.78%  |
| 1.01-2.0  | 18        | 36.73%  |
| 4.01-8.0  | 6         | 12.24%  |
| 3.01-4.0  | 5         | 10.2%   |
| 8.01-16.0 | 1         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 52.08%  |
| 2      | 14        | 29.17%  |
| 3      | 8         | 16.67%  |
| 4      | 1         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 57.14%  |
| Yes       | 21        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 40        | 83.33%  |
| No        | 8         | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 91.84%  |
| No        | 4         | 8.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 70.83%  |
| No        | 14        | 29.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 16        | 33.33%  |
| Germany      | 4         | 8.33%   |
| Russia       | 3         | 6.25%   |
| France       | 3         | 6.25%   |
| Australia    | 3         | 6.25%   |
| Spain        | 2         | 4.17%   |
| Brazil       | 2         | 4.17%   |
| Ukraine      | 1         | 2.08%   |
| UK           | 1         | 2.08%   |
| South Africa | 1         | 2.08%   |
| Puerto Rico  | 1         | 2.08%   |
| Netherlands  | 1         | 2.08%   |
| Mexico       | 1         | 2.08%   |
| Iraq         | 1         | 2.08%   |
| Indonesia    | 1         | 2.08%   |
| Hungary      | 1         | 2.08%   |
| Czechia      | 1         | 2.08%   |
| Colombia     | 1         | 2.08%   |
| Belgium      | 1         | 2.08%   |
| Bangladesh   | 1         | 2.08%   |
| Azerbaijan   | 1         | 2.08%   |
| Algeria      | 1         | 2.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Chicago           | 2         | 4.08%   |
| Witbank           | 1         | 2.04%   |
| West Jordan       | 1         | 2.04%   |
| Visalia           | 1         | 2.04%   |
| Ternopil          | 1         | 2.04%   |
| Sinntal           | 1         | 2.04%   |
| Secaucus          | 1         | 2.04%   |
| S??o Paulo        | 1         | 2.04%   |
| Santo André      | 1         | 2.04%   |
| Sannois           | 1         | 2.04%   |
| Regensburg        | 1         | 2.04%   |
| Prague            | 1         | 2.04%   |
| Portsmouth        | 1         | 2.04%   |
| Ponce             | 1         | 2.04%   |
| Oklahoma City     | 1         | 2.04%   |
| Offenbach         | 1         | 2.04%   |
| Marietta          | 1         | 2.04%   |
| Majadahonda       | 1         | 2.04%   |
| Lyon              | 1         | 2.04%   |
| Los Mochis        | 1         | 2.04%   |
| Los Angeles       | 1         | 2.04%   |
| Long Beach        | 1         | 2.04%   |
| London            | 1         | 2.04%   |
| Khabarovsk        | 1         | 2.04%   |
| Kazan?��          | 1         | 2.04%   |
| Jakarta           | 1         | 2.04%   |
| Houston           | 1         | 2.04%   |
| Frankfurt am Main | 1         | 2.04%   |
| Fort Lauderdale   | 1         | 2.04%   |
| Eugene            | 1         | 2.04%   |
| Erbil             | 1         | 2.04%   |
| East Malvern      | 1         | 2.04%   |
| Dudenhofen        | 1         | 2.04%   |
| Dhaka             | 1         | 2.04%   |
| Denham Springs    | 1         | 2.04%   |
| Concord           | 1         | 2.04%   |
| Budapest          | 1         | 2.04%   |
| Brunswick         | 1         | 2.04%   |
| Bogotá           | 1         | 2.04%   |
| Blagoveshchensk   | 1         | 2.04%   |
| Bay Saint Louis   | 1         | 2.04%   |
| Barcelona         | 1         | 2.04%   |
| Baku              | 1         | 2.04%   |
| Amsterdam         | 1         | 2.04%   |
| Akbou             | 1         | 2.04%   |
| Aix-les-Bains     | 1         | 2.04%   |
| Adelaide          | 1         | 2.04%   |
| Aalst             | 1         | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 13.16%  |
| Seagate             | 10        | 14     | 13.16%  |
| Samsung Electronics | 8         | 9      | 10.53%  |
| Unknown             | 7         | 7      | 9.21%   |
| Crucial             | 7         | 8      | 9.21%   |
| Toshiba             | 6         | 6      | 7.89%   |
| Kingston            | 4         | 4      | 5.26%   |
| Hitachi             | 4         | 5      | 5.26%   |
| China               | 3         | 3      | 3.95%   |
| A-DATA Technology   | 3         | 3      | 3.95%   |
| HGST                | 2         | 2      | 2.63%   |
| SPCC                | 1         | 1      | 1.32%   |
| SK Hynix            | 1         | 1      | 1.32%   |
| SanDisk             | 1         | 1      | 1.32%   |
| ROG                 | 1         | 1      | 1.32%   |
| Phison              | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| KIOXIA              | 1         | 1      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| FORESEE             | 1         | 1      | 1.32%   |
| Corsair             | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 2.44%   |
| Unknown SD/MMC/MS PRO 64GB               | 2         | 2.44%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 2         | 2.44%   |
| Kingston SA400S37240G 240GB SSD          | 2         | 2.44%   |
| Crucial CT1000MX500SSD1 1TB              | 2         | 2.44%   |
| WDC WDS100T2B0B-00YS70 1TB SSD           | 1         | 1.22%   |
| WDC WDBNCE0010PNC 1TB SSD                | 1         | 1.22%   |
| WDC WD800BEVS-22RST0 80GB                | 1         | 1.22%   |
| WDC WD3200LPVX-60V0TT0 320GB             | 1         | 1.22%   |
| WDC WD3200LPVX-00V0TT0 320GB             | 1         | 1.22%   |
| WDC WD2500BPVT-00JJ5T0 250GB             | 1         | 1.22%   |
| WDC WD10SPZX-17Z10T1 1TB                 | 1         | 1.22%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1         | 1.22%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB     | 1         | 1.22%   |
| Unknown Y016B  16GB                      | 1         | 1.22%   |
| Unknown xD/SD/M.S.                       | 1         | 1.22%   |
| Unknown SS16G  16GB                      | 1         | 1.22%   |
| Unknown SDU1  64GB                       | 1         | 1.22%   |
| Unknown MMC Card  128GB                  | 1         | 1.22%   |
| Toshiba THNSNF128GMCS 128GB SSD          | 1         | 1.22%   |
| Toshiba Q300. 480GB SSD                  | 1         | 1.22%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1.22%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1.22%   |
| Toshiba MK2552GSX 250GB                  | 1         | 1.22%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1.22%   |
| SPCC Solid State Disk 120GB              | 1         | 1.22%   |
| SK Hynix NVMe SSD Drive 256GB            | 1         | 1.22%   |
| Seagate ST9500420AS 500GB                | 1         | 1.22%   |
| Seagate ST9250410AS 250GB                | 1         | 1.22%   |
| Seagate ST500NM0011 500GB                | 1         | 1.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1         | 1.22%   |
| Seagate ST500DM002-1SB10A 500GB          | 1         | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1.22%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1.22%   |
| Seagate ST250DM000-1BD141 250GB          | 1         | 1.22%   |
| Seagate ST2000LM007-1R8174 2TB           | 1         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1.22%   |
| SanDisk Extreme SSD 500GB                | 1         | 1.22%   |
| Samsung SSD 980 1TB                      | 1         | 1.22%   |
| Samsung SSD 860 EVO M.2 2TB              | 1         | 1.22%   |
| Samsung SSD 860 EVO 500GB                | 1         | 1.22%   |
| Samsung NVMe SSD Drive 512GB             | 1         | 1.22%   |
| Samsung NVMe SSD Drive 1TB               | 1         | 1.22%   |
| Samsung MZVLW256HEHP-00000 256GB         | 1         | 1.22%   |
| Samsung MZVLQ256HAJD-00000 256GB         | 1         | 1.22%   |
| Samsung MZNLH128HBHQ-000H1 128GB SSD     | 1         | 1.22%   |
| Samsung MZMTE512HMHP-000MV 512GB SSD     | 1         | 1.22%   |
| ROG ESD-S1C 256GB                        | 1         | 1.22%   |
| Phison NVMe SSD Drive 1TB                | 1         | 1.22%   |
| Patriot P210 256GB SSD                   | 1         | 1.22%   |
| Micron MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1.22%   |
| KIOXIA KBG40ZNV256G 256GB                | 1         | 1.22%   |
| Kingston SV300S37A240G 240GB SSD         | 1         | 1.22%   |
| Kingston SKC400S37512G 512GB SSD         | 1         | 1.22%   |
| Intenso SSD SATAIII 960GB                | 1         | 1.22%   |
| Hitachi HTS547564A9E384 640GB            | 1         | 1.22%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1.22%   |
| Hitachi HTS545025A7E380 250GB            | 1         | 1.22%   |
| Hitachi HTS542512K9SA00 120GB            | 1         | 1.22%   |
| Hitachi HDT721010SLA360 1TB              | 1         | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 14     | 35.71%  |
| WDC     | 8         | 9      | 28.57%  |
| Toshiba | 4         | 4      | 14.29%  |
| Hitachi | 4         | 5      | 14.29%  |
| HGST    | 2         | 2      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 7         | 8      | 22.58%  |
| Samsung Electronics | 4         | 4      | 12.9%   |
| Kingston            | 4         | 4      | 12.9%   |
| China               | 3         | 3      | 9.68%   |
| WDC                 | 2         | 2      | 6.45%   |
| Toshiba             | 2         | 2      | 6.45%   |
| SPCC                | 1         | 1      | 3.23%   |
| SanDisk             | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| Intenso             | 1         | 1      | 3.23%   |
| FORESEE             | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 26        | 32     | 37.14%  |
| HDD     | 26        | 34     | 37.14%  |
| NVMe    | 10        | 11     | 14.29%  |
| MMC     | 4         | 4      | 5.71%   |
| Unknown | 4         | 4      | 5.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 44        | 65     | 69.84%  |
| NVMe | 10        | 11     | 15.87%  |
| SAS  | 5         | 5      | 7.94%   |
| MMC  | 4         | 4      | 6.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 43     | 58.49%  |
| 0.51-1.0   | 17        | 18     | 32.08%  |
| 1.01-2.0   | 4         | 4      | 7.55%   |
| 3.01-4.0   | 1         | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 11        | 22.45%  |
| 101-250        | 11        | 22.45%  |
| 501-1000       | 9         | 18.37%  |
| 1001-2000      | 5         | 10.2%   |
| Unknown        | 5         | 10.2%   |
| 2001-3000      | 3         | 6.12%   |
| 51-100         | 3         | 6.12%   |
| More than 3000 | 2         | 4.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 14        | 28.57%  |
| 51-100    | 10        | 20.41%  |
| 251-500   | 6         | 12.24%  |
| 1-20      | 6         | 12.24%  |
| 101-250   | 5         | 10.2%   |
| Unknown   | 5         | 10.2%   |
| 501-1000  | 2         | 4.08%   |
| 1001-2000 | 1         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 2         | 2      | 25%     |
| NVMe | 1         | 1      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intenso SSD SATAIII 960GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intenso | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 27        | 41     | 45%     |
| Works    | 25        | 35     | 41.67%  |
| Malfunc  | 7         | 8      | 11.67%  |
| Failed   | 1         | 1      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 68.42%  |
| AMD                   | 7         | 12.28%  |
| Samsung Electronics   | 5         | 8.77%   |
| SK Hynix              | 1         | 1.75%   |
| Sandisk               | 1         | 1.75%   |
| Realtek Semiconductor | 1         | 1.75%   |
| Phison Electronics    | 1         | 1.75%   |
| KIOXIA                | 1         | 1.75%   |
| ADATA Technology      | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 7.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 5         | 7.81%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 5         | 7.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 4         | 6.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 4.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 4.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 3.13%   |
| Samsung NVMe Controller                                                                | 2         | 3.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 3.13%   |
| SK Hynix BC511                                                                         | 1         | 1.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 1.56%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 1.56%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 1.56%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 1         | 1.56%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 1.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 1.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.56%   |
| AMD X399 Series Chipset SATA Controller                                                | 1         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 1         | 1.56%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 1.56%   |
| AMD FCH SATA Controller D                                                              | 1         | 1.56%   |
| ADATA Non-Volatile memory controller                                                   | 1         | 1.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 46        | 76.67%  |
| NVMe | 10        | 16.67%  |
| IDE  | 4         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 40        | 83.33%  |
| AMD    | 8         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz              | 2         | 4.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 2         | 4.17%   |
| Intel Core i7-2670QM CPU @ 2.20GHz             | 2         | 4.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 2         | 4.17%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 4.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 2         | 4.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 2         | 4.17%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 2         | 4.17%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 1         | 2.08%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 1         | 2.08%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1         | 2.08%   |
| Intel Core i7-8850H CPU @ 2.60GHz              | 1         | 2.08%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 2.08%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1         | 2.08%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 2.08%   |
| Intel Core i7-4650U CPU @ 1.70GHz              | 1         | 2.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1         | 2.08%   |
| Intel Core i7-4558U CPU @ 2.80GHz              | 1         | 2.08%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 2.08%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 2.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 2.08%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1         | 2.08%   |
| Intel Core i5-6400T CPU @ 2.20GHz              | 1         | 2.08%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 2.08%   |
| Intel Core i5-4210M CPU @ 2.60GHz              | 1         | 2.08%   |
| Intel Core i5-4200M CPU @ 2.50GHz              | 1         | 2.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 2.08%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 2.08%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 2.08%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz          | 1         | 2.08%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 2.08%   |
| Intel Core 2 CPU T7200 @ 2.00GHz               | 1         | 2.08%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 2.08%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 2.08%   |
| AMD Ryzen 3 3250U with Radeon Graphics         | 1         | 2.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1         | 2.08%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 2.08%   |
| AMD E1-2500 APU with Radeon HD Graphics        | 1         | 2.08%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 2.08%   |
| AMD A4-5300B APU with Radeon HD Graphics       | 1         | 2.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 16        | 33.33%  |
| Intel Core i5           | 16        | 33.33%  |
| Intel Core i3           | 2         | 4.17%   |
| AMD Ryzen 3             | 2         | 4.17%   |
| Intel Pentium Silver    | 1         | 2.08%   |
| Intel Pentium Dual-Core | 1         | 2.08%   |
| Intel Core M            | 1         | 2.08%   |
| Intel Core 2 Quad       | 1         | 2.08%   |
| Intel Core 2 Duo        | 1         | 2.08%   |
| Intel Core 2            | 1         | 2.08%   |
| AMD Ryzen Threadripper  | 1         | 2.08%   |
| AMD Ryzen 7             | 1         | 2.08%   |
| AMD FX                  | 1         | 2.08%   |
| AMD E1                  | 1         | 2.08%   |
| AMD A6                  | 1         | 2.08%   |
| AMD A4                  | 1         | 2.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 27        | 56.25%  |
| 4      | 11        | 22.92%  |
| 6      | 6         | 12.5%   |
| 12     | 1         | 2.08%   |
| 8      | 1         | 2.08%   |
| 3      | 1         | 2.08%   |
| 1      | 1         | 2.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 48        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 35        | 72.92%  |
| 1      | 13        | 27.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 48        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 51.02%  |
| 0x206a7    | 4         | 8.16%   |
| 0x306d4    | 2         | 4.08%   |
| 0x306c3    | 2         | 4.08%   |
| 0x306a9    | 2         | 4.08%   |
| 0x1067a    | 2         | 4.08%   |
| 0x906e9    | 1         | 2.04%   |
| 0x706e5    | 1         | 2.04%   |
| 0x706a1    | 1         | 2.04%   |
| 0x6fd      | 1         | 2.04%   |
| 0x6f6      | 1         | 2.04%   |
| 0x506e3    | 1         | 2.04%   |
| 0x40651    | 1         | 2.04%   |
| 0x08600106 | 1         | 2.04%   |
| 0x08108109 | 1         | 2.04%   |
| 0x06006705 | 1         | 2.04%   |
| 0x0600111f | 1         | 2.04%   |
| 0x06000852 | 1         | 2.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 6         | 12.5%   |
| KabyLake      | 6         | 12.5%   |
| IvyBridge     | 6         | 12.5%   |
| Haswell       | 6         | 12.5%   |
| Skylake       | 5         | 10.42%  |
| Broadwell     | 4         | 8.33%   |
| Zen           | 2         | 4.17%   |
| Piledriver    | 2         | 4.17%   |
| Penryn        | 2         | 4.17%   |
| Core          | 2         | 4.17%   |
| Zen+          | 1         | 2.08%   |
| Zen 2         | 1         | 2.08%   |
| Jaguar        | 1         | 2.08%   |
| IceLake       | 1         | 2.08%   |
| Goldmont plus | 1         | 2.08%   |
| Excavator     | 1         | 2.08%   |
| CometLake     | 1         | 2.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 36        | 59.02%  |
| Nvidia | 15        | 24.59%  |
| AMD    | 10        | 16.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 7.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 7.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 6.35%   |
| Intel HD Graphics 5500                                                        | 3         | 4.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 4.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 4.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 3.17%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 3.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 3.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 3.17%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.59%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 1.59%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.59%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.59%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1         | 1.59%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.59%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.59%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 1.59%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.59%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.59%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.59%   |
| Intel HD Graphics 630                                                         | 1         | 1.59%   |
| Intel HD Graphics 5300                                                        | 1         | 1.59%   |
| Intel HD Graphics 530                                                         | 1         | 1.59%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.59%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1         | 1.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 1.59%   |
| AMD Trinity 2 [Radeon HD 7480D]                                               | 1         | 1.59%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.59%   |
| AMD RS780L [Radeon 3000]                                                      | 1         | 1.59%   |
| AMD Renoir                                                                    | 1         | 1.59%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                                       | 1         | 1.59%   |
| AMD Picasso                                                                   | 1         | 1.59%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 47.92%  |
| Intel + Nvidia | 9         | 18.75%  |
| 1 x AMD        | 7         | 14.58%  |
| 1 x Nvidia     | 6         | 12.5%   |
| Intel + AMD    | 3         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 89.58%  |
| Proprietary | 5         | 10.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 73.47%  |
| 1.01-2.0   | 4         | 8.16%   |
| 0.51-1.0   | 4         | 8.16%   |
| 0.01-0.5   | 2         | 4.08%   |
| 7.01-8.0   | 1         | 2.04%   |
| 3.01-4.0   | 1         | 2.04%   |
| 2.01-3.0   | 1         | 2.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 9         | 18%     |
| LG Display              | 7         | 14%     |
| Chimei Innolux          | 7         | 14%     |
| AU Optronics            | 6         | 12%     |
| BOE                     | 5         | 10%     |
| Chi Mei Optoelectronics | 4         | 8%      |
| Hewlett-Packard         | 2         | 4%      |
| Apple                   | 2         | 4%      |
| Vizio                   | 1         | 2%      |
| Sony                    | 1         | 2%      |
| Sceptre                 | 1         | 2%      |
| Philips                 | 1         | 2%      |
| Goldstar                | 1         | 2%      |
| Dell                    | 1         | 2%      |
| AUS                     | 1         | 2%      |
| AOC                     | 1         | 2%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 3.92%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                        | 1         | 1.96%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                       | 1         | 1.96%   |
| Sceptre LCD Monitor P30 2560x1080                                         | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 250x170mm 11.9-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 340x190mm 15.3-inch      | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.96%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch        | 1         | 1.96%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch        | 1         | 1.96%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                   | 1         | 1.96%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch               | 1         | 1.96%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch              | 1         | 1.96%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch                | 1         | 1.96%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch          | 1         | 1.96%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                    | 1         | 1.96%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 310x170mm 13.9-inch           | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.96%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.96%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.96%   |
| AUS LCD Monitor VG259 1920x1080                                           | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch            | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 1         | 1.96%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch            | 1         | 1.96%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 1         | 1.96%   |
| Apple Color LCD APPA018 2560x1600 286x179mm 13.3-inch                     | 1         | 1.96%   |
| AOC LCD Monitor 2217 1680x1050                                            | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 40%     |
| 1366x768 (WXGA)    | 16        | 32%     |
| 1280x800 (WXGA)    | 3         | 6%      |
| 1600x900 (HD+)     | 2         | 4%      |
| 1280x1024 (SXGA)   | 2         | 4%      |
| 3840x1080          | 1         | 2%      |
| 2560x1600          | 1         | 2%      |
| 2560x1440 (QHD)    | 1         | 2%      |
| 2560x1080          | 1         | 2%      |
| 2160x1440          | 1         | 2%      |
| 1680x1050 (WSXGA+) | 1         | 2%      |
| 1440x900 (WXGA+)   | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 19        | 37.25%  |
| 17      | 7         | 13.73%  |
| 14      | 6         | 11.76%  |
| 13      | 4         | 7.84%   |
| Unknown | 3         | 5.88%   |
| 31      | 2         | 3.92%   |
| 23      | 2         | 3.92%   |
| 12      | 2         | 3.92%   |
| 48      | 1         | 1.96%   |
| 42      | 1         | 1.96%   |
| 27      | 1         | 1.96%   |
| 24      | 1         | 1.96%   |
| 19      | 1         | 1.96%   |
| 18      | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 56%     |
| 351-400     | 7         | 14%     |
| 201-300     | 4         | 8%      |
| 501-600     | 3         | 6%      |
| Unknown     | 3         | 6%      |
| 601-700     | 2         | 4%      |
| 401-500     | 1         | 2%      |
| 1001-1500   | 1         | 2%      |
| 901-1000    | 1         | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 38        | 77.55%  |
| 16/10   | 5         | 10.2%   |
| Unknown | 3         | 6.12%   |
| 6/5     | 1         | 2.04%   |
| 5/4     | 1         | 2.04%   |
| 32/9    | 1         | 2.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 19        | 37.25%  |
| 81-90          | 9         | 17.65%  |
| 121-130        | 5         | 9.8%    |
| 201-250        | 3         | 5.88%   |
| Unknown        | 3         | 5.88%   |
| 61-70          | 2         | 3.92%   |
| 351-500        | 2         | 3.92%   |
| 141-150        | 2         | 3.92%   |
| 501-1000       | 2         | 3.92%   |
| 71-80          | 1         | 1.96%   |
| 301-350        | 1         | 1.96%   |
| 151-200        | 1         | 1.96%   |
| 131-140        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 18        | 36.73%  |
| 121-160 | 16        | 32.65%  |
| 51-100  | 10        | 20.41%  |
| Unknown | 3         | 6.12%   |
| 1-50    | 1         | 2.04%   |
| 161-240 | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 44        | 91.67%  |
| 2     | 4         | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 26        | 32.91%  |
| Intel                             | 23        | 29.11%  |
| Qualcomm Atheros                  | 12        | 15.19%  |
| Broadcom                          | 6         | 7.59%   |
| TP-Link                           | 3         | 3.8%    |
| Ralink Technology                 | 2         | 2.53%   |
| Qualcomm Atheros Communications   | 2         | 2.53%   |
| Broadcom Limited                  | 2         | 2.53%   |
| Marvell Technology Group          | 1         | 1.27%   |
| Ericsson Business Mobile Networks | 1         | 1.27%   |
| D-Link System                     | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 15        | 15.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 5         | 5.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 4.17%   |
| Intel Wireless 7265                                                  | 4         | 4.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 3         | 3.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 3         | 3.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 3         | 3.13%   |
| Intel Wireless 3160                                                  | 3         | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.08%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 2.08%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2         | 2.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 2.08%   |
| Intel Wireless 8260                                                  | 2         | 2.08%   |
| Intel Ethernet Connection I217-V                                     | 2         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 2.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 2         | 2.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 1         | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 1.04%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 1         | 1.04%   |
| Intel Wireless 8265 / 8275                                           | 1         | 1.04%   |
| Intel Wireless 3165                                                  | 1         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.04%   |
| Intel PRO/100 VE Network Connection                                  | 1         | 1.04%   |
| Intel I211 Gigabit Network Connection                                | 1         | 1.04%   |
| Intel I210 Gigabit Network Connection                                | 1         | 1.04%   |
| Intel Ethernet Connection I219-V                                     | 1         | 1.04%   |
| Intel Ethernet Connection I218-LM                                    | 1         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                | 1         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                 | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.04%   |
| Intel Centrino Wireless-N 105                                        | 1         | 1.04%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 1         | 1.04%   |
| Ericsson Business Mobile Networks N5321 gw                           | 1         | 1.04%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1         | 1.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 1         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1         | 1.04%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 1         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.04%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 38.46%  |
| Qualcomm Atheros                | 9         | 17.31%  |
| Realtek Semiconductor           | 8         | 15.38%  |
| Broadcom                        | 5         | 9.62%   |
| TP-Link                         | 3         | 5.77%   |
| Ralink Technology               | 2         | 3.85%   |
| Qualcomm Atheros Communications | 2         | 3.85%   |
| Marvell Technology Group        | 1         | 1.92%   |
| D-Link System                   | 1         | 1.92%   |
| Broadcom Limited                | 1         | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 7.69%   |
| Intel Wireless 7265                                                  | 4         | 7.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 3         | 5.77%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 3         | 5.77%   |
| Intel Wireless 3160                                                  | 3         | 5.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 5.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 3.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2         | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 3.85%   |
| Intel Wireless 8260                                                  | 2         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 3.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 2         | 3.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 1         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 1.92%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 1         | 1.92%   |
| Intel Wireless 8265 / 8275                                           | 1         | 1.92%   |
| Intel Wireless 3165                                                  | 1         | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.92%   |
| Intel Centrino Wireless-N 105                                        | 1         | 1.92%   |
| Intel Centrino Advanced-N 6235                                       | 1         | 1.92%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1         | 1.92%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter           | 1         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 1         | 1.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 1         | 1.92%   |
| Broadcom BCM43142 802.11b/g/n                                        | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 21        | 51.22%  |
| Intel                 | 11        | 26.83%  |
| Qualcomm Atheros      | 6         | 14.63%  |
| Broadcom              | 2         | 4.88%   |
| Broadcom Limited      | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 34.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 11.63%  |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 6.98%   |
| Intel Ethernet Connection I217-V                                  | 2         | 4.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.33%   |
| Intel PRO/100 VE Network Connection                               | 1         | 2.33%   |
| Intel I211 Gigabit Network Connection                             | 1         | 2.33%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.33%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.33%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 2.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 45        | 52.33%  |
| Ethernet | 40        | 46.51%  |
| Modem    | 1         | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 68.33%  |
| Ethernet | 19        | 31.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 66.67%  |
| 1     | 14        | 29.17%  |
| 3     | 2         | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 36        | 75%     |
| Yes  | 12        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 44.12%  |
| Qualcomm Atheros Communications | 6         | 17.65%  |
| Realtek Semiconductor           | 4         | 11.76%  |
| Broadcom                        | 3         | 8.82%   |
| Marvell Semiconductor           | 1         | 2.94%   |
| Lite-On Technology              | 1         | 2.94%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| Dell                            | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |
| Apple                           | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 8         | 23.53%  |
| Intel Bluetooth wireless interface                  | 3         | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 8.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 5.88%   |
| Realtek Bluetooth Radio                             | 2         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 5.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 5.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 2.94%   |
| Qualcomm Atheros Bluetooth                          | 1         | 2.94%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.94%   |
| Lite-On Bluetooth Radio                             | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.94%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.94%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.94%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.94%   |
| Apple Bluetooth Host Controller                     | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 40        | 65.57%  |
| Nvidia              | 11        | 18.03%  |
| AMD                 | 9         | 14.75%  |
| C-Media Electronics | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 8.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 6.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 6.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 5.13%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 5.13%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 5.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.85%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.85%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 3.85%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 3         | 3.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.56%   |
| AMD FCH Azalia Controller                                                  | 2         | 2.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 1.28%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 1.28%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 1.28%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 1.28%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.28%   |
| Intel USB PnP Sound Device                                                 | 1         | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 1.28%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.28%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 1.28%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1         | 1.28%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.28%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                     | 1         | 1.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 1.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 1.28%   |
| AMD Polaris 22 HDMI Audio                                                  | 1         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.28%   |
| AMD High Definition Audio Controller                                       | 1         | 1.28%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 1.28%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 32.35%  |
| Unknown             | 4         | 11.76%  |
| SK Hynix            | 4         | 11.76%  |
| Kingston            | 3         | 8.82%   |
| Elpida              | 3         | 8.82%   |
| Crucial             | 2         | 5.88%   |
| S                   | 1         | 2.94%   |
| Ramaxel Technology  | 1         | 2.94%   |
| Nanya Technology    | 1         | 2.94%   |
| Micron Technology   | 1         | 2.94%   |
| G.Skill             | 1         | 2.94%   |
| Corsair             | 1         | 2.94%   |
| A-DATA Technology   | 1         | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 5.71%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s   | 2         | 5.71%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 2.86%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s              | 1         | 2.86%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                 | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s              | 1         | 2.86%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 2.86%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s  | 1         | 2.86%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 1         | 2.86%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s   | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s   | 1         | 2.86%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s   | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                        | 1         | 2.86%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s  | 1         | 2.86%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| Kingston RAM HP26D4S9S8MH-8 8GB SODIMM DDR4 2400MT/s       | 1         | 2.86%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s | 1         | 2.86%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s     | 1         | 2.86%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 2.86%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s   | 1         | 2.86%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s   | 1         | 2.86%   |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s  | 1         | 2.86%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s          | 1         | 2.86%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 55.17%  |
| DDR4    | 10        | 34.48%  |
| DDR2    | 2         | 6.9%    |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 26        | 89.66%  |
| DIMM   | 3         | 10.34%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 16        | 48.48%  |
| 8192  | 8         | 24.24%  |
| 16384 | 3         | 9.09%   |
| 2048  | 3         | 9.09%   |
| 1024  | 2         | 6.06%   |
| 32768 | 1         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 12        | 41.38%  |
| 2667  | 7         | 24.14%  |
| 1334  | 3         | 10.34%  |
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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 28.13%  |
| Acer                                   | 5         | 15.63%  |
| Microdia                               | 3         | 9.38%   |
| Sunplus Innovation Technology          | 2         | 6.25%   |
| Luxvisions Innotech Limited            | 2         | 6.25%   |
| IMC Networks                           | 2         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.25%   |
| Silicon Motion                         | 1         | 3.13%   |
| Samsung Electronics                    | 1         | 3.13%   |
| Ricoh                                  | 1         | 3.13%   |
| Realtek Semiconductor                  | 1         | 3.13%   |
| Quanta                                 | 1         | 3.13%   |
| Microsoft                              | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                             | 3         | 9.09%   |
| Acer HD Webcam                                           | 3         | 9.09%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera      | 2         | 6.06%   |
| Sunplus Laptop_Integrated_Webcam_FHD                     | 1         | 3.03%   |
| Sunplus HD WebCam                                        | 1         | 3.03%   |
| Silicon Motion WebCam SC-03FFL11939N                     | 1         | 3.03%   |
| Samsung Galaxy A5 (MTP)                                  | 1         | 3.03%   |
| Ricoh Pavilion Webcam                                    | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD                             | 1         | 3.03%   |
| Quanta HP High Definition 1MP Webcam                     | 1         | 3.03%   |
| Microsoft LifeCam Rear                                   | 1         | 3.03%   |
| Microsoft LifeCam Front                                  | 1         | 3.03%   |
| Microdia WebCam SC-13HDL12639P                           | 1         | 3.03%   |
| Microdia Laptop_Integrated_Webcam_E4HD                   | 1         | 3.03%   |
| Microdia Integrated Webcam HD                            | 1         | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam                        | 1         | 3.03%   |
| IMC Networks Integrated Webcam                           | 1         | 3.03%   |
| Chicony UVC 1.00 device HD UVC WebCam                    | 1         | 3.03%   |
| Chicony USB2.0 Camera                                    | 1         | 3.03%   |
| Chicony Integrated Camera                                | 1         | 3.03%   |
| Chicony HP Webcam                                        | 1         | 3.03%   |
| Chicony HP TrueVision HD                                 | 1         | 3.03%   |
| Chicony CNF8248                                          | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam            | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD | 1         | 3.03%   |
| Apple FaceTime HD Camera                                 | 1         | 3.03%   |
| Acer Lenovo EasyCamera                                   | 1         | 3.03%   |
| Acer Integrated Camera                                   | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 66.67%  |
| LighTuning Technology | 1         | 11.11%  |
| Elan Microelectronics | 1         | 11.11%  |
| AuthenTec             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Broadcom    | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 66.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 32        | 66.67%  |
| 1     | 9         | 18.75%  |
| 2     | 6         | 12.5%   |
| 3     | 1         | 2.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 9         | 39.13%  |
| Net/wireless          | 3         | 13.04%  |
| Chipcard              | 3         | 13.04%  |
| Storage               | 2         | 8.7%    |
| Multimedia controller | 2         | 8.7%    |
| Modem                 | 1         | 4.35%   |
| Graphics card         | 1         | 4.35%   |
| Camera                | 1         | 4.35%   |
| Bluetooth             | 1         | 4.35%   |

