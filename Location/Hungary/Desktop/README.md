Linux in Hungary - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

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

Total: 2946

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 21EF                        | [0aacd43b02](https://linux-hardware.org/?probe=0aacd43b02) | Jan 31, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| Gigabyte      | H61M-S2PV                   | [4aa843346a](https://linux-hardware.org/?probe=4aa843346a) | Jan 31, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [00fcd39954](https://linux-hardware.org/?probe=00fcd39954) | Jan 31, 2023 |
| Lenovo        | NO DPK                      | [35edbda29f](https://linux-hardware.org/?probe=35edbda29f) | Jan 30, 2023 |
| Lenovo        | NO DPK                      | [e21e3e152b](https://linux-hardware.org/?probe=e21e3e152b) | Jan 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [a3e79a2330](https://linux-hardware.org/?probe=a3e79a2330) | Jan 30, 2023 |
| Gigabyte      | H61M-S2PV                   | [5181ba0a3d](https://linux-hardware.org/?probe=5181ba0a3d) | Jan 30, 2023 |
| Dell          | 0D883F A06                  | [5fe35cda58](https://linux-hardware.org/?probe=5fe35cda58) | Jan 29, 2023 |
| Dell          | 0D883F A06                  | [ec1220585a](https://linux-hardware.org/?probe=ec1220585a) | Jan 29, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [f3530a6a1f](https://linux-hardware.org/?probe=f3530a6a1f) | Jan 28, 2023 |
| ASUSTek       | PRIME B365M-A               | [60fffa5422](https://linux-hardware.org/?probe=60fffa5422) | Jan 25, 2023 |
| MSI           | MS-7817                     | [93d29f37d8](https://linux-hardware.org/?probe=93d29f37d8) | Jan 24, 2023 |
| MSI           | MS-7817                     | [db9c2416af](https://linux-hardware.org/?probe=db9c2416af) | Jan 24, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [123c1db6ac](https://linux-hardware.org/?probe=123c1db6ac) | Jan 23, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48ee4a3eef](https://linux-hardware.org/?probe=48ee4a3eef) | Jan 23, 2023 |
| ASUSTek       | PRIME B365M-A               | [6727a94c5e](https://linux-hardware.org/?probe=6727a94c5e) | Jan 23, 2023 |
| ASUSTek       | PRIME B365M-A               | [b3e3fd8775](https://linux-hardware.org/?probe=b3e3fd8775) | Jan 23, 2023 |
| ASUSTek       | PRIME B365M-A               | [561b2897e2](https://linux-hardware.org/?probe=561b2897e2) | Jan 23, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [00f2a52261](https://linux-hardware.org/?probe=00f2a52261) | Jan 22, 2023 |
| Gigabyte      | M52LT-D3                    | [b53ddd69a6](https://linux-hardware.org/?probe=b53ddd69a6) | Jan 22, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [2851ee7994](https://linux-hardware.org/?probe=2851ee7994) | Jan 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [4584e904f8](https://linux-hardware.org/?probe=4584e904f8) | Jan 21, 2023 |
| Dell          | 0XCR8D A03                  | [1abe984576](https://linux-hardware.org/?probe=1abe984576) | Jan 21, 2023 |
| Gigabyte      | H61M-D2-B3                  | [e261893ec4](https://linux-hardware.org/?probe=e261893ec4) | Jan 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [0c77a64f45](https://linux-hardware.org/?probe=0c77a64f45) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | [221830de98](https://linux-hardware.org/?probe=221830de98) | Jan 17, 2023 |
| MSI           | MS-7817                     | [8eac0961cc](https://linux-hardware.org/?probe=8eac0961cc) | Jan 17, 2023 |
| MSI           | MS-7817                     | [14ae598595](https://linux-hardware.org/?probe=14ae598595) | Jan 17, 2023 |
| Gigabyte      | P67A-D3-B3                  | [3117124412](https://linux-hardware.org/?probe=3117124412) | Jan 16, 2023 |
| Gigabyte      | H61M-S2PV                   | [61f16ccc60](https://linux-hardware.org/?probe=61f16ccc60) | Jan 15, 2023 |
| ASUSTek       | H81M-C                      | [25f5800974](https://linux-hardware.org/?probe=25f5800974) | Jan 15, 2023 |
| ASUSTek       | H81M-C                      | [f1516ea54d](https://linux-hardware.org/?probe=f1516ea54d) | Jan 15, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [1eb9f8fa55](https://linux-hardware.org/?probe=1eb9f8fa55) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c541b9f1cd](https://linux-hardware.org/?probe=c541b9f1cd) | Jan 14, 2023 |
| ASUSTek       | B85M-G                      | [8c2c6b3355](https://linux-hardware.org/?probe=8c2c6b3355) | Jan 13, 2023 |
| HP            | 8265                        | [ff276ee116](https://linux-hardware.org/?probe=ff276ee116) | Jan 11, 2023 |
| Dell          | 0K240Y A01                  | [2baa58c11e](https://linux-hardware.org/?probe=2baa58c11e) | Jan 10, 2023 |
| HP            | 3032h                       | [1e729e9b75](https://linux-hardware.org/?probe=1e729e9b75) | Jan 09, 2023 |
| Lenovo        | ThinkCentre M58p 9728W47    | [cdf4eb72bb](https://linux-hardware.org/?probe=cdf4eb72bb) | Jan 09, 2023 |
| ASUSTek       | PRIME H410M-R               | [cfc6e0c455](https://linux-hardware.org/?probe=cfc6e0c455) | Jan 08, 2023 |
| VXL           | M6V90AI-VL                  | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
| ASUSTek       | H110M-A                     | [8866a21a4b](https://linux-hardware.org/?probe=8866a21a4b) | Jan 08, 2023 |
| HP            | 3029h                       | [8d20c516df](https://linux-hardware.org/?probe=8d20c516df) | Jan 08, 2023 |
| ASUSTek       | H81M-C                      | [ca27e27e15](https://linux-hardware.org/?probe=ca27e27e15) | Jan 06, 2023 |
| ASUSTek       | H81M-C                      | [7535d6b22b](https://linux-hardware.org/?probe=7535d6b22b) | Jan 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | [b1132f1491](https://linux-hardware.org/?probe=b1132f1491) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| ASRock        | AB350M Pro4                 | [42b1f8124d](https://linux-hardware.org/?probe=42b1f8124d) | Jan 03, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [7125f2d1da](https://linux-hardware.org/?probe=7125f2d1da) | Jan 02, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [8268625d25](https://linux-hardware.org/?probe=8268625d25) | Jan 02, 2023 |
| MSI           | MS-7817                     | [658352807e](https://linux-hardware.org/?probe=658352807e) | Jan 01, 2023 |
| MSI           | MS-7817                     | [135f56eb99](https://linux-hardware.org/?probe=135f56eb99) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Lenovo        | ThinkCentre M58p 9728W47    | [68bc291efd](https://linux-hardware.org/?probe=68bc291efd) | Dec 31, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| Gigabyte      | B450M GAMING                | [199a8927b8](https://linux-hardware.org/?probe=199a8927b8) | Dec 29, 2022 |
| Gigabyte      | B450M GAMING                | [012f398d07](https://linux-hardware.org/?probe=012f398d07) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [447852c33b](https://linux-hardware.org/?probe=447852c33b) | Dec 28, 2022 |
| ASRock        | Z370 Extreme4               | [8b02482c16](https://linux-hardware.org/?probe=8b02482c16) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [3f022cb1a7](https://linux-hardware.org/?probe=3f022cb1a7) | Dec 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [7c5a7b9036](https://linux-hardware.org/?probe=7c5a7b9036) | Dec 24, 2022 |
| Dell          | 0PTTT9 A01                  | [4618f09759](https://linux-hardware.org/?probe=4618f09759) | Dec 23, 2022 |
| Gigabyte      | Z690 UD AX                  | [95a82c6f4d](https://linux-hardware.org/?probe=95a82c6f4d) | Dec 19, 2022 |
| Gigabyte      | B450M GAMING                | [3b2deb36cb](https://linux-hardware.org/?probe=3b2deb36cb) | Dec 19, 2022 |
| ASRock        | B550M Pro4                  | [6bfb0295df](https://linux-hardware.org/?probe=6bfb0295df) | Dec 19, 2022 |
| ASRock        | AM1H-ITX                    | [88fc771e47](https://linux-hardware.org/?probe=88fc771e47) | Dec 18, 2022 |
| Gigabyte      | B450M GAMING                | [477947ea20](https://linux-hardware.org/?probe=477947ea20) | Dec 17, 2022 |
| HP            | 2215                        | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| ASUSTek       | B75M-A                      | [e350e12e7c](https://linux-hardware.org/?probe=e350e12e7c) | Dec 15, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [96929b34ef](https://linux-hardware.org/?probe=96929b34ef) | Dec 15, 2022 |
| ASRock        | H310M-HDV/M.2               | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| VXL           | M6V90AI-VL                  | [a16094bb41](https://linux-hardware.org/?probe=a16094bb41) | Dec 14, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [a7c03c5bfd](https://linux-hardware.org/?probe=a7c03c5bfd) | Dec 14, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [42eef61903](https://linux-hardware.org/?probe=42eef61903) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| ASUSTek       | GL10DH                      | [ca2fb9f1a2](https://linux-hardware.org/?probe=ca2fb9f1a2) | Dec 13, 2022 |
| ASUSTek       | GL10DH                      | [5c148c3a41](https://linux-hardware.org/?probe=5c148c3a41) | Dec 13, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Biostar       | A320MH                      | [31cc96d1d3](https://linux-hardware.org/?probe=31cc96d1d3) | Dec 11, 2022 |
| HP            | 1589                        | [4aa31e9d16](https://linux-hardware.org/?probe=4aa31e9d16) | Dec 11, 2022 |
| HP            | 8265                        | [da426053be](https://linux-hardware.org/?probe=da426053be) | Dec 11, 2022 |
| Dell          | 0GY6Y8 A01                  | [afda77c820](https://linux-hardware.org/?probe=afda77c820) | Dec 10, 2022 |
| Dell          | 0HY9JP A02                  | [94a6153aeb](https://linux-hardware.org/?probe=94a6153aeb) | Dec 09, 2022 |
| ASUSTek       | P7H55D-M PRO                | [dfe2221b21](https://linux-hardware.org/?probe=dfe2221b21) | Dec 06, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [639497d7e0](https://linux-hardware.org/?probe=639497d7e0) | Dec 05, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [6a477d4759](https://linux-hardware.org/?probe=6a477d4759) | Dec 05, 2022 |
| Lenovo        | Tilapia CRB                 | [a32aaf0f8c](https://linux-hardware.org/?probe=a32aaf0f8c) | Dec 05, 2022 |
| ASRock        | N68C-S UCC                  | [cdd460e503](https://linux-hardware.org/?probe=cdd460e503) | Dec 04, 2022 |
| ASUSTek       | H110M-A                     | [6136553624](https://linux-hardware.org/?probe=6136553624) | Dec 03, 2022 |
| ASUSTek       | H110M-A                     | [9ac464aa29](https://linux-hardware.org/?probe=9ac464aa29) | Dec 03, 2022 |
| Gigabyte      | B85M-D3H                    | [5e58cb10a5](https://linux-hardware.org/?probe=5e58cb10a5) | Dec 02, 2022 |
| Gigabyte      | B85M-D3H                    | [81315b2876](https://linux-hardware.org/?probe=81315b2876) | Dec 02, 2022 |
| ASRock        | AB350 Pro4                  | [de19b92dda](https://linux-hardware.org/?probe=de19b92dda) | Nov 30, 2022 |
| Lenovo        | SDK0E50510 WIN              | [76b79932d5](https://linux-hardware.org/?probe=76b79932d5) | Nov 29, 2022 |
| MSI           | D2414 S26361-D2414-A10      | [ef1367a574](https://linux-hardware.org/?probe=ef1367a574) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | MS-7817                     | [3a740dd46a](https://linux-hardware.org/?probe=3a740dd46a) | Nov 28, 2022 |
| MSI           | MS-7817                     | [48ae0e1997](https://linux-hardware.org/?probe=48ae0e1997) | Nov 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [c56c5e5a10](https://linux-hardware.org/?probe=c56c5e5a10) | Nov 28, 2022 |
| ASUSTek       | PRIME A320M-K               | [e853b09dfa](https://linux-hardware.org/?probe=e853b09dfa) | Nov 28, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [550b448753](https://linux-hardware.org/?probe=550b448753) | Nov 27, 2022 |
| ASUSTek       | H110M-A                     | [03d5c6e735](https://linux-hardware.org/?probe=03d5c6e735) | Nov 23, 2022 |
| Gigabyte      | B450M GAMING                | [ac5deb8230](https://linux-hardware.org/?probe=ac5deb8230) | Nov 22, 2022 |
| Gigabyte      | B450M GAMING                | [ffc3ff8f31](https://linux-hardware.org/?probe=ffc3ff8f31) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| ASRock        | Z590M-ITX/ax                | [f01dec11e4](https://linux-hardware.org/?probe=f01dec11e4) | Nov 21, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [855f11c57b](https://linux-hardware.org/?probe=855f11c57b) | Nov 21, 2022 |
| Gigabyte      | GA-MA770-UD3                | [b963fb74e2](https://linux-hardware.org/?probe=b963fb74e2) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| MSI           | MS-7817                     | [b2c48fde2c](https://linux-hardware.org/?probe=b2c48fde2c) | Nov 20, 2022 |
| MSI           | MS-7817                     | [ffc17a7303](https://linux-hardware.org/?probe=ffc17a7303) | Nov 20, 2022 |
| ASUSTek       | P8H61-M LX2                 | [4db9e36520](https://linux-hardware.org/?probe=4db9e36520) | Nov 20, 2022 |
| ASUSTek       | P8H61-M LX2                 | [716649aa59](https://linux-hardware.org/?probe=716649aa59) | Nov 20, 2022 |
| ASUSTek       | H110M-A                     | [fd460bcba6](https://linux-hardware.org/?probe=fd460bcba6) | Nov 18, 2022 |
| ASUSTek       | B150M-A/M.2                 | [3e906bb29a](https://linux-hardware.org/?probe=3e906bb29a) | Nov 17, 2022 |
| Lenovo        | ThinkServer TS440           | [9fe9bc94a0](https://linux-hardware.org/?probe=9fe9bc94a0) | Nov 14, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [e7820d3dfb](https://linux-hardware.org/?probe=e7820d3dfb) | Nov 13, 2022 |
| ASUSTek       | AM1M-A                      | [11bffbe5e4](https://linux-hardware.org/?probe=11bffbe5e4) | Nov 12, 2022 |
| Acer          | Veriton M2631 V:1.0         | [9ed32f5227](https://linux-hardware.org/?probe=9ed32f5227) | Nov 12, 2022 |
| Acer          | Veriton M2631 V:1.0         | [99a2e00654](https://linux-hardware.org/?probe=99a2e00654) | Nov 11, 2022 |
| Gigabyte      | Z77X-D3H                    | [a697dc0e99](https://linux-hardware.org/?probe=a697dc0e99) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [718971a0f8](https://linux-hardware.org/?probe=718971a0f8) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | [b0f1fc9e0f](https://linux-hardware.org/?probe=b0f1fc9e0f) | Nov 11, 2022 |
| Lenovo        | ThinkCentre M58p 9728W47    | [48e81f1349](https://linux-hardware.org/?probe=48e81f1349) | Nov 10, 2022 |
| ASUSTek       | AM1M-A                      | [1af38f67c6](https://linux-hardware.org/?probe=1af38f67c6) | Nov 10, 2022 |
| ASUSTek       | PRIME Z370-P II             | [7a41c26bea](https://linux-hardware.org/?probe=7a41c26bea) | Nov 09, 2022 |
| Gigabyte      | P67A-D3-B3                  | [a5492a9260](https://linux-hardware.org/?probe=a5492a9260) | Nov 07, 2022 |
| ASRock        | 4CoreDual-SATA2             | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| ASUSTek       | PRIME A520M-K               | [52c7829518](https://linux-hardware.org/?probe=52c7829518) | Nov 05, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [a9bb64111f](https://linux-hardware.org/?probe=a9bb64111f) | Nov 05, 2022 |
| Gigabyte      | H61M-S1                     | [d5125861d0](https://linux-hardware.org/?probe=d5125861d0) | Nov 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | [0a598dc332](https://linux-hardware.org/?probe=0a598dc332) | Nov 02, 2022 |
| Dell          | 0K240Y A01                  | [41707b16d1](https://linux-hardware.org/?probe=41707b16d1) | Nov 02, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [cf394ed108](https://linux-hardware.org/?probe=cf394ed108) | Nov 01, 2022 |
| ASRock        | 4CoreDual-SATA2             | [446799aa8e](https://linux-hardware.org/?probe=446799aa8e) | Nov 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [183545ed4e](https://linux-hardware.org/?probe=183545ed4e) | Oct 31, 2022 |
| Gigabyte      | GA-MA770-UD3                | [e49d4af683](https://linux-hardware.org/?probe=e49d4af683) | Oct 31, 2022 |
| Gigabyte      | GA-MA770-UD3                | [52a6d45e82](https://linux-hardware.org/?probe=52a6d45e82) | Oct 29, 2022 |
| Dell          | 0K240Y A01                  | [4be40e9739](https://linux-hardware.org/?probe=4be40e9739) | Oct 27, 2022 |
| Dell          | 0K240Y A01                  | [fc26c82789](https://linux-hardware.org/?probe=fc26c82789) | Oct 27, 2022 |
| Lenovo        | ThinkServer TS440           | [acdfb9b02e](https://linux-hardware.org/?probe=acdfb9b02e) | Oct 26, 2022 |
| ASRock        | B450M Pro4                  | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Gigabyte      | G41MT-S2PT                  | [1ad0ed065f](https://linux-hardware.org/?probe=1ad0ed065f) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [4ab8d609e7](https://linux-hardware.org/?probe=4ab8d609e7) | Oct 16, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [8781d340f7](https://linux-hardware.org/?probe=8781d340f7) | Oct 16, 2022 |
| ASRock        | 4CoreDual-SATA2             | [a0c85cb9ab](https://linux-hardware.org/?probe=a0c85cb9ab) | Oct 15, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [365f1a9123](https://linux-hardware.org/?probe=365f1a9123) | Oct 15, 2022 |
| Fujitsu       | D3313-S4 S26361-D3313-S4    | [e92144b22a](https://linux-hardware.org/?probe=e92144b22a) | Oct 15, 2022 |
| ASRock        | 4CoreDual-SATA2             | [9743b0896c](https://linux-hardware.org/?probe=9743b0896c) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [ec470df515](https://linux-hardware.org/?probe=ec470df515) | Oct 11, 2022 |
| Gigabyte      | G41MT-S2PT                  | [e5720c01a5](https://linux-hardware.org/?probe=e5720c01a5) | Oct 10, 2022 |
| Gigabyte      | P67A-D3-B3                  | [000e5389a8](https://linux-hardware.org/?probe=000e5389a8) | Oct 10, 2022 |
| Dell          | 003KPJ A00                  | [e151f6645b](https://linux-hardware.org/?probe=e151f6645b) | Oct 08, 2022 |
| HP            | 3047h                       | [b29b0b1ef4](https://linux-hardware.org/?probe=b29b0b1ef4) | Oct 07, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [c7ae238295](https://linux-hardware.org/?probe=c7ae238295) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f19e278e43](https://linux-hardware.org/?probe=f19e278e43) | Oct 06, 2022 |
| Gigabyte      | P67A-D3-B3                  | [73c9f25932](https://linux-hardware.org/?probe=73c9f25932) | Oct 04, 2022 |
| Lenovo        | ThinkServer TS440           | [1031dfcd50](https://linux-hardware.org/?probe=1031dfcd50) | Oct 03, 2022 |
| ASUSTek       | PRIME B460M-A               | [0b1bf36485](https://linux-hardware.org/?probe=0b1bf36485) | Oct 02, 2022 |
| ASUSTek       | M5A78L LE                   | [1b2683c634](https://linux-hardware.org/?probe=1b2683c634) | Sep 30, 2022 |
| ASUSTek       | M5A78L LE                   | [8762386a2b](https://linux-hardware.org/?probe=8762386a2b) | Sep 30, 2022 |
| HP            | 3047h                       | [9426ee3f59](https://linux-hardware.org/?probe=9426ee3f59) | Sep 28, 2022 |
| ASUSTek       | P7H55D-M PRO                | [9ff56b2438](https://linux-hardware.org/?probe=9ff56b2438) | Sep 24, 2022 |
| ASUSTek       | P7H55D-M PRO                | [3ba342d57a](https://linux-hardware.org/?probe=3ba342d57a) | Sep 24, 2022 |
| Gigabyte      | H61M-S1                     | [b28077e806](https://linux-hardware.org/?probe=b28077e806) | Sep 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [d62d1ed9fd](https://linux-hardware.org/?probe=d62d1ed9fd) | Sep 21, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [5cf5ac2512](https://linux-hardware.org/?probe=5cf5ac2512) | Sep 21, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| ASUSTek       | P5PL2-E                     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| ASUSTek       | P7P55D                      | [10c83deaa9](https://linux-hardware.org/?probe=10c83deaa9) | Sep 15, 2022 |
| ASUSTek       | P7P55D                      | [4b6fca3ab4](https://linux-hardware.org/?probe=4b6fca3ab4) | Sep 15, 2022 |
| Gigabyte      | G41MT-S2PT                  | [8366bd494c](https://linux-hardware.org/?probe=8366bd494c) | Sep 14, 2022 |
| ASUSTek       | PRIME B250-PRO              | [98422dda65](https://linux-hardware.org/?probe=98422dda65) | Sep 14, 2022 |
| Dell          | 0PC5F7 A03                  | [161958a208](https://linux-hardware.org/?probe=161958a208) | Sep 14, 2022 |
| HP            | 3648h                       | [8ed24fd9d4](https://linux-hardware.org/?probe=8ed24fd9d4) | Sep 13, 2022 |
| ASUSTek       | P7P55D                      | [4a7057f627](https://linux-hardware.org/?probe=4a7057f627) | Sep 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b251a95678](https://linux-hardware.org/?probe=b251a95678) | Sep 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b3c2018879](https://linux-hardware.org/?probe=b3c2018879) | Sep 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [f10e559655](https://linux-hardware.org/?probe=f10e559655) | Sep 11, 2022 |
| Lenovo        | ThinkServer TS440           | [cf028f9b8c](https://linux-hardware.org/?probe=cf028f9b8c) | Sep 10, 2022 |
| HP            | 3396                        | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| Gigabyte      | P67A-D3-B3                  | [eba0d1ad0c](https://linux-hardware.org/?probe=eba0d1ad0c) | Sep 09, 2022 |
| HP            | 18E4                        | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| HP            | 805D                        | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Gigabyte      | P67A-D3-B3                  | [8c34a6ec8c](https://linux-hardware.org/?probe=8c34a6ec8c) | Sep 05, 2022 |
| Gigabyte      | F2A78M-D3H                  | [5b0da32c82](https://linux-hardware.org/?probe=5b0da32c82) | Sep 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [7cfd7da775](https://linux-hardware.org/?probe=7cfd7da775) | Sep 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [6552f796e2](https://linux-hardware.org/?probe=6552f796e2) | Sep 01, 2022 |
| HP            | 1589                        | [fce9004571](https://linux-hardware.org/?probe=fce9004571) | Sep 01, 2022 |
| ASUSTek       | V-M3N8200                   | [f593540c1c](https://linux-hardware.org/?probe=f593540c1c) | Sep 01, 2022 |
| ASUSTek       | V-M3N8200                   | [f3cc0c0bd5](https://linux-hardware.org/?probe=f3cc0c0bd5) | Sep 01, 2022 |
| Gigabyte      | B550M DS3H                  | [2e6d572c33](https://linux-hardware.org/?probe=2e6d572c33) | Aug 30, 2022 |
| Lenovo        | Dory CRB                    | [aa633e1f74](https://linux-hardware.org/?probe=aa633e1f74) | Aug 26, 2022 |
| Lenovo        | Dory CRB                    | [34492f12b7](https://linux-hardware.org/?probe=34492f12b7) | Aug 26, 2022 |
| ASUSTek       | A7N8X2.0                    | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | A7N8X2.0                    | [56416fa002](https://linux-hardware.org/?probe=56416fa002) | Aug 23, 2022 |
| Shuttle       | FS81                        | [4c3be1b1a6](https://linux-hardware.org/?probe=4c3be1b1a6) | Aug 21, 2022 |
| Gigabyte      | G31M-ES2L                   | [c51689de69](https://linux-hardware.org/?probe=c51689de69) | Aug 16, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [3bdf8d4582](https://linux-hardware.org/?probe=3bdf8d4582) | Aug 14, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [507fa4d8dc](https://linux-hardware.org/?probe=507fa4d8dc) | Aug 13, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [bc105e1507](https://linux-hardware.org/?probe=bc105e1507) | Aug 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 1589                        | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [7b8b4b5616](https://linux-hardware.org/?probe=7b8b4b5616) | Aug 08, 2022 |
| ASUSTek       | AM1M-A                      | [e778ebd72b](https://linux-hardware.org/?probe=e778ebd72b) | Aug 08, 2022 |
| ASUSTek       | AM1M-A                      | [687f213628](https://linux-hardware.org/?probe=687f213628) | Aug 05, 2022 |
| HP            | 1589                        | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| Lenovo        | SDK0E50510 WIN              | [566648ca6d](https://linux-hardware.org/?probe=566648ca6d) | Aug 02, 2022 |
| ASRock        | FM2A75M Pro4+               | [a446c446ae](https://linux-hardware.org/?probe=a446c446ae) | Aug 02, 2022 |
| Gigabyte      | H81M-DS2V                   | [0645ed0b9e](https://linux-hardware.org/?probe=0645ed0b9e) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | [f5e17ecf3d](https://linux-hardware.org/?probe=f5e17ecf3d) | Jul 31, 2022 |
| Gigabyte      | H77-DS3H                    | [a6889e4564](https://linux-hardware.org/?probe=a6889e4564) | Jul 31, 2022 |
| ASRock        | FM2A75M Pro4+               | [9cb3ed38a5](https://linux-hardware.org/?probe=9cb3ed38a5) | Jul 30, 2022 |
| Gigabyte      | H81M-HD3                    | [0f83741c2e](https://linux-hardware.org/?probe=0f83741c2e) | Jul 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [aa6ae1c12f](https://linux-hardware.org/?probe=aa6ae1c12f) | Jul 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [6d72261de7](https://linux-hardware.org/?probe=6d72261de7) | Jul 30, 2022 |
| Gigabyte      | G41MT-S2P                   | [ea545ae9ed](https://linux-hardware.org/?probe=ea545ae9ed) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [9194a07c08](https://linux-hardware.org/?probe=9194a07c08) | Jul 28, 2022 |
| Lenovo        | Dory CRB                    | [1aa1f63a2d](https://linux-hardware.org/?probe=1aa1f63a2d) | Jul 25, 2022 |
| Lenovo        | Dory CRB                    | [81e755d9a1](https://linux-hardware.org/?probe=81e755d9a1) | Jul 25, 2022 |
| Dell          | 054KM3 A00                  | [f84c50a2ae](https://linux-hardware.org/?probe=f84c50a2ae) | Jul 25, 2022 |
| Dell          | 054KM3 A00                  | [37fc6a278e](https://linux-hardware.org/?probe=37fc6a278e) | Jul 25, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| MSI           | X58 Pro-E                   | [a448d7e654](https://linux-hardware.org/?probe=a448d7e654) | Jul 21, 2022 |
| MSI           | X58 Pro-E                   | [af97aaa970](https://linux-hardware.org/?probe=af97aaa970) | Jul 21, 2022 |
| Dell          | 054KM3 A00                  | [228194fb04](https://linux-hardware.org/?probe=228194fb04) | Jul 21, 2022 |
| Dell          | 054KM3 A00                  | [406a93be76](https://linux-hardware.org/?probe=406a93be76) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| ASUSTek       | PRIME A320M-K               | [09a3fc75e9](https://linux-hardware.org/?probe=09a3fc75e9) | Jul 18, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [fcbd85f698](https://linux-hardware.org/?probe=fcbd85f698) | Jul 17, 2022 |
| ASUSTek       | M4A78                       | [d04747e05b](https://linux-hardware.org/?probe=d04747e05b) | Jul 17, 2022 |
| Dell          | 054KM3 A00                  | [2c14be3e6c](https://linux-hardware.org/?probe=2c14be3e6c) | Jul 17, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [391df88f80](https://linux-hardware.org/?probe=391df88f80) | Jul 17, 2022 |
| Dell          | 09KPNV A00                  | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| ASRock        | B365M Pro4                  | [5701f5019e](https://linux-hardware.org/?probe=5701f5019e) | Jul 13, 2022 |
| ASRock        | B450M Pro4                  | [0cdcc2c0e0](https://linux-hardware.org/?probe=0cdcc2c0e0) | Jul 10, 2022 |
| Dell          | 0UT806                      | [7d63f287bc](https://linux-hardware.org/?probe=7d63f287bc) | Jul 08, 2022 |
| Gigabyte      | B450M GAMING                | [b7cc7cee98](https://linux-hardware.org/?probe=b7cc7cee98) | Jul 05, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [64cb4f60fb](https://linux-hardware.org/?probe=64cb4f60fb) | Jul 04, 2022 |
| Dell          | 0C27VV A01                  | [bc4f34c375](https://linux-hardware.org/?probe=bc4f34c375) | Jul 04, 2022 |
| Dell          | 0C27VV A01                  | [03cd99ca9f](https://linux-hardware.org/?probe=03cd99ca9f) | Jul 04, 2022 |
| ASRock        | B365M Pro4                  | [8b2e08891d](https://linux-hardware.org/?probe=8b2e08891d) | Jul 03, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [98c7e055a3](https://linux-hardware.org/?probe=98c7e055a3) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ffde44eef6](https://linux-hardware.org/?probe=ffde44eef6) | Jul 02, 2022 |
| Gigabyte      | H61M-S1                     | [a38b0e0209](https://linux-hardware.org/?probe=a38b0e0209) | Jul 02, 2022 |
| Biostar       | TZ77XE3                     | [7b597af136](https://linux-hardware.org/?probe=7b597af136) | Jul 02, 2022 |
| ASUSTek       | P8H77-V LE                  | [0ecaca17cb](https://linux-hardware.org/?probe=0ecaca17cb) | Jun 30, 2022 |
| ASUSTek       | PRIME B460M-A               | [b63dffc595](https://linux-hardware.org/?probe=b63dffc595) | Jun 27, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [4889364145](https://linux-hardware.org/?probe=4889364145) | Jun 26, 2022 |
| Dell          | 0TY915                      | [d6faa2c9f1](https://linux-hardware.org/?probe=d6faa2c9f1) | Jun 25, 2022 |
| Lenovo        | ThinkServer TS440           | [e68364c28e](https://linux-hardware.org/?probe=e68364c28e) | Jun 24, 2022 |
| Gigabyte      | H410M S2 V2                 | [c37f67ba4b](https://linux-hardware.org/?probe=c37f67ba4b) | Jun 23, 2022 |
| HP            | 339A                        | [4f244ada14](https://linux-hardware.org/?probe=4f244ada14) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [7c094dc326](https://linux-hardware.org/?probe=7c094dc326) | Jun 19, 2022 |
| Lenovo        | ThinkServer TS440           | [42bf4b080d](https://linux-hardware.org/?probe=42bf4b080d) | Jun 19, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [3b5fb60639](https://linux-hardware.org/?probe=3b5fb60639) | Jun 19, 2022 |
| Intel         | X79 V2.72B                  | [fbd8e560b4](https://linux-hardware.org/?probe=fbd8e560b4) | Jun 18, 2022 |
| ASUSTek       | A7N8X2.0                    | [0078dfa592](https://linux-hardware.org/?probe=0078dfa592) | Jun 17, 2022 |
| Dell          | 0VD5HY A07                  | [6a66d72bc1](https://linux-hardware.org/?probe=6a66d72bc1) | Jun 14, 2022 |
| Dell          | 0VD5HY A07                  | [5d7c3bee0c](https://linux-hardware.org/?probe=5d7c3bee0c) | Jun 14, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [f57b643831](https://linux-hardware.org/?probe=f57b643831) | Jun 08, 2022 |
| Lenovo        | SDK0E50510 WIN              | [0c00fb9fe4](https://linux-hardware.org/?probe=0c00fb9fe4) | Jun 07, 2022 |
| Lenovo        | SDK0E50510 WIN              | [4b8eab59e2](https://linux-hardware.org/?probe=4b8eab59e2) | Jun 07, 2022 |
| Gigabyte      | H77N-WIFI                   | [a989dee1a0](https://linux-hardware.org/?probe=a989dee1a0) | Jun 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [63b4cd5c56](https://linux-hardware.org/?probe=63b4cd5c56) | Jun 05, 2022 |
| ASRock        | G41MH/USB3                  | [8cb0243666](https://linux-hardware.org/?probe=8cb0243666) | Jun 02, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a02283c272](https://linux-hardware.org/?probe=a02283c272) | Jun 01, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2bb0b663d7](https://linux-hardware.org/?probe=2bb0b663d7) | Jun 01, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | [254fda14c1](https://linux-hardware.org/?probe=254fda14c1) | May 30, 2022 |
| Gigabyte      | B450M GAMING                | [2f4ff624ba](https://linux-hardware.org/?probe=2f4ff624ba) | May 29, 2022 |
| Gigabyte      | B450M GAMING                | [726cb8d22e](https://linux-hardware.org/?probe=726cb8d22e) | May 29, 2022 |
| ASRock        | B450M-HDV R4.0              | [b6d663fde6](https://linux-hardware.org/?probe=b6d663fde6) | May 29, 2022 |
| Gigabyte      | H61M-S1                     | [444e61772c](https://linux-hardware.org/?probe=444e61772c) | May 29, 2022 |
| Gigabyte      | H61M-S1                     | [09b39cf91e](https://linux-hardware.org/?probe=09b39cf91e) | May 29, 2022 |
| Gigabyte      | H81M-S                      | [143b8e7ea9](https://linux-hardware.org/?probe=143b8e7ea9) | May 29, 2022 |
| Gigabyte      | G41MT-S2                    | [255d32d2b3](https://linux-hardware.org/?probe=255d32d2b3) | May 28, 2022 |
| ASUSTek       | P5Q DELUXE                  | [65bb3086df](https://linux-hardware.org/?probe=65bb3086df) | May 28, 2022 |
| ASUSTek       | P5Q DELUXE                  | [fcff479318](https://linux-hardware.org/?probe=fcff479318) | May 28, 2022 |
| Gigabyte      | B560M H                     | [7e17227514](https://linux-hardware.org/?probe=7e17227514) | May 27, 2022 |
| Gigabyte      | H61M-S1                     | [3db842adc9](https://linux-hardware.org/?probe=3db842adc9) | May 27, 2022 |
| Gigabyte      | A320M-S2H-CF                | [293f5586bd](https://linux-hardware.org/?probe=293f5586bd) | May 25, 2022 |
| Dell          | 0PU052                      | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| Lenovo        | SDK0E50510 WIN              | [1f8b067cca](https://linux-hardware.org/?probe=1f8b067cca) | May 23, 2022 |
| ASRock        | B365M Pro4-F                | [4cbbeda22c](https://linux-hardware.org/?probe=4cbbeda22c) | May 22, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [43d5dce3ee](https://linux-hardware.org/?probe=43d5dce3ee) | May 22, 2022 |
| Lenovo        | SDK0E50510 WIN              | [6efef2bd1e](https://linux-hardware.org/?probe=6efef2bd1e) | May 22, 2022 |
| ASRock        | A75M-ITX                    | [6287159bfa](https://linux-hardware.org/?probe=6287159bfa) | May 20, 2022 |
| JGINYUE       | X99M-PLUS V2 V2.0           | [de7a2328c3](https://linux-hardware.org/?probe=de7a2328c3) | May 20, 2022 |
| Lenovo        | SDK0E50510 WIN              | [0044468fc2](https://linux-hardware.org/?probe=0044468fc2) | May 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | [ae6f7ab64b](https://linux-hardware.org/?probe=ae6f7ab64b) | May 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [cf5954d738](https://linux-hardware.org/?probe=cf5954d738) | May 18, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [5995dc5192](https://linux-hardware.org/?probe=5995dc5192) | May 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [26837853fd](https://linux-hardware.org/?probe=26837853fd) | May 17, 2022 |
| Gigabyte      | H61M-S1                     | [153c3cb471](https://linux-hardware.org/?probe=153c3cb471) | May 16, 2022 |
| HP            | 1589                        | [fb9e076bb8](https://linux-hardware.org/?probe=fb9e076bb8) | May 15, 2022 |
| Lenovo        | ThinkServer TS440           | [bde3f15809](https://linux-hardware.org/?probe=bde3f15809) | May 15, 2022 |
| Unknown       | NF-MCP78                    | [0265fc0430](https://linux-hardware.org/?probe=0265fc0430) | May 14, 2022 |
| MSI           | B85M-P32                    | [9585181994](https://linux-hardware.org/?probe=9585181994) | May 14, 2022 |
| Gigabyte      | B450M GAMING                | [146d11b8f2](https://linux-hardware.org/?probe=146d11b8f2) | May 10, 2022 |
| Gigabyte      | B450M GAMING                | [6c4bf376bd](https://linux-hardware.org/?probe=6c4bf376bd) | May 10, 2022 |
| ASUSTek       | PRIME B365M-A               | [5a694d9de8](https://linux-hardware.org/?probe=5a694d9de8) | May 10, 2022 |
| ASUSTek       | PRIME B365M-A               | [af7f41e61f](https://linux-hardware.org/?probe=af7f41e61f) | May 10, 2022 |
| ASRock        | AB350 Pro4                  | [fdc78a778b](https://linux-hardware.org/?probe=fdc78a778b) | May 09, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | [f1bdc60827](https://linux-hardware.org/?probe=f1bdc60827) | May 08, 2022 |
| Gigabyte      | H61M-S1                     | [e4030c65d7](https://linux-hardware.org/?probe=e4030c65d7) | May 07, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4c4a006287](https://linux-hardware.org/?probe=4c4a006287) | May 07, 2022 |
| Intel         | X79 V2.72B                  | [87dd767f71](https://linux-hardware.org/?probe=87dd767f71) | May 05, 2022 |
| Gigabyte      | X48-DS5                     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| HP            | 1850                        | [1a2271c939](https://linux-hardware.org/?probe=1a2271c939) | May 01, 2022 |
| Dell          | 0TY915                      | [7de07e1186](https://linux-hardware.org/?probe=7de07e1186) | May 01, 2022 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [bb192229b3](https://linux-hardware.org/?probe=bb192229b3) | Apr 30, 2022 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | [a5ce52429c](https://linux-hardware.org/?probe=a5ce52429c) | Apr 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [af2b0de49b](https://linux-hardware.org/?probe=af2b0de49b) | Apr 29, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| ASUSTek       | B85M-E                      | [05896f4d55](https://linux-hardware.org/?probe=05896f4d55) | Apr 27, 2022 |
| ASUSTek       | B85M-E                      | [c4ccc166be](https://linux-hardware.org/?probe=c4ccc166be) | Apr 27, 2022 |
| ASRock        | FM2A75M Pro4+               | [0fc510a45a](https://linux-hardware.org/?probe=0fc510a45a) | Apr 26, 2022 |
| ASRock        | FM2A75M Pro4+               | [2ccbcae022](https://linux-hardware.org/?probe=2ccbcae022) | Apr 23, 2022 |
| ASRock        | FM2A75M Pro4+               | [ec77795911](https://linux-hardware.org/?probe=ec77795911) | Apr 23, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | [9b742eb785](https://linux-hardware.org/?probe=9b742eb785) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| HP            | 339A                        | [229032eb98](https://linux-hardware.org/?probe=229032eb98) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | [d624a31b69](https://linux-hardware.org/?probe=d624a31b69) | Apr 18, 2022 |
| ASRock        | ConRoe1333-D667             | [d2bba273a0](https://linux-hardware.org/?probe=d2bba273a0) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| ASUSTek       | M4A78 PRO                   | [9ed3f59682](https://linux-hardware.org/?probe=9ed3f59682) | Apr 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0dddcf5626](https://linux-hardware.org/?probe=0dddcf5626) | Apr 13, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [5e30e0e56d](https://linux-hardware.org/?probe=5e30e0e56d) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [67175f0019](https://linux-hardware.org/?probe=67175f0019) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | [c11ab04912](https://linux-hardware.org/?probe=c11ab04912) | Apr 12, 2022 |
| Dell          | 055H3G A01                  | [a41b7fbf00](https://linux-hardware.org/?probe=a41b7fbf00) | Apr 10, 2022 |
| ASRock        | Z270 Professional Gaming... | [9129317f19](https://linux-hardware.org/?probe=9129317f19) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3d91f855bc](https://linux-hardware.org/?probe=3d91f855bc) | Apr 09, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [6130d7e1e6](https://linux-hardware.org/?probe=6130d7e1e6) | Apr 09, 2022 |
| Gigabyte      | G41MT-S2PT                  | [7dde5fefd1](https://linux-hardware.org/?probe=7dde5fefd1) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b0840dd295](https://linux-hardware.org/?probe=b0840dd295) | Apr 09, 2022 |
| ASUSTek       | B85M-G                      | [c58e24cff5](https://linux-hardware.org/?probe=c58e24cff5) | Apr 07, 2022 |
| Gigabyte      | H87M-HD3                    | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| ASRock        | B85M                        | [5e03e9532d](https://linux-hardware.org/?probe=5e03e9532d) | Apr 04, 2022 |
| Gigabyte      | G41MT-S2PT                  | [9d1398934f](https://linux-hardware.org/?probe=9d1398934f) | Apr 04, 2022 |
| Gigabyte      | H61M-DS2                    | [10ccb633ee](https://linux-hardware.org/?probe=10ccb633ee) | Apr 04, 2022 |
| ASRock        | B75 Pro3                    | [01c8b92976](https://linux-hardware.org/?probe=01c8b92976) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [c338f4ffd4](https://linux-hardware.org/?probe=c338f4ffd4) | Mar 31, 2022 |
| HP            | 18E7                        | [4503b657fe](https://linux-hardware.org/?probe=4503b657fe) | Mar 30, 2022 |
| Gigabyte      | B450M GAMING                | [6cff18109b](https://linux-hardware.org/?probe=6cff18109b) | Mar 28, 2022 |
| Gigabyte      | B450M GAMING                | [b650c90413](https://linux-hardware.org/?probe=b650c90413) | Mar 28, 2022 |
| ASUSTek       | AM1M-A                      | [2f7bece339](https://linux-hardware.org/?probe=2f7bece339) | Mar 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [5d62943116](https://linux-hardware.org/?probe=5d62943116) | Mar 27, 2022 |
| Lenovo        | ThinkServer TS440           | [a356a33d0a](https://linux-hardware.org/?probe=a356a33d0a) | Mar 27, 2022 |
| Gigabyte      | H61M-D2-B3                  | [e807733708](https://linux-hardware.org/?probe=e807733708) | Mar 26, 2022 |
| Gigabyte      | H61M-D2-B3                  | [59df12dc12](https://linux-hardware.org/?probe=59df12dc12) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | [7e1b536f6b](https://linux-hardware.org/?probe=7e1b536f6b) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | [fd041828d0](https://linux-hardware.org/?probe=fd041828d0) | Mar 26, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d2e30b1d8b](https://linux-hardware.org/?probe=d2e30b1d8b) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [72e8662f26](https://linux-hardware.org/?probe=72e8662f26) | Mar 22, 2022 |
| ASRock        | FM2A75 Pro4+                | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| ASUSTek       | P5B                         | [0ec5966c98](https://linux-hardware.org/?probe=0ec5966c98) | Mar 21, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [399ab158b9](https://linux-hardware.org/?probe=399ab158b9) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [661d9fcffa](https://linux-hardware.org/?probe=661d9fcffa) | Mar 18, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [46af9af40c](https://linux-hardware.org/?probe=46af9af40c) | Mar 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [1b697ade27](https://linux-hardware.org/?probe=1b697ade27) | Mar 17, 2022 |
| ASUSTek       | Rampage III Extreme         | [6533ff3270](https://linux-hardware.org/?probe=6533ff3270) | Mar 16, 2022 |
| ASUSTek       | Rampage III Extreme         | [1e13431147](https://linux-hardware.org/?probe=1e13431147) | Mar 16, 2022 |
| HP            | 1589                        | [41622b6b2d](https://linux-hardware.org/?probe=41622b6b2d) | Mar 14, 2022 |
| HP            | 1589                        | [95af16db2e](https://linux-hardware.org/?probe=95af16db2e) | Mar 13, 2022 |
| Dell          | 0GM819                      | [e06d400f29](https://linux-hardware.org/?probe=e06d400f29) | Mar 13, 2022 |
| ASRock        | FM2A75M Pro4+               | [912b670e0f](https://linux-hardware.org/?probe=912b670e0f) | Mar 12, 2022 |
| ASRock        | FM2A75M Pro4+               | [64f83fa328](https://linux-hardware.org/?probe=64f83fa328) | Mar 12, 2022 |
| Acer          | Veriton M4610G              | [ec980460ed](https://linux-hardware.org/?probe=ec980460ed) | Mar 12, 2022 |
| Lenovo        | ThinkServer TS440           | [ec0e6e5114](https://linux-hardware.org/?probe=ec0e6e5114) | Mar 11, 2022 |
| Gigabyte      | H61M-S2PV                   | [71e8b113b4](https://linux-hardware.org/?probe=71e8b113b4) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | [0148e15f51](https://linux-hardware.org/?probe=0148e15f51) | Mar 09, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [5b31db42d4](https://linux-hardware.org/?probe=5b31db42d4) | Mar 08, 2022 |
| HP            | 1589                        | [eceb34c7fa](https://linux-hardware.org/?probe=eceb34c7fa) | Mar 08, 2022 |
| Lenovo        | Dory CRB                    | [e8cfaeca24](https://linux-hardware.org/?probe=e8cfaeca24) | Mar 08, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | [8dcdbb2b22](https://linux-hardware.org/?probe=8dcdbb2b22) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [378234e501](https://linux-hardware.org/?probe=378234e501) | Mar 07, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [3cb51f5689](https://linux-hardware.org/?probe=3cb51f5689) | Mar 04, 2022 |
| Gigabyte      | B450M S2H V2                | [000ae29fb1](https://linux-hardware.org/?probe=000ae29fb1) | Mar 03, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [3d54b5db38](https://linux-hardware.org/?probe=3d54b5db38) | Mar 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [eb3d721453](https://linux-hardware.org/?probe=eb3d721453) | Mar 02, 2022 |
| Gigabyte      | H61M-D2-B3                  | [ad003c1394](https://linux-hardware.org/?probe=ad003c1394) | Mar 02, 2022 |
| Gigabyte      | H61M-D2-B3                  | [8225572009](https://linux-hardware.org/?probe=8225572009) | Mar 02, 2022 |
| ASRock        | B450M Pro4                  | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| HP            | 339A                        | [59d197fac4](https://linux-hardware.org/?probe=59d197fac4) | Mar 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a94729eaf7](https://linux-hardware.org/?probe=a94729eaf7) | Mar 01, 2022 |
| ASUSTek       | B75M-PLUS                   | [e479ffd9d5](https://linux-hardware.org/?probe=e479ffd9d5) | Feb 27, 2022 |
| ASUSTek       | B75M-PLUS                   | [96e4cf1606](https://linux-hardware.org/?probe=96e4cf1606) | Feb 27, 2022 |
| ASUSTek       | P5QC                        | [8d2d104db6](https://linux-hardware.org/?probe=8d2d104db6) | Feb 26, 2022 |
| HP            | 3396                        | [c9cce866c4](https://linux-hardware.org/?probe=c9cce866c4) | Feb 25, 2022 |
| Gigabyte      | B450M H                     | [fbed153592](https://linux-hardware.org/?probe=fbed153592) | Feb 25, 2022 |
| Gigabyte      | MCMLUCB-00                  | [d2bce2bda0](https://linux-hardware.org/?probe=d2bce2bda0) | Feb 25, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [e1284695f2](https://linux-hardware.org/?probe=e1284695f2) | Feb 24, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [c7c60ad7ac](https://linux-hardware.org/?probe=c7c60ad7ac) | Feb 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [9d9c4fe241](https://linux-hardware.org/?probe=9d9c4fe241) | Feb 23, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [84b8eefa6d](https://linux-hardware.org/?probe=84b8eefa6d) | Feb 23, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [4b90c1398d](https://linux-hardware.org/?probe=4b90c1398d) | Feb 23, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [ee84460851](https://linux-hardware.org/?probe=ee84460851) | Feb 20, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [158e5bd3bb](https://linux-hardware.org/?probe=158e5bd3bb) | Feb 20, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1ddb502787](https://linux-hardware.org/?probe=1ddb502787) | Feb 19, 2022 |
| ASRock        | 970 Pro3 R2.0               | [fde5d3aa86](https://linux-hardware.org/?probe=fde5d3aa86) | Feb 19, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [7ecf132718](https://linux-hardware.org/?probe=7ecf132718) | Feb 19, 2022 |
| Gigabyte      | Z68MX-UD2H-B3               | [4ee5a962df](https://linux-hardware.org/?probe=4ee5a962df) | Feb 18, 2022 |
| Gigabyte      | B85M-D3H                    | [7b5e16621e](https://linux-hardware.org/?probe=7b5e16621e) | Feb 18, 2022 |
| Gigabyte      | B85M-D3H                    | [85a5aca2eb](https://linux-hardware.org/?probe=85a5aca2eb) | Feb 18, 2022 |
| Medion        | MS-7748                     | [0f9283e5e9](https://linux-hardware.org/?probe=0f9283e5e9) | Feb 17, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [8b373bbfec](https://linux-hardware.org/?probe=8b373bbfec) | Feb 17, 2022 |
| Medion        | MS-7748                     | [72e17bd510](https://linux-hardware.org/?probe=72e17bd510) | Feb 17, 2022 |
| HP            | 2820h                       | [ecf8b8bc60](https://linux-hardware.org/?probe=ecf8b8bc60) | Feb 17, 2022 |
| HP            | 2820h                       | [89f7abcbf4](https://linux-hardware.org/?probe=89f7abcbf4) | Feb 17, 2022 |
| MSI           | B85M-P32                    | [e0a962d224](https://linux-hardware.org/?probe=e0a962d224) | Feb 15, 2022 |
| ASRock        | B550M Pro4                  | [5897907111](https://linux-hardware.org/?probe=5897907111) | Feb 15, 2022 |
| ASUSTek       | Crosshair IV Formula        | [f33f7c184e](https://linux-hardware.org/?probe=f33f7c184e) | Feb 14, 2022 |
| MSI           | H61M-P20                    | [63dbb68d31](https://linux-hardware.org/?probe=63dbb68d31) | Feb 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [3d320cc4d6](https://linux-hardware.org/?probe=3d320cc4d6) | Feb 13, 2022 |
| MSI           | H61M-P20                    | [d0996e1c65](https://linux-hardware.org/?probe=d0996e1c65) | Feb 13, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [7968062d45](https://linux-hardware.org/?probe=7968062d45) | Feb 13, 2022 |
| Intel         | DG45ID AAE27729-308         | [91f90c2997](https://linux-hardware.org/?probe=91f90c2997) | Feb 12, 2022 |
| ASRock        | B550M Pro4                  | [18b9c160a9](https://linux-hardware.org/?probe=18b9c160a9) | Feb 12, 2022 |
| Gigabyte      | AB350M-D3H-CF               | [406bd79f86](https://linux-hardware.org/?probe=406bd79f86) | Feb 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | [4a05dcdd20](https://linux-hardware.org/?probe=4a05dcdd20) | Feb 11, 2022 |
| MSI           | MS-7253                     | [c6d4e8933e](https://linux-hardware.org/?probe=c6d4e8933e) | Feb 10, 2022 |
| MSI           | MS-7253                     | [ee60e146a7](https://linux-hardware.org/?probe=ee60e146a7) | Feb 10, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [b56694aaf5](https://linux-hardware.org/?probe=b56694aaf5) | Feb 09, 2022 |
| Gigabyte      | H310M H x.x                 | [1ca3e5ad44](https://linux-hardware.org/?probe=1ca3e5ad44) | Feb 08, 2022 |
| Dell          | 0GM819                      | [473d90da33](https://linux-hardware.org/?probe=473d90da33) | Feb 08, 2022 |
| Gigabyte      | H110M-S2V-CF                | [f424a1b3be](https://linux-hardware.org/?probe=f424a1b3be) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [a76a47a11f](https://linux-hardware.org/?probe=a76a47a11f) | Feb 07, 2022 |
| HP            | 0A64h                       | [98ed15aae2](https://linux-hardware.org/?probe=98ed15aae2) | Feb 07, 2022 |
| HP            | 0A64h                       | [668921361e](https://linux-hardware.org/?probe=668921361e) | Feb 07, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [071fcc6209](https://linux-hardware.org/?probe=071fcc6209) | Feb 07, 2022 |
| HP            | 805D                        | [c60a6bdbbe](https://linux-hardware.org/?probe=c60a6bdbbe) | Feb 07, 2022 |
| HP            | 805D                        | [c744f9c342](https://linux-hardware.org/?probe=c744f9c342) | Feb 07, 2022 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [43f1fc6098](https://linux-hardware.org/?probe=43f1fc6098) | Feb 06, 2022 |
| HP            | 843C                        | [65121c676e](https://linux-hardware.org/?probe=65121c676e) | Feb 06, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [f45c4ae60c](https://linux-hardware.org/?probe=f45c4ae60c) | Feb 05, 2022 |
| ASRock        | G31M-S                      | [2b4d2d640f](https://linux-hardware.org/?probe=2b4d2d640f) | Feb 05, 2022 |
| Gigabyte      | H81M-S                      | [2f6399fd27](https://linux-hardware.org/?probe=2f6399fd27) | Feb 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [548f756c0e](https://linux-hardware.org/?probe=548f756c0e) | Feb 04, 2022 |
| Unknown       | Unknown                     | [f9a64bf682](https://linux-hardware.org/?probe=f9a64bf682) | Feb 04, 2022 |
| HP            | 805D                        | [a1c655471b](https://linux-hardware.org/?probe=a1c655471b) | Feb 04, 2022 |
| HP            | 805D                        | [1d5437358e](https://linux-hardware.org/?probe=1d5437358e) | Feb 04, 2022 |
| Unknown       | Unknown                     | [e4e8e488a2](https://linux-hardware.org/?probe=e4e8e488a2) | Feb 04, 2022 |
| HP            | 2820h                       | [29ca2cd67e](https://linux-hardware.org/?probe=29ca2cd67e) | Feb 04, 2022 |
| HP            | 2820h                       | [81782756a3](https://linux-hardware.org/?probe=81782756a3) | Feb 04, 2022 |
| ASUSTek       | VM40B                       | [81ae77ad68](https://linux-hardware.org/?probe=81ae77ad68) | Feb 03, 2022 |
| ASUSTek       | VM40B                       | [3f29251c4f](https://linux-hardware.org/?probe=3f29251c4f) | Feb 03, 2022 |
| Gigabyte      | P67A-D3-B3                  | [e490dd8875](https://linux-hardware.org/?probe=e490dd8875) | Feb 02, 2022 |
| ASUSTek       | AM1M-A                      | [7967848128](https://linux-hardware.org/?probe=7967848128) | Feb 01, 2022 |
| Lenovo        | NOK                         | [fbc8b16f78](https://linux-hardware.org/?probe=fbc8b16f78) | Feb 01, 2022 |
| ASRock        | H170M Pro4S                 | [efb4e3254e](https://linux-hardware.org/?probe=efb4e3254e) | Jan 31, 2022 |
| HP            | 18E7                        | [fb9b13b49b](https://linux-hardware.org/?probe=fb9b13b49b) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fc9ddc34b0](https://linux-hardware.org/?probe=fc9ddc34b0) | Jan 30, 2022 |
| Gigabyte      | P35-S3G                     | [21f5490cc5](https://linux-hardware.org/?probe=21f5490cc5) | Jan 30, 2022 |
| Gigabyte      | B150M-D3H-CF                | [ab6c348741](https://linux-hardware.org/?probe=ab6c348741) | Jan 30, 2022 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [88218319a7](https://linux-hardware.org/?probe=88218319a7) | Jan 30, 2022 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [1ddd377c2c](https://linux-hardware.org/?probe=1ddd377c2c) | Jan 30, 2022 |
| Lenovo        | Dory CRB                    | [6c48175227](https://linux-hardware.org/?probe=6c48175227) | Jan 30, 2022 |
| Gigabyte      | H61M-D2-B3                  | [19f3d984b0](https://linux-hardware.org/?probe=19f3d984b0) | Jan 30, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [c5e9f1b68c](https://linux-hardware.org/?probe=c5e9f1b68c) | Jan 29, 2022 |
| Lenovo        | ThinkServer TS440           | [eaef3cbdab](https://linux-hardware.org/?probe=eaef3cbdab) | Jan 29, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| Dell          | 02YYK5 A00                  | [af828f5f84](https://linux-hardware.org/?probe=af828f5f84) | Jan 26, 2022 |
| ASRock        | H170M Pro4S                 | [0c900f67d0](https://linux-hardware.org/?probe=0c900f67d0) | Jan 26, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [781a92f9a4](https://linux-hardware.org/?probe=781a92f9a4) | Jan 26, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [205214c3d2](https://linux-hardware.org/?probe=205214c3d2) | Jan 26, 2022 |
| Dell          | 02YYK5 A00                  | [d357a59431](https://linux-hardware.org/?probe=d357a59431) | Jan 26, 2022 |
| Unknown       | Unknown                     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| Medion        | MS-7748                     | [859e4baa04](https://linux-hardware.org/?probe=859e4baa04) | Jan 24, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [b1cfd38100](https://linux-hardware.org/?probe=b1cfd38100) | Jan 23, 2022 |
| ASUSTek       | P8B75-M LX                  | [dc2c32aac2](https://linux-hardware.org/?probe=dc2c32aac2) | Jan 23, 2022 |
| ASUSTek       | VM40B                       | [35ab4cf978](https://linux-hardware.org/?probe=35ab4cf978) | Jan 22, 2022 |
| MSI           | B150M ECO                   | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| Lenovo        | ThinkServer TS440           | [b736a56c19](https://linux-hardware.org/?probe=b736a56c19) | Jan 21, 2022 |
| Lenovo        | ThinkServer TS440           | [1f5146de0a](https://linux-hardware.org/?probe=1f5146de0a) | Jan 21, 2022 |
| HP            | 3647h                       | [8c83ed4e1a](https://linux-hardware.org/?probe=8c83ed4e1a) | Jan 21, 2022 |
| ASUSTek       | VM40B                       | [64aa40b399](https://linux-hardware.org/?probe=64aa40b399) | Jan 21, 2022 |
| Gigabyte      | P35-S3G                     | [64049e547a](https://linux-hardware.org/?probe=64049e547a) | Jan 21, 2022 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [918378014c](https://linux-hardware.org/?probe=918378014c) | Jan 21, 2022 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [d258269f4e](https://linux-hardware.org/?probe=d258269f4e) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| HP            | 3647h                       | [b393fe2f3a](https://linux-hardware.org/?probe=b393fe2f3a) | Jan 19, 2022 |
| HP            | 3029h                       | [21048ac4b2](https://linux-hardware.org/?probe=21048ac4b2) | Jan 19, 2022 |
| Gigabyte      | H61M-S2PV                   | [330f414282](https://linux-hardware.org/?probe=330f414282) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | [a28c50c71f](https://linux-hardware.org/?probe=a28c50c71f) | Jan 17, 2022 |
| MSI           | 890GXM-G65                  | [62c8eab51c](https://linux-hardware.org/?probe=62c8eab51c) | Jan 16, 2022 |
| MSI           | X570-A PRO                  | [acd5f363d7](https://linux-hardware.org/?probe=acd5f363d7) | Jan 16, 2022 |
| MSI           | 890GXM-G65                  | [e59fd1ba13](https://linux-hardware.org/?probe=e59fd1ba13) | Jan 16, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [fe9b500730](https://linux-hardware.org/?probe=fe9b500730) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [a3711dfcf9](https://linux-hardware.org/?probe=a3711dfcf9) | Jan 15, 2022 |
| Lenovo        | 0B98401 PRO                 | [c973a9bc0d](https://linux-hardware.org/?probe=c973a9bc0d) | Jan 15, 2022 |
| Lenovo        | ThinkServer TS440           | [bae7c1cd50](https://linux-hardware.org/?probe=bae7c1cd50) | Jan 15, 2022 |
| ASRock        | G31M-VS                     | [016c34dc7a](https://linux-hardware.org/?probe=016c34dc7a) | Jan 13, 2022 |
| ASRock        | G31M-VS                     | [c9d6ddaddc](https://linux-hardware.org/?probe=c9d6ddaddc) | Jan 13, 2022 |
| Gigabyte      | H77N-WIFI                   | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| Medion        | MS-7748                     | [a5a11345ba](https://linux-hardware.org/?probe=a5a11345ba) | Jan 12, 2022 |
| ASRock        | G41M-VS3                    | [8709398c0f](https://linux-hardware.org/?probe=8709398c0f) | Jan 11, 2022 |
| ASRock        | G41M-VS3                    | [9915e534b9](https://linux-hardware.org/?probe=9915e534b9) | Jan 11, 2022 |
| ASRock        | G31M-VS                     | [cbf7421335](https://linux-hardware.org/?probe=cbf7421335) | Jan 11, 2022 |
| Medion        | MS-7646                     | [9bc224fcf4](https://linux-hardware.org/?probe=9bc224fcf4) | Jan 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c2c5bfd879](https://linux-hardware.org/?probe=c2c5bfd879) | Jan 10, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [d3117e8b94](https://linux-hardware.org/?probe=d3117e8b94) | Jan 10, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [2a515d8620](https://linux-hardware.org/?probe=2a515d8620) | Jan 10, 2022 |
| ASUSTek       | PRIME B460M-A               | [34fad0ad77](https://linux-hardware.org/?probe=34fad0ad77) | Jan 09, 2022 |
| ASRock        | B450 Pro4                   | [56ebb4b643](https://linux-hardware.org/?probe=56ebb4b643) | Jan 09, 2022 |
| Unknown       | NF-MCP78                    | [b1cca5c515](https://linux-hardware.org/?probe=b1cca5c515) | Jan 06, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [4af527ae61](https://linux-hardware.org/?probe=4af527ae61) | Jan 05, 2022 |
| Gigabyte      | B450M GAMING                | [0c8a502a11](https://linux-hardware.org/?probe=0c8a502a11) | Jan 04, 2022 |
| Intel         | HURONRIVER                  | [85b441d7cb](https://linux-hardware.org/?probe=85b441d7cb) | Jan 04, 2022 |
| ASUSTek       | B85M-E                      | [6ef9b69e18](https://linux-hardware.org/?probe=6ef9b69e18) | Jan 04, 2022 |
| ASUSTek       | B85M-E                      | [c2d49cd216](https://linux-hardware.org/?probe=c2d49cd216) | Jan 04, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [50551cf5c6](https://linux-hardware.org/?probe=50551cf5c6) | Jan 03, 2022 |
| Gigabyte      | H310M H x.x                 | [45f7689f8d](https://linux-hardware.org/?probe=45f7689f8d) | Jan 03, 2022 |
| HP            | 2215                        | [e3e3c6590f](https://linux-hardware.org/?probe=e3e3c6590f) | Jan 02, 2022 |
| Acer          | RS880M05                    | [6d398453c9](https://linux-hardware.org/?probe=6d398453c9) | Jan 02, 2022 |
| Gigabyte      | H61M-S2PV                   | [f527f05637](https://linux-hardware.org/?probe=f527f05637) | Jan 02, 2022 |
| HP            | 3029h                       | [94547ef9f8](https://linux-hardware.org/?probe=94547ef9f8) | Jan 01, 2022 |
| MSI           | H61M-P31/W8                 | [4c7df047c4](https://linux-hardware.org/?probe=4c7df047c4) | Jan 01, 2022 |
| Gigabyte      | H87-HD3                     | [f25dd3b960](https://linux-hardware.org/?probe=f25dd3b960) | Dec 31, 2021 |
| ASUSTek       | H110M-A/M.2                 | [667da7e2b7](https://linux-hardware.org/?probe=667da7e2b7) | Dec 31, 2021 |
| ASUSTek       | H110M-A/M.2                 | [8d180dcd18](https://linux-hardware.org/?probe=8d180dcd18) | Dec 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | [9c9af63993](https://linux-hardware.org/?probe=9c9af63993) | Dec 30, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [649d41e3f8](https://linux-hardware.org/?probe=649d41e3f8) | Dec 29, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | [4d94e6a36c](https://linux-hardware.org/?probe=4d94e6a36c) | Dec 29, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [3b7ee11eda](https://linux-hardware.org/?probe=3b7ee11eda) | Dec 29, 2021 |
| Lenovo        | Dory CRB                    | [b5d2b24d12](https://linux-hardware.org/?probe=b5d2b24d12) | Dec 29, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [01bfccb835](https://linux-hardware.org/?probe=01bfccb835) | Dec 29, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [a3af4e5057](https://linux-hardware.org/?probe=a3af4e5057) | Dec 28, 2021 |
| ASRock        | 4Core1600P35-WiFi+          | [bae2ef5b28](https://linux-hardware.org/?probe=bae2ef5b28) | Dec 28, 2021 |
| Medion        | MS-7646                     | [ab5dc2c634](https://linux-hardware.org/?probe=ab5dc2c634) | Dec 27, 2021 |
| Lenovo        | No DPK                      | [373571fe93](https://linux-hardware.org/?probe=373571fe93) | Dec 27, 2021 |
| Lenovo        | No DPK                      | [393b6187f9](https://linux-hardware.org/?probe=393b6187f9) | Dec 27, 2021 |
| Gigabyte      | Z97-HD3                     | [8768948189](https://linux-hardware.org/?probe=8768948189) | Dec 26, 2021 |
| Gigabyte      | EG41MF-US2H                 | [82d9c23e0a](https://linux-hardware.org/?probe=82d9c23e0a) | Dec 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [c62bd7f367](https://linux-hardware.org/?probe=c62bd7f367) | Dec 25, 2021 |
| Gigabyte      | G31M-S2L                    | [4c00491c87](https://linux-hardware.org/?probe=4c00491c87) | Dec 25, 2021 |
| Dell          | 0M858N A01                  | [ecc633d588](https://linux-hardware.org/?probe=ecc633d588) | Dec 24, 2021 |
| Dell          | 0M858N A01                  | [3889da20c0](https://linux-hardware.org/?probe=3889da20c0) | Dec 23, 2021 |
| Dell          | 0M858N A01                  | [5f084eff7c](https://linux-hardware.org/?probe=5f084eff7c) | Dec 23, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [db48e82f65](https://linux-hardware.org/?probe=db48e82f65) | Dec 23, 2021 |
| ASUSTek       | PRIME A320M-K               | [9820c373d7](https://linux-hardware.org/?probe=9820c373d7) | Dec 23, 2021 |
| Gigabyte      | P67A-D3-B3                  | [8d4aef89ae](https://linux-hardware.org/?probe=8d4aef89ae) | Dec 22, 2021 |
| ASUSTek       | PRIME A320M-K               | [c09ffa2786](https://linux-hardware.org/?probe=c09ffa2786) | Dec 22, 2021 |
| Dell          | 0XPDFK A00                  | [5c8f9aee8c](https://linux-hardware.org/?probe=5c8f9aee8c) | Dec 21, 2021 |
| Dell          | 0XPDFK A00                  | [1ed5e7631a](https://linux-hardware.org/?probe=1ed5e7631a) | Dec 21, 2021 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [e6d6c1a347](https://linux-hardware.org/?probe=e6d6c1a347) | Dec 21, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [02ccd7fb7d](https://linux-hardware.org/?probe=02ccd7fb7d) | Dec 21, 2021 |
| ASRock        | B365M Pro4                  | [96a31c2b3c](https://linux-hardware.org/?probe=96a31c2b3c) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [75bff2c415](https://linux-hardware.org/?probe=75bff2c415) | Dec 20, 2021 |
| ASRock        | H170M Pro4S                 | [bcd4acf346](https://linux-hardware.org/?probe=bcd4acf346) | Dec 20, 2021 |
| HP            | 1905                        | [e153d159bf](https://linux-hardware.org/?probe=e153d159bf) | Dec 20, 2021 |
| Gigabyte      | H81M-S1                     | [389e039b0e](https://linux-hardware.org/?probe=389e039b0e) | Dec 19, 2021 |
| ASRock        | G31M-VS                     | [af2a2e4db9](https://linux-hardware.org/?probe=af2a2e4db9) | Dec 19, 2021 |
| ASUSTek       | PRIME B460M-A               | [c2f0152b2b](https://linux-hardware.org/?probe=c2f0152b2b) | Dec 19, 2021 |
| Gigabyte      | H87M-HD3                    | [906e50ad1d](https://linux-hardware.org/?probe=906e50ad1d) | Dec 19, 2021 |
| Acer          | Veriton M4630G V:1.0        | [e17d64b34b](https://linux-hardware.org/?probe=e17d64b34b) | Dec 18, 2021 |
| ASUSTek       | P5B-MX/WiFi-AP              | [97a556a1b1](https://linux-hardware.org/?probe=97a556a1b1) | Dec 18, 2021 |
| Acer          | Veriton M4630G V:1.0        | [e91c344097](https://linux-hardware.org/?probe=e91c344097) | Dec 18, 2021 |
| ASRock        | AM1B-ITX                    | [e66952c0c4](https://linux-hardware.org/?probe=e66952c0c4) | Dec 18, 2021 |
| Lenovo        | Dory CRB                    | [a6f93a8b7f](https://linux-hardware.org/?probe=a6f93a8b7f) | Dec 17, 2021 |
| Gigabyte      | A520M S2H                   | [c266bd78d7](https://linux-hardware.org/?probe=c266bd78d7) | Dec 17, 2021 |
| Gigabyte      | A520M S2H                   | [b23ba421f5](https://linux-hardware.org/?probe=b23ba421f5) | Dec 17, 2021 |
| Foxconn       | 2ABF                        | [a27e441ee7](https://linux-hardware.org/?probe=a27e441ee7) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Foxconn       | 2ABF                        | [eb78990a42](https://linux-hardware.org/?probe=eb78990a42) | Dec 17, 2021 |
| MSI           | B460M-A PRO                 | [5cd26fcd62](https://linux-hardware.org/?probe=5cd26fcd62) | Dec 15, 2021 |
| MSI           | B460M-A PRO                 | [eb08e1c888](https://linux-hardware.org/?probe=eb08e1c888) | Dec 15, 2021 |
| ASRock        | FM2A75M Pro4+               | [88d54712f5](https://linux-hardware.org/?probe=88d54712f5) | Dec 15, 2021 |
| ASRock        | B450M Pro4                  | [83f2efe2b5](https://linux-hardware.org/?probe=83f2efe2b5) | Dec 15, 2021 |
| ASRock        | AM1B-ITX                    | [7b567d7211](https://linux-hardware.org/?probe=7b567d7211) | Dec 14, 2021 |
| Gigabyte      | P67A-D3-B3                  | [481ac9664e](https://linux-hardware.org/?probe=481ac9664e) | Dec 14, 2021 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [3760c1b2c2](https://linux-hardware.org/?probe=3760c1b2c2) | Dec 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [f03b1893e9](https://linux-hardware.org/?probe=f03b1893e9) | Dec 14, 2021 |
| Dell          | 0KP561                      | [a39e88c6a1](https://linux-hardware.org/?probe=a39e88c6a1) | Dec 14, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | [79238447b1](https://linux-hardware.org/?probe=79238447b1) | Dec 14, 2021 |
| ASRock        | B450M Pro4-F                | [ffca94642e](https://linux-hardware.org/?probe=ffca94642e) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASRock        | FM2A75M Pro4+               | [bb9e6067a6](https://linux-hardware.org/?probe=bb9e6067a6) | Dec 12, 2021 |
| ASRock        | FM2A75M Pro4+               | [06bcf3473b](https://linux-hardware.org/?probe=06bcf3473b) | Dec 12, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [de13fff449](https://linux-hardware.org/?probe=de13fff449) | Dec 08, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [782e5be1e8](https://linux-hardware.org/?probe=782e5be1e8) | Dec 08, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [82e5fa3606](https://linux-hardware.org/?probe=82e5fa3606) | Dec 08, 2021 |
| Lenovo        | ThinkCentre M57 6081A86     | [74828f0e8c](https://linux-hardware.org/?probe=74828f0e8c) | Dec 06, 2021 |
| ASUSTek       | P5QL PRO                    | [fb041fdb69](https://linux-hardware.org/?probe=fb041fdb69) | Dec 05, 2021 |
| Foxconn       | 2ABF                        | [6f668098a9](https://linux-hardware.org/?probe=6f668098a9) | Dec 05, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [d9f0e2da32](https://linux-hardware.org/?probe=d9f0e2da32) | Dec 05, 2021 |
| Fujitsu       | D3313-S6 S26361-D3313-S6    | [40d466140f](https://linux-hardware.org/?probe=40d466140f) | Dec 03, 2021 |
| Gigabyte      | H87M-HD3                    | [4624f9164d](https://linux-hardware.org/?probe=4624f9164d) | Dec 02, 2021 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [a9ef047f21](https://linux-hardware.org/?probe=a9ef047f21) | Dec 02, 2021 |
| Gigabyte      | G41MT-S2PT                  | [77e63c266d](https://linux-hardware.org/?probe=77e63c266d) | Dec 02, 2021 |
| Foxconn       | 2ABF                        | [f194eb6d68](https://linux-hardware.org/?probe=f194eb6d68) | Dec 01, 2021 |
| ASRock        | FM2A75M Pro4+               | [ca55fa2fac](https://linux-hardware.org/?probe=ca55fa2fac) | Nov 30, 2021 |
| ASUSTek       | P5B-PLUS Series             | [ab546ec9e3](https://linux-hardware.org/?probe=ab546ec9e3) | Nov 30, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [e065a179a8](https://linux-hardware.org/?probe=e065a179a8) | Nov 30, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [fd4ce799f3](https://linux-hardware.org/?probe=fd4ce799f3) | Nov 30, 2021 |
| ASUSTek       | P5B-PLUS Series             | [7ac4ce7fff](https://linux-hardware.org/?probe=7ac4ce7fff) | Nov 30, 2021 |
| Medion        | MS-7646                     | [44d5c45bcb](https://linux-hardware.org/?probe=44d5c45bcb) | Nov 29, 2021 |
| ASRock        | G31M-VS                     | [b042297ea5](https://linux-hardware.org/?probe=b042297ea5) | Nov 29, 2021 |
| ASUSTek       | H81M-D                      | [b08d192653](https://linux-hardware.org/?probe=b08d192653) | Nov 28, 2021 |
| ASUSTek       | H81M-D                      | [822d1d4f8c](https://linux-hardware.org/?probe=822d1d4f8c) | Nov 28, 2021 |
| Gigabyte      | H87-HD3                     | [82c0604f4c](https://linux-hardware.org/?probe=82c0604f4c) | Nov 28, 2021 |
| Minix         | D2700-HD V1.0               | [53f8729986](https://linux-hardware.org/?probe=53f8729986) | Nov 28, 2021 |
| Dell          | 0K240Y A01                  | [db19440955](https://linux-hardware.org/?probe=db19440955) | Nov 27, 2021 |
| HP            | 339A                        | [e12ad89244](https://linux-hardware.org/?probe=e12ad89244) | Nov 27, 2021 |
| HP            | 339A                        | [94bb470b5e](https://linux-hardware.org/?probe=94bb470b5e) | Nov 27, 2021 |
| ASRock        | A75M-ITX                    | [4b8d23a09d](https://linux-hardware.org/?probe=4b8d23a09d) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [29efd53713](https://linux-hardware.org/?probe=29efd53713) | Nov 23, 2021 |
| HP            | 805D                        | [38636001e3](https://linux-hardware.org/?probe=38636001e3) | Nov 22, 2021 |
| Gigabyte      | H510M H                     | [0c1d0d8398](https://linux-hardware.org/?probe=0c1d0d8398) | Nov 22, 2021 |
| Medion        | MS-7748                     | [76cc89176e](https://linux-hardware.org/?probe=76cc89176e) | Nov 22, 2021 |
| Medion        | MS-7748                     | [acf3d75c25](https://linux-hardware.org/?probe=acf3d75c25) | Nov 22, 2021 |
| ASRock        | ION3D-HT                    | [915f7c5918](https://linux-hardware.org/?probe=915f7c5918) | Nov 21, 2021 |
| ASRock        | ION3D-HT                    | [2ca36fa3fc](https://linux-hardware.org/?probe=2ca36fa3fc) | Nov 21, 2021 |
| Dell          | 0GY6Y8 A01                  | [341c878a77](https://linux-hardware.org/?probe=341c878a77) | Nov 21, 2021 |
| ASRock        | B85M Pro4                   | [b628dc0d86](https://linux-hardware.org/?probe=b628dc0d86) | Nov 21, 2021 |
| ASRock        | B85M Pro4                   | [0000384b9e](https://linux-hardware.org/?probe=0000384b9e) | Nov 20, 2021 |
| ASUSTek       | P5PL2-E                     | [00ec0123c5](https://linux-hardware.org/?probe=00ec0123c5) | Nov 20, 2021 |
| ASUSTek       | M2N                         | [cc4cf29780](https://linux-hardware.org/?probe=cc4cf29780) | Nov 20, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ad117f68b3](https://linux-hardware.org/?probe=ad117f68b3) | Nov 20, 2021 |
| ASUSTek       | P5PL2-E                     | [12db2d9ccc](https://linux-hardware.org/?probe=12db2d9ccc) | Nov 19, 2021 |
| Gigabyte      | B450M S2H                   | [7781307d3c](https://linux-hardware.org/?probe=7781307d3c) | Nov 18, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [050f65927b](https://linux-hardware.org/?probe=050f65927b) | Nov 17, 2021 |
| Gigabyte      | B150M-HD3-CF                | [c35117afe2](https://linux-hardware.org/?probe=c35117afe2) | Nov 17, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [a809aa1e3c](https://linux-hardware.org/?probe=a809aa1e3c) | Nov 17, 2021 |
| HP            | 304Bh                       | [0983c3daf2](https://linux-hardware.org/?probe=0983c3daf2) | Nov 16, 2021 |
| ASUSTek       | PRIME A320M-R               | [2932e00969](https://linux-hardware.org/?probe=2932e00969) | Nov 15, 2021 |
| HP            | 3047h                       | [13eea6a00c](https://linux-hardware.org/?probe=13eea6a00c) | Nov 15, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| ASRock        | FM2A88X Extreme4+           | [fed47693de](https://linux-hardware.org/?probe=fed47693de) | Nov 14, 2021 |
| Fujitsu Si... | D1561 S26361-D1561          | [8bbf7045eb](https://linux-hardware.org/?probe=8bbf7045eb) | Nov 13, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [57d648d573](https://linux-hardware.org/?probe=57d648d573) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9234274a5e](https://linux-hardware.org/?probe=9234274a5e) | Nov 11, 2021 |
| ASUSTek       | H110-PLUS                   | [a6bfcee068](https://linux-hardware.org/?probe=a6bfcee068) | Nov 11, 2021 |
| ASUSTek       | H110-PLUS                   | [e50d021703](https://linux-hardware.org/?probe=e50d021703) | Nov 11, 2021 |
| Gigabyte      | H110M-S2H-CF                | [a180319758](https://linux-hardware.org/?probe=a180319758) | Nov 08, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [6f5959b193](https://linux-hardware.org/?probe=6f5959b193) | Nov 08, 2021 |
| ASRock        | B365M Pro4                  | [ed60292a3d](https://linux-hardware.org/?probe=ed60292a3d) | Nov 08, 2021 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [fd49440f09](https://linux-hardware.org/?probe=fd49440f09) | Nov 06, 2021 |
| Dell          | 0HH807                      | [60b8032ffc](https://linux-hardware.org/?probe=60b8032ffc) | Nov 05, 2021 |
| Dell          | 09KPNV A00                  | [2ccec65f9c](https://linux-hardware.org/?probe=2ccec65f9c) | Nov 05, 2021 |
| Dell          | 0HH807                      | [4b5694433e](https://linux-hardware.org/?probe=4b5694433e) | Nov 05, 2021 |
| Gigabyte      | GA-E350N                    | [7a1569cd1b](https://linux-hardware.org/?probe=7a1569cd1b) | Nov 04, 2021 |
| Gigabyte      | GA-E350N                    | [636653cd60](https://linux-hardware.org/?probe=636653cd60) | Nov 04, 2021 |
| ASRock        | G31M-GS                     | [4c527af865](https://linux-hardware.org/?probe=4c527af865) | Nov 04, 2021 |
| Dell          | 09KPNV A00                  | [36cb1f25d5](https://linux-hardware.org/?probe=36cb1f25d5) | Nov 03, 2021 |
| Dell          | 0XCR8D A02                  | [cb9a694f6a](https://linux-hardware.org/?probe=cb9a694f6a) | Nov 02, 2021 |
| MSI           | B150M MORTAR                | [cc32b13112](https://linux-hardware.org/?probe=cc32b13112) | Nov 02, 2021 |
| ASUSTek       | PRIME A320M-R               | [f47dd27f3d](https://linux-hardware.org/?probe=f47dd27f3d) | Nov 02, 2021 |
| Gigabyte      | J4005ND2P-CF                | [9f1fa5a3cf](https://linux-hardware.org/?probe=9f1fa5a3cf) | Nov 01, 2021 |
| Gigabyte      | J4005ND2P-CF                | [29a98234db](https://linux-hardware.org/?probe=29a98234db) | Nov 01, 2021 |
| ASRock        | A75M-ITX                    | [9d3864e6ee](https://linux-hardware.org/?probe=9d3864e6ee) | Nov 01, 2021 |
| Dell          | 051FJ8 A00                  | [304737ad06](https://linux-hardware.org/?probe=304737ad06) | Nov 01, 2021 |
| Dell          | 051FJ8 A00                  | [ee0915d7d7](https://linux-hardware.org/?probe=ee0915d7d7) | Nov 01, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [183f547eb4](https://linux-hardware.org/?probe=183f547eb4) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [29f9ae21ee](https://linux-hardware.org/?probe=29f9ae21ee) | Nov 01, 2021 |
| Lenovo        | 7052-A9G                    | [40df1b0b1a](https://linux-hardware.org/?probe=40df1b0b1a) | Nov 01, 2021 |
| Lenovo        | 7052-A9G                    | [af48c29603](https://linux-hardware.org/?probe=af48c29603) | Nov 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e52e9002d0](https://linux-hardware.org/?probe=e52e9002d0) | Oct 31, 2021 |
| Medion        | B75MA-P45                   | [c483a48272](https://linux-hardware.org/?probe=c483a48272) | Oct 30, 2021 |
| Gigabyte      | EX58-UD3R                   | [45661425ff](https://linux-hardware.org/?probe=45661425ff) | Oct 30, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [79a9123be0](https://linux-hardware.org/?probe=79a9123be0) | Oct 29, 2021 |
| Gigabyte      | B560M H                     | [be8b71d264](https://linux-hardware.org/?probe=be8b71d264) | Oct 29, 2021 |
| AOpen         | D1009 A1A4                  | [af51adb4bb](https://linux-hardware.org/?probe=af51adb4bb) | Oct 28, 2021 |
| ASUSTek       | H81M-C                      | [67b9ea1699](https://linux-hardware.org/?probe=67b9ea1699) | Oct 28, 2021 |
| Intel         | D945GCCR AAD78647-300       | [d41d75c998](https://linux-hardware.org/?probe=d41d75c998) | Oct 28, 2021 |
| ASRock        | FM2A75M Pro4+               | [7b85c81082](https://linux-hardware.org/?probe=7b85c81082) | Oct 27, 2021 |
| ASRock        | FM2A75M Pro4+               | [5e6e002dd7](https://linux-hardware.org/?probe=5e6e002dd7) | Oct 27, 2021 |
| ASRock        | FM2A68M-DG3+                | [0564545bcd](https://linux-hardware.org/?probe=0564545bcd) | Oct 27, 2021 |
| ASRock        | FM2A68M-DG3+                | [59e7bb5715](https://linux-hardware.org/?probe=59e7bb5715) | Oct 27, 2021 |
| HP            | ProLiant MicroServer        | [e1358c7c92](https://linux-hardware.org/?probe=e1358c7c92) | Oct 26, 2021 |
| Gigabyte      | EP41-UD3L                   | [77c4005bd9](https://linux-hardware.org/?probe=77c4005bd9) | Oct 26, 2021 |
| ASRock        | FM2A75M Pro4+               | [2575618c9d](https://linux-hardware.org/?probe=2575618c9d) | Oct 24, 2021 |
| ASRock        | FM2A75M Pro4+               | [219c9e69dd](https://linux-hardware.org/?probe=219c9e69dd) | Oct 24, 2021 |
| Acer          | Aspire X1935                | [b4ed3c0529](https://linux-hardware.org/?probe=b4ed3c0529) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| ASRock        | A75M-ITX                    | [c2ea35ef30](https://linux-hardware.org/?probe=c2ea35ef30) | Oct 22, 2021 |
| ASRock        | G31M-GS                     | [28e9f5e95f](https://linux-hardware.org/?probe=28e9f5e95f) | Oct 22, 2021 |
| ASRock        | G31M-GS                     | [94acb8fa87](https://linux-hardware.org/?probe=94acb8fa87) | Oct 21, 2021 |
| Dell          | 040DDP A01                  | [c401dcdeb5](https://linux-hardware.org/?probe=c401dcdeb5) | Oct 21, 2021 |
| Lenovo        | ThinkCentre M57 6066A11     | [f094a159cc](https://linux-hardware.org/?probe=f094a159cc) | Oct 21, 2021 |
| Gigabyte      | A320M-H-CF                  | [1ee663a97d](https://linux-hardware.org/?probe=1ee663a97d) | Oct 20, 2021 |
| ASRock        | AB350M-HDV R3.0             | [ac305398b3](https://linux-hardware.org/?probe=ac305398b3) | Oct 20, 2021 |
| Dell          | 042P49 A00                  | [534a66a78e](https://linux-hardware.org/?probe=534a66a78e) | Oct 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a33e68304f](https://linux-hardware.org/?probe=a33e68304f) | Oct 17, 2021 |
| ASRock        | M3A785GXH/128M              | [9268bda6a2](https://linux-hardware.org/?probe=9268bda6a2) | Oct 17, 2021 |
| Dell          | 0HH807                      | [79fdffe8ec](https://linux-hardware.org/?probe=79fdffe8ec) | Oct 17, 2021 |
| ASRock        | A320M-HDV R3.0              | [e5f58b5d76](https://linux-hardware.org/?probe=e5f58b5d76) | Oct 17, 2021 |
| ASRock        | A320M-HDV R3.0              | [4bf3c6eea6](https://linux-hardware.org/?probe=4bf3c6eea6) | Oct 17, 2021 |
| HP            | 3048h                       | [66aba742a1](https://linux-hardware.org/?probe=66aba742a1) | Oct 16, 2021 |
| HP            | 3048h                       | [e10815e28b](https://linux-hardware.org/?probe=e10815e28b) | Oct 16, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [2dc6a1d295](https://linux-hardware.org/?probe=2dc6a1d295) | Oct 16, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [1112150233](https://linux-hardware.org/?probe=1112150233) | Oct 16, 2021 |
| ASRock        | P67 Extreme4                | [fb4d76caab](https://linux-hardware.org/?probe=fb4d76caab) | Oct 16, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [4c78e0cb2b](https://linux-hardware.org/?probe=4c78e0cb2b) | Oct 15, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [8fe0fccc66](https://linux-hardware.org/?probe=8fe0fccc66) | Oct 15, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [42d90aa70b](https://linux-hardware.org/?probe=42d90aa70b) | Oct 15, 2021 |
| ASRock        | Z370 Pro4                   | [4603126532](https://linux-hardware.org/?probe=4603126532) | Oct 15, 2021 |
| Gigabyte      | GA-MA790X-UD4P              | [5c680571ad](https://linux-hardware.org/?probe=5c680571ad) | Oct 15, 2021 |
| HP            | 3047h                       | [f66ec61e22](https://linux-hardware.org/?probe=f66ec61e22) | Oct 14, 2021 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [8cb5f6619c](https://linux-hardware.org/?probe=8cb5f6619c) | Oct 14, 2021 |
| Fujitsu Si... | D1561 S26361-D1561          | [467c3682c1](https://linux-hardware.org/?probe=467c3682c1) | Oct 13, 2021 |
| MSI           | A320M BAZOOKA               | [acfde1543b](https://linux-hardware.org/?probe=acfde1543b) | Oct 13, 2021 |
| Gigabyte      | H61M-D2-B3                  | [1005ec2531](https://linux-hardware.org/?probe=1005ec2531) | Oct 13, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [297e015743](https://linux-hardware.org/?probe=297e015743) | Oct 13, 2021 |
| Gigabyte      | Z590 UD AC                  | [ec7ba8e11a](https://linux-hardware.org/?probe=ec7ba8e11a) | Oct 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | [4342f43c87](https://linux-hardware.org/?probe=4342f43c87) | Oct 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [da72dae510](https://linux-hardware.org/?probe=da72dae510) | Oct 12, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | [0adc8fc04d](https://linux-hardware.org/?probe=0adc8fc04d) | Oct 12, 2021 |
| ASUSTek       | ROG DOMINUS EXTREME         | [b977489e9c](https://linux-hardware.org/?probe=b977489e9c) | Oct 12, 2021 |
| Gigabyte      | X99-UD3-CF                  | [347d6df600](https://linux-hardware.org/?probe=347d6df600) | Oct 12, 2021 |
| ASRock        | AB350M-HDV R3.0             | [a214b95fb1](https://linux-hardware.org/?probe=a214b95fb1) | Oct 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | [3d26775340](https://linux-hardware.org/?probe=3d26775340) | Oct 11, 2021 |
| Dell          | 0HH807                      | [692c125ea1](https://linux-hardware.org/?probe=692c125ea1) | Oct 10, 2021 |
| Gigabyte      | H61M-S1                     | [d7a1eaa74f](https://linux-hardware.org/?probe=d7a1eaa74f) | Oct 10, 2021 |
| Gigabyte      | H61M-S1                     | [e7294698d5](https://linux-hardware.org/?probe=e7294698d5) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [34bd8d1731](https://linux-hardware.org/?probe=34bd8d1731) | Oct 08, 2021 |
| HP            | 1850                        | [f015e1d723](https://linux-hardware.org/?probe=f015e1d723) | Oct 08, 2021 |
| ASUSTek       | PRIME B450M-A               | [cede000cfe](https://linux-hardware.org/?probe=cede000cfe) | Oct 08, 2021 |
| ASRock        | H110 Pro BTC+               | [e099edf338](https://linux-hardware.org/?probe=e099edf338) | Oct 08, 2021 |
| Gigabyte      | P67A-D3-B3                  | [679674342a](https://linux-hardware.org/?probe=679674342a) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2            | [b4f0a3ac81](https://linux-hardware.org/?probe=b4f0a3ac81) | Oct 07, 2021 |
| Dell          | 042P49 A00                  | [ae38db7950](https://linux-hardware.org/?probe=ae38db7950) | Oct 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [96f0badb1a](https://linux-hardware.org/?probe=96f0badb1a) | Oct 07, 2021 |
| Gigabyte      | H61M-S2PV                   | [c78f82b137](https://linux-hardware.org/?probe=c78f82b137) | Oct 07, 2021 |
| Unknown       | NF-MCP78                    | [89eef3c1a9](https://linux-hardware.org/?probe=89eef3c1a9) | Oct 06, 2021 |
| Dell          | 04YP6J A02                  | [8c5232840e](https://linux-hardware.org/?probe=8c5232840e) | Oct 06, 2021 |
| ASUSTek       | PRIME B365M-A               | [c0bcda2558](https://linux-hardware.org/?probe=c0bcda2558) | Oct 05, 2021 |
| Gigabyte      | H81M-S                      | [c5c52cc683](https://linux-hardware.org/?probe=c5c52cc683) | Oct 05, 2021 |
| ASRock        | FM2A78M-ITX+                | [ac327f6ccd](https://linux-hardware.org/?probe=ac327f6ccd) | Oct 03, 2021 |
| ASUSTek       | P5K-E                       | [047ba385fb](https://linux-hardware.org/?probe=047ba385fb) | Oct 03, 2021 |
| Unknown       | NF-MCP78                    | [acd7f5af32](https://linux-hardware.org/?probe=acd7f5af32) | Oct 03, 2021 |
| HP            | 3648h                       | [a21990541e](https://linux-hardware.org/?probe=a21990541e) | Oct 02, 2021 |
| ASUSTek       | Crosshair IV Formula        | [37ab8645f2](https://linux-hardware.org/?probe=37ab8645f2) | Oct 02, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [b3820e4c5b](https://linux-hardware.org/?probe=b3820e4c5b) | Oct 01, 2021 |
| ASRock        | H61M-VG4                    | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | [6325e87df9](https://linux-hardware.org/?probe=6325e87df9) | Sep 30, 2021 |
| HP            | 339A                        | [b5af0617de](https://linux-hardware.org/?probe=b5af0617de) | Sep 30, 2021 |
| HP            | 339A                        | [40f2319534](https://linux-hardware.org/?probe=40f2319534) | Sep 30, 2021 |
| MSI           | G31M3-L V2                  | [2c6743db1a](https://linux-hardware.org/?probe=2c6743db1a) | Sep 29, 2021 |
| ASRock        | FM2A75M Pro4+               | [ea770dbf08](https://linux-hardware.org/?probe=ea770dbf08) | Sep 28, 2021 |
| ASRock        | FM2A75M Pro4+               | [117bf7a43d](https://linux-hardware.org/?probe=117bf7a43d) | Sep 28, 2021 |
| ASRock        | FM2A68M-HD+                 | [a9ea3df1de](https://linux-hardware.org/?probe=a9ea3df1de) | Sep 28, 2021 |
| HP            | ProLiant MicroServer        | [531a56dc7a](https://linux-hardware.org/?probe=531a56dc7a) | Sep 26, 2021 |
| Lenovo        | SDK0E50510 WIN              | [f8502b5c83](https://linux-hardware.org/?probe=f8502b5c83) | Sep 25, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [08d8affc67](https://linux-hardware.org/?probe=08d8affc67) | Sep 25, 2021 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [e051a4f0a5](https://linux-hardware.org/?probe=e051a4f0a5) | Sep 25, 2021 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [5c9a5f607c](https://linux-hardware.org/?probe=5c9a5f607c) | Sep 24, 2021 |
| Gigabyte      | P67A-D3-B3                  | [b0fc31da96](https://linux-hardware.org/?probe=b0fc31da96) | Sep 22, 2021 |
| ASUSTek       | Crosshair IV Formula        | [9476202052](https://linux-hardware.org/?probe=9476202052) | Sep 22, 2021 |
| HP            | 213D A01                    | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| Gigabyte      | H61M-DS2H                   | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| Gigabyte      | H61M-DS2                    | [0d52c3d318](https://linux-hardware.org/?probe=0d52c3d318) | Sep 20, 2021 |
| Lenovo        | SDK0E50510 WIN              | [59da5f6189](https://linux-hardware.org/?probe=59da5f6189) | Sep 19, 2021 |
| Dell          | 042P49 A00                  | [aac5ee2d08](https://linux-hardware.org/?probe=aac5ee2d08) | Sep 18, 2021 |
| Intel         | DG41RQ AAE54511-205         | [8830ef3d59](https://linux-hardware.org/?probe=8830ef3d59) | Sep 17, 2021 |
| Intel         | DG41RQ AAE54511-205         | [c6d04492c3](https://linux-hardware.org/?probe=c6d04492c3) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| ASUSTek       | P7P55D                      | [9b2fccd56c](https://linux-hardware.org/?probe=9b2fccd56c) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASRock        | B365M Pro4                  | [220ff38d46](https://linux-hardware.org/?probe=220ff38d46) | Sep 16, 2021 |
| ASUSTek       | H81M-C                      | [535e1cd490](https://linux-hardware.org/?probe=535e1cd490) | Sep 14, 2021 |
| Gigabyte      | Z68P-DS3                    | [1ddd2fcf1d](https://linux-hardware.org/?probe=1ddd2fcf1d) | Sep 14, 2021 |
| ASRock        | 945GCM-S                    | [03499bb636](https://linux-hardware.org/?probe=03499bb636) | Sep 13, 2021 |
| Gigabyte      | H81M-S1                     | [9776910346](https://linux-hardware.org/?probe=9776910346) | Sep 12, 2021 |
| Gigabyte      | H81M-S1                     | [2ff1e76c4c](https://linux-hardware.org/?probe=2ff1e76c4c) | Sep 12, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [9127bc0d0a](https://linux-hardware.org/?probe=9127bc0d0a) | Sep 12, 2021 |
| Gigabyte      | H110M-S2HP-CF               | [88b4dd396f](https://linux-hardware.org/?probe=88b4dd396f) | Sep 12, 2021 |
| Gigabyte      | M57SLI-S4                   | [e55af94449](https://linux-hardware.org/?probe=e55af94449) | Sep 12, 2021 |
| ASUSTek       | V-M3N8200                   | [4ee51bb086](https://linux-hardware.org/?probe=4ee51bb086) | Sep 11, 2021 |
| Gigabyte      | M57SLI-S4                   | [146ac97e70](https://linux-hardware.org/?probe=146ac97e70) | Sep 11, 2021 |
| Dell          | 042P49 A00                  | [58329f197b](https://linux-hardware.org/?probe=58329f197b) | Sep 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3a4a448af4](https://linux-hardware.org/?probe=3a4a448af4) | Sep 10, 2021 |
| Dell          | 0WMJ54 A01                  | [fb3d977ed2](https://linux-hardware.org/?probe=fb3d977ed2) | Sep 09, 2021 |
| HP            | 1850                        | [411bf15eca](https://linux-hardware.org/?probe=411bf15eca) | Sep 08, 2021 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [a3ecb14c0c](https://linux-hardware.org/?probe=a3ecb14c0c) | Sep 07, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [e72963a1b5](https://linux-hardware.org/?probe=e72963a1b5) | Sep 06, 2021 |
| Intel         | DG35EC AAE29266-206         | [ea929e2d7e](https://linux-hardware.org/?probe=ea929e2d7e) | Sep 06, 2021 |
| ASUSTek       | F1A75-M PRO                 | [a3e8627869](https://linux-hardware.org/?probe=a3e8627869) | Sep 04, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [c0df973810](https://linux-hardware.org/?probe=c0df973810) | Sep 04, 2021 |
| ASRock        | 4CoreDual-SATA2             | [cad3b9b0f1](https://linux-hardware.org/?probe=cad3b9b0f1) | Sep 04, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [c6d512b026](https://linux-hardware.org/?probe=c6d512b026) | Sep 03, 2021 |
| ASUSTek       | H110M-A                     | [ccec98ba3b](https://linux-hardware.org/?probe=ccec98ba3b) | Sep 03, 2021 |
| Dell          | 0C27VV A01                  | [4954befff2](https://linux-hardware.org/?probe=4954befff2) | Sep 03, 2021 |
| HP            | 1497                        | [b0391f5e3b](https://linux-hardware.org/?probe=b0391f5e3b) | Sep 03, 2021 |
| ASUSTek       | PRIME A320M-R               | [6c6942f44c](https://linux-hardware.org/?probe=6c6942f44c) | Sep 03, 2021 |
| Gigabyte      | B450 AORUS M                | [03bcbe2a20](https://linux-hardware.org/?probe=03bcbe2a20) | Sep 02, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [ff69ae3970](https://linux-hardware.org/?probe=ff69ae3970) | Sep 01, 2021 |
| ASUSTek       | F1A75-M PRO                 | [7462e7862f](https://linux-hardware.org/?probe=7462e7862f) | Sep 01, 2021 |
| Gigabyte      | B450 AORUS M                | [22d55b215b](https://linux-hardware.org/?probe=22d55b215b) | Sep 01, 2021 |
| Gigabyte      | B85-HD3                     | [3692a01aed](https://linux-hardware.org/?probe=3692a01aed) | Aug 31, 2021 |
| ASRock        | FM2A68M-DG3+                | [1c39c6a6a7](https://linux-hardware.org/?probe=1c39c6a6a7) | Aug 31, 2021 |
| ASRock        | FM2A75M Pro4+               | [fd885351b2](https://linux-hardware.org/?probe=fd885351b2) | Aug 31, 2021 |
| ASRock        | FM2A55M-DGS                 | [4e5483f8ac](https://linux-hardware.org/?probe=4e5483f8ac) | Aug 30, 2021 |
| Lenovo        | ThinkCentre A57 98517HG     | [01068c79df](https://linux-hardware.org/?probe=01068c79df) | Aug 29, 2021 |
| Gigabyte      | H170-D3HP-CF                | [64087c4ed2](https://linux-hardware.org/?probe=64087c4ed2) | Aug 29, 2021 |
| Unknown       | T3 MRD V1.1                 | [9acb786639](https://linux-hardware.org/?probe=9acb786639) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| Gigabyte      | G41MT-S2PT                  | [d9b8d68a27](https://linux-hardware.org/?probe=d9b8d68a27) | Aug 27, 2021 |
| Dell          | 0HN7XN A01                  | [af8a3aac02](https://linux-hardware.org/?probe=af8a3aac02) | Aug 27, 2021 |
| Gigabyte      | A320M-H-CF                  | [5cee16a454](https://linux-hardware.org/?probe=5cee16a454) | Aug 27, 2021 |
| ASUSTek       | A8N-SLI                     | [f43dbdd84f](https://linux-hardware.org/?probe=f43dbdd84f) | Aug 27, 2021 |
| Dell          | 0KP561                      | [945a17243f](https://linux-hardware.org/?probe=945a17243f) | Aug 27, 2021 |
| ASRock        | AB350 Gaming K4             | [f25ecb1f4d](https://linux-hardware.org/?probe=f25ecb1f4d) | Aug 25, 2021 |
| ASUSTek       | PRIME A320M-R               | [743bb647e8](https://linux-hardware.org/?probe=743bb647e8) | Aug 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [4ca08670f9](https://linux-hardware.org/?probe=4ca08670f9) | Aug 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [c2083e6b60](https://linux-hardware.org/?probe=c2083e6b60) | Aug 24, 2021 |
| Foxconn       | 2ABF                        | [0ea76af952](https://linux-hardware.org/?probe=0ea76af952) | Aug 24, 2021 |
| Foxconn       | 2ABF                        | [c276a9ab0a](https://linux-hardware.org/?probe=c276a9ab0a) | Aug 24, 2021 |
| ASUSTek       | PRIME A320M-R               | [aa83132d79](https://linux-hardware.org/?probe=aa83132d79) | Aug 23, 2021 |
| Gigabyte      | GA-MA790X-UD4P              | [4951e3a5e3](https://linux-hardware.org/?probe=4951e3a5e3) | Aug 22, 2021 |
| Dell          | 0KP561                      | [b136ea3e88](https://linux-hardware.org/?probe=b136ea3e88) | Aug 21, 2021 |
| Fujitsu       | D3118-A2 S26361-D3118-A2    | [8e8715b0cd](https://linux-hardware.org/?probe=8e8715b0cd) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [46614b6e2e](https://linux-hardware.org/?probe=46614b6e2e) | Aug 18, 2021 |
| Wistron       | ProLiant ML110 G6           | [a43f59c4ab](https://linux-hardware.org/?probe=a43f59c4ab) | Aug 18, 2021 |
| Gigabyte      | G41MT-S2PT                  | [0cebce03bb](https://linux-hardware.org/?probe=0cebce03bb) | Aug 17, 2021 |
| ASUSTek       | PRIME B365M-A               | [5a5a31dc0b](https://linux-hardware.org/?probe=5a5a31dc0b) | Aug 16, 2021 |
| ASUSTek       | PRIME B365M-A               | [0c67b898b6](https://linux-hardware.org/?probe=0c67b898b6) | Aug 16, 2021 |
| Dell          | 0C27VV A01                  | [c811f7984e](https://linux-hardware.org/?probe=c811f7984e) | Aug 15, 2021 |
| Dell          | 0C27VV A01                  | [6c7f7a7f72](https://linux-hardware.org/?probe=6c7f7a7f72) | Aug 15, 2021 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [337dd88949](https://linux-hardware.org/?probe=337dd88949) | Aug 14, 2021 |
| ASRock        | FM2A68M-HD+                 | [45c59105c4](https://linux-hardware.org/?probe=45c59105c4) | Aug 12, 2021 |
| Lenovo        | ThinkStation C30 1097A34    | [8841f4eb25](https://linux-hardware.org/?probe=8841f4eb25) | Aug 11, 2021 |
| ASRock        | J3160-ITX                   | [682890974b](https://linux-hardware.org/?probe=682890974b) | Aug 11, 2021 |
| HP            | ProLiant MicroServer        | [f7472b1017](https://linux-hardware.org/?probe=f7472b1017) | Aug 11, 2021 |
| Gigabyte      | GA-MA790X-UD4P              | [77f7e27f04](https://linux-hardware.org/?probe=77f7e27f04) | Aug 11, 2021 |
| ASUSTek       | H110M-K                     | [4746c16098](https://linux-hardware.org/?probe=4746c16098) | Aug 10, 2021 |
| ASRock        | B75 Pro3                    | [c32fcf3e07](https://linux-hardware.org/?probe=c32fcf3e07) | Aug 08, 2021 |
| ASRock        | B75 Pro3                    | [b6fb908c5e](https://linux-hardware.org/?probe=b6fb908c5e) | Aug 08, 2021 |
| ASUSTek       | M2A-MX                      | [9aa2ff4ca2](https://linux-hardware.org/?probe=9aa2ff4ca2) | Aug 07, 2021 |
| Lenovo        | ThinkStation D20 4158AF8    | [f3a8efacf0](https://linux-hardware.org/?probe=f3a8efacf0) | Aug 07, 2021 |
| ASRock        | B85M                        | [a3363aaf61](https://linux-hardware.org/?probe=a3363aaf61) | Aug 06, 2021 |
| ASRock        | B85M                        | [d2667fd78f](https://linux-hardware.org/?probe=d2667fd78f) | Aug 06, 2021 |
| Gigabyte      | H310M S2H x.x               | [5324364e30](https://linux-hardware.org/?probe=5324364e30) | Aug 05, 2021 |
| Gigabyte      | H310M S2H x.x               | [3464207bf9](https://linux-hardware.org/?probe=3464207bf9) | Aug 05, 2021 |
| Dell          | 0GM819                      | [6dd45e20cc](https://linux-hardware.org/?probe=6dd45e20cc) | Aug 05, 2021 |
| Gigabyte      | G41MT-S2                    | [88dc4d9a30](https://linux-hardware.org/?probe=88dc4d9a30) | Aug 02, 2021 |
| Gigabyte      | G41MT-S2                    | [bebba22bf9](https://linux-hardware.org/?probe=bebba22bf9) | Aug 02, 2021 |
| ASUSTek       | B75M-A                      | [a5019e4b32](https://linux-hardware.org/?probe=a5019e4b32) | Aug 01, 2021 |
| Gigabyte      | EP45-UD3                    | [c2ed86e850](https://linux-hardware.org/?probe=c2ed86e850) | Aug 01, 2021 |
| ASRock        | 4CoreDual-SATA2             | [5b17caa94d](https://linux-hardware.org/?probe=5b17caa94d) | Aug 01, 2021 |
| Gigabyte      | EP45-UD3                    | [6775219be1](https://linux-hardware.org/?probe=6775219be1) | Aug 01, 2021 |
| ASUSTek       | B75M-A                      | [314c09e02e](https://linux-hardware.org/?probe=314c09e02e) | Aug 01, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f656370ab1](https://linux-hardware.org/?probe=f656370ab1) | Jul 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [a282d834c3](https://linux-hardware.org/?probe=a282d834c3) | Jul 31, 2021 |
| Foxconn       | G41MXP/G41MXP-V             | [bbc2a8730c](https://linux-hardware.org/?probe=bbc2a8730c) | Jul 31, 2021 |
| Foxconn       | G41MXP/G41MXP-V             | [2fcda4fa72](https://linux-hardware.org/?probe=2fcda4fa72) | Jul 31, 2021 |
| MSI           | B450I GAMING PLUS AC        | [cacd4b91a5](https://linux-hardware.org/?probe=cacd4b91a5) | Jul 31, 2021 |
| MSI           | B450I GAMING PLUS AC        | [1caefe66d6](https://linux-hardware.org/?probe=1caefe66d6) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | [5ba8f24eda](https://linux-hardware.org/?probe=5ba8f24eda) | Jul 30, 2021 |
| Lenovo        | ThinkCentre M57p 9196AB5    | [171501e566](https://linux-hardware.org/?probe=171501e566) | Jul 30, 2021 |
| ASUSTek       | PRIME B365M-A               | [b72fa42ea7](https://linux-hardware.org/?probe=b72fa42ea7) | Jul 29, 2021 |
| Gigabyte      | 970A-DS3P                   | [a8abc9f29f](https://linux-hardware.org/?probe=a8abc9f29f) | Jul 29, 2021 |
| Dell          | 0VD5HY A00                  | [f4115403fe](https://linux-hardware.org/?probe=f4115403fe) | Jul 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [fde3c4fa9f](https://linux-hardware.org/?probe=fde3c4fa9f) | Jul 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [f3daafb698](https://linux-hardware.org/?probe=f3daafb698) | Jul 27, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [da264c335c](https://linux-hardware.org/?probe=da264c335c) | Jul 27, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [4279830fce](https://linux-hardware.org/?probe=4279830fce) | Jul 27, 2021 |
| ASUSTek       | M5A97 R2.0                  | [fe0953d7db](https://linux-hardware.org/?probe=fe0953d7db) | Jul 27, 2021 |
| ASUSTek       | P7P55D                      | [1895c9117e](https://linux-hardware.org/?probe=1895c9117e) | Jul 26, 2021 |
| ASRock        | B250M Pro4                  | [5b604a949d](https://linux-hardware.org/?probe=5b604a949d) | Jul 26, 2021 |
| ASRock        | B250M Pro4                  | [d8f05d9acc](https://linux-hardware.org/?probe=d8f05d9acc) | Jul 26, 2021 |
| MSI           | 2A9Ch                       | [93ee78c8d1](https://linux-hardware.org/?probe=93ee78c8d1) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| ASUSTek       | P5QC                        | [1964e96f5b](https://linux-hardware.org/?probe=1964e96f5b) | Jul 25, 2021 |
| ASRock        | B250M Pro4                  | [a85901b6d4](https://linux-hardware.org/?probe=a85901b6d4) | Jul 24, 2021 |
| ASRock        | B250M Pro4                  | [c2e8f0fec8](https://linux-hardware.org/?probe=c2e8f0fec8) | Jul 24, 2021 |
| Unknown       | 775i65G                     | [b92a942f9e](https://linux-hardware.org/?probe=b92a942f9e) | Jul 23, 2021 |
| HP            | 8055                        | [1b9ebeb8fa](https://linux-hardware.org/?probe=1b9ebeb8fa) | Jul 23, 2021 |
| Lenovo        | ThinkCentre M57 6066A11     | [54a35ebdd2](https://linux-hardware.org/?probe=54a35ebdd2) | Jul 22, 2021 |
| Gigabyte      | H81M-HD3                    | [c3ddc34552](https://linux-hardware.org/?probe=c3ddc34552) | Jul 22, 2021 |
| ASUSTek       | H81M-E                      | [4c55d81b47](https://linux-hardware.org/?probe=4c55d81b47) | Jul 22, 2021 |
| ASRock        | B250M Pro4                  | [ca9889003b](https://linux-hardware.org/?probe=ca9889003b) | Jul 22, 2021 |
| ASUSTek       | H81M-E                      | [df85b3a98b](https://linux-hardware.org/?probe=df85b3a98b) | Jul 22, 2021 |
| Lenovo        | ThinkCentre M57 6066A11     | [33d0133c6f](https://linux-hardware.org/?probe=33d0133c6f) | Jul 22, 2021 |
| ASUSTek       | PRIME B365M-A               | [68b7c3ed61](https://linux-hardware.org/?probe=68b7c3ed61) | Jul 19, 2021 |
| Gigabyte      | G41MT-S2PT                  | [83c0a37711](https://linux-hardware.org/?probe=83c0a37711) | Jul 18, 2021 |
| Gigabyte      | H61M-DS2                    | [9bec640779](https://linux-hardware.org/?probe=9bec640779) | Jul 18, 2021 |
| Gigabyte      | 970A-DS3P                   | [d079295fab](https://linux-hardware.org/?probe=d079295fab) | Jul 18, 2021 |
| Gigabyte      | 970A-DS3P                   | [b623dba68b](https://linux-hardware.org/?probe=b623dba68b) | Jul 18, 2021 |
| HP            | 0A68h                       | [0d65da8218](https://linux-hardware.org/?probe=0d65da8218) | Jul 18, 2021 |
| HP            | 0A68h                       | [5abf71b3b5](https://linux-hardware.org/?probe=5abf71b3b5) | Jul 18, 2021 |
| ASUSTek       | H110M-A                     | [58d78b8e65](https://linux-hardware.org/?probe=58d78b8e65) | Jul 17, 2021 |
| MSI           | G41M-P28                    | [3ee9259ce1](https://linux-hardware.org/?probe=3ee9259ce1) | Jul 17, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [f03b137212](https://linux-hardware.org/?probe=f03b137212) | Jul 17, 2021 |
| HP            | 1850                        | [7a7e737a89](https://linux-hardware.org/?probe=7a7e737a89) | Jul 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [0a56fa942f](https://linux-hardware.org/?probe=0a56fa942f) | Jul 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [5291ceb2e8](https://linux-hardware.org/?probe=5291ceb2e8) | Jul 17, 2021 |
| HP            | 3029h                       | [cdd0072823](https://linux-hardware.org/?probe=cdd0072823) | Jul 17, 2021 |
| ASUSTek       | P7P55D                      | [1fdccf0b8c](https://linux-hardware.org/?probe=1fdccf0b8c) | Jul 16, 2021 |
| ASUSTek       | P7P55D                      | [732e6e2b14](https://linux-hardware.org/?probe=732e6e2b14) | Jul 16, 2021 |
| ASUSTek       | P7P55D                      | [764653dba1](https://linux-hardware.org/?probe=764653dba1) | Jul 16, 2021 |
| HP            | ProLiant MicroServer        | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| ASUSTek       | M2N68-AM Plus               | [0369488ec1](https://linux-hardware.org/?probe=0369488ec1) | Jul 15, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [fded86e377](https://linux-hardware.org/?probe=fded86e377) | Jul 14, 2021 |
| Acer          | Veriton X4630G              | [080363027e](https://linux-hardware.org/?probe=080363027e) | Jul 14, 2021 |
| Acer          | Veriton X4630G              | [5fa2645a1f](https://linux-hardware.org/?probe=5fa2645a1f) | Jul 14, 2021 |
| ASUSTek       | P7P55D                      | [384f2488c8](https://linux-hardware.org/?probe=384f2488c8) | Jul 13, 2021 |
| Gigabyte      | H81M-HD3                    | [0d72e1d70d](https://linux-hardware.org/?probe=0d72e1d70d) | Jul 12, 2021 |
| Lenovo        | Tilapia CRB                 | [da1f0d65ec](https://linux-hardware.org/?probe=da1f0d65ec) | Jul 12, 2021 |
| ASRock        | B450M Pro4-F                | [b8a9b28642](https://linux-hardware.org/?probe=b8a9b28642) | Jul 11, 2021 |
| ASUSTek       | VC65R                       | [790c5f73db](https://linux-hardware.org/?probe=790c5f73db) | Jul 09, 2021 |
| ASUSTek       | M2N68-AM Plus               | [222c467b30](https://linux-hardware.org/?probe=222c467b30) | Jul 08, 2021 |
| HP            | 3047h                       | [e78150909f](https://linux-hardware.org/?probe=e78150909f) | Jul 08, 2021 |
| MSI           | B150M ECO                   | [c97e6af0f2](https://linux-hardware.org/?probe=c97e6af0f2) | Jul 07, 2021 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [33b70fad34](https://linux-hardware.org/?probe=33b70fad34) | Jul 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | [500b07927d](https://linux-hardware.org/?probe=500b07927d) | Jul 06, 2021 |
| ASUSTek       | P7P55-M                     | [3248d46b49](https://linux-hardware.org/?probe=3248d46b49) | Jul 06, 2021 |
| ASUSTek       | P7P55-M                     | [c4e2ad4152](https://linux-hardware.org/?probe=c4e2ad4152) | Jul 06, 2021 |
| ASRock        | 970M Pro3                   | [afcf713572](https://linux-hardware.org/?probe=afcf713572) | Jul 05, 2021 |
| Gigabyte      | EP45-UD3                    | [0bb7172bae](https://linux-hardware.org/?probe=0bb7172bae) | Jul 05, 2021 |
| ASRock        | 970M Pro3                   | [0601bffa1e](https://linux-hardware.org/?probe=0601bffa1e) | Jul 04, 2021 |
| ASUSTek       | P7P55D                      | [7a537952d2](https://linux-hardware.org/?probe=7a537952d2) | Jul 04, 2021 |
| ASRock        | B450 Pro4                   | [cddc04f9bf](https://linux-hardware.org/?probe=cddc04f9bf) | Jul 04, 2021 |
| Dell          | 0KP561                      | [7f73e68ddf](https://linux-hardware.org/?probe=7f73e68ddf) | Jul 03, 2021 |
| ASUSTek       | P7P55D                      | [fd6c20bc63](https://linux-hardware.org/?probe=fd6c20bc63) | Jul 03, 2021 |
| ASUSTek       | H110M-A                     | [7f5ac19a94](https://linux-hardware.org/?probe=7f5ac19a94) | Jul 01, 2021 |
| Dell          | 055H3G A01                  | [15d111f1ae](https://linux-hardware.org/?probe=15d111f1ae) | Jul 01, 2021 |
| ASRock        | B450 Pro4                   | [1164a5f913](https://linux-hardware.org/?probe=1164a5f913) | Jul 01, 2021 |
| ASRock        | AB350M-HDV R3.0             | [03fe042535](https://linux-hardware.org/?probe=03fe042535) | Jul 01, 2021 |
| ASUSTek       | H110M-R                     | [3f18260d1c](https://linux-hardware.org/?probe=3f18260d1c) | Jun 30, 2021 |
| ASUSTek       | PRIME A320M-R               | [78c94a5398](https://linux-hardware.org/?probe=78c94a5398) | Jun 29, 2021 |
| Gigabyte      | GA-MA770-UD3                | [34d2885e24](https://linux-hardware.org/?probe=34d2885e24) | Jun 28, 2021 |
| Lenovo        | 7052-A9G                    | [596f502ebb](https://linux-hardware.org/?probe=596f502ebb) | Jun 27, 2021 |
| Lenovo        | 7052-A9G                    | [619feb575b](https://linux-hardware.org/?probe=619feb575b) | Jun 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [602f35c3ff](https://linux-hardware.org/?probe=602f35c3ff) | Jun 27, 2021 |
| ASUSTek       | P7P55-M                     | [53556ddcf3](https://linux-hardware.org/?probe=53556ddcf3) | Jun 27, 2021 |
| Pegatron      | Benicia                     | [2e2484cb24](https://linux-hardware.org/?probe=2e2484cb24) | Jun 26, 2021 |
| Gigabyte      | 945GCM-S2L                  | [770971c70a](https://linux-hardware.org/?probe=770971c70a) | Jun 26, 2021 |
| Gigabyte      | B450M GAMING                | [437db234e1](https://linux-hardware.org/?probe=437db234e1) | Jun 26, 2021 |
| Pegatron      | 2A73                        | [45e9b6e0ca](https://linux-hardware.org/?probe=45e9b6e0ca) | Jun 26, 2021 |
| Pegatron      | 2A73                        | [af6808a93c](https://linux-hardware.org/?probe=af6808a93c) | Jun 26, 2021 |
| ASUSTek       | PRIME A320M-R               | [9b6d40dbd1](https://linux-hardware.org/?probe=9b6d40dbd1) | Jun 25, 2021 |
| Lenovo        | ThinkCentre M81 5048BC8     | [1e44038d9f](https://linux-hardware.org/?probe=1e44038d9f) | Jun 25, 2021 |
| ASUSTek       | AM1M-A                      | [7926f5f9ec](https://linux-hardware.org/?probe=7926f5f9ec) | Jun 25, 2021 |
| Lenovo        | ThinkCentre M81 5048BC8     | [c7b597d184](https://linux-hardware.org/?probe=c7b597d184) | Jun 25, 2021 |
| ASRock        | FM2A68M-HD+                 | [1e37b435ea](https://linux-hardware.org/?probe=1e37b435ea) | Jun 23, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f3de105f7c](https://linux-hardware.org/?probe=f3de105f7c) | Jun 23, 2021 |
| Gigabyte      | Z690 GAMING X DDR4          | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| ASUSTek       | P7P55D-E                    | [e2e01634fe](https://linux-hardware.org/?probe=e2e01634fe) | Jun 21, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [29be4d18e9](https://linux-hardware.org/?probe=29be4d18e9) | Jun 20, 2021 |
| ASUSTek       | P7P55D-E                    | [c9bfcd2d0e](https://linux-hardware.org/?probe=c9bfcd2d0e) | Jun 20, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [c13134fc57](https://linux-hardware.org/?probe=c13134fc57) | Jun 19, 2021 |
| ASUSTek       | P7P55D-E                    | [69dba0a341](https://linux-hardware.org/?probe=69dba0a341) | Jun 19, 2021 |
| ASRock        | G41M-VS3                    | [761cc9a0fd](https://linux-hardware.org/?probe=761cc9a0fd) | Jun 18, 2021 |
| ASRock        | G41M-VS3                    | [a4cae20589](https://linux-hardware.org/?probe=a4cae20589) | Jun 17, 2021 |
| Lenovo        | NOK                         | [7cd1c48ff7](https://linux-hardware.org/?probe=7cd1c48ff7) | Jun 17, 2021 |
| Lenovo        | NOK                         | [4a5ca01289](https://linux-hardware.org/?probe=4a5ca01289) | Jun 17, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [07a7bd0dcf](https://linux-hardware.org/?probe=07a7bd0dcf) | Jun 17, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [430e051485](https://linux-hardware.org/?probe=430e051485) | Jun 17, 2021 |
| Lenovo        | SDK0E50510 WIN              | [ffa931b206](https://linux-hardware.org/?probe=ffa931b206) | Jun 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [4f3b7ea314](https://linux-hardware.org/?probe=4f3b7ea314) | Jun 17, 2021 |
| ASUSTek       | M2N68-AM Plus               | [3ffaaf7165](https://linux-hardware.org/?probe=3ffaaf7165) | Jun 17, 2021 |
| Gigabyte      | 945GCM-S2L                  | [342ae79c5a](https://linux-hardware.org/?probe=342ae79c5a) | Jun 16, 2021 |
| ASUSTek       | M5A97 PLUS                  | [987ef5946e](https://linux-hardware.org/?probe=987ef5946e) | Jun 16, 2021 |
| ASUSTek       | M5A97 PLUS                  | [d6831d4bd5](https://linux-hardware.org/?probe=d6831d4bd5) | Jun 16, 2021 |
| ASUSTek       | P7P55D-E                    | [fd58a1c56f](https://linux-hardware.org/?probe=fd58a1c56f) | Jun 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [96353190ff](https://linux-hardware.org/?probe=96353190ff) | Jun 15, 2021 |
| Gigabyte      | 945GCM-S2C                  | [c7e324e6c2](https://linux-hardware.org/?probe=c7e324e6c2) | Jun 14, 2021 |
| Gigabyte      | GA-MA770-UD3                | [6fa1ce0161](https://linux-hardware.org/?probe=6fa1ce0161) | Jun 14, 2021 |
| Gigabyte      | 945GCM-S2C                  | [be08e30ca5](https://linux-hardware.org/?probe=be08e30ca5) | Jun 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | [3f3b75a76d](https://linux-hardware.org/?probe=3f3b75a76d) | Jun 13, 2021 |
| Lenovo        | MAHOBAY NOK                 | [34f6b01cd3](https://linux-hardware.org/?probe=34f6b01cd3) | Jun 13, 2021 |
| ASRock        | B550M Pro4                  | [a18d8c2f61](https://linux-hardware.org/?probe=a18d8c2f61) | Jun 12, 2021 |
| Lenovo        | ThinkCentre M57e 9488Y25    | [41310d3373](https://linux-hardware.org/?probe=41310d3373) | Jun 12, 2021 |
| Pegatron      | Benicia                     | [63b3d6c67e](https://linux-hardware.org/?probe=63b3d6c67e) | Jun 10, 2021 |
| Pegatron      | Benicia                     | [5233f7f85c](https://linux-hardware.org/?probe=5233f7f85c) | Jun 10, 2021 |
| ASRock        | G41M-VS3                    | [6b978deb9d](https://linux-hardware.org/?probe=6b978deb9d) | Jun 09, 2021 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | [2e1cf6ba65](https://linux-hardware.org/?probe=2e1cf6ba65) | Jun 09, 2021 |
| Gigabyte      | EP45-UD3                    | [0e24e807e1](https://linux-hardware.org/?probe=0e24e807e1) | Jun 08, 2021 |
| HP            | 8054                        | [ec649716ce](https://linux-hardware.org/?probe=ec649716ce) | Jun 08, 2021 |
| Gigabyte      | P55-US3L                    | [46186d595e](https://linux-hardware.org/?probe=46186d595e) | Jun 08, 2021 |
| Gigabyte      | P55-US3L                    | [e04be7a5d4](https://linux-hardware.org/?probe=e04be7a5d4) | Jun 08, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| BlackPanther 18.1  | 848      | 55.68%  |
| Ubuntu 20.04       | 96       | 6.3%    |
| BlackPanther 16.2  | 63       | 4.14%   |
| Ubuntu 18.04       | 56       | 3.68%   |
| OpenMandriva 4.2   | 37       | 2.43%   |
| Debian 11          | 18       | 1.18%   |
| Ubuntu 22.04       | 17       | 1.12%   |
| OpenMandriva 4.3   | 17       | 1.12%   |
| Arch Rolling       | 14       | 0.92%   |
| Zorin 16           | 13       | 0.85%   |
| Linux Mint 20.2    | 13       | 0.85%   |
| OpenMandriva 4.50  | 12       | 0.79%   |
| Debian 10          | 12       | 0.79%   |
| Ubuntu 19.10       | 11       | 0.72%   |
| Arch               | 11       | 0.72%   |
| Xubuntu 20.04      | 10       | 0.66%   |
| Linux Mint 20      | 10       | 0.66%   |
| Xubuntu 18.04      | 9        | 0.59%   |
| Ubuntu 21.10       | 9        | 0.59%   |
| Ubuntu 19.04       | 9        | 0.59%   |
| OpenMandriva 4.90  | 7        | 0.46%   |
| Linux Mint 20.1    | 7        | 0.46%   |
| Zorin 15           | 6        | 0.39%   |
| Ubuntu 21.04       | 6        | 0.39%   |
| Ubuntu 20.10       | 6        | 0.39%   |
| Manjaro            | 6        | 0.39%   |
| Linux Mint 20.3    | 6        | 0.39%   |
| Linux Mint 19.3    | 6        | 0.39%   |
| Kubuntu 20.04      | 6        | 0.39%   |
| KDE neon 20.04     | 6        | 0.39%   |
| ArcoLinux Rolling  | 6        | 0.39%   |
| OpenMandriva 23.01 | 5        | 0.33%   |
| Lubuntu 20.04      | 5        | 0.33%   |
| Fedora 37          | 5        | 0.33%   |
| Fedora 36          | 5        | 0.33%   |
| Fedora 32          | 5        | 0.33%   |
| Pop!_OS 22.04      | 4        | 0.26%   |
| Pop!_OS 20.10      | 4        | 0.26%   |
| Fedora 35          | 4        | 0.26%   |
| Ubuntu Unity 16.04 | 3        | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| BlackPanther  | 895      | 60.8%   |
| Ubuntu        | 205      | 13.93%  |
| OpenMandriva  | 79       | 5.37%   |
| Linux Mint    | 48       | 3.26%   |
| Debian        | 34       | 2.31%   |
| Arch          | 25       | 1.7%    |
| Xubuntu       | 22       | 1.49%   |
| Zorin         | 19       | 1.29%   |
| Kubuntu       | 18       | 1.22%   |
| Fedora        | 18       | 1.22%   |
| Manjaro       | 16       | 1.09%   |
| Pop!_OS       | 13       | 0.88%   |
| Ubuntu MATE   | 10       | 0.68%   |
| ArcoLinux     | 8        | 0.54%   |
| Ubuntu Unity  | 7        | 0.48%   |
| Lubuntu       | 7        | 0.48%   |
| KDE neon      | 7        | 0.48%   |
| ROSA          | 6        | 0.41%   |
| Endless       | 5        | 0.34%   |
| openSUSE      | 4        | 0.27%   |
| Gentoo        | 4        | 0.27%   |
| EndeavourOS   | 3        | 0.2%    |
| Nobara        | 2        | 0.14%   |
| MX            | 2        | 0.14%   |
| LMDE          | 2        | 0.14%   |
| Ubuntu Budgie | 1        | 0.07%   |
| risiOS        | 1        | 0.07%   |
| Reborn OS     | 1        | 0.07%   |
| Q4OS          | 1        | 0.07%   |
| NixOS         | 1        | 0.07%   |
| Linux Lite    | 1        | 0.07%   |
| Kali          | 1        | 0.07%   |
| Garuda Linux  | 1        | 0.07%   |
| Elementary    | 1        | 0.07%   |
| Clear Linux   | 1        | 0.07%   |
| CentOS        | 1        | 0.07%   |
| Archcraft     | 1        | 0.07%   |
| antergos      | 1        | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 4.18.16-desktop-1bP      | 652      | 39%     |
| 5.6.14-desktop-2bP       | 248      | 14.83%  |
| 4.9.20-desktop-pae-1bP   | 55       | 3.29%   |
| 5.10.14-desktop-1omv4002 | 34       | 2.03%   |
| 5.1.15-desktop-1bP       | 27       | 1.61%   |
| 5.16.7-desktop-1omv4003  | 17       | 1.02%   |
| 5.4.0-42-generic         | 13       | 0.78%   |
| 5.4.0-58-generic         | 12       | 0.72%   |
| 5.4.0-52-generic         | 8        | 0.48%   |
| 5.4.0-48-generic         | 8        | 0.48%   |
| 5.15.0-56-generic        | 8        | 0.48%   |
| 5.18.12-desktop-3omv4090 | 7        | 0.42%   |
| 5.11.0-27-generic        | 7        | 0.42%   |
| 5.8.0-43-generic         | 6        | 0.36%   |
| 5.4.0-47-generic         | 6        | 0.36%   |
| 5.3.0-46-generic         | 6        | 0.36%   |
| 5.11.0-43-generic        | 6        | 0.36%   |
| 4.15.0-43-generic        | 6        | 0.36%   |
| 6.1.1-desktop-1omv2290   | 5        | 0.3%    |
| 5.8.0-44-generic         | 5        | 0.3%    |
| 5.4.0-91-generic         | 5        | 0.3%    |
| 5.12.4-desktop-1omv4050  | 5        | 0.3%    |
| 5.11.0-37-generic        | 5        | 0.3%    |
| 5.0.0-37-generic         | 5        | 0.3%    |
| 5.8.0-7630-generic       | 4        | 0.24%   |
| 5.4.0-88-generic         | 4        | 0.24%   |
| 5.4.0-73-generic         | 4        | 0.24%   |
| 5.4.0-54-generic         | 4        | 0.24%   |
| 5.4.0-53-generic         | 4        | 0.24%   |
| 5.4.0-40-generic         | 4        | 0.24%   |
| 5.4.0-37-generic         | 4        | 0.24%   |
| 5.4.0-31-generic         | 4        | 0.24%   |
| 5.4.0-100-generic        | 4        | 0.24%   |
| 5.15.0-58-generic        | 4        | 0.24%   |
| 5.15.0-47-generic        | 4        | 0.24%   |
| 5.15.0-46-generic        | 4        | 0.24%   |
| 5.13.13-arch1-1          | 4        | 0.24%   |
| 5.13.0-41-generic        | 4        | 0.24%   |
| 5.13.0-30-generic        | 4        | 0.24%   |
| 5.13.0-27-generic        | 4        | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18.16 | 652      | 40.02%  |
| 5.6.14  | 249      | 15.29%  |
| 5.4.0   | 125      | 7.67%   |
| 4.9.20  | 58       | 3.56%   |
| 5.11.0  | 43       | 2.64%   |
| 4.15.0  | 43       | 2.64%   |
| 5.8.0   | 36       | 2.21%   |
| 5.15.0  | 34       | 2.09%   |
| 5.10.14 | 34       | 2.09%   |
| 5.13.0  | 30       | 1.84%   |
| 5.3.0   | 29       | 1.78%   |
| 5.1.15  | 28       | 1.72%   |
| 5.0.0   | 22       | 1.35%   |
| 5.16.7  | 17       | 1.04%   |
| 5.10.0  | 15       | 0.92%   |
| 4.19.0  | 13       | 0.8%    |
| 6.1.1   | 7        | 0.43%   |
| 5.18.12 | 7        | 0.43%   |
| 4.18.0  | 7        | 0.43%   |
| 5.12.4  | 5        | 0.31%   |
| 6.0.12  | 4        | 0.25%   |
| 5.9.16  | 4        | 0.25%   |
| 5.16.0  | 4        | 0.25%   |
| 5.13.13 | 4        | 0.25%   |
| 6.0.8   | 3        | 0.18%   |
| 6.0.10  | 3        | 0.18%   |
| 5.19.5  | 3        | 0.18%   |
| 5.19.12 | 3        | 0.18%   |
| 5.18.5  | 3        | 0.18%   |
| 5.14.9  | 3        | 0.18%   |
| 5.14.0  | 3        | 0.18%   |
| 4.7.0   | 3        | 0.18%   |
| 6.1.6   | 2        | 0.12%   |
| 6.0.9   | 2        | 0.12%   |
| 6.0.0   | 2        | 0.12%   |
| 5.9.14  | 2        | 0.12%   |
| 5.9.1   | 2        | 0.12%   |
| 5.7.0   | 2        | 0.12%   |
| 5.6.12  | 2        | 0.12%   |
| 5.5.8   | 2        | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.18    | 659      | 40.68%  |
| 5.6     | 251      | 15.49%  |
| 5.4     | 133      | 8.21%   |
| 4.9     | 63       | 3.89%   |
| 5.10    | 57       | 3.52%   |
| 5.11    | 51       | 3.15%   |
| 5.15    | 49       | 3.02%   |
| 4.15    | 43       | 2.65%   |
| 5.8     | 41       | 2.53%   |
| 5.13    | 38       | 2.35%   |
| 5.1     | 31       | 1.91%   |
| 5.3     | 30       | 1.85%   |
| 5.16    | 26       | 1.6%    |
| 5.0     | 22       | 1.36%   |
| 6.0     | 16       | 0.99%   |
| 5.19    | 14       | 0.86%   |
| 5.18    | 13       | 0.8%    |
| 4.19    | 13       | 0.8%    |
| 5.9     | 11       | 0.68%   |
| 5.14    | 10       | 0.62%   |
| 6.1     | 9        | 0.56%   |
| 5.7     | 8        | 0.49%   |
| 5.17    | 8        | 0.49%   |
| 5.12    | 8        | 0.49%   |
| 5.5     | 3        | 0.19%   |
| 4.7     | 3        | 0.19%   |
| 4.4     | 2        | 0.12%   |
| 4.20    | 2        | 0.12%   |
| 4.5     | 1        | 0.06%   |
| 4.14    | 1        | 0.06%   |
| 4.12    | 1        | 0.06%   |
| 4.10    | 1        | 0.06%   |
| 4.1     | 1        | 0.06%   |
| 3.13    | 1        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1356     | 94.3%   |
| i686   | 81       | 5.63%   |
| unknow | 1        | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 993      | 67.97%  |
| GNOME           | 212      | 14.51%  |
| Unknown         | 86       | 5.89%   |
| XFCE            | 55       | 3.76%   |
| X-Cinnamon      | 32       | 2.19%   |
| MATE            | 26       | 1.78%   |
| KDE             | 11       | 0.75%   |
| LXQt            | 9        | 0.62%   |
| Cinnamon        | 9        | 0.62%   |
| Unity           | 7        | 0.48%   |
| KDE4            | 5        | 0.34%   |
| i3              | 5        | 0.34%   |
| LXDE            | 3        | 0.21%   |
| Deepin          | 3        | 0.21%   |
| Trinity         | 1        | 0.07%   |
| GNOME Flashback | 1        | 0.07%   |
| GNOME Classic   | 1        | 0.07%   |
| Enlightenment   | 1        | 0.07%   |
| Budgie          | 1        | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1328     | 92.61%  |
| Unknown | 45       | 3.14%   |
| Wayland | 43       | 3%      |
| Tty     | 18       | 1.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 991      | 68.2%   |
| Unknown | 288      | 19.82%  |
| LightDM | 56       | 3.85%   |
| GDM3    | 45       | 3.1%    |
| GDM     | 40       | 2.75%   |
| TDM     | 26       | 1.79%   |
| KDM     | 5        | 0.34%   |
| SLiM    | 2        | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 944      | 64.79%  |
| hu_HU      | 312      | 21.41%  |
| en_US      | 164      | 11.26%  |
| en_GB      | 17       | 1.17%   |
| C          | 8        | 0.55%   |
| de_DE      | 7        | 0.48%   |
| hu_HU.UTF8 | 2        | 0.14%   |
| POSIX      | 1        | 0.07%   |
| en_AG      | 1        | 0.07%   |
| C.UTF8     | 1        | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1071     | 72.61%  |
| EFI  | 404      | 27.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 769      | 49.68%  |
| Overlay | 714      | 46.12%  |
| Btrfs   | 32       | 2.07%   |
| Unknown | 18       | 1.16%   |
| Zfs     | 5        | 0.32%   |
| Xfs     | 5        | 0.32%   |
| Ext2    | 3        | 0.19%   |
| Tmpfs   | 1        | 0.06%   |
| Ext3    | 1        | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 738      | 49.63%  |
| GPT     | 430      | 28.92%  |
| Unknown | 319      | 21.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1071     | 69.23%  |
| Yes       | 476      | 30.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 795      | 52.65%  |
| No        | 715      | 47.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 291      | 20.46%  |
| ASUSTek Computer    | 289      | 20.32%  |
| ASRock              | 246      | 17.3%   |
| Dell                | 140      | 9.85%   |
| Hewlett-Packard     | 124      | 8.72%   |
| MSI                 | 85       | 5.98%   |
| Lenovo              | 60       | 4.22%   |
| Fujitsu             | 43       | 3.02%   |
| Fujitsu Siemens     | 25       | 1.76%   |
| Acer                | 22       | 1.55%   |
| Intel               | 21       | 1.48%   |
| Foxconn             | 14       | 0.98%   |
| Unknown             | 13       | 0.91%   |
| Medion              | 8        | 0.56%   |
| Pegatron            | 5        | 0.35%   |
| Biostar             | 4        | 0.28%   |
| AOpen               | 3        | 0.21%   |
| ABIT                | 3        | 0.21%   |
| VXL                 | 2        | 0.14%   |
| Shuttle             | 2        | 0.14%   |
| Nvidia              | 2        | 0.14%   |
| Gateway             | 2        | 0.14%   |
| AMD                 | 2        | 0.14%   |
| Wistron             | 1        | 0.07%   |
| Wincor Nixdorf      | 1        | 0.07%   |
| ViewSonic           | 1        | 0.07%   |
| Supermicro          | 1        | 0.07%   |
| Seeed Studio        | 1        | 0.07%   |
| NEC Computers       | 1        | 0.07%   |
| Minix               | 1        | 0.07%   |
| Lex                 | 1        | 0.07%   |
| JW Technology       | 1        | 0.07%   |
| JGINYUE             | 1        | 0.07%   |
| IBM                 | 1        | 0.07%   |
| Hampoo              | 1        | 0.07%   |
| ECS                 | 1        | 0.07%   |
| ASRockRack          | 1        | 0.07%   |
| Apple               | 1        | 0.07%   |
| AMI                 | 1        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASRock FM2A75M Pro4+               | 33       | 2.32%   |
| ASUS All Series                    | 28       | 1.97%   |
| Dell OptiPlex 3020                 | 17       | 1.2%    |
| Unknown                            | 13       | 0.91%   |
| ASUS P5KPL-AM EPU                  | 12       | 0.84%   |
| Gigabyte G31M-ES2L                 | 11       | 0.77%   |
| Dell OptiPlex 755                  | 11       | 0.77%   |
| Dell OptiPlex 780                  | 10       | 0.7%    |
| Dell OptiPlex 760                  | 9        | 0.63%   |
| Gigabyte H61M-S1                   | 8        | 0.56%   |
| Dell Precision WorkStation T3500   | 8        | 0.56%   |
| Dell OptiPlex 7010                 | 8        | 0.56%   |
| ASRock G41M-VS3                    | 8        | 0.56%   |
| HP ProDesk 600 G2 SFF              | 7        | 0.49%   |
| Gigabyte 970A-DS3P                 | 7        | 0.49%   |
| ASRock N68C-S UCC                  | 7        | 0.49%   |
| HP Compaq 8000 Elite SFF PC        | 6        | 0.42%   |
| Dell OptiPlex 330                  | 6        | 0.42%   |
| Acer Veriton M430                  | 6        | 0.42%   |
| MSI MS-7C02                        | 5        | 0.35%   |
| MSI MS-7592                        | 5        | 0.35%   |
| HP Compaq Elite 8300 SFF           | 5        | 0.35%   |
| HP Compaq dc5850 Small Form Factor | 5        | 0.35%   |
| HP Compaq dc5800 Small Form Factor | 5        | 0.35%   |
| Gigabyte H81M-S1                   | 5        | 0.35%   |
| Gigabyte G41MT-S2PT                | 5        | 0.35%   |
| Gigabyte B450 AORUS ELITE          | 5        | 0.35%   |
| Fujitsu Siemens ESPRIMO E5730      | 5        | 0.35%   |
| Foxconn Pro 3500 Series            | 5        | 0.35%   |
| Dell OptiPlex 9020                 | 5        | 0.35%   |
| Dell OptiPlex 745                  | 5        | 0.35%   |
| Dell OptiPlex 3010                 | 5        | 0.35%   |
| ASUS PRIME A320M-K                 | 5        | 0.35%   |
| ASRock FM2A68M-HD+                 | 5        | 0.35%   |
| ASRock 970 Pro3 R2.0               | 5        | 0.35%   |
| MSI MS-7817                        | 4        | 0.28%   |
| Medion Pentino G-Series            | 4        | 0.28%   |
| HP Compaq Pro 6305 SFF             | 4        | 0.28%   |
| HP Compaq Pro 6300 MT              | 4        | 0.28%   |
| HP Compaq Elite 8300 CMT           | 4        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 112      | 7.88%   |
| HP Compaq               | 89       | 6.26%   |
| Lenovo ThinkCentre      | 46       | 3.23%   |
| ASUS PRIME              | 39       | 2.74%   |
| ASRock FM2A75M          | 33       | 2.32%   |
| Fujitsu ESPRIMO         | 31       | 2.18%   |
| ASUS All                | 28       | 1.97%   |
| Fujitsu Siemens ESPRIMO | 19       | 1.34%   |
| ASUS P5KPL-AM           | 17       | 1.2%    |
| ASUS ROG                | 16       | 1.13%   |
| Acer Veriton            | 16       | 1.13%   |
| Dell Precision          | 15       | 1.05%   |
| Gigabyte B450           | 13       | 0.91%   |
| ASUS TUF                | 13       | 0.91%   |
| Unknown                 | 13       | 0.91%   |
| Gigabyte G31M-ES2L      | 11       | 0.77%   |
| HP ProDesk              | 9        | 0.63%   |
| HP EliteDesk            | 9        | 0.63%   |
| ASUS M5A97              | 9        | 0.63%   |
| Gigabyte H61M-S1        | 8        | 0.56%   |
| Gigabyte B450M          | 8        | 0.56%   |
| Fujitsu CELSIUS         | 8        | 0.56%   |
| ASRock N68C-S           | 8        | 0.56%   |
| ASRock G41M-VS3         | 8        | 0.56%   |
| ASRock 970              | 8        | 0.56%   |
| Gigabyte H310M          | 7        | 0.49%   |
| Gigabyte 970A-DS3P      | 7        | 0.49%   |
| ASUS P8H61-M            | 6        | 0.42%   |
| ASUS M5A78L-M           | 6        | 0.42%   |
| ASUS H110M-A            | 6        | 0.42%   |
| ASRock B450M            | 6        | 0.42%   |
| MSI MS-7C02             | 5        | 0.35%   |
| MSI MS-7592             | 5        | 0.35%   |
| Gigabyte H81M-S1        | 5        | 0.35%   |
| Gigabyte G41MT-S2PT     | 5        | 0.35%   |
| Foxconn Pro             | 5        | 0.35%   |
| Dell Vostro             | 5        | 0.35%   |
| Dell PowerEdge          | 5        | 0.35%   |
| ASRock Z77              | 5        | 0.35%   |
| ASRock Z370             | 5        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 158      | 11.11%  |
| 2013    | 148      | 10.41%  |
| 2010    | 128      | 9%      |
| 2009    | 127      | 8.93%   |
| 2014    | 125      | 8.79%   |
| 2011    | 119      | 8.37%   |
| 2008    | 118      | 8.3%    |
| 2018    | 99       | 6.96%   |
| 2007    | 85       | 5.98%   |
| 2015    | 56       | 3.94%   |
| 2017    | 52       | 3.66%   |
| 2016    | 46       | 3.23%   |
| 2019    | 40       | 2.81%   |
| 2006    | 40       | 2.81%   |
| 2020    | 35       | 2.46%   |
| 2021    | 18       | 1.27%   |
| 2005    | 17       | 1.2%    |
| 2004    | 4        | 0.28%   |
| 2022    | 3        | 0.21%   |
| 2003    | 3        | 0.21%   |
| Unknown | 1        | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1422     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1413     | 99.16%  |
| Enabled  | 12       | 0.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1422     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 414      | 28.16%  |
| 8.01-16.0   | 355      | 24.15%  |
| 4.01-8.0    | 240      | 16.33%  |
| 16.01-24.0  | 217      | 14.76%  |
| 1.01-2.0    | 112      | 7.62%   |
| 32.01-64.0  | 62       | 4.22%   |
| 2.01-3.0    | 31       | 2.11%   |
| 64.01-256.0 | 18       | 1.22%   |
| 24.01-32.0  | 13       | 0.88%   |
| 0.51-1.0    | 8        | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 459      | 27.77%  |
| 0.01-0.5    | 447      | 27.04%  |
| 1.01-2.0    | 435      | 26.32%  |
| 2.01-3.0    | 154      | 9.32%   |
| 4.01-8.0    | 70       | 4.23%   |
| 3.01-4.0    | 65       | 3.93%   |
| 8.01-16.0   | 16       | 0.97%   |
| 16.01-24.0  | 5        | 0.3%    |
| 64.01-256.0 | 1        | 0.06%   |
| Unknown     | 1        | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 741      | 48.05%  |
| 2       | 408      | 26.46%  |
| 3       | 215      | 13.94%  |
| 4       | 86       | 5.58%   |
| 5       | 42       | 2.72%   |
| 0       | 23       | 1.49%   |
| 6       | 11       | 0.71%   |
| 8       | 5        | 0.32%   |
| 7       | 5        | 0.32%   |
| 9       | 3        | 0.19%   |
| 11      | 1        | 0.06%   |
| 10      | 1        | 0.06%   |
| Unknown | 1        | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 849      | 57.68%  |
| No        | 623      | 42.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1402     | 98.59%  |
| No        | 20       | 1.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1086     | 74.64%  |
| Yes       | 369      | 25.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1255     | 86.61%  |
| Yes       | 194      | 13.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Hungary | 1422     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Budapest          | 498      | 30.53%  |
| Szeged            | 39       | 2.39%   |
| Pécs             | 39       | 2.39%   |
| Győr             | 32       | 1.96%   |
| Miskolc           | 27       | 1.66%   |
| Debrecen          | 27       | 1.66%   |
| Kecskemét        | 23       | 1.41%   |
| Tatabánya        | 22       | 1.35%   |
| Szombathely       | 22       | 1.35%   |
| Karcag            | 22       | 1.35%   |
| Érd              | 19       | 1.16%   |
| Székesfehérvár | 17       | 1.04%   |
| Eger              | 17       | 1.04%   |
| Szekszárd        | 16       | 0.98%   |
| Oroshaza          | 16       | 0.98%   |
| Szigetszentmiklos | 15       | 0.92%   |
| Gödöllő        | 14       | 0.86%   |
| Nyiregyhaza       | 13       | 0.8%    |
| Zalaegerszeg      | 12       | 0.74%   |
| Esztergom         | 11       | 0.67%   |
| Toeroekbalint     | 10       | 0.61%   |
| Mosonmagyaróvár | 10       | 0.61%   |
| Hodmezovasarhely  | 10       | 0.61%   |
| Tiszafured        | 9        | 0.55%   |
| Papa              | 9        | 0.55%   |
| Nagykanizsa       | 9        | 0.55%   |
| Hatvan            | 9        | 0.55%   |
| Berettyóújfalu  | 9        | 0.55%   |
| Ajka              | 9        | 0.55%   |
| Veresegyhaz       | 8        | 0.49%   |
| Siófok           | 8        | 0.49%   |
| Gyomro            | 8        | 0.49%   |
| Dunaújváros     | 8        | 0.49%   |
| Dunakeszi         | 8        | 0.49%   |
| Szolnok           | 7        | 0.43%   |
| Sopron            | 7        | 0.43%   |
| Salgotarjan       | 7        | 0.43%   |
| Mohács           | 7        | 0.43%   |
| Gyongyos          | 7        | 0.43%   |
| Dunaharaszti      | 7        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 511      | 991    | 20.66%  |
| Samsung Electronics | 409      | 664    | 16.54%  |
| Seagate             | 367      | 584    | 14.84%  |
| Kingston            | 327      | 569    | 13.22%  |
| Toshiba             | 198      | 341    | 8.01%   |
| Hitachi             | 106      | 144    | 4.29%   |
| A-DATA Technology   | 78       | 122    | 3.15%   |
| Maxtor              | 47       | 62     | 1.9%    |
| SanDisk             | 33       | 36     | 1.33%   |
| Crucial             | 30       | 45     | 1.21%   |
| SPCC                | 29       | 41     | 1.17%   |
| Intel               | 20       | 37     | 0.81%   |
| OCZ                 | 19       | 25     | 0.77%   |
| HGST                | 18       | 38     | 0.73%   |
| Fujitsu             | 17       | 17     | 0.69%   |
| Apacer              | 16       | 22     | 0.65%   |
| China               | 15       | 22     | 0.61%   |
| Intenso             | 14       | 16     | 0.57%   |
| Transcend           | 12       | 14     | 0.49%   |
| Patriot             | 12       | 22     | 0.49%   |
| Hewlett-Packard     | 12       | 16     | 0.49%   |
| Gigabyte Technology | 12       | 31     | 0.49%   |
| Unknown             | 11       | 17     | 0.44%   |
| Kingmax             | 9        | 19     | 0.36%   |
| SK hynix            | 8        | 11     | 0.32%   |
| PNY                 | 8        | 15     | 0.32%   |
| KingSpec            | 8        | 9      | 0.32%   |
| Micron Technology   | 7        | 8      | 0.28%   |
| Zheino              | 6        | 10     | 0.24%   |
| Phison              | 6        | 9      | 0.24%   |
| JMicron Technology  | 6        | 8      | 0.24%   |
| Corsair             | 6        | 7      | 0.24%   |
| Team                | 5        | 7      | 0.2%    |
| LITEON              | 5        | 5      | 0.2%    |
| Verbatim            | 4        | 8      | 0.16%   |
| Netac               | 4        | 9      | 0.16%   |
| HGST HTS            | 4        | 4      | 0.16%   |
| USB3.0              | 3        | 4      | 0.12%   |
| Silicon Motion      | 3        | 4      | 0.12%   |
| Quantum             | 3        | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 73       | 2.61%   |
| Kingston SA400S37120G 120GB SSD  | 68       | 2.43%   |
| Kingston SV300S37A120G 120GB SSD | 56       | 2%      |
| Toshiba DT01ACA100 1TB           | 51       | 1.82%   |
| Seagate ST500DM002-1BD142 500GB  | 45       | 1.61%   |
| Toshiba DT01ACA050 500GB         | 33       | 1.18%   |
| A-DATA SU630 240GB SSD           | 28       | 1%      |
| Seagate ST380815AS 80GB          | 24       | 0.86%   |
| Kingston SUV400S37120G 120GB SSD | 23       | 0.82%   |
| Samsung HD502HJ 500GB            | 22       | 0.79%   |
| Toshiba HDWD130 3TB              | 21       | 0.75%   |
| Toshiba HDWD110 1TB              | 21       | 0.75%   |
| WDC WD10EZEX-08WN4A0 1TB         | 20       | 0.71%   |
| A-DATA SU700 120GB SSD           | 20       | 0.71%   |
| Kingston SA400S37480G 480GB SSD  | 19       | 0.68%   |
| Samsung SSD 860 EVO 250GB        | 18       | 0.64%   |
| Toshiba DT01ACA200 2TB           | 17       | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB   | 16       | 0.57%   |
| Samsung SSD 850 EVO 250GB        | 16       | 0.57%   |
| Kingston SHFS37A120G 120GB SSD   | 16       | 0.57%   |
| Samsung HD322HJ 320GB            | 15       | 0.54%   |
| Hitachi HDS721050CLA360 500GB    | 15       | 0.54%   |
| Seagate ST3160815AS 160GB        | 14       | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB   | 14       | 0.5%    |
| Samsung HD502IJ 500GB            | 14       | 0.5%    |
| Samsung HD161HJ 160GB            | 14       | 0.5%    |
| WDC WD10EZEX-22MFCA0 1TB         | 13       | 0.46%   |
| Kingston SV300S37A240G 240GB SSD | 13       | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 12       | 0.43%   |
| SPCC Solid State Disk 256GB      | 12       | 0.43%   |
| Seagate ST3160318AS 160GB        | 12       | 0.43%   |
| Samsung HD501LJ 500GB            | 12       | 0.43%   |
| Samsung HD103UJ 1TB              | 12       | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 11       | 0.39%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 11       | 0.39%   |
| WDC WD10EZRX-00L4HB0 1TB         | 11       | 0.39%   |
| Seagate ST3250318AS 249GB        | 11       | 0.39%   |
| Samsung HD154UI 1TB              | 11       | 0.39%   |
| WDC WD5000AAKX-001CA0 500GB      | 10       | 0.36%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 10       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 478      | 903    | 32.19%  |
| Seagate             | 362      | 575    | 24.38%  |
| Samsung Electronics | 235      | 362    | 15.82%  |
| Toshiba             | 190      | 332    | 12.79%  |
| Hitachi             | 106      | 144    | 7.14%   |
| Maxtor              | 47       | 62     | 3.16%   |
| HGST                | 18       | 38     | 1.21%   |
| Fujitsu             | 17       | 17     | 1.14%   |
| Hewlett-Packard     | 7        | 7      | 0.47%   |
| HGST HTS            | 4        | 4      | 0.27%   |
| USB3.0              | 3        | 4      | 0.2%    |
| Unknown             | 3        | 4      | 0.2%    |
| Quantum             | 3        | 3      | 0.2%    |
| ASMT                | 3        | 3      | 0.2%    |
| WD MediaMax         | 2        | 4      | 0.13%   |
| ICY BOX             | 2        | 3      | 0.13%   |
| Apple               | 2        | 3      | 0.13%   |
| USB                 | 1        | 1      | 0.07%   |
| IBM/Hitachi         | 1        | 1      | 0.07%   |
| ExcelStor           | 1        | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 304      | 518    | 35.14%  |
| Samsung Electronics | 148      | 220    | 17.11%  |
| A-DATA Technology   | 74       | 114    | 8.55%   |
| WDC                 | 47       | 82     | 5.43%   |
| SanDisk             | 31       | 33     | 3.58%   |
| Crucial             | 26       | 40     | 3.01%   |
| SPCC                | 22       | 33     | 2.54%   |
| OCZ                 | 19       | 25     | 2.2%    |
| Apacer              | 16       | 22     | 1.85%   |
| China               | 15       | 22     | 1.73%   |
| Intel               | 14       | 26     | 1.62%   |
| Transcend           | 11       | 13     | 1.27%   |
| Patriot             | 11       | 21     | 1.27%   |
| Intenso             | 11       | 13     | 1.27%   |
| Gigabyte Technology | 10       | 28     | 1.16%   |
| Toshiba             | 9        | 9      | 1.04%   |
| Kingmax             | 9        | 19     | 1.04%   |
| PNY                 | 8        | 15     | 0.92%   |
| KingSpec            | 8        | 9      | 0.92%   |
| Team                | 5        | 7      | 0.58%   |
| SK hynix            | 5        | 8      | 0.58%   |
| Micron Technology   | 5        | 6      | 0.58%   |
| LITEON              | 5        | 5      | 0.58%   |
| JMicron Technology  | 5        | 7      | 0.58%   |
| Corsair             | 5        | 6      | 0.58%   |
| Verbatim            | 4        | 8      | 0.46%   |
| Netac               | 4        | 9      | 0.46%   |
| Hewlett-Packard     | 3        | 4      | 0.35%   |
| SATAFIRM            | 2        | 2      | 0.23%   |
| Leven               | 2        | 2      | 0.23%   |
| KingFast            | 2        | 2      | 0.23%   |
| KingDian            | 2        | 2      | 0.23%   |
| Integral            | 2        | 2      | 0.23%   |
| GOODRAM             | 2        | 2      | 0.23%   |
| AMD                 | 2        | 2      | 0.23%   |
| WDC WDS             | 1        | 1      | 0.12%   |
| Vaseky              | 1        | 1      | 0.12%   |
| Unknown             | 1        | 2      | 0.12%   |
| TO Exter            | 1        | 1      | 0.12%   |
| Seagate             | 1        | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1118     | 2471   | 55.32%  |
| SSD     | 736      | 1360   | 36.42%  |
| NVMe    | 134      | 222    | 6.63%   |
| Unknown | 26       | 36     | 1.29%   |
| MMC     | 7        | 9      | 0.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1372     | 3750   | 86.95%  |
| NVMe | 133      | 221    | 8.43%   |
| SAS  | 66       | 118    | 4.18%   |
| MMC  | 7        | 9      | 0.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1240     | 2650   | 67.32%  |
| 0.51-1.0   | 377      | 714    | 20.47%  |
| 1.01-2.0   | 129      | 207    | 7%      |
| 2.01-3.0   | 47       | 132    | 2.55%   |
| 3.01-4.0   | 32       | 77     | 1.74%   |
| 4.01-10.0  | 13       | 35     | 0.71%   |
| 10.01-20.0 | 4        | 16     | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 661      | 40.33%  |
| 101-250        | 296      | 18.06%  |
| 251-500        | 169      | 10.31%  |
| 51-100         | 116      | 7.08%   |
| 501-1000       | 95       | 5.8%    |
| 1001-2000      | 76       | 4.64%   |
| 1-20           | 76       | 4.64%   |
| 21-50          | 68       | 4.15%   |
| More than 3000 | 50       | 3.05%   |
| 2001-3000      | 32       | 1.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 661      | 40.5%   |
| 1-20           | 522      | 31.99%  |
| 21-50          | 115      | 7.05%   |
| 51-100         | 84       | 5.15%   |
| 101-250        | 79       | 4.84%   |
| 501-1000       | 58       | 3.55%   |
| 251-500        | 48       | 2.94%   |
| 1001-2000      | 35       | 2.14%   |
| More than 3000 | 20       | 1.23%   |
| 2001-3000      | 10       | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| A-DATA Technology SU630 240GB SSD | 18       | 21     | 3.38%   |
| Seagate ST500DM002-1BD142 500GB   | 16       | 30     | 3%      |
| Kingston SV300S37A120G 120GB SSD  | 13       | 13     | 2.44%   |
| Samsung Electronics HD103UJ 1TB   | 10       | 17     | 1.88%   |
| Toshiba DT01ACA050 500GB          | 8        | 9      | 1.5%    |
| WDC WD5000AAKX-001CA0 500GB       | 6        | 6      | 1.13%   |
| WDC WD5000AADS-00S9B0 500GB       | 6        | 7      | 1.13%   |
| Toshiba DT01ACA100 1TB            | 6        | 12     | 1.13%   |
| Seagate ST3250318AS 249GB         | 5        | 8      | 0.94%   |
| Samsung Electronics HD502HJ 500GB | 5        | 8      | 0.94%   |
| Samsung Electronics HD321KJ 320GB | 5        | 5      | 0.94%   |
| Samsung Electronics HD161HJ 160GB | 5        | 5      | 0.94%   |
| Samsung Electronics HD103SI 1TB   | 5        | 5      | 0.94%   |
| Maxtor 6Y080M0 81GB               | 5        | 6      | 0.94%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 4        | 7      | 0.75%   |
| Seagate ST500LT012-9WS142 500GB   | 4        | 5      | 0.75%   |
| Seagate ST380815AS 80GB           | 4        | 7      | 0.75%   |
| Seagate ST3160815AS 160GB         | 4        | 4      | 0.75%   |
| Samsung Electronics SP2504C 250GB | 4        | 7      | 0.75%   |
| Samsung Electronics SP2004C 200GB | 4        | 7      | 0.75%   |
| Samsung Electronics HD161GJ 160GB | 4        | 5      | 0.75%   |
| Samsung Electronics HD082GJ 80GB  | 4        | 4      | 0.75%   |
| Maxtor 2B020H1 20GB               | 4        | 8      | 0.75%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 3        | 5      | 0.56%   |
| WDC WD5000AAKX-07U6AA0 500GB      | 3        | 5      | 0.56%   |
| WDC WD3200AAKS-00L9A0 320GB       | 3        | 4      | 0.56%   |
| WDC WD15EARS-00MVWB0 1TB          | 3        | 7      | 0.56%   |
| WDC WD10EZEX-22MFCA0 1TB          | 3        | 3      | 0.56%   |
| WDC WD10EARS-00Y5B1 1TB           | 3        | 6      | 0.56%   |
| WDC WD10EALX-009BA0 1TB           | 3        | 3      | 0.56%   |
| SK hynix SC210 2.5 7MM 128GB SSD  | 3        | 6      | 0.56%   |
| Seagate ST4000DM000-1F2168 4TB    | 3        | 8      | 0.56%   |
| Seagate ST3500320AS 500GB         | 3        | 4      | 0.56%   |
| Seagate ST3160812AS 160GB         | 3        | 3      | 0.56%   |
| Seagate ST3160318AS 160GB         | 3        | 3      | 0.56%   |
| Samsung Electronics SP1203N 120GB | 3        | 3      | 0.56%   |
| Samsung Electronics HD642JJ 640GB | 3        | 6      | 0.56%   |
| Samsung Electronics HD502IJ 500GB | 3        | 4      | 0.56%   |
| Samsung Electronics HD501LJ 500GB | 3        | 4      | 0.56%   |
| Samsung Electronics HD322HJ 320GB | 3        | 3      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 142      | 226    | 27.9%   |
| Seagate             | 100      | 145    | 19.65%  |
| Samsung Electronics | 94       | 135    | 18.47%  |
| Hitachi             | 32       | 46     | 6.29%   |
| Toshiba             | 31       | 42     | 6.09%   |
| Kingston            | 28       | 31     | 5.5%    |
| Maxtor              | 26       | 40     | 5.11%   |
| A-DATA Technology   | 22       | 30     | 4.32%   |
| HGST                | 7        | 8      | 1.38%   |
| Fujitsu             | 4        | 4      | 0.79%   |
| SK hynix            | 3        | 6      | 0.59%   |
| Hewlett-Packard     | 3        | 3      | 0.59%   |
| WD MediaMax         | 2        | 4      | 0.39%   |
| KingSpec            | 2        | 2      | 0.39%   |
| SATAFIRM            | 1        | 1      | 0.2%    |
| SanDisk             | 1        | 1      | 0.2%    |
| OCZ                 | 1        | 3      | 0.2%    |
| LITEON              | 1        | 1      | 0.2%    |
| Leven               | 1        | 1      | 0.2%    |
| Kingmax             | 1        | 1      | 0.2%    |
| Intenso             | 1        | 1      | 0.2%    |
| Intel               | 1        | 1      | 0.2%    |
| ICY BOX             | 1        | 1      | 0.2%    |
| IBM/Hitachi         | 1        | 1      | 0.2%    |
| ExcelStor           | 1        | 1      | 0.2%    |
| China               | 1        | 1      | 0.2%    |
| ASMT                | 1        | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 140      | 224    | 31.96%  |
| Seagate             | 100      | 145    | 22.83%  |
| Samsung Electronics | 91       | 132    | 20.78%  |
| Hitachi             | 32       | 46     | 7.31%   |
| Toshiba             | 30       | 41     | 6.85%   |
| Maxtor              | 26       | 40     | 5.94%   |
| HGST                | 7        | 8      | 1.6%    |
| Fujitsu             | 4        | 4      | 0.91%   |
| WD MediaMax         | 2        | 4      | 0.46%   |
| Hewlett-Packard     | 2        | 2      | 0.46%   |
| ICY BOX             | 1        | 1      | 0.23%   |
| IBM/Hitachi         | 1        | 1      | 0.23%   |
| ExcelStor           | 1        | 1      | 0.23%   |
| ASMT                | 1        | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 377      | 650    | 84.53%  |
| SSD  | 67       | 85     | 15.02%  |
| NVMe | 2        | 2      | 0.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502HJ 500GB | 2        | 2      | 25%     |
| Zheino CHN-NGFFNV2280-256 256GB   | 1        | 1      | 12.5%   |
| Seagate ST380815AS 80GB           | 1        | 3      | 12.5%   |
| Samsung Electronics SP0802N 80GB  | 1        | 1      | 12.5%   |
| Samsung Electronics HD204UI 2TB   | 1        | 1      | 12.5%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 2      | 12.5%   |
| Hewlett-Packard SSD EX900 250GB   | 1        | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 62.5%   |
| Zheino              | 1        | 1      | 12.5%   |
| Seagate             | 1        | 3      | 12.5%   |
| Hewlett-Packard     | 1        | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 906      | 2327   | 52.01%  |
| Malfunc  | 430      | 737    | 24.68%  |
| Detected | 398      | 1023   | 22.85%  |
| Failed   | 8        | 11     | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 959      | 54.21%  |
| AMD                              | 391      | 22.1%   |
| JMicron Technology               | 74       | 4.18%   |
| ASMedia Technology               | 60       | 3.39%   |
| Samsung Electronics              | 59       | 3.34%   |
| Nvidia                           | 56       | 3.17%   |
| Marvell Technology Group         | 35       | 1.98%   |
| Kingston Technology Company      | 32       | 1.81%   |
| Phison Electronics               | 19       | 1.07%   |
| VIA Technologies                 | 14       | 0.79%   |
| Silicon Motion                   | 12       | 0.68%   |
| Silicon Image                    | 10       | 0.57%   |
| LSI Logic / Symbios Logic        | 9        | 0.51%   |
| SanDisk                          | 6        | 0.34%   |
| ADATA Technology                 | 5        | 0.28%   |
| Micron/Crucial Technology        | 4        | 0.23%   |
| Integrated Technology Express    | 4        | 0.23%   |
| SK hynix                         | 3        | 0.17%   |
| Micron Technology                | 2        | 0.11%   |
| Broadcom / LSI                   | 2        | 0.11%   |
| Adaptec                          | 2        | 0.11%   |
| Silicon Integrated Systems [SiS] | 1        | 0.06%   |
| Seagate Technology               | 1        | 0.06%   |
| Realtek Semiconductor            | 1        | 0.06%   |
| Promise Technology               | 1        | 0.06%   |
| OCZ Technology Group             | 1        | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.06%   |
| KIOXIA                           | 1        | 0.06%   |
| Initio                           | 1        | 0.06%   |
| HighPoint Technologies           | 1        | 0.06%   |
| Hewlett-Packard                  | 1        | 0.06%   |
| 3ware                            | 1        | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 209      | 8.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 163      | 6.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 127      | 5.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 121      | 4.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 84       | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 81       | 3.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 72       | 2.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 68       | 2.71%   |
| AMD FCH IDE Controller                                                                  | 63       | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 61       | 2.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 61       | 2.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 61       | 2.43%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 53       | 2.11%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 49       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 46       | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 46       | 1.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 46       | 1.84%   |
| Intel SATA Controller [RAID mode]                                                       | 45       | 1.8%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 45       | 1.8%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 43       | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41       | 1.64%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 35       | 1.4%    |
| Nvidia MCP61 SATA Controller                                                            | 27       | 1.08%   |
| JMicron JMB368 IDE controller                                                           | 27       | 1.08%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 26       | 1.04%   |
| Nvidia MCP61 IDE                                                                        | 22       | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                         | 22       | 0.88%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 22       | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 22       | 0.88%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 22       | 0.88%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 20       | 0.8%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 20       | 0.8%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 19       | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 0.76%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 18       | 0.72%   |
| AMD FCH SATA Controller D                                                               | 18       | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17       | 0.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 17       | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16       | 0.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 16       | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 981      | 52.29%  |
| IDE  | 662      | 35.29%  |
| NVMe | 136      | 7.25%   |
| RAID | 82       | 4.37%   |
| SCSI | 8        | 0.43%   |
| SAS  | 7        | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 975      | 68.57%  |
| AMD          | 445      | 31.29%  |
| CentaurHauls | 2        | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 38       | 2.66%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 36       | 2.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27       | 1.89%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 20       | 1.4%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 19       | 1.33%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18       | 1.26%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 16       | 1.12%   |
| AMD FX-8350 Eight-Core Processor            | 16       | 1.12%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15       | 1.05%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 15       | 1.05%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 15       | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 1.05%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 14       | 0.98%   |
| AMD FX-6300 Six-Core Processor              | 14       | 0.98%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 13       | 0.91%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 13       | 0.91%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 13       | 0.91%   |
| Intel Pentium 4 CPU 3.00GHz                 | 11       | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 0.77%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 11       | 0.77%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 10       | 0.7%    |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 10       | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 9        | 0.63%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 9        | 0.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 9        | 0.63%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 9        | 0.63%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 9        | 0.63%   |
| AMD Ryzen 5 3600 6-Core Processor           | 9        | 0.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 9        | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 9        | 0.63%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 8        | 0.56%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 8        | 0.56%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 8        | 0.56%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 8        | 0.56%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 8        | 0.56%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 8        | 0.56%   |
| Intel Celeron CPU E3400 @ 2.60GHz           | 8        | 0.56%   |
| AMD Athlon II X2 260 Processor              | 8        | 0.56%   |
| AMD A4-5300 APU with Radeon HD Graphics     | 8        | 0.56%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 7        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 244      | 17.12%  |
| Intel Core i3           | 137      | 9.61%   |
| Intel Core 2 Duo        | 135      | 9.47%   |
| Intel Core i7           | 67       | 4.7%    |
| Intel Pentium           | 66       | 4.63%   |
| Intel Celeron           | 60       | 4.21%   |
| AMD Ryzen 5             | 60       | 4.21%   |
| Intel Xeon              | 56       | 3.93%   |
| Intel Pentium Dual-Core | 56       | 3.93%   |
| AMD A8                  | 55       | 3.86%   |
| Intel Core 2 Quad       | 52       | 3.65%   |
| AMD FX                  | 47       | 3.3%    |
| AMD Athlon II X2        | 37       | 2.6%    |
| AMD Athlon 64 X2        | 28       | 1.96%   |
| AMD Ryzen 7             | 26       | 1.82%   |
| AMD Ryzen 3             | 24       | 1.68%   |
| Intel Core 2            | 21       | 1.47%   |
| AMD A4                  | 21       | 1.47%   |
| Intel Pentium 4         | 19       | 1.33%   |
| AMD Phenom II X4        | 19       | 1.33%   |
| Intel Pentium Dual      | 16       | 1.12%   |
| Intel Atom              | 15       | 1.05%   |
| AMD A10                 | 14       | 0.98%   |
| AMD A6                  | 13       | 0.91%   |
| Intel Pentium D         | 12       | 0.84%   |
| Other                   | 11       | 0.77%   |
| AMD Sempron             | 11       | 0.77%   |
| AMD Athlon II X4        | 10       | 0.7%    |
| AMD Athlon Dual Core    | 10       | 0.7%    |
| AMD Athlon X4           | 9        | 0.63%   |
| AMD Athlon              | 9        | 0.63%   |
| AMD Ryzen 9             | 6        | 0.42%   |
| AMD Athlon 64           | 6        | 0.42%   |
| AMD Phenom II X6        | 5        | 0.35%   |
| AMD Phenom II X2        | 5        | 0.35%   |
| AMD GX                  | 5        | 0.35%   |
| AMD Phenom              | 4        | 0.28%   |
| Intel Pentium Gold      | 3        | 0.21%   |
| Intel Genuine           | 3        | 0.21%   |
| Intel Celeron D         | 3        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 669      | 46.78%  |
| 4       | 482      | 33.71%  |
| 6       | 110      | 7.69%   |
| 1       | 90       | 6.29%   |
| 8       | 38       | 2.66%   |
| 3       | 26       | 1.82%   |
| 16      | 6        | 0.42%   |
| 12      | 6        | 0.42%   |
| 28      | 1        | 0.07%   |
| 10      | 1        | 0.07%   |
| Unknown | 1        | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1415     | 99.44%  |
| 2      | 8        | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 894      | 62.65%  |
| 2       | 532      | 37.28%  |
| Unknown | 1        | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1410     | 99.09%  |
| 32-bit         | 7        | 0.49%   |
| Unknown        | 6        | 0.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 172      | 11.73%  |
| Unknown    | 168      | 11.46%  |
| 0x306c3    | 126      | 8.59%   |
| 0x206a7    | 106      | 7.23%   |
| 0x306a9    | 95       | 6.48%   |
| 0x06001119 | 76       | 5.18%   |
| 0x506e3    | 47       | 3.21%   |
| 0x010000c8 | 47       | 3.21%   |
| 0x10676    | 38       | 2.59%   |
| 0x906e9    | 32       | 2.18%   |
| 0x0800820d | 29       | 1.98%   |
| 0x6fd      | 28       | 1.91%   |
| 0x6fb      | 28       | 1.91%   |
| 0x906ea    | 26       | 1.77%   |
| 0x06000852 | 24       | 1.64%   |
| 0x08701021 | 16       | 1.09%   |
| 0x6f2      | 15       | 1.02%   |
| 0x106e5    | 15       | 1.02%   |
| 0x10677    | 14       | 0.95%   |
| 0x06003106 | 13       | 0.89%   |
| 0x206c2    | 12       | 0.82%   |
| 0x20655    | 12       | 0.82%   |
| 0x08001138 | 12       | 0.82%   |
| 0x0600084f | 12       | 0.82%   |
| 0x906eb    | 11       | 0.75%   |
| 0x106a5    | 11       | 0.75%   |
| 0xf43      | 10       | 0.68%   |
| 0xa0653    | 10       | 0.68%   |
| 0x0810100b | 10       | 0.68%   |
| 0x03000027 | 10       | 0.68%   |
| 0x010000db | 10       | 0.68%   |
| 0x08108109 | 9        | 0.61%   |
| 0x6f6      | 8        | 0.55%   |
| 0x0600063e | 8        | 0.55%   |
| 0xf41      | 7        | 0.48%   |
| 0x20652    | 7        | 0.48%   |
| 0x0700010f | 7        | 0.48%   |
| 0x06003104 | 7        | 0.48%   |
| 0x010000c7 | 7        | 0.48%   |
| 0xf47      | 6        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 227      | 15.95%  |
| Haswell          | 144      | 10.12%  |
| SandyBridge      | 123      | 8.64%   |
| Piledriver       | 117      | 8.22%   |
| IvyBridge        | 102      | 7.17%   |
| K10              | 94       | 6.61%   |
| Core             | 86       | 6.04%   |
| KabyLake         | 85       | 5.97%   |
| Skylake          | 54       | 3.79%   |
| K8 Hammer        | 50       | 3.51%   |
| Zen+             | 44       | 3.09%   |
| NetBurst         | 43       | 3.02%   |
| Westmere         | 31       | 2.18%   |
| Zen 2            | 30       | 2.11%   |
| Zen              | 30       | 2.11%   |
| Nehalem          | 26       | 1.83%   |
| Steamroller      | 22       | 1.55%   |
| Silvermont       | 14       | 0.98%   |
| CometLake        | 14       | 0.98%   |
| Zen 3            | 13       | 0.91%   |
| Bonnell          | 11       | 0.77%   |
| K10 Llano        | 10       | 0.7%    |
| Jaguar           | 9        | 0.63%   |
| Bulldozer        | 9        | 0.63%   |
| Unknown          | 7        | 0.49%   |
| Puma             | 6        | 0.42%   |
| Goldmont plus    | 6        | 0.42%   |
| Excavator        | 6        | 0.42%   |
| Icelake          | 3        | 0.21%   |
| Bobcat           | 2        | 0.14%   |
| Alderlake Hybrid | 2        | 0.14%   |
| K8 & K10 hybrid  | 1        | 0.07%   |
| K6               | 1        | 0.07%   |
| Goldmont         | 1        | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 519      | 34.37%  |
| Intel                      | 490      | 32.45%  |
| AMD                        | 489      | 32.38%  |
| VIA Technologies           | 6        | 0.4%    |
| ASPEED Technology          | 3        | 0.2%    |
| ATI Technologies           | 2        | 0.13%   |
| Matrox Electronics Systems | 1        | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 76       | 4.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 72       | 4.58%   |
| Nvidia GK208B [GeForce GT 710]                                              | 55       | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 53       | 3.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 47       | 2.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 47       | 2.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 40       | 2.54%   |
| AMD Richland [Radeon HD 8570D]                                              | 37       | 2.35%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 37       | 2.35%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 33       | 2.1%    |
| Intel HD Graphics 530                                                       | 31       | 1.97%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 29       | 1.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 27       | 1.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 24       | 1.53%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 21       | 1.34%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 19       | 1.21%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 19       | 1.21%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 19       | 1.21%   |
| Nvidia GF119 [GeForce GT 610]                                               | 17       | 1.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 15       | 0.95%   |
| Intel HD Graphics 630                                                       | 15       | 0.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14       | 0.89%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 13       | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 12       | 0.76%   |
| Nvidia GF108 [GeForce GT 630]                                               | 12       | 0.76%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 12       | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12       | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 11       | 0.7%    |
| AMD RV710 [Radeon HD 4350/4550]                                             | 11       | 0.7%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 11       | 0.7%    |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 11       | 0.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 10       | 0.64%   |
| AMD RS880 [Radeon HD 4200]                                                  | 10       | 0.64%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 10       | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 9        | 0.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9        | 0.57%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 9        | 0.57%   |
| AMD RS880 [Radeon HD 4250]                                                  | 9        | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 0.51%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 8        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 492      | 33.74%  |
| 1 x Intel           | 441      | 30.25%  |
| 1 x AMD             | 437      | 29.97%  |
| 2 x AMD             | 44       | 3.02%   |
| Intel + Nvidia      | 17       | 1.17%   |
| 1 x VIA             | 6        | 0.41%   |
| Intel + AMD         | 6        | 0.41%   |
| AMD + Nvidia        | 6        | 0.41%   |
| 2 x Nvidia          | 3        | 0.21%   |
| 1 x ASPEED          | 2        | 0.14%   |
| 1 x Matrox          | 1        | 0.07%   |
| 1 x Intel + 3 x AMD | 1        | 0.07%   |
| Intel + 2 x Nvidia  | 1        | 0.07%   |
| AMD + ASPEED        | 1        | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1242     | 86.31%  |
| Proprietary | 137      | 9.52%   |
| Unknown     | 60       | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 537      | 36.06%  |
| 0.51-1.0   | 297      | 19.95%  |
| 0.01-0.5   | 257      | 17.26%  |
| 1.01-2.0   | 211      | 14.17%  |
| 3.01-4.0   | 86       | 5.78%   |
| 7.01-8.0   | 50       | 3.36%   |
| 5.01-6.0   | 29       | 1.95%   |
| 2.01-3.0   | 18       | 1.21%   |
| 16.01-24.0 | 2        | 0.13%   |
| 8.01-16.0  | 2        | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 320      | 22.52%  |
| Goldstar                | 242      | 17.03%  |
| Dell                    | 106      | 7.46%   |
| Ancor Communications    | 85       | 5.98%   |
| Philips                 | 77       | 5.42%   |
| BenQ                    | 76       | 5.35%   |
| Hewlett-Packard         | 66       | 4.64%   |
| Acer                    | 66       | 4.64%   |
| Fujitsu Siemens         | 41       | 2.89%   |
| AOC                     | 26       | 1.83%   |
| Eizo                    | 22       | 1.55%   |
| LG Electronics          | 20       | 1.41%   |
| Lenovo                  | 20       | 1.41%   |
| HannStar                | 19       | 1.34%   |
| Sony                    | 15       | 1.06%   |
| HKC                     | 15       | 1.06%   |
| ASUSTek Computer        | 14       | 0.99%   |
| NEC Computers           | 13       | 0.91%   |
| ViewSonic               | 11       | 0.77%   |
| Vestel Elektronik       | 11       | 0.77%   |
| Medion                  | 11       | 0.77%   |
| Belinea                 | 10       | 0.7%    |
| Unknown                 | 9        | 0.63%   |
| IBM                     | 9        | 0.63%   |
| Arnos Instruments       | 7        | 0.49%   |
| Toshiba                 | 6        | 0.42%   |
| Panasonic               | 6        | 0.42%   |
| Videoseven              | 5        | 0.35%   |
| Plain Tree Systems      | 5        | 0.35%   |
| OEM                     | 5        | 0.35%   |
| MStar                   | 5        | 0.35%   |
| Gericom                 | 5        | 0.35%   |
| FUS                     | 5        | 0.35%   |
| Iiyama                  | 4        | 0.28%   |
| Orion                   | 3        | 0.21%   |
| KTC                     | 3        | 0.21%   |
| Impression              | 3        | 0.21%   |
| Daewoo                  | 3        | 0.21%   |
| Chi Mei Optoelectronics | 3        | 0.21%   |
| ___                     | 2        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                   | 31       | 2.11%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 11       | 0.75%   |
| HKC Monitor HKC1850 1360x768 409x230mm 18.5-inch                      | 11       | 0.75%   |
| HannStar HannsG HS191D HSD0013 1280x1024 376x301mm 19.0-inch          | 11       | 0.75%   |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch       | 11       | 0.75%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 10       | 0.68%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 10       | 0.68%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 10       | 0.68%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 10       | 0.68%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 10       | 0.68%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 9        | 0.61%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 9        | 0.61%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 8        | 0.54%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 8        | 0.54%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 8        | 0.54%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 7        | 0.48%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 7        | 0.48%   |
| Goldstar 2D HD LG TV GSM59CA 1366x768 510x290mm 23.1-inch             | 7        | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6        | 0.41%   |
| Lenovo LEN L171 LEN24C9 1280x1024 337x270mm 17.0-inch                 | 6        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 6        | 0.41%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.41%   |
| Eizo S2202W ENC1976 1680x1050 474x297mm 22.0-inch                     | 6        | 0.41%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 5        | 0.34%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                  | 5        | 0.34%   |
| OEM 22W_LCD_TV OEM3700 1920x1080                                      | 5        | 0.34%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 5        | 0.34%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 5        | 0.34%   |
| Ancor Communications ASUS VW228 ACI22E2 1920x1080 521x293mm 23.5-inch | 5        | 0.34%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 5        | 0.34%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                       | 4        | 0.27%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 4        | 0.27%   |
| Samsung Electronics SMB1920NW SAM06A5 1440x900 408x255mm 18.9-inch    | 4        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 4        | 0.27%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 4        | 0.27%   |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                     | 4        | 0.27%   |
| Hewlett-Packard P222va HWP322B 1920x1080 476x268mm 21.5-inch          | 4        | 0.27%   |
| Hewlett-Packard L1950 HWP26E7 1280x1024 380x300mm 19.1-inch           | 4        | 0.27%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch           | 4        | 0.27%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 4        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 560      | 40.46%  |
| 1280x1024 (SXGA)   | 247      | 17.85%  |
| 1680x1050 (WSXGA+) | 120      | 8.67%   |
| 1440x900 (WXGA+)   | 103      | 7.44%   |
| 3840x2160 (4K)     | 64       | 4.62%   |
| 1366x768 (WXGA)    | 60       | 4.34%   |
| 1360x768           | 33       | 2.38%   |
| 2560x1440 (QHD)    | 29       | 2.1%    |
| 1920x1200 (WUXGA)  | 26       | 1.88%   |
| 2560x1080          | 25       | 1.81%   |
| 1024x768 (XGA)     | 21       | 1.52%   |
| 1600x900 (HD+)     | 20       | 1.45%   |
| Unknown            | 19       | 1.37%   |
| 1920x540           | 11       | 0.79%   |
| 1600x1200          | 8        | 0.58%   |
| 3840x1080          | 7        | 0.51%   |
| 1280x720 (HD)      | 6        | 0.43%   |
| 3440x1440          | 3        | 0.22%   |
| 2288x1287          | 3        | 0.22%   |
| 3840x1200          | 2        | 0.14%   |
| 3280x1080          | 2        | 0.14%   |
| 2048x1152          | 2        | 0.14%   |
| 1280x960           | 2        | 0.14%   |
| 7680x2160          | 1        | 0.07%   |
| 3840x1920          | 1        | 0.07%   |
| 3600x1200          | 1        | 0.07%   |
| 3200x1080          | 1        | 0.07%   |
| 2880x1024          | 1        | 0.07%   |
| 2560x1600          | 1        | 0.07%   |
| 2304x1024          | 1        | 0.07%   |
| 2048x1536          | 1        | 0.07%   |
| 1400x1050          | 1        | 0.07%   |
| 1280x800 (WXGA)    | 1        | 0.07%   |
| 1152x864           | 1        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 212      | 15%     |
| 21      | 197      | 13.94%  |
| 23      | 142      | 10.05%  |
| 17      | 123      | 8.7%    |
| 24      | 122      | 8.63%   |
| 27      | 113      | 8%      |
| 22      | 92       | 6.51%   |
| Unknown | 90       | 6.37%   |
| 18      | 81       | 5.73%   |
| 20      | 41       | 2.9%    |
| 15      | 33       | 2.34%   |
| 34      | 27       | 1.91%   |
| 84      | 24       | 1.7%    |
| 31      | 21       | 1.49%   |
| 40      | 16       | 1.13%   |
| 72      | 14       | 0.99%   |
| 32      | 8        | 0.57%   |
| 65      | 6        | 0.42%   |
| 54      | 6        | 0.42%   |
| 52      | 5        | 0.35%   |
| 42      | 5        | 0.35%   |
| 60      | 4        | 0.28%   |
| 46      | 4        | 0.28%   |
| 64      | 3        | 0.21%   |
| 14      | 3        | 0.21%   |
| 12      | 3        | 0.21%   |
| 58      | 2        | 0.14%   |
| 48      | 2        | 0.14%   |
| 47      | 2        | 0.14%   |
| 39      | 2        | 0.14%   |
| 142     | 1        | 0.07%   |
| 75      | 1        | 0.07%   |
| 63      | 1        | 0.07%   |
| 55      | 1        | 0.07%   |
| 50      | 1        | 0.07%   |
| 49      | 1        | 0.07%   |
| 26      | 1        | 0.07%   |
| 25      | 1        | 0.07%   |
| 13      | 1        | 0.07%   |
| 7       | 1        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 484      | 34.9%   |
| 501-600        | 362      | 26.1%   |
| 301-350        | 148      | 10.67%  |
| 351-400        | 133      | 9.59%   |
| Unknown        | 90       | 6.49%   |
| 1501-2000      | 39       | 2.81%   |
| 1001-1500      | 38       | 2.74%   |
| 701-800        | 35       | 2.52%   |
| 601-700        | 26       | 1.87%   |
| 801-900        | 18       | 1.3%    |
| 201-300        | 7        | 0.5%    |
| 901-1000       | 5        | 0.36%   |
| More than 2000 | 1        | 0.07%   |
| 101-200        | 1        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 729      | 54.4%   |
| 5/4     | 238      | 17.76%  |
| 16/10   | 222      | 16.57%  |
| Unknown | 68       | 5.07%   |
| 4/3     | 44       | 3.28%   |
| 21/9    | 27       | 2.01%   |
| 3/2     | 6        | 0.45%   |
| 6/5     | 4        | 0.3%    |
| 32/9    | 1        | 0.07%   |
| 1.00    | 1        | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 460      | 32.97%  |
| 151-200        | 309      | 22.15%  |
| 141-150        | 186      | 13.33%  |
| 301-350        | 113      | 8.1%    |
| Unknown        | 90       | 6.45%   |
| More than 1000 | 71       | 5.09%   |
| 351-500        | 55       | 3.94%   |
| 251-300        | 40       | 2.87%   |
| 501-1000       | 30       | 2.15%   |
| 101-110        | 22       | 1.58%   |
| 111-120        | 11       | 0.79%   |
| 91-100         | 3        | 0.22%   |
| 71-80          | 2        | 0.14%   |
| 81-90          | 1        | 0.07%   |
| 61-70          | 1        | 0.07%   |
| 1-40           | 1        | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 937      | 70.4%   |
| 101-120 | 224      | 16.83%  |
| Unknown | 90       | 6.76%   |
| 1-50    | 53       | 3.98%   |
| 121-160 | 18       | 1.35%   |
| 161-240 | 9        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1267     | 87.14%  |
| 2     | 122      | 8.39%   |
| 0     | 55       | 3.78%   |
| 3     | 10       | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 810      | 45.13%  |
| Intel                             | 383      | 21.34%  |
| Qualcomm Atheros                  | 163      | 9.08%   |
| Broadcom                          | 68       | 3.79%   |
| Qualcomm Atheros Communications   | 58       | 3.23%   |
| Ralink Technology                 | 48       | 2.67%   |
| Broadcom Limited                  | 43       | 2.4%    |
| Nvidia                            | 39       | 2.17%   |
| TP-Link                           | 35       | 1.95%   |
| Marvell Technology Group          | 25       | 1.39%   |
| Ralink                            | 17       | 0.95%   |
| VIA Technologies                  | 12       | 0.67%   |
| ASUSTek Computer                  | 11       | 0.61%   |
| Samsung Electronics               | 8        | 0.45%   |
| Aquantia                          | 8        | 0.45%   |
| Xiaomi                            | 6        | 0.33%   |
| D-Link System                     | 6        | 0.33%   |
| IMC Networks                      | 5        | 0.28%   |
| Huawei Technologies               | 5        | 0.28%   |
| Belkin Components                 | 5        | 0.28%   |
| Edimax Technology                 | 4        | 0.22%   |
| Accton Technology                 | 4        | 0.22%   |
| Qualcomm                          | 3        | 0.17%   |
| ZyDAS                             | 2        | 0.11%   |
| Sundance Technology Inc / IC Plus | 2        | 0.11%   |
| Microsoft                         | 2        | 0.11%   |
| MediaTek                          | 2        | 0.11%   |
| D-Link                            | 2        | 0.11%   |
| ASIX Electronics                  | 2        | 0.11%   |
| Arduino SA                        | 2        | 0.11%   |
| TRENDnet                          | 1        | 0.06%   |
| Texas Instruments                 | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.06%   |
| ShenZhen ShanWan Technology       | 1        | 0.06%   |
| Seeed Technology                  | 1        | 0.06%   |
| QLogic                            | 1        | 0.06%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.06%   |
| NetGear                           | 1        | 0.06%   |
| Mercucys                          | 1        | 0.06%   |
| JMicron Technology                | 1        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 675      | 35.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 3.93%   |
| Qualcomm Atheros AR9271 802.11n                                   | 51       | 2.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48       | 2.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 46       | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 42       | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34       | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32       | 1.68%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 30       | 1.57%   |
| Intel Ethernet Connection I217-LM                                 | 27       | 1.42%   |
| Nvidia MCP61 Ethernet                                             | 26       | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 25       | 1.31%   |
| Intel I211 Gigabit Network Connection                             | 25       | 1.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 24       | 1.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 21       | 1.1%    |
| Ralink MT7601U Wireless Adapter                                   | 20       | 1.05%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 15       | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 14       | 0.73%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14       | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13       | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 13       | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 13       | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 0.63%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 12       | 0.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 11       | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 11       | 0.58%   |
| Ralink RT5370 Wireless Adapter                                    | 11       | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10       | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 9        | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9        | 0.47%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 9        | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 8        | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 8        | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.42%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 8        | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7        | 0.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 78       | 20.37%  |
| Qualcomm Atheros Communications | 58       | 15.14%  |
| Intel                           | 52       | 13.58%  |
| Qualcomm Atheros                | 49       | 12.79%  |
| Ralink Technology               | 48       | 12.53%  |
| TP-Link                         | 35       | 9.14%   |
| Ralink                          | 17       | 4.44%   |
| ASUSTek Computer                | 11       | 2.87%   |
| IMC Networks                    | 5        | 1.31%   |
| Broadcom                        | 5        | 1.31%   |
| Belkin Components               | 5        | 1.31%   |
| Edimax Technology               | 4        | 1.04%   |
| ZyDAS                           | 2        | 0.52%   |
| Microsoft                       | 2        | 0.52%   |
| D-Link System                   | 2        | 0.52%   |
| VIA Technologies                | 1        | 0.26%   |
| TRENDnet                        | 1        | 0.26%   |
| Texas Instruments               | 1        | 0.26%   |
| NetGear                         | 1        | 0.26%   |
| Mercucys                        | 1        | 0.26%   |
| MediaTek                        | 1        | 0.26%   |
| Marvell Technology Group        | 1        | 0.26%   |
| D-Link                          | 1        | 0.26%   |
| Broadcom Limited                | 1        | 0.26%   |
| Accton Technology               | 1        | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                               | 51       | 13.21%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 25       | 6.48%   |
| Ralink MT7601U Wireless Adapter                                               | 20       | 5.18%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 11       | 2.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 11       | 2.85%   |
| Ralink RT5370 Wireless Adapter                                                | 11       | 2.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 10       | 2.59%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 9        | 2.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 8        | 2.07%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 7        | 1.81%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 7        | 1.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 1.81%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 6        | 1.55%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 6        | 1.55%   |
| Intel Wi-Fi 6 AX200                                                           | 6        | 1.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 5        | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 5        | 1.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 5        | 1.3%    |
| Realtek 802.11ac NIC                                                          | 5        | 1.3%    |
| Ralink RT2070 Wireless Adapter                                                | 5        | 1.3%    |
| Intel Wireless 7260                                                           | 5        | 1.3%    |
| Intel Wireless 3165                                                           | 5        | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 5        | 1.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 4        | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 4        | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 4        | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 4        | 1.04%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 4        | 1.04%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4        | 1.04%   |
| Intel Wireless-AC 9260                                                        | 4        | 1.04%   |
| Intel Wireless 3160                                                           | 4        | 1.04%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                          | 4        | 1.04%   |
| TP-Link Archer T4U ver.3                                                      | 3        | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 3        | 0.78%   |
| Ralink RT2501/RT2573 Wireless Adapter                                         | 3        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3        | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 3        | 0.78%   |
| Intel Wireless 7265                                                           | 3        | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 3        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 776      | 52.33%  |
| Intel                             | 360      | 24.28%  |
| Qualcomm Atheros                  | 118      | 7.96%   |
| Broadcom                          | 63       | 4.25%   |
| Broadcom Limited                  | 42       | 2.83%   |
| Nvidia                            | 39       | 2.63%   |
| Marvell Technology Group          | 24       | 1.62%   |
| VIA Technologies                  | 10       | 0.67%   |
| Samsung Electronics               | 8        | 0.54%   |
| Aquantia                          | 8        | 0.54%   |
| Xiaomi                            | 6        | 0.4%    |
| Huawei Technologies               | 4        | 0.27%   |
| D-Link System                     | 4        | 0.27%   |
| Qualcomm                          | 3        | 0.2%    |
| Accton Technology                 | 3        | 0.2%    |
| Sundance Technology Inc / IC Plus | 2        | 0.13%   |
| ASIX Electronics                  | 2        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.07%   |
| QLogic                            | 1        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 1        | 0.07%   |
| MediaTek                          | 1        | 0.07%   |
| JMicron Technology                | 1        | 0.07%   |
| HMD Global                        | 1        | 0.07%   |
| Hangzhou Silan Microelectronics   | 1        | 0.07%   |
| Google                            | 1        | 0.07%   |
| DisplayLink                       | 1        | 0.07%   |
| D-Link                            | 1        | 0.07%   |
| American Megatrends               | 1        | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 675      | 44.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75       | 4.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48       | 3.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 46       | 3.04%   |
| Intel Ethernet Connection (2) I219-V                              | 42       | 2.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34       | 2.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 32       | 2.11%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 30       | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 27       | 1.78%   |
| Nvidia MCP61 Ethernet                                             | 26       | 1.72%   |
| Intel I211 Gigabit Network Connection                             | 25       | 1.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 24       | 1.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 21       | 1.39%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 15       | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 14       | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14       | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 13       | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 13       | 0.86%   |
| Intel 82579V Gigabit Network Connection                           | 13       | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 0.79%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 12       | 0.79%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10       | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9        | 0.59%   |
| Broadcom Limited NetXtreme BCM5754 Gigabit Ethernet PCI Express   | 9        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 8        | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 8        | 0.53%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 8        | 0.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7        | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 7        | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 7        | 0.46%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 7        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6        | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.4%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 6        | 0.4%    |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 6        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5        | 0.33%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 5        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1402     | 78.99%  |
| WiFi     | 367      | 20.68%  |
| Modem    | 5        | 0.28%   |
| Unknown  | 1        | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1211     | 83.63%  |
| WiFi     | 237      | 16.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1182     | 82.6%   |
| 2     | 201      | 14.05%  |
| 0     | 23       | 1.61%   |
| 3     | 20       | 1.4%    |
| 4     | 4        | 0.28%   |
| 5     | 1        | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1248     | 84.9%   |
| Yes  | 222      | 15.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 90       | 46.39%  |
| Intel                           | 51       | 26.29%  |
| Broadcom                        | 12       | 6.19%   |
| ASUSTek Computer                | 9        | 4.64%   |
| Conwise Technology              | 6        | 3.09%   |
| Realtek Semiconductor           | 4        | 2.06%   |
| Integrated System Solution      | 4        | 2.06%   |
| Qualcomm Atheros Communications | 3        | 1.55%   |
| IMC Networks                    | 3        | 1.55%   |
| Belkin Components               | 3        | 1.55%   |
| Logitech                        | 2        | 1.03%   |
| Hewlett-Packard                 | 2        | 1.03%   |
| Edimax Technology               | 2        | 1.03%   |
| TP-Link                         | 1        | 0.52%   |
| Lite-On Technology              | 1        | 0.52%   |
| Foxconn / Hon Hai               | 1        | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 90       | 46.39%  |
| Intel Bluetooth wireless interface                      | 19       | 9.79%   |
| Intel Wireless-AC 3168 Bluetooth                        | 7        | 3.61%   |
| Intel AX200 Bluetooth                                   | 6        | 3.09%   |
| Conwise CW6622                                          | 6        | 3.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 5        | 2.58%   |
| Intel AX210 Bluetooth                                   | 5        | 2.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 4        | 2.06%   |
| Intel Bluetooth Device                                  | 3        | 1.55%   |
| Broadcom Bluetooth dongle                               | 3        | 1.55%   |
| ASUS Bluetooth Radio                                    | 3        | 1.55%   |
| Logitech BT Mini-Receiver (HCI mode)                    | 2        | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 2        | 1.03%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter   | 2        | 1.03%   |
| Integrated System Solution Bluetooth Device             | 2        | 1.03%   |
| HP Bluetooth Adapter                                    | 2        | 1.03%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2        | 1.03%   |
| Broadcom HP Portable Bumble Bee                         | 2        | 1.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 2        | 1.03%   |
| Broadcom BCM2035 Bluetooth dongle                       | 2        | 1.03%   |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 1.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 2        | 1.03%   |
| TP-Link TPuLink UB500 Adapter                           | 1        | 0.52%   |
| Realtek RTL8821A Bluetooth                              | 1        | 0.52%   |
| Realtek RTL8723B Bluetooth                              | 1        | 0.52%   |
| Realtek  Bluetooth 4.2 Adapter                          | 1        | 0.52%   |
| Realtek Bluetooth Radio                                 | 1        | 0.52%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1        | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1        | 0.52%   |
| Lite-On Bluetooth Device                                | 1        | 0.52%   |
| IMC Networks Bluetooth Radio                            | 1        | 0.52%   |
| IMC Networks Bluetooth Device                           | 1        | 0.52%   |
| IMC Networks BCM20702A0                                 | 1        | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                       | 1        | 0.52%   |
| Broadcom Bluetooth 3.0 Device                           | 1        | 0.52%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter        | 1        | 0.52%   |
| Broadcom BCM2045 Bluetooth                              | 1        | 0.52%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter   | 1        | 0.52%   |
| Belkin Components F8T013 Bluetooth Adapter              | 1        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 918      | 42.27%  |
| AMD                                  | 576      | 26.52%  |
| Nvidia                               | 466      | 21.45%  |
| C-Media Electronics                  | 71       | 3.27%   |
| Creative Labs                        | 33       | 1.52%   |
| Logitech                             | 12       | 0.55%   |
| Texas Instruments                    | 10       | 0.46%   |
| VIA Technologies                     | 9        | 0.41%   |
| JMTek                                | 7        | 0.32%   |
| Generalplus Technology               | 7        | 0.32%   |
| Kingston Technology                  | 5        | 0.23%   |
| Creative Technology                  | 5        | 0.23%   |
| BEHRINGER International              | 5        | 0.23%   |
| ASUSTek Computer                     | 5        | 0.23%   |
| SteelSeries ApS                      | 4        | 0.18%   |
| Samson Technologies                  | 2        | 0.09%   |
| Plantronics                          | 2        | 0.09%   |
| GN Netcom                            | 2        | 0.09%   |
| Focusrite-Novation                   | 2        | 0.09%   |
| Ensoniq                              | 2        | 0.09%   |
| ATI Technologies                     | 2        | 0.09%   |
| Yamaha                               | 1        | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.05%   |
| Tenx Technology                      | 1        | 0.05%   |
| Syntek                               | 1        | 0.05%   |
| Superlux digit                       | 1        | 0.05%   |
| Sunplus Technology                   | 1        | 0.05%   |
| SM950T Microphone                    | 1        | 0.05%   |
| Silicon Integrated Systems [SiS]     | 1        | 0.05%   |
| Sennheiser Communications            | 1        | 0.05%   |
| Rotel                                | 1        | 0.05%   |
| Realtek Semiconductor                | 1        | 0.05%   |
| Promethean Limited                   | 1        | 0.05%   |
| Nektar                               | 1        | 0.05%   |
| MCS                                  | 1        | 0.05%   |
| LG Electronics                       | 1        | 0.05%   |
| KORG                                 | 1        | 0.05%   |
| Jieli Technology                     | 1        | 0.05%   |
| JBL                                  | 1        | 0.05%   |
| Hewlett-Packard                      | 1        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 160      | 6.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 134      | 5.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 125      | 4.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 124      | 4.86%   |
| AMD FCH Azalia Controller                                                         | 123      | 4.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 85       | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 84       | 3.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 76       | 2.98%   |
| AMD Trinity HDMI Audio Controller                                                 | 64       | 2.51%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 61       | 2.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 59       | 2.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 57       | 2.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 53       | 2.08%   |
| Intel 200 Series PCH HD Audio                                                     | 52       | 2.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 51       | 2%      |
| Nvidia High Definition Audio Controller                                           | 50       | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 49       | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 47       | 1.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 42       | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 39       | 1.53%   |
| AMD Starship/Matisse HD Audio Controller                                          | 33       | 1.29%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 33       | 1.29%   |
| Nvidia GP106 High Definition Audio Controller                                     | 31       | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                                     | 31       | 1.22%   |
| AMD Family 17h/19h HD Audio Controller                                            | 31       | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 30       | 1.18%   |
| Nvidia MCP61 High Definition Audio                                                | 26       | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                                | 25       | 0.98%   |
| Nvidia GP108 High Definition Audio Controller                                     | 21       | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 21       | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                | 20       | 0.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 20       | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 19       | 0.74%   |
| Intel Cannon Lake PCH cAVS                                                        | 18       | 0.71%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 18       | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 18       | 0.71%   |
| C-Media Electronics CM108 Audio Controller                                        | 17       | 0.67%   |
| AMD Kabini HDMI/DP Audio                                                          | 17       | 0.67%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 16       | 0.63%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 16       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 389      | 28.01%  |
| Kingston                   | 315      | 22.68%  |
| SK hynix                   | 138      | 9.94%   |
| Samsung Electronics        | 131      | 9.43%   |
| Micron Technology          | 70       | 5.04%   |
| Kingmax                    | 54       | 3.89%   |
| Corsair                    | 49       | 3.53%   |
| Nanya Technology           | 43       | 3.1%    |
| G.Skill                    | 43       | 3.1%    |
| Crucial                    | 43       | 3.1%    |
| Elpida                     | 18       | 1.3%    |
| CSX                        | 15       | 1.08%   |
| Team                       | 10       | 0.72%   |
| Ramaxel Technology         | 10       | 0.72%   |
| A-DATA Technology          | 6        | 0.43%   |
| Melco                      | 5        | 0.36%   |
| Transcend                  | 4        | 0.29%   |
| Patriot                    | 4        | 0.29%   |
| Kingmax Semiconductor      | 4        | 0.29%   |
| Qimonda                    | 3        | 0.22%   |
| OCZ                        | 3        | 0.22%   |
| GeIL                       | 3        | 0.22%   |
| Silicon Power              | 2        | 0.14%   |
| Intersil                   | 2        | 0.14%   |
| H                          | 2        | 0.14%   |
| Golden Empire              | 2        | 0.14%   |
| 48spaces                   | 2        | 0.14%   |
| Unknown                    | 2        | 0.14%   |
| ZION                       | 1        | 0.07%   |
| Unknown (ABCD)             | 1        | 0.07%   |
| Unknown (7F7F7F7F7F970000) | 1        | 0.07%   |
| Unknown (09D5)             | 1        | 0.07%   |
| Unigen                     | 1        | 0.07%   |
| Toshiba-0098               | 1        | 0.07%   |
| Toshiba                    | 1        | 0.07%   |
| Ramos Technology           | 1        | 0.07%   |
| Princeton                  | 1        | 0.07%   |
| Level One Communication    | 1        | 0.07%   |
| Hyundai lnc                | 1        | 0.07%   |
| Hikvision                  | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s    | 42       | 2.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 33       | 2.05%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 33       | 2.05%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3             | 21       | 1.3%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 19       | 1.18%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s    | 18       | 1.12%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 17       | 1.05%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 17       | 1.05%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                | 16       | 0.99%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 16       | 0.99%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s  | 16       | 0.99%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 15       | 0.93%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 12       | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s            | 11       | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s            | 11       | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 11       | 0.68%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 11       | 0.68%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s            | 10       | 0.62%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 10       | 0.62%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 10       | 0.62%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 8        | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 8        | 0.5%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 8        | 0.5%    |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s | 8        | 0.5%    |
| Unknown RAM Module 512MB DIMM SDRAM                    | 7        | 0.43%   |
| Unknown RAM Module 4096MB DIMM SDRAM                   | 7        | 0.43%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                 | 7        | 0.43%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                 | 7        | 0.43%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                 | 7        | 0.43%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s   | 7        | 0.43%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 7        | 0.43%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 7        | 0.43%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s         | 7        | 0.43%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 7        | 0.43%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 7        | 0.43%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 7        | 0.43%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 7        | 0.43%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 6        | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                | 6        | 0.37%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 6        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 471      | 39.02%  |
| DDR4    | 232      | 19.22%  |
| DDR2    | 169      | 14%     |
| Unknown | 150      | 12.43%  |
| SDRAM   | 141      | 11.68%  |
| DDR     | 37       | 3.07%   |
| DDR5    | 5        | 0.41%   |
| LPDDR4  | 1        | 0.08%   |
| DRAM    | 1        | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1117     | 97.13%  |
| SODIMM  | 30       | 2.61%   |
| RIMM    | 2        | 0.17%   |
| FB-DIMM | 1        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 427      | 31.75%  |
| 2048  | 401      | 29.81%  |
| 8192  | 248      | 18.44%  |
| 1024  | 170      | 12.64%  |
| 16384 | 48       | 3.57%   |
| 512   | 32       | 2.38%   |
| 32768 | 15       | 1.12%   |
| 256   | 4        | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 245      | 18.08%  |
| 1333    | 209      | 15.42%  |
| 800     | 154      | 11.37%  |
| 667     | 81       | 5.98%   |
| Unknown | 76       | 5.61%   |
| 2400    | 64       | 4.72%   |
| 1866    | 60       | 4.43%   |
| 2133    | 57       | 4.21%   |
| 3200    | 41       | 3.03%   |
| 3600    | 38       | 2.8%    |
| 1867    | 37       | 2.73%   |
| 400     | 33       | 2.44%   |
| 1066    | 29       | 2.14%   |
| 533     | 22       | 1.62%   |
| 2667    | 21       | 1.55%   |
| 1800    | 14       | 1.03%   |
| 3466    | 13       | 0.96%   |
| 3400    | 13       | 0.96%   |
| 2048    | 13       | 0.96%   |
| 1067    | 13       | 0.96%   |
| 3000    | 12       | 0.89%   |
| 2933    | 10       | 0.74%   |
| 1639    | 10       | 0.74%   |
| 2666    | 9        | 0.66%   |
| 2000    | 9        | 0.66%   |
| 49926   | 6        | 0.44%   |
| 3151    | 6        | 0.44%   |
| 1334    | 6        | 0.44%   |
| 5808    | 4        | 0.3%    |
| 3733    | 4        | 0.3%    |
| 333     | 4        | 0.3%    |
| 3333    | 3        | 0.22%   |
| 2733    | 3        | 0.22%   |
| 2134    | 3        | 0.22%   |
| 1648    | 3        | 0.22%   |
| 1400    | 3        | 0.22%   |
| 266     | 3        | 0.22%   |
| 3866    | 2        | 0.15%   |
| 3334    | 2        | 0.15%   |
| 3007    | 2        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 43       | 47.25%  |
| Samsung Electronics   | 21       | 23.08%  |
| Canon                 | 12       | 13.19%  |
| Brother Industries    | 5        | 5.49%   |
| Seiko Epson           | 4        | 4.4%    |
| QinHeng Electronics   | 2        | 2.2%    |
| Xerox                 | 1        | 1.1%    |
| STMicroelectronics    | 1        | 1.1%    |
| Prolific Technology   | 1        | 1.1%    |
| Lexmark International | 1        | 1.1%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2600 series                                    | 8        | 8.6%    |
| Samsung ML-2010P Mono Laser Printer                       | 5        | 5.38%   |
| Samsung M2020 Series                                      | 5        | 5.38%   |
| HP LaserJet 1020                                          | 4        | 4.3%    |
| Samsung ML-1640 Series Laser Printer                      | 3        | 3.23%   |
| HP Deskjet 2050 J510                                      | 3        | 3.23%   |
| Samsung SCX-3400 Series                                   | 2        | 2.15%   |
| QinHeng CH340S                                            | 2        | 2.15%   |
| HP LaserJet P1005                                         | 2        | 2.15%   |
| HP LaserJet 1018                                          | 2        | 2.15%   |
| HP LaserJet 1010                                          | 2        | 2.15%   |
| HP LaserJet 1000                                          | 2        | 2.15%   |
| HP DeskJet F4100 Printer series                           | 2        | 2.15%   |
| HP Deskjet F2280 series                                   | 2        | 2.15%   |
| HP DeskJet F2100 Printer series                           | 2        | 2.15%   |
| HP Deskjet 3520 series                                    | 2        | 2.15%   |
| HP DeskJet 2130 series                                    | 2        | 2.15%   |
| Canon TS5100 series                                       | 2        | 2.15%   |
| Canon LiDE 400                                            | 2        | 2.15%   |
| Brother HL-1110 series                                    | 2        | 2.15%   |
| Xerox WorkCentre 3119 Series                              | 1        | 1.08%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.08%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 1.08%   |
| Seiko Epson Printer                                       | 1        | 1.08%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 1.08%   |
| Seiko Epson L396 Series                                   | 1        | 1.08%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 1.08%   |
| Samsung SCX-4623 Series                                   | 1        | 1.08%   |
| Samsung ML-1660 Series                                    | 1        | 1.08%   |
| Samsung ML-1630 Series                                    | 1        | 1.08%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 1.08%   |
| Samsung C48x Series                                       | 1        | 1.08%   |
| Prolific PL2305 Parallel Port                             | 1        | 1.08%   |
| Lexmark International InkJet Color Printer                | 1        | 1.08%   |
| HP Smart Install                                          | 1        | 1.08%   |
| HP LaserJet Pro M12a                                      | 1        | 1.08%   |
| HP LaserJet P1102                                         | 1        | 1.08%   |
| HP LaserJet 1022                                          | 1        | 1.08%   |
| HP EWS UPD                                                | 1        | 1.08%   |
| HP Deskjet D1500 series                                   | 1        | 1.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 68.75%  |
| Hewlett-Packard | 3        | 18.75%  |
| UMAX            | 1        | 6.25%   |
| Mustek Systems  | 1        | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 3        | 18.75%  |
| HP Scanjet 300                     | 2        | 12.5%   |
| Canon CanoScan LIDE 25             | 2        | 12.5%   |
| Canon CanoScan LiDE 120            | 2        | 12.5%   |
| Canon CanoScan LiDE 110            | 2        | 12.5%   |
| UMAX Astra 4400/4450               | 1        | 6.25%   |
| Mustek Systems SNAPSCAN e22        | 1        | 6.25%   |
| HP ScanJet 3770                    | 1        | 6.25%   |
| Canon CanoScan N1240U/LiDE 30      | 1        | 6.25%   |
| Canon CanoScan LiDE 100            | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 44       | 25.58%  |
| Microdia                    | 28       | 16.28%  |
| KYE Systems (Mouse Systems) | 16       | 9.3%    |
| Microsoft                   | 14       | 8.14%   |
| Z-Star Microelectronics     | 10       | 5.81%   |
| Trust                       | 6        | 3.49%   |
| Arkmicro Technologies       | 5        | 2.91%   |
| Samsung Electronics         | 4        | 2.33%   |
| LG Electronics              | 4        | 2.33%   |
| GEMBIRD                     | 4        | 2.33%   |
| Pixart Imaging              | 3        | 1.74%   |
| Cubeternet                  | 3        | 1.74%   |
| Creative Technology         | 3        | 1.74%   |
| Chicony Electronics         | 3        | 1.74%   |
| Aveo Technology             | 3        | 1.74%   |
| Realtek Semiconductor       | 2        | 1.16%   |
| MacroSilicon                | 2        | 1.16%   |
| Jieli Technology            | 2        | 1.16%   |
| IMC Networks                | 2        | 1.16%   |
| Hewlett-Packard             | 2        | 1.16%   |
| Generalplus Technology      | 2        | 1.16%   |
| Apple                       | 2        | 1.16%   |
| Xiongmai                    | 1        | 0.58%   |
| Unknown                     | 1        | 0.58%   |
| Teslong Camera              | 1        | 0.58%   |
| Sonix Technology            | 1        | 0.58%   |
| Silicon Motion              | 1        | 0.58%   |
| OmniVision Technologies     | 1        | 0.58%   |
| ANYKA                       | 1        | 0.58%   |
| Alcor Micro                 | 1        | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 16       | 9.25%   |
| Microdia Camera                                       | 14       | 8.09%   |
| Logitech Webcam C600                                  | 7        | 4.05%   |
| Microsoft LifeCam HD-3000                             | 6        | 3.47%   |
| Microdia Sonix USB 2.0 Camera                         | 6        | 3.47%   |
| Logitech Webcam C170                                  | 5        | 2.89%   |
| KYE Systems (Mouse Systems) iSlim 321R                | 5        | 2.89%   |
| Arkmicro USB2.0 PC CAMERA                             | 5        | 2.89%   |
| Z-Star Vimicro USB Camera (Altair)                    | 4        | 2.31%   |
| Z-Star Venus USB2.0 Camera                            | 4        | 2.31%   |
| Samsung Galaxy A5 (MTP)                               | 4        | 2.31%   |
| Microdia USB 2.0 Camera                               | 4        | 2.31%   |
| Logitech HD Webcam C525                               | 4        | 2.31%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320        | 4        | 2.31%   |
| Microsoft LifeCam VX-2000                             | 3        | 1.73%   |
| Trust FHD Webcam                                      | 2        | 1.16%   |
| Trust 17676 Webcam                                    | 2        | 1.16%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 2        | 1.16%   |
| Microsoft LifeCam VX-800                              | 2        | 1.16%   |
| Microsoft LifeCam Studio                              | 2        | 1.16%   |
| Microdia Defender G-Lens 2577 HD720p Camera           | 2        | 1.16%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]         | 2        | 1.16%   |
| Logitech QuickCam Pro 9000                            | 2        | 1.16%   |
| Logitech QuickCam Communicate Deluxe/S7500            | 2        | 1.16%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 2        | 1.16%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera            | 2        | 1.16%   |
| KYE Systems (Mouse Systems) Genius WideCam F100       | 2        | 1.16%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 2        | 1.16%   |
| Jieli USB PHY 2.0                                     | 2        | 1.16%   |
| GEMBIRD USB2.0 PC CAMERA                              | 2        | 1.16%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 2        | 1.16%   |
| Cubeternet USB2.0 Camera                              | 2        | 1.16%   |
| Creative Live! Cam Chat HD [VF0700]                   | 2        | 1.16%   |
| Aveo USB2.0 Camera                                    | 2        | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE                             | 2        | 1.16%   |
| Z-Star Saturn USB 2.0 Camera                          | 1        | 0.58%   |
| Z-Star A4 TECH HD PC Camera                           | 1        | 0.58%   |
| Xiongmai web camera                                   | 1        | 0.58%   |
| Unknown HD camera                                     | 1        | 0.58%   |
| Trust Webcam                                          | 1        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Upek                  | 1        | 50%     |
| Elan Microelectronics | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 50%     |
| Elan fingerprint sensor [FeinTech FPS00200]            | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Gemalto (was Gemplus)     | 1        | 33.33%  |
| Aladdin Knowledge Systems | 1        | 33.33%  |
| Advanced Card Systems     | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 33.33%  |
| Aladdin Knowledge Systems Token JC                | 1        | 33.33%  |
| Advanced Card Systems ACR1252 Dual Reader         | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1284     | 88.07%  |
| 1     | 158      | 10.84%  |
| 2     | 12       | 0.82%   |
| 3     | 2        | 0.14%   |
| 5     | 1        | 0.07%   |
| 4     | 1        | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 111      | 58.73%  |
| Net/wireless             | 26       | 13.76%  |
| Communication controller | 14       | 7.41%   |
| Unassigned class         | 8        | 4.23%   |
| Multimedia controller    | 7        | 3.7%    |
| Camera                   | 4        | 2.12%   |
| Storage/raid             | 3        | 1.59%   |
| Net/ethernet             | 3        | 1.59%   |
| Sound                    | 2        | 1.06%   |
| Fingerprint reader       | 2        | 1.06%   |
| Card reader              | 2        | 1.06%   |
| Bluetooth                | 2        | 1.06%   |
| Storage/ide              | 1        | 0.53%   |
| Storage                  | 1        | 0.53%   |
| Network                  | 1        | 0.53%   |
| Dvb card                 | 1        | 0.53%   |
| Chipcard                 | 1        | 0.53%   |

