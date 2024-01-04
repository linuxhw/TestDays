Linux in Mexico - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

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

Total: 1276

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 8054                        | [5389720de6](https://linux-hardware.org/?probe=5389720de6) | Dec 31, 2023 |
| Acer          | Aspire XC-704               | [37410da8b1](https://linux-hardware.org/?probe=37410da8b1) | Dec 29, 2023 |
| ASUSTek       | H81M-A                      | [1676225992](https://linux-hardware.org/?probe=1676225992) | Dec 28, 2023 |
| NZXT          | N7 B550                     | [2ce2b46a02](https://linux-hardware.org/?probe=2ce2b46a02) | Dec 27, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [370753e882](https://linux-hardware.org/?probe=370753e882) | Dec 27, 2023 |
| ASUSTek       | PRIME A520M-A II            | [c37a18c186](https://linux-hardware.org/?probe=c37a18c186) | Dec 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [a2d218ac1b](https://linux-hardware.org/?probe=a2d218ac1b) | Dec 24, 2023 |
| HP            | 2ABA A01                    | [dbee4787fa](https://linux-hardware.org/?probe=dbee4787fa) | Dec 24, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [119a1632aa](https://linux-hardware.org/?probe=119a1632aa) | Dec 21, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [64131ee7e0](https://linux-hardware.org/?probe=64131ee7e0) | Dec 21, 2023 |
| Dell          | 0C522T A03                  | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| HP            | 1905                        | [540abb14df](https://linux-hardware.org/?probe=540abb14df) | Dec 20, 2023 |
| ASUSTek       | H110M-R                     | [ca0eab5d48](https://linux-hardware.org/?probe=ca0eab5d48) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [19af9254cb](https://linux-hardware.org/?probe=19af9254cb) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [5881287b44](https://linux-hardware.org/?probe=5881287b44) | Dec 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7383998676](https://linux-hardware.org/?probe=7383998676) | Dec 18, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39c5fad7d0](https://linux-hardware.org/?probe=39c5fad7d0) | Dec 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [d3ff600405](https://linux-hardware.org/?probe=d3ff600405) | Dec 17, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | [1381c72872](https://linux-hardware.org/?probe=1381c72872) | Dec 11, 2023 |
| Dell          | 0C522T A03                  | [11f857231b](https://linux-hardware.org/?probe=11f857231b) | Dec 10, 2023 |
| Gigabyte      | H310M DS2 x.x               | [6150f23143](https://linux-hardware.org/?probe=6150f23143) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | [d49b26fe0c](https://linux-hardware.org/?probe=d49b26fe0c) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | [f8bd255155](https://linux-hardware.org/?probe=f8bd255155) | Dec 09, 2023 |
| Lenovo        | ThinkCentre M58 7359AW5     | [71d7e25b16](https://linux-hardware.org/?probe=71d7e25b16) | Dec 09, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [9b36560b08](https://linux-hardware.org/?probe=9b36560b08) | Dec 06, 2023 |
| HP            | 8054                        | [d5e57e23bb](https://linux-hardware.org/?probe=d5e57e23bb) | Dec 06, 2023 |
| NEC Infron... | MS-9888 10h                 | [8a1a2b9976](https://linux-hardware.org/?probe=8a1a2b9976) | Dec 05, 2023 |
| ASUSTek       | PRIME A520M-A II            | [a2e7a10bdf](https://linux-hardware.org/?probe=a2e7a10bdf) | Dec 05, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b4efc55410](https://linux-hardware.org/?probe=b4efc55410) | Dec 05, 2023 |
| Lenovo        | Bantry CRB SDK0E50515 ST... | [09d4a641d9](https://linux-hardware.org/?probe=09d4a641d9) | Dec 04, 2023 |
| Gigabyte      | GA-880GM-USB3               | [f4078eb310](https://linux-hardware.org/?probe=f4078eb310) | Dec 04, 2023 |
| HP            | 0AECh D                     | [2a30f0332a](https://linux-hardware.org/?probe=2a30f0332a) | Dec 04, 2023 |
| HP            | 0AECh D                     | [689f0d6876](https://linux-hardware.org/?probe=689f0d6876) | Dec 04, 2023 |
| Gigabyte      | Z77X-UD5H                   | [4cb46d807d](https://linux-hardware.org/?probe=4cb46d807d) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | [0c74d4b343](https://linux-hardware.org/?probe=0c74d4b343) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [d87ba8d291](https://linux-hardware.org/?probe=d87ba8d291) | Nov 29, 2023 |
| HP            | 859B                        | [fd70c499d1](https://linux-hardware.org/?probe=fd70c499d1) | Nov 28, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [dd98dacf94](https://linux-hardware.org/?probe=dd98dacf94) | Nov 28, 2023 |
| Unknown       | Unknown                     | [beca2cade6](https://linux-hardware.org/?probe=beca2cade6) | Nov 26, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [4b2a2cc667](https://linux-hardware.org/?probe=4b2a2cc667) | Nov 23, 2023 |
| Unknown       | Unknown                     | [f90c57452a](https://linux-hardware.org/?probe=f90c57452a) | Nov 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [928f91a2f4](https://linux-hardware.org/?probe=928f91a2f4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | [508c867ae8](https://linux-hardware.org/?probe=508c867ae8) | Nov 20, 2023 |
| Unknown       | Unknown                     | [dc2ca2e65b](https://linux-hardware.org/?probe=dc2ca2e65b) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e5d2cc7fcd](https://linux-hardware.org/?probe=e5d2cc7fcd) | Nov 19, 2023 |
| Gigabyte      | B360HD3                     | [281c4b4ac5](https://linux-hardware.org/?probe=281c4b4ac5) | Nov 18, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [496e69e1e4](https://linux-hardware.org/?probe=496e69e1e4) | Nov 16, 2023 |
| HP            | 1408h                       | [b39e21e12c](https://linux-hardware.org/?probe=b39e21e12c) | Nov 15, 2023 |
| HP            | 1408h                       | [0eafe0e468](https://linux-hardware.org/?probe=0eafe0e468) | Nov 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [c5f890cb08](https://linux-hardware.org/?probe=c5f890cb08) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | [c505d16c82](https://linux-hardware.org/?probe=c505d16c82) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | [e0349fcb14](https://linux-hardware.org/?probe=e0349fcb14) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | [f7a8d7d27e](https://linux-hardware.org/?probe=f7a8d7d27e) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | [149bf90d88](https://linux-hardware.org/?probe=149bf90d88) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [1b4972f4e1](https://linux-hardware.org/?probe=1b4972f4e1) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [7d0e39fe9f](https://linux-hardware.org/?probe=7d0e39fe9f) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 09F0h                       | [1c1ab6c56f](https://linux-hardware.org/?probe=1c1ab6c56f) | Nov 12, 2023 |
| Intel         | H61 V1.5                    | [798841e126](https://linux-hardware.org/?probe=798841e126) | Nov 12, 2023 |
| Dell          | 018D1Y A00                  | [4a14d46e6b](https://linux-hardware.org/?probe=4a14d46e6b) | Nov 12, 2023 |
| AZW           | GTR V21                     | [8c7e39a466](https://linux-hardware.org/?probe=8c7e39a466) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e086a0153d](https://linux-hardware.org/?probe=e086a0153d) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d49ee32dd4](https://linux-hardware.org/?probe=d49ee32dd4) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [c2d982c2dd](https://linux-hardware.org/?probe=c2d982c2dd) | Nov 10, 2023 |
| Dell          | 0YJMC0 A02                  | [7a1de78213](https://linux-hardware.org/?probe=7a1de78213) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | [57fb2a4f18](https://linux-hardware.org/?probe=57fb2a4f18) | Nov 08, 2023 |
| HP            | 8184 X4                     | [fb7f295b44](https://linux-hardware.org/?probe=fb7f295b44) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Gigabyte      | F2A68HM-H                   | [607a31a8ef](https://linux-hardware.org/?probe=607a31a8ef) | Oct 27, 2023 |
| ASUSTek       | Leonite2                    | [f2ac570d7b](https://linux-hardware.org/?probe=f2ac570d7b) | Oct 25, 2023 |
| Lenovo        | MAHOBAY NOK                 | [5936f87a0e](https://linux-hardware.org/?probe=5936f87a0e) | Oct 23, 2023 |
| HP            | 83EF                        | [9a8026df67](https://linux-hardware.org/?probe=9a8026df67) | Oct 23, 2023 |
| AZW           | SER V1                      | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [1303e88b7c](https://linux-hardware.org/?probe=1303e88b7c) | Oct 21, 2023 |
| Biostar       | B450MH                      | [cc72642215](https://linux-hardware.org/?probe=cc72642215) | Oct 20, 2023 |
| HP            | 2B29                        | [70d4194832](https://linux-hardware.org/?probe=70d4194832) | Oct 18, 2023 |
| HP            | 2B29                        | [b4da4bf11d](https://linux-hardware.org/?probe=b4da4bf11d) | Oct 18, 2023 |
| AZW           | SER V1                      | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| Unknown       | Intel X79                   | [d2553e6cbd](https://linux-hardware.org/?probe=d2553e6cbd) | Oct 17, 2023 |
| Unknown       | Unknown                     | [172cfdcd26](https://linux-hardware.org/?probe=172cfdcd26) | Oct 16, 2023 |
| HP            | 339A                        | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| HP            | 8714                        | [1379aae868](https://linux-hardware.org/?probe=1379aae868) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [904d65b1c0](https://linux-hardware.org/?probe=904d65b1c0) | Oct 11, 2023 |
| ASUSTek       | H81M-A                      | [38a83d68e5](https://linux-hardware.org/?probe=38a83d68e5) | Oct 09, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [d97f4b5e6f](https://linux-hardware.org/?probe=d97f4b5e6f) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | [fd663ca7fa](https://linux-hardware.org/?probe=fd663ca7fa) | Oct 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [2d73d7e286](https://linux-hardware.org/?probe=2d73d7e286) | Oct 06, 2023 |
| Gigabyte      | H81M-H                      | [97dca67f82](https://linux-hardware.org/?probe=97dca67f82) | Oct 06, 2023 |
| Pegatron      | Benicia                     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| PCChips       | A51G                        | [307e9880cb](https://linux-hardware.org/?probe=307e9880cb) | Oct 03, 2023 |
| PCChips       | A51G                        | [da68aae4b8](https://linux-hardware.org/?probe=da68aae4b8) | Oct 03, 2023 |
| ASUSTek       | PRIME A320M-K               | [cacc534be7](https://linux-hardware.org/?probe=cacc534be7) | Oct 02, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| ASUSTek       | Z170-A                      | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Pegatron      | Benicia                     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M PRO-M2 MAX            | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [312172129f](https://linux-hardware.org/?probe=312172129f) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| ASRock        | H55M-LE                     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| ECS           | VX900-I                     | [0a69c91f6b](https://linux-hardware.org/?probe=0a69c91f6b) | Sep 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b4dcc89eae](https://linux-hardware.org/?probe=b4dcc89eae) | Sep 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c424e240c8](https://linux-hardware.org/?probe=c424e240c8) | Sep 15, 2023 |
| Gigabyte      | A55M-DS2                    | [6bc7d0b74c](https://linux-hardware.org/?probe=6bc7d0b74c) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| ASUSTek       | Leonite2                    | [6e387e015f](https://linux-hardware.org/?probe=6e387e015f) | Sep 13, 2023 |
| Dell          | 05XGC8 A01                  | [c09c04e44a](https://linux-hardware.org/?probe=c09c04e44a) | Sep 12, 2023 |
| Dell          | 0782GW A00                  | [e763eb02b7](https://linux-hardware.org/?probe=e763eb02b7) | Sep 10, 2023 |
| Intel         | DX58SO AAE29331-501         | [26d87ed353](https://linux-hardware.org/?probe=26d87ed353) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [c5f5d76ac5](https://linux-hardware.org/?probe=c5f5d76ac5) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [8a48280ff2](https://linux-hardware.org/?probe=8a48280ff2) | Sep 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Unknown       | Unknown                     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| Unknown       | Unknown                     | [c4829899c3](https://linux-hardware.org/?probe=c4829899c3) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Dell          | 0Y2MRG A00                  | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Dell          | 0GWHMW A00                  | [b02b2cb5f0](https://linux-hardware.org/?probe=b02b2cb5f0) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| eMachines     | EL1852G                     | [e9234028f1](https://linux-hardware.org/?probe=e9234028f1) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Biostar       | A10N-9630E                  | [823a9c1693](https://linux-hardware.org/?probe=823a9c1693) | Sep 03, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| HP            | 2215                        | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| HP            | 1587h                       | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| MSI           | Boston                      | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| Gigabyte      | H410M H V3                  | [3032b93bc8](https://linux-hardware.org/?probe=3032b93bc8) | Aug 30, 2023 |
| Dell          | 0D28YY A00                  | [9f2585c0aa](https://linux-hardware.org/?probe=9f2585c0aa) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [c3065668c8](https://linux-hardware.org/?probe=c3065668c8) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [3c4c019ee5](https://linux-hardware.org/?probe=3c4c019ee5) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| Dell          | 0HR330                      | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| Unknown       | Unknown                     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| Dell          | 0M017G A00                  | [f5e52dc9f9](https://linux-hardware.org/?probe=f5e52dc9f9) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Gigabyte      | H310M H x.x                 | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| GMKtec        | NucBox K2                   | [3cc85b0145](https://linux-hardware.org/?probe=3cc85b0145) | Aug 22, 2023 |
| HP            | 18E7                        | [49957c261d](https://linux-hardware.org/?probe=49957c261d) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| MSI           | A520M-A PRO                 | [277050ce29](https://linux-hardware.org/?probe=277050ce29) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | [3c24c755d6](https://linux-hardware.org/?probe=3c24c755d6) | Aug 20, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [455882ed8d](https://linux-hardware.org/?probe=455882ed8d) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| Dell          | 0M017G A00                  | [d480387600](https://linux-hardware.org/?probe=d480387600) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| ASUSTek       | Leonite2                    | [439a4ee1fb](https://linux-hardware.org/?probe=439a4ee1fb) | Aug 15, 2023 |
| Gigabyte      | AX370-Gaming 5              | [0bd04d6cc0](https://linux-hardware.org/?probe=0bd04d6cc0) | Aug 15, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| HP            | 0A04h                       | [61b0d9bc15](https://linux-hardware.org/?probe=61b0d9bc15) | Aug 12, 2023 |
| Lenovo        | IdeaCentre B320             | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Biostar       | A10N-8800E                  | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Dell          | 0MGK50 A01                  | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| Lenovo        | 30C1                        | [dda7ed4e8b](https://linux-hardware.org/?probe=dda7ed4e8b) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| MSI           | B350 GAMING PLUS            | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| ASUSTek       | PRIME H410M-E               | [8618a7051f](https://linux-hardware.org/?probe=8618a7051f) | Aug 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [197a9b0139](https://linux-hardware.org/?probe=197a9b0139) | Aug 03, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Dell          | 0D8M0M A00                  | [3ac6740883](https://linux-hardware.org/?probe=3ac6740883) | Jul 31, 2023 |
| Dell          | 0RF705                      | [9370437c75](https://linux-hardware.org/?probe=9370437c75) | Jul 30, 2023 |
| Dell          | 0RF705                      | [fe3118bd3c](https://linux-hardware.org/?probe=fe3118bd3c) | Jul 30, 2023 |
| Biostar       | A320MH                      | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HP            | 0A04h                       | [aaf7bb9453](https://linux-hardware.org/?probe=aaf7bb9453) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [156d74ec26](https://linux-hardware.org/?probe=156d74ec26) | Jul 24, 2023 |
| Biostar       | A68MDE                      | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Dell          | 0F373D A00                  | [fd337bb7ab](https://linux-hardware.org/?probe=fd337bb7ab) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | [026854a02c](https://linux-hardware.org/?probe=026854a02c) | Jul 23, 2023 |
| HP            | 18E7                        | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| MSI           | Boston                      | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 805A                        | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [7e1752f29c](https://linux-hardware.org/?probe=7e1752f29c) | Jul 14, 2023 |
| Dell          | 0D28YY A00                  | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| Dell          | 04Y8V0 A02                  | [b1b3d1eedc](https://linux-hardware.org/?probe=b1b3d1eedc) | Jul 10, 2023 |
| ASRock        | N68-VS3 FX                  | [9934022e9b](https://linux-hardware.org/?probe=9934022e9b) | Jul 09, 2023 |
| ECS           | A790GXM-AD3                 | [d88aa3d8d1](https://linux-hardware.org/?probe=d88aa3d8d1) | Jul 09, 2023 |
| HP            | 895C                        | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Dell          | 0MWYPT A02                  | [bbfc788fae](https://linux-hardware.org/?probe=bbfc788fae) | Jul 05, 2023 |
| Gigabyte      | AX370-Gaming 5              | [5e07b39a67](https://linux-hardware.org/?probe=5e07b39a67) | Jul 04, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| PCChips       | P17G ECS                    | [c1181f8ae7](https://linux-hardware.org/?probe=c1181f8ae7) | Jul 01, 2023 |
| Dell          | 0YXT71 A00                  | [031599c8b1](https://linux-hardware.org/?probe=031599c8b1) | Jul 01, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2f50312c02](https://linux-hardware.org/?probe=2f50312c02) | Jun 29, 2023 |
| HP            | 339A                        | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Dell          | 00V62H A01                  | [2e654ead73](https://linux-hardware.org/?probe=2e654ead73) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | [2ebfd9c347](https://linux-hardware.org/?probe=2ebfd9c347) | Jun 21, 2023 |
| Gigabyte      | GA-E350N                    | [dc5ab95b15](https://linux-hardware.org/?probe=dc5ab95b15) | Jun 19, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| MSI           | B360M PRO-VH                | [e628906fc2](https://linux-hardware.org/?probe=e628906fc2) | Jun 16, 2023 |
| ASUSTek       | Maximus VI HERO             | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| MSI           | PRO B660M-A DDR4            | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| Dell          | 0YXT71 A00                  | [477afe615b](https://linux-hardware.org/?probe=477afe615b) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | [463dfa5d83](https://linux-hardware.org/?probe=463dfa5d83) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| ASUSTek       | Maximus VI HERO             | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| MSI           | Boston                      | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| Gigabyte      | GA-E6010N                   | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| TPV-INVENT... | 2AC6 A01                    | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| Gigabyte      | H410M H V3                  | [f23e90acce](https://linux-hardware.org/?probe=f23e90acce) | May 30, 2023 |
| Biostar       | H310MHP                     | [7bfe35481d](https://linux-hardware.org/?probe=7bfe35481d) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| Biostar       | H310MHP                     | [7138f287c8](https://linux-hardware.org/?probe=7138f287c8) | May 29, 2023 |
| Pegatron      | 2ACB                        | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| ASUSTek       | H81M-A                      | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| PCChips       | P17G ECS                    | [0518fce589](https://linux-hardware.org/?probe=0518fce589) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Biostar       | A10N-8800E                  | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| HP            | 1497                        | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 1497                        | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| HP            | 895C                        | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Gigabyte      | G41MT-S2P                   | [edfd6dd6d9](https://linux-hardware.org/?probe=edfd6dd6d9) | May 24, 2023 |
| Gigabyte      | G41MT-S2P                   | [43cf78743a](https://linux-hardware.org/?probe=43cf78743a) | May 24, 2023 |
| Pegatron      | 2ACB                        | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| ASRock        | H55M-LE                     | [e31e211aa2](https://linux-hardware.org/?probe=e31e211aa2) | May 13, 2023 |
| ASRock        | H55M-LE                     | [8f2f79fb45](https://linux-hardware.org/?probe=8f2f79fb45) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HP            | 0A58h                       | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Biostar       | B450MH                      | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| Biostar       | B450MH                      | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| Gigabyte      | H410M H                     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| Dell          | 0D6H9T A00                  | [0e46a82cca](https://linux-hardware.org/?probe=0e46a82cca) | May 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [c2b7a8dbe1](https://linux-hardware.org/?probe=c2b7a8dbe1) | May 01, 2023 |
| Gigabyte      | H410M H                     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Biostar       | A10N-9630E                  | [e9df412284](https://linux-hardware.org/?probe=e9df412284) | Apr 28, 2023 |
| ASUSTek       | PRIME A320M-K               | [155ce08a00](https://linux-hardware.org/?probe=155ce08a00) | Apr 27, 2023 |
| ASUSTek       | AM1M-A                      | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| Dell          | 0WR7PY A01                  | [6eeb692185](https://linux-hardware.org/?probe=6eeb692185) | Apr 25, 2023 |
| HP            | 805D                        | [091e90cae0](https://linux-hardware.org/?probe=091e90cae0) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | [9f5177c657](https://linux-hardware.org/?probe=9f5177c657) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | [e263516539](https://linux-hardware.org/?probe=e263516539) | Apr 23, 2023 |
| ASUSTek       | PRIME A320M-K               | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| Dell          | 0HR330                      | [1619f09258](https://linux-hardware.org/?probe=1619f09258) | Apr 19, 2023 |
| Intel         | DZ68DB AAG27985-105         | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| Gigabyte      | GA-IMB410TN                 | [44293ba6b9](https://linux-hardware.org/?probe=44293ba6b9) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | [983906ed11](https://linux-hardware.org/?probe=983906ed11) | Apr 17, 2023 |
| HP            | 1850                        | [9ba17e1d9c](https://linux-hardware.org/?probe=9ba17e1d9c) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| HP            | 1850                        | [d30cea781b](https://linux-hardware.org/?probe=d30cea781b) | Apr 15, 2023 |
| Dell          | 0HR330                      | [4fd4f887bd](https://linux-hardware.org/?probe=4fd4f887bd) | Apr 14, 2023 |
| HP            | 1589                        | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| eMachines     | EL1852G                     | [e99e4b1fac](https://linux-hardware.org/?probe=e99e4b1fac) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| ASRock        | X570 Pro4                   | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| eMachines     | EL1852G                     | [e9dde876e9](https://linux-hardware.org/?probe=e9dde876e9) | Apr 08, 2023 |
| HP            | 895C                        | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| HP            | 895C                        | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| HP            | 1850                        | [04243d9db8](https://linux-hardware.org/?probe=04243d9db8) | Apr 03, 2023 |
| HP            | 1850                        | [62b8f8056b](https://linux-hardware.org/?probe=62b8f8056b) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a225e27910](https://linux-hardware.org/?probe=a225e27910) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [2cc7a15de5](https://linux-hardware.org/?probe=2cc7a15de5) | Apr 01, 2023 |
| Gigabyte      | B550M DS3H AC               | [f8e723a8dc](https://linux-hardware.org/?probe=f8e723a8dc) | Mar 31, 2023 |
| Gigabyte      | B460M AORUS ELITE           | [87145cd4b2](https://linux-hardware.org/?probe=87145cd4b2) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| Dell          | 073MMW A02                  | [311057a095](https://linux-hardware.org/?probe=311057a095) | Mar 28, 2023 |
| Gigabyte      | H410M H V3                  | [c47ec8c99a](https://linux-hardware.org/?probe=c47ec8c99a) | Mar 26, 2023 |
| Biostar       | A10N-9630E                  | [46af7d1f6d](https://linux-hardware.org/?probe=46af7d1f6d) | Mar 25, 2023 |
| Gigabyte      | GA-880GM-USB3               | [e6219dd355](https://linux-hardware.org/?probe=e6219dd355) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [7ccc7e9ae1](https://linux-hardware.org/?probe=7ccc7e9ae1) | Mar 21, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [4544e68d4a](https://linux-hardware.org/?probe=4544e68d4a) | Mar 21, 2023 |
| ASUSTek       | PRIME X570-P                | [417d3cf9b7](https://linux-hardware.org/?probe=417d3cf9b7) | Mar 19, 2023 |
| Biostar       | A10N-9630E                  | [a38995d817](https://linux-hardware.org/?probe=a38995d817) | Mar 18, 2023 |
| ASUSTek       | P5QPL-AM                    | [2e94546c02](https://linux-hardware.org/?probe=2e94546c02) | Mar 11, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [c81f97ee71](https://linux-hardware.org/?probe=c81f97ee71) | Mar 09, 2023 |
| Dell          | 0HR330                      | [314bd7b2be](https://linux-hardware.org/?probe=314bd7b2be) | Mar 08, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | [a56b16b410](https://linux-hardware.org/?probe=a56b16b410) | Mar 08, 2023 |
| Dell          | 0HR330                      | [a652a631f1](https://linux-hardware.org/?probe=a652a631f1) | Mar 08, 2023 |
| Dell          | 0VRWRC A00                  | [4810cd01e3](https://linux-hardware.org/?probe=4810cd01e3) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [f163816260](https://linux-hardware.org/?probe=f163816260) | Mar 04, 2023 |
| Biostar       | A10N-9630E                  | [e1bd95af21](https://linux-hardware.org/?probe=e1bd95af21) | Mar 03, 2023 |
| Dell          | 073MMW A02                  | [5915c17b3a](https://linux-hardware.org/?probe=5915c17b3a) | Mar 01, 2023 |
| Dell          | 073MMW A02                  | [e3ba0ef4b7](https://linux-hardware.org/?probe=e3ba0ef4b7) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | Z97M-D3H                    | [d93d9bff7f](https://linux-hardware.org/?probe=d93d9bff7f) | Feb 27, 2023 |
| Dell          | 0HR330                      | [9110acd156](https://linux-hardware.org/?probe=9110acd156) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [8a2a361aff](https://linux-hardware.org/?probe=8a2a361aff) | Feb 26, 2023 |
| Quanta        | 2AC7 011                    | [3505fadb68](https://linux-hardware.org/?probe=3505fadb68) | Feb 25, 2023 |
| Acer          | Aspire X3990                | [c83e31d66b](https://linux-hardware.org/?probe=c83e31d66b) | Feb 25, 2023 |
| Acer          | Aspire X3990                | [4be9f68049](https://linux-hardware.org/?probe=4be9f68049) | Feb 25, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [92ac86c31b](https://linux-hardware.org/?probe=92ac86c31b) | Feb 25, 2023 |
| ASUSTek       | PRIME B460M-A R2.0          | [0ccac8edb4](https://linux-hardware.org/?probe=0ccac8edb4) | Feb 24, 2023 |
| HP            | 158B                        | [4d6199df48](https://linux-hardware.org/?probe=4d6199df48) | Feb 20, 2023 |
| Gigabyte      | B460 AORUS PRO AC           | [dc6b25dcef](https://linux-hardware.org/?probe=dc6b25dcef) | Feb 19, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [b01f6d7a1f](https://linux-hardware.org/?probe=b01f6d7a1f) | Feb 17, 2023 |
| Biostar       | B450MH                      | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [27501ca342](https://linux-hardware.org/?probe=27501ca342) | Feb 17, 2023 |
| Lenovo        | ThinkCentre M91 4518E4S     | [91b1fb7e03](https://linux-hardware.org/?probe=91b1fb7e03) | Feb 16, 2023 |
| Biostar       | B450MH                      | [34591a7516](https://linux-hardware.org/?probe=34591a7516) | Feb 15, 2023 |
| Biostar       | B450MH                      | [12142a9f86](https://linux-hardware.org/?probe=12142a9f86) | Feb 15, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| HP            | 1493                        | [641106a383](https://linux-hardware.org/?probe=641106a383) | Feb 13, 2023 |
| Gigabyte      | Z77M-D3H                    | [6d428a3fb9](https://linux-hardware.org/?probe=6d428a3fb9) | Feb 13, 2023 |
| HP            | 1905                        | [a442e1de06](https://linux-hardware.org/?probe=a442e1de06) | Feb 07, 2023 |
| Gigabyte      | B450M DS3H V2               | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Gigabyte      | X570 UD                     | [909d48ecda](https://linux-hardware.org/?probe=909d48ecda) | Feb 03, 2023 |
| Dell          | 00V62H A01                  | [5b3fa12024](https://linux-hardware.org/?probe=5b3fa12024) | Feb 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [72dae43046](https://linux-hardware.org/?probe=72dae43046) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [c11ff840dd](https://linux-hardware.org/?probe=c11ff840dd) | Jan 29, 2023 |
| ASUSTek       | PRIME H510M-E               | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [edfd032f00](https://linux-hardware.org/?probe=edfd032f00) | Jan 26, 2023 |
| Gigabyte      | X570 UD                     | [75e92725f5](https://linux-hardware.org/?probe=75e92725f5) | Jan 26, 2023 |
| Dell          | 0773VG A00                  | [328dae4014](https://linux-hardware.org/?probe=328dae4014) | Jan 26, 2023 |
| AZW           | U59                         | [6d2b672b77](https://linux-hardware.org/?probe=6d2b672b77) | Jan 25, 2023 |
| PCChips       | P49G                        | [24a7d0e02b](https://linux-hardware.org/?probe=24a7d0e02b) | Jan 24, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [af23cdf7e9](https://linux-hardware.org/?probe=af23cdf7e9) | Jan 23, 2023 |
| ASRock        | N68-VGS3 FX                 | [d25d4580a9](https://linux-hardware.org/?probe=d25d4580a9) | Jan 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [17bdbada47](https://linux-hardware.org/?probe=17bdbada47) | Jan 20, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [0f21d67175](https://linux-hardware.org/?probe=0f21d67175) | Jan 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [b48e8ac2ee](https://linux-hardware.org/?probe=b48e8ac2ee) | Jan 19, 2023 |
| Intel         | DG41RQ AAE54511-205         | [1125db7cfd](https://linux-hardware.org/?probe=1125db7cfd) | Jan 18, 2023 |
| ECS           | Iris8                       | [ed85f79aaa](https://linux-hardware.org/?probe=ed85f79aaa) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | H410M H                     | [85605e8c5b](https://linux-hardware.org/?probe=85605e8c5b) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| HP            | 2ADC                        | [69bb1386c0](https://linux-hardware.org/?probe=69bb1386c0) | Jan 13, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [306315e4d8](https://linux-hardware.org/?probe=306315e4d8) | Jan 12, 2023 |
| Gigabyte      | B550M DS3H                  | [1058c3d279](https://linux-hardware.org/?probe=1058c3d279) | Jan 11, 2023 |
| Dell          | 0D28YY A00                  | [736f7a2f65](https://linux-hardware.org/?probe=736f7a2f65) | Jan 11, 2023 |
| MSI           | Boston                      | [00949f3199](https://linux-hardware.org/?probe=00949f3199) | Jan 10, 2023 |
| ASUSTek       | Leonite2                    | [cf4fe3c8d7](https://linux-hardware.org/?probe=cf4fe3c8d7) | Jan 09, 2023 |
| HP            | 1497                        | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| Gigabyte      | Z390 UD                     | [74859544a4](https://linux-hardware.org/?probe=74859544a4) | Jan 06, 2023 |
| Dell          | 0M5DCD A00                  | [c64a1198cd](https://linux-hardware.org/?probe=c64a1198cd) | Jan 04, 2023 |
| Dell          | 0MM599                      | [95763443e3](https://linux-hardware.org/?probe=95763443e3) | Jan 03, 2023 |
| ASUSTek       | E410                        | [d284787f09](https://linux-hardware.org/?probe=d284787f09) | Jan 01, 2023 |
| ASUSTek       | E410                        | [4dabf86358](https://linux-hardware.org/?probe=4dabf86358) | Jan 01, 2023 |
| ASUSTek       | E410                        | [98e0007b65](https://linux-hardware.org/?probe=98e0007b65) | Dec 31, 2022 |
| Lanix         | P55M-UD2 LNXACT             | [5575ce838c](https://linux-hardware.org/?probe=5575ce838c) | Dec 28, 2022 |
| Dell          | 0M017G A00                  | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| ASUSTek       | PRIME A320M-K               | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [bc1c9956b3](https://linux-hardware.org/?probe=bc1c9956b3) | Dec 23, 2022 |
| ASUSTek       | H110M-E/M.2                 | [82584d7e83](https://linux-hardware.org/?probe=82584d7e83) | Dec 20, 2022 |
| Biostar       | A10N-9630E                  | [bc183b5af7](https://linux-hardware.org/?probe=bc183b5af7) | Dec 20, 2022 |
| Biostar       | A10N-9630E                  | [65c72d297e](https://linux-hardware.org/?probe=65c72d297e) | Dec 19, 2022 |
| Gigabyte      | H61M-DS2                    | [b5c4e6cf61](https://linux-hardware.org/?probe=b5c4e6cf61) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [743b2176f1](https://linux-hardware.org/?probe=743b2176f1) | Dec 19, 2022 |
| Dell          | 0M858N A00                  | [e46a95080d](https://linux-hardware.org/?probe=e46a95080d) | Dec 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [7adfddc31e](https://linux-hardware.org/?probe=7adfddc31e) | Dec 16, 2022 |
| Biostar       | A10N-9630E                  | [5dce29a057](https://linux-hardware.org/?probe=5dce29a057) | Dec 16, 2022 |
| Biostar       | A10N-9630E                  | [702d391e89](https://linux-hardware.org/?probe=702d391e89) | Dec 16, 2022 |
| Dell          | 0RW203                      | [2f5bede488](https://linux-hardware.org/?probe=2f5bede488) | Dec 16, 2022 |
| Biostar       | A10N-9630E                  | [a884fddf53](https://linux-hardware.org/?probe=a884fddf53) | Dec 16, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [535643e246](https://linux-hardware.org/?probe=535643e246) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| Biostar       | A10N-9630E                  | [b90f6a6980](https://linux-hardware.org/?probe=b90f6a6980) | Dec 14, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a564c9f0f](https://linux-hardware.org/?probe=0a564c9f0f) | Dec 14, 2022 |
| Gigabyte      | 970A-UD3P                   | [4a41ed7fae](https://linux-hardware.org/?probe=4a41ed7fae) | Dec 07, 2022 |
| Gigabyte      | GA-E6010N                   | [5fddeb1852](https://linux-hardware.org/?probe=5fddeb1852) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [69d71bba75](https://linux-hardware.org/?probe=69d71bba75) | Nov 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [9cbe89c328](https://linux-hardware.org/?probe=9cbe89c328) | Nov 22, 2022 |
| ASUSTek       | PRIME A320M-K               | [9a74fdb05b](https://linux-hardware.org/?probe=9a74fdb05b) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| Intel         | JSL MRD                     | [469567b71f](https://linux-hardware.org/?probe=469567b71f) | Nov 20, 2022 |
| Dell          | 02YRK5 A02                  | [da08e08dec](https://linux-hardware.org/?probe=da08e08dec) | Nov 18, 2022 |
| TPV-INVENT... | 2AC6 A01                    | [04b3ba4242](https://linux-hardware.org/?probe=04b3ba4242) | Nov 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [41266bf8f0](https://linux-hardware.org/?probe=41266bf8f0) | Nov 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [9a7cae7b96](https://linux-hardware.org/?probe=9a7cae7b96) | Nov 15, 2022 |
| Dell          | 0VNP2H A00                  | [8a9b31c73c](https://linux-hardware.org/?probe=8a9b31c73c) | Nov 14, 2022 |
| Dell          | 0VNP2H A00                  | [b49e089cbc](https://linux-hardware.org/?probe=b49e089cbc) | Nov 14, 2022 |
| HP            | 1850                        | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Dell          | 0DF42J A00                  | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| HP            | 304Bh                       | [441e27ba6f](https://linux-hardware.org/?probe=441e27ba6f) | Nov 09, 2022 |
| HP            | 304Bh                       | [ec223d7334](https://linux-hardware.org/?probe=ec223d7334) | Nov 09, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| Intel         | DG33BU AAD79951-407         | [e692849b95](https://linux-hardware.org/?probe=e692849b95) | Nov 04, 2022 |
| Intel         | DG31PR AAD97573-300         | [b2006d028b](https://linux-hardware.org/?probe=b2006d028b) | Nov 03, 2022 |
| MSI           | PRO B660M-A DDR4            | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [689b5a4022](https://linux-hardware.org/?probe=689b5a4022) | Nov 01, 2022 |
| MSI           | A320M PRO-M2 V2             | [d7c699118b](https://linux-hardware.org/?probe=d7c699118b) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [98fe919d0e](https://linux-hardware.org/?probe=98fe919d0e) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9a6e9239e1](https://linux-hardware.org/?probe=9a6e9239e1) | Oct 29, 2022 |
| Gigabyte      | B365M DS3H                  | [2dd0f7f115](https://linux-hardware.org/?probe=2dd0f7f115) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| HP            | 21B4 A01                    | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Biostar       | B450MH                      | [048cd18957](https://linux-hardware.org/?probe=048cd18957) | Oct 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| ASUSTek       | H110M-E/M.2                 | [fb73fb5efc](https://linux-hardware.org/?probe=fb73fb5efc) | Oct 18, 2022 |
| ASUSTek       | H110M-E/M.2                 | [77fd87ca91](https://linux-hardware.org/?probe=77fd87ca91) | Oct 18, 2022 |
| Dell          | 0WG864                      | [2feb42b3cf](https://linux-hardware.org/?probe=2feb42b3cf) | Oct 17, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [b140bed0ec](https://linux-hardware.org/?probe=b140bed0ec) | Oct 17, 2022 |
| Intel         | DP45SG AAE27733-403         | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| ASUSTek       | PRIME H510M-E               | [2b217ec76a](https://linux-hardware.org/?probe=2b217ec76a) | Oct 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ede8c7fa36](https://linux-hardware.org/?probe=ede8c7fa36) | Oct 13, 2022 |
| Intel         | DX79SI AAG28808-600         | [6e3b794116](https://linux-hardware.org/?probe=6e3b794116) | Oct 11, 2022 |
| Biostar       | A10N-9630E                  | [94e5ada4d2](https://linux-hardware.org/?probe=94e5ada4d2) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| eMachines     | EMCP61M                     | [711594c5b4](https://linux-hardware.org/?probe=711594c5b4) | Oct 09, 2022 |
| HP            | ProLiant ML110 Gen9         | [de23da6c1d](https://linux-hardware.org/?probe=de23da6c1d) | Oct 07, 2022 |
| ASRock        | N68-VS3 UCC                 | [e4d5236ae6](https://linux-hardware.org/?probe=e4d5236ae6) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [c5cc32bb50](https://linux-hardware.org/?probe=c5cc32bb50) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [4a364c0802](https://linux-hardware.org/?probe=4a364c0802) | Oct 04, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| Gigabyte      | B75M-D3H                    | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| ECS           | A320AM4-M3D/3.x/5.x         | [570ff509ac](https://linux-hardware.org/?probe=570ff509ac) | Sep 30, 2022 |
| Gigabyte      | Z390 UD                     | [afe1282d38](https://linux-hardware.org/?probe=afe1282d38) | Sep 29, 2022 |
| MSI           | A68HM-E33 V2                | [3e8f63475d](https://linux-hardware.org/?probe=3e8f63475d) | Sep 29, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| Gigabyte      | M68MT-S2                    | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| ASUSTek       | PRIME H410M-A               | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| Gigabyte      | H410M H V3                  | [68f3d2bdba](https://linux-hardware.org/?probe=68f3d2bdba) | Sep 25, 2022 |
| ASUSTek       | Leonite2                    | [f7e1dc7c9d](https://linux-hardware.org/?probe=f7e1dc7c9d) | Sep 24, 2022 |
| ASUSTek       | Leonite2                    | [63d494787f](https://linux-hardware.org/?probe=63d494787f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [841474a64b](https://linux-hardware.org/?probe=841474a64b) | Sep 19, 2022 |
| Intel         | DG33BU AAD79951-407         | [d35104af13](https://linux-hardware.org/?probe=d35104af13) | Sep 19, 2022 |
| Wistron       | ProLiant ML110 G6           | [c986542d56](https://linux-hardware.org/?probe=c986542d56) | Sep 18, 2022 |
| Wistron       | ProLiant ML110 G6           | [a17cc62b40](https://linux-hardware.org/?probe=a17cc62b40) | Sep 18, 2022 |
| Gigabyte      | M68MT-S2                    | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| ECS           | G31T-M9                     | [547762d8bf](https://linux-hardware.org/?probe=547762d8bf) | Sep 11, 2022 |
| Biostar       | H310MHP                     | [6063bede72](https://linux-hardware.org/?probe=6063bede72) | Sep 07, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | H410M H V3                  | [a5f7ef09b8](https://linux-hardware.org/?probe=a5f7ef09b8) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [a138be9eb6](https://linux-hardware.org/?probe=a138be9eb6) | Sep 03, 2022 |
| Dell          | 02YRK5 A02                  | [bc316a8d3f](https://linux-hardware.org/?probe=bc316a8d3f) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [a1f434a97c](https://linux-hardware.org/?probe=a1f434a97c) | Aug 27, 2022 |
| ECS           | A320AM4-M3D                 | [685960846a](https://linux-hardware.org/?probe=685960846a) | Aug 26, 2022 |
| Dell          | 0WG864                      | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| Dell          | 01TKCC A01                  | [9a362ed844](https://linux-hardware.org/?probe=9a362ed844) | Aug 25, 2022 |
| Pegatron      | E60                         | [c1aba90f51](https://linux-hardware.org/?probe=c1aba90f51) | Aug 23, 2022 |
| Dell          | 0WG864                      | [e199a1a176](https://linux-hardware.org/?probe=e199a1a176) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| Dell          | 02YRK5 A02                  | [959d35921a](https://linux-hardware.org/?probe=959d35921a) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | [32bf5bd8b8](https://linux-hardware.org/?probe=32bf5bd8b8) | Aug 13, 2022 |
| Dell          | 0DFRFW A01                  | [9e59d35488](https://linux-hardware.org/?probe=9e59d35488) | Aug 12, 2022 |
| System76      | Thelio thelio-r1            | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| Dell          | 0WG864                      | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Dell          | 0DFRFW A01                  | [4a9c41e3fd](https://linux-hardware.org/?probe=4a9c41e3fd) | Aug 12, 2022 |
| ECS           | A55F-M4                     | [9c032723ab](https://linux-hardware.org/?probe=9c032723ab) | Aug 09, 2022 |
| ASRock        | H61M-DGS                    | [726b790d1a](https://linux-hardware.org/?probe=726b790d1a) | Aug 09, 2022 |
| Intel         | D975XBX2 AAD53350-503       | [67f56805b0](https://linux-hardware.org/?probe=67f56805b0) | Aug 07, 2022 |
| Gigabyte      | A520M S2H                   | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | [e962ba603d](https://linux-hardware.org/?probe=e962ba603d) | Jul 31, 2022 |
| ASRock        | B450M Steel Legend          | [7cb85f4322](https://linux-hardware.org/?probe=7cb85f4322) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d85cd905fd](https://linux-hardware.org/?probe=d85cd905fd) | Jul 28, 2022 |
| Dell          | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| HP            | 0AACh                       | [d7df31df8c](https://linux-hardware.org/?probe=d7df31df8c) | Jul 26, 2022 |
| HP            | 0AACh                       | [357aa343ec](https://linux-hardware.org/?probe=357aa343ec) | Jul 26, 2022 |
| MSI           | PRO Z690-A                  | [9264d3b652](https://linux-hardware.org/?probe=9264d3b652) | Jul 22, 2022 |
| Gigabyte      | M68M-S2P                    | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [afb076562c](https://linux-hardware.org/?probe=afb076562c) | Jul 21, 2022 |
| HP            | 3397                        | [81b550875a](https://linux-hardware.org/?probe=81b550875a) | Jul 19, 2022 |
| Dell          | 0D28YY A00                  | [129009177c](https://linux-hardware.org/?probe=129009177c) | Jul 18, 2022 |
| Dell          | 0D28YY A00                  | [3a633633a2](https://linux-hardware.org/?probe=3a633633a2) | Jul 18, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [639c8172d1](https://linux-hardware.org/?probe=639c8172d1) | Jul 14, 2022 |
| Pegatron      | 2AC3                        | [e1d3204cf2](https://linux-hardware.org/?probe=e1d3204cf2) | Jul 09, 2022 |
| HP            | 18E4                        | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| ASUSTek       | PRIME X570-P                | [28b43e6c1f](https://linux-hardware.org/?probe=28b43e6c1f) | Jul 06, 2022 |
| Gigabyte      | Z87-HD3                     | [d3fab53889](https://linux-hardware.org/?probe=d3fab53889) | Jul 01, 2022 |
| ASUSTek       | PRIME X570-P                | [7eeeee6c93](https://linux-hardware.org/?probe=7eeeee6c93) | Jun 30, 2022 |
| ASUSTek       | PRIME X570-P                | [53dac35f18](https://linux-hardware.org/?probe=53dac35f18) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Biostar       | H510MH/E                    | [7b28198a82](https://linux-hardware.org/?probe=7b28198a82) | Jun 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [01d9100427](https://linux-hardware.org/?probe=01d9100427) | Jun 29, 2022 |
| HP            | 18E9                        | [67a4877415](https://linux-hardware.org/?probe=67a4877415) | Jun 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5873a7a8dd](https://linux-hardware.org/?probe=5873a7a8dd) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [e457a60dd4](https://linux-hardware.org/?probe=e457a60dd4) | Jun 26, 2022 |
| Gigabyte      | GA-880GM-USB3               | [4d48252e22](https://linux-hardware.org/?probe=4d48252e22) | Jun 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| Gigabyte      | M68MT-S2                    | [c52b07844d](https://linux-hardware.org/?probe=c52b07844d) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | [31f786c1ff](https://linux-hardware.org/?probe=31f786c1ff) | Jun 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [8d106f8677](https://linux-hardware.org/?probe=8d106f8677) | Jun 16, 2022 |
| Gigabyte      | M68MT-S2                    | [ded75509fb](https://linux-hardware.org/?probe=ded75509fb) | Jun 15, 2022 |
| ASUSTek       | PRIME H310M-E               | [f0e0fc8360](https://linux-hardware.org/?probe=f0e0fc8360) | Jun 13, 2022 |
| Foxconn       | 2AB7                        | [339721d187](https://linux-hardware.org/?probe=339721d187) | Jun 10, 2022 |
| HP            | 2AF9                        | [005b85e6bb](https://linux-hardware.org/?probe=005b85e6bb) | Jun 10, 2022 |
| TPV-INVENT... | 2AD6 A01                    | [f2a54a7cc4](https://linux-hardware.org/?probe=f2a54a7cc4) | Jun 03, 2022 |
| TPV-INVENT... | 2AD6 A01                    | [deed95f1d2](https://linux-hardware.org/?probe=deed95f1d2) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ECS           | A58F2P-M4                   | [295c085967](https://linux-hardware.org/?probe=295c085967) | Jun 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| MSI           | Boston                      | [7e3c443fb1](https://linux-hardware.org/?probe=7e3c443fb1) | May 27, 2022 |
| ASUSTek       | PRIME B450M-A II            | [ee4d26d407](https://linux-hardware.org/?probe=ee4d26d407) | May 23, 2022 |
| Dell          | 0KRC95 A00                  | [8b45e8387c](https://linux-hardware.org/?probe=8b45e8387c) | May 23, 2022 |
| HP            | 158A                        | [befd0b5756](https://linux-hardware.org/?probe=befd0b5756) | May 18, 2022 |
| Gigabyte      | GA-E6010N                   | [679cd1e540](https://linux-hardware.org/?probe=679cd1e540) | May 18, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 2129                        | [d0babde387](https://linux-hardware.org/?probe=d0babde387) | May 14, 2022 |
| HP            | 158A                        | [a6bbb73cc3](https://linux-hardware.org/?probe=a6bbb73cc3) | May 13, 2022 |
| Biostar       | A10N-9630E                  | [d3151cce7a](https://linux-hardware.org/?probe=d3151cce7a) | May 12, 2022 |
| Intel         | D946GZIS AAD66165-501       | [4eb1cdd501](https://linux-hardware.org/?probe=4eb1cdd501) | May 11, 2022 |
| Gigabyte      | X58A-UD3R                   | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Dell          | 0Y958C A00                  | [5ae3c49fcd](https://linux-hardware.org/?probe=5ae3c49fcd) | May 08, 2022 |
| HP            | 158A                        | [842aab71bd](https://linux-hardware.org/?probe=842aab71bd) | May 06, 2022 |
| HP            | 158B                        | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [3a3a4e634d](https://linux-hardware.org/?probe=3a3a4e634d) | May 05, 2022 |
| Dell          | 00V62H A01                  | [fc3604980a](https://linux-hardware.org/?probe=fc3604980a) | May 04, 2022 |
| ASUSTek       | VM65N-K                     | [9df63c1d99](https://linux-hardware.org/?probe=9df63c1d99) | May 04, 2022 |
| HP            | 3047h                       | [bc2b3d4c04](https://linux-hardware.org/?probe=bc2b3d4c04) | May 04, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| ASUSTek       | Lancaster8                  | [912f9bb3f9](https://linux-hardware.org/?probe=912f9bb3f9) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| HP            | 1497                        | [559a844943](https://linux-hardware.org/?probe=559a844943) | Apr 30, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [88c6676e7b](https://linux-hardware.org/?probe=88c6676e7b) | Apr 29, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f2bdbd2a4a](https://linux-hardware.org/?probe=f2bdbd2a4a) | Apr 29, 2022 |
| Lanix         | EQ45M-S2 LNXACT             | [485f464d12](https://linux-hardware.org/?probe=485f464d12) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | [0cbc3290f0](https://linux-hardware.org/?probe=0cbc3290f0) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [2bcb31328e](https://linux-hardware.org/?probe=2bcb31328e) | Apr 23, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [acc082b594](https://linux-hardware.org/?probe=acc082b594) | Apr 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [61ca629904](https://linux-hardware.org/?probe=61ca629904) | Apr 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [c722e417a1](https://linux-hardware.org/?probe=c722e417a1) | Apr 20, 2022 |
| HP            | 3047h                       | [36a3e2ab98](https://linux-hardware.org/?probe=36a3e2ab98) | Apr 20, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | [5971999c12](https://linux-hardware.org/?probe=5971999c12) | Apr 16, 2022 |
| ASUSTek       | PRIME B450M-A II            | [bdc8f9b39e](https://linux-hardware.org/?probe=bdc8f9b39e) | Apr 15, 2022 |
| Dell          | 0WMJ54 A01                  | [d113301081](https://linux-hardware.org/?probe=d113301081) | Apr 14, 2022 |
| HP            | 0A54h                       | [11c5e77be7](https://linux-hardware.org/?probe=11c5e77be7) | Apr 14, 2022 |
| Dell          | 0C2XKD A00                  | [4ece5fe0b7](https://linux-hardware.org/?probe=4ece5fe0b7) | Apr 13, 2022 |
| ASUSTek       | M4A88T-M                    | [934e06ad74](https://linux-hardware.org/?probe=934e06ad74) | Apr 12, 2022 |
| Biostar       | H110MHC                     | [09715fbaf2](https://linux-hardware.org/?probe=09715fbaf2) | Apr 05, 2022 |
| HP            | 0B48h                       | [7cd0cbb7b7](https://linux-hardware.org/?probe=7cd0cbb7b7) | Apr 05, 2022 |
| Dell          | 0K240Y A03                  | [7e3ad9ce02](https://linux-hardware.org/?probe=7e3ad9ce02) | Apr 02, 2022 |
| ASUSTek       | M5A97 EVO                   | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| ECS           | A55F-M4                     | [0d29bdddde](https://linux-hardware.org/?probe=0d29bdddde) | Mar 31, 2022 |
| ASRock        | B550M Pro4                  | [4c69702c19](https://linux-hardware.org/?probe=4c69702c19) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b625abc938](https://linux-hardware.org/?probe=b625abc938) | Mar 26, 2022 |
| Lanix         | EQ45M-S2 LNXACT             | [ab78b9c7a6](https://linux-hardware.org/?probe=ab78b9c7a6) | Mar 25, 2022 |
| Gigabyte      | A520M H                     | [0eb6fdc31d](https://linux-hardware.org/?probe=0eb6fdc31d) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Biostar       | A10N-9630E                  | [08e8cd5735](https://linux-hardware.org/?probe=08e8cd5735) | Mar 24, 2022 |
| Biostar       | G31D-M7                     | [9882f292ea](https://linux-hardware.org/?probe=9882f292ea) | Mar 24, 2022 |
| ASUSTek       | Maximus IX HERO             | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HP            | 1589                        | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| Gigabyte      | GA-A75M-DS2                 | [7e23b31c1b](https://linux-hardware.org/?probe=7e23b31c1b) | Mar 17, 2022 |
| Dell          | 0D28YY A00                  | [065495a18e](https://linux-hardware.org/?probe=065495a18e) | Mar 13, 2022 |
| Gigabyte      | H110M-DS2-CF                | [9cad95edc1](https://linux-hardware.org/?probe=9cad95edc1) | Mar 12, 2022 |
| Gigabyte      | H110M-H-CF                  | [c8474e89b8](https://linux-hardware.org/?probe=c8474e89b8) | Mar 11, 2022 |
| HP            | 1497                        | [7965a1ed31](https://linux-hardware.org/?probe=7965a1ed31) | Mar 11, 2022 |
| Pegatron      | Benicia                     | [00bcb5f530](https://linux-hardware.org/?probe=00bcb5f530) | Mar 10, 2022 |
| Gigabyte      | A520M H                     | [db7727accf](https://linux-hardware.org/?probe=db7727accf) | Mar 09, 2022 |
| Gigabyte      | A520M H                     | [b8038bbdc8](https://linux-hardware.org/?probe=b8038bbdc8) | Mar 09, 2022 |
| ASUSTek       | PRIME A320M-K               | [515e875bbd](https://linux-hardware.org/?probe=515e875bbd) | Mar 07, 2022 |
| ASUSTek       | B85M-G R2.0                 | [673c6bd0db](https://linux-hardware.org/?probe=673c6bd0db) | Mar 07, 2022 |
| HP            | 0A64h                       | [75e39b1761](https://linux-hardware.org/?probe=75e39b1761) | Mar 07, 2022 |
| Intel         | DG41RQ AAE54511-205         | [36979f5dde](https://linux-hardware.org/?probe=36979f5dde) | Mar 07, 2022 |
| Gigabyte      | A520M H                     | [1b45a09429](https://linux-hardware.org/?probe=1b45a09429) | Mar 03, 2022 |
| Dell          | 0M5DCD A00                  | [91a666ba20](https://linux-hardware.org/?probe=91a666ba20) | Mar 02, 2022 |
| Biostar       | N68S3+                      | [d27fca4784](https://linux-hardware.org/?probe=d27fca4784) | Feb 28, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [db907dad62](https://linux-hardware.org/?probe=db907dad62) | Feb 21, 2022 |
| Gigabyte      | X570 GAMING X               | [346c976e4b](https://linux-hardware.org/?probe=346c976e4b) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b2c662bad6](https://linux-hardware.org/?probe=b2c662bad6) | Feb 18, 2022 |
| Gigabyte      | GA-880GM-USB3               | [4054007b41](https://linux-hardware.org/?probe=4054007b41) | Feb 17, 2022 |
| Dell          | 06X1TJ A00                  | [78b50a2601](https://linux-hardware.org/?probe=78b50a2601) | Feb 17, 2022 |
| Gigabyte      | B560M DS3H                  | [0bba38da27](https://linux-hardware.org/?probe=0bba38da27) | Feb 16, 2022 |
| ASRock        | B250 Gaming K4              | [226e1abd06](https://linux-hardware.org/?probe=226e1abd06) | Feb 11, 2022 |
| Gigabyte      | B150-HD3-CF                 | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| Gigabyte      | GA-880GM-USB3               | [9c02ccf9fb](https://linux-hardware.org/?probe=9c02ccf9fb) | Feb 09, 2022 |
| Gigabyte      | G41MT-S2                    | [9e2a093ef4](https://linux-hardware.org/?probe=9e2a093ef4) | Feb 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [655eea9ee5](https://linux-hardware.org/?probe=655eea9ee5) | Feb 02, 2022 |
| ASUSTek       | PRIME B350M-E               | [3bab4dd576](https://linux-hardware.org/?probe=3bab4dd576) | Jan 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e96d993823](https://linux-hardware.org/?probe=e96d993823) | Jan 26, 2022 |
| Foxconn       | 2A92                        | [affed2d377](https://linux-hardware.org/?probe=affed2d377) | Jan 26, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | [1b2ef9d1dc](https://linux-hardware.org/?probe=1b2ef9d1dc) | Jan 23, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | [e0197b9fdc](https://linux-hardware.org/?probe=e0197b9fdc) | Jan 23, 2022 |
| Intel         | DH61HO AAG62445-102         | [100cf973bf](https://linux-hardware.org/?probe=100cf973bf) | Jan 21, 2022 |
| Dell          | 0PU052                      | [0b1d31cda2](https://linux-hardware.org/?probe=0b1d31cda2) | Jan 20, 2022 |
| Dell          | 0PU052                      | [36323786b9](https://linux-hardware.org/?probe=36323786b9) | Jan 20, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [5052313cdf](https://linux-hardware.org/?probe=5052313cdf) | Jan 17, 2022 |
| HC            | HCAR357-MI V1.0             | [a610cc37dc](https://linux-hardware.org/?probe=a610cc37dc) | Jan 16, 2022 |
| Pegatron      | EVE                         | [d21708f0ed](https://linux-hardware.org/?probe=d21708f0ed) | Jan 14, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [f05cc95e99](https://linux-hardware.org/?probe=f05cc95e99) | Jan 11, 2022 |
| Gigabyte      | AX370-Gaming 5              | [4f99e4803d](https://linux-hardware.org/?probe=4f99e4803d) | Jan 09, 2022 |
| Acer          | WG43M                       | [8c9d16de68](https://linux-hardware.org/?probe=8c9d16de68) | Jan 08, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [a2ca29b82e](https://linux-hardware.org/?probe=a2ca29b82e) | Jan 07, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [b92a220707](https://linux-hardware.org/?probe=b92a220707) | Jan 07, 2022 |
| Intel         | DX58SO AAE29331-501         | [3718c8a46f](https://linux-hardware.org/?probe=3718c8a46f) | Jan 05, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [df695a7747](https://linux-hardware.org/?probe=df695a7747) | Jan 03, 2022 |
| ASUSTek       | P8B75-M                     | [2436d612db](https://linux-hardware.org/?probe=2436d612db) | Jan 02, 2022 |
| ASUSTek       | P8B75-M                     | [275d5a762b](https://linux-hardware.org/?probe=275d5a762b) | Jan 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9d2017b698](https://linux-hardware.org/?probe=9d2017b698) | Dec 29, 2021 |
| Dell          | 0GC080                      | [7ab7f1da0e](https://linux-hardware.org/?probe=7ab7f1da0e) | Dec 23, 2021 |
| Gigabyte      | H110M-DS2-CF                | [729cb86592](https://linux-hardware.org/?probe=729cb86592) | Dec 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b7b779b709](https://linux-hardware.org/?probe=b7b779b709) | Dec 16, 2021 |
| Dell          | 0GM819                      | [809fc591dd](https://linux-hardware.org/?probe=809fc591dd) | Dec 16, 2021 |
| Biostar       | H110MHC                     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| Pegatron      | 2A73h                       | [603a6f5087](https://linux-hardware.org/?probe=603a6f5087) | Dec 15, 2021 |
| HP            | 09F8h                       | [c70b669376](https://linux-hardware.org/?probe=c70b669376) | Dec 13, 2021 |
| ASUSTek       | Bantry CRB SDK0E50510 WI... | [5dfc7cb81a](https://linux-hardware.org/?probe=5dfc7cb81a) | Dec 11, 2021 |
| Gigabyte      | B150M-DS3H-CF               | [9cc5505029](https://linux-hardware.org/?probe=9cc5505029) | Dec 11, 2021 |
| HP            | 158A                        | [db518613b6](https://linux-hardware.org/?probe=db518613b6) | Dec 10, 2021 |
| HP            | 3397                        | [9c1590635c](https://linux-hardware.org/?probe=9c1590635c) | Dec 09, 2021 |
| Dell          | 0WG864                      | [59d9c69b35](https://linux-hardware.org/?probe=59d9c69b35) | Dec 08, 2021 |
| HP            | 09F8h                       | [fe41d0247b](https://linux-hardware.org/?probe=fe41d0247b) | Dec 08, 2021 |
| Acer          | Aspire XC-704G              | [961534f79d](https://linux-hardware.org/?probe=961534f79d) | Dec 08, 2021 |
| Acer          | Aspire XC-704G              | [5b69f445ad](https://linux-hardware.org/?probe=5b69f445ad) | Dec 08, 2021 |
| HP            | 0A54h                       | [e445d6aa51](https://linux-hardware.org/?probe=e445d6aa51) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7a511dda3d](https://linux-hardware.org/?probe=7a511dda3d) | Dec 04, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60e7267ddb](https://linux-hardware.org/?probe=60e7267ddb) | Dec 04, 2021 |
| Acer          | Aspire X1930                | [68d51a9af5](https://linux-hardware.org/?probe=68d51a9af5) | Dec 03, 2021 |
| Gigabyte      | GA-E350N                    | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [0105f991c1](https://linux-hardware.org/?probe=0105f991c1) | Dec 01, 2021 |
| Gigabyte      | B560 AORUS PRO AX           | [13325b986f](https://linux-hardware.org/?probe=13325b986f) | Dec 01, 2021 |
| Biostar       | TH55XE                      | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| Dell          | 0WR7PY A01                  | [f886714ec5](https://linux-hardware.org/?probe=f886714ec5) | Nov 28, 2021 |
| HP            | 1497                        | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0cb5ca7e51](https://linux-hardware.org/?probe=0cb5ca7e51) | Nov 28, 2021 |
| Gigabyte      | H77M-D3H                    | [8b2be4927b](https://linux-hardware.org/?probe=8b2be4927b) | Nov 27, 2021 |
| ECS           | 945GCT-M3                   | [a81a27ac47](https://linux-hardware.org/?probe=a81a27ac47) | Nov 25, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [81a6212074](https://linux-hardware.org/?probe=81a6212074) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| Gigabyte      | H77M-D3H                    | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| HP            | 0A5Ch                       | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| ECS           | Nettle3                     | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [de0c208dd4](https://linux-hardware.org/?probe=de0c208dd4) | Nov 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| ASUSTek       | P8B75-M                     | [a3cd1a283b](https://linux-hardware.org/?probe=a3cd1a283b) | Nov 13, 2021 |
| Dell          | 0HY9JP A00                  | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| Dell          | 0N826N A03                  | [d7d0a0b507](https://linux-hardware.org/?probe=d7d0a0b507) | Nov 03, 2021 |
| ASUSTek       | M2N-E SLI                   | [393213dee8](https://linux-hardware.org/?probe=393213dee8) | Oct 31, 2021 |
| Dell          | 0N826N A03                  | [ffb75356ef](https://linux-hardware.org/?probe=ffb75356ef) | Oct 30, 2021 |
| Dell          | 0N826N A03                  | [db2a7eba35](https://linux-hardware.org/?probe=db2a7eba35) | Oct 29, 2021 |
| ASRock        | AB350 Pro4                  | [54f331c0ec](https://linux-hardware.org/?probe=54f331c0ec) | Oct 29, 2021 |
| Gigabyte      | Z77X-UP4 TH                 | [47a0de503d](https://linux-hardware.org/?probe=47a0de503d) | Oct 27, 2021 |
| Dell          | 0GC080                      | [cb7602a2bd](https://linux-hardware.org/?probe=cb7602a2bd) | Oct 26, 2021 |
| ASUSTek       | Z170-A                      | [9fed362dde](https://linux-hardware.org/?probe=9fed362dde) | Oct 25, 2021 |
| ASUSTek       | Z170-A                      | [7414a480f8](https://linux-hardware.org/?probe=7414a480f8) | Oct 25, 2021 |
| Gigabyte      | Z77X-UP4 TH                 | [f3c4f73cb2](https://linux-hardware.org/?probe=f3c4f73cb2) | Oct 23, 2021 |
| Dell          | 0N826N A03                  | [5fea6b8b9a](https://linux-hardware.org/?probe=5fea6b8b9a) | Oct 22, 2021 |
| Dell          | 0N826N A03                  | [eb508ab31e](https://linux-hardware.org/?probe=eb508ab31e) | Oct 22, 2021 |
| Google        | Guado                       | [5aba3d29f4](https://linux-hardware.org/?probe=5aba3d29f4) | Oct 21, 2021 |
| Google        | Guado                       | [2393c52b33](https://linux-hardware.org/?probe=2393c52b33) | Oct 21, 2021 |
| Foxconn       | 2AB7                        | [de1be07e5a](https://linux-hardware.org/?probe=de1be07e5a) | Oct 20, 2021 |
| Foxconn       | 2AB7                        | [4e260fe9f3](https://linux-hardware.org/?probe=4e260fe9f3) | Oct 20, 2021 |
| HP            | 0A5Ch                       | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Dell          | 0RF705                      | [07965413db](https://linux-hardware.org/?probe=07965413db) | Oct 18, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | [6522d9dc18](https://linux-hardware.org/?probe=6522d9dc18) | Oct 18, 2021 |
| ASUSTek       | P6T                         | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Biostar       | N61PB-M2S                   | [e16a5113ba](https://linux-hardware.org/?probe=e16a5113ba) | Oct 17, 2021 |
| Biostar       | N61PB-M2S                   | [d17b2a3da0](https://linux-hardware.org/?probe=d17b2a3da0) | Oct 16, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [57eaf5a3e0](https://linux-hardware.org/?probe=57eaf5a3e0) | Oct 15, 2021 |
| Intel         | B75                         | [9374d023b7](https://linux-hardware.org/?probe=9374d023b7) | Oct 15, 2021 |
| Dell          | 09KPNV A00                  | [ecda4970d8](https://linux-hardware.org/?probe=ecda4970d8) | Oct 15, 2021 |
| Dell          | 0N826N A03                  | [54b9ff49e4](https://linux-hardware.org/?probe=54b9ff49e4) | Oct 14, 2021 |
| Biostar       | A10N-9630E                  | [d8ce068d3a](https://linux-hardware.org/?probe=d8ce068d3a) | Oct 12, 2021 |
| Dell          | 0N826N A03                  | [d74fd1a5d9](https://linux-hardware.org/?probe=d74fd1a5d9) | Oct 12, 2021 |
| ASRock        | N73V-S                      | [01e398a327](https://linux-hardware.org/?probe=01e398a327) | Oct 11, 2021 |
| ASRock        | N73V-S                      | [8ae578e81d](https://linux-hardware.org/?probe=8ae578e81d) | Oct 10, 2021 |
| ASUSTek       | H87M-PLUS                   | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [f8a55a2c62](https://linux-hardware.org/?probe=f8a55a2c62) | Oct 08, 2021 |
| Intel         | B75                         | [3a8b2a06b0](https://linux-hardware.org/?probe=3a8b2a06b0) | Oct 08, 2021 |
| Intel         | B75                         | [a694ca546a](https://linux-hardware.org/?probe=a694ca546a) | Oct 08, 2021 |
| Pegatron      | 2A99                        | [10f364b4ef](https://linux-hardware.org/?probe=10f364b4ef) | Oct 07, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [67b629d7f9](https://linux-hardware.org/?probe=67b629d7f9) | Oct 02, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [d92879de9a](https://linux-hardware.org/?probe=d92879de9a) | Sep 28, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [c91a5b0d8d](https://linux-hardware.org/?probe=c91a5b0d8d) | Sep 25, 2021 |
| HP            | 09E0h                       | [35fd460ea9](https://linux-hardware.org/?probe=35fd460ea9) | Sep 25, 2021 |
| ASRock        | N68-VS3 FX                  | [b9c8253944](https://linux-hardware.org/?probe=b9c8253944) | Sep 25, 2021 |
| Dell          | 0478VN A00                  | [89db3ccae7](https://linux-hardware.org/?probe=89db3ccae7) | Sep 22, 2021 |
| Acer          | Veriton X2631G V:1.0        | [c75d05568f](https://linux-hardware.org/?probe=c75d05568f) | Sep 22, 2021 |
| Dell          | 0GC080                      | [0297b84b90](https://linux-hardware.org/?probe=0297b84b90) | Sep 22, 2021 |
| Dell          | 0GC080                      | [d66102b7f1](https://linux-hardware.org/?probe=d66102b7f1) | Sep 22, 2021 |
| Alienware     | 0PGRP5 A02                  | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| ECS           | G41T-M7                     | [42e72694fc](https://linux-hardware.org/?probe=42e72694fc) | Sep 15, 2021 |
| Dell          | 0GC080                      | [e7be152af1](https://linux-hardware.org/?probe=e7be152af1) | Sep 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | [e1f454ca9a](https://linux-hardware.org/?probe=e1f454ca9a) | Sep 13, 2021 |
| ECS           | H81H3-M4                    | [5dcb7c25ca](https://linux-hardware.org/?probe=5dcb7c25ca) | Sep 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [267c72cca2](https://linux-hardware.org/?probe=267c72cca2) | Sep 11, 2021 |
| Lenovo        | ThinkCentre M58e 7303AS6    | [467b83765f](https://linux-hardware.org/?probe=467b83765f) | Sep 10, 2021 |
| MSI           | MS-7228                     | [30e50bf019](https://linux-hardware.org/?probe=30e50bf019) | Sep 07, 2021 |
| ASRock        | G41M-VS                     | [4895fb4c21](https://linux-hardware.org/?probe=4895fb4c21) | Sep 07, 2021 |
| HP            | 8056                        | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| ASUSTek       | PRIME A320M-K               | [fcdcfe317f](https://linux-hardware.org/?probe=fcdcfe317f) | Sep 05, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [c9fd460c11](https://linux-hardware.org/?probe=c9fd460c11) | Sep 04, 2021 |
| Lenovo        | Annapurna CRB NOK           | [2891fe25e6](https://linux-hardware.org/?probe=2891fe25e6) | Sep 03, 2021 |
| HP            | 1497                        | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [f1a0e351a2](https://linux-hardware.org/?probe=f1a0e351a2) | Aug 31, 2021 |
| Lenovo        | Annapurna CRB NOK           | [f1eec80b6a](https://linux-hardware.org/?probe=f1eec80b6a) | Aug 30, 2021 |
| ASUSTek       | PRIME X570-P                | [f185dd7230](https://linux-hardware.org/?probe=f185dd7230) | Aug 30, 2021 |
| ASRock        | G31M-S                      | [00579ca792](https://linux-hardware.org/?probe=00579ca792) | Aug 30, 2021 |
| ASRock        | G41M-VS                     | [6d2338d42c](https://linux-hardware.org/?probe=6d2338d42c) | Aug 26, 2021 |
| MSI           | MS-7228                     | [ee7056f565](https://linux-hardware.org/?probe=ee7056f565) | Aug 25, 2021 |
| Intel         | DX58SO AAE29331-501         | [465643c093](https://linux-hardware.org/?probe=465643c093) | Aug 24, 2021 |
| ASUSTek       | F1A75-V PRO                 | [52bfc025ea](https://linux-hardware.org/?probe=52bfc025ea) | Aug 24, 2021 |
| ASUSTek       | F1A75-V PRO                 | [2e19d48879](https://linux-hardware.org/?probe=2e19d48879) | Aug 24, 2021 |
| Dell          | 00V62H A01                  | [76399f56e4](https://linux-hardware.org/?probe=76399f56e4) | Aug 23, 2021 |
| Dell          | 00V62H A01                  | [178106e076](https://linux-hardware.org/?probe=178106e076) | Aug 23, 2021 |
| HP            | 0A54h                       | [bf3279fcac](https://linux-hardware.org/?probe=bf3279fcac) | Aug 21, 2021 |
| MSI           | MS-7228                     | [841ad28c0d](https://linux-hardware.org/?probe=841ad28c0d) | Aug 20, 2021 |
| HP            | 1905                        | [cce83a6aea](https://linux-hardware.org/?probe=cce83a6aea) | Aug 19, 2021 |
| HP            | 1905                        | [6d387ffc16](https://linux-hardware.org/?probe=6d387ffc16) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6f5485edfc](https://linux-hardware.org/?probe=6f5485edfc) | Aug 18, 2021 |
| ASUSTek       | PRIME X570-P                | [a86f566c6c](https://linux-hardware.org/?probe=a86f566c6c) | Aug 15, 2021 |
| ASUSTek       | M5A97                       | [886707949b](https://linux-hardware.org/?probe=886707949b) | Aug 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [0f178a3f71](https://linux-hardware.org/?probe=0f178a3f71) | Aug 12, 2021 |
| ICP / iEi     | SA60 V1.0                   | [222cb216be](https://linux-hardware.org/?probe=222cb216be) | Aug 09, 2021 |
| Dell          | 0PU052                      | [32ebdc5911](https://linux-hardware.org/?probe=32ebdc5911) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | [fed696b5e3](https://linux-hardware.org/?probe=fed696b5e3) | Aug 08, 2021 |
| HP            | 1791                        | [9de8ddbd32](https://linux-hardware.org/?probe=9de8ddbd32) | Aug 07, 2021 |
| ASRock        | A55M-HVS                    | [d5bc156b08](https://linux-hardware.org/?probe=d5bc156b08) | Aug 05, 2021 |
| Intel         | DG31PR AAD97573-300         | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [dfaac9ebd2](https://linux-hardware.org/?probe=dfaac9ebd2) | Aug 02, 2021 |
| ASRock        | Z370/OEM                    | [c90b04c55f](https://linux-hardware.org/?probe=c90b04c55f) | Aug 02, 2021 |
| ASRock        | Z370/OEM                    | [2309a1a720](https://linux-hardware.org/?probe=2309a1a720) | Aug 02, 2021 |
| Gigabyte      | H470M DS3H                  | [bac1dc0b38](https://linux-hardware.org/?probe=bac1dc0b38) | Jul 31, 2021 |
| ASRock        | G41M-VS                     | [fbdfda41ad](https://linux-hardware.org/?probe=fbdfda41ad) | Jul 26, 2021 |
| ASRock        | G41M-VS                     | [e128037a00](https://linux-hardware.org/?probe=e128037a00) | Jul 26, 2021 |
| Intel         | DZ68BC AAG30742-401         | [c45e851a86](https://linux-hardware.org/?probe=c45e851a86) | Jul 25, 2021 |
| HP            | 158A                        | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| HP            | 158A                        | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| HP            | 2129                        | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Intel         | DZ68BC AAG30742-401         | [e7678d488a](https://linux-hardware.org/?probe=e7678d488a) | Jul 25, 2021 |
| Intel         | DZ68BC AAG30742-401         | [d83e25f4e3](https://linux-hardware.org/?probe=d83e25f4e3) | Jul 25, 2021 |
| ASUSTek       | PRIME B360M-A               | [c31b8a6921](https://linux-hardware.org/?probe=c31b8a6921) | Jul 24, 2021 |
| Lanix         | ChiefRiver                  | [749fc3ef84](https://linux-hardware.org/?probe=749fc3ef84) | Jul 24, 2021 |
| ASRock        | FM2A68M-DG3+                | [aff6409a49](https://linux-hardware.org/?probe=aff6409a49) | Jul 23, 2021 |
| Gigabyte      | B360M D3H-CF                | [d836ee6421](https://linux-hardware.org/?probe=d836ee6421) | Jul 22, 2021 |
| Dell          | 0GDG8Y A00                  | [d56411950c](https://linux-hardware.org/?probe=d56411950c) | Jul 22, 2021 |
| Intel         | DG31PR AAD97573-300         | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5d56e0dd55](https://linux-hardware.org/?probe=5d56e0dd55) | Jul 21, 2021 |
| ASUSTek       | PRIME X570-P                | [8556b83d79](https://linux-hardware.org/?probe=8556b83d79) | Jul 21, 2021 |
| MSI           | MS-7267                     | [52409111c1](https://linux-hardware.org/?probe=52409111c1) | Jul 20, 2021 |
| HP            | 8719                        | [d6615d50f8](https://linux-hardware.org/?probe=d6615d50f8) | Jul 20, 2021 |
| Gigabyte      | B450M H                     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| Biostar       | A10N-8800E                  | [aae6a8bcb2](https://linux-hardware.org/?probe=aae6a8bcb2) | Jul 20, 2021 |
| Dell          | 0GM819                      | [4702931d5a](https://linux-hardware.org/?probe=4702931d5a) | Jul 19, 2021 |
| HP            | 83E8                        | [f378108dc3](https://linux-hardware.org/?probe=f378108dc3) | Jul 19, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [156577ba27](https://linux-hardware.org/?probe=156577ba27) | Jul 18, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [c332ee495e](https://linux-hardware.org/?probe=c332ee495e) | Jul 17, 2021 |
| HP            | 8719                        | [2d00fe2e1a](https://linux-hardware.org/?probe=2d00fe2e1a) | Jul 14, 2021 |
| ASUSTek       | H81M-A                      | [07c39de2b3](https://linux-hardware.org/?probe=07c39de2b3) | Jul 11, 2021 |
| HP            | 1589                        | [7b686149e2](https://linux-hardware.org/?probe=7b686149e2) | Jul 11, 2021 |
| HP            | 1589                        | [0262723214](https://linux-hardware.org/?probe=0262723214) | Jul 11, 2021 |
| ECS           | MCP61PM-AMA                 | [8d410cf5d0](https://linux-hardware.org/?probe=8d410cf5d0) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c8ef49c85e](https://linux-hardware.org/?probe=c8ef49c85e) | Jul 10, 2021 |
| Lenovo        | 0B98401 PRO                 | [f8be96c44a](https://linux-hardware.org/?probe=f8be96c44a) | Jul 09, 2021 |
| HP            | 1495                        | [3dc7075de2](https://linux-hardware.org/?probe=3dc7075de2) | Jul 06, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [5758df25ec](https://linux-hardware.org/?probe=5758df25ec) | Jul 06, 2021 |
| HP            | 1588h                       | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| Dell          | 0GM819                      | [03375c12d1](https://linux-hardware.org/?probe=03375c12d1) | Jul 03, 2021 |
| PCChips       | P25G                        | [8cbcba9099](https://linux-hardware.org/?probe=8cbcba9099) | Jul 03, 2021 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | [36c64a337b](https://linux-hardware.org/?probe=36c64a337b) | Jul 03, 2021 |
| Dell          | 0GM819                      | [b7dd22633c](https://linux-hardware.org/?probe=b7dd22633c) | Jul 01, 2021 |
| Dell          | 0J8H4R A00                  | [ceadcc5249](https://linux-hardware.org/?probe=ceadcc5249) | Jun 30, 2021 |
| HP            | 83E8                        | [ced2d9a47f](https://linux-hardware.org/?probe=ced2d9a47f) | Jun 29, 2021 |
| ECS           | G31T-M9                     | [e1952ea77b](https://linux-hardware.org/?probe=e1952ea77b) | Jun 28, 2021 |
| ECS           | G31T-M9                     | [acb1983b65](https://linux-hardware.org/?probe=acb1983b65) | Jun 27, 2021 |
| ASRock        | 890GM Pro3                  | [ba7c80fa48](https://linux-hardware.org/?probe=ba7c80fa48) | Jun 27, 2021 |
| Gigabyte      | B150M-DS3H-CF               | [ee5b0962e9](https://linux-hardware.org/?probe=ee5b0962e9) | Jun 26, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [75e171067f](https://linux-hardware.org/?probe=75e171067f) | Jun 18, 2021 |
| ASUSTek       | PRIME X370-PRO              | [15b6c87991](https://linux-hardware.org/?probe=15b6c87991) | Jun 18, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [f6d899ab00](https://linux-hardware.org/?probe=f6d899ab00) | Jun 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [39f357041a](https://linux-hardware.org/?probe=39f357041a) | Jun 17, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [02f5d5910a](https://linux-hardware.org/?probe=02f5d5910a) | Jun 15, 2021 |
| HC            | HCAR357-MI V1.0             | [6757c0e254](https://linux-hardware.org/?probe=6757c0e254) | Jun 14, 2021 |
| HP            | 8309                        | [f39dd3dca3](https://linux-hardware.org/?probe=f39dd3dca3) | Jun 11, 2021 |
| ASUSTek       | PRIME B450M-A               | [0c70aaba2f](https://linux-hardware.org/?probe=0c70aaba2f) | Jun 10, 2021 |
| ASUSTek       | PRIME B450M-A               | [dc5f10f04f](https://linux-hardware.org/?probe=dc5f10f04f) | Jun 10, 2021 |
| HP            | 8626                        | [e92fa74b31](https://linux-hardware.org/?probe=e92fa74b31) | Jun 07, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [a7a5bcdee3](https://linux-hardware.org/?probe=a7a5bcdee3) | Jun 06, 2021 |
| Dell          | 0GDG8Y A00                  | [45aa9aed0d](https://linux-hardware.org/?probe=45aa9aed0d) | Jun 02, 2021 |
| HP            | 83E8                        | [f2ed15c184](https://linux-hardware.org/?probe=f2ed15c184) | Jun 01, 2021 |
| Gigabyte      | E2100N                      | [a32062eca7](https://linux-hardware.org/?probe=a32062eca7) | May 30, 2021 |
| Dell          | 0JP3NX A01                  | [f3e4767726](https://linux-hardware.org/?probe=f3e4767726) | May 26, 2021 |
| HP            | 8309                        | [e3480e8653](https://linux-hardware.org/?probe=e3480e8653) | May 26, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [6015233ffd](https://linux-hardware.org/?probe=6015233ffd) | May 25, 2021 |
| ASUSTek       | K8N                         | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| Gigabyte      | B450 AORUS M                | [3647d11d65](https://linux-hardware.org/?probe=3647d11d65) | May 23, 2021 |
| Gigabyte      | F2A68HM-DS2H                | [2721591f4e](https://linux-hardware.org/?probe=2721591f4e) | May 21, 2021 |
| Intel         | DH61CR AAG14064-210         | [bea3558b12](https://linux-hardware.org/?probe=bea3558b12) | May 20, 2021 |
| ASUSTek       | K8N                         | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| Dell          | 0PJ149                      | [132993403b](https://linux-hardware.org/?probe=132993403b) | May 15, 2021 |
| Dell          | 0PJ149                      | [6c5a768962](https://linux-hardware.org/?probe=6c5a768962) | May 15, 2021 |
| HP            | 1495                        | [57aab0779a](https://linux-hardware.org/?probe=57aab0779a) | May 13, 2021 |
| HP            | 1495                        | [024bb4ac1e](https://linux-hardware.org/?probe=024bb4ac1e) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Gigabyte      | B450M DS3H V2               | [39f25072f9](https://linux-hardware.org/?probe=39f25072f9) | May 13, 2021 |
| Gigabyte      | GA-MA770-DS3                | [06fa187755](https://linux-hardware.org/?probe=06fa187755) | May 12, 2021 |
| Lanix         | H55M-E33 LNXACT             | [4671af1d0c](https://linux-hardware.org/?probe=4671af1d0c) | May 11, 2021 |
| Lanix         | H55M-E33 LNXACT             | [04e6d2e131](https://linux-hardware.org/?probe=04e6d2e131) | May 11, 2021 |
| ASUSTek       | K8N                         | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| HP            | 1589                        | [6505b7cd57](https://linux-hardware.org/?probe=6505b7cd57) | May 10, 2021 |
| Lenovo        | ThinkCentre M58e 7303AS6    | [b6029c290f](https://linux-hardware.org/?probe=b6029c290f) | May 08, 2021 |
| Acer          | FMCP7A-ION                  | [093d03caf5](https://linux-hardware.org/?probe=093d03caf5) | May 08, 2021 |
| ECS           | APLD-I                      | [0684f7d10f](https://linux-hardware.org/?probe=0684f7d10f) | May 08, 2021 |
| HP            | 0A54h                       | [2d99b2d79d](https://linux-hardware.org/?probe=2d99b2d79d) | May 07, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | [2e99e6785b](https://linux-hardware.org/?probe=2e99e6785b) | May 05, 2021 |
| Gigabyte      | H61M-DS2                    | [d558c3e02d](https://linux-hardware.org/?probe=d558c3e02d) | May 02, 2021 |
| HP            | 1850                        | [dda5668371](https://linux-hardware.org/?probe=dda5668371) | Apr 27, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | [e3cdc7da97](https://linux-hardware.org/?probe=e3cdc7da97) | Apr 24, 2021 |
| Acer          | F690GVM                     | [a0e95916c3](https://linux-hardware.org/?probe=a0e95916c3) | Apr 24, 2021 |
| Lenovo        | ThinkCentre M57p 6073BC1    | [095cc14306](https://linux-hardware.org/?probe=095cc14306) | Apr 21, 2021 |
| ASUSTek       | P8B75-V                     | [6396ba1a82](https://linux-hardware.org/?probe=6396ba1a82) | Apr 18, 2021 |
| ASUSTek       | P8B75-V                     | [57d0c51af4](https://linux-hardware.org/?probe=57d0c51af4) | Apr 18, 2021 |
| ASUSTek       | PRIME A320M-K               | [061de908dd](https://linux-hardware.org/?probe=061de908dd) | Apr 17, 2021 |
| ASUSTek       | PRIME A320M-K               | [f4a50f4037](https://linux-hardware.org/?probe=f4a50f4037) | Apr 16, 2021 |
| Lenovo        | 0B98401 PRO                 | [7632b57ceb](https://linux-hardware.org/?probe=7632b57ceb) | Apr 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Intel         | DP55WB AAE64798-205         | [c3484ad47c](https://linux-hardware.org/?probe=c3484ad47c) | Apr 09, 2021 |
| ASUSTek       | PRIME A320M-K               | [55543e7a34](https://linux-hardware.org/?probe=55543e7a34) | Apr 08, 2021 |
| ASUSTek       | PRIME A320M-K               | [b2a38f23f6](https://linux-hardware.org/?probe=b2a38f23f6) | Apr 08, 2021 |
| Lenovo        | 0B98401 PRO                 | [4b7f87f3eb](https://linux-hardware.org/?probe=4b7f87f3eb) | Apr 04, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| ASUSTek       | Rampage V EXTREME           | [0699b1c6fb](https://linux-hardware.org/?probe=0699b1c6fb) | Mar 30, 2021 |
| HP            | 1497                        | [4aa0208ce6](https://linux-hardware.org/?probe=4aa0208ce6) | Mar 25, 2021 |
| Gigabyte      | GA-880GM-USB3               | [a0c4ee65a0](https://linux-hardware.org/?probe=a0c4ee65a0) | Mar 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [b91dd5b40d](https://linux-hardware.org/?probe=b91dd5b40d) | Mar 22, 2021 |
| ASUSTek       | PRIME A320M-K               | [1db414e1cd](https://linux-hardware.org/?probe=1db414e1cd) | Mar 21, 2021 |
| MSI           | 09AC                        | [d104a69625](https://linux-hardware.org/?probe=d104a69625) | Mar 20, 2021 |
| HP            | 0B54h D                     | [4c7077e561](https://linux-hardware.org/?probe=4c7077e561) | Mar 19, 2021 |
| MSI           | Boston                      | [5cb4a31210](https://linux-hardware.org/?probe=5cb4a31210) | Mar 17, 2021 |
| TPV-INVENT... | 2AF2 A01                    | [f94c9af809](https://linux-hardware.org/?probe=f94c9af809) | Mar 15, 2021 |
| TPV-INVENT... | 2AF2 A01                    | [a1742b9438](https://linux-hardware.org/?probe=a1742b9438) | Mar 15, 2021 |
| Gigabyte      | GA-880GM-USB3               | [d704baeb91](https://linux-hardware.org/?probe=d704baeb91) | Mar 12, 2021 |
| MSI           | MEG Z390 ACE                | [2d747722a5](https://linux-hardware.org/?probe=2d747722a5) | Mar 09, 2021 |
| MSI           | A320I-S01                   | [a1d308d16c](https://linux-hardware.org/?probe=a1d308d16c) | Mar 09, 2021 |
| Biostar       | N61PC-M2S                   | [48e245bfde](https://linux-hardware.org/?probe=48e245bfde) | Mar 07, 2021 |
| PCChips       | P23G                        | [b449dc535c](https://linux-hardware.org/?probe=b449dc535c) | Mar 07, 2021 |
| Biostar       | A10N-8800E                  | [f70ae0cb83](https://linux-hardware.org/?probe=f70ae0cb83) | Mar 06, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6a0c475800](https://linux-hardware.org/?probe=6a0c475800) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [bfa3a17409](https://linux-hardware.org/?probe=bfa3a17409) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [4b9649e87e](https://linux-hardware.org/?probe=4b9649e87e) | Mar 02, 2021 |
| MSI           | Boston                      | [5beb270bcf](https://linux-hardware.org/?probe=5beb270bcf) | Mar 02, 2021 |
| Gigabyte      | GA-MA69VM-S2                | [64839e8197](https://linux-hardware.org/?probe=64839e8197) | Mar 01, 2021 |
| MSI           | A320I-S01                   | [cc8c69021c](https://linux-hardware.org/?probe=cc8c69021c) | Mar 01, 2021 |
| ASUSTek       | Rampage V EXTREME           | [8912ddde77](https://linux-hardware.org/?probe=8912ddde77) | Feb 23, 2021 |
| ASUSTek       | P8B75-V                     | [38c2a7057d](https://linux-hardware.org/?probe=38c2a7057d) | Feb 21, 2021 |
| Intel         | DH67BL AAG10189-208         | [5ab028f83a](https://linux-hardware.org/?probe=5ab028f83a) | Feb 21, 2021 |
| Intel         | DH67BL AAG10189-208         | [b8f62cc804](https://linux-hardware.org/?probe=b8f62cc804) | Feb 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [1c51280c71](https://linux-hardware.org/?probe=1c51280c71) | Feb 19, 2021 |
| Lenovo        | ThinkCentre M91 4518E4S     | [a57355ac9b](https://linux-hardware.org/?probe=a57355ac9b) | Feb 17, 2021 |
| ECS           | A320AM4-M3D                 | [8d2dbe8074](https://linux-hardware.org/?probe=8d2dbe8074) | Feb 15, 2021 |
| ECS           | A320AM4-M3D                 | [a610ba6866](https://linux-hardware.org/?probe=a610ba6866) | Feb 14, 2021 |
| Pegatron      | 2AD3                        | [5888de381b](https://linux-hardware.org/?probe=5888de381b) | Feb 13, 2021 |
| HP            | 83F2                        | [9b30a9a646](https://linux-hardware.org/?probe=9b30a9a646) | Feb 13, 2021 |
| Gigabyte      | H81M-H                      | [07af414e8b](https://linux-hardware.org/?probe=07af414e8b) | Feb 13, 2021 |
| Biostar       | AM1ML                       | [ad658cfe42](https://linux-hardware.org/?probe=ad658cfe42) | Feb 13, 2021 |
| ASRock        | H61M-DGS                    | [74f2e7bbf2](https://linux-hardware.org/?probe=74f2e7bbf2) | Feb 09, 2021 |
| ASRock        | FM2A68M-DG3+                | [85d68c7774](https://linux-hardware.org/?probe=85d68c7774) | Feb 07, 2021 |
| Pegatron      | BSW-P1                      | [e81b62130f](https://linux-hardware.org/?probe=e81b62130f) | Feb 07, 2021 |
| Gigabyte      | A320M-S2H-CF                | [05757c7d76](https://linux-hardware.org/?probe=05757c7d76) | Feb 06, 2021 |
| MSI           | Boston                      | [af3ffa8291](https://linux-hardware.org/?probe=af3ffa8291) | Feb 05, 2021 |
| Foxconn       | ELVAS                       | [dbe0c13d03](https://linux-hardware.org/?probe=dbe0c13d03) | Feb 05, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | [38ac60e3d1](https://linux-hardware.org/?probe=38ac60e3d1) | Feb 03, 2021 |
| Pegatron      | BSW-P1                      | [224f6f733b](https://linux-hardware.org/?probe=224f6f733b) | Feb 03, 2021 |
| Pegatron      | BSW-P1                      | [e42254b8d8](https://linux-hardware.org/?probe=e42254b8d8) | Feb 03, 2021 |
| Biostar       | Hi-Fi A70U3P                | [c2727e98b9](https://linux-hardware.org/?probe=c2727e98b9) | Feb 02, 2021 |
| Biostar       | Hi-Fi A70U3P                | [2c11d020c7](https://linux-hardware.org/?probe=2c11d020c7) | Feb 02, 2021 |
| ASUSTek       | B85M-G R2.0                 | [58b8c851c3](https://linux-hardware.org/?probe=58b8c851c3) | Feb 01, 2021 |
| HP            | 1493                        | [dd2e28d14d](https://linux-hardware.org/?probe=dd2e28d14d) | Feb 01, 2021 |
| Alienware     | 0PGRP5 A02                  | [c0f5f4e375](https://linux-hardware.org/?probe=c0f5f4e375) | Jan 29, 2021 |
| HP            | 806A                        | [b49db12f9f](https://linux-hardware.org/?probe=b49db12f9f) | Jan 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [40c599840d](https://linux-hardware.org/?probe=40c599840d) | Jan 28, 2021 |
| Gigabyte      | H61M-HD2                    | [78c877458a](https://linux-hardware.org/?probe=78c877458a) | Jan 28, 2021 |
| Intel         | DX58SO AAE29331-501         | [52cf72b2dd](https://linux-hardware.org/?probe=52cf72b2dd) | Jan 24, 2021 |
| Gigabyte      | H61M-HD2                    | [6caba093b5](https://linux-hardware.org/?probe=6caba093b5) | Jan 24, 2021 |
| MSI           | Boston                      | [7143ef66af](https://linux-hardware.org/?probe=7143ef66af) | Jan 24, 2021 |
| Dell          | 00V62H A00                  | [863c1d64fe](https://linux-hardware.org/?probe=863c1d64fe) | Jan 23, 2021 |
| HP            | 83F2                        | [8d5b4d0de9](https://linux-hardware.org/?probe=8d5b4d0de9) | Jan 23, 2021 |
| Foxconn       | ELVAS                       | [b816370786](https://linux-hardware.org/?probe=b816370786) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [3761191ef4](https://linux-hardware.org/?probe=3761191ef4) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [5446971c89](https://linux-hardware.org/?probe=5446971c89) | Jan 20, 2021 |
| Gigabyte      | J1800N-D2P                  | [adf2a9936f](https://linux-hardware.org/?probe=adf2a9936f) | Jan 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8c08ce4abd](https://linux-hardware.org/?probe=8c08ce4abd) | Jan 18, 2021 |
| Intel         | DQ965GF AAD41676-402        | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [11b7205a64](https://linux-hardware.org/?probe=11b7205a64) | Jan 12, 2021 |
| ECS           | A320AM4-M3D                 | [926f705d54](https://linux-hardware.org/?probe=926f705d54) | Jan 08, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [b5bfa0a8de](https://linux-hardware.org/?probe=b5bfa0a8de) | Jan 05, 2021 |
| Pegatron      | Benicia                     | [9ecfdb632f](https://linux-hardware.org/?probe=9ecfdb632f) | Jan 03, 2021 |
| Pegatron      | Benicia                     | [62518ac95a](https://linux-hardware.org/?probe=62518ac95a) | Jan 03, 2021 |
| ASUSTek       | NARRA2                      | [8668a91426](https://linux-hardware.org/?probe=8668a91426) | Jan 01, 2021 |
| PCChips       | P17G ECS                    | [67b674cb75](https://linux-hardware.org/?probe=67b674cb75) | Dec 30, 2020 |
| ASUSTek       | E410                        | [a876d4ba4c](https://linux-hardware.org/?probe=a876d4ba4c) | Dec 29, 2020 |
| ASUSTek       | E410                        | [f8c5b85250](https://linux-hardware.org/?probe=f8c5b85250) | Dec 26, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| Gigabyte      | F2A68HM-H                   | [bf18b5147a](https://linux-hardware.org/?probe=bf18b5147a) | Dec 23, 2020 |
| Gigabyte      | F2A68HM-H                   | [b0b75e82c7](https://linux-hardware.org/?probe=b0b75e82c7) | Dec 23, 2020 |
| ASUSTek       | M4A785T-M                   | [9ffb11ada9](https://linux-hardware.org/?probe=9ffb11ada9) | Dec 22, 2020 |
| ASUSTek       | M4A785T-M                   | [48cbf57838](https://linux-hardware.org/?probe=48cbf57838) | Dec 22, 2020 |
| ASUSTek       | PRIME B250M-A               | [1dc9ce743d](https://linux-hardware.org/?probe=1dc9ce743d) | Dec 18, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [5a0f4d7600](https://linux-hardware.org/?probe=5a0f4d7600) | Dec 18, 2020 |
| ASUSTek       | M2N32-SLI DELUXE            | [b1c0b6230d](https://linux-hardware.org/?probe=b1c0b6230d) | Dec 17, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [6e98a15118](https://linux-hardware.org/?probe=6e98a15118) | Dec 16, 2020 |
| ECS           | A320AM4-M3D                 | [aa3366e166](https://linux-hardware.org/?probe=aa3366e166) | Dec 15, 2020 |
| Intel         | DP45SG AAE27733-404         | [858605237b](https://linux-hardware.org/?probe=858605237b) | Dec 15, 2020 |
| Gigabyte      | M68M-S2                     | [2aa18660c1](https://linux-hardware.org/?probe=2aa18660c1) | Dec 13, 2020 |
| HP            | 1497                        | [29015e0a59](https://linux-hardware.org/?probe=29015e0a59) | Dec 13, 2020 |
| Lenovo        | NO DPK                      | [24dc6ea07a](https://linux-hardware.org/?probe=24dc6ea07a) | Dec 09, 2020 |
| Gigabyte      | B450M DS3H-CF               | [cc70d315c7](https://linux-hardware.org/?probe=cc70d315c7) | Dec 08, 2020 |
| ASUSTek       | A58M-K                      | [1efa7f7198](https://linux-hardware.org/?probe=1efa7f7198) | Dec 07, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [641d6711e7](https://linux-hardware.org/?probe=641d6711e7) | Dec 06, 2020 |
| Gigabyte      | H61M-DS2                    | [49263df7ee](https://linux-hardware.org/?probe=49263df7ee) | Dec 02, 2020 |
| Pegatron      | 2AC0                        | [f3064c4218](https://linux-hardware.org/?probe=f3064c4218) | Dec 01, 2020 |
| ECS           | A320AM4-M3D                 | [0066c9c0f1](https://linux-hardware.org/?probe=0066c9c0f1) | Nov 30, 2020 |
| Intel         | DG31PR AAD97573-301         | [bb174a40c5](https://linux-hardware.org/?probe=bb174a40c5) | Nov 29, 2020 |
| Gigabyte      | B450 GAMING X               | [fca90bec48](https://linux-hardware.org/?probe=fca90bec48) | Nov 29, 2020 |
| Gigabyte      | B450 GAMING X               | [0dbfa9ff7d](https://linux-hardware.org/?probe=0dbfa9ff7d) | Nov 28, 2020 |
| ECS           | A320AM4-M3D                 | [90490e92a3](https://linux-hardware.org/?probe=90490e92a3) | Nov 27, 2020 |
| Gigabyte      | H310M H                     | [1e05b28fdd](https://linux-hardware.org/?probe=1e05b28fdd) | Nov 27, 2020 |
| Wistron       | ProLiant ML110 G6           | [0a93b7c7a3](https://linux-hardware.org/?probe=0a93b7c7a3) | Nov 24, 2020 |
| PCChips       | P53G                        | [8149a46fad](https://linux-hardware.org/?probe=8149a46fad) | Nov 24, 2020 |
| Dell          | 0THJX5 A00                  | [8afcd02221](https://linux-hardware.org/?probe=8afcd02221) | Nov 24, 2020 |
| Dell          | 0T287N A03                  | [c769a7e787](https://linux-hardware.org/?probe=c769a7e787) | Nov 23, 2020 |
| Dell          | 0T287N A03                  | [f1b4344eb4](https://linux-hardware.org/?probe=f1b4344eb4) | Nov 23, 2020 |
| Dell          | 0THJX5 A00                  | [c545287894](https://linux-hardware.org/?probe=c545287894) | Nov 23, 2020 |
| Gigabyte      | MFLP3IP-00                  | [db3aeae143](https://linux-hardware.org/?probe=db3aeae143) | Nov 21, 2020 |
| MSI           | Boston                      | [6b30dd9ff7](https://linux-hardware.org/?probe=6b30dd9ff7) | Nov 21, 2020 |
| Dell          | 0THJX5 A00                  | [f2f5b654ee](https://linux-hardware.org/?probe=f2f5b654ee) | Nov 21, 2020 |
| HP            | 3032h                       | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Dell          | 0PU052                      | [17818ae6d5](https://linux-hardware.org/?probe=17818ae6d5) | Nov 18, 2020 |
| ASUSTek       | PRIME B450M-A               | [fe00092f17](https://linux-hardware.org/?probe=fe00092f17) | Nov 15, 2020 |
| ASUSTek       | PRIME B450M-A               | [f40c1b6361](https://linux-hardware.org/?probe=f40c1b6361) | Nov 13, 2020 |
| Dell          | 0ND237                      | [b03fba236c](https://linux-hardware.org/?probe=b03fba236c) | Nov 08, 2020 |
| ASUSTek       | PRIME A320I-K               | [6bfc04099a](https://linux-hardware.org/?probe=6bfc04099a) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | [ac6556242f](https://linux-hardware.org/?probe=ac6556242f) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | [56d223bda7](https://linux-hardware.org/?probe=56d223bda7) | Nov 06, 2020 |
| Dell          | 0ND237                      | [2ee8528114](https://linux-hardware.org/?probe=2ee8528114) | Nov 05, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 96       | 10.65%  |
| Ubuntu 22.04        | 58       | 6.44%   |
| Ubuntu 18.04        | 53       | 5.88%   |
| OpenMandriva 4.2    | 42       | 4.66%   |
| OpenMandriva 4.3    | 37       | 4.11%   |
| Debian 11           | 26       | 2.89%   |
| Fedora 38           | 19       | 2.11%   |
| ArcoLinux Rolling   | 19       | 2.11%   |
| Zorin 16            | 18       | 2%      |
| Debian 12           | 15       | 1.66%   |
| Pop!_OS 22.04       | 12       | 1.33%   |
| OpenMandriva 23.08  | 12       | 1.33%   |
| OpenMandriva 23.01  | 12       | 1.33%   |
| Arch Rolling        | 12       | 1.33%   |
| Arch                | 12       | 1.33%   |
| OpenMandriva 23.03  | 11       | 1.22%   |
| Linux Mint 20.3     | 11       | 1.22%   |
| Linux Mint 20.2     | 11       | 1.22%   |
| Fedora 35           | 10       | 1.11%   |
| Pop!_OS 20.04       | 9        | 1%      |
| Linux Mint 21.2     | 9        | 1%      |
| KDE neon 20.04      | 9        | 1%      |
| Ubuntu 21.10        | 8        | 0.89%   |
| Manjaro             | 8        | 0.89%   |
| Fedora 36           | 8        | 0.89%   |
| Zorin 15            | 7        | 0.78%   |
| Ubuntu 20.10        | 7        | 0.78%   |
| ROSA R10            | 7        | 0.78%   |
| Linux Mint 21.1     | 7        | 0.78%   |
| KDE neon 22.04      | 7        | 0.78%   |
| EndeavourOS Rolling | 7        | 0.78%   |
| Xubuntu 20.04       | 6        | 0.67%   |
| Ubuntu 19.10        | 6        | 0.67%   |
| Ubuntu 18.10        | 6        | 0.67%   |
| Pop!_OS 21.04       | 6        | 0.67%   |
| Linux Mint 21       | 6        | 0.67%   |
| Linux Mint 20       | 6        | 0.67%   |
| Linux Mint 19.3     | 6        | 0.67%   |
| Fedora 33           | 6        | 0.67%   |
| ROSA R9             | 5        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 246      | 28.64%  |
| OpenMandriva  | 120      | 13.97%  |
| Linux Mint    | 64       | 7.45%   |
| Fedora        | 54       | 6.29%   |
| Debian        | 46       | 5.36%   |
| Pop!_OS       | 30       | 3.49%   |
| ROSA          | 29       | 3.38%   |
| Zorin         | 27       | 3.14%   |
| Endless       | 26       | 3.03%   |
| Manjaro       | 25       | 2.91%   |
| Arch          | 24       | 2.79%   |
| ArcoLinux     | 19       | 2.21%   |
| Xubuntu       | 15       | 1.75%   |
| KDE neon      | 14       | 1.63%   |
| Kubuntu       | 11       | 1.28%   |
| openSUSE      | 10       | 1.16%   |
| Elementary    | 9        | 1.05%   |
| EndeavourOS   | 8        | 0.93%   |
| Nobara        | 7        | 0.81%   |
| Kali          | 5        | 0.58%   |
| Gentoo        | 5        | 0.58%   |
| Xero          | 4        | 0.47%   |
| Ubuntu MATE   | 4        | 0.47%   |
| Ubuntu Budgie | 4        | 0.47%   |
| Lubuntu       | 4        | 0.47%   |
| Linux Lite    | 4        | 0.47%   |
| Ubuntu Unity  | 3        | 0.35%   |
| Parrot        | 3        | 0.35%   |
| MX            | 3        | 0.35%   |
| LMDE          | 3        | 0.35%   |
| Peppermint    | 2        | 0.23%   |
| Garuda Linux  | 2        | 0.23%   |
| Deepin        | 2        | 0.23%   |
| Clear Linux   | 2        | 0.23%   |
| CentOS        | 2        | 0.23%   |
| blendOS       | 2        | 0.23%   |
| BigLinux      | 2        | 0.23%   |
| Archcraft     | 2        | 0.23%   |
| UbuntuDDE     | 1        | 0.12%   |
| Ubuntu Studio | 1        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 42       | 4.22%   |
| 5.16.7-desktop-1omv4003         | 30       | 3.02%   |
| 5.8.0-14-generic                | 12       | 1.21%   |
| 5.4.0-42-generic                | 12       | 1.21%   |
| 6.1.1-desktop-1omv2290          | 11       | 1.11%   |
| 6.4.11-desktop-1omv2390         | 10       | 1.01%   |
| 6.2.6-desktop-1omv2390          | 9        | 0.9%    |
| 5.4.0-58-generic                | 8        | 0.8%    |
| 5.4.0-40-generic                | 8        | 0.8%    |
| 5.3.0-40-generic                | 8        | 0.8%    |
| 5.16.13-desktop-1omv4003        | 8        | 0.8%    |
| 5.15.0-58-generic               | 8        | 0.8%    |
| 5.15.0-56-generic               | 8        | 0.8%    |
| 6.1.0-13-amd64                  | 7        | 0.7%    |
| 5.4.0-54-generic                | 7        | 0.7%    |
| 5.15.0-47-generic               | 7        | 0.7%    |
| 5.4.0-48-generic                | 6        | 0.6%    |
| 5.19.0-35-generic               | 6        | 0.6%    |
| 5.15.0-52-generic               | 6        | 0.6%    |
| 5.11.0-37-generic               | 6        | 0.6%    |
| 5.11.0-27-generic               | 6        | 0.6%    |
| 6.2.6-76060206-generic          | 5        | 0.5%    |
| 6.2.0-26-generic                | 5        | 0.5%    |
| 5.8.0-53-generic                | 5        | 0.5%    |
| 5.4.0-91-generic                | 5        | 0.5%    |
| 5.4.0-77-generic                | 5        | 0.5%    |
| 5.4.0-65-generic                | 5        | 0.5%    |
| 5.4.0-39-generic                | 5        | 0.5%    |
| 5.4.0-37-generic                | 5        | 0.5%    |
| 5.4.0-33-generic                | 5        | 0.5%    |
| 5.4.0-19-generic                | 5        | 0.5%    |
| 5.19.0-32-generic               | 5        | 0.5%    |
| 5.15.0-76-generic               | 5        | 0.5%    |
| 5.11.0-38-generic               | 5        | 0.5%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 5        | 0.5%    |
| 6.2.0-37-generic                | 4        | 0.4%    |
| 6.2.0-32-generic                | 4        | 0.4%    |
| 5.8.0-63-generic                | 4        | 0.4%    |
| 5.8.0-50-generic                | 4        | 0.4%    |
| 5.4.0-81-generic                | 4        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 129      | 13.77%  |
| 5.15.0  | 71       | 7.58%   |
| 5.10.14 | 42       | 4.48%   |
| 5.11.0  | 41       | 4.38%   |
| 4.15.0  | 41       | 4.38%   |
| 5.8.0   | 39       | 4.16%   |
| 5.13.0  | 34       | 3.63%   |
| 5.3.0   | 33       | 3.52%   |
| 5.16.7  | 30       | 3.2%    |
| 5.10.0  | 28       | 2.99%   |
| 6.2.0   | 25       | 2.67%   |
| 5.19.0  | 24       | 2.56%   |
| 4.18.0  | 18       | 1.92%   |
| 6.1.0   | 17       | 1.81%   |
| 6.2.6   | 14       | 1.49%   |
| 6.4.11  | 12       | 1.28%   |
| 6.1.1   | 12       | 1.28%   |
| 5.0.0   | 12       | 1.28%   |
| 5.16.13 | 9        | 0.96%   |
| 6.5.5   | 7        | 0.75%   |
| 6.5.0   | 7        | 0.75%   |
| 4.9.20  | 5        | 0.53%   |
| 4.19.0  | 5        | 0.53%   |
| 6.6.2   | 4        | 0.43%   |
| 6.4.9   | 4        | 0.43%   |
| 6.4.8   | 4        | 0.43%   |
| 6.4.12  | 4        | 0.43%   |
| 6.4.10  | 4        | 0.43%   |
| 6.3.5   | 4        | 0.43%   |
| 6.0.12  | 4        | 0.43%   |
| 6.0.0   | 4        | 0.43%   |
| 5.9.16  | 4        | 0.43%   |
| 5.11.12 | 4        | 0.43%   |
| 6.5.6   | 3        | 0.32%   |
| 6.4.4   | 3        | 0.32%   |
| 6.3.9   | 3        | 0.32%   |
| 6.2.14  | 3        | 0.32%   |
| 6.2.11  | 3        | 0.32%   |
| 6.0.9   | 3        | 0.32%   |
| 6.0.16  | 3        | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 140      | 15.15%  |
| 5.15    | 90       | 9.74%   |
| 5.10    | 79       | 8.55%   |
| 6.2     | 54       | 5.84%   |
| 5.11    | 49       | 5.3%    |
| 5.16    | 48       | 5.19%   |
| 5.8     | 45       | 4.87%   |
| 4.15    | 41       | 4.44%   |
| 6.1     | 39       | 4.22%   |
| 5.3     | 39       | 4.22%   |
| 5.13    | 39       | 4.22%   |
| 6.4     | 37       | 4%      |
| 5.19    | 33       | 3.57%   |
| 6.5     | 24       | 2.6%    |
| 6.0     | 21       | 2.27%   |
| 4.18    | 19       | 2.06%   |
| 6.3     | 13       | 1.41%   |
| 5.0     | 13       | 1.41%   |
| 4.9     | 13       | 1.41%   |
| 6.6     | 12       | 1.3%    |
| 5.18    | 10       | 1.08%   |
| 5.9     | 9        | 0.97%   |
| 5.14    | 9        | 0.97%   |
| 4.19    | 8        | 0.87%   |
| 5.7     | 7        | 0.76%   |
| 5.12    | 7        | 0.76%   |
| 5.17    | 6        | 0.65%   |
| 5.6     | 5        | 0.54%   |
| 4.1     | 3        | 0.32%   |
| 5.5     | 2        | 0.22%   |
| 5.2     | 2        | 0.22%   |
| 4.4     | 2        | 0.22%   |
| 4.12    | 2        | 0.22%   |
| 6.7     | 1        | 0.11%   |
| 4.20    | 1        | 0.11%   |
| 4.10    | 1        | 0.11%   |
| 3.10    | 1        | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 804      | 96.87%  |
| i686   | 26       | 3.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 359      | 41.31%  |
| KDE5             | 205      | 23.59%  |
| Unknown          | 68       | 7.83%   |
| XFCE             | 63       | 7.25%   |
| X-Cinnamon       | 45       | 5.18%   |
| MATE             | 31       | 3.57%   |
| Cinnamon         | 19       | 2.19%   |
| KDE4             | 17       | 1.96%   |
| KDE              | 17       | 1.96%   |
| Pantheon         | 8        | 0.92%   |
| LXQt             | 6        | 0.69%   |
| Budgie           | 6        | 0.69%   |
| LXDE             | 5        | 0.58%   |
| Unity            | 3        | 0.35%   |
| Deepin           | 3        | 0.35%   |
| qtile            | 2        | 0.23%   |
| lightdm-xsession | 2        | 0.23%   |
| Hyprland         | 2        | 0.23%   |
| GNOME Flashback  | 2        | 0.23%   |
| awesome          | 2        | 0.23%   |
| trinity          | 1        | 0.12%   |
| i3               | 1        | 0.12%   |
| GNOME Classic    | 1        | 0.12%   |
| chadwm           | 1        | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 642      | 74.65%  |
| Wayland | 170      | 19.77%  |
| Unknown | 42       | 4.88%   |
| Tty     | 6        | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 401      | 46.57%  |
| SDDM    | 177      | 20.56%  |
| GDM3    | 103      | 11.96%  |
| LightDM | 89       | 10.34%  |
| GDM     | 53       | 6.16%   |
| KDM     | 18       | 2.09%   |
| TDM     | 16       | 1.86%   |
| SLiM    | 2        | 0.23%   |
| NODM    | 1        | 0.12%   |
| LXDM    | 1        | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| es_MX      | 422      | 49.13%  |
| en_US      | 282      | 32.83%  |
| Unknown    | 76       | 8.85%   |
| es_ES      | 58       | 6.75%   |
| C          | 11       | 1.28%   |
| en_GB      | 3        | 0.35%   |
| es_US      | 2        | 0.23%   |
| en_CA      | 2        | 0.23%   |
| POSIX      | 1        | 0.12%   |
| en_US.UTF8 | 1        | 0.12%   |
| Default    | 1        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 541      | 64.18%  |
| EFI  | 302      | 35.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 617      | 72.5%   |
| Overlay  | 97       | 11.4%   |
| Btrfs    | 66       | 7.76%   |
| Tmpfs    | 28       | 3.29%   |
| Unknown  | 27       | 3.17%   |
| Xfs      | 5        | 0.59%   |
| Zfs      | 3        | 0.35%   |
| Reiserfs | 3        | 0.35%   |
| Ext2     | 3        | 0.35%   |
| F2fs     | 2        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 444      | 52.48%  |
| GPT     | 281      | 33.22%  |
| MBR     | 121      | 14.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 697      | 82.29%  |
| Yes       | 150      | 17.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 541      | 63.8%   |
| Yes       | 307      | 36.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Gigabyte Technology   | 184      | 22.17%  |
| ASUSTek Computer      | 172      | 20.72%  |
| Dell                  | 99       | 11.93%  |
| Hewlett-Packard       | 87       | 10.48%  |
| ASRock                | 40       | 4.82%   |
| MSI                   | 36       | 4.34%   |
| Lenovo                | 32       | 3.86%   |
| ECS                   | 32       | 3.86%   |
| Intel                 | 30       | 3.61%   |
| Biostar               | 29       | 3.49%   |
| Pegatron              | 18       | 2.17%   |
| Acer                  | 11       | 1.33%   |
| PCChips               | 9        | 1.08%   |
| Lanix                 | 7        | 0.84%   |
| Foxconn               | 7        | 0.84%   |
| Unknown               | 5        | 0.6%    |
| eMachines             | 4        | 0.48%   |
| Alienware             | 4        | 0.48%   |
| TPV-INVENTA           | 3        | 0.36%   |
| AZW                   | 3        | 0.36%   |
| Wistron               | 2        | 0.24%   |
| Quanta                | 2        | 0.24%   |
| VIA Technologies      | 1        | 0.12%   |
| Toshiba               | 1        | 0.12%   |
| System76              | 1        | 0.12%   |
| OEM                   | 1        | 0.12%   |
| NZXT                  | 1        | 0.12%   |
| NEC Infrontia         | 1        | 0.12%   |
| ICP / iEi             | 1        | 0.12%   |
| IBM                   | 1        | 0.12%   |
| HC                    | 1        | 0.12%   |
| Google                | 1        | 0.12%   |
| GMKtec                | 1        | 0.12%   |
| ASUSTeK_COMPUTER_INC. | 1        | 0.12%   |
| ASRockRack            | 1        | 0.12%   |
| Apple                 | 1        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME A320M-K              | 20       | 2.41%   |
| ASUS All Series                 | 12       | 1.45%   |
| Gigabyte B450M DS3H             | 9        | 1.08%   |
| Dell OptiPlex 7010              | 8        | 0.96%   |
| ECS A320AM4-M3D                 | 7        | 0.84%   |
| Dell OptiPlex 9020              | 7        | 0.84%   |
| Dell OptiPlex 745               | 7        | 0.84%   |
| ASUS PRIME B450M-A II           | 7        | 0.84%   |
| HP Compaq 6200 Pro SFF PC       | 6        | 0.72%   |
| Gigabyte GA-880GM-USB3          | 6        | 0.72%   |
| Gigabyte A320M-S2H              | 6        | 0.72%   |
| ASUS ROG STRIX B450-F GAMING    | 6        | 0.72%   |
| Dell OptiPlex 790               | 5        | 0.6%    |
| Dell OptiPlex 755               | 5        | 0.6%    |
| Dell Inspiron 3647              | 5        | 0.6%    |
| Biostar B450MH                  | 5        | 0.6%    |
| Biostar A10N-8800E              | 5        | 0.6%    |
| ASUS PRIME B550M-A AC           | 5        | 0.6%    |
| ASUS M5A78L-M PLUS/USB3         | 5        | 0.6%    |
| Unknown                         | 5        | 0.6%    |
| Gigabyte B550M AORUS ELITE      | 4        | 0.48%   |
| Gigabyte A320M-S2H V2           | 4        | 0.48%   |
| Dell OptiPlex 990               | 4        | 0.48%   |
| Dell OptiPlex 3010              | 4        | 0.48%   |
| ASUS ROG STRIX X570-E GAMING    | 4        | 0.48%   |
| ASUS PRIME B450M-A              | 4        | 0.48%   |
| Alienware X51 R2                | 4        | 0.48%   |
| Pegatron KN278AA-ABM a6430la    | 3        | 0.36%   |
| PCChips P17G                    | 3        | 0.36%   |
| Lenovo ThinkCentre M91p 4524CB9 | 3        | 0.36%   |
| Lanix MINI-TORRE                | 3        | 0.36%   |
| HP Z420 Workstation             | 3        | 0.36%   |
| HP ProDesk 600 G1 SFF           | 3        | 0.36%   |
| HP Compaq Pro 6305 SFF          | 3        | 0.36%   |
| HP Compaq 8200 Elite SFF PC     | 3        | 0.36%   |
| Gigabyte X570 AORUS PRO WIFI    | 3        | 0.36%   |
| Gigabyte H81M-H                 | 3        | 0.36%   |
| Gigabyte H61M-DS2               | 3        | 0.36%   |
| Gigabyte H310M H 2.0            | 3        | 0.36%   |
| Gigabyte H110M-H                | 3        | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 68       | 8.19%   |
| Dell OptiPlex          | 64       | 7.71%   |
| HP Compaq              | 34       | 4.1%    |
| Lenovo ThinkCentre     | 28       | 3.37%   |
| ASUS ROG               | 22       | 2.65%   |
| Dell Inspiron          | 16       | 1.93%   |
| HP ProDesk             | 12       | 1.45%   |
| Gigabyte B450M         | 12       | 1.45%   |
| ASUS TUF               | 12       | 1.45%   |
| ASUS All               | 12       | 1.45%   |
| Gigabyte A320M-S2H     | 10       | 1.2%    |
| Acer Aspire            | 10       | 1.2%    |
| Gigabyte X570          | 9        | 1.08%   |
| Dell Precision         | 9        | 1.08%   |
| ASUS M5A78L-M          | 9        | 1.08%   |
| HP EliteDesk           | 8        | 0.96%   |
| Gigabyte B550M         | 8        | 0.96%   |
| Gigabyte B450          | 7        | 0.84%   |
| ECS A320AM4-M3D        | 7        | 0.84%   |
| ASUS M5A97             | 7        | 0.84%   |
| Gigabyte GA-880GM-USB3 | 6        | 0.72%   |
| Gigabyte H410M         | 5        | 0.6%    |
| Gigabyte H310M         | 5        | 0.6%    |
| Gigabyte G1.Sniper     | 5        | 0.6%    |
| Biostar B450MH         | 5        | 0.6%    |
| Biostar A10N-8800E     | 5        | 0.6%    |
| Unknown                | 5        | 0.6%    |
| Gigabyte Z390          | 4        | 0.48%   |
| Gigabyte H61M-DS2      | 4        | 0.48%   |
| Gigabyte H110M-H       | 4        | 0.48%   |
| ASRock B450M           | 4        | 0.48%   |
| Alienware X51          | 4        | 0.48%   |
| Pegatron KN278AA-ABM   | 3        | 0.36%   |
| Pegatron Compaq        | 3        | 0.36%   |
| PCChips P17G           | 3        | 0.36%   |
| Lanix TITAN            | 3        | 0.36%   |
| Lanix MINI-TORRE       | 3        | 0.36%   |
| Intel DH67BL           | 3        | 0.36%   |
| HP Z420                | 3        | 0.36%   |
| HP ProLiant            | 3        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 87       | 10.48%  |
| 2018 | 83       | 10%     |
| 2011 | 78       | 9.4%    |
| 2017 | 62       | 7.47%   |
| 2009 | 59       | 7.11%   |
| 2013 | 55       | 6.63%   |
| 2020 | 54       | 6.51%   |
| 2019 | 47       | 5.66%   |
| 2010 | 45       | 5.42%   |
| 2014 | 44       | 5.3%    |
| 2016 | 38       | 4.58%   |
| 2007 | 35       | 4.22%   |
| 2021 | 34       | 4.1%    |
| 2015 | 33       | 3.98%   |
| 2008 | 27       | 3.25%   |
| 2022 | 17       | 2.05%   |
| 2006 | 17       | 2.05%   |
| 2005 | 8        | 0.96%   |
| 2023 | 6        | 0.72%   |
| 2003 | 1        | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 830      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 815      | 98.07%  |
| Enabled  | 16       | 1.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 829      | 99.88%  |
| Yes  | 1        | 0.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 181      | 21.32%  |
| 3.01-4.0        | 171      | 20.14%  |
| 8.01-16.0       | 168      | 19.79%  |
| 16.01-24.0      | 132      | 15.55%  |
| 32.01-64.0      | 90       | 10.6%   |
| 1.01-2.0        | 34       | 4%      |
| 24.01-32.0      | 27       | 3.18%   |
| 64.01-256.0     | 24       | 2.83%   |
| 2.01-3.0        | 15       | 1.77%   |
| 0.51-1.0        | 4        | 0.47%   |
| More than 256.0 | 1        | 0.12%   |
| 0.01-0.5        | 1        | 0.12%   |
| Unknown         | 1        | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 333      | 36.35%  |
| 2.01-3.0    | 226      | 24.67%  |
| 4.01-8.0    | 117      | 12.77%  |
| 3.01-4.0    | 110      | 12.01%  |
| 0.51-1.0    | 64       | 6.99%   |
| 8.01-16.0   | 46       | 5.02%   |
| 0.01-0.5    | 7        | 0.76%   |
| 16.01-24.0  | 6        | 0.66%   |
| 24.01-32.0  | 4        | 0.44%   |
| 32.01-64.0  | 1        | 0.11%   |
| 64.01-256.0 | 1        | 0.11%   |
| Unknown     | 1        | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 418      | 47.94%  |
| 2       | 243      | 27.87%  |
| 3       | 110      | 12.61%  |
| 4       | 52       | 5.96%   |
| 5       | 18       | 2.06%   |
| 6       | 13       | 1.49%   |
| 0       | 12       | 1.38%   |
| 7       | 4        | 0.46%   |
| 8       | 1        | 0.11%   |
| Unknown | 1        | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 490      | 58.33%  |
| Yes       | 350      | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 822      | 99.04%  |
| No        | 8        | 0.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 424      | 50.36%  |
| Yes       | 418      | 49.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 612      | 72.68%  |
| Yes       | 230      | 27.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Mexico  | 830      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Mexico City           | 166      | 18.71%  |
| Guadalajara           | 52       | 5.86%   |
| Tijuana               | 35       | 3.95%   |
| Monterrey             | 30       | 3.38%   |
| Zapopan               | 28       | 3.16%   |
| Mérida               | 20       | 2.25%   |
| Hermosillo            | 17       | 1.92%   |
| Queretaro             | 16       | 1.8%    |
| Morelia               | 16       | 1.8%    |
| Tlalnepantla          | 15       | 1.69%   |
| Puebla City           | 14       | 1.58%   |
| Ciudad Juárez        | 13       | 1.47%   |
| San Luis Potosí City | 12       | 1.35%   |
| Chihuahua City        | 12       | 1.35%   |
| Ciudad Nezahualcoyotl | 11       | 1.24%   |
| Mexicali              | 10       | 1.13%   |
| Cuernavaca            | 10       | 1.13%   |
| Cancún               | 10       | 1.13%   |
| Querétaro City       | 9        | 1.01%   |
| Oaxaca City           | 9        | 1.01%   |
| Naucalpan             | 9        | 1.01%   |
| Ecatepec              | 9        | 1.01%   |
| Culiacán             | 9        | 1.01%   |
| Apodaca               | 9        | 1.01%   |
| Toluca                | 8        | 0.9%    |
| Gustavo Adolfo Madero | 8        | 0.9%    |
| Tuxtla Gutiérrez     | 7        | 0.79%   |
| Mexico                | 7        | 0.79%   |
| León                 | 7        | 0.79%   |
| Iztapalapa            | 7        | 0.79%   |
| Guadalupe             | 7        | 0.79%   |
| Ciudad Obregón       | 7        | 0.79%   |
| Aguascalientes        | 7        | 0.79%   |
| Saltillo              | 6        | 0.68%   |
| Pachuca               | 6        | 0.68%   |
| Ensenada              | 6        | 0.68%   |
| Zacatecas City        | 5        | 0.56%   |
| Villahermosa          | 5        | 0.56%   |
| Torreón              | 5        | 0.56%   |
| Tepic                 | 5        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 321      | 494    | 23.43%  |
| WDC                         | 284      | 404    | 20.73%  |
| Kingston                    | 152      | 215    | 11.09%  |
| A-DATA Technology           | 116      | 149    | 8.47%   |
| Toshiba                     | 90       | 111    | 6.57%   |
| Hitachi                     | 81       | 116    | 5.91%   |
| Samsung Electronics         | 58       | 74     | 4.23%   |
| Crucial                     | 19       | 30     | 1.39%   |
| XPG                         | 18       | 21     | 1.31%   |
| Sandisk                     | 18       | 24     | 1.31%   |
| Unknown                     | 15       | 23     | 1.09%   |
| PNY                         | 15       | 20     | 1.09%   |
| Intel                       | 14       | 24     | 1.02%   |
| HGST                        | 13       | 22     | 0.95%   |
| Realtek Semiconductor       | 12       | 17     | 0.88%   |
| Fujitsu                     | 11       | 15     | 0.8%    |
| Maxtor                      | 10       | 12     | 0.73%   |
| Kingston Technology Company | 9        | 9      | 0.66%   |
| SK hynix                    | 8        | 16     | 0.58%   |
| Acer                        | 8        | 10     | 0.58%   |
| ADATA Technology            | 7        | 8      | 0.51%   |
| Micron/Crucial Technology   | 6        | 9      | 0.44%   |
| Hewlett-Packard             | 6        | 6      | 0.44%   |
| Phison                      | 5        | 6      | 0.36%   |
| Micron Technology           | 5        | 9      | 0.36%   |
| Gigabyte Technology         | 5        | 6      | 0.36%   |
| China                       | 5        | 6      | 0.36%   |
| Phison Electronics          | 4        | 4      | 0.29%   |
| Patriot                     | 4        | 5      | 0.29%   |
| SPCC                        | 3        | 3      | 0.22%   |
| MAXIO Technology (Hangzhou) | 3        | 3      | 0.22%   |
| Yeyian                      | 2        | 2      | 0.15%   |
| USB3.0                      | 2        | 2      | 0.15%   |
| Transcend                   | 2        | 2      | 0.15%   |
| Quaroni                     | 2        | 2      | 0.15%   |
| Lexar                       | 2        | 2      | 0.15%   |
| JMicron Technology          | 2        | 2      | 0.15%   |
| HS-SSD-C100                 | 2        | 3      | 0.15%   |
| Corsair                     | 2        | 2      | 0.15%   |
| Apple                       | 2        | 2      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 49       | 3.17%   |
| Seagate ST500DM002-1BD142 500GB  | 37       | 2.39%   |
| Kingston SA400S37480G 480GB SSD  | 31       | 2%      |
| A-DATA SU650 120GB SSD           | 26       | 1.68%   |
| Seagate ST1000DM010-2EP102 1TB   | 23       | 1.49%   |
| Kingston SA400S37120G 120GB SSD  | 17       | 1.1%    |
| A-DATA SU630 240GB SSD           | 16       | 1.03%   |
| Toshiba DT01ACA100 1TB           | 14       | 0.9%    |
| Toshiba DT01ACA050 500GB         | 13       | 0.84%   |
| Seagate ST3500418AS 500GB        | 13       | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB   | 13       | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 12       | 0.78%   |
| Toshiba DT01ACA200 2TB           | 11       | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB   | 11       | 0.71%   |
| A-DATA SU630 480GB SSD           | 11       | 0.71%   |
| WDC WD10EZEX-08WN4A0 1TB         | 10       | 0.65%   |
| Toshiba MQ01ABD100 1TB           | 10       | 0.65%   |
| Seagate ST3160815AS 160GB        | 10       | 0.65%   |
| A-DATA SU650 240GB SSD           | 10       | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB   | 9        | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB   | 9        | 0.58%   |
| Seagate ST1000DM003-1SB102 1TB   | 9        | 0.58%   |
| Seagate ST31000524AS 1TB         | 8        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB   | 8        | 0.52%   |
| Kingston SV300S37A120G 120GB SSD | 8        | 0.52%   |
| XPG GAMMIX S11 Pro 256GB         | 7        | 0.45%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 7        | 0.45%   |
| WDC WD10EZEX-75M2NA0 1TB         | 7        | 0.45%   |
| Seagate ST2000DL003-9VT166 2TB   | 7        | 0.45%   |
| Kingston SA400S37960G 960GB SSD  | 7        | 0.45%   |
| XPG SPECTRIX S40G 1TB            | 6        | 0.39%   |
| WDC WD10EZEX-08M2NA0 1TB         | 6        | 0.39%   |
| Seagate ST500LT012-9WS142 500GB  | 6        | 0.39%   |
| Seagate ST380815AS 80GB          | 6        | 0.39%   |
| Seagate ST3500414CS 500GB        | 6        | 0.39%   |
| Seagate ST31000528AS 1TB         | 6        | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB   | 6        | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB   | 6        | 0.39%   |
| Seagate ST1000DM003-9YN162 1TB   | 6        | 0.39%   |
| PNY CS900 120GB SSD              | 6        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 320      | 493    | 39.46%  |
| WDC                 | 252      | 349    | 31.07%  |
| Toshiba             | 90       | 111    | 11.1%   |
| Hitachi             | 81       | 116    | 9.99%   |
| Samsung Electronics | 20       | 23     | 2.47%   |
| HGST                | 13       | 22     | 1.6%    |
| Fujitsu             | 11       | 15     | 1.36%   |
| Maxtor              | 10       | 12     | 1.23%   |
| Unknown             | 5        | 6      | 0.62%   |
| USB3.0              | 2        | 2      | 0.25%   |
| Apple               | 2        | 2      | 0.25%   |
| QUANTUM             | 1        | 2      | 0.12%   |
| MaxDigital          | 1        | 4      | 0.12%   |
| HPE                 | 1        | 1      | 0.12%   |
| Hewlett-Packard     | 1        | 1      | 0.12%   |
| External            | 1        | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 138      | 187    | 33.66%  |
| A-DATA Technology   | 105      | 137    | 25.61%  |
| WDC                 | 39       | 51     | 9.51%   |
| Samsung Electronics | 21       | 27     | 5.12%   |
| Crucial             | 17       | 24     | 4.15%   |
| PNY                 | 15       | 20     | 3.66%   |
| Acer                | 7        | 8      | 1.71%   |
| SanDisk             | 6        | 7      | 1.46%   |
| Intel               | 6        | 7      | 1.46%   |
| SK hynix            | 5        | 13     | 1.22%   |
| Hewlett-Packard     | 5        | 5      | 1.22%   |
| China               | 5        | 6      | 1.22%   |
| Patriot             | 4        | 5      | 0.98%   |
| Micron Technology   | 4        | 6      | 0.98%   |
| Gigabyte Technology | 4        | 5      | 0.98%   |
| SPCC                | 3        | 3      | 0.73%   |
| Yeyian              | 2        | 2      | 0.49%   |
| Transcend           | 2        | 2      | 0.49%   |
| Quaroni             | 2        | 2      | 0.49%   |
| Lexar               | 2        | 2      | 0.49%   |
| VERICO              | 1        | 1      | 0.24%   |
| VALK                | 1        | 1      | 0.24%   |
| Unknown             | 1        | 1      | 0.24%   |
| Timetec             | 1        | 1      | 0.24%   |
| Team                | 1        | 1      | 0.24%   |
| SABRENT             | 1        | 1      | 0.24%   |
| OCZ                 | 1        | 1      | 0.24%   |
| Netac               | 1        | 2      | 0.24%   |
| MSI                 | 1        | 1      | 0.24%   |
| Londisk             | 1        | 1      | 0.24%   |
| LITEON              | 1        | 1      | 0.24%   |
| Lite-On             | 1        | 3      | 0.24%   |
| JMicron Technology  | 1        | 1      | 0.24%   |
| HS-SSD-C100         | 1        | 1      | 0.24%   |
| Corsair             | 1        | 1      | 0.24%   |
| Blackpcs            | 1        | 1      | 0.24%   |
| AS201               | 1        | 1      | 0.24%   |
| Apacer              | 1        | 1      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 640      | 1160   | 56.04%  |
| SSD     | 355      | 540    | 31.09%  |
| NVMe    | 134      | 205    | 11.73%  |
| Unknown | 12       | 23     | 1.05%   |
| MMC     | 1        | 1      | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 777      | 1667   | 81.45%  |
| NVMe | 134      | 204    | 14.05%  |
| SAS  | 42       | 57     | 4.4%    |
| MMC  | 1        | 1      | 0.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 612      | 1056   | 58.23%  |
| 0.51-1.0   | 270      | 394    | 25.69%  |
| 1.01-2.0   | 102      | 140    | 9.71%   |
| 3.01-4.0   | 32       | 63     | 3.04%   |
| 2.01-3.0   | 24       | 33     | 2.28%   |
| 4.01-10.0  | 11       | 14     | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 196      | 21.97%  |
| 251-500        | 182      | 20.4%   |
| 501-1000       | 131      | 14.69%  |
| 1001-2000      | 97       | 10.87%  |
| 1-20           | 78       | 8.74%   |
| 51-100         | 63       | 7.06%   |
| More than 3000 | 50       | 5.61%   |
| 21-50          | 39       | 4.37%   |
| 2001-3000      | 31       | 3.48%   |
| Unknown        | 25       | 2.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 350      | 38.13%  |
| 21-50          | 156      | 16.99%  |
| 51-100         | 97       | 10.57%  |
| 101-250        | 95       | 10.35%  |
| 501-1000       | 62       | 6.75%   |
| 251-500        | 61       | 6.64%   |
| 1001-2000      | 45       | 4.9%    |
| Unknown        | 25       | 2.72%   |
| More than 3000 | 18       | 1.96%   |
| 2001-3000      | 9        | 0.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB       | 3        | 3      | 2.19%   |
| Seagate ST3160815AS 160GB       | 3        | 3      | 2.19%   |
| Seagate ST2000DL003-9VT166 2TB  | 3        | 3      | 2.19%   |
| WDC WD3200AAJS-00YZCA0 320GB    | 2        | 3      | 1.46%   |
| Toshiba MQ04ABF100 1TB          | 2        | 2      | 1.46%   |
| Toshiba MQ01ABD100 1TB          | 2        | 2      | 1.46%   |
| Toshiba DT01ACA100 1TB          | 2        | 2      | 1.46%   |
| Seagate ST9500420AS 500GB       | 2        | 2      | 1.46%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 2      | 1.46%   |
| Seagate ST31000524AS 1TB        | 2        | 4      | 1.46%   |
| Seagate ST1500DL003-9VT16L 1TB  | 2        | 2      | 1.46%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 2      | 1.46%   |
| Seagate ST1000DM003-9YN162 1TB  | 2        | 2      | 1.46%   |
| Maxtor 6Y080M0 82GB             | 2        | 2      | 1.46%   |
| Hitachi HUA722020ALA331 2TB     | 2        | 2      | 1.46%   |
| Hitachi HDS721010CLA332 1TB     | 2        | 2      | 1.46%   |
| HGST HTS545050A7E380 500GB      | 2        | 3      | 1.46%   |
| WDC WD800JD-00MSA1 80GB         | 1        | 1      | 0.73%   |
| WDC WD6400BEVT-60A0RT0 640GB    | 1        | 1      | 0.73%   |
| WDC WD5002ABYS-02B1B0 500GB     | 1        | 2      | 0.73%   |
| WDC WD5000AVVS-63M8B0 500GB     | 1        | 1      | 0.73%   |
| WDC WD5000AVDS-61U7B1 500GB     | 1        | 1      | 0.73%   |
| WDC WD5000AAKX-75U6AA0 500GB    | 1        | 1      | 0.73%   |
| WDC WD5000AAKX-753CA1 500GB     | 1        | 1      | 0.73%   |
| WDC WD5000AAKX-603CA0 500GB     | 1        | 1      | 0.73%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 1      | 0.73%   |
| WDC WD5000AADS-56S9B1 500GB     | 1        | 1      | 0.73%   |
| WDC WD5000AACS-61M6B2 500GB     | 1        | 1      | 0.73%   |
| WDC WD40PURZ-85TTDY0 4TB        | 1        | 3      | 0.73%   |
| WDC WD3200KS-75PFB0 320GB       | 1        | 1      | 0.73%   |
| WDC WD3200AVVS-63L2B0 320GB     | 1        | 1      | 0.73%   |
| WDC WD3200AVJS-63B6A0 320GB     | 1        | 4      | 0.73%   |
| WDC WD3200AAJS-60M0A0 320GB     | 1        | 2      | 0.73%   |
| WDC WD3200AAJS-56M0A0 320GB     | 1        | 2      | 0.73%   |
| WDC WD2500SD-01KCB0 250GB       | 1        | 1      | 0.73%   |
| WDC WD2500JS-00NCB1 250GB       | 1        | 1      | 0.73%   |
| WDC WD2500AVVS-61L2B0 250GB     | 1        | 1      | 0.73%   |
| WDC WD2500AAKX-00ERMA0 250GB    | 1        | 1      | 0.73%   |
| WDC WD2003FYPS-27W9B0 2TB       | 1        | 1      | 0.73%   |
| WDC WD1600JS-60MHB5 160GB       | 1        | 1      | 0.73%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 52       | 67     | 40.31%  |
| WDC                       | 34       | 45     | 26.36%  |
| Hitachi                   | 13       | 15     | 10.08%  |
| Toshiba                   | 9        | 13     | 6.98%   |
| Samsung Electronics       | 5        | 5      | 3.88%   |
| Kingston                  | 4        | 4      | 3.1%    |
| A-DATA Technology         | 4        | 4      | 3.1%    |
| Maxtor                    | 3        | 3      | 2.33%   |
| HGST                      | 3        | 4      | 2.33%   |
| Micron/Crucial Technology | 1        | 2      | 0.78%   |
| Fujitsu                   | 1        | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 52       | 67     | 43.7%   |
| WDC                 | 33       | 44     | 27.73%  |
| Hitachi             | 13       | 15     | 10.92%  |
| Toshiba             | 9        | 13     | 7.56%   |
| Samsung Electronics | 5        | 5      | 4.2%    |
| Maxtor              | 3        | 3      | 2.52%   |
| HGST                | 3        | 4      | 2.52%   |
| Fujitsu             | 1        | 1      | 0.84%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 106      | 152    | 91.38%  |
| SSD  | 9        | 9      | 7.76%   |
| NVMe | 1        | 2      | 0.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500410AS 500GB         | 1        | 2      | 33.33%  |
| Seagate ST31500341AS 1TB          | 1        | 2      | 33.33%  |
| Samsung Electronics HD161GJ 160GB | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 4      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 507      | 1122   | 54.99%  |
| Works    | 301      | 639    | 32.65%  |
| Malfunc  | 112      | 163    | 12.15%  |
| Failed   | 2        | 5      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 469      | 46.3%   |
| AMD                         | 315      | 31.1%   |
| Nvidia                      | 40       | 3.95%   |
| ADATA Technology            | 27       | 2.67%   |
| Kingston Technology Company | 25       | 2.47%   |
| Realtek Semiconductor       | 21       | 2.07%   |
| Samsung Electronics         | 17       | 1.68%   |
| SanDisk                     | 16       | 1.58%   |
| Marvell Technology Group    | 14       | 1.38%   |
| ASMedia Technology          | 11       | 1.09%   |
| Phison Electronics          | 10       | 0.99%   |
| JMicron Technology          | 10       | 0.99%   |
| Micron/Crucial Technology   | 9        | 0.89%   |
| VIA Technologies            | 5        | 0.49%   |
| MAXIO Technology (Hangzhou) | 4        | 0.39%   |
| SK hynix                    | 3        | 0.3%    |
| Silicon Image               | 3        | 0.3%    |
| LSI Logic / Symbios Logic   | 3        | 0.3%    |
| Broadcom / LSI              | 3        | 0.3%    |
| INNOGRIT                    | 2        | 0.2%    |
| Union Memory (Shenzhen)     | 1        | 0.1%    |
| Silicon Motion              | 1        | 0.1%    |
| Seagate Technology          | 1        | 0.1%    |
| Micron Technology           | 1        | 0.1%    |
| Hewlett-Packard             | 1        | 0.1%    |
| Adaptec                     | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 182      | 13.15%  |
| AMD 400 Series Chipset SATA Controller                                                  | 59       | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 51       | 3.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50       | 3.61%   |
| Intel SATA Controller [RAID mode]                                                       | 47       | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43       | 3.11%   |
| AMD FCH SATA Controller D                                                               | 41       | 2.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 35       | 2.53%   |
| AMD 500 Series Chipset SATA Controller                                                  | 34       | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 33       | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 31       | 2.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 29       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 28       | 2.02%   |
| Nvidia MCP61 SATA Controller                                                            | 27       | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 26       | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 25       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 25       | 1.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 23       | 1.66%   |
| Nvidia MCP61 IDE                                                                        | 20       | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 1.45%   |
| AMD 300 Series Chipset SATA Controller                                                  | 18       | 1.3%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 18       | 1.3%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 17       | 1.23%   |
| AMD FCH IDE Controller                                                                  | 16       | 1.16%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 13       | 0.94%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 12       | 0.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12       | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 0.79%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 10       | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 0.65%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 9        | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 9        | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 9        | 0.65%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 9        | 0.65%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 9        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 9        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 9        | 0.65%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 8        | 0.58%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 8        | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 597      | 55.85%  |
| IDE  | 256      | 23.95%  |
| NVMe | 134      | 12.54%  |
| RAID | 71       | 6.64%   |
| SAS  | 10       | 0.94%   |
| SCSI | 1        | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 477      | 57.4%   |
| AMD          | 352      | 42.36%  |
| CentaurHauls | 1        | 0.12%   |
| Unknown      | 1        | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics          | 16       | 1.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 14       | 1.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 13       | 1.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 13       | 1.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 12       | 1.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 12       | 1.44%   |
| AMD Athlon 3000G with Radeon Vega Graphics      | 12       | 1.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 11       | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor               | 11       | 1.32%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 11       | 1.32%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 10       | 1.2%    |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G   | 10       | 1.2%    |
| Intel Core i3-3220 CPU @ 3.30GHz                | 9        | 1.08%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 9        | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 9        | 1.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 8        | 0.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 8        | 0.96%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 8        | 0.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 8        | 0.96%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 8        | 0.96%   |
| Intel Pentium 4 CPU 3.00GHz                     | 7        | 0.84%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 7        | 0.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 6        | 0.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 6        | 0.72%   |
| AMD Sempron 145 Processor                       | 6        | 0.72%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 6        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 6        | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 6        | 0.72%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 6        | 0.72%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 6        | 0.72%   |
| AMD Ryzen 3 PRO 2200G with Radeon Vega Graphics | 6        | 0.72%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 5        | 0.6%    |
| Intel Pentium Dual CPU E2200 @ 2.20GHz          | 5        | 0.6%    |
| Intel Core i7-7700K CPU @ 4.20GHz               | 5        | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz                | 5        | 0.6%    |
| Intel Core i7-2600 CPU @ 3.40GHz                | 5        | 0.6%    |
| Intel Core i5-4460S CPU @ 2.90GHz               | 5        | 0.6%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 5        | 0.6%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 5        | 0.6%    |
| AMD FX-8800P Radeon R7, 12 Compute Cores 4C+8G  | 5        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 115      | 13.77%  |
| Intel Core i7           | 81       | 9.7%    |
| AMD Ryzen 5             | 67       | 8.02%   |
| Intel Core i3           | 59       | 7.07%   |
| AMD Ryzen 7             | 45       | 5.39%   |
| Intel Xeon              | 40       | 4.79%   |
| Intel Core 2 Duo        | 39       | 4.67%   |
| AMD FX                  | 29       | 3.47%   |
| Intel Celeron           | 28       | 3.35%   |
| AMD Ryzen 3             | 24       | 2.87%   |
| AMD Ryzen 9             | 23       | 2.75%   |
| AMD Athlon              | 23       | 2.75%   |
| Intel Pentium           | 20       | 2.4%    |
| AMD A8                  | 19       | 2.28%   |
| Intel Pentium Dual-Core | 17       | 2.04%   |
| AMD Athlon II X2        | 16       | 1.92%   |
| Intel Core 2 Quad       | 15       | 1.8%    |
| AMD A6                  | 15       | 1.8%    |
| Other                   | 14       | 1.68%   |
| Intel Pentium Dual      | 12       | 1.44%   |
| Intel Pentium 4         | 12       | 1.44%   |
| AMD A4                  | 12       | 1.44%   |
| Intel Core 2            | 9        | 1.08%   |
| AMD Phenom II X4        | 9        | 1.08%   |
| AMD Sempron             | 8        | 0.96%   |
| AMD E1                  | 8        | 0.96%   |
| AMD Athlon 64 X2        | 8        | 0.96%   |
| AMD A10                 | 8        | 0.96%   |
| AMD E                   | 7        | 0.84%   |
| Intel Core i9           | 6        | 0.72%   |
| Intel Atom              | 6        | 0.72%   |
| AMD Ryzen 3 PRO         | 6        | 0.72%   |
| AMD Phenom II X6        | 6        | 0.72%   |
| Intel Pentium D         | 4        | 0.48%   |
| AMD Athlon II X4        | 3        | 0.36%   |
| AMD Athlon Dual Core    | 3        | 0.36%   |
| AMD Athlon 64           | 3        | 0.36%   |
| Intel Pentium Gold      | 2        | 0.24%   |
| AMD Phenom II X2        | 2        | 0.24%   |
| AMD Phenom              | 2        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 285      | 34.09%  |
| 4       | 280      | 33.49%  |
| 6       | 105      | 12.56%  |
| 8       | 63       | 7.54%   |
| 1       | 59       | 7.06%   |
| 12      | 15       | 1.79%   |
| 16      | 11       | 1.32%   |
| 3       | 10       | 1.2%    |
| 10      | 3        | 0.36%   |
| Unknown | 2        | 0.24%   |
| 28      | 1        | 0.12%   |
| 24      | 1        | 0.12%   |
| 14      | 1        | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 823      | 99.04%  |
| 2       | 7        | 0.84%   |
| Unknown | 1        | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 428      | 51.32%  |
| 1       | 404      | 48.44%  |
| Unknown | 2        | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 812      | 97.36%  |
| Unknown        | 13       | 1.56%   |
| 64-bit         | 6        | 0.72%   |
| 32-bit         | 3        | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 231      | 26.55%  |
| 0x206a7    | 49       | 5.63%   |
| 0x306a9    | 41       | 4.71%   |
| 0x1067a    | 41       | 4.71%   |
| 0x306c3    | 40       | 4.6%    |
| 0x08101016 | 21       | 2.41%   |
| 0x010000c8 | 21       | 2.41%   |
| 0x0800820d | 20       | 2.3%    |
| 0x08108109 | 18       | 2.07%   |
| 0x6fd      | 16       | 1.84%   |
| 0x0600611a | 16       | 1.84%   |
| 0x06001119 | 16       | 1.84%   |
| 0x08701021 | 15       | 1.72%   |
| 0x906e9    | 14       | 1.61%   |
| 0x506e3    | 14       | 1.61%   |
| 0x0a50000d | 13       | 1.49%   |
| 0x906ea    | 11       | 1.26%   |
| 0x6fb      | 11       | 1.26%   |
| 0xa0653    | 10       | 1.15%   |
| 0x10676    | 10       | 1.15%   |
| 0x06000852 | 9        | 1.03%   |
| 0x906ed    | 8        | 0.92%   |
| 0x06003106 | 8        | 0.92%   |
| 0x0a50000c | 7        | 0.8%    |
| 0x0a201016 | 7        | 0.8%    |
| 0x08001138 | 7        | 0.8%    |
| 0x08701013 | 6        | 0.69%   |
| 0x0600063e | 6        | 0.69%   |
| 0x6f2      | 5        | 0.57%   |
| 0x206d7    | 5        | 0.57%   |
| 0x106e5    | 5        | 0.57%   |
| 0x106a5    | 5        | 0.57%   |
| 0x0a601203 | 5        | 0.57%   |
| 0x0810100b | 5        | 0.57%   |
| 0x03000027 | 5        | 0.57%   |
| 0xf43      | 4        | 0.46%   |
| 0x406c4    | 4        | 0.46%   |
| 0x306f2    | 4        | 0.46%   |
| 0x05000119 | 4        | 0.46%   |
| 0xf65      | 3        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 68       | 8.15%   |
| Haswell          | 67       | 8.03%   |
| Penryn           | 60       | 7.19%   |
| KabyLake         | 59       | 7.07%   |
| IvyBridge        | 59       | 7.07%   |
| Zen+             | 52       | 6.24%   |
| Zen 3            | 48       | 5.76%   |
| K10              | 46       | 5.52%   |
| Zen              | 41       | 4.92%   |
| Core             | 40       | 4.8%    |
| Piledriver       | 34       | 4.08%   |
| Zen 2            | 31       | 3.72%   |
| Skylake          | 27       | 3.24%   |
| K8 Hammer        | 22       | 2.64%   |
| Excavator        | 22       | 2.64%   |
| CometLake        | 21       | 2.52%   |
| Unknown          | 18       | 2.16%   |
| NetBurst         | 17       | 2.04%   |
| Nehalem          | 14       | 1.68%   |
| Steamroller      | 12       | 1.44%   |
| Silvermont       | 10       | 1.2%    |
| Bulldozer        | 10       | 1.2%    |
| Bobcat           | 10       | 1.2%    |
| Westmere         | 9        | 1.08%   |
| K10 Llano        | 7        | 0.84%   |
| Bonnell          | 6        | 0.72%   |
| Jaguar           | 5        | 0.6%    |
| Puma             | 4        | 0.48%   |
| Icelake          | 4        | 0.48%   |
| Broadwell        | 3        | 0.36%   |
| Alderlake Hybrid | 3        | 0.36%   |
| Tremont          | 2        | 0.24%   |
| Goldmont plus    | 2        | 0.24%   |
| Goldmont         | 1        | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 332      | 37.43%  |
| Intel                      | 291      | 32.81%  |
| Nvidia                     | 254      | 28.64%  |
| Matrox Electronics Systems | 5        | 0.56%   |
| VIA Technologies           | 3        | 0.34%   |
| ATI Technologies           | 2        | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 46       | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 40       | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 34       | 3.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31       | 3.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27       | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23       | 2.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 20       | 2.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 19       | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18       | 1.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 17       | 1.85%   |
| Nvidia GT218 [GeForce 210]                                                               | 16       | 1.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15       | 1.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 14       | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14       | 1.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 14       | 1.52%   |
| Intel HD Graphics 530                                                                    | 12       | 1.3%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 12       | 1.3%    |
| Intel HD Graphics 630                                                                    | 11       | 1.2%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 10       | 1.09%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 10       | 1.09%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 10       | 1.09%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 10       | 1.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 10       | 1.09%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 10       | 1.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9        | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 9        | 0.98%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 9        | 0.98%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 9        | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 0.87%   |
| AMD RS780L [Radeon 3000]                                                                 | 8        | 0.87%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 7        | 0.76%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 6        | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6        | 0.65%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 6        | 0.65%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 6        | 0.65%   |
| AMD RS880 [Radeon HD 4250]                                                               | 6        | 0.65%   |
| AMD Raphael                                                                              | 6        | 0.65%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 6        | 0.65%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 5        | 0.54%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 5        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 293      | 34.76%  |
| 1 x Intel      | 258      | 30.6%   |
| 1 x Nvidia     | 225      | 26.69%  |
| 2 x AMD        | 20       | 2.37%   |
| AMD + Nvidia   | 13       | 1.54%   |
| Intel + AMD    | 10       | 1.19%   |
| Intel + Nvidia | 8        | 0.95%   |
| 2 x Nvidia     | 6        | 0.71%   |
| 1 x Matrox     | 5        | 0.59%   |
| 1 x VIA        | 2        | 0.24%   |
| 3 x AMD        | 1        | 0.12%   |
| 2 x Intel      | 1        | 0.12%   |
| Nvidia + VIA   | 1        | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 694      | 82.23%  |
| Proprietary | 128      | 15.17%  |
| Unknown     | 22       | 2.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 358      | 41.63%  |
| 0.01-0.5   | 133      | 15.47%  |
| 1.01-2.0   | 122      | 14.19%  |
| 0.51-1.0   | 103      | 11.98%  |
| 7.01-8.0   | 49       | 5.7%    |
| 3.01-4.0   | 44       | 5.12%   |
| 5.01-6.0   | 27       | 3.14%   |
| 2.01-3.0   | 12       | 1.4%    |
| 8.01-16.0  | 8        | 0.93%   |
| 16.01-24.0 | 4        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 147      | 17.01%  |
| Dell                 | 129      | 14.93%  |
| Samsung Electronics  | 111      | 12.85%  |
| Goldstar             | 62       | 7.18%   |
| Acer                 | 53       | 6.13%   |
| BenQ                 | 52       | 6.02%   |
| AOC                  | 47       | 5.44%   |
| Unknown              | 28       | 3.24%   |
| Ancor Communications | 18       | 2.08%   |
| ASUSTek Computer     | 17       | 1.97%   |
| Sony                 | 16       | 1.85%   |
| Gateway              | 15       | 1.74%   |
| ViewSonic            | 13       | 1.5%    |
| Lenovo               | 13       | 1.5%    |
| VOR                  | 8        | 0.93%   |
| ___                  | 7        | 0.81%   |
| Sceptre Tech         | 6        | 0.69%   |
| Insignia             | 6        | 0.69%   |
| Unknown              | 6        | 0.69%   |
| Philips              | 5        | 0.58%   |
| LG Electronics       | 5        | 0.58%   |
| SAC                  | 4        | 0.46%   |
| NEC Computers        | 4        | 0.46%   |
| Hitachi              | 4        | 0.46%   |
| FOX                  | 4        | 0.46%   |
| Compaq Computer      | 4        | 0.46%   |
| STD                  | 3        | 0.35%   |
| RTK                  | 3        | 0.35%   |
| Planar               | 3        | 0.35%   |
| Plain Tree Systems   | 3        | 0.35%   |
| Panasonic            | 3        | 0.35%   |
| HUAWEI               | 3        | 0.35%   |
| Gigabyte Technology  | 3        | 0.35%   |
| eMachines            | 3        | 0.35%   |
| AUS                  | 3        | 0.35%   |
| Westinghouse         | 2        | 0.23%   |
| Vizio                | 2        | 0.23%   |
| Unknown (AAA)        | 2        | 0.23%   |
| Toshiba              | 2        | 0.23%   |
| Sun                  | 2        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9        | 1%      |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 9        | 1%      |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 7        | 0.78%   |
| Dell E2011H DEL406B 1600x900 443x249mm 20.0-inch                      | 6        | 0.66%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 6        | 0.66%   |
| Unknown                                                               | 6        | 0.66%   |
| Insignia NS19D220NA16A BBY0019 1680x1050 640x384mm 29.4-inch          | 5        | 0.55%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                        | 5        | 0.55%   |
| ___ LCDTV16 ___3393 1920x1080                                         | 4        | 0.44%   |
| VOR LED21300 VOR2150 1920x1080 597x336mm 27.0-inch                    | 4        | 0.44%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                   | 4        | 0.44%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 4        | 0.44%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 4        | 0.44%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 4        | 0.44%   |
| Hewlett-Packard Compaq WF1907 HWP26A4 1440x900 408x255mm 18.9-inch    | 4        | 0.44%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch             | 4        | 0.44%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch              | 4        | 0.44%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 4        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4        | 0.44%   |
| FOX FBC TV FOX9C01 1366x768 698x393mm 31.5-inch                       | 4        | 0.44%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                      | 4        | 0.44%   |
| Dell E1911 DELF036 1440x900 408x255mm 18.9-inch                       | 4        | 0.44%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 4        | 0.44%   |
| AOC 831W AOC1831 1366x768 410x230mm 18.5-inch                         | 4        | 0.44%   |
| Acer X163W ACR0015 1440x900 344x193mm 15.5-inch                       | 4        | 0.44%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3        | 0.33%   |
| Samsung Electronics S19E310 SAM0C2B 1366x768 410x230mm 18.5-inch      | 3        | 0.33%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 3        | 0.33%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 3        | 0.33%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 3        | 0.33%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 3        | 0.33%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 408x255mm 18.9-inch            | 3        | 0.33%   |
| Hewlett-Packard vs15 HWP2646 1024x768 300x220mm 14.6-inch             | 3        | 0.33%   |
| Hewlett-Packard TouchSmart HWP4218 1600x900 440x240mm 19.7-inch       | 3        | 0.33%   |
| Hewlett-Packard LA1751 HWP2858 1280x1024 340x270mm 17.1-inch          | 3        | 0.33%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 3        | 0.33%   |
| Hewlett-Packard Compaq WF1907 HWP26A5 1440x900 408x255mm 18.9-inch    | 3        | 0.33%   |
| Hewlett-Packard 2011 HWP2935 1600x900 443x249mm 20.0-inch             | 3        | 0.33%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 3        | 0.33%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 3        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 310      | 37.17%  |
| 1366x768 (WXGA)    | 105      | 12.59%  |
| 1280x1024 (SXGA)   | 69       | 8.27%   |
| 1440x900 (WXGA+)   | 65       | 7.79%   |
| 1600x900 (HD+)     | 61       | 7.31%   |
| 3840x2160 (4K)     | 44       | 5.28%   |
| 1680x1050 (WSXGA+) | 29       | 3.48%   |
| 1360x768           | 23       | 2.76%   |
| 2560x1440 (QHD)    | 18       | 2.16%   |
| 1024x768 (XGA)     | 17       | 2.04%   |
| Unknown            | 17       | 2.04%   |
| 2560x1080          | 13       | 1.56%   |
| 3440x1440          | 11       | 1.32%   |
| 3840x1080          | 8        | 0.96%   |
| 2288x1287          | 6        | 0.72%   |
| 1920x1200 (WUXGA)  | 6        | 0.72%   |
| 1600x1200          | 6        | 0.72%   |
| 1280x960           | 5        | 0.6%    |
| 1280x800 (WXGA)    | 4        | 0.48%   |
| 3360x1080          | 2        | 0.24%   |
| 7280x2160          | 1        | 0.12%   |
| 6720x1440          | 1        | 0.12%   |
| 5560x2160          | 1        | 0.12%   |
| 4721x1050          | 1        | 0.12%   |
| 4310x1080          | 1        | 0.12%   |
| 4093x4093          | 1        | 0.12%   |
| 3600x1080          | 1        | 0.12%   |
| 3286x1080          | 1        | 0.12%   |
| 3280x1200          | 1        | 0.12%   |
| 3200x900           | 1        | 0.12%   |
| 1920x540           | 1        | 0.12%   |
| 1920x2928          | 1        | 0.12%   |
| 1400x1050          | 1        | 0.12%   |
| 1360x765           | 1        | 0.12%   |
| 1280x720 (HD)      | 1        | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 93       | 10.93%  |
| 18      | 91       | 10.69%  |
| 21      | 90       | 10.58%  |
| 23      | 79       | 9.28%   |
| Unknown | 70       | 8.23%   |
| 27      | 68       | 7.99%   |
| 24      | 65       | 7.64%   |
| 20      | 58       | 6.82%   |
| 17      | 47       | 5.52%   |
| 15      | 34       | 4%      |
| 31      | 29       | 3.41%   |
| 22      | 22       | 2.59%   |
| 34      | 21       | 2.47%   |
| 72      | 18       | 2.12%   |
| 84      | 11       | 1.29%   |
| 54      | 7        | 0.82%   |
| 40      | 7        | 0.82%   |
| 29      | 6        | 0.71%   |
| 32      | 5        | 0.59%   |
| 46      | 4        | 0.47%   |
| 142     | 3        | 0.35%   |
| 25      | 3        | 0.35%   |
| 14      | 3        | 0.35%   |
| 12      | 3        | 0.35%   |
| 49      | 2        | 0.24%   |
| 26      | 2        | 0.24%   |
| 64      | 1        | 0.12%   |
| 52      | 1        | 0.12%   |
| 50      | 1        | 0.12%   |
| 48      | 1        | 0.12%   |
| 43      | 1        | 0.12%   |
| 39      | 1        | 0.12%   |
| 38      | 1        | 0.12%   |
| 36      | 1        | 0.12%   |
| 16      | 1        | 0.12%   |
| 13      | 1        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 307      | 37.12%  |
| 501-600        | 202      | 24.43%  |
| 301-350        | 75       | 9.07%   |
| Unknown        | 70       | 8.46%   |
| 601-700        | 41       | 4.96%   |
| 351-400        | 40       | 4.84%   |
| 1501-2000      | 29       | 3.51%   |
| 701-800        | 27       | 3.26%   |
| 1001-1500      | 17       | 2.06%   |
| 801-900        | 9        | 1.09%   |
| 201-300        | 6        | 0.73%   |
| More than 2000 | 3        | 0.36%   |
| 901-1000       | 1        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 498      | 62.88%  |
| 16/10   | 105      | 13.26%  |
| 5/4     | 69       | 8.71%   |
| Unknown | 57       | 7.2%    |
| 4/3     | 30       | 3.79%   |
| 21/9    | 22       | 2.78%   |
| 1.00    | 4        | 0.51%   |
| 6/5     | 3        | 0.38%   |
| 32/9    | 3        | 0.38%   |
| 3/2     | 1        | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 206      | 24.91%  |
| 151-200        | 186      | 22.49%  |
| 141-150        | 116      | 14.03%  |
| Unknown        | 70       | 8.46%   |
| 301-350        | 69       | 8.34%   |
| 351-500        | 54       | 6.53%   |
| More than 1000 | 43       | 5.2%    |
| 101-110        | 34       | 4.11%   |
| 251-300        | 19       | 2.3%    |
| 501-1000       | 17       | 2.06%   |
| 111-120        | 4        | 0.48%   |
| 71-80          | 3        | 0.36%   |
| 131-140        | 3        | 0.36%   |
| 121-130        | 2        | 0.24%   |
| 81-90          | 1        | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 513      | 64.69%  |
| 101-120 | 133      | 16.77%  |
| Unknown | 70       | 8.83%   |
| 1-50    | 51       | 6.43%   |
| 121-160 | 14       | 1.77%   |
| 161-240 | 12       | 1.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 677      | 79.46%  |
| 2     | 123      | 14.44%  |
| 0     | 35       | 4.11%   |
| 3     | 16       | 1.88%   |
| 4     | 1        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 539      | 43.89%  |
| Intel                                 | 279      | 22.72%  |
| Qualcomm Atheros                      | 90       | 7.33%   |
| Ralink Technology                     | 53       | 4.32%   |
| Broadcom                              | 41       | 3.34%   |
| Nvidia                                | 34       | 2.77%   |
| TP-Link                               | 31       | 2.52%   |
| Qualcomm Atheros Communications       | 27       | 2.2%    |
| Ralink                                | 25       | 2.04%   |
| Mercucys                              | 12       | 0.98%   |
| Broadcom Limited                      | 12       | 0.98%   |
| MediaTek                              | 10       | 0.81%   |
| Huawei Technologies                   | 10       | 0.81%   |
| Samsung Electronics                   | 6        | 0.49%   |
| Motorola PCS                          | 6        | 0.49%   |
| VIA Technologies                      | 4        | 0.33%   |
| Linksys                               | 4        | 0.33%   |
| D-Link                                | 4        | 0.33%   |
| Marvell Technology Group              | 3        | 0.24%   |
| D-Link System                         | 3        | 0.24%   |
| Xiaomi                                | 2        | 0.16%   |
| Wacom                                 | 2        | 0.16%   |
| Qualcomm                              | 2        | 0.16%   |
| NetGear                               | 2        | 0.16%   |
| ICS Advent                            | 2        | 0.16%   |
| Google                                | 2        | 0.16%   |
| ASIX Electronics                      | 2        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.16%   |
| ZTE WCDMA Technologies MSM            | 1        | 0.08%   |
| Tenda                                 | 1        | 0.08%   |
| Sangoma Technologies                  | 1        | 0.08%   |
| OPPO Electronics                      | 1        | 0.08%   |
| Microsoft                             | 1        | 0.08%   |
| Microchip Technology                  | 1        | 0.08%   |
| Micro Star International              | 1        | 0.08%   |
| LG Electronics                        | 1        | 0.08%   |
| Lenovo                                | 1        | 0.08%   |
| InterBiometrics                       | 1        | 0.08%   |
| IBM                                   | 1        | 0.08%   |
| Hisense                               | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 412      | 29.92%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 53       | 3.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 37       | 2.69%   |
| Intel I211 Gigabit Network Connection                               | 33       | 2.4%    |
| Intel Wi-Fi 6 AX200                                                 | 29       | 2.11%   |
| Intel Ethernet Connection I217-LM                                   | 25       | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 23       | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                   | 23       | 1.67%   |
| Qualcomm Atheros AR9271 802.11n                                     | 23       | 1.67%   |
| Nvidia MCP61 Ethernet                                               | 22       | 1.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 21       | 1.53%   |
| Ralink MT7601U Wireless Adapter                                     | 20       | 1.45%   |
| Intel Ethernet Connection (2) I219-V                                | 16       | 1.16%   |
| Intel Ethernet Controller I225-V                                    | 14       | 1.02%   |
| Intel 82579V Gigabit Network Connection                             | 13       | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 12       | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 11       | 0.8%    |
| Realtek 802.11ac NIC                                                | 11       | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 11       | 0.8%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 10       | 0.73%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 10       | 0.73%   |
| Mercucys 802.11n NIC                                                | 10       | 0.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 9        | 0.65%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller           | 9        | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 9        | 0.65%   |
| Intel 82574L Gigabit Network Connection                             | 9        | 0.65%   |
| Huawei MAR-LX1M                                                     | 9        | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 8        | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 8        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 8        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                | 8        | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                          | 8        | 0.58%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express             | 8        | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 7        | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 7        | 0.51%   |
| Realtek RTL8187 Wireless Adapter                                    | 7        | 0.51%   |
| Ralink RT5370 Wireless Adapter                                      | 7        | 0.51%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 7        | 0.51%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 7        | 0.51%   |
| Intel Ethernet Connection I217-V                                    | 7        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 140      | 30.24%  |
| Intel                                 | 68       | 14.69%  |
| Qualcomm Atheros                      | 65       | 14.04%  |
| Ralink Technology                     | 53       | 11.45%  |
| TP-Link                               | 31       | 6.7%    |
| Qualcomm Atheros Communications       | 27       | 5.83%   |
| Ralink                                | 25       | 5.4%    |
| Mercucys                              | 12       | 2.59%   |
| MediaTek                              | 9        | 1.94%   |
| Broadcom                              | 9        | 1.94%   |
| Linksys                               | 4        | 0.86%   |
| D-Link                                | 4        | 0.86%   |
| Broadcom Limited                      | 3        | 0.65%   |
| Wacom                                 | 2        | 0.43%   |
| NetGear                               | 2        | 0.43%   |
| D-Link System                         | 2        | 0.43%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.43%   |
| Tenda                                 | 1        | 0.22%   |
| Microsoft                             | 1        | 0.22%   |
| Micro Star International              | 1        | 0.22%   |
| Gemtek                                | 1        | 0.22%   |
| Belkin Components                     | 1        | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 29       | 6.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 23       | 4.94%   |
| Qualcomm Atheros AR9271 802.11n                                               | 23       | 4.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 21       | 4.51%   |
| Ralink MT7601U Wireless Adapter                                               | 20       | 4.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 11       | 2.36%   |
| Realtek 802.11ac NIC                                                          | 11       | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 11       | 2.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 10       | 2.15%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 10       | 2.15%   |
| Mercucys 802.11n NIC                                                          | 10       | 2.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 9        | 1.93%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 9        | 1.93%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 9        | 1.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 8        | 1.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 8        | 1.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 7        | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                                    | 7        | 1.5%    |
| Realtek RTL8187 Wireless Adapter                                              | 7        | 1.5%    |
| Ralink RT5370 Wireless Adapter                                                | 7        | 1.5%    |
| Ralink RT2561/RT61 802.11g PCI                                                | 7        | 1.5%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]           | 7        | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 1.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 6        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6        | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 6        | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6        | 1.29%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 6        | 1.29%   |
| Intel Wireless-AC 9260                                                        | 6        | 1.29%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 5        | 1.07%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 4        | 0.86%   |
| Realtek RTL8821CE PCIe 802.11ac Wireless Network Controller                   | 4        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 4        | 0.86%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 4        | 0.86%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 4        | 0.86%   |
| Intel Wireless 3165                                                           | 4        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4        | 0.86%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 4        | 0.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 3        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 481      | 54.47%  |
| Intel                      | 252      | 28.54%  |
| Nvidia                     | 34       | 3.85%   |
| Broadcom                   | 32       | 3.62%   |
| Qualcomm Atheros           | 28       | 3.17%   |
| Huawei Technologies        | 10       | 1.13%   |
| Broadcom Limited           | 9        | 1.02%   |
| Motorola PCS               | 5        | 0.57%   |
| VIA Technologies           | 4        | 0.45%   |
| Samsung Electronics        | 4        | 0.45%   |
| Marvell Technology Group   | 3        | 0.34%   |
| Xiaomi                     | 2        | 0.23%   |
| Qualcomm                   | 2        | 0.23%   |
| ICS Advent                 | 2        | 0.23%   |
| Google                     | 2        | 0.23%   |
| ASIX Electronics           | 2        | 0.23%   |
| ZTE WCDMA Technologies MSM | 1        | 0.11%   |
| OPPO Electronics           | 1        | 0.11%   |
| MediaTek                   | 1        | 0.11%   |
| LG Electronics             | 1        | 0.11%   |
| IBM                        | 1        | 0.11%   |
| Hisense                    | 1        | 0.11%   |
| DisplayLink                | 1        | 0.11%   |
| D-Link System              | 1        | 0.11%   |
| ADMtek                     | 1        | 0.11%   |
| Accton Technology          | 1        | 0.11%   |
| 3Com                       | 1        | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 412      | 45.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53       | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37       | 4.1%    |
| Intel I211 Gigabit Network Connection                             | 33       | 3.66%   |
| Intel Ethernet Connection I217-LM                                 | 25       | 2.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23       | 2.55%   |
| Nvidia MCP61 Ethernet                                             | 22       | 2.44%   |
| Intel Ethernet Connection (2) I219-V                              | 16       | 1.77%   |
| Intel Ethernet Controller I225-V                                  | 14       | 1.55%   |
| Intel 82579V Gigabit Network Connection                           | 13       | 1.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 12       | 1.33%   |
| Intel 82574L Gigabit Network Connection                           | 9        | 1%      |
| Huawei MAR-LX1M                                                   | 9        | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 8        | 0.89%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 8        | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 7        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5        | 0.55%   |
| Motorola PCS motorola edge 40                                     | 5        | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 4        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.44%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.44%   |
| Intel Ethernet Connection (11) I219-V                             | 4        | 0.44%   |
| Intel 82566DM Gigabit Network Connection                          | 4        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4        | 0.44%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 4        | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.33%   |
| Intel NM10/ICH7 Family LAN Controller                             | 3        | 0.33%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.33%   |
| Intel Ethernet Connection (12) I219-V                             | 3        | 0.33%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 822      | 65.92%  |
| WiFi     | 416      | 33.36%  |
| Modem    | 5        | 0.4%    |
| Unknown  | 4        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 600      | 68.34%  |
| WiFi     | 277      | 31.55%  |
| Unknown  | 1        | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 571      | 68.22%  |
| 2     | 242      | 28.91%  |
| 3     | 14       | 1.67%   |
| 0     | 4        | 0.48%   |
| 4     | 3        | 0.36%   |
| 8     | 1        | 0.12%   |
| 6     | 1        | 0.12%   |
| 5     | 1        | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 592      | 68.84%  |
| Yes  | 268      | 31.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 104      | 43.15%  |
| Intel                           | 62       | 25.73%  |
| Realtek Semiconductor           | 16       | 6.64%   |
| ASUSTek Computer                | 13       | 5.39%   |
| Qualcomm Atheros Communications | 10       | 4.15%   |
| IMC Networks                    | 9        | 3.73%   |
| TP-Link                         | 6        | 2.49%   |
| MediaTek                        | 6        | 2.49%   |
| Broadcom                        | 5        | 2.07%   |
| Dell                            | 3        | 1.24%   |
| Apple                           | 2        | 0.83%   |
| Roper                           | 1        | 0.41%   |
| Ralink                          | 1        | 0.41%   |
| Micro Star International        | 1        | 0.41%   |
| Lite-On Technology              | 1        | 0.41%   |
| Dynex                           | 1        | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 104      | 43.15%  |
| Intel AX200 Bluetooth                                    | 28       | 11.62%  |
| Realtek Bluetooth Radio                                  | 13       | 5.39%   |
| Intel Bluetooth wireless interface                       | 10       | 4.15%   |
| IMC Networks Bluetooth Radio                             | 8        | 3.32%   |
| Intel Wireless-AC 3168 Bluetooth                         | 7        | 2.9%    |
| TP-Link UB500 Adapter                                    | 6        | 2.49%   |
| MediaTek Wireless_Device                                 | 6        | 2.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 6        | 2.49%   |
| ASUS Bluetooth Radio                                     | 6        | 2.49%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 5        | 2.07%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 1.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 4        | 1.66%   |
| Intel AX210 Bluetooth                                    | 4        | 1.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 4        | 1.66%   |
| Intel Bluetooth Device                                   | 3        | 1.24%   |
| Dell Broadcom BCM20702A0 Bluetooth                       | 3        | 1.24%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 0.83%   |
| Roper Class 1 Bluetooth Dongle                           | 1        | 0.41%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.41%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.41%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.41%   |
| Micro Star International Bluetooth Device                | 1        | 0.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1        | 0.41%   |
| IMC Networks Bluetooth module                            | 1        | 0.41%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.41%   |
| Broadcom HP Portable Bumble Bee                          | 1        | 0.41%   |
| Broadcom HP Bluetooth Module                             | 1        | 0.41%   |
| Broadcom HP Bluethunder                                  | 1        | 0.41%   |
| Broadcom BCM92045B3 ROM                                  | 1        | 0.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 1        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.41%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.41%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1        | 0.41%   |
| Apple Bluetooth USB Host Controller                      | 1        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 456      | 38.32%  |
| AMD                                          | 387      | 32.52%  |
| Nvidia                                       | 232      | 19.5%   |
| C-Media Electronics                          | 22       | 1.85%   |
| Logitech                                     | 10       | 0.84%   |
| Generalplus Technology                       | 10       | 0.84%   |
| Texas Instruments                            | 8        | 0.67%   |
| Creative Labs                                | 7        | 0.59%   |
| Corsair                                      | 7        | 0.59%   |
| VIA Technologies                             | 6        | 0.5%    |
| Razer USA                                    | 5        | 0.42%   |
| JMTek                                        | 4        | 0.34%   |
| ASUSTek Computer                             | 4        | 0.34%   |
| SAVITECH                                     | 2        | 0.17%   |
| Microsoft                                    | 2        | 0.17%   |
| Kingston Technology                          | 2        | 0.17%   |
| GN Netcom                                    | 2        | 0.17%   |
| Focusrite-Novation                           | 2        | 0.17%   |
| BR23                                         | 2        | 0.17%   |
| ATI Technologies                             | 2        | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.08%   |
| Tenx Technology                              | 1        | 0.08%   |
| Syntek                                       | 1        | 0.08%   |
| Shure                                        | 1        | 0.08%   |
| RODE Microphones                             | 1        | 0.08%   |
| Realtek Semiconductor                        | 1        | 0.08%   |
| Plantronics                                  | 1        | 0.08%   |
| Micro Star International                     | 1        | 0.08%   |
| M-Audio                                      | 1        | 0.08%   |
| Giga-Byte Technology                         | 1        | 0.08%   |
| FiiO Electronics Technology                  | 1        | 0.08%   |
| FDUCE PRO AUDIO MADE                         | 1        | 0.08%   |
| Dell                                         | 1        | 0.08%   |
| Creative Technology                          | 1        | 0.08%   |
| Cirrus Logic                                 | 1        | 0.08%   |
| Blue Microphones                             | 1        | 0.08%   |
| AKAI Professional M.I.                       | 1        | 0.08%   |
| Afatech                                      | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 87       | 5.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 80       | 5.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 62       | 4.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 57       | 3.82%   |
| AMD Starship/Matisse HD Audio Controller                                          | 52       | 3.48%   |
| AMD FCH Azalia Controller                                                         | 52       | 3.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 50       | 3.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 49       | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 48       | 3.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 40       | 2.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 33       | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 31       | 2.07%   |
| Intel 200 Series PCH HD Audio                                                     | 29       | 1.94%   |
| Nvidia MCP61 High Definition Audio                                                | 27       | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 27       | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                          | 27       | 1.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 25       | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 23       | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                        | 22       | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 20       | 1.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 20       | 1.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 19       | 1.27%   |
| AMD Navi 10 HDMI Audio                                                            | 18       | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 18       | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                                     | 17       | 1.14%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 17       | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 16       | 1.07%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 16       | 1.07%   |
| Nvidia High Definition Audio Controller                                           | 15       | 1%      |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 15       | 1%      |
| AMD Trinity HDMI Audio Controller                                                 | 15       | 1%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 13       | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 13       | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 12       | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                                     | 11       | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 11       | 0.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 11       | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                                     | 10       | 0.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 10       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 125      | 24.37%  |
| A-DATA Technology   | 86       | 16.76%  |
| Samsung Electronics | 56       | 10.92%  |
| Unknown             | 53       | 10.33%  |
| SK hynix            | 48       | 9.36%   |
| Corsair             | 37       | 7.21%   |
| Micron Technology   | 26       | 5.07%   |
| Team                | 11       | 2.14%   |
| Crucial             | 11       | 2.14%   |
| Nanya Technology    | 10       | 1.95%   |
| Ramaxel Technology  | 7        | 1.36%   |
| Patriot             | 6        | 1.17%   |
| G.Skill             | 5        | 0.97%   |
| Qimonda             | 4        | 0.78%   |
| PNY                 | 4        | 0.78%   |
| Timetec             | 3        | 0.58%   |
| Elpida              | 3        | 0.58%   |
| Unknown             | 3        | 0.58%   |
| Transcend           | 2        | 0.39%   |
| CSX                 | 2        | 0.39%   |
| Unknown (8A6B)      | 1        | 0.19%   |
| Unknown (0x0E9D)    | 1        | 0.19%   |
| Silicon Power       | 1        | 0.19%   |
| SGS/Thomson         | 1        | 0.19%   |
| S                   | 1        | 0.19%   |
| Patriot Memory      | 1        | 0.19%   |
| Hewlett-Packard     | 1        | 0.19%   |
| Gigabyte Technology | 1        | 0.19%   |
| Avant               | 1        | 0.19%   |
| Apacer              | 1        | 0.19%   |
| Aeneon              | 1        | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 17       | 2.97%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s | 10       | 1.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 6        | 1.05%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 6        | 1.05%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 6        | 1.05%   |
| A-DATA RAM DDR4 2666 8GB DIMM DDR4 3200MT/s            | 6        | 1.05%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s     | 5        | 0.87%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 5        | 0.87%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 5        | 0.87%   |
| A-DATA RAM Module 8GB DIMM DDR4 2133MT/s               | 5        | 0.87%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s    | 4        | 0.7%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 4        | 0.7%    |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s              | 4        | 0.7%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 4        | 0.7%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s  | 4        | 0.7%    |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s  | 4        | 0.7%    |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 4        | 0.7%    |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s   | 4        | 0.7%    |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 4        | 0.7%    |
| A-DATA RAM Module 8GB DIMM DDR4 2400MT/s               | 4        | 0.7%    |
| A-DATA RAM Module 8GB DIMM DDR3 1600MT/s               | 4        | 0.7%    |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 4        | 0.7%    |
| A-DATA RAM DDR4 2666 8GB DIMM DDR4 2667MT/s            | 4        | 0.7%    |
| A-DATA RAM DDR4 2666 2OZ 8GB DIMM DDR4 3200MT/s        | 4        | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 3        | 0.52%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s             | 3        | 0.52%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s  | 3        | 0.52%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 3        | 0.52%   |
| Kingston RAM Module 1GB DIMM DDR2 667MT/s              | 3        | 0.52%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s    | 3        | 0.52%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 3        | 0.52%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3600MT/s  | 3        | 0.52%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s     | 3        | 0.52%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s  | 3        | 0.52%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 3        | 0.52%   |
| Corsair RAM CMK8GX4M1A2400C14 8GB DIMM DDR4 2800MT/s   | 3        | 0.52%   |
| A-DATA RAM DDR4 2666 2OZ 8GB DIMM DDR4 2667MT/s        | 3        | 0.52%   |
| A-DATA RAM DDR4 2400 2OZ 8GB DIMM DDR4 3000MT/s        | 3        | 0.52%   |
| Unknown                                                | 3        | 0.52%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 2        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 187      | 42.6%   |
| DDR3    | 148      | 33.71%  |
| DDR2    | 39       | 8.88%   |
| SDRAM   | 28       | 6.38%   |
| Unknown | 22       | 5.01%   |
| DDR5    | 8        | 1.82%   |
| DDR     | 6        | 1.37%   |
| LPDDR4  | 1        | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 390      | 92.64%  |
| SODIMM       | 26       | 6.18%   |
| RIMM         | 2        | 0.48%   |
| Row Of Chips | 1        | 0.24%   |
| FB-DIMM      | 1        | 0.24%   |
| Unknown      | 1        | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 144      | 30.19%  |
| 4096  | 113      | 23.69%  |
| 2048  | 76       | 15.93%  |
| 16384 | 61       | 12.79%  |
| 32768 | 44       | 9.22%   |
| 1024  | 32       | 6.71%   |
| 512   | 5        | 1.05%   |
| 256   | 1        | 0.21%   |
| 128   | 1        | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 79       | 16.12%  |
| 1333    | 60       | 12.24%  |
| 3600    | 44       | 8.98%   |
| 3200    | 38       | 7.76%   |
| 2667    | 27       | 5.51%   |
| 800     | 24       | 4.9%    |
| 2133    | 21       | 4.29%   |
| 667     | 20       | 4.08%   |
| 2400    | 18       | 3.67%   |
| 3733    | 13       | 2.65%   |
| 1866    | 11       | 2.24%   |
| Unknown | 10       | 2.04%   |
| 2800    | 8        | 1.63%   |
| 3400    | 7        | 1.43%   |
| 3000    | 7        | 1.43%   |
| 3466    | 6        | 1.22%   |
| 2933    | 6        | 1.22%   |
| 2666    | 6        | 1.22%   |
| 1867    | 6        | 1.22%   |
| 1067    | 6        | 1.22%   |
| 1066    | 6        | 1.22%   |
| 533     | 6        | 1.22%   |
| 49926   | 4        | 0.82%   |
| 4800    | 4        | 0.82%   |
| 3933    | 4        | 0.82%   |
| 1800    | 4        | 0.82%   |
| 1331    | 4        | 0.82%   |
| 5600    | 3        | 0.61%   |
| 3800    | 3        | 0.61%   |
| 2200    | 3        | 0.61%   |
| 1639    | 3        | 0.61%   |
| 2048    | 2        | 0.41%   |
| 2000    | 2        | 0.41%   |
| 1334    | 2        | 0.41%   |
| 1332    | 2        | 0.41%   |
| 400     | 2        | 0.41%   |
| 333     | 2        | 0.41%   |
| 266     | 2        | 0.41%   |
| 8400    | 1        | 0.2%    |
| 6000    | 1        | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 13       | 30.95%  |
| Seiko Epson         | 11       | 26.19%  |
| Brother Industries  | 10       | 23.81%  |
| Samsung Electronics | 3        | 7.14%   |
| Canon               | 3        | 7.14%   |
| QinHeng Electronics | 1        | 2.38%   |
| Kyocera             | 1        | 2.38%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seiko Epson L120 Series                 | 4        | 9.3%    |
| HP DeskJet 1110 series                  | 3        | 6.98%   |
| HP LaserJet Professional P 1102w        | 2        | 4.65%   |
| Brother HL-1110 series                  | 2        | 4.65%   |
| Seiko Epson XP-235 Series               | 1        | 2.33%   |
| Seiko Epson L805 Series                 | 1        | 2.33%   |
| Seiko Epson L6160 Series                | 1        | 2.33%   |
| Seiko Epson L382 Series                 | 1        | 2.33%   |
| Seiko Epson L300 Series                 | 1        | 2.33%   |
| Seiko Epson L200 Series                 | 1        | 2.33%   |
| Seiko Epson L1300 Series                | 1        | 2.33%   |
| Seiko Epson ET-2700 Series              | 1        | 2.33%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 2.33%   |
| Samsung ML-1640 Series Laser Printer    | 1        | 2.33%   |
| Samsung M283x Series                    | 1        | 2.33%   |
| QinHeng CH340S                          | 1        | 2.33%   |
| Kyocera FS-1030D printer                | 1        | 2.33%   |
| HP OfficeJet Pro 7740 series            | 1        | 2.33%   |
| HP LaserJet P3010 Series                | 1        | 2.33%   |
| HP DeskJet F4200 series                 | 1        | 2.33%   |
| HP DeskJet F300 series                  | 1        | 2.33%   |
| HP DeskJet 4720 series                  | 1        | 2.33%   |
| HP DeskJet 3700 series                  | 1        | 2.33%   |
| HP DeskJet 2600 series                  | 1        | 2.33%   |
| HP Deskjet 2540 series                  | 1        | 2.33%   |
| Canon PIXMA MG3500 Series               | 1        | 2.33%   |
| Canon PIXMA iP3000x Printer             | 1        | 2.33%   |
| Canon G3000 series                      | 1        | 2.33%   |
| Brother MFC-T910DW                      | 1        | 2.33%   |
| Brother MFC-L3770CDW series             | 1        | 2.33%   |
| Brother MFC-J470DW                      | 1        | 2.33%   |
| Brother MFC-J460DW                      | 1        | 2.33%   |
| Brother HL-2130 series                  | 1        | 2.33%   |
| Brother DCP-T710W                       | 1        | 2.33%   |
| Brother DCP-L2540DW                     | 1        | 2.33%   |
| Brother Composite Device                | 1        | 2.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 75%     |
| Seiko Epson     | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| HP ScanJet 4500C/5550C                             | 2        | 50%     |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1        | 25%     |
| HP ScanJet 3300c                                   | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 43       | 25.15%  |
| Generalplus Technology        | 19       | 11.11%  |
| Microdia                      | 15       | 8.77%   |
| Chicony Electronics           | 14       | 8.19%   |
| Jieli Technology              | 9        | 5.26%   |
| Microsoft                     | 8        | 4.68%   |
| Samsung Electronics           | 7        | 4.09%   |
| GEMBIRD                       | 6        | 3.51%   |
| KYE Systems (Mouse Systems)   | 5        | 2.92%   |
| Apple                         | 5        | 2.92%   |
| Z-Star Microelectronics       | 3        | 1.75%   |
| Realtek Semiconductor         | 3        | 1.75%   |
| LG Electronics                | 3        | 1.75%   |
| Hewlett-Packard               | 3        | 1.75%   |
| Xiongmai                      | 2        | 1.17%   |
| Sunplus Innovation Technology | 2        | 1.17%   |
| Genesys Logic                 | 2        | 1.17%   |
| Alcor Micro                   | 2        | 1.17%   |
| XHT-210518                    | 1        | 0.58%   |
| Unknown                       | 1        | 0.58%   |
| Syntek                        | 1        | 0.58%   |
| Sunplus Technology            | 1        | 0.58%   |
| Silicon Motion                | 1        | 0.58%   |
| Ruision                       | 1        | 0.58%   |
| Razer USA                     | 1        | 0.58%   |
| Novatel Wireless              | 1        | 0.58%   |
| MacroSilicon                  | 1        | 0.58%   |
| Linux Foundation HS           | 1        | 0.58%   |
| lihappe8                      | 1        | 0.58%   |
| IMC Networks                  | 1        | 0.58%   |
| Huawei Technologies           | 1        | 0.58%   |
| Guillemot                     | 1        | 0.58%   |
| Cubeternet                    | 1        | 0.58%   |
| Creative Technology           | 1        | 0.58%   |
| Creality 3D Technology        | 1        | 0.58%   |
| AVerMedia Technologies        | 1        | 0.58%   |
| Aveo Technology               | 1        | 0.58%   |
| ARC International             | 1        | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                           | 16       | 9.2%    |
| Generalplus GENERAL WEBCAM                            | 16       | 9.2%    |
| Logitech Webcam C270                                  | 10       | 5.75%   |
| Microdia Integrated Camera                            | 9        | 5.17%   |
| Jieli USB PHY 2.0                                     | 9        | 5.17%   |
| Samsung Galaxy series, misc. (MTP mode)               | 7        | 4.02%   |
| Logitech Webcam C170                                  | 5        | 2.87%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 5        | 2.87%   |
| Chicony HP 0.3MP Webcam                               | 4        | 2.3%    |
| Microsoft LifeCam HD-3000                             | 3        | 1.72%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 3        | 1.72%   |
| HP Webcam HD-2200                                     | 3        | 1.72%   |
| Chicony HP High Definition 1MP Webcam                 | 3        | 1.72%   |
| Apple iPhone 5/5C/5S/6/SE                             | 3        | 1.72%   |
| Xiongmai web camera                                   | 2        | 1.15%   |
| Sunplus Integrated_Webcam_HD                          | 2        | 1.15%   |
| Realtek HP 1.0MP High Definition Webcam               | 2        | 1.15%   |
| Microdia USB Camera                                   | 2        | 1.15%   |
| Logitech Webcam Pro 9000                              | 2        | 1.15%   |
| Logitech HD Webcam C525                               | 2        | 1.15%   |
| Logitech C922 Pro Stream Webcam                       | 2        | 1.15%   |
| Logitech C920 PRO HD Webcam                           | 2        | 1.15%   |
| KYE Systems (Mouse Systems) Genius Webcam             | 2        | 1.15%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320        | 2        | 1.15%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 2        | 1.15%   |
| Chicony CNF8050 Webcam                                | 2        | 1.15%   |
| Apple iPhone 4                                        | 2        | 1.15%   |
| Alcor Micro USB 2.0 PC Camera                         | 2        | 1.15%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 0.57%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 0.57%   |
| Z-Star Lenovo IdeaCentre Web Camera                   | 1        | 0.57%   |
| XHT-210518 EC500X                                     | 1        | 0.57%   |
| Unknown HD camera                                     | 1        | 0.57%   |
| Syntek USB Video Device                               | 1        | 0.57%   |
| Sunplus USB2.0 2M WebCam                              | 1        | 0.57%   |
| Silicon Motion Silicon Motion Camera                  | 1        | 0.57%   |
| Ruision UVC Camera                                    | 1        | 0.57%   |
| Realtek Webcam                                        | 1        | 0.57%   |
| Razer USA Razer Kiyo Pro                              | 1        | 0.57%   |
| Novatel Wireless Merlin U740 (non-Vodafone)           | 1        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 50%     |
| DigitalPersona        | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| LighTuning Fingerprint Sensor     | 1        | 50%     |
| DigitalPersona Fingerprint Reader | 1        | 50%     |

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
| 0     | 703      | 83.1%   |
| 1     | 126      | 14.89%  |
| 2     | 12       | 1.42%   |
| 3     | 2        | 0.24%   |
| 8     | 1        | 0.12%   |
| 6     | 1        | 0.12%   |
| 4     | 1        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 56       | 34.36%  |
| Net/wireless             | 52       | 31.9%   |
| Communication controller | 16       | 9.82%   |
| Unassigned class         | 7        | 4.29%   |
| Multimedia controller    | 6        | 3.68%   |
| Sound                    | 5        | 3.07%   |
| Storage/raid             | 3        | 1.84%   |
| Network                  | 3        | 1.84%   |
| Net/ethernet             | 3        | 1.84%   |
| Bluetooth                | 3        | 1.84%   |
| Fingerprint reader       | 2        | 1.23%   |
| Camera                   | 2        | 1.23%   |
| Video                    | 1        | 0.61%   |
| Tv card                  | 1        | 0.61%   |
| Storage/nvme             | 1        | 0.61%   |
| Storage/ata              | 1        | 0.61%   |
| Modem                    | 1        | 0.61%   |

