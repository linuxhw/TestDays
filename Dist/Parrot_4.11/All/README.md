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
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
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
| 5.10.0-6parrot1-amd64    | 27        | 36.49%  |
| 5.10.0-8parrot1-amd64    | 17        | 22.97%  |
| 5.14.0-9parrot1-amd64    | 11        | 14.86%  |
| 5.10.0-3parrot1-amd64    | 5         | 6.76%   |
| 5.7.0-2parrot2-amd64     | 4         | 5.41%   |
| 5.10.0-5parrot1-amd64    | 4         | 5.41%   |
| 5.14.0-2parrot1-amd64    | 3         | 4.05%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.35%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.35%   |
| Unknown                  | 1         | 1.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 54        | 72.97%  |
| 5.14.0  | 14        | 18.92%  |
| 5.7.0   | 4         | 5.41%   |
| 5.6.0   | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 54        | 72.97%  |
| 5.14    | 14        | 18.92%  |
| 5.7     | 4         | 5.41%   |
| 5.6     | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 73        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 41        | 55.41%  |
| KDE5    | 18        | 24.32%  |
| KDE     | 7         | 9.46%   |
| Unknown | 4         | 5.41%   |
| XFCE    | 3         | 4.05%   |
| LXDE    | 1         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 73        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 34.67%  |
| LightDM | 25        | 33.33%  |
| TDM     | 23        | 30.67%  |
| SDDM    | 1         | 1.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 34        | 46.58%  |
| fr_FR   | 6         | 8.22%   |
| en_GB   | 6         | 8.22%   |
| ru_RU   | 4         | 5.48%   |
| pt_BR   | 4         | 5.48%   |
| en_AU   | 4         | 5.48%   |
| Unknown | 3         | 4.11%   |
| es_ES   | 2         | 2.74%   |
| de_DE   | 2         | 2.74%   |
| ru_UA   | 1         | 1.37%   |
| pl_PL   | 1         | 1.37%   |
| nl_BE   | 1         | 1.37%   |
| id_ID   | 1         | 1.37%   |
| es_CO   | 1         | 1.37%   |
| en_NG   | 1         | 1.37%   |
| cs_CZ   | 1         | 1.37%   |
| an_ES   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 47        | 62.67%  |
| EFI  | 28        | 37.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 58        | 79.45%  |
| Ext4  | 11        | 15.07%  |
| Xfs   | 4         | 5.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 30        | 40.54%  |
| Unknown | 27        | 36.49%  |
| MBR     | 17        | 22.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 82.43%  |
| Yes       | 13        | 17.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 63.01%  |
| Yes       | 27        | 36.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 20.55%  |
| ASUSTek Computer    | 12        | 16.44%  |
| Dell                | 11        | 15.07%  |
| MSI                 | 5         | 6.85%   |
| Lenovo              | 5         | 6.85%   |
| Acer                | 5         | 6.85%   |
| Samsung Electronics | 2         | 2.74%   |
| Apple               | 2         | 2.74%   |
| Alienware           | 2         | 2.74%   |
| ZOTAC               | 1         | 1.37%   |
| Wortmann AG         | 1         | 1.37%   |
| Toxic               | 1         | 1.37%   |
| Toshiba             | 1         | 1.37%   |
| Sony                | 1         | 1.37%   |
| Quanta              | 1         | 1.37%   |
| Microsoft           | 1         | 1.37%   |
| Intel               | 1         | 1.37%   |
| GPU Company         | 1         | 1.37%   |
| Gigabyte Technology | 1         | 1.37%   |
| Gateway             | 1         | 1.37%   |
| Fujitsu             | 1         | 1.37%   |
| Eluktronics         | 1         | 1.37%   |
| ASRock              | 1         | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 2.74%   |
| ASUS Q524UQ                             | 2         | 2.74%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 1.37%   |
| Toxic GM7MQ8P                           | 1         | 1.37%   |
| Toshiba Satellite L655                  | 1         | 1.37%   |
| Sony SVP1321L1EBI                       | 1         | 1.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.37%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 1.37%   |
| Quanta HDX PREMIUM SERIES               | 1         | 1.37%   |
| MSI GT60 2OC/2OD                        | 1         | 1.37%   |
| MSI GS66 Stealth 10UG                   | 1         | 1.37%   |
| MSI GE75 Raider 10SF                    | 1         | 1.37%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 1.37%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 1.37%   |
| Microsoft Surface Pro 3                 | 1         | 1.37%   |
| Lenovo Yoga S740-14IIL 81RS             | 1         | 1.37%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 1.37%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 1.37%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 1.37%   |
| Lenovo B50-80 80EW                      | 1         | 1.37%   |
| Intel NUC8i7HVK                         | 1         | 1.37%   |
| HP ZBook 15 G5                          | 1         | 1.37%   |
| HP Pavilion Notebook                    | 1         | 1.37%   |
| HP Pavilion dv7                         | 1         | 1.37%   |
| HP Pavilion dv6700                      | 1         | 1.37%   |
| HP Pavilion dv6                         | 1         | 1.37%   |
| HP Pavilion dv4                         | 1         | 1.37%   |
| HP Laptop 15s-eq1xxx                    | 1         | 1.37%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.37%   |
| HP EliteBook 8470p                      | 1         | 1.37%   |
| HP EliteBook 840 G8 Notebook PC         | 1         | 1.37%   |
| HP Compaq Pro 6305 MT                   | 1         | 1.37%   |
| HP All-in-One 24-f0xx                   | 1         | 1.37%   |
| HP 250 G7 Notebook PC                   | 1         | 1.37%   |
| GPU Company GWTN141-10                  | 1         | 1.37%   |
| Gigabyte A320M-S2H                      | 1         | 1.37%   |
| Gateway MP8708                          | 1         | 1.37%   |
| Fujitsu LIFEBOOK T731                   | 1         | 1.37%   |
| Eluktronics MAG-15u                     | 1         | 1.37%   |
| Dell XPS 8930                           | 1         | 1.37%   |
| Dell Precision M4600                    | 1         | 1.37%   |
| Dell OptiPlex 7070                      | 1         | 1.37%   |
| Dell OptiPlex 3010                      | 1         | 1.37%   |
| Dell Latitude E7440                     | 1         | 1.37%   |
| Dell Latitude E6420                     | 1         | 1.37%   |
| Dell Latitude E6410                     | 1         | 1.37%   |
| Dell Inspiron 7501                      | 1         | 1.37%   |
| Dell Inspiron 5593                      | 1         | 1.37%   |
| Dell Inspiron 5558                      | 1         | 1.37%   |
| Dell Inspiron 5420                      | 1         | 1.37%   |
| ASUS X75VB                              | 1         | 1.37%   |
| ASUS X450EA                             | 1         | 1.37%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 1.37%   |
| ASUS ROG STRIX B450-F GAMING            | 1         | 1.37%   |
| ASUS PRIME X399-A                       | 1         | 1.37%   |
| ASUS P8H67-M PRO                        | 1         | 1.37%   |
| ASUS M5A99X EVO                         | 1         | 1.37%   |
| ASUS M5A78L-M/USB3                      | 1         | 1.37%   |
| ASUS KJ250AA-ABE a6336.es               | 1         | 1.37%   |
| ASUS G74Sx                              | 1         | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP Pavilion            | 5         | 6.85%   |
| Dell Inspiron          | 4         | 5.48%   |
| Dell Latitude          | 3         | 4.11%   |
| Lenovo ThinkPad        | 2         | 2.74%   |
| HP ProBook             | 2         | 2.74%   |
| HP Laptop              | 2         | 2.74%   |
| HP EliteBook           | 2         | 2.74%   |
| Dell OptiPlex          | 2         | 2.74%   |
| ASUS Q524UQ            | 2         | 2.74%   |
| Acer Aspire            | 2         | 2.74%   |
| Wortmann AG TERRA      | 1         | 1.37%   |
| Toxic GM7MQ8P          | 1         | 1.37%   |
| Toshiba Satellite      | 1         | 1.37%   |
| Sony SVP1321L1EBI      | 1         | 1.37%   |
| Samsung 350V5C         | 1         | 1.37%   |
| Samsung 300E4C         | 1         | 1.37%   |
| Quanta HDX             | 1         | 1.37%   |
| MSI GT60               | 1         | 1.37%   |
| MSI GS66               | 1         | 1.37%   |
| MSI GE75               | 1         | 1.37%   |
| MSI GE73               | 1         | 1.37%   |
| MSI GE63               | 1         | 1.37%   |
| Microsoft Surface      | 1         | 1.37%   |
| Lenovo Yoga            | 1         | 1.37%   |
| Lenovo Y520-15IKBN     | 1         | 1.37%   |
| Lenovo B50-80          | 1         | 1.37%   |
| Intel NUC8i7HVK        | 1         | 1.37%   |
| HP ZBook               | 1         | 1.37%   |
| HP Compaq              | 1         | 1.37%   |
| HP All-in-One          | 1         | 1.37%   |
| HP 250                 | 1         | 1.37%   |
| GPU Company GWTN141-10 | 1         | 1.37%   |
| Gigabyte A320M-S2H     | 1         | 1.37%   |
| Gateway MP8708         | 1         | 1.37%   |
| Fujitsu LIFEBOOK       | 1         | 1.37%   |
| Eluktronics MAG-15u    | 1         | 1.37%   |
| Dell XPS               | 1         | 1.37%   |
| Dell Precision         | 1         | 1.37%   |
| ASUS X75VB             | 1         | 1.37%   |
| ASUS X450EA            | 1         | 1.37%   |
| ASUS VivoBook          | 1         | 1.37%   |
| ASUS ROG               | 1         | 1.37%   |
| ASUS PRIME             | 1         | 1.37%   |
| ASUS P8H67-M           | 1         | 1.37%   |
| ASUS M5A99X            | 1         | 1.37%   |
| ASUS M5A78L-M          | 1         | 1.37%   |
| ASUS KJ250AA-ABE       | 1         | 1.37%   |
| ASUS G74Sx             | 1         | 1.37%   |
| ASRock Z87             | 1         | 1.37%   |
| Apple MacBookPro8      | 1         | 1.37%   |
| Apple MacBookPro11     | 1         | 1.37%   |
| Alienware X51          | 1         | 1.37%   |
| Alienware m15          | 1         | 1.37%   |
| Acer TravelMate        | 1         | 1.37%   |
| Acer Swift             | 1         | 1.37%   |
| Acer Predator          | 1         | 1.37%   |
| Unknown                | 1         | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 12.33%  |
| 2013 | 9         | 12.33%  |
| 2011 | 9         | 12.33%  |
| 2016 | 7         | 9.59%   |
| 2020 | 6         | 8.22%   |
| 2018 | 6         | 8.22%   |
| 2021 | 4         | 5.48%   |
| 2012 | 4         | 5.48%   |
| 2017 | 3         | 4.11%   |
| 2015 | 3         | 4.11%   |
| 2014 | 3         | 4.11%   |
| 2010 | 3         | 4.11%   |
| 2008 | 3         | 4.11%   |
| 2007 | 3         | 4.11%   |
| 2006 | 1         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 54        | 73.97%  |
| Desktop    | 16        | 21.92%  |
| Tablet     | 1         | 1.37%   |
| Mini pc    | 1         | 1.37%   |
| All in one | 1         | 1.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 73        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 27.4%   |
| 8.01-16.0   | 17        | 23.29%  |
| 16.01-24.0  | 14        | 19.18%  |
| 3.01-4.0    | 12        | 16.44%  |
| 32.01-64.0  | 3         | 4.11%   |
| 64.01-256.0 | 3         | 4.11%   |
| 24.01-32.0  | 2         | 2.74%   |
| 2.01-3.0    | 1         | 1.37%   |
| 1.01-2.0    | 1         | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 29        | 38.67%  |
| 2.01-3.0  | 23        | 30.67%  |
| 3.01-4.0  | 11        | 14.67%  |
| 4.01-8.0  | 10        | 13.33%  |
| 8.01-16.0 | 1         | 1.33%   |
| 0.51-1.0  | 1         | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 38        | 52.05%  |
| 2      | 23        | 31.51%  |
| 3      | 9         | 12.33%  |
| 4      | 2         | 2.74%   |
| 5      | 1         | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 45        | 60.81%  |
| Yes       | 29        | 39.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 83.56%  |
| No        | 12        | 16.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 93.24%  |
| No        | 5         | 6.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 68.49%  |
| No        | 23        | 31.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 34.25%  |
| Germany      | 6         | 8.22%   |
| Spain        | 5         | 6.85%   |
| France       | 5         | 6.85%   |
| UK           | 3         | 4.11%   |
| Russia       | 3         | 4.11%   |
| Brazil       | 3         | 4.11%   |
| Australia    | 3         | 4.11%   |
| Netherlands  | 2         | 2.74%   |
| Ukraine      | 1         | 1.37%   |
| Sweden       | 1         | 1.37%   |
| South Africa | 1         | 1.37%   |
| Puerto Rico  | 1         | 1.37%   |
| Poland       | 1         | 1.37%   |
| Nigeria      | 1         | 1.37%   |
| Mexico       | 1         | 1.37%   |
| Kenya        | 1         | 1.37%   |
| Iraq         | 1         | 1.37%   |
| Indonesia    | 1         | 1.37%   |
| Hungary      | 1         | 1.37%   |
| Czechia      | 1         | 1.37%   |
| Colombia     | 1         | 1.37%   |
| Canada       | 1         | 1.37%   |
| Belgium      | 1         | 1.37%   |
| Bangladesh   | 1         | 1.37%   |
| Azerbaijan   | 1         | 1.37%   |
| Algeria      | 1         | 1.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lyon                     | 2         | 2.67%   |
| Eugene                   | 2         | 2.67%   |
| Chicago                  | 2         | 2.67%   |
| Barcelona                | 2         | 2.67%   |
| Witbank                  | 1         | 1.33%   |
| Wichita                  | 1         | 1.33%   |
| West Jordan              | 1         | 1.33%   |
| Waveland                 | 1         | 1.33%   |
| Warsaw                   | 1         | 1.33%   |
| Visalia                  | 1         | 1.33%   |
| Ternopil                 | 1         | 1.33%   |
| Stockholm                | 1         | 1.33%   |
| Sinntal                  | 1         | 1.33%   |
| Sheffield                | 1         | 1.33%   |
| Secaucus                 | 1         | 1.33%   |
| SÃ£o Paulo             | 1         | 1.33%   |
| Santo AndrГ©           | 1         | 1.33%   |
| Sannois                  | 1         | 1.33%   |
| Saint Paul               | 1         | 1.33%   |
| Regensburg               | 1         | 1.33%   |
| Reading                  | 1         | 1.33%   |
| Prague                   | 1         | 1.33%   |
| Portsmouth               | 1         | 1.33%   |
| Ponce                    | 1         | 1.33%   |
| Paris                    | 1         | 1.33%   |
| Orange Park              | 1         | 1.33%   |
| Offenbach                | 1         | 1.33%   |
| Nairobi                  | 1         | 1.33%   |
| Munich                   | 1         | 1.33%   |
| Mostoles                 | 1         | 1.33%   |
| Metairie                 | 1         | 1.33%   |
| Melbourne                | 1         | 1.33%   |
| Marietta                 | 1         | 1.33%   |
| Manchester               | 1         | 1.33%   |
| Majadahonda              | 1         | 1.33%   |
| Maggie Valley            | 1         | 1.33%   |
| Los Mochis               | 1         | 1.33%   |
| Los Angeles              | 1         | 1.33%   |
| Long Beach               | 1         | 1.33%   |
| London                   | 1         | 1.33%   |
| Lagos                    | 1         | 1.33%   |
| Lafayette                | 1         | 1.33%   |
| Kobern-Gondorf           | 1         | 1.33%   |
| Khabarovsk               | 1         | 1.33%   |
| Kazanâ€™            | 1         | 1.33%   |
| Jihlava                  | 1         | 1.33%   |
| Jaragua                  | 1         | 1.33%   |
| Houston                  | 1         | 1.33%   |
| Haarlem                  | 1         | 1.33%   |
| Fusagasuga               | 1         | 1.33%   |
| Frankfurt am Main        | 1         | 1.33%   |
| Fort Lauderdale          | 1         | 1.33%   |
| Fallbrook                | 1         | 1.33%   |
| Erbil                    | 1         | 1.33%   |
| Edmonton                 | 1         | 1.33%   |
| East Malvern             | 1         | 1.33%   |
| Dudenhofen               | 1         | 1.33%   |
| Donostia / San Sebastian | 1         | 1.33%   |
| Dhaka                    | 1         | 1.33%   |
| Dallas                   | 1         | 1.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 21     | 13.04%  |
| Samsung Electronics | 14        | 16     | 12.17%  |
| WDC                 | 13        | 16     | 11.3%   |
| Crucial             | 10        | 13     | 8.7%    |
| Toshiba             | 9         | 10     | 7.83%   |
| Unknown             | 8         | 8      | 6.96%   |
| SK Hynix            | 5         | 5      | 4.35%   |
| SanDisk             | 5         | 5      | 4.35%   |
| Kingston            | 5         | 5      | 4.35%   |
| Hitachi             | 5         | 6      | 4.35%   |
| HGST                | 4         | 4      | 3.48%   |
| Micron Technology   | 3         | 3      | 2.61%   |
| China               | 3         | 4      | 2.61%   |
| A-DATA Technology   | 3         | 3      | 2.61%   |
| KIOXIA              | 2         | 2      | 1.74%   |
| W800SH              | 1         | 1      | 0.87%   |
| SPCC                | 1         | 1      | 0.87%   |
| ROG                 | 1         | 1      | 0.87%   |
| Phison              | 1         | 1      | 0.87%   |
| Patriot             | 1         | 1      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| Intenso             | 1         | 1      | 0.87%   |
| Intel               | 1         | 1      | 0.87%   |
| FORESEE             | 1         | 1      | 0.87%   |
| Corsair             | 1         | 1      | 0.87%   |
| Apple               | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 64GB              | 3         | 2.42%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 3         | 2.42%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 2.42%   |
| HGST HTS541010A9E680 1TB                | 3         | 2.42%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 1.61%   |
| Toshiba DT01ACA100 1TB                  | 2         | 1.61%   |
| Seagate Expansion+ 2TB                  | 2         | 1.61%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.61%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.61%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.61%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.81%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.81%   |
| WDC WDBNCE2500PNC 250GB SSD             | 1         | 0.81%   |
| WDC WDBNCE0010PNC 1TB SSD               | 1         | 0.81%   |
| WDC WD800BEVS-22RST0 80GB               | 1         | 0.81%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1         | 0.81%   |
| WDC WD3200LPVX-60V0TT0 320GB            | 1         | 0.81%   |
| WDC WD3200LPVX-00V0TT0 320GB            | 1         | 0.81%   |
| WDC WD2500BPVT-00JJ5T0 250GB            | 1         | 0.81%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.81%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.81%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB    | 1         | 0.81%   |
| W800SH 512GB SSD                        | 1         | 0.81%   |
| Unknown Y016B  16GB                     | 1         | 0.81%   |
| Unknown xD/SD/M.S.                      | 1         | 0.81%   |
| Unknown SS16G  16GB                     | 1         | 0.81%   |
| Unknown SDU1  64GB                      | 1         | 0.81%   |
| Unknown MMC Card  128GB                 | 1         | 0.81%   |
| Toshiba THNSNH128G8NT 128GB SSD         | 1         | 0.81%   |
| Toshiba THNSNF128GMCS 128GB SSD         | 1         | 0.81%   |
| Toshiba Q300. 480GB SSD                 | 1         | 0.81%   |
| Toshiba MQ01ABD100V -63 1TB             | 1         | 0.81%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.81%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.81%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.81%   |
| SPCC Solid State Disk 120GB             | 1         | 0.81%   |
| SK Hynix PC601 NVMe 256GB               | 1         | 0.81%   |
| SK Hynix NVMe SSD Drive 512GB           | 1         | 0.81%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 0.81%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB       | 1         | 0.81%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.81%   |
| Seagate ST98823AS 80GB                  | 1         | 0.81%   |
| Seagate ST9500420AS 500GB               | 1         | 0.81%   |
| Seagate ST9250410AS 250GB               | 1         | 0.81%   |
| Seagate ST500NM0011 500GB               | 1         | 0.81%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.81%   |
| Seagate ST500DM002-1SB10A 500GB         | 1         | 0.81%   |
| Seagate ST4000DM004-2CV104 4TB          | 1         | 0.81%   |
| Seagate ST3500413AS 500GB               | 1         | 0.81%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 0.81%   |
| Seagate ST31000528AS 1TB                | 1         | 0.81%   |
| Seagate ST250DM000-1BD141 250GB         | 1         | 0.81%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 0.81%   |
| SanDisk SD6SF1M128G1022I 128GB SSD      | 1         | 0.81%   |
| SanDisk Extreme SSD 2TB                 | 1         | 0.81%   |
| Samsung SSD SM841N 2.5 7mm 256GB        | 1         | 0.81%   |
| Samsung SSD 980 1TB                     | 1         | 0.81%   |
| Samsung SSD 970 EVO 500GB               | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 21     | 35.71%  |
| WDC     | 9         | 11     | 21.43%  |
| Toshiba | 6         | 6      | 14.29%  |
| Hitachi | 5         | 6      | 11.9%   |
| HGST    | 4         | 4      | 9.52%   |
| Unknown | 3         | 3      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 12     | 19.57%  |
| Samsung Electronics | 8         | 9      | 17.39%  |
| SanDisk             | 5         | 5      | 10.87%  |
| Kingston            | 4         | 4      | 8.7%    |
| WDC                 | 3         | 3      | 6.52%   |
| Toshiba             | 3         | 4      | 6.52%   |
| China               | 3         | 4      | 6.52%   |
| W800SH              | 1         | 1      | 2.17%   |
| SPCC                | 1         | 1      | 2.17%   |
| Patriot             | 1         | 1      | 2.17%   |
| Micron Technology   | 1         | 1      | 2.17%   |
| LITEONIT            | 1         | 1      | 2.17%   |
| Intenso             | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| FORESEE             | 1         | 1      | 2.17%   |
| Corsair             | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 38        | 52     | 38.38%  |
| HDD     | 34        | 51     | 34.34%  |
| NVMe    | 21        | 23     | 21.21%  |
| MMC     | 4         | 4      | 4.04%   |
| Unknown | 2         | 2      | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 95     | 64.13%  |
| NVMe | 21        | 23     | 22.83%  |
| SAS  | 8         | 10     | 8.7%    |
| MMC  | 4         | 4      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 64     | 55.13%  |
| 0.51-1.0   | 27        | 30     | 34.62%  |
| 1.01-2.0   | 7         | 8      | 8.97%   |
| 3.01-4.0   | 1         | 1      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 18        | 24%     |
| 251-500        | 17        | 22.67%  |
| 501-1000       | 12        | 16%     |
| 1001-2000      | 10        | 13.33%  |
| Unknown        | 8         | 10.67%  |
| 2001-3000      | 4         | 5.33%   |
| 51-100         | 3         | 4%      |
| More than 3000 | 2         | 2.67%   |
| 21-50          | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 51-100    | 20        | 26.32%  |
| 21-50     | 18        | 23.68%  |
| 251-500   | 10        | 13.16%  |
| 101-250   | 9         | 11.84%  |
| 1-20      | 8         | 10.53%  |
| Unknown   | 8         | 10.53%  |
| 501-1000  | 2         | 2.63%   |
| 1001-2000 | 1         | 1.32%   |

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
| Intenso SSD SATAIII 480GB | 1         | 1      | 100%    |

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
| Works    | 43        | 58     | 47.78%  |
| Detected | 35        | 60     | 38.89%  |
| Malfunc  | 11        | 13     | 12.22%  |
| Failed   | 1         | 1      | 1.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 61        | 64.21%  |
| AMD                         | 9         | 9.47%   |
| Samsung Electronics         | 7         | 7.37%   |
| SK Hynix                    | 5         | 5.26%   |
| Sandisk                     | 2         | 2.11%   |
| Micron Technology           | 2         | 2.11%   |
| KIOXIA                      | 2         | 2.11%   |
| VIA Technologies            | 1         | 1.05%   |
| Realtek Semiconductor       | 1         | 1.05%   |
| Phison Electronics          | 1         | 1.05%   |
| Micron/Crucial Technology   | 1         | 1.05%   |
| Kingston Technology Company | 1         | 1.05%   |
| JMicron Technology          | 1         | 1.05%   |
| ADATA Technology            | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 3.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 3.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 3.81%   |
| SK Hynix BC511                                                                          | 3         | 2.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 2.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 2.86%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.9%    |
| Micron Non-Volatile memory controller                                                   | 2         | 1.9%    |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 1.9%    |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.9%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.95%   |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 0.95%   |
| SK Hynix Gold P31 SSD                                                                   | 1         | 0.95%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.95%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.95%   |
| Samsung Apple PCIe SSD                                                                  | 1         | 0.95%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.95%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.95%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.95%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.95%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.95%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.95%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.95%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 0.95%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 0.95%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.95%   |
| AMD FCH SATA Controller D                                                               | 1         | 0.95%   |
| AMD FCH RAID Controller                                                                 | 1         | 0.95%   |
| ADATA Non-Volatile memory controller                                                    | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 61        | 63.54%  |
| NVMe | 21        | 21.88%  |
| RAID | 7         | 7.29%   |
| IDE  | 7         | 7.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 86.3%   |
| AMD    | 10        | 13.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz              | 2         | 2.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz              | 2         | 2.74%   |
| Intel Core i7-2670QM CPU @ 2.20GHz             | 2         | 2.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 2         | 2.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 2.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 2         | 2.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 2         | 2.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz              | 2         | 2.74%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1         | 1.37%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 1         | 1.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz       | 1         | 1.37%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 1         | 1.37%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1         | 1.37%   |
| Intel Core i7-8850H CPU @ 2.60GHz              | 1         | 1.37%   |
| Intel Core i7-8809G CPU @ 3.10GHz              | 1         | 1.37%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1         | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.37%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 1         | 1.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1         | 1.37%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i7-4650U CPU @ 1.70GHz              | 1         | 1.37%   |
| Intel Core i7-4600U CPU @ 2.10GHz              | 1         | 1.37%   |
| Intel Core i7-4558U CPU @ 2.80GHz              | 1         | 1.37%   |
| Intel Core i7-3630QM CPU @ 2.40GHz             | 1         | 1.37%   |
| Intel Core i7-2720QM CPU @ 2.20GHz             | 1         | 1.37%   |
| Intel Core i7-2620M CPU @ 2.70GHz              | 1         | 1.37%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1         | 1.37%   |
| Intel Core i7-10875H CPU @ 2.30GHz             | 1         | 1.37%   |
| Intel Core i7-10870H CPU @ 2.20GHz             | 1         | 1.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.37%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1         | 1.37%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1         | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 1         | 1.37%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1         | 1.37%   |
| Intel Core i5-6400T CPU @ 2.20GHz              | 1         | 1.37%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.37%   |
| Intel Core i5-4210M CPU @ 2.60GHz              | 1         | 1.37%   |
| Intel Core i5-4200U CPU @ 1.60GHz              | 1         | 1.37%   |
| Intel Core i5-4200M CPU @ 2.50GHz              | 1         | 1.37%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 1         | 1.37%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 1.37%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz             | 1         | 1.37%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.37%   |
| Intel Core i5-10300H CPU @ 2.50GHz             | 1         | 1.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 1.37%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 1         | 1.37%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz          | 1         | 1.37%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1         | 1.37%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz           | 1         | 1.37%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz           | 1         | 1.37%   |
| Intel Core 2 CPU T7200 @ 2.00GHz               | 1         | 1.37%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 1.37%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz        | 1         | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 1.37%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1         | 1.37%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.37%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1         | 1.37%   |
| AMD Ryzen 3 3250U with Radeon Graphics         | 1         | 1.37%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 24        | 32.88%  |
| Intel Core i7           | 23        | 31.51%  |
| Other                   | 3         | 4.11%   |
| Intel Core i3           | 3         | 4.11%   |
| Intel Pentium Silver    | 2         | 2.74%   |
| Intel Core 2 Quad       | 2         | 2.74%   |
| Intel Core 2 Duo        | 2         | 2.74%   |
| AMD Ryzen 3             | 2         | 2.74%   |
| AMD FX                  | 2         | 2.74%   |
| Intel Xeon              | 1         | 1.37%   |
| Intel Pentium Dual-Core | 1         | 1.37%   |
| Intel Core M            | 1         | 1.37%   |
| Intel Core 2            | 1         | 1.37%   |
| AMD Ryzen Threadripper  | 1         | 1.37%   |
| AMD Ryzen 7             | 1         | 1.37%   |
| AMD Ryzen 5             | 1         | 1.37%   |
| AMD E1                  | 1         | 1.37%   |
| AMD A6                  | 1         | 1.37%   |
| AMD A4                  | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 32        | 43.84%  |
| 4      | 26        | 35.62%  |
| 6      | 8         | 10.96%  |
| 8      | 4         | 5.48%   |
| 12     | 1         | 1.37%   |
| 3      | 1         | 1.37%   |
| 1      | 1         | 1.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 75.34%  |
| 1      | 18        | 24.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 73        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 40%     |
| 0x206a7    | 6         | 8%      |
| 0x306c3    | 4         | 5.33%   |
| 0xa0652    | 3         | 4%      |
| 0x906e9    | 3         | 4%      |
| 0x306a9    | 3         | 4%      |
| 0x806c1    | 2         | 2.67%   |
| 0x706e5    | 2         | 2.67%   |
| 0x40651    | 2         | 2.67%   |
| 0x306d4    | 2         | 2.67%   |
| 0x1067a    | 2         | 2.67%   |
| 0x06000852 | 2         | 2.67%   |
| 0x906ed    | 1         | 1.33%   |
| 0x806ec    | 1         | 1.33%   |
| 0x806d1    | 1         | 1.33%   |
| 0x706a8    | 1         | 1.33%   |
| 0x706a1    | 1         | 1.33%   |
| 0x6fd      | 1         | 1.33%   |
| 0x6f6      | 1         | 1.33%   |
| 0x506e3    | 1         | 1.33%   |
| 0x20655    | 1         | 1.33%   |
| 0x0a201016 | 1         | 1.33%   |
| 0x08600106 | 1         | 1.33%   |
| 0x08108109 | 1         | 1.33%   |
| 0x06006705 | 1         | 1.33%   |
| 0x0600111f | 1         | 1.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 11        | 15.07%  |
| Haswell       | 9         | 12.33%  |
| SandyBridge   | 8         | 10.96%  |
| IvyBridge     | 7         | 9.59%   |
| Skylake       | 5         | 6.85%   |
| CometLake     | 4         | 5.48%   |
| Broadwell     | 4         | 5.48%   |
| Piledriver    | 3         | 4.11%   |
| Penryn        | 3         | 4.11%   |
| Icelake       | 3         | 4.11%   |
| Core          | 3         | 4.11%   |
| Zen           | 2         | 2.74%   |
| Westmere      | 2         | 2.74%   |
| TigerLake     | 2         | 2.74%   |
| Goldmont plus | 2         | 2.74%   |
| Zen+          | 1         | 1.37%   |
| Zen 3         | 1         | 1.37%   |
| Zen 2         | 1         | 1.37%   |
| Jaguar        | 1         | 1.37%   |
| Excavator     | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 53        | 55.79%  |
| Nvidia | 26        | 27.37%  |
| AMD    | 16        | 16.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 5.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 5.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 4.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 4.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 4.08%   |
| Intel HD Graphics 5500                                                        | 3         | 3.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 3.06%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 2         | 2.04%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 2         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 2.04%   |
| Intel HD Graphics 630                                                         | 2         | 2.04%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 2.04%   |
| Nvidia TU117M                                                                 | 1         | 1.02%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1         | 1.02%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 1.02%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1         | 1.02%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                         | 1         | 1.02%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 1.02%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 1         | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 1.02%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1         | 1.02%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.02%   |
| Nvidia GK106M [GeForce GTX 770M]                                              | 1         | 1.02%   |
| Nvidia GK104 [GeForce GTX 770]                                                | 1         | 1.02%   |
| Nvidia GF119M [GeForce 610M]                                                  | 1         | 1.02%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 1.02%   |
| Nvidia GF116M [GeForce GT 560M]                                               | 1         | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 1         | 1.02%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 1         | 1.02%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 1.02%   |
| Nvidia G96CM [GeForce GT 130M]                                                | 1         | 1.02%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1         | 1.02%   |
| Nvidia G86 [GeForce 8300 GS]                                                  | 1         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 1         | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 1         | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.02%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 1.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.02%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                        | 1         | 1.02%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 1.02%   |
| Intel HD Graphics 5300                                                        | 1         | 1.02%   |
| Intel HD Graphics 530                                                         | 1         | 1.02%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                 | 1         | 1.02%   |
| AMD Trinity 2 [Radeon HD 7480D]                                               | 1         | 1.02%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                      | 1         | 1.02%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 1.02%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.02%   |
| AMD RS780L [Radeon 3000]                                                      | 1         | 1.02%   |
| AMD Renoir                                                                    | 1         | 1.02%   |
| AMD Polaris 22 XT [Radeon RX Vega M GH]                                       | 1         | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 43.84%  |
| Intel + Nvidia | 15        | 20.55%  |
| 1 x AMD        | 11        | 15.07%  |
| 1 x Nvidia     | 10        | 13.7%   |
| Intel + AMD    | 4         | 5.48%   |
| AMD + Nvidia   | 1         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 65        | 89.04%  |
| Proprietary | 8         | 10.96%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 67.57%  |
| 3.01-4.0   | 6         | 8.11%   |
| 0.51-1.0   | 6         | 8.11%   |
| 1.01-2.0   | 5         | 6.76%   |
| 7.01-8.0   | 3         | 4.05%   |
| 0.01-0.5   | 3         | 4.05%   |
| 2.01-3.0   | 1         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 16.25%  |
| Samsung Electronics     | 11        | 13.75%  |
| LG Display              | 10        | 12.5%   |
| BOE                     | 9         | 11.25%  |
| Chimei Innolux          | 8         | 10%     |
| Dell                    | 5         | 6.25%   |
| Chi Mei Optoelectronics | 4         | 5%      |
| Hewlett-Packard         | 3         | 3.75%   |
| Goldstar                | 2         | 2.5%    |
| Apple                   | 2         | 2.5%    |
| AOC                     | 2         | 2.5%    |
| Vizio                   | 1         | 1.25%   |
| Toshiba                 | 1         | 1.25%   |
| Sony                    | 1         | 1.25%   |
| Sceptre                 | 1         | 1.25%   |
| Philips                 | 1         | 1.25%   |
| Panasonic               | 1         | 1.25%   |
| NEC Computers           | 1         | 1.25%   |
| Insignia                | 1         | 1.25%   |
| AUS                     | 1         | 1.25%   |
| Ancor Communications    | 1         | 1.25%   |
| Acer                    | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 2.47%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                        | 1         | 1.23%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                          | 1         | 1.23%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                       | 1         | 1.23%   |
| Sceptre LCD Monitor P30 2560x1080                                         | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch      | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.23%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch        | 1         | 1.23%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch        | 1         | 1.23%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                   | 1         | 1.23%   |
| Panasonic VVX10T025J00 MEI96A2 2560x1600 223x125mm 10.1-inch              | 1         | 1.23%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch               | 1         | 1.23%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.23%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.23%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch               | 1         | 1.23%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 1         | 1.23%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch               | 1         | 1.23%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch               | 1         | 1.23%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch                | 1         | 1.23%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch          | 1         | 1.23%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch                   | 1         | 1.23%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                    | 1         | 1.23%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch                      | 1         | 1.23%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.23%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch                         | 1         | 1.23%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                         | 1         | 1.23%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch           | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch           | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 350x190mm 15.7-inch  | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.23%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE089B 1280x800 261x163mm 12.1-inch                      | 1         | 1.23%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE07C2 1920x1080 344x193mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE07B6 1920x1080 382x215mm 17.3-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                      | 1         | 1.23%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 1         | 1.23%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                      | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 45.57%  |
| 1366x768 (WXGA)    | 18        | 22.78%  |
| 1280x800 (WXGA)    | 5         | 6.33%   |
| 1680x1050 (WSXGA+) | 3         | 3.8%    |
| 1600x900 (HD+)     | 3         | 3.8%    |
| 2560x1440 (QHD)    | 2         | 2.53%   |
| 2560x1080          | 2         | 2.53%   |
| 1440x900 (WXGA+)   | 2         | 2.53%   |
| 1280x1024 (SXGA)   | 2         | 2.53%   |
| 3840x2160 (4K)     | 1         | 1.27%   |
| 3840x1080          | 1         | 1.27%   |
| 2560x1600          | 1         | 1.27%   |
| 2160x1440          | 1         | 1.27%   |
| 1920x1200 (WUXGA)  | 1         | 1.27%   |
| 1360x768           | 1         | 1.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 33.33%  |
| 14      | 12        | 14.81%  |
| 17      | 9         | 11.11%  |
| 24      | 5         | 6.17%   |
| 23      | 4         | 4.94%   |
| 13      | 4         | 4.94%   |
| 31      | 3         | 3.7%    |
| Unknown | 3         | 3.7%    |
| 27      | 2         | 2.47%   |
| 22      | 2         | 2.47%   |
| 19      | 2         | 2.47%   |
| 18      | 2         | 2.47%   |
| 12      | 2         | 2.47%   |
| 48      | 1         | 1.23%   |
| 42      | 1         | 1.23%   |
| 34      | 1         | 1.23%   |
| 32      | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 53.16%  |
| 501-600     | 10        | 12.66%  |
| 351-400     | 9         | 11.39%  |
| 401-500     | 4         | 5.06%   |
| 201-300     | 4         | 5.06%   |
| 601-700     | 3         | 3.8%    |
| Unknown     | 3         | 3.8%    |
| 701-800     | 2         | 2.53%   |
| 1001-1500   | 1         | 1.27%   |
| 901-1000    | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 76.32%  |
| 16/10   | 11        | 14.47%  |
| Unknown | 3         | 3.95%   |
| 6/5     | 1         | 1.32%   |
| 5/4     | 1         | 1.32%   |
| 32/9    | 1         | 1.32%   |
| 21/9    | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 33.75%  |
| 81-90          | 15        | 18.75%  |
| 201-250        | 9         | 11.25%  |
| 121-130        | 7         | 8.75%   |
| 351-500        | 5         | 6.25%   |
| 141-150        | 3         | 3.75%   |
| Unknown        | 3         | 3.75%   |
| 61-70          | 2         | 2.5%    |
| 301-350        | 2         | 2.5%    |
| 151-200        | 2         | 2.5%    |
| 501-1000       | 2         | 2.5%    |
| 71-80          | 1         | 1.25%   |
| 251-300        | 1         | 1.25%   |
| 131-140        | 1         | 1.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 34.67%  |
| 101-120       | 22        | 29.33%  |
| 51-100        | 19        | 25.33%  |
| Unknown       | 3         | 4%      |
| 1-50          | 2         | 2.67%   |
| 161-240       | 2         | 2.67%   |
| More than 240 | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 83.56%  |
| 2     | 10        | 13.7%   |
| 3     | 1         | 1.37%   |
| 0     | 1         | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 39        | 31.71%  |
| Intel                             | 38        | 30.89%  |
| Qualcomm Atheros                  | 17        | 13.82%  |
| Broadcom                          | 8         | 6.5%    |
| TP-Link                           | 3         | 2.44%   |
| Qualcomm Atheros Communications   | 3         | 2.44%   |
| Broadcom Limited                  | 3         | 2.44%   |
| Samsung Electronics               | 2         | 1.63%   |
| Ralink Technology                 | 2         | 1.63%   |
| Xiaomi                            | 1         | 0.81%   |
| Ralink                            | 1         | 0.81%   |
| NetGear                           | 1         | 0.81%   |
| Microsoft                         | 1         | 0.81%   |
| Marvell Technology Group          | 1         | 0.81%   |
| Huawei Technologies               | 1         | 0.81%   |
| Ericsson Business Mobile Networks | 1         | 0.81%   |
| D-Link System                     | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 24        | 16.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 5         | 3.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 3.42%   |
| Intel Wireless 7265                                                       | 4         | 2.74%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 2.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 2.05%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 3         | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 2.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 2.05%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 2.05%   |
| Intel Wireless 3160                                                       | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 2         | 1.37%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.37%   |
| Intel Wireless 8260                                                       | 2         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                       | 2         | 1.37%   |
| Intel I211 Gigabit Network Connection                                     | 2         | 1.37%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 1         | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.68%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.68%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.68%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.68%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 0.68%   |
| Intel Wireless 8265 / 8275                                                | 1         | 0.68%   |
| Intel Wireless 7260                                                       | 1         | 0.68%   |
| Intel Wireless 3165                                                       | 1         | 0.68%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.68%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.68%   |
| Intel I210 Gigabit Network Connection                                     | 1         | 0.68%   |
| Intel Ethernet controller                                                 | 1         | 0.68%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                     | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                                     | 1         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 43.59%  |
| Qualcomm Atheros                | 13        | 16.67%  |
| Realtek Semiconductor           | 10        | 12.82%  |
| Broadcom                        | 6         | 7.69%   |
| TP-Link                         | 3         | 3.85%   |
| Qualcomm Atheros Communications | 3         | 3.85%   |
| Ralink Technology               | 2         | 2.56%   |
| Broadcom Limited                | 2         | 2.56%   |
| Ralink                          | 1         | 1.28%   |
| NetGear                         | 1         | 1.28%   |
| Microsoft                       | 1         | 1.28%   |
| Marvell Technology Group        | 1         | 1.28%   |
| D-Link System                   | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 6.41%   |
| Intel Wireless 7265                                                       | 4         | 5.13%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 5.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 3.85%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 3.85%   |
| Intel Wireless 3160                                                       | 3         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 3.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 2.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.56%   |
| Intel Wireless 8260                                                       | 2         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                       | 2         | 2.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.28%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.28%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 1.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.28%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.28%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.28%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 1.28%   |
| Intel Wireless 8265 / 8275                                                | 1         | 1.28%   |
| Intel Wireless 7260                                                       | 1         | 1.28%   |
| Intel Wireless 3165                                                       | 1         | 1.28%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.28%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.28%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.28%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 1.28%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]      | 1         | 1.28%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.28%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 1         | 1.28%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                        | 1         | 1.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.28%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 50.77%  |
| Intel                 | 16        | 24.62%  |
| Qualcomm Atheros      | 8         | 12.31%  |
| Broadcom              | 3         | 4.62%   |
| Samsung Electronics   | 2         | 3.08%   |
| Xiaomi                | 1         | 1.54%   |
| Huawei Technologies   | 1         | 1.54%   |
| Broadcom Limited      | 1         | 1.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24        | 35.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.99%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.99%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.49%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.49%   |
| Intel Ethernet controller                                         | 1         | 1.49%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.49%   |
| Huawei INE-LX2                                                    | 1         | 1.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.49%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 52.67%  |
| Ethernet | 61        | 46.56%  |
| Modem    | 1         | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 62.22%  |
| Ethernet | 34        | 37.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 47        | 64.38%  |
| 1     | 24        | 32.88%  |
| 3     | 2         | 2.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 55        | 74.32%  |
| Yes  | 19        | 25.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 50%     |
| Qualcomm Atheros Communications | 7         | 14%     |
| Realtek Semiconductor           | 4         | 8%      |
| Broadcom                        | 4         | 8%      |
| Qualcomm Atheros                | 2         | 4%      |
| Dell                            | 2         | 4%      |
| Cambridge Silicon Radio         | 2         | 4%      |
| Marvell Semiconductor           | 1         | 2%      |
| Lite-On Technology              | 1         | 2%      |
| Foxconn / Hon Hai               | 1         | 2%      |
| Apple                           | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 9         | 18%     |
| Intel Bluetooth wireless interface                  | 8         | 16%     |
| Intel AX201 Bluetooth                               | 5         | 10%     |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 8%      |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 6%      |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 4%      |
| Realtek Bluetooth Radio                             | 2         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4%      |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 2%      |
| Lite-On Bluetooth Radio                             | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2%      |
| Intel AX200 Bluetooth                               | 1         | 2%      |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2%      |
| Dell DW375 Bluetooth Module                         | 1         | 2%      |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 2%      |
| Broadcom HP Portable SoftSailing                    | 1         | 2%      |
| Broadcom HP Portable Bumble Bee                     | 1         | 2%      |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2%      |
| Apple Bluetooth Host Controller                     | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 63        | 63%     |
| Nvidia              | 18        | 18%     |
| AMD                 | 17        | 17%     |
| GN Netcom           | 1         | 1%      |
| C-Media Electronics | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 7.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 5.04%   |
| Intel Cannon Lake PCH cAVS                                                        | 5         | 4.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 4.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 3.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 3.36%   |
| Intel Sunrise Point-LP HD Audio                                                   | 4         | 3.36%   |
| Intel Haswell-ULT HD Audio Controller                                             | 4         | 3.36%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 3.36%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 3.36%   |
| Intel 8 Series HD Audio Controller                                                | 4         | 3.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 2.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 2.52%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 2.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 1.68%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.68%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 1.68%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 1.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.68%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 1.68%   |
| AMD FCH Azalia Controller                                                         | 2         | 1.68%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.84%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.84%   |
| Nvidia Audio device                                                               | 1         | 0.84%   |
| Intel USB PnP Sound Device                                                        | 1         | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1         | 0.84%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 0.84%   |
| GN Netcom Jabra Evolve 65                                                         | 1         | 0.84%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1         | 0.84%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 0.84%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 0.84%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 0.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.84%   |
| AMD Polaris 22 HDMI Audio                                                         | 1         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                          | 1         | 0.84%   |
| AMD High Definition Audio Controller                                              | 1         | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 27.27%  |
| SK Hynix            | 7         | 12.73%  |
| Unknown             | 6         | 10.91%  |
| Kingston            | 5         | 9.09%   |
| Crucial             | 5         | 9.09%   |
| Micron Technology   | 3         | 5.45%   |
| Elpida              | 3         | 5.45%   |
| Corsair             | 3         | 5.45%   |
| Ramaxel Technology  | 2         | 3.64%   |
| A-DATA Technology   | 2         | 3.64%   |
| Team                | 1         | 1.82%   |
| S                   | 1         | 1.82%   |
| Nanya Technology    | 1         | 1.82%   |
| G.Skill             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 3.39%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 3.39%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.69%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 1.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.69%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.69%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 1.69%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.69%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 1.69%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.69%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.69%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 1.69%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.69%   |
| SK Hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.69%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 1.69%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.69%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.69%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.69%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.69%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.69%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                                 | 1         | 1.69%   |
| Ramaxel RAM RMT3170MN68F9F1600 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.69%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s                  | 1         | 1.69%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s                  | 1         | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.69%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.69%   |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s          | 1         | 1.69%   |
| Kingston RAM HP26D4S9S8MH-8 8GB SODIMM DDR4 2400MT/s                | 1         | 1.69%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s                 | 1         | 1.69%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 1         | 1.69%   |
| Kingston RAM 9905469-066.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 1.69%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.69%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.69%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s               | 1         | 1.69%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s               | 1         | 1.69%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.69%   |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s               | 1         | 1.69%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s            | 1         | 1.69%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s                   | 1         | 1.69%   |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                 | 1         | 1.69%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s             | 1         | 1.69%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 1         | 1.69%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                         | 1         | 1.69%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s                | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 46.94%  |
| DDR4    | 20        | 40.82%  |
| LPDDR4  | 3         | 6.12%   |
| DDR2    | 2         | 4.08%   |
| Unknown | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 77.55%  |
| DIMM         | 9         | 18.37%  |
| Row Of Chips | 2         | 4.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 37.5%   |
| 8192  | 19        | 33.93%  |
| 2048  | 6         | 10.71%  |
| 16384 | 5         | 8.93%   |
| 32768 | 3         | 5.36%   |
| 1024  | 2         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 33.33%  |
| 2667    | 11        | 21.57%  |
| 3200    | 5         | 9.8%    |
| 1334    | 4         | 7.84%   |
| 2400    | 3         | 5.88%   |
| 3266    | 2         | 3.92%   |
| 1333    | 2         | 3.92%   |
| 4267    | 1         | 1.96%   |
| 3600    | 1         | 1.96%   |
| 2666    | 1         | 1.96%   |
| 1067    | 1         | 1.96%   |
| 667     | 1         | 1.96%   |
| 533     | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

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
| Chicony Electronics                    | 15        | 30%     |
| Microdia                               | 7         | 14%     |
| Acer                                   | 7         | 14%     |
| IMC Networks                           | 3         | 6%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6%      |
| Sunplus Innovation Technology          | 2         | 4%      |
| Ricoh                                  | 2         | 4%      |
| Realtek Semiconductor                  | 2         | 4%      |
| Luxvisions Innotech Limited            | 2         | 4%      |
| Suyin                                  | 1         | 2%      |
| Silicon Motion                         | 1         | 2%      |
| Samsung Electronics                    | 1         | 2%      |
| Quanta                                 | 1         | 2%      |
| Microsoft                              | 1         | 2%      |
| Logitech                               | 1         | 2%      |
| Apple                                  | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 5.88%   |
| Acer HD Webcam                                                             | 3         | 5.88%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.92%   |
| Microdia PC Microscope camera                                              | 2         | 3.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 3.92%   |
| Chicony HD Webcam                                                          | 2         | 3.92%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.96%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.96%   |
| Sunplus HD WebCam                                                          | 1         | 1.96%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 1.96%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.96%   |
| Ricoh Pavilion Webcam                                                      | 1         | 1.96%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.96%   |
| Quanta HP High Definition 1MP Webcam                                       | 1         | 1.96%   |
| Microsoft LifeCam Rear                                                     | 1         | 1.96%   |
| Microsoft LifeCam Front                                                    | 1         | 1.96%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.96%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.96%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.96%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.96%   |
| Logitech HD Webcam C615                                                    | 1         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.96%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.96%   |
| IMC Networks Integrated Camera                                             | 1         | 1.96%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 1.96%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.96%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.96%   |
| Chicony Integrated Camera                                                  | 1         | 1.96%   |
| Chicony HP Webcam                                                          | 1         | 1.96%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.96%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.96%   |
| Chicony HP HD Camera                                                       | 1         | 1.96%   |
| Chicony HD User Facing                                                     | 1         | 1.96%   |
| Chicony CNF8248                                                            | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.96%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.96%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.96%   |
| Acer Integrated Camera                                                     | 1         | 1.96%   |
| Acer HD Camera                                                             | 1         | 1.96%   |
| Acer EasyCamera                                                            | 1         | 1.96%   |

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
| 0     | 48        | 64.86%  |
| 1     | 17        | 22.97%  |
| 2     | 8         | 10.81%  |
| 3     | 1         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 33.33%  |
| Chipcard              | 5         | 15.15%  |
| Net/wireless          | 4         | 12.12%  |
| Graphics card         | 4         | 12.12%  |
| Storage               | 3         | 9.09%   |
| Multimedia controller | 2         | 6.06%   |
| Storage/raid          | 1         | 3.03%   |
| Modem                 | 1         | 3.03%   |
| Camera                | 1         | 3.03%   |
| Bluetooth             | 1         | 3.03%   |

