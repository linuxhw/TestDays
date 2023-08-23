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

Total: 115

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-43-generic             | 11       | 11.22%  |
| 5.15.0-60-generic             | 5        | 5.1%    |
| 5.15.0-41-generic             | 5        | 5.1%    |
| 5.19.0-50-generic             | 4        | 4.08%   |
| 5.19.0-32-generic             | 4        | 4.08%   |
| 5.15.0-56-generic             | 4        | 4.08%   |
| 5.15.0-47-generic             | 4        | 4.08%   |
| 5.15.0-25-generic             | 4        | 4.08%   |
| 5.15.0-67-generic             | 3        | 3.06%   |
| 5.15.0-52-generic             | 3        | 3.06%   |
| 5.15.0-48-generic             | 3        | 3.06%   |
| 5.15.0-40-generic             | 3        | 3.06%   |
| 5.15.0-39-generic             | 3        | 3.06%   |
| 5.19.0-46-generic             | 2        | 2.04%   |
| 5.19.0-43-generic             | 2        | 2.04%   |
| 5.19.0-35-generic             | 2        | 2.04%   |
| 5.15.0-75-generic             | 2        | 2.04%   |
| 5.15.0-58-generic             | 2        | 2.04%   |
| 5.15.0-53-generic             | 2        | 2.04%   |
| 5.15.0-50-generic             | 2        | 2.04%   |
| 5.15.0-46-generic             | 2        | 2.04%   |
| 5.15.0-35-generic             | 2        | 2.04%   |
| 5.15.0-30-generic             | 2        | 2.04%   |
| 5.15.0-27-generic             | 2        | 2.04%   |
| 6.3.3-custom                  | 1        | 1.02%   |
| 6.2.8-x64v3-xanmod1           | 1        | 1.02%   |
| 6.2.0-26-generic              | 1        | 1.02%   |
| 6.1.0-custom                  | 1        | 1.02%   |
| 6.0.8-060008-generic          | 1        | 1.02%   |
| 6.0.14                        | 1        | 1.02%   |
| 5.19.0-45-generic             | 1        | 1.02%   |
| 5.19.0-41-generic             | 1        | 1.02%   |
| 5.19.0-16.2-liquorix-amd64    | 1        | 1.02%   |
| 5.19.0-1010-nvidia-lowlatency | 1        | 1.02%   |
| 5.15.0-72-generic             | 1        | 1.02%   |
| 5.15.0-71-generic             | 1        | 1.02%   |
| 5.15.0-69-lowlatency          | 1        | 1.02%   |
| 5.15.0-59-lowlatency          | 1        | 1.02%   |
| 5.15.0-58-lowlatency          | 1        | 1.02%   |
| 5.15.0-57-generic             | 1        | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 68       | 74.73%  |
| 5.19.0  | 17       | 18.68%  |
| 6.3.3   | 1        | 1.1%    |
| 6.2.8   | 1        | 1.1%    |
| 6.2.0   | 1        | 1.1%    |
| 6.1.0   | 1        | 1.1%    |
| 6.0.8   | 1        | 1.1%    |
| 6.0.14  | 1        | 1.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 68       | 74.73%  |
| 5.19    | 17       | 18.68%  |
| 6.2     | 2        | 2.2%    |
| 6.0     | 2        | 2.2%    |
| 6.3     | 1        | 1.1%    |
| 6.1     | 1        | 1.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 87       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| LXQt | 84       | 96.55%  |
| LXDE | 2        | 2.3%    |
| XFCE | 1        | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 83       | 92.22%  |
| Tty         | 5        | 5.56%   |
| Wayland     | 1        | 1.11%   |
| Unspecified | 1        | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 74       | 85.06%  |
| LightDM | 5        | 5.75%   |
| Unknown | 4        | 4.6%    |
| XDM     | 1        | 1.15%   |
| SLiM    | 1        | 1.15%   |
| LXDM    | 1        | 1.15%   |
| GDM3    | 1        | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 26       | 29.55%  |
| fr_FR | 13       | 14.77%  |
| de_DE | 8        | 9.09%   |
| it_IT | 6        | 6.82%   |
| es_ES | 6        | 6.82%   |
| en_GB | 4        | 4.55%   |
| pt_BR | 3        | 3.41%   |
| es_AR | 3        | 3.41%   |
| C     | 3        | 3.41%   |
| es_MX | 2        | 2.27%   |
| es_CR | 2        | 2.27%   |
| en_AU | 2        | 2.27%   |
| tr_TR | 1        | 1.14%   |
| sv_SE | 1        | 1.14%   |
| ru_UA | 1        | 1.14%   |
| pl_PL | 1        | 1.14%   |
| nl_BE | 1        | 1.14%   |
| es_PE | 1        | 1.14%   |
| en_AG | 1        | 1.14%   |
| el_GR | 1        | 1.14%   |
| cv_RU | 1        | 1.14%   |
| cs_CZ | 1        | 1.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 62       | 71.26%  |
| EFI  | 25       | 28.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 80       | 89.89%  |
| Tmpfs   | 4        | 4.49%   |
| Overlay | 3        | 3.37%   |
| XXX4    | 1        | 1.12%   |
| Btrfs   | 1        | 1.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 38       | 43.18%  |
| MBR     | 31       | 35.23%  |
| Unknown | 19       | 21.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 71       | 80.68%  |
| Yes       | 17       | 19.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 60.92%  |
| Yes       | 34       | 39.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 18.39%  |
| MSI                 | 15       | 17.24%  |
| Dell                | 10       | 11.49%  |
| Gigabyte Technology | 6        | 6.9%    |
| ASRock              | 6        | 6.9%    |
| Hewlett-Packard     | 5        | 5.75%   |
| Unknown             | 5        | 5.75%   |
| Pegatron            | 4        | 4.6%    |
| Acer                | 3        | 3.45%   |
| Positivo            | 2        | 2.3%    |
| Lenovo              | 2        | 2.3%    |
| Intel               | 2        | 2.3%    |
| AMI                 | 2        | 2.3%    |
| ZOTAC               | 1        | 1.15%   |
| YANYU               | 1        | 1.15%   |
| Shuttle             | 1        | 1.15%   |
| NEC Computers       | 1        | 1.15%   |
| Fujitsu             | 1        | 1.15%   |
| Foxconn             | 1        | 1.15%   |
| ECS                 | 1        | 1.15%   |
| BANGHO              | 1        | 1.15%   |
| AAEON               | 1        | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 5        | 5.75%   |
| MSI MS-7C37                            | 3        | 3.45%   |
| Dell Dimension 9100                    | 2        | 2.3%    |
| ZOTAC NM10                             | 1        | 1.15%   |
| YANYU ITX-S192                         | 1        | 1.15%   |
| Shuttle XS35V3                         | 1        | 1.15%   |
| Positivo POS-AG31AP                    | 1        | 1.15%   |
| Positivo P5VD2-MX                      | 1        | 1.15%   |
| Pegatron NC689AA-ABA s3700y            | 1        | 1.15%   |
| Pegatron h8-1350ef                     | 1        | 1.15%   |
| Pegatron Compaq dx2400 Microtower PC   | 1        | 1.15%   |
| Pegatron AY748AA-ABA p6320y            | 1        | 1.15%   |
| NEC Computers ECS-945G                 | 1        | 1.15%   |
| MSI MS-7D54                            | 1        | 1.15%   |
| MSI MS-7D09                            | 1        | 1.15%   |
| MSI MS-7C96                            | 1        | 1.15%   |
| MSI MS-7C56                            | 1        | 1.15%   |
| MSI MS-7C51                            | 1        | 1.15%   |
| MSI MS-7B86                            | 1        | 1.15%   |
| MSI MS-7B33                            | 1        | 1.15%   |
| MSI MS-7978                            | 1        | 1.15%   |
| MSI MS-7641                            | 1        | 1.15%   |
| MSI MS-7501                            | 1        | 1.15%   |
| MSI MS-7267                            | 1        | 1.15%   |
| MSI MS-7032                            | 1        | 1.15%   |
| Lenovo ThinkCentre M83 10ANCTO1WW      | 1        | 1.15%   |
| Lenovo ThinkCentre M600 10KGS09S00     | 1        | 1.15%   |
| Intel X79 V2.72A                       | 1        | 1.15%   |
| Intel BTC-T37                          | 1        | 1.15%   |
| HP Z400 Workstation                    | 1        | 1.15%   |
| HP t620 Quad Core TC                   | 1        | 1.15%   |
| HP Slim Desktop S01-pF1xxx             | 1        | 1.15%   |
| HP Compaq 8200 ELITE SMALL FORM FACTOR | 1        | 1.15%   |
| HP Compaq 8000 Elite SFF PC            | 1        | 1.15%   |
| Gigabyte GB-BMCE-5105                  | 1        | 1.15%   |
| Gigabyte G31M-S2C                      | 1        | 1.15%   |
| Gigabyte G31M-ES2C                     | 1        | 1.15%   |
| Gigabyte F2A58M-HD2                    | 1        | 1.15%   |
| Gigabyte B450 AORUS ELITE V2           | 1        | 1.15%   |
| Gigabyte B360M-DS3H                    | 1        | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 5        | 5.75%   |
| Dell OptiPlex          | 4        | 4.6%    |
| MSI MS-7C37            | 3        | 3.45%   |
| Lenovo ThinkCentre     | 2        | 2.3%    |
| HP Compaq              | 2        | 2.3%    |
| Dell Vostro            | 2        | 2.3%    |
| Dell Dimension         | 2        | 2.3%    |
| ASUS ROG               | 2        | 2.3%    |
| ASUS PRIME             | 2        | 2.3%    |
| ZOTAC NM10             | 1        | 1.15%   |
| YANYU ITX-S192         | 1        | 1.15%   |
| Shuttle XS35V3         | 1        | 1.15%   |
| Positivo POS-AG31AP    | 1        | 1.15%   |
| Positivo P5VD2-MX      | 1        | 1.15%   |
| Pegatron NC689AA-ABA   | 1        | 1.15%   |
| Pegatron h8-1350ef     | 1        | 1.15%   |
| Pegatron Compaq        | 1        | 1.15%   |
| Pegatron AY748AA-ABA   | 1        | 1.15%   |
| NEC Computers ECS-945G | 1        | 1.15%   |
| MSI MS-7D54            | 1        | 1.15%   |
| MSI MS-7D09            | 1        | 1.15%   |
| MSI MS-7C96            | 1        | 1.15%   |
| MSI MS-7C56            | 1        | 1.15%   |
| MSI MS-7C51            | 1        | 1.15%   |
| MSI MS-7B86            | 1        | 1.15%   |
| MSI MS-7B33            | 1        | 1.15%   |
| MSI MS-7978            | 1        | 1.15%   |
| MSI MS-7641            | 1        | 1.15%   |
| MSI MS-7501            | 1        | 1.15%   |
| MSI MS-7267            | 1        | 1.15%   |
| MSI MS-7032            | 1        | 1.15%   |
| Intel X79              | 1        | 1.15%   |
| Intel BTC-T37          | 1        | 1.15%   |
| HP Z400                | 1        | 1.15%   |
| HP t620                | 1        | 1.15%   |
| HP Slim                | 1        | 1.15%   |
| Gigabyte GB-BMCE-5105  | 1        | 1.15%   |
| Gigabyte G31M-S2C      | 1        | 1.15%   |
| Gigabyte G31M-ES2C     | 1        | 1.15%   |
| Gigabyte F2A58M-HD2    | 1        | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2008 | 10       | 11.49%  |
| 2019 | 8        | 9.2%    |
| 2010 | 8        | 9.2%    |
| 2009 | 7        | 8.05%   |
| 2020 | 6        | 6.9%    |
| 2017 | 6        | 6.9%    |
| 2021 | 5        | 5.75%   |
| 2018 | 5        | 5.75%   |
| 2011 | 5        | 5.75%   |
| 2007 | 5        | 5.75%   |
| 2015 | 4        | 4.6%    |
| 2014 | 4        | 4.6%    |
| 2013 | 4        | 4.6%    |
| 2012 | 3        | 3.45%   |
| 2022 | 2        | 2.3%    |
| 2016 | 2        | 2.3%    |
| 2006 | 2        | 2.3%    |
| 2001 | 1        | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 87       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 85       | 97.7%   |
| Enabled  | 2        | 2.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 87       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 17       | 19.1%   |
| 4.01-8.0    | 16       | 17.98%  |
| 16.01-24.0  | 13       | 14.61%  |
| 8.01-16.0   | 12       | 13.48%  |
| 1.01-2.0    | 11       | 12.36%  |
| 32.01-64.0  | 10       | 11.24%  |
| 64.01-256.0 | 4        | 4.49%   |
| 2.01-3.0    | 3        | 3.37%   |
| 0.51-1.0    | 3        | 3.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 39       | 41.94%  |
| 0.51-1.0  | 20       | 21.51%  |
| 2.01-3.0  | 18       | 19.35%  |
| 4.01-8.0  | 10       | 10.75%  |
| 3.01-4.0  | 3        | 3.23%   |
| 8.01-16.0 | 2        | 2.15%   |
| 0.01-0.5  | 1        | 1.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 44       | 50.57%  |
| 2      | 27       | 31.03%  |
| 3      | 7        | 8.05%   |
| 5      | 3        | 3.45%   |
| 4      | 2        | 2.3%    |
| 12     | 1        | 1.15%   |
| 7      | 1        | 1.15%   |
| 6      | 1        | 1.15%   |
| 0      | 1        | 1.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 60.23%  |
| Yes       | 35       | 39.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 86       | 98.85%  |
| No        | 1        | 1.15%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 57.47%  |
| Yes       | 37       | 42.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 77.53%  |
| Yes       | 20       | 22.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 16       | 18.39%  |
| France     | 13       | 14.94%  |
| Germany    | 9        | 10.34%  |
| Spain      | 7        | 8.05%   |
| Italy      | 6        | 6.9%    |
| Poland     | 4        | 4.6%    |
| Brazil     | 4        | 4.6%    |
| UK         | 3        | 3.45%   |
| Argentina  | 3        | 3.45%   |
| Sweden     | 2        | 2.3%    |
| Costa Rica | 2        | 2.3%    |
| Australia  | 2        | 2.3%    |
| Venezuela  | 1        | 1.15%   |
| Ukraine    | 1        | 1.15%   |
| Turkey     | 1        | 1.15%   |
| Romania    | 1        | 1.15%   |
| Peru       | 1        | 1.15%   |
| Pakistan   | 1        | 1.15%   |
| Mexico     | 1        | 1.15%   |
| Luxembourg | 1        | 1.15%   |
| Latvia     | 1        | 1.15%   |
| Ireland    | 1        | 1.15%   |
| Iran       | 1        | 1.15%   |
| Indonesia  | 1        | 1.15%   |
| Greece     | 1        | 1.15%   |
| Czechia    | 1        | 1.15%   |
| Bulgaria   | 1        | 1.15%   |
| Belgium    | 1        | 1.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Paris                | 3        | 3.23%   |
| Melbourne            | 2        | 2.15%   |
| Largo                | 2        | 2.15%   |
| Karlstad             | 2        | 2.15%   |
| Heredia              | 2        | 2.15%   |
| Wetteren             | 1        | 1.08%   |
| Washington           | 1        | 1.08%   |
| Warsaw               | 1        | 1.08%   |
| Versailles           | 1        | 1.08%   |
| Varna                | 1        | 1.08%   |
| Valentigney          | 1        | 1.08%   |
| Valencia             | 1        | 1.08%   |
| Turin                | 1        | 1.08%   |
| Torrejón de Ardoz   | 1        | 1.08%   |
| Tehran               | 1        | 1.08%   |
| Tandil               | 1        | 1.08%   |
| St Louis             | 1        | 1.08%   |
| Sonico               | 1        | 1.08%   |
| Sao Paulo            | 1        | 1.08%   |
| Saltsjoe-Boo         | 1        | 1.08%   |
| Riverenert           | 1        | 1.08%   |
| Rio Segundo          | 1        | 1.08%   |
| Richmond             | 1        | 1.08%   |
| Resistencia          | 1        | 1.08%   |
| Prague               | 1        | 1.08%   |
| Port Washington      | 1        | 1.08%   |
| Palencia             | 1        | 1.08%   |
| Ostrów Wielkopolski | 1        | 1.08%   |
| Oberkotzau           | 1        | 1.08%   |
| Novo Gama            | 1        | 1.08%   |
| Notting Hill Gate    | 1        | 1.08%   |
| Nederland            | 1        | 1.08%   |
| Mostoles             | 1        | 1.08%   |
| Monheim am Rhein     | 1        | 1.08%   |
| Mogi Guacu           | 1        | 1.08%   |
| Mobile               | 1        | 1.08%   |
| Mexico City          | 1        | 1.08%   |
| Marseille            | 1        | 1.08%   |
| Madrid               | 1        | 1.08%   |
| Lyon                 | 1        | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 27       | 39     | 19.57%  |
| Samsung Electronics         | 20       | 28     | 14.49%  |
| WDC                         | 19       | 33     | 13.77%  |
| Kingston                    | 11       | 13     | 7.97%   |
| Hitachi                     | 11       | 15     | 7.97%   |
| SanDisk                     | 6        | 6      | 4.35%   |
| Crucial                     | 5        | 5      | 3.62%   |
| Toshiba                     | 3        | 3      | 2.17%   |
| A-DATA Technology           | 3        | 3      | 2.17%   |
| Unknown                     | 2        | 2      | 1.45%   |
| PNY                         | 2        | 2      | 1.45%   |
| Maxtor                      | 2        | 2      | 1.45%   |
| HGST                        | 2        | 2      | 1.45%   |
| GOODRAM                     | 2        | 2      | 1.45%   |
| China                       | 2        | 2      | 1.45%   |
| WD MediaMax                 | 1        | 1      | 0.72%   |
| Transcend                   | 1        | 2      | 0.72%   |
| TO Exter                    | 1        | 1      | 0.72%   |
| Team                        | 1        | 1      | 0.72%   |
| T-FORCE                     | 1        | 1      | 0.72%   |
| RSH-319                     | 1        | 1      | 0.72%   |
| Patriot                     | 1        | 1      | 0.72%   |
| Micron/Crucial Technology   | 1        | 2      | 0.72%   |
| LITEONIT                    | 1        | 1      | 0.72%   |
| Kston                       | 1        | 3      | 0.72%   |
| Kingston Technology Company | 1        | 1      | 0.72%   |
| Intel                       | 1        | 1      | 0.72%   |
| HGST HUS                    | 1        | 2      | 0.72%   |
| Gigabyte Technology         | 1        | 1      | 0.72%   |
| External                    | 1        | 1      | 0.72%   |
| Emtec                       | 1        | 1      | 0.72%   |
| BR                          | 1        | 1      | 0.72%   |
| Apricorn                    | 1        | 1      | 0.72%   |
| Apple                       | 1        | 1      | 0.72%   |
| Apacer                      | 1        | 1      | 0.72%   |
| AMD                         | 1        | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 6        | 3.75%   |
| Kingston SA400S37240G 240GB SSD    | 5        | 3.13%   |
| Toshiba DT01ACA100 1TB             | 2        | 1.25%   |
| Seagate ST3120213AS 120GB          | 2        | 1.25%   |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB     | 2        | 1.25%   |
| SanDisk DF4032  32GB               | 2        | 1.25%   |
| Samsung SSD 870 EVO 500GB          | 2        | 1.25%   |
| Samsung HD502HJ 500GB              | 2        | 1.25%   |
| Kingston SA400S37120G 120GB SSD    | 2        | 1.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.63%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 0.63%   |
| WDC WD800BB-00CAA1 80GB            | 1        | 0.63%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 0.63%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1        | 0.63%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 0.63%   |
| WDC WD5000AAKX-75U6AA0 500GB       | 1        | 0.63%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 0.63%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1        | 0.63%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 1        | 0.63%   |
| WDC WD3200BPVT-00HXZT3 320GB       | 1        | 0.63%   |
| WDC WD3200AAJS-65M0A0 320GB        | 1        | 0.63%   |
| WDC WD3200AAJS-56M0A0 320GB        | 1        | 0.63%   |
| WDC WD3200AAJS-56B4A0 320GB        | 1        | 0.63%   |
| WDC WD3200AACS-00M6B0 320GB        | 1        | 0.63%   |
| WDC WD30EZRZ-00GXCB0 3TB           | 1        | 0.63%   |
| WDC WD2500KS-00MJB0 250GB          | 1        | 0.63%   |
| WDC WD2500AAJS-07M0A0 250GB        | 1        | 0.63%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1        | 0.63%   |
| WDC WD20EZBX-00AYRA0 2TB           | 1        | 0.63%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 1        | 0.63%   |
| WDC WD2003FYYS-02W0B0 2TB          | 1        | 0.63%   |
| WDC WD10SPZX-08Z10 1TB             | 1        | 0.63%   |
| WDC WD10S21X-24R1BT0-SSHD-8GB      | 1        | 0.63%   |
| WDC WD10EZRZ-00Z5HB0 1TB           | 1        | 0.63%   |
| WDC WD10EZEX-60WN4A1 1TB           | 1        | 0.63%   |
| WDC WD10EURX-63C57Y0 1TB           | 1        | 0.63%   |
| WDC WD10EACS-00D6B1 1TB            | 1        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 38     | 36.99%  |
| WDC                 | 17       | 28     | 23.29%  |
| Hitachi             | 11       | 15     | 15.07%  |
| Samsung Electronics | 6        | 7      | 8.22%   |
| Toshiba             | 3        | 3      | 4.11%   |
| Maxtor              | 2        | 2      | 2.74%   |
| HGST                | 2        | 2      | 2.74%   |
| WD MediaMax         | 1        | 1      | 1.37%   |
| RSH-319             | 1        | 1      | 1.37%   |
| External            | 1        | 1      | 1.37%   |
| Apricorn            | 1        | 1      | 1.37%   |
| Apple               | 1        | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 10       | 12     | 21.74%  |
| Samsung Electronics | 9        | 14     | 19.57%  |
| SanDisk             | 4        | 4      | 8.7%    |
| WDC                 | 2        | 2      | 4.35%   |
| PNY                 | 2        | 2      | 4.35%   |
| GOODRAM             | 2        | 2      | 4.35%   |
| Crucial             | 2        | 2      | 4.35%   |
| China               | 2        | 2      | 4.35%   |
| A-DATA Technology   | 2        | 2      | 4.35%   |
| Transcend           | 1        | 2      | 2.17%   |
| TO Exter            | 1        | 1      | 2.17%   |
| Team                | 1        | 1      | 2.17%   |
| Patriot             | 1        | 1      | 2.17%   |
| LITEONIT            | 1        | 1      | 2.17%   |
| Kston               | 1        | 3      | 2.17%   |
| Intel               | 1        | 1      | 2.17%   |
| Gigabyte Technology | 1        | 1      | 2.17%   |
| Emtec               | 1        | 1      | 2.17%   |
| BR                  | 1        | 1      | 2.17%   |
| Apacer              | 1        | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 54       | 100    | 46.15%  |
| SSD     | 43       | 56     | 36.75%  |
| NVMe    | 14       | 19     | 11.97%  |
| MMC     | 5        | 5      | 4.27%   |
| Unknown | 1        | 3      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 78       | 152    | 77.23%  |
| NVMe | 14       | 19     | 13.86%  |
| MMC  | 5        | 5      | 4.95%   |
| SAS  | 4        | 7      | 3.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 66       | 97     | 62.26%  |
| 0.51-1.0   | 18       | 25     | 16.98%  |
| 1.01-2.0   | 13       | 19     | 12.26%  |
| 2.01-3.0   | 4        | 5      | 3.77%   |
| 4.01-10.0  | 3        | 6      | 2.83%   |
| 3.01-4.0   | 2        | 4      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 29.21%  |
| 251-500        | 13       | 14.61%  |
| 21-50          | 10       | 11.24%  |
| 1001-2000      | 10       | 11.24%  |
| More than 3000 | 7        | 7.87%   |
| 51-100         | 7        | 7.87%   |
| 1-20           | 6        | 6.74%   |
| 501-1000       | 6        | 6.74%   |
| 2001-3000      | 4        | 4.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 40       | 43.48%  |
| 21-50          | 15       | 16.3%   |
| 101-250        | 10       | 10.87%  |
| 51-100         | 8        | 8.7%    |
| 501-1000       | 6        | 6.52%   |
| More than 3000 | 4        | 4.35%   |
| 1001-2000      | 4        | 4.35%   |
| 251-500        | 3        | 3.26%   |
| 2001-3000      | 2        | 2.17%   |

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
| Works    | 42       | 77     | 42.42%  |
| Detected | 40       | 84     | 40.4%   |
| Malfunc  | 14       | 19     | 14.14%  |
| Failed   | 3        | 3      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 49       | 43.75%  |
| AMD                         | 28       | 25%     |
| Samsung Electronics         | 6        | 5.36%   |
| ASMedia Technology          | 5        | 4.46%   |
| Nvidia                      | 4        | 3.57%   |
| Micron/Crucial Technology   | 4        | 3.57%   |
| JMicron Technology          | 4        | 3.57%   |
| SanDisk                     | 3        | 2.68%   |
| VIA Technologies            | 2        | 1.79%   |
| Marvell Technology Group    | 2        | 1.79%   |
| Kingston Technology Company | 2        | 1.79%   |
| Seagate Technology          | 1        | 0.89%   |
| LSI Logic / Symbios Logic   | 1        | 0.89%   |
| ADATA Technology            | 1        | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16       | 10.26%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13       | 8.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 12       | 7.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6        | 3.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5        | 3.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 3.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 3.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 1.92%   |
| Intel SATA Controller [RAID mode]                                              | 3        | 1.92%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2        | 1.28%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 1.28%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.28%   |
| Nvidia MCP61 IDE                                                               | 2        | 1.28%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2        | 1.28%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 1.28%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 2        | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 1.28%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 2        | 1.28%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 2        | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.28%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2        | 1.28%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2        | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 2        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.28%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.28%   |
| AMD FCH IDE Controller                                                         | 2        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 1.28%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 1        | 0.64%   |
| VIA Serial ATA Controller                                                      | 1        | 0.64%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.64%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.64%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.64%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 56       | 50%     |
| IDE  | 37       | 33.04%  |
| NVMe | 14       | 12.5%   |
| RAID | 4        | 3.57%   |
| SAS  | 1        | 0.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 54       | 62.07%  |
| AMD    | 33       | 37.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-8400 CPU @ 2.80GHz                | 3        | 3.45%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3        | 3.45%   |
| Intel Atom CPU D525 @ 1.80GHz                   | 3        | 3.45%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz          | 2        | 2.3%    |
| Intel Pentium D CPU 2.80GHz                     | 2        | 2.3%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 2.3%    |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2        | 2.3%    |
| AMD Ryzen 5 1600 Six-Core Processor             | 2        | 2.3%    |
| AMD Athlon 64 X2 Dual Core Processor 5000+      | 2        | 2.3%    |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 2        | 2.3%    |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1        | 1.15%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz             | 1        | 1.15%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz             | 1        | 1.15%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 1.15%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 1.15%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 1.15%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 1.15%   |
| Intel Core i9-10900K CPU @ 3.70GHz              | 1        | 1.15%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1        | 1.15%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 1.15%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.15%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 1.15%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 1.15%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.15%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.15%   |
| Intel Core i3-4170 CPU @ 3.70GHz                | 1        | 1.15%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.15%   |
| Intel Core i3-10105 CPU @ 3.70GHz               | 1        | 1.15%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 1        | 1.15%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz           | 1        | 1.15%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 1        | 1.15%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.15%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz            | 1        | 1.15%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz            | 1        | 1.15%   |
| Intel Core 2 Duo CPU E4600 @ 2.40GHz            | 1        | 1.15%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz            | 1        | 1.15%   |
| Intel Celeron N5105 @ 2.00GHz                   | 1        | 1.15%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1        | 1.15%   |
| Intel Celeron CPU N3010 @ 1.04GHz               | 1        | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9        | 10.34%  |
| Intel Celeron           | 9        | 10.34%  |
| Intel Atom              | 9        | 10.34%  |
| Intel Core 2 Duo        | 6        | 6.9%    |
| AMD Ryzen 5             | 6        | 6.9%    |
| AMD Ryzen 7             | 5        | 5.75%   |
| Intel Core 2 Quad       | 4        | 4.6%    |
| Intel Xeon              | 3        | 3.45%   |
| Intel Pentium Dual-Core | 3        | 3.45%   |
| Intel Pentium Dual      | 3        | 3.45%   |
| Intel Core i3           | 3        | 3.45%   |
| AMD Ryzen 9             | 3        | 3.45%   |
| AMD FX                  | 3        | 3.45%   |
| AMD Athlon 64 X2        | 3        | 3.45%   |
| Intel Pentium D         | 2        | 2.3%    |
| Intel Core i7           | 2        | 2.3%    |
| AMD Phenom II X4        | 2        | 2.3%    |
| AMD A10                 | 2        | 2.3%    |
| Other                   | 1        | 1.15%   |
| Intel Core i9           | 1        | 1.15%   |
| AMD Ryzen 5 PRO         | 1        | 1.15%   |
| AMD Phenom II X6        | 1        | 1.15%   |
| AMD GX                  | 1        | 1.15%   |
| AMD G                   | 1        | 1.15%   |
| AMD Athlon II X3        | 1        | 1.15%   |
| AMD Athlon II X2        | 1        | 1.15%   |
| AMD A8                  | 1        | 1.15%   |
| AMD A4                  | 1        | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 32       | 36.78%  |
| 4      | 29       | 33.33%  |
| 6      | 10       | 11.49%  |
| 8      | 6        | 6.9%    |
| 1      | 4        | 4.6%    |
| 3      | 3        | 3.45%   |
| 16     | 1        | 1.15%   |
| 12     | 1        | 1.15%   |
| 10     | 1        | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 64.37%  |
| 2      | 31       | 35.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 87       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 42       | 46.67%  |
| 0x1067a    | 5        | 5.56%   |
| 0x406c4    | 4        | 4.44%   |
| 0x906ea    | 3        | 3.33%   |
| 0x106ca    | 3        | 3.33%   |
| 0x6fb      | 2        | 2.22%   |
| 0x306c3    | 2        | 2.22%   |
| 0x206a7    | 2        | 2.22%   |
| 0x06003106 | 2        | 2.22%   |
| 0x010000db | 2        | 2.22%   |
| 0xa0653    | 1        | 1.11%   |
| 0x906c0    | 1        | 1.11%   |
| 0x706a8    | 1        | 1.11%   |
| 0x6fd      | 1        | 1.11%   |
| 0x506e3    | 1        | 1.11%   |
| 0x506c9    | 1        | 1.11%   |
| 0x306e4    | 1        | 1.11%   |
| 0x30679    | 1        | 1.11%   |
| 0x106a5    | 1        | 1.11%   |
| 0x10676    | 1        | 1.11%   |
| 0x10661    | 1        | 1.11%   |
| 0x0a601203 | 1        | 1.11%   |
| 0x0a50000d | 1        | 1.11%   |
| 0x0a50000c | 1        | 1.11%   |
| 0x0a50000b | 1        | 1.11%   |
| 0x0a201009 | 1        | 1.11%   |
| 0x08701021 | 1        | 1.11%   |
| 0x08701013 | 1        | 1.11%   |
| 0x08001138 | 1        | 1.11%   |
| 0x0700010f | 1        | 1.11%   |
| 0x06001119 | 1        | 1.11%   |
| 0x06000852 | 1        | 1.11%   |
| 0x010000c7 | 1        | 1.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 11       | 12.64%  |
| Core          | 7        | 8.05%   |
| Zen 3         | 6        | 6.9%    |
| Silvermont    | 6        | 6.9%    |
| K10           | 5        | 5.75%   |
| Bonnell       | 5        | 5.75%   |
| K8 Hammer     | 4        | 4.6%    |
| Haswell       | 4        | 4.6%    |
| Zen+          | 3        | 3.45%   |
| Zen 2         | 3        | 3.45%   |
| SandyBridge   | 3        | 3.45%   |
| Piledriver    | 3        | 3.45%   |
| KabyLake      | 3        | 3.45%   |
| IvyBridge     | 3        | 3.45%   |
| Zen           | 2        | 2.3%    |
| Steamroller   | 2        | 2.3%    |
| Skylake       | 2        | 2.3%    |
| NetBurst      | 2        | 2.3%    |
| Nehalem       | 2        | 2.3%    |
| Goldmont plus | 2        | 2.3%    |
| CometLake     | 2        | 2.3%    |
| Tremont       | 1        | 1.15%   |
| K10 Llano     | 1        | 1.15%   |
| Jaguar        | 1        | 1.15%   |
| Goldmont      | 1        | 1.15%   |
| Bulldozer     | 1        | 1.15%   |
| Bobcat        | 1        | 1.15%   |
| Unknown       | 1        | 1.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 32       | 34.78%  |
| Nvidia | 31       | 33.7%   |
| Intel  | 29       | 31.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5        | 5.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 5.15%   |
| Nvidia GT218 [ION]                                                                       | 3        | 3.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 3.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 3.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 3.09%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3        | 3.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3        | 3.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 2.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 2.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 2.06%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 2.06%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2        | 2.06%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2        | 2.06%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 2        | 2.06%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2        | 2.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.06%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 2.06%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 1.03%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 1.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.03%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1        | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.03%   |
| Nvidia GM200GL [Tesla M40]                                                               | 1        | 1.03%   |
| Nvidia GM200GL [Quadro M6000]                                                            | 1        | 1.03%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1        | 1.03%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.03%   |
| Nvidia GK208B [GeForce GT 720]                                                           | 1        | 1.03%   |
| Nvidia GK106GL [Quadro K4000]                                                            | 1        | 1.03%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.03%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 1        | 1.03%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 1.03%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 1        | 1.03%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 1        | 1.03%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.03%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 1        | 1.03%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 1        | 1.03%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.03%   |
| Nvidia G86 [GeForce 8400 GS]                                                             | 1        | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 28       | 32.18%  |
| 1 x Intel          | 26       | 29.89%  |
| 1 x AMD            | 26       | 29.89%  |
| 2 x AMD            | 3        | 3.45%   |
| AMD + Nvidia       | 2        | 2.3%    |
| Intel + 2 x Nvidia | 1        | 1.15%   |
| Intel + 2 x AMD    | 1        | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 71       | 81.61%  |
| Proprietary | 11       | 12.64%  |
| Unknown     | 5        | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 56       | 63.64%  |
| 0.01-0.5   | 10       | 11.36%  |
| 0.51-1.0   | 8        | 9.09%   |
| 7.01-8.0   | 5        | 5.68%   |
| 1.01-2.0   | 3        | 3.41%   |
| 8.01-16.0  | 3        | 3.41%   |
| 3.01-4.0   | 2        | 2.27%   |
| 2.01-3.0   | 1        | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 12       | 15.38%  |
| Hewlett-Packard      | 8        | 10.26%  |
| Dell                 | 8        | 10.26%  |
| Philips              | 6        | 7.69%   |
| Goldstar             | 6        | 7.69%   |
| Acer                 | 5        | 6.41%   |
| Iiyama               | 3        | 3.85%   |
| Eizo                 | 3        | 3.85%   |
| Ancor Communications | 3        | 3.85%   |
| Sony                 | 2        | 2.56%   |
| HannStar             | 2        | 2.56%   |
| BenQ                 | 2        | 2.56%   |
| Westinghouse         | 1        | 1.28%   |
| Vizio                | 1        | 1.28%   |
| ViewSonic            | 1        | 1.28%   |
| VHT                  | 1        | 1.28%   |
| Unknown (ADA)        | 1        | 1.28%   |
| Unknown              | 1        | 1.28%   |
| SNC                  | 1        | 1.28%   |
| Sharp                | 1        | 1.28%   |
| Sampo                | 1        | 1.28%   |
| RTK                  | 1        | 1.28%   |
| Positivo             | 1        | 1.28%   |
| MSI                  | 1        | 1.28%   |
| LG Electronics       | 1        | 1.28%   |
| Jean                 | 1        | 1.28%   |
| Daewoo               | 1        | 1.28%   |
| Compal               | 1        | 1.28%   |
| Belinea              | 1        | 1.28%   |
| AOC                  | 1        | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2        | 2.47%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1        | 1.23%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                | 1        | 1.23%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch        | 1        | 1.23%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1        | 1.23%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1        | 1.23%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1        | 1.23%   |
| Sony TV SNY9C01 1360x768                                             | 1        | 1.23%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                   | 1        | 1.23%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1        | 1.23%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1        | 1.23%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 1.23%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1        | 1.23%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1        | 1.23%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch     | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                  | 1        | 1.23%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 1        | 1.23%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch   | 1        | 1.23%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 600x340mm 27.2-inch    | 1        | 1.23%   |
| Sampo 800S STC0800 800x600 170x127mm 8.4-inch                        | 1        | 1.23%   |
| RTK ARZOPA RTKBC33 1920x1080 309x174mm 14.0-inch                     | 1        | 1.23%   |
| Positivo SMILE4XX NON1400 1360x768 309x174mm 14.0-inch               | 1        | 1.23%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 1        | 1.23%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 1        | 1.23%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch            | 1        | 1.23%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch             | 1        | 1.23%   |
| Philips 220S4L PHL08BE 1680x1050 474x296mm 22.0-inch                 | 1        | 1.23%   |
| Philips 191EL PHLC050 1366x768 410x230mm 18.5-inch                   | 1        | 1.23%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                  | 1        | 1.23%   |
| LG Electronics LCD Monitor E2241 1920x1080                           | 1        | 1.23%   |
| Jean JT178x4 JEN0DB2 1280x1024 338x270mm 17.0-inch                   | 1        | 1.23%   |
| Iiyama PL2792H IVM664F 1920x1080 598x336mm 27.0-inch                 | 1        | 1.23%   |
| Iiyama PL2791Q IVM6646 2560x1440 597x336mm 27.0-inch                 | 1        | 1.23%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                 | 1        | 1.23%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                 | 1        | 1.23%   |
| Hewlett-Packard w2338h HWP281B 1920x1080 510x290mm 23.1-inch         | 1        | 1.23%   |
| Hewlett-Packard W2071d HWP299E 1600x900 443x249mm 20.0-inch          | 1        | 1.23%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 1        | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 30       | 38.46%  |
| 1280x1024 (SXGA)   | 9        | 11.54%  |
| 1680x1050 (WSXGA+) | 7        | 8.97%   |
| 1366x768 (WXGA)    | 7        | 8.97%   |
| 1600x900 (HD+)     | 5        | 6.41%   |
| 2560x1440 (QHD)    | 4        | 5.13%   |
| 1440x900 (WXGA+)   | 4        | 5.13%   |
| 1360x768           | 3        | 3.85%   |
| 3840x2160 (4K)     | 2        | 2.56%   |
| 800x600            | 1        | 1.28%   |
| 2560x1600          | 1        | 1.28%   |
| 1920x1200 (WUXGA)  | 1        | 1.28%   |
| 1280x800 (WXGA)    | 1        | 1.28%   |
| 1280x768           | 1        | 1.28%   |
| 1280x720 (HD)      | 1        | 1.28%   |
| 1024x768 (XGA)     | 1        | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 10       | 13.16%  |
| 24      | 9        | 11.84%  |
| 18      | 9        | 11.84%  |
| 22      | 7        | 9.21%   |
| 19      | 7        | 9.21%   |
| 23      | 6        | 7.89%   |
| Unknown | 6        | 7.89%   |
| 21      | 5        | 6.58%   |
| 20      | 4        | 5.26%   |
| 17      | 3        | 3.95%   |
| 15      | 2        | 2.63%   |
| 72      | 1        | 1.32%   |
| 49      | 1        | 1.32%   |
| 47      | 1        | 1.32%   |
| 43      | 1        | 1.32%   |
| 34      | 1        | 1.32%   |
| 14      | 1        | 1.32%   |
| 8       | 1        | 1.32%   |
| 7       | 1        | 1.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 28       | 36.84%  |
| 501-600     | 25       | 32.89%  |
| 301-350     | 6        | 7.89%   |
| Unknown     | 6        | 7.89%   |
| 351-400     | 4        | 5.26%   |
| 101-200     | 2        | 2.63%   |
| 1001-1500   | 2        | 2.63%   |
| 701-800     | 1        | 1.32%   |
| 1501-2000   | 1        | 1.32%   |
| 901-1000    | 1        | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 62.16%  |
| 16/10   | 12       | 16.22%  |
| 5/4     | 7        | 9.46%   |
| Unknown | 5        | 6.76%   |
| 4/3     | 3        | 4.05%   |
| 3/2     | 1        | 1.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 21       | 28%     |
| 151-200        | 15       | 20%     |
| 301-350        | 10       | 13.33%  |
| 141-150        | 10       | 13.33%  |
| Unknown        | 6        | 8%      |
| 251-300        | 3        | 4%      |
| 501-1000       | 3        | 4%      |
| More than 1000 | 2        | 2.67%   |
| 1-40           | 2        | 2.67%   |
| 81-90          | 1        | 1.33%   |
| 111-120        | 1        | 1.33%   |
| 101-110        | 1        | 1.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 49       | 66.22%  |
| 101-120 | 12       | 16.22%  |
| Unknown | 6        | 8.11%   |
| 1-50    | 5        | 6.76%   |
| 161-240 | 2        | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 74       | 84.09%  |
| 2     | 9        | 10.23%  |
| 0     | 5        | 5.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 57       | 44.88%  |
| Intel                           | 26       | 20.47%  |
| Qualcomm Atheros                | 10       | 7.87%   |
| Broadcom                        | 5        | 3.94%   |
| TP-Link                         | 4        | 3.15%   |
| Nvidia                          | 3        | 2.36%   |
| NetGear                         | 3        | 2.36%   |
| MediaTek                        | 3        | 2.36%   |
| VIA Technologies                | 2        | 1.57%   |
| Samsung Electronics             | 2        | 1.57%   |
| Qualcomm Atheros Communications | 2        | 1.57%   |
| Xiaomi                          | 1        | 0.79%   |
| Trident Microsystems            | 1        | 0.79%   |
| Texas Instruments               | 1        | 0.79%   |
| Ralink Technology               | 1        | 0.79%   |
| Ralink                          | 1        | 0.79%   |
| Marvell Technology Group        | 1        | 0.79%   |
| ICS Advent                      | 1        | 0.79%   |
| Broadcom Limited                | 1        | 0.79%   |
| ASUSTek Computer                | 1        | 0.79%   |
| Accton Technology               | 1        | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 49       | 36.03%  |
| Intel Ethernet Controller I225-V                                    | 4        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 3        | 2.21%   |
| VIA VT6102/VT6103 [Rhine-II]                                        | 2        | 1.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 2        | 1.47%   |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 1.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 1.47%   |
| Nvidia MCP77 Ethernet                                               | 2        | 1.47%   |
| NetGear A6210                                                       | 2        | 1.47%   |
| Intel NM10/ICH7 Family LAN Controller                               | 2        | 1.47%   |
| Intel I211 Gigabit Network Connection                               | 2        | 1.47%   |
| Intel Ethernet Connection I217-LM                                   | 2        | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 2        | 1.47%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 1.47%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                | 1        | 0.74%   |
| Trident Microsystems 4DWave DX                                      | 1        | 0.74%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 0.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.74%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 0.74%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.74%   |
| Texas Instruments CC2531 ZigBee                                     | 1        | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 1        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1        | 0.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.74%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.74%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                   | 1        | 0.74%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 0.74%   |
| Realtek 802.11ac NIC                                                | 1        | 0.74%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.74%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 1        | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 10       | 25%     |
| Intel                           | 8        | 20%     |
| TP-Link                         | 4        | 10%     |
| Qualcomm Atheros                | 4        | 10%     |
| MediaTek                        | 3        | 7.5%    |
| Broadcom                        | 3        | 7.5%    |
| Qualcomm Atheros Communications | 2        | 5%      |
| NetGear                         | 2        | 5%      |
| Ralink Technology               | 1        | 2.5%    |
| Ralink                          | 1        | 2.5%    |
| Broadcom Limited                | 1        | 2.5%    |
| ASUSTek Computer                | 1        | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2        | 5%      |
| Qualcomm Atheros AR9271 802.11n                                     | 2        | 5%      |
| NetGear A6210                                                       | 2        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2        | 5%      |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2        | 5%      |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1        | 2.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 2.5%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 2.5%    |
| TP-Link 802.11ac NIC                                                | 1        | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 2.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 2.5%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 2.5%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter             | 1        | 2.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1        | 2.5%    |
| Realtek 802.11ac NIC                                                | 1        | 2.5%    |
| Ralink RT5572 Wireless Adapter                                      | 1        | 2.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 1        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1        | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1        | 2.5%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                    | 1        | 2.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 1        | 2.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 1        | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 1        | 2.5%    |
| Intel Wireless 7265                                                 | 1        | 2.5%    |
| Intel Wireless 3165                                                 | 1        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                 | 1        | 2.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection             | 1        | 2.5%    |
| Intel Centrino Advanced-N 6235                                      | 1        | 2.5%    |
| Broadcom Limited BCM43224 802.11a/b/g/n                             | 1        | 2.5%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                   | 1        | 2.5%    |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]      | 1        | 2.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 54       | 58.06%  |
| Intel                    | 18       | 19.35%  |
| Qualcomm Atheros         | 7        | 7.53%   |
| Nvidia                   | 3        | 3.23%   |
| VIA Technologies         | 2        | 2.15%   |
| Broadcom                 | 2        | 2.15%   |
| Xiaomi                   | 1        | 1.08%   |
| Trident Microsystems     | 1        | 1.08%   |
| Samsung Electronics      | 1        | 1.08%   |
| NetGear                  | 1        | 1.08%   |
| Marvell Technology Group | 1        | 1.08%   |
| ICS Advent               | 1        | 1.08%   |
| Accton Technology        | 1        | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 52.13%  |
| Intel Ethernet Controller I225-V                                  | 4        | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.19%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 2.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 2.13%   |
| Nvidia MCP77 Ethernet                                             | 2        | 2.13%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 2.13%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.13%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 1.06%   |
| Trident Microsystems 4DWave DX                                    | 1        | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.06%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.06%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 1.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.06%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.06%   |
| NetGear LB1120-100NAS                                             | 1        | 1.06%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.06%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.06%   |
| Intel 82567V-3 Gigabit Network Connection                         | 1        | 1.06%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.06%   |
| ICS Advent 10/100M LAN                                            | 1        | 1.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.06%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1        | 1.06%   |
| Accton SMC2-1211TX                                                | 1        | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 68.8%   |
| WiFi     | 37       | 29.6%   |
| Modem    | 2        | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 64       | 71.91%  |
| WiFi     | 25       | 28.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 59       | 67.82%  |
| 2     | 24       | 27.59%  |
| 3     | 2        | 2.3%    |
| 4     | 1        | 1.15%   |
| 0     | 1        | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 73.56%  |
| Yes  | 23       | 26.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 35%     |
| Cambridge Silicon Radio         | 4        | 20%     |
| MediaTek                        | 2        | 10%     |
| Foxconn / Hon Hai               | 2        | 10%     |
| TP-Link                         | 1        | 5%      |
| Realtek Semiconductor           | 1        | 5%      |
| Qualcomm Atheros Communications | 1        | 5%      |
| Logitech                        | 1        | 5%      |
| Broadcom                        | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 20%     |
| MediaTek Wireless_Device                            | 2        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 10%     |
| Intel Bluetooth wireless interface                  | 2        | 10%     |
| TP-Link UB500 Adapter                               | 1        | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 5%      |
| Logitech BT Mini-Receiver (HCI mode)                | 1        | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 5%      |
| Intel AX210 Bluetooth                               | 1        | 5%      |
| Intel AX200 Bluetooth                               | 1        | 5%      |
| Foxconn / Hon Hai Wireless_Device                   | 1        | 5%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1        | 5%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 47       | 36.72%  |
| AMD                                          | 36       | 28.13%  |
| Nvidia                                       | 26       | 20.31%  |
| C-Media Electronics                          | 4        | 3.13%   |
| VIA Technologies                             | 3        | 2.34%   |
| ASUSTek Computer                             | 2        | 1.56%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.78%   |
| Texas Instruments                            | 1        | 0.78%   |
| Sony                                         | 1        | 0.78%   |
| Razer USA                                    | 1        | 0.78%   |
| Plantronics                                  | 1        | 0.78%   |
| Micro Star International                     | 1        | 0.78%   |
| GN Netcom                                    | 1        | 0.78%   |
| Focusrite-Novation                           | 1        | 0.78%   |
| Ensoniq                                      | 1        | 0.78%   |
| Creative Labs                                | 1        | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 16       | 10.67%  |
| Nvidia High Definition Audio Controller                                           | 7        | 4.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 3.33%   |
| AMD FCH Azalia Controller                                                         | 5        | 3.33%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 2%      |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 2%      |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                              | 3        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 2%      |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 1.33%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.33%   |
| Nvidia GK106 HDMI Audio Controller                                                | 2        | 1.33%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 2        | 1.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 2        | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 2        | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 1.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 2        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 1.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 2        | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 1.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.33%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1        | 0.67%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                    | 1        | 0.67%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1        | 0.67%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 1        | 0.67%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 21.67%  |
| Micron Technology   | 7        | 11.67%  |
| SK hynix            | 6        | 10%     |
| Kingston            | 6        | 10%     |
| Corsair             | 6        | 10%     |
| G.Skill             | 5        | 8.33%   |
| Samsung Electronics | 4        | 6.67%   |
| Unknown             | 4        | 6.67%   |
| Patriot             | 2        | 3.33%   |
| Crucial             | 2        | 3.33%   |
| Unknown (ABCD)      | 1        | 1.67%   |
| Nanya Technology    | 1        | 1.67%   |
| GOODRAM             | 1        | 1.67%   |
| Elpida              | 1        | 1.67%   |
| A-DATA Technology   | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 4        | 6.06%   |
| Unknown RAM Module 2GB DIMM SDRAM                                 | 2        | 3.03%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 2        | 3.03%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                 | 2        | 3.03%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                              | 1        | 1.52%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                        | 1        | 1.52%   |
| Unknown RAM Module 4GB DIMM SDRAM                                 | 1        | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                          | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                          | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM                                       | 1        | 1.52%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                          | 1        | 1.52%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s          | 1        | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1        | 1.52%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                        | 1        | 1.52%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 1.52%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                        | 1        | 1.52%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s              | 1        | 1.52%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 1.52%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 1.52%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1        | 1.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.52%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                   | 1        | 1.52%   |
| Samsung RAM M391B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 1        | 1.52%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2667MT/s               | 1        | 1.52%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 2800MT/s                   | 1        | 1.52%   |
| Patriot RAM PSD22G80026 2GB DIMM DDR2 800MT/s                     | 1        | 1.52%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s                | 1        | 1.52%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                          | 1        | 1.52%   |
| Micron RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s            | 1        | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 1        | 1.52%   |
| Micron RAM 8HTF12864AY-800G1 1GB DIMM DDR2 800MT/s                | 1        | 1.52%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s                | 1        | 1.52%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s              | 1        | 1.52%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2400MT/s            | 1        | 1.52%   |
| Kingston RAM KN2M64-ETB 8GB DIMM DDR3 1600MT/s                    | 1        | 1.52%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s             | 1        | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 19       | 34.55%  |
| DDR3    | 18       | 32.73%  |
| DDR2    | 9        | 16.36%  |
| Unknown | 4        | 7.27%   |
| SDRAM   | 3        | 5.45%   |
| LPDDR4  | 1        | 1.82%   |
| DDR5    | 1        | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 45       | 83.33%  |
| SODIMM | 9        | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 17       | 28.81%  |
| 8192  | 16       | 27.12%  |
| 4096  | 14       | 23.73%  |
| 16384 | 7        | 11.86%  |
| 32768 | 3        | 5.08%   |
| 1024  | 2        | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 21.43%  |
| 3200    | 7        | 12.5%   |
| 1333    | 4        | 7.14%   |
| 800     | 4        | 7.14%   |
| 667     | 3        | 5.36%   |
| Unknown | 3        | 5.36%   |
| 3400    | 2        | 3.57%   |
| 2800    | 2        | 3.57%   |
| 2667    | 2        | 3.57%   |
| 2400    | 2        | 3.57%   |
| 2133    | 2        | 3.57%   |
| 1866    | 2        | 3.57%   |
| 1066    | 2        | 3.57%   |
| 4800    | 1        | 1.79%   |
| 3933    | 1        | 1.79%   |
| 3666    | 1        | 1.79%   |
| 3534    | 1        | 1.79%   |
| 3066    | 1        | 1.79%   |
| 2666    | 1        | 1.79%   |
| 2048    | 1        | 1.79%   |
| 533     | 1        | 1.79%   |
| 333     | 1        | 1.79%   |

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


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 3        | 30%     |
| WaveRider USB 2.0 Camera                 | 1        | 10%     |
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
| Cherry | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Cherry SmartCard Reader Keyboard KC 1000 SC | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 76       | 86.36%  |
| 1     | 10       | 11.36%  |
| 2     | 2        | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 6        | 42.86%  |
| Net/wireless             | 4        | 28.57%  |
| Unassigned class         | 1        | 7.14%   |
| Sound                    | 1        | 7.14%   |
| Net/ethernet             | 1        | 7.14%   |
| Communication controller | 1        | 7.14%   |

