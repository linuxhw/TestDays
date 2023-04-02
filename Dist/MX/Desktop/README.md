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

Total: 208

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 21          | 83       | 50%     |
| MX 19          | 46       | 27.71%  |
| MX 20          | 22       | 13.25%  |
| MX 18          | 12       | 7.23%   |
| MX 22          | 1        | 0.6%    |
| MX 17          | 1        | 0.6%    |
| MX 16-migrated | 1        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 165      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 20       | 11.36%  |
| 5.10.0-20-amd64            | 10       | 5.68%   |
| 5.10.0-21-amd64            | 8        | 4.55%   |
| 5.6.0-2-amd64              | 6        | 3.41%   |
| 5.14.0-4mx-amd64           | 6        | 3.41%   |
| 5.10.0-5mx-amd64           | 6        | 3.41%   |
| 5.10.0-19-amd64            | 6        | 3.41%   |
| 5.10.0-18-amd64            | 5        | 2.84%   |
| 5.10.0-13-amd64            | 5        | 2.84%   |
| 4.19.0-17-amd64            | 5        | 2.84%   |
| 5.8.0-3-amd64              | 4        | 2.27%   |
| 5.10.0-16-amd64            | 4        | 2.27%   |
| 5.10.0-15-amd64            | 4        | 2.27%   |
| 4.19.0-14-amd64            | 4        | 2.27%   |
| 6.0.0-6mx-amd64            | 3        | 1.7%    |
| 5.4.0-3-amd64              | 3        | 1.7%    |
| 5.16.0-5mx-amd64           | 3        | 1.7%    |
| 4.19.0-5-amd64             | 3        | 1.7%    |
| 4.19.0-18-amd64            | 3        | 1.7%    |
| 4.19.0-13-amd64            | 3        | 1.7%    |
| 4.19.0-1-amd64             | 3        | 1.7%    |
| 6.0.0-10.1-liquorix-amd64  | 2        | 1.14%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 1.14%   |
| 5.18.0-4mx-amd64           | 2        | 1.14%   |
| 5.14.0-3mx-amd64           | 2        | 1.14%   |
| 5.10.0-9-amd64             | 2        | 1.14%   |
| 5.10.0-11-amd64            | 2        | 1.14%   |
| 4.19.0-16-amd64            | 2        | 1.14%   |
| 4.19.0-12-amd64            | 2        | 1.14%   |
| 6.1.0-2mx-amd64            | 1        | 0.57%   |
| 6.0.5-x64v1-xanmod1        | 1        | 0.57%   |
| 6.0.0-4mx-rt-amd64         | 1        | 0.57%   |
| 6.0.0-13.3-liquorix-amd64  | 1        | 0.57%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 0.57%   |
| 5.5.0-7.1-liquorix-amd64   | 1        | 0.57%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 0.57%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 0.57%   |
| 5.5.0-050500rc1-lowlatency | 1        | 0.57%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 0.57%   |
| 5.4.10                     | 1        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 60       | 35.5%   |
| 4.19.0   | 45       | 26.63%  |
| 5.14.0   | 9        | 5.33%   |
| 6.0.0    | 7        | 4.14%   |
| 5.6.0    | 6        | 3.55%   |
| 5.5.0    | 5        | 2.96%   |
| 5.16.0   | 5        | 2.96%   |
| 5.8.0    | 4        | 2.37%   |
| 5.4.0    | 3        | 1.78%   |
| 5.19.0   | 3        | 1.78%   |
| 5.15.0   | 3        | 1.78%   |
| 5.8.16   | 2        | 1.18%   |
| 5.3.0    | 2        | 1.18%   |
| 5.18.0   | 2        | 1.18%   |
| 6.1.0    | 1        | 0.59%   |
| 6.0.5    | 1        | 0.59%   |
| 5.4.7    | 1        | 0.59%   |
| 5.4.10   | 1        | 0.59%   |
| 5.2.21   | 1        | 0.59%   |
| 5.17.0   | 1        | 0.59%   |
| 5.11.0   | 1        | 0.59%   |
| 5.10.52  | 1        | 0.59%   |
| 5.10.113 | 1        | 0.59%   |
| 5.10.111 | 1        | 0.59%   |
| 4.9.91   | 1        | 0.59%   |
| 4.18.0   | 1        | 0.59%   |
| 4.15.0   | 1        | 0.59%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 63       | 37.28%  |
| 4.19    | 45       | 26.63%  |
| 5.14    | 9        | 5.33%   |
| 6.0     | 8        | 4.73%   |
| 5.8     | 6        | 3.55%   |
| 5.6     | 6        | 3.55%   |
| 5.5     | 5        | 2.96%   |
| 5.4     | 5        | 2.96%   |
| 5.16    | 5        | 2.96%   |
| 5.19    | 3        | 1.78%   |
| 5.15    | 3        | 1.78%   |
| 5.3     | 2        | 1.18%   |
| 5.18    | 2        | 1.18%   |
| 6.1     | 1        | 0.59%   |
| 5.2     | 1        | 0.59%   |
| 5.17    | 1        | 0.59%   |
| 5.11    | 1        | 0.59%   |
| 4.9     | 1        | 0.59%   |
| 4.18    | 1        | 0.59%   |
| 4.15    | 1        | 0.59%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 159      | 96.36%  |
| i686   | 6        | 3.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 128      | 77.58%  |
| KDE5             | 28       | 16.97%  |
| MATE             | 2        | 1.21%   |
| lightdm-xsession | 2        | 1.21%   |
| X-Cinnamon       | 1        | 0.61%   |
| LXQt             | 1        | 0.61%   |
| KDE4             | 1        | 0.61%   |
| KDE              | 1        | 0.61%   |
| Unknown          | 1        | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 164      | 99.39%  |
| Tty  | 1        | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 136      | 82.42%  |
| SDDM    | 23       | 13.94%  |
| SLiM    | 3        | 1.82%   |
| TDM     | 2        | 1.21%   |
| GDM     | 1        | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 59       | 34.71%  |
| Unknown | 34       | 20%     |
| de_DE   | 17       | 10%     |
| en_GB   | 8        | 4.71%   |
| pl_PL   | 7        | 4.12%   |
| it_IT   | 7        | 4.12%   |
| sk_SK   | 5        | 2.94%   |
| pt_BR   | 5        | 2.94%   |
| es_ES   | 5        | 2.94%   |
| ru_RU   | 4        | 2.35%   |
| sv_SE   | 2        | 1.18%   |
| hu_HU   | 2        | 1.18%   |
| fr_FR   | 2        | 1.18%   |
| es_MX   | 2        | 1.18%   |
| de_CH   | 2        | 1.18%   |
| uk_UA   | 1        | 0.59%   |
| tr_TR   | 1        | 0.59%   |
| fi_FI   | 1        | 0.59%   |
| es_VE   | 1        | 0.59%   |
| es_CO   | 1        | 0.59%   |
| es_AR   | 1        | 0.59%   |
| en_NZ   | 1        | 0.59%   |
| en_IE   | 1        | 0.59%   |
| en_AU   | 1        | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 106      | 64.24%  |
| EFI  | 59       | 35.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 149      | 90.3%   |
| Overlay  | 10       | 6.06%   |
| Btrfs    | 3        | 1.82%   |
| Xfs      | 1        | 0.61%   |
| Reiserfs | 1        | 0.61%   |
| Ext3     | 1        | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 87       | 52.41%  |
| MBR     | 77       | 46.39%  |
| Unknown | 2        | 1.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 63.31%  |
| Yes       | 62       | 36.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 91       | 55.15%  |
| No        | 74       | 44.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 34       | 20.61%  |
| Gigabyte Technology                  | 26       | 15.76%  |
| MSI                                  | 21       | 12.73%  |
| Dell                                 | 19       | 11.52%  |
| ASRock                               | 16       | 9.7%    |
| Hewlett-Packard                      | 10       | 6.06%   |
| Intel                                | 7        | 4.24%   |
| Lenovo                               | 5        | 3.03%   |
| Unknown                              | 3        | 1.82%   |
| Pegatron                             | 2        | 1.21%   |
| Fujitsu                              | 2        | 1.21%   |
| ECS                                  | 2        | 1.21%   |
| Biostar                              | 2        | 1.21%   |
| ZOTAC                                | 1        | 0.61%   |
| SLIMBOOK                             | 1        | 0.61%   |
| SIRAGON                              | 1        | 0.61%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.61%   |
| Positivo                             | 1        | 0.61%   |
| MP                                   | 1        | 0.61%   |
| Medion                               | 1        | 0.61%   |
| IBM                                  | 1        | 0.61%   |
| Huanan                               | 1        | 0.61%   |
| GreatWall                            | 1        | 0.61%   |
| Gateway                              | 1        | 0.61%   |
| GALAX                                | 1        | 0.61%   |
| Fujitsu Siemens                      | 1        | 0.61%   |
| Foxconn                              | 1        | 0.61%   |
| BESSTAR Tech                         | 1        | 0.61%   |
| AOpen                                | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 6        | 3.64%   |
| Unknown                                    | 5        | 3.03%   |
| MSI MS-7C91                                | 2        | 1.21%   |
| MSI MS-7A34                                | 2        | 1.21%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.21%   |
| Dell Studio 540                            | 2        | 1.21%   |
| Dell OptiPlex 9010                         | 2        | 1.21%   |
| Dell OptiPlex 790                          | 2        | 1.21%   |
| Dell OptiPlex 755                          | 2        | 1.21%   |
| ASUS ROG Maximus XIII HERO                 | 2        | 1.21%   |
| ASUS PRIME B450M-A                         | 2        | 1.21%   |
| ASRock K8A780LM                            | 2        | 1.21%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.61%   |
| SIRAGON AIO-5150                           | 1        | 0.61%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.61%   |
| Positivo POS-PQ45AU                        | 1        | 0.61%   |
| Pegatron FQ425AA-ABA a6655f                | 1        | 0.61%   |
| Pegatron 2AD5                              | 1        | 0.61%   |
| MSI MS-7C94                                | 1        | 0.61%   |
| MSI MS-7C88                                | 1        | 0.61%   |
| MSI MS-7C56                                | 1        | 0.61%   |
| MSI MS-7C37                                | 1        | 0.61%   |
| MSI MS-7B98                                | 1        | 0.61%   |
| MSI MS-7B86                                | 1        | 0.61%   |
| MSI MS-7B53                                | 1        | 0.61%   |
| MSI MS-7A63                                | 1        | 0.61%   |
| MSI MS-7917                                | 1        | 0.61%   |
| MSI MS-7823                                | 1        | 0.61%   |
| MSI MS-7815                                | 1        | 0.61%   |
| MSI MS-7808                                | 1        | 0.61%   |
| MSI MS-7758                                | 1        | 0.61%   |
| MSI MS-7693                                | 1        | 0.61%   |
| MSI MS-7641                                | 1        | 0.61%   |
| MSI MS-7199                                | 1        | 0.61%   |
| MSI GEG                                    | 1        | 0.61%   |
| MP MS-7848                                 | 1        | 0.61%   |
| Medion Akoya P5330 E MD8876/2458           | 1        | 0.61%   |
| Lenovo ThinkStation P620 30E0CTO1WW        | 1        | 0.61%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00   | 1        | 0.61%   |
| Lenovo ThinkCentre M58 7638CB8             | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 13       | 7.88%   |
| ASUS All                                   | 6        | 3.64%   |
| ASUS PRIME                                 | 5        | 3.03%   |
| Unknown                                    | 5        | 3.03%   |
| HP Compaq                                  | 4        | 2.42%   |
| ASUS TUF                                   | 4        | 2.42%   |
| ASUS ROG                                   | 4        | 2.42%   |
| MSI MS-7C91                                | 2        | 1.21%   |
| MSI MS-7A34                                | 2        | 1.21%   |
| Lenovo ThinkCentre                         | 2        | 1.21%   |
| Gigabyte Z390                              | 2        | 1.21%   |
| Gigabyte GA-MA785GM-US2H                   | 2        | 1.21%   |
| Gigabyte B550M                             | 2        | 1.21%   |
| Dell Studio                                | 2        | 1.21%   |
| Dell Inspiron                              | 2        | 1.21%   |
| ASUS P5GC-MX                               | 2        | 1.21%   |
| ASRock X370                                | 2        | 1.21%   |
| ASRock K8A780LM                            | 2        | 1.21%   |
| SLIMBOOK ONE-AMD-M4                        | 1        | 0.61%   |
| SIRAGON AIO-5150                           | 1        | 0.61%   |
| Shenzhen Meigao Electronic Equipment UM450 | 1        | 0.61%   |
| Positivo POS-PQ45AU                        | 1        | 0.61%   |
| Pegatron FQ425AA-ABA                       | 1        | 0.61%   |
| Pegatron 2AD5                              | 1        | 0.61%   |
| MSI MS-7C94                                | 1        | 0.61%   |
| MSI MS-7C88                                | 1        | 0.61%   |
| MSI MS-7C56                                | 1        | 0.61%   |
| MSI MS-7C37                                | 1        | 0.61%   |
| MSI MS-7B98                                | 1        | 0.61%   |
| MSI MS-7B86                                | 1        | 0.61%   |
| MSI MS-7B53                                | 1        | 0.61%   |
| MSI MS-7A63                                | 1        | 0.61%   |
| MSI MS-7917                                | 1        | 0.61%   |
| MSI MS-7823                                | 1        | 0.61%   |
| MSI MS-7815                                | 1        | 0.61%   |
| MSI MS-7808                                | 1        | 0.61%   |
| MSI MS-7758                                | 1        | 0.61%   |
| MSI MS-7693                                | 1        | 0.61%   |
| MSI MS-7641                                | 1        | 0.61%   |
| MSI MS-7199                                | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 15       | 9.09%   |
| 2013 | 15       | 9.09%   |
| 2012 | 14       | 8.48%   |
| 2020 | 13       | 7.88%   |
| 2011 | 12       | 7.27%   |
| 2019 | 10       | 6.06%   |
| 2010 | 10       | 6.06%   |
| 2021 | 9        | 5.45%   |
| 2014 | 9        | 5.45%   |
| 2009 | 9        | 5.45%   |
| 2008 | 9        | 5.45%   |
| 2016 | 8        | 4.85%   |
| 2007 | 8        | 4.85%   |
| 2022 | 7        | 4.24%   |
| 2017 | 7        | 4.24%   |
| 2015 | 5        | 3.03%   |
| 2006 | 3        | 1.82%   |
| 2005 | 2        | 1.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 165      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 165      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 165      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 40       | 24.24%  |
| 16.01-24.0  | 39       | 23.64%  |
| 4.01-8.0    | 28       | 16.97%  |
| 32.01-64.0  | 23       | 13.94%  |
| 3.01-4.0    | 18       | 10.91%  |
| 1.01-2.0    | 7        | 4.24%   |
| 24.01-32.0  | 4        | 2.42%   |
| 64.01-256.0 | 3        | 1.82%   |
| 2.01-3.0    | 2        | 1.21%   |
| 0.51-1.0    | 1        | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 60       | 35.29%  |
| 2.01-3.0   | 41       | 24.12%  |
| 3.01-4.0   | 27       | 15.88%  |
| 4.01-8.0   | 21       | 12.35%  |
| 0.51-1.0   | 13       | 7.65%   |
| 8.01-16.0  | 5        | 2.94%   |
| 0.01-0.5   | 2        | 1.18%   |
| 16.01-24.0 | 1        | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 32.94%  |
| 2      | 55       | 32.35%  |
| 3      | 31       | 18.24%  |
| 4      | 13       | 7.65%   |
| 5      | 10       | 5.88%   |
| 8      | 2        | 1.18%   |
| 7      | 1        | 0.59%   |
| 6      | 1        | 0.59%   |
| 0      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 88       | 52.69%  |
| No        | 79       | 47.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 99.39%  |
| No        | 1        | 0.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 58.79%  |
| Yes       | 68       | 41.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 78.18%  |
| Yes       | 36       | 21.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 44       | 26.67%  |
| Germany     | 16       | 9.7%    |
| Poland      | 9        | 5.45%   |
| Italy       | 9        | 5.45%   |
| Spain       | 7        | 4.24%   |
| Slovakia    | 7        | 4.24%   |
| UK          | 6        | 3.64%   |
| Russia      | 6        | 3.64%   |
| Brazil      | 6        | 3.64%   |
| France      | 5        | 3.03%   |
| Finland     | 5        | 3.03%   |
| Sweden      | 4        | 2.42%   |
| India       | 4        | 2.42%   |
| Canada      | 4        | 2.42%   |
| Australia   | 4        | 2.42%   |
| Serbia      | 3        | 1.82%   |
| Venezuela   | 2        | 1.21%   |
| Switzerland | 2        | 1.21%   |
| Netherlands | 2        | 1.21%   |
| Mexico      | 2        | 1.21%   |
| Indonesia   | 2        | 1.21%   |
| Hungary     | 2        | 1.21%   |
| Denmark     | 2        | 1.21%   |
| Ukraine     | 1        | 0.61%   |
| Turkey      | 1        | 0.61%   |
| Singapore   | 1        | 0.61%   |
| Romania     | 1        | 0.61%   |
| Philippines | 1        | 0.61%   |
| New Zealand | 1        | 0.61%   |
| Ireland     | 1        | 0.61%   |
| Greece      | 1        | 0.61%   |
| Estonia     | 1        | 0.61%   |
| Colombia    | 1        | 0.61%   |
| Austria     | 1        | 0.61%   |
| Argentina   | 1        | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 4.17%   |
| Florianópolis           | 3        | 1.79%   |
| Berlin                   | 3        | 1.79%   |
| Barcelona                | 3        | 1.79%   |
| Mesquite                 | 2        | 1.19%   |
| Krakow                   | 2        | 1.19%   |
| Houston                  | 2        | 1.19%   |
| Ettingen                 | 2        | 1.19%   |
| Espoo                    | 2        | 1.19%   |
| Centreville              | 2        | 1.19%   |
| Bengaluru                | 2        | 1.19%   |
| Belgrade                 | 2        | 1.19%   |
| Albertslund Municipality | 2        | 1.19%   |
| Yuzhno-Sakhalinsk        | 1        | 0.6%    |
| Warsaw                   | 1        | 0.6%    |
| Warren                   | 1        | 0.6%    |
| Volos                    | 1        | 0.6%    |
| Voghera                  | 1        | 0.6%    |
| Virginia Beach           | 1        | 0.6%    |
| Vilhelmina               | 1        | 0.6%    |
| Vienna                   | 1        | 0.6%    |
| Vera                     | 1        | 0.6%    |
| Vasco da Gama            | 1        | 0.6%    |
| Valencia                 | 1        | 0.6%    |
| Vaidasoo                 | 1        | 0.6%    |
| Tuglie                   | 1        | 0.6%    |
| Toronto                  | 1        | 0.6%    |
| Titusville               | 1        | 0.6%    |
| Tilburg                  | 1        | 0.6%    |
| Tampere                  | 1        | 0.6%    |
| Tacoma                   | 1        | 0.6%    |
| Sydney                   | 1        | 0.6%    |
| Stockholm                | 1        | 0.6%    |
| Stevens Point            | 1        | 0.6%    |
| Stafford                 | 1        | 0.6%    |
| St Petersburg            | 1        | 0.6%    |
| Springdale               | 1        | 0.6%    |
| Southsea                 | 1        | 0.6%    |
| Sollentuna               | 1        | 0.6%    |
| Södertälje             | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 61       | 82     | 19.18%  |
| WDC                       | 56       | 72     | 17.61%  |
| Samsung Electronics       | 47       | 74     | 14.78%  |
| Kingston                  | 27       | 29     | 8.49%   |
| Hitachi                   | 17       | 22     | 5.35%   |
| Toshiba                   | 16       | 21     | 5.03%   |
| SanDisk                   | 12       | 14     | 3.77%   |
| Crucial                   | 12       | 13     | 3.77%   |
| A-DATA Technology         | 9        | 9      | 2.83%   |
| China                     | 8        | 9      | 2.52%   |
| Maxtor                    | 5        | 6      | 1.57%   |
| GOODRAM                   | 5        | 6      | 1.57%   |
| PNY                       | 4        | 5      | 1.26%   |
| Corsair                   | 4        | 4      | 1.26%   |
| Unknown                   | 3        | 5      | 0.94%   |
| Mushkin                   | 3        | 3      | 0.94%   |
| Intel                     | 3        | 4      | 0.94%   |
| Transcend                 | 2        | 2      | 0.63%   |
| SPCC                      | 2        | 2      | 0.63%   |
| Micron/Crucial Technology | 2        | 2      | 0.63%   |
| Apacer                    | 2        | 2      | 0.63%   |
| WDC WDS1                  | 1        | 1      | 0.31%   |
| Team                      | 1        | 1      | 0.31%   |
| Silicon Motion            | 1        | 1      | 0.31%   |
| Phison Electronics        | 1        | 1      | 0.31%   |
| Phison                    | 1        | 1      | 0.31%   |
| OCZ                       | 1        | 1      | 0.31%   |
| Micron Technology         | 1        | 1      | 0.31%   |
| KingFast                  | 1        | 1      | 0.31%   |
| JMicron Technology        | 1        | 1      | 0.31%   |
| Intenso                   | 1        | 1      | 0.31%   |
| IBM/Hitachi               | 1        | 1      | 0.31%   |
| HGST                      | 1        | 1      | 0.31%   |
| Gigabyte Technology       | 1        | 1      | 0.31%   |
| Fujitsu                   | 1        | 1      | 0.31%   |
| External                  | 1        | 1      | 0.31%   |
| CT1000P3                  | 1        | 1      | 0.31%   |
| Avant                     | 1        | 1      | 0.31%   |
| Acer                      | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 6        | 1.63%   |
| Kingston SA400S37480G 480GB SSD  | 6        | 1.63%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.36%   |
| Toshiba DT01ACA100 1TB           | 4        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.08%   |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.08%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.08%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.08%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 0.81%   |
| Seagate ST3500413AS 500GB        | 3        | 0.81%   |
| SanDisk SDSSDA240G 240GB         | 3        | 0.81%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.81%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 0.81%   |
| Samsung SSD 870 EVO 500GB        | 3        | 0.81%   |
| Samsung SSD 850 EVO 500GB        | 3        | 0.81%   |
| Samsung SSD 840 Series 120GB     | 3        | 0.81%   |
| Kingston SV300S37A240G 240GB SSD | 3        | 0.81%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.81%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.54%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.54%   |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.54%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.54%   |
| WDC WD15EARX-00PASB0 1TB         | 2        | 0.54%   |
| WDC WD10EZEX-75WN4A0 1TB         | 2        | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.54%   |
| Unknown SD/MMC 2GB               | 2        | 0.54%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 2        | 0.54%   |
| Toshiba MK5065GSX 500GB          | 2        | 0.54%   |
| Toshiba HDWD110 1TB              | 2        | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB  | 2        | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.54%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.54%   |
| SanDisk SSD PLUS 1000GB          | 2        | 0.54%   |
| SanDisk SDSSDP128G 128GB         | 2        | 0.54%   |
| Samsung SSD 980 PRO 1TB          | 2        | 0.54%   |
| Samsung SSD 970 PRO 512GB        | 2        | 0.54%   |
| Samsung SSD 860 QVO 1TB          | 2        | 0.54%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.54%   |
| Samsung SSD 860 EVO 1TB          | 2        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 61       | 81     | 39.1%   |
| WDC                 | 47       | 62     | 30.13%  |
| Hitachi             | 17       | 22     | 10.9%   |
| Toshiba             | 16       | 21     | 10.26%  |
| Samsung Electronics | 5        | 6      | 3.21%   |
| Maxtor              | 5        | 6      | 3.21%   |
| Unknown             | 1        | 1      | 0.64%   |
| IBM/Hitachi         | 1        | 1      | 0.64%   |
| HGST                | 1        | 1      | 0.64%   |
| Fujitsu             | 1        | 1      | 0.64%   |
| External            | 1        | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 44     | 26.56%  |
| Kingston            | 22       | 24     | 17.19%  |
| SanDisk             | 11       | 13     | 8.59%   |
| Crucial             | 11       | 12     | 8.59%   |
| China               | 8        | 9      | 6.25%   |
| A-DATA Technology   | 8        | 8      | 6.25%   |
| WDC                 | 7        | 8      | 5.47%   |
| GOODRAM             | 5        | 6      | 3.91%   |
| PNY                 | 3        | 3      | 2.34%   |
| Transcend           | 2        | 2      | 1.56%   |
| SPCC                | 2        | 2      | 1.56%   |
| Mushkin             | 2        | 2      | 1.56%   |
| Intel               | 2        | 3      | 1.56%   |
| WDC WDS1            | 1        | 1      | 0.78%   |
| Team                | 1        | 1      | 0.78%   |
| OCZ                 | 1        | 1      | 0.78%   |
| Micron Technology   | 1        | 1      | 0.78%   |
| KingFast            | 1        | 1      | 0.78%   |
| Intenso             | 1        | 1      | 0.78%   |
| Gigabyte Technology | 1        | 1      | 0.78%   |
| CT1000P3            | 1        | 1      | 0.78%   |
| Avant               | 1        | 1      | 0.78%   |
| Apacer              | 1        | 1      | 0.78%   |
| Acer                | 1        | 1      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 118      | 203    | 44.19%  |
| SSD     | 106      | 147    | 39.7%   |
| NVMe    | 38       | 47     | 14.23%  |
| Unknown | 4        | 6      | 1.5%    |
| MMC     | 1        | 1      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 153      | 342    | 75.74%  |
| NVMe | 38       | 47     | 18.81%  |
| SAS  | 10       | 14     | 4.95%   |
| MMC  | 1        | 1      | 0.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 123      | 196    | 51.04%  |
| 0.51-1.0   | 69       | 92     | 28.63%  |
| 1.01-2.0   | 25       | 32     | 10.37%  |
| 3.01-4.0   | 9        | 10     | 3.73%   |
| 2.01-3.0   | 9        | 10     | 3.73%   |
| 4.01-10.0  | 5        | 9      | 2.07%   |
| 10.01-20.0 | 1        | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 21.05%  |
| 251-500        | 35       | 20.47%  |
| 1001-2000      | 25       | 14.62%  |
| 501-1000       | 22       | 12.87%  |
| More than 3000 | 16       | 9.36%   |
| 51-100         | 15       | 8.77%   |
| 2001-3000      | 11       | 6.43%   |
| 21-50          | 6        | 3.51%   |
| 1-20           | 5        | 2.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 41       | 24.4%   |
| 101-250        | 28       | 16.67%  |
| 21-50          | 25       | 14.88%  |
| 251-500        | 22       | 13.1%   |
| 51-100         | 15       | 8.93%   |
| 501-1000       | 14       | 8.33%   |
| 1001-2000      | 12       | 7.14%   |
| 2001-3000      | 6        | 3.57%   |
| More than 3000 | 5        | 2.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 1.75%   |
| WDC WD5003ABYX-01WERA1 500GB             | 1        | 1      | 1.75%   |
| WDC WD3200AAKS-00UU3A0 320GB             | 1        | 1      | 1.75%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 1.75%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 1.75%   |
| WDC WD20EARX-00PASB0 2TB                 | 1        | 1      | 1.75%   |
| WDC WD1600AVVS-63L2B0 160GB              | 1        | 1      | 1.75%   |
| WDC WD15EADS-11P8B2 1TB                  | 1        | 1      | 1.75%   |
| WDC WD10EZEX-75WN4A0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 1.75%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 1.75%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 1.75%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 1.75%   |
| Toshiba MK7575GSX 752GB                  | 1        | 1      | 1.75%   |
| Toshiba MK6465GSX 640GB                  | 1        | 1      | 1.75%   |
| SPCC Solid State Disk 512GB              | 1        | 1      | 1.75%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 1.75%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 1.75%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 1.75%   |
| Seagate ST3750330NS 752GB                | 1        | 1      | 1.75%   |
| Seagate ST3500820AS 500GB                | 1        | 1      | 1.75%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 1.75%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 1.75%   |
| Seagate ST3320413CS 320GB                | 1        | 1      | 1.75%   |
| Seagate ST33000651NS 3TB                 | 1        | 1      | 1.75%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 1.75%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 1.75%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 1.75%   |
| Seagate ST31000524AS 1TB                 | 1        | 1      | 1.75%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 1.75%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 1.75%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 1.75%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 1.75%   |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 1.75%   |
| Maxtor STM3500320AS 500GB                | 1        | 1      | 1.75%   |
| Maxtor 6Y120M0 120GB                     | 1        | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 18     | 29.09%  |
| WDC                 | 12       | 12     | 21.82%  |
| Samsung Electronics | 5        | 7      | 9.09%   |
| Hitachi             | 5        | 6      | 9.09%   |
| Maxtor              | 4        | 4      | 7.27%   |
| Toshiba             | 3        | 3      | 5.45%   |
| Crucial             | 2        | 2      | 3.64%   |
| SPCC                | 1        | 1      | 1.82%   |
| Intenso             | 1        | 1      | 1.82%   |
| IBM/Hitachi         | 1        | 1      | 1.82%   |
| HGST                | 1        | 1      | 1.82%   |
| GOODRAM             | 1        | 1      | 1.82%   |
| Fujitsu             | 1        | 1      | 1.82%   |
| China               | 1        | 1      | 1.82%   |
| A-DATA Technology   | 1        | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 18     | 37.21%  |
| WDC                 | 11       | 11     | 25.58%  |
| Hitachi             | 5        | 6      | 11.63%  |
| Maxtor              | 4        | 4      | 9.3%    |
| Toshiba             | 3        | 3      | 6.98%   |
| Samsung Electronics | 1        | 2      | 2.33%   |
| IBM/Hitachi         | 1        | 1      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |
| Fujitsu             | 1        | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 47     | 76.92%  |
| SSD  | 12       | 13     | 23.08%  |

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
| Works    | 145      | 319    | 68.08%  |
| Malfunc  | 49       | 60     | 23%     |
| Detected | 16       | 21     | 7.51%   |
| Failed   | 3        | 4      | 1.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 106      | 47.32%  |
| AMD                         | 50       | 22.32%  |
| Samsung Electronics         | 17       | 7.59%   |
| ASMedia Technology          | 10       | 4.46%   |
| Phison Electronics          | 8        | 3.57%   |
| JMicron Technology          | 7        | 3.13%   |
| Kingston Technology Company | 5        | 2.23%   |
| Marvell Technology Group    | 4        | 1.79%   |
| SanDisk                     | 3        | 1.34%   |
| Nvidia                      | 3        | 1.34%   |
| Micron/Crucial Technology   | 3        | 1.34%   |
| VIA Technologies            | 2        | 0.89%   |
| ULi Electronics             | 2        | 0.89%   |
| Silicon Motion              | 2        | 0.89%   |
| LSI Logic / Symbios Logic   | 1        | 0.45%   |
| ADATA Technology            | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20       | 6.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 3.47%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 3.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 3.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 2.08%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.74%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 1.74%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.39%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.39%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.39%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.39%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 1.39%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.04%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.04%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.04%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 2        | 0.69%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 2        | 0.69%   |
| ULi M5229 IDE                                                                           | 2        | 0.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 133      | 58.33%  |
| IDE  | 49       | 21.49%  |
| NVMe | 38       | 16.67%  |
| RAID | 7        | 3.07%   |
| SCSI | 1        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 110      | 66.67%  |
| AMD          | 54       | 32.73%  |
| CentaurHauls | 1        | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 3.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.42%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.42%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 1.82%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 1.82%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 1.82%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 1.21%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.21%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.21%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.21%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.21%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 1.21%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.21%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.21%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.21%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.21%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.21%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.21%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.21%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.21%   |
| AMD Phenom II X6 1090T Processor            | 2        | 1.21%   |
| AMD Phenom II X4 925 Processor              | 2        | 1.21%   |
| AMD Athlon II X4 630 Processor              | 2        | 1.21%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 0.61%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.61%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.61%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.61%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.61%   |
| Intel Pentium CPU G3240T @ 2.70GHz          | 1        | 0.61%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 0.61%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.61%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.61%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.61%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 16.97%  |
| Intel Core i7           | 21       | 12.73%  |
| AMD Ryzen 5             | 16       | 9.7%    |
| Intel Core i3           | 13       | 7.88%   |
| AMD Ryzen 7             | 10       | 6.06%   |
| Intel Core 2 Duo        | 9        | 5.45%   |
| Other                   | 6        | 3.64%   |
| Intel Xeon              | 5        | 3.03%   |
| Intel Core 2 Quad       | 5        | 3.03%   |
| Intel Pentium           | 4        | 2.42%   |
| Intel Celeron           | 4        | 2.42%   |
| Intel Pentium 4         | 3        | 1.82%   |
| Intel Core i9           | 3        | 1.82%   |
| AMD Phenom II X4        | 3        | 1.82%   |
| AMD Athlon II X4        | 3        | 1.82%   |
| AMD Athlon II X2        | 3        | 1.82%   |
| Intel Pentium Dual-Core | 2        | 1.21%   |
| AMD Sempron             | 2        | 1.21%   |
| AMD Ryzen 3             | 2        | 1.21%   |
| AMD Phenom II X6        | 2        | 1.21%   |
| AMD Phenom              | 2        | 1.21%   |
| AMD Athlon              | 2        | 1.21%   |
| Intel Pentium Gold      | 1        | 0.61%   |
| Intel Pentium Dual      | 1        | 0.61%   |
| Intel Pentium D         | 1        | 0.61%   |
| Intel Core M            | 1        | 0.61%   |
| Intel Core 2 Extreme    | 1        | 0.61%   |
| Intel Celeron D         | 1        | 0.61%   |
| Intel Atom              | 1        | 0.61%   |
| CentaurHauls VIA Esther | 1        | 0.61%   |
| AMD Ryzen Threadripper  | 1        | 0.61%   |
| AMD Ryzen 9             | 1        | 0.61%   |
| AMD Ryzen 5 PRO         | 1        | 0.61%   |
| AMD FX                  | 1        | 0.61%   |
| AMD E1                  | 1        | 0.61%   |
| AMD Athlon X4           | 1        | 0.61%   |
| AMD Athlon 64 X2        | 1        | 0.61%   |
| AMD A4                  | 1        | 0.61%   |
| AMD A10                 | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 62       | 37.58%  |
| 2      | 48       | 29.09%  |
| 6      | 24       | 14.55%  |
| 8      | 18       | 10.91%  |
| 1      | 7        | 4.24%   |
| 12     | 4        | 2.42%   |
| 10     | 2        | 1.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 164      | 99.39%  |
| 2      | 1        | 0.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 84       | 50.91%  |
| 1      | 81       | 49.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 163      | 98.79%  |
| 32-bit         | 2        | 1.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 12.12%  |
| 0x306c3    | 15       | 9.09%   |
| 0x206a7    | 12       | 7.27%   |
| 0x306a9    | 11       | 6.67%   |
| 0x1067a    | 8        | 4.85%   |
| 0x08701021 | 7        | 4.24%   |
| 0x0800820d | 6        | 3.64%   |
| 0x906ed    | 5        | 3.03%   |
| 0x506e3    | 4        | 2.42%   |
| 0x010000db | 4        | 2.42%   |
| 0xa0671    | 3        | 1.82%   |
| 0xa0653    | 3        | 1.82%   |
| 0x106e5    | 3        | 1.82%   |
| 0x08108109 | 3        | 1.82%   |
| 0x010000c8 | 3        | 1.82%   |
| 0x01000083 | 3        | 1.82%   |
| 0x906ea    | 2        | 1.21%   |
| 0x6fd      | 2        | 1.21%   |
| 0x6fb      | 2        | 1.21%   |
| 0x306f2    | 2        | 1.21%   |
| 0x20655    | 2        | 1.21%   |
| 0x10677    | 2        | 1.21%   |
| 0x08600106 | 2        | 1.21%   |
| 0x08001138 | 2        | 1.21%   |
| 0x08001137 | 2        | 1.21%   |
| 0xf65      | 1        | 0.61%   |
| 0xf64      | 1        | 0.61%   |
| 0xf4a      | 1        | 0.61%   |
| 0xf49      | 1        | 0.61%   |
| 0xf29      | 1        | 0.61%   |
| 0xa0655    | 1        | 0.61%   |
| 0x906eb    | 1        | 0.61%   |
| 0x906e9    | 1        | 0.61%   |
| 0x906a4    | 1        | 0.61%   |
| 0x90672    | 1        | 0.61%   |
| 0x706a1    | 1        | 0.61%   |
| 0x506c9    | 1        | 0.61%   |
| 0x50654    | 1        | 0.61%   |
| 0x406c3    | 1        | 0.61%   |
| 0x40651    | 1        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 21       | 12.73%  |
| Penryn        | 14       | 8.48%   |
| K10           | 14       | 8.48%   |
| SandyBridge   | 13       | 7.88%   |
| IvyBridge     | 13       | 7.88%   |
| KabyLake      | 11       | 6.67%   |
| Zen+          | 10       | 6.06%   |
| Zen 2         | 10       | 6.06%   |
| Zen           | 7        | 4.24%   |
| Skylake       | 6        | 3.64%   |
| Zen 3         | 5        | 3.03%   |
| NetBurst      | 5        | 3.03%   |
| Nehalem       | 5        | 3.03%   |
| Unknown       | 5        | 3.03%   |
| Core          | 4        | 2.42%   |
| CometLake     | 4        | 2.42%   |
| Westmere      | 3        | 1.82%   |
| K8 Hammer     | 3        | 1.82%   |
| Icelake       | 2        | 1.21%   |
| Steamroller   | 1        | 0.61%   |
| Silvermont    | 1        | 0.61%   |
| K10 Llano     | 1        | 0.61%   |
| Jaguar        | 1        | 0.61%   |
| Goldmont plus | 1        | 0.61%   |
| Goldmont      | 1        | 0.61%   |
| Excavator     | 1        | 0.61%   |
| Bulldozer     | 1        | 0.61%   |
| Broadwell     | 1        | 0.61%   |
| Bonnell       | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 68       | 37.36%  |
| Intel            | 58       | 31.87%  |
| AMD              | 55       | 30.22%  |
| VIA Technologies | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 4.79%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 3.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 3.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 3.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5        | 2.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 1.6%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                         | 3        | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.6%    |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                           | 3        | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 1.6%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 1.6%    |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 3        | 1.6%    |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 1.06%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 1.06%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.06%   |
| Nvidia GK107GL [Quadro K600]                                                | 2        | 1.06%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.06%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.06%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.06%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 1.06%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.06%   |
| Intel HD Graphics 530                                                       | 2        | 1.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.06%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 2        | 1.06%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                   | 2        | 1.06%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                           | 2        | 1.06%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                       | 2        | 1.06%   |
| AMD RS880 [Radeon HD 4200]                                                  | 2        | 1.06%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 1.06%   |
| AMD Renoir                                                                  | 2        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.06%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 1.06%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 66       | 39.29%  |
| 1 x AMD        | 50       | 29.76%  |
| 1 x Intel      | 44       | 26.19%  |
| Intel + AMD    | 3        | 1.79%   |
| 3 x AMD        | 1        | 0.6%    |
| 2 x AMD        | 1        | 0.6%    |
| 1 x VIA        | 1        | 0.6%    |
| Intel + Nvidia | 1        | 0.6%    |
| AMD + Nvidia   | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 116      | 69.88%  |
| Proprietary | 43       | 25.9%   |
| Unknown     | 7        | 4.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 57       | 33.73%  |
| 1.01-2.0   | 28       | 16.57%  |
| 0.51-1.0   | 26       | 15.38%  |
| 3.01-4.0   | 19       | 11.24%  |
| 0.01-0.5   | 16       | 9.47%   |
| 7.01-8.0   | 14       | 8.28%   |
| 5.01-6.0   | 4        | 2.37%   |
| 8.01-16.0  | 3        | 1.78%   |
| 2.01-3.0   | 2        | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 32       | 18.39%  |
| Goldstar             | 20       | 11.49%  |
| Dell                 | 19       | 10.92%  |
| Acer                 | 14       | 8.05%   |
| Hewlett-Packard      | 10       | 5.75%   |
| Philips              | 6        | 3.45%   |
| Ancor Communications | 6        | 3.45%   |
| Sony                 | 5        | 2.87%   |
| Iiyama               | 5        | 2.87%   |
| BenQ                 | 5        | 2.87%   |
| AOC                  | 5        | 2.87%   |
| ViewSonic            | 4        | 2.3%    |
| Lenovo               | 4        | 2.3%    |
| Fujitsu Siemens      | 4        | 2.3%    |
| Eizo                 | 4        | 2.3%    |
| ASUSTek Computer     | 4        | 2.3%    |
| Vestel Elektronik    | 3        | 1.72%   |
| Vizio                | 2        | 1.15%   |
| MSI                  | 2        | 1.15%   |
| Medion               | 2        | 1.15%   |
| Xiaomi               | 1        | 0.57%   |
| Videoseven           | 1        | 0.57%   |
| Sceptre Tech         | 1        | 0.57%   |
| SANYO                | 1        | 0.57%   |
| SAC                  | 1        | 0.57%   |
| RTK                  | 1        | 0.57%   |
| RIS                  | 1        | 0.57%   |
| Panasonic            | 1        | 0.57%   |
| NEC Computers        | 1        | 0.57%   |
| MiTAC                | 1        | 0.57%   |
| LG Electronics       | 1        | 0.57%   |
| IBM                  | 1        | 0.57%   |
| HYO                  | 1        | 0.57%   |
| Grundig              | 1        | 0.57%   |
| Gigabyte Technology  | 1        | 0.57%   |
| DTV                  | 1        | 0.57%   |
| CTV                  | 1        | 0.57%   |
| Arnos Instruments    | 1        | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 3.31%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 3        | 1.66%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                      | 2        | 1.1%    |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch       | 2        | 1.1%    |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                    | 2        | 1.1%    |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                   | 2        | 1.1%    |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2        | 1.1%    |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch        | 2        | 1.1%    |
| Xiaomi Mi TV XMD004A 1360x768 708x398mm 32.0-inch                       | 1        | 0.55%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                      | 1        | 0.55%   |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                      | 1        | 0.55%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                  | 1        | 0.55%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 0.55%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 0.55%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1        | 0.55%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                 | 1        | 0.55%   |
| Sony TV SNY0801 1360x768                                                | 1        | 0.55%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                    | 1        | 0.55%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                      | 1        | 0.55%   |
| Sceptre Tech E225W-1920 SPT08D5 1920x1080 443x249mm 20.0-inch           | 1        | 0.55%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                       | 1        | 0.55%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0594 1680x1050 459x296mm 21.5-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch     | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch     | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch    | 1        | 0.55%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch      | 1        | 0.55%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch        | 1        | 0.55%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.55%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.55%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch       | 1        | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SMT24A550                               | 1        | 0.55%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 70       | 40.94%  |
| 1280x1024 (SXGA)   | 16       | 9.36%   |
| 2560x1440 (QHD)    | 15       | 8.77%   |
| 3840x2160 (4K)     | 14       | 8.19%   |
| 1680x1050 (WSXGA+) | 14       | 8.19%   |
| 1600x1200          | 7        | 4.09%   |
| 1366x768 (WXGA)    | 7        | 4.09%   |
| 1440x900 (WXGA+)   | 5        | 2.92%   |
| 3440x1440          | 3        | 1.75%   |
| 1920x1200 (WUXGA)  | 3        | 1.75%   |
| 1600x900 (HD+)     | 3        | 1.75%   |
| 1360x768           | 3        | 1.75%   |
| 2560x1080          | 2        | 1.17%   |
| 1280x720 (HD)      | 2        | 1.17%   |
| 1024x768 (XGA)     | 2        | 1.17%   |
| Unknown            | 2        | 1.17%   |
| 3840x1080          | 1        | 0.58%   |
| 2560x1600          | 1        | 0.58%   |
| 2048x1536          | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 27       | 15.7%   |
| 23      | 23       | 13.37%  |
| 21      | 21       | 12.21%  |
| 24      | 18       | 10.47%  |
| 22      | 12       | 6.98%   |
| 31      | 11       | 6.4%    |
| 18      | 10       | 5.81%   |
| 19      | 9        | 5.23%   |
| 17      | 7        | 4.07%   |
| 84      | 5        | 2.91%   |
| 34      | 5        | 2.91%   |
| 20      | 4        | 2.33%   |
| 15      | 4        | 2.33%   |
| 65      | 3        | 1.74%   |
| Unknown | 3        | 1.74%   |
| 72      | 1        | 0.58%   |
| 61      | 1        | 0.58%   |
| 54      | 1        | 0.58%   |
| 49      | 1        | 0.58%   |
| 47      | 1        | 0.58%   |
| 42      | 1        | 0.58%   |
| 40      | 1        | 0.58%   |
| 26      | 1        | 0.58%   |
| 25      | 1        | 0.58%   |
| 16      | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 64       | 38.32%  |
| 401-500     | 47       | 28.14%  |
| 601-700     | 12       | 7.19%   |
| 301-350     | 11       | 6.59%   |
| 351-400     | 10       | 5.99%   |
| 1001-1500   | 7        | 4.19%   |
| 1501-2000   | 6        | 3.59%   |
| 701-800     | 5        | 2.99%   |
| Unknown     | 3        | 1.8%    |
| 801-900     | 1        | 0.6%    |
| 901-1000    | 1        | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 111      | 66.87%  |
| 16/10   | 22       | 13.25%  |
| 5/4     | 16       | 9.64%   |
| 4/3     | 9        | 5.42%   |
| 21/9    | 5        | 3.01%   |
| Unknown | 2        | 1.2%    |
| 3/2     | 1        | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 65       | 38.46%  |
| 301-350        | 27       | 15.98%  |
| 151-200        | 20       | 11.83%  |
| 351-500        | 16       | 9.47%   |
| More than 1000 | 12       | 7.1%    |
| 141-150        | 12       | 7.1%    |
| 251-300        | 6        | 3.55%   |
| 501-1000       | 3        | 1.78%   |
| Unknown        | 3        | 1.78%   |
| 101-110        | 2        | 1.18%   |
| 121-130        | 1        | 0.59%   |
| 111-120        | 1        | 0.59%   |
| 91-100         | 1        | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 115      | 70.55%  |
| 101-120 | 31       | 19.02%  |
| 1-50    | 10       | 6.13%   |
| Unknown | 3        | 1.84%   |
| 161-240 | 2        | 1.23%   |
| 121-160 | 2        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 138      | 83.64%  |
| 2     | 22       | 13.33%  |
| 0     | 3        | 1.82%   |
| 3     | 2        | 1.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 98       | 42.61%  |
| Intel                    | 68       | 29.57%  |
| Qualcomm Atheros         | 15       | 6.52%   |
| Ralink Technology        | 7        | 3.04%   |
| Broadcom                 | 7        | 3.04%   |
| TP-Link                  | 6        | 2.61%   |
| Ralink                   | 5        | 2.17%   |
| Broadcom Limited         | 3        | 1.3%    |
| VIA Technologies         | 2        | 0.87%   |
| Nvidia                   | 2        | 0.87%   |
| MediaTek                 | 2        | 0.87%   |
| Marvell Technology Group | 2        | 0.87%   |
| Xiaomi                   | 1        | 0.43%   |
| U-Blox                   | 1        | 0.43%   |
| OPPO Electronics         | 1        | 0.43%   |
| NetGear                  | 1        | 0.43%   |
| Microsoft                | 1        | 0.43%   |
| Mercucys                 | 1        | 0.43%   |
| Linksys                  | 1        | 0.43%   |
| JMicron Technology       | 1        | 0.43%   |
| Edimax Technology        | 1        | 0.43%   |
| D-Link System            | 1        | 0.43%   |
| AVM                      | 1        | 0.43%   |
| ASUSTek Computer         | 1        | 0.43%   |
| Aquantia                 | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76       | 29.8%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.14%   |
| Intel Ethernet Controller I225-V                                  | 8        | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 3.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 2.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 1.96%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.96%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.96%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.96%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 1.18%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 1.18%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.18%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.18%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.18%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.18%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.18%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.78%   |
| Realtek 802.11ac NIC                                              | 2        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.78%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.78%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.78%   |
| Intel Wireless 8260                                               | 2        | 0.78%   |
| Intel Wireless 7260                                               | 2        | 0.78%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.78%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.39%   |
| U-Blox [u-blox 8]                                                 | 1        | 0.39%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.39%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.39%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 27.03%  |
| Intel                 | 17       | 22.97%  |
| Ralink Technology     | 7        | 9.46%   |
| TP-Link               | 6        | 8.11%   |
| Qualcomm Atheros      | 6        | 8.11%   |
| Ralink                | 5        | 6.76%   |
| Broadcom              | 3        | 4.05%   |
| MediaTek              | 2        | 2.7%    |
| NetGear               | 1        | 1.35%   |
| Microsoft             | 1        | 1.35%   |
| Mercucys              | 1        | 1.35%   |
| Linksys               | 1        | 1.35%   |
| Edimax Technology     | 1        | 1.35%   |
| Broadcom Limited      | 1        | 1.35%   |
| AVM                   | 1        | 1.35%   |
| ASUSTek Computer      | 1        | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                            | 5        | 6.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 3        | 4.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 3        | 4.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 4.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 3        | 4.05%   |
| Intel Wi-Fi 6 AX200                                        | 3        | 4.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3        | 4.05%   |
| Realtek 802.11ac NIC                                       | 2        | 2.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2        | 2.7%    |
| Intel Wireless 8260                                        | 2        | 2.7%    |
| Intel Wireless 7260                                        | 2        | 2.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 1.35%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                      | 1        | 1.35%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 1.35%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 1.35%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 1.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 1.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 1.35%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1        | 1.35%   |
| Realtek B1610311068                                        | 1        | 1.35%   |
| Realtek 802.11ac WLAN Adapter                              | 1        | 1.35%   |
| Ralink RT5372 Wireless Adapter                             | 1        | 1.35%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 1.35%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 1.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1        | 1.35%   |
| Ralink RT2800 802.11n PCI                                  | 1        | 1.35%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1        | 1.35%   |
| Ralink RT2561/RT61 802.11g PCI                             | 1        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 1.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1        | 1.35%   |
| Qualcomm Atheros AR922X Wireless Network Adapter           | 1        | 1.35%   |
| NetGear A6210                                              | 1        | 1.35%   |
| Microsoft XBOX ACC                                         | 1        | 1.35%   |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 1.35%   |
| MediaTek WiFi                                              | 1        | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 1        | 1.35%   |
| Linksys WUSB6300 V2                                        | 1        | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 87       | 50%     |
| Intel                    | 61       | 35.06%  |
| Qualcomm Atheros         | 9        | 5.17%   |
| Broadcom                 | 4        | 2.3%    |
| VIA Technologies         | 2        | 1.15%   |
| Nvidia                   | 2        | 1.15%   |
| Marvell Technology Group | 2        | 1.15%   |
| Broadcom Limited         | 2        | 1.15%   |
| Xiaomi                   | 1        | 0.57%   |
| OPPO Electronics         | 1        | 0.57%   |
| JMicron Technology       | 1        | 0.57%   |
| D-Link System            | 1        | 0.57%   |
| Aquantia                 | 1        | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76       | 42.22%  |
| Intel I211 Gigabit Network Connection                             | 8        | 4.44%   |
| Intel Ethernet Controller I225-V                                  | 8        | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 4.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6        | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.78%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.67%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.11%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.11%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.11%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.11%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.11%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.56%   |
| OPPO RMX3263                                                      | 1        | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.56%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.56%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.56%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.56%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.56%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 70.39%  |
| WiFi     | 68       | 29.18%  |
| Modem    | 1        | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 120      | 71.01%  |
| WiFi     | 49       | 28.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 69.7%   |
| 2     | 43       | 26.06%  |
| 3     | 7        | 4.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 135      | 81.33%  |
| Yes  | 31       | 18.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 38.89%  |
| Cambridge Silicon Radio         | 8        | 22.22%  |
| Realtek Semiconductor           | 3        | 8.33%   |
| ASUSTek Computer                | 3        | 8.33%   |
| Foxconn / Hon Hai               | 2        | 5.56%   |
| Broadcom                        | 2        | 5.56%   |
| TP-Link                         | 1        | 2.78%   |
| Qualcomm Atheros Communications | 1        | 2.78%   |
| MediaTek                        | 1        | 2.78%   |
| Apple                           | 1        | 2.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 22.22%  |
| Intel Bluetooth wireless interface                    | 5        | 13.89%  |
| Realtek Bluetooth Radio                               | 3        | 8.33%   |
| Intel AX200 Bluetooth                                 | 3        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 5.56%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 5.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 5.56%   |
| TP-Link UB500 Adapter                                 | 1        | 2.78%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 2.78%   |
| MediaTek Wireless_Device                              | 1        | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 2.78%   |
| Intel Bluetooth Device                                | 1        | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 1        | 2.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 2.78%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.78%   |
| ASUS BCM20702A0                                       | 1        | 2.78%   |
| Apple Bluetooth Host Controller                       | 1        | 2.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 105      | 37.1%   |
| AMD                     | 70       | 24.73%  |
| Nvidia                  | 63       | 22.26%  |
| Creative Labs           | 10       | 3.53%   |
| C-Media Electronics     | 8        | 2.83%   |
| VIA Technologies        | 3        | 1.06%   |
| JMTek                   | 3        | 1.06%   |
| Texas Instruments       | 2        | 0.71%   |
| ROCCAT                  | 2        | 0.71%   |
| Focusrite-Novation      | 2        | 0.71%   |
| ULi Electronics         | 1        | 0.35%   |
| TerraTec Electronic     | 1        | 0.35%   |
| Tenx Technology         | 1        | 0.35%   |
| Setek Elektronik        | 1        | 0.35%   |
| Schiit Audio            | 1        | 0.35%   |
| Razer USA               | 1        | 0.35%   |
| Microsoft               | 1        | 0.35%   |
| Logitech                | 1        | 0.35%   |
| Kingston Technology     | 1        | 0.35%   |
| GYROCOM C&C             | 1        | 0.35%   |
| GN Netcom               | 1        | 0.35%   |
| Generalplus Technology  | 1        | 0.35%   |
| Fortemedia              | 1        | 0.35%   |
| Ensoniq                 | 1        | 0.35%   |
| BEHRINGER International | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                    | 15       | 4.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 13       | 4%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 12       | 3.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 11       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 11       | 3.38%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 10       | 3.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 9        | 2.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 9        | 2.77%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 9        | 2.77%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 7        | 2.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 6        | 1.85%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 6        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                      | 6        | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 1.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 6        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 1.85%   |
| Nvidia High Definition Audio Controller                                                         | 5        | 1.54%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 1.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 1.54%   |
| Intel 200 Series PCH HD Audio                                                                   | 5        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 5        | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.54%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 5        | 1.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 4        | 1.23%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 1.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 4        | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 3        | 0.92%   |
| Nvidia TU104 HD Audio Controller                                                                | 3        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 3        | 0.92%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 3        | 0.92%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 3        | 0.92%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                    | 3        | 0.92%   |
| AMD Navi 10 HDMI Audio                                                                          | 3        | 0.92%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                           | 3        | 0.92%   |
| AMD FCH Azalia Controller                                                                       | 3        | 0.92%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                       | 2        | 0.62%   |
| ROCCAT Khan AIMO                                                                                | 2        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 37       | 20.22%  |
| Kingston                     | 31       | 16.94%  |
| Corsair                      | 24       | 13.11%  |
| Samsung Electronics          | 16       | 8.74%   |
| G.Skill                      | 16       | 8.74%   |
| SK hynix                     | 11       | 6.01%   |
| Crucial                      | 8        | 4.37%   |
| A-DATA Technology            | 6        | 3.28%   |
| Ramaxel Technology           | 5        | 2.73%   |
| Micron Technology            | 5        | 2.73%   |
| Nanya Technology             | 4        | 2.19%   |
| Patriot                      | 3        | 1.64%   |
| Unknown (ABCD)               | 2        | 1.09%   |
| Transcend                    | 2        | 1.09%   |
| Unknown                      | 2        | 1.09%   |
| Unknown (AB)                 | 1        | 0.55%   |
| Smart                        | 1        | 0.55%   |
| RZX                          | 1        | 0.55%   |
| PNY                          | 1        | 0.55%   |
| Patriot Memory (PDP Systems) | 1        | 0.55%   |
| OCZ                          | 1        | 0.55%   |
| Golden Empire                | 1        | 0.55%   |
| Elpida                       | 1        | 0.55%   |
| Axiom                        | 1        | 0.55%   |
| Avant                        | 1        | 0.55%   |
| Apacer                       | 1        | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 6        | 2.93%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 3        | 1.46%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                       | 3        | 1.46%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 3        | 1.46%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 2        | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                     | 2        | 0.98%   |
| Unknown RAM Module 2GB DIMM 667MT/s                          | 2        | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 2        | 0.98%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 2        | 0.98%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                   | 2        | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 2        | 0.98%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s        | 2        | 0.98%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2        | 0.98%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2        | 0.98%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 2        | 0.98%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 2        | 0.98%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s          | 2        | 0.98%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s         | 2        | 0.98%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 2        | 0.98%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s        | 2        | 0.98%   |
| Crucial RAM BLS8G4D32AESBK.M8FE1 8GB DIMM DDR4 3600MT/s      | 2        | 0.98%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 2        | 0.98%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s        | 2        | 0.98%   |
| Unknown                                                      | 2        | 0.98%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 1        | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 512MB DIMM SDRAM                          | 1        | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                     | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 667MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM                                  | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 62       | 37.35%  |
| DDR3    | 56       | 33.73%  |
| Unknown | 16       | 9.64%   |
| DDR2    | 15       | 9.04%   |
| SDRAM   | 9        | 5.42%   |
| DDR     | 5        | 3.01%   |
| LPDDR4  | 2        | 1.2%    |
| LPDDR3  | 1        | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 151      | 92.64%  |
| SODIMM | 12       | 7.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 29.44%  |
| 4096  | 48       | 26.67%  |
| 2048  | 34       | 18.89%  |
| 16384 | 21       | 11.67%  |
| 1024  | 14       | 7.78%   |
| 32768 | 7        | 3.89%   |
| 512   | 3        | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 17.49%  |
| 1333    | 27       | 14.75%  |
| 3200    | 13       | 7.1%    |
| 3600    | 12       | 6.56%   |
| 2133    | 11       | 6.01%   |
| 800     | 10       | 5.46%   |
| 667     | 9        | 4.92%   |
| Unknown | 7        | 3.83%   |
| 3000    | 6        | 3.28%   |
| 2400    | 6        | 3.28%   |
| 3466    | 5        | 2.73%   |
| 2667    | 5        | 2.73%   |
| 2666    | 4        | 2.19%   |
| 333     | 4        | 2.19%   |
| 3400    | 3        | 1.64%   |
| 2933    | 3        | 1.64%   |
| 2048    | 3        | 1.64%   |
| 1800    | 3        | 1.64%   |
| 49926   | 2        | 1.09%   |
| 3266    | 2        | 1.09%   |
| 1867    | 2        | 1.09%   |
| 1639    | 2        | 1.09%   |
| 1066    | 2        | 1.09%   |
| 400     | 2        | 1.09%   |
| 3866    | 1        | 0.55%   |
| 3733    | 1        | 0.55%   |
| 3100    | 1        | 0.55%   |
| 2000    | 1        | 0.55%   |
| 1866    | 1        | 0.55%   |
| 1067    | 1        | 0.55%   |
| 533     | 1        | 0.55%   |
| 200     | 1        | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Canon                 | 3        | 37.5%   |
| Brother Industries    | 2        | 25%     |
| Seiko Epson           | 1        | 12.5%   |
| Lexmark International | 1        | 12.5%   |
| Konica Minolta        | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon MF641C                  | 2        | 25%     |
| Seiko Epson L380 Series       | 1        | 12.5%   |
| Lexmark International CS417dn | 1        | 12.5%   |
| Konica Minolta 206            | 1        | 12.5%   |
| Canon MG5700 series           | 1        | 12.5%   |
| Brother MFC-7340              | 1        | 12.5%   |
| Brother DCP-L2540DW           | 1        | 12.5%   |

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
| Logitech                      | 11       | 37.93%  |
| Microsoft                     | 5        | 17.24%  |
| Sunplus Innovation Technology | 3        | 10.34%  |
| Generalplus Technology        | 2        | 6.9%    |
| Chicony Electronics           | 2        | 6.9%    |
| Trust                         | 1        | 3.45%   |
| Sunplus Technology            | 1        | 3.45%   |
| Sonix Technology              | 1        | 3.45%   |
| Huawei Technologies           | 1        | 3.45%   |
| Hewlett-Packard               | 1        | 3.45%   |
| Arkmicro Technologies         | 1        | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 4        | 13.79%  |
| Logitech Webcam C270                                    | 3        | 10.34%  |
| Sunplus HD 720P webcam                                  | 2        | 6.9%    |
| Logitech Webcam C930e                                   | 2        | 6.9%    |
| Logitech Webcam C200                                    | 2        | 6.9%    |
| Trust Widescreen 3MP Webcam                             | 1        | 3.45%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 3.45%   |
| Sunplus NexiGo N930AF FHD Webcam                        | 1        | 3.45%   |
| Sonix USB Camera                                        | 1        | 3.45%   |
| Microsoft LifeCam VX-800                                | 1        | 3.45%   |
| Logitech Webcam Pro 9000                                | 1        | 3.45%   |
| Logitech Webcam C110                                    | 1        | 3.45%   |
| Logitech HD Webcam C615                                 | 1        | 3.45%   |
| Logitech B525 HD Webcam                                 | 1        | 3.45%   |
| Huawei UVC Camera                                       | 1        | 3.45%   |
| HP Webcam HD 2300                                       | 1        | 3.45%   |
| Generalplus GENERAL WEBCAM                              | 1        | 3.45%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 3.45%   |
| Chicony HP Prem AF Webcam KQ245AA                       | 1        | 3.45%   |
| Chicony HD Webcam                                       | 1        | 3.45%   |
| Arkmicro USB2.0 PC CAMERA                               | 1        | 3.45%   |

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
| 0     | 145      | 87.88%  |
| 1     | 16       | 9.7%    |
| 3     | 2        | 1.21%   |
| 2     | 2        | 1.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 41.67%  |
| Net/wireless             | 5        | 20.83%  |
| Unassigned class         | 3        | 12.5%   |
| Communication controller | 2        | 8.33%   |
| Multimedia controller    | 1        | 4.17%   |
| Fingerprint reader       | 1        | 4.17%   |
| Dvb card                 | 1        | 4.17%   |
| Camera                   | 1        | 4.17%   |

