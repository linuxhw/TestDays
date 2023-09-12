Ubuntu 23.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

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

Total: 483

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Shenzhen M... | AHBAA OEM                   | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| HP            | 844C                        | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7fa390fcc4](https://linux-hardware.org/?probe=7fa390fcc4) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASRock        | FM2A68M-HD+                 | [5971b283b6](https://linux-hardware.org/?probe=5971b283b6) | Sep 05, 2023 |
| ASUSTek       | A88XM-E                     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [06571c70a0](https://linux-hardware.org/?probe=06571c70a0) | Sep 04, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [75c1744e6f](https://linux-hardware.org/?probe=75c1744e6f) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| ASRock        | Z790 PG SONIC               | [72f1cf1ac0](https://linux-hardware.org/?probe=72f1cf1ac0) | Sep 02, 2023 |
| Gigabyte      | GA-970A-D3                  | [193a173166](https://linux-hardware.org/?probe=193a173166) | Sep 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| ASUSTek       | M2N68-AM SE2                | [78cb25f581](https://linux-hardware.org/?probe=78cb25f581) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [d0a3fefd23](https://linux-hardware.org/?probe=d0a3fefd23) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [710315c4f1](https://linux-hardware.org/?probe=710315c4f1) | Aug 31, 2023 |
| ASUSTek       | PRIME A320M-K               | [8c1eeceddd](https://linux-hardware.org/?probe=8c1eeceddd) | Aug 31, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [5de56db01e](https://linux-hardware.org/?probe=5de56db01e) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LE                 | [58446213e2](https://linux-hardware.org/?probe=58446213e2) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | [272508eb60](https://linux-hardware.org/?probe=272508eb60) | Aug 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| HP            | 843C                        | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [f108558763](https://linux-hardware.org/?probe=f108558763) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Dell          | 0T7D40 A00                  | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9a98c147d4](https://linux-hardware.org/?probe=9a98c147d4) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3723979edb](https://linux-hardware.org/?probe=3723979edb) | Aug 24, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| Biostar       | B450MH                      | [21f8924d2c](https://linux-hardware.org/?probe=21f8924d2c) | Aug 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [a7cd220563](https://linux-hardware.org/?probe=a7cd220563) | Aug 21, 2023 |
| ASUSTek       | X99-DELUXE II               | [d59b79adfe](https://linux-hardware.org/?probe=d59b79adfe) | Aug 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [bca7b6990c](https://linux-hardware.org/?probe=bca7b6990c) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [fee22676ae](https://linux-hardware.org/?probe=fee22676ae) | Aug 20, 2023 |
| ASRock        | Q1900M                      | [1e1e781c93](https://linux-hardware.org/?probe=1e1e781c93) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [b52dbe962f](https://linux-hardware.org/?probe=b52dbe962f) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| Acer          | Veriton M2611G v1.0         | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| Dell          | 0X8582                      | [c9661782e6](https://linux-hardware.org/?probe=c9661782e6) | Aug 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [c6918bacbd](https://linux-hardware.org/?probe=c6918bacbd) | Aug 18, 2023 |
| Gigabyte      | H81M-D2V                    | [68639ddf06](https://linux-hardware.org/?probe=68639ddf06) | Aug 16, 2023 |
| ASRock        | FM2A68M-DG3+                | [fd5dd48ab1](https://linux-hardware.org/?probe=fd5dd48ab1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| AK3V          | 1.0                         | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | H81M-S2PV                   | [0e51f02009](https://linux-hardware.org/?probe=0e51f02009) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [396327d1fa](https://linux-hardware.org/?probe=396327d1fa) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| Unknown       | Unknown                     | [e52e8ee5df](https://linux-hardware.org/?probe=e52e8ee5df) | Aug 13, 2023 |
| Gigabyte      | H81M-D2V                    | [2996bc5d6c](https://linux-hardware.org/?probe=2996bc5d6c) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M LE                 | [a68db843ea](https://linux-hardware.org/?probe=a68db843ea) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [7fb2d45505](https://linux-hardware.org/?probe=7fb2d45505) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Dell          | 0HD5W2 A01                  | [be4514c366](https://linux-hardware.org/?probe=be4514c366) | Aug 12, 2023 |
| Intel         | B85 V5.56                   | [f278787ab5](https://linux-hardware.org/?probe=f278787ab5) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [76078461ae](https://linux-hardware.org/?probe=76078461ae) | Aug 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ab2473ff49](https://linux-hardware.org/?probe=ab2473ff49) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [7f2903e1a4](https://linux-hardware.org/?probe=7f2903e1a4) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| ASUSTek       | PRIME X570-PRO              | [f7fe8fc7f3](https://linux-hardware.org/?probe=f7fe8fc7f3) | Aug 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [ab3503021a](https://linux-hardware.org/?probe=ab3503021a) | Aug 10, 2023 |
| MSI           | Z590-A PRO                  | [4448c9f2e1](https://linux-hardware.org/?probe=4448c9f2e1) | Aug 09, 2023 |
| MSI           | Z590-A PRO                  | [6e1d11025a](https://linux-hardware.org/?probe=6e1d11025a) | Aug 09, 2023 |
| MSI           | Z97-G45 GAMING              | [65d491c109](https://linux-hardware.org/?probe=65d491c109) | Aug 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [783906b878](https://linux-hardware.org/?probe=783906b878) | Aug 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1d8737323b](https://linux-hardware.org/?probe=1d8737323b) | Aug 06, 2023 |
| ASUSTek       | P8H61-M LX3                 | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| MSI           | 2AE0                        | [9d3b59de32](https://linux-hardware.org/?probe=9d3b59de32) | Aug 06, 2023 |
| MSI           | H81M-P33                    | [ebed30097f](https://linux-hardware.org/?probe=ebed30097f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [9c9e999e7f](https://linux-hardware.org/?probe=9c9e999e7f) | Aug 06, 2023 |
| Intel         | B85 V5.56                   | [54f0bde318](https://linux-hardware.org/?probe=54f0bde318) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| GMKtec        | NucBox K4                   | [64b27a1390](https://linux-hardware.org/?probe=64b27a1390) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fed2da6500](https://linux-hardware.org/?probe=fed2da6500) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2531b9d0db](https://linux-hardware.org/?probe=2531b9d0db) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [67cea35f6d](https://linux-hardware.org/?probe=67cea35f6d) | Aug 04, 2023 |
| ASUSTek       | M3A78-T                     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| MSI           | Z97 GAMING 3                | [caac03a431](https://linux-hardware.org/?probe=caac03a431) | Aug 03, 2023 |
| MSI           | A320M-A PRO MAX             | [881ac0a0e0](https://linux-hardware.org/?probe=881ac0a0e0) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | [c3beec95b8](https://linux-hardware.org/?probe=c3beec95b8) | Aug 02, 2023 |
| HP            | 8653 A                      | [09f876ab04](https://linux-hardware.org/?probe=09f876ab04) | Aug 02, 2023 |
| ASRock        | B365M-HDV                   | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [66000207b0](https://linux-hardware.org/?probe=66000207b0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [df0702afb0](https://linux-hardware.org/?probe=df0702afb0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | [0ac623dd70](https://linux-hardware.org/?probe=0ac623dd70) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [36c7268653](https://linux-hardware.org/?probe=36c7268653) | Jul 31, 2023 |
| ASRock        | FM2A75 Pro4                 | [831157a9ac](https://linux-hardware.org/?probe=831157a9ac) | Jul 31, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [45405639f5](https://linux-hardware.org/?probe=45405639f5) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Gigabyte      | MZAPLBP-00                  | [b70677782d](https://linux-hardware.org/?probe=b70677782d) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | [ae8a9f3aaf](https://linux-hardware.org/?probe=ae8a9f3aaf) | Jul 29, 2023 |
| ASUSTek       | H110M-R                     | [471516b82e](https://linux-hardware.org/?probe=471516b82e) | Jul 29, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [f36740f05f](https://linux-hardware.org/?probe=f36740f05f) | Jul 29, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [7b5aebd006](https://linux-hardware.org/?probe=7b5aebd006) | Jul 28, 2023 |
| Gigabyte      | Z490 UD                     | [370243099a](https://linux-hardware.org/?probe=370243099a) | Jul 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | [87bb7b0b79](https://linux-hardware.org/?probe=87bb7b0b79) | Jul 26, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [c7ec8db97e](https://linux-hardware.org/?probe=c7ec8db97e) | Jul 26, 2023 |
| HP            | 3646h                       | [fbc7ac7c08](https://linux-hardware.org/?probe=fbc7ac7c08) | Jul 26, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2fe1d4509a](https://linux-hardware.org/?probe=2fe1d4509a) | Jul 26, 2023 |
| ASRock        | B560M Pro4                  | [d96478ff29](https://linux-hardware.org/?probe=d96478ff29) | Jul 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | [32707549f9](https://linux-hardware.org/?probe=32707549f9) | Jul 25, 2023 |
| Unknown       | 1.2                         | [b18dd168dd](https://linux-hardware.org/?probe=b18dd168dd) | Jul 24, 2023 |
| ASUSTek       | PRIME H510M-K R2.0          | [ffee60fde7](https://linux-hardware.org/?probe=ffee60fde7) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| Intel         | Unknown                     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| ASUSTek       | PRIME X570-P                | [c052f51a67](https://linux-hardware.org/?probe=c052f51a67) | Jul 23, 2023 |
| Intel         | B75                         | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3511a9786a](https://linux-hardware.org/?probe=3511a9786a) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Dell          | 08NPPY A00                  | [63fb3abc69](https://linux-hardware.org/?probe=63fb3abc69) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Gigabyte      | B450 AORUS M                | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [e35d64a41b](https://linux-hardware.org/?probe=e35d64a41b) | Jul 21, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a07f95cdcc](https://linux-hardware.org/?probe=a07f95cdcc) | Jul 21, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b0efbdb752](https://linux-hardware.org/?probe=b0efbdb752) | Jul 20, 2023 |
| Gigabyte      | A520M DS3H                  | [3bd7501f03](https://linux-hardware.org/?probe=3bd7501f03) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [f99a99e95e](https://linux-hardware.org/?probe=f99a99e95e) | Jul 19, 2023 |
| Unknown       | G41 Series                  | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [e62367803c](https://linux-hardware.org/?probe=e62367803c) | Jul 18, 2023 |
| Lenovo        | ThinkCentre M58e 7268C5F    | [41e06d3720](https://linux-hardware.org/?probe=41e06d3720) | Jul 18, 2023 |
| ASRock        | A300M-STX                   | [2fd0158946](https://linux-hardware.org/?probe=2fd0158946) | Jul 17, 2023 |
| Packard Be... | IMEDIA S2885                | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60280e0708](https://linux-hardware.org/?probe=60280e0708) | Jul 17, 2023 |
| MSI           | FM2-A85XA-G65               | [8e6741f497](https://linux-hardware.org/?probe=8e6741f497) | Jul 17, 2023 |
| ASRock        | FM2A68M-HD+                 | [5abf5fb1c3](https://linux-hardware.org/?probe=5abf5fb1c3) | Jul 16, 2023 |
| Gigabyte      | H61M-DS2                    | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| Unknown       | EMB-BT1                     | [90dbc847d2](https://linux-hardware.org/?probe=90dbc847d2) | Jul 16, 2023 |
| MSI           | G41M4                       | [b7bda60261](https://linux-hardware.org/?probe=b7bda60261) | Jul 16, 2023 |
| MSI           | G41M4                       | [a3e5e23a49](https://linux-hardware.org/?probe=a3e5e23a49) | Jul 16, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [79af0f54f4](https://linux-hardware.org/?probe=79af0f54f4) | Jul 15, 2023 |
| ASUSTek       | PRIME B650M-A II            | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [eedcf805f7](https://linux-hardware.org/?probe=eedcf805f7) | Jul 14, 2023 |
| MSI           | FM2-A85XA-G65               | [00b4b2f7b0](https://linux-hardware.org/?probe=00b4b2f7b0) | Jul 13, 2023 |
| MSI           | Z87-G43                     | [86d9a28ae8](https://linux-hardware.org/?probe=86d9a28ae8) | Jul 13, 2023 |
| HP            | 83EE                        | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| ASRock        | X79 Extreme9                | [bfd488feb9](https://linux-hardware.org/?probe=bfd488feb9) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [f4f002c37a](https://linux-hardware.org/?probe=f4f002c37a) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASRock        | Z77 Extreme3                | [1312271ad3](https://linux-hardware.org/?probe=1312271ad3) | Jul 10, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [fe6456ff43](https://linux-hardware.org/?probe=fe6456ff43) | Jul 09, 2023 |
| Gigabyte      | MZAPLBP-00                  | [8f57c74864](https://linux-hardware.org/?probe=8f57c74864) | Jul 09, 2023 |
| Dell          | 0GXM1W A00                  | [b320d70c27](https://linux-hardware.org/?probe=b320d70c27) | Jul 09, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [d7f7dc2ef3](https://linux-hardware.org/?probe=d7f7dc2ef3) | Jul 08, 2023 |
| Lenovo        | IdeaCentre K330A            | [8d98ff8f86](https://linux-hardware.org/?probe=8d98ff8f86) | Jul 08, 2023 |
| Dell          | 0GXM1W A00                  | [91cab30323](https://linux-hardware.org/?probe=91cab30323) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | [89a1894d2a](https://linux-hardware.org/?probe=89a1894d2a) | Jul 08, 2023 |
| MSI           | Z97S SLI Krait Edition      | [c353b62b15](https://linux-hardware.org/?probe=c353b62b15) | Jul 07, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7e3f6aabfb](https://linux-hardware.org/?probe=7e3f6aabfb) | Jul 06, 2023 |
| Apple         | Mac-F221BEC8                | [5e66adbc36](https://linux-hardware.org/?probe=5e66adbc36) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [56c3cb8200](https://linux-hardware.org/?probe=56c3cb8200) | Jul 06, 2023 |
| MSI           | 760GM-E51                   | [757eefb29d](https://linux-hardware.org/?probe=757eefb29d) | Jul 05, 2023 |
| MSI           | PRO X670-P WIFI             | [12e2330b5a](https://linux-hardware.org/?probe=12e2330b5a) | Jul 05, 2023 |
| ASRock        | A320M-HDV R3.0              | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| ASUSTek       | PRIME A520M-K               | [9b1631574e](https://linux-hardware.org/?probe=9b1631574e) | Jul 03, 2023 |
| ASUSTek       | PRIME X570-P                | [0302d7f3a8](https://linux-hardware.org/?probe=0302d7f3a8) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d17e5d7807](https://linux-hardware.org/?probe=d17e5d7807) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [29897719d5](https://linux-hardware.org/?probe=29897719d5) | Jul 03, 2023 |
| ASRock        | P67 Performance             | [5abbfdce39](https://linux-hardware.org/?probe=5abbfdce39) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [40ab1ca8ab](https://linux-hardware.org/?probe=40ab1ca8ab) | Jul 02, 2023 |
| Intel         | H55                         | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| ASUSTek       | PRIME X570-P                | [5c7d4754d6](https://linux-hardware.org/?probe=5c7d4754d6) | Jul 02, 2023 |
| Biostar       | A10N-8800E                  | [261bb38239](https://linux-hardware.org/?probe=261bb38239) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [e0e64ac6a1](https://linux-hardware.org/?probe=e0e64ac6a1) | Jul 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fa055ceb7c](https://linux-hardware.org/?probe=fa055ceb7c) | Jun 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [ffcfef2edb](https://linux-hardware.org/?probe=ffcfef2edb) | Jun 30, 2023 |
| Lenovo        | 0B98401 WIN                 | [35871c9acc](https://linux-hardware.org/?probe=35871c9acc) | Jun 30, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [42624c8bb1](https://linux-hardware.org/?probe=42624c8bb1) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| ASUSTek       | PRIME Z590-P                | [6147d58cdf](https://linux-hardware.org/?probe=6147d58cdf) | Jun 29, 2023 |
| ASUSTek       | H170-PRO                    | [506c909e37](https://linux-hardware.org/?probe=506c909e37) | Jun 28, 2023 |
| ASUSTek       | P8Z77-V                     | [177c923e5a](https://linux-hardware.org/?probe=177c923e5a) | Jun 27, 2023 |
| ASRock        | A320M-DVS R4.0              | [742d015edb](https://linux-hardware.org/?probe=742d015edb) | Jun 26, 2023 |
| ASRock        | A320M-DVS R4.0              | [6c659f8e1f](https://linux-hardware.org/?probe=6c659f8e1f) | Jun 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [544c014552](https://linux-hardware.org/?probe=544c014552) | Jun 26, 2023 |
| Gigabyte      | 970A-DS3P                   | [77e0f0541a](https://linux-hardware.org/?probe=77e0f0541a) | Jun 26, 2023 |
| Dell          | 0KJCC5 A00                  | [3ec1b71f5c](https://linux-hardware.org/?probe=3ec1b71f5c) | Jun 25, 2023 |
| Intel         | H61                         | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [3505659de8](https://linux-hardware.org/?probe=3505659de8) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASRock        | X570 Extreme4               | [0ab63facb3](https://linux-hardware.org/?probe=0ab63facb3) | Jun 25, 2023 |
| HP            | 805D                        | [d55246de23](https://linux-hardware.org/?probe=d55246de23) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| System76      | Desktop leox5               | [210eb3f1e8](https://linux-hardware.org/?probe=210eb3f1e8) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [45575cf0cc](https://linux-hardware.org/?probe=45575cf0cc) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | [77d2d05995](https://linux-hardware.org/?probe=77d2d05995) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| MSI           | H270-A PRO                  | [169bbe5f04](https://linux-hardware.org/?probe=169bbe5f04) | Jun 23, 2023 |
| Gigabyte      | H61M-DS2                    | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7b33fc2cb8](https://linux-hardware.org/?probe=7b33fc2cb8) | Jun 23, 2023 |
| MSI           | 760GM -E51                  | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| Gigabyte      | H77-D3H                     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| Dell          | 0YXG0N A00                  | [546af4a5d6](https://linux-hardware.org/?probe=546af4a5d6) | Jun 22, 2023 |
| HP            | 339A                        | [420903b9cc](https://linux-hardware.org/?probe=420903b9cc) | Jun 21, 2023 |
| Shenzhen M... | F7BFC                       | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| Apple         | Mac-F221BEC8                | [05b8720dce](https://linux-hardware.org/?probe=05b8720dce) | Jun 19, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [c867520de1](https://linux-hardware.org/?probe=c867520de1) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [bc9f4e0f09](https://linux-hardware.org/?probe=bc9f4e0f09) | Jun 18, 2023 |
| HP            | 84FD                        | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| HP            | 84FD                        | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| Dell          | 0P301D A00                  | [91bec0952f](https://linux-hardware.org/?probe=91bec0952f) | Jun 17, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [2734ce8c5d](https://linux-hardware.org/?probe=2734ce8c5d) | Jun 16, 2023 |
| HP            | 1496                        | [ccc9943e2d](https://linux-hardware.org/?probe=ccc9943e2d) | Jun 16, 2023 |
| Unknown       | G41 Series                  | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| ASUSTek       | Rev                         | [6c5d91db68](https://linux-hardware.org/?probe=6c5d91db68) | Jun 15, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [7df89b77f2](https://linux-hardware.org/?probe=7df89b77f2) | Jun 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [dcfab5627c](https://linux-hardware.org/?probe=dcfab5627c) | Jun 14, 2023 |
| Unknown       | G41T-M7                     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | Z77X-UD3H                   | [5cbee4094a](https://linux-hardware.org/?probe=5cbee4094a) | Jun 14, 2023 |
| ASUSTek       | M5A97 PRO                   | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| ASRock        | Z77 Extreme3                | [143672bf6c](https://linux-hardware.org/?probe=143672bf6c) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASRock        | A520M-HVS                   | [0834ca7236](https://linux-hardware.org/?probe=0834ca7236) | Jun 13, 2023 |
| Gigabyte      | G41M-Combo                  | [a22e7ac3ea](https://linux-hardware.org/?probe=a22e7ac3ea) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M58 7360PL9     | [da837e8612](https://linux-hardware.org/?probe=da837e8612) | Jun 13, 2023 |
| ASRock        | Z77 Extreme3                | [0579a4f6f3](https://linux-hardware.org/?probe=0579a4f6f3) | Jun 13, 2023 |
| MSI           | B250M MORTAR ARCTIC         | [5e0e6586b7](https://linux-hardware.org/?probe=5e0e6586b7) | Jun 11, 2023 |
| Entroware     | Poseidon                    | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 81B4                        | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| Dell          | 0RY007                      | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| HP            | 3047h                       | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| Dell          | 0RY007                      | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| Dell          | 0RY007                      | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Dell          | 0RY007                      | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [11432ddeb6](https://linux-hardware.org/?probe=11432ddeb6) | May 29, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | B360M D2V                   | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| AAEON         | UP-CHCR1 V0.4               | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | 0MGK50 A02                  | [4572d76da5](https://linux-hardware.org/?probe=4572d76da5) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| Dell          | 0RY007                      | [6fb4081584](https://linux-hardware.org/?probe=6fb4081584) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | A88XM-PLUS                  | [55790e804a](https://linux-hardware.org/?probe=55790e804a) | May 25, 2023 |
| Dell          | 03KWTV A02                  | [60ade2d50f](https://linux-hardware.org/?probe=60ade2d50f) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| Intel         | DG31PR AAD97573-302         | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| Unknown       | DT138IB                     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8952bab351](https://linux-hardware.org/?probe=8952bab351) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c242460e72](https://linux-hardware.org/?probe=c242460e72) | May 20, 2023 |
| HP            | 8055                        | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| HP            | 8055                        | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| ASRock        | Z77 Extreme3                | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| ASUSTek       | Z170-A                      | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| ASUSTek       | PRIME B650M-A II            | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dbbfc6c8e](https://linux-hardware.org/?probe=9dbbfc6c8e) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| MSI           | MS-B9311                    | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| ASUSTek       | M2N68-AM SE2                | [41971afc9c](https://linux-hardware.org/?probe=41971afc9c) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [74b2c2122c](https://linux-hardware.org/?probe=74b2c2122c) | May 17, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| MSI           | 3664h                       | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| HP            | 8055                        | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| HP            | 3397                        | [3cfe6e2812](https://linux-hardware.org/?probe=3cfe6e2812) | May 15, 2023 |
| Dell          | 0KV3RP A00                  | [d324b5e64d](https://linux-hardware.org/?probe=d324b5e64d) | May 15, 2023 |
| Intel         | DX79SI AAG28808-600         | [d222ee2f89](https://linux-hardware.org/?probe=d222ee2f89) | May 14, 2023 |
| Lenovo        | NOK                         | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [6d362f8c74](https://linux-hardware.org/?probe=6d362f8c74) | May 13, 2023 |
| Intel         | DG43GT AAE62768-303         | [4cc21b00e7](https://linux-hardware.org/?probe=4cc21b00e7) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| Dell          | 0GU083 A00                  | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [297c4b54d4](https://linux-hardware.org/?probe=297c4b54d4) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| ASUSTek       | M2N68-AM SE2                | [39b8aee709](https://linux-hardware.org/?probe=39b8aee709) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| ASRock        | Z97 Extreme4                | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [669dc67190](https://linux-hardware.org/?probe=669dc67190) | May 09, 2023 |
| Acer          | Aspire TC-1760              | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [de7b924fdb](https://linux-hardware.org/?probe=de7b924fdb) | May 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [83c0648d66](https://linux-hardware.org/?probe=83c0648d66) | May 08, 2023 |
| Dell          | 0VNP2H A00                  | [ec04c034d3](https://linux-hardware.org/?probe=ec04c034d3) | May 08, 2023 |
| Gigabyte      | Z690 AERO G                 | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| ASUSTek       | M11BB                       | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Google        | Zako                        | [5d6aa6c0df](https://linux-hardware.org/?probe=5d6aa6c0df) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| ASUSTek       | P8H61-M LX                  | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| HP            | 212B                        | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [14a87bc11a](https://linux-hardware.org/?probe=14a87bc11a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | [2f3264f25f](https://linux-hardware.org/?probe=2f3264f25f) | May 04, 2023 |
| Dell          | 0RY007                      | [3ec4846de7](https://linux-hardware.org/?probe=3ec4846de7) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [86fc44372c](https://linux-hardware.org/?probe=86fc44372c) | May 03, 2023 |
| Dell          | 0RY007                      | [54e2c92bb9](https://linux-hardware.org/?probe=54e2c92bb9) | May 02, 2023 |
| HP            | 198E                        | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Shuttle       | FS35V4                      | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | [243a170e5a](https://linux-hardware.org/?probe=243a170e5a) | Apr 30, 2023 |
| HP            | ProLiant ML10 v2            | [3582be2f06](https://linux-hardware.org/?probe=3582be2f06) | Apr 30, 2023 |
| Dell          | 0T10XW A02                  | [2cd32d1efe](https://linux-hardware.org/?probe=2cd32d1efe) | Apr 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | NOK                         | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| Unknown       | G41                         | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| HP            | 1905                        | [7b15ec2d7d](https://linux-hardware.org/?probe=7b15ec2d7d) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| ASUSTek       | H110-PLUS                   | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Dell          | 0JP3NX A01                  | [2fa64e56ff](https://linux-hardware.org/?probe=2fa64e56ff) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| Dell          | 0K071D A01                  | [0c7edbd8ea](https://linux-hardware.org/?probe=0c7edbd8ea) | Apr 25, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| Dell          | 0JP3NX A01                  | [609eeb8038](https://linux-hardware.org/?probe=609eeb8038) | Apr 24, 2023 |
| MSI           | H81M PRO-VD                 | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [0dfc7cce7a](https://linux-hardware.org/?probe=0dfc7cce7a) | Apr 23, 2023 |
| ASUSTek       | M5A78L LE                   | [df70910ec6](https://linux-hardware.org/?probe=df70910ec6) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [4e664e5e26](https://linux-hardware.org/?probe=4e664e5e26) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| ASRock        | Z170 Gaming K4              | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a60c54ec31](https://linux-hardware.org/?probe=a60c54ec31) | Apr 22, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| BESSTAR Te... | UM700                       | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| ASUSTek       | M5A78L LE                   | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| HP            | 18E5                        | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| MSI           | A320M PRO-VD PLUS           | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Gigabyte      | GA-880GM-USB3               | [bb5da28703](https://linux-hardware.org/?probe=bb5da28703) | Feb 23, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Gigabyte      | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.2.0-20-generic        | 174      | 45.55%  |
| 6.2.0-27-generic        | 35       | 9.16%   |
| 6.2.0-26-generic        | 32       | 8.38%   |
| 6.2.0-24-generic        | 31       | 8.12%   |
| 6.2.0-25-generic        | 29       | 7.59%   |
| 6.2.0-23-generic        | 27       | 7.07%   |
| 6.2.0-31-generic        | 17       | 4.45%   |
| 6.2.0-32-generic        | 6        | 1.57%   |
| 5.19.0-21-generic       | 5        | 1.31%   |
| 6.3.6-060306-generic    | 2        | 0.52%   |
| 6.3.4-060304-generic    | 2        | 0.52%   |
| 6.3.2-060302-generic    | 2        | 0.52%   |
| 6.2.0-18-generic        | 2        | 0.52%   |
| 6.5.0-060500rc5-generic | 1        | 0.26%   |
| 6.5.0-060500-generic    | 1        | 0.26%   |
| 6.4.6-060406-generic    | 1        | 0.26%   |
| 6.4.0-060400-generic    | 1        | 0.26%   |
| 6.2.16-060216-generic   | 1        | 0.26%   |
| 6.2.11-060211-generic   | 1        | 0.26%   |
| 6.2.0-19-generic        | 1        | 0.26%   |
| 6.2.0-1010-lowlatency   | 1        | 0.26%   |
| 6.2.0-1009-lowlatency   | 1        | 0.26%   |
| 6.2.0-1007-lowlatency   | 1        | 0.26%   |
| 6.2.0-1007-gcp          | 1        | 0.26%   |
| 6.2.0-1003-oracle       | 1        | 0.26%   |
| 6.2.0-1003-lowlatency   | 1        | 0.26%   |
| 6.1.0-16-generic        | 1        | 0.26%   |
| 5.19.0-45-generic       | 1        | 0.26%   |
| 5.19.0-42-generic       | 1        | 0.26%   |
| 5.19.0-38-generic       | 1        | 0.26%   |
| 5.19.0-28-generic       | 1        | 0.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 339      | 94.17%  |
| 5.19.0  | 9        | 2.5%    |
| 6.3.6   | 2        | 0.56%   |
| 6.3.4   | 2        | 0.56%   |
| 6.3.2   | 2        | 0.56%   |
| 6.5.0   | 1        | 0.28%   |
| 6.4.6   | 1        | 0.28%   |
| 6.4.0   | 1        | 0.28%   |
| 6.2.16  | 1        | 0.28%   |
| 6.2.11  | 1        | 0.28%   |
| 6.1.0   | 1        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 341      | 94.72%  |
| 5.19    | 9        | 2.5%    |
| 6.3     | 6        | 1.67%   |
| 6.4     | 2        | 0.56%   |
| 6.5     | 1        | 0.28%   |
| 6.1     | 1        | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 360      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 346      | 96.11%  |
| Unknown         | 7        | 1.94%   |
| X-Cinnamon      | 6        | 1.67%   |
| GNOME Flashback | 1        | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 214      | 58.47%  |
| X11     | 137      | 37.43%  |
| Tty     | 9        | 2.46%   |
| Unknown | 6        | 1.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 313      | 86.46%  |
| Unknown | 37       | 10.22%  |
| LightDM | 9        | 2.49%   |
| GDM     | 3        | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| en_US            | 163      | 45.03%  |
| de_DE            | 50       | 13.81%  |
| fr_FR            | 21       | 5.8%    |
| pt_BR            | 16       | 4.42%   |
| C                | 16       | 4.42%   |
| en_GB            | 12       | 3.31%   |
| es_ES            | 10       | 2.76%   |
| ru_RU            | 9        | 2.49%   |
| en_CA            | 9        | 2.49%   |
| it_IT            | 6        | 1.66%   |
| nl_NL            | 4        | 1.1%    |
| fi_FI            | 4        | 1.1%    |
| zh_CN            | 3        | 0.83%   |
| pl_PL            | 3        | 0.83%   |
| en_AU            | 3        | 0.83%   |
| de_AT            | 3        | 0.83%   |
| cs_CZ            | 3        | 0.83%   |
| zh_TW            | 2        | 0.55%   |
| pt_PT            | 2        | 0.55%   |
| en_NZ            | 2        | 0.55%   |
| en_IL            | 2        | 0.55%   |
| el_GR            | 2        | 0.55%   |
| Unknown          | 2        | 0.55%   |
| tr_TR            | 1        | 0.28%   |
| sv_SE            | 1        | 0.28%   |
| sk_SK            | 1        | 0.28%   |
| nb_NO            | 1        | 0.28%   |
| lt_LT            | 1        | 0.28%   |
| ko_KR            | 1        | 0.28%   |
| hu_HU            | 1        | 0.28%   |
| fr_CH            | 1        | 0.28%   |
| fr_CA            | 1        | 0.28%   |
| es_CL            | 1        | 0.28%   |
| es_AR            | 1        | 0.28%   |
| en_US.ISO-8859-1 | 1        | 0.28%   |
| en_SG            | 1        | 0.28%   |
| de_CH            | 1        | 0.28%   |
| bg_BG            | 1        | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 262      | 72.18%  |
| EFI  | 101      | 27.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Tmpfs   | 216      | 59.34%  |
| Ext4    | 137      | 37.64%  |
| Btrfs   | 4        | 1.1%    |
| Zfs     | 3        | 0.82%   |
| Overlay | 3        | 0.82%   |
| Xfs     | 1        | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 301      | 82.92%  |
| MBR     | 32       | 8.82%   |
| Unknown | 30       | 8.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 287      | 78.42%  |
| Yes       | 79       | 21.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 217      | 59.45%  |
| Yes       | 148      | 40.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 111      | 30.83%  |
| Gigabyte Technology                  | 49       | 13.61%  |
| MSI                                  | 45       | 12.5%   |
| Dell                                 | 28       | 7.78%   |
| ASRock                               | 27       | 7.5%    |
| Hewlett-Packard                      | 23       | 6.39%   |
| Lenovo                               | 16       | 4.44%   |
| Intel                                | 13       | 3.61%   |
| Unknown                              | 8        | 2.22%   |
| Fujitsu                              | 7        | 1.94%   |
| Biostar                              | 4        | 1.11%   |
| Apple                                | 3        | 0.83%   |
| Acer                                 | 3        | 0.83%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.56%   |
| Pegatron                             | 2        | 0.56%   |
| ZOTAC                                | 1        | 0.28%   |
| System76                             | 1        | 0.28%   |
| Shuttle                              | 1        | 0.28%   |
| Packard Bell                         | 1        | 0.28%   |
| MACHINIST                            | 1        | 0.28%   |
| Itautec                              | 1        | 0.28%   |
| Huanan                               | 1        | 0.28%   |
| Google                               | 1        | 0.28%   |
| GMKtec                               | 1        | 0.28%   |
| Gateway                              | 1        | 0.28%   |
| Fujitsu Siemens                      | 1        | 0.28%   |
| Foxconn                              | 1        | 0.28%   |
| Entroware                            | 1        | 0.28%   |
| ECS                                  | 1        | 0.28%   |
| Colorful Technology                  | 1        | 0.28%   |
| BESSTAR Tech                         | 1        | 0.28%   |
| AZW                                  | 1        | 0.28%   |
| AK3V                                 | 1        | 0.28%   |
| AAEON                                | 1        | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Unknown                                    | 10       | 2.78%   |
| ASUS All Series                            | 7        | 1.94%   |
| MSI MS-7C95                                | 2        | 0.56%   |
| MSI MS-7C02                                | 2        | 0.56%   |
| MSI MS-7B86                                | 2        | 0.56%   |
| MSI MS-7721                                | 2        | 0.56%   |
| MSI MS-7596                                | 2        | 0.56%   |
| Intel H61                                  | 2        | 0.56%   |
| HP ProLiant ML10 v2                        | 2        | 0.56%   |
| HP EliteDesk 800 G2 DM 35W                 | 2        | 0.56%   |
| Gigabyte X670 AORUS ELITE AX               | 2        | 0.56%   |
| Gigabyte B450M DS3H                        | 2        | 0.56%   |
| Dell Precision Tower 7810                  | 2        | 0.56%   |
| Dell OptiPlex 3050                         | 2        | 0.56%   |
| Dell OptiPlex 3040                         | 2        | 0.56%   |
| ASUS TUF Gaming Z590-PLUS WIFI             | 2        | 0.56%   |
| ASUS TUF Gaming X570-PLUS                  | 2        | 0.56%   |
| ASUS TUF Gaming B550M-PLUS                 | 2        | 0.56%   |
| ASUS TUF Gaming B550-PLUS WIFI II          | 2        | 0.56%   |
| ASUS ROG STRIX B650E-I GAMING WIFI         | 2        | 0.56%   |
| ASUS PRIME Z790-A WIFI                     | 2        | 0.56%   |
| ASUS PRIME X670-P WIFI                     | 2        | 0.56%   |
| ASUS PRIME X570-P                          | 2        | 0.56%   |
| ASUS PRIME B660M-A D4                      | 2        | 0.56%   |
| ASUS PRIME B650M-A II                      | 2        | 0.56%   |
| ASUS PRIME B550-PLUS                       | 2        | 0.56%   |
| ASUS PRIME B450M-K II                      | 2        | 0.56%   |
| ASUS PRIME B450-PLUS                       | 2        | 0.56%   |
| ASUS PRIME A320M-K                         | 2        | 0.56%   |
| ASUS M5A97 R2.0                            | 2        | 0.56%   |
| ASUS M5A78L-M LE                           | 2        | 0.56%   |
| ASUS KomplettPC                            | 2        | 0.56%   |
| ASUS H170-PRO                              | 2        | 0.56%   |
| ASRock X670E Pro RS                        | 2        | 0.56%   |
| ASRock B450M-HDV R4.0                      | 2        | 0.56%   |
| ASRock A320M-HDV R4.0                      | 2        | 0.56%   |
| Apple MacPro5,1                            | 2        | 0.56%   |
| System76 Leopard Extreme                   | 1        | 0.28%   |
| Shuttle XS35V4                             | 1        | 0.28%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 35       | 9.72%   |
| Dell OptiPlex      | 15       | 4.17%   |
| ASUS ROG           | 15       | 4.17%   |
| ASUS TUF           | 14       | 3.89%   |
| Unknown            | 10       | 2.78%   |
| Lenovo ThinkCentre | 9        | 2.5%    |
| ASUS All           | 7        | 1.94%   |
| HP Compaq          | 5        | 1.39%   |
| Lenovo IdeaCentre  | 4        | 1.11%   |
| HP ProDesk         | 4        | 1.11%   |
| HP EliteDesk       | 4        | 1.11%   |
| Fujitsu ESPRIMO    | 4        | 1.11%   |
| Dell Precision     | 4        | 1.11%   |
| Dell Inspiron      | 4        | 1.11%   |
| ASUS M5A78L-M      | 4        | 1.11%   |
| Gigabyte X570      | 3        | 0.83%   |
| Gigabyte H61M-DS2  | 3        | 0.83%   |
| ASUS P8Z77-V       | 3        | 0.83%   |
| ASUS P8H61-M       | 3        | 0.83%   |
| ASUS M5A97         | 3        | 0.83%   |
| ASRock A320M-HDV   | 3        | 0.83%   |
| MSI MS-7C95        | 2        | 0.56%   |
| MSI MS-7C02        | 2        | 0.56%   |
| MSI MS-7B86        | 2        | 0.56%   |
| MSI MS-7721        | 2        | 0.56%   |
| MSI MS-7596        | 2        | 0.56%   |
| Intel H61          | 2        | 0.56%   |
| HP ProLiant        | 2        | 0.56%   |
| Gigabyte Z690      | 2        | 0.56%   |
| Gigabyte X670      | 2        | 0.56%   |
| Gigabyte B450M     | 2        | 0.56%   |
| Gigabyte A520M     | 2        | 0.56%   |
| Gigabyte A320M-S2H | 2        | 0.56%   |
| Dell XPS           | 2        | 0.56%   |
| Dell Vostro        | 2        | 0.56%   |
| ASUS KomplettPC    | 2        | 0.56%   |
| ASUS H170-PRO      | 2        | 0.56%   |
| ASRock X670E       | 2        | 0.56%   |
| ASRock B450M-HDV   | 2        | 0.56%   |
| Apple MacPro5      | 2        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 34       | 9.44%   |
| 2021 | 34       | 9.44%   |
| 2018 | 34       | 9.44%   |
| 2012 | 30       | 8.33%   |
| 2014 | 29       | 8.06%   |
| 2020 | 27       | 7.5%    |
| 2019 | 25       | 6.94%   |
| 2013 | 22       | 6.11%   |
| 2017 | 20       | 5.56%   |
| 2015 | 20       | 5.56%   |
| 2011 | 18       | 5%      |
| 2010 | 18       | 5%      |
| 2023 | 16       | 4.44%   |
| 2016 | 14       | 3.89%   |
| 2009 | 10       | 2.78%   |
| 2008 | 5        | 1.39%   |
| 2006 | 3        | 0.83%   |
| 2007 | 1        | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 360      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 350      | 96.95%  |
| Enabled  | 11       | 3.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 359      | 99.72%  |
| Yes  | 1        | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 87       | 24.1%   |
| 32.01-64.0      | 68       | 18.84%  |
| 4.01-8.0        | 64       | 17.73%  |
| 64.01-256.0     | 40       | 11.08%  |
| 8.01-16.0       | 40       | 11.08%  |
| 3.01-4.0        | 36       | 9.97%   |
| 24.01-32.0      | 17       | 4.71%   |
| 1.01-2.0        | 4        | 1.11%   |
| 2.01-3.0        | 3        | 0.83%   |
| More than 256.0 | 2        | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 114      | 30.73%  |
| 1.01-2.0   | 99       | 26.68%  |
| 4.01-8.0   | 78       | 21.02%  |
| 3.01-4.0   | 53       | 14.29%  |
| 8.01-16.0  | 19       | 5.12%   |
| 0.51-1.0   | 3        | 0.81%   |
| 32.01-64.0 | 2        | 0.54%   |
| 24.01-32.0 | 2        | 0.54%   |
| 16.01-24.0 | 1        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 153      | 41.58%  |
| 2      | 83       | 22.55%  |
| 3      | 58       | 15.76%  |
| 4      | 36       | 9.78%   |
| 5      | 18       | 4.89%   |
| 6      | 12       | 3.26%   |
| 8      | 3        | 0.82%   |
| 7      | 3        | 0.82%   |
| 9      | 1        | 0.27%   |
| 0      | 1        | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 228      | 62.98%  |
| Yes       | 134      | 37.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 355      | 98.34%  |
| No        | 6        | 1.66%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 196      | 54.44%  |
| No        | 164      | 45.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 209      | 57.89%  |
| Yes       | 152      | 42.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 65       | 18.06%  |
| Germany     | 56       | 15.56%  |
| France      | 24       | 6.67%   |
| Canada      | 24       | 6.67%   |
| Brazil      | 21       | 5.83%   |
| UK          | 18       | 5%      |
| Italy       | 12       | 3.33%   |
| Russia      | 11       | 3.06%   |
| Australia   | 9        | 2.5%    |
| Netherlands | 8        | 2.22%   |
| Sweden      | 7        | 1.94%   |
| Spain       | 7        | 1.94%   |
| Finland     | 7        | 1.94%   |
| India       | 6        | 1.67%   |
| Czechia     | 6        | 1.67%   |
| Switzerland | 5        | 1.39%   |
| Portugal    | 5        | 1.39%   |
| Austria     | 5        | 1.39%   |
| Turkey      | 4        | 1.11%   |
| Poland      | 4        | 1.11%   |
| Philippines | 4        | 1.11%   |
| New Zealand | 4        | 1.11%   |
| Greece      | 4        | 1.11%   |
| Israel      | 3        | 0.83%   |
| Iran        | 3        | 0.83%   |
| China       | 3        | 0.83%   |
| Belgium     | 3        | 0.83%   |
| Taiwan      | 2        | 0.56%   |
| South Korea | 2        | 0.56%   |
| Serbia      | 2        | 0.56%   |
| Peru        | 2        | 0.56%   |
| Norway      | 2        | 0.56%   |
| Malaysia    | 2        | 0.56%   |
| Lithuania   | 2        | 0.56%   |
| Hong Kong   | 2        | 0.56%   |
| Chile       | 2        | 0.56%   |
| Argentina   | 2        | 0.56%   |
| Ukraine     | 1        | 0.28%   |
| Thailand    | 1        | 0.28%   |
| Sri Lanka   | 1        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Sao Paulo        | 5        | 1.37%   |
| Helsinki         | 5        | 1.37%   |
| Winnipeg         | 3        | 0.82%   |
| Tourcoing        | 3        | 0.82%   |
| Tehran           | 3        | 0.82%   |
| Prague           | 3        | 0.82%   |
| Moscow           | 3        | 0.82%   |
| Montreal         | 3        | 0.82%   |
| Melbourne        | 3        | 0.82%   |
| Hanover          | 3        | 0.82%   |
| Hamburg          | 3        | 0.82%   |
| Brisbane         | 3        | 0.82%   |
| Berlin           | 3        | 0.82%   |
| Auckland         | 3        | 0.82%   |
| Warsaw           | 2        | 0.55%   |
| Valencia         | 2        | 0.55%   |
| Toronto          | 2        | 0.55%   |
| Sydney           | 2        | 0.55%   |
| Surat            | 2        | 0.55%   |
| St Petersburg    | 2        | 0.55%   |
| Sacramento       | 2        | 0.55%   |
| Petah Tikva      | 2        | 0.55%   |
| Oshawa           | 2        | 0.55%   |
| Nizhniy Novgorod | 2        | 0.55%   |
| Munich           | 2        | 0.55%   |
| Minneapolis      | 2        | 0.55%   |
| Makati City      | 2        | 0.55%   |
| Krasnoyarsk      | 2        | 0.55%   |
| Kaohsiung City   | 2        | 0.55%   |
| Heilbronn        | 2        | 0.55%   |
| Halle            | 2        | 0.55%   |
| Gothenburg       | 2        | 0.55%   |
| Florence         | 2        | 0.55%   |
| Edmonton         | 2        | 0.55%   |
| Dresden          | 2        | 0.55%   |
| Calgary          | 2        | 0.55%   |
| Brussels         | 2        | 0.55%   |
| Biel/Bienne      | 2        | 0.55%   |
| Belgrade         | 2        | 0.55%   |
| Beijing          | 2        | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 119      | 173    | 17.42%  |
| Seagate                     | 118      | 163    | 17.28%  |
| WDC                         | 104      | 151    | 15.23%  |
| SanDisk                     | 42       | 60     | 6.15%   |
| Kingston                    | 34       | 40     | 4.98%   |
| Crucial                     | 28       | 33     | 4.1%    |
| Toshiba                     | 27       | 31     | 3.95%   |
| Hitachi                     | 20       | 26     | 2.93%   |
| Phison Electronics          | 11       | 12     | 1.61%   |
| Intel                       | 11       | 12     | 1.61%   |
| SK hynix                    | 9        | 9      | 1.32%   |
| Micron/Crucial Technology   | 8        | 11     | 1.17%   |
| China                       | 7        | 9      | 1.02%   |
| Unknown                     | 6        | 7      | 0.88%   |
| Kingston Technology Company | 6        | 10     | 0.88%   |
| HGST                        | 6        | 6      | 0.88%   |
| MAXIO Technology (Hangzhou) | 5        | 5      | 0.73%   |
| Corsair                     | 5        | 6      | 0.73%   |
| Silicon Motion              | 4        | 4      | 0.59%   |
| SABRENT                     | 4        | 7      | 0.59%   |
| PNY                         | 4        | 5      | 0.59%   |
| Phison                      | 4        | 5      | 0.59%   |
| Micron Technology           | 4        | 6      | 0.59%   |
| KIOXIA                      | 4        | 4      | 0.59%   |
| Apacer                      | 4        | 5      | 0.59%   |
| A-DATA Technology           | 4        | 6      | 0.59%   |
| Patriot                     | 3        | 3      | 0.44%   |
| OCZ                         | 3        | 3      | 0.44%   |
| KingSpec                    | 3        | 4      | 0.44%   |
| Intenso                     | 3        | 3      | 0.44%   |
| Gigabyte Technology         | 3        | 3      | 0.44%   |
| ASMT                        | 3        | 5      | 0.44%   |
| Vaseky                      | 2        | 2      | 0.29%   |
| Team                        | 2        | 2      | 0.29%   |
| SPCC                        | 2        | 2      | 0.29%   |
| Smartbuy                    | 2        | 3      | 0.29%   |
| Seagate Technology          | 2        | 3      | 0.29%   |
| Realtek                     | 2        | 2      | 0.29%   |
| OWC                         | 2        | 6      | 0.29%   |
| Neo                         | 2        | 3      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 17       | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 14       | 1.8%    |
| Seagate ST1000DM010-2EP102 1TB                        | 10       | 1.29%   |
| Samsung SSD 980 1TB                                   | 9        | 1.16%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 8        | 1.03%   |
| Seagate ST2000DM008-2FR102 2TB                        | 7        | 0.9%    |
| Samsung SSD 860 EVO 500GB                             | 7        | 0.9%    |
| Samsung SSD 850 EVO 250GB                             | 7        | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6        | 0.77%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 6        | 0.77%   |
| Kingston SA400S37240G 240GB SSD                       | 6        | 0.77%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 5        | 0.64%   |
| Seagate ST4000DM004-2CV104 4TB                        | 5        | 0.64%   |
| Seagate ST3500418AS 500GB                             | 5        | 0.64%   |
| Seagate ST2000DM001-1ER164 2TB                        | 5        | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5        | 0.64%   |
| SanDisk SSD PLUS 1000GB                               | 5        | 0.64%   |
| Samsung SSD 870 EVO 500GB                             | 5        | 0.64%   |
| Samsung SSD 870 EVO 1TB                               | 5        | 0.64%   |
| Samsung SSD 850 EVO 500GB                             | 5        | 0.64%   |
| Phison E12 NVMe Controller 256GB                      | 5        | 0.64%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 4        | 0.52%   |
| Toshiba DT01ACA100 1TB                                | 4        | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB                        | 4        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB                        | 4        | 0.52%   |
| Samsung SSD 990 PRO 1TB                               | 4        | 0.52%   |
| Samsung SSD 860 QVO 1TB                               | 4        | 0.52%   |
| Samsung PSSD T7 1TB                                   | 4        | 0.52%   |
| SABRENT Disk 1TB                                      | 4        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                       | 4        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                           | 4        | 0.52%   |
| Apacer AS350 512GB SSD                                | 4        | 0.52%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 3        | 0.39%   |
| WDC WD5000AAKX-001CA0 500GB                           | 3        | 0.39%   |
| WDC WD20EZAZ-00L9GB0 2TB                              | 3        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 3        | 0.39%   |
| WDC WD1003FZEX-00MK2A0 1TB                            | 3        | 0.39%   |
| Toshiba HDWD130 3TB                                   | 3        | 0.39%   |
| Toshiba DT01ACA200 2TB                                | 3        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 112      | 156    | 40%     |
| WDC                 | 95       | 136    | 33.93%  |
| Toshiba             | 22       | 25     | 7.86%   |
| Hitachi             | 20       | 26     | 7.14%   |
| Samsung Electronics | 13       | 15     | 4.64%   |
| HGST                | 6        | 6      | 2.14%   |
| SABRENT             | 4        | 7      | 1.43%   |
| Unknown             | 2        | 2      | 0.71%   |
| Maxtor              | 2        | 3      | 0.71%   |
| USB3.0              | 1        | 1      | 0.36%   |
| Intenso             | 1        | 1      | 0.36%   |
| ASMT                | 1        | 3      | 0.36%   |
| Apple               | 1        | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 57       | 78     | 25.79%  |
| SanDisk             | 23       | 32     | 10.41%  |
| Kingston            | 23       | 29     | 10.41%  |
| Crucial             | 22       | 24     | 9.95%   |
| WDC                 | 12       | 12     | 5.43%   |
| Intel               | 7        | 8      | 3.17%   |
| China               | 7        | 9      | 3.17%   |
| Apacer              | 4        | 5      | 1.81%   |
| Toshiba             | 3        | 3      | 1.36%   |
| PNY                 | 3        | 3      | 1.36%   |
| Patriot             | 3        | 3      | 1.36%   |
| OCZ                 | 3        | 3      | 1.36%   |
| KingSpec            | 3        | 4      | 1.36%   |
| A-DATA Technology   | 3        | 5      | 1.36%   |
| Vaseky              | 2        | 2      | 0.9%    |
| Team                | 2        | 2      | 0.9%    |
| Smartbuy            | 2        | 3      | 0.9%    |
| OWC                 | 2        | 6      | 0.9%    |
| Neo                 | 2        | 3      | 0.9%    |
| Micron Technology   | 2        | 3      | 0.9%    |
| Hewlett-Packard     | 2        | 2      | 0.9%    |
| Gigastone           | 2        | 2      | 0.9%    |
| Emtec               | 2        | 2      | 0.9%    |
| ASMT                | 2        | 2      | 0.9%    |
| WALRAM              | 1        | 1      | 0.45%   |
| Verbatim            | 1        | 6      | 0.45%   |
| V7                  | 1        | 1      | 0.45%   |
| TO Exter            | 1        | 1      | 0.45%   |
| TEXTORM             | 1        | 1      | 0.45%   |
| T-FORCE             | 1        | 1      | 0.45%   |
| SPCC                | 1        | 1      | 0.45%   |
| Seagate             | 1        | 1      | 0.45%   |
| Rogueware           | 1        | 1      | 0.45%   |
| Phison              | 1        | 1      | 0.45%   |
| NN                  | 1        | 1      | 0.45%   |
| MSI                 | 1        | 1      | 0.45%   |
| MicroFrom           | 1        | 1      | 0.45%   |
| LuminouTek          | 1        | 1      | 0.45%   |
| LS                  | 1        | 1      | 0.45%   |
| LITEONIT            | 1        | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 222      | 382    | 38.88%  |
| SSD     | 183      | 279    | 32.05%  |
| NVMe    | 153      | 234    | 26.8%   |
| Unknown | 11       | 12     | 1.93%   |
| MMC     | 2        | 2      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 295      | 631    | 61.33%  |
| NVMe | 153      | 232    | 31.81%  |
| SAS  | 31       | 44     | 6.44%   |
| MMC  | 2        | 2      | 0.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 196      | 301    | 44.44%  |
| 0.51-1.0   | 136      | 210    | 30.84%  |
| 1.01-2.0   | 57       | 73     | 12.93%  |
| 3.01-4.0   | 23       | 35     | 5.22%   |
| 4.01-10.0  | 15       | 25     | 3.4%    |
| 2.01-3.0   | 12       | 14     | 2.72%   |
| 10.01-20.0 | 2        | 3      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 81       | 21.89%  |
| 251-500        | 78       | 21.08%  |
| 101-250        | 73       | 19.73%  |
| 1001-2000      | 48       | 12.97%  |
| More than 3000 | 39       | 10.54%  |
| 2001-3000      | 19       | 5.14%   |
| 1-20           | 12       | 3.24%   |
| 51-100         | 12       | 3.24%   |
| 21-50          | 6        | 1.62%   |
| Unknown        | 2        | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 103      | 27.69%  |
| 21-50          | 84       | 22.58%  |
| 101-250        | 47       | 12.63%  |
| 51-100         | 41       | 11.02%  |
| 251-500        | 33       | 8.87%   |
| 501-1000       | 23       | 6.18%   |
| More than 3000 | 16       | 4.3%    |
| 1001-2000      | 12       | 3.23%   |
| 2001-3000      | 11       | 2.96%   |
| Unknown        | 2        | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| WDC WD10EZEX-22MFCA0 1TB                | 2        | 3      | 5.26%   |
| Neo Forza NFS121SA312-6007000 120GB SSD | 2        | 3      | 5.26%   |
| Kingston SV300S37A120G 120GB SSD        | 2        | 2      | 5.26%   |
| WDC WD6400AACS-00G8B1 640GB             | 1        | 1      | 2.63%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1        | 1      | 2.63%   |
| WDC WD5000HHTZ-04N21V0 500GB            | 1        | 1      | 2.63%   |
| WDC WD5000AZLX-22JKKA0 500GB            | 1        | 1      | 2.63%   |
| WDC WD5000AAKX-001CA0 500GB             | 1        | 1      | 2.63%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 1        | 1      | 2.63%   |
| WDC WD2500AAKX-753CA1 250GB             | 1        | 1      | 2.63%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1        | 1      | 2.63%   |
| WDC WD10EZEX-60WN4A0 1TB                | 1        | 1      | 2.63%   |
| WDC WD10EARS-22Y5B1 1TB                 | 1        | 1      | 2.63%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 1        | 1      | 2.63%   |
| Toshiba MK3261GSYN 320GB                | 1        | 1      | 2.63%   |
| Toshiba MK2555GSXF 250GB                | 1        | 1      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB         | 1        | 1      | 2.63%   |
| Seagate ST3500418AS 500GB               | 1        | 1      | 2.63%   |
| Seagate ST2000LX001-1RG174 2TB          | 1        | 1      | 2.63%   |
| Seagate ST2000LM007-1R8174 2TB          | 1        | 1      | 2.63%   |
| SanDisk SSD PLUS 240GB                  | 1        | 1      | 2.63%   |
| SanDisk SD7SB2Q-512G-1006 512GB SSD     | 1        | 1      | 2.63%   |
| Samsung Electronics SSD 960 EVO 250GB   | 1        | 1      | 2.63%   |
| Samsung Electronics HD502HJ 500GB       | 1        | 1      | 2.63%   |
| Samsung Electronics HD161GJ 160GB       | 1        | 1      | 2.63%   |
| Maxtor 6L160M0 160GB                    | 1        | 2      | 2.63%   |
| Kingston SUV400S37240G 240GB SSD        | 1        | 1      | 2.63%   |
| Intel SSDSC2KW240H6 240GB               | 1        | 1      | 2.63%   |
| Intel SSDSC2BF180A5L 180GB              | 1        | 1      | 2.63%   |
| Hitachi HDT721010SLA360 1TB             | 1        | 1      | 2.63%   |
| Hitachi HDS721010CLA332 1TB             | 1        | 1      | 2.63%   |
| Gigabyte Technology GP-GM30512G-G 512GB | 1        | 1      | 2.63%   |
| Crucial CT512MX100SSD1 512GB            | 1        | 1      | 2.63%   |
| Crucial CT240M500SSD1 240GB             | 1        | 1      | 2.63%   |
| Crucial CT1050MX300SSD1 1TB             | 1        | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 14     | 34.21%  |
| Seagate             | 4        | 4      | 10.53%  |
| Samsung Electronics | 3        | 3      | 7.89%   |
| Kingston            | 3        | 3      | 7.89%   |
| Crucial             | 3        | 3      | 7.89%   |
| Toshiba             | 2        | 2      | 5.26%   |
| SanDisk             | 2        | 2      | 5.26%   |
| Neo                 | 2        | 3      | 5.26%   |
| Intel               | 2        | 2      | 5.26%   |
| Hitachi             | 2        | 2      | 5.26%   |
| Maxtor              | 1        | 2      | 2.63%   |
| Gigabyte Technology | 1        | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 14     | 54.17%  |
| Seagate             | 4        | 4      | 16.67%  |
| Toshiba             | 2        | 2      | 8.33%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| Hitachi             | 2        | 2      | 8.33%   |
| Maxtor              | 1        | 2      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 26     | 62.16%  |
| SSD  | 12       | 13     | 32.43%  |
| NVMe | 2        | 2      | 5.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 260      | 631    | 65%     |
| Works    | 107      | 236    | 26.75%  |
| Malfunc  | 32       | 41     | 8%      |
| Failed   | 1        | 1      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 231      | 40.46%  |
| AMD                          | 123      | 21.54%  |
| Samsung Electronics          | 62       | 10.86%  |
| SanDisk                      | 22       | 3.85%   |
| Phison Electronics           | 20       | 3.5%    |
| Kingston Technology Company  | 18       | 3.15%   |
| Micron/Crucial Technology    | 16       | 2.8%    |
| ASMedia Technology           | 16       | 2.8%    |
| SK hynix                     | 8        | 1.4%    |
| Marvell Technology Group     | 7        | 1.23%   |
| Seagate Technology           | 6        | 1.05%   |
| MAXIO Technology (Hangzhou)  | 6        | 1.05%   |
| Silicon Motion               | 5        | 0.88%   |
| JMicron Technology           | 5        | 0.88%   |
| Toshiba America Info Systems | 4        | 0.7%    |
| KIOXIA                       | 4        | 0.7%    |
| Realtek Semiconductor        | 3        | 0.53%   |
| Nvidia                       | 2        | 0.35%   |
| Micron Technology            | 2        | 0.35%   |
| Broadcom / LSI               | 2        | 0.35%   |
| Yangtze Memory Technologies  | 1        | 0.18%   |
| VIA Technologies             | 1        | 0.18%   |
| Shenzhen Longsys Electronics | 1        | 0.18%   |
| OCZ Technology Group         | 1        | 0.18%   |
| Netac Technology             | 1        | 0.18%   |
| LSI Logic / Symbios Logic    | 1        | 0.18%   |
| INNOGRIT                     | 1        | 0.18%   |
| Apple                        | 1        | 0.18%   |
| ADATA Technology             | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 76       | 11.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23       | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 3.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21       | 3.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 20       | 2.92%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 2.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18       | 2.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 17       | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 2.19%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 13       | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13       | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 1.9%    |
| Samsung NVMe SSD Controller 980                                                         | 12       | 1.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 12       | 1.75%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9        | 1.31%   |
| Phison E12 NVMe Controller                                                              | 9        | 1.31%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 1.31%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 1.31%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.17%   |
| Kingston Company Company Non-Volatile memory controller                                 | 7        | 1.02%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 7        | 1.02%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 6        | 0.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 0.88%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.88%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 4        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 0.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 4        | 0.58%   |
| Phison E18 PCIe4 NVMe Controller                                                        | 4        | 0.58%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 4        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 307      | 55.72%  |
| NVMe | 153      | 27.77%  |
| IDE  | 55       | 9.98%   |
| RAID | 34       | 6.17%   |
| SAS  | 2        | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 234      | 65%     |
| AMD    | 126      | 35%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1.66%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 6        | 1.66%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.38%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 5        | 1.38%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 5        | 1.38%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 1.38%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 5        | 1.38%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 5        | 1.38%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 1.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 1.1%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 1.1%    |
| Intel 13th Gen Core i9-13900K               | 4        | 1.1%    |
| Intel 12th Gen Core i7-12700                | 4        | 1.1%    |
| AMD Ryzen 9 7900 12-Core Processor          | 4        | 1.1%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 1.1%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 1.1%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.83%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.83%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 3        | 0.83%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 3        | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 0.83%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.83%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 0.83%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 0.83%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 3        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.83%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 3        | 0.83%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 0.83%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.83%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 3        | 0.83%   |
| AMD Ryzen 5 5500                            | 3        | 0.83%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 0.83%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 2        | 0.55%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 2        | 0.55%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 2        | 0.55%   |
| Intel N100                                  | 2        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 70       | 19.39%  |
| Intel Core i7           | 46       | 12.74%  |
| Other                   | 40       | 11.08%  |
| AMD Ryzen 5             | 30       | 8.31%   |
| AMD Ryzen 7             | 28       | 7.76%   |
| Intel Core i3           | 24       | 6.65%   |
| AMD Ryzen 9             | 23       | 6.37%   |
| Intel Xeon              | 18       | 4.99%   |
| Intel Core 2 Duo        | 10       | 2.77%   |
| Intel Celeron           | 8        | 2.22%   |
| AMD FX                  | 7        | 1.94%   |
| Intel Pentium Dual-Core | 4        | 1.11%   |
| Intel Pentium           | 4        | 1.11%   |
| Intel Core 2 Quad       | 4        | 1.11%   |
| AMD Ryzen 3             | 4        | 1.11%   |
| AMD Phenom II X4        | 4        | 1.11%   |
| AMD Athlon II X2        | 4        | 1.11%   |
| AMD A10                 | 4        | 1.11%   |
| Intel Atom              | 3        | 0.83%   |
| AMD Ryzen 5 PRO         | 3        | 0.83%   |
| AMD A8                  | 3        | 0.83%   |
| Intel Core i9           | 2        | 0.55%   |
| AMD Athlon X4           | 2        | 0.55%   |
| Intel Pentium Silver    | 1        | 0.28%   |
| Intel Pentium 4         | 1        | 0.28%   |
| Intel Celeron D         | 1        | 0.28%   |
| AMD Ryzen Threadripper  | 1        | 0.28%   |
| AMD Ryzen 7 PRO         | 1        | 0.28%   |
| AMD Ryzen 3 PRO         | 1        | 0.28%   |
| AMD Phenom II X6        | 1        | 0.28%   |
| AMD Phenom II X2        | 1        | 0.28%   |
| AMD Phenom              | 1        | 0.28%   |
| AMD Athlon II X4        | 1        | 0.28%   |
| AMD Athlon II X3        | 1        | 0.28%   |
| AMD Athlon Dual Core    | 1        | 0.28%   |
| AMD Athlon 64 X2        | 1        | 0.28%   |
| AMD Athlon              | 1        | 0.28%   |
| AMD A6                  | 1        | 0.28%   |
| AMD A4                  | 1        | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 132      | 36.67%  |
| 6      | 63       | 17.5%   |
| 2      | 63       | 17.5%   |
| 8      | 41       | 11.39%  |
| 12     | 28       | 7.78%   |
| 16     | 9        | 2.5%    |
| 24     | 5        | 1.39%   |
| 3      | 5        | 1.39%   |
| 14     | 4        | 1.11%   |
| 1      | 4        | 1.11%   |
| 10     | 3        | 0.83%   |
| 32     | 1        | 0.28%   |
| 20     | 1        | 0.28%   |
| 7      | 1        | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 355      | 98.61%  |
| 2      | 5        | 1.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 220      | 60.94%  |
| 1      | 141      | 39.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 360      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 304      | 84.21%  |
| 0x0a601203 | 13       | 3.6%    |
| 0x0a50000d | 8        | 2.22%   |
| 0x0a20120a | 4        | 1.11%   |
| 0x0800820d | 3        | 0.83%   |
| 0x010000c8 | 3        | 0.83%   |
| 0x0a201025 | 2        | 0.55%   |
| 0x08701030 | 2        | 0.55%   |
| 0x08701021 | 2        | 0.55%   |
| 0x08108109 | 2        | 0.55%   |
| 0xf64      | 1        | 0.28%   |
| 0x306c3    | 1        | 0.28%   |
| 0x0a704103 | 1        | 0.28%   |
| 0x0a50000c | 1        | 0.28%   |
| 0x0a50000b | 1        | 0.28%   |
| 0x0a404102 | 1        | 0.28%   |
| 0x0a201205 | 1        | 0.28%   |
| 0x0a201009 | 1        | 0.28%   |
| 0x08600109 | 1        | 0.28%   |
| 0x08101016 | 1        | 0.28%   |
| 0x0810100b | 1        | 0.28%   |
| 0x08001138 | 1        | 0.28%   |
| 0x06006705 | 1        | 0.28%   |
| 0x06001119 | 1        | 0.28%   |
| 0x06000852 | 1        | 0.28%   |
| 0x0600063e | 1        | 0.28%   |
| 0x010000dc | 1        | 0.28%   |
| 0x00000000 | 1        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 52       | 14.36%  |
| Haswell          | 44       | 12.15%  |
| Zen 3            | 31       | 8.56%   |
| KabyLake         | 29       | 8.01%   |
| IvyBridge        | 26       | 7.18%   |
| Skylake          | 25       | 6.91%   |
| SandyBridge      | 18       | 4.97%   |
| Penryn           | 18       | 4.97%   |
| Zen 2            | 17       | 4.7%    |
| Zen+             | 13       | 3.59%   |
| Piledriver       | 13       | 3.59%   |
| K10              | 13       | 3.59%   |
| Zen              | 9        | 2.49%   |
| CometLake        | 8        | 2.21%   |
| Alderlake Hybrid | 7        | 1.93%   |
| Westmere         | 5        | 1.38%   |
| Silvermont       | 5        | 1.38%   |
| Nehalem          | 4        | 1.1%    |
| Icelake          | 3        | 0.83%   |
| Excavator        | 3        | 0.83%   |
| Core             | 3        | 0.83%   |
| Broadwell        | 3        | 0.83%   |
| NetBurst         | 2        | 0.55%   |
| K8 Hammer        | 2        | 0.55%   |
| Gracemont        | 2        | 0.55%   |
| Goldmont         | 2        | 0.55%   |
| Bulldozer        | 2        | 0.55%   |
| TigerLake        | 1        | 0.28%   |
| Steamroller      | 1        | 0.28%   |
| Bonnell          | 1        | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 134      | 34.1%   |
| Intel                      | 129      | 32.82%  |
| AMD                        | 128      | 32.57%  |
| Matrox Electronics Systems | 2        | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 4.69%   |
| AMD Raphael                                                                 | 18       | 4.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 15       | 3.7%    |
| Intel HD Graphics 530                                                       | 15       | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 3.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 11       | 2.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 2.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 9        | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 2.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 1.98%   |
| Intel HD Graphics 630                                                       | 8        | 1.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 1.73%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.48%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 1.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.23%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 5        | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.23%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 1.23%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.23%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.23%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.99%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 0.99%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 4        | 0.99%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 4        | 0.99%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 4        | 0.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4        | 0.99%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 0.99%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 4        | 0.99%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 4        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 0.74%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.74%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 0.74%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 0.74%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 0.74%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.74%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 110      | 30.39%  |
| 1 x Intel           | 107      | 29.56%  |
| 1 x AMD             | 107      | 29.56%  |
| AMD + Nvidia        | 11       | 3.04%   |
| Intel + Nvidia      | 10       | 2.76%   |
| 2 x AMD             | 7        | 1.93%   |
| Intel + AMD         | 3        | 0.83%   |
| 1 x Matrox          | 2        | 0.55%   |
| Intel + 2 x Nvidia  | 2        | 0.55%   |
| 2 x Nvidia          | 1        | 0.28%   |
| 2 x Intel + 1 x AMD | 1        | 0.28%   |
| 2 x Intel           | 1        | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 263      | 72.25%  |
| Proprietary | 90       | 24.73%  |
| Unknown     | 11       | 3.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 266      | 73.08%  |
| 0.01-0.5   | 21       | 5.77%   |
| 3.01-4.0   | 20       | 5.49%   |
| 7.01-8.0   | 18       | 4.95%   |
| 1.01-2.0   | 15       | 4.12%   |
| 0.51-1.0   | 10       | 2.75%   |
| 16.01-24.0 | 5        | 1.37%   |
| 8.01-16.0  | 5        | 1.37%   |
| 5.01-6.0   | 4        | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 63       | 16.94%  |
| Goldstar             | 40       | 10.75%  |
| Dell                 | 38       | 10.22%  |
| Acer                 | 28       | 7.53%   |
| Hewlett-Packard      | 22       | 5.91%   |
| AOC                  | 21       | 5.65%   |
| Ancor Communications | 20       | 5.38%   |
| Philips              | 17       | 4.57%   |
| Iiyama               | 17       | 4.57%   |
| BenQ                 | 12       | 3.23%   |
| ViewSonic            | 9        | 2.42%   |
| ASUSTek Computer     | 7        | 1.88%   |
| Lenovo               | 6        | 1.61%   |
| MSI                  | 4        | 1.08%   |
| Vestel Elektronik    | 3        | 0.81%   |
| NEC Computers        | 3        | 0.81%   |
| MiTAC                | 3        | 0.81%   |
| HKC                  | 3        | 0.81%   |
| Gigabyte Technology  | 3        | 0.81%   |
| Fujitsu Siemens      | 3        | 0.81%   |
| Eizo                 | 3        | 0.81%   |
| Wacom                | 2        | 0.54%   |
| Unknown (XXX)        | 2        | 0.54%   |
| TCL                  | 2        | 0.54%   |
| Sony                 | 2        | 0.54%   |
| SGT                  | 2        | 0.54%   |
| Sceptre Tech         | 2        | 0.54%   |
| Medion               | 2        | 0.54%   |
| Hitachi              | 2        | 0.54%   |
| Gericom              | 2        | 0.54%   |
| Unknown              | 2        | 0.54%   |
| ___                  | 1        | 0.27%   |
| Xiaomi               | 1        | 0.27%   |
| Vizio                | 1        | 0.27%   |
| Unknown (AAA)        | 1        | 0.27%   |
| Unknown              | 1        | 0.27%   |
| Toshiba              | 1        | 0.27%   |
| SANYO                | 1        | 0.27%   |
| RTD                  | 1        | 0.27%   |
| Positivo             | 1        | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 4        | 1.03%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                         | 3        | 0.77%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.77%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3        | 0.77%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.77%   |
| Wacom Cintiq 13HD WAC1040 1920x1080 293x165mm 13.2-inch               | 2        | 0.51%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 2        | 0.51%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2        | 0.51%   |
| Samsung Electronics LCD Monitor SAM0D47 1920x1080 480x270mm 21.7-inch | 2        | 0.51%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch   | 2        | 0.51%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.51%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.51%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                   | 2        | 0.51%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 2        | 0.51%   |
| HKC '' HKC2160 1920x1080 360x270mm 17.7-inch                          | 2        | 0.51%   |
| Goldstar ULTRAGEAR GSM5BB2 1920x1080 527x296mm 23.8-inch              | 2        | 0.51%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 0.51%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.51%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 0.51%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 2        | 0.51%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 0.51%   |
| ASUSTek Computer PB278QV AUS278A 2560x1440 597x336mm 27.0-inch        | 2        | 0.51%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 2        | 0.51%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 2        | 0.51%   |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 798x335mm 34.1-inch | 2        | 0.51%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 2        | 0.51%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 2        | 0.51%   |
| Acer S191HQL ACR021C 1366x768 410x230mm 18.5-inch                     | 2        | 0.51%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                    | 2        | 0.51%   |
| Acer G236HL ACR02D4 1920x1080 509x286mm 23.0-inch                     | 2        | 0.51%   |
| Unknown                                                               | 2        | 0.51%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1        | 0.26%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 0.26%   |
| Vizio E422VLE VIZ0092 1920x1080 930x523mm 42.0-inch                   | 1        | 0.26%   |
| ViewSonic XG350R-C VSC4F37 3440x1440 819x346mm 35.0-inch              | 1        | 0.26%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 0.26%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1        | 0.26%   |
| ViewSonic VX2235wm-EU VSC591E 1680x1050 474x296mm 22.0-inch           | 1        | 0.26%   |
| ViewSonic VG2755-2K VSC4E37 2560x1440 597x336mm 27.0-inch             | 1        | 0.26%   |
| ViewSonic VA2746 SERIES VSC752E 1920x1080 598x336mm 27.0-inch         | 1        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 178      | 49.58%  |
| 3840x2160 (4K)     | 52       | 14.48%  |
| 2560x1440 (QHD)    | 38       | 10.58%  |
| 1440x900 (WXGA+)   | 14       | 3.9%    |
| 1366x768 (WXGA)    | 13       | 3.62%   |
| 3440x1440          | 10       | 2.79%   |
| 1280x1024 (SXGA)   | 10       | 2.79%   |
| 2560x1080          | 7        | 1.95%   |
| 1920x1200 (WUXGA)  | 5        | 1.39%   |
| 3840x1080          | 4        | 1.11%   |
| 1680x1050 (WSXGA+) | 4        | 1.11%   |
| 1280x720 (HD)      | 4        | 1.11%   |
| Unknown            | 4        | 1.11%   |
| 1920x540           | 3        | 0.84%   |
| 1600x900 (HD+)     | 3        | 0.84%   |
| 3840x1600          | 2        | 0.56%   |
| 1360x768           | 2        | 0.56%   |
| 5760x2160          | 1        | 0.28%   |
| 2560x1600          | 1        | 0.28%   |
| 1600x1200          | 1        | 0.28%   |
| 1280x960           | 1        | 0.28%   |
| 1024x768 (XGA)     | 1        | 0.28%   |
| 1024x600           | 1        | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 57       | 15.28%  |
| 24      | 54       | 14.48%  |
| 23      | 47       | 12.6%   |
| 21      | 42       | 11.26%  |
| 31      | 27       | 7.24%   |
| 19      | 18       | 4.83%   |
| Unknown | 15       | 4.02%   |
| 18      | 14       | 3.75%   |
| 34      | 11       | 2.95%   |
| 84      | 10       | 2.68%   |
| 17      | 9        | 2.41%   |
| 40      | 6        | 1.61%   |
| 22      | 6        | 1.61%   |
| 35      | 5        | 1.34%   |
| 32      | 5        | 1.34%   |
| 65      | 4        | 1.07%   |
| 48      | 4        | 1.07%   |
| 20      | 4        | 1.07%   |
| 72      | 3        | 0.8%    |
| 52      | 3        | 0.8%    |
| 42      | 3        | 0.8%    |
| 28      | 3        | 0.8%    |
| 26      | 3        | 0.8%    |
| 13      | 3        | 0.8%    |
| 54      | 2        | 0.54%   |
| 16      | 2        | 0.54%   |
| 63      | 1        | 0.27%   |
| 61      | 1        | 0.27%   |
| 60      | 1        | 0.27%   |
| 46      | 1        | 0.27%   |
| 43      | 1        | 0.27%   |
| 38      | 1        | 0.27%   |
| 37      | 1        | 0.27%   |
| 33      | 1        | 0.27%   |
| 29      | 1        | 0.27%   |
| 15      | 1        | 0.27%   |
| 14      | 1        | 0.27%   |
| 10      | 1        | 0.27%   |
| 9       | 1        | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 147      | 40.16%  |
| 401-500     | 76       | 20.77%  |
| 601-700     | 38       | 10.38%  |
| 701-800     | 17       | 4.64%   |
| 1001-1500   | 17       | 4.64%   |
| Unknown     | 15       | 4.1%    |
| 351-400     | 13       | 3.55%   |
| 1501-2000   | 13       | 3.55%   |
| 801-900     | 12       | 3.28%   |
| 301-350     | 7        | 1.91%   |
| 201-300     | 5        | 1.37%   |
| 901-1000    | 5        | 1.37%   |
| 101-200     | 1        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 254      | 74.05%  |
| 16/10   | 32       | 9.33%   |
| 21/9    | 19       | 5.54%   |
| 5/4     | 14       | 4.08%   |
| Unknown | 12       | 3.5%    |
| 4/3     | 7        | 2.04%   |
| 32/9    | 5        | 1.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 109      | 29.62%  |
| 301-350        | 59       | 16.03%  |
| 351-500        | 51       | 13.86%  |
| 151-200        | 39       | 10.6%   |
| 251-300        | 27       | 7.34%   |
| More than 1000 | 26       | 7.07%   |
| 141-150        | 17       | 4.62%   |
| 501-1000       | 15       | 4.08%   |
| Unknown        | 15       | 4.08%   |
| 71-80          | 3        | 0.82%   |
| 101-110        | 3        | 0.82%   |
| 51-60          | 1        | 0.27%   |
| 41-50          | 1        | 0.27%   |
| 131-140        | 1        | 0.27%   |
| 121-130        | 1        | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 212      | 59.72%  |
| 101-120 | 82       | 23.1%   |
| 121-160 | 20       | 5.63%   |
| 1-50    | 15       | 4.23%   |
| Unknown | 15       | 4.23%   |
| 161-240 | 11       | 3.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 283      | 77.53%  |
| 2     | 55       | 15.07%  |
| 0     | 21       | 5.75%   |
| 3     | 5        | 1.37%   |
| 4     | 1        | 0.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 235      | 43.93%  |
| Intel                           | 150      | 28.04%  |
| Qualcomm Atheros                | 23       | 4.3%    |
| Broadcom                        | 21       | 3.93%   |
| TP-Link                         | 17       | 3.18%   |
| MediaTek                        | 16       | 2.99%   |
| Ralink Technology               | 8        | 1.5%    |
| Microsoft                       | 8        | 1.5%    |
| NetGear                         | 7        | 1.31%   |
| D-Link                          | 6        | 1.12%   |
| Aquantia                        | 4        | 0.75%   |
| Xiaomi                          | 3        | 0.56%   |
| Ralink                          | 3        | 0.56%   |
| Qualcomm Atheros Communications | 3        | 0.56%   |
| Mellanox Technologies           | 3        | 0.56%   |
| Samsung Electronics             | 2        | 0.37%   |
| Marvell Technology Group        | 2        | 0.37%   |
| Huawei Technologies             | 2        | 0.37%   |
| Google                          | 2        | 0.37%   |
| Edimax Technology               | 2        | 0.37%   |
| D-Link System                   | 2        | 0.37%   |
| AVM                             | 2        | 0.37%   |
| ASUSTek Computer                | 2        | 0.37%   |
| Apple                           | 2        | 0.37%   |
| ZyDAS                           | 1        | 0.19%   |
| Z-Com                           | 1        | 0.19%   |
| Qualcomm                        | 1        | 0.19%   |
| Philips (or NXP)                | 1        | 0.19%   |
| Nvidia                          | 1        | 0.19%   |
| Linksys                         | 1        | 0.19%   |
| Guillemot                       | 1        | 0.19%   |
| Dresden Elektronik              | 1        | 0.19%   |
| Broadcom Limited                | 1        | 0.19%   |
| 3Com                            | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 179      | 29.49%  |
| Realtek RTL8125 2.5GbE Controller                                 | 31       | 5.11%   |
| Intel Ethernet Controller I225-V                                  | 19       | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 17       | 2.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15       | 2.47%   |
| Intel I211 Gigabit Network Connection                             | 13       | 2.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 10       | 1.65%   |
| Realtek 802.11ac NIC                                              | 8        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 1.15%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 7        | 1.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 0.99%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 5        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.82%   |
| Microsoft Xbox 360 Wireless Adapter                               | 5        | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 0.82%   |
| Intel Ethernet Connection (17) I219-V                             | 5        | 0.82%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 5        | 0.82%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 4        | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4        | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 0.66%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 4        | 0.66%   |
| D-Link 802.11ac NIC                                               | 4        | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 0.66%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 4        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.49%   |
| Intel Wireless-AC 9260                                            | 3        | 0.49%   |
| Intel Ethernet Controller I226-V                                  | 3        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 67       | 31.75%  |
| Realtek Semiconductor           | 41       | 19.43%  |
| TP-Link                         | 17       | 8.06%   |
| MediaTek                        | 16       | 7.58%   |
| Qualcomm Atheros                | 11       | 5.21%   |
| Broadcom                        | 11       | 5.21%   |
| Ralink Technology               | 8        | 3.79%   |
| Microsoft                       | 8        | 3.79%   |
| NetGear                         | 7        | 3.32%   |
| D-Link                          | 6        | 2.84%   |
| Ralink                          | 3        | 1.42%   |
| Qualcomm Atheros Communications | 3        | 1.42%   |
| Edimax Technology               | 2        | 0.95%   |
| AVM                             | 2        | 0.95%   |
| ASUSTek Computer                | 2        | 0.95%   |
| ZyDAS                           | 1        | 0.47%   |
| Z-Com                           | 1        | 0.47%   |
| Philips (or NXP)                | 1        | 0.47%   |
| Linksys                         | 1        | 0.47%   |
| Guillemot                       | 1        | 0.47%   |
| D-Link System                   | 1        | 0.47%   |
| Broadcom Limited                | 1        | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 17       | 7.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15       | 7.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 10       | 4.69%   |
| Realtek 802.11ac NIC                                           | 8        | 3.76%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7        | 3.29%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 5        | 2.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5        | 2.35%   |
| Microsoft Xbox 360 Wireless Adapter                            | 5        | 2.35%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 5        | 2.35%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 1.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4        | 1.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4        | 1.88%   |
| D-Link 802.11ac NIC                                            | 4        | 1.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4        | 1.88%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 4        | 1.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.41%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 1.41%   |
| Intel Wireless-AC 9260                                         | 3        | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3        | 1.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 0.94%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 0.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 0.94%   |
| TP-Link 802.11ac NIC                                           | 2        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2        | 0.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2        | 0.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 0.94%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 0.94%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 0.94%   |
| NetGear A6210                                                  | 2        | 0.94%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2        | 0.94%   |
| Intel Wireless 7265                                            | 2        | 0.94%   |
| Intel Wireless 7260                                            | 2        | 0.94%   |
| Intel Wireless 3165                                            | 2        | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2        | 0.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2        | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 224      | 58.64%  |
| Intel                    | 113      | 29.58%  |
| Qualcomm Atheros         | 13       | 3.4%    |
| Broadcom                 | 10       | 2.62%   |
| Aquantia                 | 4        | 1.05%   |
| Xiaomi                   | 3        | 0.79%   |
| Mellanox Technologies    | 3        | 0.79%   |
| Samsung Electronics      | 2        | 0.52%   |
| Marvell Technology Group | 2        | 0.52%   |
| Google                   | 2        | 0.52%   |
| Qualcomm                 | 1        | 0.26%   |
| Nvidia                   | 1        | 0.26%   |
| Huawei Technologies      | 1        | 0.26%   |
| D-Link System            | 1        | 0.26%   |
| Apple                    | 1        | 0.26%   |
| 3Com                     | 1        | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 179      | 45.78%  |
| Realtek RTL8125 2.5GbE Controller                                             | 31       | 7.93%   |
| Intel Ethernet Controller I225-V                                              | 19       | 4.86%   |
| Intel I211 Gigabit Network Connection                                         | 13       | 3.32%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7        | 1.79%   |
| Intel Ethernet Connection I217-LM                                             | 7        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 1.79%   |
| Intel Ethernet Connection (2) I218-V                                          | 6        | 1.53%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 1.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 5        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5        | 1.28%   |
| Intel I210 Gigabit Network Connection                                         | 5        | 1.28%   |
| Intel Ethernet Connection (7) I219-V                                          | 5        | 1.28%   |
| Intel Ethernet Connection (17) I219-V                                         | 5        | 1.28%   |
| Intel Ethernet Connection I217-V                                              | 4        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 0.77%   |
| Intel Ethernet Controller I226-V                                              | 3        | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.77%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3        | 0.77%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 3        | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 2        | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 2        | 0.51%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                         | 2        | 0.51%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 0.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2        | 0.51%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1        | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.26%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                              | 1        | 0.26%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 1        | 0.26%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1        | 0.26%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 354      | 64.01%  |
| WiFi     | 196      | 35.44%  |
| Modem    | 3        | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 271      | 72.46%  |
| WiFi     | 103      | 27.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 214      | 59.44%  |
| 2     | 118      | 32.78%  |
| 3     | 23       | 6.39%   |
| 0     | 4        | 1.11%   |
| 5     | 1        | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 239      | 65.84%  |
| Yes  | 124      | 34.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 63       | 40.13%  |
| Cambridge Silicon Radio         | 22       | 14.01%  |
| Realtek Semiconductor           | 19       | 12.1%   |
| MediaTek                        | 10       | 6.37%   |
| IMC Networks                    | 8        | 5.1%    |
| ASUSTek Computer                | 8        | 5.1%    |
| TP-Link                         | 5        | 3.18%   |
| Broadcom                        | 4        | 2.55%   |
| Qualcomm Atheros Communications | 3        | 1.91%   |
| Foxconn / Hon Hai               | 3        | 1.91%   |
| Apple                           | 3        | 1.91%   |
| Lite-On Technology              | 2        | 1.27%   |
| Realtek                         | 1        | 0.64%   |
| Logitech                        | 1        | 0.64%   |
| Integrated System Solution      | 1        | 0.64%   |
| HTC (High Tech Computer)        | 1        | 0.64%   |
| Fujitsu                         | 1        | 0.64%   |
| Dynex                           | 1        | 0.64%   |
| Belkin Components               | 1        | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 22       | 13.92%  |
| Realtek Bluetooth Radio                                              | 16       | 10.13%  |
| Intel AX200 Bluetooth                                                | 15       | 9.49%   |
| Intel AX210 Bluetooth                                                | 12       | 7.59%   |
| Intel AX201 Bluetooth                                                | 11       | 6.96%   |
| MediaTek Wireless_Device                                             | 10       | 6.33%   |
| Intel Bluetooth wireless interface                                   | 10       | 6.33%   |
| Intel Bluetooth Device                                               | 10       | 6.33%   |
| TP-Link UB5A Adapter                                                 | 5        | 3.16%   |
| IMC Networks Bluetooth Radio                                         | 5        | 3.16%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3        | 1.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 1.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 1.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 3        | 1.9%    |
| Apple Bluetooth Host Controller                                      | 3        | 1.9%    |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 1.27%   |
| IMC Networks Wireless_Device                                         | 2        | 1.27%   |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 1.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 1.27%   |
| ASUS ASUS USB-BT500                                                  | 2        | 1.27%   |
| Realtek Bluetooth Radio                                              | 1        | 0.63%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.63%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 1        | 0.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 1        | 0.63%   |
| Lite-On Bluetooth Device                                             | 1        | 0.63%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.63%   |
| IMC Networks BCM20702A0                                              | 1        | 0.63%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.63%   |
| Fujitsu Bluetooth Device                                             | 1        | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1        | 0.63%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.63%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.63%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.63%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.63%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.63%   |
| ASUS Bluetooth Radio                                                 | 1        | 0.63%   |
| ASUS BCM20702A0                                                      | 1        | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 224      | 36.84%  |
| AMD                                             | 158      | 25.99%  |
| Nvidia                                          | 128      | 21.05%  |
| C-Media Electronics                             | 17       | 2.8%    |
| Logitech                                        | 13       | 2.14%   |
| ASUSTek Computer                                | 10       | 1.64%   |
| Texas Instruments                               | 5        | 0.82%   |
| GN Netcom                                       | 4        | 0.66%   |
| VIA Technologies                                | 3        | 0.49%   |
| Razer USA                                       | 3        | 0.49%   |
| Micro Star International                        | 3        | 0.49%   |
| KORG                                            | 3        | 0.49%   |
| Creative Labs                                   | 3        | 0.49%   |
| SteelSeries ApS                                 | 2        | 0.33%   |
| Samson Technologies                             | 2        | 0.33%   |
| Kingston Technology                             | 2        | 0.33%   |
| JMTek                                           | 2        | 0.33%   |
| Giga-Byte Technology                            | 2        | 0.33%   |
| Creative Technology                             | 2        | 0.33%   |
| BEHRINGER International                         | 2        | 0.33%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1        | 0.16%   |
| Yamaha                                          | 1        | 0.16%   |
| USB Audio                                       | 1        | 0.16%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.16%   |
| Tenx Technology                                 | 1        | 0.16%   |
| Sony                                            | 1        | 0.16%   |
| Realtek Semiconductor                           | 1        | 0.16%   |
| Nektar                                          | 1        | 0.16%   |
| Native Instruments                              | 1        | 0.16%   |
| Microdia                                        | 1        | 0.16%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.16%   |
| Lenovo                                          | 1        | 0.16%   |
| Jieli Technology                                | 1        | 0.16%   |
| JBL                                             | 1        | 0.16%   |
| Focusrite-Novation                              | 1        | 0.16%   |
| ESS Technology                                  | 1        | 0.16%   |
| DSEA A/S                                        | 1        | 0.16%   |
| Corsair                                         | 1        | 0.16%   |
| Astro Gaming                                    | 1        | 0.16%   |
| Apple                                           | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 44       | 5.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 29       | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24       | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23       | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22       | 2.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22       | 2.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20       | 2.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20       | 2.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18       | 2.44%   |
| Intel Alder Lake-S HD Audio Controller                                     | 17       | 2.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17       | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 15       | 2.03%   |
| Intel 200 Series PCH HD Audio                                              | 15       | 2.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 14       | 1.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 1.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 1.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13       | 1.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 12       | 1.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 12       | 1.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11       | 1.49%   |
| AMD FCH Azalia Controller                                                  | 11       | 1.49%   |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 1.22%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 9        | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 9        | 1.22%   |
| ASUSTek Computer USB Audio                                                 | 9        | 1.22%   |
| Nvidia GA102 High Definition Audio Controller                              | 8        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 1.08%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 8        | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                              | 7        | 0.95%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 7        | 0.95%   |
| AMD Trinity HDMI Audio Controller                                          | 7        | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 0.95%   |
| AMD Navi 10 HDMI Audio                                                     | 7        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 6        | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 6        | 0.81%   |
| Nvidia Audio device                                                        | 6        | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6        | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston                             | 34       | 20.61%  |
| Corsair                              | 21       | 12.73%  |
| Unknown                              | 18       | 10.91%  |
| G.Skill                              | 15       | 9.09%   |
| Samsung Electronics                  | 14       | 8.48%   |
| Crucial                              | 11       | 6.67%   |
| SK hynix                             | 9        | 5.45%   |
| Micron Technology                    | 7        | 4.24%   |
| A-DATA Technology                    | 7        | 4.24%   |
| Team                                 | 4        | 2.42%   |
| Transcend                            | 2        | 1.21%   |
| Patriot                              | 2        | 1.21%   |
| Nanya Technology                     | 2        | 1.21%   |
| GOODRAM                              | 2        | 1.21%   |
| Unknown                              | 2        | 1.21%   |
| Unknown (ABCD)                       | 1        | 0.61%   |
| Unknown (AB)                         | 1        | 0.61%   |
| Unknown (0x9801)                     | 1        | 0.61%   |
| Unknown (0x0C26)                     | 1        | 0.61%   |
| Unknown (0B85)                       | 1        | 0.61%   |
| Unifosa                              | 1        | 0.61%   |
| Ramaxel Technology                   | 1        | 0.61%   |
| Patriot Memory                       | 1        | 0.61%   |
| Lexar                                | 1        | 0.61%   |
| Juhor                                | 1        | 0.61%   |
| Hewlett-Packard                      | 1        | 0.61%   |
| Elpida                               | 1        | 0.61%   |
| Chun Well Technology Holding Limited | 1        | 0.61%   |
| Atermiter                            | 1        | 0.61%   |
| ASint Technology                     | 1        | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 3        | 1.7%    |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s         | 3        | 1.7%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 3        | 1.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 2        | 1.14%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 1.14%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                      | 2        | 1.14%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s            | 2        | 1.14%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s               | 2        | 1.14%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s               | 2        | 1.14%   |
| G.Skill RAM F4-3600C19-16GVRB 16GB DIMM DDR4 3600MT/s          | 2        | 1.14%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 2        | 1.14%   |
| A-DATA RAM Module 16GB DIMM DDR4 3200MT/s                      | 2        | 1.14%   |
| Unknown                                                        | 2        | 1.14%   |
| Unknown RAM Module 8GB DIMM SDRAM                              | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 8GB DIMM                                    | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM SDRAM                              | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 4GB DIMM 400MT/s                            | 1        | 0.57%   |
| Unknown RAM Module 32GB DIMM DDR4 2400MT/s                     | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2                               | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR 533MT/s                        | 1        | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM SDRAM 800MT/s                      | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 1        | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                       | 1        | 0.57%   |
| Unknown RAM 3600 C18 Series 16GB DIMM DDR4 2933MT/s            | 1        | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 0.57%   |
| Unknown (AB) RAM Module 2GB DIMM LPDDR3 2133MT/s               | 1        | 0.57%   |
| Unknown (0x9801) RAM Module 4GB DIMM DDR3 1334MT/s             | 1        | 0.57%   |
| Unknown (0x0C26) RAM TIMETEC-UD4-3600 32GB DIMM DDR4 2667MT/s  | 1        | 0.57%   |
| Unknown (0B85) RAM Module 8GB DIMM DDR3                        | 1        | 0.57%   |
| Unifosa RAM HU524303EP0200 2GB DIMM DDR3 1333MT/s              | 1        | 0.57%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s               | 1        | 0.57%   |
| Transcend RAM JM2666HLB-8G 8GB DIMM DDR4 2667MT/s              | 1        | 0.57%   |
| Team RAM Value-667 1GB DIMM DDR 400MT/s                        | 1        | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 1        | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s             | 1        | 0.57%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s             | 1        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 78       | 51.32%  |
| DDR3    | 29       | 19.08%  |
| DDR5    | 22       | 14.47%  |
| SDRAM   | 11       | 7.24%   |
| Unknown | 4        | 2.63%   |
| DDR2    | 3        | 1.97%   |
| DDR     | 2        | 1.32%   |
| LPDDR5  | 1        | 0.66%   |
| LPDDR4  | 1        | 0.66%   |
| LPDDR3  | 1        | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 137      | 92.57%  |
| SODIMM       | 10       | 6.76%   |
| Row Of Chips | 1        | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 59       | 36.88%  |
| 16384 | 34       | 21.25%  |
| 32768 | 26       | 16.25%  |
| 4096  | 23       | 14.38%  |
| 2048  | 13       | 8.13%   |
| 1024  | 4        | 2.5%    |
| 512   | 1        | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 21       | 13.13%  |
| 1600    | 17       | 10.63%  |
| 3600    | 15       | 9.38%   |
| 2400    | 13       | 8.13%   |
| 2133    | 8        | 5%      |
| 1333    | 7        | 4.38%   |
| 6000    | 6        | 3.75%   |
| 2667    | 5        | 3.13%   |
| Unknown | 5        | 3.13%   |
| 5200    | 4        | 2.5%    |
| 4800    | 4        | 2.5%    |
| 2666    | 4        | 2.5%    |
| 800     | 4        | 2.5%    |
| 6400    | 3        | 1.88%   |
| 5600    | 3        | 1.88%   |
| 3866    | 3        | 1.88%   |
| 3733    | 3        | 1.88%   |
| 2933    | 3        | 1.88%   |
| 5808    | 2        | 1.25%   |
| 3666    | 2        | 1.25%   |
| 3400    | 2        | 1.25%   |
| 2048    | 2        | 1.25%   |
| 1867    | 2        | 1.25%   |
| 1866    | 2        | 1.25%   |
| 667     | 2        | 1.25%   |
| 400     | 2        | 1.25%   |
| 6800    | 1        | 0.63%   |
| 4199    | 1        | 0.63%   |
| 3933    | 1        | 0.63%   |
| 3800    | 1        | 0.63%   |
| 3534    | 1        | 0.63%   |
| 3533    | 1        | 0.63%   |
| 3466    | 1        | 0.63%   |
| 3334    | 1        | 0.63%   |
| 3266    | 1        | 0.63%   |
| 3066    | 1        | 0.63%   |
| 2800    | 1        | 0.63%   |
| 2176    | 1        | 0.63%   |
| 1800    | 1        | 0.63%   |
| 1334    | 1        | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 5        | 21.74%  |
| Brother Industries    | 5        | 21.74%  |
| Seiko Epson           | 4        | 17.39%  |
| Samsung Electronics   | 4        | 17.39%  |
| Canon                 | 2        | 8.7%    |
| QinHeng Electronics   | 1        | 4.35%   |
| Pantum                | 1        | 4.35%   |
| Lexmark International | 1        | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 4.35%   |
| Seiko Epson ET-8550 Series                   | 1        | 4.35%   |
| Seiko Epson ET-2820 Series                   | 1        | 4.35%   |
| Seiko Epson ET-2810 Series                   | 1        | 4.35%   |
| Samsung SCX-4623 Series                      | 1        | 4.35%   |
| Samsung SCX-3400 Series                      | 1        | 4.35%   |
| Samsung M2020 Series                         | 1        | 4.35%   |
| Samsung CLX-3170 Series                      | 1        | 4.35%   |
| QinHeng CH340S                               | 1        | 4.35%   |
| Pantum P2200 series                          | 1        | 4.35%   |
| Lexmark International MC3326adwe             | 1        | 4.35%   |
| HP OfficeJet 5200 series                     | 1        | 4.35%   |
| HP LaserJet P2055 series                     | 1        | 4.35%   |
| HP DeskJet 960c                              | 1        | 4.35%   |
| HP ColorLaserJet M253-M254                   | 1        | 4.35%   |
| HP Color LaserJet Pro M453-4                 | 1        | 4.35%   |
| Canon TR4500 series                          | 1        | 4.35%   |
| Canon iP7200 series                          | 1        | 4.35%   |
| Brother MFC-J1010DW                          | 1        | 4.35%   |
| Brother MFC-9330CDW                          | 1        | 4.35%   |
| Brother HL-2030 Laser Printer                | 1        | 4.35%   |
| Brother DCP-7055W                            | 1        | 4.35%   |
| Brother DCP-1610W                            | 1        | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Canon   | 2        | 66.67%  |
| Plustek | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Plustek 600dpi USB Scanner         | 1        | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1        | 33.33%  |
| Canon CanoScan LiDE 100            | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                              | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech                            | 29       | 43.28%  |
| Apple                               | 5        | 7.46%   |
| Microsoft                           | 4        | 5.97%   |
| Samsung Electronics                 | 3        | 4.48%   |
| ARC International                   | 3        | 4.48%   |
| Sunplus Innovation Technology       | 2        | 2.99%   |
| Razer USA                           | 2        | 2.99%   |
| Microdia                            | 2        | 2.99%   |
| YT-221117-J                         | 1        | 1.49%   |
| WCM_USB                             | 1        | 1.49%   |
| Trust                               | 1        | 1.49%   |
| SunplusIT                           | 1        | 1.49%   |
| Sonix Technology                    | 1        | 1.49%   |
| Pixart Imaging                      | 1        | 1.49%   |
| Lite-On Technology                  | 1        | 1.49%   |
| KYE Systems (Mouse Systems)         | 1        | 1.49%   |
| Hauppauge                           | 1        | 1.49%   |
| Genesys Logic                       | 1        | 1.49%   |
| Generalplus Technology              | 1        | 1.49%   |
| Fuzhou Rockchip Electronics Company | 1        | 1.49%   |
| eMeet                               | 1        | 1.49%   |
| AVerMedia Technologies              | 1        | 1.49%   |
| Arkmicro Technologies               | 1        | 1.49%   |
| Anchor Chips                        | 1        | 1.49%   |
| Unknown                             | 1        | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech Webcam C270                      | 8        | 11.76%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X           | 4        | 5.88%   |
| Samsung Galaxy series, misc. (MTP mode)   | 3        | 4.41%   |
| Logitech HD Pro Webcam C920               | 3        | 4.41%   |
| Logitech BRIO Ultra HD Webcam             | 3        | 4.41%   |
| Sunplus FHD Camera Microphone             | 2        | 2.94%   |
| Razer USA Gaming Webcam [Kiyo]            | 2        | 2.94%   |
| Microsoft LifeCam HD-3000                 | 2        | 2.94%   |
| Logitech HD Webcam C510                   | 2        | 2.94%   |
| ARC International Camera                  | 2        | 2.94%   |
| YT-221117-J USB2.0 Camera                 | 1        | 1.47%   |
| WCM_USB WEB CAM                           | 1        | 1.47%   |
| Trust Widescreen 3MP Webcam               | 1        | 1.47%   |
| SunplusIT USB 2.0 Camera                  | 1        | 1.47%   |
| Sonix FHD Webcam                          | 1        | 1.47%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro      | 1        | 1.47%   |
| Microsoft LifeCam NX-6000                 | 1        | 1.47%   |
| Microsoft LifeCam HD-5000                 | 1        | 1.47%   |
| Microdia Sonix USB 2.0 Camera             | 1        | 1.47%   |
| Microdia Laptop_Integrated_Webcam_HD      | 1        | 1.47%   |
| Logitech Webcam Pro 9000                  | 1        | 1.47%   |
| Logitech Webcam C930e                     | 1        | 1.47%   |
| Logitech Webcam C300                      | 1        | 1.47%   |
| Logitech Webcam C250                      | 1        | 1.47%   |
| Logitech Webcam C210                      | 1        | 1.47%   |
| Logitech Webcam C200                      | 1        | 1.47%   |
| Logitech Webcam C170                      | 1        | 1.47%   |
| Logitech StreamCam                        | 1        | 1.47%   |
| Logitech QuickCam Pro 9000                | 1        | 1.47%   |
| Logitech QuickCam Communicate MP/S5500    | 1        | 1.47%   |
| Logitech HD Webcam C615                   | 1        | 1.47%   |
| Logitech C922 Pro Stream Webcam           | 1        | 1.47%   |
| Logitech Brio 500                         | 1        | 1.47%   |
| Lite-On HP Full-HD Camera                 | 1        | 1.47%   |
| KYE Systems (Mouse Systems) Genius Webcam | 1        | 1.47%   |
| Hauppauge HD PVR Pro 60                   | 1        | 1.47%   |
| Genesys Logic Digital Microscope          | 1        | 1.47%   |
| Generalplus CAMERA - UVC                  | 1        | 1.47%   |
| Fuzhou Rockchip Company P700              | 1        | 1.47%   |
| eMeet HD Webcam C960                      | 1        | 1.47%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 308      | 85.08%  |
| 1     | 48       | 13.26%  |
| 2     | 4        | 1.1%    |
| 6     | 1        | 0.28%   |
| 3     | 1        | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 18       | 31.58%  |
| Unassigned class         | 10       | 17.54%  |
| Net/wireless             | 10       | 17.54%  |
| Communication controller | 8        | 14.04%  |
| Sound                    | 4        | 7.02%   |
| Multimedia controller    | 2        | 3.51%   |
| Camera                   | 2        | 3.51%   |
| Bluetooth                | 2        | 3.51%   |
| Chipcard                 | 1        | 1.75%   |

