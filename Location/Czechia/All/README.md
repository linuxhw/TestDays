Linux in Czechia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Czechia/Desktop/README.md) and [notebooks](/Location/Czechia/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 3370

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [a64852fe4a](https://linux-hardware.org/?probe=a64852fe4a) | Feb 02, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [0155afe6f3](https://linux-hardware.org/?probe=0155afe6f3) | Feb 02, 2024 |
| Dell          | Inspiron 7566               | Notebook    | [e8f24dd8cf](https://linux-hardware.org/?probe=e8f24dd8cf) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a3277bc7da](https://linux-hardware.org/?probe=a3277bc7da) | Jan 31, 2024 |
| HP            | 802F                        | Desktop     | [7d597a977d](https://linux-hardware.org/?probe=7d597a977d) | Jan 30, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [9e4c4acd0d](https://linux-hardware.org/?probe=9e4c4acd0d) | Jan 30, 2024 |
| ASUSTek       | UX550VD                     | Notebook    | [3b742650db](https://linux-hardware.org/?probe=3b742650db) | Jan 29, 2024 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [148a4486f3](https://linux-hardware.org/?probe=148a4486f3) | Jan 29, 2024 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [856669283d](https://linux-hardware.org/?probe=856669283d) | Jan 29, 2024 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [6304caec55](https://linux-hardware.org/?probe=6304caec55) | Jan 29, 2024 |
| MSI           | 880GMS-E35                  | Desktop     | [0216fb4b4f](https://linux-hardware.org/?probe=0216fb4b4f) | Jan 28, 2024 |
| Samsung       | 300V3A                      | Notebook    | [53e3665790](https://linux-hardware.org/?probe=53e3665790) | Jan 27, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [9cee6b0a5b](https://linux-hardware.org/?probe=9cee6b0a5b) | Jan 27, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4b4af4b9b4](https://linux-hardware.org/?probe=4b4af4b9b4) | Jan 26, 2024 |
| Dell          | XPS 9320                    | Notebook    | [ed6a1f51f5](https://linux-hardware.org/?probe=ed6a1f51f5) | Jan 26, 2024 |
| HP            | 2000                        | Notebook    | [f1e38c4df2](https://linux-hardware.org/?probe=f1e38c4df2) | Jan 25, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [9ad67b6f8d](https://linux-hardware.org/?probe=9ad67b6f8d) | Jan 23, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [04f0c2393d](https://linux-hardware.org/?probe=04f0c2393d) | Jan 23, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [61f8c8c9e0](https://linux-hardware.org/?probe=61f8c8c9e0) | Jan 22, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [3c8308af97](https://linux-hardware.org/?probe=3c8308af97) | Jan 22, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [79cf6e6101](https://linux-hardware.org/?probe=79cf6e6101) | Jan 22, 2024 |
| Dell          | Latitude 5440               | Notebook    | [4ac53b51b3](https://linux-hardware.org/?probe=4ac53b51b3) | Jan 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5a444c3b35](https://linux-hardware.org/?probe=5a444c3b35) | Jan 22, 2024 |
| ASUSTek       | P7P55D                      | Desktop     | [8d8fab9b27](https://linux-hardware.org/?probe=8d8fab9b27) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d248b6e5a9](https://linux-hardware.org/?probe=d248b6e5a9) | Jan 21, 2024 |
| Lenovo        | G550 20023                  | Notebook    | [577e991c77](https://linux-hardware.org/?probe=577e991c77) | Jan 21, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [77a68d33db](https://linux-hardware.org/?probe=77a68d33db) | Jan 20, 2024 |
| Dell          | Latitude E6420              | Notebook    | [b0d535026a](https://linux-hardware.org/?probe=b0d535026a) | Jan 19, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [008c387c2b](https://linux-hardware.org/?probe=008c387c2b) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | Notebook    | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| HP            | 530 Notebook PC(GU324AA#... | Notebook    | [785d324acb](https://linux-hardware.org/?probe=785d324acb) | Jan 18, 2024 |
| Dell          | Latitude 5591               | Notebook    | [b91323a39b](https://linux-hardware.org/?probe=b91323a39b) | Jan 17, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [e3c95c6c18](https://linux-hardware.org/?probe=e3c95c6c18) | Jan 17, 2024 |
| Gigabyte      | EP35-DS3                    | Desktop     | [18f8b43855](https://linux-hardware.org/?probe=18f8b43855) | Jan 16, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8e6afbe7c9](https://linux-hardware.org/?probe=8e6afbe7c9) | Jan 16, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ae035d3e35](https://linux-hardware.org/?probe=ae035d3e35) | Jan 16, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [bb8785aa08](https://linux-hardware.org/?probe=bb8785aa08) | Jan 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [09e866e5e9](https://linux-hardware.org/?probe=09e866e5e9) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [60e35c48cf](https://linux-hardware.org/?probe=60e35c48cf) | Jan 14, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [0d4e6f7e0b](https://linux-hardware.org/?probe=0d4e6f7e0b) | Jan 13, 2024 |
| HP            | 802F                        | Desktop     | [c1c2cf68cf](https://linux-hardware.org/?probe=c1c2cf68cf) | Jan 13, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [53b86640e5](https://linux-hardware.org/?probe=53b86640e5) | Jan 12, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [696f5dd9e3](https://linux-hardware.org/?probe=696f5dd9e3) | Jan 12, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [2714705590](https://linux-hardware.org/?probe=2714705590) | Jan 12, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [c0282ee6a5](https://linux-hardware.org/?probe=c0282ee6a5) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | Notebook    | [0ca9774d55](https://linux-hardware.org/?probe=0ca9774d55) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | Notebook    | [a2ee63de30](https://linux-hardware.org/?probe=a2ee63de30) | Jan 11, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [a2cae97378](https://linux-hardware.org/?probe=a2cae97378) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| HP            | 198E                        | Desktop     | [15f15e41f1](https://linux-hardware.org/?probe=15f15e41f1) | Jan 11, 2024 |
| ASUSTek       | H81T R2.0                   | Desktop     | [23cc8eb053](https://linux-hardware.org/?probe=23cc8eb053) | Jan 10, 2024 |
| Dell          | Latitude 5440               | Notebook    | [61e99860d0](https://linux-hardware.org/?probe=61e99860d0) | Jan 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [10676b8682](https://linux-hardware.org/?probe=10676b8682) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| HP            | Compaq 610                  | Notebook    | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [88c9ecb793](https://linux-hardware.org/?probe=88c9ecb793) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [b3dbded413](https://linux-hardware.org/?probe=b3dbded413) | Jan 07, 2024 |
| Gigabyte      | B650 GAMING X               | Desktop     | [33c147e1f3](https://linux-hardware.org/?probe=33c147e1f3) | Jan 07, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6eaa268ce1](https://linux-hardware.org/?probe=6eaa268ce1) | Jan 07, 2024 |
| HP            | 250 G3                      | Notebook    | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Google        | Teemo                       | Desktop     | [c763bd20f9](https://linux-hardware.org/?probe=c763bd20f9) | Jan 06, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [4116ba8fb4](https://linux-hardware.org/?probe=4116ba8fb4) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [345ae1cb3d](https://linux-hardware.org/?probe=345ae1cb3d) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [280d389295](https://linux-hardware.org/?probe=280d389295) | Jan 05, 2024 |
| Acer          | Extensa 5230                | Notebook    | [2c36e88ef4](https://linux-hardware.org/?probe=2c36e88ef4) | Jan 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [5e72d133f1](https://linux-hardware.org/?probe=5e72d133f1) | Jan 02, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | Notebook    | [5983998e46](https://linux-hardware.org/?probe=5983998e46) | Jan 02, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| HP            | Compaq 610                  | Notebook    | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Intel         | Thurley                     | Desktop     | [2ad7d27607](https://linux-hardware.org/?probe=2ad7d27607) | Dec 29, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [1b2d301d07](https://linux-hardware.org/?probe=1b2d301d07) | Dec 29, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| HP            | 2000                        | Notebook    | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| MSI           | MS-7390                     | Desktop     | [ca9f0bde00](https://linux-hardware.org/?probe=ca9f0bde00) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Dell          | Latitude 5591               | Notebook    | [99b2702a06](https://linux-hardware.org/?probe=99b2702a06) | Dec 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f91e53f3e0](https://linux-hardware.org/?probe=f91e53f3e0) | Dec 26, 2023 |
| HP            | 2000                        | Notebook    | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [9e99d63708](https://linux-hardware.org/?probe=9e99d63708) | Dec 25, 2023 |
| Lenovo        | 3098 0B98417 PRO            | Desktop     | [770682ab90](https://linux-hardware.org/?probe=770682ab90) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS25R00    | Notebook    | [91820391fd](https://linux-hardware.org/?probe=91820391fd) | Dec 23, 2023 |
| ASUSTek       | P8H61 EVO                   | Desktop     | [a123efbb84](https://linux-hardware.org/?probe=a123efbb84) | Dec 22, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [2f52e3fdc9](https://linux-hardware.org/?probe=2f52e3fdc9) | Dec 22, 2023 |
| HP            | ProBook 4540s               | Notebook    | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Dell          | Latitude 7490               | Notebook    | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [191d4913cd](https://linux-hardware.org/?probe=191d4913cd) | Dec 21, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [fc2beada0a](https://linux-hardware.org/?probe=fc2beada0a) | Dec 21, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35272a3d20](https://linux-hardware.org/?probe=35272a3d20) | Dec 19, 2023 |
| Dell          | Precision M2800             | Notebook    | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [e728e078f2](https://linux-hardware.org/?probe=e728e078f2) | Dec 18, 2023 |
| Sony          | VGN-FW455J                  | Notebook    | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| HP            | 09CCh                       | Desktop     | [e966e2bb97](https://linux-hardware.org/?probe=e966e2bb97) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | Notebook    | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [8939c99ccb](https://linux-hardware.org/?probe=8939c99ccb) | Dec 15, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [25b995fdda](https://linux-hardware.org/?probe=25b995fdda) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52ffec69ce](https://linux-hardware.org/?probe=52ffec69ce) | Dec 12, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [785864b944](https://linux-hardware.org/?probe=785864b944) | Dec 11, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [a00282d994](https://linux-hardware.org/?probe=a00282d994) | Dec 11, 2023 |
| Gigabyte      | Z270-Gaming K3 2017-06-1... | Desktop     | [5292573e8d](https://linux-hardware.org/?probe=5292573e8d) | Dec 11, 2023 |
| HP            | 09CCh                       | Desktop     | [3ef7653874](https://linux-hardware.org/?probe=3ef7653874) | Dec 10, 2023 |
| HP            | 2000                        | Notebook    | [40929a84a0](https://linux-hardware.org/?probe=40929a84a0) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [e55319a16a](https://linux-hardware.org/?probe=e55319a16a) | Dec 09, 2023 |
| HP            | 212B                        | Desktop     | [9a48a7f9bc](https://linux-hardware.org/?probe=9a48a7f9bc) | Dec 09, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [70f37dae85](https://linux-hardware.org/?probe=70f37dae85) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| Dell          | Latitude 5591               | Notebook    | [1961ebb904](https://linux-hardware.org/?probe=1961ebb904) | Dec 07, 2023 |
| Dell          | Latitude 5591               | Notebook    | [b9f6d020e8](https://linux-hardware.org/?probe=b9f6d020e8) | Dec 07, 2023 |
| Dell          | Precision 3550              | Notebook    | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [93bf1ceeec](https://linux-hardware.org/?probe=93bf1ceeec) | Dec 05, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [a9c38d3c16](https://linux-hardware.org/?probe=a9c38d3c16) | Dec 04, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [9b92fedd68](https://linux-hardware.org/?probe=9b92fedd68) | Dec 03, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [debba6a511](https://linux-hardware.org/?probe=debba6a511) | Dec 03, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [e4f6d008cc](https://linux-hardware.org/?probe=e4f6d008cc) | Dec 03, 2023 |
| MSI           | B360-A PRO                  | Desktop     | [7df9fbb107](https://linux-hardware.org/?probe=7df9fbb107) | Dec 03, 2023 |
| MSI           | B360-A PRO                  | Desktop     | [f9da2a7d45](https://linux-hardware.org/?probe=f9da2a7d45) | Dec 03, 2023 |
| Sony          | VPCS13S9E                   | Notebook    | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | Desktop     | [59610f075c](https://linux-hardware.org/?probe=59610f075c) | Nov 30, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | Desktop     | [1959f30d83](https://linux-hardware.org/?probe=1959f30d83) | Nov 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [86519a17c4](https://linux-hardware.org/?probe=86519a17c4) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [cc47b08289](https://linux-hardware.org/?probe=cc47b08289) | Nov 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [c4a56c14f5](https://linux-hardware.org/?probe=c4a56c14f5) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [7c57d31cc7](https://linux-hardware.org/?probe=7c57d31cc7) | Nov 28, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [a39cb80b48](https://linux-hardware.org/?probe=a39cb80b48) | Nov 26, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [e77e8d6999](https://linux-hardware.org/?probe=e77e8d6999) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Dell          | Latitude 5511               | Notebook    | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | Notebook    | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| Lenovo        | ThinkPad E450 20DC008DMC    | Notebook    | [56fc21d585](https://linux-hardware.org/?probe=56fc21d585) | Nov 23, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [3c0651cb41](https://linux-hardware.org/?probe=3c0651cb41) | Nov 23, 2023 |
| ASUSTek       | K54LY                       | Notebook    | [4ebc53e69c](https://linux-hardware.org/?probe=4ebc53e69c) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | Notebook    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [47105264f8](https://linux-hardware.org/?probe=47105264f8) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [748ea9f21b](https://linux-hardware.org/?probe=748ea9f21b) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [221dcda3ae](https://linux-hardware.org/?probe=221dcda3ae) | Nov 19, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [89e41854be](https://linux-hardware.org/?probe=89e41854be) | Nov 19, 2023 |
| UMAX          | VisionBook 9Wi Pro          | Tablet      | [816a26352f](https://linux-hardware.org/?probe=816a26352f) | Nov 19, 2023 |
| Lenovo        | ThinkPad X201 3680DE3       | Notebook    | [38290dc3e7](https://linux-hardware.org/?probe=38290dc3e7) | Nov 17, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [ca7747546b](https://linux-hardware.org/?probe=ca7747546b) | Nov 17, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [62e08b2285](https://linux-hardware.org/?probe=62e08b2285) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [2204427cc1](https://linux-hardware.org/?probe=2204427cc1) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [001dd47e7d](https://linux-hardware.org/?probe=001dd47e7d) | Nov 12, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [41e1f90785](https://linux-hardware.org/?probe=41e1f90785) | Nov 11, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [c1e2a1a0da](https://linux-hardware.org/?probe=c1e2a1a0da) | Nov 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| HP            | 83E2                        | Mini pc     | [565701f119](https://linux-hardware.org/?probe=565701f119) | Nov 09, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [154324f43d](https://linux-hardware.org/?probe=154324f43d) | Nov 08, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| Dell          | Latitude E7440              | Notebook    | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | Notebook    | [ae8881b2b2](https://linux-hardware.org/?probe=ae8881b2b2) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5832913981](https://linux-hardware.org/?probe=5832913981) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | Notebook    | [a3d91609e9](https://linux-hardware.org/?probe=a3d91609e9) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [4f6d5932fa](https://linux-hardware.org/?probe=4f6d5932fa) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| Rockchip      | Orange Pi 5 Plus            | Soc         | [9c30c8c8b4](https://linux-hardware.org/?probe=9c30c8c8b4) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [99b1ce4372](https://linux-hardware.org/?probe=99b1ce4372) | Nov 02, 2023 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [a7afcdcef2](https://linux-hardware.org/?probe=a7afcdcef2) | Nov 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a42017f05d](https://linux-hardware.org/?probe=a42017f05d) | Nov 02, 2023 |
| MSI           | IONA                        | Desktop     | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1fd433ec1e](https://linux-hardware.org/?probe=1fd433ec1e) | Nov 02, 2023 |
| Dell          | Latitude 5480               | Notebook    | [567a2774f8](https://linux-hardware.org/?probe=567a2774f8) | Nov 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [98b1bd5970](https://linux-hardware.org/?probe=98b1bd5970) | Oct 31, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [15573e8d54](https://linux-hardware.org/?probe=15573e8d54) | Oct 30, 2023 |
| HP            | 250 G3                      | Notebook    | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| Radxa         | ROCK 5B (DT)                | Soc         | [b1c2a699a9](https://linux-hardware.org/?probe=b1c2a699a9) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [10af2377c2](https://linux-hardware.org/?probe=10af2377c2) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [a95ddd6798](https://linux-hardware.org/?probe=a95ddd6798) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| HP            | 250 G3                      | Notebook    | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b124e800d6](https://linux-hardware.org/?probe=b124e800d6) | Oct 25, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [d22fc67d1d](https://linux-hardware.org/?probe=d22fc67d1d) | Oct 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [819d596b2e](https://linux-hardware.org/?probe=819d596b2e) | Oct 24, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a6d732c859](https://linux-hardware.org/?probe=a6d732c859) | Oct 24, 2023 |
| Gigabyte      | EX38-DS5                    | Desktop     | [79e9d5669a](https://linux-hardware.org/?probe=79e9d5669a) | Oct 23, 2023 |
| MSI           | IONA                        | Desktop     | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [8f65236e52](https://linux-hardware.org/?probe=8f65236e52) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [a523689a60](https://linux-hardware.org/?probe=a523689a60) | Oct 21, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [f8d2d274e1](https://linux-hardware.org/?probe=f8d2d274e1) | Oct 21, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [0dcc624a0d](https://linux-hardware.org/?probe=0dcc624a0d) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [aa10d84f78](https://linux-hardware.org/?probe=aa10d84f78) | Oct 17, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [51e04c2a8a](https://linux-hardware.org/?probe=51e04c2a8a) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [70c2a81f9f](https://linux-hardware.org/?probe=70c2a81f9f) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b2250f3c59](https://linux-hardware.org/?probe=b2250f3c59) | Oct 14, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9972c1fc42](https://linux-hardware.org/?probe=9972c1fc42) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [3e075f72d8](https://linux-hardware.org/?probe=3e075f72d8) | Oct 09, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Dell          | Latitude 5431               | Notebook    | [a85fc8f829](https://linux-hardware.org/?probe=a85fc8f829) | Oct 06, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [3c7f490b86](https://linux-hardware.org/?probe=3c7f490b86) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [ec51b8fd0c](https://linux-hardware.org/?probe=ec51b8fd0c) | Oct 02, 2023 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [5a154d10af](https://linux-hardware.org/?probe=5a154d10af) | Oct 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | Notebook    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| MSI           | X299 RAIDER 2018-10-08      | Desktop     | [8bccf1be8d](https://linux-hardware.org/?probe=8bccf1be8d) | Sep 26, 2023 |
| Acer          | Swift SF14-71T              | Notebook    | [10b657bd75](https://linux-hardware.org/?probe=10b657bd75) | Sep 25, 2023 |
| Dell          | Precision 7720              | Notebook    | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [336d5fe8c8](https://linux-hardware.org/?probe=336d5fe8c8) | Sep 25, 2023 |
| Dell          | Latitude 7400               | Notebook    | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3b9bbcebb0](https://linux-hardware.org/?probe=3b9bbcebb0) | Sep 23, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [b58de0bed0](https://linux-hardware.org/?probe=b58de0bed0) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [81d1af1a96](https://linux-hardware.org/?probe=81d1af1a96) | Sep 20, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [4bb581fb16](https://linux-hardware.org/?probe=4bb581fb16) | Sep 19, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [db308e1798](https://linux-hardware.org/?probe=db308e1798) | Sep 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | Notebook    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [d56ff45f03](https://linux-hardware.org/?probe=d56ff45f03) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [c323f31788](https://linux-hardware.org/?probe=c323f31788) | Sep 17, 2023 |
| Lenovo        | NOK                         | Desktop     | [ead85a1003](https://linux-hardware.org/?probe=ead85a1003) | Sep 16, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Dell          | G3 3500                     | Notebook    | [293bbfe2d6](https://linux-hardware.org/?probe=293bbfe2d6) | Sep 12, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [bcfc38f6da](https://linux-hardware.org/?probe=bcfc38f6da) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [1b79da7f45](https://linux-hardware.org/?probe=1b79da7f45) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2a7d4dfb14](https://linux-hardware.org/?probe=2a7d4dfb14) | Sep 09, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [db1e55d494](https://linux-hardware.org/?probe=db1e55d494) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [e3152ede03](https://linux-hardware.org/?probe=e3152ede03) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [04b9d6891a](https://linux-hardware.org/?probe=04b9d6891a) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| Lenovo        | 32E4 SDK0T76538 WIN 3556... | Mini pc     | [ac035f8420](https://linux-hardware.org/?probe=ac035f8420) | Sep 07, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [40b17904fa](https://linux-hardware.org/?probe=40b17904fa) | Sep 06, 2023 |
| Dell          | Latitude 7400               | Notebook    | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| UMAX          | 13Wr                        | Notebook    | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [61a10ef907](https://linux-hardware.org/?probe=61a10ef907) | Sep 02, 2023 |
| HP            | Unknown                     | Notebook    | [3809d7ad85](https://linux-hardware.org/?probe=3809d7ad85) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| HP            | 3032h                       | Desktop     | [7dfc9fa7a0](https://linux-hardware.org/?probe=7dfc9fa7a0) | Sep 01, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8cc90dd6b0](https://linux-hardware.org/?probe=8cc90dd6b0) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | Notebook    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [81ae698cf8](https://linux-hardware.org/?probe=81ae698cf8) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [362ee070d7](https://linux-hardware.org/?probe=362ee070d7) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [3240f39404](https://linux-hardware.org/?probe=3240f39404) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [14fce9ff7f](https://linux-hardware.org/?probe=14fce9ff7f) | Aug 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | K53E                        | Notebook    | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [e3ca221ba9](https://linux-hardware.org/?probe=e3ca221ba9) | Aug 28, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [037143c4fd](https://linux-hardware.org/?probe=037143c4fd) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| HP            | ProBook x360 435 G7         | Convertible | [127d78aea0](https://linux-hardware.org/?probe=127d78aea0) | Aug 26, 2023 |
| Google        | Robo                        | Notebook    | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| HP            | 802F                        | Desktop     | [6759058353](https://linux-hardware.org/?probe=6759058353) | Aug 25, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae2d6ab9fd](https://linux-hardware.org/?probe=ae2d6ab9fd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [6c3b3d9727](https://linux-hardware.org/?probe=6c3b3d9727) | Aug 23, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [98669adc64](https://linux-hardware.org/?probe=98669adc64) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4945bd0d6d](https://linux-hardware.org/?probe=4945bd0d6d) | Aug 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | Desktop     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [9c749716e8](https://linux-hardware.org/?probe=9c749716e8) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [722707e986](https://linux-hardware.org/?probe=722707e986) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [73867661a3](https://linux-hardware.org/?probe=73867661a3) | Aug 18, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| Dell          | Latitude 7440               | Notebook    | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [e5618417ed](https://linux-hardware.org/?probe=e5618417ed) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [1fcc89106f](https://linux-hardware.org/?probe=1fcc89106f) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| HP            | 09CCh                       | Desktop     | [947fb1edcb](https://linux-hardware.org/?probe=947fb1edcb) | Aug 15, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | Notebook    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [f4e6886bd8](https://linux-hardware.org/?probe=f4e6886bd8) | Aug 13, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4775c7e602](https://linux-hardware.org/?probe=4775c7e602) | Aug 13, 2023 |
| AMD           | A690G M2+                   | Desktop     | [4179510c0b](https://linux-hardware.org/?probe=4179510c0b) | Aug 13, 2023 |
| HP            | 09CCh                       | Desktop     | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| HP            | 250 G3                      | Notebook    | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [401fdc46ef](https://linux-hardware.org/?probe=401fdc46ef) | Aug 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Dell          | Latitude E5500              | Notebook    | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Dell          | Latitude 7400               | Notebook    | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [6495cadf19](https://linux-hardware.org/?probe=6495cadf19) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [141928d8e2](https://linux-hardware.org/?probe=141928d8e2) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [44438ab71e](https://linux-hardware.org/?probe=44438ab71e) | Jul 30, 2023 |
| HP            | 843B                        | Desktop     | [c570a7c5f2](https://linux-hardware.org/?probe=c570a7c5f2) | Jul 29, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [4baa3fe63b](https://linux-hardware.org/?probe=4baa3fe63b) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [254354d9aa](https://linux-hardware.org/?probe=254354d9aa) | Jul 29, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [d500093891](https://linux-hardware.org/?probe=d500093891) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ccfe4b2234](https://linux-hardware.org/?probe=ccfe4b2234) | Jul 27, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| HP            | 8169                        | Desktop     | [f2885ba2de](https://linux-hardware.org/?probe=f2885ba2de) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [8e3dbf7ff9](https://linux-hardware.org/?probe=8e3dbf7ff9) | Jul 23, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [4f00ba88de](https://linux-hardware.org/?probe=4f00ba88de) | Jul 21, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [6a048ba2cc](https://linux-hardware.org/?probe=6a048ba2cc) | Jul 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0d5bd8b2f2](https://linux-hardware.org/?probe=0d5bd8b2f2) | Jul 20, 2023 |
| AMI           | Intel                       | Convertible | [896ed95f63](https://linux-hardware.org/?probe=896ed95f63) | Jul 19, 2023 |
| MSI           | IONA                        | Desktop     | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4ad55cf9da](https://linux-hardware.org/?probe=4ad55cf9da) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| ASUSTek       | J1800I-A                    | Desktop     | [ce7f031b0a](https://linux-hardware.org/?probe=ce7f031b0a) | Jul 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [b3770db2e8](https://linux-hardware.org/?probe=b3770db2e8) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [d7d8d93ac1](https://linux-hardware.org/?probe=d7d8d93ac1) | Jul 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ecba1dae0a](https://linux-hardware.org/?probe=ecba1dae0a) | Jul 09, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [76a4853c56](https://linux-hardware.org/?probe=76a4853c56) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Lenovo        | ThinkPad E570 20H50074MC    | Notebook    | [029e84bf8a](https://linux-hardware.org/?probe=029e84bf8a) | Jul 06, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [ef4d169d77](https://linux-hardware.org/?probe=ef4d169d77) | Jul 05, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b0432f19ba](https://linux-hardware.org/?probe=b0432f19ba) | Jul 05, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57d7c40d](https://linux-hardware.org/?probe=1e57d7c40d) | Jul 05, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [73e054c849](https://linux-hardware.org/?probe=73e054c849) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [eada4fe260](https://linux-hardware.org/?probe=eada4fe260) | Jul 02, 2023 |
| AMI           | Intel                       | Notebook    | [65aafdb0b0](https://linux-hardware.org/?probe=65aafdb0b0) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [c5820f8068](https://linux-hardware.org/?probe=c5820f8068) | Jul 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [07ab83bef1](https://linux-hardware.org/?probe=07ab83bef1) | Jun 30, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [fcf9a0fd47](https://linux-hardware.org/?probe=fcf9a0fd47) | Jun 30, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Acer          | NC-A515-51G-59DM            | Notebook    | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| ASUSTek       | H87M-E                      | Desktop     | [7e7af2948c](https://linux-hardware.org/?probe=7e7af2948c) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [607da926f3](https://linux-hardware.org/?probe=607da926f3) | Jun 28, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [d5e4ce2efa](https://linux-hardware.org/?probe=d5e4ce2efa) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Lenovo        | 01GR176                     | Server      | [6d28cbec97](https://linux-hardware.org/?probe=6d28cbec97) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [0aa3b8d433](https://linux-hardware.org/?probe=0aa3b8d433) | Jun 21, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [3ff2c9e4cc](https://linux-hardware.org/?probe=3ff2c9e4cc) | Jun 21, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [d77f55da92](https://linux-hardware.org/?probe=d77f55da92) | Jun 19, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [71a0effa3a](https://linux-hardware.org/?probe=71a0effa3a) | Jun 19, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0054d0c92e](https://linux-hardware.org/?probe=0054d0c92e) | Jun 18, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [98b3d14b06](https://linux-hardware.org/?probe=98b3d14b06) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [706eeef80f](https://linux-hardware.org/?probe=706eeef80f) | Jun 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c74f83bbea](https://linux-hardware.org/?probe=c74f83bbea) | Jun 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [77ce1af9f8](https://linux-hardware.org/?probe=77ce1af9f8) | Jun 13, 2023 |
| MSI           | IONA                        | Desktop     | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [4d019c4a6f](https://linux-hardware.org/?probe=4d019c4a6f) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| Dell          | Latitude 7400               | Notebook    | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| MSI           | H110M ECO                   | Desktop     | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [e64369d2ec](https://linux-hardware.org/?probe=e64369d2ec) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | Notebook    | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [7ae3c54a4c](https://linux-hardware.org/?probe=7ae3c54a4c) | Jun 03, 2023 |
| Timi          | A35S                        | Notebook    | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| HP            | 158A                        | Desktop     | [39d4ab7307](https://linux-hardware.org/?probe=39d4ab7307) | May 31, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [b706fad8dc](https://linux-hardware.org/?probe=b706fad8dc) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b3966a1d81](https://linux-hardware.org/?probe=b3966a1d81) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | Notebook    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7b001db11a](https://linux-hardware.org/?probe=7b001db11a) | May 29, 2023 |
| Acer          | Aspire 7540                 | Notebook    | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | Notebook    | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | Notebook    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [84b7538837](https://linux-hardware.org/?probe=84b7538837) | May 23, 2023 |
| Dell          | G5 5587                     | Notebook    | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| HP            | 1495                        | Desktop     | [200cab3da9](https://linux-hardware.org/?probe=200cab3da9) | May 23, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [7e8b42ab5f](https://linux-hardware.org/?probe=7e8b42ab5f) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [cb8bc926b8](https://linux-hardware.org/?probe=cb8bc926b8) | May 21, 2023 |
| HP            | 2B5E                        | Desktop     | [a221629f4d](https://linux-hardware.org/?probe=a221629f4d) | May 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [69d4abb6e4](https://linux-hardware.org/?probe=69d4abb6e4) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| Dell          | Latitude 5521               | Notebook    | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c12ae2e393](https://linux-hardware.org/?probe=c12ae2e393) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [14aeaeafe8](https://linux-hardware.org/?probe=14aeaeafe8) | May 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| eMachines     | E620                        | Notebook    | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e63410f299](https://linux-hardware.org/?probe=e63410f299) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b979325eea](https://linux-hardware.org/?probe=b979325eea) | May 07, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [61a2726a1d](https://linux-hardware.org/?probe=61a2726a1d) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | Notebook    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [ab48e66c38](https://linux-hardware.org/?probe=ab48e66c38) | May 01, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [0e035d415e](https://linux-hardware.org/?probe=0e035d415e) | May 01, 2023 |
| Acer          | Extensa 5620                | Notebook    | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e0367e684f](https://linux-hardware.org/?probe=e0367e684f) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fed0a1a719](https://linux-hardware.org/?probe=fed0a1a719) | Apr 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Lenovo        | NOK                         | Desktop     | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Dell          | System XPS L502X            | Notebook    | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [68d1859c93](https://linux-hardware.org/?probe=68d1859c93) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [1cc955413f](https://linux-hardware.org/?probe=1cc955413f) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [085b87dc27](https://linux-hardware.org/?probe=085b87dc27) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [42ca23ca64](https://linux-hardware.org/?probe=42ca23ca64) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [e315ba7088](https://linux-hardware.org/?probe=e315ba7088) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | Notebook    | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [59d15de09e](https://linux-hardware.org/?probe=59d15de09e) | Apr 15, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [5439790362](https://linux-hardware.org/?probe=5439790362) | Apr 15, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| Acer          | Aspire one                  | Notebook    | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [ef5cbba147](https://linux-hardware.org/?probe=ef5cbba147) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [8a78c5b08f](https://linux-hardware.org/?probe=8a78c5b08f) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| MSI           | J1800I                      | Desktop     | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [ec627dea03](https://linux-hardware.org/?probe=ec627dea03) | Apr 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [3a1b0cca6b](https://linux-hardware.org/?probe=3a1b0cca6b) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b1168b92c0](https://linux-hardware.org/?probe=b1168b92c0) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [5499373552](https://linux-hardware.org/?probe=5499373552) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [70ed012fb4](https://linux-hardware.org/?probe=70ed012fb4) | Apr 03, 2023 |
| Notebook      | NJ50GU                      | Notebook    | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| HP            | 250 G3                      | Notebook    | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Dell          | Latitude 5511               | Notebook    | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | Notebook    | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | Notebook    | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2b23ce3fed](https://linux-hardware.org/?probe=2b23ce3fed) | Mar 31, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | Notebook    | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | Notebook    | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [95da0c6b8a](https://linux-hardware.org/?probe=95da0c6b8a) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | Notebook    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| MSI           | B250M PRO-VDH 2018-05-07    | Desktop     | [6f7e481d06](https://linux-hardware.org/?probe=6f7e481d06) | Mar 27, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [53ec55f5ae](https://linux-hardware.org/?probe=53ec55f5ae) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [b6bd6cab94](https://linux-hardware.org/?probe=b6bd6cab94) | Mar 26, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [df8f872445](https://linux-hardware.org/?probe=df8f872445) | Mar 25, 2023 |
| Lenovo        | G780                        | Notebook    | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | Notebook    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | Notebook    | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | Notebook    | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [31c28e071b](https://linux-hardware.org/?probe=31c28e071b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e82b110a76](https://linux-hardware.org/?probe=e82b110a76) | Mar 12, 2023 |
| HP            | 09CCh                       | Desktop     | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [e51e1c905c](https://linux-hardware.org/?probe=e51e1c905c) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP            | 09CCh                       | Desktop     | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| ASUSTek       | K54LY                       | Notebook    | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [70d063d399](https://linux-hardware.org/?probe=70d063d399) | Mar 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | Notebook    | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [428377b153](https://linux-hardware.org/?probe=428377b153) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9e63190b6f](https://linux-hardware.org/?probe=9e63190b6f) | Mar 01, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [10f864cbb0](https://linux-hardware.org/?probe=10f864cbb0) | Mar 01, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [8c36af11ab](https://linux-hardware.org/?probe=8c36af11ab) | Mar 01, 2023 |
| ASUSTek       | AM1I-A                      | Desktop     | [b5fe605f8b](https://linux-hardware.org/?probe=b5fe605f8b) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [0ea2a54b39](https://linux-hardware.org/?probe=0ea2a54b39) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9b2a57b7d2](https://linux-hardware.org/?probe=9b2a57b7d2) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [8bfeed43ef](https://linux-hardware.org/?probe=8bfeed43ef) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [cff33d0b1e](https://linux-hardware.org/?probe=cff33d0b1e) | Feb 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | Notebook    | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [ef3ee2ebf2](https://linux-hardware.org/?probe=ef3ee2ebf2) | Feb 14, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cdd9011e76](https://linux-hardware.org/?probe=cdd9011e76) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| MSI           | GX700                       | Notebook    | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2b4f9e9f21](https://linux-hardware.org/?probe=2b4f9e9f21) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [731d910d0c](https://linux-hardware.org/?probe=731d910d0c) | Feb 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6490f4cb92](https://linux-hardware.org/?probe=6490f4cb92) | Feb 05, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | Notebook    | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [80e1fa4ed8](https://linux-hardware.org/?probe=80e1fa4ed8) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | Notebook    | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [36caf406ce](https://linux-hardware.org/?probe=36caf406ce) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| ASUSTek       | V241DA                      | All in one  | [72df681f16](https://linux-hardware.org/?probe=72df681f16) | Jan 28, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | Notebook    | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| Lenovo        | MAHOBAY 31900003 STD        | All in one  | [d75e472005](https://linux-hardware.org/?probe=d75e472005) | Jan 26, 2023 |
| UMAX          | VisionBook 10Wr Tab         | Convertible | [6d747e3841](https://linux-hardware.org/?probe=6d747e3841) | Jan 26, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | Notebook    | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| HP            | 8750                        | Desktop     | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ec12d33bd7](https://linux-hardware.org/?probe=ec12d33bd7) | Jan 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [5a32ba3cd1](https://linux-hardware.org/?probe=5a32ba3cd1) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASRock        | X99 Taichi                  | Desktop     | [793777c14e](https://linux-hardware.org/?probe=793777c14e) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f7fcfb7b18](https://linux-hardware.org/?probe=f7fcfb7b18) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad E550 20DF0081MC    | Notebook    | [1b7e734f36](https://linux-hardware.org/?probe=1b7e734f36) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [5b0e671bb8](https://linux-hardware.org/?probe=5b0e671bb8) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [395a44652b](https://linux-hardware.org/?probe=395a44652b) | Jan 17, 2023 |
| Dynabook      | PORTEGE X30W-K              | Convertible | [5c3d7c049e](https://linux-hardware.org/?probe=5c3d7c049e) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [5f3e7922cd](https://linux-hardware.org/?probe=5f3e7922cd) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [fa4fd9061f](https://linux-hardware.org/?probe=fa4fd9061f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [6841633faf](https://linux-hardware.org/?probe=6841633faf) | Jan 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [33985f088a](https://linux-hardware.org/?probe=33985f088a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [b4bc427969](https://linux-hardware.org/?probe=b4bc427969) | Jan 15, 2023 |
| HP            | 250 G3                      | Notebook    | [717fbc7972](https://linux-hardware.org/?probe=717fbc7972) | Jan 15, 2023 |
| UMAX          | U-Box N42                   | Mini pc     | [4f778e38f0](https://linux-hardware.org/?probe=4f778e38f0) | Jan 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [9d4f877d3d](https://linux-hardware.org/?probe=9d4f877d3d) | Jan 14, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [32f2651aa1](https://linux-hardware.org/?probe=32f2651aa1) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [bd4516127b](https://linux-hardware.org/?probe=bd4516127b) | Jan 14, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [3c475bc193](https://linux-hardware.org/?probe=3c475bc193) | Jan 14, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8f9d1f85ee](https://linux-hardware.org/?probe=8f9d1f85ee) | Jan 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d60bab803e](https://linux-hardware.org/?probe=d60bab803e) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Lenovo        | ThinkPad T450 20BUA0UG00    | Notebook    | [b0854ecbf8](https://linux-hardware.org/?probe=b0854ecbf8) | Jan 12, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1d6a667a5b](https://linux-hardware.org/?probe=1d6a667a5b) | Jan 11, 2023 |
| HP            | 304Ah                       | Desktop     | [c79a932800](https://linux-hardware.org/?probe=c79a932800) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a02943108d](https://linux-hardware.org/?probe=a02943108d) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [88ffbf550c](https://linux-hardware.org/?probe=88ffbf550c) | Jan 11, 2023 |
| Acer          | Extensa 2519                | Notebook    | [c044faaa05](https://linux-hardware.org/?probe=c044faaa05) | Jan 11, 2023 |
| Dell          | Precision 7710              | Notebook    | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [fa17d61c80](https://linux-hardware.org/?probe=fa17d61c80) | Jan 11, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [fd8d969adb](https://linux-hardware.org/?probe=fd8d969adb) | Jan 11, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [e4c19089b5](https://linux-hardware.org/?probe=e4c19089b5) | Jan 11, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Dell          | Precision 5510              | Notebook    | [22a344ddad](https://linux-hardware.org/?probe=22a344ddad) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [42f10f6d45](https://linux-hardware.org/?probe=42f10f6d45) | Jan 09, 2023 |
| Dell          | Precision 7710              | Notebook    | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [182a43f2b4](https://linux-hardware.org/?probe=182a43f2b4) | Jan 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [b808a6be1a](https://linux-hardware.org/?probe=b808a6be1a) | Jan 08, 2023 |
| Lenovo        | ThinkPad X230 2320JNG       | Notebook    | [29d3023af5](https://linux-hardware.org/?probe=29d3023af5) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [667330c83f](https://linux-hardware.org/?probe=667330c83f) | Jan 07, 2023 |
| Dell          | 0C27VV A00                  | Desktop     | [317f136007](https://linux-hardware.org/?probe=317f136007) | Jan 07, 2023 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [412180b4de](https://linux-hardware.org/?probe=412180b4de) | Jan 06, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [c56206ea8a](https://linux-hardware.org/?probe=c56206ea8a) | Jan 05, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [9b5a0200df](https://linux-hardware.org/?probe=9b5a0200df) | Jan 04, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [47813fa627](https://linux-hardware.org/?probe=47813fa627) | Jan 03, 2023 |
| HP            | ProBook 635 Aero G8         | Notebook    | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Google        | Chell                       | Notebook    | [02a0ae3bea](https://linux-hardware.org/?probe=02a0ae3bea) | Jan 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [dc3612b4e1](https://linux-hardware.org/?probe=dc3612b4e1) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [ce23d2f7cd](https://linux-hardware.org/?probe=ce23d2f7cd) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Lenovo        | 31900003 STD                | All in one  | [4cc2e8cadd](https://linux-hardware.org/?probe=4cc2e8cadd) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | Desktop     | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [2b646304f0](https://linux-hardware.org/?probe=2b646304f0) | Dec 29, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [74f8dcfbb4](https://linux-hardware.org/?probe=74f8dcfbb4) | Dec 29, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [8d54484965](https://linux-hardware.org/?probe=8d54484965) | Dec 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [9e6b5e5ebf](https://linux-hardware.org/?probe=9e6b5e5ebf) | Dec 27, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [5d0485ba40](https://linux-hardware.org/?probe=5d0485ba40) | Dec 26, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [d68451099d](https://linux-hardware.org/?probe=d68451099d) | Dec 26, 2022 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [7eb49ce0ab](https://linux-hardware.org/?probe=7eb49ce0ab) | Dec 24, 2022 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [4123115ef0](https://linux-hardware.org/?probe=4123115ef0) | Dec 24, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [08a1ad1c63](https://linux-hardware.org/?probe=08a1ad1c63) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| Dell          | 0T656F A02                  | Desktop     | [35aa2eee2a](https://linux-hardware.org/?probe=35aa2eee2a) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [c5cc33f2c6](https://linux-hardware.org/?probe=c5cc33f2c6) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [ffbf35fd33](https://linux-hardware.org/?probe=ffbf35fd33) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2b25ab8790](https://linux-hardware.org/?probe=2b25ab8790) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [af14f0c425](https://linux-hardware.org/?probe=af14f0c425) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [e7393fd2b7](https://linux-hardware.org/?probe=e7393fd2b7) | Dec 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [2a2f618c62](https://linux-hardware.org/?probe=2a2f618c62) | Dec 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [c20be92503](https://linux-hardware.org/?probe=c20be92503) | Dec 19, 2022 |
| UMAX          | 13Wr-Flex                   | Convertible | [487bef515a](https://linux-hardware.org/?probe=487bef515a) | Dec 18, 2022 |
| UMAX          | 13Wr-Flex                   | Convertible | [669c43b4f3](https://linux-hardware.org/?probe=669c43b4f3) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [4f41f354cd](https://linux-hardware.org/?probe=4f41f354cd) | Dec 18, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [c106327357](https://linux-hardware.org/?probe=c106327357) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [e5525b45b5](https://linux-hardware.org/?probe=e5525b45b5) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [651fa58fbd](https://linux-hardware.org/?probe=651fa58fbd) | Dec 12, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [4471c4a012](https://linux-hardware.org/?probe=4471c4a012) | Dec 11, 2022 |
| HP            | Pavilion TS 11              | Notebook    | [db2a3e8ebb](https://linux-hardware.org/?probe=db2a3e8ebb) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [6e2cf6514a](https://linux-hardware.org/?probe=6e2cf6514a) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [6b999f972f](https://linux-hardware.org/?probe=6b999f972f) | Dec 10, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [c415ea37d7](https://linux-hardware.org/?probe=c415ea37d7) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [b9ea8b5b2b](https://linux-hardware.org/?probe=b9ea8b5b2b) | Dec 08, 2022 |
| ASUSTek       | X55A                        | Notebook    | [283ef64c76](https://linux-hardware.org/?probe=283ef64c76) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [2b5a2c145c](https://linux-hardware.org/?probe=2b5a2c145c) | Dec 06, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [2f14f32399](https://linux-hardware.org/?probe=2f14f32399) | Dec 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS2291X    | Notebook    | [312119ddbd](https://linux-hardware.org/?probe=312119ddbd) | Dec 06, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [ca5bc5dfe6](https://linux-hardware.org/?probe=ca5bc5dfe6) | Dec 05, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e39eb3e3b](https://linux-hardware.org/?probe=2e39eb3e3b) | Dec 04, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [7bde8b90c7](https://linux-hardware.org/?probe=7bde8b90c7) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [059ed32da0](https://linux-hardware.org/?probe=059ed32da0) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [e44ba4a41b](https://linux-hardware.org/?probe=e44ba4a41b) | Dec 03, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [2b1a977b21](https://linux-hardware.org/?probe=2b1a977b21) | Dec 02, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [012f2dccba](https://linux-hardware.org/?probe=012f2dccba) | Dec 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ea8b9066f6](https://linux-hardware.org/?probe=ea8b9066f6) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [44170ddf90](https://linux-hardware.org/?probe=44170ddf90) | Nov 29, 2022 |
| UMAX          | U-Box N42                   | Mini pc     | [5953c13736](https://linux-hardware.org/?probe=5953c13736) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [97c63f232d](https://linux-hardware.org/?probe=97c63f232d) | Nov 28, 2022 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [aad7343998](https://linux-hardware.org/?probe=aad7343998) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [53b311f78c](https://linux-hardware.org/?probe=53b311f78c) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [dad186aa07](https://linux-hardware.org/?probe=dad186aa07) | Nov 24, 2022 |
| HP            | 8750                        | Desktop     | [b1ac308187](https://linux-hardware.org/?probe=b1ac308187) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| HP            | 0AACh                       | Desktop     | [9e37ad4151](https://linux-hardware.org/?probe=9e37ad4151) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| HP            | 82B4                        | Desktop     | [c56604f389](https://linux-hardware.org/?probe=c56604f389) | Nov 21, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1502b216b8](https://linux-hardware.org/?probe=1502b216b8) | Nov 20, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [10840bac50](https://linux-hardware.org/?probe=10840bac50) | Nov 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c57a9ae3d5](https://linux-hardware.org/?probe=c57a9ae3d5) | Nov 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [99ed91b58d](https://linux-hardware.org/?probe=99ed91b58d) | Nov 19, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [73c9daf454](https://linux-hardware.org/?probe=73c9daf454) | Nov 19, 2022 |
| Dell          | Precision 5510              | Notebook    | [a9467ec69d](https://linux-hardware.org/?probe=a9467ec69d) | Nov 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [9c25ade74d](https://linux-hardware.org/?probe=9c25ade74d) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [9ed6d8ee1e](https://linux-hardware.org/?probe=9ed6d8ee1e) | Nov 16, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c7ac1636bc](https://linux-hardware.org/?probe=c7ac1636bc) | Nov 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [c8c143ccdd](https://linux-hardware.org/?probe=c8c143ccdd) | Nov 14, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [b8da32bca0](https://linux-hardware.org/?probe=b8da32bca0) | Nov 14, 2022 |
| Lenovo        | 0x36C4 SDK0K17763 WIN 18... | All in one  | [7a3f735fc0](https://linux-hardware.org/?probe=7a3f735fc0) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [bc9518dbad](https://linux-hardware.org/?probe=bc9518dbad) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a7e35fd231](https://linux-hardware.org/?probe=a7e35fd231) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [62d1e401a4](https://linux-hardware.org/?probe=62d1e401a4) | Nov 12, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [48572e207b](https://linux-hardware.org/?probe=48572e207b) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [350e3f7ee2](https://linux-hardware.org/?probe=350e3f7ee2) | Nov 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [fa27762189](https://linux-hardware.org/?probe=fa27762189) | Nov 11, 2022 |
| HP            | 872E                        | Mini pc     | [b2e72a139e](https://linux-hardware.org/?probe=b2e72a139e) | Nov 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5b01559647](https://linux-hardware.org/?probe=5b01559647) | Nov 11, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [8a4f5a2c29](https://linux-hardware.org/?probe=8a4f5a2c29) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [9f586bafd4](https://linux-hardware.org/?probe=9f586bafd4) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1d9cb16e2f](https://linux-hardware.org/?probe=1d9cb16e2f) | Nov 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [afb0629ea9](https://linux-hardware.org/?probe=afb0629ea9) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [fcb59bae39](https://linux-hardware.org/?probe=fcb59bae39) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [001308a248](https://linux-hardware.org/?probe=001308a248) | Nov 06, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [96bd39af33](https://linux-hardware.org/?probe=96bd39af33) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1833650d](https://linux-hardware.org/?probe=bd1833650d) | Nov 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 248       | 9.94%   |
| Ubuntu 18.04                 | 151       | 6.05%   |
| Ubuntu 22.04                 | 147       | 5.89%   |
| OpenMandriva 4.2             | 118       | 4.73%   |
| OpenMandriva 4.3             | 72        | 2.89%   |
| OpenMandriva 4.50            | 66        | 2.65%   |
| Arch Rolling                 | 45        | 1.8%    |
| Debian 11                    | 43        | 1.72%   |
| Ubuntu 21.10                 | 39        | 1.56%   |
| Fedora 38                    | 37        | 1.48%   |
| Zorin 16                     | 36        | 1.44%   |
| Ubuntu 20.10                 | 35        | 1.4%    |
| Fedora 34                    | 35        | 1.4%    |
| Linux Mint 21.1              | 33        | 1.32%   |
| Pop!_OS 22.04                | 32        | 1.28%   |
| OpenMandriva 23.01           | 31        | 1.24%   |
| Ubuntu 19.10                 | 28        | 1.12%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 1.12%   |
| Linux Mint 20.1              | 28        | 1.12%   |
| Ubuntu 21.04                 | 27        | 1.08%   |
| OpenMandriva 23.03           | 27        | 1.08%   |
| Linux Mint 20                | 27        | 1.08%   |
| Fedora 35                    | 27        | 1.08%   |
| Arch                         | 27        | 1.08%   |
| Linux Mint 20.2              | 25        | 1%      |
| Fedora 32                    | 25        | 1%      |
| Zorin 15                     | 24        | 0.96%   |
| Ubuntu 19.04                 | 24        | 0.96%   |
| Linux Mint 20.3              | 24        | 0.96%   |
| Ubuntu 22.10                 | 23        | 0.92%   |
| Linux Mint 19.3              | 23        | 0.92%   |
| Fedora 33                    | 23        | 0.92%   |
| Fedora 37                    | 22        | 0.88%   |
| Debian 12                    | 22        | 0.88%   |
| Linux Mint 21.2              | 21        | 0.84%   |
| OpenMandriva 23.08           | 20        | 0.8%    |
| Manjaro                      | 20        | 0.8%    |
| Fedora 36                    | 20        | 0.8%    |
| Ubuntu 23.04                 | 19        | 0.76%   |
| Linux Mint 21                | 19        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 723       | 30.95%  |
| OpenMandriva  | 345       | 14.77%  |
| Fedora        | 217       | 9.29%   |
| Linux Mint    | 209       | 8.95%   |
| Debian        | 92        | 3.94%   |
| Arch          | 72        | 3.08%   |
| Zorin         | 66        | 2.83%   |
| Pop!_OS       | 61        | 2.61%   |
| Manjaro       | 61        | 2.61%   |
| Kubuntu       | 50        | 2.14%   |
| Xubuntu       | 49        | 2.1%    |
| ROSA          | 42        | 1.8%    |
| Gentoo        | 42        | 1.8%    |
| openSUSE      | 34        | 1.46%   |
| KDE neon      | 26        | 1.11%   |
| Lubuntu       | 21        | 0.9%    |
| Kali          | 21        | 0.9%    |
| ArcoLinux     | 17        | 0.73%   |
| RHEL          | 15        | 0.64%   |
| Elementary    | 15        | 0.64%   |
| Ubuntu MATE   | 14        | 0.6%    |
| Endless       | 14        | 0.6%    |
| Ubuntu Unity  | 10        | 0.43%   |
| CentOS        | 9         | 0.39%   |
| SteamOS       | 8         | 0.34%   |
| EndeavourOS   | 8         | 0.34%   |
| LMDE          | 7         | 0.3%    |
| Void Linux    | 6         | 0.26%   |
| Parrot        | 6         | 0.26%   |
| NixOS         | 6         | 0.26%   |
| ACI           | 5         | 0.21%   |
| Ubuntu Budgie | 4         | 0.17%   |
| Rocky Linux   | 4         | 0.17%   |
| Nobara        | 4         | 0.17%   |
| MX            | 4         | 0.17%   |
| BlackPanther  | 4         | 0.17%   |
| Neptune OS    | 3         | 0.13%   |
| LinuxFX       | 3         | 0.13%   |
| Garuda Linux  | 3         | 0.13%   |
| Xero          | 2         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 116       | 4.25%   |
| 5.16.7-desktop-1omv4003  | 70        | 2.56%   |
| 5.14.7-desktop-1omv4050  | 55        | 2.01%   |
| 5.4.0-42-generic         | 34        | 1.24%   |
| 6.2.6-desktop-1omv2390   | 28        | 1.02%   |
| 6.1.1-desktop-1omv2290   | 28        | 1.02%   |
| 5.15.0-56-generic        | 24        | 0.88%   |
| 5.4.0-58-generic         | 23        | 0.84%   |
| 5.4.0-52-generic         | 22        | 0.81%   |
| 5.15.0-46-generic        | 21        | 0.77%   |
| 5.4.0-26-generic         | 20        | 0.73%   |
| 5.15.0-58-generic        | 17        | 0.62%   |
| 6.4.11-desktop-1omv2390  | 16        | 0.59%   |
| 5.15.0-52-generic        | 16        | 0.59%   |
| 5.11.0-27-generic        | 16        | 0.59%   |
| 5.3.0-40-generic         | 15        | 0.55%   |
| 5.0.0-37-generic         | 15        | 0.55%   |
| 5.13.0-30-generic        | 14        | 0.51%   |
| 6.6.2-desktop-1omv2390   | 13        | 0.48%   |
| 6.2.0-26-generic         | 13        | 0.48%   |
| 5.4.0-48-generic         | 12        | 0.44%   |
| 5.4.0-40-generic         | 12        | 0.44%   |
| 5.3.0-28-generic         | 12        | 0.44%   |
| 5.15.0-48-generic        | 12        | 0.44%   |
| 5.4.0-65-generic         | 11        | 0.4%    |
| 5.15.0-41-generic        | 11        | 0.4%    |
| 6.2.0-39-generic         | 10        | 0.37%   |
| 5.4.0-29-generic         | 10        | 0.37%   |
| 5.11.0-37-generic        | 10        | 0.37%   |
| 5.8.0-53-generic         | 9         | 0.33%   |
| 5.4.0-91-generic         | 9         | 0.33%   |
| 5.4.0-37-generic         | 9         | 0.33%   |
| 5.19.0-32-generic        | 9         | 0.33%   |
| 5.15.0-78-generic        | 9         | 0.33%   |
| 5.15.0-43-generic        | 9         | 0.33%   |
| 5.10.0-8-amd64           | 9         | 0.33%   |
| 4.15.0-43-generic        | 9         | 0.33%   |
| 6.2.0-33-generic         | 8         | 0.29%   |
| 6.1.0-13-amd64           | 8         | 0.29%   |
| 5.8.0-59-generic         | 8         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 319       | 12.41%  |
| 5.15.0  | 211       | 8.21%   |
| 5.10.14 | 116       | 4.51%   |
| 4.15.0  | 112       | 4.36%   |
| 5.8.0   | 101       | 3.93%   |
| 5.11.0  | 96        | 3.74%   |
| 5.13.0  | 94        | 3.66%   |
| 5.3.0   | 92        | 3.58%   |
| 5.19.0  | 73        | 2.84%   |
| 5.16.7  | 71        | 2.76%   |
| 5.0.0   | 71        | 2.76%   |
| 6.2.0   | 64        | 2.49%   |
| 4.18.0  | 57        | 2.22%   |
| 5.14.7  | 56        | 2.18%   |
| 5.10.0  | 44        | 1.71%   |
| 6.1.0   | 36        | 1.4%    |
| 6.2.6   | 35        | 1.36%   |
| 6.1.1   | 34        | 1.32%   |
| 6.5.0   | 32        | 1.25%   |
| 6.4.11  | 17        | 0.66%   |
| 4.19.0  | 17        | 0.66%   |
| 6.6.2   | 16        | 0.62%   |
| 6.0.0   | 12        | 0.47%   |
| 6.5.6   | 11        | 0.43%   |
| 3.10.0  | 11        | 0.43%   |
| 6.3.5   | 9         | 0.35%   |
| 5.14.0  | 9         | 0.35%   |
| 4.9.20  | 9         | 0.35%   |
| 5.16.11 | 8         | 0.31%   |
| 5.11.12 | 8         | 0.31%   |
| 6.2.9   | 7         | 0.27%   |
| 6.0.12  | 7         | 0.27%   |
| 5.17.0  | 7         | 0.27%   |
| 5.15.12 | 7         | 0.27%   |
| 6.6.9   | 6         | 0.23%   |
| 6.5.5   | 6         | 0.23%   |
| 6.4.6   | 6         | 0.23%   |
| 6.2.15  | 6         | 0.23%   |
| 5.9.16  | 6         | 0.23%   |
| 5.9.0   | 6         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4      | 343       | 13.48%  |
| 5.15     | 264       | 10.38%  |
| 5.10     | 204       | 8.02%   |
| 5.8      | 134       | 5.27%   |
| 6.2      | 130       | 5.11%   |
| 5.11     | 130       | 5.11%   |
| 6.1      | 114       | 4.48%   |
| 4.15     | 114       | 4.48%   |
| 5.13     | 112       | 4.4%    |
| 5.3      | 103       | 4.05%   |
| 5.16     | 102       | 4.01%   |
| 5.19     | 97        | 3.81%   |
| 5.14     | 85        | 3.34%   |
| 5.0      | 77        | 3.03%   |
| 6.5      | 67        | 2.63%   |
| 4.18     | 60        | 2.36%   |
| 6.6      | 51        | 2%      |
| 6.4      | 48        | 1.89%   |
| 6.0      | 39        | 1.53%   |
| 5.17     | 34        | 1.34%   |
| 6.3      | 29        | 1.14%   |
| 5.9      | 25        | 0.98%   |
| 5.18     | 24        | 0.94%   |
| 5.6      | 23        | 0.9%    |
| 4.19     | 22        | 0.86%   |
| 5.12     | 21        | 0.83%   |
| 4.9      | 20        | 0.79%   |
| 5.7      | 14        | 0.55%   |
| 3.10     | 12        | 0.47%   |
| 5.5      | 11        | 0.43%   |
| 4.4      | 6         | 0.24%   |
| 4.13     | 6         | 0.24%   |
| 5.1      | 4         | 0.16%   |
| 5.2      | 3         | 0.12%   |
| 4.17     | 3         | 0.12%   |
| 4.14     | 3         | 0.12%   |
| 6.7      | 2         | 0.08%   |
| 4.1      | 2         | 0.08%   |
| 5.10.164 | 1         | 0.04%   |
| 4.8      | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2208      | 96.42%  |
| i686    | 64        | 2.79%   |
| aarch64 | 15        | 0.66%   |
| armv7l  | 2         | 0.09%   |
| armv8l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 943       | 39.72%  |
| KDE5              | 558       | 23.5%   |
| Unknown           | 285       | 12.01%  |
| XFCE              | 172       | 7.25%   |
| X-Cinnamon        | 136       | 5.73%   |
| MATE              | 59        | 2.49%   |
| KDE               | 47        | 1.98%   |
| Cinnamon          | 36        | 1.52%   |
| LXQt              | 29        | 1.22%   |
| Pantheon          | 15        | 0.63%   |
| KDE4              | 13        | 0.55%   |
| GNOME Flashback   | 12        | 0.51%   |
| Unity             | 11        | 0.46%   |
| LXDE              | 11        | 0.46%   |
| i3                | 9         | 0.38%   |
| Budgie            | 7         | 0.29%   |
| openbox           | 5         | 0.21%   |
| Hyprland          | 4         | 0.17%   |
| awesome           | 4         | 0.17%   |
| sway              | 3         | 0.13%   |
| qtile             | 3         | 0.13%   |
| Yaru:ubuntu:GNOME | 1         | 0.04%   |
| XSession          | 1         | 0.04%   |
| xinitrc           | 1         | 0.04%   |
| xinit-compat      | 1         | 0.04%   |
| GNUstep           | 1         | 0.04%   |
| GNOME Classic     | 1         | 0.04%   |
| Enlightenment     | 1         | 0.04%   |
| DWM               | 1         | 0.04%   |
| Deepin            | 1         | 0.04%   |
| custom            | 1         | 0.04%   |
| Core              | 1         | 0.04%   |
| bspwm             | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1708      | 72.4%   |
| Wayland | 454       | 19.25%  |
| Unknown | 150       | 6.36%   |
| Tty     | 47        | 1.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1034      | 43.57%  |
| SDDM    | 535       | 22.55%  |
| GDM3    | 260       | 10.96%  |
| GDM     | 236       | 9.95%   |
| LightDM | 210       | 8.85%   |
| TDM     | 71        | 2.99%   |
| KDM     | 12        | 0.51%   |
| XDM     | 5         | 0.21%   |
| SLiM    | 5         | 0.21%   |
| LXDM    | 3         | 0.13%   |
| Ly      | 1         | 0.04%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| cs_CZ   | 1212      | 51.82%  |
| en_US   | 717       | 30.65%  |
| Unknown | 232       | 9.92%   |
| en_GB   | 56        | 2.39%   |
| C       | 43        | 1.84%   |
| ru_RU   | 25        | 1.07%   |
| sk_SK   | 12        | 0.51%   |
| pl_PL   | 8         | 0.34%   |
| POSIX   | 5         | 0.21%   |
| de_DE   | 5         | 0.21%   |
| uk_UA   | 3         | 0.13%   |
| it_IT   | 3         | 0.13%   |
| fr_FR   | 3         | 0.13%   |
| pt_PT   | 2         | 0.09%   |
| en_CA   | 2         | 0.09%   |
| tr_TR   | 1         | 0.04%   |
| ro_RO   | 1         | 0.04%   |
| fi_FI   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_NG   | 1         | 0.04%   |
| en_AU   | 1         | 0.04%   |
| en_150  | 1         | 0.04%   |
| el_GR   | 1         | 0.04%   |
| de_CH   | 1         | 0.04%   |
| C.UTF8  | 1         | 0.04%   |
| bg_BG   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1211      | 51.69%  |
| EFI  | 1132      | 48.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1549      | 65.75%  |
| Overlay  | 337       | 14.3%   |
| Btrfs    | 252       | 10.7%   |
| Unknown  | 64        | 2.72%   |
| Tmpfs    | 62        | 2.63%   |
| Xfs      | 57        | 2.42%   |
| Zfs      | 19        | 0.81%   |
| Ext2     | 5         | 0.21%   |
| Ext3     | 4         | 0.17%   |
| F2fs     | 3         | 0.13%   |
| Reiserfs | 2         | 0.08%   |
| Aufs     | 2         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1048      | 44.84%  |
| GPT     | 927       | 39.67%  |
| MBR     | 362       | 15.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2008      | 86.63%  |
| Yes       | 310       | 13.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1556      | 66.61%  |
| Yes       | 780       | 33.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 480       | 20.97%  |
| Lenovo                  | 437       | 19.09%  |
| Hewlett-Packard         | 354       | 15.47%  |
| Dell                    | 245       | 10.7%   |
| Gigabyte Technology     | 152       | 6.64%   |
| Acer                    | 149       | 6.51%   |
| MSI                     | 138       | 6.03%   |
| ASRock                  | 56        | 2.45%   |
| Intel                   | 32        | 1.4%    |
| UMAX                    | 28        | 1.22%   |
| Fujitsu                 | 20        | 0.87%   |
| Toshiba                 | 17        | 0.74%   |
| Sony                    | 17        | 0.74%   |
| Raspberry Pi Foundation | 14        | 0.61%   |
| Apple                   | 10        | 0.44%   |
| Unknown                 | 10        | 0.44%   |
| Valve                   | 8         | 0.35%   |
| Pegatron                | 8         | 0.35%   |
| Google                  | 8         | 0.35%   |
| Fujitsu Siemens         | 8         | 0.35%   |
| HUAWEI                  | 7         | 0.31%   |
| TUXEDO                  | 6         | 0.26%   |
| Supermicro              | 6         | 0.26%   |
| AMI                     | 6         | 0.26%   |
| Packard Bell            | 5         | 0.22%   |
| Timi                    | 4         | 0.17%   |
| Microsoft               | 4         | 0.17%   |
| ZOTAC                   | 3         | 0.13%   |
| Notebook                | 3         | 0.13%   |
| Foxconn                 | 3         | 0.13%   |
| Dynabook                | 3         | 0.13%   |
| Samsung Electronics     | 2         | 0.09%   |
| Insyde                  | 2         | 0.09%   |
| IBM                     | 2         | 0.09%   |
| Clientron               | 2         | 0.09%   |
| Chuwi                   | 2         | 0.09%   |
| Biostar                 | 2         | 0.09%   |
| ASRockRack              | 2         | 0.09%   |
| Alienware               | 2         | 0.09%   |
| Wortmann AG             | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUS UX31E                        | 127       | 5.55%   |
| Unknown                           | 15        | 0.66%   |
| ASUS All Series                   | 14        | 0.61%   |
| MSI MS-7C91                       | 11        | 0.48%   |
| Valve Jupiter                     | 8         | 0.35%   |
| MSI MS-7C02                       | 7         | 0.31%   |
| MSI MS-7A34                       | 7         | 0.31%   |
| MSI MS-7693                       | 7         | 0.31%   |
| HP ProBook 455 G7                 | 7         | 0.31%   |
| Dell Latitude E6420               | 7         | 0.31%   |
| HP ProLiant DL380e Gen8           | 6         | 0.26%   |
| HP ProBook 4540s                  | 6         | 0.26%   |
| HP EliteBook 845 G8 Notebook PC   | 6         | 0.26%   |
| RPi Raspberry Pi                  | 5         | 0.22%   |
| MSI MS-7592                       | 5         | 0.22%   |
| Lenovo ThinkPad E14 20RA001LMC    | 5         | 0.22%   |
| Lenovo IdeaPad S145-15AST 81N3    | 5         | 0.22%   |
| HP ProBook 4530s                  | 5         | 0.22%   |
| HP ProBook 450 G5                 | 5         | 0.22%   |
| HP Pavilion dv7                   | 5         | 0.22%   |
| HP EliteBook 840 G6               | 5         | 0.22%   |
| HP EliteBook 840 G3               | 5         | 0.22%   |
| Dell XPS 15 9560                  | 5         | 0.22%   |
| Dell Latitude E6400               | 5         | 0.22%   |
| Dell Latitude 5401                | 5         | 0.22%   |
| ASUS P5G41T-M LX                  | 5         | 0.22%   |
| HP ProDesk 405 G6 Desktop Mini PC | 4         | 0.17%   |
| HP Notebook                       | 4         | 0.17%   |
| HP Compaq 8200 Elite SFF PC       | 4         | 0.17%   |
| HP 250 G6 Notebook PC             | 4         | 0.17%   |
| HP 250 G3                         | 4         | 0.17%   |
| Dell XPS 15 7590                  | 4         | 0.17%   |
| Dell Precision M6500              | 4         | 0.17%   |
| Dell Latitude E7440               | 4         | 0.17%   |
| Dell Latitude E5470               | 4         | 0.17%   |
| Dell Latitude 5480                | 4         | 0.17%   |
| Acer Extensa 5620                 | 4         | 0.17%   |
| UMAX VisionBook-N12R              | 3         | 0.13%   |
| UMAX VisionBook 15Wg Plus         | 3         | 0.13%   |
| MSI MS-7817                       | 3         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 201       | 8.78%   |
| ASUS UX31E         | 127       | 5.55%   |
| Dell Latitude      | 102       | 4.46%   |
| Acer Aspire        | 86        | 3.76%   |
| Lenovo IdeaPad     | 83        | 3.63%   |
| HP EliteBook       | 76        | 3.32%   |
| HP ProBook         | 66        | 2.88%   |
| HP Compaq          | 38        | 1.66%   |
| ASUS ROG           | 37        | 1.62%   |
| HP Pavilion        | 34        | 1.49%   |
| ASUS PRIME         | 34        | 1.49%   |
| Dell XPS           | 30        | 1.31%   |
| Dell Inspiron      | 30        | 1.31%   |
| Lenovo Yoga        | 28        | 1.22%   |
| Dell Precision     | 28        | 1.22%   |
| Dell OptiPlex      | 27        | 1.18%   |
| ASUS TUF           | 27        | 1.18%   |
| Lenovo ThinkCentre | 21        | 0.92%   |
| HP ZBook           | 19        | 0.83%   |
| UMAX VisionBook    | 18        | 0.79%   |
| Lenovo Legion      | 17        | 0.74%   |
| HP Laptop          | 17        | 0.74%   |
| ASUS Zenbook       | 17        | 0.74%   |
| ASUS VivoBook      | 17        | 0.74%   |
| Toshiba Satellite  | 16        | 0.7%    |
| Acer Extensa       | 15        | 0.66%   |
| Unknown            | 15        | 0.66%   |
| RPi Raspberry      | 14        | 0.61%   |
| ASUS All           | 14        | 0.61%   |
| Acer TravelMate    | 14        | 0.61%   |
| HP ENVY            | 13        | 0.57%   |
| Acer Swift         | 13        | 0.57%   |
| HP ProDesk         | 12        | 0.52%   |
| HP 250             | 12        | 0.52%   |
| Fujitsu LIFEBOOK   | 12        | 0.52%   |
| Dell Vostro        | 12        | 0.52%   |
| MSI MS-7C91        | 11        | 0.48%   |
| ASUS ASUS          | 11        | 0.48%   |
| Lenovo ThinkBook   | 10        | 0.44%   |
| Valve Jupiter      | 8         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 263       | 11.49%  |
| 2020    | 229       | 10%     |
| 2018    | 190       | 8.3%    |
| 2019    | 178       | 7.78%   |
| 2021    | 177       | 7.73%   |
| 2017    | 156       | 6.82%   |
| 2012    | 151       | 6.6%    |
| 2014    | 129       | 5.64%   |
| 2013    | 118       | 5.16%   |
| 2015    | 106       | 4.63%   |
| 2008    | 103       | 4.5%    |
| 2016    | 92        | 4.02%   |
| 2010    | 85        | 3.71%   |
| 2022    | 84        | 3.67%   |
| 2009    | 76        | 3.32%   |
| 2007    | 68        | 2.97%   |
| 2023    | 26        | 1.14%   |
| 2006    | 26        | 1.14%   |
| Unknown | 18        | 0.79%   |
| 2005    | 9         | 0.39%   |
| 2004    | 4         | 0.17%   |
| 2000    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1398      | 61.07%  |
| Desktop        | 721       | 31.5%   |
| Convertible    | 63        | 2.75%   |
| Mini pc        | 36        | 1.57%   |
| Tablet         | 20        | 0.87%   |
| System on chip | 17        | 0.74%   |
| Server         | 17        | 0.74%   |
| All in one     | 16        | 0.7%    |
| Phone          | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2092      | 90.48%  |
| Enabled  | 220       | 9.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2281      | 99.65%  |
| Yes  | 8         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 556       | 23.83%  |
| 4.01-8.0        | 429       | 18.39%  |
| 8.01-16.0       | 411       | 17.62%  |
| 16.01-24.0      | 398       | 17.06%  |
| 32.01-64.0      | 252       | 10.8%   |
| 1.01-2.0        | 112       | 4.8%    |
| 64.01-256.0     | 62        | 2.66%   |
| 24.01-32.0      | 50        | 2.14%   |
| 2.01-3.0        | 40        | 1.71%   |
| 0.51-1.0        | 19        | 0.81%   |
| More than 256.0 | 2         | 0.09%   |
| 0.01-0.5        | 2         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 891       | 34.97%  |
| 2.01-3.0    | 554       | 21.74%  |
| 4.01-8.0    | 411       | 16.13%  |
| 3.01-4.0    | 316       | 12.4%   |
| 0.51-1.0    | 152       | 5.97%   |
| 8.01-16.0   | 145       | 5.69%   |
| 0.01-0.5    | 36        | 1.41%   |
| 16.01-24.0  | 26        | 1.02%   |
| 32.01-64.0  | 9         | 0.35%   |
| 24.01-32.0  | 6         | 0.24%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1533      | 64.77%  |
| 2      | 507       | 21.42%  |
| 3      | 157       | 6.63%   |
| 4      | 68        | 2.87%   |
| 5      | 39        | 1.65%   |
| 0      | 28        | 1.18%   |
| 6      | 18        | 0.76%   |
| 7      | 12        | 0.51%   |
| 8      | 4         | 0.17%   |
| 9      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1529      | 66.31%  |
| Yes       | 777       | 33.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1986      | 86.31%  |
| No        | 315       | 13.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1713      | 74.45%  |
| No        | 588       | 25.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1347      | 58.14%  |
| No        | 970       | 41.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Czechia | 2289      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Prague               | 892       | 37.28%  |
| Brno                 | 189       | 7.9%    |
| Ostrava              | 71        | 2.97%   |
| Pilsen               | 53        | 2.21%   |
| Liberec              | 37        | 1.55%   |
| Olomouc              | 33        | 1.38%   |
| Pardubice            | 32        | 1.34%   |
| Hradec Králové     | 31        | 1.3%    |
| České Budějovice  | 27        | 1.13%   |
| Zlín                | 21        | 0.88%   |
| Brdo                 | 20        | 0.84%   |
| Havířov            | 18        | 0.75%   |
| Znojmo               | 16        | 0.67%   |
| Most                 | 14        | 0.59%   |
| Chomutov             | 14        | 0.59%   |
| Jihlava              | 12        | 0.5%    |
| Ústí nad Labem     | 11        | 0.46%   |
| Opava                | 11        | 0.46%   |
| Kladno               | 11        | 0.46%   |
| Frýdek-Místek      | 11        | 0.46%   |
| Mladá Boleslav      | 10        | 0.42%   |
| Přerov              | 9         | 0.38%   |
| Tábor               | 8         | 0.33%   |
| Šlapanice           | 8         | 0.33%   |
| Roznov pod Radhostem | 8         | 0.33%   |
| Litoměřice         | 8         | 0.33%   |
| Karlovy Vary         | 8         | 0.33%   |
| Uherské Hradiště  | 7         | 0.29%   |
| Třebíč            | 7         | 0.29%   |
| Teplice              | 7         | 0.29%   |
| Příbram            | 7         | 0.29%   |
| Prelouc              | 7         | 0.29%   |
| Praha 10             | 7         | 0.29%   |
| Kralupy nad Vltavou  | 7         | 0.29%   |
| Jedovnice            | 7         | 0.29%   |
| Horice               | 7         | 0.29%   |
| Český Těšín     | 7         | 0.29%   |
| Česká Lípa        | 7         | 0.29%   |
| Celakovice           | 7         | 0.29%   |
| As                   | 7         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 535       | 754    | 16.72%  |
| WDC                         | 486       | 794    | 15.19%  |
| Seagate                     | 438       | 667    | 13.69%  |
| SanDisk                     | 240       | 265    | 7.5%    |
| Kingston                    | 221       | 274    | 6.91%   |
| Toshiba                     | 176       | 217    | 5.5%    |
| Unknown                     | 131       | 192    | 4.09%   |
| SK hynix                    | 95        | 112    | 2.97%   |
| Hitachi                     | 92        | 107    | 2.88%   |
| Intel                       | 86        | 104    | 2.69%   |
| A-DATA Technology           | 78        | 93     | 2.44%   |
| Crucial                     | 74        | 90     | 2.31%   |
| Micron Technology           | 71        | 96     | 2.22%   |
| Patriot                     | 55        | 66     | 1.72%   |
| HGST                        | 54        | 67     | 1.69%   |
| Apacer                      | 28        | 38     | 0.88%   |
| KIOXIA                      | 26        | 39     | 0.81%   |
| Transcend                   | 21        | 31     | 0.66%   |
| Verbatim                    | 16        | 16     | 0.5%    |
| Phison                      | 16        | 28     | 0.5%    |
| Gigabyte Technology         | 15        | 26     | 0.47%   |
| Unknown                     | 14        | 15     | 0.44%   |
| Silicon Motion              | 11        | 13     | 0.34%   |
| OCZ                         | 11        | 34     | 0.34%   |
| LITEONIT                    | 11        | 14     | 0.34%   |
| Kingston Technology Company | 11        | 12     | 0.34%   |
| Phison Electronics          | 10        | 12     | 0.31%   |
| Fujitsu                     | 10        | 11     | 0.31%   |
| China                       | 10        | 11     | 0.31%   |
| Maxtor                      | 9         | 13     | 0.28%   |
| GOODRAM                     | 9         | 12     | 0.28%   |
| Micron/Crucial Technology   | 8         | 8      | 0.25%   |
| LITEON                      | 8         | 9      | 0.25%   |
| Apple                       | 8         | 13     | 0.25%   |
| XPG                         | 7         | 14     | 0.22%   |
| Realtek Semiconductor       | 7         | 14     | 0.22%   |
| UMAX                        | 6         | 6      | 0.19%   |
| JMicron Technology          | 6         | 7      | 0.19%   |
| Corsair                     | 5         | 5      | 0.16%   |
| ASMedia                     | 5         | 7      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                             | 126       | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 35        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                    | 31        | 0.88%   |
| Samsung SSD 860 EVO 500GB                          | 28        | 0.79%   |
| Kingston SA400S37480G 480GB SSD                    | 26        | 0.74%   |
| Unknown MMC Card  64GB                             | 25        | 0.71%   |
| Unknown MMC Card  32GB                             | 24        | 0.68%   |
| Samsung NVMe SSD Drive 512GB                       | 24        | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 22        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                    | 22        | 0.62%   |
| Seagate ST1000LM035-1RK172 1TB                     | 21        | 0.6%    |
| Samsung SSD 850 EVO 250GB                          | 20        | 0.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 20        | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 19        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                     | 17        | 0.48%   |
| HGST HTS721010A9E630 1TB                           | 17        | 0.48%   |
| Samsung SSD 980 1TB                                | 16        | 0.45%   |
| Samsung NVMe SSD Drive 500GB                       | 16        | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB                     | 15        | 0.43%   |
| Seagate ST3500418AS 500GB                          | 14        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 14        | 0.4%    |
| Samsung SSD 860 EVO 1TB                            | 14        | 0.4%    |
| Unknown                                            | 14        | 0.4%    |
| Toshiba NVMe SSD Drive 256GB                       | 13        | 0.37%   |
| Seagate ST500LT012-1DG142 500GB                    | 12        | 0.34%   |
| SanDisk NVMe SSD Drive 512GB                       | 12        | 0.34%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 12        | 0.34%   |
| Patriot Burst 480GB SSD                            | 12        | 0.34%   |
| Patriot Burst 120GB SSD                            | 12        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                   | 12        | 0.34%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 11        | 0.31%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 11        | 0.31%   |
| Toshiba MQ01ABD100 1TB                             | 11        | 0.31%   |
| Seagate ST500DM002-1BD142 500GB                    | 11        | 0.31%   |
| SanDisk NVMe SSD Drive 1TB                         | 11        | 0.31%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                     | 11        | 0.31%   |
| Kingston SKC3000D2048G 2TB                         | 11        | 0.31%   |
| WDC WD10EZEX-08M2NA0 1TB                           | 10        | 0.28%   |
| Unknown MMC Card  128GB                            | 10        | 0.28%   |
| Samsung SSD 860 EVO 250GB                          | 10        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 428       | 647    | 37.61%  |
| WDC                 | 370       | 614    | 32.51%  |
| Toshiba             | 107       | 122    | 9.4%    |
| Hitachi             | 92        | 107    | 8.08%   |
| HGST                | 54        | 67     | 4.75%   |
| Samsung Electronics | 52        | 81     | 4.57%   |
| Fujitsu             | 10        | 11     | 0.88%   |
| Maxtor              | 9         | 13     | 0.79%   |
| Unknown             | 4         | 4      | 0.35%   |
| JMicron Technology  | 3         | 3      | 0.26%   |
| pqi                 | 2         | 2      | 0.18%   |
| Apple               | 2         | 7      | 0.18%   |
| TO Exter            | 1         | 2      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| External            | 1         | 1      | 0.09%   |
| ASUSTOR             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 210       | 266    | 19.13%  |
| SanDisk             | 172       | 180    | 15.66%  |
| Kingston            | 167       | 209    | 15.21%  |
| WDC                 | 88        | 119    | 8.01%   |
| A-DATA Technology   | 72        | 85     | 6.56%   |
| Crucial             | 66        | 82     | 6.01%   |
| Patriot             | 53        | 64     | 4.83%   |
| Intel               | 39        | 47     | 3.55%   |
| Micron Technology   | 26        | 39     | 2.37%   |
| Apacer              | 25        | 33     | 2.28%   |
| Transcend           | 20        | 28     | 1.82%   |
| Verbatim            | 16        | 16     | 1.46%   |
| Toshiba             | 15        | 19     | 1.37%   |
| SK hynix            | 15        | 16     | 1.37%   |
| LITEONIT            | 11        | 14     | 1%      |
| China               | 10        | 11     | 0.91%   |
| OCZ                 | 9         | 16     | 0.82%   |
| GOODRAM             | 8         | 11     | 0.73%   |
| Gigabyte Technology | 7         | 14     | 0.64%   |
| UMAX                | 6         | 6      | 0.55%   |
| LITEON              | 6         | 7      | 0.55%   |
| Seagate             | 5         | 6      | 0.46%   |
| Apple               | 5         | 5      | 0.46%   |
| Team                | 3         | 3      | 0.27%   |
| SPCC                | 3         | 3      | 0.27%   |
| HPE                 | 3         | 3      | 0.27%   |
| Hewlett-Packard     | 3         | 3      | 0.27%   |
| ASMedia             | 3         | 4      | 0.27%   |
| Unknown             | 2         | 8      | 0.18%   |
| HS-SSD-C100         | 2         | 2      | 0.18%   |
| FORESEE             | 2         | 2      | 0.18%   |
| ASMT                | 2         | 2      | 0.18%   |
| ADATA SU            | 2         | 2      | 0.18%   |
| WDC WDS1            | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| UMIS                | 1         | 1      | 0.09%   |
| TCSUNBOW            | 1         | 1      | 0.09%   |
| T-CREATE            | 1         | 1      | 0.09%   |
| ShanDianZhe         | 1         | 1      | 0.09%   |
| SATAFIRM            | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 988       | 1347   | 34.03%  |
| HDD     | 968       | 1684   | 33.34%  |
| NVMe    | 787       | 1141   | 27.11%  |
| MMC     | 142       | 196    | 4.89%   |
| Unknown | 18        | 30     | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1618      | 2946   | 61.31%  |
| NVMe | 786       | 1138   | 29.78%  |
| MMC  | 142       | 196    | 5.38%   |
| SAS  | 93        | 118    | 3.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1293      | 1899   | 63.63%  |
| 0.51-1.0   | 495       | 703    | 24.36%  |
| 1.01-2.0   | 118       | 219    | 5.81%   |
| 3.01-4.0   | 43        | 61     | 2.12%   |
| 2.01-3.0   | 34        | 55     | 1.67%   |
| 4.01-10.0  | 33        | 66     | 1.62%   |
| 10.01-20.0 | 16        | 28     | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 597       | 24.66%  |
| 251-500        | 509       | 21.02%  |
| 1-20           | 337       | 13.92%  |
| 501-1000       | 306       | 12.64%  |
| 1001-2000      | 163       | 6.73%   |
| 51-100         | 163       | 6.73%   |
| More than 3000 | 104       | 4.3%    |
| Unknown        | 99        | 4.09%   |
| 21-50          | 91        | 3.76%   |
| 2001-3000      | 52        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1055      | 42.08%  |
| 21-50          | 330       | 13.16%  |
| 101-250        | 310       | 12.37%  |
| 51-100         | 243       | 9.69%   |
| 251-500        | 201       | 8.02%   |
| 501-1000       | 128       | 5.11%   |
| Unknown        | 99        | 3.95%   |
| 1001-2000      | 66        | 2.63%   |
| More than 3000 | 48        | 1.91%   |
| 2001-3000      | 27        | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 126       | 127    | 39.5%   |
| HGST HTS725050A7E630 500GB            | 4         | 5      | 1.25%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 4      | 0.94%   |
| WDC WD60EFRX-68L0BN1 6TB              | 2         | 3      | 0.63%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.63%   |
| Toshiba MK1234GSX 120GB               | 2         | 2      | 0.63%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.63%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 3      | 0.63%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 0.63%   |
| Seagate ST3250410AS 250GB             | 2         | 4      | 0.63%   |
| Seagate ST3160318AS 160GB             | 2         | 2      | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 3      | 0.63%   |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.63%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.63%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 0.63%   |
| Hitachi HTS541610J9SA00 100GB         | 2         | 2      | 0.63%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.31%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 1      | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.31%   |
| WDC WD800BB-00JHA0 80GB               | 1         | 1      | 0.31%   |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.31%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.31%   |
| WDC WD7500AADS-00M2B0 752GB           | 1         | 1      | 0.31%   |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.31%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.31%   |
| WDC WD5003ABYX-50WERA1 500GB          | 1         | 1      | 0.31%   |
| WDC WD5000AZRX-00A8LB0 500GB          | 1         | 1      | 0.31%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 0.31%   |
| WDC WD5000AAKS-00V0A0 500GB           | 1         | 1      | 0.31%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.31%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 0.31%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.31%   |
| WDC WD2502ABYS-02B7A0 256GB           | 1         | 1      | 0.31%   |
| WDC WD2500BPVT-22JJ5T0 250GB          | 1         | 1      | 0.31%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 0.31%   |
| WDC WD2500AAKX-75U6AA0 250GB          | 1         | 1      | 0.31%   |
| WDC WD2500AAKX-60U6AA0 250GB          | 1         | 1      | 0.31%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk               | 128       | 129    | 40.76%  |
| Seagate               | 48        | 61     | 15.29%  |
| WDC                   | 38        | 48     | 12.1%   |
| Hitachi               | 20        | 20     | 6.37%   |
| Samsung Electronics   | 19        | 23     | 6.05%   |
| Toshiba               | 15        | 18     | 4.78%   |
| HGST                  | 10        | 11     | 3.18%   |
| Kingston              | 7         | 7      | 2.23%   |
| SK hynix              | 6         | 7      | 1.91%   |
| Micron Technology     | 4         | 4      | 1.27%   |
| Intel                 | 3         | 3      | 0.96%   |
| Crucial               | 3         | 3      | 0.96%   |
| A-DATA Technology     | 3         | 5      | 0.96%   |
| SPCC                  | 1         | 1      | 0.32%   |
| SATAFIRM              | 1         | 1      | 0.32%   |
| Realtek Semiconductor | 1         | 4      | 0.32%   |
| Patriot               | 1         | 1      | 0.32%   |
| Maxtor                | 1         | 1      | 0.32%   |
| LITEONIT              | 1         | 2      | 0.32%   |
| IBM/Hitachi           | 1         | 1      | 0.32%   |
| HS-SSD-C100           | 1         | 1      | 0.32%   |
| Gigabyte Technology   | 1         | 1      | 0.32%   |
| Fujitsu               | 1         | 1      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 61     | 35.04%  |
| WDC                 | 33        | 42     | 24.09%  |
| Hitachi             | 20        | 20     | 14.6%   |
| Toshiba             | 15        | 18     | 10.95%  |
| HGST                | 10        | 11     | 7.3%    |
| Samsung Electronics | 8         | 10     | 5.84%   |
| Maxtor              | 1         | 1      | 0.73%   |
| IBM/Hitachi         | 1         | 1      | 0.73%   |
| Fujitsu             | 1         | 1      | 0.73%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 164       | 168    | 52.9%   |
| HDD  | 132       | 165    | 42.58%  |
| NVMe | 14        | 20     | 4.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 2         | 4      | 66.67%  |
| Unknown 00000  16GB       | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 66.67%  |
| Unknown | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1247      | 2456   | 50.53%  |
| Works    | 913       | 1584   | 36.99%  |
| Malfunc  | 305       | 353    | 12.36%  |
| Failed   | 3         | 5      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1463      | 50.62%  |
| AMD                                     | 447       | 15.47%  |
| Samsung Electronics                     | 306       | 10.59%  |
| SanDisk                                 | 108       | 3.74%   |
| SK hynix                                | 75        | 2.6%    |
| Kingston Technology Company             | 69        | 2.39%   |
| Toshiba America Info Systems            | 53        | 1.83%   |
| Micron Technology                       | 45        | 1.56%   |
| JMicron Technology                      | 37        | 1.28%   |
| Phison Electronics                      | 36        | 1.25%   |
| ASMedia Technology                      | 34        | 1.18%   |
| Nvidia                                  | 30        | 1.04%   |
| KIOXIA                                  | 29        | 1%      |
| Marvell Technology Group                | 27        | 0.93%   |
| Silicon Motion                          | 17        | 0.59%   |
| ADATA Technology                        | 16        | 0.55%   |
| Micron/Crucial Technology               | 15        | 0.52%   |
| VIA Technologies                        | 11        | 0.38%   |
| Realtek Semiconductor                   | 8         | 0.28%   |
| Seagate Technology                      | 7         | 0.24%   |
| Hewlett-Packard                         | 6         | 0.21%   |
| Union Memory (Shenzhen)                 | 5         | 0.17%   |
| Solid State Storage Technology          | 4         | 0.14%   |
| Silicon Image                           | 4         | 0.14%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.14%   |
| Lite-On Technology                      | 4         | 0.14%   |
| Broadcom / LSI                          | 4         | 0.14%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.1%    |
| LSI Logic / Symbios Logic               | 3         | 0.1%    |
| Lenovo                                  | 3         | 0.1%    |
| Adaptec                                 | 3         | 0.1%    |
| OCZ Technology Group                    | 2         | 0.07%   |
| Integrated Technology Express           | 2         | 0.07%   |
| Western Digital                         | 1         | 0.03%   |
| Solidigm                                | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| Promise Technology                      | 1         | 0.03%   |
| O2 Micro                                | 1         | 0.03%   |
| INNOGRIT                                | 1         | 0.03%   |
| Chelsio Communications                  | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 282       | 8.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 193       | 5.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 137       | 4.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 99        | 2.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 87        | 2.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 84        | 2.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 83        | 2.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 1.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 58        | 1.73%   |
| AMD 400 Series Chipset SATA Controller                                         | 58        | 1.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 52        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 46        | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 45        | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 44        | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                         | 44        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 43        | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 43        | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 40        | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 38        | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 35        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 34        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 33        | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 32        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 31        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31        | 0.93%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 31        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 31        | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 29        | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 28        | 0.84%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 27        | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 26        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                             | 24        | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 0.72%   |
| Intel SATA Controller [RAID mode]                                              | 23        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 23        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 23        | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 22        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1606      | 55.11%  |
| NVMe | 794       | 27.25%  |
| IDE  | 324       | 11.12%  |
| RAID | 176       | 6.04%   |
| SAS  | 10        | 0.34%   |
| SCSI | 4         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1682      | 73.48%  |
| AMD      | 589       | 25.73%  |
| ARM      | 17        | 0.74%   |
| QUALCOMM | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz          | 127       | 5.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 25        | 1.09%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 20        | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor          | 20        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 19        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 18        | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 18        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 18        | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 18        | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 17        | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 17        | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 15        | 0.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 15        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 14        | 0.61%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 14        | 0.61%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 14        | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics     | 14        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 13        | 0.56%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 13        | 0.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 13        | 0.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 13        | 0.56%   |
| ARM Processor                              | 13        | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 12        | 0.52%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 12        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 12        | 0.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 12        | 0.52%   |
| AMD Ryzen 5 5600H with Radeon Graphics     | 12        | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 11        | 0.48%   |
| Intel Core i7-10850H CPU @ 2.70GHz         | 11        | 0.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 11        | 0.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics     | 11        | 0.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 10        | 0.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 10        | 0.43%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 10        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 10        | 0.43%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 10        | 0.43%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 10        | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz          | 9         | 0.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz       | 9         | 0.39%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 9         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 487       | 21.18%  |
| Intel Core i5           | 407       | 17.7%   |
| Other                   | 163       | 7.09%   |
| AMD Ryzen 5             | 162       | 7.05%   |
| Intel Celeron           | 136       | 5.92%   |
| Intel Core 2 Duo        | 121       | 5.26%   |
| Intel Core i3           | 116       | 5.05%   |
| AMD Ryzen 7             | 104       | 4.52%   |
| Intel Pentium           | 68        | 2.96%   |
| Intel Xeon              | 45        | 1.96%   |
| Intel Atom              | 41        | 1.78%   |
| AMD FX                  | 37        | 1.61%   |
| AMD Ryzen 7 PRO         | 36        | 1.57%   |
| AMD Ryzen 9             | 29        | 1.26%   |
| Intel Pentium Dual-Core | 26        | 1.13%   |
| AMD Ryzen 3             | 23        | 1%      |
| AMD A4                  | 20        | 0.87%   |
| AMD A8                  | 17        | 0.74%   |
| AMD Ryzen 5 PRO         | 16        | 0.7%    |
| AMD A6                  | 16        | 0.7%    |
| Intel Core 2            | 14        | 0.61%   |
| Intel Pentium Dual      | 12        | 0.52%   |
| AMD Athlon 64 X2        | 12        | 0.52%   |
| Intel Pentium Silver    | 11        | 0.48%   |
| Intel Core 2 Quad       | 11        | 0.48%   |
| Intel Core i9           | 10        | 0.43%   |
| AMD Phenom II X4        | 10        | 0.43%   |
| AMD A10                 | 10        | 0.43%   |
| AMD Athlon II X2        | 9         | 0.39%   |
| AMD Athlon              | 9         | 0.39%   |
| Intel Genuine           | 8         | 0.35%   |
| Intel Celeron M         | 8         | 0.35%   |
| AMD E1                  | 7         | 0.3%    |
| Intel Pentium Gold      | 6         | 0.26%   |
| Intel Pentium 4         | 5         | 0.22%   |
| Intel Celeron Dual-Core | 5         | 0.22%   |
| AMD Sempron             | 5         | 0.22%   |
| Intel Pentium M         | 4         | 0.17%   |
| Intel Pentium D         | 4         | 0.17%   |
| AMD Turion II           | 4         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 967       | 42.03%  |
| 4       | 735       | 31.94%  |
| 6       | 259       | 11.26%  |
| 8       | 171       | 7.43%   |
| 1       | 64        | 2.78%   |
| 12      | 41        | 1.78%   |
| 3       | 14        | 0.61%   |
| 16      | 13        | 0.56%   |
| 14      | 13        | 0.56%   |
| 10      | 13        | 0.56%   |
| 24      | 5         | 0.22%   |
| Unknown | 3         | 0.13%   |
| 32      | 1         | 0.04%   |
| 28      | 1         | 0.04%   |
| 20      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2272      | 99.26%  |
| 2      | 17        | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1497      | 65.26%  |
| 1       | 793       | 34.57%  |
| Unknown | 3         | 0.13%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2228      | 97%     |
| Unknown        | 38        | 1.65%   |
| 32-bit         | 27        | 1.18%   |
| 64-bit         | 4         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 627       | 26.27%  |
| 0x206a7    | 218       | 9.13%   |
| 0x306c3    | 82        | 3.44%   |
| 0x1067a    | 77        | 3.23%   |
| 0x306a9    | 72        | 3.02%   |
| 0x906ea    | 51        | 2.14%   |
| 0x806ec    | 51        | 2.14%   |
| 0x806ea    | 48        | 2.01%   |
| 0x806c1    | 41        | 1.72%   |
| 0x406e3    | 39        | 1.63%   |
| 0x0a50000c | 39        | 1.63%   |
| 0x08600106 | 37        | 1.55%   |
| 0x806e9    | 34        | 1.42%   |
| 0x506e3    | 34        | 1.42%   |
| 0x40651    | 34        | 1.42%   |
| 0x6fd      | 32        | 1.34%   |
| 0x906e9    | 31        | 1.3%    |
| 0x306d4    | 26        | 1.09%   |
| 0x08701021 | 26        | 1.09%   |
| 0x30678    | 24        | 1.01%   |
| 0x10676    | 22        | 0.92%   |
| 0x6fb      | 21        | 0.88%   |
| 0x406c4    | 20        | 0.84%   |
| 0x010000c8 | 20        | 0.84%   |
| 0x20655    | 19        | 0.8%    |
| 0x06000852 | 19        | 0.8%    |
| 0x706a1    | 18        | 0.75%   |
| 0x0800820d | 18        | 0.75%   |
| 0xa0652    | 16        | 0.67%   |
| 0x706a8    | 16        | 0.67%   |
| 0x08608103 | 16        | 0.67%   |
| 0x08600104 | 16        | 0.67%   |
| 0x906ed    | 15        | 0.63%   |
| 0x706e5    | 15        | 0.63%   |
| 0x506c9    | 15        | 0.63%   |
| 0x08108102 | 15        | 0.63%   |
| 0x06006705 | 14        | 0.59%   |
| 0x406c3    | 13        | 0.54%   |
| 0x08701013 | 13        | 0.54%   |
| 0x06001119 | 13        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 329       | 14.35%  |
| SandyBridge      | 273       | 11.91%  |
| Haswell          | 164       | 7.15%   |
| Zen 2            | 135       | 5.89%   |
| Penryn           | 127       | 5.54%   |
| IvyBridge        | 112       | 4.88%   |
| Zen 3            | 101       | 4.4%    |
| Skylake          | 100       | 4.36%   |
| Unknown          | 90        | 3.92%   |
| Core             | 83        | 3.62%   |
| Silvermont       | 80        | 3.49%   |
| TigerLake        | 61        | 2.66%   |
| Zen+             | 50        | 2.18%   |
| Goldmont plus    | 48        | 2.09%   |
| Westmere         | 47        | 2.05%   |
| Piledriver       | 46        | 2.01%   |
| Alderlake Hybrid | 46        | 2.01%   |
| Zen              | 44        | 1.92%   |
| CometLake        | 44        | 1.92%   |
| K10              | 41        | 1.79%   |
| Broadwell        | 38        | 1.66%   |
| K8 Hammer        | 29        | 1.26%   |
| Excavator        | 29        | 1.26%   |
| IceLake          | 27        | 1.18%   |
| Goldmont         | 19        | 0.83%   |
| Bonnell          | 19        | 0.83%   |
| Nehalem          | 17        | 0.74%   |
| Steamroller      | 14        | 0.61%   |
| P6               | 14        | 0.61%   |
| Puma             | 13        | 0.57%   |
| NetBurst         | 11        | 0.48%   |
| Bobcat           | 11        | 0.48%   |
| Jaguar           | 10        | 0.44%   |
| Tremont          | 7         | 0.31%   |
| K10 Llano        | 6         | 0.26%   |
| Bulldozer        | 4         | 0.17%   |
| K8 & K10 hybrid  | 3         | 0.13%   |
| K6               | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1347      | 50.17%  |
| Nvidia                           | 675       | 25.14%  |
| AMD                              | 639       | 23.8%   |
| Matrox Electronics Systems       | 14        | 0.52%   |
| ASPEED Technology                | 5         | 0.19%   |
| VIA Technologies                 | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 232       | 8.32%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 77        | 2.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 2.51%   |
| Intel UHD Graphics 620                                                                   | 65        | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 51        | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 49        | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 48        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 48        | 1.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 44        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 41        | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 1.4%    |
| Intel HD Graphics 620                                                                    | 39        | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 39        | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 1.29%   |
| Intel HD Graphics 630                                                                    | 33        | 1.18%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.11%   |
| Intel HD Graphics 530                                                                    | 28        | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26        | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 23        | 0.82%   |
| AMD Lucienne                                                                             | 22        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 21        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 21        | 0.75%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 21        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 19        | 0.68%   |
| Intel HD Graphics 500                                                                    | 17        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.54%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15        | 0.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 981       | 42.62%  |
| 1 x AMD        | 486       | 21.11%  |
| 1 x Nvidia     | 350       | 15.2%   |
| Intel + Nvidia | 278       | 12.08%  |
| Intel + AMD    | 67        | 2.91%   |
| 2 x AMD        | 45        | 1.95%   |
| AMD + Nvidia   | 40        | 1.74%   |
| Other          | 19        | 0.83%   |
| 1 x Matrox     | 13        | 0.56%   |
| 2 x Intel      | 8         | 0.35%   |
| 1 x ASPEED     | 5         | 0.22%   |
| 2 x Nvidia     | 3         | 0.13%   |
| 3 x Nvidia     | 2         | 0.09%   |
| 1 x VIA        | 2         | 0.09%   |
| 1 x SiS        | 2         | 0.09%   |
| AMD + Matrox   | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1895      | 81.61%  |
| Proprietary | 335       | 14.43%  |
| Unknown     | 92        | 3.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1384      | 58.52%  |
| 0.01-0.5   | 290       | 12.26%  |
| 1.01-2.0   | 254       | 10.74%  |
| 0.51-1.0   | 149       | 6.3%    |
| 3.01-4.0   | 128       | 5.41%   |
| 7.01-8.0   | 66        | 2.79%   |
| 5.01-6.0   | 42        | 1.78%   |
| 8.01-16.0  | 24        | 1.01%   |
| 2.01-3.0   | 21        | 0.89%   |
| 16.01-24.0 | 5         | 0.21%   |
| 4.01-5.0   | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 330       | 12.42%  |
| Samsung Electronics     | 297       | 11.17%  |
| LG Display              | 222       | 8.35%   |
| Chimei Innolux          | 189       | 7.11%   |
| BOE                     | 184       | 6.92%   |
| Dell                    | 166       | 6.25%   |
| CPT                     | 129       | 4.85%   |
| Goldstar                | 106       | 3.99%   |
| BenQ                    | 99        | 3.72%   |
| Acer                    | 93        | 3.5%    |
| Philips                 | 88        | 3.31%   |
| Hewlett-Packard         | 82        | 3.09%   |
| Eizo                    | 82        | 3.09%   |
| AOC                     | 67        | 2.52%   |
| Lenovo                  | 62        | 2.33%   |
| Ancor Communications    | 48        | 1.81%   |
| Sharp                   | 47        | 1.77%   |
| Iiyama                  | 35        | 1.32%   |
| Chi Mei Optoelectronics | 34        | 1.28%   |
| PANDA                   | 32        | 1.2%    |
| Sony                    | 19        | 0.71%   |
| LG Philips              | 18        | 0.68%   |
| InfoVision              | 16        | 0.6%    |
| Fujitsu Siemens         | 16        | 0.6%    |
| ASUSTek Computer        | 16        | 0.6%    |
| CSO                     | 15        | 0.56%   |
| Panasonic               | 13        | 0.49%   |
| NEC Computers           | 13        | 0.49%   |
| Apple                   | 10        | 0.38%   |
| ViewSonic               | 9         | 0.34%   |
| MSI                     | 9         | 0.34%   |
| Vestel Elektronik       | 8         | 0.3%    |
| Unknown                 | 8         | 0.3%    |
| Quanta Display          | 6         | 0.23%   |
| LG Electronics          | 6         | 0.23%   |
| HannStar                | 6         | 0.23%   |
| Valve                   | 5         | 0.19%   |
| Toshiba                 | 4         | 0.15%   |
| Lenovo Group Limited    | 4         | 0.15%   |
| Hitachi                 | 4         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 127       | 4.59%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 57        | 2.06%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 14        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.51%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 14        | 0.51%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 13        | 0.47%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.43%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 12        | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.33%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 8         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.29%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 8         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 7         | 0.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 7         | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 7         | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 7         | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.25%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 7         | 0.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 7         | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 7         | 0.25%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                        | 7         | 0.25%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.25%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 6         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.22%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 6         | 0.22%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.22%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 6         | 0.22%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 5         | 0.18%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 5         | 0.18%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.18%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 5         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1119      | 44.71%  |
| 1366x768 (WXGA)    | 299       | 11.95%  |
| 1600x900 (HD+)     | 208       | 8.31%   |
| 3840x2160 (4K)     | 183       | 7.31%   |
| 2560x1440 (QHD)    | 128       | 5.11%   |
| 1920x1200 (WUXGA)  | 93        | 3.72%   |
| 1280x1024 (SXGA)   | 86        | 3.44%   |
| 1680x1050 (WSXGA+) | 82        | 3.28%   |
| 1280x800 (WXGA)    | 67        | 2.68%   |
| 1440x900 (WXGA+)   | 38        | 1.52%   |
| 2560x1600          | 23        | 0.92%   |
| Unknown            | 16        | 0.64%   |
| 3440x1440          | 15        | 0.6%    |
| 2560x1080          | 13        | 0.52%   |
| 1024x768 (XGA)     | 11        | 0.44%   |
| 3840x1080          | 9         | 0.36%   |
| 1360x768           | 9         | 0.36%   |
| 1024x600           | 9         | 0.36%   |
| 2880x1800          | 8         | 0.32%   |
| 1600x1200          | 8         | 0.32%   |
| 1920x540           | 6         | 0.24%   |
| 1280x720 (HD)      | 6         | 0.24%   |
| 800x1280           | 5         | 0.2%    |
| 2288x1287          | 5         | 0.2%    |
| 2160x1350          | 5         | 0.2%    |
| 3840x2400          | 4         | 0.16%   |
| 2160x1440          | 4         | 0.16%   |
| 1400x1050          | 4         | 0.16%   |
| 3456x2160          | 3         | 0.12%   |
| 3000x2000          | 3         | 0.12%   |
| 2736x1824          | 3         | 0.12%   |
| 6400x2160          | 2         | 0.08%   |
| 3840x1600          | 2         | 0.08%   |
| 3840x1200          | 2         | 0.08%   |
| 3200x1800 (QHD+)   | 2         | 0.08%   |
| 2880x1620          | 2         | 0.08%   |
| 1280x768           | 2         | 0.08%   |
| 9600x2160          | 1         | 0.04%   |
| 8320x2160          | 1         | 0.04%   |
| 7680x2160          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 600       | 22.46%  |
| 13      | 343       | 12.84%  |
| 24      | 269       | 10.07%  |
| 14      | 215       | 8.05%   |
| 27      | 192       | 7.19%   |
| 23      | 147       | 5.5%    |
| 17      | 126       | 4.72%   |
| 21      | 125       | 4.68%   |
| 31      | 104       | 3.89%   |
| 19      | 78        | 2.92%   |
| Unknown | 77        | 2.88%   |
| 22      | 52        | 1.95%   |
| 12      | 41        | 1.53%   |
| 11      | 37        | 1.38%   |
| 20      | 35        | 1.31%   |
| 16      | 26        | 0.97%   |
| 34      | 23        | 0.86%   |
| 18      | 23        | 0.86%   |
| 84      | 21        | 0.79%   |
| 33      | 14        | 0.52%   |
| 32      | 11        | 0.41%   |
| 26      | 11        | 0.41%   |
| 25      | 11        | 0.41%   |
| 10      | 11        | 0.41%   |
| 40      | 10        | 0.37%   |
| 72      | 9         | 0.34%   |
| 54      | 9         | 0.34%   |
| 52      | 5         | 0.19%   |
| 7       | 5         | 0.19%   |
| 65      | 4         | 0.15%   |
| 47      | 4         | 0.15%   |
| 46      | 4         | 0.15%   |
| 43      | 4         | 0.15%   |
| 39      | 4         | 0.15%   |
| 28      | 4         | 0.15%   |
| 49      | 3         | 0.11%   |
| 29      | 3         | 0.11%   |
| 142     | 2         | 0.07%   |
| 48      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 961       | 36.92%  |
| 501-600        | 555       | 21.32%  |
| 201-300        | 319       | 12.26%  |
| 401-500        | 249       | 9.57%   |
| 351-400        | 175       | 6.72%   |
| 601-700        | 125       | 4.8%    |
| Unknown        | 77        | 2.96%   |
| 701-800        | 47        | 1.81%   |
| 1001-1500      | 36        | 1.38%   |
| 1501-2000      | 30        | 1.15%   |
| 801-900        | 18        | 0.69%   |
| 1-100          | 5         | 0.19%   |
| 901-1000       | 3         | 0.12%   |
| More than 2000 | 2         | 0.08%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1723      | 74.46%  |
| 16/10   | 348       | 15.04%  |
| 5/4     | 92        | 3.98%   |
| Unknown | 64        | 2.77%   |
| 4/3     | 27        | 1.17%   |
| 21/9    | 25        | 1.08%   |
| 3/2     | 21        | 0.91%   |
| 0.67    | 5         | 0.22%   |
| 32/9    | 4         | 0.17%   |
| 3.20    | 2         | 0.09%   |
| 1.00    | 2         | 0.09%   |
| 3.73    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 594       | 22.44%  |
| 201-250        | 456       | 17.23%  |
| 81-90          | 336       | 12.69%  |
| 71-80          | 224       | 8.46%   |
| 301-350        | 203       | 7.67%   |
| 351-500        | 156       | 5.89%   |
| 151-200        | 141       | 5.33%   |
| 251-300        | 105       | 3.97%   |
| 121-130        | 79        | 2.98%   |
| Unknown        | 77        | 2.91%   |
| More than 1000 | 54        | 2.04%   |
| 141-150        | 48        | 1.81%   |
| 51-60          | 37        | 1.4%    |
| 61-70          | 36        | 1.36%   |
| 501-1000       | 34        | 1.28%   |
| 111-120        | 25        | 0.94%   |
| 131-140        | 16        | 0.6%    |
| 41-50          | 12        | 0.45%   |
| 91-100         | 9         | 0.34%   |
| 1-40           | 5         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 847       | 33.89%  |
| 51-100        | 836       | 33.45%  |
| 101-120       | 491       | 19.65%  |
| 161-240       | 168       | 6.72%   |
| Unknown       | 77        | 3.08%   |
| 1-50          | 41        | 1.64%   |
| More than 240 | 39        | 1.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1728      | 73.13%  |
| 2     | 464       | 19.64%  |
| 0     | 103       | 4.36%   |
| 3     | 65        | 2.75%   |
| 4     | 3         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1123      | 32.64%  |
| Intel                                  | 1081      | 31.42%  |
| Qualcomm Atheros                       | 466       | 13.54%  |
| Broadcom                               | 149       | 4.33%   |
| Samsung Electronics                    | 133       | 3.87%   |
| MediaTek                               | 60        | 1.74%   |
| Broadcom Limited                       | 57        | 1.66%   |
| Marvell Technology Group               | 41        | 1.19%   |
| TP-Link                                | 32        | 0.93%   |
| Lenovo                                 | 28        | 0.81%   |
| Ralink Technology                      | 23        | 0.67%   |
| Qualcomm Atheros Communications        | 21        | 0.61%   |
| Nvidia                                 | 21        | 0.61%   |
| Ralink                                 | 20        | 0.58%   |
| ASIX Electronics                       | 19        | 0.55%   |
| Dell                                   | 17        | 0.49%   |
| Sierra Wireless                        | 15        | 0.44%   |
| DisplayLink                            | 14        | 0.41%   |
| Qualcomm                               | 8         | 0.23%   |
| ASUSTek Computer                       | 8         | 0.23%   |
| Xiaomi                                 | 6         | 0.17%   |
| VIA Technologies                       | 6         | 0.17%   |
| Microsoft                              | 6         | 0.17%   |
| D-Link                                 | 6         | 0.17%   |
| QLogic                                 | 5         | 0.15%   |
| Ericsson Business Mobile Networks      | 5         | 0.15%   |
| Attansic Technology                    | 5         | 0.15%   |
| Hewlett-Packard                        | 4         | 0.12%   |
| ZyDAS                                  | 3         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.09%   |
| Mellanox Technologies                  | 3         | 0.09%   |
| Huawei Technologies                    | 3         | 0.09%   |
| Fibocom                                | 3         | 0.09%   |
| Edimax Technology                      | 3         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| IBM                                    | 2         | 0.06%   |
| Google                                 | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 774       | 19.27%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 157       | 3.91%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 129       | 3.21%   |
| Intel Wi-Fi 6 AX200                                                    | 115       | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 110       | 2.74%   |
| Intel Wireless 8265 / 8275                                             | 82        | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 80        | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 78        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                      | 54        | 1.34%   |
| Intel Wireless 7260                                                    | 50        | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 49        | 1.22%   |
| Intel Wi-Fi 6 AX201                                                    | 47        | 1.17%   |
| Intel Wireless 8260                                                    | 42        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 41        | 1.02%   |
| Intel Wireless 7265                                                    | 41        | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 40        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 40        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 40        | 1%      |
| Intel Ethernet Connection I217-LM                                      | 38        | 0.95%   |
| Intel I211 Gigabit Network Connection                                  | 37        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 36        | 0.9%    |
| Intel Wireless 3165                                                    | 34        | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 34        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 33        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 33        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 32        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 31        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 31        | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 27        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 23        | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                   | 23        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 23        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 21        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 0.52%   |
| Intel Ethernet Controller I225-V                                       | 21        | 0.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20        | 0.5%    |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                        | 18        | 0.45%   |
| Intel WiFi Link 5100                                                   | 18        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 859       | 47.94%  |
| Qualcomm Atheros                  | 373       | 20.81%  |
| Realtek Semiconductor             | 223       | 12.44%  |
| Broadcom                          | 88        | 4.91%   |
| MediaTek                          | 56        | 3.13%   |
| TP-Link                           | 30        | 1.67%   |
| Broadcom Limited                  | 28        | 1.56%   |
| Ralink Technology                 | 23        | 1.28%   |
| Qualcomm Atheros Communications   | 21        | 1.17%   |
| Ralink                            | 20        | 1.12%   |
| Sierra Wireless                   | 15        | 0.84%   |
| Dell                              | 11        | 0.61%   |
| ASUSTek Computer                  | 7         | 0.39%   |
| Qualcomm                          | 6         | 0.33%   |
| Microsoft                         | 6         | 0.33%   |
| D-Link                            | 5         | 0.28%   |
| ZyDAS                             | 3         | 0.17%   |
| Fibocom                           | 3         | 0.17%   |
| Edimax Technology                 | 3         | 0.17%   |
| Marvell Technology Group          | 2         | 0.11%   |
| Hewlett-Packard                   | 2         | 0.11%   |
| ZyXEL Communications              | 1         | 0.06%   |
| Texas Instruments                 | 1         | 0.06%   |
| NetGear                           | 1         | 0.06%   |
| Mercucys                          | 1         | 0.06%   |
| Intersil                          | 1         | 0.06%   |
| Fujitsu Siemens Computers         | 1         | 0.06%   |
| Ericsson Business Mobile Networks | 1         | 0.06%   |
| D-Link System                     | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 157       | 8.74%   |
| Intel Wi-Fi 6 AX200                                            | 115       | 6.4%    |
| Intel Wireless 8265 / 8275                                     | 82        | 4.57%   |
| Intel Wireless 7260                                            | 50        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 49        | 2.73%   |
| Intel Wi-Fi 6 AX201                                            | 47        | 2.62%   |
| Intel Wireless 8260                                            | 42        | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 2.28%   |
| Intel Wireless 7265                                            | 41        | 2.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 40        | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 40        | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 40        | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 36        | 2%      |
| Intel Wireless 3165                                            | 34        | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 34        | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 33        | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 32        | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 31        | 1.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31        | 1.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 27        | 1.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 23        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 23        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                | 18        | 1%      |
| Intel WiFi Link 5100                                           | 18        | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 18        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 1%      |
| Intel Wireless 3160                                            | 17        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 17        | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 17        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 0.95%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 16        | 0.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 15        | 0.84%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 15        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 13        | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 13        | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 13        | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12        | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 11        | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1021      | 48.09%  |
| Intel                                  | 551       | 25.95%  |
| Samsung Electronics                    | 133       | 6.26%   |
| Qualcomm Atheros                       | 133       | 6.26%   |
| Broadcom                               | 71        | 3.34%   |
| Marvell Technology Group               | 40        | 1.88%   |
| Broadcom Limited                       | 29        | 1.37%   |
| Lenovo                                 | 28        | 1.32%   |
| Nvidia                                 | 21        | 0.99%   |
| ASIX Electronics                       | 19        | 0.89%   |
| DisplayLink                            | 14        | 0.66%   |
| Xiaomi                                 | 6         | 0.28%   |
| VIA Technologies                       | 5         | 0.24%   |
| QLogic                                 | 5         | 0.24%   |
| Attansic Technology                    | 5         | 0.24%   |
| MediaTek                               | 4         | 0.19%   |
| Mellanox Technologies                  | 3         | 0.14%   |
| TP-Link                                | 2         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.09%   |
| Qualcomm                               | 2         | 0.09%   |
| Microchip Technology                   | 2         | 0.09%   |
| IBM                                    | 2         | 0.09%   |
| Huawei Technologies                    | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Aquantia                               | 2         | 0.09%   |
| American Megatrends                    | 2         | 0.09%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |
| MosChip Semiconductor                  | 1         | 0.05%   |
| JMicron Technology                     | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |
| Foxconn / Hon Hai                      | 1         | 0.05%   |
| Emulex                                 | 1         | 0.05%   |
| D-Link System                          | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| Chelsio Communications                 | 1         | 0.05%   |
| ASUSTek Computer                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 774       | 35.37%  |
| Samsung Galaxy series, misc. (tethering mode)                          | 129       | 5.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 110       | 5.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 80        | 3.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 78        | 3.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 54        | 2.47%   |
| Intel Ethernet Connection I217-LM                                      | 38        | 1.74%   |
| Intel I211 Gigabit Network Connection                                  | 37        | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                                  | 33        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                                   | 23        | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 21        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 0.96%   |
| Intel Ethernet Controller I225-V                                       | 21        | 0.96%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.87%   |
| Intel 82567LM Gigabit Network Connection                               | 18        | 0.82%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                   | 16        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 16        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                  | 15        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 14        | 0.64%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 13        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 13        | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                   | 13        | 0.59%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 13        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                  | 12        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                | 11        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 11        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 10        | 0.46%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 10        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 9         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                                  | 9         | 0.41%   |
| Intel Ethernet Connection (2) I218-V                                   | 9         | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 9         | 0.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 9         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 8         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1982      | 53.18%  |
| WiFi     | 1714      | 45.99%  |
| Modem    | 26        | 0.7%    |
| Unknown  | 5         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1231      | 51.66%  |
| Ethernet | 1152      | 48.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1170      | 50.87%  |
| 1     | 1020      | 44.35%  |
| 0     | 55        | 2.39%   |
| 3     | 37        | 1.61%   |
| 4     | 8         | 0.35%   |
| 8     | 4         | 0.17%   |
| 5     | 3         | 0.13%   |
| 10    | 1         | 0.04%   |
| 9     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2010      | 86.38%  |
| Yes  | 317       | 13.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 655       | 48.16%  |
| Realtek Semiconductor           | 135       | 9.93%   |
| IMC Networks                    | 85        | 6.25%   |
| Qualcomm Atheros Communications | 84        | 6.18%   |
| Cambridge Silicon Radio         | 66        | 4.85%   |
| Broadcom                        | 64        | 4.71%   |
| Foxconn / Hon Hai               | 62        | 4.56%   |
| Lite-On Technology              | 48        | 3.53%   |
| ASUSTek Computer                | 43        | 3.16%   |
| Hewlett-Packard                 | 29        | 2.13%   |
| Dell                            | 18        | 1.32%   |
| MediaTek                        | 11        | 0.81%   |
| Ralink                          | 10        | 0.74%   |
| Apple                           | 9         | 0.66%   |
| Integrated System Solution      | 5         | 0.37%   |
| Alps Electric                   | 5         | 0.37%   |
| TP-Link                         | 4         | 0.29%   |
| Toshiba                         | 4         | 0.29%   |
| Realtek                         | 4         | 0.29%   |
| Foxconn International           | 3         | 0.22%   |
| USI                             | 2         | 0.15%   |
| Ralink Technology               | 2         | 0.15%   |
| Mobile Action Technology        | 2         | 0.15%   |
| Micro Star International        | 2         | 0.15%   |
| Marvell Semiconductor           | 2         | 0.15%   |
| Creative Technology             | 2         | 0.15%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 252       | 18.53%  |
| Intel AX201 Bluetooth                                                               | 115       | 8.46%   |
| Intel AX200 Bluetooth                                                               | 112       | 8.24%   |
| Realtek Bluetooth Radio                                                             | 96        | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 85        | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 66        | 4.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 34        | 2.5%    |
| Intel Bluetooth Device                                                              | 34        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 29        | 2.13%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 24        | 1.76%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 24        | 1.76%   |
| IMC Networks Bluetooth Radio                                                        | 22        | 1.62%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 19        | 1.4%    |
| IMC Networks Bluetooth Device                                                       | 19        | 1.4%    |
| IMC Networks Wireless_Device                                                        | 18        | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 17        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 16        | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 1.1%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 15        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 14        | 1.03%   |
| Intel AX210 Bluetooth                                                               | 13        | 0.96%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 13        | 0.96%   |
| Broadcom BCM2045 Bluetooth                                                          | 12        | 0.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 12        | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 0.81%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 0.74%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 0.74%   |
| ASUS ASUS USB-BT500                                                                 | 10        | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 0.66%   |
| MediaTek Wireless_Device                                                            | 8         | 0.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 8         | 0.59%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 0.59%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 8         | 0.59%   |
| Lite-On Bluetooth Device                                                            | 7         | 0.51%   |
| Qualcomm Atheros Bluetooth                                                          | 6         | 0.44%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 6         | 0.44%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1605      | 52.43%  |
| AMD                                  | 677       | 22.12%  |
| Nvidia                               | 451       | 14.73%  |
| C-Media Electronics                  | 55        | 1.8%    |
| Lenovo                               | 37        | 1.21%   |
| Realtek Semiconductor                | 26        | 0.85%   |
| GN Netcom                            | 20        | 0.65%   |
| Logitech                             | 17        | 0.56%   |
| Creative Labs                        | 16        | 0.52%   |
| Creative Technology                  | 14        | 0.46%   |
| VIA Technologies                     | 13        | 0.42%   |
| JMTek                                | 12        | 0.39%   |
| Kingston Technology                  | 10        | 0.33%   |
| Hewlett-Packard                      | 10        | 0.33%   |
| Razer USA                            | 6         | 0.2%    |
| Plantronics                          | 6         | 0.2%    |
| GYROCOM C&C                          | 5         | 0.16%   |
| Focusrite-Novation                   | 5         | 0.16%   |
| Dell                                 | 5         | 0.16%   |
| Trust                                | 4         | 0.13%   |
| Sennheiser Communications            | 4         | 0.13%   |
| BEHRINGER International              | 4         | 0.13%   |
| ASUSTek Computer                     | 4         | 0.13%   |
| Texas Instruments                    | 3         | 0.1%    |
| Silicon Integrated Systems [SiS]     | 3         | 0.1%    |
| Micro Star International             | 3         | 0.1%    |
| M-Audio                              | 3         | 0.1%    |
| Yamaha                               | 2         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| SteelSeries ApS                      | 2         | 0.07%   |
| Samson Technologies                  | 2         | 0.07%   |
| RODE Microphones                     | 2         | 0.07%   |
| Harman                               | 2         | 0.07%   |
| DigiTech                             | 2         | 0.07%   |
| Conexant Systems                     | 2         | 0.07%   |
| Cambridge Silicon Radio              | 2         | 0.07%   |
| ASRock                               | 2         | 0.07%   |
| Yealink Network Technology           | 1         | 0.03%   |
| Toshiba                              | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 246       | 6.73%   |
| AMD Family 17h/19h HD Audio Controller                                     | 243       | 6.65%   |
| Intel Sunrise Point-LP HD Audio                                            | 159       | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 146       | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 116       | 3.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 95        | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 87        | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 84        | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 80        | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 78        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 75        | 2.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 74        | 2.03%   |
| AMD FCH Azalia Controller                                                  | 63        | 1.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 61        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 54        | 1.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 49        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 49        | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 48        | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 45        | 1.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 44        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 42        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 41        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 41        | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 40        | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 39        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 37        | 1.01%   |
| Intel Broadwell-U Audio Controller                                         | 36        | 0.99%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 36        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 35        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 33        | 0.9%    |
| Intel 200 Series PCH HD Audio                                              | 31        | 0.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 31        | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 28        | 0.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 27        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 27        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 26        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 301       | 19.95%  |
| Kingston                     | 274       | 18.16%  |
| SK hynix                     | 238       | 15.77%  |
| Micron Technology            | 158       | 10.47%  |
| Elpida                       | 147       | 9.74%   |
| Unknown                      | 134       | 8.88%   |
| Crucial                      | 57        | 3.78%   |
| Corsair                      | 42        | 2.78%   |
| Ramaxel Technology           | 32        | 2.12%   |
| Patriot                      | 28        | 1.86%   |
| A-DATA Technology            | 23        | 1.52%   |
| Unknown (ABCD)               | 18        | 1.19%   |
| G.Skill                      | 14        | 0.93%   |
| Nanya Technology             | 11        | 0.73%   |
| Transcend                    | 6         | 0.4%    |
| Unknown                      | 3         | 0.2%    |
| GOODRAM                      | 2         | 0.13%   |
| Unknown (AB)                 | 1         | 0.07%   |
| Toshiba                      | 1         | 0.07%   |
| Team                         | 1         | 0.07%   |
| TakeMS                       | 1         | 0.07%   |
| Silicon Power                | 1         | 0.07%   |
| ProMos/Mosel Vitelic         | 1         | 0.07%   |
| PDPSystems                   | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Patriot Memory               | 1         | 0.07%   |
| OnBoard                      | 1         | 0.07%   |
| Nayna                        | 1         | 0.07%   |
| Kingmax                      | 1         | 0.07%   |
| Kimtigo                      | 1         | 0.07%   |
| H                            | 1         | 0.07%   |
| GSkill                       | 1         | 0.07%   |
| Golden Empire                | 1         | 0.07%   |
| fef5                         | 1         | 0.07%   |
| ASint Technology             | 1         | 0.07%   |
| Apacer                       | 1         | 0.07%   |
| AMD                          | 1         | 0.07%   |
| 48spaces                     | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                          | 126       | 7.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 18        | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 15        | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 14        | 0.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 12        | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 11        | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s                | 11        | 0.68%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 10        | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 9         | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 9         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 8         | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.5%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 0.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 8         | 0.5%    |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 7         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.43%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s                 | 7         | 0.43%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s               | 7         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 6         | 0.37%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 6         | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.37%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 6         | 0.37%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                 | 6         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 5         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 5         | 0.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.31%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 0.31%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 0.31%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                         | 5         | 0.31%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 5         | 0.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 0.31%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.31%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 588       | 44.55%  |
| DDR3    | 467       | 35.38%  |
| LPDDR4  | 64        | 4.85%   |
| DDR2    | 62        | 4.7%    |
| Unknown | 37        | 2.8%    |
| SDRAM   | 29        | 2.2%    |
| LPDDR3  | 25        | 1.89%   |
| DDR5    | 22        | 1.67%   |
| LPDDR5  | 16        | 1.21%   |
| DDR     | 8         | 0.61%   |
| DRAM    | 2         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 827       | 62.6%   |
| DIMM         | 385       | 29.14%  |
| Row Of Chips | 92        | 6.96%   |
| Chip         | 12        | 0.91%   |
| Unknown      | 3         | 0.23%   |
| RIMM         | 2         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 492       | 34.48%  |
| 4096  | 308       | 21.58%  |
| 2048  | 276       | 19.34%  |
| 16384 | 233       | 16.33%  |
| 32768 | 66        | 4.63%   |
| 1024  | 44        | 3.08%   |
| 512   | 4         | 0.28%   |
| 256   | 2         | 0.14%   |
| 6144  | 1         | 0.07%   |
| 3072  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 237       | 16.59%  |
| 1600    | 218       | 15.26%  |
| 1333    | 204       | 14.28%  |
| 2667    | 163       | 11.41%  |
| 2400    | 104       | 7.28%   |
| 2133    | 68        | 4.76%   |
| 800     | 39        | 2.73%   |
| 3600    | 38        | 2.66%   |
| 1334    | 37        | 2.59%   |
| 667     | 28        | 1.96%   |
| 4267    | 24        | 1.68%   |
| Unknown | 24        | 1.68%   |
| 1867    | 19        | 1.33%   |
| 3733    | 17        | 1.19%   |
| 6400    | 16        | 1.12%   |
| 1067    | 16        | 1.12%   |
| 3266    | 12        | 0.84%   |
| 2666    | 11        | 0.77%   |
| 4800    | 10        | 0.7%    |
| 3400    | 10        | 0.7%    |
| 3466    | 8         | 0.56%   |
| 2048    | 8         | 0.56%   |
| 1866    | 8         | 0.56%   |
| 4266    | 7         | 0.49%   |
| 3800    | 7         | 0.49%   |
| 3000    | 7         | 0.49%   |
| 1066    | 7         | 0.49%   |
| 5600    | 6         | 0.42%   |
| 4199    | 6         | 0.42%   |
| 533     | 6         | 0.42%   |
| 3933    | 5         | 0.35%   |
| 2933    | 5         | 0.35%   |
| 1800    | 5         | 0.35%   |
| 975     | 5         | 0.35%   |
| 8400    | 4         | 0.28%   |
| 2800    | 4         | 0.28%   |
| 400     | 4         | 0.28%   |
| 6000    | 3         | 0.21%   |
| 3533    | 3         | 0.21%   |
| 3334    | 3         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 11        | 25%     |
| Hewlett-Packard     | 10        | 22.73%  |
| Brother Industries  | 7         | 15.91%  |
| Samsung Electronics | 6         | 13.64%  |
| QinHeng Electronics | 3         | 6.82%   |
| Xerox               | 2         | 4.55%   |
| Seiko Epson         | 1         | 2.27%   |
| Prolific Technology | 1         | 2.27%   |
| Pantum              | 1         | 2.27%   |
| Minolta             | 1         | 2.27%   |
| ICS Advent          | 1         | 2.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| QinHeng CH340S                          | 3         | 6.67%   |
| HP DeskJet 2600 series                  | 3         | 6.67%   |
| Samsung M2070 Series                    | 2         | 4.44%   |
| HP LaserJet P2014                       | 2         | 4.44%   |
| Xerox Phaser 3260                       | 1         | 2.22%   |
| Xerox B215                              | 1         | 2.22%   |
| Seiko Epson L365 Series                 | 1         | 2.22%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.22%   |
| Samsung M267x 287x Series               | 1         | 2.22%   |
| Samsung M2020 Series                    | 1         | 2.22%   |
| Samsung C460 Series                     | 1         | 2.22%   |
| Prolific PL2305 Parallel Port           | 1         | 2.22%   |
| Pantum P2000                            | 1         | 2.22%   |
| Minolta PagePro 1300W                   | 1         | 2.22%   |
| ICS Advent Parallel Adapter             | 1         | 2.22%   |
| HP Officejet 4500 G510g-m               | 1         | 2.22%   |
| HP Neverstop Laser 100x                 | 1         | 2.22%   |
| HP LaserJet Professional P 1102w        | 1         | 2.22%   |
| HP LaserJet 1018                        | 1         | 2.22%   |
| HP Deskjet 3050 J610 series             | 1         | 2.22%   |
| Canon TS6300 series                     | 1         | 2.22%   |
| Canon PIXMA MX920 Series                | 1         | 2.22%   |
| Canon PIXMA MX720 Series                | 1         | 2.22%   |
| Canon PIXMA MP280                       | 1         | 2.22%   |
| Canon PIXMA MG5600 Series               | 1         | 2.22%   |
| Canon PIXMA MG3500 Series               | 1         | 2.22%   |
| Canon PIXMA MG2500 Series               | 1         | 2.22%   |
| Canon MF4100 series                     | 1         | 2.22%   |
| Canon LBP3010/LBP3018/LBP3050           | 1         | 2.22%   |
| Canon iP7200 series                     | 1         | 2.22%   |
| Canon G2020 series                      | 1         | 2.22%   |
| Canon CanoScan LiDE 300                 | 1         | 2.22%   |
| Brother MFC-J3930DW                     | 1         | 2.22%   |
| Brother HL-3040CN series                | 1         | 2.22%   |
| Brother HL-2030 Laser Printer           | 1         | 2.22%   |
| Brother HL-1430 Laser Printer           | 1         | 2.22%   |
| Brother DCP-L2510D series               | 1         | 2.22%   |
| Brother DCP-J105                        | 1         | 2.22%   |
| Brother DCP-1610W                       | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 72.73%  |
| Seiko Epson     | 1         | 9.09%   |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                | 2         | 18.18%  |
| Canon CanoScan LiDE 210               | 2         | 18.18%  |
| Seiko Epson GT-F700 [Perfection V350] | 1         | 9.09%   |
| Mustek Systems BearPaw 1200 CU Plus   | 1         | 9.09%   |
| HP ScanJet 2200c                      | 1         | 9.09%   |
| Canon CanoScan LiDE 90                | 1         | 9.09%   |
| Canon CanoScan LiDE 200               | 1         | 9.09%   |
| Canon CanoScan LiDE 120               | 1         | 9.09%   |
| Canon CanoScan LiDE 100               | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 320       | 24.32%  |
| Realtek Semiconductor                  | 124       | 9.42%   |
| IMC Networks                           | 117       | 8.89%   |
| Microdia                               | 104       | 7.9%    |
| Bison Electronics                      | 78        | 5.93%   |
| Sunplus Innovation Technology          | 77        | 5.85%   |
| Quanta                                 | 58        | 4.41%   |
| Cheng Uei Precision Industry (Foxlink) | 55        | 4.18%   |
| Lite-On Technology                     | 49        | 3.72%   |
| Acer                                   | 42        | 3.19%   |
| Syntek                                 | 37        | 2.81%   |
| Suyin                                  | 36        | 2.74%   |
| Logitech                               | 34        | 2.58%   |
| Apple                                  | 21        | 1.6%    |
| KYE Systems (Mouse Systems)            | 14        | 1.06%   |
| Luxvisions Innotech Limited            | 13        | 0.99%   |
| Samsung Electronics                    | 12        | 0.91%   |
| Ricoh                                  | 12        | 0.91%   |
| Lenovo                                 | 12        | 0.91%   |
| Alcor Micro                            | 12        | 0.91%   |
| Microsoft                              | 10        | 0.76%   |
| Z-Star Microelectronics                | 9         | 0.68%   |
| Creative Technology                    | 8         | 0.61%   |
| Sonix Technology                       | 6         | 0.46%   |
| Primax Electronics                     | 5         | 0.38%   |
| GEMBIRD                                | 5         | 0.38%   |
| USB Camera                             | 4         | 0.3%    |
| Hopewin Electronic Material            | 4         | 0.3%    |
| Silicon Motion                         | 3         | 0.23%   |
| Generalplus Technology                 | 3         | 0.23%   |
| MacroSilicon                           | 2         | 0.15%   |
| Intel                                  | 2         | 0.15%   |
| Hewlett-Packard                        | 2         | 0.15%   |
| Genesys Logic                          | 2         | 0.15%   |
| 8SSC21D67422V1SR3AV5KW1                | 2         | 0.15%   |
| YGTek                                  | 1         | 0.08%   |
| webcamvendor                           | 1         | 0.08%   |
| WaveRider Communications               | 1         | 0.08%   |
| Unknown                                | 1         | 0.08%   |
| SunplusIT                              | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 83        | 6.24%   |
| IMC Networks Integrated Camera                      | 51        | 3.83%   |
| Realtek Integrated_Webcam_HD                        | 48        | 3.61%   |
| Microdia Integrated_Webcam_HD                       | 42        | 3.16%   |
| Chicony HP HD Camera                                | 31        | 2.33%   |
| Chicony HD WebCam                                   | 31        | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 28        | 2.11%   |
| Bison Integrated Camera                             | 24        | 1.8%    |
| Lite-On HP HD Camera                                | 22        | 1.65%   |
| Syntek Integrated Camera                            | 21        | 1.58%   |
| Realtek USB Camera                                  | 19        | 1.43%   |
| Bison Lenovo EasyCamera                             | 18        | 1.35%   |
| Sunplus Integrated_Webcam_HD                        | 17        | 1.28%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 16        | 1.2%    |
| Chicony Integrated Camera (1280x720@30)             | 15        | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 13        | 0.98%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 12        | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)             | 12        | 0.9%    |
| Quanta HP HD Camera                                 | 12        | 0.9%    |
| Lite-On Integrated Camera                           | 12        | 0.9%    |
| Acer SunplusIT Integrated Camera                    | 12        | 0.9%    |
| Acer Integrated Camera                              | 12        | 0.9%    |
| Quanta HD User Facing                               | 11        | 0.83%   |
| Microdia Integrated Webcam                          | 11        | 0.83%   |
| Sunplus HD WebCam                                   | 10        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                       | 10        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 10        | 0.75%   |
| Syntek Lenovo EasyCamera                            | 9         | 0.68%   |
| Quanta HP Wide Vision HD Camera                     | 9         | 0.68%   |
| Chicony Lenovo EasyCamera                           | 9         | 0.68%   |
| Bison Lenovo Integrated Webcam                      | 9         | 0.68%   |
| Logitech Webcam C270                                | 8         | 0.6%    |
| Lenovo Integrated Webcam                            | 8         | 0.6%    |
| Chicony HP HD Webcam                                | 8         | 0.6%    |
| Chicony FJ Camera                                   | 8         | 0.6%    |
| Sunplus Laptop Integrated Webcam HD                 | 7         | 0.53%   |
| Sunplus Asus Webcam                                 | 7         | 0.53%   |
| Microdia USB 2.0 Camera                             | 7         | 0.53%   |
| Microdia Sonix USB 2.0 Camera                       | 7         | 0.53%   |
| Chicony EasyCamera                                  | 7         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 122       | 35.78%  |
| Validity Sensors                   | 110       | 32.26%  |
| Shenzhen Goodix Technology         | 38        | 11.14%  |
| AuthenTec                          | 29        | 8.5%    |
| Elan Microelectronics              | 15        | 4.4%    |
| Upek                               | 14        | 4.11%   |
| LighTuning Technology              | 7         | 2.05%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.59%   |
| Dell                               | 2         | 0.59%   |
| STMicroelectronics                 | 1         | 0.29%   |
| Microsoft                          | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 8.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 21        | 6.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 5.28%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 5.28%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 16        | 4.69%   |
| Synaptics Fingerprint reader [HP G6]                                       | 16        | 4.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 3.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.81%   |
| AuthenTec AES2810                                                          | 12        | 3.52%   |
| Validity Sensors VFS491                                                    | 11        | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 3.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.93%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 2.93%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.93%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 2.64%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.05%   |
| AuthenTec AES1600                                                          | 7         | 2.05%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.76%   |
| Synaptics UWP WBDI                                                         | 6         | 1.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.47%   |
| Synaptics WBDI                                                             | 5         | 1.47%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.47%   |
| Synaptics  WBDI                                                            | 4         | 1.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.88%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.59%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.59%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.59%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.29%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.29%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 77        | 51.33%  |
| Alcor Micro               | 47        | 31.33%  |
| O2 Micro                  | 9         | 6%      |
| Lenovo                    | 5         | 3.33%   |
| Upek                      | 2         | 1.33%   |
| SCM Microsystems          | 2         | 1.33%   |
| Realtek Semiconductor     | 2         | 1.33%   |
| Aladdin Knowledge Systems | 2         | 1.33%   |
| Purism, SPC               | 1         | 0.67%   |
| OmniKey                   | 1         | 0.67%   |
| Gemalto (was Gemplus)     | 1         | 0.67%   |
| Fujitsu Siemens Computers | 1         | 0.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 47        | 31.33%  |
| Broadcom 58200                                                               | 25        | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 13.33%  |
| Broadcom 5880                                                                | 18        | 12%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 9.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.33%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.33%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.33%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.33%   |
| Purism, SPC Librem Key                                                       | 1         | 0.67%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.67%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.67%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1564      | 67.18%  |
| 1     | 584       | 25.09%  |
| 2     | 144       | 6.19%   |
| 3     | 27        | 1.16%   |
| 4     | 5         | 0.21%   |
| 5     | 4         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 333       | 35.02%  |
| Graphics card            | 199       | 20.93%  |
| Chipcard                 | 128       | 13.46%  |
| Net/wireless             | 67        | 7.05%   |
| Multimedia controller    | 53        | 5.57%   |
| Camera                   | 27        | 2.84%   |
| Storage                  | 24        | 2.52%   |
| Communication controller | 24        | 2.52%   |
| Bluetooth                | 24        | 2.52%   |
| Unassigned class         | 15        | 1.58%   |
| Card reader              | 13        | 1.37%   |
| Net/ethernet             | 10        | 1.05%   |
| Sound                    | 9         | 0.95%   |
| Flash memory             | 7         | 0.74%   |
| Modem                    | 6         | 0.63%   |
| Network                  | 4         | 0.42%   |
| Storage/raid             | 2         | 0.21%   |
| Storage/ata              | 2         | 0.21%   |
| Dvb card                 | 2         | 0.21%   |
| Tv card                  | 1         | 0.11%   |
| Storage/ide              | 1         | 0.11%   |

