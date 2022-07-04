Parrot 4.11 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_4.11/Desktop/README.md) and [notebooks](/Dist/Parrot_4.11/Notebook/README.md).

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

Total: 105

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
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
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
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
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
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
| 5.10.0-6parrot1-amd64    | 30        | 35.29%  |
| 5.10.0-8parrot1-amd64    | 18        | 21.18%  |
| 5.14.0-9parrot1-amd64    | 12        | 14.12%  |
| 5.10.0-3parrot1-amd64    | 5         | 5.88%   |
| 5.7.0-2parrot2-amd64     | 4         | 4.71%   |
| 5.10.0-5parrot1-amd64    | 4         | 4.71%   |
| 5.16.0-12parrot1-amd64   | 3         | 3.53%   |
| 5.15.0-15parrot1-amd64   | 3         | 3.53%   |
| 5.14.0-2parrot1-amd64    | 3         | 3.53%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.18%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.18%   |
| Unknown                  | 1         | 1.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 58        | 68.24%  |
| 5.14.0  | 15        | 17.65%  |
| 5.7.0   | 4         | 4.71%   |
| 5.16.0  | 3         | 3.53%   |
| 5.15.0  | 3         | 3.53%   |
| 5.6.0   | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 58        | 68.24%  |
| 5.14    | 15        | 17.65%  |
| 5.7     | 4         | 4.71%   |
| 5.16    | 3         | 3.53%   |
| 5.15    | 3         | 3.53%   |
| 5.6     | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 48        | 56.47%  |
| KDE5    | 22        | 25.88%  |
| KDE     | 7         | 8.24%   |
| Unknown | 4         | 4.71%   |
| XFCE    | 3         | 3.53%   |
| LXDE    | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 84        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 34        | 39.53%  |
| Unknown | 27        | 31.4%   |
| TDM     | 23        | 26.74%  |
| SDDM    | 2         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 40        | 47.62%  |
| fr_FR   | 7         | 8.33%   |
| en_GB   | 6         | 7.14%   |
| pt_BR   | 5         | 5.95%   |
| ru_RU   | 4         | 4.76%   |
| en_AU   | 4         | 4.76%   |
| de_DE   | 4         | 4.76%   |
| Unknown | 3         | 3.57%   |
| es_ES   | 2         | 2.38%   |
| cs_CZ   | 2         | 2.38%   |
| ru_UA   | 1         | 1.19%   |
| pl_PL   | 1         | 1.19%   |
| nl_BE   | 1         | 1.19%   |
| id_ID   | 1         | 1.19%   |
| es_CO   | 1         | 1.19%   |
| en_NG   | 1         | 1.19%   |
| an_ES   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 51        | 59.3%   |
| EFI  | 35        | 40.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 66        | 78.57%  |
| Ext4    | 12        | 14.29%  |
| Xfs     | 5         | 5.95%   |
| Overlay | 1         | 1.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 44.71%  |
| Unknown | 29        | 34.12%  |
| MBR     | 18        | 21.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 78.82%  |
| Yes       | 18        | 21.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 59.52%  |
| Yes       | 34        | 40.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 20.24%  |
| ASUSTek Computer    | 14        | 16.67%  |
| Dell                | 12        | 14.29%  |
| Lenovo              | 8         | 9.52%   |
| MSI                 | 6         | 7.14%   |
| Acer                | 5         | 5.95%   |
| Samsung Electronics | 2         | 2.38%   |
| Apple               | 2         | 2.38%   |
| Alienware           | 2         | 2.38%   |
| ZOTAC               | 1         | 1.19%   |
| Wortmann AG         | 1         | 1.19%   |
| Wistron             | 1         | 1.19%   |
| Toxic               | 1         | 1.19%   |
| Toshiba             | 1         | 1.19%   |
| Timi                | 1         | 1.19%   |
| Sony                | 1         | 1.19%   |
| Positivo            | 1         | 1.19%   |
| Microsoft           | 1         | 1.19%   |
| Intel               | 1         | 1.19%   |
| GPU Company         | 1         | 1.19%   |
| Gigabyte Technology | 1         | 1.19%   |
| Gateway             | 1         | 1.19%   |
| Fujitsu             | 1         | 1.19%   |
| Eluktronics         | 1         | 1.19%   |
| ASRock              | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP ProBook 650 G1                        | 2         | 2.38%   |
| ASUS Q524UQ                              | 2         | 2.38%   |
| Wortmann AG TERRA_MOBILE_1542            | 1         | 1.19%   |
| Wistron FMVDD2A0H0                       | 1         | 1.19%   |
| Toxic GM7MQ8P                            | 1         | 1.19%   |
| Toshiba Satellite L655                   | 1         | 1.19%   |
| Timi TM1613                              | 1         | 1.19%   |
| Sony SVP1321L1EBI                        | 1         | 1.19%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 1.19%   |
| Samsung 300E4C/300E5C/300E7C             | 1         | 1.19%   |
| Positivo Q232A                           | 1         | 1.19%   |
| MSI MS-7529                              | 1         | 1.19%   |
| MSI GT60 2OC/2OD                         | 1         | 1.19%   |
| MSI GS66 Stealth 10UG                    | 1         | 1.19%   |
| MSI GE75 Raider 10SF                     | 1         | 1.19%   |
| MSI GE73 Raider RGB 8RE                  | 1         | 1.19%   |
| MSI GE63 Raider RGB 8RE                  | 1         | 1.19%   |
| Microsoft Surface Pro 3                  | 1         | 1.19%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.19%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 1.19%   |
| Lenovo ThinkPad X260 20F5S5QT00          | 1         | 1.19%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 1.19%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003AMC | 1         | 1.19%   |
| Lenovo ThinkPad E15 20RD0086UE           | 1         | 1.19%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 1         | 1.19%   |
| Lenovo B50-80 80EW                       | 1         | 1.19%   |
| Intel NUC8i7HVK                          | 1         | 1.19%   |
| HP ZBook 15 G5                           | 1         | 1.19%   |
| HP Pavilion Notebook                     | 1         | 1.19%   |
| HP Pavilion dv7                          | 1         | 1.19%   |
| HP Pavilion dv6700                       | 1         | 1.19%   |
| HP Pavilion dv6                          | 1         | 1.19%   |
| HP Pavilion dv4                          | 1         | 1.19%   |
| HP Laptop 15s-eq1xxx                     | 1         | 1.19%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.19%   |
| HP HDX PREMIUM SERIES                    | 1         | 1.19%   |
| HP ENVY x360 Convertible 15-es0xxx       | 1         | 1.19%   |
| HP EliteBook 8470p                       | 1         | 1.19%   |
| HP EliteBook 840 G8 Notebook PC          | 1         | 1.19%   |
| HP Compaq Pro 6305 MT                    | 1         | 1.19%   |
| HP All-in-One 24-f0xx                    | 1         | 1.19%   |
| HP 250 G7 Notebook PC                    | 1         | 1.19%   |
| GPU Company GWTN141-10                   | 1         | 1.19%   |
| Gigabyte A320M-S2H                       | 1         | 1.19%   |
| Gateway MP8708                           | 1         | 1.19%   |
| Fujitsu LIFEBOOK T731                    | 1         | 1.19%   |
| Eluktronics MAG-15u                      | 1         | 1.19%   |
| Dell XPS 8930                            | 1         | 1.19%   |
| Dell Precision M4600                     | 1         | 1.19%   |
| Dell OptiPlex 7070                       | 1         | 1.19%   |
| Dell OptiPlex 3010                       | 1         | 1.19%   |
| Dell Latitude E7440                      | 1         | 1.19%   |
| Dell Latitude E6420                      | 1         | 1.19%   |
| Dell Latitude E6410                      | 1         | 1.19%   |
| Dell Inspiron 7501                       | 1         | 1.19%   |
| Dell Inspiron 5593                       | 1         | 1.19%   |
| Dell Inspiron 5558                       | 1         | 1.19%   |
| Dell Inspiron 5420                       | 1         | 1.19%   |
| Dell Inspiron 15 5510                    | 1         | 1.19%   |
| ASUS X75VB                               | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP Pavilion            | 5         | 5.95%   |
| Dell Inspiron          | 5         | 5.95%   |
| Lenovo ThinkPad        | 4         | 4.76%   |
| Dell Latitude          | 3         | 3.57%   |
| HP ProBook             | 2         | 2.38%   |
| HP Laptop              | 2         | 2.38%   |
| HP EliteBook           | 2         | 2.38%   |
| Dell OptiPlex          | 2         | 2.38%   |
| ASUS Q524UQ            | 2         | 2.38%   |
| Acer Aspire            | 2         | 2.38%   |
| Wortmann AG TERRA      | 1         | 1.19%   |
| Wistron FMVDD2A0H0     | 1         | 1.19%   |
| Toxic GM7MQ8P          | 1         | 1.19%   |
| Toshiba Satellite      | 1         | 1.19%   |
| Timi TM1613            | 1         | 1.19%   |
| Sony SVP1321L1EBI      | 1         | 1.19%   |
| Samsung 350V5C         | 1         | 1.19%   |
| Samsung 300E4C         | 1         | 1.19%   |
| Positivo Q232A         | 1         | 1.19%   |
| MSI MS-7529            | 1         | 1.19%   |
| MSI GT60               | 1         | 1.19%   |
| MSI GS66               | 1         | 1.19%   |
| MSI GE75               | 1         | 1.19%   |
| MSI GE73               | 1         | 1.19%   |
| MSI GE63               | 1         | 1.19%   |
| Microsoft Surface      | 1         | 1.19%   |
| Lenovo Yoga            | 1         | 1.19%   |
| Lenovo Y520-15IKBN     | 1         | 1.19%   |
| Lenovo IdeaPad         | 1         | 1.19%   |
| Lenovo B50-80          | 1         | 1.19%   |
| Intel NUC8i7HVK        | 1         | 1.19%   |
| HP ZBook               | 1         | 1.19%   |
| HP HDX                 | 1         | 1.19%   |
| HP ENVY                | 1         | 1.19%   |
| HP Compaq              | 1         | 1.19%   |
| HP All-in-One          | 1         | 1.19%   |
| HP 250                 | 1         | 1.19%   |
| GPU Company GWTN141-10 | 1         | 1.19%   |
| Gigabyte A320M-S2H     | 1         | 1.19%   |
| Gateway MP8708         | 1         | 1.19%   |
| Fujitsu LIFEBOOK       | 1         | 1.19%   |
| Eluktronics MAG-15u    | 1         | 1.19%   |
| Dell XPS               | 1         | 1.19%   |
| Dell Precision         | 1         | 1.19%   |
| ASUS X75VB             | 1         | 1.19%   |
| ASUS X450EA            | 1         | 1.19%   |
| ASUS VivoBook          | 1         | 1.19%   |
| ASUS ROG               | 1         | 1.19%   |
| ASUS PRIME             | 1         | 1.19%   |
| ASUS P8H67-M           | 1         | 1.19%   |
| ASUS M5A99X            | 1         | 1.19%   |
| ASUS M5A78L-M          | 1         | 1.19%   |
| ASUS KJ250AA-ABE       | 1         | 1.19%   |
| ASUS G74Sx             | 1         | 1.19%   |
| ASUS F2A85-M           | 1         | 1.19%   |
| ASUS Basic             | 1         | 1.19%   |
| ASRock Z87             | 1         | 1.19%   |
| Apple MacBookPro8      | 1         | 1.19%   |
| Apple MacBookPro11     | 1         | 1.19%   |
| Alienware X51          | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 11        | 13.1%   |
| 2013 | 9         | 10.71%  |
| 2011 | 9         | 10.71%  |
| 2020 | 8         | 9.52%   |
| 2016 | 8         | 9.52%   |
| 2018 | 7         | 8.33%   |
| 2021 | 5         | 5.95%   |
| 2012 | 5         | 5.95%   |
| 2015 | 4         | 4.76%   |
| 2010 | 4         | 4.76%   |
| 2017 | 3         | 3.57%   |
| 2014 | 3         | 3.57%   |
| 2008 | 3         | 3.57%   |
| 2007 | 3         | 3.57%   |
| 2009 | 1         | 1.19%   |
| 2006 | 1         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 60        | 71.43%  |
| Desktop     | 20        | 23.81%  |
| Tablet      | 1         | 1.19%   |
| Convertible | 1         | 1.19%   |
| Mini pc     | 1         | 1.19%   |
| All in one  | 1         | 1.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 84        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 23        | 27.38%  |
| 8.01-16.0   | 18        | 21.43%  |
| 16.01-24.0  | 17        | 20.24%  |
| 3.01-4.0    | 12        | 14.29%  |
| 32.01-64.0  | 4         | 4.76%   |
| 1.01-2.0    | 4         | 4.76%   |
| 64.01-256.0 | 3         | 3.57%   |
| 24.01-32.0  | 2         | 2.38%   |
| 2.01-3.0    | 1         | 1.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 33        | 38.37%  |
| 2.01-3.0  | 25        | 29.07%  |
| 3.01-4.0  | 13        | 15.12%  |
| 4.01-8.0  | 11        | 12.79%  |
| 8.01-16.0 | 2         | 2.33%   |
| 0.51-1.0  | 2         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 45        | 52.94%  |
| 2      | 27        | 31.76%  |
| 3      | 10        | 11.76%  |
| 4      | 2         | 2.35%   |
| 5      | 1         | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 66.67%  |
| Yes       | 28        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 80.95%  |
| No        | 16        | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 91.76%  |
| No        | 7         | 8.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 67.86%  |
| No        | 27        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 26        | 30.95%  |
| Germany      | 8         | 9.52%   |
| France       | 6         | 7.14%   |
| Spain        | 5         | 5.95%   |
| Brazil       | 5         | 5.95%   |
| UK           | 3         | 3.57%   |
| Russia       | 3         | 3.57%   |
| Netherlands  | 3         | 3.57%   |
| Czechia      | 3         | 3.57%   |
| Australia    | 3         | 3.57%   |
| Iraq         | 2         | 2.38%   |
| Vietnam      | 1         | 1.19%   |
| Ukraine      | 1         | 1.19%   |
| Sweden       | 1         | 1.19%   |
| South Africa | 1         | 1.19%   |
| Puerto Rico  | 1         | 1.19%   |
| Poland       | 1         | 1.19%   |
| Nigeria      | 1         | 1.19%   |
| Mexico       | 1         | 1.19%   |
| Kenya        | 1         | 1.19%   |
| Indonesia    | 1         | 1.19%   |
| Hungary      | 1         | 1.19%   |
| Colombia     | 1         | 1.19%   |
| Canada       | 1         | 1.19%   |
| Belgium      | 1         | 1.19%   |
| Bangladesh   | 1         | 1.19%   |
| Azerbaijan   | 1         | 1.19%   |
| Algeria      | 1         | 1.19%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Melbourne             | 2         | 2.33%   |
| Lyon                  | 2         | 2.33%   |
| Khabarovsk            | 2         | 2.33%   |
| Eugene                | 2         | 2.33%   |
| Dallas                | 2         | 2.33%   |
| Chicago               | 2         | 2.33%   |
| Barcelona             | 2         | 2.33%   |
| West Jordan           | 1         | 1.16%   |
| Warsaw                | 1         | 1.16%   |
| Waren                 | 1         | 1.16%   |
| Visalia               | 1         | 1.16%   |
| Veitsbronn            | 1         | 1.16%   |
| Uherské Hradiště   | 1         | 1.16%   |
| Tangerang             | 1         | 1.16%   |
| Sydney                | 1         | 1.16%   |
| Stockholm             | 1         | 1.16%   |
| Sinntal               | 1         | 1.16%   |
| Shelbyville           | 1         | 1.16%   |
| Secaucus              | 1         | 1.16%   |
| Sao Paulo             | 1         | 1.16%   |
| Santo André          | 1         | 1.16%   |
| Santa Maria           | 1         | 1.16%   |
| Sant Boi de Llobregat | 1         | 1.16%   |
| Sannois               | 1         | 1.16%   |
| Saint Paul            | 1         | 1.16%   |
| Rotterdam             | 1         | 1.16%   |
| Rialma                | 1         | 1.16%   |
| Reus                  | 1         | 1.16%   |
| Regensburg            | 1         | 1.16%   |
| Reading               | 1         | 1.16%   |
| Pretoria              | 1         | 1.16%   |
| Prague                | 1         | 1.16%   |
| Portsmouth            | 1         | 1.16%   |
| Ponce                 | 1         | 1.16%   |
| Paris                 | 1         | 1.16%   |
| Orange Park           | 1         | 1.16%   |
| Omaha                 | 1         | 1.16%   |
| New Orleans           | 1         | 1.16%   |
| Nam Định           | 1         | 1.16%   |
| Nairobi               | 1         | 1.16%   |
| Munich                | 1         | 1.16%   |
| Marietta              | 1         | 1.16%   |
| Manaus                | 1         | 1.16%   |
| Maggie Valley         | 1         | 1.16%   |
| Los Mochis            | 1         | 1.16%   |
| Los Angeles           | 1         | 1.16%   |
| Long Beach            | 1         | 1.16%   |
| London                | 1         | 1.16%   |
| Lancaster             | 1         | 1.16%   |
| Lafayette             | 1         | 1.16%   |
| Kyiv                  | 1         | 1.16%   |
| Kano                  | 1         | 1.16%   |
| Jihlava               | 1         | 1.16%   |
| Houston               | 1         | 1.16%   |
| Hanau                 | 1         | 1.16%   |
| Guignicourt           | 1         | 1.16%   |
| Fusagasuga            | 1         | 1.16%   |
| Fort Lauderdale       | 1         | 1.16%   |
| Fallbrook             | 1         | 1.16%   |
| Erbil                 | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 14.5%   |
| WDC                 | 17        | 19     | 12.98%  |
| Seagate             | 16        | 22     | 12.21%  |
| Crucial             | 10        | 13     | 7.63%   |
| Unknown             | 9         | 9      | 6.87%   |
| Toshiba             | 9         | 10     | 6.87%   |
| Kingston            | 7         | 7      | 5.34%   |
| SanDisk             | 6         | 6      | 4.58%   |
| Hitachi             | 6         | 7      | 4.58%   |
| SK hynix            | 5         | 5      | 3.82%   |
| HGST                | 4         | 4      | 3.05%   |
| Micron Technology   | 3         | 3      | 2.29%   |
| China               | 3         | 4      | 2.29%   |
| A-DATA Technology   | 3         | 3      | 2.29%   |
| KIOXIA              | 2         | 2      | 1.53%   |
| W800SH              | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| ROG                 | 1         | 1      | 0.76%   |
| Phison              | 1         | 1      | 0.76%   |
| Patriot             | 1         | 1      | 0.76%   |
| LITEONIT            | 1         | 1      | 0.76%   |
| Lexar               | 1         | 1      | 0.76%   |
| Intenso             | 1         | 1      | 0.76%   |
| Intel               | 1         | 1      | 0.76%   |
| FORESEE             | 1         | 1      | 0.76%   |
| Corsair             | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 128GB             | 3         | 2.13%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 3         | 2.13%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 2.13%   |
| Samsung SSD 860 EVO 500GB               | 3         | 2.13%   |
| HGST HTS541010A9E680 1TB                | 3         | 2.13%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 1.42%   |
| Toshiba DT01ACA100 1TB                  | 2         | 1.42%   |
| Seagate Expansion 1TB                   | 2         | 1.42%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.42%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.42%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.71%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.71%   |
| WDC WDBNCE2500PNC 250GB SSD             | 1         | 0.71%   |
| WDC WDBNCE0010PNC 1TB SSD               | 1         | 0.71%   |
| WDC WD800BEVS-22RST0 80GB               | 1         | 0.71%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1         | 0.71%   |
| WDC WD3200LPVX-60V0TT0 320GB            | 1         | 0.71%   |
| WDC WD3200LPVX-00V0TT0 320GB            | 1         | 0.71%   |
| WDC WD2500BPVT-00JJ5T0 250GB            | 1         | 0.71%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.71%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.71%   |
| WDC WD10EZRX-00L4HB0 1TB                | 1         | 0.71%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.71%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 1         | 0.71%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB    | 1         | 0.71%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB    | 1         | 0.71%   |
| W800SH 512GB SSD                        | 1         | 0.71%   |
| Unknown Y016B  16GB                     | 1         | 0.71%   |
| Unknown xD/SD/M.S.                      | 1         | 0.71%   |
| Unknown SS16G  16GB                     | 1         | 0.71%   |
| Unknown SS08G  8GB                      | 1         | 0.71%   |
| Unknown SDU1  64GB                      | 1         | 0.71%   |
| Unknown MMC Card  128GB                 | 1         | 0.71%   |
| Toshiba THNSNH128G8NT 128GB SSD         | 1         | 0.71%   |
| Toshiba THNSNF128GMCS 128GB SSD         | 1         | 0.71%   |
| Toshiba Q300. 480GB SSD                 | 1         | 0.71%   |
| Toshiba MQ01ABD100V -63 1TB             | 1         | 0.71%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.71%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.71%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.71%   |
| SPCC Solid State Disk 120GB             | 1         | 0.71%   |
| SK hynix PC601 NVMe 256GB               | 1         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB           | 1         | 0.71%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 0.71%   |
| SK hynix HFM256GDJTNI-82A0A 256GB       | 1         | 0.71%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.71%   |
| Seagate ST98823AS 80GB                  | 1         | 0.71%   |
| Seagate ST9500420AS 500GB               | 1         | 0.71%   |
| Seagate ST9250410AS 250GB               | 1         | 0.71%   |
| Seagate ST500NM0011 500GB               | 1         | 0.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.71%   |
| Seagate ST500LM000-SSHD-8GB             | 1         | 0.71%   |
| Seagate ST500DM002-1SB10A 500GB         | 1         | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB          | 1         | 0.71%   |
| Seagate ST3500413AS 500GB               | 1         | 0.71%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 0.71%   |
| Seagate ST31000528AS 1TB                | 1         | 0.71%   |
| Seagate ST250DM000-1BD141 250GB         | 1         | 0.71%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 22     | 33.33%  |
| WDC                 | 11        | 12     | 22.92%  |
| Toshiba             | 6         | 6      | 12.5%   |
| Hitachi             | 6         | 7      | 12.5%   |
| HGST                | 4         | 4      | 8.33%   |
| Unknown             | 3         | 3      | 6.25%   |
| Samsung Electronics | 2         | 3      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 18.75%  |
| Crucial             | 9         | 12     | 18.75%  |
| SanDisk             | 5         | 5      | 10.42%  |
| Kingston            | 5         | 5      | 10.42%  |
| WDC                 | 3         | 3      | 6.25%   |
| Toshiba             | 3         | 4      | 6.25%   |
| China               | 3         | 4      | 6.25%   |
| W800SH              | 1         | 1      | 2.08%   |
| SPCC                | 1         | 1      | 2.08%   |
| Patriot             | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 1      | 2.08%   |
| LITEONIT            | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| FORESEE             | 1         | 1      | 2.08%   |
| Corsair             | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |
| A-DATA Technology   | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 40        | 54     | 35.4%   |
| HDD     | 39        | 57     | 34.51%  |
| NVMe    | 27        | 29     | 23.89%  |
| MMC     | 5         | 6      | 4.42%   |
| Unknown | 2         | 2      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 64        | 103    | 61.54%  |
| NVMe | 27        | 29     | 25.96%  |
| SAS  | 8         | 10     | 7.69%   |
| MMC  | 5         | 6      | 4.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 70     | 55.29%  |
| 0.51-1.0   | 31        | 34     | 36.47%  |
| 1.01-2.0   | 6         | 6      | 7.06%   |
| 3.01-4.0   | 1         | 1      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 22        | 25.58%  |
| 101-250        | 21        | 24.42%  |
| 501-1000       | 12        | 13.95%  |
| 1001-2000      | 11        | 12.79%  |
| Unknown        | 8         | 9.3%    |
| 51-100         | 5         | 5.81%   |
| 2001-3000      | 4         | 4.65%   |
| More than 3000 | 2         | 2.33%   |
| 21-50          | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 21        | 24.14%  |
| 51-100    | 20        | 22.99%  |
| 101-250   | 14        | 16.09%  |
| 251-500   | 10        | 11.49%  |
| 1-20      | 10        | 11.49%  |
| Unknown   | 8         | 9.2%    |
| 501-1000  | 3         | 3.45%   |
| 1001-2000 | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD10EZRX-00L4HB0 1TB                            | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.67%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 6.67%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 6.67%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 6.67%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 6.67%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 6.67%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 6.67%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 1         | 1      | 6.67%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 6.67%   |
| Hitachi HUA722020ALA331 2TB                         | 1         | 1      | 6.67%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 6.67%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 35.71%  |
| SanDisk             | 2         | 2      | 14.29%  |
| Hitachi             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 55.56%  |
| Hitachi | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 64.29%  |
| SSD  | 4         | 4      | 28.57%  |
| NVMe | 1         | 1      | 7.14%   |

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
| Works    | 50        | 67     | 48.54%  |
| Detected | 39        | 65     | 37.86%  |
| Malfunc  | 13        | 15     | 12.62%  |
| Failed   | 1         | 1      | 0.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 67        | 62.04%  |
| AMD                         | 10        | 9.26%   |
| Samsung Electronics         | 9         | 8.33%   |
| SK hynix                    | 5         | 4.63%   |
| SanDisk                     | 4         | 3.7%    |
| Micron Technology           | 2         | 1.85%   |
| KIOXIA                      | 2         | 1.85%   |
| Kingston Technology Company | 2         | 1.85%   |
| VIA Technologies            | 1         | 0.93%   |
| Silicon Motion              | 1         | 0.93%   |
| Realtek Semiconductor       | 1         | 0.93%   |
| Phison Electronics          | 1         | 0.93%   |
| Micron/Crucial Technology   | 1         | 0.93%   |
| JMicron Technology          | 1         | 0.93%   |
| ADATA Technology            | 1         | 0.93%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 5%      |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 4.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 3.33%   |
| SK hynix BC511                                                                          | 3         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 2.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 1.67%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.67%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.67%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 1.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.67%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.67%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.83%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 0.83%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.83%   |
| Samsung Apple PCIe SSD                                                                  | 1         | 0.83%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.83%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.83%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 0.83%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.83%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.83%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.83%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 0.83%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 0.83%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 66        | 60.55%  |
| NVMe | 27        | 24.77%  |
| IDE  | 9         | 8.26%   |
| RAID | 7         | 6.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 86.9%   |
| AMD    | 11        | 13.1%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 3.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 2.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.38%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 2.38%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 2.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.38%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.38%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1         | 1.19%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.19%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.19%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.19%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.19%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 1.19%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1         | 1.19%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i7-8809G CPU @ 3.10GHz           | 1         | 1.19%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.19%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.19%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.19%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.19%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.19%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.19%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.19%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.19%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.19%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.19%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.19%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.19%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 1         | 1.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.19%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.19%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.19%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.19%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.19%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.19%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.19%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 1.19%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.19%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.19%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.19%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.19%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 1.19%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.19%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.19%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1         | 1.19%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.19%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.19%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.19%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 25        | 29.76%  |
| Intel Core i5           | 25        | 29.76%  |
| Other                   | 6         | 7.14%   |
| Intel Core i3           | 3         | 3.57%   |
| Intel Core 2 Duo        | 3         | 3.57%   |
| Intel Pentium Silver    | 2         | 2.38%   |
| Intel Core 2 Quad       | 2         | 2.38%   |
| AMD Ryzen 3             | 2         | 2.38%   |
| AMD FX                  | 2         | 2.38%   |
| Intel Xeon              | 1         | 1.19%   |
| Intel Pentium Dual-Core | 1         | 1.19%   |
| Intel Pentium Dual      | 1         | 1.19%   |
| Intel Pentium           | 1         | 1.19%   |
| Intel Core M            | 1         | 1.19%   |
| Intel Core 2            | 1         | 1.19%   |
| Intel Atom              | 1         | 1.19%   |
| AMD Ryzen Threadripper  | 1         | 1.19%   |
| AMD Ryzen 7             | 1         | 1.19%   |
| AMD Ryzen 5             | 1         | 1.19%   |
| AMD E1                  | 1         | 1.19%   |
| AMD A8                  | 1         | 1.19%   |
| AMD A6                  | 1         | 1.19%   |
| AMD A4                  | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 44.05%  |
| 4      | 32        | 38.1%   |
| 6      | 8         | 9.52%   |
| 8      | 4         | 4.76%   |
| 12     | 1         | 1.19%   |
| 3      | 1         | 1.19%   |
| 1      | 1         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 73.81%  |
| 1      | 22        | 26.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 84        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 38.37%  |
| 0x206a7    | 6         | 6.98%   |
| 0x306c3    | 5         | 5.81%   |
| 0x806c1    | 4         | 4.65%   |
| 0xa0652    | 3         | 3.49%   |
| 0x906e9    | 3         | 3.49%   |
| 0x806ec    | 3         | 3.49%   |
| 0x306a9    | 3         | 3.49%   |
| 0x1067a    | 3         | 3.49%   |
| 0x706e5    | 2         | 2.33%   |
| 0x40651    | 2         | 2.33%   |
| 0x306d4    | 2         | 2.33%   |
| 0x06000852 | 2         | 2.33%   |
| 0x906ed    | 1         | 1.16%   |
| 0x806d1    | 1         | 1.16%   |
| 0x806c2    | 1         | 1.16%   |
| 0x706a8    | 1         | 1.16%   |
| 0x706a1    | 1         | 1.16%   |
| 0x6fd      | 1         | 1.16%   |
| 0x6f6      | 1         | 1.16%   |
| 0x506e3    | 1         | 1.16%   |
| 0x406e3    | 1         | 1.16%   |
| 0x20655    | 1         | 1.16%   |
| 0x0a201016 | 1         | 1.16%   |
| 0x08600106 | 1         | 1.16%   |
| 0x08108109 | 1         | 1.16%   |
| 0x06006705 | 1         | 1.16%   |
| 0x0600111f | 1         | 1.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 13        | 15.48%  |
| Haswell       | 10        | 11.9%   |
| SandyBridge   | 8         | 9.52%   |
| IvyBridge     | 7         | 8.33%   |
| Skylake       | 6         | 7.14%   |
| TigerLake     | 5         | 5.95%   |
| Piledriver    | 4         | 4.76%   |
| Penryn        | 4         | 4.76%   |
| Core          | 4         | 4.76%   |
| CometLake     | 4         | 4.76%   |
| Broadwell     | 4         | 4.76%   |
| IceLake       | 3         | 3.57%   |
| Zen           | 2         | 2.38%   |
| Westmere      | 2         | 2.38%   |
| Goldmont plus | 2         | 2.38%   |
| Zen+          | 1         | 1.19%   |
| Zen 3         | 1         | 1.19%   |
| Zen 2         | 1         | 1.19%   |
| Silvermont    | 1         | 1.19%   |
| Jaguar        | 1         | 1.19%   |
| Excavator     | 1         | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 62        | 56.88%  |
| Nvidia | 29        | 26.61%  |
| AMD    | 18        | 16.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 4.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.57%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.68%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.68%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.79%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.79%   |
| Intel HD Graphics 630                                                                    | 2         | 1.79%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.79%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.79%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.89%   |
| Nvidia TU117M                                                                            | 1         | 0.89%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.89%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.89%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.89%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 0.89%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.89%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.89%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.89%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.89%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.89%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 0.89%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.89%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.89%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.89%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.89%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.89%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 0.89%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 0.89%   |
| Nvidia G86 [GeForce 8300 GS]                                                             | 1         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.89%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.89%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.89%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.89%   |
| Intel HD Graphics 530                                                                    | 1         | 0.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.89%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.89%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1         | 0.89%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.89%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 38        | 45.24%  |
| Intel + Nvidia | 17        | 20.24%  |
| 1 x AMD        | 12        | 14.29%  |
| 1 x Nvidia     | 11        | 13.1%   |
| Intel + AMD    | 5         | 5.95%   |
| AMD + Nvidia   | 1         | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 75        | 89.29%  |
| Proprietary | 9         | 10.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 69.41%  |
| 0.51-1.0   | 7         | 8.24%   |
| 3.01-4.0   | 6         | 7.06%   |
| 1.01-2.0   | 6         | 7.06%   |
| 7.01-8.0   | 3         | 3.53%   |
| 0.01-0.5   | 3         | 3.53%   |
| 2.01-3.0   | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 14.58%  |
| Samsung Electronics     | 12        | 12.5%   |
| LG Display              | 11        | 11.46%  |
| BOE                     | 11        | 11.46%  |
| Chimei Innolux          | 9         | 9.38%   |
| Dell                    | 7         | 7.29%   |
| Hewlett-Packard         | 4         | 4.17%   |
| Chi Mei Optoelectronics | 4         | 4.17%   |
| Goldstar                | 3         | 3.13%   |
| Philips                 | 2         | 2.08%   |
| Apple                   | 2         | 2.08%   |
| AOC                     | 2         | 2.08%   |
| Vizio                   | 1         | 1.04%   |
| Toshiba                 | 1         | 1.04%   |
| STA                     | 1         | 1.04%   |
| Sony                    | 1         | 1.04%   |
| Sharp                   | 1         | 1.04%   |
| Sceptre Tech            | 1         | 1.04%   |
| Sceptre                 | 1         | 1.04%   |
| Panasonic               | 1         | 1.04%   |
| NEC Computers           | 1         | 1.04%   |
| Lenovo                  | 1         | 1.04%   |
| Insignia                | 1         | 1.04%   |
| BenQ                    | 1         | 1.04%   |
| AUS                     | 1         | 1.04%   |
| Ancor Communications    | 1         | 1.04%   |
| Acer                    | 1         | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 2         | 2.06%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                        | 1         | 1.03%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                          | 1         | 1.03%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                        | 1         | 1.03%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                       | 1         | 1.03%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                   | 1         | 1.03%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch            | 1         | 1.03%   |
| Sceptre LCD Monitor P30 2560x1080                                         | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM03FE 1280x720                          | 1         | 1.03%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch        | 1         | 1.03%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch        | 1         | 1.03%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                  | 1         | 1.03%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                   | 1         | 1.03%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch               | 1         | 1.03%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch               | 1         | 1.03%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.03%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD0683 1920x1080 344x194mm 15.5-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.03%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch               | 1         | 1.03%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.03%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch               | 1         | 1.03%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 1         | 1.03%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 698x393mm 31.5-inch                  | 1         | 1.03%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch               | 1         | 1.03%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch               | 1         | 1.03%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch                | 1         | 1.03%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch          | 1         | 1.03%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch               | 1         | 1.03%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch                      | 1         | 1.03%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch                   | 1         | 1.03%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                    | 1         | 1.03%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch                      | 1         | 1.03%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.03%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch                         | 1         | 1.03%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                         | 1         | 1.03%   |
| Dell E2318H DELF092 1920x1080 509x286mm 23.0-inch                         | 1         | 1.03%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                         | 1         | 1.03%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch           | 1         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 381x214mm 17.2-inch | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 47.83%  |
| 1366x768 (WXGA)    | 19        | 20.65%  |
| 1280x800 (WXGA)    | 5         | 5.43%   |
| 1280x1024 (SXGA)   | 4         | 4.35%   |
| 2560x1440 (QHD)    | 3         | 3.26%   |
| 1680x1050 (WSXGA+) | 3         | 3.26%   |
| 1600x900 (HD+)     | 3         | 3.26%   |
| 2560x1080          | 2         | 2.17%   |
| 1440x900 (WXGA+)   | 2         | 2.17%   |
| 3840x2160 (4K)     | 1         | 1.09%   |
| 3840x1080          | 1         | 1.09%   |
| 2560x1600          | 1         | 1.09%   |
| 2160x1440          | 1         | 1.09%   |
| 1920x1200 (WUXGA)  | 1         | 1.09%   |
| 1360x768           | 1         | 1.09%   |
| 1280x720 (HD)      | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 30.93%  |
| 14      | 15        | 15.46%  |
| 17      | 10        | 10.31%  |
| 24      | 5         | 5.15%   |
| 23      | 5         | 5.15%   |
| 13      | 5         | 5.15%   |
| 31      | 4         | 4.12%   |
| 27      | 4         | 4.12%   |
| Unknown | 4         | 4.12%   |
| 19      | 3         | 3.09%   |
| 32      | 2         | 2.06%   |
| 22      | 2         | 2.06%   |
| 18      | 2         | 2.06%   |
| 12      | 2         | 2.06%   |
| 48      | 1         | 1.03%   |
| 42      | 1         | 1.03%   |
| 34      | 1         | 1.03%   |
| 21      | 1         | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 51.58%  |
| 501-600     | 13        | 13.68%  |
| 351-400     | 10        | 10.53%  |
| 401-500     | 5         | 5.26%   |
| 201-300     | 5         | 5.26%   |
| 601-700     | 4         | 4.21%   |
| Unknown     | 4         | 4.21%   |
| 701-800     | 3         | 3.16%   |
| 1001-1500   | 1         | 1.05%   |
| 901-1000    | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 77.27%  |
| 16/10   | 11        | 12.5%   |
| 5/4     | 3         | 3.41%   |
| Unknown | 3         | 3.41%   |
| 6/5     | 1         | 1.14%   |
| 32/9    | 1         | 1.14%   |
| 21/9    | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 31.25%  |
| 81-90          | 18        | 18.75%  |
| 201-250        | 11        | 11.46%  |
| 351-500        | 7         | 7.29%   |
| 121-130        | 7         | 7.29%   |
| 301-350        | 4         | 4.17%   |
| 141-150        | 4         | 4.17%   |
| Unknown        | 4         | 4.17%   |
| 151-200        | 3         | 3.13%   |
| 71-80          | 2         | 2.08%   |
| 61-70          | 2         | 2.08%   |
| 501-1000       | 2         | 2.08%   |
| 251-300        | 1         | 1.04%   |
| 131-140        | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 34.07%  |
| 51-100        | 26        | 28.57%  |
| 101-120       | 24        | 26.37%  |
| Unknown       | 4         | 4.4%    |
| 161-240       | 3         | 3.3%    |
| 1-50          | 2         | 2.2%    |
| More than 240 | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 68        | 80.95%  |
| 2     | 13        | 15.48%  |
| 3     | 2         | 2.38%   |
| 0     | 1         | 1.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 45        | 32.14%  |
| Intel                             | 44        | 31.43%  |
| Qualcomm Atheros                  | 17        | 12.14%  |
| Broadcom                          | 9         | 6.43%   |
| TP-Link                           | 3         | 2.14%   |
| Qualcomm Atheros Communications   | 3         | 2.14%   |
| Broadcom Limited                  | 3         | 2.14%   |
| Samsung Electronics               | 2         | 1.43%   |
| Ralink Technology                 | 2         | 1.43%   |
| Ralink                            | 2         | 1.43%   |
| Xiaomi                            | 1         | 0.71%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.71%   |
| NetGear                           | 1         | 0.71%   |
| Microsoft                         | 1         | 0.71%   |
| Marvell Technology Group          | 1         | 0.71%   |
| Lenovo                            | 1         | 0.71%   |
| Huawei Technologies               | 1         | 0.71%   |
| Ericsson Business Mobile Networks | 1         | 0.71%   |
| D-Link System                     | 1         | 0.71%   |
| D-Link                            | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 27        | 16.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 6         | 3.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 3.05%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 3.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 4         | 2.44%   |
| Intel Wireless 7265                                                       | 4         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 2.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 1.83%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 1.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 1.83%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 1.83%   |
| Intel Wireless 8260                                                       | 3         | 1.83%   |
| Intel Wireless 3160                                                       | 3         | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.22%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 2         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.22%   |
| Intel I211 Gigabit Network Connection                                     | 2         | 1.22%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 0.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 1         | 0.61%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.61%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                      | 1         | 0.61%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.61%   |
| OnePlus (Shenzhen) EB2103                                                 | 1         | 0.61%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.61%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.61%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 0.61%   |
| Lenovo ThinkPad TBT 3 Dock                                                | 1         | 0.61%   |
| Intel Wireless 8265 / 8275                                                | 1         | 0.61%   |
| Intel Wireless 7260                                                       | 1         | 0.61%   |
| Intel Wireless 3165                                                       | 1         | 0.61%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.61%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.61%   |
| Intel I210 Gigabit Network Connection                                     | 1         | 0.61%   |
| Intel Ethernet controller                                                 | 1         | 0.61%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 45.98%  |
| Qualcomm Atheros                | 13        | 14.94%  |
| Realtek Semiconductor           | 11        | 12.64%  |
| Broadcom                        | 6         | 6.9%    |
| TP-Link                         | 3         | 3.45%   |
| Qualcomm Atheros Communications | 3         | 3.45%   |
| Ralink Technology               | 2         | 2.3%    |
| Ralink                          | 2         | 2.3%    |
| Broadcom Limited                | 2         | 2.3%    |
| NetGear                         | 1         | 1.15%   |
| Microsoft                       | 1         | 1.15%   |
| Marvell Technology Group        | 1         | 1.15%   |
| D-Link System                   | 1         | 1.15%   |
| D-Link                          | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 5.75%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 5.75%   |
| Intel Wireless 7265                                                       | 4         | 4.6%    |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 4.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 3.45%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 3.45%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 3.45%   |
| Intel Wireless 8260                                                       | 3         | 3.45%   |
| Intel Wireless 3160                                                       | 3         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.3%    |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 2.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 2.3%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.15%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                      | 1         | 1.15%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.15%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.15%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.15%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 1.15%   |
| Intel Wireless 8265 / 8275                                                | 1         | 1.15%   |
| Intel Wireless 7260                                                       | 1         | 1.15%   |
| Intel Wireless 3165                                                       | 1         | 1.15%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 1.15%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.15%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.15%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.15%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]      | 1         | 1.15%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                            | 1         | 1.15%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.15%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 1         | 1.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                        | 1         | 1.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 52.05%  |
| Intel                 | 17        | 23.29%  |
| Qualcomm Atheros      | 8         | 10.96%  |
| Broadcom              | 4         | 5.48%   |
| Samsung Electronics   | 2         | 2.74%   |
| Xiaomi                | 1         | 1.37%   |
| Lenovo                | 1         | 1.37%   |
| Huawei Technologies   | 1         | 1.37%   |
| Broadcom Limited      | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 36%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 8%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.67%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.67%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.33%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.33%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.33%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.33%   |
| Intel Ethernet controller                                         | 1         | 1.33%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.33%   |
| Huawei COL-L29                                                    | 1         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.33%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.33%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 52.7%   |
| Ethernet | 68        | 45.95%  |
| Modem    | 1         | 0.68%   |
| Unknown  | 1         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 64.52%  |
| Ethernet | 33        | 35.48%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 59.52%  |
| 1     | 31        | 36.9%   |
| 3     | 2         | 2.38%   |
| 0     | 1         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 72.94%  |
| Yes  | 23        | 27.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 54.39%  |
| Qualcomm Atheros Communications | 9         | 15.79%  |
| Realtek Semiconductor           | 4         | 7.02%   |
| Broadcom                        | 4         | 7.02%   |
| Cambridge Silicon Radio         | 3         | 5.26%   |
| Dell                            | 2         | 3.51%   |
| Marvell Semiconductor           | 1         | 1.75%   |
| Lite-On Technology              | 1         | 1.75%   |
| Foxconn / Hon Hai               | 1         | 1.75%   |
| Apple                           | 1         | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 19.3%   |
| Intel Bluetooth Device                              | 9         | 15.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 14.04%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 7.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.51%   |
| Realtek Bluetooth Radio                             | 2         | 3.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 3.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.51%   |
| Qualcomm Atheros Bluetooth                          | 1         | 1.75%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.75%   |
| Lite-On Bluetooth Radio                             | 1         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.75%   |
| Intel AX200 Bluetooth                               | 1         | 1.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.75%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.75%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 1.75%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.75%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.75%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.75%   |
| Apple Bluetooth Host Controller                     | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 72        | 63.72%  |
| Nvidia              | 19        | 16.81%  |
| AMD                 | 18        | 15.93%  |
| Lenovo              | 1         | 0.88%   |
| GYROCOM C&C         | 1         | 0.88%   |
| GN Netcom           | 1         | 0.88%   |
| C-Media Electronics | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 6.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6         | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 4.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 3.76%   |
| Intel Sunrise Point-LP HD Audio                                                   | 5         | 3.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 5         | 3.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 3.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 3.01%   |
| Intel Haswell-ULT HD Audio Controller                                             | 4         | 3.01%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 3.01%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 3.01%   |
| Intel 8 Series HD Audio Controller                                                | 4         | 3.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 3         | 2.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 2.26%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3         | 2.26%   |
| AMD FCH Azalia Controller                                                         | 3         | 2.26%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 2.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 1.5%    |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.5%    |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 1.5%    |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.5%    |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.5%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.5%    |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.75%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.75%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1         | 0.75%   |
| Nvidia Audio device                                                               | 1         | 0.75%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 1         | 0.75%   |
| Intel USB PnP Sound Device                                                        | 1         | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 0.75%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 0.75%   |
| GYROCOM C&C NuForce ÂµDAC 2 HP                                                  | 1         | 0.75%   |
| GN Netcom Jabra Evolve 65                                                         | 1         | 0.75%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 0.75%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 0.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 0.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.75%   |
| AMD Polaris 22 HDMI Audio                                                         | 1         | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                          | 1         | 0.75%   |
| AMD High Definition Audio Controller                                              | 1         | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 0.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 25%     |
| SK hynix            | 10        | 15.63%  |
| Crucial             | 7         | 10.94%  |
| Unknown             | 6         | 9.38%   |
| Kingston            | 6         | 9.38%   |
| Micron Technology   | 5         | 7.81%   |
| Elpida              | 3         | 4.69%   |
| Corsair             | 3         | 4.69%   |
| Ramaxel Technology  | 2         | 3.13%   |
| A-DATA Technology   | 2         | 3.13%   |
| Team                | 1         | 1.56%   |
| S                   | 1         | 1.56%   |
| Nanya Technology    | 1         | 1.56%   |
| G.Skill             | 1         | 1.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 2.94%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 1.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.47%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 1.47%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.47%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s               | 1         | 1.47%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 1.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.47%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 1.47%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                 | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 1.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| SK hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.47%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 1.47%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.47%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 1.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.47%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s            | 1         | 1.47%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                                 | 1         | 1.47%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.47%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s                  | 1         | 1.47%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s                  | 1         | 1.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 1.47%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 1         | 1.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 1         | 1.47%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.47%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 1.47%   |
| Kingston RAM HP26D4S9S8MH-8 8GB SODIMM DDR4 2400MT/s                | 1         | 1.47%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s                 | 1         | 1.47%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s            | 1         | 1.47%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 1         | 1.47%   |
| Kingston RAM 9905469-066.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 1.47%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.47%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.47%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 1         | 1.47%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.47%   |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| Crucial RAM CT16G4SFRA32A.M8FB 16GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s               | 1         | 1.47%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s            | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 25        | 43.1%   |
| DDR3    | 25        | 43.1%   |
| LPDDR4  | 3         | 5.17%   |
| DDR2    | 3         | 5.17%   |
| LPDDR3  | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 74.14%  |
| DIMM         | 11        | 18.97%  |
| Row Of Chips | 4         | 6.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 23        | 35.38%  |
| 8192  | 22        | 33.85%  |
| 16384 | 7         | 10.77%  |
| 2048  | 7         | 10.77%  |
| 32768 | 3         | 4.62%   |
| 1024  | 3         | 4.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 30%     |
| 2667    | 12        | 20%     |
| 3200    | 8         | 13.33%  |
| 1334    | 4         | 6.67%   |
| 2400    | 3         | 5%      |
| 3266    | 2         | 3.33%   |
| 2133    | 2         | 3.33%   |
| 1333    | 2         | 3.33%   |
| 4267    | 1         | 1.67%   |
| 3600    | 1         | 1.67%   |
| 2666    | 1         | 1.67%   |
| 1067    | 1         | 1.67%   |
| 1066    | 1         | 1.67%   |
| 800     | 1         | 1.67%   |
| 667     | 1         | 1.67%   |
| 533     | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

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
| Chicony Electronics                    | 17        | 29.82%  |
| Acer                                   | 8         | 14.04%  |
| Microdia                               | 7         | 12.28%  |
| IMC Networks                           | 4         | 7.02%   |
| Sunplus Innovation Technology          | 3         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.26%   |
| Ricoh                                  | 2         | 3.51%   |
| Realtek Semiconductor                  | 2         | 3.51%   |
| Luxvisions Innotech Limited            | 2         | 3.51%   |
| Suyin                                  | 1         | 1.75%   |
| Silicon Motion                         | 1         | 1.75%   |
| Samsung Electronics                    | 1         | 1.75%   |
| Quanta                                 | 1         | 1.75%   |
| Microsoft                              | 1         | 1.75%   |
| Logitech                               | 1         | 1.75%   |
| Creative Technology                    | 1         | 1.75%   |
| Apple                                  | 1         | 1.75%   |
| Alcor Micro                            | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 5.17%   |
| Acer HD Webcam                                                             | 3         | 5.17%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.45%   |
| Microdia PC Microscope camera                                              | 2         | 3.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 3.45%   |
| IMC Networks Integrated Camera                                             | 2         | 3.45%   |
| Chicony Integrated Camera                                                  | 2         | 3.45%   |
| Chicony HD Webcam                                                          | 2         | 3.45%   |
| Acer Integrated Camera                                                     | 2         | 3.45%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.72%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.72%   |
| Sunplus HD WebCam                                                          | 1         | 1.72%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 1.72%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 1.72%   |
| Ricoh Pavilion Webcam                                                      | 1         | 1.72%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.72%   |
| Quanta HP High Definition 1MP Webcam                                       | 1         | 1.72%   |
| Microsoft LifeCam Rear                                                     | 1         | 1.72%   |
| Microsoft LifeCam Front                                                    | 1         | 1.72%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.72%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 1.72%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 1.72%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.72%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.72%   |
| Logitech HD Webcam C615                                                    | 1         | 1.72%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.72%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.72%   |
| Creative Live! Cam Sync HD [VF0770]                                        | 1         | 1.72%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.72%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 1.72%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.72%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.72%   |
| Chicony HP Webcam                                                          | 1         | 1.72%   |
| Chicony HP TrueVision HD                                                   | 1         | 1.72%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.72%   |
| Chicony HP HD Camera                                                       | 1         | 1.72%   |
| Chicony HD User Facing                                                     | 1         | 1.72%   |
| Chicony CNF8248                                                            | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 1.72%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.72%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.72%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.72%   |
| Acer HD Camera                                                             | 1         | 1.72%   |
| Acer EasyCamera                                                            | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 58.33%  |
| Synaptics             | 2         | 16.67%  |
| LighTuning Technology | 1         | 8.33%   |
| Elan Microelectronics | 1         | 8.33%   |
| AuthenTec             | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Fingerprint scanner                                       | 2         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 8.33%   |
| Validity Sensors VFS491                                                    | 1         | 8.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 8.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 8.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 8.33%   |
| Elan ELAN:Fingerprint                                                      | 1         | 8.33%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 8.33%   |
| Unknown                                                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Alcor Micro | 2         | 40%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 55        | 65.48%  |
| 1     | 20        | 23.81%  |
| 2     | 8         | 9.52%   |
| 3     | 1         | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 32.43%  |
| Net/wireless          | 6         | 16.22%  |
| Graphics card         | 5         | 13.51%  |
| Chipcard              | 5         | 13.51%  |
| Storage               | 3         | 8.11%   |
| Multimedia controller | 2         | 5.41%   |
| Storage/raid          | 1         | 2.7%    |
| Net/ethernet          | 1         | 2.7%    |
| Modem                 | 1         | 2.7%    |
| Camera                | 1         | 2.7%    |

