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

Total: 158

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 19          | 43       | 35.25%  |
| MX 21          | 42       | 34.43%  |
| MX 20          | 22       | 18.03%  |
| MX 18          | 12       | 9.84%   |
| MX 22          | 1        | 0.82%   |
| MX 17          | 1        | 0.82%   |
| MX 16-migrated | 1        | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 121      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 20       | 15.15%  |
| 5.6.0-2-amd64              | 6        | 4.55%   |
| 5.10.0-13-amd64            | 5        | 3.79%   |
| 4.19.0-17-amd64            | 5        | 3.79%   |
| 5.8.0-3-amd64              | 4        | 3.03%   |
| 5.14.0-4mx-amd64           | 4        | 3.03%   |
| 5.10.0-5mx-amd64           | 4        | 3.03%   |
| 5.10.0-16-amd64            | 4        | 3.03%   |
| 5.10.0-15-amd64            | 4        | 3.03%   |
| 4.19.0-14-amd64            | 4        | 3.03%   |
| 5.10.0-18-amd64            | 3        | 2.27%   |
| 4.19.0-5-amd64             | 3        | 2.27%   |
| 4.19.0-18-amd64            | 3        | 2.27%   |
| 4.19.0-13-amd64            | 3        | 2.27%   |
| 4.19.0-1-amd64             | 3        | 2.27%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 1.52%   |
| 5.4.0-3-amd64              | 2        | 1.52%   |
| 5.16.0-5mx-amd64           | 2        | 1.52%   |
| 5.14.0-3mx-amd64           | 2        | 1.52%   |
| 5.10.0-9-amd64             | 2        | 1.52%   |
| 5.10.0-11-amd64            | 2        | 1.52%   |
| 4.19.0-16-amd64            | 2        | 1.52%   |
| 4.19.0-12-amd64            | 2        | 1.52%   |
| 6.0.5-x64v1-xanmod1        | 1        | 0.76%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 0.76%   |
| 5.5.0-7.1-liquorix-amd64   | 1        | 0.76%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 0.76%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 0.76%   |
| 5.5.0-050500rc1-lowlatency | 1        | 0.76%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 0.76%   |
| 5.4.10                     | 1        | 0.76%   |
| 5.3.0-10.1-liquorix-amd64  | 1        | 0.76%   |
| 5.3.0-0.bpo.2-amd64        | 1        | 0.76%   |
| 5.2.21-antix.2-amd64-smp   | 1        | 0.76%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 0.76%   |
| 5.19.0-17.2-liquorix-amd64 | 1        | 0.76%   |
| 5.18.0-4mx-amd64           | 1        | 0.76%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 0.76%   |
| 5.16.0-6mx-amd64           | 1        | 0.76%   |
| 5.15.0-2-amd64             | 1        | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.0   | 44       | 35.2%   |
| 5.10.0   | 33       | 26.4%   |
| 5.14.0   | 7        | 5.6%    |
| 5.6.0    | 6        | 4.8%    |
| 5.5.0    | 5        | 4%      |
| 5.8.0    | 4        | 3.2%    |
| 5.16.0   | 4        | 3.2%    |
| 5.15.0   | 3        | 2.4%    |
| 5.8.16   | 2        | 1.6%    |
| 5.4.0    | 2        | 1.6%    |
| 5.3.0    | 2        | 1.6%    |
| 5.19.0   | 2        | 1.6%    |
| 6.0.5    | 1        | 0.8%    |
| 5.4.7    | 1        | 0.8%    |
| 5.4.10   | 1        | 0.8%    |
| 5.2.21   | 1        | 0.8%    |
| 5.18.0   | 1        | 0.8%    |
| 5.11.0   | 1        | 0.8%    |
| 5.10.52  | 1        | 0.8%    |
| 5.10.111 | 1        | 0.8%    |
| 4.9.91   | 1        | 0.8%    |
| 4.18.0   | 1        | 0.8%    |
| 4.15.0   | 1        | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 44       | 35.2%   |
| 5.10    | 35       | 28%     |
| 5.14    | 7        | 5.6%    |
| 5.8     | 6        | 4.8%    |
| 5.6     | 6        | 4.8%    |
| 5.5     | 5        | 4%      |
| 5.4     | 4        | 3.2%    |
| 5.16    | 4        | 3.2%    |
| 5.15    | 3        | 2.4%    |
| 5.3     | 2        | 1.6%    |
| 5.19    | 2        | 1.6%    |
| 6.0     | 1        | 0.8%    |
| 5.2     | 1        | 0.8%    |
| 5.18    | 1        | 0.8%    |
| 5.11    | 1        | 0.8%    |
| 4.9     | 1        | 0.8%    |
| 4.18    | 1        | 0.8%    |
| 4.15    | 1        | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 116      | 95.87%  |
| i686   | 5        | 4.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 96       | 79.34%  |
| KDE5             | 16       | 13.22%  |
| MATE             | 2        | 1.65%   |
| lightdm-xsession | 2        | 1.65%   |
| X-Cinnamon       | 1        | 0.83%   |
| LXQt             | 1        | 0.83%   |
| KDE4             | 1        | 0.83%   |
| KDE              | 1        | 0.83%   |
| Unknown          | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 121      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 105      | 86.78%  |
| SDDM    | 12       | 9.92%   |
| TDM     | 2        | 1.65%   |
| SLiM    | 1        | 0.83%   |
| GDM     | 1        | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 37       | 29.37%  |
| Unknown | 34       | 26.98%  |
| de_DE   | 13       | 10.32%  |
| sk_SK   | 5        | 3.97%   |
| pl_PL   | 5        | 3.97%   |
| es_ES   | 5        | 3.97%   |
| en_GB   | 5        | 3.97%   |
| pt_BR   | 4        | 3.17%   |
| it_IT   | 2        | 1.59%   |
| hu_HU   | 2        | 1.59%   |
| fr_FR   | 2        | 1.59%   |
| de_CH   | 2        | 1.59%   |
| uk_UA   | 1        | 0.79%   |
| tr_TR   | 1        | 0.79%   |
| sv_SE   | 1        | 0.79%   |
| ru_RU   | 1        | 0.79%   |
| fi_FI   | 1        | 0.79%   |
| es_MX   | 1        | 0.79%   |
| es_CO   | 1        | 0.79%   |
| en_NZ   | 1        | 0.79%   |
| en_IE   | 1        | 0.79%   |
| en_AU   | 1        | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 80       | 66.12%  |
| EFI  | 41       | 33.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 111      | 91.74%  |
| Overlay  | 4        | 3.31%   |
| Btrfs    | 3        | 2.48%   |
| Xfs      | 1        | 0.83%   |
| Reiserfs | 1        | 0.83%   |
| Ext3     | 1        | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 64       | 52.46%  |
| MBR     | 56       | 45.9%   |
| Unknown | 2        | 1.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 60.8%   |
| Yes       | 49       | 39.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 57.02%  |
| No        | 52       | 42.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 28       | 23.14%  |
| Gigabyte Technology | 21       | 17.36%  |
| MSI                 | 16       | 13.22%  |
| Dell                | 15       | 12.4%   |
| ASRock              | 12       | 9.92%   |
| Intel               | 6        | 4.96%   |
| Hewlett-Packard     | 6        | 4.96%   |
| Lenovo              | 3        | 2.48%   |
| Biostar             | 2        | 1.65%   |
| Pegatron            | 1        | 0.83%   |
| MP                  | 1        | 0.83%   |
| Medion              | 1        | 0.83%   |
| IBM                 | 1        | 0.83%   |
| Huanan              | 1        | 0.83%   |
| GreatWall           | 1        | 0.83%   |
| Gateway             | 1        | 0.83%   |
| GALAX               | 1        | 0.83%   |
| Fujitsu Siemens     | 1        | 0.83%   |
| Fujitsu             | 1        | 0.83%   |
| ECS                 | 1        | 0.83%   |
| AOpen               | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 4        | 3.31%   |
| MSI MS-7A34                              | 2        | 1.65%   |
| Dell Studio 540                          | 2        | 1.65%   |
| Dell OptiPlex 9010                       | 2        | 1.65%   |
| Dell OptiPlex 755                        | 2        | 1.65%   |
| ASUS PRIME B450M-A                       | 2        | 1.65%   |
| ASRock K8A780LM                          | 2        | 1.65%   |
| Pegatron FQ425AA-ABA a6655f              | 1        | 0.83%   |
| MSI MS-7C94                              | 1        | 0.83%   |
| MSI MS-7C91                              | 1        | 0.83%   |
| MSI MS-7C88                              | 1        | 0.83%   |
| MSI MS-7C56                              | 1        | 0.83%   |
| MSI MS-7C37                              | 1        | 0.83%   |
| MSI MS-7B86                              | 1        | 0.83%   |
| MSI MS-7917                              | 1        | 0.83%   |
| MSI MS-7815                              | 1        | 0.83%   |
| MSI MS-7808                              | 1        | 0.83%   |
| MSI MS-7758                              | 1        | 0.83%   |
| MSI MS-7693                              | 1        | 0.83%   |
| MSI MS-7641                              | 1        | 0.83%   |
| MSI MS-7199                              | 1        | 0.83%   |
| MSI GEG                                  | 1        | 0.83%   |
| MP MS-7848                               | 1        | 0.83%   |
| Medion Akoya P5330 E MD8876/2458         | 1        | 0.83%   |
| Lenovo ThinkStation P620 30E0CTO1WW      | 1        | 0.83%   |
| Lenovo ThinkCentre M75s Gen 2 11JAS0CJ00 | 1        | 0.83%   |
| Lenovo 10AAS1QB0B                        | 1        | 0.83%   |
| Intel V1.3                               | 1        | 0.83%   |
| Intel MAHOBAY                            | 1        | 0.83%   |
| Intel H81                                | 1        | 0.83%   |
| Intel DH55TC AAE70932-303                | 1        | 0.83%   |
| Intel DCP847SKE G80890-105               | 1        | 0.83%   |
| IBM 8183B2U                              | 1        | 0.83%   |
| Huanan X99-F8                            | 1        | 0.83%   |
| HP Z400 Workstation                      | 1        | 0.83%   |
| HP Z230 Tower Workstation                | 1        | 0.83%   |
| HP Z220 CMT Workstation                  | 1        | 0.83%   |
| HP ProDesk 600 G1 DM                     | 1        | 0.83%   |
| HP Compaq 8000 Elite CMT PC              | 1        | 0.83%   |
| HP 3031h                                 | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 10       | 8.26%   |
| ASUS PRIME           | 5        | 4.13%   |
| ASUS All             | 4        | 3.31%   |
| ASUS ROG             | 3        | 2.48%   |
| MSI MS-7A34          | 2        | 1.65%   |
| Gigabyte Z390        | 2        | 1.65%   |
| Gigabyte B550M       | 2        | 1.65%   |
| Dell Studio          | 2        | 1.65%   |
| Dell Inspiron        | 2        | 1.65%   |
| ASUS TUF             | 2        | 1.65%   |
| ASUS P5GC-MX         | 2        | 1.65%   |
| ASRock K8A780LM      | 2        | 1.65%   |
| Pegatron FQ425AA-ABA | 1        | 0.83%   |
| MSI MS-7C94          | 1        | 0.83%   |
| MSI MS-7C91          | 1        | 0.83%   |
| MSI MS-7C88          | 1        | 0.83%   |
| MSI MS-7C56          | 1        | 0.83%   |
| MSI MS-7C37          | 1        | 0.83%   |
| MSI MS-7B86          | 1        | 0.83%   |
| MSI MS-7917          | 1        | 0.83%   |
| MSI MS-7815          | 1        | 0.83%   |
| MSI MS-7808          | 1        | 0.83%   |
| MSI MS-7758          | 1        | 0.83%   |
| MSI MS-7693          | 1        | 0.83%   |
| MSI MS-7641          | 1        | 0.83%   |
| MSI MS-7199          | 1        | 0.83%   |
| MSI GEG              | 1        | 0.83%   |
| MP MS-7848           | 1        | 0.83%   |
| Medion Akoya         | 1        | 0.83%   |
| Lenovo ThinkStation  | 1        | 0.83%   |
| Lenovo ThinkCentre   | 1        | 0.83%   |
| Lenovo 10AAS1QB0B    | 1        | 0.83%   |
| Intel V1.3           | 1        | 0.83%   |
| Intel MAHOBAY        | 1        | 0.83%   |
| Intel H81            | 1        | 0.83%   |
| Intel DH55TC         | 1        | 0.83%   |
| Intel DCP847SKE      | 1        | 0.83%   |
| IBM 8183B2U          | 1        | 0.83%   |
| Huanan X99-F8        | 1        | 0.83%   |
| HP Z400              | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 9.92%   |
| 2020 | 11       | 9.09%   |
| 2013 | 11       | 9.09%   |
| 2012 | 11       | 9.09%   |
| 2011 | 10       | 8.26%   |
| 2010 | 8        | 6.61%   |
| 2019 | 7        | 5.79%   |
| 2007 | 7        | 5.79%   |
| 2021 | 6        | 4.96%   |
| 2017 | 6        | 4.96%   |
| 2014 | 6        | 4.96%   |
| 2008 | 6        | 4.96%   |
| 2016 | 5        | 4.13%   |
| 2015 | 5        | 4.13%   |
| 2009 | 5        | 4.13%   |
| 2006 | 3        | 2.48%   |
| 2005 | 2        | 1.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 121      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 121      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 121      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 30       | 24.79%  |
| 8.01-16.0   | 28       | 23.14%  |
| 4.01-8.0    | 18       | 14.88%  |
| 32.01-64.0  | 18       | 14.88%  |
| 3.01-4.0    | 15       | 12.4%   |
| 1.01-2.0    | 6        | 4.96%   |
| 24.01-32.0  | 3        | 2.48%   |
| 2.01-3.0    | 1        | 0.83%   |
| 64.01-256.0 | 1        | 0.83%   |
| 0.51-1.0    | 1        | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 44       | 35.2%   |
| 2.01-3.0   | 29       | 23.2%   |
| 3.01-4.0   | 20       | 16%     |
| 4.01-8.0   | 13       | 10.4%   |
| 0.51-1.0   | 12       | 9.6%    |
| 8.01-16.0  | 5        | 4%      |
| 16.01-24.0 | 1        | 0.8%    |
| 0.01-0.5   | 1        | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 47       | 37.3%   |
| 1      | 37       | 29.37%  |
| 3      | 23       | 18.25%  |
| 4      | 9        | 7.14%   |
| 5      | 8        | 6.35%   |
| 8      | 1        | 0.79%   |
| 6      | 1        | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 53.28%  |
| No        | 57       | 46.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 121      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 78       | 64.46%  |
| Yes       | 43       | 35.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 83.47%  |
| Yes       | 20       | 16.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 32       | 26.45%  |
| Germany     | 10       | 8.26%   |
| Slovakia    | 7        | 5.79%   |
| Spain       | 6        | 4.96%   |
| Poland      | 6        | 4.96%   |
| UK          | 5        | 4.13%   |
| Italy       | 4        | 3.31%   |
| India       | 4        | 3.31%   |
| France      | 4        | 3.31%   |
| Brazil      | 4        | 3.31%   |
| Australia   | 4        | 3.31%   |
| Sweden      | 3        | 2.48%   |
| Serbia      | 3        | 2.48%   |
| Russia      | 3        | 2.48%   |
| Finland     | 3        | 2.48%   |
| Switzerland | 2        | 1.65%   |
| Netherlands | 2        | 1.65%   |
| Indonesia   | 2        | 1.65%   |
| Hungary     | 2        | 1.65%   |
| Denmark     | 2        | 1.65%   |
| Canada      | 2        | 1.65%   |
| Venezuela   | 1        | 0.83%   |
| Ukraine     | 1        | 0.83%   |
| Turkey      | 1        | 0.83%   |
| Philippines | 1        | 0.83%   |
| New Zealand | 1        | 0.83%   |
| Mexico      | 1        | 0.83%   |
| Ireland     | 1        | 0.83%   |
| Greece      | 1        | 0.83%   |
| Estonia     | 1        | 0.83%   |
| Colombia    | 1        | 0.83%   |
| Austria     | 1        | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 5.65%   |
| Barcelona                | 3        | 2.42%   |
| Ettingen                 | 2        | 1.61%   |
| Centreville              | 2        | 1.61%   |
| Berlin                   | 2        | 1.61%   |
| Bengaluru                | 2        | 1.61%   |
| Belgrade                 | 2        | 1.61%   |
| Albertslund Municipality | 2        | 1.61%   |
| Yuzhno-Sakhalinsk        | 1        | 0.81%   |
| Warsaw                   | 1        | 0.81%   |
| Warren                   | 1        | 0.81%   |
| Volos                    | 1        | 0.81%   |
| Voghera                  | 1        | 0.81%   |
| Virginia Beach           | 1        | 0.81%   |
| Vilhelmina               | 1        | 0.81%   |
| Vienna                   | 1        | 0.81%   |
| Vasco da Gama            | 1        | 0.81%   |
| Valencia                 | 1        | 0.81%   |
| Vaidasoo                 | 1        | 0.81%   |
| Titusville               | 1        | 0.81%   |
| Tilburg                  | 1        | 0.81%   |
| Tacoma                   | 1        | 0.81%   |
| Sydney                   | 1        | 0.81%   |
| Stockholm                | 1        | 0.81%   |
| Stevens Point            | 1        | 0.81%   |
| Springdale               | 1        | 0.81%   |
| Southsea                 | 1        | 0.81%   |
| Södertälje             | 1        | 0.81%   |
| Sibulan                  | 1        | 0.81%   |
| Serrana                  | 1        | 0.81%   |
| Seelbach                 | 1        | 0.81%   |
| San Diego                | 1        | 0.81%   |
| Rzeszów                 | 1        | 0.81%   |
| Rosporden                | 1        | 0.81%   |
| Rathenow                 | 1        | 0.81%   |
| Puebla City              | 1        | 0.81%   |
| Portland                 | 1        | 0.81%   |
| Pompano Beach            | 1        | 0.81%   |
| Podolsk                  | 1        | 0.81%   |
| Pila                     | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 49       | 69     | 20.76%  |
| WDC                       | 45       | 58     | 19.07%  |
| Samsung Electronics       | 36       | 56     | 15.25%  |
| Kingston                  | 17       | 18     | 7.2%    |
| Hitachi                   | 15       | 20     | 6.36%   |
| Toshiba                   | 12       | 16     | 5.08%   |
| Crucial                   | 11       | 12     | 4.66%   |
| A-DATA Technology         | 8        | 8      | 3.39%   |
| SanDisk                   | 7        | 8      | 2.97%   |
| Maxtor                    | 5        | 6      | 2.12%   |
| GOODRAM                   | 5        | 6      | 2.12%   |
| Corsair                   | 4        | 4      | 1.69%   |
| PNY                       | 3        | 4      | 1.27%   |
| SPCC                      | 2        | 2      | 0.85%   |
| Mushkin                   | 2        | 2      | 0.85%   |
| Intel                     | 2        | 3      | 0.85%   |
| WDC WDS1                  | 1        | 1      | 0.42%   |
| Transcend                 | 1        | 1      | 0.42%   |
| OCZ                       | 1        | 1      | 0.42%   |
| Micron/Crucial Technology | 1        | 1      | 0.42%   |
| Micron Technology         | 1        | 1      | 0.42%   |
| KingFast                  | 1        | 1      | 0.42%   |
| Intenso                   | 1        | 1      | 0.42%   |
| IBM/Hitachi               | 1        | 1      | 0.42%   |
| Gigabyte Technology       | 1        | 1      | 0.42%   |
| Fujitsu                   | 1        | 1      | 0.42%   |
| Avant                     | 1        | 1      | 0.42%   |
| Apacer                    | 1        | 1      | 0.42%   |
| Acer                      | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.81%   |
| Samsung SSD 860 EVO 500GB        | 5        | 1.81%   |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.81%   |
| Toshiba DT01ACA100 1TB           | 4        | 1.45%   |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.45%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.45%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.45%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 1.09%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.09%   |
| Seagate ST3500413AS 500GB        | 3        | 1.09%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 1.09%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.72%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.72%   |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.72%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.72%   |
| WDC WD15EARX-00PASB0 1TB         | 2        | 0.72%   |
| Toshiba MK5065GSX 500GB          | 2        | 0.72%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.72%   |
| SanDisk SSD PLUS 1000GB          | 2        | 0.72%   |
| SanDisk SDSSDP128G 128GB         | 2        | 0.72%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.72%   |
| Samsung SSD 860 QVO 1TB          | 2        | 0.72%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.72%   |
| Samsung SSD 860 EVO 1TB          | 2        | 0.72%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.72%   |
| Samsung SSD 850 EVO 1TB          | 2        | 0.72%   |
| Samsung SSD 840 EVO 250GB        | 2        | 0.72%   |
| Samsung SSD 830 Series 128GB     | 2        | 0.72%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 0.72%   |
| Hitachi HUA723020ALA641 2TB      | 2        | 0.72%   |
| Hitachi HTS543232A7A384 320GB    | 2        | 0.72%   |
| Hitachi HDS721050CLA362 500GB    | 2        | 0.72%   |
| Crucial CT120BX500SSD1 120GB     | 2        | 0.72%   |
| Corsair MP400 2TB                | 2        | 0.72%   |
| A-DATA SU630 480GB SSD           | 2        | 0.72%   |
| A-DATA SP600 32GB SSD            | 2        | 0.72%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.36%   |
| WDC WDS500G2B0A 500GB SSD        | 1        | 0.36%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 49       | 68     | 39.2%   |
| WDC                 | 37       | 49     | 29.6%   |
| Hitachi             | 15       | 20     | 12%     |
| Toshiba             | 12       | 16     | 9.6%    |
| Samsung Electronics | 5        | 6      | 4%      |
| Maxtor              | 5        | 6      | 4%      |
| IBM/Hitachi         | 1        | 1      | 0.8%    |
| Fujitsu             | 1        | 1      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 27       | 35     | 28.42%  |
| Kingston            | 15       | 16     | 15.79%  |
| Crucial             | 10       | 11     | 10.53%  |
| WDC                 | 7        | 8      | 7.37%   |
| SanDisk             | 7        | 8      | 7.37%   |
| A-DATA Technology   | 7        | 7      | 7.37%   |
| GOODRAM             | 5        | 6      | 5.26%   |
| SPCC                | 2        | 2      | 2.11%   |
| PNY                 | 2        | 2      | 2.11%   |
| Intel               | 2        | 3      | 2.11%   |
| WDC WDS1            | 1        | 1      | 1.05%   |
| Transcend           | 1        | 1      | 1.05%   |
| OCZ                 | 1        | 1      | 1.05%   |
| Mushkin             | 1        | 1      | 1.05%   |
| Micron Technology   | 1        | 1      | 1.05%   |
| KingFast            | 1        | 1      | 1.05%   |
| Intenso             | 1        | 1      | 1.05%   |
| Gigabyte Technology | 1        | 1      | 1.05%   |
| Avant               | 1        | 1      | 1.05%   |
| Apacer              | 1        | 1      | 1.05%   |
| Acer                | 1        | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 93       | 167    | 47.45%  |
| SSD     | 78       | 109    | 39.8%   |
| NVMe    | 24       | 28     | 12.24%  |
| Unknown | 1        | 1      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 118      | 273    | 81.38%  |
| NVMe | 24       | 28     | 16.55%  |
| SAS  | 3        | 4      | 2.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 97       | 157    | 52.43%  |
| 0.51-1.0   | 51       | 71     | 27.57%  |
| 1.01-2.0   | 19       | 24     | 10.27%  |
| 3.01-4.0   | 7        | 8      | 3.78%   |
| 2.01-3.0   | 7        | 8      | 3.78%   |
| 4.01-10.0  | 4        | 8      | 2.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 28       | 22.05%  |
| 101-250        | 23       | 18.11%  |
| 1001-2000      | 20       | 15.75%  |
| 501-1000       | 18       | 14.17%  |
| More than 3000 | 15       | 11.81%  |
| 51-100         | 12       | 9.45%   |
| 2001-3000      | 7        | 5.51%   |
| 21-50          | 3        | 2.36%   |
| 1-20           | 1        | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 26       | 20.97%  |
| 101-250        | 22       | 17.74%  |
| 251-500        | 20       | 16.13%  |
| 21-50          | 17       | 13.71%  |
| 51-100         | 11       | 8.87%   |
| 1001-2000      | 9        | 7.26%   |
| 501-1000       | 9        | 7.26%   |
| More than 3000 | 5        | 4.03%   |
| 2001-3000      | 5        | 4.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 1.96%   |
| WDC WD5003ABYX-01WERA1 500GB             | 1        | 1      | 1.96%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 1.96%   |
| WDC WD20EARX-00PASB0 2TB                 | 1        | 1      | 1.96%   |
| WDC WD1600AVVS-63L2B0 160GB              | 1        | 1      | 1.96%   |
| WDC WD15EADS-11P8B2 1TB                  | 1        | 1      | 1.96%   |
| WDC WD10EZEX-75WN4A0 1TB                 | 1        | 1      | 1.96%   |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 1.96%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 1.96%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 1.96%   |
| Toshiba MQ01ABF050 500GB                 | 1        | 1      | 1.96%   |
| Toshiba MK7575GSX 752GB                  | 1        | 1      | 1.96%   |
| Toshiba MK6465GSX 640GB                  | 1        | 1      | 1.96%   |
| SPCC Solid State Disk 512GB              | 1        | 1      | 1.96%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 1.96%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 1.96%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 1.96%   |
| Seagate ST3750330NS 752GB                | 1        | 1      | 1.96%   |
| Seagate ST3500820AS 500GB                | 1        | 1      | 1.96%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 1.96%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 1.96%   |
| Seagate ST3320413CS 320GB                | 1        | 1      | 1.96%   |
| Seagate ST33000651NS 3TB                 | 1        | 1      | 1.96%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 1.96%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 1.96%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 1.96%   |
| Seagate ST31000524AS 1TB                 | 1        | 1      | 1.96%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 1.96%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 1.96%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 1.96%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 1.96%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 1.96%   |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 1.96%   |
| Maxtor STM3500320AS 500GB                | 1        | 1      | 1.96%   |
| Maxtor 6Y120M0 122GB                     | 1        | 1      | 1.96%   |
| Maxtor 6L200M0 208GB                     | 1        | 1      | 1.96%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 1.96%   |
| Intenso SSD Sata III 120GB               | 1        | 1      | 1.96%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB        | 1        | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 30.61%  |
| WDC                 | 10       | 10     | 20.41%  |
| Hitachi             | 5        | 6      | 10.2%   |
| Samsung Electronics | 4        | 6      | 8.16%   |
| Maxtor              | 4        | 4      | 8.16%   |
| Toshiba             | 3        | 3      | 6.12%   |
| Crucial             | 2        | 2      | 4.08%   |
| SPCC                | 1        | 1      | 2.04%   |
| Intenso             | 1        | 1      | 2.04%   |
| IBM/Hitachi         | 1        | 1      | 2.04%   |
| GOODRAM             | 1        | 1      | 2.04%   |
| Fujitsu             | 1        | 1      | 2.04%   |
| A-DATA Technology   | 1        | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 38.46%  |
| WDC                 | 9        | 9      | 23.08%  |
| Hitachi             | 5        | 6      | 12.82%  |
| Maxtor              | 4        | 4      | 10.26%  |
| Toshiba             | 3        | 3      | 7.69%   |
| Samsung Electronics | 1        | 2      | 2.56%   |
| IBM/Hitachi         | 1        | 1      | 2.56%   |
| Fujitsu             | 1        | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 36       | 43     | 78.26%  |
| SSD  | 10       | 11     | 21.74%  |

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
| Works    | 105      | 238    | 66.46%  |
| Malfunc  | 43       | 54     | 27.22%  |
| Detected | 7        | 9      | 4.43%   |
| Failed   | 3        | 4      | 1.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 77       | 46.95%  |
| AMD                         | 38       | 23.17%  |
| Samsung Electronics         | 13       | 7.93%   |
| ASMedia Technology          | 8        | 4.88%   |
| JMicron Technology          | 7        | 4.27%   |
| Phison Electronics          | 5        | 3.05%   |
| Nvidia                      | 3        | 1.83%   |
| Marvell Technology Group    | 3        | 1.83%   |
| ULi Electronics             | 2        | 1.22%   |
| Micron/Crucial Technology   | 2        | 1.22%   |
| Kingston Technology Company | 2        | 1.22%   |
| VIA Technologies            | 1        | 0.61%   |
| Silicon Motion              | 1        | 0.61%   |
| SanDisk                     | 1        | 0.61%   |
| ADATA Technology            | 1        | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 7.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 4.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 4.15%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 8        | 3.69%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 3.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 3.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 3.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 2.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 2.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.3%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.84%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.84%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.84%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 1.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 1.84%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 1.84%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.38%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.38%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.38%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.38%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.38%   |
| ULi M5229 IDE                                                                           | 2        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.92%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 0.92%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.92%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.92%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.92%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.92%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 95       | 57.23%  |
| IDE  | 41       | 24.7%   |
| NVMe | 24       | 14.46%  |
| RAID | 6        | 3.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 79       | 65.29%  |
| AMD          | 41       | 33.88%  |
| CentaurHauls | 1        | 0.83%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 3.31%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.48%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 2.48%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 1.65%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.65%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.65%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.65%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.65%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.65%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.65%   |
| AMD Phenom II X6 1090T Processor            | 2        | 1.65%   |
| AMD Phenom II X4 925 Processor              | 2        | 1.65%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.83%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.83%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.83%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.83%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.83%   |
| Intel Pentium CPU G3240T @ 2.70GHz          | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.83%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.83%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.83%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.83%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.83%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.83%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.83%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.83%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.83%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.83%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.83%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.83%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.83%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 0.83%   |
| Intel Core i5-6402P CPU @ 2.80GHz           | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 19.01%  |
| Intel Core i7           | 12       | 9.92%   |
| AMD Ryzen 5             | 11       | 9.09%   |
| Intel Core i3           | 9        | 7.44%   |
| AMD Ryzen 7             | 8        | 6.61%   |
| Intel Core 2 Duo        | 7        | 5.79%   |
| Intel Core 2 Quad       | 5        | 4.13%   |
| Other                   | 3        | 2.48%   |
| Intel Xeon              | 3        | 2.48%   |
| Intel Pentium           | 3        | 2.48%   |
| AMD Phenom II X4        | 3        | 2.48%   |
| AMD Athlon II X2        | 3        | 2.48%   |
| Intel Pentium Dual-Core | 2        | 1.65%   |
| Intel Pentium 4         | 2        | 1.65%   |
| Intel Core i9           | 2        | 1.65%   |
| Intel Celeron           | 2        | 1.65%   |
| AMD Sempron             | 2        | 1.65%   |
| AMD Phenom II X6        | 2        | 1.65%   |
| Intel Pentium Gold      | 1        | 0.83%   |
| Intel Pentium Dual      | 1        | 0.83%   |
| Intel Pentium D         | 1        | 0.83%   |
| Intel Core 2 Extreme    | 1        | 0.83%   |
| Intel Celeron D         | 1        | 0.83%   |
| Intel Atom              | 1        | 0.83%   |
| CentaurHauls VIA Esther | 1        | 0.83%   |
| AMD Ryzen Threadripper  | 1        | 0.83%   |
| AMD Ryzen 9             | 1        | 0.83%   |
| AMD Ryzen 5 PRO         | 1        | 0.83%   |
| AMD Ryzen 3             | 1        | 0.83%   |
| AMD Phenom              | 1        | 0.83%   |
| AMD FX                  | 1        | 0.83%   |
| AMD E1                  | 1        | 0.83%   |
| AMD Athlon X4           | 1        | 0.83%   |
| AMD Athlon 64 X2        | 1        | 0.83%   |
| AMD Athlon              | 1        | 0.83%   |
| AMD A4                  | 1        | 0.83%   |
| AMD A10                 | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 43       | 35.54%  |
| 2      | 37       | 30.58%  |
| 6      | 18       | 14.88%  |
| 8      | 13       | 10.74%  |
| 1      | 6        | 4.96%   |
| 12     | 3        | 2.48%   |
| 10     | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 62       | 51.24%  |
| 2      | 59       | 48.76%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 119      | 98.35%  |
| 32-bit         | 2        | 1.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 13.22%  |
| 0x306c3    | 10       | 8.26%   |
| 0x206a7    | 9        | 7.44%   |
| 0x306a9    | 7        | 5.79%   |
| 0x1067a    | 7        | 5.79%   |
| 0x08701021 | 7        | 5.79%   |
| 0x0800820d | 5        | 4.13%   |
| 0x506e3    | 4        | 3.31%   |
| 0xa0671    | 3        | 2.48%   |
| 0xa0653    | 3        | 2.48%   |
| 0x906ed    | 3        | 2.48%   |
| 0x010000c8 | 3        | 2.48%   |
| 0x6fd      | 2        | 1.65%   |
| 0x6fb      | 2        | 1.65%   |
| 0x306f2    | 2        | 1.65%   |
| 0x20655    | 2        | 1.65%   |
| 0x10677    | 2        | 1.65%   |
| 0x08001138 | 2        | 1.65%   |
| 0x010000db | 2        | 1.65%   |
| 0x01000083 | 2        | 1.65%   |
| 0xf65      | 1        | 0.83%   |
| 0xf64      | 1        | 0.83%   |
| 0xf4a      | 1        | 0.83%   |
| 0xf29      | 1        | 0.83%   |
| 0xa0655    | 1        | 0.83%   |
| 0x906eb    | 1        | 0.83%   |
| 0x906ea    | 1        | 0.83%   |
| 0x406c3    | 1        | 0.83%   |
| 0x306e4    | 1        | 0.83%   |
| 0x30661    | 1        | 0.83%   |
| 0x206d7    | 1        | 0.83%   |
| 0x20652    | 1        | 0.83%   |
| 0x106e5    | 1        | 0.83%   |
| 0x10676    | 1        | 0.83%   |
| 0x0a201016 | 1        | 0.83%   |
| 0x0a201009 | 1        | 0.83%   |
| 0x08301039 | 1        | 0.83%   |
| 0x08108109 | 1        | 0.83%   |
| 0x0810100b | 1        | 0.83%   |
| 0x0800820b | 1        | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 15       | 12.4%   |
| Penryn      | 12       | 9.92%   |
| SandyBridge | 10       | 8.26%   |
| K10         | 10       | 8.26%   |
| IvyBridge   | 9        | 7.44%   |
| Zen 2       | 8        | 6.61%   |
| Zen+        | 7        | 5.79%   |
| KabyLake    | 7        | 5.79%   |
| Zen         | 5        | 4.13%   |
| Skylake     | 4        | 3.31%   |
| NetBurst    | 4        | 3.31%   |
| Core        | 4        | 3.31%   |
| CometLake   | 4        | 3.31%   |
| Zen 3       | 3        | 2.48%   |
| Westmere    | 3        | 2.48%   |
| K8 Hammer   | 3        | 2.48%   |
| Nehalem     | 2        | 1.65%   |
| Icelake     | 2        | 1.65%   |
| Unknown     | 2        | 1.65%   |
| Steamroller | 1        | 0.83%   |
| Silvermont  | 1        | 0.83%   |
| K10 Llano   | 1        | 0.83%   |
| Jaguar      | 1        | 0.83%   |
| Excavator   | 1        | 0.83%   |
| Bulldozer   | 1        | 0.83%   |
| Bonnell     | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 53       | 40.15%  |
| Intel            | 40       | 30.3%   |
| AMD              | 38       | 28.79%  |
| VIA Technologies | 1        | 0.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8        | 5.84%   |
| Nvidia GK208B [GeForce GT 710]                                                | 5        | 3.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 5        | 3.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4        | 2.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 4        | 2.92%   |
| Nvidia GT218 [GeForce 210]                                                    | 3        | 2.19%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 3        | 2.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 3        | 2.19%   |
| Intel Core Processor Integrated Graphics Controller                           | 3        | 2.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3        | 2.19%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                             | 3        | 2.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 3        | 2.19%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                            | 3        | 2.19%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2        | 1.46%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 1.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2        | 1.46%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.46%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 2        | 1.46%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 2        | 1.46%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 2        | 1.46%   |
| Intel HD Graphics 530                                                         | 2        | 1.46%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 1.46%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 2        | 1.46%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 2        | 1.46%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 2        | 1.46%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 2        | 1.46%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 2        | 1.46%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.46%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2        | 1.46%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 1.46%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.73%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.73%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.73%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1        | 0.73%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.73%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.73%   |
| Nvidia TU104 [GeForce RTX 2060]                                               | 1        | 0.73%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 1        | 0.73%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 1        | 0.73%   |
| Nvidia GT215 [GeForce GT 240]                                                 | 1        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 52       | 41.94%  |
| 1 x AMD        | 35       | 28.23%  |
| 1 x Intel      | 31       | 25%     |
| Intel + AMD    | 2        | 1.61%   |
| 3 x AMD        | 1        | 0.81%   |
| 2 x AMD        | 1        | 0.81%   |
| 1 x VIA        | 1        | 0.81%   |
| Intel + Nvidia | 1        | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 80       | 65.57%  |
| Proprietary | 37       | 30.33%  |
| Unknown     | 5        | 4.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 33.06%  |
| 1.01-2.0   | 21       | 16.94%  |
| 0.51-1.0   | 20       | 16.13%  |
| 3.01-4.0   | 13       | 10.48%  |
| 7.01-8.0   | 12       | 9.68%   |
| 0.01-0.5   | 10       | 8.06%   |
| 5.01-6.0   | 4        | 3.23%   |
| 8.01-16.0  | 2        | 1.61%   |
| 2.01-3.0   | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 24       | 18.6%   |
| Goldstar             | 17       | 13.18%  |
| Dell                 | 13       | 10.08%  |
| Acer                 | 13       | 10.08%  |
| Hewlett-Packard      | 6        | 4.65%   |
| Ancor Communications | 5        | 3.88%   |
| ViewSonic            | 4        | 3.1%    |
| Philips              | 4        | 3.1%    |
| Iiyama               | 4        | 3.1%    |
| Fujitsu Siemens      | 4        | 3.1%    |
| AOC                  | 4        | 3.1%    |
| Vestel Elektronik    | 3        | 2.33%   |
| ASUSTek Computer     | 3        | 2.33%   |
| Vizio                | 2        | 1.55%   |
| Medion               | 2        | 1.55%   |
| Lenovo               | 2        | 1.55%   |
| Eizo                 | 2        | 1.55%   |
| BenQ                 | 2        | 1.55%   |
| Videoseven           | 1        | 0.78%   |
| Sony                 | 1        | 0.78%   |
| Sceptre Tech         | 1        | 0.78%   |
| SANYO                | 1        | 0.78%   |
| SAC                  | 1        | 0.78%   |
| RIS                  | 1        | 0.78%   |
| NEC Computers        | 1        | 0.78%   |
| MSI                  | 1        | 0.78%   |
| MiTAC                | 1        | 0.78%   |
| IBM                  | 1        | 0.78%   |
| HYO                  | 1        | 0.78%   |
| Grundig              | 1        | 0.78%   |
| Gigabyte Technology  | 1        | 0.78%   |
| DTV                  | 1        | 0.78%   |
| Arnos Instruments    | 1        | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 4.55%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 3        | 2.27%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                    | 2        | 1.52%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                   | 2        | 1.52%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2        | 1.52%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch        | 2        | 1.52%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                      | 1        | 0.76%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1        | 0.76%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                  | 1        | 0.76%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 0.76%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 0.76%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1        | 0.76%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                 | 1        | 0.76%   |
| Sony TV SNY0801 1360x768                                                | 1        | 0.76%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                  | 1        | 0.76%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                       | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch     | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch    | 1        | 0.76%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch    | 1        | 0.76%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch      | 1        | 0.76%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch        | 1        | 0.76%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.76%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.76%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch       | 1        | 0.76%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 890x500mm 40.2-inch   | 1        | 0.76%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1        | 0.76%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch       | 1        | 0.76%   |
| Samsung Electronics C27JG5x SAM0F57 1680x1050 600x340mm 27.2-inch       | 1        | 0.76%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 0.76%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.76%   |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                        | 1        | 0.76%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1        | 0.76%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                | 1        | 0.76%   |
| Philips FTV PHL04C3 3840x2160 1440x810mm 65.0-inch                      | 1        | 0.76%   |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                       | 1        | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 53       | 42.06%  |
| 3840x2160 (4K)     | 11       | 8.73%   |
| 2560x1440 (QHD)    | 10       | 7.94%   |
| 1680x1050 (WSXGA+) | 10       | 7.94%   |
| 1280x1024 (SXGA)   | 9        | 7.14%   |
| 1600x1200          | 7        | 5.56%   |
| 1366x768 (WXGA)    | 5        | 3.97%   |
| 1440x900 (WXGA+)   | 4        | 3.17%   |
| 3440x1440          | 3        | 2.38%   |
| 1920x1200 (WUXGA)  | 3        | 2.38%   |
| 1600x900 (HD+)     | 3        | 2.38%   |
| 1360x768           | 3        | 2.38%   |
| 2560x1080          | 2        | 1.59%   |
| 2048x1536          | 1        | 0.79%   |
| 1280x720 (HD)      | 1        | 0.79%   |
| 1024x768 (XGA)     | 1        | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 14.84%  |
| 21      | 18       | 14.06%  |
| 23      | 16       | 12.5%   |
| 24      | 13       | 10.16%  |
| 22      | 9        | 7.03%   |
| 31      | 8        | 6.25%   |
| 19      | 7        | 5.47%   |
| 18      | 7        | 5.47%   |
| 84      | 5        | 3.91%   |
| 34      | 5        | 3.91%   |
| 20      | 4        | 3.13%   |
| 17      | 4        | 3.13%   |
| 15      | 3        | 2.34%   |
| 65      | 2        | 1.56%   |
| 72      | 1        | 0.78%   |
| 54      | 1        | 0.78%   |
| 49      | 1        | 0.78%   |
| 42      | 1        | 0.78%   |
| 26      | 1        | 0.78%   |
| 25      | 1        | 0.78%   |
| 16      | 1        | 0.78%   |
| Unknown | 1        | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 46       | 37.1%   |
| 401-500     | 39       | 31.45%  |
| 601-700     | 9        | 7.26%   |
| 301-350     | 7        | 5.65%   |
| 351-400     | 6        | 4.84%   |
| 1501-2000   | 6        | 4.84%   |
| 701-800     | 5        | 4.03%   |
| 1001-1500   | 4        | 3.23%   |
| 901-1000    | 1        | 0.81%   |
| Unknown     | 1        | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 84       | 68.29%  |
| 16/10 | 17       | 13.82%  |
| 5/4   | 9        | 7.32%   |
| 4/3   | 8        | 6.5%    |
| 21/9  | 5        | 4.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 50       | 39.68%  |
| 301-350        | 19       | 15.08%  |
| 151-200        | 15       | 11.9%   |
| 351-500        | 13       | 10.32%  |
| More than 1000 | 10       | 7.94%   |
| 141-150        | 8        | 6.35%   |
| 251-300        | 5        | 3.97%   |
| 121-130        | 1        | 0.79%   |
| 111-120        | 1        | 0.79%   |
| 101-110        | 1        | 0.79%   |
| 501-1000       | 1        | 0.79%   |
| 91-100         | 1        | 0.79%   |
| Unknown        | 1        | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 86       | 71.67%  |
| 101-120 | 25       | 20.83%  |
| 1-50    | 6        | 5%      |
| 161-240 | 1        | 0.83%   |
| 121-160 | 1        | 0.83%   |
| Unknown | 1        | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 102      | 84.3%   |
| 2     | 15       | 12.4%   |
| 3     | 2        | 1.65%   |
| 0     | 2        | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 74       | 45.4%   |
| Intel                    | 44       | 26.99%  |
| Qualcomm Atheros         | 10       | 6.13%   |
| Broadcom                 | 6        | 3.68%   |
| TP-Link                  | 5        | 3.07%   |
| Ralink Technology        | 5        | 3.07%   |
| Ralink                   | 3        | 1.84%   |
| Nvidia                   | 2        | 1.23%   |
| Marvell Technology Group | 2        | 1.23%   |
| Broadcom Limited         | 2        | 1.23%   |
| Xiaomi                   | 1        | 0.61%   |
| VIA Technologies         | 1        | 0.61%   |
| U-Blox                   | 1        | 0.61%   |
| NetGear                  | 1        | 0.61%   |
| Mercucys                 | 1        | 0.61%   |
| Edimax Technology        | 1        | 0.61%   |
| D-Link System            | 1        | 0.61%   |
| AVM                      | 1        | 0.61%   |
| ASUSTek Computer         | 1        | 0.61%   |
| Aquantia                 | 1        | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 32.22%  |
| Intel I211 Gigabit Network Connection                             | 7        | 3.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 2.78%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 2.22%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3        | 1.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.67%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.67%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.67%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.11%   |
| Realtek 802.11ac NIC                                              | 2        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.11%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.11%   |
| Intel Wireless 8260                                               | 2        | 1.11%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.11%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.11%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.11%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.56%   |
| U-Blox [u-blox 8]                                                 | 1        | 0.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1        | 0.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.56%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 0.56%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 0.56%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 0.56%   |
| Realtek B1690189192                                               | 1        | 0.56%   |
| Realtek 802.11ac WLAN Adapter                                     | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 28.26%  |
| Intel                 | 8        | 17.39%  |
| TP-Link               | 5        | 10.87%  |
| Ralink Technology     | 5        | 10.87%  |
| Ralink                | 3        | 6.52%   |
| Qualcomm Atheros      | 3        | 6.52%   |
| Broadcom              | 3        | 6.52%   |
| NetGear               | 1        | 2.17%   |
| Mercucys              | 1        | 2.17%   |
| Edimax Technology     | 1        | 2.17%   |
| Broadcom Limited      | 1        | 2.17%   |
| AVM                   | 1        | 2.17%   |
| ASUSTek Computer      | 1        | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 3        | 6.52%   |
| Ralink MT7601U Wireless Adapter                            | 3        | 6.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 2        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 4.35%   |
| Realtek 802.11ac NIC                                       | 2        | 4.35%   |
| Intel Wireless 8260                                        | 2        | 4.35%   |
| Intel Wi-Fi 6 AX200                                        | 2        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 2        | 4.35%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 2.17%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 2.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 2.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 2.17%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 2.17%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 2.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 2.17%   |
| Realtek B1690189192                                        | 1        | 2.17%   |
| Realtek 802.11ac WLAN Adapter                              | 1        | 2.17%   |
| Ralink RT5372 Wireless Adapter                             | 1        | 2.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 2.17%   |
| Ralink RT5392 PCIe Wireless Network Adapter                | 1        | 2.17%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 1        | 2.17%   |
| Ralink RT2800 802.11n PCI                                  | 1        | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 1        | 2.17%   |
| Qualcomm Atheros AR922X Wireless Network Adapter           | 1        | 2.17%   |
| NetGear A6210                                              | 1        | 2.17%   |
| Mercucys MW300UM RTL8192EU wifi                            | 1        | 2.17%   |
| Intel Wireless 7260                                        | 1        | 2.17%   |
| Intel Centrino Wireless-N 2230                             | 1        | 2.17%   |
| Edimax RTL8192S WLAN Adapter                               | 1        | 2.17%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 2.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1        | 2.17%   |
| AVM FRITZ!WLAN AC 860                                      | 1        | 2.17%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]   | 1        | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 68       | 53.13%  |
| Intel                    | 41       | 32.03%  |
| Qualcomm Atheros         | 7        | 5.47%   |
| Broadcom                 | 3        | 2.34%   |
| Nvidia                   | 2        | 1.56%   |
| Marvell Technology Group | 2        | 1.56%   |
| Xiaomi                   | 1        | 0.78%   |
| VIA Technologies         | 1        | 0.78%   |
| D-Link System            | 1        | 0.78%   |
| Broadcom Limited         | 1        | 0.78%   |
| Aquantia                 | 1        | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58       | 43.61%  |
| Intel I211 Gigabit Network Connection                             | 7        | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.76%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 3.01%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.01%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 2.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.26%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.26%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.26%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2        | 1.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.5%    |
| Nvidia MCP61 Ethernet                                             | 2        | 1.5%    |
| Intel Ethernet Controller I225-V                                  | 2        | 1.5%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.5%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.5%    |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.75%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.75%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.75%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.75%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.75%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.75%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.75%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.75%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.75%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 121      | 73.33%  |
| WiFi     | 43       | 26.06%  |
| Modem    | 1        | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 91       | 72.8%   |
| WiFi     | 34       | 27.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 76.03%  |
| 2     | 25       | 20.66%  |
| 3     | 4        | 3.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 106      | 86.89%  |
| Yes  | 16       | 13.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 35%     |
| Cambridge Silicon Radio         | 6        | 30%     |
| ASUSTek Computer                | 3        | 15%     |
| Realtek Semiconductor           | 1        | 5%      |
| Qualcomm Atheros Communications | 1        | 5%      |
| Broadcom                        | 1        | 5%      |
| Apple                           | 1        | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 6        | 30%     |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 10%     |
| Intel Bluetooth wireless interface                    | 2        | 10%     |
| Intel AX200 Bluetooth                                 | 2        | 10%     |
| Realtek Bluetooth Radio                               | 1        | 5%      |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 5%      |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 5%      |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 5%      |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 5%      |
| ASUS BCM20702A0                                       | 1        | 5%      |
| Apple Bluetooth USB Host Controller                   | 1        | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 76       | 36.02%  |
| Nvidia                  | 51       | 24.17%  |
| AMD                     | 51       | 24.17%  |
| Creative Labs           | 7        | 3.32%   |
| C-Media Electronics     | 5        | 2.37%   |
| JMTek                   | 3        | 1.42%   |
| ROCCAT                  | 2        | 0.95%   |
| Focusrite-Novation      | 2        | 0.95%   |
| VIA Technologies        | 1        | 0.47%   |
| Unknown                 | 1        | 0.47%   |
| ULi Electronics         | 1        | 0.47%   |
| Texas Instruments       | 1        | 0.47%   |
| TerraTec Electronic     | 1        | 0.47%   |
| Tenx Technology         | 1        | 0.47%   |
| Schiit Audio            | 1        | 0.47%   |
| Razer USA               | 1        | 0.47%   |
| Microsoft               | 1        | 0.47%   |
| Logitech                | 1        | 0.47%   |
| Kingston Technology     | 1        | 0.47%   |
| GN Netcom               | 1        | 0.47%   |
| Fortemedia              | 1        | 0.47%   |
| BEHRINGER International | 1        | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 4.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.77%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9        | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 3.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 2.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.51%   |
| Nvidia High Definition Audio Controller                                    | 5        | 2.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 2.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.67%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.26%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.26%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.26%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.26%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 1.26%   |
| AMD Navi 10 HDMI Audio                                                     | 3        | 1.26%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 3        | 1.26%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.26%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 1.26%   |
| ROCCAT Khan AIMO                                                           | 2        | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.84%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.84%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 0.84%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.84%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 0.84%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 28       | 21.37%  |
| Kingston                     | 25       | 19.08%  |
| Corsair                      | 20       | 15.27%  |
| G.Skill                      | 14       | 10.69%  |
| SK hynix                     | 10       | 7.63%   |
| Samsung Electronics          | 9        | 6.87%   |
| Micron Technology            | 4        | 3.05%   |
| Crucial                      | 4        | 3.05%   |
| Nanya Technology             | 3        | 2.29%   |
| Patriot                      | 2        | 1.53%   |
| A-DATA Technology            | 2        | 1.53%   |
| Transcend                    | 1        | 0.76%   |
| Smart                        | 1        | 0.76%   |
| RZX                          | 1        | 0.76%   |
| Ramaxel Technology           | 1        | 0.76%   |
| PNY                          | 1        | 0.76%   |
| Patriot Memory (PDP Systems) | 1        | 0.76%   |
| OCZ                          | 1        | 0.76%   |
| Elpida                       | 1        | 0.76%   |
| Axiom                        | 1        | 0.76%   |
| Unknown                      | 1        | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 4        | 2.7%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 3        | 2.03%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 3        | 2.03%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 3        | 2.03%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 2        | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                 | 2        | 1.35%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 2        | 1.35%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s               | 2        | 1.35%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s    | 2        | 1.35%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s     | 2        | 1.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 2        | 1.35%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s     | 2        | 1.35%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 1.35%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 1.35%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s    | 2        | 1.35%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 0.68%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s             | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM SDRAM                      | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                | 1        | 0.68%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                 | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 667MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM                              | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s               | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s              | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s               | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s               | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR                       | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM                           | 1        | 0.68%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s         | 1        | 0.68%   |
| Smart RAM SH564128FH8N6TNSQG 4096MB DIMM DDR3 1600MT/s   | 1        | 0.68%   |
| Smart RAM SH564128FH8N0QHSCG 4096MB DIMM DDR3 1333MT/s   | 1        | 0.68%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 44       | 36.97%  |
| DDR3    | 40       | 33.61%  |
| DDR2    | 13       | 10.92%  |
| Unknown | 12       | 10.08%  |
| SDRAM   | 5        | 4.2%    |
| DDR     | 5        | 4.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 115      | 96.64%  |
| SODIMM | 4        | 3.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 39       | 29.77%  |
| 4096  | 39       | 29.77%  |
| 2048  | 22       | 16.79%  |
| 16384 | 14       | 10.69%  |
| 1024  | 11       | 8.4%    |
| 32768 | 3        | 2.29%   |
| 512   | 3        | 2.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 16.91%  |
| 1333    | 20       | 14.71%  |
| 3200    | 9        | 6.62%   |
| 2133    | 9        | 6.62%   |
| 3600    | 8        | 5.88%   |
| 800     | 8        | 5.88%   |
| 667     | 6        | 4.41%   |
| Unknown | 6        | 4.41%   |
| 3466    | 5        | 3.68%   |
| 3000    | 5        | 3.68%   |
| 333     | 4        | 2.94%   |
| 2933    | 3        | 2.21%   |
| 2667    | 3        | 2.21%   |
| 2666    | 3        | 2.21%   |
| 2400    | 3        | 2.21%   |
| 2048    | 3        | 2.21%   |
| 1800    | 3        | 2.21%   |
| 49926   | 2        | 1.47%   |
| 3400    | 2        | 1.47%   |
| 1867    | 2        | 1.47%   |
| 1639    | 2        | 1.47%   |
| 400     | 2        | 1.47%   |
| 3266    | 1        | 0.74%   |
| 3100    | 1        | 0.74%   |
| 1866    | 1        | 0.74%   |
| 533     | 1        | 0.74%   |
| 200     | 1        | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Brother Industries    | 2        | 33.33%  |
| Seiko Epson           | 1        | 16.67%  |
| Lexmark International | 1        | 16.67%  |
| Konica Minolta        | 1        | 16.67%  |
| Canon                 | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson L380 Series       | 1        | 16.67%  |
| Lexmark International CS417dn | 1        | 16.67%  |
| Konica Minolta 206            | 1        | 16.67%  |
| Canon MF641C                  | 1        | 16.67%  |
| Brother MFC-7340              | 1        | 16.67%  |
| Brother DCP-L2540DW           | 1        | 16.67%  |

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
| Logitech                      | 10       | 43.48%  |
| Microsoft                     | 5        | 21.74%  |
| Sunplus Innovation Technology | 2        | 8.7%    |
| Generalplus Technology        | 2        | 8.7%    |
| Trust                         | 1        | 4.35%   |
| Sunplus Technology            | 1        | 4.35%   |
| Huawei Technologies           | 1        | 4.35%   |
| Arkmicro Technologies         | 1        | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 4        | 17.39%  |
| Logitech Webcam C270                                    | 3        | 13.04%  |
| Logitech Webcam C930e                                   | 2        | 8.7%    |
| Logitech Webcam C200                                    | 2        | 8.7%    |
| Trust Widescreen 3MP Webcam                             | 1        | 4.35%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 4.35%   |
| Sunplus HD 720P webcam                                  | 1        | 4.35%   |
| Sunplus Full HD webcam                                  | 1        | 4.35%   |
| Microsoft LifeCam VX-800                                | 1        | 4.35%   |
| Logitech Webcam Pro 9000                                | 1        | 4.35%   |
| Logitech HD Webcam C615                                 | 1        | 4.35%   |
| Logitech B525 HD Webcam                                 | 1        | 4.35%   |
| Huawei HiCamera                                         | 1        | 4.35%   |
| Generalplus GENERAL WEBCAM                              | 1        | 4.35%   |
| Generalplus 808 Camera                                  | 1        | 4.35%   |
| Arkmicro USB2.0 PC CAMERA                               | 1        | 4.35%   |

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
| 0     | 108      | 89.26%  |
| 1     | 11       | 9.09%   |
| 3     | 1        | 0.83%   |
| 2     | 1        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 6        | 40%     |
| Unassigned class      | 3        | 20%     |
| Net/wireless          | 2        | 13.33%  |
| Multimedia controller | 1        | 6.67%   |
| Fingerprint reader    | 1        | 6.67%   |
| Dvb card              | 1        | 6.67%   |
| Camera                | 1        | 6.67%   |

