Parrot 4.11 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_4.11/Desktop/README.md) and [notebooks](/Dist/Parrot_4.11/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5347580c37](https://linux-hardware.org/?probe=5347580c37) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-6parrot1-amd64    | 27        | 38.57%  |
| 5.10.0-8parrot1-amd64    | 17        | 24.29%  |
| 5.14.0-9parrot1-amd64    | 7         | 10%     |
| 5.10.0-3parrot1-amd64    | 5         | 7.14%   |
| 5.7.0-2parrot2-amd64     | 4         | 5.71%   |
| 5.10.0-5parrot1-amd64    | 4         | 5.71%   |
| 5.14.0-2parrot1-amd64    | 3         | 4.29%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.43%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.43%   |
| Unknown                  | 1         | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 54        | 77.14%  |
| 5.14.0  | 10        | 14.29%  |
| 5.7.0   | 4         | 5.71%   |
| 5.6.0   | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 54        | 77.14%  |
| 5.14    | 10        | 14.29%  |
| 5.7     | 4         | 5.71%   |
| 5.6     | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 39        | 55.71%  |
| KDE5    | 16        | 22.86%  |
| KDE     | 7         | 10%     |
| Unknown | 4         | 5.71%   |
| XFCE    | 3         | 4.29%   |
| LXDE    | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 69        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 25        | 35.21%  |
| TDM     | 23        | 32.39%  |
| LightDM | 22        | 30.99%  |
| SDDM    | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 32        | 46.38%  |
| fr_FR   | 6         | 8.7%    |
| en_GB   | 5         | 7.25%   |
| ru_RU   | 4         | 5.8%    |
| pt_BR   | 4         | 5.8%    |
| en_AU   | 4         | 5.8%    |
| Unknown | 3         | 4.35%   |
| es_ES   | 2         | 2.9%    |
| de_DE   | 2         | 2.9%    |
| ru_UA   | 1         | 1.45%   |
| pl_PL   | 1         | 1.45%   |
| nl_BE   | 1         | 1.45%   |
| id_ID   | 1         | 1.45%   |
| es_CO   | 1         | 1.45%   |
| en_NG   | 1         | 1.45%   |
| cs_CZ   | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 45        | 63.38%  |
| EFI  | 26        | 36.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 55        | 79.71%  |
| Ext4  | 10        | 14.49%  |
| Xfs   | 4         | 5.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 28        | 40%     |
| Unknown | 26        | 37.14%  |
| MBR     | 16        | 22.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 82.86%  |
| Yes       | 12        | 17.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 63.77%  |
| Yes       | 25        | 36.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 21.74%  |
| Dell                | 11        | 15.94%  |
| ASUSTek Computer    | 10        | 14.49%  |
| MSI                 | 5         | 7.25%   |
| Lenovo              | 5         | 7.25%   |
| Acer                | 5         | 7.25%   |
| Samsung Electronics | 2         | 2.9%    |
| Apple               | 2         | 2.9%    |
| Alienware           | 2         | 2.9%    |
| ZOTAC               | 1         | 1.45%   |
| Wortmann AG         | 1         | 1.45%   |
| Toxic               | 1         | 1.45%   |
| Toshiba             | 1         | 1.45%   |
| Quanta              | 1         | 1.45%   |
| Microsoft           | 1         | 1.45%   |
| Intel               | 1         | 1.45%   |
| Gigabyte Technology | 1         | 1.45%   |
| Gateway             | 1         | 1.45%   |
| Fujitsu             | 1         | 1.45%   |
| Eluktronics         | 1         | 1.45%   |
| ASRock              | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 2.9%    |
| ASUS Q524UQ                             | 2         | 2.9%    |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 1.45%   |
| Toxic GM7MQ8P                           | 1         | 1.45%   |
| Toshiba Satellite L655                  | 1         | 1.45%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.45%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 1.45%   |
| Quanta HDX PREMIUM SERIES               | 1         | 1.45%   |
| MSI GT60 2OC/2OD                        | 1         | 1.45%   |
| MSI GS66 Stealth 10UG                   | 1         | 1.45%   |
| MSI GE75 Raider 10SF                    | 1         | 1.45%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 1.45%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 1.45%   |
| Microsoft Surface Pro 3                 | 1         | 1.45%   |
| Lenovo Yoga S740-14IIL 81RS             | 1         | 1.45%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 1.45%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 1.45%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 1.45%   |
| Lenovo B50-80 80EW                      | 1         | 1.45%   |
| Intel NUC8i7HVK                         | 1         | 1.45%   |
| HP ZBook 15 G5                          | 1         | 1.45%   |
| HP Pavilion Notebook                    | 1         | 1.45%   |
| HP Pavilion dv7                         | 1         | 1.45%   |
| HP Pavilion dv6700                      | 1         | 1.45%   |
| HP Pavilion dv6                         | 1         | 1.45%   |
| HP Pavilion dv4                         | 1         | 1.45%   |
| HP Laptop 15s-eq1xxx                    | 1         | 1.45%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.45%   |
| HP EliteBook 8470p                      | 1         | 1.45%   |
| HP EliteBook 840 G8 Notebook PC         | 1         | 1.45%   |
| HP Compaq Pro 6305 MT                   | 1         | 1.45%   |
| HP All-in-One 24-f0xx                   | 1         | 1.45%   |
| HP 250 G7 Notebook PC                   | 1         | 1.45%   |
| Gigabyte A320M-S2H                      | 1         | 1.45%   |
| Gateway MP8708                          | 1         | 1.45%   |
| Fujitsu LIFEBOOK T731                   | 1         | 1.45%   |
| Eluktronics MAG-15u                     | 1         | 1.45%   |
| Dell XPS 8930                           | 1         | 1.45%   |
| Dell Precision M4600                    | 1         | 1.45%   |
| Dell OptiPlex 7070                      | 1         | 1.45%   |
| Dell OptiPlex 3010                      | 1         | 1.45%   |
| Dell Latitude E7440                     | 1         | 1.45%   |
| Dell Latitude E6420                     | 1         | 1.45%   |
| Dell Latitude E6410                     | 1         | 1.45%   |
| Dell Inspiron 7501                      | 1         | 1.45%   |
| Dell Inspiron 5593                      | 1         | 1.45%   |
| Dell Inspiron 5558                      | 1         | 1.45%   |
| Dell Inspiron 5420                      | 1         | 1.45%   |
| ASUS X75VB                              | 1         | 1.45%   |
| ASUS X450EA                             | 1         | 1.45%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 1.45%   |
| ASUS PRIME X399-A                       | 1         | 1.45%   |
| ASUS P8H67-M PRO                        | 1         | 1.45%   |
| ASUS M5A99X EVO                         | 1         | 1.45%   |
| ASUS M5A78L-M/USB3                      | 1         | 1.45%   |
| ASUS G74Sx                              | 1         | 1.45%   |
| ASRock Z87 Killer                       | 1         | 1.45%   |
| Apple MacBookPro8,1                     | 1         | 1.45%   |
| Apple MacBookPro11,1                    | 1         | 1.45%   |
| Alienware X51 R2                        | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| HP Pavilion         | 5         | 7.25%   |
| Dell Inspiron       | 4         | 5.8%    |
| Dell Latitude       | 3         | 4.35%   |
| Lenovo ThinkPad     | 2         | 2.9%    |
| HP ProBook          | 2         | 2.9%    |
| HP Laptop           | 2         | 2.9%    |
| HP EliteBook        | 2         | 2.9%    |
| Dell OptiPlex       | 2         | 2.9%    |
| ASUS Q524UQ         | 2         | 2.9%    |
| Acer Aspire         | 2         | 2.9%    |
| Wortmann AG TERRA   | 1         | 1.45%   |
| Toxic GM7MQ8P       | 1         | 1.45%   |
| Toshiba Satellite   | 1         | 1.45%   |
| Samsung 350V5C      | 1         | 1.45%   |
| Samsung 300E4C      | 1         | 1.45%   |
| Quanta HDX          | 1         | 1.45%   |
| MSI GT60            | 1         | 1.45%   |
| MSI GS66            | 1         | 1.45%   |
| MSI GE75            | 1         | 1.45%   |
| MSI GE73            | 1         | 1.45%   |
| MSI GE63            | 1         | 1.45%   |
| Microsoft Surface   | 1         | 1.45%   |
| Lenovo Yoga         | 1         | 1.45%   |
| Lenovo Y520-15IKBN  | 1         | 1.45%   |
| Lenovo B50-80       | 1         | 1.45%   |
| Intel NUC8i7HVK     | 1         | 1.45%   |
| HP ZBook            | 1         | 1.45%   |
| HP Compaq           | 1         | 1.45%   |
| HP All-in-One       | 1         | 1.45%   |
| HP 250              | 1         | 1.45%   |
| Gigabyte A320M-S2H  | 1         | 1.45%   |
| Gateway MP8708      | 1         | 1.45%   |
| Fujitsu LIFEBOOK    | 1         | 1.45%   |
| Eluktronics MAG-15u | 1         | 1.45%   |
| Dell XPS            | 1         | 1.45%   |
| Dell Precision      | 1         | 1.45%   |
| ASUS X75VB          | 1         | 1.45%   |
| ASUS X450EA         | 1         | 1.45%   |
| ASUS VivoBook       | 1         | 1.45%   |
| ASUS PRIME          | 1         | 1.45%   |
| ASUS P8H67-M        | 1         | 1.45%   |
| ASUS M5A99X         | 1         | 1.45%   |
| ASUS M5A78L-M       | 1         | 1.45%   |
| ASUS G74Sx          | 1         | 1.45%   |
| ASRock Z87          | 1         | 1.45%   |
| Apple MacBookPro8   | 1         | 1.45%   |
| Apple MacBookPro11  | 1         | 1.45%   |
| Alienware X51       | 1         | 1.45%   |
| Alienware m15       | 1         | 1.45%   |
| Acer TravelMate     | 1         | 1.45%   |
| Acer Swift          | 1         | 1.45%   |
| Acer Predator       | 1         | 1.45%   |
| Unknown             | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 11        | 15.94%  |
| 2019 | 11        | 15.94%  |
| 2013 | 9         | 13.04%  |
| 2018 | 8         | 11.59%  |
| 2021 | 6         | 8.7%    |
| 2017 | 4         | 5.8%    |
| 2016 | 4         | 5.8%    |
| 2015 | 4         | 5.8%    |
| 2012 | 3         | 4.35%   |
| 2010 | 3         | 4.35%   |
| 2011 | 2         | 2.9%    |
| 2008 | 2         | 2.9%    |
| 2014 | 1         | 1.45%   |
| 2006 | 1         | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 52        | 75.36%  |
| Desktop    | 14        | 20.29%  |
| Tablet     | 1         | 1.45%   |
| Mini pc    | 1         | 1.45%   |
| All in one | 1         | 1.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 69        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 28.99%  |
| 8.01-16.0   | 17        | 24.64%  |
| 16.01-24.0  | 12        | 17.39%  |
| 3.01-4.0    | 10        | 14.49%  |
| 32.01-64.0  | 3         | 4.35%   |
| 64.01-256.0 | 3         | 4.35%   |
| 24.01-32.0  | 2         | 2.9%    |
| 2.01-3.0    | 1         | 1.45%   |
| 1.01-2.0    | 1         | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 27        | 38.03%  |
| 2.01-3.0  | 23        | 32.39%  |
| 4.01-8.0  | 10        | 14.08%  |
| 3.01-4.0  | 9         | 12.68%  |
| 8.01-16.0 | 1         | 1.41%   |
| 0.51-1.0  | 1         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 35        | 50.72%  |
| 2      | 23        | 33.33%  |
| 3      | 8         | 11.59%  |
| 4      | 2         | 2.9%    |
| 5      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 61.43%  |
| Yes       | 27        | 38.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 82.61%  |
| No        | 12        | 17.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 92.86%  |
| No        | 5         | 7.14%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 71.01%  |
| No        | 20        | 28.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 23        | 33.33%  |
| Germany      | 5         | 7.25%   |
| France       | 5         | 7.25%   |
| Spain        | 4         | 5.8%    |
| UK           | 3         | 4.35%   |
| Russia       | 3         | 4.35%   |
| Brazil       | 3         | 4.35%   |
| Australia    | 3         | 4.35%   |
| Netherlands  | 2         | 2.9%    |
| Ukraine      | 1         | 1.45%   |
| Sweden       | 1         | 1.45%   |
| South Africa | 1         | 1.45%   |
| Puerto Rico  | 1         | 1.45%   |
| Poland       | 1         | 1.45%   |
| Nigeria      | 1         | 1.45%   |
| Mexico       | 1         | 1.45%   |
| Kenya        | 1         | 1.45%   |
| Iraq         | 1         | 1.45%   |
| Indonesia    | 1         | 1.45%   |
| Hungary      | 1         | 1.45%   |
| Czechia      | 1         | 1.45%   |
| Colombia     | 1         | 1.45%   |
| Canada       | 1         | 1.45%   |
| Belgium      | 1         | 1.45%   |
| Bangladesh   | 1         | 1.45%   |
| Azerbaijan   | 1         | 1.45%   |
| Algeria      | 1         | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lyon                     | 2         | 2.82%   |
| Eugene                   | 2         | 2.82%   |
| Chicago                  | 2         | 2.82%   |
| Witbank                  | 1         | 1.41%   |
| Wichita                  | 1         | 1.41%   |
| West Jordan              | 1         | 1.41%   |
| Waveland                 | 1         | 1.41%   |
| Warsaw                   | 1         | 1.41%   |
| Visalia                  | 1         | 1.41%   |
| Ternopil                 | 1         | 1.41%   |
| Stockholm                | 1         | 1.41%   |
| Sinntal                  | 1         | 1.41%   |
| Sheffield                | 1         | 1.41%   |
| Secaucus                 | 1         | 1.41%   |
| S??o Paulo               | 1         | 1.41%   |
| Santo AndrÃ©             | 1         | 1.41%   |
| Sannois                  | 1         | 1.41%   |
| Saint Paul               | 1         | 1.41%   |
| Regensburg               | 1         | 1.41%   |
| Reading                  | 1         | 1.41%   |
| Prague                   | 1         | 1.41%   |
| Portsmouth               | 1         | 1.41%   |
| Ponce                    | 1         | 1.41%   |
| Paris                    | 1         | 1.41%   |
| Offenbach                | 1         | 1.41%   |
| Nairobi                  | 1         | 1.41%   |
| Mostoles                 | 1         | 1.41%   |
| Metairie                 | 1         | 1.41%   |
| Melbourne                | 1         | 1.41%   |
| Marietta                 | 1         | 1.41%   |
| Manchester               | 1         | 1.41%   |
| Majadahonda              | 1         | 1.41%   |
| Los Mochis               | 1         | 1.41%   |
| Los Angeles              | 1         | 1.41%   |
| Long Beach               | 1         | 1.41%   |
| London                   | 1         | 1.41%   |
| Lagos                    | 1         | 1.41%   |
| Lafayette                | 1         | 1.41%   |
| Kobern-Gondorf           | 1         | 1.41%   |
| Khabarovsk               | 1         | 1.41%   |
| Kazan?ˆ™                 | 1         | 1.41%   |
| Jihlava                  | 1         | 1.41%   |
| Jaragua                  | 1         | 1.41%   |
| Houston                  | 1         | 1.41%   |
| Haarlem                  | 1         | 1.41%   |
| Fusagasuga               | 1         | 1.41%   |
| Frankfurt am Main        | 1         | 1.41%   |
| Fort Lauderdale          | 1         | 1.41%   |
| Fallbrook                | 1         | 1.41%   |
| Erbil                    | 1         | 1.41%   |
| Edmonton                 | 1         | 1.41%   |
| East Malvern             | 1         | 1.41%   |
| Dudenhofen               | 1         | 1.41%   |
| Donostia / San Sebastian | 1         | 1.41%   |
| Dhaka                    | 1         | 1.41%   |
| Dallas                   | 1         | 1.41%   |
| Concord                  | 1         | 1.41%   |
| Budapest                 | 1         | 1.41%   |
| Brunswick                | 1         | 1.41%   |
| Blagoveshchensk          | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 20     | 12.84%  |
| Samsung Electronics | 13        | 15     | 11.93%  |
| WDC                 | 12        | 15     | 11.01%  |
| Crucial             | 10        | 13     | 9.17%   |
| Unknown             | 8         | 8      | 7.34%   |
| Toshiba             | 8         | 9      | 7.34%   |
| SK Hynix            | 5         | 5      | 4.59%   |
| SanDisk             | 5         | 5      | 4.59%   |
| Kingston            | 5         | 5      | 4.59%   |
| Hitachi             | 5         | 6      | 4.59%   |
| Micron Technology   | 3         | 3      | 2.75%   |
| HGST                | 3         | 3      | 2.75%   |
| China               | 3         | 4      | 2.75%   |
| A-DATA Technology   | 3         | 3      | 2.75%   |
| KIOXIA              | 2         | 2      | 1.83%   |
| SPCC                | 1         | 1      | 0.92%   |
| ROG                 | 1         | 1      | 0.92%   |
| Phison              | 1         | 1      | 0.92%   |
| Patriot             | 1         | 1      | 0.92%   |
| LITEONIT            | 1         | 1      | 0.92%   |
| Intenso             | 1         | 1      | 0.92%   |
| Intel               | 1         | 1      | 0.92%   |
| FORESEE             | 1         | 1      | 0.92%   |
| Corsair             | 1         | 1      | 0.92%   |
| Apple               | 1         | 1      | 0.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 7GB               | 3         | 2.54%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 3         | 2.54%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 2.54%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 1.69%   |
| Toshiba DT01ACA100 1TB                  | 2         | 1.69%   |
| Seagate Expansion 1TB                   | 2         | 1.69%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.69%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.69%   |
| HGST HTS541010A9E680 1TB                | 2         | 1.69%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.69%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.85%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.85%   |
| WDC WDBNCE2500PNC 250GB SSD             | 1         | 0.85%   |
| WDC WDBNCE0010PNC 1TB SSD               | 1         | 0.85%   |
| WDC WD800BEVS-22RST0 80GB               | 1         | 0.85%   |
| WDC WD3200LPVX-60V0TT0 320GB            | 1         | 0.85%   |
| WDC WD3200LPVX-00V0TT0 320GB            | 1         | 0.85%   |
| WDC WD2500BPVT-00JJ5T0 250GB            | 1         | 0.85%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.85%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.85%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB    | 1         | 0.85%   |
| Unknown Y016B  16GB                     | 1         | 0.85%   |
| Unknown xD/SD/M.S.                      | 1         | 0.85%   |
| Unknown SS16G  16GB                     | 1         | 0.85%   |
| Unknown SDU1  64GB                      | 1         | 0.85%   |
| Unknown MMC Card  128GB                 | 1         | 0.85%   |
| Toshiba THNSNF128GMCS 128GB SSD         | 1         | 0.85%   |
| Toshiba Q300. 480GB SSD                 | 1         | 0.85%   |
| Toshiba MQ01ABD100V -63 1TB             | 1         | 0.85%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.85%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.85%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.85%   |
| SPCC Solid State Disk 120GB             | 1         | 0.85%   |
| SK Hynix PC601 NVMe 256GB               | 1         | 0.85%   |
| SK Hynix NVMe SSD Drive 512GB           | 1         | 0.85%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 0.85%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB       | 1         | 0.85%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.85%   |
| Seagate ST9500420AS 500GB               | 1         | 0.85%   |
| Seagate ST9250410AS 250GB               | 1         | 0.85%   |
| Seagate ST500NM0011 500GB               | 1         | 0.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.85%   |
| Seagate ST500DM002-1SB10A 500GB         | 1         | 0.85%   |
| Seagate ST4000DM004-2CV104 4TB          | 1         | 0.85%   |
| Seagate ST3500413AS 500GB               | 1         | 0.85%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 0.85%   |
| Seagate ST31000528AS 1TB                | 1         | 0.85%   |
| Seagate ST250DM000-1BD141 250GB         | 1         | 0.85%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 0.85%   |
| SanDisk SD6SF1M128G1022I 128GB SSD      | 1         | 0.85%   |
| SanDisk Extreme SSD 500GB               | 1         | 0.85%   |
| Samsung SSD SM841N 2.5 7mm 256GB        | 1         | 0.85%   |
| Samsung SSD 980 1TB                     | 1         | 0.85%   |
| Samsung SSD 860 EVO M.2 2TB             | 1         | 0.85%   |
| Samsung SSD 860 EVO 250GB               | 1         | 0.85%   |
| Samsung SSD 840 Series 250GB            | 1         | 0.85%   |
| Samsung NVMe SSD Drive 512GB            | 1         | 0.85%   |
| Samsung NVMe SSD Drive 1TB              | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 20     | 35.9%   |
| WDC     | 8         | 10     | 20.51%  |
| Toshiba | 6         | 6      | 15.38%  |
| Hitachi | 5         | 6      | 12.82%  |
| Unknown | 3         | 3      | 7.69%   |
| HGST    | 3         | 3      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 12     | 20.45%  |
| Samsung Electronics | 8         | 9      | 18.18%  |
| SanDisk             | 5         | 5      | 11.36%  |
| Kingston            | 4         | 4      | 9.09%   |
| WDC                 | 3         | 3      | 6.82%   |
| China               | 3         | 4      | 6.82%   |
| Toshiba             | 2         | 3      | 4.55%   |
| SPCC                | 1         | 1      | 2.27%   |
| Patriot             | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| LITEONIT            | 1         | 1      | 2.27%   |
| Intenso             | 1         | 1      | 2.27%   |
| Intel               | 1         | 1      | 2.27%   |
| FORESEE             | 1         | 1      | 2.27%   |
| Corsair             | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |
| A-DATA Technology   | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 36        | 50     | 37.89%  |
| HDD     | 33        | 48     | 34.74%  |
| NVMe    | 20        | 22     | 21.05%  |
| MMC     | 4         | 4      | 4.21%   |
| Unknown | 2         | 2      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 90     | 63.64%  |
| NVMe | 20        | 22     | 22.73%  |
| SAS  | 8         | 10     | 9.09%   |
| MMC  | 4         | 4      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 62     | 56.16%  |
| 0.51-1.0   | 26        | 30     | 35.62%  |
| 1.01-2.0   | 5         | 5      | 6.85%   |
| 3.01-4.0   | 1         | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 23.94%  |
| 251-500        | 15        | 21.13%  |
| 501-1000       | 12        | 16.9%   |
| 1001-2000      | 9         | 12.68%  |
| Unknown        | 8         | 11.27%  |
| 2001-3000      | 4         | 5.63%   |
| 51-100         | 3         | 4.23%   |
| More than 3000 | 2         | 2.82%   |
| 21-50          | 1         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 18        | 25%     |
| 51-100    | 18        | 25%     |
| 251-500   | 10        | 13.89%  |
| 101-250   | 8         | 11.11%  |
| Unknown   | 8         | 11.11%  |
| 1-20      | 7         | 9.72%   |
| 501-1000  | 2         | 2.78%   |
| 1001-2000 | 1         | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 7.69%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 7.69%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 7.69%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 7.69%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 7.69%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 7.69%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 7.69%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 1         | 1      | 7.69%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 7.69%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 7.69%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 41.67%  |
| SanDisk             | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 71.43%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 58.33%  |
| SSD  | 4         | 4      | 33.33%  |
| NVMe | 1         | 1      | 8.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intenso SSD SATAIII 128GB | 1         | 1      | 100%    |

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
| Works    | 40        | 55     | 46.51%  |
| Detected | 34        | 57     | 39.53%  |
| Malfunc  | 11        | 13     | 12.79%  |
| Failed   | 1         | 1      | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 58        | 64.44%  |
| AMD                         | 8         | 8.89%   |
| Samsung Electronics         | 6         | 6.67%   |
| SK Hynix                    | 5         | 5.56%   |
| Sandisk                     | 2         | 2.22%   |
| Micron Technology           | 2         | 2.22%   |
| KIOXIA                      | 2         | 2.22%   |
| VIA Technologies            | 1         | 1.11%   |
| Realtek Semiconductor       | 1         | 1.11%   |
| Phison Electronics          | 1         | 1.11%   |
| Micron/Crucial Technology   | 1         | 1.11%   |
| Kingston Technology Company | 1         | 1.11%   |
| JMicron Technology          | 1         | 1.11%   |
| ADATA Technology            | 1         | 1.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 6%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 5%      |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 5%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 4%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 4%      |
| SK Hynix BC511                                                                          | 3         | 3%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 3%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 3%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 3%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 3%      |
| Samsung NVMe SSD Controller 980                                                         | 2         | 2%      |
| Micron Non-Volatile memory controller                                                   | 2         | 2%      |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 2%      |
| Intel SATA Controller [RAID mode]                                                       | 2         | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 2%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 2%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 2%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 2%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 2%      |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 1%      |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 1%      |
| SK Hynix Gold P31 SSD                                                                   | 1         | 1%      |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 1%      |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 1%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 1%      |
| Samsung Apple PCIe SSD                                                                  | 1         | 1%      |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 1%      |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 1%      |
| Micron/Crucial NVMe Controller                                                          | 1         | 1%      |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 1%      |
| JMicron JMB362 SATA Controller                                                          | 1         | 1%      |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 1%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 1%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 1%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 1%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 1%      |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 1%      |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 1%      |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 1%      |
| AMD FCH SATA Controller D                                                               | 1         | 1%      |
| ADATA Non-Volatile memory controller                                                    | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 58        | 63.74%  |
| NVMe | 20        | 21.98%  |
| IDE  | 7         | 7.69%   |
| RAID | 6         | 6.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 86.96%  |
| AMD    | 9         | 13.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz              | 2         | 2.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz              | 2         | 2.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz             | 2         | 2.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz              | 2         | 2.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 2.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz              | 2         | 2.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz              | 2         | 2.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz              | 2         | 2.9%    |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1         | 1.45%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 1.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 1         | 1.45%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1         | 1.45%   |
| Intel Core i7-8850H CPU @ 2.60GHz              | 1         | 1.45%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 1.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1         | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.45%   |
| Intel Core i7-4650U CPU @ 1.70GHz              | 1         | 1.45%   |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1         | 1.45%   |
| Intel Core i7-4558U CPU @ 2.80GHz              | 1         | 1.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 1.45%   |
| Intel Core i7-2720QM CPU @ 2.20GHz             | 1         | 1.45%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 1.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1         | 1.45%   |
| Intel Core i7-10875H CPU @ 2.30GHz             | 1         | 1.45%   |
| Intel Core i7-10870H CPU @ 2.20GHz             | 1         | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.45%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1         | 1.45%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1         | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.45%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.45%   |
| Intel Core i5-6400T CPU @ 2.20GHz              | 1         | 1.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.45%   |
| Intel Core i5-4210M CPU @ 2.60GHz              | 1         | 1.45%   |
| Intel Core i5-4200M CPU @ 2.50GHz              | 1         | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 1.45%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz             | 1         | 1.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.45%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 1.45%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 1         | 1.45%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz          | 1         | 1.45%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz           | 1         | 1.45%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 1.45%   |
| Intel Core 2 CPU T7200 @ 2.00GHz               | 1         | 1.45%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 1.45%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz        | 1         | 1.45%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 1.45%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.45%   |
| AMD Ryzen 3 3250U with Radeon Graphics         | 1         | 1.45%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1         | 1.45%   |
| AMD FX-8320 Eight-Core Processor               | 1         | 1.45%   |
| AMD FX-6300 Six-Core Processor                 | 1         | 1.45%   |
| AMD E1-2500 APU with Radeon HD Graphics        | 1         | 1.45%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 23        | 33.33%  |
| Intel Core i5           | 23        | 33.33%  |
| Intel Core i3           | 3         | 4.35%   |
| Other                   | 2         | 2.9%    |
| Intel Pentium Silver    | 2         | 2.9%    |
| Intel Core 2 Duo        | 2         | 2.9%    |
| AMD Ryzen 3             | 2         | 2.9%    |
| AMD FX                  | 2         | 2.9%    |
| Intel Xeon              | 1         | 1.45%   |
| Intel Pentium Dual-Core | 1         | 1.45%   |
| Intel Core M            | 1         | 1.45%   |
| Intel Core 2 Quad       | 1         | 1.45%   |
| Intel Core 2            | 1         | 1.45%   |
| AMD Ryzen Threadripper  | 1         | 1.45%   |
| AMD Ryzen 7             | 1         | 1.45%   |
| AMD E1                  | 1         | 1.45%   |
| AMD A6                  | 1         | 1.45%   |
| AMD A4                  | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 31        | 44.93%  |
| 4      | 24        | 34.78%  |
| 6      | 7         | 10.14%  |
| 8      | 4         | 5.8%    |
| 12     | 1         | 1.45%   |
| 3      | 1         | 1.45%   |
| 1      | 1         | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 75.36%  |
| 1      | 17        | 24.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 69        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 40.85%  |
| 0x206a7    | 6         | 8.45%   |
| 0x306c3    | 4         | 5.63%   |
| 0xa0652    | 3         | 4.23%   |
| 0x906e9    | 3         | 4.23%   |
| 0x306a9    | 3         | 4.23%   |
| 0x706e5    | 2         | 2.82%   |
| 0x306d4    | 2         | 2.82%   |
| 0x1067a    | 2         | 2.82%   |
| 0x06000852 | 2         | 2.82%   |
| 0x906ed    | 1         | 1.41%   |
| 0x806ec    | 1         | 1.41%   |
| 0x806d1    | 1         | 1.41%   |
| 0x806c1    | 1         | 1.41%   |
| 0x706a8    | 1         | 1.41%   |
| 0x706a1    | 1         | 1.41%   |
| 0x6fd      | 1         | 1.41%   |
| 0x6f6      | 1         | 1.41%   |
| 0x506e3    | 1         | 1.41%   |
| 0x40651    | 1         | 1.41%   |
| 0x20655    | 1         | 1.41%   |
| 0x08600106 | 1         | 1.41%   |
| 0x08108109 | 1         | 1.41%   |
| 0x06006705 | 1         | 1.41%   |
| 0x0600111f | 1         | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 15.94%  |
| SandyBridge   | 8         | 11.59%  |
| Haswell       | 8         | 11.59%  |
| IvyBridge     | 7         | 10.14%  |
| Skylake       | 5         | 7.25%   |
| CometLake     | 4         | 5.8%    |
| Broadwell     | 4         | 5.8%    |
| Piledriver    | 3         | 4.35%   |
| Penryn        | 3         | 4.35%   |
| IceLake       | 3         | 4.35%   |
| Zen           | 2         | 2.9%    |
| Westmere      | 2         | 2.9%    |
| Goldmont plus | 2         | 2.9%    |
| Core          | 2         | 2.9%    |
| Zen+          | 1         | 1.45%   |
| Zen 2         | 1         | 1.45%   |
| TigerLake     | 1         | 1.45%   |
| Jaguar        | 1         | 1.45%   |
| Excavator     | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 51        | 56.04%  |
| Nvidia | 24        | 26.37%  |
| AMD    | 16        | 17.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 5.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 5.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 4.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 4.26%   |
| Intel HD Graphics 5500                                                        | 3         | 3.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 3.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 3.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 2.13%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.13%   |
| Intel HD Graphics 630                                                         | 2         | 2.13%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.13%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.13%   |
| Nvidia TU117M                                                                 | 1         | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1         | 1.06%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.06%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 1.06%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.06%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 1.06%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.06%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.06%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1         | 1.06%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.06%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.06%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.06%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.06%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 1.06%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.06%   |
| Nvidia G86 [GeForce 8300 GS]                                                  | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.06%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.06%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                        | 1         | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.06%   |
| Intel HD Graphics 5300                                                        | 1         | 1.06%   |
| Intel HD Graphics 530                                                         | 1         | 1.06%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.06%   |
| AMD Trinity 2 [Radeon HD 7480D]                                               | 1         | 1.06%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                      | 1         | 1.06%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.06%   |
| AMD RS780L [Radeon 3000]                                                      | 1         | 1.06%   |
| AMD Renoir                                                                    | 1         | 1.06%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                                       | 1         | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.06%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 43.48%  |
| Intel + Nvidia | 15        | 21.74%  |
| 1 x AMD        | 11        | 15.94%  |
| 1 x Nvidia     | 8         | 11.59%  |
| Intel + AMD    | 4         | 5.8%    |
| AMD + Nvidia   | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 62        | 89.86%  |
| Proprietary | 7         | 10.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 67.14%  |
| 3.01-4.0   | 6         | 8.57%   |
| 0.51-1.0   | 6         | 8.57%   |
| 1.01-2.0   | 5         | 7.14%   |
| 0.01-0.5   | 3         | 4.29%   |
| 7.01-8.0   | 2         | 2.86%   |
| 2.01-3.0   | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 16.88%  |
| Samsung Electronics     | 10        | 12.99%  |
| LG Display              | 10        | 12.99%  |
| Chimei Innolux          | 8         | 10.39%  |
| BOE                     | 8         | 10.39%  |
| Dell                    | 5         | 6.49%   |
| Chi Mei Optoelectronics | 4         | 5.19%   |
| Hewlett-Packard         | 3         | 3.9%    |
| Goldstar                | 2         | 2.6%    |
| Apple                   | 2         | 2.6%    |
| AOC                     | 2         | 2.6%    |
| Vizio                   | 1         | 1.3%    |
| Toshiba                 | 1         | 1.3%    |
| Sony                    | 1         | 1.3%    |
| Sceptre                 | 1         | 1.3%    |
| Philips                 | 1         | 1.3%    |
| NEC Computers           | 1         | 1.3%    |
| Insignia                | 1         | 1.3%    |
| AUS                     | 1         | 1.3%    |
| Ancor Communications    | 1         | 1.3%    |
| Acer                    | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 2.56%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                        | 1         | 1.28%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                          | 1         | 1.28%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                       | 1         | 1.28%   |
| Sceptre LCD Monitor P30 2560x1080                                         | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 250x170mm 11.9-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 340x190mm 15.3-inch      | 1         | 1.28%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.28%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch        | 1         | 1.28%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1190x340mm 48.7-inch        | 1         | 1.28%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                   | 1         | 1.28%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch               | 1         | 1.28%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.28%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.28%   |
| LG Display LCD Monitor LGD0503 1366x768 340x190mm 15.3-inch               | 1         | 1.28%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.28%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch               | 1         | 1.28%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch              | 1         | 1.28%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch               | 1         | 1.28%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch               | 1         | 1.28%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch                | 1         | 1.28%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch          | 1         | 1.28%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch                   | 1         | 1.28%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                    | 1         | 1.28%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch                      | 1         | 1.28%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.28%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch                         | 1         | 1.28%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                         | 1         | 1.28%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch           | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch           | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.28%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 310x170mm 13.9-inch           | 1         | 1.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.28%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE089B 1280x800 261x163mm 12.1-inch                      | 1         | 1.28%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE07B6 1920x1080 382x215mm 17.3-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.28%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 1.28%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.28%   |
| AUS LCD Monitor VG259 1920x1080                                           | 1         | 1.28%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 1         | 1.28%   |
| AU Optronics LCD Monitor AUO5A3D 1920x1080 309x174mm 14.0-inch            | 1         | 1.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 44.74%  |
| 1366x768 (WXGA)    | 18        | 23.68%  |
| 1280x800 (WXGA)    | 5         | 6.58%   |
| 1680x1050 (WSXGA+) | 3         | 3.95%   |
| 1600x900 (HD+)     | 3         | 3.95%   |
| 2560x1440 (QHD)    | 2         | 2.63%   |
| 2560x1080          | 2         | 2.63%   |
| 1440x900 (WXGA+)   | 2         | 2.63%   |
| 1280x1024 (SXGA)   | 2         | 2.63%   |
| 3840x1080          | 1         | 1.32%   |
| 2560x1600          | 1         | 1.32%   |
| 2160x1440          | 1         | 1.32%   |
| 1920x1200 (WUXGA)  | 1         | 1.32%   |
| 1360x768           | 1         | 1.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 34.62%  |
| 14      | 11        | 14.1%   |
| 17      | 8         | 10.26%  |
| 24      | 5         | 6.41%   |
| 13      | 4         | 5.13%   |
| 31      | 3         | 3.85%   |
| 23      | 3         | 3.85%   |
| Unknown | 3         | 3.85%   |
| 27      | 2         | 2.56%   |
| 22      | 2         | 2.56%   |
| 19      | 2         | 2.56%   |
| 18      | 2         | 2.56%   |
| 12      | 2         | 2.56%   |
| 48      | 1         | 1.28%   |
| 42      | 1         | 1.28%   |
| 34      | 1         | 1.28%   |
| 32      | 1         | 1.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 53.95%  |
| 501-600     | 9         | 11.84%  |
| 351-400     | 8         | 10.53%  |
| 401-500     | 4         | 5.26%   |
| 201-300     | 4         | 5.26%   |
| 601-700     | 3         | 3.95%   |
| Unknown     | 3         | 3.95%   |
| 701-800     | 2         | 2.63%   |
| 1001-1500   | 1         | 1.32%   |
| 901-1000    | 1         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 56        | 75.68%  |
| 16/10   | 11        | 14.86%  |
| Unknown | 3         | 4.05%   |
| 6/5     | 1         | 1.35%   |
| 5/4     | 1         | 1.35%   |
| 32/9    | 1         | 1.35%   |
| 21/9    | 1         | 1.35%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 35.06%  |
| 81-90          | 14        | 18.18%  |
| 201-250        | 8         | 10.39%  |
| 121-130        | 6         | 7.79%   |
| 351-500        | 5         | 6.49%   |
| 141-150        | 3         | 3.9%    |
| Unknown        | 3         | 3.9%    |
| 61-70          | 2         | 2.6%    |
| 301-350        | 2         | 2.6%    |
| 151-200        | 2         | 2.6%    |
| 501-1000       | 2         | 2.6%    |
| 71-80          | 1         | 1.3%    |
| 251-300        | 1         | 1.3%    |
| 131-140        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 25        | 34.72%  |
| 101-120 | 22        | 30.56%  |
| 51-100  | 18        | 25%     |
| Unknown | 3         | 4.17%   |
| 1-50    | 2         | 2.78%   |
| 161-240 | 2         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 85.51%  |
| 2     | 9         | 13.04%  |
| 3     | 1         | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 37        | 32.17%  |
| Intel                             | 35        | 30.43%  |
| Qualcomm Atheros                  | 17        | 14.78%  |
| Broadcom                          | 7         | 6.09%   |
| TP-Link                           | 3         | 2.61%   |
| Qualcomm Atheros Communications   | 3         | 2.61%   |
| Broadcom Limited                  | 3         | 2.61%   |
| Ralink Technology                 | 2         | 1.74%   |
| Xiaomi                            | 1         | 0.87%   |
| Samsung Electronics               | 1         | 0.87%   |
| NetGear                           | 1         | 0.87%   |
| Microsoft                         | 1         | 0.87%   |
| Marvell Technology Group          | 1         | 0.87%   |
| Huawei Technologies               | 1         | 0.87%   |
| Ericsson Business Mobile Networks | 1         | 0.87%   |
| D-Link System                     | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 23        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 5         | 3.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 3.62%   |
| Intel Wireless 7265                                                       | 4         | 2.9%    |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 2.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 2.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 2.17%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 2.17%   |
| Intel Wireless 3160                                                       | 3         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 2         | 1.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 1.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 2         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.45%   |
| Intel Wireless 8260                                                       | 2         | 1.45%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 0.72%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.72%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.72%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 0.72%   |
| Intel Wireless 8265 / 8275                                                | 1         | 0.72%   |
| Intel Wireless 3165                                                       | 1         | 0.72%   |
| Intel Wi-Fi 6 AX201                                                       | 1         | 0.72%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.72%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.72%   |
| Intel I211 Gigabit Network Connection                                     | 1         | 0.72%   |
| Intel I210 Gigabit Network Connection                                     | 1         | 0.72%   |
| Intel Ethernet controller                                                 | 1         | 0.72%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.72%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                     | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                     | 1         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 0.72%   |
| Intel Centrino Wireless-N 105                                             | 1         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 0.72%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 43.24%  |
| Qualcomm Atheros                | 13        | 17.57%  |
| Realtek Semiconductor           | 10        | 13.51%  |
| Broadcom                        | 5         | 6.76%   |
| TP-Link                         | 3         | 4.05%   |
| Qualcomm Atheros Communications | 3         | 4.05%   |
| Ralink Technology               | 2         | 2.7%    |
| Broadcom Limited                | 2         | 2.7%    |
| NetGear                         | 1         | 1.35%   |
| Microsoft                       | 1         | 1.35%   |
| Marvell Technology Group        | 1         | 1.35%   |
| D-Link System                   | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 6.76%   |
| Intel Wireless 7265                                                       | 4         | 5.41%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 5.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 4.05%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 4.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 4.05%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 4.05%   |
| Intel Wireless 3160                                                       | 3         | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 4.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 4.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.7%    |
| Intel Wireless 8260                                                       | 2         | 2.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.35%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.35%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.35%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 1.35%   |
| Intel Wireless 8265 / 8275                                                | 1         | 1.35%   |
| Intel Wireless 3165                                                       | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201                                                       | 1         | 1.35%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.35%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.35%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.35%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.35%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 1.35%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]      | 1         | 1.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.35%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 1         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 31        | 50.82%  |
| Intel                 | 15        | 24.59%  |
| Qualcomm Atheros      | 8         | 13.11%  |
| Broadcom              | 3         | 4.92%   |
| Xiaomi                | 1         | 1.64%   |
| Samsung Electronics   | 1         | 1.64%   |
| Huawei Technologies   | 1         | 1.64%   |
| Broadcom Limited      | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 36.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 3.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 3.17%   |
| Intel Ethernet Connection I217-V                                  | 2         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.59%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.59%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.59%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.59%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.59%   |
| Intel Ethernet controller                                         | 1         | 1.59%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.59%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.59%   |
| Huawei ELE-AL00                                                   | 1         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.59%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 52.85%  |
| Ethernet | 57        | 46.34%  |
| Modem    | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 63.53%  |
| Ethernet | 31        | 36.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 65.22%  |
| 1     | 22        | 31.88%  |
| 3     | 2         | 2.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 72.86%  |
| Yes  | 19        | 27.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 24        | 48.98%  |
| Qualcomm Atheros Communications | 9         | 18.37%  |
| Realtek Semiconductor           | 4         | 8.16%   |
| Broadcom                        | 4         | 8.16%   |
| Dell                            | 2         | 4.08%   |
| Cambridge Silicon Radio         | 2         | 4.08%   |
| Marvell Semiconductor           | 1         | 2.04%   |
| Lite-On Technology              | 1         | 2.04%   |
| Foxconn / Hon Hai               | 1         | 2.04%   |
| Apple                           | 1         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 13        | 26.53%  |
| Intel Bluetooth wireless interface                  | 8         | 16.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4.08%   |
| Realtek Bluetooth Radio                             | 2         | 4.08%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 4.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.08%   |
| Qualcomm Atheros Bluetooth                          | 1         | 2.04%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2.04%   |
| Lite-On Bluetooth Radio                             | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.04%   |
| Intel AX200 Bluetooth                               | 1         | 2.04%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.04%   |
| Dell DW375 Bluetooth Module                         | 1         | 2.04%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 2.04%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.04%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 2.04%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.04%   |
| Apple Bluetooth Host Controller                     | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 60        | 63.16%  |
| Nvidia              | 17        | 17.89%  |
| AMD                 | 16        | 16.84%  |
| GN Netcom           | 1         | 1.05%   |
| C-Media Electronics | 1         | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 7.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 5.31%   |
| Intel Cannon Lake PCH cAVS                                                        | 5         | 4.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 3.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 3.54%   |
| Intel Sunrise Point-LP HD Audio                                                   | 4         | 3.54%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 3.54%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 3.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 2.65%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 2.65%   |
| Intel 8 Series HD Audio Controller                                                | 3         | 2.65%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 3         | 2.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.77%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 1.77%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.77%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 1.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2         | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.77%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 1.77%   |
| AMD FCH Azalia Controller                                                         | 2         | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1         | 0.88%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.88%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.88%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.88%   |
| Nvidia Audio device                                                               | 1         | 0.88%   |
| Intel USB PnP Sound Device                                                        | 1         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 0.88%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 0.88%   |
| GN Netcom Jabra Evolve 65                                                         | 1         | 0.88%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1         | 0.88%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 0.88%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.88%   |
| AMD Polaris 22 HDMI Audio                                                         | 1         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                          | 1         | 0.88%   |
| AMD High Definition Audio Controller                                              | 1         | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 0.88%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 28.85%  |
| SK Hynix            | 7         | 13.46%  |
| Unknown             | 5         | 9.62%   |
| Kingston            | 5         | 9.62%   |
| Crucial             | 5         | 9.62%   |
| Elpida              | 3         | 5.77%   |
| Ramaxel Technology  | 2         | 3.85%   |
| Micron Technology   | 2         | 3.85%   |
| Corsair             | 2         | 3.85%   |
| A-DATA Technology   | 2         | 3.85%   |
| Team                | 1         | 1.92%   |
| S                   | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| G.Skill             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 3.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 3.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.79%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 1.79%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.79%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 1.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 1.79%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.79%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s               | 1         | 1.79%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.79%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.79%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.79%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| SK Hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.79%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 1.79%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.79%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                                 | 1         | 1.79%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s                  | 1         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s             | 1         | 1.79%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s                | 1         | 1.79%   |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s          | 1         | 1.79%   |
| Kingston RAM HP26D4S9S8MH-8 8GB SODIMM DDR4 2400MT/s                | 1         | 1.79%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s                 | 1         | 1.79%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s             | 1         | 1.79%   |
| Kingston RAM 9905469-066.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.79%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.79%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 1         | 1.79%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.79%   |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s               | 1         | 1.79%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s                   | 1         | 1.79%   |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                 | 1         | 1.79%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                         | 1         | 1.79%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s                | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 47.83%  |
| DDR4    | 19        | 41.3%   |
| LPDDR4  | 2         | 4.35%   |
| DDR2    | 2         | 4.35%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 80.43%  |
| DIMM         | 8         | 17.39%  |
| Row Of Chips | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 20        | 37.74%  |
| 8192  | 18        | 33.96%  |
| 16384 | 5         | 9.43%   |
| 2048  | 5         | 9.43%   |
| 32768 | 3         | 5.66%   |
| 1024  | 2         | 3.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 17        | 35.42%  |
| 2667  | 11        | 22.92%  |
| 3200  | 4         | 8.33%   |
| 1334  | 4         | 8.33%   |
| 2400  | 3         | 6.25%   |
| 3266  | 2         | 4.17%   |
| 1333  | 2         | 4.17%   |
| 4267  | 1         | 2.08%   |
| 2666  | 1         | 2.08%   |
| 1067  | 1         | 2.08%   |
| 667   | 1         | 2.08%   |
| 533   | 1         | 2.08%   |

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


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 29.79%  |
| Acer                                   | 7         | 14.89%  |
| Microdia                               | 5         | 10.64%  |
| IMC Networks                           | 3         | 6.38%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.38%   |
| Sunplus Innovation Technology          | 2         | 4.26%   |
| Ricoh                                  | 2         | 4.26%   |
| Realtek Semiconductor                  | 2         | 4.26%   |
| Suyin                                  | 1         | 2.13%   |
| Silicon Motion                         | 1         | 2.13%   |
| Samsung Electronics                    | 1         | 2.13%   |
| Quanta                                 | 1         | 2.13%   |
| Microsoft                              | 1         | 2.13%   |
| Luxvisions Innotech Limited            | 1         | 2.13%   |
| Logitech                               | 1         | 2.13%   |
| DLEQNA1G4FA2WJ                         | 1         | 2.13%   |
| Apple                                  | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 6.25%   |
| Acer HD Webcam                                                             | 3         | 6.25%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 4.17%   |
| Chicony HD Webcam                                                          | 2         | 4.17%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 2.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 2.08%   |
| Sunplus HD WebCam                                                          | 1         | 2.08%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 2.08%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 2.08%   |
| Ricoh Pavilion Webcam                                                      | 1         | 2.08%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 2.08%   |
| Quanta HP High Definition 1MP Webcam                                       | 1         | 2.08%   |
| Microsoft LifeCam Rear                                                     | 1         | 2.08%   |
| Microsoft LifeCam Front                                                    | 1         | 2.08%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 2.08%   |
| Microdia PC Microscope camera                                              | 1         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.08%   |
| Microdia Integrated Webcam HD                                              | 1         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 2.08%   |
| Logitech HD Webcam C615                                                    | 1         | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 2.08%   |
| IMC Networks Integrated Webcam                                             | 1         | 2.08%   |
| IMC Networks Integrated Camera                                             | 1         | 2.08%   |
| DLEQNA1G4FA2WJ HP TrueVision HD Camera                                     | 1         | 2.08%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 2.08%   |
| Chicony USB2.0 Camera                                                      | 1         | 2.08%   |
| Chicony Integrated Camera                                                  | 1         | 2.08%   |
| Chicony HP Webcam                                                          | 1         | 2.08%   |
| Chicony HP TrueVision HD                                                   | 1         | 2.08%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2.08%   |
| Chicony HP HD Camera                                                       | 1         | 2.08%   |
| Chicony HD User Facing                                                     | 1         | 2.08%   |
| Chicony CNF8248                                                            | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.08%   |
| Apple FaceTime HD Camera                                                   | 1         | 2.08%   |
| Acer Lenovo EasyCamera                                                     | 1         | 2.08%   |
| Acer Integrated Camera                                                     | 1         | 2.08%   |
| Acer HD Camera                                                             | 1         | 2.08%   |
| Acer EasyCamera                                                            | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
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


| Model                                                                      | Computers | Percent |
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


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Alcor Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 45        | 64.29%  |
| 1     | 16        | 22.86%  |
| 2     | 8         | 11.43%  |
| 3     | 1         | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 34.38%  |
| Chipcard              | 5         | 15.63%  |
| Net/wireless          | 4         | 12.5%   |
| Graphics card         | 4         | 12.5%   |
| Storage               | 3         | 9.38%   |
| Multimedia controller | 2         | 6.25%   |
| Modem                 | 1         | 3.13%   |
| Camera                | 1         | 3.13%   |
| Bluetooth             | 1         | 3.13%   |

