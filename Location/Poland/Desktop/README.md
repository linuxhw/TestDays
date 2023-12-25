Linux in Poland - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3359

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | Z790 PG Lightning           | [0b5268372a](https://linux-hardware.org/?probe=0b5268372a) | Dec 24, 2023 |
| Gigabyte      | X670 GAMING X AX            | [4452cd4a25](https://linux-hardware.org/?probe=4452cd4a25) | Dec 24, 2023 |
| ASUSTek       | P7P55D-E PRO                | [ef61ad2663](https://linux-hardware.org/?probe=ef61ad2663) | Dec 24, 2023 |
| Dell          | 09KPNV A00                  | [a90623afe1](https://linux-hardware.org/?probe=a90623afe1) | Dec 23, 2023 |
| ASUSTek       | P7P55D-E                    | [dc2914021f](https://linux-hardware.org/?probe=dc2914021f) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [739d4b0840](https://linux-hardware.org/?probe=739d4b0840) | Dec 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [da051b693c](https://linux-hardware.org/?probe=da051b693c) | Dec 23, 2023 |
| ASUSTek       | B85-PLUS                    | [58a2ef76f9](https://linux-hardware.org/?probe=58a2ef76f9) | Dec 22, 2023 |
| Hampoo        | Cherry Trail CR             | [2c180fa555](https://linux-hardware.org/?probe=2c180fa555) | Dec 20, 2023 |
| MSI           | B450-A PRO MAX              | [f46e034f2c](https://linux-hardware.org/?probe=f46e034f2c) | Dec 20, 2023 |
| Dell          | 0T10XW A00                  | [ffff088d9c](https://linux-hardware.org/?probe=ffff088d9c) | Dec 18, 2023 |
| ASUSTek       | M3A78-CM                    | [89fd7ee431](https://linux-hardware.org/?probe=89fd7ee431) | Dec 18, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [3504b628f1](https://linux-hardware.org/?probe=3504b628f1) | Dec 18, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e0b7c61c9f](https://linux-hardware.org/?probe=e0b7c61c9f) | Dec 18, 2023 |
| ASRock        | AB350M-HDV                  | [2860ba102d](https://linux-hardware.org/?probe=2860ba102d) | Dec 18, 2023 |
| ASRock        | AB350M-HDV                  | [8d45a13b61](https://linux-hardware.org/?probe=8d45a13b61) | Dec 17, 2023 |
| MSI           | MS-7255                     | [efdf3ede47](https://linux-hardware.org/?probe=efdf3ede47) | Dec 17, 2023 |
| Gigabyte      | GA-MA69G-S3H                | [d0b623f72b](https://linux-hardware.org/?probe=d0b623f72b) | Dec 17, 2023 |
| Inventec      | DQ Class A02                | [73df6dfb3b](https://linux-hardware.org/?probe=73df6dfb3b) | Dec 16, 2023 |
| HP            | 8265                        | [58cc9fa090](https://linux-hardware.org/?probe=58cc9fa090) | Dec 16, 2023 |
| Dell          | 03NVJ6 A02                  | [7f5a3db82c](https://linux-hardware.org/?probe=7f5a3db82c) | Dec 15, 2023 |
| HP            | 1495                        | [bd97989dd8](https://linux-hardware.org/?probe=bd97989dd8) | Dec 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c8d2a05aea](https://linux-hardware.org/?probe=c8d2a05aea) | Dec 14, 2023 |
| ASUSTek       | M5A78L-M LX3                | [a51734cec9](https://linux-hardware.org/?probe=a51734cec9) | Dec 13, 2023 |
| ASUSTek       | P8H61                       | [6f5272ea27](https://linux-hardware.org/?probe=6f5272ea27) | Dec 13, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [0e87f04695](https://linux-hardware.org/?probe=0e87f04695) | Dec 12, 2023 |
| Gigabyte      | 970A-UD3P                   | [82f5fec0c4](https://linux-hardware.org/?probe=82f5fec0c4) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | [2f96568c78](https://linux-hardware.org/?probe=2f96568c78) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | [68fe94d3be](https://linux-hardware.org/?probe=68fe94d3be) | Dec 12, 2023 |
| ASRock        | B650M PG Riptide            | [9b92833e92](https://linux-hardware.org/?probe=9b92833e92) | Dec 12, 2023 |
| MSI           | H61M-E33                    | [6123a79100](https://linux-hardware.org/?probe=6123a79100) | Dec 12, 2023 |
| Gigabyte      | B150M-D3H-CF                | [a46aa4d97c](https://linux-hardware.org/?probe=a46aa4d97c) | Dec 11, 2023 |
| ASUSTek       | P8Z77-V LX                  | [9e23503add](https://linux-hardware.org/?probe=9e23503add) | Dec 11, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [e07d68d658](https://linux-hardware.org/?probe=e07d68d658) | Dec 11, 2023 |
| ASUSTek       | M3A78-CM                    | [8bf4107eed](https://linux-hardware.org/?probe=8bf4107eed) | Dec 11, 2023 |
| Gigabyte      | 970A-DS3P                   | [71de71e3f4](https://linux-hardware.org/?probe=71de71e3f4) | Dec 10, 2023 |
| Gigabyte      | P67A-UD3P-B3                | [e96b9306cb](https://linux-hardware.org/?probe=e96b9306cb) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | [64b0038221](https://linux-hardware.org/?probe=64b0038221) | Dec 10, 2023 |
| ASUSTek       | B150M-A/M.2                 | [dd4ad4373b](https://linux-hardware.org/?probe=dd4ad4373b) | Dec 10, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [a960a2a5b7](https://linux-hardware.org/?probe=a960a2a5b7) | Dec 10, 2023 |
| Dell          | 0HY9JP A02                  | [25d8aaca3c](https://linux-hardware.org/?probe=25d8aaca3c) | Dec 10, 2023 |
| ASRock        | B450 Gaming K4              | [581807905e](https://linux-hardware.org/?probe=581807905e) | Dec 10, 2023 |
| ASRock        | AB350 Pro4                  | [514239398e](https://linux-hardware.org/?probe=514239398e) | Dec 09, 2023 |
| Dell          | 0NDYHG A01                  | [f7f70db230](https://linux-hardware.org/?probe=f7f70db230) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [cc6cd166f2](https://linux-hardware.org/?probe=cc6cd166f2) | Dec 08, 2023 |
| MSI           | G31TM-P35                   | [e241cfaeca](https://linux-hardware.org/?probe=e241cfaeca) | Dec 08, 2023 |
| Dell          | 0KP561                      | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| HP            | 1495                        | [361c8f4360](https://linux-hardware.org/?probe=361c8f4360) | Dec 07, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [3c37d1bb9f](https://linux-hardware.org/?probe=3c37d1bb9f) | Dec 07, 2023 |
| Foxconn       | 2A8C                        | [2a4412d268](https://linux-hardware.org/?probe=2a4412d268) | Dec 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [9b6cdd96f4](https://linux-hardware.org/?probe=9b6cdd96f4) | Dec 06, 2023 |
| Dell          | 0T1D10 A01                  | [5fa41b15bb](https://linux-hardware.org/?probe=5fa41b15bb) | Dec 05, 2023 |
| MSI           | 2A9C                        | [2ae992c0d5](https://linux-hardware.org/?probe=2ae992c0d5) | Dec 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [15d4dc2fe9](https://linux-hardware.org/?probe=15d4dc2fe9) | Dec 05, 2023 |
| Dell          | 0T1D10 A01                  | [65d5ddf61f](https://linux-hardware.org/?probe=65d5ddf61f) | Dec 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6d790b9d8c](https://linux-hardware.org/?probe=6d790b9d8c) | Dec 05, 2023 |
| Dell          | 0FG011                      | [4a5701f000](https://linux-hardware.org/?probe=4a5701f000) | Dec 04, 2023 |
| Acer          | Veriton S6620G v1.0         | [34095bbfed](https://linux-hardware.org/?probe=34095bbfed) | Dec 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [1fe1dc7462](https://linux-hardware.org/?probe=1fe1dc7462) | Dec 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | [4fd5ba2289](https://linux-hardware.org/?probe=4fd5ba2289) | Dec 04, 2023 |
| Gigabyte      | H77-DS3H                    | [4c97431f16](https://linux-hardware.org/?probe=4c97431f16) | Dec 03, 2023 |
| MSI           | B85M-E43 DASH               | [b9caa2d56f](https://linux-hardware.org/?probe=b9caa2d56f) | Dec 02, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [436f0406e4](https://linux-hardware.org/?probe=436f0406e4) | Dec 01, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [f3f624e1cf](https://linux-hardware.org/?probe=f3f624e1cf) | Nov 30, 2023 |
| MSI           | A78M-E45                    | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| Gigabyte      | H61M-S1                     | [cc54ea37ef](https://linux-hardware.org/?probe=cc54ea37ef) | Nov 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e39e2b268d](https://linux-hardware.org/?probe=e39e2b268d) | Nov 30, 2023 |
| ASRock        | 970 Extreme4                | [5dd27edbe4](https://linux-hardware.org/?probe=5dd27edbe4) | Nov 29, 2023 |
| Gigabyte      | B75M-D3H                    | [6a3776da6b](https://linux-hardware.org/?probe=6a3776da6b) | Nov 29, 2023 |
| ASRock        | J3355M                      | [a767ff37ed](https://linux-hardware.org/?probe=a767ff37ed) | Nov 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [655dc71f64](https://linux-hardware.org/?probe=655dc71f64) | Nov 29, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c6673a5a66](https://linux-hardware.org/?probe=c6673a5a66) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [2df2a6f5d8](https://linux-hardware.org/?probe=2df2a6f5d8) | Nov 28, 2023 |
| Dell          | 0NW6H5 A00                  | [1a855ee74d](https://linux-hardware.org/?probe=1a855ee74d) | Nov 27, 2023 |
| ASUSTek       | F2A85-M                     | [0c272521ab](https://linux-hardware.org/?probe=0c272521ab) | Nov 27, 2023 |
| Gigabyte      | B75M-D3V                    | [142a3240d4](https://linux-hardware.org/?probe=142a3240d4) | Nov 27, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [1d71979dbb](https://linux-hardware.org/?probe=1d71979dbb) | Nov 27, 2023 |
| Dell          | 0DR845                      | [e09cfb8e7a](https://linux-hardware.org/?probe=e09cfb8e7a) | Nov 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [2a04ec7adc](https://linux-hardware.org/?probe=2a04ec7adc) | Nov 27, 2023 |
| Gigabyte      | B560M D3H                   | [8a894da286](https://linux-hardware.org/?probe=8a894da286) | Nov 26, 2023 |
| MSI           | X570-A PRO                  | [17cd5f34c3](https://linux-hardware.org/?probe=17cd5f34c3) | Nov 25, 2023 |
| MSI           | PRO B760M-P DDR4            | [462b5c65a7](https://linux-hardware.org/?probe=462b5c65a7) | Nov 25, 2023 |
| ASRock        | H110M-HDS                   | [8e326dd485](https://linux-hardware.org/?probe=8e326dd485) | Nov 25, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fb9766adc5](https://linux-hardware.org/?probe=fb9766adc5) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| Dell          | 084J0R A00                  | [387b322a8e](https://linux-hardware.org/?probe=387b322a8e) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [5417165a43](https://linux-hardware.org/?probe=5417165a43) | Nov 24, 2023 |
| ASRock        | B450 Gaming K4              | [ee82d7417c](https://linux-hardware.org/?probe=ee82d7417c) | Nov 23, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [e0781004e0](https://linux-hardware.org/?probe=e0781004e0) | Nov 22, 2023 |
| Gigabyte      | F2A75M-HD2                  | [1370f43083](https://linux-hardware.org/?probe=1370f43083) | Nov 22, 2023 |
| ASUSTek       | M3A78-CM                    | [4eae08c59f](https://linux-hardware.org/?probe=4eae08c59f) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| MSI           | PRO H610M-B DDR4            | [f9da55efe2](https://linux-hardware.org/?probe=f9da55efe2) | Nov 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [56c19073cb](https://linux-hardware.org/?probe=56c19073cb) | Nov 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | [4ceda102e6](https://linux-hardware.org/?probe=4ceda102e6) | Nov 20, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [8d33a8020d](https://linux-hardware.org/?probe=8d33a8020d) | Nov 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [ac6d14ae8d](https://linux-hardware.org/?probe=ac6d14ae8d) | Nov 20, 2023 |
| Gigabyte      | GA-MA69G-S3H                | [7a812fcce7](https://linux-hardware.org/?probe=7a812fcce7) | Nov 20, 2023 |
| HP            | 8054                        | [2ccc2c67f2](https://linux-hardware.org/?probe=2ccc2c67f2) | Nov 20, 2023 |
| eMachines     | ET1850                      | [0bcca3431b](https://linux-hardware.org/?probe=0bcca3431b) | Nov 18, 2023 |
| ASRock        | B450M Pro4 R2.0             | [5383dca9b2](https://linux-hardware.org/?probe=5383dca9b2) | Nov 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | [66c6f85ec1](https://linux-hardware.org/?probe=66c6f85ec1) | Nov 17, 2023 |
| Acer          | Nitro N50-610               | [648f624587](https://linux-hardware.org/?probe=648f624587) | Nov 16, 2023 |
| Gigabyte      | H61M-S1                     | [5c4603de9d](https://linux-hardware.org/?probe=5c4603de9d) | Nov 16, 2023 |
| MSI           | H61M-P20                    | [237c033c24](https://linux-hardware.org/?probe=237c033c24) | Nov 15, 2023 |
| Medion        | DN2820FYB-IS BTNUCW08.11... | [def1bf43ff](https://linux-hardware.org/?probe=def1bf43ff) | Nov 15, 2023 |
| MSI           | MEG X570 UNIFY              | [d2cafb1814](https://linux-hardware.org/?probe=d2cafb1814) | Nov 15, 2023 |
| ASUSTek       | P10S-I Series               | [f27cfbe5ca](https://linux-hardware.org/?probe=f27cfbe5ca) | Nov 15, 2023 |
| MSI           | Z97-G43                     | [ea16582cb2](https://linux-hardware.org/?probe=ea16582cb2) | Nov 14, 2023 |
| Dell          | 0PGKWF A02                  | [3025cd2250](https://linux-hardware.org/?probe=3025cd2250) | Nov 14, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [2ed7720fa6](https://linux-hardware.org/?probe=2ed7720fa6) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6f0d8ee5da](https://linux-hardware.org/?probe=6f0d8ee5da) | Nov 13, 2023 |
| ASUSTek       | M3A78-CM                    | [8080101e6f](https://linux-hardware.org/?probe=8080101e6f) | Nov 13, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [de369665dc](https://linux-hardware.org/?probe=de369665dc) | Nov 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [9d2aeb3f90](https://linux-hardware.org/?probe=9d2aeb3f90) | Nov 13, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [edf208cfd3](https://linux-hardware.org/?probe=edf208cfd3) | Nov 12, 2023 |
| MSI           | PRO X670-P WIFI             | [572825e302](https://linux-hardware.org/?probe=572825e302) | Nov 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [bedc6fd7f0](https://linux-hardware.org/?probe=bedc6fd7f0) | Nov 11, 2023 |
| HP            | 1850                        | [117ab7ea0d](https://linux-hardware.org/?probe=117ab7ea0d) | Nov 11, 2023 |
| MSI           | MS-B0A21                    | [c9d19c0810](https://linux-hardware.org/?probe=c9d19c0810) | Nov 11, 2023 |
| MSI           | P55-GD65                    | [5a95aca3cc](https://linux-hardware.org/?probe=5a95aca3cc) | Nov 11, 2023 |
| HP            | 1850                        | [10595f0ac3](https://linux-hardware.org/?probe=10595f0ac3) | Nov 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [6f20a56938](https://linux-hardware.org/?probe=6f20a56938) | Nov 09, 2023 |
| Gigabyte      | H61M-S1                     | [bb13a5b1c7](https://linux-hardware.org/?probe=bb13a5b1c7) | Nov 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [656bd0c4c2](https://linux-hardware.org/?probe=656bd0c4c2) | Nov 09, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [02154de863](https://linux-hardware.org/?probe=02154de863) | Nov 08, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c4f7fd2835](https://linux-hardware.org/?probe=c4f7fd2835) | Nov 08, 2023 |
| HP            | 339A                        | [cdcbe8d47d](https://linux-hardware.org/?probe=cdcbe8d47d) | Nov 07, 2023 |
| ASRock        | B550M Pro4                  | [665120f441](https://linux-hardware.org/?probe=665120f441) | Nov 07, 2023 |
| Dell          | 0JCTF8 A00                  | [1f3f493cb1](https://linux-hardware.org/?probe=1f3f493cb1) | Nov 07, 2023 |
| MSI           | B85M-E45                    | [a2b6c4ab44](https://linux-hardware.org/?probe=a2b6c4ab44) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| MSI           | B560M PRO-E                 | [89a24ae9fa](https://linux-hardware.org/?probe=89a24ae9fa) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| Dell          | 0JCTF8 A00                  | [b3669f73a8](https://linux-hardware.org/?probe=b3669f73a8) | Nov 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [2cbd472a6e](https://linux-hardware.org/?probe=2cbd472a6e) | Nov 05, 2023 |
| MSI           | B560M PRO-E                 | [1488a8a70f](https://linux-hardware.org/?probe=1488a8a70f) | Nov 05, 2023 |
| Lenovo        | SKYBAY NOK                  | [534fcded19](https://linux-hardware.org/?probe=534fcded19) | Nov 05, 2023 |
| Gigabyte      | H510M S2H V2                | [29fc753f1e](https://linux-hardware.org/?probe=29fc753f1e) | Nov 04, 2023 |
| HP            | 21D0                        | [160964fbab](https://linux-hardware.org/?probe=160964fbab) | Nov 04, 2023 |
| HP            | 89B5 A                      | [e31ecc3904](https://linux-hardware.org/?probe=e31ecc3904) | Nov 04, 2023 |
| Gigabyte      | H510M S2H V2                | [2d4845b6b9](https://linux-hardware.org/?probe=2d4845b6b9) | Nov 03, 2023 |
| ASUSTek       | M3A78-CM                    | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| Dell          | 0J3C2F A00                  | [a9ed160c1c](https://linux-hardware.org/?probe=a9ed160c1c) | Nov 01, 2023 |
| ASUSTek       | Z97-AR                      | [39741158bc](https://linux-hardware.org/?probe=39741158bc) | Nov 01, 2023 |
| MSI           | B550-A PRO                  | [fca3ef2e73](https://linux-hardware.org/?probe=fca3ef2e73) | Oct 30, 2023 |
| Dell          | 03NVJ6 A01                  | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| Shenzhen M... | TH80                        | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| Dell          | 0JCTF8 A00                  | [3cc39678ff](https://linux-hardware.org/?probe=3cc39678ff) | Oct 27, 2023 |
| MSI           | Z170A PC MATE               | [e76ead66bc](https://linux-hardware.org/?probe=e76ead66bc) | Oct 27, 2023 |
| ASRock        | B450 Gaming K4              | [15488b723a](https://linux-hardware.org/?probe=15488b723a) | Oct 27, 2023 |
| ASUSTek       | M3A78-CM                    | [54aa16ef1e](https://linux-hardware.org/?probe=54aa16ef1e) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [700ceddf43](https://linux-hardware.org/?probe=700ceddf43) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [f43adee740](https://linux-hardware.org/?probe=f43adee740) | Oct 26, 2023 |
| MSI           | MEG X570 UNIFY              | [f1bcad7519](https://linux-hardware.org/?probe=f1bcad7519) | Oct 26, 2023 |
| ASRock        | Z370 Killer SLI             | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| Gigabyte      | 965P-DS3                    | [b33d6b8a3c](https://linux-hardware.org/?probe=b33d6b8a3c) | Oct 24, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [67564f88a0](https://linux-hardware.org/?probe=67564f88a0) | Oct 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | [6f72e3839d](https://linux-hardware.org/?probe=6f72e3839d) | Oct 23, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [def0406ec0](https://linux-hardware.org/?probe=def0406ec0) | Oct 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [6ef12aa776](https://linux-hardware.org/?probe=6ef12aa776) | Oct 23, 2023 |
| ASUSTek       | M3A78-CM                    | [e8d5f9186c](https://linux-hardware.org/?probe=e8d5f9186c) | Oct 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [2ca3451a04](https://linux-hardware.org/?probe=2ca3451a04) | Oct 20, 2023 |
| ASRock        | B450 Gaming K4              | [65f3d76afa](https://linux-hardware.org/?probe=65f3d76afa) | Oct 19, 2023 |
| ASRock        | A88M-G                      | [05d17c88b7](https://linux-hardware.org/?probe=05d17c88b7) | Oct 18, 2023 |
| MSI           | B350 PC MATE                | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [cc5a77d2c3](https://linux-hardware.org/?probe=cc5a77d2c3) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [04afaee575](https://linux-hardware.org/?probe=04afaee575) | Oct 15, 2023 |
| HP            | 1589                        | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [dfee331121](https://linux-hardware.org/?probe=dfee331121) | Oct 15, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [af4857609e](https://linux-hardware.org/?probe=af4857609e) | Oct 15, 2023 |
| ASUSTek       | B85M-E                      | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| ACTION        | M5A78L-M lX V2              | [fe141a8a31](https://linux-hardware.org/?probe=fe141a8a31) | Oct 15, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [0400bae582](https://linux-hardware.org/?probe=0400bae582) | Oct 12, 2023 |
| Gigabyte      | H81M-HD3                    | [32ffcc827b](https://linux-hardware.org/?probe=32ffcc827b) | Oct 12, 2023 |
| Gigabyte      | H81M-HD3                    | [c3992a85f0](https://linux-hardware.org/?probe=c3992a85f0) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [078d4619a6](https://linux-hardware.org/?probe=078d4619a6) | Oct 09, 2023 |
| HP            | 83E8                        | [c1028de72b](https://linux-hardware.org/?probe=c1028de72b) | Oct 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| MSI           | MS-7235                     | [afb00bf553](https://linux-hardware.org/?probe=afb00bf553) | Oct 07, 2023 |
| Dell          | 0NW6H5 A00                  | [665a7ff2eb](https://linux-hardware.org/?probe=665a7ff2eb) | Oct 06, 2023 |
| ASUSTek       | P8H77-M PRO                 | [355bc3fdfc](https://linux-hardware.org/?probe=355bc3fdfc) | Oct 06, 2023 |
| MSI           | X570-A PRO                  | [fbd07d95c2](https://linux-hardware.org/?probe=fbd07d95c2) | Oct 06, 2023 |
| ASUSTek       | P5G41T-M LX                 | [21ec0f4129](https://linux-hardware.org/?probe=21ec0f4129) | Oct 06, 2023 |
| Intel         | X99                         | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f496e4dfff](https://linux-hardware.org/?probe=f496e4dfff) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| ASUSTek       | PRIME Z790-P                | [5529ffcf1b](https://linux-hardware.org/?probe=5529ffcf1b) | Oct 05, 2023 |
| ASRock        | P4i945GC                    | [9e7c1b2d58](https://linux-hardware.org/?probe=9e7c1b2d58) | Oct 04, 2023 |
| ASUSTek       | PRIME Z790-P                | [18675da607](https://linux-hardware.org/?probe=18675da607) | Oct 04, 2023 |
| HP            | 1589                        | [75f8ba109d](https://linux-hardware.org/?probe=75f8ba109d) | Oct 04, 2023 |
| Dell          | 0HY9JP A02                  | [e7b2bada83](https://linux-hardware.org/?probe=e7b2bada83) | Oct 04, 2023 |
| Dell          | 0HY9JP A02                  | [57b66fc6eb](https://linux-hardware.org/?probe=57b66fc6eb) | Oct 04, 2023 |
| ASUSTek       | M3A78-CM                    | [27d781a357](https://linux-hardware.org/?probe=27d781a357) | Oct 04, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [ea10bf8eab](https://linux-hardware.org/?probe=ea10bf8eab) | Oct 02, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [43062f3c9a](https://linux-hardware.org/?probe=43062f3c9a) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b8068a8e68](https://linux-hardware.org/?probe=b8068a8e68) | Oct 02, 2023 |
| MSI           | 970 GAMING                  | [c095e62997](https://linux-hardware.org/?probe=c095e62997) | Oct 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [cbd8df2f8a](https://linux-hardware.org/?probe=cbd8df2f8a) | Oct 02, 2023 |
| Sapphire      | PI-AM3RS760G2               | [06371cc0f7](https://linux-hardware.org/?probe=06371cc0f7) | Oct 01, 2023 |
| ASRock        | FM2A55M-VG3+                | [6faa4fd636](https://linux-hardware.org/?probe=6faa4fd636) | Oct 01, 2023 |
| ASUSTek       | P8H77-M PRO                 | [63c99972d1](https://linux-hardware.org/?probe=63c99972d1) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [0e4e90fac1](https://linux-hardware.org/?probe=0e4e90fac1) | Sep 29, 2023 |
| HP            | 886C                        | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| ASUSTek       | M3A78-CM                    | [4ef9eaaaba](https://linux-hardware.org/?probe=4ef9eaaaba) | Sep 27, 2023 |
| HP            | 1589                        | [1063a6e665](https://linux-hardware.org/?probe=1063a6e665) | Sep 27, 2023 |
| ASUSTek       | PRIME B450M-A II            | [8e70938939](https://linux-hardware.org/?probe=8e70938939) | Sep 27, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [09a71cddc4](https://linux-hardware.org/?probe=09a71cddc4) | Sep 26, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [32a39c6a01](https://linux-hardware.org/?probe=32a39c6a01) | Sep 25, 2023 |
| Gigabyte      | Z97M-DS3H                   | [2881d9e4ec](https://linux-hardware.org/?probe=2881d9e4ec) | Sep 25, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [4c68092d28](https://linux-hardware.org/?probe=4c68092d28) | Sep 25, 2023 |
| ASUSTek       | P8H77-M PRO                 | [3afc2a0804](https://linux-hardware.org/?probe=3afc2a0804) | Sep 24, 2023 |
| Huanan        | X99-TF V1.1                 | [694b4ab1f2](https://linux-hardware.org/?probe=694b4ab1f2) | Sep 24, 2023 |
| HP            | 3397                        | [cc6f1cc8ba](https://linux-hardware.org/?probe=cc6f1cc8ba) | Sep 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [da4274c691](https://linux-hardware.org/?probe=da4274c691) | Sep 24, 2023 |
| ASUSTek       | P5G41T-M LX3                | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| ASUSTek       | P5K                         | [4d67ad50cf](https://linux-hardware.org/?probe=4d67ad50cf) | Sep 22, 2023 |
| ASUSTek       | X99-A/USB                   | [37990955f8](https://linux-hardware.org/?probe=37990955f8) | Sep 21, 2023 |
| MSI           | PRO B650M-A WIFI            | [8e60d0df9c](https://linux-hardware.org/?probe=8e60d0df9c) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [459e666cd3](https://linux-hardware.org/?probe=459e666cd3) | Sep 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [dfb78764ea](https://linux-hardware.org/?probe=dfb78764ea) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| HP            | 3047h                       | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| ASUSTek       | Maximus IX FORMULA          | [e76f3de142](https://linux-hardware.org/?probe=e76f3de142) | Sep 19, 2023 |
| ASUSTek       | M3A78-CM                    | [0748266b0a](https://linux-hardware.org/?probe=0748266b0a) | Sep 19, 2023 |
| Medion        | MS-7848                     | [acbe0e1821](https://linux-hardware.org/?probe=acbe0e1821) | Sep 19, 2023 |
| ASUSTek       | PRIME B460-PLUS             | [1ac41cc2e4](https://linux-hardware.org/?probe=1ac41cc2e4) | Sep 19, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [5680b32e39](https://linux-hardware.org/?probe=5680b32e39) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| Gigabyte      | X570 GAMING X               | [8af23c2e56](https://linux-hardware.org/?probe=8af23c2e56) | Sep 17, 2023 |
| MSI           | X470 GAMING PLUS            | [35d0dc4629](https://linux-hardware.org/?probe=35d0dc4629) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [50bfb485e5](https://linux-hardware.org/?probe=50bfb485e5) | Sep 17, 2023 |
| Gigabyte      | X570 GAMING X               | [d795a474b2](https://linux-hardware.org/?probe=d795a474b2) | Sep 16, 2023 |
| ASUSTek       | PRIME H770-PLUS             | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| Acer          | Predator G3-710             | [aa2ac7f07c](https://linux-hardware.org/?probe=aa2ac7f07c) | Sep 16, 2023 |
| HP            | 339A                        | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| ASUSTek       | A88XM-E                     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| ASRock        | B450 Pro4                   | [8f1762e098](https://linux-hardware.org/?probe=8f1762e098) | Sep 15, 2023 |
| ASUSTek       | P8P67 PRO                   | [c3d0531198](https://linux-hardware.org/?probe=c3d0531198) | Sep 14, 2023 |
| Huanan        | X99-TF V1.1                 | [a5acc6026f](https://linux-hardware.org/?probe=a5acc6026f) | Sep 14, 2023 |
| Acer          | Veriton N4640G              | [df814b2a84](https://linux-hardware.org/?probe=df814b2a84) | Sep 13, 2023 |
| Dell          | 07T4MC A06                  | [393a33da8c](https://linux-hardware.org/?probe=393a33da8c) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| Unknown       | Unknown                     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [3716cce5f9](https://linux-hardware.org/?probe=3716cce5f9) | Sep 11, 2023 |
| ASUSTek       | M3A78-CM                    | [77105eb7da](https://linux-hardware.org/?probe=77105eb7da) | Sep 11, 2023 |
| ASUSTek       | H110M-D                     | [de229ab61f](https://linux-hardware.org/?probe=de229ab61f) | Sep 11, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [a25f4b1c5c](https://linux-hardware.org/?probe=a25f4b1c5c) | Sep 11, 2023 |
| Dell          | 07T4MC A06                  | [ec26895704](https://linux-hardware.org/?probe=ec26895704) | Sep 10, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [dffd28975a](https://linux-hardware.org/?probe=dffd28975a) | Sep 09, 2023 |
| Gigabyte      | B450M DS3H V2               | [23e3266b07](https://linux-hardware.org/?probe=23e3266b07) | Sep 08, 2023 |
| HP            | 1589                        | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| Dell          | 0T10XW A00                  | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Dell          | 0J3C2F A00                  | [1aa546be8c](https://linux-hardware.org/?probe=1aa546be8c) | Sep 05, 2023 |
| MSI           | P55-GD65                    | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| Gigabyte      | G41M-Combo                  | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| HP            | 1589                        | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | [0ac2938640](https://linux-hardware.org/?probe=0ac2938640) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ca52538b46](https://linux-hardware.org/?probe=ca52538b46) | Aug 31, 2023 |
| HP            | 3047h                       | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| ASUSTek       | M3A78-CM                    | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| Dell          | 0JCTF8 A00                  | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| Lenovo        | SKYBAY NOK                  | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| ASUSTek       | M3A78-CM                    | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| Gigabyte      | P67A-UD7-B3                 | [912d956729](https://linux-hardware.org/?probe=912d956729) | Aug 24, 2023 |
| ASUSTek       | EX-A320M-GAMING             | [a28ee4ea6b](https://linux-hardware.org/?probe=a28ee4ea6b) | Aug 23, 2023 |
| ASRock        | A320M-DVS R4.0              | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| Gigabyte      | B365M D3H-CF                | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASUSTek       | M3A78-CM                    | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| ASRock        | B450M-HDV R4.0              | [637bd422c5](https://linux-hardware.org/?probe=637bd422c5) | Aug 19, 2023 |
| ASUSTek       | M3A78-CM                    | [2173b6b2b0](https://linux-hardware.org/?probe=2173b6b2b0) | Aug 18, 2023 |
| Gigabyte      | G31M-ES2L                   | [d84596d3c1](https://linux-hardware.org/?probe=d84596d3c1) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| MSI           | PRO H610M-G DDR4            | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| MSI           | H310M PRO-VDH               | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | [69deac32bd](https://linux-hardware.org/?probe=69deac32bd) | Aug 14, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [7ff2052c0f](https://linux-hardware.org/?probe=7ff2052c0f) | Aug 14, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| ECS           | H61H2-M6                    | [b9b9ef9f84](https://linux-hardware.org/?probe=b9b9ef9f84) | Aug 12, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| HP            | 83E8                        | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Unknown       | Unknown                     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| ASUSTek       | M3A78-CM                    | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| MSI           | 970A-G43 PLUS               | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [25bb416eb3](https://linux-hardware.org/?probe=25bb416eb3) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | 970A-UD3P                   | [dcd061dff8](https://linux-hardware.org/?probe=dcd061dff8) | Aug 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| HP            | 8054                        | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| ASRock        | FM2A55M-VG3+                | [ce76d8b410](https://linux-hardware.org/?probe=ce76d8b410) | Jul 31, 2023 |
| ASUSTek       | PRIME Z270-A                | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| ASRock        | AM1H-ITX                    | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| Gigabyte      | EP45T-UD3LR                 | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Gigabyte      | B450M DS3H V2               | [ca9b6e0320](https://linux-hardware.org/?probe=ca9b6e0320) | Jul 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| ASUSTek       | P5G41T-M                    | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| HP            | 212B                        | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5ec24ea9ad](https://linux-hardware.org/?probe=5ec24ea9ad) | Jul 25, 2023 |
| ASUSTek       | P8H61-M LX                  | [9ffd99b082](https://linux-hardware.org/?probe=9ffd99b082) | Jul 25, 2023 |
| HP            | 198E                        | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| ASUSTek       | M3A78-CM                    | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| Dell          | 0VD92X A00                  | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3032h                       | [f6a4202b21](https://linux-hardware.org/?probe=f6a4202b21) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Dell          | 0HD5W2 A01                  | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [c527cf56ad](https://linux-hardware.org/?probe=c527cf56ad) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| Dell          | 0T7D40 A01                  | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| ASRock        | H81M                        | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| Google        | Guado                       | [d14465ad06](https://linux-hardware.org/?probe=d14465ad06) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASUSTek       | M3A78-CM                    | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| MSI           | X99A GAMING 9 ACK           | [4a36d070b4](https://linux-hardware.org/?probe=4a36d070b4) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| HP            | 1998                        | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| HP            | 1998                        | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [6a55de667a](https://linux-hardware.org/?probe=6a55de667a) | Jul 09, 2023 |
| Dell          | 0KC9NP A01                  | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| Gigabyte      | B85M-HD3                    | [43034103ef](https://linux-hardware.org/?probe=43034103ef) | Jul 06, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Google        | Guado                       | [8bd38f802a](https://linux-hardware.org/?probe=8bd38f802a) | Jul 06, 2023 |
| ASRock        | Z370 Killer SLI             | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | [685f105356](https://linux-hardware.org/?probe=685f105356) | Jul 05, 2023 |
| HP            | 339A                        | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| ASRock        | Z170 Extreme4               | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| ASRock        | A320M-HDV R3.0              | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| Gigabyte      | B450M GAMING                | [22a13c2e16](https://linux-hardware.org/?probe=22a13c2e16) | Jul 03, 2023 |
| ASUSTek       | M3A78-CM                    | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Acer          | FX58M                       | [44e563ac2a](https://linux-hardware.org/?probe=44e563ac2a) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| Acer          | FX58M                       | [69f3a5d4fb](https://linux-hardware.org/?probe=69f3a5d4fb) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Gigabyte      | Z77X-UD5H                   | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| Gigabyte      | GA-970A-UD3                 | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | 21B4 A01                    | [e277fd2772](https://linux-hardware.org/?probe=e277fd2772) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| Intel         | H81                         | [65ad18a4bd](https://linux-hardware.org/?probe=65ad18a4bd) | Jun 24, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [d4d7534ac3](https://linux-hardware.org/?probe=d4d7534ac3) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Gigabyte      | H510M S2H V2                | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| Gigabyte      | H510M S2H V2                | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| ASRock        | Z87 Extreme4                | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| MSI           | B85-G43 GAMING              | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASRock        | H61M-VG3                    | [858be00df4](https://linux-hardware.org/?probe=858be00df4) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| MSI           | B450 TOMAHAWK               | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [dbe7676807](https://linux-hardware.org/?probe=dbe7676807) | Jun 15, 2023 |
| ASUSTek       | P5G41C-M LX                 | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| MSI           | B450M-A PRO MAX             | [de08f65c4d](https://linux-hardware.org/?probe=de08f65c4d) | Jun 11, 2023 |
| HP            | 3397                        | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| Gigabyte      | Z97M-DS3H                   | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| MSI           | Z87-G43                     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Gigabyte      | B250-FinTech-CF             | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| HP            | 21B4 A01                    | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| HP            | 845A                        | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| Dell          | 02N3WF A01                  | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| ASRock        | G41M-VS3                    | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| Gateway       | DT55                        | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| ASRock        | H81M-VG4                    | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| ASUSTek       | A8N-E                       | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Acer          | WG43M                       | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| ASRock        | AB350 Pro4                  | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| Gigabyte      | B250-FinTech-CF             | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| ASUSTek       | M3A78-CM                    | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| ASUSTek       | B85M-G                      | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASUSTek       | PRIME Z790-P                | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Pegatron      | VIOLET                      | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Foxconn       | P35A01                      | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| HP            | 339A                        | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Inventec      | D CLASS A02                 | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| HP            | 3047h                       | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| ASUSTek       | B85-PLUS                    | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | B85-G43                     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| ASUSTek       | M3A78-CM                    | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| ASUSTek       | PRIME B550M-K               | [c0ade7c98e](https://linux-hardware.org/?probe=c0ade7c98e) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| ASUSTek       | M3A78-CM                    | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| MSI           | B450M MORTAR MAX            | [91f2551511](https://linux-hardware.org/?probe=91f2551511) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| HP            | 1589                        | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | 1589                        | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [15c40bae27](https://linux-hardware.org/?probe=15c40bae27) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| MSI           | B450M PRO-M2                | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| ASRock        | Z370 Gaming K6              | [a5ff738639](https://linux-hardware.org/?probe=a5ff738639) | Apr 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [ee996917df](https://linux-hardware.org/?probe=ee996917df) | Apr 29, 2023 |
| ASRock        | Z170 Extreme4               | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | P5K/EPU                     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| Dell          | 03NVJ6 A02                  | [74a0632f6e](https://linux-hardware.org/?probe=74a0632f6e) | Apr 25, 2023 |
| ASUSTek       | M3A78-CM                    | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| MSI           | P55-GD65                    | [90cc53b6dd](https://linux-hardware.org/?probe=90cc53b6dd) | Apr 22, 2023 |
| MSI           | B450-A PRO MAX              | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Unknown       | Unknown                     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| Gigabyte      | G31M-ES2L                   | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [3c77a2b081](https://linux-hardware.org/?probe=3c77a2b081) | Apr 14, 2023 |
| MSI           | B85-G43                     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Dell          | 0GXM1W A00                  | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | A68HM-K                     | [5586a15d29](https://linux-hardware.org/?probe=5586a15d29) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Acer          | WG43M                       | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| HP            | 3032h                       | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| MSI           | MS-B0A21                    | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| ASUSTek       | M3A78-CM                    | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| ASRock        | B75 Pro3-M                  | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Dell          | 0Y2K8N A01                  | [379f9d7af7](https://linux-hardware.org/?probe=379f9d7af7) | Apr 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6e8ca2befa](https://linux-hardware.org/?probe=6e8ca2befa) | Apr 04, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [64fa944dfd](https://linux-hardware.org/?probe=64fa944dfd) | Apr 03, 2023 |
| MSI           | PH67A-C43                   | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [c98048fb64](https://linux-hardware.org/?probe=c98048fb64) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | [383835a445](https://linux-hardware.org/?probe=383835a445) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [dff9959cd7](https://linux-hardware.org/?probe=dff9959cd7) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| Acer          | WG43M                       | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| ASRock        | Z77 Extreme6                | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| ASUSTek       | M3A78-CM                    | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| HP            | 895D                        | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| HP            | 1998                        | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| ASRock        | AM1H-ITX                    | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| Acer          | WG43M                       | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [4fcf740ee9](https://linux-hardware.org/?probe=4fcf740ee9) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | [caa720b95b](https://linux-hardware.org/?probe=caa720b95b) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| HP            | 304Ah                       | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | A520I AC                    | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Intel         | DG41RQ AAE54511-203         | [703ea3d03c](https://linux-hardware.org/?probe=703ea3d03c) | Mar 18, 2023 |
| Intel         | DG41RQ AAE54511-203         | [a5775c7491](https://linux-hardware.org/?probe=a5775c7491) | Mar 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [2a17e297a2](https://linux-hardware.org/?probe=2a17e297a2) | Mar 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | [96742a0cb2](https://linux-hardware.org/?probe=96742a0cb2) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Dell          | 03NVJ6 A02                  | [b5281b4ba4](https://linux-hardware.org/?probe=b5281b4ba4) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| MSI           | B85-G43                     | [d8334d09fa](https://linux-hardware.org/?probe=d8334d09fa) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| Dell          | 0C96W1 A03                  | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| MSI           | B85-G43                     | [e270b5804a](https://linux-hardware.org/?probe=e270b5804a) | Mar 13, 2023 |
| Dell          | 051FJ8 A02                  | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [73d5ba11c5](https://linux-hardware.org/?probe=73d5ba11c5) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| MSI           | A68HM-E33 V2                | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [afe81d4bfa](https://linux-hardware.org/?probe=afe81d4bfa) | Mar 12, 2023 |
| HP            | 213D A01                    | [8c6054a4f7](https://linux-hardware.org/?probe=8c6054a4f7) | Mar 12, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| ASRock        | AM1H-ITX                    | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| ASUSTek       | A68HM-K                     | [12fa2455f7](https://linux-hardware.org/?probe=12fa2455f7) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| Dell          | 03NVJ6 A02                  | [34696138fe](https://linux-hardware.org/?probe=34696138fe) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [43a939870d](https://linux-hardware.org/?probe=43a939870d) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f64ba0ea72](https://linux-hardware.org/?probe=f64ba0ea72) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [59cb6854e5](https://linux-hardware.org/?probe=59cb6854e5) | Mar 07, 2023 |
| ASUSTek       | A88XM-E                     | [b809f137cd](https://linux-hardware.org/?probe=b809f137cd) | Mar 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Biostar       | TA780G M2+                  | [f5ddb4d21a](https://linux-hardware.org/?probe=f5ddb4d21a) | Mar 05, 2023 |
| MSI           | B550M PRO                   | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| HP            | 18E5                        | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Dell          | 03NVJ6 A02                  | [80e769b994](https://linux-hardware.org/?probe=80e769b994) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | A88XM-E                     | [ea145a8349](https://linux-hardware.org/?probe=ea145a8349) | Mar 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d9a9f6b904](https://linux-hardware.org/?probe=d9a9f6b904) | Mar 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [cf87d901a9](https://linux-hardware.org/?probe=cf87d901a9) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [5eb43b511f](https://linux-hardware.org/?probe=5eb43b511f) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | [8db9ca3a4b](https://linux-hardware.org/?probe=8db9ca3a4b) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [789ca3b7bd](https://linux-hardware.org/?probe=789ca3b7bd) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [241283977d](https://linux-hardware.org/?probe=241283977d) | Mar 04, 2023 |
| ASRock        | Z87 Extreme4                | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | Maximus VII RANGER          | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [52522a762d](https://linux-hardware.org/?probe=52522a762d) | Feb 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | [07bb534dc9](https://linux-hardware.org/?probe=07bb534dc9) | Feb 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [589b06afc1](https://linux-hardware.org/?probe=589b06afc1) | Feb 26, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [df54545112](https://linux-hardware.org/?probe=df54545112) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [782598981d](https://linux-hardware.org/?probe=782598981d) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [6a75456290](https://linux-hardware.org/?probe=6a75456290) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [73caef7b95](https://linux-hardware.org/?probe=73caef7b95) | Feb 25, 2023 |
| Gigabyte      | G31M-S2L                    | [563101d2b2](https://linux-hardware.org/?probe=563101d2b2) | Feb 25, 2023 |
| ASRock        | AM1H-ITX                    | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| MSI           | B350M MORTAR                | [6a7ac3b38b](https://linux-hardware.org/?probe=6a7ac3b38b) | Feb 24, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [b2681528bd](https://linux-hardware.org/?probe=b2681528bd) | Feb 24, 2023 |
| ASUSTek       | B150M-A D3                  | [01caadaee0](https://linux-hardware.org/?probe=01caadaee0) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B85M-HD3 R4                 | [db83755f3f](https://linux-hardware.org/?probe=db83755f3f) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| Gigabyte      | Z97-HD3                     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [39e6d492c4](https://linux-hardware.org/?probe=39e6d492c4) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | [40bc5397ea](https://linux-hardware.org/?probe=40bc5397ea) | Feb 22, 2023 |
| ASRock        | Z690 Extreme                | [16e67a28e4](https://linux-hardware.org/?probe=16e67a28e4) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| ASRock        | A520M-HVS                   | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| ASUSTek       | M3A78-CM                    | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| Gigabyte      | B75M-D2V                    | [fe04dfeaac](https://linux-hardware.org/?probe=fe04dfeaac) | Feb 19, 2023 |
| Dell          | 0PU052                      | [a460806b91](https://linux-hardware.org/?probe=a460806b91) | Feb 18, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [28965259ad](https://linux-hardware.org/?probe=28965259ad) | Feb 18, 2023 |
| Dell          | 03NVJ6 A02                  | [5201547dce](https://linux-hardware.org/?probe=5201547dce) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | [a77d2c8a54](https://linux-hardware.org/?probe=a77d2c8a54) | Feb 17, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | [8efdbecd75](https://linux-hardware.org/?probe=8efdbecd75) | Feb 17, 2023 |
| ASRock        | J3355M                      | [9118f960dd](https://linux-hardware.org/?probe=9118f960dd) | Feb 16, 2023 |
| Gigabyte      | EP35-DS4                    | [00d960f926](https://linux-hardware.org/?probe=00d960f926) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| MSI           | MS-7235                     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | [ae4f47209a](https://linux-hardware.org/?probe=ae4f47209a) | Feb 15, 2023 |
| Gigabyte      | H410M H V3                  | [59f88fb4d0](https://linux-hardware.org/?probe=59f88fb4d0) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | [f1c6e21bfb](https://linux-hardware.org/?probe=f1c6e21bfb) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| ASUSTek       | M3A78-CM                    | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Gigabyte      | H55M-USB3                   | [08b959d9ec](https://linux-hardware.org/?probe=08b959d9ec) | Feb 14, 2023 |
| ASUSTek       | M3A78-CM                    | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| HP            | 3397                        | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| HP            | 3397                        | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | 3397                        | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| Dell          | 04YJ19 A00                  | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| ASUSTek       | PRIME B450M-A               | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [ddaad5aa0d](https://linux-hardware.org/?probe=ddaad5aa0d) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [2b4bc22652](https://linux-hardware.org/?probe=2b4bc22652) | Feb 08, 2023 |
| ASRock        | X470 Gaming K4              | [086ea7a0e6](https://linux-hardware.org/?probe=086ea7a0e6) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| Dell          | 0DR845                      | [537252420b](https://linux-hardware.org/?probe=537252420b) | Feb 07, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | DG31PR AAD97573-301         | [2080f0edf4](https://linux-hardware.org/?probe=2080f0edf4) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| MSI           | H410M-A PRO                 | [6ac747c27e](https://linux-hardware.org/?probe=6ac747c27e) | Feb 05, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| HP            | 8054                        | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [854b52f85c](https://linux-hardware.org/?probe=854b52f85c) | Feb 05, 2023 |
| Foxconn       | 2ABF                        | [54a305f83e](https://linux-hardware.org/?probe=54a305f83e) | Feb 03, 2023 |
| ASRock        | Z370 Gaming K6              | [203d5736d7](https://linux-hardware.org/?probe=203d5736d7) | Feb 03, 2023 |
| HP            | 212B                        | [f27b5c4aa0](https://linux-hardware.org/?probe=f27b5c4aa0) | Feb 03, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a4a3ea0e4e](https://linux-hardware.org/?probe=a4a3ea0e4e) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| Gigabyte      | B365M DS3H                  | [f04d195965](https://linux-hardware.org/?probe=f04d195965) | Feb 02, 2023 |
| ASUSTek       | P5QPL-AM                    | [c8ee9be68c](https://linux-hardware.org/?probe=c8ee9be68c) | Feb 02, 2023 |
| ASUSTek       | B85M-G                      | [de152b340c](https://linux-hardware.org/?probe=de152b340c) | Feb 01, 2023 |
| Gigabyte      | B365M DS3H                  | [d515d5d9f7](https://linux-hardware.org/?probe=d515d5d9f7) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| ASUSTek       | Maximus VII GENE            | [c936c07925](https://linux-hardware.org/?probe=c936c07925) | Jan 31, 2023 |
| Gigabyte      | Z97M-DS3H                   | [360dc83e04](https://linux-hardware.org/?probe=360dc83e04) | Jan 31, 2023 |
| HP            | 8054                        | [f2367fdcda](https://linux-hardware.org/?probe=f2367fdcda) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| Dell          | 0HY9JP A00                  | [f4aefcd670](https://linux-hardware.org/?probe=f4aefcd670) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| HP            | 8054                        | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| HP            | 3048h                       | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [9fcf89ea7c](https://linux-hardware.org/?probe=9fcf89ea7c) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASRock        | FM2A55M-VG3+                | [c5da4a997d](https://linux-hardware.org/?probe=c5da4a997d) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [076a3479fa](https://linux-hardware.org/?probe=076a3479fa) | Jan 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d251029940](https://linux-hardware.org/?probe=d251029940) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6c55213012](https://linux-hardware.org/?probe=6c55213012) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6b5c46a680](https://linux-hardware.org/?probe=6b5c46a680) | Jan 19, 2023 |
| Huanan        | X99-TF V2.0                 | [3fa0103359](https://linux-hardware.org/?probe=3fa0103359) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Dell          | 0Y3R3K A00                  | [f2164a9c60](https://linux-hardware.org/?probe=f2164a9c60) | Jan 18, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B560M DS3H                  | [be77d8e20d](https://linux-hardware.org/?probe=be77d8e20d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| Gigabyte      | Z97M-D3H                    | [305ff29dad](https://linux-hardware.org/?probe=305ff29dad) | Jan 14, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [6cc45bde0b](https://linux-hardware.org/?probe=6cc45bde0b) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | M3A78-CM                    | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | [3dcb242fd6](https://linux-hardware.org/?probe=3dcb242fd6) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [366e5b92d7](https://linux-hardware.org/?probe=366e5b92d7) | Jan 11, 2023 |
| Gigabyte      | B365M DS3H                  | [78153a929d](https://linux-hardware.org/?probe=78153a929d) | Jan 11, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [f3fe7611d3](https://linux-hardware.org/?probe=f3fe7611d3) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [eefd133e1f](https://linux-hardware.org/?probe=eefd133e1f) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Dell          | 0MGK50 A02                  | [045695f1d5](https://linux-hardware.org/?probe=045695f1d5) | Jan 09, 2023 |
| Dell          | 088DT1 A00                  | [f7632cc6ba](https://linux-hardware.org/?probe=f7632cc6ba) | Jan 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| Lenovo        | SKYBAY NOK                  | [9bbe57d371](https://linux-hardware.org/?probe=9bbe57d371) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | [0f51a2d7d5](https://linux-hardware.org/?probe=0f51a2d7d5) | Jan 07, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | [531eaa88b5](https://linux-hardware.org/?probe=531eaa88b5) | Jan 07, 2023 |
| Dell          | 0J584C A00                  | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| MSI           | Z590 PRO WIFI               | [98af54429b](https://linux-hardware.org/?probe=98af54429b) | Jan 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fd20c9e982](https://linux-hardware.org/?probe=fd20c9e982) | Jan 07, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Dell          | 0Y3R3K A00                  | [8337b0691c](https://linux-hardware.org/?probe=8337b0691c) | Jan 05, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [96150fc8a5](https://linux-hardware.org/?probe=96150fc8a5) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | [bd3d76fa53](https://linux-hardware.org/?probe=bd3d76fa53) | Jan 03, 2023 |
| HP            | 304Bh                       | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| MSI           | B250M PRO-VDH               | [0a4b320a9e](https://linux-hardware.org/?probe=0a4b320a9e) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | B450M Pro4                  | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| Gigabyte      | H61M-D2H                    | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | [fdb09844e9](https://linux-hardware.org/?probe=fdb09844e9) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | [9ff3461c31](https://linux-hardware.org/?probe=9ff3461c31) | Dec 29, 2022 |
| Gigabyte      | H270-HD3-CF                 | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | Z97M-DS3H                   | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9ada5592f6](https://linux-hardware.org/?probe=9ada5592f6) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| HP            | ProLiant ML350 G6           | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| Foxconn       | A76GMV                      | [722a9911f8](https://linux-hardware.org/?probe=722a9911f8) | Dec 18, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| POSIFLEX      | KK-3703 D0                  | [8ce9910b00](https://linux-hardware.org/?probe=8ce9910b00) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| ASUSTek       | P5K Deluxe                  | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [ffb030fbbf](https://linux-hardware.org/?probe=ffb030fbbf) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [fe9424a1f0](https://linux-hardware.org/?probe=fe9424a1f0) | Dec 09, 2022 |
| Dell          | 01TKCC A01                  | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| Gigabyte      | H61M-S1                     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | [798cf690c5](https://linux-hardware.org/?probe=798cf690c5) | Dec 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [091b8a3a8a](https://linux-hardware.org/?probe=091b8a3a8a) | Dec 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [aadffecf5b](https://linux-hardware.org/?probe=aadffecf5b) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| Lenovo        | SKYBAY NOK                  | [10315500be](https://linux-hardware.org/?probe=10315500be) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | [f8dacfeca3](https://linux-hardware.org/?probe=f8dacfeca3) | Dec 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [6578471259](https://linux-hardware.org/?probe=6578471259) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | [9990900d63](https://linux-hardware.org/?probe=9990900d63) | Dec 03, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | [8a25bf4545](https://linux-hardware.org/?probe=8a25bf4545) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [dd124e3579](https://linux-hardware.org/?probe=dd124e3579) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [a5b34b67f2](https://linux-hardware.org/?probe=a5b34b67f2) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | [f0dfa48048](https://linux-hardware.org/?probe=f0dfa48048) | Nov 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| ASUSTek       | M3A78-CM                    | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Gigabyte      | Z97M-DS3H                   | [a17a108297](https://linux-hardware.org/?probe=a17a108297) | Nov 25, 2022 |
| MSI           | B350 GAMING PLUS            | [2b7bb89689](https://linux-hardware.org/?probe=2b7bb89689) | Nov 25, 2022 |
| HP            | 2215                        | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| HP            | 213D A01                    | [b0c45fb200](https://linux-hardware.org/?probe=b0c45fb200) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Unknown       | HX90                        | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| ASRock        | H410M-HVS R2.0              | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| MSI           | PRO H610M-B DDR4            | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Lenovo        | SKYBAY NOK                  | [24d16fa5df](https://linux-hardware.org/?probe=24d16fa5df) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0PU052                      | [b54afc7e1a](https://linux-hardware.org/?probe=b54afc7e1a) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| Gigabyte      | EP45-UD3LR                  | [75a8f2a500](https://linux-hardware.org/?probe=75a8f2a500) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Gigabyte      | A520M H                     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Dell          | 0PU052                      | [802c39b94f](https://linux-hardware.org/?probe=802c39b94f) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| HP            | 22F8                        | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | [220c131e59](https://linux-hardware.org/?probe=220c131e59) | Nov 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| MSI           | B450M-A PRO MAX             | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| ASUSTek       | P8H61                       | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASUSTek       | M3A78-CM                    | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| Intel         | H55                         | [0481a6ff8e](https://linux-hardware.org/?probe=0481a6ff8e) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| Gigabyte      | H81M-DS2                    | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Gigabyte      | B560M D3H                   | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| MSI           | Z97-G43                     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [a2af2980ad](https://linux-hardware.org/?probe=a2af2980ad) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [245ec71478](https://linux-hardware.org/?probe=245ec71478) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [738569f811](https://linux-hardware.org/?probe=738569f811) | Oct 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a8b08a47aa](https://linux-hardware.org/?probe=a8b08a47aa) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| MSI           | B560M PRO                   | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | [9914e4d771](https://linux-hardware.org/?probe=9914e4d771) | Oct 28, 2022 |
| Gigabyte      | P35-DS3L                    | [2f5cb804c0](https://linux-hardware.org/?probe=2f5cb804c0) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| Dell          | 0HY9JP A00                  | [ecbfb1ca5c](https://linux-hardware.org/?probe=ecbfb1ca5c) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HX555                      | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| HP            | 1825                        | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [fc51a7c9dc](https://linux-hardware.org/?probe=fc51a7c9dc) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| ASUSTek       | M3A78-CM                    | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Gigabyte      | H61M-D2H                    | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-A               | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [7706fb5578](https://linux-hardware.org/?probe=7706fb5578) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 225      | 10.04%  |
| OpenMandriva 4.2   | 129      | 5.75%   |
| OpenMandriva 4.3   | 120      | 5.35%   |
| Ubuntu 18.04       | 108      | 4.82%   |
| Ubuntu 22.04       | 81       | 3.61%   |
| Arch Rolling       | 78       | 3.48%   |
| ROSA R10           | 47       | 2.1%    |
| Debian 11          | 45       | 2.01%   |
| ROSA R11           | 39       | 1.74%   |
| OpenMandriva 23.03 | 36       | 1.61%   |
| Zorin 16           | 35       | 1.56%   |
| OpenMandriva 23.01 | 35       | 1.56%   |
| OpenMandriva 23.08 | 34       | 1.52%   |
| Manjaro            | 34       | 1.52%   |
| ROSA R9            | 31       | 1.38%   |
| ROSA R11.1         | 28       | 1.25%   |
| Linux Mint 20.3    | 25       | 1.12%   |
| Linux Mint 20.1    | 24       | 1.07%   |
| Arch               | 24       | 1.07%   |
| Pop!_OS 22.04      | 23       | 1.03%   |
| Fedora 36          | 23       | 1.03%   |
| Linux Mint 21.1    | 22       | 0.98%   |
| KDE neon 20.04     | 22       | 0.98%   |
| Fedora 37          | 22       | 0.98%   |
| Linux Mint 20      | 21       | 0.94%   |
| Fedora 38          | 21       | 0.94%   |
| Ubuntu 20.10       | 20       | 0.89%   |
| ROSA R8.1          | 19       | 0.85%   |
| OpenMandriva 4.50  | 19       | 0.85%   |
| Linux Mint 20.2    | 19       | 0.85%   |
| Debian 12          | 19       | 0.85%   |
| Ubuntu 19.10       | 18       | 0.8%    |
| Ubuntu 19.04       | 17       | 0.76%   |
| ROSA R8            | 17       | 0.76%   |
| Linux Mint 21.2    | 17       | 0.76%   |
| Fedora 35          | 17       | 0.76%   |
| Fedora 34          | 17       | 0.76%   |
| ArcoLinux Rolling  | 17       | 0.76%   |
| Ubuntu 21.04       | 16       | 0.71%   |
| Linux Mint 19.3    | 16       | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 492      | 24.43%  |
| OpenMandriva  | 365      | 18.12%  |
| Linux Mint    | 161      | 7.99%   |
| ROSA          | 147      | 7.3%    |
| Fedora        | 124      | 6.16%   |
| Arch          | 99       | 4.92%   |
| Debian        | 82       | 4.07%   |
| Manjaro       | 81       | 4.02%   |
| Pop!_OS       | 63       | 3.13%   |
| Kubuntu       | 45       | 2.23%   |
| Zorin         | 44       | 2.18%   |
| KDE neon      | 33       | 1.64%   |
| Xubuntu       | 25       | 1.24%   |
| Gentoo        | 25       | 1.24%   |
| openSUSE      | 19       | 0.94%   |
| ArcoLinux     | 17       | 0.84%   |
| EndeavourOS   | 13       | 0.65%   |
| Endless       | 12       | 0.6%    |
| LMDE          | 11       | 0.55%   |
| BlackPanther  | 11       | 0.55%   |
| Ubuntu MATE   | 10       | 0.5%    |
| Ubuntu Unity  | 9        | 0.45%   |
| MX            | 9        | 0.45%   |
| Lubuntu       | 9        | 0.45%   |
| Elementary    | 9        | 0.45%   |
| Kali          | 8        | 0.4%    |
| CentOS        | 7        | 0.35%   |
| Xero          | 6        | 0.3%    |
| Clear Linux   | 6        | 0.3%    |
| Void Linux    | 5        | 0.25%   |
| Nobara        | 5        | 0.25%   |
| SteamOS       | 4        | 0.2%    |
| Garuda Linux  | 4        | 0.2%    |
| Ubuntu Budgie | 3        | 0.15%   |
| Peppermint    | 3        | 0.15%   |
| NixOS         | 3        | 0.15%   |
| Linux Lite    | 3        | 0.15%   |
| EuroLinux     | 3        | 0.15%   |
| Devuan        | 3        | 0.15%   |
| antiX         | 3        | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 125      | 4.87%   |
| 5.16.7-desktop-1omv4003             | 102      | 3.97%   |
| 6.2.6-desktop-1omv2390              | 34       | 1.32%   |
| 5.4.0-42-generic                    | 34       | 1.32%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 30       | 1.17%   |
| 6.4.11-desktop-1omv2390             | 28       | 1.09%   |
| 6.1.1-desktop-1omv2290              | 28       | 1.09%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 27       | 1.05%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 22       | 0.86%   |
| 5.16.13-desktop-1omv4003            | 21       | 0.82%   |
| 5.4.0-26-generic                    | 19       | 0.74%   |
| 6.6.2-desktop-1omv2390              | 17       | 0.66%   |
| 5.15.0-56-generic                   | 16       | 0.62%   |
| 5.4.0-52-generic                    | 15       | 0.58%   |
| 5.4.0-58-generic                    | 13       | 0.51%   |
| 5.4.0-54-generic                    | 13       | 0.51%   |
| 5.19.0-35-generic                   | 13       | 0.51%   |
| 5.15.0-52-generic                   | 13       | 0.51%   |
| 5.8.0-48-generic                    | 12       | 0.47%   |
| 5.4.0-72-generic                    | 12       | 0.47%   |
| 5.4.0-48-generic                    | 12       | 0.47%   |
| 5.4.0-40-generic                    | 12       | 0.47%   |
| 5.15.0-43-generic                   | 12       | 0.47%   |
| 5.4.0-66-generic                    | 11       | 0.43%   |
| 5.3.0-46-generic                    | 11       | 0.43%   |
| 5.13.0-39-generic                   | 11       | 0.43%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 11       | 0.43%   |
| 6.2.0-36-generic                    | 10       | 0.39%   |
| 5.8.0-43-generic                    | 10       | 0.39%   |
| 5.4.0-56-generic                    | 10       | 0.39%   |
| 5.4.0-29-generic                    | 10       | 0.39%   |
| 5.15.0-58-generic                   | 10       | 0.39%   |
| 5.13.0-40-generic                   | 10       | 0.39%   |
| 5.13.0-27-generic                   | 10       | 0.39%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 10       | 0.39%   |
| 5.4.0-81-generic                    | 9        | 0.35%   |
| 5.4.0-65-generic                    | 9        | 0.35%   |
| 5.4.0-47-generic                    | 9        | 0.35%   |
| 5.4.0-37-generic                    | 9        | 0.35%   |
| 5.19.0-32-generic                   | 9        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 300      | 12.54%  |
| 5.15.0  | 141      | 5.89%   |
| 4.15.0  | 133      | 5.56%   |
| 5.10.14 | 126      | 5.27%   |
| 5.16.7  | 104      | 4.35%   |
| 5.8.0   | 85       | 3.55%   |
| 5.11.0  | 71       | 2.97%   |
| 5.13.0  | 67       | 2.8%    |
| 5.3.0   | 56       | 2.34%   |
| 5.19.0  | 49       | 2.05%   |
| 5.10.0  | 45       | 1.88%   |
| 6.2.0   | 42       | 1.76%   |
| 6.2.6   | 41       | 1.71%   |
| 5.0.0   | 37       | 1.55%   |
| 4.9.60  | 33       | 1.38%   |
| 4.18.0  | 30       | 1.25%   |
| 6.1.1   | 29       | 1.21%   |
| 6.4.11  | 28       | 1.17%   |
| 4.9.20  | 27       | 1.13%   |
| 6.1.0   | 26       | 1.09%   |
| 4.19.0  | 22       | 0.92%   |
| 5.16.13 | 21       | 0.88%   |
| 6.6.2   | 20       | 0.84%   |
| 4.1.38  | 14       | 0.59%   |
| 4.9.124 | 10       | 0.42%   |
| 4.1.34  | 10       | 0.42%   |
| 6.0.12  | 9        | 0.38%   |
| 4.9.155 | 9        | 0.38%   |
| 4.18.16 | 9        | 0.38%   |
| 5.17.5  | 8        | 0.33%   |
| 4.9.76  | 8        | 0.33%   |
| 6.4.8   | 7        | 0.29%   |
| 6.1.4   | 7        | 0.29%   |
| 6.0.8   | 7        | 0.29%   |
| 6.0.0   | 7        | 0.29%   |
| 5.6.0   | 7        | 0.29%   |
| 5.4.32  | 7        | 0.29%   |
| 6.1.41  | 6        | 0.25%   |
| 6.1.12  | 6        | 0.25%   |
| 5.9.16  | 6        | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 338      | 14.81%  |
| 5.10    | 219      | 9.6%    |
| 5.15    | 204      | 8.94%   |
| 5.16    | 143      | 6.27%   |
| 4.15    | 133      | 5.83%   |
| 6.2     | 107      | 4.69%   |
| 5.8     | 106      | 4.65%   |
| 6.1     | 104      | 4.56%   |
| 5.11    | 97       | 4.25%   |
| 5.13    | 80       | 3.51%   |
| 4.9     | 78       | 3.42%   |
| 5.19    | 71       | 3.11%   |
| 5.3     | 62       | 2.72%   |
| 6.4     | 55       | 2.41%   |
| 6.0     | 47       | 2.06%   |
| 5.0     | 41       | 1.8%    |
| 4.18    | 39       | 1.71%   |
| 6.6     | 31       | 1.36%   |
| 5.14    | 31       | 1.36%   |
| 5.12    | 31       | 1.36%   |
| 5.18    | 30       | 1.31%   |
| 6.3     | 28       | 1.23%   |
| 4.1     | 28       | 1.23%   |
| 5.9     | 27       | 1.18%   |
| 5.17    | 27       | 1.18%   |
| 4.19    | 26       | 1.14%   |
| 5.6     | 24       | 1.05%   |
| 6.5     | 23       | 1.01%   |
| 5.5     | 16       | 0.7%    |
| 5.7     | 13       | 0.57%   |
| 4.4     | 6        | 0.26%   |
| 4.16    | 3        | 0.13%   |
| 5.1     | 2        | 0.09%   |
| 4.8     | 2        | 0.09%   |
| 4.20    | 2        | 0.09%   |
| 5.2     | 1        | 0.04%   |
| 4.7     | 1        | 0.04%   |
| 4.14    | 1        | 0.04%   |
| 4.13    | 1        | 0.04%   |
| 4.12    | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1890     | 97.67%  |
| i686   | 43       | 2.22%   |
| ppc64  | 1        | 0.05%   |
| ppc    | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 669      | 32.65%  |
| KDE5            | 630      | 30.75%  |
| Unknown         | 190      | 9.27%   |
| XFCE            | 131      | 6.39%   |
| X-Cinnamon      | 109      | 5.32%   |
| KDE4            | 78       | 3.81%   |
| MATE            | 59       | 2.88%   |
| KDE             | 52       | 2.54%   |
| LXQt            | 23       | 1.12%   |
| Cinnamon        | 22       | 1.07%   |
| i3              | 20       | 0.98%   |
| Unity           | 10       | 0.49%   |
| LXDE            | 10       | 0.49%   |
| Pantheon        | 9        | 0.44%   |
| Deepin          | 6        | 0.29%   |
| Budgie          | 5        | 0.24%   |
| GNOME Flashback | 4        | 0.2%    |
| GNOME Classic   | 4        | 0.2%    |
| qtile           | 3        | 0.15%   |
| openbox         | 2        | 0.1%    |
| icewm           | 2        | 0.1%    |
| Hyprland        | 2        | 0.1%    |
| DWM             | 2        | 0.1%    |
| awesome         | 2        | 0.1%    |
| xmonad          | 1        | 0.05%   |
| sway            | 1        | 0.05%   |
| jwm             | 1        | 0.05%   |
| gnome-xorg      | 1        | 0.05%   |
| fluxbox         | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1594     | 79.34%  |
| Wayland | 282      | 14.04%  |
| Unknown | 80       | 3.98%   |
| Tty     | 53       | 2.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 827      | 40.66%  |
| SDDM    | 577      | 28.37%  |
| LightDM | 168      | 8.26%   |
| GDM     | 158      | 7.77%   |
| GDM3    | 150      | 7.37%   |
| KDM     | 86       | 4.23%   |
| TDM     | 52       | 2.56%   |
| XDM     | 5        | 0.25%   |
| LXDM    | 3        | 0.15%   |
| SLIMSKI | 2        | 0.1%    |
| SLiM    | 2        | 0.1%    |
| LY-DM   | 2        | 0.1%    |
| MDM     | 1        | 0.05%   |
| Ly      | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pl_PL       | 1162     | 57.27%  |
| en_US       | 469      | 23.11%  |
| Unknown     | 258      | 12.72%  |
| en_GB       | 55       | 2.71%   |
| C           | 33       | 1.63%   |
| ru_RU       | 11       | 0.54%   |
| en_CA       | 7        | 0.34%   |
| de_DE       | 4        | 0.2%    |
| szl_PL      | 3        | 0.15%   |
| ru_UA       | 3        | 0.15%   |
| POSIX       | 3        | 0.15%   |
| en_AG       | 3        | 0.15%   |
| uk_UA       | 2        | 0.1%    |
| fr_FR       | 2        | 0.1%    |
| en_IE       | 2        | 0.1%    |
| en_DK       | 2        | 0.1%    |
| sv_SE       | 1        | 0.05%   |
| pl_PL.UTF8  | 1        | 0.05%   |
| es_BO       | 1        | 0.05%   |
| en_US.UTF8  | 1        | 0.05%   |
| en_US.utf-8 | 1        | 0.05%   |
| en_SE       | 1        | 0.05%   |
| en_IN       | 1        | 0.05%   |
| de_CH       | 1        | 0.05%   |
| cs_CZ       | 1        | 0.05%   |
| C.UTF8      | 1        | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1200     | 60.45%  |
| EFI  | 785      | 39.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1310     | 64.15%  |
| Overlay  | 331      | 16.21%  |
| Btrfs    | 192      | 9.4%    |
| Unknown  | 117      | 5.73%   |
| Tmpfs    | 36       | 1.76%   |
| Xfs      | 26       | 1.27%   |
| Zfs      | 10       | 0.49%   |
| F2fs     | 8        | 0.39%   |
| Ext2     | 4        | 0.2%    |
| Ext3     | 3        | 0.15%   |
| Jfs      | 2        | 0.1%    |
| XXXXXXX  | 1        | 0.05%   |
| SquXshfs | 1        | 0.05%   |
| Aufs     | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 903      | 44.57%  |
| GPT     | 735      | 36.28%  |
| MBR     | 388      | 19.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1501     | 74.86%  |
| Yes       | 504      | 25.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1212     | 60.84%  |
| Yes       | 780      | 39.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Gigabyte Technology                  | 450      | 23.32%  |
| ASUSTek Computer                     | 424      | 21.97%  |
| MSI                                  | 327      | 16.94%  |
| ASRock                               | 186      | 9.64%   |
| Dell                                 | 165      | 8.55%   |
| Hewlett-Packard                      | 130      | 6.74%   |
| Lenovo                               | 66       | 3.42%   |
| Fujitsu                              | 32       | 1.66%   |
| Intel                                | 24       | 1.24%   |
| Acer                                 | 21       | 1.09%   |
| Foxconn                              | 15       | 0.78%   |
| Unknown                              | 13       | 0.67%   |
| Fujitsu Siemens                      | 11       | 0.57%   |
| Inventec                             | 7        | 0.36%   |
| Medion                               | 6        | 0.31%   |
| Huanan                               | 6        | 0.31%   |
| ECS                                  | 4        | 0.21%   |
| Pegatron                             | 3        | 0.16%   |
| Biostar                              | 3        | 0.16%   |
| Apple                                | 3        | 0.16%   |
| ACTION                               | 3        | 0.16%   |
| ABIT                                 | 3        | 0.16%   |
| Supermicro                           | 2        | 0.1%    |
| Hardkernel                           | 2        | 0.1%    |
| Gateway                              | 2        | 0.1%    |
| AMI                                  | 2        | 0.1%    |
| Wortmann AG                          | 1        | 0.05%   |
| WeiBu                                | 1        | 0.05%   |
| Shuttle                              | 1        | 0.05%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.05%   |
| Seeed Studio                         | 1        | 0.05%   |
| Sapphire                             | 1        | 0.05%   |
| POSIFLEX                             | 1        | 0.05%   |
| OPTIMUS                              | 1        | 0.05%   |
| Nvidia                               | 1        | 0.05%   |
| MACHINIST                            | 1        | 0.05%   |
| ITSUMI                               | 1        | 0.05%   |
| HEDYCOMPUTER                         | 1        | 0.05%   |
| Hampoo                               | 1        | 0.05%   |
| Google                               | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 35       | 1.81%   |
| MSI MS-7B86                  | 19       | 0.98%   |
| Gigabyte B450M DS3H          | 19       | 0.98%   |
| ASUS SABERTOOTH Z77          | 18       | 0.93%   |
| MSI MS-7817                  | 17       | 0.88%   |
| Dell OptiPlex 780            | 15       | 0.78%   |
| MSI MS-7C37                  | 14       | 0.73%   |
| MSI MS-7C02                  | 13       | 0.67%   |
| Unknown                      | 13       | 0.67%   |
| Dell OptiPlex 7010           | 11       | 0.57%   |
| MSI MS-7B79                  | 10       | 0.52%   |
| MSI MS-7721                  | 10       | 0.52%   |
| Gigabyte B450 AORUS ELITE    | 10       | 0.52%   |
| Dell OptiPlex 755            | 10       | 0.52%   |
| Gigabyte B85M-D3H            | 9        | 0.47%   |
| Gigabyte B550 AORUS ELITE V2 | 9        | 0.47%   |
| ASUS TUF Gaming X570-PLUS    | 9        | 0.47%   |
| MSI MS-7A38                  | 8        | 0.41%   |
| MSI MS-7816                  | 8        | 0.41%   |
| Dell OptiPlex 790            | 8        | 0.41%   |
| ASUS TUF Gaming B550-PLUS    | 8        | 0.41%   |
| ASUS PRIME X470-PRO          | 8        | 0.41%   |
| ASUS PRIME B450M-A           | 8        | 0.41%   |
| MSI MS-7B89                  | 7        | 0.36%   |
| HP t620 Quad Core TC         | 7        | 0.36%   |
| Gigabyte 970A-DS3P           | 7        | 0.36%   |
| ASUS PRIME B350-PLUS         | 7        | 0.36%   |
| ASUS P5G41T-M LX             | 7        | 0.36%   |
| MSI MS-7C52                  | 6        | 0.31%   |
| MSI MS-7971                  | 6        | 0.31%   |
| HP Compaq 8200 Elite SFF PC  | 6        | 0.31%   |
| Gigabyte P31-DS3L            | 6        | 0.31%   |
| Gigabyte GA-MA770T-UD3P      | 6        | 0.31%   |
| Gigabyte G31M-ES2L           | 6        | 0.31%   |
| Dell OptiPlex 9020           | 6        | 0.31%   |
| Dell OptiPlex 3010           | 6        | 0.31%   |
| ASUS PRIME X370-PRO          | 6        | 0.31%   |
| MSI MS-7D25                  | 5        | 0.26%   |
| MSI MS-7C91                  | 5        | 0.26%   |
| MSI MS-7C80                  | 5        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 114      | 5.91%   |
| ASUS PRIME             | 80       | 4.15%   |
| HP Compaq              | 53       | 2.75%   |
| Lenovo ThinkCentre     | 42       | 2.18%   |
| ASUS TUF               | 41       | 2.12%   |
| ASUS All               | 35       | 1.81%   |
| ASUS ROG               | 31       | 1.61%   |
| Gigabyte B450M         | 28       | 1.45%   |
| Dell Precision         | 26       | 1.35%   |
| HP EliteDesk           | 24       | 1.24%   |
| Fujitsu ESPRIMO        | 22       | 1.14%   |
| ASUS SABERTOOTH        | 20       | 1.04%   |
| MSI MS-7B86            | 19       | 0.98%   |
| MSI MS-7817            | 17       | 0.88%   |
| Gigabyte X570          | 17       | 0.88%   |
| Gigabyte B550          | 16       | 0.83%   |
| MSI MS-7C37            | 14       | 0.73%   |
| Gigabyte B450          | 14       | 0.73%   |
| MSI MS-7C02            | 13       | 0.67%   |
| Dell Vostro            | 13       | 0.67%   |
| Unknown                | 13       | 0.67%   |
| ASUS P5G41T-M          | 11       | 0.57%   |
| MSI MS-7B79            | 10       | 0.52%   |
| MSI MS-7721            | 10       | 0.52%   |
| ASUS M5A97             | 10       | 0.52%   |
| ASRock B450            | 10       | 0.52%   |
| Gigabyte B85M-D3H      | 9        | 0.47%   |
| MSI MS-7A38            | 8        | 0.41%   |
| MSI MS-7816            | 8        | 0.41%   |
| HP t620                | 8        | 0.41%   |
| HP ProDesk             | 8        | 0.41%   |
| ASRock B450M           | 8        | 0.41%   |
| Acer Veriton           | 8        | 0.41%   |
| MSI MS-7B89            | 7        | 0.36%   |
| Lenovo ThinkStation    | 7        | 0.36%   |
| Lenovo IdeaCentre      | 7        | 0.36%   |
| Gigabyte Z390          | 7        | 0.36%   |
| Gigabyte GA-78LMT-USB3 | 7        | 0.36%   |
| Gigabyte B560M         | 7        | 0.36%   |
| Gigabyte 970A-DS3P     | 7        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 212      | 10.98%  |
| 2012    | 201      | 10.41%  |
| 2013    | 167      | 8.65%   |
| 2019    | 134      | 6.94%   |
| 2014    | 129      | 6.68%   |
| 2020    | 122      | 6.32%   |
| 2011    | 122      | 6.32%   |
| 2009    | 120      | 6.22%   |
| 2017    | 105      | 5.44%   |
| 2010    | 103      | 5.34%   |
| 2007    | 93       | 4.82%   |
| 2015    | 82       | 4.25%   |
| 2008    | 82       | 4.25%   |
| 2021    | 75       | 3.89%   |
| 2016    | 74       | 3.83%   |
| 2006    | 44       | 2.28%   |
| 2022    | 40       | 2.07%   |
| 2005    | 8        | 0.41%   |
| 2023    | 7        | 0.36%   |
| 2004    | 5        | 0.26%   |
| Unknown | 4        | 0.21%   |
| 2001    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1930     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1903     | 98.09%  |
| Enabled  | 37       | 1.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1928     | 99.9%   |
| Yes  | 2        | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 454      | 22.71%  |
| 8.01-16.0       | 421      | 21.06%  |
| 4.01-8.0        | 298      | 14.91%  |
| 3.01-4.0        | 297      | 14.86%  |
| 32.01-64.0      | 287      | 14.36%  |
| 64.01-256.0     | 88       | 4.4%    |
| 24.01-32.0      | 60       | 3%      |
| 1.01-2.0        | 57       | 2.85%   |
| 2.01-3.0        | 27       | 1.35%   |
| 0.51-1.0        | 9        | 0.45%   |
| More than 256.0 | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 817      | 36.18%  |
| 2.01-3.0    | 467      | 20.68%  |
| 4.01-8.0    | 327      | 14.48%  |
| 3.01-4.0    | 241      | 10.67%  |
| 0.51-1.0    | 219      | 9.7%    |
| 8.01-16.0   | 100      | 4.43%   |
| 0.01-0.5    | 42       | 1.86%   |
| 16.01-24.0  | 32       | 1.42%   |
| 24.01-32.0  | 7        | 0.31%   |
| 32.01-64.0  | 3        | 0.13%   |
| 64.01-256.0 | 2        | 0.09%   |
| Unknown     | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 736      | 35.61%  |
| 2      | 603      | 29.17%  |
| 3      | 379      | 18.34%  |
| 4      | 174      | 8.42%   |
| 5      | 80       | 3.87%   |
| 6      | 34       | 1.64%   |
| 0      | 28       | 1.35%   |
| 7      | 16       | 0.77%   |
| 8      | 7        | 0.34%   |
| 11     | 3        | 0.15%   |
| 9      | 3        | 0.15%   |
| 10     | 2        | 0.1%    |
| 13     | 1        | 0.05%   |
| 12     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 998      | 50.53%  |
| No        | 977      | 49.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1913     | 99.12%  |
| No        | 17       | 0.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1195     | 60.45%  |
| Yes       | 782      | 39.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1457     | 74.03%  |
| Yes       | 511      | 25.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Poland  | 1930     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Warsaw                 | 404      | 18.8%   |
| Krakow                 | 150      | 6.98%   |
| Wroclaw                | 125      | 5.82%   |
| Poznan                 | 82       | 3.82%   |
| Gdansk                 | 72       | 3.35%   |
| Katowice               | 56       | 2.61%   |
| Lodz                   | 53       | 2.47%   |
| Gdynia                 | 32       | 1.49%   |
| Lublin                 | 29       | 1.35%   |
| Szczecin               | 24       | 1.12%   |
| Bialystok              | 23       | 1.07%   |
| Częstochowa           | 20       | 0.93%   |
| Gliwice                | 19       | 0.88%   |
| Strzyzow               | 18       | 0.84%   |
| Bytom                  | 18       | 0.84%   |
| Radom                  | 17       | 0.79%   |
| Torun                  | 16       | 0.74%   |
| Bydgoszcz              | 15       | 0.7%    |
| Rzeszów               | 14       | 0.65%   |
| Rybnik                 | 14       | 0.65%   |
| Ruda Śląska          | 13       | 0.6%    |
| Bielsko-Biala          | 13       | 0.6%    |
| Płock                 | 12       | 0.56%   |
| Kielce                 | 12       | 0.56%   |
| Sosnowiec              | 11       | 0.51%   |
| Zabrze                 | 9        | 0.42%   |
| Słupsk                | 9        | 0.42%   |
| Wodzisław Śląski    | 8        | 0.37%   |
| Tychy                  | 8        | 0.37%   |
| Tarnów                | 8        | 0.37%   |
| Elblag                 | 8        | 0.37%   |
| Debica                 | 8        | 0.37%   |
| Cieszyn                | 8        | 0.37%   |
| Chorzów               | 8        | 0.37%   |
| Zdunska Wola           | 7        | 0.33%   |
| Wołomin               | 7        | 0.33%   |
| Siemianowice Śląskie | 7        | 0.33%   |
| Kościan               | 7        | 0.33%   |
| Jelenia Góra          | 7        | 0.33%   |
| Będzin                | 7        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 621      | 1110   | 16.68%  |
| WDC                         | 615      | 1069   | 16.52%  |
| Samsung Electronics         | 471      | 824    | 12.65%  |
| GOODRAM                     | 285      | 501    | 7.66%   |
| Toshiba                     | 218      | 390    | 5.86%   |
| Crucial                     | 167      | 295    | 4.49%   |
| Kingston                    | 162      | 234    | 4.35%   |
| A-DATA Technology           | 151      | 227    | 4.06%   |
| Hitachi                     | 109      | 211    | 2.93%   |
| Sandisk                     | 103      | 165    | 2.77%   |
| Patriot                     | 67       | 89     | 1.8%    |
| SPCC                        | 50       | 100    | 1.34%   |
| Intel                       | 44       | 70     | 1.18%   |
| XPG                         | 39       | 57     | 1.05%   |
| Plextor                     | 34       | 41     | 0.91%   |
| HGST                        | 33       | 47     | 0.89%   |
| PNY                         | 30       | 35     | 0.81%   |
| Unknown                     | 28       | 51     | 0.75%   |
| Phison                      | 27       | 36     | 0.73%   |
| Apacer                      | 27       | 43     | 0.73%   |
| OCZ                         | 22       | 25     | 0.59%   |
| Micron Technology           | 22       | 31     | 0.59%   |
| Maxtor                      | 22       | 23     | 0.59%   |
| Corsair                     | 21       | 30     | 0.56%   |
| China                       | 21       | 34     | 0.56%   |
| Phison Electronics          | 20       | 34     | 0.54%   |
| Realtek Semiconductor       | 19       | 30     | 0.51%   |
| ADATA Technology            | 18       | 20     | 0.48%   |
| SK hynix                    | 17       | 29     | 0.46%   |
| Fujitsu                     | 17       | 22     | 0.46%   |
| ASMT                        | 15       | 16     | 0.4%    |
| Silicon Motion              | 14       | 18     | 0.38%   |
| Micron/Crucial Technology   | 13       | 13     | 0.35%   |
| Lite-On                     | 12       | 14     | 0.32%   |
| Lexar                       | 9        | 9      | 0.24%   |
| KIOXIA-EXCERIA              | 9        | 16     | 0.24%   |
| KIOXIA                      | 9        | 10     | 0.24%   |
| Kingston Technology Company | 9        | 10     | 0.24%   |
| JMicron Technology          | 8        | 9      | 0.21%   |
| Intenso                     | 8        | 13     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba HDWD110 1TB                                 | 57       | 1.33%   |
| Crucial CT500MX500SSD1 500GB                        | 43       | 1%      |
| Seagate ST500DM002-1BD142 500GB                     | 41       | 0.95%   |
| Samsung SSD 850 EVO 250GB                           | 38       | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB                      | 35       | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB                      | 33       | 0.77%   |
| Seagate ST3500418AS 500GB                           | 31       | 0.72%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 28       | 0.65%   |
| GOODRAM SSD 120GB                                   | 28       | 0.65%   |
| Crucial CT1000MX500SSD1 1TB                         | 28       | 0.65%   |
| Toshiba DT01ACA100 1TB                              | 26       | 0.6%    |
| Samsung NVMe SSD Drive 500GB                        | 26       | 0.6%    |
| Samsung HD502HJ 500GB                               | 26       | 0.6%    |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 26       | 0.6%    |
| Kingston SV300S37A120G 120GB SSD                    | 25       | 0.58%   |
| Toshiba HDWD130 3TB                                 | 23       | 0.54%   |
| Samsung SSD 860 EVO 500GB                           | 23       | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB                      | 22       | 0.51%   |
| Samsung SSD 860 EVO 250GB                           | 22       | 0.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 22       | 0.51%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 22       | 0.51%   |
| GOODRAM SSD 240GB                                   | 22       | 0.51%   |
| Crucial CT240BX500SSD1 240GB                        | 22       | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                      | 20       | 0.47%   |
| GOODRAM SSDPR-CL100-120-G2 120GB                    | 19       | 0.44%   |
| A-DATA SU800 256GB SSD                              | 19       | 0.44%   |
| Patriot Burst 120GB SSD                             | 18       | 0.42%   |
| Kingston SA400S37240G 240GB SSD                     | 18       | 0.42%   |
| Kingston SA400S37480G 480GB SSD                     | 17       | 0.4%    |
| Samsung SSD 980 500GB                               | 16       | 0.37%   |
| Samsung SSD 980 1TB                                 | 16       | 0.37%   |
| A-DATA SX8200PNP 512GB                              | 16       | 0.37%   |
| Seagate ST250DM000-1BD141 250GB                     | 15       | 0.35%   |
| GOODRAM SSDPR-CX400-128 128GB                       | 15       | 0.35%   |
| A-DATA SU650 240GB SSD                              | 15       | 0.35%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 14       | 0.33%   |
| Toshiba HDWD120 2TB                                 | 14       | 0.33%   |
| SPCC Solid State Disk 120GB                         | 14       | 0.33%   |
| Seagate ST3250410AS 250GB                           | 14       | 0.33%   |
| Seagate ST3250310AS 250GB                           | 14       | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 620      | 1106   | 35.61%  |
| WDC                 | 577      | 999    | 33.14%  |
| Toshiba             | 196      | 365    | 11.26%  |
| Samsung Electronics | 143      | 213    | 8.21%   |
| Hitachi             | 109      | 211    | 6.26%   |
| HGST                | 33       | 47     | 1.9%    |
| Maxtor              | 21       | 22     | 1.21%   |
| Fujitsu             | 17       | 22     | 0.98%   |
| WD MediaMax         | 3        | 5      | 0.17%   |
| Unknown             | 3        | 3      | 0.17%   |
| SAGE                | 2        | 2      | 0.11%   |
| ASMT                | 2        | 3      | 0.11%   |
| Unknown             | 2        | 2      | 0.11%   |
| USB3.0              | 1        | 1      | 0.06%   |
| Synology            | 1        | 1      | 0.06%   |
| MARVELL             | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| IB-377U3            | 1        | 6      | 0.06%   |
| HPE                 | 1        | 1      | 0.06%   |
| HGST HTS            | 1        | 1      | 0.06%   |
| Hewlett-Packard     | 1        | 1      | 0.06%   |
| ExcelStor           | 1        | 1      | 0.06%   |
| ASUSTOR             | 1        | 1      | 0.06%   |
| ASMT109x            | 1        | 1      | 0.06%   |
| ASMedia             | 1        | 1      | 0.06%   |
| Apple               | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| GOODRAM             | 277      | 477    | 20.41%  |
| Samsung Electronics | 202      | 313    | 14.89%  |
| Crucial             | 161      | 288    | 11.86%  |
| A-DATA Technology   | 122      | 181    | 8.99%   |
| Kingston            | 101      | 144    | 7.44%   |
| SanDisk             | 75       | 121    | 5.53%   |
| Patriot             | 59       | 81     | 4.35%   |
| SPCC                | 44       | 92     | 3.24%   |
| WDC                 | 33       | 42     | 2.43%   |
| Plextor             | 28       | 35     | 2.06%   |
| Apacer              | 26       | 42     | 1.92%   |
| PNY                 | 24       | 28     | 1.77%   |
| OCZ                 | 22       | 25     | 1.62%   |
| Intel               | 20       | 28     | 1.47%   |
| China               | 20       | 33     | 1.47%   |
| Micron Technology   | 17       | 23     | 1.25%   |
| Toshiba             | 15       | 17     | 1.11%   |
| ASMT                | 13       | 13     | 0.96%   |
| Corsair             | 8        | 9      | 0.59%   |
| Transcend           | 7        | 7      | 0.52%   |
| LITEON              | 7        | 12     | 0.52%   |
| KIOXIA-EXCERIA      | 6        | 11     | 0.44%   |
| Team                | 5        | 6      | 0.37%   |
| Intenso             | 5        | 10     | 0.37%   |
| SK hynix            | 4        | 4      | 0.29%   |
| Lexar               | 4        | 4      | 0.29%   |
| JMicron Technology  | 4        | 4      | 0.29%   |
| LITEONIT            | 3        | 3      | 0.22%   |
| KingSpec            | 3        | 3      | 0.22%   |
| HS-SSD-E100         | 3        | 3      | 0.22%   |
| Hewlett-Packard     | 3        | 3      | 0.22%   |
| BIWIN               | 3        | 3      | 0.22%   |
| SSSTC               | 2        | 2      | 0.15%   |
| PHD 3.0             | 2        | 2      | 0.15%   |
| Kingchuxing         | 2        | 4      | 0.15%   |
| Gigabyte Technology | 2        | 2      | 0.15%   |
| XrayDisk            | 1        | 1      | 0.07%   |
| XPG                 | 1        | 1      | 0.07%   |
| WDC WDS2            | 1        | 1      | 0.07%   |
| Valuetech           | 1        | 1      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1341     | 3018   | 43.87%  |
| SSD     | 1100     | 2104   | 35.98%  |
| NVMe    | 560      | 974    | 18.32%  |
| Unknown | 46       | 74     | 1.5%    |
| MMC     | 10       | 11     | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1756     | 5022   | 71.88%  |
| NVMe | 560      | 973    | 22.92%  |
| SAS  | 117      | 175    | 4.79%   |
| MMC  | 10       | 11     | 0.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1432     | 2910   | 56%     |
| 0.51-1.0   | 726      | 1357   | 28.39%  |
| 1.01-2.0   | 212      | 375    | 8.29%   |
| 3.01-4.0   | 68       | 154    | 2.66%   |
| 2.01-3.0   | 67       | 189    | 2.62%   |
| 4.01-10.0  | 43       | 104    | 1.68%   |
| 10.01-20.0 | 9        | 33     | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 502      | 23.27%  |
| 251-500        | 321      | 14.88%  |
| 501-1000       | 289      | 13.4%   |
| 1-20           | 241      | 11.17%  |
| 1001-2000      | 226      | 10.48%  |
| 51-100         | 155      | 7.19%   |
| More than 3000 | 137      | 6.35%   |
| Unknown        | 109      | 5.05%   |
| 21-50          | 94       | 4.36%   |
| 2001-3000      | 83       | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 825      | 37.41%  |
| 21-50          | 274      | 12.43%  |
| 101-250        | 243      | 11.02%  |
| 51-100         | 188      | 8.53%   |
| 501-1000       | 182      | 8.25%   |
| 251-500        | 176      | 7.98%   |
| 1001-2000      | 112      | 5.08%   |
| Unknown        | 109      | 4.94%   |
| More than 3000 | 50       | 2.27%   |
| 2001-3000      | 46       | 2.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 10       | 13     | 2.39%   |
| Seagate ST500DM002-1BD142 500GB   | 8        | 8      | 1.91%   |
| Seagate ST1000DM003-9YN162 1TB    | 7        | 8      | 1.67%   |
| Seagate ST9500325AS 500GB         | 5        | 8      | 1.2%    |
| GOODRAM SSD 120GB                 | 5        | 5      | 1.2%    |
| ASMT 2135 240GB                   | 5        | 5      | 1.2%    |
| Seagate ST92505610AS 250GB        | 4        | 4      | 0.96%   |
| Seagate ST3320613AS 320GB         | 4        | 4      | 0.96%   |
| Seagate ST1000DX001-1CM162 1TB    | 4        | 7      | 0.96%   |
| WDC WD15EARS-00Z5B1 1TB           | 3        | 3      | 0.72%   |
| WDC WD10JFCX-68N6GN0 1TB          | 3        | 4      | 0.72%   |
| Seagate ST3500320AS 500GB         | 3        | 3      | 0.72%   |
| Seagate ST3500312CS 500GB         | 3        | 3      | 0.72%   |
| Seagate ST3320418AS 320GB         | 3        | 3      | 0.72%   |
| Seagate ST3250410AS 250GB         | 3        | 4      | 0.72%   |
| Seagate ST31500341AS 1TB          | 3        | 4      | 0.72%   |
| Seagate ST2000DX002-2DV164 2TB    | 3        | 5      | 0.72%   |
| Seagate ST1000DX001-1NS162 1TB    | 3        | 5      | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 3      | 0.72%   |
| Samsung Electronics HD502HJ 500GB | 3        | 3      | 0.72%   |
| Samsung Electronics HD321KJ 320GB | 3        | 3      | 0.72%   |
| Samsung Electronics HD103UJ 1TB   | 3        | 4      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 3      | 0.72%   |
| Kingston SA400S37480G 480GB SSD   | 3        | 3      | 0.72%   |
| Hitachi HDP725050GLA360 500GB     | 3        | 4      | 0.72%   |
| WDC WD5002ABYS-01B1B0 500GB       | 2        | 14     | 0.48%   |
| WDC WD5000AVDS-63U7B1 500GB       | 2        | 2      | 0.48%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 2        | 2      | 0.48%   |
| WDC WD5000AAKS-22V1A0 500GB       | 2        | 2      | 0.48%   |
| WDC WD5000AACS-00G8B1 500GB       | 2        | 2      | 0.48%   |
| WDC WD3200AAJS-00B4A0 320GB       | 2        | 4      | 0.48%   |
| WDC WD2500AAJS-75M0A0 250GB       | 2        | 2      | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 10     | 0.48%   |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 4      | 0.48%   |
| WDC WD10EZEX-00RKKA0 1TB          | 2        | 3      | 0.48%   |
| WDC WD10EARS-00Y5B1 1TB           | 2        | 2      | 0.48%   |
| WDC WD10EADS-22M2B0 1TB           | 2        | 4      | 0.48%   |
| WD MediaMax WL1000GSA6472B 1TB    | 2        | 3      | 0.48%   |
| Toshiba MQ04ABF100 1TB            | 2        | 3      | 0.48%   |
| Toshiba MQ01ABD100 1TB            | 2        | 2      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 129      | 172    | 33.08%  |
| WDC                   | 93       | 152    | 23.85%  |
| Samsung Electronics   | 38       | 45     | 9.74%   |
| Hitachi               | 23       | 34     | 5.9%    |
| Toshiba               | 13       | 14     | 3.33%   |
| A-DATA Technology     | 13       | 14     | 3.33%   |
| SanDisk               | 9        | 11     | 2.31%   |
| Kingston              | 9        | 9      | 2.31%   |
| GOODRAM               | 8        | 8      | 2.05%   |
| Maxtor                | 6        | 7      | 1.54%   |
| ASMT                  | 6        | 7      | 1.54%   |
| Fujitsu               | 4        | 6      | 1.03%   |
| WD MediaMax           | 3        | 4      | 0.77%   |
| SPCC                  | 3        | 3      | 0.77%   |
| HGST                  | 3        | 3      | 0.77%   |
| Hewlett-Packard       | 3        | 3      | 0.77%   |
| China                 | 3        | 3      | 0.77%   |
| Apacer                | 3        | 6      | 0.77%   |
| SSSTC                 | 2        | 2      | 0.51%   |
| LITEON                | 2        | 2      | 0.51%   |
| Intel                 | 2        | 2      | 0.51%   |
| Crucial               | 2        | 2      | 0.51%   |
| XPG                   | 1        | 1      | 0.26%   |
| WDC WDS2              | 1        | 1      | 0.26%   |
| SAGE                  | 1        | 1      | 0.26%   |
| Realtek Semiconductor | 1        | 1      | 0.26%   |
| Patriot               | 1        | 1      | 0.26%   |
| OCZ                   | 1        | 1      | 0.26%   |
| Micron Technology     | 1        | 1      | 0.26%   |
| LITEONIT              | 1        | 1      | 0.26%   |
| KingFast              | 1        | 1      | 0.26%   |
| HPE                   | 1        | 1      | 0.26%   |
| Corsair               | 1        | 2      | 0.26%   |
| Apple                 | 1        | 1      | 0.26%   |
| Unknown               | 1        | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 129      | 172    | 41.61%  |
| WDC                 | 92       | 150    | 29.68%  |
| Samsung Electronics | 32       | 38     | 10.32%  |
| Hitachi             | 23       | 34     | 7.42%   |
| Toshiba             | 13       | 14     | 4.19%   |
| Maxtor              | 6        | 7      | 1.94%   |
| Fujitsu             | 4        | 6      | 1.29%   |
| WD MediaMax         | 3        | 4      | 0.97%   |
| HGST                | 3        | 3      | 0.97%   |
| SAGE                | 1        | 1      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| ASMT                | 1        | 2      | 0.32%   |
| Apple               | 1        | 1      | 0.32%   |
| Unknown             | 1        | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 275      | 434    | 77.9%   |
| SSD  | 71       | 82     | 20.11%  |
| NVMe | 7        | 7      | 1.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB       | 1        | 1      | 12.5%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 12.5%   |
| Toshiba DT01ACA100 1TB            | 1        | 2      | 12.5%   |
| Seagate ST500DM002-1BC142 500GB   | 1        | 1      | 12.5%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 12.5%   |
| Samsung Electronics HD250HJ 250GB | 1        | 1      | 12.5%   |
| OCZ-AGIL ITY3 64GB SSD            | 1        | 1      | 12.5%   |
| HGST HTS725025A7 250GB            | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 25%     |
| Seagate             | 2        | 2      | 25%     |
| Toshiba             | 1        | 2      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| OCZ-AGIL            | 1        | 1      | 12.5%   |
| HGST                | 1        | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 964      | 2921   | 42.6%   |
| Works    | 948      | 2728   | 41.89%  |
| Malfunc  | 343      | 523    | 15.16%  |
| Failed   | 8        | 9      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 1184     | 41.33%  |
| AMD                            | 662      | 23.11%  |
| Samsung Electronics            | 191      | 6.67%   |
| ASMedia Technology             | 111      | 3.87%   |
| JMicron Technology             | 103      | 3.6%    |
| ADATA Technology               | 82       | 2.86%   |
| Phison Electronics             | 81       | 2.83%   |
| Kingston Technology Company    | 73       | 2.55%   |
| Nvidia                         | 70       | 2.44%   |
| Marvell Technology Group       | 50       | 1.75%   |
| SanDisk                        | 47       | 1.64%   |
| Realtek Semiconductor          | 28       | 0.98%   |
| Silicon Motion                 | 27       | 0.94%   |
| Lite-On Technology             | 20       | 0.7%    |
| Micron/Crucial Technology      | 18       | 0.63%   |
| VIA Technologies               | 17       | 0.59%   |
| KIOXIA                         | 14       | 0.49%   |
| Shenzhen Longsys Electronics   | 13       | 0.45%   |
| LSI Logic / Symbios Logic      | 12       | 0.42%   |
| SK hynix                       | 11       | 0.38%   |
| Silicon Image                  | 7        | 0.24%   |
| Toshiba America Info Systems   | 6        | 0.21%   |
| Micron Technology              | 6        | 0.21%   |
| MAXIO Technology (Hangzhou)    | 4        | 0.14%   |
| INNOGRIT                       | 4        | 0.14%   |
| Hewlett-Packard                | 4        | 0.14%   |
| Broadcom / LSI                 | 4        | 0.14%   |
| Integrated Technology Express  | 3        | 0.1%    |
| Union Memory (Shenzhen)        | 2        | 0.07%   |
| ULi Electronics                | 2        | 0.07%   |
| Solid State Storage Technology | 2        | 0.07%   |
| Seagate Technology             | 2        | 0.07%   |
| Lite-On IT Corp. / Plextor     | 2        | 0.07%   |
| Tekram Technology              | 1        | 0.03%   |
| Broadcom                       | 1        | 0.03%   |
| Adaptec                        | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 380      | 10.35%  |
| AMD 400 Series Chipset SATA Controller                                                  | 180      | 4.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 158      | 4.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 106      | 2.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 105      | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 103      | 2.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 103      | 2.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 101      | 2.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 97       | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 87       | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 82       | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 77       | 2.1%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 73       | 1.99%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 72       | 1.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 71       | 1.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 67       | 1.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 64       | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 61       | 1.66%   |
| Intel SATA Controller [RAID mode]                                                       | 54       | 1.47%   |
| Phison E12 NVMe Controller                                                              | 46       | 1.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 43       | 1.17%   |
| Nvidia MCP61 SATA Controller                                                            | 37       | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 37       | 1.01%   |
| Nvidia MCP61 IDE                                                                        | 36       | 0.98%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 35       | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 34       | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 33       | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 29       | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                                  | 29       | 0.79%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 27       | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 26       | 0.71%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 26       | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25       | 0.68%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 24       | 0.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 24       | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 22       | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 21       | 0.57%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 20       | 0.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 20       | 0.54%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 20       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1526     | 54.71%  |
| NVMe | 568      | 20.37%  |
| IDE  | 564      | 20.22%  |
| RAID | 107      | 3.84%   |
| SAS  | 13       | 0.47%   |
| SCSI | 11       | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1195     | 61.92%  |
| AMD          | 733      | 37.98%  |
| PowerMac11,2 | 1        | 0.05%   |
| PowerBook6,7 | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 47       | 2.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 36       | 1.84%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 30       | 1.54%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 30       | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 28       | 1.43%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 25       | 1.28%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 24       | 1.23%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 23       | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 23       | 1.18%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 23       | 1.18%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 20       | 1.02%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 19       | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 18       | 0.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 18       | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 17       | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 17       | 0.87%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 16       | 0.82%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 0.82%   |
| AMD Phenom II X4 955 Processor              | 16       | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 13       | 0.67%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 13       | 0.67%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 13       | 0.67%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 13       | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 12       | 0.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 12       | 0.61%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 12       | 0.61%   |
| AMD FX-8350 Eight-Core Processor            | 12       | 0.61%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.56%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 11       | 0.56%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 11       | 0.56%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 11       | 0.56%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 11       | 0.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 10       | 0.51%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 10       | 0.51%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 10       | 0.51%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 10       | 0.51%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 10       | 0.51%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 10       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 369      | 18.97%  |
| Intel Core i7           | 199      | 10.23%  |
| AMD Ryzen 5             | 199      | 10.23%  |
| Intel Core i3           | 118      | 6.07%   |
| AMD Ryzen 7             | 110      | 5.66%   |
| Intel Xeon              | 102      | 5.24%   |
| Intel Core 2 Duo        | 85       | 4.37%   |
| Intel Core 2 Quad       | 71       | 3.65%   |
| AMD Ryzen 9             | 57       | 2.93%   |
| Other                   | 56       | 2.88%   |
| AMD FX                  | 55       | 2.83%   |
| Intel Pentium           | 47       | 2.42%   |
| Intel Celeron           | 45       | 2.31%   |
| AMD Phenom II X4        | 40       | 2.06%   |
| Intel Pentium Dual-Core | 35       | 1.8%    |
| AMD Athlon 64 X2        | 33       | 1.7%    |
| AMD Ryzen 3             | 30       | 1.54%   |
| AMD Athlon II X2        | 29       | 1.49%   |
| AMD A10                 | 22       | 1.13%   |
| Intel Core 2            | 21       | 1.08%   |
| AMD Athlon II X4        | 20       | 1.03%   |
| AMD A8                  | 20       | 1.03%   |
| Intel Pentium Dual      | 18       | 0.93%   |
| Intel Core i9           | 12       | 0.62%   |
| AMD GX                  | 12       | 0.62%   |
| AMD A6                  | 12       | 0.62%   |
| AMD Ryzen Threadripper  | 11       | 0.57%   |
| AMD Athlon              | 10       | 0.51%   |
| Intel Pentium 4         | 8        | 0.41%   |
| AMD Phenom II X6        | 8        | 0.41%   |
| Intel Pentium Gold      | 7        | 0.36%   |
| Intel Pentium D         | 7        | 0.36%   |
| AMD Athlon 64           | 7        | 0.36%   |
| AMD A4                  | 7        | 0.36%   |
| AMD Sempron             | 6        | 0.31%   |
| AMD Ryzen 5 PRO         | 6        | 0.31%   |
| AMD G                   | 6        | 0.31%   |
| AMD Athlon II X3        | 6        | 0.31%   |
| Intel Atom              | 5        | 0.26%   |
| AMD Phenom II X2        | 5        | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 778      | 39.82%  |
| 2       | 482      | 24.67%  |
| 6       | 309      | 15.81%  |
| 8       | 161      | 8.24%   |
| 12      | 64       | 3.28%   |
| Unknown | 45       | 2.3%    |
| 1       | 39       | 2%      |
| 16      | 29       | 1.48%   |
| 3       | 22       | 1.13%   |
| 10      | 10       | 0.51%   |
| 14      | 4        | 0.2%    |
| 24      | 3        | 0.15%   |
| 32      | 2        | 0.1%    |
| 20      | 2        | 0.1%    |
| 64      | 1        | 0.05%   |
| 44      | 1        | 0.05%   |
| 28      | 1        | 0.05%   |
| 18      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1903     | 98.55%  |
| 2      | 28       | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 958      | 49.13%  |
| 1       | 947      | 48.56%  |
| Unknown | 45       | 2.31%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1911     | 98.76%  |
| Unknown        | 17       | 0.88%   |
| 32-bit         | 7        | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 517      | 25.28%  |
| 0x306c3    | 165      | 8.07%   |
| 0x1067a    | 110      | 5.38%   |
| 0x306a9    | 103      | 5.04%   |
| 0x206a7    | 84       | 4.11%   |
| 0x0800820d | 71       | 3.47%   |
| 0x08701021 | 66       | 3.23%   |
| 0x506e3    | 64       | 3.13%   |
| 0x010000c8 | 54       | 2.64%   |
| 0x906ea    | 48       | 2.35%   |
| 0x906e9    | 43       | 2.1%    |
| 0x06001119 | 29       | 1.42%   |
| 0x6fb      | 28       | 1.37%   |
| 0x08701013 | 28       | 1.37%   |
| 0xa0653    | 26       | 1.27%   |
| 0x06000852 | 26       | 1.27%   |
| 0x10676    | 25       | 1.22%   |
| 0x08001138 | 23       | 1.12%   |
| 0x6fd      | 20       | 0.98%   |
| 0x06003106 | 18       | 0.88%   |
| 0x106e5    | 16       | 0.78%   |
| 0x10677    | 16       | 0.78%   |
| 0x6f6      | 15       | 0.73%   |
| 0x206c2    | 15       | 0.73%   |
| 0x0a201016 | 15       | 0.73%   |
| 0x08101016 | 14       | 0.68%   |
| 0x08108109 | 13       | 0.64%   |
| 0x010000db | 13       | 0.64%   |
| 0xa0671    | 12       | 0.59%   |
| 0x306f2    | 12       | 0.59%   |
| 0x0a50000d | 12       | 0.59%   |
| 0x0a50000c | 12       | 0.59%   |
| 0x08001137 | 12       | 0.59%   |
| 0x0a20120a | 11       | 0.54%   |
| 0x0a201009 | 11       | 0.54%   |
| 0xa0655    | 10       | 0.49%   |
| 0x0a601203 | 10       | 0.49%   |
| 0x206d7    | 9        | 0.44%   |
| 0x906ed    | 8        | 0.39%   |
| 0x906ec    | 8        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 225      | 11.57%  |
| Penryn           | 170      | 8.74%   |
| KabyLake         | 151      | 7.76%   |
| IvyBridge        | 140      | 7.2%    |
| Zen 2            | 134      | 6.89%   |
| SandyBridge      | 118      | 6.07%   |
| K10              | 116      | 5.96%   |
| Zen+             | 114      | 5.86%   |
| Skylake          | 96       | 4.94%   |
| Core             | 89       | 4.58%   |
| Zen 3            | 79       | 4.06%   |
| Piledriver       | 74       | 3.8%    |
| Zen              | 71       | 3.65%   |
| K8 Hammer        | 53       | 2.72%   |
| Unknown          | 49       | 2.52%   |
| CometLake        | 45       | 2.31%   |
| Nehalem          | 33       | 1.7%    |
| Westmere         | 28       | 1.44%   |
| Alderlake Hybrid | 23       | 1.18%   |
| Steamroller      | 20       | 1.03%   |
| NetBurst         | 18       | 0.93%   |
| Jaguar           | 17       | 0.87%   |
| Bulldozer        | 13       | 0.67%   |
| Silvermont       | 12       | 0.62%   |
| Icelake          | 12       | 0.62%   |
| Bobcat           | 11       | 0.57%   |
| K10 Llano        | 7        | 0.36%   |
| Goldmont plus    | 7        | 0.36%   |
| Broadwell        | 7        | 0.36%   |
| Goldmont         | 4        | 0.21%   |
| Excavator        | 4        | 0.21%   |
| Puma             | 2        | 0.1%    |
| P6               | 1        | 0.05%   |
| Gracemont        | 1        | 0.05%   |
| Bonnell          | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 909      | 43.93%  |
| AMD                        | 638      | 30.84%  |
| Intel                      | 514      | 24.84%  |
| ASPEED Technology          | 5        | 0.24%   |
| Matrox Electronics Systems | 2        | 0.1%    |
| S3 Graphics                | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 110      | 5.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 107      | 4.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 61       | 2.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 50       | 2.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 47       | 2.18%   |
| Intel HD Graphics 530                                                       | 47       | 2.18%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 45       | 2.09%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 44       | 2.04%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 33       | 1.53%   |
| Nvidia GT218 [GeForce 210]                                                  | 32       | 1.49%   |
| Nvidia GK208B [GeForce GT 710]                                              | 30       | 1.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 30       | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 29       | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 27       | 1.25%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 26       | 1.21%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 25       | 1.16%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 24       | 1.12%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 24       | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22       | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 22       | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 21       | 0.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 20       | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 20       | 0.93%   |
| Intel HD Graphics 630                                                       | 20       | 0.93%   |
| AMD Raphael                                                                 | 18       | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18       | 0.84%   |
| Nvidia GF108 [GeForce GT 630]                                               | 17       | 0.79%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 17       | 0.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 17       | 0.79%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 17       | 0.79%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 17       | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 15       | 0.7%    |
| Nvidia GK208B [GeForce GT 730]                                              | 15       | 0.7%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 15       | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                               | 15       | 0.7%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 15       | 0.7%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 14       | 0.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 14       | 0.65%   |
| Intel AlderLake-S GT1                                                       | 14       | 0.65%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 14       | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 851      | 43.02%  |
| 1 x AMD         | 573      | 28.97%  |
| 1 x Intel       | 435      | 21.99%  |
| 2 x AMD         | 31       | 1.57%   |
| Intel + Nvidia  | 26       | 1.31%   |
| AMD + Nvidia    | 22       | 1.11%   |
| Intel + AMD     | 17       | 0.86%   |
| 2 x Nvidia      | 7        | 0.35%   |
| 2 x Intel       | 5        | 0.25%   |
| 1 x ASPEED      | 3        | 0.15%   |
| 3 x AMD         | 2        | 0.1%    |
| Nvidia + ASPEED | 2        | 0.1%    |
| 1 x Matrox      | 2        | 0.1%    |
| Other           | 1        | 0.05%   |
| 1 x S3 Graphics | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1416     | 70.98%  |
| Proprietary | 491      | 24.61%  |
| Unknown     | 88       | 4.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 728      | 35.49%  |
| 1.01-2.0   | 285      | 13.9%   |
| 0.51-1.0   | 265      | 12.92%  |
| 0.01-0.5   | 256      | 12.48%  |
| 7.01-8.0   | 184      | 8.97%   |
| 3.01-4.0   | 168      | 8.19%   |
| 5.01-6.0   | 84       | 4.1%    |
| 8.01-16.0  | 53       | 2.58%   |
| 2.01-3.0   | 19       | 0.93%   |
| 16.01-24.0 | 8        | 0.39%   |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 354      | 16.85%  |
| Goldstar             | 255      | 12.14%  |
| Dell                 | 212      | 10.09%  |
| Philips              | 143      | 6.81%   |
| Iiyama               | 131      | 6.24%   |
| Hewlett-Packard      | 115      | 5.47%   |
| Acer                 | 112      | 5.33%   |
| BenQ                 | 107      | 5.09%   |
| AOC                  | 87       | 4.14%   |
| Eizo                 | 71       | 3.38%   |
| NEC Computers        | 64       | 3.05%   |
| Ancor Communications | 52       | 2.48%   |
| Fujitsu Siemens      | 35       | 1.67%   |
| Sony                 | 34       | 1.62%   |
| LG Electronics       | 34       | 1.62%   |
| Lenovo               | 34       | 1.62%   |
| Unknown              | 22       | 1.05%   |
| ASUSTek Computer     | 20       | 0.95%   |
| Idek Iiyama          | 17       | 0.81%   |
| Gigabyte Technology  | 11       | 0.52%   |
| Gateway              | 11       | 0.52%   |
| Belinea              | 11       | 0.52%   |
| ViewSonic            | 10       | 0.48%   |
| Toshiba              | 9        | 0.43%   |
| MSI                  | 9        | 0.43%   |
| Panasonic            | 8        | 0.38%   |
| Unknown              | 8        | 0.38%   |
| Medion               | 7        | 0.33%   |
| Hyundai ImageQuest   | 7        | 0.33%   |
| RTK                  | 5        | 0.24%   |
| IBM                  | 5        | 0.24%   |
| Hitachi              | 5        | 0.24%   |
| Arnos Instruments    | 5        | 0.24%   |
| Vestel Elektronik    | 4        | 0.19%   |
| Sharp                | 4        | 0.19%   |
| OEM                  | 4        | 0.19%   |
| Xiaomi               | 3        | 0.14%   |
| Vestel               | 3        | 0.14%   |
| TCL                  | 3        | 0.14%   |
| Plain Tree Systems   | 3        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 14       | 0.62%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                | 14       | 0.62%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 12       | 0.53%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 12       | 0.53%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                   | 11       | 0.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 10       | 0.44%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 9        | 0.4%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 9        | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 9        | 0.4%    |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 9        | 0.4%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 8        | 0.35%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 8        | 0.35%   |
| Unknown                                                              | 8        | 0.35%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 7        | 0.31%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch             | 7        | 0.31%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                    | 7        | 0.31%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                  | 7        | 0.31%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 6        | 0.27%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch             | 6        | 0.27%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 6        | 0.27%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch              | 6        | 0.27%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                | 6        | 0.27%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 509x286mm 23.0-inch         | 6        | 0.27%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch             | 6        | 0.27%   |
| Eizo EV2316W ENC2394 1920x1080 510x287mm 23.0-inch                   | 6        | 0.27%   |
| Dell U2212HM DELD047 1920x1080 475x267mm 21.5-inch                   | 6        | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 6        | 0.27%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch | 5        | 0.22%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                   | 5        | 0.22%   |
| NEC Computers EA223WM NEC6890 1680x1050 474x296mm 22.0-inch          | 5        | 0.22%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                 | 5        | 0.22%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                | 5        | 0.22%   |
| Hewlett-Packard LA2306 HWP294B 1920x1080 509x286mm 23.0-inch         | 5        | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 5        | 0.22%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                 | 5        | 0.22%   |
| Goldstar E2242 GSM58BE 1920x1080 477x268mm 21.5-inch                 | 5        | 0.22%   |
| Eizo EV2316W ENC2393 1920x1080 510x287mm 23.0-inch                   | 5        | 0.22%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                    | 5        | 0.22%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 5        | 0.22%   |
| Acer VG270U P ACR06CF 2560x1440 597x336mm 27.0-inch                  | 5        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 913      | 44.6%   |
| 1280x1024 (SXGA)   | 213      | 10.41%  |
| 2560x1440 (QHD)    | 154      | 7.52%   |
| 1680x1050 (WSXGA+) | 142      | 6.94%   |
| 3840x2160 (4K)     | 139      | 6.79%   |
| 1920x1200 (WUXGA)  | 98       | 4.79%   |
| 1440x900 (WXGA+)   | 80       | 3.91%   |
| Unknown            | 45       | 2.2%    |
| 1366x768 (WXGA)    | 40       | 1.95%   |
| 3440x1440          | 33       | 1.61%   |
| 2560x1080          | 31       | 1.51%   |
| 1600x1200          | 21       | 1.03%   |
| 1360x768           | 19       | 0.93%   |
| 3840x1080          | 15       | 0.73%   |
| 1024x768 (XGA)     | 15       | 0.73%   |
| 1920x540           | 10       | 0.49%   |
| 1600x900 (HD+)     | 10       | 0.49%   |
| 2288x1287          | 8        | 0.39%   |
| 1280x720 (HD)      | 5        | 0.24%   |
| 5120x1440          | 4        | 0.2%    |
| 2560x1600          | 4        | 0.2%    |
| 2048x1152          | 4        | 0.2%    |
| 1280x960           | 4        | 0.2%    |
| 4480x1440          | 3        | 0.15%   |
| 3840x1200          | 3        | 0.15%   |
| 3200x1080          | 3        | 0.15%   |
| 5760x1080          | 2        | 0.1%    |
| 5120x1080          | 2        | 0.1%    |
| 3840x1600          | 2        | 0.1%    |
| 3600x1080          | 2        | 0.1%    |
| 1400x1050          | 2        | 0.1%    |
| 1280x768           | 2        | 0.1%    |
| 7280x1440          | 1        | 0.05%   |
| 720x576            | 1        | 0.05%   |
| 720x480            | 1        | 0.05%   |
| 6880x1440          | 1        | 0.05%   |
| 6400x1440          | 1        | 0.05%   |
| 5760x1200          | 1        | 0.05%   |
| 5120x2160          | 1        | 0.05%   |
| 5040x1050          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 310      | 14.91%  |
| 21      | 256      | 12.31%  |
| 23      | 252      | 12.12%  |
| 27      | 243      | 11.69%  |
| Unknown | 213      | 10.25%  |
| 19      | 178      | 8.56%   |
| 22      | 95       | 4.57%   |
| 17      | 93       | 4.47%   |
| 18      | 56       | 2.69%   |
| 34      | 55       | 2.65%   |
| 31      | 54       | 2.6%    |
| 20      | 40       | 1.92%   |
| 72      | 23       | 1.11%   |
| 84      | 20       | 0.96%   |
| 25      | 20       | 0.96%   |
| 15      | 20       | 0.96%   |
| 32      | 18       | 0.87%   |
| 54      | 17       | 0.82%   |
| 40      | 16       | 0.77%   |
| 65      | 10       | 0.48%   |
| 46      | 9        | 0.43%   |
| 142     | 8        | 0.38%   |
| 33      | 8        | 0.38%   |
| 42      | 7        | 0.34%   |
| 28      | 7        | 0.34%   |
| 26      | 6        | 0.29%   |
| 48      | 4        | 0.19%   |
| 43      | 4        | 0.19%   |
| 39      | 4        | 0.19%   |
| 29      | 4        | 0.19%   |
| 14      | 4        | 0.19%   |
| 12      | 4        | 0.19%   |
| 55      | 3        | 0.14%   |
| 50      | 3        | 0.14%   |
| 49      | 3        | 0.14%   |
| 37      | 3        | 0.14%   |
| 47      | 2        | 0.1%    |
| 35      | 2        | 0.1%    |
| 85      | 1        | 0.05%   |
| 59      | 1        | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 765      | 37.83%  |
| 401-500        | 499      | 24.68%  |
| Unknown        | 213      | 10.53%  |
| 351-400        | 120      | 5.93%   |
| 301-350        | 111      | 5.49%   |
| 601-700        | 84       | 4.15%   |
| 701-800        | 82       | 4.06%   |
| 1001-1500      | 52       | 2.57%   |
| 1501-2000      | 44       | 2.18%   |
| 801-900        | 27       | 1.34%   |
| 901-1000       | 10       | 0.49%   |
| More than 2000 | 8        | 0.4%    |
| 201-300        | 7        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1103     | 56.74%  |
| 16/10   | 308      | 15.84%  |
| 5/4     | 200      | 10.29%  |
| Unknown | 190      | 9.77%   |
| 21/9    | 61       | 3.14%   |
| 4/3     | 43       | 2.21%   |
| 3/2     | 20       | 1.03%   |
| 1.00    | 8        | 0.41%   |
| 32/9    | 6        | 0.31%   |
| 6/5     | 4        | 0.21%   |
| 0.56    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 713      | 34.85%  |
| 151-200        | 282      | 13.78%  |
| 301-350        | 247      | 12.07%  |
| Unknown        | 213      | 10.41%  |
| 251-300        | 148      | 7.23%   |
| 351-500        | 145      | 7.09%   |
| 141-150        | 130      | 6.35%   |
| More than 1000 | 91       | 4.45%   |
| 501-1000       | 49       | 2.39%   |
| 101-110        | 16       | 0.78%   |
| 71-80          | 4        | 0.2%    |
| 111-120        | 4        | 0.2%    |
| 91-100         | 3        | 0.15%   |
| 81-90          | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1196     | 61.27%  |
| 101-120 | 377      | 19.31%  |
| Unknown | 213      | 10.91%  |
| 1-50    | 83       | 4.25%   |
| 121-160 | 55       | 2.82%   |
| 161-240 | 28       | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1568     | 78.99%  |
| 2     | 278      | 14.01%  |
| 0     | 91       | 4.58%   |
| 3     | 41       | 2.07%   |
| 4     | 7        | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1192     | 42.88%  |
| Intel                                  | 685      | 24.64%  |
| Qualcomm Atheros                       | 203      | 7.3%    |
| TP-Link                                | 89       | 3.2%    |
| Broadcom                               | 87       | 3.13%   |
| Ralink Technology                      | 58       | 2.09%   |
| Nvidia                                 | 52       | 1.87%   |
| Qualcomm Atheros Communications        | 45       | 1.62%   |
| Ralink                                 | 38       | 1.37%   |
| Microsoft                              | 34       | 1.22%   |
| MediaTek                               | 30       | 1.08%   |
| Huawei Technologies                    | 29       | 1.04%   |
| Marvell Technology Group               | 26       | 0.94%   |
| Xiaomi                                 | 23       | 0.83%   |
| Broadcom Limited                       | 22       | 0.79%   |
| ASUSTek Computer                       | 22       | 0.79%   |
| Samsung Electronics                    | 16       | 0.58%   |
| Aquantia                               | 12       | 0.43%   |
| Edimax Technology                      | 11       | 0.4%    |
| D-Link                                 | 9        | 0.32%   |
| VIA Technologies                       | 7        | 0.25%   |
| Motorola PCS                           | 6        | 0.22%   |
| Sony Ericsson Mobile Communications AB | 5        | 0.18%   |
| NetGear                                | 5        | 0.18%   |
| OPPO Electronics                       | 4        | 0.14%   |
| D-Link System                          | 4        | 0.14%   |
| Texas Instruments                      | 3        | 0.11%   |
| Sagem                                  | 3        | 0.11%   |
| HTC (High Tech Computer)               | 3        | 0.11%   |
| ZyXEL Communications                   | 2        | 0.07%   |
| ZyDAS                                  | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.07%   |
| Seeed Technology                       | 2        | 0.07%   |
| Research In Motion                     | 2        | 0.07%   |
| QLogic                                 | 2        | 0.07%   |
| QinHeng Electronics                    | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.07%   |
| NetXen Incorporated                    | 2        | 0.07%   |
| Loupedeck                              | 2        | 0.07%   |
| ICS Advent                             | 2        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 956      | 31.35%  |
| Realtek RTL8125 2.5GbE Controller                                 | 88       | 2.89%   |
| Intel I211 Gigabit Network Connection                             | 88       | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88       | 2.89%   |
| Intel Ethernet Connection (2) I219-V                              | 66       | 2.16%   |
| Intel Wi-Fi 6 AX200                                               | 61       | 2%      |
| Intel Ethernet Connection I217-LM                                 | 44       | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40       | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 38       | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35       | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35       | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                   | 34       | 1.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 32       | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 32       | 1.05%   |
| Nvidia MCP61 Ethernet                                             | 30       | 0.98%   |
| Intel Ethernet Controller I225-V                                  | 29       | 0.95%   |
| Ralink MT7601U Wireless Adapter                                   | 27       | 0.89%   |
| Intel Wireless-AC 9260                                            | 25       | 0.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23       | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 23       | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22       | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 21       | 0.69%   |
| Microsoft Xbox 360 Wireless Adapter                               | 21       | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 19       | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 19       | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.59%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 17       | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17       | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 16       | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 16       | 0.52%   |
| Realtek 802.11ac NIC                                              | 16       | 0.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16       | 0.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 16       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16       | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 15       | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15       | 0.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15       | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 190      | 22.46%  |
| Realtek Semiconductor           | 172      | 20.33%  |
| Qualcomm Atheros                | 97       | 11.47%  |
| TP-Link                         | 88       | 10.4%   |
| Ralink Technology               | 58       | 6.86%   |
| Qualcomm Atheros Communications | 45       | 5.32%   |
| Ralink                          | 38       | 4.49%   |
| Microsoft                       | 34       | 4.02%   |
| MediaTek                        | 28       | 3.31%   |
| Broadcom                        | 27       | 3.19%   |
| ASUSTek Computer                | 22       | 2.6%    |
| Edimax Technology               | 11       | 1.3%    |
| D-Link                          | 9        | 1.06%   |
| NetGear                         | 5        | 0.59%   |
| Sagem                           | 3        | 0.35%   |
| D-Link System                   | 3        | 0.35%   |
| ZyXEL Communications            | 2        | 0.24%   |
| ZyDAS                           | 2        | 0.24%   |
| Broadcom Limited                | 2        | 0.24%   |
| Belkin Components               | 2        | 0.24%   |
| Z-Com                           | 1        | 0.12%   |
| Wacom                           | 1        | 0.12%   |
| Ovislink                        | 1        | 0.12%   |
| Marvell Technology Group        | 1        | 0.12%   |
| Linksys                         | 1        | 0.12%   |
| IMC Networks                    | 1        | 0.12%   |
| AVM                             | 1        | 0.12%   |
| Accton Technology               | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 61       | 7.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 35       | 4.09%   |
| Qualcomm Atheros AR9271 802.11n                                               | 34       | 3.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 32       | 3.74%   |
| Ralink MT7601U Wireless Adapter                                               | 27       | 3.16%   |
| Intel Wireless-AC 9260                                                        | 25       | 2.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 22       | 2.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 21       | 2.46%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 21       | 2.46%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 17       | 1.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 17       | 1.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 16       | 1.87%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 16       | 1.87%   |
| Realtek 802.11ac NIC                                                          | 16       | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 16       | 1.87%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 16       | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 15       | 1.75%   |
| Ralink RT5370 Wireless Adapter                                                | 14       | 1.64%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 14       | 1.64%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 13       | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 11       | 1.29%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 11       | 1.29%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 11       | 1.29%   |
| Microsoft XBOX ACC                                                            | 11       | 1.29%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 10       | 1.17%   |
| Intel Wireless 7260                                                           | 10       | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 9        | 1.05%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                | 9        | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 8        | 0.94%   |
| TP-Link 802.11ac NIC                                                          | 8        | 0.94%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 8        | 0.94%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 7        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 7        | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 7        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 7        | 0.82%   |
| Intel Wireless 8260                                                           | 7        | 0.82%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 7        | 0.82%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 6        | 0.7%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 6        | 0.7%    |
| TP-Link 802.11ac WLAN Adapter                                                 | 6        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1117     | 53.42%  |
| Intel                                  | 589      | 28.17%  |
| Qualcomm Atheros                       | 114      | 5.45%   |
| Broadcom                               | 60       | 2.87%   |
| Nvidia                                 | 52       | 2.49%   |
| Marvell Technology Group               | 26       | 1.24%   |
| Xiaomi                                 | 23       | 1.1%    |
| Broadcom Limited                       | 20       | 0.96%   |
| Huawei Technologies                    | 17       | 0.81%   |
| Aquantia                               | 12       | 0.57%   |
| Samsung Electronics                    | 10       | 0.48%   |
| VIA Technologies                       | 7        | 0.33%   |
| Motorola PCS                           | 5        | 0.24%   |
| Sony Ericsson Mobile Communications AB | 4        | 0.19%   |
| OPPO Electronics                       | 4        | 0.19%   |
| HTC (High Tech Computer)               | 3        | 0.14%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.1%    |
| TP-Link                                | 2        | 0.1%    |
| Research In Motion                     | 2        | 0.1%    |
| QLogic                                 | 2        | 0.1%    |
| NetXen Incorporated                    | 2        | 0.1%    |
| ICS Advent                             | 2        | 0.1%    |
| ASIX Electronics                       | 2        | 0.1%    |
| Apple                                  | 2        | 0.1%    |
| 3Com                                   | 2        | 0.1%    |
| Qualcomm                               | 1        | 0.05%   |
| Mellanox Technologies                  | 1        | 0.05%   |
| MediaTek                               | 1        | 0.05%   |
| Lenovo                                 | 1        | 0.05%   |
| Google                                 | 1        | 0.05%   |
| Foxconn / Hon Hai                      | 1        | 0.05%   |
| D-Link System                          | 1        | 0.05%   |
| American Megatrends                    | 1        | 0.05%   |
| AMD                                    | 1        | 0.05%   |
| ADMtek                                 | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 956      | 44.53%  |
| Realtek RTL8125 2.5GbE Controller                                 | 88       | 4.1%    |
| Intel I211 Gigabit Network Connection                             | 88       | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88       | 4.1%    |
| Intel Ethernet Connection (2) I219-V                              | 66       | 3.07%   |
| Intel Ethernet Connection I217-LM                                 | 44       | 2.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40       | 1.86%   |
| Intel 82579V Gigabit Network Connection                           | 38       | 1.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35       | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 32       | 1.49%   |
| Nvidia MCP61 Ethernet                                             | 30       | 1.4%    |
| Intel Ethernet Controller I225-V                                  | 29       | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23       | 1.07%   |
| Intel Ethernet Connection (2) I218-V                              | 23       | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19       | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 19       | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 19       | 0.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18       | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 18       | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16       | 0.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 15       | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15       | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14       | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14       | 0.65%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 14       | 0.65%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.56%   |
| Intel Ethernet Connection (14) I219-V                             | 12       | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 11       | 0.51%   |
| Huawei E353/E3131                                                 | 11       | 0.51%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 11       | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10       | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 10       | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.42%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9        | 0.42%   |
| Nvidia MCP55 Ethernet                                             | 8        | 0.37%   |
| Intel I210 Gigabit Network Connection                             | 8        | 0.37%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7        | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1913     | 69.95%  |
| WiFi     | 780      | 28.52%  |
| Modem    | 35       | 1.28%   |
| Unknown  | 7        | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1523     | 77.55%  |
| WiFi     | 438      | 22.3%   |
| Modem    | 2        | 0.1%    |
| Unknown  | 1        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1371     | 70.24%  |
| 2     | 495      | 25.36%  |
| 3     | 57       | 2.92%   |
| 0     | 12       | 0.61%   |
| 4     | 6        | 0.31%   |
| 5     | 5        | 0.26%   |
| 6     | 3        | 0.15%   |
| 17    | 1        | 0.05%   |
| 9     | 1        | 0.05%   |
| 7     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1814     | 93.22%  |
| Yes  | 132      | 6.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 179      | 33.71%  |
| Cambridge Silicon Radio         | 167      | 31.45%  |
| ASUSTek Computer                | 71       | 13.37%  |
| Realtek Semiconductor           | 21       | 3.95%   |
| Broadcom                        | 17       | 3.2%    |
| TP-Link                         | 13       | 2.45%   |
| Qualcomm Atheros Communications | 13       | 2.45%   |
| MediaTek                        | 11       | 2.07%   |
| Edimax Technology               | 6        | 1.13%   |
| Apple                           | 5        | 0.94%   |
| Realtek                         | 4        | 0.75%   |
| Integrated System Solution      | 4        | 0.75%   |
| Foxconn / Hon Hai               | 4        | 0.75%   |
| Lite-On Technology              | 3        | 0.56%   |
| IMC Networks                    | 3        | 0.56%   |
| Conwise Technology              | 3        | 0.56%   |
| Logitech                        | 2        | 0.38%   |
| Belkin Components               | 2        | 0.38%   |
| Unknown                         | 2        | 0.38%   |
| SINO WEALTH                     | 1        | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 167      | 31.33%  |
| Intel AX200 Bluetooth                                   | 60       | 11.26%  |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 49       | 9.19%   |
| Intel Bluetooth wireless interface                      | 26       | 4.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 23       | 4.32%   |
| Intel Wireless-AC 3168 Bluetooth                        | 21       | 3.94%   |
| Realtek Bluetooth Radio                                 | 19       | 3.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 18       | 3.38%   |
| Intel AX210 Bluetooth                                   | 17       | 3.19%   |
| TP-Link TP-Cdj+ UB5A Adapter                            | 13       | 2.44%   |
| ASUS ASUS USB-BT500                                     | 12       | 2.25%   |
| MediaTek Wireless_Device                                | 11       | 2.06%   |
| Intel AX201 Bluetooth                                   | 11       | 2.06%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 7        | 1.31%   |
| Realtek Bluetooth Radio                                 | 4        | 0.75%   |
| Broadcom HP Portable Bumble Bee                         | 4        | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 4        | 0.75%   |
| ASUS Qualcomm Bluetooth 4.1                             | 4        | 0.75%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 3        | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                       | 3        | 0.56%   |
| Edimax Bluetooth Adapter                                | 3        | 0.56%   |
| Conwise CW6622                                          | 3        | 0.56%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter        | 3        | 0.56%   |
| Broadcom BCM2045 Bluetooth                              | 3        | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 2        | 0.38%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 2        | 0.38%   |
| Lite-On Bluetooth Device                                | 2        | 0.38%   |
| Intel Bluetooth Device                                  | 2        | 0.38%   |
| IMC Networks Wireless_Device                            | 2        | 0.38%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2        | 0.38%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE   | 2        | 0.38%   |
| ASUS Bluetooth Radio                                    | 2        | 0.38%   |
| ASUS BCM20702A0                                         | 2        | 0.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 2        | 0.38%   |
| Unknown                                                 | 2        | 0.38%   |
| SINO WEALTH RK Bluetooth Keyboar                        | 1        | 0.19%   |
| Realtek Bluetooth 5.3 Radio                             | 1        | 0.19%   |
| Realtek Bluetooth 5.1 Radio                             | 1        | 0.19%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 0.19%   |
| Qualcomm Atheros AR9462 Bluetooth                       | 1        | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1136     | 34.25%  |
| AMD                                  | 872      | 26.29%  |
| Nvidia                               | 812      | 24.48%  |
| Creative Labs                        | 93       | 2.8%    |
| C-Media Electronics                  | 84       | 2.53%   |
| Creative Technology                  | 32       | 0.96%   |
| Logitech                             | 21       | 0.63%   |
| JMTek                                | 18       | 0.54%   |
| VIA Technologies                     | 17       | 0.51%   |
| Texas Instruments                    | 14       | 0.42%   |
| SteelSeries ApS                      | 14       | 0.42%   |
| Kingston Technology                  | 13       | 0.39%   |
| GYROCOM C&C                          | 11       | 0.33%   |
| Realtek Semiconductor                | 10       | 0.3%    |
| SAVITECH                             | 9        | 0.27%   |
| ASUSTek Computer                     | 9        | 0.27%   |
| Generalplus Technology               | 7        | 0.21%   |
| Razer USA                            | 6        | 0.18%   |
| Plantronics                          | 6        | 0.18%   |
| Dell                                 | 6        | 0.18%   |
| AOKEO                                | 6        | 0.18%   |
| Micro Star International             | 5        | 0.15%   |
| BEHRINGER International              | 5        | 0.15%   |
| Valve Software                       | 4        | 0.12%   |
| Trust                                | 4        | 0.12%   |
| Sony                                 | 4        | 0.12%   |
| GN Netcom                            | 4        | 0.12%   |
| Corsair                              | 4        | 0.12%   |
| Thesycon Systemsoftware & Consulting | 3        | 0.09%   |
| Stadium USB microphone               | 3        | 0.09%   |
| Samson Technologies                  | 3        | 0.09%   |
| RODE Microphones                     | 3        | 0.09%   |
| ROCCAT                               | 3        | 0.09%   |
| PreSonus Audio Electronics           | 3        | 0.09%   |
| M-Audio                              | 3        | 0.09%   |
| Focusrite-Novation                   | 3        | 0.09%   |
| AudioQuest                           | 3        | 0.09%   |
| XMOS                                 | 2        | 0.06%   |
| ULi Electronics                      | 2        | 0.06%   |
| Solid State System                   | 2        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 179      | 4.63%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 158      | 4.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 156      | 4.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 132      | 3.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 118      | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 117      | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 116      | 3%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 111      | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 104      | 2.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 103      | 2.67%   |
| AMD Family 17h/19h HD Audio Controller                                     | 88       | 2.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 78       | 2.02%   |
| AMD FCH Azalia Controller                                                  | 75       | 1.94%   |
| Intel 200 Series PCH HD Audio                                              | 72       | 1.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 68       | 1.76%   |
| Nvidia GP106 High Definition Audio Controller                              | 66       | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 64       | 1.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 55       | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 48       | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 47       | 1.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 46       | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                              | 45       | 1.16%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 45       | 1.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 44       | 1.14%   |
| Nvidia High Definition Audio Controller                                    | 43       | 1.11%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 43       | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                              | 42       | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 40       | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 39       | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 39       | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 35       | 0.91%   |
| Nvidia MCP61 High Definition Audio                                         | 33       | 0.85%   |
| Nvidia GP108 High Definition Audio Controller                              | 32       | 0.83%   |
| AMD Navi 10 HDMI Audio                                                     | 32       | 0.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 30       | 0.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 29       | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                              | 27       | 0.7%    |
| Nvidia GM204 High Definition Audio Controller                              | 26       | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                         | 26       | 0.67%   |
| Nvidia TU104 HD Audio Controller                                           | 25       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 260      | 18.91%  |
| Unknown                      | 259      | 18.84%  |
| Samsung Electronics          | 118      | 8.58%   |
| GOODRAM                      | 116      | 8.44%   |
| G.Skill                      | 109      | 7.93%   |
| SK hynix                     | 107      | 7.78%   |
| Corsair                      | 85       | 6.18%   |
| Crucial                      | 72       | 5.24%   |
| Micron Technology            | 41       | 2.98%   |
| Patriot                      | 38       | 2.76%   |
| A-DATA Technology            | 30       | 2.18%   |
| Nanya Technology             | 21       | 1.53%   |
| Elpida                       | 15       | 1.09%   |
| Unknown                      | 15       | 1.09%   |
| Wilk Elektronik              | 10       | 0.73%   |
| GeIL                         | 10       | 0.73%   |
| Apacer                       | 10       | 0.73%   |
| Wilk                         | 7        | 0.51%   |
| Unknown (ABCD)               | 5        | 0.36%   |
| Silicon Power                | 5        | 0.36%   |
| Ramaxel Technology           | 5        | 0.36%   |
| Patriot Memory (PDP Systems) | 4        | 0.29%   |
| Team                         | 3        | 0.22%   |
| Qimonda                      | 3        | 0.22%   |
| OCZ                          | 3        | 0.22%   |
| KingFast                     | 2        | 0.15%   |
| ASint Technology             | 2        | 0.15%   |
| AMD                          | 2        | 0.15%   |
| Unknown (A)                  | 1        | 0.07%   |
| Unknown (0x7FFF)             | 1        | 0.07%   |
| Unknown (0x0E9D)             | 1        | 0.07%   |
| Unifosa                      | 1        | 0.07%   |
| Transcend                    | 1        | 0.07%   |
| Toshiba                      | 1        | 0.07%   |
| tigo                         | 1        | 0.07%   |
| PUSKILL                      | 1        | 0.07%   |
| PNY                          | 1        | 0.07%   |
| Lexar Co Limited             | 1        | 0.07%   |
| Lexar                        | 1        | 0.07%   |
| Kingmax                      | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s  | 19       | 1.22%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 18       | 1.15%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s    | 17       | 1.09%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 15       | 0.96%   |
| Unknown                                                | 15       | 0.96%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 14       | 0.9%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 14       | 0.9%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 14       | 0.9%    |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 14       | 0.9%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 13       | 0.83%   |
| GOODRAM RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s     | 13       | 0.83%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 12       | 0.77%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1648MT/s    | 12       | 0.77%   |
| GOODRAM RAM GR1600D364L11/8G 8GB DIMM DDR3 1600MT/s    | 11       | 0.71%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 11       | 0.71%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 10       | 0.64%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 9        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 9        | 0.58%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 8        | 0.51%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 8        | 0.51%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 8        | 0.51%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 8        | 0.51%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s    | 8        | 0.51%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 7        | 0.45%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 7        | 0.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 7        | 0.45%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s | 7        | 0.45%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 7        | 0.45%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 7        | 0.45%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 7        | 0.45%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s  | 7        | 0.45%   |
| GOODRAM RAM IRX3000D464L16S/8G 8GB DIMM DDR4 3333MT/s  | 7        | 0.45%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 6        | 0.38%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 6        | 0.38%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 6        | 0.38%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 6        | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 6        | 0.38%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 6        | 0.38%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s  | 6        | 0.38%   |
| GOODRAM RAM IR2400D464L15S/8G 8GB DIMM DDR4 3200MT/s   | 6        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 489      | 39.95%  |
| DDR3    | 406      | 33.17%  |
| Unknown | 140      | 11.44%  |
| DDR2    | 73       | 5.96%   |
| SDRAM   | 66       | 5.39%   |
| DDR     | 23       | 1.88%   |
| DDR5    | 20       | 1.63%   |
| LPDDR4  | 6        | 0.49%   |
| DRAM    | 1        | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1145     | 95.34%  |
| SODIMM       | 52       | 4.33%   |
| RIMM         | 2        | 0.17%   |
| Row Of Chips | 1        | 0.08%   |
| FB-DIMM      | 1        | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 432      | 31.86%  |
| 4096   | 309      | 22.79%  |
| 2048   | 258      | 19.03%  |
| 16384  | 171      | 12.61%  |
| 1024   | 94       | 6.93%   |
| 32768  | 68       | 5.01%   |
| 512    | 19       | 1.4%    |
| 256    | 2        | 0.15%   |
| 131072 | 1        | 0.07%   |
| 1536   | 1        | 0.07%   |
| 64     | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 247      | 18.23%  |
| 1333    | 153      | 11.29%  |
| 3200    | 112      | 8.27%   |
| 3600    | 96       | 7.08%   |
| 800     | 91       | 6.72%   |
| 2400    | 69       | 5.09%   |
| 667     | 54       | 3.99%   |
| 2667    | 48       | 3.54%   |
| 2133    | 38       | 2.8%    |
| 3000    | 32       | 2.36%   |
| 1867    | 30       | 2.21%   |
| Unknown | 27       | 1.99%   |
| 3400    | 23       | 1.7%    |
| 3733    | 22       | 1.62%   |
| 1800    | 22       | 1.62%   |
| 1866    | 20       | 1.48%   |
| 3866    | 18       | 1.33%   |
| 2933    | 18       | 1.33%   |
| 2666    | 17       | 1.25%   |
| 400     | 17       | 1.25%   |
| 1067    | 16       | 1.18%   |
| 3800    | 15       | 1.11%   |
| 1066    | 15       | 1.11%   |
| 3533    | 11       | 0.81%   |
| 3333    | 10       | 0.74%   |
| 1334    | 9        | 0.66%   |
| 533     | 9        | 0.66%   |
| 2866    | 8        | 0.59%   |
| 3933    | 7        | 0.52%   |
| 333     | 7        | 0.52%   |
| 6000    | 6        | 0.44%   |
| 4800    | 6        | 0.44%   |
| 3466    | 6        | 0.44%   |
| 49926   | 5        | 0.37%   |
| 2000    | 5        | 0.37%   |
| 5808    | 4        | 0.3%    |
| 4000    | 4        | 0.3%    |
| 3334    | 4        | 0.3%    |
| 3266    | 4        | 0.3%    |
| 2800    | 4        | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 41       | 45.56%  |
| Brother Industries    | 13       | 14.44%  |
| Samsung Electronics   | 10       | 11.11%  |
| Canon                 | 7        | 7.78%   |
| Seiko Epson           | 6        | 6.67%   |
| Prolific Technology   | 5        | 5.56%   |
| Lexmark International | 3        | 3.33%   |
| Zebra                 | 2        | 2.22%   |
| Xerox                 | 1        | 1.11%   |
| Minolta               | 1        | 1.11%   |
| Datamax-O'Neil        | 1        | 1.11%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port          | 5        | 5.43%   |
| HP LaserJet 1020                       | 4        | 4.35%   |
| HP LaserJet P2015 series               | 3        | 3.26%   |
| HP LaserJet M14-M17                    | 3        | 3.26%   |
| Canon iP7200 series                    | 3        | 3.26%   |
| Seiko Epson L6270 Series               | 2        | 2.17%   |
| Samsung ML-216x Series Laser Printer   | 2        | 2.17%   |
| Samsung ML-2010P Mono Laser Printer    | 2        | 2.17%   |
| HP Deskjet F4500 series                | 2        | 2.17%   |
| HP DeskJet F4100 Printer series        | 2        | 2.17%   |
| HP DeskJet 845c                        | 2        | 2.17%   |
| HP DeskJet 840c                        | 2        | 2.17%   |
| HP DeskJet 4530 series                 | 2        | 2.17%   |
| HP DeskJet 3700 series                 | 2        | 2.17%   |
| HP Deskjet 1050 J410                   | 2        | 2.17%   |
| Brother DCP-J105                       | 2        | 2.17%   |
| Zebra LP2844 Printer                   | 1        | 1.09%   |
| Zebra LP2824                           | 1        | 1.09%   |
| Xerox WorkCentre PE16                  | 1        | 1.09%   |
| Seiko Epson Stylus NX230/SX235W Series | 1        | 1.09%   |
| Seiko Epson L405 Series                | 1        | 1.09%   |
| Seiko Epson L3150 Series               | 1        | 1.09%   |
| Seiko Epson L1110 Series               | 1        | 1.09%   |
| Samsung SCX-4300 Series                | 1        | 1.09%   |
| Samsung SCX-4200 series                | 1        | 1.09%   |
| Samsung SCX-3400 Series                | 1        | 1.09%   |
| Samsung ML-3050/ML-3051 Laser Printer  | 1        | 1.09%   |
| Samsung ML-2540 Series Laser Printer   | 1        | 1.09%   |
| Samsung M2020 Series                   | 1        | 1.09%   |
| Minolta PagePro 1200W                  | 1        | 1.09%   |
| Lexmark International MS415dn          | 1        | 1.09%   |
| Lexmark International Lexmark E352dn   | 1        | 1.09%   |
| Lexmark International B2236dw          | 1        | 1.09%   |
| HP Smart Tank 510 series               | 1        | 1.09%   |
| HP PSC 1100 series                     | 1        | 1.09%   |
| HP Printing Support                    | 1        | 1.09%   |
| HP LaserJet P2055 series               | 1        | 1.09%   |
| HP LaserJet P1102                      | 1        | 1.09%   |
| HP LaserJet M101-M106                  | 1        | 1.09%   |
| HP LaserJet CM1415fnw                  | 1        | 1.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 10       | 62.5%   |
| Seiko Epson                 | 2        | 12.5%   |
| Ultima Electronics          | 1        | 6.25%   |
| Plustek                     | 1        | 6.25%   |
| Mustek Systems              | 1        | 6.25%   |
| Acer Peripherals (now BenQ) | 1        | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 5        | 31.25%  |
| Canon CanoScan LiDE 120                                  | 2        | 12.5%   |
| Ultima Artec E+ 48U                                      | 1        | 6.25%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1        | 6.25%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 6.25%   |
| Plustek OpticPro 1248U Scanner #2                        | 1        | 6.25%   |
| Mustek Systems BearPaw 2448 TA Pro                       | 1        | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 6.25%   |
| Canon CanoScan LIDE 25                                   | 1        | 6.25%   |
| Canon CanoScan LiDE 110                                  | 1        | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 87       | 32.1%   |
| Microdia                               | 33       | 12.18%  |
| Creative Technology                    | 28       | 10.33%  |
| Samsung Electronics                    | 16       | 5.9%    |
| Microsoft                              | 16       | 5.9%    |
| Z-Star Microelectronics                | 8        | 2.95%   |
| Jieli Technology                       | 7        | 2.58%   |
| Sunplus Innovation Technology          | 6        | 2.21%   |
| Hewlett-Packard                        | 6        | 2.21%   |
| Cubeternet                             | 6        | 2.21%   |
| Generalplus Technology                 | 5        | 1.85%   |
| Aveo Technology                        | 4        | 1.48%   |
| Xiongmai                               | 3        | 1.11%   |
| Trust                                  | 3        | 1.11%   |
| Realtek Semiconductor                  | 3        | 1.11%   |
| Razer USA                              | 3        | 1.11%   |
| GEMBIRD                                | 3        | 1.11%   |
| Chicony Electronics                    | 3        | 1.11%   |
| Apple                                  | 3        | 1.11%   |
| Alcor Micro                            | 3        | 1.11%   |
| Valve Software                         | 2        | 0.74%   |
| Pixart Imaging                         | 2        | 0.74%   |
| MacroSilicon                           | 2        | 0.74%   |
| LG Electronics                         | 2        | 0.74%   |
| KYE Systems (Mouse Systems)            | 2        | 0.74%   |
| ARC International                      | 2        | 0.74%   |
| USB3.0 HD Audio Capture                | 1        | 0.37%   |
| OPPO Electronics                       | 1        | 0.37%   |
| Lenovo                                 | 1        | 0.37%   |
| Huawei Technologies                    | 1        | 0.37%   |
| HRY                                    | 1        | 0.37%   |
| Google                                 | 1        | 0.37%   |
| Etron Technology                       | 1        | 0.37%   |
| DigitalPersona                         | 1        | 0.37%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.37%   |
| Bison Electronics                      | 1        | 0.37%   |
| Asuscom Network                        | 1        | 0.37%   |
| Arkmicro Technologies                  | 1        | 0.37%   |
| Unknown                                | 1        | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 21       | 7.69%   |
| Samsung Galaxy series, misc. (MTP mode)           | 15       | 5.49%   |
| Creative Live! Cam Sync HD [VF0770]               | 13       | 4.76%   |
| Microdia USB 2.0 Camera                           | 12       | 4.4%    |
| Logitech HD Pro Webcam C920                       | 11       | 4.03%   |
| Logitech Webcam C310                              | 9        | 3.3%    |
| Logitech Webcam C170                              | 9        | 3.3%    |
| Jieli USB PHY 2.0                                 | 7        | 2.56%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 2.2%    |
| Microsoft LifeCam HD-3000                         | 5        | 1.83%   |
| Microdia Integrated Camera                        | 5        | 1.83%   |
| Microdia USB Camera                               | 4        | 1.47%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 1.47%   |
| HP Webcam HD 2300                                 | 4        | 1.47%   |
| Generalplus GENERAL WEBCAM                        | 4        | 1.47%   |
| Cubeternet USB2.0 Camera                          | 4        | 1.47%   |
| Creative Live! Cam Sync 1080p                     | 4        | 1.47%   |
| Xiongmai web camera                               | 3        | 1.1%    |
| Sunplus HD 720P webcam                            | 3        | 1.1%    |
| Razer USA Gaming Webcam [Kiyo]                    | 3        | 1.1%    |
| Microsoft LifeCam NX-6000                         | 3        | 1.1%    |
| Microdia Webcam Vitade AF                         | 3        | 1.1%    |
| Microdia Camera                                   | 3        | 1.1%    |
| Logitech Webcam C930e                             | 3        | 1.1%    |
| Logitech Webcam C120                              | 3        | 1.1%    |
| Logitech C922 Pro Stream Webcam                   | 3        | 1.1%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 3        | 1.1%    |
| Creative Live! Cam Optia                          | 3        | 1.1%    |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 3        | 1.1%    |
| Aveo USB2.0 Camera                                | 3        | 1.1%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 3        | 1.1%    |
| Valve Software 3D Camera                          | 2        | 0.73%   |
| Trust USB Camera                                  | 2        | 0.73%   |
| Sunplus FHD Camera Microphone                     | 2        | 0.73%   |
| Realtek Thronmax Webcam Mic                       | 2        | 0.73%   |
| Realtek Thronmax StreamGo Webcam                  | 2        | 0.73%   |
| Pixart Imaging USB2.0_Camera                      | 2        | 0.73%   |
| Microsoft LifeCam VX-500 [1357]                   | 2        | 0.73%   |
| Microsoft LifeCam HD-5000                         | 2        | 0.73%   |
| MacroSilicon USB Video                            | 2        | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Synaptics                  | 2        | 33.33%  |
| STMicroelectronics         | 1        | 16.67%  |
| Shenzhen Goodix Technology | 1        | 16.67%  |
| Elan Microelectronics      | 1        | 16.67%  |
| AuthenTec                  | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 33.33%  |
| STMicroelectronics Fingerprint Reader        | 1        | 16.67%  |
| Shenzhen Goodix  FingerPrint Device          | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200]  | 1        | 16.67%  |
| AuthenTec AES1600                            | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| OmniKey                  | 3        | 23.08%  |
| Advanced Card Systems    | 3        | 23.08%  |
| Cherry                   | 2        | 15.38%  |
| SCM Microsystems         | 1        | 7.69%   |
| Reiner SCT Kartensysteme | 1        | 7.69%   |
| Gemalto (was Gemplus)    | 1        | 7.69%   |
| Clay Logic               | 1        | 7.69%   |
| Alcor Micro              | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                                                | 2        | 15.38%  |
| Advanced Card Systems ACR39U                                               | 2        | 15.38%  |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 7.69%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 7.69%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 7.69%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 7.69%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 7.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 7.69%   |
| Cherry Smart Terminal XX44                                                 | 1        | 7.69%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 7.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1671     | 84.01%  |
| 1     | 275      | 13.83%  |
| 2     | 31       | 1.56%   |
| 3     | 6        | 0.3%    |
| 4     | 3        | 0.15%   |
| 7     | 1        | 0.05%   |
| 6     | 1        | 0.05%   |
| 5     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 143      | 40.28%  |
| Net/wireless             | 71       | 20%     |
| Unassigned class         | 27       | 7.61%   |
| Communication controller | 24       | 6.76%   |
| Multimedia controller    | 15       | 4.23%   |
| Sound                    | 12       | 3.38%   |
| Bluetooth                | 11       | 3.1%    |
| Camera                   | 8        | 2.25%   |
| Network                  | 7        | 1.97%   |
| Net/ethernet             | 6        | 1.69%   |
| Fingerprint reader       | 6        | 1.69%   |
| Chipcard                 | 6        | 1.69%   |
| Storage/ide              | 5        | 1.41%   |
| Storage/raid             | 3        | 0.85%   |
| Firewire controller      | 3        | 0.85%   |
| Dvb card                 | 3        | 0.85%   |
| Storage                  | 2        | 0.56%   |
| Modem                    | 2        | 0.56%   |
| Storage/nvme             | 1        | 0.28%   |

