ArcoLinux - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

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

Total: 764

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Supermicro    | A2SAN-E-WOHSA               | [f8d0b19c1e](https://linux-hardware.org/?probe=f8d0b19c1e) | Jul 01, 2022 |
| MSI           | MEG X570 UNIFY              | [0fbd5ca967](https://linux-hardware.org/?probe=0fbd5ca967) | Jun 29, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [cf7b4fb7e1](https://linux-hardware.org/?probe=cf7b4fb7e1) | Jun 29, 2022 |
| Biostar       | J3060NH                     | [6cefe763b7](https://linux-hardware.org/?probe=6cefe763b7) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| MSI           | B450-A PRO MAX              | [23b355d820](https://linux-hardware.org/?probe=23b355d820) | Jun 27, 2022 |
| MSI           | B250 GAMING M3              | [b294a7b0b1](https://linux-hardware.org/?probe=b294a7b0b1) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [e3fcc67ecc](https://linux-hardware.org/?probe=e3fcc67ecc) | Jun 26, 2022 |
| Dell          | 0VHWTR A02                  | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| ASRock        | X299 Taichi CLX             | [ee5ad45d8b](https://linux-hardware.org/?probe=ee5ad45d8b) | Jun 21, 2022 |
| Dell          | 0F896N A02                  | [223cbe95f4](https://linux-hardware.org/?probe=223cbe95f4) | Jun 20, 2022 |
| ASRock        | Z370 Extreme4               | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| MSI           | A320M PRO-M2                | [8ffdebb12e](https://linux-hardware.org/?probe=8ffdebb12e) | Jun 20, 2022 |
| MSI           | X570-A PRO                  | [3ac49a6b54](https://linux-hardware.org/?probe=3ac49a6b54) | Jun 19, 2022 |
| PLEXHD        | X79 Turbo                   | [b93749f5e0](https://linux-hardware.org/?probe=b93749f5e0) | Jun 19, 2022 |
| ASUSTek       | PRIME Z490-A                | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| Dell          | 0VHWTR A02                  | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| Gigabyte      | H87-HD3                     | [b018aaf572](https://linux-hardware.org/?probe=b018aaf572) | Jun 15, 2022 |
| MSI           | Z390-A PRO                  | [3074e50dff](https://linux-hardware.org/?probe=3074e50dff) | Jun 15, 2022 |
| ASRock        | X299 Taichi CLX             | [d349f8b0f5](https://linux-hardware.org/?probe=d349f8b0f5) | Jun 15, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [ee0fb46764](https://linux-hardware.org/?probe=ee0fb46764) | Jun 08, 2022 |
| Gigabyte      | Z370XP SLI-CF               | [23191e0c1d](https://linux-hardware.org/?probe=23191e0c1d) | Jun 07, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [8f5dae3cd7](https://linux-hardware.org/?probe=8f5dae3cd7) | Jun 06, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| MSI           | H81M-P33                    | [b48f5d554f](https://linux-hardware.org/?probe=b48f5d554f) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| Dell          | 0WR7PY A01                  | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| Biostar       | J3060NH                     | [e2d33f6c66](https://linux-hardware.org/?probe=e2d33f6c66) | May 31, 2022 |
| Gigabyte      | H110N-CF                    | [3a0b00c45d](https://linux-hardware.org/?probe=3a0b00c45d) | May 30, 2022 |
| Biostar       | J3060NH                     | [2c67e6fc81](https://linux-hardware.org/?probe=2c67e6fc81) | May 28, 2022 |
| HP            | 2B36                        | [7a6bff3398](https://linux-hardware.org/?probe=7a6bff3398) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| Dell          | 0RY007                      | [2d0a227175](https://linux-hardware.org/?probe=2d0a227175) | May 26, 2022 |
| Dell          | 0YJPT1 A00                  | [f4afc8ed1d](https://linux-hardware.org/?probe=f4afc8ed1d) | May 25, 2022 |
| ASUSTek       | PRIME Z490-A                | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c9c033d2f](https://linux-hardware.org/?probe=5c9c033d2f) | May 24, 2022 |
| ASUSTek       | PRIME Z490-A                | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| Gigabyte      | A520 AORUS ELITE            | [2fdd079ebc](https://linux-hardware.org/?probe=2fdd079ebc) | May 21, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [1609781085](https://linux-hardware.org/?probe=1609781085) | May 20, 2022 |
| MSI           | B460M-A PRO                 | [2f1ec161d1](https://linux-hardware.org/?probe=2f1ec161d1) | May 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| ASUSTek       | P8Z68-V                     | [c3438d922b](https://linux-hardware.org/?probe=c3438d922b) | May 19, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | [d29a88fa1f](https://linux-hardware.org/?probe=d29a88fa1f) | May 18, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | [d87dcc4dff](https://linux-hardware.org/?probe=d87dcc4dff) | May 18, 2022 |
| HP            | 2B36                        | [390784f8e5](https://linux-hardware.org/?probe=390784f8e5) | May 15, 2022 |
| MSI           | B350M MORTAR                | [459e7e3586](https://linux-hardware.org/?probe=459e7e3586) | May 15, 2022 |
| Biostar       | J3060NH                     | [09900d1cf6](https://linux-hardware.org/?probe=09900d1cf6) | May 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [2484d9989f](https://linux-hardware.org/?probe=2484d9989f) | May 12, 2022 |
| Gigabyte      | A520M H                     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Acer          | Predator G3-605             | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [08deba5f5f](https://linux-hardware.org/?probe=08deba5f5f) | May 11, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| MSI           | X570-A PRO                  | [34a59f46c4](https://linux-hardware.org/?probe=34a59f46c4) | May 10, 2022 |
| MSI           | B460M-A PRO                 | [29c0818bcd](https://linux-hardware.org/?probe=29c0818bcd) | May 08, 2022 |
| Acer          | WMCP78M                     | [bb0d37a6b8](https://linux-hardware.org/?probe=bb0d37a6b8) | May 08, 2022 |
| MSI           | A320M-HDV R4.0              | [837a74d32f](https://linux-hardware.org/?probe=837a74d32f) | May 08, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| MSI           | A320M-HDV R4.0              | [43b827546c](https://linux-hardware.org/?probe=43b827546c) | May 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| Gigabyte      | GA-M55PLUS-S3G              | [ff948aad6c](https://linux-hardware.org/?probe=ff948aad6c) | May 05, 2022 |
| ASRock        | FM2A78M Pro4+               | [7a00557ba5](https://linux-hardware.org/?probe=7a00557ba5) | May 05, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [297dca51b9](https://linux-hardware.org/?probe=297dca51b9) | Apr 30, 2022 |
| Gigabyte      | B365M H                     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2514409f18](https://linux-hardware.org/?probe=2514409f18) | Apr 28, 2022 |
| ASUSTek       | Z87-PLUS                    | [3b25bc9d0d](https://linux-hardware.org/?probe=3b25bc9d0d) | Apr 27, 2022 |
| Dell          | 0J3C2F A02                  | [833d1610d5](https://linux-hardware.org/?probe=833d1610d5) | Apr 25, 2022 |
| HP            | 2B47                        | [3805de3dc4](https://linux-hardware.org/?probe=3805de3dc4) | Apr 25, 2022 |
| ASUSTek       | Z87-PLUS                    | [cdc3ddaa2d](https://linux-hardware.org/?probe=cdc3ddaa2d) | Apr 22, 2022 |
| ASUSTek       | H87-PRO                     | [aa1df63f27](https://linux-hardware.org/?probe=aa1df63f27) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | 2B2C                        | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4a4df2dc70](https://linux-hardware.org/?probe=4a4df2dc70) | Apr 20, 2022 |
| Pegatron      | 2AC3                        | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Dell          | 0N4YC8 A00                  | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [9ba73648b1](https://linux-hardware.org/?probe=9ba73648b1) | Apr 16, 2022 |
| HP            | 2B2C                        | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| Dell          | 00V62H A00                  | [499a00bcf8](https://linux-hardware.org/?probe=499a00bcf8) | Apr 15, 2022 |
| ASRock        | TRX40 Taichi                | [7ce5e071a2](https://linux-hardware.org/?probe=7ce5e071a2) | Apr 13, 2022 |
| ASUSTek       | M51BC                       | [4c52c99ee9](https://linux-hardware.org/?probe=4c52c99ee9) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | [162850d6b3](https://linux-hardware.org/?probe=162850d6b3) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Unknown       | Unknown                     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| Dell          | 0N4YC8 A00                  | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [36b98241e2](https://linux-hardware.org/?probe=36b98241e2) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d03632cea9](https://linux-hardware.org/?probe=d03632cea9) | Apr 10, 2022 |
| Unknown       | Unknown                     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [7d87907153](https://linux-hardware.org/?probe=7d87907153) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [41fc926d28](https://linux-hardware.org/?probe=41fc926d28) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [586edef1b9](https://linux-hardware.org/?probe=586edef1b9) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [bb881ed0ee](https://linux-hardware.org/?probe=bb881ed0ee) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5370b9e906](https://linux-hardware.org/?probe=5370b9e906) | Apr 07, 2022 |
| MSI           | Z390-A PRO                  | [4e232c446f](https://linux-hardware.org/?probe=4e232c446f) | Apr 06, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [30591629c3](https://linux-hardware.org/?probe=30591629c3) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [8181b0cd19](https://linux-hardware.org/?probe=8181b0cd19) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [dd1fef9175](https://linux-hardware.org/?probe=dd1fef9175) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [fe7fdad91b](https://linux-hardware.org/?probe=fe7fdad91b) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [a26b03795a](https://linux-hardware.org/?probe=a26b03795a) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [d467a8e89f](https://linux-hardware.org/?probe=d467a8e89f) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [5cfb35fb9e](https://linux-hardware.org/?probe=5cfb35fb9e) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [2c39a577ac](https://linux-hardware.org/?probe=2c39a577ac) | Apr 04, 2022 |
| Gigabyte      | Z270-Gaming K3              | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | WMCP78M                     | [7c9d2a802f](https://linux-hardware.org/?probe=7c9d2a802f) | Apr 03, 2022 |
| Unknown       | Unknown                     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a4228141cb](https://linux-hardware.org/?probe=a4228141cb) | Apr 02, 2022 |
| Unknown       | Unknown                     | [9ea14bf201](https://linux-hardware.org/?probe=9ea14bf201) | Apr 02, 2022 |
| ASRock        | B450M Steel Legend          | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | [f74de3797f](https://linux-hardware.org/?probe=f74de3797f) | Mar 31, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | [44eafd5b02](https://linux-hardware.org/?probe=44eafd5b02) | Mar 31, 2022 |
| Intel         | Unknown                     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| Acer          | Predator G3-710             | [d8d0331e9e](https://linux-hardware.org/?probe=d8d0331e9e) | Mar 30, 2022 |
| MSI           | B450-A PRO                  | [e33537863b](https://linux-hardware.org/?probe=e33537863b) | Mar 28, 2022 |
| ASUSTek       | PRIME X570-P                | [d72468b304](https://linux-hardware.org/?probe=d72468b304) | Mar 27, 2022 |
| MSI           | Z390-A PRO                  | [1f36f7eada](https://linux-hardware.org/?probe=1f36f7eada) | Mar 27, 2022 |
| MSI           | H170 GAMING M3              | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| HP            | 8643 SMVB                   | [170657280c](https://linux-hardware.org/?probe=170657280c) | Mar 25, 2022 |
| ASUSTek       | PRIME B450M-A II            | [672496577e](https://linux-hardware.org/?probe=672496577e) | Mar 21, 2022 |
| Gigabyte      | X570 GAMING X               | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| ASUSTek       | PRIME Z490-A                | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Unknown       | Intel X79                   | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| ASUSTek       | P8Z77-V LE                  | [908e3fe366](https://linux-hardware.org/?probe=908e3fe366) | Mar 16, 2022 |
| ASRock        | Z87 Professional            | [e75eb7a802](https://linux-hardware.org/?probe=e75eb7a802) | Mar 15, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| Dell          | 02YYK5 A01                  | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| ASRock        | B450M Steel Legend          | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Dell          | 055H3G A01                  | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [531e740b37](https://linux-hardware.org/?probe=531e740b37) | Mar 05, 2022 |
| MSI           | Z390-A PRO                  | [d5ab693301](https://linux-hardware.org/?probe=d5ab693301) | Mar 05, 2022 |
| MSI           | B350 GAMING PLUS            | [2383184762](https://linux-hardware.org/?probe=2383184762) | Mar 05, 2022 |
| ASRock        | X399 Taichi                 | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| Gigabyte      | A520M H                     | [1b45a09429](https://linux-hardware.org/?probe=1b45a09429) | Mar 03, 2022 |
| ASUSTek       | CM6870                      | [45c8e5fea2](https://linux-hardware.org/?probe=45c8e5fea2) | Mar 01, 2022 |
| Unknown       | Intel X79                   | [6a9245acd2](https://linux-hardware.org/?probe=6a9245acd2) | Feb 27, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [759958a4b0](https://linux-hardware.org/?probe=759958a4b0) | Feb 26, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [52bbb8515e](https://linux-hardware.org/?probe=52bbb8515e) | Feb 23, 2022 |
| ASUSTek       | PRIME X570-P                | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| Medion        | MS-7707                     | [2e4723aea4](https://linux-hardware.org/?probe=2e4723aea4) | Feb 22, 2022 |
| ASUSTek       | PRIME X570-P                | [732c7ad77e](https://linux-hardware.org/?probe=732c7ad77e) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1982ff9621](https://linux-hardware.org/?probe=1982ff9621) | Feb 18, 2022 |
| Gigabyte      | B365M H                     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [1e8c363a67](https://linux-hardware.org/?probe=1e8c363a67) | Feb 16, 2022 |
| ASUSTek       | Z170-A                      | [046f5cdbd7](https://linux-hardware.org/?probe=046f5cdbd7) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [0ee015dd8e](https://linux-hardware.org/?probe=0ee015dd8e) | Feb 14, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| Gigabyte      | F2A78M-D3H                  | [ca5c3f80ae](https://linux-hardware.org/?probe=ca5c3f80ae) | Feb 11, 2022 |
| ASUSTek       | Z170-A                      | [aa66dba98f](https://linux-hardware.org/?probe=aa66dba98f) | Feb 09, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de476d2b5a](https://linux-hardware.org/?probe=de476d2b5a) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [8a7cf7aca4](https://linux-hardware.org/?probe=8a7cf7aca4) | Feb 07, 2022 |
| Biostar       | J3060NH                     | [b34126597c](https://linux-hardware.org/?probe=b34126597c) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6c3ac00f6a](https://linux-hardware.org/?probe=6c3ac00f6a) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [f4a6341837](https://linux-hardware.org/?probe=f4a6341837) | Feb 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | [655eea9ee5](https://linux-hardware.org/?probe=655eea9ee5) | Feb 02, 2022 |
| Gigabyte      | A520M S2H                   | [ccbf2ec4f5](https://linux-hardware.org/?probe=ccbf2ec4f5) | Jan 29, 2022 |
| Gigabyte      | H110M-A-CF                  | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| HP            | 1998                        | [4ee1e4fcee](https://linux-hardware.org/?probe=4ee1e4fcee) | Jan 28, 2022 |
| Gigabyte      | B450M DS3H V2               | [efe16c5921](https://linux-hardware.org/?probe=efe16c5921) | Jan 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [0b57afd8bf](https://linux-hardware.org/?probe=0b57afd8bf) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| ASRock        | P75 Pro3                    | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [269d1509c2](https://linux-hardware.org/?probe=269d1509c2) | Jan 24, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [2dbb65e1bc](https://linux-hardware.org/?probe=2dbb65e1bc) | Jan 24, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a2ed61ffcd](https://linux-hardware.org/?probe=a2ed61ffcd) | Jan 24, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [0d9f79bb17](https://linux-hardware.org/?probe=0d9f79bb17) | Jan 23, 2022 |
| Unknown       | Intel X79                   | [7d1ab99839](https://linux-hardware.org/?probe=7d1ab99839) | Jan 23, 2022 |
| ASRock        | A300M-STX                   | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| MSI           | A320M-HDV R4.0              | [09347426df](https://linux-hardware.org/?probe=09347426df) | Jan 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [03aa6d19c1](https://linux-hardware.org/?probe=03aa6d19c1) | Jan 18, 2022 |
| ASUSTek       | PRIME B550M-A               | [30edae47a1](https://linux-hardware.org/?probe=30edae47a1) | Jan 17, 2022 |
| Gigabyte      | GA-970A-UD3                 | [b123404920](https://linux-hardware.org/?probe=b123404920) | Jan 17, 2022 |
| MSI           | B450 TOMAHAWK               | [9324cf10f9](https://linux-hardware.org/?probe=9324cf10f9) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [f87a30cc1b](https://linux-hardware.org/?probe=f87a30cc1b) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [a7e3aee849](https://linux-hardware.org/?probe=a7e3aee849) | Jan 15, 2022 |
| ASUSTek       | P5L8L-SE                    | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | 83E0                        | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| Dell          | 05CNYF A01                  | [c197ba435d](https://linux-hardware.org/?probe=c197ba435d) | Jan 09, 2022 |
| MSI           | MEG X570 GODLIKE            | [2e21ca6670](https://linux-hardware.org/?probe=2e21ca6670) | Jan 08, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [c56817a778](https://linux-hardware.org/?probe=c56817a778) | Jan 08, 2022 |
| HP            | 843B                        | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5cec5778a0](https://linux-hardware.org/?probe=5cec5778a0) | Jan 06, 2022 |
| HP            | 82F2 A01                    | [416ee28a87](https://linux-hardware.org/?probe=416ee28a87) | Jan 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e2753ebd08](https://linux-hardware.org/?probe=e2753ebd08) | Jan 04, 2022 |
| Dell          | 0KWVT8 A02                  | [fe5ca696c8](https://linux-hardware.org/?probe=fe5ca696c8) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3383929020](https://linux-hardware.org/?probe=3383929020) | Jan 03, 2022 |
| VS Company    | MCP61M                      | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [98ed791fc8](https://linux-hardware.org/?probe=98ed791fc8) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3e3a3df7ce](https://linux-hardware.org/?probe=3e3a3df7ce) | Dec 31, 2021 |
| Gigabyte      | B150-HD3P-CF                | [46c8424272](https://linux-hardware.org/?probe=46c8424272) | Dec 31, 2021 |
| Gigabyte      | Z77X-D3H                    | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| Dell          | 0YXT71 A01                  | [1bd919981a](https://linux-hardware.org/?probe=1bd919981a) | Dec 30, 2021 |
| Lenovo        | SHARKBAY NOK                | [7376dd6793](https://linux-hardware.org/?probe=7376dd6793) | Dec 29, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [34c9874e50](https://linux-hardware.org/?probe=34c9874e50) | Dec 27, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [54774d551c](https://linux-hardware.org/?probe=54774d551c) | Dec 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| MSI           | B450I GAMING PLUS MAX WI... | [9cb5033472](https://linux-hardware.org/?probe=9cb5033472) | Dec 26, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d971e22ea1](https://linux-hardware.org/?probe=d971e22ea1) | Dec 24, 2021 |
| ASRock        | 880GM-LE FX                 | [ed79d730cd](https://linux-hardware.org/?probe=ed79d730cd) | Dec 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [82a81d9287](https://linux-hardware.org/?probe=82a81d9287) | Dec 24, 2021 |
| ASRock        | H310CM-HDV                  | [3b01d877ce](https://linux-hardware.org/?probe=3b01d877ce) | Dec 24, 2021 |
| MSI           | B250M BAZOOKA               | [af10afb79b](https://linux-hardware.org/?probe=af10afb79b) | Dec 23, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [a54f9967ef](https://linux-hardware.org/?probe=a54f9967ef) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [2ca39a2067](https://linux-hardware.org/?probe=2ca39a2067) | Dec 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [b73f1f9cb1](https://linux-hardware.org/?probe=b73f1f9cb1) | Dec 23, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [870a0913ee](https://linux-hardware.org/?probe=870a0913ee) | Dec 23, 2021 |
| HP            | 1998                        | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d00c0b2ded](https://linux-hardware.org/?probe=d00c0b2ded) | Dec 23, 2021 |
| SYWZ          | S210H Series                | [df3edf9f7b](https://linux-hardware.org/?probe=df3edf9f7b) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [8b33da2ce4](https://linux-hardware.org/?probe=8b33da2ce4) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| Unknown       | Unknown                     | [de9ccde374](https://linux-hardware.org/?probe=de9ccde374) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [bee0b80356](https://linux-hardware.org/?probe=bee0b80356) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [bc4e465833](https://linux-hardware.org/?probe=bc4e465833) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [082bd4283a](https://linux-hardware.org/?probe=082bd4283a) | Dec 16, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [8b9e71b388](https://linux-hardware.org/?probe=8b9e71b388) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | [f9f891f9b2](https://linux-hardware.org/?probe=f9f891f9b2) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e2633be8cd](https://linux-hardware.org/?probe=e2633be8cd) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| ASUSTek       | CM6870                      | [05624c26d2](https://linux-hardware.org/?probe=05624c26d2) | Dec 14, 2021 |
| Foxconn       | 2AB1                        | [d5328cbc95](https://linux-hardware.org/?probe=d5328cbc95) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [05db94d8a5](https://linux-hardware.org/?probe=05db94d8a5) | Dec 14, 2021 |
| EVGA          | 141-HW-E877                 | [a9d6f7c590](https://linux-hardware.org/?probe=a9d6f7c590) | Dec 14, 2021 |
| ASUSTek       | P8P67 LE                    | [36ce439bef](https://linux-hardware.org/?probe=36ce439bef) | Dec 14, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [dc12c3cae7](https://linux-hardware.org/?probe=dc12c3cae7) | Dec 14, 2021 |
| HP            | 1587h                       | [b9f599ed03](https://linux-hardware.org/?probe=b9f599ed03) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [afbed7279a](https://linux-hardware.org/?probe=afbed7279a) | Dec 13, 2021 |
| ECS           | H61H2-MV                    | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| ASRock        | AB350 Pro4                  | [ebf80cd948](https://linux-hardware.org/?probe=ebf80cd948) | Dec 13, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [fd1da12c59](https://linux-hardware.org/?probe=fd1da12c59) | Dec 13, 2021 |
| Acer          | EM61SM/EM61PM               | [2e90062d9a](https://linux-hardware.org/?probe=2e90062d9a) | Dec 12, 2021 |
| Packard Be... | IMEDIA S2185                | [26f91db3d6](https://linux-hardware.org/?probe=26f91db3d6) | Dec 12, 2021 |
| ASUSTek       | PRIME X470-PRO              | [b14b8a40ec](https://linux-hardware.org/?probe=b14b8a40ec) | Dec 12, 2021 |
| Gigabyte      | G41M-Combo                  | [666796bd7e](https://linux-hardware.org/?probe=666796bd7e) | Dec 12, 2021 |
| HP            | 1495                        | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [981dc4e673](https://linux-hardware.org/?probe=981dc4e673) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-P                | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | H81M-S                      | [c11f61f55f](https://linux-hardware.org/?probe=c11f61f55f) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX                  | [48325242e3](https://linux-hardware.org/?probe=48325242e3) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Gigabyte      | Z77-D3H                     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a2bfa3a5d3](https://linux-hardware.org/?probe=a2bfa3a5d3) | Dec 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [00b5d9eba5](https://linux-hardware.org/?probe=00b5d9eba5) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | [b9eda20029](https://linux-hardware.org/?probe=b9eda20029) | Dec 12, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ed5c21cccd](https://linux-hardware.org/?probe=ed5c21cccd) | Dec 11, 2021 |
| ASUSTek       | X99-S                       | [df25f864d4](https://linux-hardware.org/?probe=df25f864d4) | Dec 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [330425b3b7](https://linux-hardware.org/?probe=330425b3b7) | Dec 11, 2021 |
| Lenovo        | SHARKBAY NOK                | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| Dell          | 084J0R A00                  | [dff25b4704](https://linux-hardware.org/?probe=dff25b4704) | Dec 11, 2021 |
| HP            | 8768 A                      | [dddb82f6a8](https://linux-hardware.org/?probe=dddb82f6a8) | Dec 11, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [34dacc4911](https://linux-hardware.org/?probe=34dacc4911) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | [96a7160cee](https://linux-hardware.org/?probe=96a7160cee) | Dec 11, 2021 |
| ASUSTek       | PRIME B450M-A II            | [1b3b98bfd7](https://linux-hardware.org/?probe=1b3b98bfd7) | Dec 11, 2021 |
| Gigabyte      | Z97X-Gaming GT              | [efb6380716](https://linux-hardware.org/?probe=efb6380716) | Dec 11, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [684572bd8a](https://linux-hardware.org/?probe=684572bd8a) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | [f40860a3ed](https://linux-hardware.org/?probe=f40860a3ed) | Dec 11, 2021 |
| Dell          | 0WR7PY A03                  | [1676bf41af](https://linux-hardware.org/?probe=1676bf41af) | Dec 11, 2021 |
| Dell          | 00F82W A01                  | [ecdd032df4](https://linux-hardware.org/?probe=ecdd032df4) | Dec 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e7b92397a3](https://linux-hardware.org/?probe=e7b92397a3) | Dec 09, 2021 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [1a64f6d9ca](https://linux-hardware.org/?probe=1a64f6d9ca) | Dec 09, 2021 |
| ASUSTek       | PRIME Z370-P                | [a9cb8442ac](https://linux-hardware.org/?probe=a9cb8442ac) | Dec 08, 2021 |
| ASRock        | B450M Steel Legend          | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| Gigabyte      | B550 AORUS MASTER           | [b25e4ae64c](https://linux-hardware.org/?probe=b25e4ae64c) | Dec 05, 2021 |
| Medion        | B360H4-EM V1.0              | [5f5964c9a4](https://linux-hardware.org/?probe=5f5964c9a4) | Dec 05, 2021 |
| Intel         | DH67BL AAG10189-208         | [8647345ee8](https://linux-hardware.org/?probe=8647345ee8) | Dec 05, 2021 |
| Dell          | 07C0H8 A00                  | [8b0b4e0427](https://linux-hardware.org/?probe=8b0b4e0427) | Dec 04, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | [5efc3e5fc4](https://linux-hardware.org/?probe=5efc3e5fc4) | Dec 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [df01b853dd](https://linux-hardware.org/?probe=df01b853dd) | Dec 03, 2021 |
| ASUSTek       | TUF Z370-PRO GAMING         | [f35a1d4b6f](https://linux-hardware.org/?probe=f35a1d4b6f) | Dec 02, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| MSI           | B460M-A PRO                 | [53de3c938f](https://linux-hardware.org/?probe=53de3c938f) | Nov 30, 2021 |
| ASUSTek       | Rampage III GENE            | [8967a333fa](https://linux-hardware.org/?probe=8967a333fa) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5e6aa10813](https://linux-hardware.org/?probe=5e6aa10813) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f5a807ee34](https://linux-hardware.org/?probe=f5a807ee34) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [43ec4aeaa5](https://linux-hardware.org/?probe=43ec4aeaa5) | Nov 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [73dbadb8f1](https://linux-hardware.org/?probe=73dbadb8f1) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| MSI           | H110M PRO-VD PLUS           | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [be44e9c10b](https://linux-hardware.org/?probe=be44e9c10b) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [2f2ac97b5b](https://linux-hardware.org/?probe=2f2ac97b5b) | Nov 26, 2021 |
| Gigabyte      | H81M-S                      | [3df1e42b0e](https://linux-hardware.org/?probe=3df1e42b0e) | Nov 26, 2021 |
| Dell          | 0H4VK7 A01                  | [83171d6677](https://linux-hardware.org/?probe=83171d6677) | Nov 26, 2021 |
| ASRock        | B450 Gaming K4              | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [5cdb53e7ae](https://linux-hardware.org/?probe=5cdb53e7ae) | Nov 25, 2021 |
| Gigabyte      | 970A-DS3P                   | [9bc92b5ef9](https://linux-hardware.org/?probe=9bc92b5ef9) | Nov 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [5575758e0a](https://linux-hardware.org/?probe=5575758e0a) | Nov 25, 2021 |
| ASRock        | B450M Pro4                  | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [7d4b6453e9](https://linux-hardware.org/?probe=7d4b6453e9) | Nov 24, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [ce783dccca](https://linux-hardware.org/?probe=ce783dccca) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [e9b4b7ecba](https://linux-hardware.org/?probe=e9b4b7ecba) | Nov 24, 2021 |
| ASRock        | FM2A78M Pro4+               | [1670e83f4d](https://linux-hardware.org/?probe=1670e83f4d) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1d82d0b32b](https://linux-hardware.org/?probe=1d82d0b32b) | Nov 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [35063b25d7](https://linux-hardware.org/?probe=35063b25d7) | Nov 23, 2021 |
| ASUSTek       | P8Z77-V LE                  | [6994e8dbb3](https://linux-hardware.org/?probe=6994e8dbb3) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| ASUSTek       | PRIME Z490-A                | [fbc257563e](https://linux-hardware.org/?probe=fbc257563e) | Nov 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [47fe68608a](https://linux-hardware.org/?probe=47fe68608a) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [a95e047ec3](https://linux-hardware.org/?probe=a95e047ec3) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| HP            | 158B                        | [28d106042e](https://linux-hardware.org/?probe=28d106042e) | Nov 20, 2021 |
| ASUSTek       | Z87-A                       | [906510b2cd](https://linux-hardware.org/?probe=906510b2cd) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c5c112ae1d](https://linux-hardware.org/?probe=c5c112ae1d) | Nov 18, 2021 |
| ASUSTek       | P8Z68-V PRO                 | [223642cd17](https://linux-hardware.org/?probe=223642cd17) | Nov 16, 2021 |
| ASUSTek       | P8Z77-V                     | [5fc521fe4b](https://linux-hardware.org/?probe=5fc521fe4b) | Nov 15, 2021 |
| Acer          | Predator G3-605             | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| Gigabyte      | B365M GAMING HD             | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| ASRock        | A55M-VS                     | [3e40db1efb](https://linux-hardware.org/?probe=3e40db1efb) | Nov 09, 2021 |
| HP            | 8055                        | [5d16a78abe](https://linux-hardware.org/?probe=5d16a78abe) | Nov 09, 2021 |
| ASRock        | B450M Pro4                  | [b64db5197a](https://linux-hardware.org/?probe=b64db5197a) | Nov 09, 2021 |
| Gigabyte      | F2A68HM-H                   | [77b62d6178](https://linux-hardware.org/?probe=77b62d6178) | Nov 09, 2021 |
| Gigabyte      | B560M DS3H                  | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| ASRock        | B450M Steel Legend          | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [88d5f57ea9](https://linux-hardware.org/?probe=88d5f57ea9) | Nov 06, 2021 |
| ASRock        | H81M-DG4                    | [33d4154b93](https://linux-hardware.org/?probe=33d4154b93) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK               | [7e09d7d036](https://linux-hardware.org/?probe=7e09d7d036) | Nov 04, 2021 |
| MSI           | H510M-A PRO                 | [745d661721](https://linux-hardware.org/?probe=745d661721) | Nov 03, 2021 |
| MSI           | Z170-A PRO                  | [77006702f8](https://linux-hardware.org/?probe=77006702f8) | Oct 31, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [381023907e](https://linux-hardware.org/?probe=381023907e) | Oct 31, 2021 |
| Gigabyte      | 945GCM-S2L                  | [35d876d2dc](https://linux-hardware.org/?probe=35d876d2dc) | Oct 30, 2021 |
| ASUSTek       | X99-DELUXE                  | [d3a4772e4e](https://linux-hardware.org/?probe=d3a4772e4e) | Oct 29, 2021 |
| ASRock        | B450M Steel Legend          | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| ASRock        | B360M Performance           | [2ff008a28d](https://linux-hardware.org/?probe=2ff008a28d) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d0cb96f5b2](https://linux-hardware.org/?probe=d0cb96f5b2) | Oct 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [eaf56ad62b](https://linux-hardware.org/?probe=eaf56ad62b) | Oct 25, 2021 |
| MSI           | B450M MORTAR                | [46651b942b](https://linux-hardware.org/?probe=46651b942b) | Oct 23, 2021 |
| MSI           | Z77A-GD65                   | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [94848f2347](https://linux-hardware.org/?probe=94848f2347) | Oct 19, 2021 |
| Gigabyte      | F2A88XM-D3HP                | [08715cfcc4](https://linux-hardware.org/?probe=08715cfcc4) | Oct 18, 2021 |
| MSI           | B150 PC MATE                | [f2e71b602e](https://linux-hardware.org/?probe=f2e71b602e) | Oct 18, 2021 |
| Pegatron      | 2AD4                        | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3061eaa067](https://linux-hardware.org/?probe=3061eaa067) | Oct 17, 2021 |
| ASUSTek       | PRIME Z490-A                | [274cba3955](https://linux-hardware.org/?probe=274cba3955) | Oct 17, 2021 |
| ASUSTek       | PRIME Z590-A                | [2a03ec745f](https://linux-hardware.org/?probe=2a03ec745f) | Oct 16, 2021 |
| HP            | 8768 A                      | [bd722ad5d5](https://linux-hardware.org/?probe=bd722ad5d5) | Oct 15, 2021 |
| Gigabyte      | B450 AORUS M                | [e025ccbf40](https://linux-hardware.org/?probe=e025ccbf40) | Oct 15, 2021 |
| Dell          | 0RM5DR A00                  | [c35c2fd772](https://linux-hardware.org/?probe=c35c2fd772) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [eb4a97ceef](https://linux-hardware.org/?probe=eb4a97ceef) | Oct 12, 2021 |
| ASUSTek       | B85M-E                      | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a94b3893c1](https://linux-hardware.org/?probe=a94b3893c1) | Oct 11, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| ASUSTek       | M4A79XTD EVO                | [fea72dd4e7](https://linux-hardware.org/?probe=fea72dd4e7) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [e309ba4276](https://linux-hardware.org/?probe=e309ba4276) | Oct 09, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [e4e8fba89b](https://linux-hardware.org/?probe=e4e8fba89b) | Oct 09, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [d8a64024f9](https://linux-hardware.org/?probe=d8a64024f9) | Oct 07, 2021 |
| MSI           | B450 TOMAHAWK               | [f50b61b450](https://linux-hardware.org/?probe=f50b61b450) | Oct 06, 2021 |
| Gigabyte      | B450M DS3H V2               | [bd9fe373d2](https://linux-hardware.org/?probe=bd9fe373d2) | Oct 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [ceefec9a7f](https://linux-hardware.org/?probe=ceefec9a7f) | Oct 06, 2021 |
| ASRock        | FM2A75M Pro4+               | [d9637236c2](https://linux-hardware.org/?probe=d9637236c2) | Oct 04, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [e5d1cb1742](https://linux-hardware.org/?probe=e5d1cb1742) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | [9bec53673d](https://linux-hardware.org/?probe=9bec53673d) | Oct 03, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [1129266f95](https://linux-hardware.org/?probe=1129266f95) | Oct 03, 2021 |
| ASUSTek       | X99-A                       | [8645db4302](https://linux-hardware.org/?probe=8645db4302) | Oct 02, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [45605570fe](https://linux-hardware.org/?probe=45605570fe) | Sep 29, 2021 |
| ASRock        | FM2A75M Pro4+               | [d0f4eaa9f8](https://linux-hardware.org/?probe=d0f4eaa9f8) | Sep 29, 2021 |
| ASUSTek       | PRIME X370-PRO              | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| ASUSTek       | P8Z77-V LX                  | [e47c168067](https://linux-hardware.org/?probe=e47c168067) | Sep 25, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [434da8cb2d](https://linux-hardware.org/?probe=434da8cb2d) | Sep 24, 2021 |
| ASUSTek       | PRIME X570-P                | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [92e151e105](https://linux-hardware.org/?probe=92e151e105) | Sep 22, 2021 |
| ASRock        | X570 Taichi                 | [72b58edccd](https://linux-hardware.org/?probe=72b58edccd) | Sep 21, 2021 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [855a10f536](https://linux-hardware.org/?probe=855a10f536) | Sep 21, 2021 |
| Lenovo        | 36C5 SDK0J40709 WIN 3259... | [49e564cb99](https://linux-hardware.org/?probe=49e564cb99) | Sep 21, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bd2cfcf1ee](https://linux-hardware.org/?probe=bd2cfcf1ee) | Sep 20, 2021 |
| Maibenben     | PC34 V1.0                   | [10d3e02dfb](https://linux-hardware.org/?probe=10d3e02dfb) | Sep 19, 2021 |
| MSI           | H510M-A PRO                 | [edb11a70a9](https://linux-hardware.org/?probe=edb11a70a9) | Sep 19, 2021 |
| ASUSTek       | PRIME X570-PRO              | [a73053ecf3](https://linux-hardware.org/?probe=a73053ecf3) | Sep 18, 2021 |
| HP            | 2B47                        | [d065e6065e](https://linux-hardware.org/?probe=d065e6065e) | Sep 18, 2021 |
| Gigabyte      | Z97-HD3                     | [de56866167](https://linux-hardware.org/?probe=de56866167) | Sep 17, 2021 |
| ASUSTek       | M4A79XTD EVO                | [babdb2f68a](https://linux-hardware.org/?probe=babdb2f68a) | Sep 17, 2021 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [086b930d7d](https://linux-hardware.org/?probe=086b930d7d) | Sep 16, 2021 |
| Unknown       | HX90                        | [7a2e84e05d](https://linux-hardware.org/?probe=7a2e84e05d) | Sep 15, 2021 |
| Lenovo        | 36EB NOK                    | [f8c3745c72](https://linux-hardware.org/?probe=f8c3745c72) | Sep 13, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [9782c3ebac](https://linux-hardware.org/?probe=9782c3ebac) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [f7f2edee75](https://linux-hardware.org/?probe=f7f2edee75) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| MSI           | A320M-HDV R4.0              | [bedc045e2c](https://linux-hardware.org/?probe=bedc045e2c) | Sep 11, 2021 |
| ASUSTek       | M2N-E SLI                   | [1cb1281742](https://linux-hardware.org/?probe=1cb1281742) | Sep 10, 2021 |
| ASUSTek       | M4A77T                      | [a013c12dff](https://linux-hardware.org/?probe=a013c12dff) | Sep 09, 2021 |
| Maibenben     | PC34 V1.0                   | [dd82d2282e](https://linux-hardware.org/?probe=dd82d2282e) | Sep 08, 2021 |
| Gigabyte      | B450M DS3H V2               | [70c214c3b6](https://linux-hardware.org/?probe=70c214c3b6) | Sep 07, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [866150f656](https://linux-hardware.org/?probe=866150f656) | Sep 07, 2021 |
| MSI           | H510M-A PRO                 | [db625f00d5](https://linux-hardware.org/?probe=db625f00d5) | Sep 07, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [b094346e99](https://linux-hardware.org/?probe=b094346e99) | Sep 07, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [8a53d9eccc](https://linux-hardware.org/?probe=8a53d9eccc) | Sep 05, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [9a1ae9ad8d](https://linux-hardware.org/?probe=9a1ae9ad8d) | Sep 05, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | [f07151c6ac](https://linux-hardware.org/?probe=f07151c6ac) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e92353130f](https://linux-hardware.org/?probe=e92353130f) | Sep 04, 2021 |
| Gigabyte      | X570 GAMING X               | [3f152a9790](https://linux-hardware.org/?probe=3f152a9790) | Sep 02, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [61fdddc7a9](https://linux-hardware.org/?probe=61fdddc7a9) | Sep 01, 2021 |
| ASUSTek       | PRIME X570-P                | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| MSI           | MEG X570 ACE                | [f393dc1e30](https://linux-hardware.org/?probe=f393dc1e30) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [1167357f4a](https://linux-hardware.org/?probe=1167357f4a) | Aug 30, 2021 |
| Apple         | Mac-F221BEC8                | [ba521aca9f](https://linux-hardware.org/?probe=ba521aca9f) | Aug 29, 2021 |
| Apple         | Mac-F221BEC8                | [81a53f9837](https://linux-hardware.org/?probe=81a53f9837) | Aug 29, 2021 |
| ASUSTek       | Z170-A                      | [03c1787182](https://linux-hardware.org/?probe=03c1787182) | Aug 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d438e4ea8c](https://linux-hardware.org/?probe=d438e4ea8c) | Aug 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2263bc71b6](https://linux-hardware.org/?probe=2263bc71b6) | Aug 29, 2021 |
| Gigabyte      | H170-D3HP-CF                | [64087c4ed2](https://linux-hardware.org/?probe=64087c4ed2) | Aug 29, 2021 |
| Gigabyte      | G41M-ES2L                   | [ed21ca940e](https://linux-hardware.org/?probe=ed21ca940e) | Aug 29, 2021 |
| MSI           | H170 GAMING M3              | [7affee0cde](https://linux-hardware.org/?probe=7affee0cde) | Aug 28, 2021 |
| Gigabyte      | H370M D3H-CF                | [4ab2284059](https://linux-hardware.org/?probe=4ab2284059) | Aug 28, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [0dc125b1e6](https://linux-hardware.org/?probe=0dc125b1e6) | Aug 27, 2021 |
| Gigabyte      | A520M H                     | [4b126be26e](https://linux-hardware.org/?probe=4b126be26e) | Aug 26, 2021 |
| Gigabyte      | Z77X-D3H                    | [2509d57e06](https://linux-hardware.org/?probe=2509d57e06) | Aug 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f4f4a32442](https://linux-hardware.org/?probe=f4f4a32442) | Aug 25, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [46e5ae55be](https://linux-hardware.org/?probe=46e5ae55be) | Aug 25, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [6eb4797b58](https://linux-hardware.org/?probe=6eb4797b58) | Aug 23, 2021 |
| ASRock        | X299 Taichi CLX             | [968a7cc18e](https://linux-hardware.org/?probe=968a7cc18e) | Aug 22, 2021 |
| Medion        | B360H4-EM V1.0              | [376acac039](https://linux-hardware.org/?probe=376acac039) | Aug 21, 2021 |
| ASUSTek       | P8P67 LE                    | [a679909847](https://linux-hardware.org/?probe=a679909847) | Aug 20, 2021 |
| MSI           | X470 GAMING M7 AC           | [b2e8193bf3](https://linux-hardware.org/?probe=b2e8193bf3) | Aug 18, 2021 |
| Gigabyte      | GA-870A-USB3                | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| Gigabyte      | B365M GAMING HD             | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1f7bc2a4a6](https://linux-hardware.org/?probe=1f7bc2a4a6) | Aug 13, 2021 |
| Gigabyte      | GA-870A-USB3                | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| ASUSTek       | PRIME Z490-A                | [835e8af58f](https://linux-hardware.org/?probe=835e8af58f) | Aug 12, 2021 |
| Intel         | X99                         | [61e528cf30](https://linux-hardware.org/?probe=61e528cf30) | Aug 09, 2021 |
| MSI           | B150 PC MATE                | [ba7d5b0b10](https://linux-hardware.org/?probe=ba7d5b0b10) | Aug 08, 2021 |
| Intel         | X99                         | [5566d7fc66](https://linux-hardware.org/?probe=5566d7fc66) | Aug 07, 2021 |
| Foxconn       | 2AB1                        | [b726ceaba4](https://linux-hardware.org/?probe=b726ceaba4) | Aug 07, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [64dcd58bc3](https://linux-hardware.org/?probe=64dcd58bc3) | Aug 03, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [1e7666d492](https://linux-hardware.org/?probe=1e7666d492) | Aug 03, 2021 |
| Gigabyte      | G31M-ES2L                   | [0e44549ee5](https://linux-hardware.org/?probe=0e44549ee5) | Aug 01, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING II     | [1219c874c4](https://linux-hardware.org/?probe=1219c874c4) | Jul 30, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [43cbf83241](https://linux-hardware.org/?probe=43cbf83241) | Jul 29, 2021 |
| ASUSTek       | P5Q-E                       | [0904b136a3](https://linux-hardware.org/?probe=0904b136a3) | Jul 29, 2021 |
| ASUSTek       | P5Q-E                       | [35206ac976](https://linux-hardware.org/?probe=35206ac976) | Jul 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3f0188a6fd](https://linux-hardware.org/?probe=3f0188a6fd) | Jul 28, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Gigabyte      | B450 AORUS M                | [41b4ea65d2](https://linux-hardware.org/?probe=41b4ea65d2) | Jul 26, 2021 |
| Gigabyte      | H310M H                     | [c73718bf7a](https://linux-hardware.org/?probe=c73718bf7a) | Jul 23, 2021 |
| Gigabyte      | GA-870A-USB3                | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| Gigabyte      | P85-D3                      | [34c0c89c1e](https://linux-hardware.org/?probe=34c0c89c1e) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K               | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [8b1a8c783b](https://linux-hardware.org/?probe=8b1a8c783b) | Jul 20, 2021 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [eedd331195](https://linux-hardware.org/?probe=eedd331195) | Jul 20, 2021 |
| Dell          | 0HD5W2 A01                  | [ece0155c70](https://linux-hardware.org/?probe=ece0155c70) | Jul 20, 2021 |
| ASUSTek       | PRIME X570-P                | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| ASUSTek       | PRIME B250M-K               | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| ASUSTek       | P8P67 LE                    | [72497bac92](https://linux-hardware.org/?probe=72497bac92) | Jul 12, 2021 |
| Biostar       | TZ68K+                      | [1547ca7da5](https://linux-hardware.org/?probe=1547ca7da5) | Jul 12, 2021 |
| ASUSTek       | PRIME Z490-A                | [7a44c0b8e6](https://linux-hardware.org/?probe=7a44c0b8e6) | Jul 12, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [af549dc0a9](https://linux-hardware.org/?probe=af549dc0a9) | Jul 12, 2021 |
| Gigabyte      | B365M GAMING HD             | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | G41M-ES2L                   | [d3e26d256d](https://linux-hardware.org/?probe=d3e26d256d) | Jul 03, 2021 |
| ASRock        | Z370 Killer SLI/ac          | [ff0be1b59c](https://linux-hardware.org/?probe=ff0be1b59c) | Jul 02, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [8cf6670ab0](https://linux-hardware.org/?probe=8cf6670ab0) | Jul 02, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [c0c53f7ebf](https://linux-hardware.org/?probe=c0c53f7ebf) | Jul 01, 2021 |
| Gigabyte      | B85M-D3H                    | [e79d247254](https://linux-hardware.org/?probe=e79d247254) | Jul 01, 2021 |
| MSI           | B550-A PRO                  | [bbe226bce0](https://linux-hardware.org/?probe=bbe226bce0) | Jun 29, 2021 |
| Gigabyte      | Z97X-Gaming GT              | [ca207b7cd3](https://linux-hardware.org/?probe=ca207b7cd3) | Jun 28, 2021 |
| Gigabyte      | GA-870A-USB3                | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [e6a1412110](https://linux-hardware.org/?probe=e6a1412110) | Jun 28, 2021 |
| ASUSTek       | PRIME Z490-A                | [08c0ec2fb7](https://linux-hardware.org/?probe=08c0ec2fb7) | Jun 27, 2021 |
| MSI           | H110M PRO-VD                | [83b2318c6a](https://linux-hardware.org/?probe=83b2318c6a) | Jun 26, 2021 |
| ASUSTek       | PRIME Z490-A                | [58933ebb06](https://linux-hardware.org/?probe=58933ebb06) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| MSI           | H110M PRO-VD                | [856b9bc825](https://linux-hardware.org/?probe=856b9bc825) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [dbc4494db2](https://linux-hardware.org/?probe=dbc4494db2) | Jun 23, 2021 |
| ASRock        | Z170 Gaming K4              | [9604635e51](https://linux-hardware.org/?probe=9604635e51) | Jun 23, 2021 |
| MSI           | B85M-E45                    | [5508d6a84e](https://linux-hardware.org/?probe=5508d6a84e) | Jun 23, 2021 |
| ASRock        | B450 Pro4                   | [0bd06bbe0b](https://linux-hardware.org/?probe=0bd06bbe0b) | Jun 22, 2021 |
| ASRock        | Z170 Gaming K4              | [58070bd585](https://linux-hardware.org/?probe=58070bd585) | Jun 22, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [a347deb07c](https://linux-hardware.org/?probe=a347deb07c) | Jun 22, 2021 |
| Gigabyte      | B365M GAMING HD             | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [7e2d8c8d09](https://linux-hardware.org/?probe=7e2d8c8d09) | Jun 17, 2021 |
| Intel         | DG31PR AAE58249-306         | [8d9cf5ea94](https://linux-hardware.org/?probe=8d9cf5ea94) | Jun 15, 2021 |
| MSI           | Z97-G45 GAMING              | [2f36a0ce80](https://linux-hardware.org/?probe=2f36a0ce80) | Jun 15, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [42e10b10fd](https://linux-hardware.org/?probe=42e10b10fd) | Jun 15, 2021 |
| MSI           | X570-A PRO                  | [fc9d4907b2](https://linux-hardware.org/?probe=fc9d4907b2) | Jun 13, 2021 |
| ASUSTek       | H81M-K                      | [2aa987fc0d](https://linux-hardware.org/?probe=2aa987fc0d) | Jun 13, 2021 |
| ASUSTek       | D425MC                      | [aa893a2c50](https://linux-hardware.org/?probe=aa893a2c50) | Jun 10, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [172643ea98](https://linux-hardware.org/?probe=172643ea98) | Jun 07, 2021 |
| ASUSTek       | PRIME X570-P                | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [db78e09514](https://linux-hardware.org/?probe=db78e09514) | Jun 03, 2021 |
| Gigabyte      | A520M S2H                   | [f10a48e6cf](https://linux-hardware.org/?probe=f10a48e6cf) | Jun 03, 2021 |
| Gigabyte      | A520M S2H                   | [63be8e2205](https://linux-hardware.org/?probe=63be8e2205) | Jun 03, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [ee0630b07c](https://linux-hardware.org/?probe=ee0630b07c) | Jun 02, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| ASUSTek       | M5A97 R2.0                  | [b7175abf98](https://linux-hardware.org/?probe=b7175abf98) | May 29, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| Intel         | H61                         | [3b35e80002](https://linux-hardware.org/?probe=3b35e80002) | May 26, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [e71b786be5](https://linux-hardware.org/?probe=e71b786be5) | May 25, 2021 |
| Huanan        | X99-F8                      | [40e64a9bd9](https://linux-hardware.org/?probe=40e64a9bd9) | May 24, 2021 |
| Huanan        | X99-F8                      | [0158c76f85](https://linux-hardware.org/?probe=0158c76f85) | May 23, 2021 |
| Dell          | 0D02VH A01                  | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| Gigabyte      | B450M DS3H V2               | [a77184c9c7](https://linux-hardware.org/?probe=a77184c9c7) | May 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [cf1638450e](https://linux-hardware.org/?probe=cf1638450e) | May 14, 2021 |
| Foxconn       | A85GM                       | [f75d2cd0a7](https://linux-hardware.org/?probe=f75d2cd0a7) | May 14, 2021 |
| MSI           | H81M-P33                    | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| ASUSTek       | TUF X299 MARK 1             | [eb55e9a1cd](https://linux-hardware.org/?probe=eb55e9a1cd) | May 12, 2021 |
| ASUSTek       | TUF X299 MARK 1             | [e1ebffb1f6](https://linux-hardware.org/?probe=e1ebffb1f6) | May 12, 2021 |
| ASUSTek       | Z87-K                       | [6d9e2228c3](https://linux-hardware.org/?probe=6d9e2228c3) | May 05, 2021 |
| ASRock        | Z77 Pro4-M                  | [e9fe60f89a](https://linux-hardware.org/?probe=e9fe60f89a) | May 05, 2021 |
| ASUSTek       | M4A79XTD EVO                | [4bf4556f96](https://linux-hardware.org/?probe=4bf4556f96) | May 03, 2021 |
| ASUSTek       | EX-A320M-GAMING             | [dc100ee99f](https://linux-hardware.org/?probe=dc100ee99f) | May 01, 2021 |
| ASRock        | H110M-HDV R3.0              | [7c6c704c51](https://linux-hardware.org/?probe=7c6c704c51) | Apr 30, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [5c21c8e3b5](https://linux-hardware.org/?probe=5c21c8e3b5) | Apr 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [47da354af9](https://linux-hardware.org/?probe=47da354af9) | Apr 27, 2021 |
| ASUSTek       | PRIME A320M-K               | [3be3ad06bb](https://linux-hardware.org/?probe=3be3ad06bb) | Apr 26, 2021 |
| ASUSTek       | P7H55-M                     | [f4a2af7fa8](https://linux-hardware.org/?probe=f4a2af7fa8) | Apr 24, 2021 |
| HP            | 83E9                        | [d9a6f8bf8f](https://linux-hardware.org/?probe=d9a6f8bf8f) | Apr 24, 2021 |
| Gigabyte      | H170-D3HP-CF                | [c970ef4e84](https://linux-hardware.org/?probe=c970ef4e84) | Apr 21, 2021 |
| ASRock        | D1800B-ITX                  | [16a33b32ac](https://linux-hardware.org/?probe=16a33b32ac) | Apr 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [d55735e0db](https://linux-hardware.org/?probe=d55735e0db) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [4601ed2bc4](https://linux-hardware.org/?probe=4601ed2bc4) | Apr 19, 2021 |
| ASRock        | B450 Pro4                   | [c642353f62](https://linux-hardware.org/?probe=c642353f62) | Apr 18, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [a66644d8f9](https://linux-hardware.org/?probe=a66644d8f9) | Apr 18, 2021 |
| ASRock        | X99 Professional Gaming ... | [70928b7215](https://linux-hardware.org/?probe=70928b7215) | Apr 16, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f0a9a9b376](https://linux-hardware.org/?probe=f0a9a9b376) | Apr 15, 2021 |
| Intel         | DN2820FYK H24582-202        | [920e36be7e](https://linux-hardware.org/?probe=920e36be7e) | Apr 14, 2021 |
| HP            | 1850                        | [5129384114](https://linux-hardware.org/?probe=5129384114) | Apr 14, 2021 |
| HP            | 1998                        | [ec0fdacf3a](https://linux-hardware.org/?probe=ec0fdacf3a) | Apr 12, 2021 |
| HP            | 1998                        | [c395021e6a](https://linux-hardware.org/?probe=c395021e6a) | Apr 12, 2021 |
| Gigabyte      | X399 AORUS Gaming 7         | [61f0309c59](https://linux-hardware.org/?probe=61f0309c59) | Apr 11, 2021 |
| ASUSTek       | PRIME X370-PRO              | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| HP            | 1850                        | [9472ac815b](https://linux-hardware.org/?probe=9472ac815b) | Apr 08, 2021 |
| ASRock        | X570 Taichi                 | [59a4c88b2a](https://linux-hardware.org/?probe=59a4c88b2a) | Apr 04, 2021 |
| HP            | 3397                        | [53b1e2e13d](https://linux-hardware.org/?probe=53b1e2e13d) | Apr 03, 2021 |
| ASRock        | Z270M Extreme4              | [11c057ddb1](https://linux-hardware.org/?probe=11c057ddb1) | Apr 03, 2021 |
| BESSTAR Te... | DMAF5 V1.0                  | [e4a8b63e16](https://linux-hardware.org/?probe=e4a8b63e16) | Mar 28, 2021 |
| ASRock        | X570 Extreme4               | [9ecdb36d8e](https://linux-hardware.org/?probe=9ecdb36d8e) | Mar 25, 2021 |
| HP            | 158B                        | [837cecdae8](https://linux-hardware.org/?probe=837cecdae8) | Mar 23, 2021 |
| Dell          | 05XGC8 A01                  | [1f7a0c0323](https://linux-hardware.org/?probe=1f7a0c0323) | Mar 22, 2021 |
| ASRock        | X570 Taichi                 | [9b9018d7c8](https://linux-hardware.org/?probe=9b9018d7c8) | Mar 21, 2021 |
| MSI           | X570-A PRO                  | [be77b62a8a](https://linux-hardware.org/?probe=be77b62a8a) | Mar 21, 2021 |
| ASUSTek       | P8H61-M LE/BR               | [e17cb89c8c](https://linux-hardware.org/?probe=e17cb89c8c) | Mar 20, 2021 |
| Intel         | B75                         | [cf8a32d6bf](https://linux-hardware.org/?probe=cf8a32d6bf) | Mar 19, 2021 |
| Unknown       | VER                         | [2b66d90e15](https://linux-hardware.org/?probe=2b66d90e15) | Mar 18, 2021 |
| Gigabyte      | E3000N                      | [a5c6af7849](https://linux-hardware.org/?probe=a5c6af7849) | Mar 18, 2021 |
| ASUSTek       | P8Z77-V LE                  | [79e3573fed](https://linux-hardware.org/?probe=79e3573fed) | Mar 17, 2021 |
| Dell          | 0Y2YM6 A00                  | [d91551dac1](https://linux-hardware.org/?probe=d91551dac1) | Mar 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1c133a66fe](https://linux-hardware.org/?probe=1c133a66fe) | Mar 16, 2021 |
| MSI           | B450M MORTAR MAX            | [b40d3ff1b0](https://linux-hardware.org/?probe=b40d3ff1b0) | Mar 12, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0ab96b7281](https://linux-hardware.org/?probe=0ab96b7281) | Mar 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [db1f9d815c](https://linux-hardware.org/?probe=db1f9d815c) | Mar 12, 2021 |
| MSI           | X470 GAMING PRO CARBON      | [3133dbf834](https://linux-hardware.org/?probe=3133dbf834) | Mar 11, 2021 |
| Lenovo        | MAHOBAY No DPK              | [08769f0d3a](https://linux-hardware.org/?probe=08769f0d3a) | Mar 08, 2021 |
| ASRock        | A300M-STX                   | [6377ea853f](https://linux-hardware.org/?probe=6377ea853f) | Mar 07, 2021 |
| MSI           | Z170-A PRO                  | [ba76d096ed](https://linux-hardware.org/?probe=ba76d096ed) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [ad390daa6b](https://linux-hardware.org/?probe=ad390daa6b) | Mar 04, 2021 |
| MSI           | B450M MORTAR MAX            | [f9d2730cb4](https://linux-hardware.org/?probe=f9d2730cb4) | Mar 02, 2021 |
| HP            | 18E7                        | [a7389fa350](https://linux-hardware.org/?probe=a7389fa350) | Mar 02, 2021 |
| Gigabyte      | 970A-DS3P                   | [5db3daf51c](https://linux-hardware.org/?probe=5db3daf51c) | Mar 02, 2021 |
| Dell          | 0DF42J A00                  | [0a24bf8dca](https://linux-hardware.org/?probe=0a24bf8dca) | Feb 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | [3defa02f89](https://linux-hardware.org/?probe=3defa02f89) | Feb 24, 2021 |
| Dell          | 0D02VH A01                  | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| ASRock        | Z270 Pro4                   | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| HP            | 1497                        | [08f2159393](https://linux-hardware.org/?probe=08f2159393) | Feb 20, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [d1f52ba806](https://linux-hardware.org/?probe=d1f52ba806) | Feb 19, 2021 |
| HP            | 18E7                        | [8456b19c7e](https://linux-hardware.org/?probe=8456b19c7e) | Feb 19, 2021 |
| MSI           | A320M-HDV R4.0              | [750999a54f](https://linux-hardware.org/?probe=750999a54f) | Feb 18, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [aac7af965f](https://linux-hardware.org/?probe=aac7af965f) | Feb 18, 2021 |
| MSI           | X570-A PRO                  | [a11127fa47](https://linux-hardware.org/?probe=a11127fa47) | Feb 16, 2021 |
| Biostar       | J3060NH                     | [710471e54c](https://linux-hardware.org/?probe=710471e54c) | Feb 16, 2021 |
| MSI           | H61M-P31                    | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| Dell          | 0WR7PY A03                  | [3c15f6f889](https://linux-hardware.org/?probe=3c15f6f889) | Feb 14, 2021 |
| HP            | 82F2 A01                    | [dce89bfc5d](https://linux-hardware.org/?probe=dce89bfc5d) | Feb 13, 2021 |
| Dell          | 0D02VH A01                  | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| HP            | 18E7                        | [ea4850a633](https://linux-hardware.org/?probe=ea4850a633) | Feb 11, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [aa9f19288b](https://linux-hardware.org/?probe=aa9f19288b) | Feb 10, 2021 |
| MSI           | X570-A PRO                  | [710e2aada3](https://linux-hardware.org/?probe=710e2aada3) | Feb 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9534354645](https://linux-hardware.org/?probe=9534354645) | Feb 08, 2021 |
| ASUSTek       | PRIME B450M-A               | [041c5bffa5](https://linux-hardware.org/?probe=041c5bffa5) | Feb 07, 2021 |
| ASRock        | X399 Professional Gaming    | [cf9cd8fbf4](https://linux-hardware.org/?probe=cf9cd8fbf4) | Feb 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4448c7c05d](https://linux-hardware.org/?probe=4448c7c05d) | Feb 06, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | [ca9d4cd0e7](https://linux-hardware.org/?probe=ca9d4cd0e7) | Feb 06, 2021 |
| Dell          | 0M9KCM A02                  | [0c8a1fea22](https://linux-hardware.org/?probe=0c8a1fea22) | Feb 04, 2021 |
| Biostar       | J3060NH                     | [4e74b60668](https://linux-hardware.org/?probe=4e74b60668) | Feb 04, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [f0a2cff7fc](https://linux-hardware.org/?probe=f0a2cff7fc) | Feb 02, 2021 |
| MSI           | B450-A PRO MAX              | [0521e66a3f](https://linux-hardware.org/?probe=0521e66a3f) | Feb 01, 2021 |
| MSI           | B450-A PRO MAX              | [1e3b19bb06](https://linux-hardware.org/?probe=1e3b19bb06) | Jan 30, 2021 |
| Proline       | ProlinePartner              | [ebe3099bba](https://linux-hardware.org/?probe=ebe3099bba) | Jan 28, 2021 |
| Proline       | ProlinePartner              | [9f76238b74](https://linux-hardware.org/?probe=9f76238b74) | Jan 28, 2021 |
| ASUSTek       | PRIME H310M-E               | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| HP            | 2B47                        | [406d514ed5](https://linux-hardware.org/?probe=406d514ed5) | Jan 24, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e6246a62eb](https://linux-hardware.org/?probe=e6246a62eb) | Jan 20, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [7482661d1c](https://linux-hardware.org/?probe=7482661d1c) | Jan 19, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | [0598377b14](https://linux-hardware.org/?probe=0598377b14) | Jan 19, 2021 |
| ASUSTek       | PRIME Z390-P                | [f25a998d4f](https://linux-hardware.org/?probe=f25a998d4f) | Jan 18, 2021 |
| Unknown       | Unknown                     | [12987dd140](https://linux-hardware.org/?probe=12987dd140) | Jan 18, 2021 |
| Unknown       | Unknown                     | [511d8a9322](https://linux-hardware.org/?probe=511d8a9322) | Jan 18, 2021 |
| Lenovo        | 36EB NOK                    | [9a0f9b96dc](https://linux-hardware.org/?probe=9a0f9b96dc) | Jan 17, 2021 |
| MSI           | X470 GAMING PLUS            | [96664f7b59](https://linux-hardware.org/?probe=96664f7b59) | Jan 16, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [605c9b4d80](https://linux-hardware.org/?probe=605c9b4d80) | Jan 15, 2021 |
| MSI           | X470 GAMING PRO MAX         | [ef19f435be](https://linux-hardware.org/?probe=ef19f435be) | Jan 15, 2021 |
| Gigabyte      | H310N x.x                   | [bce10fe231](https://linux-hardware.org/?probe=bce10fe231) | Jan 12, 2021 |
| Unknown       | Intel X79                   | [8aa4df594f](https://linux-hardware.org/?probe=8aa4df594f) | Jan 12, 2021 |
| ASRock        | J4105-ITX                   | [7917a1f444](https://linux-hardware.org/?probe=7917a1f444) | Jan 11, 2021 |
| MSI           | 2A9C                        | [5da08b027b](https://linux-hardware.org/?probe=5da08b027b) | Jan 11, 2021 |
| ASUSTek       | PRIME Z390-P                | [ae2c1ae2d1](https://linux-hardware.org/?probe=ae2c1ae2d1) | Jan 10, 2021 |
| Unknown       | X79                         | [a895be79c6](https://linux-hardware.org/?probe=a895be79c6) | Jan 10, 2021 |
| Gigabyte      | B365M D3H-CF                | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [42fc68c6da](https://linux-hardware.org/?probe=42fc68c6da) | Jan 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [1796a84503](https://linux-hardware.org/?probe=1796a84503) | Jan 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [08ccb0120e](https://linux-hardware.org/?probe=08ccb0120e) | Jan 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ab63715f96](https://linux-hardware.org/?probe=ab63715f96) | Jan 08, 2021 |
| HP            | 0B4Ch D                     | [1cf9b4e160](https://linux-hardware.org/?probe=1cf9b4e160) | Jan 06, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [860d7e3d8d](https://linux-hardware.org/?probe=860d7e3d8d) | Jan 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7f4357bae8](https://linux-hardware.org/?probe=7f4357bae8) | Jan 05, 2021 |
| Gigabyte      | H310N x.x                   | [c5162a33b1](https://linux-hardware.org/?probe=c5162a33b1) | Jan 05, 2021 |
| MSI           | B450M BAZOOKA V2            | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [c56c2c1b79](https://linux-hardware.org/?probe=c56c2c1b79) | Jan 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [f3aa67a60f](https://linux-hardware.org/?probe=f3aa67a60f) | Jan 02, 2021 |
| MSI           | B450M PRO-VDH               | [29e1d5935f](https://linux-hardware.org/?probe=29e1d5935f) | Jan 02, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [11ab49e949](https://linux-hardware.org/?probe=11ab49e949) | Jan 01, 2021 |
| ASUSTek       | PRIME X470-PRO              | [7774d76390](https://linux-hardware.org/?probe=7774d76390) | Dec 29, 2020 |
| System76      | Thelio thelio-r1            | [aa8f2e17ca](https://linux-hardware.org/?probe=aa8f2e17ca) | Dec 29, 2020 |
| ASUSTek       | H81M-C                      | [02e59017b8](https://linux-hardware.org/?probe=02e59017b8) | Dec 28, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c2b36956c2](https://linux-hardware.org/?probe=c2b36956c2) | Dec 28, 2020 |
| HP            | 8618                        | [a021be4e84](https://linux-hardware.org/?probe=a021be4e84) | Dec 24, 2020 |
| MSI           | A320M PRO-VD PLUS           | [eb1f0354f0](https://linux-hardware.org/?probe=eb1f0354f0) | Dec 23, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [88b5ce4f14](https://linux-hardware.org/?probe=88b5ce4f14) | Dec 22, 2020 |
| Gigabyte      | B250M-DS3H-CF               | [1b147eb313](https://linux-hardware.org/?probe=1b147eb313) | Dec 20, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [c74c628d8a](https://linux-hardware.org/?probe=c74c628d8a) | Dec 19, 2020 |
| MSI           | Z97 GAMING 3                | [6e4b2c6326](https://linux-hardware.org/?probe=6e4b2c6326) | Dec 19, 2020 |
| Gigabyte      | B450 AORUS PRO-CF           | [56d8809172](https://linux-hardware.org/?probe=56d8809172) | Dec 17, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4aaf32a9fc](https://linux-hardware.org/?probe=4aaf32a9fc) | Dec 17, 2020 |
| Gigabyte      | J3455N-D3H                  | [3600589bf6](https://linux-hardware.org/?probe=3600589bf6) | Dec 15, 2020 |
| HP            | 0AECh D                     | [3c29596884](https://linux-hardware.org/?probe=3c29596884) | Dec 15, 2020 |
| ASUSTek       | Z170-DELUXE                 | [354f430cf1](https://linux-hardware.org/?probe=354f430cf1) | Dec 14, 2020 |
| MSI           | Z97 GAMING 7                | [6ce0652b8e](https://linux-hardware.org/?probe=6ce0652b8e) | Dec 13, 2020 |
| ASRock        | B450M Pro4                  | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| Pegatron      | BOWIE                       | [40f3ca1c9b](https://linux-hardware.org/?probe=40f3ca1c9b) | Dec 10, 2020 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [b9e091029f](https://linux-hardware.org/?probe=b9e091029f) | Dec 10, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d11b9d7e47](https://linux-hardware.org/?probe=d11b9d7e47) | Dec 08, 2020 |
| MSI           | H170A PC MATE               | [5cc4fd552a](https://linux-hardware.org/?probe=5cc4fd552a) | Dec 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8dbe0b6c4a](https://linux-hardware.org/?probe=8dbe0b6c4a) | Dec 07, 2020 |
| MSI           | A320M-HDV R4.0              | [99d3945e94](https://linux-hardware.org/?probe=99d3945e94) | Dec 05, 2020 |
| MSI           | A320M-HDV R4.0              | [b6414b072b](https://linux-hardware.org/?probe=b6414b072b) | Dec 05, 2020 |
| Medion        | MS-7785                     | [7db825feae](https://linux-hardware.org/?probe=7db825feae) | Dec 05, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [25333a85bb](https://linux-hardware.org/?probe=25333a85bb) | Dec 02, 2020 |
| MSI           | B150 PC MATE                | [8d4a1b883d](https://linux-hardware.org/?probe=8d4a1b883d) | Dec 02, 2020 |
| Gigabyte      | B250-D3A-CF                 | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| MSI           | H110M ECO                   | [d848b46f0e](https://linux-hardware.org/?probe=d848b46f0e) | Nov 29, 2020 |
| MSI           | X570-A PRO                  | [f126a3d4d1](https://linux-hardware.org/?probe=f126a3d4d1) | Nov 28, 2020 |
| Alienware     | 0J560M A01                  | [ab6a38d6c2](https://linux-hardware.org/?probe=ab6a38d6c2) | Nov 27, 2020 |
| ASUSTek       | PRIME X370-PRO              | [4f2f77fbd0](https://linux-hardware.org/?probe=4f2f77fbd0) | Nov 26, 2020 |
| Dell          | 0WR7PY A02                  | [425d99f3d7](https://linux-hardware.org/?probe=425d99f3d7) | Nov 25, 2020 |
| ASRock        | P67 Extreme4                | [2fb0f5003d](https://linux-hardware.org/?probe=2fb0f5003d) | Nov 24, 2020 |
| MSI           | X470 GAMING PLUS            | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [6bfb7d2b4c](https://linux-hardware.org/?probe=6bfb7d2b4c) | Nov 23, 2020 |
| ASUSTek       | D425MC                      | [a2a7090e43](https://linux-hardware.org/?probe=a2a7090e43) | Nov 23, 2020 |
| Alienware     | 0KM92T A00                  | [9fd3a31b57](https://linux-hardware.org/?probe=9fd3a31b57) | Nov 22, 2020 |
| Gigabyte      | Z97MX-Gaming 5              | [a4caa995dd](https://linux-hardware.org/?probe=a4caa995dd) | Nov 22, 2020 |
| ASRock        | X470 Master SLI             | [e0de72e9a0](https://linux-hardware.org/?probe=e0de72e9a0) | Nov 21, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd25862710](https://linux-hardware.org/?probe=cd25862710) | Nov 20, 2020 |
| ASRock        | B450M Pro4                  | [155ae942ef](https://linux-hardware.org/?probe=155ae942ef) | Nov 17, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [d8a43c445c](https://linux-hardware.org/?probe=d8a43c445c) | Nov 17, 2020 |
| Dell          | 0WWJRX A00                  | [79bddf0f48](https://linux-hardware.org/?probe=79bddf0f48) | Nov 17, 2020 |
| ASRock        | G41C-GS                     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| Pegatron      | 2AC2A                       | [0d8e938368](https://linux-hardware.org/?probe=0d8e938368) | Nov 16, 2020 |
| MSI           | X570-A PRO                  | [b669b71fce](https://linux-hardware.org/?probe=b669b71fce) | Nov 15, 2020 |
| Gigabyte      | B450 AORUS M                | [af8d47e3e4](https://linux-hardware.org/?probe=af8d47e3e4) | Nov 15, 2020 |
| ASUSTek       | PRIME B450M-A               | [fe00092f17](https://linux-hardware.org/?probe=fe00092f17) | Nov 15, 2020 |
| ASUSTek       | PRIME B450M-A               | [f40c1b6361](https://linux-hardware.org/?probe=f40c1b6361) | Nov 13, 2020 |
| ASRock        | B75 Pro3-M                  | [bc564e4cc1](https://linux-hardware.org/?probe=bc564e4cc1) | Nov 10, 2020 |
| Lenovo        | ThinkCentre M91p 4512A47    | [7efad9603e](https://linux-hardware.org/?probe=7efad9603e) | Nov 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [521629e12d](https://linux-hardware.org/?probe=521629e12d) | Nov 10, 2020 |
| MSI           | MAG Z490 TOMAHAWK           | [62b36ce80c](https://linux-hardware.org/?probe=62b36ce80c) | Nov 10, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [636003c419](https://linux-hardware.org/?probe=636003c419) | Nov 09, 2020 |
| ASUSTek       | D425MC                      | [50665babae](https://linux-hardware.org/?probe=50665babae) | Nov 09, 2020 |
| MSI           | A68HM GRENADE               | [f0d0a824e5](https://linux-hardware.org/?probe=f0d0a824e5) | Nov 09, 2020 |
| Gigabyte      | H170-D3HP-CF                | [5b499e2547](https://linux-hardware.org/?probe=5b499e2547) | Nov 09, 2020 |
| ASRock        | 970M Pro3                   | [d34d91c84c](https://linux-hardware.org/?probe=d34d91c84c) | Nov 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [da0dd4eed3](https://linux-hardware.org/?probe=da0dd4eed3) | Nov 07, 2020 |
| Dell          | Dimension 5100              | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| ASUSTek       | PRIME X470-PRO              | [859b87566a](https://linux-hardware.org/?probe=859b87566a) | Nov 01, 2020 |
| ASUSTek       | PRIME X470-PRO              | [655eea2ec8](https://linux-hardware.org/?probe=655eea2ec8) | Oct 28, 2020 |
| Shuttle       | FS110                       | [43b2f8fffb](https://linux-hardware.org/?probe=43b2f8fffb) | Oct 25, 2020 |
| Gigabyte      | Z77-D3H                     | [26f91cadbf](https://linux-hardware.org/?probe=26f91cadbf) | Oct 23, 2020 |
| Unknown       | Intel X79                   | [844bc2247d](https://linux-hardware.org/?probe=844bc2247d) | Oct 21, 2020 |
| ASRock        | X570 Extreme4               | [d28168f646](https://linux-hardware.org/?probe=d28168f646) | Oct 20, 2020 |
| HP            | 82F2 A01                    | [8fb1e5339c](https://linux-hardware.org/?probe=8fb1e5339c) | Oct 17, 2020 |
| MSI           | 2A9C                        | [60d4bfc9de](https://linux-hardware.org/?probe=60d4bfc9de) | Oct 16, 2020 |
| Dell          | 0XHGV1 A00                  | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| Shuttle       | FS110                       | [5e555b749c](https://linux-hardware.org/?probe=5e555b749c) | Oct 15, 2020 |
| HP            | 843B                        | [86632c3a3e](https://linux-hardware.org/?probe=86632c3a3e) | Oct 15, 2020 |
| HP            | 158B                        | [714dc50b38](https://linux-hardware.org/?probe=714dc50b38) | Oct 15, 2020 |
| ASUSTek       | Z170-AR                     | [68df141e31](https://linux-hardware.org/?probe=68df141e31) | Oct 14, 2020 |
| Dell          | Dimension 5100              | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| Lenovo        | MAHOBAY                     | [b23c5d6ffd](https://linux-hardware.org/?probe=b23c5d6ffd) | Oct 14, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [930cc6ba98](https://linux-hardware.org/?probe=930cc6ba98) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Gigabyte      | B450 AORUS M                | [2bbb556fce](https://linux-hardware.org/?probe=2bbb556fce) | Oct 14, 2020 |
| Lenovo        | ThinkCentre M58e 7408BA5    | [505cd9e4f6](https://linux-hardware.org/?probe=505cd9e4f6) | Oct 13, 2020 |
| ASUSTek       | P5Q-E                       | [b59905555f](https://linux-hardware.org/?probe=b59905555f) | Oct 12, 2020 |
| Gigabyte      | B150M-HD3-CF                | [393ee605a8](https://linux-hardware.org/?probe=393ee605a8) | Oct 07, 2020 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [a0560ef7de](https://linux-hardware.org/?probe=a0560ef7de) | Oct 07, 2020 |
| Gigabyte      | Z77-D3H                     | [66018917e4](https://linux-hardware.org/?probe=66018917e4) | Oct 05, 2020 |
| ASUSTek       | PRIME X470-PRO              | [36b807b440](https://linux-hardware.org/?probe=36b807b440) | Oct 05, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [359e6431c4](https://linux-hardware.org/?probe=359e6431c4) | Oct 05, 2020 |
| MSI           | MAG Z390 TOMAHAWK           | [77b2ccc8f7](https://linux-hardware.org/?probe=77b2ccc8f7) | Sep 20, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| MSI           | Z87-G45 GAMING              | [142d422a44](https://linux-hardware.org/?probe=142d422a44) | Sep 09, 2020 |
| Gigabyte      | Z97X-UD5H                   | [779949fca8](https://linux-hardware.org/?probe=779949fca8) | Sep 09, 2020 |
| HP            | 2AF3                        | [436d491c10](https://linux-hardware.org/?probe=436d491c10) | Sep 04, 2020 |
| HP            | 2AF3                        | [9618698fa4](https://linux-hardware.org/?probe=9618698fa4) | Sep 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| Dell          | 0YJPT1 A00                  | [54ee6486e4](https://linux-hardware.org/?probe=54ee6486e4) | Sep 01, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [1e5956278f](https://linux-hardware.org/?probe=1e5956278f) | Sep 01, 2020 |
| ASUSTek       | STRIX Z270H GAMING          | [ca6cdad0fc](https://linux-hardware.org/?probe=ca6cdad0fc) | Sep 01, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [3fa1727f63](https://linux-hardware.org/?probe=3fa1727f63) | Aug 28, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [62455c5947](https://linux-hardware.org/?probe=62455c5947) | Aug 28, 2020 |
| HP            | 2AFA                        | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| ASRock        | H77 Pro4/MVP                | [a235fadae8](https://linux-hardware.org/?probe=a235fadae8) | Aug 20, 2020 |
| HP            | 0AE8h C                     | [2c1ae8f199](https://linux-hardware.org/?probe=2c1ae8f199) | Jul 18, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ba0d58a56a](https://linux-hardware.org/?probe=ba0d58a56a) | Jul 16, 2020 |
| HP            | 843B                        | [27dae7b96d](https://linux-hardware.org/?probe=27dae7b96d) | May 25, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8361eff2e8](https://linux-hardware.org/?probe=8361eff2e8) | Apr 27, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [daf65ba215](https://linux-hardware.org/?probe=daf65ba215) | Apr 19, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [a76ba909ef](https://linux-hardware.org/?probe=a76ba909ef) | Apr 17, 2020 |
| ASUSTek       | PRIME X470-PRO              | [e9be68d1ba](https://linux-hardware.org/?probe=e9be68d1ba) | Apr 13, 2020 |
| ASUSTek       | PRIME Z390-A                | [4823f5bb65](https://linux-hardware.org/?probe=4823f5bb65) | Mar 31, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [165309707f](https://linux-hardware.org/?probe=165309707f) | Mar 24, 2020 |
| ASUSTek       | PRIME B450M-A               | [e973706460](https://linux-hardware.org/?probe=e973706460) | Mar 24, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [d316d9c7f4](https://linux-hardware.org/?probe=d316d9c7f4) | Mar 09, 2020 |
| ASRock        | P55DE3                      | [af644cb23e](https://linux-hardware.org/?probe=af644cb23e) | Feb 10, 2020 |
| ASUSTek       | PRIME X470-PRO              | [da709d9bae](https://linux-hardware.org/?probe=da709d9bae) | Feb 09, 2020 |
| ASRock        | FM2A88X Extreme6+           | [2f34f5c135](https://linux-hardware.org/?probe=2f34f5c135) | Jan 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [2aea82baf4](https://linux-hardware.org/?probe=2aea82baf4) | Dec 29, 2019 |
| ASRock        | FM2A88X Extreme6+           | [0dc9dd21f6](https://linux-hardware.org/?probe=0dc9dd21f6) | Dec 28, 2019 |
| ASUSTek       | PRIME A320M-K               | [de065f2cfc](https://linux-hardware.org/?probe=de065f2cfc) | Dec 22, 2019 |
| ASUSTek       | PRIME A320M-K               | [c898033824](https://linux-hardware.org/?probe=c898033824) | Dec 18, 2019 |
| ASUSTek       | PRIME A320M-K               | [833f4e96c9](https://linux-hardware.org/?probe=833f4e96c9) | Dec 08, 2019 |
| ASUSTek       | PRIME A320M-K               | [4ec0437226](https://linux-hardware.org/?probe=4ec0437226) | Dec 07, 2019 |
| Dell          | 0H0P0M A00                  | [074175e3f0](https://linux-hardware.org/?probe=074175e3f0) | Nov 05, 2019 |
| Dell          | 0H0P0M A00                  | [ad47c45f44](https://linux-hardware.org/?probe=ad47c45f44) | Nov 05, 2019 |
| ASUSTek       | P8Z77-V DELUXE              | [55f43c974b](https://linux-hardware.org/?probe=55f43c974b) | Sep 26, 2019 |
| Dell          | 05DN3X A00                  | [39bc0ad7b5](https://linux-hardware.org/?probe=39bc0ad7b5) | Sep 22, 2019 |
| ASUSTek       | Z97-A                       | [6489d4345b](https://linux-hardware.org/?probe=6489d4345b) | Aug 06, 2019 |
| ASUSTek       | Z97-A                       | [98918645ab](https://linux-hardware.org/?probe=98918645ab) | Aug 02, 2019 |
| ASUSTek       | M5A97 EVO R2.0              | [d5ecd1cb87](https://linux-hardware.org/?probe=d5ecd1cb87) | Apr 09, 2019 |
| ASRock        | AB350 Gaming-ITX/ac         | [f0bef09470](https://linux-hardware.org/?probe=f0bef09470) | Jul 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ArcoLinux Rolling  | 474      | 90.8%   |
| ArcoLinux          | 23       | 4.41%   |
| ArcoLinux 20.7.5   | 4        | 0.77%   |
| ArcoLinux 20.6.5   | 3        | 0.57%   |
| ArcoLinux 19.12.15 | 3        | 0.57%   |
| ArcoLinux 20.3.4   | 2        | 0.38%   |
| ArcoLinux 20.2.12  | 2        | 0.38%   |
| ArcoLinux 19.07.11 | 2        | 0.38%   |
| ArcoLinux 6.9.1    | 1        | 0.19%   |
| ArcoLinux 20.5.7   | 1        | 0.19%   |
| ArcoLinux 20.5.2   | 1        | 0.19%   |
| ArcoLinux 20.4.11  | 1        | 0.19%   |
| ArcoLinux 20.3.3   | 1        | 0.19%   |
| ArcoLinux 20.2.9   | 1        | 0.19%   |
| ArcoLinux 20.1.4   | 1        | 0.19%   |
| ArcoLinux 19.11.3  | 1        | 0.19%   |
| ArcoLinux 19.02.4  | 1        | 0.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| ArcoLinux | 520      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.7-arch1-1    | 26       | 4.01%   |
| 5.15.10-arch1-1   | 19       | 2.93%   |
| 5.13.13-arch1-1   | 18       | 2.78%   |
| 5.16.11-arch1-1   | 17       | 2.62%   |
| 5.8.14-arch1-1    | 14       | 2.16%   |
| 5.14.14-arch1-1   | 11       | 1.7%    |
| 5.9.14-arch1-1    | 10       | 1.54%   |
| 5.15.4-arch1-1    | 8        | 1.23%   |
| 5.9.6-arch1-1     | 7        | 1.08%   |
| 5.8.5-arch1-1     | 7        | 1.08%   |
| 5.15.7-zen1-1-zen | 7        | 1.08%   |
| 5.15.2-arch1-1    | 7        | 1.08%   |
| 5.13.12-arch1-1   | 7        | 1.08%   |
| 5.12.12-arch1-1   | 7        | 1.08%   |
| 5.11.16-arch1-1   | 7        | 1.08%   |
| 5.17.9-arch1-1    | 6        | 0.93%   |
| 5.16.2-arch1-1    | 6        | 0.93%   |
| 5.14.16-arch1-1   | 6        | 0.93%   |
| 5.14.12-arch1-1   | 6        | 0.93%   |
| 5.12.15-arch1-1   | 6        | 0.93%   |
| 5.11.6-arch1-1    | 6        | 0.93%   |
| 5.10.84-1-lts     | 6        | 0.93%   |
| 5.10.3-arch1-1    | 6        | 0.93%   |
| 5.18.3-arch1-1    | 5        | 0.77%   |
| 5.18.1-arch1-1    | 5        | 0.77%   |
| 5.17.5-arch1-1    | 5        | 0.77%   |
| 5.17.1-arch1-1    | 5        | 0.77%   |
| 5.15.6-arch2-1    | 5        | 0.77%   |
| 5.15.5-arch1-1    | 5        | 0.77%   |
| 5.15.12-arch1-1   | 5        | 0.77%   |
| 5.10.61-1-lts     | 5        | 0.77%   |
| 5.9.9-arch1-1     | 4        | 0.62%   |
| 5.9.8-arch1-1     | 4        | 0.62%   |
| 5.9.13-arch1-1    | 4        | 0.62%   |
| 5.9.11-arch2-1    | 4        | 0.62%   |
| 5.9.1-arch1-1     | 4        | 0.62%   |
| 5.17.4-arch1-1    | 4        | 0.62%   |
| 5.17.3-arch1-1    | 4        | 0.62%   |
| 5.16.16-arch1-1   | 4        | 0.62%   |
| 5.15.11-arch2-1   | 4        | 0.62%   |
| 5.14.6-arch1-1    | 4        | 0.62%   |
| 5.14.2-arch1-2    | 4        | 0.62%   |
| 5.12.13-arch1-2   | 4        | 0.62%   |
| 5.12.10-arch1-1   | 4        | 0.62%   |
| 5.12.1-arch1-1    | 4        | 0.62%   |
| 5.11.2-arch1-1    | 4        | 0.62%   |
| 5.10.7-arch1-1    | 4        | 0.62%   |
| 5.9.10-arch1-1    | 3        | 0.46%   |
| 5.18.6-arch1-1    | 3        | 0.46%   |
| 5.18.5-zen1-1-zen | 3        | 0.46%   |
| 5.18.5-arch1-1    | 3        | 0.46%   |
| 5.17.5-zen1-1-zen | 3        | 0.46%   |
| 5.17.1-zen1-1-zen | 3        | 0.46%   |
| 5.16.10-arch1-1   | 3        | 0.46%   |
| 5.15.4-zen1-1-zen | 3        | 0.46%   |
| 5.14.8-arch1-1    | 3        | 0.46%   |
| 5.14.11-arch1-1   | 3        | 0.46%   |
| 5.13.8-arch1-1    | 3        | 0.46%   |
| 5.13.5-arch1-1    | 3        | 0.46%   |
| 5.12.8-arch1-1    | 3        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.7  | 33       | 5.09%   |
| 5.15.10 | 21       | 3.24%   |
| 5.16.11 | 19       | 2.93%   |
| 5.13.13 | 18       | 2.78%   |
| 5.8.14  | 14       | 2.16%   |
| 5.15.4  | 12       | 1.85%   |
| 5.14.14 | 11       | 1.7%    |
| 5.9.14  | 10       | 1.54%   |
| 5.17.5  | 10       | 1.54%   |
| 5.9.6   | 9        | 1.39%   |
| 5.17.1  | 9        | 1.39%   |
| 5.13.12 | 9        | 1.39%   |
| 5.8.5   | 8        | 1.23%   |
| 5.16.2  | 8        | 1.23%   |
| 5.15.2  | 8        | 1.23%   |
| 5.14.16 | 8        | 1.23%   |
| 5.12.15 | 8        | 1.23%   |
| 5.11.16 | 8        | 1.23%   |
| 5.17.9  | 7        | 1.08%   |
| 5.15.6  | 7        | 1.08%   |
| 5.15.12 | 7        | 1.08%   |
| 5.14.12 | 7        | 1.08%   |
| 5.12.12 | 7        | 1.08%   |
| 5.18.5  | 6        | 0.93%   |
| 5.18.1  | 6        | 0.93%   |
| 5.16.16 | 6        | 0.93%   |
| 5.15.5  | 6        | 0.93%   |
| 5.12.13 | 6        | 0.93%   |
| 5.11.6  | 6        | 0.93%   |
| 5.10.84 | 6        | 0.93%   |
| 5.10.3  | 6        | 0.93%   |
| 5.9.9   | 5        | 0.77%   |
| 5.9.8   | 5        | 0.77%   |
| 5.9.11  | 5        | 0.77%   |
| 5.9.1   | 5        | 0.77%   |
| 5.18.3  | 5        | 0.77%   |
| 5.15.11 | 5        | 0.77%   |
| 5.14.9  | 5        | 0.77%   |
| 5.14.2  | 5        | 0.77%   |
| 5.14.11 | 5        | 0.77%   |
| 5.10.61 | 5        | 0.77%   |
| 5.10.13 | 5        | 0.77%   |
| 5.9.13  | 4        | 0.62%   |
| 5.9.10  | 4        | 0.62%   |
| 5.17.4  | 4        | 0.62%   |
| 5.17.3  | 4        | 0.62%   |
| 5.16.12 | 4        | 0.62%   |
| 5.15.8  | 4        | 0.62%   |
| 5.15.3  | 4        | 0.62%   |
| 5.14.8  | 4        | 0.62%   |
| 5.14.6  | 4        | 0.62%   |
| 5.12.8  | 4        | 0.62%   |
| 5.12.10 | 4        | 0.62%   |
| 5.12.1  | 4        | 0.62%   |
| 5.11.7  | 4        | 0.62%   |
| 5.11.2  | 4        | 0.62%   |
| 5.11.15 | 4        | 0.62%   |
| 5.10.7  | 4        | 0.62%   |
| 5.10.16 | 4        | 0.62%   |
| 5.8.13  | 3        | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 124      | 19.81%  |
| 5.10    | 83       | 13.26%  |
| 5.16    | 60       | 9.58%   |
| 5.14    | 57       | 9.11%   |
| 5.9     | 49       | 7.83%   |
| 5.12    | 44       | 7.03%   |
| 5.13    | 43       | 6.87%   |
| 5.11    | 40       | 6.39%   |
| 5.17    | 37       | 5.91%   |
| 5.8     | 28       | 4.47%   |
| 5.18    | 23       | 3.67%   |
| 5.4     | 22       | 3.51%   |
| 5.6     | 5        | 0.8%    |
| 5.3     | 3        | 0.48%   |
| 5.7     | 2        | 0.32%   |
| 5.5     | 2        | 0.32%   |
| 4.19    | 2        | 0.32%   |
| 5.0     | 1        | 0.16%   |
| 4.17    | 1        | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 520      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| XFCE           | 201      | 36.28%  |
| KDE5           | 105      | 18.95%  |
| awesome        | 38       | 6.86%   |
| i3             | 32       | 5.78%   |
| GNOME          | 28       | 5.05%   |
| X-Cinnamon     | 22       | 3.97%   |
| qtile          | 17       | 3.07%   |
| xmonad         | 16       | 2.89%   |
| bspwm          | 13       | 2.35%   |
| Unknown        | 12       | 2.17%   |
| DWM            | 11       | 1.99%   |
| KDE            | 10       | 1.81%   |
| Cinnamon       | 10       | 1.81%   |
| LeftWM         | 9        | 1.62%   |
| LXQt           | 7        | 1.26%   |
| Deepin         | 6        | 1.08%   |
| MATE           | 4        | 0.72%   |
| Cutefish       | 3        | 0.54%   |
| Budgie         | 3        | 0.54%   |
| herbstluftwm   | 2        | 0.36%   |
| Unity          | 1        | 0.18%   |
| openbox        | 1        | 0.18%   |
| ICEWM          | 1        | 0.18%   |
| i3-with-shmlog | 1        | 0.18%   |
| dusk           | 1        | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 465      | 88.57%  |
| Tty     | 48       | 9.14%   |
| Wayland | 6        | 1.14%   |
| Unknown | 6        | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 283      | 50.99%  |
| TDM     | 133      | 23.96%  |
| LightDM | 88       | 15.86%  |
| Unknown | 44       | 7.93%   |
| GDM     | 5        | 0.9%    |
| Ly      | 2        | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 301      | 57.01%  |
| en_GB   | 57       | 10.8%   |
| de_DE   | 23       | 4.36%   |
| en_CA   | 18       | 3.41%   |
| en_AU   | 14       | 2.65%   |
| es_ES   | 10       | 1.89%   |
| ru_RU   | 9        | 1.7%    |
| fr_FR   | 9        | 1.7%    |
| en_IN   | 8        | 1.52%   |
| pt_BR   | 7        | 1.33%   |
| sv_SE   | 6        | 1.14%   |
| Unknown | 6        | 1.14%   |
| en_ZA   | 5        | 0.95%   |
| pl_PL   | 4        | 0.76%   |
| nl_NL   | 4        | 0.76%   |
| it_IT   | 4        | 0.76%   |
| hu_HU   | 4        | 0.76%   |
| fi_FI   | 4        | 0.76%   |
| es_AR   | 4        | 0.76%   |
| tr_TR   | 3        | 0.57%   |
| pt_PT   | 3        | 0.57%   |
| nl_BE   | 2        | 0.38%   |
| fr_CA   | 2        | 0.38%   |
| en_SG   | 2        | 0.38%   |
| en_IL   | 2        | 0.38%   |
| en_IE   | 2        | 0.38%   |
| de_AT   | 2        | 0.38%   |
| da_DK   | 2        | 0.38%   |
| zh_CN   | 1        | 0.19%   |
| uk_UA   | 1        | 0.19%   |
| sl_SI   | 1        | 0.19%   |
| ru_UA   | 1        | 0.19%   |
| lt_LT   | 1        | 0.19%   |
| es_CO   | 1        | 0.19%   |
| en_NZ   | 1        | 0.19%   |
| en_DK   | 1        | 0.19%   |
| de_CH   | 1        | 0.19%   |
| C       | 1        | 0.19%   |
| bg_BG   | 1        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 364      | 69.47%  |
| BIOS | 160      | 30.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 403      | 74.91%  |
| Btrfs   | 88       | 16.36%  |
| Overlay | 30       | 5.58%   |
| F2fs    | 6        | 1.12%   |
| Unknown | 6        | 1.12%   |
| Xfs     | 5        | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 407      | 77.08%  |
| MBR     | 80       | 15.15%  |
| Unknown | 41       | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 354      | 65.92%  |
| Yes       | 183      | 34.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 266      | 50.38%  |
| No        | 262      | 49.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 158      | 30.38%  |
| Gigabyte Technology | 92       | 17.69%  |
| MSI                 | 81       | 15.58%  |
| ASRock              | 50       | 9.62%   |
| Dell                | 33       | 6.35%   |
| Hewlett-Packard     | 28       | 5.38%   |
| Supermicro          | 14       | 2.69%   |
| Lenovo              | 14       | 2.69%   |
| Unknown             | 9        | 1.73%   |
| Intel               | 7        | 1.35%   |
| Acer                | 5        | 0.96%   |
| Pegatron            | 3        | 0.58%   |
| Medion              | 3        | 0.58%   |
| Foxconn             | 3        | 0.58%   |
| Biostar             | 2        | 0.38%   |
| Apple               | 2        | 0.38%   |
| Alienware           | 2        | 0.38%   |
| VS Company          | 1        | 0.19%   |
| SYWZ                | 1        | 0.19%   |
| System76            | 1        | 0.19%   |
| Shuttle             | 1        | 0.19%   |
| Seeed Studio        | 1        | 0.19%   |
| Proline             | 1        | 0.19%   |
| PLEXHD              | 1        | 0.19%   |
| Packard Bell        | 1        | 0.19%   |
| Maibenben           | 1        | 0.19%   |
| Huanan              | 1        | 0.19%   |
| Fujitsu             | 1        | 0.19%   |
| EVGA                | 1        | 0.19%   |
| ECS                 | 1        | 0.19%   |
| BESSTAR Tech        | 1        | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Supermicro SYS-5019A-FTN4      | 10       | 1.92%   |
| ASUS TUF Gaming X570-PLUS      | 10       | 1.92%   |
| ASUS All Series                | 10       | 1.92%   |
| Unknown                        | 10       | 1.92%   |
| ASUS ROG STRIX B550-F GAMING   | 8        | 1.54%   |
| MSI MS-7C37                    | 7        | 1.35%   |
| MSI MS-7C91                    | 6        | 1.15%   |
| ASUS PRIME X470-PRO            | 6        | 1.15%   |
| MSI MS-7B79                    | 5        | 0.96%   |
| ASUS PRIME X570-P              | 5        | 0.96%   |
| MSI MS-7B89                    | 4        | 0.77%   |
| MSI MS-7971                    | 4        | 0.77%   |
| Gigabyte X570 AORUS MASTER     | 4        | 0.77%   |
| Dell OptiPlex 7010             | 4        | 0.77%   |
| ASUS Z170 PRO GAMING           | 4        | 0.77%   |
| ASUS STRIX Z270H GAMING        | 4        | 0.77%   |
| ASUS PRIME B450M-A             | 4        | 0.77%   |
| ASUS PRIME A320M-K             | 4        | 0.77%   |
| ASRock B450M Pro4              | 4        | 0.77%   |
| MSI MS-7B86                    | 3        | 0.58%   |
| MSI MS-7A38                    | 3        | 0.58%   |
| MSI MS-7817                    | 3        | 0.58%   |
| HP EliteDesk 800 G1 SFF        | 3        | 0.58%   |
| Gigabyte B450 AORUS ELITE      | 3        | 0.58%   |
| ASUS ROG STRIX X570-E GAMING   | 3        | 0.58%   |
| ASUS ROG STRIX B450-F GAMING   | 3        | 0.58%   |
| ASUS ROG CROSSHAIR VIII HERO   | 3        | 0.58%   |
| ASUS PRIME X570-PRO            | 3        | 0.58%   |
| ASUS M5A78L-M/USB3             | 3        | 0.58%   |
| ASUS CROSSHAIR VI HERO         | 3        | 0.58%   |
| Supermicro SYS-E100-9AP        | 2        | 0.38%   |
| Supermicro SYS-110C-FHN4T      | 2        | 0.38%   |
| MSI MS-7C88                    | 2        | 0.38%   |
| MSI MS-7C56                    | 2        | 0.38%   |
| MSI MS-7C35                    | 2        | 0.38%   |
| MSI MS-7C02                    | 2        | 0.38%   |
| MSI MS-7B98                    | 2        | 0.38%   |
| MSI MS-7B85                    | 2        | 0.38%   |
| MSI MS-7B78                    | 2        | 0.38%   |
| MSI MS-7A34                    | 2        | 0.38%   |
| MSI MS-7821                    | 2        | 0.38%   |
| HP Pavilion Desktop 590-p0xxx  | 2        | 0.38%   |
| Gigabyte Z77X-D3H              | 2        | 0.38%   |
| Gigabyte Z77-D3H               | 2        | 0.38%   |
| Gigabyte X570 GAMING X         | 2        | 0.38%   |
| Gigabyte X570 AORUS PRO WIFI   | 2        | 0.38%   |
| Gigabyte X570 AORUS ELITE WIFI | 2        | 0.38%   |
| Gigabyte B550I AORUS PRO AX    | 2        | 0.38%   |
| Gigabyte B450M DS3H V2         | 2        | 0.38%   |
| Gigabyte B450M DS3H            | 2        | 0.38%   |
| Gigabyte B450 AORUS PRO        | 2        | 0.38%   |
| Gigabyte B450 AORUS M          | 2        | 0.38%   |
| Gigabyte B365M H               | 2        | 0.38%   |
| Gigabyte A520M H               | 2        | 0.38%   |
| Gigabyte 970A-DS3P             | 2        | 0.38%   |
| Dell XPS 8930                  | 2        | 0.38%   |
| Dell OptiPlex 9020             | 2        | 0.38%   |
| Dell OptiPlex 9010             | 2        | 0.38%   |
| Dell OptiPlex 7050             | 2        | 0.38%   |
| Dell OptiPlex 3040             | 2        | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 39       | 7.5%    |
| ASUS ROG                  | 30       | 5.77%   |
| ASUS TUF                  | 24       | 4.62%   |
| Dell OptiPlex             | 17       | 3.27%   |
| Gigabyte X570             | 11       | 2.12%   |
| Supermicro SYS-5019A-FTN4 | 10       | 1.92%   |
| ASUS All                  | 10       | 1.92%   |
| Unknown                   | 10       | 1.92%   |
| Lenovo ThinkCentre        | 8        | 1.54%   |
| Gigabyte B450             | 8        | 1.54%   |
| MSI MS-7C37               | 7        | 1.35%   |
| HP EliteDesk              | 7        | 1.35%   |
| MSI MS-7C91               | 6        | 1.15%   |
| Dell Inspiron             | 6        | 1.15%   |
| ASUS STRIX                | 6        | 1.15%   |
| ASUS P8Z77-V              | 6        | 1.15%   |
| ASRock B450M              | 6        | 1.15%   |
| MSI MS-7B79               | 5        | 0.96%   |
| MSI MS-7B89               | 4        | 0.77%   |
| MSI MS-7971               | 4        | 0.77%   |
| HP Compaq                 | 4        | 0.77%   |
| Gigabyte B550             | 4        | 0.77%   |
| Gigabyte B450M            | 4        | 0.77%   |
| Dell XPS                  | 4        | 0.77%   |
| Dell Vostro               | 4        | 0.77%   |
| ASUS Z170                 | 4        | 0.77%   |
| ASUS M5A78L-M             | 4        | 0.77%   |
| MSI MS-7B86               | 3        | 0.58%   |
| MSI MS-7A38               | 3        | 0.58%   |
| MSI MS-7817               | 3        | 0.58%   |
| HP Pavilion               | 3        | 0.58%   |
| Gigabyte B365M            | 3        | 0.58%   |
| Gigabyte A520M            | 3        | 0.58%   |
| ASUS P8H61-M              | 3        | 0.58%   |
| ASUS CROSSHAIR            | 3        | 0.58%   |
| ASRock X570               | 3        | 0.58%   |
| ASRock B450               | 3        | 0.58%   |
| Acer Aspire               | 3        | 0.58%   |
| Supermicro SYS-E100-9AP   | 2        | 0.38%   |
| Supermicro SYS-110C-FHN4T | 2        | 0.38%   |
| MSI MS-7C88               | 2        | 0.38%   |
| MSI MS-7C56               | 2        | 0.38%   |
| MSI MS-7C35               | 2        | 0.38%   |
| MSI MS-7C02               | 2        | 0.38%   |
| MSI MS-7B98               | 2        | 0.38%   |
| MSI MS-7B85               | 2        | 0.38%   |
| MSI MS-7B78               | 2        | 0.38%   |
| MSI MS-7A34               | 2        | 0.38%   |
| MSI MS-7821               | 2        | 0.38%   |
| Lenovo ThinkStation       | 2        | 0.38%   |
| Lenovo IdeaCentre         | 2        | 0.38%   |
| HP Desktop                | 2        | 0.38%   |
| Gigabyte Z77X-D3H         | 2        | 0.38%   |
| Gigabyte Z77-D3H          | 2        | 0.38%   |
| Gigabyte B550I            | 2        | 0.38%   |
| Gigabyte 970A-DS3P        | 2        | 0.38%   |
| ASUS Z170-A               | 2        | 0.38%   |
| ASUS P8Z68-V              | 2        | 0.38%   |
| ASUS Maximus              | 2        | 0.38%   |
| ASUS M5A97                | 2        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 90       | 17.31%  |
| 2019    | 86       | 16.54%  |
| 2020    | 63       | 12.12%  |
| 2017    | 41       | 7.88%   |
| 2013    | 39       | 7.5%    |
| 2015    | 35       | 6.73%   |
| 2012    | 31       | 5.96%   |
| 2011    | 27       | 5.19%   |
| 2021    | 26       | 5%      |
| 2016    | 22       | 4.23%   |
| 2014    | 20       | 3.85%   |
| 2010    | 16       | 3.08%   |
| 2009    | 10       | 1.92%   |
| 2008    | 5        | 0.96%   |
| 2006    | 4        | 0.77%   |
| 2007    | 3        | 0.58%   |
| 2005    | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 520      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 520      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 520      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 171      | 32.14%  |
| 32.01-64.0  | 137      | 25.75%  |
| 8.01-16.0   | 90       | 16.92%  |
| 4.01-8.0    | 57       | 10.71%  |
| 64.01-256.0 | 28       | 5.26%   |
| 3.01-4.0    | 26       | 4.89%   |
| 24.01-32.0  | 18       | 3.38%   |
| 1.01-2.0    | 3        | 0.56%   |
| 2.01-3.0    | 1        | 0.19%   |
| Unknown     | 1        | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 161      | 27.24%  |
| 2.01-3.0   | 148      | 25.04%  |
| 4.01-8.0   | 109      | 18.44%  |
| 3.01-4.0   | 69       | 11.68%  |
| 0.51-1.0   | 55       | 9.31%   |
| 8.01-16.0  | 32       | 5.41%   |
| 0.01-0.5   | 14       | 2.37%   |
| 16.01-24.0 | 2        | 0.34%   |
| Unknown    | 1        | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 155      | 28.49%  |
| 1      | 119      | 21.88%  |
| 3      | 115      | 21.14%  |
| 4      | 85       | 15.63%  |
| 5      | 36       | 6.62%   |
| 6      | 14       | 2.57%   |
| 7      | 9        | 1.65%   |
| 9      | 3        | 0.55%   |
| 8      | 3        | 0.55%   |
| 0      | 3        | 0.55%   |
| 11     | 1        | 0.18%   |
| 10     | 1        | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 355      | 66.98%  |
| Yes       | 175      | 33.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 518      | 99.62%  |
| No        | 2        | 0.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 293      | 56.13%  |
| Yes       | 229      | 43.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 313      | 58.83%  |
| Yes       | 219      | 41.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                   | Desktops | Percent |
|---------------------------|----------|---------|
| USA                       | 131      | 25.1%   |
| UK                        | 38       | 7.28%   |
| Germany                   | 38       | 7.28%   |
| Canada                    | 25       | 4.79%   |
| Brazil                    | 18       | 3.45%   |
| Australia                 | 15       | 2.87%   |
| Spain                     | 14       | 2.68%   |
| Belgium                   | 14       | 2.68%   |
| Netherlands               | 13       | 2.49%   |
| India                     | 12       | 2.3%    |
| France                    | 12       | 2.3%    |
| Russia                    | 11       | 2.11%   |
| Sweden                    | 10       | 1.92%   |
| Romania                   | 8        | 1.53%   |
| Poland                    | 8        | 1.53%   |
| Austria                   | 8        | 1.53%   |
| Argentina                 | 8        | 1.53%   |
| Norway                    | 7        | 1.34%   |
| Bulgaria                  | 7        | 1.34%   |
| Switzerland               | 6        | 1.15%   |
| Greece                    | 6        | 1.15%   |
| Finland                   | 6        | 1.15%   |
| South Africa              | 5        | 0.96%   |
| Portugal                  | 5        | 0.96%   |
| Italy                     | 5        | 0.96%   |
| Ireland                   | 5        | 0.96%   |
| Colombia                  | 5        | 0.96%   |
| Ukraine                   | 4        | 0.77%   |
| Turkey                    | 4        | 0.77%   |
| Hungary                   | 4        | 0.77%   |
| Serbia                    | 3        | 0.57%   |
| Mexico                    | 3        | 0.57%   |
| Malaysia                  | 3        | 0.57%   |
| Lebanon                   | 3        | 0.57%   |
| Kenya                     | 3        | 0.57%   |
| Israel                    | 3        | 0.57%   |
| Indonesia                 | 3        | 0.57%   |
| Hong Kong                 | 3        | 0.57%   |
| Denmark                   | 3        | 0.57%   |
| Vietnam                   | 2        | 0.38%   |
| Slovakia                  | 2        | 0.38%   |
| Puerto Rico               | 2        | 0.38%   |
| Lithuania                 | 2        | 0.38%   |
| Czechia                   | 2        | 0.38%   |
| Croatia                   | 2        | 0.38%   |
| Chile                     | 2        | 0.38%   |
| Belarus                   | 2        | 0.38%   |
| Bangladesh                | 2        | 0.38%   |
| Azerbaijan                | 2        | 0.38%   |
| Uzbekistan                | 1        | 0.19%   |
| Tunisia                   | 1        | 0.19%   |
| Thailand                  | 1        | 0.19%   |
| St Vincent and Grenadines | 1        | 0.19%   |
| Slovenia                  | 1        | 0.19%   |
| Singapore                 | 1        | 0.19%   |
| Saudi Arabia              | 1        | 0.19%   |
| Papua New Guinea          | 1        | 0.19%   |
| Panama                    | 1        | 0.19%   |
| New Zealand               | 1        | 0.19%   |
| Nepal                     | 1        | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Durham           | 14       | 2.56%   |
| Sydney           | 10       | 1.83%   |
| Lier             | 7        | 1.28%   |
| Berlin           | 7        | 1.28%   |
| Vienna           | 6        | 1.1%    |
| Sao Paulo        | 5        | 0.92%   |
| Madrid           | 5        | 0.92%   |
| Wilrijk          | 4        | 0.73%   |
| Warsaw           | 4        | 0.73%   |
| Toronto          | 4        | 0.73%   |
| Sofia            | 4        | 0.73%   |
| Shetland Islands | 4        | 0.73%   |
| London           | 4        | 0.73%   |
| Dublin           | 4        | 0.73%   |
| Bucharest        | 4        | 0.73%   |
| Portland         | 3        | 0.55%   |
| New Delhi        | 3        | 0.55%   |
| Nairobi          | 3        | 0.55%   |
| Montreal         | 3        | 0.55%   |
| Miami            | 3        | 0.55%   |
| Istanbul         | 3        | 0.55%   |
| Helsinki         | 3        | 0.55%   |
| Haarlem          | 3        | 0.55%   |
| Edmonton         | 3        | 0.55%   |
| Dallas           | 3        | 0.55%   |
| Central          | 3        | 0.55%   |
| Benoni           | 3        | 0.55%   |
| Beirut           | 3        | 0.55%   |
| Athens           | 3        | 0.55%   |
| Zurich           | 2        | 0.37%   |
| Valencia         | 2        | 0.37%   |
| Tuscaloosa       | 2        | 0.37%   |
| Tucson           | 2        | 0.37%   |
| Tubbergen        | 2        | 0.37%   |
| Tobaccoville     | 2        | 0.37%   |
| Syracuse         | 2        | 0.37%   |
| Stittsville      | 2        | 0.37%   |
| Southampton      | 2        | 0.37%   |
| Snohomish        | 2        | 0.37%   |
| Shumen           | 2        | 0.37%   |
| Saarbrücken     | 2        | 0.37%   |
| Rosario          | 2        | 0.37%   |
| Rio de Janeiro   | 2        | 0.37%   |
| Paul             | 2        | 0.37%   |
| Paris            | 2        | 0.37%   |
| Oslo             | 2        | 0.37%   |
| New York         | 2        | 0.37%   |
| Moscow           | 2        | 0.37%   |
| Milton Keynes    | 2        | 0.37%   |
| Melbourne        | 2        | 0.37%   |
| Louisville       | 2        | 0.37%   |
| Lillehammer      | 2        | 0.37%   |
| Leiria           | 2        | 0.37%   |
| Las Vegas        | 2        | 0.37%   |
| Kyiv             | 2        | 0.37%   |
| Jacksonville     | 2        | 0.37%   |
| Ho Chi Minh City | 2        | 0.37%   |
| Duffel           | 2        | 0.37%   |
| Denver           | 2        | 0.37%   |
| Cotia            | 2        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 214      | 372    | 18.92%  |
| Samsung Electronics   | 212      | 415    | 18.74%  |
| Seagate               | 186      | 313    | 16.45%  |
| Toshiba               | 70       | 96     | 6.19%   |
| Kingston              | 62       | 76     | 5.48%   |
| Crucial               | 59       | 92     | 5.22%   |
| SanDisk               | 46       | 56     | 4.07%   |
| Hitachi               | 30       | 36     | 2.65%   |
| A-DATA Technology     | 24       | 31     | 2.12%   |
| Phison                | 19       | 33     | 1.68%   |
| Intel                 | 17       | 27     | 1.5%    |
| SPCC                  | 12       | 16     | 1.06%   |
| Corsair               | 12       | 20     | 1.06%   |
| Unknown               | 10       | 14     | 0.88%   |
| PNY                   | 10       | 18     | 0.88%   |
| XPG                   | 9        | 12     | 0.8%    |
| Patriot               | 8        | 11     | 0.71%   |
| Gigabyte Technology   | 8        | 10     | 0.71%   |
| Transcend             | 7        | 10     | 0.62%   |
| HGST                  | 7        | 10     | 0.62%   |
| China                 | 7        | 21     | 0.62%   |
| SK hynix              | 6        | 12     | 0.53%   |
| Silicon Motion        | 6        | 6      | 0.53%   |
| JMicron Technology    | 6        | 8      | 0.53%   |
| OCZ                   | 5        | 6      | 0.44%   |
| ASMT                  | 5        | 5      | 0.44%   |
| Plextor               | 4        | 4      | 0.35%   |
| Hewlett-Packard       | 4        | 4      | 0.35%   |
| TO Exter              | 3        | 3      | 0.27%   |
| Maxtor                | 3        | 5      | 0.27%   |
| LITEON                | 3        | 3      | 0.27%   |
| Vaseky                | 2        | 4      | 0.18%   |
| SABRENT               | 2        | 2      | 0.18%   |
| Mushkin               | 2        | 5      | 0.18%   |
| Leven                 | 2        | 2      | 0.18%   |
| KingSpec              | 2        | 2      | 0.18%   |
| Goodram               | 2        | 2      | 0.18%   |
| External              | 2        | 6      | 0.18%   |
| Drevo                 | 2        | 2      | 0.18%   |
| Apple                 | 2        | 2      | 0.18%   |
| AMD                   | 2        | 3      | 0.18%   |
| Unknown               | 2        | 2      | 0.18%   |
| WD MediaMax           | 1        | 1      | 0.09%   |
| Verbatim              | 1        | 1      | 0.09%   |
| V-GeN                 | 1        | 2      | 0.09%   |
| USB30                 | 1        | 1      | 0.09%   |
| tigo                  | 1        | 1      | 0.09%   |
| T-FORCE               | 1        | 1      | 0.09%   |
| Realtek Semiconductor | 1        | 1      | 0.09%   |
| Phison Electronics    | 1        | 1      | 0.09%   |
| Palit                 | 1        | 1      | 0.09%   |
| OEM                   | 1        | 1      | 0.09%   |
| Netac                 | 1        | 1      | 0.09%   |
| Micron Technology     | 1        | 2      | 0.09%   |
| LITEONIT              | 1        | 1      | 0.09%   |
| Lexar                 | 1        | 1      | 0.09%   |
| LaCie                 | 1        | 2      | 0.09%   |
| KODAK                 | 1        | 1      | 0.09%   |
| KIOXIA                | 1        | 1      | 0.09%   |
| KingFast              | 1        | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 26       | 1.87%   |
| Seagate ST1000DM010-2EP102 1TB   | 20       | 1.44%   |
| Samsung SSD 970 EVO Plus 500GB   | 20       | 1.44%   |
| Samsung SSD 850 EVO 250GB        | 17       | 1.22%   |
| Samsung SSD 850 EVO 500GB        | 16       | 1.15%   |
| WDC WD10EZEX-08WN4A0 1TB         | 15       | 1.08%   |
| Samsung SSD 970 EVO Plus 1TB     | 15       | 1.08%   |
| Samsung SSD 860 EVO 1TB          | 15       | 1.08%   |
| Kingston SA400S37240G 240GB SSD  | 15       | 1.08%   |
| Seagate ST2000DM008-2FR102 2TB   | 14       | 1.01%   |
| Samsung SSD 860 EVO 250GB        | 14       | 1.01%   |
| Seagate ST2000DM001-1ER164 2TB   | 13       | 0.94%   |
| Samsung SSD 970 EVO 1TB          | 12       | 0.86%   |
| Kingston SA400S37120G 120GB SSD  | 12       | 0.86%   |
| Toshiba KXG60ZNV1T02 1TB         | 10       | 0.72%   |
| Toshiba HDWD110 1TB              | 10       | 0.72%   |
| Crucial CT500MX500SSD1 500GB     | 10       | 0.72%   |
| Crucial CT1000P1SSD8 1TB         | 10       | 0.72%   |
| Seagate ST1000DM003-1ER162 1TB   | 9        | 0.65%   |
| Samsung SSD 840 EVO 250GB        | 9        | 0.65%   |
| Crucial CT1000MX500SSD1 1TB      | 9        | 0.65%   |
| Toshiba DT01ACA100 1TB           | 8        | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 7        | 0.5%    |
| Seagate ST4000DM004-2CV104 4TB   | 7        | 0.5%    |
| Seagate ST31000528AS 1TB         | 7        | 0.5%    |
| Samsung SSD 980 PRO 1TB          | 7        | 0.5%    |
| Samsung SSD 840 EVO 120GB        | 7        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 6        | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB      | 6        | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB      | 6        | 0.43%   |
| Toshiba HDWD120 2TB              | 6        | 0.43%   |
| Seagate ST3000DM001-1ER166 3TB   | 6        | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB   | 6        | 0.43%   |
| Seagate Expansion 1TB            | 6        | 0.43%   |
| SanDisk SDSSDA240G 240GB         | 6        | 0.43%   |
| Samsung SSD 870 EVO 1TB          | 6        | 0.43%   |
| Crucial CT240BX500SSD1 240GB     | 6        | 0.43%   |
| A-DATA SX8200PNP 512GB           | 6        | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 5        | 0.36%   |
| WDC WD10EZEX-00BN5A0 1TB         | 5        | 0.36%   |
| WDC WD1003FZEX-00K3CA0 1TB       | 5        | 0.36%   |
| Toshiba DT01ACA200 2TB           | 5        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB   | 5        | 0.36%   |
| SanDisk SSD PLUS 240GB           | 5        | 0.36%   |
| Samsung SSD 980 PRO 500GB        | 5        | 0.36%   |
| Samsung SSD 970 EVO 500GB        | 5        | 0.36%   |
| Samsung SSD 870 QVO 1TB          | 5        | 0.36%   |
| Patriot Burst 240GB SSD          | 5        | 0.36%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 0.36%   |
| Kingston SA2000M81000G 1TB       | 5        | 0.36%   |
| Intel SSDPEKNW010T8 1TB          | 5        | 0.36%   |
| Crucial CT250MX500SSD1 250GB     | 5        | 0.36%   |
| XPG GAMMIX S11 Pro 1TB           | 4        | 0.29%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 4        | 0.29%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 0.29%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 4        | 0.29%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 4        | 0.29%   |
| WDC WD40EFRX-68N32N0 4TB         | 4        | 0.29%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 4        | 0.29%   |
| WDC WD20EFRX-68EUZN0 2TB         | 4        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 181      | 299    | 37.17%  |
| WDC                 | 165      | 277    | 33.88%  |
| Toshiba             | 54       | 74     | 11.09%  |
| Hitachi             | 30       | 36     | 6.16%   |
| Samsung Electronics | 26       | 32     | 5.34%   |
| Unknown             | 7        | 10     | 1.44%   |
| HGST                | 7        | 10     | 1.44%   |
| JMicron Technology  | 4        | 4      | 0.82%   |
| Maxtor              | 3        | 5      | 0.62%   |
| ASMT                | 3        | 3      | 0.62%   |
| WD MediaMax         | 1        | 1      | 0.21%   |
| HGST HUS            | 1        | 1      | 0.21%   |
| HGST HTS            | 1        | 1      | 0.21%   |
| Hewlett-Packard     | 1        | 1      | 0.21%   |
| Fujitsu             | 1        | 1      | 0.21%   |
| ExcelStor           | 1        | 2      | 0.21%   |
| Unknown             | 1        | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 139      | 231    | 30.62%  |
| Kingston            | 51       | 59     | 11.23%  |
| Crucial             | 47       | 71     | 10.35%  |
| SanDisk             | 42       | 49     | 9.25%   |
| WDC                 | 40       | 54     | 8.81%   |
| A-DATA Technology   | 13       | 18     | 2.86%   |
| PNY                 | 10       | 16     | 2.2%    |
| SPCC                | 8        | 10     | 1.76%   |
| Patriot             | 8        | 11     | 1.76%   |
| China               | 7        | 21     | 1.54%   |
| Transcend           | 6        | 9      | 1.32%   |
| Toshiba             | 5        | 10     | 1.1%    |
| SK hynix            | 5        | 10     | 1.1%    |
| OCZ                 | 5        | 6      | 1.1%    |
| Intel               | 5        | 6      | 1.1%    |
| Gigabyte Technology | 4        | 4      | 0.88%   |
| Corsair             | 4        | 4      | 0.88%   |
| TO Exter            | 3        | 3      | 0.66%   |
| Vaseky              | 2        | 4      | 0.44%   |
| Unknown             | 2        | 2      | 0.44%   |
| Plextor             | 2        | 2      | 0.44%   |
| Mushkin             | 2        | 5      | 0.44%   |
| LITEON              | 2        | 2      | 0.44%   |
| Leven               | 2        | 2      | 0.44%   |
| KingSpec            | 2        | 2      | 0.44%   |
| Hewlett-Packard     | 2        | 2      | 0.44%   |
| Goodram             | 2        | 2      | 0.44%   |
| Drevo               | 2        | 2      | 0.44%   |
| ASMT                | 2        | 2      | 0.44%   |
| Apple               | 2        | 2      | 0.44%   |
| AMD                 | 2        | 3      | 0.44%   |
| Verbatim            | 1        | 1      | 0.22%   |
| V-GeN               | 1        | 2      | 0.22%   |
| USB30               | 1        | 1      | 0.22%   |
| T-FORCE             | 1        | 1      | 0.22%   |
| Seagate             | 1        | 3      | 0.22%   |
| Palit               | 1        | 1      | 0.22%   |
| Netac               | 1        | 1      | 0.22%   |
| Micron Technology   | 1        | 2      | 0.22%   |
| LITEONIT            | 1        | 1      | 0.22%   |
| Lexar               | 1        | 1      | 0.22%   |
| KODAK               | 1        | 1      | 0.22%   |
| KingFast            | 1        | 1      | 0.22%   |
| JMicron Technology  | 1        | 3      | 0.22%   |
| Intenso             | 1        | 1      | 0.22%   |
| INTEL SS            | 1        | 1      | 0.22%   |
| Integral            | 1        | 1      | 0.22%   |
| Innodisk            | 1        | 1      | 0.22%   |
| HS-SSD-E100         | 1        | 1      | 0.22%   |
| HS-SSD-C100         | 1        | 1      | 0.22%   |
| Hoodisk             | 1        | 1      | 0.22%   |
| CT240BX5            | 1        | 1      | 0.22%   |
| ASMedia             | 1        | 2      | 0.22%   |
| Apacer              | 1        | 1      | 0.22%   |
| addlink             | 1        | 1      | 0.22%   |
| 1TB                 | 1        | 1      | 0.22%   |
| Unknown             | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 370      | 758    | 39.4%   |
| SSD     | 341      | 657    | 36.32%  |
| NVMe    | 220      | 391    | 23.43%  |
| Unknown | 8        | 11     | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 472      | 1334   | 62.85%  |
| NVMe | 219      | 385    | 29.16%  |
| SAS  | 60       | 98     | 7.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 345      | 679    | 42.59%  |
| 0.51-1.0   | 256      | 396    | 31.6%   |
| 1.01-2.0   | 118      | 194    | 14.57%  |
| 3.01-4.0   | 42       | 63     | 5.19%   |
| 2.01-3.0   | 27       | 45     | 3.33%   |
| 4.01-10.0  | 19       | 31     | 2.35%   |
| 10.01-20.0 | 3        | 7      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 100      | 17.79%  |
| 501-1000       | 94       | 16.73%  |
| More than 3000 | 90       | 16.01%  |
| 251-500        | 87       | 15.48%  |
| 1001-2000      | 87       | 15.48%  |
| 2001-3000      | 40       | 7.12%   |
| 1-20           | 28       | 4.98%   |
| Unknown        | 20       | 3.56%   |
| 51-100         | 10       | 1.78%   |
| 21-50          | 6        | 1.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 128      | 21.81%  |
| 21-50          | 99       | 16.87%  |
| 101-250        | 72       | 12.27%  |
| 501-1000       | 67       | 11.41%  |
| 251-500        | 57       | 9.71%   |
| 51-100         | 54       | 9.2%    |
| 1001-2000      | 44       | 7.5%    |
| More than 3000 | 23       | 3.92%   |
| 2001-3000      | 23       | 3.92%   |
| Unknown        | 20       | 3.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB            | 5        | 5      | 3.29%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 4      | 1.97%   |
| Seagate ST1000DM003-9YN162 1TB      | 3        | 3      | 1.97%   |
| WDC WD5000AAKX-603CA0 500GB         | 2        | 6      | 1.32%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 1.32%   |
| WDC WD5000AAKX-001CA0 500GB         | 2        | 3      | 1.32%   |
| WDC WD40EFRX-68N32N0 4TB            | 2        | 6      | 1.32%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 2      | 1.32%   |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 3      | 1.32%   |
| Seagate ST9320325AS 320GB           | 2        | 3      | 1.32%   |
| Seagate ST3500413AS 500GB           | 2        | 2      | 1.32%   |
| Seagate ST3500312CS 500GB           | 2        | 4      | 1.32%   |
| Seagate ST31000524AS 1TB            | 2        | 2      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2        | 2      | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 2      | 1.32%   |
| Samsung Electronics SSD 870 EVO 1TB | 2        | 2      | 1.32%   |
| Maxtor STM3250310AS 250GB           | 2        | 3      | 1.32%   |
| Hitachi HDS723020BLA642 2TB         | 2        | 2      | 1.32%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 3      | 1.32%   |
| XPG SPECTRIX S40G 4TB               | 1        | 1      | 0.66%   |
| WDC WDS500G1X0E-00AFY0 500GB        | 1        | 1      | 0.66%   |
| WDC WD7500BPVT-55HXZT4 752GB        | 1        | 1      | 0.66%   |
| WDC WD6400AAKS-65Z7B0 640GB         | 1        | 1      | 0.66%   |
| WDC WD6400AAKS-22A7B2 640GB         | 1        | 2      | 0.66%   |
| WDC WD60EZRZ-00GZ5B1 6TB            | 1        | 1      | 0.66%   |
| WDC WD5000BEVT-75A0RT0 500GB        | 1        | 1      | 0.66%   |
| WDC WD5000BEVT-35A0RT0 500GB        | 1        | 1      | 0.66%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 1      | 0.66%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 1        | 1      | 0.66%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 1        | 1      | 0.66%   |
| WDC WD5000AAKS-60WWPA0 500GB        | 1        | 1      | 0.66%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 1      | 0.66%   |
| WDC WD5000AADS-00M2B0 500GB         | 1        | 1      | 0.66%   |
| WDC WD3200AVJS-63B6A0 320GB         | 1        | 1      | 0.66%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1        | 1      | 0.66%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1        | 1      | 0.66%   |
| WDC WD3200AAJS-00L7A0 320GB         | 1        | 1      | 0.66%   |
| WDC WD30EFRX-68N32N0 3TB            | 1        | 1      | 0.66%   |
| WDC WD30EFRX-68EUZN0 3TB            | 1        | 1      | 0.66%   |
| WDC WD25EZRX-00MMMB0 2TB            | 1        | 1      | 0.66%   |
| WDC WD2500AAKX-603CA0 250GB         | 1        | 1      | 0.66%   |
| WDC WD20EURS-63S48Y0 2TB            | 1        | 1      | 0.66%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1      | 0.66%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 2      | 0.66%   |
| WDC WD20EARS-00J99B0 2TB            | 1        | 1      | 0.66%   |
| WDC WD2002FAEX-007BA0 2TB           | 1        | 1      | 0.66%   |
| WDC WD2001FASS-00W2B0 2TB           | 1        | 2      | 0.66%   |
| WDC WD2000JD-00HBB0 200GB           | 1        | 1      | 0.66%   |
| WDC WD1600AVVS-63L2B0 160GB         | 1        | 2      | 0.66%   |
| WDC WD10PURZ-85U8XY0 1TB            | 1        | 1      | 0.66%   |
| WDC WD10EZRZ-22HTKB0 1TB            | 1        | 1      | 0.66%   |
| WDC WD10EZEX-21WN4A0 1TB            | 1        | 1      | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB            | 1        | 1      | 0.66%   |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 1      | 0.66%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 1      | 0.66%   |
| WDC WD10EADS-00L5B1 1TB             | 1        | 1      | 0.66%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1        | 1      | 0.66%   |
| WDC WD1003FZEX-00K3CA0 1TB          | 1        | 1      | 0.66%   |
| WDC WD1001FALS-403AA0 1TB           | 1        | 1      | 0.66%   |
| Transcend TS512GSSD720 512GB        | 1        | 1      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 45       | 65     | 31.47%  |
| Seagate             | 42       | 53     | 29.37%  |
| Samsung Electronics | 15       | 16     | 10.49%  |
| Hitachi             | 8        | 10     | 5.59%   |
| Toshiba             | 5        | 6      | 3.5%    |
| Kingston            | 4        | 6      | 2.8%    |
| Transcend           | 3        | 3      | 2.1%    |
| Maxtor              | 3        | 5      | 2.1%    |
| SanDisk             | 2        | 2      | 1.4%    |
| Intel               | 2        | 2      | 1.4%    |
| Drevo               | 2        | 2      | 1.4%    |
| Corsair             | 2        | 2      | 1.4%    |
| XPG                 | 1        | 1      | 0.7%    |
| SPCC                | 1        | 1      | 0.7%    |
| Patriot             | 1        | 1      | 0.7%    |
| HGST HTS            | 1        | 1      | 0.7%    |
| HGST                | 1        | 1      | 0.7%    |
| Hewlett-Packard     | 1        | 1      | 0.7%    |
| China               | 1        | 2      | 0.7%    |
| ASMedia             | 1        | 2      | 0.7%    |
| A-DATA Technology   | 1        | 1      | 0.7%    |
| Unknown             | 1        | 1      | 0.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 45       | 64     | 40.54%  |
| Seagate             | 42       | 53     | 37.84%  |
| Hitachi             | 8        | 10     | 7.21%   |
| Toshiba             | 5        | 6      | 4.5%    |
| Samsung Electronics | 5        | 5      | 4.5%    |
| Maxtor              | 3        | 5      | 2.7%    |
| HGST HTS            | 1        | 1      | 0.9%    |
| HGST                | 1        | 1      | 0.9%    |
| Unknown             | 1        | 1      | 0.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 99       | 146    | 75.57%  |
| SSD  | 26       | 31     | 19.85%  |
| NVMe | 6        | 7      | 4.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST32000641AS 2TB                         | 1        | 2      | 50%     |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 2      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 437      | 1381   | 64.45%  |
| Malfunc  | 129      | 184    | 19.03%  |
| Detected | 110      | 249    | 16.22%  |
| Failed   | 2        | 3      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 292      | 34.76%  |
| AMD                          | 228      | 27.14%  |
| Samsung Electronics          | 96       | 11.43%  |
| Phison Electronics           | 35       | 4.17%   |
| ASMedia Technology           | 35       | 4.17%   |
| SanDisk                      | 32       | 3.81%   |
| Marvell Technology Group     | 21       | 2.5%    |
| Micron/Crucial Technology    | 14       | 1.67%   |
| Kingston Technology Company  | 14       | 1.67%   |
| ADATA Technology             | 13       | 1.55%   |
| Toshiba America Info Systems | 11       | 1.31%   |
| Silicon Motion               | 9        | 1.07%   |
| Realtek Semiconductor        | 8        | 0.95%   |
| Seagate Technology           | 6        | 0.71%   |
| Nvidia                       | 6        | 0.71%   |
| JMicron Technology           | 6        | 0.71%   |
| Lite-On Technology           | 3        | 0.36%   |
| VIA Technologies             | 2        | 0.24%   |
| SK hynix                     | 2        | 0.24%   |
| Broadcom / LSI               | 2        | 0.24%   |
| Silicon Image                | 1        | 0.12%   |
| Shenzhen Longsys Electronics | 1        | 0.12%   |
| Micron Technology            | 1        | 0.12%   |
| LSI Logic / Symbios Logic    | 1        | 0.12%   |
| KIOXIA                       | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 149      | 14.69%  |
| AMD 400 Series Chipset SATA Controller                                                  | 72       | 7.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 66       | 6.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 40       | 3.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 37       | 3.65%   |
| AMD 500 Series Chipset SATA Controller                                                  | 37       | 3.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 34       | 3.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32       | 3.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 31       | 3.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 26       | 2.56%   |
| Phison E12 NVMe Controller                                                              | 22       | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19       | 1.87%   |
| Intel SATA Controller [RAID mode]                                                       | 16       | 1.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15       | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 1.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 14       | 1.38%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 13       | 1.28%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 13       | 1.28%   |
| Intel SSD 660P Series                                                                   | 11       | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 1.08%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 10       | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 10       | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 10       | 0.99%   |
| Kingston Company A2000 NVMe SSD                                                         | 10       | 0.99%   |
| Intel Atom Processor C3000 Series SATA Controller 1                                     | 10       | 0.99%   |
| Intel Atom Processor C3000 Series SATA Controller 0                                     | 10       | 0.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 8        | 0.79%   |
| AMD FCH SATA Controller D                                                               | 8        | 0.79%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 0.79%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 7        | 0.69%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 6        | 0.59%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 0.59%   |
| AMD X370 Series Chipset SATA Controller                                                 | 6        | 0.59%   |
| Samsung NVMe SSD Controller 980                                                         | 5        | 0.49%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 5        | 0.49%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.49%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.39%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4        | 0.39%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 4        | 0.39%   |
| Realtek Realtek Non-Volatile memory controller                                          | 4        | 0.39%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 0.39%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4        | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.39%   |
| AMD FCH IDE Controller                                                                  | 4        | 0.39%   |
| Seagate FireCuda 520 SSD                                                                | 3        | 0.3%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3        | 0.3%    |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.3%    |
| Micron/Crucial NVMe Controller                                                          | 3        | 0.3%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.3%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 0.3%    |
| JMicron JMB362 SATA Controller                                                          | 3        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 466      | 60.05%  |
| NVMe | 220      | 28.35%  |
| IDE  | 68       | 8.76%   |
| RAID | 20       | 2.58%   |
| SAS  | 1        | 0.13%   |
| SCSI | 1        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 285      | 54.81%  |
| AMD     | 234      | 45%     |
| Unknown | 1        | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 19       | 3.65%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 16       | 3.07%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 15       | 2.88%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 12       | 2.3%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 11       | 2.11%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 10       | 1.92%   |
| Intel Atom CPU C3758 @ 2.20GHz              | 10       | 1.92%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 10       | 1.92%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 10       | 1.92%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 10       | 1.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 9        | 1.73%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 1.73%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 8        | 1.54%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 8        | 1.54%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 8        | 1.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 7        | 1.34%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 7        | 1.34%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 7        | 1.34%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 7        | 1.34%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 6        | 1.15%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 6        | 1.15%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 6        | 1.15%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 1.15%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 6        | 1.15%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 5        | 0.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 0.96%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 0.96%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 0.96%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 0.96%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.96%   |
| AMD FX-6300 Six-Core Processor              | 5        | 0.96%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 4        | 0.77%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.77%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 4        | 0.77%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 0.77%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.77%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 4        | 0.77%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 4        | 0.77%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.77%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 4        | 0.77%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 3        | 0.58%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 0.58%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.58%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.58%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.58%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.58%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 0.58%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.58%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 3        | 0.58%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 0.58%   |
| Intel Xeon W-1250 CPU @ 3.30GHz             | 2        | 0.38%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 2        | 0.38%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 2        | 0.38%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 0.38%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.38%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 2        | 0.38%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 96       | 18.43%  |
| Intel Core i7           | 91       | 17.47%  |
| AMD Ryzen 5             | 71       | 13.63%  |
| AMD Ryzen 7             | 63       | 12.09%  |
| AMD Ryzen 9             | 33       | 6.33%   |
| Intel Xeon              | 24       | 4.61%   |
| Intel Core i3           | 19       | 3.65%   |
| AMD Ryzen 3             | 18       | 3.45%   |
| Intel Pentium           | 13       | 2.5%    |
| AMD FX                  | 13       | 2.5%    |
| Intel Atom              | 12       | 2.3%    |
| Intel Core i9           | 7        | 1.34%   |
| Intel Celeron           | 7        | 1.34%   |
| AMD Ryzen Threadripper  | 5        | 0.96%   |
| AMD Phenom II X4        | 5        | 0.96%   |
| Other                   | 4        | 0.77%   |
| Intel Core 2 Duo        | 4        | 0.77%   |
| AMD A4                  | 4        | 0.77%   |
| AMD A10                 | 4        | 0.77%   |
| Intel Pentium Dual      | 3        | 0.58%   |
| AMD Athlon 64 X2        | 3        | 0.58%   |
| AMD A6                  | 3        | 0.58%   |
| Intel Pentium Dual-Core | 2        | 0.38%   |
| Intel Core 2 Quad       | 2        | 0.38%   |
| AMD Phenom II X6        | 2        | 0.38%   |
| AMD Athlon II X2        | 2        | 0.38%   |
| AMD A8                  | 2        | 0.38%   |
| Intel Pentium Gold      | 1        | 0.19%   |
| Intel Pentium 4         | 1        | 0.19%   |
| AMD Ryzen 7 PRO         | 1        | 0.19%   |
| AMD Ryzen 5 PRO         | 1        | 0.19%   |
| AMD Phenom              | 1        | 0.19%   |
| AMD E2                  | 1        | 0.19%   |
| AMD Athlon II X4        | 1        | 0.19%   |
| AMD Athlon II X3        | 1        | 0.19%   |
| AMD Athlon              | 1        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 205      | 39.27%  |
| 6       | 110      | 21.07%  |
| 8       | 88       | 16.86%  |
| 2       | 60       | 11.49%  |
| 12      | 24       | 4.6%    |
| 16      | 15       | 2.87%   |
| 3       | 8        | 1.53%   |
| 1       | 7        | 1.34%   |
| 10      | 2        | 0.38%   |
| 32      | 1        | 0.19%   |
| 24      | 1        | 0.19%   |
| Unknown | 1        | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 517      | 99.23%  |
| 2       | 3        | 0.58%   |
| Unknown | 1        | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 349      | 67.12%  |
| 1       | 170      | 32.69%  |
| Unknown | 1        | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 515      | 99.04%  |
| Unknown        | 5        | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 48       | 9.06%   |
| Unknown    | 42       | 7.92%   |
| 0x306c3    | 38       | 7.17%   |
| 0x306a9    | 36       | 6.79%   |
| 0x506e3    | 32       | 6.04%   |
| 0x0800820d | 32       | 6.04%   |
| 0x906ea    | 28       | 5.28%   |
| 0x906e9    | 26       | 4.91%   |
| 0x0a201009 | 21       | 3.96%   |
| 0x0a201016 | 20       | 3.77%   |
| 0x206a7    | 19       | 3.58%   |
| 0x08701013 | 11       | 2.08%   |
| 0x506f1    | 10       | 1.89%   |
| 0x08101016 | 10       | 1.89%   |
| 0x1067a    | 9        | 1.7%    |
| 0xa0653    | 8        | 1.51%   |
| 0x906ec    | 8        | 1.51%   |
| 0x08108109 | 8        | 1.51%   |
| 0x0a50000c | 7        | 1.32%   |
| 0x08001138 | 7        | 1.32%   |
| 0x306f2    | 5        | 0.94%   |
| 0x106e5    | 5        | 0.94%   |
| 0x08001137 | 5        | 0.94%   |
| 0x906ed    | 4        | 0.75%   |
| 0x6fd      | 4        | 0.75%   |
| 0x206c2    | 4        | 0.75%   |
| 0x0810100b | 4        | 0.75%   |
| 0x06003106 | 4        | 0.75%   |
| 0x06000852 | 4        | 0.75%   |
| 0xa0671    | 3        | 0.57%   |
| 0xa0655    | 3        | 0.57%   |
| 0x906eb    | 3        | 0.57%   |
| 0x506c9    | 3        | 0.57%   |
| 0x306e4    | 3        | 0.57%   |
| 0x08108102 | 3        | 0.57%   |
| 0x06001119 | 3        | 0.57%   |
| 0x06000822 | 3        | 0.57%   |
| 0x010000c8 | 3        | 0.57%   |
| 0x010000b6 | 3        | 0.57%   |
| 0x206d7    | 2        | 0.38%   |
| 0x106a5    | 2        | 0.38%   |
| 0x0a201205 | 2        | 0.38%   |
| 0x0700010b | 2        | 0.38%   |
| 0x010000dc | 2        | 0.38%   |
| 0x010000db | 2        | 0.38%   |
| 0xf41      | 1        | 0.19%   |
| 0x806eb    | 1        | 0.19%   |
| 0x706e5    | 1        | 0.19%   |
| 0x706a8    | 1        | 0.19%   |
| 0x706a1    | 1        | 0.19%   |
| 0x506ca    | 1        | 0.19%   |
| 0x50657    | 1        | 0.19%   |
| 0x406f1    | 1        | 0.19%   |
| 0x406c4    | 1        | 0.19%   |
| 0x30678    | 1        | 0.19%   |
| 0x30673    | 1        | 0.19%   |
| 0x20655    | 1        | 0.19%   |
| 0x0a500007 | 1        | 0.19%   |
| 0x08701012 | 1        | 0.19%   |
| 0x08600103 | 1        | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 74       | 14.2%   |
| Zen 2         | 66       | 12.67%  |
| Zen 3         | 51       | 9.79%   |
| Haswell       | 48       | 9.21%   |
| Zen+          | 47       | 9.02%   |
| IvyBridge     | 43       | 8.25%   |
| Skylake       | 35       | 6.72%   |
| Zen           | 28       | 5.37%   |
| SandyBridge   | 24       | 4.61%   |
| Piledriver    | 15       | 2.88%   |
| Goldmont      | 14       | 2.69%   |
| K10           | 12       | 2.3%    |
| CometLake     | 11       | 2.11%   |
| Penryn        | 9        | 1.73%   |
| Nehalem       | 8        | 1.54%   |
| Westmere      | 5        | 0.96%   |
| Steamroller   | 5        | 0.96%   |
| K8 Hammer     | 4        | 0.77%   |
| Core          | 4        | 0.77%   |
| Silvermont    | 3        | 0.58%   |
| Icelake       | 3        | 0.58%   |
| Jaguar        | 2        | 0.38%   |
| Goldmont plus | 2        | 0.38%   |
| Excavator     | 2        | 0.38%   |
| Bulldozer     | 2        | 0.38%   |
| NetBurst      | 1        | 0.19%   |
| K10 Llano     | 1        | 0.19%   |
| Broadwell     | 1        | 0.19%   |
| Unknown       | 1        | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 256      | 45.63%  |
| AMD               | 171      | 30.48%  |
| Intel             | 121      | 21.57%  |
| ASPEED Technology | 12       | 2.14%   |
| ATI Technologies  | 1        | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 46       | 8.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 21       | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 3.32%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 2.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 14       | 2.44%   |
| Intel HD Graphics 630                                                       | 14       | 2.44%   |
| Intel HD Graphics 530                                                       | 14       | 2.44%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 14       | 2.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13       | 2.27%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13       | 2.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 12       | 2.09%   |
| ASPEED Technology ASPEED Graphics Family                                    | 12       | 2.09%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 2.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 11       | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 10       | 1.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 1.75%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 1.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 10       | 1.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 9        | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 9        | 1.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 1.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 9        | 1.57%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 1.22%   |
| AMD Cezanne                                                                 | 7        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 6        | 1.05%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 6        | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 5        | 0.87%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 5        | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 0.87%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 5        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 0.87%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.87%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.7%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.7%    |
| Nvidia GK104 [GeForce GTX 770]                                              | 4        | 0.7%    |
| Intel HD Graphics 500                                                       | 4        | 0.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.7%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 4        | 0.7%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.7%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 4        | 0.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 4        | 0.7%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.7%    |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3        | 0.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 0.52%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 0.52%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 0.52%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.52%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 3        | 0.52%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 3        | 0.52%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 3        | 0.52%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 3        | 0.52%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 0.35%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.35%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.35%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 2        | 0.35%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 2        | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 244      | 46.21%  |
| 1 x AMD        | 165      | 31.25%  |
| 1 x Intel      | 85       | 16.1%   |
| 1 x ASPEED     | 12       | 2.27%   |
| Intel + Nvidia | 11       | 2.08%   |
| 2 x AMD        | 4        | 0.76%   |
| Other          | 3        | 0.57%   |
| Intel + AMD    | 2        | 0.38%   |
| 2 x Nvidia     | 1        | 0.19%   |
| AMD + Nvidia   | 1        | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 319      | 60.19%  |
| Proprietary | 182      | 34.34%  |
| Unknown     | 29       | 5.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 164      | 30.48%  |
| 7.01-8.0   | 94       | 17.47%  |
| 3.01-4.0   | 73       | 13.57%  |
| 1.01-2.0   | 67       | 12.45%  |
| 8.01-16.0  | 38       | 7.06%   |
| 5.01-6.0   | 36       | 6.69%   |
| 0.51-1.0   | 28       | 5.2%    |
| 0.01-0.5   | 28       | 5.2%    |
| 2.01-3.0   | 9        | 1.67%   |
| 16.01-24.0 | 1        | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 95       | 15.7%   |
| Dell                 | 79       | 13.06%  |
| Goldstar             | 76       | 12.56%  |
| Acer                 | 47       | 7.77%   |
| Ancor Communications | 40       | 6.61%   |
| BenQ                 | 38       | 6.28%   |
| AOC                  | 38       | 6.28%   |
| Hewlett-Packard      | 26       | 4.3%    |
| Philips              | 17       | 2.81%   |
| ASUSTek Computer     | 15       | 2.48%   |
| ViewSonic            | 13       | 2.15%   |
| Iiyama               | 10       | 1.65%   |
| Unknown              | 9        | 1.49%   |
| Vizio                | 8        | 1.32%   |
| Eizo                 | 8        | 1.32%   |
| Sony                 | 7        | 1.16%   |
| MSI                  | 6        | 0.99%   |
| Toshiba              | 5        | 0.83%   |
| Sceptre Tech         | 5        | 0.83%   |
| Gigabyte Technology  | 5        | 0.83%   |
| Vestel Elektronik    | 4        | 0.66%   |
| Panasonic            | 4        | 0.66%   |
| Lenovo               | 3        | 0.5%    |
| VIZ                  | 2        | 0.33%   |
| VIE                  | 2        | 0.33%   |
| UTV                  | 2        | 0.33%   |
| Sharp                | 2        | 0.33%   |
| ONN                  | 2        | 0.33%   |
| NEC Computers        | 2        | 0.33%   |
| MStar                | 2        | 0.33%   |
| MiTAC                | 2        | 0.33%   |
| LG Electronics       | 2        | 0.33%   |
| HannStar             | 2        | 0.33%   |
| Denver               | 2        | 0.33%   |
| Compal               | 2        | 0.33%   |
| ___                  | 1        | 0.17%   |
| Unknown (XXX)        | 1        | 0.17%   |
| SUNNY                | 1        | 0.17%   |
| RCA                  | 1        | 0.17%   |
| PRISM+               | 1        | 0.17%   |
| Pixio                | 1        | 0.17%   |
| PEGA                 | 1        | 0.17%   |
| Onkyo                | 1        | 0.17%   |
| OEM                  | 1        | 0.17%   |
| Nixeus               | 1        | 0.17%   |
| Monoprice            | 1        | 0.17%   |
| Mitsubishi           | 1        | 0.17%   |
| Mi                   | 1        | 0.17%   |
| INS                  | 1        | 0.17%   |
| Impression           | 1        | 0.17%   |
| HXF                  | 1        | 0.17%   |
| Huion                | 1        | 0.17%   |
| HPN                  | 1        | 0.17%   |
| Gateway              | 1        | 0.17%   |
| Fujitsu Siemens      | 1        | 0.17%   |
| DTV                  | 1        | 0.17%   |
| Belinea              | 1        | 0.17%   |
| AOpen                | 1        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9        | 1.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 5        | 0.77%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5        | 0.77%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                         | 4        | 0.62%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 4        | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4        | 0.62%   |
| BenQ GC2870 BNQ78DD 1920x1080 621x341mm 27.9-inch                     | 4        | 0.62%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 4        | 0.62%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 4        | 0.62%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 0.46%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.46%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.46%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 3        | 0.46%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 3        | 0.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3        | 0.46%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 3        | 0.46%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                 | 3        | 0.46%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3        | 0.46%   |
| Dell S2716DG DELA0D1 2560x1440 598x336mm 27.0-inch                    | 3        | 0.46%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 3        | 0.46%   |
| AOC Q2963 AOC2963 2560x1080 670x280mm 28.6-inch                       | 3        | 0.46%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 3        | 0.46%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 3        | 0.46%   |
| Ancor Communications VE248 ACI2494 1920x1080 530x300mm 24.0-inch      | 3        | 0.46%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 3        | 0.46%   |
| Acer VG271 ACR06E2 1920x1080 598x336mm 27.0-inch                      | 3        | 0.46%   |
| Vizio D43n-E1 VIZ1009 1920x1080 953x543mm 43.2-inch                   | 2        | 0.31%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                   | 2        | 0.31%   |
| Sony TV SNYE903 1920x1080                                             | 2        | 0.31%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM0657 1920x1080                      | 2        | 0.31%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2        | 0.31%   |
| Samsung Electronics S23B350 SAM08D6 1920x1080 510x287mm 23.0-inch     | 2        | 0.31%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch     | 2        | 0.31%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2        | 0.31%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 820x460mm 37.0-inch | 2        | 0.31%   |
| Samsung Electronics LCD Monitor SAM01FF 1360x768 885x498mm 40.0-inch  | 2        | 0.31%   |
| Samsung Electronics C49RG9x SAM0F99 3840x1080 1193x336mm 48.8-inch    | 2        | 0.31%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch     | 2        | 0.31%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 2        | 0.31%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2        | 0.31%   |
| MSI Optix MAG24C MSI1462 1920x1080 520x290mm 23.4-inch                | 2        | 0.31%   |
| MiTAC DSGi TV SZM0308 1920x540 708x398mm 32.0-inch                    | 2        | 0.31%   |
| Iiyama PL2792Q IVM6637 2560x1440 597x336mm 27.0-inch                  | 2        | 0.31%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 2        | 0.31%   |
| Hewlett-Packard w2408 HWP26CF 1920x1200 518x324mm 24.1-inch           | 2        | 0.31%   |
| Hewlett-Packard 27q HPN3565 2560x1440 597x336mm 27.0-inch             | 2        | 0.31%   |
| Hewlett-Packard 27ea HPN3395 1920x1080 527x296mm 23.8-inch            | 2        | 0.31%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch              | 2        | 0.31%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.31%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 2        | 0.31%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.31%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.31%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2        | 0.31%   |
| Goldstar 24MP56 GSM5A56 1920x1080 510x290mm 23.1-inch                 | 2        | 0.31%   |
| Eizo EV2450 ENC2530 1920x1080 528x297mm 23.9-inch                     | 2        | 0.31%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2        | 0.31%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                    | 2        | 0.31%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                     | 2        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 275      | 48.25%  |
| 2560x1440 (QHD)    | 81       | 14.21%  |
| 3840x2160 (4K)     | 60       | 10.53%  |
| 1680x1050 (WSXGA+) | 21       | 3.68%   |
| 1280x1024 (SXGA)   | 20       | 3.51%   |
| 2560x1080          | 17       | 2.98%   |
| 1366x768 (WXGA)    | 17       | 2.98%   |
| 3440x1440          | 15       | 2.63%   |
| 1920x1200 (WUXGA)  | 14       | 2.46%   |
| 1440x900 (WXGA+)   | 12       | 2.11%   |
| 1600x900 (HD+)     | 8        | 1.4%    |
| 1360x768           | 8        | 1.4%    |
| 3840x1080          | 6        | 1.05%   |
| 1920x540           | 5        | 0.88%   |
| Unknown            | 3        | 0.53%   |
| 1600x1200          | 2        | 0.35%   |
| 5760x2160          | 1        | 0.18%   |
| 3840x1600          | 1        | 0.18%   |
| 3840x1200          | 1        | 0.18%   |
| 2288x1287          | 1        | 0.18%   |
| 2048x1152          | 1        | 0.18%   |
| 1400x1050          | 1        | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 118      | 19.7%   |
| 24      | 97       | 16.19%  |
| 23      | 67       | 11.19%  |
| 21      | 67       | 11.19%  |
| 31      | 40       | 6.68%   |
| 34      | 25       | 4.17%   |
| Unknown | 24       | 4.01%   |
| 19      | 21       | 3.51%   |
| 22      | 15       | 2.5%    |
| 17      | 15       | 2.5%    |
| 18      | 14       | 2.34%   |
| 84      | 12       | 2%      |
| 20      | 12       | 2%      |
| 72      | 9        | 1.5%    |
| 54      | 7        | 1.17%   |
| 25      | 7        | 1.17%   |
| 32      | 5        | 0.83%   |
| 28      | 5        | 0.83%   |
| 26      | 5        | 0.83%   |
| 40      | 4        | 0.67%   |
| 52      | 3        | 0.5%    |
| 48      | 3        | 0.5%    |
| 46      | 3        | 0.5%    |
| 39      | 3        | 0.5%    |
| 55      | 2        | 0.33%   |
| 49      | 2        | 0.33%   |
| 43      | 2        | 0.33%   |
| 35      | 2        | 0.33%   |
| 142     | 1        | 0.17%   |
| 74      | 1        | 0.17%   |
| 42      | 1        | 0.17%   |
| 37      | 1        | 0.17%   |
| 36      | 1        | 0.17%   |
| 33      | 1        | 0.17%   |
| 29      | 1        | 0.17%   |
| 16      | 1        | 0.17%   |
| 15      | 1        | 0.17%   |
| 14      | 1        | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 249      | 44.07%  |
| 401-500        | 117      | 20.71%  |
| 601-700        | 63       | 11.15%  |
| 701-800        | 32       | 5.66%   |
| Unknown        | 24       | 4.25%   |
| 1501-2000      | 21       | 3.72%   |
| 1001-1500      | 20       | 3.54%   |
| 301-350        | 17       | 3.01%   |
| 801-900        | 10       | 1.77%   |
| 351-400        | 7        | 1.24%   |
| 901-1000       | 3        | 0.53%   |
| More than 2000 | 1        | 0.18%   |
| 201-300        | 1        | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 381      | 72.71%  |
| 16/10   | 57       | 10.88%  |
| 21/9    | 34       | 6.49%   |
| 5/4     | 21       | 4.01%   |
| Unknown | 19       | 3.63%   |
| 4/3     | 6        | 1.15%   |
| 32/9    | 4        | 0.76%   |
| 3/2     | 1        | 0.19%   |
| 1.00    | 1        | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 199      | 34.43%  |
| 301-350        | 120      | 20.76%  |
| 351-500        | 71       | 12.28%  |
| 151-200        | 43       | 7.44%   |
| 251-300        | 37       | 6.4%    |
| More than 1000 | 34       | 5.88%   |
| 141-150        | 28       | 4.84%   |
| Unknown        | 24       | 4.15%   |
| 501-1000       | 19       | 3.29%   |
| 101-110        | 2        | 0.35%   |
| 131-140        | 1        | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 320      | 59.26%  |
| 101-120 | 139      | 25.74%  |
| 1-50    | 27       | 5%      |
| Unknown | 24       | 4.44%   |
| 121-160 | 21       | 3.89%   |
| 161-240 | 9        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 343      | 64.72%  |
| 2     | 133      | 25.09%  |
| 0     | 36       | 6.79%   |
| 3     | 16       | 3.02%   |
| 4     | 2        | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 313      | 43.53%  |
| Intel                           | 261      | 36.3%   |
| Qualcomm Atheros                | 41       | 5.7%    |
| Broadcom                        | 24       | 3.34%   |
| Ralink Technology               | 15       | 2.09%   |
| TP-Link                         | 9        | 1.25%   |
| Microsoft                       | 6        | 0.83%   |
| Nvidia                          | 5        | 0.7%    |
| Marvell Technology Group        | 4        | 0.56%   |
| D-Link System                   | 4        | 0.56%   |
| Aquantia                        | 4        | 0.56%   |
| Broadcom Limited                | 3        | 0.42%   |
| ASIX Electronics                | 3        | 0.42%   |
| Qualcomm Atheros Communications | 2        | 0.28%   |
| Oculus VR                       | 2        | 0.28%   |
| Insyde Software                 | 2        | 0.28%   |
| D-Link                          | 2        | 0.28%   |
| Tenda                           | 1        | 0.14%   |
| Solarflare Communications       | 1        | 0.14%   |
| Seeed Technology                | 1        | 0.14%   |
| Ralink                          | 1        | 0.14%   |
| Qualcomm                        | 1        | 0.14%   |
| NetGear                         | 1        | 0.14%   |
| Motorola                        | 1        | 0.14%   |
| Microchip Technology            | 1        | 0.14%   |
| Lenovo                          | 1        | 0.14%   |
| InterBiometrics                 | 1        | 0.14%   |
| IMC Networks                    | 1        | 0.14%   |
| ICS Advent                      | 1        | 0.14%   |
| Emulex                          | 1        | 0.14%   |
| Edimax Technology               | 1        | 0.14%   |
| DisplayLink                     | 1        | 0.14%   |
| CyberTAN Technology             | 1        | 0.14%   |
| ASUSTek Computer                | 1        | 0.14%   |
| Arduino SA                      | 1        | 0.14%   |
| 3Com                            | 1        | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 254      | 30.38%  |
| Intel I211 Gigabit Network Connection                             | 69       | 8.25%   |
| Intel Wi-Fi 6 AX200                                               | 54       | 6.46%   |
| Intel Ethernet Connection (2) I219-V                              | 34       | 4.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32       | 3.83%   |
| Intel Ethernet Connection (7) I219-V                              | 17       | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 2.03%   |
| Intel Wireless-AC 9260                                            | 15       | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15       | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 12       | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 1.32%   |
| Intel Ethernet Connection X553 1GbE                               | 10       | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 9        | 1.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 9        | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 8        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 0.96%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7        | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6        | 0.72%   |
| Intel Wireless 3165                                               | 6        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 5        | 0.6%    |
| Realtek 802.11ac NIC                                              | 5        | 0.6%    |
| Intel Wireless 8265 / 8275                                        | 5        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 5        | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 0.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4        | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4        | 0.48%   |
| Intel Wireless 7260                                               | 4        | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4        | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3        | 0.36%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3        | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.36%   |
| Microsoft XBOX ACC                                                | 3        | 0.36%   |
| Intel Wireless 8260                                               | 3        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.36%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3        | 0.36%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 0.36%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.24%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.24%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 2        | 0.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.24%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.24%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.24%   |
| Oculus VR Rift S                                                  | 2        | 0.24%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 116      | 48.54%  |
| Realtek Semiconductor           | 41       | 17.15%  |
| Qualcomm Atheros                | 20       | 8.37%   |
| Broadcom                        | 18       | 7.53%   |
| Ralink Technology               | 15       | 6.28%   |
| TP-Link                         | 9        | 3.77%   |
| Microsoft                       | 6        | 2.51%   |
| Qualcomm Atheros Communications | 2        | 0.84%   |
| D-Link System                   | 2        | 0.84%   |
| D-Link                          | 2        | 0.84%   |
| Tenda                           | 1        | 0.42%   |
| Ralink                          | 1        | 0.42%   |
| NetGear                         | 1        | 0.42%   |
| IMC Networks                    | 1        | 0.42%   |
| Edimax Technology               | 1        | 0.42%   |
| CyberTAN Technology             | 1        | 0.42%   |
| Broadcom Limited                | 1        | 0.42%   |
| ASUSTek Computer                | 1        | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 54       | 22.13%  |
| Intel Wireless-AC 9260                                                        | 15       | 6.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 15       | 6.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 9        | 3.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 9        | 3.69%   |
| Ralink MT7601U Wireless Adapter                                               | 7        | 2.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7        | 2.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 6        | 2.46%   |
| Intel Wireless 3165                                                           | 6        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 5        | 2.05%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 5        | 2.05%   |
| Realtek 802.11ac NIC                                                          | 5        | 2.05%   |
| Intel Wireless 8265 / 8275                                                    | 5        | 2.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 4        | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 4        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4        | 1.64%   |
| Intel Wireless 7260                                                           | 4        | 1.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4        | 1.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 3        | 1.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 3        | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3        | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 1.23%   |
| Microsoft XBOX ACC                                                            | 3        | 1.23%   |
| Intel Wireless 8260                                                           | 3        | 1.23%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 3        | 1.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 0.82%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2        | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 2        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 0.82%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2        | 0.82%   |
| Microsoft Wireless XBox Controller Dongle                                     | 2        | 0.82%   |
| Intel Wireless 7265                                                           | 2        | 0.82%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1        | 0.41%   |
| TP-Link Archer T4UH wireless Realtek 8812AU                                   | 1        | 0.41%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.41%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.41%   |
| Tenda U12                                                                     | 1        | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                           | 1        | 0.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.41%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1        | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1        | 0.41%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 1        | 0.41%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.41%   |
| Ralink RT3072 Wireless Adapter                                                | 1        | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1        | 0.41%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 0.41%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1        | 0.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.41%   |
| NetGear WNDA3100v2 802.11abgn [Broadcom BCM4323]                              | 1        | 0.41%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 0.41%   |
| Intel Wireless 3160                                                           | 1        | 0.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 0.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1        | 0.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 0.41%   |
| Intel Centrino Advanced-N 6200                                                | 1        | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 299      | 53.58%  |
| Intel                     | 200      | 35.84%  |
| Qualcomm Atheros          | 23       | 4.12%   |
| Broadcom                  | 7        | 1.25%   |
| Nvidia                    | 5        | 0.9%    |
| Marvell Technology Group  | 4        | 0.72%   |
| Aquantia                  | 4        | 0.72%   |
| ASIX Electronics          | 3        | 0.54%   |
| Insyde Software           | 2        | 0.36%   |
| D-Link System             | 2        | 0.36%   |
| Broadcom Limited          | 2        | 0.36%   |
| Solarflare Communications | 1        | 0.18%   |
| Qualcomm                  | 1        | 0.18%   |
| Lenovo                    | 1        | 0.18%   |
| ICS Advent                | 1        | 0.18%   |
| Emulex                    | 1        | 0.18%   |
| DisplayLink               | 1        | 0.18%   |
| 3Com                      | 1        | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 254      | 43.42%  |
| Intel I211 Gigabit Network Connection                             | 69       | 11.79%  |
| Intel Ethernet Connection (2) I219-V                              | 34       | 5.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32       | 5.47%   |
| Intel Ethernet Connection (7) I219-V                              | 17       | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17       | 2.91%   |
| Intel Ethernet Controller I225-V                                  | 12       | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 1.88%   |
| Intel Ethernet Connection X553 1GbE                               | 10       | 1.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8        | 1.37%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.37%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.51%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.34%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.34%   |
| Intel Ethernet Controller X550                                    | 2        | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.34%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.34%   |
| Intel Ethernet Connection (11) I219-LM                            | 2        | 0.34%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.34%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2        | 0.34%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.34%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2        | 0.34%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.17%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.17%   |
| Realtek RT8139 (B/C) Cardbus Fast Ethernet Adapter                | 1        | 0.17%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.17%   |
| Qualcomm POCO F2 Pro                                              | 1        | 0.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.17%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.17%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.17%   |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.17%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.17%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.17%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.17%   |
| Lenovo ThinkPad Lan                                               | 1        | 0.17%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.17%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.17%   |
| Intel Ethernet Connection (10) I219-V                             | 1        | 0.17%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.17%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.17%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.17%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 0.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 518      | 68.7%   |
| WiFi     | 229      | 30.37%  |
| Modem    | 7        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 432      | 80.45%  |
| WiFi     | 105      | 19.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 302      | 57.74%  |
| 2     | 173      | 33.08%  |
| 3     | 29       | 5.54%   |
| 4     | 16       | 3.06%   |
| 0     | 2        | 0.38%   |
| 9     | 1        | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 416      | 78.49%  |
| Yes  | 114      | 21.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 111      | 49.78%  |
| Cambridge Silicon Radio         | 47       | 21.08%  |
| ASUSTek Computer                | 18       | 8.07%   |
| Realtek Semiconductor           | 13       | 5.83%   |
| Broadcom                        | 10       | 4.48%   |
| Qualcomm Atheros Communications | 9        | 4.04%   |
| Apple                           | 5        | 2.24%   |
| Belkin Components               | 3        | 1.35%   |
| IMC Networks                    | 2        | 0.9%    |
| Edimax Technology               | 2        | 0.9%    |
| Lite-On Technology              | 1        | 0.45%   |
| HTC (High Tech Computer)        | 1        | 0.45%   |
| Dynex                           | 1        | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 53       | 23.66%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 47       | 20.98%  |
| Intel Bluetooth wireless interface                                   | 20       | 8.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 15       | 6.7%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 14       | 6.25%   |
| Realtek Bluetooth Radio                                              | 8        | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8        | 3.57%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7        | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 7        | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 3.13%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4        | 1.79%   |
| ASUS ASUS USB-BT500                                                  | 4        | 1.79%   |
| Apple Bluetooth USB Host Controller                                  | 4        | 1.79%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3        | 1.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.89%   |
| Edimax Bluetooth Device                                              | 2        | 0.89%   |
| Broadcom HP Portable Bumble Bee                                      | 2        | 0.89%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 0.89%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 0.89%   |
| ASUS Bluetooth Adapter                                               | 2        | 0.89%   |
| ASUS BCM20702A0                                                      | 2        | 0.89%   |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.45%   |
| Lite-On Bluetooth Device                                             | 1        | 0.45%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.45%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.45%   |
| IMC Networks Bluetooth Device                                        | 1        | 0.45%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.45%   |
| Dynex BCM20702A0                                                     | 1        | 0.45%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 1        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 281      | 27.9%   |
| Intel                                | 267      | 26.51%  |
| Nvidia                               | 250      | 24.83%  |
| C-Media Electronics                  | 34       | 3.38%   |
| Logitech                             | 19       | 1.89%   |
| Kingston Technology                  | 13       | 1.29%   |
| Texas Instruments                    | 11       | 1.09%   |
| Focusrite-Novation                   | 10       | 0.99%   |
| JMTek                                | 9        | 0.89%   |
| Creative Technology                  | 9        | 0.89%   |
| Corsair                              | 8        | 0.79%   |
| SteelSeries ApS                      | 6        | 0.6%    |
| RODE Microphones                     | 6        | 0.6%    |
| Razer USA                            | 6        | 0.6%    |
| Creative Labs                        | 6        | 0.6%    |
| Blue Microphones                     | 5        | 0.5%    |
| Sennheiser Communications            | 4        | 0.4%    |
| SAVITECH                             | 4        | 0.4%    |
| Yamaha                               | 3        | 0.3%    |
| Thesycon Systemsoftware & Consulting | 3        | 0.3%    |
| Samson Technologies                  | 3        | 0.3%    |
| PreSonus Audio Electronics           | 3        | 0.3%    |
| Generalplus Technology               | 3        | 0.3%    |
| VIA Technologies                     | 2        | 0.2%    |
| Realtek Semiconductor                | 2        | 0.2%    |
| Project                              | 2        | 0.2%    |
| Plantronics                          | 2        | 0.2%    |
| Native Instruments                   | 2        | 0.2%    |
| FIFINE Microphones                   | 2        | 0.2%    |
| Cambridge Silicon Radio              | 2        | 0.2%    |
| XMOS                                 | 1        | 0.1%    |
| Unknown                              | 1        | 0.1%    |
| Trust                                | 1        | 0.1%    |
| Tdlasunnic                           | 1        | 0.1%    |
| Sony                                 | 1        | 0.1%    |
| SM950 Microphone                     | 1        | 0.1%    |
| RadioShack (Tandy)                   | 1        | 0.1%    |
| Philips (or NXP)                     | 1        | 0.1%    |
| Microfone Condensador Avalanche      | 1        | 0.1%    |
| Medeli Electronics                   | 1        | 0.1%    |
| Mark of the Unicorn                  | 1        | 0.1%    |
| M-Audio                              | 1        | 0.1%    |
| Lautsprecher Teufel                  | 1        | 0.1%    |
| GYROCOM C&C                          | 1        | 0.1%    |
| GN Netcom                            | 1        | 0.1%    |
| Giga-Byte Technology                 | 1        | 0.1%    |
| DigiTech                             | 1        | 0.1%    |
| Dell                                 | 1        | 0.1%    |
| DCMT Technology                      | 1        | 0.1%    |
| Cooler Master                        | 1        | 0.1%    |
| BEHRINGER International              | 1        | 0.1%    |
| AudioQuest                           | 1        | 0.1%    |
| ATI Technologies                     | 1        | 0.1%    |
| ASUSTek Computer                     | 1        | 0.1%    |
| Astro Gaming                         | 1        | 0.1%    |
| Asahi Kasei Microsystems             | 1        | 0.1%    |
| Arturia                              | 1        | 0.1%    |
| Apple                                | 1        | 0.1%    |
| Antlion Audio                        | 1        | 0.1%    |
| Afatech                              | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 104      | 9.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 45       | 3.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 45       | 3.9%    |
| Intel 200 Series PCH HD Audio                                              | 41       | 3.56%   |
| AMD Family 17h/19h HD Audio Controller                                     | 38       | 3.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 37       | 3.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35       | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32       | 2.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 28       | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 28       | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28       | 2.43%   |
| Nvidia TU116 High Definition Audio Controller                              | 27       | 2.34%   |
| Nvidia GP106 High Definition Audio Controller                              | 26       | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19       | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16       | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 16       | 1.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 16       | 1.39%   |
| AMD Navi 10 HDMI Audio                                                     | 15       | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 15       | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14       | 1.21%   |
| Nvidia TU104 HD Audio Controller                                           | 13       | 1.13%   |
| Nvidia GP102 HDMI Audio Controller                                         | 13       | 1.13%   |
| Nvidia GM204 High Definition Audio Controller                              | 12       | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                              | 11       | 0.95%   |
| Nvidia GM206 High Definition Audio Controller                              | 11       | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11       | 0.95%   |
| AMD FCH Azalia Controller                                                  | 11       | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10       | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 0.87%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 0.78%   |
| Kingston Technology HyperX 7.1 Audio                                       | 9        | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 0.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9        | 0.78%   |
| Texas Instruments PCM2902 Audio Codec                                      | 8        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 8        | 0.69%   |
| Nvidia GK104 HDMI Audio Controller                                         | 8        | 0.69%   |
| JMTek USB PnP Audio Device                                                 | 8        | 0.69%   |
| Intel Comet Lake PCH-V cAVS                                                | 7        | 0.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.61%   |
| C-Media Electronics USB Audio Device                                       | 7        | 0.61%   |
| RODE Microphones RODE NT-USB                                               | 6        | 0.52%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.52%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.52%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 0.52%   |
| Nvidia GF108 High Definition Audio Controller                              | 5        | 0.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5        | 0.43%   |
| C-Media Electronics Schiit Modi 3                                          | 5        | 0.43%   |
| C-Media Electronics Blue Snowball                                          | 5        | 0.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 5        | 0.43%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 4        | 0.35%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 0.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4        | 0.35%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4        | 0.35%   |
| Blue Microphones Yeti Stereo Microphone                                    | 4        | 0.35%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 4        | 0.35%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver] | 3        | 0.26%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 0.26%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 119      | 21.6%   |
| G.Skill             | 72       | 13.07%  |
| Kingston            | 70       | 12.7%   |
| Crucial             | 61       | 11.07%  |
| Unknown             | 46       | 8.35%   |
| SK hynix            | 45       | 8.17%   |
| Samsung Electronics | 35       | 6.35%   |
| Micron Technology   | 19       | 3.45%   |
| A-DATA Technology   | 16       | 2.9%    |
| Team                | 15       | 2.72%   |
| Patriot             | 8        | 1.45%   |
| Nanya Technology    | 6        | 1.09%   |
| Ramaxel Technology  | 5        | 0.91%   |
| Elpida              | 4        | 0.73%   |
| Unknown             | 4        | 0.73%   |
| Unknown (ABCD)      | 2        | 0.36%   |
| Transcend           | 2        | 0.36%   |
| Silicon Power       | 2        | 0.36%   |
| Kingmax             | 2        | 0.36%   |
| Goldkey             | 2        | 0.36%   |
| GeIL                | 2        | 0.36%   |
| Unifosa             | 1        | 0.18%   |
| Smart               | 1        | 0.18%   |
| S                   | 1        | 0.18%   |
| PNY                 | 1        | 0.18%   |
| Neo Forza           | 1        | 0.18%   |
| Lexar Co Limited    | 1        | 0.18%   |
| Lexar               | 1        | 0.18%   |
| Innodisk            | 1        | 0.18%   |
| EVGA                | 1        | 0.18%   |
| Avant               | 1        | 0.18%   |
| Atermiter           | 1        | 0.18%   |
| ASint Technology    | 1        | 0.18%   |
| Apacer              | 1        | 0.18%   |
| AMD                 | 1        | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 11       | 1.83%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 11       | 1.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s       | 11       | 1.83%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s          | 10       | 1.67%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 5        | 0.83%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 5        | 0.83%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 5        | 0.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 5        | 0.83%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 5        | 0.83%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 5        | 0.83%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 5        | 0.83%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s          | 5        | 0.83%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 4        | 0.67%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s              | 4        | 0.67%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 4        | 0.67%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s         | 4        | 0.67%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s            | 4        | 0.67%   |
| Unknown                                                        | 4        | 0.67%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 0.5%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 3        | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3        | 0.5%    |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 3        | 0.5%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s             | 3        | 0.5%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3        | 0.5%    |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 3        | 0.5%    |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s            | 3        | 0.5%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 3        | 0.5%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s          | 3        | 0.5%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s         | 3        | 0.5%    |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s            | 3        | 0.5%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 3        | 0.5%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 3        | 0.5%    |
| Corsair RAM CMZ4GX3M1A1600C9 4096MB DIMM DDR3 1600MT/s         | 3        | 0.5%    |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s         | 3        | 0.5%    |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 3        | 0.5%    |
| Corsair RAM CMK16GX4M2A2400C14 8GB DIMM DDR4 2800MT/s          | 3        | 0.5%    |
| Unknown RAM Module 4GB DIMM SDRAM                              | 2        | 0.33%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                     | 2        | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 0.33%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s             | 2        | 0.33%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s             | 2        | 0.33%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s            | 2        | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2        | 0.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.33%   |
| SK hynix RAM HMAA4GU7CJR8N-XN 32GB DIMM DDR4 3200MT/s          | 2        | 0.33%   |
| SK hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s           | 2        | 0.33%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8192MB DIMM DDR4 2667MT/s        | 2        | 0.33%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s        | 2        | 0.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s            | 2        | 0.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 2        | 0.33%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s            | 2        | 0.33%   |
| Samsung RAM M378B1G73EB0-YK0 8192MB DIMM DDR3 1600MT/s         | 2        | 0.33%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s            | 2        | 0.33%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s         | 2        | 0.33%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                | 2        | 0.33%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 2        | 0.33%   |
| Patriot RAM 3000 C16 Series 8192MB DIMM DDR4 3200MT/s          | 2        | 0.33%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 2        | 0.33%   |
| Micron RAM 16ATF1G64AZ-2G3A2 8GB DIMM DDR4 2400MT/s            | 2        | 0.33%   |
| Kingston RAM KY7N41-MIE 8192MB DIMM DDR4 2666MT/s              | 2        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 307      | 63.56%  |
| DDR3    | 133      | 27.54%  |
| Unknown | 22       | 4.55%   |
| SDRAM   | 8        | 1.66%   |
| DDR2    | 8        | 1.66%   |
| DDR     | 3        | 0.62%   |
| LPDDR4  | 2        | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 456      | 95.6%   |
| SODIMM | 21       | 4.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 245      | 46.58%  |
| 16384 | 117      | 22.24%  |
| 4096  | 105      | 19.96%  |
| 2048  | 35       | 6.65%   |
| 32768 | 17       | 3.23%   |
| 1024  | 6        | 1.14%   |
| 16    | 1        | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 87       | 16.11%  |
| 1600    | 87       | 16.11%  |
| 2400    | 50       | 9.26%   |
| 3600    | 48       | 8.89%   |
| 1333    | 47       | 8.7%    |
| 2667    | 29       | 5.37%   |
| 3466    | 23       | 4.26%   |
| 2133    | 20       | 3.7%    |
| 3000    | 15       | 2.78%   |
| 1867    | 13       | 2.41%   |
| 3733    | 12       | 2.22%   |
| 2933    | 12       | 2.22%   |
| 2800    | 9        | 1.67%   |
| 2666    | 9        | 1.67%   |
| 800     | 9        | 1.67%   |
| 3400    | 7        | 1.3%    |
| 667     | 7        | 1.3%    |
| 1866    | 5        | 0.93%   |
| 3800    | 4        | 0.74%   |
| 1800    | 4        | 0.74%   |
| 3866    | 3        | 0.56%   |
| 3266    | 3        | 0.56%   |
| 1067    | 3        | 0.56%   |
| 1066    | 3        | 0.56%   |
| Unknown | 3        | 0.56%   |
| 3533    | 2        | 0.37%   |
| 3334    | 2        | 0.37%   |
| 3333    | 2        | 0.37%   |
| 3067    | 2        | 0.37%   |
| 2934    | 2        | 0.37%   |
| 2465    | 2        | 0.37%   |
| 2200    | 2        | 0.37%   |
| 533     | 2        | 0.37%   |
| 52217   | 1        | 0.19%   |
| 4333    | 1        | 0.19%   |
| 3151    | 1        | 0.19%   |
| 3100    | 1        | 0.19%   |
| 3066    | 1        | 0.19%   |
| 3007    | 1        | 0.19%   |
| 2733    | 1        | 0.19%   |
| 2197    | 1        | 0.19%   |
| 2048    | 1        | 0.19%   |
| 2000    | 1        | 0.19%   |
| 400     | 1        | 0.19%   |
| 333     | 1        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 12       | 50%     |
| Brother Industries  | 10       | 41.67%  |
| Samsung Electronics | 1        | 4.17%   |
| Dymo-CoStar         | 1        | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| HP DeskJet 2620 All-in-One Printer     | 2        | 8.33%   |
| Brother Printer                        | 2        | 8.33%   |
| Samsung SCX-3400 Series                | 1        | 4.17%   |
| HP OfficeJet Pro 6960                  | 1        | 4.17%   |
| HP OfficeJet 5200 series               | 1        | 4.17%   |
| HP OfficeJet 4650 series               | 1        | 4.17%   |
| HP LaserJet Professional P1102w        | 1        | 4.17%   |
| HP LaserJet P1005                      | 1        | 4.17%   |
| HP LaserJet M203-M206                  | 1        | 4.17%   |
| HP ENVY 4500 series                    | 1        | 4.17%   |
| HP Deskjet 4640 series                 | 1        | 4.17%   |
| HP DeskJet 2700 series                 | 1        | 4.17%   |
| HP Deskjet 1050 J410                   | 1        | 4.17%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 4.17%   |
| Brother MFC-L3750CDW                   | 1        | 4.17%   |
| Brother MFC-J6545DW                    | 1        | 4.17%   |
| Brother MFC-J497DW                     | 1        | 4.17%   |
| Brother MFC-J485DW                     | 1        | 4.17%   |
| Brother MFC-J450DW                     | 1        | 4.17%   |
| Brother HL-3140CW series               | 1        | 4.17%   |
| Brother DCP-7055 scanner/printer       | 1        | 4.17%   |
| Brother DCP-1610W                      | 1        | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 2        | 50%     |
| Hewlett-Packard | 2        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1        | 25%     |
| HP ScanJet 2400c                                        | 1        | 25%     |
| HP ScanJet 2200c                                        | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech                                          | 60       | 47.24%  |
| Microdia                                          | 9        | 7.09%   |
| Microsoft                                         | 7        | 5.51%   |
| Sunplus Innovation Technology                     | 6        | 4.72%   |
| KYE Systems (Mouse Systems)                       | 4        | 3.15%   |
| Hewlett-Packard                                   | 4        | 3.15%   |
| Razer USA                                         | 3        | 2.36%   |
| GEMBIRD                                           | 3        | 2.36%   |
| Creative Technology                               | 3        | 2.36%   |
| Apple                                             | 3        | 2.36%   |
| Ruision                                           | 2        | 1.57%   |
| Realtek Semiconductor                             | 2        | 1.57%   |
| Generalplus Technology                            | 2        | 1.57%   |
| Z-Star Microelectronics                           | 1        | 0.79%   |
| WaveRider Communications                          | 1        | 0.79%   |
| Unknown                                           | 1        | 0.79%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1        | 0.79%   |
| Samsung Electronics                               | 1        | 0.79%   |
| OmniVision Technologies                           | 1        | 0.79%   |
| MacroSilicon                                      | 1        | 0.79%   |
| Lenovo                                            | 1        | 0.79%   |
| Jeilin Technology                                 | 1        | 0.79%   |
| Huawei Technologies                               | 1        | 0.79%   |
| Google                                            | 1        | 0.79%   |
| Chicony Electronics                               | 1        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink)            | 1        | 0.79%   |
| AVerMedia Technologies                            | 1        | 0.79%   |
| Aveo Technology                                   | 1        | 0.79%   |
| Arkmicro Technologies                             | 1        | 0.79%   |
| ARC International                                 | 1        | 0.79%   |
| ANYKA                                             | 1        | 0.79%   |
| Anker                                             | 1        | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                 | 15       | 11.81%  |
| Logitech HD Pro Webcam C920                                          | 15       | 11.81%  |
| Logitech C922 Pro Stream Webcam                                      | 6        | 4.72%   |
| Microsoft LifeCam HD-3000                                            | 5        | 3.94%   |
| Logitech Webcam C310                                                 | 4        | 3.15%   |
| Sunplus FHD Camera Microphone                                        | 3        | 2.36%   |
| Razer USA Gaming Webcam [Kiyo]                                       | 3        | 2.36%   |
| Microdia USB 2.0 Camera                                              | 3        | 2.36%   |
| Logitech Webcam C930e                                                | 3        | 2.36%   |
| Logitech Webcam C925e                                                | 3        | 2.36%   |
| Logitech HD Webcam C615                                              | 3        | 2.36%   |
| Logitech C920 PRO HD Webcam                                          | 3        | 2.36%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                           | 3        | 2.36%   |
| HP Webcam HD 2300                                                    | 3        | 2.36%   |
| GEMBIRD USB2.0 PC CAMERA                                             | 3        | 2.36%   |
| Creative Live! Cam Sync HD [VF0770]                                  | 3        | 2.36%   |
| Apple iPhone 5/5C/5S/6/SE                                            | 3        | 2.36%   |
| Sunplus Full HD webcam                                               | 2        | 1.57%   |
| Ruision UVC Camera                                                   | 2        | 1.57%   |
| Microdia Integrated Camera                                           | 2        | 1.57%   |
| Microdia AUKEY PCâW1                                            | 2        | 1.57%   |
| Logitech HD Webcam C910                                              | 2        | 1.57%   |
| Generalplus GENERAL WEBCAM                                           | 2        | 1.57%   |
| Z-Star A4 TECH USB2.0 PC Camera J                                    | 1        | 0.79%   |
| WaveRider USB 2.0 Camera                                             | 1        | 0.79%   |
| Unknown HD camera                                                    | 1        | 0.79%   |
| Sunplus USB 2.0 Camera                                               | 1        | 0.79%   |
| STMicroelectronics Imaging Division (VLSI Vision) STV0680 Camera     | 1        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 1        | 0.79%   |
| Realtek WEB CAMERA M9 Pro                                            | 1        | 0.79%   |
| Realtek FULL HD 1080P Webcam                                         | 1        | 0.79%   |
| OmniVision Monitor Webcam                                            | 1        | 0.79%   |
| Microsoft Xbox NUI Camera                                            | 1        | 0.79%   |
| Microsoft LifeCam Cinema                                             | 1        | 0.79%   |
| Microdia Integrated_Webcam_HD                                        | 1        | 0.79%   |
| Microdia Camera                                                      | 1        | 0.79%   |
| MacroSilicon MiraBox Capture                                         | 1        | 0.79%   |
| Logitech Webcam Pro 9000                                             | 1        | 0.79%   |
| Logitech Webcam C200                                                 | 1        | 0.79%   |
| Logitech Webcam C170                                                 | 1        | 0.79%   |
| Logitech Webcam C110                                                 | 1        | 0.79%   |
| Logitech QuickCam Pro for Notebooks                                  | 1        | 0.79%   |
| Logitech HD Webcam B910                                              | 1        | 0.79%   |
| Lenovo 500 RGB Camera                                                | 1        | 0.79%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320                       | 1        | 0.79%   |
| Jeilin Kodak S101 Webcam                                             | 1        | 0.79%   |
| Huawei UVC Camera                                                    | 1        | 0.79%   |
| HP Webcam 3110                                                       | 1        | 0.79%   |
| Google Nexus/Pixel Device (MTP + debug)                              | 1        | 0.79%   |
| Chicony HP High Definition Webcam                                    | 1        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 0.79%   |
| AVerMedia Live Streamer CAM 313                                      | 1        | 0.79%   |
| Aveo USB2.0 Camera                                                   | 1        | 0.79%   |
| Arkmicro USB2.0 PC CAMERA                                            | 1        | 0.79%   |
| ARC International Camera                                             | 1        | 0.79%   |
| ANYKA V380 FHD Camera                                                | 1        | 0.79%   |
| Anker PowerConf C300                                                 | 1        | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| Elan ELAN:Fingerprint | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Gemalto (was Gemplus) | 2        | 28.57%  |
| Alcor Micro           | 2        | 28.57%  |
| Yubico.com            | 1        | 14.29%  |
| SCM Microsystems      | 1        | 14.29%  |
| Cherry                | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 2        | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader               | 2        | 28.57%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID               | 1        | 14.29%  |
| SCM Microsystems SCR3500 A Contact Reader         | 1        | 14.29%  |
| Cherry Smart Card Reader USB                      | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 443      | 83.11%  |
| 1     | 75       | 14.07%  |
| 2     | 14       | 2.63%   |
| 3     | 1        | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 42       | 42.86%  |
| Net/wireless             | 16       | 16.33%  |
| Communication controller | 12       | 12.24%  |
| Unassigned class         | 6        | 6.12%   |
| Chipcard                 | 5        | 5.1%    |
| Camera                   | 4        | 4.08%   |
| Bluetooth                | 4        | 4.08%   |
| Modem                    | 2        | 2.04%   |
| Fingerprint reader       | 2        | 2.04%   |
| Storage/nvme             | 1        | 1.02%   |
| Net/ethernet             | 1        | 1.02%   |
| Multimedia controller    | 1        | 1.02%   |
| Dvb card                 | 1        | 1.02%   |
| Card reader              | 1        | 1.02%   |

