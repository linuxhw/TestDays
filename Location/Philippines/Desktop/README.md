Linux in Philippines - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

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

Total: 359

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H410M H V3                  | [0610c346d8](https://linux-hardware.org/?probe=0610c346d8) | Jan 25, 2024 |
| Dell          | 0G679R A00                  | [993e7a71b2](https://linux-hardware.org/?probe=993e7a71b2) | Jan 18, 2024 |
| Dell          | 0G679R A00                  | [31f196442f](https://linux-hardware.org/?probe=31f196442f) | Jan 18, 2024 |
| Gigabyte      | B450 AORUS M                | [06cced7a39](https://linux-hardware.org/?probe=06cced7a39) | Jan 18, 2024 |
| ASUSTek       | PRIME A320M-K               | [bddc683db5](https://linux-hardware.org/?probe=bddc683db5) | Jan 12, 2024 |
| ASUSTek       | PRIME A320M-K               | [cf07066830](https://linux-hardware.org/?probe=cf07066830) | Jan 03, 2024 |
| Gigabyte      | F2A68HM-S1                  | [dc498a88a6](https://linux-hardware.org/?probe=dc498a88a6) | Dec 27, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [341417afe4](https://linux-hardware.org/?probe=341417afe4) | Dec 21, 2023 |
| ASUSTek       | PRIME B250M-A               | [1eaf3dd454](https://linux-hardware.org/?probe=1eaf3dd454) | Dec 10, 2023 |
| MSI           | A520M PRO-VH                | [96475c0e77](https://linux-hardware.org/?probe=96475c0e77) | Dec 08, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [0dade4f111](https://linux-hardware.org/?probe=0dade4f111) | Dec 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| MSI           | B550-A PRO                  | [6f41c9ca50](https://linux-hardware.org/?probe=6f41c9ca50) | Dec 02, 2023 |
| Gigabyte      | H470 HD3                    | [0b9cf3a0a5](https://linux-hardware.org/?probe=0b9cf3a0a5) | Dec 02, 2023 |
| Gigabyte      | H470 HD3                    | [0ecb969c2c](https://linux-hardware.org/?probe=0ecb969c2c) | Nov 28, 2023 |
| ASUSTek       | A55BM-E                     | [28fe1a1fe1](https://linux-hardware.org/?probe=28fe1a1fe1) | Nov 26, 2023 |
| HP            | 2AE5 A01                    | [d23f45244b](https://linux-hardware.org/?probe=d23f45244b) | Nov 25, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [bc11e1264c](https://linux-hardware.org/?probe=bc11e1264c) | Nov 22, 2023 |
| HP            | 2AE5 A01                    | [90e640454c](https://linux-hardware.org/?probe=90e640454c) | Nov 18, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [5368b237d8](https://linux-hardware.org/?probe=5368b237d8) | Nov 18, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | [7af93dbd28](https://linux-hardware.org/?probe=7af93dbd28) | Nov 17, 2023 |
| MSI           | B550-A PRO                  | [a7467830d5](https://linux-hardware.org/?probe=a7467830d5) | Nov 17, 2023 |
| HP            | 2AE5 A01                    | [729cec323f](https://linux-hardware.org/?probe=729cec323f) | Nov 14, 2023 |
| HP            | 8054                        | [66fa2fd8c5](https://linux-hardware.org/?probe=66fa2fd8c5) | Nov 11, 2023 |
| HP            | 8054                        | [91d4d659b4](https://linux-hardware.org/?probe=91d4d659b4) | Nov 11, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [eb9b1302fd](https://linux-hardware.org/?probe=eb9b1302fd) | Nov 08, 2023 |
| ASRock        | B650M PG Riptide WiFi       | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| MSI           | A320M-A PRO                 | [851db330be](https://linux-hardware.org/?probe=851db330be) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d3e630e86d](https://linux-hardware.org/?probe=d3e630e86d) | Oct 23, 2023 |
| Biostar       | A320MH                      | [e2c20a6c0c](https://linux-hardware.org/?probe=e2c20a6c0c) | Oct 19, 2023 |
| Biostar       | A320MH                      | [62a3d049b2](https://linux-hardware.org/?probe=62a3d049b2) | Oct 18, 2023 |
| Acer          | Veriton X2660G              | [d122988e18](https://linux-hardware.org/?probe=d122988e18) | Oct 17, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [04d307e685](https://linux-hardware.org/?probe=04d307e685) | Oct 16, 2023 |
| Unknown       | Unknown                     | [5e866a9155](https://linux-hardware.org/?probe=5e866a9155) | Oct 10, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [ecef286c2a](https://linux-hardware.org/?probe=ecef286c2a) | Sep 26, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [bf29b07e79](https://linux-hardware.org/?probe=bf29b07e79) | Sep 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [1259637f6b](https://linux-hardware.org/?probe=1259637f6b) | Sep 18, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| MSI           | PRO B760M-G DDR4            | [a8f42a3c96](https://linux-hardware.org/?probe=a8f42a3c96) | Sep 05, 2023 |
| Dell          | 0G679R A00                  | [30755bff92](https://linux-hardware.org/?probe=30755bff92) | Sep 03, 2023 |
| Intel         | H81                         | [75aabbccf5](https://linux-hardware.org/?probe=75aabbccf5) | Sep 03, 2023 |
| Dell          | 0G679R A00                  | [cc4b4ad10d](https://linux-hardware.org/?probe=cc4b4ad10d) | Sep 01, 2023 |
| MSI           | H110M PRO-VD PLUS           | [a75e60a457](https://linux-hardware.org/?probe=a75e60a457) | Aug 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| EMAXX TECH... | EMX-B450M-GAMING            | [3f5c0e83d4](https://linux-hardware.org/?probe=3f5c0e83d4) | Aug 06, 2023 |
| MSI           | A320M PRO-VH                | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| Gigabyte      | B360M HD3                   | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| Samsung       | DeskTop System              | [c1d4c8efb2](https://linux-hardware.org/?probe=c1d4c8efb2) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [d1dee26c33](https://linux-hardware.org/?probe=d1dee26c33) | Jul 20, 2023 |
| Samsung       | DeskTop System              | [715ff16efc](https://linux-hardware.org/?probe=715ff16efc) | Jul 17, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4d00148664](https://linux-hardware.org/?probe=4d00148664) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [75d40e5a2b](https://linux-hardware.org/?probe=75d40e5a2b) | Jul 14, 2023 |
| GPD           | G1618-03                    | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [fc70411ea4](https://linux-hardware.org/?probe=fc70411ea4) | Jul 03, 2023 |
| ASUSTek       | H110M-D                     | [f95d5e83f5](https://linux-hardware.org/?probe=f95d5e83f5) | Jun 25, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [9408842ffc](https://linux-hardware.org/?probe=9408842ffc) | Jun 24, 2023 |
| Biostar       | B450MH                      | [04c924ce6f](https://linux-hardware.org/?probe=04c924ce6f) | Jun 16, 2023 |
| Lenovo        | 315F SDK0J40697 WIN 3305... | [dac73c9b94](https://linux-hardware.org/?probe=dac73c9b94) | Jun 16, 2023 |
| HP            | 1496                        | [7189030996](https://linux-hardware.org/?probe=7189030996) | Jun 11, 2023 |
| HP            | 1496                        | [68db57fde8](https://linux-hardware.org/?probe=68db57fde8) | Jun 10, 2023 |
| AMD           | A88                         | [a7f64b7e4b](https://linux-hardware.org/?probe=a7f64b7e4b) | Jun 05, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Biostar       | B450MH                      | [36947ca7e1](https://linux-hardware.org/?probe=36947ca7e1) | May 30, 2023 |
| Pegatron      | NARRA3                      | [5c016d4faf](https://linux-hardware.org/?probe=5c016d4faf) | May 28, 2023 |
| Unknown       | SKYBAY                      | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| ECS           | G41T-R3                     | [fcbdd2737a](https://linux-hardware.org/?probe=fcbdd2737a) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [96f6b41a5c](https://linux-hardware.org/?probe=96f6b41a5c) | Apr 19, 2023 |
| ECS           | G41T-R3                     | [2c589a38f7](https://linux-hardware.org/?probe=2c589a38f7) | Apr 13, 2023 |
| HP            | 3397                        | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [4eb8132fd2](https://linux-hardware.org/?probe=4eb8132fd2) | Mar 24, 2023 |
| EMAXX TECH... | EMX-B450M-GAMING            | [f147ee8484](https://linux-hardware.org/?probe=f147ee8484) | Mar 21, 2023 |
| ASRock        | B450M Steel Legend          | [ae258d05b1](https://linux-hardware.org/?probe=ae258d05b1) | Mar 16, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [26ecc0b7a2](https://linux-hardware.org/?probe=26ecc0b7a2) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| MSI           | A320M PRO-VH                | [e1266ebf79](https://linux-hardware.org/?probe=e1266ebf79) | Feb 27, 2023 |
| ASUSTek       | A68HM-K                     | [d6f5b00609](https://linux-hardware.org/?probe=d6f5b00609) | Feb 26, 2023 |
| ASUSTek       | A68HM-K                     | [89cd5d5c44](https://linux-hardware.org/?probe=89cd5d5c44) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [99b1ae3224](https://linux-hardware.org/?probe=99b1ae3224) | Feb 25, 2023 |
| MSI           | K9N6PGM2-V2                 | [e88df81d6f](https://linux-hardware.org/?probe=e88df81d6f) | Feb 24, 2023 |
| Biostar       | A320MH                      | [b6f7ef6e4a](https://linux-hardware.org/?probe=b6f7ef6e4a) | Feb 23, 2023 |
| Biostar       | A320MH                      | [e80f86a0bf](https://linux-hardware.org/?probe=e80f86a0bf) | Feb 23, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [eb8434e607](https://linux-hardware.org/?probe=eb8434e607) | Feb 15, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [abe1e578c0](https://linux-hardware.org/?probe=abe1e578c0) | Feb 12, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [cfeb9545a3](https://linux-hardware.org/?probe=cfeb9545a3) | Dec 21, 2022 |
| Biostar       | A520MH                      | [b6c4fdd80b](https://linux-hardware.org/?probe=b6c4fdd80b) | Dec 11, 2022 |
| ASUSTek       | BM5242                      | [d37b75dc52](https://linux-hardware.org/?probe=d37b75dc52) | Dec 10, 2022 |
| ASUSTek       | BM5242                      | [7c17c8d773](https://linux-hardware.org/?probe=7c17c8d773) | Dec 10, 2022 |
| Intel         | D946GZAB AAD66610-302       | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASRock        | B450M Steel Legend          | [4792cdbba2](https://linux-hardware.org/?probe=4792cdbba2) | Nov 21, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| ASUSTek       | A68HM-K                     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | B550 VISION D-P             | [c08b835f58](https://linux-hardware.org/?probe=c08b835f58) | Nov 07, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [7db5fcb7b0](https://linux-hardware.org/?probe=7db5fcb7b0) | Nov 05, 2022 |
| Gigabyte      | B450 AORUS M                | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Gigabyte      | Z97N-WIFI                   | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Gigabyte      | B550M DS3H                  | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fc0a9a6b24](https://linux-hardware.org/?probe=fc0a9a6b24) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [9f52e46640](https://linux-hardware.org/?probe=9f52e46640) | Oct 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [aa7d067a6f](https://linux-hardware.org/?probe=aa7d067a6f) | Oct 11, 2022 |
| Gigabyte      | F2A68HM-S1                  | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [700c5cc2bc](https://linux-hardware.org/?probe=700c5cc2bc) | Oct 05, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | [34c1beb103](https://linux-hardware.org/?probe=34c1beb103) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| Biostar       | A780L3B                     | [bc83f32ddf](https://linux-hardware.org/?probe=bc83f32ddf) | Sep 12, 2022 |
| Biostar       | A780L3B                     | [61057dc040](https://linux-hardware.org/?probe=61057dc040) | Sep 12, 2022 |
| Biostar       | A780L3B                     | [6463bcc136](https://linux-hardware.org/?probe=6463bcc136) | Sep 10, 2022 |
| Biostar       | A780L3B                     | [f65db263d7](https://linux-hardware.org/?probe=f65db263d7) | Sep 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [b77aa249c8](https://linux-hardware.org/?probe=b77aa249c8) | Sep 09, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [dc69b9dde6](https://linux-hardware.org/?probe=dc69b9dde6) | Sep 09, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| HP            | 83F3                        | [71d62174e2](https://linux-hardware.org/?probe=71d62174e2) | Aug 27, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [7a37d5e6a5](https://linux-hardware.org/?probe=7a37d5e6a5) | Aug 07, 2022 |
| Gigabyte      | H77N-WIFI                   | [db237c843c](https://linux-hardware.org/?probe=db237c843c) | Aug 06, 2022 |
| Gigabyte      | H77N-WIFI                   | [5251e7868a](https://linux-hardware.org/?probe=5251e7868a) | Aug 06, 2022 |
| Gigabyte      | H81M-D2V                    | [64da165357](https://linux-hardware.org/?probe=64da165357) | Aug 01, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| Gigabyte      | H410M H V3                  | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| ASUSTek       | M4A88T-M                    | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| YANYU         | EPIC-C19                    | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| MSI           | A320M PRO-VH                | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| Gigabyte      | F2A68HM-S1                  | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| ASUSTek       | H81M-K                      | [512fb81a9b](https://linux-hardware.org/?probe=512fb81a9b) | May 31, 2022 |
| MSI           | Z97 XPOWER AC               | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ECS           | A68M-C4DL                   | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| HP            | 212A                        | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| MSI           | B450M MORTAR                | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| MSI           | H510M-A PRO                 | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| HP            | 2B38                        | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| MSI           | MS-7619                     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| MSI           | H510M PRO-E                 | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [95373e24b7](https://linux-hardware.org/?probe=95373e24b7) | Mar 16, 2022 |
| MSI           | B560M PRO-VDH WIFI          | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| MSI           | H510M PRO-E                 | [ad5840ceb1](https://linux-hardware.org/?probe=ad5840ceb1) | Mar 14, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [a1b757e234](https://linux-hardware.org/?probe=a1b757e234) | Mar 05, 2022 |
| ASUSTek       | H81M-D                      | [4f6714e804](https://linux-hardware.org/?probe=4f6714e804) | Mar 01, 2022 |
| Dell          | 00V62H A01                  | [70f59ecacf](https://linux-hardware.org/?probe=70f59ecacf) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | [2bc13ee0e2](https://linux-hardware.org/?probe=2bc13ee0e2) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | [a8334fb3c3](https://linux-hardware.org/?probe=a8334fb3c3) | Feb 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [f269ebd3a2](https://linux-hardware.org/?probe=f269ebd3a2) | Feb 28, 2022 |
| ASUSTek       | A88XM-PLUS                  | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [da8ce5d5b5](https://linux-hardware.org/?probe=da8ce5d5b5) | Feb 05, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [56bbe3562f](https://linux-hardware.org/?probe=56bbe3562f) | Jan 15, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [266128f234](https://linux-hardware.org/?probe=266128f234) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | [900b250e00](https://linux-hardware.org/?probe=900b250e00) | Jan 05, 2022 |
| Gigabyte      | G41M-Combo                  | [e0b5bc37a4](https://linux-hardware.org/?probe=e0b5bc37a4) | Dec 18, 2021 |
| EMAXX TECH... | EMX-A55GT-iCafe V1.0        | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| ASUSTek       | P8B75-M                     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Gigabyte      | B450M DS3H V2               | [2302fee654](https://linux-hardware.org/?probe=2302fee654) | Nov 09, 2021 |
| MSI           | Z97 GAMING 3                | [249f25308e](https://linux-hardware.org/?probe=249f25308e) | Nov 08, 2021 |
| MSI           | B350M PRO-VDH               | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| ECS           | G41T-R3                     | [892069341e](https://linux-hardware.org/?probe=892069341e) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | [0ac8e061f1](https://linux-hardware.org/?probe=0ac8e061f1) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | [655000678d](https://linux-hardware.org/?probe=655000678d) | Oct 30, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| ASUSTek       | GD30CI                      | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| JOOYON        | IPM41-D3G                   | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| JOOYON        | IPM41-D3G                   | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | [f6388fb1b0](https://linux-hardware.org/?probe=f6388fb1b0) | Sep 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | [a19fc44e26](https://linux-hardware.org/?probe=a19fc44e26) | Sep 07, 2021 |
| Gigabyte      | F2A58M-DS2                  | [8ea19cfa9d](https://linux-hardware.org/?probe=8ea19cfa9d) | Aug 25, 2021 |
| Unknown       | Ionics Carrier Board Adv... | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| ECS           | H81H3-M4                    | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| ASRock        | N68C-GS4 FX                 | [4bf2729f88](https://linux-hardware.org/?probe=4bf2729f88) | Aug 04, 2021 |
| Gigabyte      | F2A68HM-S1                  | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| Gigabyte      | MZGLKCP-00                  | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| Biostar       | H110MHV3                    | [28344398db](https://linux-hardware.org/?probe=28344398db) | Jul 27, 2021 |
| ASRock        | B450M Steel Legend          | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Biostar       | A320MH                      | [16e2552ccc](https://linux-hardware.org/?probe=16e2552ccc) | Jun 20, 2021 |
| Dell          | 040DDP A01                  | [8a9bdad1fd](https://linux-hardware.org/?probe=8a9bdad1fd) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Gigabyte      | H61M-DS2                    | [e31519274b](https://linux-hardware.org/?probe=e31519274b) | May 22, 2021 |
| Gigabyte      | H61M-DS2                    | [523ced455c](https://linux-hardware.org/?probe=523ced455c) | May 22, 2021 |
| Acer          | Aspire X1900                | [c4e0203ed9](https://linux-hardware.org/?probe=c4e0203ed9) | May 19, 2021 |
| MSI           | A68HM-E33 V2                | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| ASRock        | B450M Steel Legend          | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| ASRock        | B450M Steel Legend          | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| ASUSTek       | EX-B365M-V5                 | [c169d54571](https://linux-hardware.org/?probe=c169d54571) | Apr 25, 2021 |
| ASRock        | B450M Steel Legend          | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Gigabyte      | H61M-DS2                    | [f66e7cbdfd](https://linux-hardware.org/?probe=f66e7cbdfd) | Apr 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | Z270 GAMING M7              | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| MSI           | Z97 XPOWER AC               | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [3582928f83](https://linux-hardware.org/?probe=3582928f83) | Feb 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [d392637e95](https://linux-hardware.org/?probe=d392637e95) | Feb 20, 2021 |
| AMD           | A88                         | [11ecb6d298](https://linux-hardware.org/?probe=11ecb6d298) | Feb 14, 2021 |
| Dell          | 0JP3NX A00                  | [3e5d4f837a](https://linux-hardware.org/?probe=3e5d4f837a) | Feb 10, 2021 |
| JOOYON        | IPM41-D3G                   | [6feab903f8](https://linux-hardware.org/?probe=6feab903f8) | Feb 05, 2021 |
| JOOYON        | IPM41-D3G                   | [5fa1dabba9](https://linux-hardware.org/?probe=5fa1dabba9) | Feb 05, 2021 |
| Dell          | 0JP3NX A00                  | [1f5d53a4a2](https://linux-hardware.org/?probe=1f5d53a4a2) | Feb 03, 2021 |
| QTQD          | Unknown                     | [2912607416](https://linux-hardware.org/?probe=2912607416) | Jan 27, 2021 |
| Gigabyte      | H97M-D3H                    | [76f0201d14](https://linux-hardware.org/?probe=76f0201d14) | Jan 26, 2021 |
| MSI           | B450 TOMAHAWK               | [795b4f4c7b](https://linux-hardware.org/?probe=795b4f4c7b) | Jan 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [6e4545c96a](https://linux-hardware.org/?probe=6e4545c96a) | Jan 23, 2021 |
| ASRock        | G41M-VS3                    | [603bb5d8e4](https://linux-hardware.org/?probe=603bb5d8e4) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | [c108942b4e](https://linux-hardware.org/?probe=c108942b4e) | Jan 19, 2021 |
| Acer          | Aspire X1900                | [d0a0250e62](https://linux-hardware.org/?probe=d0a0250e62) | Jan 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [15b8546bd4](https://linux-hardware.org/?probe=15b8546bd4) | Jan 11, 2021 |
| Gigabyte      | AM1M-S2P                    | [433295603d](https://linux-hardware.org/?probe=433295603d) | Jan 09, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [3f75d5f2e1](https://linux-hardware.org/?probe=3f75d5f2e1) | Jan 07, 2021 |
| Gigabyte      | Z370M D3H-CF                | [e6533b7b24](https://linux-hardware.org/?probe=e6533b7b24) | Jan 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [91ccfb9b5a](https://linux-hardware.org/?probe=91ccfb9b5a) | Jan 06, 2021 |
| MSI           | A320M PRO-VD/S V2           | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [031ad52398](https://linux-hardware.org/?probe=031ad52398) | Jan 01, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | [11a5fd5bae](https://linux-hardware.org/?probe=11a5fd5bae) | Dec 30, 2020 |
| MSI           | IONA                        | [bfb84589dd](https://linux-hardware.org/?probe=bfb84589dd) | Dec 28, 2020 |
| MSI           | IONA                        | [0ec5c79eb8](https://linux-hardware.org/?probe=0ec5c79eb8) | Dec 26, 2020 |
| ECS           | H110M-C3D/C3V               | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| ASRock        | N68-S3                      | [bfa6bd97d5](https://linux-hardware.org/?probe=bfa6bd97d5) | Dec 23, 2020 |
| MSI           | MS-7541                     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| ASRock        | A320M-DVS R4.0              | [d186067403](https://linux-hardware.org/?probe=d186067403) | Dec 17, 2020 |
| ASRock        | N68-S3                      | [1d3067d8cb](https://linux-hardware.org/?probe=1d3067d8cb) | Dec 17, 2020 |
| HP            | 8061                        | [0f0bc8b49a](https://linux-hardware.org/?probe=0f0bc8b49a) | Dec 04, 2020 |
| HP            | 8061                        | [a63c8237f1](https://linux-hardware.org/?probe=a63c8237f1) | Dec 04, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| NEC Comput... | IS8XM                       | [57afeee773](https://linux-hardware.org/?probe=57afeee773) | Nov 30, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [354202e98e](https://linux-hardware.org/?probe=354202e98e) | Nov 19, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [f86e0d2af5](https://linux-hardware.org/?probe=f86e0d2af5) | Nov 11, 2020 |
| HP            | 3031h                       | [fb54f48959](https://linux-hardware.org/?probe=fb54f48959) | Nov 10, 2020 |
| HP            | 8061                        | [7936b223e9](https://linux-hardware.org/?probe=7936b223e9) | Nov 10, 2020 |
| ASUSTek       | B85M-G                      | [2c9a8f0838](https://linux-hardware.org/?probe=2c9a8f0838) | Nov 08, 2020 |
| Gigabyte      | Z97N-WIFI                   | [c812c2b6f9](https://linux-hardware.org/?probe=c812c2b6f9) | Nov 07, 2020 |
| Gigabyte      | Z97N-WIFI                   | [e21be2124d](https://linux-hardware.org/?probe=e21be2124d) | Nov 04, 2020 |
| HP            | 8061                        | [d11b92ef18](https://linux-hardware.org/?probe=d11b92ef18) | Nov 01, 2020 |
| Gigabyte      | H81M-DS2                    | [a3cdedf351](https://linux-hardware.org/?probe=a3cdedf351) | Oct 30, 2020 |
| Gigabyte      | F2A78M-HD2                  | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
| Pegatron      | IPMSB-H61                   | [c569d86fff](https://linux-hardware.org/?probe=c569d86fff) | Oct 19, 2020 |
| HP            | 8061                        | [b2cf684801](https://linux-hardware.org/?probe=b2cf684801) | Oct 13, 2020 |
| MSI           | MAG B550M MORTAR            | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [11b8e32835](https://linux-hardware.org/?probe=11b8e32835) | Oct 06, 2020 |
| MSI           | A88XM-E35                   | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| HP            | 8061                        | [1d3e0a6b3d](https://linux-hardware.org/?probe=1d3e0a6b3d) | Sep 25, 2020 |
| ASUSTek       | PRIME B250M-K               | [546b3fec83](https://linux-hardware.org/?probe=546b3fec83) | Sep 16, 2020 |
| ASRock        | A320M-DVS R4.0              | [eaff730455](https://linux-hardware.org/?probe=eaff730455) | Sep 09, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [9557e9d02c](https://linux-hardware.org/?probe=9557e9d02c) | Sep 04, 2020 |
| ASRock        | A320M-DVS R4.0              | [288f4f772c](https://linux-hardware.org/?probe=288f4f772c) | Sep 01, 2020 |
| Biostar       | H81MHV3                     | [ecd87de5e0](https://linux-hardware.org/?probe=ecd87de5e0) | Aug 21, 2020 |
| Dell          | 0VRWRC A00                  | [b5e17b6229](https://linux-hardware.org/?probe=b5e17b6229) | Aug 16, 2020 |
| ASUSTek       | PRIME B250M-K               | [6b5b2287e0](https://linux-hardware.org/?probe=6b5b2287e0) | Aug 07, 2020 |
| HP            | 805D                        | [b0f200fe77](https://linux-hardware.org/?probe=b0f200fe77) | Jul 29, 2020 |
| MSI           | Z170A GAMING M3             | [22963b821f](https://linux-hardware.org/?probe=22963b821f) | Jun 20, 2020 |
| MSI           | Z170A GAMING M3             | [c5779593cc](https://linux-hardware.org/?probe=c5779593cc) | Jun 20, 2020 |
| Biostar       | Hi-Fi A68U3P                | [ec653ae1fc](https://linux-hardware.org/?probe=ec653ae1fc) | Jun 11, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | [5cde7141d6](https://linux-hardware.org/?probe=5cde7141d6) | Jun 02, 2020 |
| Gigabyte      | F2A78M-HD2                  | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| Dell          | 0D28YY A03                  | [7ae56aa829](https://linux-hardware.org/?probe=7ae56aa829) | May 11, 2020 |
| ASUSTek       | P5KPL-AM EPU                | [d4cbef0ab2](https://linux-hardware.org/?probe=d4cbef0ab2) | May 02, 2020 |
| Dell          | 0D28YY A03                  | [285c59f702](https://linux-hardware.org/?probe=285c59f702) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [36bb48017f](https://linux-hardware.org/?probe=36bb48017f) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [1f91672dce](https://linux-hardware.org/?probe=1f91672dce) | Apr 28, 2020 |
| ASRock        | 960GC-GS FX                 | [6b07754d1d](https://linux-hardware.org/?probe=6b07754d1d) | Apr 27, 2020 |
| MSI           | K9N6PGM2-V2                 | [e487e06d2c](https://linux-hardware.org/?probe=e487e06d2c) | Apr 26, 2020 |
| ASRock        | 960GC-GS FX                 | [390a1cbbb3](https://linux-hardware.org/?probe=390a1cbbb3) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | [252b646f8b](https://linux-hardware.org/?probe=252b646f8b) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | [0fe6d54c09](https://linux-hardware.org/?probe=0fe6d54c09) | Apr 25, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [eec2e1e90f](https://linux-hardware.org/?probe=eec2e1e90f) | Apr 24, 2020 |
| Dell          | 0D28YY A03                  | [cb0a381ca1](https://linux-hardware.org/?probe=cb0a381ca1) | Apr 22, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [dbe36dfd4f](https://linux-hardware.org/?probe=dbe36dfd4f) | Apr 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | [06c5a92500](https://linux-hardware.org/?probe=06c5a92500) | Apr 18, 2020 |
| Gigabyte      | F2A68HM-S1                  | [b87b3feefd](https://linux-hardware.org/?probe=b87b3feefd) | Apr 18, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [d092c3db85](https://linux-hardware.org/?probe=d092c3db85) | Apr 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [8eca04a69b](https://linux-hardware.org/?probe=8eca04a69b) | Apr 14, 2020 |
| MSI           | K9N6PGM2-V2                 | [576c3b1853](https://linux-hardware.org/?probe=576c3b1853) | Apr 13, 2020 |
| TriGem Com... | DreamSys                    | [e5a22f4123](https://linux-hardware.org/?probe=e5a22f4123) | Apr 09, 2020 |
| Gigabyte      | H61M-DS2                    | [c00e4e1a0e](https://linux-hardware.org/?probe=c00e4e1a0e) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | [087a36a4bd](https://linux-hardware.org/?probe=087a36a4bd) | Apr 04, 2020 |
| Biostar       | Hi-Fi A68U3P                | [35b973ebbb](https://linux-hardware.org/?probe=35b973ebbb) | Apr 03, 2020 |
| Gigabyte      | H61M-DS2                    | [9355c0ff9e](https://linux-hardware.org/?probe=9355c0ff9e) | Apr 01, 2020 |
| HP            | 0A5Ch                       | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Gigabyte      | H61M-DS2                    | [8c6dbdb971](https://linux-hardware.org/?probe=8c6dbdb971) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | [70b408e2f0](https://linux-hardware.org/?probe=70b408e2f0) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | [be10de1b16](https://linux-hardware.org/?probe=be10de1b16) | Mar 24, 2020 |
| Gigabyte      | Z77X-UD5H                   | [92e778ba2a](https://linux-hardware.org/?probe=92e778ba2a) | Mar 21, 2020 |
| Gigabyte      | H61M-DS2                    | [f7cbec79e8](https://linux-hardware.org/?probe=f7cbec79e8) | Mar 15, 2020 |
| Gigabyte      | H310M DS2                   | [529f84f7d1](https://linux-hardware.org/?probe=529f84f7d1) | Mar 12, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [636f6029b4](https://linux-hardware.org/?probe=636f6029b4) | Mar 11, 2020 |
| Gigabyte      | H61M-DS2                    | [861919e59d](https://linux-hardware.org/?probe=861919e59d) | Mar 08, 2020 |
| MSI           | MS-7309                     | [dff3f373f6](https://linux-hardware.org/?probe=dff3f373f6) | Mar 08, 2020 |
| Gigabyte      | H61M-DS2                    | [2b1b62332c](https://linux-hardware.org/?probe=2b1b62332c) | Mar 08, 2020 |
| MSI           | MS-7309                     | [e52b770dff](https://linux-hardware.org/?probe=e52b770dff) | Mar 08, 2020 |
| MSI           | MS-7309                     | [a06909608c](https://linux-hardware.org/?probe=a06909608c) | Mar 08, 2020 |
| MSI           | MS-7309                     | [b3e1633a13](https://linux-hardware.org/?probe=b3e1633a13) | Mar 08, 2020 |
| ASUSTek       | PRIME B250M-A               | [a1d3a510e8](https://linux-hardware.org/?probe=a1d3a510e8) | Mar 04, 2020 |
| ASUSTek       | PRIME B250M-A               | [6e803cdc23](https://linux-hardware.org/?probe=6e803cdc23) | Mar 02, 2020 |
| ASUSTek       | PRIME B250M-A               | [fb41a1d23f](https://linux-hardware.org/?probe=fb41a1d23f) | Mar 02, 2020 |
| Foxconn       | G31MX Series                | [e3c94b5684](https://linux-hardware.org/?probe=e3c94b5684) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | [c549e93013](https://linux-hardware.org/?probe=c549e93013) | Feb 21, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [75b9cc12a9](https://linux-hardware.org/?probe=75b9cc12a9) | Feb 20, 2020 |
| ASUSTek       | P8H61-M LE                  | [78d658fc64](https://linux-hardware.org/?probe=78d658fc64) | Feb 09, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | [4f64209449](https://linux-hardware.org/?probe=4f64209449) | Feb 07, 2020 |
| Foxconn       | G31MX Series                | [cb21aa111e](https://linux-hardware.org/?probe=cb21aa111e) | Jan 31, 2020 |
| Foxconn       | 2A8C                        | [973270aee7](https://linux-hardware.org/?probe=973270aee7) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | [459627eda2](https://linux-hardware.org/?probe=459627eda2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | [61dfac2df2](https://linux-hardware.org/?probe=61dfac2df2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | [880daf6c76](https://linux-hardware.org/?probe=880daf6c76) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | [0d020faa5c](https://linux-hardware.org/?probe=0d020faa5c) | Jan 24, 2020 |
| Foxconn       | 2A8C                        | [e3389e7b39](https://linux-hardware.org/?probe=e3389e7b39) | Jan 23, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [d5df64e644](https://linux-hardware.org/?probe=d5df64e644) | Dec 29, 2019 |
| ASUSTek       | PRIME B250M-A               | [e4fecb44bc](https://linux-hardware.org/?probe=e4fecb44bc) | Dec 05, 2019 |
| Pegatron      | IPMSB-H61                   | [857c9bddda](https://linux-hardware.org/?probe=857c9bddda) | Nov 07, 2019 |
| Pegatron      | IPMSB-H61                   | [55e7a33a87](https://linux-hardware.org/?probe=55e7a33a87) | Nov 07, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [e5d5c98452](https://linux-hardware.org/?probe=e5d5c98452) | Sep 11, 2019 |
| ASRock        | A780GM-LE                   | [80fb7e01aa](https://linux-hardware.org/?probe=80fb7e01aa) | Aug 22, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [1f7f86ed9e](https://linux-hardware.org/?probe=1f7f86ed9e) | Jul 13, 2019 |
| Gigabyte      | A320M-S2H-CF                | [704346ee85](https://linux-hardware.org/?probe=704346ee85) | Jun 24, 2019 |
| Gigabyte      | A320M-S2H-CF                | [3fb0bfffca](https://linux-hardware.org/?probe=3fb0bfffca) | Jun 24, 2019 |
| Dell          | 01TKCC A01                  | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| ASRock        | 960GC-GS FX                 | [db39b4023e](https://linux-hardware.org/?probe=db39b4023e) | Jun 03, 2019 |
| ASRock        | 960GC-GS FX                 | [833afc1cd1](https://linux-hardware.org/?probe=833afc1cd1) | May 12, 2019 |
| ASRock        | 960GC-GS FX                 | [04903c40d9](https://linux-hardware.org/?probe=04903c40d9) | May 10, 2019 |
| ASRock        | 960GC-GS FX                 | [1d29713c8b](https://linux-hardware.org/?probe=1d29713c8b) | May 02, 2019 |
| Dell          | 01TKCC A01                  | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| Gigabyte      | A320M-S2H-CF                | [ac265b9b6d](https://linux-hardware.org/?probe=ac265b9b6d) | Mar 27, 2019 |
| Lenovo        | No DPK                      | [02bdd4779e](https://linux-hardware.org/?probe=02bdd4779e) | Oct 21, 2018 |
| Lenovo        | No DPK                      | [d98528c04e](https://linux-hardware.org/?probe=d98528c04e) | Oct 21, 2018 |
| MSI           | A68HM-E33 V2                | [aee859c42b](https://linux-hardware.org/?probe=aee859c42b) | Jan 05, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 15       | 6.33%   |
| Ubuntu 22.04       | 11       | 4.64%   |
| Pop!_OS 20.04      | 9        | 3.8%    |
| Ubuntu 18.04       | 8        | 3.38%   |
| Manjaro            | 8        | 3.38%   |
| BlackPanther 18.1  | 7        | 2.95%   |
| Zorin 15           | 5        | 2.11%   |
| OpenMandriva 4.3   | 5        | 2.11%   |
| Linux Mint 21.2    | 5        | 2.11%   |
| KDE neon 20.04     | 5        | 2.11%   |
| Fedora 36          | 5        | 2.11%   |
| Endless 3.7.7      | 5        | 2.11%   |
| Zorin 16           | 4        | 1.69%   |
| Ubuntu 23.04       | 4        | 1.69%   |
| Pop!_OS 22.04      | 4        | 1.69%   |
| Pop!_OS 21.04      | 4        | 1.69%   |
| Pop!_OS 20.10      | 4        | 1.69%   |
| Linux Mint 21      | 4        | 1.69%   |
| Linux Mint 20.2    | 4        | 1.69%   |
| Endless 3.7.6      | 4        | 1.69%   |
| ArcoLinux Rolling  | 4        | 1.69%   |
| Arch Rolling       | 4        | 1.69%   |
| Ubuntu Unity 18.04 | 3        | 1.27%   |
| OpenMandriva 4.2   | 3        | 1.27%   |
| Linux Mint 20.1    | 3        | 1.27%   |
| Kubuntu 22.04      | 3        | 1.27%   |
| KDE neon 22.04     | 3        | 1.27%   |
| Fedora 38          | 3        | 1.27%   |
| Fedora 32          | 3        | 1.27%   |
| Debian 12          | 3        | 1.27%   |
| BlackPanther 16.2  | 3        | 1.27%   |
| Ubuntu 21.10       | 2        | 0.84%   |
| SteamOS 3.4        | 2        | 0.84%   |
| OpenMandriva 23.03 | 2        | 0.84%   |
| Linux Mint 20.3    | 2        | 0.84%   |
| Linux Mint 19.3    | 2        | 0.84%   |
| Kubuntu 22.10      | 2        | 0.84%   |
| Kali 2021.4        | 2        | 0.84%   |
| Fedora 33          | 2        | 0.84%   |
| Endless 3.9.4      | 2        | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 40       | 17.94%  |
| Linux Mint   | 22       | 9.87%   |
| Pop!_OS      | 21       | 9.42%   |
| Fedora       | 17       | 7.62%   |
| Endless      | 16       | 7.17%   |
| OpenMandriva | 15       | 6.73%   |
| Manjaro      | 12       | 5.38%   |
| Zorin        | 9        | 4.04%   |
| KDE neon     | 8        | 3.59%   |
| BlackPanther | 8        | 3.59%   |
| Debian       | 7        | 3.14%   |
| Kubuntu      | 6        | 2.69%   |
| Arch         | 5        | 2.24%   |
| ArcoLinux    | 4        | 1.79%   |
| Ubuntu Unity | 3        | 1.35%   |
| Nobara       | 3        | 1.35%   |
| Kali         | 3        | 1.35%   |
| Xubuntu      | 2        | 0.9%    |
| SteamOS      | 2        | 0.9%    |
| ROSA         | 2        | 0.9%    |
| Garuda Linux | 2        | 0.9%    |
| Elementary   | 2        | 0.9%    |
| Xero         | 1        | 0.45%   |
| Ubuntu MATE  | 1        | 0.45%   |
| Solus        | 1        | 0.45%   |
| Reborn OS    | 1        | 0.45%   |
| Peppermint   | 1        | 0.45%   |
| Parrot       | 1        | 0.45%   |
| openSUSE     | 1        | 0.45%   |
| NixOS        | 1        | 0.45%   |
| MX           | 1        | 0.45%   |
| LMDE         | 1        | 0.45%   |
| Hash Linux   | 1        | 0.45%   |
| Gentoo       | 1        | 0.45%   |
| BunsenLabs   | 1        | 0.45%   |
| BuildRoot    | 1        | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.18.16-desktop-1bP      | 7        | 2.76%   |
| 5.8.0-7630-generic       | 6        | 2.36%   |
| 5.3.0-28-generic         | 6        | 2.36%   |
| 5.16.7-desktop-1omv4003  | 5        | 1.97%   |
| 5.3.0-23-generic         | 4        | 1.57%   |
| 5.4.0-7634-generic       | 3        | 1.18%   |
| 5.4.0-58-generic         | 3        | 1.18%   |
| 5.10.14-desktop-1omv4002 | 3        | 1.18%   |
| 4.9.20-desktop-pae-1bP   | 3        | 1.18%   |
| 6.6.2-desktop-1omv2390   | 2        | 0.79%   |
| 6.2.6-desktop-1omv2390   | 2        | 0.79%   |
| 6.2.0-37-generic         | 2        | 0.79%   |
| 6.2.0-20-generic         | 2        | 0.79%   |
| 6.1.0-13-amd64           | 2        | 0.79%   |
| 5.8.0-36-generic         | 2        | 0.79%   |
| 5.8.0-14-generic         | 2        | 0.79%   |
| 5.4.0-80-generic         | 2        | 0.79%   |
| 5.4.0-74-generic         | 2        | 0.79%   |
| 5.4.0-73-generic         | 2        | 0.79%   |
| 5.4.0-65-generic         | 2        | 0.79%   |
| 5.3.0-46-generic         | 2        | 0.79%   |
| 5.19.0-43-generic        | 2        | 0.79%   |
| 5.19.0-32-generic        | 2        | 0.79%   |
| 5.19.0-23-generic        | 2        | 0.79%   |
| 5.15.0-56-generic        | 2        | 0.79%   |
| 5.15.0-48-generic        | 2        | 0.79%   |
| 5.15.0-41-generic        | 2        | 0.79%   |
| 5.15.0-27-generic        | 2        | 0.79%   |
| 5.13.0-7620-generic      | 2        | 0.79%   |
| 5.13.0-35-generic        | 2        | 0.79%   |
| 5.13.0-30-generic        | 2        | 0.79%   |
| 5.11.0-35-generic        | 2        | 0.79%   |
| 4.18.0-18-generic        | 2        | 0.79%   |
| 4.13.0-32-generic        | 2        | 0.79%   |
| 6.6.6-76060606-generic   | 1        | 0.39%   |
| 6.6.4-arch1-1            | 1        | 0.39%   |
| 6.6.3-arch1-1            | 1        | 0.39%   |
| 6.5.9-300.fc39.x86_64    | 1        | 0.39%   |
| 6.5.9-1-MANJARO          | 1        | 0.39%   |
| 6.5.8-arch1-1            | 1        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 26       | 10.74%  |
| 5.15.0  | 23       | 9.5%    |
| 5.8.0   | 15       | 6.2%    |
| 5.3.0   | 15       | 6.2%    |
| 5.13.0  | 11       | 4.55%   |
| 5.19.0  | 10       | 4.13%   |
| 6.2.0   | 9        | 3.72%   |
| 4.15.0  | 8        | 3.31%   |
| 5.11.0  | 7        | 2.89%   |
| 4.18.16 | 7        | 2.89%   |
| 5.16.7  | 5        | 2.07%   |
| 6.2.6   | 3        | 1.24%   |
| 6.1.0   | 3        | 1.24%   |
| 5.17.5  | 3        | 1.24%   |
| 5.10.14 | 3        | 1.24%   |
| 5.0.0   | 3        | 1.24%   |
| 4.9.20  | 3        | 1.24%   |
| 4.19.0  | 3        | 1.24%   |
| 4.18.0  | 3        | 1.24%   |
| 6.6.2   | 2        | 0.83%   |
| 6.5.9   | 2        | 0.83%   |
| 6.0.7   | 2        | 0.83%   |
| 6.0.0   | 2        | 0.83%   |
| 5.16.0  | 2        | 0.83%   |
| 5.10.0  | 2        | 0.83%   |
| 4.13.0  | 2        | 0.83%   |
| 6.6.6   | 1        | 0.41%   |
| 6.6.4   | 1        | 0.41%   |
| 6.6.3   | 1        | 0.41%   |
| 6.5.8   | 1        | 0.41%   |
| 6.5.7   | 1        | 0.41%   |
| 6.5.5   | 1        | 0.41%   |
| 6.5.4   | 1        | 0.41%   |
| 6.5.3   | 1        | 0.41%   |
| 6.5.0   | 1        | 0.41%   |
| 6.4.4   | 1        | 0.41%   |
| 6.4.3   | 1        | 0.41%   |
| 6.4.11  | 1        | 0.41%   |
| 6.4.1   | 1        | 0.41%   |
| 6.4.0   | 1        | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 29       | 12.13%  |
| 5.4     | 27       | 11.3%   |
| 5.8     | 18       | 7.53%   |
| 6.2     | 16       | 6.69%   |
| 5.19    | 16       | 6.69%   |
| 5.3     | 15       | 6.28%   |
| 6.1     | 12       | 5.02%   |
| 5.13    | 12       | 5.02%   |
| 5.10    | 12       | 5.02%   |
| 4.18    | 10       | 4.18%   |
| 5.11    | 8        | 3.35%   |
| 4.15    | 8        | 3.35%   |
| 6.5     | 7        | 2.93%   |
| 5.16    | 7        | 2.93%   |
| 6.0     | 6        | 2.51%   |
| 6.6     | 5        | 2.09%   |
| 6.4     | 5        | 2.09%   |
| 4.9     | 5        | 2.09%   |
| 5.18    | 3        | 1.26%   |
| 5.17    | 3        | 1.26%   |
| 5.0     | 3        | 1.26%   |
| 4.19    | 3        | 1.26%   |
| 6.3     | 2        | 0.84%   |
| 5.9     | 2        | 0.84%   |
| 4.13    | 2        | 0.84%   |
| 5.7     | 1        | 0.42%   |
| 5.14    | 1        | 0.42%   |
| 5.1     | 1        | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 208      | 97.2%   |
| i686   | 5        | 2.34%   |
| armv7l | 1        | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 94       | 42.34%  |
| KDE5            | 64       | 28.83%  |
| X-Cinnamon      | 19       | 8.56%   |
| XFCE            | 14       | 6.31%   |
| Unknown         | 14       | 6.31%   |
| MATE            | 4        | 1.8%    |
| KDE             | 3        | 1.35%   |
| Unity           | 2        | 0.9%    |
| LXQt            | 2        | 0.9%    |
| Pantheon        | 1        | 0.45%   |
| openbox         | 1        | 0.45%   |
| LXDE            | 1        | 0.45%   |
| GNOME Flashback | 1        | 0.45%   |
| Budgie          | 1        | 0.45%   |
| awesome         | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 174      | 80.93%  |
| Wayland | 28       | 13.02%  |
| Tty     | 7        | 3.26%   |
| Unknown | 6        | 2.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 122      | 54.95%  |
| SDDM    | 45       | 20.27%  |
| GDM3    | 23       | 10.36%  |
| LightDM | 17       | 7.66%   |
| GDM     | 13       | 5.86%   |
| TDM     | 2        | 0.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| en_PH            | 111      | 49.55%  |
| en_US            | 82       | 36.61%  |
| Unknown          | 19       | 8.48%   |
| C                | 6        | 2.68%   |
| en_GB            | 2        | 0.89%   |
| ja_JP            | 1        | 0.45%   |
| en_US.ISO-8859-1 | 1        | 0.45%   |
| en_HK            | 1        | 0.45%   |
| de_DE            | 1        | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 125      | 57.6%   |
| EFI  | 92       | 42.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 158      | 70.85%  |
| Btrfs   | 30       | 13.45%  |
| Overlay | 21       | 9.42%   |
| Tmpfs   | 8        | 3.59%   |
| Unknown | 4        | 1.79%   |
| Xfs     | 2        | 0.9%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 124      | 56.36%  |
| GPT     | 73       | 33.18%  |
| MBR     | 23       | 10.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 181      | 80.8%   |
| Yes       | 43       | 19.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 161      | 72.2%   |
| Yes       | 62       | 27.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 50       | 23.58%  |
| ASUSTek Computer    | 41       | 19.34%  |
| MSI                 | 39       | 18.4%   |
| Hewlett-Packard     | 14       | 6.6%    |
| ASRock              | 14       | 6.6%    |
| Dell                | 8        | 3.77%   |
| Biostar             | 8        | 3.77%   |
| ECS                 | 6        | 2.83%   |
| Foxconn             | 5        | 2.36%   |
| EMAXX TECHNOLOGY    | 4        | 1.89%   |
| Pegatron            | 3        | 1.42%   |
| Lenovo              | 3        | 1.42%   |
| Unknown             | 3        | 1.42%   |
| Intel               | 2        | 0.94%   |
| AMD                 | 2        | 0.94%   |
| Acer                | 2        | 0.94%   |
| YANYU               | 1        | 0.47%   |
| TriGem Computer     | 1        | 0.47%   |
| Samsung Electronics | 1        | 0.47%   |
| QTQD                | 1        | 0.47%   |
| NEC Computers       | 1        | 0.47%   |
| JOOYON              | 1        | 0.47%   |
| GPD                 | 1        | 0.47%   |
| Colorful Technology | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7309                   | 5        | 2.36%   |
| Gigabyte F2A68HM-S1           | 5        | 2.36%   |
| Gigabyte A320M-S2H V2         | 5        | 2.36%   |
| ASRock B450M Steel Legend     | 5        | 2.36%   |
| MSI MS-7721                   | 4        | 1.89%   |
| ASUS P8H61-M LX3 PLUS R2.0    | 4        | 1.89%   |
| ASUS All Series               | 4        | 1.89%   |
| Unknown                       | 4        | 1.89%   |
| Foxconn G31MX Series          | 3        | 1.42%   |
| ECS G41T-R3                   | 3        | 1.42%   |
| Pegatron IPMSB-H61            | 2        | 0.94%   |
| MSI MS-7C94                   | 2        | 0.94%   |
| MSI MS-7C52                   | 2        | 0.94%   |
| Gigabyte Z590 AORUS ULTRA     | 2        | 0.94%   |
| Gigabyte H97M-D3H             | 2        | 0.94%   |
| Gigabyte H410M H V3           | 2        | 0.94%   |
| Gigabyte B450 AORUS M         | 2        | 0.94%   |
| Gigabyte A320M-S2H            | 2        | 0.94%   |
| Foxconn 500B Microtower       | 2        | 0.94%   |
| Biostar A320MH                | 2        | 0.94%   |
| ASUS PRIME B250M-K            | 2        | 0.94%   |
| ASUS PRIME B250M-A            | 2        | 0.94%   |
| ASUS EX-H310M-V3 R2.0         | 2        | 0.94%   |
| ASUS A68HM-K                  | 2        | 0.94%   |
| AMD A88                       | 2        | 0.94%   |
| YANYU EPIC-C19                | 1        | 0.47%   |
| TriGem DreamSys               | 1        | 0.47%   |
| Samsung DeskTop System        | 1        | 0.47%   |
| Pegatron FR440AA-ABU a6652uk  | 1        | 0.47%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.47%   |
| MSI MS-7D90                   | 1        | 0.47%   |
| MSI MS-7D43                   | 1        | 0.47%   |
| MSI MS-7D23                   | 1        | 0.47%   |
| MSI MS-7D22                   | 1        | 0.47%   |
| MSI MS-7D18                   | 1        | 0.47%   |
| MSI MS-7D17                   | 1        | 0.47%   |
| MSI MS-7D14                   | 1        | 0.47%   |
| MSI MS-7C96                   | 1        | 0.47%   |
| MSI MS-7C56                   | 1        | 0.47%   |
| MSI MS-7C51                   | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Gigabyte A320M-S2H            | 7        | 3.3%    |
| Dell OptiPlex                 | 7        | 3.3%    |
| ASUS PRIME                    | 7        | 3.3%    |
| HP Compaq                     | 6        | 2.83%   |
| ASUS P8H61-M                  | 6        | 2.83%   |
| MSI MS-7309                   | 5        | 2.36%   |
| Gigabyte F2A68HM-S1           | 5        | 2.36%   |
| ASRock B450M                  | 5        | 2.36%   |
| MSI MS-7721                   | 4        | 1.89%   |
| Gigabyte B450                 | 4        | 1.89%   |
| ASUS TUF                      | 4        | 1.89%   |
| ASUS ROG                      | 4        | 1.89%   |
| ASUS All                      | 4        | 1.89%   |
| Unknown                       | 4        | 1.89%   |
| HP ProDesk                    | 3        | 1.42%   |
| Foxconn G31MX                 | 3        | 1.42%   |
| ECS G41T-R3                   | 3        | 1.42%   |
| Pegatron IPMSB-H61            | 2        | 0.94%   |
| MSI MS-7C94                   | 2        | 0.94%   |
| MSI MS-7C52                   | 2        | 0.94%   |
| Gigabyte Z590                 | 2        | 0.94%   |
| Gigabyte X570                 | 2        | 0.94%   |
| Gigabyte H97M-D3H             | 2        | 0.94%   |
| Gigabyte H410M                | 2        | 0.94%   |
| Gigabyte B550                 | 2        | 0.94%   |
| Foxconn 500B                  | 2        | 0.94%   |
| Biostar A320MH                | 2        | 0.94%   |
| ASUS EX-H310M-V3              | 2        | 0.94%   |
| ASUS A68HM-K                  | 2        | 0.94%   |
| AMD A88                       | 2        | 0.94%   |
| YANYU EPIC-C19                | 1        | 0.47%   |
| TriGem DreamSys               | 1        | 0.47%   |
| Samsung DeskTop               | 1        | 0.47%   |
| Pegatron FR440AA-ABU          | 1        | 0.47%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.47%   |
| MSI MS-7D90                   | 1        | 0.47%   |
| MSI MS-7D43                   | 1        | 0.47%   |
| MSI MS-7D23                   | 1        | 0.47%   |
| MSI MS-7D22                   | 1        | 0.47%   |
| MSI MS-7D18                   | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 23       | 10.85%  |
| 2014    | 22       | 10.38%  |
| 2012    | 18       | 8.49%   |
| 2015    | 17       | 8.02%   |
| 2020    | 15       | 7.08%   |
| 2019    | 15       | 7.08%   |
| 2017    | 15       | 7.08%   |
| 2010    | 15       | 7.08%   |
| 2021    | 14       | 6.6%    |
| 2013    | 13       | 6.13%   |
| 2009    | 11       | 5.19%   |
| 2011    | 10       | 4.72%   |
| 2016    | 6        | 2.83%   |
| 2007    | 4        | 1.89%   |
| 2006    | 4        | 1.89%   |
| 2023    | 3        | 1.42%   |
| 2022    | 3        | 1.42%   |
| 2008    | 3        | 1.42%   |
| Unknown | 1        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 212      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 205      | 96.24%  |
| Enabled  | 8        | 3.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 212      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 53       | 23.98%  |
| 16.01-24.0  | 43       | 19.46%  |
| 4.01-8.0    | 40       | 18.1%   |
| 3.01-4.0    | 40       | 18.1%   |
| 32.01-64.0  | 22       | 9.95%   |
| 64.01-256.0 | 8        | 3.62%   |
| 1.01-2.0    | 8        | 3.62%   |
| 2.01-3.0    | 5        | 2.26%   |
| 24.01-32.0  | 2        | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 72       | 30.25%  |
| 2.01-3.0    | 59       | 24.79%  |
| 4.01-8.0    | 38       | 15.97%  |
| 3.01-4.0    | 29       | 12.18%  |
| 0.51-1.0    | 17       | 7.14%   |
| 8.01-16.0   | 12       | 5.04%   |
| 0.01-0.5    | 7        | 2.94%   |
| 16.01-24.0  | 2        | 0.84%   |
| 24.01-32.0  | 1        | 0.42%   |
| 64.01-256.0 | 1        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 98       | 43.56%  |
| 2      | 74       | 32.89%  |
| 3      | 20       | 8.89%   |
| 4      | 19       | 8.44%   |
| 5      | 7        | 3.11%   |
| 6      | 2        | 0.89%   |
| 0      | 2        | 0.89%   |
| 14     | 1        | 0.44%   |
| 13     | 1        | 0.44%   |
| 12     | 1        | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 78.08%  |
| Yes       | 48       | 21.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 210      | 98.59%  |
| No        | 3        | 1.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 58.14%  |
| Yes       | 90       | 41.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 72.43%  |
| Yes       | 59       | 27.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Philippines | 212      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Quezon City       | 43       | 18.07%  |
| Davao City        | 16       | 6.72%   |
| Cagayan de Oro    | 12       | 5.04%   |
| Manila            | 10       | 4.2%    |
| Angeles City      | 10       | 4.2%    |
| Caloocan City     | 9        | 3.78%   |
| Makati City       | 8        | 3.36%   |
| Iligan City       | 8        | 3.36%   |
| Bacolod City      | 8        | 3.36%   |
| San Miguel        | 6        | 2.52%   |
| Mandaluyong City  | 6        | 2.52%   |
| Cebu City         | 6        | 2.52%   |
| Bacoor            | 6        | 2.52%   |
| Tarlac City       | 5        | 2.1%    |
| Paranaque City    | 5        | 2.1%    |
| Lipa City         | 5        | 2.1%    |
| Zamboanga City    | 4        | 1.68%   |
| Santa Rosa        | 4        | 1.68%   |
| San Juan          | 3        | 1.26%   |
| Pasig             | 3        | 1.26%   |
| Manajao           | 3        | 1.26%   |
| Imus              | 3        | 1.26%   |
| Iloilo City       | 3        | 1.26%   |
| Calamba           | 3        | 1.26%   |
| Antipolo City     | 3        | 1.26%   |
| San Fernando City | 2        | 0.84%   |
| Mandaue City      | 2        | 0.84%   |
| Magugpo Poblacion | 2        | 0.84%   |
| Lahug             | 2        | 0.84%   |
| General Santos    | 2        | 0.84%   |
| Dumaguete         | 2        | 0.84%   |
| Abaga             | 2        | 0.84%   |
| Valencia          | 1        | 0.42%   |
| Tuguegarao City   | 1        | 0.42%   |
| Taytay            | 1        | 0.42%   |
| Tanza             | 1        | 0.42%   |
| Taguig            | 1        | 0.42%   |
| Tagbilaran        | 1        | 0.42%   |
| Tabaco            | 1        | 0.42%   |
| Sibulan           | 1        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 82       | 119    | 21.13%  |
| WDC                         | 67       | 92     | 17.27%  |
| Kingston                    | 29       | 40     | 7.47%   |
| Samsung Electronics         | 28       | 43     | 7.22%   |
| Toshiba                     | 24       | 31     | 6.19%   |
| Hitachi                     | 19       | 34     | 4.9%    |
| SanDisk                     | 15       | 23     | 3.87%   |
| Crucial                     | 8        | 11     | 2.06%   |
| Transcend                   | 7        | 7      | 1.8%    |
| Lexar                       | 7        | 8      | 1.8%    |
| Team                        | 6        | 8      | 1.55%   |
| Gigabyte Technology         | 6        | 11     | 1.55%   |
| A-DATA Technology           | 6        | 8      | 1.55%   |
| Ramsta                      | 5        | 5      | 1.29%   |
| PNY                         | 5        | 6      | 1.29%   |
| Phison Electronics          | 5        | 8      | 1.29%   |
| Unknown                     | 4        | 5      | 1.03%   |
| Micron/Crucial Technology   | 4        | 9      | 1.03%   |
| HGST                        | 4        | 5      | 1.03%   |
| WALRAM                      | 3        | 4      | 0.77%   |
| SK hynix                    | 3        | 9      | 0.77%   |
| KingSpec                    | 3        | 4      | 0.77%   |
| Intel                       | 3        | 4      | 0.77%   |
| Fujitsu                     | 3        | 3      | 0.77%   |
| Unknown                     | 3        | 4      | 0.77%   |
| XPG                         | 2        | 2      | 0.52%   |
| Phison                      | 2        | 2      | 0.52%   |
| Patriot                     | 2        | 2      | 0.52%   |
| Kingston Technology Company | 2        | 2      | 0.52%   |
| JMicron Technology          | 2        | 2      | 0.52%   |
| Indilinx                    | 2        | 2      | 0.52%   |
| HS-SSD-C100                 | 2        | 2      | 0.52%   |
| ZOTAC                       | 1        | 1      | 0.26%   |
| XrayDisk                    | 1        | 1      | 0.26%   |
| Voyager                     | 1        | 1      | 0.26%   |
| USB                         | 1        | 1      | 0.26%   |
| TAMMUZ                      | 1        | 1      | 0.26%   |
| T-FORCE                     | 1        | 1      | 0.26%   |
| SKIHOTAR                    | 1        | 1      | 0.26%   |
| Realtek Semiconductor       | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB                    | 13       | 3%      |
| Seagate ST500DM002-1BD142 500GB                   | 12       | 2.76%   |
| Toshiba DT01ACA050 500GB                          | 7        | 1.61%   |
| Kingston SA400S37120G 120GB SSD                   | 6        | 1.38%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 5        | 1.15%   |
| Toshiba DT01ACA100 1TB                            | 5        | 1.15%   |
| Seagate ST4000DM004-2CV104 4TB                    | 5        | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB                    | 5        | 1.15%   |
| Hitachi HDS721050CLA362 500GB                     | 5        | 1.15%   |
| Samsung SSD 860 EVO 500GB                         | 4        | 0.92%   |
| Samsung SSD 860 EVO 250GB                         | 4        | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4        | 0.92%   |
| Kingston SA400S37480G 480GB SSD                   | 4        | 0.92%   |
| Kingston SA400S37240G 240GB SSD                   | 4        | 0.92%   |
| Hitachi HDS721616PLA380 160GB                     | 4        | 0.92%   |
| WDC WD5000AZLX-60K2TA0 500GB                      | 3        | 0.69%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 3        | 0.69%   |
| Transcend TS128GSSD370S 128GB                     | 3        | 0.69%   |
| Toshiba MQ01ABD100 1TB                            | 3        | 0.69%   |
| Seagate ST500DM002-1ER14C 500GB                   | 3        | 0.69%   |
| Seagate ST3160812AS 160GB                         | 3        | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB                    | 3        | 0.69%   |
| SanDisk SSD PLUS 1000GB                           | 3        | 0.69%   |
| SanDisk SDSSDA240G 240GB                          | 3        | 0.69%   |
| PNY CS900 240GB SSD                               | 3        | 0.69%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 3        | 0.69%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB               | 3        | 0.69%   |
| Lexar 128GB SSD                                   | 3        | 0.69%   |
| Hitachi HTS543232A7A384 320GB                     | 3        | 0.69%   |
| Hitachi HDS721050CLA660 500GB                     | 3        | 0.69%   |
| Crucial CT500P2SSD8 500GB                         | 3        | 0.69%   |
| Unknown                                           | 3        | 0.69%   |
| WDC WD5003ABYZ-011FA0 500GB                       | 2        | 0.46%   |
| WDC WD5000AAVS-00ZTB0 500GB                       | 2        | 0.46%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 2        | 0.46%   |
| WDC WD20EARX-00ZUDB0 2TB                          | 2        | 0.46%   |
| WDC WD10EZEX-08M2NA0 1TB                          | 2        | 0.46%   |
| WDC WD10EZEX-00WN4A0 1TB                          | 2        | 0.46%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 2        | 0.46%   |
| WDC WD1003FZEX-00K3CA0 1TB                        | 2        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 80       | 115    | 40%     |
| WDC                 | 64       | 84     | 32%     |
| Toshiba             | 23       | 28     | 11.5%   |
| Hitachi             | 19       | 34     | 9.5%    |
| HGST                | 4        | 5      | 2%      |
| Samsung Electronics | 3        | 4      | 1.5%    |
| Fujitsu             | 3        | 3      | 1.5%    |
| Unknown             | 2        | 2      | 1%      |
| XrayDisk            | 1        | 1      | 0.5%    |
| ExcelStor           | 1        | 1      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 25       | 32     | 19.84%  |
| Samsung Electronics | 13       | 22     | 10.32%  |
| SanDisk             | 12       | 14     | 9.52%   |
| WDC                 | 6        | 8      | 4.76%   |
| Transcend           | 6        | 6      | 4.76%   |
| Team                | 6        | 8      | 4.76%   |
| Lexar               | 6        | 7      | 4.76%   |
| A-DATA Technology   | 5        | 7      | 3.97%   |
| PNY                 | 4        | 5      | 3.17%   |
| Crucial             | 4        | 6      | 3.17%   |
| Ramsta              | 3        | 3      | 2.38%   |
| KingSpec            | 3        | 4      | 2.38%   |
| Intel               | 3        | 4      | 2.38%   |
| Gigabyte Technology | 3        | 4      | 2.38%   |
| Toshiba             | 2        | 2      | 1.59%   |
| SK hynix            | 2        | 8      | 1.59%   |
| Patriot             | 2        | 2      | 1.59%   |
| ZOTAC               | 1        | 1      | 0.79%   |
| WALRAM              | 1        | 1      | 0.79%   |
| Unknown             | 1        | 2      | 0.79%   |
| TAMMUZ              | 1        | 1      | 0.79%   |
| SKIHOTAR            | 1        | 1      | 0.79%   |
| Seagate             | 1        | 2      | 0.79%   |
| MCTECH              | 1        | 1      | 0.79%   |
| Kingmax             | 1        | 1      | 0.79%   |
| Kimtigo             | 1        | 2      | 0.79%   |
| Indilinx            | 1        | 1      | 0.79%   |
| HS-SSD-E100         | 1        | 1      | 0.79%   |
| HS-SSD-C100         | 1        | 1      | 0.79%   |
| Hikvision           | 1        | 2      | 0.79%   |
| GLOWAY              | 1        | 2      | 0.79%   |
| FORESEE             | 1        | 1      | 0.79%   |
| Dahua               | 1        | 1      | 0.79%   |
| Corsair             | 1        | 1      | 0.79%   |
| China               | 1        | 10     | 0.79%   |
| CERVVO              | 1        | 1      | 0.79%   |
| BR                  | 1        | 1      | 0.79%   |
| Unknown             | 1        | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 161      | 277    | 50.31%  |
| SSD     | 99       | 177    | 30.94%  |
| NVMe    | 46       | 80     | 14.38%  |
| Unknown | 13       | 17     | 4.06%   |
| MMC     | 1        | 1      | 0.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 195      | 457    | 77.08%  |
| NVMe | 46       | 80     | 18.18%  |
| SAS  | 11       | 14     | 4.35%   |
| MMC  | 1        | 1      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 161      | 302    | 63.14%  |
| 0.51-1.0   | 65       | 108    | 25.49%  |
| 1.01-2.0   | 17       | 22     | 6.67%   |
| 3.01-4.0   | 9        | 19     | 3.53%   |
| 4.01-10.0  | 2        | 2      | 0.78%   |
| 10.01-20.0 | 1        | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 68       | 29.18%  |
| 251-500        | 51       | 21.89%  |
| 501-1000       | 25       | 10.73%  |
| 1001-2000      | 24       | 10.3%   |
| 1-20           | 15       | 6.44%   |
| 51-100         | 15       | 6.44%   |
| More than 3000 | 14       | 6.01%   |
| 2001-3000      | 10       | 4.29%   |
| Unknown        | 6        | 2.58%   |
| 21-50          | 5        | 2.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 78       | 32.77%  |
| 21-50          | 42       | 17.65%  |
| 51-100         | 30       | 12.61%  |
| 101-250        | 28       | 11.76%  |
| 251-500        | 18       | 7.56%   |
| 501-1000       | 14       | 5.88%   |
| 1001-2000      | 10       | 4.2%    |
| 2001-3000      | 7        | 2.94%   |
| Unknown        | 6        | 2.52%   |
| More than 3000 | 5        | 2.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| Hitachi HDS721050CLA362 500GB                                 | 5        | 10     | 15.15%  |
| Hitachi HTS543232A7A384 320GB                                 | 3        | 5      | 9.09%   |
| Unknown S050 Hard drive 500GB                                 | 2        | 2      | 6.06%   |
| HGST HTS541010A9E680 1TB                                      | 2        | 3      | 6.06%   |
| WDC WD5003ABYZ-011FA0 500GB                                   | 1        | 1      | 3.03%   |
| WDC WD5000LPCX-60VHAT0 500GB                                  | 1        | 2      | 3.03%   |
| WDC WD5000AAVS-00ZTB0 500GB                                   | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-603CA0 500GB                                   | 1        | 1      | 3.03%   |
| WDC WD3200AAJS-08L7A0 320GB                                   | 1        | 1      | 3.03%   |
| WDC WD10EZEX-00MFCA0 1TB                                      | 1        | 1      | 3.03%   |
| Toshiba MQ01ABD100 1TB                                        | 1        | 1      | 3.03%   |
| Toshiba DT01ACA100 1TB                                        | 1        | 1      | 3.03%   |
| Toshiba DT01ACA050 500GB                                      | 1        | 1      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB                               | 1        | 2      | 3.03%   |
| Seagate ST500DM002 500GB                                      | 1        | 1      | 3.03%   |
| Seagate ST380815AS 80GB                                       | 1        | 1      | 3.03%   |
| Seagate ST3500514NS 500GB                                     | 1        | 1      | 3.03%   |
| Seagate ST3500418AS 500GB                                     | 1        | 1      | 3.03%   |
| Seagate ST2000DM008-2FR102 2TB                                | 1        | 1      | 3.03%   |
| SanDisk SSD PLUS 1000GB                                       | 1        | 1      | 3.03%   |
| SanDisk SDSSDA240G 240GB                                      | 1        | 1      | 3.03%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 2      | 3.03%   |
| Kingston SA400S37240G 240GB SSD                               | 1        | 1      | 3.03%   |
| Hitachi HUA721010KLA330 1TB                                   | 1        | 2      | 3.03%   |
| Hitachi HDS721050CLA660 500GB                                 | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 7        | 18     | 24.14%  |
| WDC                 | 6        | 7      | 20.69%  |
| Seagate             | 6        | 7      | 20.69%  |
| Unknown             | 2        | 2      | 6.9%    |
| Toshiba             | 2        | 3      | 6.9%    |
| SanDisk             | 2        | 2      | 6.9%    |
| HGST                | 2        | 3      | 6.9%    |
| Samsung Electronics | 1        | 2      | 3.45%   |
| Kingston            | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 7        | 18     | 28%     |
| WDC     | 6        | 7      | 24%     |
| Seagate | 6        | 7      | 24%     |
| Unknown | 2        | 2      | 8%      |
| Toshiba | 2        | 3      | 8%      |
| HGST    | 2        | 3      | 8%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 40     | 84%     |
| SSD  | 3        | 3      | 12%     |
| NVMe | 1        | 2      | 4%      |

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
| Detected | 136      | 344    | 58.37%  |
| Works    | 73       | 163    | 31.33%  |
| Malfunc  | 24       | 45     | 10.3%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 114      | 42.54%  |
| AMD                          | 86       | 32.09%  |
| Samsung Electronics          | 13       | 4.85%   |
| Phison Electronics           | 10       | 3.73%   |
| Nvidia                       | 9        | 3.36%   |
| Micron/Crucial Technology    | 7        | 2.61%   |
| Kingston Technology Company  | 6        | 2.24%   |
| Silicon Motion               | 3        | 1.12%   |
| SanDisk                      | 3        | 1.12%   |
| Marvell Technology Group     | 3        | 1.12%   |
| ASMedia Technology           | 3        | 1.12%   |
| ADATA Technology             | 3        | 1.12%   |
| JMicron Technology           | 2        | 0.75%   |
| Toshiba America Info Systems | 1        | 0.37%   |
| SK hynix                     | 1        | 0.37%   |
| Realtek Semiconductor        | 1        | 0.37%   |
| MAXIO Technology (Hangzhou)  | 1        | 0.37%   |
| Broadcom / LSI               | 1        | 0.37%   |
| Biwin Storage Technology     | 1        | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 50       | 13.77%  |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 5.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18       | 4.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15       | 4.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 4.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 2.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10       | 2.75%   |
| AMD FCH SATA Controller D                                                               | 10       | 2.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 2.75%   |
| Nvidia MCP61 SATA Controller                                                            | 9        | 2.48%   |
| Nvidia MCP61 IDE                                                                        | 9        | 2.48%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9        | 2.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 2.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 1.93%   |
| AMD FCH IDE Controller                                                                  | 7        | 1.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 6        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5        | 1.38%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 1.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 1.1%    |
| Intel SATA Controller [RAID Mode]                                                       | 4        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 0.83%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 3        | 0.83%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.83%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 3        | 0.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.83%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 2        | 0.55%   |
| JMicron JMB58x AHCI SATA controller                                                     | 2        | 0.55%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 164      | 59.42%  |
| IDE  | 59       | 21.38%  |
| NVMe | 46       | 16.67%  |
| RAID | 6        | 2.17%   |
| SAS  | 1        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 116      | 54.72%  |
| AMD    | 95       | 44.81%  |
| ARM    | 1        | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 9        | 4.25%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6        | 2.83%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 6        | 2.83%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 6        | 2.83%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 5        | 2.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 1.89%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4        | 1.89%   |
| AMD Sempron Processor LE-1100                 | 4        | 1.89%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 4        | 1.89%   |
| AMD A6-6400K APU with Radeon HD Graphics      | 4        | 1.89%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3        | 1.42%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3        | 1.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3        | 1.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 1.42%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 3        | 1.42%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3        | 1.42%   |
| Intel 12th Gen Core i5-12400                  | 3        | 1.42%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3        | 1.42%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2        | 0.94%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 2        | 0.94%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2        | 0.94%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 0.94%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2        | 0.94%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 0.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2        | 0.94%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 2        | 0.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2        | 0.94%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2        | 0.94%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2        | 0.94%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2        | 0.94%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2        | 0.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 0.94%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz          | 2        | 0.94%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 2        | 0.94%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 2        | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2        | 0.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2        | 0.94%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2        | 0.94%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2        | 0.94%   |
| AMD A6-7480 Radeon R5, 8 Compute Cores 2C+6G  | 2        | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 39       | 18.4%   |
| AMD Ryzen 5             | 30       | 14.15%  |
| Intel Core i7           | 17       | 8.02%   |
| Intel Core i3           | 16       | 7.55%   |
| Intel Core 2 Duo        | 12       | 5.66%   |
| Other                   | 10       | 4.72%   |
| AMD Ryzen 3             | 10       | 4.72%   |
| AMD A6                  | 10       | 4.72%   |
| AMD Ryzen 7             | 6        | 2.83%   |
| Intel Pentium Dual-Core | 5        | 2.36%   |
| Intel Core 2 Quad       | 5        | 2.36%   |
| Intel Celeron           | 5        | 2.36%   |
| AMD A8                  | 5        | 2.36%   |
| Intel Pentium           | 4        | 1.89%   |
| AMD Sempron             | 4        | 1.89%   |
| AMD FX                  | 4        | 1.89%   |
| AMD A4                  | 4        | 1.89%   |
| AMD A10                 | 4        | 1.89%   |
| AMD Phenom II X4        | 3        | 1.42%   |
| AMD Athlon II X2        | 3        | 1.42%   |
| AMD Athlon              | 3        | 1.42%   |
| Intel Pentium Gold      | 2        | 0.94%   |
| AMD Ryzen 9             | 2        | 0.94%   |
| Intel Xeon              | 1        | 0.47%   |
| Intel Core i9           | 1        | 0.47%   |
| Intel Core 2            | 1        | 0.47%   |
| AMD Ryzen 7 PRO         | 1        | 0.47%   |
| AMD Ryzen 5 PRO         | 1        | 0.47%   |
| AMD Phenom II X2        | 1        | 0.47%   |
| AMD Phenom              | 1        | 0.47%   |
| AMD Athlon X4           | 1        | 0.47%   |
| AMD Athlon 64 X2        | 1        | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 77       | 36.32%  |
| 2      | 62       | 29.25%  |
| 6      | 41       | 19.34%  |
| 1      | 17       | 8.02%   |
| 8      | 10       | 4.72%   |
| 16     | 2        | 0.94%   |
| 12     | 1        | 0.47%   |
| 10     | 1        | 0.47%   |
| 3      | 1        | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 211      | 99.53%  |
| 2      | 1        | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 120      | 56.34%  |
| 1      | 93       | 43.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 210      | 98.59%  |
| Unknown        | 3        | 1.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 73       | 33.64%  |
| 0x306c3    | 14       | 6.45%   |
| 0x1067a    | 12       | 5.53%   |
| 0x08701021 | 10       | 4.61%   |
| 0x06001119 | 9        | 4.15%   |
| 0x306a9    | 8        | 3.69%   |
| 0x0800820d | 7        | 3.23%   |
| 0x906e9    | 6        | 2.76%   |
| 0x06003106 | 6        | 2.76%   |
| 0x906ea    | 5        | 2.3%    |
| 0x506e3    | 5        | 2.3%    |
| 0x10676    | 5        | 2.3%    |
| 0xa0671    | 4        | 1.84%   |
| 0x206a7    | 4        | 1.84%   |
| 0x0a50000d | 4        | 1.84%   |
| 0x08108109 | 4        | 1.84%   |
| 0x08600106 | 3        | 1.38%   |
| 0xa0655    | 2        | 0.92%   |
| 0x6fb      | 2        | 0.92%   |
| 0x08101016 | 2        | 0.92%   |
| 0x0810100b | 2        | 0.92%   |
| 0x0600611a | 2        | 0.92%   |
| 0x010000c8 | 2        | 0.92%   |
| 0x010000c7 | 2        | 0.92%   |
| 0xa0653    | 1        | 0.46%   |
| 0x90675    | 1        | 0.46%   |
| 0x90672    | 1        | 0.46%   |
| 0x706a1    | 1        | 0.46%   |
| 0x6f6      | 1        | 0.46%   |
| 0x50654    | 1        | 0.46%   |
| 0x406f1    | 1        | 0.46%   |
| 0x40651    | 1        | 0.46%   |
| 0x30679    | 1        | 0.46%   |
| 0x106e5    | 1        | 0.46%   |
| 0x0a601206 | 1        | 0.46%   |
| 0x0a601203 | 1        | 0.46%   |
| 0x0a50000c | 1        | 0.46%   |
| 0x0a20102b | 1        | 0.46%   |
| 0x0a201016 | 1        | 0.46%   |
| 0x08701030 | 1        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 21       | 9.86%   |
| Penryn           | 20       | 9.39%   |
| KabyLake         | 18       | 8.45%   |
| Zen 2            | 16       | 7.51%   |
| Piledriver       | 16       | 7.51%   |
| IvyBridge        | 16       | 7.51%   |
| Zen+             | 15       | 7.04%   |
| Zen 3            | 10       | 4.69%   |
| Zen              | 9        | 4.23%   |
| SandyBridge      | 9        | 4.23%   |
| Skylake          | 8        | 3.76%   |
| K10              | 8        | 3.76%   |
| Steamroller      | 7        | 3.29%   |
| CometLake        | 7        | 3.29%   |
| K8 Hammer        | 5        | 2.35%   |
| Unknown          | 5        | 2.35%   |
| Excavator        | 4        | 1.88%   |
| Icelake          | 3        | 1.41%   |
| Core             | 3        | 1.41%   |
| Alderlake Hybrid | 3        | 1.41%   |
| Nehalem          | 2        | 0.94%   |
| Tremont          | 1        | 0.47%   |
| TigerLake        | 1        | 0.47%   |
| Silvermont       | 1        | 0.47%   |
| K10 Llano        | 1        | 0.47%   |
| Jaguar           | 1        | 0.47%   |
| Goldmont plus    | 1        | 0.47%   |
| Bulldozer        | 1        | 0.47%   |
| Broadwell        | 1        | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 82       | 35.04%  |
| AMD    | 82       | 35.04%  |
| Intel  | 70       | 29.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11       | 4.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 10       | 4.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 3.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 7        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.9%    |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 2.49%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 6        | 2.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 2.49%   |
| Intel HD Graphics 630                                                       | 6        | 2.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 2.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 2.49%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 2.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5        | 2.07%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 2.07%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 2.07%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 2.07%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 2.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.66%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 1.66%   |
| Intel HD Graphics 530                                                       | 4        | 1.66%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 4        | 1.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.66%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 1.66%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 1.66%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.24%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.24%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 3        | 1.24%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.24%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 3        | 1.24%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 1.24%   |
| AMD Richland [Radeon HD 8470D]                                              | 3        | 1.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 3        | 1.24%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.83%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.83%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.83%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 79       | 35.75%  |
| 1 x Nvidia     | 73       | 33.03%  |
| 1 x Intel      | 57       | 25.79%  |
| Intel + Nvidia | 6        | 2.71%   |
| 2 x Nvidia     | 2        | 0.9%    |
| Other          | 1        | 0.45%   |
| 2 x AMD        | 1        | 0.45%   |
| Intel + AMD    | 1        | 0.45%   |
| AMD + Nvidia   | 1        | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 160      | 74.42%  |
| Proprietary | 46       | 21.4%   |
| Unknown     | 9        | 4.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 98       | 44.34%  |
| 1.01-2.0   | 38       | 17.19%  |
| 0.51-1.0   | 19       | 8.6%    |
| 0.01-0.5   | 19       | 8.6%    |
| 3.01-4.0   | 16       | 7.24%   |
| 7.01-8.0   | 14       | 6.33%   |
| 5.01-6.0   | 9        | 4.07%   |
| 8.01-16.0  | 6        | 2.71%   |
| 2.01-3.0   | 2        | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 31       | 14.42%  |
| Dell                 | 28       | 13.02%  |
| AOC                  | 19       | 8.84%   |
| Acer                 | 17       | 7.91%   |
| Hewlett-Packard      | 12       | 5.58%   |
| Goldstar             | 9        | 4.19%   |
| ASUSTek Computer     | 9        | 4.19%   |
| BenQ                 | 7        | 3.26%   |
| Lenovo               | 6        | 2.79%   |
| IPS                  | 6        | 2.79%   |
| Ancor Communications | 6        | 2.79%   |
| Sony                 | 5        | 2.33%   |
| Unknown              | 5        | 2.33%   |
| ViewSonic            | 4        | 1.86%   |
| Mi                   | 4        | 1.86%   |
| Unknown              | 3        | 1.4%    |
| Philips              | 3        | 1.4%    |
| VIE                  | 2        | 0.93%   |
| Unknown (XXX)        | 2        | 0.93%   |
| SGT                  | 2        | 0.93%   |
| MStar                | 2        | 0.93%   |
| MSI                  | 2        | 0.93%   |
| eMachines            | 2        | 0.93%   |
| Eizo                 | 2        | 0.93%   |
| SMC                  | 1        | 0.47%   |
| Sharp                | 1        | 0.47%   |
| SANYO                | 1        | 0.47%   |
| SAC                  | 1        | 0.47%   |
| RGT                  | 1        | 0.47%   |
| Pixio                | 1        | 0.47%   |
| NVS                  | 1        | 0.47%   |
| NVISION              | 1        | 0.47%   |
| NVI                  | 1        | 0.47%   |
| NEX                  | 1        | 0.47%   |
| LLL                  | 1        | 0.47%   |
| IOD                  | 1        | 0.47%   |
| Huion                | 1        | 0.47%   |
| HSI                  | 1        | 0.47%   |
| HON                  | 1        | 0.47%   |
| HKC                  | 1        | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 5        | 2.2%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 4        | 1.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 1.76%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                    | 4        | 1.76%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 4        | 1.76%   |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch              | 3        | 1.32%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 3        | 1.32%   |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                      | 3        | 1.32%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                      | 2        | 0.88%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2        | 0.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.88%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 2        | 0.88%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 2        | 0.88%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2        | 0.88%   |
| IPS ZP2200 IPS2200 1920x1080 477x268mm 21.5-inch                      | 2        | 0.88%   |
| IPS 21.5HQ-LED IPS2150 1920x1080 475x267mm 21.5-inch                  | 2        | 0.88%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.88%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 0.88%   |
| Dell P170S DEL4059 1280x1024 338x270mm 17.0-inch                      | 2        | 0.88%   |
| Dell E228WFP DELD015 1680x1050 473x296mm 22.0-inch                    | 2        | 0.88%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                     | 2        | 0.88%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 2        | 0.88%   |
| ASUSTek Computer VG27AQL1A AUS2705 2560x1440 597x336mm 27.0-inch      | 2        | 0.88%   |
| AOC 22B2WG5 AOC2202 1920x1080 477x268mm 21.5-inch                     | 2        | 0.88%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                        | 2        | 0.88%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 2        | 0.88%   |
| Acer S200HQL ACR0359 1920x1080 435x239mm 19.5-inch                    | 2        | 0.88%   |
| Acer R230H ACR046E 1920x1080 509x286mm 23.0-inch                      | 2        | 0.88%   |
| Acer KA220HQ ACR0497 1920x1080 477x268mm 21.5-inch                    | 2        | 0.88%   |
| Acer EB192Q ACR0517 1366x768 410x230mm 18.5-inch                      | 2        | 0.88%   |
| ViewSonic XG2705 VSC0E39 1920x1080 600x340mm 27.2-inch                | 1        | 0.44%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1        | 0.44%   |
| ViewSonic VA1917 SERIES VSCAD30 1366x768 410x230mm 18.5-inch          | 1        | 0.44%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch            | 1        | 0.44%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.44%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 0.44%   |
| Unknown (XXX) Beyond TV XXX2851 2560x1440 1209x680mm 54.6-inch        | 1        | 0.44%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.44%   |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.44%   |
| Sony TV SNY4B03 1920x1080 708x398mm 32.0-inch                         | 1        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 93       | 44.93%  |
| 1366x768 (WXGA)    | 31       | 14.98%  |
| 1280x1024 (SXGA)   | 19       | 9.18%   |
| 3840x2160 (4K)     | 14       | 6.76%   |
| 1600x900 (HD+)     | 14       | 6.76%   |
| 2560x1440 (QHD)    | 8        | 3.86%   |
| 1440x900 (WXGA+)   | 7        | 3.38%   |
| 3440x1440          | 5        | 2.42%   |
| 1680x1050 (WSXGA+) | 3        | 1.45%   |
| 2288x1287          | 2        | 0.97%   |
| 1920x1200 (WUXGA)  | 2        | 0.97%   |
| 1360x768           | 2        | 0.97%   |
| 1024x768 (XGA)     | 2        | 0.97%   |
| Unknown            | 2        | 0.97%   |
| 3200x1080          | 1        | 0.48%   |
| 2966x900           | 1        | 0.48%   |
| 1920x540           | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 32       | 14.61%  |
| 18      | 26       | 11.87%  |
| 23      | 20       | 9.13%   |
| Unknown | 18       | 8.22%   |
| 27      | 17       | 7.76%   |
| 24      | 17       | 7.76%   |
| 20      | 15       | 6.85%   |
| 19      | 15       | 6.85%   |
| 17      | 14       | 6.39%   |
| 15      | 7        | 3.2%    |
| 34      | 5        | 2.28%   |
| 32      | 5        | 2.28%   |
| 31      | 5        | 2.28%   |
| 22      | 5        | 2.28%   |
| 72      | 4        | 1.83%   |
| 54      | 3        | 1.37%   |
| 52      | 3        | 1.37%   |
| 142     | 2        | 0.91%   |
| 40      | 2        | 0.91%   |
| 84      | 1        | 0.46%   |
| 58      | 1        | 0.46%   |
| 50      | 1        | 0.46%   |
| 39      | 1        | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 84       | 39.81%  |
| 501-600        | 49       | 23.22%  |
| 301-350        | 21       | 9.95%   |
| Unknown        | 18       | 8.53%   |
| 701-800        | 10       | 4.74%   |
| 1001-1500      | 8        | 3.79%   |
| 601-700        | 6        | 2.84%   |
| 351-400        | 5        | 2.37%   |
| 1501-2000      | 5        | 2.37%   |
| 801-900        | 3        | 1.42%   |
| More than 2000 | 2        | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 140      | 69.65%  |
| 5/4     | 18       | 8.96%   |
| Unknown | 18       | 8.96%   |
| 16/10   | 16       | 7.96%   |
| 21/9    | 5        | 2.49%   |
| 4/3     | 2        | 1%      |
| 1.00    | 2        | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 24.06%  |
| 151-200        | 45       | 21.23%  |
| 141-150        | 38       | 17.92%  |
| Unknown        | 18       | 8.49%   |
| 301-350        | 17       | 8.02%   |
| More than 1000 | 15       | 7.08%   |
| 351-500        | 15       | 7.08%   |
| 101-110        | 6        | 2.83%   |
| 251-300        | 3        | 1.42%   |
| 501-1000       | 3        | 1.42%   |
| 91-100         | 1        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 116      | 57.14%  |
| 101-120 | 51       | 25.12%  |
| Unknown | 18       | 8.87%   |
| 1-50    | 15       | 7.39%   |
| 161-240 | 2        | 0.99%   |
| 121-160 | 1        | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 166      | 76.85%  |
| 2     | 36       | 16.67%  |
| 0     | 14       | 6.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 160      | 53.87%  |
| Intel                                 | 52       | 17.51%  |
| Ralink Technology                     | 19       | 6.4%    |
| Qualcomm Atheros                      | 13       | 4.38%   |
| TP-Link                               | 9        | 3.03%   |
| Nvidia                                | 7        | 2.36%   |
| Samsung Electronics                   | 6        | 2.02%   |
| MediaTek                              | 4        | 1.35%   |
| JMicron Technology                    | 3        | 1.01%   |
| Huawei Technologies                   | 3        | 1.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 1.01%   |
| Xiaomi                                | 2        | 0.67%   |
| Ralink                                | 2        | 0.67%   |
| OPPO Electronics                      | 2        | 0.67%   |
| D-Link                                | 2        | 0.67%   |
| Broadcom                              | 2        | 0.67%   |
| Tenda                                 | 1        | 0.34%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.34%   |
| Qualcomm Atheros Communications       | 1        | 0.34%   |
| Qualcomm                              | 1        | 0.34%   |
| ICS Advent                            | 1        | 0.34%   |
| D-Link System                         | 1        | 0.34%   |
| Broadcom Limited                      | 1        | 0.34%   |
| ASIX Electronics                      | 1        | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                                 | 139      | 41%     |
| Realtek RTL8125 2.5GbE Controller                                                                      | 12       | 3.54%   |
| Realtek 802.11ac NIC                                                                                   | 10       | 2.95%   |
| Ralink MT7601U Wireless Adapter                                                                        | 10       | 2.95%   |
| Intel Wi-Fi 6 AX200                                                                                    | 9        | 2.65%   |
| Nvidia MCP61 Ethernet                                                                                  | 7        | 2.06%   |
| Intel I211 Gigabit Network Connection                                                                  | 7        | 2.06%   |
| Intel Ethernet Controller I225-V                                                                       | 6        | 1.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                  | 5        | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                  | 5        | 1.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                  | 4        | 1.18%   |
| Ralink RT5370 Wireless Adapter                                                                         | 4        | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 3        | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 3        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 3        | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 3        | 0.88%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                                                    | 3        | 0.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                              | 3        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 3        | 0.88%   |
| Intel 82579V Gigabit Network Connection                                                                | 3        | 0.88%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                                          | 2        | 0.59%   |
| Samsung E2530 Phone (Samsung Kies mode)                                                                | 2        | 0.59%   |
| Realtek 802.11n WLAN Adapter                                                                           | 2        | 0.59%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2        | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 2        | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 2        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                          | 2        | 0.59%   |
| OPPO SM8350-IDP _SN:361A1B3C                                                                           | 2        | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                          | 2        | 0.59%   |
| Intel Ethernet Connection I217-V                                                                       | 2        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                                                   | 2        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                                                  | 2        | 0.59%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                       | 2        | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                                             | 2        | 0.59%   |
| Huawei STG-LX1                                                                                         | 2        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                         | 1        | 0.29%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                                   | 1        | 0.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1        | 0.29%   |
| TP-Link Archer T4U ver.3                                                                               | 1        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 28       | 28.28%  |
| Intel                                 | 23       | 23.23%  |
| Ralink Technology                     | 19       | 19.19%  |
| TP-Link                               | 9        | 9.09%   |
| Qualcomm Atheros                      | 5        | 5.05%   |
| MediaTek                              | 4        | 4.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 3.03%   |
| Ralink                                | 2        | 2.02%   |
| D-Link                                | 2        | 2.02%   |
| Tenda                                 | 1        | 1.01%   |
| Samsung Electronics                   | 1        | 1.01%   |
| Qualcomm Atheros Communications       | 1        | 1.01%   |
| Broadcom                              | 1        | 1.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                                                                   | 10       | 10%     |
| Ralink MT7601U Wireless Adapter                                                                        | 10       | 10%     |
| Intel Wi-Fi 6 AX200                                                                                    | 9        | 9%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                  | 4        | 4%      |
| Ralink RT5370 Wireless Adapter                                                                         | 4        | 4%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 3        | 3%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 3        | 3%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 3        | 3%      |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 3        | 3%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                              | 3        | 3%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 3        | 3%      |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 3%      |
| Realtek 802.11n WLAN Adapter                                                                           | 2        | 2%      |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2        | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 2        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 2        | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                          | 2        | 2%      |
| Intel Alder Lake-S PCH CNVi WiFi                                                                       | 2        | 2%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1        | 1%      |
| TP-Link Archer T4U ver.3                                                                               | 1        | 1%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                                 | 1        | 1%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                    | 1        | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                             | 1        | 1%      |
| TP-Link 802.11ac WLAN Adapter                                                                          | 1        | 1%      |
| Tenda U12                                                                                              | 1        | 1%      |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                                       | 1        | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                        | 1        | 1%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                             | 1        | 1%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                                 | 1        | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 1%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                                | 1        | 1%      |
| Ralink RT3072 Wireless Adapter                                                                         | 1        | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                              | 1        | 1%      |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                                   | 1        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 1%      |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 1%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                          | 1        | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                | 1        | 1%      |
| Intel Wireless 7260                                                                                    | 1        | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 157      | 67.67%  |
| Intel                             | 40       | 17.24%  |
| Qualcomm Atheros                  | 9        | 3.88%   |
| Nvidia                            | 7        | 3.02%   |
| Samsung Electronics               | 3        | 1.29%   |
| JMicron Technology                | 3        | 1.29%   |
| Xiaomi                            | 2        | 0.86%   |
| OPPO Electronics                  | 2        | 0.86%   |
| Huawei Technologies               | 2        | 0.86%   |
| Sundance Technology Inc / IC Plus | 1        | 0.43%   |
| Qualcomm                          | 1        | 0.43%   |
| ICS Advent                        | 1        | 0.43%   |
| D-Link System                     | 1        | 0.43%   |
| Broadcom Limited                  | 1        | 0.43%   |
| Broadcom                          | 1        | 0.43%   |
| ASIX Electronics                  | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 139      | 58.9%   |
| Realtek RTL8125 2.5GbE Controller                                          | 12       | 5.08%   |
| Nvidia MCP61 Ethernet                                                      | 7        | 2.97%   |
| Intel I211 Gigabit Network Connection                                      | 7        | 2.97%   |
| Intel Ethernet Controller I225-V                                           | 6        | 2.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 5        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 5        | 2.12%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                        | 3        | 1.27%   |
| Intel 82579V Gigabit Network Connection                                    | 3        | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 2        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.85%   |
| OPPO SM8350-IDP _SN:361A1B3C                                               | 2        | 0.85%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.85%   |
| Huawei STG-LX1                                                             | 2        | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.42%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 1        | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1        | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.42%   |
| Qualcomm Redmi 9T                                                          | 1        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.42%   |
| Intel PRO/100 VM Network Connection                                        | 1        | 0.42%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.42%   |
| Intel Ethernet Controller I226-V                                           | 1        | 0.42%   |
| Intel Ethernet Connection I217-LM                                          | 1        | 0.42%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.42%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.42%   |
| Intel Ethernet Connection (14) I219-V                                      | 1        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                      | 1        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 210      | 69.31%  |
| WiFi     | 90       | 29.7%   |
| Modem    | 3        | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 171      | 76.34%  |
| WiFi     | 53       | 23.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 168      | 77.78%  |
| 2     | 35       | 16.2%   |
| 3     | 10       | 4.63%   |
| 6     | 2        | 0.93%   |
| 0     | 1        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 199      | 92.13%  |
| Yes  | 17       | 7.87%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 22       | 37.29%  |
| Cambridge Silicon Radio    | 19       | 32.2%   |
| Realtek Semiconductor      | 6        | 10.17%  |
| Broadcom                   | 4        | 6.78%   |
| IMC Networks               | 2        | 3.39%   |
| TP-Link                    | 1        | 1.69%   |
| Ralink                     | 1        | 1.69%   |
| MediaTek                   | 1        | 1.69%   |
| Lite-On Technology         | 1        | 1.69%   |
| Integrated System Solution | 1        | 1.69%   |
| Unknown                    | 1        | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 19       | 32.2%   |
| Intel AX200 Bluetooth                                 | 8        | 13.56%  |
| Realtek Bluetooth Radio                               | 5        | 8.47%   |
| Intel AX201 Bluetooth                                 | 4        | 6.78%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 5.08%   |
| Intel AX210 Bluetooth                                 | 3        | 5.08%   |
| Intel Bluetooth wireless interface                    | 2        | 3.39%   |
| Broadcom BCM2035 Bluetooth                            | 2        | 3.39%   |
| TP-Link UB500 Adapter                                 | 1        | 1.69%   |
| Realtek RTL8723B Bluetooth                            | 1        | 1.69%   |
| Ralink RT3290 Bluetooth                               | 1        | 1.69%   |
| MediaTek Wireless_Device                              | 1        | 1.69%   |
| Lite-On Bluetooth Device                              | 1        | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 1.69%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 1.69%   |
| IMC Networks Wireless_Device                          | 1        | 1.69%   |
| IMC Networks Bluetooth Device                         | 1        | 1.69%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 1.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 1.69%   |
| Unknown                                               | 1        | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 114      | 33.53%  |
| AMD                         | 102      | 30%     |
| Nvidia                      | 80       | 23.53%  |
| C-Media Electronics         | 9        | 2.65%   |
| KTMicro                     | 4        | 1.18%   |
| Generalplus Technology      | 4        | 1.18%   |
| Kingston Technology         | 3        | 0.88%   |
| SteelSeries ApS             | 2        | 0.59%   |
| Razer USA                   | 2        | 0.59%   |
| Logitech                    | 2        | 0.59%   |
| JMTek                       | 2        | 0.59%   |
| GN Netcom                   | 2        | 0.59%   |
| Giga-Byte Technology        | 2        | 0.59%   |
| ZOOM                        | 1        | 0.29%   |
| XMOS                        | 1        | 0.29%   |
| M-Audio                     | 1        | 0.29%   |
| Fry's Electronics           | 1        | 0.29%   |
| FiiO Electronics Technology | 1        | 0.29%   |
| FIFINE 683 Microphone       | 1        | 0.29%   |
| Elgato Systems              | 1        | 0.29%   |
| Corsair                     | 1        | 0.29%   |
| Cooler Master               | 1        | 0.29%   |
| ASUSTek Computer            | 1        | 0.29%   |
| Arturia                     | 1        | 0.29%   |
| AKAI Professional M.I.      | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 25       | 5.95%   |
| AMD FCH Azalia Controller                                                         | 24       | 5.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 18       | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 17       | 4.05%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17       | 4.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15       | 3.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 13       | 3.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 12       | 2.86%   |
| Nvidia GF108 High Definition Audio Controller                                     | 11       | 2.62%   |
| Intel 200 Series PCH HD Audio                                                     | 11       | 2.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 2.38%   |
| Nvidia MCP61 High Definition Audio                                                | 9        | 2.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 9        | 2.14%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 9        | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 8        | 1.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 1.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 1.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 1.67%   |
| AMD Trinity HDMI Audio Controller                                                 | 6        | 1.43%   |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5        | 1.19%   |
| Nvidia GA102 High Definition Audio Controller                                     | 5        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 5        | 1.19%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 5        | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.95%   |
| KTMicro KT_USB_AUDIO                                                              | 4        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 0.95%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 4        | 0.95%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 0.95%   |
| Generalplus Technology USB Audio Device                                           | 4        | 0.95%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 0.95%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.71%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                                | 3        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 25.49%  |
| Unknown             | 11       | 10.78%  |
| Team                | 10       | 9.8%    |
| Samsung Electronics | 8        | 7.84%   |
| G.Skill             | 8        | 7.84%   |
| SK hynix            | 7        | 6.86%   |
| Corsair             | 7        | 6.86%   |
| Crucial             | 5        | 4.9%    |
| Unknown             | 4        | 3.92%   |
| PNY                 | 2        | 1.96%   |
| Patriot             | 2        | 1.96%   |
| Kingmax             | 2        | 1.96%   |
| Uroad               | 1        | 0.98%   |
| Unknown (89BA)      | 1        | 0.98%   |
| Unknown (0x0B79)    | 1        | 0.98%   |
| Unifosa             | 1        | 0.98%   |
| Transcend           | 1        | 0.98%   |
| Silicon Power       | 1        | 0.98%   |
| Nanya Technology    | 1        | 0.98%   |
| Mitsubishi          | 1        | 0.98%   |
| Carry               | 1        | 0.98%   |
| A-DATA Technology   | 1        | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 4        | 3.77%   |
| Unknown                                                     | 4        | 3.77%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s         | 3        | 2.83%   |
| Kingston RAM KF2666C16D4/8G 8GB DIMM DDR4 2667MT/s          | 3        | 2.83%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s         | 3        | 2.83%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 2        | 1.89%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s         | 2        | 1.89%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s         | 2        | 1.89%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s             | 2        | 1.89%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s        | 2        | 1.89%   |
| Kingston RAM HX313C9F/8 8GB DIMM DDR3 1333MT/s              | 2        | 1.89%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s       | 2        | 1.89%   |
| Corsair RAM CMT128GX4M4C3200C16 32GB DIMM DDR4 3200MT/s     | 2        | 1.89%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s         | 2        | 1.89%   |
| Uroad RAM WJD8G4M16P12800 8192MB DIMM DDR3 1600MT/s         | 1        | 0.94%   |
| Unknown RAM Module 8192MB DIMM                              | 1        | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 1        | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                   | 1        | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                   | 1        | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                   | 1        | 0.94%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                        | 1        | 0.94%   |
| Unknown RAM Module 4096MB DIMM DDR2                         | 1        | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                   | 1        | 0.94%   |
| Unknown RAM Module 1GB DIMM DDR2                            | 1        | 0.94%   |
| Unknown RAM Module 16384MB DIMM DDR4 2666MT/s               | 1        | 0.94%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                 | 1        | 0.94%   |
| Unknown RAM Module 1024MB DIMM DDR2                         | 1        | 0.94%   |
| Unknown RAM KZ24UE5116HAR8 8192MB DIMM DDR4 2400MT/s        | 1        | 0.94%   |
| Unknown (89BA) RAM MMV16GD426C19S 16GB SODIMM DDR4 2667MT/s | 1        | 0.94%   |
| Unknown (0x0B79) RAM Module 8GB DIMM DDR4 3200MT/s          | 1        | 0.94%   |
| Unifosa RAM GU512303EP0202 2048MB DIMM DDR3 1333MT/s        | 1        | 0.94%   |
| Transcend RAM TS2GLH64V4B 16384MB DIMM DDR4 2400MT/s        | 1        | 0.94%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s          | 1        | 0.94%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 0.94%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s               | 1        | 0.94%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s                  | 1        | 0.94%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s        | 1        | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1        | 0.94%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s     | 1        | 0.94%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB DIMM DDR4 2400MT/s        | 1        | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 53       | 58.89%  |
| DDR3    | 28       | 31.11%  |
| DDR2    | 4        | 4.44%   |
| Unknown | 2        | 2.22%   |
| SDRAM   | 1        | 1.11%   |
| LPDDR4  | 1        | 1.11%   |
| DDR5    | 1        | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 86       | 94.51%  |
| SODIMM       | 4        | 4.4%    |
| Row Of Chips | 1        | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 45       | 46.39%  |
| 4096  | 22       | 22.68%  |
| 16384 | 12       | 12.37%  |
| 32768 | 11       | 11.34%  |
| 2048  | 4        | 4.12%   |
| 1024  | 3        | 3.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 16.67%  |
| 3200    | 11       | 11.46%  |
| 2133    | 9        | 9.38%   |
| 2667    | 8        | 8.33%   |
| 2400    | 7        | 7.29%   |
| 3733    | 6        | 6.25%   |
| 3600    | 6        | 6.25%   |
| 1333    | 5        | 5.21%   |
| 2666    | 4        | 4.17%   |
| 3866    | 3        | 3.13%   |
| 3800    | 3        | 3.13%   |
| Unknown | 3        | 3.13%   |
| 1867    | 2        | 2.08%   |
| 1800    | 2        | 2.08%   |
| 6000    | 1        | 1.04%   |
| 4333    | 1        | 1.04%   |
| 4267    | 1        | 1.04%   |
| 3500    | 1        | 1.04%   |
| 3466    | 1        | 1.04%   |
| 2933    | 1        | 1.04%   |
| 2448    | 1        | 1.04%   |
| 1648    | 1        | 1.04%   |
| 1067    | 1        | 1.04%   |
| 800     | 1        | 1.04%   |
| 667     | 1        | 1.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 3        | 42.86%  |
| Canon              | 2        | 28.57%  |
| Hewlett-Packard    | 1        | 14.29%  |
| Brother Industries | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Seiko Epson L120 Series   | 2        | 28.57%  |
| Seiko Epson L3110 Series  | 1        | 14.29%  |
| HP Smart Tank 610 series  | 1        | 14.29%  |
| Canon PIXMA MG2500 Series | 1        | 14.29%  |
| Canon G2010 series        | 1        | 14.29%  |
| Brother DCP-T700W         | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 9        | 15.79%  |
| Microdia                      | 7        | 12.28%  |
| A4Tech                        | 7        | 12.28%  |
| Z-Star Microelectronics       | 4        | 7.02%   |
| Realtek Semiconductor         | 4        | 7.02%   |
| Jieli Technology              | 4        | 7.02%   |
| Pixart Imaging                | 3        | 5.26%   |
| Cubeternet                    | 3        | 5.26%   |
| Samsung Electronics           | 2        | 3.51%   |
| Razer USA                     | 2        | 3.51%   |
| Generalplus Technology        | 2        | 3.51%   |
| Apple                         | 2        | 3.51%   |
| WaveRider Communications      | 1        | 1.75%   |
| Sunplus Innovation Technology | 1        | 1.75%   |
| Silicon Motion                | 1        | 1.75%   |
| OPPO Electronics              | 1        | 1.75%   |
| KYE Systems (Mouse Systems)   | 1        | 1.75%   |
| Aveo Technology               | 1        | 1.75%   |
| ARC International             | 1        | 1.75%   |
| Alcor Micro                   | 1        | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Jieli USB PHY 2.0                                                   | 4        | 7.02%   |
| Z-Star Venus USB2.0 Camera                                          | 3        | 5.26%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                | 3        | 5.26%   |
| Microdia Integrated Camera                                          | 3        | 5.26%   |
| Logitech Webcam C270                                                | 3        | 5.26%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 2        | 3.51%   |
| Microdia Sonix USB 2.0 Camera                                       | 2        | 3.51%   |
| Logitech HD Webcam C910                                             | 2        | 3.51%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                  | 2        | 3.51%   |
| A4Tech USB Live camera                                              | 2        | 3.51%   |
| A4Tech FHD 1080P PC Camera                                          | 2        | 3.51%   |
| A4Tech A4tech FHD 1080P PC Camera                                   | 2        | 3.51%   |
| Z-Star A4 TECH USB2.0 PC Camera J                                   | 1        | 1.75%   |
| WaveRider USB 2.0 Camera                                            | 1        | 1.75%   |
| Sunplus Full HD webcam                                              | 1        | 1.75%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 1.75%   |
| Samsung USB2.0 UVC HQ WebCam                                        | 1        | 1.75%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 1.75%   |
| Realtek HP 1.0MP High Definition Webcam                             | 1        | 1.75%   |
| Realtek HD Camera                                                   | 1        | 1.75%   |
| Realtek Front Camera                                                | 1        | 1.75%   |
| Realtek BRI-S90AF                                                   | 1        | 1.75%   |
| OPPO WAIPIO-MTP _SN:2B7F7E2C                                        | 1        | 1.75%   |
| Microdia USB 2.0 Camera                                             | 1        | 1.75%   |
| Microdia rapoo camera                                               | 1        | 1.75%   |
| Logitech StreamCam                                                  | 1        | 1.75%   |
| Logitech HD Webcam B910                                             | 1        | 1.75%   |
| Logitech HD Pro Webcam C920                                         | 1        | 1.75%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 1.75%   |
| KYE Systems (Mouse Systems) Genius Webcam                           | 1        | 1.75%   |
| Generalplus GENERAL WEBCAM                                          | 1        | 1.75%   |
| Generalplus 808 Camera                                              | 1        | 1.75%   |
| Cubeternet USB2.0 Camera                                            | 1        | 1.75%   |
| Cubeternet GL-UPC822 UVC WebCam                                     | 1        | 1.75%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.75%   |
| Aveo UVC camera (Bresser microscope)                                | 1        | 1.75%   |
| ARC International Camera                                            | 1        | 1.75%   |
| Alcor Micro USB 2.0 Camera                                          | 1        | 1.75%   |
| A4Tech PC Camera                                                    | 1        | 1.75%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 187      | 85.39%  |
| 1     | 27       | 12.33%  |
| 2     | 4        | 1.83%   |
| 3     | 1        | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 14       | 37.84%  |
| Graphics card            | 13       | 35.14%  |
| Communication controller | 2        | 5.41%   |
| Unassigned class         | 1        | 2.7%    |
| Storage/raid             | 1        | 2.7%    |
| Sound                    | 1        | 2.7%    |
| Network                  | 1        | 2.7%    |
| Net/ethernet             | 1        | 2.7%    |
| Chipcard                 | 1        | 2.7%    |
| Camera                   | 1        | 2.7%    |
| Bluetooth                | 1        | 2.7%    |

