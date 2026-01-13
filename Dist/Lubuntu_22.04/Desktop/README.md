Lubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

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

Total: 210

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3047h                       | [3e9b77ce9c](https://linux-hardware.org/?probe=3e9b77ce9c) | Dec 27, 2025 |
| Positivo      | POS-PIB150DR                | [a0e653cf7a](https://linux-hardware.org/?probe=a0e653cf7a) | Dec 26, 2025 |
| Dell          | 07WP95 A01                  | [52514104c4](https://linux-hardware.org/?probe=52514104c4) | Dec 17, 2025 |
| ASUSTek       | Rampage V EDITION 10        | [d353b691d6](https://linux-hardware.org/?probe=d353b691d6) | Nov 22, 2025 |
| ASUSTek       | Rampage V EDITION 10        | [d249be039c](https://linux-hardware.org/?probe=d249be039c) | Nov 22, 2025 |
| HP            | 3646h                       | [b50d13bcf3](https://linux-hardware.org/?probe=b50d13bcf3) | Nov 07, 2025 |
| HP            | 3646h                       | [4e4f2ff457](https://linux-hardware.org/?probe=4e4f2ff457) | Nov 07, 2025 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [c08c323907](https://linux-hardware.org/?probe=c08c323907) | Nov 03, 2025 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [8d66987856](https://linux-hardware.org/?probe=8d66987856) | Nov 02, 2025 |
| MSI           | B450 TOMAHAWK               | [aabe4ab513](https://linux-hardware.org/?probe=aabe4ab513) | Sep 25, 2025 |
| Unknown       | Xilinx Zynq                 | [d85ee6a244](https://linux-hardware.org/?probe=d85ee6a244) | Sep 17, 2025 |
| Dell          | 073MMW A00                  | [2fdb6fa60f](https://linux-hardware.org/?probe=2fdb6fa60f) | Jul 28, 2025 |
| Gigabyte      | X570 AORUS MASTER           | [f66bcf38fa](https://linux-hardware.org/?probe=f66bcf38fa) | Jul 14, 2025 |
| VS Company    | G31T-M                      | [3618308657](https://linux-hardware.org/?probe=3618308657) | Jul 14, 2025 |
| Itautec       | ST 4273 ST-4273 Custom 0... | [5e72ab6865](https://linux-hardware.org/?probe=5e72ab6865) | May 26, 2025 |
| Dell          | 0MN1TX A01                  | [74ae783308](https://linux-hardware.org/?probe=74ae783308) | Apr 30, 2025 |
| Dell          | 0N0K9J A00                  | [195bb11857](https://linux-hardware.org/?probe=195bb11857) | Apr 23, 2025 |
| Dell          | 0N0K9J A00                  | [0c6446c0f1](https://linux-hardware.org/?probe=0c6446c0f1) | Apr 23, 2025 |
| MSI           | H81M-E33                    | [0ab7142e8b](https://linux-hardware.org/?probe=0ab7142e8b) | Apr 10, 2025 |
| MSI           | H81M-E33                    | [4f6d89ad42](https://linux-hardware.org/?probe=4f6d89ad42) | Mar 20, 2025 |
| VS Company    | G31T-M                      | [1618319c37](https://linux-hardware.org/?probe=1618319c37) | Feb 06, 2025 |
| VS Company    | G31T-M                      | [ce3a28f962](https://linux-hardware.org/?probe=ce3a28f962) | Jan 31, 2025 |
| Dell          | 0N4YC8 A00                  | [f722edf7a9](https://linux-hardware.org/?probe=f722edf7a9) | Jan 01, 2025 |
| MSI           | H410M BOMBER                | [0fdf3b3e0b](https://linux-hardware.org/?probe=0fdf3b3e0b) | Nov 21, 2024 |
| MSI           | H410M BOMBER                | [97ed06f147](https://linux-hardware.org/?probe=97ed06f147) | Nov 21, 2024 |
| ASUSTek       | PRIME H510M-E R2.0          | [98d4a70c46](https://linux-hardware.org/?probe=98d4a70c46) | Nov 20, 2024 |
| Intel         | H61                         | [0e1936ef18](https://linux-hardware.org/?probe=0e1936ef18) | Oct 31, 2024 |
| ASUSTek       | M4A87TD/USB3                | [fb9c9f4215](https://linux-hardware.org/?probe=fb9c9f4215) | Oct 06, 2024 |
| ASUSTek       | M4A78 PRO                   | [3fefc80707](https://linux-hardware.org/?probe=3fefc80707) | Oct 05, 2024 |
| Gateway       | IPISB-VR                    | [bc45b7939c](https://linux-hardware.org/?probe=bc45b7939c) | Sep 23, 2024 |
| Fujitsu Si... | D2151-A2 S26361-D2151-A2    | [d15a8e878e](https://linux-hardware.org/?probe=d15a8e878e) | Sep 06, 2024 |
| Dell          | 0HY9JP A00                  | [dae885b643](https://linux-hardware.org/?probe=dae885b643) | Aug 25, 2024 |
| HP            | 2AF7                        | [d00c713358](https://linux-hardware.org/?probe=d00c713358) | Jul 23, 2024 |
| Dell          | 0MN1TX A01                  | [99e899cbb0](https://linux-hardware.org/?probe=99e899cbb0) | Jul 22, 2024 |
| Dell          | 0PC5F7 A01                  | [57944fa9c9](https://linux-hardware.org/?probe=57944fa9c9) | Jul 16, 2024 |
| Dell          | 088DT1 A01                  | [35d8e69b80](https://linux-hardware.org/?probe=35d8e69b80) | Jun 20, 2024 |
| Dell          | 07WP95 A01                  | [220e02a4f2](https://linux-hardware.org/?probe=220e02a4f2) | Jun 19, 2024 |
| ASUSTek       | M5A99X EVO                  | [01934266f4](https://linux-hardware.org/?probe=01934266f4) | May 31, 2024 |
| ASUSTek       | M5A99X EVO                  | [3414247f17](https://linux-hardware.org/?probe=3414247f17) | May 31, 2024 |
| Itautec       | NT 2030                     | [956753c602](https://linux-hardware.org/?probe=956753c602) | May 25, 2024 |
| MSI           | MS-B0A81                    | [3b16ea46f0](https://linux-hardware.org/?probe=3b16ea46f0) | May 20, 2024 |
| Dell          | 0DF42J A00                  | [dc9f14663c](https://linux-hardware.org/?probe=dc9f14663c) | May 18, 2024 |
| Intel         | H61                         | [274a448032](https://linux-hardware.org/?probe=274a448032) | May 09, 2024 |
| ASRock        | FM2A68M-DG3+                | [8049fc6b37](https://linux-hardware.org/?probe=8049fc6b37) | Apr 23, 2024 |
| HP            | 8265                        | [17dd357578](https://linux-hardware.org/?probe=17dd357578) | Apr 21, 2024 |
| Dell          | 0D28YY A00                  | [c1bd4e2de3](https://linux-hardware.org/?probe=c1bd4e2de3) | Apr 14, 2024 |
| ASRock        | H61M-VG3                    | [caf43c2754](https://linux-hardware.org/?probe=caf43c2754) | Apr 14, 2024 |
| Prestigio     | Smartbook PSB116A           | [cc592e784e](https://linux-hardware.org/?probe=cc592e784e) | Apr 13, 2024 |
| Unknown       | Unknown                     | [94f12b2951](https://linux-hardware.org/?probe=94f12b2951) | Apr 11, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | [8f232e4e6c](https://linux-hardware.org/?probe=8f232e4e6c) | Apr 11, 2024 |
| Biostar       | TA75M+                      | [24de8dbd0b](https://linux-hardware.org/?probe=24de8dbd0b) | Apr 10, 2024 |
| ASRock        | H61M-VG3                    | [82fa2b1397](https://linux-hardware.org/?probe=82fa2b1397) | Apr 04, 2024 |
| Dell          | Inspiron 531s               | [0d9877a337](https://linux-hardware.org/?probe=0d9877a337) | Feb 19, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [edc56f85b9](https://linux-hardware.org/?probe=edc56f85b9) | Feb 17, 2024 |
| ASRock        | H110M Combo-G               | [319e01fd31](https://linux-hardware.org/?probe=319e01fd31) | Feb 09, 2024 |
| MSI           | MS-7309                     | [dd1dea1c0e](https://linux-hardware.org/?probe=dd1dea1c0e) | Feb 07, 2024 |
| Gigabyte      | H61M-S1                     | [e7f247621c](https://linux-hardware.org/?probe=e7f247621c) | Feb 02, 2024 |
| Dell          | 0DF42J A00                  | [f181c086e3](https://linux-hardware.org/?probe=f181c086e3) | Jan 23, 2024 |
| Dell          | 0DF42J A00                  | [5a172ff7ec](https://linux-hardware.org/?probe=5a172ff7ec) | Jan 22, 2024 |
| ASUSTek       | M2N32-SLI DELUXE            | [9b6eb3d320](https://linux-hardware.org/?probe=9b6eb3d320) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | [5d46b8d1b3](https://linux-hardware.org/?probe=5d46b8d1b3) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | [cf089739df](https://linux-hardware.org/?probe=cf089739df) | Jan 19, 2024 |
| ZOTAC         | NM10                        | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| Intel         | H61                         | [1d639194e4](https://linux-hardware.org/?probe=1d639194e4) | Jan 17, 2024 |
| HP            | 3397                        | [a46224b9bc](https://linux-hardware.org/?probe=a46224b9bc) | Jan 17, 2024 |
| ASUSTek       | PRIME B250-PLUS             | [c0f0afd78c](https://linux-hardware.org/?probe=c0f0afd78c) | Jan 14, 2024 |
| ASUSTek       | PRIME B250-PLUS             | [5654e285db](https://linux-hardware.org/?probe=5654e285db) | Jan 10, 2024 |
| Dell          | 0CRH6C A00                  | [6c4bafe7b1](https://linux-hardware.org/?probe=6c4bafe7b1) | Jan 04, 2024 |
| ASUSTek       | PRIME B250-PLUS             | [8f6b669800](https://linux-hardware.org/?probe=8f6b669800) | Dec 27, 2023 |
| Dell          | 0XPDFK A01                  | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| PELADN        | HA-3                        | [cd40102512](https://linux-hardware.org/?probe=cd40102512) | Dec 17, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [e126cdbf4b](https://linux-hardware.org/?probe=e126cdbf4b) | Dec 10, 2023 |
| Dell          | 0XPDFK A01                  | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| eMachines     | EL1358                      | [f22b0b98c3](https://linux-hardware.org/?probe=f22b0b98c3) | Nov 23, 2023 |
| MSI           | MS-7309                     | [c6ca259cae](https://linux-hardware.org/?probe=c6ca259cae) | Nov 13, 2023 |
| PCChips       | P49G                        | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| ZOTAC         | NM10                        | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| ASUSTek       | P7P55-M                     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| Intel         | H61                         | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| ZOTAC         | NM10                        | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| HP            | 8265                        | [f1bdedb075](https://linux-hardware.org/?probe=f1bdedb075) | Oct 20, 2023 |
| ASRock        | Q1900B-ITX                  | [f8ad7736e2](https://linux-hardware.org/?probe=f8ad7736e2) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| Intel         | H61                         | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [7b1aae3e2b](https://linux-hardware.org/?probe=7b1aae3e2b) | Sep 20, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [47d423039b](https://linux-hardware.org/?probe=47d423039b) | Sep 19, 2023 |
| ASUSTek       | M4A87TD/USB3                | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| Dell          | 0T10XW A00                  | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [69fec63660](https://linux-hardware.org/?probe=69fec63660) | Sep 04, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [ea00f871b9](https://linux-hardware.org/?probe=ea00f871b9) | Sep 04, 2023 |
| Inventec      | DQ Class A02                | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Apple         | Mac-F223BEC8                | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| Shuttle       | XS35V3                      | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| ASUSTek       | P5QD TURBO                  | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Shuttle       | XS35V3                      | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Unknown       | T3 MRD                      | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| HP            | 3646h                       | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| ASUSTek       | M4A87TD/USB3                | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Pegatron      | 2A73h                       | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| HP            | 3646h                       | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| HP            | 3646h                       | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 3397                        | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Unknown       | Unknown                     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| Foxconn       | G41MXE-V                    | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| ASUSTek       | A88XM-A                     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| ZOTAC         | NM10                        | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Acer          | EQ45M                       | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| NEC Comput... | ECS-945G                    | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| MSI           | H310M PRO-VD                | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| MSI           | B550-A PRO                  | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| YANYU         | ITX-S192                    | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Gigabyte      | MJPLNBB-00                  | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| BANGHO        | LITE E34                    | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| Gigabyte      | B360M DS3H                  | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Pegatron      | 2AD5                        | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| MSI           | MS-7267                     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| ECS           | G41T-M7                     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| ASUSTek       | M5A78L-M LX3                | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Dell          | 0FPP7F A00                  | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| MSI           | B550-A PRO                  | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| MSI           | MS-7032                     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| NEC Comput... | ECS-945G                    | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| ASRock        | ION3D-HT                    | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| ASUSTek       | M5A97 PRO                   | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Positivo      | POS-AG31AP                  | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| HP            | 21B4 A01                    | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| ZOTAC         | NM10                        | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Intel         | BTC-T37                     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| ASUSTek       | EB1501P                     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| ASRock        | H110M-HDV                   | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Gigabyte      | F2A58M-HD2                  | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| HP            | 0B4Ch D                     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Dell          | 0R849J A00                  | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Dell          | 09M8Y8 A01                  | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| MSI           | B450-A PRO MAX              | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| AMI           | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Dell          | 0J584C A00                  | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| MSI           | Z590-A PRO                  | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| MSI           | Z170A GAMING M3             | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| ASRock        | G41M-VS3                    | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| HP            | 8768 A                      | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| HP            | 1495                        | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| MSI           | 760GM-P23                   | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | PRIME X370-A                | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Dell          | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-43-generic | 10       | 5.71%   |
| 5.19.0-50-generic | 7        | 4%      |
| 5.19.0-32-generic | 6        | 3.43%   |
| 6.5.0-14-generic  | 5        | 2.86%   |
| 5.15.0-60-generic | 5        | 2.86%   |
| 5.15.0-41-generic | 5        | 2.86%   |
| 5.15.0-56-generic | 4        | 2.29%   |
| 5.15.0-47-generic | 4        | 2.29%   |
| 5.15.0-25-generic | 4        | 2.29%   |
| 6.8.0-48-generic  | 3        | 1.71%   |
| 6.5.0-27-generic  | 3        | 1.71%   |
| 5.15.0-91-generic | 3        | 1.71%   |
| 5.15.0-75-generic | 3        | 1.71%   |
| 5.15.0-67-generic | 3        | 1.71%   |
| 5.15.0-52-generic | 3        | 1.71%   |
| 5.15.0-48-generic | 3        | 1.71%   |
| 5.15.0-40-generic | 3        | 1.71%   |
| 5.15.0-39-generic | 3        | 1.71%   |
| 6.8.0-85-generic  | 2        | 1.14%   |
| 6.8.0-60-generic  | 2        | 1.14%   |
| 6.8.0-45-generic  | 2        | 1.14%   |
| 6.5.0-35-generic  | 2        | 1.14%   |
| 6.5.0-28-generic  | 2        | 1.14%   |
| 6.5.0-17-generic  | 2        | 1.14%   |
| 6.2.0-39-generic  | 2        | 1.14%   |
| 6.2.0-36-generic  | 2        | 1.14%   |
| 6.2.0-35-generic  | 2        | 1.14%   |
| 6.2.0-26-generic  | 2        | 1.14%   |
| 5.19.0-46-generic | 2        | 1.14%   |
| 5.19.0-43-generic | 2        | 1.14%   |
| 5.19.0-35-generic | 2        | 1.14%   |
| 5.15.0-94-generic | 2        | 1.14%   |
| 5.15.0-89-generic | 2        | 1.14%   |
| 5.15.0-86-generic | 2        | 1.14%   |
| 5.15.0-83-generic | 2        | 1.14%   |
| 5.15.0-82-generic | 2        | 1.14%   |
| 5.15.0-58-generic | 2        | 1.14%   |
| 5.15.0-53-generic | 2        | 1.14%   |
| 5.15.0-50-generic | 2        | 1.14%   |
| 5.15.0-46-generic | 2        | 1.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 89       | 54.6%   |
| 5.19.0  | 23       | 14.11%  |
| 6.5.0   | 19       | 11.66%  |
| 6.8.0   | 12       | 7.36%   |
| 6.2.0   | 9        | 5.52%   |
| 6.7.0   | 1        | 0.61%   |
| 6.6.0   | 1        | 0.61%   |
| 6.3.3   | 1        | 0.61%   |
| 6.2.8   | 1        | 0.61%   |
| 6.13.9  | 1        | 0.61%   |
| 6.12.11 | 1        | 0.61%   |
| 6.1.46  | 1        | 0.61%   |
| 6.1.0   | 1        | 0.61%   |
| 6.0.8   | 1        | 0.61%   |
| 6.0.14  | 1        | 0.61%   |
| 4.4.30  | 1        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 89       | 54.6%   |
| 5.19    | 23       | 14.11%  |
| 6.5     | 19       | 11.66%  |
| 6.8     | 12       | 7.36%   |
| 6.2     | 10       | 6.13%   |
| 6.1     | 2        | 1.23%   |
| 6.0     | 2        | 1.23%   |
| 6.7     | 1        | 0.61%   |
| 6.6     | 1        | 0.61%   |
| 6.3     | 1        | 0.61%   |
| 6.13    | 1        | 0.61%   |
| 6.12    | 1        | 0.61%   |
| 4.4     | 1        | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 152      | 99.35%  |
| armv7l | 1        | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| LXQt           | 142      | 92.81%  |
| LXDE           | 6        | 3.92%   |
| GNOME          | 2        | 1.31%   |
| XFCE           | 1        | 0.65%   |
| ratflow        | 1        | 0.65%   |
| i3-with-shmlog | 1        | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 145      | 92.95%  |
| Tty         | 9        | 5.77%   |
| Wayland     | 1        | 0.64%   |
| Unspecified | 1        | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 118      | 77.12%  |
| LightDM | 12       | 7.84%   |
| Unknown | 12       | 7.84%   |
| GDM3    | 5        | 3.27%   |
| XDM     | 3        | 1.96%   |
| LXDM    | 2        | 1.31%   |
| SLiM    | 1        | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 48       | 30.77%  |
| fr_FR | 24       | 15.38%  |
| de_DE | 13       | 8.33%   |
| pt_BR | 10       | 6.41%   |
| es_ES | 7        | 4.49%   |
| en_GB | 7        | 4.49%   |
| it_IT | 6        | 3.85%   |
| es_AR | 5        | 3.21%   |
| C     | 5        | 3.21%   |
| en_CA | 3        | 1.92%   |
| en_AU | 3        | 1.92%   |
| zh_TW | 2        | 1.28%   |
| pl_PL | 2        | 1.28%   |
| es_MX | 2        | 1.28%   |
| es_CR | 2        | 1.28%   |
| tr_TR | 1        | 0.64%   |
| sv_SE | 1        | 0.64%   |
| ru_UA | 1        | 0.64%   |
| ru_RU | 1        | 0.64%   |
| nl_BE | 1        | 0.64%   |
| ja_JP | 1        | 0.64%   |
| fi_FI | 1        | 0.64%   |
| es_VE | 1        | 0.64%   |
| es_PE | 1        | 0.64%   |
| es_CU | 1        | 0.64%   |
| en_SG | 1        | 0.64%   |
| en_DK | 1        | 0.64%   |
| en_AG | 1        | 0.64%   |
| el_GR | 1        | 0.64%   |
| de_LU | 1        | 0.64%   |
| cv_RU | 1        | 0.64%   |
| cs_CZ | 1        | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 108      | 69.68%  |
| EFI  | 47       | 30.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 123      | 79.35%  |
| Tmpfs   | 23       | 14.84%  |
| Overlay | 4        | 2.58%   |
| Btrfs   | 2        | 1.29%   |
| Zfs     | 1        | 0.65%   |
| XXX4    | 1        | 0.65%   |
| Nfs     | 1        | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 77       | 49.68%  |
| MBR     | 51       | 32.9%   |
| Unknown | 27       | 17.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 122      | 78.21%  |
| Yes       | 34       | 21.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 66.67%  |
| Yes       | 51       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 28       | 18.3%   |
| Dell                | 25       | 16.34%  |
| MSI                 | 21       | 13.73%  |
| Hewlett-Packard     | 10       | 6.54%   |
| ASRock              | 10       | 6.54%   |
| Gigabyte Technology | 8        | 5.23%   |
| Unknown             | 7        | 4.58%   |
| Pegatron            | 4        | 2.61%   |
| Lenovo              | 4        | 2.61%   |
| Intel               | 4        | 2.61%   |
| Acer                | 4        | 2.61%   |
| Positivo            | 3        | 1.96%   |
| Itautec             | 2        | 1.31%   |
| Fujitsu             | 2        | 1.31%   |
| AMI                 | 2        | 1.31%   |
| ZOTAC               | 1        | 0.65%   |
| YANYU               | 1        | 0.65%   |
| VS Company          | 1        | 0.65%   |
| Shuttle             | 1        | 0.65%   |
| Seeed Studio        | 1        | 0.65%   |
| PELADN              | 1        | 0.65%   |
| PCChips             | 1        | 0.65%   |
| NEC Computers       | 1        | 0.65%   |
| Inventec            | 1        | 0.65%   |
| IceWhale Technology | 1        | 0.65%   |
| Gateway             | 1        | 0.65%   |
| Fujitsu Siemens     | 1        | 0.65%   |
| Foxconn             | 1        | 0.65%   |
| eMachines           | 1        | 0.65%   |
| ECS                 | 1        | 0.65%   |
| Biostar             | 1        | 0.65%   |
| BANGHO              | 1        | 0.65%   |
| Apple               | 1        | 0.65%   |
| AAEON               | 1        | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Desktops | Percent |
|---------------------------------------|----------|---------|
| Unknown                               | 7        | 4.58%   |
| MSI MS-7C37                           | 3        | 1.96%   |
| MSI MS-7309                           | 2        | 1.31%   |
| Intel H61                             | 2        | 1.31%   |
| HP Compaq 8000 Elite SFF PC           | 2        | 1.31%   |
| Dell OptiPlex 9020                    | 2        | 1.31%   |
| Dell OptiPlex 790                     | 2        | 1.31%   |
| Dell OptiPlex 7010                    | 2        | 1.31%   |
| Dell Dimension 9100                   | 2        | 1.31%   |
| ZOTAC NM10                            | 1        | 0.65%   |
| YANYU ITX-S192                        | 1        | 0.65%   |
| VS Company G31T-M                     | 1        | 0.65%   |
| Shuttle XS35V3                        | 1        | 0.65%   |
| Seeed Studio ODYSSEY-X86J4125         | 1        | 0.65%   |
| Positivo Positivo Master C610 MiniPro | 1        | 0.65%   |
| Positivo POS-AG31AP                   | 1        | 0.65%   |
| Positivo P5VD2-MX                     | 1        | 0.65%   |
| PELADN HA-3                           | 1        | 0.65%   |
| Pegatron NC689AA-ABA s3700y           | 1        | 0.65%   |
| Pegatron h8-1350ef                    | 1        | 0.65%   |
| Pegatron Compaq dx2400 Microtower PC  | 1        | 0.65%   |
| Pegatron AY748AA-ABA p6320y           | 1        | 0.65%   |
| PCChips P49G                          | 1        | 0.65%   |
| NEC Computers ECS-945G                | 1        | 0.65%   |
| MSI PRO ADL-U Cubi 5 (MS-B0A8)        | 1        | 0.65%   |
| MSI MS-7D54                           | 1        | 0.65%   |
| MSI MS-7D09                           | 1        | 0.65%   |
| MSI MS-7C96                           | 1        | 0.65%   |
| MSI MS-7C89                           | 1        | 0.65%   |
| MSI MS-7C56                           | 1        | 0.65%   |
| MSI MS-7C51                           | 1        | 0.65%   |
| MSI MS-7C02                           | 1        | 0.65%   |
| MSI MS-7B86                           | 1        | 0.65%   |
| MSI MS-7B33                           | 1        | 0.65%   |
| MSI MS-7978                           | 1        | 0.65%   |
| MSI MS-7817                           | 1        | 0.65%   |
| MSI MS-7641                           | 1        | 0.65%   |
| MSI MS-7501                           | 1        | 0.65%   |
| MSI MS-7267                           | 1        | 0.65%   |
| MSI MS-7032                           | 1        | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 12       | 7.84%   |
| Unknown                       | 7        | 4.58%   |
| HP Compaq                     | 5        | 3.27%   |
| ASUS PRIME                    | 5        | 3.27%   |
| Lenovo ThinkCentre            | 4        | 2.61%   |
| Dell Precision                | 4        | 2.61%   |
| MSI MS-7C37                   | 3        | 1.96%   |
| Dell Inspiron                 | 3        | 1.96%   |
| ASUS ROG                      | 3        | 1.96%   |
| MSI MS-7309                   | 2        | 1.31%   |
| Intel H61                     | 2        | 1.31%   |
| Dell Vostro                   | 2        | 1.31%   |
| Dell Dimension                | 2        | 1.31%   |
| Acer Veriton                  | 2        | 1.31%   |
| ZOTAC NM10                    | 1        | 0.65%   |
| YANYU ITX-S192                | 1        | 0.65%   |
| VS Company G31T-M             | 1        | 0.65%   |
| Shuttle XS35V3                | 1        | 0.65%   |
| Seeed Studio ODYSSEY-X86J4125 | 1        | 0.65%   |
| Positivo Positivo             | 1        | 0.65%   |
| Positivo POS-AG31AP           | 1        | 0.65%   |
| Positivo P5VD2-MX             | 1        | 0.65%   |
| PELADN HA-3                   | 1        | 0.65%   |
| Pegatron NC689AA-ABA          | 1        | 0.65%   |
| Pegatron h8-1350ef            | 1        | 0.65%   |
| Pegatron Compaq               | 1        | 0.65%   |
| Pegatron AY748AA-ABA          | 1        | 0.65%   |
| PCChips P49G                  | 1        | 0.65%   |
| NEC Computers ECS-945G        | 1        | 0.65%   |
| MSI PRO                       | 1        | 0.65%   |
| MSI MS-7D54                   | 1        | 0.65%   |
| MSI MS-7D09                   | 1        | 0.65%   |
| MSI MS-7C96                   | 1        | 0.65%   |
| MSI MS-7C89                   | 1        | 0.65%   |
| MSI MS-7C56                   | 1        | 0.65%   |
| MSI MS-7C51                   | 1        | 0.65%   |
| MSI MS-7C02                   | 1        | 0.65%   |
| MSI MS-7B86                   | 1        | 0.65%   |
| MSI MS-7B33                   | 1        | 0.65%   |
| MSI MS-7978                   | 1        | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2009    | 16       | 10.46%  |
| 2012    | 12       | 7.84%   |
| 2010    | 12       | 7.84%   |
| 2019    | 10       | 6.54%   |
| 2018    | 10       | 6.54%   |
| 2017    | 10       | 6.54%   |
| 2013    | 10       | 6.54%   |
| 2011    | 10       | 6.54%   |
| 2008    | 10       | 6.54%   |
| 2020    | 7        | 4.58%   |
| 2022    | 6        | 3.92%   |
| 2015    | 6        | 3.92%   |
| 2014    | 6        | 3.92%   |
| 2007    | 6        | 3.92%   |
| 2021    | 5        | 3.27%   |
| 2006    | 5        | 3.27%   |
| 2023    | 4        | 2.61%   |
| 2016    | 4        | 2.61%   |
| 2024    | 1        | 0.65%   |
| 2004    | 1        | 0.65%   |
| 2001    | 1        | 0.65%   |
| Unknown | 1        | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 153      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 149      | 97.39%  |
| Enabled  | 4        | 2.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 153      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 31       | 19.87%  |
| 4.01-8.0    | 29       | 18.59%  |
| 16.01-24.0  | 26       | 16.67%  |
| 8.01-16.0   | 23       | 14.74%  |
| 32.01-64.0  | 18       | 11.54%  |
| 1.01-2.0    | 16       | 10.26%  |
| 64.01-256.0 | 5        | 3.21%   |
| 2.01-3.0    | 3        | 1.92%   |
| 0.51-1.0    | 3        | 1.92%   |
| 24.01-32.0  | 1        | 0.64%   |
| 0.01-0.5    | 1        | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 64       | 39.02%  |
| 2.01-3.0   | 33       | 20.12%  |
| 0.51-1.0   | 28       | 17.07%  |
| 4.01-8.0   | 21       | 12.8%   |
| 3.01-4.0   | 8        | 4.88%   |
| 8.01-16.0  | 5        | 3.05%   |
| 0.01-0.5   | 3        | 1.83%   |
| 32.01-64.0 | 2        | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 76       | 49.67%  |
| 2      | 45       | 29.41%  |
| 3      | 17       | 11.11%  |
| 4      | 5        | 3.27%   |
| 5      | 4        | 2.61%   |
| 7      | 2        | 1.31%   |
| 6      | 2        | 1.31%   |
| 12     | 1        | 0.65%   |
| 0      | 1        | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 59.87%  |
| Yes       | 63       | 40.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 150      | 98.04%  |
| No        | 3        | 1.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 55.48%  |
| Yes       | 69       | 44.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 76.77%  |
| Yes       | 36       | 23.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 28       | 18.3%   |
| France     | 24       | 15.69%  |
| Germany    | 14       | 9.15%   |
| Brazil     | 13       | 8.5%    |
| Spain      | 8        | 5.23%   |
| Poland     | 7        | 4.58%   |
| Italy      | 6        | 3.92%   |
| UK         | 5        | 3.27%   |
| Argentina  | 5        | 3.27%   |
| Canada     | 3        | 1.96%   |
| Australia  | 3        | 1.96%   |
| Venezuela  | 2        | 1.31%   |
| Sweden     | 2        | 1.31%   |
| Russia     | 2        | 1.31%   |
| Malaysia   | 2        | 1.31%   |
| Luxembourg | 2        | 1.31%   |
| Iran       | 2        | 1.31%   |
| Indonesia  | 2        | 1.31%   |
| Costa Rica | 2        | 1.31%   |
| Bulgaria   | 2        | 1.31%   |
| Ukraine    | 1        | 0.65%   |
| Turkey     | 1        | 0.65%   |
| Taiwan     | 1        | 0.65%   |
| Slovakia   | 1        | 0.65%   |
| Serbia     | 1        | 0.65%   |
| Romania    | 1        | 0.65%   |
| Peru       | 1        | 0.65%   |
| Pakistan   | 1        | 0.65%   |
| Morocco    | 1        | 0.65%   |
| Mexico     | 1        | 0.65%   |
| Latvia     | 1        | 0.65%   |
| Japan      | 1        | 0.65%   |
| Ireland    | 1        | 0.65%   |
| Greece     | 1        | 0.65%   |
| Finland    | 1        | 0.65%   |
| Denmark    | 1        | 0.65%   |
| Czechia    | 1        | 0.65%   |
| Cuba       | 1        | 0.65%   |
| Belgium    | 1        | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 1.86%   |
| Warsaw                 | 2        | 1.24%   |
| Tehran                 | 2        | 1.24%   |
| Sao Paulo              | 2        | 1.24%   |
| Sao José dos Campos   | 2        | 1.24%   |
| Melbourne              | 2        | 1.24%   |
| Largo                  | 2        | 1.24%   |
| Karlstad               | 2        | 1.24%   |
| Heredia                | 2        | 1.24%   |
| Chicago                | 2        | 1.24%   |
| Yaroslavl              | 1        | 0.62%   |
| Woking                 | 1        | 0.62%   |
| Wetteren               | 1        | 0.62%   |
| Washington             | 1        | 0.62%   |
| Vordorf                | 1        | 0.62%   |
| Villingen-Schwenningen | 1        | 0.62%   |
| Villa Ballester        | 1        | 0.62%   |
| Victoria               | 1        | 0.62%   |
| Versailles             | 1        | 0.62%   |
| Veliko Tarnovo         | 1        | 0.62%   |
| Varna                  | 1        | 0.62%   |
| Vallet                 | 1        | 0.62%   |
| Valentigney            | 1        | 0.62%   |
| Valencia               | 1        | 0.62%   |
| Tychy                  | 1        | 0.62%   |
| Turin                  | 1        | 0.62%   |
| Torrejón de Ardoz     | 1        | 0.62%   |
| Tandil                 | 1        | 0.62%   |
| Taipei                 | 1        | 0.62%   |
| St Louis               | 1        | 0.62%   |
| Sonico                 | 1        | 0.62%   |
| Sherbrooke             | 1        | 0.62%   |
| Settat                 | 1        | 0.62%   |
| Schonsee               | 1        | 0.62%   |
| Sarcelles              | 1        | 0.62%   |
| Santomera              | 1        | 0.62%   |
| Saltsjoe-Boo           | 1        | 0.62%   |
| Ronde                  | 1        | 0.62%   |
| Rochester              | 1        | 0.62%   |
| Riverenert             | 1        | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 45       | 62     | 18%     |
| WDC                          | 43       | 64     | 17.2%   |
| Samsung Electronics          | 30       | 46     | 12%     |
| Kingston                     | 16       | 26     | 6.4%    |
| Hitachi                      | 15       | 20     | 6%      |
| SanDisk                      | 9        | 10     | 3.6%    |
| Crucial                      | 8        | 10     | 3.2%    |
| Toshiba                      | 7        | 10     | 2.8%    |
| Unknown                      | 6        | 6      | 2.4%    |
| A-DATA Technology            | 5        | 5      | 2%      |
| HGST                         | 4        | 4      | 1.6%    |
| Maxtor                       | 3        | 5      | 1.2%    |
| Kingston Technology Company  | 3        | 3      | 1.2%    |
| Intenso                      | 3        | 3      | 1.2%    |
| China                        | 3        | 5      | 1.2%    |
| Apacer                       | 3        | 3      | 1.2%    |
| Team                         | 2        | 2      | 0.8%    |
| PNY                          | 2        | 2      | 0.8%    |
| Patriot                      | 2        | 2      | 0.8%    |
| Micron/Crucial Technology    | 2        | 3      | 0.8%    |
| Micron Technology            | 2        | 2      | 0.8%    |
| GOODRAM                      | 2        | 2      | 0.8%    |
| ExcelStor                    | 2        | 2      | 0.8%    |
| BR                           | 2        | 3      | 0.8%    |
| Apple                        | 2        | 2      | 0.8%    |
| XrayDisk                     | 1        | 1      | 0.4%    |
| WDC WUH                      | 1        | 1      | 0.4%    |
| WD MediaMax                  | 1        | 1      | 0.4%    |
| Varro                        | 1        | 1      | 0.4%    |
| Transcend                    | 1        | 2      | 0.4%    |
| TO Exter                     | 1        | 1      | 0.4%    |
| T-FORCE                      | 1        | 1      | 0.4%    |
| Silicon Motion               | 1        | 1      | 0.4%    |
| Shenzhen Longsys Electronics | 1        | 2      | 0.4%    |
| RSH-319                      | 1        | 1      | 0.4%    |
| Phison                       | 1        | 1      | 0.4%    |
| OWC                          | 1        | 1      | 0.4%    |
| MW2406-SATA                  | 1        | 1      | 0.4%    |
| LITEONIT                     | 1        | 1      | 0.4%    |
| Kston                        | 1        | 3      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD    | 7        | 2.48%   |
| Seagate ST500DM002-1BD142 500GB    | 6        | 2.13%   |
| Toshiba DT01ACA100 1TB             | 4        | 1.42%   |
| Seagate ST1000DM003-1CH162 1TB     | 4        | 1.42%   |
| Samsung SSD 870 EVO 500GB          | 3        | 1.06%   |
| Kingston SA400S37960G 960GB SSD    | 3        | 1.06%   |
| Kingston SA400S37120G 120GB SSD    | 3        | 1.06%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 2        | 0.71%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 2        | 0.71%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2        | 0.71%   |
| Seagate ST3500418AS 500GB          | 2        | 0.71%   |
| Seagate ST3120213AS 120GB          | 2        | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.71%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.71%   |
| SanDisk DF4032  32GB               | 2        | 0.71%   |
| Samsung SSD 970 EVO Plus 250GB     | 2        | 0.71%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.71%   |
| Samsung HD502HJ 500GB              | 2        | 0.71%   |
| Samsung HD161HJ 160GB              | 2        | 0.71%   |
| Maxtor STM3160215AS 160GB          | 2        | 0.71%   |
| Kingston Company SNV2S1000G 1TB    | 2        | 0.71%   |
| ExcelStor J8160S 160GB             | 2        | 0.71%   |
| Crucial CT1000BX500SSD1 1TB        | 2        | 0.71%   |
| China SSD 128GB                    | 2        | 0.71%   |
| XrayDisk 240GB SSD                 | 1        | 0.35%   |
| WDC WUH721818ALE6L4 18TB           | 1        | 0.35%   |
| WDC WUH 721818ALE6L4 18TB          | 1        | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 1        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB       | 1        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 0.35%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.35%   |
| WDC WD800BD-00MRA1 80GB            | 1        | 0.35%   |
| WDC WD800BB-00CAA1 80GB            | 1        | 0.35%   |
| WDC WD80 03FFBX-68B9A 8TB          | 1        | 0.35%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 0.35%   |
| WDC WD5003AZEX-00K3CA0 500GB       | 1        | 0.35%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 45       | 61     | 34.09%  |
| WDC                 | 39       | 56     | 29.55%  |
| Hitachi             | 15       | 20     | 11.36%  |
| Samsung Electronics | 8        | 9      | 6.06%   |
| Toshiba             | 7        | 10     | 5.3%    |
| HGST                | 4        | 4      | 3.03%   |
| Maxtor              | 3        | 5      | 2.27%   |
| ExcelStor           | 2        | 2      | 1.52%   |
| WD MediaMax         | 1        | 1      | 0.76%   |
| TO Exter            | 1        | 1      | 0.76%   |
| T-FORCE             | 1        | 1      | 0.76%   |
| RSH-319             | 1        | 1      | 0.76%   |
| Intenso             | 1        | 1      | 0.76%   |
| External            | 1        | 1      | 0.76%   |
| ASMT                | 1        | 1      | 0.76%   |
| Apricorn            | 1        | 1      | 0.76%   |
| Apple               | 1        | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 15       | 26     | 18.52%  |
| Kingston            | 15       | 25     | 18.52%  |
| SanDisk             | 7        | 8      | 8.64%   |
| WDC                 | 5        | 5      | 6.17%   |
| Crucial             | 4        | 5      | 4.94%   |
| A-DATA Technology   | 4        | 4      | 4.94%   |
| China               | 3        | 5      | 3.7%    |
| Apacer              | 3        | 3      | 3.7%    |
| Team                | 2        | 2      | 2.47%   |
| PNY                 | 2        | 2      | 2.47%   |
| Intenso             | 2        | 2      | 2.47%   |
| GOODRAM             | 2        | 2      | 2.47%   |
| XrayDisk            | 1        | 1      | 1.23%   |
| Varro               | 1        | 1      | 1.23%   |
| Transcend           | 1        | 2      | 1.23%   |
| Patriot             | 1        | 1      | 1.23%   |
| OWC                 | 1        | 1      | 1.23%   |
| Micron Technology   | 1        | 1      | 1.23%   |
| LITEONIT            | 1        | 1      | 1.23%   |
| Kston               | 1        | 3      | 1.23%   |
| KINGBANK            | 1        | 4      | 1.23%   |
| Intel               | 1        | 1      | 1.23%   |
| HUSKY               | 1        | 2      | 1.23%   |
| Gigabyte Technology | 1        | 1      | 1.23%   |
| GeIL                | 1        | 1      | 1.23%   |
| Emtec               | 1        | 1      | 1.23%   |
| Dogfish             | 1        | 1      | 1.23%   |
| BR                  | 1        | 1      | 1.23%   |
| Apple               | 1        | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 99       | 176    | 47.14%  |
| SSD     | 70       | 113    | 33.33%  |
| NVMe    | 27       | 36     | 12.86%  |
| MMC     | 9        | 9      | 4.29%   |
| Unknown | 5        | 7      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 137      | 281    | 76.11%  |
| NVMe | 26       | 34     | 14.44%  |
| MMC  | 9        | 9      | 5%      |
| SAS  | 8        | 17     | 4.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 113      | 177    | 60.11%  |
| 0.51-1.0   | 38       | 54     | 20.21%  |
| 1.01-2.0   | 20       | 33     | 10.64%  |
| 4.01-10.0  | 6        | 11     | 3.19%   |
| 3.01-4.0   | 5        | 7      | 2.66%   |
| 2.01-3.0   | 5        | 6      | 2.66%   |
| 10.01-20.0 | 1        | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 38       | 23.9%   |
| 251-500        | 33       | 20.75%  |
| 501-1000       | 18       | 11.32%  |
| 1001-2000      | 16       | 10.06%  |
| 21-50          | 15       | 9.43%   |
| More than 3000 | 14       | 8.81%   |
| 51-100         | 10       | 6.29%   |
| 1-20           | 7        | 4.4%    |
| 2001-3000      | 6        | 3.77%   |
| Unknown        | 2        | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 61       | 37.65%  |
| 21-50          | 26       | 16.05%  |
| 101-250        | 20       | 12.35%  |
| 501-1000       | 16       | 9.88%   |
| 51-100         | 11       | 6.79%   |
| 251-500        | 9        | 5.56%   |
| More than 3000 | 7        | 4.32%   |
| 1001-2000      | 7        | 4.32%   |
| 2001-3000      | 3        | 1.85%   |
| Unknown        | 2        | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD20EFRX-68EUZN0 2TB            | 2        | 2      | 7.69%   |
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 2      | 3.85%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1      | 3.85%   |
| WDC WD3200AACS-00M6B0 320GB         | 1        | 1      | 3.85%   |
| WDC WD2500AAJS-75M0A0 249GB         | 1        | 1      | 3.85%   |
| WDC WD2003FYYS-02W0B0 2TB           | 1        | 1      | 3.85%   |
| WDC WD10SPZX-08Z10 1TB              | 1        | 1      | 3.85%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 3.85%   |
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 3.85%   |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 3.85%   |
| Toshiba DT01ACA050 500GB            | 1        | 1      | 3.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 3.85%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 3.85%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 2      | 3.85%   |
| Seagate ST1000DM003-1CH162 1TB      | 1        | 1      | 3.85%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 3.85%   |
| Maxtor 6L200M0 208GB                | 1        | 1      | 3.85%   |
| Hitachi HTS545032B9A300 320GB       | 1        | 1      | 3.85%   |
| Hitachi HTS545016B9A300 160GB       | 1        | 1      | 3.85%   |
| Hitachi HTS543216L9A300 160GB       | 1        | 1      | 3.85%   |
| Hitachi HTE545050B9A300 500GB       | 1        | 1      | 3.85%   |
| Apple HDD HTS547550A9E384 500GB     | 1        | 1      | 3.85%   |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 3.85%   |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 33.33%  |
| Seagate             | 5        | 6      | 20.83%  |
| Hitachi             | 4        | 4      | 16.67%  |
| Toshiba             | 2        | 2      | 8.33%   |
| Samsung Electronics | 1        | 1      | 4.17%   |
| Maxtor              | 1        | 1      | 4.17%   |
| Apple               | 1        | 1      | 4.17%   |
| Apacer              | 1        | 1      | 4.17%   |
| A-DATA Technology   | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 36.36%  |
| Seagate             | 5        | 6      | 22.73%  |
| Hitachi             | 4        | 4      | 18.18%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Samsung Electronics | 1        | 1      | 4.55%   |
| Maxtor              | 1        | 1      | 4.55%   |
| Apple               | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 26     | 91.3%   |
| SSD  | 2        | 2      | 8.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1        | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1        | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 33.33%  |
| Samsung Electronics | 1        | 1      | 33.33%  |
| HGST                | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 80       | 147    | 45.2%   |
| Detected | 71       | 163    | 40.11%  |
| Malfunc  | 23       | 28     | 12.99%  |
| Failed   | 3        | 3      | 1.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 95       | 47.74%  |
| AMD                          | 41       | 20.6%   |
| Nvidia                       | 10       | 5.03%   |
| Samsung Electronics          | 8        | 4.02%   |
| ASMedia Technology           | 7        | 3.52%   |
| Micron/Crucial Technology    | 6        | 3.02%   |
| JMicron Technology           | 6        | 3.02%   |
| Kingston Technology Company  | 4        | 2.01%   |
| VIA Technologies             | 3        | 1.51%   |
| SanDisk                      | 3        | 1.51%   |
| LSI Logic / Symbios Logic    | 3        | 1.51%   |
| Silicon Image                | 2        | 1.01%   |
| Marvell Technology Group     | 2        | 1.01%   |
| Silicon Motion               | 1        | 0.5%    |
| Shenzhen Longsys Electronics | 1        | 0.5%    |
| Seagate Technology           | 1        | 0.5%    |
| Phison Electronics           | 1        | 0.5%    |
| Micron Technology            | 1        | 0.5%    |
| KIOXIA                       | 1        | 0.5%    |
| Hosin Global Electronics     | 1        | 0.5%    |
| Apple                        | 1        | 0.5%    |
| ADATA Technology             | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23       | 8.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 17       | 6.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 15       | 5.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9        | 3.44%   |
| Nvidia MCP61 SATA Controller                                                   | 7        | 2.67%   |
| Intel SATA Controller [RAID mode]                                              | 7        | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7        | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7        | 2.67%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6        | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 2.29%   |
| Nvidia MCP61 IDE                                                               | 5        | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 1.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 1.53%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4        | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 1.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4        | 1.53%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 3        | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3        | 1.15%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 1.15%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 3        | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 3        | 1.15%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 1.15%   |
| AMD FCH IDE Controller                                                         | 3        | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 1.15%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 0.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2        | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 0.76%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2        | 0.76%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 2        | 0.76%   |
| JMicron JMB362 SATA Controller                                                 | 2        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2        | 0.76%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 0.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 0.76%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 0.76%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 102      | 51.78%  |
| IDE  | 55       | 27.92%  |
| NVMe | 26       | 13.2%   |
| RAID | 11       | 5.58%   |
| SAS  | 2        | 1.02%   |
| SCSI | 1        | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 100      | 65.36%  |
| AMD    | 52       | 33.99%  |
| ARM    | 1        | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium Dual CPU E2140 @ 1.60GHz          | 3        | 1.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 1.96%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3        | 1.96%   |
| Intel Atom CPU D525 @ 1.80GHz                   | 3        | 1.96%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 3        | 1.96%   |
| Intel Pentium D CPU 2.80GHz                     | 2        | 1.31%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 2        | 1.31%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 2        | 1.31%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2        | 1.31%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2        | 1.31%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 2        | 1.31%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2        | 1.31%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 1.31%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 2        | 1.31%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2        | 1.31%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 2        | 1.31%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 2        | 1.31%   |
| Intel Celeron CPU G3900T @ 2.60GHz              | 2        | 1.31%   |
| Intel Celeron CPU 450 @ 2.20GHz                 | 2        | 1.31%   |
| Intel Atom CPU D2550 @ 1.86GHz                  | 2        | 1.31%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 1.31%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 1.31%   |
| AMD GX-415GA SOC with Radeon HD Graphics        | 2        | 1.31%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 2        | 1.31%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.31%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 0.65%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 1        | 0.65%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 0.65%   |
| Intel Xeon CPU E5520 @ 2.27GHz                  | 1        | 0.65%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz             | 1        | 0.65%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz             | 1        | 0.65%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1        | 0.65%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 0.65%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 0.65%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 0.65%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 0.65%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 1        | 0.65%   |
| Intel N100                                      | 1        | 0.65%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 0.65%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 13.07%  |
| Intel Celeron           | 16       | 10.46%  |
| Intel Core i7           | 11       | 7.19%   |
| Intel Core i3           | 10       | 6.54%   |
| Intel Atom              | 10       | 6.54%   |
| AMD Ryzen 5             | 9        | 5.88%   |
| Intel Core 2 Duo        | 8        | 5.23%   |
| AMD Ryzen 7             | 8        | 5.23%   |
| Intel Xeon              | 6        | 3.92%   |
| AMD Athlon 64 X2        | 6        | 3.92%   |
| Other                   | 5        | 3.27%   |
| Intel Pentium Dual      | 4        | 2.61%   |
| Intel Core 2 Quad       | 4        | 2.61%   |
| Intel Pentium Dual-Core | 3        | 1.96%   |
| AMD Ryzen 9             | 3        | 1.96%   |
| AMD Phenom II X4        | 3        | 1.96%   |
| AMD FX                  | 3        | 1.96%   |
| Intel Pentium D         | 2        | 1.31%   |
| AMD Phenom II X6        | 2        | 1.31%   |
| AMD GX                  | 2        | 1.31%   |
| AMD Athlon II X2        | 2        | 1.31%   |
| AMD A8                  | 2        | 1.31%   |
| AMD A10                 | 2        | 1.31%   |
| Intel Pentium Gold      | 1        | 0.65%   |
| Intel Pentium           | 1        | 0.65%   |
| Intel Core i9           | 1        | 0.65%   |
| AMD Sempron             | 1        | 0.65%   |
| AMD Ryzen 5 PRO         | 1        | 0.65%   |
| AMD PRO A10             | 1        | 0.65%   |
| AMD Phenom II X2        | 1        | 0.65%   |
| AMD G                   | 1        | 0.65%   |
| AMD Athlon II X3        | 1        | 0.65%   |
| AMD Athlon              | 1        | 0.65%   |
| AMD A6                  | 1        | 0.65%   |
| AMD A4                  | 1        | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 56       | 36.6%   |
| 4      | 55       | 35.95%  |
| 6      | 18       | 11.76%  |
| 8      | 11       | 7.19%   |
| 1      | 7        | 4.58%   |
| 3      | 3        | 1.96%   |
| 16     | 1        | 0.65%   |
| 12     | 1        | 0.65%   |
| 10     | 1        | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 151      | 98.69%  |
| 2      | 2        | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 91       | 59.48%  |
| 2      | 62       | 40.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 152      | 99.35%  |
| Unknown        | 1        | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 57.96%  |
| 0x1067a    | 5        | 3.18%   |
| 0x906ea    | 4        | 2.55%   |
| 0x406c4    | 4        | 2.55%   |
| 0x306c3    | 3        | 1.91%   |
| 0x206a7    | 3        | 1.91%   |
| 0x106ca    | 3        | 1.91%   |
| 0x6fb      | 2        | 1.27%   |
| 0x506e3    | 2        | 1.27%   |
| 0x306a9    | 2        | 1.27%   |
| 0x30679    | 2        | 1.27%   |
| 0x0a201009 | 2        | 1.27%   |
| 0x0800820d | 2        | 1.27%   |
| 0x0700010f | 2        | 1.27%   |
| 0x06003106 | 2        | 1.27%   |
| 0x010000db | 2        | 1.27%   |
| 0xa0653    | 1        | 0.64%   |
| 0x906eb    | 1        | 0.64%   |
| 0x906c0    | 1        | 0.64%   |
| 0x706a8    | 1        | 0.64%   |
| 0x706a1    | 1        | 0.64%   |
| 0x6fd      | 1        | 0.64%   |
| 0x506ca    | 1        | 0.64%   |
| 0x506c9    | 1        | 0.64%   |
| 0x306e4    | 1        | 0.64%   |
| 0x206c2    | 1        | 0.64%   |
| 0x106a5    | 1        | 0.64%   |
| 0x10676    | 1        | 0.64%   |
| 0x10661    | 1        | 0.64%   |
| 0x0a601203 | 1        | 0.64%   |
| 0x0a50000d | 1        | 0.64%   |
| 0x0a50000c | 1        | 0.64%   |
| 0x0a50000b | 1        | 0.64%   |
| 0x08701021 | 1        | 0.64%   |
| 0x08701013 | 1        | 0.64%   |
| 0x08608103 | 1        | 0.64%   |
| 0x08001138 | 1        | 0.64%   |
| 0x06001119 | 1        | 0.64%   |
| 0x06000852 | 1        | 0.64%   |
| 0x010000dc | 1        | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 14       | 9.15%   |
| IvyBridge        | 13       | 8.5%    |
| Haswell          | 12       | 7.84%   |
| K10              | 11       | 7.19%   |
| Core             | 9        | 5.88%   |
| Zen 3            | 7        | 4.58%   |
| Silvermont       | 7        | 4.58%   |
| KabyLake         | 7        | 4.58%   |
| K8 Hammer        | 7        | 4.58%   |
| Skylake          | 6        | 3.92%   |
| Bonnell          | 6        | 3.92%   |
| Zen+             | 5        | 3.27%   |
| SandyBridge      | 5        | 3.27%   |
| Zen 2            | 4        | 2.61%   |
| Nehalem          | 4        | 2.61%   |
| CometLake        | 4        | 2.61%   |
| Unknown          | 4        | 2.61%   |
| Zen              | 3        | 1.96%   |
| Piledriver       | 3        | 1.96%   |
| Goldmont plus    | 3        | 1.96%   |
| Westmere         | 2        | 1.31%   |
| Steamroller      | 2        | 1.31%   |
| NetBurst         | 2        | 1.31%   |
| K10 Llano        | 2        | 1.31%   |
| Jaguar           | 2        | 1.31%   |
| Goldmont         | 2        | 1.31%   |
| Excavator        | 2        | 1.31%   |
| Tremont          | 1        | 0.65%   |
| Gracemont        | 1        | 0.65%   |
| Bulldozer        | 1        | 0.65%   |
| Bobcat           | 1        | 0.65%   |
| Alderlake Hybrid | 1        | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 40.51%  |
| Nvidia | 51       | 32.28%  |
| AMD    | 43       | 27.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8        | 4.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 4.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6        | 3.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 3.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 3.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.05%   |
| Nvidia GT218 [ION]                                                                       | 3        | 1.83%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 3        | 1.83%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 1.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3        | 1.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 1.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.83%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 1.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 2        | 1.22%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 2        | 1.22%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 2        | 1.22%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 2        | 1.22%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                                    | 2        | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.22%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 2        | 1.22%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 1.22%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.22%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 1.22%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.22%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 1.22%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2        | 1.22%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.22%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.22%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.61%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.61%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1        | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 60       | 39.22%  |
| 1 x Nvidia         | 48       | 31.37%  |
| 1 x AMD            | 37       | 24.18%  |
| 2 x AMD            | 3        | 1.96%   |
| AMD + Nvidia       | 2        | 1.31%   |
| Other              | 1        | 0.65%   |
| Intel + 2 x Nvidia | 1        | 0.65%   |
| Intel + 2 x AMD    | 1        | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 126      | 82.35%  |
| Proprietary | 18       | 11.76%  |
| Unknown     | 9        | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 101      | 65.58%  |
| 0.51-1.0   | 15       | 9.74%   |
| 0.01-0.5   | 15       | 9.74%   |
| 7.01-8.0   | 7        | 4.55%   |
| 1.01-2.0   | 6        | 3.9%    |
| 8.01-16.0  | 4        | 2.6%    |
| 5.01-6.0   | 3        | 1.95%   |
| 3.01-4.0   | 2        | 1.3%    |
| 2.01-3.0   | 1        | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 27       | 19.57%  |
| Dell                 | 17       | 12.32%  |
| Philips              | 10       | 7.25%   |
| Hewlett-Packard      | 10       | 7.25%   |
| Goldstar             | 10       | 7.25%   |
| Ancor Communications | 7        | 5.07%   |
| Acer                 | 7        | 5.07%   |
| Iiyama               | 3        | 2.17%   |
| Eizo                 | 3        | 2.17%   |
| ViewSonic            | 2        | 1.45%   |
| Unknown              | 2        | 1.45%   |
| Sony                 | 2        | 1.45%   |
| MSI                  | 2        | 1.45%   |
| Lenovo               | 2        | 1.45%   |
| HannStar             | 2        | 1.45%   |
| BenQ                 | 2        | 1.45%   |
| Belinea              | 2        | 1.45%   |
| AOC                  | 2        | 1.45%   |
| XKX                  | 1        | 0.72%   |
| Westinghouse         | 1        | 0.72%   |
| Vizio                | 1        | 0.72%   |
| VHT                  | 1        | 0.72%   |
| Unknown (ADA)        | 1        | 0.72%   |
| SNC                  | 1        | 0.72%   |
| Sharp                | 1        | 0.72%   |
| SFX                  | 1        | 0.72%   |
| Sceptre Tech         | 1        | 0.72%   |
| Sampo                | 1        | 0.72%   |
| RTK                  | 1        | 0.72%   |
| Positivo             | 1        | 0.72%   |
| Plain Tree Systems   | 1        | 0.72%   |
| Pixio                | 1        | 0.72%   |
| NEC Computers        | 1        | 0.72%   |
| LG Electronics       | 1        | 0.72%   |
| Jean                 | 1        | 0.72%   |
| HKC                  | 1        | 0.72%   |
| HJW                  | 1        | 0.72%   |
| FUS                  | 1        | 0.72%   |
| Daewoo               | 1        | 0.72%   |
| Compal               | 1        | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 1.39%   |
| XKX HDMI XKX3200 3840x2160 698x393mm 31.5-inch                       | 1        | 0.69%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1        | 0.69%   |
| Vizio VO370M VIZ0050 1920x1080 820x460mm 37.0-inch                   | 1        | 0.69%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.69%   |
| ViewSonic VT2342 VSC1324 1920x1080 509x286mm 23.0-inch               | 1        | 0.69%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 0.69%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 0.69%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 0.69%   |
| Unknown (ADA) LCD Monitor ADA0004 800x480 150x100mm 7.1-inch         | 1        | 0.69%   |
| Sony TV SNY9C01 1920x1080                                            | 1        | 0.69%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1        | 0.69%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 0.69%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 0.69%   |
| SFX MX0402 4K60 SFX0100 1920x1080                                    | 1        | 0.69%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch       | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch  | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0497 1600x900 443x249mm 20.0-inch  | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch  | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 480x300mm 22.3-inch | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch  | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 0.69%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 0.69%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch  | 1        | 0.69%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 0.69%   |
| Samsung Electronics SMB2430HD SAM0713 1920x1080 531x299mm 24.0-inch  | 1        | 0.69%   |
| Samsung Electronics SMB2330H SAM0649 1920x1080 509x286mm 23.0-inch   | 1        | 0.69%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 0.69%   |
| Samsung Electronics S24C450 SAM09CD 1920x1080 521x293mm 23.5-inch    | 1        | 0.69%   |
| Samsung Electronics S23C650 SAM09DE 1920x1080 510x287mm 23.0-inch    | 1        | 0.69%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 0.69%   |
| Samsung Electronics S/M 550v SAM12B6 1024x768 267x200mm 13.1-inch    | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SyncMaster                           | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 0.69%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 580x320mm 26.1-inch | 1        | 0.69%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 0.69%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 697x392mm 31.5-inch    | 1        | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 56       | 40.88%  |
| 1280x1024 (SXGA)   | 15       | 10.95%  |
| 1600x900 (HD+)     | 9        | 6.57%   |
| 1680x1050 (WSXGA+) | 8        | 5.84%   |
| 1440x900 (WXGA+)   | 8        | 5.84%   |
| 1366x768 (WXGA)    | 8        | 5.84%   |
| 3840x2160 (4K)     | 7        | 5.11%   |
| 1360x768           | 7        | 5.11%   |
| 2560x1440 (QHD)    | 6        | 4.38%   |
| 1920x1200 (WUXGA)  | 2        | 1.46%   |
| 1024x768 (XGA)     | 2        | 1.46%   |
| 800x600            | 1        | 0.73%   |
| 3440x1440          | 1        | 0.73%   |
| 3200x1200          | 1        | 0.73%   |
| 2560x1600          | 1        | 0.73%   |
| 2288x1287          | 1        | 0.73%   |
| 1280x800 (WXGA)    | 1        | 0.73%   |
| 1280x768           | 1        | 0.73%   |
| 1280x720 (HD)      | 1        | 0.73%   |
| Unknown            | 1        | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 15       | 11.11%  |
| 21      | 15       | 11.11%  |
| 19      | 15       | 11.11%  |
| 24      | 14       | 10.37%  |
| 27      | 13       | 9.63%   |
| 18      | 10       | 7.41%   |
| Unknown | 10       | 7.41%   |
| 22      | 8        | 5.93%   |
| 20      | 6        | 4.44%   |
| 17      | 6        | 4.44%   |
| 31      | 4        | 2.96%   |
| 15      | 4        | 2.96%   |
| 32      | 2        | 1.48%   |
| 142     | 1        | 0.74%   |
| 84      | 1        | 0.74%   |
| 72      | 1        | 0.74%   |
| 49      | 1        | 0.74%   |
| 47      | 1        | 0.74%   |
| 43      | 1        | 0.74%   |
| 42      | 1        | 0.74%   |
| 34      | 1        | 0.74%   |
| 26      | 1        | 0.74%   |
| 14      | 1        | 0.74%   |
| 13      | 1        | 0.74%   |
| 8       | 1        | 0.74%   |
| 7       | 1        | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 45       | 33.33%  |
| 501-600        | 42       | 31.11%  |
| 351-400        | 11       | 8.15%   |
| Unknown        | 10       | 7.41%   |
| 301-350        | 9        | 6.67%   |
| 601-700        | 5        | 3.7%    |
| 701-800        | 3        | 2.22%   |
| 1501-2000      | 2        | 1.48%   |
| 101-200        | 2        | 1.48%   |
| 1001-1500      | 2        | 1.48%   |
| 901-1000       | 2        | 1.48%   |
| More than 2000 | 1        | 0.74%   |
| 201-300        | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 87       | 66.92%  |
| 16/10   | 17       | 13.08%  |
| 5/4     | 13       | 10%     |
| Unknown | 7        | 5.38%   |
| 4/3     | 4        | 3.08%   |
| 3/2     | 1        | 0.77%   |
| 1.00    | 1        | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 31.34%  |
| 151-200        | 28       | 20.9%   |
| 301-350        | 13       | 9.7%    |
| 141-150        | 12       | 8.96%   |
| Unknown        | 10       | 7.46%   |
| 351-500        | 6        | 4.48%   |
| 251-300        | 5        | 3.73%   |
| More than 1000 | 4        | 2.99%   |
| 501-1000       | 4        | 2.99%   |
| 101-110        | 3        | 2.24%   |
| 81-90          | 2        | 1.49%   |
| 1-40           | 2        | 1.49%   |
| 131-140        | 2        | 1.49%   |
| 111-120        | 1        | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 83       | 62.41%  |
| 101-120 | 26       | 19.55%  |
| Unknown | 10       | 7.52%   |
| 1-50    | 8        | 6.02%   |
| 161-240 | 4        | 3.01%   |
| 121-160 | 2        | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 126      | 81.82%  |
| 2     | 18       | 11.69%  |
| 0     | 10       | 6.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 91       | 39.74%  |
| Intel                                 | 53       | 23.14%  |
| Qualcomm Atheros                      | 14       | 6.11%   |
| Broadcom                              | 11       | 4.8%    |
| TP-Link                               | 9        | 3.93%   |
| Nvidia                                | 9        | 3.93%   |
| Samsung Electronics                   | 4        | 1.75%   |
| Ralink Technology                     | 3        | 1.31%   |
| NetGear                               | 3        | 1.31%   |
| MediaTek                              | 3        | 1.31%   |
| VIA Technologies                      | 2        | 0.87%   |
| Ralink                                | 2        | 0.87%   |
| Qualcomm Atheros Communications       | 2        | 0.87%   |
| Broadcom Limited                      | 2        | 0.87%   |
| Belkin Components                     | 2        | 0.87%   |
| ZTopInc                               | 1        | 0.44%   |
| Xiaomi                                | 1        | 0.44%   |
| Trident Microsystems                  | 1        | 0.44%   |
| TRENDnet                              | 1        | 0.44%   |
| Texas Instruments                     | 1        | 0.44%   |
| Seeed Technology                      | 1        | 0.44%   |
| OPPO Electronics                      | 1        | 0.44%   |
| Motorola                              | 1        | 0.44%   |
| Mellanox Technologies                 | 1        | 0.44%   |
| Marvell Technology Group              | 1        | 0.44%   |
| Linksys                               | 1        | 0.44%   |
| ICS Advent                            | 1        | 0.44%   |
| Hangzhou Silan Microelectronics       | 1        | 0.44%   |
| Edimax Technology                     | 1        | 0.44%   |
| D-Link                                | 1        | 0.44%   |
| BUFFALO                               | 1        | 0.44%   |
| ASUSTek Computer                      | 1        | 0.44%   |
| Accton Technology                     | 1        | 0.44%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 75       | 29.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 9        | 3.57%   |
| Nvidia MCP61 Ethernet                                                             | 6        | 2.38%   |
| Intel I211 Gigabit Network Connection                                             | 6        | 2.38%   |
| Intel Ethernet Connection I217-LM                                                 | 6        | 2.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 5        | 1.98%   |
| Intel Ethernet Controller I225-V                                                  | 5        | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 4        | 1.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 3        | 1.19%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 3        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 3        | 1.19%   |
| Intel Wi-Fi 6 AX200                                                               | 3        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                              | 3        | 1.19%   |
| Intel 82567LM-3 Gigabit Network Connection                                        | 3        | 1.19%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                  | 3        | 1.19%   |
| VIA VT6102/VT6103 [Rhine-II]                                                      | 2        | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 2        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 2        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 2        | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 2        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                         | 2        | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 2        | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                          | 2        | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                    | 2        | 0.79%   |
| Nvidia MCP77 Ethernet                                                             | 2        | 0.79%   |
| NetGear A6210                                                                     | 2        | 0.79%   |
| Intel NM10/ICH7 Family LAN Controller                                             | 2        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 0.79%   |
| Intel 82574L Gigabit Network Connection                                           | 2        | 0.79%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                      | 2        | 0.79%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller               | 2        | 0.79%   |
| ZTopInc 802.11n NIC                                                               | 1        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                              | 1        | 0.4%    |
| Trident Microsystems 4DWave DX                                                    | 1        | 0.4%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                   | 1        | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.4%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                             | 1        | 0.4%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                            | 1        | 0.4%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                               | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 19       | 25%     |
| Intel                                 | 14       | 18.42%  |
| TP-Link                               | 8        | 10.53%  |
| Qualcomm Atheros                      | 7        | 9.21%   |
| Broadcom                              | 5        | 6.58%   |
| Ralink Technology                     | 3        | 3.95%   |
| MediaTek                              | 3        | 3.95%   |
| Ralink                                | 2        | 2.63%   |
| Qualcomm Atheros Communications       | 2        | 2.63%   |
| NetGear                               | 2        | 2.63%   |
| Belkin Components                     | 2        | 2.63%   |
| ZTopInc                               | 1        | 1.32%   |
| TRENDnet                              | 1        | 1.32%   |
| Linksys                               | 1        | 1.32%   |
| Edimax Technology                     | 1        | 1.32%   |
| D-Link                                | 1        | 1.32%   |
| BUFFALO                               | 1        | 1.32%   |
| Broadcom Limited                      | 1        | 1.32%   |
| ASUSTek Computer                      | 1        | 1.32%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 5        | 6.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                      | 3        | 3.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                            | 3        | 3.9%    |
| Intel Wi-Fi 6 AX200                                                               | 3        | 3.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 2        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 2        | 2.6%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 2        | 2.6%    |
| NetGear A6210                                                                     | 2        | 2.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 2.6%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                      | 2        | 2.6%    |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller               | 2        | 2.6%    |
| ZTopInc 802.11n NIC                                                               | 1        | 1.3%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 1.3%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 1.3%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                             | 1        | 1.3%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                            | 1        | 1.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                               | 1        | 1.3%    |
| TP-Link 802.11ac NIC                                                              | 1        | 1.3%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.3%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                        | 1        | 1.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                   | 1        | 1.3%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                            | 1        | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 1        | 1.3%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 1.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 1.3%    |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 1.3%    |
| Realtek 802.11ax WLAN Adapter                                                     | 1        | 1.3%    |
| Realtek 802.11ac NIC                                                              | 1        | 1.3%    |
| Ralink RT5572 Wireless Adapter                                                    | 1        | 1.3%    |
| Ralink RT5370 Wireless Adapter                                                    | 1        | 1.3%    |
| Ralink MT7601U Wireless Adapter                                                   | 1        | 1.3%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.3%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                              | 1        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 1        | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                    | 1        | 1.3%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                  | 1        | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                     | 1        | 1.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                           | 1        | 1.3%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 84       | 50.3%   |
| Intel                           | 42       | 25.15%  |
| Qualcomm Atheros                | 9        | 5.39%   |
| Nvidia                          | 9        | 5.39%   |
| Broadcom                        | 6        | 3.59%   |
| Samsung Electronics             | 4        | 2.4%    |
| VIA Technologies                | 2        | 1.2%    |
| Xiaomi                          | 1        | 0.6%    |
| Trident Microsystems            | 1        | 0.6%    |
| TP-Link                         | 1        | 0.6%    |
| OPPO Electronics                | 1        | 0.6%    |
| NetGear                         | 1        | 0.6%    |
| Mellanox Technologies           | 1        | 0.6%    |
| Marvell Technology Group        | 1        | 0.6%    |
| ICS Advent                      | 1        | 0.6%    |
| Hangzhou Silan Microelectronics | 1        | 0.6%    |
| Broadcom Limited                | 1        | 0.6%    |
| Accton Technology               | 1        | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75       | 43.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9        | 5.23%   |
| Nvidia MCP61 Ethernet                                                  | 6        | 3.49%   |
| Intel I211 Gigabit Network Connection                                  | 6        | 3.49%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 3.49%   |
| Intel Ethernet Controller I225-V                                       | 5        | 2.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.74%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.74%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 3        | 1.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2        | 1.16%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2        | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2        | 1.16%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 1.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 1.16%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2        | 1.16%   |
| Nvidia MCP77 Ethernet                                                  | 2        | 1.16%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 2        | 1.16%   |
| Intel 82574L Gigabit Network Connection                                | 2        | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.58%   |
| Trident Microsystems 4DWave DX                                         | 1        | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1        | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1        | 0.58%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.58%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.58%   |
| OPPO RMX3741                                                           | 1        | 0.58%   |
| Nvidia MCP55 Ethernet                                                  | 1        | 0.58%   |
| NetGear LB1120-100NAS                                                  | 1        | 0.58%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                  | 1        | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.58%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.58%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.58%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 0.58%   |
| Intel Ethernet Connection (12) I219-V                                  | 1        | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 150      | 67.57%  |
| WiFi     | 69       | 31.08%  |
| Modem    | 3        | 1.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 70.7%   |
| WiFi     | 46       | 29.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 104      | 67.97%  |
| 2     | 37       | 24.18%  |
| 3     | 8        | 5.23%   |
| 0     | 3        | 1.96%   |
| 4     | 1        | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 107      | 69.93%  |
| Yes  | 46       | 30.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 38.89%  |
| Cambridge Silicon Radio         | 7        | 19.44%  |
| Realtek Semiconductor           | 3        | 8.33%   |
| Qualcomm Atheros Communications | 3        | 8.33%   |
| TP-Link                         | 2        | 5.56%   |
| MediaTek                        | 2        | 5.56%   |
| Foxconn / Hon Hai               | 2        | 5.56%   |
| Logitech                        | 1        | 2.78%   |
| Broadcom                        | 1        | 2.78%   |
| ASUSTek Computer                | 1        | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 18.92%  |
| Intel AX200 Bluetooth                                 | 3        | 8.11%   |
| TP-Link TP-T@- UB500 Adapter                          | 2        | 5.41%   |
| Realtek Bluetooth Radio                               | 2        | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 5.41%   |
| MediaTek Wireless_Device                              | 2        | 5.41%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 5.41%   |
| Intel Bluetooth wireless interface                    | 2        | 5.41%   |
| Intel Bluetooth Device                                | 2        | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 5.41%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 2.7%    |
| Realtek Bluetooth 5.3 Radio                           | 1        | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 2.7%    |
| Logitech BT Mini-Receiver (HCI mode)                  | 1        | 2.7%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.7%    |
| Intel AX210 Bluetooth                                 | 1        | 2.7%    |
| Intel AX201 Bluetooth                                 | 1        | 2.7%    |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 2.7%    |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 2.7%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 93       | 42.86%  |
| AMD                                          | 51       | 23.5%   |
| Nvidia                                       | 42       | 19.35%  |
| C-Media Electronics                          | 6        | 2.76%   |
| VIA Technologies                             | 3        | 1.38%   |
| Texas Instruments                            | 3        | 1.38%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.92%   |
| Razer USA                                    | 2        | 0.92%   |
| JMTek                                        | 2        | 0.92%   |
| GN Netcom                                    | 2        | 0.92%   |
| ASUSTek Computer                             | 2        | 0.92%   |
| Sony                                         | 1        | 0.46%   |
| Plantronics                                  | 1        | 0.46%   |
| Microsoft                                    | 1        | 0.46%   |
| Micro Star International                     | 1        | 0.46%   |
| Kingston Technology                          | 1        | 0.46%   |
| Fujitsu Connected Technologies Limited       | 1        | 0.46%   |
| Focusrite-Novation                           | 1        | 0.46%   |
| Ensoniq                                      | 1        | 0.46%   |
| Creative Labs                                | 1        | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 20       | 7.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10       | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 10       | 3.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 10       | 3.94%   |
| Nvidia High Definition Audio Controller                                           | 9        | 3.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 3.15%   |
| AMD Ryzen HD Audio Controller                                                     | 8        | 3.15%   |
| AMD FCH Azalia Controller                                                         | 8        | 3.15%   |
| Nvidia MCP61 High Definition Audio                                                | 7        | 2.76%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 2.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 2.36%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 1.97%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 5        | 1.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 1.97%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 1.57%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                          | 4        | 1.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.57%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.18%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 1.18%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 3        | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 3        | 1.18%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 3        | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.18%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 3        | 1.18%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2        | 0.79%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                | 2        | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 20       | 18.35%  |
| Kingston            | 15       | 13.76%  |
| Samsung Electronics | 12       | 11.01%  |
| Micron Technology   | 11       | 10.09%  |
| SK hynix            | 10       | 9.17%   |
| Crucial             | 7        | 6.42%   |
| Corsair             | 7        | 6.42%   |
| G.Skill             | 6        | 5.5%    |
| Unknown             | 5        | 4.59%   |
| Unknown (ABCD)      | 3        | 2.75%   |
| Patriot             | 2        | 1.83%   |
| Nanya Technology    | 2        | 1.83%   |
| A-DATA Technology   | 2        | 1.83%   |
| Unknown (AB)        | 1        | 0.92%   |
| Unifosa             | 1        | 0.92%   |
| Smart               | 1        | 0.92%   |
| PUSKILL             | 1        | 0.92%   |
| PNY                 | 1        | 0.92%   |
| GOODRAM             | 1        | 0.92%   |
| Elpida              | 1        | 0.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 5        | 4.1%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 3        | 2.46%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 1.64%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2        | 1.64%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 2        | 1.64%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 2        | 1.64%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s            | 2        | 1.64%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 2        | 1.64%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.82%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s                     | 1        | 0.82%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                     | 1        | 0.82%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 1        | 0.82%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                       | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 0.82%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 1        | 0.82%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s       | 1        | 0.82%   |
| Unknown (AB) RAM Module 1GB DIMM LPDDR4 1600MT/s               | 1        | 0.82%   |
| Unifosa RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 0.82%   |
| Smart RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 3200MT/s          | 1        | 0.82%   |
| SK hynix RAM Module 8GB DIMM DDR3                              | 1        | 0.82%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 0.82%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                     | 1        | 0.82%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 1        | 0.82%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2666MT/s                  | 1        | 0.82%   |
| SK hynix RAM HMT451S6BFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.82%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 1        | 0.82%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.82%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.82%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 0.82%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 1        | 0.82%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s            | 1        | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 37       | 36.63%  |
| DDR4    | 34       | 33.66%  |
| DDR2    | 12       | 11.88%  |
| SDRAM   | 6        | 5.94%   |
| Unknown | 6        | 5.94%   |
| LPDDR4  | 3        | 2.97%   |
| LPDDR5  | 1        | 0.99%   |
| DDR5    | 1        | 0.99%   |
| DDR     | 1        | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 82       | 82.83%  |
| SODIMM       | 16       | 16.16%  |
| Row Of Chips | 1        | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 28.83%  |
| 4096  | 31       | 27.93%  |
| 2048  | 22       | 19.82%  |
| 16384 | 13       | 11.71%  |
| 1024  | 6        | 5.41%   |
| 32768 | 5        | 4.5%    |
| 3072  | 1        | 0.9%    |
| 512   | 1        | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 22.22%  |
| 1333    | 14       | 12.96%  |
| 3200    | 10       | 9.26%   |
| 2667    | 7        | 6.48%   |
| 800     | 7        | 6.48%   |
| 2400    | 6        | 5.56%   |
| 667     | 5        | 4.63%   |
| 2133    | 4        | 3.7%    |
| 1866    | 4        | 3.7%    |
| 1066    | 4        | 3.7%    |
| Unknown | 4        | 3.7%    |
| 3600    | 3        | 2.78%   |
| 3400    | 3        | 2.78%   |
| 3066    | 2        | 1.85%   |
| 2666    | 2        | 1.85%   |
| 6400    | 1        | 0.93%   |
| 4800    | 1        | 0.93%   |
| 4000    | 1        | 0.93%   |
| 3933    | 1        | 0.93%   |
| 3666    | 1        | 0.93%   |
| 2800    | 1        | 0.93%   |
| 2048    | 1        | 0.93%   |
| 533     | 1        | 0.93%   |
| 333     | 1        | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Brother Industries       | 3        | 33.33%  |
| Canon                    | 2        | 22.22%  |
| Zhuhai Poskey Technology | 1        | 11.11%  |
| STMicroelectronics       | 1        | 11.11%  |
| Samsung Electronics      | 1        | 11.11%  |
| Hewlett-Packard          | 1        | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Zhuhai Poskey Z1                                          | 1        | 11.11%  |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 11.11%  |
| Samsung SCX-4200 series                                   | 1        | 11.11%  |
| HP DeskJet 6980 series                                    | 1        | 11.11%  |
| Canon PIXMA MP250                                         | 1        | 11.11%  |
| Canon LiDE 300                                            | 1        | 11.11%  |
| Brother HL-L2380DW                                        | 1        | 11.11%  |
| Brother HL-2230 series                                    | 1        | 11.11%  |
| Brother DCP-7055W                                         | 1        | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Seiko Epson    | 1        | 50%     |
| Mustek Systems | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1        | 50%     |
| Mustek Systems ScanExpress A3 USB             | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Logitech                       | 9        | 60%     |
| WaveRider Communications       | 1        | 6.67%   |
| Santa Barbara Instrument Group | 1        | 6.67%   |
| Pixart Imaging                 | 1        | 6.67%   |
| Microsoft                      | 1        | 6.67%   |
| Generalplus Technology         | 1        | 6.67%   |
| AVerMedia Technologies         | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                 | 3        | 20%     |
| WaveRider USB Live camera                                            | 1        | 6.67%   |
| Santa Barbara Instrument Group SBIG Astronomy Camera (with firmware) | 1        | 6.67%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                 | 1        | 6.67%   |
| Microsoft LifeCam VX-800                                             | 1        | 6.67%   |
| Logitech Webcam C170                                                 | 1        | 6.67%   |
| Logitech Webcam C120                                                 | 1        | 6.67%   |
| Logitech QuickCam Ultra Vision                                       | 1        | 6.67%   |
| Logitech HD Webcam C615                                              | 1        | 6.67%   |
| Logitech HD Webcam C510                                              | 1        | 6.67%   |
| Logitech HD Pro Webcam C920                                          | 1        | 6.67%   |
| Generalplus 808 Camera #9 (web-cam mode)                             | 1        | 6.67%   |
| AVerMedia Live Streamer CAM 313                                      | 1        | 6.67%   |

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


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Cherry | 2        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Cherry SmartCard Reader Keyboard KC 1000 SC | 2        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 130      | 83.87%  |
| 1     | 22       | 14.19%  |
| 2     | 3        | 1.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 37.04%  |
| Net/wireless             | 8        | 29.63%  |
| Unassigned class         | 2        | 7.41%   |
| Net/ethernet             | 2        | 7.41%   |
| Communication controller | 2        | 7.41%   |
| Storage/raid             | 1        | 3.7%    |
| Sound                    | 1        | 3.7%    |
| Modem                    | 1        | 3.7%    |

