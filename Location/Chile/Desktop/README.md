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

Total: 330

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04       | 24       | 10.34%  |
| Ubuntu 18.04       | 19       | 8.19%   |
| Arch               | 10       | 4.31%   |
| Ubuntu 22.04       | 8        | 3.45%   |
| OpenMandriva 4.2   | 8        | 3.45%   |
| Zorin 16           | 7        | 3.02%   |
| Ubuntu 19.04       | 7        | 3.02%   |
| Pop!_OS 22.04      | 7        | 3.02%   |
| OpenMandriva 4.3   | 7        | 3.02%   |
| Arch Rolling       | 7        | 3.02%   |
| Manjaro            | 6        | 2.59%   |
| Linux Mint 20.1    | 6        | 2.59%   |
| Zorin 15           | 5        | 2.16%   |
| Pop!_OS 20.10      | 5        | 2.16%   |
| KDE neon 20.04     | 5        | 2.16%   |
| Debian Testing     | 5        | 2.16%   |
| Ubuntu 21.04       | 4        | 1.72%   |
| OpenMandriva 23.01 | 4        | 1.72%   |
| Fedora 34          | 4        | 1.72%   |
| Ubuntu 21.10       | 3        | 1.29%   |
| Ubuntu 19.10       | 3        | 1.29%   |
| Linux Mint 20      | 3        | 1.29%   |
| Linux Mint 19.3    | 3        | 1.29%   |
| Kubuntu 20.04      | 3        | 1.29%   |
| Fedora 35          | 3        | 1.29%   |
| Fedora 33          | 3        | 1.29%   |
| Fedora 32          | 3        | 1.29%   |
| Debian 11          | 3        | 1.29%   |
| Ubuntu 20.10       | 2        | 0.86%   |
| Ubuntu 18.10       | 2        | 0.86%   |
| Ubuntu 16.04       | 2        | 0.86%   |
| Pop!_OS 21.10      | 2        | 0.86%   |
| Pop!_OS 20.04      | 2        | 0.86%   |
| Nobara 36          | 2        | 0.86%   |
| Manjaro 21.0       | 2        | 0.86%   |
| Linux Mint 20.3    | 2        | 0.86%   |
| Linux Mint 20.2    | 2        | 0.86%   |
| Linux Mint 19.2    | 2        | 0.86%   |
| KDE neon 18.04     | 2        | 0.86%   |
| Debian             | 2        | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 74       | 33.79%  |
| OpenMandriva     | 19       | 8.68%   |
| Linux Mint       | 19       | 8.68%   |
| Pop!_OS          | 15       | 6.85%   |
| Fedora           | 14       | 6.39%   |
| Arch             | 14       | 6.39%   |
| Zorin            | 13       | 5.94%   |
| Manjaro          | 9        | 4.11%   |
| Debian           | 9        | 4.11%   |
| KDE neon         | 7        | 3.2%    |
| Kubuntu          | 5        | 2.28%   |
| Ubuntu MATE      | 2        | 0.91%   |
| Nobara           | 2        | 0.91%   |
| Elementary       | 2        | 0.91%   |
| ArcoLinux        | 2        | 0.91%   |
| Ubuntu Budgie    | 1        | 0.46%   |
| ROSA             | 1        | 0.46%   |
| org.kde.Platform | 1        | 0.46%   |
| Lubuntu          | 1        | 0.46%   |
| LMDE             | 1        | 0.46%   |
| LinuxFX          | 1        | 0.46%   |
| Linux Lite       | 1        | 0.46%   |
| Kali             | 1        | 0.46%   |
| Gentoo           | 1        | 0.46%   |
| Garuda Linux     | 1        | 0.46%   |
| Endless          | 1        | 0.46%   |
| EndeavourOS      | 1        | 0.46%   |
| Clear Linux      | 1        | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 7        | 2.73%   |
| 5.10.14-desktop-1omv4002 | 7        | 2.73%   |
| 5.4.0-42-generic         | 6        | 2.34%   |
| 5.15.0-58-generic        | 6        | 2.34%   |
| 6.1.1-desktop-1omv2290   | 4        | 1.56%   |
| 5.9.16-1-MANJARO         | 4        | 1.56%   |
| 5.0.0-13-generic         | 4        | 1.56%   |
| 5.4.0-77-generic         | 3        | 1.17%   |
| 5.4.0-33-generic         | 3        | 1.17%   |
| 5.4.0-26-generic         | 3        | 1.17%   |
| 5.11.0-7614-generic      | 3        | 1.17%   |
| 4.18.0-18-generic        | 3        | 1.17%   |
| 5.8.0-59-generic         | 2        | 0.78%   |
| 5.8.0-48-generic         | 2        | 0.78%   |
| 5.4.0-89-generic         | 2        | 0.78%   |
| 5.4.0-74-generic         | 2        | 0.78%   |
| 5.4.0-70-generic         | 2        | 0.78%   |
| 5.4.0-65-generic         | 2        | 0.78%   |
| 5.4.0-52-generic         | 2        | 0.78%   |
| 5.4.0-47-generic         | 2        | 0.78%   |
| 5.4.0-29-generic         | 2        | 0.78%   |
| 5.4.0-124-generic        | 2        | 0.78%   |
| 5.4.0-117-generic        | 2        | 0.78%   |
| 5.3.0-53-generic         | 2        | 0.78%   |
| 5.18.10-76051810-generic | 2        | 0.78%   |
| 5.17.5-76051705-generic  | 2        | 0.78%   |
| 5.15.0-52-generic        | 2        | 0.78%   |
| 5.13.0-39-generic        | 2        | 0.78%   |
| 5.11.0-41-generic        | 2        | 0.78%   |
| 5.11.0-34-generic        | 2        | 0.78%   |
| 5.11.0-27-generic        | 2        | 0.78%   |
| 5.11.0-18-generic        | 2        | 0.78%   |
| 4.18.0-20-generic        | 2        | 0.78%   |
| 4.18.0-17-generic        | 2        | 0.78%   |
| 4.18.0-15-generic        | 2        | 0.78%   |
| 4.15.0-43-generic        | 2        | 0.78%   |
| 4.15.0-112-generic       | 2        | 0.78%   |
| 6.2.6-arch1-1            | 1        | 0.39%   |
| 6.2.6-76060206-generic   | 1        | 0.39%   |
| 6.1.7-arch1-1            | 1        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 40       | 16.6%   |
| 5.15.0  | 18       | 7.47%   |
| 5.11.0  | 15       | 6.22%   |
| 4.15.0  | 14       | 5.81%   |
| 5.8.0   | 11       | 4.56%   |
| 5.0.0   | 10       | 4.15%   |
| 4.18.0  | 10       | 4.15%   |
| 5.3.0   | 9        | 3.73%   |
| 5.13.0  | 9        | 3.73%   |
| 5.16.7  | 7        | 2.9%    |
| 5.10.14 | 7        | 2.9%    |
| 6.1.1   | 5        | 2.07%   |
| 5.9.16  | 5        | 2.07%   |
| 5.19.0  | 4        | 1.66%   |
| 6.1.11  | 3        | 1.24%   |
| 5.18.10 | 3        | 1.24%   |
| 5.17.5  | 3        | 1.24%   |
| 5.10.0  | 3        | 1.24%   |
| 6.2.6   | 2        | 0.83%   |
| 5.8.12  | 2        | 0.83%   |
| 5.16.16 | 2        | 0.83%   |
| 5.14.0  | 2        | 0.83%   |
| 5.13.13 | 2        | 0.83%   |
| 5.13.12 | 2        | 0.83%   |
| 6.1.7   | 1        | 0.41%   |
| 6.1.18  | 1        | 0.41%   |
| 6.1.0   | 1        | 0.41%   |
| 6.0.6   | 1        | 0.41%   |
| 6.0.0   | 1        | 0.41%   |
| 5.9.8   | 1        | 0.41%   |
| 5.9.1   | 1        | 0.41%   |
| 5.7.6   | 1        | 0.41%   |
| 5.7.10  | 1        | 0.41%   |
| 5.6.6   | 1        | 0.41%   |
| 5.6.18  | 1        | 0.41%   |
| 5.4.94  | 1        | 0.41%   |
| 5.3.1   | 1        | 0.41%   |
| 5.19.9  | 1        | 0.41%   |
| 5.19.8  | 1        | 0.41%   |
| 5.19.5  | 1        | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 41       | 17.23%  |
| 5.15    | 22       | 9.24%   |
| 5.11    | 18       | 7.56%   |
| 5.13    | 17       | 7.14%   |
| 5.10    | 15       | 6.3%    |
| 4.15    | 14       | 5.88%   |
| 5.8     | 13       | 5.46%   |
| 6.1     | 11       | 4.62%   |
| 5.3     | 10       | 4.2%    |
| 5.16    | 10       | 4.2%    |
| 5.0     | 10       | 4.2%    |
| 4.18    | 10       | 4.2%    |
| 5.19    | 9        | 3.78%   |
| 5.9     | 7        | 2.94%   |
| 5.17    | 6        | 2.52%   |
| 5.14    | 6        | 2.52%   |
| 5.18    | 5        | 2.1%    |
| 5.12    | 3        | 1.26%   |
| 6.2     | 2        | 0.84%   |
| 6.0     | 2        | 0.84%   |
| 5.7     | 2        | 0.84%   |
| 5.6     | 2        | 0.84%   |
| 4.19    | 2        | 0.84%   |
| 4.9     | 1        | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 212      | 98.6%   |
| i686   | 3        | 1.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 89       | 40.45%  |
| KDE5       | 42       | 19.09%  |
| Unknown    | 33       | 15%     |
| X-Cinnamon | 16       | 7.27%   |
| XFCE       | 15       | 6.82%   |
| KDE        | 10       | 4.55%   |
| xmonad     | 2        | 0.91%   |
| Pantheon   | 2        | 0.91%   |
| MATE       | 2        | 0.91%   |
| LXDE       | 2        | 0.91%   |
| Cinnamon   | 2        | 0.91%   |
| Budgie     | 2        | 0.91%   |
| KDE4       | 1        | 0.45%   |
| i3         | 1        | 0.45%   |
| Deepin     | 1        | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 165      | 76.04%  |
| Unknown | 26       | 11.98%  |
| Wayland | 25       | 11.52%  |
| Tty     | 1        | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 133      | 60.18%  |
| SDDM    | 34       | 15.38%  |
| GDM     | 21       | 9.5%    |
| LightDM | 14       | 6.33%   |
| GDM3    | 11       | 4.98%   |
| TDM     | 6        | 2.71%   |
| LXDM    | 1        | 0.45%   |
| KDM     | 1        | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CL   | 112      | 50.91%  |
| en_US   | 52       | 23.64%  |
| Unknown | 34       | 15.45%  |
| es_ES   | 10       | 4.55%   |
| en_GB   | 5        | 2.27%   |
| es_MX   | 3        | 1.36%   |
| C       | 2        | 0.91%   |
| pt_BR   | 1        | 0.45%   |
| es_UY   | 1        | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 134      | 60.63%  |
| EFI  | 87       | 39.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 169      | 76.82%  |
| Btrfs   | 20       | 9.09%   |
| Overlay | 18       | 8.18%   |
| Unknown | 7        | 3.18%   |
| Ext2    | 3        | 1.36%   |
| Zfs     | 2        | 0.91%   |
| Xfs     | 1        | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 138      | 61.88%  |
| GPT     | 61       | 27.35%  |
| MBR     | 24       | 10.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 185      | 84.47%  |
| Yes       | 34       | 15.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 61.71%  |
| Yes       | 85       | 38.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 59       | 27.44%  |
| MSI                 | 40       | 18.6%   |
| Gigabyte Technology | 22       | 10.23%  |
| Hewlett-Packard     | 18       | 8.37%   |
| Intel               | 15       | 6.98%   |
| ECS                 | 10       | 4.65%   |
| Dell                | 8        | 3.72%   |
| ASRock              | 6        | 2.79%   |
| Pegatron            | 4        | 1.86%   |
| Lenovo              | 4        | 1.86%   |
| Huanan              | 4        | 1.86%   |
| Unknown             | 3        | 1.4%    |
| TPV-INVENTA         | 2        | 0.93%   |
| MACHINIST           | 2        | 0.93%   |
| HC                  | 2        | 0.93%   |
| ViewSonic           | 1        | 0.47%   |
| SZMZ                | 1        | 0.47%   |
| R-StyleComputers    | 1        | 0.47%   |
| Quanta              | 1        | 0.47%   |
| PCPartner           | 1        | 0.47%   |
| Olidata             | 1        | 0.47%   |
| Nvidia              | 1        | 0.47%   |
| JGINYUE             | 1        | 0.47%   |
| IBM                 | 1        | 0.47%   |
| Foxconn             | 1        | 0.47%   |
| eMachines           | 1        | 0.47%   |
| Elo TouchSystems    | 1        | 0.47%   |
| Colorful Technology | 1        | 0.47%   |
| BESSTAR Tech        | 1        | 0.47%   |
| Apple               | 1        | 0.47%   |
| AMI                 | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| ASUS All Series                           | 6        | 2.79%   |
| MSI MS-7817                               | 5        | 2.33%   |
| ASUS PRIME B450M-A                        | 4        | 1.86%   |
| ASUS PRIME A320M-K                        | 4        | 1.86%   |
| Unknown                                   | 4        | 1.86%   |
| MSI MS-7A34                               | 3        | 1.4%    |
| MSI MS-7788                               | 3        | 1.4%    |
| ASUS TUF Gaming B450M-PLUS II             | 3        | 1.4%    |
| MSI Pro 3000/3080                         | 2        | 0.93%   |
| MSI MS-7A65                               | 2        | 0.93%   |
| MSI MS-7A15                               | 2        | 0.93%   |
| MSI MS-7693                               | 2        | 0.93%   |
| Intel X79M-S                              | 2        | 0.93%   |
| HP Compaq Pro 6300 SFF                    | 2        | 0.93%   |
| HP Compaq Pro 4300 SFF PC                 | 2        | 0.93%   |
| HC HCAR357-MI                             | 2        | 0.93%   |
| Gigabyte B450M DS3H V2                    | 2        | 0.93%   |
| Gigabyte B450 AORUS PRO WIFI              | 2        | 0.93%   |
| ECS MCP61M-M3                             | 2        | 0.93%   |
| ECS A960M-MV                              | 2        | 0.93%   |
| ECS A740GM-M                              | 2        | 0.93%   |
| ASUS TUF Gaming X570-PLUS                 | 2        | 0.93%   |
| ASUS SABERTOOTH 990FX R2.0                | 2        | 0.93%   |
| ASUS PRIME H410M-E                        | 2        | 0.93%   |
| ASUS M5A99X EVO                           | 2        | 0.93%   |
| ASUS F2A55-M LK2                          | 2        | 0.93%   |
| ViewSonic VOT132                          | 1        | 0.47%   |
| TPV-INVENTA Pro 1005 Series All-in-One PC | 1        | 0.47%   |
| TPV-INVENTA CQ1-3130LA                    | 1        | 0.47%   |
| SZMZ X99M-G2                              | 1        | 0.47%   |
| R-StyleComputers ALICON AI2S-A21 00.69    | 1        | 0.47%   |
| Quanta 120-1016la                         | 1        | 0.47%   |
| Pegatron SAISHIAT2                        | 1        | 0.47%   |
| Pegatron 9100                             | 1        | 0.47%   |
| Pegatron 520-1135la                       | 1        | 0.47%   |
| Pegatron 23-d015la                        | 1        | 0.47%   |
| PCPartner G43-F71862                      | 1        | 0.47%   |
| Nvidia NF-MCP61                           | 1        | 0.47%   |
| MSI TITAN                                 | 1        | 0.47%   |
| MSI MS-7D53                               | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 15       | 6.98%   |
| ASUS TUF                | 9        | 4.19%   |
| HP Compaq               | 7        | 3.26%   |
| ASUS All                | 6        | 2.79%   |
| MSI MS-7817             | 5        | 2.33%   |
| Lenovo ThinkCentre      | 4        | 1.86%   |
| Dell OptiPlex           | 4        | 1.86%   |
| ASUS M5A78L-M           | 4        | 1.86%   |
| Unknown                 | 4        | 1.86%   |
| MSI MS-7A34             | 3        | 1.4%    |
| MSI MS-7788             | 3        | 1.4%    |
| Huanan X79              | 3        | 1.4%    |
| HP ProDesk              | 3        | 1.4%    |
| HP EliteDesk            | 3        | 1.4%    |
| Gigabyte B450M          | 3        | 1.4%    |
| ASUS SABERTOOTH         | 3        | 1.4%    |
| MSI Pro                 | 2        | 0.93%   |
| MSI MS-7A65             | 2        | 0.93%   |
| MSI MS-7A15             | 2        | 0.93%   |
| MSI MS-7693             | 2        | 0.93%   |
| Intel X79M-S            | 2        | 0.93%   |
| Intel D54250WYK         | 2        | 0.93%   |
| HC HCAR357-MI           | 2        | 0.93%   |
| Gigabyte B450           | 2        | 0.93%   |
| ECS MCP61M-M3           | 2        | 0.93%   |
| ECS A960M-MV            | 2        | 0.93%   |
| ECS A740GM-M            | 2        | 0.93%   |
| Dell Precision          | 2        | 0.93%   |
| ASUS ROG                | 2        | 0.93%   |
| ASUS M5A99X             | 2        | 0.93%   |
| ASUS F2A55-M            | 2        | 0.93%   |
| ViewSonic VOT132        | 1        | 0.47%   |
| TPV-INVENTA Pro         | 1        | 0.47%   |
| TPV-INVENTA CQ1-3130LA  | 1        | 0.47%   |
| SZMZ X99M-G2            | 1        | 0.47%   |
| R-StyleComputers ALICON | 1        | 0.47%   |
| Quanta 120-1016la       | 1        | 0.47%   |
| Pegatron SAISHIAT2      | 1        | 0.47%   |
| Pegatron 9100           | 1        | 0.47%   |
| Pegatron 520-1135la     | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 27       | 12.56%  |
| 2012 | 25       | 11.63%  |
| 2018 | 22       | 10.23%  |
| 2013 | 20       | 9.3%    |
| 2014 | 16       | 7.44%   |
| 2019 | 15       | 6.98%   |
| 2011 | 15       | 6.98%   |
| 2017 | 13       | 6.05%   |
| 2007 | 13       | 6.05%   |
| 2008 | 10       | 4.65%   |
| 2016 | 9        | 4.19%   |
| 2010 | 9        | 4.19%   |
| 2021 | 6        | 2.79%   |
| 2009 | 6        | 2.79%   |
| 2015 | 4        | 1.86%   |
| 2022 | 3        | 1.4%    |
| 2006 | 1        | 0.47%   |
| 2005 | 1        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 215      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 212      | 98.15%  |
| Enabled  | 4        | 1.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 215      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 54       | 24.77%  |
| 16.01-24.0  | 44       | 20.18%  |
| 4.01-8.0    | 34       | 15.6%   |
| 3.01-4.0    | 34       | 15.6%   |
| 32.01-64.0  | 31       | 14.22%  |
| 1.01-2.0    | 11       | 5.05%   |
| 24.01-32.0  | 5        | 2.29%   |
| 2.01-3.0    | 3        | 1.38%   |
| 64.01-256.0 | 2        | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 87       | 36.71%  |
| 2.01-3.0   | 65       | 27.43%  |
| 3.01-4.0   | 33       | 13.92%  |
| 4.01-8.0   | 32       | 13.5%   |
| 8.01-16.0  | 12       | 5.06%   |
| 0.51-1.0   | 5        | 2.11%   |
| 0.01-0.5   | 2        | 0.84%   |
| 16.01-24.0 | 1        | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 85       | 38.46%  |
| 2      | 70       | 31.67%  |
| 3      | 34       | 15.38%  |
| 4      | 21       | 9.5%    |
| 5      | 6        | 2.71%   |
| 7      | 2        | 0.9%    |
| 0      | 2        | 0.9%    |
| 6      | 1        | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 58.33%  |
| Yes       | 90       | 41.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 213      | 99.07%  |
| No        | 2        | 0.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 53%     |
| Yes       | 102      | 47%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 153      | 69.86%  |
| Yes       | 66       | 30.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Chile   | 215      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Santiago            | 64       | 28.32%  |
| Maipu               | 10       | 4.42%   |
| Las Condes          | 9        | 3.98%   |
| Puente Alto         | 8        | 3.54%   |
| Viña del Mar       | 7        | 3.1%    |
| Nunoa               | 7        | 3.1%    |
| Antofagasta         | 7        | 3.1%    |
| La Florida          | 6        | 2.65%   |
| Valparaíso         | 5        | 2.21%   |
| Valdivia            | 5        | 2.21%   |
| Temuco              | 5        | 2.21%   |
| Providencia         | 5        | 2.21%   |
| Concepción         | 5        | 2.21%   |
| Central             | 5        | 2.21%   |
| Port Montt          | 4        | 1.77%   |
| Osorno              | 4        | 1.77%   |
| San Miguel          | 3        | 1.33%   |
| Quilpué            | 3        | 1.33%   |
| Penalolen           | 3        | 1.33%   |
| La Serena           | 3        | 1.33%   |
| El Bosque           | 3        | 1.33%   |
| Coquimbo            | 3        | 1.33%   |
| Chillan             | 3        | 1.33%   |
| Arica               | 3        | 1.33%   |
| Vitacura            | 2        | 0.88%   |
| Vallenar            | 2        | 0.88%   |
| Tome                | 2        | 0.88%   |
| Talca               | 2        | 0.88%   |
| San Pedro de la Paz | 2        | 0.88%   |
| Recoleta            | 2        | 0.88%   |
| Los Ángeles        | 2        | 0.88%   |
| La Granja           | 2        | 0.88%   |
| Hualpen             | 2        | 0.88%   |
| Coronel             | 2        | 0.88%   |
| Colina              | 2        | 0.88%   |
| Villa Alemana       | 1        | 0.44%   |
| Villa Alegre        | 1        | 0.44%   |
| Talagante           | 1        | 0.44%   |
| San Joaquin         | 1        | 0.44%   |
| San Javier          | 1        | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 87       | 152    | 22.66%  |
| Seagate                   | 75       | 108    | 19.53%  |
| Kingston                  | 44       | 68     | 11.46%  |
| Toshiba                   | 40       | 45     | 10.42%  |
| Crucial                   | 23       | 31     | 5.99%   |
| Samsung Electronics       | 18       | 28     | 4.69%   |
| Hitachi                   | 14       | 18     | 3.65%   |
| SanDisk                   | 10       | 12     | 2.6%    |
| Silicon Motion            | 9        | 9      | 2.34%   |
| China                     | 7        | 10     | 1.82%   |
| Unknown                   | 5        | 6      | 1.3%    |
| XPG                       | 4        | 10     | 1.04%   |
| Corsair                   | 4        | 9      | 1.04%   |
| XrayDisk                  | 3        | 3      | 0.78%   |
| Realtek Semiconductor     | 3        | 3      | 0.78%   |
| Micron Technology         | 3        | 6      | 0.78%   |
| Lexar                     | 3        | 3      | 0.78%   |
| KingSpec                  | 3        | 3      | 0.78%   |
| A-DATA Technology         | 3        | 3      | 0.78%   |
| Micron/Crucial Technology | 2        | 5      | 0.52%   |
| Maxtor                    | 2        | 2      | 0.52%   |
| JMicron Technology        | 2        | 2      | 0.52%   |
| Gigabyte Technology       | 2        | 2      | 0.52%   |
| ZOTAC                     | 1        | 1      | 0.26%   |
| WALRAM                    | 1        | 2      | 0.26%   |
| Transcend                 | 1        | 1      | 0.26%   |
| StoreJet                  | 1        | 1      | 0.26%   |
| SK hynix                  | 1        | 1      | 0.26%   |
| PNY                       | 1        | 1      | 0.26%   |
| Patriot                   | 1        | 1      | 0.26%   |
| OCZ                       | 1        | 2      | 0.26%   |
| NGFF                      | 1        | 1      | 0.26%   |
| Netac                     | 1        | 1      | 0.26%   |
| Mass                      | 1        | 1      | 0.26%   |
| JASTER                    | 1        | 2      | 0.26%   |
| Intenso                   | 1        | 1      | 0.26%   |
| BIWIN                     | 1        | 1      | 0.26%   |
| ASMT                      | 1        | 1      | 0.26%   |
| ASMedia                   | 1        | 2      | 0.26%   |
| Apple                     | 1        | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 14       | 3.17%   |
| Seagate ST500DM002-1BD142 500GB     | 14       | 3.17%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 11       | 2.49%   |
| Toshiba HDWD110 1TB                 | 10       | 2.27%   |
| Kingston SA400S37240G 240GB SSD     | 10       | 2.27%   |
| Kingston SA400S37120G 120GB SSD     | 9        | 2.04%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7        | 1.59%   |
| WDC WD5000AAKX-001CA0 500GB         | 6        | 1.36%   |
| Kingston SA400S37480G 480GB SSD     | 6        | 1.36%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 5        | 1.13%   |
| Seagate ST3500418AS 500GB           | 5        | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB      | 5        | 1.13%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 4        | 0.91%   |
| WDC WD10EZEX-00BN5A0 1TB            | 4        | 0.91%   |
| Toshiba DT01ACA050 500GB            | 4        | 0.91%   |
| Seagate ST3320418AS 320GB           | 4        | 0.91%   |
| SanDisk NVMe SSD Drive 1TB          | 4        | 0.91%   |
| Hitachi HDS721050CLA362 500GB       | 4        | 0.91%   |
| Crucial CT500MX500SSD1 500GB        | 4        | 0.91%   |
| Crucial CT480BX500SSD1 480GB        | 4        | 0.91%   |
| XPG SPECTRIX S40G 4TB               | 3        | 0.68%   |
| XPG GAMMIX S11 Pro 256GB            | 3        | 0.68%   |
| Seagate ST9640320AS 640GB           | 3        | 0.68%   |
| Seagate ST500LT012-9WS142 500GB     | 3        | 0.68%   |
| Seagate ST500LT012-1DG142 500GB     | 3        | 0.68%   |
| SanDisk NVMe SSD Drive 500GB        | 3        | 0.68%   |
| Kingston SUV400S37240G 240GB SSD    | 3        | 0.68%   |
| Hitachi HDS721032CLA362 320GB       | 3        | 0.68%   |
| Crucial CT240BX500SSD1 240GB        | 3        | 0.68%   |
| WDC WDS500G3X0C-00SJG0 500GB        | 2        | 0.45%   |
| WDC WDS240G1G0A-00SS50 240GB SSD    | 2        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2        | 0.45%   |
| WDC WDS100T2B0C-00PXH0 1TB          | 2        | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 2        | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 2        | 0.45%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 0.45%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 2        | 0.45%   |
| WDC WD1003FBYZ-010FB0 1TB           | 2        | 0.45%   |
| Toshiba HDWD105 500GB               | 2        | 0.45%   |
| Silicon Motion NVMe SSD Drive 512GB | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 74       | 107    | 36.27%  |
| WDC                 | 66       | 105    | 32.35%  |
| Toshiba             | 40       | 45     | 19.61%  |
| Hitachi             | 14       | 18     | 6.86%   |
| Samsung Electronics | 4        | 6      | 1.96%   |
| Maxtor              | 2        | 2      | 0.98%   |
| Unknown             | 1        | 1      | 0.49%   |
| ASMT                | 1        | 1      | 0.49%   |
| ASMedia             | 1        | 2      | 0.49%   |
| Apple               | 1        | 1      | 0.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 40       | 53     | 29.63%  |
| WDC                 | 27       | 38     | 20%     |
| Crucial             | 23       | 30     | 17.04%  |
| Samsung Electronics | 10       | 13     | 7.41%   |
| China               | 7        | 10     | 5.19%   |
| Corsair             | 4        | 9      | 2.96%   |
| Lexar               | 3        | 3      | 2.22%   |
| KingSpec            | 3        | 3      | 2.22%   |
| XrayDisk            | 2        | 2      | 1.48%   |
| Micron Technology   | 2        | 2      | 1.48%   |
| Gigabyte Technology | 2        | 2      | 1.48%   |
| ZOTAC               | 1        | 1      | 0.74%   |
| WALRAM              | 1        | 1      | 0.74%   |
| StoreJet            | 1        | 1      | 0.74%   |
| PNY                 | 1        | 1      | 0.74%   |
| Patriot             | 1        | 1      | 0.74%   |
| OCZ                 | 1        | 2      | 0.74%   |
| NGFF                | 1        | 1      | 0.74%   |
| JMicron Technology  | 1        | 1      | 0.74%   |
| Intenso             | 1        | 1      | 0.74%   |
| BIWIN               | 1        | 1      | 0.74%   |
| A-DATA Technology   | 1        | 1      | 0.74%   |
| Unknown             | 1        | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 153      | 288    | 47.22%  |
| SSD     | 112      | 178    | 34.57%  |
| NVMe    | 49       | 83     | 15.12%  |
| Unknown | 8        | 9      | 2.47%   |
| MMC     | 2        | 2      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 203      | 457    | 76.32%  |
| NVMe | 49       | 83     | 18.42%  |
| SAS  | 12       | 18     | 4.51%   |
| MMC  | 2        | 2      | 0.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 165      | 300    | 60.44%  |
| 0.51-1.0   | 71       | 108    | 26.01%  |
| 1.01-2.0   | 23       | 33     | 8.42%   |
| 2.01-3.0   | 6        | 14     | 2.2%    |
| 3.01-4.0   | 5        | 6      | 1.83%   |
| 4.01-10.0  | 3        | 5      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 53       | 23.04%  |
| 101-250        | 45       | 19.57%  |
| 501-1000       | 33       | 14.35%  |
| 1001-2000      | 23       | 10%     |
| More than 3000 | 19       | 8.26%   |
| 1-20           | 18       | 7.83%   |
| 2001-3000      | 13       | 5.65%   |
| 51-100         | 13       | 5.65%   |
| Unknown        | 7        | 3.04%   |
| 21-50          | 6        | 2.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 85       | 36.02%  |
| 21-50          | 44       | 18.64%  |
| 101-250        | 23       | 9.75%   |
| 501-1000       | 19       | 8.05%   |
| 51-100         | 18       | 7.63%   |
| 1001-2000      | 17       | 7.2%    |
| 251-500        | 12       | 5.08%   |
| More than 3000 | 8        | 3.39%   |
| Unknown        | 7        | 2.97%   |
| 2001-3000      | 3        | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 2        | 2      | 6.9%    |
| Kingston SA400S37240G 240GB SSD      | 2        | 2      | 6.9%    |
| XrayDisk SSD 256GB                   | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-083CA1 500GB          | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1        | 1      | 3.45%   |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 2      | 3.45%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1      | 3.45%   |
| WDC WD1600BB-00GUC0 160GB            | 1        | 1      | 3.45%   |
| WDC WD10EARS-003BB1 1TB              | 1        | 1      | 3.45%   |
| Toshiba MK1652GSX 160GB              | 1        | 1      | 3.45%   |
| Toshiba DT01ACA100 1TB               | 1        | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB      | 1        | 1      | 3.45%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 1      | 3.45%   |
| Seagate ST3500418AS 500GB            | 1        | 1      | 3.45%   |
| Seagate ST31000528AS 1TB             | 1        | 1      | 3.45%   |
| Samsung Electronics SSD 870 EVO 1TB  | 1        | 1      | 3.45%   |
| Samsung Electronics HD250HJ 250GB    | 1        | 2      | 3.45%   |
| Samsung Electronics HD081GJ 80GB     | 1        | 1      | 3.45%   |
| Kingston SKC400S371T 1TB SSD         | 1        | 4      | 3.45%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 1      | 3.45%   |
| Kingston SA400S37120G 120GB SSD      | 1        | 1      | 3.45%   |
| Hitachi HTS547550A9E384 500GB        | 1        | 1      | 3.45%   |
| Hitachi HTS545050B9A300 500GB        | 1        | 1      | 3.45%   |
| Hitachi HTS545050A7E380 500GB        | 1        | 1      | 3.45%   |
| Hitachi HDS721050CLA660 500GB        | 1        | 1      | 3.45%   |
| Hitachi HDS721032CLA362 320GB        | 1        | 1      | 3.45%   |
| A-DATA Technology SX8100NP 1TB       | 1        | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 22.22%  |
| Seagate             | 6        | 6      | 22.22%  |
| Kingston            | 5        | 8      | 18.52%  |
| Hitachi             | 4        | 5      | 14.81%  |
| Toshiba             | 2        | 2      | 7.41%   |
| Samsung Electronics | 2        | 4      | 7.41%   |
| XrayDisk            | 1        | 1      | 3.7%    |
| A-DATA Technology   | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 31.58%  |
| Seagate             | 6        | 6      | 31.58%  |
| Hitachi             | 4        | 5      | 21.05%  |
| Toshiba             | 2        | 2      | 10.53%  |
| Samsung Electronics | 1        | 3      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 23     | 66.67%  |
| SSD  | 7        | 10     | 29.17%  |
| NVMe | 1        | 1      | 4.17%   |

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
| Detected | 147      | 362    | 61%     |
| Works    | 70       | 163    | 29.05%  |
| Malfunc  | 23       | 34     | 9.54%   |
| Failed   | 1        | 1      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 122      | 42.81%  |
| AMD                          | 84       | 29.47%  |
| SanDisk                      | 15       | 5.26%   |
| Silicon Motion               | 11       | 3.86%   |
| Realtek Semiconductor        | 8        | 2.81%   |
| JMicron Technology           | 8        | 2.81%   |
| Marvell Technology Group     | 7        | 2.46%   |
| Samsung Electronics          | 5        | 1.75%   |
| Nvidia                       | 5        | 1.75%   |
| Kingston Technology Company  | 5        | 1.75%   |
| ASMedia Technology           | 5        | 1.75%   |
| Micron/Crucial Technology    | 3        | 1.05%   |
| ADATA Technology             | 3        | 1.05%   |
| VIA Technologies             | 1        | 0.35%   |
| SK hynix                     | 1        | 0.35%   |
| Shenzhen Longsys Electronics | 1        | 0.35%   |
| Micron Technology            | 1        | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 48       | 12.83%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19       | 5.08%   |
| AMD 400 Series Chipset SATA Controller                                                  | 18       | 4.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 3.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12       | 3.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 2.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 10       | 2.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.14%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 7        | 1.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.87%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 1.87%   |
| AMD FCH SATA Controller D                                                               | 7        | 1.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6        | 1.6%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.6%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 6        | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.6%    |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 1.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.34%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.07%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.07%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 4        | 1.07%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.07%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 1.07%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 3        | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 0.8%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.8%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.8%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.8%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 170      | 60.07%  |
| IDE  | 58       | 20.49%  |
| NVMe | 49       | 17.31%  |
| RAID | 6        | 2.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 126      | 58.6%   |
| AMD    | 89       | 41.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor                | 5        | 2.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 1.82%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 4        | 1.82%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 4        | 1.82%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4        | 1.82%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4        | 1.82%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4        | 1.82%   |
| AMD FX-8350 Eight-Core Processor              | 4        | 1.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 3        | 1.36%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3        | 1.36%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3        | 1.36%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3        | 1.36%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3        | 1.36%   |
| AMD E-450 APU with Radeon HD Graphics         | 3        | 1.36%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 3        | 1.36%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 2        | 0.91%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz            | 2        | 0.91%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 2        | 0.91%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz           | 2        | 0.91%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 2        | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2        | 0.91%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 2        | 0.91%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2        | 0.91%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2        | 0.91%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2        | 0.91%   |
| Intel Core i5-4250U CPU @ 1.30GHz             | 2        | 0.91%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 2        | 0.91%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 2        | 0.91%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2        | 0.91%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2        | 0.91%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 2        | 0.91%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 2        | 0.91%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 2        | 0.91%   |
| AMD Ryzen 9 3900XT 12-Core Processor          | 2        | 0.91%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2        | 0.91%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2        | 0.91%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2        | 0.91%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 2        | 0.91%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2        | 0.91%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2        | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 14.16%  |
| Intel Core i7           | 22       | 10.05%  |
| Intel Xeon              | 21       | 9.59%   |
| AMD Ryzen 5             | 20       | 9.13%   |
| Intel Core i3           | 16       | 7.31%   |
| AMD FX                  | 12       | 5.48%   |
| AMD Ryzen 7             | 11       | 5.02%   |
| Intel Core 2 Duo        | 10       | 4.57%   |
| Intel Celeron           | 8        | 3.65%   |
| AMD Ryzen 3             | 8        | 3.65%   |
| AMD A6                  | 7        | 3.2%    |
| Intel Pentium           | 5        | 2.28%   |
| AMD Athlon              | 5        | 2.28%   |
| AMD Ryzen 9             | 3        | 1.37%   |
| AMD Phenom              | 3        | 1.37%   |
| AMD E                   | 3        | 1.37%   |
| AMD Athlon II X2        | 3        | 1.37%   |
| Intel Pentium Dual-Core | 2        | 0.91%   |
| Intel Pentium Dual      | 2        | 0.91%   |
| Intel Pentium 4         | 2        | 0.91%   |
| Intel Core 2 Quad       | 2        | 0.91%   |
| Intel Core 2            | 2        | 0.91%   |
| Intel Atom              | 2        | 0.91%   |
| AMD Phenom II X6        | 2        | 0.91%   |
| AMD Phenom II X4        | 2        | 0.91%   |
| AMD Athlon 64 X2        | 2        | 0.91%   |
| AMD A8                  | 2        | 0.91%   |
| AMD A10                 | 2        | 0.91%   |
| Intel Xeon Bronze       | 1        | 0.46%   |
| Intel Pentium Gold      | 1        | 0.46%   |
| Intel Core i9           | 1        | 0.46%   |
| AMD Ryzen Threadripper  | 1        | 0.46%   |
| AMD Ryzen 5 PRO         | 1        | 0.46%   |
| AMD Athlon X4           | 1        | 0.46%   |
| AMD Athlon II X4        | 1        | 0.46%   |
| AMD Athlon II           | 1        | 0.46%   |
| AMD A4                  | 1        | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 80       | 36.36%  |
| 2       | 62       | 28.18%  |
| 6       | 29       | 13.18%  |
| 8       | 21       | 9.55%   |
| 3       | 8        | 3.64%   |
| 1       | 8        | 3.64%   |
| 12      | 6        | 2.73%   |
| 10      | 3        | 1.36%   |
| 16      | 2        | 0.91%   |
| Unknown | 1        | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 213      | 99.07%  |
| 2      | 2        | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 123      | 56.94%  |
| 1       | 92       | 42.59%  |
| Unknown | 1        | 0.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 209      | 97.21%  |
| Unknown        | 4        | 1.86%   |
| 64-bit         | 1        | 0.47%   |
| 32-bit         | 1        | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 58       | 25.33%  |
| 0x306c3    | 16       | 6.99%   |
| 0x306a9    | 10       | 4.37%   |
| 0x08701021 | 10       | 4.37%   |
| 0x206a7    | 9        | 3.93%   |
| 0x08108109 | 9        | 3.93%   |
| 0x06000852 | 7        | 3.06%   |
| 0x1067a    | 6        | 2.62%   |
| 0xa0653    | 5        | 2.18%   |
| 0x906e9    | 5        | 2.18%   |
| 0x10676    | 5        | 2.18%   |
| 0x906ea    | 4        | 1.75%   |
| 0x6fd      | 4        | 1.75%   |
| 0x306f2    | 4        | 1.75%   |
| 0x0800820d | 4        | 1.75%   |
| 0x03000027 | 4        | 1.75%   |
| 0x6fb      | 3        | 1.31%   |
| 0x506e3    | 3        | 1.31%   |
| 0x306e4    | 3        | 1.31%   |
| 0x206d7    | 3        | 1.31%   |
| 0x08108102 | 3        | 1.31%   |
| 0x06001119 | 3        | 1.31%   |
| 0x0600063e | 3        | 1.31%   |
| 0x010000c8 | 3        | 1.31%   |
| 0x40651    | 2        | 0.87%   |
| 0x30678    | 2        | 0.87%   |
| 0x106a5    | 2        | 0.87%   |
| 0x08701013 | 2        | 0.87%   |
| 0x08101016 | 2        | 0.87%   |
| 0x08001138 | 2        | 0.87%   |
| 0x06003106 | 2        | 0.87%   |
| 0x05000119 | 2        | 0.87%   |
| 0x010000bf | 2        | 0.87%   |
| 0x01000095 | 2        | 0.87%   |
| 0xf65      | 1        | 0.44%   |
| 0xf41      | 1        | 0.44%   |
| 0xa0655    | 1        | 0.44%   |
| 0x906ed    | 1        | 0.44%   |
| 0x906eb    | 1        | 0.44%   |
| 0x706a1    | 1        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 29       | 13.3%   |
| IvyBridge     | 18       | 8.26%   |
| Zen+          | 16       | 7.34%   |
| KabyLake      | 16       | 7.34%   |
| Penryn        | 15       | 6.88%   |
| Zen 2         | 14       | 6.42%   |
| Piledriver    | 14       | 6.42%   |
| SandyBridge   | 13       | 5.96%   |
| K10           | 12       | 5.5%    |
| Zen           | 11       | 5.05%   |
| Core          | 9        | 4.13%   |
| CometLake     | 8        | 3.67%   |
| Zen 3         | 7        | 3.21%   |
| Skylake       | 5        | 2.29%   |
| Silvermont    | 4        | 1.83%   |
| K10 Llano     | 4        | 1.83%   |
| Steamroller   | 3        | 1.38%   |
| Nehalem       | 3        | 1.38%   |
| Bulldozer     | 3        | 1.38%   |
| Bobcat        | 3        | 1.38%   |
| Westmere      | 2        | 0.92%   |
| NetBurst      | 2        | 0.92%   |
| K8 Hammer     | 2        | 0.92%   |
| Jaguar        | 1        | 0.46%   |
| Goldmont plus | 1        | 0.46%   |
| Excavator     | 1        | 0.46%   |
| Broadwell     | 1        | 0.46%   |
| Bonnell       | 1        | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 88       | 38.26%  |
| Nvidia                     | 78       | 33.91%  |
| Intel                      | 61       | 26.52%  |
| VIA Technologies           | 1        | 0.43%   |
| Matrox Electronics Systems | 1        | 0.43%   |
| ATI Technologies           | 1        | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 5.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9        | 3.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 3.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 2.94%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 2.52%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 2.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 2.1%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5        | 2.1%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 2.1%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 5        | 2.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.68%   |
| Intel HD Graphics 530                                                       | 4        | 1.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 1.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.68%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 1.26%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.26%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3        | 1.26%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.26%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.26%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 1.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.26%   |
| AMD Wrestler [Radeon HD 6320]                                               | 3        | 1.26%   |
| AMD Sumo [Radeon HD 6530D]                                                  | 3        | 1.26%   |
| AMD RS780L [Radeon 3000]                                                    | 3        | 1.26%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 3        | 1.26%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.26%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.84%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.84%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.84%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 0.84%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.84%   |
| Nvidia GF106GL [Quadro 2000]                                                | 2        | 0.84%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2        | 0.84%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 0.84%   |
| Intel HD Graphics 630                                                       | 2        | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 75       | 34.56%  |
| 1 x Nvidia   | 73       | 33.64%  |
| 1 x Intel    | 55       | 25.35%  |
| AMD + Nvidia | 6        | 2.76%   |
| 2 x AMD      | 5        | 2.3%    |
| 1 x VIA      | 1        | 0.46%   |
| 1 x Matrox   | 1        | 0.46%   |
| Intel + AMD  | 1        | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 163      | 75.12%  |
| Proprietary | 47       | 21.66%  |
| Unknown     | 7        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 96       | 43.44%  |
| 1.01-2.0   | 39       | 17.65%  |
| 0.51-1.0   | 24       | 10.86%  |
| 0.01-0.5   | 20       | 9.05%   |
| 3.01-4.0   | 17       | 7.69%   |
| 7.01-8.0   | 7        | 3.17%   |
| 5.01-6.0   | 7        | 3.17%   |
| 8.01-16.0  | 7        | 3.17%   |
| 2.01-3.0   | 4        | 1.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 50       | 22.73%  |
| Goldstar             | 41       | 18.64%  |
| Hewlett-Packard      | 22       | 10%     |
| Dell                 | 13       | 5.91%   |
| LG Electronics       | 12       | 5.45%   |
| AOC                  | 12       | 5.45%   |
| Lenovo               | 9        | 4.09%   |
| Unknown              | 6        | 2.73%   |
| ViewSonic            | 5        | 2.27%   |
| Sony                 | 5        | 2.27%   |
| ___                  | 4        | 1.82%   |
| SAC                  | 4        | 1.82%   |
| Plain Tree Systems   | 3        | 1.36%   |
| Packard Bell         | 3        | 1.36%   |
| KTC                  | 3        | 1.36%   |
| Envision             | 3        | 1.36%   |
| Acer                 | 3        | 1.36%   |
| Philips              | 2        | 0.91%   |
| MSI                  | 2        | 0.91%   |
| Hitachi              | 2        | 0.91%   |
| CHR                  | 2        | 0.91%   |
| Ancor Communications | 2        | 0.91%   |
| Westinghouse         | 1        | 0.45%   |
| Wacom                | 1        | 0.45%   |
| Unknown (XXX)        | 1        | 0.45%   |
| SKY                  | 1        | 0.45%   |
| Sharp                | 1        | 0.45%   |
| NCS                  | 1        | 0.45%   |
| Mi                   | 1        | 0.45%   |
| HKC                  | 1        | 0.45%   |
| GDH                  | 1        | 0.45%   |
| BenQ                 | 1        | 0.45%   |
| ASUSTek Computer     | 1        | 0.45%   |
| Unknown              | 1        | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 7        | 3%      |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 6        | 2.58%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 5        | 2.15%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 4        | 1.72%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 3        | 1.29%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                   | 3        | 1.29%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                      | 3        | 1.29%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                  | 3        | 1.29%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                | 3        | 1.29%   |
| ___ LCDTV16 ___0101 1360x768                                            | 2        | 0.86%   |
| ___ LCD TV ___9000 1360x768                                             | 2        | 0.86%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                    | 2        | 0.86%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 2        | 0.86%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                      | 2        | 0.86%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.86%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 2        | 0.86%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.86%   |
| Philips 190P PHL0831 1280x1024 376x301mm 19.0-inch                      | 2        | 0.86%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                  | 2        | 0.86%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                             | 2        | 0.86%   |
| Lenovo LEN S22e-19 LEN61C9 1920x1080 476x268mm 21.5-inch                | 2        | 0.86%   |
| Hewlett-Packard TouchSmart HWP4211 1920x1080 509x286mm 23.0-inch        | 2        | 0.86%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                     | 2        | 0.86%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 2        | 0.86%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                     | 2        | 0.86%   |
| CHR CH7511B CHR7511 1024x768 518x333mm 24.2-inch                        | 2        | 0.86%   |
| AOC LE24H037 AOC2407 1920x1080 521x293mm 23.5-inch                      | 2        | 0.86%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                          | 2        | 0.86%   |
| Westinghouse LCM-19v5 WDE1905 1280x1024 376x301mm 19.0-inch             | 1        | 0.43%   |
| Wacom Cintiq 21UX 2 WAC1022 1600x1200 432x324mm 21.3-inch               | 1        | 0.43%   |
| ViewSonic VX2253 Series VSC0A28 1920x1080 476x268mm 21.5-inch           | 1        | 0.43%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch                | 1        | 0.43%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch           | 1        | 0.43%   |
| ViewSonic VA1926wSERIES VSC5920 1440x900 410x256mm 19.0-inch            | 1        | 0.43%   |
| ViewSonic LCD Monitor VX2370 SERIES 1920x1080                           | 1        | 0.43%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch          | 1        | 0.43%   |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                            | 1        | 0.43%   |
| Sony TV SNY4302 1920x1080                                               | 1        | 0.43%   |
| Sony TV SNY3002 1920x1080 708x398mm 32.0-inch                           | 1        | 0.43%   |
| Sony TV SNY1503 1360x768                                                | 1        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 85       | 40.48%  |
| 3840x2160 (4K)     | 18       | 8.57%   |
| 1366x768 (WXGA)    | 18       | 8.57%   |
| 1360x768           | 17       | 8.1%    |
| 1440x900 (WXGA+)   | 14       | 6.67%   |
| 1600x900 (HD+)     | 10       | 4.76%   |
| 1280x1024 (SXGA)   | 10       | 4.76%   |
| 2560x1080          | 8        | 3.81%   |
| 2560x1440 (QHD)    | 6        | 2.86%   |
| Unknown            | 5        | 2.38%   |
| 1680x1050 (WSXGA+) | 4        | 1.9%    |
| 3840x1080          | 3        | 1.43%   |
| 3440x1440          | 3        | 1.43%   |
| 1024x768 (XGA)     | 3        | 1.43%   |
| 5760x1080          | 1        | 0.48%   |
| 3840x1600          | 1        | 0.48%   |
| 3286x1080          | 1        | 0.48%   |
| 1600x1200          | 1        | 0.48%   |
| 1280x960           | 1        | 0.48%   |
| 1280x768           | 1        | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 35       | 16.2%   |
| 23      | 30       | 13.89%  |
| Unknown | 25       | 11.57%  |
| 18      | 18       | 8.33%   |
| 24      | 13       | 6.02%   |
| 19      | 13       | 6.02%   |
| 34      | 11       | 5.09%   |
| 27      | 9        | 4.17%   |
| 20      | 9        | 4.17%   |
| 17      | 8        | 3.7%    |
| 15      | 7        | 3.24%   |
| 84      | 6        | 2.78%   |
| 72      | 6        | 2.78%   |
| 32      | 6        | 2.78%   |
| 31      | 6        | 2.78%   |
| 54      | 3        | 1.39%   |
| 40      | 3        | 1.39%   |
| 22      | 2        | 0.93%   |
| 65      | 1        | 0.46%   |
| 52      | 1        | 0.46%   |
| 37      | 1        | 0.46%   |
| 28      | 1        | 0.46%   |
| 14      | 1        | 0.46%   |
| 13      | 1        | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 66       | 31.88%  |
| 501-600     | 47       | 22.71%  |
| Unknown     | 25       | 12.08%  |
| 701-800     | 17       | 8.21%   |
| 301-350     | 13       | 6.28%   |
| 1501-2000   | 12       | 5.8%    |
| 601-700     | 9        | 4.35%   |
| 351-400     | 7        | 3.38%   |
| 1001-1500   | 5        | 2.42%   |
| 801-900     | 4        | 1.93%   |
| 201-300     | 2        | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 131      | 66.5%   |
| Unknown | 21       | 10.66%  |
| 16/10   | 18       | 9.14%   |
| 5/4     | 11       | 5.58%   |
| 21/9    | 11       | 5.58%   |
| 4/3     | 5        | 2.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 68       | 32.23%  |
| 151-200        | 28       | 13.27%  |
| Unknown        | 25       | 11.85%  |
| 351-500        | 24       | 11.37%  |
| 141-150        | 21       | 9.95%   |
| More than 1000 | 17       | 8.06%   |
| 301-350        | 9        | 4.27%   |
| 101-110        | 8        | 3.79%   |
| 251-300        | 4        | 1.9%    |
| 501-1000       | 4        | 1.9%    |
| 131-140        | 2        | 0.95%   |
| 91-100         | 1        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 114      | 55.61%  |
| 101-120 | 42       | 20.49%  |
| Unknown | 25       | 12.2%   |
| 1-50    | 19       | 9.27%   |
| 121-160 | 4        | 1.95%   |
| 161-240 | 1        | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 165      | 75.34%  |
| 2     | 36       | 16.44%  |
| 0     | 13       | 5.94%   |
| 3     | 5        | 2.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 155      | 48.29%  |
| Intel                           | 56       | 17.45%  |
| Qualcomm Atheros                | 17       | 5.3%    |
| Ralink Technology               | 14       | 4.36%   |
| Ralink                          | 12       | 3.74%   |
| TP-Link                         | 9        | 2.8%    |
| Broadcom                        | 9        | 2.8%    |
| Xiaomi                          | 8        | 2.49%   |
| Broadcom Limited                | 6        | 1.87%   |
| Nvidia                          | 4        | 1.25%   |
| D-Link System                   | 4        | 1.25%   |
| Qualcomm Atheros Communications | 3        | 0.93%   |
| Marvell Technology Group        | 3        | 0.93%   |
| Huawei Technologies             | 3        | 0.93%   |
| D-Link                          | 3        | 0.93%   |
| VIA Technologies                | 2        | 0.62%   |
| Samsung Electronics             | 2        | 0.62%   |
| Motorola PCS                    | 2        | 0.62%   |
| Microsoft                       | 2        | 0.62%   |
| Spreadtrum Communications       | 1        | 0.31%   |
| Padix (Rockfire)                | 1        | 0.31%   |
| Oculus VR                       | 1        | 0.31%   |
| Mercucys                        | 1        | 0.31%   |
| Manta                           | 1        | 0.31%   |
| ICS Advent                      | 1        | 0.31%   |
| HMD Global                      | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 130      | 36.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 2.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 2.22%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 1.94%   |
| Intel I211 Gigabit Network Connection                             | 7        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.67%   |
| Intel Wireless 7260                                               | 6        | 1.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.39%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.39%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4        | 1.11%   |
| Realtek 802.11ac NIC                                              | 4        | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 1.11%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 4        | 1.11%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 4        | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.83%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 0.83%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.83%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.83%   |
| Huawei ANA-NX9                                                    | 3        | 0.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.56%   |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 0.56%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 2        | 0.56%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.56%   |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.56%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2        | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 28       | 24.56%  |
| Intel                           | 26       | 22.81%  |
| Ralink Technology               | 14       | 12.28%  |
| Ralink                          | 12       | 10.53%  |
| TP-Link                         | 9        | 7.89%   |
| Qualcomm Atheros                | 8        | 7.02%   |
| Qualcomm Atheros Communications | 3        | 2.63%   |
| D-Link                          | 3        | 2.63%   |
| Broadcom Limited                | 3        | 2.63%   |
| Broadcom                        | 3        | 2.63%   |
| Microsoft                       | 2        | 1.75%   |
| D-Link System                   | 2        | 1.75%   |
| Mercucys                        | 1        | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                      | 7        | 6.14%   |
| Intel Wireless 7260                                                  | 6        | 5.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 5        | 4.39%   |
| Intel Wi-Fi 6 AX200                                                  | 5        | 4.39%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 4        | 3.51%   |
| Realtek 802.11ac NIC                                                 | 4        | 3.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 4        | 3.51%   |
| Ralink RT5392 PCIe Wireless Network Adapter                          | 4        | 3.51%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 4        | 3.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3        | 2.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 3        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3        | 2.63%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2        | 1.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 1.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 2        | 1.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 2        | 1.75%   |
| Realtek RTL8187 Wireless Adapter                                     | 2        | 1.75%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 2        | 1.75%   |
| Ralink RT5370 Wireless Adapter                                       | 2        | 1.75%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 1.75%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2        | 1.75%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 2        | 1.75%   |
| Intel Wireless-AC 9260                                               | 2        | 1.75%   |
| Intel Wireless 8260                                                  | 2        | 1.75%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 2        | 1.75%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 1        | 0.88%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.88%   |
| TP-Link 802.11ac WLAN Adapter                                        | 1        | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1        | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1        | 0.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.88%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1        | 0.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.88%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1        | 0.88%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                            | 1        | 0.88%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 148      | 62.71%  |
| Intel                     | 41       | 17.37%  |
| Qualcomm Atheros          | 10       | 4.24%   |
| Xiaomi                    | 8        | 3.39%   |
| Broadcom                  | 6        | 2.54%   |
| Nvidia                    | 4        | 1.69%   |
| Marvell Technology Group  | 3        | 1.27%   |
| Huawei Technologies       | 3        | 1.27%   |
| Broadcom Limited          | 3        | 1.27%   |
| VIA Technologies          | 2        | 0.85%   |
| Samsung Electronics       | 2        | 0.85%   |
| D-Link System             | 2        | 0.85%   |
| Spreadtrum Communications | 1        | 0.42%   |
| Motorola PCS              | 1        | 0.42%   |
| ICS Advent                | 1        | 0.42%   |
| HMD Global                | 1        | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 130      | 53.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 4.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8        | 3.31%   |
| Intel I211 Gigabit Network Connection                             | 7        | 2.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.48%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.07%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.24%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.24%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.24%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.24%   |
| Huawei ANA-NX9                                                    | 3        | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.83%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 2        | 0.83%   |
| Intel Ethernet Connection I218-V                                  | 2        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.83%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.83%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.83%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 0.83%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 2        | 0.83%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.41%   |
| Spreadtrum Nokia G21                                              | 1        | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.41%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.41%   |
| Motorola PCS moto g pure                                          | 1        | 0.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.41%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 213      | 66.77%  |
| WiFi     | 102      | 31.97%  |
| Unknown  | 3        | 0.94%   |
| Modem    | 1        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 161      | 74.54%  |
| WiFi     | 55       | 25.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 143      | 65.6%   |
| 2     | 63       | 28.9%   |
| 3     | 10       | 4.59%   |
| 4     | 1        | 0.46%   |
| 0     | 1        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 201      | 91.36%  |
| Yes  | 19       | 8.64%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 23       | 33.82%  |
| Cambridge Silicon Radio         | 22       | 32.35%  |
| Realtek Semiconductor           | 12       | 17.65%  |
| Broadcom                        | 7        | 10.29%  |
| Qualcomm Atheros Communications | 2        | 2.94%   |
| ASUSTek Computer                | 1        | 1.47%   |
| Apple                           | 1        | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22       | 32.35%  |
| Realtek Bluetooth Radio                             | 10       | 14.71%  |
| Intel Bluetooth wireless interface                  | 8        | 11.76%  |
| Intel AX210 Bluetooth                               | 5        | 7.35%   |
| Intel AX200 Bluetooth                               | 5        | 7.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 4.41%   |
| Broadcom Bluetooth 3.0 Dongle                       | 3        | 4.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2        | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 1.47%   |
| Broadcom HP Bluetooth Module                        | 1        | 1.47%   |
| Broadcom HP Bluethunder                             | 1        | 1.47%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 1.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.47%   |
| ASUS BCM20702A0                                     | 1        | 1.47%   |
| Apple Bluetooth HCI                                 | 1        | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 118      | 33.43%  |
| AMD                        | 110      | 31.16%  |
| Nvidia                     | 72       | 20.4%   |
| C-Media Electronics        | 8        | 2.27%   |
| Creative Labs              | 7        | 1.98%   |
| Razer USA                  | 4        | 1.13%   |
| Logitech                   | 3        | 0.85%   |
| VIA Technologies           | 2        | 0.57%   |
| Texas Instruments          | 2        | 0.57%   |
| Kingston Technology        | 2        | 0.57%   |
| JMTek                      | 2        | 0.57%   |
| Generalplus Technology     | 2        | 0.57%   |
| Creative Technology        | 2        | 0.57%   |
| Corsair                    | 2        | 0.57%   |
| Arturia                    | 2        | 0.57%   |
| Unknown                    | 1        | 0.28%   |
| Trust                      | 1        | 0.28%   |
| Synaptics                  | 1        | 0.28%   |
| Realtek Semiconductor      | 1        | 0.28%   |
| PreSonus Audio Electronics | 1        | 0.28%   |
| Native Instruments         | 1        | 0.28%   |
| Micro Star International   | 1        | 0.28%   |
| Hewlett-Packard            | 1        | 0.28%   |
| GYROCOM C&C                | 1        | 0.28%   |
| Focusrite-Novation         | 1        | 0.28%   |
| eMPIA Technology           | 1        | 0.28%   |
| Blue Microphones           | 1        | 0.28%   |
| ATI Technologies           | 1        | 0.28%   |
| Apple                      | 1        | 0.28%   |
| Afatech                    | 1        | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 23       | 5.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 21       | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                            | 20       | 4.65%   |
| AMD Starship/Matisse HD Audio Controller                                          | 19       | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 14       | 3.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13       | 3.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 13       | 3.02%   |
| AMD FCH Azalia Controller                                                         | 13       | 3.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 2.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9        | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 9        | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9        | 2.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 1.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 1.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7        | 1.63%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 7        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 1.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 7        | 1.63%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 1.4%    |
| Intel 200 Series PCH HD Audio                                                     | 6        | 1.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6        | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                                     | 5        | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.16%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5        | 1.16%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4        | 0.93%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 0.93%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 0.93%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.7%    |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                                     | 3        | 0.7%    |
| Intel Haswell-ULT HD Audio Controller                                             | 3        | 0.7%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3        | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 22.02%  |
| Crucial             | 19       | 17.43%  |
| Unknown             | 13       | 11.93%  |
| Samsung Electronics | 12       | 11.01%  |
| Corsair             | 12       | 11.01%  |
| SK hynix            | 5        | 4.59%   |
| Micron Technology   | 4        | 3.67%   |
| G.Skill             | 4        | 3.67%   |
| A-DATA Technology   | 4        | 3.67%   |
| Patriot             | 3        | 2.75%   |
| Team                | 1        | 0.92%   |
| Nanya Technology    | 1        | 0.92%   |
| Kreton              | 1        | 0.92%   |
| Hikvision           | 1        | 0.92%   |
| Goldenmars          | 1        | 0.92%   |
| GLOWAY              | 1        | 0.92%   |
| Elpida              | 1        | 0.92%   |
| Atermiter           | 1        | 0.92%   |
| Ankowall            | 1        | 0.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s      | 3        | 2.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 2.46%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 2.46%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 2        | 1.64%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 2        | 1.64%   |
| Kingston RAM KHX3466C17D4/16GX 16GB DIMM DDR4 3466MT/s   | 2        | 1.64%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4GB DIMM DDR4 2666MT/s     | 2        | 1.64%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s     | 2        | 1.64%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.82%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.82%   |
| Unknown RAM Module 8192MB DIMM DDR3                      | 1        | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 0.82%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.82%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 0.82%   |
| Unknown RAM Module 2GB DIMM                              | 1        | 0.82%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.82%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                  | 1        | 0.82%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s       | 1        | 0.82%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s          | 1        | 0.82%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s            | 1        | 0.82%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB DIMM SDRAM 2048MT/s | 1        | 0.82%   |
| SK hynix RAM HMT151R7BFR4C 4096MB DIMM DDR3 1333MT/s     | 1        | 0.82%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s  | 1        | 0.82%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                | 1        | 0.82%   |
| Samsung RAM M471B1G73QHO-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.82%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 1        | 0.82%   |
| Samsung RAM M393B5273CH0-YH9 4GB DIMM DDR3 1333MT/s      | 1        | 0.82%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s          | 1        | 0.82%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1866MT/s         | 1        | 0.82%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.82%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.82%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 0.82%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1        | 0.82%   |
| Micron RAM M471A3243BB0-CP50 16GB SODIMM DDR4 2667MT/s   | 1        | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 1        | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 47       | 48.96%  |
| DDR3    | 36       | 37.5%   |
| DDR2    | 5        | 5.21%   |
| SDRAM   | 4        | 4.17%   |
| Unknown | 3        | 3.13%   |
| DDR     | 1        | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 86       | 90.53%  |
| SODIMM | 9        | 9.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 40.57%  |
| 4096  | 26       | 24.53%  |
| 2048  | 18       | 16.98%  |
| 16384 | 13       | 12.26%  |
| 32768 | 5        | 4.72%   |
| 1024  | 1        | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 21       | 18.75%  |
| 1333    | 14       | 12.5%   |
| 3600    | 8        | 7.14%   |
| 2667    | 8        | 7.14%   |
| 2133    | 8        | 7.14%   |
| 2400    | 6        | 5.36%   |
| 3466    | 5        | 4.46%   |
| 3200    | 5        | 4.46%   |
| 667     | 4        | 3.57%   |
| 3266    | 3        | 2.68%   |
| 2933    | 3        | 2.68%   |
| 2666    | 3        | 2.68%   |
| 1866    | 3        | 2.68%   |
| Unknown | 3        | 2.68%   |
| 3733    | 2        | 1.79%   |
| 3400    | 2        | 1.79%   |
| 1334    | 2        | 1.79%   |
| 1066    | 2        | 1.79%   |
| 800     | 2        | 1.79%   |
| 4000    | 1        | 0.89%   |
| 3800    | 1        | 0.89%   |
| 3666    | 1        | 0.89%   |
| 3134    | 1        | 0.89%   |
| 3000    | 1        | 0.89%   |
| 2800    | 1        | 0.89%   |
| 2048    | 1        | 0.89%   |
| 1067    | 1        | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Seiko Epson         | 3        | 27.27%  |
| Canon               | 3        | 27.27%  |
| Hewlett-Packard     | 2        | 18.18%  |
| Brother Industries  | 2        | 18.18%  |
| QinHeng Electronics | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Brother HL-1200 series     | 2        | 18.18%  |
| Seiko Epson XP-2100 Series | 1        | 9.09%   |
| Seiko Epson Printer        | 1        | 9.09%   |
| Seiko Epson ET-2710 Series | 1        | 9.09%   |
| QinHeng CH340S             | 1        | 9.09%   |
| HP Deskjet 4640 series     | 1        | 9.09%   |
| HP Deskjet 4620 series     | 1        | 9.09%   |
| Canon PIXMA MP250          | 1        | 9.09%   |
| Canon G2000 series         | 1        | 9.09%   |
| Canon G1000 series         | 1        | 9.09%   |

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
| Logitech                      | 8        | 15.09%  |
| Generalplus Technology        | 6        | 11.32%  |
| Chicony Electronics           | 6        | 11.32%  |
| Microdia                      | 5        | 9.43%   |
| Apple                         | 4        | 7.55%   |
| Sunplus Innovation Technology | 3        | 5.66%   |
| Jieli Technology              | 3        | 5.66%   |
| Microsoft                     | 2        | 3.77%   |
| Lenovo                        | 2        | 3.77%   |
| Alcor Micro                   | 2        | 3.77%   |
| Z-Star Microelectronics       | 1        | 1.89%   |
| YGTek                         | 1        | 1.89%   |
| webcam                        | 1        | 1.89%   |
| Unknown                       | 1        | 1.89%   |
| SN0002                        | 1        | 1.89%   |
| Realtek Semiconductor         | 1        | 1.89%   |
| Razer USA                     | 1        | 1.89%   |
| OmniVision Technologies       | 1        | 1.89%   |
| MacroSilicon                  | 1        | 1.89%   |
| KYE Systems (Mouse Systems)   | 1        | 1.89%   |
| AVerMedia Technologies        | 1        | 1.89%   |
| Arkmicro Technologies         | 1        | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Generalplus GENERAL WEBCAM                    | 6        | 11.32%  |
| Logitech C922 Pro Stream Webcam               | 4        | 7.55%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 4        | 7.55%   |
| Jieli USB PHY 2.0                             | 3        | 5.66%   |
| Chicony HP 0.3MP Webcam                       | 3        | 5.66%   |
| Sunplus HD 720P webcam                        | 2        | 3.77%   |
| Microdia Webcam Vitade AF                     | 2        | 3.77%   |
| Microdia USB 2.0 Camera                       | 2        | 3.77%   |
| Z-Star Integrated Camera                      | 1        | 1.89%   |
| YGTek Webcam                                  | 1        | 1.89%   |
| webcam webcam                                 | 1        | 1.89%   |
| Unknown HD camera                             | 1        | 1.89%   |
| Sunplus Aukey-PC-LM1E Camera                  | 1        | 1.89%   |
| SN0002 1080P Web Camera                       | 1        | 1.89%   |
| Realtek NexiGo N960E FHD Webcam               | 1        | 1.89%   |
| Razer USA Razer Kiyo Pro                      | 1        | 1.89%   |
| OmniVision OV511+ Webcam                      | 1        | 1.89%   |
| Microsoft MicrosoftÂ LifeCam Studio          | 1        | 1.89%   |
| Microsoft LifeCam VX-800                      | 1        | 1.89%   |
| Microdia USB camera                           | 1        | 1.89%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 1.89%   |
| Logitech Webcam C270                          | 1        | 1.89%   |
| Logitech Webcam C210                          | 1        | 1.89%   |
| Logitech Webcam C170                          | 1        | 1.89%   |
| Logitech StreamCam                            | 1        | 1.89%   |
| Lenovo FHD Webcam Audio                       | 1        | 1.89%   |
| Lenovo 500 RGB Camera                         | 1        | 1.89%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 1.89%   |
| Chicony HP High Definition 1MP Webcam         | 1        | 1.89%   |
| Chicony HP 1.0MP High Definition Webcam       | 1        | 1.89%   |
| Chicony CNF8050 Webcam                        | 1        | 1.89%   |
| AVerMedia Live Streamer CAM 313               | 1        | 1.89%   |
| Arkmicro USB2.0 PC CAMERA                     | 1        | 1.89%   |
| Alcor Micro USB Video Device                  | 1        | 1.89%   |
| Alcor Micro USB 2.0 PC Camera                 | 1        | 1.89%   |

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
| 0     | 184      | 84.02%  |
| 1     | 30       | 13.7%   |
| 2     | 5        | 2.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 35.14%  |
| Graphics card            | 9        | 24.32%  |
| Unassigned class         | 5        | 13.51%  |
| Sound                    | 2        | 5.41%   |
| Network                  | 2        | 5.41%   |
| Communication controller | 2        | 5.41%   |
| Multimedia controller    | 1        | 2.7%    |
| Firewire controller      | 1        | 2.7%    |
| Camera                   | 1        | 2.7%    |
| Bluetooth                | 1        | 2.7%    |

