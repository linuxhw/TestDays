MX - Tested Hardware & Statistics (Desktops)
--------------------------------------------

A project to collect tested hardware configurations for MX.

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

Total: 236

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | B350M MORTAR                | [6e5323aa42](https://linux-hardware.org/?probe=6e5323aa42) | Jun 09, 2023 |
| MSI           | B350M MORTAR                | [fc4b07cbb0](https://linux-hardware.org/?probe=fc4b07cbb0) | Jun 09, 2023 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | [c64fbbcad9](https://linux-hardware.org/?probe=c64fbbcad9) | Jun 02, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [7070e55aa0](https://linux-hardware.org/?probe=7070e55aa0) | Jun 01, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [5ae19394fc](https://linux-hardware.org/?probe=5ae19394fc) | May 20, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [14548bc77a](https://linux-hardware.org/?probe=14548bc77a) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming 9       | [5ca1acbf9b](https://linux-hardware.org/?probe=5ca1acbf9b) | May 19, 2023 |
| Unknown       | Unknown                     | [58066198c4](https://linux-hardware.org/?probe=58066198c4) | May 18, 2023 |
| Dell          | 06X1TJ A00                  | [d3107c9603](https://linux-hardware.org/?probe=d3107c9603) | May 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | [3bc96663a8](https://linux-hardware.org/?probe=3bc96663a8) | May 14, 2023 |
| Gigabyte      | X670 GAMING X AX            | [ebd2a32ce2](https://linux-hardware.org/?probe=ebd2a32ce2) | May 12, 2023 |
| Gigabyte      | X670 GAMING X AX            | [352c0902e9](https://linux-hardware.org/?probe=352c0902e9) | May 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [f894b9a2c4](https://linux-hardware.org/?probe=f894b9a2c4) | May 07, 2023 |
| ASRock        | P55 Extreme                 | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| ASRock        | N68-S UCC                   | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| Dell          | 0PC5F7 A02                  | [2d1086090c](https://linux-hardware.org/?probe=2d1086090c) | May 01, 2023 |
| ASUSTek       | Z97-P                       | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Gigabyte      | H61MA-D3V                   | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [4939e609de](https://linux-hardware.org/?probe=4939e609de) | Apr 24, 2023 |
| HP            | 090Ch                       | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| ASRock        | Z690 Pro RS                 | [acb9cde3d7](https://linux-hardware.org/?probe=acb9cde3d7) | Apr 23, 2023 |
| Gateway       | DX4860                      | [5583641f1b](https://linux-hardware.org/?probe=5583641f1b) | Apr 22, 2023 |
| ASUSTek       | GRYPHON Z87                 | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| HP            | 3646h                       | [c36653d824](https://linux-hardware.org/?probe=c36653d824) | Apr 12, 2023 |
| HP            | 18E5                        | [441d2678ff](https://linux-hardware.org/?probe=441d2678ff) | Apr 07, 2023 |
| ASUSTek       | P8P67 LE                    | [aea33c89a1](https://linux-hardware.org/?probe=aea33c89a1) | Apr 05, 2023 |
| ASUSTek       | Z97-P                       | [86d8d7f80f](https://linux-hardware.org/?probe=86d8d7f80f) | Apr 05, 2023 |
| HP            | 3029h                       | [153b913406](https://linux-hardware.org/?probe=153b913406) | Mar 27, 2023 |
| Unknown       | GB01                        | [ad0e76307c](https://linux-hardware.org/?probe=ad0e76307c) | Mar 24, 2023 |
| MSI           | B360M PRO-VH                | [2706ed39b7](https://linux-hardware.org/?probe=2706ed39b7) | Mar 23, 2023 |
| HP            | 3048h                       | [cd326ce9fa](https://linux-hardware.org/?probe=cd326ce9fa) | Mar 22, 2023 |
| ASRock        | AB350 Pro4                  | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| Shenzhen M... | F6BFC                       | [46cb84be25](https://linux-hardware.org/?probe=46cb84be25) | Mar 14, 2023 |
| MSI           | CSM-H87M-G43                | [9df13e200e](https://linux-hardware.org/?probe=9df13e200e) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| Gigabyte      | PH67A-D3-B3                 | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| HP            | 8184 X4                     | [b42f6862c7](https://linux-hardware.org/?probe=b42f6862c7) | Mar 04, 2023 |
| Unknown       | 1.0                         | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| Dell          | 0D441T A03                  | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| ASUSTek       | Z97M-PLUS                   | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [42e242e6bf](https://linux-hardware.org/?probe=42e242e6bf) | Feb 04, 2023 |
| Unknown       | Unknown                     | [793f52c99a](https://linux-hardware.org/?probe=793f52c99a) | Feb 03, 2023 |
| ECS           | P4M800PRO-M                 | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| Intel         | D34010WYK H14771-303        | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Gigabyte      | Z77X-D3H                    | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| Dell          | 0PC5F7 A02                  | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| HP            | 3396                        | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| ASRock        | X370 Taichi                 | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| ASUSTek       | H81M-E                      | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Dell          | 0D881F A06                  | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0HY9JP A02                  | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| ASRock        | B365M Pro4                  | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASRock        | H81M-HG4 R4.0               | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASRock        | H370M-ITX/ac                | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| Pegatron      | NARRA3                      | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [bb43eb5333](https://linux-hardware.org/?probe=bb43eb5333) | Oct 04, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | 1632                        | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| ASRock        | H370M-ITX/ac                | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| Gigabyte      | B560M DS3H V2               | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Biostar       | A780L3B                     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| Intel         | DH55TC AAE70932-303         | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP            | MS-7848                     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen         | D1009 A1A4                  | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | 0DR845                      | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI           | B350 TOMAHAWK               | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte      | H410M S2H V3                | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek       | SABERTOOTH X99              | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel         | V1.3                        | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek       | SABERTOOTH X99              | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| ASUSTek       | M4A785-M                    | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Gigabyte      | B550M S2H                   | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Gigabyte      | P35-DS3P                    | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 3647h                       | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-A               | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI           | Z97 GAMING 5                | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| Intel         | H81                         | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| IBM           | 8183B2U                     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| HP            | 0B4Ch D                     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Gigabyte      | F2A88X-UP4                  | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX         | B550M                       | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| ECS           | A55F-M3                     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| MSI           | B460M PRO                   | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | Maximus VII HERO            | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Gigabyte      | B550M DS3H                  | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Dell          | 00F82W A01                  | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| Dell          | 0P611C A00                  | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| HP            | 21D0                        | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| GreatWall     | U320                        | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Dell          | 0M017G A00                  | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Intel         | Unknown                     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| Dell          | 0P611C A00                  | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| ASUSTek       | X79-DELUXE                  | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| ASRock        | H170M Pro4                  | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Gigabyte      | H110M-S2H-CF                | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Dell          | 00F82W A01                  | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| MSI           | B450-A PRO MAX              | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| ASRock        | B560M Pro4                  | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | P5K-E                       | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | 0XR1GT A00                  | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | B350 TOMAHAWK               | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| MSI           | MS-7210 100                 | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| ASRock        | H81M-ITX                    | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| ASRock        | K8A780LM                    | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Intel         | MAHOBAY                     | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                     | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | [6a65eeffd1](https://linux-hardware.org/?probe=6a65eeffd1) | Nov 27, 2020 |
| HP            | 1905                        | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| ASRock        | H110M-ITX                   | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| ASUSTek       | PRIME B450M-A               | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| MSI           | Z87 MPOWER MAX              | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Dell          | 0D28YY A00                  | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Dell          | 0M9KCM A02                  | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 8265                        | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Dell          | 0M5DCD A00                  | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| MSI           | 970A-G43                    | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Gigabyte      | P55-USB3                    | [901dfafdbf](https://linux-hardware.org/?probe=901dfafdbf) | May 21, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Intel         | DCP847SKE G80890-105        | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| ASUSTek       | P8Z77-V LX                  | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | Z97-E                       | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [67d9f2023b](https://linux-hardware.org/?probe=67d9f2023b) | Apr 01, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| ASRock        | Z68 Pro3-M                  | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| HP            | 1790                        | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| ASUSTek       | M4A77T                      | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| ASUSTek       | PRIME H310M-K               | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| ASRock        | K8A780LM                    | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Gigabyte      | GA-880GA-UD3H               | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X               | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                      | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| Dell          | 088DT1 A01                  | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| MSI           | MS-7199                     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| MSI           | B75MA-E33                   | [a08cc9782c](https://linux-hardware.org/?probe=a08cc9782c) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| ASRock        | H81M-ITX                    | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| Dell          | 0F8096                      | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| ASUSTek       | SABERTOOTH X79              | [13dbc6f66d](https://linux-hardware.org/?probe=13dbc6f66d) | Oct 06, 2019 |
| ASUSTek       | Z97-A                       | [6a9aa2dd84](https://linux-hardware.org/?probe=6a9aa2dd84) | Jul 22, 2019 |
| Gigabyte      | EP45-UD3LR                  | [e42fd626b2](https://linux-hardware.org/?probe=e42fd626b2) | Apr 23, 2019 |
| Gigabyte      | EP45-UD3LR                  | [8469904453](https://linux-hardware.org/?probe=8469904453) | Apr 17, 2019 |
| Gigabyte      | Z370 AORUS Gaming 7         | [c68bd6bce7](https://linux-hardware.org/?probe=c68bd6bce7) | Feb 23, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| MX 21          | 104      | 55.32%  |
| MX 19          | 46       | 24.47%  |
| MX 20          | 22       | 11.7%   |
| MX 18          | 12       | 6.38%   |
| MX 23          | 1        | 0.53%   |
| MX 22          | 1        | 0.53%   |
| MX 17          | 1        | 0.53%   |
| MX 16-migrated | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 187      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 4.19.0-6-amd64            | 20       | 10.05%  |
| 5.10.0-21-amd64           | 15       | 7.54%   |
| 5.10.0-20-amd64           | 12       | 6.03%   |
| 6.0.0-6mx-amd64           | 6        | 3.02%   |
| 5.6.0-2-amd64             | 6        | 3.02%   |
| 5.14.0-4mx-amd64          | 6        | 3.02%   |
| 5.10.0-5mx-amd64          | 6        | 3.02%   |
| 5.10.0-19-amd64           | 6        | 3.02%   |
| 5.10.0-18-amd64           | 6        | 3.02%   |
| 5.18.0-4mx-amd64          | 5        | 2.51%   |
| 5.10.0-13-amd64           | 5        | 2.51%   |
| 4.19.0-17-amd64           | 5        | 2.51%   |
| 5.8.0-3-amd64             | 4        | 2.01%   |
| 5.10.0-16-amd64           | 4        | 2.01%   |
| 5.10.0-15-amd64           | 4        | 2.01%   |
| 4.19.0-14-amd64           | 4        | 2.01%   |
| 5.4.0-3-amd64             | 3        | 1.51%   |
| 5.16.0-5mx-amd64          | 3        | 1.51%   |
| 5.10.0-23-amd64           | 3        | 1.51%   |
| 4.19.0-5-amd64            | 3        | 1.51%   |
| 4.19.0-18-amd64           | 3        | 1.51%   |
| 4.19.0-13-amd64           | 3        | 1.51%   |
| 4.19.0-1-amd64            | 3        | 1.51%   |
| 6.0.0-10.1-liquorix-amd64 | 2        | 1.01%   |
| 5.8.16-antix.1-amd64-smp  | 2        | 1.01%   |
| 5.14.0-3mx-amd64          | 2        | 1.01%   |
| 5.10.0-9-amd64            | 2        | 1.01%   |
| 5.10.0-11-amd64           | 2        | 1.01%   |
| 4.19.0-16-amd64           | 2        | 1.01%   |
| 4.19.0-12-amd64           | 2        | 1.01%   |
| 6.2.14-1-liquorix-amd64   | 1        | 0.5%    |
| 6.1.15-2-liquorix-amd64   | 1        | 0.5%    |
| 6.1.0-2mx-amd64           | 1        | 0.5%    |
| 6.0.5-x64v1-xanmod1       | 1        | 0.5%    |
| 6.0.0-4mx-rt-amd64        | 1        | 0.5%    |
| 6.0.0-13.3-liquorix-amd64 | 1        | 0.5%    |
| 5.5.0-9.1-liquorix-amd64  | 1        | 0.5%    |
| 5.5.0-7.1-liquorix-amd64  | 1        | 0.5%    |
| 5.5.0-5.1-liquorix-amd64  | 1        | 0.5%    |
| 5.5.0-10.2-liquorix-amd64 | 1        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 74       | 38.74%  |
| 4.19.0   | 45       | 23.56%  |
| 6.0.0    | 10       | 5.24%   |
| 5.14.0   | 9        | 4.71%   |
| 5.6.0    | 6        | 3.14%   |
| 5.5.0    | 5        | 2.62%   |
| 5.18.0   | 5        | 2.62%   |
| 5.16.0   | 5        | 2.62%   |
| 5.8.0    | 4        | 2.09%   |
| 5.4.0    | 3        | 1.57%   |
| 5.19.0   | 3        | 1.57%   |
| 5.15.0   | 3        | 1.57%   |
| 5.8.16   | 2        | 1.05%   |
| 5.3.0    | 2        | 1.05%   |
| 6.2.14   | 1        | 0.52%   |
| 6.1.15   | 1        | 0.52%   |
| 6.1.0    | 1        | 0.52%   |
| 6.0.5    | 1        | 0.52%   |
| 5.4.7    | 1        | 0.52%   |
| 5.4.10   | 1        | 0.52%   |
| 5.2.21   | 1        | 0.52%   |
| 5.17.0   | 1        | 0.52%   |
| 5.11.0   | 1        | 0.52%   |
| 5.10.52  | 1        | 0.52%   |
| 5.10.113 | 1        | 0.52%   |
| 5.10.111 | 1        | 0.52%   |
| 4.9.91   | 1        | 0.52%   |
| 4.18.0   | 1        | 0.52%   |
| 4.15.0   | 1        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 77       | 40.31%  |
| 4.19    | 45       | 23.56%  |
| 6.0     | 11       | 5.76%   |
| 5.14    | 9        | 4.71%   |
| 5.8     | 6        | 3.14%   |
| 5.6     | 6        | 3.14%   |
| 5.5     | 5        | 2.62%   |
| 5.4     | 5        | 2.62%   |
| 5.18    | 5        | 2.62%   |
| 5.16    | 5        | 2.62%   |
| 5.19    | 3        | 1.57%   |
| 5.15    | 3        | 1.57%   |
| 6.1     | 2        | 1.05%   |
| 5.3     | 2        | 1.05%   |
| 6.2     | 1        | 0.52%   |
| 5.2     | 1        | 0.52%   |
| 5.17    | 1        | 0.52%   |
| 5.11    | 1        | 0.52%   |
| 4.9     | 1        | 0.52%   |
| 4.18    | 1        | 0.52%   |
| 4.15    | 1        | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 180      | 96.26%  |
| i686   | 7        | 3.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 145      | 77.54%  |
| KDE5             | 33       | 17.65%  |
| MATE             | 2        | 1.07%   |
| lightdm-xsession | 2        | 1.07%   |
| X-Cinnamon       | 1        | 0.53%   |
| LXQt             | 1        | 0.53%   |
| KDE4             | 1        | 0.53%   |
| KDE              | 1        | 0.53%   |
| Unknown          | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 186      | 99.47%  |
| Tty  | 1        | 0.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 153      | 81.82%  |
| SDDM    | 28       | 14.97%  |
| SLiM    | 3        | 1.6%    |
| TDM     | 2        | 1.07%   |
| GDM     | 1        | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 69       | 35.94%  |
| Unknown | 34       | 17.71%  |
| de_DE   | 19       | 9.9%    |
| en_GB   | 8        | 4.17%   |
| pl_PL   | 7        | 3.65%   |
| it_IT   | 7        | 3.65%   |
| es_ES   | 7        | 3.65%   |
| sk_SK   | 5        | 2.6%    |
| ru_RU   | 5        | 2.6%    |
| pt_BR   | 5        | 2.6%    |
| fr_FR   | 3        | 1.56%   |
| es_AR   | 3        | 1.56%   |
| sv_SE   | 2        | 1.04%   |
| hu_HU   | 2        | 1.04%   |
| es_MX   | 2        | 1.04%   |
| en_CA   | 2        | 1.04%   |
| en_AU   | 2        | 1.04%   |
| de_CH   | 2        | 1.04%   |
| uk_UA   | 1        | 0.52%   |
| tr_TR   | 1        | 0.52%   |
| hr_HR   | 1        | 0.52%   |
| fi_FI   | 1        | 0.52%   |
| es_VE   | 1        | 0.52%   |
| es_CO   | 1        | 0.52%   |
| en_NZ   | 1        | 0.52%   |
| en_IE   | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 118      | 63.1%   |
| EFI  | 69       | 36.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 171      | 91.44%  |
| Overlay  | 10       | 5.35%   |
| Btrfs    | 3        | 1.6%    |
| Xfs      | 1        | 0.53%   |
| Reiserfs | 1        | 0.53%   |
| Ext3     | 1        | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 99       | 52.66%  |
| MBR     | 87       | 46.28%  |
| Unknown | 2        | 1.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 62.83%  |
| Yes       | 71       | 37.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 101      | 54.01%  |
| No        | 86       | 45.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 39       | 20.86%  |
| Gigabyte Technology                  | 30       | 16.04%  |
| MSI                                  | 23       | 12.3%   |
| Dell                                 | 20       | 10.7%   |
| ASRock                               | 20       | 10.7%   |
| Hewlett-Packard                      | 13       | 6.95%   |
| Intel                                | 7        | 3.74%   |
| Lenovo                               | 6        | 3.21%   |
| Unknown                              | 4        | 2.14%   |
| Pegatron                             | 2        | 1.07%   |
| Gateway                              | 2        | 1.07%   |
| Fujitsu                              | 2        | 1.07%   |
| ECS                                  | 2        | 1.07%   |
| Biostar                              | 2        | 1.07%   |
| ZOTAC                                | 1        | 0.53%   |
| SLIMBOOK                             | 1        | 0.53%   |
| SIRAGON                              | 1        | 0.53%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.53%   |
| Positivo                             | 1        | 0.53%   |
| MP                                   | 1        | 0.53%   |
| Medion                               | 1        | 0.53%   |
| IBM                                  | 1        | 0.53%   |
| Huanan                               | 1        | 0.53%   |
| GreatWall                            | 1        | 0.53%   |
| GALAX                                | 1        | 0.53%   |
| Fujitsu Siemens                      | 1        | 0.53%   |
| Foxconn                              | 1        | 0.53%   |
| BESSTAR Tech                         | 1        | 0.53%   |
| AOpen                                | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 9        | 4.81%   |
| Unknown                                    | 6        | 3.21%   |
| MSI MS-7C91                                | 2        | 1.07%   |
| MSI MS-7A34                                | 2        | 1.07%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.07%   |
| Dell Studio 540                            | 2        | 1.07%   |
| Dell OptiPlex 9020                         | 2        | 1.07%   |
| Dell OptiPlex 9010                         | 2        | 1.07%   |
| Dell OptiPlex 790                          | 2        | 1.07%   |
| Dell OptiPlex 755                          | 2        | 1.07%   |
| ASUS ROG Maximus XIII HERO                 | 2        | 1.07%   |
| ASUS PRIME B450M-A                         | 2        | 1.07%   |
| ASRock K8A780LM                            | 2        | 1.07%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.53%   |
| SIRAGON AIO-5150                           | 1        | 0.53%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.53%   |
| Positivo POS-PQ45AU                        | 1        | 0.53%   |
| Pegatron FQ425AA-ABA a6655f                | 1        | 0.53%   |
| Pegatron 2AD5                              | 1        | 0.53%   |
| MSI MS-7E12                                | 1        | 0.53%   |
| MSI MS-7C94                                | 1        | 0.53%   |
| MSI MS-7C88                                | 1        | 0.53%   |
| MSI MS-7C56                                | 1        | 0.53%   |
| MSI MS-7C37                                | 1        | 0.53%   |
| MSI MS-7B98                                | 1        | 0.53%   |
| MSI MS-7B86                                | 1        | 0.53%   |
| MSI MS-7B53                                | 1        | 0.53%   |
| MSI MS-7A63                                | 1        | 0.53%   |
| MSI MS-7A37                                | 1        | 0.53%   |
| MSI MS-7917                                | 1        | 0.53%   |
| MSI MS-7823                                | 1        | 0.53%   |
| MSI MS-7815                                | 1        | 0.53%   |
| MSI MS-7808                                | 1        | 0.53%   |
| MSI MS-7758                                | 1        | 0.53%   |
| MSI MS-7693                                | 1        | 0.53%   |
| MSI MS-7641                                | 1        | 0.53%   |
| MSI MS-7199                                | 1        | 0.53%   |
| MSI GEG                                    | 1        | 0.53%   |
| MP MS-7848                                 | 1        | 0.53%   |
| Medion Akoya P5330 E MD8876/2458           | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 14       | 7.49%   |
| ASUS All                                   | 9        | 4.81%   |
| Unknown                                    | 6        | 3.21%   |
| ASUS ROG                                   | 5        | 2.67%   |
| ASUS PRIME                                 | 5        | 2.67%   |
| HP Compaq                                  | 4        | 2.14%   |
| ASUS TUF                                   | 4        | 2.14%   |
| MSI MS-7C91                                | 2        | 1.07%   |
| MSI MS-7A34                                | 2        | 1.07%   |
| Lenovo ThinkCentre                         | 2        | 1.07%   |
| Gigabyte Z390                              | 2        | 1.07%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.07%   |
| Gigabyte B550M                             | 2        | 1.07%   |
| Dell Studio                                | 2        | 1.07%   |
| Dell Inspiron                              | 2        | 1.07%   |
| ASUS P5GC-MX                               | 2        | 1.07%   |
| ASRock X370                                | 2        | 1.07%   |
| ASRock K8A780LM                            | 2        | 1.07%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.53%   |
| SIRAGON AIO-5150                           | 1        | 0.53%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.53%   |
| Positivo POS-PQ45AU                        | 1        | 0.53%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.53%   |
| Pegatron 2AD5                              | 1        | 0.53%   |
| MSI MS-7E12                                | 1        | 0.53%   |
| MSI MS-7C94                                | 1        | 0.53%   |
| MSI MS-7C88                                | 1        | 0.53%   |
| MSI MS-7C56                                | 1        | 0.53%   |
| MSI MS-7C37                                | 1        | 0.53%   |
| MSI MS-7B98                                | 1        | 0.53%   |
| MSI MS-7B86                                | 1        | 0.53%   |
| MSI MS-7B53                                | 1        | 0.53%   |
| MSI MS-7A63                                | 1        | 0.53%   |
| MSI MS-7A37                                | 1        | 0.53%   |
| MSI MS-7917                                | 1        | 0.53%   |
| MSI MS-7823                                | 1        | 0.53%   |
| MSI MS-7815                                | 1        | 0.53%   |
| MSI MS-7808                                | 1        | 0.53%   |
| MSI MS-7758                                | 1        | 0.53%   |
| MSI MS-7693                                | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 18       | 9.63%   |
| 2018 | 16       | 8.56%   |
| 2012 | 15       | 8.02%   |
| 2011 | 15       | 8.02%   |
| 2020 | 14       | 7.49%   |
| 2014 | 12       | 6.42%   |
| 2021 | 11       | 5.88%   |
| 2010 | 11       | 5.88%   |
| 2022 | 10       | 5.35%   |
| 2019 | 10       | 5.35%   |
| 2009 | 10       | 5.35%   |
| 2008 | 9        | 4.81%   |
| 2017 | 8        | 4.28%   |
| 2016 | 8        | 4.28%   |
| 2007 | 8        | 4.28%   |
| 2015 | 5        | 2.67%   |
| 2006 | 3        | 1.6%    |
| 2005 | 2        | 1.07%   |
| 2023 | 1        | 0.53%   |
| 2004 | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 187      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 187      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 187      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 46       | 24.6%   |
| 16.01-24.0  | 45       | 24.06%  |
| 4.01-8.0    | 31       | 16.58%  |
| 32.01-64.0  | 25       | 13.37%  |
| 3.01-4.0    | 19       | 10.16%  |
| 24.01-32.0  | 7        | 3.74%   |
| 1.01-2.0    | 7        | 3.74%   |
| 64.01-256.0 | 3        | 1.6%    |
| 2.01-3.0    | 2        | 1.07%   |
| 0.51-1.0    | 2        | 1.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 71       | 36.79%  |
| 2.01-3.0   | 48       | 24.87%  |
| 3.01-4.0   | 29       | 15.03%  |
| 4.01-8.0   | 22       | 11.4%   |
| 0.51-1.0   | 14       | 7.25%   |
| 8.01-16.0  | 6        | 3.11%   |
| 0.01-0.5   | 2        | 1.04%   |
| 16.01-24.0 | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 65       | 33.85%  |
| 2      | 57       | 29.69%  |
| 3      | 37       | 19.27%  |
| 4      | 15       | 7.81%   |
| 5      | 11       | 5.73%   |
| 8      | 3        | 1.56%   |
| 9      | 1        | 0.52%   |
| 7      | 1        | 0.52%   |
| 6      | 1        | 0.52%   |
| 0      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 51.06%  |
| No        | 92       | 48.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 186      | 99.47%  |
| No        | 1        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 57.22%  |
| Yes       | 80       | 42.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 143      | 76.47%  |
| Yes       | 44       | 23.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 47       | 25.13%  |
| Germany                | 18       | 9.63%   |
| Spain                  | 9        | 4.81%   |
| Poland                 | 9        | 4.81%   |
| Italy                  | 9        | 4.81%   |
| Canada                 | 8        | 4.28%   |
| Slovakia               | 7        | 3.74%   |
| Russia                 | 7        | 3.74%   |
| UK                     | 6        | 3.21%   |
| France                 | 6        | 3.21%   |
| Brazil                 | 6        | 3.21%   |
| Australia              | 6        | 3.21%   |
| Sweden                 | 5        | 2.67%   |
| Finland                | 5        | 2.67%   |
| India                  | 4        | 2.14%   |
| Serbia                 | 3        | 1.6%    |
| Argentina              | 3        | 1.6%    |
| Venezuela              | 2        | 1.07%   |
| Switzerland            | 2        | 1.07%   |
| Netherlands            | 2        | 1.07%   |
| Mexico                 | 2        | 1.07%   |
| Indonesia              | 2        | 1.07%   |
| Hungary                | 2        | 1.07%   |
| Denmark                | 2        | 1.07%   |
| Ukraine                | 1        | 0.53%   |
| Turkey                 | 1        | 0.53%   |
| South Africa           | 1        | 0.53%   |
| Singapore              | 1        | 0.53%   |
| Romania                | 1        | 0.53%   |
| Philippines            | 1        | 0.53%   |
| New Zealand            | 1        | 0.53%   |
| Ireland                | 1        | 0.53%   |
| Greece                 | 1        | 0.53%   |
| French Guiana          | 1        | 0.53%   |
| Estonia                | 1        | 0.53%   |
| Croatia                | 1        | 0.53%   |
| Colombia               | 1        | 0.53%   |
| Bosnia and Herzegovina | 1        | 0.53%   |
| Austria                | 1        | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 3.68%   |
| Sydney                   | 3        | 1.58%   |
| Moscow                   | 3        | 1.58%   |
| Florianópolis           | 3        | 1.58%   |
| Berlin                   | 3        | 1.58%   |
| Barcelona                | 3        | 1.58%   |
| Toronto                  | 2        | 1.05%   |
| Mesquite                 | 2        | 1.05%   |
| Krakow                   | 2        | 1.05%   |
| Houston                  | 2        | 1.05%   |
| Ettingen                 | 2        | 1.05%   |
| Espoo                    | 2        | 1.05%   |
| Córdoba                 | 2        | 1.05%   |
| Centreville              | 2        | 1.05%   |
| Bengaluru                | 2        | 1.05%   |
| Belgrade                 | 2        | 1.05%   |
| Alma                     | 2        | 1.05%   |
| Albertslund Municipality | 2        | 1.05%   |
| Zagreb                   | 1        | 0.53%   |
| Yuzhno-Sakhalinsk        | 1        | 0.53%   |
| Warsaw                   | 1        | 0.53%   |
| Warren                   | 1        | 0.53%   |
| Volos                    | 1        | 0.53%   |
| Voghera                  | 1        | 0.53%   |
| Virginia Beach           | 1        | 0.53%   |
| Vilhelmina               | 1        | 0.53%   |
| Vienna                   | 1        | 0.53%   |
| Vera                     | 1        | 0.53%   |
| Vasco da Gama            | 1        | 0.53%   |
| Valencia                 | 1        | 0.53%   |
| Vaidasoo                 | 1        | 0.53%   |
| Tuglie                   | 1        | 0.53%   |
| Tlalnepantla             | 1        | 0.53%   |
| Titusville               | 1        | 0.53%   |
| Tilburg                  | 1        | 0.53%   |
| Tampere                  | 1        | 0.53%   |
| Tacoma                   | 1        | 0.53%   |
| Surrey                   | 1        | 0.53%   |
| Stockholm                | 1        | 0.53%   |
| Stevens Point            | 1        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 68       | 97     | 18.68%  |
| WDC                       | 67       | 84     | 18.41%  |
| Samsung Electronics       | 55       | 88     | 15.11%  |
| Kingston                  | 31       | 33     | 8.52%   |
| Toshiba                   | 18       | 23     | 4.95%   |
| SanDisk                   | 17       | 20     | 4.67%   |
| Hitachi                   | 17       | 22     | 4.67%   |
| Crucial                   | 13       | 14     | 3.57%   |
| China                     | 10       | 11     | 2.75%   |
| A-DATA Technology         | 9        | 9      | 2.47%   |
| Maxtor                    | 5        | 6      | 1.37%   |
| GOODRAM                   | 5        | 6      | 1.37%   |
| Unknown                   | 4        | 6      | 1.1%    |
| PNY                       | 4        | 5      | 1.1%    |
| Intel                     | 4        | 5      | 1.1%    |
| Corsair                   | 4        | 4      | 1.1%    |
| Mushkin                   | 3        | 3      | 0.82%   |
| Transcend                 | 2        | 2      | 0.55%   |
| SPCC                      | 2        | 2      | 0.55%   |
| Silicon Motion            | 2        | 2      | 0.55%   |
| Micron/Crucial Technology | 2        | 2      | 0.55%   |
| Apacer                    | 2        | 2      | 0.55%   |
| WDC WDS1                  | 1        | 1      | 0.27%   |
| Vaseky                    | 1        | 1      | 0.27%   |
| Team                      | 1        | 1      | 0.27%   |
| Rogueware                 | 1        | 2      | 0.27%   |
| Phison Electronics        | 1        | 1      | 0.27%   |
| Phison                    | 1        | 1      | 0.27%   |
| OCZ                       | 1        | 1      | 0.27%   |
| Micron Technology         | 1        | 1      | 0.27%   |
| KingSpec                  | 1        | 1      | 0.27%   |
| KingFast                  | 1        | 1      | 0.27%   |
| JMicron Technology        | 1        | 1      | 0.27%   |
| Intenso                   | 1        | 1      | 0.27%   |
| IBM/Hitachi               | 1        | 1      | 0.27%   |
| HGST                      | 1        | 1      | 0.27%   |
| Gigabyte Technology       | 1        | 1      | 0.27%   |
| Fujitsu                   | 1        | 1      | 0.27%   |
| External                  | 1        | 1      | 0.27%   |
| CT1000P3                  | 1        | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 7        | 1.65%   |
| Samsung SSD 860 EVO 500GB        | 6        | 1.42%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 1.18%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.18%   |
| Samsung SSD 970 EVO Plus 1TB     | 5        | 1.18%   |
| Samsung SSD 850 EVO 250GB        | 5        | 1.18%   |
| Kingston SV300S37A240G 240GB SSD | 5        | 1.18%   |
| Toshiba DT01ACA100 1TB           | 4        | 0.95%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 0.95%   |
| Seagate ST3500413AS 500GB        | 4        | 0.95%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 0.95%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 0.71%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.71%   |
| SanDisk NVMe SSD Drive 1TB       | 3        | 0.71%   |
| Samsung SSD 980 PRO 1TB          | 3        | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.71%   |
| Samsung SSD 870 EVO 500GB        | 3        | 0.71%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.71%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.71%   |
| Samsung SSD 850 EVO 1TB          | 3        | 0.71%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.71%   |
| Kingston SV300S37A120G 120GB SSD | 3        | 0.71%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.71%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 2        | 0.47%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.47%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.47%   |
| WDC WD3200AAKS-75B3A0 320GB      | 2        | 0.47%   |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.47%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.47%   |
| WDC WD15EARX-00PASB0 1TB         | 2        | 0.47%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 2        | 0.47%   |
| WDC WD10EZEX-75WN4A0 1TB         | 2        | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.47%   |
| Unknown SD/MMC 2GB               | 2        | 0.47%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 0.47%   |
| Toshiba MK5065GSX 500GB          | 2        | 0.47%   |
| Toshiba HDWD110 1TB              | 2        | 0.47%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 0.47%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 68       | 96     | 38.64%  |
| WDC                 | 57       | 73     | 32.39%  |
| Toshiba             | 18       | 23     | 10.23%  |
| Hitachi             | 17       | 22     | 9.66%   |
| Samsung Electronics | 6        | 7      | 3.41%   |
| Maxtor              | 5        | 6      | 2.84%   |
| Unknown             | 1        | 1      | 0.57%   |
| IBM/Hitachi         | 1        | 1      | 0.57%   |
| HGST                | 1        | 1      | 0.57%   |
| Fujitsu             | 1        | 1      | 0.57%   |
| External            | 1        | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 39       | 51     | 26.53%  |
| Kingston            | 26       | 28     | 17.69%  |
| SanDisk             | 13       | 15     | 8.84%   |
| Crucial             | 12       | 13     | 8.16%   |
| China               | 10       | 11     | 6.8%    |
| WDC                 | 8        | 9      | 5.44%   |
| A-DATA Technology   | 8        | 8      | 5.44%   |
| GOODRAM             | 5        | 6      | 3.4%    |
| PNY                 | 3        | 3      | 2.04%   |
| Intel               | 3        | 4      | 2.04%   |
| Transcend           | 2        | 2      | 1.36%   |
| SPCC                | 2        | 2      | 1.36%   |
| Mushkin             | 2        | 2      | 1.36%   |
| WDC WDS1            | 1        | 1      | 0.68%   |
| Vaseky              | 1        | 1      | 0.68%   |
| Team                | 1        | 1      | 0.68%   |
| Rogueware           | 1        | 2      | 0.68%   |
| OCZ                 | 1        | 1      | 0.68%   |
| Micron Technology   | 1        | 1      | 0.68%   |
| KingSpec            | 1        | 1      | 0.68%   |
| KingFast            | 1        | 1      | 0.68%   |
| Intenso             | 1        | 1      | 0.68%   |
| Gigabyte Technology | 1        | 1      | 0.68%   |
| CT1000P3            | 1        | 1      | 0.68%   |
| Avant               | 1        | 1      | 0.68%   |
| Apacer              | 1        | 1      | 0.68%   |
| Acer                | 1        | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 132      | 232    | 43.71%  |
| SSD     | 120      | 169    | 39.74%  |
| NVMe    | 45       | 59     | 14.9%   |
| Unknown | 4        | 6      | 1.32%   |
| MMC     | 1        | 1      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 173      | 391    | 75.22%  |
| NVMe | 45       | 59     | 19.57%  |
| SAS  | 11       | 16     | 4.78%   |
| MMC  | 1        | 1      | 0.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 140      | 223    | 51.47%  |
| 0.51-1.0   | 76       | 102    | 27.94%  |
| 1.01-2.0   | 28       | 36     | 10.29%  |
| 2.01-3.0   | 10       | 12     | 3.68%   |
| 3.01-4.0   | 9        | 10     | 3.31%   |
| 4.01-10.0  | 8        | 17     | 2.94%   |
| 10.01-20.0 | 1        | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 41       | 21.24%  |
| 251-500        | 40       | 20.73%  |
| 1001-2000      | 26       | 13.47%  |
| 501-1000       | 26       | 13.47%  |
| More than 3000 | 18       | 9.33%   |
| 51-100         | 16       | 8.29%   |
| 2001-3000      | 15       | 7.77%   |
| 21-50          | 6        | 3.11%   |
| 1-20           | 5        | 2.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 49       | 25.79%  |
| 101-250        | 30       | 15.79%  |
| 21-50          | 27       | 14.21%  |
| 251-500        | 24       | 12.63%  |
| 51-100         | 18       | 9.47%   |
| 501-1000       | 15       | 7.89%   |
| 1001-2000      | 14       | 7.37%   |
| More than 3000 | 7        | 3.68%   |
| 2001-3000      | 6        | 3.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| China SSD 512GB                       | 2        | 2      | 3.08%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1        | 1      | 1.54%   |
| WDC WD5003ABYX-01WERA1 500GB          | 1        | 1      | 1.54%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 1.54%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1        | 1      | 1.54%   |
| WDC WD2500AAJS-00B4A0 250GB           | 1        | 1      | 1.54%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 1.54%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 1.54%   |
| WDC WD1600AVVS-63L2B0 160GB           | 1        | 1      | 1.54%   |
| WDC WD15EADS-11P8B2 1TB               | 1        | 1      | 1.54%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1        | 1      | 1.54%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1        | 1      | 1.54%   |
| WDC WD10EAVS-00D7B1 1TB               | 1        | 1      | 1.54%   |
| WDC WD10EADS-98M2B0 1TB               | 1        | 1      | 1.54%   |
| WDC WD10EADS-00M2B0 1TB               | 1        | 1      | 1.54%   |
| Toshiba MQ01ABF050 500GB              | 1        | 1      | 1.54%   |
| Toshiba MK7575GSX 752GB               | 1        | 1      | 1.54%   |
| Toshiba MK6465GSX 640GB               | 1        | 1      | 1.54%   |
| SPCC Solid State Disk 512GB           | 1        | 1      | 1.54%   |
| Seagate ST500LT012-9WS142 500GB       | 1        | 1      | 1.54%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 1      | 1.54%   |
| Seagate ST380815AS 80GB               | 1        | 1      | 1.54%   |
| Seagate ST3750330NS 752GB             | 1        | 1      | 1.54%   |
| Seagate ST3500820AS 500GB             | 1        | 1      | 1.54%   |
| Seagate ST3500413AS 500GB             | 1        | 1      | 1.54%   |
| Seagate ST3360320AS 360GB             | 1        | 1      | 1.54%   |
| Seagate ST3320418AS 320GB             | 1        | 1      | 1.54%   |
| Seagate ST3320413CS 320GB             | 1        | 1      | 1.54%   |
| Seagate ST33000651NS 3TB              | 1        | 1      | 1.54%   |
| Seagate ST320LT020-9YG142 320GB       | 1        | 1      | 1.54%   |
| Seagate ST320LT012-1DG14C 320GB       | 1        | 2      | 1.54%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 1.54%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 1.54%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 1.54%   |
| Seagate ST2000DM001-1ER164 2TB        | 1        | 1      | 1.54%   |
| Seagate ST1000VM002-1CT162 1TB        | 1        | 1      | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1      | 1.54%   |
| Seagate ST1000DM003-9YN162 1TB        | 1        | 1      | 1.54%   |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 2      | 1.54%   |
| Samsung Electronics SSD 850 EVO 500GB | 1        | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 28.57%  |
| WDC                 | 14       | 14     | 22.22%  |
| Samsung Electronics | 5        | 8      | 7.94%   |
| Hitachi             | 5        | 6      | 7.94%   |
| Maxtor              | 4        | 4      | 6.35%   |
| Toshiba             | 3        | 3      | 4.76%   |
| Kingston            | 2        | 2      | 3.17%   |
| Crucial             | 2        | 2      | 3.17%   |
| China               | 2        | 2      | 3.17%   |
| SPCC                | 1        | 1      | 1.59%   |
| KingSpec            | 1        | 1      | 1.59%   |
| Intenso             | 1        | 1      | 1.59%   |
| IBM/Hitachi         | 1        | 1      | 1.59%   |
| HGST                | 1        | 1      | 1.59%   |
| GOODRAM             | 1        | 1      | 1.59%   |
| Fujitsu             | 1        | 1      | 1.59%   |
| A-DATA Technology   | 1        | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 20     | 38.3%   |
| WDC                 | 13       | 13     | 27.66%  |
| Hitachi             | 5        | 6      | 10.64%  |
| Maxtor              | 4        | 4      | 8.51%   |
| Toshiba             | 3        | 3      | 6.38%   |
| Samsung Electronics | 1        | 2      | 2.13%   |
| IBM/Hitachi         | 1        | 1      | 2.13%   |
| HGST                | 1        | 1      | 2.13%   |
| Fujitsu             | 1        | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 44       | 51     | 74.58%  |
| SSD  | 15       | 18     | 25.42%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2        | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 2        | 2      | 66.67%  |
| Seagate | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 163      | 365    | 67.36%  |
| Malfunc  | 56       | 69     | 23.14%  |
| Detected | 20       | 29     | 8.26%   |
| Failed   | 3        | 4      | 1.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 121      | 45.66%  |
| AMD                         | 56       | 21.13%  |
| Samsung Electronics         | 21       | 7.92%   |
| ASMedia Technology          | 13       | 4.91%   |
| Phison Electronics          | 8        | 3.02%   |
| Marvell Technology Group    | 8        | 3.02%   |
| JMicron Technology          | 8        | 3.02%   |
| SanDisk                     | 6        | 2.26%   |
| Kingston Technology Company | 5        | 1.89%   |
| Nvidia                      | 4        | 1.51%   |
| VIA Technologies            | 3        | 1.13%   |
| Silicon Motion              | 3        | 1.13%   |
| Micron/Crucial Technology   | 3        | 1.13%   |
| ULi Electronics             | 2        | 0.75%   |
| Silicon Image               | 1        | 0.38%   |
| MAXIO Technology (Hangzhou) | 1        | 0.38%   |
| LSI Logic / Symbios Logic   | 1        | 0.38%   |
| ADATA Technology            | 1        | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 7.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14       | 4.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 3.55%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 2.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.37%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 2.07%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.78%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.48%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.48%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.48%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5        | 1.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 1.48%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.18%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.18%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.18%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.18%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.18%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 3        | 0.89%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.89%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.89%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.89%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 0.89%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.89%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 152      | 58.02%  |
| IDE  | 54       | 20.61%  |
| NVMe | 45       | 17.18%  |
| RAID | 10       | 3.82%   |
| SCSI | 1        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 125      | 66.84%  |
| AMD          | 61       | 32.62%  |
| CentaurHauls | 1        | 0.53%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 2.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 2.67%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.14%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 4        | 2.14%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 3        | 1.6%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 1.6%    |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 1.6%    |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 1.07%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.07%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 1.07%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.07%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.07%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.07%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.07%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.07%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.07%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.07%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.07%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 1.07%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.07%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.07%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.07%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.07%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.07%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.07%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.07%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.07%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.07%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.07%   |
| AMD Phenom II X6 1090T Processor            | 2        | 1.07%   |
| AMD Phenom II X4 925 Processor              | 2        | 1.07%   |
| AMD Athlon II X4 630 Processor              | 2        | 1.07%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 0.53%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.53%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.53%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.53%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.53%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.53%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 18.72%  |
| Intel Core i7           | 24       | 12.83%  |
| AMD Ryzen 5             | 18       | 9.63%   |
| Intel Core i3           | 14       | 7.49%   |
| AMD Ryzen 7             | 12       | 6.42%   |
| Intel Core 2 Duo        | 10       | 5.35%   |
| Other                   | 7        | 3.74%   |
| Intel Xeon              | 5        | 2.67%   |
| Intel Core 2 Quad       | 5        | 2.67%   |
| Intel Celeron           | 5        | 2.67%   |
| Intel Pentium 4         | 4        | 2.14%   |
| Intel Pentium           | 4        | 2.14%   |
| AMD Phenom II X4        | 4        | 2.14%   |
| Intel Core i9           | 3        | 1.6%    |
| AMD Athlon II X4        | 3        | 1.6%    |
| AMD Athlon II X2        | 3        | 1.6%    |
| Intel Pentium Dual-Core | 2        | 1.07%   |
| AMD Sempron             | 2        | 1.07%   |
| AMD Ryzen 9             | 2        | 1.07%   |
| AMD Ryzen 3             | 2        | 1.07%   |
| AMD Phenom II X6        | 2        | 1.07%   |
| AMD Phenom              | 2        | 1.07%   |
| AMD FX                  | 2        | 1.07%   |
| AMD Athlon              | 2        | 1.07%   |
| Intel Pentium Gold      | 1        | 0.53%   |
| Intel Pentium Dual      | 1        | 0.53%   |
| Intel Pentium D         | 1        | 0.53%   |
| Intel Core M            | 1        | 0.53%   |
| Intel Core 2 Extreme    | 1        | 0.53%   |
| Intel Celeron D         | 1        | 0.53%   |
| Intel Atom              | 1        | 0.53%   |
| CentaurHauls VIA Esther | 1        | 0.53%   |
| AMD Ryzen Threadripper  | 1        | 0.53%   |
| AMD Ryzen 5 PRO         | 1        | 0.53%   |
| AMD E1                  | 1        | 0.53%   |
| AMD Athlon X4           | 1        | 0.53%   |
| AMD Athlon 64 X2        | 1        | 0.53%   |
| AMD A4                  | 1        | 0.53%   |
| AMD A10                 | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 73       | 39.04%  |
| 2      | 49       | 26.2%   |
| 6      | 26       | 13.9%   |
| 8      | 21       | 11.23%  |
| 1      | 9        | 4.81%   |
| 12     | 5        | 2.67%   |
| 10     | 2        | 1.07%   |
| 16     | 1        | 0.53%   |
| 3      | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 186      | 99.47%  |
| 2      | 1        | 0.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 50.27%  |
| 2      | 93       | 49.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 184      | 98.4%   |
| 32-bit         | 3        | 1.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 11.23%  |
| 0x306c3    | 20       | 10.7%   |
| 0x206a7    | 14       | 7.49%   |
| 0x306a9    | 11       | 5.88%   |
| 0x1067a    | 9        | 4.81%   |
| 0x08701021 | 7        | 3.74%   |
| 0x906ed    | 6        | 3.21%   |
| 0x0800820d | 6        | 3.21%   |
| 0xa0653    | 4        | 2.14%   |
| 0x506e3    | 4        | 2.14%   |
| 0x106e5    | 4        | 2.14%   |
| 0x010000db | 4        | 2.14%   |
| 0x010000c8 | 4        | 2.14%   |
| 0xa0671    | 3        | 1.6%    |
| 0x08108109 | 3        | 1.6%    |
| 0x08001138 | 3        | 1.6%    |
| 0x01000083 | 3        | 1.6%    |
| 0x906ea    | 2        | 1.07%   |
| 0x6fd      | 2        | 1.07%   |
| 0x6fb      | 2        | 1.07%   |
| 0x306f2    | 2        | 1.07%   |
| 0x20655    | 2        | 1.07%   |
| 0x10677    | 2        | 1.07%   |
| 0x0a601203 | 2        | 1.07%   |
| 0x0a20120a | 2        | 1.07%   |
| 0x08600106 | 2        | 1.07%   |
| 0x08001137 | 2        | 1.07%   |
| 0xf65      | 1        | 0.53%   |
| 0xf64      | 1        | 0.53%   |
| 0xf4a      | 1        | 0.53%   |
| 0xf49      | 1        | 0.53%   |
| 0xf34      | 1        | 0.53%   |
| 0xf29      | 1        | 0.53%   |
| 0xb0671    | 1        | 0.53%   |
| 0xa0655    | 1        | 0.53%   |
| 0x906eb    | 1        | 0.53%   |
| 0x906e9    | 1        | 0.53%   |
| 0x906a4    | 1        | 0.53%   |
| 0x90672    | 1        | 0.53%   |
| 0x706a8    | 1        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 26       | 13.9%   |
| SandyBridge      | 16       | 8.56%   |
| Penryn           | 15       | 8.02%   |
| K10              | 15       | 8.02%   |
| IvyBridge        | 13       | 6.95%   |
| KabyLake         | 12       | 6.42%   |
| Zen+             | 10       | 5.35%   |
| Zen 2            | 10       | 5.35%   |
| Zen              | 8        | 4.28%   |
| Unknown          | 8        | 4.28%   |
| Zen 3            | 6        | 3.21%   |
| Skylake          | 6        | 3.21%   |
| NetBurst         | 6        | 3.21%   |
| Nehalem          | 6        | 3.21%   |
| CometLake        | 5        | 2.67%   |
| Core             | 4        | 2.14%   |
| Westmere         | 3        | 1.6%    |
| K8 Hammer        | 3        | 1.6%    |
| Icelake          | 2        | 1.07%   |
| Goldmont plus    | 2        | 1.07%   |
| Steamroller      | 1        | 0.53%   |
| Silvermont       | 1        | 0.53%   |
| Piledriver       | 1        | 0.53%   |
| K10 Llano        | 1        | 0.53%   |
| Jaguar           | 1        | 0.53%   |
| Goldmont         | 1        | 0.53%   |
| Excavator        | 1        | 0.53%   |
| Bulldozer        | 1        | 0.53%   |
| Broadwell        | 1        | 0.53%   |
| Bonnell          | 1        | 0.53%   |
| Alderlake Hybrid | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 79       | 38.16%  |
| AMD              | 64       | 30.92%  |
| Intel            | 63       | 30.43%  |
| VIA Technologies | 1        | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 4.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 3.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 3.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 1.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.88%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.41%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.41%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                           | 3        | 1.41%   |
| AMD Raphael                                                                 | 3        | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.41%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 1.41%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.41%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.41%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.41%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.94%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 0.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.94%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 2        | 0.94%   |
| Nvidia GK107GL [Quadro K600]                                                | 2        | 0.94%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.94%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.94%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.94%   |
| Intel HD Graphics 530                                                       | 2        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 0.94%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 0.94%   |
| Intel 82865G Integrated Graphics Controller                                 | 2        | 0.94%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                   | 2        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 74       | 38.74%  |
| 1 x AMD        | 57       | 29.84%  |
| 1 x Intel      | 49       | 25.65%  |
| AMD + Nvidia   | 4        | 2.09%   |
| Intel + AMD    | 3        | 1.57%   |
| 3 x AMD        | 1        | 0.52%   |
| 2 x AMD        | 1        | 0.52%   |
| 1 x VIA        | 1        | 0.52%   |
| Intel + Nvidia | 1        | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 131      | 69.68%  |
| Proprietary | 50       | 26.6%   |
| Unknown     | 7        | 3.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 63       | 32.98%  |
| 1.01-2.0   | 33       | 17.28%  |
| 0.51-1.0   | 26       | 13.61%  |
| 3.01-4.0   | 21       | 10.99%  |
| 0.01-0.5   | 18       | 9.42%   |
| 7.01-8.0   | 17       | 8.9%    |
| 8.01-16.0  | 6        | 3.14%   |
| 5.01-6.0   | 4        | 2.09%   |
| 2.01-3.0   | 3        | 1.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 33       | 16.84%  |
| Dell                 | 21       | 10.71%  |
| Goldstar             | 20       | 10.2%   |
| Acer                 | 19       | 9.69%   |
| Hewlett-Packard      | 10       | 5.1%    |
| Ancor Communications | 8        | 4.08%   |
| AOC                  | 7        | 3.57%   |
| ViewSonic            | 6        | 3.06%   |
| Sony                 | 6        | 3.06%   |
| Philips              | 6        | 3.06%   |
| BenQ                 | 6        | 3.06%   |
| Iiyama               | 5        | 2.55%   |
| Fujitsu Siemens      | 5        | 2.55%   |
| ASUSTek Computer     | 5        | 2.55%   |
| Lenovo               | 4        | 2.04%   |
| Eizo                 | 4        | 2.04%   |
| Vestel Elektronik    | 3        | 1.53%   |
| MSI                  | 3        | 1.53%   |
| Medion               | 3        | 1.53%   |
| Vizio                | 2        | 1.02%   |
| Xiaomi               | 1        | 0.51%   |
| Videoseven           | 1        | 0.51%   |
| Sceptre Tech         | 1        | 0.51%   |
| SANYO                | 1        | 0.51%   |
| Sangyo               | 1        | 0.51%   |
| SAC                  | 1        | 0.51%   |
| Ruijiang             | 1        | 0.51%   |
| RTK                  | 1        | 0.51%   |
| RIS                  | 1        | 0.51%   |
| Panasonic            | 1        | 0.51%   |
| NEC Computers        | 1        | 0.51%   |
| MiTAC                | 1        | 0.51%   |
| LG Electronics       | 1        | 0.51%   |
| IBM                  | 1        | 0.51%   |
| HYO                  | 1        | 0.51%   |
| Grundig              | 1        | 0.51%   |
| Gigabyte Technology  | 1        | 0.51%   |
| DTV                  | 1        | 0.51%   |
| CTV                  | 1        | 0.51%   |
| Arnos Instruments    | 1        | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 6        | 2.96%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch | 3        | 1.48%   |
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch            | 2        | 0.99%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                   | 2        | 0.99%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch    | 2        | 0.99%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                      | 2        | 0.99%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                 | 2        | 0.99%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                | 2        | 0.99%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                | 2        | 0.99%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch     | 2        | 0.99%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                   | 1        | 0.49%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                   | 1        | 0.49%   |
| Vizio D50-D1 VIZ1004 1920x1080 1100x620mm 49.7-inch                  | 1        | 0.49%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch               | 1        | 0.49%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch               | 1        | 0.49%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch        | 1        | 0.49%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch           | 1        | 0.49%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch              | 1        | 0.49%   |
| Sony TV SNY0801 1360x768                                             | 1        | 0.49%   |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                   | 1        | 0.49%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                 | 1        | 0.49%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                   | 1        | 0.49%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch               | 1        | 0.49%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                    | 1        | 0.49%   |
| Sangyo LCD Monitor M27A3 1920x1080                                   | 1        | 0.49%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1        | 0.49%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch    | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch  | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch | 1        | 0.49%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch | 1        | 0.49%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch   | 1        | 0.49%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch     | 1        | 0.49%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 1        | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 85       | 44.04%  |
| 1280x1024 (SXGA)   | 17       | 8.81%   |
| 3840x2160 (4K)     | 16       | 8.29%   |
| 2560x1440 (QHD)    | 16       | 8.29%   |
| 1680x1050 (WSXGA+) | 15       | 7.77%   |
| 1600x1200          | 7        | 3.63%   |
| 1440x900 (WXGA+)   | 7        | 3.63%   |
| 1366x768 (WXGA)    | 7        | 3.63%   |
| 3440x1440          | 3        | 1.55%   |
| 1920x1200 (WUXGA)  | 3        | 1.55%   |
| 1600x900 (HD+)     | 3        | 1.55%   |
| 1360x768           | 3        | 1.55%   |
| 2560x1080          | 2        | 1.04%   |
| 1280x720 (HD)      | 2        | 1.04%   |
| 1024x768 (XGA)     | 2        | 1.04%   |
| Unknown            | 2        | 1.04%   |
| 3840x1080          | 1        | 0.52%   |
| 2560x1600          | 1        | 0.52%   |
| 2048x1536          | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 29       | 14.95%  |
| 23      | 25       | 12.89%  |
| 21      | 24       | 12.37%  |
| 24      | 22       | 11.34%  |
| 22      | 13       | 6.7%    |
| 19      | 12       | 6.19%   |
| 31      | 11       | 5.67%   |
| 18      | 10       | 5.15%   |
| 17      | 7        | 3.61%   |
| Unknown | 7        | 3.61%   |
| 84      | 5        | 2.58%   |
| 34      | 5        | 2.58%   |
| 65      | 4        | 2.06%   |
| 20      | 4        | 2.06%   |
| 15      | 4        | 2.06%   |
| 25      | 2        | 1.03%   |
| 86      | 1        | 0.52%   |
| 72      | 1        | 0.52%   |
| 61      | 1        | 0.52%   |
| 54      | 1        | 0.52%   |
| 49      | 1        | 0.52%   |
| 47      | 1        | 0.52%   |
| 42      | 1        | 0.52%   |
| 40      | 1        | 0.52%   |
| 26      | 1        | 0.52%   |
| 16      | 1        | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 72       | 38.1%   |
| 401-500     | 53       | 28.04%  |
| 601-700     | 13       | 6.88%   |
| 351-400     | 11       | 5.82%   |
| 301-350     | 11       | 5.82%   |
| 1001-1500   | 8        | 4.23%   |
| 1501-2000   | 7        | 3.7%    |
| Unknown     | 7        | 3.7%    |
| 701-800     | 5        | 2.65%   |
| 801-900     | 1        | 0.53%   |
| 901-1000    | 1        | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 124      | 65.96%  |
| 16/10   | 26       | 13.83%  |
| 5/4     | 17       | 9.04%   |
| 4/3     | 9        | 4.79%   |
| Unknown | 6        | 3.19%   |
| 21/9    | 5        | 2.66%   |
| 3/2     | 1        | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 72       | 37.7%   |
| 301-350        | 29       | 15.18%  |
| 151-200        | 26       | 13.61%  |
| 351-500        | 16       | 8.38%   |
| More than 1000 | 14       | 7.33%   |
| 141-150        | 12       | 6.28%   |
| 251-300        | 7        | 3.66%   |
| Unknown        | 7        | 3.66%   |
| 501-1000       | 3        | 1.57%   |
| 101-110        | 2        | 1.05%   |
| 121-130        | 1        | 0.52%   |
| 111-120        | 1        | 0.52%   |
| 91-100         | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 128      | 69.19%  |
| 101-120 | 34       | 18.38%  |
| 1-50    | 11       | 5.95%   |
| Unknown | 7        | 3.78%   |
| 121-160 | 3        | 1.62%   |
| 161-240 | 2        | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 160      | 85.56%  |
| 2     | 22       | 11.76%  |
| 0     | 3        | 1.6%    |
| 3     | 2        | 1.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 115      | 43.23%  |
| Intel                           | 76       | 28.57%  |
| Qualcomm Atheros                | 15       | 5.64%   |
| Ralink Technology               | 7        | 2.63%   |
| Broadcom                        | 7        | 2.63%   |
| TP-Link                         | 6        | 2.26%   |
| MediaTek                        | 6        | 2.26%   |
| Ralink                          | 5        | 1.88%   |
| Broadcom Limited                | 4        | 1.5%    |
| Nvidia                          | 3        | 1.13%   |
| VIA Technologies                | 2        | 0.75%   |
| Microsoft                       | 2        | 0.75%   |
| Marvell Technology Group        | 2        | 0.75%   |
| Linksys                         | 2        | 0.75%   |
| Xiaomi                          | 1        | 0.38%   |
| U-Blox                          | 1        | 0.38%   |
| Samsung Electronics             | 1        | 0.38%   |
| Qualcomm Atheros Communications | 1        | 0.38%   |
| OPPO Electronics                | 1        | 0.38%   |
| NetGear                         | 1        | 0.38%   |
| Mercucys                        | 1        | 0.38%   |
| JMicron Technology              | 1        | 0.38%   |
| Edimax Technology               | 1        | 0.38%   |
| D-Link System                   | 1        | 0.38%   |
| D-Link                          | 1        | 0.38%   |
| AVM                             | 1        | 0.38%   |
| ASUSTek Computer                | 1        | 0.38%   |
| Aquantia                        | 1        | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86       | 29.35%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 3.41%   |
| Intel Ethernet Controller I225-V                                  | 9        | 3.07%   |
| Intel I211 Gigabit Network Connection                             | 8        | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 2.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 2.39%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.71%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.71%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.71%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4        | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 1.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 1.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.02%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.02%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.02%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3        | 1.02%   |
| Intel Wireless-AC 9260                                            | 3        | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.68%   |
| Realtek 802.11ac NIC                                              | 2        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.68%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 0.68%   |
| Intel Wireless 8260                                               | 2        | 0.68%   |
| Intel Wireless 7260                                               | 2        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.68%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.68%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.68%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 24       | 26.97%  |
| Intel                           | 20       | 22.47%  |
| Ralink Technology               | 7        | 7.87%   |
| TP-Link                         | 6        | 6.74%   |
| Qualcomm Atheros                | 6        | 6.74%   |
| MediaTek                        | 6        | 6.74%   |
| Ralink                          | 5        | 5.62%   |
| Broadcom                        | 3        | 3.37%   |
| Microsoft                       | 2        | 2.25%   |
| Linksys                         | 2        | 2.25%   |
| Qualcomm Atheros Communications | 1        | 1.12%   |
| NetGear                         | 1        | 1.12%   |
| Mercucys                        | 1        | 1.12%   |
| Edimax Technology               | 1        | 1.12%   |
| D-Link                          | 1        | 1.12%   |
| Broadcom Limited                | 1        | 1.12%   |
| AVM                             | 1        | 1.12%   |
| ASUSTek Computer                | 1        | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                               | 5        | 5.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 4        | 4.49%   |
| Intel Wi-Fi 6 AX200                                                                           | 4        | 4.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 3.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 3        | 3.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3        | 3.37%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 3        | 3.37%   |
| Intel Wireless-AC 9260                                                                        | 3        | 3.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2        | 2.25%   |
| Realtek 802.11ac NIC                                                                          | 2        | 2.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2        | 2.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2        | 2.25%   |
| Intel Wireless 8260                                                                           | 2        | 2.25%   |
| Intel Wireless 7260                                                                           | 2        | 2.25%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 1.12%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1        | 1.12%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.12%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.12%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 1        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 1        | 1.12%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.12%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.12%   |
| Realtek B1610311068                                                                           | 1        | 1.12%   |
| Realtek 8821CE PCIe 802.11ac Wireless Network Controller                                      | 1        | 1.12%   |
| Realtek 802.11ac WLAN Adapter                                                                 | 1        | 1.12%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 1.12%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 1.12%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.12%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 1.12%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 1.12%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 1        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.12%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1        | 1.12%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 102      | 52.04%  |
| Intel                    | 66       | 33.67%  |
| Qualcomm Atheros         | 9        | 4.59%   |
| Broadcom                 | 4        | 2.04%   |
| Nvidia                   | 3        | 1.53%   |
| Broadcom Limited         | 3        | 1.53%   |
| VIA Technologies         | 2        | 1.02%   |
| Marvell Technology Group | 2        | 1.02%   |
| Xiaomi                   | 1        | 0.51%   |
| OPPO Electronics         | 1        | 0.51%   |
| JMicron Technology       | 1        | 0.51%   |
| D-Link System            | 1        | 0.51%   |
| Aquantia                 | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86       | 42.57%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 4.95%   |
| Intel Ethernet Controller I225-V                                  | 9        | 4.46%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 3.96%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 7        | 3.47%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.48%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.48%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.49%   |
| Nvidia MCP61 Ethernet                                             | 3        | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.99%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.99%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.99%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.99%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.99%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.5%    |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.5%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.5%    |
| Intel Ethernet Connection I218-V                                  | 1        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.5%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.5%    |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.5%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 186      | 69.4%   |
| WiFi     | 80       | 29.85%  |
| Modem    | 2        | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 137      | 71.35%  |
| WiFi     | 55       | 28.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 129      | 68.98%  |
| 2     | 50       | 26.74%  |
| 3     | 8        | 4.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 151      | 80.32%  |
| Yes  | 37       | 19.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 38.64%  |
| Cambridge Silicon Radio         | 8        | 18.18%  |
| Realtek Semiconductor           | 4        | 9.09%   |
| MediaTek                        | 4        | 9.09%   |
| Broadcom                        | 3        | 6.82%   |
| ASUSTek Computer                | 3        | 6.82%   |
| Foxconn / Hon Hai               | 2        | 4.55%   |
| TP-Link                         | 1        | 2.27%   |
| Qualcomm Atheros Communications | 1        | 2.27%   |
| Apple                           | 1        | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 18.18%  |
| Intel Bluetooth wireless interface                    | 5        | 11.36%  |
| Realtek Bluetooth Radio                               | 4        | 9.09%   |
| MediaTek Wireless_Device                              | 4        | 9.09%   |
| Intel AX200 Bluetooth                                 | 4        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 6.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 6.82%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 4.55%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 4.55%   |
| TP-Link UB500 Adapter                                 | 1        | 2.27%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.27%   |
| Intel Bluetooth Device                                | 1        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 2.27%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.27%   |
| ASUS BCM20702A0                                       | 1        | 2.27%   |
| Apple Bluetooth Host Controller                       | 1        | 2.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 120      | 37.04%  |
| AMD                     | 81       | 25%     |
| Nvidia                  | 74       | 22.84%  |
| Creative Labs           | 10       | 3.09%   |
| C-Media Electronics     | 8        | 2.47%   |
| VIA Technologies        | 3        | 0.93%   |
| Texas Instruments       | 3        | 0.93%   |
| JMTek                   | 3        | 0.93%   |
| ROCCAT                  | 2        | 0.62%   |
| Kingston Technology     | 2        | 0.62%   |
| Focusrite-Novation      | 2        | 0.62%   |
| ULi Electronics         | 1        | 0.31%   |
| TerraTec Electronic     | 1        | 0.31%   |
| Tenx Technology         | 1        | 0.31%   |
| Setek Elektronik        | 1        | 0.31%   |
| Schiit Audio            | 1        | 0.31%   |
| Razer USA               | 1        | 0.31%   |
| Microsoft               | 1        | 0.31%   |
| Logitech                | 1        | 0.31%   |
| GYROCOM C&C             | 1        | 0.31%   |
| GN Netcom               | 1        | 0.31%   |
| Generalplus Technology  | 1        | 0.31%   |
| Fortemedia              | 1        | 0.31%   |
| Ensoniq                 | 1        | 0.31%   |
| Digidesign              | 1        | 0.31%   |
| Cambridge Silicon Radio | 1        | 0.31%   |
| BEHRINGER International | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                    | 16       | 4.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 14       | 3.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 14       | 3.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 13       | 3.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 13       | 3.5%    |
| AMD Family 17h/19h HD Audio Controller                                                          | 12       | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 11       | 2.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 10       | 2.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 10       | 2.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 9        | 2.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 7        | 1.89%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 7        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                      | 7        | 1.89%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 7        | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 7        | 1.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 1.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 1.62%   |
| Nvidia High Definition Audio Controller                                                         | 5        | 1.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 5        | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 1.35%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 5        | 1.35%   |
| Intel 200 Series PCH HD Audio                                                                   | 5        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 5        | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.35%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 5        | 1.35%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 4        | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 4        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 3        | 0.81%   |
| Nvidia TU104 HD Audio Controller                                                                | 3        | 0.81%   |
| Nvidia MCP61 High Definition Audio                                                              | 3        | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 3        | 0.81%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 3        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 3        | 0.81%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 0.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 3        | 0.81%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 3        | 0.81%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                    | 3        | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 3        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 39       | 18.84%  |
| Kingston                     | 34       | 16.43%  |
| Corsair                      | 29       | 14.01%  |
| Samsung Electronics          | 20       | 9.66%   |
| G.Skill                      | 18       | 8.7%    |
| SK hynix                     | 15       | 7.25%   |
| Crucial                      | 9        | 4.35%   |
| A-DATA Technology            | 6        | 2.9%    |
| Ramaxel Technology           | 5        | 2.42%   |
| Micron Technology            | 5        | 2.42%   |
| Nanya Technology             | 4        | 1.93%   |
| Unknown (ABCD)               | 3        | 1.45%   |
| Patriot                      | 3        | 1.45%   |
| Transcend                    | 2        | 0.97%   |
| Apacer                       | 2        | 0.97%   |
| Unknown                      | 2        | 0.97%   |
| Unknown (AB)                 | 1        | 0.48%   |
| Unifosa                      | 1        | 0.48%   |
| Smart                        | 1        | 0.48%   |
| RZX                          | 1        | 0.48%   |
| PNY                          | 1        | 0.48%   |
| Patriot Memory (PDP Systems) | 1        | 0.48%   |
| OCZ                          | 1        | 0.48%   |
| Golden Empire                | 1        | 0.48%   |
| Elpida                       | 1        | 0.48%   |
| Axiom                        | 1        | 0.48%   |
| Avant                        | 1        | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 6        | 2.59%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 3        | 1.29%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 3        | 1.29%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 3        | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 3        | 1.29%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 3        | 1.29%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 3        | 1.29%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 2        | 0.86%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 2        | 0.86%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 0.86%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 2        | 0.86%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                     | 2        | 0.86%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 2        | 0.86%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.86%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 2        | 0.86%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 2        | 0.86%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 2        | 0.86%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                 | 2        | 0.86%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s            | 2        | 0.86%   |
| Micron RAM 16JTF51264AZ-1G6M1 4096MB DIMM DDR3 1600MT/s        | 2        | 0.86%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2667MT/s          | 2        | 0.86%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s        | 2        | 0.86%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 0.86%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s          | 2        | 0.86%   |
| Unknown                                                        | 2        | 0.86%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.43%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                   | 1        | 0.43%   |
| Unknown RAM Module 512MB DIMM SDRAM                            | 1        | 0.43%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                       | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1        | 0.43%   |
| Unknown RAM Module 4GB DIMM                                    | 1        | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 1        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 67       | 35.83%  |
| DDR3    | 65       | 34.76%  |
| DDR2    | 16       | 8.56%   |
| Unknown | 16       | 8.56%   |
| SDRAM   | 10       | 5.35%   |
| DDR     | 6        | 3.21%   |
| LPDDR4  | 3        | 1.6%    |
| DDR5    | 3        | 1.6%    |
| LPDDR3  | 1        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 172      | 93.48%  |
| SODIMM | 12       | 6.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 58       | 28.71%  |
| 4096  | 57       | 28.22%  |
| 2048  | 36       | 17.82%  |
| 16384 | 26       | 12.87%  |
| 1024  | 14       | 6.93%   |
| 32768 | 7        | 3.47%   |
| 512   | 3        | 1.49%   |
| 256   | 1        | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 35       | 16.91%  |
| 1333    | 30       | 14.49%  |
| 3200    | 15       | 7.25%   |
| 3600    | 14       | 6.76%   |
| 800     | 10       | 4.83%   |
| 2400    | 9        | 4.35%   |
| 667     | 9        | 4.35%   |
| 2133    | 8        | 3.86%   |
| Unknown | 8        | 3.86%   |
| 2667    | 7        | 3.38%   |
| 3000    | 6        | 2.9%    |
| 2933    | 4        | 1.93%   |
| 2666    | 4        | 1.93%   |
| 1800    | 4        | 1.93%   |
| 333     | 4        | 1.93%   |
| 3533    | 3        | 1.45%   |
| 2048    | 3        | 1.45%   |
| 1867    | 3        | 1.45%   |
| 400     | 3        | 1.45%   |
| 49926   | 2        | 0.97%   |
| 6000    | 2        | 0.97%   |
| 3466    | 2        | 0.97%   |
| 3400    | 2        | 0.97%   |
| 3266    | 2        | 0.97%   |
| 1866    | 2        | 0.97%   |
| 1639    | 2        | 0.97%   |
| 1067    | 2        | 0.97%   |
| 533     | 2        | 0.97%   |
| 5800    | 1        | 0.48%   |
| 4133    | 1        | 0.48%   |
| 3866    | 1        | 0.48%   |
| 3733    | 1        | 0.48%   |
| 3100    | 1        | 0.48%   |
| 2800    | 1        | 0.48%   |
| 2200    | 1        | 0.48%   |
| 2000    | 1        | 0.48%   |
| 1066    | 1        | 0.48%   |
| 200     | 1        | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Canon                 | 3        | 30%     |
| Hewlett-Packard       | 2        | 20%     |
| Brother Industries    | 2        | 20%     |
| Seiko Epson           | 1        | 10%     |
| Lexmark International | 1        | 10%     |
| Konica Minolta        | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon MF641C                  | 2        | 20%     |
| Seiko Epson L380 Series       | 1        | 10%     |
| Lexmark International CS417dn | 1        | 10%     |
| Konica Minolta 206            | 1        | 10%     |
| HP ENVY 4500 series           | 1        | 10%     |
| HP Deskjet 1510               | 1        | 10%     |
| Canon MG5700 series           | 1        | 10%     |
| Brother MFC-7340              | 1        | 10%     |
| Brother DCP-L2540DW           | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LIDE 25  | 1        | 50%     |
| Canon CanoScan LiDE 210 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 36.67%  |
| Microsoft                     | 5        | 16.67%  |
| Sunplus Innovation Technology | 3        | 10%     |
| Generalplus Technology        | 2        | 6.67%   |
| Chicony Electronics           | 2        | 6.67%   |
| Trust                         | 1        | 3.33%   |
| Sunplus Technology            | 1        | 3.33%   |
| Sonix Technology              | 1        | 3.33%   |
| Microdia                      | 1        | 3.33%   |
| Huawei Technologies           | 1        | 3.33%   |
| Hewlett-Packard               | 1        | 3.33%   |
| Arkmicro Technologies         | 1        | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 4        | 13.33%  |
| Logitech Webcam C270                                    | 3        | 10%     |
| Sunplus HD 720P webcam                                  | 2        | 6.67%   |
| Logitech Webcam C930e                                   | 2        | 6.67%   |
| Logitech Webcam C200                                    | 2        | 6.67%   |
| Trust Widescreen 3MP Webcam                             | 1        | 3.33%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 3.33%   |
| Sunplus Aoni FHD Camera                                 | 1        | 3.33%   |
| Sonix USB Camera                                        | 1        | 3.33%   |
| Microsoft LifeCam VX-800                                | 1        | 3.33%   |
| Microdia Camera                                         | 1        | 3.33%   |
| Logitech Webcam Pro 9000                                | 1        | 3.33%   |
| Logitech Webcam C110                                    | 1        | 3.33%   |
| Logitech HD Webcam C615                                 | 1        | 3.33%   |
| Logitech B525 HD Webcam                                 | 1        | 3.33%   |
| Huawei UVC Camera                                       | 1        | 3.33%   |
| HP Webcam HD 2300                                       | 1        | 3.33%   |
| Generalplus GENERAL WEBCAM                              | 1        | 3.33%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 3.33%   |
| Chicony HP Prem AF Webcam KQ245AA                       | 1        | 3.33%   |
| Chicony HD Webcam                                       | 1        | 3.33%   |
| Arkmicro USB2.0 PC CAMERA                               | 1        | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Microsoft | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Microsoft Fingerprint Reader | 1        | 100%    |

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
| 0     | 165      | 88.24%  |
| 1     | 18       | 9.63%   |
| 3     | 2        | 1.07%   |
| 2     | 2        | 1.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 42.31%  |
| Net/wireless             | 6        | 23.08%  |
| Unassigned class         | 3        | 11.54%  |
| Communication controller | 2        | 7.69%   |
| Multimedia controller    | 1        | 3.85%   |
| Fingerprint reader       | 1        | 3.85%   |
| Dvb card                 | 1        | 3.85%   |
| Camera                   | 1        | 3.85%   |

