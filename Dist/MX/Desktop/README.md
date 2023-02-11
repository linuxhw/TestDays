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

Total: 187

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 21          | 66       | 44.9%   |
| MX 19          | 44       | 29.93%  |
| MX 20          | 22       | 14.97%  |
| MX 18          | 12       | 8.16%   |
| MX 22          | 1        | 0.68%   |
| MX 17          | 1        | 0.68%   |
| MX 16-migrated | 1        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 146      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 20       | 12.74%  |
| 5.10.0-20-amd64            | 9        | 5.73%   |
| 5.6.0-2-amd64              | 6        | 3.82%   |
| 5.14.0-4mx-amd64           | 6        | 3.82%   |
| 5.10.0-19-amd64            | 6        | 3.82%   |
| 5.10.0-13-amd64            | 5        | 3.18%   |
| 4.19.0-17-amd64            | 5        | 3.18%   |
| 5.8.0-3-amd64              | 4        | 2.55%   |
| 5.10.0-5mx-amd64           | 4        | 2.55%   |
| 5.10.0-18-amd64            | 4        | 2.55%   |
| 5.10.0-16-amd64            | 4        | 2.55%   |
| 5.10.0-15-amd64            | 4        | 2.55%   |
| 4.19.0-14-amd64            | 4        | 2.55%   |
| 5.4.0-3-amd64              | 3        | 1.91%   |
| 5.16.0-5mx-amd64           | 3        | 1.91%   |
| 4.19.0-5-amd64             | 3        | 1.91%   |
| 4.19.0-18-amd64            | 3        | 1.91%   |
| 4.19.0-13-amd64            | 3        | 1.91%   |
| 4.19.0-1-amd64             | 3        | 1.91%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 1.27%   |
| 5.14.0-3mx-amd64           | 2        | 1.27%   |
| 5.10.0-9-amd64             | 2        | 1.27%   |
| 5.10.0-11-amd64            | 2        | 1.27%   |
| 4.19.0-16-amd64            | 2        | 1.27%   |
| 4.19.0-12-amd64            | 2        | 1.27%   |
| 6.1.0-2mx-amd64            | 1        | 0.64%   |
| 6.0.5-x64v1-xanmod1        | 1        | 0.64%   |
| 6.0.0-4mx-rt-amd64         | 1        | 0.64%   |
| 6.0.0-13.3-liquorix-amd64  | 1        | 0.64%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 0.64%   |
| 5.5.0-7.1-liquorix-amd64   | 1        | 0.64%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 0.64%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 0.64%   |
| 5.5.0-050500rc1-lowlatency | 1        | 0.64%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 0.64%   |
| 5.4.10                     | 1        | 0.64%   |
| 5.3.0-10.1-liquorix-amd64  | 1        | 0.64%   |
| 5.3.0-0.bpo.2-amd64        | 1        | 0.64%   |
| 5.2.21-antix.2-amd64-smp   | 1        | 0.64%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 49       | 32.67%  |
| 4.19.0   | 45       | 30%     |
| 5.14.0   | 9        | 6%      |
| 5.6.0    | 6        | 4%      |
| 5.5.0    | 5        | 3.33%   |
| 5.16.0   | 5        | 3.33%   |
| 5.8.0    | 4        | 2.67%   |
| 5.4.0    | 3        | 2%      |
| 5.19.0   | 3        | 2%      |
| 5.15.0   | 3        | 2%      |
| 6.0.0    | 2        | 1.33%   |
| 5.8.16   | 2        | 1.33%   |
| 5.3.0    | 2        | 1.33%   |
| 6.1.0    | 1        | 0.67%   |
| 6.0.5    | 1        | 0.67%   |
| 5.4.7    | 1        | 0.67%   |
| 5.4.10   | 1        | 0.67%   |
| 5.2.21   | 1        | 0.67%   |
| 5.18.0   | 1        | 0.67%   |
| 5.11.0   | 1        | 0.67%   |
| 5.10.52  | 1        | 0.67%   |
| 5.10.111 | 1        | 0.67%   |
| 4.9.91   | 1        | 0.67%   |
| 4.18.0   | 1        | 0.67%   |
| 4.15.0   | 1        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 51       | 34%     |
| 4.19    | 45       | 30%     |
| 5.14    | 9        | 6%      |
| 5.8     | 6        | 4%      |
| 5.6     | 6        | 4%      |
| 5.5     | 5        | 3.33%   |
| 5.4     | 5        | 3.33%   |
| 5.16    | 5        | 3.33%   |
| 6.0     | 3        | 2%      |
| 5.19    | 3        | 2%      |
| 5.15    | 3        | 2%      |
| 5.3     | 2        | 1.33%   |
| 6.1     | 1        | 0.67%   |
| 5.2     | 1        | 0.67%   |
| 5.18    | 1        | 0.67%   |
| 5.11    | 1        | 0.67%   |
| 4.9     | 1        | 0.67%   |
| 4.18    | 1        | 0.67%   |
| 4.15    | 1        | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 141      | 96.58%  |
| i686   | 5        | 3.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 113      | 77.4%   |
| KDE5             | 24       | 16.44%  |
| MATE             | 2        | 1.37%   |
| lightdm-xsession | 2        | 1.37%   |
| X-Cinnamon       | 1        | 0.68%   |
| LXQt             | 1        | 0.68%   |
| KDE4             | 1        | 0.68%   |
| KDE              | 1        | 0.68%   |
| Unknown          | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 146      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 120      | 82.19%  |
| SDDM    | 20       | 13.7%   |
| SLiM    | 3        | 2.05%   |
| TDM     | 2        | 1.37%   |
| GDM     | 1        | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 51       | 33.77%  |
| Unknown | 34       | 22.52%  |
| de_DE   | 14       | 9.27%   |
| pl_PL   | 6        | 3.97%   |
| it_IT   | 6        | 3.97%   |
| en_GB   | 6        | 3.97%   |
| sk_SK   | 5        | 3.31%   |
| es_ES   | 5        | 3.31%   |
| ru_RU   | 4        | 2.65%   |
| pt_BR   | 4        | 2.65%   |
| hu_HU   | 2        | 1.32%   |
| fr_FR   | 2        | 1.32%   |
| de_CH   | 2        | 1.32%   |
| uk_UA   | 1        | 0.66%   |
| tr_TR   | 1        | 0.66%   |
| sv_SE   | 1        | 0.66%   |
| fi_FI   | 1        | 0.66%   |
| es_VE   | 1        | 0.66%   |
| es_MX   | 1        | 0.66%   |
| es_CO   | 1        | 0.66%   |
| en_NZ   | 1        | 0.66%   |
| en_IE   | 1        | 0.66%   |
| en_AU   | 1        | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 95       | 65.07%  |
| EFI  | 51       | 34.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 134      | 91.78%  |
| Overlay  | 6        | 4.11%   |
| Btrfs    | 3        | 2.05%   |
| Xfs      | 1        | 0.68%   |
| Reiserfs | 1        | 0.68%   |
| Ext3     | 1        | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 77       | 52.38%  |
| MBR     | 68       | 46.26%  |
| Unknown | 2        | 1.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 62%     |
| Yes       | 57       | 38%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 56.16%  |
| No        | 64       | 43.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 32       | 21.92%  |
| Gigabyte Technology | 24       | 16.44%  |
| MSI                 | 18       | 12.33%  |
| Dell                | 18       | 12.33%  |
| ASRock              | 15       | 10.27%  |
| Hewlett-Packard     | 8        | 5.48%   |
| Intel               | 7        | 4.79%   |
| Lenovo              | 4        | 2.74%   |
| Pegatron            | 2        | 1.37%   |
| Fujitsu             | 2        | 1.37%   |
| Biostar             | 2        | 1.37%   |
| ZOTAC               | 1        | 0.68%   |
| SIRAGON             | 1        | 0.68%   |
| MP                  | 1        | 0.68%   |
| Medion              | 1        | 0.68%   |
| IBM                 | 1        | 0.68%   |
| Huanan              | 1        | 0.68%   |
| GreatWall           | 1        | 0.68%   |
| Gateway             | 1        | 0.68%   |
| GALAX               | 1        | 0.68%   |
| Fujitsu Siemens     | 1        | 0.68%   |
| Foxconn             | 1        | 0.68%   |
| ECS                 | 1        | 0.68%   |
| BESSTAR Tech        | 1        | 0.68%   |
| AOpen               | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| ASUS All Series                             | 5        | 3.42%   |
| MSI MS-7A34                                 | 2        | 1.37%   |
| Dell Studio 540                             | 2        | 1.37%   |
| Dell OptiPlex 9010                          | 2        | 1.37%   |
| Dell OptiPlex 790                           | 2        | 1.37%   |
| Dell OptiPlex 755                           | 2        | 1.37%   |
| ASUS ROG Maximus XIII HERO                  | 2        | 1.37%   |
| ASUS PRIME B450M-A                          | 2        | 1.37%   |
| ASRock K8A780LM                             | 2        | 1.37%   |
| Unknown                                     | 2        | 1.37%   |
| SIRAGON AIO-5150                            | 1        | 0.68%   |
| Pegatron FQ425AA-ABA a6655f                 | 1        | 0.68%   |
| Pegatron 2AD5                               | 1        | 0.68%   |
| MSI MS-7C94                                 | 1        | 0.68%   |
| MSI MS-7C91                                 | 1        | 0.68%   |
| MSI MS-7C88                                 | 1        | 0.68%   |
| MSI MS-7C56                                 | 1        | 0.68%   |
| MSI MS-7C37                                 | 1        | 0.68%   |
| MSI MS-7B98                                 | 1        | 0.68%   |
| MSI MS-7B86                                 | 1        | 0.68%   |
| MSI MS-7A63                                 | 1        | 0.68%   |
| MSI MS-7917                                 | 1        | 0.68%   |
| MSI MS-7815                                 | 1        | 0.68%   |
| MSI MS-7808                                 | 1        | 0.68%   |
| MSI MS-7758                                 | 1        | 0.68%   |
| MSI MS-7693                                 | 1        | 0.68%   |
| MSI MS-7641                                 | 1        | 0.68%   |
| MSI MS-7199                                 | 1        | 0.68%   |
| MSI GEG                                     | 1        | 0.68%   |
| MP MS-7848                                  | 1        | 0.68%   |
| Medion Akoya P5330 E MD8876/2458            | 1        | 0.68%   |
| Lenovo ThinkStation P620 30E0CTO1WW         | 1        | 0.68%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00    | 1        | 0.68%   |
| Lenovo IdeaCentre Gaming5 17IAB7 90T00007US | 1        | 0.68%   |
| Lenovo 10AAS1QB0B                           | 1        | 0.68%   |
| Intel V1.3                                  | 1        | 0.68%   |
| Intel MAHOBAY                               | 1        | 0.68%   |
| Intel H81                                   | 1        | 0.68%   |
| Intel DH55TC AAE70932-303                   | 1        | 0.68%   |
| Intel DCP847SKE G80890-105                  | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 12       | 8.22%   |
| ASUS PRIME           | 5        | 3.42%   |
| ASUS All             | 5        | 3.42%   |
| ASUS ROG             | 4        | 2.74%   |
| HP Compaq            | 3        | 2.05%   |
| ASUS TUF             | 3        | 2.05%   |
| MSI MS-7A34          | 2        | 1.37%   |
| Gigabyte Z390        | 2        | 1.37%   |
| Gigabyte B550M       | 2        | 1.37%   |
| Dell Studio          | 2        | 1.37%   |
| Dell Inspiron        | 2        | 1.37%   |
| ASUS P5GC-MX         | 2        | 1.37%   |
| ASRock X370          | 2        | 1.37%   |
| ASRock K8A780LM      | 2        | 1.37%   |
| Unknown              | 2        | 1.37%   |
| SIRAGON AIO-5150     | 1        | 0.68%   |
| Pegatron FQ425AA-ABA | 1        | 0.68%   |
| Pegatron 2AD5        | 1        | 0.68%   |
| MSI MS-7C94          | 1        | 0.68%   |
| MSI MS-7C91          | 1        | 0.68%   |
| MSI MS-7C88          | 1        | 0.68%   |
| MSI MS-7C56          | 1        | 0.68%   |
| MSI MS-7C37          | 1        | 0.68%   |
| MSI MS-7B98          | 1        | 0.68%   |
| MSI MS-7B86          | 1        | 0.68%   |
| MSI MS-7A63          | 1        | 0.68%   |
| MSI MS-7917          | 1        | 0.68%   |
| MSI MS-7815          | 1        | 0.68%   |
| MSI MS-7808          | 1        | 0.68%   |
| MSI MS-7758          | 1        | 0.68%   |
| MSI MS-7693          | 1        | 0.68%   |
| MSI MS-7641          | 1        | 0.68%   |
| MSI MS-7199          | 1        | 0.68%   |
| MSI GEG              | 1        | 0.68%   |
| MP MS-7848           | 1        | 0.68%   |
| Medion Akoya         | 1        | 0.68%   |
| Lenovo ThinkStation  | 1        | 0.68%   |
| Lenovo ThinkCentre   | 1        | 0.68%   |
| Lenovo IdeaCentre    | 1        | 0.68%   |
| Lenovo 10AAS1QB0B    | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 14       | 9.59%   |
| 2013 | 14       | 9.59%   |
| 2012 | 14       | 9.59%   |
| 2020 | 12       | 8.22%   |
| 2011 | 11       | 7.53%   |
| 2019 | 10       | 6.85%   |
| 2010 | 8        | 5.48%   |
| 2009 | 8        | 5.48%   |
| 2021 | 7        | 4.79%   |
| 2016 | 7        | 4.79%   |
| 2014 | 7        | 4.79%   |
| 2008 | 7        | 4.79%   |
| 2007 | 7        | 4.79%   |
| 2017 | 6        | 4.11%   |
| 2015 | 5        | 3.42%   |
| 2022 | 4        | 2.74%   |
| 2006 | 3        | 2.05%   |
| 2005 | 2        | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 146      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 146      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 146      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 25.34%  |
| 8.01-16.0   | 37       | 25.34%  |
| 32.01-64.0  | 22       | 15.07%  |
| 4.01-8.0    | 21       | 14.38%  |
| 3.01-4.0    | 16       | 10.96%  |
| 1.01-2.0    | 6        | 4.11%   |
| 24.01-32.0  | 3        | 2.05%   |
| 64.01-256.0 | 2        | 1.37%   |
| 2.01-3.0    | 1        | 0.68%   |
| 0.51-1.0    | 1        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 49       | 32.45%  |
| 2.01-3.0   | 37       | 24.5%   |
| 3.01-4.0   | 26       | 17.22%  |
| 4.01-8.0   | 19       | 12.58%  |
| 0.51-1.0   | 13       | 8.61%   |
| 8.01-16.0  | 5        | 3.31%   |
| 16.01-24.0 | 1        | 0.66%   |
| 0.01-0.5   | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 54       | 35.76%  |
| 1      | 44       | 29.14%  |
| 3      | 28       | 18.54%  |
| 4      | 12       | 7.95%   |
| 5      | 9        | 5.96%   |
| 8      | 2        | 1.32%   |
| 6      | 1        | 0.66%   |
| 0      | 1        | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 78       | 52.7%   |
| No        | 70       | 47.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 146      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 62.33%  |
| Yes       | 55       | 37.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 82.19%  |
| Yes       | 26       | 17.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 38       | 26.03%  |
| Germany     | 13       | 8.9%    |
| Italy       | 8        | 5.48%   |
| Slovakia    | 7        | 4.79%   |
| Poland      | 7        | 4.79%   |
| UK          | 6        | 4.11%   |
| Spain       | 6        | 4.11%   |
| Russia      | 6        | 4.11%   |
| France      | 5        | 3.42%   |
| Finland     | 5        | 3.42%   |
| Brazil      | 5        | 3.42%   |
| India       | 4        | 2.74%   |
| Australia   | 4        | 2.74%   |
| Sweden      | 3        | 2.05%   |
| Serbia      | 3        | 2.05%   |
| Canada      | 3        | 2.05%   |
| Venezuela   | 2        | 1.37%   |
| Switzerland | 2        | 1.37%   |
| Netherlands | 2        | 1.37%   |
| Indonesia   | 2        | 1.37%   |
| Hungary     | 2        | 1.37%   |
| Denmark     | 2        | 1.37%   |
| Ukraine     | 1        | 0.68%   |
| Turkey      | 1        | 0.68%   |
| Romania     | 1        | 0.68%   |
| Philippines | 1        | 0.68%   |
| New Zealand | 1        | 0.68%   |
| Mexico      | 1        | 0.68%   |
| Ireland     | 1        | 0.68%   |
| Greece      | 1        | 0.68%   |
| Estonia     | 1        | 0.68%   |
| Colombia    | 1        | 0.68%   |
| Austria     | 1        | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 4.7%    |
| Barcelona                | 3        | 2.01%   |
| Houston                  | 2        | 1.34%   |
| Florianópolis           | 2        | 1.34%   |
| Ettingen                 | 2        | 1.34%   |
| Espoo                    | 2        | 1.34%   |
| Centreville              | 2        | 1.34%   |
| Berlin                   | 2        | 1.34%   |
| Bengaluru                | 2        | 1.34%   |
| Belgrade                 | 2        | 1.34%   |
| Albertslund Municipality | 2        | 1.34%   |
| Yuzhno-Sakhalinsk        | 1        | 0.67%   |
| Warsaw                   | 1        | 0.67%   |
| Warren                   | 1        | 0.67%   |
| Volos                    | 1        | 0.67%   |
| Voghera                  | 1        | 0.67%   |
| Virginia Beach           | 1        | 0.67%   |
| Vilhelmina               | 1        | 0.67%   |
| Vienna                   | 1        | 0.67%   |
| Vasco da Gama            | 1        | 0.67%   |
| Valencia                 | 1        | 0.67%   |
| Vaidasoo                 | 1        | 0.67%   |
| Tuglie                   | 1        | 0.67%   |
| Titusville               | 1        | 0.67%   |
| Tilburg                  | 1        | 0.67%   |
| Tampere                  | 1        | 0.67%   |
| Tacoma                   | 1        | 0.67%   |
| Sydney                   | 1        | 0.67%   |
| Stockholm                | 1        | 0.67%   |
| Stevens Point            | 1        | 0.67%   |
| St Petersburg            | 1        | 0.67%   |
| Springdale               | 1        | 0.67%   |
| Southsea                 | 1        | 0.67%   |
| Södertälje             | 1        | 0.67%   |
| Sibulan                  | 1        | 0.67%   |
| Serrana                  | 1        | 0.67%   |
| Seelbach                 | 1        | 0.67%   |
| San Diego                | 1        | 0.67%   |
| Rzeszów                 | 1        | 0.67%   |
| Rosporden                | 1        | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 57       | 78     | 20%     |
| WDC                       | 50       | 65     | 17.54%  |
| Samsung Electronics       | 44       | 71     | 15.44%  |
| Kingston                  | 23       | 25     | 8.07%   |
| Hitachi                   | 16       | 21     | 5.61%   |
| Toshiba                   | 15       | 20     | 5.26%   |
| Crucial                   | 11       | 12     | 3.86%   |
| SanDisk                   | 10       | 11     | 3.51%   |
| A-DATA Technology         | 9        | 9      | 3.16%   |
| Maxtor                    | 5        | 6      | 1.75%   |
| GOODRAM                   | 5        | 6      | 1.75%   |
| PNY                       | 4        | 5      | 1.4%    |
| Corsair                   | 4        | 4      | 1.4%    |
| Intel                     | 3        | 4      | 1.05%   |
| China                     | 3        | 3      | 1.05%   |
| Unknown                   | 2        | 3      | 0.7%    |
| Transcend                 | 2        | 2      | 0.7%    |
| SPCC                      | 2        | 2      | 0.7%    |
| Mushkin                   | 2        | 2      | 0.7%    |
| Micron/Crucial Technology | 2        | 2      | 0.7%    |
| Apacer                    | 2        | 2      | 0.7%    |
| WDC WDS1                  | 1        | 1      | 0.35%   |
| Phison Electronics        | 1        | 1      | 0.35%   |
| OCZ                       | 1        | 1      | 0.35%   |
| Micron Technology         | 1        | 1      | 0.35%   |
| KingFast                  | 1        | 1      | 0.35%   |
| JMicron Technology        | 1        | 1      | 0.35%   |
| Intenso                   | 1        | 1      | 0.35%   |
| IBM/Hitachi               | 1        | 1      | 0.35%   |
| HGST                      | 1        | 1      | 0.35%   |
| Gigabyte Technology       | 1        | 1      | 0.35%   |
| Fujitsu                   | 1        | 1      | 0.35%   |
| External                  | 1        | 1      | 0.35%   |
| Avant                     | 1        | 1      | 0.35%   |
| Acer                      | 1        | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 6        | 1.81%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.51%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.51%   |
| Toshiba DT01ACA100 1TB           | 4        | 1.2%    |
| Seagate ST500DM002-1BD142 500GB  | 4        | 1.2%    |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.2%    |
| Samsung SSD 850 EVO 250GB        | 4        | 1.2%    |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 0.9%    |
| Seagate ST3500413AS 500GB        | 3        | 0.9%    |
| SanDisk SDSSDA240G 240GB         | 3        | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 0.9%    |
| Samsung SSD 870 EVO 500GB        | 3        | 0.9%    |
| Samsung SSD 850 EVO 500GB        | 3        | 0.9%    |
| Kingston SV300S37A240G 240GB SSD | 3        | 0.9%    |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.9%    |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.6%    |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.6%    |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.6%    |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.6%    |
| WDC WD15EARX-00PASB0 1TB         | 2        | 0.6%    |
| WDC WD10EZEX-75WN4A0 1TB         | 2        | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.6%    |
| Toshiba MK5065GSX 500GB          | 2        | 0.6%    |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.6%    |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.6%    |
| SanDisk SSD PLUS 1000GB          | 2        | 0.6%    |
| SanDisk SDSSDP128G 128GB         | 2        | 0.6%    |
| Samsung SSD 980 PRO 1TB          | 2        | 0.6%    |
| Samsung SSD 970 PRO 512GB        | 2        | 0.6%    |
| Samsung SSD 860 QVO 1TB          | 2        | 0.6%    |
| Samsung SSD 860 EVO 250GB        | 2        | 0.6%    |
| Samsung SSD 860 EVO 1TB          | 2        | 0.6%    |
| Samsung SSD 850 EVO 1TB          | 2        | 0.6%    |
| Samsung SSD 840 Series 120GB     | 2        | 0.6%    |
| Samsung SSD 840 EVO 250GB        | 2        | 0.6%    |
| Samsung SSD 830 Series 128GB     | 2        | 0.6%    |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.6%    |
| Hitachi HUA723020ALA641 2TB      | 2        | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 57       | 77     | 39.31%  |
| WDC                 | 42       | 56     | 28.97%  |
| Hitachi             | 16       | 21     | 11.03%  |
| Toshiba             | 15       | 20     | 10.34%  |
| Samsung Electronics | 5        | 6      | 3.45%   |
| Maxtor              | 5        | 6      | 3.45%   |
| Unknown             | 1        | 1      | 0.69%   |
| IBM/Hitachi         | 1        | 1      | 0.69%   |
| HGST                | 1        | 1      | 0.69%   |
| Fujitsu             | 1        | 1      | 0.69%   |
| External            | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 32       | 42     | 28.32%  |
| Kingston            | 19       | 21     | 16.81%  |
| SanDisk             | 10       | 11     | 8.85%   |
| Crucial             | 10       | 11     | 8.85%   |
| A-DATA Technology   | 8        | 8      | 7.08%   |
| WDC                 | 7        | 8      | 6.19%   |
| GOODRAM             | 5        | 6      | 4.42%   |
| PNY                 | 3        | 3      | 2.65%   |
| China               | 3        | 3      | 2.65%   |
| Transcend           | 2        | 2      | 1.77%   |
| SPCC                | 2        | 2      | 1.77%   |
| Intel               | 2        | 3      | 1.77%   |
| WDC WDS1            | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 1      | 0.88%   |
| Mushkin             | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 1      | 0.88%   |
| KingFast            | 1        | 1      | 0.88%   |
| Intenso             | 1        | 1      | 0.88%   |
| Gigabyte Technology | 1        | 1      | 0.88%   |
| Avant               | 1        | 1      | 0.88%   |
| Apacer              | 1        | 1      | 0.88%   |
| Acer                | 1        | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 108      | 191    | 45.57%  |
| SSD     | 93       | 130    | 39.24%  |
| NVMe    | 33       | 42     | 13.92%  |
| Unknown | 3        | 4      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 137      | 314    | 76.97%  |
| NVMe | 33       | 42     | 18.54%  |
| SAS  | 8        | 11     | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 111      | 179    | 50.92%  |
| 0.51-1.0   | 62       | 85     | 28.44%  |
| 1.01-2.0   | 22       | 28     | 10.09%  |
| 2.01-3.0   | 9        | 10     | 4.13%   |
| 3.01-4.0   | 8        | 9      | 3.67%   |
| 4.01-10.0  | 5        | 9      | 2.29%   |
| 10.01-20.0 | 1        | 1      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 33       | 21.71%  |
| 101-250        | 30       | 19.74%  |
| 1001-2000      | 22       | 14.47%  |
| 501-1000       | 19       | 12.5%   |
| More than 3000 | 16       | 10.53%  |
| 51-100         | 14       | 9.21%   |
| 2001-3000      | 11       | 7.24%   |
| 21-50          | 4        | 2.63%   |
| 1-20           | 3        | 1.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 32       | 21.48%  |
| 101-250        | 27       | 18.12%  |
| 251-500        | 22       | 14.77%  |
| 21-50          | 22       | 14.77%  |
| 51-100         | 13       | 8.72%   |
| 1001-2000      | 11       | 7.38%   |
| 501-1000       | 11       | 7.38%   |
| 2001-3000      | 6        | 4.03%   |
| More than 3000 | 5        | 3.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 1.82%   |
| WDC WD5003ABYX-01WERA1 500GB             | 1        | 1      | 1.82%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 1.82%   |
| WDC WD20EARX-00PASB0 2TB                 | 1        | 1      | 1.82%   |
| WDC WD1600AVVS-63L2B0 160GB              | 1        | 1      | 1.82%   |
| WDC WD15EADS-11P8B2 1TB                  | 1        | 1      | 1.82%   |
| WDC WD10EZEX-75WN4A0 1TB                 | 1        | 1      | 1.82%   |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 1.82%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 1.82%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 1.82%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 1.82%   |
| Toshiba MK7575GSX 752GB                  | 1        | 1      | 1.82%   |
| Toshiba MK6465GSX 640GB                  | 1        | 1      | 1.82%   |
| SPCC Solid State Disk 512GB              | 1        | 1      | 1.82%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 1.82%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 1.82%   |
| Seagate ST3750330NS 752GB                | 1        | 1      | 1.82%   |
| Seagate ST3500820AS 500GB                | 1        | 1      | 1.82%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 1.82%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 1.82%   |
| Seagate ST3320413CS 320GB                | 1        | 1      | 1.82%   |
| Seagate ST33000651NS 3TB                 | 1        | 1      | 1.82%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 1.82%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 1.82%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 1.82%   |
| Seagate ST31000524AS 1TB                 | 1        | 1      | 1.82%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 1.82%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 1.82%   |
| Seagate ST1000VM002-1CT162 1TB           | 1        | 1      | 1.82%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 1.82%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 1.82%   |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 1.82%   |
| Maxtor STM3500320AS 500GB                | 1        | 1      | 1.82%   |
| Maxtor 6Y120M0 128GB                     | 1        | 1      | 1.82%   |
| Maxtor 6L200M0 208GB                     | 1        | 1      | 1.82%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 18     | 30.19%  |
| WDC                 | 10       | 10     | 18.87%  |
| Samsung Electronics | 5        | 7      | 9.43%   |
| Hitachi             | 5        | 6      | 9.43%   |
| Maxtor              | 4        | 4      | 7.55%   |
| Toshiba             | 3        | 3      | 5.66%   |
| Crucial             | 2        | 2      | 3.77%   |
| SPCC                | 1        | 1      | 1.89%   |
| Intenso             | 1        | 1      | 1.89%   |
| IBM/Hitachi         | 1        | 1      | 1.89%   |
| HGST                | 1        | 1      | 1.89%   |
| GOODRAM             | 1        | 1      | 1.89%   |
| Fujitsu             | 1        | 1      | 1.89%   |
| China               | 1        | 1      | 1.89%   |
| A-DATA Technology   | 1        | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 16       | 18     | 39.02%  |
| WDC                 | 9        | 9      | 21.95%  |
| Hitachi             | 5        | 6      | 12.2%   |
| Maxtor              | 4        | 4      | 9.76%   |
| Toshiba             | 3        | 3      | 7.32%   |
| Samsung Electronics | 1        | 2      | 2.44%   |
| IBM/Hitachi         | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |
| Fujitsu             | 1        | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 45     | 76%     |
| SSD  | 12       | 13     | 24%     |

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
| Works    | 127      | 289    | 67.2%   |
| Malfunc  | 47       | 58     | 24.87%  |
| Detected | 12       | 16     | 6.35%   |
| Failed   | 3        | 4      | 1.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 95       | 47.5%   |
| AMD                         | 44       | 22%     |
| Samsung Electronics         | 17       | 8.5%    |
| ASMedia Technology          | 9        | 4.5%    |
| Phison Electronics          | 7        | 3.5%    |
| JMicron Technology          | 7        | 3.5%    |
| Marvell Technology Group    | 4        | 2%      |
| Kingston Technology Company | 4        | 2%      |
| Nvidia                      | 3        | 1.5%    |
| Micron/Crucial Technology   | 3        | 1.5%    |
| ULi Electronics             | 2        | 1%      |
| VIA Technologies            | 1        | 0.5%    |
| Silicon Motion              | 1        | 0.5%    |
| SanDisk                     | 1        | 0.5%    |
| LSI Logic / Symbios Logic   | 1        | 0.5%    |
| ADATA Technology            | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17       | 6.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 4.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11       | 4.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10       | 3.89%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 3.5%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 9        | 3.5%    |
| AMD 500 Series Chipset SATA Controller                                         | 8        | 3.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 8        | 3.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 7        | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 2.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6        | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6        | 2.33%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6        | 2.33%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5        | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 1.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5        | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5        | 1.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 1.56%   |
| Phison E12 NVMe Controller                                                     | 4        | 1.56%   |
| Intel SATA Controller [RAID mode]                                              | 4        | 1.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 4        | 1.56%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 4        | 1.56%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 4        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 4        | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.17%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3        | 1.17%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 1.17%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 1.17%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 3        | 1.17%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 3        | 1.17%   |
| AMD 300 Series Chipset SATA Controller                                         | 3        | 1.17%   |
| ULi M5229 IDE                                                                  | 2        | 0.78%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 0.78%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 0.78%   |
| Nvidia MCP61 IDE                                                               | 2        | 0.78%   |
| JMicron JMB368 IDE controller                                                  | 2        | 0.78%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2        | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 120      | 59.7%   |
| IDE  | 41       | 20.4%   |
| NVMe | 33       | 16.42%  |
| RAID | 6        | 2.99%   |
| SCSI | 1        | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 98       | 67.12%  |
| AMD          | 47       | 32.19%  |
| CentaurHauls | 1        | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 3.42%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.05%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 2.05%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 1.37%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.37%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.37%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.37%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 1.37%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 2        | 1.37%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.37%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.37%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 2        | 1.37%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 1.37%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.37%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.37%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.37%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.37%   |
| AMD Phenom II X6 1090T Processor            | 2        | 1.37%   |
| AMD Phenom II X4 925 Processor              | 2        | 1.37%   |
| Intel Xeon W-2123 CPU @ 3.60GHz             | 1        | 0.68%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.68%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.68%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.68%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.68%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.68%   |
| Intel Pentium CPU G3240T @ 2.70GHz          | 1        | 0.68%   |
| Intel Pentium CPU 2030M @ 2.50GHz           | 1        | 0.68%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.68%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.68%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 0.68%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.68%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.68%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.68%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.68%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 25       | 17.12%  |
| Intel Core i7           | 19       | 13.01%  |
| Intel Core i3           | 12       | 8.22%   |
| AMD Ryzen 5             | 12       | 8.22%   |
| AMD Ryzen 7             | 9        | 6.16%   |
| Intel Core 2 Duo        | 7        | 4.79%   |
| Other                   | 5        | 3.42%   |
| Intel Xeon              | 5        | 3.42%   |
| Intel Core 2 Quad       | 5        | 3.42%   |
| Intel Pentium           | 4        | 2.74%   |
| Intel Core i9           | 3        | 2.05%   |
| AMD Phenom II X4        | 3        | 2.05%   |
| AMD Athlon II X2        | 3        | 2.05%   |
| Intel Pentium Dual-Core | 2        | 1.37%   |
| Intel Pentium 4         | 2        | 1.37%   |
| Intel Celeron           | 2        | 1.37%   |
| AMD Sempron             | 2        | 1.37%   |
| AMD Ryzen 3             | 2        | 1.37%   |
| AMD Phenom II X6        | 2        | 1.37%   |
| AMD Athlon II X4        | 2        | 1.37%   |
| AMD Athlon              | 2        | 1.37%   |
| Intel Pentium Gold      | 1        | 0.68%   |
| Intel Pentium Dual      | 1        | 0.68%   |
| Intel Pentium D         | 1        | 0.68%   |
| Intel Core M            | 1        | 0.68%   |
| Intel Core 2 Extreme    | 1        | 0.68%   |
| Intel Celeron D         | 1        | 0.68%   |
| Intel Atom              | 1        | 0.68%   |
| CentaurHauls VIA Esther | 1        | 0.68%   |
| AMD Ryzen Threadripper  | 1        | 0.68%   |
| AMD Ryzen 9             | 1        | 0.68%   |
| AMD Ryzen 5 PRO         | 1        | 0.68%   |
| AMD Phenom              | 1        | 0.68%   |
| AMD FX                  | 1        | 0.68%   |
| AMD E1                  | 1        | 0.68%   |
| AMD Athlon X4           | 1        | 0.68%   |
| AMD Athlon 64 X2        | 1        | 0.68%   |
| AMD A4                  | 1        | 0.68%   |
| AMD A10                 | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 56       | 38.36%  |
| 2      | 43       | 29.45%  |
| 6      | 19       | 13.01%  |
| 8      | 17       | 11.64%  |
| 1      | 6        | 4.11%   |
| 12     | 4        | 2.74%   |
| 10     | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 145      | 99.32%  |
| 2      | 1        | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 76       | 52.05%  |
| 1      | 70       | 47.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 144      | 98.63%  |
| 32-bit         | 2        | 1.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 18       | 12.33%  |
| 0x306c3    | 13       | 8.9%    |
| 0x306a9    | 11       | 7.53%   |
| 0x206a7    | 11       | 7.53%   |
| 0x1067a    | 7        | 4.79%   |
| 0x08701021 | 7        | 4.79%   |
| 0x906ed    | 5        | 3.42%   |
| 0x0800820d | 5        | 3.42%   |
| 0x506e3    | 4        | 2.74%   |
| 0xa0671    | 3        | 2.05%   |
| 0xa0653    | 3        | 2.05%   |
| 0x08108109 | 3        | 2.05%   |
| 0x010000db | 3        | 2.05%   |
| 0x010000c8 | 3        | 2.05%   |
| 0x6fd      | 2        | 1.37%   |
| 0x6fb      | 2        | 1.37%   |
| 0x306f2    | 2        | 1.37%   |
| 0x20655    | 2        | 1.37%   |
| 0x106e5    | 2        | 1.37%   |
| 0x10677    | 2        | 1.37%   |
| 0x08001138 | 2        | 1.37%   |
| 0x01000083 | 2        | 1.37%   |
| 0xf65      | 1        | 0.68%   |
| 0xf64      | 1        | 0.68%   |
| 0xf4a      | 1        | 0.68%   |
| 0xf29      | 1        | 0.68%   |
| 0xa0655    | 1        | 0.68%   |
| 0x906eb    | 1        | 0.68%   |
| 0x906ea    | 1        | 0.68%   |
| 0x906e9    | 1        | 0.68%   |
| 0x90672    | 1        | 0.68%   |
| 0x50654    | 1        | 0.68%   |
| 0x406c3    | 1        | 0.68%   |
| 0x40651    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x306d4    | 1        | 0.68%   |
| 0x30661    | 1        | 0.68%   |
| 0x206d7    | 1        | 0.68%   |
| 0x20652    | 1        | 0.68%   |
| 0x106a5    | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 19       | 13.01%  |
| IvyBridge   | 13       | 8.9%    |
| SandyBridge | 12       | 8.22%   |
| Penryn      | 12       | 8.22%   |
| K10         | 12       | 8.22%   |
| KabyLake    | 10       | 6.85%   |
| Zen+        | 9        | 6.16%   |
| Zen 2       | 8        | 5.48%   |
| Zen         | 6        | 4.11%   |
| Skylake     | 5        | 3.42%   |
| Zen 3       | 4        | 2.74%   |
| NetBurst    | 4        | 2.74%   |
| Nehalem     | 4        | 2.74%   |
| Core        | 4        | 2.74%   |
| CometLake   | 4        | 2.74%   |
| Unknown     | 4        | 2.74%   |
| Westmere    | 3        | 2.05%   |
| K8 Hammer   | 3        | 2.05%   |
| Icelake     | 2        | 1.37%   |
| Steamroller | 1        | 0.68%   |
| Silvermont  | 1        | 0.68%   |
| K10 Llano   | 1        | 0.68%   |
| Jaguar      | 1        | 0.68%   |
| Excavator   | 1        | 0.68%   |
| Bulldozer   | 1        | 0.68%   |
| Broadwell   | 1        | 0.68%   |
| Bonnell     | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 64       | 39.51%  |
| Intel            | 49       | 30.25%  |
| AMD              | 48       | 29.63%  |
| VIA Technologies | 1        | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9        | 5.36%   |
| Nvidia GK208B [GeForce GT 710]                                                | 7        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 5        | 2.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 5        | 2.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 4        | 2.38%   |
| Nvidia GT218 [GeForce 210]                                                    | 3        | 1.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 3        | 1.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 3        | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                           | 3        | 1.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 3        | 1.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3        | 1.79%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                             | 3        | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3        | 1.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 3        | 1.79%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                            | 3        | 1.79%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 2        | 1.19%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 2        | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2        | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 1.19%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.19%   |
| Nvidia GK107GL [Quadro K600]                                                  | 2        | 1.19%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 2        | 1.19%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 2        | 1.19%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 2        | 1.19%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 2        | 1.19%   |
| Intel HD Graphics 530                                                         | 2        | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 1.19%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 2        | 1.19%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 2        | 1.19%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 2        | 1.19%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 2        | 1.19%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 2        | 1.19%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2        | 1.19%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2        | 1.19%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 1.19%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2        | 1.19%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.6%    |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 63       | 42.28%  |
| 1 x AMD        | 44       | 29.53%  |
| 1 x Intel      | 35       | 23.49%  |
| Intel + AMD    | 3        | 2.01%   |
| 3 x AMD        | 1        | 0.67%   |
| 2 x AMD        | 1        | 0.67%   |
| 1 x VIA        | 1        | 0.67%   |
| Intel + Nvidia | 1        | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 100      | 68.03%  |
| Proprietary | 41       | 27.89%  |
| Unknown     | 6        | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 47       | 31.33%  |
| 1.01-2.0   | 28       | 18.67%  |
| 0.51-1.0   | 25       | 16.67%  |
| 3.01-4.0   | 16       | 10.67%  |
| 7.01-8.0   | 14       | 9.33%   |
| 0.01-0.5   | 11       | 7.33%   |
| 5.01-6.0   | 4        | 2.67%   |
| 8.01-16.0  | 3        | 2%      |
| 2.01-3.0   | 2        | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 29       | 18.71%  |
| Goldstar             | 19       | 12.26%  |
| Dell                 | 17       | 10.97%  |
| Acer                 | 14       | 9.03%   |
| Hewlett-Packard      | 8        | 5.16%   |
| Ancor Communications | 6        | 3.87%   |
| ViewSonic            | 4        | 2.58%   |
| Sony                 | 4        | 2.58%   |
| Philips              | 4        | 2.58%   |
| Lenovo               | 4        | 2.58%   |
| Iiyama               | 4        | 2.58%   |
| Fujitsu Siemens      | 4        | 2.58%   |
| Eizo                 | 4        | 2.58%   |
| AOC                  | 4        | 2.58%   |
| Vestel Elektronik    | 3        | 1.94%   |
| BenQ                 | 3        | 1.94%   |
| ASUSTek Computer     | 3        | 1.94%   |
| Vizio                | 2        | 1.29%   |
| MSI                  | 2        | 1.29%   |
| Medion               | 2        | 1.29%   |
| Videoseven           | 1        | 0.65%   |
| Sceptre Tech         | 1        | 0.65%   |
| SANYO                | 1        | 0.65%   |
| SAC                  | 1        | 0.65%   |
| RTK                  | 1        | 0.65%   |
| RIS                  | 1        | 0.65%   |
| Panasonic            | 1        | 0.65%   |
| NEC Computers        | 1        | 0.65%   |
| MiTAC                | 1        | 0.65%   |
| IBM                  | 1        | 0.65%   |
| HYO                  | 1        | 0.65%   |
| Grundig              | 1        | 0.65%   |
| Gigabyte Technology  | 1        | 0.65%   |
| DTV                  | 1        | 0.65%   |
| Arnos Instruments    | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 3.7%    |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch   | 3        | 1.85%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch       | 2        | 1.23%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                    | 2        | 1.23%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                   | 2        | 1.23%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2        | 1.23%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch        | 2        | 1.23%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                      | 1        | 0.62%   |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 1        | 0.62%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                  | 1        | 0.62%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 0.62%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 0.62%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1        | 0.62%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                 | 1        | 0.62%   |
| Sony TV SNY0801 1360x768                                                | 1        | 0.62%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                      | 1        | 0.62%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                    | 1        | 0.62%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                      | 1        | 0.62%   |
| Sceptre Tech E22 SPT08D5 1920x1080 470x300mm 22.0-inch                  | 1        | 0.62%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                       | 1        | 0.62%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch       | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch     | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch     | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch    | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch    | 1        | 0.62%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch    | 1        | 0.62%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch      | 1        | 0.62%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch        | 1        | 0.62%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 1        | 0.62%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.62%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch       | 1        | 0.62%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.62%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.62%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 950x540mm 43.0-inch   | 1        | 0.62%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1        | 0.62%   |
| Samsung Electronics C27JG5x SAM0F57 2560x1440 597x336mm 27.0-inch       | 1        | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 66       | 43.42%  |
| 2560x1440 (QHD)    | 13       | 8.55%   |
| 1280x1024 (SXGA)   | 13       | 8.55%   |
| 3840x2160 (4K)     | 12       | 7.89%   |
| 1680x1050 (WSXGA+) | 11       | 7.24%   |
| 1600x1200          | 7        | 4.61%   |
| 1440x900 (WXGA+)   | 5        | 3.29%   |
| 1366x768 (WXGA)    | 5        | 3.29%   |
| 3440x1440          | 3        | 1.97%   |
| 1920x1200 (WUXGA)  | 3        | 1.97%   |
| 1600x900 (HD+)     | 3        | 1.97%   |
| 1360x768           | 3        | 1.97%   |
| 2560x1080          | 2        | 1.32%   |
| 1280x720 (HD)      | 2        | 1.32%   |
| 1024x768 (XGA)     | 2        | 1.32%   |
| 2560x1600          | 1        | 0.66%   |
| 2048x1536          | 1        | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 24       | 15.48%  |
| 23      | 21       | 13.55%  |
| 21      | 20       | 12.9%   |
| 24      | 17       | 10.97%  |
| 31      | 11       | 7.1%    |
| 22      | 10       | 6.45%   |
| 19      | 9        | 5.81%   |
| 18      | 8        | 5.16%   |
| 84      | 5        | 3.23%   |
| 34      | 5        | 3.23%   |
| 17      | 5        | 3.23%   |
| 20      | 4        | 2.58%   |
| 15      | 4        | 2.58%   |
| 65      | 2        | 1.29%   |
| 72      | 1        | 0.65%   |
| 54      | 1        | 0.65%   |
| 49      | 1        | 0.65%   |
| 47      | 1        | 0.65%   |
| 42      | 1        | 0.65%   |
| 40      | 1        | 0.65%   |
| 26      | 1        | 0.65%   |
| 25      | 1        | 0.65%   |
| 16      | 1        | 0.65%   |
| Unknown | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 58       | 38.67%  |
| 401-500     | 43       | 28.67%  |
| 601-700     | 12       | 8%      |
| 351-400     | 9        | 6%      |
| 301-350     | 9        | 6%      |
| 1501-2000   | 6        | 4%      |
| 701-800     | 5        | 3.33%   |
| 1001-1500   | 5        | 3.33%   |
| 801-900     | 1        | 0.67%   |
| 901-1000    | 1        | 0.67%   |
| Unknown     | 1        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 102      | 68.46%  |
| 16/10 | 19       | 12.75%  |
| 5/4   | 13       | 8.72%   |
| 4/3   | 9        | 6.04%   |
| 21/9  | 5        | 3.36%   |
| 3/2   | 1        | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 59       | 38.82%  |
| 301-350        | 24       | 15.79%  |
| 151-200        | 19       | 12.5%   |
| 351-500        | 16       | 10.53%  |
| More than 1000 | 10       | 6.58%   |
| 141-150        | 9        | 5.92%   |
| 251-300        | 6        | 3.95%   |
| 501-1000       | 3        | 1.97%   |
| 101-110        | 2        | 1.32%   |
| 121-130        | 1        | 0.66%   |
| 111-120        | 1        | 0.66%   |
| 91-100         | 1        | 0.66%   |
| Unknown        | 1        | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 104      | 71.72%  |
| 101-120 | 29       | 20%     |
| 1-50    | 8        | 5.52%   |
| 121-160 | 2        | 1.38%   |
| 161-240 | 1        | 0.69%   |
| Unknown | 1        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 122      | 83.56%  |
| 2     | 20       | 13.7%   |
| 3     | 2        | 1.37%   |
| 0     | 2        | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 86       | 43.22%  |
| Intel                    | 58       | 29.15%  |
| Qualcomm Atheros         | 13       | 6.53%   |
| Broadcom                 | 7        | 3.52%   |
| Ralink Technology        | 6        | 3.02%   |
| TP-Link                  | 5        | 2.51%   |
| Ralink                   | 5        | 2.51%   |
| Nvidia                   | 2        | 1.01%   |
| Marvell Technology Group | 2        | 1.01%   |
| Broadcom Limited         | 2        | 1.01%   |
| Xiaomi                   | 1        | 0.5%    |
| VIA Technologies         | 1        | 0.5%    |
| U-Blox                   | 1        | 0.5%    |
| OPPO Electronics         | 1        | 0.5%    |
| NetGear                  | 1        | 0.5%    |
| Mercucys                 | 1        | 0.5%    |
| Linksys                  | 1        | 0.5%    |
| JMicron Technology       | 1        | 0.5%    |
| Edimax Technology        | 1        | 0.5%    |
| D-Link System            | 1        | 0.5%    |
| AVM                      | 1        | 0.5%    |
| ASUSTek Computer         | 1        | 0.5%    |
| Aquantia                 | 1        | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 30.59%  |
| Intel I211 Gigabit Network Connection                             | 8        | 3.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 3.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.28%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.83%   |
| Ralink MT7601U Wireless Adapter                                   | 4        | 1.83%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.83%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.83%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 1.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 1.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 0.91%   |
| Realtek 802.11ac NIC                                              | 2        | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.91%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.91%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.91%   |
| Intel Wireless 8260                                               | 2        | 0.91%   |
| Intel Wireless 7260                                               | 2        | 0.91%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 0.91%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.91%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.91%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.46%   |
| U-Blox [u-blox 8]                                                 | 1        | 0.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.46%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.46%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.46%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.46%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 25.86%  |
| Intel                 | 13       | 22.41%  |
| Ralink Technology     | 6        | 10.34%  |
| TP-Link               | 5        | 8.62%   |
| Ralink                | 5        | 8.62%   |
| Qualcomm Atheros      | 4        | 6.9%    |
| Broadcom              | 3        | 5.17%   |
| NetGear               | 1        | 1.72%   |
| Mercucys              | 1        | 1.72%   |
| Linksys               | 1        | 1.72%   |
| Edimax Technology     | 1        | 1.72%   |
| Broadcom Limited      | 1        | 1.72%   |
| AVM                   | 1        | 1.72%   |
| ASUSTek Computer      | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                               | 4        | 6.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 5.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 3        | 5.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3        | 5.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 3.45%   |
| Realtek 802.11ac NIC                                                                          | 2        | 3.45%   |
| Intel Wireless 8260                                                                           | 2        | 3.45%   |
| Intel Wireless 7260                                                                           | 2        | 3.45%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 3.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 1.72%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 1.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.72%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 1.72%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 1.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 1.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 1        | 1.72%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.72%   |
| Realtek B1610311068                                                                           | 1        | 1.72%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1        | 1.72%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 1.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 1.72%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 1.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 1        | 1.72%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 1        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1        | 1.72%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 1.72%   |
| NetGear A6210                                                                                 | 1        | 1.72%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 1.72%   |
| Linksys WUSB6300 V2                                                                           | 1        | 1.72%   |
| Intel Wireless 7265                                                                           | 1        | 1.72%   |
| Intel Wireless 3160                                                                           | 1        | 1.72%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 1.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 1        | 1.72%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 1        | 1.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 78       | 50.32%  |
| Intel                    | 53       | 34.19%  |
| Qualcomm Atheros         | 9        | 5.81%   |
| Broadcom                 | 4        | 2.58%   |
| Nvidia                   | 2        | 1.29%   |
| Marvell Technology Group | 2        | 1.29%   |
| Xiaomi                   | 1        | 0.65%   |
| VIA Technologies         | 1        | 0.65%   |
| OPPO Electronics         | 1        | 0.65%   |
| JMicron Technology       | 1        | 0.65%   |
| D-Link System            | 1        | 0.65%   |
| Broadcom Limited         | 1        | 0.65%   |
| Aquantia                 | 1        | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67       | 41.88%  |
| Intel I211 Gigabit Network Connection                             | 8        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 2.5%    |
| Intel Ethernet Controller I225-V                                  | 4        | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.5%    |
| Intel Ethernet Connection (2) I218-V                              | 4        | 2.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.88%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.25%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 1.25%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.25%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.25%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.25%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.63%   |
| OPPO SDM710-MTP _SN:2396E2D4                                      | 1        | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.63%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1        | 0.63%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.63%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.63%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.63%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.63%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.63%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 146      | 72.28%  |
| WiFi     | 55       | 27.23%  |
| Modem    | 1        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 110      | 73.83%  |
| WiFi     | 39       | 26.17%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 71.92%  |
| 2     | 35       | 23.97%  |
| 3     | 6        | 4.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 126      | 85.71%  |
| Yes  | 21       | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 42.31%  |
| Cambridge Silicon Radio         | 7        | 26.92%  |
| ASUSTek Computer                | 3        | 11.54%  |
| Realtek Semiconductor           | 1        | 3.85%   |
| Qualcomm Atheros Communications | 1        | 3.85%   |
| Foxconn / Hon Hai               | 1        | 3.85%   |
| Broadcom                        | 1        | 3.85%   |
| Apple                           | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 26.92%  |
| Intel Bluetooth wireless interface                    | 5        | 19.23%  |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 7.69%   |
| Intel AX200 Bluetooth                                 | 2        | 7.69%   |
| Realtek Bluetooth Radio                               | 1        | 3.85%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 3.85%   |
| Intel Bluetooth Device                                | 1        | 3.85%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 3.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 3.85%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 3.85%   |
| ASUS BCM20702A0                                       | 1        | 3.85%   |
| Apple Bluetooth USB Host Controller                   | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 94       | 36.15%  |
| AMD                     | 63       | 24.23%  |
| Nvidia                  | 62       | 23.85%  |
| Creative Labs           | 10       | 3.85%   |
| C-Media Electronics     | 7        | 2.69%   |
| JMTek                   | 3        | 1.15%   |
| Texas Instruments       | 2        | 0.77%   |
| ROCCAT                  | 2        | 0.77%   |
| Focusrite-Novation      | 2        | 0.77%   |
| VIA Technologies        | 1        | 0.38%   |
| Unknown                 | 1        | 0.38%   |
| ULi Electronics         | 1        | 0.38%   |
| TerraTec Electronic     | 1        | 0.38%   |
| Tenx Technology         | 1        | 0.38%   |
| Schiit Audio            | 1        | 0.38%   |
| Razer USA               | 1        | 0.38%   |
| Microsoft               | 1        | 0.38%   |
| Logitech                | 1        | 0.38%   |
| Kingston Technology     | 1        | 0.38%   |
| GYROCOM C&C             | 1        | 0.38%   |
| GN Netcom               | 1        | 0.38%   |
| Generalplus Technology  | 1        | 0.38%   |
| Fortemedia              | 1        | 0.38%   |
| BEHRINGER International | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 13       | 4.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 13       | 4.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 10       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 10       | 3.39%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 10       | 3.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 10       | 3.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 9        | 3.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 7        | 2.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 6        | 2.03%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 6        | 2.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 2.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 2.03%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 6        | 2.03%   |
| Nvidia High Definition Audio Controller                                                         | 5        | 1.69%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                      | 5        | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 5        | 1.69%   |
| Intel 200 Series PCH HD Audio                                                                   | 5        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 5        | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 5        | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 5        | 1.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 5        | 1.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 4        | 1.36%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 4        | 1.36%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 4        | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 3        | 1.02%   |
| Nvidia TU104 HD Audio Controller                                                                | 3        | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 3        | 1.02%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 3        | 1.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 3        | 1.02%   |
| AMD Navi 10 HDMI Audio                                                                          | 3        | 1.02%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                           | 3        | 1.02%   |
| AMD FCH Azalia Controller                                                                       | 3        | 1.02%   |
| ROCCAT Khan AIMO                                                                                | 2        | 0.68%   |
| Nvidia MCP61 High Definition Audio                                                              | 2        | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                                              | 2        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 2        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 32       | 20.13%  |
| Kingston                     | 28       | 17.61%  |
| Corsair                      | 23       | 14.47%  |
| Samsung Electronics          | 15       | 9.43%   |
| G.Skill                      | 15       | 9.43%   |
| SK hynix                     | 11       | 6.92%   |
| Crucial                      | 6        | 3.77%   |
| Ramaxel Technology           | 4        | 2.52%   |
| Nanya Technology             | 4        | 2.52%   |
| Micron Technology            | 4        | 2.52%   |
| Patriot                      | 3        | 1.89%   |
| A-DATA Technology            | 3        | 1.89%   |
| Transcend                    | 2        | 1.26%   |
| Smart                        | 1        | 0.63%   |
| RZX                          | 1        | 0.63%   |
| PNY                          | 1        | 0.63%   |
| Patriot Memory (PDP Systems) | 1        | 0.63%   |
| OCZ                          | 1        | 0.63%   |
| Elpida                       | 1        | 0.63%   |
| Axiom                        | 1        | 0.63%   |
| Apacer                       | 1        | 0.63%   |
| Unknown                      | 1        | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 6        | 3.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 3        | 1.69%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 3        | 1.69%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s  | 3        | 1.69%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 2        | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 2        | 1.12%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 2        | 1.12%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s             | 2        | 1.12%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s  | 2        | 1.12%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s   | 2        | 1.12%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 2        | 1.12%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s    | 2        | 1.12%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s   | 2        | 1.12%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s    | 2        | 1.12%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s  | 2        | 1.12%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s | 2        | 1.12%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s  | 2        | 1.12%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.56%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                   | 1        | 0.56%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s           | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s              | 1        | 0.56%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s              | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s               | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM 667MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 4GB DIMM                            | 1        | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 1        | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s             | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s            | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s             | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s             | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR                     | 1        | 0.56%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 1        | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 54       | 37.5%   |
| DDR3    | 52       | 36.11%  |
| Unknown | 14       | 9.72%   |
| DDR2    | 12       | 8.33%   |
| SDRAM   | 7        | 4.86%   |
| DDR     | 5        | 3.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 136      | 95.1%   |
| SODIMM | 7        | 4.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 49       | 31.21%  |
| 4096  | 46       | 29.3%   |
| 2048  | 26       | 16.56%  |
| 16384 | 17       | 10.83%  |
| 1024  | 11       | 7.01%   |
| 32768 | 5        | 3.18%   |
| 512   | 3        | 1.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 18.01%  |
| 1333    | 24       | 14.91%  |
| 3600    | 11       | 6.83%   |
| 2133    | 11       | 6.83%   |
| 3200    | 10       | 6.21%   |
| 800     | 9        | 5.59%   |
| 667     | 7        | 4.35%   |
| Unknown | 6        | 3.73%   |
| 3466    | 5        | 3.11%   |
| 3000    | 5        | 3.11%   |
| 2667    | 4        | 2.48%   |
| 2666    | 4        | 2.48%   |
| 333     | 4        | 2.48%   |
| 3400    | 3        | 1.86%   |
| 2933    | 3        | 1.86%   |
| 2400    | 3        | 1.86%   |
| 2048    | 3        | 1.86%   |
| 1800    | 3        | 1.86%   |
| 49926   | 2        | 1.24%   |
| 3266    | 2        | 1.24%   |
| 1867    | 2        | 1.24%   |
| 1639    | 2        | 1.24%   |
| 400     | 2        | 1.24%   |
| 3733    | 1        | 0.62%   |
| 3100    | 1        | 0.62%   |
| 2000    | 1        | 0.62%   |
| 1866    | 1        | 0.62%   |
| 1066    | 1        | 0.62%   |
| 533     | 1        | 0.62%   |
| 200     | 1        | 0.62%   |

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
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon CanoScan LIDE 25 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 11       | 40.74%  |
| Microsoft                     | 5        | 18.52%  |
| Sunplus Innovation Technology | 2        | 7.41%   |
| Generalplus Technology        | 2        | 7.41%   |
| Chicony Electronics           | 2        | 7.41%   |
| Trust                         | 1        | 3.7%    |
| Sunplus Technology            | 1        | 3.7%    |
| Sonix Technology              | 1        | 3.7%    |
| Huawei Technologies           | 1        | 3.7%    |
| Arkmicro Technologies         | 1        | 3.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 4        | 14.81%  |
| Logitech Webcam C270                                    | 3        | 11.11%  |
| Logitech Webcam C930e                                   | 2        | 7.41%   |
| Logitech Webcam C200                                    | 2        | 7.41%   |
| Trust Widescreen 3MP Webcam                             | 1        | 3.7%    |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 3.7%    |
| Sunplus ZET USB WEBCAM                                  | 1        | 3.7%    |
| Sunplus HD 720P webcam                                  | 1        | 3.7%    |
| Sonix USB Camera                                        | 1        | 3.7%    |
| Microsoft LifeCam VX-800                                | 1        | 3.7%    |
| Logitech Webcam Pro 9000                                | 1        | 3.7%    |
| Logitech Webcam C110                                    | 1        | 3.7%    |
| Logitech HD Webcam C615                                 | 1        | 3.7%    |
| Logitech B525 HD Webcam                                 | 1        | 3.7%    |
| Huawei UVC Camera                                       | 1        | 3.7%    |
| Generalplus GENERAL WEBCAM                              | 1        | 3.7%    |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 3.7%    |
| Chicony HP Prem AF Webcam KQ245AA                       | 1        | 3.7%    |
| Chicony HD Webcam                                       | 1        | 3.7%    |
| Arkmicro USB2.0 PC CAMERA                               | 1        | 3.7%    |

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
| 0     | 128      | 87.67%  |
| 1     | 16       | 10.96%  |
| 3     | 1        | 0.68%   |
| 2     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 9        | 45%     |
| Unassigned class         | 3        | 15%     |
| Net/wireless             | 3        | 15%     |
| Multimedia controller    | 1        | 5%      |
| Fingerprint reader       | 1        | 5%      |
| Dvb card                 | 1        | 5%      |
| Communication controller | 1        | 5%      |
| Camera                   | 1        | 5%      |

