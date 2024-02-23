Parrot - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Parrot.

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

Total: 193

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B350-F GAMING     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| ASUSTek       | PRIME A320M-K               | [b7fff52e41](https://linux-hardware.org/?probe=b7fff52e41) | Jan 29, 2024 |
| ASRock        | Z77M                        | [f3bd1cdf2c](https://linux-hardware.org/?probe=f3bd1cdf2c) | Jan 19, 2024 |
| ASRock        | 970 Pro3 R2.0               | [ca8734dc63](https://linux-hardware.org/?probe=ca8734dc63) | Jan 11, 2024 |
| MSI           | B550 GAMING GEN3            | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [404320e4d7](https://linux-hardware.org/?probe=404320e4d7) | Dec 28, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [d90c13f9c6](https://linux-hardware.org/?probe=d90c13f9c6) | Dec 12, 2023 |
| Gateway       | TBGM01                      | [3ca4695541](https://linux-hardware.org/?probe=3ca4695541) | Nov 07, 2023 |
| Dell          | 0V8WGR A00                  | [9b13411bc8](https://linux-hardware.org/?probe=9b13411bc8) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [4ce8997d5a](https://linux-hardware.org/?probe=4ce8997d5a) | Nov 05, 2023 |
| ASUSTek       | Maximus VII HERO            | [3c959b9af8](https://linux-hardware.org/?probe=3c959b9af8) | Oct 25, 2023 |
| ASUSTek       | Maximus VII HERO            | [e3540cf969](https://linux-hardware.org/?probe=e3540cf969) | Oct 23, 2023 |
| ASUSTek       | M5A99X EVO                  | [a13621c5d3](https://linux-hardware.org/?probe=a13621c5d3) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | [144cbc70d0](https://linux-hardware.org/?probe=144cbc70d0) | Oct 03, 2023 |
| HP            | 8619                        | [d631850d2f](https://linux-hardware.org/?probe=d631850d2f) | Sep 28, 2023 |
| ASUSTek       | M5A99X EVO                  | [34e34036d7](https://linux-hardware.org/?probe=34e34036d7) | Sep 27, 2023 |
| HP            | 8714                        | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | [e10f21c5c5](https://linux-hardware.org/?probe=e10f21c5c5) | Sep 22, 2023 |
| ASUSTek       | M5A99X EVO                  | [648ac87a81](https://linux-hardware.org/?probe=648ac87a81) | Sep 21, 2023 |
| Shenzhen M... | F7BAA                       | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| Dell          | 0HD5W2 A01                  | [faf0bfe427](https://linux-hardware.org/?probe=faf0bfe427) | Sep 17, 2023 |
| Dell          | 0HD5W2 A01                  | [e59c5b4fda](https://linux-hardware.org/?probe=e59c5b4fda) | Sep 10, 2023 |
| ASUSTek       | Maximus V FORMULA           | [694ffed41f](https://linux-hardware.org/?probe=694ffed41f) | Sep 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | [039aa353eb](https://linux-hardware.org/?probe=039aa353eb) | Sep 06, 2023 |
| Pegatron      | 2A94h                       | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| MSI           | 3666h                       | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Dell          | 0100P6 A01                  | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b76b1bf00a](https://linux-hardware.org/?probe=b76b1bf00a) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [63665fca24](https://linux-hardware.org/?probe=63665fca24) | Aug 08, 2023 |
| MSI           | PRO H610M-B DDR4            | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| ASUSTek       | PRIME X570-P                | [48ec623298](https://linux-hardware.org/?probe=48ec623298) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| Dell          | 0RY007                      | [8317045335](https://linux-hardware.org/?probe=8317045335) | Aug 01, 2023 |
| MSI           | PRO Z790-P WIFI             | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| ASUSTek       | Maximus V FORMULA           | [190d408bc2](https://linux-hardware.org/?probe=190d408bc2) | Jun 23, 2023 |
| ASUSTek       | Maximus V FORMULA           | [fa49028492](https://linux-hardware.org/?probe=fa49028492) | Jun 23, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [11161fa30c](https://linux-hardware.org/?probe=11161fa30c) | Jun 18, 2023 |
| HP            | 339A                        | [d1fa07d03f](https://linux-hardware.org/?probe=d1fa07d03f) | Jun 10, 2023 |
| HP            | 339A                        | [f2147ed11b](https://linux-hardware.org/?probe=f2147ed11b) | Jun 05, 2023 |
| HP            | 1495                        | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| ASUSTek       | P8Z68-V                     | [59e64db8de](https://linux-hardware.org/?probe=59e64db8de) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [15b23b6779](https://linux-hardware.org/?probe=15b23b6779) | May 30, 2023 |
| Gigabyte      | H61M-HD2                    | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [d2ddb8221f](https://linux-hardware.org/?probe=d2ddb8221f) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| ASUSTek       | PRIME X399-A                | [b4861cf35c](https://linux-hardware.org/?probe=b4861cf35c) | Apr 23, 2023 |
| MSI           | Z97 GAMING 5                | [2f61bfa5a5](https://linux-hardware.org/?probe=2f61bfa5a5) | Apr 04, 2023 |
| MSI           | Z97 GAMING 5                | [1e81e330e1](https://linux-hardware.org/?probe=1e81e330e1) | Apr 04, 2023 |
| MSI           | 760GM-P33                   | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Gigabyte      | H61M-S2PV                   | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| ASRock        | B560M-C                     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Pegatron      | 2ACB                        | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Dell          | 0C1R19 A02                  | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| ASRock        | B560M-C                     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Biostar       | B450MH                      | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| Dell          | 0WMJ54 A01                  | [bfb29a2d13](https://linux-hardware.org/?probe=bfb29a2d13) | Feb 04, 2023 |
| ASRock        | Z87M Extreme4               | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| ASUSTek       | PRIME Z270-P                | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [6552c7b8b3](https://linux-hardware.org/?probe=6552c7b8b3) | Jan 22, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [64164ef7df](https://linux-hardware.org/?probe=64164ef7df) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [46befb7112](https://linux-hardware.org/?probe=46befb7112) | Jan 20, 2023 |
| HP            | 3397                        | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K               | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| ASUSTek       | Z170-DELUXE                 | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Dell          | 0C1R19 A02                  | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                      | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| Gigabyte      | Z97N-WIFI                   | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| ASUSTek       | P5G41T-M LX                 | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2                   | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| ASUSTek       | P6X58D-E                    | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                    | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Gigabyte      | H61M-S2PT                   | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Gateway       | SX2855                      | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| ASUSTek       | H110M-K                     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| ASUSTek       | H110M-K                     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| ASUSTek       | H110M-K                     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| Gigabyte      | H61M-USB3H                  | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Unknown       | TB-4000                     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Lenovo        | 31900058 STD                | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| MSI           | G31M3-L V2                  | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| HP            | 1495                        | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Unknown       | TB-4000                     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | B350 TOMAHAWK               | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| ECS           | Nettle2                     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASUSTek       | F2A85-M                     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| MSI           | G31M3-L V2                  | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Unknown       | TB-4000                     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Unknown       | TB-4000                     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| ASUSTek       | Benicia                     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| Unknown       | TB-4000                     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Unknown       | Unknown                     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| ASUSTek       | M5A99X EVO                  | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Alienware     | 0PGRP5 A02                  | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Acer          | Aspire TC-780               | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Dell          | 0T2HR0 A00                  | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| ZOTAC         | Unknown                     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| HP            | 1850                        | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | 0T10XW A02                  | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| HP            | 1850                        | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| Dell          | 0C1R19 A02                  | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| ASUSTek       | PRIME X399-A                | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Predator PO3-600 V:1.1      | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| HP            | 339A                        | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| MSI           | B250M MORTAR                | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| Acer          | Aspire X3990                | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Medion        | MS-7621                     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| HP            | 3047h                       | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | Maximus VIII HERO           | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ECS           | A740GM-M                    | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Gigabyte      | H370M DS3H-CF               | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Apple         | Mac-F221BEC8                | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Biostar       | H77MU3                      | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| Dell          | 0VYXHD A00                  | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| Dell          | 05DN3X A00                  | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| ASUSTek       | A68HM-PLUS                  | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Foxconn       | 2A8C                        | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| ASUSTek       | K31CD-K                     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Dell          | 0CU409                      | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| ASRock        | FM2A68M-DG3+                | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Foxconn       | 2A8C                        | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Parrot 5.3  | 31       | 22.63%  |
| Parrot 5.0  | 27       | 19.71%  |
| Parrot 4.11 | 23       | 16.79%  |
| Parrot 4.10 | 14       | 10.22%  |
| Parrot 5.1  | 13       | 9.49%   |
| Parrot 4.9  | 9        | 6.57%   |
| Parrot 5.2  | 8        | 5.84%   |
| Parrot 4.8  | 6        | 4.38%   |
| Parrot 6.0  | 3        | 2.19%   |
| Parrot 4.7  | 3        | 2.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Parrot | 131      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 6.1.0-1parrot1-amd64     | 31       | 22.14%  |
| 5.16.0-12parrot1-amd64   | 14       | 10%     |
| 5.14.0-9parrot1-amd64    | 14       | 10%     |
| 6.0.0-12parrot1-amd64    | 13       | 9.29%   |
| 5.5.0-1parrot1-amd64     | 12       | 8.57%   |
| 6.0.0-2parrot1-amd64     | 8        | 5.71%   |
| 5.7.0-2parrot2-amd64     | 6        | 4.29%   |
| 5.15.0-15parrot1-amd64   | 6        | 4.29%   |
| 5.10.0-6parrot1-amd64    | 6        | 4.29%   |
| 5.8.0-2parrot1-amd64     | 3        | 2.14%   |
| 5.4.0-4parrot1-amd64     | 3        | 2.14%   |
| 5.10.0-8parrot1-amd64    | 3        | 2.14%   |
| 5.9.0-2parrot1-amd64     | 2        | 1.43%   |
| 5.4.0-2parrot1-amd64     | 2        | 1.43%   |
| 5.3.0-3parrot3-amd64     | 2        | 1.43%   |
| 5.18.0-1parrot1-amd64    | 2        | 1.43%   |
| 5.18.0-14parrot1-amd64   | 2        | 1.43%   |
| 5.14.0-2parrot1-amd64    | 2        | 1.43%   |
| 5.10.0-3parrot1-amd64    | 2        | 1.43%   |
| 6.5.0-kali3-amd64        | 1        | 0.71%   |
| 6.5.0-13parrot1-amd64    | 1        | 0.71%   |
| 5.8.0-1parrot1-amd64     | 1        | 0.71%   |
| 5.6.0-2parrot1-amd64     | 1        | 0.71%   |
| 5.4.0-3parrot1-amd64     | 1        | 0.71%   |
| 5.16.0-12parrot1-686-pae | 1        | 0.71%   |
| 5.10.0-5parrot1-amd64    | 1        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1.0   | 31       | 22.46%  |
| 6.0.0   | 20       | 14.49%  |
| 5.16.0  | 15       | 10.87%  |
| 5.14.0  | 15       | 10.87%  |
| 5.5.0   | 12       | 8.7%    |
| 5.10.0  | 12       | 8.7%    |
| 5.7.0   | 6        | 4.35%   |
| 5.4.0   | 6        | 4.35%   |
| 5.15.0  | 6        | 4.35%   |
| 5.8.0   | 4        | 2.9%    |
| 5.18.0  | 4        | 2.9%    |
| 6.5.0   | 2        | 1.45%   |
| 5.9.0   | 2        | 1.45%   |
| 5.3.0   | 2        | 1.45%   |
| 5.6.0   | 1        | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 31       | 22.46%  |
| 6.0     | 20       | 14.49%  |
| 5.16    | 15       | 10.87%  |
| 5.14    | 15       | 10.87%  |
| 5.5     | 12       | 8.7%    |
| 5.10    | 12       | 8.7%    |
| 5.7     | 6        | 4.35%   |
| 5.4     | 6        | 4.35%   |
| 5.15    | 6        | 4.35%   |
| 5.8     | 4        | 2.9%    |
| 5.18    | 4        | 2.9%    |
| 6.5     | 2        | 1.45%   |
| 5.9     | 2        | 1.45%   |
| 5.3     | 2        | 1.45%   |
| 5.6     | 1        | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 130      | 99.24%  |
| i686   | 1        | 0.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| MATE            | 100      | 72.99%  |
| KDE5            | 13       | 9.49%   |
| XFCE            | 7        | 5.11%   |
| KDE             | 7        | 5.11%   |
| GNOME           | 4        | 2.92%   |
| Unknown         | 4        | 2.92%   |
| GNOME Flashback | 1        | 0.73%   |
| bspwm           | 1        | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 126      | 96.18%  |
| Wayland | 3        | 2.29%   |
| Tty     | 1        | 0.76%   |
| Unknown | 1        | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 64       | 47.06%  |
| Unknown | 45       | 33.09%  |
| TDM     | 18       | 13.24%  |
| SDDM    | 6        | 4.41%   |
| GDM     | 3        | 2.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 73       | 55.3%   |
| es_ES | 6        | 4.55%   |
| ru_RU | 5        | 3.79%   |
| en_IN | 5        | 3.79%   |
| de_DE | 5        | 3.79%   |
| pt_BR | 4        | 3.03%   |
| fr_FR | 4        | 3.03%   |
| en_AU | 4        | 3.03%   |
| pl_PL | 3        | 2.27%   |
| en_GB | 3        | 2.27%   |
| it_IT | 2        | 1.52%   |
| es_MX | 2        | 1.52%   |
| en_HK | 2        | 1.52%   |
| cs_CZ | 2        | 1.52%   |
| ru_UA | 1        | 0.76%   |
| mk_MK | 1        | 0.76%   |
| id_ID | 1        | 0.76%   |
| es_CO | 1        | 0.76%   |
| en_ZA | 1        | 0.76%   |
| en_NZ | 1        | 0.76%   |
| en_IE | 1        | 0.76%   |
| en_DK | 1        | 0.76%   |
| en_CA | 1        | 0.76%   |
| de_AT | 1        | 0.76%   |
| C     | 1        | 0.76%   |
| an_ES | 1        | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 99       | 73.88%  |
| EFI  | 35       | 26.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 101      | 75.94%  |
| Ext4    | 18       | 13.53%  |
| Tmpfs   | 5        | 3.76%   |
| Overlay | 5        | 3.76%   |
| Xfs     | 4        | 3.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 61       | 44.85%  |
| GPT     | 48       | 35.29%  |
| MBR     | 27       | 19.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 80.6%   |
| Yes       | 26       | 19.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 57.58%  |
| Yes       | 56       | 42.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 40       | 30.53%  |
| Gigabyte Technology                  | 19       | 14.5%   |
| Dell                                 | 15       | 11.45%  |
| MSI                                  | 14       | 10.69%  |
| Hewlett-Packard                      | 12       | 9.16%   |
| ASRock                               | 6        | 4.58%   |
| Foxconn                              | 3        | 2.29%   |
| Acer                                 | 3        | 2.29%   |
| Pegatron                             | 2        | 1.53%   |
| Lenovo                               | 2        | 1.53%   |
| Gateway                              | 2        | 1.53%   |
| ECS                                  | 2        | 1.53%   |
| Biostar                              | 2        | 1.53%   |
| Unknown                              | 2        | 1.53%   |
| ZOTAC                                | 1        | 0.76%   |
| Wistron                              | 1        | 0.76%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.76%   |
| Positivo                             | 1        | 0.76%   |
| Daewoo Lucoms                        | 1        | 0.76%   |
| Apple                                | 1        | 0.76%   |
| Alienware                            | 1        | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS M5A78L-M/USB3                         | 3        | 2.29%   |
| Unknown                                    | 3        | 2.29%   |
| HP ProDesk 600 G1 SFF                      | 2        | 1.53%   |
| HP Compaq 8200 Elite SFF PC                | 2        | 1.53%   |
| Gigabyte AX370-Gaming                      | 2        | 1.53%   |
| Foxconn s5710t                             | 2        | 1.53%   |
| Dell OptiPlex 7010                         | 2        | 1.53%   |
| Dell OptiPlex 3020                         | 2        | 1.53%   |
| Dell Inspiron 5676                         | 2        | 1.53%   |
| ASUS PRIME X399-A                          | 2        | 1.53%   |
| ASUS M5A99X EVO                            | 2        | 1.53%   |
| ASUS H110I-PLUS                            | 2        | 1.53%   |
| ASUS Basic 3221BM                          | 2        | 1.53%   |
| Wistron FMVDD2A0H0                         | 1        | 0.76%   |
| Shenzhen Meigao Electronic Equipment HX99G | 1        | 0.76%   |
| Positivo POS-PIG43BC                       | 1        | 0.76%   |
| Pegatron Pro 3010 Microtower PC            | 1        | 0.76%   |
| Pegatron 520-1030a                         | 1        | 0.76%   |
| MSI Pro 2000/2080                          | 1        | 0.76%   |
| MSI MS-7E06                                | 1        | 0.76%   |
| MSI MS-7D46                                | 1        | 0.76%   |
| MSI MS-7D32                                | 1        | 0.76%   |
| MSI MS-7C91                                | 1        | 0.76%   |
| MSI MS-7C79                                | 1        | 0.76%   |
| MSI MS-7C02                                | 1        | 0.76%   |
| MSI MS-7B86                                | 1        | 0.76%   |
| MSI MS-7B85                                | 1        | 0.76%   |
| MSI MS-7A69                                | 1        | 0.76%   |
| MSI MS-7A34                                | 1        | 0.76%   |
| MSI MS-7917                                | 1        | 0.76%   |
| MSI MS-7623                                | 1        | 0.76%   |
| MSI MS-7529                                | 1        | 0.76%   |
| Lenovo H535 10117                          | 1        | 0.76%   |
| Lenovo H530 10130                          | 1        | 0.76%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx  | 1        | 0.76%   |
| HP ProDesk 600 G6 Small Form Factor PC     | 1        | 0.76%   |
| HP EliteDesk 705 G5 Desktop Mini           | 1        | 0.76%   |
| HP Compaq Pro 6305 MT                      | 1        | 0.76%   |
| HP Compaq Pro 6300 SFF                     | 1        | 0.76%   |
| HP Compaq Pro 6300 MT                      | 1        | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 9        | 6.87%   |
| ASUS PRIME                                 | 8        | 6.11%   |
| HP Compaq                                  | 7        | 5.34%   |
| ASUS ROG                                   | 4        | 3.05%   |
| HP ProDesk                                 | 3        | 2.29%   |
| Dell Inspiron                              | 3        | 2.29%   |
| ASUS M5A78L-M                              | 3        | 2.29%   |
| Unknown                                    | 3        | 2.29%   |
| Gigabyte AX370-Gaming                      | 2        | 1.53%   |
| Foxconn s5710t                             | 2        | 1.53%   |
| ASUS Maximus                               | 2        | 1.53%   |
| ASUS M5A99X                                | 2        | 1.53%   |
| ASUS H110I-PLUS                            | 2        | 1.53%   |
| ASUS Basic                                 | 2        | 1.53%   |
| Acer Aspire                                | 2        | 1.53%   |
| Wistron FMVDD2A0H0                         | 1        | 0.76%   |
| Shenzhen Meigao Electronic Equipment HX99G | 1        | 0.76%   |
| Positivo POS-PIG43BC                       | 1        | 0.76%   |
| Pegatron Pro                               | 1        | 0.76%   |
| Pegatron 520-1030a                         | 1        | 0.76%   |
| MSI Pro                                    | 1        | 0.76%   |
| MSI MS-7E06                                | 1        | 0.76%   |
| MSI MS-7D46                                | 1        | 0.76%   |
| MSI MS-7D32                                | 1        | 0.76%   |
| MSI MS-7C91                                | 1        | 0.76%   |
| MSI MS-7C79                                | 1        | 0.76%   |
| MSI MS-7C02                                | 1        | 0.76%   |
| MSI MS-7B86                                | 1        | 0.76%   |
| MSI MS-7B85                                | 1        | 0.76%   |
| MSI MS-7A69                                | 1        | 0.76%   |
| MSI MS-7A34                                | 1        | 0.76%   |
| MSI MS-7917                                | 1        | 0.76%   |
| MSI MS-7623                                | 1        | 0.76%   |
| MSI MS-7529                                | 1        | 0.76%   |
| Lenovo H535                                | 1        | 0.76%   |
| Lenovo H530                                | 1        | 0.76%   |
| HP Victus                                  | 1        | 0.76%   |
| HP EliteDesk                               | 1        | 0.76%   |
| Gigabyte Z97X-UD3H                         | 1        | 0.76%   |
| Gigabyte Z97N-WIFI                         | 1        | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 15       | 11.45%  |
| 2011 | 15       | 11.45%  |
| 2013 | 12       | 9.16%   |
| 2018 | 11       | 8.4%    |
| 2021 | 9        | 6.87%   |
| 2017 | 9        | 6.87%   |
| 2016 | 9        | 6.87%   |
| 2010 | 9        | 6.87%   |
| 2015 | 7        | 5.34%   |
| 2020 | 6        | 4.58%   |
| 2014 | 6        | 4.58%   |
| 2007 | 6        | 4.58%   |
| 2019 | 5        | 3.82%   |
| 2009 | 5        | 3.82%   |
| 2022 | 3        | 2.29%   |
| 2023 | 2        | 1.53%   |
| 2008 | 2        | 1.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 131      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 131      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 131      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 38       | 28.15%  |
| 8.01-16.0   | 27       | 20%     |
| 4.01-8.0    | 24       | 17.78%  |
| 32.01-64.0  | 23       | 17.04%  |
| 3.01-4.0    | 16       | 11.85%  |
| 1.01-2.0    | 3        | 2.22%   |
| 24.01-32.0  | 2        | 1.48%   |
| 64.01-256.0 | 2        | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 45       | 32.61%  |
| 1.01-2.0   | 36       | 26.09%  |
| 4.01-8.0   | 22       | 15.94%  |
| 3.01-4.0   | 22       | 15.94%  |
| 0.51-1.0   | 7        | 5.07%   |
| 8.01-16.0  | 4        | 2.9%    |
| 16.01-24.0 | 1        | 0.72%   |
| 0.01-0.5   | 1        | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 36.96%  |
| 1      | 47       | 34.06%  |
| 3      | 18       | 13.04%  |
| 4      | 13       | 9.42%   |
| 5      | 6        | 4.35%   |
| 6      | 2        | 1.45%   |
| 0      | 1        | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 67.65%  |
| Yes       | 44       | 32.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 129      | 98.47%  |
| No        | 2        | 1.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 87       | 64.93%  |
| No        | 47       | 35.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 68.94%  |
| Yes       | 41       | 31.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 47       | 35.34%  |
| Germany         | 10       | 7.52%   |
| Brazil          | 7        | 5.26%   |
| Spain           | 6        | 4.51%   |
| India           | 6        | 4.51%   |
| Russia          | 4        | 3.01%   |
| Netherlands     | 4        | 3.01%   |
| Mexico          | 3        | 2.26%   |
| Italy           | 3        | 2.26%   |
| France          | 3        | 2.26%   |
| Canada          | 3        | 2.26%   |
| Australia       | 3        | 2.26%   |
| UK              | 2        | 1.5%    |
| Poland          | 2        | 1.5%    |
| Japan           | 2        | 1.5%    |
| Hong Kong       | 2        | 1.5%    |
| Czechia         | 2        | 1.5%    |
| Austria         | 2        | 1.5%    |
| Algeria         | 2        | 1.5%    |
| Vietnam         | 1        | 0.75%   |
| Ukraine         | 1        | 0.75%   |
| Turkey          | 1        | 0.75%   |
| Sweden          | 1        | 0.75%   |
| South Africa    | 1        | 0.75%   |
| Romania         | 1        | 0.75%   |
| Philippines     | 1        | 0.75%   |
| Peru            | 1        | 0.75%   |
| Pakistan        | 1        | 0.75%   |
| North Macedonia | 1        | 0.75%   |
| New Zealand     | 1        | 0.75%   |
| Morocco         | 1        | 0.75%   |
| Mongolia        | 1        | 0.75%   |
| Ireland         | 1        | 0.75%   |
| Indonesia       | 1        | 0.75%   |
| Egypt           | 1        | 0.75%   |
| Denmark         | 1        | 0.75%   |
| Colombia        | 1        | 0.75%   |
| Bulgaria        | 1        | 0.75%   |
| Belgium         | 1        | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Indianapolis           | 3        | 2.21%   |
| Vienna                 | 2        | 1.47%   |
| Uherské Hradiště    | 2        | 1.47%   |
| Tokyo                  | 2        | 1.47%   |
| Ngau Wu Tok            | 2        | 1.47%   |
| Newburgh               | 2        | 1.47%   |
| Morelia                | 2        | 1.47%   |
| Madrid                 | 2        | 1.47%   |
| Los Angeles            | 2        | 1.47%   |
| Eugene                 | 2        | 1.47%   |
| Atlanta                | 2        | 1.47%   |
| Wichita                | 1        | 0.74%   |
| Wellington             | 1        | 0.74%   |
| Warsaw                 | 1        | 0.74%   |
| Viby J                 | 1        | 0.74%   |
| Velbert                | 1        | 0.74%   |
| Vapi                   | 1        | 0.74%   |
| Vancouver              | 1        | 0.74%   |
| Valencia               | 1        | 0.74%   |
| Ulan Bator             | 1        | 0.74%   |
| Terrace                | 1        | 0.74%   |
| Tangier                | 1        | 0.74%   |
| Sydney                 | 1        | 0.74%   |
| Stockton               | 1        | 0.74%   |
| St Louis               | 1        | 0.74%   |
| Springfield            | 1        | 0.74%   |
| Spring                 | 1        | 0.74%   |
| Sorocaba               | 1        | 0.74%   |
| Sofia                  | 1        | 0.74%   |
| Skopje                 | 1        | 0.74%   |
| Skikda                 | 1        | 0.74%   |
| Sao Paulo              | 1        | 0.74%   |
| Sao Joao de Meriti     | 1        | 0.74%   |
| Santa Rita do Sapucai  | 1        | 0.74%   |
| Santa Maria            | 1        | 0.74%   |
| San Francisco          | 1        | 0.74%   |
| Saint-Denis            | 1        | 0.74%   |
| Saint Paul             | 1        | 0.74%   |
| Rubí                  | 1        | 0.74%   |
| Rieschweiler-Muehlbach | 1        | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 54       | 78     | 22.31%  |
| WDC                         | 48       | 67     | 19.83%  |
| Samsung Electronics         | 26       | 40     | 10.74%  |
| Toshiba                     | 20       | 21     | 8.26%   |
| Kingston                    | 13       | 16     | 5.37%   |
| SanDisk                     | 11       | 16     | 4.55%   |
| Hitachi                     | 11       | 15     | 4.55%   |
| Crucial                     | 6        | 6      | 2.48%   |
| SPCC                        | 4        | 4      | 1.65%   |
| A-DATA Technology           | 4        | 4      | 1.65%   |
| Unknown                     | 3        | 3      | 1.24%   |
| SK hynix                    | 3        | 5      | 1.24%   |
| Silicon Motion              | 3        | 3      | 1.24%   |
| JMicron Technology          | 3        | 3      | 1.24%   |
| HGST                        | 3        | 3      | 1.24%   |
| Team                        | 2        | 3      | 0.83%   |
| Phison                      | 2        | 2      | 0.83%   |
| Micron Technology           | 2        | 2      | 0.83%   |
| LITEONIT                    | 2        | 2      | 0.83%   |
| Intenso                     | 2        | 2      | 0.83%   |
| Fujitsu                     | 2        | 2      | 0.83%   |
| China                       | 2        | 5      | 0.83%   |
| WALRAM                      | 1        | 1      | 0.41%   |
| PNY USB                     | 1        | 1      | 0.41%   |
| PNY                         | 1        | 1      | 0.41%   |
| Plextor                     | 1        | 1      | 0.41%   |
| OCZ                         | 1        | 1      | 0.41%   |
| Micron/Crucial Technology   | 1        | 2      | 0.41%   |
| Kingston Technology Company | 1        | 1      | 0.41%   |
| Intel                       | 1        | 1      | 0.41%   |
| GOODRAM                     | 1        | 1      | 0.41%   |
| FORESEE                     | 1        | 1      | 0.41%   |
| Fanxiang                    | 1        | 1      | 0.41%   |
| Corsair                     | 1        | 1      | 0.41%   |
| CLOVER                      | 1        | 1      | 0.41%   |
| Apple                       | 1        | 1      | 0.41%   |
| Apacer                      | 1        | 1      | 0.41%   |
| AMD                         | 1        | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA200 2TB             | 6        | 2.12%   |
| Seagate Expansion 1TB              | 5        | 1.77%   |
| Kingston SA400S37480G 480GB SSD    | 5        | 1.77%   |
| Seagate ST31000528AS 1TB           | 4        | 1.41%   |
| Samsung SSD 860 EVO 500GB          | 4        | 1.41%   |
| WDC WD5000AADS-00S9B0 500GB        | 3        | 1.06%   |
| Toshiba DT01ACA100 1TB             | 3        | 1.06%   |
| Toshiba DT01ACA050 500GB           | 3        | 1.06%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB     | 3        | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB     | 3        | 1.06%   |
| Samsung SSD 860 EVO 250GB          | 3        | 1.06%   |
| Kingston SA400S37240G 240GB SSD    | 3        | 1.06%   |
| JMicron Generic 8GB                | 3        | 1.06%   |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 2        | 0.71%   |
| WDC WD2500JS-75MHB0 250GB          | 2        | 0.71%   |
| WDC WD2500AAKX-753CA1 250GB        | 2        | 0.71%   |
| WDC WD10EZRX-00L4HB0 1TB           | 2        | 0.71%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 0.71%   |
| WDC WD10EARS-00Y5B1 1TB            | 2        | 0.71%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 2        | 0.71%   |
| Unknown SD/MMC/MS PRO 256GB        | 2        | 0.71%   |
| Seagate ST500VT000-1DK142 500GB    | 2        | 0.71%   |
| Seagate ST500LM000-SSHD-8GB        | 2        | 0.71%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2        | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 0.71%   |
| Seagate BUP Slim SL 2TB            | 2        | 0.71%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 2        | 0.71%   |
| SanDisk NVMe SSD Drive 2TB         | 2        | 0.71%   |
| Samsung SSD 980 1TB                | 2        | 0.71%   |
| Samsung SSD 850 EVO 250GB          | 2        | 0.71%   |
| Samsung SSD 840 Series 250GB       | 2        | 0.71%   |
| Samsung HD161HJ 160GB              | 2        | 0.71%   |
| Hitachi HUA722020ALA331 2TB        | 2        | 0.71%   |
| Fujitsu F300 480GB                 | 2        | 0.71%   |
| A-DATA SU635 240GB SSD             | 2        | 0.71%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 54       | 78     | 38.3%   |
| WDC                 | 39       | 57     | 27.66%  |
| Toshiba             | 20       | 21     | 14.18%  |
| Hitachi             | 11       | 15     | 7.8%    |
| Samsung Electronics | 7        | 9      | 4.96%   |
| JMicron Technology  | 3        | 3      | 2.13%   |
| HGST                | 3        | 3      | 2.13%   |
| Unknown             | 2        | 2      | 1.42%   |
| CLOVER              | 1        | 1      | 0.71%   |
| Apple               | 1        | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 23     | 18.31%  |
| Kingston            | 11       | 13     | 15.49%  |
| WDC                 | 7        | 7      | 9.86%   |
| SanDisk             | 6        | 7      | 8.45%   |
| Crucial             | 5        | 5      | 7.04%   |
| SPCC                | 3        | 3      | 4.23%   |
| A-DATA Technology   | 3        | 3      | 4.23%   |
| Team                | 2        | 3      | 2.82%   |
| LITEONIT            | 2        | 2      | 2.82%   |
| Intenso             | 2        | 2      | 2.82%   |
| Fujitsu             | 2        | 2      | 2.82%   |
| China               | 2        | 5      | 2.82%   |
| WALRAM              | 1        | 1      | 1.41%   |
| Unknown             | 1        | 1      | 1.41%   |
| PNY USB             | 1        | 1      | 1.41%   |
| PNY                 | 1        | 1      | 1.41%   |
| Plextor             | 1        | 1      | 1.41%   |
| OCZ                 | 1        | 1      | 1.41%   |
| Micron Technology   | 1        | 1      | 1.41%   |
| GOODRAM             | 1        | 1      | 1.41%   |
| FORESEE             | 1        | 1      | 1.41%   |
| Fanxiang            | 1        | 1      | 1.41%   |
| Corsair             | 1        | 1      | 1.41%   |
| Apacer              | 1        | 1      | 1.41%   |
| AMD                 | 1        | 1      | 1.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 102      | 190    | 53.13%  |
| SSD  | 61       | 88     | 31.77%  |
| NVMe | 29       | 41     | 15.1%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 114      | 264    | 73.08%  |
| NVMe | 29       | 41     | 18.59%  |
| SAS  | 13       | 14     | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 89       | 164    | 49.72%  |
| 0.51-1.0   | 56       | 73     | 31.28%  |
| 1.01-2.0   | 23       | 27     | 12.85%  |
| 3.01-4.0   | 5        | 6      | 2.79%   |
| 2.01-3.0   | 4        | 6      | 2.23%   |
| 4.01-10.0  | 2        | 2      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 31       | 22.14%  |
| 501-1000       | 26       | 18.57%  |
| 101-250        | 23       | 16.43%  |
| 1001-2000      | 23       | 16.43%  |
| Unknown        | 10       | 7.14%   |
| More than 3000 | 8        | 5.71%   |
| 51-100         | 8        | 5.71%   |
| 2001-3000      | 5        | 3.57%   |
| 21-50          | 3        | 2.14%   |
| 1-20           | 3        | 2.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 37       | 26.06%  |
| 101-250        | 29       | 20.42%  |
| 1-20           | 21       | 14.79%  |
| 51-100         | 20       | 14.08%  |
| Unknown        | 10       | 7.04%   |
| 251-500        | 9        | 6.34%   |
| 501-1000       | 9        | 6.34%   |
| 1001-2000      | 5        | 3.52%   |
| More than 3000 | 2        | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| SanDisk SD6SF1M128G1022I 128GB SSD           | 2        | 3      | 5.13%   |
| WDC WD5000AAKS-75V0A0 500GB                  | 1        | 1      | 2.56%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 2.56%   |
| WDC WD3200AVJS-63B6A0 320GB                  | 1        | 1      | 2.56%   |
| WDC WD2003FZEX-00Z4SA0 2TB                   | 1        | 1      | 2.56%   |
| WDC WD10JUCX-63WPNY0 1TB                     | 1        | 1      | 2.56%   |
| WDC WD10EZRX-00L4HB0 1TB                     | 1        | 1      | 2.56%   |
| WDC WD10EADS-22M2B0 1TB                      | 1        | 1      | 2.56%   |
| Toshiba DT01ACA050 500GB                     | 1        | 1      | 2.56%   |
| SPCC M.2 PCIe SSD 256GB                      | 1        | 1      | 2.56%   |
| Seagate ST9500325AS 500GB                    | 1        | 1      | 2.56%   |
| Seagate ST940210AS 40GB                      | 1        | 1      | 2.56%   |
| Seagate ST9250410AS 250GB                    | 1        | 1      | 2.56%   |
| Seagate ST500NM0011 500GB                    | 1        | 1      | 2.56%   |
| Seagate ST380215AS 80GB                      | 1        | 1      | 2.56%   |
| Seagate ST3802110A 80GB                      | 1        | 1      | 2.56%   |
| Seagate ST3500413AS 500GB                    | 1        | 1      | 2.56%   |
| Seagate ST3320418AS 320GB                    | 1        | 1      | 2.56%   |
| Seagate ST3250824AS 250GB                    | 1        | 1      | 2.56%   |
| Seagate ST320LT007-9ZV142 320GB              | 1        | 1      | 2.56%   |
| Seagate ST3160215AS 160GB                    | 1        | 1      | 2.56%   |
| Seagate ST31000528AS 1TB                     | 1        | 1      | 2.56%   |
| Seagate ST250DM000-1BD141 250GB              | 1        | 1      | 2.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1        | 2      | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB               | 1        | 1      | 2.56%   |
| SanDisk SSD PLUS 480GB                       | 1        | 1      | 2.56%   |
| SanDisk SSD PLUS 1000GB                      | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 1        | 2      | 2.56%   |
| Samsung Electronics HM500JI 500GB            | 1        | 1      | 2.56%   |
| Samsung Electronics HD642JJ 640GB            | 1        | 1      | 2.56%   |
| Samsung Electronics HD161HJ 160GB            | 1        | 1      | 2.56%   |
| Samsung Electronics HD154UI 1TB              | 1        | 1      | 2.56%   |
| Plextor PX-512M6Pro 512GB SSD                | 1        | 1      | 2.56%   |
| Intenso SSD Sata III 256GB                   | 1        | 1      | 2.56%   |
| Hitachi HUA722020ALA331 2TB                  | 1        | 1      | 2.56%   |
| Hitachi HDT722525DLA380 41N3150LEN 250GB     | 1        | 1      | 2.56%   |
| CLOVER CM161GI 160GB                         | 1        | 1      | 2.56%   |
| A-DATA Technology SX7000NP 128GB             | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 33.33%  |
| WDC                 | 7        | 7      | 19.44%  |
| Samsung Electronics | 5        | 6      | 13.89%  |
| SanDisk             | 4        | 5      | 11.11%  |
| Hitachi             | 2        | 2      | 5.56%   |
| Toshiba             | 1        | 1      | 2.78%   |
| SPCC                | 1        | 1      | 2.78%   |
| Plextor             | 1        | 1      | 2.78%   |
| Intenso             | 1        | 1      | 2.78%   |
| CLOVER              | 1        | 1      | 2.78%   |
| A-DATA Technology   | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 16     | 44.44%  |
| WDC                 | 7        | 7      | 25.93%  |
| Samsung Electronics | 4        | 4      | 14.81%  |
| Hitachi             | 2        | 2      | 7.41%   |
| Toshiba             | 1        | 1      | 3.7%    |
| CLOVER              | 1        | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 31     | 70%     |
| SSD  | 7        | 9      | 23.33%  |
| NVMe | 2        | 2      | 6.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1        | 1      | 50%     |
| Intenso SSD SATAIII 1024GB  | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Intenso | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 76       | 172    | 46.06%  |
| Works    | 61       | 103    | 36.97%  |
| Malfunc  | 26       | 42     | 15.76%  |
| Failed   | 2        | 2      | 1.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 81       | 47.37%  |
| AMD                         | 45       | 26.32%  |
| SanDisk                     | 8        | 4.68%   |
| Samsung Electronics         | 7        | 4.09%   |
| ASMedia Technology          | 6        | 3.51%   |
| JMicron Technology          | 4        | 2.34%   |
| SK hynix                    | 3        | 1.75%   |
| Silicon Motion              | 3        | 1.75%   |
| Nvidia                      | 3        | 1.75%   |
| Kingston Technology Company | 3        | 1.75%   |
| Phison Electronics          | 2        | 1.17%   |
| Micron/Crucial Technology   | 2        | 1.17%   |
| VIA Technologies            | 1        | 0.58%   |
| Realtek Semiconductor       | 1        | 0.58%   |
| Micron Technology           | 1        | 0.58%   |
| Marvell Technology Group    | 1        | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 11.82%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 4.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 9        | 4.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 3.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 3.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 3.18%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 2.73%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 6        | 2.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 2.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.82%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 4        | 1.82%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 1.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 1.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3        | 1.36%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.36%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.36%   |
| JMicron JMB362 SATA Controller                                                          | 3        | 1.36%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 1.36%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 2        | 0.91%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.91%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 0.91%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 0.91%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 0.91%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.91%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.91%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.45%   |
| SK hynix PC601 NVMe Solid State Drive                                                   | 1        | 0.45%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                       | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 103      | 60.23%  |
| IDE  | 31       | 18.13%  |
| NVMe | 29       | 16.96%  |
| RAID | 8        | 4.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 82       | 62.6%   |
| AMD    | 49       | 37.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-8350 Eight-Core Processor            | 4        | 3.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.29%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 2.29%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 2.29%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 3        | 2.29%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.29%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 3        | 2.29%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 2        | 1.53%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 1.53%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 2        | 1.53%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 1.53%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.53%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 1.53%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.53%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.53%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.53%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.53%   |
| Intel 12th Gen Core i7-12700F               | 2        | 1.53%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 1.53%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 1.53%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.53%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.53%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.53%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.76%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.76%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.76%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.76%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.76%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.76%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.76%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.76%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.76%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 0.76%   |
| Intel Core i9-10900F CPU @ 2.80GHz          | 1        | 0.76%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 0.76%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 0.76%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.76%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 22       | 16.79%  |
| Intel Core i7           | 19       | 14.5%   |
| AMD Ryzen 5             | 12       | 9.16%   |
| Intel Core i3           | 11       | 8.4%    |
| Other                   | 9        | 6.87%   |
| AMD Ryzen 7             | 7        | 5.34%   |
| AMD FX                  | 7        | 5.34%   |
| Intel Xeon              | 5        | 3.82%   |
| Intel Pentium Dual-Core | 5        | 3.82%   |
| Intel Pentium           | 4        | 3.05%   |
| Intel Core 2 Duo        | 4        | 3.05%   |
| AMD Ryzen 9             | 3        | 2.29%   |
| AMD Ryzen Threadripper  | 2        | 1.53%   |
| AMD Ryzen 3             | 2        | 1.53%   |
| AMD Phenom II X4        | 2        | 1.53%   |
| AMD Athlon II X2        | 2        | 1.53%   |
| AMD A8                  | 2        | 1.53%   |
| AMD A10                 | 2        | 1.53%   |
| Intel Pentium Dual      | 1        | 0.76%   |
| Intel Core M            | 1        | 0.76%   |
| Intel Core i9           | 1        | 0.76%   |
| Intel Core 2 Quad       | 1        | 0.76%   |
| AMD Sempron             | 1        | 0.76%   |
| AMD Ryzen 5 PRO         | 1        | 0.76%   |
| AMD Phenom              | 1        | 0.76%   |
| AMD Athlon 64 X2        | 1        | 0.76%   |
| AMD Athlon 64           | 1        | 0.76%   |
| AMD A6                  | 1        | 0.76%   |
| AMD A4                  | 1        | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 56       | 42.75%  |
| 2      | 33       | 25.19%  |
| 6      | 14       | 10.69%  |
| 8      | 11       | 8.4%    |
| 12     | 6        | 4.58%   |
| 3      | 3        | 2.29%   |
| 1      | 3        | 2.29%   |
| 16     | 2        | 1.53%   |
| 10     | 2        | 1.53%   |
| 24     | 1        | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 130      | 99.24%  |
| 2      | 1        | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 71       | 54.2%   |
| 1      | 60       | 45.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 131      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 54.81%  |
| 0x206a7    | 6        | 4.44%   |
| 0x906e9    | 5        | 3.7%    |
| 0x306c3    | 5        | 3.7%    |
| 0x306a9    | 4        | 2.96%   |
| 0x08108109 | 4        | 2.96%   |
| 0x06000852 | 4        | 2.96%   |
| 0x90672    | 3        | 2.22%   |
| 0x1067a    | 3        | 2.22%   |
| 0x010000c8 | 3        | 2.22%   |
| 0xb0671    | 2        | 1.48%   |
| 0x0a50000c | 2        | 1.48%   |
| 0x0a20120a | 2        | 1.48%   |
| 0x08701021 | 2        | 1.48%   |
| 0x08001138 | 2        | 1.48%   |
| 0xa0671    | 1        | 0.74%   |
| 0xa0655    | 1        | 0.74%   |
| 0x906ed    | 1        | 0.74%   |
| 0x906ea    | 1        | 0.74%   |
| 0x90675    | 1        | 0.74%   |
| 0x106a5    | 1        | 0.74%   |
| 0x0a404102 | 1        | 0.74%   |
| 0x0a201204 | 1        | 0.74%   |
| 0x0a201016 | 1        | 0.74%   |
| 0x08701030 | 1        | 0.74%   |
| 0x0800820d | 1        | 0.74%   |
| 0x0600111f | 1        | 0.74%   |
| 0x06001119 | 1        | 0.74%   |
| 0x01000095 | 1        | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 15       | 11.45%  |
| KabyLake         | 14       | 10.69%  |
| SandyBridge      | 12       | 9.16%   |
| Piledriver       | 11       | 8.4%    |
| Zen+             | 9        | 6.87%   |
| Penryn           | 9        | 6.87%   |
| IvyBridge        | 8        | 6.11%   |
| K10              | 7        | 5.34%   |
| Zen 3            | 6        | 4.58%   |
| Zen              | 6        | 4.58%   |
| Alderlake Hybrid | 6        | 4.58%   |
| Zen 2            | 5        | 3.82%   |
| Skylake          | 5        | 3.82%   |
| Core             | 4        | 3.05%   |
| Nehalem          | 3        | 2.29%   |
| K8 Hammer        | 2        | 1.53%   |
| CometLake        | 2        | 1.53%   |
| Unknown          | 2        | 1.53%   |
| Westmere         | 1        | 0.76%   |
| Steamroller      | 1        | 0.76%   |
| K10 Llano        | 1        | 0.76%   |
| Icelake          | 1        | 0.76%   |
| Broadwell        | 1        | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 57       | 38.26%  |
| Intel  | 46       | 30.87%  |
| AMD    | 46       | 30.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 6%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 5.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 4        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.67%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 2%      |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 2%      |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3        | 2%      |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 2%      |
| Intel HD Graphics 630                                                       | 3        | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2%      |
| AMD RS780L [Radeon 3000]                                                    | 3        | 2%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 2%      |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 3        | 2%      |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.33%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.33%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.33%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 1.33%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.33%   |
| Intel HD Graphics 530                                                       | 2        | 1.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.33%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 1.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.33%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 1.33%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.67%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1        | 0.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.67%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 0.67%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 53       | 40.15%  |
| 1 x AMD        | 41       | 31.06%  |
| 1 x Intel      | 31       | 23.48%  |
| Intel + Nvidia | 2        | 1.52%   |
| Intel + AMD    | 2        | 1.52%   |
| AMD + Nvidia   | 2        | 1.52%   |
| 2 x AMD        | 1        | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 101      | 76.52%  |
| Proprietary | 24       | 18.18%  |
| Unknown     | 7        | 5.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 76       | 56.3%   |
| 1.01-2.0   | 13       | 9.63%   |
| 7.01-8.0   | 12       | 8.89%   |
| 3.01-4.0   | 12       | 8.89%   |
| 0.51-1.0   | 9        | 6.67%   |
| 0.01-0.5   | 6        | 4.44%   |
| 5.01-6.0   | 4        | 2.96%   |
| 8.01-16.0  | 3        | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 26       | 18.06%  |
| Dell                 | 17       | 11.81%  |
| Acer                 | 13       | 9.03%   |
| Hewlett-Packard      | 10       | 6.94%   |
| Goldstar             | 8        | 5.56%   |
| BenQ                 | 8        | 5.56%   |
| Ancor Communications | 8        | 5.56%   |
| Unknown              | 6        | 4.17%   |
| Philips              | 6        | 4.17%   |
| AOC                  | 6        | 4.17%   |
| Toshiba              | 3        | 2.08%   |
| AUS                  | 3        | 2.08%   |
| Vizio                | 2        | 1.39%   |
| ViewSonic            | 2        | 1.39%   |
| Panasonic            | 2        | 1.39%   |
| NEC Computers        | 2        | 1.39%   |
| Insignia             | 2        | 1.39%   |
| Iiyama               | 2        | 1.39%   |
| ASUSTek Computer     | 2        | 1.39%   |
| ___                  | 1        | 0.69%   |
| VOR                  | 1        | 0.69%   |
| STD                  | 1        | 0.69%   |
| Sony                 | 1        | 0.69%   |
| Sceptre              | 1        | 0.69%   |
| RIS                  | 1        | 0.69%   |
| Plain Tree Systems   | 1        | 0.69%   |
| MStar                | 1        | 0.69%   |
| LG Electronics       | 1        | 0.69%   |
| Lenovo               | 1        | 0.69%   |
| KON                  | 1        | 0.69%   |
| GDH                  | 1        | 0.69%   |
| Eizo                 | 1        | 0.69%   |
| BBY                  | 1        | 0.69%   |
| Ativa                | 1        | 0.69%   |
| AGO                  | 1        | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2        | 1.3%    |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2        | 1.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 1.3%    |
| Panasonic TV MEIA08F 1920x540                                         | 2        | 1.3%    |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2        | 1.3%    |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2        | 1.3%    |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                     | 2        | 1.3%    |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 2        | 1.3%    |
| AUS LCD Monitor VG245 1920x1080                                       | 2        | 1.3%    |
| Acer X223W ACR0011 1680x1050 470x300mm 22.0-inch                      | 2        | 1.3%    |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.65%   |
| VOR LED21300 VOR2150 1920x1080 597x336mm 27.0-inch                    | 1        | 0.65%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 1        | 0.65%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                    | 1        | 0.65%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1        | 0.65%   |
| ViewSonic VA3456-WQHD VSCFC3A 3440x1440 800x335mm 34.1-inch           | 1        | 0.65%   |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 0.65%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1        | 0.65%   |
| Unknown LCD Monitor SAMSUNG 1600x900                                  | 1        | 0.65%   |
| Unknown LCD Monitor HRX 32H4030 1920x1080                             | 1        | 0.65%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                       | 1        | 0.65%   |
| STD Monitor STD0001 1920x1080                                         | 1        | 0.65%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 1        | 0.65%   |
| Sceptre LCD Monitor P30 2560x1080                                     | 1        | 0.65%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM043F 1920x1200 518x324mm 24.1-inch  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch  | 1        | 0.65%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch    | 1        | 0.65%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch    | 1        | 0.65%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1        | 0.65%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch     | 1        | 0.65%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch     | 1        | 0.65%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM7245 1920x1080 700x390mm 31.5-inch | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 700x390mm 31.5-inch | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 50.37%  |
| 1280x1024 (SXGA)   | 11       | 8.15%   |
| 1680x1050 (WSXGA+) | 10       | 7.41%   |
| 3840x2160 (4K)     | 8        | 5.93%   |
| 1920x1200 (WUXGA)  | 6        | 4.44%   |
| 1360x768           | 5        | 3.7%    |
| 1440x900 (WXGA+)   | 4        | 2.96%   |
| 3440x1440          | 3        | 2.22%   |
| 2560x1440 (QHD)    | 3        | 2.22%   |
| 2560x1080          | 3        | 2.22%   |
| Unknown            | 3        | 2.22%   |
| 1920x540           | 2        | 1.48%   |
| 1366x768 (WXGA)    | 2        | 1.48%   |
| 1280x720 (HD)      | 2        | 1.48%   |
| 5200x1080          | 1        | 0.74%   |
| 3840x1080          | 1        | 0.74%   |
| 3200x1080          | 1        | 0.74%   |
| 1600x900 (HD+)     | 1        | 0.74%   |
| 1600x1200          | 1        | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 27       | 18.88%  |
| Unknown | 20       | 13.99%  |
| 27      | 15       | 10.49%  |
| 23      | 13       | 9.09%   |
| 22      | 9        | 6.29%   |
| 21      | 9        | 6.29%   |
| 19      | 7        | 4.9%    |
| 31      | 6        | 4.2%    |
| 17      | 6        | 4.2%    |
| 40      | 4        | 2.8%    |
| 34      | 4        | 2.8%    |
| 32      | 3        | 2.1%    |
| 72      | 2        | 1.4%    |
| 54      | 2        | 1.4%    |
| 47      | 2        | 1.4%    |
| 20      | 2        | 1.4%    |
| 18      | 2        | 1.4%    |
| 84      | 1        | 0.7%    |
| 52      | 1        | 0.7%    |
| 46      | 1        | 0.7%    |
| 43      | 1        | 0.7%    |
| 42      | 1        | 0.7%    |
| 41      | 1        | 0.7%    |
| 36      | 1        | 0.7%    |
| 25      | 1        | 0.7%    |
| 15      | 1        | 0.7%    |
| 12      | 1        | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 48       | 35.29%  |
| 401-500     | 25       | 18.38%  |
| Unknown     | 20       | 14.71%  |
| 701-800     | 8        | 5.88%   |
| 601-700     | 7        | 5.15%   |
| 301-350     | 7        | 5.15%   |
| 1001-1500   | 6        | 4.41%   |
| 801-900     | 4        | 2.94%   |
| 351-400     | 4        | 2.94%   |
| 1501-2000   | 3        | 2.21%   |
| 901-1000    | 3        | 2.21%   |
| 201-300     | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 77       | 59.69%  |
| 16/10   | 17       | 13.18%  |
| Unknown | 15       | 11.63%  |
| 5/4     | 9        | 6.98%   |
| 4/3     | 4        | 3.1%    |
| 21/9    | 4        | 3.1%    |
| 32/9    | 2        | 1.55%   |
| 3/2     | 1        | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 46       | 32.39%  |
| Unknown        | 20       | 14.08%  |
| 301-350        | 15       | 10.56%  |
| 351-500        | 13       | 9.15%   |
| 151-200        | 12       | 8.45%   |
| 251-300        | 10       | 7.04%   |
| 501-1000       | 10       | 7.04%   |
| 141-150        | 8        | 5.63%   |
| More than 1000 | 6        | 4.23%   |
| 71-80          | 1        | 0.7%    |
| 111-120        | 1        | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 79       | 61.24%  |
| Unknown | 20       | 15.5%   |
| 101-120 | 15       | 11.63%  |
| 1-50    | 10       | 7.75%   |
| 121-160 | 3        | 2.33%   |
| 161-240 | 2        | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 92       | 67.15%  |
| 2     | 32       | 23.36%  |
| 0     | 8        | 5.84%   |
| 3     | 5        | 3.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 85       | 37.12%  |
| Intel                           | 51       | 22.27%  |
| Ralink Technology               | 14       | 6.11%   |
| Qualcomm Atheros                | 14       | 6.11%   |
| Broadcom                        | 9        | 3.93%   |
| TP-Link                         | 7        | 3.06%   |
| Samsung Electronics             | 5        | 2.18%   |
| Ralink                          | 4        | 1.75%   |
| NetGear                         | 4        | 1.75%   |
| Microsoft                       | 4        | 1.75%   |
| Qualcomm Atheros Communications | 3        | 1.31%   |
| Nvidia                          | 3        | 1.31%   |
| MediaTek                        | 3        | 1.31%   |
| D-Link System                   | 3        | 1.31%   |
| vivo                            | 2        | 0.87%   |
| OnePlus Technology (Shenzhen)   | 2        | 0.87%   |
| Mercucys                        | 2        | 0.87%   |
| Broadcom Limited                | 2        | 0.87%   |
| ASUSTek Computer                | 2        | 0.87%   |
| Xiaomi                          | 1        | 0.44%   |
| Microchip Technology            | 1        | 0.44%   |
| Marvell Technology Group        | 1        | 0.44%   |
| Linksys                         | 1        | 0.44%   |
| Lenovo                          | 1        | 0.44%   |
| ICS Advent                      | 1        | 0.44%   |
| Huawei Technologies             | 1        | 0.44%   |
| Gemtek                          | 1        | 0.44%   |
| D-Link                          | 1        | 0.44%   |
| ASIX Electronics                | 1        | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 66       | 25.38%  |
| Intel I211 Gigabit Network Connection                                  | 8        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 3.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 6        | 2.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5        | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 1.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 5        | 1.92%   |
| Ralink MT7601U Wireless Adapter                                        | 5        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.54%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 4        | 1.54%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 1.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 3        | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 1.15%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 1.15%   |
| Intel Ethernet Controller I225-V                                       | 3        | 1.15%   |
| Intel Ethernet Connection I217-V                                       | 3        | 1.15%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3        | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.77%   |
| TP-Link Archer T4U ver.3                                               | 2        | 0.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2        | 0.77%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.77%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 2        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.77%   |
| OnePlus (Shenzhen) KB2000                                              | 2        | 0.77%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 2        | 0.77%   |
| Mercucys 802.11n NIC                                                   | 2        | 0.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2        | 0.77%   |
| Intel Wireless 7265                                                    | 2        | 0.77%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 0.77%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 0.77%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]     | 2        | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.38%   |
| vivo iQOO Neo7 ç«éç                                      | 1        | 0.38%   |
| vivo 1820                                                              | 1        | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 27       | 25.96%  |
| Ralink Technology               | 14       | 13.46%  |
| Intel                           | 14       | 13.46%  |
| Qualcomm Atheros                | 9        | 8.65%   |
| TP-Link                         | 7        | 6.73%   |
| Broadcom                        | 7        | 6.73%   |
| Ralink                          | 4        | 3.85%   |
| NetGear                         | 4        | 3.85%   |
| Microsoft                       | 4        | 3.85%   |
| Qualcomm Atheros Communications | 3        | 2.88%   |
| Mercucys                        | 2        | 1.92%   |
| MediaTek                        | 2        | 1.92%   |
| ASUSTek Computer                | 2        | 1.92%   |
| Linksys                         | 1        | 0.96%   |
| Gemtek                          | 1        | 0.96%   |
| D-Link System                   | 1        | 0.96%   |
| D-Link                          | 1        | 0.96%   |
| Broadcom Limited                | 1        | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 6        | 5.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 5        | 4.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 5        | 4.72%   |
| Ralink MT7601U Wireless Adapter                                    | 5        | 4.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 4        | 3.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                   | 4        | 3.77%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                | 3        | 2.83%   |
| Qualcomm Atheros AR9271 802.11n                                    | 3        | 2.83%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter       | 3        | 2.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 2        | 1.89%   |
| TP-Link Archer T4U ver.3                                           | 2        | 1.89%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                             | 2        | 1.89%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 2        | 1.89%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter           | 2        | 1.89%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 2        | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 2        | 1.89%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 1.89%   |
| Mercucys 802.11n NIC                                               | 2        | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 2        | 1.89%   |
| Intel Wireless 7265                                                | 2        | 1.89%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 2        | 1.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 1        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1        | 0.94%   |
| Realtek RTL8812AU-VS 802.11a/b/g/n/ac 2T2R DB WLAN Adapter         | 1        | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 1        | 0.94%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1        | 0.94%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)          | 1        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1        | 0.94%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter            | 1        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.94%   |
| Ralink RT5572 Wireless Adapter                                     | 1        | 0.94%   |
| Ralink RT5372 Wireless Adapter                                     | 1        | 0.94%   |
| Ralink RT5370 Wireless Adapter                                     | 1        | 0.94%   |
| Ralink RT2070 Wireless Adapter                                     | 1        | 0.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                          | 1        | 0.94%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 1        | 0.94%   |
| Ralink RT2561/RT61 802.11g PCI                                     | 1        | 0.94%   |
| Ralink RT2500 Wireless 802.11bg                                    | 1        | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1        | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1        | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 76       | 51.7%   |
| Intel                    | 45       | 30.61%  |
| Qualcomm Atheros         | 6        | 4.08%   |
| Samsung Electronics      | 5        | 3.4%    |
| Nvidia                   | 3        | 2.04%   |
| D-Link System            | 2        | 1.36%   |
| Broadcom                 | 2        | 1.36%   |
| Xiaomi                   | 1        | 0.68%   |
| vivo                     | 1        | 0.68%   |
| MediaTek                 | 1        | 0.68%   |
| Marvell Technology Group | 1        | 0.68%   |
| Lenovo                   | 1        | 0.68%   |
| ICS Advent               | 1        | 0.68%   |
| Broadcom Limited         | 1        | 0.68%   |
| ASIX Electronics         | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 66       | 44.3%   |
| Intel I211 Gigabit Network Connection                                  | 8        | 5.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 5.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5        | 3.36%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5        | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 2.68%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 2.68%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 2.68%   |
| Nvidia MCP61 Ethernet                                                  | 3        | 2.01%   |
| Intel Ethernet Controller I225-V                                       | 3        | 2.01%   |
| Intel Ethernet Connection I217-V                                       | 3        | 2.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 1.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 1.34%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 1.34%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 1.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 0.67%   |
| vivo 1820                                                              | 1        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 0.67%   |
| MediaTek moto e22                                                      | 1        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 0.67%   |
| Lenovo TB-X606F                                                        | 1        | 0.67%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.67%   |
| Intel Ethernet Connection (17) I219-V                                  | 1        | 0.67%   |
| Intel Ethernet Connection (17) I219-LM                                 | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 0.67%   |
| Intel Ethernet Connection (11) I219-LM                                 | 1        | 0.67%   |
| Intel 82583V Gigabit Network Connection                                | 1        | 0.67%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 0.67%   |
| Intel 82571EB Gigabit Ethernet Controller                              | 1        | 0.67%   |
| Intel 82567LF-2 Gigabit Network Connection                             | 1        | 0.67%   |
| Intel 82562V-2 10/100 Network Connection                               | 1        | 0.67%   |
| ICS Advent USB 10/100 LAN                                              | 1        | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 129      | 58.37%  |
| WiFi     | 87       | 39.37%  |
| Unknown  | 4        | 1.81%   |
| Modem    | 1        | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 89       | 63.57%  |
| WiFi     | 50       | 35.71%  |
| Unknown  | 1        | 0.71%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 85       | 63.91%  |
| 2     | 39       | 29.32%  |
| 3     | 5        | 3.76%   |
| 0     | 2        | 1.5%    |
| 5     | 1        | 0.75%   |
| 4     | 1        | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 105      | 78.36%  |
| Yes  | 29       | 21.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 30.95%  |
| Cambridge Silicon Radio         | 9        | 21.43%  |
| Qualcomm Atheros Communications | 4        | 9.52%   |
| ASUSTek Computer                | 4        | 9.52%   |
| Realtek Semiconductor           | 2        | 4.76%   |
| MediaTek                        | 2        | 4.76%   |
| TP-Link                         | 1        | 2.38%   |
| Toshiba                         | 1        | 2.38%   |
| Realtek                         | 1        | 2.38%   |
| Logitech                        | 1        | 2.38%   |
| IMC Networks                    | 1        | 2.38%   |
| Dynex                           | 1        | 2.38%   |
| Dell                            | 1        | 2.38%   |
| Apple                           | 1        | 2.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 9        | 21.43%  |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 9.52%   |
| Intel Bluetooth wireless interface                       | 4        | 9.52%   |
| Intel Bluetooth Device                                   | 3        | 7.14%   |
| Intel AX201 Bluetooth                                    | 3        | 7.14%   |
| Realtek Bluetooth Radio                                  | 2        | 4.76%   |
| MediaTek Wireless_Device                                 | 2        | 4.76%   |
| TP-Link UB500 Adapter                                    | 1        | 2.38%   |
| Toshiba Atheros AR3012 Bluetooth                         | 1        | 2.38%   |
| Realtek Bluetooth Radio                                  | 1        | 2.38%   |
| Logitech BT Mini-Receiver (HCI mode)                     | 1        | 2.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1        | 2.38%   |
| Intel Wireless-AC 3168 Bluetooth                         | 1        | 2.38%   |
| Intel AX200 Bluetooth                                    | 1        | 2.38%   |
| IMC Networks Bluetooth Device                            | 1        | 2.38%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 2.38%   |
| Dell Broadcom BCM20702A0 Bluetooth                       | 1        | 2.38%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 2.38%   |
| ASUS Bluetooth Adapter                                   | 1        | 2.38%   |
| ASUS BCM20702A0                                          | 1        | 2.38%   |
| ASUS ASUS USB-BT500                                      | 1        | 2.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 1        | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 81       | 36.82%  |
| AMD                      | 63       | 28.64%  |
| Nvidia                   | 52       | 23.64%  |
| C-Media Electronics      | 7        | 3.18%   |
| Logitech                 | 2        | 0.91%   |
| Corsair                  | 2        | 0.91%   |
| Yamaha                   | 1        | 0.45%   |
| USB-MIC                  | 1        | 0.45%   |
| Tenx Technology          | 1        | 0.45%   |
| SteelSeries ApS          | 1        | 0.45%   |
| Samson Technologies      | 1        | 0.45%   |
| Razer USA                | 1        | 0.45%   |
| Micro Star International | 1        | 0.45%   |
| Kingston Technology      | 1        | 0.45%   |
| JMTek                    | 1        | 0.45%   |
| GYROCOM C&C              | 1        | 0.45%   |
| GN Netcom                | 1        | 0.45%   |
| Generalplus Technology   | 1        | 0.45%   |
| Creative Labs            | 1        | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 13       | 4.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12       | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 12       | 4.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 4.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11       | 4.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10       | 3.8%    |
| AMD Family 17h/19h HD Audio Controller                                            | 9        | 3.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 3.04%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 3.04%   |
| Nvidia GA104 High Definition Audio Controller                                     | 7        | 2.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 2.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 7        | 2.66%   |
| Intel Alder Lake-S HD Audio Controller                                            | 6        | 2.28%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 2.28%   |
| AMD FCH Azalia Controller                                                         | 6        | 2.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 2.28%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 2.28%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 1.9%    |
| Nvidia GA106 High Definition Audio Controller                                     | 5        | 1.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 1.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.52%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.14%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 1.14%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3        | 1.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3        | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.14%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.76%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 0.76%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 0.76%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 0.76%   |
| AMD Trinity HDMI Audio Controller                                                 | 2        | 0.76%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 2        | 0.76%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 0.76%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 17.86%  |
| Corsair             | 13       | 15.48%  |
| Kingston            | 12       | 14.29%  |
| Crucial             | 9        | 10.71%  |
| SK hynix            | 7        | 8.33%   |
| G.Skill             | 5        | 5.95%   |
| Samsung Electronics | 4        | 4.76%   |
| Micron Technology   | 3        | 3.57%   |
| Unknown             | 3        | 3.57%   |
| Team                | 2        | 2.38%   |
| A-DATA Technology   | 2        | 2.38%   |
| Unifosa             | 1        | 1.19%   |
| Silicon Power       | 1        | 1.19%   |
| S                   | 1        | 1.19%   |
| Ramos Technology    | 1        | 1.19%   |
| PNY                 | 1        | 1.19%   |
| Patriot             | 1        | 1.19%   |
| Nanya Technology    | 1        | 1.19%   |
| Asgard              | 1        | 1.19%   |
| AMD                 | 1        | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 3        | 3.33%   |
| Unknown                                                    | 3        | 3.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 2        | 2.22%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 2.22%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s        | 2        | 2.22%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s      | 2        | 2.22%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 1.11%   |
| Unknown RAM Module 8GB DIMM 667MT/s                        | 1        | 1.11%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                  | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM 800MT/s                        | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 1.11%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                       | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 1        | 1.11%   |
| Unknown RAM Module 2GB DIMM                                | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 1        | 1.11%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s        | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s         | 1        | 1.11%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s               | 1        | 1.11%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 1.11%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                     | 1        | 1.11%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.11%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.11%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s    | 1        | 1.11%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s     | 1        | 1.11%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 1.11%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s | 1        | 1.11%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s        | 1        | 1.11%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 1.11%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s        | 1        | 1.11%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s        | 1        | 1.11%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.11%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.11%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 1.11%   |
| Ramos RAM EMB2GB481CL4-13HA 2GB DIMM 1227MT/s              | 1        | 1.11%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s        | 1        | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 31       | 40.79%  |
| DDR3    | 28       | 36.84%  |
| Unknown | 8        | 10.53%  |
| SDRAM   | 3        | 3.95%   |
| DDR5    | 3        | 3.95%   |
| DDR2    | 3        | 3.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 68       | 93.15%  |
| SODIMM | 5        | 6.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 33       | 41.25%  |
| 4096  | 17       | 21.25%  |
| 2048  | 13       | 16.25%  |
| 16384 | 11       | 13.75%  |
| 32768 | 3        | 3.75%   |
| 1024  | 3        | 3.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 14.29%  |
| 3600    | 10       | 11.9%   |
| 1333    | 9        | 10.71%  |
| 3200    | 7        | 8.33%   |
| 2400    | 5        | 5.95%   |
| 2667    | 4        | 4.76%   |
| 1867    | 4        | 4.76%   |
| 1800    | 4        | 4.76%   |
| Unknown | 3        | 3.57%   |
| 4800    | 2        | 2.38%   |
| 3800    | 2        | 2.38%   |
| 1866    | 2        | 2.38%   |
| 1067    | 2        | 2.38%   |
| 800     | 2        | 2.38%   |
| 6800    | 1        | 1.19%   |
| 3866    | 1        | 1.19%   |
| 3733    | 1        | 1.19%   |
| 3534    | 1        | 1.19%   |
| 3533    | 1        | 1.19%   |
| 3100    | 1        | 1.19%   |
| 3000    | 1        | 1.19%   |
| 2933    | 1        | 1.19%   |
| 2666    | 1        | 1.19%   |
| 2200    | 1        | 1.19%   |
| 2133    | 1        | 1.19%   |
| 2132    | 1        | 1.19%   |
| 1227    | 1        | 1.19%   |
| 1066    | 1        | 1.19%   |
| 667     | 1        | 1.19%   |
| 400     | 1        | 1.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 1        | 25%     |
| Samsung Electronics | 1        | 25%     |
| Hewlett-Packard     | 1        | 25%     |
| Dymo-CoStar         | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Seiko Epson L120 Series      | 1        | 25%     |
| Samsung ML-2850 Series       | 1        | 25%     |
| HP OfficeJet Pro 7720 series | 1        | 25%     |
| Dymo-CoStar LabelWriter 450  | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 5        | 23.81%  |
| Microdia               | 4        | 19.05%  |
| Generalplus Technology | 2        | 9.52%   |
| Creative Technology    | 2        | 9.52%   |
| Teslong Camera         | 1        | 4.76%   |
| Razer USA              | 1        | 4.76%   |
| LG Electronics         | 1        | 4.76%   |
| Jieli Technology       | 1        | 4.76%   |
| IMC Networks           | 1        | 4.76%   |
| Chicony Electronics    | 1        | 4.76%   |
| ARC International      | 1        | 4.76%   |
| Apple                  | 1        | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Webcam C615                               | 2        | 9.52%   |
| Generalplus GENERAL WEBCAM                            | 2        | 9.52%   |
| Creative Live! Cam Sync HD [VF0770]                   | 2        | 9.52%   |
| Teslong Camera                                        | 1        | 4.76%   |
| Razer USA Gaming Webcam [Kiyo]                        | 1        | 4.76%   |
| Microdia Webcam Vitade AF                             | 1        | 4.76%   |
| Microdia Sonix USB 2.0 Camera                         | 1        | 4.76%   |
| Microdia PC Microscope camera                         | 1        | 4.76%   |
| Microdia Defender G-Lens 2577 HD720p Camera           | 1        | 4.76%   |
| Logitech Webcam C270                                  | 1        | 4.76%   |
| Logitech HD Pro Webcam C920                           | 1        | 4.76%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 4.76%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 4.76%   |
| Jieli USB PHY 2.0                                     | 1        | 4.76%   |
| IMC Networks XHC Camera                               | 1        | 4.76%   |
| Chicony HP High Definition 1MP Webcam                 | 1        | 4.76%   |
| ARC International Camera                              | 1        | 4.76%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                    | 1        | 4.76%   |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 100      | 74.63%  |
| 1     | 29       | 21.64%  |
| 2     | 5        | 3.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 17       | 44.74%  |
| Graphics card            | 11       | 28.95%  |
| Communication controller | 3        | 7.89%   |
| Net/ethernet             | 2        | 5.26%   |
| Dvb card                 | 2        | 5.26%   |
| Storage/raid             | 1        | 2.63%   |
| Multimedia controller    | 1        | 2.63%   |
| Camera                   | 1        | 2.63%   |

