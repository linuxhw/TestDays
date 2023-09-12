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

Total: 122

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 5.15.0-43-generic             | 11       | 10.58%  |
| 5.19.0-50-generic             | 5        | 4.81%   |
| 5.19.0-32-generic             | 5        | 4.81%   |
| 5.15.0-60-generic             | 5        | 4.81%   |
| 5.15.0-41-generic             | 5        | 4.81%   |
| 5.15.0-56-generic             | 4        | 3.85%   |
| 5.15.0-47-generic             | 4        | 3.85%   |
| 5.15.0-25-generic             | 4        | 3.85%   |
| 5.15.0-75-generic             | 3        | 2.88%   |
| 5.15.0-67-generic             | 3        | 2.88%   |
| 5.15.0-52-generic             | 3        | 2.88%   |
| 5.15.0-48-generic             | 3        | 2.88%   |
| 5.15.0-40-generic             | 3        | 2.88%   |
| 5.15.0-39-generic             | 3        | 2.88%   |
| 6.2.0-26-generic              | 2        | 1.92%   |
| 5.19.0-46-generic             | 2        | 1.92%   |
| 5.19.0-43-generic             | 2        | 1.92%   |
| 5.19.0-35-generic             | 2        | 1.92%   |
| 5.15.0-82-generic             | 2        | 1.92%   |
| 5.15.0-58-generic             | 2        | 1.92%   |
| 5.15.0-53-generic             | 2        | 1.92%   |
| 5.15.0-50-generic             | 2        | 1.92%   |
| 5.15.0-46-generic             | 2        | 1.92%   |
| 5.15.0-35-generic             | 2        | 1.92%   |
| 5.15.0-30-generic             | 2        | 1.92%   |
| 5.15.0-27-generic             | 2        | 1.92%   |
| 6.3.3-custom                  | 1        | 0.96%   |
| 6.2.8-x64v3-xanmod1           | 1        | 0.96%   |
| 6.1.0-custom                  | 1        | 0.96%   |
| 6.0.8-060008-generic          | 1        | 0.96%   |
| 6.0.14                        | 1        | 0.96%   |
| 5.19.0-45-generic             | 1        | 0.96%   |
| 5.19.0-41-generic             | 1        | 0.96%   |
| 5.19.0-16.2-liquorix-amd64    | 1        | 0.96%   |
| 5.19.0-1010-nvidia-lowlatency | 1        | 0.96%   |
| 5.15.0-72-generic             | 1        | 0.96%   |
| 5.15.0-71-generic             | 1        | 0.96%   |
| 5.15.0-69-lowlatency          | 1        | 0.96%   |
| 5.15.0-59-lowlatency          | 1        | 0.96%   |
| 5.15.0-58-lowlatency          | 1        | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 71       | 73.2%   |
| 5.19.0  | 19       | 19.59%  |
| 6.2.0   | 2        | 2.06%   |
| 6.3.3   | 1        | 1.03%   |
| 6.2.8   | 1        | 1.03%   |
| 6.1.0   | 1        | 1.03%   |
| 6.0.8   | 1        | 1.03%   |
| 6.0.14  | 1        | 1.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 71       | 73.2%   |
| 5.19    | 19       | 19.59%  |
| 6.2     | 3        | 3.09%   |
| 6.0     | 2        | 2.06%   |
| 6.3     | 1        | 1.03%   |
| 6.1     | 1        | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 93       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LXQt | 89       | 95.7%   |
| LXDE | 3        | 3.23%   |
| XFCE | 1        | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 89       | 92.71%  |
| Tty         | 5        | 5.21%   |
| Wayland     | 1        | 1.04%   |
| Unspecified | 1        | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 78       | 83.87%  |
| LightDM | 6        | 6.45%   |
| Unknown | 5        | 5.38%   |
| XDM     | 1        | 1.08%   |
| SLiM    | 1        | 1.08%   |
| LXDM    | 1        | 1.08%   |
| GDM3    | 1        | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 27       | 28.72%  |
| fr_FR | 14       | 14.89%  |
| de_DE | 8        | 8.51%   |
| it_IT | 6        | 6.38%   |
| es_ES | 6        | 6.38%   |
| en_GB | 5        | 5.32%   |
| pt_BR | 3        | 3.19%   |
| es_AR | 3        | 3.19%   |
| en_AU | 3        | 3.19%   |
| C     | 3        | 3.19%   |
| pl_PL | 2        | 2.13%   |
| es_MX | 2        | 2.13%   |
| es_CR | 2        | 2.13%   |
| zh_TW | 1        | 1.06%   |
| tr_TR | 1        | 1.06%   |
| sv_SE | 1        | 1.06%   |
| ru_UA | 1        | 1.06%   |
| nl_BE | 1        | 1.06%   |
| es_PE | 1        | 1.06%   |
| en_AG | 1        | 1.06%   |
| el_GR | 1        | 1.06%   |
| cv_RU | 1        | 1.06%   |
| cs_CZ | 1        | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 65       | 69.89%  |
| EFI  | 28       | 30.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 85       | 89.47%  |
| Tmpfs   | 5        | 5.26%   |
| Overlay | 3        | 3.16%   |
| XXX4    | 1        | 1.05%   |
| Btrfs   | 1        | 1.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 42       | 44.68%  |
| MBR     | 32       | 34.04%  |
| Unknown | 20       | 21.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 80.85%  |
| Yes       | 18       | 19.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 61.29%  |
| Yes       | 36       | 38.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 19.35%  |
| MSI                 | 15       | 16.13%  |
| Dell                | 11       | 11.83%  |
| Gigabyte Technology | 6        | 6.45%   |
| ASRock              | 6        | 6.45%   |
| Hewlett-Packard     | 5        | 5.38%   |
| Unknown             | 5        | 5.38%   |
| Pegatron            | 4        | 4.3%    |
| Acer                | 3        | 3.23%   |
| Positivo            | 2        | 2.15%   |
| Lenovo              | 2        | 2.15%   |
| Intel               | 2        | 2.15%   |
| AMI                 | 2        | 2.15%   |
| ZOTAC               | 1        | 1.08%   |
| YANYU               | 1        | 1.08%   |
| Shuttle             | 1        | 1.08%   |
| Seeed Studio        | 1        | 1.08%   |
| NEC Computers       | 1        | 1.08%   |
| Inventec            | 1        | 1.08%   |
| Fujitsu             | 1        | 1.08%   |
| Foxconn             | 1        | 1.08%   |
| ECS                 | 1        | 1.08%   |
| BANGHO              | 1        | 1.08%   |
| Apple               | 1        | 1.08%   |
| AAEON               | 1        | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 5        | 5.38%   |
| MSI MS-7C37                            | 3        | 3.23%   |
| Dell Dimension 9100                    | 2        | 2.15%   |
| ZOTAC NM10                             | 1        | 1.08%   |
| YANYU ITX-S192                         | 1        | 1.08%   |
| Shuttle XS35V3                         | 1        | 1.08%   |
| Seeed Studio ODYSSEY-X86J4125          | 1        | 1.08%   |
| Positivo POS-AG31AP                    | 1        | 1.08%   |
| Positivo P5VD2-MX                      | 1        | 1.08%   |
| Pegatron NC689AA-ABA s3700y            | 1        | 1.08%   |
| Pegatron h8-1350ef                     | 1        | 1.08%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 1.08%   |
| Pegatron AY748AA-ABA p6320y            | 1        | 1.08%   |
| NEC Computers ECS-945G                 | 1        | 1.08%   |
| MSI MS-7D54                            | 1        | 1.08%   |
| MSI MS-7D09                            | 1        | 1.08%   |
| MSI MS-7C96                            | 1        | 1.08%   |
| MSI MS-7C56                            | 1        | 1.08%   |
| MSI MS-7C51                            | 1        | 1.08%   |
| MSI MS-7B86                            | 1        | 1.08%   |
| MSI MS-7B33                            | 1        | 1.08%   |
| MSI MS-7978                            | 1        | 1.08%   |
| MSI MS-7641                            | 1        | 1.08%   |
| MSI MS-7501                            | 1        | 1.08%   |
| MSI MS-7267                            | 1        | 1.08%   |
| MSI MS-7032                            | 1        | 1.08%   |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 1.08%   |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 1.08%   |
| Inventec DQ Class                      | 1        | 1.08%   |
| Intel X79 V2.72A                       | 1        | 1.08%   |
| Intel BTC-T37                          | 1        | 1.08%   |
| HP Z400 Workstation                    | 1        | 1.08%   |
| HP t620 Quad Core TC                   | 1        | 1.08%   |
| HP Slim Desktop S01-pF1xxx             | 1        | 1.08%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 1.08%   |
| HP Compaq 8000 Elite SFF PC            | 1        | 1.08%   |
| Gigabyte GB-BMCE-5105                  | 1        | 1.08%   |
| Gigabyte G31M-S2C                      | 1        | 1.08%   |
| Gigabyte G31M-ES2C                     | 1        | 1.08%   |
| Gigabyte F2A58M-HD2                    | 1        | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 5        | 5.38%   |
| Unknown                       | 5        | 5.38%   |
| MSI MS-7C37                   | 3        | 3.23%   |
| ASUS ROG                      | 3        | 3.23%   |
| Lenovo ThinkCentre            | 2        | 2.15%   |
| HP Compaq                     | 2        | 2.15%   |
| Dell Vostro                   | 2        | 2.15%   |
| Dell Dimension                | 2        | 2.15%   |
| ASUS PRIME                    | 2        | 2.15%   |
| ZOTAC NM10                    | 1        | 1.08%   |
| YANYU ITX-S192                | 1        | 1.08%   |
| Shuttle XS35V3                | 1        | 1.08%   |
| Seeed Studio ODYSSEY-X86J4125 | 1        | 1.08%   |
| Positivo POS-AG31AP           | 1        | 1.08%   |
| Positivo P5VD2-MX             | 1        | 1.08%   |
| Pegatron NC689AA-ABA          | 1        | 1.08%   |
| Pegatron h8-1350ef            | 1        | 1.08%   |
| Pegatron Compaq               | 1        | 1.08%   |
| Pegatron AY748AA-ABA          | 1        | 1.08%   |
| NEC Computers ECS-945G        | 1        | 1.08%   |
| MSI MS-7D54                   | 1        | 1.08%   |
| MSI MS-7D09                   | 1        | 1.08%   |
| MSI MS-7C96                   | 1        | 1.08%   |
| MSI MS-7C56                   | 1        | 1.08%   |
| MSI MS-7C51                   | 1        | 1.08%   |
| MSI MS-7B86                   | 1        | 1.08%   |
| MSI MS-7B33                   | 1        | 1.08%   |
| MSI MS-7978                   | 1        | 1.08%   |
| MSI MS-7641                   | 1        | 1.08%   |
| MSI MS-7501                   | 1        | 1.08%   |
| MSI MS-7267                   | 1        | 1.08%   |
| MSI MS-7032                   | 1        | 1.08%   |
| Inventec DQ                   | 1        | 1.08%   |
| Intel X79                     | 1        | 1.08%   |
| Intel BTC-T37                 | 1        | 1.08%   |
| HP Z400                       | 1        | 1.08%   |
| HP t620                       | 1        | 1.08%   |
| HP Slim                       | 1        | 1.08%   |
| Gigabyte GB-BMCE-5105         | 1        | 1.08%   |
| Gigabyte G31M-S2C             | 1        | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2008 | 10       | 10.75%  |
| 2019 | 8        | 8.6%    |
| 2010 | 8        | 8.6%    |
| 2009 | 8        | 8.6%    |
| 2020 | 7        | 7.53%   |
| 2017 | 6        | 6.45%   |
| 2021 | 5        | 5.38%   |
| 2018 | 5        | 5.38%   |
| 2013 | 5        | 5.38%   |
| 2012 | 5        | 5.38%   |
| 2011 | 5        | 5.38%   |
| 2007 | 5        | 5.38%   |
| 2015 | 4        | 4.3%    |
| 2014 | 4        | 4.3%    |
| 2022 | 3        | 3.23%   |
| 2016 | 2        | 2.15%   |
| 2006 | 2        | 2.15%   |
| 2001 | 1        | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 93       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 91       | 97.85%  |
| Enabled  | 2        | 2.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 93       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 19       | 20%     |
| 3.01-4.0    | 18       | 18.95%  |
| 16.01-24.0  | 13       | 13.68%  |
| 8.01-16.0   | 13       | 13.68%  |
| 32.01-64.0  | 11       | 11.58%  |
| 1.01-2.0    | 11       | 11.58%  |
| 64.01-256.0 | 4        | 4.21%   |
| 2.01-3.0    | 3        | 3.16%   |
| 0.51-1.0    | 3        | 3.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 43       | 43.43%  |
| 0.51-1.0  | 20       | 20.2%   |
| 2.01-3.0  | 19       | 19.19%  |
| 4.01-8.0  | 10       | 10.1%   |
| 3.01-4.0  | 3        | 3.03%   |
| 8.01-16.0 | 3        | 3.03%   |
| 0.01-0.5  | 1        | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 47       | 50.54%  |
| 2      | 29       | 31.18%  |
| 3      | 8        | 8.6%    |
| 5      | 3        | 3.23%   |
| 4      | 2        | 2.15%   |
| 12     | 1        | 1.08%   |
| 7      | 1        | 1.08%   |
| 6      | 1        | 1.08%   |
| 0      | 1        | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 59.57%  |
| Yes       | 38       | 40.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 92       | 98.92%  |
| No        | 1        | 1.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 56.99%  |
| Yes       | 40       | 43.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 76.84%  |
| Yes       | 22       | 23.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 17       | 18.28%  |
| France     | 14       | 15.05%  |
| Germany    | 9        | 9.68%   |
| Spain      | 7        | 7.53%   |
| Italy      | 6        | 6.45%   |
| Poland     | 5        | 5.38%   |
| UK         | 4        | 4.3%    |
| Brazil     | 4        | 4.3%    |
| Australia  | 3        | 3.23%   |
| Argentina  | 3        | 3.23%   |
| Sweden     | 2        | 2.15%   |
| Costa Rica | 2        | 2.15%   |
| Venezuela  | 1        | 1.08%   |
| Ukraine    | 1        | 1.08%   |
| Turkey     | 1        | 1.08%   |
| Taiwan     | 1        | 1.08%   |
| Romania    | 1        | 1.08%   |
| Peru       | 1        | 1.08%   |
| Pakistan   | 1        | 1.08%   |
| Mexico     | 1        | 1.08%   |
| Luxembourg | 1        | 1.08%   |
| Latvia     | 1        | 1.08%   |
| Ireland    | 1        | 1.08%   |
| Iran       | 1        | 1.08%   |
| Indonesia  | 1        | 1.08%   |
| Greece     | 1        | 1.08%   |
| Czechia    | 1        | 1.08%   |
| Bulgaria   | 1        | 1.08%   |
| Belgium    | 1        | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 3        | 3.03%   |
| Melbourne            | 2        | 2.02%   |
| Largo                | 2        | 2.02%   |
| Karlstad             | 2        | 2.02%   |
| Heredia              | 2        | 2.02%   |
| Woking               | 1        | 1.01%   |
| Wetteren             | 1        | 1.01%   |
| Washington           | 1        | 1.01%   |
| Warsaw               | 1        | 1.01%   |
| Versailles           | 1        | 1.01%   |
| Varna                | 1        | 1.01%   |
| Valentigney          | 1        | 1.01%   |
| Valencia             | 1        | 1.01%   |
| Tychy                | 1        | 1.01%   |
| Turin                | 1        | 1.01%   |
| Torrejón de Ardoz   | 1        | 1.01%   |
| Tehran               | 1        | 1.01%   |
| Tandil               | 1        | 1.01%   |
| Taipei               | 1        | 1.01%   |
| St Louis             | 1        | 1.01%   |
| Sonico               | 1        | 1.01%   |
| Sarcelles            | 1        | 1.01%   |
| Sao Paulo            | 1        | 1.01%   |
| Saltsjoe-Boo         | 1        | 1.01%   |
| Riverenert           | 1        | 1.01%   |
| Rio Segundo          | 1        | 1.01%   |
| Richmond             | 1        | 1.01%   |
| Resistencia          | 1        | 1.01%   |
| Prague               | 1        | 1.01%   |
| Port Washington      | 1        | 1.01%   |
| Perth                | 1        | 1.01%   |
| Palencia             | 1        | 1.01%   |
| Ostrów Wielkopolski | 1        | 1.01%   |
| Oberkotzau           | 1        | 1.01%   |
| Novo Gama            | 1        | 1.01%   |
| Notting Hill Gate    | 1        | 1.01%   |
| Nederland            | 1        | 1.01%   |
| Mostoles             | 1        | 1.01%   |
| Monheim am Rhein     | 1        | 1.01%   |
| Mogi Guacu           | 1        | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 28       | 40     | 19.05%  |
| Samsung Electronics         | 23       | 32     | 15.65%  |
| WDC                         | 21       | 35     | 14.29%  |
| Kingston                    | 11       | 13     | 7.48%   |
| Hitachi                     | 11       | 15     | 7.48%   |
| SanDisk                     | 6        | 6      | 4.08%   |
| Crucial                     | 5        | 5      | 3.4%    |
| Unknown                     | 3        | 3      | 2.04%   |
| Toshiba                     | 3        | 3      | 2.04%   |
| A-DATA Technology           | 3        | 3      | 2.04%   |
| PNY                         | 2        | 2      | 1.36%   |
| Maxtor                      | 2        | 2      | 1.36%   |
| HGST                        | 2        | 2      | 1.36%   |
| GOODRAM                     | 2        | 2      | 1.36%   |
| China                       | 2        | 2      | 1.36%   |
| Apple                       | 2        | 2      | 1.36%   |
| Apacer                      | 2        | 2      | 1.36%   |
| WD MediaMax                 | 1        | 1      | 0.68%   |
| Transcend                   | 1        | 2      | 0.68%   |
| TO Exter                    | 1        | 1      | 0.68%   |
| Team                        | 1        | 1      | 0.68%   |
| T-FORCE                     | 1        | 1      | 0.68%   |
| RSH-319                     | 1        | 1      | 0.68%   |
| Patriot                     | 1        | 1      | 0.68%   |
| Micron/Crucial Technology   | 1        | 2      | 0.68%   |
| LITEONIT                    | 1        | 1      | 0.68%   |
| Kston                       | 1        | 3      | 0.68%   |
| Kingston Technology Company | 1        | 1      | 0.68%   |
| Intel                       | 1        | 1      | 0.68%   |
| HGST HUS                    | 1        | 2      | 0.68%   |
| Gigabyte Technology         | 1        | 1      | 0.68%   |
| External                    | 1        | 1      | 0.68%   |
| Emtec                       | 1        | 1      | 0.68%   |
| BR                          | 1        | 1      | 0.68%   |
| Apricorn                    | 1        | 1      | 0.68%   |
| AMD                         | 1        | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 6        | 3.55%   |
| Kingston SA400S37240G 240GB SSD    | 5        | 2.96%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.18%   |
| Seagate ST3120213AS 120GB          | 2        | 1.18%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 1.18%   |
| SanDisk DF4032  32GB               | 2        | 1.18%   |
| Samsung SSD 870 EVO 500GB          | 2        | 1.18%   |
| Samsung HD502HJ 500GB              | 2        | 1.18%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.18%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 1        | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.59%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.59%   |
| WDC WD800BB-00CAA1 80GB            | 1        | 0.59%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 0.59%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1        | 0.59%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.59%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 0.59%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.59%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.59%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 1        | 0.59%   |
| WDC WD3200BPVT-00HXZT3 320GB       | 1        | 0.59%   |
| WDC WD3200AAKS-75L9A0 320GB        | 1        | 0.59%   |
| WDC WD3200AAJS-65M0A0 320GB        | 1        | 0.59%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 0.59%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.59%   |
| WDC WD3200AACS-00M6B0 320GB        | 1        | 0.59%   |
| WDC WD30EZRZ-00GXCB0 3TB           | 1        | 0.59%   |
| WDC WD2500KS-00MJB0 250GB          | 1        | 0.59%   |
| WDC WD2500AAJS-07M0A0 250GB        | 1        | 0.59%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.59%   |
| WDC WD20EZBX-00AYRA0 2TB           | 1        | 0.59%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 1        | 0.59%   |
| WDC WD2003FYYS-02W0B0 2TB          | 1        | 0.59%   |
| WDC WD10SPZX-08Z10 1TB             | 1        | 0.59%   |
| WDC WD10S21X-24R1BT0-SSHD-8GB      | 1        | 0.59%   |
| WDC WD10EZRZ-00Z5HB0 1TB           | 1        | 0.59%   |
| WDC WD10EZEX-60WN4A1 1TB           | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 28       | 39     | 37.33%  |
| WDC                 | 18       | 29     | 24%     |
| Hitachi             | 11       | 15     | 14.67%  |
| Samsung Electronics | 6        | 7      | 8%      |
| Toshiba             | 3        | 3      | 4%      |
| Maxtor              | 2        | 2      | 2.67%   |
| HGST                | 2        | 2      | 2.67%   |
| WD MediaMax         | 1        | 1      | 1.33%   |
| RSH-319             | 1        | 1      | 1.33%   |
| External            | 1        | 1      | 1.33%   |
| Apricorn            | 1        | 1      | 1.33%   |
| Apple               | 1        | 1      | 1.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 17     | 21.57%  |
| Kingston            | 10       | 12     | 19.61%  |
| SanDisk             | 4        | 4      | 7.84%   |
| WDC                 | 3        | 3      | 5.88%   |
| PNY                 | 2        | 2      | 3.92%   |
| GOODRAM             | 2        | 2      | 3.92%   |
| Crucial             | 2        | 2      | 3.92%   |
| China               | 2        | 2      | 3.92%   |
| Apacer              | 2        | 2      | 3.92%   |
| A-DATA Technology   | 2        | 2      | 3.92%   |
| Transcend           | 1        | 2      | 1.96%   |
| TO Exter            | 1        | 1      | 1.96%   |
| Team                | 1        | 1      | 1.96%   |
| Patriot             | 1        | 1      | 1.96%   |
| LITEONIT            | 1        | 1      | 1.96%   |
| Kston               | 1        | 3      | 1.96%   |
| Intel               | 1        | 1      | 1.96%   |
| Gigabyte Technology | 1        | 1      | 1.96%   |
| Emtec               | 1        | 1      | 1.96%   |
| BR                  | 1        | 1      | 1.96%   |
| Apple               | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 56       | 102    | 44.8%   |
| SSD     | 47       | 62     | 37.6%   |
| NVMe    | 15       | 20     | 12%     |
| MMC     | 6        | 6      | 4.8%    |
| Unknown | 1        | 3      | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 84       | 160    | 77.06%  |
| NVMe | 15       | 20     | 13.76%  |
| MMC  | 6        | 6      | 5.5%    |
| SAS  | 4        | 7      | 3.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 71       | 103    | 63.39%  |
| 0.51-1.0   | 19       | 26     | 16.96%  |
| 1.01-2.0   | 13       | 20     | 11.61%  |
| 2.01-3.0   | 4        | 5      | 3.57%   |
| 4.01-10.0  | 3        | 6      | 2.68%   |
| 3.01-4.0   | 2        | 4      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 27.37%  |
| 251-500        | 16       | 16.84%  |
| 21-50          | 11       | 11.58%  |
| 1001-2000      | 10       | 10.53%  |
| More than 3000 | 7        | 7.37%   |
| 501-1000       | 7        | 7.37%   |
| 51-100         | 7        | 7.37%   |
| 1-20           | 6        | 6.32%   |
| 2001-3000      | 5        | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 43       | 43.88%  |
| 21-50          | 16       | 16.33%  |
| 101-250        | 11       | 11.22%  |
| 51-100         | 9        | 9.18%   |
| 501-1000       | 6        | 6.12%   |
| More than 3000 | 4        | 4.08%   |
| 1001-2000      | 4        | 4.08%   |
| 251-500        | 3        | 3.06%   |
| 2001-3000      | 2        | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB            | 1        | 2      | 5.88%   |
| WDC WD3200AACS-00M6B0 320GB         | 1        | 1      | 5.88%   |
| WDC WD2003FYYS-02W0B0 2TB           | 1        | 1      | 5.88%   |
| WDC WD10SPZX-08Z10 1TB              | 1        | 1      | 5.88%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 1      | 5.88%   |
| WDC WD10EACS-00D6B1 1TB             | 1        | 1      | 5.88%   |
| Toshiba MK6465GSX 640GB             | 1        | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 5.88%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 2      | 5.88%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 5.88%   |
| Maxtor 6L200M0 208GB                | 1        | 1      | 5.88%   |
| Hitachi HTS543216L9A300 160GB       | 1        | 1      | 5.88%   |
| Hitachi HTE545050B9A300 500GB       | 1        | 1      | 5.88%   |
| Apple HDD HTS547550A9E384 500GB     | 1        | 1      | 5.88%   |
| Apacer 16GB SATA Flash Drive SSD    | 1        | 1      | 5.88%   |
| A-DATA Technology SP920SS 256GB SSD | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 26.67%  |
| Seagate             | 3        | 4      | 20%     |
| Hitachi             | 2        | 2      | 13.33%  |
| Toshiba             | 1        | 1      | 6.67%   |
| Samsung Electronics | 1        | 1      | 6.67%   |
| Maxtor              | 1        | 1      | 6.67%   |
| Apple               | 1        | 1      | 6.67%   |
| Apacer              | 1        | 1      | 6.67%   |
| A-DATA Technology   | 1        | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 7      | 30.77%  |
| Seagate             | 3        | 4      | 23.08%  |
| Hitachi             | 2        | 2      | 15.38%  |
| Toshiba             | 1        | 1      | 7.69%   |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Maxtor              | 1        | 1      | 7.69%   |
| Apple               | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 17     | 85.71%  |
| SSD  | 2        | 2      | 14.29%  |

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
| Works    | 46       | 82     | 43.81%  |
| Detected | 42       | 89     | 40%     |
| Malfunc  | 14       | 19     | 13.33%  |
| Failed   | 3        | 3      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 53       | 43.8%   |
| AMD                         | 30       | 24.79%  |
| Samsung Electronics         | 7        | 5.79%   |
| ASMedia Technology          | 6        | 4.96%   |
| Nvidia                      | 4        | 3.31%   |
| Micron/Crucial Technology   | 4        | 3.31%   |
| JMicron Technology          | 4        | 3.31%   |
| SanDisk                     | 3        | 2.48%   |
| VIA Technologies            | 2        | 1.65%   |
| Marvell Technology Group    | 2        | 1.65%   |
| Kingston Technology Company | 2        | 1.65%   |
| Seagate Technology          | 1        | 0.83%   |
| LSI Logic / Symbios Logic   | 1        | 0.83%   |
| Apple                       | 1        | 0.83%   |
| ADATA Technology            | 1        | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18       | 10.78%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13       | 7.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 12       | 7.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6        | 3.59%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5        | 2.99%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 2.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 1.8%    |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3        | 1.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 1.8%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 1.2%    |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.2%    |
| Nvidia MCP61 IDE                                                               | 2        | 1.2%    |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2        | 1.2%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.2%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2        | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.2%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.2%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 1.2%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.2%    |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.2%    |
| AMD FCH IDE Controller                                                         | 2        | 1.2%    |
| VIA VIA VT6420 SATA RAID Controller                                            | 1        | 0.6%    |
| VIA Serial ATA Controller                                                      | 1        | 0.6%    |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.6%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.6%    |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 61       | 50.83%  |
| IDE  | 38       | 31.67%  |
| NVMe | 15       | 12.5%   |
| RAID | 5        | 4.17%   |
| SAS  | 1        | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 62.37%  |
| AMD    | 35       | 37.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 3.23%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3        | 3.23%   |
| Intel Atom CPU D525 @ 1.80GHz                   | 3        | 3.23%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz          | 2        | 2.15%   |
| Intel Pentium D CPU 2.80GHz                     | 2        | 2.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 2.15%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2        | 2.15%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2        | 2.15%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 2.15%   |
| AMD GX-415GA SOC with Radeon HD Graphics        | 2        | 2.15%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 2        | 2.15%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 2.15%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 1.08%   |
| Intel Xeon CPU E5520 @ 2.27GHz                  | 1        | 1.08%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz             | 1        | 1.08%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz             | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 1.08%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 1.08%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 1.08%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 1.08%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.08%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 1.08%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.08%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 1.08%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.08%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.08%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 1        | 1.08%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 1.08%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.08%   |
| Intel Core i3-10105 CPU @ 3.70GHz               | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 1        | 1.08%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.08%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz            | 1        | 1.08%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz            | 1        | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 10       | 10.75%  |
| Intel Core i5           | 9        | 9.68%   |
| Intel Atom              | 9        | 9.68%   |
| Intel Core 2 Duo        | 6        | 6.45%   |
| AMD Ryzen 7             | 6        | 6.45%   |
| AMD Ryzen 5             | 6        | 6.45%   |
| Intel Xeon              | 4        | 4.3%    |
| Intel Core i3           | 4        | 4.3%    |
| Intel Core 2 Quad       | 4        | 4.3%    |
| Intel Pentium Dual-Core | 3        | 3.23%   |
| Intel Pentium Dual      | 3        | 3.23%   |
| Intel Core i7           | 3        | 3.23%   |
| AMD Ryzen 9             | 3        | 3.23%   |
| AMD FX                  | 3        | 3.23%   |
| AMD Athlon 64 X2        | 3        | 3.23%   |
| Intel Pentium D         | 2        | 2.15%   |
| AMD Phenom II X4        | 2        | 2.15%   |
| AMD GX                  | 2        | 2.15%   |
| AMD A10                 | 2        | 2.15%   |
| Other                   | 1        | 1.08%   |
| Intel Core i9           | 1        | 1.08%   |
| AMD Ryzen 5 PRO         | 1        | 1.08%   |
| AMD Phenom II X6        | 1        | 1.08%   |
| AMD G                   | 1        | 1.08%   |
| AMD Athlon II X3        | 1        | 1.08%   |
| AMD Athlon II X2        | 1        | 1.08%   |
| AMD A8                  | 1        | 1.08%   |
| AMD A4                  | 1        | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 33       | 35.48%  |
| 4      | 32       | 34.41%  |
| 6      | 10       | 10.75%  |
| 8      | 8        | 8.6%    |
| 1      | 4        | 4.3%    |
| 3      | 3        | 3.23%   |
| 16     | 1        | 1.08%   |
| 12     | 1        | 1.08%   |
| 10     | 1        | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 92       | 98.92%  |
| 2      | 1        | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 58       | 62.37%  |
| 2      | 35       | 37.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 93       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 45.83%  |
| 0x1067a    | 5        | 5.21%   |
| 0x406c4    | 4        | 4.17%   |
| 0x906ea    | 3        | 3.13%   |
| 0x106ca    | 3        | 3.13%   |
| 0x6fb      | 2        | 2.08%   |
| 0x306c3    | 2        | 2.08%   |
| 0x206a7    | 2        | 2.08%   |
| 0x0a201009 | 2        | 2.08%   |
| 0x0700010f | 2        | 2.08%   |
| 0x06003106 | 2        | 2.08%   |
| 0x010000db | 2        | 2.08%   |
| 0xa0653    | 1        | 1.04%   |
| 0x906c0    | 1        | 1.04%   |
| 0x706a8    | 1        | 1.04%   |
| 0x706a1    | 1        | 1.04%   |
| 0x6fd      | 1        | 1.04%   |
| 0x506e3    | 1        | 1.04%   |
| 0x506c9    | 1        | 1.04%   |
| 0x306e4    | 1        | 1.04%   |
| 0x306a9    | 1        | 1.04%   |
| 0x30679    | 1        | 1.04%   |
| 0x106a5    | 1        | 1.04%   |
| 0x10676    | 1        | 1.04%   |
| 0x10661    | 1        | 1.04%   |
| 0x0a601203 | 1        | 1.04%   |
| 0x0a50000d | 1        | 1.04%   |
| 0x0a50000c | 1        | 1.04%   |
| 0x0a50000b | 1        | 1.04%   |
| 0x08701021 | 1        | 1.04%   |
| 0x08701013 | 1        | 1.04%   |
| 0x08001138 | 1        | 1.04%   |
| 0x06001119 | 1        | 1.04%   |
| 0x06000852 | 1        | 1.04%   |
| 0x010000c7 | 1        | 1.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 11       | 11.83%  |
| Zen 3         | 7        | 7.53%   |
| Core          | 7        | 7.53%   |
| Silvermont    | 6        | 6.45%   |
| K10           | 5        | 5.38%   |
| IvyBridge     | 5        | 5.38%   |
| Bonnell       | 5        | 5.38%   |
| K8 Hammer     | 4        | 4.3%    |
| Haswell       | 4        | 4.3%    |
| Zen+          | 3        | 3.23%   |
| Zen 2         | 3        | 3.23%   |
| SandyBridge   | 3        | 3.23%   |
| Piledriver    | 3        | 3.23%   |
| Nehalem       | 3        | 3.23%   |
| KabyLake      | 3        | 3.23%   |
| Goldmont plus | 3        | 3.23%   |
| Zen           | 2        | 2.15%   |
| Steamroller   | 2        | 2.15%   |
| Skylake       | 2        | 2.15%   |
| NetBurst      | 2        | 2.15%   |
| Jaguar        | 2        | 2.15%   |
| CometLake     | 2        | 2.15%   |
| Tremont       | 1        | 1.08%   |
| K10 Llano     | 1        | 1.08%   |
| Goldmont      | 1        | 1.08%   |
| Bulldozer     | 1        | 1.08%   |
| Bobcat        | 1        | 1.08%   |
| Unknown       | 1        | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 34       | 34.69%  |
| Nvidia | 33       | 33.67%  |
| Intel  | 31       | 31.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 4.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 4.85%   |
| Nvidia GT218 [ION]                                                                       | 3        | 2.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 2.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 2.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 2.91%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 2.91%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 2.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 1.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.94%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.94%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 1.94%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 1.94%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2        | 1.94%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 1.94%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 1.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.94%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 0.97%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.97%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.97%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1        | 0.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.97%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 0.97%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 0.97%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 0.97%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 0.97%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 0.97%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 0.97%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.97%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 0.97%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 0.97%   |
| Nvidia GA104GL [RTX A4000]                                                               | 1        | 0.97%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 0.97%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 0.97%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 0.97%   |
| Nvidia G96 [GeForce GT 120 Mac Edition]                                                  | 1        | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 30       | 32.26%  |
| 1 x Intel          | 28       | 30.11%  |
| 1 x AMD            | 28       | 30.11%  |
| 2 x AMD            | 3        | 3.23%   |
| AMD + Nvidia       | 2        | 2.15%   |
| Intel + 2 x Nvidia | 1        | 1.08%   |
| Intel + 2 x AMD    | 1        | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 76       | 81.72%  |
| Proprietary | 12       | 12.9%   |
| Unknown     | 5        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 62.77%  |
| 0.01-0.5   | 11       | 11.7%   |
| 0.51-1.0   | 9        | 9.57%   |
| 7.01-8.0   | 5        | 5.32%   |
| 8.01-16.0  | 4        | 4.26%   |
| 1.01-2.0   | 3        | 3.19%   |
| 3.01-4.0   | 2        | 2.13%   |
| 2.01-3.0   | 1        | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 14.29%  |
| Dell                 | 10       | 11.9%   |
| Hewlett-Packard      | 8        | 9.52%   |
| Philips              | 6        | 7.14%   |
| Goldstar             | 6        | 7.14%   |
| Acer                 | 5        | 5.95%   |
| Ancor Communications | 4        | 4.76%   |
| Iiyama               | 3        | 3.57%   |
| Eizo                 | 3        | 3.57%   |
| Sony                 | 2        | 2.38%   |
| HannStar             | 2        | 2.38%   |
| BenQ                 | 2        | 2.38%   |
| Westinghouse         | 1        | 1.19%   |
| Vizio                | 1        | 1.19%   |
| ViewSonic            | 1        | 1.19%   |
| VHT                  | 1        | 1.19%   |
| Unknown (ADA)        | 1        | 1.19%   |
| Unknown              | 1        | 1.19%   |
| SNC                  | 1        | 1.19%   |
| Sharp                | 1        | 1.19%   |
| SFX                  | 1        | 1.19%   |
| Sampo                | 1        | 1.19%   |
| RTK                  | 1        | 1.19%   |
| Positivo             | 1        | 1.19%   |
| Pixio                | 1        | 1.19%   |
| NEC Computers        | 1        | 1.19%   |
| MSI                  | 1        | 1.19%   |
| LG Electronics       | 1        | 1.19%   |
| Jean                 | 1        | 1.19%   |
| Daewoo               | 1        | 1.19%   |
| Compal               | 1        | 1.19%   |
| Belinea              | 1        | 1.19%   |
| AOC                  | 1        | 1.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 2.3%    |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1        | 1.15%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1        | 1.15%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 1.15%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 1.15%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 1.15%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1        | 1.15%   |
| Sony TV SNY9C01 1360x768                                             | 1        | 1.15%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1        | 1.15%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 1.15%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 1.15%   |
| SFX 4K EXTENDER SFX0100 3840x2160 1872x1053mm 84.6-inch              | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 1.15%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.15%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 1.15%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 1.15%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 1.15%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 1.15%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 1.15%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch    | 1        | 1.15%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 1.15%   |
| RTK ARZOPA RTKBC33 1920x1080 309x174mm 14.0-inch                     | 1        | 1.15%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 1.15%   |
| Pixio DP ICB3500 3440x1440 708x399mm 32.0-inch                       | 1        | 1.15%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 1.15%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 1.15%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1        | 1.15%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1        | 1.15%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.15%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                   | 1        | 1.15%   |
| NEC Computers EA224WMi NEC68C1 1920x1080 476x268mm 21.5-inch         | 1        | 1.15%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                  | 1        | 1.15%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.15%   |
| Jean JT178x4 JEN0DB2 1280x1024 338x270mm 17.0-inch                   | 1        | 1.15%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                 | 1        | 1.15%   |
| Iiyama PL2791Q IVM6646 2560x1440 597x336mm 27.0-inch                 | 1        | 1.15%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                 | 1        | 1.15%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                 | 1        | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 33       | 39.29%  |
| 1280x1024 (SXGA)   | 10       | 11.9%   |
| 1680x1050 (WSXGA+) | 7        | 8.33%   |
| 1366x768 (WXGA)    | 7        | 8.33%   |
| 1600x900 (HD+)     | 5        | 5.95%   |
| 2560x1440 (QHD)    | 4        | 4.76%   |
| 1440x900 (WXGA+)   | 4        | 4.76%   |
| 3840x2160 (4K)     | 3        | 3.57%   |
| 1360x768           | 3        | 3.57%   |
| 800x600            | 1        | 1.19%   |
| 3440x1440          | 1        | 1.19%   |
| 2560x1600          | 1        | 1.19%   |
| 1920x1200 (WUXGA)  | 1        | 1.19%   |
| 1280x800 (WXGA)    | 1        | 1.19%   |
| 1280x768           | 1        | 1.19%   |
| 1280x720 (HD)      | 1        | 1.19%   |
| 1024x768 (XGA)     | 1        | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 12.2%   |
| 24      | 10       | 12.2%   |
| 18      | 9        | 10.98%  |
| 19      | 8        | 9.76%   |
| 23      | 7        | 8.54%   |
| 22      | 7        | 8.54%   |
| 21      | 6        | 7.32%   |
| Unknown | 6        | 7.32%   |
| 20      | 4        | 4.88%   |
| 17      | 3        | 3.66%   |
| 15      | 2        | 2.44%   |
| 84      | 1        | 1.22%   |
| 72      | 1        | 1.22%   |
| 49      | 1        | 1.22%   |
| 47      | 1        | 1.22%   |
| 43      | 1        | 1.22%   |
| 34      | 1        | 1.22%   |
| 32      | 1        | 1.22%   |
| 14      | 1        | 1.22%   |
| 8       | 1        | 1.22%   |
| 7       | 1        | 1.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 29       | 35.37%  |
| 501-600     | 27       | 32.93%  |
| 301-350     | 6        | 7.32%   |
| Unknown     | 6        | 7.32%   |
| 351-400     | 5        | 6.1%    |
| 701-800     | 2        | 2.44%   |
| 1501-2000   | 2        | 2.44%   |
| 101-200     | 2        | 2.44%   |
| 1001-1500   | 2        | 2.44%   |
| 901-1000    | 1        | 1.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 50       | 63.29%  |
| 16/10   | 12       | 15.19%  |
| 5/4     | 8        | 10.13%  |
| Unknown | 5        | 6.33%   |
| 4/3     | 3        | 3.8%    |
| 3/2     | 1        | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 28.4%   |
| 151-200        | 17       | 20.99%  |
| 301-350        | 10       | 12.35%  |
| 141-150        | 10       | 12.35%  |
| Unknown        | 6        | 7.41%   |
| More than 1000 | 3        | 3.7%    |
| 251-300        | 3        | 3.7%    |
| 501-1000       | 3        | 3.7%    |
| 1-40           | 2        | 2.47%   |
| 81-90          | 1        | 1.23%   |
| 351-500        | 1        | 1.23%   |
| 111-120        | 1        | 1.23%   |
| 101-110        | 1        | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 53       | 66.25%  |
| 101-120 | 14       | 17.5%   |
| Unknown | 6        | 7.5%    |
| 1-50    | 5        | 6.25%   |
| 161-240 | 2        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 79       | 84.04%  |
| 2     | 10       | 10.64%  |
| 0     | 5        | 5.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 59       | 43.38%  |
| Intel                           | 30       | 22.06%  |
| Qualcomm Atheros                | 10       | 7.35%   |
| TP-Link                         | 6        | 4.41%   |
| Broadcom                        | 5        | 3.68%   |
| Nvidia                          | 3        | 2.21%   |
| NetGear                         | 3        | 2.21%   |
| MediaTek                        | 3        | 2.21%   |
| VIA Technologies                | 2        | 1.47%   |
| Samsung Electronics             | 2        | 1.47%   |
| Qualcomm Atheros Communications | 2        | 1.47%   |
| Xiaomi                          | 1        | 0.74%   |
| Trident Microsystems            | 1        | 0.74%   |
| Texas Instruments               | 1        | 0.74%   |
| Seeed Technology                | 1        | 0.74%   |
| Ralink Technology               | 1        | 0.74%   |
| Ralink                          | 1        | 0.74%   |
| Marvell Technology Group        | 1        | 0.74%   |
| ICS Advent                      | 1        | 0.74%   |
| Broadcom Limited                | 1        | 0.74%   |
| ASUSTek Computer                | 1        | 0.74%   |
| Accton Technology               | 1        | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 51       | 34.69%  |
| Intel Ethernet Controller I225-V                                    | 5        | 3.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 4        | 2.72%   |
| Intel I211 Gigabit Network Connection                               | 3        | 2.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 2        | 1.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 1.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.36%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 1.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.36%   |
| Nvidia MCP77 Ethernet                                               | 2        | 1.36%   |
| NetGear A6210                                                       | 2        | 1.36%   |
| Intel Wi-Fi 6 AX200                                                 | 2        | 1.36%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 1.36%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.36%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 1.36%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 1.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 1        | 0.68%   |
| Trident Microsystems 4DWave DX                                      | 1        | 0.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]     | 1        | 0.68%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 0.68%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.68%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.68%   |
| Texas Instruments CC2531 ZigBee                                     | 1        | 0.68%   |
| Seeed Seeeduino_Cortex_M0+                                          | 1        | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.68%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.68%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                   | 1        | 0.68%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.68%   |
| Realtek 802.11ac NIC                                                | 1        | 0.68%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 23.26%  |
| Intel                           | 10       | 23.26%  |
| TP-Link                         | 5        | 11.63%  |
| Qualcomm Atheros                | 4        | 9.3%    |
| MediaTek                        | 3        | 6.98%   |
| Broadcom                        | 3        | 6.98%   |
| Qualcomm Atheros Communications | 2        | 4.65%   |
| NetGear                         | 2        | 4.65%   |
| Ralink Technology               | 1        | 2.33%   |
| Ralink                          | 1        | 2.33%   |
| Broadcom Limited                | 1        | 2.33%   |
| ASUSTek Computer                | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 4.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 4.65%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 4.65%   |
| NetGear A6210                                                       | 2        | 4.65%   |
| Intel Wi-Fi 6 AX200                                                 | 2        | 4.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 4.65%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 4.65%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 2.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 2.33%   |
| TP-Link 802.11ac NIC                                                | 1        | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 2.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 2.33%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 2.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 2.33%   |
| Realtek 802.11ac NIC                                                | 1        | 2.33%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 2.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 2.33%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 2.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 1        | 2.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 2.33%   |
| Intel Wireless 7265                                                 | 1        | 2.33%   |
| Intel Wireless 3165                                                 | 1        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 2.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 2.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                     | 1        | 2.33%   |
| Intel Centrino Advanced-N 6235                                      | 1        | 2.33%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 2.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 1        | 2.33%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]      | 1        | 2.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 56       | 55.45%  |
| Intel                    | 22       | 21.78%  |
| Qualcomm Atheros         | 7        | 6.93%   |
| Nvidia                   | 3        | 2.97%   |
| VIA Technologies         | 2        | 1.98%   |
| Samsung Electronics      | 2        | 1.98%   |
| Broadcom                 | 2        | 1.98%   |
| Xiaomi                   | 1        | 0.99%   |
| Trident Microsystems     | 1        | 0.99%   |
| TP-Link                  | 1        | 0.99%   |
| NetGear                  | 1        | 0.99%   |
| Marvell Technology Group | 1        | 0.99%   |
| ICS Advent               | 1        | 0.99%   |
| Accton Technology        | 1        | 0.99%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51       | 50%     |
| Intel Ethernet Controller I225-V                                  | 5        | 4.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.92%   |
| Intel I211 Gigabit Network Connection                             | 3        | 2.94%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.96%   |
| Nvidia MCP77 Ethernet                                             | 2        | 1.96%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.98%   |
| Trident Microsystems 4DWave DX                                    | 1        | 0.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.98%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.98%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.98%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.98%   |
| NetGear LB1120-100NAS                                             | 1        | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.98%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.98%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.98%   |
| Intel 82567V-3 Gigabit Network Connection                         | 1        | 0.98%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 0.98%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.98%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 0.98%   |
| Accton SMC2-1211TX                                                | 1        | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 92       | 68.66%  |
| WiFi     | 40       | 29.85%  |
| Modem    | 2        | 1.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 72.92%  |
| WiFi     | 26       | 27.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 62       | 66.67%  |
| 2     | 26       | 27.96%  |
| 3     | 3        | 3.23%   |
| 4     | 1        | 1.08%   |
| 0     | 1        | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 69       | 74.19%  |
| Yes  | 24       | 25.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 9        | 40.91%  |
| Cambridge Silicon Radio         | 4        | 18.18%  |
| MediaTek                        | 2        | 9.09%   |
| Foxconn / Hon Hai               | 2        | 9.09%   |
| TP-Link                         | 1        | 4.55%   |
| Realtek Semiconductor           | 1        | 4.55%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| Logitech                        | 1        | 4.55%   |
| Broadcom                        | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 18.18%  |
| MediaTek Wireless_Device                            | 2        | 9.09%   |
| Intel Bluetooth wireless interface                  | 2        | 9.09%   |
| Intel Bluetooth Device                              | 2        | 9.09%   |
| Intel AX200 Bluetooth                               | 2        | 9.09%   |
| TP-Link UB5A Adapter                                | 1        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 4.55%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 4.55%   |
| Intel AX210 Bluetooth                               | 1        | 4.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 4.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 51       | 37.5%   |
| AMD                                          | 39       | 28.68%  |
| Nvidia                                       | 27       | 19.85%  |
| C-Media Electronics                          | 4        | 2.94%   |
| VIA Technologies                             | 3        | 2.21%   |
| ASUSTek Computer                             | 2        | 1.47%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.74%   |
| Texas Instruments                            | 1        | 0.74%   |
| Sony                                         | 1        | 0.74%   |
| Razer USA                                    | 1        | 0.74%   |
| Plantronics                                  | 1        | 0.74%   |
| Micro Star International                     | 1        | 0.74%   |
| GN Netcom                                    | 1        | 0.74%   |
| Focusrite-Novation                           | 1        | 0.74%   |
| Ensoniq                                      | 1        | 0.74%   |
| Creative Labs                                | 1        | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16       | 10.06%  |
| Nvidia High Definition Audio Controller                                           | 7        | 4.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 4.4%    |
| AMD Starship/Matisse HD Audio Controller                                          | 6        | 3.77%   |
| AMD FCH Azalia Controller                                                         | 6        | 3.77%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 3.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 2.52%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 2.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 2.52%   |
| Nvidia GA104 High Definition Audio Controller                                     | 3        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 1.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 1.89%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 3        | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 1.89%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.89%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.26%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1.26%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.26%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 1.26%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.26%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 1.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 1.26%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 1.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.26%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                          | 2        | 1.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.26%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1        | 0.63%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.63%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1        | 0.63%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 1        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 20%     |
| Micron Technology   | 8        | 12.31%  |
| SK hynix            | 7        | 10.77%  |
| Kingston            | 6        | 9.23%   |
| Corsair             | 6        | 9.23%   |
| Samsung Electronics | 5        | 7.69%   |
| G.Skill             | 5        | 7.69%   |
| Unknown             | 4        | 6.15%   |
| Crucial             | 3        | 4.62%   |
| Unknown (ABCD)      | 2        | 3.08%   |
| Patriot             | 2        | 3.08%   |
| Nanya Technology    | 1        | 1.54%   |
| GOODRAM             | 1        | 1.54%   |
| Elpida              | 1        | 1.54%   |
| A-DATA Technology   | 1        | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 4        | 5.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2        | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 2        | 2.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 2.78%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 2        | 2.78%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                     | 1        | 1.39%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 1.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 1.39%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                       | 1        | 1.39%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 1        | 1.39%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.39%   |
| Unknown RAM Module 2GB DIMM                                    | 1        | 1.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 1.39%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s       | 1        | 1.39%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                     | 1        | 1.39%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                     | 1        | 1.39%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 1        | 1.39%   |
| SK hynix RAM HMT451S6BFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 1.39%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 1        | 1.39%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.39%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.39%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 1        | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                | 1        | 1.39%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.39%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 1.39%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s            | 1        | 1.39%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s                | 1        | 1.39%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s                  | 1        | 1.39%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s             | 1        | 1.39%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                       | 1        | 1.39%   |
| Micron RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s         | 1        | 1.39%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1        | 1.39%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s            | 1        | 1.39%   |
| Micron RAM 8HTF12864AY-800G1 1GB DIMM DDR2 800MT/s             | 1        | 1.39%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s             | 1        | 1.39%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s           | 1        | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 20       | 33.33%  |
| DDR3    | 20       | 33.33%  |
| DDR2    | 9        | 15%     |
| SDRAM   | 4        | 6.67%   |
| Unknown | 4        | 6.67%   |
| LPDDR4  | 2        | 3.33%   |
| DDR5    | 1        | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 49       | 83.05%  |
| SODIMM | 10       | 16.95%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 18       | 27.69%  |
| 8192  | 17       | 26.15%  |
| 4096  | 16       | 24.62%  |
| 16384 | 9        | 13.85%  |
| 32768 | 3        | 4.62%   |
| 1024  | 2        | 3.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 22.58%  |
| 3200    | 7        | 11.29%  |
| 1333    | 6        | 9.68%   |
| 800     | 4        | 6.45%   |
| 2400    | 3        | 4.84%   |
| 667     | 3        | 4.84%   |
| Unknown | 3        | 4.84%   |
| 3400    | 2        | 3.23%   |
| 2800    | 2        | 3.23%   |
| 2667    | 2        | 3.23%   |
| 2133    | 2        | 3.23%   |
| 1866    | 2        | 3.23%   |
| 1066    | 2        | 3.23%   |
| 4800    | 1        | 1.61%   |
| 3933    | 1        | 1.61%   |
| 3666    | 1        | 1.61%   |
| 3600    | 1        | 1.61%   |
| 3534    | 1        | 1.61%   |
| 3066    | 1        | 1.61%   |
| 2666    | 1        | 1.61%   |
| 2048    | 1        | 1.61%   |
| 533     | 1        | 1.61%   |
| 333     | 1        | 1.61%   |

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
| Canon CanoScan LiDE 300 | 1        | 25%     |
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


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech Webcam C270                 | 3        | 30%     |
| WaveRider USB Live camera            | 1        | 10%     |
| Pixart Imaging GE 1.3 MP MiniCam Pro | 1        | 10%     |
| Microsoft LifeCam VX-800             | 1        | 10%     |
| Logitech Webcam C170                 | 1        | 10%     |
| Logitech HD Webcam C615              | 1        | 10%     |
| Generalplus 808 Camera               | 1        | 10%     |
| AVerMedia Live Streamer CAM 313      | 1        | 10%     |

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
| 0     | 80       | 85.11%  |
| 1     | 12       | 12.77%  |
| 2     | 2        | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 43.75%  |
| Net/wireless             | 4        | 25%     |
| Unassigned class         | 1        | 6.25%   |
| Storage/raid             | 1        | 6.25%   |
| Sound                    | 1        | 6.25%   |
| Net/ethernet             | 1        | 6.25%   |
| Communication controller | 1        | 6.25%   |

