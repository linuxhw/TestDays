MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 124

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
| Dell          | 0D441T A03                  | [351a527308](https://linux-hardware.org/?probe=351a527308) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [482c922bbc](https://linux-hardware.org/?probe=482c922bbc) | Feb 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [13492935fd](https://linux-hardware.org/?probe=13492935fd) | Feb 09, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [11f3874a6f](https://linux-hardware.org/?probe=11f3874a6f) | Feb 07, 2023 |
| ASUSTek       | Z97M-PLUS                   | [99a4bb9e50](https://linux-hardware.org/?probe=99a4bb9e50) | Feb 05, 2023 |
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
| ASRock        | B365M Pro4                  | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| Pegatron      | NARRA3                      | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| ASUSTek       | Z170-P                      | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| ASUSTek       | P5G41T-M LX                 | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | 1632                        | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
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
| Gigabyte      | B550M S2H                   | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell          | 0YXT71 A01                  | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | 1046 NO DPK                 | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP            | 3647h                       | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI           | Z97 GAMING 5                | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASUSTek       | X99-DELUXE                  | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| HP            | 0B4Ch D                     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX         | B550M                       | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock        | X570 Steel Legend           | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Gigabyte      | X570 AORUS PRO              | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Gigabyte      | B550M DS3H                  | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.10.0-21-amd64              | 14       | 13.33%  |
| 5.10.0-20-amd64              | 12       | 11.43%  |
| 6.0.0-6mx-amd64              | 6        | 5.71%   |
| 5.14.0-4mx-amd64             | 6        | 5.71%   |
| 5.10.0-19-amd64              | 6        | 5.71%   |
| 5.10.0-18-amd64              | 6        | 5.71%   |
| 5.10.0-13-amd64              | 5        | 4.76%   |
| 5.18.0-4mx-amd64             | 4        | 3.81%   |
| 5.10.0-16-amd64              | 4        | 3.81%   |
| 5.10.0-15-amd64              | 4        | 3.81%   |
| 5.16.0-5mx-amd64             | 3        | 2.86%   |
| 5.10.0-23-amd64              | 3        | 2.86%   |
| 6.0.0-10.1-liquorix-amd64    | 2        | 1.9%    |
| 5.14.0-3mx-amd64             | 2        | 1.9%    |
| 5.10.0-9-amd64               | 2        | 1.9%    |
| 5.10.0-11-amd64              | 2        | 1.9%    |
| 6.2.14-1-liquorix-amd64      | 1        | 0.95%   |
| 6.1.15-2-liquorix-amd64      | 1        | 0.95%   |
| 6.1.0-2mx-amd64              | 1        | 0.95%   |
| 6.0.5-x64v1-xanmod1          | 1        | 0.95%   |
| 6.0.0-4mx-rt-amd64           | 1        | 0.95%   |
| 6.0.0-13.3-liquorix-amd64    | 1        | 0.95%   |
| 5.19.0-4.2-liquorix-amd64    | 1        | 0.95%   |
| 5.19.0-17.2-liquorix-amd64   | 1        | 0.95%   |
| 5.19.0-14.1-liquorix-amd64   | 1        | 0.95%   |
| 5.17.0-3mx-amd64             | 1        | 0.95%   |
| 5.16.0-rc5-hwmon-next+       | 1        | 0.95%   |
| 5.16.0-6mx-amd64             | 1        | 0.95%   |
| 5.15.0-2-amd64               | 1        | 0.95%   |
| 5.15.0-0.bpo.2-amd64         | 1        | 0.95%   |
| 5.14.0-2mx-amd64             | 1        | 0.95%   |
| 5.10.52-antix.1-amd64-smp    | 1        | 0.95%   |
| 5.10.113-lkdtm-i386pae       | 1        | 0.95%   |
| 5.10.111-tkg-cfs             | 1        | 0.95%   |
| 5.10.0-22-amd64              | 1        | 0.95%   |
| 5.10.0-20-686-pae            | 1        | 0.95%   |
| 5.10.0-18-686-pae            | 1        | 0.95%   |
| 5.10.0-17-amd64              | 1        | 0.95%   |
| 5.10.0-10-amd64              | 1        | 0.95%   |
| 4.19.0-256-antix.1-amd64-smp | 1        | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 62       | 59.62%  |
| 6.0.0    | 10       | 9.62%   |
| 5.14.0   | 9        | 8.65%   |
| 5.16.0   | 5        | 4.81%   |
| 5.18.0   | 4        | 3.85%   |
| 5.19.0   | 3        | 2.88%   |
| 5.15.0   | 2        | 1.92%   |
| 6.2.14   | 1        | 0.96%   |
| 6.1.15   | 1        | 0.96%   |
| 6.1.0    | 1        | 0.96%   |
| 6.0.5    | 1        | 0.96%   |
| 5.17.0   | 1        | 0.96%   |
| 5.10.52  | 1        | 0.96%   |
| 5.10.113 | 1        | 0.96%   |
| 5.10.111 | 1        | 0.96%   |
| 4.19.0   | 1        | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 65       | 62.5%   |
| 6.0     | 11       | 10.58%  |
| 5.14    | 9        | 8.65%   |
| 5.16    | 5        | 4.81%   |
| 5.18    | 4        | 3.85%   |
| 5.19    | 3        | 2.88%   |
| 6.1     | 2        | 1.92%   |
| 5.15    | 2        | 1.92%   |
| 6.2     | 1        | 0.96%   |
| 5.17    | 1        | 0.96%   |
| 4.19    | 1        | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 101      | 97.12%  |
| i686   | 3        | 2.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 78       | 75%     |
| KDE5             | 23       | 22.12%  |
| lightdm-xsession | 2        | 1.92%   |
| Unknown          | 1        | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 104      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 78       | 75%     |
| SDDM    | 22       | 21.15%  |
| SLiM    | 3        | 2.88%   |
| GDM     | 1        | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 47       | 45.19%  |
| de_DE | 15       | 14.42%  |
| it_IT | 7        | 6.73%   |
| ru_RU | 4        | 3.85%   |
| pl_PL | 4        | 3.85%   |
| en_GB | 4        | 3.85%   |
| es_AR | 3        | 2.88%   |
| sv_SE | 2        | 1.92%   |
| fr_FR | 2        | 1.92%   |
| es_MX | 2        | 1.92%   |
| es_ES | 2        | 1.92%   |
| en_CA | 2        | 1.92%   |
| de_CH | 2        | 1.92%   |
| pt_BR | 1        | 0.96%   |
| hu_HU | 1        | 0.96%   |
| hr_HR | 1        | 0.96%   |
| fi_FI | 1        | 0.96%   |
| es_VE | 1        | 0.96%   |
| es_CO | 1        | 0.96%   |
| en_NZ | 1        | 0.96%   |
| en_AU | 1        | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 60       | 57.69%  |
| EFI  | 44       | 42.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 92       | 88.46%  |
| Overlay  | 8        | 7.69%   |
| Xfs      | 1        | 0.96%   |
| Reiserfs | 1        | 0.96%   |
| Ext3     | 1        | 0.96%   |
| Btrfs    | 1        | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 60       | 57.69%  |
| MBR  | 44       | 42.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 61.54%  |
| Yes       | 40       | 38.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56       | 53.85%  |
| No        | 48       | 46.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 20       | 19.23%  |
| Gigabyte Technology                  | 14       | 13.46%  |
| MSI                                  | 12       | 11.54%  |
| Hewlett-Packard                      | 9        | 8.65%   |
| Dell                                 | 9        | 8.65%   |
| ASRock                               | 9        | 8.65%   |
| Lenovo                               | 6        | 5.77%   |
| Unknown                              | 4        | 3.85%   |
| Intel                                | 3        | 2.88%   |
| Pegatron                             | 2        | 1.92%   |
| Fujitsu                              | 2        | 1.92%   |
| Biostar                              | 2        | 1.92%   |
| ZOTAC                                | 1        | 0.96%   |
| SIRAGON                              | 1        | 0.96%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.96%   |
| MP                                   | 1        | 0.96%   |
| Medion                               | 1        | 0.96%   |
| Huanan                               | 1        | 0.96%   |
| Gateway                              | 1        | 0.96%   |
| GALAX                                | 1        | 0.96%   |
| Foxconn                              | 1        | 0.96%   |
| ECS                                  | 1        | 0.96%   |
| BESSTAR Tech                         | 1        | 0.96%   |
| AOpen                                | 1        | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 7        | 6.73%   |
| Unknown                                     | 5        | 4.81%   |
| MSI MS-7C91                                 | 2        | 1.92%   |
| Gigabyte GA-MA785GM-US2H                    | 2        | 1.92%   |
| Dell OptiPlex 9020                          | 2        | 1.92%   |
| Dell OptiPlex 755                           | 2        | 1.92%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 1.92%   |
| SIRAGON AIO-5150                            | 1        | 0.96%   |
| Shenzhen Meigao Electronic Equipment UM450  | 1        | 0.96%   |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 0.96%   |
| Pegatron 2AD5                               | 1        | 0.96%   |
| MSI MS-7E12                                 | 1        | 0.96%   |
| MSI MS-7C37                                 | 1        | 0.96%   |
| MSI MS-7B98                                 | 1        | 0.96%   |
| MSI MS-7B53                                 | 1        | 0.96%   |
| MSI MS-7A63                                 | 1        | 0.96%   |
| MSI MS-7A37                                 | 1        | 0.96%   |
| MSI MS-7A34                                 | 1        | 0.96%   |
| MSI MS-7917                                 | 1        | 0.96%   |
| MSI MS-7823                                 | 1        | 0.96%   |
| MSI MS-7758                                 | 1        | 0.96%   |
| MP MS-7848                                  | 1        | 0.96%   |
| Medion Akoya P5330 E MD8876/2458            | 1        | 0.96%   |
| Lenovo V50s-07IMB 11HB002AFR                | 1        | 0.96%   |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 0.96%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 0.96%   |
| Lenovo ThinkCentre M58 7638CB8              | 1        | 0.96%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 0.96%   |
| Lenovo 10AAS1QB0B                           | 1        | 0.96%   |
| Intel V1.3                                  | 1        | 0.96%   |
| Intel DH55TC AAE70932-303                   | 1        | 0.96%   |
| Intel D34010WYK H14771-303                  | 1        | 0.96%   |
| Huanan X99-F8                               | 1        | 0.96%   |
| HP Z400 Workstation                         | 1        | 0.96%   |
| HP EliteDesk 800 G1 USDT                    | 1        | 0.96%   |
| HP dc5000 uT(PB647A)                        | 1        | 0.96%   |
| HP Compaq Elite 8300 CMT                    | 1        | 0.96%   |
| HP Compaq dc5850 Microtower                 | 1        | 0.96%   |
| HP Compaq 8100 Elite SFF PC                 | 1        | 0.96%   |
| HP Compaq 8000 Elite CMT PC                 | 1        | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 8        | 7.69%   |
| ASUS All                                   | 7        | 6.73%   |
| Unknown                                    | 5        | 4.81%   |
| HP Compaq                                  | 4        | 3.85%   |
| ASUS ROG                                   | 3        | 2.88%   |
| MSI MS-7C91                                | 2        | 1.92%   |
| Lenovo ThinkCentre                         | 2        | 1.92%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.92%   |
| Gigabyte B550M                             | 2        | 1.92%   |
| ASUS TUF                                   | 2        | 1.92%   |
| ASUS P5GC-MX                               | 2        | 1.92%   |
| SIRAGON AIO-5150                           | 1        | 0.96%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.96%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.96%   |
| Pegatron 2AD5                              | 1        | 0.96%   |
| MSI MS-7E12                                | 1        | 0.96%   |
| MSI MS-7C37                                | 1        | 0.96%   |
| MSI MS-7B98                                | 1        | 0.96%   |
| MSI MS-7B53                                | 1        | 0.96%   |
| MSI MS-7A63                                | 1        | 0.96%   |
| MSI MS-7A37                                | 1        | 0.96%   |
| MSI MS-7A34                                | 1        | 0.96%   |
| MSI MS-7917                                | 1        | 0.96%   |
| MSI MS-7823                                | 1        | 0.96%   |
| MSI MS-7758                                | 1        | 0.96%   |
| MP MS-7848                                 | 1        | 0.96%   |
| Medion Akoya                               | 1        | 0.96%   |
| Lenovo V50s-07IMB                          | 1        | 0.96%   |
| Lenovo ThinkStation                        | 1        | 0.96%   |
| Lenovo IdeaCentre                          | 1        | 0.96%   |
| Lenovo 10AAS1QB0B                          | 1        | 0.96%   |
| Intel V1.3                                 | 1        | 0.96%   |
| Intel DH55TC                               | 1        | 0.96%   |
| Intel D34010WYK                            | 1        | 0.96%   |
| Huanan X99-F8                              | 1        | 0.96%   |
| HP Z400                                    | 1        | 0.96%   |
| HP EliteDesk                               | 1        | 0.96%   |
| HP dc5000                                  | 1        | 0.96%   |
| HP 3646h                                   | 1        | 0.96%   |
| HP 260                                     | 1        | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 10       | 9.62%   |
| 2020 | 9        | 8.65%   |
| 2014 | 9        | 8.65%   |
| 2013 | 9        | 8.65%   |
| 2021 | 8        | 7.69%   |
| 2018 | 8        | 7.69%   |
| 2011 | 7        | 6.73%   |
| 2009 | 7        | 6.73%   |
| 2012 | 6        | 5.77%   |
| 2019 | 5        | 4.81%   |
| 2016 | 5        | 4.81%   |
| 2010 | 5        | 4.81%   |
| 2007 | 5        | 4.81%   |
| 2008 | 4        | 3.85%   |
| 2017 | 3        | 2.88%   |
| 2015 | 2        | 1.92%   |
| 2023 | 1        | 0.96%   |
| 2004 | 1        | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 104      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 104      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 104      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 27       | 25.96%  |
| 4.01-8.0    | 21       | 20.19%  |
| 32.01-64.0  | 19       | 18.27%  |
| 16.01-24.0  | 16       | 15.38%  |
| 3.01-4.0    | 10       | 9.62%   |
| 24.01-32.0  | 5        | 4.81%   |
| 64.01-256.0 | 3        | 2.88%   |
| 2.01-3.0    | 2        | 1.92%   |
| 0.51-1.0    | 1        | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 43       | 40.57%  |
| 2.01-3.0   | 28       | 26.42%  |
| 3.01-4.0   | 15       | 14.15%  |
| 4.01-8.0   | 12       | 11.32%  |
| 8.01-16.0  | 4        | 3.77%   |
| 0.51-1.0   | 3        | 2.83%   |
| 16.01-24.0 | 1        | 0.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 36.54%  |
| 3      | 24       | 23.08%  |
| 2      | 22       | 21.15%  |
| 4      | 10       | 9.62%   |
| 5      | 5        | 4.81%   |
| 8      | 3        | 2.88%   |
| 9      | 1        | 0.96%   |
| 7      | 1        | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 50.96%  |
| Yes       | 51       | 49.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 103      | 99.04%  |
| No        | 1        | 0.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 53       | 50.96%  |
| No        | 51       | 49.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 72.12%  |
| Yes       | 29       | 27.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 26       | 25%     |
| Germany                | 15       | 14.42%  |
| Italy                  | 7        | 6.73%   |
| Canada                 | 6        | 5.77%   |
| Poland                 | 5        | 4.81%   |
| Russia                 | 4        | 3.85%   |
| Sweden                 | 3        | 2.88%   |
| France                 | 3        | 2.88%   |
| Finland                | 3        | 2.88%   |
| Australia              | 3        | 2.88%   |
| Argentina              | 3        | 2.88%   |
| Venezuela              | 2        | 1.92%   |
| UK                     | 2        | 1.92%   |
| Switzerland            | 2        | 1.92%   |
| Spain                  | 2        | 1.92%   |
| Mexico                 | 2        | 1.92%   |
| India                  | 2        | 1.92%   |
| South Africa           | 1        | 0.96%   |
| Singapore              | 1        | 0.96%   |
| Romania                | 1        | 0.96%   |
| New Zealand            | 1        | 0.96%   |
| Netherlands            | 1        | 0.96%   |
| Indonesia              | 1        | 0.96%   |
| Hungary                | 1        | 0.96%   |
| Greece                 | 1        | 0.96%   |
| French Guiana          | 1        | 0.96%   |
| Estonia                | 1        | 0.96%   |
| Croatia                | 1        | 0.96%   |
| Colombia               | 1        | 0.96%   |
| Brazil                 | 1        | 0.96%   |
| Bosnia and Herzegovina | 1        | 0.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Moscow        | 3        | 2.88%   |
| Toronto       | 2        | 1.92%   |
| Sydney        | 2        | 1.92%   |
| Mesquite      | 2        | 1.92%   |
| Krakow        | 2        | 1.92%   |
| Houston       | 2        | 1.92%   |
| Ettingen      | 2        | 1.92%   |
| Córdoba      | 2        | 1.92%   |
| Berlin        | 2        | 1.92%   |
| Alma          | 2        | 1.92%   |
| Zagreb        | 1        | 0.96%   |
| Volos         | 1        | 0.96%   |
| Voghera       | 1        | 0.96%   |
| Vilhelmina    | 1        | 0.96%   |
| Vasco da Gama | 1        | 0.96%   |
| Vaidasoo      | 1        | 0.96%   |
| Tuglie        | 1        | 0.96%   |
| Tlalnepantla  | 1        | 0.96%   |
| Tampere       | 1        | 0.96%   |
| Surrey        | 1        | 0.96%   |
| Stevens Point | 1        | 0.96%   |
| Stafford      | 1        | 0.96%   |
| St Petersburg | 1        | 0.96%   |
| Sollentuna    | 1        | 0.96%   |
| Singapore     | 1        | 0.96%   |
| Seelbach      | 1        | 0.96%   |
| San Fernando  | 1        | 0.96%   |
| San Diego     | 1        | 0.96%   |
| Rzeszów      | 1        | 0.96%   |
| Rosporden     | 1        | 0.96%   |
| Reno          | 1        | 0.96%   |
| Rathenow      | 1        | 0.96%   |
| Puebla City   | 1        | 0.96%   |
| Portland      | 1        | 0.96%   |
| Portage       | 1        | 0.96%   |
| Pompano Beach | 1        | 0.96%   |
| Pila          | 1        | 0.96%   |
| Piedmont      | 1        | 0.96%   |
| Otwock        | 1        | 0.96%   |
| Osnabrück    | 1        | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 37       | 63     | 18.23%  |
| Seagate                   | 35       | 51     | 17.24%  |
| WDC                       | 31       | 38     | 15.27%  |
| Kingston                  | 20       | 21     | 9.85%   |
| SanDisk                   | 11       | 13     | 5.42%   |
| Toshiba                   | 10       | 11     | 4.93%   |
| China                     | 9        | 10     | 4.43%   |
| Hitachi                   | 5        | 6      | 2.46%   |
| Crucial                   | 5        | 5      | 2.46%   |
| Unknown                   | 4        | 6      | 1.97%   |
| PNY                       | 3        | 4      | 1.48%   |
| Corsair                   | 3        | 3      | 1.48%   |
| Transcend                 | 2        | 2      | 0.99%   |
| Silicon Motion            | 2        | 2      | 0.99%   |
| Intel                     | 2        | 2      | 0.99%   |
| GOODRAM                   | 2        | 2      | 0.99%   |
| Apacer                    | 2        | 2      | 0.99%   |
| A-DATA Technology         | 2        | 2      | 0.99%   |
| Vaseky                    | 1        | 1      | 0.49%   |
| Team                      | 1        | 1      | 0.49%   |
| SPCC                      | 1        | 1      | 0.49%   |
| Rogueware                 | 1        | 2      | 0.49%   |
| Phison Electronics        | 1        | 1      | 0.49%   |
| Phison                    | 1        | 1      | 0.49%   |
| OCZ                       | 1        | 1      | 0.49%   |
| Mushkin                   | 1        | 1      | 0.49%   |
| Micron/Crucial Technology | 1        | 1      | 0.49%   |
| Micron Technology         | 1        | 1      | 0.49%   |
| Maxtor                    | 1        | 1      | 0.49%   |
| KingSpec                  | 1        | 1      | 0.49%   |
| JMicron Technology        | 1        | 1      | 0.49%   |
| HGST                      | 1        | 1      | 0.49%   |
| External                  | 1        | 1      | 0.49%   |
| CT1000P3                  | 1        | 1      | 0.49%   |
| Avant                     | 1        | 1      | 0.49%   |
| Acer                      | 1        | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37480G 480GB SSD  | 6        | 2.49%   |
| Kingston SV300S37A240G 240GB SSD | 5        | 2.07%   |
| Samsung SSD 970 EVO Plus 1TB     | 4        | 1.66%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.66%   |
| Seagate ST3500413AS 500GB        | 3        | 1.24%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 1.24%   |
| SanDisk SDSSDA240G 240GB         | 3        | 1.24%   |
| SanDisk NVMe SSD Drive 1TB       | 3        | 1.24%   |
| Samsung SSD 980 PRO 1TB          | 3        | 1.24%   |
| Samsung SSD 850 EVO 1TB          | 3        | 1.24%   |
| Samsung SSD 840 Series 120GB     | 3        | 1.24%   |
| WDC WD3200AAKS-75B3A0 320GB      | 2        | 0.83%   |
| Unknown SD/MMC 2GB               | 2        | 0.83%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 0.83%   |
| Toshiba HDWD110 1TB              | 2        | 0.83%   |
| Toshiba DT01ACA100 1TB           | 2        | 0.83%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB   | 2        | 0.83%   |
| Seagate ST250DM000-1BD141 250GB  | 2        | 0.83%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.83%   |
| SanDisk SDSSDA120G 120GB         | 2        | 0.83%   |
| Samsung SSD 980 500GB            | 2        | 0.83%   |
| Samsung SSD 970 PRO 512GB        | 2        | 0.83%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 0.83%   |
| Samsung SSD 870 QVO 1TB          | 2        | 0.83%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.83%   |
| Samsung SSD 860 EVO 500GB        | 2        | 0.83%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.83%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.83%   |
| Samsung HD501LJ 500GB            | 2        | 0.83%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 0.83%   |
| Corsair MP400 2TB                | 2        | 0.83%   |
| China SSD 512GB                  | 2        | 0.83%   |
| China SATA SSD 512GB             | 2        | 0.83%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.41%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 1        | 0.41%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 1        | 0.41%   |
| WDC WD800AAJS-60M0A0 80GB        | 1        | 0.41%   |
| WDC WD7500BPKX-00HPJT0 752GB     | 1        | 0.41%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 51     | 40.7%   |
| WDC                 | 28       | 35     | 32.56%  |
| Toshiba             | 10       | 11     | 11.63%  |
| Hitachi             | 5        | 6      | 5.81%   |
| Samsung Electronics | 4        | 4      | 4.65%   |
| Unknown             | 1        | 1      | 1.16%   |
| Maxtor              | 1        | 1      | 1.16%   |
| HGST                | 1        | 1      | 1.16%   |
| External            | 1        | 1      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 34     | 30.23%  |
| Kingston            | 17       | 18     | 19.77%  |
| China               | 9        | 10     | 10.47%  |
| SanDisk             | 7        | 8      | 8.14%   |
| Crucial             | 4        | 4      | 4.65%   |
| WDC                 | 2        | 2      | 2.33%   |
| Transcend           | 2        | 2      | 2.33%   |
| PNY                 | 2        | 2      | 2.33%   |
| GOODRAM             | 2        | 2      | 2.33%   |
| A-DATA Technology   | 2        | 2      | 2.33%   |
| Vaseky              | 1        | 1      | 1.16%   |
| Team                | 1        | 1      | 1.16%   |
| SPCC                | 1        | 1      | 1.16%   |
| Rogueware           | 1        | 2      | 1.16%   |
| OCZ                 | 1        | 1      | 1.16%   |
| Mushkin             | 1        | 1      | 1.16%   |
| Micron Technology   | 1        | 1      | 1.16%   |
| KingSpec            | 1        | 1      | 1.16%   |
| Intel               | 1        | 1      | 1.16%   |
| CT1000P3            | 1        | 1      | 1.16%   |
| Avant               | 1        | 1      | 1.16%   |
| Apacer              | 1        | 1      | 1.16%   |
| Acer                | 1        | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 69       | 98     | 39.2%   |
| HDD     | 69       | 111    | 39.2%   |
| NVMe    | 34       | 47     | 19.32%  |
| Unknown | 3        | 5      | 1.7%    |
| MMC     | 1        | 1      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 94       | 200    | 68.12%  |
| NVMe | 34       | 47     | 24.64%  |
| SAS  | 9        | 14     | 6.52%   |
| MMC  | 1        | 1      | 0.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 74       | 118    | 51.75%  |
| 0.51-1.0   | 39       | 47     | 27.27%  |
| 1.01-2.0   | 16       | 22     | 11.19%  |
| 4.01-10.0  | 5        | 12     | 3.5%    |
| 3.01-4.0   | 4        | 4      | 2.8%    |
| 2.01-3.0   | 4        | 5      | 2.8%    |
| 10.01-20.0 | 1        | 1      | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 25%     |
| 251-500        | 22       | 21.15%  |
| 501-1000       | 13       | 12.5%   |
| 1001-2000      | 12       | 11.54%  |
| 2001-3000      | 10       | 9.62%   |
| More than 3000 | 8        | 7.69%   |
| 51-100         | 7        | 6.73%   |
| 1-20           | 4        | 3.85%   |
| 21-50          | 2        | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 28       | 26.67%  |
| 21-50          | 18       | 17.14%  |
| 101-250        | 18       | 17.14%  |
| 51-100         | 12       | 11.43%  |
| 251-500        | 8        | 7.62%   |
| 1001-2000      | 8        | 7.62%   |
| 501-1000       | 7        | 6.67%   |
| More than 3000 | 4        | 3.81%   |
| 2001-3000      | 2        | 1.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| China SSD 512GB                          | 2        | 2      | 6.06%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 3.03%   |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 1      | 3.03%   |
| WDC WD3200AAJS-00B4A0 320GB              | 1        | 1      | 3.03%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 3.03%   |
| WDC WD10EZRZ-00HTKB0 1TB                 | 1        | 1      | 3.03%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 3.03%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 3.03%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 3.03%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 3.03%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 3.03%   |
| Seagate ST3320418AS 320GB                | 1        | 1      | 3.03%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 3.03%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 3.03%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 3.03%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 3.03%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 3.03%   |
| Seagate ST1000DM003-9YN162 1TB           | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 2      | 3.03%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 3.03%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 3.03%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 3.03%   |
| Kingston SA400S37480G 480GB SSD          | 1        | 1      | 3.03%   |
| KingSpec P4-960 960GB SSD                | 1        | 1      | 3.03%   |
| Hitachi HTS545050A7E380 500GB            | 1        | 1      | 3.03%   |
| Hitachi HDS721050CLA362 500GB            | 1        | 1      | 3.03%   |
| HGST HTS545050A7E380 500GB               | 1        | 1      | 3.03%   |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 13     | 37.5%   |
| WDC                 | 7        | 7      | 21.88%  |
| Samsung Electronics | 4        | 6      | 12.5%   |
| China               | 2        | 2      | 6.25%   |
| Toshiba             | 1        | 1      | 3.13%   |
| Maxtor              | 1        | 1      | 3.13%   |
| Kingston            | 1        | 1      | 3.13%   |
| KingSpec            | 1        | 1      | 3.13%   |
| Hitachi             | 1        | 2      | 3.13%   |
| HGST                | 1        | 1      | 3.13%   |
| GOODRAM             | 1        | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 12       | 13     | 54.55%  |
| WDC     | 6        | 6      | 27.27%  |
| Toshiba | 1        | 1      | 4.55%   |
| Maxtor  | 1        | 1      | 4.55%   |
| Hitachi | 1        | 2      | 4.55%   |
| HGST    | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 24     | 70%     |
| SSD  | 9        | 12     | 30%     |

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
| Works    | 92       | 204    | 67.65%  |
| Malfunc  | 30       | 36     | 22.06%  |
| Detected | 14       | 22     | 10.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 71       | 44.94%  |
| AMD                         | 30       | 18.99%  |
| Samsung Electronics         | 16       | 10.13%  |
| ASMedia Technology          | 9        | 5.7%    |
| Phison Electronics          | 7        | 4.43%   |
| SanDisk                     | 5        | 3.16%   |
| Marvell Technology Group    | 4        | 2.53%   |
| Kingston Technology Company | 3        | 1.9%    |
| VIA Technologies            | 2        | 1.27%   |
| Silicon Motion              | 2        | 1.27%   |
| Nvidia                      | 2        | 1.27%   |
| Micron/Crucial Technology   | 2        | 1.27%   |
| ULi Electronics             | 1        | 0.63%   |
| Silicon Image               | 1        | 0.63%   |
| MAXIO Technology (Hangzhou) | 1        | 0.63%   |
| LSI Logic / Symbios Logic   | 1        | 0.63%   |
| JMicron Technology          | 1        | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 4.62%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9        | 4.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 3.59%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4        | 2.05%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 3        | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 1.54%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 1.54%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.54%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.54%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.54%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.54%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.03%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2        | 1.03%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.03%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.03%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.03%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2        | 1.03%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 90       | 58.44%  |
| NVMe | 34       | 22.08%  |
| IDE  | 23       | 14.94%  |
| RAID | 6        | 3.9%    |
| SCSI | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 72       | 69.23%  |
| AMD    | 32       | 30.77%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 3.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.88%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 2.88%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 2.88%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.92%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.92%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 1.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.92%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.92%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 1.92%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.92%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.92%   |
| AMD Athlon II X4 630 Processor              | 2        | 1.92%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 0.96%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.96%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.96%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.96%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.96%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.96%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 0.96%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.96%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1        | 0.96%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 0.96%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.96%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.96%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.96%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.96%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.96%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 0.96%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 0.96%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.96%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.96%   |
| Intel Core i5-6402P CPU @ 2.80GHz           | 1        | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1        | 0.96%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1        | 0.96%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.96%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 1        | 0.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 19       | 18.27%  |
| Intel Core i7           | 14       | 13.46%  |
| Intel Core i3           | 11       | 10.58%  |
| AMD Ryzen 5             | 10       | 9.62%   |
| Intel Core 2 Duo        | 7        | 6.73%   |
| AMD Ryzen 7             | 7        | 6.73%   |
| Other                   | 5        | 4.81%   |
| Intel Xeon              | 4        | 3.85%   |
| Intel Celeron           | 4        | 3.85%   |
| AMD Athlon II X4        | 3        | 2.88%   |
| Intel Pentium 4         | 2        | 1.92%   |
| Intel Core i9           | 2        | 1.92%   |
| AMD Ryzen 9             | 2        | 1.92%   |
| AMD Ryzen 3             | 2        | 1.92%   |
| AMD Phenom II X4        | 2        | 1.92%   |
| AMD Phenom              | 2        | 1.92%   |
| Intel Pentium Dual-Core | 1        | 0.96%   |
| Intel Pentium Dual      | 1        | 0.96%   |
| Intel Pentium           | 1        | 0.96%   |
| Intel Core M            | 1        | 0.96%   |
| AMD Ryzen Threadripper  | 1        | 0.96%   |
| AMD Ryzen 5 PRO         | 1        | 0.96%   |
| AMD FX                  | 1        | 0.96%   |
| AMD Athlon              | 1        | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 41       | 39.42%  |
| 2      | 25       | 24.04%  |
| 6      | 14       | 13.46%  |
| 8      | 12       | 11.54%  |
| 12     | 5        | 4.81%   |
| 1      | 3        | 2.88%   |
| 10     | 2        | 1.92%   |
| 16     | 1        | 0.96%   |
| 3      | 1        | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 103      | 99.04%  |
| 2      | 1        | 0.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 57       | 54.81%  |
| 1      | 47       | 45.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 103      | 99.04%  |
| 32-bit         | 1        | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 11       | 10.58%  |
| Unknown    | 10       | 9.62%   |
| 0x306a9    | 7        | 6.73%   |
| 0x206a7    | 6        | 5.77%   |
| 0x1067a    | 5        | 4.81%   |
| 0x906ed    | 4        | 3.85%   |
| 0x106e5    | 3        | 2.88%   |
| 0x08701021 | 3        | 2.88%   |
| 0x08108109 | 3        | 2.88%   |
| 0x0800820d | 3        | 2.88%   |
| 0x010000db | 3        | 2.88%   |
| 0xa0653    | 2        | 1.92%   |
| 0x6fd      | 2        | 1.92%   |
| 0x506e3    | 2        | 1.92%   |
| 0x306f2    | 2        | 1.92%   |
| 0x20655    | 2        | 1.92%   |
| 0x0a601203 | 2        | 1.92%   |
| 0x0a20120a | 2        | 1.92%   |
| 0x08001138 | 2        | 1.92%   |
| 0x01000083 | 2        | 1.92%   |
| 0xf49      | 1        | 0.96%   |
| 0xf34      | 1        | 0.96%   |
| 0xb0671    | 1        | 0.96%   |
| 0xa0671    | 1        | 0.96%   |
| 0xa0655    | 1        | 0.96%   |
| 0x906ea    | 1        | 0.96%   |
| 0x906e9    | 1        | 0.96%   |
| 0x906a4    | 1        | 0.96%   |
| 0x90672    | 1        | 0.96%   |
| 0x706a8    | 1        | 0.96%   |
| 0x706a1    | 1        | 0.96%   |
| 0x506c9    | 1        | 0.96%   |
| 0x50654    | 1        | 0.96%   |
| 0x406c3    | 1        | 0.96%   |
| 0x40651    | 1        | 0.96%   |
| 0x306d4    | 1        | 0.96%   |
| 0x106a5    | 1        | 0.96%   |
| 0x10676    | 1        | 0.96%   |
| 0x0a601201 | 1        | 0.96%   |
| 0x0a50000d | 1        | 0.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 17       | 16.35%  |
| SandyBridge      | 7        | 6.73%   |
| Penryn           | 7        | 6.73%   |
| K10              | 7        | 6.73%   |
| IvyBridge        | 7        | 6.73%   |
| Zen+             | 6        | 5.77%   |
| Zen 3            | 6        | 5.77%   |
| KabyLake         | 6        | 5.77%   |
| Unknown          | 6        | 5.77%   |
| Zen 2            | 5        | 4.81%   |
| Nehalem          | 5        | 4.81%   |
| Zen              | 4        | 3.85%   |
| Skylake          | 4        | 3.85%   |
| CometLake        | 3        | 2.88%   |
| Westmere         | 2        | 1.92%   |
| NetBurst         | 2        | 1.92%   |
| Goldmont plus    | 2        | 1.92%   |
| Core             | 2        | 1.92%   |
| Silvermont       | 1        | 0.96%   |
| Piledriver       | 1        | 0.96%   |
| Icelake          | 1        | 0.96%   |
| Goldmont         | 1        | 0.96%   |
| Broadwell        | 1        | 0.96%   |
| Alderlake Hybrid | 1        | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 42       | 36.21%  |
| Intel  | 38       | 32.76%  |
| AMD    | 36       | 31.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 5.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 3.42%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 3.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 3.42%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.56%   |
| AMD Raphael                                                                 | 3        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.56%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 3        | 2.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.71%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                         | 2        | 1.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.71%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 1.71%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.71%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.71%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.85%   |
| Nvidia NV44A [GeForce 6200]                                                 | 1        | 0.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.85%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.85%   |
| Nvidia GM107GL [Quadro K620]                                                | 1        | 0.85%   |
| Nvidia GK208 [GeForce GT 635]                                               | 1        | 0.85%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 1        | 0.85%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 0.85%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.85%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.85%   |
| Nvidia GF116 [GeForce GT 640 OEM]                                           | 1        | 0.85%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.85%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.85%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 38       | 36.19%  |
| 1 x AMD      | 31       | 29.52%  |
| 1 x Intel    | 30       | 28.57%  |
| AMD + Nvidia | 4        | 3.81%   |
| Intel + AMD  | 2        | 1.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 70.19%  |
| Proprietary | 26       | 25%     |
| Unknown     | 5        | 4.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 37       | 35.24%  |
| 1.01-2.0   | 17       | 16.19%  |
| 3.01-4.0   | 13       | 12.38%  |
| 7.01-8.0   | 12       | 11.43%  |
| 0.51-1.0   | 10       | 9.52%   |
| 0.01-0.5   | 8        | 7.62%   |
| 8.01-16.0  | 6        | 5.71%   |
| 2.01-3.0   | 2        | 1.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 14.68%  |
| Dell                 | 12       | 11.01%  |
| Acer                 | 11       | 10.09%  |
| Hewlett-Packard      | 8        | 7.34%   |
| Sony                 | 5        | 4.59%   |
| Goldstar             | 5        | 4.59%   |
| AOC                  | 5        | 4.59%   |
| Ancor Communications | 5        | 4.59%   |
| Fujitsu Siemens      | 4        | 3.67%   |
| Philips              | 3        | 2.75%   |
| Medion               | 3        | 2.75%   |
| Lenovo               | 3        | 2.75%   |
| Iiyama               | 3        | 2.75%   |
| Eizo                 | 3        | 2.75%   |
| BenQ                 | 3        | 2.75%   |
| ViewSonic            | 2        | 1.83%   |
| MSI                  | 2        | 1.83%   |
| ASUSTek Computer     | 2        | 1.83%   |
| Xiaomi               | 1        | 0.92%   |
| Vizio                | 1        | 0.92%   |
| Vestel Elektronik    | 1        | 0.92%   |
| Sangyo               | 1        | 0.92%   |
| SAC                  | 1        | 0.92%   |
| Ruijiang             | 1        | 0.92%   |
| RTK                  | 1        | 0.92%   |
| Panasonic            | 1        | 0.92%   |
| NEC Computers        | 1        | 0.92%   |
| MiTAC                | 1        | 0.92%   |
| LG Electronics       | 1        | 0.92%   |
| Grundig              | 1        | 0.92%   |
| Gigabyte Technology  | 1        | 0.92%   |
| CTV                  | 1        | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic VX1935wm-3 VSCB81E 1440x900 410x256mm 19.0-inch             | 2        | 1.74%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                    | 2        | 1.74%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch     | 2        | 1.74%   |
| MSI G27C6 MSI5CA9 1920x1080 598x336mm 27.0-inch                       | 2        | 1.74%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 1.74%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 2        | 1.74%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                    | 1        | 0.87%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1        | 0.87%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 1        | 0.87%   |
| Sony TV *00 SNY7105 3840x2160 1218x685mm 55.0-inch                    | 1        | 0.87%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                  | 1        | 0.87%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                    | 1        | 0.87%   |
| Sangyo LCD Monitor M27A3 1920x1080                                    | 1        | 0.87%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1        | 0.87%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch     | 1        | 0.87%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.87%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch  | 1        | 0.87%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 1        | 0.87%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 1        | 0.87%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch   | 1        | 0.87%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1        | 0.87%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 1        | 0.87%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.87%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch     | 1        | 0.87%   |
| Samsung Electronics LCD Monitor SMT24A550                             | 1        | 0.87%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1        | 0.87%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                     | 1        | 0.87%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.87%   |
| SAC HDMI SAC2700 2560x1440 596x335mm 26.9-inch                        | 1        | 0.87%   |
| Ruijiang RJT HDMI RJT1200 1920x1080 320x180mm 14.5-inch               | 1        | 0.87%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 0.87%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 0.87%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 1        | 0.87%   |
| Philips 170C PHL0848 1280x1024 338x270mm 17.0-inch                    | 1        | 0.87%   |
| Panasonic TV MEIA09B 1280x720 698x392mm 31.5-inch                     | 1        | 0.87%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch           | 1        | 0.87%   |
| MSI G27C6 MSI5CA9 1920x1080 600x340mm 27.2-inch                       | 1        | 0.87%   |
| MiTAC KOGAN TV MTC6306 1366x768 700x400mm 31.7-inch                   | 1        | 0.87%   |
| Medion MD30422PV MED86F6 1680x1050 474x296mm 22.0-inch                | 1        | 0.87%   |
| LG Electronics LCD Monitor E2211                                      | 1        | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 45       | 41.67%  |
| 2560x1440 (QHD)    | 11       | 10.19%  |
| 1680x1050 (WSXGA+) | 11       | 10.19%  |
| 1280x1024 (SXGA)   | 10       | 9.26%   |
| 3840x2160 (4K)     | 9        | 8.33%   |
| 1440x900 (WXGA+)   | 4        | 3.7%    |
| 1366x768 (WXGA)    | 4        | 3.7%    |
| 3440x1440          | 2        | 1.85%   |
| 1920x1200 (WUXGA)  | 2        | 1.85%   |
| 1280x720 (HD)      | 2        | 1.85%   |
| Unknown            | 2        | 1.85%   |
| 3840x1080          | 1        | 0.93%   |
| 2560x1600          | 1        | 0.93%   |
| 2560x1080          | 1        | 0.93%   |
| 1600x900 (HD+)     | 1        | 0.93%   |
| 1360x768           | 1        | 0.93%   |
| 1024x768 (XGA)     | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 16       | 15.09%  |
| 23      | 16       | 15.09%  |
| 24      | 11       | 10.38%  |
| 22      | 10       | 9.43%   |
| 31      | 8        | 7.55%   |
| 21      | 8        | 7.55%   |
| Unknown | 7        | 6.6%    |
| 19      | 5        | 4.72%   |
| 17      | 5        | 4.72%   |
| 18      | 4        | 3.77%   |
| 34      | 3        | 2.83%   |
| 65      | 2        | 1.89%   |
| 15      | 2        | 1.89%   |
| 86      | 1        | 0.94%   |
| 84      | 1        | 0.94%   |
| 61      | 1        | 0.94%   |
| 54      | 1        | 0.94%   |
| 47      | 1        | 0.94%   |
| 40      | 1        | 0.94%   |
| 26      | 1        | 0.94%   |
| 20      | 1        | 0.94%   |
| 16      | 1        | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 40       | 38.46%  |
| 401-500     | 24       | 23.08%  |
| 601-700     | 9        | 8.65%   |
| 301-350     | 7        | 6.73%   |
| Unknown     | 7        | 6.73%   |
| 351-400     | 6        | 5.77%   |
| 1001-1500   | 5        | 4.81%   |
| 701-800     | 3        | 2.88%   |
| 1501-2000   | 2        | 1.92%   |
| 801-900     | 1        | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 66       | 63.46%  |
| 16/10   | 17       | 16.35%  |
| 5/4     | 10       | 9.62%   |
| Unknown | 6        | 5.77%   |
| 21/9    | 3        | 2.88%   |
| 4/3     | 1        | 0.96%   |
| 3/2     | 1        | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 36       | 34.29%  |
| 301-350        | 16       | 15.24%  |
| 151-200        | 14       | 13.33%  |
| 351-500        | 11       | 10.48%  |
| Unknown        | 7        | 6.67%   |
| More than 1000 | 6        | 5.71%   |
| 141-150        | 6        | 5.71%   |
| 251-300        | 4        | 3.81%   |
| 501-1000       | 2        | 1.9%    |
| 121-130        | 1        | 0.95%   |
| 101-110        | 1        | 0.95%   |
| 91-100         | 1        | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 70       | 67.96%  |
| 101-120 | 16       | 15.53%  |
| 1-50    | 7        | 6.8%    |
| Unknown | 7        | 6.8%    |
| 121-160 | 2        | 1.94%   |
| 161-240 | 1        | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 85       | 81.73%  |
| 2     | 14       | 13.46%  |
| 0     | 3        | 2.88%   |
| 3     | 2        | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 63       | 40.13%  |
| Intel                           | 45       | 28.66%  |
| Qualcomm Atheros                | 9        | 5.73%   |
| MediaTek                        | 6        | 3.82%   |
| Ralink Technology               | 5        | 3.18%   |
| TP-Link                         | 4        | 2.55%   |
| Broadcom Limited                | 3        | 1.91%   |
| Broadcom                        | 3        | 1.91%   |
| Ralink                          | 2        | 1.27%   |
| Nvidia                          | 2        | 1.27%   |
| Microsoft                       | 2        | 1.27%   |
| Linksys                         | 2        | 1.27%   |
| Xiaomi                          | 1        | 0.64%   |
| VIA Technologies                | 1        | 0.64%   |
| Samsung Electronics             | 1        | 0.64%   |
| Qualcomm Atheros Communications | 1        | 0.64%   |
| OPPO Electronics                | 1        | 0.64%   |
| Mercucys                        | 1        | 0.64%   |
| JMicron Technology              | 1        | 0.64%   |
| Edimax Technology               | 1        | 0.64%   |
| D-Link                          | 1        | 0.64%   |
| AVM                             | 1        | 0.64%   |
| Aquantia                        | 1        | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44       | 25.43%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 4.62%   |
| Intel Ethernet Controller I225-V                                  | 8        | 4.62%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 2.31%   |
| Intel I211 Gigabit Network Connection                             | 4        | 2.31%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 1.73%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3        | 1.73%   |
| Intel Wireless-AC 9260                                            | 3        | 1.73%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.73%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.16%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.16%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 1.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.16%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.16%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.16%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.58%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.58%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.58%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.58%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.58%   |
| Realtek B1610311068                                               | 1        | 0.58%   |
| Realtek 8821CE PCIe 802.11ac Wireless Network Controller          | 1        | 0.58%   |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.58%   |
| Realtek 802.11ac NIC                                              | 1        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 29.51%  |
| Intel                           | 12       | 19.67%  |
| MediaTek                        | 6        | 9.84%   |
| Ralink Technology               | 5        | 8.2%    |
| TP-Link                         | 4        | 6.56%   |
| Qualcomm Atheros                | 3        | 4.92%   |
| Ralink                          | 2        | 3.28%   |
| Microsoft                       | 2        | 3.28%   |
| Linksys                         | 2        | 3.28%   |
| Qualcomm Atheros Communications | 1        | 1.64%   |
| Mercucys                        | 1        | 1.64%   |
| Edimax Technology               | 1        | 1.64%   |
| D-Link                          | 1        | 1.64%   |
| Broadcom Limited                | 1        | 1.64%   |
| Broadcom                        | 1        | 1.64%   |
| AVM                             | 1        | 1.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                     | 4        | 6.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 3        | 4.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 3        | 4.92%   |
| Intel Wireless-AC 9260                                              | 3        | 4.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2        | 3.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 2        | 3.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 2        | 3.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 3.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 3.28%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 2        | 3.28%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                               | 1        | 1.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 1.64%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 1.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 1        | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 1        | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1        | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 1.64%   |
| Realtek B1610311068                                                 | 1        | 1.64%   |
| Realtek 8821CE PCIe 802.11ac Wireless Network Controller            | 1        | 1.64%   |
| Realtek 802.11ac WLAN Adapter                                       | 1        | 1.64%   |
| Realtek 802.11ac NIC                                                | 1        | 1.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.64%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                           | 1        | 1.64%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                     | 1        | 1.64%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 1.64%   |
| Microsoft XBOX ACC                                                  | 1        | 1.64%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 1        | 1.64%   |
| Mercucys MW300UM RTL8192EU wifi                                     | 1        | 1.64%   |
| MediaTek WiFi                                                       | 1        | 1.64%   |
| Linksys WUSB6300 V2                                                 | 1        | 1.64%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 1.64%   |
| Intel Wireless 8260                                                 | 1        | 1.64%   |
| Intel Wireless 7265                                                 | 1        | 1.64%   |
| Intel Wireless 7260                                                 | 1        | 1.64%   |
| Intel Wireless 3160                                                 | 1        | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 1        | 1.64%   |
| Intel Wi-Fi 6 AX200                                                 | 1        | 1.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                     | 1        | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 1.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 52       | 48.15%  |
| Intel                 | 39       | 36.11%  |
| Qualcomm Atheros      | 6        | 5.56%   |
| Nvidia                | 2        | 1.85%   |
| Broadcom Limited      | 2        | 1.85%   |
| Broadcom              | 2        | 1.85%   |
| Xiaomi                | 1        | 0.93%   |
| VIA Technologies      | 1        | 0.93%   |
| OPPO Electronics      | 1        | 0.93%   |
| JMicron Technology    | 1        | 0.93%   |
| Aquantia              | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44       | 39.64%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 7.21%   |
| Intel Ethernet Controller I225-V                                  | 8        | 7.21%   |
| Intel I211 Gigabit Network Connection                             | 4        | 3.6%    |
| Intel Ethernet Connection I217-LM                                 | 4        | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 3.6%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.6%    |
| Intel Ethernet Connection (2) I218-V                              | 3        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.8%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.8%    |
| Nvidia MCP61 Ethernet                                             | 2        | 1.8%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.8%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.8%    |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.8%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.9%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.9%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.9%    |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1        | 0.9%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.9%    |
| Intel Ethernet Connection I218-V                                  | 1        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.9%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.9%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.9%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.9%    |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 1        | 0.9%    |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 1        | 0.9%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 103      | 65.61%  |
| WiFi     | 53       | 33.76%  |
| Modem    | 1        | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 68.22%  |
| WiFi     | 34       | 31.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 66.35%  |
| 2     | 30       | 28.85%  |
| 3     | 5        | 4.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 73       | 70.19%  |
| Yes  | 31       | 29.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 31.03%  |
| Cambridge Silicon Radio | 5        | 17.24%  |
| MediaTek                | 4        | 13.79%  |
| Realtek Semiconductor   | 3        | 10.34%  |
| Foxconn / Hon Hai       | 2        | 6.9%    |
| Broadcom                | 2        | 6.9%    |
| ASUSTek Computer        | 2        | 6.9%    |
| TP-Link                 | 1        | 3.45%   |
| Apple                   | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 17.24%  |
| MediaTek Wireless_Device                              | 4        | 13.79%  |
| Realtek Bluetooth Radio                               | 3        | 10.34%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3        | 10.34%  |
| Intel Bluetooth wireless interface                    | 3        | 10.34%  |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 6.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 6.9%    |
| TP-Link UB500 Adapter                                 | 1        | 3.45%   |
| Intel Bluetooth Device                                | 1        | 3.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 3.45%   |
| Intel AX200 Bluetooth                                 | 1        | 3.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 3.45%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 3.45%   |
| Apple Bluetooth Host Controller                       | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 69       | 38.33%  |
| AMD                     | 44       | 24.44%  |
| Nvidia                  | 37       | 20.56%  |
| C-Media Electronics     | 6        | 3.33%   |
| Creative Labs           | 5        | 2.78%   |
| VIA Technologies        | 2        | 1.11%   |
| Texas Instruments       | 2        | 1.11%   |
| ROCCAT                  | 2        | 1.11%   |
| TerraTec Electronic     | 1        | 0.56%   |
| Setek Elektronik        | 1        | 0.56%   |
| Schiit Audio            | 1        | 0.56%   |
| Razer USA               | 1        | 0.56%   |
| Kingston Technology     | 1        | 0.56%   |
| JMTek                   | 1        | 0.56%   |
| GYROCOM C&C             | 1        | 0.56%   |
| GN Netcom               | 1        | 0.56%   |
| Generalplus Technology  | 1        | 0.56%   |
| Ensoniq                 | 1        | 0.56%   |
| Digidesign              | 1        | 0.56%   |
| Cambridge Silicon Radio | 1        | 0.56%   |
| BEHRINGER International | 1        | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                          | 10       | 4.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 8        | 3.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 8        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 8        | 3.83%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 7        | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 6        | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 6        | 2.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 6        | 2.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 6        | 2.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 5        | 2.39%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 5        | 2.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 5        | 2.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 4        | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                                      | 4        | 1.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 4        | 1.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 1.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 4        | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 3        | 1.44%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 1.44%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 1.44%   |
| Intel 200 Series PCH HD Audio                                                                   | 3        | 1.44%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 1.44%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 3        | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 3        | 1.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 3        | 1.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 1.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 3        | 1.44%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 3        | 1.44%   |
| Texas Instruments PCM2902 Audio Codec                                                           | 2        | 0.96%   |
| ROCCAT Khan AIMO                                                                                | 2        | 0.96%   |
| Nvidia TU104 HD Audio Controller                                                                | 2        | 0.96%   |
| Nvidia MCP61 High Definition Audio                                                              | 2        | 0.96%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 0.96%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 2        | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 2        | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                    | 2        | 0.96%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 2        | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 2        | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 17       | 14.53%  |
| Unknown             | 16       | 13.68%  |
| Corsair             | 16       | 13.68%  |
| Samsung Electronics | 15       | 12.82%  |
| G.Skill             | 9        | 7.69%   |
| SK hynix            | 8        | 6.84%   |
| A-DATA Technology   | 6        | 5.13%   |
| Ramaxel Technology  | 5        | 4.27%   |
| Crucial             | 5        | 4.27%   |
| Unknown (ABCD)      | 3        | 2.56%   |
| Nanya Technology    | 3        | 2.56%   |
| Micron Technology   | 3        | 2.56%   |
| Transcend           | 2        | 1.71%   |
| Unknown             | 2        | 1.71%   |
| Unknown (AB)        | 1        | 0.85%   |
| Unifosa             | 1        | 0.85%   |
| Patriot             | 1        | 0.85%   |
| Golden Empire       | 1        | 0.85%   |
| Elpida              | 1        | 0.85%   |
| Avant               | 1        | 0.85%   |
| Apacer              | 1        | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 4        | 3.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 3        | 2.38%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 2        | 1.59%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                       | 2        | 1.59%   |
| Unknown RAM Module 2GB DIMM 667MT/s                            | 2        | 1.59%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s           | 2        | 1.59%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s                 | 2        | 1.59%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2667MT/s          | 2        | 1.59%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s        | 2        | 1.59%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 2        | 1.59%   |
| Unknown                                                        | 2        | 1.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1        | 0.79%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.79%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                       | 1        | 0.79%   |
| Unknown RAM Module 4GB DIMM 667MT/s                            | 1        | 0.79%   |
| Unknown RAM Module 4GB DIMM                                    | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 1        | 0.79%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.79%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 1        | 0.79%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 1333MT/s               | 1        | 0.79%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 0.79%   |
| Transcend RAM JM800QLU-2G 1GB DIMM DDR2 2048MT/s               | 1        | 0.79%   |
| Transcend RAM JM1333KLN-8GK 4GB DIMM DDR3 1333MT/s             | 1        | 0.79%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1        | 0.79%   |
| SK hynix RAM HMT41GU6MFR8C 8GB DIMM DDR3 1866MT/s              | 1        | 0.79%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.79%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 1        | 0.79%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.79%   |
| SK hynix RAM HMT125U6DFR8C-H9 2048MB DIMM DDR3 1333MT/s        | 1        | 0.79%   |
| SK hynix RAM HMA851U6DJR6N-WM 4GB DIMM DDR4 2933MT/s           | 1        | 0.79%   |
| Samsung RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1        | 0.79%   |
| Samsung RAM M393B5170DZ1-CF8 4GB DIMM DDR3 1066MT/s            | 1        | 0.79%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s           | 1        | 0.79%   |
| Samsung RAM M393A2K43CB2-CTD 16GB DIMM DDR4 2666MT/s           | 1        | 0.79%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s           | 1        | 0.79%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 1        | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 40%     |
| DDR3    | 36       | 34.29%  |
| DDR2    | 7        | 6.67%   |
| SDRAM   | 6        | 5.71%   |
| Unknown | 6        | 5.71%   |
| LPDDR4  | 3        | 2.86%   |
| DDR5    | 3        | 2.86%   |
| LPDDR3  | 1        | 0.95%   |
| DDR     | 1        | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 94       | 92.16%  |
| SODIMM | 8        | 7.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 32       | 28.83%  |
| 8192  | 27       | 24.32%  |
| 16384 | 20       | 18.02%  |
| 2048  | 20       | 18.02%  |
| 32768 | 6        | 5.41%   |
| 1024  | 5        | 4.5%    |
| 256   | 1        | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 14.41%  |
| 1333    | 15       | 13.51%  |
| 3600    | 11       | 9.91%   |
| 3200    | 9        | 8.11%   |
| 2667    | 7        | 6.31%   |
| 2400    | 6        | 5.41%   |
| 800     | 4        | 3.6%    |
| 667     | 4        | 3.6%    |
| Unknown | 4        | 3.6%    |
| 2666    | 3        | 2.7%    |
| 2133    | 3        | 2.7%    |
| 6000    | 2        | 1.8%    |
| 3400    | 2        | 1.8%    |
| 2933    | 2        | 1.8%    |
| 2048    | 2        | 1.8%    |
| 1866    | 2        | 1.8%    |
| 1800    | 2        | 1.8%    |
| 1067    | 2        | 1.8%    |
| 333     | 2        | 1.8%    |
| 5800    | 1        | 0.9%    |
| 4133    | 1        | 0.9%    |
| 3866    | 1        | 0.9%    |
| 3533    | 1        | 0.9%    |
| 3266    | 1        | 0.9%    |
| 3000    | 1        | 0.9%    |
| 2800    | 1        | 0.9%    |
| 2200    | 1        | 0.9%    |
| 2000    | 1        | 0.9%    |
| 1867    | 1        | 0.9%    |
| 1066    | 1        | 0.9%    |
| 533     | 1        | 0.9%    |
| 400     | 1        | 0.9%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 50%     |
| Hewlett-Packard    | 2        | 33.33%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Desktops | Percent |
|---------------------|----------|---------|
| Canon MF641C        | 2        | 33.33%  |
| HP ENVY 4500 series | 1        | 16.67%  |
| HP Deskjet 1510     | 1        | 16.67%  |
| Canon MG5700 series | 1        | 16.67%  |
| Brother MFC-7340    | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 35.29%  |
| Sunplus Innovation Technology | 2        | 11.76%  |
| Microsoft                     | 2        | 11.76%  |
| Chicony Electronics           | 2        | 11.76%  |
| Sonix Technology              | 1        | 5.88%   |
| Microdia                      | 1        | 5.88%   |
| Hewlett-Packard               | 1        | 5.88%   |
| Generalplus Technology        | 1        | 5.88%   |
| Arkmicro Technologies         | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Sunplus HD 720P webcam            | 2        | 11.76%  |
| Microsoft LifeCam HD-3000         | 2        | 11.76%  |
| Logitech Webcam C930e             | 2        | 11.76%  |
| Logitech Webcam C270              | 2        | 11.76%  |
| Sonix USB Camera                  | 1        | 5.88%   |
| Microdia Camera                   | 1        | 5.88%   |
| Logitech Webcam C110              | 1        | 5.88%   |
| Logitech HD Webcam C615           | 1        | 5.88%   |
| HP Webcam HD 2300                 | 1        | 5.88%   |
| Generalplus GENERAL WEBCAM        | 1        | 5.88%   |
| Chicony HP Prem AF Webcam KQ245AA | 1        | 5.88%   |
| Chicony HD Webcam                 | 1        | 5.88%   |
| Arkmicro USB2.0 PC CAMERA         | 1        | 5.88%   |

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
| 0     | 88       | 84.62%  |
| 1     | 13       | 12.5%   |
| 2     | 2        | 1.92%   |
| 3     | 1        | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 7        | 36.84%  |
| Net/wireless             | 5        | 26.32%  |
| Unassigned class         | 3        | 15.79%  |
| Communication controller | 2        | 10.53%  |
| Fingerprint reader       | 1        | 5.26%   |
| Dvb card                 | 1        | 5.26%   |

