Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 3548

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 1495                        | [48d0ae2bf5](https://linux-hardware.org/?probe=48d0ae2bf5) | Dec 30, 2023 |
| ASUSTek       | CM6870                      | [529b92f758](https://linux-hardware.org/?probe=529b92f758) | Dec 28, 2023 |
| Gigabyte      | P55-UD4P                    | [62b547894e](https://linux-hardware.org/?probe=62b547894e) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| HP            | 3396                        | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| ASRock        | 970M Pro3                   | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Gigabyte      | X570S UD                    | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| Dell          | 0M5WNK A02                  | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| Acer          | Aspire 1510 Rev.A           | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| AZW           | MINI S                      | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| Dell          | 0KP561                      | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| Intel         | H61                         | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| MSI           | A78M-E45                    | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| MSI           | X299 GAMING PRO CARBON      | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| AZW           | MINI S                      | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| AZW           | MINI S                      | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| MSI           | B85M-G43                    | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| AZW           | U59                         | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| ASRock        | AB350 Pro4                  | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| Dell          | 0D6H9T A02                  | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | 1905                        | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| ASUSTek       | PRIME Z370-P                | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| ASUSTek       | M5A97                       | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| ASRock        | B550 Pro4                   | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Dell          | 02YRK5 A02                  | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| WanYou        | WanYouChunXiao              | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| ASRock        | J3455-ITX                   | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| Acer          | EG43M                       | [53270970b2](https://linux-hardware.org/?probe=53270970b2) | Nov 09, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Unknown       | Unknown                     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| Dell          | 01XK1W A00                  | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| ASRock        | H170M Pro4                  | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| ASRock        | Z77 WS                      | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [b684f82e3c](https://linux-hardware.org/?probe=b684f82e3c) | Nov 01, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Gigabyte      | H170N-WIFI-CF               | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| Shenzhen M... | TH80                        | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| ASUSTek       | H81M-PLUS                   | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| Gigabyte      | 990FXA-UD5                  | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASRock        | B550 Pro4                   | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [d48d54a951](https://linux-hardware.org/?probe=d48d54a951) | Oct 16, 2023 |
| ASUSTek       | B85M-E                      | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| ASUSTek       | PRIME B550M-A               | [2686ddd07b](https://linux-hardware.org/?probe=2686ddd07b) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [925371c475](https://linux-hardware.org/?probe=925371c475) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [8606120535](https://linux-hardware.org/?probe=8606120535) | Oct 10, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| Gigabyte      | G31M-ES2L                   | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b54dca932a](https://linux-hardware.org/?probe=b54dca932a) | Oct 07, 2023 |
| ASUSTek       | PRIME B365M-A               | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| ASRock        | H81M-HG4                    | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| ASRock        | 970M Pro3                   | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Intel         | DP35DP AAD81073-206         | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| MSI           | MS-7318                     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| HP            | 1905                        | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| MSI           | MS-7318                     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| NetGear       | ReadyDATA 5200              | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| ASRock        | B550 Pro4                   | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| Gigabyte      | H55N-USB3                   | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Supermicro    | X9DR3-F                     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| Dell          | 01XK1W A00                  | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Gigabyte      | P85-D3                      | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | 970A-G46                    | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| ASRock        | H81M-HG4                    | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| HP            | 876C SMVB                   | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| ASRock        | J3455-ITX                   | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| MEGA          | G41T-M7 LGT                 | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| HP            | 1495                        | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 1495                        | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| HP            | 158A                        | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| ASRock        | J4125B-ITX                  | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Medion        | MS-7728                     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Dell          | 0CT017                      | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Unknown       | Unknown                     | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| ASUSTek       | P5LD2-SE                    | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Biostar       | B365MHC                     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Gigabyte      | H510M H                     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| ASRock        | X300-ITX                    | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Unknown       | Unknown                     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 0K240Y A01                  | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| ASRockRack    | X470D4U                     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Dell          | 06X1TJ A00                  | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Phoenix Co... | PSB514 A11                  | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| HP            | 805A                        | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| MSI           | H81M-P33                    | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Unknown       | Unknown                     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| ASRock        | FM2A68M-DG3+                | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| MSI           | H170M PRO-VDH               | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Dell          | 0T10XW A01                  | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| AZW           | U59                         | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| AZW           | MINI S                      | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| HP            | 895C                        | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Dell          | 0KYWH7 A00                  | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| ASUSTek       | Z87-A                       | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| Supermicro    | X8ST3                       | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| Gigabyte      | B365M D3H-CF                | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Shuttle       | FS61                        | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| AMI           | Cherry Trail CR             | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| ASRock        | H61M-HVS                    | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASRockRack    | X470D4U                     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| HP            | 3397                        | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| ASRockRack    | X470D4U                     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| MSI           | H81M-P33                    | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| Dell          | 0PU052                      | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| AZW           | U59                         | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| HP            | 1589                        | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Supermicro    | X9DR3-F                     | [afcfc0fdf3](https://linux-hardware.org/?probe=afcfc0fdf3) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| ASRock        | H310CM-HDV                  | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| MSI           | Z390-A PRO                  | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Unknown       | Unknown                     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Intel         | X99                         | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| AZW           | MINI S                      | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASUSTek       | Berkeley                    | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | F2A85-M                     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| HP            | 2B38                        | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Dell          | 09KPNV A00                  | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| HP            | 8076                        | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| AMI           | Cherry Trail CR             | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Dell          | 0782GW A00                  | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| HP            | 339A                        | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| HP            | 1632                        | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| AZW           | Green G3                    | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| Dell          | 0C1R19 A01                  | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Unknown       | Unknown                     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Dell          | 0RN474                      | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| Unknown       | Unknown                     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| BESSTAR Te... | DMAF5                       | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| HP            | 2B38                        | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Medion        | MS-7708                     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| MSI           | MS-B0A21                    | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| HP            | 1632                        | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| HP            | 8056                        | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Shuttle       | FS81                        | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| HP            | 18E7                        | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| HP            | 1589                        | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| HP            | 2B29                        | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| MSI           | MS-7253                     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| MSI           | MS-B1831                    | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| HP            | 895C                        | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [9c6a3de994](https://linux-hardware.org/?probe=9c6a3de994) | Apr 05, 2023 |
| HP            | 895C                        | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [2783ec6da9](https://linux-hardware.org/?probe=2783ec6da9) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | 1790                        | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [7f904181ea](https://linux-hardware.org/?probe=7f904181ea) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| Acer          | WG43M                       | [10bf0c0d1a](https://linux-hardware.org/?probe=10bf0c0d1a) | Apr 04, 2023 |
| MSI           | MAG B460 TORPEDO            | [62a628da55](https://linux-hardware.org/?probe=62a628da55) | Apr 04, 2023 |
| Unknown       | Q-790                       | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| ASUSTek       | P8Z77-M                     | [ec9901fcd5](https://linux-hardware.org/?probe=ec9901fcd5) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [aaa2e273c1](https://linux-hardware.org/?probe=aaa2e273c1) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cbcfbb8783](https://linux-hardware.org/?probe=cbcfbb8783) | Apr 03, 2023 |
| BESSTAR Te... | HM90                        | [722013016f](https://linux-hardware.org/?probe=722013016f) | Apr 03, 2023 |
| Shuttle       | FH370                       | [29b2ad6149](https://linux-hardware.org/?probe=29b2ad6149) | Apr 03, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| Unknown       | Unknown                     | [077bed9951](https://linux-hardware.org/?probe=077bed9951) | Apr 02, 2023 |
| Google        | Panther                     | [73f3ed3c65](https://linux-hardware.org/?probe=73f3ed3c65) | Apr 02, 2023 |
| MSI           | MS-7318                     | [3d02816b24](https://linux-hardware.org/?probe=3d02816b24) | Apr 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2a597d7a33](https://linux-hardware.org/?probe=2a597d7a33) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [32c0716bfa](https://linux-hardware.org/?probe=32c0716bfa) | Apr 01, 2023 |
| Medion        | TJ4125                      | [2627cc2d42](https://linux-hardware.org/?probe=2627cc2d42) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | TS10                        | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| HP            | 3048h                       | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| ECS           | G31T-M                      | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LE                  | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| HP            | 83E2                        | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Dell          | 0PU052                      | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| ASRockRack    | E3C242D4U2-2T               | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| HP            | 3048h                       | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| Supermicro    | X10DRi-T4+                  | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| HP            | 198E                        | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| HP            | 1495                        | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| Medion        | TJ4125                      | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Dell          | 0F5C5X A00                  | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| AZW           | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| ASRock        | 990FX Extreme4              | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Unknown       | i855-W83627HF               | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Win elemen... | M600                        | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [80644bb1ec](https://linux-hardware.org/?probe=80644bb1ec) | Mar 02, 2023 |
| Gigabyte      | H310M H x.x                 | [f6b780ae7e](https://linux-hardware.org/?probe=f6b780ae7e) | Mar 01, 2023 |
| CWWK          | CW-J6-6L                    | [aea23f5903](https://linux-hardware.org/?probe=aea23f5903) | Mar 01, 2023 |
| Gigabyte      | H310M H x.x                 | [25112e4f96](https://linux-hardware.org/?probe=25112e4f96) | Mar 01, 2023 |
| Unknown       | J3160-4L                    | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| Gigabyte      | B650M DS3H                  | [6e5e4d848d](https://linux-hardware.org/?probe=6e5e4d848d) | Mar 01, 2023 |
| AZW           | MINI S                      | [2206d30a53](https://linux-hardware.org/?probe=2206d30a53) | Mar 01, 2023 |
| HP            | 8433 11                     | [15dccf1191](https://linux-hardware.org/?probe=15dccf1191) | Mar 01, 2023 |
| Medion        | TJ4125                      | [2024916642](https://linux-hardware.org/?probe=2024916642) | Feb 28, 2023 |
| CWWK          | CW-J6-6L                    | [46c17d2c14](https://linux-hardware.org/?probe=46c17d2c14) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| HP            | 83E2                        | [fdbe4ec1cb](https://linux-hardware.org/?probe=fdbe4ec1cb) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| AZW           | MINI S                      | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| ASRock        | N68C-S UCC                  | [a5469adf59](https://linux-hardware.org/?probe=a5469adf59) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| HP            | 3397                        | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Dell          | 0MH651                      | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| ASRock        | 970M Pro3                   | [787ddfd44c](https://linux-hardware.org/?probe=787ddfd44c) | Feb 26, 2023 |
| Gigabyte      | B550 GAMING X V2            | [9c64d6366e](https://linux-hardware.org/?probe=9c64d6366e) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| MSI           | B85M-E45                    | [a7748c0e8b](https://linux-hardware.org/?probe=a7748c0e8b) | Feb 25, 2023 |
| Medion        | TJ4125                      | [bde9228741](https://linux-hardware.org/?probe=bde9228741) | Feb 25, 2023 |
| Intel         | JSL MRD                     | [84a33f3c84](https://linux-hardware.org/?probe=84a33f3c84) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fe6e0dcde](https://linux-hardware.org/?probe=7fe6e0dcde) | Feb 24, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f5b4a5da72](https://linux-hardware.org/?probe=f5b4a5da72) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [efc9b2fdbf](https://linux-hardware.org/?probe=efc9b2fdbf) | Feb 24, 2023 |
| HP            | 82F2 A01                    | [24dc4341d3](https://linux-hardware.org/?probe=24dc4341d3) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [52b14c9235](https://linux-hardware.org/?probe=52b14c9235) | Feb 24, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [a09d17dd16](https://linux-hardware.org/?probe=a09d17dd16) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [0806dcb9ca](https://linux-hardware.org/?probe=0806dcb9ca) | Feb 24, 2023 |
| Dell          | 0GY6Y8 A01                  | [e3cdd0b411](https://linux-hardware.org/?probe=e3cdd0b411) | Feb 24, 2023 |
| Gigabyte      | H610M S2H DDR4              | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| ASUSTek       | KRPA-U16 Series             | [e417ffd8e7](https://linux-hardware.org/?probe=e417ffd8e7) | Feb 23, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [4f19f71811](https://linux-hardware.org/?probe=4f19f71811) | Feb 23, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Intel         | H61                         | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| AZW           | U59                         | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| AZW           | U59                         | [368562790b](https://linux-hardware.org/?probe=368562790b) | Feb 22, 2023 |
| Unknown       | Unknown                     | [5cf4127d47](https://linux-hardware.org/?probe=5cf4127d47) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| ASUSTek       | P8B75-V                     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58e 7269E3S    | [6b30da3a31](https://linux-hardware.org/?probe=6b30da3a31) | Feb 20, 2023 |
| Dell          | 073MMW A02                  | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Intel         | JSL MRD                     | [5e021f6a92](https://linux-hardware.org/?probe=5e021f6a92) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Gigabyte      | GA-A55M-DS2                 | [3159aede6c](https://linux-hardware.org/?probe=3159aede6c) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| Intel         | H61                         | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| MSI           | X399 SLI PLUS               | [8741094cd9](https://linux-hardware.org/?probe=8741094cd9) | Feb 17, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbce6ba3b1](https://linux-hardware.org/?probe=bbce6ba3b1) | Feb 16, 2023 |
| Lenovo        | 1030 SDK0J40705 WIN 3425... | [daed0124f0](https://linux-hardware.org/?probe=daed0124f0) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| Itautec       | ST 4265                     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| ASUSTek       | P5GD1 PRO                   | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| ASRock        | Z77 Extreme6                | [48328ab864](https://linux-hardware.org/?probe=48328ab864) | Feb 15, 2023 |
| Unknown       | Unknown                     | [0ac84e31dd](https://linux-hardware.org/?probe=0ac84e31dd) | Feb 14, 2023 |
| Dell          | 0RN474                      | [5c1bf45372](https://linux-hardware.org/?probe=5c1bf45372) | Feb 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| Shenzhen M... | F6BFC                       | [67b141272c](https://linux-hardware.org/?probe=67b141272c) | Feb 14, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [c69ee15636](https://linux-hardware.org/?probe=c69ee15636) | Feb 14, 2023 |
| Dell          | 0RN474                      | [20f3c37dc2](https://linux-hardware.org/?probe=20f3c37dc2) | Feb 14, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [55e684c121](https://linux-hardware.org/?probe=55e684c121) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [e83cd923a5](https://linux-hardware.org/?probe=e83cd923a5) | Feb 13, 2023 |
| Gigabyte      | H81M-S2V                    | [09dff429cd](https://linux-hardware.org/?probe=09dff429cd) | Feb 12, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [52674d23ad](https://linux-hardware.org/?probe=52674d23ad) | Feb 12, 2023 |
| ASRock        | X300M-STX                   | [4829b991be](https://linux-hardware.org/?probe=4829b991be) | Feb 12, 2023 |
| ASRock        | A320M-DVS R4.0              | [1589cfe790](https://linux-hardware.org/?probe=1589cfe790) | Feb 11, 2023 |
| ASRock        | A320M-DVS R4.0              | [22fdde82eb](https://linux-hardware.org/?probe=22fdde82eb) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [d003016397](https://linux-hardware.org/?probe=d003016397) | Feb 11, 2023 |
| AZW           | U59                         | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Dell          | 0J3C2F A00                  | [a3f08d08aa](https://linux-hardware.org/?probe=a3f08d08aa) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| AMD           | CM-iGLX Platform Board R... | [c256a73072](https://linux-hardware.org/?probe=c256a73072) | Feb 11, 2023 |
| Maxtang       | EHL30 V1.0                  | [4d133c615c](https://linux-hardware.org/?probe=4d133c615c) | Feb 10, 2023 |
| ASRockRack    | X570D4U                     | [bb2c98768e](https://linux-hardware.org/?probe=bb2c98768e) | Feb 10, 2023 |
| Intel         | H61                         | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8c4ab545de](https://linux-hardware.org/?probe=8c4ab545de) | Feb 09, 2023 |
| Acer          | Veriton N4630G              | [262d8ec347](https://linux-hardware.org/?probe=262d8ec347) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a0132107aa](https://linux-hardware.org/?probe=a0132107aa) | Feb 08, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [6231dbe6d4](https://linux-hardware.org/?probe=6231dbe6d4) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| HP            | 3397                        | [2fb7638874](https://linux-hardware.org/?probe=2fb7638874) | Feb 06, 2023 |
| Intel         | DH77EB AAG39073-304         | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| AZW           | U59                         | [b97c4f6277](https://linux-hardware.org/?probe=b97c4f6277) | Feb 06, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [db292bc714](https://linux-hardware.org/?probe=db292bc714) | Feb 05, 2023 |
| HP            | 0A64h                       | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Huanan        | X99-T8D V1.2                | [cb7e750cee](https://linux-hardware.org/?probe=cb7e750cee) | Feb 05, 2023 |
| Gigabyte      | H61MA-D2V                   | [b708cdc12f](https://linux-hardware.org/?probe=b708cdc12f) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | [6023defc83](https://linux-hardware.org/?probe=6023defc83) | Feb 05, 2023 |
| Unknown       | Unknown                     | [5a491991ef](https://linux-hardware.org/?probe=5a491991ef) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| OEM           | Intel H81                   | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [2543adebba](https://linux-hardware.org/?probe=2543adebba) | Feb 05, 2023 |
| HP            | 1589                        | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| ASRock        | 4X4-4000 Series             | [4ed27fe851](https://linux-hardware.org/?probe=4ed27fe851) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [018b3728ea](https://linux-hardware.org/?probe=018b3728ea) | Feb 04, 2023 |
| Gigabyte      | MZBSWMP-00                  | [52bb20e0b2](https://linux-hardware.org/?probe=52bb20e0b2) | Feb 04, 2023 |
| ECS           | A780GM-A                    | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| HP            | 3048h                       | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| AZW           | MINI S                      | [6c746a5f95](https://linux-hardware.org/?probe=6c746a5f95) | Feb 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| BESSTAR Te... | TH50                        | [6d39ef2792](https://linux-hardware.org/?probe=6d39ef2792) | Feb 03, 2023 |
| Intel         | SKYBAY                      | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| NEC Comput... | MS9666 011                  | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | [2cb0ec3b98](https://linux-hardware.org/?probe=2cb0ec3b98) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 0A64h                       | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Dell          | 02YRK5 A02                  | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| AZW           | MINI S                      | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| HP            | 805D                        | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| ASRock        | 990FX Killer                | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | PRIME X399-A                | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| AZW           | SEi                         | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Medion        | TJ4125                      | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| ASRock        | A300M-STX                   | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Intel         | JSL MRD                     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [deb2b560bc](https://linux-hardware.org/?probe=deb2b560bc) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| Intel         | DH77EB AAG39073-304         | [cb3c4b1eb4](https://linux-hardware.org/?probe=cb3c4b1eb4) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| MSI           | MS-B1711                    | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Medion        | TJ4125                      | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| HP            | 21EF                        | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| HP            | 21EF                        | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LX V2              | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| Gigabyte      | X570 GAMING X               | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d93218978e](https://linux-hardware.org/?probe=d93218978e) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [25bd789598](https://linux-hardware.org/?probe=25bd789598) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c040acffcf](https://linux-hardware.org/?probe=c040acffcf) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Gigabyte      | H510M H                     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [982de9c98d](https://linux-hardware.org/?probe=982de9c98d) | Jan 06, 2023 |
| Dell          | 01XK1W A00                  | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| ELSKY         | M219FN-6C                   | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-7-amd64         | 513      | 18.51%  |
| 5.10.0-8-amd64         | 230      | 8.3%    |
| 5.10.0-21-amd64        | 181      | 6.53%   |
| 5.10.0-9-amd64         | 121      | 4.37%   |
| 5.10.0-2-amd64         | 116      | 4.18%   |
| 5.10.0-20-amd64        | 104      | 3.75%   |
| 5.10.0-19-amd64        | 104      | 3.75%   |
| 5.10.0-23-amd64        | 90       | 3.25%   |
| 5.10.0-13-amd64        | 87       | 3.14%   |
| 5.10.0-18-amd64        | 83       | 2.99%   |
| 5.10.0-10-amd64        | 73       | 2.63%   |
| 5.10.0-11-amd64        | 72       | 2.6%    |
| 5.10.0-16-amd64        | 69       | 2.49%   |
| 5.10.0-14-amd64        | 51       | 1.84%   |
| 5.10.0-15-amd64        | 44       | 1.59%   |
| 5.10.0-22-amd64        | 43       | 1.55%   |
| 5.10.0-17-amd64        | 43       | 1.55%   |
| 5.10.0-26-amd64        | 29       | 1.05%   |
| 5.10.0-12-amd64        | 29       | 1.05%   |
| 5.15.0-2-amd64         | 22       | 0.79%   |
| 5.16.0-0.bpo.4-amd64   | 20       | 0.72%   |
| 5.10.0-25-amd64        | 20       | 0.72%   |
| 6.0.0-0.deb11.6-amd64  | 19       | 0.69%   |
| 5.15.102-1-pve         | 19       | 0.69%   |
| 5.13.19-6-pve          | 18       | 0.65%   |
| 5.18.0-0.bpo.1-amd64   | 16       | 0.58%   |
| 6.1.0-0.deb11.7-amd64  | 14       | 0.51%   |
| 5.18.0-0.deb11.4-amd64 | 14       | 0.51%   |
| 5.15.83-1-pve          | 14       | 0.51%   |
| 5.15.74-1-pve          | 14       | 0.51%   |
| 5.13.19-2-pve          | 14       | 0.51%   |
| 5.10.0-6-amd64         | 13       | 0.47%   |
| 5.15.85-1-pve          | 12       | 0.43%   |
| 5.15.53-1-pve          | 11       | 0.4%    |
| 5.15.30-2-pve          | 11       | 0.4%    |
| 5.15.107-2-pve         | 11       | 0.4%    |
| 6.1.0-0.deb11.11-amd64 | 9        | 0.32%   |
| 6.0.0-0.deb11.2-amd64  | 9        | 0.32%   |
| 5.15.35-1-pve          | 9        | 0.32%   |
| 5.19.0-0.deb11.2-amd64 | 8        | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2051     | 78.07%  |
| 5.13.19  | 44       | 1.67%   |
| 6.1.0    | 43       | 1.64%   |
| 5.18.0   | 43       | 1.64%   |
| 6.0.0    | 39       | 1.48%   |
| 5.15.0   | 37       | 1.41%   |
| 5.16.0   | 31       | 1.18%   |
| 5.19.0   | 21       | 0.8%    |
| 5.15.107 | 19       | 0.72%   |
| 5.15.102 | 19       | 0.72%   |
| 5.14.0   | 17       | 0.65%   |
| 5.11.22  | 17       | 0.65%   |
| 5.15.83  | 14       | 0.53%   |
| 5.15.74  | 14       | 0.53%   |
| 5.15.39  | 13       | 0.49%   |
| 5.15.35  | 13       | 0.49%   |
| 5.15.85  | 12       | 0.46%   |
| 5.15.53  | 11       | 0.42%   |
| 5.15.30  | 11       | 0.42%   |
| 5.17.0   | 9        | 0.34%   |
| 5.15.108 | 8        | 0.3%    |
| 5.15.104 | 8        | 0.3%    |
| 6.2.6    | 5        | 0.19%   |
| 6.1.15   | 5        | 0.19%   |
| 6.2.9    | 4        | 0.15%   |
| 6.2.11   | 4        | 0.15%   |
| 6.0.8    | 4        | 0.15%   |
| 5.19.17  | 4        | 0.15%   |
| 5.15.60  | 4        | 0.15%   |
| 5.15.126 | 4        | 0.15%   |
| 5.15.116 | 4        | 0.15%   |
| 5.13.0   | 4        | 0.15%   |
| 5.16.5   | 3        | 0.11%   |
| 5.15.79  | 3        | 0.11%   |
| 5.10.57  | 3        | 0.11%   |
| 4.19.0   | 3        | 0.11%   |
| 6.1.12   | 2        | 0.08%   |
| 6.0.19   | 2        | 0.08%   |
| 6.0.12   | 2        | 0.08%   |
| 5.15.64  | 2        | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10     | 2071     | 79.5%   |
| 5.15     | 186      | 7.14%   |
| 5.13     | 54       | 2.07%   |
| 6.1      | 53       | 2.03%   |
| 6.0      | 48       | 1.84%   |
| 5.18     | 47       | 1.8%    |
| 5.16     | 36       | 1.38%   |
| 5.19     | 29       | 1.11%   |
| 5.11     | 20       | 0.77%   |
| 5.14     | 18       | 0.69%   |
| 6.2      | 17       | 0.65%   |
| 5.17     | 11       | 0.42%   |
| 6.3      | 3        | 0.12%   |
| 4.19     | 3        | 0.12%   |
| 5.4      | 2        | 0.08%   |
| 6.6      | 1        | 0.04%   |
| 6.5      | 1        | 0.04%   |
| 5.8      | 1        | 0.04%   |
| 5.5      | 1        | 0.04%   |
| 5.12     | 1        | 0.04%   |
| 5.10.164 | 1        | 0.04%   |
| 5.1      | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 2480     | 97.52%  |
| i686    | 57       | 2.24%   |
| riscv64 | 4        | 0.16%   |
| i586    | 1        | 0.04%   |
| armv7l  | 1        | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1066     | 41.35%  |
| GNOME             | 488      | 18.93%  |
| XFCE              | 279      | 10.82%  |
| KDE5              | 268      | 10.4%   |
| MATE              | 110      | 4.27%   |
| X-Cinnamon        | 86       | 3.34%   |
| LXDE              | 70       | 2.72%   |
| Cinnamon          | 60       | 2.33%   |
| LXQt              | 34       | 1.32%   |
| i3                | 24       | 0.93%   |
| Openbox           | 17       | 0.66%   |
| KDE               | 14       | 0.54%   |
| Trinity           | 13       | 0.5%    |
| lightdm-xsession  | 11       | 0.43%   |
| GNOME Flashback   | 11       | 0.43%   |
| Budgie            | 10       | 0.39%   |
| GNOME Classic     | 4        | 0.16%   |
| sway              | 3        | 0.12%   |
| awesome           | 3        | 0.12%   |
| UKUI              | 1        | 0.04%   |
| GNUstep           | 1        | 0.04%   |
| gnome-xorg        | 1        | 0.04%   |
| Enlightenment     | 1        | 0.04%   |
| e16-session       | 1        | 0.04%   |
| DWM               | 1        | 0.04%   |
| /etc/X11/Xsession | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 1164     | 45.24%  |
| Unknown     | 688      | 26.74%  |
| Tty         | 468      | 18.19%  |
| Wayland     | 248      | 9.64%   |
| Web         | 3        | 0.12%   |
| Unspecified | 2        | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1361     | 53.1%   |
| LightDM | 477      | 18.61%  |
| GDM     | 357      | 13.93%  |
| SDDM    | 224      | 8.74%   |
| TDM     | 73       | 2.85%   |
| GDM3    | 47       | 1.83%   |
| SLiM    | 9        | 0.35%   |
| XDM     | 6        | 0.23%   |
| NODM    | 5        | 0.2%    |
| LXDM    | 2        | 0.08%   |
| WDM     | 1        | 0.04%   |
| SU      | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 919      | 35.95%  |
| ru_RU   | 670      | 26.21%  |
| de_DE   | 140      | 5.48%   |
| fr_FR   | 130      | 5.09%   |
| en_GB   | 104      | 4.07%   |
| es_ES   | 76       | 2.97%   |
| pt_BR   | 55       | 2.15%   |
| it_IT   | 49       | 1.92%   |
| Unknown | 49       | 1.92%   |
| en_CA   | 34       | 1.33%   |
| en_AU   | 32       | 1.25%   |
| C       | 32       | 1.25%   |
| pl_PL   | 24       | 0.94%   |
| es_MX   | 15       | 0.59%   |
| en_IE   | 14       | 0.55%   |
| es_AR   | 13       | 0.51%   |
| ja_JP   | 12       | 0.47%   |
| hu_HU   | 12       | 0.47%   |
| es_VE   | 12       | 0.47%   |
| zh_CN   | 11       | 0.43%   |
| en_IN   | 9        | 0.35%   |
| de_AT   | 9        | 0.35%   |
| nl_BE   | 8        | 0.31%   |
| en_NZ   | 7        | 0.27%   |
| pt_PT   | 6        | 0.23%   |
| nl_NL   | 6        | 0.23%   |
| de_CH   | 6        | 0.23%   |
| en_ZA   | 5        | 0.2%    |
| en_HK   | 5        | 0.2%    |
| ca_ES   | 5        | 0.2%    |
| uk_UA   | 4        | 0.16%   |
| sv_SE   | 4        | 0.16%   |
| fr_BE   | 4        | 0.16%   |
| cs_CZ   | 4        | 0.16%   |
| tr_TR   | 3        | 0.12%   |
| ru_UA   | 3        | 0.12%   |
| hr_HR   | 3        | 0.12%   |
| fi_FI   | 3        | 0.12%   |
| es_UY   | 3        | 0.12%   |
| es_PE   | 3        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1568     | 60.78%  |
| EFI  | 1012     | 39.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1669     | 65.27%  |
| Overlay | 671      | 26.24%  |
| Btrfs   | 86       | 3.36%   |
| Zfs     | 67       | 2.62%   |
| Xfs     | 35       | 1.37%   |
| Ext3    | 13       | 0.51%   |
| Tmpfs   | 7        | 0.27%   |
| Unknown | 4        | 0.16%   |
| Ext2    | 3        | 0.12%   |
| Rootfs  | 1        | 0.04%   |
| Aufs    | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1243     | 48.23%  |
| MBR     | 989      | 38.38%  |
| Unknown | 345      | 13.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2089     | 81.41%  |
| Yes       | 477      | 18.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1492     | 58.14%  |
| Yes       | 1074     | 41.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 669      | 26.32%  |
| Gigabyte Technology                  | 421      | 16.56%  |
| MSI                                  | 259      | 10.19%  |
| ASRock                               | 236      | 9.28%   |
| Dell                                 | 181      | 7.12%   |
| Hewlett-Packard                      | 163      | 6.41%   |
| Intel                                | 84       | 3.3%    |
| Lenovo                               | 81       | 3.19%   |
| Unknown                              | 50       | 1.97%   |
| ECS                                  | 49       | 1.93%   |
| Fujitsu                              | 32       | 1.26%   |
| AZW                                  | 30       | 1.18%   |
| ASRockRack                           | 30       | 1.18%   |
| Foxconn                              | 28       | 1.1%    |
| Supermicro                           | 19       | 0.75%   |
| Acer                                 | 19       | 0.75%   |
| Pegatron                             | 14       | 0.55%   |
| Biostar                              | 13       | 0.51%   |
| Inventec                             | 11       | 0.43%   |
| BESSTAR Tech                         | 9        | 0.35%   |
| Medion                               | 7        | 0.28%   |
| IceWhale Technology                  | 7        | 0.28%   |
| Huanan                               | 7        | 0.28%   |
| Shuttle                              | 6        | 0.24%   |
| Google                               | 6        | 0.24%   |
| Apple                                | 5        | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 4        | 0.16%   |
| Positivo                             | 4        | 0.16%   |
| HPE                                  | 4        | 0.16%   |
| Fujitsu Siemens                      | 4        | 0.16%   |
| Techvision                           | 3        | 0.12%   |
| Packard Bell                         | 3        | 0.12%   |
| Hardkernel                           | 3        | 0.12%   |
| Aquarius                             | 3        | 0.12%   |
| AMI                                  | 3        | 0.12%   |
| AAEON                                | 3        | 0.12%   |
| Thecus                               | 2        | 0.08%   |
| Semp Toshiba                         | 2        | 0.08%   |
| Seeed Studio                         | 2        | 0.08%   |
| PC Engines                           | 2        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 81       | 3.19%   |
| ASUS S20 K29                 | 55       | 2.16%   |
| Unknown                      | 51       | 2.01%   |
| MSI MS-7996                  | 38       | 1.49%   |
| MSI MS-7817                  | 22       | 0.87%   |
| ECS G31T-M9                  | 22       | 0.87%   |
| ASRock H470M-HVS             | 20       | 0.79%   |
| Gigabyte H81M-S2V            | 18       | 0.71%   |
| ASUS PRIME H510M-A           | 17       | 0.67%   |
| Gigabyte H410M S2H           | 16       | 0.63%   |
| ECS H61H2-M13                | 16       | 0.63%   |
| ASUS P8H61-M LX3 R2.0        | 15       | 0.59%   |
| Dell OptiPlex 7010           | 13       | 0.51%   |
| AZW U59                      | 12       | 0.47%   |
| AZW MINI S                   | 12       | 0.47%   |
| Gigabyte B450M DS3H          | 11       | 0.43%   |
| ASUS PRIME A320M-K           | 11       | 0.43%   |
| ASUS TUF Gaming X570-PLUS    | 10       | 0.39%   |
| ASUS PRIME B450M-A           | 10       | 0.39%   |
| ASUS H110M-R                 | 10       | 0.39%   |
| HP Z420 Workstation          | 9        | 0.35%   |
| HP ProLiant MicroServer Gen8 | 9        | 0.35%   |
| ASUS P8H67-M                 | 9        | 0.35%   |
| Gigabyte B360M H             | 8        | 0.31%   |
| Dell OptiPlex 9020           | 8        | 0.31%   |
| Dell OptiPlex 790            | 8        | 0.31%   |
| ASRock H61M-VG4              | 8        | 0.31%   |
| ASRock G31M-VS2              | 8        | 0.31%   |
| ASRock B450M Pro4            | 8        | 0.31%   |
| MSI MS-7C91                  | 7        | 0.28%   |
| MSI MS-7C56                  | 7        | 0.28%   |
| MSI MS-7C02                  | 7        | 0.28%   |
| Gigabyte P85-D3              | 7        | 0.28%   |
| Gigabyte A320M-S2H           | 7        | 0.28%   |
| Fujitsu ESPRIMO P720         | 7        | 0.28%   |
| ASUS P8H61-M LX3 PLUS R2.0   | 7        | 0.28%   |
| ASUS P5G41T-M LE             | 7        | 0.28%   |
| ASRockRack X470D4U           | 7        | 0.28%   |
| Inventec D CLASS             | 6        | 0.24%   |
| Intel Pro, Std, Elt Series   | 6        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 143      | 5.63%   |
| Dell OptiPlex          | 97       | 3.82%   |
| ASUS All               | 81       | 3.19%   |
| ASUS S20               | 55       | 2.16%   |
| Unknown                | 51       | 2.01%   |
| Lenovo ThinkCentre     | 47       | 1.85%   |
| ASUS ROG               | 47       | 1.85%   |
| HP Compaq              | 44       | 1.73%   |
| ASUS TUF               | 43       | 1.69%   |
| Dell Precision         | 41       | 1.61%   |
| MSI MS-7996            | 38       | 1.49%   |
| ASUS P8H61-M           | 31       | 1.22%   |
| Gigabyte B450M         | 25       | 0.98%   |
| HP EliteDesk           | 23       | 0.9%    |
| MSI MS-7817            | 22       | 0.87%   |
| ECS G31T-M9            | 22       | 0.87%   |
| ASUS PRO               | 21       | 0.83%   |
| HP ProLiant            | 20       | 0.79%   |
| Fujitsu ESPRIMO        | 20       | 0.79%   |
| ASRock H470M-HVS       | 20       | 0.79%   |
| Gigabyte H410M         | 19       | 0.75%   |
| Gigabyte H81M-S2V      | 18       | 0.71%   |
| ECS H61H2-M13          | 16       | 0.63%   |
| Lenovo ThinkStation    | 14       | 0.55%   |
| Gigabyte B550          | 14       | 0.55%   |
| Gigabyte X570          | 13       | 0.51%   |
| ASRock B450M           | 13       | 0.51%   |
| Dell XPS               | 12       | 0.47%   |
| AZW U59                | 12       | 0.47%   |
| AZW MINI               | 12       | 0.47%   |
| ASUS P5G41T-M          | 12       | 0.47%   |
| HP ProDesk             | 11       | 0.43%   |
| Gigabyte GA-78LMT-USB3 | 11       | 0.43%   |
| Dell Inspiron          | 11       | 0.43%   |
| ASUS P8H67-M           | 11       | 0.43%   |
| ASUS M5A97             | 11       | 0.43%   |
| ASRock B450            | 11       | 0.43%   |
| Dell Vostro            | 10       | 0.39%   |
| ASUS H110M-R           | 10       | 0.39%   |
| Acer Aspire            | 10       | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 264      | 10.39%  |
| 2012    | 251      | 9.87%   |
| 2021    | 225      | 8.85%   |
| 2018    | 221      | 8.69%   |
| 2013    | 212      | 8.34%   |
| 2011    | 159      | 6.25%   |
| 2019    | 152      | 5.98%   |
| 2014    | 144      | 5.66%   |
| 2009    | 124      | 4.88%   |
| 2015    | 120      | 4.72%   |
| 2022    | 118      | 4.64%   |
| 2017    | 117      | 4.6%    |
| 2010    | 111      | 4.37%   |
| 2016    | 98       | 3.86%   |
| 2008    | 87       | 3.42%   |
| 2007    | 62       | 2.44%   |
| 2006    | 24       | 0.94%   |
| 2005    | 18       | 0.71%   |
| 2023    | 15       | 0.59%   |
| 2003    | 6        | 0.24%   |
| 2004    | 5        | 0.2%    |
| 2001    | 3        | 0.12%   |
| Unknown | 3        | 0.12%   |
| 2024    | 2        | 0.08%   |
| 2000    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2542     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2504     | 98.27%  |
| Enabled  | 44       | 1.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2529     | 99.49%  |
| Yes  | 13       | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 501      | 19.49%  |
| 4.01-8.0        | 476      | 18.51%  |
| 3.01-4.0        | 405      | 15.75%  |
| 8.01-16.0       | 359      | 13.96%  |
| 32.01-64.0      | 336      | 13.07%  |
| 64.01-256.0     | 230      | 8.95%   |
| 1.01-2.0        | 122      | 4.75%   |
| 24.01-32.0      | 61       | 2.37%   |
| 2.01-3.0        | 46       | 1.79%   |
| 0.51-1.0        | 17       | 0.66%   |
| More than 256.0 | 10       | 0.39%   |
| 0.01-0.5        | 8        | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 770      | 28.54%  |
| 1.01-2.0        | 531      | 19.68%  |
| 2.01-3.0        | 388      | 14.38%  |
| 4.01-8.0        | 346      | 12.82%  |
| 3.01-4.0        | 247      | 9.15%   |
| 8.01-16.0       | 148      | 5.49%   |
| 0.01-0.5        | 115      | 4.26%   |
| 16.01-24.0      | 62       | 2.3%    |
| 32.01-64.0      | 45       | 1.67%   |
| 24.01-32.0      | 30       | 1.11%   |
| 64.01-256.0     | 15       | 0.56%   |
| More than 256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1274     | 48.85%  |
| 2      | 535      | 20.51%  |
| 3      | 304      | 11.66%  |
| 4      | 208      | 7.98%   |
| 5      | 100      | 3.83%   |
| 6      | 63       | 2.42%   |
| 7      | 36       | 1.38%   |
| 8      | 26       | 1%      |
| 0      | 15       | 0.58%   |
| 9      | 14       | 0.54%   |
| 10     | 8        | 0.31%   |
| 13     | 5        | 0.19%   |
| 12     | 5        | 0.19%   |
| 11     | 5        | 0.19%   |
| 19     | 2        | 0.08%   |
| 29     | 1        | 0.04%   |
| 28     | 1        | 0.04%   |
| 27     | 1        | 0.04%   |
| 22     | 1        | 0.04%   |
| 21     | 1        | 0.04%   |
| 18     | 1        | 0.04%   |
| 16     | 1        | 0.04%   |
| 14     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1715     | 67.12%  |
| Yes       | 840      | 32.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2527     | 99.41%  |
| No        | 15       | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1786     | 69.9%   |
| Yes       | 769      | 30.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1950     | 76.32%  |
| Yes       | 605      | 23.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 706      | 27.74%  |
| USA          | 385      | 15.13%  |
| Germany      | 238      | 9.35%   |
| France       | 162      | 6.37%   |
| Spain        | 101      | 3.97%   |
| Brazil       | 78       | 3.06%   |
| UK           | 73       | 2.87%   |
| Italy        | 70       | 2.75%   |
| Canada       | 62       | 2.44%   |
| Australia    | 49       | 1.93%   |
| Poland       | 45       | 1.77%   |
| Netherlands  | 37       | 1.45%   |
| Argentina    | 28       | 1.1%    |
| Mexico       | 26       | 1.02%   |
| Belgium      | 24       | 0.94%   |
| Austria      | 24       | 0.94%   |
| Ukraine      | 22       | 0.86%   |
| China        | 22       | 0.86%   |
| Hungary      | 20       | 0.79%   |
| Switzerland  | 19       | 0.75%   |
| Czechia      | 17       | 0.67%   |
| Bulgaria     | 17       | 0.67%   |
| Sweden       | 15       | 0.59%   |
| Norway       | 15       | 0.59%   |
| Malaysia     | 15       | 0.59%   |
| Japan        | 15       | 0.59%   |
| Venezuela    | 14       | 0.55%   |
| Portugal     | 14       | 0.55%   |
| Finland      | 14       | 0.55%   |
| Romania      | 13       | 0.51%   |
| India        | 12       | 0.47%   |
| Taiwan       | 10       | 0.39%   |
| Hong Kong    | 10       | 0.39%   |
| Ireland      | 9        | 0.35%   |
| Denmark      | 9        | 0.35%   |
| Turkey       | 8        | 0.31%   |
| South Africa | 7        | 0.28%   |
| New Zealand  | 7        | 0.28%   |
| Greece       | 7        | 0.28%   |
| Croatia      | 7        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Voronezh       | 571      | 21.92%  |
| Moscow         | 35       | 1.34%   |
| St Petersburg  | 20       | 0.77%   |
| Vienna         | 19       | 0.73%   |
| Paris          | 18       | 0.69%   |
| Falkenstein    | 18       | 0.69%   |
| Seville        | 16       | 0.61%   |
| Barcelona      | 14       | 0.54%   |
| Bangor         | 14       | 0.54%   |
| Sao Paulo      | 13       | 0.5%    |
| Kuala Lumpur   | 12       | 0.46%   |
| Berlin         | 12       | 0.46%   |
| Melbourne      | 11       | 0.42%   |
| Munich         | 10       | 0.38%   |
| Dover-Foxcroft | 10       | 0.38%   |
| Buenos Aires   | 10       | 0.38%   |
| Toronto        | 9        | 0.35%   |
| Sydney         | 9        | 0.35%   |
| Chicago        | 9        | 0.35%   |
| Brisbane       | 9        | 0.35%   |
| Warsaw         | 8        | 0.31%   |
| Sofia          | 8        | 0.31%   |
| Milan          | 8        | 0.31%   |
| Madrid         | 8        | 0.31%   |
| Zurich         | 7        | 0.27%   |
| Yekaterinburg  | 7        | 0.27%   |
| Valencia       | 7        | 0.27%   |
| Stuttgart      | 7        | 0.27%   |
| Siegsdorf      | 7        | 0.27%   |
| Nuremberg      | 7        | 0.27%   |
| London         | 7        | 0.27%   |
| Kyiv           | 7        | 0.27%   |
| Central        | 7        | 0.27%   |
| Stockholm      | 6        | 0.23%   |
| San José      | 6        | 0.23%   |
| Rio de Janeiro | 6        | 0.23%   |
| Ocala          | 6        | 0.23%   |
| New York       | 6        | 0.23%   |
| Leipzig        | 6        | 0.23%   |
| Las Vegas      | 6        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 765      | 1414   | 17.65%  |
| WDC                       | 755      | 1329   | 17.42%  |
| Samsung Electronics       | 612      | 962    | 14.12%  |
| Kingston                  | 322      | 418    | 7.43%   |
| Toshiba                   | 302      | 555    | 6.97%   |
| Crucial                   | 252      | 322    | 5.81%   |
| Hitachi                   | 152      | 214    | 3.51%   |
| SanDisk                   | 150      | 195    | 3.46%   |
| Intel                     | 83       | 114    | 1.91%   |
| China                     | 75       | 88     | 1.73%   |
| HGST                      | 72       | 125    | 1.66%   |
| A-DATA Technology         | 63       | 83     | 1.45%   |
| SPCC                      | 41       | 47     | 0.95%   |
| Unknown                   | 40       | 63     | 0.92%   |
| PNY                       | 40       | 79     | 0.92%   |
| Corsair                   | 28       | 44     | 0.65%   |
| Transcend                 | 26       | 27     | 0.6%    |
| Phison                    | 26       | 33     | 0.6%    |
| Netac                     | 26       | 85     | 0.6%    |
| Micron Technology         | 25       | 31     | 0.58%   |
| Maxtor                    | 23       | 25     | 0.53%   |
| Patriot                   | 22       | 29     | 0.51%   |
| SK hynix                  | 21       | 40     | 0.48%   |
| Intenso                   | 21       | 28     | 0.48%   |
| Hewlett-Packard           | 21       | 36     | 0.48%   |
| OCZ                       | 20       | 24     | 0.46%   |
| Unknown                   | 20       | 21     | 0.46%   |
| Gigabyte Technology       | 18       | 19     | 0.42%   |
| GOODRAM                   | 14       | 30     | 0.32%   |
| JMicron Technology        | 11       | 11     | 0.25%   |
| Apacer                    | 11       | 11     | 0.25%   |
| Team                      | 10       | 16     | 0.23%   |
| XPG                       | 8        | 9      | 0.18%   |
| Silicon Motion            | 8        | 11     | 0.18%   |
| Micron/Crucial Technology | 8        | 9      | 0.18%   |
| LITEON                    | 8        | 11     | 0.18%   |
| Mushkin                   | 7        | 9      | 0.16%   |
| KIOXIA                    | 7        | 9      | 0.16%   |
| Hajaan                    | 7        | 9      | 0.16%   |
| Plextor                   | 6        | 9      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 83       | 1.63%   |
| Kingston SA400S37240G 240GB SSD  | 83       | 1.63%   |
| Crucial CT480BX500SSD1 480GB     | 68       | 1.33%   |
| Toshiba DT01ACA050 500GB         | 62       | 1.22%   |
| Seagate ST1000DM010-2EP102 1TB   | 55       | 1.08%   |
| Kingston SV300S37A120G 120GB SSD | 45       | 0.88%   |
| Kingston SA400S37480G 480GB SSD  | 45       | 0.88%   |
| Samsung SSD 860 EVO 250GB        | 42       | 0.82%   |
| Toshiba DT01ACA100 1TB           | 38       | 0.74%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 36       | 0.71%   |
| Samsung SSD 860 EVO 500GB        | 35       | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB   | 34       | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB         | 33       | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB   | 33       | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB     | 33       | 0.65%   |
| Samsung SSD 860 EVO 1TB          | 33       | 0.65%   |
| Hitachi HDS721050CLA362 500GB    | 32       | 0.63%   |
| Toshiba HDWD110 1TB              | 31       | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB   | 31       | 0.61%   |
| Crucial CT500MX500SSD1 500GB     | 30       | 0.59%   |
| Samsung SSD 850 EVO 250GB        | 28       | 0.55%   |
| Crucial CT240BX500SSD1 240GB     | 28       | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB   | 26       | 0.51%   |
| Crucial CT1000MX500SSD1 1TB      | 26       | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB   | 25       | 0.49%   |
| Samsung SSD 870 EVO 500GB        | 24       | 0.47%   |
| Kingston SA400S37120G 120GB SSD  | 24       | 0.47%   |
| Samsung SSD 850 EVO 500GB        | 23       | 0.45%   |
| Toshiba DT01ACA200 2TB           | 20       | 0.39%   |
| Seagate ST3250318AS 250GB        | 20       | 0.39%   |
| Samsung SSD 980 PRO 1TB          | 20       | 0.39%   |
| Netac SSD 240GB                  | 20       | 0.39%   |
| Unknown                          | 20       | 0.39%   |
| SanDisk NVMe SSD Drive 1TB       | 19       | 0.37%   |
| Seagate ST3500418AS 500GB        | 18       | 0.35%   |
| Seagate ST1000DM003-1SB102 1TB   | 18       | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB         | 17       | 0.33%   |
| Seagate ST250DM000-1BD141 250GB  | 17       | 0.33%   |
| Samsung SSD 980 1TB              | 17       | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB   | 16       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 749      | 1365   | 36.36%  |
| WDC                 | 653      | 1160   | 31.7%   |
| Toshiba             | 280      | 517    | 13.59%  |
| Hitachi             | 152      | 214    | 7.38%   |
| Samsung Electronics | 74       | 92     | 3.59%   |
| HGST                | 71       | 124    | 3.45%   |
| Maxtor              | 22       | 24     | 1.07%   |
| Unknown             | 10       | 15     | 0.49%   |
| Hewlett-Packard     | 6        | 15     | 0.29%   |
| SABRENT             | 5        | 5      | 0.24%   |
| External            | 4        | 5      | 0.19%   |
| Intenso             | 3        | 3      | 0.15%   |
| Fujitsu             | 3        | 4      | 0.15%   |
| QNAP                | 2        | 3      | 0.1%    |
| HPE                 | 2        | 6      | 0.1%    |
| Apple               | 2        | 2      | 0.1%    |
| WD MediaMax         | 1        | 6      | 0.05%   |
| Synology            | 1        | 1      | 0.05%   |
| StoreJet            | 1        | 1      | 0.05%   |
| SSK                 | 1        | 1      | 0.05%   |
| SD                  | 1        | 1      | 0.05%   |
| RSH-319             | 1        | 1      | 0.05%   |
| pqi                 | 1        | 1      | 0.05%   |
| NAS                 | 1        | 5      | 0.05%   |
| MaxDigital          | 1        | 4      | 0.05%   |
| MARSHAL             | 1        | 1      | 0.05%   |
| Inateck             | 1        | 1      | 0.05%   |
| IBM/Hitachi         | 1        | 1      | 0.05%   |
| IBM                 | 1        | 1      | 0.05%   |
| Hajaan              | 1        | 1      | 0.05%   |
| H/W                 | 1        | 3      | 0.05%   |
| China               | 1        | 1      | 0.05%   |
| ASMT                | 1        | 1      | 0.05%   |
| ASMedia             | 1        | 1      | 0.05%   |
| AMP                 | 1        | 1      | 0.05%   |
| Advantech           | 1        | 1      | 0.05%   |
| 3ware               | 1        | 4      | 0.05%   |
| 128MB               | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 346      | 509    | 21.03%  |
| Kingston            | 291      | 370    | 17.69%  |
| Crucial             | 226      | 283    | 13.74%  |
| SanDisk             | 98       | 125    | 5.96%   |
| WDC                 | 89       | 98     | 5.41%   |
| China               | 73       | 86     | 4.44%   |
| A-DATA Technology   | 47       | 56     | 2.86%   |
| Intel               | 45       | 60     | 2.74%   |
| SPCC                | 36       | 40     | 2.19%   |
| PNY                 | 28       | 64     | 1.7%    |
| Netac               | 25       | 84     | 1.52%   |
| Transcend           | 24       | 25     | 1.46%   |
| OCZ                 | 20       | 24     | 1.22%   |
| Toshiba             | 19       | 23     | 1.16%   |
| Patriot             | 17       | 20     | 1.03%   |
| Micron Technology   | 16       | 18     | 0.97%   |
| Intenso             | 16       | 21     | 0.97%   |
| GOODRAM             | 12       | 19     | 0.73%   |
| Gigabyte Technology | 11       | 11     | 0.67%   |
| Hewlett-Packard     | 10       | 14     | 0.61%   |
| Corsair             | 10       | 14     | 0.61%   |
| Apacer              | 10       | 10     | 0.61%   |
| Team                | 9        | 12     | 0.55%   |
| Unknown             | 9        | 10     | 0.55%   |
| LITEON              | 7        | 10     | 0.43%   |
| Hajaan              | 7        | 8      | 0.43%   |
| Seagate             | 6        | 7      | 0.36%   |
| NGFF                | 6        | 6      | 0.36%   |
| Mushkin             | 6        | 7      | 0.36%   |
| JMicron Technology  | 6        | 6      | 0.36%   |
| Xinhaike            | 5        | 8      | 0.3%    |
| SK hynix            | 5        | 6      | 0.3%    |
| LITEONIT            | 5        | 9      | 0.3%    |
| Unknown             | 4        | 7      | 0.24%   |
| Plextor             | 4        | 7      | 0.24%   |
| Innodisk            | 4        | 4      | 0.24%   |
| Foxline             | 4        | 4      | 0.24%   |
| Drevo               | 4        | 4      | 0.24%   |
| T-FORCE             | 3        | 4      | 0.18%   |
| Supermicro          | 3        | 4      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1610     | 3593   | 43.81%  |
| SSD     | 1372     | 2186   | 37.33%  |
| NVMe    | 618      | 956    | 16.82%  |
| Unknown | 51       | 102    | 1.39%   |
| MMC     | 24       | 26     | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2289     | 5513   | 74.34%  |
| NVMe | 615      | 950    | 19.97%  |
| SAS  | 151      | 374    | 4.9%    |
| MMC  | 24       | 26     | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1770     | 2810   | 53.15%  |
| 0.51-1.0   | 756      | 1249   | 22.7%   |
| 1.01-2.0   | 345      | 602    | 10.36%  |
| 3.01-4.0   | 175      | 363    | 5.26%   |
| 4.01-10.0  | 145      | 374    | 4.35%   |
| 2.01-3.0   | 94       | 195    | 2.82%   |
| 10.01-20.0 | 44       | 185    | 1.32%   |
| 20.01-50.0 | 1        | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 697      | 26.78%  |
| 101-250        | 393      | 15.1%   |
| 251-500        | 328      | 12.6%   |
| 501-1000       | 317      | 12.18%  |
| More than 3000 | 270      | 10.37%  |
| 1001-2000      | 183      | 7.03%   |
| 51-100         | 138      | 5.3%    |
| 1-20           | 99       | 3.8%    |
| 2001-3000      | 96       | 3.69%   |
| 21-50          | 82       | 3.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 707      | 26.69%  |
| Unknown        | 697      | 26.31%  |
| 101-250        | 238      | 8.98%   |
| 21-50          | 201      | 7.59%   |
| 51-100         | 190      | 7.17%   |
| 251-500        | 168      | 6.34%   |
| 501-1000       | 149      | 5.62%   |
| More than 3000 | 124      | 4.68%   |
| 1001-2000      | 109      | 4.11%   |
| 2001-3000      | 58       | 2.19%   |
| 0              | 8        | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 21       | 36     | 3.47%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 20       | 24     | 3.31%   |
| Kingston SV300S37A120G 120GB SSD    | 17       | 17     | 2.81%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 8        | 8      | 1.32%   |
| Hitachi HDS721050CLA362 500GB       | 8        | 8      | 1.32%   |
| Seagate ST3500418AS 500GB           | 7        | 9      | 1.16%   |
| Seagate ST3250318AS 250GB           | 7        | 7      | 1.16%   |
| Seagate ST250DM000-1BD141 250GB     | 7        | 7      | 1.16%   |
| Toshiba DT01ACA050 500GB            | 6        | 7      | 0.99%   |
| Seagate ST31000528AS 1TB            | 6        | 7      | 0.99%   |
| Seagate ST1000DM003-9YN162 1TB      | 6        | 7      | 0.99%   |
| Hitachi HDS721050DLE630 500GB       | 6        | 11     | 0.99%   |
| WDC WD20EARX-00PASB0 2TB            | 5        | 5      | 0.83%   |
| WDC WD20EARS-00MVWB0 2TB            | 5        | 5      | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5        | 5      | 0.83%   |
| Seagate ST3320613AS 320GB           | 5        | 5      | 0.83%   |
| Seagate ST31500341AS 1TB            | 5        | 7      | 0.83%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4        | 4      | 0.66%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4        | 5      | 0.66%   |
| Seagate ST3500413AS 500GB           | 4        | 5      | 0.66%   |
| Seagate ST2000DL003-9VT166 2TB      | 4        | 4      | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 4      | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB         | 3        | 3      | 0.5%    |
| WDC WD3200AAJS-08L7A0 320GB         | 3        | 3      | 0.5%    |
| WDC WD3200AAJS-00L7A0 320GB         | 3        | 3      | 0.5%    |
| WDC WD2500AAJS-00YZCA0 250GB        | 3        | 3      | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB             | 3        | 3      | 0.5%    |
| Toshiba MK2555GSXF 250GB            | 3        | 3      | 0.5%    |
| Toshiba DT01ACA100 1TB              | 3        | 4      | 0.5%    |
| Seagate ST3320620AS 320GB           | 3        | 5      | 0.5%    |
| Seagate ST3320418AS 320GB           | 3        | 5      | 0.5%    |
| Seagate ST3250310AS 250GB           | 3        | 3      | 0.5%    |
| Seagate ST3120827AS 120GB           | 3        | 4      | 0.5%    |
| Seagate ST3120811AS 120GB           | 3        | 3      | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB      | 3        | 4      | 0.5%    |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 3      | 0.5%    |
| Seagate ST2000DM001-1CH164 2TB      | 3        | 4      | 0.5%    |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 4      | 0.5%    |
| SanDisk SSD PLUS 120 GB             | 3        | 3      | 0.5%    |
| Samsung Electronics SSD 970 EVO 1TB | 3        | 4      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 178      | 249    | 30.8%   |
| WDC                 | 171      | 212    | 29.58%  |
| Hitachi             | 42       | 57     | 7.27%   |
| Samsung Electronics | 37       | 41     | 6.4%    |
| Toshiba             | 30       | 36     | 5.19%   |
| Kingston            | 30       | 35     | 5.19%   |
| Intel               | 18       | 22     | 3.11%   |
| A-DATA Technology   | 11       | 14     | 1.9%    |
| Maxtor              | 10       | 10     | 1.73%   |
| Crucial             | 8        | 13     | 1.38%   |
| SanDisk             | 7        | 7      | 1.21%   |
| HGST                | 6        | 6      | 1.04%   |
| SK hynix            | 3        | 6      | 0.52%   |
| China               | 3        | 3      | 0.52%   |
| Transcend           | 2        | 2      | 0.35%   |
| SPCC                | 2        | 2      | 0.35%   |
| OCZ                 | 2        | 2      | 0.35%   |
| Micron Technology   | 2        | 2      | 0.35%   |
| Hewlett-Packard     | 2        | 3      | 0.35%   |
| Corsair             | 2        | 2      | 0.35%   |
| Apacer              | 2        | 2      | 0.35%   |
| Western Digital     | 1        | 2      | 0.17%   |
| ShiJi               | 1        | 1      | 0.17%   |
| PNY                 | 1        | 1      | 0.17%   |
| Patriot             | 1        | 1      | 0.17%   |
| LITEONIT            | 1        | 1      | 0.17%   |
| KingDian            | 1        | 1      | 0.17%   |
| Intenso             | 1        | 1      | 0.17%   |
| IBM                 | 1        | 1      | 0.17%   |
| HANCHU              | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 2      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 178      | 249    | 39.38%  |
| WDC                 | 164      | 204    | 36.28%  |
| Hitachi             | 42       | 57     | 9.29%   |
| Toshiba             | 28       | 34     | 6.19%   |
| Samsung Electronics | 20       | 20     | 4.42%   |
| Maxtor              | 10       | 10     | 2.21%   |
| HGST                | 6        | 6      | 1.33%   |
| Hewlett-Packard     | 2        | 3      | 0.44%   |
| IBM                 | 1        | 1      | 0.22%   |
| Fujitsu             | 1        | 2      | 0.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 417      | 586    | 77.08%  |
| SSD  | 107      | 126    | 19.78%  |
| NVMe | 17       | 26     | 3.14%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB                  | 1        | 1      | 6.25%   |
| Seagate ST500DM005 HD502HJ 500GB            | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 2      | 6.25%   |
| Seagate ST3500830AS 500GB                   | 1        | 1      | 6.25%   |
| Seagate ST3500630A 500GB                    | 1        | 1      | 6.25%   |
| Seagate ST2000NM0011 2TB                    | 1        | 1      | 6.25%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 980 1TB             | 1        | 1      | 6.25%   |
| Samsung Electronics SP0802N 80GB            | 1        | 1      | 6.25%   |
| Samsung Electronics HD253GJ 250GB           | 1        | 1      | 6.25%   |
| Samsung Electronics HD103SJ 1TB             | 1        | 1      | 6.25%   |
| Intel SSDSC2KW256G8 256GB                   | 1        | 1      | 6.25%   |
| Inland SATA SSD 128GB                       | 1        | 1      | 6.25%   |
| HGST HUH728080ALN600 8TB                    | 1        | 1      | 6.25%   |
| HGST HDN724040ALE640 4TB                    | 1        | 1      | 6.25%   |
| Hewlett-Packard SSD S700 500GB              | 1        | 2      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 31.25%  |
| Samsung Electronics | 5        | 5      | 31.25%  |
| HGST                | 2        | 2      | 12.5%   |
| WDC                 | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| Inland              | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 2      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1932     | 4622   | 64.96%  |
| Malfunc  | 519      | 738    | 17.45%  |
| Detected | 506      | 1484   | 17.01%  |
| Failed   | 16       | 18     | 0.54%   |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1790     | 50.55%  |
| AMD                              | 664      | 18.75%  |
| Samsung Electronics              | 257      | 7.26%   |
| ASMedia Technology               | 125      | 3.53%   |
| SanDisk                          | 104      | 2.94%   |
| Phison Electronics               | 79       | 2.23%   |
| Marvell Technology Group         | 73       | 2.06%   |
| JMicron Technology               | 70       | 1.98%   |
| Nvidia                           | 55       | 1.55%   |
| Kingston Technology Company      | 42       | 1.19%   |
| Micron/Crucial Technology        | 38       | 1.07%   |
| LSI Logic / Symbios Logic        | 32       | 0.9%    |
| VIA Technologies                 | 31       | 0.88%   |
| Broadcom / LSI                   | 25       | 0.71%   |
| ADATA Technology                 | 22       | 0.62%   |
| Silicon Motion                   | 20       | 0.56%   |
| SK hynix                         | 15       | 0.42%   |
| Adaptec                          | 13       | 0.37%   |
| Toshiba America Info Systems     | 11       | 0.31%   |
| Micron Technology                | 10       | 0.28%   |
| MAXIO Technology (Hangzhou)      | 10       | 0.28%   |
| Silicon Image                    | 8        | 0.23%   |
| KIOXIA                           | 8        | 0.23%   |
| Realtek Semiconductor            | 7        | 0.2%    |
| Seagate Technology               | 5        | 0.14%   |
| Silicon Integrated Systems [SiS] | 4        | 0.11%   |
| Lite-On Technology               | 3        | 0.08%   |
| INNOGRIT                         | 3        | 0.08%   |
| Hewlett-Packard                  | 3        | 0.08%   |
| Shenzhen Longsys Electronics     | 2        | 0.06%   |
| Integrated Technology Express    | 2        | 0.06%   |
| Biwin Storage Technology         | 2        | 0.06%   |
| 3ware                            | 2        | 0.06%   |
| Swissbit                         | 1        | 0.03%   |
| Netac Technology                 | 1        | 0.03%   |
| Jiangsu Huacun Elec.             | 1        | 0.03%   |
| Innodisk                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Broadcom                         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 379      | 8.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 218      | 4.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 149      | 3.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 148      | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 147      | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 146      | 3.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 137      | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 134      | 3.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 104      | 2.37%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 102      | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                                  | 99       | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 89       | 2.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 82       | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 75       | 1.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 73       | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 66       | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 63       | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 63       | 1.44%   |
| Intel SATA Controller [RAID mode]                                                       | 60       | 1.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 58       | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 54       | 1.23%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 52       | 1.19%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 42       | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 41       | 0.94%   |
| AMD FCH SATA Controller D                                                               | 39       | 0.89%   |
| Phison E12 NVMe Controller                                                              | 38       | 0.87%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 37       | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 37       | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 35       | 0.8%    |
| Nvidia MCP61 SATA Controller                                                            | 31       | 0.71%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 31       | 0.71%   |
| AMD 300 Series Chipset SATA Controller                                                  | 30       | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 29       | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 28       | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 26       | 0.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 26       | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 25       | 0.57%   |
| Nvidia MCP61 IDE                                                                        | 25       | 0.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 25       | 0.57%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 24       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2054     | 58.54%  |
| NVMe | 616      | 17.55%  |
| IDE  | 604      | 17.21%  |
| RAID | 153      | 4.36%   |
| SAS  | 65       | 1.85%   |
| SCSI | 17       | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1808     | 71.13%  |
| AMD                   | 724      | 28.48%  |
| CentaurHauls          | 5        | 0.2%    |
| sifive,u74-mc         | 3        | 0.12%   |
| Marvell Semiconductor | 1        | 0.04%   |
| Unknown               | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 63       | 2.47%   |
| AMD Ryzen 5 3600 6-Core Processor           | 38       | 1.49%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 1.37%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 33       | 1.29%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 30       | 1.18%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 28       | 1.1%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 28       | 1.1%    |
| Intel Core i7-10700 CPU @ 2.90GHz           | 27       | 1.06%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 27       | 1.06%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 25       | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 25       | 0.98%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 24       | 0.94%   |
| Intel Celeron N5105 @ 2.00GHz               | 23       | 0.9%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 23       | 0.9%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 22       | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 21       | 0.82%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 21       | 0.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 21       | 0.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 21       | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 21       | 0.82%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 20       | 0.78%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 20       | 0.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 19       | 0.75%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 19       | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 18       | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 18       | 0.71%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 0.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 17       | 0.67%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 16       | 0.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 16       | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.63%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 16       | 0.63%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 16       | 0.63%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 16       | 0.63%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 15       | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 0.59%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 15       | 0.59%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 15       | 0.59%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 15       | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 425      | 16.7%   |
| Intel Core i3           | 241      | 9.47%   |
| Intel Core i7           | 227      | 8.92%   |
| Intel Pentium           | 168      | 6.6%    |
| AMD Ryzen 5             | 163      | 6.4%    |
| Intel Xeon              | 159      | 6.25%   |
| Intel Celeron           | 154      | 6.05%   |
| AMD Ryzen 7             | 125      | 4.91%   |
| Other                   | 112      | 4.4%    |
| Intel Core 2 Duo        | 104      | 4.09%   |
| AMD Ryzen 9             | 84       | 3.3%    |
| AMD FX                  | 70       | 2.75%   |
| Intel Pentium Dual-Core | 59       | 2.32%   |
| Intel Core 2 Quad       | 37       | 1.45%   |
| AMD Ryzen 3             | 37       | 1.45%   |
| Intel Atom              | 29       | 1.14%   |
| Intel Core i9           | 25       | 0.98%   |
| AMD Ryzen Threadripper  | 25       | 0.98%   |
| AMD Athlon              | 21       | 0.83%   |
| AMD A10                 | 21       | 0.83%   |
| Intel Pentium Gold      | 17       | 0.67%   |
| AMD Phenom II X4        | 17       | 0.67%   |
| AMD Athlon II X2        | 17       | 0.67%   |
| AMD Athlon 64 X2        | 17       | 0.67%   |
| Intel Pentium 4         | 15       | 0.59%   |
| Intel Core 2            | 13       | 0.51%   |
| AMD GX                  | 13       | 0.51%   |
| AMD Phenom II X6        | 11       | 0.43%   |
| AMD Ryzen 5 PRO         | 10       | 0.39%   |
| Intel Pentium Silver    | 9        | 0.35%   |
| Intel Pentium Dual      | 9        | 0.35%   |
| Intel Pentium D         | 8        | 0.31%   |
| AMD G                   | 8        | 0.31%   |
| AMD A8                  | 8        | 0.31%   |
| AMD A4                  | 8        | 0.31%   |
| AMD Sempron             | 7        | 0.28%   |
| AMD Athlon II X4        | 6        | 0.24%   |
| AMD A6                  | 6        | 0.24%   |
| Intel Genuine           | 5        | 0.2%    |
| AMD Opteron             | 5        | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 847      | 33.27%  |
| 2       | 778      | 30.56%  |
| 6       | 378      | 14.85%  |
| 8       | 234      | 9.19%   |
| 1       | 77       | 3.02%   |
| 16      | 75       | 2.95%   |
| 12      | 68       | 2.67%   |
| 3       | 28       | 1.1%    |
| 10      | 20       | 0.79%   |
| 24      | 12       | 0.47%   |
| 32      | 11       | 0.43%   |
| 18      | 4        | 0.16%   |
| Unknown | 4        | 0.16%   |
| 14      | 3        | 0.12%   |
| 44      | 2        | 0.08%   |
| 20      | 2        | 0.08%   |
| 64      | 1        | 0.04%   |
| 36      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2493     | 98.03%  |
| 2       | 45       | 1.77%   |
| Unknown | 4        | 0.16%   |
| 0       | 1        | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1323     | 51.98%  |
| 1       | 1218     | 47.86%  |
| Unknown | 4        | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2508     | 98.62%  |
| 32-bit         | 29       | 1.14%   |
| Unknown        | 6        | 0.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 436      | 16.79%  |
| 0x306c3    | 229      | 8.82%   |
| 0x206a7    | 143      | 5.51%   |
| 0x1067a    | 137      | 5.28%   |
| 0x306a9    | 136      | 5.24%   |
| 0x506e3    | 112      | 4.31%   |
| 0x906ea    | 109      | 4.2%    |
| 0xa0653    | 73       | 2.81%   |
| 0x08701021 | 70       | 2.7%    |
| 0x906e9    | 51       | 1.96%   |
| 0x906c0    | 43       | 1.66%   |
| 0x0a201016 | 42       | 1.62%   |
| 0xa0655    | 39       | 1.5%    |
| 0xa0671    | 37       | 1.42%   |
| 0x08108109 | 37       | 1.42%   |
| 0x0800820d | 35       | 1.35%   |
| 0x90672    | 28       | 1.08%   |
| 0x010000c8 | 24       | 0.92%   |
| 0x6fd      | 23       | 0.89%   |
| 0x906ed    | 21       | 0.81%   |
| 0x306f2    | 21       | 0.81%   |
| 0x08101016 | 20       | 0.77%   |
| 0x906eb    | 19       | 0.73%   |
| 0x6fb      | 19       | 0.73%   |
| 0x0a50000c | 19       | 0.73%   |
| 0x0a50000d | 18       | 0.69%   |
| 0x06003106 | 18       | 0.69%   |
| 0x306e4    | 17       | 0.65%   |
| 0x206d7    | 17       | 0.65%   |
| 0x06000852 | 17       | 0.65%   |
| 0x0a201009 | 16       | 0.62%   |
| 0x90675    | 15       | 0.58%   |
| 0x706a8    | 15       | 0.58%   |
| 0x206c2    | 15       | 0.58%   |
| 0x10676    | 15       | 0.58%   |
| 0x0a20120a | 15       | 0.58%   |
| 0x08600106 | 15       | 0.58%   |
| 0x06000822 | 15       | 0.58%   |
| 0x506c9    | 14       | 0.54%   |
| 0x20655    | 14       | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 307      | 12.04%  |
| KabyLake         | 251      | 9.84%   |
| SandyBridge      | 186      | 7.29%   |
| IvyBridge        | 175      | 6.86%   |
| Penryn           | 174      | 6.82%   |
| Zen 3            | 149      | 5.84%   |
| Skylake          | 142      | 5.57%   |
| Zen 2            | 138      | 5.41%   |
| CometLake        | 130      | 5.1%    |
| Zen+             | 101      | 3.96%   |
| Unknown          | 94       | 3.69%   |
| Core             | 73       | 2.86%   |
| Piledriver       | 69       | 2.71%   |
| K10              | 69       | 2.71%   |
| Zen              | 65       | 2.55%   |
| Tremont          | 50       | 1.96%   |
| Westmere         | 43       | 1.69%   |
| Silvermont       | 33       | 1.29%   |
| NetBurst         | 30       | 1.18%   |
| K8 Hammer        | 29       | 1.14%   |
| Nehalem          | 28       | 1.1%    |
| Goldmont plus    | 26       | 1.02%   |
| Alderlake Hybrid | 24       | 0.94%   |
| Steamroller      | 22       | 0.86%   |
| Goldmont         | 20       | 0.78%   |
| Bonnell          | 19       | 0.75%   |
| Bulldozer        | 18       | 0.71%   |
| Broadwell        | 13       | 0.51%   |
| Icelake          | 12       | 0.47%   |
| Bobcat           | 12       | 0.47%   |
| Jaguar           | 11       | 0.43%   |
| Excavator        | 11       | 0.43%   |
| Puma             | 8        | 0.31%   |
| P6               | 5        | 0.2%    |
| TigerLake        | 4        | 0.16%   |
| K6               | 4        | 0.16%   |
| K10 Llano        | 2        | 0.08%   |
| Gracemont        | 2        | 0.08%   |
| Geode            | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1157     | 43.04%  |
| Nvidia                           | 836      | 31.1%   |
| AMD                              | 600      | 22.32%  |
| ASPEED Technology                | 58       | 2.16%   |
| Matrox Electronics Systems       | 26       | 0.97%   |
| VIA Technologies                 | 7        | 0.26%   |
| Silicon Integrated Systems [SiS] | 3        | 0.11%   |
| ATI Technologies                 | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 162      | 5.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 120      | 4.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 96       | 3.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 80       | 2.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 78       | 2.85%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 68       | 2.48%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 62       | 2.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 62       | 2.26%   |
| ASPEED Technology ASPEED Graphics Family                                    | 58       | 2.12%   |
| Intel HD Graphics 530                                                       | 54       | 1.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 53       | 1.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 49       | 1.79%   |
| Intel JasperLake [UHD Graphics]                                             | 45       | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 41       | 1.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 40       | 1.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 39       | 1.42%   |
| Nvidia GF108 [GeForce GT 730]                                               | 38       | 1.39%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 35       | 1.28%   |
| Intel HD Graphics 630                                                       | 35       | 1.28%   |
| Intel HD Graphics 510                                                       | 30       | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 29       | 1.06%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 28       | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 25       | 0.91%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 25       | 0.91%   |
| Nvidia GF108 [GeForce GT 630]                                               | 25       | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 23       | 0.84%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23       | 0.84%   |
| Nvidia GT218 [GeForce 210]                                                  | 21       | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 21       | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 20       | 0.73%   |
| Intel AlderLake-S GT1                                                       | 20       | 0.73%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 18       | 0.66%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 18       | 0.66%   |
| Intel HD Graphics 500                                                       | 16       | 0.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 16       | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 16       | 0.58%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 16       | 0.58%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 16       | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 14       | 0.51%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 14       | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1050     | 40.98%  |
| 1 x Nvidia                        | 750      | 29.27%  |
| 1 x AMD                           | 540      | 21.08%  |
| 1 x ASPEED                        | 42       | 1.64%   |
| Intel + Nvidia                    | 41       | 1.6%    |
| 1 x Matrox                        | 25       | 0.98%   |
| 2 x AMD                           | 22       | 0.86%   |
| AMD + Nvidia                      | 22       | 0.86%   |
| Other                             | 21       | 0.82%   |
| Nvidia + ASPEED                   | 9        | 0.35%   |
| Intel + AMD                       | 9        | 0.35%   |
| 2 x Nvidia                        | 8        | 0.31%   |
| 1 x VIA                           | 7        | 0.27%   |
| AMD + ASPEED                      | 5        | 0.2%    |
| 1 x SiS                           | 3        | 0.12%   |
| Intel + 2 x Nvidia                | 3        | 0.12%   |
| 3 x AMD                           | 1        | 0.04%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.04%   |
| 2 x Intel                         | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.04%   |
| AMD + Matrox                      | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1345     | 52.46%  |
| Unknown     | 872      | 34.01%  |
| Proprietary | 347      | 13.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1716     | 66.59%  |
| 1.01-2.0   | 208      | 8.07%   |
| 0.01-0.5   | 151      | 5.86%   |
| 3.01-4.0   | 132      | 5.12%   |
| 0.51-1.0   | 130      | 5.04%   |
| 7.01-8.0   | 114      | 4.42%   |
| 5.01-6.0   | 58       | 2.25%   |
| 8.01-16.0  | 35       | 1.36%   |
| 2.01-3.0   | 19       | 0.74%   |
| 16.01-24.0 | 7        | 0.27%   |
| 4.01-5.0   | 5        | 0.19%   |
| 32.01-64.0 | 1        | 0.04%   |
| 24.01-32.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 265      | 15.02%  |
| Dell                    | 203      | 11.51%  |
| Goldstar                | 175      | 9.92%   |
| Acer                    | 116      | 6.58%   |
| Hewlett-Packard         | 110      | 6.24%   |
| BenQ                    | 97       | 5.5%    |
| AOC                     | 87       | 4.93%   |
| Ancor Communications    | 79       | 4.48%   |
| Philips                 | 75       | 4.25%   |
| Unknown                 | 46       | 2.61%   |
| Iiyama                  | 40       | 2.27%   |
| ViewSonic               | 39       | 2.21%   |
| ASUSTek Computer        | 34       | 1.93%   |
| Eizo                    | 28       | 1.59%   |
| Lenovo                  | 25       | 1.42%   |
| LG Electronics          | 22       | 1.25%   |
| Sony                    | 21       | 1.19%   |
| NEC Computers           | 18       | 1.02%   |
| Unknown                 | 15       | 0.85%   |
| Vestel Elektronik       | 10       | 0.57%   |
| Vizio                   | 9        | 0.51%   |
| MSI                     | 9        | 0.51%   |
| Medion                  | 9        | 0.51%   |
| Fujitsu Siemens         | 7        | 0.4%    |
| Belinea                 | 6        | 0.34%   |
| Toshiba                 | 5        | 0.28%   |
| Panasonic               | 5        | 0.28%   |
| Idek Iiyama             | 5        | 0.28%   |
| HPN                     | 5        | 0.28%   |
| HannStar                | 5        | 0.28%   |
| Sceptre Tech            | 4        | 0.23%   |
| Plain Tree Systems      | 4        | 0.23%   |
| Packard Bell            | 4        | 0.23%   |
| Microstep               | 4        | 0.23%   |
| Lenovo Group Limited    | 4        | 0.23%   |
| HKC                     | 4        | 0.23%   |
| Hitachi                 | 4        | 0.23%   |
| Chi Mei Optoelectronics | 4        | 0.23%   |
| AGO                     | 4        | 0.23%   |
| Xiaomi                  | 3        | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 33       | 1.77%   |
| Unknown                                                                | 15       | 0.81%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 11       | 0.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 10       | 0.54%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 9        | 0.48%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 8        | 0.43%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 7        | 0.38%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 7        | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 6        | 0.32%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                      | 6        | 0.32%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                         | 6        | 0.32%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 5        | 0.27%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 5        | 0.27%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 5        | 0.27%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                      | 5        | 0.27%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                       | 5        | 0.27%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 5        | 0.27%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 5        | 0.27%   |
| Ancor Communications VE228 ACI22FA 1920x1080 480x270mm 21.7-inch       | 5        | 0.27%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 5        | 0.27%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 4        | 0.21%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch   | 4        | 0.21%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 4        | 0.21%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 4        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 4        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 4        | 0.21%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                | 4        | 0.21%   |
| Hewlett-Packard E201 HWP305F 1600x900 440x250mm 19.9-inch              | 4        | 0.21%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 4        | 0.21%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 4        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 4        | 0.21%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 4        | 0.21%   |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                      | 4        | 0.21%   |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                      | 4        | 0.21%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                     | 4        | 0.21%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 4        | 0.21%   |
| AOC 2475W AOC2475 1920x1080 527x296mm 23.8-inch                        | 4        | 0.21%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch       | 4        | 0.21%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch  | 4        | 0.21%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                      | 4        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 748      | 43.04%  |
| 3840x2160 (4K)     | 167      | 9.61%   |
| 1280x1024 (SXGA)   | 149      | 8.57%   |
| 2560x1440 (QHD)    | 122      | 7.02%   |
| 1680x1050 (WSXGA+) | 80       | 4.6%    |
| Unknown            | 61       | 3.51%   |
| 1366x768 (WXGA)    | 56       | 3.22%   |
| 1920x1200 (WUXGA)  | 45       | 2.59%   |
| 1600x900 (HD+)     | 44       | 2.53%   |
| 1440x900 (WXGA+)   | 38       | 2.19%   |
| 2288x1287          | 35       | 2.01%   |
| 3440x1440          | 25       | 1.44%   |
| 2560x1080          | 24       | 1.38%   |
| 1360x768           | 22       | 1.27%   |
| 1024x768 (XGA)     | 22       | 1.27%   |
| 3840x1080          | 19       | 1.09%   |
| 1600x1200          | 17       | 0.98%   |
| 1920x540           | 6        | 0.35%   |
| 4480x1440          | 5        | 0.29%   |
| 5760x1080          | 4        | 0.23%   |
| 3200x1080          | 4        | 0.23%   |
| 2560x1600          | 3        | 0.17%   |
| 1400x1050          | 3        | 0.17%   |
| 5760x2160          | 2        | 0.12%   |
| 5360x1440          | 2        | 0.12%   |
| 5120x1440          | 2        | 0.12%   |
| 3840x1200          | 2        | 0.12%   |
| 3360x1050          | 2        | 0.12%   |
| 2048x1152          | 2        | 0.12%   |
| 1280x800 (WXGA)    | 2        | 0.12%   |
| 1280x720 (HD)      | 2        | 0.12%   |
| 7680x4320          | 1        | 0.06%   |
| 6400x2160          | 1        | 0.06%   |
| 6160x1440          | 1        | 0.06%   |
| 5120x2160          | 1        | 0.06%   |
| 5120x1080          | 1        | 0.06%   |
| 4480x1600          | 1        | 0.06%   |
| 3840x2560          | 1        | 0.06%   |
| 3840x1600          | 1        | 0.06%   |
| 3600x1080          | 1        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 249      | 14.5%   |
| 27      | 226      | 13.16%  |
| 23      | 211      | 12.29%  |
| 21      | 165      | 9.61%   |
| Unknown | 161      | 9.38%   |
| 19      | 106      | 6.17%   |
| 17      | 76       | 4.43%   |
| 18      | 71       | 4.14%   |
| 31      | 63       | 3.67%   |
| 22      | 57       | 3.32%   |
| 20      | 53       | 3.09%   |
| 15      | 41       | 2.39%   |
| 34      | 35       | 2.04%   |
| 142     | 33       | 1.92%   |
| 84      | 24       | 1.4%    |
| 72      | 15       | 0.87%   |
| 32      | 15       | 0.87%   |
| 54      | 12       | 0.7%    |
| 25      | 11       | 0.64%   |
| 28      | 10       | 0.58%   |
| 40      | 8        | 0.47%   |
| 26      | 7        | 0.41%   |
| 13      | 7        | 0.41%   |
| 52      | 6        | 0.35%   |
| 48      | 5        | 0.29%   |
| 65      | 4        | 0.23%   |
| 42      | 4        | 0.23%   |
| 35      | 4        | 0.23%   |
| 33      | 4        | 0.23%   |
| 29      | 4        | 0.23%   |
| 39      | 3        | 0.17%   |
| 12      | 3        | 0.17%   |
| 75      | 2        | 0.12%   |
| 60      | 2        | 0.12%   |
| 43      | 2        | 0.12%   |
| 36      | 2        | 0.12%   |
| 16      | 2        | 0.12%   |
| 99      | 1        | 0.06%   |
| 85      | 1        | 0.06%   |
| 74      | 1        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 624      | 37.57%  |
| 401-500        | 376      | 22.64%  |
| Unknown        | 161      | 9.69%   |
| 301-350        | 112      | 6.74%   |
| 601-700        | 105      | 6.32%   |
| 351-400        | 82       | 4.94%   |
| 701-800        | 54       | 3.25%   |
| 1501-2000      | 43       | 2.59%   |
| More than 2000 | 34       | 2.05%   |
| 1001-1500      | 33       | 1.99%   |
| 801-900        | 17       | 1.02%   |
| 201-300        | 12       | 0.72%   |
| 901-1000       | 6        | 0.36%   |
| 101-200        | 2        | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 997      | 61.77%  |
| 16/10   | 173      | 10.72%  |
| Unknown | 145      | 8.98%   |
| 5/4     | 139      | 8.61%   |
| 4/3     | 51       | 3.16%   |
| 21/9    | 44       | 2.73%   |
| 1.00    | 35       | 2.17%   |
| 3/2     | 13       | 0.81%   |
| 6/5     | 9        | 0.56%   |
| 32/9    | 3        | 0.19%   |
| 2.65    | 1        | 0.06%   |
| 2.00    | 1        | 0.06%   |
| 11/10   | 1        | 0.06%   |
| 1.96    | 1        | 0.06%   |
| 0.56    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 551      | 32.84%  |
| 301-350        | 231      | 13.77%  |
| 151-200        | 208      | 12.4%   |
| Unknown        | 161      | 9.59%   |
| 351-500        | 130      | 7.75%   |
| 141-150        | 124      | 7.39%   |
| More than 1000 | 106      | 6.32%   |
| 251-300        | 82       | 4.89%   |
| 101-110        | 34       | 2.03%   |
| 501-1000       | 23       | 1.37%   |
| 71-80          | 7        | 0.42%   |
| 131-140        | 5        | 0.3%    |
| 111-120        | 5        | 0.3%    |
| 121-130        | 4        | 0.24%   |
| 81-90          | 3        | 0.18%   |
| 1-40           | 2        | 0.12%   |
| 41-50          | 1        | 0.06%   |
| 91-100         | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 987      | 61.27%  |
| 101-120       | 266      | 16.51%  |
| Unknown       | 161      | 9.99%   |
| 1-50          | 82       | 5.09%   |
| 121-160       | 76       | 4.72%   |
| 161-240       | 37       | 2.3%    |
| More than 240 | 2        | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1255     | 48.7%   |
| 0     | 995      | 38.61%  |
| 2     | 298      | 11.56%  |
| 3     | 27       | 1.05%   |
| 4     | 2        | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1583     | 46.48%  |
| Intel                            | 1035     | 30.39%  |
| Qualcomm Atheros                 | 184      | 5.4%    |
| Broadcom                         | 87       | 2.55%   |
| Ralink Technology                | 52       | 1.53%   |
| Nvidia                           | 47       | 1.38%   |
| TP-Link                          | 38       | 1.12%   |
| MediaTek                         | 32       | 0.94%   |
| Broadcom Limited                 | 28       | 0.82%   |
| Ralink                           | 22       | 0.65%   |
| Marvell Technology Group         | 19       | 0.56%   |
| Aquantia                         | 19       | 0.56%   |
| Mellanox Technologies            | 16       | 0.47%   |
| Samsung Electronics              | 15       | 0.44%   |
| Qualcomm Atheros Communications  | 15       | 0.44%   |
| D-Link System                    | 14       | 0.41%   |
| ASIX Electronics                 | 14       | 0.41%   |
| American Megatrends              | 12       | 0.35%   |
| Huawei Technologies              | 10       | 0.29%   |
| D-Link                           | 10       | 0.29%   |
| VIA Technologies                 | 9        | 0.26%   |
| NetGear                          | 9        | 0.26%   |
| Microsoft                        | 9        | 0.26%   |
| Edimax Technology                | 9        | 0.26%   |
| Xiaomi                           | 8        | 0.23%   |
| ASUSTek Computer                 | 8        | 0.23%   |
| Sigma Designs                    | 5        | 0.15%   |
| Gemtek                           | 5        | 0.15%   |
| Belkin Components                | 5        | 0.15%   |
| 3Com                             | 5        | 0.15%   |
| ZTE WCDMA Technologies MSM       | 4        | 0.12%   |
| Texas Instruments                | 4        | 0.12%   |
| Dresden Elektronik               | 4        | 0.12%   |
| Silicon Integrated Systems [SiS] | 3        | 0.09%   |
| QLogic                           | 3        | 0.09%   |
| QinHeng Electronics              | 3        | 0.09%   |
| OPPO Electronics                 | 3        | 0.09%   |
| IMC Networks                     | 3        | 0.09%   |
| ICS Advent                       | 3        | 0.09%   |
| Emulex                           | 3        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1269     | 33.39%  |
| Realtek RTL8125 2.5GbE Controller                                 | 125      | 3.29%   |
| Intel I211 Gigabit Network Connection                             | 94       | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 87       | 2.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 86       | 2.26%   |
| Intel Wi-Fi 6 AX200                                               | 86       | 2.26%   |
| Intel Ethernet Controller I225-V                                  | 74       | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 62       | 1.63%   |
| Intel I210 Gigabit Network Connection                             | 56       | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 55       | 1.45%   |
| Intel Wireless 3165                                               | 37       | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 37       | 0.97%   |
| Intel 82574L Gigabit Network Connection                           | 36       | 0.95%   |
| Intel Ethernet Connection (14) I219-V                             | 35       | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 31       | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 29       | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 29       | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 29       | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 29       | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 25       | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 25       | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 24       | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23       | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22       | 0.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 22       | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.55%   |
| Ralink MT7601U Wireless Adapter                                   | 19       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 18       | 0.47%   |
| Intel Wireless-AC 9260                                            | 18       | 0.47%   |
| Intel I350 Gigabit Network Connection                             | 18       | 0.47%   |
| Intel Ethernet Controller X550                                    | 18       | 0.47%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 18       | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17       | 0.45%   |
| Realtek 802.11ac NIC                                              | 17       | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 17       | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 17       | 0.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 17       | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16       | 0.42%   |
| Intel Wireless 7265                                               | 16       | 0.42%   |
| Intel Wireless 7260                                               | 16       | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 313      | 37.99%  |
| Realtek Semiconductor           | 168      | 20.39%  |
| Qualcomm Atheros                | 87       | 10.56%  |
| Ralink Technology               | 52       | 6.31%   |
| TP-Link                         | 35       | 4.25%   |
| MediaTek                        | 30       | 3.64%   |
| Ralink                          | 22       | 2.67%   |
| Broadcom                        | 21       | 2.55%   |
| Qualcomm Atheros Communications | 15       | 1.82%   |
| D-Link                          | 10       | 1.21%   |
| NetGear                         | 9        | 1.09%   |
| Microsoft                       | 8        | 0.97%   |
| Edimax Technology               | 8        | 0.97%   |
| ASUSTek Computer                | 8        | 0.97%   |
| D-Link System                   | 7        | 0.85%   |
| Belkin Components               | 5        | 0.61%   |
| Gemtek                          | 4        | 0.49%   |
| Broadcom Limited                | 4        | 0.49%   |
| IMC Networks                    | 3        | 0.36%   |
| AVM                             | 3        | 0.36%   |
| Wilocity                        | 2        | 0.24%   |
| Linksys                         | 2        | 0.24%   |
| Xiaomi                          | 1        | 0.12%   |
| Tenda                           | 1        | 0.12%   |
| Sitecom Europe                  | 1        | 0.12%   |
| Micro Star International        | 1        | 0.12%   |
| Marvell Technology Group        | 1        | 0.12%   |
| Encore Electronics              | 1        | 0.12%   |
| CyberTAN Technology             | 1        | 0.12%   |
| BUFFALO                         | 1        | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 86       | 10.39%  |
| Intel Wireless 3165                                            | 37       | 4.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 29       | 3.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 29       | 3.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 25       | 3.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23       | 2.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 22       | 2.66%   |
| Ralink MT7601U Wireless Adapter                                | 19       | 2.29%   |
| Intel Wireless-AC 9260                                         | 18       | 2.17%   |
| Realtek 802.11ac NIC                                           | 17       | 2.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 17       | 2.05%   |
| Intel Wireless 7265                                            | 16       | 1.93%   |
| Intel Wireless 7260                                            | 16       | 1.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 14       | 1.69%   |
| Qualcomm Atheros AR9271 802.11n                                | 14       | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14       | 1.69%   |
| Ralink RT5370 Wireless Adapter                                 | 13       | 1.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12       | 1.45%   |
| Intel Wireless 8260                                            | 10       | 1.21%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 10       | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9        | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9        | 1.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 8        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8        | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8        | 0.97%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 8        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 0.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7        | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 6        | 0.72%   |
| Ralink RT5372 Wireless Adapter                                 | 6        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6        | 0.72%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 5        | 0.6%    |
| TP-Link 802.11ac NIC                                           | 5        | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 5        | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1517     | 54.55%  |
| Intel                             | 858      | 30.85%  |
| Qualcomm Atheros                  | 105      | 3.78%   |
| Broadcom                          | 70       | 2.52%   |
| Nvidia                            | 46       | 1.65%   |
| Broadcom Limited                  | 24       | 0.86%   |
| Marvell Technology Group          | 19       | 0.68%   |
| Aquantia                          | 19       | 0.68%   |
| Mellanox Technologies             | 14       | 0.5%    |
| ASIX Electronics                  | 14       | 0.5%    |
| American Megatrends               | 12       | 0.43%   |
| Samsung Electronics               | 11       | 0.4%    |
| VIA Technologies                  | 9        | 0.32%   |
| Xiaomi                            | 7        | 0.25%   |
| D-Link System                     | 7        | 0.25%   |
| Huawei Technologies               | 6        | 0.22%   |
| 3Com                              | 5        | 0.18%   |
| TP-Link                           | 3        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 3        | 0.11%   |
| QLogic                            | 3        | 0.11%   |
| OPPO Electronics                  | 3        | 0.11%   |
| ICS Advent                        | 3        | 0.11%   |
| Emulex                            | 3        | 0.11%   |
| DisplayLink                       | 3        | 0.11%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.07%   |
| Qualcomm                          | 2        | 0.07%   |
| Motorola PCS                      | 2        | 0.07%   |
| Tehuti Networks                   | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| Microsoft                         | 1        | 0.04%   |
| MediaTek                          | 1        | 0.04%   |
| Lenovo                            | 1        | 0.04%   |
| Google                            | 1        | 0.04%   |
| Gemtek                            | 1        | 0.04%   |
| Edimax Technology                 | 1        | 0.04%   |
| ATEN International                | 1        | 0.04%   |
| ADMtek                            | 1        | 0.04%   |
| Accton Technology                 | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1269     | 43.47%  |
| Realtek RTL8125 2.5GbE Controller                                 | 125      | 4.28%   |
| Intel I211 Gigabit Network Connection                             | 94       | 3.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 87       | 2.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 86       | 2.95%   |
| Intel Ethernet Controller I225-V                                  | 74       | 2.54%   |
| Intel Ethernet Connection (2) I219-V                              | 62       | 2.12%   |
| Intel I210 Gigabit Network Connection                             | 56       | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 55       | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 37       | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 36       | 1.23%   |
| Intel Ethernet Connection (14) I219-V                             | 35       | 1.2%    |
| Intel Ethernet Connection (7) I219-V                              | 31       | 1.06%   |
| Nvidia MCP61 Ethernet                                             | 29       | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 29       | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 25       | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 24       | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22       | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 18       | 0.62%   |
| Intel I350 Gigabit Network Connection                             | 18       | 0.62%   |
| Intel Ethernet Controller X550                                    | 18       | 0.62%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 18       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17       | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 17       | 0.58%   |
| Intel Ethernet Connection (2) I218-V                              | 17       | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16       | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 15       | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 15       | 0.51%   |
| Intel Ethernet Controller I226-V                                  | 14       | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 13       | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 13       | 0.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 13       | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 12       | 0.41%   |
| American Megatrends Virtual Ethernet.                             | 12       | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11       | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10       | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 10       | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2527     | 75.46%  |
| WiFi     | 769      | 22.96%  |
| Modem    | 48       | 1.43%   |
| Unknown  | 5        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2222     | 87.83%  |
| WiFi     | 307      | 12.13%  |
| Modem    | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1661     | 65.04%  |
| 2     | 643      | 25.18%  |
| 3     | 144      | 5.64%   |
| 4     | 39       | 1.53%   |
| 5     | 20       | 0.78%   |
| 6     | 16       | 0.63%   |
| 0     | 12       | 0.47%   |
| 7     | 7        | 0.27%   |
| 8     | 5        | 0.2%    |
| 9     | 3        | 0.12%   |
| 12    | 2        | 0.08%   |
| 17    | 1        | 0.04%   |
| 13    | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2095     | 81.74%  |
| Yes  | 468      | 18.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 289      | 46.09%  |
| Cambridge Silicon Radio         | 140      | 22.33%  |
| Realtek Semiconductor           | 50       | 7.97%   |
| ASUSTek Computer                | 33       | 5.26%   |
| Broadcom                        | 27       | 4.31%   |
| MediaTek                        | 23       | 3.67%   |
| Qualcomm Atheros Communications | 21       | 3.35%   |
| IMC Networks                    | 16       | 2.55%   |
| TP-Link                         | 5        | 0.8%    |
| Apple                           | 4        | 0.64%   |
| Lite-On Technology              | 3        | 0.48%   |
| Foxconn / Hon Hai               | 3        | 0.48%   |
| Belkin Components               | 2        | 0.32%   |
| Toshiba                         | 1        | 0.16%   |
| Sitecom Europe                  | 1        | 0.16%   |
| SINO WEALTH                     | 1        | 0.16%   |
| Realtek                         | 1        | 0.16%   |
| Microsoft                       | 1        | 0.16%   |
| Micro Star International        | 1        | 0.16%   |
| Integrated System Solution      | 1        | 0.16%   |
| Hewlett-Packard                 | 1        | 0.16%   |
| Edimax Technology               | 1        | 0.16%   |
| Dynex                           | 1        | 0.16%   |
| Unknown                         | 1        | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 140      | 22.29%  |
| Intel Bluetooth wireless interface                        | 82       | 13.06%  |
| Intel AX200 Bluetooth                                     | 82       | 13.06%  |
| Realtek Bluetooth Radio                                   | 39       | 6.21%   |
| Intel Bluetooth Device                                    | 36       | 5.73%   |
| Intel Wireless-AC 3168 Bluetooth                          | 28       | 4.46%   |
| Intel AX210 Bluetooth                                     | 24       | 3.82%   |
| MediaTek Wireless_Device                                  | 23       | 3.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 18       | 2.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 16       | 2.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 15       | 2.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 11       | 1.75%   |
| ASUS Bluetooth Device                                     | 11       | 1.75%   |
| IMC Networks Bluetooth Radio                              | 8        | 1.27%   |
| Realtek  Bluetooth 4.2 Adapter                            | 7        | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                        | 6        | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 6        | 0.96%   |
| TP-Link UB500 Adapter                                     | 5        | 0.8%    |
| ASUS Bluetooth Radio                                      | 5        | 0.8%    |
| Qualcomm Atheros Bluetooth USB Host Controller            | 4        | 0.64%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 0.64%   |
| IMC Networks Bluetooth Device                             | 4        | 0.64%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 3        | 0.48%   |
| Realtek Bluetooth 5.1 Radio                               | 2        | 0.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 2        | 0.32%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)           | 2        | 0.32%   |
| Lite-On Bluetooth Device                                  | 2        | 0.32%   |
| IMC Networks Wireless_Device                              | 2        | 0.32%   |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 2        | 0.32%   |
| Broadcom BCM2045 Bluetooth                                | 2        | 0.32%   |
| ASUS Bluetooth Adapter                                    | 2        | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 2        | 0.32%   |
| Apple Bluetooth USB Host Controller                       | 2        | 0.32%   |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.16%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.16%   |
| SINO WEALTH RK Bluetooth Keyboard                         | 1        | 0.16%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                   | 1        | 0.16%   |
| Realtek RTL8723B Bluetooth                                | 1        | 0.16%   |
| Realtek Bluetooth Radio                                   | 1        | 0.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1663     | 44.87%  |
| AMD                                          | 815      | 21.99%  |
| Nvidia                                       | 781      | 21.07%  |
| C-Media Electronics                          | 74       | 2%      |
| Logitech                                     | 38       | 1.03%   |
| Creative Labs                                | 35       | 0.94%   |
| KTMicro                                      | 24       | 0.65%   |
| ASUSTek Computer                             | 24       | 0.65%   |
| Texas Instruments                            | 14       | 0.38%   |
| Generalplus Technology                       | 14       | 0.38%   |
| VIA Technologies                             | 13       | 0.35%   |
| Focusrite-Novation                           | 13       | 0.35%   |
| Micro Star International                     | 11       | 0.3%    |
| Creative Technology                          | 11       | 0.3%    |
| Kingston Technology                          | 9        | 0.24%   |
| SteelSeries ApS                              | 8        | 0.22%   |
| JMTek                                        | 8        | 0.22%   |
| GN Netcom                                    | 8        | 0.22%   |
| Plantronics                                  | 7        | 0.19%   |
| RODE Microphones                             | 6        | 0.16%   |
| GYROCOM C&C                                  | 6        | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 5        | 0.13%   |
| Yamaha                                       | 5        | 0.13%   |
| Razer USA                                    | 5        | 0.13%   |
| Giga-Byte Technology                         | 5        | 0.13%   |
| Dell                                         | 5        | 0.13%   |
| BEHRINGER International                      | 5        | 0.13%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.11%   |
| Cambridge Silicon Radio                      | 4        | 0.11%   |
| TerraTec Electronic                          | 3        | 0.08%   |
| Tenx Technology                              | 3        | 0.08%   |
| Samson Technologies                          | 3        | 0.08%   |
| Realtek Semiconductor                        | 3        | 0.08%   |
| Ensoniq                                      | 3        | 0.08%   |
| Corsair                                      | 3        | 0.08%   |
| Blue Microphones                             | 3        | 0.08%   |
| XMOS                                         | 2        | 0.05%   |
| Valve Software                               | 2        | 0.05%   |
| Unknown                                      | 2        | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 237      | 5.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 203      | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 198      | 4.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 179      | 4.16%   |
| Intel 200 Series PCH HD Audio                                              | 151      | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 150      | 3.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 140      | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 138      | 3.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 128      | 2.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 99       | 2.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 84       | 1.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 80       | 1.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 78       | 1.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 75       | 1.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 70       | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 69       | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 64       | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 64       | 1.49%   |
| AMD FCH Azalia Controller                                                  | 59       | 1.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 57       | 1.33%   |
| Intel Comet Lake PCH cAVS                                                  | 51       | 1.19%   |
| Intel Alder Lake-S HD Audio Controller                                     | 46       | 1.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 45       | 1.05%   |
| Intel Jasper Lake HD Audio                                                 | 44       | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 43       | 1%      |
| Nvidia High Definition Audio Controller                                    | 40       | 0.93%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 40       | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 36       | 0.84%   |
| Nvidia GP108 High Definition Audio Controller                              | 35       | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 35       | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 35       | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 35       | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                              | 34       | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                | 34       | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 34       | 0.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 32       | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 31       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 30       | 0.7%    |
| AMD Navi 10 HDMI Audio                                                     | 30       | 0.7%    |
| Nvidia MCP61 High Definition Audio                                         | 29       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 431      | 17.17%  |
| Unknown                      | 377      | 15.02%  |
| Crucial                      | 304      | 12.11%  |
| Samsung Electronics          | 267      | 10.64%  |
| SK hynix                     | 232      | 9.24%   |
| Corsair                      | 207      | 8.25%   |
| G.Skill                      | 144      | 5.74%   |
| Micron Technology            | 106      | 4.22%   |
| Patriot                      | 68       | 2.71%   |
| A-DATA Technology            | 42       | 1.67%   |
| Unknown                      | 34       | 1.35%   |
| Team                         | 23       | 0.92%   |
| Hikvision                    | 21       | 0.84%   |
| Unknown (ABCD)               | 20       | 0.8%    |
| Ramaxel Technology           | 20       | 0.8%    |
| AMD                          | 18       | 0.72%   |
| Nanya Technology             | 16       | 0.64%   |
| Elpida                       | 15       | 0.6%    |
| Transcend                    | 9        | 0.36%   |
| Smart                        | 9        | 0.36%   |
| Goodram                      | 9        | 0.36%   |
| Timetec                      | 7        | 0.28%   |
| Apacer                       | 7        | 0.28%   |
| Unknown (0x5846)             | 6        | 0.24%   |
| Hewlett-Packard              | 6        | 0.24%   |
| GeIL                         | 6        | 0.24%   |
| Avant                        | 6        | 0.24%   |
| Qimonda                      | 5        | 0.2%    |
| Unknown (0x0DD5)             | 4        | 0.16%   |
| Unknown (AB)                 | 3        | 0.12%   |
| Unknown (0x0B45)             | 3        | 0.12%   |
| Unifosa                      | 3        | 0.12%   |
| Toshiba                      | 3        | 0.12%   |
| PNY                          | 3        | 0.12%   |
| Patriot Memory (PDP Systems) | 3        | 0.12%   |
| Kingmax                      | 3        | 0.12%   |
| Goldkey                      | 3        | 0.12%   |
| Wilk                         | 2        | 0.08%   |
| V-Color                      | 2        | 0.08%   |
| Silicon Power                | 2        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 44       | 1.59%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s       | 36       | 1.3%    |
| Unknown                                                        | 34       | 1.23%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s          | 31       | 1.12%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4096MB DIMM DDR4 2133MT/s      | 29       | 1.05%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 25       | 0.9%    |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s           | 24       | 0.87%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 23       | 0.83%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 20       | 0.72%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 20       | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 20       | 0.72%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s        | 20       | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 19       | 0.69%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 18       | 0.65%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 17       | 0.62%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                | 16       | 0.58%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 15       | 0.54%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                 | 14       | 0.51%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 13       | 0.47%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s           | 12       | 0.43%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s           | 12       | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 11       | 0.4%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 11       | 0.4%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 11       | 0.4%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 11       | 0.4%    |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 10       | 0.36%   |
| Unknown RAM Module 1GB DIMM                                    | 10       | 0.36%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 10       | 0.36%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 10       | 0.36%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s        | 10       | 0.36%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 10       | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 9        | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 9        | 0.33%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 9        | 0.33%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s          | 9        | 0.33%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s         | 9        | 0.33%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 8        | 0.29%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 8        | 0.29%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.29%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 8        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1019     | 45.7%   |
| DDR3         | 744      | 33.36%  |
| Unknown      | 155      | 6.95%   |
| SDRAM        | 127      | 5.7%    |
| DDR2         | 103      | 4.62%   |
| LPDDR4       | 29       | 1.3%    |
| DDR          | 24       | 1.08%   |
| DDR5         | 22       | 0.99%   |
| DRAM         | 6        | 0.27%   |
| DDR2 FB-DIMM | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1963     | 89.19%  |
| SODIMM       | 213      | 9.68%   |
| Row Of Chips | 10       | 0.45%   |
| RIMM         | 8        | 0.36%   |
| FB-DIMM      | 4        | 0.18%   |
| Unknown      | 2        | 0.09%   |
| Chip         | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 773      | 31.85%  |
| 4096    | 549      | 22.62%  |
| 2048    | 384      | 15.82%  |
| 16384   | 378      | 15.57%  |
| 32768   | 173      | 7.13%   |
| 1024    | 126      | 5.19%   |
| 512     | 29       | 1.19%   |
| 256     | 7        | 0.29%   |
| 65536   | 4        | 0.16%   |
| 3072    | 1        | 0.04%   |
| 1536    | 1        | 0.04%   |
| 128     | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 417      | 17.13%  |
| 1333    | 272      | 11.17%  |
| 3200    | 218      | 8.95%   |
| 2667    | 202      | 8.3%    |
| 2400    | 148      | 6.08%   |
| 2133    | 122      | 5.01%   |
| 3600    | 113      | 4.64%   |
| 800     | 108      | 4.44%   |
| Unknown | 98       | 4.02%   |
| 1866    | 75       | 3.08%   |
| 2666    | 69       | 2.83%   |
| 667     | 50       | 2.05%   |
| 1867    | 35       | 1.44%   |
| 3400    | 33       | 1.36%   |
| 2933    | 30       | 1.23%   |
| 1066    | 30       | 1.23%   |
| 3000    | 29       | 1.19%   |
| 1800    | 29       | 1.19%   |
| 3733    | 28       | 1.15%   |
| 1067    | 28       | 1.15%   |
| 2866    | 26       | 1.07%   |
| 4800    | 19       | 0.78%   |
| 3800    | 19       | 0.78%   |
| 3466    | 18       | 0.74%   |
| 1334    | 13       | 0.53%   |
| 400     | 13       | 0.53%   |
| 3933    | 11       | 0.45%   |
| 3533    | 11       | 0.45%   |
| 3866    | 10       | 0.41%   |
| 3534    | 10       | 0.41%   |
| 3100    | 9        | 0.37%   |
| 2048    | 9        | 0.37%   |
| 533     | 9        | 0.37%   |
| 3266    | 8        | 0.33%   |
| 1648    | 8        | 0.33%   |
| 4333    | 7        | 0.29%   |
| 3666    | 7        | 0.29%   |
| 2800    | 7        | 0.29%   |
| 3500    | 6        | 0.25%   |
| 2733    | 5        | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 36       | 36%     |
| Brother Industries    | 20       | 20%     |
| Canon                 | 11       | 11%     |
| Samsung Electronics   | 7        | 7%      |
| Seiko Epson           | 4        | 4%      |
| Xerox                 | 3        | 3%      |
| Lexmark International | 3        | 3%      |
| Dymo-CoStar           | 3        | 3%      |
| Zebra                 | 2        | 2%      |
| Prolific Technology   | 2        | 2%      |
| Pantum                | 2        | 2%      |
| STMicroelectronics    | 1        | 1%      |
| QinHeng Electronics   | 1        | 1%      |
| Printer               | 1        | 1%      |
| Kyocera               | 1        | 1%      |
| Konica Minolta        | 1        | 1%      |
| GODEX INTERNATIONAL   | 1        | 1%      |
| Apple                 | 1        | 1%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1200                                          | 5        | 5%      |
| Xerox B205                                                | 3        | 3%      |
| Samsung ML-1660 Series                                    | 3        | 3%      |
| HP LaserJet M101-M106                                     | 3        | 3%      |
| HP LaserJet 1020                                          | 3        | 3%      |
| Prolific PL2305 Parallel Port                             | 2        | 2%      |
| HP LaserJet P1005                                         | 2        | 2%      |
| HP ENVY 4520 series                                       | 2        | 2%      |
| Canon MF4410                                              | 2        | 2%      |
| Brother MFC-7460DN                                        | 2        | 2%      |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 1%      |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 1%      |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1%      |
| Seiko Epson XP-200 Series                                 | 1        | 1%      |
| Seiko Epson M105 Series                                   | 1        | 1%      |
| Seiko Epson L3150 Series                                  | 1        | 1%      |
| Seiko Epson ET-2700 Series                                | 1        | 1%      |
| Samsung SCX-4x26 Series                                   | 1        | 1%      |
| Samsung SCX-4650 4x21S Series                             | 1        | 1%      |
| Samsung SCX-3200 Series                                   | 1        | 1%      |
| Samsung ML-216x Series Laser Printer                      | 1        | 1%      |
| QinHeng CH340S                                            | 1        | 1%      |
| Printer Printer                                           | 1        | 1%      |
| Pantum P2500W series                                      | 1        | 1%      |
| Pantum M6500-series                                       | 1        | 1%      |
| Lexmark International MS710                               | 1        | 1%      |
| Lexmark International Laser Printer                       | 1        | 1%      |
| Lexmark International B2338dw                             | 1        | 1%      |
| Kyocera ECOSYS M5521cdn                                   | 1        | 1%      |
| Konica Minolta bizhub 4402P                               | 1        | 1%      |
| HP Officejet J4500 series                                 | 1        | 1%      |
| HP Officejet 7110 series                                  | 1        | 1%      |
| HP LaserJet Pro M404-M405                                 | 1        | 1%      |
| HP LaserJet Pro M148-M149                                 | 1        | 1%      |
| HP LaserJet P2055 series                                  | 1        | 1%      |
| HP Laserjet P1505                                         | 1        | 1%      |
| HP LaserJet P1006                                         | 1        | 1%      |
| HP LaserJet M14-M17                                       | 1        | 1%      |
| HP LaserJet 400 M401a                                     | 1        | 1%      |
| HP LaserJet 1320                                          | 1        | 1%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 14       | 60.87%  |
| Seiko Epson     | 4        | 17.39%  |
| Hewlett-Packard | 3        | 13.04%  |
| AGFA-Gevaert NV | 2        | 8.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 3        | 13.04%  |
| Canon CanoScan LiDE 220                                       | 3        | 13.04%  |
| Canon CanoScan LiDE 210                                       | 2        | 8.7%    |
| Canon CanoScan LiDE 110                                       | 2        | 8.7%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2        | 8.7%    |
| Seiko Epson GT-X770 [Perfection V500]                         | 1        | 4.35%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 4.35%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1        | 4.35%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 4.35%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 4.35%   |
| HP ScanJet 3970c                                              | 1        | 4.35%   |
| HP Scanjet 300                                                | 1        | 4.35%   |
| Canon CanoScan LiDE 60                                        | 1        | 4.35%   |
| Canon CanoScan 8800F                                          | 1        | 4.35%   |
| Canon CanoScan 5600F                                          | 1        | 4.35%   |
| Canon CanoScan 4400F                                          | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 138      | 40.71%  |
| Microdia                               | 23       | 6.78%   |
| Generalplus Technology                 | 16       | 4.72%   |
| Sunplus Innovation Technology          | 15       | 4.42%   |
| Microsoft                              | 12       | 3.54%   |
| Creative Technology                    | 11       | 3.24%   |
| Jieli Technology                       | 10       | 2.95%   |
| Apple                                  | 10       | 2.95%   |
| Samsung Electronics                    | 9        | 2.65%   |
| KYE Systems (Mouse Systems)            | 7        | 2.06%   |
| Chicony Electronics                    | 6        | 1.77%   |
| ARC International                      | 6        | 1.77%   |
| Z-Star Microelectronics                | 5        | 1.47%   |
| GEMBIRD                                | 5        | 1.47%   |
| Novatek Microelectronics               | 3        | 0.88%   |
| Google                                 | 3        | 0.88%   |
| Genesys Logic                          | 3        | 0.88%   |
| AVerMedia Technologies                 | 3        | 0.88%   |
| Xiongmai                               | 2        | 0.59%   |
| Valve Software                         | 2        | 0.59%   |
| Realtek Semiconductor                  | 2        | 0.59%   |
| Razer USA                              | 2        | 0.59%   |
| Nintendo                               | 2        | 0.59%   |
| MacroSilicon                           | 2        | 0.59%   |
| Cubeternet                             | 2        | 0.59%   |
| Creality 3D Technology                 | 2        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.59%   |
| Aveo Technology                        | 2        | 0.59%   |
| Arkmicro Technologies                  | 2        | 0.59%   |
| Xiaomi                                 | 1        | 0.29%   |
| WaveRider Communications               | 1        | 0.29%   |
| ValueHD                                | 1        | 0.29%   |
| USB3.0 HD Audio Capture                | 1        | 0.29%   |
| Unknown                                | 1        | 0.29%   |
| Trust                                  | 1        | 0.29%   |
| Tobii Technology AB                    | 1        | 0.29%   |
| Syntek                                 | 1        | 0.29%   |
| SunplusIT                              | 1        | 0.29%   |
| Sunplus IT                             | 1        | 0.29%   |
| Silicon Motion                         | 1        | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 47       | 13.74%  |
| Logitech C922 Pro Stream Webcam            | 15       | 4.39%   |
| Logitech HD Pro Webcam C920                | 13       | 3.8%    |
| Jieli USB PHY 2.0                          | 10       | 2.92%   |
| Generalplus GENERAL WEBCAM                 | 10       | 2.92%   |
| Apple iPhone 5/5C/5S/6/SE                  | 10       | 2.92%   |
| Samsung Galaxy series, misc. (MTP mode)    | 9        | 2.63%   |
| Microsoft LifeCam HD-3000                  | 7        | 2.05%   |
| Microdia Webcam Vitade AF                  | 7        | 2.05%   |
| Logitech Webcam C310                       | 7        | 2.05%   |
| Logitech Webcam C170                       | 7        | 2.05%   |
| Microdia USB Camera                        | 6        | 1.75%   |
| Logitech HD Webcam C615                    | 6        | 1.75%   |
| Logitech C920 PRO HD Webcam                | 6        | 1.75%   |
| KYE Systems (Mouse Systems) Genius Webcam  | 6        | 1.75%   |
| Sunplus Integrated_Webcam_HD               | 5        | 1.46%   |
| Logitech HD Webcam C525                    | 5        | 1.46%   |
| Z-Star Venus USB2.0 Camera                 | 4        | 1.17%   |
| ARC International Camera                   | 4        | 1.17%   |
| Novatek HP High Definition 2MP Webcam      | 3        | 0.88%   |
| Microdia USB 2.0 Camera                    | 3        | 0.88%   |
| Logitech Webcam C925e                      | 3        | 0.88%   |
| Logitech Logi Webcam C920e                 | 3        | 0.88%   |
| Logitech HD Webcam C910                    | 3        | 0.88%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 0.88%   |
| Generalplus WEB CAM                        | 3        | 0.88%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 3        | 0.88%   |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 3        | 0.88%   |
| Xiongmai web camera                        | 2        | 0.58%   |
| Valve Software 3D Camera                   | 2        | 0.58%   |
| Sunplus WEBCAM ESSENTIELB W1               | 2        | 0.58%   |
| Sunplus HD 720P webcam                     | 2        | 0.58%   |
| Razer USA Gaming Webcam [Kiyo]             | 2        | 0.58%   |
| Nintendo USB Camera                        | 2        | 0.58%   |
| Microsoft LifeCam HD-5000                  | 2        | 0.58%   |
| Microdia Sonix USB 2.0 Camera              | 2        | 0.58%   |
| Microdia Camera                            | 2        | 0.58%   |
| Logitech StreamCam                         | 2        | 0.58%   |
| Logitech QuickCam Pro 9000                 | 2        | 0.58%   |
| Logitech QuickCam Pro 4000                 | 2        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 50%     |
| Synaptics        | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 50%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| SCM Microsystems         | 3        | 18.75%  |
| Gemalto (was Gemplus)    | 2        | 12.5%   |
| Alcor Micro              | 2        | 12.5%   |
| Yubico.com               | 1        | 6.25%   |
| Reiner SCT Kartensysteme | 1        | 6.25%   |
| Realtek Semiconductor    | 1        | 6.25%   |
| Lenovo                   | 1        | 6.25%   |
| Feitian Technologies     | 1        | 6.25%   |
| Clay Logic               | 1        | 6.25%   |
| Chicony Electronics      | 1        | 6.25%   |
| Cherry                   | 1        | 6.25%   |
| Advanced Card Systems    | 1        | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 2        | 12.5%   |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 6.25%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 6.25%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 6.25%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 6.25%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 6.25%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 6.25%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 6.25%   |
| Feitian Technologies SCR301                                                | 1        | 6.25%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 6.25%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 6.25%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 6.25%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 6.25%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 6.25%   |
| Advanced Card Systems ACR39U                                               | 1        | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1467     | 57.02%  |
| 1     | 964      | 37.47%  |
| 2     | 123      | 4.78%   |
| 3     | 14       | 0.54%   |
| 4     | 3        | 0.12%   |
| 7     | 1        | 0.04%   |
| 5     | 1        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 923      | 76.85%  |
| Net/wireless             | 97       | 8.08%   |
| Communication controller | 43       | 3.58%   |
| Unassigned class         | 40       | 3.33%   |
| Sound                    | 21       | 1.75%   |
| Multimedia controller    | 15       | 1.25%   |
| Bluetooth                | 14       | 1.17%   |
| Camera                   | 10       | 0.83%   |
| Chipcard                 | 8        | 0.67%   |
| Card reader              | 6        | 0.5%    |
| Storage/raid             | 5        | 0.42%   |
| Net/ethernet             | 5        | 0.42%   |
| Tv card                  | 3        | 0.25%   |
| Modem                    | 3        | 0.25%   |
| Network                  | 2        | 0.17%   |
| Fingerprint reader       | 2        | 0.17%   |
| Dvb card                 | 2        | 0.17%   |
| Storage/nvme             | 1        | 0.08%   |
| Storage                  | 1        | 0.08%   |

