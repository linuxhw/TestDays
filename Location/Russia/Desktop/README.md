Linux in Russia - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 18367

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 8906 SMVB                   | [74430f2160](https://linux-hardware.org/?probe=74430f2160) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [978a5e2579](https://linux-hardware.org/?probe=978a5e2579) | Apr 01, 2023 |
| Gigabyte      | G41M-Combo                  | [ac658bcb80](https://linux-hardware.org/?probe=ac658bcb80) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| Gigabyte      | MZGLKDP-00                  | [c9427f4873](https://linux-hardware.org/?probe=c9427f4873) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASUSTek       | M5A78L LE                   | [af64a32a09](https://linux-hardware.org/?probe=af64a32a09) | Apr 01, 2023 |
| MSI           | H510M-A PRO                 | [a6953d3b96](https://linux-hardware.org/?probe=a6953d3b96) | Apr 01, 2023 |
| Unknown       | X79                         | [d0592836a5](https://linux-hardware.org/?probe=d0592836a5) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | P8B75-V                     | [5ed3be8dbc](https://linux-hardware.org/?probe=5ed3be8dbc) | Mar 31, 2023 |
| ASUSTek       | M5A78L LE                   | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [1ac381c18f](https://linux-hardware.org/?probe=1ac381c18f) | Mar 31, 2023 |
| Gigabyte      | Z77-DS3H                    | [79e2cfa0f1](https://linux-hardware.org/?probe=79e2cfa0f1) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [51c601477f](https://linux-hardware.org/?probe=51c601477f) | Mar 31, 2023 |
| Gigabyte      | Z77X-UD5H                   | [323d8881a5](https://linux-hardware.org/?probe=323d8881a5) | Mar 31, 2023 |
| ASRock        | N68-GS4 FX                  | [573f5db37d](https://linux-hardware.org/?probe=573f5db37d) | Mar 31, 2023 |
| Quanta        | 2AC5 100                    | [7f253a82dc](https://linux-hardware.org/?probe=7f253a82dc) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [6bd60aa5f0](https://linux-hardware.org/?probe=6bd60aa5f0) | Mar 31, 2023 |
| Gigabyte      | 965P-DS4                    | [ddebc735da](https://linux-hardware.org/?probe=ddebc735da) | Mar 31, 2023 |
| Intel         | X79                         | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | H510M PRO-E                 | [9ec66a8f48](https://linux-hardware.org/?probe=9ec66a8f48) | Mar 31, 2023 |
| MSI           | G31TM-P21                   | [7404d94ca4](https://linux-hardware.org/?probe=7404d94ca4) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a0f5608b2](https://linux-hardware.org/?probe=7a0f5608b2) | Mar 31, 2023 |
| ECS           | H61H2-M6                    | [6c33ee7e15](https://linux-hardware.org/?probe=6c33ee7e15) | Mar 31, 2023 |
| ASRock        | H61M                        | [29327171c4](https://linux-hardware.org/?probe=29327171c4) | Mar 31, 2023 |
| Gigabyte      | EP43-DS3L                   | [b7594db73b](https://linux-hardware.org/?probe=b7594db73b) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX3                | [6ff0a3cb3f](https://linux-hardware.org/?probe=6ff0a3cb3f) | Mar 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [3670f0a6ed](https://linux-hardware.org/?probe=3670f0a6ed) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| Gigabyte      | P41T-D3P                    | [c8cadc8a94](https://linux-hardware.org/?probe=c8cadc8a94) | Mar 30, 2023 |
| Intel         | B75A                        | [b7b1423f34](https://linux-hardware.org/?probe=b7b1423f34) | Mar 30, 2023 |
| Gigabyte      | H410M S2H V2                | [cf13162657](https://linux-hardware.org/?probe=cf13162657) | Mar 30, 2023 |
| MSI           | H510M-A PRO                 | [49a4903c58](https://linux-hardware.org/?probe=49a4903c58) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| Foxconn       | 2ABF                        | [8e1750d5e4](https://linux-hardware.org/?probe=8e1750d5e4) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | P8H77-V                     | [1869e23c56](https://linux-hardware.org/?probe=1869e23c56) | Mar 30, 2023 |
| MSI           | H97 PC Mate                 | [37c098e51a](https://linux-hardware.org/?probe=37c098e51a) | Mar 30, 2023 |
| Gigabyte      | Z390 UD                     | [558d551d9a](https://linux-hardware.org/?probe=558d551d9a) | Mar 30, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [6bb5f276cd](https://linux-hardware.org/?probe=6bb5f276cd) | Mar 30, 2023 |
| Gigabyte      | H77N-WIFI                   | [fecc161428](https://linux-hardware.org/?probe=fecc161428) | Mar 30, 2023 |
| Gigabyte      | B75M-D3V                    | [d3ae118e3b](https://linux-hardware.org/?probe=d3ae118e3b) | Mar 30, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [3ad3c5e45c](https://linux-hardware.org/?probe=3ad3c5e45c) | Mar 30, 2023 |
| Huanan        | X99-QD4 V1.0                | [d88393be26](https://linux-hardware.org/?probe=d88393be26) | Mar 30, 2023 |
| Gigabyte      | H81M-S2V                    | [5a16920bc0](https://linux-hardware.org/?probe=5a16920bc0) | Mar 30, 2023 |
| Acer          | Aspire TC-605               | [5938e606b6](https://linux-hardware.org/?probe=5938e606b6) | Mar 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [0580e11b2f](https://linux-hardware.org/?probe=0580e11b2f) | Mar 29, 2023 |
| ASRock        | B650M PG Riptide            | [f019265109](https://linux-hardware.org/?probe=f019265109) | Mar 29, 2023 |
| Unknown       | Unknown                     | [e62607df55](https://linux-hardware.org/?probe=e62607df55) | Mar 29, 2023 |
| ASRock        | N68PV-GS                    | [1c473cd5c6](https://linux-hardware.org/?probe=1c473cd5c6) | Mar 29, 2023 |
| Gigabyte      | 945P-S3                     | [8aa985b6fa](https://linux-hardware.org/?probe=8aa985b6fa) | Mar 29, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [55a22382cc](https://linux-hardware.org/?probe=55a22382cc) | Mar 29, 2023 |
| ASRock        | 990FX Extreme3              | [ca172328f1](https://linux-hardware.org/?probe=ca172328f1) | Mar 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [599577c3b4](https://linux-hardware.org/?probe=599577c3b4) | Mar 29, 2023 |
| ASRock        | H81M-HDS R2.0               | [1f333c98e1](https://linux-hardware.org/?probe=1f333c98e1) | Mar 29, 2023 |
| Graviton      | DMB-A520-MCA01              | [9d7a43d81f](https://linux-hardware.org/?probe=9d7a43d81f) | Mar 29, 2023 |
| Gigabyte      | B550M DS3H                  | [612dd1dba2](https://linux-hardware.org/?probe=612dd1dba2) | Mar 29, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [8400d48ed0](https://linux-hardware.org/?probe=8400d48ed0) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| Gigabyte      | H410M H V3                  | [10fd7d1526](https://linux-hardware.org/?probe=10fd7d1526) | Mar 28, 2023 |
| MSI           | X370 GAMING PLUS            | [53543ce276](https://linux-hardware.org/?probe=53543ce276) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Gigabyte      | 946GMX-S2                   | [41f98f54fd](https://linux-hardware.org/?probe=41f98f54fd) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | [b097373c25](https://linux-hardware.org/?probe=b097373c25) | Mar 28, 2023 |
| MSI           | 770-C45                     | [9b23a7e2d0](https://linux-hardware.org/?probe=9b23a7e2d0) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [23438353bb](https://linux-hardware.org/?probe=23438353bb) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [c49cc33482](https://linux-hardware.org/?probe=c49cc33482) | Mar 28, 2023 |
| Huanan        | X99-F8D V2.6                | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| Intel         | X79v2.72 KD V2.0            | [7b9dfca8cc](https://linux-hardware.org/?probe=7b9dfca8cc) | Mar 27, 2023 |
| Foxconn       | 2AA9                        | [97192fc35b](https://linux-hardware.org/?probe=97192fc35b) | Mar 27, 2023 |
| ASUSTek       | P7H55                       | [40158bca43](https://linux-hardware.org/?probe=40158bca43) | Mar 27, 2023 |
| MSI           | G41M-P33 Combo              | [ea8ce90ed5](https://linux-hardware.org/?probe=ea8ce90ed5) | Mar 27, 2023 |
| Unknown       | Unknown                     | [ecf55ab179](https://linux-hardware.org/?probe=ecf55ab179) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| Gigabyte      | MRHM3AP                     | [27ac802035](https://linux-hardware.org/?probe=27ac802035) | Mar 26, 2023 |
| Gigabyte      | H77-DS3H                    | [36d80a146f](https://linux-hardware.org/?probe=36d80a146f) | Mar 26, 2023 |
| Foxconn       | G41MXE-V                    | [38d87a8061](https://linux-hardware.org/?probe=38d87a8061) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bbfe5423c9](https://linux-hardware.org/?probe=bbfe5423c9) | Mar 26, 2023 |
| ASUSTek       | P5W DH Deluxe               | [781cafa540](https://linux-hardware.org/?probe=781cafa540) | Mar 26, 2023 |
| ASUSTek       | M5A78L/USB3                 | [732b7b7fab](https://linux-hardware.org/?probe=732b7b7fab) | Mar 26, 2023 |
| Gigabyte      | F2A55M-S1                   | [fff8f87d2a](https://linux-hardware.org/?probe=fff8f87d2a) | Mar 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [c33415cb2b](https://linux-hardware.org/?probe=c33415cb2b) | Mar 25, 2023 |
| Gigabyte      | B75M-D2V                    | [c98eac375f](https://linux-hardware.org/?probe=c98eac375f) | Mar 25, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [8f04388ab5](https://linux-hardware.org/?probe=8f04388ab5) | Mar 25, 2023 |
| MSI           | A520M PRO                   | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3ce94dae13](https://linux-hardware.org/?probe=3ce94dae13) | Mar 25, 2023 |
| HP            | 0AA4h                       | [a77b084eba](https://linux-hardware.org/?probe=a77b084eba) | Mar 25, 2023 |
| Intel         | D2700DC AAG32420-602        | [0d20e81321](https://linux-hardware.org/?probe=0d20e81321) | Mar 25, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [357a52fe14](https://linux-hardware.org/?probe=357a52fe14) | Mar 25, 2023 |
| ASRock        | X99 Professional Gaming ... | [1cafadad17](https://linux-hardware.org/?probe=1cafadad17) | Mar 25, 2023 |
| ASRock        | X99 Professional Gaming ... | [38cead30d5](https://linux-hardware.org/?probe=38cead30d5) | Mar 25, 2023 |
| Gigabyte      | H310N                       | [33a905038c](https://linux-hardware.org/?probe=33a905038c) | Mar 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f185ea819d](https://linux-hardware.org/?probe=f185ea819d) | Mar 24, 2023 |
| Gigabyte      | H61M-DS2                    | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| MACHINIST     | X99-RS9 V3.1                | [c1e2b5e7fb](https://linux-hardware.org/?probe=c1e2b5e7fb) | Mar 24, 2023 |
| ASRock        | Z370M Pro4                  | [765602e7bf](https://linux-hardware.org/?probe=765602e7bf) | Mar 24, 2023 |
| ASRock        | 990FX Extreme3              | [c310b97b8d](https://linux-hardware.org/?probe=c310b97b8d) | Mar 24, 2023 |
| Gigabyte      | H410M S2                    | [08b36ebc25](https://linux-hardware.org/?probe=08b36ebc25) | Mar 24, 2023 |
| Intel         | D945GNT AAC96315-405        | [fcc7a18f89](https://linux-hardware.org/?probe=fcc7a18f89) | Mar 24, 2023 |
| HP            | 8906 SMVB                   | [ae7d4327f5](https://linux-hardware.org/?probe=ae7d4327f5) | Mar 24, 2023 |
| Unknown       | X79M2-Q                     | [f517d6c26d](https://linux-hardware.org/?probe=f517d6c26d) | Mar 23, 2023 |
| ASRock        | N68C-GS FX                  | [03da177044](https://linux-hardware.org/?probe=03da177044) | Mar 23, 2023 |
| Gigabyte      | B85M-D2V                    | [afba39d63c](https://linux-hardware.org/?probe=afba39d63c) | Mar 23, 2023 |
| Gigabyte      | 970-GAMING                  | [f16afa095b](https://linux-hardware.org/?probe=f16afa095b) | Mar 23, 2023 |
| ECS           | G31T-M9                     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [ea6d900647](https://linux-hardware.org/?probe=ea6d900647) | Mar 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [86d12b640c](https://linux-hardware.org/?probe=86d12b640c) | Mar 23, 2023 |
| Gigabyte      | B450M S2H                   | [73d22216c2](https://linux-hardware.org/?probe=73d22216c2) | Mar 23, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [a36464850a](https://linux-hardware.org/?probe=a36464850a) | Mar 23, 2023 |
| MSI           | 760GM-P23                   | [f170457555](https://linux-hardware.org/?probe=f170457555) | Mar 23, 2023 |
| ASUSTek       | H97-PLUS                    | [577716237d](https://linux-hardware.org/?probe=577716237d) | Mar 22, 2023 |
| Gigabyte      | H97M-HD3                    | [ab4dce8483](https://linux-hardware.org/?probe=ab4dce8483) | Mar 22, 2023 |
| Graviton      | DMB-A520-MCA01              | [123e95cee1](https://linux-hardware.org/?probe=123e95cee1) | Mar 22, 2023 |
| ASUSTek       | H97-PLUS                    | [32fa1d46e2](https://linux-hardware.org/?probe=32fa1d46e2) | Mar 22, 2023 |
| DEPO Compu... | MS-7846                     | [baaaef2394](https://linux-hardware.org/?probe=baaaef2394) | Mar 22, 2023 |
| Unknown       | Unknown                     | [5d06af8741](https://linux-hardware.org/?probe=5d06af8741) | Mar 22, 2023 |
| MACHINIST     | X99-k9 V2.0                 | [24377b0218](https://linux-hardware.org/?probe=24377b0218) | Mar 22, 2023 |
| ASUSTek       | M2N-MX                      | [7eead8bd18](https://linux-hardware.org/?probe=7eead8bd18) | Mar 22, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [3308202939](https://linux-hardware.org/?probe=3308202939) | Mar 21, 2023 |
| Graviton      | DMB-A520-MCA01              | [24b07c4402](https://linux-hardware.org/?probe=24b07c4402) | Mar 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [3a70b6918f](https://linux-hardware.org/?probe=3a70b6918f) | Mar 21, 2023 |
| ASRock        | H470M-HDV                   | [52b14963e3](https://linux-hardware.org/?probe=52b14963e3) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | [7336ce9057](https://linux-hardware.org/?probe=7336ce9057) | Mar 21, 2023 |
| ASRock        | AB350 Pro4                  | [01e06fb483](https://linux-hardware.org/?probe=01e06fb483) | Mar 21, 2023 |
| MSI           | B350 GAMING PLUS            | [2d82cffc81](https://linux-hardware.org/?probe=2d82cffc81) | Mar 20, 2023 |
| Gigabyte      | P31-DS3L                    | [7fb5a2f07e](https://linux-hardware.org/?probe=7fb5a2f07e) | Mar 20, 2023 |
| Unknown       | X79M2-Q                     | [11e2caa120](https://linux-hardware.org/?probe=11e2caa120) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [e128423a13](https://linux-hardware.org/?probe=e128423a13) | Mar 20, 2023 |
| Gigabyte      | B360M DS3H                  | [4df457f6bb](https://linux-hardware.org/?probe=4df457f6bb) | Mar 20, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9a5bfcc056](https://linux-hardware.org/?probe=9a5bfcc056) | Mar 20, 2023 |
| Unknown       | Unknown                     | [dfcc73f24d](https://linux-hardware.org/?probe=dfcc73f24d) | Mar 20, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e897657a4e](https://linux-hardware.org/?probe=e897657a4e) | Mar 20, 2023 |
| ASRock        | H310CM-DVS                  | [2ef180bad0](https://linux-hardware.org/?probe=2ef180bad0) | Mar 20, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f9c84aa26c](https://linux-hardware.org/?probe=f9c84aa26c) | Mar 20, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [e49b9e39d5](https://linux-hardware.org/?probe=e49b9e39d5) | Mar 20, 2023 |
| ASUSTek       | Z97-K                       | [a48a2fbdd0](https://linux-hardware.org/?probe=a48a2fbdd0) | Mar 19, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [4f56864a63](https://linux-hardware.org/?probe=4f56864a63) | Mar 19, 2023 |
| Soyo          | SY-Classic B660M            | [cebe1d8722](https://linux-hardware.org/?probe=cebe1d8722) | Mar 19, 2023 |
| HP            | 0A54h                       | [6ec15582a7](https://linux-hardware.org/?probe=6ec15582a7) | Mar 19, 2023 |
| ASRock        | N68C-GS FX                  | [4d50b47e95](https://linux-hardware.org/?probe=4d50b47e95) | Mar 19, 2023 |
| MB            | A320-SF110                  | [588c8f3fe5](https://linux-hardware.org/?probe=588c8f3fe5) | Mar 19, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | [99096c6a78](https://linux-hardware.org/?probe=99096c6a78) | Mar 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| Gigabyte      | H110M-S2V-CF                | [1bedc9be7e](https://linux-hardware.org/?probe=1bedc9be7e) | Mar 18, 2023 |
| MSI           | MS-B0A21                    | [7b5c0f63da](https://linux-hardware.org/?probe=7b5c0f63da) | Mar 18, 2023 |
| Gigabyte      | GA-870A-UD3                 | [caf54bddb9](https://linux-hardware.org/?probe=caf54bddb9) | Mar 18, 2023 |
| Gigabyte      | 945GCM-S2L                  | [4b484ab326](https://linux-hardware.org/?probe=4b484ab326) | Mar 18, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [c399d3fbf5](https://linux-hardware.org/?probe=c399d3fbf5) | Mar 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [b33066c1b7](https://linux-hardware.org/?probe=b33066c1b7) | Mar 18, 2023 |
| ASRock        | N68C-GS FX                  | [94b8c06fdd](https://linux-hardware.org/?probe=94b8c06fdd) | Mar 18, 2023 |
| Gigabyte      | G41M-Combo                  | [877608b32b](https://linux-hardware.org/?probe=877608b32b) | Mar 18, 2023 |
| ASRock        | QC6000M                     | [b897493246](https://linux-hardware.org/?probe=b897493246) | Mar 18, 2023 |
| Unknown       | X79M2-Q                     | [fe58227748](https://linux-hardware.org/?probe=fe58227748) | Mar 17, 2023 |
| Biostar       | G41-M7                      | [7109205ef0](https://linux-hardware.org/?probe=7109205ef0) | Mar 17, 2023 |
| ZOTAC         | H67ITX-C-E                  | [1da59d5440](https://linux-hardware.org/?probe=1da59d5440) | Mar 17, 2023 |
| ASUSTek       | P8H61-M LE                  | [bb43961724](https://linux-hardware.org/?probe=bb43961724) | Mar 17, 2023 |
| ASRock        | N68C-GS FX                  | [814c2e63c6](https://linux-hardware.org/?probe=814c2e63c6) | Mar 17, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [0125449b9f](https://linux-hardware.org/?probe=0125449b9f) | Mar 17, 2023 |
| Biostar       | G41-M7                      | [b1fe372b7d](https://linux-hardware.org/?probe=b1fe372b7d) | Mar 17, 2023 |
| Gigabyte      | M52L-S3P                    | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| Intel         | X99 V1.0                    | [1b993725aa](https://linux-hardware.org/?probe=1b993725aa) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | [be0d148aa6](https://linux-hardware.org/?probe=be0d148aa6) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | [3b591bcb12](https://linux-hardware.org/?probe=3b591bcb12) | Mar 17, 2023 |
| Intel         | D945GNT AAC96315-405        | [58c99c07a6](https://linux-hardware.org/?probe=58c99c07a6) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | [97ef9205b5](https://linux-hardware.org/?probe=97ef9205b5) | Mar 17, 2023 |
| ASUSTek       | PRIME B250M-K               | [244382a7f5](https://linux-hardware.org/?probe=244382a7f5) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [fd875a6058](https://linux-hardware.org/?probe=fd875a6058) | Mar 16, 2023 |
| Dell          | 0VRWRC A00                  | [2159ca2389](https://linux-hardware.org/?probe=2159ca2389) | Mar 16, 2023 |
| ASUSTek       | P7H57D-V EVO                | [f93f85e76d](https://linux-hardware.org/?probe=f93f85e76d) | Mar 16, 2023 |
| Biostar       | H610MH                      | [6b367d747d](https://linux-hardware.org/?probe=6b367d747d) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [9e172b266b](https://linux-hardware.org/?probe=9e172b266b) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e6d8cd5424](https://linux-hardware.org/?probe=e6d8cd5424) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [dfe927cc13](https://linux-hardware.org/?probe=dfe927cc13) | Mar 15, 2023 |
| ASRock        | Z77 Extreme3                | [e128413357](https://linux-hardware.org/?probe=e128413357) | Mar 15, 2023 |
| ECS           | K8M890M-M                   | [f38e796f51](https://linux-hardware.org/?probe=f38e796f51) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| Gigabyte      | H55-UD3H                    | [bd69e8e59c](https://linux-hardware.org/?probe=bd69e8e59c) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| ASUSTek       | PRIME Z370-P                | [82e7940a77](https://linux-hardware.org/?probe=82e7940a77) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| ASUSTek       | P5Q SE2                     | [4f76198c2d](https://linux-hardware.org/?probe=4f76198c2d) | Mar 15, 2023 |
| MSI           | H61M-P20                    | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| Gigabyte      | B450M S2H                   | [31a56518c3](https://linux-hardware.org/?probe=31a56518c3) | Mar 14, 2023 |
| Gigabyte      | GA-A55M-S2V                 | [25f7fa6e96](https://linux-hardware.org/?probe=25f7fa6e96) | Mar 14, 2023 |
| ASRock        | H55M Pro                    | [fe7531d450](https://linux-hardware.org/?probe=fe7531d450) | Mar 14, 2023 |
| MSI           | 770-C45                     | [ec1fc57db4](https://linux-hardware.org/?probe=ec1fc57db4) | Mar 14, 2023 |
| ASUSTek       | P5K                         | [2257feac11](https://linux-hardware.org/?probe=2257feac11) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| HP            | 0B4Ch D                     | [a26dff699b](https://linux-hardware.org/?probe=a26dff699b) | Mar 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ac3240d021](https://linux-hardware.org/?probe=ac3240d021) | Mar 14, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | [11056484c3](https://linux-hardware.org/?probe=11056484c3) | Mar 13, 2023 |
| Gigabyte      | B550 GAMING X V2            | [72f5663d9d](https://linux-hardware.org/?probe=72f5663d9d) | Mar 13, 2023 |
| Intel         | X79                         | [ae742c13ae](https://linux-hardware.org/?probe=ae742c13ae) | Mar 13, 2023 |
| Gigabyte      | X570 GAMING X               | [d4ebb8d458](https://linux-hardware.org/?probe=d4ebb8d458) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | [47b6690dc8](https://linux-hardware.org/?probe=47b6690dc8) | Mar 13, 2023 |
| ASRock        | H61M-DGS                    | [7c7bdc15fe](https://linux-hardware.org/?probe=7c7bdc15fe) | Mar 13, 2023 |
| ASUSTek       | H110M-K                     | [d0e82a7ba0](https://linux-hardware.org/?probe=d0e82a7ba0) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| ASUSTek       | B75M-A                      | [8ca3a8801d](https://linux-hardware.org/?probe=8ca3a8801d) | Mar 13, 2023 |
| MSI           | H61M-P32/W8                 | [9eefe8ac8e](https://linux-hardware.org/?probe=9eefe8ac8e) | Mar 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Foxconn       | nT-330i                     | [e4b99289c7](https://linux-hardware.org/?probe=e4b99289c7) | Mar 13, 2023 |
| Gigabyte      | B450 AORUS M                | [94a2a9b97a](https://linux-hardware.org/?probe=94a2a9b97a) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| ECS           | K8M890M-M                   | [5adfeea7d1](https://linux-hardware.org/?probe=5adfeea7d1) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [3103d0f0c2](https://linux-hardware.org/?probe=3103d0f0c2) | Mar 12, 2023 |
| Fujitsu       | D2778-D1 S26361-D2778-D1    | [092aec6abe](https://linux-hardware.org/?probe=092aec6abe) | Mar 12, 2023 |
| Gigabyte      | 8IR533                      | [ee9bb6485a](https://linux-hardware.org/?probe=ee9bb6485a) | Mar 12, 2023 |
| Gigabyte      | 8IR533                      | [9e5837ddaf](https://linux-hardware.org/?probe=9e5837ddaf) | Mar 12, 2023 |
| Gigabyte      | B365M H                     | [1f3f97f186](https://linux-hardware.org/?probe=1f3f97f186) | Mar 12, 2023 |
| ASUSTek       | P8B75-M LE                  | [cb6d3a8371](https://linux-hardware.org/?probe=cb6d3a8371) | Mar 12, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [b1df269b3c](https://linux-hardware.org/?probe=b1df269b3c) | Mar 12, 2023 |
| ASRock        | AB350M-HDV                  | [45a5fbc5e7](https://linux-hardware.org/?probe=45a5fbc5e7) | Mar 12, 2023 |
| Gigabyte      | H55M-USB3                   | [3633c704cc](https://linux-hardware.org/?probe=3633c704cc) | Mar 11, 2023 |
| Gigabyte      | H55M-USB3                   | [c249ea9094](https://linux-hardware.org/?probe=c249ea9094) | Mar 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [70fe849438](https://linux-hardware.org/?probe=70fe849438) | Mar 11, 2023 |
| Biostar       | TB250-BTC                   | [59d148cedc](https://linux-hardware.org/?probe=59d148cedc) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [c3c00e99aa](https://linux-hardware.org/?probe=c3c00e99aa) | Mar 11, 2023 |
| Gigabyte      | 970A-UD3P                   | [2da8e75f5c](https://linux-hardware.org/?probe=2da8e75f5c) | Mar 11, 2023 |
| ASUSTek       | P5QL/EPU                    | [ccd888c89f](https://linux-hardware.org/?probe=ccd888c89f) | Mar 10, 2023 |
| MSI           | B450I GAMING PLUS AC        | [502bf5911c](https://linux-hardware.org/?probe=502bf5911c) | Mar 10, 2023 |
| Gigabyte      | A520I AC                    | [f1e983c2dc](https://linux-hardware.org/?probe=f1e983c2dc) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| ASUSTek       | PRIME H510M-R               | [058f4d66e2](https://linux-hardware.org/?probe=058f4d66e2) | Mar 10, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c59f1b8832](https://linux-hardware.org/?probe=c59f1b8832) | Mar 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [fb2f4741e9](https://linux-hardware.org/?probe=fb2f4741e9) | Mar 10, 2023 |
| Gigabyte      | 965GM-S2                    | [8a58676b8d](https://linux-hardware.org/?probe=8a58676b8d) | Mar 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [9260aaddc7](https://linux-hardware.org/?probe=9260aaddc7) | Mar 10, 2023 |
| Gigabyte      | 965GM-S2                    | [e514c2892e](https://linux-hardware.org/?probe=e514c2892e) | Mar 10, 2023 |
| ASUSTek       | PRIME B450M-A               | [ceb2734b56](https://linux-hardware.org/?probe=ceb2734b56) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| Gigabyte      | B560M AORUS PRO             | [9442ced293](https://linux-hardware.org/?probe=9442ced293) | Mar 09, 2023 |
| Intel         | SKYBAY                      | [226b8468d4](https://linux-hardware.org/?probe=226b8468d4) | Mar 09, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | [271d259059](https://linux-hardware.org/?probe=271d259059) | Mar 08, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | [4cb9932b91](https://linux-hardware.org/?probe=4cb9932b91) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [cefdfde063](https://linux-hardware.org/?probe=cefdfde063) | Mar 08, 2023 |
| ASRock        | B450 Gaming K4              | [ef22a14cc5](https://linux-hardware.org/?probe=ef22a14cc5) | Mar 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a84a348f29](https://linux-hardware.org/?probe=a84a348f29) | Mar 08, 2023 |
| Gigabyte      | GA-M55PLUS-S3G              | [dfd0b3e3de](https://linux-hardware.org/?probe=dfd0b3e3de) | Mar 08, 2023 |
| Gigabyte      | H170-HD3-CF                 | [5785eede0a](https://linux-hardware.org/?probe=5785eede0a) | Mar 08, 2023 |
| Gigabyte      | 8IPE1000-G                  | [58d94793e2](https://linux-hardware.org/?probe=58d94793e2) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [38c0ccd72e](https://linux-hardware.org/?probe=38c0ccd72e) | Mar 08, 2023 |
| Gigabyte      | P35-DS3L                    | [246f8d46b3](https://linux-hardware.org/?probe=246f8d46b3) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [c4c9827316](https://linux-hardware.org/?probe=c4c9827316) | Mar 08, 2023 |
| ASUSTek       | P5Q-EM                      | [371913da58](https://linux-hardware.org/?probe=371913da58) | Mar 08, 2023 |
| ASRock        | 890GX Extreme3              | [4d59bfb158](https://linux-hardware.org/?probe=4d59bfb158) | Mar 08, 2023 |
| MSI           | A320M-A PRO                 | [ce2373e31a](https://linux-hardware.org/?probe=ce2373e31a) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | B450-A PRO MAX              | [55883b5a5d](https://linux-hardware.org/?probe=55883b5a5d) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [887c698c7d](https://linux-hardware.org/?probe=887c698c7d) | Mar 07, 2023 |
| MSI           | X470 GAMING PRO MAX         | [eada75807b](https://linux-hardware.org/?probe=eada75807b) | Mar 07, 2023 |
| ASUSTek       | H110M-R                     | [d62a6bc830](https://linux-hardware.org/?probe=d62a6bc830) | Mar 07, 2023 |
| Dell          | 0Y5DDC A00                  | [46fa342e07](https://linux-hardware.org/?probe=46fa342e07) | Mar 07, 2023 |
| HP            | 8599                        | [2b9bd0b4a7](https://linux-hardware.org/?probe=2b9bd0b4a7) | Mar 07, 2023 |
| ASUSTek       | Z97-PRO                     | [3cd613e991](https://linux-hardware.org/?probe=3cd613e991) | Mar 07, 2023 |
| ASUSTek       | Z97-PRO                     | [37e53b9cd0](https://linux-hardware.org/?probe=37e53b9cd0) | Mar 07, 2023 |
| DEPO Compu... | DPH410S                     | [5fb80da27b](https://linux-hardware.org/?probe=5fb80da27b) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX/1333                | [ccb99906a8](https://linux-hardware.org/?probe=ccb99906a8) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| MSI           | G41M-P33 Combo              | [a78a4114e6](https://linux-hardware.org/?probe=a78a4114e6) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [388d4b38c1](https://linux-hardware.org/?probe=388d4b38c1) | Mar 06, 2023 |
| ASUSTek       | P5GC-MX/1333                | [6d97e48a7e](https://linux-hardware.org/?probe=6d97e48a7e) | Mar 06, 2023 |
| ASRock        | H61M-DGS                    | [8741c0e2f1](https://linux-hardware.org/?probe=8741c0e2f1) | Mar 06, 2023 |
| EPoX Compu... | MCP61S DDR2: AGF6110-M S... | [537087cc72](https://linux-hardware.org/?probe=537087cc72) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-K               | [9e1f0243d7](https://linux-hardware.org/?probe=9e1f0243d7) | Mar 06, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [2c8192e064](https://linux-hardware.org/?probe=2c8192e064) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [2891c31951](https://linux-hardware.org/?probe=2891c31951) | Mar 06, 2023 |
| EPoX Compu... | NF550/570 DDR2: AF550/57... | [de616ef63b](https://linux-hardware.org/?probe=de616ef63b) | Mar 06, 2023 |
| Huanan        | X99-TF                      | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| ASRock        | H110M-DGS R3.0              | [4b3689dc5c](https://linux-hardware.org/?probe=4b3689dc5c) | Mar 05, 2023 |
| ASRock        | X470 Gaming K4              | [3884dbf23c](https://linux-hardware.org/?probe=3884dbf23c) | Mar 05, 2023 |
| ASRock        | X470 Gaming K4              | [36b6cd2a7e](https://linux-hardware.org/?probe=36b6cd2a7e) | Mar 05, 2023 |
| Shuttle       | XS35V3                      | [1f391b4852](https://linux-hardware.org/?probe=1f391b4852) | Mar 05, 2023 |
| Gigabyte      | P41-ES3G                    | [ae657140ba](https://linux-hardware.org/?probe=ae657140ba) | Mar 05, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [93b1720fa7](https://linux-hardware.org/?probe=93b1720fa7) | Mar 05, 2023 |
| ASUSTek       | P8H61                       | [a5212119dc](https://linux-hardware.org/?probe=a5212119dc) | Mar 05, 2023 |
| Gigabyte      | H510M H                     | [9eeb7d071e](https://linux-hardware.org/?probe=9eeb7d071e) | Mar 05, 2023 |
| Biostar       | A320MH                      | [f4701d1a66](https://linux-hardware.org/?probe=f4701d1a66) | Mar 05, 2023 |
| Dell          | 0T1D10 A01                  | [e42a2e580a](https://linux-hardware.org/?probe=e42a2e580a) | Mar 05, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [8555857264](https://linux-hardware.org/?probe=8555857264) | Mar 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [17da5ff761](https://linux-hardware.org/?probe=17da5ff761) | Mar 05, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [b51b70bc1a](https://linux-hardware.org/?probe=b51b70bc1a) | Mar 05, 2023 |
| Gigabyte      | Z370M D3H-CF                | [d000dc6718](https://linux-hardware.org/?probe=d000dc6718) | Mar 04, 2023 |
| Gigabyte      | H110M-D3H R2-CF             | [35866f074d](https://linux-hardware.org/?probe=35866f074d) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| Gigabyte      | H55M-S2H                    | [545e7119e9](https://linux-hardware.org/?probe=545e7119e9) | Mar 04, 2023 |
| ASUSTek       | P5G41-M LX2/GB              | [b00bb9faf9](https://linux-hardware.org/?probe=b00bb9faf9) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9627dbdadf](https://linux-hardware.org/?probe=9627dbdadf) | Mar 04, 2023 |
| Huanan        | X99-QD4 V1.0                | [17889079ab](https://linux-hardware.org/?probe=17889079ab) | Mar 04, 2023 |
| Gigabyte      | P41-ES3G                    | [dfd94da97c](https://linux-hardware.org/?probe=dfd94da97c) | Mar 03, 2023 |
| Gigabyte      | B450 AORUS M                | [3603a535a3](https://linux-hardware.org/?probe=3603a535a3) | Mar 03, 2023 |
| Gigabyte      | B450 AORUS M                | [b43557ffd3](https://linux-hardware.org/?probe=b43557ffd3) | Mar 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [dd9492dd43](https://linux-hardware.org/?probe=dd9492dd43) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASRock        | Z68 Extreme7 Gen3           | [133f8a8bef](https://linux-hardware.org/?probe=133f8a8bef) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [ae8815c871](https://linux-hardware.org/?probe=ae8815c871) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Gigabyte      | B75M-HD3                    | [c76495f7b0](https://linux-hardware.org/?probe=c76495f7b0) | Mar 03, 2023 |
| ASUSTek       | F2A55-M LE                  | [47c7f6e38d](https://linux-hardware.org/?probe=47c7f6e38d) | Mar 03, 2023 |
| MSI           | 970A SLI Krait Edition      | [55b187db64](https://linux-hardware.org/?probe=55b187db64) | Mar 03, 2023 |
| Intel         | D945GNT AAC96315-405        | [0d02616013](https://linux-hardware.org/?probe=0d02616013) | Mar 03, 2023 |
| ASUSTek       | PRIME B250M-K               | [e9b7260885](https://linux-hardware.org/?probe=e9b7260885) | Mar 03, 2023 |
| MSI           | 970A SLI Krait Edition      | [db674213ce](https://linux-hardware.org/?probe=db674213ce) | Mar 03, 2023 |
| Huanan        | X99-F8D V2.4                | [e260724901](https://linux-hardware.org/?probe=e260724901) | Mar 03, 2023 |
| ASUSTek       | PRIME Z370-P II             | [771fd25f9d](https://linux-hardware.org/?probe=771fd25f9d) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| ASUSTek       | PRIME H310M-K               | [8c7ab87113](https://linux-hardware.org/?probe=8c7ab87113) | Mar 02, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2485632618](https://linux-hardware.org/?probe=2485632618) | Mar 02, 2023 |
| ASRock        | H510M-HVS R2.0              | [9acee9d7d4](https://linux-hardware.org/?probe=9acee9d7d4) | Mar 02, 2023 |
| AZW           | SEi                         | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [ea9a7523dc](https://linux-hardware.org/?probe=ea9a7523dc) | Mar 01, 2023 |
| ASUSTek       | AT4NM10T-I                  | [ca09a29082](https://linux-hardware.org/?probe=ca09a29082) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0a096e93c1](https://linux-hardware.org/?probe=0a096e93c1) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | [ee3aeec484](https://linux-hardware.org/?probe=ee3aeec484) | Mar 01, 2023 |
| Biostar       | A320MH                      | [d1f48d6cab](https://linux-hardware.org/?probe=d1f48d6cab) | Mar 01, 2023 |
| HP            | 83F3                        | [67f6266111](https://linux-hardware.org/?probe=67f6266111) | Mar 01, 2023 |
| Gigabyte      | H61M-S1                     | [a37a935237](https://linux-hardware.org/?probe=a37a935237) | Mar 01, 2023 |
| Aquarius      | AQB560M                     | [fedd6483cd](https://linux-hardware.org/?probe=fedd6483cd) | Mar 01, 2023 |
| ASRock        | 760GM-HDV                   | [c420a55609](https://linux-hardware.org/?probe=c420a55609) | Feb 28, 2023 |
| ASRock        | B550M Steel Legend          | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LE                  | [69713a19ea](https://linux-hardware.org/?probe=69713a19ea) | Feb 28, 2023 |
| HP            | ProLiant ML350 G5           | [073427bc3c](https://linux-hardware.org/?probe=073427bc3c) | Feb 28, 2023 |
| HP            | ProLiant ML350 Gen9         | [bbad31d175](https://linux-hardware.org/?probe=bbad31d175) | Feb 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [19fd766ea6](https://linux-hardware.org/?probe=19fd766ea6) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [17fcfc2758](https://linux-hardware.org/?probe=17fcfc2758) | Feb 28, 2023 |
| Aquarius      | AQB560M                     | [ee0c530562](https://linux-hardware.org/?probe=ee0c530562) | Feb 28, 2023 |
| AZW           | MINI S                      | [e65b0d1ef6](https://linux-hardware.org/?probe=e65b0d1ef6) | Feb 28, 2023 |
| Gigabyte      | P31-ES3G                    | [5ab1863f2b](https://linux-hardware.org/?probe=5ab1863f2b) | Feb 28, 2023 |
| Gigabyte      | H61M-DS2                    | [49205269e7](https://linux-hardware.org/?probe=49205269e7) | Feb 28, 2023 |
| ASUSTek       | P8B75-V                     | [cf4c7357eb](https://linux-hardware.org/?probe=cf4c7357eb) | Feb 28, 2023 |
| Foxconn       | 2ABF                        | [d6eb6b4839](https://linux-hardware.org/?probe=d6eb6b4839) | Feb 28, 2023 |
| MSI           | MS-7210 100                 | [5cb2d5ea2c](https://linux-hardware.org/?probe=5cb2d5ea2c) | Feb 28, 2023 |
| MSI           | MS-7210 100                 | [a541b48e4d](https://linux-hardware.org/?probe=a541b48e4d) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [882168458c](https://linux-hardware.org/?probe=882168458c) | Feb 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [e4bb117847](https://linux-hardware.org/?probe=e4bb117847) | Feb 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | [732f6c8c00](https://linux-hardware.org/?probe=732f6c8c00) | Feb 27, 2023 |
| MSI           | NF750-G55                   | [f279251ffa](https://linux-hardware.org/?probe=f279251ffa) | Feb 27, 2023 |
| ASUSTek       | P7H55                       | [394ad3d24f](https://linux-hardware.org/?probe=394ad3d24f) | Feb 27, 2023 |
| Aquarius      | AQH310CM                    | [a2f4d0f77e](https://linux-hardware.org/?probe=a2f4d0f77e) | Feb 27, 2023 |
| Gigabyte      | B365M D2V                   | [aa39313621](https://linux-hardware.org/?probe=aa39313621) | Feb 27, 2023 |
| ASUSTek       | P8B75-V                     | [7a8e478900](https://linux-hardware.org/?probe=7a8e478900) | Feb 27, 2023 |
| Gigabyte      | B365M H                     | [dbb3e73c89](https://linux-hardware.org/?probe=dbb3e73c89) | Feb 27, 2023 |
| Dell          | 0Y5DDC A00                  | [e3090d9725](https://linux-hardware.org/?probe=e3090d9725) | Feb 27, 2023 |
| ASUSTek       | H61M-E                      | [ee5b36d127](https://linux-hardware.org/?probe=ee5b36d127) | Feb 27, 2023 |
| Gigabyte      | B550M AORUS PRO             | [ffdac8fa88](https://linux-hardware.org/?probe=ffdac8fa88) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| ASUSTek       | PRIME B250-PLUS             | [49b1cd5754](https://linux-hardware.org/?probe=49b1cd5754) | Feb 26, 2023 |
| ASUSTek       | Z97-K                       | [77a5832b3f](https://linux-hardware.org/?probe=77a5832b3f) | Feb 26, 2023 |
| MSI           | Z77A-G43                    | [2fe5c30b13](https://linux-hardware.org/?probe=2fe5c30b13) | Feb 26, 2023 |
| MSI           | Z77A-G43                    | [4b96538701](https://linux-hardware.org/?probe=4b96538701) | Feb 26, 2023 |
| ASRock        | 880GM-LE                    | [32366172e4](https://linux-hardware.org/?probe=32366172e4) | Feb 26, 2023 |
| Unknown       | Intel X79                   | [0f7920afd6](https://linux-hardware.org/?probe=0f7920afd6) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| Gigabyte      | H310M D3H                   | [058fac57c2](https://linux-hardware.org/?probe=058fac57c2) | Feb 25, 2023 |
| Unknown       | Unknown                     | [b4e0540b00](https://linux-hardware.org/?probe=b4e0540b00) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [585e02a6dc](https://linux-hardware.org/?probe=585e02a6dc) | Feb 25, 2023 |
| ASUSTek       | H81M-E                      | [25a3002df1](https://linux-hardware.org/?probe=25a3002df1) | Feb 25, 2023 |
| MSI           | B350M PRO-VDH               | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| HP            | 1497                        | [ebf580cb5d](https://linux-hardware.org/?probe=ebf580cb5d) | Feb 24, 2023 |
| ASUSTek       | P5B                         | [60cb8319db](https://linux-hardware.org/?probe=60cb8319db) | Feb 24, 2023 |
| ASUSTek       | P5Q-EM                      | [3fef9c126a](https://linux-hardware.org/?probe=3fef9c126a) | Feb 24, 2023 |
| ASRock        | 760GM-GS3                   | [5440ad3270](https://linux-hardware.org/?probe=5440ad3270) | Feb 24, 2023 |
| ASRock        | N68C-GS FX                  | [6b7b16645d](https://linux-hardware.org/?probe=6b7b16645d) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [1989031eb6](https://linux-hardware.org/?probe=1989031eb6) | Feb 24, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [b410c9f493](https://linux-hardware.org/?probe=b410c9f493) | Feb 24, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [21aa20cd64](https://linux-hardware.org/?probe=21aa20cd64) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [4cddc9362b](https://linux-hardware.org/?probe=4cddc9362b) | Feb 23, 2023 |
| MSI           | B450M GAMING PLUS           | [accb966ada](https://linux-hardware.org/?probe=accb966ada) | Feb 23, 2023 |
| ASUSTek       | P5K                         | [f564dd9ac5](https://linux-hardware.org/?probe=f564dd9ac5) | Feb 23, 2023 |
| Gigabyte      | GA-970A-D3                  | [8b1222a755](https://linux-hardware.org/?probe=8b1222a755) | Feb 23, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [cfe5ecec44](https://linux-hardware.org/?probe=cfe5ecec44) | Feb 23, 2023 |
| Gigabyte      | H61M-S1                     | [ca76e62a1e](https://linux-hardware.org/?probe=ca76e62a1e) | Feb 23, 2023 |
| ASUSTek       | P5K                         | [1769888b2b](https://linux-hardware.org/?probe=1769888b2b) | Feb 23, 2023 |
| MSI           | G31TM-P21                   | [7d6e4cd766](https://linux-hardware.org/?probe=7d6e4cd766) | Feb 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [640957cabe](https://linux-hardware.org/?probe=640957cabe) | Feb 23, 2023 |
| ASUSTek       | PRIME H510M-K               | [3dab1052d4](https://linux-hardware.org/?probe=3dab1052d4) | Feb 22, 2023 |
| Unknown       | NF-CK804                    | [3dd6239815](https://linux-hardware.org/?probe=3dd6239815) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [feea587fef](https://linux-hardware.org/?probe=feea587fef) | Feb 22, 2023 |
| ASUSTek       | P7H55-M/USB3                | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| ASUSTek       | P8H61-M LX3                 | [af3c7b2459](https://linux-hardware.org/?probe=af3c7b2459) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [fb050eaf3c](https://linux-hardware.org/?probe=fb050eaf3c) | Feb 22, 2023 |
| ASRock        | B450M Pro4                  | [f245e79c04](https://linux-hardware.org/?probe=f245e79c04) | Feb 22, 2023 |
| ASRock        | B450M Pro4                  | [2e1d1c3117](https://linux-hardware.org/?probe=2e1d1c3117) | Feb 22, 2023 |
| MSI           | GF615M-P33                  | [c9cad5f4fa](https://linux-hardware.org/?probe=c9cad5f4fa) | Feb 22, 2023 |
| ASUSTek       | P8B75-M LE                  | [fa3e62fdef](https://linux-hardware.org/?probe=fa3e62fdef) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| ASUSTek       | P8B75-V                     | [de56e36164](https://linux-hardware.org/?probe=de56e36164) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | [f511e61852](https://linux-hardware.org/?probe=f511e61852) | Feb 21, 2023 |
| Lenovo        | ThinkCentre M91p 4524PL4    | [5cda5522e8](https://linux-hardware.org/?probe=5cda5522e8) | Feb 21, 2023 |
| Intel         | DH61CR AAG14064-204         | [eec6e2f905](https://linux-hardware.org/?probe=eec6e2f905) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | [2ea45a0d80](https://linux-hardware.org/?probe=2ea45a0d80) | Feb 21, 2023 |
| ASUSTek       | Z97-K                       | [132a805814](https://linux-hardware.org/?probe=132a805814) | Feb 20, 2023 |
| ASUSTek       | Z97-K                       | [59931c7434](https://linux-hardware.org/?probe=59931c7434) | Feb 20, 2023 |
| MSI           | A320M PRO-E                 | [3e441c86f1](https://linux-hardware.org/?probe=3e441c86f1) | Feb 20, 2023 |
| ASUSTek       | B85M-G                      | [501a95ac36](https://linux-hardware.org/?probe=501a95ac36) | Feb 20, 2023 |
| Huanan        | X99 F8D V2.2                | [c9d8617e08](https://linux-hardware.org/?probe=c9d8617e08) | Feb 20, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [29758ea823](https://linux-hardware.org/?probe=29758ea823) | Feb 20, 2023 |
| Intel         | X79M-S                      | [89ac8fc3ce](https://linux-hardware.org/?probe=89ac8fc3ce) | Feb 20, 2023 |
| ASUSTek       | P8H61-M LX3                 | [509f76c7ec](https://linux-hardware.org/?probe=509f76c7ec) | Feb 20, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [45e185354c](https://linux-hardware.org/?probe=45e185354c) | Feb 20, 2023 |
| Gigabyte      | MRHM3AP                     | [9f4978d79f](https://linux-hardware.org/?probe=9f4978d79f) | Feb 19, 2023 |
| Gigabyte      | H61M-S1                     | [82ab7aabe2](https://linux-hardware.org/?probe=82ab7aabe2) | Feb 19, 2023 |
| AZW           | GK55                        | [e8376dbc54](https://linux-hardware.org/?probe=e8376dbc54) | Feb 19, 2023 |
| ASRock        | 870 Extreme3 R2.0           | [68c2299161](https://linux-hardware.org/?probe=68c2299161) | Feb 19, 2023 |
| Gigabyte      | P85-D3                      | [970f04658e](https://linux-hardware.org/?probe=970f04658e) | Feb 19, 2023 |
| Gigabyte      | P85-D3                      | [331f606733](https://linux-hardware.org/?probe=331f606733) | Feb 19, 2023 |
| ASRock        | AB350 Pro4                  | [0f1365d8d8](https://linux-hardware.org/?probe=0f1365d8d8) | Feb 19, 2023 |
| Dell          | 0Y5DDC A00                  | [87c921a93a](https://linux-hardware.org/?probe=87c921a93a) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0c6f21a56e](https://linux-hardware.org/?probe=0c6f21a56e) | Feb 18, 2023 |
| ASUSTek       | P5Q SE2                     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| Gigabyte      | H410M S2H                   | [bdb8c0094b](https://linux-hardware.org/?probe=bdb8c0094b) | Feb 18, 2023 |
| OEM           | Intel H81                   | [2dc44e8ff2](https://linux-hardware.org/?probe=2dc44e8ff2) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Intel         | DP965LT AAD41694-206        | [2744ec3c4a](https://linux-hardware.org/?probe=2744ec3c4a) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| ASUSTek       | H170 PRO GAMING             | [e85ff6e5c3](https://linux-hardware.org/?probe=e85ff6e5c3) | Feb 18, 2023 |
| Gigabyte      | MRHM3AP                     | [a427da167b](https://linux-hardware.org/?probe=a427da167b) | Feb 18, 2023 |
| ASRock        | Z690 Pro RS                 | [68dcf39492](https://linux-hardware.org/?probe=68dcf39492) | Feb 18, 2023 |
| Biostar       | H61MLB                      | [b79584c7c9](https://linux-hardware.org/?probe=b79584c7c9) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [46289356fa](https://linux-hardware.org/?probe=46289356fa) | Feb 18, 2023 |
| OEM           | Unknown                     | [90c705ee6b](https://linux-hardware.org/?probe=90c705ee6b) | Feb 17, 2023 |
| Gigabyte      | G31M-S2L                    | [78e184862a](https://linux-hardware.org/?probe=78e184862a) | Feb 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | [55a53738ee](https://linux-hardware.org/?probe=55a53738ee) | Feb 17, 2023 |
| MSI           | B460M PRO-VDH               | [38f8f579be](https://linux-hardware.org/?probe=38f8f579be) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0d5eded653](https://linux-hardware.org/?probe=0d5eded653) | Feb 17, 2023 |
| ASUSTek       | P5G41-M LX                  | [0a174dcd20](https://linux-hardware.org/?probe=0a174dcd20) | Feb 17, 2023 |
| ASUSTek       | H110M-R                     | [bd6636c99d](https://linux-hardware.org/?probe=bd6636c99d) | Feb 17, 2023 |
| HP            | 18E7                        | [2c779d2395](https://linux-hardware.org/?probe=2c779d2395) | Feb 17, 2023 |
| Gigabyte      | B360M DS3H                  | [1ceaa9af7d](https://linux-hardware.org/?probe=1ceaa9af7d) | Feb 17, 2023 |
| iRU           | v1.0                        | [9d70818485](https://linux-hardware.org/?probe=9d70818485) | Feb 17, 2023 |
| ASRock        | 760GM-GS3                   | [88433e4e24](https://linux-hardware.org/?probe=88433e4e24) | Feb 16, 2023 |
| ASRock        | X370 Gaming X               | [cda38b5b9b](https://linux-hardware.org/?probe=cda38b5b9b) | Feb 16, 2023 |
| Gigabyte      | H410M S2 V3                 | [0dbeeea38c](https://linux-hardware.org/?probe=0dbeeea38c) | Feb 16, 2023 |
| ASUSTek       | P7H55-M SI                  | [387881f288](https://linux-hardware.org/?probe=387881f288) | Feb 16, 2023 |
| Intel         | DP67BA AAG10219-300         | [8fc0c69640](https://linux-hardware.org/?probe=8fc0c69640) | Feb 16, 2023 |
| ASUSTek       | H81T                        | [51aa090e9a](https://linux-hardware.org/?probe=51aa090e9a) | Feb 16, 2023 |
| MSI           | G41M-P28                    | [85efceb14b](https://linux-hardware.org/?probe=85efceb14b) | Feb 16, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b19c73e236](https://linux-hardware.org/?probe=b19c73e236) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| Gigabyte      | EP43-S3L                    | [82730ed699](https://linux-hardware.org/?probe=82730ed699) | Feb 15, 2023 |
| ASRock        | N68C-GS FX                  | [bc0fe319be](https://linux-hardware.org/?probe=bc0fe319be) | Feb 15, 2023 |
| ASUSTek       | Z170-PRO                    | [bd408485b0](https://linux-hardware.org/?probe=bd408485b0) | Feb 15, 2023 |
| ASRock        | Z77 Pro3                    | [095671c1c9](https://linux-hardware.org/?probe=095671c1c9) | Feb 15, 2023 |
| ASRock        | H61M-DGS                    | [9716d5ed72](https://linux-hardware.org/?probe=9716d5ed72) | Feb 15, 2023 |
| MSI           | MS-7357                     | [84cadfbabc](https://linux-hardware.org/?probe=84cadfbabc) | Feb 15, 2023 |
| ASUSTek       | PRIME B365M-K               | [20b88dda19](https://linux-hardware.org/?probe=20b88dda19) | Feb 15, 2023 |
| Dell          | 0Y5DDC A00                  | [261e3ca363](https://linux-hardware.org/?probe=261e3ca363) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Unknown       | X79A                        | [4cf2d15d70](https://linux-hardware.org/?probe=4cf2d15d70) | Feb 14, 2023 |
| ASUSTek       | P9X79                       | [d7f1d6a937](https://linux-hardware.org/?probe=d7f1d6a937) | Feb 14, 2023 |
| MAINBRD       | OPS62A-SHA                  | [a9267dffac](https://linux-hardware.org/?probe=a9267dffac) | Feb 14, 2023 |
| Gigabyte      | Z87-HD3                     | [e856a4629d](https://linux-hardware.org/?probe=e856a4629d) | Feb 14, 2023 |
| Gigabyte      | B450M H                     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| ASRock        | AQH410T                     | [9ca03a8dcd](https://linux-hardware.org/?probe=9ca03a8dcd) | Feb 14, 2023 |
| Intel         | X99 V1.0                    | [0bfbfe2876](https://linux-hardware.org/?probe=0bfbfe2876) | Feb 14, 2023 |
| Gigabyte      | GA-990XA-UD3                | [da50295fcc](https://linux-hardware.org/?probe=da50295fcc) | Feb 14, 2023 |
| ICL           | H410SB                      | [e994f10643](https://linux-hardware.org/?probe=e994f10643) | Feb 14, 2023 |
| Gigabyte      | B450M S2H                   | [2120a2f3b5](https://linux-hardware.org/?probe=2120a2f3b5) | Feb 13, 2023 |
| Gigabyte      | B450M DS3H V2               | [6338542845](https://linux-hardware.org/?probe=6338542845) | Feb 13, 2023 |
| ASUSTek       | P7P55D-E EVO                | [f1ec250753](https://linux-hardware.org/?probe=f1ec250753) | Feb 13, 2023 |
| MSI           | PRO B660M-E DDR4            | [aab30259f8](https://linux-hardware.org/?probe=aab30259f8) | Feb 13, 2023 |
| Gigabyte      | H510M S2H V2                | [e3580e73af](https://linux-hardware.org/?probe=e3580e73af) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| MSI           | H97 GAMING 3                | [855634fadc](https://linux-hardware.org/?probe=855634fadc) | Feb 13, 2023 |
| Biostar       | A320MH                      | [d51405079c](https://linux-hardware.org/?probe=d51405079c) | Feb 13, 2023 |
| ASUSTek       | M2N-E SLI                   | [8bf6aedf43](https://linux-hardware.org/?probe=8bf6aedf43) | Feb 12, 2023 |
| Huanan        | X99 F8D V2.2                | [7b98ade6b1](https://linux-hardware.org/?probe=7b98ade6b1) | Feb 12, 2023 |
| ASRock        | B450M Pro4                  | [8f60713f8a](https://linux-hardware.org/?probe=8f60713f8a) | Feb 12, 2023 |
| Gigabyte      | B550M DS3H                  | [06dc671402](https://linux-hardware.org/?probe=06dc671402) | Feb 12, 2023 |
| Gigabyte      | B450M H                     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| MSI           | MS-7369                     | [f2d9a7a428](https://linux-hardware.org/?probe=f2d9a7a428) | Feb 12, 2023 |
| MSI           | Z97 U3 PLUS                 | [12ed284f81](https://linux-hardware.org/?probe=12ed284f81) | Feb 12, 2023 |
| MSI           | 770-C45                     | [80cd4311f5](https://linux-hardware.org/?probe=80cd4311f5) | Feb 12, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| ASUSTek       | M4N78-AM                    | [26ecdbcf90](https://linux-hardware.org/?probe=26ecdbcf90) | Feb 12, 2023 |
| OEM           | Intel H81                   | [89ca7b56ce](https://linux-hardware.org/?probe=89ca7b56ce) | Feb 12, 2023 |
| Unknown       | X79A                        | [d2cdf88906](https://linux-hardware.org/?probe=d2cdf88906) | Feb 12, 2023 |
| ASRock        | X99 Professional Gaming ... | [56a6b8bb0f](https://linux-hardware.org/?probe=56a6b8bb0f) | Feb 11, 2023 |
| ASRock        | X99 Professional Gaming ... | [975e99c02f](https://linux-hardware.org/?probe=975e99c02f) | Feb 11, 2023 |
| ASUSTek       | P5B-E                       | [92bf62be3c](https://linux-hardware.org/?probe=92bf62be3c) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Gigabyte      | Z370M DS3H-CF               | [2194ea605a](https://linux-hardware.org/?probe=2194ea605a) | Feb 11, 2023 |
| Acer          | RS880M05                    | [c585589925](https://linux-hardware.org/?probe=c585589925) | Feb 11, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [0207d4f5eb](https://linux-hardware.org/?probe=0207d4f5eb) | Feb 11, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [4a3b0fd844](https://linux-hardware.org/?probe=4a3b0fd844) | Feb 11, 2023 |
| MSI           | H110M PRO-VD                | [5483d83053](https://linux-hardware.org/?probe=5483d83053) | Feb 11, 2023 |
| Huanan        | X99 F8D V2.2                | [226310e919](https://linux-hardware.org/?probe=226310e919) | Feb 10, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d88dcef939](https://linux-hardware.org/?probe=d88dcef939) | Feb 10, 2023 |
| ASUSTek       | PRIME H510M-K               | [ad01ef1c97](https://linux-hardware.org/?probe=ad01ef1c97) | Feb 10, 2023 |
| Gigabyte      | B560M DS3H V2               | [2512d8d9ab](https://linux-hardware.org/?probe=2512d8d9ab) | Feb 10, 2023 |
| MSI           | PH61-SP35                   | [ffd100018d](https://linux-hardware.org/?probe=ffd100018d) | Feb 10, 2023 |
| EPoX Compu... | nForce4 DDR: 9NPA3I / 9N... | [978c5bad53](https://linux-hardware.org/?probe=978c5bad53) | Feb 10, 2023 |
| Gigabyte      | H310M S2V x.x               | [e87d8bc37e](https://linux-hardware.org/?probe=e87d8bc37e) | Feb 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2cfb05371e](https://linux-hardware.org/?probe=2cfb05371e) | Feb 09, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [4468518165](https://linux-hardware.org/?probe=4468518165) | Feb 09, 2023 |
| MSI           | PH61-SP35                   | [579c7bc265](https://linux-hardware.org/?probe=579c7bc265) | Feb 09, 2023 |
| MSI           | H510M-A PRO                 | [dea6a1a077](https://linux-hardware.org/?probe=dea6a1a077) | Feb 09, 2023 |
| ASUSTek       | M4A785TD-M EVO              | [31d8a68d71](https://linux-hardware.org/?probe=31d8a68d71) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [2a366ac100](https://linux-hardware.org/?probe=2a366ac100) | Feb 09, 2023 |
| MSI           | X470 GAMING PRO             | [7b972f1e58](https://linux-hardware.org/?probe=7b972f1e58) | Feb 09, 2023 |
| MSI           | H97 GAMING 3                | [209d4693fe](https://linux-hardware.org/?probe=209d4693fe) | Feb 09, 2023 |
| Gigabyte      | H61M-S2PV                   | [6cd301542b](https://linux-hardware.org/?probe=6cd301542b) | Feb 09, 2023 |
| Unknown       | X99H                        | [722aafff41](https://linux-hardware.org/?probe=722aafff41) | Feb 09, 2023 |
| Huanan        | B75 V10.1 376               | [f501974f04](https://linux-hardware.org/?probe=f501974f04) | Feb 09, 2023 |
| AZW           | GTR V02                     | [739c44358c](https://linux-hardware.org/?probe=739c44358c) | Feb 08, 2023 |
| MSI           | MS-B1711                    | [9a5096ba48](https://linux-hardware.org/?probe=9a5096ba48) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [e533f4d15f](https://linux-hardware.org/?probe=e533f4d15f) | Feb 08, 2023 |
| MSI           | H110M PRO-VD PLUS           | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | Z170-P                      | [b0e0ac8815](https://linux-hardware.org/?probe=b0e0ac8815) | Feb 08, 2023 |
| Intel         | DH67CL AAG10212-208         | [e53a89d83d](https://linux-hardware.org/?probe=e53a89d83d) | Feb 08, 2023 |
| ASUSTek       | H61M-K                      | [5fc600ad0c](https://linux-hardware.org/?probe=5fc600ad0c) | Feb 08, 2023 |
| ASUSTek       | P7H55-USB3                  | [0c02735e75](https://linux-hardware.org/?probe=0c02735e75) | Feb 08, 2023 |
| ASRock        | A320M-DVS R4.0              | [8fb4060e1f](https://linux-hardware.org/?probe=8fb4060e1f) | Feb 08, 2023 |
| Gigabyte      | B85M-D3V                    | [21e3210daa](https://linux-hardware.org/?probe=21e3210daa) | Feb 08, 2023 |
| ASRock        | B450M Pro4-F                | [133f0c845d](https://linux-hardware.org/?probe=133f0c845d) | Feb 07, 2023 |
| ECS           | GF8100VM-M5                 | [9b536f16be](https://linux-hardware.org/?probe=9b536f16be) | Feb 07, 2023 |
| ASUSTek       | P7H55-USB3                  | [8d7cca4218](https://linux-hardware.org/?probe=8d7cca4218) | Feb 07, 2023 |
| Dell          | 0Y5DDC A00                  | [35c52844f5](https://linux-hardware.org/?probe=35c52844f5) | Feb 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [b6c83b73c5](https://linux-hardware.org/?probe=b6c83b73c5) | Feb 07, 2023 |
| Pegatron      | 2A73h                       | [6745d62f6e](https://linux-hardware.org/?probe=6745d62f6e) | Feb 07, 2023 |
| Gigabyte      | B365M DS3H                  | [4bc9beae71](https://linux-hardware.org/?probe=4bc9beae71) | Feb 07, 2023 |
| Gigabyte      | B450M S2H V2                | [62a01ed1f1](https://linux-hardware.org/?probe=62a01ed1f1) | Feb 07, 2023 |
| ASUSTek       | P8B75-V                     | [04d1d12416](https://linux-hardware.org/?probe=04d1d12416) | Feb 07, 2023 |
| Gigabyte      | B560 HD3                    | [ab4ab47498](https://linux-hardware.org/?probe=ab4ab47498) | Feb 06, 2023 |
| ASUSTek       | P5QL/EPU                    | [32c834326a](https://linux-hardware.org/?probe=32c834326a) | Feb 06, 2023 |
| Gigabyte      | M61SME-S2                   | [395b6fa893](https://linux-hardware.org/?probe=395b6fa893) | Feb 06, 2023 |
| Lenovo        | 3708 NOK                    | [b306f4c9dc](https://linux-hardware.org/?probe=b306f4c9dc) | Feb 06, 2023 |
| Acer          | FMCP7A-ION-LE               | [4567c6a09c](https://linux-hardware.org/?probe=4567c6a09c) | Feb 06, 2023 |
| Compal        | DIP00                       | [fc6de899ba](https://linux-hardware.org/?probe=fc6de899ba) | Feb 06, 2023 |
| Compal        | DIP00                       | [632d4c313a](https://linux-hardware.org/?probe=632d4c313a) | Feb 06, 2023 |
| ASRock        | FM2A78 Pro4+                | [788d1d408b](https://linux-hardware.org/?probe=788d1d408b) | Feb 06, 2023 |
| ASRock        | FM2A88X Extreme4+           | [97252e199d](https://linux-hardware.org/?probe=97252e199d) | Feb 06, 2023 |
| ASRock        | K10N78D                     | [f8bf09228c](https://linux-hardware.org/?probe=f8bf09228c) | Feb 06, 2023 |
| ASRock        | K10N78D                     | [8ac073e470](https://linux-hardware.org/?probe=8ac073e470) | Feb 06, 2023 |
| Gigabyte      | B85M-D3H                    | [fcf0932318](https://linux-hardware.org/?probe=fcf0932318) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | [ebe7e665d6](https://linux-hardware.org/?probe=ebe7e665d6) | Feb 05, 2023 |
| Huanan        | X79 VAA1                    | [62888124bd](https://linux-hardware.org/?probe=62888124bd) | Feb 05, 2023 |
| ASRock        | H61M-VG4                    | [b2fec94855](https://linux-hardware.org/?probe=b2fec94855) | Feb 05, 2023 |
| Quanta        | 2AC5 101                    | [fbf7122883](https://linux-hardware.org/?probe=fbf7122883) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [bdd3224e6c](https://linux-hardware.org/?probe=bdd3224e6c) | Feb 05, 2023 |
| ASUSTek       | M2N                         | [cc5d457ca6](https://linux-hardware.org/?probe=cc5d457ca6) | Feb 05, 2023 |
| ECS           | H61H2-MV                    | [e0a93d257b](https://linux-hardware.org/?probe=e0a93d257b) | Feb 05, 2023 |
| ASRock        | A75M-HVS                    | [74c7bde15c](https://linux-hardware.org/?probe=74c7bde15c) | Feb 05, 2023 |
| ASUSTek       | M4A785T-M                   | [5402edfed1](https://linux-hardware.org/?probe=5402edfed1) | Feb 04, 2023 |
| Unknown       | MZ-B75-S                    | [ed6041df37](https://linux-hardware.org/?probe=ed6041df37) | Feb 04, 2023 |
| Intel         | X99 V1.0                    | [b8de53522e](https://linux-hardware.org/?probe=b8de53522e) | Feb 04, 2023 |
| JGINYUE       | H97I GAMING V1.0            | [d83687e8ea](https://linux-hardware.org/?probe=d83687e8ea) | Feb 03, 2023 |
| Biostar       | A320MH                      | [61f708d874](https://linux-hardware.org/?probe=61f708d874) | Feb 03, 2023 |
| ASUSTek       | M5A78L LE                   | [96181fd904](https://linux-hardware.org/?probe=96181fd904) | Feb 03, 2023 |
| Gigabyte      | 990XA-UD3                   | [f26da18faa](https://linux-hardware.org/?probe=f26da18faa) | Feb 02, 2023 |
| MSI           | 770-C45                     | [fa06564503](https://linux-hardware.org/?probe=fa06564503) | Feb 02, 2023 |
| MSI           | Z87-GD65 GAMING             | [0021264c10](https://linux-hardware.org/?probe=0021264c10) | Feb 02, 2023 |
| Gigabyte      | X58A-UD3R                   | [e29b47f46f](https://linux-hardware.org/?probe=e29b47f46f) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M LE                 | [dab3550ce4](https://linux-hardware.org/?probe=dab3550ce4) | Feb 02, 2023 |
| MSI           | B450M MORTAR MAX            | [4b8bbc4d84](https://linux-hardware.org/?probe=4b8bbc4d84) | Feb 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3b016839cd](https://linux-hardware.org/?probe=3b016839cd) | Feb 02, 2023 |
| Biostar       | G41-M7                      | [862afd5a70](https://linux-hardware.org/?probe=862afd5a70) | Feb 01, 2023 |
| Gigabyte      | B560 HD3                    | [477504bfc6](https://linux-hardware.org/?probe=477504bfc6) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [19d65de9b6](https://linux-hardware.org/?probe=19d65de9b6) | Jan 31, 2023 |
| Gigabyte      | B560M H                     | [65f58e4e39](https://linux-hardware.org/?probe=65f58e4e39) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a2c87504d6](https://linux-hardware.org/?probe=a2c87504d6) | Jan 31, 2023 |
| MSI           | G41M-P28                    | [7f37c4b40e](https://linux-hardware.org/?probe=7f37c4b40e) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| Gigabyte      | A320M-H-CF                  | [f5379a55ea](https://linux-hardware.org/?probe=f5379a55ea) | Jan 31, 2023 |
| ASUSTek       | B85M-G                      | [44c2ca8150](https://linux-hardware.org/?probe=44c2ca8150) | Jan 31, 2023 |
| HP            | 8599                        | [3ffedfbc62](https://linux-hardware.org/?probe=3ffedfbc62) | Jan 31, 2023 |
| HP            | 8599                        | [759d3a0829](https://linux-hardware.org/?probe=759d3a0829) | Jan 31, 2023 |
| ASUSTek       | H110-PLUS                   | [c20a43e3e5](https://linux-hardware.org/?probe=c20a43e3e5) | Jan 31, 2023 |
| ASRock        | B650M PG Riptide            | [260d257a0c](https://linux-hardware.org/?probe=260d257a0c) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [4830eacf5e](https://linux-hardware.org/?probe=4830eacf5e) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [0b59b68d55](https://linux-hardware.org/?probe=0b59b68d55) | Jan 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [10c275723f](https://linux-hardware.org/?probe=10c275723f) | Jan 30, 2023 |
| Gigabyte      | B365M H                     | [89d336f0b7](https://linux-hardware.org/?probe=89d336f0b7) | Jan 30, 2023 |
| MSI           | H81M-P33                    | [32149d3b64](https://linux-hardware.org/?probe=32149d3b64) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 8526 MVB, A                 | [eaa1bf595f](https://linux-hardware.org/?probe=eaa1bf595f) | Jan 30, 2023 |
| MSI           | B450M-A PRO MAX             | [a7232f4811](https://linux-hardware.org/?probe=a7232f4811) | Jan 30, 2023 |
| ASUSTek       | P8Q77-M                     | [be0ebca5cc](https://linux-hardware.org/?probe=be0ebca5cc) | Jan 29, 2023 |
| HC            | HCAR357-MI V1.0             | [986dd858ba](https://linux-hardware.org/?probe=986dd858ba) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [868269808a](https://linux-hardware.org/?probe=868269808a) | Jan 29, 2023 |
| ASRock        | P45DE3                      | [e4c2e737f7](https://linux-hardware.org/?probe=e4c2e737f7) | Jan 29, 2023 |
| EVGA          | E689 $                      | [9d4b1aeaa9](https://linux-hardware.org/?probe=9d4b1aeaa9) | Jan 29, 2023 |
| ASRock        | Z77M                        | [83a27ed2b5](https://linux-hardware.org/?probe=83a27ed2b5) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS PRO              | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| ASRock        | G41M-S3                     | [2196343afa](https://linux-hardware.org/?probe=2196343afa) | Jan 29, 2023 |
| ASUSTek       | P7P55D LE                   | [943a02b7e9](https://linux-hardware.org/?probe=943a02b7e9) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | [c52b5b3357](https://linux-hardware.org/?probe=c52b5b3357) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [e768563b42](https://linux-hardware.org/?probe=e768563b42) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [97aa61aba5](https://linux-hardware.org/?probe=97aa61aba5) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [000203af81](https://linux-hardware.org/?probe=000203af81) | Jan 29, 2023 |
| MSI           | B450M MORTAR MAX            | [017467452c](https://linux-hardware.org/?probe=017467452c) | Jan 29, 2023 |
| Intel         | X79G V2.x                   | [40bc764c73](https://linux-hardware.org/?probe=40bc764c73) | Jan 28, 2023 |
| EVGA          | E689 $                      | [be99ae882b](https://linux-hardware.org/?probe=be99ae882b) | Jan 28, 2023 |
| ASRock        | X570 Taichi                 | [3b1c5df727](https://linux-hardware.org/?probe=3b1c5df727) | Jan 28, 2023 |
| AZW           | Gemini M                    | [5534667621](https://linux-hardware.org/?probe=5534667621) | Jan 28, 2023 |
| AZW           | GTR V02                     | [b1b34f10a2](https://linux-hardware.org/?probe=b1b34f10a2) | Jan 28, 2023 |
| Unknown       | X79                         | [164508bcb4](https://linux-hardware.org/?probe=164508bcb4) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8492e549e2](https://linux-hardware.org/?probe=8492e549e2) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [836e9a9809](https://linux-hardware.org/?probe=836e9a9809) | Jan 28, 2023 |
| DEPO Compu... | DPH410S                     | [d380c83ebf](https://linux-hardware.org/?probe=d380c83ebf) | Jan 28, 2023 |
| ASUSTek       | P8Z77-M                     | [22d53e86e0](https://linux-hardware.org/?probe=22d53e86e0) | Jan 28, 2023 |
| Acer          | Aspire TC-705               | [be48644835](https://linux-hardware.org/?probe=be48644835) | Jan 27, 2023 |
| ASUSTek       | M2N-MX                      | [0920c10a0e](https://linux-hardware.org/?probe=0920c10a0e) | Jan 27, 2023 |
| Gigabyte      | B85M-D3H-A                  | [8289da39ca](https://linux-hardware.org/?probe=8289da39ca) | Jan 27, 2023 |
| Gigabyte      | 970A-DS3P                   | [547e171057](https://linux-hardware.org/?probe=547e171057) | Jan 27, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| ASUSTek       | H81M-K                      | [13f23afb38](https://linux-hardware.org/?probe=13f23afb38) | Jan 27, 2023 |
| ASRock        | B450 Gaming K4              | [7ce2ff0443](https://linux-hardware.org/?probe=7ce2ff0443) | Jan 27, 2023 |
| Gigabyte      | G41MT-S2                    | [774f8eb27f](https://linux-hardware.org/?probe=774f8eb27f) | Jan 27, 2023 |
| Aquarius      | AQB560M                     | [1187e4d240](https://linux-hardware.org/?probe=1187e4d240) | Jan 27, 2023 |
| Intel         | X99                         | [1fbd6cf5bd](https://linux-hardware.org/?probe=1fbd6cf5bd) | Jan 27, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [2fea9476f5](https://linux-hardware.org/?probe=2fea9476f5) | Jan 26, 2023 |
| MSI           | 770-C45                     | [3da3ee46c2](https://linux-hardware.org/?probe=3da3ee46c2) | Jan 26, 2023 |
| Gigabyte      | G41MT-S2                    | [06cd0f5943](https://linux-hardware.org/?probe=06cd0f5943) | Jan 26, 2023 |
| ASUSTek       | P6T SE                      | [1033fae7e9](https://linux-hardware.org/?probe=1033fae7e9) | Jan 26, 2023 |
| ASRock        | B650M PG Riptide            | [e9f4894d6d](https://linux-hardware.org/?probe=e9f4894d6d) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| ASRock        | H610M-HDV/M.2               | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [4ad0b3594f](https://linux-hardware.org/?probe=4ad0b3594f) | Jan 26, 2023 |
| ASUSTek       | P7H55-M                     | [34c55ab8ae](https://linux-hardware.org/?probe=34c55ab8ae) | Jan 26, 2023 |
| iRU           | v1.0                        | [5dfa804f74](https://linux-hardware.org/?probe=5dfa804f74) | Jan 26, 2023 |
| ASUSTek       | P5E-VM SE                   | [0b25483160](https://linux-hardware.org/?probe=0b25483160) | Jan 26, 2023 |
| Intel         | X99 V1.0                    | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [883b4a1c39](https://linux-hardware.org/?probe=883b4a1c39) | Jan 26, 2023 |
| Intel         | H61M-DS2V                   | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| MSI           | 770-C45                     | [42ffd24c35](https://linux-hardware.org/?probe=42ffd24c35) | Jan 25, 2023 |
| Lenovo        | ThinkCentre M70e 0851RZ3    | [23b8d711f4](https://linux-hardware.org/?probe=23b8d711f4) | Jan 25, 2023 |
| MSI           | 770-C45                     | [1991e96ff2](https://linux-hardware.org/?probe=1991e96ff2) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [28effc69e6](https://linux-hardware.org/?probe=28effc69e6) | Jan 25, 2023 |
| ASRock        | H110 Pro BTC+               | [4fab0cb4c4](https://linux-hardware.org/?probe=4fab0cb4c4) | Jan 25, 2023 |
| MSI           | PRO H610M-E DDR4            | [8a06b2350d](https://linux-hardware.org/?probe=8a06b2350d) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | H61M-DS2                    | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Gigabyte      | B560M AORUS PRO             | [a145217706](https://linux-hardware.org/?probe=a145217706) | Jan 25, 2023 |
| ASRock        | H310CM-DVS                  | [41b1ad4545](https://linux-hardware.org/?probe=41b1ad4545) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8a7a7f6b72](https://linux-hardware.org/?probe=8a7a7f6b72) | Jan 25, 2023 |
| ASRock        | X99 Professional Gaming ... | [74054f4cb8](https://linux-hardware.org/?probe=74054f4cb8) | Jan 24, 2023 |
| ASRock        | X99 Professional Gaming ... | [2a89d751e1](https://linux-hardware.org/?probe=2a89d751e1) | Jan 24, 2023 |
| MSI           | G41M-P28                    | [465a715dc7](https://linux-hardware.org/?probe=465a715dc7) | Jan 24, 2023 |
| Gigabyte      | B450M S2H V2                | [e8e7a44a2a](https://linux-hardware.org/?probe=e8e7a44a2a) | Jan 24, 2023 |
| MSI           | B560M PRO-VDH               | [8cb2b45267](https://linux-hardware.org/?probe=8cb2b45267) | Jan 24, 2023 |
| Biostar       | G41-M7                      | [3f66a61637](https://linux-hardware.org/?probe=3f66a61637) | Jan 24, 2023 |
| Pegatron      | IPPPV-D3G                   | [770e25fefd](https://linux-hardware.org/?probe=770e25fefd) | Jan 24, 2023 |
| ASRock        | H110 Pro BTC+               | [f4a90a48ec](https://linux-hardware.org/?probe=f4a90a48ec) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e2d597c046](https://linux-hardware.org/?probe=e2d597c046) | Jan 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [416a11089a](https://linux-hardware.org/?probe=416a11089a) | Jan 23, 2023 |
| ASRock        | B450 Gaming K4              | [0a7ef9990f](https://linux-hardware.org/?probe=0a7ef9990f) | Jan 23, 2023 |
| ASUSTek       | P8Z77-M                     | [06d41872a9](https://linux-hardware.org/?probe=06d41872a9) | Jan 23, 2023 |
| ASUSTek       | P8Z77-M                     | [f965d9b5b1](https://linux-hardware.org/?probe=f965d9b5b1) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [257f3b320c](https://linux-hardware.org/?probe=257f3b320c) | Jan 23, 2023 |
| Gigabyte      | H81M-S1                     | [ab746d7557](https://linux-hardware.org/?probe=ab746d7557) | Jan 23, 2023 |
| Intel         | SKYBAY                      | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [10fa3eeed2](https://linux-hardware.org/?probe=10fa3eeed2) | Jan 23, 2023 |
| ASUSTek       | P5K SE                      | [6d55940af7](https://linux-hardware.org/?probe=6d55940af7) | Jan 23, 2023 |
| ASUSTek       | H81M-K                      | [3c25197bac](https://linux-hardware.org/?probe=3c25197bac) | Jan 23, 2023 |
| ASRock        | X300M-STX                   | [13ce0469f3](https://linux-hardware.org/?probe=13ce0469f3) | Jan 23, 2023 |
| Dell          | 0JP3NX A01                  | [f75ac14e70](https://linux-hardware.org/?probe=f75ac14e70) | Jan 23, 2023 |
| Gigabyte      | B75M-HD3                    | [77d58eb890](https://linux-hardware.org/?probe=77d58eb890) | Jan 23, 2023 |
| ASUSTek       | P5Q SE2                     | [8618810acb](https://linux-hardware.org/?probe=8618810acb) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | A88X-PRO                    | [659f4bf9b1](https://linux-hardware.org/?probe=659f4bf9b1) | Jan 23, 2023 |
| Biostar       | H510MHP                     | [be134c4160](https://linux-hardware.org/?probe=be134c4160) | Jan 23, 2023 |
| ASUSTek       | Z97-C                       | [3a89f39a8f](https://linux-hardware.org/?probe=3a89f39a8f) | Jan 23, 2023 |
| Biostar       | H510MHP                     | [2df96ea9cf](https://linux-hardware.org/?probe=2df96ea9cf) | Jan 23, 2023 |
| MSI           | PRO H610M-E DDR4            | [d5c4129361](https://linux-hardware.org/?probe=d5c4129361) | Jan 23, 2023 |
| ASRock        | X99 Professional Gaming ... | [04f06d8d99](https://linux-hardware.org/?probe=04f06d8d99) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [ec7d450cb0](https://linux-hardware.org/?probe=ec7d450cb0) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [d55b2b9507](https://linux-hardware.org/?probe=d55b2b9507) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [8716ca07da](https://linux-hardware.org/?probe=8716ca07da) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [21e1d557cc](https://linux-hardware.org/?probe=21e1d557cc) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [33c845f3a4](https://linux-hardware.org/?probe=33c845f3a4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [24d2721a00](https://linux-hardware.org/?probe=24d2721a00) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [1e1066bd8b](https://linux-hardware.org/?probe=1e1066bd8b) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [7e636906b9](https://linux-hardware.org/?probe=7e636906b9) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [5aa076d0a5](https://linux-hardware.org/?probe=5aa076d0a5) | Jan 23, 2023 |
| ASUSTek       | H81M-E                      | [2a20dabdd7](https://linux-hardware.org/?probe=2a20dabdd7) | Jan 23, 2023 |
| Biostar       | N61PB-M2S                   | [bce8692808](https://linux-hardware.org/?probe=bce8692808) | Jan 22, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| Gigabyte      | F2A55M-DS2                  | [0e1605a304](https://linux-hardware.org/?probe=0e1605a304) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-K               | [4c4a17a3cf](https://linux-hardware.org/?probe=4c4a17a3cf) | Jan 22, 2023 |
| Gigabyte      | H310M H                     | [bd85a7e96e](https://linux-hardware.org/?probe=bd85a7e96e) | Jan 22, 2023 |
| MSI           | B350 TOMAHAWK               | [91ef58d8a0](https://linux-hardware.org/?probe=91ef58d8a0) | Jan 22, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [ecfd1795a0](https://linux-hardware.org/?probe=ecfd1795a0) | Jan 22, 2023 |
| ASRock        | B75M-GL R2.0                | [19b61442fe](https://linux-hardware.org/?probe=19b61442fe) | Jan 22, 2023 |
| ASRock        | B360 Pro4                   | [9cd508a59c](https://linux-hardware.org/?probe=9cd508a59c) | Jan 22, 2023 |
| ASUSTek       | P5E-VM SE                   | [a0b3d87534](https://linux-hardware.org/?probe=a0b3d87534) | Jan 22, 2023 |
| Dell          | 0JP3NX A01                  | [7189416b97](https://linux-hardware.org/?probe=7189416b97) | Jan 22, 2023 |
| Huanan        | H97-ZD3 V2.0                | [afb82fa3cf](https://linux-hardware.org/?probe=afb82fa3cf) | Jan 22, 2023 |
| MSI           | H97 GAMING 3                | [c861b7e450](https://linux-hardware.org/?probe=c861b7e450) | Jan 22, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | [e967d42f1b](https://linux-hardware.org/?probe=e967d42f1b) | Jan 22, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [77a744c052](https://linux-hardware.org/?probe=77a744c052) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9672c4222a](https://linux-hardware.org/?probe=9672c4222a) | Jan 21, 2023 |
| ASUSTek       | P7H55-M                     | [18efa12cb2](https://linux-hardware.org/?probe=18efa12cb2) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| MSI           | B75MA-E33                   | [df4c3bb4d2](https://linux-hardware.org/?probe=df4c3bb4d2) | Jan 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | [3a1d7fb570](https://linux-hardware.org/?probe=3a1d7fb570) | Jan 21, 2023 |
| ASUSTek       | P7H55-USB3                  | [3f270588f4](https://linux-hardware.org/?probe=3f270588f4) | Jan 21, 2023 |
| ASRock        | 880GMH/U3S3                 | [f2dff18301](https://linux-hardware.org/?probe=f2dff18301) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [b6b4b01344](https://linux-hardware.org/?probe=b6b4b01344) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Supermicro    | X9DR6-LN4+                  | [23fe7b0642](https://linux-hardware.org/?probe=23fe7b0642) | Jan 20, 2023 |
| Supermicro    | X9DR6-LN4+                  | [4e099f57d5](https://linux-hardware.org/?probe=4e099f57d5) | Jan 20, 2023 |
| Gigabyte      | A520M H                     | [db3b391bd0](https://linux-hardware.org/?probe=db3b391bd0) | Jan 20, 2023 |
| MSI           | Z490-A PRO                  | [712d12e3e9](https://linux-hardware.org/?probe=712d12e3e9) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| ASUSTek       | P5E-VM SE                   | [b3df4a1dfa](https://linux-hardware.org/?probe=b3df4a1dfa) | Jan 20, 2023 |
| MSI           | H510M PRO-E                 | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| HP            | 3047h                       | [4bbcb58967](https://linux-hardware.org/?probe=4bbcb58967) | Jan 20, 2023 |
| MSI           | PH61-SP35                   | [3bdfad797c](https://linux-hardware.org/?probe=3bdfad797c) | Jan 20, 2023 |
| ASUSTek       | M5A78L-M LE                 | [af00f739f8](https://linux-hardware.org/?probe=af00f739f8) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| ASRock        | B450M Pro4-F                | [031b7e3b0a](https://linux-hardware.org/?probe=031b7e3b0a) | Jan 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [4ebd222ef1](https://linux-hardware.org/?probe=4ebd222ef1) | Jan 20, 2023 |
| HP            | 18E4                        | [9a62a59c37](https://linux-hardware.org/?probe=9a62a59c37) | Jan 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [86d4a0e87c](https://linux-hardware.org/?probe=86d4a0e87c) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | B360HD3                     | [cbd81c917f](https://linux-hardware.org/?probe=cbd81c917f) | Jan 20, 2023 |
| Gigabyte      | H510M H                     | [f44f319e21](https://linux-hardware.org/?probe=f44f319e21) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Gigabyte      | B560M DS3H V2               | [d53ffd975c](https://linux-hardware.org/?probe=d53ffd975c) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| Huanan        | X99-F8D V2.4                | [26bc61b381](https://linux-hardware.org/?probe=26bc61b381) | Jan 19, 2023 |
| ASRock        | X99 Professional Gaming ... | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| AZW           | U59                         | [6621409d8c](https://linux-hardware.org/?probe=6621409d8c) | Jan 19, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| Biostar       | A780LB                      | [ffce251f42](https://linux-hardware.org/?probe=ffce251f42) | Jan 19, 2023 |
| ASRock        | H110 Pro BTC+               | [f888822c0d](https://linux-hardware.org/?probe=f888822c0d) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [348a5d1848](https://linux-hardware.org/?probe=348a5d1848) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| Gigabyte      | H610M S2H DDR4              | [4e77673e60](https://linux-hardware.org/?probe=4e77673e60) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| ASUSTek       | P4P800                      | [f37bee349c](https://linux-hardware.org/?probe=f37bee349c) | Jan 18, 2023 |
| MSI           | PRO H610M-E DDR4            | [3f185b85f5](https://linux-hardware.org/?probe=3f185b85f5) | Jan 18, 2023 |
| ASUSTek       | H81M-K                      | [1e6f35ceff](https://linux-hardware.org/?probe=1e6f35ceff) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Gigabyte      | B360HD3                     | [3fb3939014](https://linux-hardware.org/?probe=3fb3939014) | Jan 18, 2023 |
| ASUSTek       | P5G41T-M LX3                | [67dc4c315a](https://linux-hardware.org/?probe=67dc4c315a) | Jan 17, 2023 |
| ASUSTek       | P8Q77-M                     | [f883cb7c7b](https://linux-hardware.org/?probe=f883cb7c7b) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | [ac58bc440d](https://linux-hardware.org/?probe=ac58bc440d) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| ASRock        | H110 Pro BTC+               | [0b515319d8](https://linux-hardware.org/?probe=0b515319d8) | Jan 17, 2023 |
| ASRock        | H410M-HVS                   | [2024f1ae76](https://linux-hardware.org/?probe=2024f1ae76) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [b01089cba7](https://linux-hardware.org/?probe=b01089cba7) | Jan 17, 2023 |
| ASUSTek       | J1800I-C                    | [c32c7f2d35](https://linux-hardware.org/?probe=c32c7f2d35) | Jan 17, 2023 |
| Biostar       | A780LB                      | [fe4d79e9f8](https://linux-hardware.org/?probe=fe4d79e9f8) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [bffcece8fb](https://linux-hardware.org/?probe=bffcece8fb) | Jan 17, 2023 |
| Gigabyte      | B360HD3                     | [8b992a1d50](https://linux-hardware.org/?probe=8b992a1d50) | Jan 17, 2023 |
| ASUSTek       | H81M-K                      | [a4ee55fea9](https://linux-hardware.org/?probe=a4ee55fea9) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Gigabyte      | B450M H                     | [e3638a2110](https://linux-hardware.org/?probe=e3638a2110) | Jan 17, 2023 |
| ASRock        | H61M-HVGS                   | [2256e1c087](https://linux-hardware.org/?probe=2256e1c087) | Jan 17, 2023 |
| Gigabyte      | B560M DS3H V2               | [e29ceaa96c](https://linux-hardware.org/?probe=e29ceaa96c) | Jan 17, 2023 |
| Gigabyte      | H310M H                     | [faa3746295](https://linux-hardware.org/?probe=faa3746295) | Jan 17, 2023 |
| ASUSTek       | M2N68-AM SE2                | [72e3ebc3b8](https://linux-hardware.org/?probe=72e3ebc3b8) | Jan 17, 2023 |
| ASUSTek       | H81-PLUS                    | [e95534600a](https://linux-hardware.org/?probe=e95534600a) | Jan 16, 2023 |
| Gigabyte      | A320M-S2H-CF                | [df0f33ee66](https://linux-hardware.org/?probe=df0f33ee66) | Jan 16, 2023 |
| Intel         | X99                         | [f966e7aa92](https://linux-hardware.org/?probe=f966e7aa92) | Jan 16, 2023 |
| Huanan        | H97-ZD3 V2.0                | [aececc6971](https://linux-hardware.org/?probe=aececc6971) | Jan 16, 2023 |
| MSI           | 970A-G43                    | [f15370df26](https://linux-hardware.org/?probe=f15370df26) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| Unknown       | T310D11                     | [acce0e1df1](https://linux-hardware.org/?probe=acce0e1df1) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [2ebeb3fa1a](https://linux-hardware.org/?probe=2ebeb3fa1a) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| Gigabyte      | B450 GAMING X               | [c07c86ed27](https://linux-hardware.org/?probe=c07c86ed27) | Jan 16, 2023 |
| Gigabyte      | B450 GAMING X               | [f06080b088](https://linux-hardware.org/?probe=f06080b088) | Jan 16, 2023 |
| ASUSTek       | P8H77-V                     | [d136e01384](https://linux-hardware.org/?probe=d136e01384) | Jan 16, 2023 |
| Gigabyte      | MZBSWMP-00                  | [c1660ab5a4](https://linux-hardware.org/?probe=c1660ab5a4) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [939ab29431](https://linux-hardware.org/?probe=939ab29431) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| ASRock        | Z77 Pro4-M                  | [4c8f01cfd7](https://linux-hardware.org/?probe=4c8f01cfd7) | Jan 15, 2023 |
| MSI           | 970A-G43                    | [669512ff6c](https://linux-hardware.org/?probe=669512ff6c) | Jan 15, 2023 |
| ASUSTek       | P7H55-USB3                  | [d412197c51](https://linux-hardware.org/?probe=d412197c51) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS M                | [ac596694bd](https://linux-hardware.org/?probe=ac596694bd) | Jan 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [fe4b311f78](https://linux-hardware.org/?probe=fe4b311f78) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a65831f165](https://linux-hardware.org/?probe=a65831f165) | Jan 15, 2023 |
| ASUSTek       | P5E-VM SE                   | [af5169b24d](https://linux-hardware.org/?probe=af5169b24d) | Jan 15, 2023 |
| PLEXHD        | X79T rev. V1.0              | [9c8c729f1c](https://linux-hardware.org/?probe=9c8c729f1c) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS M                | [89a3800060](https://linux-hardware.org/?probe=89a3800060) | Jan 15, 2023 |
| Intel         | X99 V1.0                    | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [c59c9570d6](https://linux-hardware.org/?probe=c59c9570d6) | Jan 14, 2023 |
| Acer          | Aspire XC-830               | [1d9206b1f1](https://linux-hardware.org/?probe=1d9206b1f1) | Jan 14, 2023 |
| MSI           | B450M MORTAR MAX            | [1e42d818dd](https://linux-hardware.org/?probe=1e42d818dd) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | [77adbc7487](https://linux-hardware.org/?probe=77adbc7487) | Jan 14, 2023 |
| ASRock        | AB350 Pro4                  | [e430030b47](https://linux-hardware.org/?probe=e430030b47) | Jan 14, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [69819d1ce1](https://linux-hardware.org/?probe=69819d1ce1) | Jan 14, 2023 |
| ASRock        | N68C-S UCC                  | [7c5f173e5c](https://linux-hardware.org/?probe=7c5f173e5c) | Jan 13, 2023 |
| ASRock        | A320M-HDV R4.0              | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [7cde78238f](https://linux-hardware.org/?probe=7cde78238f) | Jan 13, 2023 |
| ASUSTek       | P8H77-V LE                  | [ae418043f3](https://linux-hardware.org/?probe=ae418043f3) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| MSI           | H310M PRO-VD PLUS           | [e33042f453](https://linux-hardware.org/?probe=e33042f453) | Jan 13, 2023 |
| MSI           | B450M MORTAR MAX            | [e840ab1f61](https://linux-hardware.org/?probe=e840ab1f61) | Jan 13, 2023 |
| Gigabyte      | G41MT-S2                    | [25b6ab4c75](https://linux-hardware.org/?probe=25b6ab4c75) | Jan 12, 2023 |
| ASUSTek       | H81M-K                      | [8c3dc4bac3](https://linux-hardware.org/?probe=8c3dc4bac3) | Jan 12, 2023 |
| ASUSTek       | P5E-VM SE                   | [feee0755d0](https://linux-hardware.org/?probe=feee0755d0) | Jan 12, 2023 |
| ASUSTek       | H81M-K                      | [14ed7f9591](https://linux-hardware.org/?probe=14ed7f9591) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| Gigabyte      | X570S UD                    | [e3458505fd](https://linux-hardware.org/?probe=e3458505fd) | Jan 12, 2023 |
| Gigabyte      | H510M H                     | [69d2cb7e14](https://linux-hardware.org/?probe=69d2cb7e14) | Jan 11, 2023 |
| Intel         | X79G V2.x                   | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| ASRock        | B450M Pro4                  | [5b24178097](https://linux-hardware.org/?probe=5b24178097) | Jan 11, 2023 |
| ASUSTek       | P7H55-USB3                  | [ae85db39c6](https://linux-hardware.org/?probe=ae85db39c6) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b8df2d6479](https://linux-hardware.org/?probe=b8df2d6479) | Jan 11, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [49863a504f](https://linux-hardware.org/?probe=49863a504f) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [4074262fd3](https://linux-hardware.org/?probe=4074262fd3) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a1e541c1b3](https://linux-hardware.org/?probe=a1e541c1b3) | Jan 11, 2023 |
| Intel         | SKYBAY                      | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Gigabyte      | B360HD3                     | [6c3f234091](https://linux-hardware.org/?probe=6c3f234091) | Jan 11, 2023 |
| Intel         | SKYBAY                      | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [e9a8dfc18e](https://linux-hardware.org/?probe=e9a8dfc18e) | Jan 11, 2023 |
| ASUSTek       | H81M-K                      | [2e985853be](https://linux-hardware.org/?probe=2e985853be) | Jan 11, 2023 |
| ASUSTek       | PRIME H610M-K D4            | [31ecdfb704](https://linux-hardware.org/?probe=31ecdfb704) | Jan 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a57b3e3df6](https://linux-hardware.org/?probe=a57b3e3df6) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [694c5c31f9](https://linux-hardware.org/?probe=694c5c31f9) | Jan 10, 2023 |
| Gigabyte      | H61M-S2PV                   | [8248661973](https://linux-hardware.org/?probe=8248661973) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| Gigabyte      | H61M-DS2                    | [69ceed18f7](https://linux-hardware.org/?probe=69ceed18f7) | Jan 10, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [3b99403f0f](https://linux-hardware.org/?probe=3b99403f0f) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | [286d590fda](https://linux-hardware.org/?probe=286d590fda) | Jan 10, 2023 |
| ECS           | BSWI-D2                     | [74f6bf3564](https://linux-hardware.org/?probe=74f6bf3564) | Jan 10, 2023 |
| ASRock        | H110 Pro BTC+               | [685765625e](https://linux-hardware.org/?probe=685765625e) | Jan 10, 2023 |
| ASUSTek       | PRIME B460-PLUS             | [88840b68e3](https://linux-hardware.org/?probe=88840b68e3) | Jan 10, 2023 |
| ASUSTek       | P7H55-M                     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Acer          | Aspire TC-605               | [77ecead5ed](https://linux-hardware.org/?probe=77ecead5ed) | Jan 09, 2023 |
| ASUSTek       | P5E-VM SE                   | [d9f3023575](https://linux-hardware.org/?probe=d9f3023575) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [ef4b23a73d](https://linux-hardware.org/?probe=ef4b23a73d) | Jan 09, 2023 |
| HP            | 18E6                        | [61070949ee](https://linux-hardware.org/?probe=61070949ee) | Jan 09, 2023 |
| Gigabyte      | GA-870A-UD3                 | [49beabba6b](https://linux-hardware.org/?probe=49beabba6b) | Jan 09, 2023 |
| Acer          | Veriton N4660G              | [8f27f893b1](https://linux-hardware.org/?probe=8f27f893b1) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [2a22078fe1](https://linux-hardware.org/?probe=2a22078fe1) | Jan 09, 2023 |
| Gigabyte      | 965P-DS3                    | [1b27c7404f](https://linux-hardware.org/?probe=1b27c7404f) | Jan 09, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [d5c81ffaec](https://linux-hardware.org/?probe=d5c81ffaec) | Jan 09, 2023 |
| ASRock        | AB350 Pro4                  | [66805743c5](https://linux-hardware.org/?probe=66805743c5) | Jan 09, 2023 |
| ASUSTek       | PRIME B560M-A               | [3447d8086d](https://linux-hardware.org/?probe=3447d8086d) | Jan 09, 2023 |
| Gigabyte      | B450M DS3H-CF               | [4dd5ee2fa8](https://linux-hardware.org/?probe=4dd5ee2fa8) | Jan 09, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [50032f13ef](https://linux-hardware.org/?probe=50032f13ef) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [8ddf09108e](https://linux-hardware.org/?probe=8ddf09108e) | Jan 08, 2023 |
| ASUSTek       | Z170-K                      | [896e860da1](https://linux-hardware.org/?probe=896e860da1) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [61f4028846](https://linux-hardware.org/?probe=61f4028846) | Jan 08, 2023 |
| ASUSTek       | P5B                         | [9fd56e9b73](https://linux-hardware.org/?probe=9fd56e9b73) | Jan 08, 2023 |
| ASRock        | Z77 Extreme3                | [51f731b0f4](https://linux-hardware.org/?probe=51f731b0f4) | Jan 08, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [8ef8c9baa7](https://linux-hardware.org/?probe=8ef8c9baa7) | Jan 08, 2023 |
| ASRock        | 960GM-VGS3 FX               | [5b64e74a17](https://linux-hardware.org/?probe=5b64e74a17) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [49f4c2fbc8](https://linux-hardware.org/?probe=49f4c2fbc8) | Jan 08, 2023 |
| ASUSTek       | P5QL PRO                    | [e5d4ce1aa7](https://linux-hardware.org/?probe=e5d4ce1aa7) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | P8H77-V                     | [85e7e56c1d](https://linux-hardware.org/?probe=85e7e56c1d) | Jan 08, 2023 |
| ASUSTek       | P6X58D-E                    | [0fdf612101](https://linux-hardware.org/?probe=0fdf612101) | Jan 08, 2023 |
| ASUSTek       | PRIME B365M-A               | [4f9477b846](https://linux-hardware.org/?probe=4f9477b846) | Jan 08, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| Foxconn       | H55MXV Series               | [8722a85ee1](https://linux-hardware.org/?probe=8722a85ee1) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | [93957e7a70](https://linux-hardware.org/?probe=93957e7a70) | Jan 07, 2023 |
| Gigabyte      | GA-MA770-UD3                | [b4bf97514d](https://linux-hardware.org/?probe=b4bf97514d) | Jan 07, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [f811d71835](https://linux-hardware.org/?probe=f811d71835) | Jan 07, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [c1c8654cde](https://linux-hardware.org/?probe=c1c8654cde) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [829138fad9](https://linux-hardware.org/?probe=829138fad9) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [9193043004](https://linux-hardware.org/?probe=9193043004) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [a6d1d6523b](https://linux-hardware.org/?probe=a6d1d6523b) | Jan 07, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [af95c3e61e](https://linux-hardware.org/?probe=af95c3e61e) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | [4f26146dd8](https://linux-hardware.org/?probe=4f26146dd8) | Jan 07, 2023 |
| Gigabyte      | H610M H DDR4                | [f139bfc805](https://linux-hardware.org/?probe=f139bfc805) | Jan 07, 2023 |
| ASRock        | X300M-STX                   | [55db2decf3](https://linux-hardware.org/?probe=55db2decf3) | Jan 07, 2023 |
| MB            | A320-SF110                  | [d23ec63d82](https://linux-hardware.org/?probe=d23ec63d82) | Jan 07, 2023 |
| ASUSTek       | PRIME B460M-A               | [b5dd8ee9f3](https://linux-hardware.org/?probe=b5dd8ee9f3) | Jan 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6893b29920](https://linux-hardware.org/?probe=6893b29920) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a9288e85f6](https://linux-hardware.org/?probe=a9288e85f6) | Jan 06, 2023 |
| ASRock        | 960GM-VGS3 FX               | [633f31b57e](https://linux-hardware.org/?probe=633f31b57e) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [30bf1793c5](https://linux-hardware.org/?probe=30bf1793c5) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | [843dbca31d](https://linux-hardware.org/?probe=843dbca31d) | Jan 06, 2023 |
| ASUSTek       | P8H77-V LE                  | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| MB            | A320-SF110                  | [5b690cf226](https://linux-hardware.org/?probe=5b690cf226) | Jan 06, 2023 |
| ASRock        | A320D4-P1                   | [b6a61f9d2d](https://linux-hardware.org/?probe=b6a61f9d2d) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| Gigabyte      | H61M-S1                     | [7b61bf12d0](https://linux-hardware.org/?probe=7b61bf12d0) | Jan 06, 2023 |
| ASRock        | D1800M                      | [f70a4786d7](https://linux-hardware.org/?probe=f70a4786d7) | Jan 06, 2023 |
| ASUSTek       | P7H55-USB3                  | [e94f2584b0](https://linux-hardware.org/?probe=e94f2584b0) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6cd2288696](https://linux-hardware.org/?probe=6cd2288696) | Jan 06, 2023 |
| Gigabyte      | H77M-D3H                    | [8a0c5b7924](https://linux-hardware.org/?probe=8a0c5b7924) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | [0f4c3a7053](https://linux-hardware.org/?probe=0f4c3a7053) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| MSI           | H61M-P20                    | [f48c04fe8f](https://linux-hardware.org/?probe=f48c04fe8f) | Jan 05, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| ASRock        | M3A770DE                    | [952caf04f8](https://linux-hardware.org/?probe=952caf04f8) | Jan 05, 2023 |
| ASUSTek       | M2N68 Plus                  | [12309f8c91](https://linux-hardware.org/?probe=12309f8c91) | Jan 05, 2023 |
| ASRock        | Z77M                        | [fe6f6a7b05](https://linux-hardware.org/?probe=fe6f6a7b05) | Jan 05, 2023 |
| ASRock        | X570 Steel Legend           | [584234b202](https://linux-hardware.org/?probe=584234b202) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | [e1b3de18e9](https://linux-hardware.org/?probe=e1b3de18e9) | Jan 05, 2023 |
| ASUSTek       | A55BM-PLUS                  | [8601b7f2e9](https://linux-hardware.org/?probe=8601b7f2e9) | Jan 04, 2023 |
| ASRock        | H510M-HVS                   | [738739788a](https://linux-hardware.org/?probe=738739788a) | Jan 04, 2023 |
| Maibenben     | PC34 V1.0                   | [0ed25644b7](https://linux-hardware.org/?probe=0ed25644b7) | Jan 04, 2023 |
| Gigabyte      | P35-DS3L                    | [c07ba0a973](https://linux-hardware.org/?probe=c07ba0a973) | Jan 04, 2023 |
| ECS           | G41T-M2                     | [8df8f82fb8](https://linux-hardware.org/?probe=8df8f82fb8) | Jan 04, 2023 |
| ASRock        | FM2A85X Extreme4            | [67f24d7bfa](https://linux-hardware.org/?probe=67f24d7bfa) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| MSI           | A320M GRENADE               | [5e6f9a181c](https://linux-hardware.org/?probe=5e6f9a181c) | Jan 04, 2023 |
| MSI           | MS-B0A41                    | [f57c26d714](https://linux-hardware.org/?probe=f57c26d714) | Jan 04, 2023 |
| MSI           | B550-A PRO                  | [36c23fdfd7](https://linux-hardware.org/?probe=36c23fdfd7) | Jan 04, 2023 |
| Lenovo        | H420                        | [0765ceb3e8](https://linux-hardware.org/?probe=0765ceb3e8) | Jan 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [89868317cd](https://linux-hardware.org/?probe=89868317cd) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [c8618e40a6](https://linux-hardware.org/?probe=c8618e40a6) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASRock        | N68-GS4 FX                  | [f55d8b7bc9](https://linux-hardware.org/?probe=f55d8b7bc9) | Jan 03, 2023 |
| Gigabyte      | H470M DS3H                  | [07e46fc5f7](https://linux-hardware.org/?probe=07e46fc5f7) | Jan 03, 2023 |
| Gigabyte      | H61M-S1                     | [5ea753453b](https://linux-hardware.org/?probe=5ea753453b) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Gigabyte      | H61M-S2PV                   | [85ad98c994](https://linux-hardware.org/?probe=85ad98c994) | Jan 02, 2023 |
| ASUSTek       | P8Z68-M PRO                 | [33b212da3e](https://linux-hardware.org/?probe=33b212da3e) | Jan 02, 2023 |
| AZW           | MINI S                      | [ad7c4329eb](https://linux-hardware.org/?probe=ad7c4329eb) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| OEM           | Intel H81                   | [1700a7a4c7](https://linux-hardware.org/?probe=1700a7a4c7) | Jan 01, 2023 |
| Gigabyte      | H55M-USB3                   | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| Gigabyte      | EP45-DS3L                   | [e818c3c6ed](https://linux-hardware.org/?probe=e818c3c6ed) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| Huanan        | X99 F8D V2.2                | [c1818201ce](https://linux-hardware.org/?probe=c1818201ce) | Jan 01, 2023 |
| ASUSTek       | P8H67                       | [33bf029e5f](https://linux-hardware.org/?probe=33bf029e5f) | Jan 01, 2023 |
| ZOTAC         | Unknown                     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | MS-B0A41                    | [c69ab6fbe8](https://linux-hardware.org/?probe=c69ab6fbe8) | Jan 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e18f6635d3](https://linux-hardware.org/?probe=e18f6635d3) | Dec 31, 2022 |
| Phoenix       | 945GM                       | [d391eaf6e2](https://linux-hardware.org/?probe=d391eaf6e2) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | [dff8a56537](https://linux-hardware.org/?probe=dff8a56537) | Dec 30, 2022 |
| Gigabyte      | H55M-USB3                   | [8fdced7ae8](https://linux-hardware.org/?probe=8fdced7ae8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R11           | 1604     | 11.82%  |
| ROSA R10           | 1538     | 11.33%  |
| ROSA R8.1          | 1139     | 8.39%   |
| ROSA R8            | 1050     | 7.74%   |
| ROSA R9            | 928      | 6.84%   |
| ROSA 12.2          | 911      | 6.71%   |
| ROSA R11.1         | 870      | 6.41%   |
| Debian 11          | 679      | 5%      |
| ROSA 12.3          | 421      | 3.1%    |
| Ubuntu 20.04       | 334      | 2.46%   |
| OpenMandriva 4.2   | 231      | 1.7%    |
| Ubuntu 18.04       | 203      | 1.5%    |
| OpenMandriva 4.3   | 167      | 1.23%   |
| ROSA 12.1          | 146      | 1.08%   |
| Ubuntu 22.04       | 116      | 0.85%   |
| Arch Rolling       | 110      | 0.81%   |
| ROSA 12            | 95       | 0.7%    |
| KDE neon 20.04     | 87       | 0.64%   |
| Debian 10          | 83       | 0.61%   |
| Kometa P10         | 81       | 0.6%    |
| Xubuntu 20.04      | 73       | 0.54%   |
| OpenMandriva 23.01 | 69       | 0.51%   |
| Arch               | 68       | 0.5%    |
| Manjaro            | 59       | 0.43%   |
| RED X3             | 56       | 0.41%   |
| Linux Mint 20.3    | 56       | 0.41%   |
| RED X4             | 51       | 0.38%   |
| Linux Mint 18.3    | 51       | 0.38%   |
| Kubuntu 20.04      | 51       | 0.38%   |
| Red OS 7.3         | 50       | 0.37%   |
| Fedora 36          | 47       | 0.35%   |
| Red OS 7.3.1       | 46       | 0.34%   |
| Linux Mint 19.3    | 44       | 0.32%   |
| Linux Mint 19.1    | 43       | 0.32%   |
| ALT Linux 10.1     | 39       | 0.29%   |
| ROSA R12           | 38       | 0.28%   |
| OpenMandriva 4.50  | 38       | 0.28%   |
| Linux Mint 20      | 38       | 0.28%   |
| Fedora 37          | 38       | 0.28%   |
| Fedora 35          | 34       | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 7519     | 62.66%  |
| Debian       | 824      | 6.87%   |
| Ubuntu       | 781      | 6.51%   |
| OpenMandriva | 529      | 4.41%   |
| Linux Mint   | 399      | 3.33%   |
| Manjaro      | 226      | 1.88%   |
| Fedora       | 223      | 1.86%   |
| ALT Linux    | 214      | 1.78%   |
| Arch         | 173      | 1.44%   |
| Red OS       | 127      | 1.06%   |
| Xubuntu      | 116      | 0.97%   |
| RED          | 113      | 0.94%   |
| KDE neon     | 110      | 0.92%   |
| Kubuntu      | 96       | 0.8%    |
| Gentoo       | 59       | 0.49%   |
| Endless      | 53       | 0.44%   |
| Pop!_OS      | 46       | 0.38%   |
| openSUSE     | 37       | 0.31%   |
| Ubuntu MATE  | 28       | 0.23%   |
| Clear Linux  | 25       | 0.21%   |
| Elementary   | 24       | 0.2%    |
| RELS         | 22       | 0.18%   |
| CentOS       | 21       | 0.18%   |
| Zorin        | 20       | 0.17%   |
| Ubuntu Unity | 18       | 0.15%   |
| Lubuntu      | 17       | 0.14%   |
| ArcoLinux    | 17       | 0.14%   |
| LMDE         | 16       | 0.13%   |
| Kali         | 10       | 0.08%   |
| Astra Linux  | 7        | 0.06%   |
| Artix        | 7        | 0.06%   |
| Solus        | 6        | 0.05%   |
| MX           | 6        | 0.05%   |
| EndeavourOS  | 6        | 0.05%   |
| Rocky Linux  | 5        | 0.04%   |
| Devuan       | 5        | 0.04%   |
| Calculate    | 5        | 0.04%   |
| Void Linux   | 4        | 0.03%   |
| Virtuozzo    | 4        | 0.03%   |
| Slackware    | 4        | 0.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 780      | 5.33%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 700      | 4.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 697      | 4.76%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 667      | 4.56%   |
| 5.10.0-7-amd64                      | 472      | 3.23%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 401      | 2.74%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 332      | 2.27%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 318      | 2.17%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 255      | 1.74%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 250      | 1.71%   |
| 5.10.14-desktop-1omv4002            | 221      | 1.51%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 205      | 1.4%    |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 197      | 1.35%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 196      | 1.34%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 195      | 1.33%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 189      | 1.29%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 183      | 1.25%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 180      | 1.23%   |
| 4.15.0-desktop-45.1rosa-i586        | 169      | 1.16%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 167      | 1.14%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 165      | 1.13%   |
| 5.16.7-desktop-1omv4003             | 160      | 1.09%   |
| 5.4.32-generic-2rosa-x86_64         | 158      | 1.08%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 151      | 1.03%   |
| 5.4.83-generic-2rosa-x86_64         | 148      | 1.01%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 148      | 1.01%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 140      | 0.96%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 137      | 0.94%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 134      | 0.92%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 112      | 0.77%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 112      | 0.77%   |
| 5.10.0-2-amd64                      | 110      | 0.75%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 92       | 0.63%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 92       | 0.63%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 91       | 0.62%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 83       | 0.57%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 65       | 0.44%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 64       | 0.44%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 64       | 0.44%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 64       | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 2004     | 14.15%  |
| 4.9.60   | 884      | 6.24%   |
| 4.9.20   | 846      | 5.97%   |
| 5.10.74  | 793      | 5.6%    |
| 5.10.0   | 678      | 4.79%   |
| 4.1.34   | 546      | 3.86%   |
| 5.4.0    | 544      | 3.84%   |
| 4.1.38   | 434      | 3.06%   |
| 4.1.25   | 430      | 3.04%   |
| 4.9.9    | 402      | 2.84%   |
| 4.9.124  | 395      | 2.79%   |
| 4.9.155  | 261      | 1.84%   |
| 4.9.76   | 251      | 1.77%   |
| 4.9.41   | 250      | 1.77%   |
| 5.15.0   | 247      | 1.74%   |
| 5.10.14  | 221      | 1.56%   |
| 5.4.32   | 210      | 1.48%   |
| 5.4.83   | 188      | 1.33%   |
| 5.10.118 | 172      | 1.21%   |
| 5.16.7   | 161      | 1.14%   |
| 5.15.75  | 152      | 1.07%   |
| 5.8.0    | 139      | 0.98%   |
| 5.3.0    | 137      | 0.97%   |
| 5.15.79  | 134      | 0.95%   |
| 5.11.0   | 129      | 0.91%   |
| 4.9.95   | 120      | 0.85%   |
| 5.0.0    | 110      | 0.78%   |
| 4.9.111  | 104      | 0.73%   |
| 5.10.71  | 93       | 0.66%   |
| 5.13.0   | 89       | 0.63%   |
| 4.9.87   | 82       | 0.58%   |
| 4.18.0   | 82       | 0.58%   |
| 4.19.0   | 74       | 0.52%   |
| 6.1.1    | 67       | 0.47%   |
| 5.10.109 | 51       | 0.36%   |
| 4.9.14   | 48       | 0.34%   |
| 5.19.0   | 47       | 0.33%   |
| 5.17.11  | 46       | 0.32%   |
| 5.10.155 | 40       | 0.28%   |
| 5.4.40   | 39       | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 3195     | 24.18%  |
| 5.10    | 2169     | 16.42%  |
| 4.15    | 2016     | 15.26%  |
| 4.1     | 1369     | 10.36%  |
| 5.4     | 1114     | 8.43%   |
| 5.15    | 813      | 6.15%   |
| 5.16    | 224      | 1.7%    |
| 5.11    | 207      | 1.57%   |
| 5.8     | 196      | 1.48%   |
| 5.3     | 186      | 1.41%   |
| 6.1     | 165      | 1.25%   |
| 5.0     | 129      | 0.98%   |
| 5.13    | 125      | 0.95%   |
| 5.18    | 124      | 0.94%   |
| 4.19    | 109      | 0.82%   |
| 6.0     | 108      | 0.82%   |
| 5.19    | 92       | 0.7%    |
| 4.18    | 92       | 0.7%    |
| 5.17    | 81       | 0.61%   |
| 5.14    | 64       | 0.48%   |
| 5.6     | 60       | 0.45%   |
| 5.9     | 57       | 0.43%   |
| 4.4     | 52       | 0.39%   |
| 4.13    | 51       | 0.39%   |
| 5.12    | 47       | 0.36%   |
| 5.7     | 38       | 0.29%   |
| 3.10    | 38       | 0.29%   |
| 4.8     | 36       | 0.27%   |
| 6.2     | 35       | 0.26%   |
| 5.5     | 27       | 0.2%    |
| 4.14    | 26       | 0.2%    |
| 4.16    | 25       | 0.19%   |
| 3.14    | 23       | 0.17%   |
| 5.2     | 21       | 0.16%   |
| 4.10    | 20       | 0.15%   |
| 4.20    | 13       | 0.1%    |
| 4.17    | 13       | 0.1%    |
| 4.12    | 13       | 0.1%    |
| 4.11    | 11       | 0.08%   |
| 4.7     | 8        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| x86_64      | 10161    | 86.2%   |
| i686        | 1620     | 13.74%  |
| e2k         | 4        | 0.03%   |
| ppc64       | 1        | 0.01%   |
| loongarch64 | 1        | 0.01%   |
| armv6l      | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| KDE4              | 4716     | 37.75%  |
| KDE5              | 3347     | 26.79%  |
| GNOME             | 1629     | 13.04%  |
| Unknown           | 1103     | 8.83%   |
| XFCE              | 370      | 2.96%   |
| MATE              | 349      | 2.79%   |
| LXQt              | 315      | 2.52%   |
| Cinnamon          | 191      | 1.53%   |
| X-Cinnamon        | 189      | 1.51%   |
| KDE               | 137      | 1.1%    |
| LXDE              | 24       | 0.19%   |
| Pantheon          | 23       | 0.18%   |
| Unity             | 18       | 0.14%   |
| i3                | 11       | 0.09%   |
| Budgie            | 11       | 0.09%   |
| GNOME Flashback   | 8        | 0.06%   |
| Deepin            | 8        | 0.06%   |
| GNOME Classic     | 7        | 0.06%   |
| openbox           | 6        | 0.05%   |
| awesome           | 5        | 0.04%   |
| fly               | 4        | 0.03%   |
| Hyprland          | 3        | 0.02%   |
| bspwm             | 3        | 0.02%   |
| xmonad            | 2        | 0.02%   |
| sway              | 2        | 0.02%   |
| lightdm-xsession  | 2        | 0.02%   |
| ICEWM             | 2        | 0.02%   |
| DWM               | 2        | 0.02%   |
| X-Generic         | 1        | 0.01%   |
| Trinity           | 1        | 0.01%   |
| steamos           | 1        | 0.01%   |
| i3-with-shmlog    | 1        | 0.01%   |
| /etc/X11/Xsession | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 9571     | 79.73%  |
| Wayland | 1533     | 12.77%  |
| Unknown | 776      | 6.46%   |
| Tty     | 124      | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 4758     | 38.24%  |
| SDDM    | 3414     | 27.44%  |
| Unknown | 1975     | 15.87%  |
| GDM     | 1312     | 10.54%  |
| LightDM | 391      | 3.14%   |
| TDM     | 320      | 2.57%   |
| GDM3    | 215      | 1.73%   |
| MDM     | 22       | 0.18%   |
| XDM     | 10       | 0.08%   |
| SLiM    | 8        | 0.06%   |
| LXDM    | 6        | 0.05%   |
| FLY-DM  | 5        | 0.04%   |
| Ly      | 2        | 0.02%   |
| WDM     | 1        | 0.01%   |
| NODM    | 1        | 0.01%   |
| LDM     | 1        | 0.01%   |
| GREETD  | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 6238     | 51.29%  |
| ru_RU       | 4990     | 41.03%  |
| en_US       | 817      | 6.72%   |
| C           | 45       | 0.37%   |
| en_GB       | 20       | 0.16%   |
| ru_RU.UTF_8 | 9        | 0.07%   |
| ru_UA       | 8        | 0.07%   |
| C.UTF8      | 7        | 0.06%   |
| ru_RU.UTF8  | 6        | 0.05%   |
| POSIX       | 4        | 0.03%   |
| cv_RU       | 4        | 0.03%   |
| tt_RU       | 2        | 0.02%   |
| en_DK       | 2        | 0.02%   |
| ba_RU       | 2        | 0.02%   |
| zh_CN       | 1        | 0.01%   |
| uk_UA       | 1        | 0.01%   |
| myv_RU      | 1        | 0.01%   |
| fr_FR       | 1        | 0.01%   |
| en_RU       | 1        | 0.01%   |
| en_CA       | 1        | 0.01%   |
| en_AG       | 1        | 0.01%   |
| de_DE       | 1        | 0.01%   |
| ce_RU       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 8641     | 72.35%  |
| EFI  | 3303     | 27.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 6712     | 54.22%  |
| Unknown  | 3833     | 30.96%  |
| Overlay  | 1094     | 8.84%   |
| Btrfs    | 501      | 4.05%   |
| Xfs      | 94       | 0.76%   |
| Ext3     | 45       | 0.36%   |
| Zfs      | 34       | 0.27%   |
| F2fs     | 23       | 0.19%   |
| Ext2     | 19       | 0.15%   |
| Aufs     | 5        | 0.04%   |
| Jfs      | 4        | 0.03%   |
| XXXXXXX  | 3        | 0.02%   |
| SAMSUNG  | 3        | 0.02%   |
| Reiserfs | 3        | 0.02%   |
| Tmpfs    | 2        | 0.02%   |
| Rootfs   | 2        | 0.02%   |
| XXXXX    | 1        | 0.01%   |
| Exfat    | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 5808     | 46.77%  |
| GPT     | 3617     | 29.13%  |
| Unknown | 2993     | 24.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10134    | 83.7%   |
| Yes       | 1974     | 16.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7751     | 63.27%  |
| Yes       | 4499     | 36.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4159     | 35.7%   |
| Gigabyte Technology | 2868     | 24.62%  |
| ASRock              | 1278     | 10.97%  |
| MSI                 | 1230     | 10.56%  |
| Intel               | 354      | 3.04%   |
| ECS                 | 262      | 2.25%   |
| Hewlett-Packard     | 181      | 1.55%   |
| Unknown             | 178      | 1.53%   |
| Acer                | 146      | 1.25%   |
| Biostar             | 127      | 1.09%   |
| Foxconn             | 121      | 1.04%   |
| Lenovo              | 98       | 0.84%   |
| Dell                | 96       | 0.82%   |
| Pegatron            | 82       | 0.7%    |
| Huanan              | 79       | 0.68%   |
| EPoX Computer       | 24       | 0.21%   |
| DEPO Computers      | 23       | 0.2%    |
| WinFast             | 20       | 0.17%   |
| Supermicro          | 19       | 0.16%   |
| Fujitsu             | 19       | 0.16%   |
| AZW                 | 17       | 0.15%   |
| Fujitsu Siemens     | 13       | 0.11%   |
| Aquarius            | 13       | 0.11%   |
| MACHINIST           | 11       | 0.09%   |
| Nvidia              | 10       | 0.09%   |
| AMD                 | 10       | 0.09%   |
| OEM                 | 9        | 0.08%   |
| Shuttle             | 8        | 0.07%   |
| Kraftway            | 8        | 0.07%   |
| JW Technology       | 8        | 0.07%   |
| SiS Technology      | 7        | 0.06%   |
| Kllisre             | 7        | 0.06%   |
| iRU                 | 6        | 0.05%   |
| ABIT                | 6        | 0.05%   |
| Packard Bell        | 5        | 0.04%   |
| Lite-On             | 5        | 0.04%   |
| IBM                 | 5        | 0.04%   |
| eMachines           | 5        | 0.04%   |
| Colorful Technology | 5        | 0.04%   |
| AMI                 | 5        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS All Series          | 373      | 3.2%    |
| Unknown                  | 195      | 1.67%   |
| Gigabyte 970A-DS3P       | 71       | 0.61%   |
| MSI MS-7996              | 70       | 0.6%    |
| ASUS M5A78L-M LX3        | 68       | 0.58%   |
| MSI MS-7817              | 67       | 0.58%   |
| ASUS P8H61-M LX3 R2.0    | 59       | 0.51%   |
| ASUS H110M-R             | 59       | 0.51%   |
| ASUS S20 K29             | 55       | 0.47%   |
| Intel SKYBAY             | 48       | 0.41%   |
| ASUS P5K                 | 46       | 0.39%   |
| ASUS M5A97 R2.0          | 46       | 0.39%   |
| ASRock G31M-S            | 46       | 0.39%   |
| MSI MS-7529              | 45       | 0.39%   |
| Gigabyte H61M-S1         | 45       | 0.39%   |
| Gigabyte G31M-ES2L       | 43       | 0.37%   |
| ASUS P5G41T-M LX2/GB     | 43       | 0.37%   |
| ASUS P5KPL-AM            | 41       | 0.35%   |
| Gigabyte H61M-S2PV       | 40       | 0.34%   |
| ASRock N68C-S UCC        | 40       | 0.34%   |
| MSI MS-7592              | 39       | 0.33%   |
| ASUS M5A78L-M/USB3       | 39       | 0.33%   |
| ASUS PRIME A320M-K       | 38       | 0.33%   |
| ASUS M5A97 LE R2.0       | 37       | 0.32%   |
| ECS G31T-M9              | 34       | 0.29%   |
| ASUS P5B                 | 34       | 0.29%   |
| Gigabyte Z77-DS3H        | 33       | 0.28%   |
| ASUS A68HM-K             | 33       | 0.28%   |
| ASUS P5Q SE2             | 32       | 0.27%   |
| ASUS P5KPL-AM IN/ROEM/SI | 32       | 0.27%   |
| Gigabyte GA-78LMT-S2     | 31       | 0.27%   |
| ASRock G41M-VS3          | 31       | 0.27%   |
| MSI MS-7721              | 30       | 0.26%   |
| Gigabyte GA-78LMT-S2P    | 30       | 0.26%   |
| ASUS P8Z77-V LX          | 30       | 0.26%   |
| MSI MS-7693              | 29       | 0.25%   |
| ASUS PRIME H310M-R R2.0  | 29       | 0.25%   |
| ASUS P8B75-V             | 29       | 0.25%   |
| ASUS H110M-K             | 29       | 0.25%   |
| MSI MS-7309              | 27       | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 392      | 3.37%   |
| ASUS All           | 373      | 3.2%    |
| Unknown            | 195      | 1.67%   |
| ASUS P8H61-M       | 188      | 1.61%   |
| ASUS M5A78L-M      | 178      | 1.53%   |
| ASUS P5KPL-AM      | 125      | 1.07%   |
| ASUS M5A97         | 112      | 0.96%   |
| ASUS P5G41T-M      | 106      | 0.91%   |
| ASUS P5K           | 96       | 0.82%   |
| Acer Aspire        | 91       | 0.78%   |
| ASUS P8Z77-V       | 86       | 0.74%   |
| ASUS ROG           | 75       | 0.64%   |
| ASUS TUF           | 74       | 0.64%   |
| ASUS P5Q           | 73       | 0.63%   |
| Gigabyte 970A-DS3P | 72       | 0.62%   |
| MSI MS-7996        | 70       | 0.6%    |
| HP Compaq          | 68       | 0.58%   |
| Gigabyte B450M     | 68       | 0.58%   |
| MSI MS-7817        | 67       | 0.58%   |
| Dell OptiPlex      | 65       | 0.56%   |
| ASUS H110M-R       | 59       | 0.51%   |
| Gigabyte B450      | 55       | 0.47%   |
| ASUS S20           | 55       | 0.47%   |
| ASUS P8H77-V       | 53       | 0.45%   |
| ASUS P8H67-M       | 53       | 0.45%   |
| Intel SKYBAY       | 48       | 0.41%   |
| ASUS SABERTOOTH    | 48       | 0.41%   |
| ASUS P8H61-MX      | 47       | 0.4%    |
| Lenovo ThinkCentre | 46       | 0.39%   |
| ASRock G31M-S      | 46       | 0.39%   |
| MSI MS-7529        | 45       | 0.39%   |
| Gigabyte H61M-S1   | 45       | 0.39%   |
| Gigabyte A320M-S2H | 45       | 0.39%   |
| ASUS P7H55-M       | 45       | 0.39%   |
| Gigabyte G31M-ES2L | 43       | 0.37%   |
| ASUS P8B75-M       | 43       | 0.37%   |
| Gigabyte H310M     | 42       | 0.36%   |
| Acer Veriton       | 42       | 0.36%   |
| ASRock N68C-S      | 41       | 0.35%   |
| Gigabyte H61M-S2PV | 40       | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 1602     | 13.75%  |
| 2009    | 1026     | 8.81%   |
| 2011    | 1002     | 8.6%    |
| 2010    | 925      | 7.94%   |
| 2013    | 853      | 7.32%   |
| 2018    | 834      | 7.16%   |
| 2008    | 762      | 6.54%   |
| 2007    | 726      | 6.23%   |
| 2016    | 481      | 4.13%   |
| 2006    | 479      | 4.11%   |
| 2014    | 461      | 3.96%   |
| 2019    | 439      | 3.77%   |
| 2017    | 438      | 3.76%   |
| 2020    | 421      | 3.61%   |
| 2015    | 410      | 3.52%   |
| 2021    | 355      | 3.05%   |
| 2005    | 197      | 1.69%   |
| 2022    | 93       | 0.8%    |
| 2004    | 69       | 0.59%   |
| 2003    | 41       | 0.35%   |
| Unknown | 19       | 0.16%   |
| 2002    | 8        | 0.07%   |
| 2001    | 4        | 0.03%   |
| 2023    | 3        | 0.03%   |
| 2000    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 11649    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 11581    | 99.38%  |
| Enabled  | 72       | 0.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11647    | 99.98%  |
| Yes  | 2        | 0.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 3063     | 25.23%  |
| 8.01-16.0       | 2692     | 22.17%  |
| 4.01-8.0        | 1903     | 15.67%  |
| 16.01-24.0      | 1740     | 14.33%  |
| 1.01-2.0        | 1022     | 8.42%   |
| 2.01-3.0        | 647      | 5.33%   |
| 32.01-64.0      | 615      | 5.07%   |
| 0.51-1.0        | 157      | 1.29%   |
| 64.01-256.0     | 153      | 1.26%   |
| 24.01-32.0      | 131      | 1.08%   |
| 0.01-0.5        | 13       | 0.11%   |
| More than 256.0 | 3        | 0.02%   |
| Unknown         | 3        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 5050     | 38.23%  |
| 0.51-1.0    | 4565     | 34.56%  |
| 2.01-3.0    | 1596     | 12.08%  |
| 4.01-8.0    | 750      | 5.68%   |
| 3.01-4.0    | 644      | 4.88%   |
| 0.01-0.5    | 288      | 2.18%   |
| 8.01-16.0   | 223      | 1.69%   |
| 16.01-24.0  | 52       | 0.39%   |
| 32.01-64.0  | 15       | 0.11%   |
| 24.01-32.0  | 13       | 0.1%    |
| Unknown     | 11       | 0.08%   |
| 64.01-256.0 | 3        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 6122     | 49.58%  |
| 2       | 3334     | 27%     |
| 3       | 1637     | 13.26%  |
| 4       | 710      | 5.75%   |
| 5       | 290      | 2.35%   |
| 6       | 99       | 0.8%    |
| 0       | 81       | 0.66%   |
| 7       | 37       | 0.3%    |
| 8       | 18       | 0.15%   |
| 9       | 8        | 0.06%   |
| 10      | 3        | 0.02%   |
| Unknown | 2        | 0.02%   |
| 25      | 1        | 0.01%   |
| 18      | 1        | 0.01%   |
| 17      | 1        | 0.01%   |
| 13      | 1        | 0.01%   |
| 12      | 1        | 0.01%   |
| 11      | 1        | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6166     | 51.68%  |
| Yes       | 5765     | 48.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11541    | 99.06%  |
| No        | 109      | 0.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9050     | 76.39%  |
| Yes       | 2797     | 23.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10229    | 86.61%  |
| Yes       | 1582     | 13.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 11649    | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 1993     | 16.05%  |
| St Petersburg    | 805      | 6.48%   |
| Voronezh         | 768      | 6.18%   |
| Pecherskoye      | 421      | 3.39%   |
| Novosibirsk      | 381      | 3.07%   |
| Yekaterinburg    | 314      | 2.53%   |
| Krasnodar        | 274      | 2.21%   |
| Samara           | 250      | 2.01%   |
| Nizhniy Novgorod | 244      | 1.96%   |
| Rostov-on-Don    | 221      | 1.78%   |
| Chelyabinsk      | 199      | 1.6%    |
| Perm             | 198      | 1.59%   |
| Krasnoyarsk      | 155      | 1.25%   |
| Saratov          | 140      | 1.13%   |
| Omsk             | 136      | 1.1%    |
| Volgograd        | 119      | 0.96%   |
| Ufa              | 116      | 0.93%   |
| Kazan’         | 116      | 0.93%   |
| Stavropol        | 105      | 0.85%   |
| Barnaul          | 105      | 0.85%   |
| Vladivostok      | 104      | 0.84%   |
| Tyumen           | 98       | 0.79%   |
| Irkutsk          | 96       | 0.77%   |
| Khabarovsk       | 95       | 0.77%   |
| Ulyanovsk        | 81       | 0.65%   |
| Orenburg         | 80       | 0.64%   |
| Tomsk            | 75       | 0.6%    |
| Bryansk          | 74       | 0.6%    |
| Belgorod         | 73       | 0.59%   |
| Novokuznetsk     | 72       | 0.58%   |
| Kemerovo         | 72       | 0.58%   |
| Yaroslavl        | 69       | 0.56%   |
| Tolyatti         | 69       | 0.56%   |
| Tula             | 68       | 0.55%   |
| Cheboksary       | 66       | 0.53%   |
| Lipetsk          | 64       | 0.52%   |
| Izhevsk          | 64       | 0.52%   |
| Kaliningrad      | 61       | 0.49%   |
| Astrakhan        | 59       | 0.48%   |
| Ryazan           | 58       | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4757     | 7735   | 24.76%  |
| WDC                 | 4658     | 7992   | 24.25%  |
| Samsung Electronics | 1689     | 2564   | 8.79%   |
| Toshiba             | 1308     | 1945   | 6.81%   |
| Hitachi             | 1036     | 1452   | 5.39%   |
| Kingston            | 1005     | 1373   | 5.23%   |
| A-DATA Technology   | 332      | 460    | 1.73%   |
| China               | 316      | 450    | 1.64%   |
| SPCC                | 301      | 383    | 1.57%   |
| Crucial             | 287      | 384    | 1.49%   |
| Maxtor              | 278      | 351    | 1.45%   |
| OCZ                 | 231      | 302    | 1.2%    |
| Intel               | 218      | 372    | 1.13%   |
| SanDisk             | 216      | 315    | 1.12%   |
| Plextor             | 193      | 299    | 1%      |
| HGST                | 183      | 279    | 0.95%   |
| Apacer              | 181      | 246    | 0.94%   |
| Smartbuy            | 119      | 163    | 0.62%   |
| Patriot             | 110      | 146    | 0.57%   |
| AMD                 | 108      | 142    | 0.56%   |
| HUAWEI              | 88       | 103    | 0.46%   |
| Silicon Motion      | 87       | 107    | 0.45%   |
| GOODRAM             | 82       | 116    | 0.43%   |
| Corsair             | 81       | 120    | 0.42%   |
| Transcend           | 80       | 101    | 0.42%   |
| KingSpec            | 76       | 95     | 0.4%    |
| Netac               | 75       | 149    | 0.39%   |
| Unknown             | 64       | 101    | 0.33%   |
| Gigabyte Technology | 58       | 70     | 0.3%    |
| Phison              | 53       | 61     | 0.28%   |
| XPG                 | 45       | 56     | 0.23%   |
| KingDian            | 44       | 70     | 0.23%   |
| Fujitsu             | 40       | 47     | 0.21%   |
| Kingmax             | 35       | 62     | 0.18%   |
| XrayDisk            | 33       | 42     | 0.17%   |
| JMicron Technology  | 32       | 33     | 0.17%   |
| Foxline             | 31       | 38     | 0.16%   |
| Unknown             | 28       | 29     | 0.15%   |
| AXIOMTEK            | 27       | 29     | 0.14%   |
| Hewlett-Packard     | 25       | 42     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 390      | 1.77%   |
| Toshiba DT01ACA050 500GB         | 277      | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB   | 250      | 1.13%   |
| Seagate ST3500418AS 500GB        | 249      | 1.13%   |
| Toshiba HDWD110 1TB              | 246      | 1.11%   |
| WDC WD10EZEX-08WN4A0 1TB         | 223      | 1.01%   |
| Seagate ST1000DM003-1CH162 1TB   | 200      | 0.91%   |
| Toshiba DT01ACA100 1TB           | 196      | 0.89%   |
| Kingston SA400S37120G 120GB SSD  | 156      | 0.71%   |
| Kingston SA400S37240G 240GB SSD  | 154      | 0.7%    |
| Samsung SSD 860 EVO 250GB        | 148      | 0.67%   |
| Kingston SV300S37A120G 120GB SSD | 146      | 0.66%   |
| WDC WD5000AAKX-001CA0 500GB      | 137      | 0.62%   |
| Seagate ST3250410AS 250GB        | 134      | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 132      | 0.6%    |
| Seagate ST380011A 80GB           | 129      | 0.58%   |
| Seagate ST380815AS 80GB          | 126      | 0.57%   |
| Seagate ST31000524AS 1TB         | 121      | 0.55%   |
| Seagate ST3160815AS 160GB        | 118      | 0.53%   |
| Hitachi HDS721050CLA362 500GB    | 117      | 0.53%   |
| Seagate ST31000528AS 1TB         | 116      | 0.53%   |
| Seagate ST3250310AS 250GB        | 113      | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB   | 112      | 0.51%   |
| Seagate ST1000DM003-9YN162 1TB   | 103      | 0.47%   |
| Toshiba HDWD105 500GB            | 101      | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 99       | 0.45%   |
| Seagate ST3250318AS 250GB        | 91       | 0.41%   |
| Seagate ST250DM000-1BD141 250GB  | 90       | 0.41%   |
| Crucial CT480BX500SSD1 480GB     | 90       | 0.41%   |
| Seagate ST3500413AS 500GB        | 89       | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 86       | 0.39%   |
| SPCC Solid State Disk 120GB      | 82       | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB         | 80       | 0.36%   |
| Seagate ST3320613AS 320GB        | 80       | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB   | 78       | 0.35%   |
| Seagate ST3320620AS 320GB        | 76       | 0.34%   |
| Samsung SSD 860 EVO 500GB        | 75       | 0.34%   |
| WDC WD5000AADS-00S9B0 500GB      | 74       | 0.34%   |
| Hitachi HDS721616PLA380 160GB    | 70       | 0.32%   |
| SPCC Solid State Disk 64GB       | 69       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4739     | 7692   | 37.23%  |
| WDC                 | 4362     | 7329   | 34.27%  |
| Toshiba             | 1253     | 1832   | 9.84%   |
| Hitachi             | 1036     | 1452   | 8.14%   |
| Samsung Electronics | 754      | 1086   | 5.92%   |
| Maxtor              | 277      | 350    | 2.18%   |
| HGST                | 183      | 279    | 1.44%   |
| Fujitsu             | 39       | 46     | 0.31%   |
| Unknown             | 20       | 28     | 0.16%   |
| IBM/Hitachi         | 12       | 15     | 0.09%   |
| Hewlett-Packard     | 10       | 20     | 0.08%   |
| IBM                 | 4        | 4      | 0.03%   |
| USB3.0              | 3        | 3      | 0.02%   |
| Quantum             | 3        | 3      | 0.02%   |
| WD MediaMax         | 2        | 2      | 0.02%   |
| Synology            | 2        | 3      | 0.02%   |
| PHD 3.0             | 2        | 2      | 0.02%   |
| ExcelStor           | 2        | 2      | 0.02%   |
| CLOVER              | 2        | 2      | 0.02%   |
| ASMT106x            | 2        | 3      | 0.02%   |
| ASMT                | 2        | 10     | 0.02%   |
| Apple               | 2        | 2      | 0.02%   |
| Unknown             | 2        | 2      | 0.02%   |
| USB 3.0             | 1        | 1      | 0.01%   |
| USB                 | 1        | 1      | 0.01%   |
| Silicon             | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| Pioneer             | 1        | 1      | 0.01%   |
| MR2020              | 1        | 1      | 0.01%   |
| MARVELL             | 1        | 1      | 0.01%   |
| LIO-ORG             | 1        | 1      | 0.01%   |
| KESU                | 1        | 1      | 0.01%   |
| JMicron Technology  | 1        | 1      | 0.01%   |
| IET                 | 1        | 2      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |
| FreeBSD             | 1        | 1      | 0.01%   |
| External            | 1        | 1      | 0.01%   |
| ASMedia             | 1        | 2      | 0.01%   |
| AFAYA               | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 900      | 1226   | 16.73%  |
| Samsung Electronics | 640      | 933    | 11.89%  |
| WDC                 | 450      | 604    | 8.36%   |
| China               | 314      | 448    | 5.84%   |
| SPCC                | 283      | 360    | 5.26%   |
| Crucial             | 278      | 370    | 5.17%   |
| A-DATA Technology   | 273      | 358    | 5.07%   |
| OCZ                 | 230      | 301    | 4.27%   |
| SanDisk             | 176      | 262    | 3.27%   |
| Plextor             | 176      | 260    | 3.27%   |
| Apacer              | 161      | 219    | 2.99%   |
| Intel               | 157      | 274    | 2.92%   |
| Smartbuy            | 110      | 152    | 2.04%   |
| Patriot             | 103      | 138    | 1.91%   |
| AMD                 | 96       | 123    | 1.78%   |
| Toshiba             | 78       | 109    | 1.45%   |
| GOODRAM             | 77       | 111    | 1.43%   |
| Corsair             | 76       | 111    | 1.41%   |
| KingSpec            | 75       | 94     | 1.39%   |
| Transcend           | 72       | 89     | 1.34%   |
| Netac               | 62       | 133    | 1.15%   |
| KingDian            | 44       | 70     | 0.82%   |
| Gigabyte Technology | 42       | 46     | 0.78%   |
| Kingmax             | 35       | 62     | 0.65%   |
| Foxline             | 30       | 37     | 0.56%   |
| AXIOMTEK            | 27       | 29     | 0.5%    |
| XrayDisk            | 26       | 34     | 0.48%   |
| JMicron Technology  | 21       | 21     | 0.39%   |
| Qumo                | 20       | 27     | 0.37%   |
| Unknown             | 18       | 19     | 0.33%   |
| Team                | 13       | 14     | 0.24%   |
| Seagate             | 13       | 23     | 0.24%   |
| Londisk             | 13       | 14     | 0.24%   |
| KingFast            | 12       | 16     | 0.22%   |
| Micron Technology   | 11       | 15     | 0.2%    |
| Hewlett-Packard     | 11       | 17     | 0.2%    |
| Zheino              | 10       | 13     | 0.19%   |
| Palit               | 10       | 15     | 0.19%   |
| OCZ-VERTEX3         | 10       | 15     | 0.19%   |
| Unknown             | 9        | 13     | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 9854     | 20185  | 62.78%  |
| SSD     | 4516     | 7469   | 28.77%  |
| NVMe    | 1083     | 1624   | 6.9%    |
| Unknown | 228      | 266    | 1.45%   |
| MMC     | 16       | 22     | 0.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11272    | 27420  | 88.37%  |
| NVMe | 1077     | 1613   | 8.44%   |
| SAS  | 390      | 511    | 3.06%   |
| MMC  | 16       | 22     | 0.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 9614     | 18302  | 63.52%  |
| 0.51-1.0        | 3935     | 6698   | 26%     |
| 1.01-2.0        | 1057     | 1729   | 6.98%   |
| 2.01-3.0        | 236      | 402    | 1.56%   |
| 3.01-4.0        | 172      | 281    | 1.14%   |
| 4.01-10.0       | 101      | 209    | 0.67%   |
| 10.01-20.0      | 18       | 30     | 0.12%   |
| More than 100.0 | 1        | 1      | 0.01%   |
| 20.01-50.0      | 1        | 1      | 0.01%   |
| 0               | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 3300     | 25.17%  |
| 251-500        | 2270     | 17.31%  |
| 501-1000       | 1647     | 12.56%  |
| 1-20           | 1362     | 10.39%  |
| 51-100         | 1326     | 10.11%  |
| 1001-2000      | 1010     | 7.7%    |
| 21-50          | 766      | 5.84%   |
| Unknown        | 717      | 5.47%   |
| 2001-3000      | 361      | 2.75%   |
| More than 3000 | 353      | 2.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 6912     | 52.54%  |
| 21-50          | 1341     | 10.19%  |
| 101-250        | 1049     | 7.97%   |
| 51-100         | 879      | 6.68%   |
| 251-500        | 862      | 6.55%   |
| Unknown        | 717      | 5.45%   |
| 501-1000       | 704      | 5.35%   |
| 1001-2000      | 420      | 3.19%   |
| More than 3000 | 148      | 1.12%   |
| 2001-3000      | 123      | 0.93%   |
| 0              | 1        | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 151      | 189    | 2.74%   |
| Seagate ST3500418AS 500GB          | 110      | 141    | 2%      |
| Seagate ST3250410AS 250GB          | 88       | 113    | 1.6%    |
| WDC WD5000AAKX-001CA0 500GB        | 67       | 85     | 1.22%   |
| Seagate ST3250310AS 250GB          | 65       | 108    | 1.18%   |
| Seagate ST3320613AS 320GB          | 62       | 82     | 1.13%   |
| Seagate ST31000528AS 1TB           | 55       | 62     | 1%      |
| Seagate ST1000DM003-9YN162 1TB     | 54       | 64     | 0.98%   |
| Seagate ST1000DM003-1CH162 1TB     | 54       | 83     | 0.98%   |
| Hitachi HDS721050CLA362 500GB      | 46       | 54     | 0.84%   |
| WDC WD5000AADS-00S9B0 500GB        | 45       | 52     | 0.82%   |
| Seagate ST380011A 80GB             | 45       | 48     | 0.82%   |
| Seagate ST250DM000-1BD141 250GB    | 43       | 58     | 0.78%   |
| Seagate ST3160815AS 160GB          | 42       | 53     | 0.76%   |
| Seagate ST31000524AS 1TB           | 42       | 55     | 0.76%   |
| Seagate ST3250318AS 250GB          | 40       | 48     | 0.73%   |
| Hitachi HDS721010CLA332 1TB        | 39       | 46     | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB        | 38       | 43     | 0.69%   |
| Hitachi HDS721616PLA380 160GB      | 37       | 51     | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 36       | 45     | 0.65%   |
| WDC WD10EARS-00Y5B1 1TB            | 36       | 60     | 0.65%   |
| Seagate ST3160811AS 160GB          | 35       | 50     | 0.64%   |
| Seagate ST380815AS 80GB            | 34       | 46     | 0.62%   |
| Samsung Electronics HD160JJ/ 160GB | 33       | 53     | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 33       | 34     | 0.6%    |
| Samsung Electronics HD080HJ 80GB   | 32       | 42     | 0.58%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 31       | 40     | 0.56%   |
| Seagate ST3500413AS 500GB          | 31       | 34     | 0.56%   |
| Maxtor STM3250310AS 250GB          | 30       | 39     | 0.54%   |
| Seagate ST31500341AS 1TB           | 28       | 36     | 0.51%   |
| Hitachi HDP725050GLA360 500GB      | 28       | 40     | 0.51%   |
| WDC WD5000AAKS-00V1A0 500GB        | 26       | 31     | 0.47%   |
| Seagate ST3320620AS 320GB          | 26       | 34     | 0.47%   |
| Toshiba DT01ACA050 500GB           | 25       | 36     | 0.45%   |
| Samsung Electronics HD161HJ 160GB  | 25       | 31     | 0.45%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 22       | 27     | 0.4%    |
| Toshiba DT01ACA100 1TB             | 22       | 33     | 0.4%    |
| Seagate ST3500320AS 500GB          | 22       | 26     | 0.4%    |
| Samsung Electronics HD321KJ 320GB  | 22       | 27     | 0.4%    |
| Hitachi HDS721050CLA360 500GB      | 22       | 27     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1909     | 2747   | 37.21%  |
| WDC                 | 1533     | 2149   | 29.88%  |
| Hitachi             | 470      | 631    | 9.16%   |
| Samsung Electronics | 391      | 552    | 7.62%   |
| Toshiba             | 170      | 227    | 3.31%   |
| Maxtor              | 161      | 192    | 3.14%   |
| Kingston            | 97       | 108    | 1.89%   |
| OCZ                 | 51       | 68     | 0.99%   |
| SPCC                | 37       | 44     | 0.72%   |
| A-DATA Technology   | 33       | 47     | 0.64%   |
| HGST                | 31       | 38     | 0.6%    |
| Corsair             | 29       | 44     | 0.57%   |
| Intel               | 25       | 30     | 0.49%   |
| Kingmax             | 24       | 45     | 0.47%   |
| SanDisk             | 13       | 18     | 0.25%   |
| KingSpec            | 13       | 15     | 0.25%   |
| Plextor             | 12       | 23     | 0.23%   |
| IBM/Hitachi         | 11       | 14     | 0.21%   |
| China               | 11       | 13     | 0.21%   |
| Crucial             | 10       | 20     | 0.19%   |
| AMD                 | 10       | 13     | 0.19%   |
| Fujitsu             | 9        | 10     | 0.18%   |
| OCZ-VERTEX3         | 6        | 11     | 0.12%   |
| Netac               | 6        | 6      | 0.12%   |
| Neo                 | 4        | 8      | 0.08%   |
| Unknown             | 4        | 5      | 0.08%   |
| XPG                 | 3        | 5      | 0.06%   |
| Qumo                | 3        | 6      | 0.06%   |
| LITEONIT            | 3        | 3      | 0.06%   |
| KingDian            | 3        | 4      | 0.06%   |
| IBM                 | 3        | 3      | 0.06%   |
| Hewlett-Packard     | 3        | 4      | 0.06%   |
| Apacer              | 3        | 3      | 0.06%   |
| Verbatim            | 2        | 2      | 0.04%   |
| Smartbuy            | 2        | 2      | 0.04%   |
| Silicon Motion      | 2        | 3      | 0.04%   |
| Quantum             | 2        | 2      | 0.04%   |
| PNY                 | 2        | 2      | 0.04%   |
| Patriot             | 2        | 2      | 0.04%   |
| Intenso             | 2        | 7      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1908     | 2744   | 41.13%  |
| WDC                 | 1503     | 2097   | 32.4%   |
| Hitachi             | 470      | 631    | 10.13%  |
| Samsung Electronics | 367      | 522    | 7.91%   |
| Toshiba             | 167      | 224    | 3.6%    |
| Maxtor              | 161      | 192    | 3.47%   |
| HGST                | 31       | 38     | 0.67%   |
| IBM/Hitachi         | 11       | 14     | 0.24%   |
| Fujitsu             | 9        | 10     | 0.19%   |
| IBM                 | 3        | 3      | 0.06%   |
| Hewlett-Packard     | 3        | 4      | 0.06%   |
| Quantum             | 2        | 2      | 0.04%   |
| WD MediaMax         | 1        | 1      | 0.02%   |
| ExcelStor           | 1        | 1      | 0.02%   |
| ASMT                | 1        | 2      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4076     | 6486   | 89.29%  |
| SSD  | 467      | 632    | 10.23%  |
| NVMe | 22       | 37     | 0.48%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31000528AS 1TB          | 7        | 9      | 3.85%   |
| Seagate ST31000524AS 1TB          | 7        | 9      | 3.85%   |
| Seagate ST3500418AS 500GB         | 5        | 6      | 2.75%   |
| Seagate ST3500412AS 500GB         | 5        | 6      | 2.75%   |
| Hitachi HDS721010DLE630 1TB       | 5        | 6      | 2.75%   |
| Seagate ST31000333AS 1TB          | 3        | 3      | 1.65%   |
| Samsung Electronics SP0411N 40GB  | 3        | 4      | 1.65%   |
| Maxtor 6Y080L0 82GB               | 3        | 3      | 1.65%   |
| Hitachi HDS721010CLA332 1TB       | 3        | 3      | 1.65%   |
| HGST HTS545050A7E380 500GB        | 3        | 3      | 1.65%   |
| WDC WD5000AAKS-00V1A0 500GB       | 2        | 2      | 1.1%    |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 1.1%    |
| WDC WD20EARS-00MVWB0 2TB          | 2        | 2      | 1.1%    |
| WDC WD15EARS-00MVWB0 1TB          | 2        | 4      | 1.1%    |
| Seagate STM3500418AS 500GB        | 2        | 2      | 1.1%    |
| Seagate ST500DM005 HD502HJ 500GB  | 2        | 3      | 1.1%    |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 1.1%    |
| Seagate ST500DM002-1BC142 500GB   | 2        | 2      | 1.1%    |
| Seagate ST3750528AS 752GB         | 2        | 2      | 1.1%    |
| Seagate ST3320613AS 320GB         | 2        | 3      | 1.1%    |
| Seagate ST3250318AS 250GB         | 2        | 2      | 1.1%    |
| Seagate ST32000542AS 2TB          | 2        | 4      | 1.1%    |
| Seagate ST3160318AS 160GB         | 2        | 2      | 1.1%    |
| Seagate ST250DM000-1BD141 250GB   | 2        | 2      | 1.1%    |
| Samsung Electronics HD503HI 500GB | 2        | 2      | 1.1%    |
| Samsung Electronics HD204UI 2TB   | 2        | 2      | 1.1%    |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 1.1%    |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 1.1%    |
| Hitachi HDS721050DLE630 500GB     | 2        | 2      | 1.1%    |
| Hitachi HDS721025CLA382 250GB     | 2        | 2      | 1.1%    |
| WDC WD800JD-22LSA0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800JB-00JJC0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800JB-00FMA0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800BB-55JKC0 80GB           | 1        | 2      | 0.55%   |
| WDC WD800BB-22JHA0 80GB           | 1        | 1      | 0.55%   |
| WDC WD800BB-00JKC0 80GB           | 1        | 2      | 0.55%   |
| WDC WD800BB-00JHC0 80GB           | 1        | 1      | 0.55%   |
| WDC WD7501AALS-00J7B0 752GB       | 1        | 2      | 0.55%   |
| WDC WD6400AACS-00G8B0 640GB       | 1        | 1      | 0.55%   |
| WDC WD5001AALS-00E3A0 500GB       | 1        | 1      | 0.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 67       | 79     | 37.22%  |
| WDC                 | 48       | 63     | 26.67%  |
| Samsung Electronics | 22       | 24     | 12.22%  |
| Hitachi             | 17       | 18     | 9.44%   |
| Maxtor              | 7        | 7      | 3.89%   |
| Toshiba             | 6        | 6      | 3.33%   |
| HGST                | 5        | 5      | 2.78%   |
| Transcend           | 1        | 1      | 0.56%   |
| OCZ                 | 1        | 1      | 0.56%   |
| Intel               | 1        | 1      | 0.56%   |
| Hewlett-Packard     | 1        | 1      | 0.56%   |
| GOODRAM             | 1        | 1      | 0.56%   |
| Crucial             | 1        | 1      | 0.56%   |
| Corsair             | 1        | 1      | 0.56%   |
| A-DATA Technology   | 1        | 1      | 0.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 8147     | 17976  | 55.78%  |
| Malfunc  | 4399     | 7155   | 30.12%  |
| Detected | 1883     | 4225   | 12.89%  |
| Failed   | 176      | 210    | 1.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 7707     | 52.85%  |
| AMD                              | 3046     | 20.89%  |
| JMicron Technology               | 774      | 5.31%   |
| Nvidia                           | 769      | 5.27%   |
| Marvell Technology Group         | 431      | 2.96%   |
| Samsung Electronics              | 381      | 2.61%   |
| ASMedia Technology               | 371      | 2.54%   |
| VIA Technologies                 | 208      | 1.43%   |
| Silicon Motion                   | 153      | 1.05%   |
| Kingston Technology Company      | 127      | 0.87%   |
| Phison Electronics               | 124      | 0.85%   |
| SanDisk                          | 82       | 0.56%   |
| ADATA Technology                 | 70       | 0.48%   |
| Realtek Semiconductor            | 59       | 0.4%    |
| Silicon Integrated Systems [SiS] | 39       | 0.27%   |
| Silicon Image                    | 36       | 0.25%   |
| Integrated Technology Express    | 31       | 0.21%   |
| Lite-On Technology               | 30       | 0.21%   |
| MAXIO Technology (Hangzhou)      | 19       | 0.13%   |
| SK hynix                         | 15       | 0.1%    |
| Micron/Crucial Technology        | 12       | 0.08%   |
| Adaptec                          | 10       | 0.07%   |
| Netac Technology                 | 9        | 0.06%   |
| Broadcom / LSI                   | 9        | 0.06%   |
| LSI Logic / Symbios Logic        | 7        | 0.05%   |
| Hewlett-Packard                  | 6        | 0.04%   |
| Micron Technology                | 5        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 5        | 0.03%   |
| ULi Electronics                  | 4        | 0.03%   |
| Toshiba America Info Systems     | 4        | 0.03%   |
| Shenzhen Longsys Electronics     | 4        | 0.03%   |
| Promise Technology               | 4        | 0.03%   |
| MCST                             | 4        | 0.03%   |
| KIOXIA                           | 4        | 0.03%   |
| Seagate Technology               | 3        | 0.02%   |
| OCZ Technology Group             | 3        | 0.02%   |
| Union Memory (Shenzhen)          | 2        | 0.01%   |
| Solid State Storage Technology   | 2        | 0.01%   |
| INNOGRIT                         | 2        | 0.01%   |
| Broadcom                         | 2        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1408     | 6.83%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1206     | 5.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1060     | 5.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1056     | 5.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 756      | 3.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 689      | 3.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 616      | 2.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 597      | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 595      | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 594      | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 578      | 2.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 474      | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 441      | 2.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 425      | 2.06%   |
| Nvidia MCP61 SATA Controller                                                            | 399      | 1.93%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 381      | 1.85%   |
| Nvidia MCP61 IDE                                                                        | 375      | 1.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 357      | 1.73%   |
| JMicron JMB368 IDE controller                                                           | 296      | 1.44%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 277      | 1.34%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 276      | 1.34%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 261      | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 242      | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 191      | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 188      | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 188      | 0.91%   |
| AMD FCH SATA Controller D                                                               | 188      | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 186      | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 185      | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 183      | 0.89%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 168      | 0.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 163      | 0.79%   |
| AMD FCH IDE Controller                                                                  | 143      | 0.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 140      | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 137      | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 136      | 0.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 126      | 0.61%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 122      | 0.59%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 119      | 0.58%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 116      | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7462     | 50.79%  |
| IDE  | 5815     | 39.58%  |
| NVMe | 1086     | 7.39%   |
| RAID | 303      | 2.06%   |
| SAS  | 21       | 0.14%   |
| SCSI | 6        | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 7848     | 67.37%  |
| AMD          | 3792     | 32.55%  |
| CentaurHauls | 2        | 0.02%   |
| PowerMac7,2  | 1        | 0.01%   |
| MBE8C-PC     | 1        | 0.01%   |
| Loongson     | 1        | 0.01%   |
| Elbrus-MCST  | 1        | 0.01%   |
| E8C/EATX     | 1        | 0.01%   |
| E8C-SWTX     | 1        | 0.01%   |
| Unknown      | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 168      | 1.43%   |
| Intel Pentium 4 CPU 3.00GHz                 | 113      | 0.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 113      | 0.96%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 112      | 0.95%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 108      | 0.92%   |
| AMD FX-6300 Six-Core Processor              | 105      | 0.89%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 104      | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 103      | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 102      | 0.87%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 99       | 0.84%   |
| AMD FX-8350 Eight-Core Processor            | 91       | 0.77%   |
| AMD Athlon II X2 250 Processor              | 90       | 0.76%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 86       | 0.73%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 84       | 0.71%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 82       | 0.7%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 79       | 0.67%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 77       | 0.65%   |
| AMD FX-4300 Quad-Core Processor             | 77       | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 75       | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 72       | 0.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 71       | 0.6%    |
| AMD FX-8320 Eight-Core Processor            | 67       | 0.57%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 66       | 0.56%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 65       | 0.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 63       | 0.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 60       | 0.51%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 59       | 0.5%    |
| Intel Core i3-10100 CPU @ 3.60GHz           | 59       | 0.5%    |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 58       | 0.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 58       | 0.49%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 58       | 0.49%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 58       | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 57       | 0.48%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 56       | 0.48%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 55       | 0.47%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 55       | 0.47%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 54       | 0.46%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 54       | 0.46%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 54       | 0.46%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 54       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1619     | 13.78%  |
| Intel Core i3           | 1208     | 10.28%  |
| Intel Core 2 Duo        | 752      | 6.4%    |
| Intel Celeron           | 694      | 5.91%   |
| Intel Pentium           | 673      | 5.73%   |
| Intel Core i7           | 646      | 5.5%    |
| AMD FX                  | 625      | 5.32%   |
| AMD Ryzen 5             | 541      | 4.61%   |
| Intel Xeon              | 516      | 4.39%   |
| AMD Athlon 64 X2        | 407      | 3.46%   |
| Intel Pentium Dual-Core | 381      | 3.24%   |
| Intel Core 2 Quad       | 347      | 2.95%   |
| AMD Athlon II X2        | 323      | 2.75%   |
| Intel Pentium 4         | 257      | 2.19%   |
| AMD Ryzen 7             | 202      | 1.72%   |
| AMD Phenom II X4        | 202      | 1.72%   |
| AMD Ryzen 3             | 162      | 1.38%   |
| Other                   | 155      | 1.32%   |
| AMD Athlon II X4        | 147      | 1.25%   |
| Intel Pentium Dual      | 144      | 1.23%   |
| Intel Core 2            | 134      | 1.14%   |
| Intel Atom              | 119      | 1.01%   |
| AMD Athlon II X3        | 117      | 1%      |
| Intel Pentium D         | 106      | 0.9%    |
| AMD A8                  | 103      | 0.88%   |
| AMD A10                 | 101      | 0.86%   |
| AMD Phenom              | 99       | 0.84%   |
| AMD A4                  | 97       | 0.83%   |
| AMD Athlon 64           | 89       | 0.76%   |
| AMD Phenom II X6        | 82       | 0.7%    |
| AMD A6                  | 76       | 0.65%   |
| AMD Athlon              | 74       | 0.63%   |
| Intel Pentium Gold      | 73       | 0.62%   |
| AMD Athlon X4           | 73       | 0.62%   |
| AMD Ryzen 9             | 55       | 0.47%   |
| AMD Sempron             | 42       | 0.36%   |
| Intel Genuine           | 36       | 0.31%   |
| AMD Phenom II X2        | 33       | 0.28%   |
| Intel Core i9           | 29       | 0.25%   |
| AMD Phenom II X3        | 23       | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 4876     | 40.75%  |
| 4       | 3598     | 30.07%  |
| 6       | 1115     | 9.32%   |
| Unknown | 794      | 6.63%   |
| 1       | 635      | 5.31%   |
| 8       | 447      | 3.74%   |
| 3       | 305      | 2.55%   |
| 12      | 86       | 0.72%   |
| 16      | 40       | 0.33%   |
| 10      | 39       | 0.33%   |
| 24      | 14       | 0.12%   |
| 18      | 5        | 0.04%   |
| 20      | 4        | 0.03%   |
| 14      | 3        | 0.03%   |
| 32      | 2        | 0.02%   |
| 28      | 1        | 0.01%   |
| 22      | 1        | 0.01%   |
| 15      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 11581    | 99.38%  |
| 2       | 63       | 0.54%   |
| Unknown | 7        | 0.06%   |
| 4       | 1        | 0.01%   |
| 0       | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 6698     | 56.12%  |
| 2       | 4440     | 37.2%   |
| Unknown | 794      | 6.65%   |
| 8       | 2        | 0.02%   |
| 6       | 2        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 11403    | 97.78%  |
| 32-bit         | 184      | 1.58%   |
| Unknown        | 70       | 0.6%    |
| 64-bit         | 5        | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1202     | 10.03%  |
| 0x1067a    | 1011     | 8.44%   |
| 0x206a7    | 924      | 7.71%   |
| 0x306a9    | 827      | 6.9%    |
| 0x306c3    | 811      | 6.77%   |
| 0x010000c8 | 497      | 4.15%   |
| 0x506e3    | 414      | 3.46%   |
| 0x906e9    | 295      | 2.46%   |
| 0x906ea    | 292      | 2.44%   |
| 0x6fd      | 276      | 2.3%    |
| 0x10676    | 265      | 2.21%   |
| 0x06000852 | 233      | 1.94%   |
| 0x6fb      | 230      | 1.92%   |
| 0x06001119 | 219      | 1.83%   |
| 0xa0653    | 185      | 1.54%   |
| 0x0600084f | 171      | 1.43%   |
| 0x0800820d | 168      | 1.4%    |
| 0x08701021 | 164      | 1.37%   |
| 0x010000db | 146      | 1.22%   |
| 0x106e5    | 121      | 1.01%   |
| 0x20655    | 106      | 0.88%   |
| 0x06003106 | 99       | 0.83%   |
| 0x08108109 | 93       | 0.78%   |
| 0x906eb    | 92       | 0.77%   |
| 0x08001138 | 91       | 0.76%   |
| 0x206d7    | 86       | 0.72%   |
| 0xf49      | 85       | 0.71%   |
| 0x306f2    | 84       | 0.7%    |
| 0x6f6      | 82       | 0.68%   |
| 0x6f2      | 81       | 0.68%   |
| 0x08101016 | 76       | 0.63%   |
| 0x010000c7 | 76       | 0.63%   |
| 0xf41      | 74       | 0.62%   |
| 0x03000027 | 70       | 0.58%   |
| 0x010000dc | 70       | 0.58%   |
| 0x20652    | 69       | 0.58%   |
| 0x0600063d | 69       | 0.58%   |
| 0xa0671    | 66       | 0.55%   |
| 0x0600063e | 65       | 0.54%   |
| 0x10677    | 64       | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 1309     | 11.14%  |
| SandyBridge      | 1046     | 8.9%    |
| K10              | 1026     | 8.73%   |
| Haswell          | 944      | 8.03%   |
| IvyBridge        | 933      | 7.94%   |
| KabyLake         | 823      | 7%      |
| Core             | 792      | 6.74%   |
| Piledriver       | 711      | 6.05%   |
| K8 Hammer        | 507      | 4.31%   |
| NetBurst         | 475      | 4.04%   |
| Skylake          | 459      | 3.91%   |
| Zen              | 317      | 2.7%    |
| Zen+             | 314      | 2.67%   |
| Zen 2            | 288      | 2.45%   |
| CometLake        | 262      | 2.23%   |
| Westmere         | 206      | 1.75%   |
| Unknown          | 175      | 1.49%   |
| Nehalem          | 171      | 1.46%   |
| Zen 3            | 147      | 1.25%   |
| Bulldozer        | 142      | 1.21%   |
| Steamroller      | 111      | 0.94%   |
| Silvermont       | 100      | 0.85%   |
| Bonnell          | 97       | 0.83%   |
| K10 Llano        | 76       | 0.65%   |
| Excavator        | 55       | 0.47%   |
| Goldmont plus    | 53       | 0.45%   |
| Alderlake Hybrid | 41       | 0.35%   |
| Icelake          | 38       | 0.32%   |
| Goldmont         | 25       | 0.21%   |
| Jaguar           | 24       | 0.2%    |
| Broadwell        | 24       | 0.2%    |
| Bobcat           | 22       | 0.19%   |
| Tremont          | 12       | 0.1%    |
| K6               | 11       | 0.09%   |
| Puma             | 7        | 0.06%   |
| P6               | 5        | 0.04%   |
| TigerLake        | 3        | 0.03%   |
| K8 & K10 hybrid  | 1        | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 5847     | 47.42%  |
| AMD                                          | 3276     | 26.57%  |
| Intel                                        | 3143     | 25.49%  |
| VIA Technologies                             | 15       | 0.12%   |
| Matrox Electronics Systems                   | 15       | 0.12%   |
| ASPEED Technology                            | 15       | 0.12%   |
| ATI Technologies                             | 7        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.02%   |
| S3 Graphics                                  | 3        | 0.02%   |
| Silicon Motion                               | 2        | 0.02%   |
| Zhaoxin                                      | 1        | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.01%   |
| Loongson Technology                          | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 384      | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 373      | 2.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 304      | 2.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 273      | 2.13%   |
| Nvidia GK208B [GeForce GT 710]                                              | 270      | 2.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 255      | 1.98%   |
| Nvidia GT218 [GeForce 210]                                                  | 253      | 1.97%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 215      | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 214      | 1.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 212      | 1.65%   |
| Nvidia GF108 [GeForce GT 630]                                               | 177      | 1.38%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 175      | 1.36%   |
| Intel HD Graphics 530                                                       | 170      | 1.32%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 167      | 1.3%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 148      | 1.15%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 148      | 1.15%   |
| Nvidia GF119 [GeForce GT 610]                                               | 146      | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 143      | 1.11%   |
| Intel HD Graphics 630                                                       | 136      | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 130      | 1.01%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 128      | 1%      |
| Nvidia GF108 [GeForce GT 430]                                               | 127      | 0.99%   |
| Nvidia GK208B [GeForce GT 730]                                              | 124      | 0.97%   |
| AMD RS780L [Radeon 3000]                                                    | 120      | 0.93%   |
| Nvidia G92 [GeForce GTS 250]                                                | 119      | 0.93%   |
| Nvidia GF108 [GeForce GT 440]                                               | 117      | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 116      | 0.9%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 112      | 0.87%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 108      | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 107      | 0.83%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 101      | 0.79%   |
| Nvidia GT215 [GeForce GT 240]                                               | 98       | 0.76%   |
| Nvidia GF108 [GeForce GT 730]                                               | 98       | 0.76%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 95       | 0.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 93       | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 92       | 0.72%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 92       | 0.72%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 90       | 0.7%    |
| Intel HD Graphics 510                                                       | 90       | 0.7%    |
| Nvidia GF106 [GeForce GTS 450]                                              | 88       | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| 1 x Nvidia                    | 5610     | 47.07%  |
| 1 x AMD                       | 2939     | 24.66%  |
| 1 x Intel                     | 2758     | 23.14%  |
| 2 x AMD                       | 260      | 2.18%   |
| Intel + Nvidia                | 153      | 1.28%   |
| AMD + Nvidia                  | 48       | 0.4%    |
| Intel + AMD                   | 40       | 0.34%   |
| 2 x Nvidia                    | 33       | 0.28%   |
| 1 x VIA                       | 15       | 0.13%   |
| 1 x Matrox                    | 13       | 0.11%   |
| 1 x ASPEED                    | 13       | 0.11%   |
| Other                         | 8        | 0.07%   |
| 3 x AMD                       | 4        | 0.03%   |
| 3 x Nvidia                    | 3        | 0.03%   |
| 1 x SiS                       | 3        | 0.03%   |
| 1 x Silicon Motion            | 2        | 0.02%   |
| 1 x S3 Graphics               | 2        | 0.02%   |
| Nvidia + Matrox               | 2        | 0.02%   |
| Nvidia + ASPEED               | 2        | 0.02%   |
| 2 x Intel                     | 1        | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1        | 0.01%   |
| 1 x XGI                       | 1        | 0.01%   |
| Nvidia + Zhaoxin              | 1        | 0.01%   |
| 1 x Loongson Technology       | 1        | 0.01%   |
| Intel + 2 x Nvidia            | 1        | 0.01%   |
| Intel + 2 x AMD               | 1        | 0.01%   |
| Intel + SiS + 1 x S3 Graphics | 1        | 0.01%   |
| Intel + AMD + 4 x Nvidia      | 1        | 0.01%   |
| AMD + 2 x Nvidia              | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 8544     | 69.66%  |
| Proprietary | 2380     | 19.4%   |
| Unknown     | 1341     | 10.93%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3362     | 27.22%  |
| 1.01-2.0   | 2465     | 19.96%  |
| 0.51-1.0   | 2387     | 19.33%  |
| 0.01-0.5   | 2325     | 18.83%  |
| 3.01-4.0   | 933      | 7.56%   |
| 7.01-8.0   | 404      | 3.27%   |
| 5.01-6.0   | 217      | 1.76%   |
| 2.01-3.0   | 161      | 1.3%    |
| 8.01-16.0  | 83       | 0.67%   |
| 4.01-5.0   | 6        | 0.05%   |
| 16.01-24.0 | 6        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 2698     | 24.32%  |
| Goldstar             | 1554     | 14.01%  |
| Acer                 | 1211     | 10.92%  |
| BenQ                 | 965      | 8.7%    |
| Philips              | 743      | 6.7%    |
| ViewSonic            | 549      | 4.95%   |
| AOC                  | 520      | 4.69%   |
| Dell                 | 481      | 4.34%   |
| Ancor Communications | 367      | 3.31%   |
| Hewlett-Packard      | 298      | 2.69%   |
| NEC Computers        | 244      | 2.2%    |
| Iiyama               | 147      | 1.33%   |
| Sony                 | 105      | 0.95%   |
| Unknown              | 77       | 0.69%   |
| ASUSTek Computer     | 66       | 0.59%   |
| Envision Peripherals | 61       | 0.55%   |
| LG Electronics       | 58       | 0.52%   |
| Plain Tree Systems   | 56       | 0.5%    |
| HHT                  | 46       | 0.41%   |
| Lenovo               | 45       | 0.41%   |
| Packard Bell         | 39       | 0.35%   |
| ___                  | 32       | 0.29%   |
| Toshiba              | 25       | 0.23%   |
| Fujitsu Siemens      | 24       | 0.22%   |
| Mi                   | 22       | 0.2%    |
| CHR                  | 22       | 0.2%    |
| KTC                  | 21       | 0.19%   |
| VIE                  | 20       | 0.18%   |
| MiTAC                | 20       | 0.18%   |
| HUAWEI               | 18       | 0.16%   |
| HannStar             | 18       | 0.16%   |
| JRY                  | 17       | 0.15%   |
| MStar                | 15       | 0.14%   |
| MSI                  | 15       | 0.14%   |
| HKC                  | 15       | 0.14%   |
| Panasonic            | 14       | 0.13%   |
| Haier                | 14       | 0.13%   |
| AGO                  | 14       | 0.13%   |
| Hitachi              | 13       | 0.12%   |
| CTV                  | 12       | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 81       | 0.7%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 71       | 0.62%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                   | 71       | 0.62%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 65       | 0.56%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 60       | 0.52%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 57       | 0.49%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch | 56       | 0.49%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 46       | 0.4%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 46       | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 45       | 0.39%   |
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch              | 45       | 0.39%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch  | 43       | 0.37%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 40       | 0.35%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 40       | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 37       | 0.32%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                    | 37       | 0.32%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 34       | 0.29%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 33       | 0.29%   |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                    | 32       | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 31       | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 30       | 0.26%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 29       | 0.25%   |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                 | 28       | 0.24%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 28       | 0.24%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 27       | 0.23%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 27       | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 26       | 0.23%   |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                     | 26       | 0.23%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch | 25       | 0.22%   |
| Plain Tree Systems LCD Monitor PTS06A5 1280x1024 337x270mm 17.0-inch | 25       | 0.22%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 25       | 0.22%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 25       | 0.22%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 25       | 0.22%   |
| Goldstar L1952S GSM4AE0 1280x1024 376x301mm 19.0-inch                | 24       | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 23       | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 23       | 0.2%    |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                | 23       | 0.2%    |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                | 23       | 0.2%    |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch | 22       | 0.19%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                 | 22       | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 4760     | 43.6%   |
| 1280x1024 (SXGA)   | 2250     | 20.61%  |
| 1680x1050 (WSXGA+) | 623      | 5.71%   |
| 1440x900 (WXGA+)   | 547      | 5.01%   |
| 1366x768 (WXGA)    | 447      | 4.09%   |
| 1600x900 (HD+)     | 388      | 3.55%   |
| 3840x2160 (4K)     | 385      | 3.53%   |
| 2560x1440 (QHD)    | 379      | 3.47%   |
| 1920x1200 (WUXGA)  | 206      | 1.89%   |
| 1360x768           | 190      | 1.74%   |
| 1024x768 (XGA)     | 154      | 1.41%   |
| 2560x1080          | 88       | 0.81%   |
| Unknown            | 88       | 0.81%   |
| 1600x1200          | 86       | 0.79%   |
| 3440x1440          | 55       | 0.5%    |
| 1280x720 (HD)      | 37       | 0.34%   |
| 1920x540           | 31       | 0.28%   |
| 1400x1050          | 24       | 0.22%   |
| 3840x1080          | 22       | 0.2%    |
| 2288x1287          | 17       | 0.16%   |
| 2048x1536          | 13       | 0.12%   |
| 1280x960           | 13       | 0.12%   |
| 1152x864           | 13       | 0.12%   |
| 2048x1152          | 9        | 0.08%   |
| 4480x1440          | 8        | 0.07%   |
| 1920x1440          | 8        | 0.07%   |
| 2560x1600          | 6        | 0.05%   |
| 5760x2160          | 5        | 0.05%   |
| 3200x1080          | 5        | 0.05%   |
| 7680x2160          | 4        | 0.04%   |
| 5760x1080          | 4        | 0.04%   |
| 3600x1080          | 4        | 0.04%   |
| 2160x1200          | 4        | 0.04%   |
| 1280x768           | 3        | 0.03%   |
| 5120x1440          | 2        | 0.02%   |
| 5120x1080          | 2        | 0.02%   |
| 4093x4093          | 2        | 0.02%   |
| 4000x1440          | 2        | 0.02%   |
| 3840x2560          | 2        | 0.02%   |
| 3840x1600          | 2        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 1791     | 16.07%  |
| 19      | 1578     | 14.16%  |
| 23      | 1429     | 12.82%  |
| 24      | 1138     | 10.21%  |
| 17      | 1107     | 9.93%   |
| 27      | 737      | 6.61%   |
| 18      | 620      | 5.56%   |
| 20      | 513      | 4.6%    |
| Unknown | 449      | 4.03%   |
| 22      | 386      | 3.46%   |
| 15      | 282      | 2.53%   |
| 31      | 176      | 1.58%   |
| 34      | 129      | 1.16%   |
| 40      | 118      | 1.06%   |
| 72      | 91       | 0.82%   |
| 32      | 83       | 0.74%   |
| 54      | 80       | 0.72%   |
| 52      | 45       | 0.4%    |
| 16      | 41       | 0.37%   |
| 25      | 39       | 0.35%   |
| 84      | 34       | 0.3%    |
| 48      | 27       | 0.24%   |
| 46      | 27       | 0.24%   |
| 42      | 21       | 0.19%   |
| 12      | 20       | 0.18%   |
| 43      | 17       | 0.15%   |
| 26      | 17       | 0.15%   |
| 14      | 16       | 0.14%   |
| 142     | 15       | 0.13%   |
| 28      | 15       | 0.13%   |
| 33      | 12       | 0.11%   |
| 13      | 12       | 0.11%   |
| 65      | 9        | 0.08%   |
| 29      | 9        | 0.08%   |
| 58      | 8        | 0.07%   |
| 50      | 7        | 0.06%   |
| 37      | 7        | 0.06%   |
| 60      | 6        | 0.05%   |
| 39      | 6        | 0.05%   |
| 47      | 5        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 3780     | 34.47%  |
| 501-600        | 3156     | 28.78%  |
| 301-350        | 1405     | 12.81%  |
| 351-400        | 1121     | 10.22%  |
| Unknown        | 449      | 4.09%   |
| 601-700        | 241      | 2.2%    |
| 701-800        | 225      | 2.05%   |
| 1001-1500      | 221      | 2.02%   |
| 1501-2000      | 129      | 1.18%   |
| 801-900        | 89       | 0.81%   |
| 901-1000       | 85       | 0.78%   |
| 201-300        | 46       | 0.42%   |
| More than 2000 | 19       | 0.17%   |
| 1-100          | 1        | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 6100     | 57.18%  |
| 5/4     | 2133     | 19.99%  |
| 16/10   | 1309     | 12.27%  |
| 4/3     | 445      | 4.17%   |
| Unknown | 337      | 3.16%   |
| 21/9    | 183      | 1.72%   |
| 3/2     | 99       | 0.93%   |
| 6/5     | 37       | 0.35%   |
| 1.00    | 15       | 0.14%   |
| 32/9    | 9        | 0.08%   |
| 2.00    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4041     | 36.72%  |
| 151-200        | 2567     | 23.33%  |
| 141-150        | 1565     | 14.22%  |
| 301-350        | 754      | 6.85%   |
| Unknown        | 449      | 4.08%   |
| 351-500        | 406      | 3.69%   |
| More than 1000 | 330      | 3%      |
| 251-300        | 302      | 2.74%   |
| 501-1000       | 215      | 1.95%   |
| 101-110        | 178      | 1.62%   |
| 111-120        | 119      | 1.08%   |
| 121-130        | 25       | 0.23%   |
| 71-80          | 22       | 0.2%    |
| 131-140        | 15       | 0.14%   |
| 81-90          | 9        | 0.08%   |
| 91-100         | 5        | 0.05%   |
| 61-70          | 1        | 0.01%   |
| 51-60          | 1        | 0.01%   |
| 1-40           | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 7406     | 69.61%  |
| 101-120       | 2142     | 20.13%  |
| Unknown       | 449      | 4.22%   |
| 1-50          | 392      | 3.68%   |
| 121-160       | 172      | 1.62%   |
| 161-240       | 76       | 0.71%   |
| More than 240 | 2        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9802     | 82.29%  |
| 0     | 1094     | 9.18%   |
| 2     | 947      | 7.95%   |
| 3     | 65       | 0.55%   |
| 4     | 3        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8357     | 55.67%  |
| Intel                                  | 1706     | 11.36%  |
| Qualcomm Atheros                       | 1442     | 9.61%   |
| Nvidia                                 | 665      | 4.43%   |
| Ralink Technology                      | 385      | 2.56%   |
| Huawei Technologies                    | 262      | 1.75%   |
| Marvell Technology Group               | 225      | 1.5%    |
| TP-Link                                | 209      | 1.39%   |
| Ralink                                 | 191      | 1.27%   |
| VIA Technologies                       | 184      | 1.23%   |
| D-Link System                          | 147      | 0.98%   |
| Broadcom                               | 132      | 0.88%   |
| D-Link                                 | 127      | 0.85%   |
| ASUSTek Computer                       | 105      | 0.7%    |
| Qualcomm Atheros Communications        | 98       | 0.65%   |
| Xiaomi                                 | 69       | 0.46%   |
| ZTE WCDMA Technologies MSM             | 68       | 0.45%   |
| Broadcom Limited                       | 67       | 0.45%   |
| MediaTek                               | 61       | 0.41%   |
| Samsung Electronics                    | 45       | 0.3%    |
| Sundance Technology Inc / IC Plus      | 37       | 0.25%   |
| 3Com                                   | 31       | 0.21%   |
| Silicon Integrated Systems [SiS]       | 29       | 0.19%   |
| Microsoft                              | 23       | 0.15%   |
| NetGear                                | 19       | 0.13%   |
| Mercucys                               | 16       | 0.11%   |
| IMC Networks                           | 16       | 0.11%   |
| ZyXEL Communications                   | 15       | 0.1%    |
| HTC (High Tech Computer)               | 15       | 0.1%    |
| Gemtek                                 | 15       | 0.1%    |
| Aquantia                               | 15       | 0.1%    |
| ASIX Electronics                       | 14       | 0.09%   |
| Spreadtrum Communications              | 12       | 0.08%   |
| Qualcomm                               | 11       | 0.07%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.07%   |
| OPPO Electronics                       | 10       | 0.07%   |
| LSI                                    | 10       | 0.07%   |
| Tenda                                  | 8        | 0.05%   |
| T & A Mobile Phones                    | 8        | 0.05%   |
| GCT Semiconductor                      | 8        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7035     | 43.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 473      | 2.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 404      | 2.51%   |
| Nvidia MCP61 Ethernet                                             | 356      | 2.22%   |
| Ralink MT7601U Wireless Adapter                                   | 237      | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 216      | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 205      | 1.28%   |
| Intel I211 Gigabit Network Connection                             | 187      | 1.16%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 178      | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 163      | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 162      | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 151      | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 147      | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 137      | 0.85%   |
| Huawei Modem/Networkcard                                          | 134      | 0.83%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 126      | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 116      | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 107      | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 104      | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 94       | 0.59%   |
| Intel Wi-Fi 6 AX200                                               | 88       | 0.55%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 83       | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                   | 80       | 0.5%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 77       | 0.48%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 77       | 0.48%   |
| Intel Ethernet Connection (14) I219-V                             | 76       | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 73       | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 70       | 0.44%   |
| Nvidia MCP77 Ethernet                                             | 68       | 0.42%   |
| Nvidia CK804 Ethernet Controller                                  | 67       | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 66       | 0.41%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 65       | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 64       | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 64       | 0.4%    |
| Intel 82574L Gigabit Network Connection                           | 63       | 0.39%   |
| Ralink RT5370 Wireless Adapter                                    | 62       | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 62       | 0.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60       | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 59       | 0.37%   |
| Intel Ethernet Connection (2) I218-V                              | 59       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 741      | 25.16%  |
| Intel                           | 412      | 13.99%  |
| Qualcomm Atheros                | 393      | 13.34%  |
| Ralink Technology               | 385      | 13.07%  |
| TP-Link                         | 205      | 6.96%   |
| Ralink                          | 191      | 6.49%   |
| D-Link                          | 123      | 4.18%   |
| ASUSTek Computer                | 99       | 3.36%   |
| Qualcomm Atheros Communications | 98       | 3.33%   |
| Broadcom                        | 76       | 2.58%   |
| D-Link System                   | 61       | 2.07%   |
| Microsoft                       | 23       | 0.78%   |
| MediaTek                        | 19       | 0.65%   |
| NetGear                         | 18       | 0.61%   |
| Mercucys                        | 16       | 0.54%   |
| IMC Networks                    | 16       | 0.54%   |
| ZyXEL Communications            | 13       | 0.44%   |
| Broadcom Limited                | 10       | 0.34%   |
| Tenda                           | 8        | 0.27%   |
| Xiaomi                          | 7        | 0.24%   |
| ZyDAS                           | 3        | 0.1%    |
| VIA Technologies                | 3        | 0.1%    |
| Texas Instruments               | 3        | 0.1%    |
| Micro Star International        | 3        | 0.1%    |
| Marvell Technology Group        | 3        | 0.1%    |
| TRENDnet                        | 2        | 0.07%   |
| Edimax Technology               | 2        | 0.07%   |
| Z-Com                           | 1        | 0.03%   |
| Wilocity                        | 1        | 0.03%   |
| Sierra Wireless                 | 1        | 0.03%   |
| Linksys                         | 1        | 0.03%   |
| Gemtek                          | 1        | 0.03%   |
| Chu Yuen Enterprise             | 1        | 0.03%   |
| BUFFALO                         | 1        | 0.03%   |
| Belkin Components               | 1        | 0.03%   |
| ASUSTek Computer (wrong ID)     | 1        | 0.03%   |
| AirTies Wireless Networks       | 1        | 0.03%   |
| Accton Technology               | 1        | 0.03%   |
| AboCom Systems                  | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                    | 237      | 7.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 163      | 5.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 107      | 3.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 94       | 3.16%   |
| Intel Wi-Fi 6 AX200                                                | 88       | 2.96%   |
| Qualcomm Atheros AR9271 802.11n                                    | 80       | 2.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                   | 65       | 2.18%   |
| Ralink RT5370 Wireless Adapter                                     | 62       | 2.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 59       | 1.98%   |
| Realtek 802.11ac NIC                                               | 58       | 1.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 58       | 1.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 50       | 1.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 47       | 1.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 47       | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 47       | 1.58%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 45       | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 40       | 1.34%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 39       | 1.31%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                         | 37       | 1.24%   |
| Ralink RT2561/RT61 rev B 802.11g                                   | 37       | 1.24%   |
| Intel Wireless-AC 9260                                             | 37       | 1.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 35       | 1.18%   |
| Intel Wireless 3165                                                | 35       | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 31       | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 31       | 1.04%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 31       | 1.04%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                               | 30       | 1.01%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                | 29       | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 29       | 0.97%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 29       | 0.97%   |
| D-Link 802.11 n WLAN                                               | 27       | 0.91%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]          | 26       | 0.87%   |
| Intel Wireless 7265                                                | 25       | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 25       | 0.84%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 24       | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                          | 22       | 0.74%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 21       | 0.71%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 20       | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 19       | 0.64%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller          | 18       | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8118     | 64.7%   |
| Intel                                  | 1475     | 11.76%  |
| Qualcomm Atheros                       | 1090     | 8.69%   |
| Nvidia                                 | 665      | 5.3%    |
| Marvell Technology Group               | 222      | 1.77%   |
| VIA Technologies                       | 179      | 1.43%   |
| D-Link System                          | 87       | 0.69%   |
| Huawei Technologies                    | 82       | 0.65%   |
| ZTE WCDMA Technologies MSM             | 63       | 0.5%    |
| Xiaomi                                 | 62       | 0.49%   |
| Broadcom Limited                       | 57       | 0.45%   |
| Broadcom                               | 56       | 0.45%   |
| Samsung Electronics                    | 45       | 0.36%   |
| MediaTek                               | 41       | 0.33%   |
| Sundance Technology Inc / IC Plus      | 37       | 0.29%   |
| 3Com                                   | 31       | 0.25%   |
| Silicon Integrated Systems [SiS]       | 29       | 0.23%   |
| HTC (High Tech Computer)               | 15       | 0.12%   |
| Aquantia                               | 15       | 0.12%   |
| Gemtek                                 | 14       | 0.11%   |
| ASIX Electronics                       | 14       | 0.11%   |
| Spreadtrum Communications              | 12       | 0.1%    |
| Qualcomm                               | 11       | 0.09%   |
| Sony Ericsson Mobile Communications AB | 10       | 0.08%   |
| OPPO Electronics                       | 10       | 0.08%   |
| T & A Mobile Phones                    | 8        | 0.06%   |
| GCT Semiconductor                      | 8        | 0.06%   |
| Vimtron Electronics                    | 7        | 0.06%   |
| JMicron Technology                     | 7        | 0.06%   |
| HMD Global                             | 6        | 0.05%   |
| ASUSTek Computer                       | 6        | 0.05%   |
| TP-Link                                | 5        | 0.04%   |
| Lenovo                                 | 5        | 0.04%   |
| ULi Electronics                        | 4        | 0.03%   |
| MCST                                   | 4        | 0.03%   |
| D-Link                                 | 4        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.02%   |
| ICS Advent                             | 3        | 0.02%   |
| Davicom Semiconductor                  | 3        | 0.02%   |
| ZyXEL Communications                   | 2        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7035     | 54.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 473      | 3.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 404      | 3.15%   |
| Nvidia MCP61 Ethernet                                             | 356      | 2.77%   |
| Intel Ethernet Connection (2) I219-V                              | 216      | 1.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 205      | 1.6%    |
| Intel I211 Gigabit Network Connection                             | 187      | 1.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 178      | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 162      | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 151      | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 147      | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 137      | 1.07%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 126      | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 116      | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 104      | 0.81%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 83       | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 77       | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 77       | 0.6%    |
| Intel Ethernet Connection (14) I219-V                             | 76       | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 73       | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 70       | 0.55%   |
| Nvidia MCP77 Ethernet                                             | 68       | 0.53%   |
| Nvidia CK804 Ethernet Controller                                  | 67       | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 66       | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 64       | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 64       | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 63       | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 62       | 0.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60       | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 59       | 0.46%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 55       | 0.43%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 53       | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 52       | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 51       | 0.4%    |
| Nvidia MCP55 Ethernet                                             | 51       | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 47       | 0.37%   |
| Huawei ANA-NX9                                                    | 47       | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.32%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 40       | 0.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11535    | 79.08%  |
| WiFi     | 2798     | 19.18%  |
| Modem    | 234      | 1.6%    |
| Unknown  | 20       | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 9771     | 84.48%  |
| WiFi     | 1794     | 15.51%  |
| Modem    | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9436     | 80.44%  |
| 2     | 1993     | 16.99%  |
| 3     | 165      | 1.41%   |
| 0     | 96       | 0.82%   |
| 4     | 32       | 0.27%   |
| 5     | 3        | 0.03%   |
| 8     | 2        | 0.02%   |
| 6     | 2        | 0.02%   |
| 33    | 1        | 0.01%   |
| 13    | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11516    | 98.57%  |
| Yes  | 167      | 1.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 704      | 43.56%  |
| Intel                           | 370      | 22.9%   |
| ASUSTek Computer                | 147      | 9.1%    |
| Realtek Semiconductor           | 118      | 7.3%    |
| Broadcom                        | 92       | 5.69%   |
| Qualcomm Atheros Communications | 49       | 3.03%   |
| Integrated System Solution      | 28       | 1.73%   |
| IMC Networks                    | 20       | 1.24%   |
| TP-Link                         | 14       | 0.87%   |
| MediaTek                        | 12       | 0.74%   |
| Lite-On Technology              | 12       | 0.74%   |
| Conwise Technology              | 9        | 0.56%   |
| Apple                           | 7        | 0.43%   |
| Ralink                          | 6        | 0.37%   |
| Roper                           | 5        | 0.31%   |
| Logitech                        | 4        | 0.25%   |
| HTC (High Tech Computer)        | 4        | 0.25%   |
| Foxconn / Hon Hai               | 4        | 0.25%   |
| D-Link System                   | 4        | 0.25%   |
| Hewlett-Packard                 | 3        | 0.19%   |
| Micro Star International        | 2        | 0.12%   |
| TRENDnet                        | 1        | 0.06%   |
| Edimax Technology               | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 704      | 43.51%  |
| Intel Bluetooth wireless interface                                   | 102      | 6.3%    |
| Realtek Bluetooth Radio                                              | 101      | 6.24%   |
| Intel AX200 Bluetooth                                                | 84       | 5.19%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 64       | 3.96%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 56       | 3.46%   |
| Intel AX210 Bluetooth                                                | 37       | 2.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 32       | 1.98%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 29       | 1.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 25       | 1.55%   |
| ASUS Bluetooth Adapter                                               | 23       | 1.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 20       | 1.24%   |
| Intel AX201 Bluetooth                                                | 18       | 1.11%   |
| Broadcom BCM2045 Bluetooth                                           | 18       | 1.11%   |
| ASUS BCM20702A0                                                      | 17       | 1.05%   |
| Integrated System Solution Bluetooth Device                          | 16       | 0.99%   |
| Broadcom Bluetooth 3.0 Dongle                                        | 15       | 0.93%   |
| TP-Link UB500 Adapter                                                | 14       | 0.87%   |
| MediaTek Wireless_Device                                             | 12       | 0.74%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 12       | 0.74%   |
| ASUS Bluetooth Radio                                                 | 12       | 0.74%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 11       | 0.68%   |
| ASUS ASUS USB-BT500                                                  | 11       | 0.68%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 0.62%   |
| Lite-On Bluetooth Device                                             | 10       | 0.62%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 9        | 0.56%   |
| Conwise CW6622                                                       | 9        | 0.56%   |
| Broadcom BCM92045B3 ROM                                              | 9        | 0.56%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7        | 0.43%   |
| Intel Bluetooth Device                                               | 7        | 0.43%   |
| Ralink RT3290 Bluetooth                                              | 6        | 0.37%   |
| IMC Networks Bluetooth Radio                                         | 6        | 0.37%   |
| ASUS Bluetooth Device                                                | 6        | 0.37%   |
| Roper Class 1 Bluetooth Dongle                                       | 5        | 0.31%   |
| Qualcomm Atheros Bluetooth (AR3011)                                  | 5        | 0.31%   |
| Apple Bluetooth Host Controller                                      | 5        | 0.31%   |
| Realtek Bluetooth 5.1 Radio                                          | 4        | 0.25%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 4        | 0.25%   |
| IMC Networks Bluetooth Module                                        | 4        | 0.25%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 7459     | 40.12%  |
| Nvidia                               | 5046     | 27.14%  |
| AMD                                  | 4330     | 23.29%  |
| C-Media Electronics                  | 493      | 2.65%   |
| Creative Labs                        | 307      | 1.65%   |
| VIA Technologies                     | 117      | 0.63%   |
| Creative Technology                  | 79       | 0.42%   |
| JMTek                                | 69       | 0.37%   |
| Logitech                             | 68       | 0.37%   |
| Texas Instruments                    | 48       | 0.26%   |
| Generalplus Technology               | 41       | 0.22%   |
| Silicon Integrated Systems [SiS]     | 37       | 0.2%    |
| ASUSTek Computer                     | 25       | 0.13%   |
| Kingston Technology                  | 23       | 0.12%   |
| Plantronics                          | 19       | 0.1%    |
| Sony                                 | 16       | 0.09%   |
| Razer USA                            | 14       | 0.08%   |
| Yamaha                               | 13       | 0.07%   |
| Pixart Imaging                       | 11       | 0.06%   |
| GN Netcom                            | 11       | 0.06%   |
| Focusrite-Novation                   | 11       | 0.06%   |
| A4Tech                               | 11       | 0.06%   |
| Ensoniq                              | 10       | 0.05%   |
| SteelSeries ApS                      | 9        | 0.05%   |
| Samson Technologies                  | 9        | 0.05%   |
| M-Audio                              | 9        | 0.05%   |
| XMOS                                 | 8        | 0.04%   |
| KTMicro                              | 8        | 0.04%   |
| Microsoft                            | 7        | 0.04%   |
| ESS Technology                       | 7        | 0.04%   |
| Conexant Systems                     | 7        | 0.04%   |
| BEHRINGER International              | 7        | 0.04%   |
| ATI Technologies                     | 7        | 0.04%   |
| Tenx Technology                      | 6        | 0.03%   |
| Shenzhen Rapoo Technology            | 6        | 0.03%   |
| Nordic Semiconductor ASA             | 6        | 0.03%   |
| Aureal Semiconductor                 | 6        | 0.03%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.03%   |
| SAVITECH                             | 5        | 0.03%   |
| Realtek Semiconductor                | 5        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1417     | 6.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1396     | 6.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1135     | 5.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 723      | 3.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 674      | 3.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 589      | 2.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 550      | 2.64%   |
| AMD FCH Azalia Controller                                                  | 444      | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 443      | 2.13%   |
| Intel 200 Series PCH HD Audio                                              | 437      | 2.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 433      | 2.08%   |
| Nvidia High Definition Audio Controller                                    | 432      | 2.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 416      | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 388      | 1.86%   |
| Nvidia MCP61 High Definition Audio                                         | 385      | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 371      | 1.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 364      | 1.75%   |
| AMD Family 17h/19h HD Audio Controller                                     | 352      | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 313      | 1.5%    |
| AMD Starship/Matisse HD Audio Controller                                   | 312      | 1.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 305      | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 286      | 1.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 284      | 1.36%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 236      | 1.13%   |
| Nvidia GP106 High Definition Audio Controller                              | 226      | 1.08%   |
| Nvidia GK106 HDMI Audio Controller                                         | 223      | 1.07%   |
| Nvidia GF119 HDMI Audio Controller                                         | 215      | 1.03%   |
| Nvidia GF116 High Definition Audio Controller                              | 204      | 0.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 204      | 0.98%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 192      | 0.92%   |
| Intel Cannon Lake PCH cAVS                                                 | 191      | 0.92%   |
| Nvidia GK104 HDMI Audio Controller                                         | 166      | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 144      | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 144      | 0.69%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 136      | 0.65%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 134      | 0.64%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 133      | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 128      | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 128      | 0.61%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 126      | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 4607     | 40.44%  |
| Kingston                     | 2179     | 19.13%  |
| Crucial                      | 915      | 8.03%   |
| Samsung Electronics          | 716      | 6.29%   |
| SK hynix                     | 468      | 4.11%   |
| Corsair                      | 465      | 4.08%   |
| Patriot                      | 296      | 2.6%    |
| AMD                          | 293      | 2.57%   |
| Micron Technology            | 163      | 1.43%   |
| A-DATA Technology            | 105      | 0.92%   |
| GOODRAM                      | 93       | 0.82%   |
| G.Skill                      | 83       | 0.73%   |
| Nanya Technology             | 81       | 0.71%   |
| Apacer                       | 66       | 0.58%   |
| Kingmax                      | 65       | 0.57%   |
| Qumo                         | 63       | 0.55%   |
| Foxline                      | 56       | 0.49%   |
| Goldkey                      | 50       | 0.44%   |
| Unknown                      | 49       | 0.43%   |
| Silicon Power                | 47       | 0.41%   |
| Elpida                       | 43       | 0.38%   |
| Kllisre                      | 39       | 0.34%   |
| Transcend                    | 37       | 0.32%   |
| KETECH                       | 29       | 0.25%   |
| GeIL                         | 27       | 0.24%   |
| Ramaxel Technology           | 25       | 0.22%   |
| Hikvision                    | 24       | 0.21%   |
| Atermiter                    | 24       | 0.21%   |
| Unifosa                      | 22       | 0.19%   |
| Team                         | 19       | 0.17%   |
| Unknown (ABCD)               | 16       | 0.14%   |
| Ramos Technology             | 16       | 0.14%   |
| Qimonda                      | 11       | 0.1%    |
| Neo Forza                    | 10       | 0.09%   |
| Patriot Memory (PDP Systems) | 9        | 0.08%   |
| TakeMS                       | 8        | 0.07%   |
| Juhor                        | 8        | 0.07%   |
| Hexon                        | 7        | 0.06%   |
| Wilk Elektronik              | 6        | 0.05%   |
| Patriot Memory               | 6        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 290      | 2.18%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 268      | 2.02%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 263      | 1.98%   |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 223      | 1.68%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 213      | 1.6%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 206      | 1.55%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s           | 186      | 1.4%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                | 142      | 1.07%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s           | 137      | 1.03%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 122      | 0.92%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 97       | 0.73%   |
| Unknown RAM Module 2GB DIMM SDRAM                     | 93       | 0.7%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 91       | 0.68%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                | 89       | 0.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 86       | 0.65%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                | 86       | 0.65%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 83       | 0.62%   |
| Unknown RAM Module 512MB DIMM SDRAM                   | 82       | 0.62%   |
| Unknown RAM Module 1024MB DIMM                        | 71       | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s              | 70       | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s          | 69       | 0.52%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                  | 66       | 0.5%    |
| Unknown RAM Module 2GB DIMM 800MT/s                   | 65       | 0.49%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s | 65       | 0.49%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                | 64       | 0.48%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s           | 64       | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 61       | 0.46%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s           | 60       | 0.45%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s | 57       | 0.43%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s   | 54       | 0.41%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                  | 51       | 0.38%   |
| Unknown                                               | 49       | 0.37%   |
| Unknown RAM Module 512MB DIMM                         | 48       | 0.36%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s     | 48       | 0.36%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 47       | 0.35%   |
| Unknown RAM Module 2048MB DIMM                        | 47       | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 46       | 0.35%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 46       | 0.35%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s | 45       | 0.34%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s | 45       | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3536     | 34.1%   |
| DDR4    | 2364     | 22.8%   |
| Unknown | 1921     | 18.53%  |
| DDR2    | 1242     | 11.98%  |
| SDRAM   | 964      | 9.3%    |
| DDR     | 287      | 2.77%   |
| LPDDR4  | 23       | 0.22%   |
| DDR5    | 18       | 0.17%   |
| DRAM    | 14       | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 9975     | 97.07%  |
| SODIMM       | 291      | 2.83%   |
| FB-DIMM      | 6        | 0.06%   |
| Row Of Chips | 3        | 0.03%   |
| RIMM         | 1        | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 3430     | 28.86%  |
| 2048  | 3155     | 26.54%  |
| 8192  | 2514     | 21.15%  |
| 1024  | 1648     | 13.86%  |
| 16384 | 516      | 4.34%   |
| 512   | 405      | 3.41%   |
| 32768 | 122      | 1.03%   |
| 256   | 88       | 0.74%   |
| 32    | 5        | 0.04%   |
| 128   | 2        | 0.02%   |
| 16    | 2        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 2036     | 18.03%  |
| 1333    | 1777     | 15.74%  |
| 800     | 1242     | 11%     |
| Unknown | 970      | 8.59%   |
| 667     | 688      | 6.09%   |
| 2400    | 568      | 5.03%   |
| 2133    | 425      | 3.76%   |
| 2667    | 415      | 3.68%   |
| 3200    | 325      | 2.88%   |
| 400     | 274      | 2.43%   |
| 1867    | 218      | 1.93%   |
| 1866    | 213      | 1.89%   |
| 3600    | 196      | 1.74%   |
| 1066    | 170      | 1.51%   |
| 3400    | 145      | 1.28%   |
| 333     | 134      | 1.19%   |
| 533     | 132      | 1.17%   |
| 2666    | 119      | 1.05%   |
| 2933    | 111      | 0.98%   |
| 3466    | 77       | 0.68%   |
| 1800    | 70       | 0.62%   |
| 3000    | 66       | 0.58%   |
| 1067    | 61       | 0.54%   |
| 3266    | 59       | 0.52%   |
| 266     | 59       | 0.52%   |
| 2866    | 54       | 0.48%   |
| 2800    | 51       | 0.45%   |
| 1334    | 47       | 0.42%   |
| 3333    | 38       | 0.34%   |
| 3066    | 37       | 0.33%   |
| 1648    | 33       | 0.29%   |
| 66      | 33       | 0.29%   |
| 2000    | 28       | 0.25%   |
| 2134    | 27       | 0.24%   |
| 3334    | 25       | 0.22%   |
| 1400    | 25       | 0.22%   |
| 3733    | 20       | 0.18%   |
| 200     | 19       | 0.17%   |
| 2048    | 18       | 0.16%   |
| 2934    | 17       | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 276      | 29.08%  |
| Canon                           | 205      | 21.6%   |
| Samsung Electronics             | 164      | 17.28%  |
| Seiko Epson                     | 85       | 8.96%   |
| Brother Industries              | 66       | 6.95%   |
| Xerox                           | 33       | 3.48%   |
| Pantum                          | 28       | 2.95%   |
| Panasonic (Matsushita)          | 25       | 2.63%   |
| Kyocera                         | 20       | 2.11%   |
| QinHeng Electronics             | 11       | 1.16%   |
| Ricoh                           | 10       | 1.05%   |
| Prolific Technology             | 6        | 0.63%   |
| TSC Auto ID Technology          | 2        | 0.21%   |
| STMicroelectronics              | 2        | 0.21%   |
| NXP Semiconductors              | 2        | 0.21%   |
| Lexmark International           | 2        | 0.21%   |
| Konica Minolta                  | 2        | 0.21%   |
| cab Produkttechnik GmbH & Co KG | 2        | 0.21%   |
| Apple                           | 2        | 0.21%   |
| Sharp                           | 1        | 0.11%   |
| Samsung Info. Systems America   | 1        | 0.11%   |
| KODAK                           | 1        | 0.11%   |
| GODEX INTERNATIONAL             | 1        | 0.11%   |
| Fuji Xerox                      | 1        | 0.11%   |
| Datamax-O'Neil                  | 1        | 0.11%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| HP LaserJet 1020                      | 29       | 3.03%   |
| Canon LBP2900                         | 29       | 3.03%   |
| Samsung SCX-4200 series               | 28       | 2.93%   |
| HP LaserJet 1018                      | 28       | 2.93%   |
| HP LaserJet P1102                     | 24       | 2.51%   |
| Panasonic (Matsushita) KX-MB1500RU    | 18       | 1.88%   |
| HP LaserJet 1010                      | 17       | 1.78%   |
| HP LaserJet P1005                     | 16       | 1.67%   |
| Samsung SCX-3400 Series               | 15       | 1.57%   |
| Seiko Epson Printer                   | 14       | 1.46%   |
| Canon MF4410                          | 13       | 1.36%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 12       | 1.26%   |
| Samsung SCX-3200 Series               | 12       | 1.26%   |
| HP LaserJet 1320                      | 12       | 1.26%   |
| QinHeng CH340S                        | 11       | 1.15%   |
| Canon MF4010 series                   | 11       | 1.15%   |
| Canon MF3010                          | 11       | 1.15%   |
| Samsung M2070 Series                  | 10       | 1.05%   |
| Pantum P2200 series                   | 10       | 1.05%   |
| HP LaserJet 1300                      | 10       | 1.05%   |
| HP LaserJet 1200                      | 10       | 1.05%   |
| Samsung SCX-4100 Scanner              | 9        | 0.94%   |
| Samsung ML-2010P Mono Laser Printer   | 9        | 0.94%   |
| HP DeskJet 2130 series                | 9        | 0.94%   |
| Canon LBP3010/LBP3018/LBP3050         | 9        | 0.94%   |
| Xerox Phaser 3140 and 3155            | 8        | 0.84%   |
| Seiko Epson L210 Series               | 8        | 0.84%   |
| Samsung ML-216x Series Laser Printer  | 8        | 0.84%   |
| Samsung ML-1640 Series Laser Printer  | 8        | 0.84%   |
| Samsung ML-1210 Printer               | 8        | 0.84%   |
| Pantum M6500 series                   | 8        | 0.84%   |
| HP LaserJet 1022                      | 8        | 0.84%   |
| Canon PIXMA MG2500 Series             | 8        | 0.84%   |
| Canon LBP810                          | 8        | 0.84%   |
| Canon LBP6000                         | 8        | 0.84%   |
| Brother HL-2030 Laser Printer         | 8        | 0.84%   |
| Brother DCP-7057 scanner/printer      | 8        | 0.84%   |
| Xerox WorkCentre 3119 Series          | 7        | 0.73%   |
| HP LaserJet 1000                      | 7        | 0.73%   |
| Canon MG2400 series                   | 7        | 0.73%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 100      | 37.45%  |
| Seiko Epson                 | 67       | 25.09%  |
| Hewlett-Packard             | 45       | 16.85%  |
| Mustek Systems              | 28       | 10.49%  |
| Acer Peripherals (now BenQ) | 11       | 4.12%   |
| Ultima Electronics          | 10       | 3.75%   |
| KYE Systems (Mouse Systems) | 3        | 1.12%   |
| Avision                     | 2        | 0.75%   |
| Canon Electronics           | 1        | 0.37%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                                                      | 17       | 6.34%   |
| Canon CanoScan LIDE 25                                                                | 17       | 6.34%   |
| Canon CanoScan LiDE 120                                                               | 16       | 5.97%   |
| Canon CanoScan LiDE 110                                                               | 16       | 5.97%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11       | 4.1%    |
| Canon CanoScan LiDE 210                                                               | 11       | 4.1%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 9        | 3.36%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 9        | 3.36%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 8        | 2.99%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 8        | 2.99%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 8        | 2.99%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8        | 2.99%   |
| Mustek Systems SNAPSCAN e22                                                           | 6        | 2.24%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6        | 2.24%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 5        | 1.87%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 5        | 1.87%   |
| Canon CanoScan LiDE 60                                                                | 5        | 1.87%   |
| Canon CanoScan LiDE 220                                                               | 5        | 1.87%   |
| Canon CanoScan LiDE 100                                                               | 5        | 1.87%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4        | 1.49%   |
| HP ScanJet 3800c                                                                      | 4        | 1.49%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4        | 1.49%   |
| Seiko Epson Perfection 660                                                            | 3        | 1.12%   |
| HP ScanJet 3970c                                                                      | 3        | 1.12%   |
| Canon CanoScan LiDE 70                                                                | 3        | 1.12%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3        | 1.12%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 0.75%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2        | 0.75%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2        | 0.75%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2        | 0.75%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 2        | 0.75%   |
| HP ScanJet G4050                                                                      | 2        | 0.75%   |
| HP ScanJet 4300c                                                                      | 2        | 0.75%   |
| HP ScanJet 2300c                                                                      | 2        | 0.75%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 0.75%   |
| Canon CanoScan LiDE 700F                                                              | 2        | 0.75%   |
| Canon CanoScan                                                                        | 2        | 0.75%   |
| Avision iVina FB1600/UMAX Astra 4500                                                  | 2        | 0.75%   |
| Acer Peripherals (now BenQ) Color FlatbedScanner39                                    | 2        | 0.75%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 2        | 0.75%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 770      | 33.55%  |
| Z-Star Microelectronics                | 375      | 16.34%  |
| Microdia                               | 178      | 7.76%   |
| Microsoft                              | 116      | 5.05%   |
| KYE Systems (Mouse Systems)            | 90       | 3.92%   |
| Arkmicro Technologies                  | 73       | 3.18%   |
| GEMBIRD                                | 64       | 2.79%   |
| Aveo Technology                        | 62       | 2.7%    |
| Cubeternet                             | 52       | 2.27%   |
| Pixart Imaging                         | 50       | 2.18%   |
| Chicony Electronics                    | 47       | 2.05%   |
| Creative Technology                    | 42       | 1.83%   |
| Alcor Micro                            | 40       | 1.74%   |
| Realtek Semiconductor                  | 39       | 1.7%    |
| Apple                                  | 30       | 1.31%   |
| Sunplus Innovation Technology          | 25       | 1.09%   |
| Samsung Electronics                    | 23       | 1%      |
| Genesys Logic                          | 18       | 0.78%   |
| A4Tech                                 | 18       | 0.78%   |
| Guillemot                              | 13       | 0.57%   |
| Hewlett-Packard                        | 11       | 0.48%   |
| SunplusIT                              | 10       | 0.44%   |
| Philips (or NXP)                       | 10       | 0.44%   |
| lihappe8                               | 9        | 0.39%   |
| SiGma Micro                            | 8        | 0.35%   |
| IMC Networks                           | 8        | 0.35%   |
| Generalplus Technology                 | 8        | 0.35%   |
| AVerMedia Technologies                 | 8        | 0.35%   |
| Trust                                  | 7        | 0.31%   |
| Xiaomi                                 | 4        | 0.17%   |
| Unknown                                | 4        | 0.17%   |
| Silicon Motion                         | 4        | 0.17%   |
| Cheng Uei Precision Industry (Foxlink) | 4        | 0.17%   |
| ANYKA                                  | 4        | 0.17%   |
| Suyin                                  | 3        | 0.13%   |
| Sony                                   | 3        | 0.13%   |
| Sonix Technology                       | 3        | 0.13%   |
| Nokia Mobile Phones                    | 3        | 0.13%   |
| MacroSilicon                           | 3        | 0.13%   |
| Jieli Technology                       | 3        | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 280      | 12.18%  |
| Z-Star Venus USB2.0 Camera                        | 158      | 6.87%   |
| Microdia Camera                                   | 113      | 4.92%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 108      | 4.7%    |
| Z-Star Vimicro USB Camera (Altair)                | 78       | 3.39%   |
| Arkmicro USB2.0 PC CAMERA                         | 67       | 2.91%   |
| Logitech Webcam C170                              | 63       | 2.74%   |
| Logitech Webcam C310                              | 60       | 2.61%   |
| Logitech HD Webcam C525                           | 56       | 2.44%   |
| Logitech Webcam C210                              | 47       | 2.04%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 37       | 1.61%   |
| Microsoft LifeCam HD-3000                         | 34       | 1.48%   |
| Logitech HD Pro Webcam C920                       | 32       | 1.39%   |
| GEMBIRD USB2.0 PC CAMERA                          | 32       | 1.39%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 31       | 1.35%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 30       | 1.3%    |
| Alcor Micro USB 2.0 PC Camera                     | 26       | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 25       | 1.09%   |
| Logitech Webcam C110                              | 24       | 1.04%   |
| Logitech HD Webcam C510                           | 24       | 1.04%   |
| Aveo Camera                                       | 24       | 1.04%   |
| Samsung Galaxy A5 (MTP)                           | 22       | 0.96%   |
| Microsoft LifeCam VX-800                          | 22       | 0.96%   |
| Logitech Logitech Webcam C160                     | 19       | 0.83%   |
| Logitech HD Webcam C615                           | 19       | 0.83%   |
| Aveo USB2.0 Camera                                | 19       | 0.83%   |
| Realtek FULL HD 1080P Webcam                      | 17       | 0.74%   |
| Microdia USB 2.0 Camera                           | 17       | 0.74%   |
| Logitech HD Webcam C910                           | 17       | 0.74%   |
| Z-Star A4 TECH HD PC Camera                       | 16       | 0.7%    |
| Microdia Sonix USB 2.0 Camera                     | 15       | 0.65%   |
| Cubeternet USB2.0 Camera                          | 15       | 0.65%   |
| Aveo UVC camera (Bresser microscope)              | 15       | 0.65%   |
| Microsoft LifeCam VX-2000                         | 14       | 0.61%   |
| Microsoft LifeCam HD-5000                         | 14       | 0.61%   |
| Logitech Logitech Webcam C100                     | 14       | 0.61%   |
| Microsoft LifeCam Cinema                          | 13       | 0.57%   |
| Genesys Logic Camera                              | 12       | 0.52%   |
| Microdia MSI Starcam Racer                        | 11       | 0.48%   |
| A4Tech FHD 1080P PC Camera                        | 11       | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 4        | 44.44%  |
| STMicroelectronics    | 2        | 22.22%  |
| Microsoft             | 2        | 22.22%  |
| Elan Microelectronics | 1        | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader       | 2        | 22.22%  |
| Microsoft Fingerprint Reader                | 2        | 22.22%  |
| LighTuning Fingerprint Sensor               | 2        | 22.22%  |
| LighTuning ES603 Swipe Fingerprint Sensor   | 1        | 11.11%  |
| LighTuning EgisTec Touch Fingerprint Sensor | 1        | 11.11%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Aktiv                      | 13       | 27.66%  |
| Aladdin Knowledge Systems  | 10       | 21.28%  |
| Aladdin R.D.               | 7        | 14.89%  |
| Athena Smartcard Solutions | 4        | 8.51%   |
| Alcor Micro                | 4        | 8.51%   |
| Advanced Card Systems      | 4        | 8.51%   |
| Yubico.com                 | 2        | 4.26%   |
| OmniKey                    | 1        | 2.13%   |
| Gemalto (was Gemplus)      | 1        | 2.13%   |
| Castles Technology         | 1        | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Aktiv Rutoken lite                               | 13       | 27.66%  |
| Aladdin Knowledge Systems Token JC               | 10       | 21.28%  |
| Aladdin R.D. JaCarta                             | 6        | 12.77%  |
| Athena Smartcard Solutions ASEDrive CCID         | 4        | 8.51%   |
| Alcor Micro Watchdata W 1981                     | 3        | 6.38%   |
| Yubico.com Yubikey 4/5 U2F+CCID                  | 2        | 4.26%   |
| OmniKey Smart Card Reader USB                    | 1        | 2.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1        | 2.13%   |
| Castles Technology EZCCID Smart Card Reader      | 1        | 2.13%   |
| Alcor Micro AU9540 Smartcard Reader              | 1        | 2.13%   |
| Aladdin R.D. Smart card reader JCR721            | 1        | 2.13%   |
| Advanced Card Systems ACR39U                     | 1        | 2.13%   |
| Advanced Card Systems ACR3901U                   | 1        | 2.13%   |
| Advanced Card Systems ACR38 SmartCard Reader     | 1        | 2.13%   |
| Advanced Card Systems ACR1281 1S Dual Reader     | 1        | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 9794     | 81.92%  |
| 1     | 1930     | 16.14%  |
| 2     | 185      | 1.55%   |
| 3     | 30       | 0.25%   |
| 4     | 10       | 0.08%   |
| 6     | 3        | 0.03%   |
| 5     | 2        | 0.02%   |
| 9     | 1        | 0.01%   |
| 7     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1525     | 65.45%  |
| Net/wireless             | 230      | 9.87%   |
| Communication controller | 145      | 6.22%   |
| Unassigned class         | 94       | 4.03%   |
| Multimedia controller    | 66       | 2.83%   |
| Sound                    | 60       | 2.58%   |
| Camera                   | 39       | 1.67%   |
| Chipcard                 | 36       | 1.55%   |
| Net/ethernet             | 24       | 1.03%   |
| Network                  | 19       | 0.82%   |
| Bluetooth                | 19       | 0.82%   |
| Modem                    | 17       | 0.73%   |
| Storage/raid             | 14       | 0.6%    |
| Fingerprint reader       | 9        | 0.39%   |
| Dvb card                 | 8        | 0.34%   |
| Firewire controller      | 6        | 0.26%   |
| Storage/ide              | 5        | 0.21%   |
| Storage/ata              | 5        | 0.21%   |
| Tv card                  | 4        | 0.17%   |
| Storage                  | 2        | 0.09%   |
| Video                    | 1        | 0.04%   |
| Unclassified device      | 1        | 0.04%   |
| Card reader              | 1        | 0.04%   |

