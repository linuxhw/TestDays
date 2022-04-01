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

Total: 103

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| 5.10.0-6parrot1-amd64    | 29        | 36.25%  |
| 5.10.0-8parrot1-amd64    | 17        | 21.25%  |
| 5.14.0-9parrot1-amd64    | 12        | 15%     |
| 5.10.0-3parrot1-amd64    | 5         | 6.25%   |
| 5.7.0-2parrot2-amd64     | 4         | 5%      |
| 5.10.0-5parrot1-amd64    | 4         | 5%      |
| 5.15.0-15parrot1-amd64   | 3         | 3.75%   |
| 5.14.0-2parrot1-amd64    | 3         | 3.75%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.25%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.25%   |
| Unknown                  | 1         | 1.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 56        | 70%     |
| 5.14.0  | 15        | 18.75%  |
| 5.7.0   | 4         | 5%      |
| 5.15.0  | 3         | 3.75%   |
| 5.6.0   | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 56        | 70%     |
| 5.14    | 15        | 18.75%  |
| 5.7     | 4         | 5%      |
| 5.15    | 3         | 3.75%   |
| 5.6     | 1         | 1.25%   |
| Unknown | 1         | 1.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 79        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 47        | 58.75%  |
| KDE5    | 18        | 22.5%   |
| KDE     | 7         | 8.75%   |
| Unknown | 4         | 5%      |
| XFCE    | 3         | 3.75%   |
| LXDE    | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 79        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 30        | 37.04%  |
| Unknown | 27        | 33.33%  |
| TDM     | 23        | 28.4%   |
| SDDM    | 1         | 1.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 38        | 48.1%   |
| fr_FR   | 6         | 7.59%   |
| en_GB   | 6         | 7.59%   |
| pt_BR   | 5         | 6.33%   |
| ru_RU   | 4         | 5.06%   |
| en_AU   | 4         | 5.06%   |
| de_DE   | 3         | 3.8%    |
| Unknown | 3         | 3.8%    |
| es_ES   | 2         | 2.53%   |
| ru_UA   | 1         | 1.27%   |
| pl_PL   | 1         | 1.27%   |
| nl_BE   | 1         | 1.27%   |
| id_ID   | 1         | 1.27%   |
| es_CO   | 1         | 1.27%   |
| en_NG   | 1         | 1.27%   |
| cs_CZ   | 1         | 1.27%   |
| an_ES   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 50        | 61.73%  |
| EFI  | 31        | 38.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 62        | 78.48%  |
| Ext4  | 12        | 15.19%  |
| Xfs   | 5         | 6.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 33        | 41.25%  |
| Unknown | 29        | 36.25%  |
| MBR     | 18        | 22.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 81.25%  |
| Yes       | 15        | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 48        | 60.76%  |
| Yes       | 31        | 39.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 18.99%  |
| ASUSTek Computer    | 13        | 16.46%  |
| Dell                | 11        | 13.92%  |
| Lenovo              | 7         | 8.86%   |
| MSI                 | 6         | 7.59%   |
| Acer                | 5         | 6.33%   |
| Samsung Electronics | 2         | 2.53%   |
| Apple               | 2         | 2.53%   |
| Alienware           | 2         | 2.53%   |
| ZOTAC               | 1         | 1.27%   |
| Wortmann AG         | 1         | 1.27%   |
| Wistron             | 1         | 1.27%   |
| Toxic               | 1         | 1.27%   |
| Toshiba             | 1         | 1.27%   |
| Sony                | 1         | 1.27%   |
| Quanta              | 1         | 1.27%   |
| Positivo            | 1         | 1.27%   |
| Microsoft           | 1         | 1.27%   |
| Intel               | 1         | 1.27%   |
| GPU Company         | 1         | 1.27%   |
| Gigabyte Technology | 1         | 1.27%   |
| Gateway             | 1         | 1.27%   |
| Fujitsu             | 1         | 1.27%   |
| Eluktronics         | 1         | 1.27%   |
| ASRock              | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 650 G1                       | 2         | 2.53%   |
| ASUS Q524UQ                             | 2         | 2.53%   |
| Wortmann AG TERRA_MOBILE_1542           | 1         | 1.27%   |
| Wistron FMVDD2A0H0                      | 1         | 1.27%   |
| Toxic GM7MQ8P                           | 1         | 1.27%   |
| Toshiba Satellite L655                  | 1         | 1.27%   |
| Sony SVP1321L1EBI                       | 1         | 1.27%   |
| Samsung 350V5C/351V5C/3540VC/3440VC     | 1         | 1.27%   |
| Samsung 300E4C/300E5C/300E7C            | 1         | 1.27%   |
| Quanta HDX PREMIUM SERIES               | 1         | 1.27%   |
| Positivo Q232A                          | 1         | 1.27%   |
| MSI MS-7529                             | 1         | 1.27%   |
| MSI GT60 2OC/2OD                        | 1         | 1.27%   |
| MSI GS66 Stealth 10UG                   | 1         | 1.27%   |
| MSI GE75 Raider 10SF                    | 1         | 1.27%   |
| MSI GE73 Raider RGB 8RE                 | 1         | 1.27%   |
| MSI GE63 Raider RGB 8RE                 | 1         | 1.27%   |
| Microsoft Surface Pro 3                 | 1         | 1.27%   |
| Lenovo Yoga S740-14IIL 81RS             | 1         | 1.27%   |
| Lenovo Y520-15IKBN 80WK                 | 1         | 1.27%   |
| Lenovo ThinkPad X260 20F5S5QT00         | 1         | 1.27%   |
| Lenovo ThinkPad X250 20CL001GZA         | 1         | 1.27%   |
| Lenovo ThinkPad E15 20RD0086UE          | 1         | 1.27%   |
| Lenovo IdeaPad 5 14ITL05 82FE           | 1         | 1.27%   |
| Lenovo B50-80 80EW                      | 1         | 1.27%   |
| Intel NUC8i7HVK                         | 1         | 1.27%   |
| HP ZBook 15 G5                          | 1         | 1.27%   |
| HP Pavilion Notebook                    | 1         | 1.27%   |
| HP Pavilion dv7                         | 1         | 1.27%   |
| HP Pavilion dv6700                      | 1         | 1.27%   |
| HP Pavilion dv6                         | 1         | 1.27%   |
| HP Pavilion dv4                         | 1         | 1.27%   |
| HP Laptop 15s-eq1xxx                    | 1         | 1.27%   |
| HP Laptop 15-dw0xxx                     | 1         | 1.27%   |
| HP EliteBook 8470p                      | 1         | 1.27%   |
| HP EliteBook 840 G8 Notebook PC         | 1         | 1.27%   |
| HP Compaq Pro 6305 MT                   | 1         | 1.27%   |
| HP All-in-One 24-f0xx                   | 1         | 1.27%   |
| HP 250 G7 Notebook PC                   | 1         | 1.27%   |
| GPU Company GWTN141-10                  | 1         | 1.27%   |
| Gigabyte A320M-S2H                      | 1         | 1.27%   |
| Gateway MP8708                          | 1         | 1.27%   |
| Fujitsu LIFEBOOK T731                   | 1         | 1.27%   |
| Eluktronics MAG-15u                     | 1         | 1.27%   |
| Dell XPS 8930                           | 1         | 1.27%   |
| Dell Precision M4600                    | 1         | 1.27%   |
| Dell OptiPlex 7070                      | 1         | 1.27%   |
| Dell OptiPlex 3010                      | 1         | 1.27%   |
| Dell Latitude E7440                     | 1         | 1.27%   |
| Dell Latitude E6420                     | 1         | 1.27%   |
| Dell Latitude E6410                     | 1         | 1.27%   |
| Dell Inspiron 7501                      | 1         | 1.27%   |
| Dell Inspiron 5593                      | 1         | 1.27%   |
| Dell Inspiron 5558                      | 1         | 1.27%   |
| Dell Inspiron 5420                      | 1         | 1.27%   |
| ASUS X75VB                              | 1         | 1.27%   |
| ASUS X450EA                             | 1         | 1.27%   |
| ASUS VivoBook_ASUSLaptop X412DAP_F412DA | 1         | 1.27%   |
| ASUS ROG STRIX B450-F GAMING            | 1         | 1.27%   |
| ASUS PRIME X399-A                       | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| HP Pavilion            | 5         | 6.33%   |
| Dell Inspiron          | 4         | 5.06%   |
| Lenovo ThinkPad        | 3         | 3.8%    |
| Dell Latitude          | 3         | 3.8%    |
| HP ProBook             | 2         | 2.53%   |
| HP Laptop              | 2         | 2.53%   |
| HP EliteBook           | 2         | 2.53%   |
| Dell OptiPlex          | 2         | 2.53%   |
| ASUS Q524UQ            | 2         | 2.53%   |
| Acer Aspire            | 2         | 2.53%   |
| Wortmann AG TERRA      | 1         | 1.27%   |
| Wistron FMVDD2A0H0     | 1         | 1.27%   |
| Toxic GM7MQ8P          | 1         | 1.27%   |
| Toshiba Satellite      | 1         | 1.27%   |
| Sony SVP1321L1EBI      | 1         | 1.27%   |
| Samsung 350V5C         | 1         | 1.27%   |
| Samsung 300E4C         | 1         | 1.27%   |
| Quanta HDX             | 1         | 1.27%   |
| Positivo Q232A         | 1         | 1.27%   |
| MSI MS-7529            | 1         | 1.27%   |
| MSI GT60               | 1         | 1.27%   |
| MSI GS66               | 1         | 1.27%   |
| MSI GE75               | 1         | 1.27%   |
| MSI GE73               | 1         | 1.27%   |
| MSI GE63               | 1         | 1.27%   |
| Microsoft Surface      | 1         | 1.27%   |
| Lenovo Yoga            | 1         | 1.27%   |
| Lenovo Y520-15IKBN     | 1         | 1.27%   |
| Lenovo IdeaPad         | 1         | 1.27%   |
| Lenovo B50-80          | 1         | 1.27%   |
| Intel NUC8i7HVK        | 1         | 1.27%   |
| HP ZBook               | 1         | 1.27%   |
| HP Compaq              | 1         | 1.27%   |
| HP All-in-One          | 1         | 1.27%   |
| HP 250                 | 1         | 1.27%   |
| GPU Company GWTN141-10 | 1         | 1.27%   |
| Gigabyte A320M-S2H     | 1         | 1.27%   |
| Gateway MP8708         | 1         | 1.27%   |
| Fujitsu LIFEBOOK       | 1         | 1.27%   |
| Eluktronics MAG-15u    | 1         | 1.27%   |
| Dell XPS               | 1         | 1.27%   |
| Dell Precision         | 1         | 1.27%   |
| ASUS X75VB             | 1         | 1.27%   |
| ASUS X450EA            | 1         | 1.27%   |
| ASUS VivoBook          | 1         | 1.27%   |
| ASUS ROG               | 1         | 1.27%   |
| ASUS PRIME             | 1         | 1.27%   |
| ASUS P8H67-M           | 1         | 1.27%   |
| ASUS M5A99X            | 1         | 1.27%   |
| ASUS M5A78L-M          | 1         | 1.27%   |
| ASUS KJ250AA-ABE       | 1         | 1.27%   |
| ASUS G74Sx             | 1         | 1.27%   |
| ASUS F2A85-M           | 1         | 1.27%   |
| ASRock Z87             | 1         | 1.27%   |
| Apple MacBookPro8      | 1         | 1.27%   |
| Apple MacBookPro11     | 1         | 1.27%   |
| Alienware X51          | 1         | 1.27%   |
| Alienware m15          | 1         | 1.27%   |
| Acer TravelMate        | 1         | 1.27%   |
| Acer Swift             | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 12.66%  |
| 2013 | 9         | 11.39%  |
| 2011 | 9         | 11.39%  |
| 2020 | 7         | 8.86%   |
| 2018 | 7         | 8.86%   |
| 2016 | 7         | 8.86%   |
| 2012 | 5         | 6.33%   |
| 2021 | 4         | 5.06%   |
| 2010 | 4         | 5.06%   |
| 2017 | 3         | 3.8%    |
| 2015 | 3         | 3.8%    |
| 2014 | 3         | 3.8%    |
| 2008 | 3         | 3.8%    |
| 2007 | 3         | 3.8%    |
| 2009 | 1         | 1.27%   |
| 2006 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 57        | 72.15%  |
| Desktop    | 19        | 24.05%  |
| Tablet     | 1         | 1.27%   |
| Mini pc    | 1         | 1.27%   |
| All in one | 1         | 1.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 79        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 20        | 25.32%  |
| 8.01-16.0   | 18        | 22.78%  |
| 16.01-24.0  | 16        | 20.25%  |
| 3.01-4.0    | 12        | 15.19%  |
| 1.01-2.0    | 4         | 5.06%   |
| 32.01-64.0  | 3         | 3.8%    |
| 64.01-256.0 | 3         | 3.8%    |
| 24.01-32.0  | 2         | 2.53%   |
| 2.01-3.0    | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 32        | 39.51%  |
| 2.01-3.0  | 24        | 29.63%  |
| 3.01-4.0  | 12        | 14.81%  |
| 4.01-8.0  | 10        | 12.35%  |
| 0.51-1.0  | 2         | 2.47%   |
| 8.01-16.0 | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 50.63%  |
| 2      | 27        | 34.18%  |
| 3      | 9         | 11.39%  |
| 4      | 2         | 2.53%   |
| 5      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 62.5%   |
| Yes       | 30        | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 83.54%  |
| No        | 13        | 16.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 92.5%   |
| No        | 6         | 7.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 67.09%  |
| No        | 26        | 32.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 31.65%  |
| Germany      | 7         | 8.86%   |
| Spain        | 5         | 6.33%   |
| France       | 5         | 6.33%   |
| Brazil       | 5         | 6.33%   |
| UK           | 3         | 3.8%    |
| Russia       | 3         | 3.8%    |
| Netherlands  | 3         | 3.8%    |
| Australia    | 3         | 3.8%    |
| Iraq         | 2         | 2.53%   |
| Vietnam      | 1         | 1.27%   |
| Ukraine      | 1         | 1.27%   |
| Sweden       | 1         | 1.27%   |
| South Africa | 1         | 1.27%   |
| Puerto Rico  | 1         | 1.27%   |
| Poland       | 1         | 1.27%   |
| Nigeria      | 1         | 1.27%   |
| Mexico       | 1         | 1.27%   |
| Kenya        | 1         | 1.27%   |
| Indonesia    | 1         | 1.27%   |
| Hungary      | 1         | 1.27%   |
| Czechia      | 1         | 1.27%   |
| Colombia     | 1         | 1.27%   |
| Canada       | 1         | 1.27%   |
| Belgium      | 1         | 1.27%   |
| Bangladesh   | 1         | 1.27%   |
| Azerbaijan   | 1         | 1.27%   |
| Algeria      | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Lyon              | 2         | 2.47%   |
| Eugene            | 2         | 2.47%   |
| Chicago           | 2         | 2.47%   |
| Barcelona         | 2         | 2.47%   |
| Witbank           | 1         | 1.23%   |
| Wichita           | 1         | 1.23%   |
| West Jordan       | 1         | 1.23%   |
| Waveland          | 1         | 1.23%   |
| Warsaw            | 1         | 1.23%   |
| Visalia           | 1         | 1.23%   |
| Ternopil          | 1         | 1.23%   |
| Stockholm         | 1         | 1.23%   |
| Sinntal           | 1         | 1.23%   |
| Sheffield         | 1         | 1.23%   |
| Secaucus          | 1         | 1.23%   |
| Sao Paulo         | 1         | 1.23%   |
| Santo AndrГ©    | 1         | 1.23%   |
| Santa Maria       | 1         | 1.23%   |
| Sannois           | 1         | 1.23%   |
| Saint Paul        | 1         | 1.23%   |
| Regensburg        | 1         | 1.23%   |
| Reading           | 1         | 1.23%   |
| Prague            | 1         | 1.23%   |
| Portsmouth        | 1         | 1.23%   |
| Ponce             | 1         | 1.23%   |
| Paris             | 1         | 1.23%   |
| Orange Park       | 1         | 1.23%   |
| Offenbach         | 1         | 1.23%   |
| Nam Định       | 1         | 1.23%   |
| Nairobi           | 1         | 1.23%   |
| Munich            | 1         | 1.23%   |
| Mostoles          | 1         | 1.23%   |
| Metairie          | 1         | 1.23%   |
| Melbourne         | 1         | 1.23%   |
| Marietta          | 1         | 1.23%   |
| Manchester        | 1         | 1.23%   |
| Manaus            | 1         | 1.23%   |
| Majadahonda       | 1         | 1.23%   |
| Maggie Valley     | 1         | 1.23%   |
| Los Mochis        | 1         | 1.23%   |
| Los Angeles       | 1         | 1.23%   |
| Long Beach        | 1         | 1.23%   |
| London            | 1         | 1.23%   |
| Lagos             | 1         | 1.23%   |
| Lafayette         | 1         | 1.23%   |
| Kobern-Gondorf    | 1         | 1.23%   |
| Khabarovsk        | 1         | 1.23%   |
| Kazanâ€™     | 1         | 1.23%   |
| Jihlava           | 1         | 1.23%   |
| Jaragua           | 1         | 1.23%   |
| Houston           | 1         | 1.23%   |
| Haarlem           | 1         | 1.23%   |
| Fusagasuga        | 1         | 1.23%   |
| Frankfurt am Main | 1         | 1.23%   |
| Fort Lauderdale   | 1         | 1.23%   |
| Fallbrook         | 1         | 1.23%   |
| Erbil             | 1         | 1.23%   |
| Edmonton          | 1         | 1.23%   |
| East Malvern      | 1         | 1.23%   |
| Dudenhofen        | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 13.71%  |
| Seagate             | 15        | 21     | 12.1%   |
| WDC                 | 14        | 17     | 11.29%  |
| Crucial             | 10        | 13     | 8.06%   |
| Unknown             | 9         | 9      | 7.26%   |
| Toshiba             | 9         | 10     | 7.26%   |
| SanDisk             | 6         | 6      | 4.84%   |
| Kingston            | 6         | 6      | 4.84%   |
| Hitachi             | 6         | 7      | 4.84%   |
| SK Hynix            | 5         | 5      | 4.03%   |
| HGST                | 4         | 4      | 3.23%   |
| Micron Technology   | 3         | 3      | 2.42%   |
| China               | 3         | 4      | 2.42%   |
| A-DATA Technology   | 3         | 3      | 2.42%   |
| KIOXIA              | 2         | 2      | 1.61%   |
| W800SH              | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| ROG                 | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| Lexar               | 1         | 1      | 0.81%   |
| Intenso             | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| FORESEE             | 1         | 1      | 0.81%   |
| Corsair             | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 32GB              | 3         | 2.24%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 3         | 2.24%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 2.24%   |
| HGST HTS541010A9E680 1TB                | 3         | 2.24%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 1.49%   |
| Toshiba DT01ACA100 1TB                  | 2         | 1.49%   |
| Seagate Expansion 320GB                 | 2         | 1.49%   |
| Samsung SSD 860 EVO 500GB               | 2         | 1.49%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 1.49%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 1.49%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.75%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.75%   |
| WDC WDBNCE2500PNC 250GB SSD             | 1         | 0.75%   |
| WDC WDBNCE0010PNC 1TB SSD               | 1         | 0.75%   |
| WDC WD800BEVS-22RST0 80GB               | 1         | 0.75%   |
| WDC WD5000AACS-00ZUB0 500GB             | 1         | 0.75%   |
| WDC WD3200LPVX-60V0TT0 320GB            | 1         | 0.75%   |
| WDC WD3200LPVX-00V0TT0 320GB            | 1         | 0.75%   |
| WDC WD2500BPVT-00JJ5T0 250GB            | 1         | 0.75%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.75%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.75%   |
| WDC WD10EARS-00Y5B1 1TB                 | 1         | 0.75%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB    | 1         | 0.75%   |
| W800SH 512GB SSD                        | 1         | 0.75%   |
| Unknown Y016B  16GB                     | 1         | 0.75%   |
| Unknown xD/SD/M.S.                      | 1         | 0.75%   |
| Unknown SS16G  16GB                     | 1         | 0.75%   |
| Unknown SS08G  8GB                      | 1         | 0.75%   |
| Unknown SDU1  64GB                      | 1         | 0.75%   |
| Unknown MMC Card  128GB                 | 1         | 0.75%   |
| Toshiba THNSNH128G8NT 128GB SSD         | 1         | 0.75%   |
| Toshiba THNSNF128GMCS 128GB SSD         | 1         | 0.75%   |
| Toshiba Q300. 480GB SSD                 | 1         | 0.75%   |
| Toshiba MQ01ABD100V -63 1TB             | 1         | 0.75%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.75%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.75%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.75%   |
| SPCC Solid State Disk 120GB             | 1         | 0.75%   |
| SK Hynix PC601 NVMe 256GB               | 1         | 0.75%   |
| SK Hynix NVMe SSD Drive 512GB           | 1         | 0.75%   |
| SK Hynix NVMe SSD Drive 256GB           | 1         | 0.75%   |
| SK Hynix HFM256GDJTNI-82A0A 256GB       | 1         | 0.75%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 1         | 0.75%   |
| Seagate ST98823AS 80GB                  | 1         | 0.75%   |
| Seagate ST9500420AS 500GB               | 1         | 0.75%   |
| Seagate ST9250410AS 250GB               | 1         | 0.75%   |
| Seagate ST500NM0011 500GB               | 1         | 0.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.75%   |
| Seagate ST500DM002-1SB10A 500GB         | 1         | 0.75%   |
| Seagate ST4000DM004-2CV104 4TB          | 1         | 0.75%   |
| Seagate ST3500413AS 500GB               | 1         | 0.75%   |
| Seagate ST320LT020-9YG142 320GB         | 1         | 0.75%   |
| Seagate ST31000528AS 1TB                | 1         | 0.75%   |
| Seagate ST250DM000-1BD141 250GB         | 1         | 0.75%   |
| Seagate ST2000LM007-1R8174 2TB          | 1         | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 0.75%   |
| SanDisk SD6SF1M128G1022I 128GB SSD      | 1         | 0.75%   |
| SanDisk Extreme SSD 2TB                 | 1         | 0.75%   |
| SanDisk DF4032  32GB                    | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 21     | 32.61%  |
| WDC                 | 10        | 12     | 21.74%  |
| Toshiba             | 6         | 6      | 13.04%  |
| Hitachi             | 6         | 7      | 13.04%  |
| HGST                | 4         | 4      | 8.7%    |
| Unknown             | 3         | 3      | 6.52%   |
| Samsung Electronics | 2         | 3      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 12     | 19.15%  |
| Samsung Electronics | 8         | 9      | 17.02%  |
| SanDisk             | 5         | 5      | 10.64%  |
| Kingston            | 5         | 5      | 10.64%  |
| WDC                 | 3         | 3      | 6.38%   |
| Toshiba             | 3         | 4      | 6.38%   |
| China               | 3         | 4      | 6.38%   |
| W800SH              | 1         | 1      | 2.13%   |
| SPCC                | 1         | 1      | 2.13%   |
| Patriot             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| LITEONIT            | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| FORESEE             | 1         | 1      | 2.13%   |
| Corsair             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 39        | 53     | 36.45%  |
| HDD     | 38        | 56     | 35.51%  |
| NVMe    | 23        | 25     | 21.5%   |
| MMC     | 5         | 6      | 4.67%   |
| Unknown | 2         | 2      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 63        | 101    | 63.64%  |
| NVMe | 23        | 25     | 23.23%  |
| SAS  | 8         | 10     | 8.08%   |
| MMC  | 5         | 6      | 5.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 69     | 56.1%   |
| 0.51-1.0   | 28        | 32     | 34.15%  |
| 1.01-2.0   | 7         | 7      | 8.54%   |
| 3.01-4.0   | 1         | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 24.69%  |
| 251-500        | 19        | 23.46%  |
| 501-1000       | 12        | 14.81%  |
| 1001-2000      | 11        | 13.58%  |
| Unknown        | 8         | 9.88%   |
| 2001-3000      | 4         | 4.94%   |
| 51-100         | 4         | 4.94%   |
| More than 3000 | 2         | 2.47%   |
| 21-50          | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 20        | 24.39%  |
| 51-100    | 20        | 24.39%  |
| 101-250   | 11        | 13.41%  |
| 251-500   | 10        | 12.2%   |
| 1-20      | 9         | 10.98%  |
| Unknown   | 8         | 9.76%   |
| 501-1000  | 3         | 3.66%   |
| 1001-2000 | 1         | 1.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 7.14%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 7.14%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 7.14%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 7.14%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 7.14%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 7.14%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 7.14%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 7.14%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 1         | 1      | 7.14%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 7.14%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 7.14%   |
| Hitachi HUA722020ALA331 2TB                         | 1         | 1      | 7.14%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 7.14%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 38.46%  |
| SanDisk             | 2         | 2      | 15.38%  |
| Hitachi             | 2         | 2      | 15.38%  |
| Toshiba             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| A-DATA Technology   | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 62.5%   |
| Hitachi | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 61.54%  |
| SSD  | 4         | 4      | 30.77%  |
| NVMe | 1         | 1      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intenso SSD SATAIII 512GB | 1         | 1      | 100%    |

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
| Works    | 46        | 62     | 47.42%  |
| Detected | 38        | 65     | 39.18%  |
| Malfunc  | 12        | 14     | 12.37%  |
| Failed   | 1         | 1      | 1.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 64        | 63.37%  |
| AMD                         | 10        | 9.9%    |
| Samsung Electronics         | 8         | 7.92%   |
| SK Hynix                    | 5         | 4.95%   |
| Sandisk                     | 2         | 1.98%   |
| Micron Technology           | 2         | 1.98%   |
| KIOXIA                      | 2         | 1.98%   |
| VIA Technologies            | 1         | 0.99%   |
| Silicon Motion              | 1         | 0.99%   |
| Realtek Semiconductor       | 1         | 0.99%   |
| Phison Electronics          | 1         | 0.99%   |
| Micron/Crucial Technology   | 1         | 0.99%   |
| Kingston Technology Company | 1         | 0.99%   |
| JMicron Technology          | 1         | 0.99%   |
| ADATA Technology            | 1         | 0.99%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 5.31%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 6         | 5.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5         | 4.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 3.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 3.54%   |
| SK Hynix BC511                                                                          | 3         | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 2.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 2.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 2.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 2.65%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.77%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.77%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 1.77%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 1.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2         | 1.77%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.88%   |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 0.88%   |
| SK Hynix Gold P31 SSD                                                                   | 1         | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.88%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.88%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.88%   |
| Samsung Apple PCIe SSD                                                                  | 1         | 0.88%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.88%   |
| Micron/Crucial NVMe Controller                                                          | 1         | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.88%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1         | 0.88%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 1         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1         | 0.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5)  | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1         | 0.88%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1         | 0.88%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.88%   |
| AMD FCH SATA Controller D                                                               | 1         | 0.88%   |
| AMD FCH RAID Controller                                                                 | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 63        | 61.76%  |
| NVMe | 23        | 22.55%  |
| IDE  | 9         | 8.82%   |
| RAID | 7         | 6.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 68        | 86.08%  |
| AMD    | 11        | 13.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 2.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 2.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 2.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.53%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 2.53%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1         | 1.27%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.27%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.27%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.27%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.27%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1         | 1.27%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i7-8809G CPU @ 3.10GHz           | 1         | 1.27%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.27%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.27%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.27%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.27%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.27%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.27%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.27%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.27%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.27%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.27%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 1         | 1.27%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.27%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.27%   |
| Intel Core i5-4210M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz          | 1         | 1.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.27%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.27%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.27%   |
| Intel Core 2 Quad CPU Q9100 @ 2.26GHz       | 1         | 1.27%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 1         | 1.27%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.27%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.27%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1         | 1.27%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.27%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.27%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 1         | 1.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 24        | 30.38%  |
| Intel Core i5           | 24        | 30.38%  |
| Other                   | 4         | 5.06%   |
| Intel Core i3           | 3         | 3.8%    |
| Intel Core 2 Duo        | 3         | 3.8%    |
| Intel Pentium Silver    | 2         | 2.53%   |
| Intel Core 2 Quad       | 2         | 2.53%   |
| AMD Ryzen 3             | 2         | 2.53%   |
| AMD FX                  | 2         | 2.53%   |
| Intel Xeon              | 1         | 1.27%   |
| Intel Pentium Dual-Core | 1         | 1.27%   |
| Intel Pentium Dual      | 1         | 1.27%   |
| Intel Core M            | 1         | 1.27%   |
| Intel Core 2            | 1         | 1.27%   |
| Intel Atom              | 1         | 1.27%   |
| AMD Ryzen Threadripper  | 1         | 1.27%   |
| AMD Ryzen 7             | 1         | 1.27%   |
| AMD Ryzen 5             | 1         | 1.27%   |
| AMD E1                  | 1         | 1.27%   |
| AMD A8                  | 1         | 1.27%   |
| AMD A6                  | 1         | 1.27%   |
| AMD A4                  | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 35        | 44.3%   |
| 4      | 29        | 36.71%  |
| 6      | 8         | 10.13%  |
| 8      | 4         | 5.06%   |
| 12     | 1         | 1.27%   |
| 3      | 1         | 1.27%   |
| 1      | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 79        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 58        | 73.42%  |
| 1      | 21        | 26.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 40.74%  |
| 0x206a7    | 6         | 7.41%   |
| 0x306c3    | 4         | 4.94%   |
| 0xa0652    | 3         | 3.7%    |
| 0x906e9    | 3         | 3.7%    |
| 0x806c1    | 3         | 3.7%    |
| 0x306a9    | 3         | 3.7%    |
| 0x1067a    | 3         | 3.7%    |
| 0x806ec    | 2         | 2.47%   |
| 0x706e5    | 2         | 2.47%   |
| 0x40651    | 2         | 2.47%   |
| 0x306d4    | 2         | 2.47%   |
| 0x06000852 | 2         | 2.47%   |
| 0x906ed    | 1         | 1.23%   |
| 0x806d1    | 1         | 1.23%   |
| 0x706a8    | 1         | 1.23%   |
| 0x706a1    | 1         | 1.23%   |
| 0x6fd      | 1         | 1.23%   |
| 0x6f6      | 1         | 1.23%   |
| 0x506e3    | 1         | 1.23%   |
| 0x20655    | 1         | 1.23%   |
| 0x0a201016 | 1         | 1.23%   |
| 0x08600106 | 1         | 1.23%   |
| 0x08108109 | 1         | 1.23%   |
| 0x06006705 | 1         | 1.23%   |
| 0x0600111f | 1         | 1.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 15.19%  |
| Haswell       | 9         | 11.39%  |
| SandyBridge   | 8         | 10.13%  |
| IvyBridge     | 7         | 8.86%   |
| Skylake       | 5         | 6.33%   |
| Piledriver    | 4         | 5.06%   |
| Penryn        | 4         | 5.06%   |
| Core          | 4         | 5.06%   |
| CometLake     | 4         | 5.06%   |
| Broadwell     | 4         | 5.06%   |
| TigerLake     | 3         | 3.8%    |
| IceLake       | 3         | 3.8%    |
| Zen           | 2         | 2.53%   |
| Westmere      | 2         | 2.53%   |
| Goldmont plus | 2         | 2.53%   |
| Zen+          | 1         | 1.27%   |
| Zen 3         | 1         | 1.27%   |
| Zen 2         | 1         | 1.27%   |
| Silvermont    | 1         | 1.27%   |
| Jaguar        | 1         | 1.27%   |
| Excavator     | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 56.31%  |
| Nvidia | 27        | 26.21%  |
| AMD    | 18        | 17.48%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 4.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 3.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.83%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.83%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 1.89%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.89%   |
| Intel HD Graphics 630                                                                    | 2         | 1.89%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.89%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.89%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.94%   |
| Nvidia TU117M                                                                            | 1         | 0.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.94%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.94%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 0.94%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.94%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.94%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.94%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.94%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 1         | 0.94%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.94%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.94%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.94%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1         | 0.94%   |
| Nvidia G96CM [GeForce GT 130M]                                                           | 1         | 0.94%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 0.94%   |
| Nvidia G86 [GeForce 8300 GS]                                                             | 1         | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.94%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.94%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.94%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.94%   |
| Intel HD Graphics 530                                                                    | 1         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.94%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.94%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1         | 0.94%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.94%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 35        | 44.3%   |
| Intel + Nvidia | 16        | 20.25%  |
| 1 x AMD        | 12        | 15.19%  |
| 1 x Nvidia     | 10        | 12.66%  |
| Intel + AMD    | 5         | 6.33%   |
| AMD + Nvidia   | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 89.87%  |
| Proprietary | 8         | 10.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 68.75%  |
| 3.01-4.0   | 6         | 7.5%    |
| 1.01-2.0   | 6         | 7.5%    |
| 0.51-1.0   | 6         | 7.5%    |
| 7.01-8.0   | 3         | 3.75%   |
| 0.01-0.5   | 3         | 3.75%   |
| 2.01-3.0   | 1         | 1.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 14.77%  |
| Samsung Electronics     | 12        | 13.64%  |
| LG Display              | 10        | 11.36%  |
| BOE                     | 10        | 11.36%  |
| Chimei Innolux          | 9         | 10.23%  |
| Dell                    | 7         | 7.95%   |
| Chi Mei Optoelectronics | 4         | 4.55%   |
| Hewlett-Packard         | 3         | 3.41%   |
| Goldstar                | 3         | 3.41%   |
| Philips                 | 2         | 2.27%   |
| Apple                   | 2         | 2.27%   |
| AOC                     | 2         | 2.27%   |
| Vizio                   | 1         | 1.14%   |
| Toshiba                 | 1         | 1.14%   |
| STA                     | 1         | 1.14%   |
| Sony                    | 1         | 1.14%   |
| Sceptre                 | 1         | 1.14%   |
| Panasonic               | 1         | 1.14%   |
| NEC Computers           | 1         | 1.14%   |
| Insignia                | 1         | 1.14%   |
| AUS                     | 1         | 1.14%   |
| Ancor Communications    | 1         | 1.14%   |
| Acer                    | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 2         | 2.25%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                        | 1         | 1.12%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                          | 1         | 1.12%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                        | 1         | 1.12%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                       | 1         | 1.12%   |
| Sceptre LCD Monitor P30 2560x1080                                         | 1         | 1.12%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch      | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM03FE 1280x720                          | 1         | 1.12%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch        | 1         | 1.12%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch        | 1         | 1.12%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                  | 1         | 1.12%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                   | 1         | 1.12%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch              | 1         | 1.12%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch               | 1         | 1.12%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 1         | 1.12%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch               | 1         | 1.12%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch               | 1         | 1.12%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch               | 1         | 1.12%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 1         | 1.12%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch               | 1         | 1.12%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch               | 1         | 1.12%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch                | 1         | 1.12%   |
| Hewlett-Packard ALL-in-One HPN4018 1920x1080 527x297mm 23.8-inch          | 1         | 1.12%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch                      | 1         | 1.12%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch                   | 1         | 1.12%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                    | 1         | 1.12%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch                      | 1         | 1.12%   |
| Dell S2721NX DEL41FF 1920x1080 598x336mm 27.0-inch                        | 1         | 1.12%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch                         | 1         | 1.12%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                         | 1         | 1.12%   |
| Dell E2318H DELF092 1920x1080 509x286mm 23.0-inch                         | 1         | 1.12%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                         | 1         | 1.12%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                         | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN176E 1920x1080 381x214mm 17.2-inch          | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch          | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch           | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch          | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch           | 1         | 1.12%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 1         | 1.12%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.12%   |
| Chi Mei Optoelectronics LCD Monitor CMO1464 1366x768 309x174mm 14.0-inch  | 1         | 1.12%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch  | 1         | 1.12%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                     | 1         | 1.12%   |
| BOE LCD Monitor BOE08B5 1920x1080 309x174mm 14.0-inch                     | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 45.35%  |
| 1366x768 (WXGA)    | 19        | 22.09%  |
| 1280x800 (WXGA)    | 5         | 5.81%   |
| 1280x1024 (SXGA)   | 4         | 4.65%   |
| 1680x1050 (WSXGA+) | 3         | 3.49%   |
| 1600x900 (HD+)     | 3         | 3.49%   |
| 2560x1440 (QHD)    | 2         | 2.33%   |
| 2560x1080          | 2         | 2.33%   |
| 1440x900 (WXGA+)   | 2         | 2.33%   |
| 3840x2160 (4K)     | 1         | 1.16%   |
| 3840x1080          | 1         | 1.16%   |
| 2560x1600          | 1         | 1.16%   |
| 2160x1440          | 1         | 1.16%   |
| 1920x1200 (WUXGA)  | 1         | 1.16%   |
| 1360x768           | 1         | 1.16%   |
| 1280x720 (HD)      | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 31.46%  |
| 14      | 14        | 15.73%  |
| 17      | 10        | 11.24%  |
| 24      | 5         | 5.62%   |
| 23      | 5         | 5.62%   |
| 13      | 4         | 4.49%   |
| Unknown | 4         | 4.49%   |
| 31      | 3         | 3.37%   |
| 27      | 3         | 3.37%   |
| 19      | 3         | 3.37%   |
| 22      | 2         | 2.25%   |
| 18      | 2         | 2.25%   |
| 12      | 2         | 2.25%   |
| 48      | 1         | 1.12%   |
| 42      | 1         | 1.12%   |
| 34      | 1         | 1.12%   |
| 32      | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 52.87%  |
| 501-600     | 12        | 13.79%  |
| 351-400     | 10        | 11.49%  |
| 401-500     | 4         | 4.6%    |
| 201-300     | 4         | 4.6%    |
| Unknown     | 4         | 4.6%    |
| 601-700     | 3         | 3.45%   |
| 701-800     | 2         | 2.3%    |
| 1001-1500   | 1         | 1.15%   |
| 901-1000    | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 63        | 75.9%   |
| 16/10   | 11        | 13.25%  |
| 5/4     | 3         | 3.61%   |
| Unknown | 3         | 3.61%   |
| 6/5     | 1         | 1.2%    |
| 32/9    | 1         | 1.2%    |
| 21/9    | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 28        | 31.82%  |
| 81-90          | 17        | 19.32%  |
| 201-250        | 10        | 11.36%  |
| 121-130        | 7         | 7.95%   |
| 351-500        | 5         | 5.68%   |
| 141-150        | 4         | 4.55%   |
| Unknown        | 4         | 4.55%   |
| 301-350        | 3         | 3.41%   |
| 151-200        | 3         | 3.41%   |
| 61-70          | 2         | 2.27%   |
| 501-1000       | 2         | 2.27%   |
| 71-80          | 1         | 1.14%   |
| 251-300        | 1         | 1.14%   |
| 131-140        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 28        | 33.73%  |
| 101-120       | 23        | 27.71%  |
| 51-100        | 23        | 27.71%  |
| Unknown       | 4         | 4.82%   |
| 1-50          | 2         | 2.41%   |
| 161-240       | 2         | 2.41%   |
| More than 240 | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 82.28%  |
| 2     | 12        | 15.19%  |
| 3     | 1         | 1.27%   |
| 0     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 44        | 33.08%  |
| Intel                             | 40        | 30.08%  |
| Qualcomm Atheros                  | 17        | 12.78%  |
| Broadcom                          | 9         | 6.77%   |
| TP-Link                           | 3         | 2.26%   |
| Qualcomm Atheros Communications   | 3         | 2.26%   |
| Broadcom Limited                  | 3         | 2.26%   |
| Samsung Electronics               | 2         | 1.5%    |
| Ralink Technology                 | 2         | 1.5%    |
| Ralink                            | 2         | 1.5%    |
| Xiaomi                            | 1         | 0.75%   |
| NetGear                           | 1         | 0.75%   |
| Microsoft                         | 1         | 0.75%   |
| Marvell Technology Group          | 1         | 0.75%   |
| Huawei Technologies               | 1         | 0.75%   |
| Ericsson Business Mobile Networks | 1         | 0.75%   |
| D-Link System                     | 1         | 0.75%   |
| D-Link                            | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 26        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 6         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 3.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 4         | 2.56%   |
| Intel Wireless 7265                                                       | 4         | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 2.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 1.92%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 1.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                 | 3         | 1.92%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 1.92%   |
| Intel Wireless 3160                                                       | 3         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 3         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 1.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                 | 2         | 1.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.28%   |
| Intel Wireless 8260                                                       | 2         | 1.28%   |
| Intel I211 Gigabit Network Connection                                     | 2         | 1.28%   |
| Intel Ethernet Connection I217-V                                          | 2         | 1.28%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS)                                            | 1         | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                             | 1         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 0.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                     | 1         | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                          | 1         | 0.64%   |
| Realtek 802.11n                                                           | 1         | 0.64%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                      | 1         | 0.64%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                     | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                  | 1         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.64%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.64%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 0.64%   |
| Intel Wireless 8265 / 8275                                                | 1         | 0.64%   |
| Intel Wireless 7260                                                       | 1         | 0.64%   |
| Intel Wireless 3165                                                       | 1         | 0.64%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 0.64%   |
| Intel PRO/100 VE Network Connection                                       | 1         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.64%   |
| Intel I210 Gigabit Network Connection                                     | 1         | 0.64%   |
| Intel Ethernet controller                                                 | 1         | 0.64%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.64%   |
| Intel Ethernet Connection I218-LM                                         | 1         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                     | 1         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                                     | 1         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                      | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 36        | 42.86%  |
| Qualcomm Atheros                  | 13        | 15.48%  |
| Realtek Semiconductor             | 11        | 13.1%   |
| Broadcom                          | 6         | 7.14%   |
| TP-Link                           | 3         | 3.57%   |
| Qualcomm Atheros Communications   | 3         | 3.57%   |
| Ralink Technology                 | 2         | 2.38%   |
| Ralink                            | 2         | 2.38%   |
| Broadcom Limited                  | 2         | 2.38%   |
| NetGear                           | 1         | 1.19%   |
| Microsoft                         | 1         | 1.19%   |
| Marvell Technology Group          | 1         | 1.19%   |
| Ericsson Business Mobile Networks | 1         | 1.19%   |
| D-Link System                     | 1         | 1.19%   |
| D-Link                            | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 5.95%   |
| Intel Wireless 7265                                                       | 4         | 4.76%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 4.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 3.57%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 3.57%   |
| Intel Wireless 3160                                                       | 3         | 3.57%   |
| Intel Wi-Fi 6 AX201                                                       | 3         | 3.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 3.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 2.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.38%   |
| Intel Wireless 8260                                                       | 2         | 2.38%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.19%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.19%   |
| Realtek 802.11n                                                           | 1         | 1.19%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                      | 1         | 1.19%   |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.19%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.19%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.19%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 1.19%   |
| Intel Wireless 8265 / 8275                                                | 1         | 1.19%   |
| Intel Wireless 7260                                                       | 1         | 1.19%   |
| Intel Wireless 3165                                                       | 1         | 1.19%   |
| Intel Wi-Fi 6 AX200                                                       | 1         | 1.19%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.19%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 1.19%   |
| Intel Centrino Wireless-N 105                                             | 1         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.19%   |
| Intel Centrino Advanced-N 6235                                            | 1         | 1.19%   |
| Intel Centrino Advanced-N 6200                                            | 1         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 1         | 1.19%   |
| Ericsson Business Mobile Networks N5321 gw                                | 1         | 1.19%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]      | 1         | 1.19%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                            | 1         | 1.19%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.19%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 1         | 1.19%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                        | 1         | 1.19%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 1         | 1.19%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                             | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 37        | 52.86%  |
| Intel                 | 16        | 22.86%  |
| Qualcomm Atheros      | 8         | 11.43%  |
| Broadcom              | 4         | 5.71%   |
| Samsung Electronics   | 2         | 2.86%   |
| Xiaomi                | 1         | 1.43%   |
| Huawei Technologies   | 1         | 1.43%   |
| Broadcom Limited      | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 36.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 8.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.78%   |
| Intel Ethernet Connection I217-V                                  | 2         | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.39%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.39%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.39%   |
| Intel Ethernet controller                                         | 1         | 1.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.39%   |
| Huawei SNE-LX3                                                    | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.39%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 52.86%  |
| Ethernet | 66        | 47.14%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 60.42%  |
| Ethernet | 38        | 39.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 49        | 62.03%  |
| 1     | 27        | 34.18%  |
| 3     | 2         | 2.53%   |
| 0     | 1         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 73.75%  |
| Yes  | 21        | 26.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 50.94%  |
| Qualcomm Atheros Communications | 9         | 16.98%  |
| Realtek Semiconductor           | 4         | 7.55%   |
| Broadcom                        | 4         | 7.55%   |
| Cambridge Silicon Radio         | 3         | 5.66%   |
| Dell                            | 2         | 3.77%   |
| Marvell Semiconductor           | 1         | 1.89%   |
| Lite-On Technology              | 1         | 1.89%   |
| Foxconn / Hon Hai               | 1         | 1.89%   |
| Apple                           | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 18.87%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 13.21%  |
| Intel AX201 Bluetooth                               | 7         | 13.21%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 7.55%   |
| Realtek Bluetooth Radio                             | 3         | 5.66%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 5.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.89%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.89%   |
| Lite-On Bluetooth Radio                             | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.89%   |
| Intel AX200 Bluetooth                               | 1         | 1.89%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.89%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.89%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 1.89%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.89%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.89%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.89%   |
| Apple Bluetooth Host Controller                     | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 67        | 63.21%  |
| Nvidia              | 18        | 16.98%  |
| AMD                 | 18        | 16.98%  |
| GYROCOM C&C         | 1         | 0.94%   |
| GN Netcom           | 1         | 0.94%   |
| C-Media Electronics | 1         | 0.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 9         | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 4.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 5         | 3.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 5         | 3.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4         | 3.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 3.17%   |
| Intel Sunrise Point-LP HD Audio                                                   | 4         | 3.17%   |
| Intel Haswell-ULT HD Audio Controller                                             | 4         | 3.17%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 3.17%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 3.17%   |
| Intel 8 Series HD Audio Controller                                                | 4         | 3.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 2.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3         | 2.38%   |
| AMD FCH Azalia Controller                                                         | 3         | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2         | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                                     | 2         | 1.59%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.59%   |
| Nvidia GP106 High Definition Audio Controller                                     | 2         | 1.59%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.59%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.59%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.59%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1         | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1         | 0.79%   |
| Nvidia GF116 High Definition Audio Controller                                     | 1         | 0.79%   |
| Nvidia Audio device                                                               | 1         | 0.79%   |
| Intel USB PnP Sound Device                                                        | 1         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 1         | 0.79%   |
| Intel 200 Series PCH HD Audio                                                     | 1         | 0.79%   |
| GYROCOM C&C NuForce ÂµDAC 2 HP                                                  | 1         | 0.79%   |
| GN Netcom Jabra Evolve 65                                                         | 1         | 0.79%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1         | 0.79%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 0.79%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1         | 0.79%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1         | 0.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1         | 0.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.79%   |
| AMD Polaris 22 HDMI Audio                                                         | 1         | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                          | 1         | 0.79%   |
| AMD High Definition Audio Controller                                              | 1         | 0.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1         | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 25.42%  |
| SK Hynix            | 9         | 15.25%  |
| Unknown             | 6         | 10.17%  |
| Crucial             | 6         | 10.17%  |
| Kingston            | 5         | 8.47%   |
| Micron Technology   | 4         | 6.78%   |
| Elpida              | 3         | 5.08%   |
| Corsair             | 3         | 5.08%   |
| Ramaxel Technology  | 2         | 3.39%   |
| A-DATA Technology   | 2         | 3.39%   |
| Team                | 1         | 1.69%   |
| S                   | 1         | 1.69%   |
| Nanya Technology    | 1         | 1.69%   |
| G.Skill             | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 3.17%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 3.17%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 1.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 1.59%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 1.59%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.59%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 1.59%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.59%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 1.59%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                 | 1         | 1.59%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.59%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.59%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.59%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM 1600MT/s                   | 1         | 1.59%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| SK Hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.59%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 1.59%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 1.59%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.59%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.59%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.59%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 1.59%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.59%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.59%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                                 | 1         | 1.59%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.59%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s                  | 1         | 1.59%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 3200MT/s                  | 1         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s             | 1         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 1.59%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 1         | 1.59%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 1         | 1.59%   |
| Kingston RAM HP26D4S9S8MH-8 8192MB SODIMM DDR4 2400MT/s             | 1         | 1.59%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s                 | 1         | 1.59%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 1         | 1.59%   |
| Kingston RAM 9905469-066.A00LF 4GB SODIMM DDR3 1600MT/s             | 1         | 1.59%   |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s              | 1         | 1.59%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 1.59%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |
| Crucial RAM CT8G4SFS8266.C8FE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.59%   |
| Crucial RAM CT32G4SFD8266.C16FE 32GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s            | 1         | 1.59%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s               | 1         | 1.59%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Crucial RAM 99P5471-006.A00DT 4GB SODIMM 1067MT/s                   | 1         | 1.59%   |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                 | 1         | 1.59%   |
| Corsair RAM CMSO8GX3M1A1600C11 8GB SODIMM DDR3 1600MT/s             | 1         | 1.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 1         | 1.59%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                         | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 24        | 45.28%  |
| DDR4    | 22        | 41.51%  |
| LPDDR4  | 3         | 5.66%   |
| DDR2    | 3         | 5.66%   |
| Unknown | 1         | 1.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 75.47%  |
| DIMM         | 10        | 18.87%  |
| Row Of Chips | 3         | 5.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 35%     |
| 8192  | 20        | 33.33%  |
| 2048  | 7         | 11.67%  |
| 16384 | 6         | 10%     |
| 32768 | 3         | 5%      |
| 1024  | 3         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 30.91%  |
| 2667    | 12        | 21.82%  |
| 3200    | 6         | 10.91%  |
| 1334    | 4         | 7.27%   |
| 2400    | 3         | 5.45%   |
| 3266    | 2         | 3.64%   |
| 1333    | 2         | 3.64%   |
| 4267    | 1         | 1.82%   |
| 3600    | 1         | 1.82%   |
| 2666    | 1         | 1.82%   |
| 1067    | 1         | 1.82%   |
| 1066    | 1         | 1.82%   |
| 800     | 1         | 1.82%   |
| 667     | 1         | 1.82%   |
| 533     | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

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
| Chicony Electronics                    | 16        | 30.19%  |
| Acer                                   | 8         | 15.09%  |
| Microdia                               | 7         | 13.21%  |
| IMC Networks                           | 3         | 5.66%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.66%   |
| Sunplus Innovation Technology          | 2         | 3.77%   |
| Ricoh                                  | 2         | 3.77%   |
| Realtek Semiconductor                  | 2         | 3.77%   |
| Luxvisions Innotech Limited            | 2         | 3.77%   |
| Suyin                                  | 1         | 1.89%   |
| Silicon Motion                         | 1         | 1.89%   |
| Samsung Electronics                    | 1         | 1.89%   |
| Quanta                                 | 1         | 1.89%   |
| Microsoft                              | 1         | 1.89%   |
| Logitech                               | 1         | 1.89%   |
| Apple                                  | 1         | 1.89%   |
| Alcor Micro                            | 1         | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 5.56%   |
| Acer HD Webcam                                                             | 3         | 5.56%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.7%    |
| Microdia PC Microscope camera                                              | 2         | 3.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 3.7%    |
| Chicony Integrated Camera                                                  | 2         | 3.7%    |
| Chicony HD Webcam                                                          | 2         | 3.7%    |
| Acer Integrated Camera                                                     | 2         | 3.7%    |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.85%   |
| Sunplus HD WebCam                                                          | 1         | 1.85%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 1         | 1.85%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 1.85%   |
| Ricoh Pavilion Webcam                                                      | 1         | 1.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.85%   |
| Quanta HP High Definition 1MP Webcam                                       | 1         | 1.85%   |
| Microsoft LifeCam Rear                                                     | 1         | 1.85%   |
| Microsoft LifeCam Front                                                    | 1         | 1.85%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.85%   |
| Microdia WebCam SC-13HDL12639P                                             | 1         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_E4HD                                     | 1         | 1.85%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.85%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.85%   |
| Logitech HD Webcam C615                                                    | 1         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.85%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.85%   |
| IMC Networks Integrated Camera                                             | 1         | 1.85%   |
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
| 0     | 52        | 65%     |
| 1     | 19        | 23.75%  |
| 2     | 8         | 10%     |
| 3     | 1         | 1.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 31.43%  |
| Net/wireless          | 5         | 14.29%  |
| Graphics card         | 5         | 14.29%  |
| Chipcard              | 5         | 14.29%  |
| Storage               | 3         | 8.57%   |
| Multimedia controller | 2         | 5.71%   |
| Storage/raid          | 1         | 2.86%   |
| Modem                 | 1         | 2.86%   |
| Camera                | 1         | 2.86%   |
| Bluetooth             | 1         | 2.86%   |

