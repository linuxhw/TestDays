Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 925

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M5A99FX PRO R2.0            | [42cb82f584](https://linux-hardware.org/?probe=42cb82f584) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8e83e6141d](https://linux-hardware.org/?probe=8e83e6141d) | Aug 01, 2022 |
| Alienware     | 04VWF2 A02                  | [a877f0aa97](https://linux-hardware.org/?probe=a877f0aa97) | Aug 01, 2022 |
| Dell          | 0P096C A01                  | [11bc1115f2](https://linux-hardware.org/?probe=11bc1115f2) | Aug 01, 2022 |
| HP            | 3646h                       | [7988eaa5e3](https://linux-hardware.org/?probe=7988eaa5e3) | Aug 01, 2022 |
| MSI           | MEG X570 UNIFY              | [9be9a3e83b](https://linux-hardware.org/?probe=9be9a3e83b) | Aug 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [e1fa8ab12b](https://linux-hardware.org/?probe=e1fa8ab12b) | Aug 01, 2022 |
| ASUSTek       | M2A-VM                      | [4b1dabbf52](https://linux-hardware.org/?probe=4b1dabbf52) | Aug 01, 2022 |
| PCWare        | IPMH61R1                    | [0843909534](https://linux-hardware.org/?probe=0843909534) | Aug 01, 2022 |
| Apple         | Mac-F221BEC8                | [13cbc87486](https://linux-hardware.org/?probe=13cbc87486) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | [0645ed0b9e](https://linux-hardware.org/?probe=0645ed0b9e) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | [f5e17ecf3d](https://linux-hardware.org/?probe=f5e17ecf3d) | Jul 31, 2022 |
| PCWare        | IPMH61R1                    | [7da7204a12](https://linux-hardware.org/?probe=7da7204a12) | Jul 31, 2022 |
| HP            | 2AF7                        | [da51487005](https://linux-hardware.org/?probe=da51487005) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [22b4bcc010](https://linux-hardware.org/?probe=22b4bcc010) | Jul 31, 2022 |
| HP            | 3646h                       | [443cfc9c15](https://linux-hardware.org/?probe=443cfc9c15) | Jul 31, 2022 |
| Gigabyte      | F2A68HM-H                   | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [16f64b6f1a](https://linux-hardware.org/?probe=16f64b6f1a) | Jul 30, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | [7cc8e19d03](https://linux-hardware.org/?probe=7cc8e19d03) | Jul 30, 2022 |
| Acer          | FIH57                       | [a6b9d91f36](https://linux-hardware.org/?probe=a6b9d91f36) | Jul 30, 2022 |
| ASRock        | Z390 Extreme4               | [670d8c5f1e](https://linux-hardware.org/?probe=670d8c5f1e) | Jul 30, 2022 |
| Gigabyte      | H81M-HD3                    | [0f83741c2e](https://linux-hardware.org/?probe=0f83741c2e) | Jul 30, 2022 |
| ASRock        | Z390 Extreme4               | [8130877fa3](https://linux-hardware.org/?probe=8130877fa3) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f6ecfb2a51](https://linux-hardware.org/?probe=f6ecfb2a51) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7ceff6f032](https://linux-hardware.org/?probe=7ceff6f032) | Jul 30, 2022 |
| Alienware     | 0PGRP5 A01                  | [7c0915ec41](https://linux-hardware.org/?probe=7c0915ec41) | Jul 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| ASRock        | Z97 Pro4                    | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [3c18081f88](https://linux-hardware.org/?probe=3c18081f88) | Jul 29, 2022 |
| HP            | 1497                        | [1f72cc333a](https://linux-hardware.org/?probe=1f72cc333a) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [51893f2237](https://linux-hardware.org/?probe=51893f2237) | Jul 29, 2022 |
| Intel         | H61                         | [7bb7deaca9](https://linux-hardware.org/?probe=7bb7deaca9) | Jul 29, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | [5a12531bf9](https://linux-hardware.org/?probe=5a12531bf9) | Jul 29, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [e84f999c94](https://linux-hardware.org/?probe=e84f999c94) | Jul 29, 2022 |
| Dell          | 0UW457 A03                  | [b09d9907b9](https://linux-hardware.org/?probe=b09d9907b9) | Jul 29, 2022 |
| HP            | 3647h                       | [321f75b5a1](https://linux-hardware.org/?probe=321f75b5a1) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [aa77364c9c](https://linux-hardware.org/?probe=aa77364c9c) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | [c4a4fed104](https://linux-hardware.org/?probe=c4a4fed104) | Jul 28, 2022 |
| MSI           | MEG X570 ACE                | [c2741e6f43](https://linux-hardware.org/?probe=c2741e6f43) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | [61c0b1285b](https://linux-hardware.org/?probe=61c0b1285b) | Jul 28, 2022 |
| MSI           | B250M PRO-VDH               | [737604edb6](https://linux-hardware.org/?probe=737604edb6) | Jul 28, 2022 |
| ASUSTek       | Z97-C                       | [e292699b1c](https://linux-hardware.org/?probe=e292699b1c) | Jul 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [db241f583d](https://linux-hardware.org/?probe=db241f583d) | Jul 28, 2022 |
| Gigabyte      | B85-HD3                     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| Gigabyte      | GA-970A-UD3                 | [62b86d61af](https://linux-hardware.org/?probe=62b86d61af) | Jul 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [df54f79195](https://linux-hardware.org/?probe=df54f79195) | Jul 28, 2022 |
| ASUSTek       | P8H67-M LE                  | [08af503a5a](https://linux-hardware.org/?probe=08af503a5a) | Jul 28, 2022 |
| ASUSTek       | VC65                        | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| Foxconn       | ALOE X3                     | [dd3dd847b8](https://linux-hardware.org/?probe=dd3dd847b8) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | [d8b47ea062](https://linux-hardware.org/?probe=d8b47ea062) | Jul 27, 2022 |
| PCWare        | IPMH61R1                    | [18610dd9f0](https://linux-hardware.org/?probe=18610dd9f0) | Jul 27, 2022 |
| Apple         | Mac-F221BEC8                | [98461afcdb](https://linux-hardware.org/?probe=98461afcdb) | Jul 27, 2022 |
| Apple         | Mac-F221BEC8                | [703ce95e74](https://linux-hardware.org/?probe=703ce95e74) | Jul 27, 2022 |
| HP            | 8054                        | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [55318bcefe](https://linux-hardware.org/?probe=55318bcefe) | Jul 27, 2022 |
| Acer          | Aspire XC-830               | [3f67091cd9](https://linux-hardware.org/?probe=3f67091cd9) | Jul 27, 2022 |
| MSI           | X79A-GD45 Plus              | [5496428dac](https://linux-hardware.org/?probe=5496428dac) | Jul 27, 2022 |
| Acer          | Aspire XC-830               | [21032de7c0](https://linux-hardware.org/?probe=21032de7c0) | Jul 27, 2022 |
| MSI           | 2A9C                        | [de5a8c7ecd](https://linux-hardware.org/?probe=de5a8c7ecd) | Jul 27, 2022 |
| Gigabyte      | H410M S2 V3                 | [29d5401a6b](https://linux-hardware.org/?probe=29d5401a6b) | Jul 27, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [0648778462](https://linux-hardware.org/?probe=0648778462) | Jul 26, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [1e2e0882a8](https://linux-hardware.org/?probe=1e2e0882a8) | Jul 26, 2022 |
| Huanan        | X99-F8                      | [3ba1885fb4](https://linux-hardware.org/?probe=3ba1885fb4) | Jul 26, 2022 |
| Gigabyte      | Z370N WIFI-CF               | [eb3c3fceb3](https://linux-hardware.org/?probe=eb3c3fceb3) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| Acer          | FIH57                       | [f351802c52](https://linux-hardware.org/?probe=f351802c52) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| HP            | 870C                        | [b88964a379](https://linux-hardware.org/?probe=b88964a379) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [b61b6b5fa5](https://linux-hardware.org/?probe=b61b6b5fa5) | Jul 26, 2022 |
| HP            | 339A                        | [39d7b3c457](https://linux-hardware.org/?probe=39d7b3c457) | Jul 26, 2022 |
| Medion        | MS-7800                     | [cb2ef643bb](https://linux-hardware.org/?probe=cb2ef643bb) | Jul 26, 2022 |
| Acer          | FIH57                       | [df3c42e452](https://linux-hardware.org/?probe=df3c42e452) | Jul 25, 2022 |
| HP            | 18E9                        | [8514b39779](https://linux-hardware.org/?probe=8514b39779) | Jul 25, 2022 |
| Medion        | MS-7797                     | [9ad7252b8a](https://linux-hardware.org/?probe=9ad7252b8a) | Jul 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [fe6b7362b8](https://linux-hardware.org/?probe=fe6b7362b8) | Jul 25, 2022 |
| ASUSTek       | Maximus VII HERO            | [b44ef13187](https://linux-hardware.org/?probe=b44ef13187) | Jul 24, 2022 |
| HP            | 3646h                       | [65d1da3eba](https://linux-hardware.org/?probe=65d1da3eba) | Jul 24, 2022 |
| Medion        | MS-7800                     | [320071c9a0](https://linux-hardware.org/?probe=320071c9a0) | Jul 24, 2022 |
| Dell          | 0KV3RP A00                  | [be029b4d99](https://linux-hardware.org/?probe=be029b4d99) | Jul 24, 2022 |
| ASRock        | H81M-HDS                    | [b3f2310571](https://linux-hardware.org/?probe=b3f2310571) | Jul 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [903908877a](https://linux-hardware.org/?probe=903908877a) | Jul 24, 2022 |
| Dell          | 042P49 A02                  | [85391d674c](https://linux-hardware.org/?probe=85391d674c) | Jul 24, 2022 |
| XDO.AI        | Pantera Pico PC             | [e29f39ad9e](https://linux-hardware.org/?probe=e29f39ad9e) | Jul 23, 2022 |
| Dell          | 08WKV3 A00                  | [894cbd512c](https://linux-hardware.org/?probe=894cbd512c) | Jul 23, 2022 |
| ASUSTek       | P5QPL-AM                    | [79113b8782](https://linux-hardware.org/?probe=79113b8782) | Jul 23, 2022 |
| AZW           | SEi                         | [e2d04ac048](https://linux-hardware.org/?probe=e2d04ac048) | Jul 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4b3a55fc55](https://linux-hardware.org/?probe=4b3a55fc55) | Jul 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [7d3501365a](https://linux-hardware.org/?probe=7d3501365a) | Jul 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [b0e3bc86bc](https://linux-hardware.org/?probe=b0e3bc86bc) | Jul 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [8288af270f](https://linux-hardware.org/?probe=8288af270f) | Jul 23, 2022 |
| HP            | 2B2B                        | [14cefcf857](https://linux-hardware.org/?probe=14cefcf857) | Jul 22, 2022 |
| Gigabyte      | Z690I A ULTRA PLUS D4       | [453b2cce27](https://linux-hardware.org/?probe=453b2cce27) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [a57ab4e2dc](https://linux-hardware.org/?probe=a57ab4e2dc) | Jul 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f383b92a53](https://linux-hardware.org/?probe=f383b92a53) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| ASUSTek       | P7H55-M LX                  | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| Shuttle       | FH67H                       | [fe77bc1ab0](https://linux-hardware.org/?probe=fe77bc1ab0) | Jul 22, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [07be23439c](https://linux-hardware.org/?probe=07be23439c) | Jul 21, 2022 |
| Pegatron      | Benicia                     | [f197aeb457](https://linux-hardware.org/?probe=f197aeb457) | Jul 21, 2022 |
| Unknown       | T3 MRD                      | [afbe55b100](https://linux-hardware.org/?probe=afbe55b100) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| ASUSTek       | A88X-PRO                    | [a9fb1104e7](https://linux-hardware.org/?probe=a9fb1104e7) | Jul 20, 2022 |
| ASRock        | B450 Pro4                   | [7037061aed](https://linux-hardware.org/?probe=7037061aed) | Jul 20, 2022 |
| Acer          | EQ45M                       | [53a74d39e4](https://linux-hardware.org/?probe=53a74d39e4) | Jul 20, 2022 |
| ASUSTek       | A88X-PRO                    | [400c3cee0d](https://linux-hardware.org/?probe=400c3cee0d) | Jul 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d88edfec1f](https://linux-hardware.org/?probe=d88edfec1f) | Jul 20, 2022 |
| Huanan        | X99-TF V2.0                 | [4217957e12](https://linux-hardware.org/?probe=4217957e12) | Jul 19, 2022 |
| Medion        | MS-7797                     | [68faff0dba](https://linux-hardware.org/?probe=68faff0dba) | Jul 19, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [2c81e24a1a](https://linux-hardware.org/?probe=2c81e24a1a) | Jul 19, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [290d973b31](https://linux-hardware.org/?probe=290d973b31) | Jul 19, 2022 |
| MSI           | Z77A-G43                    | [56afef1d13](https://linux-hardware.org/?probe=56afef1d13) | Jul 19, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f32b12f921](https://linux-hardware.org/?probe=f32b12f921) | Jul 19, 2022 |
| Dell          | 0CRH6C A02                  | [e324e6a67b](https://linux-hardware.org/?probe=e324e6a67b) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| PCPartner     | MILANO-P Rev.00             | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| Intel         | X79M-S                      | [225309497e](https://linux-hardware.org/?probe=225309497e) | Jul 18, 2022 |
| Intel         | X79M-S                      | [d788e4c74d](https://linux-hardware.org/?probe=d788e4c74d) | Jul 18, 2022 |
| ASUSTek       | WS X299 SAGE                | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [ec770759cd](https://linux-hardware.org/?probe=ec770759cd) | Jul 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [325fbd84e9](https://linux-hardware.org/?probe=325fbd84e9) | Jul 17, 2022 |
| ASRock        | H310CM-HDV                  | [5cad17641f](https://linux-hardware.org/?probe=5cad17641f) | Jul 17, 2022 |
| ASUSTek       | Z170-K                      | [094ba7059b](https://linux-hardware.org/?probe=094ba7059b) | Jul 16, 2022 |
| Gigabyte      | P55-USB3                    | [a974b4bb92](https://linux-hardware.org/?probe=a974b4bb92) | Jul 16, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [88f3a17986](https://linux-hardware.org/?probe=88f3a17986) | Jul 16, 2022 |
| ASUSTek       | PRIME H610M-E D4            | [66fe37549d](https://linux-hardware.org/?probe=66fe37549d) | Jul 16, 2022 |
| ASRock        | H61M-GS                     | [a653521268](https://linux-hardware.org/?probe=a653521268) | Jul 16, 2022 |
| ASRock        | H61M-GS                     | [1d2de44667](https://linux-hardware.org/?probe=1d2de44667) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [710cf5ff0e](https://linux-hardware.org/?probe=710cf5ff0e) | Jul 16, 2022 |
| ASUSTek       | P8H61-M LX2                 | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Acer          | FIH57                       | [ea25a3cc88](https://linux-hardware.org/?probe=ea25a3cc88) | Jul 15, 2022 |
| Supermicro    | X10DRH-CT                   | [bcf5e02acd](https://linux-hardware.org/?probe=bcf5e02acd) | Jul 15, 2022 |
| ASUSTek       | H81M-E                      | [a227b89fef](https://linux-hardware.org/?probe=a227b89fef) | Jul 15, 2022 |
| Lenovo        | 7033EW4                     | [e471fc8ecd](https://linux-hardware.org/?probe=e471fc8ecd) | Jul 15, 2022 |
| Intel         | D54250WYK H13922-304        | [2ea167ab24](https://linux-hardware.org/?probe=2ea167ab24) | Jul 15, 2022 |
| Dell          | 042P49 A02                  | [bb5748e226](https://linux-hardware.org/?probe=bb5748e226) | Jul 15, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [48c1d4e141](https://linux-hardware.org/?probe=48c1d4e141) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [14a754a395](https://linux-hardware.org/?probe=14a754a395) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | [844ac53526](https://linux-hardware.org/?probe=844ac53526) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | [3b8f491017](https://linux-hardware.org/?probe=3b8f491017) | Jul 14, 2022 |
| ASUSTek       | H81M-E                      | [e1ef49be7d](https://linux-hardware.org/?probe=e1ef49be7d) | Jul 14, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7797840c50](https://linux-hardware.org/?probe=7797840c50) | Jul 14, 2022 |
| ASRockRack    | ROMED8-2T                   | [e56577e7d4](https://linux-hardware.org/?probe=e56577e7d4) | Jul 14, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [a4f5723ada](https://linux-hardware.org/?probe=a4f5723ada) | Jul 14, 2022 |
| ASRockRack    | ROMED8-2T                   | [d0bfc3e9d3](https://linux-hardware.org/?probe=d0bfc3e9d3) | Jul 14, 2022 |
| Dell          | 0W2F8G A01                  | [77f2181e08](https://linux-hardware.org/?probe=77f2181e08) | Jul 13, 2022 |
| ASUSTek       | X99-A                       | [6db5d85e5c](https://linux-hardware.org/?probe=6db5d85e5c) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK               | [6cf3eeb7fc](https://linux-hardware.org/?probe=6cf3eeb7fc) | Jul 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [37890b5158](https://linux-hardware.org/?probe=37890b5158) | Jul 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [0e195b05bf](https://linux-hardware.org/?probe=0e195b05bf) | Jul 13, 2022 |
| MSI           | A320M PRO-VH PLUS           | [e007a2fbc2](https://linux-hardware.org/?probe=e007a2fbc2) | Jul 13, 2022 |
| HP            | 2B17                        | [c9481d00f3](https://linux-hardware.org/?probe=c9481d00f3) | Jul 13, 2022 |
| Intel         | D34010WYK H14771-304        | [3fe93a38f6](https://linux-hardware.org/?probe=3fe93a38f6) | Jul 13, 2022 |
| Dell          | 07KY25 A00                  | [14e0ab8eb2](https://linux-hardware.org/?probe=14e0ab8eb2) | Jul 13, 2022 |
| Acer          | EQ45M                       | [22911b2564](https://linux-hardware.org/?probe=22911b2564) | Jul 12, 2022 |
| Gigabyte      | A520M S2H                   | [52aab7f65b](https://linux-hardware.org/?probe=52aab7f65b) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [43e78c262a](https://linux-hardware.org/?probe=43e78c262a) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [063f846aad](https://linux-hardware.org/?probe=063f846aad) | Jul 12, 2022 |
| HP            | 2B2B                        | [3254e734a5](https://linux-hardware.org/?probe=3254e734a5) | Jul 12, 2022 |
| Intel         | D34010WYK H14771-304        | [26c70348e9](https://linux-hardware.org/?probe=26c70348e9) | Jul 12, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [37ee80d118](https://linux-hardware.org/?probe=37ee80d118) | Jul 11, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [80de38308d](https://linux-hardware.org/?probe=80de38308d) | Jul 11, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1a80abdbf2](https://linux-hardware.org/?probe=1a80abdbf2) | Jul 11, 2022 |
| ASUSTek       | P5LD2                       | [933399f6f5](https://linux-hardware.org/?probe=933399f6f5) | Jul 11, 2022 |
| MSI           | H81M-P33                    | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| Acer          | Aspire M3920                | [9b12bf66ac](https://linux-hardware.org/?probe=9b12bf66ac) | Jul 11, 2022 |
| YANYU         | EPIC-C19                    | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| Acer          | FIH57                       | [b052eec1d0](https://linux-hardware.org/?probe=b052eec1d0) | Jul 10, 2022 |
| Dell          | 09M8Y8 A02                  | [b4f3b56350](https://linux-hardware.org/?probe=b4f3b56350) | Jul 10, 2022 |
| Acer          | Nitro N50-610               | [48c007b4e2](https://linux-hardware.org/?probe=48c007b4e2) | Jul 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [978d27ca8b](https://linux-hardware.org/?probe=978d27ca8b) | Jul 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3209c50980](https://linux-hardware.org/?probe=3209c50980) | Jul 10, 2022 |
| Medion        | H81H3-EM2                   | [fbe5cf60f0](https://linux-hardware.org/?probe=fbe5cf60f0) | Jul 10, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [5ccd729440](https://linux-hardware.org/?probe=5ccd729440) | Jul 10, 2022 |
| Apple         | Mac-F221BEC8                | [2efb274f31](https://linux-hardware.org/?probe=2efb274f31) | Jul 10, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [cbe2ceab3e](https://linux-hardware.org/?probe=cbe2ceab3e) | Jul 10, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [f5d291204f](https://linux-hardware.org/?probe=f5d291204f) | Jul 10, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [d1eaa06cd9](https://linux-hardware.org/?probe=d1eaa06cd9) | Jul 09, 2022 |
| ABIT          | IP35-E                      | [797026a126](https://linux-hardware.org/?probe=797026a126) | Jul 09, 2022 |
| ABIT          | IP35-E                      | [e217f62c10](https://linux-hardware.org/?probe=e217f62c10) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| Unknown       | Unknown                     | [e7dfa60f77](https://linux-hardware.org/?probe=e7dfa60f77) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8ac6704c06](https://linux-hardware.org/?probe=8ac6704c06) | Jul 09, 2022 |
| Gigabyte      | Z690 UD DDR4                | [bcec55fd41](https://linux-hardware.org/?probe=bcec55fd41) | Jul 09, 2022 |
| Pegatron      | 2AC3                        | [e1d3204cf2](https://linux-hardware.org/?probe=e1d3204cf2) | Jul 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [75f0ca97b8](https://linux-hardware.org/?probe=75f0ca97b8) | Jul 08, 2022 |
| ASRock        | A320M-HDV R4.0              | [4f7f102599](https://linux-hardware.org/?probe=4f7f102599) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [d66a60be9a](https://linux-hardware.org/?probe=d66a60be9a) | Jul 08, 2022 |
| ECS           | H110M4-C23                  | [4a4af6d2e9](https://linux-hardware.org/?probe=4a4af6d2e9) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | [560e81bb64](https://linux-hardware.org/?probe=560e81bb64) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | [4f57a8d7f4](https://linux-hardware.org/?probe=4f57a8d7f4) | Jul 08, 2022 |
| HP            | 212B                        | [f5972124a5](https://linux-hardware.org/?probe=f5972124a5) | Jul 08, 2022 |
| HP            | 212B                        | [c6b1d18aec](https://linux-hardware.org/?probe=c6b1d18aec) | Jul 08, 2022 |
| MSI           | 2A9C                        | [40457980de](https://linux-hardware.org/?probe=40457980de) | Jul 08, 2022 |
| ASRock        | G41M-VS3                    | [fe19bb609e](https://linux-hardware.org/?probe=fe19bb609e) | Jul 08, 2022 |
| ASRock        | G41M-VS3                    | [8dc2d34c99](https://linux-hardware.org/?probe=8dc2d34c99) | Jul 08, 2022 |
| MSI           | Z590-A PRO                  | [45155c9045](https://linux-hardware.org/?probe=45155c9045) | Jul 07, 2022 |
| MSI           | Z590-A PRO                  | [2685bc5f4f](https://linux-hardware.org/?probe=2685bc5f4f) | Jul 07, 2022 |
| ASUSTek       | PRIME Z590-P                | [53fbdec1df](https://linux-hardware.org/?probe=53fbdec1df) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [758112a61d](https://linux-hardware.org/?probe=758112a61d) | Jul 07, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [50dc2b8c60](https://linux-hardware.org/?probe=50dc2b8c60) | Jul 07, 2022 |
| MSI           | X470 GAMING PRO             | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| HP            | 18E7                        | [68781cd22f](https://linux-hardware.org/?probe=68781cd22f) | Jul 07, 2022 |
| Dell          | 0FKVT5 A01                  | [8f61264039](https://linux-hardware.org/?probe=8f61264039) | Jul 07, 2022 |
| Dell          | 0FKVT5 A01                  | [de88b169a1](https://linux-hardware.org/?probe=de88b169a1) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [5b90bd12c7](https://linux-hardware.org/?probe=5b90bd12c7) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [9c2136e4eb](https://linux-hardware.org/?probe=9c2136e4eb) | Jul 07, 2022 |
| ASUSTek       | PRIME B450M-A               | [a3548b2397](https://linux-hardware.org/?probe=a3548b2397) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [21f58df6b0](https://linux-hardware.org/?probe=21f58df6b0) | Jul 06, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [ebaa969297](https://linux-hardware.org/?probe=ebaa969297) | Jul 06, 2022 |
| HP            | 870C                        | [17993cf668](https://linux-hardware.org/?probe=17993cf668) | Jul 06, 2022 |
| ASUSTek       | P5GC-MX                     | [a3ec66a255](https://linux-hardware.org/?probe=a3ec66a255) | Jul 05, 2022 |
| Acer          | FIH57                       | [75895f96b9](https://linux-hardware.org/?probe=75895f96b9) | Jul 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [e400d050db](https://linux-hardware.org/?probe=e400d050db) | Jul 05, 2022 |
| HP            | 3646h                       | [36c53efdac](https://linux-hardware.org/?probe=36c53efdac) | Jul 05, 2022 |
| HP            | 3646h                       | [675a46eda3](https://linux-hardware.org/?probe=675a46eda3) | Jul 05, 2022 |
| HP            | 3648h                       | [4d9ef6de51](https://linux-hardware.org/?probe=4d9ef6de51) | Jul 05, 2022 |
| MSI           | Z170-A PRO                  | [24a76119e1](https://linux-hardware.org/?probe=24a76119e1) | Jul 04, 2022 |
| Dell          | 07KY25 A01                  | [35ac60e264](https://linux-hardware.org/?probe=35ac60e264) | Jul 04, 2022 |
| Shuttle       | FS61                        | [43d79d98be](https://linux-hardware.org/?probe=43d79d98be) | Jul 04, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5c8477b1a3](https://linux-hardware.org/?probe=5c8477b1a3) | Jul 04, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [6f75b1c1e4](https://linux-hardware.org/?probe=6f75b1c1e4) | Jul 04, 2022 |
| MSI           | 970A SLI Krait Edition      | [3199c023cb](https://linux-hardware.org/?probe=3199c023cb) | Jul 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [c76805b11f](https://linux-hardware.org/?probe=c76805b11f) | Jul 04, 2022 |
| HP            | 18E7                        | [39c3a381f4](https://linux-hardware.org/?probe=39c3a381f4) | Jul 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| ASUSTek       | M5A99X EVO                  | [f0c71f2614](https://linux-hardware.org/?probe=f0c71f2614) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [2a709f4166](https://linux-hardware.org/?probe=2a709f4166) | Jul 03, 2022 |
| Acer          | Aspire TC-280               | [7322461b76](https://linux-hardware.org/?probe=7322461b76) | Jul 03, 2022 |
| HP            | 8643 SMVB                   | [66de926a3d](https://linux-hardware.org/?probe=66de926a3d) | Jul 03, 2022 |
| ASUSTek       | B85M-G R2.0                 | [ab0751d062](https://linux-hardware.org/?probe=ab0751d062) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6fa5768750](https://linux-hardware.org/?probe=6fa5768750) | Jul 02, 2022 |
| Medion        | MS-7797                     | [0fa607f9a5](https://linux-hardware.org/?probe=0fa607f9a5) | Jul 02, 2022 |
| Dell          | 0D28YY A03                  | [de2bbc9ab0](https://linux-hardware.org/?probe=de2bbc9ab0) | Jul 02, 2022 |
| MSI           | Z170A GAMING M7             | [a0d37a0b9f](https://linux-hardware.org/?probe=a0d37a0b9f) | Jul 02, 2022 |
| Gigabyte      | H81M-S                      | [4a6acd9191](https://linux-hardware.org/?probe=4a6acd9191) | Jul 02, 2022 |
| Apple         | Mac-F221BEC8                | [564950d244](https://linux-hardware.org/?probe=564950d244) | Jul 02, 2022 |
| Acer          | Aspire TC-280               | [0e497c1c13](https://linux-hardware.org/?probe=0e497c1c13) | Jul 02, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [dbeb1565c1](https://linux-hardware.org/?probe=dbeb1565c1) | Jul 02, 2022 |
| Foxconn       | ALOE X3                     | [754758d432](https://linux-hardware.org/?probe=754758d432) | Jul 02, 2022 |
| ASRock        | N68-VS3 UCC                 | [dd43bf961c](https://linux-hardware.org/?probe=dd43bf961c) | Jul 02, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [060a34b3a1](https://linux-hardware.org/?probe=060a34b3a1) | Jul 01, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [630bb92cd8](https://linux-hardware.org/?probe=630bb92cd8) | Jul 01, 2022 |
| MSI           | Z390 GAM PRO CARB AC        | [a55ab11db7](https://linux-hardware.org/?probe=a55ab11db7) | Jul 01, 2022 |
| Dell          | 042P49 A02                  | [110e5da723](https://linux-hardware.org/?probe=110e5da723) | Jul 01, 2022 |
| Intel         | DX58SO AAE29331-703         | [3b22974574](https://linux-hardware.org/?probe=3b22974574) | Jul 01, 2022 |
| Medion        | MS-7797                     | [01ff2f8272](https://linux-hardware.org/?probe=01ff2f8272) | Jul 01, 2022 |
| ASUSTek       | M5A78L LE                   | [19dbe00e60](https://linux-hardware.org/?probe=19dbe00e60) | Jul 01, 2022 |
| HP            | 805D                        | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| Dell          | 042P49 A02                  | [169b7b8c30](https://linux-hardware.org/?probe=169b7b8c30) | Jul 01, 2022 |
| Gigabyte      | H81M-S2PH                   | [cc62a478ac](https://linux-hardware.org/?probe=cc62a478ac) | Jul 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [9b8bb163d3](https://linux-hardware.org/?probe=9b8bb163d3) | Jul 01, 2022 |
| ECS           | A780GM-A                    | [2cea4325e9](https://linux-hardware.org/?probe=2cea4325e9) | Jul 01, 2022 |
| Unknown       | Unknown                     | [1de34d9bf9](https://linux-hardware.org/?probe=1de34d9bf9) | Jun 30, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [349dc94a13](https://linux-hardware.org/?probe=349dc94a13) | Jun 29, 2022 |
| MSI           | MEG Z490 UNIFY              | [2c7a50869d](https://linux-hardware.org/?probe=2c7a50869d) | Jun 29, 2022 |
| Dell          | 0M5DCD A00                  | [7ff0a3f172](https://linux-hardware.org/?probe=7ff0a3f172) | Jun 29, 2022 |
| Dell          | 0M5DCD A00                  | [483d6a9299](https://linux-hardware.org/?probe=483d6a9299) | Jun 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | [20a14662e8](https://linux-hardware.org/?probe=20a14662e8) | Jun 29, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [389293962a](https://linux-hardware.org/?probe=389293962a) | Jun 29, 2022 |
| ASUSTek       | B85M-E                      | [2423d184c0](https://linux-hardware.org/?probe=2423d184c0) | Jun 29, 2022 |
| ASUSTek       | P5LD2                       | [4fdebc2b9c](https://linux-hardware.org/?probe=4fdebc2b9c) | Jun 29, 2022 |
| ASRock        | B550M-ITX/ac                | [01614433d5](https://linux-hardware.org/?probe=01614433d5) | Jun 29, 2022 |
| ASUSTek       | P5LD2                       | [c7f67d9347](https://linux-hardware.org/?probe=c7f67d9347) | Jun 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| Dell          | 0D24M8 A00                  | [1588270a58](https://linux-hardware.org/?probe=1588270a58) | Jun 29, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d59692d648](https://linux-hardware.org/?probe=d59692d648) | Jun 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5873a7a8dd](https://linux-hardware.org/?probe=5873a7a8dd) | Jun 29, 2022 |
| MSI           | H110M GAMING                | [e33051cbd0](https://linux-hardware.org/?probe=e33051cbd0) | Jun 28, 2022 |
| Dell          | 0TP406                      | [4f0f2b2e05](https://linux-hardware.org/?probe=4f0f2b2e05) | Jun 28, 2022 |
| Acer          | H81-M1                      | [9ddfb2ec8d](https://linux-hardware.org/?probe=9ddfb2ec8d) | Jun 28, 2022 |
| HP            | 0B4Ch D                     | [6e28eeb447](https://linux-hardware.org/?probe=6e28eeb447) | Jun 27, 2022 |
| Dell          | 0RF703                      | [7b1a5ddcb6](https://linux-hardware.org/?probe=7b1a5ddcb6) | Jun 27, 2022 |
| ASRock        | 970 Pro3 R2.0               | [ba2f829e73](https://linux-hardware.org/?probe=ba2f829e73) | Jun 27, 2022 |
| Dell          | 051FJ8 A02                  | [5b997790f1](https://linux-hardware.org/?probe=5b997790f1) | Jun 27, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [3d575e19b6](https://linux-hardware.org/?probe=3d575e19b6) | Jun 27, 2022 |
| MSI           | B450M-A PRO MAX             | [666f9678a5](https://linux-hardware.org/?probe=666f9678a5) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | [48cbc869da](https://linux-hardware.org/?probe=48cbc869da) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | [ea31080862](https://linux-hardware.org/?probe=ea31080862) | Jun 27, 2022 |
| MSI           | Z590-A PRO                  | [1adcde94c5](https://linux-hardware.org/?probe=1adcde94c5) | Jun 26, 2022 |
| MSI           | Z590-A PRO                  | [18d6fda695](https://linux-hardware.org/?probe=18d6fda695) | Jun 26, 2022 |
| MSI           | H55M-E33                    | [035cfe1a5b](https://linux-hardware.org/?probe=035cfe1a5b) | Jun 26, 2022 |
| MSI           | B450M PRO-M2                | [516abfbea1](https://linux-hardware.org/?probe=516abfbea1) | Jun 26, 2022 |
| MSI           | B450M-A PRO MAX             | [aa9757e958](https://linux-hardware.org/?probe=aa9757e958) | Jun 26, 2022 |
| ASUSTek       | P8Z68-V LX                  | [5935ab812a](https://linux-hardware.org/?probe=5935ab812a) | Jun 26, 2022 |
| MSI           | PRO Z690-A                  | [34a2f4f726](https://linux-hardware.org/?probe=34a2f4f726) | Jun 26, 2022 |
| ASUSTek       | P8H61-I                     | [15b8beca14](https://linux-hardware.org/?probe=15b8beca14) | Jun 26, 2022 |
| Dell          | 0HD5W2 A01                  | [9f87421952](https://linux-hardware.org/?probe=9f87421952) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| MSI           | A78M-E45 V2                 | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| Gigabyte      | X570 GAMING X               | [b66ac35391](https://linux-hardware.org/?probe=b66ac35391) | Jun 26, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [f440505698](https://linux-hardware.org/?probe=f440505698) | Jun 25, 2022 |
| MSI           | H81M-P33                    | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [8f2b511688](https://linux-hardware.org/?probe=8f2b511688) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ace55b44d7](https://linux-hardware.org/?probe=ace55b44d7) | Jun 25, 2022 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [1be22bc8af](https://linux-hardware.org/?probe=1be22bc8af) | Jun 24, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [57660d8f0f](https://linux-hardware.org/?probe=57660d8f0f) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | [fc1716de1f](https://linux-hardware.org/?probe=fc1716de1f) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | [785ec99ee8](https://linux-hardware.org/?probe=785ec99ee8) | Jun 24, 2022 |
| Gigabyte      | A520M S2H                   | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| Dell          | 0KW626                      | [ceb37aeba1](https://linux-hardware.org/?probe=ceb37aeba1) | Jun 24, 2022 |
| Intel         | X79G V2.x                   | [67b2e27895](https://linux-hardware.org/?probe=67b2e27895) | Jun 24, 2022 |
| ASUSTek       | X99-DELUXE                  | [34e3aad338](https://linux-hardware.org/?probe=34e3aad338) | Jun 24, 2022 |
| HP            | 2AF7                        | [86ecfeb9e2](https://linux-hardware.org/?probe=86ecfeb9e2) | Jun 24, 2022 |
| Dell          | 018D1Y A00                  | [8344a8b783](https://linux-hardware.org/?probe=8344a8b783) | Jun 24, 2022 |
| Foxconn       | 2AB1                        | [389a1d6185](https://linux-hardware.org/?probe=389a1d6185) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| ASRock        | Z590M-ITX/ax                | [263e8a50af](https://linux-hardware.org/?probe=263e8a50af) | Jun 23, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [95d5b870bb](https://linux-hardware.org/?probe=95d5b870bb) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [3cfb6f7ee5](https://linux-hardware.org/?probe=3cfb6f7ee5) | Jun 23, 2022 |
| Lenovo        | MAHOBAY                     | [8f7a233327](https://linux-hardware.org/?probe=8f7a233327) | Jun 22, 2022 |
| Dell          | 0W2F8G A01                  | [447653d4f2](https://linux-hardware.org/?probe=447653d4f2) | Jun 22, 2022 |
| Dell          | 0W2F8G A01                  | [4610c38358](https://linux-hardware.org/?probe=4610c38358) | Jun 22, 2022 |
| ASUSTek       | P6T WS PRO                  | [9899337065](https://linux-hardware.org/?probe=9899337065) | Jun 22, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e4116b95a2](https://linux-hardware.org/?probe=e4116b95a2) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [836efa773c](https://linux-hardware.org/?probe=836efa773c) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [380b66353e](https://linux-hardware.org/?probe=380b66353e) | Jun 21, 2022 |
| MSI           | A320M-A PRO                 | [1f3b17165b](https://linux-hardware.org/?probe=1f3b17165b) | Jun 21, 2022 |
| ASRock        | H81M-VG4                    | [f9f9db00a7](https://linux-hardware.org/?probe=f9f9db00a7) | Jun 21, 2022 |
| Acer          | Aspire X1700                | [6a67f8cba0](https://linux-hardware.org/?probe=6a67f8cba0) | Jun 21, 2022 |
| HP            | 0AA0h                       | [ccc94e1725](https://linux-hardware.org/?probe=ccc94e1725) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | [c52b07844d](https://linux-hardware.org/?probe=c52b07844d) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | [31f786c1ff](https://linux-hardware.org/?probe=31f786c1ff) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | [280d4af2d2](https://linux-hardware.org/?probe=280d4af2d2) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | [c90adf6d43](https://linux-hardware.org/?probe=c90adf6d43) | Jun 21, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Gigabyte      | B450M DS3H WIFI V2-CF       | [37f7936cd9](https://linux-hardware.org/?probe=37f7936cd9) | Jun 21, 2022 |
| Dell          | 0VD92X A00                  | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| ASUSTek       | Q87M-E                      | [9f37139898](https://linux-hardware.org/?probe=9f37139898) | Jun 21, 2022 |
| Dell          | 0TP406                      | [3798b45f67](https://linux-hardware.org/?probe=3798b45f67) | Jun 20, 2022 |
| MSI           | A78M-E45 V2                 | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| MSI           | Creator X299                | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| MSI           | A320M-A PRO                 | [8cecec73c6](https://linux-hardware.org/?probe=8cecec73c6) | Jun 19, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Gigabyte      | 965P-S3                     | [0beb9ce480](https://linux-hardware.org/?probe=0beb9ce480) | Jun 19, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [4c91d4b394](https://linux-hardware.org/?probe=4c91d4b394) | Jun 19, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [571829be67](https://linux-hardware.org/?probe=571829be67) | Jun 19, 2022 |
| ASUSTek       | X99-A/USB                   | [d9808cc5aa](https://linux-hardware.org/?probe=d9808cc5aa) | Jun 19, 2022 |
| Dell          | 09M8Y8 A02                  | [a029173d31](https://linux-hardware.org/?probe=a029173d31) | Jun 18, 2022 |
| Acer          | Aspire X3950                | [7a70838628](https://linux-hardware.org/?probe=7a70838628) | Jun 18, 2022 |
| Dell          | 0XHGV1 A00                  | [aeb1a92366](https://linux-hardware.org/?probe=aeb1a92366) | Jun 18, 2022 |
| MSI           | A320M-A PRO MAX             | [50149d3df0](https://linux-hardware.org/?probe=50149d3df0) | Jun 18, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [3e7ce078c6](https://linux-hardware.org/?probe=3e7ce078c6) | Jun 18, 2022 |
| Gigabyte      | H61M-DS2                    | [866ee7a33b](https://linux-hardware.org/?probe=866ee7a33b) | Jun 18, 2022 |
| Gigabyte      | F2A68HM-H                   | [3adcbf0255](https://linux-hardware.org/?probe=3adcbf0255) | Jun 18, 2022 |
| ASRock        | G41M-GS                     | [9167934132](https://linux-hardware.org/?probe=9167934132) | Jun 18, 2022 |
| ASUSTek       | H110M-CS/BR                 | [35cfc3daf7](https://linux-hardware.org/?probe=35cfc3daf7) | Jun 18, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [63e3deaaf4](https://linux-hardware.org/?probe=63e3deaaf4) | Jun 17, 2022 |
| Gigabyte      | M68MT-S2                    | [570c3b2345](https://linux-hardware.org/?probe=570c3b2345) | Jun 17, 2022 |
| ASUSTek       | H110M-CS/BR                 | [47e88dae48](https://linux-hardware.org/?probe=47e88dae48) | Jun 17, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| HP            | 1998                        | [86d621451f](https://linux-hardware.org/?probe=86d621451f) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [d52a1b8eea](https://linux-hardware.org/?probe=d52a1b8eea) | Jun 17, 2022 |
| HP            | 8184 X4                     | [e2f24b580b](https://linux-hardware.org/?probe=e2f24b580b) | Jun 17, 2022 |
| Dell          | 0KRC95 A00                  | [c47403b875](https://linux-hardware.org/?probe=c47403b875) | Jun 17, 2022 |
| HP            | 8184 X4                     | [668438d39e](https://linux-hardware.org/?probe=668438d39e) | Jun 17, 2022 |
| MSI           | B450-A PRO MAX              | [24ecffb555](https://linux-hardware.org/?probe=24ecffb555) | Jun 16, 2022 |
| Lenovo        | 3148 SDK0J40709 WIN 3259... | [475e980cb3](https://linux-hardware.org/?probe=475e980cb3) | Jun 16, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [63ba339f77](https://linux-hardware.org/?probe=63ba339f77) | Jun 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f005c585bd](https://linux-hardware.org/?probe=f005c585bd) | Jun 16, 2022 |
| Gigabyte      | B560M DS3H AC               | [f0b95571fd](https://linux-hardware.org/?probe=f0b95571fd) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | [549a55efdf](https://linux-hardware.org/?probe=549a55efdf) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | [693d81e1a3](https://linux-hardware.org/?probe=693d81e1a3) | Jun 16, 2022 |
| HP            | 3031h                       | [00080c0264](https://linux-hardware.org/?probe=00080c0264) | Jun 16, 2022 |
| ASUSTek       | PRIME X570-P                | [4dc736e2b5](https://linux-hardware.org/?probe=4dc736e2b5) | Jun 16, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [e8f85ab771](https://linux-hardware.org/?probe=e8f85ab771) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| MSI           | MPG B550I GAMING EDGE MA... | [69b95cc638](https://linux-hardware.org/?probe=69b95cc638) | Jun 16, 2022 |
| Nvidia        | MCP73                       | [4af86ef214](https://linux-hardware.org/?probe=4af86ef214) | Jun 15, 2022 |
| Nvidia        | MCP73                       | [bc4b2de5bc](https://linux-hardware.org/?probe=bc4b2de5bc) | Jun 15, 2022 |
| Gigabyte      | M68MT-S2                    | [ded75509fb](https://linux-hardware.org/?probe=ded75509fb) | Jun 15, 2022 |
| Lenovo        | 3148 SDK0J40709 WIN 3259... | [8d5ba3c58c](https://linux-hardware.org/?probe=8d5ba3c58c) | Jun 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [8bf8ec8bd0](https://linux-hardware.org/?probe=8bf8ec8bd0) | Jun 15, 2022 |
| Acer          | Aspire X1400                | [a90701fd86](https://linux-hardware.org/?probe=a90701fd86) | Jun 15, 2022 |
| MSI           | B550M PRO-VDH               | [9916ed24a9](https://linux-hardware.org/?probe=9916ed24a9) | Jun 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [c8dfb12509](https://linux-hardware.org/?probe=c8dfb12509) | Jun 14, 2022 |
| Medion        | B460H6-EM                   | [b2d8ad91a9](https://linux-hardware.org/?probe=b2d8ad91a9) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| ASUSTek       | F2A55-M                     | [845c94e939](https://linux-hardware.org/?probe=845c94e939) | Jun 14, 2022 |
| MSI           | A78M-E45 V2                 | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | P9X79 PRO                   | [6643e636b5](https://linux-hardware.org/?probe=6643e636b5) | Jun 14, 2022 |
| MSI           | H81M-E33                    | [d6180859a8](https://linux-hardware.org/?probe=d6180859a8) | Jun 14, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [aeb975478b](https://linux-hardware.org/?probe=aeb975478b) | Jun 14, 2022 |
| ASUSTek       | F2A55-M                     | [3cf5e25cca](https://linux-hardware.org/?probe=3cf5e25cca) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | [15cb74d079](https://linux-hardware.org/?probe=15cb74d079) | Jun 13, 2022 |
| ASUSTek       | PRIME H310M-E               | [f0e0fc8360](https://linux-hardware.org/?probe=f0e0fc8360) | Jun 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| ASRock        | B75M-DGS R2.0               | [457047ad06](https://linux-hardware.org/?probe=457047ad06) | Jun 13, 2022 |
| Acer          | Veriton X2631G V:1.0        | [8f7cca461c](https://linux-hardware.org/?probe=8f7cca461c) | Jun 13, 2022 |
| ASUSTek       | F2A55-M                     | [e6a15fe5a4](https://linux-hardware.org/?probe=e6a15fe5a4) | Jun 13, 2022 |
| ASUSTek       | PRO H410M-C                 | [055ed7de1b](https://linux-hardware.org/?probe=055ed7de1b) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | [0c6a9f5dff](https://linux-hardware.org/?probe=0c6a9f5dff) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | [aeec9e715d](https://linux-hardware.org/?probe=aeec9e715d) | Jun 13, 2022 |
| ASRock        | B460M Pro4                  | [603eff18a0](https://linux-hardware.org/?probe=603eff18a0) | Jun 12, 2022 |
| Intel         | DH61CR AAG14064-207         | [a840bbb5a3](https://linux-hardware.org/?probe=a840bbb5a3) | Jun 12, 2022 |
| Dell          | 0XHGV1 A00                  | [6eec9d17a5](https://linux-hardware.org/?probe=6eec9d17a5) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [d22ca1b39a](https://linux-hardware.org/?probe=d22ca1b39a) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| ASUSTek       | F2A55-M                     | [8f99758eb8](https://linux-hardware.org/?probe=8f99758eb8) | Jun 12, 2022 |
| Intel         | DB75EN AAG39650-400         | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| HP            | 3396                        | [4c0f1563a7](https://linux-hardware.org/?probe=4c0f1563a7) | Jun 12, 2022 |
| MSI           | A68HM-E33 V2                | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [a3ca1ea153](https://linux-hardware.org/?probe=a3ca1ea153) | Jun 12, 2022 |
| Unknown       | X99-GT                      | [6a36412f6d](https://linux-hardware.org/?probe=6a36412f6d) | Jun 12, 2022 |
| ASUSTek       | H170M-PLUS                  | [416fd6d121](https://linux-hardware.org/?probe=416fd6d121) | Jun 11, 2022 |
| Biostar       | B450MX-S                    | [be9e9c5a99](https://linux-hardware.org/?probe=be9e9c5a99) | Jun 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | [d07617dd7a](https://linux-hardware.org/?probe=d07617dd7a) | Jun 11, 2022 |
| Pegatron      | 2AC3                        | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [a3dcf1b0d6](https://linux-hardware.org/?probe=a3dcf1b0d6) | Jun 11, 2022 |
| Acer          | Veriton X2631G V:1.0        | [943f097be0](https://linux-hardware.org/?probe=943f097be0) | Jun 11, 2022 |
| Unknown       | G41                         | [04e03cb3d5](https://linux-hardware.org/?probe=04e03cb3d5) | Jun 10, 2022 |
| Lenovo        | ThinkServer TS140           | [23515284b5](https://linux-hardware.org/?probe=23515284b5) | Jun 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [eb7ee3a693](https://linux-hardware.org/?probe=eb7ee3a693) | Jun 10, 2022 |
| ASUSTek       | M5A99X EVO                  | [e54c226fed](https://linux-hardware.org/?probe=e54c226fed) | Jun 10, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f00af11f1c](https://linux-hardware.org/?probe=f00af11f1c) | Jun 10, 2022 |
| ASUSTek       | PRIME X570-P                | [1e73a95e9e](https://linux-hardware.org/?probe=1e73a95e9e) | Jun 10, 2022 |
| ASUSTek       | P5Q                         | [df07364c28](https://linux-hardware.org/?probe=df07364c28) | Jun 10, 2022 |
| Dell          | 0XHGV1 A00                  | [0de2a3f1a0](https://linux-hardware.org/?probe=0de2a3f1a0) | Jun 10, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [238e30f096](https://linux-hardware.org/?probe=238e30f096) | Jun 10, 2022 |
| Foxconn       | 2AB7                        | [339721d187](https://linux-hardware.org/?probe=339721d187) | Jun 10, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [9deff6136b](https://linux-hardware.org/?probe=9deff6136b) | Jun 10, 2022 |
| Gigabyte      | H61M-DS2                    | [e202a8662f](https://linux-hardware.org/?probe=e202a8662f) | Jun 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [b33d07af6c](https://linux-hardware.org/?probe=b33d07af6c) | Jun 09, 2022 |
| Dell          | 0XCR8D A03                  | [7b5fb1809b](https://linux-hardware.org/?probe=7b5fb1809b) | Jun 09, 2022 |
| Dell          | 06JWJY A01                  | [d4675eb5c0](https://linux-hardware.org/?probe=d4675eb5c0) | Jun 09, 2022 |
| Dell          | 0XCR8D A03                  | [08cc695028](https://linux-hardware.org/?probe=08cc695028) | Jun 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bda08758b5](https://linux-hardware.org/?probe=bda08758b5) | Jun 09, 2022 |
| MSI           | A55M-E33                    | [388ba5e3dd](https://linux-hardware.org/?probe=388ba5e3dd) | Jun 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6d195af721](https://linux-hardware.org/?probe=6d195af721) | Jun 09, 2022 |
| Gigabyte      | 970A-UD3P                   | [7e45eef7ba](https://linux-hardware.org/?probe=7e45eef7ba) | Jun 09, 2022 |
| MSI           | MAG B550M MORTAR            | [40c1095611](https://linux-hardware.org/?probe=40c1095611) | Jun 08, 2022 |
| ASUSTek       | PRIME B350M-A               | [d5f5af27dc](https://linux-hardware.org/?probe=d5f5af27dc) | Jun 08, 2022 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [36d73de92c](https://linux-hardware.org/?probe=36d73de92c) | Jun 08, 2022 |
| Gigabyte      | F2A55M-HD2                  | [19e1ff0736](https://linux-hardware.org/?probe=19e1ff0736) | Jun 08, 2022 |
| HP            | 1998                        | [362416dfc1](https://linux-hardware.org/?probe=362416dfc1) | Jun 08, 2022 |
| Acer          | Veriton X2631G V:1.0        | [0c5963ea95](https://linux-hardware.org/?probe=0c5963ea95) | Jun 07, 2022 |
| HP            | 8433 11                     | [fa4c4f5c0e](https://linux-hardware.org/?probe=fa4c4f5c0e) | Jun 07, 2022 |
| MSI           | B550-A PRO                  | [13c7b714dc](https://linux-hardware.org/?probe=13c7b714dc) | Jun 07, 2022 |
| Gigabyte      | F2A68HM-S1                  | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [c443fc775b](https://linux-hardware.org/?probe=c443fc775b) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [9ab2042d74](https://linux-hardware.org/?probe=9ab2042d74) | Jun 07, 2022 |
| ASRock        | H55M                        | [058eceb951](https://linux-hardware.org/?probe=058eceb951) | Jun 07, 2022 |
| ASUSTek       | PRO H410M-C                 | [fa1a1d1431](https://linux-hardware.org/?probe=fa1a1d1431) | Jun 07, 2022 |
| Gigabyte      | B85M-D2V                    | [fabaa25753](https://linux-hardware.org/?probe=fabaa25753) | Jun 07, 2022 |
| MSI           | H510I PRO WIFI              | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| Shuttle       | FS61                        | [4f4bd19a2d](https://linux-hardware.org/?probe=4f4bd19a2d) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| Intel         | H61                         | [8178c4da07](https://linux-hardware.org/?probe=8178c4da07) | Jun 06, 2022 |
| MSI           | A68HM-E33                   | [0c4686ca42](https://linux-hardware.org/?probe=0c4686ca42) | Jun 06, 2022 |
| Dell          | 0C2XKD A01                  | [e82c37f339](https://linux-hardware.org/?probe=e82c37f339) | Jun 06, 2022 |
| ASUSTek       | Q87M-E                      | [3c8c0d1998](https://linux-hardware.org/?probe=3c8c0d1998) | Jun 06, 2022 |
| MSI           | A320M-A PRO                 | [488a6e3259](https://linux-hardware.org/?probe=488a6e3259) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [0dd5791ff8](https://linux-hardware.org/?probe=0dd5791ff8) | Jun 05, 2022 |
| Dell          | 0200DY A01                  | [00f49d760b](https://linux-hardware.org/?probe=00f49d760b) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [1b7a237b9b](https://linux-hardware.org/?probe=1b7a237b9b) | Jun 05, 2022 |
| Dell          | 0HHV7N A00                  | [45bdcd9b5c](https://linux-hardware.org/?probe=45bdcd9b5c) | Jun 05, 2022 |
| Dell          | 0C3YXR A00                  | [5c72365ea3](https://linux-hardware.org/?probe=5c72365ea3) | Jun 05, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX         | [4760e98a1c](https://linux-hardware.org/?probe=4760e98a1c) | Jun 05, 2022 |
| Dell          | 0K3CM7 A00                  | [d90f0bb618](https://linux-hardware.org/?probe=d90f0bb618) | Jun 05, 2022 |
| MSI           | B460M-A PRO                 | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [e636b14f58](https://linux-hardware.org/?probe=e636b14f58) | Jun 05, 2022 |
| ASUSTek       | M5A97 R2.0                  | [07468743a9](https://linux-hardware.org/?probe=07468743a9) | Jun 04, 2022 |
| MSI           | B85M-E45                    | [4446978a6f](https://linux-hardware.org/?probe=4446978a6f) | Jun 04, 2022 |
| MSI           | H510I PRO WIFI              | [39d9bd396f](https://linux-hardware.org/?probe=39d9bd396f) | Jun 04, 2022 |
| Shuttle       | DS10U                       | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| ASRock        | 870 Extreme3                | [e93db26e8c](https://linux-hardware.org/?probe=e93db26e8c) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| Biostar       | G41U3G                      | [40d72e8d4a](https://linux-hardware.org/?probe=40d72e8d4a) | Jun 04, 2022 |
| ASUSTek       | PRIME A320M-K               | [5d311a66dc](https://linux-hardware.org/?probe=5d311a66dc) | Jun 04, 2022 |
| Biostar       | G41U3G                      | [d3eb0d0a63](https://linux-hardware.org/?probe=d3eb0d0a63) | Jun 03, 2022 |
| Supermicro    | X10SBA-LA                   | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [a31e1dac27](https://linux-hardware.org/?probe=a31e1dac27) | Jun 03, 2022 |
| ASUSTek       | P8B75-M LE                  | [72008ba457](https://linux-hardware.org/?probe=72008ba457) | Jun 03, 2022 |
| MSI           | A68HM-P33                   | [9dbbf2c6ec](https://linux-hardware.org/?probe=9dbbf2c6ec) | Jun 03, 2022 |
| MSI           | B75MA-E33                   | [cba34d6021](https://linux-hardware.org/?probe=cba34d6021) | Jun 03, 2022 |
| MSI           | A68HM-P33                   | [0590463974](https://linux-hardware.org/?probe=0590463974) | Jun 03, 2022 |
| MSI           | A68HM-P33 V2                | [ff55b171ff](https://linux-hardware.org/?probe=ff55b171ff) | Jun 03, 2022 |
| ASUSTek       | B85M-G                      | [68e585cb49](https://linux-hardware.org/?probe=68e585cb49) | Jun 03, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [eccf357f9f](https://linux-hardware.org/?probe=eccf357f9f) | Jun 03, 2022 |
| Gigabyte      | Z590 VISION G               | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [051dd28c75](https://linux-hardware.org/?probe=051dd28c75) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | [3210714de1](https://linux-hardware.org/?probe=3210714de1) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | [9b01043ab8](https://linux-hardware.org/?probe=9b01043ab8) | Jun 03, 2022 |
| ASRock        | 760GM-HDV                   | [b72f6362e5](https://linux-hardware.org/?probe=b72f6362e5) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | [86be2de304](https://linux-hardware.org/?probe=86be2de304) | Jun 02, 2022 |
| ASUSTek       | B85M-G                      | [c0273d93b6](https://linux-hardware.org/?probe=c0273d93b6) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | [979e6b0d13](https://linux-hardware.org/?probe=979e6b0d13) | Jun 02, 2022 |
| ASUSTek       | H110M-K                     | [e85b6e752d](https://linux-hardware.org/?probe=e85b6e752d) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | [3fc80d0ef1](https://linux-hardware.org/?probe=3fc80d0ef1) | Jun 02, 2022 |
| MSI           | A68HM-P33                   | [a47c89c432](https://linux-hardware.org/?probe=a47c89c432) | Jun 02, 2022 |
| MSI           | A68HM-P33                   | [6cb525598b](https://linux-hardware.org/?probe=6cb525598b) | Jun 02, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [238f6ecead](https://linux-hardware.org/?probe=238f6ecead) | Jun 02, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [c8c6c6ca29](https://linux-hardware.org/?probe=c8c6c6ca29) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K               | [2a7bfa492d](https://linux-hardware.org/?probe=2a7bfa492d) | Jun 02, 2022 |
| Gigabyte      | Z690 UD DDR4                | [17a0805ec2](https://linux-hardware.org/?probe=17a0805ec2) | Jun 02, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [bfd781966f](https://linux-hardware.org/?probe=bfd781966f) | Jun 02, 2022 |
| ASRock        | 760GM-HDV                   | [e116b2ed29](https://linux-hardware.org/?probe=e116b2ed29) | Jun 01, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [db32f9ad3e](https://linux-hardware.org/?probe=db32f9ad3e) | Jun 01, 2022 |
| MSI           | Z77A-G41                    | [8a43bd2e75](https://linux-hardware.org/?probe=8a43bd2e75) | Jun 01, 2022 |
| Gigabyte      | F2A55M-HD2                  | [cb731e1ef2](https://linux-hardware.org/?probe=cb731e1ef2) | Jun 01, 2022 |
| MSI           | A68HM-E33                   | [c784c88156](https://linux-hardware.org/?probe=c784c88156) | Jun 01, 2022 |
| MSI           | A68HM-P33                   | [cf1188fed4](https://linux-hardware.org/?probe=cf1188fed4) | Jun 01, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [915fbaa0ea](https://linux-hardware.org/?probe=915fbaa0ea) | Jun 01, 2022 |
| ASUSTek       | Z170-P                      | [4684599a3a](https://linux-hardware.org/?probe=4684599a3a) | Jun 01, 2022 |
| ASRock        | H81M-DG4                    | [45dbfa155f](https://linux-hardware.org/?probe=45dbfa155f) | Jun 01, 2022 |
| ASUSTek       | STRIX B250H GAMING          | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| Alienware     | 0XJKKD A00                  | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| MSI           | B250M BAZOOKA               | [45d3300158](https://linux-hardware.org/?probe=45d3300158) | Jun 01, 2022 |
| Dell          | 0NK5PH A00                  | [960e8817bf](https://linux-hardware.org/?probe=960e8817bf) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Pegatron      | 2AED                        | [67df0b1c08](https://linux-hardware.org/?probe=67df0b1c08) | May 31, 2022 |
| Dell          | 07WP95 A02                  | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Dell          | 0200DY A01                  | [0d7be8de90](https://linux-hardware.org/?probe=0d7be8de90) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | [72484e859d](https://linux-hardware.org/?probe=72484e859d) | May 31, 2022 |
| Dell          | 0200DY A01                  | [c3c585ba02](https://linux-hardware.org/?probe=c3c585ba02) | May 31, 2022 |
| Unknown       | Unknown                     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | [9f7d224ed7](https://linux-hardware.org/?probe=9f7d224ed7) | May 31, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [ab6fb60b96](https://linux-hardware.org/?probe=ab6fb60b96) | May 31, 2022 |
| ASUSTek       | H81M-A                      | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Intel         | DP67BG AAG10491-305         | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| Gigabyte      | Q35M-S2                     | [7ef3498226](https://linux-hardware.org/?probe=7ef3498226) | May 30, 2022 |
| ASRock        | 870 Extreme3                | [7e2000d3a1](https://linux-hardware.org/?probe=7e2000d3a1) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b0e96de917](https://linux-hardware.org/?probe=b0e96de917) | May 30, 2022 |
| ASUSTek       | PRO H410M-C                 | [c40635b66e](https://linux-hardware.org/?probe=c40635b66e) | May 30, 2022 |
| Unknown       | Unknown                     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b4f73129a2](https://linux-hardware.org/?probe=b4f73129a2) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | [44e2ec7714](https://linux-hardware.org/?probe=44e2ec7714) | May 30, 2022 |
| ASUSTek       | X99-E-10G WS                | [83e525ca4e](https://linux-hardware.org/?probe=83e525ca4e) | May 30, 2022 |
| ECS           | MCP61M-M3                   | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0b83e8fa79](https://linux-hardware.org/?probe=0b83e8fa79) | May 29, 2022 |
| Intel         | DQ35JO AAD82085-803         | [40429e6d9a](https://linux-hardware.org/?probe=40429e6d9a) | May 29, 2022 |
| Biostar       | G41U3G                      | [1c6caef665](https://linux-hardware.org/?probe=1c6caef665) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [bcca466c5e](https://linux-hardware.org/?probe=bcca466c5e) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [c11ae8de66](https://linux-hardware.org/?probe=c11ae8de66) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [c1dd2cf1be](https://linux-hardware.org/?probe=c1dd2cf1be) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [0df520da7e](https://linux-hardware.org/?probe=0df520da7e) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [b83d80f5d2](https://linux-hardware.org/?probe=b83d80f5d2) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Shuttle       | FS81                        | [756f86d9fc](https://linux-hardware.org/?probe=756f86d9fc) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [3c144d36f0](https://linux-hardware.org/?probe=3c144d36f0) | May 28, 2022 |
| Pegatron      | 2ACF                        | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| ASUSTek       | H110M-K                     | [9ff7306bbd](https://linux-hardware.org/?probe=9ff7306bbd) | May 28, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0399b42b7](https://linux-hardware.org/?probe=c0399b42b7) | May 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [1094233e96](https://linux-hardware.org/?probe=1094233e96) | May 28, 2022 |
| Dell          | 0C2XKD A01                  | [2aaa53dd85](https://linux-hardware.org/?probe=2aaa53dd85) | May 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5458522367](https://linux-hardware.org/?probe=5458522367) | May 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ce112fb9d2](https://linux-hardware.org/?probe=ce112fb9d2) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7aea9bfd](https://linux-hardware.org/?probe=bd7aea9bfd) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [26e26a3995](https://linux-hardware.org/?probe=26e26a3995) | May 28, 2022 |
| MSI           | B450 TOMAHAWK               | [2651c1881a](https://linux-hardware.org/?probe=2651c1881a) | May 27, 2022 |
| Dell          | 0GXM1W A02                  | [8e0891e3c7](https://linux-hardware.org/?probe=8e0891e3c7) | May 27, 2022 |
| Dell          | 09KPNV A01                  | [b98a471ead](https://linux-hardware.org/?probe=b98a471ead) | May 27, 2022 |
| Dell          | 09KPNV A01                  | [44162ea497](https://linux-hardware.org/?probe=44162ea497) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f5beaba229](https://linux-hardware.org/?probe=f5beaba229) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [2624ebd3a1](https://linux-hardware.org/?probe=2624ebd3a1) | May 27, 2022 |
| ASUSTek       | B150-PLUS                   | [bdcda1dabc](https://linux-hardware.org/?probe=bdcda1dabc) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| Dell          | 0YJPT1 A00                  | [b122151e55](https://linux-hardware.org/?probe=b122151e55) | May 27, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| Dell          | 0MY171 A01                  | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [3774c9e6e6](https://linux-hardware.org/?probe=3774c9e6e6) | May 26, 2022 |
| MSI           | A320M-A PRO MAX             | [f1ccdbbba4](https://linux-hardware.org/?probe=f1ccdbbba4) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [f52de609a0](https://linux-hardware.org/?probe=f52de609a0) | May 26, 2022 |
| ASUSTek       | PRO H410M-C                 | [e38c676047](https://linux-hardware.org/?probe=e38c676047) | May 26, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [9d9a7dc189](https://linux-hardware.org/?probe=9d9a7dc189) | May 25, 2022 |
| ASRock        | AB350M Pro4                 | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Gigabyte      | G31M-S2C                    | [5251ce0950](https://linux-hardware.org/?probe=5251ce0950) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| Dell          | 0DT029 A00                  | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a649429f59](https://linux-hardware.org/?probe=a649429f59) | May 25, 2022 |
| Dell          | 096JG8 A01                  | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| Dell          | 0WG864                      | [5bda6fbb3a](https://linux-hardware.org/?probe=5bda6fbb3a) | May 24, 2022 |
| Gigabyte      | P55-UD3L                    | [256b5355c3](https://linux-hardware.org/?probe=256b5355c3) | May 24, 2022 |
| Dell          | 0HY9JP A01                  | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| MSI           | H97M-G43                    | [4c1e9752b6](https://linux-hardware.org/?probe=4c1e9752b6) | May 23, 2022 |
| ASUSTek       | PRIME B660M-A AC D4         | [286688e46b](https://linux-hardware.org/?probe=286688e46b) | May 23, 2022 |
| ASRock        | 970 Pro3 R2.0               | [afeae78ecd](https://linux-hardware.org/?probe=afeae78ecd) | May 23, 2022 |
| Shuttle       | FS110                       | [d1147263be](https://linux-hardware.org/?probe=d1147263be) | May 23, 2022 |
| Intel         | H55                         | [8dd80b1c9d](https://linux-hardware.org/?probe=8dd80b1c9d) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| ASUSTek       | PRO H410M-C                 | [a700df310a](https://linux-hardware.org/?probe=a700df310a) | May 23, 2022 |
| Intel         | H55                         | [c383403505](https://linux-hardware.org/?probe=c383403505) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | Z390 UD                     | [d49bf6427c](https://linux-hardware.org/?probe=d49bf6427c) | May 23, 2022 |
| MSI           | 2AE0                        | [ea14a764bb](https://linux-hardware.org/?probe=ea14a764bb) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [85ec601970](https://linux-hardware.org/?probe=85ec601970) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a7c99d7f14](https://linux-hardware.org/?probe=a7c99d7f14) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a37dd040cc](https://linux-hardware.org/?probe=a37dd040cc) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [1ceb70430f](https://linux-hardware.org/?probe=1ceb70430f) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| Shuttle       | FS110                       | [4845946b59](https://linux-hardware.org/?probe=4845946b59) | May 22, 2022 |
| HP            | 18E4                        | [e8bc371de1](https://linux-hardware.org/?probe=e8bc371de1) | May 22, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [aac14b5554](https://linux-hardware.org/?probe=aac14b5554) | May 21, 2022 |
| ASRock        | AB350M-HDV R3.0             | [01fcce62c6](https://linux-hardware.org/?probe=01fcce62c6) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [6763ad45ce](https://linux-hardware.org/?probe=6763ad45ce) | May 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [cedcf3fa98](https://linux-hardware.org/?probe=cedcf3fa98) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [72560a6e0c](https://linux-hardware.org/?probe=72560a6e0c) | May 21, 2022 |
| HP            | 18E4                        | [e567895819](https://linux-hardware.org/?probe=e567895819) | May 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [72a96fc8a3](https://linux-hardware.org/?probe=72a96fc8a3) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Medion        | H81H3-EM2                   | [ba616a92bf](https://linux-hardware.org/?probe=ba616a92bf) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Gigabyte      | Z77X-UP7                    | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| Dell          | 09M8Y8 A01                  | [f4894739f4](https://linux-hardware.org/?probe=f4894739f4) | May 20, 2022 |
| HP            | 8767 A                      | [a1b50431fa](https://linux-hardware.org/?probe=a1b50431fa) | May 19, 2022 |
| MSI           | MPG B550I GAMING EDGE MA... | [407d3e4f43](https://linux-hardware.org/?probe=407d3e4f43) | May 19, 2022 |
| Intel         | ChiefRiver                  | [8e4aca2b1f](https://linux-hardware.org/?probe=8e4aca2b1f) | May 19, 2022 |
| Intel         | ChiefRiver                  | [4d38806404](https://linux-hardware.org/?probe=4d38806404) | May 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6a9166ca20](https://linux-hardware.org/?probe=6a9166ca20) | May 19, 2022 |
| Dell          | 0HY9JP A01                  | [d845952849](https://linux-hardware.org/?probe=d845952849) | May 19, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [39fb6cd4e3](https://linux-hardware.org/?probe=39fb6cd4e3) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| ASUSTek       | PRIME B360M-D               | [6a00f5f597](https://linux-hardware.org/?probe=6a00f5f597) | May 18, 2022 |
| ECS           | GF7050VT-M5                 | [485f780320](https://linux-hardware.org/?probe=485f780320) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [54f3323bd2](https://linux-hardware.org/?probe=54f3323bd2) | May 18, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [eaea352b1a](https://linux-hardware.org/?probe=eaea352b1a) | May 18, 2022 |
| Foxconn       | 2ADA                        | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [1dba88e243](https://linux-hardware.org/?probe=1dba88e243) | May 18, 2022 |
| ASUSTek       | F2A85-M PRO                 | [99e949c3e8](https://linux-hardware.org/?probe=99e949c3e8) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| ASRock        | 970M Pro3                   | [f08826b5b4](https://linux-hardware.org/?probe=f08826b5b4) | May 17, 2022 |
| HP            | 22F8                        | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | PRO H410M-C                 | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| ASUSTek       | M3N78 PRO                   | [246f442b9b](https://linux-hardware.org/?probe=246f442b9b) | May 15, 2022 |
| Gigabyte      | Z690 UD DDR4                | [e2ed8b47c2](https://linux-hardware.org/?probe=e2ed8b47c2) | May 15, 2022 |
| ASRock        | 970 Pro3 R2.0               | [5ad0b4a6c6](https://linux-hardware.org/?probe=5ad0b4a6c6) | May 15, 2022 |
| Acer          | H57M01                      | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [a2fa413622](https://linux-hardware.org/?probe=a2fa413622) | May 15, 2022 |
| ASUSTek       | M3N78 PRO                   | [af5eec886b](https://linux-hardware.org/?probe=af5eec886b) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [021f95ce24](https://linux-hardware.org/?probe=021f95ce24) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ce2f8b28b](https://linux-hardware.org/?probe=9ce2f8b28b) | May 15, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [e819cbe6f7](https://linux-hardware.org/?probe=e819cbe6f7) | May 15, 2022 |
| ASRock        | 970M Pro3                   | [5f67a595f4](https://linux-hardware.org/?probe=5f67a595f4) | May 15, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| MSI           | PRO Z690-A DDR4             | [5ce4d54b58](https://linux-hardware.org/?probe=5ce4d54b58) | May 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [d7f98d5384](https://linux-hardware.org/?probe=d7f98d5384) | May 14, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b061586ff0](https://linux-hardware.org/?probe=b061586ff0) | May 14, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [a292b16ff7](https://linux-hardware.org/?probe=a292b16ff7) | May 14, 2022 |
| ASUSTek       | Z97-P                       | [3fc95850aa](https://linux-hardware.org/?probe=3fc95850aa) | May 14, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [975e7a6b47](https://linux-hardware.org/?probe=975e7a6b47) | May 14, 2022 |
| Acer          | H57M01                      | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Intel         | X99 V1.0                    | [554b088978](https://linux-hardware.org/?probe=554b088978) | May 14, 2022 |
| Acer          | Veriton M670G               | [a583d3a342](https://linux-hardware.org/?probe=a583d3a342) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| MSI           | B550M PRO-VDH               | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Shuttle       | DS10U                       | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Acer          | Aspire X3400                | [9dd76b4599](https://linux-hardware.org/?probe=9dd76b4599) | May 13, 2022 |
| Acer          | Aspire X3400                | [b590b149fc](https://linux-hardware.org/?probe=b590b149fc) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Dell          | 0773VG A02                  | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Shuttle       | FH87                        | [42cb5c0ef7](https://linux-hardware.org/?probe=42cb5c0ef7) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| ASUSTek       | P8H61                       | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| HP            | 0AECh D                     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [578328d0b5](https://linux-hardware.org/?probe=578328d0b5) | May 12, 2022 |
| Unknown       | Unknown                     | [7931f8191f](https://linux-hardware.org/?probe=7931f8191f) | May 11, 2022 |
| Unknown       | Unknown                     | [271a8ba23e](https://linux-hardware.org/?probe=271a8ba23e) | May 11, 2022 |
| MSI           | Z97S SLI Krait Edition      | [861cbb7b6e](https://linux-hardware.org/?probe=861cbb7b6e) | May 11, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [14f5c24c81](https://linux-hardware.org/?probe=14f5c24c81) | May 11, 2022 |
| Dell          | 0WMJ54 A00                  | [393406b0e8](https://linux-hardware.org/?probe=393406b0e8) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Intel         | B75                         | [d2a9132d48](https://linux-hardware.org/?probe=d2a9132d48) | May 11, 2022 |
| ASUSTek       | H61M-K                      | [64f2ed4df2](https://linux-hardware.org/?probe=64f2ed4df2) | May 11, 2022 |
| ASRock        | B550 Steel Legend           | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [74862d462d](https://linux-hardware.org/?probe=74862d462d) | May 10, 2022 |
| Gigabyte      | H97N                        | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ECS           | A68M-C4DL                   | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [7987b700d5](https://linux-hardware.org/?probe=7987b700d5) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b57ce8e7e1](https://linux-hardware.org/?probe=b57ce8e7e1) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b3cac7c464](https://linux-hardware.org/?probe=b3cac7c464) | May 09, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Intel         | H61                         | [3f5d8ae941](https://linux-hardware.org/?probe=3f5d8ae941) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [77145b587d](https://linux-hardware.org/?probe=77145b587d) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [e3f65dec10](https://linux-hardware.org/?probe=e3f65dec10) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [344bc071a2](https://linux-hardware.org/?probe=344bc071a2) | May 09, 2022 |
| HP            | 1998                        | [bb8d501109](https://linux-hardware.org/?probe=bb8d501109) | May 09, 2022 |
| ASUSTek       | P5Q SE/R                    | [c99b0a0683](https://linux-hardware.org/?probe=c99b0a0683) | May 08, 2022 |
| Acer          | Revo RL80                   | [c48857049a](https://linux-hardware.org/?probe=c48857049a) | May 08, 2022 |
| Pegatron      | Eureka3                     | [e383533179](https://linux-hardware.org/?probe=e383533179) | May 08, 2022 |
| Gigabyte      | Z170X-GamingG1              | [28fc5f92bc](https://linux-hardware.org/?probe=28fc5f92bc) | May 08, 2022 |
| HP            | 870C                        | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [acf562b58b](https://linux-hardware.org/?probe=acf562b58b) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [1a3e2da376](https://linux-hardware.org/?probe=1a3e2da376) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| ASUSTek       | PRIME B360M-A               | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | P8B75-M                     | [6371d77b5d](https://linux-hardware.org/?probe=6371d77b5d) | May 07, 2022 |
| Pegatron      | 2AC3                        | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| Dell          | 0WMJ54 A01                  | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Dell          | 00V62H A00                  | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| Medion        | B460H6-EM                   | [e2abcd94ce](https://linux-hardware.org/?probe=e2abcd94ce) | May 06, 2022 |
| Lenovo        | 0B98401 WIN                 | [b080a2bae5](https://linux-hardware.org/?probe=b080a2bae5) | May 06, 2022 |
| HP            | 1495                        | [4b63b733be](https://linux-hardware.org/?probe=4b63b733be) | May 06, 2022 |
| Lenovo        | NO DPK                      | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Google        | Panther                     | [4b7366ed94](https://linux-hardware.org/?probe=4b7366ed94) | May 06, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [61c86467ba](https://linux-hardware.org/?probe=61c86467ba) | May 06, 2022 |
| MSI           | B550M PRO-VDH               | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| Supermicro    | X8ST3                       | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| ASUSTek       | Z97-K                       | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| MSI           | 770-C45                     | [0e9179888b](https://linux-hardware.org/?probe=0e9179888b) | May 05, 2022 |
| Lenovo        | NO DPK                      | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| MSI           | Z390-A PRO                  | [145317db95](https://linux-hardware.org/?probe=145317db95) | May 05, 2022 |
| MSI           | H55M-E23                    | [d42084b294](https://linux-hardware.org/?probe=d42084b294) | May 04, 2022 |
| ASUSTek       | Maximus VI HERO             | [540a55671c](https://linux-hardware.org/?probe=540a55671c) | May 04, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d5cd65ba5b](https://linux-hardware.org/?probe=d5cd65ba5b) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | [180a5d086f](https://linux-hardware.org/?probe=180a5d086f) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | [f47683cd76](https://linux-hardware.org/?probe=f47683cd76) | May 04, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [4ce66ff579](https://linux-hardware.org/?probe=4ce66ff579) | May 04, 2022 |
| Gigabyte      | H110M-S2-CF                 | [156de9d4de](https://linux-hardware.org/?probe=156de9d4de) | May 04, 2022 |
| ASUSTek       | Z97M-PLUS                   | [c2ab1a3ec2](https://linux-hardware.org/?probe=c2ab1a3ec2) | May 04, 2022 |
| Gigabyte      | B75M-HD3                    | [7dc76bf420](https://linux-hardware.org/?probe=7dc76bf420) | May 04, 2022 |
| ASUSTek       | B150M PRO GAMING            | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| Dell          | 0P301D A02                  | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| Acer          | FX58M                       | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| Shuttle       | FG41 V20                    | [fd07bdf7b5](https://linux-hardware.org/?probe=fd07bdf7b5) | May 02, 2022 |
| Dell          | 0M017G A00                  | [93884340db](https://linux-hardware.org/?probe=93884340db) | May 02, 2022 |
| Alienware     | 07JNH0 A02                  | [d39a57aed6](https://linux-hardware.org/?probe=d39a57aed6) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [bbbfaa9157](https://linux-hardware.org/?probe=bbbfaa9157) | May 02, 2022 |
| Dell          | 09M8Y8 A01                  | [301694185a](https://linux-hardware.org/?probe=301694185a) | May 02, 2022 |
| Dell          | 0HHV7N A00                  | [7636489d8e](https://linux-hardware.org/?probe=7636489d8e) | May 01, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [965ebad5cb](https://linux-hardware.org/?probe=965ebad5cb) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| ASUSTek       | H61M-K                      | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| ASUSTek       | P5B                         | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Positivo      | POS-ECIG41BSA               | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| Medion        | MS-7616                     | [f3572ea9a5](https://linux-hardware.org/?probe=f3572ea9a5) | Apr 30, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [463e99eb8c](https://linux-hardware.org/?probe=463e99eb8c) | Apr 30, 2022 |
| MSI           | X570-A PRO                  | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | [f62d8963d7](https://linux-hardware.org/?probe=f62d8963d7) | Apr 30, 2022 |
| ASRock        | B75M-ITX                    | [dbc851e0d3](https://linux-hardware.org/?probe=dbc851e0d3) | Apr 30, 2022 |
| HP            | 3396                        | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | [7797c23169](https://linux-hardware.org/?probe=7797c23169) | Apr 30, 2022 |
| MSI           | A320M PRO-E                 | [655905bb3b](https://linux-hardware.org/?probe=655905bb3b) | Apr 29, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [fe522bdf2e](https://linux-hardware.org/?probe=fe522bdf2e) | Apr 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [686f4acac4](https://linux-hardware.org/?probe=686f4acac4) | Apr 29, 2022 |
| ASUSTek       | Rampage IV EXTREME          | [111d072676](https://linux-hardware.org/?probe=111d072676) | Apr 29, 2022 |
| Dell          | 07WP95 A02                  | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| Pepper Job... | GLK-UC2X                    | [28495f32bd](https://linux-hardware.org/?probe=28495f32bd) | Apr 29, 2022 |
| Alienware     | 07W25T A00                  | [b989838f70](https://linux-hardware.org/?probe=b989838f70) | Apr 29, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [27df4d83ea](https://linux-hardware.org/?probe=27df4d83ea) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| MSI           | A78M-E35                    | [8f9bf75a08](https://linux-hardware.org/?probe=8f9bf75a08) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d291472a69](https://linux-hardware.org/?probe=d291472a69) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | [773f69d63b](https://linux-hardware.org/?probe=773f69d63b) | Apr 28, 2022 |
| ASUSTek       | M5A78L LE                   | [96739891ab](https://linux-hardware.org/?probe=96739891ab) | Apr 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | [2943b21899](https://linux-hardware.org/?probe=2943b21899) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c4f91167bb](https://linux-hardware.org/?probe=c4f91167bb) | Apr 27, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| ASUSTek       | H110M-A/M.2                 | [4c6852d631](https://linux-hardware.org/?probe=4c6852d631) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f06ce3d416](https://linux-hardware.org/?probe=f06ce3d416) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a3f49d1a04](https://linux-hardware.org/?probe=a3f49d1a04) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b47f678ce9](https://linux-hardware.org/?probe=b47f678ce9) | Apr 27, 2022 |
| ASRock        | H61M-VG4                    | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [3c53a0e59d](https://linux-hardware.org/?probe=3c53a0e59d) | Apr 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [f09766a481](https://linux-hardware.org/?probe=f09766a481) | Apr 27, 2022 |
| HP            | 22F8                        | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [56da721176](https://linux-hardware.org/?probe=56da721176) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [1619af58d4](https://linux-hardware.org/?probe=1619af58d4) | Apr 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [3c6aace75c](https://linux-hardware.org/?probe=3c6aace75c) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Dell          | 0WR7PY A03                  | [4ac0a4dff1](https://linux-hardware.org/?probe=4ac0a4dff1) | Apr 26, 2022 |
| Dell          | 0VNM11 A00                  | [6aae7c23ad](https://linux-hardware.org/?probe=6aae7c23ad) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Biostar       | J3160NH                     | [8ffd3a1aa4](https://linux-hardware.org/?probe=8ffd3a1aa4) | Apr 26, 2022 |
| MSI           | Z68A-GD80                   | [fedca9082a](https://linux-hardware.org/?probe=fedca9082a) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| Gigabyte      | P55M-UD2                    | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | [6564561a75](https://linux-hardware.org/?probe=6564561a75) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| Acer          | FX58M                       | [3074ddb372](https://linux-hardware.org/?probe=3074ddb372) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | [af6b49b2a5](https://linux-hardware.org/?probe=af6b49b2a5) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| ASUSTek       | F2A85-M PRO                 | [e0298dd8f0](https://linux-hardware.org/?probe=e0298dd8f0) | Apr 24, 2022 |
| HP            | 21EF                        | [9e37979ea3](https://linux-hardware.org/?probe=9e37979ea3) | Apr 23, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [929f99800a](https://linux-hardware.org/?probe=929f99800a) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [3b01c4a4a5](https://linux-hardware.org/?probe=3b01c4a4a5) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| HP            | 22F8                        | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [8e31efa5fa](https://linux-hardware.org/?probe=8e31efa5fa) | Apr 23, 2022 |
| Dell          | 088DT1 A01                  | [9e72ff0940](https://linux-hardware.org/?probe=9e72ff0940) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [d35c4838f2](https://linux-hardware.org/?probe=d35c4838f2) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [61e0546ed7](https://linux-hardware.org/?probe=61e0546ed7) | Apr 22, 2022 |
| ASRock        | Z370 Pro4-IB                | [c0c51e4d53](https://linux-hardware.org/?probe=c0c51e4d53) | Apr 22, 2022 |
| Dell          | 0HD5W2 A00                  | [ddfd89e9dc](https://linux-hardware.org/?probe=ddfd89e9dc) | Apr 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [a76e953825](https://linux-hardware.org/?probe=a76e953825) | Apr 22, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| HP            | 8054                        | [f9ec7b0896](https://linux-hardware.org/?probe=f9ec7b0896) | Apr 21, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| Gigabyte      | B450M GAMING                | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| MSI           | Z97 GAMING 5                | [a6bd59cad3](https://linux-hardware.org/?probe=a6bd59cad3) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | [350979cb0a](https://linux-hardware.org/?probe=350979cb0a) | Apr 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [a0325fabb2](https://linux-hardware.org/?probe=a0325fabb2) | Apr 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [d775ab24fe](https://linux-hardware.org/?probe=d775ab24fe) | Apr 17, 2022 |
| MSI           | 970 GAMING                  | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Gigabyte      | B75M-D3P                    | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| HP            | 1495                        | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HP            | 1589                        | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| Unknown       | T3 MRD                      | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| Unknown       | T3 MRD                      | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASRockRack    | X470D4U2/1N1                | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| MSI           | Z490-A PRO                  | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| MSI           | C236A WORKSTATION           | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| Intel         | H61                         | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| Huanan        | X99 F8D V2.2                | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Gigabyte      | EP31-DS3L                   | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| MSI           | MS-7235                     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.15.0-27-generic           | 101      | 14.49%  |
| 5.15.0-40-generic           | 87       | 12.48%  |
| 5.15.0-41-generic           | 85       | 12.2%   |
| 5.15.0-25-generic           | 78       | 11.19%  |
| 5.15.0-33-generic           | 61       | 8.75%   |
| 5.15.0-30-generic           | 51       | 7.32%   |
| 5.15.0-39-generic           | 45       | 6.46%   |
| 5.15.0-35-generic           | 44       | 6.31%   |
| 5.15.0-37-generic           | 42       | 6.03%   |
| 5.15.0-43-generic           | 19       | 2.73%   |
| 5.15.0-23-generic           | 12       | 1.72%   |
| 5.15.0-18-generic           | 9        | 1.29%   |
| 5.15.0-32-generic           | 7        | 1%      |
| 5.13.0-19-generic           | 7        | 1%      |
| 5.15.0-28-generic           | 4        | 0.57%   |
| 5.15.0-22-generic           | 3        | 0.43%   |
| 5.18.0-051800-generic       | 2        | 0.29%   |
| 5.17.0-1013-oem             | 2        | 0.29%   |
| 5.17.0-051700-generic       | 2        | 0.29%   |
| 5.15.13-051513-generic      | 2        | 0.29%   |
| 5.18.8-051808-generic       | 1        | 0.14%   |
| 5.18.3-051803-generic       | 1        | 0.14%   |
| 5.18.13-051813-generic      | 1        | 0.14%   |
| 5.18.10-051810-generic      | 1        | 0.14%   |
| 5.18.1-tkg-pds              | 1        | 0.14%   |
| 5.18.0-14.2-liquorix-amd64  | 1        | 0.14%   |
| 5.17.9-xanmod1-x64v2        | 1        | 0.14%   |
| 5.17.9-051709-generic       | 1        | 0.14%   |
| 5.17.7-051707-generic       | 1        | 0.14%   |
| 5.17.6-051706-generic       | 1        | 0.14%   |
| 5.17.5-051705-generic       | 1        | 0.14%   |
| 5.17.4-051704-generic       | 1        | 0.14%   |
| 5.17.2-051702-generic       | 1        | 0.14%   |
| 5.17.14-void31-nomac-znver3 | 1        | 0.14%   |
| 5.17.1-051701-generic       | 1        | 0.14%   |
| 5.17.0-void25-nomac-znver3  | 1        | 0.14%   |
| 5.17.0-tkg-cacule           | 1        | 0.14%   |
| 5.17.0-4.1-liquorix-amd64   | 1        | 0.14%   |
| 5.17.0-1014-oem             | 1        | 0.14%   |
| 5.17.0-1006-oem             | 1        | 0.14%   |
| 5.17.0-1003-oem             | 1        | 0.14%   |
| 5.16.0-051600-generic       | 1        | 0.14%   |
| 5.15.0-40-lowlatency        | 1        | 0.14%   |
| 5.15.0-37-lowlatency        | 1        | 0.14%   |
| 5.15.0-30-lowlatency        | 1        | 0.14%   |
| 5.15.0-27-lowlatency        | 1        | 0.14%   |
| 5.15.0-17-generic           | 1        | 0.14%   |
| 5.15.0-10037-tuxedo         | 1        | 0.14%   |
| 5.15.0-051500rc7-generic    | 1        | 0.14%   |
| 5.13.0-48-generic           | 1        | 0.14%   |
| 5.13.0-40-generic           | 1        | 0.14%   |
| 5.13.0-28-generic           | 1        | 0.14%   |
| 5.13.0-21-generic           | 1        | 0.14%   |
| 5.13.0-20-generic           | 1        | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 626      | 93.71%  |
| 5.13.0  | 12       | 1.8%    |
| 5.17.0  | 10       | 1.5%    |
| 5.18.0  | 3        | 0.45%   |
| 5.17.9  | 2        | 0.3%    |
| 5.15.13 | 2        | 0.3%    |
| 5.18.8  | 1        | 0.15%   |
| 5.18.3  | 1        | 0.15%   |
| 5.18.13 | 1        | 0.15%   |
| 5.18.10 | 1        | 0.15%   |
| 5.18.1  | 1        | 0.15%   |
| 5.17.7  | 1        | 0.15%   |
| 5.17.6  | 1        | 0.15%   |
| 5.17.5  | 1        | 0.15%   |
| 5.17.4  | 1        | 0.15%   |
| 5.17.2  | 1        | 0.15%   |
| 5.17.14 | 1        | 0.15%   |
| 5.17.1  | 1        | 0.15%   |
| 5.16.0  | 1        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 628      | 94.15%  |
| 5.17    | 18       | 2.7%    |
| 5.13    | 12       | 1.8%    |
| 5.18    | 8        | 1.2%    |
| 5.16    | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 664      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 614      | 92.47%  |
| Unknown         | 30       | 4.52%   |
| X-Cinnamon      | 10       | 1.51%   |
| Unity           | 5        | 0.75%   |
| GNOME Classic   | 4        | 0.6%    |
| GNOME Flashback | 1        | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 359      | 53.58%  |
| X11     | 282      | 42.09%  |
| Tty     | 17       | 2.54%   |
| Unknown | 12       | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 589      | 88.44%  |
| Unknown | 58       | 8.71%   |
| LightDM | 11       | 1.65%   |
| GDM     | 4        | 0.6%    |
| SLiM    | 2        | 0.3%    |
| SDDM    | 2        | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 283      | 42.62%  |
| de_DE   | 63       | 9.49%   |
| fr_FR   | 42       | 6.33%   |
| en_GB   | 40       | 6.02%   |
| ru_RU   | 24       | 3.61%   |
| pt_BR   | 24       | 3.61%   |
| es_ES   | 22       | 3.31%   |
| en_CA   | 22       | 3.31%   |
| it_IT   | 13       | 1.96%   |
| en_AU   | 13       | 1.96%   |
| cs_CZ   | 12       | 1.81%   |
| pl_PL   | 10       | 1.51%   |
| es_AR   | 8        | 1.2%    |
| en_IN   | 8        | 1.2%    |
| pt_PT   | 6        | 0.9%    |
| ja_JP   | 6        | 0.9%    |
| C       | 5        | 0.75%   |
| zh_CN   | 4        | 0.6%    |
| nl_NL   | 4        | 0.6%    |
| es_MX   | 4        | 0.6%    |
| en_PH   | 4        | 0.6%    |
| zh_TW   | 3        | 0.45%   |
| tr_TR   | 3        | 0.45%   |
| sv_SE   | 3        | 0.45%   |
| nl_BE   | 3        | 0.45%   |
| en_ZA   | 3        | 0.45%   |
| en_NZ   | 3        | 0.45%   |
| el_GR   | 3        | 0.45%   |
| de_AT   | 3        | 0.45%   |
| sk_SK   | 2        | 0.3%    |
| fi_FI   | 2        | 0.3%    |
| es_CL   | 2        | 0.3%    |
| de_CH   | 2        | 0.3%    |
| th_TH   | 1        | 0.15%   |
| ro_RO   | 1        | 0.15%   |
| nb_NO   | 1        | 0.15%   |
| ko_KR   | 1        | 0.15%   |
| hu_HU   | 1        | 0.15%   |
| fr_CA   | 1        | 0.15%   |
| fr_BE   | 1        | 0.15%   |
| es_PE   | 1        | 0.15%   |
| es_NI   | 1        | 0.15%   |
| es_EC   | 1        | 0.15%   |
| es_CU   | 1        | 0.15%   |
| es_CR   | 1        | 0.15%   |
| en_ZW   | 1        | 0.15%   |
| de_BE   | 1        | 0.15%   |
| Unknown | 1        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 475      | 71%     |
| EFI  | 194      | 29%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 598      | 89.92%  |
| Zfs     | 22       | 3.31%   |
| Overlay | 21       | 3.16%   |
| Btrfs   | 15       | 2.26%   |
| Xfs     | 7        | 1.05%   |
| Ext2    | 1        | 0.15%   |
| Unknown | 1        | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 454      | 68.17%  |
| GPT     | 198      | 29.73%  |
| MBR     | 14       | 2.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 545      | 81.22%  |
| Yes       | 126      | 18.78%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 374      | 55.9%   |
| Yes       | 295      | 44.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 165      | 24.85%  |
| MSI                 | 109      | 16.42%  |
| Gigabyte Technology | 108      | 16.27%  |
| Dell                | 61       | 9.19%   |
| ASRock              | 41       | 6.17%   |
| Hewlett-Packard     | 40       | 6.02%   |
| Lenovo              | 20       | 3.01%   |
| Intel               | 20       | 3.01%   |
| Acer                | 18       | 2.71%   |
| Unknown             | 11       | 1.66%   |
| Shuttle             | 8        | 1.2%    |
| Pegatron            | 6        | 0.9%    |
| Medion              | 6        | 0.9%    |
| Fujitsu             | 6        | 0.9%    |
| ECS                 | 5        | 0.75%   |
| Apple               | 5        | 0.75%   |
| Alienware           | 5        | 0.75%   |
| Huanan              | 4        | 0.6%    |
| Foxconn             | 4        | 0.6%    |
| Supermicro          | 3        | 0.45%   |
| Biostar             | 3        | 0.45%   |
| ASRockRack          | 2        | 0.3%    |
| YANYU               | 1        | 0.15%   |
| XDO.AI              | 1        | 0.15%   |
| QIYIDA              | 1        | 0.15%   |
| Positivo            | 1        | 0.15%   |
| Pepper Jobs         | 1        | 0.15%   |
| PCWare              | 1        | 0.15%   |
| PCPartner           | 1        | 0.15%   |
| Packard Bell        | 1        | 0.15%   |
| Nvidia              | 1        | 0.15%   |
| Maxtang             | 1        | 0.15%   |
| Le Cube 1           | 1        | 0.15%   |
| ITI LIMITED         | 1        | 0.15%   |
| Google              | 1        | 0.15%   |
| ABIT                | 1        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 21       | 3.16%   |
| MSI MS-7721                              | 12       | 1.81%   |
| Unknown                                  | 12       | 1.81%   |
| MSI MS-7C52                              | 5        | 0.75%   |
| Dell OptiPlex 7010                       | 5        | 0.75%   |
| ASUS PRIME A320M-K                       | 5        | 0.75%   |
| MSI MS-7C02                              | 4        | 0.6%    |
| Intel H61                                | 4        | 0.6%    |
| ASUS TUF Gaming X570-PLUS                | 4        | 0.6%    |
| Apple MacPro5,1                          | 4        | 0.6%    |
| MSI MS-7D54                              | 3        | 0.45%   |
| MSI MS-7C92                              | 3        | 0.45%   |
| MSI MS-7C37                              | 3        | 0.45%   |
| MSI MS-7C35                              | 3        | 0.45%   |
| MSI MS-7B84                              | 3        | 0.45%   |
| MSI MS-7B79                              | 3        | 0.45%   |
| MSI MS-7A38                              | 3        | 0.45%   |
| MSI MS-7817                              | 3        | 0.45%   |
| HP EliteDesk 800 G1 SFF                  | 3        | 0.45%   |
| Dell OptiPlex 9020                       | 3        | 0.45%   |
| Dell OptiPlex 790                        | 3        | 0.45%   |
| Dell OptiPlex 7040                       | 3        | 0.45%   |
| Dell OptiPlex 3010                       | 3        | 0.45%   |
| ASUS ROG STRIX B550-F GAMING             | 3        | 0.45%   |
| ASUS PRIME B450M-A                       | 3        | 0.45%   |
| Shuttle DS10U                            | 2        | 0.3%    |
| MSI MS-7D25                              | 2        | 0.3%    |
| MSI MS-7D16                              | 2        | 0.3%    |
| MSI MS-7D09                              | 2        | 0.3%    |
| MSI MS-7C95                              | 2        | 0.3%    |
| MSI MS-7C91                              | 2        | 0.3%    |
| MSI MS-7C51                              | 2        | 0.3%    |
| MSI MS-7B17                              | 2        | 0.3%    |
| MSI MS-7A70                              | 2        | 0.3%    |
| MSI MS-7758                              | 2        | 0.3%    |
| MSI MS-7693                              | 2        | 0.3%    |
| MSI MS-7636                              | 2        | 0.3%    |
| HP Z440 Workstation                      | 2        | 0.3%    |
| HP Z400 Workstation                      | 2        | 0.3%    |
| HP ProDesk 600 G1 SFF                    | 2        | 0.3%    |
| HP EliteDesk 800 G6 Small Form Factor PC | 2        | 0.3%    |
| HP EliteDesk 800 G2 SFF                  | 2        | 0.3%    |
| HP Compaq Elite 8300 CMT                 | 2        | 0.3%    |
| HP Compaq 8200 Elite SFF PC              | 2        | 0.3%    |
| Gigabyte Z97X-Gaming 3                   | 2        | 0.3%    |
| Gigabyte Z87X-UD3H                       | 2        | 0.3%    |
| Gigabyte Z77X-UD3H                       | 2        | 0.3%    |
| Gigabyte Z390 M GAMING                   | 2        | 0.3%    |
| Gigabyte X99-UD4-CF                      | 2        | 0.3%    |
| Gigabyte X570S AORUS MASTER              | 2        | 0.3%    |
| Gigabyte X570 I AORUS PRO WIFI           | 2        | 0.3%    |
| Gigabyte X570 AORUS MASTER               | 2        | 0.3%    |
| Gigabyte X570 AORUS ELITE                | 2        | 0.3%    |
| Gigabyte PH67A-D3-B3                     | 2        | 0.3%    |
| Gigabyte F2A68HM-H                       | 2        | 0.3%    |
| Gigabyte F2A55M-HD2                      | 2        | 0.3%    |
| Fujitsu CELSIUS R570-2                   | 2        | 0.3%    |
| Dell XPS 8940                            | 2        | 0.3%    |
| Dell Precision WorkStation 690           | 2        | 0.3%    |
| Dell Precision T3610                     | 2        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 34       | 5.12%   |
| ASUS PRIME           | 25       | 3.77%   |
| ASUS All             | 21       | 3.16%   |
| ASUS ROG             | 20       | 3.01%   |
| ASUS TUF             | 13       | 1.96%   |
| MSI MS-7721          | 12       | 1.81%   |
| Lenovo ThinkCentre   | 12       | 1.81%   |
| Acer Aspire          | 12       | 1.81%   |
| Unknown              | 12       | 1.81%   |
| Dell Precision       | 11       | 1.66%   |
| HP Compaq            | 10       | 1.51%   |
| HP EliteDesk         | 8        | 1.2%    |
| Gigabyte X570        | 8        | 1.2%    |
| Dell Inspiron        | 6        | 0.9%    |
| ASUS Pro             | 6        | 0.9%    |
| ASUS CROSSHAIR       | 6        | 0.9%    |
| MSI MS-7C52          | 5        | 0.75%   |
| MSI MS-7C02          | 4        | 0.6%    |
| Intel H61            | 4        | 0.6%    |
| HP ProDesk           | 4        | 0.6%    |
| Gigabyte Z690        | 4        | 0.6%    |
| Gigabyte Z390        | 4        | 0.6%    |
| Apple MacPro5        | 4        | 0.6%    |
| Acer Veriton         | 4        | 0.6%    |
| MSI MS-7D54          | 3        | 0.45%   |
| MSI MS-7C92          | 3        | 0.45%   |
| MSI MS-7C37          | 3        | 0.45%   |
| MSI MS-7C35          | 3        | 0.45%   |
| MSI MS-7B84          | 3        | 0.45%   |
| MSI MS-7B79          | 3        | 0.45%   |
| MSI MS-7A38          | 3        | 0.45%   |
| MSI MS-7817          | 3        | 0.45%   |
| Gigabyte Z97X-Gaming | 3        | 0.45%   |
| Gigabyte X570S       | 3        | 0.45%   |
| Gigabyte H61M-DS2    | 3        | 0.45%   |
| Gigabyte B450M       | 3        | 0.45%   |
| Fujitsu ESPRIMO      | 3        | 0.45%   |
| Dell XPS             | 3        | 0.45%   |
| ASUS P8H61-M         | 3        | 0.45%   |
| ASUS P8B75-M         | 3        | 0.45%   |
| ASUS M5A99X          | 3        | 0.45%   |
| ASUS M5A97           | 3        | 0.45%   |
| ASRock 970           | 3        | 0.45%   |
| Shuttle DS10U        | 2        | 0.3%    |
| MSI MS-7D25          | 2        | 0.3%    |
| MSI MS-7D16          | 2        | 0.3%    |
| MSI MS-7D09          | 2        | 0.3%    |
| MSI MS-7C95          | 2        | 0.3%    |
| MSI MS-7C91          | 2        | 0.3%    |
| MSI MS-7C51          | 2        | 0.3%    |
| MSI MS-7B17          | 2        | 0.3%    |
| MSI MS-7A70          | 2        | 0.3%    |
| MSI MS-7758          | 2        | 0.3%    |
| MSI MS-7693          | 2        | 0.3%    |
| MSI MS-7636          | 2        | 0.3%    |
| Lenovo ThinkStation  | 2        | 0.3%    |
| Lenovo IdeaCentre    | 2        | 0.3%    |
| Intel DH67BL         | 2        | 0.3%    |
| HP Z440              | 2        | 0.3%    |
| HP Z400              | 2        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 67       | 10.09%  |
| 2012    | 61       | 9.19%   |
| 2019    | 57       | 8.58%   |
| 2014    | 56       | 8.43%   |
| 2013    | 56       | 8.43%   |
| 2018    | 52       | 7.83%   |
| 2020    | 51       | 7.68%   |
| 2010    | 46       | 6.93%   |
| 2011    | 41       | 6.17%   |
| 2017    | 37       | 5.57%   |
| 2015    | 35       | 5.27%   |
| 2016    | 27       | 4.07%   |
| 2009    | 23       | 3.46%   |
| 2008    | 23       | 3.46%   |
| 2022    | 15       | 2.26%   |
| 2007    | 9        | 1.36%   |
| 2006    | 5        | 0.75%   |
| 2005    | 2        | 0.3%    |
| Unknown | 1        | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 664      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 644      | 96.84%  |
| Enabled  | 21       | 3.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 663      | 99.85%  |
| Yes  | 1        | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 180      | 26.99%  |
| 4.01-8.0        | 118      | 17.69%  |
| 32.01-64.0      | 117      | 17.54%  |
| 8.01-16.0       | 106      | 15.89%  |
| 3.01-4.0        | 75       | 11.24%  |
| 64.01-256.0     | 42       | 6.3%    |
| 24.01-32.0      | 16       | 2.4%    |
| 1.01-2.0        | 5        | 0.75%   |
| More than 256.0 | 4        | 0.6%    |
| 2.01-3.0        | 4        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 241      | 35.18%  |
| 2.01-3.0   | 199      | 29.05%  |
| 3.01-4.0   | 97       | 14.16%  |
| 4.01-8.0   | 96       | 14.01%  |
| 8.01-16.0  | 31       | 4.53%   |
| 0.51-1.0   | 9        | 1.31%   |
| 16.01-24.0 | 5        | 0.73%   |
| 0.01-0.5   | 3        | 0.44%   |
| 32.01-64.0 | 2        | 0.29%   |
| 24.01-32.0 | 2        | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 232      | 34.42%  |
| 2      | 200      | 29.67%  |
| 3      | 109      | 16.17%  |
| 4      | 55       | 8.16%   |
| 5      | 30       | 4.45%   |
| 6      | 17       | 2.52%   |
| 8      | 8        | 1.19%   |
| 0      | 8        | 1.19%   |
| 7      | 7        | 1.04%   |
| 11     | 2        | 0.3%    |
| 9      | 2        | 0.3%    |
| 20     | 1        | 0.15%   |
| 13     | 1        | 0.15%   |
| 12     | 1        | 0.15%   |
| 10     | 1        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 401      | 60.21%  |
| Yes       | 265      | 39.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 657      | 98.8%   |
| No        | 8        | 1.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 354      | 53.15%  |
| Yes       | 312      | 46.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 438      | 65.57%  |
| Yes       | 230      | 34.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 134      | 20.18%  |
| Germany             | 70       | 10.54%  |
| Russia              | 48       | 7.23%   |
| France              | 44       | 6.63%   |
| UK                  | 39       | 5.87%   |
| Brazil              | 38       | 5.72%   |
| Canada              | 27       | 4.07%   |
| Spain               | 22       | 3.31%   |
| Poland              | 15       | 2.26%   |
| Italy               | 15       | 2.26%   |
| Australia           | 15       | 2.26%   |
| Argentina           | 15       | 2.26%   |
| Czechia             | 13       | 1.96%   |
| Switzerland         | 10       | 1.51%   |
| Netherlands         | 10       | 1.51%   |
| Finland             | 10       | 1.51%   |
| Japan               | 9        | 1.36%   |
| India               | 8        | 1.2%    |
| Belgium             | 8        | 1.2%    |
| Austria             | 7        | 1.05%   |
| Turkey              | 6        | 0.9%    |
| Sweden              | 6        | 0.9%    |
| Portugal            | 6        | 0.9%    |
| Romania             | 5        | 0.75%   |
| Norway              | 5        | 0.75%   |
| Mexico              | 5        | 0.75%   |
| South Africa        | 4        | 0.6%    |
| Philippines         | 4        | 0.6%    |
| New Zealand         | 4        | 0.6%    |
| China               | 4        | 0.6%    |
| Bulgaria            | 4        | 0.6%    |
| Taiwan              | 3        | 0.45%   |
| South Korea         | 3        | 0.45%   |
| Saudi Arabia        | 3        | 0.45%   |
| Peru                | 3        | 0.45%   |
| Hungary             | 3        | 0.45%   |
| Greece              | 3        | 0.45%   |
| Slovenia            | 2        | 0.3%    |
| Slovakia            | 2        | 0.3%    |
| Serbia              | 2        | 0.3%    |
| Réunion            | 2        | 0.3%    |
| Pakistan            | 2        | 0.3%    |
| Malaysia            | 2        | 0.3%    |
| Denmark             | 2        | 0.3%    |
| Chile               | 2        | 0.3%    |
| Ukraine             | 1        | 0.15%   |
| UAE                 | 1        | 0.15%   |
| Trinidad and Tobago | 1        | 0.15%   |
| Thailand            | 1        | 0.15%   |
| Nicaragua           | 1        | 0.15%   |
| Myanmar             | 1        | 0.15%   |
| Morocco             | 1        | 0.15%   |
| Lithuania           | 1        | 0.15%   |
| Latvia              | 1        | 0.15%   |
| Ivory Coast         | 1        | 0.15%   |
| Iran                | 1        | 0.15%   |
| Indonesia           | 1        | 0.15%   |
| Estonia             | 1        | 0.15%   |
| Egypt               | 1        | 0.15%   |
| Ecuador             | 1        | 0.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Cheboksary       | 23       | 3.45%   |
| Sao Paulo        | 8        | 1.2%    |
| Sydney           | 7        | 1.05%   |
| Prague           | 6        | 0.9%    |
| Helsinki         | 6        | 0.9%    |
| Paris            | 5        | 0.75%   |
| Madrid           | 5        | 0.75%   |
| Jacksonville     | 5        | 0.75%   |
| Debica           | 5        | 0.75%   |
| Vienna           | 4        | 0.6%    |
| St Petersburg    | 4        | 0.6%    |
| San Jose         | 4        | 0.6%    |
| Moscow           | 4        | 0.6%    |
| Manchester       | 4        | 0.6%    |
| Istanbul         | 4        | 0.6%    |
| Hamburg          | 4        | 0.6%    |
| Guarulhos        | 4        | 0.6%    |
| Dallas           | 4        | 0.6%    |
| Brisbane         | 4        | 0.6%    |
| Berlin           | 4        | 0.6%    |
| Zurich           | 3        | 0.45%   |
| Santa Clara      | 3        | 0.45%   |
| Osaka            | 3        | 0.45%   |
| Novosibirsk      | 3        | 0.45%   |
| London           | 3        | 0.45%   |
| Houston          | 3        | 0.45%   |
| Buenos Aires     | 3        | 0.45%   |
| Bucharest        | 3        | 0.45%   |
| Barcelona        | 3        | 0.45%   |
| Auckland         | 3        | 0.45%   |
| Amsterdam        | 3        | 0.45%   |
| Ypsilanti        | 2        | 0.3%    |
| Wiesbaden        | 2        | 0.3%    |
| Warsaw           | 2        | 0.3%    |
| Volta Redonda    | 2        | 0.3%    |
| Vancouver        | 2        | 0.3%    |
| Toronto          | 2        | 0.3%    |
| Taipei           | 2        | 0.3%    |
| Stuttgart        | 2        | 0.3%    |
| Seattle          | 2        | 0.3%    |
| Santiago         | 2        | 0.3%    |
| Saarlouis        | 2        | 0.3%    |
| Roubaix          | 2        | 0.3%    |
| Rosario          | 2        | 0.3%    |
| Rome             | 2        | 0.3%    |
| Rochester        | 2        | 0.3%    |
| Roche-la-Moliere | 2        | 0.3%    |
| Pretoria         | 2        | 0.3%    |
| Portland         | 2        | 0.3%    |
| Ottawa           | 2        | 0.3%    |
| Ostrava          | 2        | 0.3%    |
| Osasco           | 2        | 0.3%    |
| Orlando          | 2        | 0.3%    |
| Niederhaslach    | 2        | 0.3%    |
| Nesttun          | 2        | 0.3%    |
| Munich           | 2        | 0.3%    |
| Melbourne        | 2        | 0.3%    |
| Los Angeles      | 2        | 0.3%    |
| Lima             | 2        | 0.3%    |
| Leipzig          | 2        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 240      | 358    | 19.54%  |
| WDC                          | 224      | 392    | 18.24%  |
| Samsung Electronics          | 174      | 270    | 14.17%  |
| Kingston                     | 88       | 109    | 7.17%   |
| Toshiba                      | 82       | 115    | 6.68%   |
| SanDisk                      | 54       | 74     | 4.4%    |
| Crucial                      | 54       | 66     | 4.4%    |
| Hitachi                      | 33       | 37     | 2.69%   |
| Phison                       | 16       | 23     | 1.3%    |
| SK hynix                     | 14       | 16     | 1.14%   |
| A-DATA Technology            | 14       | 16     | 1.14%   |
| HGST                         | 13       | 17     | 1.06%   |
| OCZ                          | 12       | 22     | 0.98%   |
| China                        | 12       | 14     | 0.98%   |
| PNY                          | 11       | 14     | 0.9%    |
| Intel                        | 11       | 12     | 0.9%    |
| Intenso                      | 10       | 10     | 0.81%   |
| Unknown                      | 9        | 15     | 0.73%   |
| Silicon Motion               | 9        | 10     | 0.73%   |
| Corsair                      | 7        | 7      | 0.57%   |
| Transcend                    | 6        | 6      | 0.49%   |
| SPCC                         | 6        | 6      | 0.49%   |
| Micron/Crucial Technology    | 6        | 10     | 0.49%   |
| Micron Technology            | 6        | 8      | 0.49%   |
| Lexar                        | 6        | 6      | 0.49%   |
| Gigabyte Technology          | 6        | 7      | 0.49%   |
| Team                         | 5        | 9      | 0.41%   |
| Maxtor                       | 5        | 6      | 0.41%   |
| Unknown                      | 5        | 5      | 0.41%   |
| XPG                          | 4        | 5      | 0.33%   |
| Realtek Semiconductor        | 4        | 4      | 0.33%   |
| Netac                        | 4        | 4      | 0.33%   |
| KIOXIA                       | 4        | 5      | 0.33%   |
| JMicron Technology           | 4        | 4      | 0.33%   |
| WALRAM                       | 3        | 3      | 0.24%   |
| Dogfish                      | 3        | 4      | 0.24%   |
| SABRENT                      | 2        | 3      | 0.16%   |
| Plextor                      | 2        | 2      | 0.16%   |
| Leven                        | 2        | 2      | 0.16%   |
| KingFast                     | 2        | 2      | 0.16%   |
| KingDian                     | 2        | 2      | 0.16%   |
| HGST HTS                     | 2        | 2      | 0.16%   |
| GOODRAM                      | 2        | 3      | 0.16%   |
| FORESEE                      | 2        | 2      | 0.16%   |
| ASMT                         | 2        | 3      | 0.16%   |
| Apple                        | 2        | 2      | 0.16%   |
| Apacer                       | 2        | 2      | 0.16%   |
| Zheino                       | 1        | 1      | 0.08%   |
| WD MediaMax                  | 1        | 1      | 0.08%   |
| ViperTeq                     | 1        | 1      | 0.08%   |
| USB3.0                       | 1        | 1      | 0.08%   |
| UMIS                         | 1        | 1      | 0.08%   |
| UMAX                         | 1        | 1      | 0.08%   |
| TCSUNBOW-X5                  | 1        | 1      | 0.08%   |
| TCSUNBOW                     | 1        | 2      | 0.08%   |
| StoreJet                     | 1        | 1      | 0.08%   |
| SMI                          | 1        | 1      | 0.08%   |
| Smartbuy                     | 1        | 1      | 0.08%   |
| Shenzhen Longsys Electronics | 1        | 2      | 0.08%   |
| SATADOM-ML                   | 1        | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba VT180 240GB SSD            | 23       | 1.55%   |
| Seagate ST500DM002-1BD142 500GB    | 20       | 1.34%   |
| Seagate ST2000DM008-2FR102 2TB     | 19       | 1.28%   |
| Toshiba DT01ACA050 500GB           | 18       | 1.21%   |
| Seagate ST1000DM010-2EP102 1TB     | 17       | 1.14%   |
| Kingston SA400S37240G 240GB SSD    | 17       | 1.14%   |
| SanDisk NVMe SSD Drive 1TB         | 15       | 1.01%   |
| Samsung SSD 850 EVO 500GB          | 15       | 1.01%   |
| Samsung SSD 850 EVO 250GB          | 15       | 1.01%   |
| Samsung NVMe SSD Drive 1TB         | 15       | 1.01%   |
| Samsung SSD 980 PRO 1TB            | 12       | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB           | 10       | 0.67%   |
| Toshiba HDWD110 1TB                | 10       | 0.67%   |
| Toshiba DT01ACA100 1TB             | 10       | 0.67%   |
| Seagate ST1000DM003-1ER162 1TB     | 10       | 0.67%   |
| Samsung SSD 860 EVO 500GB          | 10       | 0.67%   |
| Kingston SA400S37480G 480GB SSD    | 9        | 0.6%    |
| Crucial CT500MX500SSD1 500GB       | 9        | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB     | 8        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB     | 8        | 0.54%   |
| SanDisk NVMe SSD Drive 500GB       | 8        | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB     | 8        | 0.54%   |
| Kingston SA400S37120G 120GB SSD    | 8        | 0.54%   |
| Toshiba MQ01ABD100 1TB             | 7        | 0.47%   |
| Seagate ST31000528AS 1TB           | 7        | 0.47%   |
| Seagate Expansion Desk 4TB         | 7        | 0.47%   |
| Samsung SSD 980 1TB                | 7        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB        | 7        | 0.47%   |
| Toshiba DT01ACA200 2TB             | 6        | 0.4%    |
| Seagate ST3500418AS 500GB          | 6        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB     | 6        | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB     | 6        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6        | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB     | 6        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB       | 6        | 0.4%    |
| Samsung NVMe SSD Drive 500GB       | 6        | 0.4%    |
| Kingston SV300S37A240G 240GB SSD   | 6        | 0.4%    |
| Seagate Expansion 1TB              | 5        | 0.34%   |
| Samsung SSD 870 QVO 1TB            | 5        | 0.34%   |
| Samsung SSD 860 EVO 250GB          | 5        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD   | 5        | 0.34%   |
| Crucial CT240BX500SSD1 240GB       | 5        | 0.34%   |
| Unknown                            | 5        | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 4        | 0.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 4        | 0.27%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 4        | 0.27%   |
| WDC WD20EARX-00PASB0 2TB           | 4        | 0.27%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4        | 0.27%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 4        | 0.27%   |
| Unknown SD/MMC/MS PRO 64GB         | 4        | 0.27%   |
| Toshiba DT01ACA300 3TB             | 4        | 0.27%   |
| Seagate ST2000DM001-9YN164 2TB     | 4        | 0.27%   |
| Seagate ST1000LM049-2GH172 1TB     | 4        | 0.27%   |
| Seagate ST1000DM003-9YN162 1TB     | 4        | 0.27%   |
| SanDisk SDSSDA240G 240GB           | 4        | 0.27%   |
| Samsung SSD 970 EVO 1TB            | 4        | 0.27%   |
| Samsung SSD 870 QVO 2TB            | 4        | 0.27%   |
| Samsung SSD 860 EVO 1TB            | 4        | 0.27%   |
| Samsung SSD 850 EVO 1TB            | 4        | 0.27%   |
| Samsung SSD 750 EVO 250GB          | 4        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 232      | 348    | 39.66%  |
| WDC                 | 190      | 331    | 32.48%  |
| Toshiba             | 67       | 84     | 11.45%  |
| Hitachi             | 33       | 37     | 5.64%   |
| Samsung Electronics | 28       | 41     | 4.79%   |
| HGST                | 13       | 17     | 2.22%   |
| Unknown             | 5        | 5      | 0.85%   |
| Maxtor              | 4        | 5      | 0.68%   |
| Intenso             | 4        | 4      | 0.68%   |
| SABRENT             | 2        | 3      | 0.34%   |
| ASMT                | 2        | 3      | 0.34%   |
| WD MediaMax         | 1        | 1      | 0.17%   |
| HPE                 | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 1      | 0.17%   |
| DAS                 | 1        | 3      | 0.17%   |
| Apple               | 1        | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 93       | 121    | 20.53%  |
| Kingston            | 75       | 91     | 16.56%  |
| Crucial             | 53       | 65     | 11.7%   |
| SanDisk             | 32       | 43     | 7.06%   |
| WDC                 | 31       | 38     | 6.84%   |
| Toshiba             | 27       | 29     | 5.96%   |
| China               | 12       | 14     | 2.65%   |
| OCZ                 | 10       | 10     | 2.21%   |
| A-DATA Technology   | 10       | 12     | 2.21%   |
| PNY                 | 9        | 12     | 1.99%   |
| Transcend           | 6        | 6      | 1.32%   |
| SPCC                | 6        | 6      | 1.32%   |
| Lexar               | 6        | 6      | 1.32%   |
| Intel               | 6        | 6      | 1.32%   |
| Team                | 5        | 9      | 1.1%    |
| SK hynix            | 5        | 5      | 1.1%    |
| Corsair             | 5        | 5      | 1.1%    |
| Micron Technology   | 4        | 6      | 0.88%   |
| Intenso             | 4        | 4      | 0.88%   |
| Gigabyte Technology | 4        | 5      | 0.88%   |
| Netac               | 3        | 3      | 0.66%   |
| Dogfish             | 3        | 4      | 0.66%   |
| Unknown             | 3        | 3      | 0.66%   |
| Plextor             | 2        | 2      | 0.44%   |
| Phison              | 2        | 2      | 0.44%   |
| Leven               | 2        | 2      | 0.44%   |
| KingDian            | 2        | 2      | 0.44%   |
| GOODRAM             | 2        | 3      | 0.44%   |
| FORESEE             | 2        | 2      | 0.44%   |
| Apacer              | 2        | 2      | 0.44%   |
| WALRAM              | 1        | 1      | 0.22%   |
| ViperTeq            | 1        | 1      | 0.22%   |
| USB3.0              | 1        | 1      | 0.22%   |
| UMAX                | 1        | 1      | 0.22%   |
| TCSUNBOW-X5         | 1        | 1      | 0.22%   |
| StoreJet            | 1        | 1      | 0.22%   |
| Smartbuy            | 1        | 1      | 0.22%   |
| Seagate             | 1        | 1      | 0.22%   |
| S3+                 | 1        | 1      | 0.22%   |
| RZX                 | 1        | 1      | 0.22%   |
| PNY USB             | 1        | 1      | 0.22%   |
| Patriot             | 1        | 1      | 0.22%   |
| OWC                 | 1        | 1      | 0.22%   |
| Mushkin             | 1        | 1      | 0.22%   |
| MidasForce          | 1        | 1      | 0.22%   |
| Maxtor              | 1        | 1      | 0.22%   |
| Londisk             | 1        | 2      | 0.22%   |
| LITEONIT            | 1        | 1      | 0.22%   |
| LDLC                | 1        | 1      | 0.22%   |
| KLEVV               | 1        | 2      | 0.22%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.22%   |
| KingSpec            | 1        | 1      | 0.22%   |
| Hewlett-Packard     | 1        | 1      | 0.22%   |
| Emtec               | 1        | 1      | 0.22%   |
| BAITITON            | 1        | 1      | 0.22%   |
| Apple               | 1        | 1      | 0.22%   |
| AMD                 | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 449      | 885    | 43.13%  |
| SSD     | 369      | 547    | 35.45%  |
| NVMe    | 192      | 291    | 18.44%  |
| Unknown | 28       | 35     | 2.69%   |
| MMC     | 3        | 6      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 593      | 1383   | 70.09%  |
| NVMe | 189      | 288    | 22.34%  |
| SAS  | 61       | 87     | 7.21%   |
| MMC  | 3        | 6      | 0.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 427      | 661    | 47.92%  |
| 0.51-1.0   | 255      | 388    | 28.62%  |
| 1.01-2.0   | 113      | 186    | 12.68%  |
| 3.01-4.0   | 42       | 62     | 4.71%   |
| 4.01-10.0  | 28       | 83     | 3.14%   |
| 2.01-3.0   | 18       | 24     | 2.02%   |
| 10.01-20.0 | 8        | 28     | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 169      | 25%     |
| 251-500        | 129      | 19.08%  |
| 501-1000       | 127      | 18.79%  |
| More than 3000 | 76       | 11.24%  |
| 1001-2000      | 73       | 10.8%   |
| 1-20           | 36       | 5.33%   |
| 2001-3000      | 33       | 4.88%   |
| 51-100         | 25       | 3.7%    |
| 21-50          | 5        | 0.74%   |
| Unknown        | 3        | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 262      | 38.3%   |
| 21-50          | 99       | 14.47%  |
| 101-250        | 81       | 11.84%  |
| 51-100         | 67       | 9.8%    |
| 251-500        | 59       | 8.63%   |
| 501-1000       | 33       | 4.82%   |
| More than 3000 | 31       | 4.53%   |
| 1001-2000      | 31       | 4.53%   |
| 2001-3000      | 17       | 2.49%   |
| Unknown        | 3        | 0.44%   |
| 0              | 1        | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2        | 2      | 3.45%   |
| Hitachi HDS721010CLA332 1TB                      | 2        | 2      | 3.45%   |
| WDC WD75 00BPVT-16HXZ 752GB                      | 1        | 1      | 1.72%   |
| WDC WD6002FZWX-00GBGB0 6TB                       | 1        | 1      | 1.72%   |
| WDC WD5000AAKX-08ERMA0 500GB                     | 1        | 1      | 1.72%   |
| WDC WD5000AAKS-65V0A0 500GB                      | 1        | 1      | 1.72%   |
| WDC WD40PURZ-85TTDY0 4TB                         | 1        | 1      | 1.72%   |
| WDC WD40EFRX-68WT0N0 4TB                         | 1        | 2      | 1.72%   |
| WDC WD4003FZEX-00Z4SA0 4TB                       | 1        | 2      | 1.72%   |
| WDC WD20EARX-008FB0 2TB                          | 1        | 2      | 1.72%   |
| WDC WD10PURX-64D85Y0 1TB                         | 1        | 1      | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1        | 1      | 1.72%   |
| WDC WD10EZEX-22MFCA0 1TB                         | 1        | 1      | 1.72%   |
| WDC WD10EFRX-68FYTN0 1TB                         | 1        | 1      | 1.72%   |
| WDC WD10EARX-00N0YB0 1TB                         | 1        | 1      | 1.72%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1        | 1      | 1.72%   |
| WDC WD1003FBYX-01Y7B1 752GB                      | 1        | 1      | 1.72%   |
| Toshiba MQ01ABD100 1TB                           | 1        | 1      | 1.72%   |
| Toshiba MK6465GSX 640GB                          | 1        | 1      | 1.72%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 1.72%   |
| Seagate ST4000VX007-2DT166 4TB                   | 1        | 1      | 1.72%   |
| Seagate ST3750640NS 752GB                        | 1        | 2      | 1.72%   |
| Seagate ST3250823AS 250GB                        | 1        | 1      | 1.72%   |
| Seagate ST3250410AS 250GB                        | 1        | 1      | 1.72%   |
| Seagate ST3160815AS 160GB                        | 1        | 1      | 1.72%   |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 1.72%   |
| Seagate ST2000DX002-2DV164 2TB                   | 1        | 1      | 1.72%   |
| Seagate ST1000DX001-1CM162 1TB                   | 1        | 1      | 1.72%   |
| Seagate ST1000DM010-2EP102 1TB                   | 1        | 1      | 1.72%   |
| SanDisk SSD PLUS 480GB                           | 1        | 1      | 1.72%   |
| SanDisk SD9SB8W-128G-1006 128GB SSD              | 1        | 1      | 1.72%   |
| Samsung Electronics SSD PM800 Series 2.5 256GB   | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 980 PRO 2TB              | 1        | 2      | 1.72%   |
| Samsung Electronics SSD 980 PRO 1TB              | 1        | 1      | 1.72%   |
| Samsung Electronics SSD 870 EVO 1TB              | 1        | 1      | 1.72%   |
| Samsung Electronics SP1614C 160GB                | 1        | 1      | 1.72%   |
| Samsung Electronics MZ7TE128HMGR-000H1 128GB SSD | 1        | 1      | 1.72%   |
| Samsung Electronics HD642JJ 640GB                | 1        | 1      | 1.72%   |
| Samsung Electronics HD322GJ 320GB                | 1        | 1      | 1.72%   |
| Samsung Electronics HD103SI 1TB                  | 1        | 1      | 1.72%   |
| PNY CS3030 500GB SSD                             | 1        | 1      | 1.72%   |
| OCZ VERTEX4 256GB SSD                            | 1        | 1      | 1.72%   |
| Maxtor STM3160211AS 160GB                        | 1        | 1      | 1.72%   |
| LITEONIT LCT-128M3S 128GB SSD                    | 1        | 1      | 1.72%   |
| Kingston SV300S37A60G 64GB SSD                   | 1        | 1      | 1.72%   |
| Kingston SV300S37A120G 120GB SSD                 | 1        | 1      | 1.72%   |
| Kingston SH103S3240G 240GB SSD                   | 1        | 1      | 1.72%   |
| Kingston SA400S37240G 240GB SSD                  | 1        | 1      | 1.72%   |
| Intenso SSD 120GB                                | 1        | 1      | 1.72%   |
| Hitachi HTS727575A9E364 752GB                    | 1        | 1      | 1.72%   |
| Hitachi HDT725032VLA360 320GB                    | 1        | 1      | 1.72%   |
| Hitachi HDT721032SLA380 320GB                    | 1        | 1      | 1.72%   |
| Hitachi HDS725050KLA360 500GB                    | 1        | 1      | 1.72%   |
| Hitachi HDS721616PLA380 160GB                    | 1        | 1      | 1.72%   |
| HGST HTS721010A9E630 1TB                         | 1        | 2      | 1.72%   |
| Crucial CT480M500SSD1 480GB                      | 1        | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 18     | 25.86%  |
| Seagate             | 11       | 12     | 18.97%  |
| Samsung Electronics | 9        | 10     | 15.52%  |
| Hitachi             | 7        | 7      | 12.07%  |
| Kingston            | 4        | 4      | 6.9%    |
| Toshiba             | 3        | 3      | 5.17%   |
| SanDisk             | 2        | 2      | 3.45%   |
| PNY                 | 1        | 1      | 1.72%   |
| OCZ                 | 1        | 1      | 1.72%   |
| Maxtor              | 1        | 1      | 1.72%   |
| LITEONIT            | 1        | 1      | 1.72%   |
| Intenso             | 1        | 1      | 1.72%   |
| HGST                | 1        | 2      | 1.72%   |
| Crucial             | 1        | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 18     | 35.71%  |
| Seagate             | 11       | 12     | 26.19%  |
| Hitachi             | 7        | 7      | 16.67%  |
| Samsung Electronics | 4        | 4      | 9.52%   |
| Toshiba             | 3        | 3      | 7.14%   |
| Maxtor              | 1        | 1      | 2.38%   |
| HGST                | 1        | 2      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 47     | 70.37%  |
| SSD  | 13       | 13     | 24.07%  |
| NVMe | 3        | 4      | 5.56%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 462      | 1229   | 63.99%  |
| Works    | 212      | 471    | 29.36%  |
| Malfunc  | 48       | 64     | 6.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 437      | 45.05%  |
| AMD                          | 207      | 21.34%  |
| Samsung Electronics          | 78       | 8.04%   |
| SanDisk                      | 44       | 4.54%   |
| ASMedia Technology           | 36       | 3.71%   |
| Marvell Technology Group     | 25       | 2.58%   |
| JMicron Technology           | 20       | 2.06%   |
| Phison Electronics           | 18       | 1.86%   |
| Nvidia                       | 16       | 1.65%   |
| Kingston Technology Company  | 14       | 1.44%   |
| SK hynix                     | 11       | 1.13%   |
| Silicon Motion               | 9        | 0.93%   |
| Micron/Crucial Technology    | 7        | 0.72%   |
| LSI Logic / Symbios Logic    | 7        | 0.72%   |
| Realtek Semiconductor        | 6        | 0.62%   |
| KIOXIA                       | 5        | 0.52%   |
| ADATA Technology             | 5        | 0.52%   |
| VIA Technologies             | 4        | 0.41%   |
| Silicon Image                | 4        | 0.41%   |
| Seagate Technology           | 4        | 0.41%   |
| OCZ Technology Group         | 2        | 0.21%   |
| Micron Technology            | 2        | 0.21%   |
| Union Memory (Shenzhen)      | 1        | 0.1%    |
| Toshiba America Info Systems | 1        | 0.1%    |
| Shenzhen Longsys Electronics | 1        | 0.1%    |
| MAXIO Technology (Hangzhou)  | 1        | 0.1%    |
| Lite-On IT Corp. / Plextor   | 1        | 0.1%    |
| HighPoint Technologies       | 1        | 0.1%    |
| Chelsio Communications       | 1        | 0.1%    |
| Broadcom / LSI               | 1        | 0.1%    |
| Biwin Storage Technology     | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 126      | 10.6%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 60       | 5.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40       | 3.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 39       | 3.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 38       | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 36       | 3.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 34       | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 30       | 2.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 27       | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 27       | 2.27%   |
| Intel SATA Controller [RAID mode]                                                       | 25       | 2.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 21       | 1.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20       | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 19       | 1.6%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 19       | 1.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 17       | 1.43%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 17       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 16       | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 16       | 1.35%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 15       | 1.26%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 15       | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 1.26%   |
| AMD FCH SATA Controller D                                                               | 15       | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 13       | 1.09%   |
| Samsung NVMe SSD Controller 980                                                         | 13       | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 11       | 0.93%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 11       | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 10       | 0.84%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 9        | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9        | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9        | 0.76%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 9        | 0.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 9        | 0.76%   |
| SanDisk Non-Volatile memory controller                                                  | 8        | 0.67%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8        | 0.67%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 8        | 0.67%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 8        | 0.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8        | 0.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 8        | 0.67%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 7        | 0.59%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.59%   |
| Kingston Company Company Non-Volatile memory controller                                 | 7        | 0.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7        | 0.59%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7        | 0.59%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 7        | 0.59%   |
| AMD FCH IDE Controller                                                                  | 7        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 0.5%    |
| Nvidia MCP61 SATA Controller                                                            | 6        | 0.5%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 6        | 0.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 6        | 0.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.5%    |
| AMD X370 Series Chipset SATA Controller                                                 | 6        | 0.5%    |
| SK hynix Gold P31 SSD                                                                   | 5        | 0.42%   |
| Realtek Realtek Non-Volatile memory controller                                          | 5        | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 551      | 58.87%  |
| NVMe | 190      | 20.3%   |
| IDE  | 133      | 14.21%  |
| RAID | 50       | 5.34%   |
| SAS  | 7        | 0.75%   |
| SCSI | 5        | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 446      | 67.17%  |
| AMD    | 218      | 32.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 17       | 2.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 11       | 1.66%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 11       | 1.66%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 9        | 1.36%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 8        | 1.2%    |
| Intel Core i5-3470 CPU @ 3.20GHz                | 8        | 1.2%    |
| AMD Ryzen 7 3700X 8-Core Processor              | 8        | 1.2%    |
| Intel Core i7-6700K CPU @ 4.00GHz               | 7        | 1.05%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 7        | 1.05%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 7        | 1.05%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 7        | 1.05%   |
| AMD FX-8350 Eight-Core Processor                | 7        | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 6        | 0.9%    |
| Intel Core i3-6100 CPU @ 3.70GHz                | 6        | 0.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz                | 6        | 0.9%    |
| Intel Core i3-2120 CPU @ 3.30GHz                | 6        | 0.9%    |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 6        | 0.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 6        | 0.9%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 6        | 0.9%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 6        | 0.9%    |
| AMD A10-7700K Radeon R7, 10 Compute Cores 4C+6G | 6        | 0.9%    |
| Intel Core i9-9900K CPU @ 3.60GHz               | 5        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 5        | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 5        | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 5        | 0.75%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 5        | 0.75%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 5        | 0.75%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 5        | 0.75%   |
| Intel 12th Gen Core i9-12900K                   | 5        | 0.75%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 5        | 0.75%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 5        | 0.75%   |
| AMD Phenom II X4 965 Processor                  | 5        | 0.75%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 4        | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz                | 4        | 0.6%    |
| Intel Core i7-5820K CPU @ 3.30GHz               | 4        | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz                | 4        | 0.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz                | 4        | 0.6%    |
| Intel Core i5-6600K CPU @ 3.50GHz               | 4        | 0.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz                | 4        | 0.6%    |
| Intel Core i5-3570 CPU @ 3.40GHz                | 4        | 0.6%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 4        | 0.6%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 4        | 0.6%    |
| Intel Celeron J4125 CPU @ 2.00GHz               | 4        | 0.6%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 4        | 0.6%    |
| AMD Ryzen 7 5800X 8-Core Processor              | 4        | 0.6%    |
| AMD Ryzen 7 5700G with Radeon Graphics          | 4        | 0.6%    |
| AMD Ryzen 7 1800X Eight-Core Processor          | 4        | 0.6%    |
| AMD Ryzen 7 1700 Eight-Core Processor           | 4        | 0.6%    |
| AMD Phenom II X4 955 Processor                  | 4        | 0.6%    |
| AMD FX-6300 Six-Core Processor                  | 4        | 0.6%    |
| AMD FX-4300 Quad-Core Processor                 | 4        | 0.6%    |
| AMD A4-5300 APU with Radeon HD Graphics         | 4        | 0.6%    |
| Intel Core i7-8700K CPU @ 3.70GHz               | 3        | 0.45%   |
| Intel Core i7-3820 CPU @ 3.60GHz                | 3        | 0.45%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 3        | 0.45%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 3        | 0.45%   |
| Intel Core i5-9500 CPU @ 3.00GHz                | 3        | 0.45%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 3        | 0.45%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 3        | 0.45%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 3        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 116      | 17.47%  |
| Intel Core i7           | 87       | 13.1%   |
| Intel Core i3           | 69       | 10.39%  |
| AMD Ryzen 5             | 55       | 8.28%   |
| Intel Xeon              | 41       | 6.17%   |
| Other                   | 34       | 5.12%   |
| AMD Ryzen 7             | 34       | 5.12%   |
| AMD FX                  | 26       | 3.92%   |
| Intel Celeron           | 21       | 3.16%   |
| Intel Core 2 Duo        | 20       | 3.01%   |
| AMD Ryzen 9             | 18       | 2.71%   |
| Intel Core 2 Quad       | 17       | 2.56%   |
| Intel Pentium           | 15       | 2.26%   |
| AMD A10                 | 12       | 1.81%   |
| Intel Core i9           | 11       | 1.66%   |
| AMD Phenom II X4        | 11       | 1.66%   |
| AMD Ryzen 3             | 9        | 1.36%   |
| AMD A8                  | 8        | 1.2%    |
| AMD A4                  | 6        | 0.9%    |
| AMD Phenom II X6        | 5        | 0.75%   |
| Intel Pentium Dual-Core | 4        | 0.6%    |
| Intel Core 2            | 4        | 0.6%    |
| AMD A6                  | 4        | 0.6%    |
| AMD Ryzen Threadripper  | 3        | 0.45%   |
| AMD Athlon II X4        | 3        | 0.45%   |
| AMD Athlon II X2        | 3        | 0.45%   |
| AMD Athlon              | 3        | 0.45%   |
| Intel Pentium Dual      | 2        | 0.3%    |
| Intel Pentium 4         | 2        | 0.3%    |
| Intel Atom              | 2        | 0.3%    |
| AMD Ryzen 7 PRO         | 2        | 0.3%    |
| AMD Ryzen 5 PRO         | 2        | 0.3%    |
| AMD Phenom              | 2        | 0.3%    |
| AMD Athlon II X3        | 2        | 0.3%    |
| AMD Athlon 64           | 2        | 0.3%    |
| Intel Pentium Gold      | 1        | 0.15%   |
| Intel Core 2 Extreme    | 1        | 0.15%   |
| AMD Ryzen Embedded      | 1        | 0.15%   |
| AMD Phenom II X2        | 1        | 0.15%   |
| AMD GX                  | 1        | 0.15%   |
| AMD EPYC                | 1        | 0.15%   |
| AMD E1                  | 1        | 0.15%   |
| AMD Athlon X4           | 1        | 0.15%   |
| AMD Athlon 64 X2        | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 260      | 39.16%  |
| 2      | 159      | 23.95%  |
| 6      | 105      | 15.81%  |
| 8      | 67       | 10.09%  |
| 12     | 23       | 3.46%   |
| 16     | 15       | 2.26%   |
| 1      | 12       | 1.81%   |
| 10     | 9        | 1.36%   |
| 3      | 9        | 1.36%   |
| 28     | 2        | 0.3%    |
| 64     | 1        | 0.15%   |
| 32     | 1        | 0.15%   |
| 14     | 1        | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 651      | 98.04%  |
| 2      | 13       | 1.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 403      | 60.69%  |
| 1      | 261      | 39.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 663      | 99.85%  |
| Unknown        | 1        | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 413      | 61.09%  |
| 0x306c3    | 30       | 4.44%   |
| 0x08701021 | 17       | 2.51%   |
| 0x306a9    | 16       | 2.37%   |
| 0x206a7    | 16       | 2.37%   |
| 0x506e3    | 14       | 2.07%   |
| 0x906e9    | 11       | 1.63%   |
| 0x0a201016 | 11       | 1.63%   |
| 0x06003106 | 10       | 1.48%   |
| 0x1067a    | 9        | 1.33%   |
| 0xa0653    | 8        | 1.18%   |
| 0x906ea    | 8        | 1.18%   |
| 0x06000852 | 8        | 1.18%   |
| 0x90672    | 7        | 1.04%   |
| 0x306f2    | 6        | 0.89%   |
| 0x0a50000c | 5        | 0.74%   |
| 0x010000c8 | 5        | 0.74%   |
| 0xa0655    | 4        | 0.59%   |
| 0x06001119 | 4        | 0.59%   |
| 0xa0671    | 3        | 0.44%   |
| 0x706a8    | 3        | 0.44%   |
| 0x106a5    | 3        | 0.44%   |
| 0x0a201009 | 3        | 0.44%   |
| 0x08701013 | 3        | 0.44%   |
| 0x08108109 | 3        | 0.44%   |
| 0x0810100b | 3        | 0.44%   |
| 0x0800820d | 3        | 0.44%   |
| 0x906ec    | 2        | 0.3%    |
| 0x906eb    | 2        | 0.3%    |
| 0x90675    | 2        | 0.3%    |
| 0x806ec    | 2        | 0.3%    |
| 0x706a1    | 2        | 0.3%    |
| 0x50654    | 2        | 0.3%    |
| 0x20655    | 2        | 0.3%    |
| 0x0a201204 | 2        | 0.3%    |
| 0x0830104d | 2        | 0.3%    |
| 0x08001138 | 2        | 0.3%    |
| 0x08001126 | 2        | 0.3%    |
| 0x00000000 | 2        | 0.3%    |
| 0x906ed    | 1        | 0.15%   |
| 0x806e9    | 1        | 0.15%   |
| 0x806c1    | 1        | 0.15%   |
| 0x6fd      | 1        | 0.15%   |
| 0x6f6      | 1        | 0.15%   |
| 0x406f1    | 1        | 0.15%   |
| 0x406e3    | 1        | 0.15%   |
| 0x306e4    | 1        | 0.15%   |
| 0x30679    | 1        | 0.15%   |
| 0x206d7    | 1        | 0.15%   |
| 0x206c2    | 1        | 0.15%   |
| 0x10677    | 1        | 0.15%   |
| 0x10676    | 1        | 0.15%   |
| 0x0a20120a | 1        | 0.15%   |
| 0x0a201205 | 1        | 0.15%   |
| 0x08301034 | 1        | 0.15%   |
| 0x08101016 | 1        | 0.15%   |
| 0x08001137 | 1        | 0.15%   |
| 0x0800111c | 1        | 0.15%   |
| 0x0600611a | 1        | 0.15%   |
| 0x06003104 | 1        | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 93       | 14.01%  |
| IvyBridge        | 55       | 8.28%   |
| Zen 2            | 47       | 7.08%   |
| KabyLake         | 47       | 7.08%   |
| SandyBridge      | 45       | 6.78%   |
| Skylake          | 41       | 6.17%   |
| Zen 3            | 40       | 6.02%   |
| Penryn           | 38       | 5.72%   |
| Piledriver       | 33       | 4.97%   |
| K10              | 27       | 4.07%   |
| Westmere         | 23       | 3.46%   |
| CometLake        | 22       | 3.31%   |
| Zen              | 21       | 3.16%   |
| Zen+             | 20       | 3.01%   |
| Unknown          | 20       | 3.01%   |
| Core             | 16       | 2.41%   |
| Steamroller      | 15       | 2.26%   |
| Nehalem          | 11       | 1.66%   |
| Alderlake Hybrid | 8        | 1.2%    |
| Goldmont plus    | 7        | 1.05%   |
| Silvermont       | 6        | 0.9%    |
| Broadwell        | 6        | 0.9%    |
| Excavator        | 5        | 0.75%   |
| Icelake          | 4        | 0.6%    |
| K8 Hammer        | 3        | 0.45%   |
| Bulldozer        | 3        | 0.45%   |
| TigerLake        | 2        | 0.3%    |
| NetBurst         | 2        | 0.3%    |
| K10 Llano        | 2        | 0.3%    |
| Puma             | 1        | 0.15%   |
| Bobcat           | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 290      | 41.31%  |
| Intel                      | 210      | 29.91%  |
| AMD                        | 196      | 27.92%  |
| ASPEED Technology          | 4        | 0.57%   |
| Matrox Electronics Systems | 2        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 45       | 6.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 21       | 2.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 21       | 2.95%   |
| Intel HD Graphics 530                                                       | 19       | 2.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 2.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 16       | 2.25%   |
| Nvidia GK208B [GeForce GT 730]                                              | 14       | 1.97%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 13       | 1.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 12       | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 1.54%   |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 1.54%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 1.4%    |
| Intel AlderLake-S GT1                                                       | 10       | 1.4%    |
| Intel HD Graphics 630                                                       | 9        | 1.26%   |
| AMD Cezanne                                                                 | 9        | 1.26%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 9        | 1.26%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 1.12%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 8        | 1.12%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 8        | 1.12%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 0.98%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 0.98%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 0.98%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 7        | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 7        | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 0.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 6        | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 5        | 0.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 0.7%    |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 5        | 0.7%    |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 0.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.7%    |
| AMD Juniper XT [Radeon HD 5770]                                             | 5        | 0.7%    |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 5        | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.56%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 4        | 0.56%   |
| Nvidia GF108 [GeForce GT 730]                                               | 4        | 0.56%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 4        | 0.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.56%   |
| ASPEED Technology ASPEED Graphics Family                                    | 4        | 0.56%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 4        | 0.56%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 4        | 0.56%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 0.56%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.42%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.42%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 3        | 0.42%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.42%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 3        | 0.42%   |
| Nvidia GT216 [GeForce GT 220]                                               | 3        | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.42%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 3        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 267      | 39.97%  |
| 1 x Intel       | 181      | 27.1%   |
| 1 x AMD         | 181      | 27.1%   |
| Intel + Nvidia  | 10       | 1.5%    |
| AMD + Nvidia    | 8        | 1.2%    |
| 2 x AMD         | 5        | 0.75%   |
| 2 x Nvidia      | 4        | 0.6%    |
| Intel + AMD     | 4        | 0.6%    |
| 1 x ASPEED      | 3        | 0.45%   |
| Other           | 2        | 0.3%    |
| Nvidia + Matrox | 1        | 0.15%   |
| Nvidia + ASPEED | 1        | 0.15%   |
| 1 x Matrox      | 1        | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 454      | 68.17%  |
| Proprietary | 174      | 26.13%  |
| Unknown     | 38       | 5.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 480      | 71.64%  |
| 0.51-1.0   | 39       | 5.82%   |
| 1.01-2.0   | 37       | 5.52%   |
| 7.01-8.0   | 35       | 5.22%   |
| 3.01-4.0   | 30       | 4.48%   |
| 0.01-0.5   | 18       | 2.69%   |
| 5.01-6.0   | 12       | 1.79%   |
| 8.01-16.0  | 12       | 1.79%   |
| 4.01-5.0   | 4        | 0.6%    |
| 2.01-3.0   | 3        | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 109      | 16.12%  |
| Dell                 | 79       | 11.69%  |
| Goldstar             | 68       | 10.06%  |
| BenQ                 | 44       | 6.51%   |
| Acer                 | 37       | 5.47%   |
| Hewlett-Packard      | 36       | 5.33%   |
| Philips              | 35       | 5.18%   |
| Ancor Communications | 35       | 5.18%   |
| AOC                  | 23       | 3.4%    |
| Lenovo               | 18       | 2.66%   |
| ViewSonic            | 16       | 2.37%   |
| ASUSTek Computer     | 15       | 2.22%   |
| LG Electronics       | 12       | 1.78%   |
| Sony                 | 11       | 1.63%   |
| Iiyama               | 9        | 1.33%   |
| Unknown              | 8        | 1.18%   |
| Fujitsu Siemens      | 7        | 1.04%   |
| Sceptre Tech         | 5        | 0.74%   |
| Panasonic            | 5        | 0.74%   |
| NEC Computers        | 5        | 0.74%   |
| Gigabyte Technology  | 5        | 0.74%   |
| Onkyo                | 4        | 0.59%   |
| MStar                | 4        | 0.59%   |
| Eizo                 | 4        | 0.59%   |
| Unknown              | 4        | 0.59%   |
| Vizio                | 3        | 0.44%   |
| Unknown (XXX)        | 3        | 0.44%   |
| Toshiba              | 3        | 0.44%   |
| Sharp                | 3        | 0.44%   |
| Medion               | 3        | 0.44%   |
| HKC                  | 3        | 0.44%   |
| Vestel Elektronik    | 2        | 0.3%    |
| STA                  | 2        | 0.3%    |
| Seiki                | 2        | 0.3%    |
| MSI                  | 2        | 0.3%    |
| KTC                  | 2        | 0.3%    |
| Idek Iiyama          | 2        | 0.3%    |
| HUAWEI               | 2        | 0.3%    |
| Hitachi              | 2        | 0.3%    |
| HannStar             | 2        | 0.3%    |
| CTV                  | 2        | 0.3%    |
| ___                  | 1        | 0.15%   |
| Zoran                | 1        | 0.15%   |
| YCT                  | 1        | 0.15%   |
| Xiaomi               | 1        | 0.15%   |
| Westinghouse         | 1        | 0.15%   |
| Wacom                | 1        | 0.15%   |
| Viotek               | 1        | 0.15%   |
| Unknown (AAA)        | 1        | 0.15%   |
| TCT                  | 1        | 0.15%   |
| Sunplus              | 1        | 0.15%   |
| SPU                  | 1        | 0.15%   |
| Skyworth             | 1        | 0.15%   |
| SKY                  | 1        | 0.15%   |
| SHC                  | 1        | 0.15%   |
| SAC                  | 1        | 0.15%   |
| RTK                  | 1        | 0.15%   |
| RS                   | 1        | 0.15%   |
| RCA                  | 1        | 0.15%   |
| Planar               | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 16       | 2.24%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 8        | 1.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 5        | 0.7%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 4        | 0.56%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 4        | 0.56%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                       | 4        | 0.56%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch   | 4        | 0.56%   |
| Unknown                                                                 | 4        | 0.56%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 3        | 0.42%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 3        | 0.42%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                          | 3        | 0.42%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch                | 3        | 0.42%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 3        | 0.42%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                  | 3        | 0.42%   |
| Dell U2410 DELF016 1920x1200 520x320mm 24.0-inch                        | 3        | 0.42%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                     | 3        | 0.42%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                        | 3        | 0.42%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch        | 3        | 0.42%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch        | 3        | 0.42%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch   | 2        | 0.28%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 2        | 0.28%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 2        | 0.28%   |
| STA SEMP LEDTV STA0030 1920x540 708x398mm 32.0-inch                     | 2        | 0.28%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 598x336mm 27.0-inch          | 2        | 0.28%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2        | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.28%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 2        | 0.28%   |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch    | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                    | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM7032 1920x1080 1210x680mm 54.6-inch  | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0FB9 3840x2160 1872x1053mm 84.6-inch | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch   | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch   | 2        | 0.28%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch      | 2        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2        | 0.28%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2        | 0.28%   |
| Onkyo TX-NR747 ONK0F71 1920x1200 550x309mm 24.8-inch                    | 2        | 0.28%   |
| HKC 24N1 HKC2413 1920x1080 527x296mm 23.8-inch                          | 2        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 2        | 0.28%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 2        | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 0.28%   |
| Goldstar E2251 GSM586D 1920x1080 480x270mm 21.7-inch                    | 2        | 0.28%   |
| Gigabyte Technology AORUS FV43U GBT4300 3840x2160 697x392mm 31.5-inch   | 2        | 0.28%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                     | 2        | 0.28%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                       | 2        | 0.28%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                       | 2        | 0.28%   |
| Dell P2415Q DELA0BE 3840x2160 530x300mm 24.0-inch                       | 2        | 0.28%   |
| Dell P2012H DEL4079 1600x900 443x249mm 20.0-inch                        | 2        | 0.28%   |
| Dell 2208WFP DEL403C 1680x1050 473x296mm 22.0-inch                      | 2        | 0.28%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                       | 2        | 0.28%   |
| CTV CTV CTV0030 1920x1080 708x398mm 32.0-inch                           | 2        | 0.28%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                      | 2        | 0.28%   |
| BenQ LCD BNQ8020 3840x2160 708x399mm 32.0-inch                          | 2        | 0.28%   |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                       | 2        | 0.28%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                      | 2        | 0.28%   |
| Ancor Communications PA248 ACI24B1 1920x1200 546x352mm 25.6-inch        | 2        | 0.28%   |
| Ancor Communications ASUS VX279 ACI27E4 1920x1080 621x341mm 27.9-inch   | 2        | 0.28%   |
| Acer XB273U ACR074A 2560x1440 597x336mm 27.0-inch                       | 2        | 0.28%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                        | 2        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 324      | 49.47%  |
| 3840x2160 (4K)     | 81       | 12.37%  |
| 2560x1440 (QHD)    | 51       | 7.79%   |
| 1680x1050 (WSXGA+) | 34       | 5.19%   |
| 1280x1024 (SXGA)   | 31       | 4.73%   |
| 1920x1200 (WUXGA)  | 20       | 3.05%   |
| 1440x900 (WXGA+)   | 17       | 2.6%    |
| 1366x768 (WXGA)    | 17       | 2.6%    |
| 1600x900 (HD+)     | 12       | 1.83%   |
| 3440x1440          | 11       | 1.68%   |
| Unknown            | 8        | 1.22%   |
| 2560x1080          | 7        | 1.07%   |
| 1920x540           | 7        | 1.07%   |
| 3840x1080          | 5        | 0.76%   |
| 1360x768           | 4        | 0.61%   |
| 1280x720 (HD)      | 3        | 0.46%   |
| 1024x768 (XGA)     | 3        | 0.46%   |
| 2288x1287          | 2        | 0.31%   |
| 2048x1152          | 2        | 0.31%   |
| 1600x1200          | 2        | 0.31%   |
| 720x480            | 1        | 0.15%   |
| 5760x2160          | 1        | 0.15%   |
| 4480x1440          | 1        | 0.15%   |
| 4480x1080          | 1        | 0.15%   |
| 4080x2058          | 1        | 0.15%   |
| 3840x2560          | 1        | 0.15%   |
| 3840x1600          | 1        | 0.15%   |
| 3360x1080          | 1        | 0.15%   |
| 2560x1600          | 1        | 0.15%   |
| 2464x900           | 1        | 0.15%   |
| 2048x1536          | 1        | 0.15%   |
| 1280x960           | 1        | 0.15%   |
| 1280x800 (WXGA)    | 1        | 0.15%   |
| 1280x768           | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 99       | 14.69%  |
| 27      | 98       | 14.54%  |
| 24      | 90       | 13.35%  |
| 21      | 72       | 10.68%  |
| Unknown | 43       | 6.38%   |
| 19      | 32       | 4.75%   |
| 31      | 30       | 4.45%   |
| 22      | 28       | 4.15%   |
| 17      | 21       | 3.12%   |
| 34      | 16       | 2.37%   |
| 18      | 15       | 2.23%   |
| 84      | 13       | 1.93%   |
| 32      | 13       | 1.93%   |
| 20      | 12       | 1.78%   |
| 72      | 8        | 1.19%   |
| 54      | 8        | 1.19%   |
| 40      | 8        | 1.19%   |
| 43      | 7        | 1.04%   |
| 52      | 6        | 0.89%   |
| 15      | 6        | 0.89%   |
| 28      | 5        | 0.74%   |
| 25      | 5        | 0.74%   |
| 48      | 4        | 0.59%   |
| 46      | 4        | 0.59%   |
| 42      | 4        | 0.59%   |
| 55      | 3        | 0.45%   |
| 37      | 3        | 0.45%   |
| 142     | 2        | 0.3%    |
| 65      | 2        | 0.3%    |
| 57      | 2        | 0.3%    |
| 29      | 2        | 0.3%    |
| 26      | 2        | 0.3%    |
| 13      | 2        | 0.3%    |
| 12      | 2        | 0.3%    |
| 100     | 1        | 0.15%   |
| 64      | 1        | 0.15%   |
| 63      | 1        | 0.15%   |
| 61      | 1        | 0.15%   |
| 49      | 1        | 0.15%   |
| 36      | 1        | 0.15%   |
| 33      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 266      | 40.55%  |
| 401-500        | 143      | 21.8%   |
| 601-700        | 49       | 7.47%   |
| Unknown        | 43       | 6.55%   |
| 1001-1500      | 33       | 5.03%   |
| 701-800        | 30       | 4.57%   |
| 301-350        | 24       | 3.66%   |
| 1501-2000      | 21       | 3.2%    |
| 351-400        | 18       | 2.74%   |
| 801-900        | 11       | 1.68%   |
| 901-1000       | 11       | 1.68%   |
| 201-300        | 4        | 0.61%   |
| More than 2000 | 3        | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 443      | 70.99%  |
| 16/10   | 75       | 12.02%  |
| Unknown | 37       | 5.93%   |
| 5/4     | 32       | 5.13%   |
| 21/9    | 17       | 2.72%   |
| 4/3     | 8        | 1.28%   |
| 32/9    | 5        | 0.8%    |
| 3/2     | 4        | 0.64%   |
| 1.00    | 2        | 0.32%   |
| 6/5     | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 238      | 35.84%  |
| 301-350        | 101      | 15.21%  |
| 151-200        | 65       | 9.79%   |
| 351-500        | 64       | 9.64%   |
| More than 1000 | 49       | 7.38%   |
| Unknown        | 43       | 6.48%   |
| 501-1000       | 32       | 4.82%   |
| 251-300        | 30       | 4.52%   |
| 141-150        | 29       | 4.37%   |
| 101-110        | 4        | 0.6%    |
| 71-80          | 3        | 0.45%   |
| 131-140        | 3        | 0.45%   |
| 81-90          | 1        | 0.15%   |
| 121-130        | 1        | 0.15%   |
| 111-120        | 1        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 385      | 59.97%  |
| 101-120       | 116      | 18.07%  |
| Unknown       | 43       | 6.7%    |
| 1-50          | 42       | 6.54%   |
| 121-160       | 39       | 6.07%   |
| 161-240       | 16       | 2.49%   |
| More than 240 | 1        | 0.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 506      | 75.52%  |
| 2     | 108      | 16.12%  |
| 0     | 48       | 7.16%   |
| 3     | 6        | 0.9%    |
| 4     | 2        | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 426      | 45.37%  |
| Intel                           | 291      | 30.99%  |
| Qualcomm Atheros                | 50       | 5.32%   |
| Broadcom                        | 30       | 3.19%   |
| Ralink Technology               | 15       | 1.6%    |
| TP-Link                         | 14       | 1.49%   |
| Ralink                          | 14       | 1.49%   |
| Nvidia                          | 14       | 1.49%   |
| Marvell Technology Group        | 9        | 0.96%   |
| Microsoft                       | 7        | 0.75%   |
| Broadcom Limited                | 7        | 0.75%   |
| ASUSTek Computer                | 7        | 0.75%   |
| Xiaomi                          | 5        | 0.53%   |
| MediaTek                        | 5        | 0.53%   |
| Aquantia                        | 5        | 0.53%   |
| Samsung Electronics             | 3        | 0.32%   |
| NetGear                         | 3        | 0.32%   |
| Mellanox Technologies           | 3        | 0.32%   |
| Linksys                         | 2        | 0.21%   |
| Encore Electronics              | 2        | 0.21%   |
| D-Link System                   | 2        | 0.21%   |
| D-Link                          | 2        | 0.21%   |
| ASIX Electronics                | 2        | 0.21%   |
| VIA Technologies                | 1        | 0.11%   |
| Systec                          | 1        | 0.11%   |
| Sitecom Europe                  | 1        | 0.11%   |
| Sigma Designs                   | 1        | 0.11%   |
| Sagem                           | 1        | 0.11%   |
| Qualcomm Atheros Communications | 1        | 0.11%   |
| Pulse-Eight                     | 1        | 0.11%   |
| Philips (or NXP)                | 1        | 0.11%   |
| Motorola PCS                    | 1        | 0.11%   |
| Microchip Technology            | 1        | 0.11%   |
| Micro Star International        | 1        | 0.11%   |
| LG Electronics                  | 1        | 0.11%   |
| JMicron Technology              | 1        | 0.11%   |
| IMC Networks                    | 1        | 0.11%   |
| Huawei Technologies             | 1        | 0.11%   |
| DisplayLink                     | 1        | 0.11%   |
| Chelsio Communications          | 1        | 0.11%   |
| Belkin Components               | 1        | 0.11%   |
| AVM                             | 1        | 0.11%   |
| Apple                           | 1        | 0.11%   |
| American Megatrends             | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 334      | 30.93%  |
| Realtek RTL8125 2.5GbE Controller                                 | 43       | 3.98%   |
| Intel Wi-Fi 6 AX200                                               | 36       | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 35       | 3.24%   |
| Intel Ethernet Connection (2) I219-V                              | 26       | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26       | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 20       | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18       | 1.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 16       | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 16       | 1.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 13       | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12       | 1.11%   |
| Intel 82579V Gigabit Network Connection                           | 12       | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 10       | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 10       | 0.93%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 10       | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 0.83%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9        | 0.83%   |
| Realtek 802.11ac NIC                                              | 8        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 0.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 8        | 0.74%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 0.65%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 6        | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 6        | 0.56%   |
| Intel Wireless 7260                                               | 6        | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 6        | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 5        | 0.46%   |
| Microsoft XBOX ACC                                                | 5        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5        | 0.46%   |
| Intel Ethernet Controller X550                                    | 5        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 0.46%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5        | 0.46%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4        | 0.37%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4        | 0.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4        | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4        | 0.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.37%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 4        | 0.37%   |
| Intel Wireless-AC 9260                                            | 4        | 0.37%   |
| Intel Wireless 8265 / 8275                                        | 4        | 0.37%   |
| Intel Wireless 7265                                               | 4        | 0.37%   |
| Intel Wireless 3165                                               | 4        | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 0.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3        | 0.28%   |
| TP-Link 802.11ac WLAN Adapter                                     | 3        | 0.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.28%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 0.28%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 3        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 113      | 34.04%  |
| Realtek Semiconductor           | 85       | 25.6%   |
| Qualcomm Atheros                | 29       | 8.73%   |
| Broadcom                        | 18       | 5.42%   |
| Ralink Technology               | 15       | 4.52%   |
| TP-Link                         | 14       | 4.22%   |
| Ralink                          | 14       | 4.22%   |
| Microsoft                       | 7        | 2.11%   |
| ASUSTek Computer                | 7        | 2.11%   |
| Broadcom Limited                | 6        | 1.81%   |
| MediaTek                        | 5        | 1.51%   |
| NetGear                         | 3        | 0.9%    |
| Linksys                         | 2        | 0.6%    |
| Encore Electronics              | 2        | 0.6%    |
| D-Link System                   | 2        | 0.6%    |
| D-Link                          | 2        | 0.6%    |
| Sitecom Europe                  | 1        | 0.3%    |
| Sagem                           | 1        | 0.3%    |
| Qualcomm Atheros Communications | 1        | 0.3%    |
| Philips (or NXP)                | 1        | 0.3%    |
| Micro Star International        | 1        | 0.3%    |
| IMC Networks                    | 1        | 0.3%    |
| Belkin Components               | 1        | 0.3%    |
| AVM                             | 1        | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 36       | 10.78%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 18       | 5.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 16       | 4.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 13       | 3.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 10       | 2.99%   |
| Realtek 802.11ac NIC                                       | 8        | 2.4%    |
| Intel Alder Lake-S PCH CNVi WiFi                           | 8        | 2.4%    |
| Ralink MT7601U Wireless Adapter                            | 7        | 2.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 7        | 2.1%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 6        | 1.8%    |
| Intel Wireless 7260                                        | 6        | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 5        | 1.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 5        | 1.5%    |
| Microsoft XBOX ACC                                         | 5        | 1.5%    |
| Intel Tiger Lake PCH CNVi WiFi                             | 5        | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                             | 5        | 1.5%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 4        | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 4        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 4        | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 4        | 1.2%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 4        | 1.2%    |
| Intel Wireless-AC 9260                                     | 4        | 1.2%    |
| Intel Wireless 8265 / 8275                                 | 4        | 1.2%    |
| Intel Wireless 7265                                        | 4        | 1.2%    |
| Intel Wireless 3165                                        | 4        | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 3        | 0.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 3        | 0.9%    |
| TP-Link 802.11ac WLAN Adapter                              | 3        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 3        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 3        | 0.9%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 0.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 3        | 0.9%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 3        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 3        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 3        | 0.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 3        | 0.9%    |
| Intel Wireless 8260                                        | 3        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                            | 3        | 0.9%    |
| Broadcom Limited BCM4321 802.11a/b/g/n                     | 3        | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller     | 3        | 0.9%    |
| ASUS 802.11ac NIC                                          | 3        | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 2        | 0.6%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 2        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2        | 0.6%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 2        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 2        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 2        | 0.6%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter          | 2        | 0.6%    |
| Ralink RT5360 Wireless 802.11n 1T/1R                       | 2        | 0.6%    |
| Ralink RT2561/RT61 rev B 802.11g                           | 2        | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2        | 0.6%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 2        | 0.6%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 2        | 0.6%    |
| Intel Centrino Advanced-N 6235                             | 2        | 0.6%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 2        | 0.6%    |
| Broadcom BCM43225 802.11b/g/n                              | 2        | 0.6%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                      | 1        | 0.3%    |
| Sitecom Europe WL-345 Wireless USB adapter 300N X3         | 1        | 0.3%    |
| Sagem XG-76NA 802.11bg                                     | 1        | 0.3%    |
| Realtek RTL8813AE 802.11ac PCIe Wireless Network Adapter   | 1        | 0.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 400      | 56.18%  |
| Intel                    | 229      | 32.16%  |
| Qualcomm Atheros         | 22       | 3.09%   |
| Nvidia                   | 14       | 1.97%   |
| Broadcom                 | 12       | 1.69%   |
| Marvell Technology Group | 9        | 1.26%   |
| Xiaomi                   | 5        | 0.7%    |
| Aquantia                 | 5        | 0.7%    |
| Samsung Electronics      | 3        | 0.42%   |
| Mellanox Technologies    | 2        | 0.28%   |
| ASIX Electronics         | 2        | 0.28%   |
| VIA Technologies         | 1        | 0.14%   |
| LG Electronics           | 1        | 0.14%   |
| JMicron Technology       | 1        | 0.14%   |
| Huawei Technologies      | 1        | 0.14%   |
| DisplayLink              | 1        | 0.14%   |
| Chelsio Communications   | 1        | 0.14%   |
| Broadcom Limited         | 1        | 0.14%   |
| Apple                    | 1        | 0.14%   |
| American Megatrends      | 1        | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 334      | 45.14%  |
| Realtek RTL8125 2.5GbE Controller                                 | 43       | 5.81%   |
| Intel I211 Gigabit Network Connection                             | 35       | 4.73%   |
| Intel Ethernet Connection (2) I219-V                              | 26       | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26       | 3.51%   |
| Intel Ethernet Controller I225-V                                  | 20       | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 16       | 2.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12       | 1.62%   |
| Intel 82579V Gigabit Network Connection                           | 12       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10       | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 10       | 1.35%   |
| Intel Ethernet Connection (2) I218-V                              | 10       | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 1.22%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 1.22%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9        | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.95%   |
| Nvidia MCP61 Ethernet                                             | 6        | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 6        | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.68%   |
| Intel Ethernet Controller X550                                    | 5        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.41%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 3        | 0.41%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 0.27%   |
| Nvidia MCP73 Ethernet                                             | 2        | 0.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.27%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 2        | 0.27%   |
| Intel Ethernet Connection I218-V                                  | 2        | 0.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 2        | 0.27%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.27%   |
| Intel Ethernet Connection (13) I219-V                             | 2        | 0.27%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.27%   |
| Intel Ethernet Connection (11) I219-LM                            | 2        | 0.27%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 0.27%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.27%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.27%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.27%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 0.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.14%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.14%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.14%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.14%   |
| Nvidia MCP79 Ethernet                                             | 1        | 0.14%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 656      | 67.35%  |
| WiFi     | 312      | 32.03%  |
| Modem    | 3        | 0.31%   |
| Unknown  | 3        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 524      | 76.83%  |
| WiFi     | 158      | 23.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 400      | 60.15%  |
| 2     | 211      | 31.73%  |
| 3     | 43       | 6.47%   |
| 0     | 6        | 0.9%    |
| 4     | 4        | 0.6%    |
| 8     | 1        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 452      | 67.97%  |
| Yes  | 213      | 32.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 99       | 42.49%  |
| Cambridge Silicon Radio         | 46       | 19.74%  |
| Realtek Semiconductor           | 17       | 7.3%    |
| ASUSTek Computer                | 14       | 6.01%   |
| Broadcom                        | 12       | 5.15%   |
| Qualcomm Atheros Communications | 11       | 4.72%   |
| IMC Networks                    | 7        | 3%      |
| Apple                           | 6        | 2.58%   |
| MediaTek                        | 3        | 1.29%   |
| Logitech                        | 3        | 1.29%   |
| Lite-On Technology              | 3        | 1.29%   |
| TP-Link                         | 2        | 0.86%   |
| Edimax Technology               | 2        | 0.86%   |
| Dell                            | 2        | 0.86%   |
| TRENDnet                        | 1        | 0.43%   |
| Mobile Action Technology        | 1        | 0.43%   |
| Micro Star International        | 1        | 0.43%   |
| Integrated System Solution      | 1        | 0.43%   |
| Belkin Components               | 1        | 0.43%   |
| Unknown                         | 1        | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 46       | 19.74%  |
| Intel AX200 Bluetooth                                 | 29       | 12.45%  |
| Intel Bluetooth wireless interface                    | 20       | 8.58%   |
| Intel AX210 Bluetooth                                 | 16       | 6.87%   |
| Realtek Bluetooth Radio                               | 15       | 6.44%   |
| Intel AX201 Bluetooth                                 | 14       | 6.01%   |
| Qualcomm Atheros  Bluetooth Device                    | 7        | 3%      |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 7        | 3%      |
| Intel Wireless-AC 3168 Bluetooth                      | 6        | 2.58%   |
| Intel Bluetooth Device                                | 6        | 2.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5        | 2.15%   |
| IMC Networks Bluetooth Radio                          | 5        | 2.15%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 4        | 1.72%   |
| ASUS ASUS USB-BT500                                   | 4        | 1.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 4        | 1.72%   |
| MediaTek Wireless_Device                              | 3        | 1.29%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 3        | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 1.29%   |
| ASUS Bluetooth Radio                                  | 3        | 1.29%   |
| TP-Link TP-hink UB500 Adapter                         | 2        | 0.86%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 0.86%   |
| Lite-On Bluetooth Device                              | 2        | 0.86%   |
| Edimax Bluetooth Adapter                              | 2        | 0.86%   |
| Broadcom HP Bluethunder                               | 2        | 0.86%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.86%   |
| Apple Bluetooth USB Host Controller                   | 2        | 0.86%   |
| TRENDnet TBW-108UB USB Adapter                        | 1        | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 0.43%   |
| Mobile Action MA-700 Bluetooth Adapter                | 1        | 0.43%   |
| Micro Star International Bluetooth Device             | 1        | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1        | 0.43%   |
| Integrated System Solution Bluetooth Device           | 1        | 0.43%   |
| IMC Networks Wireless_Device                          | 1        | 0.43%   |
| IMC Networks Bluetooth Device                         | 1        | 0.43%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1        | 0.43%   |
| Dell BCM20702A0 Bluetooth Module                      | 1        | 0.43%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 1        | 0.43%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 1        | 0.43%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 0.43%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.43%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.43%   |
| Unknown                                               | 1        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 429      | 39.18%  |
| AMD                                          | 279      | 25.48%  |
| Nvidia                                       | 263      | 24.02%  |
| C-Media Electronics                          | 27       | 2.47%   |
| Logitech                                     | 11       | 1%      |
| Creative Labs                                | 9        | 0.82%   |
| SteelSeries ApS                              | 5        | 0.46%   |
| Micro Star International                     | 5        | 0.46%   |
| ASUSTek Computer                             | 5        | 0.46%   |
| GN Netcom                                    | 4        | 0.37%   |
| Creative Technology                          | 4        | 0.37%   |
| Corsair                                      | 4        | 0.37%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.27%   |
| Texas Instruments                            | 3        | 0.27%   |
| Razer USA                                    | 3        | 0.27%   |
| Kingston Technology                          | 3        | 0.27%   |
| JMTek                                        | 3        | 0.27%   |
| Generalplus Technology                       | 3        | 0.27%   |
| Astro Gaming                                 | 3        | 0.27%   |
| Medeli Electronics                           | 2        | 0.18%   |
| Giga-Byte Technology                         | 2        | 0.18%   |
| XMOS                                         | 1        | 0.09%   |
| Xilinx                                       | 1        | 0.09%   |
| Syntek                                       | 1        | 0.09%   |
| Sennheiser Communications                    | 1        | 0.09%   |
| PreSonus Audio Electronics                   | 1        | 0.09%   |
| Orbbec 3D Technology International           | 1        | 0.09%   |
| Native Instruments                           | 1        | 0.09%   |
| Nam Tai E&E Products                         | 1        | 0.09%   |
| KORG                                         | 1        | 0.09%   |
| Huawei Technologies                          | 1        | 0.09%   |
| Fry's Electronics                            | 1        | 0.09%   |
| Focusrite-Novation                           | 1        | 0.09%   |
| Ensoniq                                      | 1        | 0.09%   |
| Elite Silicon                                | 1        | 0.09%   |
| Elgato Systems                               | 1        | 0.09%   |
| DigiTech                                     | 1        | 0.09%   |
| Dell                                         | 1        | 0.09%   |
| Cooler Master                                | 1        | 0.09%   |
| Bose                                         | 1        | 0.09%   |
| Blue Microphones                             | 1        | 0.09%   |
| AVer Information                             | 1        | 0.09%   |
| Audient                                      | 1        | 0.09%   |
| Arturia                                      | 1        | 0.09%   |
| Apple                                        | 1        | 0.09%   |
| Unknown                                      | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 72       | 5.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 64       | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 52       | 4.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 45       | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 45       | 3.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 40       | 3.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 36       | 2.85%   |
| AMD FCH Azalia Controller                                                         | 29       | 2.3%    |
| Intel 200 Series PCH HD Audio                                                     | 26       | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                            | 26       | 2.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 26       | 2.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 25       | 1.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 23       | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 21       | 1.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18       | 1.43%   |
| Nvidia GP104 High Definition Audio Controller                                     | 17       | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 16       | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16       | 1.27%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 16       | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                            | 16       | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 16       | 1.27%   |
| AMD Navi 10 HDMI Audio                                                            | 16       | 1.27%   |
| Intel Cannon Lake PCH cAVS                                                        | 15       | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 15       | 1.19%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 15       | 1.19%   |
| Nvidia High Definition Audio Controller                                           | 14       | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                     | 13       | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 13       | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 13       | 1.03%   |
| Nvidia GA102 High Definition Audio Controller                                     | 12       | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 12       | 0.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 12       | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 12       | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 11       | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 11       | 0.87%   |
| Nvidia TU104 HD Audio Controller                                                  | 10       | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                     | 10       | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                                     | 10       | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                                     | 10       | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 10       | 0.79%   |
| Intel Audio device                                                                | 10       | 0.79%   |
| Nvidia GM204 High Definition Audio Controller                                     | 9        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 9        | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                | 9        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                     | 9        | 0.71%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 9        | 0.71%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 9        | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                                     | 8        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                | 8        | 0.63%   |
| Intel Comet Lake PCH-V cAVS                                                       | 8        | 0.63%   |
| Intel Comet Lake PCH cAVS                                                         | 7        | 0.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 7        | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 7        | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6        | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                     | 6        | 0.48%   |
| Nvidia MCP61 High Definition Audio                                                | 6        | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                                | 6        | 0.48%   |
| Nvidia GF116 High Definition Audio Controller                                     | 6        | 0.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 0.48%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 6        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 64       | 19.05%  |
| Corsair             | 59       | 17.56%  |
| Unknown             | 33       | 9.82%   |
| Samsung Electronics | 32       | 9.52%   |
| SK hynix            | 29       | 8.63%   |
| Crucial             | 26       | 7.74%   |
| G.Skill             | 24       | 7.14%   |
| Micron Technology   | 18       | 5.36%   |
| A-DATA Technology   | 7        | 2.08%   |
| Team                | 5        | 1.49%   |
| Patriot             | 5        | 1.49%   |
| Unknown             | 5        | 1.49%   |
| KETECH              | 4        | 1.19%   |
| GOODRAM             | 3        | 0.89%   |
| Unknown (ABCD)      | 2        | 0.6%    |
| Ramaxel Technology  | 2        | 0.6%    |
| PNY                 | 2        | 0.6%    |
| Nanya Technology    | 2        | 0.6%    |
| Kingmax             | 2        | 0.6%    |
| GeIL                | 2        | 0.6%    |
| ZION                | 1        | 0.3%    |
| V-Color             | 1        | 0.3%    |
| Unifosa             | 1        | 0.3%    |
| Transcend           | 1        | 0.3%    |
| Timetec             | 1        | 0.3%    |
| Qumo                | 1        | 0.3%    |
| Kllisre             | 1        | 0.3%    |
| Hewlett-Packard     | 1        | 0.3%    |
| Exceleram           | 1        | 0.3%    |
| Elpida              | 1        | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 8        | 2.22%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 5        | 1.39%   |
| Unknown                                                        | 5        | 1.39%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s         | 4        | 1.11%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 3        | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3        | 0.83%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 3        | 0.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 3        | 0.83%   |
| KETECH RAM Module 8GB DIMM DDR3 1600MT/s                       | 3        | 0.83%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 3        | 0.83%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 3        | 0.83%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s         | 3        | 0.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 3        | 0.83%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 2        | 0.55%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s          | 2        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s | 2        | 0.55%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s             | 2        | 0.55%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2        | 0.55%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 2        | 0.55%   |
| SK hynix RAM DMT451E6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2        | 0.55%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                      | 2        | 0.55%   |
| Samsung RAM M391A2K43BB1-CTD 16384MB DIMM DDR4 3600MT/s        | 2        | 0.55%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s                 | 2        | 0.55%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s            | 2        | 0.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s         | 2        | 0.55%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s            | 2        | 0.55%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s            | 2        | 0.55%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 2        | 0.55%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 2        | 0.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 2        | 0.55%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 2        | 0.55%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s            | 2        | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s         | 2        | 0.55%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 2        | 0.55%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 2        | 0.55%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s          | 2        | 0.55%   |
| Kingston RAM 99U5471-031.A00LF 8GB DIMM DDR3 1333MT/s          | 2        | 0.55%   |
| KETECH RAM Module 2GB DIMM DDR3 1600MT/s                       | 2        | 0.55%   |
| Goodram RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s             | 2        | 0.55%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 2        | 0.55%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s          | 2        | 0.55%   |
| Crucial RAM BL8G24C16U4B.8FB 8GB DIMM DDR4 2400MT/s            | 2        | 0.55%   |
| Corsair RAM CMY8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s            | 2        | 0.55%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s            | 2        | 0.55%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 2        | 0.55%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 0.55%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s          | 2        | 0.55%   |
| ZION RAM ZION4GBDDR3PC1600 4GB DIMM DDR3 1400MT/s              | 1        | 0.28%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s             | 1        | 0.28%   |
| Unknown RAM Module 8GB DIMM DDR3 800MT/s                       | 1        | 0.28%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.28%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.28%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 1        | 0.28%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1        | 0.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1        | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                       | 1        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 152      | 51.88%  |
| DDR3    | 97       | 33.11%  |
| Unknown | 17       | 5.8%    |
| SDRAM   | 11       | 3.75%   |
| DDR2    | 10       | 3.41%   |
| LPDDR4  | 3        | 1.02%   |
| DDR     | 2        | 0.68%   |
| DRAM    | 1        | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 266      | 93.01%  |
| SODIMM  | 18       | 6.29%   |
| RIMM    | 1        | 0.35%   |
| FB-DIMM | 1        | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 111      | 35.02%  |
| 4096   | 87       | 27.44%  |
| 16384  | 63       | 19.87%  |
| 2048   | 29       | 9.15%   |
| 32768  | 18       | 5.68%   |
| 1024   | 7        | 2.21%   |
| 131072 | 1        | 0.32%   |
| 65536  | 1        | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 60       | 18.69%  |
| 3200    | 38       | 11.84%  |
| 1333    | 34       | 10.59%  |
| 3600    | 33       | 10.28%  |
| 2400    | 23       | 7.17%   |
| 2667    | 20       | 6.23%   |
| 2133    | 18       | 5.61%   |
| 1867    | 9        | 2.8%    |
| 3466    | 8        | 2.49%   |
| 2666    | 8        | 2.49%   |
| 800     | 8        | 2.49%   |
| 3000    | 7        | 2.18%   |
| 2933    | 5        | 1.56%   |
| 667     | 5        | 1.56%   |
| 3400    | 4        | 1.25%   |
| 1800    | 4        | 1.25%   |
| 1067    | 4        | 1.25%   |
| 1066    | 3        | 0.93%   |
| Unknown | 3        | 0.93%   |
| 4800    | 2        | 0.62%   |
| 3733    | 2        | 0.62%   |
| 3467    | 2        | 0.62%   |
| 2800    | 2        | 0.62%   |
| 2733    | 2        | 0.62%   |
| 2000    | 2        | 0.62%   |
| 1866    | 2        | 0.62%   |
| 1400    | 2        | 0.62%   |
| 5600    | 1        | 0.31%   |
| 4600    | 1        | 0.31%   |
| 4333    | 1        | 0.31%   |
| 4000    | 1        | 0.31%   |
| 3666    | 1        | 0.31%   |
| 3266    | 1        | 0.31%   |
| 3066    | 1        | 0.31%   |
| 2048    | 1        | 0.31%   |
| 1334    | 1        | 0.31%   |
| 400     | 1        | 0.31%   |
| 333     | 1        | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Samsung Electronics   | 7        | 26.92%  |
| Hewlett-Packard       | 7        | 26.92%  |
| Brother Industries    | 6        | 23.08%  |
| Canon                 | 3        | 11.54%  |
| Seiko Epson           | 2        | 7.69%   |
| Lexmark International | 1        | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung Composite Device             | 3        | 11.11%  |
| Seiko Epson L220 Series              | 1        | 3.7%    |
| Seiko Epson ET-2720 Series           | 1        | 3.7%    |
| Samsung SCX-4600 Series              | 1        | 3.7%    |
| Samsung ML-216x Series Laser Printer | 1        | 3.7%    |
| Samsung M267x 287x Series            | 1        | 3.7%    |
| Samsung M2070 Series                 | 1        | 3.7%    |
| Lexmark International B2442dw        | 1        | 3.7%    |
| HP OfficeJet 8700                    | 1        | 3.7%    |
| HP OfficeJet 5500 series             | 1        | 3.7%    |
| HP OfficeJet 3830 series             | 1        | 3.7%    |
| HP LaserJet Professional P1102w      | 1        | 3.7%    |
| HP LaserJet 1320                     | 1        | 3.7%    |
| HP ENVY 4500 series                  | 1        | 3.7%    |
| HP DeskJet 1110 series               | 1        | 3.7%    |
| Canon MF632C/634C                    | 1        | 3.7%    |
| Canon MF4410                         | 1        | 3.7%    |
| Canon MF4320-4350                    | 1        | 3.7%    |
| Canon iR2004/2204 UFRII LT           | 1        | 3.7%    |
| Brother MFC-L2700DW                  | 1        | 3.7%    |
| Brother HL-5340 series               | 1        | 3.7%    |
| Brother HL-52x0 series               | 1        | 3.7%    |
| Brother HL-2030 Laser Printer        | 1        | 3.7%    |
| Brother HL-1440 Laser Printer        | 1        | 3.7%    |
| Brother HL-1200 series               | 1        | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 4        | 80%     |
| Seiko Epson | 1        | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1        | 20%     |
| Canon CanoScan LiDE 220               | 1        | 20%     |
| Canon CanoScan LiDE 200               | 1        | 20%     |
| Canon CanoScan LiDE 110               | 1        | 20%     |
| Canon CanoScan LiDE 100               | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 52       | 40.31%  |
| Sunplus Innovation Technology          | 10       | 7.75%   |
| Microdia                               | 7        | 5.43%   |
| Apple                                  | 6        | 4.65%   |
| Generalplus Technology                 | 5        | 3.88%   |
| Z-Star Microelectronics                | 4        | 3.1%    |
| Razer USA                              | 4        | 3.1%    |
| Microsoft                              | 4        | 3.1%    |
| Realtek Semiconductor                  | 3        | 2.33%   |
| Creative Technology                    | 3        | 2.33%   |
| Chicony Electronics                    | 3        | 2.33%   |
| Samsung Electronics                    | 2        | 1.55%   |
| Pixart Imaging                         | 2        | 1.55%   |
| Hewlett-Packard                        | 2        | 1.55%   |
| 2M UVC CAMERA                          | 2        | 1.55%   |
| WaveRider Communications               | 1        | 0.78%   |
| Trust                                  | 1        | 0.78%   |
| Tobii Technology AB                    | 1        | 0.78%   |
| Sony                                   | 1        | 0.78%   |
| MacroSilicon                           | 1        | 0.78%   |
| KYE Systems (Mouse Systems)            | 1        | 0.78%   |
| Jieli Technology                       | 1        | 0.78%   |
| Huawei Technologies                    | 1        | 0.78%   |
| HD USB Camera                          | 1        | 0.78%   |
| Guillemot                              | 1        | 0.78%   |
| Google                                 | 1        | 0.78%   |
| Genesys Logic                          | 1        | 0.78%   |
| GEMBIRD                                | 1        | 0.78%   |
| eMeet                                  | 1        | 0.78%   |
| Cubeternet                             | 1        | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.78%   |
| AVer Information                       | 1        | 0.78%   |
| Arkmicro Technologies                  | 1        | 0.78%   |
| ARC International                      | 1        | 0.78%   |
| Alcor Micro                            | 1        | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                       | 13       | 10.08%  |
| Logitech Webcam C270                              | 9        | 6.98%   |
| Logitech C922 Pro Stream Webcam                   | 9        | 6.98%   |
| Sunplus Integrated_Webcam_HD                      | 5        | 3.88%   |
| Generalplus WEB CAM                               | 5        | 3.88%   |
| Apple iPhone 5/5C/5S/6/SE                         | 5        | 3.88%   |
| Sunplus Full HD webcam                            | 3        | 2.33%   |
| Razer USA Gaming Webcam [Kiyo]                    | 3        | 2.33%   |
| Logitech HD Webcam C525                           | 3        | 2.33%   |
| Logitech C920 PRO HD Webcam                       | 3        | 2.33%   |
| Z-Star Venus USB2.0 Camera                        | 2        | 1.55%   |
| Samsung Galaxy A5 (MTP)                           | 2        | 1.55%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 2        | 1.55%   |
| Microsoft LifeCam HD-3000                         | 2        | 1.55%   |
| Microdia USB 2.0 Camera                           | 2        | 1.55%   |
| Microdia Amcrest AWC2198 USB Webcam               | 2        | 1.55%   |
| Logitech Webcam C170                              | 2        | 1.55%   |
| Chicony HP High Definition 1MP Webcam             | 2        | 1.55%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam              | 2        | 1.55%   |
| Z-Star Vimicro USB Camera (Altair)                | 1        | 0.78%   |
| Z-Star Integrated Camera                          | 1        | 0.78%   |
| WaveRider USB 2.0 Camera                          | 1        | 0.78%   |
| Trust USB Camera                                  | 1        | 0.78%   |
| Tobii AB EyeChip                                  | 1        | 0.78%   |
| Sunplus USB2.0 Camera                             | 1        | 0.78%   |
| Sunplus USB camera                                | 1        | 0.78%   |
| Sony CEVCECM                                      | 1        | 0.78%   |
| Realtek NYK NEMESIS                               | 1        | 0.78%   |
| Realtek Integrated_Webcam_FHD                     | 1        | 0.78%   |
| Realtek FULL HD 1080P Webcam                      | 1        | 0.78%   |
| Razer USA Razer Ripsaw HD - Game Capture Card     | 1        | 0.78%   |
| Microsoft LifeCam VX-500 [1357]                   | 1        | 0.78%   |
| Microsoft LifeCam Cinema                          | 1        | 0.78%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 0.78%   |
| Microdia Integrated Camera                        | 1        | 0.78%   |
| Microdia HDP Webcam USB                           | 1        | 0.78%   |
| MacroSilicon USB3.0 HD VIDEO                      | 1        | 0.78%   |
| Logitech Webcam C930e                             | 1        | 0.78%   |
| Logitech Webcam C925e                             | 1        | 0.78%   |
| Logitech Webcam C600                              | 1        | 0.78%   |
| Logitech Webcam C210                              | 1        | 0.78%   |
| Logitech StreamCam                                | 1        | 0.78%   |
| Logitech QuickCam Express                         | 1        | 0.78%   |
| Logitech QuickCam E 3500                          | 1        | 0.78%   |
| Logitech Logi 4K Stream Edition                   | 1        | 0.78%   |
| Logitech HD Webcam C910                           | 1        | 0.78%   |
| Logitech HD Webcam C615                           | 1        | 0.78%   |
| Logitech HD Webcam C510                           | 1        | 0.78%   |
| Logitech C930c                                    | 1        | 0.78%   |
| Logitech B525 HD Webcam                           | 1        | 0.78%   |
| KYE Systems (Mouse Systems) FaceCam 1000X         | 1        | 0.78%   |
| Jieli USB PHY 2.0                                 | 1        | 0.78%   |
| Huawei HiCamera                                   | 1        | 0.78%   |
| HP Webcam HD 2300                                 | 1        | 0.78%   |
| HP Webcam                                         | 1        | 0.78%   |
| HD USB Camera HD USB Camera                       | 1        | 0.78%   |
| Guillemot Hercules HD Twist                       | 1        | 0.78%   |
| Google Nexus/Pixel Device (MTP + debug)           | 1        | 0.78%   |
| Genesys Logic USB2.0 UVC PC Camera                | 1        | 0.78%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 50%     |
| Dell                  | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan ELAN:Fingerprint                          | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 542      | 81.14%  |
| 1     | 109      | 16.32%  |
| 2     | 9        | 1.35%   |
| 3     | 7        | 1.05%   |
| 5     | 1        | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 56       | 39.72%  |
| Net/wireless             | 34       | 24.11%  |
| Unassigned class         | 18       | 12.77%  |
| Sound                    | 9        | 6.38%   |
| Communication controller | 7        | 4.96%   |
| Bluetooth                | 4        | 2.84%   |
| Net/ethernet             | 2        | 1.42%   |
| Multimedia controller    | 2        | 1.42%   |
| Chipcard                 | 2        | 1.42%   |
| Card reader              | 2        | 1.42%   |
| Camera                   | 2        | 1.42%   |
| Storage/raid             | 1        | 0.71%   |
| Network                  | 1        | 0.71%   |
| Fingerprint reader       | 1        | 0.71%   |

