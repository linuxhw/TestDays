Ubuntu 23.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

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

Total: 413

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A78L-M LE                 | [a68db843ea](https://linux-hardware.org/?probe=a68db843ea) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [7fb2d45505](https://linux-hardware.org/?probe=7fb2d45505) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Dell          | 0HD5W2 A01                  | [be4514c366](https://linux-hardware.org/?probe=be4514c366) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [f278787ab5](https://linux-hardware.org/?probe=f278787ab5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [76078461ae](https://linux-hardware.org/?probe=76078461ae) | Aug 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ab2473ff49](https://linux-hardware.org/?probe=ab2473ff49) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7f2903e1a4](https://linux-hardware.org/?probe=7f2903e1a4) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f7fe8fc7f3](https://linux-hardware.org/?probe=f7fe8fc7f3) | Aug 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [ab3503021a](https://linux-hardware.org/?probe=ab3503021a) | Aug 10, 2023 |
| MSI           | Z590-A PRO                  | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [783906b878](https://linux-hardware.org/?probe=783906b878) | Aug 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1d8737323b](https://linux-hardware.org/?probe=1d8737323b) | Aug 06, 2023 |
| ASUSTek       | P8H61-M LX3                 | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| MSI           | 2AE0                        | [9d3b59de32](https://linux-hardware.org/?probe=9d3b59de32) | Aug 06, 2023 |
| MSI           | H81M-P33                    | [ebed30097f](https://linux-hardware.org/?probe=ebed30097f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [9c9e999e7f](https://linux-hardware.org/?probe=9c9e999e7f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [54f0bde318](https://linux-hardware.org/?probe=54f0bde318) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| GMKtec        | NucBox K4                   | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fed2da6500](https://linux-hardware.org/?probe=fed2da6500) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2531b9d0db](https://linux-hardware.org/?probe=2531b9d0db) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [67cea35f6d](https://linux-hardware.org/?probe=67cea35f6d) | Aug 04, 2023 |
| ASUSTek       | M3A78-T                     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| MSI           | A320M-A PRO MAX             | [881ac0a0e0](https://linux-hardware.org/?probe=881ac0a0e0) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | [c3beec95b8](https://linux-hardware.org/?probe=c3beec95b8) | Aug 02, 2023 |
| HP            | 8653 A                      | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| ASRock        | B365M-HDV                   | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [66000207b0](https://linux-hardware.org/?probe=66000207b0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [df0702afb0](https://linux-hardware.org/?probe=df0702afb0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [0ac623dd70](https://linux-hardware.org/?probe=0ac623dd70) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| ASRock        | FM2A75 Pro4                 | [831157a9ac](https://linux-hardware.org/?probe=831157a9ac) | Jul 31, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [45405639f5](https://linux-hardware.org/?probe=45405639f5) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b70677782d](https://linux-hardware.org/?probe=b70677782d) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | [ae8a9f3aaf](https://linux-hardware.org/?probe=ae8a9f3aaf) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [f36740f05f](https://linux-hardware.org/?probe=f36740f05f) | Jul 29, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| Gigabyte      | Z490 UD                     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | [87bb7b0b79](https://linux-hardware.org/?probe=87bb7b0b79) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| HP            | 3646h                       | [fbc7ac7c08](https://linux-hardware.org/?probe=fbc7ac7c08) | Jul 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2fe1d4509a](https://linux-hardware.org/?probe=2fe1d4509a) | Jul 26, 2023 |
| ASRock        | B560M Pro4                  | [d96478ff29](https://linux-hardware.org/?probe=d96478ff29) | Jul 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | [32707549f9](https://linux-hardware.org/?probe=32707549f9) | Jul 25, 2023 |
| Unknown       | 1.2                         | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| Intel         | Unknown                     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| Intel         | B75                         | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3511a9786a](https://linux-hardware.org/?probe=3511a9786a) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Dell          | 08NPPY A00                  | [63fb3abc69](https://linux-hardware.org/?probe=63fb3abc69) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS M                | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [e35d64a41b](https://linux-hardware.org/?probe=e35d64a41b) | Jul 21, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a07f95cdcc](https://linux-hardware.org/?probe=a07f95cdcc) | Jul 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Gigabyte      | A520M DS3H                  | [3bd7501f03](https://linux-hardware.org/?probe=3bd7501f03) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [f99a99e95e](https://linux-hardware.org/?probe=f99a99e95e) | Jul 19, 2023 |
| Unknown       | G41 Series                  | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [e62367803c](https://linux-hardware.org/?probe=e62367803c) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [41e06d3720](https://linux-hardware.org/?probe=41e06d3720) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| Packard Be... | IMEDIA S2885                | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60280e0708](https://linux-hardware.org/?probe=60280e0708) | Jul 17, 2023 |
| MSI           | FM2-A85XA-G65               | [8e6741f497](https://linux-hardware.org/?probe=8e6741f497) | Jul 17, 2023 |
| ASRock        | FM2A68M-HD+                 | [5abf5fb1c3](https://linux-hardware.org/?probe=5abf5fb1c3) | Jul 16, 2023 |
| Gigabyte      | H61M-DS2                    | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| MSI           | G41M4                       | [b7bda60261](https://linux-hardware.org/?probe=b7bda60261) | Jul 16, 2023 |
| MSI           | G41M4                       | [a3e5e23a49](https://linux-hardware.org/?probe=a3e5e23a49) | Jul 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [79af0f54f4](https://linux-hardware.org/?probe=79af0f54f4) | Jul 15, 2023 |
| ASUSTek       | PRIME B650M-A II            | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| MSI           | FM2-A85XA-G65               | [00b4b2f7b0](https://linux-hardware.org/?probe=00b4b2f7b0) | Jul 13, 2023 |
| MSI           | Z87-G43                     | [86d9a28ae8](https://linux-hardware.org/?probe=86d9a28ae8) | Jul 13, 2023 |
| HP            | 83EE                        | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| ASRock        | X79 Extreme9                | [bfd488feb9](https://linux-hardware.org/?probe=bfd488feb9) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | Z77 Extreme3                | [1312271ad3](https://linux-hardware.org/?probe=1312271ad3) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| Gigabyte      | MZAPLBP-00                  | [8f57c74864](https://linux-hardware.org/?probe=8f57c74864) | Jul 09, 2023 |
| Dell          | 0GXM1W A00                  | [b320d70c27](https://linux-hardware.org/?probe=b320d70c27) | Jul 09, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [d7f7dc2ef3](https://linux-hardware.org/?probe=d7f7dc2ef3) | Jul 08, 2023 |
| Lenovo        | IdeaCentre K330A            | [8d98ff8f86](https://linux-hardware.org/?probe=8d98ff8f86) | Jul 08, 2023 |
| Dell          | 0GXM1W A00                  | [91cab30323](https://linux-hardware.org/?probe=91cab30323) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | [89a1894d2a](https://linux-hardware.org/?probe=89a1894d2a) | Jul 08, 2023 |
| MSI           | Z97S SLI Krait Edition      | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7e3f6aabfb](https://linux-hardware.org/?probe=7e3f6aabfb) | Jul 06, 2023 |
| Apple         | Mac-F221BEC8                | [5e66adbc36](https://linux-hardware.org/?probe=5e66adbc36) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| MSI           | 760GM-E51                   | [757eefb29d](https://linux-hardware.org/?probe=757eefb29d) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | [12e2330b5a](https://linux-hardware.org/?probe=12e2330b5a) | Jul 05, 2023 |
| ASRock        | A320M-HDV R3.0              | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| ASUSTek       | PRIME A520M-K               | [9b1631574e](https://linux-hardware.org/?probe=9b1631574e) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d17e5d7807](https://linux-hardware.org/?probe=d17e5d7807) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [29897719d5](https://linux-hardware.org/?probe=29897719d5) | Jul 03, 2023 |
| ASRock        | P67 Performance             | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| Intel         | H55                         | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Biostar       | A10N-8800E                  | [261bb38239](https://linux-hardware.org/?probe=261bb38239) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fa055ceb7c](https://linux-hardware.org/?probe=fa055ceb7c) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Lenovo        | 0B98401 WIN                 | [35871c9acc](https://linux-hardware.org/?probe=35871c9acc) | Jun 30, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| ASUSTek       | PRIME Z590-P                | [6147d58cdf](https://linux-hardware.org/?probe=6147d58cdf) | Jun 29, 2023 |
| ASUSTek       | H170-PRO                    | [506c909e37](https://linux-hardware.org/?probe=506c909e37) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| ASRock        | A320M-DVS R4.0              | [742d015edb](https://linux-hardware.org/?probe=742d015edb) | Jun 26, 2023 |
| ASRock        | A320M-DVS R4.0              | [6c659f8e1f](https://linux-hardware.org/?probe=6c659f8e1f) | Jun 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [544c014552](https://linux-hardware.org/?probe=544c014552) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| Dell          | 0KJCC5 A00                  | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| Intel         | H61                         | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASRock        | X570 Extreme4               | [0ab63facb3](https://linux-hardware.org/?probe=0ab63facb3) | Jun 25, 2023 |
| HP            | 805D                        | [d55246de23](https://linux-hardware.org/?probe=d55246de23) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| System76      | Desktop leox5               | [210eb3f1e8](https://linux-hardware.org/?probe=210eb3f1e8) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [45575cf0cc](https://linux-hardware.org/?probe=45575cf0cc) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [77d2d05995](https://linux-hardware.org/?probe=77d2d05995) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| MSI           | H270-A PRO                  | [169bbe5f04](https://linux-hardware.org/?probe=169bbe5f04) | Jun 23, 2023 |
| Gigabyte      | H61M-DS2                    | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| MSI           | 760GM -E51                  | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| Gigabyte      | H77-D3H                     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| Dell          | 0YXG0N A00                  | [546af4a5d6](https://linux-hardware.org/?probe=546af4a5d6) | Jun 22, 2023 |
| HP            | 339A                        | [420903b9cc](https://linux-hardware.org/?probe=420903b9cc) | Jun 21, 2023 |
| Shenzhen M... | F7BFC                       | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| Apple         | Mac-F221BEC8                | [05b8720dce](https://linux-hardware.org/?probe=05b8720dce) | Jun 19, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [c867520de1](https://linux-hardware.org/?probe=c867520de1) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [bc9f4e0f09](https://linux-hardware.org/?probe=bc9f4e0f09) | Jun 18, 2023 |
| HP            | 84FD                        | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| HP            | 84FD                        | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| HP            | 1496                        | [ccc9943e2d](https://linux-hardware.org/?probe=ccc9943e2d) | Jun 16, 2023 |
| Unknown       | G41 Series                  | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| ASUSTek       | Rev                         | [6c5d91db68](https://linux-hardware.org/?probe=6c5d91db68) | Jun 15, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [7df89b77f2](https://linux-hardware.org/?probe=7df89b77f2) | Jun 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [dcfab5627c](https://linux-hardware.org/?probe=dcfab5627c) | Jun 14, 2023 |
| Unknown       | G41T-M7                     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | Z77X-UD3H                   | [5cbee4094a](https://linux-hardware.org/?probe=5cbee4094a) | Jun 14, 2023 |
| ASUSTek       | M5A97 PRO                   | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| ASRock        | Z77 Extreme3                | [143672bf6c](https://linux-hardware.org/?probe=143672bf6c) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASRock        | A520M-HVS                   | [0834ca7236](https://linux-hardware.org/?probe=0834ca7236) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| ASRock        | Z77 Extreme3                | [0579a4f6f3](https://linux-hardware.org/?probe=0579a4f6f3) | Jun 13, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| Entroware     | Poseidon                    | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 81B4                        | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| Dell          | 0RY007                      | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| HP            | 3047h                       | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| Dell          | 0RY007                      | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| Dell          | 0RY007                      | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Dell          | 0RY007                      | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [11432ddeb6](https://linux-hardware.org/?probe=11432ddeb6) | May 29, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | B360M D2V                   | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| AAEON         | UP-CHCR1 V0.4               | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | 0MGK50 A02                  | [4572d76da5](https://linux-hardware.org/?probe=4572d76da5) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| Dell          | 0RY007                      | [6fb4081584](https://linux-hardware.org/?probe=6fb4081584) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | A88XM-PLUS                  | [55790e804a](https://linux-hardware.org/?probe=55790e804a) | May 25, 2023 |
| Dell          | 03KWTV A02                  | [60ade2d50f](https://linux-hardware.org/?probe=60ade2d50f) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| Intel         | DG31PR AAD97573-302         | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| Unknown       | DT138IB                     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8952bab351](https://linux-hardware.org/?probe=8952bab351) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c242460e72](https://linux-hardware.org/?probe=c242460e72) | May 20, 2023 |
| HP            | 8055                        | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| HP            | 8055                        | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| ASRock        | Z77 Extreme3                | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| ASUSTek       | Z170-A                      | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| ASUSTek       | PRIME B650M-A II            | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dbbfc6c8e](https://linux-hardware.org/?probe=9dbbfc6c8e) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| MSI           | MS-B9311                    | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| ASUSTek       | M2N68-AM SE2                | [41971afc9c](https://linux-hardware.org/?probe=41971afc9c) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [74b2c2122c](https://linux-hardware.org/?probe=74b2c2122c) | May 17, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| MSI           | 3664h                       | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| HP            | 8055                        | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| HP            | 3397                        | [3cfe6e2812](https://linux-hardware.org/?probe=3cfe6e2812) | May 15, 2023 |
| Dell          | 0KV3RP A00                  | [d324b5e64d](https://linux-hardware.org/?probe=d324b5e64d) | May 15, 2023 |
| Intel         | DX79SI AAG28808-600         | [d222ee2f89](https://linux-hardware.org/?probe=d222ee2f89) | May 14, 2023 |
| Lenovo        | NOK                         | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [6d362f8c74](https://linux-hardware.org/?probe=6d362f8c74) | May 13, 2023 |
| Intel         | DG43GT AAE62768-303         | [4cc21b00e7](https://linux-hardware.org/?probe=4cc21b00e7) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| Dell          | 0GU083 A00                  | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [297c4b54d4](https://linux-hardware.org/?probe=297c4b54d4) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| ASUSTek       | M2N68-AM SE2                | [39b8aee709](https://linux-hardware.org/?probe=39b8aee709) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| ASRock        | Z97 Extreme4                | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [669dc67190](https://linux-hardware.org/?probe=669dc67190) | May 09, 2023 |
| Acer          | Aspire TC-1760              | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [de7b924fdb](https://linux-hardware.org/?probe=de7b924fdb) | May 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [83c0648d66](https://linux-hardware.org/?probe=83c0648d66) | May 08, 2023 |
| Dell          | 0VNP2H A00                  | [ec04c034d3](https://linux-hardware.org/?probe=ec04c034d3) | May 08, 2023 |
| Gigabyte      | Z690 AERO G                 | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| ASUSTek       | M11BB                       | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Google        | Zako                        | [5d6aa6c0df](https://linux-hardware.org/?probe=5d6aa6c0df) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| ASUSTek       | P8H61-M LX                  | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| HP            | 212B                        | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [14a87bc11a](https://linux-hardware.org/?probe=14a87bc11a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | [2f3264f25f](https://linux-hardware.org/?probe=2f3264f25f) | May 04, 2023 |
| Dell          | 0RY007                      | [3ec4846de7](https://linux-hardware.org/?probe=3ec4846de7) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [86fc44372c](https://linux-hardware.org/?probe=86fc44372c) | May 03, 2023 |
| Dell          | 0RY007                      | [54e2c92bb9](https://linux-hardware.org/?probe=54e2c92bb9) | May 02, 2023 |
| HP            | 198E                        | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Shuttle       | FS35V4                      | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | [243a170e5a](https://linux-hardware.org/?probe=243a170e5a) | Apr 30, 2023 |
| HP            | ProLiant ML10 v2            | [3582be2f06](https://linux-hardware.org/?probe=3582be2f06) | Apr 30, 2023 |
| Dell          | 0T10XW A02                  | [2cd32d1efe](https://linux-hardware.org/?probe=2cd32d1efe) | Apr 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | NOK                         | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| Unknown       | G41                         | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| HP            | 1905                        | [7b15ec2d7d](https://linux-hardware.org/?probe=7b15ec2d7d) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| ASUSTek       | H110-PLUS                   | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Dell          | 0JP3NX A01                  | [2fa64e56ff](https://linux-hardware.org/?probe=2fa64e56ff) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| Dell          | 0K071D A01                  | [0c7edbd8ea](https://linux-hardware.org/?probe=0c7edbd8ea) | Apr 25, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| Dell          | 0JP3NX A01                  | [609eeb8038](https://linux-hardware.org/?probe=609eeb8038) | Apr 24, 2023 |
| MSI           | H81M PRO-VD                 | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [0dfc7cce7a](https://linux-hardware.org/?probe=0dfc7cce7a) | Apr 23, 2023 |
| ASUSTek       | M5A78L LE                   | [df70910ec6](https://linux-hardware.org/?probe=df70910ec6) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [4e664e5e26](https://linux-hardware.org/?probe=4e664e5e26) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| ASRock        | Z170 Gaming K4              | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a60c54ec31](https://linux-hardware.org/?probe=a60c54ec31) | Apr 22, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| BESSTAR Te... | UM700                       | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| ASUSTek       | M5A78L LE                   | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| HP            | 18E5                        | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| MSI           | A320M PRO-VD PLUS           | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Gigabyte      | GA-880GM-USB3               | [bb5da28703](https://linux-hardware.org/?probe=bb5da28703) | Feb 23, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Gigabyte      | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.2.0-20-generic      | 172      | 53.75%  |
| 6.2.0-24-generic      | 31       | 9.69%   |
| 6.2.0-26-generic      | 30       | 9.38%   |
| 6.2.0-25-generic      | 29       | 9.06%   |
| 6.2.0-23-generic      | 27       | 8.44%   |
| 5.19.0-21-generic     | 5        | 1.56%   |
| 6.2.0-27-generic      | 4        | 1.25%   |
| 6.3.6-060306-generic  | 2        | 0.63%   |
| 6.3.4-060304-generic  | 2        | 0.63%   |
| 6.3.2-060302-generic  | 2        | 0.63%   |
| 6.2.0-18-generic      | 2        | 0.63%   |
| 6.4.6-060406-generic  | 1        | 0.31%   |
| 6.4.0-060400-generic  | 1        | 0.31%   |
| 6.2.16-060216-generic | 1        | 0.31%   |
| 6.2.11-060211-generic | 1        | 0.31%   |
| 6.2.0-19-generic      | 1        | 0.31%   |
| 6.2.0-1009-lowlatency | 1        | 0.31%   |
| 6.2.0-1007-lowlatency | 1        | 0.31%   |
| 6.2.0-1007-gcp        | 1        | 0.31%   |
| 6.2.0-1003-lowlatency | 1        | 0.31%   |
| 6.1.0-16-generic      | 1        | 0.31%   |
| 5.19.0-45-generic     | 1        | 0.31%   |
| 5.19.0-42-generic     | 1        | 0.31%   |
| 5.19.0-38-generic     | 1        | 0.31%   |
| 5.19.0-28-generic     | 1        | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 286      | 93.46%  |
| 5.19.0  | 9        | 2.94%   |
| 6.3.6   | 2        | 0.65%   |
| 6.3.4   | 2        | 0.65%   |
| 6.3.2   | 2        | 0.65%   |
| 6.4.6   | 1        | 0.33%   |
| 6.4.0   | 1        | 0.33%   |
| 6.2.16  | 1        | 0.33%   |
| 6.2.11  | 1        | 0.33%   |
| 6.1.0   | 1        | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 288      | 94.12%  |
| 5.19    | 9        | 2.94%   |
| 6.3     | 6        | 1.96%   |
| 6.4     | 2        | 0.65%   |
| 6.1     | 1        | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 306      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 295      | 96.41%  |
| X-Cinnamon      | 6        | 1.96%   |
| Unknown         | 4        | 1.31%   |
| GNOME Flashback | 1        | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 177      | 56.91%  |
| X11     | 123      | 39.55%  |
| Tty     | 6        | 1.93%   |
| Unknown | 5        | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 267      | 86.69%  |
| Unknown | 30       | 9.74%   |
| LightDM | 8        | 2.6%    |
| GDM     | 3        | 0.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| en_US            | 146      | 47.4%   |
| de_DE            | 39       | 12.66%  |
| C                | 16       | 5.19%   |
| fr_FR            | 15       | 4.87%   |
| pt_BR            | 14       | 4.55%   |
| es_ES            | 8        | 2.6%    |
| en_GB            | 8        | 2.6%    |
| en_CA            | 7        | 2.27%   |
| ru_RU            | 5        | 1.62%   |
| it_IT            | 5        | 1.62%   |
| zh_CN            | 3        | 0.97%   |
| pl_PL            | 3        | 0.97%   |
| nl_NL            | 3        | 0.97%   |
| fi_FI            | 3        | 0.97%   |
| en_AU            | 3        | 0.97%   |
| de_AT            | 3        | 0.97%   |
| cs_CZ            | 3        | 0.97%   |
| zh_TW            | 2        | 0.65%   |
| pt_PT            | 2        | 0.65%   |
| en_NZ            | 2        | 0.65%   |
| en_IL            | 2        | 0.65%   |
| el_GR            | 2        | 0.65%   |
| Unknown          | 2        | 0.65%   |
| tr_TR            | 1        | 0.32%   |
| sv_SE            | 1        | 0.32%   |
| lt_LT            | 1        | 0.32%   |
| ko_KR            | 1        | 0.32%   |
| hu_HU            | 1        | 0.32%   |
| fr_CH            | 1        | 0.32%   |
| es_CL            | 1        | 0.32%   |
| es_AR            | 1        | 0.32%   |
| en_US.ISO-8859-1 | 1        | 0.32%   |
| en_SG            | 1        | 0.32%   |
| de_CH            | 1        | 0.32%   |
| bg_BG            | 1        | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 222      | 71.84%  |
| EFI  | 87       | 28.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Tmpfs   | 184      | 59.35%  |
| Ext4    | 117      | 37.74%  |
| Zfs     | 3        | 0.97%   |
| Overlay | 3        | 0.97%   |
| Btrfs   | 2        | 0.65%   |
| Xfs     | 1        | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 256      | 82.85%  |
| MBR     | 28       | 9.06%   |
| Unknown | 25       | 8.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 249      | 80.06%  |
| Yes       | 62       | 19.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 181      | 58.77%  |
| Yes       | 127      | 41.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 92       | 30.07%  |
| MSI                                  | 42       | 13.73%  |
| Gigabyte Technology                  | 42       | 13.73%  |
| Dell                                 | 24       | 7.84%   |
| ASRock                               | 24       | 7.84%   |
| Hewlett-Packard                      | 19       | 6.21%   |
| Lenovo                               | 14       | 4.58%   |
| Intel                                | 12       | 3.92%   |
| Unknown                              | 7        | 2.29%   |
| Fujitsu                              | 5        | 1.63%   |
| Apple                                | 3        | 0.98%   |
| Biostar                              | 2        | 0.65%   |
| Acer                                 | 2        | 0.65%   |
| ZOTAC                                | 1        | 0.33%   |
| System76                             | 1        | 0.33%   |
| Shuttle                              | 1        | 0.33%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.33%   |
| Pegatron                             | 1        | 0.33%   |
| Packard Bell                         | 1        | 0.33%   |
| MACHINIST                            | 1        | 0.33%   |
| Itautec                              | 1        | 0.33%   |
| Huanan                               | 1        | 0.33%   |
| Google                               | 1        | 0.33%   |
| GMKtec                               | 1        | 0.33%   |
| Gateway                              | 1        | 0.33%   |
| Fujitsu Siemens                      | 1        | 0.33%   |
| Entroware                            | 1        | 0.33%   |
| Colorful Technology                  | 1        | 0.33%   |
| BESSTAR Tech                         | 1        | 0.33%   |
| AZW                                  | 1        | 0.33%   |
| AAEON                                | 1        | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 9        | 2.94%   |
| ASUS All Series                            | 6        | 1.96%   |
| MSI MS-7C95                                | 2        | 0.65%   |
| MSI MS-7721                                | 2        | 0.65%   |
| MSI MS-7596                                | 2        | 0.65%   |
| Intel H61                                  | 2        | 0.65%   |
| HP EliteDesk 800 G2 DM 35W                 | 2        | 0.65%   |
| Gigabyte X670 AORUS ELITE AX               | 2        | 0.65%   |
| Dell Precision Tower 7810                  | 2        | 0.65%   |
| Dell OptiPlex 3050                         | 2        | 0.65%   |
| Dell OptiPlex 3040                         | 2        | 0.65%   |
| ASUS TUF Gaming Z590-PLUS WIFI             | 2        | 0.65%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 0.65%   |
| ASUS TUF Gaming B550-PLUS WIFI II          | 2        | 0.65%   |
| ASUS ROG STRIX B650E-I GAMING WIFI         | 2        | 0.65%   |
| ASUS PRIME Z790-A WIFI                     | 2        | 0.65%   |
| ASUS PRIME X670-P WIFI                     | 2        | 0.65%   |
| ASUS PRIME X570-P                          | 2        | 0.65%   |
| ASUS PRIME B650M-A II                      | 2        | 0.65%   |
| ASUS PRIME B550-PLUS                       | 2        | 0.65%   |
| ASUS PRIME B450M-K II                      | 2        | 0.65%   |
| ASUS PRIME B450-PLUS                       | 2        | 0.65%   |
| ASUS M5A97 R2.0                            | 2        | 0.65%   |
| ASUS H170-PRO                              | 2        | 0.65%   |
| ASRock X670E Pro RS                        | 2        | 0.65%   |
| ASRock B450M-HDV R4.0                      | 2        | 0.65%   |
| ASRock A320M-HDV R4.0                      | 2        | 0.65%   |
| Apple MacPro5,1                            | 2        | 0.65%   |
| System76 Leopard Extreme                   | 1        | 0.33%   |
| Shuttle XS35V4                             | 1        | 0.33%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.33%   |
| Pegatron H81-M1                            | 1        | 0.33%   |
| Packard Bell IMEDIA S2885                  | 1        | 0.33%   |
| MSI Pro 3000/3080                          | 1        | 0.33%   |
| MSI MS-7E01                                | 1        | 0.33%   |
| MSI MS-7D99                                | 1        | 0.33%   |
| MSI MS-7D74                                | 1        | 0.33%   |
| MSI MS-7D67                                | 1        | 0.33%   |
| MSI MS-7D53                                | 1        | 0.33%   |
| MSI MS-7D09                                | 1        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 30       | 9.8%    |
| Dell OptiPlex                              | 13       | 4.25%   |
| ASUS TUF                                   | 12       | 3.92%   |
| ASUS ROG                                   | 10       | 3.27%   |
| Unknown                                    | 9        | 2.94%   |
| Lenovo ThinkCentre                         | 7        | 2.29%   |
| ASUS All                                   | 6        | 1.96%   |
| HP Compaq                                  | 5        | 1.63%   |
| Lenovo IdeaCentre                          | 4        | 1.31%   |
| HP EliteDesk                               | 4        | 1.31%   |
| Dell Precision                             | 4        | 1.31%   |
| HP ProDesk                                 | 3        | 0.98%   |
| Gigabyte X570                              | 3        | 0.98%   |
| Gigabyte H61M-DS2                          | 3        | 0.98%   |
| Fujitsu ESPRIMO                            | 3        | 0.98%   |
| Dell Inspiron                              | 3        | 0.98%   |
| ASUS P8Z77-V                               | 3        | 0.98%   |
| ASUS P8H61-M                               | 3        | 0.98%   |
| ASUS M5A97                                 | 3        | 0.98%   |
| ASRock A320M-HDV                           | 3        | 0.98%   |
| MSI MS-7C95                                | 2        | 0.65%   |
| MSI MS-7721                                | 2        | 0.65%   |
| MSI MS-7596                                | 2        | 0.65%   |
| Intel H61                                  | 2        | 0.65%   |
| Gigabyte Z690                              | 2        | 0.65%   |
| Gigabyte X670                              | 2        | 0.65%   |
| Gigabyte A520M                             | 2        | 0.65%   |
| Dell XPS                                   | 2        | 0.65%   |
| Dell Vostro                                | 2        | 0.65%   |
| ASUS M5A78L-M                              | 2        | 0.65%   |
| ASUS H170-PRO                              | 2        | 0.65%   |
| ASRock X670E                               | 2        | 0.65%   |
| ASRock B450M-HDV                           | 2        | 0.65%   |
| Apple MacPro5                              | 2        | 0.65%   |
| Acer Aspire                                | 2        | 0.65%   |
| System76 Leopard                           | 1        | 0.33%   |
| Shuttle XS35V4                             | 1        | 0.33%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.33%   |
| Pegatron H81-M1                            | 1        | 0.33%   |
| Packard Bell IMEDIA                        | 1        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 31       | 10.13%  |
| 2021 | 30       | 9.8%    |
| 2018 | 28       | 9.15%   |
| 2012 | 26       | 8.5%    |
| 2020 | 24       | 7.84%   |
| 2014 | 23       | 7.52%   |
| 2019 | 22       | 7.19%   |
| 2013 | 19       | 6.21%   |
| 2015 | 18       | 5.88%   |
| 2017 | 16       | 5.23%   |
| 2010 | 16       | 5.23%   |
| 2011 | 14       | 4.58%   |
| 2023 | 12       | 3.92%   |
| 2016 | 11       | 3.59%   |
| 2009 | 9        | 2.94%   |
| 2008 | 4        | 1.31%   |
| 2006 | 2        | 0.65%   |
| 2007 | 1        | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 306      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 299      | 97.39%  |
| Enabled  | 8        | 2.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 305      | 99.67%  |
| Yes  | 1        | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 69       | 22.48%  |
| 32.01-64.0      | 60       | 19.54%  |
| 4.01-8.0        | 54       | 17.59%  |
| 64.01-256.0     | 36       | 11.73%  |
| 8.01-16.0       | 34       | 11.07%  |
| 3.01-4.0        | 32       | 10.42%  |
| 24.01-32.0      | 15       | 4.89%   |
| 2.01-3.0        | 3        | 0.98%   |
| More than 256.0 | 2        | 0.65%   |
| 1.01-2.0        | 2        | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 96       | 30.48%  |
| 1.01-2.0   | 82       | 26.03%  |
| 4.01-8.0   | 70       | 22.22%  |
| 3.01-4.0   | 46       | 14.6%   |
| 8.01-16.0  | 17       | 5.4%    |
| 24.01-32.0 | 2        | 0.63%   |
| 16.01-24.0 | 1        | 0.32%   |
| 0.51-1.0   | 1        | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 129      | 41.21%  |
| 2      | 71       | 22.68%  |
| 3      | 50       | 15.97%  |
| 4      | 31       | 9.9%    |
| 5      | 16       | 5.11%   |
| 6      | 11       | 3.51%   |
| 7      | 3        | 0.96%   |
| 8      | 1        | 0.32%   |
| 0      | 1        | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 63.52%  |
| Yes       | 112      | 36.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 302      | 98.37%  |
| No        | 5        | 1.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 172      | 56.21%  |
| No        | 134      | 43.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 174      | 56.86%  |
| Yes       | 132      | 43.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 62       | 20.26%  |
| Germany      | 45       | 14.71%  |
| Canada       | 21       | 6.86%   |
| France       | 19       | 6.21%   |
| Brazil       | 19       | 6.21%   |
| Italy        | 11       | 3.59%   |
| UK           | 10       | 3.27%   |
| Russia       | 8        | 2.61%   |
| Netherlands  | 8        | 2.61%   |
| Australia    | 7        | 2.29%   |
| Sweden       | 6        | 1.96%   |
| Spain        | 6        | 1.96%   |
| Portugal     | 5        | 1.63%   |
| India        | 5        | 1.63%   |
| Finland      | 5        | 1.63%   |
| Austria      | 5        | 1.63%   |
| Turkey       | 4        | 1.31%   |
| Switzerland  | 4        | 1.31%   |
| Poland       | 4        | 1.31%   |
| New Zealand  | 4        | 1.31%   |
| Greece       | 4        | 1.31%   |
| Czechia      | 4        | 1.31%   |
| Philippines  | 3        | 0.98%   |
| Israel       | 3        | 0.98%   |
| Iran         | 3        | 0.98%   |
| China        | 3        | 0.98%   |
| Taiwan       | 2        | 0.65%   |
| South Korea  | 2        | 0.65%   |
| Serbia       | 2        | 0.65%   |
| Peru         | 2        | 0.65%   |
| Lithuania    | 2        | 0.65%   |
| Hong Kong    | 2        | 0.65%   |
| Chile        | 2        | 0.65%   |
| Belgium      | 2        | 0.65%   |
| Sri Lanka    | 1        | 0.33%   |
| South Africa | 1        | 0.33%   |
| Singapore    | 1        | 0.33%   |
| Paraguay     | 1        | 0.33%   |
| Norway       | 1        | 0.33%   |
| Namibia      | 1        | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sao Paulo      | 4        | 1.29%   |
| Helsinki       | 4        | 1.29%   |
| Tehran         | 3        | 0.96%   |
| Montreal       | 3        | 0.96%   |
| Melbourne      | 3        | 0.96%   |
| Hanover        | 3        | 0.96%   |
| Berlin         | 3        | 0.96%   |
| Auckland       | 3        | 0.96%   |
| Winnipeg       | 2        | 0.64%   |
| Warsaw         | 2        | 0.64%   |
| Valencia       | 2        | 0.64%   |
| Toronto        | 2        | 0.64%   |
| Surat          | 2        | 0.64%   |
| St Petersburg  | 2        | 0.64%   |
| Sacramento     | 2        | 0.64%   |
| Prague         | 2        | 0.64%   |
| Petah Tikva    | 2        | 0.64%   |
| Oshawa         | 2        | 0.64%   |
| Munich         | 2        | 0.64%   |
| Moscow         | 2        | 0.64%   |
| Kaohsiung City | 2        | 0.64%   |
| Heilbronn      | 2        | 0.64%   |
| Hamburg        | 2        | 0.64%   |
| Florence       | 2        | 0.64%   |
| Dresden        | 2        | 0.64%   |
| Calgary        | 2        | 0.64%   |
| Brisbane       | 2        | 0.64%   |
| Biel/Bienne    | 2        | 0.64%   |
| Belgrade       | 2        | 0.64%   |
| Beijing        | 2        | 0.64%   |
| Amsterdam      | 2        | 0.64%   |
| Zaandam        | 1        | 0.32%   |
| Yuma           | 1        | 0.32%   |
| Ypsilanti      | 1        | 0.32%   |
| York           | 1        | 0.32%   |
| Würzburg      | 1        | 0.32%   |
| Wuhan          | 1        | 0.32%   |
| Wroclaw        | 1        | 0.32%   |
| Winston-Salem  | 1        | 0.32%   |
| Windsor        | 1        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 104      | 151    | 17.84%  |
| Seagate                     | 102      | 140    | 17.5%   |
| WDC                         | 89       | 125    | 15.27%  |
| SanDisk                     | 31       | 43     | 5.32%   |
| Kingston                    | 28       | 34     | 4.8%    |
| Toshiba                     | 26       | 29     | 4.46%   |
| Crucial                     | 25       | 30     | 4.29%   |
| Hitachi                     | 19       | 24     | 3.26%   |
| Intel                       | 11       | 12     | 1.89%   |
| Phison Electronics          | 10       | 11     | 1.72%   |
| SK hynix                    | 9        | 9      | 1.54%   |
| Micron/Crucial Technology   | 8        | 10     | 1.37%   |
| China                       | 6        | 7      | 1.03%   |
| Unknown                     | 5        | 5      | 0.86%   |
| Kingston Technology Company | 5        | 8      | 0.86%   |
| HGST                        | 5        | 5      | 0.86%   |
| Corsair                     | 5        | 6      | 0.86%   |
| Phison                      | 4        | 5      | 0.69%   |
| Micron Technology           | 4        | 6      | 0.69%   |
| MAXIO Technology (Hangzhou) | 4        | 4      | 0.69%   |
| KIOXIA                      | 4        | 4      | 0.69%   |
| Silicon Motion              | 3        | 3      | 0.51%   |
| SABRENT                     | 3        | 6      | 0.51%   |
| PNY                         | 3        | 4      | 0.51%   |
| OCZ                         | 3        | 3      | 0.51%   |
| Intenso                     | 3        | 3      | 0.51%   |
| Team                        | 2        | 2      | 0.34%   |
| SPCC                        | 2        | 2      | 0.34%   |
| Seagate Technology          | 2        | 2      | 0.34%   |
| Realtek                     | 2        | 2      | 0.34%   |
| Patriot                     | 2        | 2      | 0.34%   |
| OWC                         | 2        | 6      | 0.34%   |
| KingSpec                    | 2        | 3      | 0.34%   |
| Hewlett-Packard             | 2        | 2      | 0.34%   |
| Gigastone                   | 2        | 2      | 0.34%   |
| Gigabyte Technology         | 2        | 2      | 0.34%   |
| Fanxiang                    | 2        | 2      | 0.34%   |
| ASMT                        | 2        | 4      | 0.34%   |
| Apple                       | 2        | 2      | 0.34%   |
| A-DATA Technology           | 2        | 4      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 15       | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 11       | 1.66%   |
| Seagate ST1000DM010-2EP102 1TB                        | 9        | 1.36%   |
| Samsung SSD 980 1TB                                   | 9        | 1.36%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 8        | 1.21%   |
| Seagate ST2000DM008-2FR102 2TB                        | 7        | 1.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.9%    |
| Samsung SSD 850 EVO 250GB                             | 6        | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 6        | 0.9%    |
| WDC WD20EZRX-00D8PB0 2TB                              | 5        | 0.75%   |
| Seagate ST4000DM004-2CV104 4TB                        | 5        | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5        | 0.75%   |
| Samsung SSD 870 EVO 1TB                               | 5        | 0.75%   |
| Samsung SSD 860 EVO 500GB                             | 5        | 0.75%   |
| Phison E12 NVMe Controller 2TB                        | 5        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                       | 5        | 0.75%   |
| Toshiba DT01ACA100 1TB                                | 4        | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB                        | 4        | 0.6%    |
| Samsung SSD 990 PRO 1TB                               | 4        | 0.6%    |
| Samsung SSD 870 EVO 500GB                             | 4        | 0.6%    |
| Samsung SSD 860 QVO 1TB                               | 4        | 0.6%    |
| Samsung SSD 850 EVO 500GB                             | 4        | 0.6%    |
| Samsung PSSD T7 1TB                                   | 4        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                           | 4        | 0.6%    |
| WDC WD5000AAKX-00ERMA0 500GB                          | 3        | 0.45%   |
| WDC WD5000AAKX-001CA0 500GB                           | 3        | 0.45%   |
| WDC WD20EZAZ-00L9GB0 2TB                              | 3        | 0.45%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 3        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.45%   |
| Toshiba HDWD130 3TB                                   | 3        | 0.45%   |
| Toshiba DT01ACA200 2TB                                | 3        | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 3        | 0.45%   |
| Seagate ST3500418AS 500GB                             | 3        | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB                        | 3        | 0.45%   |
| Seagate ST1000DM003-9YN162 1TB                        | 3        | 0.45%   |
| Seagate ST1000DM003-1SB10C 1TB                        | 3        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB                        | 3        | 0.45%   |
| Sandisk WD Black SN850 1TB                            | 3        | 0.45%   |
| SanDisk SSD PLUS 1000GB                               | 3        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 97       | 135    | 40.08%  |
| WDC                 | 80       | 110    | 33.06%  |
| Toshiba             | 22       | 24     | 9.09%   |
| Hitachi             | 19       | 24     | 7.85%   |
| Samsung Electronics | 12       | 14     | 4.96%   |
| HGST                | 5        | 5      | 2.07%   |
| Unknown             | 2        | 2      | 0.83%   |
| ASMT                | 2        | 4      | 0.83%   |
| USB3.0              | 1        | 1      | 0.41%   |
| Intenso             | 1        | 1      | 0.41%   |
| Apple               | 1        | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 51       | 67     | 27.87%  |
| Crucial             | 20       | 22     | 10.93%  |
| Kingston            | 19       | 25     | 10.38%  |
| SanDisk             | 16       | 21     | 8.74%   |
| WDC                 | 12       | 12     | 6.56%   |
| Intel               | 7        | 8      | 3.83%   |
| China               | 6        | 7      | 3.28%   |
| Toshiba             | 3        | 3      | 1.64%   |
| OCZ                 | 3        | 3      | 1.64%   |
| Team                | 2        | 2      | 1.09%   |
| PNY                 | 2        | 2      | 1.09%   |
| Patriot             | 2        | 2      | 1.09%   |
| OWC                 | 2        | 6      | 1.09%   |
| Micron Technology   | 2        | 3      | 1.09%   |
| KingSpec            | 2        | 3      | 1.09%   |
| Hewlett-Packard     | 2        | 2      | 1.09%   |
| Gigastone           | 2        | 2      | 1.09%   |
| A-DATA Technology   | 2        | 4      | 1.09%   |
| WALRAM              | 1        | 1      | 0.55%   |
| Verbatim            | 1        | 6      | 0.55%   |
| Vaseky              | 1        | 1      | 0.55%   |
| V7                  | 1        | 1      | 0.55%   |
| TEXTORM             | 1        | 1      | 0.55%   |
| T-FORCE             | 1        | 1      | 0.55%   |
| SPCC                | 1        | 1      | 0.55%   |
| Smartbuy            | 1        | 2      | 0.55%   |
| Seagate             | 1        | 1      | 0.55%   |
| Rogueware           | 1        | 1      | 0.55%   |
| Phison              | 1        | 1      | 0.55%   |
| NN                  | 1        | 1      | 0.55%   |
| Neo                 | 1        | 2      | 0.55%   |
| MSI                 | 1        | 1      | 0.55%   |
| LuminouTek          | 1        | 1      | 0.55%   |
| LITEONIT            | 1        | 1      | 0.55%   |
| LITEON              | 1        | 1      | 0.55%   |
| Lenovo              | 1        | 1      | 0.55%   |
| LDLC                | 1        | 2      | 0.55%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.55%   |
| Intenso             | 1        | 1      | 0.55%   |
| INNOVATION IT       | 1        | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 191      | 321    | 39.3%   |
| SSD     | 154      | 230    | 31.69%  |
| NVMe    | 132      | 209    | 27.16%  |
| Unknown | 8        | 8      | 1.65%   |
| MMC     | 1        | 1      | 0.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 252      | 533    | 61.76%  |
| NVMe | 131      | 201    | 32.11%  |
| SAS  | 24       | 34     | 5.88%   |
| MMC  | 1        | 1      | 0.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 164      | 262    | 43.97%  |
| 0.51-1.0   | 114      | 167    | 30.56%  |
| 1.01-2.0   | 49       | 59     | 13.14%  |
| 3.01-4.0   | 21       | 32     | 5.63%   |
| 4.01-10.0  | 13       | 18     | 3.49%   |
| 2.01-3.0   | 10       | 10     | 2.68%   |
| 10.01-20.0 | 2        | 3      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 70       | 22.29%  |
| 251-500        | 65       | 20.7%   |
| 101-250        | 62       | 19.75%  |
| 1001-2000      | 43       | 13.69%  |
| More than 3000 | 31       | 9.87%   |
| 2001-3000      | 14       | 4.46%   |
| 1-20           | 11       | 3.5%    |
| 51-100         | 10       | 3.18%   |
| 21-50          | 6        | 1.91%   |
| Unknown        | 2        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 87       | 27.62%  |
| 21-50          | 69       | 21.9%   |
| 101-250        | 41       | 13.02%  |
| 51-100         | 37       | 11.75%  |
| 251-500        | 28       | 8.89%   |
| 501-1000       | 20       | 6.35%   |
| More than 3000 | 13       | 4.13%   |
| 2001-3000      | 9        | 2.86%   |
| 1001-2000      | 9        | 2.86%   |
| Unknown        | 2        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD        | 2        | 2      | 6.9%    |
| WDC WD5000HHTZ-04N21V0 500GB            | 1        | 1      | 3.45%   |
| WDC WD5000AZLX-22JKKA0 500GB            | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-001CA0 500GB             | 1        | 1      | 3.45%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1        | 1      | 3.45%   |
| WDC WD2500AAKX-753CA1 250GB             | 1        | 1      | 3.45%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1        | 1      | 3.45%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 1      | 3.45%   |
| WDC WD10EZEX-22MFCA0 1TB                | 1        | 2      | 3.45%   |
| WDC WD10EARS-22Y5B1 1TB                 | 1        | 1      | 3.45%   |
| Toshiba MK3261GSYN 320GB                | 1        | 1      | 3.45%   |
| Toshiba MK2555GSXF 250GB                | 1        | 1      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 1      | 3.45%   |
| Seagate ST2000LX001-1RG174 2TB          | 1        | 1      | 3.45%   |
| Seagate ST2000LM007-1R8174 2TB          | 1        | 1      | 3.45%   |
| SanDisk SSD PLUS 240GB                  | 1        | 1      | 3.45%   |
| Samsung Electronics SSD 960 EVO 250GB   | 1        | 1      | 3.45%   |
| Samsung Electronics HD502HJ 500GB       | 1        | 1      | 3.45%   |
| Samsung Electronics HD161GJ 160GB       | 1        | 1      | 3.45%   |
| Neo Forza NFS121SA312-6007000 120GB SSD | 1        | 2      | 3.45%   |
| Kingston SUV400S37240G 240GB SSD        | 1        | 1      | 3.45%   |
| Intel SSDSC2KW240H6 240GB               | 1        | 1      | 3.45%   |
| Intel SSDSC2BF180A5L 180GB              | 1        | 1      | 3.45%   |
| Hitachi HDT721010SLA360 1TB             | 1        | 1      | 3.45%   |
| Hitachi HDS721010CLA332 1TB             | 1        | 1      | 3.45%   |
| Gigabyte Technology GP-GM30512G-G 512GB | 1        | 1      | 3.45%   |
| Crucial CT512MX100SSD1 512GB            | 1        | 1      | 3.45%   |
| Crucial CT240M500SSD1 240GB             | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 31.03%  |
| Seagate             | 3        | 3      | 10.34%  |
| Samsung Electronics | 3        | 3      | 10.34%  |
| Kingston            | 3        | 3      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Intel               | 2        | 2      | 6.9%    |
| Hitachi             | 2        | 2      | 6.9%    |
| Crucial             | 2        | 2      | 6.9%    |
| SanDisk             | 1        | 1      | 3.45%   |
| Neo                 | 1        | 2      | 3.45%   |
| Gigabyte Technology | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 50%     |
| Seagate             | 3        | 3      | 16.67%  |
| Toshiba             | 2        | 2      | 11.11%  |
| Samsung Electronics | 2        | 2      | 11.11%  |
| Hitachi             | 2        | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 19     | 60.71%  |
| SSD  | 9        | 10     | 32.14%  |
| NVMe | 2        | 2      | 7.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 221      | 534    | 65.77%  |
| Works    | 90       | 203    | 26.79%  |
| Malfunc  | 24       | 31     | 7.14%   |
| Failed   | 1        | 1      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 199      | 40.78%  |
| AMD                          | 102      | 20.9%   |
| Samsung Electronics          | 54       | 11.07%  |
| SanDisk                      | 18       | 3.69%   |
| Phison Electronics           | 18       | 3.69%   |
| Micron/Crucial Technology    | 15       | 3.07%   |
| Kingston Technology Company  | 15       | 3.07%   |
| ASMedia Technology           | 15       | 3.07%   |
| SK hynix                     | 8        | 1.64%   |
| Marvell Technology Group     | 7        | 1.43%   |
| Seagate Technology           | 5        | 1.02%   |
| MAXIO Technology (Hangzhou)  | 5        | 1.02%   |
| Silicon Motion               | 4        | 0.82%   |
| KIOXIA                       | 4        | 0.82%   |
| JMicron Technology           | 4        | 0.82%   |
| Realtek Semiconductor        | 3        | 0.61%   |
| Toshiba America Info Systems | 2        | 0.41%   |
| Micron Technology            | 2        | 0.41%   |
| Yangtze Memory Technologies  | 1        | 0.2%    |
| VIA Technologies             | 1        | 0.2%    |
| Shenzhen Longsys Electronics | 1        | 0.2%    |
| Nvidia                       | 1        | 0.2%    |
| Netac Technology             | 1        | 0.2%    |
| INNOGRIT                     | 1        | 0.2%    |
| Broadcom / LSI               | 1        | 0.2%    |
| Apple                        | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63       | 10.81%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21       | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 20       | 3.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19       | 3.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 17       | 2.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15       | 2.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 2.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 13       | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 2.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 2.23%   |
| Samsung NVMe SSD Controller 980                                                         | 12       | 2.06%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 12       | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 1.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 1.72%   |
| Phison E12 NVMe Controller                                                              | 9        | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 9        | 1.54%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 1.54%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8        | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1.37%   |
| Kingston Company Company Non-Volatile memory controller                                 | 7        | 1.2%    |
| AMD FCH SATA Controller D                                                               | 7        | 1.2%    |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.03%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 5        | 0.86%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 4        | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.69%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.69%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 4        | 0.69%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.69%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 0.69%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 261      | 56.25%  |
| NVMe | 130      | 28.02%  |
| IDE  | 46       | 9.91%   |
| RAID | 27       | 5.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 201      | 65.69%  |
| AMD    | 105      | 34.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1.95%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 5        | 1.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.63%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 5        | 1.63%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 5        | 1.63%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 1.63%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 5        | 1.63%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 1.3%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 1.3%    |
| Intel 13th Gen Core i9-13900K               | 4        | 1.3%    |
| Intel 12th Gen Core i7-12700                | 4        | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 1.3%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.98%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.98%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 3        | 0.98%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.98%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.98%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.98%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 0.98%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 3        | 0.98%   |
| AMD Ryzen 9 7900 12-Core Processor          | 3        | 0.98%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 3        | 0.98%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3        | 0.98%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3        | 0.98%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 0.98%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.98%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 3        | 0.98%   |
| AMD Ryzen 5 5500                            | 3        | 0.98%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 0.98%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 2        | 0.65%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 0.65%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 0.65%   |
| Intel N100                                  | 2        | 0.65%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 2        | 0.65%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 0.65%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2        | 0.65%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.65%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 2        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 60       | 19.54%  |
| Intel Core i7           | 42       | 13.68%  |
| Other                   | 33       | 10.75%  |
| AMD Ryzen 5             | 25       | 8.14%   |
| AMD Ryzen 7             | 23       | 7.49%   |
| AMD Ryzen 9             | 21       | 6.84%   |
| Intel Core i3           | 19       | 6.19%   |
| Intel Xeon              | 17       | 5.54%   |
| Intel Core 2 Duo        | 10       | 3.26%   |
| Intel Celeron           | 6        | 1.95%   |
| AMD FX                  | 6        | 1.95%   |
| Intel Pentium           | 4        | 1.3%    |
| Intel Core 2 Quad       | 4        | 1.3%    |
| AMD Phenom II X4        | 4        | 1.3%    |
| AMD A10                 | 4        | 1.3%    |
| Intel Pentium Dual-Core | 3        | 0.98%   |
| AMD Ryzen 5 PRO         | 3        | 0.98%   |
| AMD Athlon II X2        | 3        | 0.98%   |
| AMD A8                  | 3        | 0.98%   |
| Intel Atom              | 2        | 0.65%   |
| AMD Ryzen 3             | 2        | 0.65%   |
| Intel Pentium Silver    | 1        | 0.33%   |
| Intel Core i9           | 1        | 0.33%   |
| Intel Celeron D         | 1        | 0.33%   |
| AMD Ryzen Threadripper  | 1        | 0.33%   |
| AMD Ryzen 7 PRO         | 1        | 0.33%   |
| AMD Ryzen 3 PRO         | 1        | 0.33%   |
| AMD Phenom II X2        | 1        | 0.33%   |
| AMD Phenom              | 1        | 0.33%   |
| AMD Athlon II X4        | 1        | 0.33%   |
| AMD Athlon II X3        | 1        | 0.33%   |
| AMD Athlon Dual Core    | 1        | 0.33%   |
| AMD A6                  | 1        | 0.33%   |
| AMD A4                  | 1        | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 117      | 38.24%  |
| 6      | 54       | 17.65%  |
| 2      | 49       | 16.01%  |
| 8      | 35       | 11.44%  |
| 12     | 25       | 8.17%   |
| 16     | 9        | 2.94%   |
| 24     | 5        | 1.63%   |
| 3      | 4        | 1.31%   |
| 1      | 3        | 0.98%   |
| 14     | 2        | 0.65%   |
| 32     | 1        | 0.33%   |
| 10     | 1        | 0.33%   |
| 7      | 1        | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 302      | 98.69%  |
| 2      | 4        | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 187      | 60.91%  |
| 1      | 120      | 39.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 306      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 259      | 84.36%  |
| 0x0a601203 | 13       | 4.23%   |
| 0x0a50000d | 6        | 1.95%   |
| 0x0a20120a | 4        | 1.3%    |
| 0x010000c8 | 3        | 0.98%   |
| 0x0a201025 | 2        | 0.65%   |
| 0x08701021 | 2        | 0.65%   |
| 0x0800820d | 2        | 0.65%   |
| 0xf64      | 1        | 0.33%   |
| 0x306c3    | 1        | 0.33%   |
| 0x0a704103 | 1        | 0.33%   |
| 0x0a50000c | 1        | 0.33%   |
| 0x0a50000b | 1        | 0.33%   |
| 0x0a404102 | 1        | 0.33%   |
| 0x0a201205 | 1        | 0.33%   |
| 0x08701030 | 1        | 0.33%   |
| 0x08600109 | 1        | 0.33%   |
| 0x08108109 | 1        | 0.33%   |
| 0x08101016 | 1        | 0.33%   |
| 0x0810100b | 1        | 0.33%   |
| 0x06006705 | 1        | 0.33%   |
| 0x06001119 | 1        | 0.33%   |
| 0x06000852 | 1        | 0.33%   |
| 0x00000000 | 1        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 46       | 14.98%  |
| Haswell          | 38       | 12.38%  |
| Zen 3            | 26       | 8.47%   |
| IvyBridge        | 25       | 8.14%   |
| KabyLake         | 24       | 7.82%   |
| Skylake          | 23       | 7.49%   |
| Penryn           | 17       | 5.54%   |
| Zen 2            | 15       | 4.89%   |
| SandyBridge      | 14       | 4.56%   |
| Piledriver       | 13       | 4.23%   |
| K10              | 11       | 3.58%   |
| Zen+             | 10       | 3.26%   |
| CometLake        | 8        | 2.61%   |
| Alderlake Hybrid | 6        | 1.95%   |
| Zen              | 4        | 1.3%    |
| Westmere         | 4        | 1.3%    |
| Silvermont       | 4        | 1.3%    |
| Nehalem          | 4        | 1.3%    |
| Icelake          | 3        | 0.98%   |
| Core             | 3        | 0.98%   |
| Gracemont        | 2        | 0.65%   |
| Excavator        | 2        | 0.65%   |
| NetBurst         | 1        | 0.33%   |
| K8 Hammer        | 1        | 0.33%   |
| Goldmont         | 1        | 0.33%   |
| Bulldozer        | 1        | 0.33%   |
| Broadwell        | 1        | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 115      | 34.23%  |
| Intel                      | 110      | 32.74%  |
| AMD                        | 110      | 32.74%  |
| Matrox Electronics Systems | 1        | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Raphael                                                                 | 17       | 4.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16       | 4.61%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 14       | 4.03%   |
| Intel HD Graphics 530                                                       | 14       | 4.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 4.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 2.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 8        | 2.31%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 2.31%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 1.73%   |
| Intel HD Graphics 630                                                       | 6        | 1.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.73%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.44%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.44%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 5        | 1.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.44%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 1.44%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.44%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 1.15%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 1.15%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 1.15%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 4        | 1.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 1.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.15%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4        | 1.15%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.15%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.86%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.86%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 0.86%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 3        | 0.86%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.86%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3        | 0.86%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 0.86%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.86%   |
| AMD Richland [Radeon HD 8670D]                                              | 3        | 0.86%   |
| AMD Renoir                                                                  | 3        | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 93       | 30.29%  |
| 1 x Intel           | 91       | 29.64%  |
| 1 x AMD             | 90       | 29.32%  |
| AMD + Nvidia        | 11       | 3.58%   |
| Intel + Nvidia      | 9        | 2.93%   |
| 2 x AMD             | 6        | 1.95%   |
| Intel + AMD         | 2        | 0.65%   |
| 2 x Nvidia          | 1        | 0.33%   |
| 2 x Intel + 1 x AMD | 1        | 0.33%   |
| 2 x Intel           | 1        | 0.33%   |
| 1 x Matrox          | 1        | 0.33%   |
| Intel + 2 x Nvidia  | 1        | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 222      | 71.84%  |
| Proprietary | 77       | 24.92%  |
| Unknown     | 10       | 3.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 224      | 72.26%  |
| 3.01-4.0   | 19       | 6.13%   |
| 0.01-0.5   | 18       | 5.81%   |
| 7.01-8.0   | 15       | 4.84%   |
| 1.01-2.0   | 13       | 4.19%   |
| 0.51-1.0   | 8        | 2.58%   |
| 16.01-24.0 | 5        | 1.61%   |
| 8.01-16.0  | 5        | 1.61%   |
| 5.01-6.0   | 3        | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 57       | 17.65%  |
| Goldstar             | 35       | 10.84%  |
| Dell                 | 35       | 10.84%  |
| Acer                 | 23       | 7.12%   |
| Hewlett-Packard      | 20       | 6.19%   |
| AOC                  | 19       | 5.88%   |
| Ancor Communications | 19       | 5.88%   |
| Philips              | 15       | 4.64%   |
| Iiyama               | 15       | 4.64%   |
| ViewSonic            | 9        | 2.79%   |
| BenQ                 | 8        | 2.48%   |
| ASUSTek Computer     | 6        | 1.86%   |
| MSI                  | 4        | 1.24%   |
| Lenovo               | 4        | 1.24%   |
| Fujitsu Siemens      | 3        | 0.93%   |
| Eizo                 | 3        | 0.93%   |
| Wacom                | 2        | 0.62%   |
| Vestel Elektronik    | 2        | 0.62%   |
| Unknown (XXX)        | 2        | 0.62%   |
| SGT                  | 2        | 0.62%   |
| Sceptre Tech         | 2        | 0.62%   |
| NEC Computers        | 2        | 0.62%   |
| MiTAC                | 2        | 0.62%   |
| Hitachi              | 2        | 0.62%   |
| Gigabyte Technology  | 2        | 0.62%   |
| Gericom              | 2        | 0.62%   |
| ___                  | 1        | 0.31%   |
| Xiaomi               | 1        | 0.31%   |
| Vizio                | 1        | 0.31%   |
| Unknown (AAA)        | 1        | 0.31%   |
| Unknown              | 1        | 0.31%   |
| Toshiba              | 1        | 0.31%   |
| TCL                  | 1        | 0.31%   |
| Sony                 | 1        | 0.31%   |
| SANYO                | 1        | 0.31%   |
| Positivo             | 1        | 0.31%   |
| Panasonic            | 1        | 0.31%   |
| Packard Bell         | 1        | 0.31%   |
| NECCI                | 1        | 0.31%   |
| Medion               | 1        | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 4        | 1.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.88%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.88%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.59%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 2        | 0.59%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.59%   |
| Samsung Electronics LCD Monitor SAM0D47 1920x1080 480x270mm 21.7-inch | 2        | 0.59%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 2        | 0.59%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.59%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.59%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 2        | 0.59%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 2        | 0.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2        | 0.59%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch              | 2        | 0.59%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.59%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.59%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 2        | 0.59%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 0.59%   |
| ASUSTek Computer PB278QV AUS278A 2560x1440 597x336mm 27.0-inch        | 2        | 0.59%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 2        | 0.59%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2        | 0.59%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 2        | 0.59%   |
| Acer S191HQL ACR021C 1366x768 410x230mm 18.5-inch                     | 2        | 0.59%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 2        | 0.59%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1        | 0.29%   |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                    | 1        | 0.29%   |
| Vizio E422VLE VIZ0092 1920x1080 930x523mm 42.0-inch                   | 1        | 0.29%   |
| ViewSonic XG350R-C VSC4F37 3440x1440 819x346mm 35.0-inch              | 1        | 0.29%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 0.29%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1        | 0.29%   |
| ViewSonic VX2235wm-EU VSC591E 1680x1050 474x296mm 22.0-inch           | 1        | 0.29%   |
| ViewSonic VG2755-2K VSC4E37 2560x1440 597x336mm 27.0-inch             | 1        | 0.29%   |
| ViewSonic VA2746 SERIES VSC752E 1920x1080 598x336mm 27.0-inch         | 1        | 0.29%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 1        | 0.29%   |
| ViewSonic VA2702w VSCE727 1920x1080 598x336mm 27.0-inch               | 1        | 0.29%   |
| ViewSonic VA2447-FHD VSC303B 1920x1080 527x296mm 23.8-inch            | 1        | 0.29%   |
| ViewSonic LCD Monitor VX2235wm 1680x1050                              | 1        | 0.29%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 1        | 0.29%   |
| Unknown (XXX) LED TV XXX3553 1920x1080 530x290mm 23.8-inch            | 1        | 0.29%   |
| Unknown (XXX) HD TV XXXC37E 1920x1080 700x390mm 31.5-inch             | 1        | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 156      | 50.32%  |
| 3840x2160 (4K)     | 45       | 14.52%  |
| 2560x1440 (QHD)    | 35       | 11.29%  |
| 1366x768 (WXGA)    | 12       | 3.87%   |
| 1440x900 (WXGA+)   | 11       | 3.55%   |
| 1280x1024 (SXGA)   | 10       | 3.23%   |
| 3440x1440          | 8        | 2.58%   |
| 2560x1080          | 5        | 1.61%   |
| 3840x1080          | 4        | 1.29%   |
| 1920x1200 (WUXGA)  | 4        | 1.29%   |
| Unknown            | 4        | 1.29%   |
| 1680x1050 (WSXGA+) | 3        | 0.97%   |
| 1600x900 (HD+)     | 3        | 0.97%   |
| 3840x1600          | 2        | 0.65%   |
| 1920x540           | 2        | 0.65%   |
| 1280x720 (HD)      | 2        | 0.65%   |
| 5760x2160          | 1        | 0.32%   |
| 2560x1600          | 1        | 0.32%   |
| 1360x768           | 1        | 0.32%   |
| 1024x768 (XGA)     | 1        | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 52       | 16.05%  |
| 24      | 48       | 14.81%  |
| 23      | 40       | 12.35%  |
| 21      | 39       | 12.04%  |
| 31      | 25       | 7.72%   |
| 19      | 16       | 4.94%   |
| Unknown | 14       | 4.32%   |
| 18      | 12       | 3.7%    |
| 34      | 9        | 2.78%   |
| 84      | 7        | 2.16%   |
| 40      | 6        | 1.85%   |
| 17      | 6        | 1.85%   |
| 35      | 4        | 1.23%   |
| 22      | 4        | 1.23%   |
| 72      | 3        | 0.93%   |
| 65      | 3        | 0.93%   |
| 52      | 3        | 0.93%   |
| 48      | 3        | 0.93%   |
| 42      | 3        | 0.93%   |
| 32      | 3        | 0.93%   |
| 26      | 3        | 0.93%   |
| 13      | 3        | 0.93%   |
| 28      | 2        | 0.62%   |
| 20      | 2        | 0.62%   |
| 63      | 1        | 0.31%   |
| 61      | 1        | 0.31%   |
| 60      | 1        | 0.31%   |
| 54      | 1        | 0.31%   |
| 46      | 1        | 0.31%   |
| 43      | 1        | 0.31%   |
| 38      | 1        | 0.31%   |
| 37      | 1        | 0.31%   |
| 33      | 1        | 0.31%   |
| 29      | 1        | 0.31%   |
| 16      | 1        | 0.31%   |
| 15      | 1        | 0.31%   |
| 14      | 1        | 0.31%   |
| 10      | 1        | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 129      | 40.69%  |
| 401-500     | 65       | 20.5%   |
| 601-700     | 35       | 11.04%  |
| 1001-1500   | 14       | 4.42%   |
| Unknown     | 14       | 4.42%   |
| 701-800     | 13       | 4.1%    |
| 801-900     | 11       | 3.47%   |
| 351-400     | 10       | 3.15%   |
| 1501-2000   | 10       | 3.15%   |
| 301-350     | 6        | 1.89%   |
| 201-300     | 5        | 1.58%   |
| 901-1000    | 5        | 1.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 224      | 75.42%  |
| 16/10   | 26       | 8.75%   |
| 21/9    | 15       | 5.05%   |
| 5/4     | 13       | 4.38%   |
| Unknown | 11       | 3.7%    |
| 32/9    | 5        | 1.68%   |
| 4/3     | 3        | 1.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 94       | 29.47%  |
| 301-350        | 54       | 16.93%  |
| 351-500        | 44       | 13.79%  |
| 151-200        | 31       | 9.72%   |
| 251-300        | 24       | 7.52%   |
| More than 1000 | 20       | 6.27%   |
| 141-150        | 15       | 4.7%    |
| 501-1000       | 15       | 4.7%    |
| Unknown        | 14       | 4.39%   |
| 71-80          | 3        | 0.94%   |
| 101-110        | 3        | 0.94%   |
| 51-60          | 1        | 0.31%   |
| 131-140        | 1        | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 181      | 58.58%  |
| 101-120 | 74       | 23.95%  |
| 121-160 | 17       | 5.5%    |
| Unknown | 14       | 4.53%   |
| 1-50    | 13       | 4.21%   |
| 161-240 | 10       | 3.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 235      | 75.81%  |
| 2     | 51       | 16.45%  |
| 0     | 18       | 5.81%   |
| 3     | 5        | 1.61%   |
| 4     | 1        | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 200      | 43.38%  |
| Intel                           | 124      | 26.9%   |
| Qualcomm Atheros                | 20       | 4.34%   |
| Broadcom                        | 19       | 4.12%   |
| TP-Link                         | 15       | 3.25%   |
| MediaTek                        | 15       | 3.25%   |
| Ralink Technology               | 8        | 1.74%   |
| NetGear                         | 7        | 1.52%   |
| Microsoft                       | 6        | 1.3%    |
| D-Link                          | 6        | 1.3%    |
| Aquantia                        | 4        | 0.87%   |
| Xiaomi                          | 3        | 0.65%   |
| Ralink                          | 3        | 0.65%   |
| Qualcomm Atheros Communications | 3        | 0.65%   |
| Samsung Electronics             | 2        | 0.43%   |
| Mellanox Technologies           | 2        | 0.43%   |
| Marvell Technology Group        | 2        | 0.43%   |
| Huawei Technologies             | 2        | 0.43%   |
| Google                          | 2        | 0.43%   |
| Edimax Technology               | 2        | 0.43%   |
| AVM                             | 2        | 0.43%   |
| ASUSTek Computer                | 2        | 0.43%   |
| Apple                           | 2        | 0.43%   |
| ZyDAS                           | 1        | 0.22%   |
| Z-Com                           | 1        | 0.22%   |
| Philips (or NXP)                | 1        | 0.22%   |
| Nvidia                          | 1        | 0.22%   |
| Linksys                         | 1        | 0.22%   |
| Guillemot                       | 1        | 0.22%   |
| Dresden Elektronik              | 1        | 0.22%   |
| D-Link System                   | 1        | 0.22%   |
| Broadcom Limited                | 1        | 0.22%   |
| 3Com                            | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 151      | 28.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 30       | 5.74%   |
| Intel Ethernet Controller I225-V                                  | 15       | 2.87%   |
| Intel Wi-Fi 6 AX200                                               | 12       | 2.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11       | 2.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 10       | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 9        | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.34%   |
| Realtek 802.11ac NIC                                              | 6        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 1.15%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 6        | 1.15%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 0.96%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.96%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 5        | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 4        | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4        | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                               | 4        | 0.76%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 0.76%   |
| D-Link 802.11ac NIC                                               | 4        | 0.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 4        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.57%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3        | 0.57%   |
| Intel Wireless-AC 9260                                            | 3        | 0.57%   |
| Intel Ethernet Controller I226-V                                  | 3        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.57%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.57%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 56       | 30.27%  |
| Realtek Semiconductor           | 34       | 18.38%  |
| TP-Link                         | 15       | 8.11%   |
| MediaTek                        | 15       | 8.11%   |
| Qualcomm Atheros                | 10       | 5.41%   |
| Broadcom                        | 10       | 5.41%   |
| Ralink Technology               | 8        | 4.32%   |
| NetGear                         | 7        | 3.78%   |
| Microsoft                       | 6        | 3.24%   |
| D-Link                          | 6        | 3.24%   |
| Ralink                          | 3        | 1.62%   |
| Qualcomm Atheros Communications | 3        | 1.62%   |
| Edimax Technology               | 2        | 1.08%   |
| AVM                             | 2        | 1.08%   |
| ASUSTek Computer                | 2        | 1.08%   |
| ZyDAS                           | 1        | 0.54%   |
| Z-Com                           | 1        | 0.54%   |
| Philips (or NXP)                | 1        | 0.54%   |
| Linksys                         | 1        | 0.54%   |
| Guillemot                       | 1        | 0.54%   |
| Broadcom Limited                | 1        | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12       | 6.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11       | 5.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10       | 5.38%   |
| Realtek 802.11ac NIC                                           | 6        | 3.23%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 6        | 3.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 5        | 2.69%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 5        | 2.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4        | 2.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 2.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4        | 2.15%   |
| Microsoft Xbox 360 Wireless Adapter                            | 4        | 2.15%   |
| D-Link 802.11ac NIC                                            | 4        | 2.15%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 4        | 2.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 1.61%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 1.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3        | 1.61%   |
| Intel Wireless-AC 9260                                         | 3        | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 1.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3        | 1.61%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 1.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 1.08%   |
| TP-Link 802.11ac NIC                                           | 2        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2        | 1.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 1.08%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.08%   |
| NetGear A6210                                                  | 2        | 1.08%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2        | 1.08%   |
| Intel Wireless 7260                                            | 2        | 1.08%   |
| Intel Wireless 3165                                            | 2        | 1.08%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2        | 1.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2        | 1.08%   |
| AVM FRITZ WLAN N v2 [RT5572/rt2870.bin]                        | 2        | 1.08%   |
| ASUS 802.11ac NIC                                              | 2        | 1.08%   |
| ZyDAS ZD1211B 802.11g                                          | 1        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 193      | 59.38%  |
| Intel                    | 93       | 28.62%  |
| Qualcomm Atheros         | 11       | 3.38%   |
| Broadcom                 | 9        | 2.77%   |
| Aquantia                 | 4        | 1.23%   |
| Xiaomi                   | 3        | 0.92%   |
| Mellanox Technologies    | 2        | 0.62%   |
| Marvell Technology Group | 2        | 0.62%   |
| Google                   | 2        | 0.62%   |
| Samsung Electronics      | 1        | 0.31%   |
| Nvidia                   | 1        | 0.31%   |
| Huawei Technologies      | 1        | 0.31%   |
| D-Link System            | 1        | 0.31%   |
| Apple                    | 1        | 0.31%   |
| 3Com                     | 1        | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 151      | 45.35%  |
| Realtek RTL8125 2.5GbE Controller                                             | 30       | 9.01%   |
| Intel Ethernet Controller I225-V                                              | 15       | 4.5%    |
| Intel I211 Gigabit Network Connection                                         | 9        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7        | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 2.1%    |
| Intel Ethernet Connection I217-LM                                             | 6        | 1.8%    |
| Intel Ethernet Connection (2) I219-V                                          | 6        | 1.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5        | 1.5%    |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 1.5%    |
| Intel Ethernet Connection (2) I218-V                                          | 5        | 1.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 4        | 1.2%    |
| Intel I210 Gigabit Network Connection                                         | 4        | 1.2%    |
| Intel Ethernet Connection I217-V                                              | 4        | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 1.2%    |
| Intel 82579V Gigabit Network Connection                                       | 4        | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 0.9%    |
| Intel Ethernet Controller I226-V                                              | 3        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.9%    |
| Intel Ethernet Connection (17) I219-V                                         | 3        | 0.9%    |
| Intel 82574L Gigabit Network Connection                                       | 3        | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.9%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.6%    |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 0.6%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.3%    |
| Realtek Killer E3000 2.5GbE Controller                                        | 1        | 0.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.3%    |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.3%    |
| Mellanox MT27520 Family [ConnectX-3 Pro]                                      | 1        | 0.3%    |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 1        | 0.3%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1        | 0.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 301      | 63.1%   |
| WiFi     | 172      | 36.06%  |
| Modem    | 4        | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 230      | 71.65%  |
| WiFi     | 91       | 28.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 180      | 58.82%  |
| 2     | 102      | 33.33%  |
| 3     | 19       | 6.21%   |
| 0     | 4        | 1.31%   |
| 5     | 1        | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 200      | 64.72%  |
| Yes  | 109      | 35.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 55       | 40.74%  |
| Cambridge Silicon Radio         | 19       | 14.07%  |
| Realtek Semiconductor           | 16       | 11.85%  |
| MediaTek                        | 9        | 6.67%   |
| IMC Networks                    | 8        | 5.93%   |
| ASUSTek Computer                | 6        | 4.44%   |
| TP-Link                         | 5        | 3.7%    |
| Broadcom                        | 4        | 2.96%   |
| Foxconn / Hon Hai               | 3        | 2.22%   |
| Apple                           | 3        | 2.22%   |
| Qualcomm Atheros Communications | 2        | 1.48%   |
| Lite-On Technology              | 2        | 1.48%   |
| Integrated System Solution      | 1        | 0.74%   |
| Fujitsu                         | 1        | 0.74%   |
| Dynex                           | 1        | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 19       | 14.07%  |
| Realtek Bluetooth Radio                                  | 13       | 9.63%   |
| Intel AX200 Bluetooth                                    | 11       | 8.15%   |
| Intel AX210 Bluetooth                                    | 10       | 7.41%   |
| Intel AX201 Bluetooth                                    | 10       | 7.41%   |
| MediaTek Wireless_Device                                 | 9        | 6.67%   |
| Intel Bluetooth wireless interface                       | 9        | 6.67%   |
| Intel Bluetooth Device                                   | 6        | 4.44%   |
| TP-Link UB500 Adapter                                    | 5        | 3.7%    |
| IMC Networks Bluetooth Radio                             | 5        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3        | 2.22%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3        | 2.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3        | 2.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 3        | 2.22%   |
| Apple Bluetooth USB Host Controller                      | 3        | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 1.48%   |
| IMC Networks Wireless_Device                             | 2        | 1.48%   |
| Foxconn / Hon Hai Wireless_Device                        | 2        | 1.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 1.48%   |
| ASUS ASUS USB-BT500                                      | 2        | 1.48%   |
| Realtek Bluetooth 5.1 Radio                              | 1        | 0.74%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1        | 0.74%   |
| Lite-On Bluetooth Device                                 | 1        | 0.74%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.74%   |
| IMC Networks BCM20702A0                                  | 1        | 0.74%   |
| Fujitsu Bluetooth Device                                 | 1        | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 0.74%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.74%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.74%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1        | 0.74%   |
| ASUS BCM20702A0                                          | 1        | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 193      | 37.19%  |
| AMD                                             | 133      | 25.63%  |
| Nvidia                                          | 110      | 21.19%  |
| Logitech                                        | 13       | 2.5%    |
| C-Media Electronics                             | 12       | 2.31%   |
| ASUSTek Computer                                | 8        | 1.54%   |
| Texas Instruments                               | 5        | 0.96%   |
| GN Netcom                                       | 4        | 0.77%   |
| Micro Star International                        | 3        | 0.58%   |
| KORG                                            | 3        | 0.58%   |
| VIA Technologies                                | 2        | 0.39%   |
| SteelSeries ApS                                 | 2        | 0.39%   |
| Samson Technologies                             | 2        | 0.39%   |
| Razer USA                                       | 2        | 0.39%   |
| Kingston Technology                             | 2        | 0.39%   |
| Giga-Byte Technology                            | 2        | 0.39%   |
| Creative Technology                             | 2        | 0.39%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.19%   |
| Yamaha                                          | 1        | 0.19%   |
| USB Audio                                       | 1        | 0.19%   |
| Tenx Technology                                 | 1        | 0.19%   |
| Sony                                            | 1        | 0.19%   |
| Realtek Semiconductor                           | 1        | 0.19%   |
| Nektar                                          | 1        | 0.19%   |
| Native Instruments                              | 1        | 0.19%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.19%   |
| Lenovo                                          | 1        | 0.19%   |
| JMTek                                           | 1        | 0.19%   |
| Jieli Technology                                | 1        | 0.19%   |
| JBL                                             | 1        | 0.19%   |
| Focusrite-Novation                              | 1        | 0.19%   |
| ESS Technology                                  | 1        | 0.19%   |
| DSEA A/S                                        | 1        | 0.19%   |
| Creative Labs                                   | 1        | 0.19%   |
| Corsair                                         | 1        | 0.19%   |
| BEHRINGER International                         | 1        | 0.19%   |
| Astro Gaming                                    | 1        | 0.19%   |
| Apple                                           | 1        | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 37       | 5.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 26       | 4.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21       | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19       | 3%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 19       | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18       | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 16       | 2.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 2.52%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15       | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 2.21%   |
| Intel Alder Lake-S HD Audio Controller                                     | 13       | 2.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13       | 2.05%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 1.89%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 1.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10       | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 1.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9        | 1.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.42%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.42%   |
| Nvidia GM204 High Definition Audio Controller                              | 8        | 1.26%   |
| Nvidia GA102 High Definition Audio Controller                              | 8        | 1.26%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 1.26%   |
| Nvidia GA104 High Definition Audio Controller                              | 7        | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.1%    |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 7        | 1.1%    |
| ASUSTek Computer USB Audio                                                 | 7        | 1.1%    |
| AMD Trinity HDMI Audio Controller                                          | 7        | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 7        | 1.1%    |
| Nvidia High Definition Audio Controller                                    | 6        | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                              | 6        | 0.95%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6        | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5        | 0.79%   |
| Nvidia Audio device                                                        | 5        | 0.79%   |
| Nvidia AD102 High Definition Audio Controller                              | 5        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston                             | 29       | 20.71%  |
| Corsair                              | 18       | 12.86%  |
| Unknown                              | 14       | 10%     |
| G.Skill                              | 14       | 10%     |
| Samsung Electronics                  | 13       | 9.29%   |
| Crucial                              | 11       | 7.86%   |
| SK hynix                             | 6        | 4.29%   |
| Micron Technology                    | 5        | 3.57%   |
| A-DATA Technology                    | 4        | 2.86%   |
| Team                                 | 3        | 2.14%   |
| Transcend                            | 2        | 1.43%   |
| Patriot                              | 2        | 1.43%   |
| Nanya Technology                     | 2        | 1.43%   |
| GOODRAM                              | 2        | 1.43%   |
| Unknown                              | 2        | 1.43%   |
| Unknown (0x9801)                     | 1        | 0.71%   |
| Unknown (0x0C26)                     | 1        | 0.71%   |
| Unknown (0B85)                       | 1        | 0.71%   |
| Unifosa                              | 1        | 0.71%   |
| Ramaxel Technology                   | 1        | 0.71%   |
| Patriot Memory                       | 1        | 0.71%   |
| Lexar                                | 1        | 0.71%   |
| Juhor                                | 1        | 0.71%   |
| Hewlett-Packard                      | 1        | 0.71%   |
| Elpida                               | 1        | 0.71%   |
| Chun Well Technology Holding Limited | 1        | 0.71%   |
| Atermiter                            | 1        | 0.71%   |
| ASint Technology                     | 1        | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s           | 3        | 1.99%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 2        | 1.32%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                     | 2        | 1.32%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s           | 2        | 1.32%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s              | 2        | 1.32%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s              | 2        | 1.32%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s         | 2        | 1.32%   |
| A-DATA RAM Module 16GB DIMM DDR4 3200MT/s                     | 2        | 1.32%   |
| Unknown                                                       | 2        | 1.32%   |
| Unknown RAM Module 8GB DIMM SDRAM                             | 1        | 0.66%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM SDRAM                             | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 400MT/s                           | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2                              | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR 533MT/s                       | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                          | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM SDRAM 800MT/s                     | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                      | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                      | 1        | 0.66%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s           | 1        | 0.66%   |
| Unknown (0x9801) RAM Module 4GB DIMM DDR3 1334MT/s            | 1        | 0.66%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3600 32GB DIMM DDR4 2667MT/s | 1        | 0.66%   |
| Unknown (0B85) RAM Module 8GB DIMM DDR3                       | 1        | 0.66%   |
| Unifosa RAM HU524303EP0200 2GB DIMM DDR3 1333MT/s             | 1        | 0.66%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s              | 1        | 0.66%   |
| Transcend RAM JM2666HLB-8G 8GB DIMM DDR4 2667MT/s             | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s            | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s           | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 2933MT/s           | 1        | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1        | 0.66%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s           | 1        | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1        | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s          | 1        | 0.66%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s          | 1        | 0.66%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s          | 1        | 0.66%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                     | 1        | 0.66%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s                    | 1        | 0.66%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s           | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 64       | 49.23%  |
| DDR3    | 26       | 20%     |
| DDR5    | 22       | 16.92%  |
| SDRAM   | 10       | 7.69%   |
| DDR2    | 3        | 2.31%   |
| Unknown | 3        | 2.31%   |
| LPDDR5  | 1        | 0.77%   |
| DDR     | 1        | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 117      | 92.13%  |
| SODIMM       | 9        | 7.09%   |
| Row Of Chips | 1        | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 50       | 36.5%   |
| 16384 | 30       | 21.9%   |
| 32768 | 22       | 16.06%  |
| 4096  | 20       | 14.6%   |
| 2048  | 12       | 8.76%   |
| 1024  | 3        | 2.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 19       | 13.87%  |
| 1600    | 16       | 11.68%  |
| 2400    | 10       | 7.3%    |
| 3600    | 9        | 6.57%   |
| 1333    | 6        | 4.38%   |
| 6000    | 5        | 3.65%   |
| 2667    | 5        | 3.65%   |
| 2133    | 5        | 3.65%   |
| 5600    | 4        | 2.92%   |
| 5200    | 4        | 2.92%   |
| 4800    | 4        | 2.92%   |
| 800     | 4        | 2.92%   |
| Unknown | 4        | 2.92%   |
| 6400    | 3        | 2.19%   |
| 3866    | 3        | 2.19%   |
| 3733    | 3        | 2.19%   |
| 2933    | 3        | 2.19%   |
| 5808    | 2        | 1.46%   |
| 3666    | 2        | 1.46%   |
| 3400    | 2        | 1.46%   |
| 2666    | 2        | 1.46%   |
| 1867    | 2        | 1.46%   |
| 1866    | 2        | 1.46%   |
| 667     | 2        | 1.46%   |
| 6800    | 1        | 0.73%   |
| 4199    | 1        | 0.73%   |
| 3800    | 1        | 0.73%   |
| 3534    | 1        | 0.73%   |
| 3466    | 1        | 0.73%   |
| 3334    | 1        | 0.73%   |
| 3266    | 1        | 0.73%   |
| 3066    | 1        | 0.73%   |
| 2800    | 1        | 0.73%   |
| 2176    | 1        | 0.73%   |
| 2048    | 1        | 0.73%   |
| 1800    | 1        | 0.73%   |
| 1334    | 1        | 0.73%   |
| 1066    | 1        | 0.73%   |
| 533     | 1        | 0.73%   |
| 400     | 1        | 0.73%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Samsung Electronics   | 4        | 23.53%  |
| Hewlett-Packard       | 4        | 23.53%  |
| Brother Industries    | 3        | 17.65%  |
| Seiko Epson           | 2        | 11.76%  |
| Canon                 | 2        | 11.76%  |
| QinHeng Electronics   | 1        | 5.88%   |
| Lexmark International | 1        | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 5.88%   |
| Seiko Epson ET-2820 Series                   | 1        | 5.88%   |
| Samsung SCX-4623 Series                      | 1        | 5.88%   |
| Samsung SCX-3400 Series                      | 1        | 5.88%   |
| Samsung M2020 Series                         | 1        | 5.88%   |
| Samsung CLX-3170 Series                      | 1        | 5.88%   |
| QinHeng CH340S                               | 1        | 5.88%   |
| Lexmark International MC3326adwe             | 1        | 5.88%   |
| HP LaserJet P2055 series                     | 1        | 5.88%   |
| HP DeskJet 960c                              | 1        | 5.88%   |
| HP ColorLaserJet M253-M254                   | 1        | 5.88%   |
| HP Color LaserJet Pro M453-4                 | 1        | 5.88%   |
| Canon TR4500 series                          | 1        | 5.88%   |
| Canon iP7200 series                          | 1        | 5.88%   |
| Brother MFC-J1010DW                          | 1        | 5.88%   |
| Brother MFC-9330CDW                          | 1        | 5.88%   |
| Brother HL-2030 Laser Printer                | 1        | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Plustek | 1        | 50%     |
| Canon   | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Plustek 600dpi USB Scanner | 1        | 50%     |
| Canon CanoScan LiDE 100    | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 25       | 45.45%  |
| Apple                         | 5        | 9.09%   |
| Microsoft                     | 4        | 7.27%   |
| Samsung Electronics           | 3        | 5.45%   |
| ARC International             | 3        | 5.45%   |
| Sunplus Innovation Technology | 2        | 3.64%   |
| YT-221117-J                   | 1        | 1.82%   |
| WCM_USB                       | 1        | 1.82%   |
| Trust                         | 1        | 1.82%   |
| Razer USA                     | 1        | 1.82%   |
| Pixart Imaging                | 1        | 1.82%   |
| Microdia                      | 1        | 1.82%   |
| Lite-On Technology            | 1        | 1.82%   |
| KYE Systems (Mouse Systems)   | 1        | 1.82%   |
| Generalplus Technology        | 1        | 1.82%   |
| eMeet                         | 1        | 1.82%   |
| AVerMedia Technologies        | 1        | 1.82%   |
| Anchor Chips                  | 1        | 1.82%   |
| Unknown                       | 1        | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 8        | 14.29%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X            | 4        | 7.14%   |
| Samsung Galaxy series, misc. (MTP mode)    | 3        | 5.36%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 5.36%   |
| Sunplus 1080P Webcam                       | 2        | 3.57%   |
| Microsoft LifeCam HD-3000                  | 2        | 3.57%   |
| Logitech HD Pro Webcam C920                | 2        | 3.57%   |
| ARC International Camera                   | 2        | 3.57%   |
| YT-221117-J USB2.0 Camera                  | 1        | 1.79%   |
| WCM_USB WEB CAM                            | 1        | 1.79%   |
| Trust Widescreen 3MP Webcam                | 1        | 1.79%   |
| Razer USA Gaming Webcam [Kiyo]             | 1        | 1.79%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro       | 1        | 1.79%   |
| Microsoft LifeCam NX-6000                  | 1        | 1.79%   |
| Microsoft LifeCam HD-5000                  | 1        | 1.79%   |
| Microdia Laptop_Integrated_Webcam_HD       | 1        | 1.79%   |
| Logitech Webcam Pro 9000                   | 1        | 1.79%   |
| Logitech Webcam C250                       | 1        | 1.79%   |
| Logitech Webcam C210                       | 1        | 1.79%   |
| Logitech Webcam C200                       | 1        | 1.79%   |
| Logitech Webcam C170                       | 1        | 1.79%   |
| Logitech StreamCam                         | 1        | 1.79%   |
| Logitech QuickCam Pro 9000                 | 1        | 1.79%   |
| Logitech QuickCam Communicate MP/S5500     | 1        | 1.79%   |
| Logitech HD Webcam C615                    | 1        | 1.79%   |
| Logitech HD Webcam C510                    | 1        | 1.79%   |
| Logitech C922 Pro Stream Webcam            | 1        | 1.79%   |
| Logitech Brio 500                          | 1        | 1.79%   |
| Lite-On HP Full-HD Camera                  | 1        | 1.79%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 1        | 1.79%   |
| Generalplus GENERAL WEBCAM                 | 1        | 1.79%   |
| eMeet HD Webcam C960                       | 1        | 1.79%   |
| AVerMedia Live Streamer CAM 313            | 1        | 1.79%   |
| ARC International USB 2.0 Camera           | 1        | 1.79%   |
| Apple iPod Touch 2.Gen                     | 1        | 1.79%   |
| Apple iPad 2                               | 1        | 1.79%   |
| Anchor Chips Camera                        | 1        | 1.79%   |
| Unknown                                    | 1        | 1.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 263      | 85.39%  |
| 1     | 40       | 12.99%  |
| 2     | 3        | 0.97%   |
| 6     | 1        | 0.32%   |
| 3     | 1        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 15       | 31.91%  |
| Net/wireless             | 10       | 21.28%  |
| Unassigned class         | 8        | 17.02%  |
| Communication controller | 6        | 12.77%  |
| Sound                    | 2        | 4.26%   |
| Multimedia controller    | 2        | 4.26%   |
| Camera                   | 2        | 4.26%   |
| Bluetooth                | 2        | 4.26%   |

