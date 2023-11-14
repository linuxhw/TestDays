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

Total: 135

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-43-generic    | 11       | 9.65%   |
| 5.19.0-50-generic    | 5        | 4.39%   |
| 5.19.0-32-generic    | 5        | 4.39%   |
| 5.15.0-60-generic    | 5        | 4.39%   |
| 5.15.0-41-generic    | 5        | 4.39%   |
| 5.15.0-56-generic    | 4        | 3.51%   |
| 5.15.0-47-generic    | 4        | 3.51%   |
| 5.15.0-25-generic    | 4        | 3.51%   |
| 5.15.0-75-generic    | 3        | 2.63%   |
| 5.15.0-67-generic    | 3        | 2.63%   |
| 5.15.0-52-generic    | 3        | 2.63%   |
| 5.15.0-48-generic    | 3        | 2.63%   |
| 5.15.0-40-generic    | 3        | 2.63%   |
| 5.15.0-39-generic    | 3        | 2.63%   |
| 6.2.0-35-generic     | 2        | 1.75%   |
| 6.2.0-26-generic     | 2        | 1.75%   |
| 5.19.0-46-generic    | 2        | 1.75%   |
| 5.19.0-43-generic    | 2        | 1.75%   |
| 5.19.0-35-generic    | 2        | 1.75%   |
| 5.15.0-86-generic    | 2        | 1.75%   |
| 5.15.0-83-generic    | 2        | 1.75%   |
| 5.15.0-82-generic    | 2        | 1.75%   |
| 5.15.0-58-generic    | 2        | 1.75%   |
| 5.15.0-53-generic    | 2        | 1.75%   |
| 5.15.0-50-generic    | 2        | 1.75%   |
| 5.15.0-46-generic    | 2        | 1.75%   |
| 5.15.0-35-generic    | 2        | 1.75%   |
| 5.15.0-30-generic    | 2        | 1.75%   |
| 5.15.0-27-generic    | 2        | 1.75%   |
| 6.5.8-custom         | 1        | 0.88%   |
| 6.3.3-custom         | 1        | 0.88%   |
| 6.2.8-x64v3-xanmod1  | 1        | 0.88%   |
| 6.2.0-36-generic     | 1        | 0.88%   |
| 6.2.0-33-generic     | 1        | 0.88%   |
| 6.1.46-rt13-tkg-r2b  | 1        | 0.88%   |
| 6.1.0-custom         | 1        | 0.88%   |
| 6.0.8-060008-generic | 1        | 0.88%   |
| 6.0.14               | 1        | 0.88%   |
| 5.19.0-45-generic    | 1        | 0.88%   |
| 5.19.0-41-generic    | 1        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 74       | 70.48%  |
| 5.19.0  | 19       | 18.1%   |
| 6.2.0   | 5        | 4.76%   |
| 6.5.8   | 1        | 0.95%   |
| 6.3.3   | 1        | 0.95%   |
| 6.2.8   | 1        | 0.95%   |
| 6.1.46  | 1        | 0.95%   |
| 6.1.0   | 1        | 0.95%   |
| 6.0.8   | 1        | 0.95%   |
| 6.0.14  | 1        | 0.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 74       | 70.48%  |
| 5.19    | 19       | 18.1%   |
| 6.2     | 6        | 5.71%   |
| 6.1     | 2        | 1.9%    |
| 6.0     | 2        | 1.9%    |
| 6.5     | 1        | 0.95%   |
| 6.3     | 1        | 0.95%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 100      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| LXQt  | 95       | 95%     |
| LXDE  | 3        | 3%      |
| XFCE  | 1        | 1%      |
| GNOME | 1        | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 96       | 93.2%   |
| Tty         | 5        | 4.85%   |
| Wayland     | 1        | 0.97%   |
| Unspecified | 1        | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 84       | 84%     |
| LightDM | 6        | 6%      |
| Unknown | 5        | 5%      |
| GDM3    | 2        | 2%      |
| XDM     | 1        | 1%      |
| SLiM    | 1        | 1%      |
| LXDM    | 1        | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 29       | 28.71%  |
| fr_FR | 15       | 14.85%  |
| de_DE | 9        | 8.91%   |
| it_IT | 6        | 5.94%   |
| es_ES | 6        | 5.94%   |
| en_GB | 5        | 4.95%   |
| es_AR | 4        | 3.96%   |
| pt_BR | 3        | 2.97%   |
| en_AU | 3        | 2.97%   |
| C     | 3        | 2.97%   |
| pl_PL | 2        | 1.98%   |
| es_MX | 2        | 1.98%   |
| es_CR | 2        | 1.98%   |
| zh_TW | 1        | 0.99%   |
| tr_TR | 1        | 0.99%   |
| sv_SE | 1        | 0.99%   |
| ru_UA | 1        | 0.99%   |
| ru_RU | 1        | 0.99%   |
| nl_BE | 1        | 0.99%   |
| fi_FI | 1        | 0.99%   |
| es_PE | 1        | 0.99%   |
| en_AG | 1        | 0.99%   |
| el_GR | 1        | 0.99%   |
| cv_RU | 1        | 0.99%   |
| cs_CZ | 1        | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 69       | 69%     |
| EFI  | 31       | 31%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 90       | 88.24%  |
| Tmpfs   | 6        | 5.88%   |
| Overlay | 3        | 2.94%   |
| Btrfs   | 2        | 1.96%   |
| XXX4    | 1        | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 48       | 47.52%  |
| MBR     | 33       | 32.67%  |
| Unknown | 20       | 19.8%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 81       | 80.2%   |
| Yes       | 20       | 19.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 63%     |
| Yes       | 37       | 37%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 20%     |
| MSI                 | 15       | 15%     |
| Dell                | 11       | 11%     |
| ASRock              | 7        | 7%      |
| Gigabyte Technology | 6        | 6%      |
| Hewlett-Packard     | 5        | 5%      |
| Unknown             | 5        | 5%      |
| Pegatron            | 4        | 4%      |
| Acer                | 4        | 4%      |
| Intel               | 3        | 3%      |
| Positivo            | 2        | 2%      |
| Lenovo              | 2        | 2%      |
| AMI                 | 2        | 2%      |
| ZOTAC               | 1        | 1%      |
| YANYU               | 1        | 1%      |
| Shuttle             | 1        | 1%      |
| Seeed Studio        | 1        | 1%      |
| PCChips             | 1        | 1%      |
| NEC Computers       | 1        | 1%      |
| Inventec            | 1        | 1%      |
| IceWhale Technology | 1        | 1%      |
| Fujitsu             | 1        | 1%      |
| Foxconn             | 1        | 1%      |
| ECS                 | 1        | 1%      |
| BANGHO              | 1        | 1%      |
| Apple               | 1        | 1%      |
| AAEON               | 1        | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 5        | 5%      |
| MSI MS-7C37                            | 3        | 3%      |
| Dell Dimension 9100                    | 2        | 2%      |
| ZOTAC NM10                             | 1        | 1%      |
| YANYU ITX-S192                         | 1        | 1%      |
| Shuttle XS35V3                         | 1        | 1%      |
| Seeed Studio ODYSSEY-X86J4125          | 1        | 1%      |
| Positivo POS-AG31AP                    | 1        | 1%      |
| Positivo P5VD2-MX                      | 1        | 1%      |
| Pegatron NC689AA-ABA s3700y            | 1        | 1%      |
| Pegatron h8-1350ef                     | 1        | 1%      |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 1%      |
| Pegatron AY748AA-ABA p6320y            | 1        | 1%      |
| PCChips P49G                           | 1        | 1%      |
| NEC Computers ECS-945G                 | 1        | 1%      |
| MSI MS-7D54                            | 1        | 1%      |
| MSI MS-7D09                            | 1        | 1%      |
| MSI MS-7C96                            | 1        | 1%      |
| MSI MS-7C56                            | 1        | 1%      |
| MSI MS-7C51                            | 1        | 1%      |
| MSI MS-7B86                            | 1        | 1%      |
| MSI MS-7B33                            | 1        | 1%      |
| MSI MS-7978                            | 1        | 1%      |
| MSI MS-7641                            | 1        | 1%      |
| MSI MS-7501                            | 1        | 1%      |
| MSI MS-7267                            | 1        | 1%      |
| MSI MS-7032                            | 1        | 1%      |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 1%      |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 1%      |
| Inventec DQ Class                      | 1        | 1%      |
| Intel X79 V2.72A                       | 1        | 1%      |
| Intel H61                              | 1        | 1%      |
| Intel BTC-T37                          | 1        | 1%      |
| IceWhale ZimaBoard 216 ZMB             | 1        | 1%      |
| HP Z400 Workstation                    | 1        | 1%      |
| HP t620 Quad Core TC                   | 1        | 1%      |
| HP Slim Desktop S01-pF1xxx             | 1        | 1%      |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 1%      |
| HP Compaq 8000 Elite SFF PC            | 1        | 1%      |
| Gigabyte GB-BMCE-5105                  | 1        | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 5        | 5%      |
| Unknown                       | 5        | 5%      |
| MSI MS-7C37                   | 3        | 3%      |
| ASUS ROG                      | 3        | 3%      |
| ASUS PRIME                    | 3        | 3%      |
| Lenovo ThinkCentre            | 2        | 2%      |
| HP Compaq                     | 2        | 2%      |
| Dell Vostro                   | 2        | 2%      |
| Dell Dimension                | 2        | 2%      |
| Acer Veriton                  | 2        | 2%      |
| ZOTAC NM10                    | 1        | 1%      |
| YANYU ITX-S192                | 1        | 1%      |
| Shuttle XS35V3                | 1        | 1%      |
| Seeed Studio ODYSSEY-X86J4125 | 1        | 1%      |
| Positivo POS-AG31AP           | 1        | 1%      |
| Positivo P5VD2-MX             | 1        | 1%      |
| Pegatron NC689AA-ABA          | 1        | 1%      |
| Pegatron h8-1350ef            | 1        | 1%      |
| Pegatron Compaq               | 1        | 1%      |
| Pegatron AY748AA-ABA          | 1        | 1%      |
| PCChips P49G                  | 1        | 1%      |
| NEC Computers ECS-945G        | 1        | 1%      |
| MSI MS-7D54                   | 1        | 1%      |
| MSI MS-7D09                   | 1        | 1%      |
| MSI MS-7C96                   | 1        | 1%      |
| MSI MS-7C56                   | 1        | 1%      |
| MSI MS-7C51                   | 1        | 1%      |
| MSI MS-7B86                   | 1        | 1%      |
| MSI MS-7B33                   | 1        | 1%      |
| MSI MS-7978                   | 1        | 1%      |
| MSI MS-7641                   | 1        | 1%      |
| MSI MS-7501                   | 1        | 1%      |
| MSI MS-7267                   | 1        | 1%      |
| MSI MS-7032                   | 1        | 1%      |
| Inventec DQ                   | 1        | 1%      |
| Intel X79                     | 1        | 1%      |
| Intel H61                     | 1        | 1%      |
| Intel BTC-T37                 | 1        | 1%      |
| IceWhale ZimaBoard            | 1        | 1%      |
| HP Z400                       | 1        | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2008 | 10       | 10%     |
| 2010 | 9        | 9%      |
| 2009 | 9        | 9%      |
| 2019 | 8        | 8%      |
| 2020 | 7        | 7%      |
| 2018 | 7        | 7%      |
| 2017 | 7        | 7%      |
| 2021 | 5        | 5%      |
| 2014 | 5        | 5%      |
| 2013 | 5        | 5%      |
| 2012 | 5        | 5%      |
| 2011 | 5        | 5%      |
| 2007 | 5        | 5%      |
| 2022 | 4        | 4%      |
| 2015 | 4        | 4%      |
| 2016 | 2        | 2%      |
| 2006 | 2        | 2%      |
| 2001 | 1        | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 100      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 98       | 98%     |
| Enabled  | 2        | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 100      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 20       | 19.61%  |
| 3.01-4.0    | 19       | 18.63%  |
| 16.01-24.0  | 15       | 14.71%  |
| 8.01-16.0   | 14       | 13.73%  |
| 1.01-2.0    | 13       | 12.75%  |
| 32.01-64.0  | 11       | 10.78%  |
| 64.01-256.0 | 4        | 3.92%   |
| 2.01-3.0    | 3        | 2.94%   |
| 0.51-1.0    | 3        | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 45       | 42.06%  |
| 2.01-3.0  | 21       | 19.63%  |
| 0.51-1.0  | 20       | 18.69%  |
| 4.01-8.0  | 12       | 11.21%  |
| 8.01-16.0 | 4        | 3.74%   |
| 3.01-4.0  | 3        | 2.8%    |
| 0.01-0.5  | 2        | 1.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 50       | 50%     |
| 2      | 30       | 30%     |
| 3      | 10       | 10%     |
| 5      | 3        | 3%      |
| 4      | 3        | 3%      |
| 12     | 1        | 1%      |
| 7      | 1        | 1%      |
| 6      | 1        | 1%      |
| 0      | 1        | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 62.38%  |
| Yes       | 38       | 37.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 98       | 98%     |
| No        | 2        | 2%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 56%     |
| Yes       | 44       | 44%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 79       | 77.45%  |
| Yes       | 23       | 22.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 18       | 18%     |
| France     | 15       | 15%     |
| Germany    | 10       | 10%     |
| Spain      | 7        | 7%      |
| Italy      | 6        | 6%      |
| Poland     | 5        | 5%      |
| Brazil     | 5        | 5%      |
| UK         | 4        | 4%      |
| Argentina  | 4        | 4%      |
| Australia  | 3        | 3%      |
| Sweden     | 2        | 2%      |
| Costa Rica | 2        | 2%      |
| Venezuela  | 1        | 1%      |
| Ukraine    | 1        | 1%      |
| Turkey     | 1        | 1%      |
| Taiwan     | 1        | 1%      |
| Russia     | 1        | 1%      |
| Romania    | 1        | 1%      |
| Peru       | 1        | 1%      |
| Pakistan   | 1        | 1%      |
| Mexico     | 1        | 1%      |
| Luxembourg | 1        | 1%      |
| Latvia     | 1        | 1%      |
| Ireland    | 1        | 1%      |
| Iran       | 1        | 1%      |
| Indonesia  | 1        | 1%      |
| Greece     | 1        | 1%      |
| Finland    | 1        | 1%      |
| Czechia    | 1        | 1%      |
| Bulgaria   | 1        | 1%      |
| Belgium    | 1        | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 3        | 2.83%   |
| Melbourne              | 2        | 1.89%   |
| Largo                  | 2        | 1.89%   |
| Karlstad               | 2        | 1.89%   |
| Heredia                | 2        | 1.89%   |
| Yaroslavl              | 1        | 0.94%   |
| Woking                 | 1        | 0.94%   |
| Wetteren               | 1        | 0.94%   |
| Washington             | 1        | 0.94%   |
| Warsaw                 | 1        | 0.94%   |
| Villingen-Schwenningen | 1        | 0.94%   |
| Villa Ballester        | 1        | 0.94%   |
| Versailles             | 1        | 0.94%   |
| Varna                  | 1        | 0.94%   |
| Valentigney            | 1        | 0.94%   |
| Valencia               | 1        | 0.94%   |
| Tychy                  | 1        | 0.94%   |
| Turin                  | 1        | 0.94%   |
| Torrejón de Ardoz     | 1        | 0.94%   |
| Tehran                 | 1        | 0.94%   |
| Tandil                 | 1        | 0.94%   |
| Taipei                 | 1        | 0.94%   |
| St Louis               | 1        | 0.94%   |
| Sonico                 | 1        | 0.94%   |
| Sarcelles              | 1        | 0.94%   |
| Sao Paulo              | 1        | 0.94%   |
| Sao José dos Campos   | 1        | 0.94%   |
| Saltsjoe-Boo           | 1        | 0.94%   |
| Riverenert             | 1        | 0.94%   |
| Rio Segundo            | 1        | 0.94%   |
| Richmond               | 1        | 0.94%   |
| Resistencia            | 1        | 0.94%   |
| Prague                 | 1        | 0.94%   |
| Port Washington        | 1        | 0.94%   |
| Poitiers               | 1        | 0.94%   |
| Perth                  | 1        | 0.94%   |
| Palencia               | 1        | 0.94%   |
| Ostrów Wielkopolski   | 1        | 0.94%   |
| Oberkotzau             | 1        | 0.94%   |
| Novo Gama              | 1        | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 29       | 42     | 18.13%  |
| Samsung Electronics         | 24       | 35     | 15%     |
| WDC                         | 23       | 38     | 14.38%  |
| Kingston                    | 13       | 18     | 8.13%   |
| Hitachi                     | 13       | 17     | 8.13%   |
| SanDisk                     | 7        | 7      | 4.38%   |
| Crucial                     | 5        | 5      | 3.13%   |
| Unknown                     | 4        | 4      | 2.5%    |
| Toshiba                     | 3        | 3      | 1.88%   |
| HGST                        | 3        | 3      | 1.88%   |
| A-DATA Technology           | 3        | 3      | 1.88%   |
| PNY                         | 2        | 2      | 1.25%   |
| Maxtor                      | 2        | 2      | 1.25%   |
| GOODRAM                     | 2        | 2      | 1.25%   |
| China                       | 2        | 2      | 1.25%   |
| Apple                       | 2        | 2      | 1.25%   |
| Apacer                      | 2        | 2      | 1.25%   |
| WD MediaMax                 | 1        | 1      | 0.63%   |
| Transcend                   | 1        | 2      | 0.63%   |
| TO Exter                    | 1        | 1      | 0.63%   |
| Team                        | 1        | 1      | 0.63%   |
| T-FORCE                     | 1        | 1      | 0.63%   |
| RSH-319                     | 1        | 1      | 0.63%   |
| Patriot                     | 1        | 1      | 0.63%   |
| Micron/Crucial Technology   | 1        | 2      | 0.63%   |
| LITEONIT                    | 1        | 1      | 0.63%   |
| Kston                       | 1        | 3      | 0.63%   |
| Kingston Technology Company | 1        | 1      | 0.63%   |
| KINGBANK                    | 1        | 2      | 0.63%   |
| Intel                       | 1        | 1      | 0.63%   |
| HGST HUS                    | 1        | 2      | 0.63%   |
| Gigabyte Technology         | 1        | 1      | 0.63%   |
| External                    | 1        | 1      | 0.63%   |
| Emtec                       | 1        | 1      | 0.63%   |
| Dogfish                     | 1        | 1      | 0.63%   |
| BR                          | 1        | 1      | 0.63%   |
| Apricorn                    | 1        | 1      | 0.63%   |
| AMD                         | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 6        | 3.26%   |
| Kingston SA400S37240G 240GB SSD    | 6        | 3.26%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.09%   |
| Seagate ST3120213AS 120GB          | 2        | 1.09%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 1.09%   |
| SanDisk DF4032  32GB               | 2        | 1.09%   |
| Samsung SSD 970 EVO Plus 250GB     | 2        | 1.09%   |
| Samsung SSD 870 EVO 500GB          | 2        | 1.09%   |
| Samsung HD502HJ 500GB              | 2        | 1.09%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.09%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 1        | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD     | 1        | 0.54%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.54%   |
| WDC WD800BB-00CAA1 80GB            | 1        | 0.54%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 0.54%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1        | 0.54%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.54%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 0.54%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.54%   |
| WDC WD40EZRX-00SPEB0 4TB           | 1        | 0.54%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.54%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 1        | 0.54%   |
| WDC WD3200BPVT-00HXZT3 320GB       | 1        | 0.54%   |
| WDC WD3200AAKS-75L9A0 320GB        | 1        | 0.54%   |
| WDC WD3200AAJS-65M0A0 320GB        | 1        | 0.54%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 0.54%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.54%   |
| WDC WD3200AACS-00M6B0 320GB        | 1        | 0.54%   |
| WDC WD30EZRZ-00GXCB0 3TB           | 1        | 0.54%   |
| WDC WD2500KS-00MJB0 250GB          | 1        | 0.54%   |
| WDC WD2500AAJS-07M0A0 250GB        | 1        | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.54%   |
| WDC WD20EZBX-00AYRA0 2TB           | 1        | 0.54%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 1        | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 0.54%   |
| WDC WD2003FYYS-02W0B0 2TB          | 1        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 41     | 35.8%   |
| WDC                 | 20       | 31     | 24.69%  |
| Hitachi             | 13       | 17     | 16.05%  |
| Samsung Electronics | 6        | 7      | 7.41%   |
| Toshiba             | 3        | 3      | 3.7%    |
| HGST                | 3        | 3      | 3.7%    |
| Maxtor              | 2        | 2      | 2.47%   |
| WD MediaMax         | 1        | 1      | 1.23%   |
| RSH-319             | 1        | 1      | 1.23%   |
| External            | 1        | 1      | 1.23%   |
| Apricorn            | 1        | 1      | 1.23%   |
| Apple               | 1        | 1      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 12       | 17     | 21.05%  |
| Samsung Electronics | 11       | 19     | 19.3%   |
| SanDisk             | 5        | 5      | 8.77%   |
| WDC                 | 4        | 4      | 7.02%   |
| PNY                 | 2        | 2      | 3.51%   |
| GOODRAM             | 2        | 2      | 3.51%   |
| Crucial             | 2        | 2      | 3.51%   |
| China               | 2        | 2      | 3.51%   |
| Apacer              | 2        | 2      | 3.51%   |
| A-DATA Technology   | 2        | 2      | 3.51%   |
| Transcend           | 1        | 2      | 1.75%   |
| TO Exter            | 1        | 1      | 1.75%   |
| Team                | 1        | 1      | 1.75%   |
| Patriot             | 1        | 1      | 1.75%   |
| LITEONIT            | 1        | 1      | 1.75%   |
| Kston               | 1        | 3      | 1.75%   |
| KINGBANK            | 1        | 2      | 1.75%   |
| Intel               | 1        | 1      | 1.75%   |
| Gigabyte Technology | 1        | 1      | 1.75%   |
| Emtec               | 1        | 1      | 1.75%   |
| Dogfish             | 1        | 1      | 1.75%   |
| BR                  | 1        | 1      | 1.75%   |
| Apple               | 1        | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 61       | 109    | 45.19%  |
| SSD     | 50       | 74     | 37.04%  |
| NVMe    | 16       | 21     | 11.85%  |
| MMC     | 7        | 7      | 5.19%   |
| Unknown | 1        | 3      | 0.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 90       | 179    | 76.92%  |
| NVMe | 16       | 21     | 13.68%  |
| MMC  | 7        | 7      | 5.98%   |
| SAS  | 4        | 7      | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 115    | 62.5%   |
| 0.51-1.0   | 20       | 28     | 16.67%  |
| 1.01-2.0   | 14       | 23     | 11.67%  |
| 2.01-3.0   | 4        | 5      | 3.33%   |
| 4.01-10.0  | 4        | 7      | 3.33%   |
| 3.01-4.0   | 3        | 5      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 27       | 26.21%  |
| 251-500        | 18       | 17.48%  |
| 21-50          | 12       | 11.65%  |
| 1001-2000      | 11       | 10.68%  |
| More than 3000 | 10       | 9.71%   |
| 501-1000       | 7        | 6.8%    |
| 51-100         | 7        | 6.8%    |
| 1-20           | 6        | 5.83%   |
| 2001-3000      | 5        | 4.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 45       | 42.45%  |
| 21-50          | 17       | 16.04%  |
| 101-250        | 12       | 11.32%  |
| 51-100         | 9        | 8.49%   |
| 501-1000       | 7        | 6.6%    |
| More than 3000 | 5        | 4.72%   |
| 1001-2000      | 5        | 4.72%   |
| 251-500        | 4        | 3.77%   |
| 2001-3000      | 2        | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 2      | 5.26%   |
| WDC WD3200AACS-00M6B0 320GB         | 1        | 1      | 5.26%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1      | 5.26%   |
| WDC WD2003FYYS-02W0B0 2TB           | 1        | 1      | 5.26%   |
| WDC WD10SPZX-08Z10 1TB              | 1        | 1      | 5.26%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 5.26%   |
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 5.26%   |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 5.26%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 2      | 5.26%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 5.26%   |
| Maxtor 6L200M0 208GB                | 1        | 1      | 5.26%   |
| Hitachi HTS545016B9A300 160GB       | 1        | 1      | 5.26%   |
| Hitachi HTS543216L9A300 160GB       | 1        | 1      | 5.26%   |
| Hitachi HTE545050B9A300 500GB       | 1        | 1      | 5.26%   |
| Apple HDD HTS547550A9E384 500GB     | 1        | 1      | 5.26%   |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 5.26%   |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 8      | 29.41%  |
| Seagate             | 3        | 4      | 17.65%  |
| Hitachi             | 3        | 3      | 17.65%  |
| Toshiba             | 1        | 1      | 5.88%   |
| Samsung Electronics | 1        | 1      | 5.88%   |
| Maxtor              | 1        | 1      | 5.88%   |
| Apple               | 1        | 1      | 5.88%   |
| Apacer              | 1        | 1      | 5.88%   |
| A-DATA Technology   | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 8      | 33.33%  |
| Seagate             | 3        | 4      | 20%     |
| Hitachi             | 3        | 3      | 20%     |
| Toshiba             | 1        | 1      | 6.67%   |
| Samsung Electronics | 1        | 1      | 6.67%   |
| Maxtor              | 1        | 1      | 6.67%   |
| Apple               | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 19     | 87.5%   |
| SSD  | 2        | 2      | 12.5%   |

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
| Works    | 52       | 95     | 45.22%  |
| Detected | 44       | 95     | 38.26%  |
| Malfunc  | 16       | 21     | 13.91%  |
| Failed   | 3        | 3      | 2.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 59       | 44.7%   |
| AMD                         | 31       | 23.48%  |
| Samsung Electronics         | 8        | 6.06%   |
| ASMedia Technology          | 7        | 5.3%    |
| JMicron Technology          | 5        | 3.79%   |
| Nvidia                      | 4        | 3.03%   |
| Micron/Crucial Technology   | 4        | 3.03%   |
| VIA Technologies            | 3        | 2.27%   |
| SanDisk                     | 3        | 2.27%   |
| Marvell Technology Group    | 2        | 1.52%   |
| Kingston Technology Company | 2        | 1.52%   |
| Seagate Technology          | 1        | 0.76%   |
| LSI Logic / Symbios Logic   | 1        | 0.76%   |
| Apple                       | 1        | 0.76%   |
| ADATA Technology            | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19       | 10.5%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14       | 7.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13       | 7.18%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6        | 3.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6        | 3.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5        | 2.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 2.76%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 2.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 2.21%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3        | 1.66%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.66%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 1.66%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 1.1%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 1.1%    |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.1%    |
| Nvidia MCP61 IDE                                                               | 2        | 1.1%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2        | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.1%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2        | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2        | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.1%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 1.1%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2        | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.1%    |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.1%    |
| AMD FCH IDE Controller                                                         | 2        | 1.1%    |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 0.55%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 1        | 0.55%   |
| VIA Serial ATA Controller                                                      | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 51.56%  |
| IDE  | 40       | 31.25%  |
| NVMe | 16       | 12.5%   |
| RAID | 5        | 3.91%   |
| SAS  | 1        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 64%     |
| AMD    | 36       | 36%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 3%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3        | 3%      |
| Intel Atom CPU D525 @ 1.80GHz                   | 3        | 3%      |
| Intel Pentium Dual CPU E2140 @ 1.60GHz          | 2        | 2%      |
| Intel Pentium D CPU 2.80GHz                     | 2        | 2%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 2%      |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2        | 2%      |
| Intel Celeron CPU N3350 @ 1.10GHz               | 2        | 2%      |
| Intel Celeron CPU J1900 @ 1.99GHz               | 2        | 2%      |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 2%      |
| AMD Ryzen 7 2700 Eight-Core Processor           | 2        | 2%      |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 2%      |
| AMD GX-415GA SOC with Radeon HD Graphics        | 2        | 2%      |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 2        | 2%      |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 2%      |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 1%      |
| Intel Xeon CPU E5520 @ 2.27GHz                  | 1        | 1%      |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz             | 1        | 1%      |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz             | 1        | 1%      |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 1%      |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 1%      |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 1%      |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 1%      |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1%      |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1%      |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 1%      |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1%      |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1%      |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 1%      |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1%      |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 1%      |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1%      |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1%      |
| Intel Core i3-8100T CPU @ 3.10GHz               | 1        | 1%      |
| Intel Core i3-4170 CPU @ 3.70GHz                | 1        | 1%      |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 1%      |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1%      |
| Intel Core i3-10105 CPU @ 3.70GHz               | 1        | 1%      |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 1        | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 13       | 13%     |
| Intel Core i5           | 10       | 10%     |
| Intel Atom              | 9        | 9%      |
| AMD Ryzen 7             | 7        | 7%      |
| Intel Core i3           | 6        | 6%      |
| Intel Core 2 Duo        | 6        | 6%      |
| AMD Ryzen 5             | 6        | 6%      |
| Intel Xeon              | 4        | 4%      |
| Intel Core 2 Quad       | 4        | 4%      |
| Intel Pentium Dual-Core | 3        | 3%      |
| Intel Pentium Dual      | 3        | 3%      |
| Intel Core i7           | 3        | 3%      |
| AMD Ryzen 9             | 3        | 3%      |
| AMD FX                  | 3        | 3%      |
| AMD Athlon 64 X2        | 3        | 3%      |
| Intel Pentium D         | 2        | 2%      |
| AMD Phenom II X4        | 2        | 2%      |
| AMD GX                  | 2        | 2%      |
| AMD A10                 | 2        | 2%      |
| Other                   | 1        | 1%      |
| Intel Core i9           | 1        | 1%      |
| AMD Ryzen 5 PRO         | 1        | 1%      |
| AMD Phenom II X6        | 1        | 1%      |
| AMD G                   | 1        | 1%      |
| AMD Athlon II X3        | 1        | 1%      |
| AMD Athlon II X2        | 1        | 1%      |
| AMD A8                  | 1        | 1%      |
| AMD A4                  | 1        | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 36%     |
| 4      | 35       | 35%     |
| 6      | 10       | 10%     |
| 8      | 9        | 9%      |
| 1      | 4        | 4%      |
| 3      | 3        | 3%      |
| 16     | 1        | 1%      |
| 12     | 1        | 1%      |
| 10     | 1        | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 99       | 99%     |
| 2      | 1        | 1%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 63%     |
| 2      | 37       | 37%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 100      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 45.63%  |
| 0x1067a    | 5        | 4.85%   |
| 0x406c4    | 4        | 3.88%   |
| 0x906ea    | 3        | 2.91%   |
| 0x106ca    | 3        | 2.91%   |
| 0x6fb      | 2        | 1.94%   |
| 0x306c3    | 2        | 1.94%   |
| 0x30679    | 2        | 1.94%   |
| 0x206a7    | 2        | 1.94%   |
| 0x0a201009 | 2        | 1.94%   |
| 0x0700010f | 2        | 1.94%   |
| 0x06003106 | 2        | 1.94%   |
| 0x010000db | 2        | 1.94%   |
| 0xa0653    | 1        | 0.97%   |
| 0x906eb    | 1        | 0.97%   |
| 0x906c0    | 1        | 0.97%   |
| 0x706a8    | 1        | 0.97%   |
| 0x706a1    | 1        | 0.97%   |
| 0x6fd      | 1        | 0.97%   |
| 0x506e3    | 1        | 0.97%   |
| 0x506ca    | 1        | 0.97%   |
| 0x506c9    | 1        | 0.97%   |
| 0x306e4    | 1        | 0.97%   |
| 0x306a9    | 1        | 0.97%   |
| 0x106a5    | 1        | 0.97%   |
| 0x10676    | 1        | 0.97%   |
| 0x10661    | 1        | 0.97%   |
| 0x0a601203 | 1        | 0.97%   |
| 0x0a50000d | 1        | 0.97%   |
| 0x0a50000c | 1        | 0.97%   |
| 0x0a50000b | 1        | 0.97%   |
| 0x08701021 | 1        | 0.97%   |
| 0x08701013 | 1        | 0.97%   |
| 0x0800820d | 1        | 0.97%   |
| 0x08001138 | 1        | 0.97%   |
| 0x06001119 | 1        | 0.97%   |
| 0x06000852 | 1        | 0.97%   |
| 0x010000c7 | 1        | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 12       | 12%     |
| Zen 3         | 7        | 7%      |
| Silvermont    | 7        | 7%      |
| Core          | 7        | 7%      |
| IvyBridge     | 6        | 6%      |
| K10           | 5        | 5%      |
| Bonnell       | 5        | 5%      |
| Zen+          | 4        | 4%      |
| KabyLake      | 4        | 4%      |
| K8 Hammer     | 4        | 4%      |
| Haswell       | 4        | 4%      |
| Zen 2         | 3        | 3%      |
| SandyBridge   | 3        | 3%      |
| Piledriver    | 3        | 3%      |
| Nehalem       | 3        | 3%      |
| Goldmont plus | 3        | 3%      |
| Zen           | 2        | 2%      |
| Steamroller   | 2        | 2%      |
| Skylake       | 2        | 2%      |
| NetBurst      | 2        | 2%      |
| Jaguar        | 2        | 2%      |
| Goldmont      | 2        | 2%      |
| CometLake     | 2        | 2%      |
| Westmere      | 1        | 1%      |
| Tremont       | 1        | 1%      |
| K10 Llano     | 1        | 1%      |
| Bulldozer     | 1        | 1%      |
| Bobcat        | 1        | 1%      |
| Unknown       | 1        | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 34.29%  |
| Nvidia | 35       | 33.33%  |
| AMD    | 34       | 32.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 5.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 4.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 3.64%   |
| Nvidia GT218 [ION]                                                                       | 3        | 2.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 2.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 2.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 2.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.73%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 2.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.82%   |
| Intel HD Graphics 500                                                                    | 2        | 1.82%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.82%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.82%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 1.82%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 1.82%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2        | 1.82%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.82%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.82%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.91%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.91%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.91%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.91%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.91%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 0.91%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 0.91%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.91%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 0.91%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.91%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.91%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 0.91%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 1        | 0.91%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 0.91%   |
| Nvidia GA104GL [RTX A4000]                                                               | 1        | 0.91%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 33       | 33%     |
| 1 x Nvidia         | 32       | 32%     |
| 1 x AMD            | 28       | 28%     |
| 2 x AMD            | 3        | 3%      |
| AMD + Nvidia       | 2        | 2%      |
| Intel + 2 x Nvidia | 1        | 1%      |
| Intel + 2 x AMD    | 1        | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 81       | 81%     |
| Proprietary | 14       | 14%     |
| Unknown     | 5        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 64       | 63.37%  |
| 0.01-0.5   | 11       | 10.89%  |
| 0.51-1.0   | 10       | 9.9%    |
| 7.01-8.0   | 5        | 4.95%   |
| 8.01-16.0  | 4        | 3.96%   |
| 1.01-2.0   | 3        | 2.97%   |
| 3.01-4.0   | 2        | 1.98%   |
| 5.01-6.0   | 1        | 0.99%   |
| 2.01-3.0   | 1        | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 15       | 16.85%  |
| Dell                 | 10       | 11.24%  |
| Hewlett-Packard      | 8        | 8.99%   |
| Philips              | 6        | 6.74%   |
| Goldstar             | 6        | 6.74%   |
| Acer                 | 5        | 5.62%   |
| Ancor Communications | 4        | 4.49%   |
| Iiyama               | 3        | 3.37%   |
| Eizo                 | 3        | 3.37%   |
| Sony                 | 2        | 2.25%   |
| MSI                  | 2        | 2.25%   |
| HannStar             | 2        | 2.25%   |
| BenQ                 | 2        | 2.25%   |
| Westinghouse         | 1        | 1.12%   |
| Vizio                | 1        | 1.12%   |
| ViewSonic            | 1        | 1.12%   |
| VHT                  | 1        | 1.12%   |
| Unknown (ADA)        | 1        | 1.12%   |
| Unknown              | 1        | 1.12%   |
| SNC                  | 1        | 1.12%   |
| Sharp                | 1        | 1.12%   |
| SFX                  | 1        | 1.12%   |
| Sampo                | 1        | 1.12%   |
| RTK                  | 1        | 1.12%   |
| Positivo             | 1        | 1.12%   |
| Pixio                | 1        | 1.12%   |
| NEC Computers        | 1        | 1.12%   |
| LG Electronics       | 1        | 1.12%   |
| Jean                 | 1        | 1.12%   |
| HJW                  | 1        | 1.12%   |
| Daewoo               | 1        | 1.12%   |
| Compal               | 1        | 1.12%   |
| Belinea              | 1        | 1.12%   |
| AOC                  | 1        | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 2.17%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1        | 1.09%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1        | 1.09%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 1.09%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 1.09%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 1.09%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1        | 1.09%   |
| Sony TV SNY9C01 1360x768                                             | 1        | 1.09%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1        | 1.09%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 1.09%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 1.09%   |
| SFX 4K EXTENDER SFX0100 3840x2160 1872x1053mm 84.6-inch              | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch  | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 1.09%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.09%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 1.09%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 1.09%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 1.09%   |
| Samsung Electronics S/M 550v SAM12B6 1024x768 267x200mm 13.1-inch    | 1        | 1.09%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 1.09%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 1.09%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 1.09%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 697x392mm 31.5-inch    | 1        | 1.09%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch    | 1        | 1.09%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 1.09%   |
| RTK ARZOPA RTKBC33 1920x1080 309x174mm 14.0-inch                     | 1        | 1.09%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 1.09%   |
| Pixio DP ICB3500 3440x1440 708x399mm 32.0-inch                       | 1        | 1.09%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 1.09%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 1.09%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1        | 1.09%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1        | 1.09%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.09%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                   | 1        | 1.09%   |
| NEC Computers EA224WMi NEC68C1 1920x1080 476x268mm 21.5-inch         | 1        | 1.09%   |
| MSI MP242A MSI40A1 1920x1080 527x296mm 23.8-inch                     | 1        | 1.09%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                  | 1        | 1.09%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.09%   |
| Jean JT178x4 JEN0DB2 1280x1024 338x270mm 17.0-inch                   | 1        | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 35       | 39.33%  |
| 1280x1024 (SXGA)   | 10       | 11.24%  |
| 1680x1050 (WSXGA+) | 7        | 7.87%   |
| 1366x768 (WXGA)    | 7        | 7.87%   |
| 1600x900 (HD+)     | 6        | 6.74%   |
| 2560x1440 (QHD)    | 5        | 5.62%   |
| 1440x900 (WXGA+)   | 4        | 4.49%   |
| 3840x2160 (4K)     | 3        | 3.37%   |
| 1360x768           | 3        | 3.37%   |
| 1024x768 (XGA)     | 2        | 2.25%   |
| 800x600            | 1        | 1.12%   |
| 3440x1440          | 1        | 1.12%   |
| 2560x1600          | 1        | 1.12%   |
| 1920x1200 (WUXGA)  | 1        | 1.12%   |
| 1280x800 (WXGA)    | 1        | 1.12%   |
| 1280x768           | 1        | 1.12%   |
| 1280x720 (HD)      | 1        | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 11.49%  |
| 24      | 10       | 11.49%  |
| 18      | 9        | 10.34%  |
| 23      | 8        | 9.2%    |
| 19      | 8        | 9.2%    |
| 22      | 7        | 8.05%   |
| 21      | 6        | 6.9%    |
| Unknown | 6        | 6.9%    |
| 20      | 5        | 5.75%   |
| 17      | 3        | 3.45%   |
| 32      | 2        | 2.3%    |
| 15      | 2        | 2.3%    |
| 84      | 1        | 1.15%   |
| 72      | 1        | 1.15%   |
| 49      | 1        | 1.15%   |
| 47      | 1        | 1.15%   |
| 43      | 1        | 1.15%   |
| 34      | 1        | 1.15%   |
| 31      | 1        | 1.15%   |
| 14      | 1        | 1.15%   |
| 13      | 1        | 1.15%   |
| 8       | 1        | 1.15%   |
| 7       | 1        | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 30       | 34.48%  |
| 501-600     | 28       | 32.18%  |
| 301-350     | 6        | 6.9%    |
| Unknown     | 6        | 6.9%    |
| 351-400     | 5        | 5.75%   |
| 701-800     | 3        | 3.45%   |
| 1501-2000   | 2        | 2.3%    |
| 101-200     | 2        | 2.3%    |
| 1001-1500   | 2        | 2.3%    |
| 601-700     | 1        | 1.15%   |
| 201-300     | 1        | 1.15%   |
| 901-1000    | 1        | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 54       | 64.29%  |
| 16/10   | 12       | 14.29%  |
| 5/4     | 8        | 9.52%   |
| Unknown | 5        | 5.95%   |
| 4/3     | 4        | 4.76%   |
| 3/2     | 1        | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 24       | 27.91%  |
| 151-200        | 18       | 20.93%  |
| 301-350        | 10       | 11.63%  |
| 141-150        | 10       | 11.63%  |
| Unknown        | 6        | 6.98%   |
| More than 1000 | 3        | 3.49%   |
| 351-500        | 3        | 3.49%   |
| 251-300        | 3        | 3.49%   |
| 501-1000       | 3        | 3.49%   |
| 81-90          | 2        | 2.33%   |
| 1-40           | 2        | 2.33%   |
| 111-120        | 1        | 1.16%   |
| 101-110        | 1        | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 58       | 68.24%  |
| 101-120 | 14       | 16.47%  |
| Unknown | 6        | 7.06%   |
| 1-50    | 5        | 5.88%   |
| 161-240 | 2        | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 85       | 84.16%  |
| 2     | 10       | 9.9%    |
| 0     | 6        | 5.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 65       | 44.83%  |
| Intel                           | 31       | 21.38%  |
| Qualcomm Atheros                | 10       | 6.9%    |
| TP-Link                         | 6        | 4.14%   |
| Broadcom                        | 5        | 3.45%   |
| Nvidia                          | 3        | 2.07%   |
| NetGear                         | 3        | 2.07%   |
| MediaTek                        | 3        | 2.07%   |
| VIA Technologies                | 2        | 1.38%   |
| Samsung Electronics             | 2        | 1.38%   |
| Ralink Technology               | 2        | 1.38%   |
| Qualcomm Atheros Communications | 2        | 1.38%   |
| Xiaomi                          | 1        | 0.69%   |
| Trident Microsystems            | 1        | 0.69%   |
| Texas Instruments               | 1        | 0.69%   |
| Seeed Technology                | 1        | 0.69%   |
| Ralink                          | 1        | 0.69%   |
| Marvell Technology Group        | 1        | 0.69%   |
| ICS Advent                      | 1        | 0.69%   |
| Broadcom Limited                | 1        | 0.69%   |
| Belkin Components               | 1        | 0.69%   |
| ASUSTek Computer                | 1        | 0.69%   |
| Accton Technology               | 1        | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 56       | 35.67%  |
| Intel Ethernet Controller I225-V                                    | 5        | 3.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 4        | 2.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.91%   |
| Intel I211 Gigabit Network Connection                               | 3        | 1.91%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 2        | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2        | 1.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 1.27%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.27%   |
| Nvidia MCP77 Ethernet                                               | 2        | 1.27%   |
| NetGear A6210                                                       | 2        | 1.27%   |
| Intel Wi-Fi 6 AX200                                                 | 2        | 1.27%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 1.27%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 1.27%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 1        | 0.64%   |
| Trident Microsystems 4DWave DX                                      | 1        | 0.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.64%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 0.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.64%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.64%   |
| Texas Instruments CC2531 ZigBee                                     | 1        | 0.64%   |
| Seeed Seeeduino_Cortex_M0+                                          | 1        | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.64%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.64%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.64%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.64%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                   | 1        | 0.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.64%   |
| Realtek 802.11ac NIC                                                | 1        | 0.64%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 23.4%   |
| Intel                           | 11       | 23.4%   |
| TP-Link                         | 5        | 10.64%  |
| Qualcomm Atheros                | 4        | 8.51%   |
| MediaTek                        | 3        | 6.38%   |
| Broadcom                        | 3        | 6.38%   |
| Ralink Technology               | 2        | 4.26%   |
| Qualcomm Atheros Communications | 2        | 4.26%   |
| NetGear                         | 2        | 4.26%   |
| Ralink                          | 1        | 2.13%   |
| Broadcom Limited                | 1        | 2.13%   |
| Belkin Components               | 1        | 2.13%   |
| ASUSTek Computer                | 1        | 2.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 4.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 2        | 4.26%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 2        | 4.26%   |
| Qualcomm Atheros AR9271 802.11n                                            | 2        | 4.26%   |
| NetGear A6210                                                              | 2        | 4.26%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 4.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 4.26%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller        | 2        | 4.26%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                      | 1        | 2.13%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                     | 1        | 2.13%   |
| TP-Link 802.11ac NIC                                                       | 1        | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 2.13%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 2.13%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1        | 2.13%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                     | 1        | 2.13%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                    | 1        | 2.13%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 2.13%   |
| Realtek 802.11ac NIC                                                       | 1        | 2.13%   |
| Ralink RT5572 Wireless Adapter                                             | 1        | 2.13%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 2.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1        | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 1        | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1        | 2.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1        | 2.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter              | 1        | 2.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                    | 1        | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1        | 2.13%   |
| Intel Wireless 7265                                                        | 1        | 2.13%   |
| Intel Wireless 3165                                                        | 1        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1        | 2.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1        | 2.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1        | 2.13%   |
| Intel Centrino Advanced-N 6235                                             | 1        | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1        | 2.13%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                    | 1        | 2.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                          | 1        | 2.13%   |
| Belkin Components F5D8053 N Wireless USB Adapter v6000 [Realtek RTL8192SU] | 1        | 2.13%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]             | 1        | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 62       | 57.94%  |
| Intel                    | 22       | 20.56%  |
| Qualcomm Atheros         | 7        | 6.54%   |
| Nvidia                   | 3        | 2.8%    |
| VIA Technologies         | 2        | 1.87%   |
| Samsung Electronics      | 2        | 1.87%   |
| Broadcom                 | 2        | 1.87%   |
| Xiaomi                   | 1        | 0.93%   |
| Trident Microsystems     | 1        | 0.93%   |
| TP-Link                  | 1        | 0.93%   |
| NetGear                  | 1        | 0.93%   |
| Marvell Technology Group | 1        | 0.93%   |
| ICS Advent               | 1        | 0.93%   |
| Accton Technology        | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56       | 51.85%  |
| Intel Ethernet Controller I225-V                                  | 5        | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 1.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.85%   |
| Nvidia MCP77 Ethernet                                             | 2        | 1.85%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.93%   |
| Trident Microsystems 4DWave DX                                    | 1        | 0.93%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.93%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.93%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.93%   |
| NetGear LB1120-100NAS                                             | 1        | 0.93%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.93%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.93%   |
| Intel 82567V-3 Gigabit Network Connection                         | 1        | 0.93%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 0.93%   |
| ICS Advent 10/100M LAN                                            | 1        | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.93%   |
| Accton SMC2-1211TX                                                | 1        | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 98       | 68.06%  |
| WiFi     | 44       | 30.56%  |
| Modem    | 2        | 1.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 75       | 72.12%  |
| WiFi     | 29       | 27.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 66       | 66%     |
| 2     | 28       | 28%     |
| 3     | 3        | 3%      |
| 0     | 2        | 2%      |
| 4     | 1        | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 72%     |
| Yes  | 28       | 28%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 10       | 41.67%  |
| Cambridge Silicon Radio         | 4        | 16.67%  |
| Realtek Semiconductor           | 2        | 8.33%   |
| MediaTek                        | 2        | 8.33%   |
| Foxconn / Hon Hai               | 2        | 8.33%   |
| TP-Link                         | 1        | 4.17%   |
| Qualcomm Atheros Communications | 1        | 4.17%   |
| Logitech                        | 1        | 4.17%   |
| Broadcom                        | 1        | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 16.67%  |
| MediaTek Wireless_Device                            | 2        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 8.33%   |
| Intel Bluetooth wireless interface                  | 2        | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 8.33%   |
| Intel AX200 Bluetooth                               | 2        | 8.33%   |
| TP-Link UB500 Adapter                               | 1        | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.17%   |
| Realtek Bluetooth Radio                             | 1        | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 4.17%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4.17%   |
| Intel AX210 Bluetooth                               | 1        | 4.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 4.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 4.17%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 57       | 39.04%  |
| AMD                                          | 40       | 27.4%   |
| Nvidia                                       | 29       | 19.86%  |
| C-Media Electronics                          | 4        | 2.74%   |
| VIA Technologies                             | 3        | 2.05%   |
| ASUSTek Computer                             | 2        | 1.37%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.68%   |
| Texas Instruments                            | 1        | 0.68%   |
| Sony                                         | 1        | 0.68%   |
| Razer USA                                    | 1        | 0.68%   |
| Plantronics                                  | 1        | 0.68%   |
| Micro Star International                     | 1        | 0.68%   |
| JMTek                                        | 1        | 0.68%   |
| GN Netcom                                    | 1        | 0.68%   |
| Focusrite-Novation                           | 1        | 0.68%   |
| Ensoniq                                      | 1        | 0.68%   |
| Creative Labs                                | 1        | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 17       | 10.06%  |
| Nvidia High Definition Audio Controller                                           | 7        | 4.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 4.14%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 3.55%   |
| AMD FCH Azalia Controller                                                         | 6        | 3.55%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 2.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4        | 2.37%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 2.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 2.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 2.37%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 1.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 1.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 1.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 1.78%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 3        | 1.78%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.78%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.18%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.18%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2        | 1.18%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 1.18%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 1.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.18%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.18%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.18%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1        | 0.59%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 20.27%  |
| SK hynix            | 8        | 10.81%  |
| Micron Technology   | 8        | 10.81%  |
| Kingston            | 7        | 9.46%   |
| Samsung Electronics | 6        | 8.11%   |
| G.Skill             | 6        | 8.11%   |
| Corsair             | 6        | 8.11%   |
| Unknown             | 4        | 5.41%   |
| Unknown (ABCD)      | 3        | 4.05%   |
| Crucial             | 3        | 4.05%   |
| Patriot             | 2        | 2.7%    |
| A-DATA Technology   | 2        | 2.7%    |
| Unknown (AB)        | 1        | 1.35%   |
| Nanya Technology    | 1        | 1.35%   |
| GOODRAM             | 1        | 1.35%   |
| Elpida              | 1        | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 4        | 4.94%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 3        | 3.7%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 2.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2        | 2.47%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 2        | 2.47%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 2        | 2.47%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                     | 1        | 1.23%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 1.23%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                       | 1        | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                       | 1        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 1        | 1.23%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.23%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 1.23%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 1.23%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s       | 1        | 1.23%   |
| Unknown (AB) RAM Module 1GB DIMM LPDDR4 1600MT/s               | 1        | 1.23%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 1.23%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                     | 1        | 1.23%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 1        | 1.23%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2666MT/s                  | 1        | 1.23%   |
| SK hynix RAM HMT451S6BFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 1.23%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 1        | 1.23%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.23%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.23%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.23%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                | 1        | 1.23%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.23%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.23%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s            | 1        | 1.23%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s                | 1        | 1.23%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s                  | 1        | 1.23%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 1        | 1.23%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 1.23%   |
| Micron RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 1        | 1.23%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s       | 1        | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 34.33%  |
| DDR3    | 21       | 31.34%  |
| DDR2    | 10       | 14.93%  |
| SDRAM   | 4        | 5.97%   |
| Unknown | 4        | 5.97%   |
| LPDDR4  | 3        | 4.48%   |
| DDR5    | 1        | 1.49%   |
| DDR     | 1        | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 54       | 81.82%  |
| SODIMM | 12       | 18.18%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 25.68%  |
| 4096  | 19       | 25.68%  |
| 2048  | 19       | 25.68%  |
| 16384 | 11       | 14.86%  |
| 32768 | 3        | 4.05%   |
| 1024  | 3        | 4.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 22.54%  |
| 3200    | 7        | 9.86%   |
| 1333    | 7        | 9.86%   |
| 2400    | 5        | 7.04%   |
| 800     | 5        | 7.04%   |
| 2667    | 3        | 4.23%   |
| 667     | 3        | 4.23%   |
| Unknown | 3        | 4.23%   |
| 3400    | 2        | 2.82%   |
| 2800    | 2        | 2.82%   |
| 2666    | 2        | 2.82%   |
| 2133    | 2        | 2.82%   |
| 1866    | 2        | 2.82%   |
| 1066    | 2        | 2.82%   |
| 4800    | 1        | 1.41%   |
| 3933    | 1        | 1.41%   |
| 3866    | 1        | 1.41%   |
| 3666    | 1        | 1.41%   |
| 3600    | 1        | 1.41%   |
| 3534    | 1        | 1.41%   |
| 3066    | 1        | 1.41%   |
| 2048    | 1        | 1.41%   |
| 533     | 1        | 1.41%   |
| 333     | 1        | 1.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 2        | 50%     |
| Samsung Electronics | 1        | 25%     |
| Brother Industries  | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung SCX-4200 series | 1        | 25%     |
| Canon PIXMA MP250       | 1        | 25%     |
| Canon LiDE 300          | 1        | 25%     |
| Brother DCP-7055W       | 1        | 25%     |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 5        | 50%     |
| WaveRider Communications | 1        | 10%     |
| Pixart Imaging           | 1        | 10%     |
| Microsoft                | 1        | 10%     |
| Generalplus Technology   | 1        | 10%     |
| AVerMedia Technologies   | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 3        | 30%     |
| WaveRider USB Live camera                | 1        | 10%     |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1        | 10%     |
| Microsoft LifeCam VX-800                 | 1        | 10%     |
| Logitech Webcam C170                     | 1        | 10%     |
| Logitech HD Webcam C615                  | 1        | 10%     |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 10%     |
| AVerMedia Live Streamer CAM 313          | 1        | 10%     |

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
| 0     | 86       | 85.15%  |
| 1     | 12       | 11.88%  |
| 2     | 3        | 2.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 41.18%  |
| Net/wireless             | 4        | 23.53%  |
| Communication controller | 2        | 11.76%  |
| Unassigned class         | 1        | 5.88%   |
| Storage/raid             | 1        | 5.88%   |
| Sound                    | 1        | 5.88%   |
| Net/ethernet             | 1        | 5.88%   |

