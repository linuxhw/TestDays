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

Total: 167

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-43-generic | 10       | 7.25%   |
| 6.5.0-14-generic  | 5        | 3.62%   |
| 5.19.0-50-generic | 5        | 3.62%   |
| 5.19.0-32-generic | 5        | 3.62%   |
| 5.15.0-60-generic | 5        | 3.62%   |
| 5.15.0-41-generic | 5        | 3.62%   |
| 5.15.0-56-generic | 4        | 2.9%    |
| 5.15.0-47-generic | 4        | 2.9%    |
| 5.15.0-25-generic | 4        | 2.9%    |
| 6.5.0-27-generic  | 3        | 2.17%   |
| 5.15.0-91-generic | 3        | 2.17%   |
| 5.15.0-75-generic | 3        | 2.17%   |
| 5.15.0-67-generic | 3        | 2.17%   |
| 5.15.0-52-generic | 3        | 2.17%   |
| 5.15.0-48-generic | 3        | 2.17%   |
| 5.15.0-40-generic | 3        | 2.17%   |
| 5.15.0-39-generic | 3        | 2.17%   |
| 6.5.0-28-generic  | 2        | 1.45%   |
| 6.2.0-36-generic  | 2        | 1.45%   |
| 6.2.0-35-generic  | 2        | 1.45%   |
| 6.2.0-26-generic  | 2        | 1.45%   |
| 5.19.0-46-generic | 2        | 1.45%   |
| 5.19.0-43-generic | 2        | 1.45%   |
| 5.19.0-35-generic | 2        | 1.45%   |
| 5.15.0-94-generic | 2        | 1.45%   |
| 5.15.0-89-generic | 2        | 1.45%   |
| 5.15.0-86-generic | 2        | 1.45%   |
| 5.15.0-83-generic | 2        | 1.45%   |
| 5.15.0-82-generic | 2        | 1.45%   |
| 5.15.0-58-generic | 2        | 1.45%   |
| 5.15.0-53-generic | 2        | 1.45%   |
| 5.15.0-50-generic | 2        | 1.45%   |
| 5.15.0-46-generic | 2        | 1.45%   |
| 5.15.0-35-generic | 2        | 1.45%   |
| 5.15.0-30-generic | 2        | 1.45%   |
| 5.15.0-27-generic | 2        | 1.45%   |
| 6.7.0-custom      | 1        | 0.72%   |
| 6.6.0-custom      | 1        | 0.72%   |
| 6.5.0-26-generic  | 1        | 0.72%   |
| 6.5.0-17-generic  | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 82       | 63.08%  |
| 5.19.0  | 19       | 14.62%  |
| 6.5.0   | 13       | 10%     |
| 6.2.0   | 8        | 6.15%   |
| 6.7.0   | 1        | 0.77%   |
| 6.6.0   | 1        | 0.77%   |
| 6.3.3   | 1        | 0.77%   |
| 6.2.8   | 1        | 0.77%   |
| 6.1.46  | 1        | 0.77%   |
| 6.1.0   | 1        | 0.77%   |
| 6.0.8   | 1        | 0.77%   |
| 6.0.14  | 1        | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 82       | 63.08%  |
| 5.19    | 19       | 14.62%  |
| 6.5     | 13       | 10%     |
| 6.2     | 9        | 6.92%   |
| 6.1     | 2        | 1.54%   |
| 6.0     | 2        | 1.54%   |
| 6.7     | 1        | 0.77%   |
| 6.6     | 1        | 0.77%   |
| 6.3     | 1        | 0.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 123      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LXQt    | 117      | 95.12%  |
| LXDE    | 3        | 2.44%   |
| XFCE    | 1        | 0.81%   |
| ratflow | 1        | 0.81%   |
| GNOME   | 1        | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 116      | 92.06%  |
| Tty         | 8        | 6.35%   |
| Wayland     | 1        | 0.79%   |
| Unspecified | 1        | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 99       | 80.49%  |
| LightDM | 9        | 7.32%   |
| Unknown | 8        | 6.5%    |
| GDM3    | 3        | 2.44%   |
| LXDM    | 2        | 1.63%   |
| XDM     | 1        | 0.81%   |
| SLiM    | 1        | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 38       | 30.65%  |
| fr_FR | 18       | 14.52%  |
| de_DE | 10       | 8.06%   |
| es_ES | 7        | 5.65%   |
| en_GB | 7        | 5.65%   |
| it_IT | 6        | 4.84%   |
| es_AR | 5        | 4.03%   |
| pt_BR | 4        | 3.23%   |
| en_AU | 3        | 2.42%   |
| C     | 3        | 2.42%   |
| zh_TW | 2        | 1.61%   |
| pl_PL | 2        | 1.61%   |
| es_MX | 2        | 1.61%   |
| es_CR | 2        | 1.61%   |
| tr_TR | 1        | 0.81%   |
| sv_SE | 1        | 0.81%   |
| ru_UA | 1        | 0.81%   |
| ru_RU | 1        | 0.81%   |
| nl_BE | 1        | 0.81%   |
| fi_FI | 1        | 0.81%   |
| es_VE | 1        | 0.81%   |
| es_PE | 1        | 0.81%   |
| es_CU | 1        | 0.81%   |
| en_SG | 1        | 0.81%   |
| en_CA | 1        | 0.81%   |
| en_AG | 1        | 0.81%   |
| el_GR | 1        | 0.81%   |
| cv_RU | 1        | 0.81%   |
| cs_CZ | 1        | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 87       | 70.16%  |
| EFI  | 37       | 29.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 107      | 85.6%   |
| Tmpfs   | 12       | 9.6%    |
| Overlay | 3        | 2.4%    |
| Btrfs   | 2        | 1.6%    |
| XXX4    | 1        | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 60       | 48.39%  |
| MBR     | 41       | 33.06%  |
| Unknown | 23       | 18.55%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 79.2%   |
| Yes       | 26       | 20.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 63.41%  |
| Yes       | 45       | 36.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 24       | 19.51%  |
| MSI                 | 17       | 13.82%  |
| Dell                | 17       | 13.82%  |
| ASRock              | 10       | 8.13%   |
| Hewlett-Packard     | 7        | 5.69%   |
| Gigabyte Technology | 7        | 5.69%   |
| Unknown             | 6        | 4.88%   |
| Pegatron            | 4        | 3.25%   |
| Acer                | 4        | 3.25%   |
| Intel               | 3        | 2.44%   |
| Positivo            | 2        | 1.63%   |
| Lenovo              | 2        | 1.63%   |
| Fujitsu             | 2        | 1.63%   |
| AMI                 | 2        | 1.63%   |
| ZOTAC               | 1        | 0.81%   |
| YANYU               | 1        | 0.81%   |
| Shuttle             | 1        | 0.81%   |
| Seeed Studio        | 1        | 0.81%   |
| PELADN              | 1        | 0.81%   |
| PCChips             | 1        | 0.81%   |
| NEC Computers       | 1        | 0.81%   |
| Inventec            | 1        | 0.81%   |
| IceWhale Technology | 1        | 0.81%   |
| Foxconn             | 1        | 0.81%   |
| eMachines           | 1        | 0.81%   |
| ECS                 | 1        | 0.81%   |
| Biostar             | 1        | 0.81%   |
| BANGHO              | 1        | 0.81%   |
| Apple               | 1        | 0.81%   |
| AAEON               | 1        | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 6        | 4.88%   |
| MSI MS-7C37                          | 3        | 2.44%   |
| MSI MS-7309                          | 2        | 1.63%   |
| Dell Dimension 9100                  | 2        | 1.63%   |
| ZOTAC NM10                           | 1        | 0.81%   |
| YANYU ITX-S192                       | 1        | 0.81%   |
| Shuttle XS35V3                       | 1        | 0.81%   |
| Seeed Studio ODYSSEY-X86J4125        | 1        | 0.81%   |
| Positivo POS-AG31AP                  | 1        | 0.81%   |
| Positivo P5VD2-MX                    | 1        | 0.81%   |
| PELADN HA-3                          | 1        | 0.81%   |
| Pegatron NC689AA-ABA s3700y          | 1        | 0.81%   |
| Pegatron h8-1350ef                   | 1        | 0.81%   |
| Pegatron Compaq dx2400 Microtower PC | 1        | 0.81%   |
| Pegatron AY748AA-ABA p6320y          | 1        | 0.81%   |
| PCChips P49G                         | 1        | 0.81%   |
| NEC Computers ECS-945G               | 1        | 0.81%   |
| MSI MS-7D54                          | 1        | 0.81%   |
| MSI MS-7D09                          | 1        | 0.81%   |
| MSI MS-7C96                          | 1        | 0.81%   |
| MSI MS-7C56                          | 1        | 0.81%   |
| MSI MS-7C51                          | 1        | 0.81%   |
| MSI MS-7B86                          | 1        | 0.81%   |
| MSI MS-7B33                          | 1        | 0.81%   |
| MSI MS-7978                          | 1        | 0.81%   |
| MSI MS-7641                          | 1        | 0.81%   |
| MSI MS-7501                          | 1        | 0.81%   |
| MSI MS-7267                          | 1        | 0.81%   |
| MSI MS-7032                          | 1        | 0.81%   |
| Lenovo ThinkCentre M83 10ANCTO1WW    | 1        | 0.81%   |
| Lenovo ThinkCentre M600 10KGS09S00   | 1        | 0.81%   |
| Inventec DQ Class                    | 1        | 0.81%   |
| Intel X79 V2.72A                     | 1        | 0.81%   |
| Intel H61                            | 1        | 0.81%   |
| Intel BTC-T37                        | 1        | 0.81%   |
| IceWhale ZimaBoard 216 ZMB           | 1        | 0.81%   |
| HP Z400 Workstation                  | 1        | 0.81%   |
| HP t620 Quad Core TC                 | 1        | 0.81%   |
| HP Slim Desktop S01-pF1xxx           | 1        | 0.81%   |
| HP EliteDesk 705 G3 SFF              | 1        | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 6        | 4.88%   |
| Unknown                       | 6        | 4.88%   |
| ASUS PRIME                    | 4        | 3.25%   |
| MSI MS-7C37                   | 3        | 2.44%   |
| HP Compaq                     | 3        | 2.44%   |
| Dell Precision                | 3        | 2.44%   |
| ASUS ROG                      | 3        | 2.44%   |
| MSI MS-7309                   | 2        | 1.63%   |
| Lenovo ThinkCentre            | 2        | 1.63%   |
| Dell Vostro                   | 2        | 1.63%   |
| Dell Inspiron                 | 2        | 1.63%   |
| Dell Dimension                | 2        | 1.63%   |
| Acer Veriton                  | 2        | 1.63%   |
| ZOTAC NM10                    | 1        | 0.81%   |
| YANYU ITX-S192                | 1        | 0.81%   |
| Shuttle XS35V3                | 1        | 0.81%   |
| Seeed Studio ODYSSEY-X86J4125 | 1        | 0.81%   |
| Positivo POS-AG31AP           | 1        | 0.81%   |
| Positivo P5VD2-MX             | 1        | 0.81%   |
| PELADN HA-3                   | 1        | 0.81%   |
| Pegatron NC689AA-ABA          | 1        | 0.81%   |
| Pegatron h8-1350ef            | 1        | 0.81%   |
| Pegatron Compaq               | 1        | 0.81%   |
| Pegatron AY748AA-ABA          | 1        | 0.81%   |
| PCChips P49G                  | 1        | 0.81%   |
| NEC Computers ECS-945G        | 1        | 0.81%   |
| MSI MS-7D54                   | 1        | 0.81%   |
| MSI MS-7D09                   | 1        | 0.81%   |
| MSI MS-7C96                   | 1        | 0.81%   |
| MSI MS-7C56                   | 1        | 0.81%   |
| MSI MS-7C51                   | 1        | 0.81%   |
| MSI MS-7B86                   | 1        | 0.81%   |
| MSI MS-7B33                   | 1        | 0.81%   |
| MSI MS-7978                   | 1        | 0.81%   |
| MSI MS-7641                   | 1        | 0.81%   |
| MSI MS-7501                   | 1        | 0.81%   |
| MSI MS-7267                   | 1        | 0.81%   |
| MSI MS-7032                   | 1        | 0.81%   |
| Inventec DQ                   | 1        | 0.81%   |
| Intel X79                     | 1        | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 12       | 9.76%   |
| 2009 | 11       | 8.94%   |
| 2017 | 10       | 8.13%   |
| 2008 | 10       | 8.13%   |
| 2012 | 9        | 7.32%   |
| 2019 | 8        | 6.5%    |
| 2011 | 8        | 6.5%    |
| 2020 | 7        | 5.69%   |
| 2018 | 7        | 5.69%   |
| 2014 | 6        | 4.88%   |
| 2021 | 5        | 4.07%   |
| 2015 | 5        | 4.07%   |
| 2007 | 5        | 4.07%   |
| 2006 | 5        | 4.07%   |
| 2022 | 4        | 3.25%   |
| 2013 | 4        | 3.25%   |
| 2023 | 3        | 2.44%   |
| 2016 | 3        | 2.44%   |
| 2001 | 1        | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 123      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 121      | 98.37%  |
| Enabled  | 2        | 1.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 123      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 24       | 19.2%   |
| 4.01-8.0    | 23       | 18.4%   |
| 16.01-24.0  | 19       | 15.2%   |
| 8.01-16.0   | 18       | 14.4%   |
| 32.01-64.0  | 15       | 12%     |
| 1.01-2.0    | 15       | 12%     |
| 64.01-256.0 | 4        | 3.2%    |
| 2.01-3.0    | 3        | 2.4%    |
| 0.51-1.0    | 3        | 2.4%    |
| 24.01-32.0  | 1        | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 50       | 38.46%  |
| 2.01-3.0  | 29       | 22.31%  |
| 0.51-1.0  | 25       | 19.23%  |
| 4.01-8.0  | 16       | 12.31%  |
| 3.01-4.0  | 4        | 3.08%   |
| 8.01-16.0 | 4        | 3.08%   |
| 0.01-0.5  | 2        | 1.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 59       | 47.97%  |
| 2      | 39       | 31.71%  |
| 3      | 12       | 9.76%   |
| 4      | 5        | 4.07%   |
| 5      | 4        | 3.25%   |
| 12     | 1        | 0.81%   |
| 7      | 1        | 0.81%   |
| 6      | 1        | 0.81%   |
| 0      | 1        | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 61.11%  |
| Yes       | 49       | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 98.37%  |
| No        | 2        | 1.63%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 55.28%  |
| Yes       | 55       | 44.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 77.6%   |
| Yes       | 28       | 22.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 24       | 19.51%  |
| France     | 18       | 14.63%  |
| Germany    | 11       | 8.94%   |
| Spain      | 8        | 6.5%    |
| Brazil     | 7        | 5.69%   |
| Poland     | 6        | 4.88%   |
| Italy      | 6        | 4.88%   |
| UK         | 5        | 4.07%   |
| Argentina  | 5        | 4.07%   |
| Australia  | 3        | 2.44%   |
| Venezuela  | 2        | 1.63%   |
| Sweden     | 2        | 1.63%   |
| Iran       | 2        | 1.63%   |
| Costa Rica | 2        | 1.63%   |
| Ukraine    | 1        | 0.81%   |
| Turkey     | 1        | 0.81%   |
| Taiwan     | 1        | 0.81%   |
| Slovakia   | 1        | 0.81%   |
| Serbia     | 1        | 0.81%   |
| Russia     | 1        | 0.81%   |
| Romania    | 1        | 0.81%   |
| Peru       | 1        | 0.81%   |
| Pakistan   | 1        | 0.81%   |
| Mexico     | 1        | 0.81%   |
| Malaysia   | 1        | 0.81%   |
| Luxembourg | 1        | 0.81%   |
| Latvia     | 1        | 0.81%   |
| Ireland    | 1        | 0.81%   |
| Indonesia  | 1        | 0.81%   |
| Greece     | 1        | 0.81%   |
| Finland    | 1        | 0.81%   |
| Czechia    | 1        | 0.81%   |
| Cuba       | 1        | 0.81%   |
| Canada     | 1        | 0.81%   |
| Bulgaria   | 1        | 0.81%   |
| Belgium    | 1        | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 2.33%   |
| Warsaw                 | 2        | 1.55%   |
| Tehran                 | 2        | 1.55%   |
| Sao Paulo              | 2        | 1.55%   |
| Melbourne              | 2        | 1.55%   |
| Largo                  | 2        | 1.55%   |
| Karlstad               | 2        | 1.55%   |
| Heredia                | 2        | 1.55%   |
| Chicago                | 2        | 1.55%   |
| Yaroslavl              | 1        | 0.78%   |
| Woking                 | 1        | 0.78%   |
| Wetteren               | 1        | 0.78%   |
| Washington             | 1        | 0.78%   |
| Vordorf                | 1        | 0.78%   |
| Villingen-Schwenningen | 1        | 0.78%   |
| Villa Ballester        | 1        | 0.78%   |
| Versailles             | 1        | 0.78%   |
| Varna                  | 1        | 0.78%   |
| Valentigney            | 1        | 0.78%   |
| Valencia               | 1        | 0.78%   |
| Tychy                  | 1        | 0.78%   |
| Turin                  | 1        | 0.78%   |
| Torrejón de Ardoz     | 1        | 0.78%   |
| Tandil                 | 1        | 0.78%   |
| Taipei                 | 1        | 0.78%   |
| St Louis               | 1        | 0.78%   |
| Sonico                 | 1        | 0.78%   |
| Sarcelles              | 1        | 0.78%   |
| Sao José dos Campos   | 1        | 0.78%   |
| Santomera              | 1        | 0.78%   |
| Saltsjoe-Boo           | 1        | 0.78%   |
| Riverenert             | 1        | 0.78%   |
| Rio Segundo            | 1        | 0.78%   |
| Richmond               | 1        | 0.78%   |
| Resistencia            | 1        | 0.78%   |
| Prague                 | 1        | 0.78%   |
| Port Washington        | 1        | 0.78%   |
| Ponta Grossa           | 1        | 0.78%   |
| Poitiers               | 1        | 0.78%   |
| Perth                  | 1        | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Seagate                      | 35       | 48     | 17.33%  |
| WDC                          | 31       | 47     | 15.35%  |
| Samsung Electronics          | 29       | 42     | 14.36%  |
| Kingston                     | 15       | 22     | 7.43%   |
| Hitachi                      | 15       | 20     | 7.43%   |
| SanDisk                      | 8        | 9      | 3.96%   |
| Unknown                      | 5        | 5      | 2.48%   |
| Crucial                      | 5        | 5      | 2.48%   |
| Toshiba                      | 4        | 7      | 1.98%   |
| HGST                         | 4        | 4      | 1.98%   |
| Apacer                       | 3        | 3      | 1.49%   |
| A-DATA Technology            | 3        | 3      | 1.49%   |
| PNY                          | 2        | 2      | 0.99%   |
| Patriot                      | 2        | 2      | 0.99%   |
| Micron Technology            | 2        | 2      | 0.99%   |
| Maxtor                       | 2        | 2      | 0.99%   |
| GOODRAM                      | 2        | 2      | 0.99%   |
| China                        | 2        | 2      | 0.99%   |
| BR                           | 2        | 3      | 0.99%   |
| Apple                        | 2        | 2      | 0.99%   |
| XrayDisk                     | 1        | 1      | 0.5%    |
| WD MediaMax                  | 1        | 1      | 0.5%    |
| Transcend                    | 1        | 2      | 0.5%    |
| TO Exter                     | 1        | 1      | 0.5%    |
| Team                         | 1        | 1      | 0.5%    |
| T-FORCE                      | 1        | 1      | 0.5%    |
| Silicon Motion               | 1        | 1      | 0.5%    |
| Shenzhen Longsys Electronics | 1        | 2      | 0.5%    |
| RSH-319                      | 1        | 1      | 0.5%    |
| Phison                       | 1        | 1      | 0.5%    |
| OWC                          | 1        | 1      | 0.5%    |
| Micron/Crucial Technology    | 1        | 2      | 0.5%    |
| LITEONIT                     | 1        | 1      | 0.5%    |
| Kston                        | 1        | 3      | 0.5%    |
| Kingston Technology Company  | 1        | 1      | 0.5%    |
| KINGBANK                     | 1        | 3      | 0.5%    |
| Intenso                      | 1        | 1      | 0.5%    |
| Intel                        | 1        | 1      | 0.5%    |
| HGST HUS                     | 1        | 2      | 0.5%    |
| Gigabyte Technology          | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 6        | 2.62%   |
| Kingston SA400S37240G 240GB SSD    | 6        | 2.62%   |
| Toshiba DT01ACA100 1TB             | 3        | 1.31%   |
| Samsung SSD 870 EVO 500GB          | 3        | 1.31%   |
| Kingston SA400S37120G 120GB SSD    | 3        | 1.31%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 2        | 0.87%   |
| Seagate ST3500418AS 500GB          | 2        | 0.87%   |
| Seagate ST3120213AS 120GB          | 2        | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB     | 2        | 0.87%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 0.87%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 0.87%   |
| SanDisk DF4032  32GB               | 2        | 0.87%   |
| Samsung SSD 970 EVO Plus 250GB     | 2        | 0.87%   |
| Samsung HD502HJ 500GB              | 2        | 0.87%   |
| Samsung HD161HJ 160GB              | 2        | 0.87%   |
| Kingston SA400S37960G 960GB SSD    | 2        | 0.87%   |
| XrayDisk 240GB SSD                 | 1        | 0.44%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 1        | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 0.44%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.44%   |
| WDC WD800BD-00MRA1 80GB            | 1        | 0.44%   |
| WDC WD800BB-00CAA1 80GB            | 1        | 0.44%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 0.44%   |
| WDC WD5003AZEX-00K3CA0 500GB       | 1        | 0.44%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1        | 0.44%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.44%   |
| WDC WD5000AAKX-22ERMA0 500GB       | 1        | 0.44%   |
| WDC WD5000AAKX-001CA0 500GB        | 1        | 0.44%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.44%   |
| WDC WD40EZRX-00SPEB0 4TB           | 1        | 0.44%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.44%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 1        | 0.44%   |
| WDC WD3200BPVT-00HXZT3 320GB       | 1        | 0.44%   |
| WDC WD3200AAKS-75L9A0 320GB        | 1        | 0.44%   |
| WDC WD3200AAJS-65M0A0 320GB        | 1        | 0.44%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 0.44%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 47     | 34.31%  |
| WDC                 | 27       | 39     | 26.47%  |
| Hitachi             | 15       | 20     | 14.71%  |
| Samsung Electronics | 8        | 9      | 7.84%   |
| Toshiba             | 4        | 7      | 3.92%   |
| HGST                | 4        | 4      | 3.92%   |
| Maxtor              | 2        | 2      | 1.96%   |
| WD MediaMax         | 1        | 1      | 0.98%   |
| TO Exter            | 1        | 1      | 0.98%   |
| RSH-319             | 1        | 1      | 0.98%   |
| External            | 1        | 1      | 0.98%   |
| ExcelStor           | 1        | 1      | 0.98%   |
| Apricorn            | 1        | 1      | 0.98%   |
| Apple               | 1        | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 23     | 20%     |
| Kingston            | 14       | 21     | 20%     |
| SanDisk             | 6        | 7      | 8.57%   |
| WDC                 | 5        | 5      | 7.14%   |
| Apacer              | 3        | 3      | 4.29%   |
| PNY                 | 2        | 2      | 2.86%   |
| GOODRAM             | 2        | 2      | 2.86%   |
| Crucial             | 2        | 2      | 2.86%   |
| China               | 2        | 2      | 2.86%   |
| A-DATA Technology   | 2        | 2      | 2.86%   |
| XrayDisk            | 1        | 1      | 1.43%   |
| Transcend           | 1        | 2      | 1.43%   |
| Team                | 1        | 1      | 1.43%   |
| Patriot             | 1        | 1      | 1.43%   |
| OWC                 | 1        | 1      | 1.43%   |
| Micron Technology   | 1        | 1      | 1.43%   |
| LITEONIT            | 1        | 1      | 1.43%   |
| Kston               | 1        | 3      | 1.43%   |
| KINGBANK            | 1        | 3      | 1.43%   |
| Intenso             | 1        | 1      | 1.43%   |
| Intel               | 1        | 1      | 1.43%   |
| Gigabyte Technology | 1        | 1      | 1.43%   |
| GeIL                | 1        | 1      | 1.43%   |
| Emtec               | 1        | 1      | 1.43%   |
| Dogfish             | 1        | 1      | 1.43%   |
| BR                  | 1        | 1      | 1.43%   |
| ASMT                | 1        | 1      | 1.43%   |
| Apple               | 1        | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 76       | 135    | 45.24%  |
| SSD     | 59       | 92     | 35.12%  |
| NVMe    | 22       | 28     | 13.1%   |
| MMC     | 8        | 8      | 4.76%   |
| Unknown | 3        | 6      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 111      | 224    | 76.03%  |
| NVMe | 21       | 27     | 14.38%  |
| MMC  | 8        | 8      | 5.48%   |
| SAS  | 6        | 10     | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 93       | 143    | 62.84%  |
| 0.51-1.0   | 27       | 40     | 18.24%  |
| 1.01-2.0   | 16       | 26     | 10.81%  |
| 3.01-4.0   | 5        | 7      | 3.38%   |
| 2.01-3.0   | 4        | 5      | 2.7%    |
| 4.01-10.0  | 3        | 6      | 2.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 32       | 25%     |
| 251-500        | 25       | 19.53%  |
| 1001-2000      | 14       | 10.94%  |
| 21-50          | 13       | 10.16%  |
| More than 3000 | 12       | 9.38%   |
| 501-1000       | 10       | 7.81%   |
| 51-100         | 10       | 7.81%   |
| 2001-3000      | 6        | 4.69%   |
| 1-20           | 6        | 4.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 41.54%  |
| 21-50          | 20       | 15.38%  |
| 101-250        | 15       | 11.54%  |
| 501-1000       | 11       | 8.46%   |
| 51-100         | 10       | 7.69%   |
| More than 3000 | 6        | 4.62%   |
| 251-500        | 6        | 4.62%   |
| 1001-2000      | 6        | 4.62%   |
| 2001-3000      | 2        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 2      | 4.55%   |
| WDC WD5000AAKX-001CA0 500GB         | 1        | 1      | 4.55%   |
| WDC WD3200AACS-00M6B0 320GB         | 1        | 1      | 4.55%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1      | 4.55%   |
| WDC WD2003FYYS-02W0B0 2TB           | 1        | 1      | 4.55%   |
| WDC WD10SPZX-08Z10 1TB              | 1        | 1      | 4.55%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 4.55%   |
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 4.55%   |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 4.55%   |
| Toshiba DT01ACA050 500GB            | 1        | 1      | 4.55%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 4.55%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 2      | 4.55%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 4.55%   |
| Maxtor 6L200M0 208GB                | 1        | 1      | 4.55%   |
| Hitachi HTS545032B9A300 320GB       | 1        | 1      | 4.55%   |
| Hitachi HTS545016B9A300 160GB       | 1        | 1      | 4.55%   |
| Hitachi HTS543216L9A300 160GB       | 1        | 1      | 4.55%   |
| Hitachi HTE545050B9A300 500GB       | 1        | 1      | 4.55%   |
| Apple HDD HTS547550A9E384 500GB     | 1        | 1      | 4.55%   |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 4.55%   |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 9      | 30%     |
| Hitachi             | 4        | 4      | 20%     |
| Seagate             | 3        | 4      | 15%     |
| Toshiba             | 2        | 2      | 10%     |
| Samsung Electronics | 1        | 1      | 5%      |
| Maxtor              | 1        | 1      | 5%      |
| Apple               | 1        | 1      | 5%      |
| Apacer              | 1        | 1      | 5%      |
| A-DATA Technology   | 1        | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 9      | 33.33%  |
| Hitachi             | 4        | 4      | 22.22%  |
| Seagate             | 3        | 4      | 16.67%  |
| Toshiba             | 2        | 2      | 11.11%  |
| Samsung Electronics | 1        | 1      | 5.56%   |
| Maxtor              | 1        | 1      | 5.56%   |
| Apple               | 1        | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 22     | 89.47%  |
| SSD  | 2        | 2      | 10.53%  |

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
| Works    | 66       | 119    | 46.48%  |
| Detected | 54       | 123    | 38.03%  |
| Malfunc  | 19       | 24     | 13.38%  |
| Failed   | 3        | 3      | 2.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 71       | 43.83%  |
| AMD                          | 36       | 22.22%  |
| Nvidia                       | 10       | 6.17%   |
| Samsung Electronics          | 8        | 4.94%   |
| ASMedia Technology           | 7        | 4.32%   |
| JMicron Technology           | 5        | 3.09%   |
| Micron/Crucial Technology    | 4        | 2.47%   |
| VIA Technologies             | 3        | 1.85%   |
| SanDisk                      | 3        | 1.85%   |
| Silicon Image                | 2        | 1.23%   |
| Marvell Technology Group     | 2        | 1.23%   |
| Kingston Technology Company  | 2        | 1.23%   |
| Silicon Motion               | 1        | 0.62%   |
| Shenzhen Longsys Electronics | 1        | 0.62%   |
| Seagate Technology           | 1        | 0.62%   |
| Phison Electronics           | 1        | 0.62%   |
| Micron Technology            | 1        | 0.62%   |
| LSI Logic / Symbios Logic    | 1        | 0.62%   |
| Hosin Global Electronics     | 1        | 0.62%   |
| Apple                        | 1        | 0.62%   |
| ADATA Technology             | 1        | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 10.05%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 6.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 5.94%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 3.2%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.74%   |
| Nvidia MCP61 IDE                                                                        | 5        | 2.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5        | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 1.83%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 1.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.37%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.37%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.37%   |
| AMD FCH IDE Controller                                                                  | 3        | 1.37%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.37%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.91%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                                    | 2        | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 0.91%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2        | 0.91%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.91%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.91%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.91%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 0.91%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.91%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 0.91%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 80       | 50.31%  |
| IDE  | 49       | 30.82%  |
| NVMe | 21       | 13.21%  |
| RAID | 8        | 5.03%   |
| SAS  | 1        | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 76       | 61.79%  |
| AMD    | 47       | 38.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 2.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3        | 2.44%   |
| Intel Atom CPU D525 @ 1.80GHz                   | 3        | 2.44%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 3        | 2.44%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz          | 2        | 1.63%   |
| Intel Pentium D CPU 2.80GHz                     | 2        | 1.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2        | 1.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 1.63%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2        | 1.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 2        | 1.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 2        | 1.63%   |
| Intel Celeron CPU 450 @ 2.20GHz                 | 2        | 1.63%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 1.63%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 1.63%   |
| AMD GX-415GA SOC with Radeon HD Graphics        | 2        | 1.63%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 2        | 1.63%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 1.63%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 0.81%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 1        | 0.81%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 0.81%   |
| Intel Xeon CPU E5520 @ 2.27GHz                  | 1        | 0.81%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz             | 1        | 0.81%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz             | 1        | 0.81%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 0.81%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 0.81%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 0.81%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 0.81%   |
| Intel N100                                      | 1        | 0.81%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 0.81%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 0.81%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 0.81%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 0.81%   |
| Intel Core i7-3770S CPU @ 3.10GHz               | 1        | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 0.81%   |
| Intel Core i7-2600S CPU @ 2.80GHz               | 1        | 0.81%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 0.81%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 0.81%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 0.81%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 14       | 11.38%  |
| Intel Core i5           | 12       | 9.76%   |
| Intel Atom              | 9        | 7.32%   |
| Intel Core i7           | 8        | 6.5%    |
| AMD Ryzen 7             | 8        | 6.5%    |
| Intel Core i3           | 7        | 5.69%   |
| AMD Ryzen 5             | 7        | 5.69%   |
| Intel Xeon              | 6        | 4.88%   |
| Intel Core 2 Duo        | 6        | 4.88%   |
| AMD Athlon 64 X2        | 6        | 4.88%   |
| Intel Core 2 Quad       | 4        | 3.25%   |
| Intel Pentium Dual-Core | 3        | 2.44%   |
| Intel Pentium Dual      | 3        | 2.44%   |
| AMD Ryzen 9             | 3        | 2.44%   |
| AMD Phenom II X4        | 3        | 2.44%   |
| AMD FX                  | 3        | 2.44%   |
| Other                   | 2        | 1.63%   |
| Intel Pentium D         | 2        | 1.63%   |
| AMD GX                  | 2        | 1.63%   |
| AMD Athlon II X2        | 2        | 1.63%   |
| AMD A8                  | 2        | 1.63%   |
| AMD A10                 | 2        | 1.63%   |
| Intel Core i9           | 1        | 0.81%   |
| AMD Sempron             | 1        | 0.81%   |
| AMD Ryzen 5 PRO         | 1        | 0.81%   |
| AMD PRO A10             | 1        | 0.81%   |
| AMD Phenom II X6        | 1        | 0.81%   |
| AMD G                   | 1        | 0.81%   |
| AMD Athlon II X3        | 1        | 0.81%   |
| AMD A6                  | 1        | 0.81%   |
| AMD A4                  | 1        | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 45       | 36.59%  |
| 2      | 42       | 34.15%  |
| 6      | 12       | 9.76%   |
| 8      | 11       | 8.94%   |
| 1      | 7        | 5.69%   |
| 3      | 3        | 2.44%   |
| 16     | 1        | 0.81%   |
| 12     | 1        | 0.81%   |
| 10     | 1        | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 98.37%  |
| 2      | 2        | 1.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 74       | 60.16%  |
| 2      | 49       | 39.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 123      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 50%     |
| 0x1067a    | 5        | 3.97%   |
| 0x406c4    | 4        | 3.17%   |
| 0x906ea    | 3        | 2.38%   |
| 0x306c3    | 3        | 2.38%   |
| 0x106ca    | 3        | 2.38%   |
| 0x6fb      | 2        | 1.59%   |
| 0x506e3    | 2        | 1.59%   |
| 0x306a9    | 2        | 1.59%   |
| 0x30679    | 2        | 1.59%   |
| 0x206a7    | 2        | 1.59%   |
| 0x0a201009 | 2        | 1.59%   |
| 0x0800820d | 2        | 1.59%   |
| 0x0700010f | 2        | 1.59%   |
| 0x06003106 | 2        | 1.59%   |
| 0x010000db | 2        | 1.59%   |
| 0xa0653    | 1        | 0.79%   |
| 0x906eb    | 1        | 0.79%   |
| 0x906c0    | 1        | 0.79%   |
| 0x706a8    | 1        | 0.79%   |
| 0x706a1    | 1        | 0.79%   |
| 0x6fd      | 1        | 0.79%   |
| 0x506ca    | 1        | 0.79%   |
| 0x506c9    | 1        | 0.79%   |
| 0x306e4    | 1        | 0.79%   |
| 0x206c2    | 1        | 0.79%   |
| 0x106a5    | 1        | 0.79%   |
| 0x10676    | 1        | 0.79%   |
| 0x10661    | 1        | 0.79%   |
| 0x0a601203 | 1        | 0.79%   |
| 0x0a50000d | 1        | 0.79%   |
| 0x0a50000c | 1        | 0.79%   |
| 0x0a50000b | 1        | 0.79%   |
| 0x08701021 | 1        | 0.79%   |
| 0x08701013 | 1        | 0.79%   |
| 0x08608103 | 1        | 0.79%   |
| 0x08001138 | 1        | 0.79%   |
| 0x06001119 | 1        | 0.79%   |
| 0x06000852 | 1        | 0.79%   |
| 0x010000c8 | 1        | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 12       | 9.76%   |
| IvyBridge     | 9        | 7.32%   |
| K10           | 8        | 6.5%    |
| Core          | 8        | 6.5%    |
| Zen 3         | 7        | 5.69%   |
| Silvermont    | 7        | 5.69%   |
| K8 Hammer     | 7        | 5.69%   |
| KabyLake      | 6        | 4.88%   |
| Zen+          | 5        | 4.07%   |
| Haswell       | 5        | 4.07%   |
| Bonnell       | 5        | 4.07%   |
| SandyBridge   | 4        | 3.25%   |
| Nehalem       | 4        | 3.25%   |
| Zen 2         | 3        | 2.44%   |
| Skylake       | 3        | 2.44%   |
| Piledriver    | 3        | 2.44%   |
| Goldmont plus | 3        | 2.44%   |
| Zen           | 2        | 1.63%   |
| Westmere      | 2        | 1.63%   |
| Steamroller   | 2        | 1.63%   |
| NetBurst      | 2        | 1.63%   |
| K10 Llano     | 2        | 1.63%   |
| Jaguar        | 2        | 1.63%   |
| Goldmont      | 2        | 1.63%   |
| Excavator     | 2        | 1.63%   |
| CometLake     | 2        | 1.63%   |
| Unknown       | 2        | 1.63%   |
| Tremont       | 1        | 0.81%   |
| Gracemont     | 1        | 0.81%   |
| Bulldozer     | 1        | 0.81%   |
| Bobcat        | 1        | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 46       | 35.66%  |
| Intel  | 44       | 34.11%  |
| AMD    | 39       | 30.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7        | 5.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5        | 3.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 3.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 2.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 2.99%   |
| Nvidia GT218 [ION]                                                                       | 3        | 2.24%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 3        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 2.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 2.24%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.24%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 2.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 2.24%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 2        | 1.49%   |
| Intel HD Graphics 500                                                                    | 2        | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 1.49%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.49%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 1.49%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 1.49%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2        | 1.49%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2        | 1.49%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.49%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1        | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.75%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.75%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.75%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.75%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.75%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 0.75%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 0.75%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 43       | 34.96%  |
| 1 x Intel          | 40       | 32.52%  |
| 1 x AMD            | 33       | 26.83%  |
| 2 x AMD            | 3        | 2.44%   |
| AMD + Nvidia       | 2        | 1.63%   |
| Intel + 2 x Nvidia | 1        | 0.81%   |
| Intel + 2 x AMD    | 1        | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 100      | 81.3%   |
| Proprietary | 16       | 13.01%  |
| Unknown     | 7        | 5.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 62.1%   |
| 0.01-0.5   | 15       | 12.1%   |
| 0.51-1.0   | 12       | 9.68%   |
| 7.01-8.0   | 6        | 4.84%   |
| 1.01-2.0   | 4        | 3.23%   |
| 8.01-16.0  | 4        | 3.23%   |
| 5.01-6.0   | 3        | 2.42%   |
| 3.01-4.0   | 2        | 1.61%   |
| 2.01-3.0   | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 17.12%  |
| Dell                 | 13       | 11.71%  |
| Hewlett-Packard      | 8        | 7.21%   |
| Goldstar             | 8        | 7.21%   |
| Philips              | 7        | 6.31%   |
| Ancor Communications | 6        | 5.41%   |
| Acer                 | 6        | 5.41%   |
| Iiyama               | 3        | 2.7%    |
| Eizo                 | 3        | 2.7%    |
| Unknown              | 2        | 1.8%    |
| Sony                 | 2        | 1.8%    |
| MSI                  | 2        | 1.8%    |
| Lenovo               | 2        | 1.8%    |
| HannStar             | 2        | 1.8%    |
| BenQ                 | 2        | 1.8%    |
| XKX                  | 1        | 0.9%    |
| Westinghouse         | 1        | 0.9%    |
| Vizio                | 1        | 0.9%    |
| ViewSonic            | 1        | 0.9%    |
| VHT                  | 1        | 0.9%    |
| Unknown (ADA)        | 1        | 0.9%    |
| SNC                  | 1        | 0.9%    |
| Sharp                | 1        | 0.9%    |
| SFX                  | 1        | 0.9%    |
| Sceptre Tech         | 1        | 0.9%    |
| Sampo                | 1        | 0.9%    |
| RTK                  | 1        | 0.9%    |
| Positivo             | 1        | 0.9%    |
| Plain Tree Systems   | 1        | 0.9%    |
| Pixio                | 1        | 0.9%    |
| NEC Computers        | 1        | 0.9%    |
| LG Electronics       | 1        | 0.9%    |
| Jean                 | 1        | 0.9%    |
| HKC                  | 1        | 0.9%    |
| HJW                  | 1        | 0.9%    |
| Daewoo               | 1        | 0.9%    |
| Compal               | 1        | 0.9%    |
| CMT                  | 1        | 0.9%    |
| Belinea              | 1        | 0.9%    |
| AOC                  | 1        | 0.9%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 1.75%   |
| XKX HDMI XKX3200 3840x2160 698x393mm 31.5-inch                       | 1        | 0.88%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1        | 0.88%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1        | 0.88%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 0.88%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 0.88%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 1        | 0.88%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 0.88%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1        | 0.88%   |
| Sony TV SNY9C01 1920x1080                                            | 1        | 0.88%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1        | 0.88%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 0.88%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 0.88%   |
| SFX HDMI2.0 KVM SFX0100 3840x2160 610x350mm 27.7-inch                | 1        | 0.88%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch       | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 340x190mm 15.3-inch  | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 0.88%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 0.88%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 0.88%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 0.88%   |
| Samsung Electronics S23C650 SAM09DE 1920x1080 510x287mm 23.0-inch    | 1        | 0.88%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 0.88%   |
| Samsung Electronics S/M 550v SAM12B6 1024x768 267x200mm 13.1-inch    | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 0.88%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                     | 1        | 0.88%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 0.88%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 697x392mm 31.5-inch    | 1        | 0.88%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch    | 1        | 0.88%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 0.88%   |
| RTK ARZOPA RTKBC33 1920x1080 309x174mm 14.0-inch                     | 1        | 0.88%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 0.88%   |
| Plain Tree Systems RD979 PTS05C5 1280x1024 376x301mm 19.0-inch       | 1        | 0.88%   |
| Pixio DP ICB3500 3440x1440 708x399mm 32.0-inch                       | 1        | 0.88%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 0.88%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 0.88%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1        | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 41       | 37.27%  |
| 1280x1024 (SXGA)   | 12       | 10.91%  |
| 1680x1050 (WSXGA+) | 8        | 7.27%   |
| 1600x900 (HD+)     | 7        | 6.36%   |
| 1440x900 (WXGA+)   | 7        | 6.36%   |
| 1366x768 (WXGA)    | 7        | 6.36%   |
| 3840x2160 (4K)     | 6        | 5.45%   |
| 2560x1440 (QHD)    | 6        | 5.45%   |
| 1360x768           | 6        | 5.45%   |
| 1024x768 (XGA)     | 2        | 1.82%   |
| 800x600            | 1        | 0.91%   |
| 3440x1440          | 1        | 0.91%   |
| 2560x1600          | 1        | 0.91%   |
| 2288x1287          | 1        | 0.91%   |
| 1920x1200 (WUXGA)  | 1        | 0.91%   |
| 1280x800 (WXGA)    | 1        | 0.91%   |
| 1280x768           | 1        | 0.91%   |
| 1280x720 (HD)      | 1        | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 13       | 12.04%  |
| 27      | 12       | 11.11%  |
| 23      | 11       | 10.19%  |
| 24      | 10       | 9.26%   |
| 18      | 9        | 8.33%   |
| 22      | 8        | 7.41%   |
| 21      | 8        | 7.41%   |
| Unknown | 7        | 6.48%   |
| 20      | 5        | 4.63%   |
| 17      | 4        | 3.7%    |
| 31      | 3        | 2.78%   |
| 15      | 3        | 2.78%   |
| 32      | 2        | 1.85%   |
| 142     | 1        | 0.93%   |
| 84      | 1        | 0.93%   |
| 72      | 1        | 0.93%   |
| 49      | 1        | 0.93%   |
| 47      | 1        | 0.93%   |
| 43      | 1        | 0.93%   |
| 42      | 1        | 0.93%   |
| 34      | 1        | 0.93%   |
| 26      | 1        | 0.93%   |
| 14      | 1        | 0.93%   |
| 13      | 1        | 0.93%   |
| 8       | 1        | 0.93%   |
| 7       | 1        | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 36       | 33.33%  |
| 501-600        | 33       | 30.56%  |
| 351-400        | 8        | 7.41%   |
| 301-350        | 7        | 6.48%   |
| Unknown        | 7        | 6.48%   |
| 601-700        | 4        | 3.7%    |
| 701-800        | 3        | 2.78%   |
| 1501-2000      | 2        | 1.85%   |
| 101-200        | 2        | 1.85%   |
| 1001-1500      | 2        | 1.85%   |
| 901-1000       | 2        | 1.85%   |
| More than 2000 | 1        | 0.93%   |
| 201-300        | 1        | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 67       | 63.81%  |
| 16/10   | 16       | 15.24%  |
| 5/4     | 10       | 9.52%   |
| Unknown | 6        | 5.71%   |
| 4/3     | 4        | 3.81%   |
| 3/2     | 1        | 0.95%   |
| 1.00    | 1        | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 28.04%  |
| 151-200        | 23       | 21.5%   |
| 301-350        | 12       | 11.21%  |
| 141-150        | 10       | 9.35%   |
| Unknown        | 7        | 6.54%   |
| 351-500        | 5        | 4.67%   |
| More than 1000 | 4        | 3.74%   |
| 251-300        | 4        | 3.74%   |
| 501-1000       | 4        | 3.74%   |
| 81-90          | 2        | 1.87%   |
| 1-40           | 2        | 1.87%   |
| 101-110        | 2        | 1.87%   |
| 131-140        | 1        | 0.93%   |
| 111-120        | 1        | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 68       | 64.15%  |
| 101-120 | 18       | 16.98%  |
| 1-50    | 8        | 7.55%   |
| Unknown | 7        | 6.6%    |
| 161-240 | 3        | 2.83%   |
| 121-160 | 2        | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 103      | 83.06%  |
| 2     | 13       | 10.48%  |
| 0     | 8        | 6.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 76       | 42.22%  |
| Intel                                 | 38       | 21.11%  |
| Qualcomm Atheros                      | 11       | 6.11%   |
| Nvidia                                | 9        | 5%      |
| TP-Link                               | 8        | 4.44%   |
| Broadcom                              | 8        | 4.44%   |
| NetGear                               | 3        | 1.67%   |
| MediaTek                              | 3        | 1.67%   |
| VIA Technologies                      | 2        | 1.11%   |
| Samsung Electronics                   | 2        | 1.11%   |
| Ralink Technology                     | 2        | 1.11%   |
| Ralink                                | 2        | 1.11%   |
| Qualcomm Atheros Communications       | 2        | 1.11%   |
| Xiaomi                                | 1        | 0.56%   |
| Trident Microsystems                  | 1        | 0.56%   |
| Texas Instruments                     | 1        | 0.56%   |
| Seeed Technology                      | 1        | 0.56%   |
| Marvell Technology Group              | 1        | 0.56%   |
| Linksys                               | 1        | 0.56%   |
| ICS Advent                            | 1        | 0.56%   |
| Hangzhou Silan Microelectronics       | 1        | 0.56%   |
| D-Link                                | 1        | 0.56%   |
| Broadcom Limited                      | 1        | 0.56%   |
| Belkin Components                     | 1        | 0.56%   |
| ASUSTek Computer                      | 1        | 0.56%   |
| Accton Technology                     | 1        | 0.56%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 64       | 32.65%  |
| Nvidia MCP61 Ethernet                                                  | 6        | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 3.06%   |
| Intel Ethernet Controller I225-V                                       | 5        | 2.55%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 2.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 3        | 1.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 1.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 1.53%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 1.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2        | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 1.02%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 2        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 1.02%   |
| Nvidia MCP77 Ethernet                                                  | 2        | 1.02%   |
| NetGear A6210                                                          | 2        | 1.02%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 1.02%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 2        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.02%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2        | 1.02%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller    | 2        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.51%   |
| Trident Microsystems 4DWave DX                                         | 1        | 0.51%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1        | 0.51%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 1        | 0.51%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1        | 0.51%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 1        | 0.51%   |
| TP-Link 802.11ac NIC                                                   | 1        | 0.51%   |
| Texas Instruments CC2531 ZigBee                                        | 1        | 0.51%   |
| Seeed Seeeduino_Cortex_M0+                                             | 1        | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.51%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.51%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                 | 1        | 0.51%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                | 1        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 15       | 25.42%  |
| Intel                                 | 12       | 20.34%  |
| TP-Link                               | 7        | 11.86%  |
| Qualcomm Atheros                      | 5        | 8.47%   |
| MediaTek                              | 3        | 5.08%   |
| Broadcom                              | 3        | 5.08%   |
| Ralink Technology                     | 2        | 3.39%   |
| Ralink                                | 2        | 3.39%   |
| Qualcomm Atheros Communications       | 2        | 3.39%   |
| NetGear                               | 2        | 3.39%   |
| Linksys                               | 1        | 1.69%   |
| D-Link                                | 1        | 1.69%   |
| Broadcom Limited                      | 1        | 1.69%   |
| Belkin Components                     | 1        | 1.69%   |
| ASUSTek Computer                      | 1        | 1.69%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 3        | 5.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3        | 5.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2        | 3.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 3.39%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 3.39%   |
| NetGear A6210                                                       | 2        | 3.39%   |
| Intel Wi-Fi 6 AX200                                                 | 2        | 3.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 3.39%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 3.39%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 1.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 1.69%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1        | 1.69%   |
| TP-Link 802.11ac NIC                                                | 1        | 1.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                          | 1        | 1.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 1.69%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 1.69%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 1.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 1.69%   |
| Realtek RTL8187 Wireless Adapter                                    | 1        | 1.69%   |
| Realtek 802.11ac NIC                                                | 1        | 1.69%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 1.69%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 1.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 1.69%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                | 1        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1        | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 1.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 1.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 1        | 1.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 1.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 1.69%   |
| Linksys AM10 v1 802.11n [Ralink RT3072]                             | 1        | 1.69%   |
| Intel Wireless 7265                                                 | 1        | 1.69%   |
| Intel Wireless 3165                                                 | 1        | 1.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]           | 1        | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 1.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                     | 1        | 1.69%   |
| Intel CNVi: Wi-Fi                                                   | 1        | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 71       | 53.38%  |
| Intel                           | 28       | 21.05%  |
| Nvidia                          | 9        | 6.77%   |
| Qualcomm Atheros                | 8        | 6.02%   |
| Broadcom                        | 5        | 3.76%   |
| VIA Technologies                | 2        | 1.5%    |
| Samsung Electronics             | 2        | 1.5%    |
| Xiaomi                          | 1        | 0.75%   |
| Trident Microsystems            | 1        | 0.75%   |
| TP-Link                         | 1        | 0.75%   |
| NetGear                         | 1        | 0.75%   |
| Marvell Technology Group        | 1        | 0.75%   |
| ICS Advent                      | 1        | 0.75%   |
| Hangzhou Silan Microelectronics | 1        | 0.75%   |
| Accton Technology               | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 64       | 47.41%  |
| Nvidia MCP61 Ethernet                                                  | 6        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6        | 4.44%   |
| Intel Ethernet Controller I225-V                                       | 5        | 3.7%    |
| Intel I211 Gigabit Network Connection                                  | 4        | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 2.22%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 2.22%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2        | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 1.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2        | 1.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2        | 1.48%   |
| Nvidia MCP77 Ethernet                                                  | 2        | 1.48%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 2        | 1.48%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 1.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2        | 1.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1        | 0.74%   |
| Trident Microsystems 4DWave DX                                         | 1        | 0.74%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1        | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.74%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 0.74%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.74%   |
| Nvidia MCP55 Ethernet                                                  | 1        | 0.74%   |
| NetGear LB1120-100NAS                                                  | 1        | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.74%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.74%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 0.74%   |
| Intel 82583V Gigabit Network Connection                                | 1        | 0.74%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 0.74%   |
| Intel 82567V-3 Gigabit Network Connection                              | 1        | 0.74%   |
| Intel 82567LF-2 Gigabit Network Connection                             | 1        | 0.74%   |
| ICS Advent 10/100M LAN                                                 | 1        | 0.74%   |
| Hangzhou Silan RTL8139D [Realtek] PCI 10/100BaseTX ethernet adaptor    | 1        | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1        | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 121      | 67.98%  |
| WiFi     | 55       | 30.9%   |
| Modem    | 2        | 1.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 90       | 70.31%  |
| WiFi     | 38       | 29.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 82       | 66.67%  |
| 2     | 34       | 27.64%  |
| 3     | 4        | 3.25%   |
| 0     | 2        | 1.63%   |
| 4     | 1        | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 85       | 69.11%  |
| Yes  | 38       | 30.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 39.29%  |
| Cambridge Silicon Radio         | 5        | 17.86%  |
| Realtek Semiconductor           | 3        | 10.71%  |
| Qualcomm Atheros Communications | 2        | 7.14%   |
| MediaTek                        | 2        | 7.14%   |
| Foxconn / Hon Hai               | 2        | 7.14%   |
| TP-Link                         | 1        | 3.57%   |
| Logitech                        | 1        | 3.57%   |
| Broadcom                        | 1        | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5        | 17.24%  |
| Realtek Bluetooth Radio                             | 2        | 6.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 6.9%    |
| MediaTek Wireless_Device                            | 2        | 6.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 6.9%    |
| Intel Bluetooth wireless interface                  | 2        | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 6.9%    |
| Intel AX200 Bluetooth                               | 2        | 6.9%    |
| TP-Link UB500 Adapter                               | 1        | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 3.45%   |
| Realtek Bluetooth 5.3 Radio                         | 1        | 3.45%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 3.45%   |
| Intel AX210 Bluetooth                               | 1        | 3.45%   |
| Intel AX201 Bluetooth                               | 1        | 3.45%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 3.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 69       | 38.98%  |
| AMD                                          | 45       | 25.42%  |
| Nvidia                                       | 38       | 21.47%  |
| C-Media Electronics                          | 6        | 3.39%   |
| VIA Technologies                             | 3        | 1.69%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 1.13%   |
| Texas Instruments                            | 2        | 1.13%   |
| ASUSTek Computer                             | 2        | 1.13%   |
| Sony                                         | 1        | 0.56%   |
| Razer USA                                    | 1        | 0.56%   |
| Plantronics                                  | 1        | 0.56%   |
| Microsoft                                    | 1        | 0.56%   |
| Micro Star International                     | 1        | 0.56%   |
| JMTek                                        | 1        | 0.56%   |
| GN Netcom                                    | 1        | 0.56%   |
| Focusrite-Novation                           | 1        | 0.56%   |
| Ensoniq                                      | 1        | 0.56%   |
| Creative Labs                                | 1        | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 17       | 8.17%   |
| Nvidia High Definition Audio Controller                                           | 8        | 3.85%   |
| AMD FCH Azalia Controller                                                         | 8        | 3.85%   |
| Nvidia MCP61 High Definition Audio                                                | 7        | 3.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 3.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 3.37%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 2.88%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 2.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5        | 2.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5        | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 4        | 1.92%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4        | 1.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 1.92%   |
| AMD Kabini HDMI/DP Audio                                                          | 4        | 1.92%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 1.44%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 3        | 1.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 3        | 1.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.44%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2        | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2        | 0.96%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 0.96%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 0.96%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.96%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.96%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 0.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 0.96%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 17       | 18.68%  |
| Kingston            | 13       | 14.29%  |
| Samsung Electronics | 9        | 9.89%   |
| Micron Technology   | 9        | 9.89%   |
| SK hynix            | 8        | 8.79%   |
| G.Skill             | 6        | 6.59%   |
| Corsair             | 6        | 6.59%   |
| Crucial             | 5        | 5.49%   |
| Unknown             | 5        | 5.49%   |
| Unknown (ABCD)      | 3        | 3.3%    |
| Patriot             | 2        | 2.2%    |
| A-DATA Technology   | 2        | 2.2%    |
| Unknown (AB)        | 1        | 1.1%    |
| Unifosa             | 1        | 1.1%    |
| PUSKILL             | 1        | 1.1%    |
| Nanya Technology    | 1        | 1.1%    |
| GOODRAM             | 1        | 1.1%    |
| Elpida              | 1        | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown                                                      | 5        | 4.95%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 3        | 2.97%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2        | 1.98%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 2        | 1.98%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                     | 2        | 1.98%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 2        | 1.98%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                         | 1        | 0.99%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                   | 1        | 0.99%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1        | 0.99%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1        | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                     | 1        | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                     | 1        | 0.99%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.99%   |
| Unknown RAM Module 2GB DIMM                                  | 1        | 0.99%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                     | 1        | 0.99%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 1        | 0.99%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s     | 1        | 0.99%   |
| Unknown (AB) RAM Module 1GB DIMM LPDDR4 1600MT/s             | 1        | 0.99%   |
| Unifosa RAM Module 2GB DIMM DDR3 1066MT/s                    | 1        | 0.99%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                   | 1        | 0.99%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                   | 1        | 0.99%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                   | 1        | 0.99%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2666MT/s                | 1        | 0.99%   |
| SK hynix RAM HMT451S6BFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1        | 0.99%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s         | 1        | 0.99%   |
| Samsung RAM Module 3GB Row Of Chips LPDDR5 6400MT/s          | 1        | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.99%   |
| Samsung RAM M393B5773CH0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s              | 1        | 0.99%   |
| Samsung RAM M393B1K70BH1-CH9 8GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 1        | 0.99%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 29       | 34.52%  |
| DDR4    | 27       | 32.14%  |
| DDR2    | 11       | 13.1%   |
| Unknown | 6        | 7.14%   |
| SDRAM   | 5        | 5.95%   |
| LPDDR4  | 3        | 3.57%   |
| LPDDR5  | 1        | 1.19%   |
| DDR5    | 1        | 1.19%   |
| DDR     | 1        | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 68       | 82.93%  |
| SODIMM       | 13       | 15.85%  |
| Row Of Chips | 1        | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 29.35%  |
| 4096  | 23       | 25%     |
| 2048  | 21       | 22.83%  |
| 16384 | 12       | 13.04%  |
| 1024  | 5        | 5.43%   |
| 32768 | 3        | 3.26%   |
| 3072  | 1        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 23.6%   |
| 1333    | 10       | 11.24%  |
| 3200    | 9        | 10.11%  |
| 800     | 7        | 7.87%   |
| 2400    | 6        | 6.74%   |
| 667     | 4        | 4.49%   |
| 3400    | 3        | 3.37%   |
| 2667    | 3        | 3.37%   |
| 2133    | 3        | 3.37%   |
| 1066    | 3        | 3.37%   |
| Unknown | 3        | 3.37%   |
| 3066    | 2        | 2.25%   |
| 2666    | 2        | 2.25%   |
| 1866    | 2        | 2.25%   |
| 6400    | 1        | 1.12%   |
| 4800    | 1        | 1.12%   |
| 3933    | 1        | 1.12%   |
| 3866    | 1        | 1.12%   |
| 3666    | 1        | 1.12%   |
| 3600    | 1        | 1.12%   |
| 3534    | 1        | 1.12%   |
| 2800    | 1        | 1.12%   |
| 2048    | 1        | 1.12%   |
| 533     | 1        | 1.12%   |
| 333     | 1        | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 3        | 50%     |
| Canon               | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung SCX-4200 series | 1        | 16.67%  |
| Canon PIXMA MP250       | 1        | 16.67%  |
| Canon LiDE 300          | 1        | 16.67%  |
| Brother HL-L2380DW      | 1        | 16.67%  |
| Brother HL-2230 series  | 1        | 16.67%  |
| Brother DCP-7055W       | 1        | 16.67%  |

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


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Logitech                       | 5        | 45.45%  |
| WaveRider Communications       | 1        | 9.09%   |
| Santa Barbara Instrument Group | 1        | 9.09%   |
| Pixart Imaging                 | 1        | 9.09%   |
| Microsoft                      | 1        | 9.09%   |
| Generalplus Technology         | 1        | 9.09%   |
| AVerMedia Technologies         | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                 | 3        | 27.27%  |
| WaveRider USB Live camera                                            | 1        | 9.09%   |
| Santa Barbara Instrument Group SBIG Astronomy Camera (with firmware) | 1        | 9.09%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                                 | 1        | 9.09%   |
| Microsoft LifeCam VX-800                                             | 1        | 9.09%   |
| Logitech Webcam C170                                                 | 1        | 9.09%   |
| Logitech HD Webcam C615                                              | 1        | 9.09%   |
| Generalplus 808 Camera                                               | 1        | 9.09%   |
| AVerMedia Live Streamer CAM 313                                      | 1        | 9.09%   |

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
| CHERRY | 2        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| CHERRY SmartCard Reader Keyboard KC 1000 SC | 2        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 106      | 85.48%  |
| 1     | 14       | 11.29%  |
| 2     | 4        | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 40%     |
| Net/wireless             | 5        | 25%     |
| Net/ethernet             | 2        | 10%     |
| Communication controller | 2        | 10%     |
| Unassigned class         | 1        | 5%      |
| Storage/raid             | 1        | 5%      |
| Sound                    | 1        | 5%      |

