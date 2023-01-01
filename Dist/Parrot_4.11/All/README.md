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

Total: 112

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B450M-K               | Desktop     | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
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
| Radxa         | ROCK 5B                     | Soc         | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-6parrot1-amd64    | 33        | 35.87%  |
| 5.10.0-8parrot1-amd64    | 18        | 19.57%  |
| 5.14.0-9parrot1-amd64    | 13        | 14.13%  |
| 5.10.0-3parrot1-amd64    | 5         | 5.43%   |
| 5.7.0-2parrot2-amd64     | 4         | 4.35%   |
| 5.14.0-2parrot1-amd64    | 4         | 4.35%   |
| 5.10.0-5parrot1-amd64    | 4         | 4.35%   |
| 5.16.0-12parrot1-amd64   | 3         | 3.26%   |
| 5.15.0-15parrot1-amd64   | 3         | 3.26%   |
| 6.0.0-2parrot1-amd64     | 1         | 1.09%   |
| 5.6.0-2parrot1-amd64     | 1         | 1.09%   |
| 5.18.0-14parrot1-amd64   | 1         | 1.09%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 1.09%   |
| Unknown                  | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 61        | 66.3%   |
| 5.14.0  | 17        | 18.48%  |
| 5.7.0   | 4         | 4.35%   |
| 5.16.0  | 3         | 3.26%   |
| 5.15.0  | 3         | 3.26%   |
| 6.0.0   | 1         | 1.09%   |
| 5.6.0   | 1         | 1.09%   |
| 5.18.0  | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 61        | 66.3%   |
| 5.14    | 17        | 18.48%  |
| 5.7     | 4         | 4.35%   |
| 5.16    | 3         | 3.26%   |
| 5.15    | 3         | 3.26%   |
| 6.0     | 1         | 1.09%   |
| 5.6     | 1         | 1.09%   |
| 5.18    | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 90        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 53        | 58.24%  |
| KDE5    | 23        | 25.27%  |
| KDE     | 7         | 7.69%   |
| Unknown | 4         | 4.4%    |
| XFCE    | 3         | 3.3%    |
| LXDE    | 1         | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 90        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 40        | 43.48%  |
| Unknown | 27        | 29.35%  |
| TDM     | 23        | 25%     |
| SDDM    | 2         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 44        | 48.89%  |
| fr_FR   | 7         | 7.78%   |
| en_GB   | 6         | 6.67%   |
| ru_RU   | 5         | 5.56%   |
| pt_BR   | 5         | 5.56%   |
| en_AU   | 4         | 4.44%   |
| de_DE   | 4         | 4.44%   |
| Unknown | 3         | 3.33%   |
| es_ES   | 2         | 2.22%   |
| cs_CZ   | 2         | 2.22%   |
| ru_UA   | 1         | 1.11%   |
| pl_PL   | 1         | 1.11%   |
| nl_BE   | 1         | 1.11%   |
| id_ID   | 1         | 1.11%   |
| es_CO   | 1         | 1.11%   |
| en_NG   | 1         | 1.11%   |
| arn_CL  | 1         | 1.11%   |
| an_ES   | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 52        | 56.52%  |
| EFI  | 40        | 43.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 69        | 76.67%  |
| Ext4    | 13        | 14.44%  |
| Xfs     | 6         | 6.67%   |
| Overlay | 2         | 2.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 43        | 47.25%  |
| Unknown | 29        | 31.87%  |
| MBR     | 19        | 20.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 80.22%  |
| Yes       | 18        | 19.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 57.78%  |
| Yes       | 38        | 42.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 18        | 20%     |
| ASUSTek Computer    | 15        | 16.67%  |
| Dell                | 13        | 14.44%  |
| Lenovo              | 9         | 10%     |
| Acer                | 6         | 6.67%   |
| MSI                 | 5         | 5.56%   |
| Samsung Electronics | 2         | 2.22%   |
| Gigabyte Technology | 2         | 2.22%   |
| Apple               | 2         | 2.22%   |
| Alienware           | 2         | 2.22%   |
| ZOTAC               | 1         | 1.11%   |
| Wortmann AG         | 1         | 1.11%   |
| Wistron             | 1         | 1.11%   |
| Toxic               | 1         | 1.11%   |
| Toshiba             | 1         | 1.11%   |
| Timi                | 1         | 1.11%   |
| Sony                | 1         | 1.11%   |
| Radxa               | 1         | 1.11%   |
| Positivo            | 1         | 1.11%   |
| Microsoft           | 1         | 1.11%   |
| Intel               | 1         | 1.11%   |
| GPU Company         | 1         | 1.11%   |
| Gateway             | 1         | 1.11%   |
| Fujitsu             | 1         | 1.11%   |
| Eluktronics         | 1         | 1.11%   |
| ASRock              | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP ProBook 650 G1                        | 2         | 2.22%   |
| ASUS Q524UQ                              | 2         | 2.22%   |
| Wortmann AG TERRA_MOBILE_1542            | 1         | 1.11%   |
| Wistron FMVDD2A0H0                       | 1         | 1.11%   |
| Toxic GM7MQ8P                            | 1         | 1.11%   |
| Toshiba Satellite L655                   | 1         | 1.11%   |
| Timi TM1613                              | 1         | 1.11%   |
| Sony SVP1321L1EBI                        | 1         | 1.11%   |
| Samsung 350V5C/351V5C/3540VC/3440VC      | 1         | 1.11%   |
| Samsung 300E4C/300E5C/300E7C             | 1         | 1.11%   |
| Radxa ROCK 5B                            | 1         | 1.11%   |
| Positivo Q232A                           | 1         | 1.11%   |
| MSI MS-7529                              | 1         | 1.11%   |
| MSI GT60 2OC/2OD                         | 1         | 1.11%   |
| MSI GE75 Raider 10SF                     | 1         | 1.11%   |
| MSI GE73 Raider RGB 8RE                  | 1         | 1.11%   |
| MSI GE63 Raider RGB 8RE                  | 1         | 1.11%   |
| Microsoft Surface Pro 3                  | 1         | 1.11%   |
| Lenovo Yoga S740-14IIL 81RS              | 1         | 1.11%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 1.11%   |
| Lenovo ThinkPad X260 20F5S5QT00          | 1         | 1.11%   |
| Lenovo ThinkPad X250 20CL001GZA          | 1         | 1.11%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003AMC | 1         | 1.11%   |
| Lenovo ThinkPad E15 20RD0086UE           | 1         | 1.11%   |
| Lenovo ThinkBook 15 G2 ARE 20VG          | 1         | 1.11%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 1         | 1.11%   |
| Lenovo B50-80 80EW                       | 1         | 1.11%   |
| Intel NUC8i7HVK                          | 1         | 1.11%   |
| HP ZBook 15 G5                           | 1         | 1.11%   |
| HP Pavilion Notebook                     | 1         | 1.11%   |
| HP Pavilion dv7                          | 1         | 1.11%   |
| HP Pavilion dv6700                       | 1         | 1.11%   |
| HP Pavilion dv6                          | 1         | 1.11%   |
| HP Pavilion dv4                          | 1         | 1.11%   |
| HP Laptop 15s-eq1xxx                     | 1         | 1.11%   |
| HP Laptop 15-dw0xxx                      | 1         | 1.11%   |
| HP HDX PREMIUM SERIES                    | 1         | 1.11%   |
| HP ENVY x360 Convertible 15-es0xxx       | 1         | 1.11%   |
| HP EliteBook 850 G6                      | 1         | 1.11%   |
| HP EliteBook 8470p                       | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 6         | 6.67%   |
| HP Pavilion            | 5         | 5.56%   |
| Lenovo ThinkPad        | 4         | 4.44%   |
| HP EliteBook           | 3         | 3.33%   |
| Dell Latitude          | 3         | 3.33%   |
| Acer Aspire            | 3         | 3.33%   |
| HP ProBook             | 2         | 2.22%   |
| HP Laptop              | 2         | 2.22%   |
| Dell OptiPlex          | 2         | 2.22%   |
| ASUS Q524UQ            | 2         | 2.22%   |
| ASUS PRIME             | 2         | 2.22%   |
| Wortmann AG TERRA      | 1         | 1.11%   |
| Wistron FMVDD2A0H0     | 1         | 1.11%   |
| Toxic GM7MQ8P          | 1         | 1.11%   |
| Toshiba Satellite      | 1         | 1.11%   |
| Timi TM1613            | 1         | 1.11%   |
| Sony SVP1321L1EBI      | 1         | 1.11%   |
| Samsung 350V5C         | 1         | 1.11%   |
| Samsung 300E4C         | 1         | 1.11%   |
| Radxa ROCK             | 1         | 1.11%   |
| Positivo Q232A         | 1         | 1.11%   |
| MSI MS-7529            | 1         | 1.11%   |
| MSI GT60               | 1         | 1.11%   |
| MSI GE75               | 1         | 1.11%   |
| MSI GE73               | 1         | 1.11%   |
| MSI GE63               | 1         | 1.11%   |
| Microsoft Surface      | 1         | 1.11%   |
| Lenovo Yoga            | 1         | 1.11%   |
| Lenovo Y520-15IKBN     | 1         | 1.11%   |
| Lenovo ThinkBook       | 1         | 1.11%   |
| Lenovo IdeaPad         | 1         | 1.11%   |
| Lenovo B50-80          | 1         | 1.11%   |
| Intel NUC8i7HVK        | 1         | 1.11%   |
| HP ZBook               | 1         | 1.11%   |
| HP HDX                 | 1         | 1.11%   |
| HP ENVY                | 1         | 1.11%   |
| HP Compaq              | 1         | 1.11%   |
| HP All-in-One          | 1         | 1.11%   |
| HP 250                 | 1         | 1.11%   |
| GPU Company GWTN141-10 | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 12        | 13.33%  |
| 2013 | 11        | 12.22%  |
| 2016 | 9         | 10%     |
| 2011 | 9         | 10%     |
| 2020 | 8         | 8.89%   |
| 2018 | 8         | 8.89%   |
| 2021 | 5         | 5.56%   |
| 2015 | 5         | 5.56%   |
| 2012 | 5         | 5.56%   |
| 2010 | 4         | 4.44%   |
| 2017 | 3         | 3.33%   |
| 2014 | 3         | 3.33%   |
| 2008 | 3         | 3.33%   |
| 2007 | 3         | 3.33%   |
| 2009 | 1         | 1.11%   |
| 2006 | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 63        | 70%     |
| Desktop        | 22        | 24.44%  |
| System on chip | 1         | 1.11%   |
| Tablet         | 1         | 1.11%   |
| Convertible    | 1         | 1.11%   |
| Mini pc        | 1         | 1.11%   |
| All in one     | 1         | 1.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 90        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 90        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 26.67%  |
| 8.01-16.0   | 20        | 22.22%  |
| 16.01-24.0  | 19        | 21.11%  |
| 3.01-4.0    | 13        | 14.44%  |
| 32.01-64.0  | 4         | 4.44%   |
| 1.01-2.0    | 4         | 4.44%   |
| 64.01-256.0 | 3         | 3.33%   |
| 24.01-32.0  | 2         | 2.22%   |
| 2.01-3.0    | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 35        | 37.63%  |
| 2.01-3.0  | 28        | 30.11%  |
| 3.01-4.0  | 14        | 15.05%  |
| 4.01-8.0  | 12        | 12.9%   |
| 8.01-16.0 | 2         | 2.15%   |
| 0.51-1.0  | 2         | 2.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 49        | 53.85%  |
| 2      | 28        | 30.77%  |
| 3      | 10        | 10.99%  |
| 4      | 3         | 3.3%    |
| 5      | 1         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 65.93%  |
| Yes       | 31        | 34.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 81.11%  |
| No        | 17        | 18.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 90.11%  |
| No        | 9         | 9.89%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 66.67%  |
| No        | 30        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 28        | 31.11%  |
| Germany      | 8         | 8.89%   |
| France       | 6         | 6.67%   |
| Brazil       | 6         | 6.67%   |
| Spain        | 5         | 5.56%   |
| Russia       | 5         | 5.56%   |
| UK           | 3         | 3.33%   |
| Netherlands  | 3         | 3.33%   |
| Czechia      | 3         | 3.33%   |
| Australia    | 3         | 3.33%   |
| Iraq         | 2         | 2.22%   |
| Vietnam      | 1         | 1.11%   |
| Ukraine      | 1         | 1.11%   |
| Sweden       | 1         | 1.11%   |
| South Africa | 1         | 1.11%   |
| Puerto Rico  | 1         | 1.11%   |
| Poland       | 1         | 1.11%   |
| Nigeria      | 1         | 1.11%   |
| Mexico       | 1         | 1.11%   |
| Kenya        | 1         | 1.11%   |
| Indonesia    | 1         | 1.11%   |
| Hungary      | 1         | 1.11%   |
| Colombia     | 1         | 1.11%   |
| Chile        | 1         | 1.11%   |
| Canada       | 1         | 1.11%   |
| Belgium      | 1         | 1.11%   |
| Bangladesh   | 1         | 1.11%   |
| Azerbaijan   | 1         | 1.11%   |
| Algeria      | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Melbourne             | 2         | 2.17%   |
| Lyon                  | 2         | 2.17%   |
| Khabarovsk            | 2         | 2.17%   |
| Eugene                | 2         | 2.17%   |
| Dallas                | 2         | 2.17%   |
| Chicago               | 2         | 2.17%   |
| Barcelona             | 2         | 2.17%   |
| West Jordan           | 1         | 1.09%   |
| Warsaw                | 1         | 1.09%   |
| Waren                 | 1         | 1.09%   |
| Visalia               | 1         | 1.09%   |
| Veitsbronn            | 1         | 1.09%   |
| Uherské Hradiště   | 1         | 1.09%   |
| Tangerang             | 1         | 1.09%   |
| Sydney                | 1         | 1.09%   |
| Stockholm             | 1         | 1.09%   |
| St Petersburg         | 1         | 1.09%   |
| Sinntal               | 1         | 1.09%   |
| Shelbyville           | 1         | 1.09%   |
| Secaucus              | 1         | 1.09%   |
| Sao Paulo             | 1         | 1.09%   |
| Santo André          | 1         | 1.09%   |
| Santiago              | 1         | 1.09%   |
| Santa Maria           | 1         | 1.09%   |
| Sant Boi de Llobregat | 1         | 1.09%   |
| Sannois               | 1         | 1.09%   |
| Saint Paul            | 1         | 1.09%   |
| Rotterdam             | 1         | 1.09%   |
| Rialma                | 1         | 1.09%   |
| Reus                  | 1         | 1.09%   |
| Regensburg            | 1         | 1.09%   |
| Reading               | 1         | 1.09%   |
| Pretoria              | 1         | 1.09%   |
| Prague                | 1         | 1.09%   |
| Portsmouth            | 1         | 1.09%   |
| Ponce                 | 1         | 1.09%   |
| Paris                 | 1         | 1.09%   |
| Orange Park           | 1         | 1.09%   |
| Omaha                 | 1         | 1.09%   |
| New Orleans           | 1         | 1.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 14.89%  |
| WDC                 | 18        | 20     | 12.77%  |
| Seagate             | 17        | 23     | 12.06%  |
| Unknown             | 10        | 10     | 7.09%   |
| Crucial             | 10        | 13     | 7.09%   |
| Toshiba             | 9         | 10     | 6.38%   |
| Kingston            | 8         | 8      | 5.67%   |
| SanDisk             | 6         | 6      | 4.26%   |
| Hitachi             | 6         | 7      | 4.26%   |
| SK hynix            | 5         | 5      | 3.55%   |
| HGST                | 4         | 4      | 2.84%   |
| Micron Technology   | 3         | 3      | 2.13%   |
| China               | 3         | 4      | 2.13%   |
| A-DATA Technology   | 3         | 3      | 2.13%   |
| KIOXIA              | 2         | 3      | 1.42%   |
| W800SH              | 1         | 1      | 0.71%   |
| Team                | 1         | 1      | 0.71%   |
| SPCC                | 1         | 1      | 0.71%   |
| ROG                 | 1         | 1      | 0.71%   |
| PNY                 | 1         | 1      | 0.71%   |
| Phison              | 1         | 1      | 0.71%   |
| Patriot             | 1         | 1      | 0.71%   |
| LITEONIT            | 1         | 1      | 0.71%   |
| Lexar               | 1         | 1      | 0.71%   |
| Intenso             | 1         | 1      | 0.71%   |
| Intel               | 1         | 1      | 0.71%   |
| HS-SSD-C100         | 1         | 1      | 0.71%   |
| FORESEE             | 1         | 1      | 0.71%   |
| Corsair             | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |
| AMD                 | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown SD/MMC/MS PRO 64GB           | 4         | 2.65%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 3         | 1.99%   |
| SanDisk SSD PLUS 1000GB              | 3         | 1.99%   |
| Samsung SSD 860 EVO 500GB            | 3         | 1.99%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.99%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.99%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 1.32%   |
| Toshiba DT01ACA100 1TB               | 2         | 1.32%   |
| Seagate Expansion 4TB                | 2         | 1.32%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.32%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.66%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.66%   |
| WDC WDBNCE2500PNC 250GB SSD          | 1         | 0.66%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.66%   |
| WDC WD800BEVS-22RST0 80GB            | 1         | 0.66%   |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 0.66%   |
| WDC WD5000AACS-00ZUB0 500GB          | 1         | 0.66%   |
| WDC WD3200LPVX-60V0TT0 320GB         | 1         | 0.66%   |
| WDC WD3200LPVX-00V0TT0 320GB         | 1         | 0.66%   |
| WDC WD2500BPVT-00JJ5T0 250GB         | 1         | 0.66%   |
| WDC WD10SPZX-17Z10T1 1TB             | 1         | 0.66%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.66%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 0.66%   |
| WDC WD10EARS-00Y5B1 1TB              | 1         | 0.66%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.66%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB | 1         | 0.66%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.66%   |
| W800SH 512GB SSD                     | 1         | 0.66%   |
| Unknown Y016B  16GB                  | 1         | 0.66%   |
| Unknown xD/SD/M.S.                   | 1         | 0.66%   |
| Unknown SS16G  16GB                  | 1         | 0.66%   |
| Unknown SS08G  8GB                   | 1         | 0.66%   |
| Unknown SDU1  64GB                   | 1         | 0.66%   |
| Unknown MMC Card  128GB              | 1         | 0.66%   |
| Toshiba THNSNH128G8NT 128GB SSD      | 1         | 0.66%   |
| Toshiba THNSNF128GMCS 128GB SSD      | 1         | 0.66%   |
| Toshiba Q300 480GB SSD               | 1         | 0.66%   |
| Toshiba MQ01ABD100V -63 1TB          | 1         | 0.66%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.66%   |
| Toshiba MK7575GSX 752GB              | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 23     | 32.69%  |
| WDC                 | 12        | 13     | 23.08%  |
| Toshiba             | 6         | 6      | 11.54%  |
| Hitachi             | 6         | 7      | 11.54%  |
| Unknown             | 4         | 4      | 7.69%   |
| HGST                | 4         | 4      | 7.69%   |
| Samsung Electronics | 3         | 4      | 5.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 16.98%  |
| Crucial             | 9         | 12     | 16.98%  |
| Kingston            | 6         | 6      | 11.32%  |
| SanDisk             | 5         | 5      | 9.43%   |
| WDC                 | 3         | 3      | 5.66%   |
| Toshiba             | 3         | 4      | 5.66%   |
| China               | 3         | 4      | 5.66%   |
| W800SH              | 1         | 1      | 1.89%   |
| Team                | 1         | 1      | 1.89%   |
| SPCC                | 1         | 1      | 1.89%   |
| PNY                 | 1         | 1      | 1.89%   |
| Patriot             | 1         | 1      | 1.89%   |
| Micron Technology   | 1         | 1      | 1.89%   |
| LITEONIT            | 1         | 1      | 1.89%   |
| Intenso             | 1         | 1      | 1.89%   |
| Intel               | 1         | 1      | 1.89%   |
| HS-SSD-C100         | 1         | 1      | 1.89%   |
| FORESEE             | 1         | 1      | 1.89%   |
| Corsair             | 1         | 1      | 1.89%   |
| Apple               | 1         | 1      | 1.89%   |
| AMD                 | 1         | 1      | 1.89%   |
| A-DATA Technology   | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 45        | 59     | 37.19%  |
| HDD     | 41        | 61     | 33.88%  |
| NVMe    | 28        | 31     | 23.14%  |
| MMC     | 5         | 6      | 4.13%   |
| Unknown | 2         | 2      | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 111    | 62.16%  |
| NVMe | 28        | 31     | 25.23%  |
| SAS  | 9         | 11     | 8.11%   |
| MMC  | 5         | 6      | 4.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 78     | 56.04%  |
| 0.51-1.0   | 31        | 33     | 34.07%  |
| 1.01-2.0   | 6         | 6      | 6.59%   |
| 3.01-4.0   | 3         | 3      | 3.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 26.09%  |
| 101-250        | 23        | 25%     |
| 501-1000       | 13        | 14.13%  |
| 1001-2000      | 12        | 13.04%  |
| Unknown        | 8         | 8.7%    |
| 51-100         | 5         | 5.43%   |
| 2001-3000      | 4         | 4.35%   |
| More than 3000 | 2         | 2.17%   |
| 21-50          | 1         | 1.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 21        | 22.58%  |
| 51-100    | 20        | 21.51%  |
| 101-250   | 15        | 16.13%  |
| 1-20      | 13        | 13.98%  |
| 251-500   | 11        | 11.83%  |
| Unknown   | 8         | 8.6%    |
| 501-1000  | 3         | 3.23%   |
| 1001-2000 | 2         | 2.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB                         | 1         | 1      | 5.56%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.56%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 5.56%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 5.56%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 5.56%   |
| Seagate ST3250824AS 250GB                           | 1         | 1      | 5.56%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 5.56%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 5.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 5.56%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 1         | 1      | 5.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 5.56%   |
| Samsung Electronics HD154UI 1TB                     | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 5.56%   |
| Hitachi HUA722020ALA331 2TB                         | 1         | 1      | 5.56%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 5.56%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 35.29%  |
| WDC                 | 2         | 2      | 11.76%  |
| SanDisk             | 2         | 2      | 11.76%  |
| Samsung Electronics | 2         | 2      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| Toshiba             | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 50%     |
| WDC                 | 2         | 2      | 16.67%  |
| Hitachi             | 2         | 2      | 16.67%  |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 13     | 66.67%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 1         | 1      | 6.67%   |

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
| Works    | 56        | 74     | 50.45%  |
| Detected | 40        | 66     | 36.04%  |
| Malfunc  | 14        | 18     | 12.61%  |
| Failed   | 1         | 1      | 0.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 71        | 61.74%  |
| AMD                         | 12        | 10.43%  |
| Samsung Electronics         | 10        | 8.7%    |
| SK hynix                    | 5         | 4.35%   |
| SanDisk                     | 4         | 3.48%   |
| Micron Technology           | 2         | 1.74%   |
| KIOXIA                      | 2         | 1.74%   |
| Kingston Technology Company | 2         | 1.74%   |
| VIA Technologies            | 1         | 0.87%   |
| Silicon Motion              | 1         | 0.87%   |
| Realtek Semiconductor       | 1         | 0.87%   |
| Phison Electronics          | 1         | 0.87%   |
| Micron/Crucial Technology   | 1         | 0.87%   |
| JMicron Technology          | 1         | 0.87%   |
| ADATA Technology            | 1         | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 3.13%   |
| SK hynix BC511                                                                 | 3         | 2.34%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 2.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 2.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 2.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.56%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.56%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.56%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.56%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1         | 0.78%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.78%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.78%   |
| Samsung Apple PCIe SSD                                                         | 1         | 0.78%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1         | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.78%   |
| Micron/Crucial NVMe Controller                                                 | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 71        | 61.21%  |
| NVMe | 28        | 24.14%  |
| IDE  | 9         | 7.76%   |
| RAID | 8         | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 77        | 85.56%  |
| AMD    | 13        | 14.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 3.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 3.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 2.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.22%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 2.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.22%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 2.22%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.22%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.22%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1         | 1.11%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 1.11%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.11%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 1.11%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 1.11%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1         | 1.11%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i7-8809G CPU @ 3.10GHz           | 1         | 1.11%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.11%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.11%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 1.11%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.11%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.11%   |
| Intel Core i7-4558U CPU @ 2.80GHz           | 1         | 1.11%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.11%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 1.11%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.11%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.11%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.11%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 1.11%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 1         | 1.11%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.11%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.11%   |
| Intel Core i5-6400T CPU @ 2.20GHz           | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 26        | 28.89%  |
| Intel Core i5           | 26        | 28.89%  |
| Other                   | 6         | 6.67%   |
| Intel Core i3           | 4         | 4.44%   |
| Intel Core 2 Duo        | 3         | 3.33%   |
| AMD Ryzen 5             | 3         | 3.33%   |
| Intel Pentium Silver    | 2         | 2.22%   |
| Intel Core 2 Quad       | 2         | 2.22%   |
| AMD Ryzen 3             | 2         | 2.22%   |
| AMD FX                  | 2         | 2.22%   |
| Intel Xeon              | 1         | 1.11%   |
| Intel Pentium Dual-Core | 1         | 1.11%   |
| Intel Pentium Dual      | 1         | 1.11%   |
| Intel Pentium           | 1         | 1.11%   |
| Intel Core M            | 1         | 1.11%   |
| Intel Core 2            | 1         | 1.11%   |
| Intel Celeron           | 1         | 1.11%   |
| Intel Atom              | 1         | 1.11%   |
| AMD Ryzen Threadripper  | 1         | 1.11%   |
| AMD Ryzen 7             | 1         | 1.11%   |
| AMD E1                  | 1         | 1.11%   |
| AMD A8                  | 1         | 1.11%   |
| AMD A6                  | 1         | 1.11%   |
| AMD A4                  | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 40        | 44.44%  |
| 4      | 34        | 37.78%  |
| 6      | 9         | 10%     |
| 8      | 4         | 4.44%   |
| 12     | 1         | 1.11%   |
| 3      | 1         | 1.11%   |
| 1      | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 90        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 66        | 73.33%  |
| 1      | 24        | 26.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 90        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 35.87%  |
| 0x206a7    | 6         | 6.52%   |
| 0x306c3    | 5         | 5.43%   |
| 0x906e9    | 4         | 4.35%   |
| 0x806ec    | 4         | 4.35%   |
| 0x806c1    | 4         | 4.35%   |
| 0xa0652    | 3         | 3.26%   |
| 0x306a9    | 3         | 3.26%   |
| 0x1067a    | 3         | 3.26%   |
| 0x706e5    | 2         | 2.17%   |
| 0x406e3    | 2         | 2.17%   |
| 0x40651    | 2         | 2.17%   |
| 0x306d4    | 2         | 2.17%   |
| 0x08600106 | 2         | 2.17%   |
| 0x08108109 | 2         | 2.17%   |
| 0x06000852 | 2         | 2.17%   |
| 0x906ed    | 1         | 1.09%   |
| 0x806d1    | 1         | 1.09%   |
| 0x806c2    | 1         | 1.09%   |
| 0x706a8    | 1         | 1.09%   |
| 0x706a1    | 1         | 1.09%   |
| 0x6fd      | 1         | 1.09%   |
| 0x6f6      | 1         | 1.09%   |
| 0x506e3    | 1         | 1.09%   |
| 0x30678    | 1         | 1.09%   |
| 0x20655    | 1         | 1.09%   |
| 0x0a201016 | 1         | 1.09%   |
| 0x06006705 | 1         | 1.09%   |
| 0x0600111f | 1         | 1.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 16.67%  |
| Haswell       | 10        | 11.11%  |
| SandyBridge   | 8         | 8.89%   |
| Skylake       | 7         | 7.78%   |
| IvyBridge     | 7         | 7.78%   |
| TigerLake     | 5         | 5.56%   |
| Piledriver    | 4         | 4.44%   |
| Penryn        | 4         | 4.44%   |
| Core          | 4         | 4.44%   |
| CometLake     | 4         | 4.44%   |
| Broadwell     | 4         | 4.44%   |
| IceLake       | 3         | 3.33%   |
| Zen+          | 2         | 2.22%   |
| Zen 2         | 2         | 2.22%   |
| Zen           | 2         | 2.22%   |
| Westmere      | 2         | 2.22%   |
| Silvermont    | 2         | 2.22%   |
| Goldmont plus | 2         | 2.22%   |
| Zen 3         | 1         | 1.11%   |
| Jaguar        | 1         | 1.11%   |
| Excavator     | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 56.52%  |
| Nvidia | 30        | 26.09%  |
| AMD    | 20        | 17.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 5.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 4.24%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 4.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 3.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 4         | 3.39%   |
| Intel HD Graphics 5500                                                    | 3         | 2.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 2         | 1.69%   |
| Nvidia GM107 [GeForce 940MX]                                              | 2         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.69%   |
| Intel HD Graphics 630                                                     | 2         | 1.69%   |
| Intel GeminiLake [UHD Graphics 605]                                       | 2         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 1.69%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 1.69%   |
| AMD Renoir                                                                | 2         | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.69%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.85%   |
| Nvidia TU117M                                                             | 1         | 0.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                   | 1         | 0.85%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                     | 1         | 0.85%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                     | 1         | 0.85%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.85%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                     | 1         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1         | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1         | 0.85%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.85%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.85%   |
| Nvidia GK106M [GeForce GTX 770M]                                          | 1         | 0.85%   |
| Nvidia GK104 [GeForce GTX 770]                                            | 1         | 0.85%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 45.56%  |
| Intel + Nvidia | 17        | 18.89%  |
| 1 x AMD        | 14        | 15.56%  |
| 1 x Nvidia     | 12        | 13.33%  |
| Intel + AMD    | 5         | 5.56%   |
| AMD + Nvidia   | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 81        | 90%     |
| Proprietary | 9         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 68.13%  |
| 1.01-2.0   | 8         | 8.79%   |
| 0.51-1.0   | 7         | 7.69%   |
| 3.01-4.0   | 6         | 6.59%   |
| 7.01-8.0   | 3         | 3.3%    |
| 0.01-0.5   | 3         | 3.3%    |
| 5.01-6.0   | 1         | 1.1%    |
| 2.01-3.0   | 1         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 14        | 13.59%  |
| Samsung Electronics     | 13        | 12.62%  |
| LG Display              | 13        | 12.62%  |
| BOE                     | 12        | 11.65%  |
| Chimei Innolux          | 9         | 8.74%   |
| Dell                    | 7         | 6.8%    |
| Hewlett-Packard         | 4         | 3.88%   |
| Chi Mei Optoelectronics | 4         | 3.88%   |
| Goldstar                | 3         | 2.91%   |
| Sceptre Tech            | 2         | 1.94%   |
| Philips                 | 2         | 1.94%   |
| BenQ                    | 2         | 1.94%   |
| Apple                   | 2         | 1.94%   |
| AOC                     | 2         | 1.94%   |
| Acer                    | 2         | 1.94%   |
| Vizio                   | 1         | 0.97%   |
| Toshiba                 | 1         | 0.97%   |
| STA                     | 1         | 0.97%   |
| Sony                    | 1         | 0.97%   |
| Sharp                   | 1         | 0.97%   |
| Sceptre                 | 1         | 0.97%   |
| Panasonic               | 1         | 0.97%   |
| NEC Computers           | 1         | 0.97%   |
| Lenovo                  | 1         | 0.97%   |
| Insignia                | 1         | 0.97%   |
| AUS                     | 1         | 0.97%   |
| Ancor Communications    | 1         | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.92%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                    | 1         | 0.96%   |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                       | 1         | 0.96%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.96%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 1         | 0.96%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.96%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.96%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch        | 1         | 0.96%   |
| Sceptre LCD Monitor P30 2560x1080                                     | 1         | 0.96%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SAM0F3D 1360x768 522x293mm 23.6-inch  | 1         | 0.96%   |
| Samsung Electronics LCD Monitor SAM03FE 1280x720                      | 1         | 0.96%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch    | 1         | 0.96%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 0.96%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1         | 0.96%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 1         | 0.96%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.96%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 1         | 0.96%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 0.96%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0683 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD066D 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.96%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 1         | 0.96%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch          | 1         | 0.96%   |
| Lenovo LEN T32h-20 LEN61F1 2560x1440 698x393mm 31.5-inch              | 1         | 0.96%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch           | 1         | 0.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 49.49%  |
| 1366x768 (WXGA)    | 20        | 20.2%   |
| 1280x800 (WXGA)    | 5         | 5.05%   |
| 1280x1024 (SXGA)   | 4         | 4.04%   |
| 2560x1440 (QHD)    | 3         | 3.03%   |
| 2560x1080          | 3         | 3.03%   |
| 1680x1050 (WSXGA+) | 3         | 3.03%   |
| 1600x900 (HD+)     | 3         | 3.03%   |
| 1440x900 (WXGA+)   | 2         | 2.02%   |
| 3840x2160 (4K)     | 1         | 1.01%   |
| 3840x1080          | 1         | 1.01%   |
| 2560x1600          | 1         | 1.01%   |
| 2160x1440          | 1         | 1.01%   |
| 1920x1200 (WUXGA)  | 1         | 1.01%   |
| 1360x768           | 1         | 1.01%   |
| 1280x720 (HD)      | 1         | 1.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 30.77%  |
| 14      | 15        | 14.42%  |
| 17      | 10        | 9.62%   |
| 13      | 7         | 6.73%   |
| 24      | 6         | 5.77%   |
| 23      | 5         | 4.81%   |
| 31      | 4         | 3.85%   |
| 27      | 4         | 3.85%   |
| Unknown | 4         | 3.85%   |
| 19      | 3         | 2.88%   |
| 32      | 2         | 1.92%   |
| 22      | 2         | 1.92%   |
| 21      | 2         | 1.92%   |
| 18      | 2         | 1.92%   |
| 12      | 2         | 1.92%   |
| 48      | 1         | 0.96%   |
| 42      | 1         | 0.96%   |
| 34      | 1         | 0.96%   |
| 29      | 1         | 0.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 50.98%  |
| 501-600     | 14        | 13.73%  |
| 351-400     | 10        | 9.8%    |
| 401-500     | 6         | 5.88%   |
| 201-300     | 6         | 5.88%   |
| 601-700     | 5         | 4.9%    |
| Unknown     | 4         | 3.92%   |
| 701-800     | 3         | 2.94%   |
| 1001-1500   | 1         | 0.98%   |
| 901-1000    | 1         | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 77.89%  |
| 16/10   | 11        | 11.58%  |
| 5/4     | 3         | 3.16%   |
| Unknown | 3         | 3.16%   |
| 21/9    | 2         | 2.11%   |
| 6/5     | 1         | 1.05%   |
| 32/9    | 1         | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 31.07%  |
| 81-90          | 19        | 18.45%  |
| 201-250        | 12        | 11.65%  |
| 351-500        | 7         | 6.8%    |
| 121-130        | 7         | 6.8%    |
| 301-350        | 5         | 4.85%   |
| 151-200        | 4         | 3.88%   |
| 141-150        | 4         | 3.88%   |
| Unknown        | 4         | 3.88%   |
| 71-80          | 3         | 2.91%   |
| 61-70          | 2         | 1.94%   |
| 501-1000       | 2         | 1.94%   |
| 251-300        | 1         | 0.97%   |
| 131-140        | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 33.67%  |
| 51-100        | 28        | 28.57%  |
| 101-120       | 26        | 26.53%  |
| 161-240       | 4         | 4.08%   |
| Unknown       | 4         | 4.08%   |
| 1-50          | 2         | 2.04%   |
| More than 240 | 1         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 81.11%  |
| 2     | 14        | 15.56%  |
| 3     | 2         | 2.22%   |
| 0     | 1         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 49        | 33.33%  |
| Intel                             | 47        | 31.97%  |
| Qualcomm Atheros                  | 17        | 11.56%  |
| Broadcom                          | 9         | 6.12%   |
| TP-Link                           | 3         | 2.04%   |
| Qualcomm Atheros Communications   | 3         | 2.04%   |
| Broadcom Limited                  | 3         | 2.04%   |
| Samsung Electronics               | 2         | 1.36%   |
| Ralink Technology                 | 2         | 1.36%   |
| Ralink                            | 2         | 1.36%   |
| Xiaomi                            | 1         | 0.68%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.68%   |
| NetGear                           | 1         | 0.68%   |
| Microsoft                         | 1         | 0.68%   |
| Marvell Technology Group          | 1         | 0.68%   |
| Lenovo                            | 1         | 0.68%   |
| Huawei Technologies               | 1         | 0.68%   |
| Ericsson Business Mobile Networks | 1         | 0.68%   |
| D-Link System                     | 1         | 0.68%   |
| D-Link                            | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 17.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.89%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.31%   |
| Intel Wireless 7265                                               | 4         | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 1.73%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 3         | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.73%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 1.73%   |
| Intel Wireless 8260                                               | 3         | 1.73%   |
| Intel Wireless 3160                                               | 3         | 1.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.16%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2         | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.16%   |
| Intel Wireless 7260                                               | 2         | 1.16%   |
| Intel Wireless 3165                                               | 2         | 1.16%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.16%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.58%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.58%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 47.25%  |
| Qualcomm Atheros                | 13        | 14.29%  |
| Realtek Semiconductor           | 12        | 13.19%  |
| Broadcom                        | 6         | 6.59%   |
| TP-Link                         | 3         | 3.3%    |
| Qualcomm Atheros Communications | 3         | 3.3%    |
| Ralink Technology               | 2         | 2.2%    |
| Ralink                          | 2         | 2.2%    |
| Broadcom Limited                | 2         | 2.2%    |
| NetGear                         | 1         | 1.1%    |
| Microsoft                       | 1         | 1.1%    |
| Marvell Technology Group        | 1         | 1.1%    |
| D-Link System                   | 1         | 1.1%    |
| D-Link                          | 1         | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 5         | 5.49%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 5.49%   |
| Intel Wireless 7265                                                       | 4         | 4.4%    |
| Intel Comet Lake PCH CNVi WiFi                                            | 4         | 4.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                              | 3         | 3.3%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                       | 3         | 3.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 3         | 3.3%    |
| Qualcomm Atheros AR9271 802.11n                                           | 3         | 3.3%    |
| Intel Wireless 8260                                                       | 3         | 3.3%    |
| Intel Wireless 3160                                                       | 3         | 3.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 3         | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                           | 3         | 3.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 2         | 2.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 2.2%    |
| Intel Wireless 7260                                                       | 2         | 2.2%    |
| Intel Wireless 3165                                                       | 2         | 2.2%    |
| Intel Wi-Fi 6 AX200                                                       | 2         | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 2         | 2.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                         | 2         | 2.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.1%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                   | 1         | 1.1%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                     | 1         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                | 1         | 1.1%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                      | 1         | 1.1%    |
| Ralink RT2500 Wireless 802.11bg                                           | 1         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)            | 1         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 1.1%    |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.1%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                         | 1         | 1.1%    |
| Intel Wireless 8265 / 8275                                                | 1         | 1.1%    |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                     | 1         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 1         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 53.85%  |
| Intel                 | 18        | 23.08%  |
| Qualcomm Atheros      | 8         | 10.26%  |
| Broadcom              | 4         | 5.13%   |
| Samsung Electronics   | 2         | 2.56%   |
| Xiaomi                | 1         | 1.28%   |
| Lenovo                | 1         | 1.28%   |
| Huawei Technologies   | 1         | 1.28%   |
| Broadcom Limited      | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 38.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 7.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 2         | 2.5%    |
| Intel Ethernet Connection I217-V                                  | 2         | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.25%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.25%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 1.25%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.25%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.25%   |
| Intel Ethernet controller                                         | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.25%   |
| Huawei STK-L21                                                    | 1         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.25%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.25%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1         | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.25%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 52.23%  |
| Ethernet | 73        | 46.5%   |
| Modem    | 1         | 0.64%   |
| Unknown  | 1         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 64.65%  |
| Ethernet | 35        | 35.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 53        | 58.89%  |
| 1     | 34        | 37.78%  |
| 3     | 2         | 2.22%   |
| 0     | 1         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 74.73%  |
| Yes  | 23        | 25.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 55%     |
| Qualcomm Atheros Communications | 9         | 15%     |
| Realtek Semiconductor           | 5         | 8.33%   |
| Broadcom                        | 4         | 6.67%   |
| Cambridge Silicon Radio         | 3         | 5%      |
| Dell                            | 2         | 3.33%   |
| Marvell Semiconductor           | 1         | 1.67%   |
| Lite-On Technology              | 1         | 1.67%   |
| Foxconn / Hon Hai               | 1         | 1.67%   |
| Apple                           | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 20%     |
| Intel AX201 Bluetooth                               | 9         | 15%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 13.33%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 6.67%   |
| Realtek Bluetooth Radio                             | 3         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 3.33%   |
| Intel AX200 Bluetooth                               | 2         | 3.33%   |
| Qualcomm Atheros Bluetooth                          | 1         | 1.67%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.67%   |
| Lite-On Bluetooth Radio                             | 1         | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.67%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.67%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.67%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 1.67%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.67%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.67%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.67%   |
| Apple Bluetooth Host Controller                     | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 76        | 63.33%  |
| Nvidia              | 20        | 16.67%  |
| AMD                 | 20        | 16.67%  |
| Lenovo              | 1         | 0.83%   |
| GYROCOM C&C         | 1         | 0.83%   |
| GN Netcom           | 1         | 0.83%   |
| C-Media Electronics | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 6.38%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 3.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 2.84%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.84%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.84%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 2.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 2.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 2.13%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.42%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.42%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.42%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 1.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 1.42%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.71%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.71%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 25.71%  |
| SK hynix            | 10        | 14.29%  |
| Kingston            | 7         | 10%     |
| Crucial             | 7         | 10%     |
| Unknown             | 6         | 8.57%   |
| Micron Technology   | 6         | 8.57%   |
| Elpida              | 3         | 4.29%   |
| Corsair             | 3         | 4.29%   |
| Team                | 2         | 2.86%   |
| Ramaxel Technology  | 2         | 2.86%   |
| A-DATA Technology   | 2         | 2.86%   |
| S                   | 1         | 1.43%   |
| Nanya Technology    | 1         | 1.43%   |
| G.Skill             | 1         | 1.43%   |
| AMD                 | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 1.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 1.33%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 1.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 1.33%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 1.33%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 1.33%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.33%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.33%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 1.33%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK hynix RAM H9HCNNNBKMALHR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.33%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                    | 1         | 1.33%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 1.33%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.33%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 1         | 1.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 1         | 1.33%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                              | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 44.44%  |
| DDR3    | 27        | 42.86%  |
| LPDDR4  | 3         | 4.76%   |
| DDR2    | 3         | 4.76%   |
| LPDDR3  | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 73.02%  |
| DIMM         | 13        | 20.63%  |
| Row Of Chips | 4         | 6.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 38.57%  |
| 4096  | 22        | 31.43%  |
| 16384 | 8         | 11.43%  |
| 2048  | 7         | 10%     |
| 32768 | 3         | 4.29%   |
| 1024  | 3         | 4.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 28.36%  |
| 2667    | 14        | 20.9%   |
| 3200    | 9         | 13.43%  |
| 1334    | 4         | 5.97%   |
| 2400    | 3         | 4.48%   |
| 3266    | 2         | 2.99%   |
| 2133    | 2         | 2.99%   |
| 1333    | 2         | 2.99%   |
| 8400    | 1         | 1.49%   |
| 4267    | 1         | 1.49%   |
| 3600    | 1         | 1.49%   |
| 3000    | 1         | 1.49%   |
| 2666    | 1         | 1.49%   |
| 1867    | 1         | 1.49%   |
| 1067    | 1         | 1.49%   |
| 1066    | 1         | 1.49%   |
| 800     | 1         | 1.49%   |
| 667     | 1         | 1.49%   |
| 533     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

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
| Chicony Electronics                    | 17        | 28.81%  |
| Acer                                   | 8         | 13.56%  |
| Microdia                               | 7         | 11.86%  |
| IMC Networks                           | 4         | 6.78%   |
| Sunplus Innovation Technology          | 3         | 5.08%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.08%   |
| Ricoh                                  | 2         | 3.39%   |
| Realtek Semiconductor                  | 2         | 3.39%   |
| Quanta                                 | 2         | 3.39%   |
| Luxvisions Innotech Limited            | 2         | 3.39%   |
| Syntek                                 | 1         | 1.69%   |
| Suyin                                  | 1         | 1.69%   |
| Silicon Motion                         | 1         | 1.69%   |
| Samsung Electronics                    | 1         | 1.69%   |
| Microsoft                              | 1         | 1.69%   |
| Logitech                               | 1         | 1.69%   |
| Creative Technology                    | 1         | 1.69%   |
| Apple                                  | 1         | 1.69%   |
| Alcor Micro                            | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB2.0 HD UVC WebCam                        | 3         | 5%      |
| Acer HD Webcam                                      | 3         | 5%      |
| Realtek Integrated_Webcam_HD                        | 2         | 3.33%   |
| Microdia PC Microscope camera                       | 2         | 3.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 3.33%   |
| IMC Networks Integrated Camera                      | 2         | 3.33%   |
| Chicony Integrated Camera                           | 2         | 3.33%   |
| Chicony HD Webcam                                   | 2         | 3.33%   |
| Acer Integrated Camera                              | 2         | 3.33%   |
| Syntek Integrated Camera                            | 1         | 1.67%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.67%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.67%   |
| Sunplus HD WebCam                                   | 1         | 1.67%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 1.67%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 1.67%   |
| Ricoh Pavilion Webcam                               | 1         | 1.67%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 1         | 1.67%   |
| Quanta HP High Definition 1MP Webcam                | 1         | 1.67%   |
| Quanta HP HD Camera                                 | 1         | 1.67%   |
| Microsoft LifeCam Rear                              | 1         | 1.67%   |
| Microsoft LifeCam Front                             | 1         | 1.67%   |
| Microdia Webcam Vitade AF                           | 1         | 1.67%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.67%   |
| Microdia Integrated Webcam HD                       | 1         | 1.67%   |
| Logitech HD Webcam C615                             | 1         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.67%   |
| IMC Networks Integrated Webcam                      | 1         | 1.67%   |
| Creative Live! Cam Sync HD [VF0770]                 | 1         | 1.67%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 1.67%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.67%   |
| Chicony USB2.0 Camera                               | 1         | 1.67%   |
| Chicony USB 2.0 Camera                              | 1         | 1.67%   |
| Chicony HP Webcam                                   | 1         | 1.67%   |
| Chicony HP TrueVision HD                            | 1         | 1.67%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 1.67%   |
| Chicony HP HD Camera                                | 1         | 1.67%   |
| Chicony HD User Facing                              | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
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


| Model                                                                      | Computers | Percent |
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
| 0     | 60        | 66.67%  |
| 1     | 21        | 23.33%  |
| 2     | 8         | 8.89%   |
| 3     | 1         | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 34.21%  |
| Net/wireless          | 6         | 15.79%  |
| Graphics card         | 5         | 13.16%  |
| Chipcard              | 5         | 13.16%  |
| Storage               | 3         | 7.89%   |
| Multimedia controller | 2         | 5.26%   |
| Storage/raid          | 1         | 2.63%   |
| Net/ethernet          | 1         | 2.63%   |
| Modem                 | 1         | 2.63%   |
| Camera                | 1         | 2.63%   |

