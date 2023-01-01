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

Total: 298

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 23       | 11.11%  |
| Ubuntu 18.04      | 19       | 9.18%   |
| Arch              | 10       | 4.83%   |
| Ubuntu 19.04      | 7        | 3.38%   |
| OpenMandriva 4.2  | 7        | 3.38%   |
| OpenMandriva 4.3  | 6        | 2.9%    |
| Manjaro           | 6        | 2.9%    |
| Linux Mint 20.1   | 6        | 2.9%    |
| Zorin 16          | 5        | 2.42%   |
| Zorin 15          | 5        | 2.42%   |
| Pop!_OS 20.10     | 5        | 2.42%   |
| KDE neon 20.04    | 5        | 2.42%   |
| Debian Testing    | 5        | 2.42%   |
| Ubuntu 22.04      | 4        | 1.93%   |
| Ubuntu 21.04      | 4        | 1.93%   |
| Pop!_OS 22.04     | 4        | 1.93%   |
| Fedora 34         | 4        | 1.93%   |
| Arch Rolling      | 4        | 1.93%   |
| Ubuntu 21.10      | 3        | 1.45%   |
| Ubuntu 19.10      | 3        | 1.45%   |
| Linux Mint 20     | 3        | 1.45%   |
| Linux Mint 19.3   | 3        | 1.45%   |
| Kubuntu 20.04     | 3        | 1.45%   |
| Fedora 35         | 3        | 1.45%   |
| Fedora 33         | 3        | 1.45%   |
| Fedora 32         | 3        | 1.45%   |
| Ubuntu 20.10      | 2        | 0.97%   |
| Ubuntu 18.10      | 2        | 0.97%   |
| Ubuntu 16.04      | 2        | 0.97%   |
| Pop!_OS 21.10     | 2        | 0.97%   |
| Pop!_OS 20.04     | 2        | 0.97%   |
| Nobara 36         | 2        | 0.97%   |
| Manjaro 21.0      | 2        | 0.97%   |
| Linux Mint 20.3   | 2        | 0.97%   |
| Linux Mint 20.2   | 2        | 0.97%   |
| Linux Mint 19.2   | 2        | 0.97%   |
| KDE neon 18.04    | 2        | 0.97%   |
| Debian 11         | 2        | 0.97%   |
| ArcoLinux Rolling | 2        | 0.97%   |
| Zorin 12          | 1        | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 69       | 34.85%  |
| Linux Mint       | 18       | 9.09%   |
| Pop!_OS          | 14       | 7.07%   |
| OpenMandriva     | 13       | 6.57%   |
| Fedora           | 13       | 6.57%   |
| Arch             | 13       | 6.57%   |
| Zorin            | 11       | 5.56%   |
| Manjaro          | 9        | 4.55%   |
| KDE neon         | 7        | 3.54%   |
| Debian           | 7        | 3.54%   |
| Kubuntu          | 4        | 2.02%   |
| Ubuntu MATE      | 2        | 1.01%   |
| Nobara           | 2        | 1.01%   |
| ArcoLinux        | 2        | 1.01%   |
| Ubuntu Budgie    | 1        | 0.51%   |
| ROSA             | 1        | 0.51%   |
| org.kde.Platform | 1        | 0.51%   |
| Lubuntu          | 1        | 0.51%   |
| LMDE             | 1        | 0.51%   |
| LinuxFX          | 1        | 0.51%   |
| Linux Lite       | 1        | 0.51%   |
| Kali             | 1        | 0.51%   |
| Gentoo           | 1        | 0.51%   |
| Garuda Linux     | 1        | 0.51%   |
| Endless          | 1        | 0.51%   |
| EndeavourOS      | 1        | 0.51%   |
| Elementary       | 1        | 0.51%   |
| Clear Linux      | 1        | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 6        | 2.63%   |
| 5.16.7-desktop-1omv4003  | 6        | 2.63%   |
| 5.10.14-desktop-1omv4002 | 6        | 2.63%   |
| 5.9.16-1-MANJARO         | 4        | 1.75%   |
| 5.0.0-13-generic         | 4        | 1.75%   |
| 5.4.0-77-generic         | 3        | 1.32%   |
| 5.4.0-33-generic         | 3        | 1.32%   |
| 5.4.0-26-generic         | 3        | 1.32%   |
| 5.11.0-7614-generic      | 3        | 1.32%   |
| 4.18.0-18-generic        | 3        | 1.32%   |
| 5.8.0-59-generic         | 2        | 0.88%   |
| 5.8.0-48-generic         | 2        | 0.88%   |
| 5.4.0-89-generic         | 2        | 0.88%   |
| 5.4.0-74-generic         | 2        | 0.88%   |
| 5.4.0-70-generic         | 2        | 0.88%   |
| 5.4.0-65-generic         | 2        | 0.88%   |
| 5.4.0-52-generic         | 2        | 0.88%   |
| 5.4.0-47-generic         | 2        | 0.88%   |
| 5.4.0-29-generic         | 2        | 0.88%   |
| 5.4.0-124-generic        | 2        | 0.88%   |
| 5.4.0-117-generic        | 2        | 0.88%   |
| 5.3.0-53-generic         | 2        | 0.88%   |
| 5.18.10-76051810-generic | 2        | 0.88%   |
| 5.17.5-76051705-generic  | 2        | 0.88%   |
| 5.13.0-39-generic        | 2        | 0.88%   |
| 5.11.0-41-generic        | 2        | 0.88%   |
| 5.11.0-34-generic        | 2        | 0.88%   |
| 5.11.0-27-generic        | 2        | 0.88%   |
| 5.11.0-18-generic        | 2        | 0.88%   |
| 4.18.0-20-generic        | 2        | 0.88%   |
| 4.18.0-17-generic        | 2        | 0.88%   |
| 4.18.0-15-generic        | 2        | 0.88%   |
| 4.15.0-43-generic        | 2        | 0.88%   |
| 4.15.0-112-generic       | 2        | 0.88%   |
| 6.0.6-76060006-generic   | 1        | 0.44%   |
| 6.0.0-9.1-liquorix-amd64 | 1        | 0.44%   |
| 5.9.8-arch1-1            | 1        | 0.44%   |
| 5.9.16-200.fc33.x86_64   | 1        | 0.44%   |
| 5.9.1-050901-lowlatency  | 1        | 0.44%   |
| 5.8.12-xanmod1           | 1        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 40       | 18.69%  |
| 5.11.0  | 15       | 7.01%   |
| 4.15.0  | 14       | 6.54%   |
| 5.8.0   | 11       | 5.14%   |
| 5.0.0   | 10       | 4.67%   |
| 4.18.0  | 10       | 4.67%   |
| 5.3.0   | 9        | 4.21%   |
| 5.15.0  | 9        | 4.21%   |
| 5.13.0  | 9        | 4.21%   |
| 5.16.7  | 6        | 2.8%    |
| 5.10.14 | 6        | 2.8%    |
| 5.9.16  | 5        | 2.34%   |
| 5.19.0  | 3        | 1.4%    |
| 5.18.10 | 3        | 1.4%    |
| 5.17.5  | 3        | 1.4%    |
| 5.8.12  | 2        | 0.93%   |
| 5.16.16 | 2        | 0.93%   |
| 5.14.0  | 2        | 0.93%   |
| 5.13.13 | 2        | 0.93%   |
| 5.13.12 | 2        | 0.93%   |
| 5.10.0  | 2        | 0.93%   |
| 6.0.6   | 1        | 0.47%   |
| 6.0.0   | 1        | 0.47%   |
| 5.9.8   | 1        | 0.47%   |
| 5.9.1   | 1        | 0.47%   |
| 5.7.6   | 1        | 0.47%   |
| 5.7.10  | 1        | 0.47%   |
| 5.6.6   | 1        | 0.47%   |
| 5.6.18  | 1        | 0.47%   |
| 5.4.94  | 1        | 0.47%   |
| 5.3.1   | 1        | 0.47%   |
| 5.19.9  | 1        | 0.47%   |
| 5.19.8  | 1        | 0.47%   |
| 5.19.5  | 1        | 0.47%   |
| 5.19.3  | 1        | 0.47%   |
| 5.19.16 | 1        | 0.47%   |
| 5.19.15 | 1        | 0.47%   |
| 5.18.9  | 1        | 0.47%   |
| 5.18.0  | 1        | 0.47%   |
| 5.17.1  | 1        | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 41       | 19.43%  |
| 5.11    | 18       | 8.53%   |
| 5.13    | 17       | 8.06%   |
| 4.15    | 14       | 6.64%   |
| 5.8     | 13       | 6.16%   |
| 5.15    | 13       | 6.16%   |
| 5.10    | 13       | 6.16%   |
| 5.3     | 10       | 4.74%   |
| 5.0     | 10       | 4.74%   |
| 4.18    | 10       | 4.74%   |
| 5.16    | 9        | 4.27%   |
| 5.19    | 8        | 3.79%   |
| 5.9     | 7        | 3.32%   |
| 5.14    | 6        | 2.84%   |
| 5.18    | 5        | 2.37%   |
| 5.17    | 5        | 2.37%   |
| 5.12    | 3        | 1.42%   |
| 6.0     | 2        | 0.95%   |
| 5.7     | 2        | 0.95%   |
| 5.6     | 2        | 0.95%   |
| 4.19    | 2        | 0.95%   |
| 4.9     | 1        | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 191      | 98.45%  |
| i686   | 3        | 1.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 79       | 39.9%   |
| KDE5       | 35       | 17.68%  |
| Unknown    | 32       | 16.16%  |
| X-Cinnamon | 15       | 7.58%   |
| XFCE       | 14       | 7.07%   |
| KDE        | 10       | 5.05%   |
| xmonad     | 2        | 1.01%   |
| MATE       | 2        | 1.01%   |
| LXDE       | 2        | 1.01%   |
| Cinnamon   | 2        | 1.01%   |
| Pantheon   | 1        | 0.51%   |
| KDE4       | 1        | 0.51%   |
| i3         | 1        | 0.51%   |
| Deepin     | 1        | 0.51%   |
| Budgie     | 1        | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 149      | 76.02%  |
| Unknown | 25       | 12.76%  |
| Wayland | 21       | 10.71%  |
| Tty     | 1        | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 126      | 63.64%  |
| SDDM    | 27       | 13.64%  |
| GDM     | 17       | 8.59%   |
| LightDM | 12       | 6.06%   |
| GDM3    | 8        | 4.04%   |
| TDM     | 6        | 3.03%   |
| LXDM    | 1        | 0.51%   |
| KDM     | 1        | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CL   | 100      | 50.76%  |
| en_US   | 46       | 23.35%  |
| Unknown | 33       | 16.75%  |
| es_ES   | 8        | 4.06%   |
| en_GB   | 4        | 2.03%   |
| es_MX   | 2        | 1.02%   |
| C       | 2        | 1.02%   |
| pt_BR   | 1        | 0.51%   |
| es_UY   | 1        | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 125      | 63.13%  |
| EFI  | 73       | 36.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 155      | 78.68%  |
| Btrfs   | 17       | 8.63%   |
| Overlay | 12       | 6.09%   |
| Unknown | 7        | 3.55%   |
| Ext2    | 3        | 1.52%   |
| Zfs     | 2        | 1.02%   |
| Xfs     | 1        | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 132      | 66.67%  |
| GPT     | 46       | 23.23%  |
| MBR     | 20       | 10.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 165      | 83.33%  |
| Yes       | 33       | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 61.5%   |
| Yes       | 77       | 38.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 55       | 28.35%  |
| MSI                 | 34       | 17.53%  |
| Gigabyte Technology | 22       | 11.34%  |
| Intel               | 15       | 7.73%   |
| Hewlett-Packard     | 14       | 7.22%   |
| ECS                 | 10       | 5.15%   |
| Dell                | 6        | 3.09%   |
| ASRock              | 6        | 3.09%   |
| Pegatron            | 4        | 2.06%   |
| Lenovo              | 3        | 1.55%   |
| Huanan              | 3        | 1.55%   |
| Unknown             | 3        | 1.55%   |
| TPV-INVENTA         | 2        | 1.03%   |
| SZMZ                | 1        | 0.52%   |
| R-StyleComputers    | 1        | 0.52%   |
| Quanta              | 1        | 0.52%   |
| PCPartner           | 1        | 0.52%   |
| Olidata             | 1        | 0.52%   |
| Nvidia              | 1        | 0.52%   |
| MACHINIST           | 1        | 0.52%   |
| JGINYUE             | 1        | 0.52%   |
| IBM                 | 1        | 0.52%   |
| HC                  | 1        | 0.52%   |
| Foxconn             | 1        | 0.52%   |
| eMachines           | 1        | 0.52%   |
| Elo TouchSystems    | 1        | 0.52%   |
| Colorful Technology | 1        | 0.52%   |
| BESSTAR Tech        | 1        | 0.52%   |
| Apple               | 1        | 0.52%   |
| AMI                 | 1        | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| ASUS All Series                           | 6        | 3.09%   |
| MSI MS-7817                               | 4        | 2.06%   |
| ASUS PRIME B450M-A                        | 4        | 2.06%   |
| ASUS PRIME A320M-K                        | 4        | 2.06%   |
| Unknown                                   | 4        | 2.06%   |
| MSI MS-7A34                               | 3        | 1.55%   |
| MSI MS-7788                               | 3        | 1.55%   |
| MSI Pro 3000/3080                         | 2        | 1.03%   |
| MSI MS-7A65                               | 2        | 1.03%   |
| Intel X79M-S                              | 2        | 1.03%   |
| HP Compaq Pro 6300 SFF                    | 2        | 1.03%   |
| HP Compaq Pro 4300 SFF PC                 | 2        | 1.03%   |
| Gigabyte B450M DS3H V2                    | 2        | 1.03%   |
| Gigabyte B450 AORUS PRO WIFI              | 2        | 1.03%   |
| ECS MCP61M-M3                             | 2        | 1.03%   |
| ECS A960M-MV                              | 2        | 1.03%   |
| ECS A740GM-M                              | 2        | 1.03%   |
| ASUS TUF Gaming X570-PLUS                 | 2        | 1.03%   |
| ASUS TUF Gaming B450M-PLUS II             | 2        | 1.03%   |
| ASUS SABERTOOTH 990FX R2.0                | 2        | 1.03%   |
| ASUS PRIME H410M-E                        | 2        | 1.03%   |
| ASUS M5A99X EVO                           | 2        | 1.03%   |
| TPV-INVENTA Pro 1005 Series All-in-One PC | 1        | 0.52%   |
| TPV-INVENTA CQ1-3130LA                    | 1        | 0.52%   |
| SZMZ X99M-G2                              | 1        | 0.52%   |
| R-StyleComputers ALICON AI2S-A21 00.69    | 1        | 0.52%   |
| Quanta 120-1016la                         | 1        | 0.52%   |
| Pegatron SAISHIAT2                        | 1        | 0.52%   |
| Pegatron 9100                             | 1        | 0.52%   |
| Pegatron 520-1135la                       | 1        | 0.52%   |
| Pegatron 23-d015la                        | 1        | 0.52%   |
| PCPartner G43-F71862                      | 1        | 0.52%   |
| Nvidia NF-MCP61                           | 1        | 0.52%   |
| MSI TITAN                                 | 1        | 0.52%   |
| MSI MS-7D53                               | 1        | 0.52%   |
| MSI MS-7C90                               | 1        | 0.52%   |
| MSI MS-7C83                               | 1        | 0.52%   |
| MSI MS-7C52                               | 1        | 0.52%   |
| MSI MS-7C31                               | 1        | 0.52%   |
| MSI MS-7C09                               | 1        | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 15       | 7.73%   |
| ASUS TUF                | 7        | 3.61%   |
| HP Compaq               | 6        | 3.09%   |
| ASUS All                | 6        | 3.09%   |
| MSI MS-7817             | 4        | 2.06%   |
| ASUS M5A78L-M           | 4        | 2.06%   |
| Unknown                 | 4        | 2.06%   |
| MSI MS-7A34             | 3        | 1.55%   |
| MSI MS-7788             | 3        | 1.55%   |
| Lenovo ThinkCentre      | 3        | 1.55%   |
| HP EliteDesk            | 3        | 1.55%   |
| Gigabyte B450M          | 3        | 1.55%   |
| MSI Pro                 | 2        | 1.03%   |
| MSI MS-7A65             | 2        | 1.03%   |
| Intel X79M-S            | 2        | 1.03%   |
| Intel D54250WYK         | 2        | 1.03%   |
| Huanan X79              | 2        | 1.03%   |
| Gigabyte B450           | 2        | 1.03%   |
| ECS MCP61M-M3           | 2        | 1.03%   |
| ECS A960M-MV            | 2        | 1.03%   |
| ECS A740GM-M            | 2        | 1.03%   |
| Dell Precision          | 2        | 1.03%   |
| Dell OptiPlex           | 2        | 1.03%   |
| ASUS SABERTOOTH         | 2        | 1.03%   |
| ASUS ROG                | 2        | 1.03%   |
| ASUS M5A99X             | 2        | 1.03%   |
| TPV-INVENTA Pro         | 1        | 0.52%   |
| TPV-INVENTA CQ1-3130LA  | 1        | 0.52%   |
| SZMZ X99M-G2            | 1        | 0.52%   |
| R-StyleComputers ALICON | 1        | 0.52%   |
| Quanta 120-1016la       | 1        | 0.52%   |
| Pegatron SAISHIAT2      | 1        | 0.52%   |
| Pegatron 9100           | 1        | 0.52%   |
| Pegatron 520-1135la     | 1        | 0.52%   |
| Pegatron 23-d015la      | 1        | 0.52%   |
| PCPartner G43-F71862    | 1        | 0.52%   |
| Nvidia NF-MCP61         | 1        | 0.52%   |
| MSI TITAN               | 1        | 0.52%   |
| MSI MS-7D53             | 1        | 0.52%   |
| MSI MS-7C90             | 1        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 23       | 11.86%  |
| 2012 | 22       | 11.34%  |
| 2018 | 19       | 9.79%   |
| 2013 | 17       | 8.76%   |
| 2019 | 15       | 7.73%   |
| 2014 | 15       | 7.73%   |
| 2011 | 14       | 7.22%   |
| 2017 | 13       | 6.7%    |
| 2007 | 12       | 6.19%   |
| 2008 | 10       | 5.15%   |
| 2010 | 8        | 4.12%   |
| 2016 | 7        | 3.61%   |
| 2021 | 6        | 3.09%   |
| 2009 | 6        | 3.09%   |
| 2015 | 3        | 1.55%   |
| 2022 | 2        | 1.03%   |
| 2006 | 1        | 0.52%   |
| 2005 | 1        | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 194      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 191      | 97.95%  |
| Enabled  | 4        | 2.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 194      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 47       | 23.98%  |
| 16.01-24.0  | 38       | 19.39%  |
| 4.01-8.0    | 32       | 16.33%  |
| 3.01-4.0    | 32       | 16.33%  |
| 32.01-64.0  | 27       | 13.78%  |
| 1.01-2.0    | 10       | 5.1%    |
| 24.01-32.0  | 5        | 2.55%   |
| 2.01-3.0    | 3        | 1.53%   |
| 64.01-256.0 | 2        | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 79       | 37.44%  |
| 2.01-3.0   | 58       | 27.49%  |
| 4.01-8.0   | 30       | 14.22%  |
| 3.01-4.0   | 26       | 12.32%  |
| 8.01-16.0  | 10       | 4.74%   |
| 0.51-1.0   | 5        | 2.37%   |
| 0.01-0.5   | 2        | 0.95%   |
| 16.01-24.0 | 1        | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 73       | 36.68%  |
| 2      | 66       | 33.17%  |
| 3      | 31       | 15.58%  |
| 4      | 21       | 10.55%  |
| 5      | 5        | 2.51%   |
| 7      | 1        | 0.5%    |
| 6      | 1        | 0.5%    |
| 0      | 1        | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 58.76%  |
| Yes       | 80       | 41.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 193      | 99.48%  |
| No        | 1        | 0.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 51.28%  |
| Yes       | 95       | 48.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 139      | 70.56%  |
| Yes       | 58       | 29.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Chile   | 194      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Santiago            | 52       | 25.62%  |
| Maipu               | 9        | 4.43%   |
| Las Condes          | 9        | 4.43%   |
| Puente Alto         | 8        | 3.94%   |
| Antofagasta         | 7        | 3.45%   |
| Viña del Mar       | 6        | 2.96%   |
| Nunoa               | 6        | 2.96%   |
| La Florida          | 6        | 2.96%   |
| Valdivia            | 5        | 2.46%   |
| Temuco              | 5        | 2.46%   |
| Providencia         | 5        | 2.46%   |
| Concepción         | 5        | 2.46%   |
| Central             | 5        | 2.46%   |
| Valparaíso         | 4        | 1.97%   |
| San Miguel          | 3        | 1.48%   |
| Port Montt          | 3        | 1.48%   |
| Penalolen           | 3        | 1.48%   |
| Osorno              | 3        | 1.48%   |
| La Serena           | 3        | 1.48%   |
| El Bosque           | 3        | 1.48%   |
| Coquimbo            | 3        | 1.48%   |
| Vitacura            | 2        | 0.99%   |
| Tome                | 2        | 0.99%   |
| Talca               | 2        | 0.99%   |
| San Pedro de la Paz | 2        | 0.99%   |
| Recoleta            | 2        | 0.99%   |
| Quilpué            | 2        | 0.99%   |
| Los Ángeles        | 2        | 0.99%   |
| La Granja           | 2        | 0.99%   |
| Coronel             | 2        | 0.99%   |
| Colina              | 2        | 0.99%   |
| Chillan             | 2        | 0.99%   |
| Arica               | 2        | 0.99%   |
| Villa Alemana       | 1        | 0.49%   |
| Villa Alegre        | 1        | 0.49%   |
| Vallenar            | 1        | 0.49%   |
| Talagante           | 1        | 0.49%   |
| San Joaquin         | 1        | 0.49%   |
| San Javier          | 1        | 0.49%   |
| San Bernardo        | 1        | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 81       | 136    | 23.28%  |
| Seagate                   | 69       | 98     | 19.83%  |
| Kingston                  | 37       | 57     | 10.63%  |
| Toshiba                   | 34       | 36     | 9.77%   |
| Crucial                   | 21       | 28     | 6.03%   |
| Samsung Electronics       | 18       | 24     | 5.17%   |
| Hitachi                   | 13       | 17     | 3.74%   |
| Silicon Motion            | 8        | 8      | 2.3%    |
| SanDisk                   | 8        | 9      | 2.3%    |
| China                     | 7        | 10     | 2.01%   |
| Unknown                   | 5        | 6      | 1.44%   |
| XPG                       | 4        | 10     | 1.15%   |
| Corsair                   | 4        | 9      | 1.15%   |
| XrayDisk                  | 3        | 3      | 0.86%   |
| Micron Technology         | 3        | 6      | 0.86%   |
| KingSpec                  | 3        | 3      | 0.86%   |
| A-DATA Technology         | 3        | 3      | 0.86%   |
| Realtek Semiconductor     | 2        | 2      | 0.57%   |
| Micron/Crucial Technology | 2        | 5      | 0.57%   |
| Maxtor                    | 2        | 2      | 0.57%   |
| Lexar                     | 2        | 2      | 0.57%   |
| JMicron Technology        | 2        | 2      | 0.57%   |
| WALRAM                    | 1        | 2      | 0.29%   |
| Transcend                 | 1        | 1      | 0.29%   |
| StoreJet                  | 1        | 1      | 0.29%   |
| SK hynix                  | 1        | 1      | 0.29%   |
| Patriot                   | 1        | 1      | 0.29%   |
| OCZ                       | 1        | 2      | 0.29%   |
| NGFF                      | 1        | 1      | 0.29%   |
| Netac                     | 1        | 1      | 0.29%   |
| Mass                      | 1        | 1      | 0.29%   |
| JASTER                    | 1        | 2      | 0.29%   |
| Intenso                   | 1        | 1      | 0.29%   |
| Gigabyte Technology       | 1        | 1      | 0.29%   |
| BIWIN                     | 1        | 1      | 0.29%   |
| ASMT                      | 1        | 1      | 0.29%   |
| ASMedia                   | 1        | 2      | 0.29%   |
| Apple                     | 1        | 1      | 0.29%   |
| Unknown                   | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 12       | 3.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 10       | 2.51%   |
| Toshiba HDWD110 1TB                  | 9        | 2.26%   |
| Toshiba DT01ACA100 1TB               | 9        | 2.26%   |
| Kingston SA400S37240G 240GB SSD      | 8        | 2.01%   |
| WDC WD10EZEX-08WN4A0 1TB             | 7        | 1.76%   |
| Kingston SA400S37120G 120GB SSD      | 7        | 1.76%   |
| WDC WD5000AAKX-001CA0 500GB          | 6        | 1.51%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 5        | 1.26%   |
| Seagate ST3500418AS 500GB            | 5        | 1.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 4        | 1.01%   |
| WDC WD10EZEX-00BN5A0 1TB             | 4        | 1.01%   |
| Seagate ST3320418AS 320GB            | 4        | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB       | 4        | 1.01%   |
| SanDisk NVMe SSD Drive 1TB           | 4        | 1.01%   |
| Kingston SA400S37480G 480GB SSD      | 4        | 1.01%   |
| Crucial CT500MX500SSD1 500GB         | 4        | 1.01%   |
| XPG SPECTRIX S40G 256GB              | 3        | 0.75%   |
| XPG GAMMIX S11 Pro 512GB             | 3        | 0.75%   |
| Toshiba DT01ACA050 500GB             | 3        | 0.75%   |
| Seagate ST500LT012-9WS142 500GB      | 3        | 0.75%   |
| Seagate ST500LT012-1DG142 500GB      | 3        | 0.75%   |
| SanDisk NVMe SSD Drive 500GB         | 3        | 0.75%   |
| Kingston SUV400S37240G 240GB SSD     | 3        | 0.75%   |
| Hitachi HDS721050CLA362 500GB        | 3        | 0.75%   |
| Hitachi HDS721032CLA362 320GB        | 3        | 0.75%   |
| Crucial CT480BX500SSD1 480GB         | 3        | 0.75%   |
| Crucial CT240BX500SSD1 240GB         | 3        | 0.75%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 2        | 0.5%    |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 2        | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2        | 0.5%    |
| WDC WDS100T2B0C-00PXH0 1TB           | 2        | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2        | 0.5%    |
| WDC WD20EARX-00PASB0 2TB             | 2        | 0.5%    |
| WDC WD2003FZEX-00Z4SA0 2TB           | 2        | 0.5%    |
| WDC WD1003FBYZ-010FB0 1TB            | 2        | 0.5%    |
| Toshiba HDWD105 500GB                | 2        | 0.5%    |
| Silicon Motion NVMe SSD Drive 512GB  | 2        | 0.5%    |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.5%    |
| Seagate ST9640320AS 640GB            | 2        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 69       | 98     | 36.7%   |
| WDC                 | 62       | 94     | 32.98%  |
| Toshiba             | 34       | 36     | 18.09%  |
| Hitachi             | 13       | 17     | 6.91%   |
| Samsung Electronics | 4        | 6      | 2.13%   |
| Maxtor              | 2        | 2      | 1.06%   |
| Unknown             | 1        | 1      | 0.53%   |
| ASMT                | 1        | 1      | 0.53%   |
| ASMedia             | 1        | 2      | 0.53%   |
| Apple               | 1        | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 35       | 44     | 28.69%  |
| WDC                 | 25       | 34     | 20.49%  |
| Crucial             | 21       | 27     | 17.21%  |
| Samsung Electronics | 10       | 11     | 8.2%    |
| China               | 7        | 10     | 5.74%   |
| Corsair             | 4        | 9      | 3.28%   |
| KingSpec            | 3        | 3      | 2.46%   |
| XrayDisk            | 2        | 2      | 1.64%   |
| Micron Technology   | 2        | 2      | 1.64%   |
| Lexar               | 2        | 2      | 1.64%   |
| WALRAM              | 1        | 1      | 0.82%   |
| StoreJet            | 1        | 1      | 0.82%   |
| Patriot             | 1        | 1      | 0.82%   |
| OCZ                 | 1        | 2      | 0.82%   |
| NGFF                | 1        | 1      | 0.82%   |
| JMicron Technology  | 1        | 1      | 0.82%   |
| Intenso             | 1        | 1      | 0.82%   |
| Gigabyte Technology | 1        | 1      | 0.82%   |
| BIWIN               | 1        | 1      | 0.82%   |
| A-DATA Technology   | 1        | 1      | 0.82%   |
| Unknown             | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 141      | 258    | 48.29%  |
| SSD     | 99       | 156    | 33.9%   |
| NVMe    | 43       | 73     | 14.73%  |
| Unknown | 7        | 8      | 2.4%    |
| MMC     | 2        | 2      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 185      | 405    | 76.45%  |
| NVMe | 43       | 73     | 17.77%  |
| SAS  | 12       | 17     | 4.96%   |
| MMC  | 2        | 2      | 0.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 153      | 276    | 61.94%  |
| 0.51-1.0   | 60       | 86     | 24.29%  |
| 1.01-2.0   | 19       | 27     | 7.69%   |
| 3.01-4.0   | 8        | 9      | 3.24%   |
| 2.01-3.0   | 4        | 11     | 1.62%   |
| 4.01-10.0  | 3        | 5      | 1.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 49       | 23.79%  |
| 101-250        | 40       | 19.42%  |
| 501-1000       | 28       | 13.59%  |
| 1001-2000      | 20       | 9.71%   |
| More than 3000 | 17       | 8.25%   |
| 1-20           | 15       | 7.28%   |
| 51-100         | 13       | 6.31%   |
| 2001-3000      | 12       | 5.83%   |
| 21-50          | 6        | 2.91%   |
| Unknown        | 6        | 2.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 77       | 36.67%  |
| 21-50          | 43       | 20.48%  |
| 101-250        | 21       | 10%     |
| 501-1000       | 15       | 7.14%   |
| 1001-2000      | 14       | 6.67%   |
| 51-100         | 13       | 6.19%   |
| 251-500        | 11       | 5.24%   |
| More than 3000 | 7        | 3.33%   |
| Unknown        | 6        | 2.86%   |
| 2001-3000      | 3        | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| XrayDisk SSD 256GB                   | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-083CA1 500GB          | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1        | 1      | 4.35%   |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 2      | 4.35%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1      | 4.35%   |
| WDC WD10EARS-003BB1 1TB              | 1        | 1      | 4.35%   |
| Toshiba MK1652GSX 160GB              | 1        | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB      | 1        | 1      | 4.35%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 1      | 4.35%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1      | 4.35%   |
| Seagate ST3500418AS 500GB            | 1        | 1      | 4.35%   |
| Samsung Electronics SSD 870 EVO 1TB  | 1        | 1      | 4.35%   |
| Samsung Electronics HD250HJ 250GB    | 1        | 2      | 4.35%   |
| Samsung Electronics HD081GJ 80GB     | 1        | 1      | 4.35%   |
| Kingston SKC400S371T 1TB SSD         | 1        | 2      | 4.35%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 1      | 4.35%   |
| Kingston SA400S37240G 240GB SSD      | 1        | 1      | 4.35%   |
| Hitachi HTS547550A9E384 500GB        | 1        | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB        | 1        | 1      | 4.35%   |
| Hitachi HTS545050A7E380 500GB        | 1        | 1      | 4.35%   |
| Hitachi HDS721050CLA660 500GB        | 1        | 1      | 4.35%   |
| Hitachi HDS721032CLA362 320GB        | 1        | 1      | 4.35%   |
| A-DATA Technology SX8100NP 1TB       | 1        | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 23.81%  |
| Seagate             | 4        | 4      | 19.05%  |
| Hitachi             | 4        | 5      | 19.05%  |
| Kingston            | 3        | 4      | 14.29%  |
| Samsung Electronics | 2        | 4      | 9.52%   |
| XrayDisk            | 1        | 1      | 4.76%   |
| Toshiba             | 1        | 1      | 4.76%   |
| A-DATA Technology   | 1        | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 33.33%  |
| Seagate             | 4        | 4      | 26.67%  |
| Hitachi             | 4        | 5      | 26.67%  |
| Toshiba             | 1        | 1      | 6.67%   |
| Samsung Electronics | 1        | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 19     | 68.42%  |
| SSD  | 5        | 6      | 26.32%  |
| NVMe | 1        | 1      | 5.26%   |

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
| Detected | 138      | 332    | 63.59%  |
| Works    | 60       | 138    | 27.65%  |
| Malfunc  | 18       | 26     | 8.29%   |
| Failed   | 1        | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 109      | 42.58%  |
| AMD                          | 77       | 30.08%  |
| SanDisk                      | 12       | 4.69%   |
| Silicon Motion               | 10       | 3.91%   |
| JMicron Technology           | 8        | 3.13%   |
| Realtek Semiconductor        | 7        | 2.73%   |
| Marvell Technology Group     | 6        | 2.34%   |
| Samsung Electronics          | 5        | 1.95%   |
| Nvidia                       | 5        | 1.95%   |
| ASMedia Technology           | 4        | 1.56%   |
| Micron/Crucial Technology    | 3        | 1.17%   |
| Kingston Technology Company  | 3        | 1.17%   |
| ADATA Technology             | 3        | 1.17%   |
| VIA Technologies             | 1        | 0.39%   |
| SK hynix                     | 1        | 0.39%   |
| Shenzhen Longsys Electronics | 1        | 0.39%   |
| Micron Technology            | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43       | 12.57%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 4.68%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 4.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 4.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 12       | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 2.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 9        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.34%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 7        | 2.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.05%   |
| AMD FCH SATA Controller D                                                               | 7        | 2.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 6        | 1.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 1.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 1.75%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 1.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 5        | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.46%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.46%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5        | 1.46%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 1.17%   |
| Nvidia MCP61 IDE                                                                        | 4        | 1.17%   |
| SanDisk Non-Volatile memory controller                                                  | 3        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 0.88%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 0.88%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 0.88%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 0.88%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 3        | 0.88%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3        | 0.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 0.88%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 152      | 59.38%  |
| IDE  | 57       | 22.27%  |
| NVMe | 43       | 16.8%   |
| RAID | 4        | 1.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 112      | 57.73%  |
| AMD    | 82       | 42.27%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 5        | 2.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 2.02%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4        | 2.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.02%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 2.02%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.52%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.52%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.52%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.52%   |
| AMD E-450 APU with Radeon HD Graphics       | 3        | 1.52%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 3        | 1.52%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 2        | 1.01%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 2        | 1.01%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 2        | 1.01%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.01%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.01%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 1.01%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.01%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.01%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.01%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 2        | 1.01%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.01%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.01%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 1.01%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 1.01%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 2        | 1.01%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.01%   |
| AMD Ryzen 9 3900XT 12-Core Processor        | 2        | 1.01%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.01%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.01%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.01%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.01%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.01%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.01%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.01%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.01%   |
| AMD Phenom II X6 1090T Processor            | 2        | 1.01%   |
| AMD Phenom II X4 955 Processor              | 2        | 1.01%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 14.72%  |
| Intel Xeon              | 19       | 9.64%   |
| Intel Core i7           | 16       | 8.12%   |
| AMD Ryzen 5             | 16       | 8.12%   |
| Intel Core i3           | 14       | 7.11%   |
| AMD Ryzen 7             | 11       | 5.58%   |
| AMD FX                  | 11       | 5.58%   |
| Intel Core 2 Duo        | 10       | 5.08%   |
| Intel Celeron           | 8        | 4.06%   |
| AMD Ryzen 3             | 7        | 3.55%   |
| AMD A6                  | 6        | 3.05%   |
| Intel Pentium           | 5        | 2.54%   |
| AMD Athlon              | 5        | 2.54%   |
| AMD Ryzen 9             | 3        | 1.52%   |
| AMD Phenom              | 3        | 1.52%   |
| AMD E                   | 3        | 1.52%   |
| AMD Athlon II X2        | 3        | 1.52%   |
| Intel Pentium Dual-Core | 2        | 1.02%   |
| Intel Pentium Dual      | 2        | 1.02%   |
| Intel Pentium 4         | 2        | 1.02%   |
| Intel Core 2            | 2        | 1.02%   |
| AMD Phenom II X6        | 2        | 1.02%   |
| AMD Phenom II X4        | 2        | 1.02%   |
| AMD Athlon 64 X2        | 2        | 1.02%   |
| AMD A8                  | 2        | 1.02%   |
| AMD A10                 | 2        | 1.02%   |
| Intel Xeon Bronze       | 1        | 0.51%   |
| Intel Pentium Gold      | 1        | 0.51%   |
| Intel Core i9           | 1        | 0.51%   |
| Intel Core 2 Quad       | 1        | 0.51%   |
| Intel Atom              | 1        | 0.51%   |
| AMD Ryzen Threadripper  | 1        | 0.51%   |
| AMD Ryzen 5 PRO         | 1        | 0.51%   |
| AMD Athlon X4           | 1        | 0.51%   |
| AMD Athlon II X4        | 1        | 0.51%   |
| AMD Athlon II           | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 69       | 34.85%  |
| 2       | 58       | 29.29%  |
| 6       | 26       | 13.13%  |
| 8       | 19       | 9.6%    |
| 3       | 8        | 4.04%   |
| 12      | 6        | 3.03%   |
| 1       | 6        | 3.03%   |
| 10      | 3        | 1.52%   |
| 16      | 2        | 1.01%   |
| Unknown | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 192      | 98.97%  |
| 2      | 2        | 1.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 105      | 53.85%  |
| 1       | 89       | 45.64%  |
| Unknown | 1        | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 188      | 96.91%  |
| Unknown        | 4        | 2.06%   |
| 64-bit         | 1        | 0.52%   |
| 32-bit         | 1        | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 24.88%  |
| 0x306c3    | 14       | 6.83%   |
| 0x306a9    | 10       | 4.88%   |
| 0x08701021 | 10       | 4.88%   |
| 0x206a7    | 8        | 3.9%    |
| 0x08108109 | 8        | 3.9%    |
| 0x06000852 | 7        | 3.41%   |
| 0xa0653    | 5        | 2.44%   |
| 0x1067a    | 5        | 2.44%   |
| 0x10676    | 5        | 2.44%   |
| 0x6fd      | 4        | 1.95%   |
| 0x0800820d | 4        | 1.95%   |
| 0x03000027 | 4        | 1.95%   |
| 0x906ea    | 3        | 1.46%   |
| 0x6fb      | 3        | 1.46%   |
| 0x306f2    | 3        | 1.46%   |
| 0x306e4    | 3        | 1.46%   |
| 0x0600063e | 3        | 1.46%   |
| 0x010000c8 | 3        | 1.46%   |
| 0x906e9    | 2        | 0.98%   |
| 0x506e3    | 2        | 0.98%   |
| 0x40651    | 2        | 0.98%   |
| 0x30678    | 2        | 0.98%   |
| 0x206d7    | 2        | 0.98%   |
| 0x106a5    | 2        | 0.98%   |
| 0x08108102 | 2        | 0.98%   |
| 0x08101016 | 2        | 0.98%   |
| 0x08001138 | 2        | 0.98%   |
| 0x06003106 | 2        | 0.98%   |
| 0x06001119 | 2        | 0.98%   |
| 0x05000119 | 2        | 0.98%   |
| 0x010000bf | 2        | 0.98%   |
| 0x01000095 | 2        | 0.98%   |
| 0xf65      | 1        | 0.49%   |
| 0xf41      | 1        | 0.49%   |
| 0xa0655    | 1        | 0.49%   |
| 0x906ed    | 1        | 0.49%   |
| 0x906eb    | 1        | 0.49%   |
| 0x706a1    | 1        | 0.49%   |
| 0x6f2      | 1        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 25       | 12.76%  |
| IvyBridge     | 17       | 8.67%   |
| Zen+          | 14       | 7.14%   |
| Penryn        | 14       | 7.14%   |
| Zen 2         | 13       | 6.63%   |
| KabyLake      | 12       | 6.12%   |
| K10           | 12       | 6.12%   |
| SandyBridge   | 11       | 5.61%   |
| Piledriver    | 11       | 5.61%   |
| Zen           | 10       | 5.1%    |
| Core          | 9        | 4.59%   |
| CometLake     | 8        | 4.08%   |
| Zen 3         | 6        | 3.06%   |
| Skylake       | 4        | 2.04%   |
| Silvermont    | 4        | 2.04%   |
| K10 Llano     | 4        | 2.04%   |
| Steamroller   | 3        | 1.53%   |
| Nehalem       | 3        | 1.53%   |
| Bulldozer     | 3        | 1.53%   |
| Bobcat        | 3        | 1.53%   |
| Westmere      | 2        | 1.02%   |
| NetBurst      | 2        | 1.02%   |
| K8 Hammer     | 2        | 1.02%   |
| Jaguar        | 1        | 0.51%   |
| Goldmont plus | 1        | 0.51%   |
| Excavator     | 1        | 0.51%   |
| Broadwell     | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 78       | 37.86%  |
| Nvidia                     | 69       | 33.5%   |
| Intel                      | 56       | 27.18%  |
| VIA Technologies           | 1        | 0.49%   |
| Matrox Electronics Systems | 1        | 0.49%   |
| ATI Technologies           | 1        | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 4.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7        | 3.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7        | 3.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7        | 3.3%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 2.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5        | 2.36%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5        | 2.36%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 2.36%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.89%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 3        | 1.42%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 1.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3        | 1.42%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 1.42%   |
| Intel HD Graphics 530                                                                    | 3        | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3        | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3        | 1.42%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 1.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.42%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3        | 1.42%   |
| AMD Sumo [Radeon HD 6530D]                                                               | 3        | 1.42%   |
| AMD RS780L [Radeon 3000]                                                                 | 3        | 1.42%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.42%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 3        | 1.42%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3        | 1.42%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 0.94%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 0.94%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2        | 0.94%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 2        | 0.94%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 2        | 0.94%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2        | 0.94%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 2        | 0.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.94%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x AMD      | 66       | 33.67%  |
| 1 x Nvidia   | 65       | 33.16%  |
| 1 x Intel    | 52       | 26.53%  |
| 2 x AMD      | 5        | 2.55%   |
| AMD + Nvidia | 5        | 2.55%   |
| 1 x VIA      | 1        | 0.51%   |
| 1 x Matrox   | 1        | 0.51%   |
| Intel + AMD  | 1        | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 149      | 76.02%  |
| Proprietary | 41       | 20.92%  |
| Unknown     | 6        | 3.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 85       | 43.15%  |
| 1.01-2.0   | 36       | 18.27%  |
| 0.51-1.0   | 21       | 10.66%  |
| 0.01-0.5   | 18       | 9.14%   |
| 3.01-4.0   | 15       | 7.61%   |
| 7.01-8.0   | 7        | 3.55%   |
| 5.01-6.0   | 6        | 3.05%   |
| 8.01-16.0  | 6        | 3.05%   |
| 2.01-3.0   | 3        | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 48       | 24.12%  |
| Goldstar             | 41       | 20.6%   |
| Hewlett-Packard      | 17       | 8.54%   |
| Dell                 | 11       | 5.53%   |
| AOC                  | 11       | 5.53%   |
| LG Electronics       | 10       | 5.03%   |
| Unknown              | 6        | 3.02%   |
| Lenovo               | 6        | 3.02%   |
| ___                  | 4        | 2.01%   |
| ViewSonic            | 4        | 2.01%   |
| Sony                 | 4        | 2.01%   |
| SAC                  | 3        | 1.51%   |
| Plain Tree Systems   | 3        | 1.51%   |
| Packard Bell         | 3        | 1.51%   |
| KTC                  | 3        | 1.51%   |
| Envision             | 3        | 1.51%   |
| Acer                 | 3        | 1.51%   |
| Philips              | 2        | 1.01%   |
| Hitachi              | 2        | 1.01%   |
| CHR                  | 2        | 1.01%   |
| Ancor Communications | 2        | 1.01%   |
| Westinghouse         | 1        | 0.5%    |
| Unknown (XXX)        | 1        | 0.5%    |
| SKY                  | 1        | 0.5%    |
| Sharp                | 1        | 0.5%    |
| MSI                  | 1        | 0.5%    |
| Mi                   | 1        | 0.5%    |
| HKC                  | 1        | 0.5%    |
| GDH                  | 1        | 0.5%    |
| BenQ                 | 1        | 0.5%    |
| ASUSTek Computer     | 1        | 0.5%    |
| Unknown              | 1        | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 7        | 3.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 5        | 2.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 5        | 2.38%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 4        | 1.9%    |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 3        | 1.43%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                  | 3        | 1.43%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                | 3        | 1.43%   |
| ___ LCDTV16 ___9000 1360x768                                            | 2        | 0.95%   |
| ___ LCDTV16 ___0101 1920x1080                                           | 2        | 0.95%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                    | 2        | 0.95%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 2        | 0.95%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                      | 2        | 0.95%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 2        | 0.95%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 2        | 0.95%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.95%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                   | 2        | 0.95%   |
| Philips 190P PHL0831 1280x1024 376x301mm 19.0-inch                      | 2        | 0.95%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                             | 2        | 0.95%   |
| Lenovo LEN S22e-19 LEN61C9 1920x1080 476x268mm 21.5-inch                | 2        | 0.95%   |
| Hewlett-Packard All-in-One HWP4211 1920x1080 509x286mm 23.0-inch        | 2        | 0.95%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 2        | 0.95%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                       | 2        | 0.95%   |
| AOC LE24H037 AOC2407 1920x1080 521x293mm 23.5-inch                      | 2        | 0.95%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                          | 2        | 0.95%   |
| Westinghouse LCM-19v5 WDE1905 1280x1024 376x301mm 19.0-inch             | 1        | 0.48%   |
| ViewSonic VX2253 Series VSC0A28 1920x1080 476x268mm 21.5-inch           | 1        | 0.48%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch                | 1        | 0.48%   |
| ViewSonic VA1926wSERIES VSC5920 1440x900 410x256mm 19.0-inch            | 1        | 0.48%   |
| ViewSonic LCD Monitor VX2370 SERIES 1920x1080                           | 1        | 0.48%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch          | 1        | 0.48%   |
| Sony TV SNY4302 1920x1080                                               | 1        | 0.48%   |
| Sony TV SNY3002 1920x1080 708x398mm 32.0-inch                           | 1        | 0.48%   |
| Sony TV SNY1503 1360x768 1600x900mm 72.3-inch                           | 1        | 0.48%   |
| Sony TV *02 SNYC403 1920x1080 1085x610mm 49.0-inch                      | 1        | 0.48%   |
| SKY TV-monitor SKY0102 1920x1080 885x498mm 40.0-inch                    | 1        | 0.48%   |
| Sharp HDMI SHP101E 1920x540                                             | 1        | 0.48%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 0.48%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch       | 1        | 0.48%   |
| Samsung Electronics T19B300 SAM0926 1366x768 410x230mm 18.5-inch        | 1        | 0.48%   |
| Samsung Electronics SyncMaster SAM0576 1280x1024 338x270mm 17.0-inch    | 1        | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 78       | 40.84%  |
| 1366x768 (WXGA)    | 17       | 8.9%    |
| 3840x2160 (4K)     | 16       | 8.38%   |
| 1360x768           | 14       | 7.33%   |
| 1440x900 (WXGA+)   | 13       | 6.81%   |
| 1280x1024 (SXGA)   | 10       | 5.24%   |
| 2560x1440 (QHD)    | 8        | 4.19%   |
| 2560x1080          | 8        | 4.19%   |
| 1600x900 (HD+)     | 8        | 4.19%   |
| 1680x1050 (WSXGA+) | 4        | 2.09%   |
| Unknown            | 4        | 2.09%   |
| 3840x1080          | 3        | 1.57%   |
| 1024x768 (XGA)     | 3        | 1.57%   |
| 3440x1440          | 2        | 1.05%   |
| 5760x1080          | 1        | 0.52%   |
| 1280x960           | 1        | 0.52%   |
| 1280x768           | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 31       | 15.74%  |
| 23      | 28       | 14.21%  |
| Unknown | 23       | 11.68%  |
| 18      | 16       | 8.12%   |
| 19      | 11       | 5.58%   |
| 34      | 10       | 5.08%   |
| 27      | 10       | 5.08%   |
| 24      | 10       | 5.08%   |
| 20      | 8        | 4.06%   |
| 17      | 8        | 4.06%   |
| 31      | 7        | 3.55%   |
| 15      | 7        | 3.55%   |
| 72      | 6        | 3.05%   |
| 84      | 4        | 2.03%   |
| 54      | 4        | 2.03%   |
| 32      | 4        | 2.03%   |
| 40      | 3        | 1.52%   |
| 22      | 2        | 1.02%   |
| 55      | 1        | 0.51%   |
| 52      | 1        | 0.51%   |
| 37      | 1        | 0.51%   |
| 28      | 1        | 0.51%   |
| 13      | 1        | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 59       | 31.05%  |
| 501-600     | 43       | 22.63%  |
| Unknown     | 23       | 12.11%  |
| 701-800     | 14       | 7.37%   |
| 301-350     | 13       | 6.84%   |
| 601-700     | 10       | 5.26%   |
| 1501-2000   | 10       | 5.26%   |
| 351-400     | 7        | 3.68%   |
| 1001-1500   | 6        | 3.16%   |
| 801-900     | 4        | 2.11%   |
| 201-300     | 1        | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 120      | 67.04%  |
| Unknown | 18       | 10.06%  |
| 16/10   | 17       | 9.5%    |
| 5/4     | 11       | 6.15%   |
| 21/9    | 10       | 5.59%   |
| 4/3     | 3        | 1.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 59       | 30.73%  |
| 151-200        | 25       | 13.02%  |
| Unknown        | 23       | 11.98%  |
| 351-500        | 22       | 11.46%  |
| 141-150        | 19       | 9.9%    |
| More than 1000 | 16       | 8.33%   |
| 301-350        | 10       | 5.21%   |
| 101-110        | 7        | 3.65%   |
| 251-300        | 4        | 2.08%   |
| 501-1000       | 4        | 2.08%   |
| 131-140        | 2        | 1.04%   |
| 91-100         | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 106      | 56.08%  |
| 101-120 | 39       | 20.63%  |
| Unknown | 23       | 12.17%  |
| 1-50    | 17       | 8.99%   |
| 121-160 | 3        | 1.59%   |
| 161-240 | 1        | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 147      | 75%     |
| 2     | 33       | 16.84%  |
| 0     | 12       | 6.12%   |
| 3     | 4        | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 145      | 48.99%  |
| Intel                           | 49       | 16.55%  |
| Ralink Technology               | 14       | 4.73%   |
| Qualcomm Atheros                | 13       | 4.39%   |
| Ralink                          | 12       | 4.05%   |
| Broadcom                        | 9        | 3.04%   |
| TP-Link                         | 8        | 2.7%    |
| Xiaomi                          | 7        | 2.36%   |
| Broadcom Limited                | 5        | 1.69%   |
| Nvidia                          | 4        | 1.35%   |
| D-Link System                   | 4        | 1.35%   |
| Qualcomm Atheros Communications | 3        | 1.01%   |
| Marvell Technology Group        | 3        | 1.01%   |
| Huawei Technologies             | 3        | 1.01%   |
| VIA Technologies                | 2        | 0.68%   |
| Samsung Electronics             | 2        | 0.68%   |
| Motorola PCS                    | 2        | 0.68%   |
| Microsoft                       | 2        | 0.68%   |
| D-Link                          | 2        | 0.68%   |
| Spreadtrum Communications       | 1        | 0.34%   |
| Padix (Rockfire)                | 1        | 0.34%   |
| Oculus VR                       | 1        | 0.34%   |
| Mercucys                        | 1        | 0.34%   |
| Manta                           | 1        | 0.34%   |
| ICS Advent                      | 1        | 0.34%   |
| HMD Global                      | 1        | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 120      | 36.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 3.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 2.11%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 2.11%   |
| Intel I211 Gigabit Network Connection                             | 7        | 2.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 1.81%   |
| Intel Wireless 7260                                               | 5        | 1.51%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 1.51%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 4        | 1.21%   |
| Realtek 802.11ac NIC                                              | 4        | 1.21%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 1.21%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 4        | 1.21%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 4        | 1.21%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 1.21%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 0.91%   |
| Huawei STK-L21                                                    | 3        | 0.91%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2        | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2        | 0.6%    |
| Realtek RTL8187 Wireless Adapter                                  | 2        | 0.6%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 2        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.6%    |
| Ralink RT2561/RT61 rev B 802.11g                                  | 2        | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.6%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.6%    |
| Intel Wireless-AC 9260                                            | 2        | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 2        | 0.6%    |
| Intel Ethernet Connection I218-V                                  | 2        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.6%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 26       | 24.53%  |
| Intel                           | 23       | 21.7%   |
| Ralink Technology               | 14       | 13.21%  |
| Ralink                          | 12       | 11.32%  |
| TP-Link                         | 8        | 7.55%   |
| Qualcomm Atheros                | 7        | 6.6%    |
| Qualcomm Atheros Communications | 3        | 2.83%   |
| Broadcom Limited                | 3        | 2.83%   |
| Broadcom                        | 3        | 2.83%   |
| Microsoft                       | 2        | 1.89%   |
| D-Link System                   | 2        | 1.89%   |
| D-Link                          | 2        | 1.89%   |
| Mercucys                        | 1        | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                               | 7        | 6.6%    |
| Intel Wireless 7260                                                           | 5        | 4.72%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 4.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 4        | 3.77%   |
| Realtek 802.11ac NIC                                                          | 4        | 3.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 4        | 3.77%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 4        | 3.77%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4        | 3.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4        | 3.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 3        | 2.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 2.83%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 1.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 1.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2        | 1.89%   |
| Realtek RTL8187 Wireless Adapter                                              | 2        | 1.89%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 2        | 1.89%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 1.89%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 1.89%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 1.89%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 2        | 1.89%   |
| Intel Wireless-AC 9260                                                        | 2        | 1.89%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]          | 2        | 1.89%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.94%   |
| TP-Link Archer T4U ver.3                                                      | 1        | 0.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.94%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 1        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.94%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 0.94%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.94%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 0.94%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                     | 1        | 0.94%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.94%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 138      | 64.19%  |
| Intel                     | 36       | 16.74%  |
| Xiaomi                    | 7        | 3.26%   |
| Qualcomm Atheros          | 6        | 2.79%   |
| Broadcom                  | 6        | 2.79%   |
| Nvidia                    | 4        | 1.86%   |
| Marvell Technology Group  | 3        | 1.4%    |
| Huawei Technologies       | 3        | 1.4%    |
| VIA Technologies          | 2        | 0.93%   |
| Samsung Electronics       | 2        | 0.93%   |
| D-Link System             | 2        | 0.93%   |
| Broadcom Limited          | 2        | 0.93%   |
| Spreadtrum Communications | 1        | 0.47%   |
| Motorola PCS              | 1        | 0.47%   |
| ICS Advent                | 1        | 0.47%   |
| HMD Global                | 1        | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 120      | 54.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 4.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7        | 3.17%   |
| Intel I211 Gigabit Network Connection                             | 7        | 3.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6        | 2.71%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.26%   |
| Nvidia MCP61 Ethernet                                             | 4        | 1.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.36%   |
| Huawei STK-L21                                                    | 3        | 1.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.9%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 2        | 0.9%    |
| Intel Ethernet Connection I218-V                                  | 2        | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.9%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.9%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.9%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 0.9%    |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2        | 0.9%    |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 2        | 0.9%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.45%   |
| Spreadtrum Nokia G21                                              | 1        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.45%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.45%   |
| Motorola PCS moto g(9) play                                       | 1        | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.45%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.45%   |
| Intel Ethernet Connection (3) I219-LM                             | 1        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 193      | 66.1%   |
| WiFi     | 95       | 32.53%  |
| Unknown  | 3        | 1.03%   |
| Modem    | 1        | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 142      | 73.2%   |
| WiFi     | 52       | 26.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 126      | 64.29%  |
| 2     | 59       | 30.1%   |
| 3     | 9        | 4.59%   |
| 4     | 1        | 0.51%   |
| 0     | 1        | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 183      | 93.37%  |
| Yes  | 13       | 6.63%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 33.33%  |
| Cambridge Silicon Radio         | 19       | 31.67%  |
| Realtek Semiconductor           | 10       | 16.67%  |
| Broadcom                        | 7        | 11.67%  |
| Qualcomm Atheros Communications | 2        | 3.33%   |
| ASUSTek Computer                | 1        | 1.67%   |
| Apple                           | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 19       | 31.67%  |
| Realtek Bluetooth Radio                             | 9        | 15%     |
| Intel Bluetooth wireless interface                  | 6        | 10%     |
| Intel AX200 Bluetooth                               | 5        | 8.33%   |
| Intel AX210 Bluetooth                               | 4        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5%      |
| Broadcom Bluetooth 3.0 Dongle                       | 3        | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 1.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 1.67%   |
| Broadcom HP Bluetooth Module                        | 1        | 1.67%   |
| Broadcom HP Bluethunder                             | 1        | 1.67%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 1.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.67%   |
| ASUS BCM20702A0                                     | 1        | 1.67%   |
| Apple Bluetooth HCI                                 | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 106      | 33.54%  |
| AMD                        | 99       | 31.33%  |
| Nvidia                     | 63       | 19.94%  |
| C-Media Electronics        | 8        | 2.53%   |
| Creative Labs              | 6        | 1.9%    |
| Razer USA                  | 3        | 0.95%   |
| Logitech                   | 3        | 0.95%   |
| VIA Technologies           | 2        | 0.63%   |
| Texas Instruments          | 2        | 0.63%   |
| Kingston Technology        | 2        | 0.63%   |
| Generalplus Technology     | 2        | 0.63%   |
| Creative Technology        | 2        | 0.63%   |
| Corsair                    | 2        | 0.63%   |
| Arturia                    | 2        | 0.63%   |
| Unknown                    | 1        | 0.32%   |
| Trust                      | 1        | 0.32%   |
| PreSonus Audio Electronics | 1        | 0.32%   |
| Native Instruments         | 1        | 0.32%   |
| Micro Star International   | 1        | 0.32%   |
| JMTek                      | 1        | 0.32%   |
| Hewlett-Packard            | 1        | 0.32%   |
| GYROCOM C&C                | 1        | 0.32%   |
| Focusrite-Novation         | 1        | 0.32%   |
| eMPIA Technology           | 1        | 0.32%   |
| Blue Microphones           | 1        | 0.32%   |
| ATI Technologies           | 1        | 0.32%   |
| Apple                      | 1        | 0.32%   |
| Afatech                    | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 22       | 5.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 18       | 4.7%    |
| AMD Starship/Matisse HD Audio Controller                                          | 17       | 4.44%   |
| AMD Family 17h/19h HD Audio Controller                                            | 17       | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 13       | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 2.87%   |
| AMD FCH Azalia Controller                                                         | 11       | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10       | 2.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 2.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 9        | 2.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 2.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8        | 2.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 2.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 1.83%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 1.57%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6        | 1.57%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 6        | 1.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6        | 1.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 1.57%   |
| Intel Comet Lake PCH-V cAVS                                                       | 5        | 1.31%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 1.31%   |
| AMD Navi 10 HDMI Audio                                                            | 5        | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.04%   |
| Nvidia MCP61 High Definition Audio                                                | 4        | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 1.04%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 1.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.78%   |
| Nvidia High Definition Audio Controller                                           | 3        | 0.78%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3        | 0.78%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 3        | 0.78%   |
| Intel 8 Series HD Audio Controller                                                | 3        | 0.78%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 3        | 0.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 25.26%  |
| Crucial             | 17       | 17.89%  |
| Unknown             | 10       | 10.53%  |
| Samsung Electronics | 10       | 10.53%  |
| Corsair             | 10       | 10.53%  |
| SK hynix            | 4        | 4.21%   |
| Micron Technology   | 4        | 4.21%   |
| Patriot             | 3        | 3.16%   |
| G.Skill             | 3        | 3.16%   |
| A-DATA Technology   | 3        | 3.16%   |
| Nanya Technology    | 1        | 1.05%   |
| Kreton              | 1        | 1.05%   |
| Goldenmars          | 1        | 1.05%   |
| GLOWAY              | 1        | 1.05%   |
| Elpida              | 1        | 1.05%   |
| Atermiter           | 1        | 1.05%   |
| Ankowall            | 1        | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s      | 3        | 2.8%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 3        | 2.8%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 3        | 2.8%    |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 2        | 1.87%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s | 2        | 1.87%   |
| Kingston RAM KHX3466C17D4/16GX 16GB DIMM DDR4 3466MT/s   | 2        | 1.87%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4096MB DIMM DDR4 2666MT/s  | 2        | 1.87%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.93%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 0.93%   |
| Unknown RAM Module 8192MB DIMM DDR3                      | 1        | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 1        | 0.93%   |
| Unknown RAM Module 2GB DIMM                              | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                  | 1        | 0.93%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s          | 1        | 0.93%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s            | 1        | 0.93%   |
| SK hynix RAM HMT151R7BFR4C 4096MB DIMM DDR3 1333MT/s     | 1        | 0.93%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s  | 1        | 0.93%   |
| Samsung RAM M471B1G73QHO-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.93%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s    | 1        | 0.93%   |
| Samsung RAM M393B5273CH0-YH9 4GB DIMM DDR3 1333MT/s      | 1        | 0.93%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s          | 1        | 0.93%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1866MT/s         | 1        | 0.93%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 0.93%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 0.93%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 0.93%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1        | 0.93%   |
| Micron RAM M471A3243BB0-CP50 16GB SODIMM DDR4 2667MT/s   | 1        | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 1        | 0.93%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s      | 1        | 0.93%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 1        | 0.93%   |
| Kreton RAM 51525xxxx68x35xxxx 1GB DIMM DDR2 667MT/s      | 1        | 0.93%   |
| Kingston RAM Module 2GB DIMM DDR 667MT/s                 | 1        | 0.93%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 0.93%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 1        | 0.93%   |
| Kingston RAM KHX2933C15D4/8GX 8192MB DIMM DDR4 2933MT/s  | 1        | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 46.99%  |
| DDR3    | 33       | 39.76%  |
| DDR2    | 5        | 6.02%   |
| Unknown | 3        | 3.61%   |
| SDRAM   | 2        | 2.41%   |
| DDR     | 1        | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 74       | 90.24%  |
| SODIMM | 8        | 9.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 35       | 38.04%  |
| 4096  | 24       | 26.09%  |
| 2048  | 16       | 17.39%  |
| 16384 | 13       | 14.13%  |
| 32768 | 3        | 3.26%   |
| 1024  | 1        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 19       | 19.59%  |
| 1333    | 13       | 13.4%   |
| 2133    | 8        | 8.25%   |
| 3600    | 7        | 7.22%   |
| 2667    | 6        | 6.19%   |
| 3466    | 5        | 5.15%   |
| 3200    | 5        | 5.15%   |
| 2400    | 4        | 4.12%   |
| 667     | 4        | 4.12%   |
| 2933    | 3        | 3.09%   |
| 2666    | 3        | 3.09%   |
| 1866    | 3        | 3.09%   |
| 1334    | 2        | 2.06%   |
| 1066    | 2        | 2.06%   |
| 800     | 2        | 2.06%   |
| Unknown | 2        | 2.06%   |
| 4000    | 1        | 1.03%   |
| 3800    | 1        | 1.03%   |
| 3733    | 1        | 1.03%   |
| 3666    | 1        | 1.03%   |
| 3400    | 1        | 1.03%   |
| 3134    | 1        | 1.03%   |
| 3000    | 1        | 1.03%   |
| 2800    | 1        | 1.03%   |
| 1067    | 1        | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 3        | 30%     |
| Seiko Epson         | 2        | 20%     |
| Hewlett-Packard     | 2        | 20%     |
| Brother Industries  | 2        | 20%     |
| QinHeng Electronics | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Brother HL-1200 series   | 2        | 20%     |
| Seiko Epson Printer      | 1        | 10%     |
| Seiko Epson L3150 Series | 1        | 10%     |
| QinHeng CH340S           | 1        | 10%     |
| HP Deskjet 4640 series   | 1        | 10%     |
| HP Deskjet 4620 series   | 1        | 10%     |
| Canon PIXMA MP250        | 1        | 10%     |
| Canon G2000 series       | 1        | 10%     |
| Canon G1000 series       | 1        | 10%     |

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
| Logitech                      | 7        | 15.22%  |
| Chicony Electronics           | 6        | 13.04%  |
| Generalplus Technology        | 5        | 10.87%  |
| Apple                         | 4        | 8.7%    |
| Sunplus Innovation Technology | 3        | 6.52%   |
| Microdia                      | 3        | 6.52%   |
| Microsoft                     | 2        | 4.35%   |
| Lenovo                        | 2        | 4.35%   |
| Jieli Technology              | 2        | 4.35%   |
| Alcor Micro                   | 2        | 4.35%   |
| Z-Star Microelectronics       | 1        | 2.17%   |
| YGTek                         | 1        | 2.17%   |
| Unknown                       | 1        | 2.17%   |
| SN0002                        | 1        | 2.17%   |
| Realtek Semiconductor         | 1        | 2.17%   |
| OmniVision Technologies       | 1        | 2.17%   |
| MacroSilicon                  | 1        | 2.17%   |
| KYE Systems (Mouse Systems)   | 1        | 2.17%   |
| AVerMedia Technologies        | 1        | 2.17%   |
| Arkmicro Technologies         | 1        | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Generalplus GENERAL WEBCAM                    | 5        | 10.87%  |
| Logitech C922 Pro Stream Webcam               | 4        | 8.7%    |
| Apple iPhone5/5C/5S/6                         | 4        | 8.7%    |
| Chicony HP 0.3MP Webcam                       | 3        | 6.52%   |
| Sunplus HD 720P webcam                        | 2        | 4.35%   |
| Jieli USB PHY 2.0                             | 2        | 4.35%   |
| Z-Star Integrated Camera                      | 1        | 2.17%   |
| YGTek Webcam                                  | 1        | 2.17%   |
| Unknown HD camera                             | 1        | 2.17%   |
| Sunplus Aukey-PC-LM1E Camera                  | 1        | 2.17%   |
| SN0002 1080P Web Camera                       | 1        | 2.17%   |
| Realtek NexiGo N660P FHD Webcam               | 1        | 2.17%   |
| OmniVision OV511+ Webcam                      | 1        | 2.17%   |
| Microsoft MicrosoftÂ LifeCam Studio          | 1        | 2.17%   |
| Microsoft LifeCam VX-800                      | 1        | 2.17%   |
| Microdia Webcam Vitade AF                     | 1        | 2.17%   |
| Microdia USB camera                           | 1        | 2.17%   |
| Microdia USB 2.0 Camera                       | 1        | 2.17%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 2.17%   |
| Logitech Webcam C270                          | 1        | 2.17%   |
| Logitech Webcam C210                          | 1        | 2.17%   |
| Logitech Webcam C170                          | 1        | 2.17%   |
| Lenovo FHD Webcam Audio                       | 1        | 2.17%   |
| Lenovo 500 RGB Camera                         | 1        | 2.17%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 2.17%   |
| Chicony HP High Definition 1MP Webcam         | 1        | 2.17%   |
| Chicony HP 1.0MP High Definition Webcam       | 1        | 2.17%   |
| Chicony CNF8050 Webcam                        | 1        | 2.17%   |
| AVerMedia Live Streamer CAM 313               | 1        | 2.17%   |
| Arkmicro USB2.0 PC CAMERA                     | 1        | 2.17%   |
| Alcor Micro USB Video Device                  | 1        | 2.17%   |
| Alcor Micro USB 2.0 PC Camera                 | 1        | 2.17%   |

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
| 0     | 167      | 84.77%  |
| 1     | 26       | 13.2%   |
| 2     | 4        | 2.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 11       | 34.38%  |
| Graphics card            | 8        | 25%     |
| Unassigned class         | 4        | 12.5%   |
| Network                  | 2        | 6.25%   |
| Communication controller | 2        | 6.25%   |
| Sound                    | 1        | 3.13%   |
| Multimedia controller    | 1        | 3.13%   |
| Firewire controller      | 1        | 3.13%   |
| Camera                   | 1        | 3.13%   |
| Bluetooth                | 1        | 3.13%   |

