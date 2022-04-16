MX - Tested Hardware & Statistics (Desktops)
--------------------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 128

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| ASRock        | K8A780LM                    | [2340ea8f96](https://linux-hardware.org/?probe=2340ea8f96) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| ASRock        | K8A780LM                    | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASRock        | K8A780LM                    | [ba37404fee](https://linux-hardware.org/?probe=ba37404fee) | Jan 14, 2021 |
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
| ASUSTek       | P8Z77-V LX                  | [84c9f3b9cb](https://linux-hardware.org/?probe=84c9f3b9cb) | Apr 02, 2020 |
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
| MX 19          | 42       | 45.16%  |
| MX 20          | 21       | 22.58%  |
| MX 21          | 16       | 17.2%   |
| MX 18          | 11       | 11.83%  |
| MX 18.1        | 1        | 1.08%   |
| MX 17          | 1        | 1.08%   |
| MX 16-migrated | 1        | 1.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| MX   | 92       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 20       | 19.61%  |
| 5.6.0-2-amd64              | 6        | 5.88%   |
| 4.19.0-17-amd64            | 5        | 4.9%    |
| 5.8.0-3-amd64              | 4        | 3.92%   |
| 5.10.0-5mx-amd64           | 4        | 3.92%   |
| 4.19.0-14-amd64            | 4        | 3.92%   |
| 5.14.0-4mx-amd64           | 3        | 2.94%   |
| 4.19.0-5-amd64             | 3        | 2.94%   |
| 4.19.0-18-amd64            | 3        | 2.94%   |
| 4.19.0-13-amd64            | 3        | 2.94%   |
| 4.19.0-1-amd64             | 3        | 2.94%   |
| 5.8.16-antix.1-amd64-smp   | 2        | 1.96%   |
| 5.4.0-3-amd64              | 2        | 1.96%   |
| 5.14.0-3mx-amd64           | 2        | 1.96%   |
| 5.10.0-9-amd64             | 2        | 1.96%   |
| 5.10.0-11-amd64            | 2        | 1.96%   |
| 4.19.0-16-amd64            | 2        | 1.96%   |
| 4.19.0-12-amd64            | 2        | 1.96%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 0.98%   |
| 5.5.0-7.1-liquorix-amd64   | 1        | 0.98%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 0.98%   |
| 5.5.0-10.2-liquorix-amd64  | 1        | 0.98%   |
| 5.5.0-050500rc1-lowlatency | 1        | 0.98%   |
| 5.4.7-antix.1-amd64-smp    | 1        | 0.98%   |
| 5.4.10                     | 1        | 0.98%   |
| 5.3.0-10.1-liquorix-amd64  | 1        | 0.98%   |
| 5.3.0-0.bpo.2-amd64        | 1        | 0.98%   |
| 5.2.21-antix.2-amd64-smp   | 1        | 0.98%   |
| 5.16.0-rc5-hwmon-next+     | 1        | 0.98%   |
| 5.15.0-2-amd64             | 1        | 0.98%   |
| 5.15.0-1mx-amd64           | 1        | 0.98%   |
| 5.15.0-0.bpo.2-amd64       | 1        | 0.98%   |
| 5.14.0-2mx-amd64           | 1        | 0.98%   |
| 5.11.0-16.1-liquorix-amd64 | 1        | 0.98%   |
| 5.10.52-antix.1-amd64-smp  | 1        | 0.98%   |
| 5.10.0-9mx-amd64           | 1        | 0.98%   |
| 5.10.0-8mx-rt-amd64        | 1        | 0.98%   |
| 5.10.0-8mx-amd64           | 1        | 0.98%   |
| 5.10.0-4mx-amd64           | 1        | 0.98%   |
| 5.10.0-13-amd64            | 1        | 0.98%   |
| 5.10.0-10-amd64            | 1        | 0.98%   |
| 5.10.0-0.bpo.3-amd64       | 1        | 0.98%   |
| 4.9.91-antix.1-amd64-smp   | 1        | 0.98%   |
| 4.19.0-9-686-pae           | 1        | 0.98%   |
| 4.19.0-10-686-pae          | 1        | 0.98%   |
| 4.19.0-1-686-pae           | 1        | 0.98%   |
| 4.18.0-16.1-liquorix-amd64 | 1        | 0.98%   |
| 4.15.0-1-686-pae           | 1        | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 42       | 43.75%  |
| 5.10.0  | 15       | 15.63%  |
| 5.6.0   | 6        | 6.25%   |
| 5.14.0  | 6        | 6.25%   |
| 5.5.0   | 5        | 5.21%   |
| 5.8.0   | 4        | 4.17%   |
| 5.15.0  | 3        | 3.13%   |
| 5.8.16  | 2        | 2.08%   |
| 5.4.0   | 2        | 2.08%   |
| 5.3.0   | 2        | 2.08%   |
| 5.4.7   | 1        | 1.04%   |
| 5.4.10  | 1        | 1.04%   |
| 5.2.21  | 1        | 1.04%   |
| 5.16.0  | 1        | 1.04%   |
| 5.11.0  | 1        | 1.04%   |
| 5.10.52 | 1        | 1.04%   |
| 4.9.91  | 1        | 1.04%   |
| 4.18.0  | 1        | 1.04%   |
| 4.15.0  | 1        | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 42       | 43.75%  |
| 5.10    | 16       | 16.67%  |
| 5.8     | 6        | 6.25%   |
| 5.6     | 6        | 6.25%   |
| 5.14    | 6        | 6.25%   |
| 5.5     | 5        | 5.21%   |
| 5.4     | 4        | 4.17%   |
| 5.15    | 3        | 3.13%   |
| 5.3     | 2        | 2.08%   |
| 5.2     | 1        | 1.04%   |
| 5.16    | 1        | 1.04%   |
| 5.11    | 1        | 1.04%   |
| 4.9     | 1        | 1.04%   |
| 4.18    | 1        | 1.04%   |
| 4.15    | 1        | 1.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 88       | 95.65%  |
| i686   | 4        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 74       | 80.43%  |
| KDE5             | 12       | 13.04%  |
| MATE             | 2        | 2.17%   |
| LXQt             | 1        | 1.09%   |
| lightdm-xsession | 1        | 1.09%   |
| KDE4             | 1        | 1.09%   |
| KDE              | 1        | 1.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 92       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 84       | 91.3%   |
| SDDM    | 8        | 8.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 33       | 34.02%  |
| en_US   | 26       | 26.8%   |
| de_DE   | 7        | 7.22%   |
| sk_SK   | 5        | 5.15%   |
| en_GB   | 5        | 5.15%   |
| es_ES   | 4        | 4.12%   |
| pt_BR   | 3        | 3.09%   |
| pl_PL   | 3        | 3.09%   |
| fr_FR   | 2        | 2.06%   |
| de_CH   | 2        | 2.06%   |
| uk_UA   | 1        | 1.03%   |
| tr_TR   | 1        | 1.03%   |
| sv_SE   | 1        | 1.03%   |
| ru_RU   | 1        | 1.03%   |
| hu_HU   | 1        | 1.03%   |
| en_IE   | 1        | 1.03%   |
| en_AU   | 1        | 1.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 60       | 65.22%  |
| EFI  | 32       | 34.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 87       | 94.57%  |
| Btrfs   | 3        | 3.26%   |
| Overlay | 2        | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 50       | 54.35%  |
| MBR     | 40       | 43.48%  |
| Unknown | 2        | 2.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 58       | 61.05%  |
| Yes       | 37       | 38.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 51       | 55.43%  |
| No        | 41       | 44.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 21       | 22.83%  |
| Gigabyte Technology | 17       | 18.48%  |
| MSI                 | 12       | 13.04%  |
| Dell                | 12       | 13.04%  |
| ASRock              | 10       | 10.87%  |
| Hewlett-Packard     | 6        | 6.52%   |
| Intel               | 4        | 4.35%   |
| Lenovo              | 2        | 2.17%   |
| IBM                 | 1        | 1.09%   |
| Huanan              | 1        | 1.09%   |
| GreatWall           | 1        | 1.09%   |
| Gateway             | 1        | 1.09%   |
| GALAX               | 1        | 1.09%   |
| Fujitsu Siemens     | 1        | 1.09%   |
| Fujitsu             | 1        | 1.09%   |
| ECS                 | 1        | 1.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 3        | 3.26%   |
| Dell Studio 540                     | 2        | 2.17%   |
| Dell OptiPlex 9010                  | 2        | 2.17%   |
| ASRock K8A780LM                     | 2        | 2.17%   |
| MSI MS-7C94                         | 1        | 1.09%   |
| MSI MS-7C88                         | 1        | 1.09%   |
| MSI MS-7C56                         | 1        | 1.09%   |
| MSI MS-7B86                         | 1        | 1.09%   |
| MSI MS-7A34                         | 1        | 1.09%   |
| MSI MS-7917                         | 1        | 1.09%   |
| MSI MS-7815                         | 1        | 1.09%   |
| MSI MS-7808                         | 1        | 1.09%   |
| MSI MS-7693                         | 1        | 1.09%   |
| MSI MS-7641                         | 1        | 1.09%   |
| MSI MS-7199                         | 1        | 1.09%   |
| MSI GEG                             | 1        | 1.09%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 1.09%   |
| Lenovo 10AAS1QB0B                   | 1        | 1.09%   |
| Intel MAHOBAY                       | 1        | 1.09%   |
| Intel H81                           | 1        | 1.09%   |
| Intel DCP847SKE G80890-105          | 1        | 1.09%   |
| IBM 8183B2U                         | 1        | 1.09%   |
| Huanan X99-F8                       | 1        | 1.09%   |
| HP Z400 Workstation                 | 1        | 1.09%   |
| HP Z230 Tower Workstation           | 1        | 1.09%   |
| HP Z220 CMT Workstation             | 1        | 1.09%   |
| HP ProDesk 600 G1 DM                | 1        | 1.09%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 1.09%   |
| HP 3031h                            | 1        | 1.09%   |
| GreatWall U320                      | 1        | 1.09%   |
| Gigabyte Z68AP-D3                   | 1        | 1.09%   |
| Gigabyte Z390 UD                    | 1        | 1.09%   |
| Gigabyte Z390 GAMING X              | 1        | 1.09%   |
| Gigabyte Z370 AORUS Gaming 7        | 1        | 1.09%   |
| Gigabyte X570 AORUS PRO             | 1        | 1.09%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 1        | 1.09%   |
| Gigabyte P55-USB3                   | 1        | 1.09%   |
| Gigabyte P43-ES3G                   | 1        | 1.09%   |
| Gigabyte P35-DS3P                   | 1        | 1.09%   |
| Gigabyte H110M-S2H                  | 1        | 1.09%   |
| Gigabyte GA-880GM-UD2H              | 1        | 1.09%   |
| Gigabyte GA-880GA-UD3H              | 1        | 1.09%   |
| Gigabyte F2A88X-UP4                 | 1        | 1.09%   |
| Gigabyte EP45-UD3LR                 | 1        | 1.09%   |
| Gigabyte B550M DS3H                 | 1        | 1.09%   |
| Gigabyte B450M DS3H                 | 1        | 1.09%   |
| Gigabyte A320M-DS2                  | 1        | 1.09%   |
| Gateway SX2185                      | 1        | 1.09%   |
| GALAX B550M                         | 1        | 1.09%   |
| Fujitsu Siemens ESPRIMO P           | 1        | 1.09%   |
| Fujitsu ESPRIMO P720                | 1        | 1.09%   |
| ECS A55F-M3                         | 1        | 1.09%   |
| Dell XPS720                         | 1        | 1.09%   |
| Dell OptiPlex GX620                 | 1        | 1.09%   |
| Dell OptiPlex 790                   | 1        | 1.09%   |
| Dell OptiPlex 760                   | 1        | 1.09%   |
| Dell OptiPlex 7010                  | 1        | 1.09%   |
| Dell OptiPlex 390                   | 1        | 1.09%   |
| Dell Inspiron 660                   | 1        | 1.09%   |
| Dell Inspiron 3847                  | 1        | 1.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 7        | 7.61%   |
| ASUS PRIME              | 4        | 4.35%   |
| ASUS ROG                | 3        | 3.26%   |
| ASUS All                | 3        | 3.26%   |
| Gigabyte Z390           | 2        | 2.17%   |
| Dell Studio             | 2        | 2.17%   |
| Dell Inspiron           | 2        | 2.17%   |
| ASUS TUF                | 2        | 2.17%   |
| ASRock K8A780LM         | 2        | 2.17%   |
| MSI MS-7C94             | 1        | 1.09%   |
| MSI MS-7C88             | 1        | 1.09%   |
| MSI MS-7C56             | 1        | 1.09%   |
| MSI MS-7B86             | 1        | 1.09%   |
| MSI MS-7A34             | 1        | 1.09%   |
| MSI MS-7917             | 1        | 1.09%   |
| MSI MS-7815             | 1        | 1.09%   |
| MSI MS-7808             | 1        | 1.09%   |
| MSI MS-7693             | 1        | 1.09%   |
| MSI MS-7641             | 1        | 1.09%   |
| MSI MS-7199             | 1        | 1.09%   |
| MSI GEG                 | 1        | 1.09%   |
| Lenovo ThinkStation     | 1        | 1.09%   |
| Lenovo 10AAS1QB0B       | 1        | 1.09%   |
| Intel MAHOBAY           | 1        | 1.09%   |
| Intel H81               | 1        | 1.09%   |
| Intel DCP847SKE         | 1        | 1.09%   |
| IBM 8183B2U             | 1        | 1.09%   |
| Huanan X99-F8           | 1        | 1.09%   |
| HP Z400                 | 1        | 1.09%   |
| HP Z230                 | 1        | 1.09%   |
| HP Z220                 | 1        | 1.09%   |
| HP ProDesk              | 1        | 1.09%   |
| HP Compaq               | 1        | 1.09%   |
| HP 3031h                | 1        | 1.09%   |
| GreatWall U320          | 1        | 1.09%   |
| Gigabyte Z68AP-D3       | 1        | 1.09%   |
| Gigabyte Z370           | 1        | 1.09%   |
| Gigabyte X570           | 1        | 1.09%   |
| Gigabyte X470           | 1        | 1.09%   |
| Gigabyte P55-USB3       | 1        | 1.09%   |
| Gigabyte P43-ES3G       | 1        | 1.09%   |
| Gigabyte P35-DS3P       | 1        | 1.09%   |
| Gigabyte H110M-S2H      | 1        | 1.09%   |
| Gigabyte GA-880GM-UD2H  | 1        | 1.09%   |
| Gigabyte GA-880GA-UD3H  | 1        | 1.09%   |
| Gigabyte F2A88X-UP4     | 1        | 1.09%   |
| Gigabyte EP45-UD3LR     | 1        | 1.09%   |
| Gigabyte B550M          | 1        | 1.09%   |
| Gigabyte B450M          | 1        | 1.09%   |
| Gigabyte A320M-DS2      | 1        | 1.09%   |
| Gateway SX2185          | 1        | 1.09%   |
| GALAX B550M             | 1        | 1.09%   |
| Fujitsu Siemens ESPRIMO | 1        | 1.09%   |
| Fujitsu ESPRIMO         | 1        | 1.09%   |
| ECS A55F-M3             | 1        | 1.09%   |
| Dell XPS720             | 1        | 1.09%   |
| ASUS X79-DELUXE         | 1        | 1.09%   |
| ASUS SABERTOOTH         | 1        | 1.09%   |
| ASUS P8Z77-V            | 1        | 1.09%   |
| ASUS P5K-E              | 1        | 1.09%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 10       | 10.87%  |
| 2020 | 9        | 9.78%   |
| 2018 | 9        | 9.78%   |
| 2012 | 8        | 8.7%    |
| 2011 | 8        | 8.7%    |
| 2019 | 6        | 6.52%   |
| 2014 | 6        | 6.52%   |
| 2017 | 5        | 5.43%   |
| 2010 | 5        | 5.43%   |
| 2008 | 5        | 5.43%   |
| 2007 | 4        | 4.35%   |
| 2021 | 3        | 3.26%   |
| 2016 | 3        | 3.26%   |
| 2015 | 3        | 3.26%   |
| 2009 | 3        | 3.26%   |
| 2006 | 3        | 3.26%   |
| 2005 | 2        | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 92       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 92       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 92       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 28       | 30.43%  |
| 8.01-16.0   | 18       | 19.57%  |
| 4.01-8.0    | 12       | 13.04%  |
| 32.01-64.0  | 12       | 13.04%  |
| 3.01-4.0    | 11       | 11.96%  |
| 1.01-2.0    | 6        | 6.52%   |
| 24.01-32.0  | 2        | 2.17%   |
| 2.01-3.0    | 1        | 1.09%   |
| 64.01-256.0 | 1        | 1.09%   |
| 0.51-1.0    | 1        | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 32       | 33.68%  |
| 2.01-3.0   | 22       | 23.16%  |
| 3.01-4.0   | 14       | 14.74%  |
| 4.01-8.0   | 11       | 11.58%  |
| 0.51-1.0   | 11       | 11.58%  |
| 8.01-16.0  | 3        | 3.16%   |
| 16.01-24.0 | 1        | 1.05%   |
| 0.01-0.5   | 1        | 1.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 39       | 40.63%  |
| 1      | 27       | 28.13%  |
| 3      | 16       | 16.67%  |
| 5      | 7        | 7.29%   |
| 4      | 6        | 6.25%   |
| 8      | 1        | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 48       | 51.61%  |
| No        | 45       | 48.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 92       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 67.39%  |
| Yes       | 30       | 32.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 83.7%   |
| Yes       | 15       | 16.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 26       | 28.26%  |
| Slovakia    | 7        | 7.61%   |
| UK          | 5        | 5.43%   |
| Spain       | 5        | 5.43%   |
| Germany     | 5        | 5.43%   |
| Poland      | 4        | 4.35%   |
| France      | 4        | 4.35%   |
| Australia   | 4        | 4.35%   |
| Sweden      | 3        | 3.26%   |
| Serbia      | 3        | 3.26%   |
| Russia      | 3        | 3.26%   |
| India       | 3        | 3.26%   |
| Brazil      | 3        | 3.26%   |
| Switzerland | 2        | 2.17%   |
| Finland     | 2        | 2.17%   |
| Denmark     | 2        | 2.17%   |
| Ukraine     | 1        | 1.09%   |
| Turkey      | 1        | 1.09%   |
| Philippines | 1        | 1.09%   |
| Netherlands | 1        | 1.09%   |
| Italy       | 1        | 1.09%   |
| Ireland     | 1        | 1.09%   |
| Indonesia   | 1        | 1.09%   |
| Hungary     | 1        | 1.09%   |
| Greece      | 1        | 1.09%   |
| Canada      | 1        | 1.09%   |
| Austria     | 1        | 1.09%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Bratislava               | 7        | 7.45%   |
| Montevallo               | 2        | 2.13%   |
| Melbourne                | 2        | 2.13%   |
| Madrid                   | 2        | 2.13%   |
| Lausen                   | 2        | 2.13%   |
| Bengaluru                | 2        | 2.13%   |
| Belgrade                 | 2        | 2.13%   |
| Albertslund Municipality | 2        | 2.13%   |
| Yuzhno-Sakhalinsk        | 1        | 1.06%   |
| Winter Park              | 1        | 1.06%   |
| Warren                   | 1        | 1.06%   |
| Volos                    | 1        | 1.06%   |
| Virginia Beach           | 1        | 1.06%   |
| Vilhelmina               | 1        | 1.06%   |
| Vienna                   | 1        | 1.06%   |
| Vertou                   | 1        | 1.06%   |
| Valencia                 | 1        | 1.06%   |
| Tuusula                  | 1        | 1.06%   |
| Torrevieja               | 1        | 1.06%   |
| Tobyhanna                | 1        | 1.06%   |
| Tilburg                  | 1        | 1.06%   |
| Szar                     | 1        | 1.06%   |
| Sydney                   | 1        | 1.06%   |
| Stockholm                | 1        | 1.06%   |
| Stargard                 | 1        | 1.06%   |
| Springdale               | 1        | 1.06%   |
| Serrana                  | 1        | 1.06%   |
| SÃ¶dertÃ¤lje         | 1        | 1.06%   |
| San Diego                | 1        | 1.06%   |
| Rosporden                | 1        | 1.06%   |
| Portland                 | 1        | 1.06%   |
| Podolsk                  | 1        | 1.06%   |
| Pocono Summit            | 1        | 1.06%   |
| Pleyben                  | 1        | 1.06%   |
| Pleasant Hill            | 1        | 1.06%   |
| Pabianice                | 1        | 1.06%   |
| Oxford                   | 1        | 1.06%   |
| Omsk                     | 1        | 1.06%   |
| Novi Knezevac            | 1        | 1.06%   |
| Norwalk                  | 1        | 1.06%   |
| Normal                   | 1        | 1.06%   |
| Newtownabbey             | 1        | 1.06%   |
| Munster                  | 1        | 1.06%   |
| Milwaukee                | 1        | 1.06%   |
| Mechanicsburg            | 1        | 1.06%   |
| McLoud                   | 1        | 1.06%   |
| Marbella                 | 1        | 1.06%   |
| Manado                   | 1        | 1.06%   |
| Mainz                    | 1        | 1.06%   |
| Lyon                     | 1        | 1.06%   |
| London                   | 1        | 1.06%   |
| Lebanon                  | 1        | 1.06%   |
| Kharagpur                | 1        | 1.06%   |
| Kent                     | 1        | 1.06%   |
| Istanbul                 | 1        | 1.06%   |
| Huntsville               | 1        | 1.06%   |
| Houston                  | 1        | 1.06%   |
| Heinola                  | 1        | 1.06%   |
| Greenwich                | 1        | 1.06%   |
| Göttingen               | 1        | 1.06%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 38       | 49     | 20.65%  |
| Seagate                   | 37       | 52     | 20.11%  |
| Samsung Electronics       | 25       | 36     | 13.59%  |
| Kingston                  | 13       | 14     | 7.07%   |
| Hitachi                   | 13       | 17     | 7.07%   |
| Crucial                   | 8        | 8      | 4.35%   |
| A-DATA Technology         | 8        | 9      | 4.35%   |
| Toshiba                   | 7        | 9      | 3.8%    |
| SanDisk                   | 6        | 7      | 3.26%   |
| MAXTOR                    | 4        | 5      | 2.17%   |
| GOODRAM                   | 4        | 5      | 2.17%   |
| PNY                       | 3        | 4      | 1.63%   |
| Corsair                   | 3        | 3      | 1.63%   |
| SPCC                      | 2        | 2      | 1.09%   |
| Mushkin                   | 2        | 2      | 1.09%   |
| Intel                     | 2        | 3      | 1.09%   |
| WDC WDS1                  | 1        | 1      | 0.54%   |
| Transcend                 | 1        | 1      | 0.54%   |
| OCZ                       | 1        | 1      | 0.54%   |
| Micron/Crucial Technology | 1        | 1      | 0.54%   |
| Micron Technology         | 1        | 1      | 0.54%   |
| KingFast                  | 1        | 1      | 0.54%   |
| IBM/Hitachi               | 1        | 1      | 0.54%   |
| Gigabyte Technology       | 1        | 1      | 0.54%   |
| Fujitsu                   | 1        | 2      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seagate ST4000DM004-2CV104 4TB    | 4        | 1.89%   |
| Seagate ST2000DM008-2FR102 2TB    | 4        | 1.89%   |
| Samsung SSD 860 EVO 500GB         | 4        | 1.89%   |
| Kingston SA400S37480G 480GB SSD   | 4        | 1.89%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 3        | 1.42%   |
| Seagate ST500DM002-1BD142 500GB   | 3        | 1.42%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 1.42%   |
| WDC WD60EZRZ-00RWYB1 6TB          | 2        | 0.94%   |
| WDC WD60EFRX-68L0BN1 6TB          | 2        | 0.94%   |
| WDC WD30EZRX-00D8PB0 3TB          | 2        | 0.94%   |
| WDC WD30EFRX-68AX9N0 3TB          | 2        | 0.94%   |
| WDC WD15EARX-00PASB0 1TB          | 2        | 0.94%   |
| Toshiba MK5065GSX 500GB           | 2        | 0.94%   |
| Seagate ST3500413AS 500GB         | 2        | 0.94%   |
| Seagate ST2000DM001-1CH164 2TB    | 2        | 0.94%   |
| SanDisk SSD PLUS 1000GB           | 2        | 0.94%   |
| SanDisk SDSSDP128G 128GB          | 2        | 0.94%   |
| Samsung SSD 870 EVO 500GB         | 2        | 0.94%   |
| Samsung SSD 860 EVO 1TB           | 2        | 0.94%   |
| Samsung SSD 850 EVO 500GB         | 2        | 0.94%   |
| Samsung SSD 840 EVO 250GB         | 2        | 0.94%   |
| Samsung SSD 830 Series 128GB      | 2        | 0.94%   |
| Hitachi HUA723020ALA641 2TB       | 2        | 0.94%   |
| Hitachi HTS543232A7A384 320GB     | 2        | 0.94%   |
| Corsair MP400 2TB                 | 2        | 0.94%   |
| A-DATA SU630 480GB SSD            | 2        | 0.94%   |
| A-DATA SP600 32GB SSD             | 2        | 0.94%   |
| WDC WDS500G2B0C-00PXH0 500GB      | 1        | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1        | 0.47%   |
| WDC WDS500G2B0A 500GB SSD         | 1        | 0.47%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD  | 1        | 0.47%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 1        | 0.47%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD  | 1        | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.47%   |
| WDC WDS1 20G2G0A-00JH30 120GB SSD | 1        | 0.47%   |
| WDC WD80EZAZ-11TDBA0 8TB          | 1        | 0.47%   |
| WDC WD800JD-00MSA1 80GB           | 1        | 0.47%   |
| WDC WD5003ABYX-01WERA1 500GB      | 1        | 0.47%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1        | 0.47%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB          | 1        | 0.47%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 0.47%   |
| WDC WD2500JS-75NCB3 250GB         | 1        | 0.47%   |
| WDC WD2500AAJS-00L7A0 250GB       | 1        | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB          | 1        | 0.47%   |
| WDC WD20EARX-00PASB0 2TB          | 1        | 0.47%   |
| WDC WD1600AVVS-63L2B0 160GB       | 1        | 0.47%   |
| WDC WD15EADS-11P8B2 1TB           | 1        | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB          | 1        | 0.47%   |
| WDC WD10EZRZ-00HTKB0 1TB          | 1        | 0.47%   |
| WDC WD10EZEX-75WN4A0 1TB          | 1        | 0.47%   |
| WDC WD10EZEX-08M2NA0 1TB          | 1        | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB          | 1        | 0.47%   |
| WDC WD10EVDS-63U8B1 1TB           | 1        | 0.47%   |
| WDC WD10EAVS-00D7B1 1TB           | 1        | 0.47%   |
| WDC WD10EARX-00N0YB0 1TB          | 1        | 0.47%   |
| WDC WD10EALX-008EA0 1TB           | 1        | 0.47%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 37       | 51     | 38.14%  |
| WDC                 | 30       | 40     | 30.93%  |
| Hitachi             | 13       | 17     | 13.4%   |
| Toshiba             | 7        | 9      | 7.22%   |
| Samsung Electronics | 4        | 5      | 4.12%   |
| MAXTOR              | 4        | 5      | 4.12%   |
| IBM/Hitachi         | 1        | 1      | 1.03%   |
| Fujitsu             | 1        | 2      | 1.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 21     | 23.61%  |
| Kingston            | 11       | 12     | 15.28%  |
| WDC                 | 7        | 8      | 9.72%   |
| Crucial             | 7        | 7      | 9.72%   |
| A-DATA Technology   | 7        | 8      | 9.72%   |
| SanDisk             | 6        | 7      | 8.33%   |
| GOODRAM             | 4        | 5      | 5.56%   |
| SPCC                | 2        | 2      | 2.78%   |
| PNY                 | 2        | 2      | 2.78%   |
| Intel               | 2        | 3      | 2.78%   |
| WDC WDS1            | 1        | 1      | 1.39%   |
| Transcend           | 1        | 1      | 1.39%   |
| OCZ                 | 1        | 1      | 1.39%   |
| Mushkin             | 1        | 1      | 1.39%   |
| Micron Technology   | 1        | 1      | 1.39%   |
| KingFast            | 1        | 1      | 1.39%   |
| Gigabyte Technology | 1        | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 70       | 130    | 47.3%   |
| SSD     | 58       | 82     | 39.19%  |
| NVMe    | 19       | 22     | 12.84%  |
| Unknown | 1        | 1      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 89       | 211    | 80.91%  |
| NVMe | 19       | 22     | 17.27%  |
| SAS  | 2        | 2      | 1.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 122    | 52.45%  |
| 0.51-1.0   | 36       | 49     | 25.17%  |
| 1.01-2.0   | 15       | 18     | 10.49%  |
| 2.01-3.0   | 7        | 8      | 4.9%    |
| 3.01-4.0   | 6        | 7      | 4.2%    |
| 4.01-10.0  | 4        | 8      | 2.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 23       | 23.71%  |
| 1001-2000      | 15       | 15.46%  |
| 101-250        | 14       | 14.43%  |
| 501-1000       | 14       | 14.43%  |
| More than 3000 | 13       | 13.4%   |
| 51-100         | 10       | 10.31%  |
| 2001-3000      | 5        | 5.15%   |
| 21-50          | 3        | 3.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 21       | 22.58%  |
| 251-500        | 14       | 15.05%  |
| 101-250        | 14       | 15.05%  |
| 21-50          | 13       | 13.98%  |
| 501-1000       | 8        | 8.6%    |
| 51-100         | 8        | 8.6%    |
| 1001-2000      | 7        | 7.53%   |
| More than 3000 | 4        | 4.3%    |
| 2001-3000      | 4        | 4.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 2.7%    |
| WDC WD5003ABYX-01WERA1 500GB             | 1        | 1      | 2.7%    |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 2.7%    |
| WDC WD20EARX-00PASB0 2TB                 | 1        | 1      | 2.7%    |
| WDC WD1600AVVS-63L2B0 160GB              | 1        | 1      | 2.7%    |
| WDC WD15EADS-11P8B2 1TB                  | 1        | 1      | 2.7%    |
| WDC WD10EZEX-75WN4A0 1TB                 | 1        | 1      | 2.7%    |
| WDC WD10EAVS-00D7B1 1TB                  | 1        | 1      | 2.7%    |
| Toshiba MK7575GSX 752GB                  | 1        | 1      | 2.7%    |
| Toshiba MK6465GSX 640GB                  | 1        | 1      | 2.7%    |
| SPCC Solid State Disk 512GB              | 1        | 1      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 2.7%    |
| Seagate ST3750330NS 752GB                | 1        | 1      | 2.7%    |
| Seagate ST3500820AS 500GB                | 1        | 1      | 2.7%    |
| Seagate ST3500413AS 500GB                | 1        | 1      | 2.7%    |
| Seagate ST3360320AS 360GB                | 1        | 1      | 2.7%    |
| Seagate ST3320413CS 320GB                | 1        | 1      | 2.7%    |
| Seagate ST33000651NS 3TB                 | 1        | 1      | 2.7%    |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 2.7%    |
| Seagate ST31000524AS 1TB                 | 1        | 1      | 2.7%    |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1      | 2.7%    |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 2.7%    |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 2.7%    |
| Samsung Electronics HD322GJ 320GB        | 1        | 2      | 2.7%    |
| MAXTOR 6Y120M0 122GB                     | 1        | 1      | 2.7%    |
| MAXTOR 6L200M0 208GB                     | 1        | 1      | 2.7%    |
| MAXTOR 4K040H2 40GB                      | 1        | 1      | 2.7%    |
| IBM/Hitachi IC25N030ATCS04-0 32GB        | 1        | 1      | 2.7%    |
| Hitachi HUA722020ALA331 2TB              | 1        | 1      | 2.7%    |
| Hitachi HTS545032B9SA00 320GB            | 1        | 1      | 2.7%    |
| Hitachi HDT721010SLA360 1TB              | 1        | 1      | 2.7%    |
| Hitachi HDP725016GLA380 160GB            | 1        | 1      | 2.7%    |
| GOODRAM SSDPR-CL100-480-G3 480GB         | 1        | 1      | 2.7%    |
| Fujitsu MHV2060BH PL 64GB                | 1        | 2      | 2.7%    |
| Crucial CT256M550SSD1 256GB              | 1        | 1      | 2.7%    |
| Crucial CT240M500SSD1 240GB              | 1        | 1      | 2.7%    |
| A-DATA Technology SU650 240GB SSD        | 1        | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 25%     |
| WDC                 | 8        | 8      | 22.22%  |
| Hitachi             | 4        | 4      | 11.11%  |
| Samsung Electronics | 3        | 4      | 8.33%   |
| MAXTOR              | 3        | 3      | 8.33%   |
| Toshiba             | 2        | 2      | 5.56%   |
| Crucial             | 2        | 2      | 5.56%   |
| SPCC                | 1        | 1      | 2.78%   |
| IBM/Hitachi         | 1        | 1      | 2.78%   |
| GOODRAM             | 1        | 1      | 2.78%   |
| Fujitsu             | 1        | 2      | 2.78%   |
| A-DATA Technology   | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 10     | 32.14%  |
| WDC                 | 7        | 7      | 25%     |
| Hitachi             | 4        | 4      | 14.29%  |
| MAXTOR              | 3        | 3      | 10.71%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Samsung Electronics | 1        | 2      | 3.57%   |
| IBM/Hitachi         | 1        | 1      | 3.57%   |
| Fujitsu             | 1        | 2      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 31     | 75.76%  |
| SSD  | 8        | 8      | 24.24%  |

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
| Works    | 79       | 185    | 66.39%  |
| Malfunc  | 31       | 39     | 26.05%  |
| Detected | 6        | 7      | 5.04%   |
| Failed   | 3        | 4      | 2.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 58       | 46.03%  |
| AMD                         | 29       | 23.02%  |
| Samsung Electronics         | 9        | 7.14%   |
| JMicron Technology          | 6        | 4.76%   |
| ASMedia Technology          | 6        | 4.76%   |
| Phison Electronics          | 4        | 3.17%   |
| Marvell Technology Group    | 3        | 2.38%   |
| Nvidia                      | 2        | 1.59%   |
| Micron/Crucial Technology   | 2        | 1.59%   |
| Kingston Technology Company | 2        | 1.59%   |
| VIA Technologies            | 1        | 0.79%   |
| ULi Electronics             | 1        | 0.79%   |
| Silicon Motion              | 1        | 0.79%   |
| Sandisk                     | 1        | 0.79%   |
| ADATA Technology            | 1        | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 8.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8        | 4.91%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6        | 3.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 3.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 3.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 3.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 3.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4        | 2.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 2.45%   |
| Phison E12 NVMe Controller                                                              | 4        | 2.45%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 2.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4        | 2.45%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 2.45%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 2.45%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.84%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 1.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.84%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.23%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.23%   |
| JMicron JMB368 IDE controller                                                           | 2        | 1.23%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 1.23%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.23%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.23%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 1.23%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 1.23%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.61%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.61%   |
| ULi ULi M5288 SATA                                                                      | 1        | 0.61%   |
| ULi M5229 IDE                                                                           | 1        | 0.61%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.61%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.61%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 0.61%   |
| Nvidia MCP61 IDE                                                                        | 1        | 0.61%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.61%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.61%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.61%   |
| Marvell Group 88SE9170 PCIe 2.0 x1 2-port SATA 6 Gb/s Controller                        | 1        | 0.61%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1        | 0.61%   |
| Kingston Company KC2000 NVMe SSD                                                        | 1        | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.61%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.61%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 1        | 0.61%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.61%   |
| Intel 82801EB (ICH5) SATA Controller                                                    | 1        | 0.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 73       | 58.4%   |
| IDE  | 29       | 23.2%   |
| NVMe | 19       | 15.2%   |
| RAID | 4        | 3.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 60       | 65.22%  |
| AMD          | 31       | 33.7%   |
| CentaurHauls | 1        | 1.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 3.26%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 3        | 3.26%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 2        | 2.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 2.17%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.17%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 2        | 2.17%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 2.17%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 1.09%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 1.09%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1        | 1.09%   |
| Intel Pentium Gold G6605 CPU @ 4.30GHz      | 1        | 1.09%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 1.09%   |
| Intel Pentium D CPU 3.40GHz                 | 1        | 1.09%   |
| Intel Pentium CPU G3240T @ 2.70GHz          | 1        | 1.09%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1        | 1.09%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1        | 1.09%   |
| Intel Core i9-10850K CPU @ 3.60GHz          | 1        | 1.09%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.09%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 1.09%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.09%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1        | 1.09%   |
| Intel Core i7-4820K CPU @ 3.70GHz           | 1        | 1.09%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.09%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 1.09%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 1.09%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 1        | 1.09%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 1.09%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.09%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 1.09%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.09%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.09%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1        | 1.09%   |
| Intel Core i5-4430 CPU @ 3.00GHz            | 1        | 1.09%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.09%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1        | 1.09%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.09%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1        | 1.09%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.09%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 1.09%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1        | 1.09%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.09%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1        | 1.09%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 1.09%   |
| Intel Core i3-6300 CPU @ 3.80GHz            | 1        | 1.09%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1        | 1.09%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 1.09%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 1        | 1.09%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 1        | 1.09%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 1.09%   |
| Intel Core 2 Extreme CPU Q6850 @ 3.00GHz    | 1        | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 1.09%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 1.09%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 1        | 1.09%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1        | 1.09%   |
| Intel Celeron D CPU 3.46GHz                 | 1        | 1.09%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 1.09%   |
| Intel Atom CPU D2550 @ 1.86GHz              | 1        | 1.09%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 1        | 1.09%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1        | 1.09%   |
| CentaurHauls VIA Esther processor 1000MHz   | 1        | 1.09%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 18       | 19.57%  |
| Intel Core i7           | 11       | 11.96%  |
| AMD Ryzen 5             | 10       | 10.87%  |
| Intel Core 2 Quad       | 5        | 5.43%   |
| AMD Ryzen 7             | 5        | 5.43%   |
| Intel Core i3           | 4        | 4.35%   |
| Intel Core 2 Duo        | 4        | 4.35%   |
| Intel Xeon              | 3        | 3.26%   |
| Intel Pentium           | 3        | 3.26%   |
| Other                   | 2        | 2.17%   |
| Intel Pentium 4         | 2        | 2.17%   |
| AMD Sempron             | 2        | 2.17%   |
| AMD Phenom II X4        | 2        | 2.17%   |
| AMD Athlon II X2        | 2        | 2.17%   |
| Intel Pentium Gold      | 1        | 1.09%   |
| Intel Pentium Dual-Core | 1        | 1.09%   |
| Intel Pentium D         | 1        | 1.09%   |
| Intel Core i9           | 1        | 1.09%   |
| Intel Core 2 Extreme    | 1        | 1.09%   |
| Intel Celeron D         | 1        | 1.09%   |
| Intel Celeron           | 1        | 1.09%   |
| Intel Atom              | 1        | 1.09%   |
| CentaurHauls VIA Esther | 1        | 1.09%   |
| AMD Ryzen Threadripper  | 1        | 1.09%   |
| AMD Ryzen 3             | 1        | 1.09%   |
| AMD Phenom II X6        | 1        | 1.09%   |
| AMD FX                  | 1        | 1.09%   |
| AMD E1                  | 1        | 1.09%   |
| AMD Athlon X4           | 1        | 1.09%   |
| AMD Athlon 64 X2        | 1        | 1.09%   |
| AMD Athlon              | 1        | 1.09%   |
| AMD A4                  | 1        | 1.09%   |
| AMD A10                 | 1        | 1.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 34       | 36.96%  |
| 2      | 26       | 28.26%  |
| 6      | 15       | 16.3%   |
| 8      | 8        | 8.7%    |
| 1      | 6        | 6.52%   |
| 12     | 2        | 2.17%   |
| 10     | 1        | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 92       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 48       | 52.17%  |
| 2      | 44       | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 90       | 97.83%  |
| 32-bit         | 2        | 2.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 15.22%  |
| 0x306c3    | 9        | 9.78%   |
| 0x206a7    | 7        | 7.61%   |
| 0x306a9    | 5        | 5.43%   |
| 0x08701021 | 5        | 5.43%   |
| 0x1067a    | 4        | 4.35%   |
| 0x0800820d | 4        | 4.35%   |
| 0x906ed    | 3        | 3.26%   |
| 0xa0671    | 2        | 2.17%   |
| 0xa0653    | 2        | 2.17%   |
| 0x6fb      | 2        | 2.17%   |
| 0x506e3    | 2        | 2.17%   |
| 0x10677    | 2        | 2.17%   |
| 0x010000c8 | 2        | 2.17%   |
| 0xf65      | 1        | 1.09%   |
| 0xf64      | 1        | 1.09%   |
| 0xf4a      | 1        | 1.09%   |
| 0xf29      | 1        | 1.09%   |
| 0xa0655    | 1        | 1.09%   |
| 0x906eb    | 1        | 1.09%   |
| 0x906ea    | 1        | 1.09%   |
| 0x6fd      | 1        | 1.09%   |
| 0x306f2    | 1        | 1.09%   |
| 0x306e4    | 1        | 1.09%   |
| 0x30661    | 1        | 1.09%   |
| 0x206d7    | 1        | 1.09%   |
| 0x20652    | 1        | 1.09%   |
| 0x106e5    | 1        | 1.09%   |
| 0x0a201016 | 1        | 1.09%   |
| 0x0a201009 | 1        | 1.09%   |
| 0x08301039 | 1        | 1.09%   |
| 0x0810100b | 1        | 1.09%   |
| 0x0800820b | 1        | 1.09%   |
| 0x08001138 | 1        | 1.09%   |
| 0x08001137 | 1        | 1.09%   |
| 0x08001126 | 1        | 1.09%   |
| 0x0700010f | 1        | 1.09%   |
| 0x06006118 | 1        | 1.09%   |
| 0x0600063e | 1        | 1.09%   |
| 0x03000027 | 1        | 1.09%   |
| 0x010000dc | 1        | 1.09%   |
| 0x010000db | 1        | 1.09%   |
| 0x01000083 | 1        | 1.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 13       | 14.13%  |
| SandyBridge | 8        | 8.7%    |
| Penryn      | 8        | 8.7%    |
| IvyBridge   | 7        | 7.61%   |
| Zen 2       | 6        | 6.52%   |
| KabyLake    | 6        | 6.52%   |
| K10         | 6        | 6.52%   |
| Zen+        | 5        | 5.43%   |
| Zen         | 4        | 4.35%   |
| NetBurst    | 4        | 4.35%   |
| K8 Hammer   | 3        | 3.26%   |
| Core        | 3        | 3.26%   |
| CometLake   | 3        | 3.26%   |
| Zen 3       | 2        | 2.17%   |
| Skylake     | 2        | 2.17%   |
| Nehalem     | 2        | 2.17%   |
| Unknown     | 2        | 2.17%   |
| Westmere    | 1        | 1.09%   |
| Steamroller | 1        | 1.09%   |
| K10 Llano   | 1        | 1.09%   |
| Jaguar      | 1        | 1.09%   |
| Icelake     | 1        | 1.09%   |
| Excavator   | 1        | 1.09%   |
| Bulldozer   | 1        | 1.09%   |
| Bonnell     | 1        | 1.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 40       | 39.22%  |
| AMD              | 33       | 32.35%  |
| Intel            | 28       | 27.45%  |
| VIA Technologies | 1        | 0.98%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6        | 5.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 5        | 4.67%   |
| Nvidia GK208B [GeForce GT 710]                                                | 4        | 3.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4        | 3.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 4        | 3.74%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                            | 3        | 2.8%    |
| Nvidia GT218 [GeForce 210]                                                    | 2        | 1.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                               | 2        | 1.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2        | 1.87%   |
| Nvidia GK106 [GeForce GTX 660]                                                | 2        | 1.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 2        | 1.87%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                     | 2        | 1.87%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                             | 2        | 1.87%   |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                             | 2        | 1.87%   |
| AMD RV516 [Radeon X1300/X1550 Series]                                         | 2        | 1.87%   |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.87%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                          | 2        | 1.87%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 1.87%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 1.87%   |
| VIA Technologies CN700/P4M800 Pro/P4M800 CE/VN800 Graphics [S3 UniChrome Pro] | 1        | 0.93%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1        | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1        | 0.93%   |
| Nvidia TU106 [GeForce RTX 2070]                                               | 1        | 0.93%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 1        | 0.93%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1        | 0.93%   |
| Nvidia TU104 [GeForce RTX 2060]                                               | 1        | 0.93%   |
| Nvidia GT216 [GeForce GT 220]                                                 | 1        | 0.93%   |
| Nvidia GT215 [GeForce GT 240]                                                 | 1        | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1        | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1        | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1        | 0.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                               | 1        | 0.93%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1        | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1        | 0.93%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                             | 1        | 0.93%   |
| Nvidia GK208B [GeForce GT 730]                                                | 1        | 0.93%   |
| Nvidia GK110 [GeForce GTX 780]                                                | 1        | 0.93%   |
| Nvidia GK107GL [Quadro K600]                                                  | 1        | 0.93%   |
| Nvidia GK107 [GeForce GTX 650]                                                | 1        | 0.93%   |
| Nvidia GK107 [GeForce GT 640]                                                 | 1        | 0.93%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                             | 1        | 0.93%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                             | 1        | 0.93%   |
| Nvidia GF114 [GeForce GTX 560 SE]                                             | 1        | 0.93%   |
| Nvidia GF110 [GeForce GTX 570]                                                | 1        | 0.93%   |
| Nvidia GF108 [GeForce GT 630]                                                 | 1        | 0.93%   |
| Nvidia GF108 [GeForce GT 430]                                                 | 1        | 0.93%   |
| Nvidia GF104 [GeForce GTX 460]                                                | 1        | 0.93%   |
| Nvidia G94GL [Quadro FX 1800]                                                 | 1        | 0.93%   |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1        | 0.93%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                     | 1        | 0.93%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                     | 1        | 0.93%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1        | 0.93%   |
| Intel HD Graphics 630                                                         | 1        | 0.93%   |
| Intel HD Graphics 530                                                         | 1        | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                           | 1        | 0.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1        | 0.93%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1        | 0.93%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                              | 1        | 0.93%   |
| Intel 82945G/GZ Integrated Graphics Controller                                | 1        | 0.93%   |
| Intel 82865G Integrated Graphics Controller                                   | 1        | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 39       | 41.05%  |
| 1 x AMD        | 30       | 31.58%  |
| 1 x Intel      | 20       | 21.05%  |
| Intel + AMD    | 2        | 2.11%   |
| 3 x AMD        | 1        | 1.05%   |
| 2 x AMD        | 1        | 1.05%   |
| 1 x VIA        | 1        | 1.05%   |
| Intel + Nvidia | 1        | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 63       | 67.74%  |
| Proprietary | 28       | 30.11%  |
| Unknown     | 2        | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 29.47%  |
| 0.51-1.0   | 16       | 16.84%  |
| 1.01-2.0   | 14       | 14.74%  |
| 3.01-4.0   | 12       | 12.63%  |
| 7.01-8.0   | 9        | 9.47%   |
| 0.01-0.5   | 9        | 9.47%   |
| 5.01-6.0   | 4        | 4.21%   |
| 8.01-16.0  | 2        | 2.11%   |
| 2.01-3.0   | 1        | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 19       | 18.81%  |
| Goldstar             | 13       | 12.87%  |
| Dell                 | 12       | 11.88%  |
| Acer                 | 9        | 8.91%   |
| Ancor Communications | 5        | 4.95%   |
| Philips              | 4        | 3.96%   |
| ViewSonic            | 3        | 2.97%   |
| Iiyama               | 3        | 2.97%   |
| Hewlett-Packard      | 3        | 2.97%   |
| ASUSTek Computer     | 3        | 2.97%   |
| Vizio                | 2        | 1.98%   |
| Vestel Elektronik    | 2        | 1.98%   |
| Medion               | 2        | 1.98%   |
| Fujitsu Siemens      | 2        | 1.98%   |
| BenQ                 | 2        | 1.98%   |
| AOC                  | 2        | 1.98%   |
| Videoseven           | 1        | 0.99%   |
| Sony                 | 1        | 0.99%   |
| Sceptre Tech         | 1        | 0.99%   |
| Sanyo                | 1        | 0.99%   |
| RIS                  | 1        | 0.99%   |
| NEC Computers        | 1        | 0.99%   |
| MSI                  | 1        | 0.99%   |
| Lenovo               | 1        | 0.99%   |
| IBM                  | 1        | 0.99%   |
| HYO                  | 1        | 0.99%   |
| Grundig              | 1        | 0.99%   |
| Gigabyte Technology  | 1        | 0.99%   |
| Eizo                 | 1        | 0.99%   |
| DTV                  | 1        | 0.99%   |
| Arnos Instruments    | 1        | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch    | 6        | 5.88%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch      | 2        | 1.96%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                    | 2        | 1.96%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                   | 2        | 1.96%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                   | 2        | 1.96%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                      | 1        | 0.98%   |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                   | 1        | 0.98%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                  | 1        | 0.98%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1        | 0.98%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 0.98%   |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch                 | 1        | 0.98%   |
| Sony TV SNY0801 1360x768                                                | 1        | 0.98%   |
| Sceptre Tech E22 SPT08D5 1920x1080 409x230mm 18.5-inch                  | 1        | 0.98%   |
| Sanyo LCD MONITOR SAN2213 1920x1080 474x296mm 22.0-inch                 | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch    | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch    | 1        | 0.98%   |
| Samsung Electronics SyncMaster SAM0059 1280x1024 312x234mm 15.4-inch    | 1        | 0.98%   |
| Samsung Electronics SMBX2450 SAM0722 1920x1080 531x299mm 24.0-inch      | 1        | 0.98%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch       | 1        | 0.98%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1        | 0.98%   |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch   | 1        | 0.98%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch       | 1        | 0.98%   |
| Samsung Electronics C27JG5x SAM0F57 2560x1440 600x340mm 27.2-inch       | 1        | 0.98%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1        | 0.98%   |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                        | 1        | 0.98%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1        | 0.98%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch                | 1        | 0.98%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 1        | 0.98%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 1        | 0.98%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch             | 1        | 0.98%   |
| MSI MAG271C MSI3FA6 1920x1080 600x340mm 27.2-inch                       | 1        | 0.98%   |
| Lenovo LEN L192p LEN24CB 1280x1024 376x301mm 19.0-inch                  | 1        | 0.98%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                    | 1        | 0.98%   |
| IBM L191p IBM24CB 1280x1024 380x300mm 19.1-inch                         | 1        | 0.98%   |
| HYO DUAL-DVI HYO049B 2560x1440 597x336mm 27.0-inch                      | 1        | 0.98%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch             | 1        | 0.98%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch              | 1        | 0.98%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch              | 1        | 0.98%   |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                       | 1        | 0.98%   |
| Goldstar W2361 GSM56FA 1920x1080 510x290mm 23.1-inch                    | 1        | 0.98%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                    | 1        | 0.98%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                    | 1        | 0.98%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch              | 1        | 0.98%   |
| Goldstar L222W GSM5664 1680x1050 474x296mm 22.0-inch                    | 1        | 0.98%   |
| Goldstar L1715S GSM436F 1280x1024 338x270mm 17.0-inch                   | 1        | 0.98%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch               | 1        | 0.98%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                        | 1        | 0.98%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                  | 1        | 0.98%   |
| Goldstar E2411 GSM583B 1920x1080 477x268mm 21.5-inch                    | 1        | 0.98%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                     | 1        | 0.98%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch        | 1        | 0.98%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch        | 1        | 0.98%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch        | 1        | 0.98%   |
| Eizo S1921 ENC1831 1280x1024 380x300mm 19.1-inch                        | 1        | 0.98%   |
| DTV Philco DTV0B01 1600x1200 700x390mm 31.5-inch                        | 1        | 0.98%   |
| Dell U4320Q DEL41D6 3840x2160 940x530mm 42.5-inch                       | 1        | 0.98%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                       | 1        | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 43.88%  |
| 3840x2160 (4K)     | 9        | 9.18%   |
| 2560x1440 (QHD)    | 8        | 8.16%   |
| 1680x1050 (WSXGA+) | 7        | 7.14%   |
| 1600x1200          | 7        | 7.14%   |
| 1280x1024 (SXGA)   | 7        | 7.14%   |
| 3440x1440          | 3        | 3.06%   |
| 1440x900 (WXGA+)   | 3        | 3.06%   |
| 1366x768 (WXGA)    | 3        | 3.06%   |
| 1920x1200 (WUXGA)  | 2        | 2.04%   |
| 1600x900 (HD+)     | 2        | 2.04%   |
| 1360x768           | 2        | 2.04%   |
| 2048x1536          | 1        | 1.02%   |
| 1024x768 (XGA)     | 1        | 1.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 16       | 15.84%  |
| 21      | 15       | 14.85%  |
| 24      | 12       | 11.88%  |
| 23      | 10       | 9.9%    |
| 31      | 6        | 5.94%   |
| 22      | 6        | 5.94%   |
| 19      | 6        | 5.94%   |
| 18      | 6        | 5.94%   |
| 84      | 4        | 3.96%   |
| 34      | 3        | 2.97%   |
| 20      | 3        | 2.97%   |
| 17      | 3        | 2.97%   |
| 65      | 2        | 1.98%   |
| 15      | 2        | 1.98%   |
| 72      | 1        | 0.99%   |
| 54      | 1        | 0.99%   |
| 49      | 1        | 0.99%   |
| 42      | 1        | 0.99%   |
| 26      | 1        | 0.99%   |
| 25      | 1        | 0.99%   |
| Unknown | 1        | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 37       | 37.76%  |
| 401-500     | 31       | 31.63%  |
| 601-700     | 7        | 7.14%   |
| 301-350     | 5        | 5.1%    |
| 1501-2000   | 5        | 5.1%    |
| 351-400     | 4        | 4.08%   |
| 1001-1500   | 4        | 4.08%   |
| 701-800     | 3        | 3.06%   |
| 901-1000    | 1        | 1.02%   |
| Unknown     | 1        | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 66       | 68.75%  |
| 16/10 | 12       | 12.5%   |
| 4/3   | 8        | 8.33%   |
| 5/4   | 7        | 7.29%   |
| 21/9  | 3        | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 39       | 39.39%  |
| 301-350        | 16       | 16.16%  |
| 151-200        | 11       | 11.11%  |
| More than 1000 | 9        | 9.09%   |
| 351-500        | 9        | 9.09%   |
| 141-150        | 7        | 7.07%   |
| 251-300        | 4        | 4.04%   |
| 111-120        | 1        | 1.01%   |
| 101-110        | 1        | 1.01%   |
| 501-1000       | 1        | 1.01%   |
| Unknown        | 1        | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 67       | 72.04%  |
| 101-120 | 19       | 20.43%  |
| 1-50    | 4        | 4.3%    |
| 161-240 | 1        | 1.08%   |
| 121-160 | 1        | 1.08%   |
| Unknown | 1        | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 80       | 86.96%  |
| 2     | 11       | 11.96%  |
| 3     | 1        | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 52       | 42.98%  |
| Intel                    | 36       | 29.75%  |
| Qualcomm Atheros         | 8        | 6.61%   |
| Broadcom                 | 6        | 4.96%   |
| TP-Link                  | 3        | 2.48%   |
| Ralink Technology        | 2        | 1.65%   |
| Ralink                   | 2        | 1.65%   |
| Marvell Technology Group | 2        | 1.65%   |
| Broadcom Limited         | 2        | 1.65%   |
| VIA Technologies         | 1        | 0.83%   |
| U-Blox                   | 1        | 0.83%   |
| Nvidia                   | 1        | 0.83%   |
| NetGear                  | 1        | 0.83%   |
| Edimax Technology        | 1        | 0.83%   |
| D-Link System            | 1        | 0.83%   |
| ASUSTek Computer         | 1        | 0.83%   |
| Aquantia                 | 1        | 0.83%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 41       | 31.3%   |
| Intel I211 Gigabit Network Connection                                                         | 6        | 4.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 5        | 3.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 3        | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 3        | 2.29%   |
| Intel Ethernet Connection I217-LM                                                             | 3        | 2.29%   |
| Intel Ethernet Connection (2) I219-V                                                          | 3        | 2.29%   |
| Intel Ethernet Connection (2) I218-V                                                          | 3        | 2.29%   |
| Intel 82579V Gigabit Network Connection                                                       | 3        | 2.29%   |
| Intel 82567LM-3 Gigabit Network Connection                                                    | 3        | 2.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 1.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                     | 2        | 1.53%   |
| Intel Wireless 8260                                                                           | 2        | 1.53%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 1.53%   |
| Intel Ethernet Controller I225-V                                                              | 2        | 1.53%   |
| Intel Ethernet Connection (11) I219-V                                                         | 2        | 1.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                                                  | 1        | 0.76%   |
| U-Blox [u-blox 8]                                                                             | 1        | 0.76%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 0.76%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 0.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                         | 1        | 0.76%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 0.76%   |
| Realtek 802.11ac NIC                                                                          | 1        | 0.76%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 0.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 0.76%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                     | 1        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1        | 0.76%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                                    | 1        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 0.76%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 0.76%   |
| Nvidia MCP61 Ethernet                                                                         | 1        | 0.76%   |
| NetGear A6210                                                                                 | 1        | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 0.76%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                             | 1        | 0.76%   |
| Intel Wireless 7260                                                                           | 1        | 0.76%   |
| Intel Ethernet Connection I217-V                                                              | 1        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                                                         | 1        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 0.76%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 0.76%   |
| Intel 82562EZ 10/100 Ethernet Controller                                                      | 1        | 0.76%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 1        | 0.76%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                               | 1        | 0.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                             | 1        | 0.76%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                                       | 1        | 0.76%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                                       | 1        | 0.76%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                               | 1        | 0.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 0.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 0.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 0.76%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                                      | 1        | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 22.58%  |
| Intel                 | 7        | 22.58%  |
| TP-Link               | 3        | 9.68%   |
| Qualcomm Atheros      | 3        | 9.68%   |
| Broadcom              | 3        | 9.68%   |
| Ralink Technology     | 2        | 6.45%   |
| Ralink                | 2        | 6.45%   |
| NetGear               | 1        | 3.23%   |
| Edimax Technology     | 1        | 3.23%   |
| Broadcom Limited      | 1        | 3.23%   |
| ASUSTek Computer      | 1        | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2        | 6.45%   |
| Intel Wireless 8260                                                                           | 2        | 6.45%   |
| Intel Wi-Fi 6 AX200                                                                           | 2        | 6.45%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 3.23%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                           | 1        | 3.23%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 1        | 3.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 1        | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1        | 3.23%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 3.23%   |
| Realtek 802.11ac NIC                                                                          | 1        | 3.23%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 3.23%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 1        | 3.23%   |
| Ralink RT2800 802.11n PCI                                                                     | 1        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1        | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 3.23%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                                              | 1        | 3.23%   |
| NetGear A6210                                                                                 | 1        | 3.23%   |
| Intel Wireless 7260                                                                           | 1        | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 3.23%   |
| Intel Centrino Wireless-N 2230                                                                | 1        | 3.23%   |
| Edimax RTL8192S WLAN Adapter                                                                  | 1        | 3.23%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 1        | 3.23%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 1        | 3.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                                               | 1        | 3.23%   |
| ASUS USB-N10 802.11n Network Adapter [Realtek RTL8188SU]                                      | 1        | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 49       | 50.52%  |
| Intel                    | 33       | 34.02%  |
| Qualcomm Atheros         | 5        | 5.15%   |
| Broadcom                 | 3        | 3.09%   |
| Marvell Technology Group | 2        | 2.06%   |
| VIA Technologies         | 1        | 1.03%   |
| Nvidia                   | 1        | 1.03%   |
| D-Link System            | 1        | 1.03%   |
| Broadcom Limited         | 1        | 1.03%   |
| Aquantia                 | 1        | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41       | 41.41%  |
| Intel I211 Gigabit Network Connection                             | 6        | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 5.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.03%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.03%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 3.03%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 2.02%   |
| Intel Ethernet Controller I225-V                                  | 2        | 2.02%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 2.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.01%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 1        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.01%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.01%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.01%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 1.01%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.01%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.01%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 1.01%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1        | 1.01%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 1.01%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 92       | 74.8%   |
| WiFi     | 30       | 24.39%  |
| Modem    | 1        | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 81       | 75%     |
| WiFi     | 27       | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 69       | 75%     |
| 2     | 20       | 21.74%  |
| 3     | 3        | 3.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 88.17%  |
| Yes  | 11       | 11.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 40%     |
| Cambridge Silicon Radio         | 3        | 20%     |
| ASUSTek Computer                | 2        | 13.33%  |
| Realtek Semiconductor           | 1        | 6.67%   |
| Qualcomm Atheros Communications | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |
| Apple                           | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3        | 20%     |
| Intel Bluetooth wireless interface                    | 2        | 13.33%  |
| Intel AX200 Bluetooth                                 | 2        | 13.33%  |
| Realtek Bluetooth Radio                               | 1        | 6.67%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 1        | 6.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 6.67%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 6.67%   |
| ASUS BCM20702A0                                       | 1        | 6.67%   |
| Apple Bluetooth USB Host Controller                   | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 57       | 35.4%   |
| AMD                 | 41       | 25.47%  |
| Nvidia              | 38       | 23.6%   |
| Creative Labs       | 7        | 4.35%   |
| ROCCAT              | 2        | 1.24%   |
| JMTek               | 2        | 1.24%   |
| Focusrite-Novation  | 2        | 1.24%   |
| C-Media Electronics | 2        | 1.24%   |
| VIA Technologies    | 1        | 0.62%   |
| Unknown             | 1        | 0.62%   |
| ULi Electronics     | 1        | 0.62%   |
| Texas Instruments   | 1        | 0.62%   |
| Tenx Technology     | 1        | 0.62%   |
| Razer USA           | 1        | 0.62%   |
| Microsoft           | 1        | 0.62%   |
| Logitech            | 1        | 0.62%   |
| Kingston Technology | 1        | 0.62%   |
| Fortemedia          | 1        | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 4.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 4.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 4.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7        | 3.78%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 3.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 2.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5        | 2.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5        | 2.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 4        | 2.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4        | 2.16%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 3        | 1.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3        | 1.62%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.62%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 3        | 1.62%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                      | 3        | 1.62%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.62%   |
| ROCCAT Khan AIMO                                                           | 2        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 2        | 1.08%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 1.08%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 1.08%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 1.08%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 2        | 1.08%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                            | 2        | 1.08%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 2        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 1.08%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 1.08%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 0.54%   |
| Unknown Realtek USB Audio Rear                                             | 1        | 0.54%   |
| Unknown Realtek USB Audio Front                                            | 1        | 0.54%   |
| ULi Electronics HD Audio Controller                                        | 1        | 0.54%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.54%   |
| Tenx Technology USB AUDIO                                                  | 1        | 0.54%   |
| Razer USA Kraken Tournament Edition                                        | 1        | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 0.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 0.54%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 0.54%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 0.54%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 0.54%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 0.54%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.54%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1        | 0.54%   |
| Nvidia GF110 High Definition Audio Controller                              | 1        | 0.54%   |
| Nvidia GF104 High Definition Audio Controller                              | 1        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 21       | 21.43%  |
| Corsair                      | 18       | 18.37%  |
| Kingston                     | 17       | 17.35%  |
| G.Skill                      | 12       | 12.24%  |
| SK Hynix                     | 8        | 8.16%   |
| Samsung Electronics          | 7        | 7.14%   |
| Micron Technology            | 3        | 3.06%   |
| Crucial                      | 3        | 3.06%   |
| Patriot                      | 2        | 2.04%   |
| Smart                        | 1        | 1.02%   |
| RZX                          | 1        | 1.02%   |
| PNY                          | 1        | 1.02%   |
| Patriot Memory (PDP Systems) | 1        | 1.02%   |
| OCZ                          | 1        | 1.02%   |
| Nanya Technology             | 1        | 1.02%   |
| Axiom                        | 1        | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1600MT/s                              | 3        | 2.68%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                               | 3        | 2.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                | 3        | 2.68%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s                | 3        | 2.68%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                              | 2        | 1.79%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                           | 2        | 1.79%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s                | 2        | 1.79%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 2        | 1.79%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                 | 2        | 1.79%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s               | 2        | 1.79%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s               | 2        | 1.79%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s                | 2        | 1.79%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                         | 1        | 0.89%   |
| Unknown RAM Module 512MB DIMM SDRAM                                  | 1        | 0.89%   |
| Unknown RAM Module 512MB DIMM DDR 400MT/s                            | 1        | 0.89%   |
| Unknown RAM Module 512MB DIMM DDR 200MT/s                            | 1        | 0.89%   |
| Unknown RAM Module 4GB DIMM SDRAM                                    | 1        | 0.89%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                         | 1        | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                             | 1        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                          | 1        | 0.89%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                           | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                 | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                          | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                           | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR 200MT/s                           | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR                                   | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                               | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                               | 1        | 0.89%   |
| Unknown RAM Module 1024MB DIMM                                       | 1        | 0.89%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s                  | 1        | 0.89%   |
| Smart RAM SH564128FH8N0QHSCG 4096MB DIMM DDR3 1333MT/s               | 1        | 0.89%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s               | 1        | 0.89%   |
| SK Hynix RAM HMT351U7EFR8C-PB 4096MB DIMM DDR3 1600MT/s              | 1        | 0.89%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 1        | 0.89%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s                 | 1        | 0.89%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                 | 1        | 0.89%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                | 1        | 0.89%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s                 | 1        | 0.89%   |
| Samsung RAM M391B5273DH0-YK0 4096MB DIMM DDR3 1600MT/s               | 1        | 0.89%   |
| Samsung RAM M391B5273CH0-CH9 4GB DIMM DDR3 1333MT/s                  | 1        | 0.89%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s                 | 1        | 0.89%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                  | 1        | 0.89%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM DDR2 1639MT/s              | 1        | 0.89%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 667MT/s                  | 1        | 0.89%   |
| RZX RAM D3D10M1600B-8G 8GB DIMM DDR3 1600MT/s                        | 1        | 0.89%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s                 | 1        | 0.89%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s                   | 1        | 0.89%   |
| Patriot RAM 3000 C15 Series 8GB DIMM DDR4 3000MT/s                   | 1        | 0.89%   |
| Patriot Memory (PDP Systems) RAM PSD48G320081 8GB DIMM DDR4 3200MT/s | 1        | 0.89%   |
| OCZ RAM OCZ2N800SR2G 2048MB DIMM DDR 800MT/s                         | 1        | 0.89%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                   | 1        | 0.89%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                  | 1        | 0.89%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s                  | 1        | 0.89%   |
| Kingston RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1        | 0.89%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                        | 1        | 0.89%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                         | 1        | 0.89%   |
| Kingston RAM KTC1G-UDIMM 1GB DIMM DDR2 1639MT/s                      | 1        | 0.89%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s                 | 1        | 0.89%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                    | 1        | 0.89%   |
| Kingston RAM KHX2133C13D4/8GX 8192MB DIMM DDR4 2133MT/s              | 1        | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 35.56%  |
| DDR3    | 32       | 35.56%  |
| Unknown | 9        | 10%     |
| DDR2    | 8        | 8.89%   |
| DDR     | 5        | 5.56%   |
| SDRAM   | 4        | 4.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 87       | 96.67%  |
| SODIMM | 3        | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 32.65%  |
| 4096  | 28       | 28.57%  |
| 2048  | 15       | 15.31%  |
| 1024  | 9        | 9.18%   |
| 16384 | 8        | 8.16%   |
| 32768 | 3        | 3.06%   |
| 512   | 3        | 3.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 21.15%  |
| 1333    | 13       | 12.5%   |
| 2133    | 8        | 7.69%   |
| 3200    | 6        | 5.77%   |
| 3000    | 6        | 5.77%   |
| 3600    | 5        | 4.81%   |
| 800     | 5        | 4.81%   |
| 667     | 4        | 3.85%   |
| Unknown | 4        | 3.85%   |
| 3466    | 3        | 2.88%   |
| 2400    | 3        | 2.88%   |
| 333     | 3        | 2.88%   |
| 49926   | 2        | 1.92%   |
| 3400    | 2        | 1.92%   |
| 2933    | 2        | 1.92%   |
| 1867    | 2        | 1.92%   |
| 1800    | 2        | 1.92%   |
| 1639    | 2        | 1.92%   |
| 400     | 2        | 1.92%   |
| 3266    | 1        | 0.96%   |
| 3100    | 1        | 0.96%   |
| 2667    | 1        | 0.96%   |
| 2666    | 1        | 0.96%   |
| 2048    | 1        | 0.96%   |
| 1400    | 1        | 0.96%   |
| 533     | 1        | 0.96%   |
| 200     | 1        | 0.96%   |

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
| Logitech                      | 7        | 53.85%  |
| Generalplus Technology        | 2        | 15.38%  |
| Sunplus Technology            | 1        | 7.69%   |
| Sunplus Innovation Technology | 1        | 7.69%   |
| Microsoft                     | 1        | 7.69%   |
| Huawei Technologies           | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Logitech Webcam C930e                                   | 2        | 15.38%  |
| Logitech Webcam C270                                    | 2        | 15.38%  |
| Logitech Webcam C200                                    | 2        | 15.38%  |
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 7.69%   |
| Sunplus Full HD webcam                                  | 1        | 7.69%   |
| Microsoft LifeCam HD-3000                               | 1        | 7.69%   |
| Logitech Webcam Pro 9000                                | 1        | 7.69%   |
| Huawei UVC Camera                                       | 1        | 7.69%   |
| Generalplus GENERAL WEBCAM                              | 1        | 7.69%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 1        | 7.69%   |

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
| 0     | 84       | 91.3%   |
| 1     | 7        | 7.61%   |
| 3     | 1        | 1.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 4        | 44.44%  |
| Unassigned class      | 2        | 22.22%  |
| Net/wireless          | 1        | 11.11%  |
| Multimedia controller | 1        | 11.11%  |
| Camera                | 1        | 11.11%  |

