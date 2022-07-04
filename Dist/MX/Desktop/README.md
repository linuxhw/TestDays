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

Total: 137

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MX 19          | 43       | 41.75%  |
| MX 21          | 25       | 24.27%  |
| MX 20          | 21       | 20.39%  |
| MX 18          | 12       | 11.65%  |
| MX 17          | 1        | 0.97%   |
| MX 16-migrated | 1        | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 102      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 20       | 17.86%  |
| 5.6.0-2-amd64              | 6        | 5.36%   |
| 5.10.0-13-amd64            | 5        | 4.46%   |
| 4.19.0-17-amd64            | 5        | 4.46%   |
| 5.8.0-3-amd64              | 4        | 3.57%   |
| 5.10.0-5mx-amd64           | 4        | 3.57%   |
| 4.19.0-14-amd64            | 4        | 3.57%   |
| 5.14.0-4mx-amd64           | 3        | 2.68%   |
| 5.10.0-15-amd64            | 3        | 2.68%   |
| 4.19.0-5-amd64             | 3        | 2.68%   |
| 4.19.0-18-amd64            | 3        | 2.68%   |
| 4.19.0-13-amd64            | 3        | 2.68%   |
| 4.19.0-1-amd64             | 3        | 2.68%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 1.79%   |
| 5.4.0-3-amd64              | 2        | 1.79%   |
| 5.14.0-3mx-amd64           | 2        | 1.79%   |
| 5.10.0-9-amd64             | 2        | 1.79%   |
| 5.10.0-11-amd64            | 2        | 1.79%   |
| 4.19.0-16-amd64            | 2        | 1.79%   |
| 4.19.0-12-amd64            | 2        | 1.79%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 0.89%   |
| 5.5.0-7.1-liquorix-amd64   | 1        | 0.89%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 0.89%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 0.89%   |
| 5.5.0-050500rc1-lowlatency | 1        | 0.89%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 0.89%   |
| 5.4.10                     | 1        | 0.89%   |
| 5.3.0-10.1-liquorix-amd64  | 1        | 0.89%   |
| 5.3.0-0.bpo.2-amd64        | 1        | 0.89%   |
| 5.2.21-antix.2-amd64-smp   | 1        | 0.89%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 0.89%   |
| 5.16.0-5mx-amd64           | 1        | 0.89%   |
| 5.15.0-2-amd64             | 1        | 0.89%   |
| 5.15.0-1mx-amd64           | 1        | 0.89%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 0.89%   |
| 5.14.0-2mx-amd64           | 1        | 0.89%   |
| 5.11.0-16.1-liquorix-amd64 | 1        | 0.89%   |
| 5.10.52-antix.1-amd64-smp  | 1        | 0.89%   |
| 5.10.111-tkg-cfs           | 1        | 0.89%   |
| 5.10.0-9mx-amd64           | 1        | 0.89%   |
| 5.10.0-8mx-rt-amd64        | 1        | 0.89%   |
| 5.10.0-8mx-amd64           | 1        | 0.89%   |
| 5.10.0-4mx-amd64           | 1        | 0.89%   |
| 5.10.0-10-amd64            | 1        | 0.89%   |
| 5.10.0-0.bpo.3-amd64       | 1        | 0.89%   |
| 4.9.91-antix.1-amd64-smp   | 1        | 0.89%   |
| 4.19.0-9-686-pae           | 1        | 0.89%   |
| 4.19.0-20-amd64            | 1        | 0.89%   |
| 4.19.0-10-686-pae          | 1        | 0.89%   |
| 4.19.0-1-686-pae           | 1        | 0.89%   |
| 4.18.0-16.1-liquorix-amd64 | 1        | 0.89%   |
| 4.15.0-1-686-pae           | 1        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.19.0   | 43       | 40.57%  |
| 5.10.0   | 22       | 20.75%  |
| 5.6.0    | 6        | 5.66%   |
| 5.14.0   | 6        | 5.66%   |
| 5.5.0    | 5        | 4.72%   |
| 5.8.0    | 4        | 3.77%   |
| 5.15.0   | 3        | 2.83%   |
| 5.8.16   | 2        | 1.89%   |
| 5.4.0    | 2        | 1.89%   |
| 5.3.0    | 2        | 1.89%   |
| 5.16.0   | 2        | 1.89%   |
| 5.4.7    | 1        | 0.94%   |
| 5.4.10   | 1        | 0.94%   |
| 5.2.21   | 1        | 0.94%   |
| 5.11.0   | 1        | 0.94%   |
| 5.10.52  | 1        | 0.94%   |
| 5.10.111 | 1        | 0.94%   |
| 4.9.91   | 1        | 0.94%   |
| 4.18.0   | 1        | 0.94%   |
| 4.15.0   | 1        | 0.94%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 43       | 40.57%  |
| 5.10    | 24       | 22.64%  |
| 5.8     | 6        | 5.66%   |
| 5.6     | 6        | 5.66%   |
| 5.14    | 6        | 5.66%   |
| 5.5     | 5        | 4.72%   |
| 5.4     | 4        | 3.77%   |
| 5.15    | 3        | 2.83%   |
| 5.3     | 2        | 1.89%   |
| 5.16    | 2        | 1.89%   |
| 5.2     | 1        | 0.94%   |
| 5.11    | 1        | 0.94%   |
| 4.9     | 1        | 0.94%   |
| 4.18    | 1        | 0.94%   |
| 4.15    | 1        | 0.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 98       | 96.08%  |
| i686   | 4        | 3.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 80       | 78.43%  |
| KDE5             | 14       | 13.73%  |
| MATE             | 2        | 1.96%   |
| lightdm-xsession | 2        | 1.96%   |
| LXQt             | 1        | 0.98%   |
| KDE4             | 1        | 0.98%   |
| KDE              | 1        | 0.98%   |
| Unknown          | 1        | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 102      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 90       | 88.24%  |
| SDDM    | 10       | 9.8%    |
| TDM     | 2        | 1.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 33       | 30.84%  |
| en_US   | 32       | 29.91%  |
| de_DE   | 9        | 8.41%   |
| sk_SK   | 5        | 4.67%   |
| en_GB   | 5        | 4.67%   |
| pl_PL   | 4        | 3.74%   |
| es_ES   | 4        | 3.74%   |
| pt_BR   | 3        | 2.8%    |
| fr_FR   | 2        | 1.87%   |
| de_CH   | 2        | 1.87%   |
| uk_UA   | 1        | 0.93%   |
| tr_TR   | 1        | 0.93%   |
| sv_SE   | 1        | 0.93%   |
| ru_RU   | 1        | 0.93%   |
| hu_HU   | 1        | 0.93%   |
| es_MX   | 1        | 0.93%   |
| en_IE   | 1        | 0.93%   |
| en_AU   | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 68       | 66.67%  |
| EFI  | 34       | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 94       | 92.16%  |
| Overlay  | 3        | 2.94%   |
| Btrfs    | 3        | 2.94%   |
| Reiserfs | 1        | 0.98%   |
| Ext3     | 1        | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 55       | 53.92%  |
| MBR     | 45       | 44.12%  |
| Unknown | 2        | 1.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 60%     |
| Yes       | 42       | 40%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 57       | 55.88%  |
| No        | 45       | 44.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 23       | 22.55%  |
| Gigabyte Technology | 19       | 18.63%  |
| MSI                 | 14       | 13.73%  |
| Dell                | 14       | 13.73%  |
| ASRock              | 11       | 10.78%  |
| Hewlett-Packard     | 6        | 5.88%   |
| Intel               | 5        | 4.9%    |
| Lenovo              | 2        | 1.96%   |
| IBM                 | 1        | 0.98%   |
| Huanan              | 1        | 0.98%   |
| GreatWall           | 1        | 0.98%   |
| Gateway             | 1        | 0.98%   |
| GALAX               | 1        | 0.98%   |
| Fujitsu Siemens     | 1        | 0.98%   |
| Fujitsu             | 1        | 0.98%   |
| ECS                 | 1        | 0.98%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 4        | 3.92%   |
| MSI MS-7A34                         | 2        | 1.96%   |
| Dell Studio 540                     | 2        | 1.96%   |
| Dell OptiPlex 9010                  | 2        | 1.96%   |
| ASRock K8A780LM                     | 2        | 1.96%   |
| MSI MS-7C94                         | 1        | 0.98%   |
| MSI MS-7C88                         | 1        | 0.98%   |
| MSI MS-7C56                         | 1        | 0.98%   |
| MSI MS-7B86                         | 1        | 0.98%   |
| MSI MS-7917                         | 1        | 0.98%   |
| MSI MS-7815                         | 1        | 0.98%   |
| MSI MS-7808                         | 1        | 0.98%   |
| MSI MS-7758                         | 1        | 0.98%   |
| MSI MS-7693                         | 1        | 0.98%   |
| MSI MS-7641                         | 1        | 0.98%   |
| MSI MS-7199                         | 1        | 0.98%   |
| MSI GEG                             | 1        | 0.98%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 0.98%   |
| Lenovo 10AAS1QB0B                   | 1        | 0.98%   |
| Intel V1.3                          | 1        | 0.98%   |
| Intel MAHOBAY                       | 1        | 0.98%   |
| Intel H81                           | 1        | 0.98%   |
| Intel DCP847SKE G80890-105          | 1        | 0.98%   |
| IBM 8183B2U                         | 1        | 0.98%   |
| Huanan X99-F8                       | 1        | 0.98%   |
| HP Z400 Workstation                 | 1        | 0.98%   |
| HP Z230 Tower Workstation           | 1        | 0.98%   |
| HP Z220 CMT Workstation             | 1        | 0.98%   |
| HP ProDesk 600 G1 DM                | 1        | 0.98%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 0.98%   |
| HP 3031h                            | 1        | 0.98%   |
| GreatWall U320                      | 1        | 0.98%   |
| Gigabyte Z68AP-D3                   | 1        | 0.98%   |
| Gigabyte Z390 UD                    | 1        | 0.98%   |
| Gigabyte Z390 GAMING X              | 1        | 0.98%   |
| Gigabyte Z370 AORUS Gaming 7        | 1        | 0.98%   |
| Gigabyte X570 AORUS PRO             | 1        | 0.98%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 1        | 0.98%   |
| Gigabyte P55-USB3                   | 1        | 0.98%   |
| Gigabyte P43-ES3G                   | 1        | 0.98%   |
| Gigabyte P35-DS3P                   | 1        | 0.98%   |
| Gigabyte H410M S2H V3               | 1        | 0.98%   |
| Gigabyte H110M-S2H                  | 1        | 0.98%   |
| Gigabyte GA-880GM-UD2H              | 1        | 0.98%   |
| Gigabyte GA-880GA-UD3H              | 1        | 0.98%   |
| Gigabyte F2A88X-UP4                 | 1        | 0.98%   |
| Gigabyte EP45-UD3LR                 | 1        | 0.98%   |
| Gigabyte B550M S2H                  | 1        | 0.98%   |
| Gigabyte B550M DS3H                 | 1        | 0.98%   |
| Gigabyte B450M DS3H                 | 1        | 0.98%   |
| Gigabyte A320M-DS2                  | 1        | 0.98%   |
| Gateway SX2185                      | 1        | 0.98%   |
| GALAX B550M                         | 1        | 0.98%   |
| Fujitsu Siemens ESPRIMO P           | 1        | 0.98%   |
| Fujitsu ESPRIMO P720                | 1        | 0.98%   |
| ECS A55F-M3                         | 1        | 0.98%   |
| Dell XPS720                         | 1        | 0.98%   |
| Dell OptiPlex GX620                 | 1        | 0.98%   |
| Dell OptiPlex 790                   | 1        | 0.98%   |
| Dell OptiPlex 780                   | 1        | 0.98%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 9        | 8.82%   |
| ASUS PRIME              | 4        | 3.92%   |
| ASUS All                | 4        | 3.92%   |
| ASUS ROG                | 3        | 2.94%   |
| MSI MS-7A34             | 2        | 1.96%   |
| Gigabyte Z390           | 2        | 1.96%   |
| Gigabyte B550M          | 2        | 1.96%   |
| Dell Studio             | 2        | 1.96%   |
| Dell Inspiron           | 2        | 1.96%   |
| ASUS TUF                | 2        | 1.96%   |
| ASRock K8A780LM         | 2        | 1.96%   |
| MSI MS-7C94             | 1        | 0.98%   |
| MSI MS-7C88             | 1        | 0.98%   |
| MSI MS-7C56             | 1        | 0.98%   |
| MSI MS-7B86             | 1        | 0.98%   |
| MSI MS-7917             | 1        | 0.98%   |
| MSI MS-7815             | 1        | 0.98%   |
| MSI MS-7808             | 1        | 0.98%   |
| MSI MS-7758             | 1        | 0.98%   |
| MSI MS-7693             | 1        | 0.98%   |
| MSI MS-7641             | 1        | 0.98%   |
| MSI MS-7199             | 1        | 0.98%   |
| MSI GEG                 | 1        | 0.98%   |
| Lenovo ThinkStation     | 1        | 0.98%   |
| Lenovo 10AAS1QB0B       | 1        | 0.98%   |
| Intel V1.3              | 1        | 0.98%   |
| Intel MAHOBAY           | 1        | 0.98%   |
| Intel H81               | 1        | 0.98%   |
| Intel DCP847SKE         | 1        | 0.98%   |
| IBM 8183B2U             | 1        | 0.98%   |
| Huanan X99-F8           | 1        | 0.98%   |
| HP Z400                 | 1        | 0.98%   |
| HP Z230                 | 1        | 0.98%   |
| HP Z220                 | 1        | 0.98%   |
| HP ProDesk              | 1        | 0.98%   |
| HP Compaq               | 1        | 0.98%   |
| HP 3031h                | 1        | 0.98%   |
| GreatWall U320          | 1        | 0.98%   |
| Gigabyte Z68AP-D3       | 1        | 0.98%   |
| Gigabyte Z370           | 1        | 0.98%   |
| Gigabyte X570           | 1        | 0.98%   |
| Gigabyte X470           | 1        | 0.98%   |
| Gigabyte P55-USB3       | 1        | 0.98%   |
| Gigabyte P43-ES3G       | 1        | 0.98%   |
| Gigabyte P35-DS3P       | 1        | 0.98%   |
| Gigabyte H410M          | 1        | 0.98%   |
| Gigabyte H110M-S2H      | 1        | 0.98%   |
| Gigabyte GA-880GM-UD2H  | 1        | 0.98%   |
| Gigabyte GA-880GA-UD3H  | 1        | 0.98%   |
| Gigabyte F2A88X-UP4     | 1        | 0.98%   |
| Gigabyte EP45-UD3LR     | 1        | 0.98%   |
| Gigabyte B450M          | 1        | 0.98%   |
| Gigabyte A320M-DS2      | 1        | 0.98%   |
| Gateway SX2185          | 1        | 0.98%   |
| GALAX B550M             | 1        | 0.98%   |
| Fujitsu Siemens ESPRIMO | 1        | 0.98%   |
| Fujitsu ESPRIMO         | 1        | 0.98%   |
| ECS A55F-M3             | 1        | 0.98%   |
| Dell XPS720             | 1        | 0.98%   |
| ASUS X79-DELUXE         | 1        | 0.98%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 10       | 9.8%    |
| 2013 | 10       | 9.8%    |
| 2018 | 9        | 8.82%   |
| 2012 | 9        | 8.82%   |
| 2011 | 8        | 7.84%   |
| 2019 | 6        | 5.88%   |
| 2017 | 6        | 5.88%   |
| 2014 | 6        | 5.88%   |
| 2016 | 5        | 4.9%    |
| 2010 | 5        | 4.9%    |
| 2009 | 5        | 4.9%    |
| 2008 | 5        | 4.9%    |
| 2007 | 5        | 4.9%    |
| 2021 | 4        | 3.92%   |
| 2015 | 4        | 3.92%   |
| 2006 | 3        | 2.94%   |
| 2005 | 2        | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 102      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 102      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 102      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 27.45%  |
| 8.01-16.0   | 21       | 20.59%  |
| 4.01-8.0    | 15       | 14.71%  |
| 32.01-64.0  | 14       | 13.73%  |
| 3.01-4.0    | 13       | 12.75%  |
| 1.01-2.0    | 6        | 5.88%   |
| 24.01-32.0  | 2        | 1.96%   |
| 2.01-3.0    | 1        | 0.98%   |
| 64.01-256.0 | 1        | 0.98%   |
| 0.51-1.0    | 1        | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 37       | 35.24%  |
| 2.01-3.0   | 23       | 21.9%   |
| 3.01-4.0   | 16       | 15.24%  |
| 4.01-8.0   | 12       | 11.43%  |
| 0.51-1.0   | 11       | 10.48%  |
| 8.01-16.0  | 4        | 3.81%   |
| 16.01-24.0 | 1        | 0.95%   |
| 0.01-0.5   | 1        | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 41       | 38.68%  |
| 1      | 31       | 29.25%  |
| 3      | 17       | 16.04%  |
| 5      | 8        | 7.55%   |
| 4      | 8        | 7.55%   |
| 8      | 1        | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 54       | 52.43%  |
| No        | 49       | 47.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 102      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 67.65%  |
| Yes       | 33       | 32.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 84.31%  |
| Yes       | 16       | 15.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 30       | 29.41%  |
| Slovakia    | 7        | 6.86%   |
| Spain       | 6        | 5.88%   |
| Germany     | 6        | 5.88%   |
| UK          | 5        | 4.9%    |
| Poland      | 5        | 4.9%    |
| France      | 4        | 3.92%   |
| Australia   | 4        | 3.92%   |
| Sweden      | 3        | 2.94%   |
| Serbia      | 3        | 2.94%   |
| Russia      | 3        | 2.94%   |
| India       | 3        | 2.94%   |
| Brazil      | 3        | 2.94%   |
| Switzerland | 2        | 1.96%   |
| Finland     | 2        | 1.96%   |
| Denmark     | 2        | 1.96%   |
| Canada      | 2        | 1.96%   |
| Ukraine     | 1        | 0.98%   |
| Turkey      | 1        | 0.98%   |
| Philippines | 1        | 0.98%   |
| Netherlands | 1        | 0.98%   |
| Mexico      | 1        | 0.98%   |
| Italy       | 1        | 0.98%   |
| Ireland     | 1        | 0.98%   |
| Indonesia   | 1        | 0.98%   |
| Hungary     | 1        | 0.98%   |
| Greece      | 1        | 0.98%   |
| Estonia     | 1        | 0.98%   |
| Austria     | 1        | 0.98%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 6.73%   |
| Ettingen                 | 2        | 1.92%   |
| Centreville              | 2        | 1.92%   |
| Bengaluru                | 2        | 1.92%   |
| Belgrade                 | 2        | 1.92%   |
| Barcelona                | 2        | 1.92%   |
| Albertslund Municipality | 2        | 1.92%   |
| Yuzhno-Sakhalinsk        | 1        | 0.96%   |
| Warsaw                   | 1        | 0.96%   |
| Warren                   | 1        | 0.96%   |
| Volos                    | 1        | 0.96%   |
| Virginia Beach           | 1        | 0.96%   |
| Vilhelmina               | 1        | 0.96%   |
| Vienna                   | 1        | 0.96%   |
| Valencia                 | 1        | 0.96%   |
| Vaidasoo                 | 1        | 0.96%   |
| Titusville               | 1        | 0.96%   |
| Tilburg                  | 1        | 0.96%   |
| Tacoma                   | 1        | 0.96%   |
| Sydney                   | 1        | 0.96%   |
| Stockholm                | 1        | 0.96%   |
| Springdale               | 1        | 0.96%   |
| Southsea                 | 1        | 0.96%   |
| Södertälje             | 1        | 0.96%   |
| Sibulan                  | 1        | 0.96%   |
| Serrana                  | 1        | 0.96%   |
| Seelbach                 | 1        | 0.96%   |
| San Diego                | 1        | 0.96%   |
| Rosporden                | 1        | 0.96%   |
| Puebla City              | 1        | 0.96%   |
| Portland                 | 1        | 0.96%   |
| Pompano Beach            | 1        | 0.96%   |
| Podolsk                  | 1        | 0.96%   |
| Pila                     | 1        | 0.96%   |
| Piedmont                 | 1        | 0.96%   |
| Pabianice                | 1        | 0.96%   |
| Oxford                   | 1        | 0.96%   |
| Omsk                     | 1        | 0.96%   |
| Oconto                   | 1        | 0.96%   |
| Novi Knezevac            | 1        | 0.96%   |
| Norwalk                  | 1        | 0.96%   |
| Normal                   | 1        | 0.96%   |
| Newtownabbey             | 1        | 0.96%   |
| Mount Pocono             | 1        | 0.96%   |
| Milwaukee                | 1        | 0.96%   |
| Melbourne                | 1        | 0.96%   |
| Mechanicsburg            | 1        | 0.96%   |
| McLoud                   | 1        | 0.96%   |
| Manado                   | 1        | 0.96%   |
| Madrid                   | 1        | 0.96%   |
| Lyon                     | 1        | 0.96%   |
| Lewisham                 | 1        | 0.96%   |
| Lee's Summit             | 1        | 0.96%   |
| Lahnstein                | 1        | 0.96%   |
| La Puebla                | 1        | 0.96%   |
| Kolodenka                | 1        | 0.96%   |
| Kharagpur                | 1        | 0.96%   |
| Kamiah                   | 1        | 0.96%   |
| Huntsville               | 1        | 0.96%   |
| Houston                  | 1        | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 41       | 57     | 20.3%   |
| WDC                       | 40       | 52     | 19.8%   |
| Samsung Electronics       | 29       | 47     | 14.36%  |
| Kingston                  | 15       | 16     | 7.43%   |
| Hitachi                   | 14       | 18     | 6.93%   |
| Crucial                   | 9        | 9      | 4.46%   |
| Toshiba                   | 8        | 10     | 3.96%   |
| A-DATA Technology         | 8        | 8      | 3.96%   |
| SanDisk                   | 6        | 7      | 2.97%   |
| Goodram                   | 5        | 6      | 2.48%   |
| Maxtor                    | 4        | 5      | 1.98%   |
| PNY                       | 3        | 4      | 1.49%   |
| Corsair                   | 3        | 3      | 1.49%   |
| SPCC                      | 2        | 2      | 0.99%   |
| Mushkin                   | 2        | 2      | 0.99%   |
| Intel                     | 2        | 3      | 0.99%   |
| WDC WDS1                  | 1        | 1      | 0.5%    |
| Transcend                 | 1        | 1      | 0.5%    |
| OCZ                       | 1        | 1      | 0.5%    |
| Micron/Crucial Technology | 1        | 1      | 0.5%    |
| Micron Technology         | 1        | 1      | 0.5%    |
| KingFast                  | 1        | 1      | 0.5%    |
| IBM/Hitachi               | 1        | 1      | 0.5%    |
| Gigabyte Technology       | 1        | 1      | 0.5%    |
| Fujitsu                   | 1        | 1      | 0.5%    |
| Avant                     | 1        | 1      | 0.5%    |
| Acer                      | 1        | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB    | 5        | 2.12%   |
| Samsung SSD 860 EVO 500GB         | 5        | 2.12%   |
| Seagate ST4000DM004-2CV104 4TB    | 4        | 1.69%   |
| Seagate ST1000DM010-2EP102 1TB    | 4        | 1.69%   |
| Kingston SA400S37480G 480GB SSD   | 4        | 1.69%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 3        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB   | 3        | 1.27%   |
| Samsung SSD 970 EVO Plus 1TB      | 3        | 1.27%   |
| WDC WD60EZRZ-00RWYB1 6TB          | 2        | 0.85%   |
| WDC WD60EFRX-68L0BN1 6TB          | 2        | 0.85%   |
| WDC WD30EZRX-00D8PB0 3TB          | 2        | 0.85%   |
| WDC WD30EFRX-68AX9N0 3TB          | 2        | 0.85%   |
| WDC WD15EARX-00PASB0 1TB          | 2        | 0.85%   |
| Toshiba MK5065GSX 500GB           | 2        | 0.85%   |
| Toshiba DT01ACA100 1TB            | 2        | 0.85%   |
| Seagate ST3500413AS 500GB         | 2        | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB    | 2        | 0.85%   |
| SanDisk SSD PLUS 1000GB           | 2        | 0.85%   |
| SanDisk SDSSDP128G 128GB          | 2        | 0.85%   |
| Samsung SSD 870 EVO 500GB         | 2        | 0.85%   |
| Samsung SSD 860 QVO 1TB           | 2        | 0.85%   |
| Samsung SSD 860 EVO 250GB         | 2        | 0.85%   |
| Samsung SSD 860 EVO 1TB           | 2        | 0.85%   |
| Samsung SSD 850 EVO 500GB         | 2        | 0.85%   |
| Samsung SSD 850 EVO 250GB         | 2        | 0.85%   |
| Samsung SSD 850 EVO 1TB           | 2        | 0.85%   |
| Samsung SSD 840 EVO 250GB         | 2        | 0.85%   |
| Samsung SSD 830 Series 128GB      | 2        | 0.85%   |
| Kingston SA400S37120G 120GB SSD   | 2        | 0.85%   |
| Hitachi HUA723020ALA641 2TB       | 2        | 0.85%   |
| Hitachi HTS543232A7A384 320GB     | 2        | 0.85%   |
| Crucial CT120BX500SSD1 120GB      | 2        | 0.85%   |
| Corsair MP400 2TB                 | 2        | 0.85%   |
| A-DATA SU630 480GB SSD            | 2        | 0.85%   |
| A-DATA SP600 32GB SSD             | 2        | 0.85%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 1        | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1        | 0.42%   |
| WDC WDS500G2B0A 500GB SSD         | 1        | 0.42%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD  | 1        | 0.42%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 1        | 0.42%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD  | 1        | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.42%   |
| WDC WDS1 20G2G0A-00JH30 120GB SSD | 1        | 0.42%   |
| WDC WD80EZAZ-11TDBA0 8TB          | 1        | 0.42%   |
| WDC WD800JD-00MSA1 80GB           | 1        | 0.42%   |
| WDC WD5003ABYX-01WERA1 500GB      | 1        | 0.42%   |
| WDC WD5002AALX-00J37A0 500GB      | 1        | 0.42%   |
| WDC WD5000AVCS-632DY1 500GB       | 1        | 0.42%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1        | 0.42%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 0.42%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 0.42%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 0.42%   |
| WDC WD2500JS-75NCB3 250GB         | 1        | 0.42%   |
| WDC WD2500AAJS-00L7A0 250GB       | 1        | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 0.42%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 0.42%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 0.42%   |
| WDC WD1600AVVS-63L2B0 160GB       | 1        | 0.42%   |
| WDC WD15EADS-11P8B2 1TB           | 1        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 41       | 56     | 39.05%  |
| WDC                 | 32       | 43     | 30.48%  |
| Hitachi             | 14       | 18     | 13.33%  |
| Toshiba             | 8        | 10     | 7.62%   |
| Samsung Electronics | 4        | 5      | 3.81%   |
| Maxtor              | 4        | 5      | 3.81%   |
| IBM/Hitachi         | 1        | 1      | 0.95%   |
| Fujitsu             | 1        | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 29     | 25.61%  |
| Kingston            | 13       | 14     | 15.85%  |
| Crucial             | 8        | 8      | 9.76%   |
| WDC                 | 7        | 8      | 8.54%   |
| A-DATA Technology   | 7        | 7      | 8.54%   |
| SanDisk             | 6        | 7      | 7.32%   |
| Goodram             | 5        | 6      | 6.1%    |
| SPCC                | 2        | 2      | 2.44%   |
| PNY                 | 2        | 2      | 2.44%   |
| Intel               | 2        | 3      | 2.44%   |
| WDC WDS1            | 1        | 1      | 1.22%   |
| Transcend           | 1        | 1      | 1.22%   |
| OCZ                 | 1        | 1      | 1.22%   |
| Mushkin             | 1        | 1      | 1.22%   |
| Micron Technology   | 1        | 1      | 1.22%   |
| KingFast            | 1        | 1      | 1.22%   |
| Gigabyte Technology | 1        | 1      | 1.22%   |
| Avant               | 1        | 1      | 1.22%   |
| Acer                | 1        | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 77       | 139    | 46.67%  |
| SSD     | 66       | 95     | 40%     |
| NVMe    | 21       | 25     | 12.73%  |
| Unknown | 1        | 1      | 0.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 99       | 231    | 80.49%  |
| NVMe | 21       | 25     | 17.07%  |
| SAS  | 3        | 4      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 84       | 134    | 52.83%  |
| 0.51-1.0   | 42       | 57     | 26.42%  |
| 1.01-2.0   | 16       | 20     | 10.06%  |
| 2.01-3.0   | 7        | 8      | 4.4%    |
| 3.01-4.0   | 6        | 7      | 3.77%   |
| 4.01-10.0  | 4        | 8      | 2.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 25       | 23.36%  |
| 101-250        | 18       | 16.82%  |
| 1001-2000      | 15       | 14.02%  |
| 501-1000       | 15       | 14.02%  |
| More than 3000 | 14       | 13.08%  |
| 51-100         | 11       | 10.28%  |
| 2001-3000      | 6        | 5.61%   |
| 21-50          | 3        | 2.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 23       | 22.12%  |
| 251-500        | 16       | 15.38%  |
| 101-250        | 16       | 15.38%  |
| 21-50          | 15       | 14.42%  |
| 51-100         | 10       | 9.62%   |
| 501-1000       | 8        | 7.69%   |
| 1001-2000      | 7        | 6.73%   |
| 2001-3000      | 5        | 4.81%   |
| More than 3000 | 4        | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 2.5%    |
| WDC WD5003ABYX-01WERA1 500GB             | 1        | 1      | 2.5%    |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 2.5%    |
| WDC WD20EARX-00PASB0 2TB                 | 1        | 1      | 2.5%    |
| WDC WD1600AVVS-63L2B0 160GB              | 1        | 1      | 2.5%    |
| WDC WD15EADS-11P8B2 1TB                  | 1        | 1      | 2.5%    |
| WDC WD10EZEX-75WN4A0 1TB                 | 1        | 1      | 2.5%    |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 2.5%    |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 2.5%    |
| Toshiba MK7575GSX 752GB                  | 1        | 1      | 2.5%    |
| Toshiba MK6465GSX 640GB                  | 1        | 1      | 2.5%    |
| SPCC Solid State Disk 512GB              | 1        | 1      | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 2.5%    |
| Seagate ST3750330NS 752GB                | 1        | 1      | 2.5%    |
| Seagate ST3500820AS 500GB                | 1        | 1      | 2.5%    |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.5%    |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.5%    |
| Seagate ST3320413CS 320GB                | 1        | 1      | 2.5%    |
| Seagate ST33000651NS 3TB                 | 1        | 1      | 2.5%    |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 2.5%    |
| Seagate ST31000524AS 1TB                 | 1        | 1      | 2.5%    |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 2.5%    |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 2.5%    |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 2.5%    |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 2.5%    |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 2.5%    |
| Maxtor 6Y120M0 122GB                     | 1        | 1      | 2.5%    |
| Maxtor 6L200M0 208GB                     | 1        | 1      | 2.5%    |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 2.5%    |
| IBM/Hitachi IC25N030ATCS04-0 32GB        | 1        | 1      | 2.5%    |
| Hitachi HUA722020ALA331 2TB              | 1        | 1      | 2.5%    |
| Hitachi HTS545032B9SA00 320GB            | 1        | 1      | 2.5%    |
| Hitachi HDT721010SLA360 1TB              | 1        | 1      | 2.5%    |
| Hitachi HDP725016GLA380 160GB            | 1        | 1      | 2.5%    |
| Goodram SSDPR-CL100-480-G3 480GB         | 1        | 1      | 2.5%    |
| Fujitsu MHV2060BH PL 64GB                | 1        | 1      | 2.5%    |
| Crucial CT256M550SSD1 256GB              | 1        | 1      | 2.5%    |
| Crucial CT240M500SSD1 240GB              | 1        | 1      | 2.5%    |
| A-DATA Technology SU650 240GB SSD        | 1        | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 11     | 25.64%  |
| WDC                 | 9        | 9      | 23.08%  |
| Samsung Electronics | 4        | 6      | 10.26%  |
| Hitachi             | 4        | 4      | 10.26%  |
| Maxtor              | 3        | 3      | 7.69%   |
| Toshiba             | 2        | 2      | 5.13%   |
| Crucial             | 2        | 2      | 5.13%   |
| SPCC                | 1        | 1      | 2.56%   |
| IBM/Hitachi         | 1        | 1      | 2.56%   |
| Goodram             | 1        | 1      | 2.56%   |
| Fujitsu             | 1        | 1      | 2.56%   |
| A-DATA Technology   | 1        | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 11     | 33.33%  |
| WDC                 | 8        | 8      | 26.67%  |
| Hitachi             | 4        | 4      | 13.33%  |
| Maxtor              | 3        | 3      | 10%     |
| Toshiba             | 2        | 2      | 6.67%   |
| Samsung Electronics | 1        | 2      | 3.33%   |
| IBM/Hitachi         | 1        | 1      | 3.33%   |
| Fujitsu             | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 27       | 32     | 75%     |
| SSD  | 9        | 10     | 25%     |

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
| Works    | 88       | 205    | 66.67%  |
| Malfunc  | 34       | 42     | 25.76%  |
| Detected | 7        | 9      | 5.3%    |
| Failed   | 3        | 4      | 2.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 65       | 46.76%  |
| AMD                         | 32       | 23.02%  |
| Samsung Electronics         | 11       | 7.91%   |
| ASMedia Technology          | 7        | 5.04%   |
| JMicron Technology          | 6        | 4.32%   |
| Phison Electronics          | 4        | 2.88%   |
| Marvell Technology Group    | 3        | 2.16%   |
| Nvidia                      | 2        | 1.44%   |
| Micron/Crucial Technology   | 2        | 1.44%   |
| Kingston Technology Company | 2        | 1.44%   |
| VIA Technologies            | 1        | 0.72%   |
| ULi Electronics             | 1        | 0.72%   |
| Silicon Motion              | 1        | 0.72%   |
| SanDisk                     | 1        | 0.72%   |
| ADATA Technology            | 1        | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 8.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.4%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 3.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 2.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 2.2%    |
| Phison E12 NVMe Controller                                                              | 4        | 2.2%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 2.2%    |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 2.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 2.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 1.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 1.65%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3        | 1.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.1%    |
| JMicron JMB368 IDE controller                                                           | 2        | 1.1%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.1%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.55%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.55%   |
| ULi ULi M5288 SATA                                                                      | 1        | 0.55%   |
| ULi M5229 IDE                                                                           | 1        | 0.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.55%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.55%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.55%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.55%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.55%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.55%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller                        | 1        | 0.55%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.55%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 0.55%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 0.55%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.55%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.55%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.55%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 1        | 0.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 81       | 57.86%  |
| IDE  | 33       | 23.57%  |
| NVMe | 21       | 15%     |
| RAID | 5        | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 67       | 65.69%  |
| AMD          | 34       | 33.33%  |
| CentaurHauls | 1        | 0.98%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 2.94%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 2.94%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 1.96%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 2        | 1.96%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.96%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.96%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 1.96%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.96%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.96%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.96%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.98%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.98%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 0.98%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 0.98%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.98%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 0.98%   |
| Intel Pentium CPU G3240T @ 2.70GHz          | 1        | 0.98%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 0.98%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 0.98%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 0.98%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.98%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 0.98%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 0.98%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.98%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.98%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.98%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 0.98%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.98%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.98%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 0.98%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 0.98%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.98%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 0.98%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 0.98%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 0.98%   |
| Intel Core i5-3350P CPU @ 3.10GHz           | 1        | 0.98%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 0.98%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 0.98%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 0.98%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 0.98%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1        | 0.98%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.98%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 0.98%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 0.98%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 0.98%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 0.98%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1        | 0.98%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 1        | 0.98%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 0.98%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 0.98%   |
| Intel Core 2 Extreme CPU Q6850 @ 3.00GHz    | 1        | 0.98%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 0.98%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 1        | 0.98%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 0.98%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 0.98%   |
| Intel Celeron D CPU 3.46GHz                 | 1        | 0.98%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 20       | 19.61%  |
| Intel Core i7           | 12       | 11.76%  |
| AMD Ryzen 5             | 10       | 9.8%    |
| Intel Core 2 Duo        | 6        | 5.88%   |
| AMD Ryzen 7             | 6        | 5.88%   |
| Intel Core i3           | 5        | 4.9%    |
| Intel Core 2 Quad       | 5        | 4.9%    |
| Intel Xeon              | 3        | 2.94%   |
| Intel Pentium           | 3        | 2.94%   |
| AMD Athlon II X2        | 3        | 2.94%   |
| Other                   | 2        | 1.96%   |
| Intel Pentium 4         | 2        | 1.96%   |
| Intel Celeron           | 2        | 1.96%   |
| AMD Sempron             | 2        | 1.96%   |
| AMD Phenom II X4        | 2        | 1.96%   |
| Intel Pentium Gold      | 1        | 0.98%   |
| Intel Pentium Dual-Core | 1        | 0.98%   |
| Intel Pentium D         | 1        | 0.98%   |
| Intel Core i9           | 1        | 0.98%   |
| Intel Core 2 Extreme    | 1        | 0.98%   |
| Intel Celeron D         | 1        | 0.98%   |
| Intel Atom              | 1        | 0.98%   |
| CentaurHauls VIA Esther | 1        | 0.98%   |
| AMD Ryzen Threadripper  | 1        | 0.98%   |
| AMD Ryzen 9             | 1        | 0.98%   |
| AMD Ryzen 3             | 1        | 0.98%   |
| AMD Phenom II X6        | 1        | 0.98%   |
| AMD FX                  | 1        | 0.98%   |
| AMD E1                  | 1        | 0.98%   |
| AMD Athlon X4           | 1        | 0.98%   |
| AMD Athlon 64 X2        | 1        | 0.98%   |
| AMD Athlon              | 1        | 0.98%   |
| AMD A4                  | 1        | 0.98%   |
| AMD A10                 | 1        | 0.98%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 37       | 36.27%  |
| 2      | 30       | 29.41%  |
| 6      | 16       | 15.69%  |
| 8      | 9        | 8.82%   |
| 1      | 6        | 5.88%   |
| 12     | 3        | 2.94%   |
| 10     | 1        | 0.98%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 102      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 51.96%  |
| 2      | 49       | 48.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 100      | 98.04%  |
| 32-bit         | 2        | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 13.73%  |
| 0x306c3    | 9        | 8.82%   |
| 0x206a7    | 7        | 6.86%   |
| 0x306a9    | 6        | 5.88%   |
| 0x08701021 | 6        | 5.88%   |
| 0x1067a    | 5        | 4.9%    |
| 0x0800820d | 5        | 4.9%    |
| 0xa0653    | 3        | 2.94%   |
| 0x906ed    | 3        | 2.94%   |
| 0x010000c8 | 3        | 2.94%   |
| 0xa0671    | 2        | 1.96%   |
| 0x6fb      | 2        | 1.96%   |
| 0x506e3    | 2        | 1.96%   |
| 0x306f2    | 2        | 1.96%   |
| 0x10677    | 2        | 1.96%   |
| 0xf65      | 1        | 0.98%   |
| 0xf64      | 1        | 0.98%   |
| 0xf4a      | 1        | 0.98%   |
| 0xf29      | 1        | 0.98%   |
| 0xa0655    | 1        | 0.98%   |
| 0x906eb    | 1        | 0.98%   |
| 0x906ea    | 1        | 0.98%   |
| 0x6fd      | 1        | 0.98%   |
| 0x406c3    | 1        | 0.98%   |
| 0x306e4    | 1        | 0.98%   |
| 0x30661    | 1        | 0.98%   |
| 0x206d7    | 1        | 0.98%   |
| 0x20655    | 1        | 0.98%   |
| 0x20652    | 1        | 0.98%   |
| 0x106e5    | 1        | 0.98%   |
| 0x10676    | 1        | 0.98%   |
| 0x0a201016 | 1        | 0.98%   |
| 0x0a201009 | 1        | 0.98%   |
| 0x08301039 | 1        | 0.98%   |
| 0x0810100b | 1        | 0.98%   |
| 0x0800820b | 1        | 0.98%   |
| 0x08001138 | 1        | 0.98%   |
| 0x08001137 | 1        | 0.98%   |
| 0x08001126 | 1        | 0.98%   |
| 0x0700010f | 1        | 0.98%   |
| 0x06006118 | 1        | 0.98%   |
| 0x0600063e | 1        | 0.98%   |
| 0x03000027 | 1        | 0.98%   |
| 0x010000dc | 1        | 0.98%   |
| 0x010000db | 1        | 0.98%   |
| 0x01000083 | 1        | 0.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 14       | 13.73%  |
| Penryn      | 10       | 9.8%    |
| SandyBridge | 8        | 7.84%   |
| IvyBridge   | 8        | 7.84%   |
| Zen 2       | 7        | 6.86%   |
| K10         | 7        | 6.86%   |
| Zen+        | 6        | 5.88%   |
| KabyLake    | 6        | 5.88%   |
| Zen         | 4        | 3.92%   |
| NetBurst    | 4        | 3.92%   |
| CometLake   | 4        | 3.92%   |
| K8 Hammer   | 3        | 2.94%   |
| Core        | 3        | 2.94%   |
| Zen 3       | 2        | 1.96%   |
| Westmere    | 2        | 1.96%   |
| Skylake     | 2        | 1.96%   |
| Nehalem     | 2        | 1.96%   |
| Unknown     | 2        | 1.96%   |
| Steamroller | 1        | 0.98%   |
| Silvermont  | 1        | 0.98%   |
| K10 Llano   | 1        | 0.98%   |
| Jaguar      | 1        | 0.98%   |
| Icelake     | 1        | 0.98%   |
| Excavator   | 1        | 0.98%   |
| Bulldozer   | 1        | 0.98%   |
| Bonnell     | 1        | 0.98%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 46       | 40.71%  |
| AMD              | 34       | 30.09%  |
| Intel            | 32       | 28.32%  |
| VIA Technologies | 1        | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6        | 5.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5        | 4.24%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 3.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4        | 3.39%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 2.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 2.54%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 3        | 2.54%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 3        | 2.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2        | 1.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2        | 1.69%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 1.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.69%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 2        | 1.69%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                                        | 2        | 1.69%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                                    | 2        | 1.69%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.69%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 1.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 1.69%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro]            | 1        | 0.85%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.85%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.85%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1        | 0.85%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.85%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.85%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1        | 0.85%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.85%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1        | 0.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 0.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1        | 0.85%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 0.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 0.85%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 0.85%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 1        | 0.85%   |
| Nvidia GK107GL [Quadro K600]                                                             | 1        | 0.85%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 0.85%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1        | 0.85%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                                        | 1        | 0.85%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 1        | 0.85%   |
| Nvidia GF114 [GeForce GTX 560 SE]                                                        | 1        | 0.85%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1        | 0.85%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 0.85%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 1        | 0.85%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 0.85%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 0.85%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 1        | 0.85%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1        | 0.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 0.85%   |
| Intel HD Graphics 630                                                                    | 1        | 0.85%   |
| Intel HD Graphics 530                                                                    | 1        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 0.85%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 45       | 42.86%  |
| 1 x AMD        | 31       | 29.52%  |
| 1 x Intel      | 23       | 21.9%   |
| Intel + AMD    | 2        | 1.9%    |
| 3 x AMD        | 1        | 0.95%   |
| 2 x AMD        | 1        | 0.95%   |
| 1 x VIA        | 1        | 0.95%   |
| Intel + Nvidia | 1        | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 67       | 65.05%  |
| Proprietary | 33       | 32.04%  |
| Unknown     | 3        | 2.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 29.52%  |
| 0.51-1.0   | 18       | 17.14%  |
| 1.01-2.0   | 15       | 14.29%  |
| 3.01-4.0   | 13       | 12.38%  |
| 7.01-8.0   | 11       | 10.48%  |
| 0.01-0.5   | 10       | 9.52%   |
| 5.01-6.0   | 4        | 3.81%   |
| 8.01-16.0  | 2        | 1.9%    |
| 2.01-3.0   | 1        | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 16.81%  |
| Goldstar             | 15       | 13.27%  |
| Dell                 | 13       | 11.5%   |
| Acer                 | 10       | 8.85%   |
| Hewlett-Packard      | 6        | 5.31%   |
| Ancor Communications | 5        | 4.42%   |
| ViewSonic            | 4        | 3.54%   |
| Philips              | 4        | 3.54%   |
| Iiyama               | 3        | 2.65%   |
| Fujitsu Siemens      | 3        | 2.65%   |
| ASUSTek Computer     | 3        | 2.65%   |
| AOC                  | 3        | 2.65%   |
| Vizio                | 2        | 1.77%   |
| Vestel Elektronik    | 2        | 1.77%   |
| Medion               | 2        | 1.77%   |
| Eizo                 | 2        | 1.77%   |
| BenQ                 | 2        | 1.77%   |
| Videoseven           | 1        | 0.88%   |
| Sony                 | 1        | 0.88%   |
| Sceptre Tech         | 1        | 0.88%   |
| SANYO                | 1        | 0.88%   |
| SAC                  | 1        | 0.88%   |
| RIS                  | 1        | 0.88%   |
| NEC Computers        | 1        | 0.88%   |
| MSI                  | 1        | 0.88%   |
| Lenovo               | 1        | 0.88%   |
| IBM                  | 1        | 0.88%   |
| HYO                  | 1        | 0.88%   |
| Grundig              | 1        | 0.88%   |
| Gigabyte Technology  | 1        | 0.88%   |
| DTV                  | 1        | 0.88%   |
| Arnos Instruments    | 1        | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 5.17%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                           | 2        | 1.72%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                    | 2        | 1.72%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                   | 2        | 1.72%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2        | 1.72%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                      | 1        | 0.86%   |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                    | 1        | 0.86%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                  | 1        | 0.86%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 0.86%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 0.86%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1        | 0.86%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                 | 1        | 0.86%   |
| Sony TV SNY0801 1360x768                                                | 1        | 0.86%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                  | 1        | 0.86%   |
| SANYO LCD MONITOR SAN2213 1920x1080 474x296mm 22.0-inch                 | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch    | 1        | 0.86%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch    | 1        | 0.86%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch      | 1        | 0.86%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.86%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch   | 1        | 0.86%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch       | 1        | 0.86%   |
| Samsung Electronics C27JG5x SAM0F57 2560x1440 600x340mm 27.2-inch       | 1        | 0.86%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.86%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                   | 1        | 0.86%   |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                        | 1        | 0.86%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1        | 0.86%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                | 1        | 0.86%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1        | 0.86%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 1        | 0.86%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch             | 1        | 0.86%   |
| MSI MAG271C MSI3FA6 1920x1080 600x340mm 27.2-inch                       | 1        | 0.86%   |
| Lenovo LEN L192p LEN24CB 1280x1024 376x301mm 19.0-inch                  | 1        | 0.86%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                    | 1        | 0.86%   |
| IBM L191p IBM24CB 1280x1024 380x300mm 19.1-inch                         | 1        | 0.86%   |
| HYO DUAL-DVI HYO049B 2560x1440 597x336mm 27.0-inch                      | 1        | 0.86%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch              | 1        | 0.86%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch              | 1        | 0.86%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch             | 1        | 0.86%   |
| Hewlett-Packard w17e HWP26E0 1440x900 370x230mm 17.2-inch               | 1        | 0.86%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch              | 1        | 0.86%   |
| Hewlett-Packard 27es HWP3325 1920x1080 600x340mm 27.2-inch              | 1        | 0.86%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch              | 1        | 0.86%   |
| Grundig WXGA GRU4448 1600x1200                                          | 1        | 0.86%   |
| Goldstar W2361 GSM56FA 1920x1080 510x290mm 23.1-inch                    | 1        | 0.86%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                    | 1        | 0.86%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch                | 1        | 0.86%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 1        | 0.86%   |
| Goldstar L222W GSM5664 1680x1050 474x296mm 22.0-inch                    | 1        | 0.86%   |
| Goldstar L1715S GSM436F 1280x1024 338x270mm 17.0-inch                   | 1        | 0.86%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 1        | 0.86%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 1        | 0.86%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 1        | 0.86%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                  | 1        | 0.86%   |
| Goldstar E2411 GSM583B 1920x1080 477x268mm 21.5-inch                    | 1        | 0.86%   |
| Goldstar E2350 GSM578F 1920x1080 510x290mm 23.1-inch                    | 1        | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 48       | 43.64%  |
| 2560x1440 (QHD)    | 10       | 9.09%   |
| 3840x2160 (4K)     | 9        | 8.18%   |
| 1280x1024 (SXGA)   | 8        | 7.27%   |
| 1680x1050 (WSXGA+) | 7        | 6.36%   |
| 1600x1200          | 7        | 6.36%   |
| 1440x900 (WXGA+)   | 4        | 3.64%   |
| 3440x1440          | 3        | 2.73%   |
| 1920x1200 (WUXGA)  | 3        | 2.73%   |
| 1366x768 (WXGA)    | 3        | 2.73%   |
| 1360x768           | 3        | 2.73%   |
| 1600x900 (HD+)     | 2        | 1.82%   |
| 2560x1080          | 1        | 0.91%   |
| 2048x1536          | 1        | 0.91%   |
| 1024x768 (XGA)     | 1        | 0.91%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 19       | 16.96%  |
| 21      | 16       | 14.29%  |
| 24      | 13       | 11.61%  |
| 23      | 12       | 10.71%  |
| 31      | 7        | 6.25%   |
| 19      | 7        | 6.25%   |
| 18      | 7        | 6.25%   |
| 22      | 6        | 5.36%   |
| 84      | 4        | 3.57%   |
| 34      | 4        | 3.57%   |
| 20      | 3        | 2.68%   |
| 17      | 3        | 2.68%   |
| 65      | 2        | 1.79%   |
| 15      | 2        | 1.79%   |
| 72      | 1        | 0.89%   |
| 54      | 1        | 0.89%   |
| 49      | 1        | 0.89%   |
| 42      | 1        | 0.89%   |
| 26      | 1        | 0.89%   |
| 25      | 1        | 0.89%   |
| Unknown | 1        | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 42       | 38.89%  |
| 401-500     | 33       | 30.56%  |
| 601-700     | 8        | 7.41%   |
| 351-400     | 5        | 4.63%   |
| 301-350     | 5        | 4.63%   |
| 1501-2000   | 5        | 4.63%   |
| 701-800     | 4        | 3.7%    |
| 1001-1500   | 4        | 3.7%    |
| 901-1000    | 1        | 0.93%   |
| Unknown     | 1        | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 73       | 68.22%  |
| 16/10 | 14       | 13.08%  |
| 5/4   | 8        | 7.48%   |
| 4/3   | 8        | 7.48%   |
| 21/9  | 4        | 3.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 38.18%  |
| 301-350        | 19       | 17.27%  |
| 151-200        | 13       | 11.82%  |
| 351-500        | 11       | 10%     |
| More than 1000 | 9        | 8.18%   |
| 141-150        | 7        | 6.36%   |
| 251-300        | 5        | 4.55%   |
| 111-120        | 1        | 0.91%   |
| 101-110        | 1        | 0.91%   |
| 501-1000       | 1        | 0.91%   |
| Unknown        | 1        | 0.91%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 74       | 71.15%  |
| 101-120 | 22       | 21.15%  |
| 1-50    | 5        | 4.81%   |
| 161-240 | 1        | 0.96%   |
| 121-160 | 1        | 0.96%   |
| Unknown | 1        | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 85       | 83.33%  |
| 2     | 14       | 13.73%  |
| 3     | 2        | 1.96%   |
| 0     | 1        | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 60       | 44.44%  |
| Intel                    | 40       | 29.63%  |
| Qualcomm Atheros         | 8        | 5.93%   |
| Broadcom                 | 6        | 4.44%   |
| TP-Link                  | 4        | 2.96%   |
| Ralink                   | 3        | 2.22%   |
| Ralink Technology        | 2        | 1.48%   |
| Marvell Technology Group | 2        | 1.48%   |
| Broadcom Limited         | 2        | 1.48%   |
| VIA Technologies         | 1        | 0.74%   |
| U-Blox                   | 1        | 0.74%   |
| Nvidia                   | 1        | 0.74%   |
| NetGear                  | 1        | 0.74%   |
| Edimax Technology        | 1        | 0.74%   |
| D-Link System            | 1        | 0.74%   |
| ASUSTek Computer         | 1        | 0.74%   |
| Aquantia                 | 1        | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 47       | 32.41%  |
| Intel I211 Gigabit Network Connection                                                         | 6        | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5        | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 4        | 2.76%   |
| Intel Ethernet Connection (2) I218-V                                                          | 4        | 2.76%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 4        | 2.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 3        | 2.07%   |
| Intel Ethernet Connection I217-LM                                                             | 3        | 2.07%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 2.07%   |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 2.07%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 1.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 1.38%   |
| Intel Wireless 8260                                                                           | 2        | 1.38%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.38%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 1.38%   |
| Intel Ethernet Connection (14) I219-V                                                         | 2        | 1.38%   |
| Intel Ethernet Connection (11) I219-V                                                         | 2        | 1.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.69%   |
| U-Blox [u-blox 8]                                                                             | 1        | 0.69%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 0.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.69%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.69%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.69%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.69%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.69%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 0.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.69%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.69%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.69%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 0.69%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 0.69%   |
| NetGear A6210                                                                                 | 1        | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 0.69%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                             | 1        | 0.69%   |
| Intel Wireless 7260                                                                           | 1        | 0.69%   |
| Intel Ethernet Connection I217-V                                                              | 1        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 0.69%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 1        | 0.69%   |
| Intel 82562EZ 10/100 Ethernet Controller                                                      | 1        | 0.69%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 1        | 0.69%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 1        | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 1        | 0.69%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                                       | 1        | 0.69%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                                       | 1        | 0.69%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                               | 1        | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 23.53%  |
| Intel                 | 7        | 20.59%  |
| TP-Link               | 4        | 11.76%  |
| Ralink                | 3        | 8.82%   |
| Qualcomm Atheros      | 3        | 8.82%   |
| Broadcom              | 3        | 8.82%   |
| Ralink Technology     | 2        | 5.88%   |
| NetGear               | 1        | 2.94%   |
| Edimax Technology     | 1        | 2.94%   |
| Broadcom Limited      | 1        | 2.94%   |
| ASUSTek Computer      | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 5.88%   |
| Intel Wireless 8260                                                                           | 2        | 5.88%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 5.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 1        | 2.94%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                        | 1        | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 2.94%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 2.94%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 1        | 2.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 2.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 2.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 2.94%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.94%   |
| Realtek 802.11ac NIC                                                                          | 1        | 2.94%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 2.94%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 2.94%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                                   | 1        | 2.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 2.94%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.94%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 2.94%   |
| NetGear A6210                                                                                 | 1        | 2.94%   |
| Intel Wireless 7260                                                                           | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 2.94%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 2.94%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 1        | 2.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 2.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 2.94%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 2.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 2.94%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                                      | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 56       | 51.85%  |
| Intel                    | 37       | 34.26%  |
| Qualcomm Atheros         | 5        | 4.63%   |
| Broadcom                 | 3        | 2.78%   |
| Marvell Technology Group | 2        | 1.85%   |
| VIA Technologies         | 1        | 0.93%   |
| Nvidia                   | 1        | 0.93%   |
| D-Link System            | 1        | 0.93%   |
| Broadcom Limited         | 1        | 0.93%   |
| Aquantia                 | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47       | 42.73%  |
| Intel I211 Gigabit Network Connection                             | 6        | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 4.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 3.64%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 3.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 3.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 2.73%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.73%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.73%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 2        | 1.82%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.82%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.91%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.91%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.91%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.91%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.91%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 0.91%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.91%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.91%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 0.91%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.91%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 102      | 75%     |
| WiFi     | 33       | 24.26%  |
| Modem    | 1        | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 73.33%  |
| WiFi     | 28       | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 77       | 75.49%  |
| 2     | 22       | 21.57%  |
| 3     | 3        | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 90       | 87.38%  |
| Yes  | 13       | 12.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 37.5%   |
| Cambridge Silicon Radio         | 3        | 18.75%  |
| ASUSTek Computer                | 3        | 18.75%  |
| Realtek Semiconductor           | 1        | 6.25%   |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| Broadcom                        | 1        | 6.25%   |
| Apple                           | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3        | 18.75%  |
| Intel Bluetooth wireless interface                    | 2        | 12.5%   |
| Intel AX200 Bluetooth                                 | 2        | 12.5%   |
| Realtek Bluetooth Radio                               | 1        | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 6.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 6.25%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 6.25%   |
| ASUS BCM20702A0                                       | 1        | 6.25%   |
| Apple Bluetooth USB Host Controller                   | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 64       | 35.16%  |
| Nvidia              | 44       | 24.18%  |
| AMD                 | 44       | 24.18%  |
| Creative Labs       | 7        | 3.85%   |
| C-Media Electronics | 4        | 2.2%    |
| ROCCAT              | 2        | 1.1%    |
| JMTek               | 2        | 1.1%    |
| Focusrite-Novation  | 2        | 1.1%    |
| VIA Technologies    | 1        | 0.55%   |
| Unknown             | 1        | 0.55%   |
| ULi Electronics     | 1        | 0.55%   |
| Texas Instruments   | 1        | 0.55%   |
| TerraTec Electronic | 1        | 0.55%   |
| Tenx Technology     | 1        | 0.55%   |
| Schiit Audio        | 1        | 0.55%   |
| Razer USA           | 1        | 0.55%   |
| Microsoft           | 1        | 0.55%   |
| Logitech            | 1        | 0.55%   |
| Kingston Technology | 1        | 0.55%   |
| GN Netcom           | 1        | 0.55%   |
| Fortemedia          | 1        | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 4.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 4.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 4.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 3.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 3.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 2.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 2.43%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.43%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.94%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 1.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.46%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 1.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.46%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 1.46%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 3        | 1.46%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.46%   |
| ROCCAT Khan AIMO                                                           | 2        | 0.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 0.97%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2        | 0.97%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.97%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.97%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 0.97%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 0.97%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 2        | 0.97%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 2        | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 0.97%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 0.97%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.49%   |
| Unknown Realtek USB Audio Rear                                             | 1        | 0.49%   |
| Unknown Realtek USB Audio Front                                            | 1        | 0.49%   |
| ULi Electronics HD Audio Controller                                        | 1        | 0.49%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.49%   |
| TerraTec Electronic Aureon Dual USB                                        | 1        | 0.49%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.49%   |
| Schiit Audio I'm Fulla Schiit                                              | 1        | 0.49%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.49%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 23       | 20.91%  |
| Kingston                     | 19       | 17.27%  |
| Corsair                      | 19       | 17.27%  |
| G.Skill                      | 14       | 12.73%  |
| SK hynix                     | 9        | 8.18%   |
| Samsung Electronics          | 7        | 6.36%   |
| Crucial                      | 4        | 3.64%   |
| Nanya Technology             | 3        | 2.73%   |
| Micron Technology            | 3        | 2.73%   |
| Patriot                      | 2        | 1.82%   |
| Smart                        | 1        | 0.91%   |
| RZX                          | 1        | 0.91%   |
| PNY                          | 1        | 0.91%   |
| Patriot Memory (PDP Systems) | 1        | 0.91%   |
| OCZ                          | 1        | 0.91%   |
| Axiom                        | 1        | 0.91%   |
| A-DATA Technology            | 1        | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                | 4        | 3.2%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                              | 3        | 2.4%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                               | 3        | 2.4%    |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s             | 3        | 2.4%    |
| Unknown RAM Module 4GB DIMM SDRAM                                    | 2        | 1.6%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                              | 2        | 1.6%    |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                           | 2        | 1.6%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                | 2        | 1.6%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 2        | 1.6%    |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                 | 2        | 1.6%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                  | 2        | 1.6%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s               | 2        | 1.6%    |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM 3000MT/s                     | 2        | 1.6%    |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                         | 1        | 0.8%    |
| Unknown RAM Module 512MB DIMM SDRAM                                  | 1        | 0.8%    |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                            | 1        | 0.8%    |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                            | 1        | 0.8%    |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                             | 1        | 0.8%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                         | 1        | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                             | 1        | 0.8%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                          | 1        | 0.8%    |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                           | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM SDRAM                                 | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                          | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                           | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s                           | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM DDR                                   | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                               | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM 667MT/s                               | 1        | 0.8%    |
| Unknown RAM Module 1024MB DIMM                                       | 1        | 0.8%    |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3                           | 1        | 0.8%    |
| Smart RAM SH564128FH8N0QHSCG 4096MB DIMM DDR3 1333MT/s               | 1        | 0.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1        | 0.8%    |
| SK hynix RAM HMT351U7EFR8C-PB 4096MB DIMM DDR3 1600MT/s              | 1        | 0.8%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 1        | 0.8%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s                 | 1        | 0.8%    |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                 | 1        | 0.8%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                 | 1        | 0.8%    |
| SK hynix RAM HMT125U6DFR8C-H9 2GB DIMM DDR3 1066MT/s                 | 1        | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                | 1        | 0.8%    |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                 | 1        | 0.8%    |
| Samsung RAM M391B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                  | 1        | 0.8%    |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1333MT/s                  | 1        | 0.8%    |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s                 | 1        | 0.8%    |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s               | 1        | 0.8%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 1639MT/s                 | 1        | 0.8%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s                  | 1        | 0.8%    |
| RZX RAM D3D10M1600B-8G 8GB DIMM DDR3 1600MT/s                        | 1        | 0.8%    |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s                 | 1        | 0.8%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s                   | 1        | 0.8%    |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s                   | 1        | 0.8%    |
| Patriot Memory (PDP Systems) RAM PSD48G320081 8GB DIMM DDR4 3200MT/s | 1        | 0.8%    |
| OCZ RAM OCZ2N800SR2G 2048MB DIMM DDR 800MT/s                         | 1        | 0.8%    |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                   | 1        | 0.8%    |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s                    | 1        | 0.8%    |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s                   | 1        | 0.8%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                  | 1        | 0.8%    |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                  | 1        | 0.8%    |
| Kingston RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1        | 0.8%    |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                        | 1        | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 36       | 36%     |
| DDR3    | 35       | 35%     |
| DDR2    | 10       | 10%     |
| Unknown | 9        | 9%      |
| SDRAM   | 5        | 5%      |
| DDR     | 5        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 97       | 97%     |
| SODIMM | 3        | 3%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 34       | 31.48%  |
| 8192  | 33       | 30.56%  |
| 2048  | 17       | 15.74%  |
| 16384 | 9        | 8.33%   |
| 1024  | 9        | 8.33%   |
| 32768 | 3        | 2.78%   |
| 512   | 3        | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 19.83%  |
| 1333    | 15       | 12.93%  |
| 2133    | 8        | 6.9%    |
| 3600    | 7        | 6.03%   |
| 3000    | 6        | 5.17%   |
| 800     | 6        | 5.17%   |
| 3200    | 5        | 4.31%   |
| Unknown | 5        | 4.31%   |
| 3466    | 4        | 3.45%   |
| 667     | 4        | 3.45%   |
| 2933    | 3        | 2.59%   |
| 2400    | 3        | 2.59%   |
| 333     | 3        | 2.59%   |
| 49926   | 2        | 1.72%   |
| 3400    | 2        | 1.72%   |
| 2667    | 2        | 1.72%   |
| 2666    | 2        | 1.72%   |
| 2048    | 2        | 1.72%   |
| 1867    | 2        | 1.72%   |
| 1800    | 2        | 1.72%   |
| 1639    | 2        | 1.72%   |
| 400     | 2        | 1.72%   |
| 3266    | 1        | 0.86%   |
| 3100    | 1        | 0.86%   |
| 1400    | 1        | 0.86%   |
| 1066    | 1        | 0.86%   |
| 533     | 1        | 0.86%   |
| 200     | 1        | 0.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Seiko Epson           | 1        | 20%     |
| Lexmark International | 1        | 20%     |
| Konica Minolta        | 1        | 20%     |
| Canon                 | 1        | 20%     |
| Brother Industries    | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson L380 Series       | 1        | 20%     |
| Lexmark International CS417dn | 1        | 20%     |
| Konica Minolta 206            | 1        | 20%     |
| Canon MF641C                  | 1        | 20%     |
| Brother DCP-L2540DW           | 1        | 20%     |

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
| Logitech                      | 8        | 50%     |
| Microsoft                     | 3        | 18.75%  |
| Generalplus Technology        | 2        | 12.5%   |
| Sunplus Technology            | 1        | 6.25%   |
| Sunplus Innovation Technology | 1        | 6.25%   |
| Huawei Technologies           | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                               | 3        | 18.75%  |
| Logitech Webcam C930e                                   | 2        | 12.5%   |
| Logitech Webcam C270                                    | 2        | 12.5%   |
| Logitech Webcam C200                                    | 2        | 12.5%   |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 6.25%   |
| Sunplus Full HD webcam                                  | 1        | 6.25%   |
| Logitech Webcam Pro 9000                                | 1        | 6.25%   |
| Logitech B525 HD Webcam                                 | 1        | 6.25%   |
| Huawei UVC Camera                                       | 1        | 6.25%   |
| Generalplus GENERAL WEBCAM                              | 1        | 6.25%   |
| Generalplus 808 Camera                                  | 1        | 6.25%   |

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
| 0     | 94       | 92.16%  |
| 1     | 7        | 6.86%   |
| 3     | 1        | 0.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unassigned class      | 3        | 33.33%  |
| Graphics card         | 3        | 33.33%  |
| Net/wireless          | 1        | 11.11%  |
| Multimedia controller | 1        | 11.11%  |
| Camera                | 1        | 11.11%  |

