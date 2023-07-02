Linux in Chile - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

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

Total: 359

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P7H55-M LX                  | [8a0d6c1825](https://linux-hardware.org/?probe=8a0d6c1825) | Jun 29, 2023 |
| MSI           | 880GM-E41                   | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Unknown       | Unknown                     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| BESSTAR Te... | UM700                       | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [7e8ae5cb7a](https://linux-hardware.org/?probe=7e8ae5cb7a) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| ECS           | H61H2-M17                   | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| ASRock        | Z590 Phantom Gaming 4       | [1e9eef0102](https://linux-hardware.org/?probe=1e9eef0102) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Intel         | H61                         | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| ASUSTek       | PRIME B560M-K               | [ce0391bdee](https://linux-hardware.org/?probe=ce0391bdee) | May 09, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c8b7ffa6dc](https://linux-hardware.org/?probe=c8b7ffa6dc) | May 02, 2023 |
| ASUSTek       | PRIME J4005I-C              | [611ed4a200](https://linux-hardware.org/?probe=611ed4a200) | May 01, 2023 |
| Gigabyte      | B550M DS3H                  | [1950979b24](https://linux-hardware.org/?probe=1950979b24) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| WZA300S2R1... | SA300-D4                    | [e2a6ae91b9](https://linux-hardware.org/?probe=e2a6ae91b9) | Apr 17, 2023 |
| HP            | 8433 11                     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MS-7360                     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| ASRock        | B360M/OEM                   | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| Unknown       | X99-GT                      | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| HP            | 8433 11                     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| MSI           | Z270 GAMING M3              | [2c25601c7c](https://linux-hardware.org/?probe=2c25601c7c) | Mar 22, 2023 |
| HP            | 18E7                        | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| MSI           | MS-7360                     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| MSI           | H110M PRO-VH PLUS           | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| MSI           | X58 PLATINUM SLI            | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| HP            | 339A                        | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Dell          | 0NW6H5 A00                  | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| MSI           | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| Gigabyte      | B450M DS3H V2               | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| HP            | 1850                        | [54f5b16151](https://linux-hardware.org/?probe=54f5b16151) | Feb 11, 2023 |
| MSI           | 970 GAMING                  | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3fce6d5f05](https://linux-hardware.org/?probe=3fce6d5f05) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [104a086d29](https://linux-hardware.org/?probe=104a086d29) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [578b166faa](https://linux-hardware.org/?probe=578b166faa) | Feb 05, 2023 |
| Dell          | 06D7TR A02                  | [b3bb51473f](https://linux-hardware.org/?probe=b3bb51473f) | Feb 01, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| ViewSonic     | VOT132                      | [a8ecfadd53](https://linux-hardware.org/?probe=a8ecfadd53) | Jan 30, 2023 |
| Dell          | 06D7TR A02                  | [cd487a22cd](https://linux-hardware.org/?probe=cd487a22cd) | Jan 25, 2023 |
| HP            | 2ADE                        | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| ASUSTek       | F2A55-M LK2                 | [93db1bee75](https://linux-hardware.org/?probe=93db1bee75) | Jan 23, 2023 |
| ASUSTek       | H110M-R                     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| MSI           | H81M-E33                    | [ddb1be1cc6](https://linux-hardware.org/?probe=ddb1be1cc6) | Jan 18, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [1a68bed616](https://linux-hardware.org/?probe=1a68bed616) | Jan 12, 2023 |
| HP            | 83F2                        | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [247bb9fe04](https://linux-hardware.org/?probe=247bb9fe04) | Jan 10, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| HP            | 8309                        | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| MSI           | A320M-A PRO MAX             | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| Pegatron      | IPPCR-SS                    | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| Huanan        | X99-QD4 V1.0                | [2e4c04ada0](https://linux-hardware.org/?probe=2e4c04ada0) | Oct 27, 2022 |
| Huanan        | X99-QD4 V1.0                | [cb31f9ab8b](https://linux-hardware.org/?probe=cb31f9ab8b) | Oct 26, 2022 |
| HP            | 225E                        | [7e246d254b](https://linux-hardware.org/?probe=7e246d254b) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| ASUSTek       | P5B-Deluxe                  | [e3dcca8113](https://linux-hardware.org/?probe=e3dcca8113) | Oct 11, 2022 |
| ASUSTek       | P5B-Deluxe                  | [cf179c716e](https://linux-hardware.org/?probe=cf179c716e) | Sep 27, 2022 |
| ASUSTek       | PRIME A320M-K               | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| Dell          | 060K5C A00                  | [a64a44387b](https://linux-hardware.org/?probe=a64a44387b) | Sep 13, 2022 |
| BESSTAR Te... | UM700                       | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ECS           | H61H-G11/7.0                | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| MSI           | H81M-E33                    | [ec88b5b492](https://linux-hardware.org/?probe=ec88b5b492) | Sep 02, 2022 |
| ASRock        | X99 Taichi                  | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |
| SZMZ          | X99M-G2                     | [eff1231310](https://linux-hardware.org/?probe=eff1231310) | Aug 31, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [93f28535f8](https://linux-hardware.org/?probe=93f28535f8) | Aug 23, 2022 |
| MSI           | H81M-E33                    | [56808775ee](https://linux-hardware.org/?probe=56808775ee) | Aug 23, 2022 |
| Intel         | X79M-S                      | [b6746f7b8d](https://linux-hardware.org/?probe=b6746f7b8d) | Aug 18, 2022 |
| Intel         | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [3db0355713](https://linux-hardware.org/?probe=3db0355713) | Aug 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f9efd8697b](https://linux-hardware.org/?probe=f9efd8697b) | Aug 11, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [18b6026d87](https://linux-hardware.org/?probe=18b6026d87) | Aug 09, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Intel         | D54250WYK H13922-303        | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| Olidata       | Unknown                     | [ac7a530d9d](https://linux-hardware.org/?probe=ac7a530d9d) | Jul 19, 2022 |
| Gigabyte      | H410M H                     | [8a0a0ed167](https://linux-hardware.org/?probe=8a0a0ed167) | Jul 16, 2022 |
| Gigabyte      | H410M H                     | [e94723280f](https://linux-hardware.org/?probe=e94723280f) | Jul 16, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c96551a28](https://linux-hardware.org/?probe=0c96551a28) | Jul 09, 2022 |
| MSI           | B350 GAMING PLUS            | [de014d917d](https://linux-hardware.org/?probe=de014d917d) | Jul 05, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [576c9acdaa](https://linux-hardware.org/?probe=576c9acdaa) | Jun 08, 2022 |
| Intel         | DH61BF AAG81311-101         | [b1fe95fd93](https://linux-hardware.org/?probe=b1fe95fd93) | May 31, 2022 |
| ECS           | MCP61M-M3                   | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [b7b419d941](https://linux-hardware.org/?probe=b7b419d941) | May 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [713dcb3d05](https://linux-hardware.org/?probe=713dcb3d05) | May 17, 2022 |
| HP            | 2ADE                        | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f2f965ba56](https://linux-hardware.org/?probe=f2f965ba56) | May 13, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [21e4e874a2](https://linux-hardware.org/?probe=21e4e874a2) | May 06, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [37e77cbfe5](https://linux-hardware.org/?probe=37e77cbfe5) | May 06, 2022 |
| MSI           | B250M GAMING PRO            | [cd1e81afae](https://linux-hardware.org/?probe=cd1e81afae) | May 03, 2022 |
| MSI           | B250M GAMING PRO            | [bf6d6784ab](https://linux-hardware.org/?probe=bf6d6784ab) | May 03, 2022 |
| MSI           | B450M BAZOOKA               | [a913401ce9](https://linux-hardware.org/?probe=a913401ce9) | May 02, 2022 |
| MSI           | B450M BAZOOKA               | [726be8a4f1](https://linux-hardware.org/?probe=726be8a4f1) | May 02, 2022 |
| ASUSTek       | H110M-R                     | [0fa0b3d5f4](https://linux-hardware.org/?probe=0fa0b3d5f4) | May 01, 2022 |
| MSI           | H110M PRO-VH PLUS           | [876baf36d7](https://linux-hardware.org/?probe=876baf36d7) | Apr 29, 2022 |
| Intel         | DH61BF AAG81311-101         | [f40f12b9be](https://linux-hardware.org/?probe=f40f12b9be) | Apr 27, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [cb4bc274b3](https://linux-hardware.org/?probe=cb4bc274b3) | Apr 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [79eb10a5ef](https://linux-hardware.org/?probe=79eb10a5ef) | Apr 19, 2022 |
| MSI           | H81M-E33                    | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| MSI           | B350 TOMAHAWK               | [f531f62c1b](https://linux-hardware.org/?probe=f531f62c1b) | Apr 03, 2022 |
| HP            | 1998                        | [13b901f36a](https://linux-hardware.org/?probe=13b901f36a) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| ASUSTek       | PRIME H410M-E               | [e02f2032f1](https://linux-hardware.org/?probe=e02f2032f1) | Mar 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9183654349](https://linux-hardware.org/?probe=9183654349) | Mar 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [539ebb7dd9](https://linux-hardware.org/?probe=539ebb7dd9) | Mar 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [671a3fc70b](https://linux-hardware.org/?probe=671a3fc70b) | Mar 12, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [332a3f936b](https://linux-hardware.org/?probe=332a3f936b) | Feb 28, 2022 |
| ASUSTek       | B85-PRO GAMER               | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Dell          | 0CT017                      | [27a31fcb1b](https://linux-hardware.org/?probe=27a31fcb1b) | Feb 17, 2022 |
| Gigabyte      | B450M DS3H V2               | [824518037a](https://linux-hardware.org/?probe=824518037a) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| Gigabyte      | B560M DS3H                  | [3c0ad9ce1b](https://linux-hardware.org/?probe=3c0ad9ce1b) | Feb 08, 2022 |
| MSI           | H310M GAMING ARCTIC         | [842ee88335](https://linux-hardware.org/?probe=842ee88335) | Jan 26, 2022 |
| MSI           | B85M-E33 V2                 | [ef65c0c144](https://linux-hardware.org/?probe=ef65c0c144) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [8107f2613f](https://linux-hardware.org/?probe=8107f2613f) | Jan 05, 2022 |
| ASRock        | B550 Steel Legend           | [704e9c09ad](https://linux-hardware.org/?probe=704e9c09ad) | Jan 05, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [2e00250378](https://linux-hardware.org/?probe=2e00250378) | Dec 16, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| MSI           | 3664h                       | [c4bc6c8049](https://linux-hardware.org/?probe=c4bc6c8049) | Nov 29, 2021 |
| ASUSTek       | PRIME Z590-P                | [6490a6beba](https://linux-hardware.org/?probe=6490a6beba) | Nov 29, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [e9b3a62560](https://linux-hardware.org/?probe=e9b3a62560) | Nov 26, 2021 |
| ASUSTek       | PRIME X570-PRO              | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| HP            | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| MSI           | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| Nvidia        | NF-MCP61                    | [666f204c08](https://linux-hardware.org/?probe=666f204c08) | Oct 18, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [8f7c7a493b](https://linux-hardware.org/?probe=8f7c7a493b) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | PRIME Z590-P                | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| Intel         | DG41WV AAE90316-103         | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| Gigabyte      | A520M DS3H                  | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LX                  | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Huanan        | X79 249PC V2.3              | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
| ASRock        | Z490 Phantom Gaming 4G      | [7857ce2ffa](https://linux-hardware.org/?probe=7857ce2ffa) | Sep 16, 2021 |
| ASUSTek       | B85M-E                      | [27a6448b5e](https://linux-hardware.org/?probe=27a6448b5e) | Sep 12, 2021 |
| HC            | HCAR357-MI V1.0             | [e2df45f5f6](https://linux-hardware.org/?probe=e2df45f5f6) | Sep 12, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | B85M-E                      | [36685ad5ea](https://linux-hardware.org/?probe=36685ad5ea) | Sep 11, 2021 |
| HP            | 339A                        | [ae80063e20](https://linux-hardware.org/?probe=ae80063e20) | Sep 07, 2021 |
| HC            | HCAR357-MI V1.0             | [14536c9a37](https://linux-hardware.org/?probe=14536c9a37) | Sep 06, 2021 |
| Intel         | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| HP            | 339A                        | [ceb91782c2](https://linux-hardware.org/?probe=ceb91782c2) | Sep 05, 2021 |
| HC            | HCAR357-MI V1.0             | [3697a37403](https://linux-hardware.org/?probe=3697a37403) | Sep 04, 2021 |
| HC            | HCAR357-MI V1.0             | [e4d2306204](https://linux-hardware.org/?probe=e4d2306204) | Sep 04, 2021 |
| HP            | 339A                        | [2c96fd74fb](https://linux-hardware.org/?probe=2c96fd74fb) | Sep 04, 2021 |
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Gigabyte      | H97M-D3H                    | [a2afd00e64](https://linux-hardware.org/?probe=a2afd00e64) | Aug 26, 2021 |
| Dell          | 0GDG8Y A00                  | [2a0bf4d1a9](https://linux-hardware.org/?probe=2a0bf4d1a9) | Aug 21, 2021 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0eb2abca1d](https://linux-hardware.org/?probe=0eb2abca1d) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | [9c25f25e8f](https://linux-hardware.org/?probe=9c25f25e8f) | Aug 16, 2021 |
| Pegatron      | 2ADC                        | [48cc7f548e](https://linux-hardware.org/?probe=48cc7f548e) | Aug 13, 2021 |
| MSI           | B75MA-E33                   | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [482c64a9c9](https://linux-hardware.org/?probe=482c64a9c9) | Aug 03, 2021 |
| ASUSTek       | PRIME B450M-A               | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60b58b4557](https://linux-hardware.org/?probe=60b58b4557) | Jul 28, 2021 |
| ASUSTek       | PRIME H410M-E               | [cae2419e98](https://linux-hardware.org/?probe=cae2419e98) | Jul 25, 2021 |
| MSI           | 3664h                       | [491117f46c](https://linux-hardware.org/?probe=491117f46c) | Jul 25, 2021 |
| MSI           | 3664h                       | [c9f3c48709](https://linux-hardware.org/?probe=c9f3c48709) | Jul 24, 2021 |
| ASUSTek       | PRIME B450M-A               | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| MSI           | H81M-E33                    | [f56f54e2fa](https://linux-hardware.org/?probe=f56f54e2fa) | Jul 18, 2021 |
| ASUSTek       | PRIME X570-P                | [783a5cafc2](https://linux-hardware.org/?probe=783a5cafc2) | Jul 18, 2021 |
| eMachines     | EL1352                      | [83c494c15a](https://linux-hardware.org/?probe=83c494c15a) | Jul 17, 2021 |
| R-StyleCom... | ALICON AI2S-A21 00.69       | [85a8017eaf](https://linux-hardware.org/?probe=85a8017eaf) | Jul 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5320824c78](https://linux-hardware.org/?probe=5320824c78) | Jul 11, 2021 |
| Dell          | 0Y5DDC A00                  | [1888baa539](https://linux-hardware.org/?probe=1888baa539) | Jul 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| MSI           | A75MA-G55                   | [3611191f22](https://linux-hardware.org/?probe=3611191f22) | Jun 30, 2021 |
| Intel         | X79 V2.72B                  | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Unknown       | Intel X79                   | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| MSI           | 970A-G46                    | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Intel         | DZ77GA-70K AAG39009-401     | [a88c5c7685](https://linux-hardware.org/?probe=a88c5c7685) | Jun 09, 2021 |
| ASUSTek       | PRIME X570-P                | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| ASUSTek       | P5K3 Deluxe                 | [458525ba70](https://linux-hardware.org/?probe=458525ba70) | May 22, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [0be7d156c5](https://linux-hardware.org/?probe=0be7d156c5) | May 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [493edc40c4](https://linux-hardware.org/?probe=493edc40c4) | May 15, 2021 |
| Intel         | YL-3160L2                   | [c282d94246](https://linux-hardware.org/?probe=c282d94246) | May 13, 2021 |
| Lenovo        | ThinkCentre M55 8808E19     | [a53c13a5c9](https://linux-hardware.org/?probe=a53c13a5c9) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | [1fba25dbcf](https://linux-hardware.org/?probe=1fba25dbcf) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | [c71715672c](https://linux-hardware.org/?probe=c71715672c) | May 12, 2021 |
| Olidata       | Unknown                     | [1dc7094a4d](https://linux-hardware.org/?probe=1dc7094a4d) | May 09, 2021 |
| HP            | 339A                        | [c103096e94](https://linux-hardware.org/?probe=c103096e94) | May 09, 2021 |
| HP            | 339A                        | [1b94801e8b](https://linux-hardware.org/?probe=1b94801e8b) | May 09, 2021 |
| Olidata       | Unknown                     | [0c2f6b27a9](https://linux-hardware.org/?probe=0c2f6b27a9) | May 08, 2021 |
| MSI           | H81M-E33                    | [47447aaec1](https://linux-hardware.org/?probe=47447aaec1) | May 05, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [ef811a6184](https://linux-hardware.org/?probe=ef811a6184) | May 01, 2021 |
| Gigabyte      | B450M GAMING                | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| ASUSTek       | P5K SE                      | [73a2ad1fd9](https://linux-hardware.org/?probe=73a2ad1fd9) | Apr 18, 2021 |
| ECS           | MCP61M-M3                   | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| MSI           | H81M-E33                    | [a5ebd5e702](https://linux-hardware.org/?probe=a5ebd5e702) | Apr 13, 2021 |
| Unknown       | Unknown                     | [a13b6fcbcd](https://linux-hardware.org/?probe=a13b6fcbcd) | Apr 12, 2021 |
| ASUSTek       | PRIME J4005I-C              | [5a1bc2f8fe](https://linux-hardware.org/?probe=5a1bc2f8fe) | Apr 10, 2021 |
| ASUSTek       | PRIME J4005I-C              | [79f36c06be](https://linux-hardware.org/?probe=79f36c06be) | Apr 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [8e2a8be8ce](https://linux-hardware.org/?probe=8e2a8be8ce) | Apr 06, 2021 |
| Foxconn       | G31MV/G31MV-K FAB           | [18047eb612](https://linux-hardware.org/?probe=18047eb612) | Apr 01, 2021 |
| ASUSTek       | P5K SE                      | [fb06c3aee0](https://linux-hardware.org/?probe=fb06c3aee0) | Mar 31, 2021 |
| ASUSTek       | P5K SE                      | [22e69da73a](https://linux-hardware.org/?probe=22e69da73a) | Mar 30, 2021 |
| MSI           | 970A-G46                    | [09083497aa](https://linux-hardware.org/?probe=09083497aa) | Mar 26, 2021 |
| MSI           | 970A-G46                    | [dfb535cf31](https://linux-hardware.org/?probe=dfb535cf31) | Mar 26, 2021 |
| HP            | 18E9                        | [db74abc8b8](https://linux-hardware.org/?probe=db74abc8b8) | Mar 23, 2021 |
| HP            | 18E9                        | [13bfb17279](https://linux-hardware.org/?probe=13bfb17279) | Mar 23, 2021 |
| HP            | ProLiant ML10               | [1b448e4a71](https://linux-hardware.org/?probe=1b448e4a71) | Mar 23, 2021 |
| HP            | ProLiant ML10               | [cd6b0c3826](https://linux-hardware.org/?probe=cd6b0c3826) | Mar 22, 2021 |
| ASUSTek       | H110M-D                     | [da2dd5ad1a](https://linux-hardware.org/?probe=da2dd5ad1a) | Mar 15, 2021 |
| ECS           | A740GM-M                    | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| Intel         | X79 V1.x                    | [2b98f9b956](https://linux-hardware.org/?probe=2b98f9b956) | Mar 08, 2021 |
| Gigabyte      | 970A-DS3P                   | [000cba3fb5](https://linux-hardware.org/?probe=000cba3fb5) | Feb 28, 2021 |
| ASUSTek       | M5A97 R2.0                  | [485a4f1e98](https://linux-hardware.org/?probe=485a4f1e98) | Feb 25, 2021 |
| Unknown       | AD12-B                      | [8167d089b9](https://linux-hardware.org/?probe=8167d089b9) | Feb 20, 2021 |
| MSI           | MS-7267                     | [79cfa785c3](https://linux-hardware.org/?probe=79cfa785c3) | Feb 16, 2021 |
| MSI           | MS-7267                     | [9677e2392c](https://linux-hardware.org/?probe=9677e2392c) | Feb 16, 2021 |
| Dell          | 0CRH6C A01                  | [31da132ae8](https://linux-hardware.org/?probe=31da132ae8) | Feb 08, 2021 |
| Dell          | 0CRH6C A01                  | [8e9e7ffea0](https://linux-hardware.org/?probe=8e9e7ffea0) | Feb 08, 2021 |
| Unknown       | AD12-B                      | [6635cbda4d](https://linux-hardware.org/?probe=6635cbda4d) | Feb 06, 2021 |
| Unknown       | AD12-B                      | [05ad299f0e](https://linux-hardware.org/?probe=05ad299f0e) | Feb 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [121e3e7d2d](https://linux-hardware.org/?probe=121e3e7d2d) | Feb 02, 2021 |
| HP            | 2ADE                        | [2ee5093250](https://linux-hardware.org/?probe=2ee5093250) | Feb 02, 2021 |
| ECS           | MCP61M-M3                   | [445f06dbde](https://linux-hardware.org/?probe=445f06dbde) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [1a8312f66a](https://linux-hardware.org/?probe=1a8312f66a) | Jan 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [b024bfc145](https://linux-hardware.org/?probe=b024bfc145) | Jan 29, 2021 |
| Intel         | SHARKBAY                    | [c1df3dc860](https://linux-hardware.org/?probe=c1df3dc860) | Jan 21, 2021 |
| IBM           | 813311S                     | [c65634928d](https://linux-hardware.org/?probe=c65634928d) | Jan 20, 2021 |
| IBM           | 813311S                     | [9dc5e1fd39](https://linux-hardware.org/?probe=9dc5e1fd39) | Jan 19, 2021 |
| Huanan        | X79 VAA1                    | [d88d20e6fc](https://linux-hardware.org/?probe=d88d20e6fc) | Jan 15, 2021 |
| MSI           | B360M PRO-VH                | [f666aa301e](https://linux-hardware.org/?probe=f666aa301e) | Jan 08, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [fb56fb77b9](https://linux-hardware.org/?probe=fb56fb77b9) | Jan 07, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | [74ccd1687d](https://linux-hardware.org/?probe=74ccd1687d) | Dec 24, 2020 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [df5beb221f](https://linux-hardware.org/?probe=df5beb221f) | Nov 15, 2020 |
| Gigabyte      | H97-Gaming 3                | [2c19015153](https://linux-hardware.org/?probe=2c19015153) | Nov 05, 2020 |
| ECS           | A785GM-M                    | [fa61acdd56](https://linux-hardware.org/?probe=fa61acdd56) | Oct 30, 2020 |
| ASUSTek       | A68HM-PLUS                  | [e31a805419](https://linux-hardware.org/?probe=e31a805419) | Oct 24, 2020 |
| ASUSTek       | M5A99X EVO                  | [e2a0899961](https://linux-hardware.org/?probe=e2a0899961) | Oct 23, 2020 |
| ASUSTek       | A68HM-PLUS                  | [e1ac94acb7](https://linux-hardware.org/?probe=e1ac94acb7) | Oct 23, 2020 |
| Intel         | X99                         | [53e51e0b25](https://linux-hardware.org/?probe=53e51e0b25) | Oct 22, 2020 |
| Intel         | X99                         | [194038048f](https://linux-hardware.org/?probe=194038048f) | Oct 22, 2020 |
| MSI           | B75MA-E33                   | [1616dff15a](https://linux-hardware.org/?probe=1616dff15a) | Oct 04, 2020 |
| Intel         | DH55PJ AAE93812-301         | [f6a0fd4389](https://linux-hardware.org/?probe=f6a0fd4389) | Sep 30, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [5e196929f0](https://linux-hardware.org/?probe=5e196929f0) | Sep 28, 2020 |
| ASUSTek       | F2A55-M LK2                 | [0ad4bcad78](https://linux-hardware.org/?probe=0ad4bcad78) | Sep 23, 2020 |
| HP            | 2ADE                        | [0ac3191171](https://linux-hardware.org/?probe=0ac3191171) | Sep 10, 2020 |
| HP            | 2ADE                        | [1cf059d943](https://linux-hardware.org/?probe=1cf059d943) | Sep 10, 2020 |
| MSI           | H61M-P20                    | [9eafb382df](https://linux-hardware.org/?probe=9eafb382df) | Aug 28, 2020 |
| HP            | 81C3                        | [d558ddad9e](https://linux-hardware.org/?probe=d558ddad9e) | Aug 22, 2020 |
| PCPartner     | G43-F71862                  | [6f7db25de0](https://linux-hardware.org/?probe=6f7db25de0) | Aug 12, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [55195790be](https://linux-hardware.org/?probe=55195790be) | Aug 10, 2020 |
| AMI           | Cherry Trail CR             | [69e0a22aed](https://linux-hardware.org/?probe=69e0a22aed) | Aug 07, 2020 |
| Gigabyte      | H310M H x.x                 | [8067b679a3](https://linux-hardware.org/?probe=8067b679a3) | Aug 06, 2020 |
| MSI           | H61M-P20                    | [594f095da2](https://linux-hardware.org/?probe=594f095da2) | Aug 02, 2020 |
| Dell          | 0GDG8Y A00                  | [a1fb518075](https://linux-hardware.org/?probe=a1fb518075) | Jul 12, 2020 |
| Dell          | 0GDG8Y A00                  | [8bb25da515](https://linux-hardware.org/?probe=8bb25da515) | Jul 09, 2020 |
| ASRock        | B450M Pro4                  | [06da0a5ed7](https://linux-hardware.org/?probe=06da0a5ed7) | Jul 05, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4788e05f08](https://linux-hardware.org/?probe=4788e05f08) | Jul 01, 2020 |
| ASUSTek       | P5KPL-AM                    | [8b9bb2543f](https://linux-hardware.org/?probe=8b9bb2543f) | Jun 28, 2020 |
| ASUSTek       | M5A78L-M LX                 | [ee35b699fa](https://linux-hardware.org/?probe=ee35b699fa) | Jun 24, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [646f93ec3a](https://linux-hardware.org/?probe=646f93ec3a) | Jun 20, 2020 |
| Apple         | Mac-F42C88C8 Proto1         | [08ce018dd0](https://linux-hardware.org/?probe=08ce018dd0) | Jun 20, 2020 |
| MSI           | MS-7379                     | [b7f52ad261](https://linux-hardware.org/?probe=b7f52ad261) | Jun 18, 2020 |
| TPV-INVENT... | 2AC6 A01                    | [90725b3c8a](https://linux-hardware.org/?probe=90725b3c8a) | Jun 18, 2020 |
| Elo TouchS... | ESY1XDX                     | [64aded4262](https://linux-hardware.org/?probe=64aded4262) | Jun 09, 2020 |
| HP            | 0AA8h                       | [2f692488e5](https://linux-hardware.org/?probe=2f692488e5) | Jun 05, 2020 |
| HP            | 0AA8h                       | [1ee6fa5fb7](https://linux-hardware.org/?probe=1ee6fa5fb7) | Jun 03, 2020 |
| HP            | 0AA8h                       | [3226f7a8da](https://linux-hardware.org/?probe=3226f7a8da) | Jun 03, 2020 |
| Elo TouchS... | ESY1XDX                     | [467adf2413](https://linux-hardware.org/?probe=467adf2413) | Jun 01, 2020 |
| Gigabyte      | 970A-UD3P                   | [6661e20292](https://linux-hardware.org/?probe=6661e20292) | May 28, 2020 |
| Gigabyte      | GA-MA790FX-DS5              | [bc3ed232f3](https://linux-hardware.org/?probe=bc3ed232f3) | May 28, 2020 |
| Olidata       | Unknown                     | [4d13b52bae](https://linux-hardware.org/?probe=4d13b52bae) | May 23, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f170547556](https://linux-hardware.org/?probe=f170547556) | May 16, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [6f3a5a041d](https://linux-hardware.org/?probe=6f3a5a041d) | May 08, 2020 |
| Intel         | D54250WYK H13922-304        | [cc19077417](https://linux-hardware.org/?probe=cc19077417) | May 01, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [d6abc4c56c](https://linux-hardware.org/?probe=d6abc4c56c) | Apr 29, 2020 |
| ECS           | A740GM-M                    | [8af834c918](https://linux-hardware.org/?probe=8af834c918) | Apr 28, 2020 |
| Intel         | DN2820FYK H24582-204        | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| ECS           | A780GM-A                    | [3530b26663](https://linux-hardware.org/?probe=3530b26663) | Mar 30, 2020 |
| ASRock        | A320M-HDV R4.0              | [ab20239127](https://linux-hardware.org/?probe=ab20239127) | Feb 09, 2020 |
| ECS           | A960M-MV                    | [b5991a8181](https://linux-hardware.org/?probe=b5991a8181) | Jan 13, 2020 |
| Gigabyte      | G41MT-S2                    | [1b60792885](https://linux-hardware.org/?probe=1b60792885) | Nov 12, 2019 |
| ASUSTek       | M5A99X EVO                  | [a0de23ca8b](https://linux-hardware.org/?probe=a0de23ca8b) | Oct 21, 2019 |
| Intel         | DG31PR AAD97573-204         | [3ca8dab2bd](https://linux-hardware.org/?probe=3ca8dab2bd) | Oct 14, 2019 |
| ASUSTek       | H81M-A                      | [dbb29527ff](https://linux-hardware.org/?probe=dbb29527ff) | Oct 08, 2019 |
| ASUSTek       | H81M-A                      | [3337b6ddbf](https://linux-hardware.org/?probe=3337b6ddbf) | Oct 08, 2019 |
| ASUSTek       | F1A75-M LE                  | [711b77b300](https://linux-hardware.org/?probe=711b77b300) | Sep 28, 2019 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [e8a0b17de8](https://linux-hardware.org/?probe=e8a0b17de8) | Sep 13, 2019 |
| ASUSTek       | B75M-A                      | [58ec049231](https://linux-hardware.org/?probe=58ec049231) | Sep 04, 2019 |
| ASUSTek       | P5QC                        | [441e7f2005](https://linux-hardware.org/?probe=441e7f2005) | Aug 19, 2019 |
| ASUSTek       | P5QC                        | [68e31b6013](https://linux-hardware.org/?probe=68e31b6013) | Aug 19, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [017c004a48](https://linux-hardware.org/?probe=017c004a48) | Aug 12, 2019 |
| ASUSTek       | F1A55-M LX                  | [db521911e3](https://linux-hardware.org/?probe=db521911e3) | Aug 06, 2019 |
| ECS           | A960M-MV                    | [4a3c832524](https://linux-hardware.org/?probe=4a3c832524) | Aug 05, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [7875ecd5a5](https://linux-hardware.org/?probe=7875ecd5a5) | Jul 17, 2019 |
| MSI           | X399 SLI PLUS               | [db1a79ac69](https://linux-hardware.org/?probe=db1a79ac69) | Jun 29, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [dc8d42d5d1](https://linux-hardware.org/?probe=dc8d42d5d1) | Jun 15, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [b189962fa8](https://linux-hardware.org/?probe=b189962fa8) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [3166cd0be4](https://linux-hardware.org/?probe=3166cd0be4) | Jun 14, 2019 |
| Gigabyte      | Z87X-UD4H-CF                | [b08781392f](https://linux-hardware.org/?probe=b08781392f) | Jun 13, 2019 |
| TPV-INVENT... | 2AC6 A01                    | [461345008c](https://linux-hardware.org/?probe=461345008c) | Jun 10, 2019 |
| TPV-INVENT... | 2AC6 A01                    | [4421365140](https://linux-hardware.org/?probe=4421365140) | Jun 10, 2019 |
| HP            | 0AA8h                       | [6d02866e6c](https://linux-hardware.org/?probe=6d02866e6c) | Jun 05, 2019 |
| Gigabyte      | Z77X-UD5H                   | [09ccaf8ccf](https://linux-hardware.org/?probe=09ccaf8ccf) | Jun 03, 2019 |
| MSI           | B250M GAMING PRO            | [a935e6e9c7](https://linux-hardware.org/?probe=a935e6e9c7) | May 27, 2019 |
| ASUSTek       | P6T DELUXE V2               | [d1f1be1b36](https://linux-hardware.org/?probe=d1f1be1b36) | May 24, 2019 |
| ASUSTek       | P6T DELUXE V2               | [77f0aad272](https://linux-hardware.org/?probe=77f0aad272) | May 24, 2019 |
| HP            | 0AA8h                       | [f2fbc75122](https://linux-hardware.org/?probe=f2fbc75122) | May 16, 2019 |
| MSI           | H61M-P31/W8                 | [915fd7548f](https://linux-hardware.org/?probe=915fd7548f) | May 13, 2019 |
| HP            | 0AA8h                       | [f0d1f05c8e](https://linux-hardware.org/?probe=f0d1f05c8e) | May 10, 2019 |
| ECS           | A780LM-M                    | [ca438dd2a7](https://linux-hardware.org/?probe=ca438dd2a7) | May 08, 2019 |
| Gigabyte      | A320M-S2H                   | [b4d5cdee78](https://linux-hardware.org/?probe=b4d5cdee78) | May 07, 2019 |
| Gigabyte      | EP45-DS3R                   | [8c9b60b665](https://linux-hardware.org/?probe=8c9b60b665) | May 01, 2019 |
| Dell          | 0GXM1W A02                  | [3841c32f4a](https://linux-hardware.org/?probe=3841c32f4a) | May 01, 2019 |
| Dell          | 0GXM1W A02                  | [e9c14efd74](https://linux-hardware.org/?probe=e9c14efd74) | Apr 30, 2019 |
| Pegatron      | 2AA1h                       | [df47c88db6](https://linux-hardware.org/?probe=df47c88db6) | Apr 23, 2019 |
| Pegatron      | 2AA1h                       | [70922676a8](https://linux-hardware.org/?probe=70922676a8) | Apr 23, 2019 |
| Pegatron      | 2AA1h                       | [07c7ac4546](https://linux-hardware.org/?probe=07c7ac4546) | Apr 23, 2019 |
| MSI           | A58M-E33                    | [987015c03b](https://linux-hardware.org/?probe=987015c03b) | Apr 18, 2019 |
| HP            | 0B4Ch D                     | [8dc7a1b1e8](https://linux-hardware.org/?probe=8dc7a1b1e8) | Feb 14, 2019 |
| Quanta        | 2AC7 011                    | [7a9d5af1ce](https://linux-hardware.org/?probe=7a9d5af1ce) | Jan 27, 2019 |
| Quanta        | 2AC7 011                    | [a2533c8043](https://linux-hardware.org/?probe=a2533c8043) | Jan 27, 2019 |
| ASUSTek       | F2A85-M LE                  | [efbf81762c](https://linux-hardware.org/?probe=efbf81762c) | Jan 09, 2019 |
| ASUSTek       | B85-PRO GAMER               | [09848aacf0](https://linux-hardware.org/?probe=09848aacf0) | Dec 26, 2018 |
| ASUSTek       | B85-PRO GAMER               | [7f0c38474e](https://linux-hardware.org/?probe=7f0c38474e) | Oct 29, 2018 |
| ASUSTek       | P5KC                        | [8ee7c3b1f4](https://linux-hardware.org/?probe=8ee7c3b1f4) | Sep 23, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 24       | 9.49%   |
| Ubuntu 18.04       | 19       | 7.51%   |
| Arch               | 10       | 3.95%   |
| Arch Rolling       | 9        | 3.56%   |
| Ubuntu 22.04       | 8        | 3.16%   |
| Pop!_OS 22.04      | 8        | 3.16%   |
| OpenMandriva 4.2   | 8        | 3.16%   |
| Zorin 16           | 7        | 2.77%   |
| Ubuntu 19.04       | 7        | 2.77%   |
| OpenMandriva 4.3   | 7        | 2.77%   |
| Manjaro            | 6        | 2.37%   |
| Linux Mint 20.1    | 6        | 2.37%   |
| Zorin 15           | 5        | 1.98%   |
| Pop!_OS 20.10      | 5        | 1.98%   |
| OpenMandriva 23.01 | 5        | 1.98%   |
| Linux Mint 21.1    | 5        | 1.98%   |
| KDE neon 20.04     | 5        | 1.98%   |
| Debian Testing     | 5        | 1.98%   |
| Ubuntu 21.04       | 4        | 1.58%   |
| OpenMandriva 23.03 | 4        | 1.58%   |
| Fedora 34          | 4        | 1.58%   |
| Ubuntu 21.10       | 3        | 1.19%   |
| Ubuntu 19.10       | 3        | 1.19%   |
| Linux Mint 20      | 3        | 1.19%   |
| Linux Mint 19.3    | 3        | 1.19%   |
| Kubuntu 20.04      | 3        | 1.19%   |
| Fedora 38          | 3        | 1.19%   |
| Fedora 37          | 3        | 1.19%   |
| Fedora 35          | 3        | 1.19%   |
| Fedora 33          | 3        | 1.19%   |
| Fedora 32          | 3        | 1.19%   |
| Debian 11          | 3        | 1.19%   |
| Ubuntu 22.10       | 2        | 0.79%   |
| Ubuntu 20.10       | 2        | 0.79%   |
| Ubuntu 18.10       | 2        | 0.79%   |
| Ubuntu 16.04       | 2        | 0.79%   |
| Pop!_OS 21.10      | 2        | 0.79%   |
| Pop!_OS 20.04      | 2        | 0.79%   |
| Nobara 36          | 2        | 0.79%   |
| Manjaro 21.0       | 2        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 75       | 31.38%  |
| OpenMandriva     | 24       | 10.04%  |
| Linux Mint       | 22       | 9.21%   |
| Fedora           | 19       | 7.95%   |
| Pop!_OS          | 16       | 6.69%   |
| Arch             | 16       | 6.69%   |
| Zorin            | 13       | 5.44%   |
| Manjaro          | 9        | 3.77%   |
| Debian           | 9        | 3.77%   |
| KDE neon         | 7        | 2.93%   |
| Kubuntu          | 6        | 2.51%   |
| Nobara           | 3        | 1.26%   |
| Ubuntu MATE      | 2        | 0.84%   |
| EndeavourOS      | 2        | 0.84%   |
| Elementary       | 2        | 0.84%   |
| ArcoLinux        | 2        | 0.84%   |
| Ubuntu Budgie    | 1        | 0.42%   |
| ROSA             | 1        | 0.42%   |
| org.kde.Platform | 1        | 0.42%   |
| Lubuntu          | 1        | 0.42%   |
| LMDE             | 1        | 0.42%   |
| LinuxFX          | 1        | 0.42%   |
| Linux Lite       | 1        | 0.42%   |
| Kali             | 1        | 0.42%   |
| Gentoo           | 1        | 0.42%   |
| Garuda Linux     | 1        | 0.42%   |
| Endless          | 1        | 0.42%   |
| Clear Linux      | 1        | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 7        | 2.51%   |
| 5.10.14-desktop-1omv4002 | 7        | 2.51%   |
| 5.4.0-42-generic         | 6        | 2.15%   |
| 5.15.0-58-generic        | 6        | 2.15%   |
| 6.1.1-desktop-1omv2290   | 5        | 1.79%   |
| 6.2.6-desktop-1omv2390   | 4        | 1.43%   |
| 5.9.16-1-MANJARO         | 4        | 1.43%   |
| 5.0.0-13-generic         | 4        | 1.43%   |
| 5.4.0-77-generic         | 3        | 1.08%   |
| 5.4.0-33-generic         | 3        | 1.08%   |
| 5.4.0-26-generic         | 3        | 1.08%   |
| 5.11.0-7614-generic      | 3        | 1.08%   |
| 4.18.0-18-generic        | 3        | 1.08%   |
| 6.2.6-76060206-generic   | 2        | 0.72%   |
| 5.8.0-59-generic         | 2        | 0.72%   |
| 5.8.0-48-generic         | 2        | 0.72%   |
| 5.4.0-89-generic         | 2        | 0.72%   |
| 5.4.0-74-generic         | 2        | 0.72%   |
| 5.4.0-70-generic         | 2        | 0.72%   |
| 5.4.0-65-generic         | 2        | 0.72%   |
| 5.4.0-52-generic         | 2        | 0.72%   |
| 5.4.0-47-generic         | 2        | 0.72%   |
| 5.4.0-29-generic         | 2        | 0.72%   |
| 5.4.0-124-generic        | 2        | 0.72%   |
| 5.4.0-117-generic        | 2        | 0.72%   |
| 5.3.0-53-generic         | 2        | 0.72%   |
| 5.18.10-76051810-generic | 2        | 0.72%   |
| 5.17.5-76051705-generic  | 2        | 0.72%   |
| 5.15.0-52-generic        | 2        | 0.72%   |
| 5.13.0-39-generic        | 2        | 0.72%   |
| 5.11.0-41-generic        | 2        | 0.72%   |
| 5.11.0-34-generic        | 2        | 0.72%   |
| 5.11.0-27-generic        | 2        | 0.72%   |
| 5.11.0-18-generic        | 2        | 0.72%   |
| 4.18.0-20-generic        | 2        | 0.72%   |
| 4.18.0-17-generic        | 2        | 0.72%   |
| 4.18.0-15-generic        | 2        | 0.72%   |
| 4.15.0-43-generic        | 2        | 0.72%   |
| 4.15.0-112-generic       | 2        | 0.72%   |
| 6.3.8-arch1-1            | 1        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 40       | 15.15%  |
| 5.15.0  | 21       | 7.95%   |
| 5.11.0  | 15       | 5.68%   |
| 4.15.0  | 14       | 5.3%    |
| 5.8.0   | 11       | 4.17%   |
| 5.0.0   | 10       | 3.79%   |
| 4.18.0  | 10       | 3.79%   |
| 5.3.0   | 9        | 3.41%   |
| 5.13.0  | 9        | 3.41%   |
| 6.2.6   | 7        | 2.65%   |
| 5.16.7  | 7        | 2.65%   |
| 5.10.14 | 7        | 2.65%   |
| 6.1.1   | 6        | 2.27%   |
| 5.19.0  | 6        | 2.27%   |
| 5.9.16  | 5        | 1.89%   |
| 6.1.11  | 3        | 1.14%   |
| 5.18.10 | 3        | 1.14%   |
| 5.17.5  | 3        | 1.14%   |
| 5.10.0  | 3        | 1.14%   |
| 6.3.8   | 2        | 0.76%   |
| 6.2.9   | 2        | 0.76%   |
| 5.8.12  | 2        | 0.76%   |
| 5.16.16 | 2        | 0.76%   |
| 5.14.0  | 2        | 0.76%   |
| 5.13.13 | 2        | 0.76%   |
| 5.13.12 | 2        | 0.76%   |
| 6.3.7   | 1        | 0.38%   |
| 6.3.4   | 1        | 0.38%   |
| 6.2.8   | 1        | 0.38%   |
| 6.2.14  | 1        | 0.38%   |
| 6.2.13  | 1        | 0.38%   |
| 6.2.12  | 1        | 0.38%   |
| 6.2.11  | 1        | 0.38%   |
| 6.2.0   | 1        | 0.38%   |
| 6.1.7   | 1        | 0.38%   |
| 6.1.18  | 1        | 0.38%   |
| 6.1.0   | 1        | 0.38%   |
| 6.0.6   | 1        | 0.38%   |
| 6.0.0   | 1        | 0.38%   |
| 5.9.8   | 1        | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 41       | 15.83%  |
| 5.15    | 25       | 9.65%   |
| 5.11    | 18       | 6.95%   |
| 5.13    | 17       | 6.56%   |
| 5.10    | 15       | 5.79%   |
| 4.15    | 14       | 5.41%   |
| 6.2     | 13       | 5.02%   |
| 5.8     | 13       | 5.02%   |
| 6.1     | 12       | 4.63%   |
| 5.19    | 11       | 4.25%   |
| 5.3     | 10       | 3.86%   |
| 5.16    | 10       | 3.86%   |
| 5.0     | 10       | 3.86%   |
| 4.18    | 10       | 3.86%   |
| 5.9     | 7        | 2.7%    |
| 5.17    | 6        | 2.32%   |
| 5.14    | 6        | 2.32%   |
| 5.18    | 5        | 1.93%   |
| 6.3     | 4        | 1.54%   |
| 5.12    | 3        | 1.16%   |
| 6.0     | 2        | 0.77%   |
| 5.7     | 2        | 0.77%   |
| 5.6     | 2        | 0.77%   |
| 4.19    | 2        | 0.77%   |
| 4.9     | 1        | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 229      | 98.71%  |
| i686   | 3        | 1.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 94       | 39.5%   |
| KDE5       | 52       | 21.85%  |
| Unknown    | 33       | 13.87%  |
| X-Cinnamon | 18       | 7.56%   |
| XFCE       | 15       | 6.3%    |
| KDE        | 10       | 4.2%    |
| MATE       | 3        | 1.26%   |
| xmonad     | 2        | 0.84%   |
| Pantheon   | 2        | 0.84%   |
| LXDE       | 2        | 0.84%   |
| Cinnamon   | 2        | 0.84%   |
| Budgie     | 2        | 0.84%   |
| KDE4       | 1        | 0.42%   |
| i3         | 1        | 0.42%   |
| Deepin     | 1        | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 176      | 74.89%  |
| Wayland | 30       | 12.77%  |
| Unknown | 26       | 11.06%  |
| Tty     | 3        | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 141      | 58.51%  |
| SDDM    | 41       | 17.01%  |
| GDM     | 24       | 9.96%   |
| LightDM | 14       | 5.81%   |
| GDM3    | 12       | 4.98%   |
| TDM     | 6        | 2.49%   |
| LY-DM   | 1        | 0.41%   |
| LXDM    | 1        | 0.41%   |
| KDM     | 1        | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CL   | 120      | 50.42%  |
| en_US   | 58       | 24.37%  |
| Unknown | 34       | 14.29%  |
| es_ES   | 12       | 5.04%   |
| es_MX   | 5        | 2.1%    |
| en_GB   | 5        | 2.1%    |
| C       | 2        | 0.84%   |
| pt_BR   | 1        | 0.42%   |
| es_UY   | 1        | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 143      | 59.83%  |
| EFI  | 96       | 40.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 178      | 74.48%  |
| Btrfs   | 25       | 10.46%  |
| Overlay | 21       | 8.79%   |
| Unknown | 7        | 2.93%   |
| Ext2    | 3        | 1.26%   |
| Zfs     | 2        | 0.84%   |
| Xfs     | 1        | 0.42%   |
| Tmpfs   | 1        | 0.42%   |
| Jfs     | 1        | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 146      | 60.08%  |
| GPT     | 72       | 29.63%  |
| MBR     | 25       | 10.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 199      | 83.97%  |
| Yes       | 38       | 16.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 149      | 61.83%  |
| Yes       | 92       | 38.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 63       | 27.16%  |
| MSI                 | 42       | 18.1%   |
| Gigabyte Technology | 23       | 9.91%   |
| Hewlett-Packard     | 18       | 7.76%   |
| Intel               | 17       | 7.33%   |
| ECS                 | 11       | 4.74%   |
| Dell                | 8        | 3.45%   |
| ASRock              | 8        | 3.45%   |
| Lenovo              | 5        | 2.16%   |
| Huanan              | 5        | 2.16%   |
| Unknown             | 5        | 2.16%   |
| Pegatron            | 4        | 1.72%   |
| TPV-INVENTA         | 2        | 0.86%   |
| MACHINIST           | 2        | 0.86%   |
| HC                  | 2        | 0.86%   |
| WZA300S2R120        | 1        | 0.43%   |
| ViewSonic           | 1        | 0.43%   |
| SZMZ                | 1        | 0.43%   |
| R-StyleComputers    | 1        | 0.43%   |
| Quanta              | 1        | 0.43%   |
| PCPartner           | 1        | 0.43%   |
| Olidata             | 1        | 0.43%   |
| Nvidia              | 1        | 0.43%   |
| JGINYUE             | 1        | 0.43%   |
| IBM                 | 1        | 0.43%   |
| Foxconn             | 1        | 0.43%   |
| eMachines           | 1        | 0.43%   |
| Elo TouchSystems    | 1        | 0.43%   |
| Colorful Technology | 1        | 0.43%   |
| BESSTAR Tech        | 1        | 0.43%   |
| Apple               | 1        | 0.43%   |
| AMI                 | 1        | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| ASUS All Series                           | 6        | 2.59%   |
| Unknown                                   | 6        | 2.59%   |
| MSI MS-7817                               | 5        | 2.16%   |
| ASUS PRIME B450M-A                        | 4        | 1.72%   |
| ASUS PRIME A320M-K                        | 4        | 1.72%   |
| MSI MS-7A34                               | 3        | 1.29%   |
| MSI MS-7788                               | 3        | 1.29%   |
| ASUS TUF Gaming B450M-PLUS II             | 3        | 1.29%   |
| MSI Pro 3000/3080                         | 2        | 0.86%   |
| MSI MS-7A65                               | 2        | 0.86%   |
| MSI MS-7A15                               | 2        | 0.86%   |
| MSI MS-7693                               | 2        | 0.86%   |
| MSI MS-7360                               | 2        | 0.86%   |
| Intel X79M-S                              | 2        | 0.86%   |
| HP Compaq Pro 6300 SFF                    | 2        | 0.86%   |
| HP Compaq Pro 4300 SFF PC                 | 2        | 0.86%   |
| HC HCAR357-MI                             | 2        | 0.86%   |
| Gigabyte B450M DS3H V2                    | 2        | 0.86%   |
| Gigabyte B450 AORUS PRO WIFI              | 2        | 0.86%   |
| ECS MCP61M-M3                             | 2        | 0.86%   |
| ECS A960M-MV                              | 2        | 0.86%   |
| ECS A740GM-M                              | 2        | 0.86%   |
| ASUS TUF Gaming X570-PLUS                 | 2        | 0.86%   |
| ASUS SABERTOOTH 990FX R2.0                | 2        | 0.86%   |
| ASUS PRIME H410M-E                        | 2        | 0.86%   |
| ASUS M5A99X EVO                           | 2        | 0.86%   |
| ASUS F2A55-M LK2                          | 2        | 0.86%   |
| WZA300S2R120 SA300-D4                     | 1        | 0.43%   |
| ViewSonic VOT132                          | 1        | 0.43%   |
| TPV-INVENTA Pro 1005 Series All-in-One PC | 1        | 0.43%   |
| TPV-INVENTA CQ1-3130LA                    | 1        | 0.43%   |
| SZMZ X99M-G2                              | 1        | 0.43%   |
| R-StyleComputers ALICON AI2S-A21 00.69    | 1        | 0.43%   |
| Quanta 120-1016la                         | 1        | 0.43%   |
| Pegatron SAISHIAT2                        | 1        | 0.43%   |
| Pegatron 9100                             | 1        | 0.43%   |
| Pegatron 520-1135la                       | 1        | 0.43%   |
| Pegatron 23-d015la                        | 1        | 0.43%   |
| PCPartner G43-F71862                      | 1        | 0.43%   |
| Nvidia NF-MCP61                           | 1        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 16       | 6.9%    |
| ASUS TUF                | 10       | 4.31%   |
| HP Compaq               | 7        | 3.02%   |
| ASUS All                | 6        | 2.59%   |
| Unknown                 | 6        | 2.59%   |
| MSI MS-7817             | 5        | 2.16%   |
| Lenovo ThinkCentre      | 5        | 2.16%   |
| Dell OptiPlex           | 4        | 1.72%   |
| ASUS M5A78L-M           | 4        | 1.72%   |
| MSI MS-7A34             | 3        | 1.29%   |
| MSI MS-7788             | 3        | 1.29%   |
| Huanan X79              | 3        | 1.29%   |
| HP ProDesk              | 3        | 1.29%   |
| HP EliteDesk            | 3        | 1.29%   |
| Gigabyte B450M          | 3        | 1.29%   |
| ASUS SABERTOOTH         | 3        | 1.29%   |
| ASUS ROG                | 3        | 1.29%   |
| MSI Pro                 | 2        | 0.86%   |
| MSI MS-7A65             | 2        | 0.86%   |
| MSI MS-7A15             | 2        | 0.86%   |
| MSI MS-7693             | 2        | 0.86%   |
| MSI MS-7360             | 2        | 0.86%   |
| Intel X79M-S            | 2        | 0.86%   |
| Intel D54250WYK         | 2        | 0.86%   |
| HC HCAR357-MI           | 2        | 0.86%   |
| Gigabyte B450           | 2        | 0.86%   |
| ECS MCP61M-M3           | 2        | 0.86%   |
| ECS A960M-MV            | 2        | 0.86%   |
| ECS A740GM-M            | 2        | 0.86%   |
| Dell Precision          | 2        | 0.86%   |
| ASUS M5A99X             | 2        | 0.86%   |
| ASUS F2A55-M            | 2        | 0.86%   |
| WZA300S2R120 SA300-D4   | 1        | 0.43%   |
| ViewSonic VOT132        | 1        | 0.43%   |
| TPV-INVENTA Pro         | 1        | 0.43%   |
| TPV-INVENTA CQ1-3130LA  | 1        | 0.43%   |
| SZMZ X99M-G2            | 1        | 0.43%   |
| R-StyleComputers ALICON | 1        | 0.43%   |
| Quanta 120-1016la       | 1        | 0.43%   |
| Pegatron SAISHIAT2      | 1        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 30       | 12.93%  |
| 2012 | 26       | 11.21%  |
| 2018 | 23       | 9.91%   |
| 2013 | 20       | 8.62%   |
| 2014 | 16       | 6.9%    |
| 2019 | 15       | 6.47%   |
| 2011 | 15       | 6.47%   |
| 2017 | 14       | 6.03%   |
| 2007 | 14       | 6.03%   |
| 2010 | 11       | 4.74%   |
| 2008 | 10       | 4.31%   |
| 2021 | 9        | 3.88%   |
| 2016 | 9        | 3.88%   |
| 2009 | 7        | 3.02%   |
| 2022 | 6        | 2.59%   |
| 2015 | 5        | 2.16%   |
| 2006 | 1        | 0.43%   |
| 2005 | 1        | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 232      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 229      | 98.28%  |
| Enabled  | 4        | 1.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 232      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 56       | 23.83%  |
| 16.01-24.0  | 49       | 20.85%  |
| 4.01-8.0    | 37       | 15.74%  |
| 3.01-4.0    | 37       | 15.74%  |
| 32.01-64.0  | 35       | 14.89%  |
| 1.01-2.0    | 11       | 4.68%   |
| 24.01-32.0  | 5        | 2.13%   |
| 2.01-3.0    | 3        | 1.28%   |
| 64.01-256.0 | 2        | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 89       | 34.77%  |
| 2.01-3.0   | 71       | 27.73%  |
| 3.01-4.0   | 38       | 14.84%  |
| 4.01-8.0   | 36       | 14.06%  |
| 8.01-16.0  | 13       | 5.08%   |
| 0.51-1.0   | 6        | 2.34%   |
| 0.01-0.5   | 2        | 0.78%   |
| 16.01-24.0 | 1        | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 39.17%  |
| 2      | 74       | 30.83%  |
| 3      | 36       | 15%     |
| 4      | 24       | 10%     |
| 5      | 7        | 2.92%   |
| 7      | 2        | 0.83%   |
| 0      | 2        | 0.83%   |
| 6      | 1        | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 140      | 59.83%  |
| Yes       | 94       | 40.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 230      | 99.14%  |
| No        | 2        | 0.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 52.56%  |
| Yes       | 111      | 47.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 163      | 69.07%  |
| Yes       | 73       | 30.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Chile   | 232      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Santiago            | 74       | 30.2%   |
| Maipu               | 9        | 3.67%   |
| Las Condes          | 9        | 3.67%   |
| Viña del Mar       | 8        | 3.27%   |
| Puente Alto         | 8        | 3.27%   |
| Concepción         | 8        | 3.27%   |
| Antofagasta         | 8        | 3.27%   |
| Nunoa               | 7        | 2.86%   |
| La Florida          | 6        | 2.45%   |
| Valparaíso         | 5        | 2.04%   |
| Valdivia            | 5        | 2.04%   |
| Temuco              | 5        | 2.04%   |
| Providencia         | 5        | 2.04%   |
| Central             | 5        | 2.04%   |
| San Miguel          | 4        | 1.63%   |
| Port Montt          | 4        | 1.63%   |
| Osorno              | 4        | 1.63%   |
| Quilpué            | 3        | 1.22%   |
| Penalolen           | 3        | 1.22%   |
| La Serena           | 3        | 1.22%   |
| El Bosque           | 3        | 1.22%   |
| Coquimbo            | 3        | 1.22%   |
| Chillan             | 3        | 1.22%   |
| Arica               | 3        | 1.22%   |
| Vitacura            | 2        | 0.82%   |
| Vallenar            | 2        | 0.82%   |
| Tome                | 2        | 0.82%   |
| Talca               | 2        | 0.82%   |
| San Pedro de la Paz | 2        | 0.82%   |
| Recoleta            | 2        | 0.82%   |
| Melipilla           | 2        | 0.82%   |
| Los Ángeles        | 2        | 0.82%   |
| La Granja           | 2        | 0.82%   |
| Coronel             | 2        | 0.82%   |
| Colina              | 2        | 0.82%   |
| Villa Alemana       | 1        | 0.41%   |
| Villa Alegre        | 1        | 0.41%   |
| Tierra Amarilla     | 1        | 0.41%   |
| Talagante           | 1        | 0.41%   |
| San Joaquin         | 1        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 92       | 157    | 21.8%   |
| Seagate                     | 79       | 114    | 18.72%  |
| Kingston                    | 49       | 76     | 11.61%  |
| Toshiba                     | 44       | 52     | 10.43%  |
| Crucial                     | 26       | 34     | 6.16%   |
| Samsung Electronics         | 20       | 32     | 4.74%   |
| Sandisk                     | 14       | 17     | 3.32%   |
| Hitachi                     | 14       | 18     | 3.32%   |
| Silicon Motion              | 12       | 12     | 2.84%   |
| China                       | 8        | 11     | 1.9%    |
| Unknown                     | 5        | 6      | 1.18%   |
| XPG                         | 4        | 10     | 0.95%   |
| Maxtor                      | 4        | 4      | 0.95%   |
| Corsair                     | 4        | 9      | 0.95%   |
| XrayDisk                    | 3        | 3      | 0.71%   |
| Realtek Semiconductor       | 3        | 3      | 0.71%   |
| Micron/Crucial Technology   | 3        | 6      | 0.71%   |
| Micron Technology           | 3        | 6      | 0.71%   |
| Lexar                       | 3        | 3      | 0.71%   |
| KingSpec                    | 3        | 3      | 0.71%   |
| A-DATA Technology           | 3        | 3      | 0.71%   |
| Kingston Technology Company | 2        | 2      | 0.47%   |
| JMicron Technology          | 2        | 2      | 0.47%   |
| Gigabyte Technology         | 2        | 3      | 0.47%   |
| ZOTAC                       | 1        | 1      | 0.24%   |
| WALRAM                      | 1        | 2      | 0.24%   |
| Transcend                   | 1        | 1      | 0.24%   |
| StoreJet                    | 1        | 1      | 0.24%   |
| SK hynix                    | 1        | 1      | 0.24%   |
| SCY                         | 1        | 1      | 0.24%   |
| PNY                         | 1        | 1      | 0.24%   |
| Patriot                     | 1        | 1      | 0.24%   |
| OCZ                         | 1        | 2      | 0.24%   |
| NGFF                        | 1        | 1      | 0.24%   |
| Netac                       | 1        | 1      | 0.24%   |
| Mass                        | 1        | 1      | 0.24%   |
| JASTER                      | 1        | 2      | 0.24%   |
| Intenso                     | 1        | 1      | 0.24%   |
| FORESEE                     | 1        | 1      | 0.24%   |
| BIWIN                       | 1        | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 16       | 3.33%   |
| Seagate ST500DM002-1BD142 500GB                       | 14       | 2.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 11       | 2.29%   |
| Toshiba HDWD110 1TB                                   | 10       | 2.08%   |
| Kingston SA400S37240G 240GB SSD                       | 10       | 2.08%   |
| Kingston SA400S37120G 120GB SSD                       | 10       | 2.08%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 7        | 1.46%   |
| Kingston SA400S37480G 480GB SSD                       | 7        | 1.46%   |
| WDC WD5000AAKX-001CA0 500GB                           | 6        | 1.25%   |
| Toshiba DT01ACA050 500GB                              | 6        | 1.25%   |
| WDC WD5000AAKX-00ERMA0 500GB                          | 5        | 1.04%   |
| Seagate ST3500418AS 500GB                             | 5        | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB                        | 5        | 1.04%   |
| Crucial CT500MX500SSD1 500GB                          | 5        | 1.04%   |
| Crucial CT480BX500SSD1 480GB                          | 5        | 1.04%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 4        | 0.83%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 4        | 0.83%   |
| Seagate ST3320418AS 320GB                             | 4        | 0.83%   |
| SanDisk NVMe SSD Drive 1TB                            | 4        | 0.83%   |
| Hitachi HDS721050CLA362 500GB                         | 4        | 0.83%   |
| XPG SPECTRIX S40G 4TB                                 | 3        | 0.63%   |
| XPG GAMMIX S11 Pro 512GB                              | 3        | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 3        | 0.63%   |
| Seagate ST9640320AS 640GB                             | 3        | 0.63%   |
| Seagate ST500LT012-9WS142 500GB                       | 3        | 0.63%   |
| Seagate ST500LT012-1DG142 500GB                       | 3        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3        | 0.63%   |
| SanDisk NVMe SSD Drive 500GB                          | 3        | 0.63%   |
| Kingston SUV400S37240G 240GB SSD                      | 3        | 0.63%   |
| Hitachi HDS721032CLA362 320GB                         | 3        | 0.63%   |
| Crucial CT240BX500SSD1 240GB                          | 3        | 0.63%   |
| WDC WDS500G3X0C-00SJG0 500GB                          | 2        | 0.42%   |
| WDC WDS240G1G0A-00SS50 240GB SSD                      | 2        | 0.42%   |
| WDC WDS120G2G0A-00JH30 128GB SSD                      | 2        | 0.42%   |
| WDC WDS100T2B0C-00PXH0 1TB                            | 2        | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 2        | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 2        | 0.42%   |
| WDC WD20EARX-00PASB0 2TB                              | 2        | 0.42%   |
| WDC WD2003FZEX-00Z4SA0 2TB                            | 2        | 0.42%   |
| WDC WD1600BB-00GUC0 160GB                             | 2        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 78       | 113    | 35.45%  |
| WDC                 | 71       | 110    | 32.27%  |
| Toshiba             | 44       | 52     | 20%     |
| Hitachi             | 14       | 18     | 6.36%   |
| Samsung Electronics | 5        | 7      | 2.27%   |
| Maxtor              | 4        | 4      | 1.82%   |
| Unknown             | 1        | 1      | 0.45%   |
| ASMT                | 1        | 1      | 0.45%   |
| ASMedia             | 1        | 2      | 0.45%   |
| Apple               | 1        | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 44       | 60     | 30.56%  |
| WDC                 | 27       | 38     | 18.75%  |
| Crucial             | 26       | 33     | 18.06%  |
| Samsung Electronics | 11       | 15     | 7.64%   |
| China               | 8        | 11     | 5.56%   |
| Corsair             | 4        | 9      | 2.78%   |
| Lexar               | 3        | 3      | 2.08%   |
| KingSpec            | 3        | 3      | 2.08%   |
| XrayDisk            | 2        | 2      | 1.39%   |
| Micron Technology   | 2        | 2      | 1.39%   |
| Gigabyte Technology | 2        | 3      | 1.39%   |
| ZOTAC               | 1        | 1      | 0.69%   |
| WALRAM              | 1        | 1      | 0.69%   |
| StoreJet            | 1        | 1      | 0.69%   |
| PNY                 | 1        | 1      | 0.69%   |
| Patriot             | 1        | 1      | 0.69%   |
| OCZ                 | 1        | 2      | 0.69%   |
| NGFF                | 1        | 1      | 0.69%   |
| Intenso             | 1        | 1      | 0.69%   |
| FORESEE             | 1        | 1      | 0.69%   |
| BIWIN               | 1        | 1      | 0.69%   |
| A-DATA Technology   | 1        | 1      | 0.69%   |
| Unknown             | 1        | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 162      | 309    | 45.89%  |
| SSD     | 121      | 192    | 34.28%  |
| NVMe    | 59       | 97     | 16.71%  |
| Unknown | 9        | 10     | 2.55%   |
| MMC     | 2        | 2      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 216      | 494    | 75%     |
| NVMe | 58       | 96     | 20.14%  |
| SAS  | 12       | 18     | 4.17%   |
| MMC  | 2        | 2      | 0.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 174      | 317    | 60.21%  |
| 0.51-1.0   | 76       | 121    | 26.3%   |
| 1.01-2.0   | 26       | 38     | 9%      |
| 2.01-3.0   | 6        | 14     | 2.08%   |
| 3.01-4.0   | 4        | 5      | 1.38%   |
| 4.01-10.0  | 3        | 6      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 57       | 22.89%  |
| 101-250        | 49       | 19.68%  |
| 501-1000       | 36       | 14.46%  |
| 1001-2000      | 26       | 10.44%  |
| 1-20           | 21       | 8.43%   |
| More than 3000 | 20       | 8.03%   |
| 2001-3000      | 13       | 5.22%   |
| 51-100         | 13       | 5.22%   |
| Unknown        | 8        | 3.21%   |
| 21-50          | 6        | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 91       | 35.27%  |
| 21-50          | 51       | 19.77%  |
| 101-250        | 25       | 9.69%   |
| 501-1000       | 20       | 7.75%   |
| 51-100         | 20       | 7.75%   |
| 1001-2000      | 19       | 7.36%   |
| 251-500        | 13       | 5.04%   |
| More than 3000 | 8        | 3.1%    |
| Unknown        | 8        | 3.1%    |
| 2001-3000      | 3        | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD1600BB-00GUC0 160GB            | 2        | 2      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB      | 2        | 2      | 6.25%   |
| Seagate ST31000528AS 1TB             | 2        | 2      | 6.25%   |
| Kingston SKC400S371T 1TB SSD         | 2        | 6      | 6.25%   |
| Kingston SA400S37240G 240GB SSD      | 2        | 2      | 6.25%   |
| XrayDisk SSD 256GB                   | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-083CA1 500GB          | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1        | 1      | 3.13%   |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 2      | 3.13%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1      | 3.13%   |
| WDC WD10EARS-003BB1 1TB              | 1        | 1      | 3.13%   |
| Toshiba MK1652GSX 160GB              | 1        | 1      | 3.13%   |
| Toshiba DT01ACA100 1TB               | 1        | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB      | 1        | 1      | 3.13%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 1      | 3.13%   |
| Seagate ST3500418AS 500GB            | 1        | 1      | 3.13%   |
| Samsung Electronics SSD 870 EVO 1TB  | 1        | 1      | 3.13%   |
| Samsung Electronics HD250HJ 250GB    | 1        | 2      | 3.13%   |
| Samsung Electronics HD081GJ 80GB     | 1        | 1      | 3.13%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 1      | 3.13%   |
| Kingston SA400S37120G 120GB SSD      | 1        | 1      | 3.13%   |
| Hitachi HTS547550A9E384 500GB        | 1        | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB        | 1        | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB        | 1        | 1      | 3.13%   |
| Hitachi HDS721050CLA660 500GB        | 1        | 1      | 3.13%   |
| Hitachi HDS721032CLA362 320GB        | 1        | 1      | 3.13%   |
| A-DATA Technology SX8100NP 1TB       | 1        | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 23.33%  |
| Seagate             | 7        | 7      | 23.33%  |
| Kingston            | 6        | 10     | 20%     |
| Hitachi             | 4        | 5      | 13.33%  |
| Toshiba             | 2        | 2      | 6.67%   |
| Samsung Electronics | 2        | 4      | 6.67%   |
| XrayDisk            | 1        | 1      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 33.33%  |
| Seagate             | 7        | 7      | 33.33%  |
| Hitachi             | 4        | 5      | 19.05%  |
| Toshiba             | 2        | 2      | 9.52%   |
| Samsung Electronics | 1        | 3      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 25     | 65.38%  |
| SSD  | 8        | 12     | 30.77%  |
| NVMe | 1        | 1      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Toshiba MQ01ABF050 500GB | 1        | 1      | 100%    |

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
| Detected | 157      | 391    | 59.92%  |
| Works    | 79       | 180    | 30.15%  |
| Malfunc  | 25       | 38     | 9.54%   |
| Failed   | 1        | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 134      | 43.09%  |
| AMD                          | 88       | 28.3%   |
| SanDisk                      | 19       | 6.11%   |
| Silicon Motion               | 14       | 4.5%    |
| Realtek Semiconductor        | 8        | 2.57%   |
| Marvell Technology Group     | 8        | 2.57%   |
| JMicron Technology           | 8        | 2.57%   |
| Kingston Technology Company  | 6        | 1.93%   |
| Samsung Electronics          | 5        | 1.61%   |
| Nvidia                       | 5        | 1.61%   |
| ASMedia Technology           | 5        | 1.61%   |
| Micron/Crucial Technology    | 4        | 1.29%   |
| ADATA Technology             | 3        | 0.96%   |
| VIA Technologies             | 1        | 0.32%   |
| SK hynix                     | 1        | 0.32%   |
| Shenzhen Longsys Electronics | 1        | 0.32%   |
| Micron Technology            | 1        | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 49       | 12.07%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21       | 5.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19       | 4.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 3.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 13       | 3.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 13       | 3.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 2.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 1.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 1.97%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 7        | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.72%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 1.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 7        | 1.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 1.72%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6        | 1.48%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.48%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.48%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.48%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 1.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.48%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 5        | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.99%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.99%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.99%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 0.99%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.99%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 4        | 0.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 0.99%   |
| SanDisk WD Black SN770 NVMe SSD                                                         | 3        | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 0.74%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.74%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.74%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 181      | 58.58%  |
| IDE  | 63       | 20.39%  |
| NVMe | 58       | 18.77%  |
| RAID | 7        | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 139      | 59.91%  |
| AMD    | 93       | 40.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-4460 CPU @ 3.20GHz            | 5        | 2.11%   |
| AMD FX-6300 Six-Core Processor              | 5        | 2.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.69%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 1.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4        | 1.69%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 1.69%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 1.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 1.27%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 1.27%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.27%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.27%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.27%   |
| AMD E-450 APU with Radeon HD Graphics       | 3        | 1.27%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 3        | 1.27%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 2        | 0.84%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 2        | 0.84%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz         | 2        | 0.84%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 2        | 0.84%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 2        | 0.84%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 0.84%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 0.84%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 0.84%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 0.84%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 0.84%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.84%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 2        | 0.84%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 0.84%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 0.84%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2        | 0.84%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 0.84%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 0.84%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2        | 0.84%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz       | 2        | 0.84%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 2        | 0.84%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 0.84%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz      | 2        | 0.84%   |
| AMD Ryzen 9 3900XT 12-Core Processor        | 2        | 0.84%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 34       | 14.41%  |
| Intel Xeon              | 23       | 9.75%   |
| Intel Core i7           | 23       | 9.75%   |
| AMD Ryzen 5             | 22       | 9.32%   |
| Intel Core i3           | 17       | 7.2%    |
| AMD FX                  | 12       | 5.08%   |
| AMD Ryzen 7             | 11       | 4.66%   |
| Intel Core 2 Duo        | 10       | 4.24%   |
| Intel Celeron           | 8        | 3.39%   |
| AMD Ryzen 3             | 8        | 3.39%   |
| AMD A6                  | 7        | 2.97%   |
| Intel Pentium           | 6        | 2.54%   |
| AMD Athlon              | 5        | 2.12%   |
| AMD Ryzen 9             | 4        | 1.69%   |
| Other                   | 3        | 1.27%   |
| Intel Pentium Dual      | 3        | 1.27%   |
| Intel Core 2 Quad       | 3        | 1.27%   |
| AMD Phenom              | 3        | 1.27%   |
| AMD E                   | 3        | 1.27%   |
| AMD Athlon II X2        | 3        | 1.27%   |
| Intel Pentium Dual-Core | 2        | 0.85%   |
| Intel Pentium 4         | 2        | 0.85%   |
| Intel Core 2            | 2        | 0.85%   |
| Intel Atom              | 2        | 0.85%   |
| AMD Phenom II X6        | 2        | 0.85%   |
| AMD Phenom II X4        | 2        | 0.85%   |
| AMD Athlon 64 X2        | 2        | 0.85%   |
| AMD A8                  | 2        | 0.85%   |
| AMD A10                 | 2        | 0.85%   |
| Intel Xeon Bronze       | 1        | 0.42%   |
| Intel Pentium Gold      | 1        | 0.42%   |
| Intel Core i9           | 1        | 0.42%   |
| AMD Ryzen Threadripper  | 1        | 0.42%   |
| AMD Ryzen 5 PRO         | 1        | 0.42%   |
| AMD Phenom II X2        | 1        | 0.42%   |
| AMD Athlon X4           | 1        | 0.42%   |
| AMD Athlon II X4        | 1        | 0.42%   |
| AMD Athlon II           | 1        | 0.42%   |
| AMD A4                  | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 86       | 36.29%  |
| 2       | 66       | 27.85%  |
| 6       | 30       | 12.66%  |
| 8       | 23       | 9.7%    |
| 12      | 8        | 3.38%   |
| 3       | 8        | 3.38%   |
| 1       | 8        | 3.38%   |
| 10      | 4        | 1.69%   |
| 16      | 2        | 0.84%   |
| 14      | 1        | 0.42%   |
| Unknown | 1        | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 230      | 99.14%  |
| 2      | 2        | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 133      | 57.08%  |
| 1       | 99       | 42.49%  |
| Unknown | 1        | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 226      | 97.41%  |
| Unknown        | 4        | 1.72%   |
| 64-bit         | 1        | 0.43%   |
| 32-bit         | 1        | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 28.63%  |
| 0x306c3    | 16       | 6.45%   |
| 0x08701021 | 11       | 4.44%   |
| 0x306a9    | 10       | 4.03%   |
| 0x206a7    | 9        | 3.63%   |
| 0x08108109 | 9        | 3.63%   |
| 0x1067a    | 7        | 2.82%   |
| 0x06000852 | 7        | 2.82%   |
| 0xa0653    | 5        | 2.02%   |
| 0x906e9    | 5        | 2.02%   |
| 0x10676    | 5        | 2.02%   |
| 0x906ea    | 4        | 1.61%   |
| 0x6fd      | 4        | 1.61%   |
| 0x306f2    | 4        | 1.61%   |
| 0x0800820d | 4        | 1.61%   |
| 0x03000027 | 4        | 1.61%   |
| 0x010000c8 | 4        | 1.61%   |
| 0x6fb      | 3        | 1.21%   |
| 0x506e3    | 3        | 1.21%   |
| 0x306e4    | 3        | 1.21%   |
| 0x206d7    | 3        | 1.21%   |
| 0x08108102 | 3        | 1.21%   |
| 0x06001119 | 3        | 1.21%   |
| 0x0600063e | 3        | 1.21%   |
| 0x40651    | 2        | 0.81%   |
| 0x30678    | 2        | 0.81%   |
| 0x106a5    | 2        | 0.81%   |
| 0x0a20120a | 2        | 0.81%   |
| 0x08701013 | 2        | 0.81%   |
| 0x08101016 | 2        | 0.81%   |
| 0x08001138 | 2        | 0.81%   |
| 0x06003106 | 2        | 0.81%   |
| 0x05000119 | 2        | 0.81%   |
| 0x010000bf | 2        | 0.81%   |
| 0x01000095 | 2        | 0.81%   |
| 0xf65      | 1        | 0.4%    |
| 0xf41      | 1        | 0.4%    |
| 0xa0671    | 1        | 0.4%    |
| 0xa0655    | 1        | 0.4%    |
| 0x906ed    | 1        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 32       | 13.62%  |
| IvyBridge        | 19       | 8.09%   |
| KabyLake         | 18       | 7.66%   |
| Zen+             | 17       | 7.23%   |
| Penryn           | 16       | 6.81%   |
| Zen 2            | 15       | 6.38%   |
| SandyBridge      | 14       | 5.96%   |
| Piledriver       | 14       | 5.96%   |
| K10              | 13       | 5.53%   |
| Zen              | 11       | 4.68%   |
| Core             | 10       | 4.26%   |
| Zen 3            | 8        | 3.4%    |
| CometLake        | 8        | 3.4%    |
| Skylake          | 5        | 2.13%   |
| Silvermont       | 4        | 1.7%    |
| K10 Llano        | 4        | 1.7%    |
| Westmere         | 3        | 1.28%   |
| Steamroller      | 3        | 1.28%   |
| Nehalem          | 3        | 1.28%   |
| Bulldozer        | 3        | 1.28%   |
| Bobcat           | 3        | 1.28%   |
| NetBurst         | 2        | 0.85%   |
| K8 Hammer        | 2        | 0.85%   |
| Icelake          | 2        | 0.85%   |
| Jaguar           | 1        | 0.43%   |
| Goldmont plus    | 1        | 0.43%   |
| Excavator        | 1        | 0.43%   |
| Broadwell        | 1        | 0.43%   |
| Bonnell          | 1        | 0.43%   |
| Alderlake Hybrid | 1        | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 92       | 37.1%   |
| Nvidia                     | 84       | 33.87%  |
| Intel                      | 69       | 27.82%  |
| VIA Technologies           | 1        | 0.4%    |
| Matrox Electronics Systems | 1        | 0.4%    |
| ATI Technologies           | 1        | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 13       | 5.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 3.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 9        | 3.52%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 7        | 2.73%   |
| Nvidia GK208B [GeForce GT 710]                                              | 7        | 2.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 2.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.95%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 1.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 1.95%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.56%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.56%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 1.56%   |
| Intel HD Graphics 530                                                       | 4        | 1.56%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.56%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.17%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.17%   |
| AMD Wrestler [Radeon HD 6320]                                               | 3        | 1.17%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 3        | 1.17%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.17%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 3        | 1.17%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.78%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.78%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.78%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.78%   |
| Nvidia GF106GL [Quadro 2000]                                                | 2        | 0.78%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 0.78%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.78%   |
| Intel HD Graphics 630                                                       | 2        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 79       | 33.76%  |
| 1 x AMD      | 78       | 33.33%  |
| 1 x Intel    | 62       | 26.5%   |
| AMD + Nvidia | 6        | 2.56%   |
| 2 x AMD      | 5        | 2.14%   |
| Intel + AMD  | 2        | 0.85%   |
| 1 x VIA      | 1        | 0.43%   |
| 1 x Matrox   | 1        | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 178      | 76.07%  |
| Proprietary | 49       | 20.94%  |
| Unknown     | 7        | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 107      | 44.77%  |
| 1.01-2.0   | 40       | 16.74%  |
| 0.51-1.0   | 27       | 11.3%   |
| 0.01-0.5   | 21       | 8.79%   |
| 3.01-4.0   | 18       | 7.53%   |
| 8.01-16.0  | 8        | 3.35%   |
| 7.01-8.0   | 7        | 2.93%   |
| 5.01-6.0   | 7        | 2.93%   |
| 2.01-3.0   | 4        | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 55       | 22.92%  |
| Goldstar             | 43       | 17.92%  |
| Hewlett-Packard      | 28       | 11.67%  |
| Dell                 | 13       | 5.42%   |
| AOC                  | 13       | 5.42%   |
| LG Electronics       | 12       | 5%      |
| Lenovo               | 9        | 3.75%   |
| Unknown              | 7        | 2.92%   |
| ViewSonic            | 6        | 2.5%    |
| ___                  | 5        | 2.08%   |
| Sony                 | 5        | 2.08%   |
| KTC                  | 5        | 2.08%   |
| SAC                  | 4        | 1.67%   |
| Plain Tree Systems   | 3        | 1.25%   |
| Packard Bell         | 3        | 1.25%   |
| Envision             | 3        | 1.25%   |
| Ancor Communications | 3        | 1.25%   |
| Acer                 | 3        | 1.25%   |
| Philips              | 2        | 0.83%   |
| MSI                  | 2        | 0.83%   |
| Hitachi              | 2        | 0.83%   |
| CHR                  | 2        | 0.83%   |
| Westinghouse         | 1        | 0.42%   |
| Wacom                | 1        | 0.42%   |
| Unknown (XXX)        | 1        | 0.42%   |
| SKY                  | 1        | 0.42%   |
| Sharp                | 1        | 0.42%   |
| NCS                  | 1        | 0.42%   |
| Mi                   | 1        | 0.42%   |
| HKC                  | 1        | 0.42%   |
| GDH                  | 1        | 0.42%   |
| BenQ                 | 1        | 0.42%   |
| ASUSTek Computer     | 1        | 0.42%   |
| Unknown              | 1        | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7        | 2.73%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6        | 2.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 1.95%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 5        | 1.95%   |
| ___ LCDTV16 ___9000 1360x768                                          | 3        | 1.17%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 3        | 1.17%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 3        | 1.17%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 3        | 1.17%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 3        | 1.17%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 3        | 1.17%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 3        | 1.17%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 2        | 0.78%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 2        | 0.78%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                    | 2        | 0.78%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 2        | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.78%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2        | 0.78%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch | 2        | 0.78%   |
| Philips 190P PHL0831 1280x1024 376x301mm 19.0-inch                    | 2        | 0.78%   |
| MSI Optix MAG24C MSI1462 1920x1080 521x293mm 23.5-inch                | 2        | 0.78%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                           | 2        | 0.78%   |
| Lenovo LEN S22e-19 LEN61C9 1920x1080 476x268mm 21.5-inch              | 2        | 0.78%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch            | 2        | 0.78%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 510x290mm 23.1-inch      | 2        | 0.78%   |
| Hewlett-Packard 19ka HWP3328 1366x768 410x230mm 18.5-inch             | 2        | 0.78%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 2        | 0.78%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.78%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 2        | 0.78%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 2        | 0.78%   |
| AOC LE24H037 AOC2407 1920x1080 521x293mm 23.5-inch                    | 2        | 0.78%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2        | 0.78%   |
| Westinghouse LCM-19v5 WDE1905 1280x1024 376x301mm 19.0-inch           | 1        | 0.39%   |
| Wacom Cintiq 21UX 2 WAC1022 1600x1200 432x324mm 21.3-inch             | 1        | 0.39%   |
| ViewSonic VX2253 Series VSC0A28 1920x1080 476x268mm 21.5-inch         | 1        | 0.39%   |
| ViewSonic VX2240w VSC6B20 1680x1050 495x291mm 22.6-inch               | 1        | 0.39%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch              | 1        | 0.39%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch         | 1        | 0.39%   |
| ViewSonic VA1926wSERIES VSC5920 1440x900 410x256mm 19.0-inch          | 1        | 0.39%   |
| ViewSonic LCD Monitor VX2370 SERIES 1920x1080                         | 1        | 0.39%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch        | 1        | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 94       | 40.69%  |
| 1366x768 (WXGA)    | 23       | 9.96%   |
| 3840x2160 (4K)     | 18       | 7.79%   |
| 1360x768           | 18       | 7.79%   |
| 1440x900 (WXGA+)   | 16       | 6.93%   |
| 1600x900 (HD+)     | 12       | 5.19%   |
| 1280x1024 (SXGA)   | 11       | 4.76%   |
| 2560x1080          | 8        | 3.46%   |
| 2560x1440 (QHD)    | 6        | 2.6%    |
| 1680x1050 (WSXGA+) | 5        | 2.16%   |
| Unknown            | 5        | 2.16%   |
| 3840x1080          | 3        | 1.3%    |
| 3440x1440          | 3        | 1.3%    |
| 1024x768 (XGA)     | 3        | 1.3%    |
| 5760x1080          | 1        | 0.43%   |
| 3840x1600          | 1        | 0.43%   |
| 3286x1080          | 1        | 0.43%   |
| 1600x1200          | 1        | 0.43%   |
| 1280x960           | 1        | 0.43%   |
| 1280x768           | 1        | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 37       | 15.55%  |
| 23      | 35       | 14.71%  |
| Unknown | 27       | 11.34%  |
| 18      | 20       | 8.4%    |
| 19      | 15       | 6.3%    |
| 24      | 14       | 5.88%   |
| 34      | 11       | 4.62%   |
| 27      | 10       | 4.2%    |
| 20      | 10       | 4.2%    |
| 17      | 9        | 3.78%   |
| 15      | 9        | 3.78%   |
| 72      | 7        | 2.94%   |
| 32      | 7        | 2.94%   |
| 84      | 6        | 2.52%   |
| 31      | 6        | 2.52%   |
| 54      | 3        | 1.26%   |
| 22      | 3        | 1.26%   |
| 40      | 2        | 0.84%   |
| 65      | 1        | 0.42%   |
| 52      | 1        | 0.42%   |
| 46      | 1        | 0.42%   |
| 37      | 1        | 0.42%   |
| 28      | 1        | 0.42%   |
| 14      | 1        | 0.42%   |
| 13      | 1        | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 74       | 32.31%  |
| 501-600     | 54       | 23.58%  |
| Unknown     | 27       | 11.79%  |
| 701-800     | 18       | 7.86%   |
| 301-350     | 16       | 6.99%   |
| 1501-2000   | 13       | 5.68%   |
| 601-700     | 9        | 3.93%   |
| 351-400     | 7        | 3.06%   |
| 1001-1500   | 6        | 2.62%   |
| 801-900     | 3        | 1.31%   |
| 201-300     | 2        | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 145      | 67.76%  |
| Unknown | 22       | 10.28%  |
| 16/10   | 19       | 8.88%   |
| 5/4     | 12       | 5.61%   |
| 21/9    | 11       | 5.14%   |
| 4/3     | 5        | 2.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 76       | 32.62%  |
| 151-200        | 32       | 13.73%  |
| Unknown        | 27       | 11.59%  |
| 351-500        | 25       | 10.73%  |
| 141-150        | 24       | 10.3%   |
| More than 1000 | 18       | 7.73%   |
| 301-350        | 10       | 4.29%   |
| 101-110        | 10       | 4.29%   |
| 251-300        | 4        | 1.72%   |
| 501-1000       | 4        | 1.72%   |
| 131-140        | 2        | 0.86%   |
| 91-100         | 1        | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 124      | 55.36%  |
| 101-120 | 46       | 20.54%  |
| Unknown | 27       | 12.05%  |
| 1-50    | 22       | 9.82%   |
| 121-160 | 4        | 1.79%   |
| 161-240 | 1        | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 177      | 74.68%  |
| 2     | 40       | 16.88%  |
| 0     | 13       | 5.49%   |
| 3     | 7        | 2.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 166      | 47.98%  |
| Intel                           | 64       | 18.5%   |
| Qualcomm Atheros                | 19       | 5.49%   |
| Ralink Technology               | 14       | 4.05%   |
| Ralink                          | 12       | 3.47%   |
| TP-Link                         | 9        | 2.6%    |
| Broadcom                        | 9        | 2.6%    |
| Xiaomi                          | 8        | 2.31%   |
| Broadcom Limited                | 6        | 1.73%   |
| Qualcomm Atheros Communications | 4        | 1.16%   |
| Nvidia                          | 4        | 1.16%   |
| D-Link System                   | 4        | 1.16%   |
| D-Link                          | 4        | 1.16%   |
| Motorola PCS                    | 3        | 0.87%   |
| Marvell Technology Group        | 3        | 0.87%   |
| Huawei Technologies             | 3        | 0.87%   |
| VIA Technologies                | 2        | 0.58%   |
| Samsung Electronics             | 2        | 0.58%   |
| Microsoft                       | 2        | 0.58%   |
| Spreadtrum Communications       | 1        | 0.29%   |
| Padix (Rockfire)                | 1        | 0.29%   |
| Oculus VR                       | 1        | 0.29%   |
| Mercucys                        | 1        | 0.29%   |
| MediaTek                        | 1        | 0.29%   |
| Manta                           | 1        | 0.29%   |
| ICS Advent                      | 1        | 0.29%   |
| HMD Global                      | 1        | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 138      | 35.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 2.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 2.06%   |
| Intel I211 Gigabit Network Connection                             | 8        | 2.06%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.54%   |
| Intel Wireless 7260                                               | 6        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6        | 1.54%   |
| Realtek 802.11ac NIC                                              | 5        | 1.29%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.29%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.29%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4        | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 1.03%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 4        | 1.03%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 4        | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.77%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.77%   |
| Huawei LLD-L21                                                    | 3        | 0.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.51%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.51%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 2        | 0.51%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.51%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 25.2%   |
| Realtek Semiconductor           | 30       | 24.39%  |
| Ralink Technology               | 14       | 11.38%  |
| Ralink                          | 12       | 9.76%   |
| TP-Link                         | 9        | 7.32%   |
| Qualcomm Atheros                | 8        | 6.5%    |
| Qualcomm Atheros Communications | 4        | 3.25%   |
| D-Link                          | 4        | 3.25%   |
| Broadcom Limited                | 3        | 2.44%   |
| Broadcom                        | 3        | 2.44%   |
| Microsoft                       | 2        | 1.63%   |
| D-Link System                   | 2        | 1.63%   |
| Mercucys                        | 1        | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                      | 7        | 5.69%   |
| Intel Wireless 7260                                                  | 6        | 4.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 6        | 4.88%   |
| Realtek 802.11ac NIC                                                 | 5        | 4.07%   |
| Intel Wi-Fi 6 AX200                                                  | 5        | 4.07%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 4        | 3.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 4        | 3.25%   |
| Ralink RT5392 PCIe Wireless Network Adapter                          | 4        | 3.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 4        | 3.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 2.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 3        | 2.44%   |
| Qualcomm Atheros AR9271 802.11n                                      | 3        | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 2.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 1.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2        | 1.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 1.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2        | 1.63%   |
| Realtek RTL8187 Wireless Adapter                                     | 2        | 1.63%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 2        | 1.63%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 1.63%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2        | 1.63%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 2        | 1.63%   |
| Intel Wireless-AC 9260                                               | 2        | 1.63%   |
| Intel Wireless 8260                                                  | 2        | 1.63%   |
| Intel Wireless 7265                                                  | 2        | 1.63%   |
| D-Link WLAN controller                                               | 2        | 1.63%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 2        | 1.63%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 0.81%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.81%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.81%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.81%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1        | 0.81%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                            | 1        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 158      | 61.72%  |
| Intel                     | 47       | 18.36%  |
| Qualcomm Atheros          | 12       | 4.69%   |
| Xiaomi                    | 8        | 3.13%   |
| Broadcom                  | 6        | 2.34%   |
| Nvidia                    | 4        | 1.56%   |
| Marvell Technology Group  | 3        | 1.17%   |
| Huawei Technologies       | 3        | 1.17%   |
| Broadcom Limited          | 3        | 1.17%   |
| VIA Technologies          | 2        | 0.78%   |
| Samsung Electronics       | 2        | 0.78%   |
| Motorola PCS              | 2        | 0.78%   |
| D-Link System             | 2        | 0.78%   |
| Spreadtrum Communications | 1        | 0.39%   |
| MediaTek                  | 1        | 0.39%   |
| ICS Advent                | 1        | 0.39%   |
| HMD Global                | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 138      | 52.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11       | 4.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 3.05%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.29%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.91%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.15%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.15%   |
| Huawei LLD-L21                                                    | 3        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.76%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.76%   |
| Motorola PCS moto g(30)                                           | 2        | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.76%   |
| Intel Ethernet Connection I218-V                                  | 2        | 0.76%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.76%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.76%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.76%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.76%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 0.76%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 2        | 0.76%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.38%   |
| Spreadtrum Spreadtrum Phone                                       | 1        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.38%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.38%   |
| MediaTek Armor X10 Pro                                            | 1        | 0.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.38%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 230      | 66.67%  |
| WiFi     | 111      | 32.17%  |
| Unknown  | 3        | 0.87%   |
| Modem    | 1        | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 174      | 74.36%  |
| WiFi     | 60       | 25.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 154      | 65.53%  |
| 2     | 69       | 29.36%  |
| 3     | 10       | 4.26%   |
| 4     | 1        | 0.43%   |
| 0     | 1        | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 214      | 90.3%   |
| Yes  | 23       | 9.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 28       | 36.84%  |
| Cambridge Silicon Radio         | 24       | 31.58%  |
| Realtek Semiconductor           | 12       | 15.79%  |
| Broadcom                        | 7        | 9.21%   |
| Qualcomm Atheros Communications | 2        | 2.63%   |
| ASUSTek Computer                | 2        | 2.63%   |
| Apple                           | 1        | 1.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24       | 31.58%  |
| Realtek Bluetooth Radio                             | 10       | 13.16%  |
| Intel Bluetooth wireless interface                  | 10       | 13.16%  |
| Intel AX210 Bluetooth                               | 6        | 7.89%   |
| Intel AX200 Bluetooth                               | 5        | 6.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 3.95%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 3        | 3.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 1.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.32%   |
| Intel AX201 Bluetooth                               | 1        | 1.32%   |
| Broadcom HP Bluetooth Module                        | 1        | 1.32%   |
| Broadcom HP Bluethunder                             | 1        | 1.32%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 1.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.32%   |
| ASUS Bluetooth Radio                                | 1        | 1.32%   |
| ASUS BCM20702A0                                     | 1        | 1.32%   |
| Apple Bluetooth HCI                                 | 1        | 1.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 131      | 34.29%  |
| AMD                                          | 115      | 30.1%   |
| Nvidia                                       | 78       | 20.42%  |
| C-Media Electronics                          | 9        | 2.36%   |
| Creative Labs                                | 7        | 1.83%   |
| Razer USA                                    | 5        | 1.31%   |
| Logitech                                     | 4        | 1.05%   |
| Creative Technology                          | 3        | 0.79%   |
| VIA Technologies                             | 2        | 0.52%   |
| Texas Instruments                            | 2        | 0.52%   |
| Kingston Technology                          | 2        | 0.52%   |
| JMTek                                        | 2        | 0.52%   |
| Generalplus Technology                       | 2        | 0.52%   |
| Corsair                                      | 2        | 0.52%   |
| Arturia                                      | 2        | 0.52%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.26%   |
| Unknown                                      | 1        | 0.26%   |
| Trust                                        | 1        | 0.26%   |
| Synaptics                                    | 1        | 0.26%   |
| Realtek Semiconductor                        | 1        | 0.26%   |
| PreSonus Audio Electronics                   | 1        | 0.26%   |
| Native Instruments                           | 1        | 0.26%   |
| Micro Star International                     | 1        | 0.26%   |
| Hewlett-Packard                              | 1        | 0.26%   |
| GYROCOM C&C                                  | 1        | 0.26%   |
| Focusrite-Novation                           | 1        | 0.26%   |
| eMPIA Technology                             | 1        | 0.26%   |
| Blue Microphones                             | 1        | 0.26%   |
| ATI Technologies                             | 1        | 0.26%   |
| Apple                                        | 1        | 0.26%   |
| Afatech                                      | 1        | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 24       | 5.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 23       | 4.97%   |
| AMD Starship/Matisse HD Audio Controller                                          | 21       | 4.54%   |
| AMD Family 17h/19h HD Audio Controller                                            | 21       | 4.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 16       | 3.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 14       | 3.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 14       | 3.02%   |
| AMD FCH Azalia Controller                                                         | 13       | 2.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 10       | 2.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9        | 1.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 1.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9        | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 9        | 1.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 1.73%   |
| Nvidia GP108 High Definition Audio Controller                                     | 7        | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.51%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 7        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 1.51%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 6        | 1.3%    |
| Intel 200 Series PCH HD Audio                                                     | 6        | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 1.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6        | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                                     | 5        | 1.08%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 1.08%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.86%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                                | 4        | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                                     | 4        | 0.86%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 4        | 0.86%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.86%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.65%   |
| Logitech H390 headset with microphone                                             | 3        | 0.65%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 26       | 21.49%  |
| Crucial             | 21       | 17.36%  |
| Unknown             | 15       | 12.4%   |
| Samsung Electronics | 14       | 11.57%  |
| Corsair             | 13       | 10.74%  |
| SK hynix            | 6        | 4.96%   |
| A-DATA Technology   | 5        | 4.13%   |
| Micron Technology   | 4        | 3.31%   |
| G.Skill             | 4        | 3.31%   |
| Patriot             | 3        | 2.48%   |
| Hikvision           | 2        | 1.65%   |
| Team                | 1        | 0.83%   |
| Nanya Technology    | 1        | 0.83%   |
| Kreton              | 1        | 0.83%   |
| Goldenmars          | 1        | 0.83%   |
| GLOWAY              | 1        | 0.83%   |
| Elpida              | 1        | 0.83%   |
| Atermiter           | 1        | 0.83%   |
| Ankowall            | 1        | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s       | 3        | 2.24%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 2.24%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 2.24%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 2        | 1.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 1.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 2        | 1.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 2        | 1.49%   |
| Kingston RAM KHX3466C17D4/16GX 16GB DIMM DDR4 3466MT/s   | 2        | 1.49%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4GB DIMM DDR4 2666MT/s     | 2        | 1.49%   |
| Crucial RAM BLS8G4D30AESEK.M8FE 8GB DIMM DDR4 3600MT/s   | 2        | 1.49%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 1.49%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 2        | 1.49%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.75%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.75%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.75%   |
| Unknown RAM Module 8192MB DIMM DDR3                      | 1        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 0.75%   |
| Unknown RAM Module 2GB DIMM                              | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.75%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                  | 1        | 0.75%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 1        | 0.75%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s          | 1        | 0.75%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s            | 1        | 0.75%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB DIMM SDRAM 2048MT/s | 1        | 0.75%   |
| SK hynix RAM HMT151R7BFR4C 4096MB DIMM DDR3 1333MT/s     | 1        | 0.75%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s   | 1        | 0.75%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8GB DIMM DDR4 2666MT/s     | 1        | 0.75%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.75%   |
| Samsung RAM M471B1G73QHO-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.75%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 1        | 0.75%   |
| Samsung RAM M393B5273CH0-YH9 4GB DIMM DDR3 1333MT/s      | 1        | 0.75%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s          | 1        | 0.75%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1866MT/s         | 1        | 0.75%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s      | 1        | 0.75%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 52       | 49.52%  |
| DDR3    | 38       | 36.19%  |
| DDR2    | 6        | 5.71%   |
| SDRAM   | 5        | 4.76%   |
| Unknown | 3        | 2.86%   |
| DDR     | 1        | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 94       | 90.38%  |
| SODIMM | 10       | 9.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 48       | 40.68%  |
| 4096  | 27       | 22.88%  |
| 2048  | 21       | 17.8%   |
| 16384 | 14       | 11.86%  |
| 32768 | 7        | 5.93%   |
| 1024  | 1        | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 22       | 17.89%  |
| 1333    | 16       | 13.01%  |
| 3600    | 9        | 7.32%   |
| 2133    | 9        | 7.32%   |
| 2667    | 8        | 6.5%    |
| 2400    | 8        | 6.5%    |
| 3466    | 5        | 4.07%   |
| 3200    | 5        | 4.07%   |
| Unknown | 5        | 4.07%   |
| 667     | 4        | 3.25%   |
| 3266    | 3        | 2.44%   |
| 3000    | 3        | 2.44%   |
| 2933    | 3        | 2.44%   |
| 2666    | 3        | 2.44%   |
| 1866    | 3        | 2.44%   |
| 800     | 3        | 2.44%   |
| 3733    | 2        | 1.63%   |
| 1334    | 2        | 1.63%   |
| 1066    | 2        | 1.63%   |
| 4000    | 1        | 0.81%   |
| 3800    | 1        | 0.81%   |
| 3666    | 1        | 0.81%   |
| 3400    | 1        | 0.81%   |
| 3134    | 1        | 0.81%   |
| 2800    | 1        | 0.81%   |
| 2048    | 1        | 0.81%   |
| 1067    | 1        | 0.81%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 4        | 30.77%  |
| Canon               | 3        | 23.08%  |
| Brother Industries  | 3        | 23.08%  |
| Hewlett-Packard     | 2        | 15.38%  |
| QinHeng Electronics | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Brother HL-1200 series     | 3        | 23.08%  |
| Seiko Epson XP-2100 Series | 1        | 7.69%   |
| Seiko Epson Printer        | 1        | 7.69%   |
| Seiko Epson L210 Series    | 1        | 7.69%   |
| Seiko Epson ET-2710 Series | 1        | 7.69%   |
| QinHeng CH340S             | 1        | 7.69%   |
| HP Deskjet 4640 series     | 1        | 7.69%   |
| HP Deskjet 4620 series     | 1        | 7.69%   |
| Canon PIXMA MP250          | 1        | 7.69%   |
| Canon G2000 series         | 1        | 7.69%   |
| Canon G1000 series         | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 2        | 50%     |
| Canon       | 2        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1        | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1        | 25%     |
| Canon CanoScan LiDE 110                       | 1        | 25%     |
| Canon CanoScan D1250U2                        | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 8        | 14.55%  |
| Generalplus Technology        | 6        | 10.91%  |
| Chicony Electronics           | 6        | 10.91%  |
| Microdia                      | 5        | 9.09%   |
| Apple                         | 4        | 7.27%   |
| Sunplus Innovation Technology | 3        | 5.45%   |
| Lenovo                        | 3        | 5.45%   |
| Jieli Technology              | 3        | 5.45%   |
| Microsoft                     | 2        | 3.64%   |
| Alcor Micro                   | 2        | 3.64%   |
| 2M UVC CAMERA                 | 2        | 3.64%   |
| Z-Star Microelectronics       | 1        | 1.82%   |
| YGTek                         | 1        | 1.82%   |
| Unknown                       | 1        | 1.82%   |
| SN0002                        | 1        | 1.82%   |
| Realtek Semiconductor         | 1        | 1.82%   |
| Razer USA                     | 1        | 1.82%   |
| OmniVision Technologies       | 1        | 1.82%   |
| MacroSilicon                  | 1        | 1.82%   |
| KYE Systems (Mouse Systems)   | 1        | 1.82%   |
| AVerMedia Technologies        | 1        | 1.82%   |
| Arkmicro Technologies         | 1        | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Generalplus GENERAL WEBCAM                    | 6        | 10.91%  |
| Logitech C922 Pro Stream Webcam               | 4        | 7.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 4        | 7.27%   |
| Jieli USB PHY 2.0                             | 3        | 5.45%   |
| Chicony HP 0.3MP Webcam                       | 3        | 5.45%   |
| Sunplus HD 720P webcam                        | 2        | 3.64%   |
| Microdia Webcam Vitade AF                     | 2        | 3.64%   |
| Lenovo 500 RGB Camera                         | 2        | 3.64%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam          | 2        | 3.64%   |
| Z-Star Integrated Camera                      | 1        | 1.82%   |
| YGTek Webcam                                  | 1        | 1.82%   |
| Unknown HD camera                             | 1        | 1.82%   |
| Sunplus Aukey-PC-LM1E Camera                  | 1        | 1.82%   |
| SN0002 1080P Web Camera                       | 1        | 1.82%   |
| Realtek NexiGo N660P FHD Webcam               | 1        | 1.82%   |
| Razer USA Razer Kiyo Pro                      | 1        | 1.82%   |
| OmniVision OV511+ Webcam                      | 1        | 1.82%   |
| Microsoft MicrosoftÂ LifeCam Studio          | 1        | 1.82%   |
| Microsoft LifeCam VX-800                      | 1        | 1.82%   |
| Microdia USB camera                           | 1        | 1.82%   |
| Microdia REDRAGON Live Camera Audio           | 1        | 1.82%   |
| Microdia PC-LM1E                              | 1        | 1.82%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 1.82%   |
| Logitech Webcam C270                          | 1        | 1.82%   |
| Logitech Webcam C210                          | 1        | 1.82%   |
| Logitech Webcam C170                          | 1        | 1.82%   |
| Logitech StreamCam                            | 1        | 1.82%   |
| Lenovo FHD Webcam Audio                       | 1        | 1.82%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 1.82%   |
| Chicony HP High Definition 1MP Webcam         | 1        | 1.82%   |
| Chicony HP 1.0MP High Definition Webcam       | 1        | 1.82%   |
| Chicony CNF8050 Webcam                        | 1        | 1.82%   |
| AVerMedia Live Streamer CAM 313               | 1        | 1.82%   |
| Arkmicro USB2.0 PC CAMERA                     | 1        | 1.82%   |
| Alcor Micro USB Video Device                  | 1        | 1.82%   |
| Alcor Micro USB 2.0 PC Camera                 | 1        | 1.82%   |

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
| 0     | 198      | 83.9%   |
| 1     | 33       | 13.98%  |
| 2     | 5        | 2.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 32.5%   |
| Graphics card            | 10       | 25%     |
| Unassigned class         | 6        | 15%     |
| Communication controller | 3        | 7.5%    |
| Sound                    | 2        | 5%      |
| Network                  | 2        | 5%      |
| Multimedia controller    | 1        | 2.5%    |
| Firewire controller      | 1        | 2.5%    |
| Camera                   | 1        | 2.5%    |
| Bluetooth                | 1        | 2.5%    |

