Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_35/Desktop/README.md) and [notebooks](/Dist/Fedora_35/Notebook/README.md).

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
| Dell          | 0T7D40 A01                  | Desktop     | [4ce7ea3bb0](https://linux-hardware.org/?probe=4ce7ea3bb0) | Dec 31, 2021 |
| Dell          | Latitude E5570              | Notebook    | [34af93663b](https://linux-hardware.org/?probe=34af93663b) | Dec 31, 2021 |
| Intel         | SKYBAY                      | Desktop     | [043f80cded](https://linux-hardware.org/?probe=043f80cded) | Dec 31, 2021 |
| Google        | Coral                       | Notebook    | [23a0352176](https://linux-hardware.org/?probe=23a0352176) | Dec 31, 2021 |
| ASUSTek       | TP300LD                     | Notebook    | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [6a91ead443](https://linux-hardware.org/?probe=6a91ead443) | Dec 31, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [ec26febbae](https://linux-hardware.org/?probe=ec26febbae) | Dec 31, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [cd66e486be](https://linux-hardware.org/?probe=cd66e486be) | Dec 31, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [298d5a0323](https://linux-hardware.org/?probe=298d5a0323) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | Notebook    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [c1eeaec01b](https://linux-hardware.org/?probe=c1eeaec01b) | Dec 30, 2021 |
| Google        | Chell                       | Notebook    | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [bfd79da0e0](https://linux-hardware.org/?probe=bfd79da0e0) | Dec 30, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [00f3b181b3](https://linux-hardware.org/?probe=00f3b181b3) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [c3497fe5bd](https://linux-hardware.org/?probe=c3497fe5bd) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [49f7093e8c](https://linux-hardware.org/?probe=49f7093e8c) | Dec 29, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [c539559392](https://linux-hardware.org/?probe=c539559392) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | Notebook    | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | Notebook    | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [47edce55a4](https://linux-hardware.org/?probe=47edce55a4) | Dec 29, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [5cbf982807](https://linux-hardware.org/?probe=5cbf982807) | Dec 29, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [e3297eb51f](https://linux-hardware.org/?probe=e3297eb51f) | Dec 29, 2021 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [433a512192](https://linux-hardware.org/?probe=433a512192) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | Notebook    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| MSI           | H81M-E33                    | Desktop     | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Toshiba       | Satellite L12-C-104         | Notebook    | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [707835b4ff](https://linux-hardware.org/?probe=707835b4ff) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [f255947b6f](https://linux-hardware.org/?probe=f255947b6f) | Dec 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [572bbe8d7b](https://linux-hardware.org/?probe=572bbe8d7b) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [61dd257cc7](https://linux-hardware.org/?probe=61dd257cc7) | Dec 26, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [e076af5bf8](https://linux-hardware.org/?probe=e076af5bf8) | Dec 26, 2021 |
| HP            | 2000                        | Notebook    | [e3408eb743](https://linux-hardware.org/?probe=e3408eb743) | Dec 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1e8ce2ec6d](https://linux-hardware.org/?probe=1e8ce2ec6d) | Dec 25, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Latitude 7410               | Notebook    | [71a96bfc8f](https://linux-hardware.org/?probe=71a96bfc8f) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| Cube          | i18-L                       | Notebook    | [6770cf2a44](https://linux-hardware.org/?probe=6770cf2a44) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ca0f62a716](https://linux-hardware.org/?probe=ca0f62a716) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | Notebook    | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [44dd4eee41](https://linux-hardware.org/?probe=44dd4eee41) | Dec 24, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [91ee24853b](https://linux-hardware.org/?probe=91ee24853b) | Dec 23, 2021 |
| LDLC          | Mercure MH                  | Notebook    | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | Notebook    | [abba53c091](https://linux-hardware.org/?probe=abba53c091) | Dec 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1962ddfdb4](https://linux-hardware.org/?probe=1962ddfdb4) | Dec 23, 2021 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [6efc5bede0](https://linux-hardware.org/?probe=6efc5bede0) | Dec 23, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [4cd052492e](https://linux-hardware.org/?probe=4cd052492e) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| HP            | 250 G1                      | Notebook    | [da8e31b740](https://linux-hardware.org/?probe=da8e31b740) | Dec 23, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [18ea7c2e7e](https://linux-hardware.org/?probe=18ea7c2e7e) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [9b2acc6ea1](https://linux-hardware.org/?probe=9b2acc6ea1) | Dec 22, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1975ee2fc0](https://linux-hardware.org/?probe=1975ee2fc0) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [5f27936a88](https://linux-hardware.org/?probe=5f27936a88) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7fc27f5255](https://linux-hardware.org/?probe=7fc27f5255) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [42d4ee98ce](https://linux-hardware.org/?probe=42d4ee98ce) | Dec 21, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e0f736fe3b](https://linux-hardware.org/?probe=e0f736fe3b) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8cd9d762c9](https://linux-hardware.org/?probe=8cd9d762c9) | Dec 20, 2021 |
| Dell          | 0YJPT1 A00                  | Desktop     | [a92e152a7c](https://linux-hardware.org/?probe=a92e152a7c) | Dec 20, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| Notebook      | N24_25JU                    | Notebook    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [58f36b9637](https://linux-hardware.org/?probe=58f36b9637) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ddb3571ec6](https://linux-hardware.org/?probe=ddb3571ec6) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bb28c266ec](https://linux-hardware.org/?probe=bb28c266ec) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [e2ce1d7284](https://linux-hardware.org/?probe=e2ce1d7284) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [e380536aac](https://linux-hardware.org/?probe=e380536aac) | Dec 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [87399b5e8b](https://linux-hardware.org/?probe=87399b5e8b) | Dec 19, 2021 |
| Intel         | NUC6i7KYB H90766-410        | Mini pc     | [c5f8ba42bd](https://linux-hardware.org/?probe=c5f8ba42bd) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [25c7dd18f2](https://linux-hardware.org/?probe=25c7dd18f2) | Dec 19, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| JINGSHA       | Unknown                     | Desktop     | [13da82798c](https://linux-hardware.org/?probe=13da82798c) | Dec 18, 2021 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | Notebook    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | Notebook    | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Precision 5540              | Notebook    | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [305153f0a8](https://linux-hardware.org/?probe=305153f0a8) | Dec 17, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [cda7a2c35c](https://linux-hardware.org/?probe=cda7a2c35c) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [e985e04d6d](https://linux-hardware.org/?probe=e985e04d6d) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [290b1d081b](https://linux-hardware.org/?probe=290b1d081b) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [aba6548652](https://linux-hardware.org/?probe=aba6548652) | Dec 16, 2021 |
| HP            | 805D                        | Desktop     | [dfdc70512c](https://linux-hardware.org/?probe=dfdc70512c) | Dec 16, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [30a4a58c5d](https://linux-hardware.org/?probe=30a4a58c5d) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [ff779fe08f](https://linux-hardware.org/?probe=ff779fe08f) | Dec 16, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Dell          | Latitude 5500               | Notebook    | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | Notebook    | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| ASUSTek       | K43U                        | Notebook    | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [2cabe8184b](https://linux-hardware.org/?probe=2cabe8184b) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| Dell          | 0RY007                      | Desktop     | [f3cb490147](https://linux-hardware.org/?probe=f3cb490147) | Dec 14, 2021 |
| Lenovo        | 3111 NOK                    | Mini pc     | [b599c84248](https://linux-hardware.org/?probe=b599c84248) | Dec 14, 2021 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [b2dc7c9e05](https://linux-hardware.org/?probe=b2dc7c9e05) | Dec 14, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4290797f32](https://linux-hardware.org/?probe=4290797f32) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [fb79be9e00](https://linux-hardware.org/?probe=fb79be9e00) | Dec 14, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [1ffa9927c7](https://linux-hardware.org/?probe=1ffa9927c7) | Dec 14, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [a1c2190f8d](https://linux-hardware.org/?probe=a1c2190f8d) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Dell          | Latitude 7300               | Notebook    | [23f38f8a7d](https://linux-hardware.org/?probe=23f38f8a7d) | Dec 14, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [8d121836c9](https://linux-hardware.org/?probe=8d121836c9) | Dec 14, 2021 |
| HP            | 2B2B                        | Desktop     | [bf929a4359](https://linux-hardware.org/?probe=bf929a4359) | Dec 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ae8a45bc5a](https://linux-hardware.org/?probe=ae8a45bc5a) | Dec 14, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [fd53be96e6](https://linux-hardware.org/?probe=fd53be96e6) | Dec 13, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | Notebook    | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [27bbd905bf](https://linux-hardware.org/?probe=27bbd905bf) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| Dell          | Latitude 7290               | Notebook    | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5975d86599](https://linux-hardware.org/?probe=5975d86599) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [169e6793c2](https://linux-hardware.org/?probe=169e6793c2) | Dec 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [021525201e](https://linux-hardware.org/?probe=021525201e) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | Notebook    | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| ASUSTek       | P6T                         | Desktop     | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [54058ac7e2](https://linux-hardware.org/?probe=54058ac7e2) | Dec 11, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [6d5c35bf9f](https://linux-hardware.org/?probe=6d5c35bf9f) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4fba952635](https://linux-hardware.org/?probe=4fba952635) | Dec 11, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [d7faa88624](https://linux-hardware.org/?probe=d7faa88624) | Dec 11, 2021 |
| Dell          | Latitude 7300               | Notebook    | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f3d37d4574](https://linux-hardware.org/?probe=f3d37d4574) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | Notebook    | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8ae1043ce6](https://linux-hardware.org/?probe=8ae1043ce6) | Dec 10, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [bcb885e52b](https://linux-hardware.org/?probe=bcb885e52b) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [4fe4d7393e](https://linux-hardware.org/?probe=4fe4d7393e) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [a81ed5c974](https://linux-hardware.org/?probe=a81ed5c974) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4ba265c070](https://linux-hardware.org/?probe=4ba265c070) | Dec 10, 2021 |
| ASUSTek       | P6T                         | Desktop     | [71ce922273](https://linux-hardware.org/?probe=71ce922273) | Dec 09, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [439a97ec9b](https://linux-hardware.org/?probe=439a97ec9b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [195283a93a](https://linux-hardware.org/?probe=195283a93a) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [d0070c39c4](https://linux-hardware.org/?probe=d0070c39c4) | Dec 09, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c486c9645b](https://linux-hardware.org/?probe=c486c9645b) | Dec 09, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1881f48bd1](https://linux-hardware.org/?probe=1881f48bd1) | Dec 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [73645a62d6](https://linux-hardware.org/?probe=73645a62d6) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [f7ca8d84ca](https://linux-hardware.org/?probe=f7ca8d84ca) | Dec 08, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b673a5f067](https://linux-hardware.org/?probe=b673a5f067) | Dec 08, 2021 |
| ASUSTek       | P6T                         | Desktop     | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [80630ad3ed](https://linux-hardware.org/?probe=80630ad3ed) | Dec 08, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [3880c485fb](https://linux-hardware.org/?probe=3880c485fb) | Dec 08, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [fcfdb2cedc](https://linux-hardware.org/?probe=fcfdb2cedc) | Dec 08, 2021 |
| Unknown       | Unknown Product             | Soc         | [a85a563642](https://linux-hardware.org/?probe=a85a563642) | Dec 08, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [82926e68a4](https://linux-hardware.org/?probe=82926e68a4) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [78b37822bc](https://linux-hardware.org/?probe=78b37822bc) | Dec 08, 2021 |
| Sony          | SVE1711Z1RB                 | Notebook    | [adb25167ea](https://linux-hardware.org/?probe=adb25167ea) | Dec 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [9c98446833](https://linux-hardware.org/?probe=9c98446833) | Dec 07, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [809152313d](https://linux-hardware.org/?probe=809152313d) | Dec 07, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [58c6a86730](https://linux-hardware.org/?probe=58c6a86730) | Dec 07, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [775bafdec8](https://linux-hardware.org/?probe=775bafdec8) | Dec 07, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [0523a58e8a](https://linux-hardware.org/?probe=0523a58e8a) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | Notebook    | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [a6722f2ff3](https://linux-hardware.org/?probe=a6722f2ff3) | Dec 07, 2021 |
| Sony          | SVE1713S1RW                 | Notebook    | [41775b7503](https://linux-hardware.org/?probe=41775b7503) | Dec 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8b704c0d3f](https://linux-hardware.org/?probe=8b704c0d3f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [b5a282abf6](https://linux-hardware.org/?probe=b5a282abf6) | Dec 06, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | Desktop     | [5393b5ad7a](https://linux-hardware.org/?probe=5393b5ad7a) | Dec 06, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [4fc7bc5515](https://linux-hardware.org/?probe=4fc7bc5515) | Dec 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [42fe75c227](https://linux-hardware.org/?probe=42fe75c227) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [9e878d83a3](https://linux-hardware.org/?probe=9e878d83a3) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [0a06cba7c5](https://linux-hardware.org/?probe=0a06cba7c5) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | Desktop     | [82cd98ea5a](https://linux-hardware.org/?probe=82cd98ea5a) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | Desktop     | [07f484651e](https://linux-hardware.org/?probe=07f484651e) | Dec 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [05538278b6](https://linux-hardware.org/?probe=05538278b6) | Dec 06, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [40640fd92f](https://linux-hardware.org/?probe=40640fd92f) | Dec 06, 2021 |
| Framework     | Laptop                      | Notebook    | [64dc54fbc6](https://linux-hardware.org/?probe=64dc54fbc6) | Dec 06, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [9e6cd42a9f](https://linux-hardware.org/?probe=9e6cd42a9f) | Dec 05, 2021 |
| Dell          | Inspiron 7586               | Convertible | [53604c12d1](https://linux-hardware.org/?probe=53604c12d1) | Dec 05, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [18ae64d44d](https://linux-hardware.org/?probe=18ae64d44d) | Dec 05, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [b296e2a320](https://linux-hardware.org/?probe=b296e2a320) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | Notebook    | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [f254ee88c6](https://linux-hardware.org/?probe=f254ee88c6) | Dec 05, 2021 |
| Dell          | Latitude E6530              | Notebook    | [de5ad42b2f](https://linux-hardware.org/?probe=de5ad42b2f) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [15e8e28073](https://linux-hardware.org/?probe=15e8e28073) | Dec 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b006a547c8](https://linux-hardware.org/?probe=b006a547c8) | Dec 04, 2021 |
| MSI           | Z87M GAMING                 | Desktop     | [4ef67e0560](https://linux-hardware.org/?probe=4ef67e0560) | Dec 04, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [6239b4eda5](https://linux-hardware.org/?probe=6239b4eda5) | Dec 04, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | Desktop     | [ce556a2535](https://linux-hardware.org/?probe=ce556a2535) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [511a349d7f](https://linux-hardware.org/?probe=511a349d7f) | Dec 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f90f047538](https://linux-hardware.org/?probe=f90f047538) | Dec 03, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [fd20b7fc56](https://linux-hardware.org/?probe=fd20b7fc56) | Dec 03, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [8c6244cb77](https://linux-hardware.org/?probe=8c6244cb77) | Dec 03, 2021 |
| Toshiba       | Satellite C70-A-K2W         | Notebook    | [8e46f67032](https://linux-hardware.org/?probe=8e46f67032) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | Notebook    | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | Notebook    | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f53047cd0d](https://linux-hardware.org/?probe=f53047cd0d) | Dec 02, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Gateway       | SX2185                      | Desktop     | [70e907b207](https://linux-hardware.org/?probe=70e907b207) | Dec 02, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [33ef9926a3](https://linux-hardware.org/?probe=33ef9926a3) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [4189e1f255](https://linux-hardware.org/?probe=4189e1f255) | Dec 02, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [ffecd77f3a](https://linux-hardware.org/?probe=ffecd77f3a) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [508352ad4a](https://linux-hardware.org/?probe=508352ad4a) | Dec 02, 2021 |
| Lenovo        | ThinkPad L390 20NSS43600    | Notebook    | [e9aae12812](https://linux-hardware.org/?probe=e9aae12812) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d5c6c6edee](https://linux-hardware.org/?probe=d5c6c6edee) | Dec 01, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [94b9d8b093](https://linux-hardware.org/?probe=94b9d8b093) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [240ca54dfb](https://linux-hardware.org/?probe=240ca54dfb) | Dec 01, 2021 |
| HP            | 2B2E A01                    | All in one  | [6f6101b39b](https://linux-hardware.org/?probe=6f6101b39b) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [24800d20ac](https://linux-hardware.org/?probe=24800d20ac) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [610709bb66](https://linux-hardware.org/?probe=610709bb66) | Nov 30, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [f940ae414d](https://linux-hardware.org/?probe=f940ae414d) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [7ad53e55ba](https://linux-hardware.org/?probe=7ad53e55ba) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [b2d55bd445](https://linux-hardware.org/?probe=b2d55bd445) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [23ae32af07](https://linux-hardware.org/?probe=23ae32af07) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [074ec973ae](https://linux-hardware.org/?probe=074ec973ae) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [2ceb61c052](https://linux-hardware.org/?probe=2ceb61c052) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [80bbba47f6](https://linux-hardware.org/?probe=80bbba47f6) | Nov 29, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [95cb3fe8b3](https://linux-hardware.org/?probe=95cb3fe8b3) | Nov 29, 2021 |
| Acer          | Predator G9-793             | Notebook    | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Dell          | G5 5590                     | Notebook    | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [959af2b8dd](https://linux-hardware.org/?probe=959af2b8dd) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | Notebook    | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [a91b7dd31b](https://linux-hardware.org/?probe=a91b7dd31b) | Nov 29, 2021 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| Notebook      | NB50TL                      | Notebook    | [15a716161c](https://linux-hardware.org/?probe=15a716161c) | Nov 28, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [b75e21b247](https://linux-hardware.org/?probe=b75e21b247) | Nov 28, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [8e5c4cc27b](https://linux-hardware.org/?probe=8e5c4cc27b) | Nov 28, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [6a4ed949e9](https://linux-hardware.org/?probe=6a4ed949e9) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude 7420               | Notebook    | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [e83680db56](https://linux-hardware.org/?probe=e83680db56) | Nov 28, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [eabdd46893](https://linux-hardware.org/?probe=eabdd46893) | Nov 28, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d813ffb878](https://linux-hardware.org/?probe=d813ffb878) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [783b49e383](https://linux-hardware.org/?probe=783b49e383) | Nov 28, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [67f32be00d](https://linux-hardware.org/?probe=67f32be00d) | Nov 27, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [d980b32136](https://linux-hardware.org/?probe=d980b32136) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [ef8336f76a](https://linux-hardware.org/?probe=ef8336f76a) | Nov 26, 2021 |
| Dell          | Precision 5550              | Notebook    | [41caa6a4a0](https://linux-hardware.org/?probe=41caa6a4a0) | Nov 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| ASUSTek       | K54C                        | Notebook    | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Acer          | AP714-51T                   | Notebook    | [3fe9bcf889](https://linux-hardware.org/?probe=3fe9bcf889) | Nov 26, 2021 |
| Acer          | AP714-51T                   | Notebook    | [406001fc85](https://linux-hardware.org/?probe=406001fc85) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [a000027ce6](https://linux-hardware.org/?probe=a000027ce6) | Nov 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [366fe373c9](https://linux-hardware.org/?probe=366fe373c9) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [beff046f56](https://linux-hardware.org/?probe=beff046f56) | Nov 25, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [395718db33](https://linux-hardware.org/?probe=395718db33) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [2a96a2a7af](https://linux-hardware.org/?probe=2a96a2a7af) | Nov 25, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [f4f5c37779](https://linux-hardware.org/?probe=f4f5c37779) | Nov 25, 2021 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [b6ffc90d4e](https://linux-hardware.org/?probe=b6ffc90d4e) | Nov 25, 2021 |
| Sony          | VPCF131FM                   | Notebook    | [f0ba5e0db2](https://linux-hardware.org/?probe=f0ba5e0db2) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| HP            | 3561                        | All in one  | [5ff1d7a72e](https://linux-hardware.org/?probe=5ff1d7a72e) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | Notebook    | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [b90083da69](https://linux-hardware.org/?probe=b90083da69) | Nov 24, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [e606757d4a](https://linux-hardware.org/?probe=e606757d4a) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [96fec5d214](https://linux-hardware.org/?probe=96fec5d214) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [35801f40df](https://linux-hardware.org/?probe=35801f40df) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [79ee4911cb](https://linux-hardware.org/?probe=79ee4911cb) | Nov 24, 2021 |
| MSI           | A55M-E33                    | Desktop     | [e6616870b6](https://linux-hardware.org/?probe=e6616870b6) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| HP            | 1906                        | Desktop     | [8ec5c16fc7](https://linux-hardware.org/?probe=8ec5c16fc7) | Nov 24, 2021 |
| HP            | 83E1                        | Desktop     | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | Desktop     | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | Notebook    | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | Notebook    | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| HP            | 1906                        | Desktop     | [90499fe34d](https://linux-hardware.org/?probe=90499fe34d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Gigabyte      | GA-MA790X-UD4               | Desktop     | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b58b567113](https://linux-hardware.org/?probe=b58b567113) | Nov 22, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [7b9225653f](https://linux-hardware.org/?probe=7b9225653f) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Lenovo        | 3746 No DPK                 | All in one  | [44d15ef318](https://linux-hardware.org/?probe=44d15ef318) | Nov 22, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [ece0600e5d](https://linux-hardware.org/?probe=ece0600e5d) | Nov 22, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [c686d7d85c](https://linux-hardware.org/?probe=c686d7d85c) | Nov 22, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [8fc4f44be5](https://linux-hardware.org/?probe=8fc4f44be5) | Nov 22, 2021 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a20fe0f647](https://linux-hardware.org/?probe=a20fe0f647) | Nov 21, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [f779165258](https://linux-hardware.org/?probe=f779165258) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [8cc8502887](https://linux-hardware.org/?probe=8cc8502887) | Nov 21, 2021 |
| Google        | Relm                        | Notebook    | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [683697e6ee](https://linux-hardware.org/?probe=683697e6ee) | Nov 21, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [2fa52f3236](https://linux-hardware.org/?probe=2fa52f3236) | Nov 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [faec9a8f8b](https://linux-hardware.org/?probe=faec9a8f8b) | Nov 21, 2021 |
| HP            | Pavilion 17                 | Notebook    | [2d69072cdf](https://linux-hardware.org/?probe=2d69072cdf) | Nov 20, 2021 |
| HP            | 3048h                       | Desktop     | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| Dell          | Latitude 5490               | Notebook    | [cbe23836bf](https://linux-hardware.org/?probe=cbe23836bf) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [44d1a95b0b](https://linux-hardware.org/?probe=44d1a95b0b) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [3b34362c42](https://linux-hardware.org/?probe=3b34362c42) | Nov 19, 2021 |
| Acer          | Swift SF514-51              | Notebook    | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [8bf7660808](https://linux-hardware.org/?probe=8bf7660808) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [a524ba65b5](https://linux-hardware.org/?probe=a524ba65b5) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7e7b7d381e](https://linux-hardware.org/?probe=7e7b7d381e) | Nov 19, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d0aea280e7](https://linux-hardware.org/?probe=d0aea280e7) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [02b2e4cb00](https://linux-hardware.org/?probe=02b2e4cb00) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [181c56512d](https://linux-hardware.org/?probe=181c56512d) | Nov 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d7a5775f61](https://linux-hardware.org/?probe=d7a5775f61) | Nov 19, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [d111fd1549](https://linux-hardware.org/?probe=d111fd1549) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [fbedd3af33](https://linux-hardware.org/?probe=fbedd3af33) | Nov 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [01a15306b9](https://linux-hardware.org/?probe=01a15306b9) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [bb6f44b058](https://linux-hardware.org/?probe=bb6f44b058) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [839b5c24aa](https://linux-hardware.org/?probe=839b5c24aa) | Nov 19, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [12f769ed4c](https://linux-hardware.org/?probe=12f769ed4c) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Dell          | Precision 5510              | Notebook    | [1d46cced08](https://linux-hardware.org/?probe=1d46cced08) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [70ee93daac](https://linux-hardware.org/?probe=70ee93daac) | Nov 19, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [f9b7bdfef8](https://linux-hardware.org/?probe=f9b7bdfef8) | Nov 19, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6a1607ab9d](https://linux-hardware.org/?probe=6a1607ab9d) | Nov 18, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [dc150f9fba](https://linux-hardware.org/?probe=dc150f9fba) | Nov 18, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c8a6893780](https://linux-hardware.org/?probe=c8a6893780) | Nov 18, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d9f71fda8f](https://linux-hardware.org/?probe=d9f71fda8f) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [3b2165faa8](https://linux-hardware.org/?probe=3b2165faa8) | Nov 18, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [46c44d537a](https://linux-hardware.org/?probe=46c44d537a) | Nov 18, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [01f7a4c33d](https://linux-hardware.org/?probe=01f7a4c33d) | Nov 18, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f6dc8337e7](https://linux-hardware.org/?probe=f6dc8337e7) | Nov 18, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [05020e1e61](https://linux-hardware.org/?probe=05020e1e61) | Nov 18, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [5f40fb240a](https://linux-hardware.org/?probe=5f40fb240a) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [dbde83db50](https://linux-hardware.org/?probe=dbde83db50) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [04db0a2350](https://linux-hardware.org/?probe=04db0a2350) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Dell          | Latitude E7270              | Notebook    | [70a4c30534](https://linux-hardware.org/?probe=70a4c30534) | Nov 17, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [eefe2dc8be](https://linux-hardware.org/?probe=eefe2dc8be) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [61734716ea](https://linux-hardware.org/?probe=61734716ea) | Nov 16, 2021 |
| HP            | ENVY Laptop 15t-ep000       | Notebook    | [02c2ed5954](https://linux-hardware.org/?probe=02c2ed5954) | Nov 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c4763ca2a5](https://linux-hardware.org/?probe=c4763ca2a5) | Nov 16, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [db85b885ae](https://linux-hardware.org/?probe=db85b885ae) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6b1f5ce8b7](https://linux-hardware.org/?probe=6b1f5ce8b7) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [ccf125eb47](https://linux-hardware.org/?probe=ccf125eb47) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [6398858488](https://linux-hardware.org/?probe=6398858488) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3412d5cf0b](https://linux-hardware.org/?probe=3412d5cf0b) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bdd9599f2f](https://linux-hardware.org/?probe=bdd9599f2f) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [1119a0805e](https://linux-hardware.org/?probe=1119a0805e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [06f896ff98](https://linux-hardware.org/?probe=06f896ff98) | Nov 15, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [97ed26b846](https://linux-hardware.org/?probe=97ed26b846) | Nov 15, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [9ef2a8f6d7](https://linux-hardware.org/?probe=9ef2a8f6d7) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [516e448510](https://linux-hardware.org/?probe=516e448510) | Nov 14, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [8b02ecc2b6](https://linux-hardware.org/?probe=8b02ecc2b6) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | Notebook    | [70b84217bd](https://linux-hardware.org/?probe=70b84217bd) | Nov 14, 2021 |
| Dell          | Precision 3541              | Notebook    | [a21fd45ac3](https://linux-hardware.org/?probe=a21fd45ac3) | Nov 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [54bb479f64](https://linux-hardware.org/?probe=54bb479f64) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | Notebook    | [d88aea84ef](https://linux-hardware.org/?probe=d88aea84ef) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2bca77430e](https://linux-hardware.org/?probe=2bca77430e) | Nov 14, 2021 |
| Dell          | Latitude 5511               | Notebook    | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | Notebook    | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [68633b9bf5](https://linux-hardware.org/?probe=68633b9bf5) | Nov 13, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2142069a51](https://linux-hardware.org/?probe=2142069a51) | Nov 13, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [bc6a3771aa](https://linux-hardware.org/?probe=bc6a3771aa) | Nov 13, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | Notebook    | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [e1cc8b1ee3](https://linux-hardware.org/?probe=e1cc8b1ee3) | Nov 13, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [40de24f0e5](https://linux-hardware.org/?probe=40de24f0e5) | Nov 13, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [5cbec68d6e](https://linux-hardware.org/?probe=5cbec68d6e) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | Notebook    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| ASUSTek       | H61M-CS                     | Desktop     | [22858e9ab9](https://linux-hardware.org/?probe=22858e9ab9) | Nov 13, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [04e988d138](https://linux-hardware.org/?probe=04e988d138) | Nov 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [85929a9a18](https://linux-hardware.org/?probe=85929a9a18) | Nov 12, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [5991ba5f44](https://linux-hardware.org/?probe=5991ba5f44) | Nov 12, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Dell          | Precision 5510              | Notebook    | [80bbc48bce](https://linux-hardware.org/?probe=80bbc48bce) | Nov 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e85856bbef](https://linux-hardware.org/?probe=e85856bbef) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| AMI           | Intel                       | Convertible | [670ce3c062](https://linux-hardware.org/?probe=670ce3c062) | Nov 11, 2021 |
| System76      | Oryx Pro                    | Notebook    | [77cf902290](https://linux-hardware.org/?probe=77cf902290) | Nov 11, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [61afe68685](https://linux-hardware.org/?probe=61afe68685) | Nov 11, 2021 |
| Dell          | Latitude E7440              | Notebook    | [e907f0bbf1](https://linux-hardware.org/?probe=e907f0bbf1) | Nov 11, 2021 |
| ASUSTek       | X202EV                      | Notebook    | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Dell          | 0DXJD9 A00                  | Desktop     | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [f5ceaaf6fe](https://linux-hardware.org/?probe=f5ceaaf6fe) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | Notebook    | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [99ece77400](https://linux-hardware.org/?probe=99ece77400) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [ca1489298b](https://linux-hardware.org/?probe=ca1489298b) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | Notebook    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [81605538eb](https://linux-hardware.org/?probe=81605538eb) | Nov 09, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [1c63b3b4ce](https://linux-hardware.org/?probe=1c63b3b4ce) | Nov 09, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [09cae8a245](https://linux-hardware.org/?probe=09cae8a245) | Nov 09, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [cb4e2271c0](https://linux-hardware.org/?probe=cb4e2271c0) | Nov 09, 2021 |
| Toshiba       | NB255                       | Notebook    | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| HP            | 2215                        | Desktop     | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4a2a86c38](https://linux-hardware.org/?probe=d4a2a86c38) | Nov 09, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fdbec54288](https://linux-hardware.org/?probe=fdbec54288) | Nov 08, 2021 |
| HP            | Notebook                    | Notebook    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [5f5424fe84](https://linux-hardware.org/?probe=5f5424fe84) | Nov 08, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [74b5acd6cd](https://linux-hardware.org/?probe=74b5acd6cd) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [a7510caa6d](https://linux-hardware.org/?probe=a7510caa6d) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [2eebb6842a](https://linux-hardware.org/?probe=2eebb6842a) | Nov 08, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | Notebook    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [65e1d14e1c](https://linux-hardware.org/?probe=65e1d14e1c) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8988b7e735](https://linux-hardware.org/?probe=8988b7e735) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Acer          | Aspire Z3-615               | All in one  | [fa3d223e18](https://linux-hardware.org/?probe=fa3d223e18) | Nov 07, 2021 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [6269149643](https://linux-hardware.org/?probe=6269149643) | Nov 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [6a2354e970](https://linux-hardware.org/?probe=6a2354e970) | Nov 07, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef16e3ad0f](https://linux-hardware.org/?probe=ef16e3ad0f) | Nov 07, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [43d8e3d9d8](https://linux-hardware.org/?probe=43d8e3d9d8) | Nov 07, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [b4d29007be](https://linux-hardware.org/?probe=b4d29007be) | Nov 07, 2021 |
| ABIT          | AX78                        | Desktop     | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| Dell          | Latitude E7440              | Notebook    | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [34a03f8adf](https://linux-hardware.org/?probe=34a03f8adf) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| HP            | 250 G1                      | Notebook    | [1c52b861c7](https://linux-hardware.org/?probe=1c52b861c7) | Nov 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001XIX     | Notebook    | [98d8c0fbdb](https://linux-hardware.org/?probe=98d8c0fbdb) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Notebook      | W65_W67RZ                   | Notebook    | [153b2a920d](https://linux-hardware.org/?probe=153b2a920d) | Nov 05, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [f8ce8bca36](https://linux-hardware.org/?probe=f8ce8bca36) | Nov 05, 2021 |
| MSI           | Z97M-G43                    | Desktop     | [7b0e15a051](https://linux-hardware.org/?probe=7b0e15a051) | Nov 05, 2021 |
| HONOR         | NBD-WXX9                    | Notebook    | [1030fbbff6](https://linux-hardware.org/?probe=1030fbbff6) | Nov 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ad6e327cf5](https://linux-hardware.org/?probe=ad6e327cf5) | Nov 05, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [32aedc2d5b](https://linux-hardware.org/?probe=32aedc2d5b) | Nov 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| ASUSTek       | TP410UAR                    | Convertible | [a4d5174826](https://linux-hardware.org/?probe=a4d5174826) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | Notebook    | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8e06f2617d](https://linux-hardware.org/?probe=8e06f2617d) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1a2dda8941](https://linux-hardware.org/?probe=1a2dda8941) | Nov 05, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [ed53f501e6](https://linux-hardware.org/?probe=ed53f501e6) | Nov 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [fa84d0d544](https://linux-hardware.org/?probe=fa84d0d544) | Nov 04, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [f29c3d7003](https://linux-hardware.org/?probe=f29c3d7003) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [a795236afd](https://linux-hardware.org/?probe=a795236afd) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [5baf0ce3af](https://linux-hardware.org/?probe=5baf0ce3af) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [6ee78bd50a](https://linux-hardware.org/?probe=6ee78bd50a) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | Notebook    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| Dell          | Studio 1537                 | Notebook    | [d040c159b8](https://linux-hardware.org/?probe=d040c159b8) | Nov 04, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [00a97d0eba](https://linux-hardware.org/?probe=00a97d0eba) | Nov 03, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [1d421060d7](https://linux-hardware.org/?probe=1d421060d7) | Nov 03, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4478f8c509](https://linux-hardware.org/?probe=4478f8c509) | Nov 03, 2021 |
| Dell          | Precision 5510              | Notebook    | [eb702ce1e6](https://linux-hardware.org/?probe=eb702ce1e6) | Nov 03, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [dedf8fbd8c](https://linux-hardware.org/?probe=dedf8fbd8c) | Nov 03, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [fe22676441](https://linux-hardware.org/?probe=fe22676441) | Nov 03, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [c68c3a5c3b](https://linux-hardware.org/?probe=c68c3a5c3b) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [10bd49d9c0](https://linux-hardware.org/?probe=10bd49d9c0) | Nov 03, 2021 |
| Dell          | Latitude 5590               | Notebook    | [5bc1ed5978](https://linux-hardware.org/?probe=5bc1ed5978) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0297ef158a](https://linux-hardware.org/?probe=0297ef158a) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | Notebook    | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | Notebook    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3acf5c243f](https://linux-hardware.org/?probe=3acf5c243f) | Nov 03, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [10a45363fe](https://linux-hardware.org/?probe=10a45363fe) | Nov 03, 2021 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [f30e20e67b](https://linux-hardware.org/?probe=f30e20e67b) | Nov 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | Notebook    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [4aae9bdc03](https://linux-hardware.org/?probe=4aae9bdc03) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [40df244ae9](https://linux-hardware.org/?probe=40df244ae9) | Nov 02, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [28b152bb19](https://linux-hardware.org/?probe=28b152bb19) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Framework     | Laptop                      | Notebook    | [04db6c2222](https://linux-hardware.org/?probe=04db6c2222) | Oct 29, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [5b10037da5](https://linux-hardware.org/?probe=5b10037da5) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | Notebook    | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f67b298ab](https://linux-hardware.org/?probe=5f67b298ab) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [136c409f1a](https://linux-hardware.org/?probe=136c409f1a) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [ae8daa788a](https://linux-hardware.org/?probe=ae8daa788a) | Oct 27, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [91c5853577](https://linux-hardware.org/?probe=91c5853577) | Oct 25, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Alienware     | Area-51m R2                 | Notebook    | [c3f94d8599](https://linux-hardware.org/?probe=c3f94d8599) | Oct 24, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [98bd384a42](https://linux-hardware.org/?probe=98bd384a42) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [9383081522](https://linux-hardware.org/?probe=9383081522) | Oct 22, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [9932dd3c21](https://linux-hardware.org/?probe=9932dd3c21) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Foxconn       | H81MXV FAB A                | Desktop     | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [faa49a332b](https://linux-hardware.org/?probe=faa49a332b) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | Notebook    | [4dbc231901](https://linux-hardware.org/?probe=4dbc231901) | Oct 18, 2021 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [746401b748](https://linux-hardware.org/?probe=746401b748) | Oct 18, 2021 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [b1c4af0594](https://linux-hardware.org/?probe=b1c4af0594) | Oct 17, 2021 |
| GPU Compan... | GWTN156-1                   | Notebook    | [3cb0b09b48](https://linux-hardware.org/?probe=3cb0b09b48) | Oct 17, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [ac488ba246](https://linux-hardware.org/?probe=ac488ba246) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [362e1d3b99](https://linux-hardware.org/?probe=362e1d3b99) | Oct 15, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [bc716e921b](https://linux-hardware.org/?probe=bc716e921b) | Oct 15, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [01ce3b252c](https://linux-hardware.org/?probe=01ce3b252c) | Oct 14, 2021 |
| Dell          | Precision 5550              | Notebook    | [15a0f61f84](https://linux-hardware.org/?probe=15a0f61f84) | Oct 14, 2021 |
| Unknown       | Unknown Product             | Soc         | [bf8abdfb09](https://linux-hardware.org/?probe=bf8abdfb09) | Oct 14, 2021 |
| Unknown       | Unknown Product             | Soc         | [3a844f7153](https://linux-hardware.org/?probe=3a844f7153) | Oct 14, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2ff2eb607a](https://linux-hardware.org/?probe=2ff2eb607a) | Oct 14, 2021 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [b9971b685a](https://linux-hardware.org/?probe=b9971b685a) | Oct 12, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4bb5ac9410](https://linux-hardware.org/?probe=4bb5ac9410) | Oct 12, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [d4acf59f3b](https://linux-hardware.org/?probe=d4acf59f3b) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7b26df9bc4](https://linux-hardware.org/?probe=7b26df9bc4) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [2eeb05ff03](https://linux-hardware.org/?probe=2eeb05ff03) | Oct 09, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [43ded3a853](https://linux-hardware.org/?probe=43ded3a853) | Oct 09, 2021 |
| HP            | ENVY Laptop 15t-ep000       | Notebook    | [f9b69ffa3d](https://linux-hardware.org/?probe=f9b69ffa3d) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | Notebook    | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b3d0295208](https://linux-hardware.org/?probe=b3d0295208) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [75d34f09c4](https://linux-hardware.org/?probe=75d34f09c4) | Oct 06, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [146866c629](https://linux-hardware.org/?probe=146866c629) | Oct 06, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [17a03c217e](https://linux-hardware.org/?probe=17a03c217e) | Oct 04, 2021 |
| Lenovo        | ThinkPad L390 20NUS01W00    | Convertible | [880201a9eb](https://linux-hardware.org/?probe=880201a9eb) | Oct 04, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [db435ab99c](https://linux-hardware.org/?probe=db435ab99c) | Oct 03, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [08adba2c54](https://linux-hardware.org/?probe=08adba2c54) | Oct 02, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [1dbb7762f6](https://linux-hardware.org/?probe=1dbb7762f6) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Dell          | Studio 1537                 | Notebook    | [aae900457c](https://linux-hardware.org/?probe=aae900457c) | Oct 01, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Framework     | Laptop                      | Notebook    | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook      | N2x0WU                      | Notebook    | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | Notebook    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [0b68c3f5c3](https://linux-hardware.org/?probe=0b68c3f5c3) | Sep 20, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP            | G42                         | Notebook    | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP            | ZBook 15u G5                | Notebook    | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2766de5f8a](https://linux-hardware.org/?probe=2766de5f8a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | Notebook    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell          | Latitude E5470              | Notebook    | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| AZW           | GK mini                     | Mini pc     | [995cc09b8d](https://linux-hardware.org/?probe=995cc09b8d) | Aug 22, 2021 |
| AZW           | GK mini                     | Mini pc     | [2024a6712e](https://linux-hardware.org/?probe=2024a6712e) | Aug 22, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| HP            | 8055                        | Desktop     | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| Notebook      | P377SM-A                    | Notebook    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| Notebook      | P377SM-A                    | Notebook    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook      | P377SM-A                    | Notebook    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [7a294509de](https://linux-hardware.org/?probe=7a294509de) | May 15, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [4238374bcc](https://linux-hardware.org/?probe=4238374bcc) | Apr 26, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [89892d4957](https://linux-hardware.org/?probe=89892d4957) | Apr 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [97c124c8a3](https://linux-hardware.org/?probe=97c124c8a3) | Apr 18, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | Notebook    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c0901f4607](https://linux-hardware.org/?probe=c0901f4607) | Mar 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.15.6-200.fc35.x86_64                                        | 77        | 12.3%   |
| 5.14.16-301.fc35.x86_64                                       | 67        | 10.7%   |
| 5.14.18-300.fc35.x86_64                                       | 60        | 9.58%   |
| 5.14.10-300.fc35.x86_64                                       | 56        | 8.95%   |
| 5.14.17-301.fc35.x86_64                                       | 48        | 7.67%   |
| 5.14.14-300.fc35.x86_64                                       | 39        | 6.23%   |
| 5.15.8-200.fc35.x86_64                                        | 29        | 4.63%   |
| 5.14.15-300.fc35.x86_64                                       | 29        | 4.63%   |
| 5.15.11-200.fc35.x86_64                                       | 28        | 4.47%   |
| 5.15.10-200.fc35.x86_64                                       | 23        | 3.67%   |
| 5.15.5-200.fc35.x86_64                                        | 22        | 3.51%   |
| 5.15.4-201.fc35.x86_64                                        | 21        | 3.35%   |
| 5.15.7-200.fc35.x86_64                                        | 17        | 2.72%   |
| 5.14.9-300.fc35.x86_64                                        | 15        | 2.4%    |
| 5.14.0-60.fc35.x86_64                                         | 10        | 1.6%    |
| 5.14.11-300.fc35.x86_64                                       | 6         | 0.96%   |
| 5.14.0-0.rc5.42.fc35.x86_64                                   | 5         | 0.8%    |
| 5.14.7-300.fc35.x86_64                                        | 4         | 0.64%   |
| 5.14.6-300.fc35.x86_64                                        | 3         | 0.48%   |
| 5.14.12-300.fc35.x86_64                                       | 3         | 0.48%   |
| 5.14.0-0.rc6.46.fc35.x86_64                                   | 3         | 0.48%   |
| 5.15.6-200.rog.fc35.x86_64                                    | 2         | 0.32%   |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 2         | 0.32%   |
| 5.14.5-300.fc35.x86_64                                        | 2         | 0.32%   |
| 5.14.3-300.fc35.x86_64                                        | 2         | 0.32%   |
| 5.14.1-300.fc35.x86_64                                        | 2         | 0.32%   |
| 5.12.0-0.rc7.189.fc35.x86_64                                  | 2         | 0.32%   |
| 5.16.0-0.rc6.41.vanilla.1.fc35.x86_64                         | 1         | 0.16%   |
| 5.16.0-0.rc5.35.vanilla.1.fc35.x86_64                         | 1         | 0.16%   |
| 5.16.0-0.rc2.18.vanilla.1.fc35.x86_64                         | 1         | 0.16%   |
| 5.16.0-0.rc1.20211115git8ab774587903.14.vanilla.1.fc35.x86_64 | 1         | 0.16%   |
| 5.15.8_tkg_pds                                                | 1         | 0.16%   |
| 5.15.6-301.fc35.x86_64                                        | 1         | 0.16%   |
| 5.15.6-250.vanilla.1.fc35.x86_64                              | 1         | 0.16%   |
| 5.15.6-200.fc35.aarch64                                       | 1         | 0.16%   |
| 5.15.4-xm1.0.fc35.x86_64                                      | 1         | 0.16%   |
| 5.15.4-200.fc35.x86_64                                        | 1         | 0.16%   |
| 5.15.2_tkg_bmq                                                | 1         | 0.16%   |
| 5.15.2-225.vanilla.1.fc35.x86_64                              | 1         | 0.16%   |
| 5.15.11-250.vanilla.1.fc35.x86_64                             | 1         | 0.16%   |
| 5.15.0-60.fc36.x86_64                                         | 1         | 0.16%   |
| 5.15.0-500.chinfo.fc35.x86_64                                 | 1         | 0.16%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.vanilla.1.fc35.x86_64 | 1         | 0.16%   |
| 5.14.9-300.fc35.aarch64                                       | 1         | 0.16%   |
| 5.14.8-xm1cacule.0.fc35.x86_64                                | 1         | 0.16%   |
| 5.14.8-lqx1.0.fc35.x86_64                                     | 1         | 0.16%   |
| 5.14.20-300.fc35.x86_64                                       | 1         | 0.16%   |
| 5.14.18-301.fsync.fc35.x86_64                                 | 1         | 0.16%   |
| 5.14.16-201.fc34.x86_64                                       | 1         | 0.16%   |
| 5.14.15-300.rog.fc35.x86_64                                   | 1         | 0.16%   |
| 5.14.13_MY                                                    | 1         | 0.16%   |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64           | 1         | 0.16%   |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64           | 1         | 0.16%   |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64            | 1         | 0.16%   |
| 5.13.9-200.fc34.x86_64                                        | 1         | 0.16%   |
| 5.13.7-200.fc34.x86_64                                        | 1         | 0.16%   |
| 5.13.4-200.fc34.x86_64                                        | 1         | 0.16%   |
| 5.13.19-200.fc35.x86_64                                       | 1         | 0.16%   |
| 5.13.19-200.fc34.x86_64                                       | 1         | 0.16%   |
| 5.13.0-58.fc35.x86_64                                         | 1         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.6  | 82        | 13.23%  |
| 5.14.16 | 68        | 10.97%  |
| 5.14.18 | 61        | 9.84%   |
| 5.14.10 | 56        | 9.03%   |
| 5.14.17 | 48        | 7.74%   |
| 5.14.14 | 39        | 6.29%   |
| 5.15.8  | 30        | 4.84%   |
| 5.14.15 | 30        | 4.84%   |
| 5.15.11 | 29        | 4.68%   |
| 5.15.5  | 24        | 3.87%   |
| 5.15.4  | 23        | 3.71%   |
| 5.15.10 | 23        | 3.71%   |
| 5.14.0  | 20        | 3.23%   |
| 5.15.7  | 17        | 2.74%   |
| 5.14.9  | 16        | 2.58%   |
| 5.12.0  | 7         | 1.13%   |
| 5.14.11 | 6         | 0.97%   |
| 5.14.7  | 4         | 0.65%   |
| 5.13.0  | 4         | 0.65%   |
| 5.16.0  | 3         | 0.48%   |
| 5.15.0  | 3         | 0.48%   |
| 5.14.6  | 3         | 0.48%   |
| 5.14.12 | 3         | 0.48%   |
| 5.15.2  | 2         | 0.32%   |
| 5.14.8  | 2         | 0.32%   |
| 5.14.5  | 2         | 0.32%   |
| 5.14.3  | 2         | 0.32%   |
| 5.14.1  | 2         | 0.32%   |
| 5.13.19 | 2         | 0.32%   |
| 5.14.20 | 1         | 0.16%   |
| 5.14.13 | 1         | 0.16%   |
| 5.13.9  | 1         | 0.16%   |
| 5.13.7  | 1         | 0.16%   |
| 5.13.4  | 1         | 0.16%   |
| 5.12.8  | 1         | 0.16%   |
| 5.11.18 | 1         | 0.16%   |
| 5.11.12 | 1         | 0.16%   |
| 5.10.23 | 1         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 353       | 58.25%  |
| 5.15    | 230       | 37.95%  |
| 5.13    | 9         | 1.49%   |
| 5.12    | 8         | 1.32%   |
| 5.16    | 3         | 0.5%    |
| 5.11    | 2         | 0.33%   |
| 5.10    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 571       | 99.65%  |
| aarch64 | 2         | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 435       | 74.61%  |
| KDE5          | 62        | 10.63%  |
| Unknown       | 28        | 4.8%    |
| MATE          | 16        | 2.74%   |
| X-Cinnamon    | 14        | 2.4%    |
| XFCE          | 7         | 1.2%    |
| KDE           | 5         | 0.86%   |
| Cinnamon      | 5         | 0.86%   |
| sway          | 2         | 0.34%   |
| GNOME Classic | 2         | 0.34%   |
| Pantheon      | 1         | 0.17%   |
| openbox       | 1         | 0.17%   |
| LXQt          | 1         | 0.17%   |
| LXDE          | 1         | 0.17%   |
| i3            | 1         | 0.17%   |
| fluxbox       | 1         | 0.17%   |
| DWM           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 374       | 64.15%  |
| X11     | 182       | 31.22%  |
| Tty     | 15        | 2.57%   |
| Unknown | 12        | 2.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 294       | 50.87%  |
| GDM     | 205       | 35.47%  |
| LightDM | 40        | 6.92%   |
| SDDM    | 37        | 6.4%    |
| XDM     | 1         | 0.17%   |
| TDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 308       | 53.47%  |
| en_GB      | 44        | 7.64%   |
| ru_RU      | 36        | 6.25%   |
| pt_BR      | 26        | 4.51%   |
| de_DE      | 20        | 3.47%   |
| fr_FR      | 17        | 2.95%   |
| it_IT      | 14        | 2.43%   |
| es_ES      | 14        | 2.43%   |
| en_CA      | 13        | 2.26%   |
| pl_PL      | 9         | 1.56%   |
| en_AU      | 6         | 1.04%   |
| sv_SE      | 5         | 0.87%   |
| nl_BE      | 4         | 0.69%   |
| cs_CZ      | 4         | 0.69%   |
| ru_UA      | 3         | 0.52%   |
| nl_NL      | 3         | 0.52%   |
| es_CL      | 3         | 0.52%   |
| en_NZ      | 3         | 0.52%   |
| en_IN      | 3         | 0.52%   |
| C          | 3         | 0.52%   |
| zh_CN      | 2         | 0.35%   |
| uk_UA      | 2         | 0.35%   |
| pt_PT      | 2         | 0.35%   |
| nb_NO      | 2         | 0.35%   |
| fr_CA      | 2         | 0.35%   |
| es_MX      | 2         | 0.35%   |
| es_CO      | 2         | 0.35%   |
| es_AR      | 2         | 0.35%   |
| en_IL      | 2         | 0.35%   |
| de_CH      | 2         | 0.35%   |
| Unknown    | 2         | 0.35%   |
| tr_TR      | 1         | 0.17%   |
| pa_IN      | 1         | 0.17%   |
| ja_JP      | 1         | 0.17%   |
| hu_HU      | 1         | 0.17%   |
| ga_IE      | 1         | 0.17%   |
| fr_CH      | 1         | 0.17%   |
| fi_FI      | 1         | 0.17%   |
| es_VE      | 1         | 0.17%   |
| es_GT      | 1         | 0.17%   |
| en_US.UTF8 | 1         | 0.17%   |
| en_IE      | 1         | 0.17%   |
| en_DK      | 1         | 0.17%   |
| de_AT      | 1         | 0.17%   |
| da_DK      | 1         | 0.17%   |
| ca_ES      | 1         | 0.17%   |
| ar_SA      | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 464       | 80.42%  |
| BIOS | 113       | 19.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 417       | 72.4%   |
| Ext4    | 140       | 24.31%  |
| Xfs     | 15        | 2.6%    |
| Overlay | 2         | 0.35%   |
| Ext3    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 289       | 50%     |
| GPT     | 254       | 43.94%  |
| MBR     | 35        | 6.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 512       | 88.28%  |
| Yes       | 68        | 11.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 469       | 81.28%  |
| Yes       | 108       | 18.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 128       | 22.34%  |
| Dell                   | 81        | 14.14%  |
| Hewlett-Packard        | 71        | 12.39%  |
| ASUSTek Computer       | 69        | 12.04%  |
| Gigabyte Technology    | 46        | 8.03%   |
| MSI                    | 39        | 6.81%   |
| Acer                   | 24        | 4.19%   |
| Apple                  | 20        | 3.49%   |
| HUAWEI                 | 11        | 1.92%   |
| Notebook               | 9         | 1.57%   |
| ASRock                 | 8         | 1.4%    |
| Intel                  | 7         | 1.22%   |
| Toshiba                | 5         | 0.87%   |
| Fujitsu                | 5         | 0.87%   |
| Sony                   | 3         | 0.52%   |
| Google                 | 3         | 0.52%   |
| Framework              | 3         | 0.52%   |
| Unknown                | 3         | 0.52%   |
| XFX                    | 2         | 0.35%   |
| System76               | 2         | 0.35%   |
| Samsung Electronics    | 2         | 0.35%   |
| Microsoft              | 2         | 0.35%   |
| ECS                    | 2         | 0.35%   |
| ZOTAC                  | 1         | 0.17%   |
| TUXEDO                 | 1         | 0.17%   |
| Supermicro             | 1         | 0.17%   |
| SiComputer             | 1         | 0.17%   |
| Seco                   | 1         | 0.17%   |
| Razer                  | 1         | 0.17%   |
| Positivo Bahia - VAIO  | 1         | 0.17%   |
| Positivo               | 1         | 0.17%   |
| Pegatron               | 1         | 0.17%   |
| Login Informatica      | 1         | 0.17%   |
| LG Electronics         | 1         | 0.17%   |
| LDLC                   | 1         | 0.17%   |
| JINGSHA                | 1         | 0.17%   |
| Huanan                 | 1         | 0.17%   |
| HONOR                  | 1         | 0.17%   |
| Hampoo                 | 1         | 0.17%   |
| GPU Company            | 1         | 0.17%   |
| Gateway                | 1         | 0.17%   |
| Fujitsu Siemens        | 1         | 0.17%   |
| Foxconn                | 1         | 0.17%   |
| Cube                   | 1         | 0.17%   |
| BESSTAR Tech           | 1         | 0.17%   |
| AZW                    | 1         | 0.17%   |
| AVITA                  | 1         | 0.17%   |
| Avell High Performance | 1         | 0.17%   |
| AMI                    | 1         | 0.17%   |
| Alienware              | 1         | 0.17%   |
| ABIT                   | 1         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 5         | 0.87%   |
| Unknown                                    | 4         | 0.7%    |
| MSI MS-7C56                                | 3         | 0.52%   |
| Framework Laptop                           | 3         | 0.52%   |
| Dell XPS 17 9700                           | 3         | 0.52%   |
| Dell Latitude E7440                        | 3         | 0.52%   |
| ASUS ROG Strix G513QY_G513QY               | 3         | 0.52%   |
| MSI MS-7C91                                | 2         | 0.35%   |
| MSI MS-7C52                                | 2         | 0.35%   |
| MSI MS-7B93                                | 2         | 0.35%   |
| MSI MS-7B10                                | 2         | 0.35%   |
| MSI MS-7A33                                | 2         | 0.35%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.35%   |
| Lenovo Yoga 9 14ITL5 82BG                  | 2         | 0.35%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 2         | 0.35%   |
| Lenovo ThinkPad P1 Gen 3 20TJS53A00        | 2         | 0.35%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW       | 2         | 0.35%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2          | 2         | 0.35%   |
| Lenovo IdeaPad 530S-14IKB 81EU             | 2         | 0.35%   |
| Lenovo IdeaPad 320-15ISK 80XH              | 2         | 0.35%   |
| HUAWEI KLVL-WXX9                           | 2         | 0.35%   |
| HUAWEI HVY-WXX9                            | 2         | 0.35%   |
| HP ProBook 470 G5                          | 2         | 0.35%   |
| HP Laptop 15s-fq2xxx                       | 2         | 0.35%   |
| HP ENVY x360 Convertible 13-ay0xxx         | 2         | 0.35%   |
| HP EliteBook x360 1030 G2                  | 2         | 0.35%   |
| Gigabyte Z390 I AORUS PRO WIFI             | 2         | 0.35%   |
| Gigabyte X570 AORUS MASTER                 | 2         | 0.35%   |
| Gigabyte H97M-D3H                          | 2         | 0.35%   |
| Gigabyte B450M DS3H                        | 2         | 0.35%   |
| Dell XPS 15 9570                           | 2         | 0.35%   |
| Dell XPS 13 9380                           | 2         | 0.35%   |
| Dell XPS 13 9310 2-in-1                    | 2         | 0.35%   |
| Dell XPS 13 7390                           | 2         | 0.35%   |
| Dell Precision 5510                        | 2         | 0.35%   |
| Dell OptiPlex 7010                         | 2         | 0.35%   |
| Dell OptiPlex 3020                         | 2         | 0.35%   |
| Dell Latitude E5570                        | 2         | 0.35%   |
| Dell Latitude E5470                        | 2         | 0.35%   |
| Dell Latitude 7300                         | 2         | 0.35%   |
| Dell Inspiron 5558                         | 2         | 0.35%   |
| ASUS TUF GAMING B550-PLUS                  | 2         | 0.35%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 2         | 0.35%   |
| Apple MacPro5,1                            | 2         | 0.35%   |
| Apple Macmini5,1                           | 2         | 0.35%   |
| Apple MacBookPro9,2                        | 2         | 0.35%   |
| Apple MacBookPro7,1                        | 2         | 0.35%   |
| Apple MacBookPro6,2                        | 2         | 0.35%   |
| Acer Swift SF314-43                        | 2         | 0.35%   |
| Acer Nitro AN515-55                        | 2         | 0.35%   |
| ZOTAC B410                                 | 1         | 0.17%   |
| XFX nForce 780i 3-Way SLI                  | 1         | 0.17%   |
| XFX MI-A78S-8209 Ver1.1                    | 1         | 0.17%   |
| TUXEDO InfinityBook S 15 Gen6              | 1         | 0.17%   |
| Toshiba TECRA Z50-A                        | 1         | 0.17%   |
| Toshiba Satellite L12-C-104                | 1         | 0.17%   |
| Toshiba Satellite C855-12R                 | 1         | 0.17%   |
| Toshiba Satellite C70-A-K2W                | 1         | 0.17%   |
| Toshiba NB255                              | 1         | 0.17%   |
| System76 Pangolin                          | 1         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 75        | 13.09%  |
| Lenovo IdeaPad     | 21        | 3.66%   |
| Dell XPS           | 19        | 3.32%   |
| Dell Latitude      | 19        | 3.32%   |
| Dell Inspiron      | 19        | 3.32%   |
| ASUS ROG           | 18        | 3.14%   |
| Dell OptiPlex      | 13        | 2.27%   |
| HP Pavilion        | 12        | 2.09%   |
| HP EliteBook       | 11        | 1.92%   |
| Acer Aspire        | 10        | 1.75%   |
| HP Laptop          | 9         | 1.57%   |
| HP ENVY            | 9         | 1.57%   |
| ASUS PRIME         | 9         | 1.57%   |
| HP ProBook         | 8         | 1.4%    |
| Acer Swift         | 7         | 1.22%   |
| Lenovo Yoga        | 6         | 1.05%   |
| Gigabyte X570      | 6         | 1.05%   |
| ASUS VivoBook      | 6         | 1.05%   |
| Dell Precision     | 5         | 0.87%   |
| ASUS TUF           | 5         | 0.87%   |
| ASUS All           | 5         | 0.87%   |
| Acer Nitro         | 5         | 0.87%   |
| Lenovo ThinkCentre | 4         | 0.7%    |
| Lenovo Legion      | 4         | 0.7%    |
| HP ZBook           | 4         | 0.7%    |
| Unknown            | 4         | 0.7%    |
| Toshiba Satellite  | 3         | 0.52%   |
| MSI MS-7C56        | 3         | 0.52%   |
| Lenovo ThinkBook   | 3         | 0.52%   |
| Lenovo IdeaPadFlex | 3         | 0.52%   |
| HP EliteDesk       | 3         | 0.52%   |
| Gigabyte Z390      | 3         | 0.52%   |
| Framework Laptop   | 3         | 0.52%   |
| Dell Vostro        | 3         | 0.52%   |
| Notebook NH5x      | 2         | 0.35%   |
| MSI MS-7C91        | 2         | 0.35%   |
| MSI MS-7C52        | 2         | 0.35%   |
| MSI MS-7B93        | 2         | 0.35%   |
| MSI MS-7B10        | 2         | 0.35%   |
| MSI MS-7A33        | 2         | 0.35%   |
| MSI Modern         | 2         | 0.35%   |
| Microsoft Surface  | 2         | 0.35%   |
| Lenovo IdeaCentre  | 2         | 0.35%   |
| HUAWEI KLVL-WXX9   | 2         | 0.35%   |
| HUAWEI HVY-WXX9    | 2         | 0.35%   |
| HP OMEN            | 2         | 0.35%   |
| Gigabyte TRX40     | 2         | 0.35%   |
| Gigabyte H97M-D3H  | 2         | 0.35%   |
| Gigabyte B550      | 2         | 0.35%   |
| Gigabyte B450M     | 2         | 0.35%   |
| Gigabyte B450      | 2         | 0.35%   |
| Fujitsu LIFEBOOK   | 2         | 0.35%   |
| Fujitsu ESPRIMO    | 2         | 0.35%   |
| Dell G5            | 2         | 0.35%   |
| ASUS Maximus       | 2         | 0.35%   |
| ASUS ASUS          | 2         | 0.35%   |
| Apple MacPro5      | 2         | 0.35%   |
| Apple Macmini5     | 2         | 0.35%   |
| Apple MacBookPro9  | 2         | 0.35%   |
| Apple MacBookPro7  | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 220       | 38.39%  |
| 2020 | 96        | 16.75%  |
| 2019 | 74        | 12.91%  |
| 2018 | 43        | 7.5%    |
| 2014 | 24        | 4.19%   |
| 2013 | 22        | 3.84%   |
| 2017 | 18        | 3.14%   |
| 2015 | 17        | 2.97%   |
| 2016 | 14        | 2.44%   |
| 2012 | 13        | 2.27%   |
| 2011 | 11        | 1.92%   |
| 2009 | 11        | 1.92%   |
| 2010 | 6         | 1.05%   |
| 2008 | 4         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 344       | 60.03%  |
| Desktop        | 177       | 30.89%  |
| Convertible    | 29        | 5.06%   |
| Mini pc        | 11        | 1.92%   |
| All in one     | 7         | 1.22%   |
| System on chip | 2         | 0.35%   |
| Tablet         | 2         | 0.35%   |
| Server         | 1         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 473       | 81.69%  |
| Enabled  | 106       | 18.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 570       | 99.48%  |
| Yes  | 3         | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 143       | 24.87%  |
| 4.01-8.0    | 141       | 24.52%  |
| 8.01-16.0   | 116       | 20.17%  |
| 32.01-64.0  | 97        | 16.87%  |
| 3.01-4.0    | 48        | 8.35%   |
| 64.01-256.0 | 18        | 3.13%   |
| 24.01-32.0  | 6         | 1.04%   |
| 2.01-3.0    | 3         | 0.52%   |
| 1.01-2.0    | 3         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 176       | 28.66%  |
| 4.01-8.0   | 166       | 27.04%  |
| 3.01-4.0   | 130       | 21.17%  |
| 1.01-2.0   | 80        | 13.03%  |
| 8.01-16.0  | 45        | 7.33%   |
| 0.51-1.0   | 7         | 1.14%   |
| 16.01-24.0 | 5         | 0.81%   |
| 24.01-32.0 | 3         | 0.49%   |
| 0.01-0.5   | 2         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 347       | 60.45%  |
| 2      | 136       | 23.69%  |
| 3      | 51        | 8.89%   |
| 5      | 15        | 2.61%   |
| 6      | 8         | 1.39%   |
| 4      | 8         | 1.39%   |
| 0      | 5         | 0.87%   |
| 7      | 2         | 0.35%   |
| 14     | 1         | 0.17%   |
| 9      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 448       | 78.05%  |
| Yes       | 126       | 21.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 450       | 77.99%  |
| No        | 127       | 22.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 473       | 82.55%  |
| No        | 100       | 17.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 420       | 72.79%  |
| No        | 157       | 27.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 100       | 17.39%  |
| Russia                | 47        | 8.17%   |
| Brazil                | 36        | 6.26%   |
| Germany               | 35        | 6.09%   |
| Canada                | 26        | 4.52%   |
| Italy                 | 24        | 4.17%   |
| Spain                 | 22        | 3.83%   |
| UK                    | 20        | 3.48%   |
| France                | 20        | 3.48%   |
| Poland                | 15        | 2.61%   |
| Netherlands           | 15        | 2.61%   |
| India                 | 15        | 2.61%   |
| Sweden                | 11        | 1.91%   |
| Norway                | 10        | 1.74%   |
| Belgium               | 10        | 1.74%   |
| Romania               | 9         | 1.57%   |
| Belarus               | 9         | 1.57%   |
| Ukraine               | 8         | 1.39%   |
| Switzerland           | 8         | 1.39%   |
| Czechia               | 8         | 1.39%   |
| Austria               | 8         | 1.39%   |
| Mexico                | 7         | 1.22%   |
| Indonesia             | 7         | 1.22%   |
| Australia             | 7         | 1.22%   |
| Greece                | 6         | 1.04%   |
| Turkey                | 5         | 0.87%   |
| Portugal              | 5         | 0.87%   |
| Israel                | 5         | 0.87%   |
| Denmark               | 5         | 0.87%   |
| Chile                 | 5         | 0.87%   |
| Hungary               | 4         | 0.7%    |
| China                 | 4         | 0.7%    |
| Venezuela             | 3         | 0.52%   |
| Saudi Arabia          | 3         | 0.52%   |
| New Zealand           | 3         | 0.52%   |
| Hong Kong             | 3         | 0.52%   |
| Finland               | 3         | 0.52%   |
| Estonia               | 3         | 0.52%   |
| Colombia              | 3         | 0.52%   |
| Argentina             | 3         | 0.52%   |
| South Africa          | 2         | 0.35%   |
| Kazakhstan            | 2         | 0.35%   |
| Japan                 | 2         | 0.35%   |
| Ireland               | 2         | 0.35%   |
| Iran                  | 2         | 0.35%   |
| Cyprus                | 2         | 0.35%   |
| Yemen                 | 1         | 0.17%   |
| Trinidad and Tobago   | 1         | 0.17%   |
| Slovenia              | 1         | 0.17%   |
| Slovakia              | 1         | 0.17%   |
| Singapore             | 1         | 0.17%   |
| Serbia                | 1         | 0.17%   |
| Philippines           | 1         | 0.17%   |
| Palestinian Territory | 1         | 0.17%   |
| Palestine             | 1         | 0.17%   |
| Pakistan              | 1         | 0.17%   |
| Nigeria               | 1         | 0.17%   |
| Morocco               | 1         | 0.17%   |
| Malaysia              | 1         | 0.17%   |
| Lithuania             | 1         | 0.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 18        | 3.06%   |
| S??o Paulo         | 8         | 1.36%   |
| Berlin             | 8         | 1.36%   |
| Vienna             | 7         | 1.19%   |
| Minsk              | 7         | 1.19%   |
| St Petersburg      | 6         | 1.02%   |
| Madrid             | 6         | 1.02%   |
| Montreal           | 5         | 0.85%   |
| Milan              | 5         | 0.85%   |
| Istanbul           | 5         | 0.85%   |
| Zurich             | 4         | 0.68%   |
| Warsaw             | 4         | 0.68%   |
| Ufa                | 4         | 0.68%   |
| Kyiv               | 4         | 0.68%   |
| Jakarta            | 4         | 0.68%   |
| Bucharest          | 4         | 0.68%   |
| Athens             | 4         | 0.68%   |
| Amsterdam          | 4         | 0.68%   |
| Weinsberg          | 3         | 0.51%   |
| Seattle            | 3         | 0.51%   |
| Rome               | 3         | 0.51%   |
| Prague             | 3         | 0.51%   |
| Mangawhai          | 3         | 0.51%   |
| Helsinki           | 3         | 0.51%   |
| Haifa              | 3         | 0.51%   |
| East Longmeadow    | 3         | 0.51%   |
| Caracas            | 3         | 0.51%   |
| Belo Horizonte     | 3         | 0.51%   |
| Atlanta            | 3         | 0.51%   |
| Yekaterinburg      | 2         | 0.34%   |
| Yakima             | 2         | 0.34%   |
| Winterthur         | 2         | 0.34%   |
| Timi?™oara         | 2         | 0.34%   |
| Tartu              | 2         | 0.34%   |
| Sunderland         | 2         | 0.34%   |
| Somerville         | 2         | 0.34%   |
| Shenzhen           | 2         | 0.34%   |
| Salt Lake City     | 2         | 0.34%   |
| Royse              | 2         | 0.34%   |
| Rotterdam          | 2         | 0.34%   |
| Roquetas de Mar    | 2         | 0.34%   |
| Rio de Janeiro     | 2         | 0.34%   |
| Raleigh            | 2         | 0.34%   |
| Porto Alegre       | 2         | 0.34%   |
| Perth              | 2         | 0.34%   |
| Perm               | 2         | 0.34%   |
| Paris              | 2         | 0.34%   |
| Noyelles-sous-Lens | 2         | 0.34%   |
| Novosibirsk        | 2         | 0.34%   |
| Nova Russas        | 2         | 0.34%   |
| Nizhniy Novgorod   | 2         | 0.34%   |
| New Delhi          | 2         | 0.34%   |
| Munich             | 2         | 0.34%   |
| Mumbai             | 2         | 0.34%   |
| Mexico City        | 2         | 0.34%   |
| Melbourne          | 2         | 0.34%   |
| Madison            | 2         | 0.34%   |
| Lubbock            | 2         | 0.34%   |
| Los Angeles        | 2         | 0.34%   |
| London             | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 180       | 262    | 21.53%  |
| WDC                         | 109       | 151    | 13.04%  |
| Seagate                     | 95        | 138    | 11.36%  |
| SanDisk                     | 53        | 60     | 6.34%   |
| Toshiba                     | 49        | 55     | 5.86%   |
| Kingston                    | 44        | 49     | 5.26%   |
| SK Hynix                    | 41        | 51     | 4.9%    |
| Unknown                     | 33        | 36     | 3.95%   |
| Crucial                     | 32        | 34     | 3.83%   |
| Micron Technology           | 23        | 25     | 2.75%   |
| Intel                       | 18        | 22     | 2.15%   |
| KIOXIA                      | 17        | 24     | 2.03%   |
| Phison                      | 11        | 15     | 1.32%   |
| A-DATA Technology           | 11        | 14     | 1.32%   |
| SPCC                        | 8         | 10     | 0.96%   |
| Silicon Motion              | 8         | 8      | 0.96%   |
| Patriot                     | 8         | 9      | 0.96%   |
| HGST                        | 7         | 7      | 0.84%   |
| LITEON                      | 6         | 6      | 0.72%   |
| Hitachi                     | 6         | 6      | 0.72%   |
| Apple                       | 6         | 7      | 0.72%   |
| Transcend                   | 5         | 5      | 0.6%    |
| Corsair                     | 5         | 5      | 0.6%    |
| XPG                         | 4         | 6      | 0.48%   |
| GOODRAM                     | 4         | 4      | 0.48%   |
| PNY                         | 3         | 4      | 0.36%   |
| Mushkin                     | 3         | 3      | 0.36%   |
| Hewlett-Packard             | 3         | 3      | 0.36%   |
| Realtek Semiconductor       | 2         | 2      | 0.24%   |
| PLEXTOR                     | 2         | 2      | 0.24%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.24%   |
| Lexar                       | 2         | 2      | 0.24%   |
| China                       | 2         | 2      | 0.24%   |
| Apacer                      | 2         | 2      | 0.24%   |
| ADATA Technology            | 2         | 2      | 0.24%   |
| Unknown                     | 2         | 2      | 0.24%   |
| YMTC                        | 1         | 1      | 0.12%   |
| WDC WDS                     | 1         | 1      | 0.12%   |
| USB3.1                      | 1         | 1      | 0.12%   |
| USB 3.0                     | 1         | 2      | 0.12%   |
| UMIS                        | 1         | 2      | 0.12%   |
| TO Exter                    | 1         | 1      | 0.12%   |
| TCSUNBOW                    | 1         | 1      | 0.12%   |
| T-FORCE                     | 1         | 1      | 0.12%   |
| SUNEAST                     | 1         | 1      | 0.12%   |
| SSSTC                       | 1         | 1      | 0.12%   |
| SP B75P                     | 1         | 1      | 0.12%   |
| SABRENT                     | 1         | 1      | 0.12%   |
| OWC                         | 1         | 1      | 0.12%   |
| Micron/Crucial Technology   | 1         | 1      | 0.12%   |
| MAXTOR                      | 1         | 1      | 0.12%   |
| Mass                        | 1         | 1      | 0.12%   |
| LS600                       | 1         | 1      | 0.12%   |
| LITEONIT                    | 1         | 1      | 0.12%   |
| LDLC                        | 1         | 1      | 0.12%   |
| LaCie                       | 1         | 2      | 0.12%   |
| Intenso                     | 1         | 4      | 0.12%   |
| HPE                         | 1         | 1      | 0.12%   |
| Gigabyte Technology         | 1         | 1      | 0.12%   |
| FORESEE                     | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB         | 19        | 2.01%   |
| Samsung NVMe SSD Drive 512GB         | 14        | 1.48%   |
| Samsung SSD 860 EVO 500GB            | 11        | 1.17%   |
| Kingston SA400S37480G 480GB SSD      | 11        | 1.17%   |
| SK Hynix NVMe SSD Drive 512GB        | 9         | 0.95%   |
| Seagate ST2000DM008-2FR102 2TB       | 9         | 0.95%   |
| Seagate ST1000DM010-2EP102 1TB       | 7         | 0.74%   |
| Sandisk NVMe SSD Drive 512GB         | 7         | 0.74%   |
| Sandisk NVMe SSD Drive 256GB         | 7         | 0.74%   |
| Samsung SSD 970 EVO Plus 500GB       | 7         | 0.74%   |
| Samsung NVMe SSD Drive 2TB           | 7         | 0.74%   |
| Sandisk NVMe SSD Drive 1TB           | 6         | 0.64%   |
| Samsung SSD 860 EVO 1TB              | 6         | 0.64%   |
| Samsung SSD 850 EVO 250GB            | 6         | 0.64%   |
| Samsung NVMe SSD Drive 256GB         | 6         | 0.64%   |
| Samsung NVMe SSD Drive 1TB           | 6         | 0.64%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 0.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 5         | 0.53%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 5         | 0.53%   |
| Unknown MMC Card  64GB               | 5         | 0.53%   |
| Unknown MMC Card  32GB               | 5         | 0.53%   |
| Toshiba NVMe SSD Drive 512GB         | 5         | 0.53%   |
| SK Hynix NVMe SSD Drive 256GB        | 5         | 0.53%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB       | 5         | 0.53%   |
| Sandisk NVMe SSD Drive 500GB         | 5         | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB         | 5         | 0.53%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 4         | 0.42%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 0.42%   |
| Samsung SSD 980 PRO 500GB            | 4         | 0.42%   |
| Samsung SSD 970 EVO Plus 2TB         | 4         | 0.42%   |
| Samsung SSD 870 EVO 1TB              | 4         | 0.42%   |
| Samsung NVMe SSD Drive 250GB         | 4         | 0.42%   |
| KIOXIA NVMe SSD Drive 512GB          | 4         | 0.42%   |
| KIOXIA NVMe SSD Drive 256GB          | 4         | 0.42%   |
| Intel NVMe SSD Drive 512GB           | 4         | 0.42%   |
| HGST HTS721010A9E630 1TB             | 4         | 0.42%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.42%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.42%   |
| Crucial CT1000MX500SSD1 1TB          | 4         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.32%   |
| WDC WD5000AADS-00S9B0 500GB          | 3         | 0.32%   |
| WDC WD30EFRX-68EUZN0 3TB             | 3         | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.32%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 3         | 0.32%   |
| Unknown MMC Card  128GB              | 3         | 0.32%   |
| Toshiba NVMe SSD Drive 256GB         | 3         | 0.32%   |
| Toshiba KXG6AZNV256G 256GB           | 3         | 0.32%   |
| Seagate ST8000DM004-2CX188 8TB       | 3         | 0.32%   |
| Seagate ST31000528AS 1TB             | 3         | 0.32%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 3         | 0.32%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.32%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 0.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.32%   |
| SanDisk SSD PLUS 240GB               | 3         | 0.32%   |
| SanDisk SDSSDA240G 240GB             | 3         | 0.32%   |
| Sandisk NVMe SSD Drive 1024GB        | 3         | 0.32%   |
| Samsung SSD 980 500GB                | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 136    | 43.87%  |
| WDC                 | 67        | 96     | 31.6%   |
| Toshiba             | 26        | 30     | 12.26%  |
| HGST                | 7         | 7      | 3.3%    |
| Samsung Electronics | 6         | 7      | 2.83%   |
| Hitachi             | 6         | 6      | 2.83%   |
| Unknown             | 2         | 2      | 0.94%   |
| USB 3.0             | 1         | 2      | 0.47%   |
| TO Exter            | 1         | 1      | 0.47%   |
| MAXTOR              | 1         | 1      | 0.47%   |
| LaCie               | 1         | 2      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 76        | 112    | 28.04%  |
| Kingston            | 30        | 33     | 11.07%  |
| Crucial             | 28        | 30     | 10.33%  |
| SanDisk             | 23        | 27     | 8.49%   |
| WDC                 | 22        | 27     | 8.12%   |
| Patriot             | 8         | 9      | 2.95%   |
| Micron Technology   | 7         | 7      | 2.58%   |
| A-DATA Technology   | 7         | 10     | 2.58%   |
| SPCC                | 5         | 6      | 1.85%   |
| Unknown             | 4         | 4      | 1.48%   |
| Transcend           | 4         | 4      | 1.48%   |
| Toshiba             | 4         | 4      | 1.48%   |
| SK Hynix            | 4         | 4      | 1.48%   |
| LITEON              | 4         | 4      | 1.48%   |
| GOODRAM             | 4         | 4      | 1.48%   |
| Apple               | 4         | 4      | 1.48%   |
| PNY                 | 3         | 4      | 1.11%   |
| Mushkin             | 3         | 3      | 1.11%   |
| Hewlett-Packard     | 3         | 3      | 1.11%   |
| PLEXTOR             | 2         | 2      | 0.74%   |
| Lexar               | 2         | 2      | 0.74%   |
| Intel               | 2         | 2      | 0.74%   |
| Corsair             | 2         | 2      | 0.74%   |
| China               | 2         | 2      | 0.74%   |
| Apacer              | 2         | 2      | 0.74%   |
| XPG                 | 1         | 2      | 0.37%   |
| WDC WDS             | 1         | 1      | 0.37%   |
| TCSUNBOW            | 1         | 1      | 0.37%   |
| T-FORCE             | 1         | 1      | 0.37%   |
| SUNEAST             | 1         | 1      | 0.37%   |
| Seagate             | 1         | 1      | 0.37%   |
| SABRENT             | 1         | 1      | 0.37%   |
| OWC                 | 1         | 1      | 0.37%   |
| LS600               | 1         | 1      | 0.37%   |
| LITEONIT            | 1         | 1      | 0.37%   |
| Intenso             | 1         | 4      | 0.37%   |
| Gigabyte Technology | 1         | 1      | 0.37%   |
| FORESEE             | 1         | 1      | 0.37%   |
| Dahua               | 1         | 1      | 0.37%   |
| BIWIN               | 1         | 1      | 0.37%   |
| ASMT                | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 310       | 408    | 41.01%  |
| SSD     | 231       | 331    | 30.56%  |
| HDD     | 180       | 291    | 23.81%  |
| MMC     | 25        | 28     | 3.31%   |
| Unknown | 10        | 11     | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 323       | 601    | 47.22%  |
| NVMe | 310       | 408    | 45.32%  |
| SAS  | 26        | 32     | 3.8%    |
| MMC  | 25        | 28     | 3.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 239       | 322    | 52.76%  |
| 0.51-1.0   | 129       | 180    | 28.48%  |
| 1.01-2.0   | 48        | 58     | 10.6%   |
| 3.01-4.0   | 14        | 16     | 3.09%   |
| 2.01-3.0   | 12        | 28     | 2.65%   |
| 4.01-10.0  | 10        | 16     | 2.21%   |
| 10.01-20.0 | 1         | 2      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 111       | 19.17%  |
| 251-500        | 100       | 17.27%  |
| 101-250        | 87        | 15.03%  |
| 1-20           | 85        | 14.68%  |
| 1001-2000      | 66        | 11.4%   |
| Unknown        | 49        | 8.46%   |
| More than 3000 | 35        | 6.04%   |
| 2001-3000      | 22        | 3.8%    |
| 51-100         | 17        | 2.94%   |
| 21-50          | 7         | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 181       | 30.78%  |
| 21-50          | 86        | 14.63%  |
| 101-250        | 70        | 11.9%   |
| 51-100         | 60        | 10.2%   |
| 251-500        | 56        | 9.52%   |
| Unknown        | 49        | 8.33%   |
| 501-1000       | 45        | 7.65%   |
| 1001-2000      | 23        | 3.91%   |
| More than 3000 | 10        | 1.7%    |
| 2001-3000      | 8         | 1.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 4         | 6      | 9.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 3      | 4.88%   |
| WDC WD30EZRX-00MMMB0 3TB                            | 1         | 1      | 2.44%   |
| WDC WD2500AAKX-753CA1 250GB                         | 1         | 1      | 2.44%   |
| WDC WD1600BEVT-24A23T0 160GB                        | 1         | 1      | 2.44%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 1         | 1      | 2.44%   |
| WDC WD10EFRX-68JCSN0 1TB                            | 1         | 1      | 2.44%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1         | 1      | 2.44%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 2.44%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 2.44%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 2.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.44%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1         | 1      | 2.44%   |
| Seagate ST3500630AS 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST3200822A 200GB                            | 1         | 1      | 2.44%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.44%   |
| Seagate ST31000524AS 1TB                            | 1         | 1      | 2.44%   |
| Seagate ST3000DM001-1ER166 3TB                      | 1         | 1      | 2.44%   |
| Seagate ST2000DL003-9VT166 2TB                      | 1         | 1      | 2.44%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.44%   |
| Seagate ST1000DM003-1ER162 1TB                      | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 970 EVO 250GB               | 1         | 1      | 2.44%   |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD    | 1         | 1      | 2.44%   |
| Samsung Electronics HD103UJ 1TB                     | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.44%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.44%   |
| Kingston SV300S37A240G 240GB SSD                    | 1         | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.44%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.44%   |
| Crucial CT128MX100SSD1 128GB                        | 1         | 1      | 2.44%   |
| Crucial CT1050MX300SSD1 1050GB                      | 1         | 1      | 2.44%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 2.44%   |
| A-DATA Technology SX8100NP 1TB                      | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 19     | 39.02%  |
| WDC                 | 7         | 7      | 17.07%  |
| Samsung Electronics | 3         | 3      | 7.32%   |
| Crucial             | 3         | 3      | 7.32%   |
| Toshiba             | 2         | 2      | 4.88%   |
| Micron Technology   | 2         | 2      | 4.88%   |
| Kingston            | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| SK Hynix            | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| Hitachi             | 1         | 1      | 2.44%   |
| A-DATA Technology   | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 19     | 57.14%  |
| WDC                 | 7         | 7      | 25%     |
| HGST                | 2         | 2      | 7.14%   |
| Toshiba             | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 65.79%  |
| SSD  | 10        | 10     | 26.32%  |
| NVMe | 3         | 3      | 7.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 306       | 577    | 48.8%   |
| Works    | 282       | 447    | 44.98%  |
| Malfunc  | 38        | 44     | 6.06%   |
| Failed   | 1         | 1      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 306       | 39.43%  |
| AMD                            | 124       | 15.98%  |
| Samsung Electronics            | 110       | 14.18%  |
| Sandisk                        | 53        | 6.83%   |
| SK Hynix                       | 37        | 4.77%   |
| Toshiba America Info Systems   | 22        | 2.84%   |
| Micron Technology              | 16        | 2.06%   |
| KIOXIA                         | 15        | 1.93%   |
| Phison Electronics             | 14        | 1.8%    |
| Kingston Technology Company    | 14        | 1.8%    |
| ASMedia Technology             | 10        | 1.29%   |
| Silicon Motion                 | 9         | 1.16%   |
| Nvidia                         | 9         | 1.16%   |
| ADATA Technology               | 7         | 0.9%    |
| Micron/Crucial Technology      | 5         | 0.64%   |
| JMicron Technology             | 5         | 0.64%   |
| Realtek Semiconductor          | 4         | 0.52%   |
| Marvell Technology Group       | 4         | 0.52%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.26%   |
| LSI Logic / Symbios Logic      | 2         | 0.26%   |
| Lite-On Technology             | 2         | 0.26%   |
| Yangtze Memory Technologies    | 1         | 0.13%   |
| Union Memory (Shenzhen)        | 1         | 0.13%   |
| Solid State Storage Technology | 1         | 0.13%   |
| Silicon Image                  | 1         | 0.13%   |
| Broadcom / LSI                 | 1         | 0.13%   |
| Apple                          | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 97        | 11.48%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 67        | 7.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 44        | 5.21%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 22        | 2.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20        | 2.37%   |
| Samsung NVMe SSD Controller 980                                                  | 19        | 2.25%   |
| AMD 400 Series Chipset SATA Controller                                           | 19        | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 2.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 2.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 2.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 16        | 1.89%   |
| Micron Non-Volatile memory controller                                            | 16        | 1.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 16        | 1.89%   |
| SK Hynix Gold P31 SSD                                                            | 15        | 1.78%   |
| KIOXIA Non-Volatile memory controller                                            | 15        | 1.78%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 15        | 1.78%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 1.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 12        | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 12        | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 1.42%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 11        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 11        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 11        | 1.3%    |
| SK Hynix Non-Volatile memory controller                                          | 9         | 1.07%   |
| Intel SSD 660P Series                                                            | 9         | 1.07%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 9         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8         | 0.95%   |
| Sandisk Non-Volatile memory controller                                           | 7         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 0.83%   |
| SK Hynix BC511                                                                   | 6         | 0.71%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 6         | 0.71%   |
| Phison E12 NVMe Controller                                                       | 6         | 0.71%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 6         | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 6         | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 6         | 0.71%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 5         | 0.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 0.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.59%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5         | 0.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5         | 0.59%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 4         | 0.47%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 4         | 0.47%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.47%   |
| Phison PS5013 E13 NVMe Controller                                                | 4         | 0.47%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 4         | 0.47%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 4         | 0.47%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 0.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 0.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 0.47%   |
| AMD X370 Series Chipset SATA Controller                                          | 4         | 0.47%   |
| AMD 300 Series Chipset SATA Controller                                           | 4         | 0.47%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 0.47%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 382       | 50.07%  |
| NVMe | 308       | 40.37%  |
| RAID | 43        | 5.64%   |
| IDE  | 26        | 3.41%   |
| SAS  | 3         | 0.39%   |
| SCSI | 1         | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 401       | 69.98%  |
| AMD    | 170       | 29.67%  |
| ARM    | 2         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 2.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 2.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 2.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 1.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 9         | 1.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.4%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.22%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.22%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 0.87%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 5         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.87%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 5         | 0.87%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.87%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 5         | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.7%    |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.7%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.7%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 4         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.7%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 4         | 0.7%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 4         | 0.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.7%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.7%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 4         | 0.7%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.52%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 3         | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.52%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.52%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.52%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.52%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 0.52%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 3         | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.52%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.52%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 3         | 0.52%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 0.52%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.52%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.52%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 3         | 0.52%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 3         | 0.52%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 146       | 25.48%  |
| Intel Core i5           | 113       | 19.72%  |
| AMD Ryzen 5             | 57        | 9.95%   |
| Other                   | 51        | 8.9%    |
| AMD Ryzen 7             | 38        | 6.63%   |
| Intel Core i3           | 32        | 5.58%   |
| AMD Ryzen 9             | 20        | 3.49%   |
| Intel Core 2 Duo        | 13        | 2.27%   |
| Intel Celeron           | 11        | 1.92%   |
| AMD Ryzen 3             | 11        | 1.92%   |
| Intel Xeon              | 10        | 1.75%   |
| Intel Core i9           | 9         | 1.57%   |
| Intel Pentium           | 7         | 1.22%   |
| AMD Ryzen 7 PRO         | 5         | 0.87%   |
| AMD Ryzen Threadripper  | 4         | 0.7%    |
| AMD FX                  | 4         | 0.7%    |
| AMD A8                  | 4         | 0.7%    |
| AMD A10                 | 4         | 0.7%    |
| Intel Pentium Silver    | 3         | 0.52%   |
| Intel Atom              | 3         | 0.52%   |
| AMD Ryzen 5 PRO         | 3         | 0.52%   |
| AMD Phenom              | 3         | 0.52%   |
| Intel Pentium Dual-Core | 2         | 0.35%   |
| AMD Athlon II X2        | 2         | 0.35%   |
| AMD Athlon              | 2         | 0.35%   |
| AMD A6                  | 2         | 0.35%   |
| AMD A4                  | 2         | 0.35%   |
| Intel Pentium Dual      | 1         | 0.17%   |
| Intel Core m7           | 1         | 0.17%   |
| Intel Core m3           | 1         | 0.17%   |
| Intel Core 2 Extreme    | 1         | 0.17%   |
| AMD Ryzen Embedded      | 1         | 0.17%   |
| AMD PRO A10             | 1         | 0.17%   |
| AMD Phenom II X6        | 1         | 0.17%   |
| AMD E1                  | 1         | 0.17%   |
| AMD E                   | 1         | 0.17%   |
| AMD C-60                | 1         | 0.17%   |
| AMD Athlon X4           | 1         | 0.17%   |
| AMD Athlon 64 X2        | 1         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 248       | 43.28%  |
| 2       | 146       | 25.48%  |
| 6       | 85        | 14.83%  |
| 8       | 65        | 11.34%  |
| 12      | 9         | 1.57%   |
| 16      | 6         | 1.05%   |
| 10      | 4         | 0.7%    |
| 24      | 3         | 0.52%   |
| 1       | 3         | 0.52%   |
| 3       | 2         | 0.35%   |
| 32      | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 571       | 99.65%  |
| 2      | 2         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 454       | 79.23%  |
| 1       | 118       | 20.59%  |
| Unknown | 1         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 572       | 99.83%  |
| 64-bit         | 1         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 38        | 6.59%   |
| Unknown    | 35        | 6.07%   |
| 0x806ec    | 33        | 5.72%   |
| 0x806ea    | 30        | 5.2%    |
| 0x306a9    | 27        | 4.68%   |
| 0x306c3    | 25        | 4.33%   |
| 0x906ea    | 19        | 3.29%   |
| 0x806e9    | 19        | 3.29%   |
| 0x206a7    | 19        | 3.29%   |
| 0xa0652    | 17        | 2.95%   |
| 0x506e3    | 17        | 2.95%   |
| 0x0a50000c | 17        | 2.95%   |
| 0x08600106 | 17        | 2.95%   |
| 0x40651    | 16        | 2.77%   |
| 0x406e3    | 15        | 2.6%    |
| 0x906ed    | 13        | 2.25%   |
| 0x1067a    | 12        | 2.08%   |
| 0x08701021 | 12        | 2.08%   |
| 0x706e5    | 11        | 1.91%   |
| 0x08108109 | 10        | 1.73%   |
| 0x08608103 | 9         | 1.56%   |
| 0x08600104 | 8         | 1.39%   |
| 0x0800820d | 7         | 1.21%   |
| 0x506c9    | 6         | 1.04%   |
| 0x306d4    | 6         | 1.04%   |
| 0x0a201016 | 6         | 1.04%   |
| 0x0a201009 | 6         | 1.04%   |
| 0x0810100b | 6         | 1.04%   |
| 0x906e9    | 5         | 0.87%   |
| 0x706a8    | 5         | 0.87%   |
| 0x08608102 | 5         | 0.87%   |
| 0x08101016 | 5         | 0.87%   |
| 0x06001119 | 5         | 0.87%   |
| 0x806eb    | 4         | 0.69%   |
| 0x20655    | 4         | 0.69%   |
| 0x10676    | 4         | 0.69%   |
| 0x08701013 | 4         | 0.69%   |
| 0x06003106 | 4         | 0.69%   |
| 0x90672    | 3         | 0.52%   |
| 0x106a5    | 3         | 0.52%   |
| 0x08108102 | 3         | 0.52%   |
| 0x08008206 | 3         | 0.52%   |
| 0x08001138 | 3         | 0.52%   |
| 0x08001137 | 3         | 0.52%   |
| 0xa0671    | 2         | 0.35%   |
| 0xa0655    | 2         | 0.35%   |
| 0x906ec    | 2         | 0.35%   |
| 0x906eb    | 2         | 0.35%   |
| 0x806d1    | 2         | 0.35%   |
| 0x806c2    | 2         | 0.35%   |
| 0x406c4    | 2         | 0.35%   |
| 0x406c3    | 2         | 0.35%   |
| 0x40661    | 2         | 0.35%   |
| 0x306f2    | 2         | 0.35%   |
| 0x206c2    | 2         | 0.35%   |
| 0x0a50000b | 2         | 0.35%   |
| 0x08600102 | 2         | 0.35%   |
| 0x0800820b | 2         | 0.35%   |
| 0x07030105 | 2         | 0.35%   |
| 0x0600611a | 2         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 134       | 23.39%  |
| Haswell          | 47        | 8.2%    |
| Zen 2            | 46        | 8.03%   |
| TigerLake        | 40        | 6.98%   |
| Zen 3            | 36        | 6.28%   |
| Skylake          | 36        | 6.28%   |
| IvyBridge        | 30        | 5.24%   |
| Zen+             | 26        | 4.54%   |
| SandyBridge      | 22        | 3.84%   |
| CometLake        | 21        | 3.66%   |
| Zen              | 20        | 3.49%   |
| Unknown          | 17        | 2.97%   |
| Penryn           | 16        | 2.79%   |
| Icelake          | 15        | 2.62%   |
| Westmere         | 8         | 1.4%    |
| Piledriver       | 7         | 1.22%   |
| Broadwell        | 7         | 1.22%   |
| K10              | 6         | 1.05%   |
| Goldmont plus    | 6         | 1.05%   |
| Goldmont         | 6         | 1.05%   |
| Steamroller      | 4         | 0.7%    |
| Silvermont       | 4         | 0.7%    |
| Nehalem          | 3         | 0.52%   |
| Alderlake Hybrid | 3         | 0.52%   |
| Puma             | 2         | 0.35%   |
| Jaguar           | 2         | 0.35%   |
| Excavator        | 2         | 0.35%   |
| Bulldozer        | 2         | 0.35%   |
| Bobcat           | 2         | 0.35%   |
| K8 Hammer        | 1         | 0.17%   |
| Core             | 1         | 0.17%   |
| Bonnell          | 1         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 338       | 48.99%  |
| Nvidia                     | 185       | 26.81%  |
| AMD                        | 165       | 23.91%  |
| Matrox Electronics Systems | 1         | 0.14%   |
| ASPEED Technology          | 1         | 0.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 4.99%   |
| Intel UHD Graphics 620                                                                   | 31        | 4.42%   |
| AMD Renoir                                                                               | 26        | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 2.99%   |
| AMD Cezanne                                                                              | 19        | 2.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 2.56%   |
| Intel HD Graphics 530                                                                    | 17        | 2.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 2.42%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 2.42%   |
| Intel HD Graphics 620                                                                    | 16        | 2.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 2.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 1.99%   |
| AMD Lucienne                                                                             | 14        | 1.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 1.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 1.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7         | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.85%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 6         | 0.85%   |
| Nvidia GP108M [GeForce MX250]                                                            | 6         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.85%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.71%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 5         | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.57%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 4         | 0.57%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.57%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.57%   |
| Intel HD Graphics 630                                                                    | 4         | 0.57%   |
| Intel HD Graphics 500                                                                    | 4         | 0.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.57%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                             | 4         | 0.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 4         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.43%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.43%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.43%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.43%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.43%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.43%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.43%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.43%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.43%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 3         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 231       | 40.31%  |
| 1 x AMD        | 131       | 22.86%  |
| Intel + Nvidia | 89        | 15.53%  |
| 1 x Nvidia     | 83        | 14.49%  |
| AMD + Nvidia   | 12        | 2.09%   |
| 2 x AMD        | 11        | 1.92%   |
| Intel + AMD    | 10        | 1.75%   |
| Other          | 3         | 0.52%   |
| 2 x Nvidia     | 1         | 0.17%   |
| 1 x Matrox     | 1         | 0.17%   |
| 1 x ASPEED     | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 472       | 81.94%  |
| Proprietary | 97        | 16.84%  |
| Unknown     | 7         | 1.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 323       | 55.88%  |
| 1.01-2.0   | 65        | 11.25%  |
| 0.01-0.5   | 64        | 11.07%  |
| 0.51-1.0   | 39        | 6.75%   |
| 3.01-4.0   | 37        | 6.4%    |
| 7.01-8.0   | 27        | 4.67%   |
| 5.01-6.0   | 13        | 2.25%   |
| 8.01-16.0  | 10        | 1.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 83        | 12.33%  |
| BOE                     | 74        | 11%     |
| Chimei Innolux          | 66        | 9.81%   |
| LG Display              | 63        | 9.36%   |
| Samsung Electronics     | 56        | 8.32%   |
| Dell                    | 52        | 7.73%   |
| Goldstar                | 33        | 4.9%    |
| Hewlett-Packard         | 27        | 4.01%   |
| Acer                    | 21        | 3.12%   |
| Sharp                   | 19        | 2.82%   |
| Philips                 | 19        | 2.82%   |
| Lenovo                  | 18        | 2.67%   |
| AOC                     | 18        | 2.67%   |
| Apple                   | 17        | 2.53%   |
| BenQ                    | 12        | 1.78%   |
| Ancor Communications    | 12        | 1.78%   |
| ViewSonic               | 9         | 1.34%   |
| InfoVision              | 9         | 1.34%   |
| CSO                     | 8         | 1.19%   |
| Iiyama                  | 7         | 1.04%   |
| PANDA                   | 6         | 0.89%   |
| ASUSTek Computer        | 6         | 0.89%   |
| TMX                     | 4         | 0.59%   |
| Eizo                    | 4         | 0.59%   |
| Sony                    | 2         | 0.3%    |
| Panasonic               | 2         | 0.3%    |
| MSI                     | 2         | 0.3%    |
| HannStar                | 2         | 0.3%    |
| Gigabyte Technology     | 2         | 0.3%    |
| Chi Mei Optoelectronics | 2         | 0.3%    |
| Westinghouse            | 1         | 0.15%   |
| Unknown (XXX)           | 1         | 0.15%   |
| TCL                     | 1         | 0.15%   |
| Sceptre Tech            | 1         | 0.15%   |
| PRISM+                  | 1         | 0.15%   |
| Plain Tree Systems      | 1         | 0.15%   |
| Packard Bell            | 1         | 0.15%   |
| NEC Computers           | 1         | 0.15%   |
| Kogan                   | 1         | 0.15%   |
| JRY                     | 1         | 0.15%   |
| JDI                     | 1         | 0.15%   |
| InnoLux Display         | 1         | 0.15%   |
| Hitachi                 | 1         | 0.15%   |
| Fujitsu Siemens         | 1         | 0.15%   |
| CHE                     | 1         | 0.15%   |
| Belinea                 | 1         | 0.15%   |
| Arnos Instruments       | 1         | 0.15%   |
| AGT                     | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 8         | 1.15%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch | 5         | 0.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 4         | 0.58%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch             | 4         | 0.58%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch             | 4         | 0.58%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch    | 4         | 0.58%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch           | 3         | 0.43%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch | 3         | 0.43%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch      | 3         | 0.43%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch          | 3         | 0.43%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch         | 3         | 0.43%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                 | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch  | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch  | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch  | 3         | 0.43%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 3         | 0.43%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch             | 3         | 0.43%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch             | 3         | 0.43%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch             | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch    | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 309x173mm 13.9-inch    | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch    | 3         | 0.43%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch           | 2         | 0.29%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch           | 2         | 0.29%   |
| Sharp LCD Monitor SHP14F7 1920x1200 288x180mm 13.4-inch           | 2         | 0.29%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch           | 2         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 2         | 0.29%   |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch | 2         | 0.29%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch | 2         | 0.29%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch          | 2         | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch           | 2         | 0.29%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch           | 2         | 0.29%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch           | 2         | 0.29%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch      | 2         | 0.29%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch      | 2         | 0.29%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch      | 2         | 0.29%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch      | 2         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch      | 2         | 0.29%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch       | 2         | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch       | 2         | 0.29%   |
| InfoVision LCD Monitor IVO057C 1366x768 310x170mm 13.9-inch       | 2         | 0.29%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch       | 2         | 0.29%   |
| Goldstar IPS235 GSM587E 1920x1080 510x290mm 23.1-inch             | 2         | 0.29%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                 | 2         | 0.29%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                 | 2         | 0.29%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                  | 2         | 0.29%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                 | 2         | 0.29%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                 | 2         | 0.29%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 2         | 0.29%   |
| Dell 2407WFP DELA017 1680x1050 520x330mm 24.2-inch                | 2         | 0.29%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch             | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1526 1920x1080 344x193mm 15.5-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch  | 2         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch  | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 349       | 55.22%  |
| 1366x768 (WXGA)    | 60        | 9.49%   |
| 2560x1440 (QHD)    | 51        | 8.07%   |
| 3840x2160 (4K)     | 45        | 7.12%   |
| 1920x1200 (WUXGA)  | 25        | 3.96%   |
| 1600x900 (HD+)     | 14        | 2.22%   |
| 2560x1600          | 10        | 1.58%   |
| 1680x1050 (WSXGA+) | 10        | 1.58%   |
| 1280x1024 (SXGA)   | 10        | 1.58%   |
| 3440x1440          | 9         | 1.42%   |
| 1440x900 (WXGA+)   | 9         | 1.42%   |
| 1280x800 (WXGA)    | 7         | 1.11%   |
| 2560x1080          | 6         | 0.95%   |
| 3840x2400          | 4         | 0.63%   |
| 2160x1440          | 4         | 0.63%   |
| 2880x1800          | 3         | 0.47%   |
| 2256x1504          | 3         | 0.47%   |
| 3840x1080          | 2         | 0.32%   |
| 3200x2000          | 2         | 0.32%   |
| 2160x1350          | 2         | 0.32%   |
| 3840x1600          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 3000x2000          | 1         | 0.16%   |
| 2736x1824          | 1         | 0.16%   |
| 1280x720 (HD)      | 1         | 0.16%   |
| 1024x600           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 146       | 21.57%  |
| 13     | 94        | 13.88%  |
| 14     | 78        | 11.52%  |
| 27     | 65        | 9.6%    |
| 24     | 61        | 9.01%   |
| 21     | 45        | 6.65%   |
| 23     | 37        | 5.47%   |
| 17     | 28        | 4.14%   |
| 31     | 15        | 2.22%   |
| 34     | 14        | 2.07%   |
| 12     | 12        | 1.77%   |
| 16     | 10        | 1.48%   |
| 22     | 9         | 1.33%   |
| 19     | 9         | 1.33%   |
| 20     | 7         | 1.03%   |
| 18     | 6         | 0.89%   |
| 25     | 5         | 0.74%   |
| 11     | 5         | 0.74%   |
| 54     | 3         | 0.44%   |
| 42     | 3         | 0.44%   |
| 40     | 3         | 0.44%   |
| 26     | 3         | 0.44%   |
| 84     | 2         | 0.3%    |
| 47     | 2         | 0.3%    |
| 32     | 2         | 0.3%    |
| 29     | 2         | 0.3%    |
| 10     | 2         | 0.3%    |
| 72     | 1         | 0.15%   |
| 55     | 1         | 0.15%   |
| 52     | 1         | 0.15%   |
| 49     | 1         | 0.15%   |
| 48     | 1         | 0.15%   |
| 43     | 1         | 0.15%   |
| 37     | 1         | 0.15%   |
| 30     | 1         | 0.15%   |
| 28     | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 277       | 41.65%  |
| 501-600     | 153       | 23.01%  |
| 401-500     | 72        | 10.83%  |
| 201-300     | 71        | 10.68%  |
| 351-400     | 31        | 4.66%   |
| 601-700     | 25        | 3.76%   |
| 701-800     | 16        | 2.41%   |
| 1001-1500   | 9         | 1.35%   |
| 801-900     | 4         | 0.6%    |
| 901-1000    | 4         | 0.6%    |
| 1501-2000   | 3         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 471       | 79.97%  |
| 16/10 | 81        | 13.75%  |
| 21/9  | 16        | 2.72%   |
| 5/4   | 10        | 1.7%    |
| 3/2   | 8         | 1.36%   |
| 32/9  | 2         | 0.34%   |
| 6/5   | 1         | 0.17%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 149       | 22.11%  |
| 81-90          | 130       | 19.29%  |
| 201-250        | 113       | 16.77%  |
| 301-350        | 69        | 10.24%  |
| 71-80          | 44        | 6.53%   |
| 351-500        | 33        | 4.9%    |
| 151-200        | 30        | 4.45%   |
| 251-300        | 27        | 4.01%   |
| 121-130        | 23        | 3.41%   |
| 141-150        | 12        | 1.78%   |
| 501-1000       | 12        | 1.78%   |
| 61-70          | 11        | 1.63%   |
| More than 1000 | 8         | 1.19%   |
| 111-120        | 6         | 0.89%   |
| 51-60          | 5         | 0.74%   |
| 41-50          | 2         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 235       | 36.15%  |
| 51-100        | 176       | 27.08%  |
| 101-120       | 137       | 21.08%  |
| 161-240       | 75        | 11.54%  |
| More than 240 | 21        | 3.23%   |
| 1-50          | 6         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 433       | 75.17%  |
| 2     | 115       | 19.97%  |
| 3     | 15        | 2.6%    |
| 0     | 12        | 2.08%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 335       | 39.83%  |
| Realtek Semiconductor             | 289       | 34.36%  |
| Qualcomm Atheros                  | 65        | 7.73%   |
| Broadcom                          | 29        | 3.45%   |
| MEDIATEK                          | 19        | 2.26%   |
| Ralink Technology                 | 13        | 1.55%   |
| TP-Link                           | 11        | 1.31%   |
| Lenovo                            | 10        | 1.19%   |
| Nvidia                            | 6         | 0.71%   |
| Marvell Technology Group          | 5         | 0.59%   |
| DisplayLink                       | 5         | 0.59%   |
| Sierra Wireless                   | 4         | 0.48%   |
| Ralink                            | 4         | 0.48%   |
| Qualcomm                          | 3         | 0.36%   |
| NetGear                           | 3         | 0.36%   |
| Dell                              | 3         | 0.36%   |
| D-Link                            | 3         | 0.36%   |
| Aquantia                          | 3         | 0.36%   |
| Xiaomi                            | 2         | 0.24%   |
| Qualcomm Atheros Communications   | 2         | 0.24%   |
| Linksys                           | 2         | 0.24%   |
| Google                            | 2         | 0.24%   |
| FIBOCOM                           | 2         | 0.24%   |
| Edimax Technology                 | 2         | 0.24%   |
| Broadcom Limited                  | 2         | 0.24%   |
| Belkin Components                 | 2         | 0.24%   |
| ASUSTek Computer                  | 2         | 0.24%   |
| ASIX Electronics                  | 2         | 0.24%   |
| Spreadtrum Communications         | 1         | 0.12%   |
| Shenzhen Goodix Technology        | 1         | 0.12%   |
| OPPO Electronics                  | 1         | 0.12%   |
| MosChip Semiconductor             | 1         | 0.12%   |
| Mellanox Technologies             | 1         | 0.12%   |
| ICS Advent                        | 1         | 0.12%   |
| Huawei Technologies               | 1         | 0.12%   |
| HMD Global                        | 1         | 0.12%   |
| Hewlett-Packard                   | 1         | 0.12%   |
| Ericsson Business Mobile Networks | 1         | 0.12%   |
| AVM                               | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 194       | 19.3%   |
| Intel Wi-Fi 6 AX200                                               | 57        | 5.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 3.08%   |
| Intel Wi-Fi 6 AX201                                               | 29        | 2.89%   |
| Intel Wireless 8265 / 8275                                        | 28        | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 2.19%   |
| Intel I211 Gigabit Network Connection                             | 19        | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 1.59%   |
| Intel Wireless 8260                                               | 16        | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 16        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 1.49%   |
| MEDIATEK Network controller                                       | 14        | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.29%   |
| Intel Wireless 7260                                               | 13        | 1.29%   |
| Intel Wireless 3165                                               | 13        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 10        | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 10        | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 0.9%    |
| Intel Wireless-AC 9260                                            | 9         | 0.9%    |
| Intel Wireless 7265                                               | 9         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                              | 8         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 6         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 6         | 0.6%    |
| TP-Link 802.11ac NIC                                              | 5         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.5%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 5         | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 5         | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 4         | 0.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.4%    |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.4%    |
| Intel Ethernet Connection (10) I219-LM                            | 4         | 0.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.3%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 3         | 0.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 289       | 57.57%  |
| Realtek Semiconductor           | 63        | 12.55%  |
| Qualcomm Atheros                | 53        | 10.56%  |
| Broadcom                        | 23        | 4.58%   |
| MEDIATEK                        | 18        | 3.59%   |
| Ralink Technology               | 13        | 2.59%   |
| TP-Link                         | 10        | 1.99%   |
| Ralink                          | 4         | 0.8%    |
| Sierra Wireless                 | 3         | 0.6%    |
| NetGear                         | 3         | 0.6%    |
| D-Link                          | 3         | 0.6%    |
| Qualcomm Atheros Communications | 2         | 0.4%    |
| Qualcomm                        | 2         | 0.4%    |
| Marvell Technology Group        | 2         | 0.4%    |
| FIBOCOM                         | 2         | 0.4%    |
| Edimax Technology               | 2         | 0.4%    |
| Dell                            | 2         | 0.4%    |
| Broadcom Limited                | 2         | 0.4%    |
| Belkin Components               | 2         | 0.4%    |
| Linksys                         | 1         | 0.2%    |
| Hewlett-Packard                 | 1         | 0.2%    |
| AVM                             | 1         | 0.2%    |
| ASUSTek Computer                | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 57        | 11.29%  |
| Intel Wi-Fi 6 AX201                                            | 29        | 5.74%   |
| Intel Wireless 8265 / 8275                                     | 28        | 5.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22        | 4.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 3.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 3.17%   |
| Intel Wireless 8260                                            | 16        | 3.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 16        | 3.17%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 3.17%   |
| MEDIATEK Network controller                                    | 14        | 2.77%   |
| Intel Wireless 7260                                            | 13        | 2.57%   |
| Intel Wireless 3165                                            | 13        | 2.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11        | 2.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 1.78%   |
| Intel Wireless-AC 9260                                         | 9         | 1.78%   |
| Intel Wireless 7265                                            | 9         | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.19%   |
| TP-Link 802.11ac NIC                                           | 5         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 0.79%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 0.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 0.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.59%   |
| Sierra Wireless EM7305                                         | 2         | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.4%    |
| Realtek 802.11ac NIC                                           | 2         | 0.4%    |
| Ralink RT5372 Wireless Adapter                                 | 2         | 0.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.4%    |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.4%    |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 2         | 0.4%    |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter            | 2         | 0.4%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter             | 2         | 0.4%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 0.4%    |
| Intel Wireless 3160                                            | 2         | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.4%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.4%    |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.4%    |
| Intel 600 Series Chipset Family Wireless-AC 9560               | 2         | 0.4%    |
| FIBOCOM L830-EB                                                | 2         | 0.4%    |
| Dell DW5811e Snapdragon???„?? X7 LTE                           | 2         | 0.4%    |
| D-Link 11ac adapter                                            | 2         | 0.4%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.4%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 0.4%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 0.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 0.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 254       | 52.92%  |
| Intel                     | 149       | 31.04%  |
| Qualcomm Atheros          | 17        | 3.54%   |
| Broadcom                  | 15        | 3.13%   |
| Lenovo                    | 10        | 2.08%   |
| Nvidia                    | 6         | 1.25%   |
| DisplayLink               | 5         | 1.04%   |
| Marvell Technology Group  | 3         | 0.63%   |
| Aquantia                  | 3         | 0.63%   |
| Xiaomi                    | 2         | 0.42%   |
| ASIX Electronics          | 2         | 0.42%   |
| TP-Link                   | 1         | 0.21%   |
| Spreadtrum Communications | 1         | 0.21%   |
| Sierra Wireless           | 1         | 0.21%   |
| Qualcomm                  | 1         | 0.21%   |
| OPPO Electronics          | 1         | 0.21%   |
| MosChip Semiconductor     | 1         | 0.21%   |
| Mellanox Technologies     | 1         | 0.21%   |
| MediaTek                  | 1         | 0.21%   |
| Linksys                   | 1         | 0.21%   |
| ICS Advent                | 1         | 0.21%   |
| Huawei Technologies       | 1         | 0.21%   |
| HMD Global                | 1         | 0.21%   |
| Google                    | 1         | 0.21%   |
| ASUSTek Computer          | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 194       | 39.19%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 6.26%   |
| Intel I211 Gigabit Network Connection                             | 19        | 3.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 2.63%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 2.22%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 1.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 1.41%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.21%   |
| Intel Ethernet Connection (2) I219-V                              | 6         | 1.21%   |
| Intel 82574L Gigabit Network Connection                           | 6         | 1.21%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 5         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.01%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.81%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.81%   |
| Intel Ethernet Connection (10) I219-LM                            | 4         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.61%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 3         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.61%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.4%    |
| Nvidia MCP55 Ethernet                                             | 2         | 0.4%    |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.4%    |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.4%    |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.4%    |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.4%    |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.2%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.2%    |
| TP-Link USB 10/100 LAN                                            | 1         | 0.2%    |
| Spreadtrum Nokia C30                                              | 1         | 0.2%    |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.2%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.2%    |
| Qualcomm Mobile Router                                            | 1         | 0.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.2%    |
| OPPO realme X50 Pro 5G                                            | 1         | 0.2%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 473       | 51.02%  |
| Ethernet | 449       | 48.44%  |
| Modem    | 3         | 0.32%   |
| Unknown  | 2         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 420       | 55.7%   |
| Ethernet | 334       | 44.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 282       | 49.21%  |
| 1     | 263       | 45.9%   |
| 3     | 18        | 3.14%   |
| 0     | 7         | 1.22%   |
| 4     | 2         | 0.35%   |
| 5     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 432       | 74.61%  |
| Yes  | 147       | 25.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 254       | 59.21%  |
| Realtek Semiconductor           | 43        | 10.02%  |
| Qualcomm Atheros Communications | 22        | 5.13%   |
| Cambridge Silicon Radio         | 21        | 4.9%    |
| Apple                           | 20        | 4.66%   |
| Lite-On Technology              | 14        | 3.26%   |
| Broadcom                        | 11        | 2.56%   |
| IMC Networks                    | 10        | 2.33%   |
| Foxconn / Hon Hai               | 10        | 2.33%   |
| ASUSTek Computer                | 7         | 1.63%   |
| Realtek                         | 6         | 1.4%    |
| Ralink                          | 3         | 0.7%    |
| TP-Link                         | 2         | 0.47%   |
| MediaTek                        | 2         | 0.47%   |
| Marvell Semiconductor           | 2         | 0.47%   |
| Dell                            | 2         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 141       | 32.87%  |
| Intel AX200 Bluetooth                               | 55        | 12.82%  |
| Intel Bluetooth wireless interface                  | 35        | 8.16%   |
| Realtek Bluetooth Radio                             | 28        | 6.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 21        | 4.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 3.73%   |
| Apple Bluetooth Host Controller                     | 13        | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 2.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 2.1%    |
| Realtek Bluetooth Radio                             | 6         | 1.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 1.17%   |
| IMC Networks Wireless_Device                        | 5         | 1.17%   |
| Lite-On Wireless_Device                             | 4         | 0.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.93%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.93%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.93%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.7%    |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.7%    |
| Lite-On Bluetooth Device                            | 3         | 0.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.7%    |
| IMC Networks Bluetooth Radio                        | 3         | 0.7%    |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.7%    |
| TP-Link UB500 Adapter                               | 2         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.47%   |
| MediaTek Wireless_Device                            | 2         | 0.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.47%   |
| Foxconn / Hon Hai BT                                | 2         | 0.47%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.47%   |
| ASUS Bluetooth Radio                                | 2         | 0.47%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.23%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.23%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.23%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.23%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.23%   |
| IMC Networks Bluetooth Device                       | 1         | 0.23%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.23%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.23%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.23%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.23%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.23%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.23%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1         | 0.23%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 0.23%   |
| ASUS BCM20702A0                                     | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 387       | 46.85%  |
| AMD                         | 186       | 22.52%  |
| Nvidia                      | 132       | 15.98%  |
| C-Media Electronics         | 17        | 2.06%   |
| Lenovo                      | 10        | 1.21%   |
| GN Netcom                   | 9         | 1.09%   |
| Plantronics                 | 7         | 0.85%   |
| Realtek Semiconductor       | 6         | 0.73%   |
| Creative Labs               | 6         | 0.73%   |
| Texas Instruments           | 4         | 0.48%   |
| Razer USA                   | 4         | 0.48%   |
| Kingston Technology         | 4         | 0.48%   |
| SteelSeries ApS             | 3         | 0.36%   |
| Sennheiser Communications   | 3         | 0.36%   |
| SAVITECH                    | 3         | 0.36%   |
| CMX Systems                 | 3         | 0.36%   |
| Logitech                    | 2         | 0.24%   |
| JMTek                       | 2         | 0.24%   |
| Hewlett-Packard             | 2         | 0.24%   |
| Giga-Byte Technology        | 2         | 0.24%   |
| Generalplus Technology      | 2         | 0.24%   |
| Focusrite-Novation          | 2         | 0.24%   |
| Dell                        | 2         | 0.24%   |
| Creative Technology         | 2         | 0.24%   |
| Blue Microphones            | 2         | 0.24%   |
| Arturia                     | 2         | 0.24%   |
| Apple                       | 2         | 0.24%   |
| ZOOM                        | 1         | 0.12%   |
| Unknown                     | 1         | 0.12%   |
| Tenx Technology             | 1         | 0.12%   |
| Sony                        | 1         | 0.12%   |
| Samson Technologies         | 1         | 0.12%   |
| Micronas                    | 1         | 0.12%   |
| HECATE G2 GAMING HEADSET    | 1         | 0.12%   |
| GYROCOM C&C                 | 1         | 0.12%   |
| Goldvish                    | 1         | 0.12%   |
| Fujitsu                     | 1         | 0.12%   |
| FiiO Electronics Technology | 1         | 0.12%   |
| FIFINE Microphones          | 1         | 0.12%   |
| Elite Silicon               | 1         | 0.12%   |
| DigiTech                    | 1         | 0.12%   |
| Corsair                     | 1         | 0.12%   |
| Cooler Master               | 1         | 0.12%   |
| Conexant Systems            | 1         | 0.12%   |
| Audio-Technica              | 1         | 0.12%   |
| ASUSTek Computer            | 1         | 0.12%   |
| AKAI Professional M.I.      | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 87        | 8.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 66        | 6.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 53        | 5.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 40        | 4.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 35        | 3.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 32        | 3.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 27        | 2.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 2.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 23        | 2.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 2.21%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 18        | 1.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17        | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 1.61%   |
| Intel 8 Series HD Audio Controller                                         | 16        | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 14        | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 1.41%   |
| Nvidia Audio device                                                        | 14        | 1.41%   |
| AMD FCH Azalia Controller                                                  | 14        | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 1.31%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 13        | 1.31%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 12        | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 11        | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 0.91%   |
| AMD Navi 10 HDMI Audio                                                     | 9         | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 0.7%    |
| Intel Broadwell-U Audio Controller                                         | 7         | 0.7%    |
| Realtek Semiconductor USB Audio                                            | 6         | 0.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 0.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6         | 0.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 0.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.6%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 6         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 0.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6         | 0.6%    |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.5%    |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 5         | 0.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.5%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5         | 0.5%    |
| Intel 200 Series PCH HD Audio                                              | 5         | 0.5%    |
| AMD Trinity HDMI Audio Controller                                          | 5         | 0.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.4%    |
| C-Media Electronics USB Audio Device                                       | 4         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                         | 3         | 0.3%    |
| Nvidia GM206 High Definition Audio Controller                              | 3         | 0.3%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.3%    |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.3%    |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 0.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.3%    |
| Intel CM238 HD Audio Controller                                            | 3         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 94        | 27.33%  |
| SK Hynix            | 62        | 18.02%  |
| Micron Technology   | 46        | 13.37%  |
| Kingston            | 41        | 11.92%  |
| Crucial             | 30        | 8.72%   |
| Corsair             | 20        | 5.81%   |
| Unknown             | 18        | 5.23%   |
| G.Skill             | 7         | 2.03%   |
| A-DATA Technology   | 5         | 1.45%   |
| Team                | 4         | 1.16%   |
| Ramaxel Technology  | 2         | 0.58%   |
| Patriot             | 2         | 0.58%   |
| Avant               | 2         | 0.58%   |
| V-GeN               | 1         | 0.29%   |
| Unknown (ABCD)      | 1         | 0.29%   |
| Transcend           | 1         | 0.29%   |
| SMART Brazil        | 1         | 0.29%   |
| PLEXHD              | 1         | 0.29%   |
| OCZ                 | 1         | 0.29%   |
| Miron               | 1         | 0.29%   |
| GOODRAM             | 1         | 0.29%   |
| Goldkey             | 1         | 0.29%   |
| Elpida              | 1         | 0.29%   |
| Apacer              | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.63%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s          | 5         | 1.36%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.36%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.09%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 1.09%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 1.09%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.82%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.82%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 3         | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.82%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 0.82%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 3         | 0.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.82%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 3         | 0.82%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 3         | 0.82%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.54%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.54%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.54%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.54%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s                       | 2         | 0.54%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.54%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.54%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.54%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.54%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.54%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 2         | 0.54%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 0.54%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 2         | 0.54%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.54%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s             | 2         | 0.54%   |
| Samsung RAM K4E6E304EC-EGCG 4096MB Row Of Chips LPDDR3 2133MT/s  | 2         | 0.54%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.54%   |
| Kingston RAM Module 4GB DIMM DDR3 1066MT/s                       | 2         | 0.54%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s          | 2         | 0.54%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 0.54%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 2         | 0.54%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.54%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 0.54%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.54%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.54%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2667MT/s       | 2         | 0.54%   |
| Crucial RAM CT16G4SFD824A.C16FE 16GB SODIMM DDR4 2400MT/s        | 2         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 181       | 59.74%  |
| DDR3    | 73        | 24.09%  |
| LPDDR4  | 22        | 7.26%   |
| LPDDR3  | 14        | 4.62%   |
| Unknown | 7         | 2.31%   |
| DDR2    | 5         | 1.65%   |
| SDRAM   | 1         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 178       | 57.42%  |
| DIMM         | 82        | 26.45%  |
| Row Of Chips | 46        | 14.84%  |
| Chip         | 3         | 0.97%   |
| Unknown      | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 142       | 44.65%  |
| 4096  | 87        | 27.36%  |
| 16384 | 62        | 19.5%   |
| 2048  | 18        | 5.66%   |
| 32768 | 8         | 2.52%   |
| 1024  | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 74        | 22.98%  |
| 2667  | 56        | 17.39%  |
| 1600  | 51        | 15.84%  |
| 2400  | 25        | 7.76%   |
| 2133  | 21        | 6.52%   |
| 4267  | 14        | 4.35%   |
| 1333  | 11        | 3.42%   |
| 3600  | 8         | 2.48%   |
| 3266  | 7         | 2.17%   |
| 1867  | 6         | 1.86%   |
| 1067  | 6         | 1.86%   |
| 800   | 6         | 1.86%   |
| 2933  | 5         | 1.55%   |
| 3400  | 4         | 1.24%   |
| 1066  | 4         | 1.24%   |
| 4266  | 3         | 0.93%   |
| 3733  | 3         | 0.93%   |
| 3466  | 3         | 0.93%   |
| 2666  | 3         | 0.93%   |
| 3533  | 2         | 0.62%   |
| 3000  | 2         | 0.62%   |
| 1334  | 2         | 0.62%   |
| 4800  | 1         | 0.31%   |
| 4199  | 1         | 0.31%   |
| 2800  | 1         | 0.31%   |
| 1866  | 1         | 0.31%   |
| 1024  | 1         | 0.31%   |
| 667   | 1         | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 30%     |
| Samsung Electronics | 2         | 20%     |
| Canon               | 2         | 20%     |
| Prolific Technology | 1         | 10%     |
| Kyocera             | 1         | 10%     |
| Hewlett-Packard     | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother HL-L2340D series      | 2         | 20%     |
| Samsung SCX-3200 Series       | 1         | 10%     |
| Samsung CLX-6260 Series       | 1         | 10%     |
| Prolific PL2305 Parallel Port | 1         | 10%     |
| Kyocera ECOSYS M5521cdw       | 1         | 10%     |
| HP LaserJet CM1415fnw         | 1         | 10%     |
| Canon TR4500 series           | 1         | 10%     |
| Canon MF4010 series           | 1         | 10%     |
| Brother HL-L2360D series      | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 210 | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 96        | 23.24%  |
| IMC Networks                           | 40        | 9.69%   |
| Acer                                   | 37        | 8.96%   |
| Logitech                               | 35        | 8.47%   |
| Realtek Semiconductor                  | 32        | 7.75%   |
| Microdia                               | 30        | 7.26%   |
| Quanta                                 | 29        | 7.02%   |
| Sunplus Innovation Technology          | 15        | 3.63%   |
| Apple                                  | 14        | 3.39%   |
| Syntek                                 | 12        | 2.91%   |
| Lite-On Technology                     | 12        | 2.91%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.66%   |
| Suyin                                  | 8         | 1.94%   |
| Luxvisions Innotech Limited            | 7         | 1.69%   |
| Samsung Electronics                    | 4         | 0.97%   |
| Microsoft                              | 4         | 0.97%   |
| Silicon Motion                         | 3         | 0.73%   |
| Z-Star Microelectronics                | 2         | 0.48%   |
| Ricoh                                  | 2         | 0.48%   |
| KYE Systems (Mouse Systems)            | 2         | 0.48%   |
| Generalplus Technology                 | 2         | 0.48%   |
| DLEQNA1G4FA2WJ                         | 2         | 0.48%   |
| Tobii Technology AB                    | 1         | 0.24%   |
| Sonix Technology                       | 1         | 0.24%   |
| Razer USA                              | 1         | 0.24%   |
| Pixart Imaging                         | 1         | 0.24%   |
| Micro Star International               | 1         | 0.24%   |
| MacroSilicon                           | 1         | 0.24%   |
| LG Electronics                         | 1         | 0.24%   |
| Lenovo                                 | 1         | 0.24%   |
| Hewlett-Packard                        | 1         | 0.24%   |
| Cubeternet                             | 1         | 0.24%   |
| Creative Technology                    | 1         | 0.24%   |
| ARC International                      | 1         | 0.24%   |
| Alcor Micro                            | 1         | 0.24%   |
| 8SSC20F27114V1SR0CV12SG                | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 34        | 8.1%    |
| Microdia Integrated_Webcam_HD                        | 22        | 5.24%   |
| IMC Networks Integrated Camera                       | 19        | 4.52%   |
| Realtek Integrated_Webcam_HD                         | 17        | 4.05%   |
| Acer Integrated Camera                               | 16        | 3.81%   |
| Syntek Integrated Camera                             | 10        | 2.38%   |
| Quanta HD User Facing                                | 10        | 2.38%   |
| Logitech Webcam C270                                 | 9         | 2.14%   |
| Sunplus Integrated_Webcam_HD                         | 8         | 1.9%    |
| Logitech HD Pro Webcam C920                          | 7         | 1.67%   |
| Apple Built-in iSight                                | 7         | 1.67%   |
| Quanta HP TrueVision HD Camera                       | 6         | 1.43%   |
| Chicony Integrated Camera (1280x720@30)              | 6         | 1.43%   |
| Chicony HP HD Camera                                 | 6         | 1.43%   |
| Chicony HD Webcam                                    | 6         | 1.43%   |
| Microdia Integrated Webcam                           | 5         | 1.19%   |
| Logitech C922 Pro Stream Webcam                      | 5         | 1.19%   |
| IMC Networks HD Camera                               | 5         | 1.19%   |
| Samsung Galaxy A5 (MTP)                              | 4         | 0.95%   |
| Quanta HP Wide Vision HD Camera                      | 4         | 0.95%   |
| Lite-On Integrated Camera                            | 4         | 0.95%   |
| Lite-On HP HD Camera                                 | 4         | 0.95%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 0.95%   |
| Chicony HP Wide Vision HD Camera                     | 4         | 0.95%   |
| Acer SunplusIT Integrated Camera                     | 4         | 0.95%   |
| Acer BisonCam,NB Pro                                 | 4         | 0.95%   |
| Suyin HP TrueVision HD Integrated Webcam             | 3         | 0.71%   |
| Realtek Integrated Webcam HD                         | 3         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 0.71%   |
| Chicony USB2.0 Camera                                | 3         | 0.71%   |
| Chicony USB 2.0 Camera                               | 3         | 0.71%   |
| Chicony EasyCamera                                   | 3         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera  | 3         | 0.71%   |
| Apple FaceTime HD Camera                             | 3         | 0.71%   |
| Acer HD Webcam                                       | 3         | 0.71%   |
| Acer BisonCam, NB Pro                                | 3         | 0.71%   |
| Syntek EasyCamera                                    | 2         | 0.48%   |
| Suyin Integrated_Webcam_HD                           | 2         | 0.48%   |
| Sunplus Depstech webcam MIC                          | 2         | 0.48%   |
| Realtek USB Camera                                   | 2         | 0.48%   |
| Realtek Laptop Camera                                | 2         | 0.48%   |
| Realtek HD WebCam                                    | 2         | 0.48%   |
| Quanta VGA WebCam                                    | 2         | 0.48%   |
| Quanta HP HD Camera                                  | 2         | 0.48%   |
| Microsoft LifeCam Cinema                             | 2         | 0.48%   |
| Microdia HP Integrated Webcam                        | 2         | 0.48%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 0.48%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.48%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 0.48%   |
| Logitech Webcam C930e                                | 2         | 0.48%   |
| Logitech StreamCam                                   | 2         | 0.48%   |
| Logitech QuickCam Pro 9000                           | 2         | 0.48%   |
| Logitech HD Webcam C525                              | 2         | 0.48%   |
| Lite-On HP HD Webcam                                 | 2         | 0.48%   |
| IMC Networks ov9734_azurewave_camera                 | 2         | 0.48%   |
| IMC Networks HP TrueVision HD Camera                 | 2         | 0.48%   |
| DLEQNA1G4FA2WJ HP TrueVision HD Camera               | 2         | 0.48%   |
| Chicony VGA WebCam                                   | 2         | 0.48%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 2         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 49        | 43.75%  |
| Validity Sensors           | 28        | 25%     |
| Shenzhen Goodix Technology | 26        | 23.21%  |
| LighTuning Technology      | 4         | 3.57%   |
| Elan Microelectronics      | 4         | 3.57%   |
| Upek                       | 1         | 0.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 21.43%  |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 13.39%  |
| Unknown                                                                    | 10        | 8.93%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 5.36%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 4.46%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.57%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.57%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.79%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.79%   |
| Validity Sensors VFS491                                                    | 1         | 0.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.89%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 0.89%   |
| Synaptics WBDI Device                                                      | 1         | 0.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.89%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 15        | 50%     |
| Broadcom    | 12        | 40%     |
| Upek        | 1         | 3.33%   |
| O2 Micro    | 1         | 3.33%   |
| Lenovo      | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 50%     |
| Broadcom 5880                                                                | 5         | 16.67%  |
| Broadcom 58200                                                               | 4         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 378       | 65.4%   |
| 1     | 163       | 28.2%   |
| 2     | 31        | 5.36%   |
| 3     | 4         | 0.69%   |
| 4     | 2         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 109       | 45.99%  |
| Graphics card            | 45        | 18.99%  |
| Multimedia controller    | 25        | 10.55%  |
| Net/wireless             | 24        | 10.13%  |
| Camera                   | 10        | 4.22%   |
| Chipcard                 | 7         | 2.95%   |
| Bluetooth                | 5         | 2.11%   |
| Communication controller | 4         | 1.69%   |
| Card reader              | 3         | 1.27%   |
| Unassigned class         | 2         | 0.84%   |
| Sound                    | 1         | 0.42%   |
| Network                  | 1         | 0.42%   |
| Net/ethernet             | 1         | 0.42%   |

