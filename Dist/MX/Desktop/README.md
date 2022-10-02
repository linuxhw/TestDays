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

Total: 152

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 19          | 43       | 36.75%  |
| MX 21          | 38       | 32.48%  |
| MX 20          | 22       | 18.8%   |
| MX 18          | 12       | 10.26%  |
| MX 17          | 1        | 0.85%   |
| MX 16-migrated | 1        | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 116      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 20       | 15.87%  |
| 5.6.0-2-amd64              | 6        | 4.76%   |
| 5.10.0-13-amd64            | 5        | 3.97%   |
| 4.19.0-17-amd64            | 5        | 3.97%   |
| 5.8.0-3-amd64              | 4        | 3.17%   |
| 5.14.0-4mx-amd64           | 4        | 3.17%   |
| 5.10.0-5mx-amd64           | 4        | 3.17%   |
| 5.10.0-16-amd64            | 4        | 3.17%   |
| 5.10.0-15-amd64            | 4        | 3.17%   |
| 4.19.0-14-amd64            | 4        | 3.17%   |
| 4.19.0-5-amd64             | 3        | 2.38%   |
| 4.19.0-18-amd64            | 3        | 2.38%   |
| 4.19.0-13-amd64            | 3        | 2.38%   |
| 4.19.0-1-amd64             | 3        | 2.38%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 1.59%   |
| 5.4.0-3-amd64              | 2        | 1.59%   |
| 5.16.0-5mx-amd64           | 2        | 1.59%   |
| 5.14.0-3mx-amd64           | 2        | 1.59%   |
| 5.10.0-9-amd64             | 2        | 1.59%   |
| 5.10.0-18-amd64            | 2        | 1.59%   |
| 5.10.0-11-amd64            | 2        | 1.59%   |
| 4.19.0-16-amd64            | 2        | 1.59%   |
| 4.19.0-12-amd64            | 2        | 1.59%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 0.79%   |
| 5.5.0-7.1-liquorix-amd64   | 1        | 0.79%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 0.79%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 0.79%   |
| 5.5.0-050500rc1-lowlatency | 1        | 0.79%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 0.79%   |
| 5.4.10                     | 1        | 0.79%   |
| 5.3.0-10.1-liquorix-amd64  | 1        | 0.79%   |
| 5.3.0-0.bpo.2-amd64        | 1        | 0.79%   |
| 5.2.21-antix.2-amd64-smp   | 1        | 0.79%   |
| 5.19.0-4.2-liquorix-amd64  | 1        | 0.79%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 0.79%   |
| 5.16.0-6mx-amd64           | 1        | 0.79%   |
| 5.15.0-2-amd64             | 1        | 0.79%   |
| 5.15.0-1mx-amd64           | 1        | 0.79%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 0.79%   |
| 5.14.0-2mx-amd64           | 1        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.0   | 44       | 36.67%  |
| 5.10.0   | 31       | 25.83%  |
| 5.14.0   | 7        | 5.83%   |
| 5.6.0    | 6        | 5%      |
| 5.5.0    | 5        | 4.17%   |
| 5.8.0    | 4        | 3.33%   |
| 5.16.0   | 4        | 3.33%   |
| 5.15.0   | 3        | 2.5%    |
| 5.8.16   | 2        | 1.67%   |
| 5.4.0    | 2        | 1.67%   |
| 5.3.0    | 2        | 1.67%   |
| 5.4.7    | 1        | 0.83%   |
| 5.4.10   | 1        | 0.83%   |
| 5.2.21   | 1        | 0.83%   |
| 5.19.0   | 1        | 0.83%   |
| 5.11.0   | 1        | 0.83%   |
| 5.10.52  | 1        | 0.83%   |
| 5.10.111 | 1        | 0.83%   |
| 4.9.91   | 1        | 0.83%   |
| 4.18.0   | 1        | 0.83%   |
| 4.15.0   | 1        | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 44       | 36.67%  |
| 5.10    | 33       | 27.5%   |
| 5.14    | 7        | 5.83%   |
| 5.8     | 6        | 5%      |
| 5.6     | 6        | 5%      |
| 5.5     | 5        | 4.17%   |
| 5.4     | 4        | 3.33%   |
| 5.16    | 4        | 3.33%   |
| 5.15    | 3        | 2.5%    |
| 5.3     | 2        | 1.67%   |
| 5.2     | 1        | 0.83%   |
| 5.19    | 1        | 0.83%   |
| 5.11    | 1        | 0.83%   |
| 4.9     | 1        | 0.83%   |
| 4.18    | 1        | 0.83%   |
| 4.15    | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 111      | 95.69%  |
| i686   | 5        | 4.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 92       | 79.31%  |
| KDE5             | 16       | 13.79%  |
| MATE             | 2        | 1.72%   |
| lightdm-xsession | 2        | 1.72%   |
| LXQt             | 1        | 0.86%   |
| KDE4             | 1        | 0.86%   |
| KDE              | 1        | 0.86%   |
| Unknown          | 1        | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 116      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 101      | 87.07%  |
| SDDM    | 12       | 10.34%  |
| TDM     | 2        | 1.72%   |
| SLiM    | 1        | 0.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 36       | 29.75%  |
| Unknown | 34       | 28.1%   |
| de_DE   | 12       | 9.92%   |
| sk_SK   | 5        | 4.13%   |
| pl_PL   | 5        | 4.13%   |
| es_ES   | 5        | 4.13%   |
| en_GB   | 5        | 4.13%   |
| pt_BR   | 4        | 3.31%   |
| hu_HU   | 2        | 1.65%   |
| fr_FR   | 2        | 1.65%   |
| de_CH   | 2        | 1.65%   |
| uk_UA   | 1        | 0.83%   |
| tr_TR   | 1        | 0.83%   |
| sv_SE   | 1        | 0.83%   |
| ru_RU   | 1        | 0.83%   |
| fi_FI   | 1        | 0.83%   |
| es_MX   | 1        | 0.83%   |
| en_NZ   | 1        | 0.83%   |
| en_IE   | 1        | 0.83%   |
| en_AU   | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 78       | 67.24%  |
| EFI  | 38       | 32.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 106      | 91.38%  |
| Overlay  | 4        | 3.45%   |
| Btrfs    | 3        | 2.59%   |
| Xfs      | 1        | 0.86%   |
| Reiserfs | 1        | 0.86%   |
| Ext3     | 1        | 0.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 60       | 51.72%  |
| MBR     | 54       | 46.55%  |
| Unknown | 2        | 1.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 62.18%  |
| Yes       | 45       | 37.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 56.03%  |
| No        | 51       | 43.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 28       | 24.14%  |
| Gigabyte Technology | 20       | 17.24%  |
| MSI                 | 15       | 12.93%  |
| Dell                | 15       | 12.93%  |
| ASRock              | 12       | 10.34%  |
| Intel               | 6        | 5.17%   |
| Hewlett-Packard     | 6        | 5.17%   |
| Lenovo              | 2        | 1.72%   |
| MP                  | 1        | 0.86%   |
| Medion              | 1        | 0.86%   |
| IBM                 | 1        | 0.86%   |
| Huanan              | 1        | 0.86%   |
| GreatWall           | 1        | 0.86%   |
| Gateway             | 1        | 0.86%   |
| GALAX               | 1        | 0.86%   |
| Fujitsu Siemens     | 1        | 0.86%   |
| Fujitsu             | 1        | 0.86%   |
| ECS                 | 1        | 0.86%   |
| Biostar             | 1        | 0.86%   |
| AOpen               | 1        | 0.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 3.45%   |
| MSI MS-7A34                         | 2        | 1.72%   |
| Dell Studio 540                     | 2        | 1.72%   |
| Dell OptiPlex 9010                  | 2        | 1.72%   |
| Dell OptiPlex 755                   | 2        | 1.72%   |
| ASUS PRIME B450M-A                  | 2        | 1.72%   |
| ASRock K8A780LM                     | 2        | 1.72%   |
| MSI MS-7C94                         | 1        | 0.86%   |
| MSI MS-7C91                         | 1        | 0.86%   |
| MSI MS-7C88                         | 1        | 0.86%   |
| MSI MS-7C56                         | 1        | 0.86%   |
| MSI MS-7B86                         | 1        | 0.86%   |
| MSI MS-7917                         | 1        | 0.86%   |
| MSI MS-7815                         | 1        | 0.86%   |
| MSI MS-7808                         | 1        | 0.86%   |
| MSI MS-7758                         | 1        | 0.86%   |
| MSI MS-7693                         | 1        | 0.86%   |
| MSI MS-7641                         | 1        | 0.86%   |
| MSI MS-7199                         | 1        | 0.86%   |
| MSI GEG                             | 1        | 0.86%   |
| MP MS-7848                          | 1        | 0.86%   |
| Medion Akoya P5330 E MD8876/2458    | 1        | 0.86%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 0.86%   |
| Lenovo 10AAS1QB0B                   | 1        | 0.86%   |
| Intel V1.3                          | 1        | 0.86%   |
| Intel MAHOBAY                       | 1        | 0.86%   |
| Intel H81                           | 1        | 0.86%   |
| Intel DH55TC AAE70932-303           | 1        | 0.86%   |
| Intel DCP847SKE G80890-105          | 1        | 0.86%   |
| IBM 8183B2U                         | 1        | 0.86%   |
| Huanan X99-F8                       | 1        | 0.86%   |
| HP Z400 Workstation                 | 1        | 0.86%   |
| HP Z230 Tower Workstation           | 1        | 0.86%   |
| HP Z220 CMT Workstation             | 1        | 0.86%   |
| HP ProDesk 600 G1 DM                | 1        | 0.86%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 0.86%   |
| HP 3031h                            | 1        | 0.86%   |
| GreatWall U320                      | 1        | 0.86%   |
| Gigabyte Z68AP-D3                   | 1        | 0.86%   |
| Gigabyte Z390 UD                    | 1        | 0.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 10       | 8.62%   |
| ASUS PRIME          | 5        | 4.31%   |
| ASUS All            | 4        | 3.45%   |
| ASUS ROG            | 3        | 2.59%   |
| MSI MS-7A34         | 2        | 1.72%   |
| Gigabyte Z390       | 2        | 1.72%   |
| Gigabyte B550M      | 2        | 1.72%   |
| Dell Studio         | 2        | 1.72%   |
| Dell Inspiron       | 2        | 1.72%   |
| ASUS TUF            | 2        | 1.72%   |
| ASUS P5GC-MX        | 2        | 1.72%   |
| ASRock K8A780LM     | 2        | 1.72%   |
| MSI MS-7C94         | 1        | 0.86%   |
| MSI MS-7C91         | 1        | 0.86%   |
| MSI MS-7C88         | 1        | 0.86%   |
| MSI MS-7C56         | 1        | 0.86%   |
| MSI MS-7B86         | 1        | 0.86%   |
| MSI MS-7917         | 1        | 0.86%   |
| MSI MS-7815         | 1        | 0.86%   |
| MSI MS-7808         | 1        | 0.86%   |
| MSI MS-7758         | 1        | 0.86%   |
| MSI MS-7693         | 1        | 0.86%   |
| MSI MS-7641         | 1        | 0.86%   |
| MSI MS-7199         | 1        | 0.86%   |
| MSI GEG             | 1        | 0.86%   |
| MP MS-7848          | 1        | 0.86%   |
| Medion Akoya        | 1        | 0.86%   |
| Lenovo ThinkStation | 1        | 0.86%   |
| Lenovo 10AAS1QB0B   | 1        | 0.86%   |
| Intel V1.3          | 1        | 0.86%   |
| Intel MAHOBAY       | 1        | 0.86%   |
| Intel H81           | 1        | 0.86%   |
| Intel DH55TC        | 1        | 0.86%   |
| Intel DCP847SKE     | 1        | 0.86%   |
| IBM 8183B2U         | 1        | 0.86%   |
| Huanan X99-F8       | 1        | 0.86%   |
| HP Z400             | 1        | 0.86%   |
| HP Z230             | 1        | 0.86%   |
| HP Z220             | 1        | 0.86%   |
| HP ProDesk          | 1        | 0.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 10.34%  |
| 2020 | 11       | 9.48%   |
| 2012 | 11       | 9.48%   |
| 2013 | 10       | 8.62%   |
| 2011 | 9        | 7.76%   |
| 2014 | 7        | 6.03%   |
| 2010 | 7        | 6.03%   |
| 2007 | 7        | 6.03%   |
| 2019 | 6        | 5.17%   |
| 2017 | 6        | 5.17%   |
| 2021 | 5        | 4.31%   |
| 2016 | 5        | 4.31%   |
| 2015 | 5        | 4.31%   |
| 2009 | 5        | 4.31%   |
| 2008 | 5        | 4.31%   |
| 2006 | 3        | 2.59%   |
| 2005 | 2        | 1.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 116      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 116      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 116      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 29       | 25%     |
| 8.01-16.0   | 26       | 22.41%  |
| 4.01-8.0    | 17       | 14.66%  |
| 32.01-64.0  | 17       | 14.66%  |
| 3.01-4.0    | 15       | 12.93%  |
| 1.01-2.0    | 6        | 5.17%   |
| 24.01-32.0  | 3        | 2.59%   |
| 2.01-3.0    | 1        | 0.86%   |
| 64.01-256.0 | 1        | 0.86%   |
| 0.51-1.0    | 1        | 0.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 42       | 35.29%  |
| 2.01-3.0   | 26       | 21.85%  |
| 3.01-4.0   | 19       | 15.97%  |
| 4.01-8.0   | 13       | 10.92%  |
| 0.51-1.0   | 12       | 10.08%  |
| 8.01-16.0  | 5        | 4.2%    |
| 16.01-24.0 | 1        | 0.84%   |
| 0.01-0.5   | 1        | 0.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 45       | 37.5%   |
| 1      | 36       | 30%     |
| 3      | 21       | 17.5%   |
| 4      | 9        | 7.5%    |
| 5      | 8        | 6.67%   |
| 8      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 63       | 53.85%  |
| No        | 54       | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 116      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 64.66%  |
| Yes       | 41       | 35.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 83.62%  |
| Yes       | 19       | 16.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 31       | 26.72%  |
| Germany     | 9        | 7.76%   |
| Slovakia    | 7        | 6.03%   |
| Spain       | 6        | 5.17%   |
| Poland      | 6        | 5.17%   |
| UK          | 5        | 4.31%   |
| India       | 4        | 3.45%   |
| France      | 4        | 3.45%   |
| Brazil      | 4        | 3.45%   |
| Australia   | 4        | 3.45%   |
| Sweden      | 3        | 2.59%   |
| Serbia      | 3        | 2.59%   |
| Russia      | 3        | 2.59%   |
| Finland     | 3        | 2.59%   |
| Switzerland | 2        | 1.72%   |
| Netherlands | 2        | 1.72%   |
| Italy       | 2        | 1.72%   |
| Indonesia   | 2        | 1.72%   |
| Hungary     | 2        | 1.72%   |
| Denmark     | 2        | 1.72%   |
| Canada      | 2        | 1.72%   |
| Venezuela   | 1        | 0.86%   |
| Ukraine     | 1        | 0.86%   |
| Turkey      | 1        | 0.86%   |
| Philippines | 1        | 0.86%   |
| New Zealand | 1        | 0.86%   |
| Mexico      | 1        | 0.86%   |
| Ireland     | 1        | 0.86%   |
| Greece      | 1        | 0.86%   |
| Estonia     | 1        | 0.86%   |
| Austria     | 1        | 0.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 5.93%   |
| Barcelona                | 3        | 2.54%   |
| Ettingen                 | 2        | 1.69%   |
| Centreville              | 2        | 1.69%   |
| Bengaluru                | 2        | 1.69%   |
| Belgrade                 | 2        | 1.69%   |
| Albertslund Municipality | 2        | 1.69%   |
| Yuzhno-Sakhalinsk        | 1        | 0.85%   |
| Warsaw                   | 1        | 0.85%   |
| Warren                   | 1        | 0.85%   |
| Volos                    | 1        | 0.85%   |
| Virginia Beach           | 1        | 0.85%   |
| Vilhelmina               | 1        | 0.85%   |
| Vienna                   | 1        | 0.85%   |
| Vasco da Gama            | 1        | 0.85%   |
| Valencia                 | 1        | 0.85%   |
| Vaidasoo                 | 1        | 0.85%   |
| Titusville               | 1        | 0.85%   |
| Tilburg                  | 1        | 0.85%   |
| Tacoma                   | 1        | 0.85%   |
| Sydney                   | 1        | 0.85%   |
| Stockholm                | 1        | 0.85%   |
| Stevens Point            | 1        | 0.85%   |
| Springdale               | 1        | 0.85%   |
| Southsea                 | 1        | 0.85%   |
| Södertälje             | 1        | 0.85%   |
| Sibulan                  | 1        | 0.85%   |
| Serrana                  | 1        | 0.85%   |
| Seelbach                 | 1        | 0.85%   |
| San Diego                | 1        | 0.85%   |
| Rzeszów                 | 1        | 0.85%   |
| Rosporden                | 1        | 0.85%   |
| Rathenow                 | 1        | 0.85%   |
| Puebla City              | 1        | 0.85%   |
| Portland                 | 1        | 0.85%   |
| Pompano Beach            | 1        | 0.85%   |
| Podolsk                  | 1        | 0.85%   |
| Pila                     | 1        | 0.85%   |
| Piedmont                 | 1        | 0.85%   |
| Pabianice                | 1        | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 48       | 68     | 21.43%  |
| WDC                       | 44       | 56     | 19.64%  |
| Samsung Electronics       | 35       | 55     | 15.63%  |
| Kingston                  | 16       | 17     | 7.14%   |
| Hitachi                   | 14       | 18     | 6.25%   |
| Crucial                   | 10       | 10     | 4.46%   |
| Toshiba                   | 9        | 11     | 4.02%   |
| A-DATA Technology         | 8        | 8      | 3.57%   |
| SanDisk                   | 7        | 8      | 3.13%   |
| GOODRAM                   | 5        | 6      | 2.23%   |
| Maxtor                    | 4        | 5      | 1.79%   |
| PNY                       | 3        | 4      | 1.34%   |
| Corsair                   | 3        | 3      | 1.34%   |
| SPCC                      | 2        | 2      | 0.89%   |
| Mushkin                   | 2        | 2      | 0.89%   |
| Intel                     | 2        | 3      | 0.89%   |
| WDC WDS1                  | 1        | 1      | 0.45%   |
| Transcend                 | 1        | 1      | 0.45%   |
| OCZ                       | 1        | 1      | 0.45%   |
| Micron/Crucial Technology | 1        | 1      | 0.45%   |
| Micron Technology         | 1        | 1      | 0.45%   |
| KingFast                  | 1        | 1      | 0.45%   |
| IBM/Hitachi               | 1        | 1      | 0.45%   |
| Gigabyte Technology       | 1        | 1      | 0.45%   |
| Fujitsu                   | 1        | 1      | 0.45%   |
| Avant                     | 1        | 1      | 0.45%   |
| Apacer                    | 1        | 1      | 0.45%   |
| Acer                      | 1        | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.9%    |
| Samsung SSD 860 EVO 500GB        | 5        | 1.9%    |
| Kingston SA400S37480G 480GB SSD  | 5        | 1.9%    |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.52%   |
| Samsung SSD 850 EVO 250GB        | 4        | 1.52%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3        | 1.14%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.14%   |
| Seagate ST500DM002-1BD142 500GB  | 3        | 1.14%   |
| Seagate ST3500413AS 500GB        | 3        | 1.14%   |
| Samsung SSD 970 EVO Plus 1TB     | 3        | 1.14%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2        | 0.76%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2        | 0.76%   |
| WDC WD30EZRX-00D8PB0 3TB         | 2        | 0.76%   |
| WDC WD30EFRX-68AX9N0 3TB         | 2        | 0.76%   |
| WDC WD15EARX-00PASB0 1TB         | 2        | 0.76%   |
| Toshiba MK5065GSX 500GB          | 2        | 0.76%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 0.76%   |
| SanDisk SSD PLUS 1000GB          | 2        | 0.76%   |
| SanDisk SDSSDP128G 128GB         | 2        | 0.76%   |
| Samsung SSD 870 EVO 500GB        | 2        | 0.76%   |
| Samsung SSD 860 QVO 1TB          | 2        | 0.76%   |
| Samsung SSD 860 EVO 250GB        | 2        | 0.76%   |
| Samsung SSD 860 EVO 1TB          | 2        | 0.76%   |
| Samsung SSD 850 EVO 500GB        | 2        | 0.76%   |
| Samsung SSD 850 EVO 1TB          | 2        | 0.76%   |
| Samsung SSD 840 EVO 250GB        | 2        | 0.76%   |
| Samsung SSD 830 Series 128GB     | 2        | 0.76%   |
| Kingston SA400S37120G 120GB SSD  | 2        | 0.76%   |
| Hitachi HUA723020ALA641 2TB      | 2        | 0.76%   |
| Hitachi HTS543232A7A384 320GB    | 2        | 0.76%   |
| Crucial CT120BX500SSD1 120GB     | 2        | 0.76%   |
| Corsair MP400 2TB                | 2        | 0.76%   |
| A-DATA SU630 480GB SSD           | 2        | 0.76%   |
| A-DATA SP600 32GB SSD            | 2        | 0.76%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1        | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 0.38%   |
| WDC WDS500G2B0A 500GB SSD        | 1        | 0.38%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1        | 0.38%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 1        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 48       | 67     | 40.68%  |
| WDC                 | 36       | 47     | 30.51%  |
| Hitachi             | 14       | 18     | 11.86%  |
| Toshiba             | 9        | 11     | 7.63%   |
| Samsung Electronics | 5        | 6      | 4.24%   |
| Maxtor              | 4        | 5      | 3.39%   |
| IBM/Hitachi         | 1        | 1      | 0.85%   |
| Fujitsu             | 1        | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 27       | 35     | 29.35%  |
| Kingston            | 14       | 15     | 15.22%  |
| Crucial             | 9        | 9      | 9.78%   |
| WDC                 | 7        | 8      | 7.61%   |
| SanDisk             | 7        | 8      | 7.61%   |
| A-DATA Technology   | 7        | 7      | 7.61%   |
| GOODRAM             | 5        | 6      | 5.43%   |
| SPCC                | 2        | 2      | 2.17%   |
| PNY                 | 2        | 2      | 2.17%   |
| Intel               | 2        | 3      | 2.17%   |
| WDC WDS1            | 1        | 1      | 1.09%   |
| Transcend           | 1        | 1      | 1.09%   |
| OCZ                 | 1        | 1      | 1.09%   |
| Mushkin             | 1        | 1      | 1.09%   |
| Micron Technology   | 1        | 1      | 1.09%   |
| KingFast            | 1        | 1      | 1.09%   |
| Gigabyte Technology | 1        | 1      | 1.09%   |
| Avant               | 1        | 1      | 1.09%   |
| Apacer              | 1        | 1      | 1.09%   |
| Acer                | 1        | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 89       | 156    | 47.59%  |
| SSD     | 75       | 105    | 40.11%  |
| NVMe    | 22       | 26     | 11.76%  |
| Unknown | 1        | 1      | 0.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 113      | 258    | 81.88%  |
| NVMe | 22       | 26     | 15.94%  |
| SAS  | 3        | 4      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 93       | 148    | 51.96%  |
| 0.51-1.0   | 50       | 66     | 27.93%  |
| 1.01-2.0   | 19       | 24     | 10.61%  |
| 2.01-3.0   | 7        | 8      | 3.91%   |
| 3.01-4.0   | 6        | 7      | 3.35%   |
| 4.01-10.0  | 4        | 8      | 2.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 28       | 23.14%  |
| 101-250        | 21       | 17.36%  |
| 1001-2000      | 19       | 15.7%   |
| 501-1000       | 17       | 14.05%  |
| More than 3000 | 15       | 12.4%   |
| 51-100         | 11       | 9.09%   |
| 2001-3000      | 6        | 4.96%   |
| 21-50          | 3        | 2.48%   |
| 1-20           | 1        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 25       | 21.19%  |
| 101-250        | 20       | 16.95%  |
| 251-500        | 17       | 14.41%  |
| 21-50          | 17       | 14.41%  |
| 51-100         | 11       | 9.32%   |
| 1001-2000      | 9        | 7.63%   |
| 501-1000       | 9        | 7.63%   |
| More than 3000 | 5        | 4.24%   |
| 2001-3000      | 5        | 4.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 2.17%   |
| WDC WD5003ABYX-01WERA1 500GB             | 1        | 1      | 2.17%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 2.17%   |
| WDC WD20EARX-00PASB0 2TB                 | 1        | 1      | 2.17%   |
| WDC WD1600AVVS-63L2B0 160GB              | 1        | 1      | 2.17%   |
| WDC WD15EADS-11P8B2 1TB                  | 1        | 1      | 2.17%   |
| WDC WD10EZEX-75WN4A0 1TB                 | 1        | 1      | 2.17%   |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 2.17%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 2.17%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 2.17%   |
| Toshiba MK7575GSX 752GB                  | 1        | 1      | 2.17%   |
| Toshiba MK6465GSX 640GB                  | 1        | 1      | 2.17%   |
| SPCC Solid State Disk 512GB              | 1        | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 2.17%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 2.17%   |
| Seagate ST380815AS 80GB                  | 1        | 1      | 2.17%   |
| Seagate ST3750330NS 752GB                | 1        | 1      | 2.17%   |
| Seagate ST3500820AS 500GB                | 1        | 1      | 2.17%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.17%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.17%   |
| Seagate ST3320413CS 320GB                | 1        | 1      | 2.17%   |
| Seagate ST33000651NS 3TB                 | 1        | 1      | 2.17%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 2.17%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 2      | 2.17%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 2.17%   |
| Seagate ST31000524AS 1TB                 | 1        | 1      | 2.17%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 2.17%   |
| Seagate ST2000DM001-1ER164 2TB           | 1        | 1      | 2.17%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 2.17%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 2.17%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 2.17%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 2.17%   |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 2.17%   |
| Maxtor 6Y120M0 122GB                     | 1        | 1      | 2.17%   |
| Maxtor 6L200M0 208GB                     | 1        | 1      | 2.17%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 2.17%   |
| IBM/Hitachi IC25N030ATCS04-0 32GB        | 1        | 1      | 2.17%   |
| Hitachi HUA722020ALA331 2TB              | 1        | 1      | 2.17%   |
| Hitachi HTS545032B9SA00 320GB            | 1        | 1      | 2.17%   |
| Hitachi HDT721010SLA360 1TB              | 1        | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 33.33%  |
| WDC                 | 10       | 10     | 22.22%  |
| Samsung Electronics | 4        | 6      | 8.89%   |
| Hitachi             | 4        | 4      | 8.89%   |
| Maxtor              | 3        | 3      | 6.67%   |
| Toshiba             | 2        | 2      | 4.44%   |
| Crucial             | 2        | 2      | 4.44%   |
| SPCC                | 1        | 1      | 2.22%   |
| IBM/Hitachi         | 1        | 1      | 2.22%   |
| GOODRAM             | 1        | 1      | 2.22%   |
| Fujitsu             | 1        | 1      | 2.22%   |
| A-DATA Technology   | 1        | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 17     | 41.67%  |
| WDC                 | 9        | 9      | 25%     |
| Hitachi             | 4        | 4      | 11.11%  |
| Maxtor              | 3        | 3      | 8.33%   |
| Toshiba             | 2        | 2      | 5.56%   |
| Samsung Electronics | 1        | 2      | 2.78%   |
| IBM/Hitachi         | 1        | 1      | 2.78%   |
| Fujitsu             | 1        | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 39     | 78.57%  |
| SSD  | 9        | 10     | 21.43%  |

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
| Works    | 100      | 226    | 66.67%  |
| Malfunc  | 40       | 49     | 26.67%  |
| Detected | 7        | 9      | 4.67%   |
| Failed   | 3        | 4      | 2%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 76       | 49.03%  |
| AMD                         | 35       | 22.58%  |
| Samsung Electronics         | 12       | 7.74%   |
| ASMedia Technology          | 7        | 4.52%   |
| JMicron Technology          | 6        | 3.87%   |
| Phison Electronics          | 4        | 2.58%   |
| Marvell Technology Group    | 3        | 1.94%   |
| ULi Electronics             | 2        | 1.29%   |
| Nvidia                      | 2        | 1.29%   |
| Micron/Crucial Technology   | 2        | 1.29%   |
| Kingston Technology Company | 2        | 1.29%   |
| VIA Technologies            | 1        | 0.65%   |
| Silicon Motion              | 1        | 0.65%   |
| SanDisk                     | 1        | 0.65%   |
| ADATA Technology            | 1        | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 7.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 4.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 3.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 3.4%    |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 3.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 2.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.43%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.94%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.94%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.94%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.94%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.94%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.94%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 1.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4        | 1.94%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4        | 1.94%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.46%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.46%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.46%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.46%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.46%   |
| ULi M5229 IDE                                                                           | 2        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.97%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.97%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.97%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2        | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 91       | 57.96%  |
| IDE  | 39       | 24.84%  |
| NVMe | 22       | 14.01%  |
| RAID | 5        | 3.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 78       | 67.24%  |
| AMD          | 37       | 31.9%   |
| CentaurHauls | 1        | 0.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 2.59%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.59%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 2.59%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 1.72%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.72%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 2        | 1.72%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.72%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 1.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.72%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.72%   |
| AMD Phenom II X4 925 Processor              | 2        | 1.72%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.86%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.86%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.86%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 0.86%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1        | 0.86%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.86%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.86%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.86%   |
| Intel Pentium CPU G3240T @ 2.70GHz          | 1        | 0.86%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.86%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.86%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.86%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.86%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.86%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.86%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.86%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 0.86%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.86%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.86%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.86%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.86%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.86%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.86%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.86%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 0.86%   |
| Intel Core i5-6402P CPU @ 2.80GHz           | 1        | 0.86%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 23       | 19.83%  |
| Intel Core i7           | 12       | 10.34%  |
| AMD Ryzen 5             | 11       | 9.48%   |
| Intel Core i3           | 8        | 6.9%    |
| Intel Core 2 Duo        | 7        | 6.03%   |
| AMD Ryzen 7             | 7        | 6.03%   |
| Intel Core 2 Quad       | 5        | 4.31%   |
| Other                   | 3        | 2.59%   |
| Intel Xeon              | 3        | 2.59%   |
| Intel Pentium           | 3        | 2.59%   |
| AMD Phenom II X4        | 3        | 2.59%   |
| AMD Athlon II X2        | 3        | 2.59%   |
| Intel Pentium Dual-Core | 2        | 1.72%   |
| Intel Pentium 4         | 2        | 1.72%   |
| Intel Core i9           | 2        | 1.72%   |
| Intel Celeron           | 2        | 1.72%   |
| AMD Sempron             | 2        | 1.72%   |
| Intel Pentium Gold      | 1        | 0.86%   |
| Intel Pentium Dual      | 1        | 0.86%   |
| Intel Pentium D         | 1        | 0.86%   |
| Intel Core 2 Extreme    | 1        | 0.86%   |
| Intel Celeron D         | 1        | 0.86%   |
| Intel Atom              | 1        | 0.86%   |
| CentaurHauls VIA Esther | 1        | 0.86%   |
| AMD Ryzen Threadripper  | 1        | 0.86%   |
| AMD Ryzen 9             | 1        | 0.86%   |
| AMD Ryzen 3             | 1        | 0.86%   |
| AMD Phenom II X6        | 1        | 0.86%   |
| AMD FX                  | 1        | 0.86%   |
| AMD E1                  | 1        | 0.86%   |
| AMD Athlon X4           | 1        | 0.86%   |
| AMD Athlon 64 X2        | 1        | 0.86%   |
| AMD Athlon              | 1        | 0.86%   |
| AMD A4                  | 1        | 0.86%   |
| AMD A10                 | 1        | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 41       | 35.34%  |
| 2      | 36       | 31.03%  |
| 6      | 17       | 14.66%  |
| 8      | 12       | 10.34%  |
| 1      | 6        | 5.17%   |
| 12     | 3        | 2.59%   |
| 10     | 1        | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 116      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 51.72%  |
| 2      | 56       | 48.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 114      | 98.28%  |
| 32-bit         | 2        | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 13.79%  |
| 0x306c3    | 10       | 8.62%   |
| 0x206a7    | 8        | 6.9%    |
| 0x306a9    | 7        | 6.03%   |
| 0x1067a    | 7        | 6.03%   |
| 0x08701021 | 6        | 5.17%   |
| 0x0800820d | 5        | 4.31%   |
| 0x506e3    | 4        | 3.45%   |
| 0xa0671    | 3        | 2.59%   |
| 0xa0653    | 3        | 2.59%   |
| 0x906ed    | 3        | 2.59%   |
| 0x010000c8 | 3        | 2.59%   |
| 0x6fd      | 2        | 1.72%   |
| 0x6fb      | 2        | 1.72%   |
| 0x306f2    | 2        | 1.72%   |
| 0x20655    | 2        | 1.72%   |
| 0x10677    | 2        | 1.72%   |
| 0x08001138 | 2        | 1.72%   |
| 0x010000db | 2        | 1.72%   |
| 0xf65      | 1        | 0.86%   |
| 0xf64      | 1        | 0.86%   |
| 0xf4a      | 1        | 0.86%   |
| 0xf29      | 1        | 0.86%   |
| 0xa0655    | 1        | 0.86%   |
| 0x906eb    | 1        | 0.86%   |
| 0x906ea    | 1        | 0.86%   |
| 0x406c3    | 1        | 0.86%   |
| 0x306e4    | 1        | 0.86%   |
| 0x30661    | 1        | 0.86%   |
| 0x206d7    | 1        | 0.86%   |
| 0x20652    | 1        | 0.86%   |
| 0x106e5    | 1        | 0.86%   |
| 0x10676    | 1        | 0.86%   |
| 0x0a201016 | 1        | 0.86%   |
| 0x0a201009 | 1        | 0.86%   |
| 0x08301039 | 1        | 0.86%   |
| 0x0810100b | 1        | 0.86%   |
| 0x0800820b | 1        | 0.86%   |
| 0x08001137 | 1        | 0.86%   |
| 0x08001126 | 1        | 0.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 15       | 12.93%  |
| Penryn      | 12       | 10.34%  |
| SandyBridge | 9        | 7.76%   |
| IvyBridge   | 9        | 7.76%   |
| K10         | 8        | 6.9%    |
| Zen 2       | 7        | 6.03%   |
| KabyLake    | 7        | 6.03%   |
| Zen+        | 6        | 5.17%   |
| Zen         | 5        | 4.31%   |
| Skylake     | 4        | 3.45%   |
| NetBurst    | 4        | 3.45%   |
| Core        | 4        | 3.45%   |
| CometLake   | 4        | 3.45%   |
| Zen 3       | 3        | 2.59%   |
| Westmere    | 3        | 2.59%   |
| K8 Hammer   | 3        | 2.59%   |
| Nehalem     | 2        | 1.72%   |
| Icelake     | 2        | 1.72%   |
| Unknown     | 2        | 1.72%   |
| Steamroller | 1        | 0.86%   |
| Silvermont  | 1        | 0.86%   |
| K10 Llano   | 1        | 0.86%   |
| Jaguar      | 1        | 0.86%   |
| Excavator   | 1        | 0.86%   |
| Bulldozer   | 1        | 0.86%   |
| Bonnell     | 1        | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 51       | 40.16%  |
| Intel            | 39       | 30.71%  |
| AMD              | 36       | 28.35%  |
| VIA Technologies | 1        | 0.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7        | 5.3%    |
| Nvidia GK208B [GeForce GT 710]                                                | 5        | 3.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 5        | 3.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4        | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 4        | 3.03%   |
| Nvidia GT218 [GeForce 210]                                                    | 3        | 2.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 3        | 2.27%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 3        | 2.27%   |
| Intel Core Processor Integrated Graphics Controller                           | 3        | 2.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3        | 2.27%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                             | 3        | 2.27%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                            | 3        | 2.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 2        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2        | 1.52%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.52%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 2        | 1.52%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 2        | 1.52%   |
| Intel HD Graphics 530                                                         | 2        | 1.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 2        | 1.52%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 2        | 1.52%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 2        | 1.52%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 2        | 1.52%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 2        | 1.52%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 2        | 1.52%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.52%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2        | 1.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 1.52%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 1.52%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.76%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1        | 0.76%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2060]                                               | 1        | 0.76%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                         | 1        | 0.76%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 1        | 0.76%   |
| Nvidia GT215 [GeForce GT 240]                                                 | 1        | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 50       | 42.02%  |
| 1 x AMD        | 33       | 27.73%  |
| 1 x Intel      | 30       | 25.21%  |
| Intel + AMD    | 2        | 1.68%   |
| 3 x AMD        | 1        | 0.84%   |
| 2 x AMD        | 1        | 0.84%   |
| 1 x VIA        | 1        | 0.84%   |
| Intel + Nvidia | 1        | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 76       | 64.96%  |
| Proprietary | 37       | 31.62%  |
| Unknown     | 4        | 3.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 32.77%  |
| 0.51-1.0   | 20       | 16.81%  |
| 1.01-2.0   | 19       | 15.97%  |
| 3.01-4.0   | 13       | 10.92%  |
| 7.01-8.0   | 11       | 9.24%   |
| 0.01-0.5   | 10       | 8.4%    |
| 5.01-6.0   | 4        | 3.36%   |
| 8.01-16.0  | 2        | 1.68%   |
| 2.01-3.0   | 1        | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 24       | 18.9%   |
| Goldstar             | 16       | 12.6%   |
| Dell                 | 13       | 10.24%  |
| Acer                 | 13       | 10.24%  |
| Hewlett-Packard      | 6        | 4.72%   |
| Ancor Communications | 5        | 3.94%   |
| ViewSonic            | 4        | 3.15%   |
| Philips              | 4        | 3.15%   |
| Iiyama               | 4        | 3.15%   |
| Fujitsu Siemens      | 4        | 3.15%   |
| AOC                  | 4        | 3.15%   |
| Vestel Elektronik    | 3        | 2.36%   |
| ASUSTek Computer     | 3        | 2.36%   |
| Vizio                | 2        | 1.57%   |
| Medion               | 2        | 1.57%   |
| Eizo                 | 2        | 1.57%   |
| BenQ                 | 2        | 1.57%   |
| Videoseven           | 1        | 0.79%   |
| Sony                 | 1        | 0.79%   |
| Sceptre Tech         | 1        | 0.79%   |
| SANYO                | 1        | 0.79%   |
| SAC                  | 1        | 0.79%   |
| RIS                  | 1        | 0.79%   |
| NEC Computers        | 1        | 0.79%   |
| MSI                  | 1        | 0.79%   |
| MiTAC                | 1        | 0.79%   |
| Lenovo               | 1        | 0.79%   |
| IBM                  | 1        | 0.79%   |
| HYO                  | 1        | 0.79%   |
| Grundig              | 1        | 0.79%   |
| Gigabyte Technology  | 1        | 0.79%   |
| DTV                  | 1        | 0.79%   |
| Arnos Instruments    | 1        | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 4.62%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch      | 3        | 2.31%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                    | 2        | 1.54%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                   | 2        | 1.54%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2        | 1.54%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch        | 2        | 1.54%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                      | 1        | 0.77%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1        | 0.77%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                  | 1        | 0.77%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 0.77%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 0.77%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1        | 0.77%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                 | 1        | 0.77%   |
| Sony TV SNY0801 1360x768                                                | 1        | 0.77%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                  | 1        | 0.77%   |
| SANYO Casper SAN2213 1600x900 304x228mm 15.0-inch                       | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch    | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch     | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch    | 1        | 0.77%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch    | 1        | 0.77%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch      | 1        | 0.77%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch        | 1        | 0.77%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.77%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.77%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch       | 1        | 0.77%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.77%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1        | 0.77%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 1872x1053mm 84.6-inch | 1        | 0.77%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch       | 1        | 0.77%   |
| Samsung Electronics C27JG5x SAM0F57 1680x1050 600x340mm 27.2-inch       | 1        | 0.77%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.77%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.77%   |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                        | 1        | 0.77%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1        | 0.77%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                | 1        | 0.77%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1        | 0.77%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 1        | 0.77%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 52       | 41.94%  |
| 3840x2160 (4K)     | 10       | 8.06%   |
| 2560x1440 (QHD)    | 10       | 8.06%   |
| 1680x1050 (WSXGA+) | 10       | 8.06%   |
| 1280x1024 (SXGA)   | 9        | 7.26%   |
| 1600x1200          | 7        | 5.65%   |
| 1366x768 (WXGA)    | 5        | 4.03%   |
| 1440x900 (WXGA+)   | 4        | 3.23%   |
| 3440x1440          | 3        | 2.42%   |
| 1920x1200 (WUXGA)  | 3        | 2.42%   |
| 1600x900 (HD+)     | 3        | 2.42%   |
| 1360x768           | 3        | 2.42%   |
| 2560x1080          | 2        | 1.61%   |
| 2048x1536          | 1        | 0.81%   |
| 1280x720 (HD)      | 1        | 0.81%   |
| 1024x768 (XGA)     | 1        | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 15.08%  |
| 21      | 17       | 13.49%  |
| 23      | 15       | 11.9%   |
| 24      | 13       | 10.32%  |
| 22      | 9        | 7.14%   |
| 31      | 8        | 6.35%   |
| 19      | 7        | 5.56%   |
| 18      | 7        | 5.56%   |
| 84      | 5        | 3.97%   |
| 34      | 5        | 3.97%   |
| 20      | 4        | 3.17%   |
| 17      | 4        | 3.17%   |
| 15      | 3        | 2.38%   |
| 65      | 2        | 1.59%   |
| 72      | 1        | 0.79%   |
| 54      | 1        | 0.79%   |
| 49      | 1        | 0.79%   |
| 42      | 1        | 0.79%   |
| 26      | 1        | 0.79%   |
| 25      | 1        | 0.79%   |
| 16      | 1        | 0.79%   |
| Unknown | 1        | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 45       | 36.89%  |
| 401-500     | 38       | 31.15%  |
| 601-700     | 9        | 7.38%   |
| 301-350     | 7        | 5.74%   |
| 351-400     | 6        | 4.92%   |
| 1501-2000   | 6        | 4.92%   |
| 701-800     | 5        | 4.1%    |
| 1001-1500   | 4        | 3.28%   |
| 901-1000    | 1        | 0.82%   |
| Unknown     | 1        | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 82       | 67.77%  |
| 16/10 | 17       | 14.05%  |
| 5/4   | 9        | 7.44%   |
| 4/3   | 8        | 6.61%   |
| 21/9  | 5        | 4.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 48       | 38.71%  |
| 301-350        | 19       | 15.32%  |
| 151-200        | 15       | 12.1%   |
| 351-500        | 13       | 10.48%  |
| More than 1000 | 10       | 8.06%   |
| 141-150        | 8        | 6.45%   |
| 251-300        | 5        | 4.03%   |
| 121-130        | 1        | 0.81%   |
| 111-120        | 1        | 0.81%   |
| 101-110        | 1        | 0.81%   |
| 501-1000       | 1        | 0.81%   |
| 91-100         | 1        | 0.81%   |
| Unknown        | 1        | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 85       | 72.03%  |
| 101-120 | 24       | 20.34%  |
| 1-50    | 6        | 5.08%   |
| 161-240 | 1        | 0.85%   |
| 121-160 | 1        | 0.85%   |
| Unknown | 1        | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 98       | 84.48%  |
| 2     | 15       | 12.93%  |
| 3     | 2        | 1.72%   |
| 0     | 1        | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 70       | 44.59%  |
| Intel                    | 44       | 28.03%  |
| Qualcomm Atheros         | 10       | 6.37%   |
| Broadcom                 | 6        | 3.82%   |
| TP-Link                  | 5        | 3.18%   |
| Ralink Technology        | 4        | 2.55%   |
| Ralink                   | 3        | 1.91%   |
| Marvell Technology Group | 2        | 1.27%   |
| Broadcom Limited         | 2        | 1.27%   |
| Xiaomi                   | 1        | 0.64%   |
| VIA Technologies         | 1        | 0.64%   |
| U-Blox                   | 1        | 0.64%   |
| Nvidia                   | 1        | 0.64%   |
| NetGear                  | 1        | 0.64%   |
| Mercucys                 | 1        | 0.64%   |
| Edimax Technology        | 1        | 0.64%   |
| D-Link System            | 1        | 0.64%   |
| AVM                      | 1        | 0.64%   |
| ASUSTek Computer         | 1        | 0.64%   |
| Aquantia                 | 1        | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 54       | 31.4%   |
| Intel I211 Gigabit Network Connection                                                         | 7        | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 6        | 3.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 5        | 2.91%   |
| Intel Ethernet Connection (2) I218-V                                                          | 4        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 4        | 2.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 1.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 3        | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 3        | 1.74%   |
| Realtek 802.11ac NIC                                                                          | 3        | 1.74%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 1.74%   |
| Intel Ethernet Connection I217-LM                                                             | 3        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 1.74%   |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 1.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 1.16%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 2        | 1.16%   |
| Intel Wireless 8260                                                                           | 2        | 1.16%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.16%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                                                          | 2        | 1.16%   |
| Intel Ethernet Connection (14) I219-V                                                         | 2        | 1.16%   |
| Intel Ethernet Connection (11) I219-V                                                         | 2        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 1.16%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 2        | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 1        | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.58%   |
| U-Blox [u-blox 8]                                                                             | 1        | 0.58%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.58%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.58%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.58%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.58%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.58%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.58%   |
| Realtek B1690189192                                                                           | 1        | 0.58%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.58%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 27.27%  |
| Intel                 | 8        | 18.18%  |
| TP-Link               | 5        | 11.36%  |
| Ralink Technology     | 4        | 9.09%   |
| Ralink                | 3        | 6.82%   |
| Qualcomm Atheros      | 3        | 6.82%   |
| Broadcom              | 3        | 6.82%   |
| NetGear               | 1        | 2.27%   |
| Mercucys              | 1        | 2.27%   |
| Edimax Technology     | 1        | 2.27%   |
| Broadcom Limited      | 1        | 2.27%   |
| AVM                   | 1        | 2.27%   |
| ASUSTek Computer      | 1        | 2.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 3        | 6.82%   |
| Realtek 802.11ac NIC                                                                          | 3        | 6.82%   |
| Ralink MT7601U Wireless Adapter                                                               | 3        | 6.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2        | 4.55%   |
| Intel Wireless 8260                                                                           | 2        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 4.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 2.27%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 2.27%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 2.27%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 2.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 2.27%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 2.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1        | 2.27%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.27%   |
| Realtek B1690189192                                                                           | 1        | 2.27%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 2.27%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 2.27%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 2.27%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 2.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.27%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 2.27%   |
| NetGear A6210                                                                                 | 1        | 2.27%   |
| Mercucys MW300UM RTL8192EU wifi                                                               | 1        | 2.27%   |
| Intel Wireless 7260                                                                           | 1        | 2.27%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 2.27%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 1        | 2.27%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 2.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 2.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 2.27%   |
| AVM FRITZ!WLAN AC 860                                                                         | 1        | 2.27%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                                      | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 64       | 52.03%  |
| Intel                    | 41       | 33.33%  |
| Qualcomm Atheros         | 7        | 5.69%   |
| Broadcom                 | 3        | 2.44%   |
| Marvell Technology Group | 2        | 1.63%   |
| Xiaomi                   | 1        | 0.81%   |
| VIA Technologies         | 1        | 0.81%   |
| Nvidia                   | 1        | 0.81%   |
| D-Link System            | 1        | 0.81%   |
| Broadcom Limited         | 1        | 0.81%   |
| Aquantia                 | 1        | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54       | 42.52%  |
| Intel I211 Gigabit Network Connection                             | 7        | 5.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5        | 3.94%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 3.15%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 2.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.36%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.36%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.36%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 1.57%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.57%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.57%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.57%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.57%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.79%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.79%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.79%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.79%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.79%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.79%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.79%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.79%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.79%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 73.42%  |
| WiFi     | 41       | 25.95%  |
| Modem    | 1        | 0.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 88       | 73.33%  |
| WiFi     | 32       | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 89       | 76.72%  |
| 2     | 23       | 19.83%  |
| 3     | 4        | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 101      | 86.32%  |
| Yes  | 16       | 13.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 36.84%  |
| Cambridge Silicon Radio         | 5        | 26.32%  |
| ASUSTek Computer                | 3        | 15.79%  |
| Realtek Semiconductor           | 1        | 5.26%   |
| Qualcomm Atheros Communications | 1        | 5.26%   |
| Broadcom                        | 1        | 5.26%   |
| Apple                           | 1        | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5        | 26.32%  |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 10.53%  |
| Intel Bluetooth wireless interface                    | 2        | 10.53%  |
| Intel AX200 Bluetooth                                 | 2        | 10.53%  |
| Realtek Bluetooth Radio                               | 1        | 5.26%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 5.26%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 5.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 5.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 5.26%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 5.26%   |
| ASUS BCM20702A0                                       | 1        | 5.26%   |
| Apple Bluetooth USB Host Controller                   | 1        | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 75       | 36.59%  |
| Nvidia                  | 49       | 23.9%   |
| AMD                     | 48       | 23.41%  |
| Creative Labs           | 7        | 3.41%   |
| C-Media Electronics     | 5        | 2.44%   |
| JMTek                   | 3        | 1.46%   |
| ROCCAT                  | 2        | 0.98%   |
| Focusrite-Novation      | 2        | 0.98%   |
| VIA Technologies        | 1        | 0.49%   |
| Unknown                 | 1        | 0.49%   |
| ULi Electronics         | 1        | 0.49%   |
| Texas Instruments       | 1        | 0.49%   |
| TerraTec Electronic     | 1        | 0.49%   |
| Tenx Technology         | 1        | 0.49%   |
| Schiit Audio            | 1        | 0.49%   |
| Razer USA               | 1        | 0.49%   |
| Microsoft               | 1        | 0.49%   |
| Logitech                | 1        | 0.49%   |
| Kingston Technology     | 1        | 0.49%   |
| GN Netcom               | 1        | 0.49%   |
| Fortemedia              | 1        | 0.49%   |
| BEHRINGER International | 1        | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 10       | 4.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10       | 4.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8        | 3.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 3.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7        | 3.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 2.6%    |
| Nvidia High Definition Audio Controller                                    | 5        | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 2.16%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 2.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 2.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.73%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.3%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 1.3%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.3%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 1.3%    |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 3        | 1.3%    |
| AMD FCH Azalia Controller                                                  | 3        | 1.3%    |
| ROCCAT Khan AIMO                                                           | 2        | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.87%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.87%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 0.87%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 0.87%   |
| C-Media Electronics Audio Adapter                                          | 2        | 0.87%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 2        | 0.87%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 2        | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 27       | 21.6%   |
| Kingston                     | 23       | 18.4%   |
| Corsair                      | 20       | 16%     |
| G.Skill                      | 14       | 11.2%   |
| SK hynix                     | 10       | 8%      |
| Samsung Electronics          | 8        | 6.4%    |
| Micron Technology            | 4        | 3.2%    |
| Crucial                      | 4        | 3.2%    |
| Nanya Technology             | 3        | 2.4%    |
| Patriot                      | 2        | 1.6%    |
| A-DATA Technology            | 2        | 1.6%    |
| Transcend                    | 1        | 0.8%    |
| Smart                        | 1        | 0.8%    |
| RZX                          | 1        | 0.8%    |
| PNY                          | 1        | 0.8%    |
| Patriot Memory (PDP Systems) | 1        | 0.8%    |
| OCZ                          | 1        | 0.8%    |
| Axiom                        | 1        | 0.8%    |
| Unknown                      | 1        | 0.8%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 4        | 2.84%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 3        | 2.13%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 3        | 2.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s   | 3        | 2.13%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 2        | 1.42%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                | 2        | 1.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 2        | 1.42%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s              | 2        | 1.42%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s   | 2        | 1.42%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 1.42%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 2        | 1.42%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s    | 2        | 1.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s     | 2        | 1.42%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s  | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s   | 2        | 1.42%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s            | 1        | 0.71%   |
| Unknown RAM Module 512MB DIMM SDRAM                     | 1        | 0.71%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s               | 1        | 0.71%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s               | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM 667MT/s                     | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM                             | 1        | 0.71%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 0.71%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s              | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s             | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s              | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s              | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM DDR                      | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                  | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1        | 0.71%   |
| Unknown RAM Module 1024MB DIMM                          | 1        | 0.71%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s        | 1        | 0.71%   |
| Smart RAM SH564128FH8N6TNSQG 4096MB DIMM DDR3 1600MT/s  | 1        | 0.71%   |
| Smart RAM SH564128FH8N0QHSCG 4096MB DIMM DDR3 1333MT/s  | 1        | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 0.71%   |
| SK hynix RAM HMT351U7EFR8C-PB 4096MB DIMM DDR3 1600MT/s | 1        | 0.71%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s    | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 36.84%  |
| DDR3    | 39       | 34.21%  |
| DDR2    | 12       | 10.53%  |
| Unknown | 11       | 9.65%   |
| SDRAM   | 5        | 4.39%   |
| DDR     | 5        | 4.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 110      | 96.49%  |
| SODIMM | 4        | 3.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 39       | 31.45%  |
| 8192  | 36       | 29.03%  |
| 2048  | 20       | 16.13%  |
| 16384 | 13       | 10.48%  |
| 1024  | 10       | 8.06%   |
| 32768 | 3        | 2.42%   |
| 512   | 3        | 2.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 16.92%  |
| 1333    | 18       | 13.85%  |
| 2133    | 9        | 6.92%   |
| 3200    | 8        | 6.15%   |
| 3600    | 7        | 5.38%   |
| 800     | 7        | 5.38%   |
| Unknown | 6        | 4.62%   |
| 3466    | 5        | 3.85%   |
| 3000    | 5        | 3.85%   |
| 667     | 5        | 3.85%   |
| 333     | 4        | 3.08%   |
| 2933    | 3        | 2.31%   |
| 2667    | 3        | 2.31%   |
| 2666    | 3        | 2.31%   |
| 2400    | 3        | 2.31%   |
| 2048    | 3        | 2.31%   |
| 1800    | 3        | 2.31%   |
| 49926   | 2        | 1.54%   |
| 3400    | 2        | 1.54%   |
| 1867    | 2        | 1.54%   |
| 1639    | 2        | 1.54%   |
| 400     | 2        | 1.54%   |
| 3266    | 1        | 0.77%   |
| 3100    | 1        | 0.77%   |
| 1866    | 1        | 0.77%   |
| 1400    | 1        | 0.77%   |
| 533     | 1        | 0.77%   |
| 200     | 1        | 0.77%   |

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
| Logitech                      | 10       | 52.63%  |
| Microsoft                     | 3        | 15.79%  |
| Sunplus Innovation Technology | 2        | 10.53%  |
| Generalplus Technology        | 2        | 10.53%  |
| Sunplus Technology            | 1        | 5.26%   |
| Huawei Technologies           | 1        | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 3        | 15.79%  |
| Logitech Webcam C270                                    | 3        | 15.79%  |
| Logitech Webcam C930e                                   | 2        | 10.53%  |
| Logitech Webcam C200                                    | 2        | 10.53%  |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 5.26%   |
| Sunplus HD 720P webcam                                  | 1        | 5.26%   |
| Sunplus Canyon CNS-CWC5 Webcam                          | 1        | 5.26%   |
| Logitech Webcam Pro 9000                                | 1        | 5.26%   |
| Logitech HD Webcam C615                                 | 1        | 5.26%   |
| Logitech B525 HD Webcam                                 | 1        | 5.26%   |
| Huawei HiCamera                                         | 1        | 5.26%   |
| Generalplus GENERAL WEBCAM                              | 1        | 5.26%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 5.26%   |

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
| 0     | 103      | 88.79%  |
| 1     | 12       | 10.34%  |
| 3     | 1        | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 6        | 42.86%  |
| Unassigned class      | 3        | 21.43%  |
| Net/wireless          | 2        | 14.29%  |
| Multimedia controller | 1        | 7.14%   |
| Dvb card              | 1        | 7.14%   |
| Camera                | 1        | 7.14%   |

