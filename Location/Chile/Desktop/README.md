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

Total: 254

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| ASUSTek       | PRIME H410M-E               | [a8ba9467c8](https://linux-hardware.org/?probe=a8ba9467c8) | Mar 27, 2022 |
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
| MSI           | B450 TOMAHAWK MAX II        | [7aeab73b07](https://linux-hardware.org/?probe=7aeab73b07) | Nov 21, 2021 |
| HP            | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| MSI           | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [33e45a8fe9](https://linux-hardware.org/?probe=33e45a8fe9) | Oct 21, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| Nvidia        | NF-MCP61                    | [666f204c08](https://linux-hardware.org/?probe=666f204c08) | Oct 18, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | [8f7c7a493b](https://linux-hardware.org/?probe=8f7c7a493b) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-P                | [36e45017ff](https://linux-hardware.org/?probe=36e45017ff) | Oct 14, 2021 |
| ASUSTek       | PRIME Z590-P                | [36d8e83f29](https://linux-hardware.org/?probe=36d8e83f29) | Oct 11, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [665206cf21](https://linux-hardware.org/?probe=665206cf21) | Oct 08, 2021 |
| Intel         | DG41WV AAE90316-103         | [0055a963ef](https://linux-hardware.org/?probe=0055a963ef) | Sep 30, 2021 |
| Gigabyte      | A520M DS3H                  | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LX                  | [7360f8d859](https://linux-hardware.org/?probe=7360f8d859) | Sep 23, 2021 |
| Huanan        | X79 249PC V2.3              | [feb9cf5a3f](https://linux-hardware.org/?probe=feb9cf5a3f) | Sep 20, 2021 |
| Huanan        | X79 249PC V2.3              | [0025ab8888](https://linux-hardware.org/?probe=0025ab8888) | Sep 20, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
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
| ASUSTek       | TUF GAMING B460M-PLUS       | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | [f6049274c5](https://linux-hardware.org/?probe=f6049274c5) | Aug 27, 2021 |
| Gigabyte      | H97M-D3H                    | [a2afd00e64](https://linux-hardware.org/?probe=a2afd00e64) | Aug 26, 2021 |
| Dell          | 0GDG8Y A00                  | [2a0bf4d1a9](https://linux-hardware.org/?probe=2a0bf4d1a9) | Aug 21, 2021 |
| ASUSTek       | TUF GAMING B460M-PLUS       | [0eb2abca1d](https://linux-hardware.org/?probe=0eb2abca1d) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H V2               | [9c25f25e8f](https://linux-hardware.org/?probe=9c25f25e8f) | Aug 16, 2021 |
| Pegatron      | 2ADC                        | [48cc7f548e](https://linux-hardware.org/?probe=48cc7f548e) | Aug 13, 2021 |
| MSI           | B75MA-E33                   | [8a1743cb75](https://linux-hardware.org/?probe=8a1743cb75) | Aug 10, 2021 |
| ASUSTek       | TUF GAMING B450M-PLUS II    | [482c64a9c9](https://linux-hardware.org/?probe=482c64a9c9) | Aug 03, 2021 |
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
| ASUSTek       | TUF GAMING X570-PLUS        | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| MSI           | A75MA-G55                   | [3611191f22](https://linux-hardware.org/?probe=3611191f22) | Jun 30, 2021 |
| Intel         | X79 V2.72B                  | [c78b66e96e](https://linux-hardware.org/?probe=c78b66e96e) | Jun 25, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Unknown       | Intel X79                   | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| MSI           | 970A-G46                    | [f7b1001ef1](https://linux-hardware.org/?probe=f7b1001ef1) | Jun 13, 2021 |
| Intel         | DZ77GA-70K AAG39009-401     | [a88c5c7685](https://linux-hardware.org/?probe=a88c5c7685) | Jun 09, 2021 |
| ASUSTek       | PRIME X570-P                | [587e4453b3](https://linux-hardware.org/?probe=587e4453b3) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [86060380c8](https://linux-hardware.org/?probe=86060380c8) | May 23, 2021 |
| ASUSTek       | P5K3 Deluxe                 | [458525ba70](https://linux-hardware.org/?probe=458525ba70) | May 22, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [0be7d156c5](https://linux-hardware.org/?probe=0be7d156c5) | May 17, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [493edc40c4](https://linux-hardware.org/?probe=493edc40c4) | May 15, 2021 |
| Intel         | YL-3160L2                   | [c282d94246](https://linux-hardware.org/?probe=c282d94246) | May 13, 2021 |
| Lenovo        | Board                       | [a53c13a5c9](https://linux-hardware.org/?probe=a53c13a5c9) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | [1fba25dbcf](https://linux-hardware.org/?probe=1fba25dbcf) | May 12, 2021 |
| MSI           | X58 PLATINUM SLI            | [c71715672c](https://linux-hardware.org/?probe=c71715672c) | May 12, 2021 |
| Unknown       | Unknown                     | [1dc7094a4d](https://linux-hardware.org/?probe=1dc7094a4d) | May 09, 2021 |
| HP            | 339A                        | [c103096e94](https://linux-hardware.org/?probe=c103096e94) | May 09, 2021 |
| HP            | 339A                        | [1b94801e8b](https://linux-hardware.org/?probe=1b94801e8b) | May 09, 2021 |
| Unknown       | Unknown                     | [0c2f6b27a9](https://linux-hardware.org/?probe=0c2f6b27a9) | May 08, 2021 |
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
| HP            | 2ADE                        | [abdbd9d964](https://linux-hardware.org/?probe=abdbd9d964) | Feb 02, 2021 |
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
| Dell          | 0GDG8Y A00                  | [733982af78](https://linux-hardware.org/?probe=733982af78) | Jul 12, 2020 |
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
| HP            | 0AA8h                       | [7688d6cfd0](https://linux-hardware.org/?probe=7688d6cfd0) | Jun 05, 2020 |
| HP            | 0AA8h                       | [1ee6fa5fb7](https://linux-hardware.org/?probe=1ee6fa5fb7) | Jun 03, 2020 |
| HP            | 0AA8h                       | [3226f7a8da](https://linux-hardware.org/?probe=3226f7a8da) | Jun 03, 2020 |
| Elo TouchS... | ESY1XDX                     | [467adf2413](https://linux-hardware.org/?probe=467adf2413) | Jun 01, 2020 |
| Gigabyte      | 970A-UD3P                   | [6661e20292](https://linux-hardware.org/?probe=6661e20292) | May 28, 2020 |
| Gigabyte      | GA-MA790FX-DS5              | [bc3ed232f3](https://linux-hardware.org/?probe=bc3ed232f3) | May 28, 2020 |
| Unknown       | Unknown                     | [2049e110df](https://linux-hardware.org/?probe=2049e110df) | May 27, 2020 |
| Unknown       | Unknown                     | [4d13b52bae](https://linux-hardware.org/?probe=4d13b52bae) | May 23, 2020 |
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
| HP            | 0AA8h                       | [14723b2572](https://linux-hardware.org/?probe=14723b2572) | May 26, 2019 |
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


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Ubuntu 20.04         | 22       | 12.57%  |
| Ubuntu 18.04         | 19       | 10.86%  |
| Arch                 | 10       | 5.71%   |
| Ubuntu 19.04         | 7        | 4%      |
| OpenMandriva 4.2     | 7        | 4%      |
| Linux Mint 20.1      | 6        | 3.43%   |
| Zorin 15             | 5        | 2.86%   |
| Pop!_OS 20.10        | 5        | 2.86%   |
| Ubuntu 21.04         | 4        | 2.29%   |
| Manjaro              | 4        | 2.29%   |
| Fedora 34            | 4        | 2.29%   |
| Zorin 16             | 3        | 1.71%   |
| Ubuntu 21.10         | 3        | 1.71%   |
| Ubuntu 19.10         | 3        | 1.71%   |
| Linux Mint 20        | 3        | 1.71%   |
| Linux Mint 19.3      | 3        | 1.71%   |
| Kubuntu 20.04        | 3        | 1.71%   |
| KDE neon 20.04       | 3        | 1.71%   |
| Fedora 35            | 3        | 1.71%   |
| Fedora 33            | 3        | 1.71%   |
| Fedora 32            | 3        | 1.71%   |
| Debian Testing       | 3        | 1.71%   |
| Ubuntu 20.10         | 2        | 1.14%   |
| Ubuntu 18.10         | 2        | 1.14%   |
| Ubuntu 16.04         | 2        | 1.14%   |
| Pop!_OS 21.10        | 2        | 1.14%   |
| Pop!_OS 20.04        | 2        | 1.14%   |
| Manjaro 21.0         | 2        | 1.14%   |
| Linux Mint 20.2      | 2        | 1.14%   |
| Linux Mint 19.2      | 2        | 1.14%   |
| KDE neon 18.04       | 2        | 1.14%   |
| Debian 11            | 2        | 1.14%   |
| ArcoLinux Rolling    | 2        | 1.14%   |
| Arch Rolling         | 2        | 1.14%   |
| Zorin 12             | 1        | 0.57%   |
| Ubuntu MATE 21.04    | 1        | 0.57%   |
| Ubuntu MATE 20.04    | 1        | 0.57%   |
| Ubuntu MATE 18.04    | 1        | 0.57%   |
| Ubuntu Budgie 20.04  | 1        | 0.57%   |
| ROSA R10             | 1        | 0.57%   |
| Pop!_OS 21.04        | 1        | 0.57%   |
| OpenMandriva 4.50    | 1        | 0.57%   |
| OpenMandriva 4.3     | 1        | 0.57%   |
| Manjaro 21.0.1       | 1        | 0.57%   |
| Lubuntu 18.04        | 1        | 0.57%   |
| LMDE 4               | 1        | 0.57%   |
| Linux Mint 20.3      | 1        | 0.57%   |
| Linux Mint 19.1      | 1        | 0.57%   |
| Linux Mint 19        | 1        | 0.57%   |
| Linux Lite 5.8       | 1        | 0.57%   |
| Kubuntu 21.10        | 1        | 0.57%   |
| Kali 2022.2          | 1        | 0.57%   |
| Gentoo 2.6           | 1        | 0.57%   |
| Garuda Linux Soaring | 1        | 0.57%   |
| Endless 3.5.3        | 1        | 0.57%   |
| EndeavourOS Rolling  | 1        | 0.57%   |
| Elementary 6         | 1        | 0.57%   |
| Clear Linux 35320    | 1        | 0.57%   |
| Clear Linux 35110    | 1        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 63       | 37.28%  |
| Linux Mint    | 18       | 10.65%  |
| Fedora        | 12       | 7.1%    |
| Arch          | 12       | 7.1%    |
| Pop!_OS       | 10       | 5.92%   |
| Zorin         | 9        | 5.33%   |
| OpenMandriva  | 8        | 4.73%   |
| Manjaro       | 7        | 4.14%   |
| KDE neon      | 5        | 2.96%   |
| Debian        | 5        | 2.96%   |
| Kubuntu       | 4        | 2.37%   |
| Ubuntu MATE   | 2        | 1.18%   |
| ArcoLinux     | 2        | 1.18%   |
| Ubuntu Budgie | 1        | 0.59%   |
| ROSA          | 1        | 0.59%   |
| Lubuntu       | 1        | 0.59%   |
| LMDE          | 1        | 0.59%   |
| Linux Lite    | 1        | 0.59%   |
| Kali          | 1        | 0.59%   |
| Gentoo        | 1        | 0.59%   |
| Garuda Linux  | 1        | 0.59%   |
| Endless       | 1        | 0.59%   |
| EndeavourOS   | 1        | 0.59%   |
| Elementary    | 1        | 0.59%   |
| Clear Linux   | 1        | 0.59%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 6        | 3.23%   |
| 5.10.14-desktop-1omv4002 | 6        | 3.23%   |
| 5.9.16-1-MANJARO         | 4        | 2.15%   |
| 5.0.0-13-generic         | 4        | 2.15%   |
| 5.4.0-77-generic         | 3        | 1.61%   |
| 5.4.0-33-generic         | 3        | 1.61%   |
| 5.4.0-26-generic         | 3        | 1.61%   |
| 5.11.0-7614-generic      | 3        | 1.61%   |
| 4.18.0-18-generic        | 3        | 1.61%   |
| 5.8.0-59-generic         | 2        | 1.08%   |
| 5.8.0-48-generic         | 2        | 1.08%   |
| 5.4.0-88-generic         | 2        | 1.08%   |
| 5.4.0-74-generic         | 2        | 1.08%   |
| 5.4.0-70-generic         | 2        | 1.08%   |
| 5.4.0-65-generic         | 2        | 1.08%   |
| 5.4.0-52-generic         | 2        | 1.08%   |
| 5.4.0-47-generic         | 2        | 1.08%   |
| 5.4.0-29-generic         | 2        | 1.08%   |
| 5.3.0-53-generic         | 2        | 1.08%   |
| 5.13.0-39-generic        | 2        | 1.08%   |
| 5.11.0-41-generic        | 2        | 1.08%   |
| 5.11.0-34-generic        | 2        | 1.08%   |
| 5.11.0-27-generic        | 2        | 1.08%   |
| 5.11.0-18-generic        | 2        | 1.08%   |
| 4.18.0-20-generic        | 2        | 1.08%   |
| 4.18.0-17-generic        | 2        | 1.08%   |
| 4.18.0-15-generic        | 2        | 1.08%   |
| 4.15.0-43-generic        | 2        | 1.08%   |
| 4.15.0-112-generic       | 2        | 1.08%   |
| 5.9.8-arch1-1            | 1        | 0.54%   |
| 5.9.16-200.fc33.x86_64   | 1        | 0.54%   |
| 5.9.1-050901-lowlatency  | 1        | 0.54%   |
| 5.8.12-xanmod1           | 1        | 0.54%   |
| 5.8.12-20-tkg-cfs        | 1        | 0.54%   |
| 5.8.0-7642-generic       | 1        | 0.54%   |
| 5.8.0-7625-generic       | 1        | 0.54%   |
| 5.8.0-63-generic         | 1        | 0.54%   |
| 5.8.0-50-generic         | 1        | 0.54%   |
| 5.8.0-44-generic         | 1        | 0.54%   |
| 5.8.0-43-generic         | 1        | 0.54%   |
| 5.8.0-41-generic         | 1        | 0.54%   |
| 5.7.6-12-tkg-bmq         | 1        | 0.54%   |
| 5.7.10-201.fc32.x86_64   | 1        | 0.54%   |
| 5.6.6-300.fc32.x86_64    | 1        | 0.54%   |
| 5.6.18-300.fc32.x86_64   | 1        | 0.54%   |
| 5.4.94-1-lts             | 1        | 0.54%   |
| 5.4.0-99-generic         | 1        | 0.54%   |
| 5.4.0-91-generic         | 1        | 0.54%   |
| 5.4.0-84-generic         | 1        | 0.54%   |
| 5.4.0-81-generic         | 1        | 0.54%   |
| 5.4.0-73-generic         | 1        | 0.54%   |
| 5.4.0-72-generic         | 1        | 0.54%   |
| 5.4.0-62-generic         | 1        | 0.54%   |
| 5.4.0-59-generic         | 1        | 0.54%   |
| 5.4.0-48-generic         | 1        | 0.54%   |
| 5.4.0-39-generic         | 1        | 0.54%   |
| 5.4.0-38-generic         | 1        | 0.54%   |
| 5.4.0-37-generic         | 1        | 0.54%   |
| 5.4.0-107-generic        | 1        | 0.54%   |
| 5.3.1-arch1-1-ARCH       | 1        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 38       | 21.23%  |
| 5.11.0   | 15       | 8.38%   |
| 4.15.0   | 14       | 7.82%   |
| 5.8.0    | 11       | 6.15%   |
| 5.0.0    | 10       | 5.59%   |
| 4.18.0   | 10       | 5.59%   |
| 5.3.0    | 9        | 5.03%   |
| 5.13.0   | 8        | 4.47%   |
| 5.10.14  | 6        | 3.35%   |
| 5.9.16   | 5        | 2.79%   |
| 5.8.12   | 2        | 1.12%   |
| 5.16.16  | 2        | 1.12%   |
| 5.15.0   | 2        | 1.12%   |
| 5.14.0   | 2        | 1.12%   |
| 5.13.13  | 2        | 1.12%   |
| 5.13.12  | 2        | 1.12%   |
| 5.10.0   | 2        | 1.12%   |
| 5.9.8    | 1        | 0.56%   |
| 5.9.1    | 1        | 0.56%   |
| 5.7.6    | 1        | 0.56%   |
| 5.7.10   | 1        | 0.56%   |
| 5.6.6    | 1        | 0.56%   |
| 5.6.18   | 1        | 0.56%   |
| 5.4.94   | 1        | 0.56%   |
| 5.3.1    | 1        | 0.56%   |
| 5.17.5   | 1        | 0.56%   |
| 5.17.1   | 1        | 0.56%   |
| 5.17.0   | 1        | 0.56%   |
| 5.16.7   | 1        | 0.56%   |
| 5.16.11  | 1        | 0.56%   |
| 5.15.4   | 1        | 0.56%   |
| 5.15.15  | 1        | 0.56%   |
| 5.15.11  | 1        | 0.56%   |
| 5.14.3   | 1        | 0.56%   |
| 5.14.16  | 1        | 0.56%   |
| 5.14.15  | 1        | 0.56%   |
| 5.14.12  | 1        | 0.56%   |
| 5.13.8   | 1        | 0.56%   |
| 5.13.7   | 1        | 0.56%   |
| 5.13.16  | 1        | 0.56%   |
| 5.13.10  | 1        | 0.56%   |
| 5.12.9   | 1        | 0.56%   |
| 5.12.7   | 1        | 0.56%   |
| 5.12.15  | 1        | 0.56%   |
| 5.12.0   | 1        | 0.56%   |
| 5.11.16  | 1        | 0.56%   |
| 5.11.14  | 1        | 0.56%   |
| 5.11.12  | 1        | 0.56%   |
| 5.11.10  | 1        | 0.56%   |
| 5.10.89  | 1        | 0.56%   |
| 5.10.6   | 1        | 0.56%   |
| 5.10.16  | 1        | 0.56%   |
| 5.10.105 | 1        | 0.56%   |
| 4.9.60   | 1        | 0.56%   |
| 4.19.226 | 1        | 0.56%   |
| 4.19.0   | 1        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 39       | 22.03%  |
| 5.11    | 18       | 10.17%  |
| 5.13    | 16       | 9.04%   |
| 4.15    | 14       | 7.91%   |
| 5.8     | 13       | 7.34%   |
| 5.10    | 12       | 6.78%   |
| 5.3     | 10       | 5.65%   |
| 5.0     | 10       | 5.65%   |
| 4.18    | 10       | 5.65%   |
| 5.9     | 7        | 3.95%   |
| 5.14    | 6        | 3.39%   |
| 5.15    | 5        | 2.82%   |
| 5.16    | 4        | 2.26%   |
| 5.17    | 3        | 1.69%   |
| 5.12    | 3        | 1.69%   |
| 5.7     | 2        | 1.13%   |
| 5.6     | 2        | 1.13%   |
| 4.19    | 2        | 1.13%   |
| 4.9     | 1        | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 164      | 98.2%   |
| i686   | 3        | 1.8%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 66       | 39.52%  |
| Unknown    | 32       | 19.16%  |
| KDE5       | 21       | 12.57%  |
| X-Cinnamon | 14       | 8.38%   |
| XFCE       | 12       | 7.19%   |
| KDE        | 10       | 5.99%   |
| xmonad     | 2        | 1.2%    |
| MATE       | 2        | 1.2%    |
| LXDE       | 2        | 1.2%    |
| Cinnamon   | 2        | 1.2%    |
| Pantheon   | 1        | 0.6%    |
| KDE4       | 1        | 0.6%    |
| i3         | 1        | 0.6%    |
| Budgie     | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 127      | 75.6%   |
| Unknown | 25       | 14.88%  |
| Wayland | 15       | 8.93%   |
| Tty     | 1        | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 113      | 67.26%  |
| SDDM    | 17       | 10.12%  |
| GDM     | 15       | 8.93%   |
| LightDM | 11       | 6.55%   |
| TDM     | 6        | 3.57%   |
| GDM3    | 4        | 2.38%   |
| LXDM    | 1        | 0.6%    |
| KDM     | 1        | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CL   | 83       | 49.4%   |
| en_US   | 38       | 22.62%  |
| Unknown | 33       | 19.64%  |
| es_ES   | 7        | 4.17%   |
| en_GB   | 3        | 1.79%   |
| es_MX   | 2        | 1.19%   |
| pt_BR   | 1        | 0.6%    |
| C       | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 108      | 63.53%  |
| EFI  | 62       | 36.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 132      | 78.57%  |
| Btrfs   | 15       | 8.93%   |
| Overlay | 8        | 4.76%   |
| Unknown | 7        | 4.17%   |
| Ext2    | 3        | 1.79%   |
| Zfs     | 2        | 1.19%   |
| Xfs     | 1        | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 115      | 68.45%  |
| GPT     | 36       | 21.43%  |
| MBR     | 17       | 10.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 146      | 85.88%  |
| Yes       | 24       | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 60.59%  |
| Yes       | 67       | 39.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 50       | 29.94%  |
| MSI                 | 29       | 17.37%  |
| Gigabyte Technology | 20       | 11.98%  |
| Intel               | 13       | 7.78%   |
| Hewlett-Packard     | 12       | 7.19%   |
| ECS                 | 8        | 4.79%   |
| Dell                | 5        | 2.99%   |
| ASRock              | 4        | 2.4%    |
| Unknown             | 4        | 2.4%    |
| Pegatron            | 3        | 1.8%    |
| Lenovo              | 3        | 1.8%    |
| TPV-INVENTA         | 2        | 1.2%    |
| Huanan              | 2        | 1.2%    |
| R-StyleComputers    | 1        | 0.6%    |
| Quanta              | 1        | 0.6%    |
| PCPartner           | 1        | 0.6%    |
| Nvidia              | 1        | 0.6%    |
| IBM                 | 1        | 0.6%    |
| HC                  | 1        | 0.6%    |
| Foxconn             | 1        | 0.6%    |
| eMachines           | 1        | 0.6%    |
| Elo TouchSystems    | 1        | 0.6%    |
| Colorful Technology | 1        | 0.6%    |
| Apple               | 1        | 0.6%    |
| AMI                 | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| ASUS All Series                           | 6        | 3.59%   |
| ASUS PRIME B450M-A                        | 4        | 2.4%    |
| Unknown                                   | 4        | 2.4%    |
| MSI MS-7817                               | 3        | 1.8%    |
| MSI MS-7788                               | 3        | 1.8%    |
| MSI Pro 3000/3080                         | 2        | 1.2%    |
| MSI MS-7A65                               | 2        | 1.2%    |
| HP Compaq Pro 6300 SFF                    | 2        | 1.2%    |
| HP Compaq Pro 4300 SFF PC                 | 2        | 1.2%    |
| Gigabyte B450M DS3H V2                    | 2        | 1.2%    |
| Gigabyte B450 AORUS PRO WIFI              | 2        | 1.2%    |
| ECS A960M-MV                              | 2        | 1.2%    |
| ECS A740GM-M                              | 2        | 1.2%    |
| ASUS TUF Gaming X570-PLUS                 | 2        | 1.2%    |
| ASUS SABERTOOTH 990FX R2.0                | 2        | 1.2%    |
| ASUS PRIME H410M-E                        | 2        | 1.2%    |
| ASUS PRIME A320M-K                        | 2        | 1.2%    |
| ASUS M5A99X EVO                           | 2        | 1.2%    |
| TPV-INVENTA Pro 1005 Series All-in-One PC | 1        | 0.6%    |
| TPV-INVENTA CQ1-3130LA                    | 1        | 0.6%    |
| R-StyleComputers ALICON AI2S-A21 00.69    | 1        | 0.6%    |
| Quanta 120-1016la                         | 1        | 0.6%    |
| Pegatron 9100                             | 1        | 0.6%    |
| Pegatron 520-1135la                       | 1        | 0.6%    |
| Pegatron 23-d015la                        | 1        | 0.6%    |
| PCPartner G43-F71862                      | 1        | 0.6%    |
| Nvidia NF-MCP61                           | 1        | 0.6%    |
| MSI TITAN                                 | 1        | 0.6%    |
| MSI MS-7C90                               | 1        | 0.6%    |
| MSI MS-7C83                               | 1        | 0.6%    |
| MSI MS-7C31                               | 1        | 0.6%    |
| MSI MS-7C09                               | 1        | 0.6%    |
| MSI MS-7C02                               | 1        | 0.6%    |
| MSI MS-7B53                               | 1        | 0.6%    |
| MSI MS-7B28                               | 1        | 0.6%    |
| MSI MS-7B09                               | 1        | 0.6%    |
| MSI MS-7A38                               | 1        | 0.6%    |
| MSI MS-7A34                               | 1        | 0.6%    |
| MSI MS-7A15                               | 1        | 0.6%    |
| MSI MS-7846                               | 1        | 0.6%    |
| MSI MS-7808                               | 1        | 0.6%    |
| MSI MS-7721                               | 1        | 0.6%    |
| MSI MS-7696                               | 1        | 0.6%    |
| MSI MS-7693                               | 1        | 0.6%    |
| MSI MS-7522                               | 1        | 0.6%    |
| MSI MS-7379                               | 1        | 0.6%    |
| Lenovo ThinkCentre M73z 10BBA0XNCS        | 1        | 0.6%    |
| Lenovo ThinkCentre M700 10GSA05DCS        | 1        | 0.6%    |
| Lenovo ThinkCentre M55 8808E19            | 1        | 0.6%    |
| Intel YL-3160L2                           | 1        | 0.6%    |
| Intel X99                                 | 1        | 0.6%    |
| Intel X79M-S                              | 1        | 0.6%    |
| Intel X79 V2.72B                          | 1        | 0.6%    |
| Intel X64                                 | 1        | 0.6%    |
| Intel SHARKBAY                            | 1        | 0.6%    |
| Intel DZ77GA-70K AAG39009-401             | 1        | 0.6%    |
| Intel DN2820FYK H24582-204                | 1        | 0.6%    |
| Intel DH61BF AAG81311-101                 | 1        | 0.6%    |
| Intel DH55PJ AAE93812-301                 | 1        | 0.6%    |
| Intel DG41WV AAE90316-103                 | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 13       | 7.78%   |
| HP Compaq               | 6        | 3.59%   |
| ASUS TUF                | 6        | 3.59%   |
| ASUS All                | 6        | 3.59%   |
| Unknown                 | 4        | 2.4%    |
| MSI MS-7817             | 3        | 1.8%    |
| MSI MS-7788             | 3        | 1.8%    |
| Lenovo ThinkCentre      | 3        | 1.8%    |
| Gigabyte B450M          | 3        | 1.8%    |
| ASUS M5A78L-M           | 3        | 1.8%    |
| MSI Pro                 | 2        | 1.2%    |
| MSI MS-7A65             | 2        | 1.2%    |
| Huanan X79              | 2        | 1.2%    |
| HP EliteDesk            | 2        | 1.2%    |
| Gigabyte B450           | 2        | 1.2%    |
| ECS A960M-MV            | 2        | 1.2%    |
| ECS A740GM-M            | 2        | 1.2%    |
| Dell OptiPlex           | 2        | 1.2%    |
| ASUS SABERTOOTH         | 2        | 1.2%    |
| ASUS ROG                | 2        | 1.2%    |
| ASUS M5A99X             | 2        | 1.2%    |
| TPV-INVENTA Pro         | 1        | 0.6%    |
| TPV-INVENTA CQ1-3130LA  | 1        | 0.6%    |
| R-StyleComputers ALICON | 1        | 0.6%    |
| Quanta 120-1016la       | 1        | 0.6%    |
| Pegatron 9100           | 1        | 0.6%    |
| Pegatron 520-1135la     | 1        | 0.6%    |
| Pegatron 23-d015la      | 1        | 0.6%    |
| PCPartner G43-F71862    | 1        | 0.6%    |
| Nvidia NF-MCP61         | 1        | 0.6%    |
| MSI TITAN               | 1        | 0.6%    |
| MSI MS-7C90             | 1        | 0.6%    |
| MSI MS-7C83             | 1        | 0.6%    |
| MSI MS-7C31             | 1        | 0.6%    |
| MSI MS-7C09             | 1        | 0.6%    |
| MSI MS-7C02             | 1        | 0.6%    |
| MSI MS-7B53             | 1        | 0.6%    |
| MSI MS-7B28             | 1        | 0.6%    |
| MSI MS-7B09             | 1        | 0.6%    |
| MSI MS-7A38             | 1        | 0.6%    |
| MSI MS-7A34             | 1        | 0.6%    |
| MSI MS-7A15             | 1        | 0.6%    |
| MSI MS-7846             | 1        | 0.6%    |
| MSI MS-7808             | 1        | 0.6%    |
| MSI MS-7721             | 1        | 0.6%    |
| MSI MS-7696             | 1        | 0.6%    |
| MSI MS-7693             | 1        | 0.6%    |
| MSI MS-7522             | 1        | 0.6%    |
| MSI MS-7379             | 1        | 0.6%    |
| Intel YL-3160L2         | 1        | 0.6%    |
| Intel X99               | 1        | 0.6%    |
| Intel X79M-S            | 1        | 0.6%    |
| Intel X79               | 1        | 0.6%    |
| Intel X64               | 1        | 0.6%    |
| Intel SHARKBAY          | 1        | 0.6%    |
| Intel DZ77GA-70K        | 1        | 0.6%    |
| Intel DN2820FYK         | 1        | 0.6%    |
| Intel DH61BF            | 1        | 0.6%    |
| Intel DH55PJ            | 1        | 0.6%    |
| Intel DG41WV            | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 20       | 11.98%  |
| 2012 | 20       | 11.98%  |
| 2018 | 17       | 10.18%  |
| 2014 | 15       | 8.98%   |
| 2013 | 15       | 8.98%   |
| 2011 | 13       | 7.78%   |
| 2019 | 11       | 6.59%   |
| 2008 | 11       | 6.59%   |
| 2007 | 11       | 6.59%   |
| 2017 | 8        | 4.79%   |
| 2010 | 8        | 4.79%   |
| 2016 | 6        | 3.59%   |
| 2009 | 5        | 2.99%   |
| 2021 | 3        | 1.8%    |
| 2015 | 3        | 1.8%    |
| 2005 | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 167      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 164      | 98.2%   |
| Enabled  | 3        | 1.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 167      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 41       | 24.55%  |
| 16.01-24.0  | 32       | 19.16%  |
| 3.01-4.0    | 31       | 18.56%  |
| 4.01-8.0    | 25       | 14.97%  |
| 32.01-64.0  | 21       | 12.57%  |
| 1.01-2.0    | 10       | 5.99%   |
| 24.01-32.0  | 3        | 1.8%    |
| 2.01-3.0    | 3        | 1.8%    |
| 64.01-256.0 | 1        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 68       | 38.42%  |
| 2.01-3.0  | 50       | 28.25%  |
| 4.01-8.0  | 26       | 14.69%  |
| 3.01-4.0  | 17       | 9.6%    |
| 8.01-16.0 | 9        | 5.08%   |
| 0.51-1.0  | 5        | 2.82%   |
| 0.01-0.5  | 2        | 1.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 37.28%  |
| 2      | 58       | 34.32%  |
| 3      | 25       | 14.79%  |
| 4      | 17       | 10.06%  |
| 5      | 3        | 1.78%   |
| 7      | 1        | 0.59%   |
| 6      | 1        | 0.59%   |
| 0      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 54.49%  |
| Yes       | 76       | 45.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 166      | 99.4%   |
| No        | 1        | 0.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 87       | 52.1%   |
| Yes       | 80       | 47.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 71.01%  |
| Yes       | 49       | 28.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Chile   | 167      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Santiago            | 51       | 29.31%  |
| Maipu               | 11       | 6.32%   |
| Las Condes          | 9        | 5.17%   |
| Nunoa               | 8        | 4.6%    |
| ViГ±a del Mar     | 6        | 3.45%   |
| Temuco              | 6        | 3.45%   |
| Antofagasta         | 5        | 2.87%   |
| La Florida          | 4        | 2.3%    |
| ConcepciГіn       | 4        | 2.3%    |
| ValparaГ­so       | 3        | 1.72%   |
| Valdivia            | 3        | 1.72%   |
| Talca               | 3        | 1.72%   |
| San Miguel          | 3        | 1.72%   |
| Puente Alto         | 3        | 1.72%   |
| Providencia         | 3        | 1.72%   |
| Port Montt          | 3        | 1.72%   |
| Penalolen           | 3        | 1.72%   |
| Osorno              | 3        | 1.72%   |
| La Serena           | 3        | 1.72%   |
| Chillan             | 3        | 1.72%   |
| ValparaÃ­so       | 2        | 1.15%   |
| Recoleta            | 2        | 1.15%   |
| Rancagua            | 2        | 1.15%   |
| CuricГі           | 2        | 1.15%   |
| Central             | 2        | 1.15%   |
| Vitacura            | 1        | 0.57%   |
| Villa Alemana       | 1        | 0.57%   |
| Villa Alegre        | 1        | 0.57%   |
| ViÃ±a del Mar     | 1        | 0.57%   |
| Talcahuano          | 1        | 0.57%   |
| Talagante           | 1        | 0.57%   |
| San Pedro de la Paz | 1        | 0.57%   |
| San Bernardo        | 1        | 0.57%   |
| QuilpuГ©          | 1        | 0.57%   |
| Quillota            | 1        | 0.57%   |
| Ovalle              | 1        | 0.57%   |
| Melipilla           | 1        | 0.57%   |
| Macul               | 1        | 0.57%   |
| Los Ãngeles      | 1        | 0.57%   |
| Los Ángeles        | 1        | 0.57%   |
| Los Andes           | 1        | 0.57%   |
| La Granja           | 1        | 0.57%   |
| La Cisterna         | 1        | 0.57%   |
| Hualpen             | 1        | 0.57%   |
| Espejo              | 1        | 0.57%   |
| El Monte            | 1        | 0.57%   |
| El Bosque           | 1        | 0.57%   |
| Conchali            | 1        | 0.57%   |
| ConcepciÃ³n       | 1        | 0.57%   |
| Colina              | 1        | 0.57%   |
| Chiguayante         | 1        | 0.57%   |
| Castro              | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 70       | 116    | 23.65%  |
| Seagate                   | 60       | 76     | 20.27%  |
| Kingston                  | 31       | 38     | 10.47%  |
| Toshiba                   | 26       | 27     | 8.78%   |
| Crucial                   | 18       | 23     | 6.08%   |
| Samsung Electronics       | 15       | 18     | 5.07%   |
| Hitachi                   | 13       | 16     | 4.39%   |
| Silicon Motion            | 8        | 8      | 2.7%    |
| Sandisk                   | 6        | 7      | 2.03%   |
| Unknown                   | 4        | 5      | 1.35%   |
| Corsair                   | 4        | 9      | 1.35%   |
| China                     | 4        | 6      | 1.35%   |
| XrayDisk                  | 3        | 3      | 1.01%   |
| Micron Technology         | 3        | 6      | 1.01%   |
| A-DATA Technology         | 3        | 3      | 1.01%   |
| XPG                       | 2        | 3      | 0.68%   |
| Realtek Semiconductor     | 2        | 2      | 0.68%   |
| Micron/Crucial Technology | 2        | 5      | 0.68%   |
| MAXTOR                    | 2        | 2      | 0.68%   |
| Lexar                     | 2        | 2      | 0.68%   |
| KingSpec                  | 2        | 2      | 0.68%   |
| walram                    | 1        | 2      | 0.34%   |
| Transcend                 | 1        | 1      | 0.34%   |
| StoreJet                  | 1        | 1      | 0.34%   |
| SK Hynix                  | 1        | 1      | 0.34%   |
| Patriot                   | 1        | 1      | 0.34%   |
| OCZ                       | 1        | 2      | 0.34%   |
| Netac                     | 1        | 1      | 0.34%   |
| Mass                      | 1        | 1      | 0.34%   |
| JMicron                   | 1        | 1      | 0.34%   |
| JASTER                    | 1        | 2      | 0.34%   |
| Intenso                   | 1        | 1      | 0.34%   |
| Gigabyte Technology       | 1        | 1      | 0.34%   |
| BIWIN                     | 1        | 1      | 0.34%   |
| ASMT                      | 1        | 1      | 0.34%   |
| asmedia                   | 1        | 2      | 0.34%   |
| Apple                     | 1        | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 11       | 3.27%   |
| Toshiba HDWD110 1TB                  | 8        | 2.38%   |
| Toshiba DT01ACA100 1TB               | 8        | 2.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 6        | 1.79%   |
| WDC WD10EZEX-08WN4A0 1TB             | 6        | 1.79%   |
| Kingston SA400S37120G 120GB SSD      | 6        | 1.79%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 5        | 1.49%   |
| WDC WD5000AAKX-001CA0 500GB          | 5        | 1.49%   |
| Seagate ST3500418AS 500GB            | 5        | 1.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 4        | 1.19%   |
| WDC WD10EZEX-00BN5A0 1TB             | 4        | 1.19%   |
| Seagate ST3320418AS 320GB            | 4        | 1.19%   |
| Seagate ST1000DM010-2EP102 1TB       | 4        | 1.19%   |
| Kingston SA400S37240G 240GB SSD      | 4        | 1.19%   |
| Toshiba DT01ACA050 500GB             | 3        | 0.89%   |
| Seagate ST500LT012-9WS142 500GB      | 3        | 0.89%   |
| Seagate ST500LT012-1DG142 500GB      | 3        | 0.89%   |
| Sandisk NVMe SSD Drive 500GB         | 3        | 0.89%   |
| Sandisk NVMe SSD Drive 1TB           | 3        | 0.89%   |
| Kingston SUV400S37240G 240GB SSD     | 3        | 0.89%   |
| Kingston SA400S37480G 480GB SSD      | 3        | 0.89%   |
| Hitachi HDS721050CLA362 500GB        | 3        | 0.89%   |
| Hitachi HDS721032CLA362 320GB        | 3        | 0.89%   |
| Crucial CT500MX500SSD1 500GB         | 3        | 0.89%   |
| XPG SPECTRIX S40G 4TB                | 2        | 0.6%    |
| WDC WDS500G3X0C-00SJG0 500GB         | 2        | 0.6%    |
| WDC WDS240G1G0A-00SS50 240GB SSD     | 2        | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2        | 0.6%    |
| WDC WDS100T2B0C-00PXH0 1TB           | 2        | 0.6%    |
| WDC WD20EARX-00PASB0 2TB             | 2        | 0.6%    |
| WDC WD2003FZEX-00Z4SA0 2TB           | 2        | 0.6%    |
| WDC WD1003FBYZ-010FB0 1TB            | 2        | 0.6%    |
| Toshiba HDWD105 500GB                | 2        | 0.6%    |
| Silicon Motion NVMe SSD Drive 512GB  | 2        | 0.6%    |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.6%    |
| Seagate ST9640320AS 640GB            | 2        | 0.6%    |
| Seagate ST500DM002-1BC142 500GB      | 2        | 0.6%    |
| Seagate ST3500320AS 500GB            | 2        | 0.6%    |
| Seagate ST2000DM001-1ER164 2TB       | 2        | 0.6%    |
| Samsung NVMe SSD Drive 512GB         | 2        | 0.6%    |
| Micron/Crucial NVMe SSD Drive 500GB  | 2        | 0.6%    |
| Lexar 128GB SSD                      | 2        | 0.6%    |
| Kingston SV300S37A120G 120GB SSD     | 2        | 0.6%    |
| Kingston SUV400S37120G 120GB SSD     | 2        | 0.6%    |
| Kingston SKC300S37A120G 120GB SSD    | 2        | 0.6%    |
| Kingston SA400M8120G 120GB SSD       | 2        | 0.6%    |
| Crucial CT480BX500SSD1 480GB         | 2        | 0.6%    |
| Crucial CT250MX500SSD1 250GB         | 2        | 0.6%    |
| Crucial CT240BX500SSD1 240GB         | 2        | 0.6%    |
| Crucial CT120BX500SSD1 120GB         | 2        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB          | 2        | 0.6%    |
| XrayDisk SSD 256GB                   | 1        | 0.3%    |
| XrayDisk SSD 240GB                   | 1        | 0.3%    |
| XrayDisk 512GB                       | 1        | 0.3%    |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1        | 0.3%    |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1        | 0.3%    |
| WDC WDS250G2B0A 250GB SSD            | 1        | 0.3%    |
| WDC WDS250G1B0C-00S6U0 250GB         | 1        | 0.3%    |
| WDC WDS240G2G0C-00AJM0 240GB         | 1        | 0.3%    |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 60       | 76     | 37.04%  |
| WDC                 | 54       | 82     | 33.33%  |
| Toshiba             | 26       | 27     | 16.05%  |
| Hitachi             | 13       | 16     | 8.02%   |
| Samsung Electronics | 4        | 6      | 2.47%   |
| MAXTOR              | 2        | 2      | 1.23%   |
| ASMT                | 1        | 1      | 0.62%   |
| asmedia             | 1        | 2      | 0.62%   |
| Apple               | 1        | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 29       | 32     | 29.29%  |
| WDC                 | 20       | 26     | 20.2%   |
| Crucial             | 18       | 22     | 18.18%  |
| Samsung Electronics | 7        | 8      | 7.07%   |
| Corsair             | 4        | 9      | 4.04%   |
| China               | 4        | 6      | 4.04%   |
| XrayDisk            | 2        | 2      | 2.02%   |
| Micron Technology   | 2        | 2      | 2.02%   |
| Lexar               | 2        | 2      | 2.02%   |
| KingSpec            | 2        | 2      | 2.02%   |
| walram              | 1        | 1      | 1.01%   |
| StoreJet            | 1        | 1      | 1.01%   |
| Patriot             | 1        | 1      | 1.01%   |
| OCZ                 | 1        | 2      | 1.01%   |
| JMicron             | 1        | 1      | 1.01%   |
| Intenso             | 1        | 1      | 1.01%   |
| Gigabyte Technology | 1        | 1      | 1.01%   |
| BIWIN               | 1        | 1      | 1.01%   |
| A-DATA Technology   | 1        | 1      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 123      | 213    | 49.4%   |
| SSD     | 81       | 121    | 32.53%  |
| NVMe    | 37       | 54     | 14.86%  |
| Unknown | 6        | 7      | 2.41%   |
| MMC     | 2        | 2      | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 159      | 331    | 77.56%  |
| NVMe | 37       | 54     | 18.05%  |
| SAS  | 7        | 10     | 3.41%   |
| MMC  | 2        | 2      | 0.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 127      | 224    | 61.35%  |
| 0.51-1.0   | 56       | 75     | 27.05%  |
| 1.01-2.0   | 16       | 23     | 7.73%   |
| 3.01-4.0   | 3        | 3      | 1.45%   |
| 2.01-3.0   | 3        | 6      | 1.45%   |
| 4.01-10.0  | 2        | 3      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 44       | 25.43%  |
| 101-250        | 33       | 19.08%  |
| 501-1000       | 21       | 12.14%  |
| 1001-2000      | 16       | 9.25%   |
| More than 3000 | 14       | 8.09%   |
| 1-20           | 13       | 7.51%   |
| 51-100         | 11       | 6.36%   |
| 2001-3000      | 10       | 5.78%   |
| 21-50          | 6        | 3.47%   |
| Unknown        | 5        | 2.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 68       | 38.42%  |
| 21-50          | 36       | 20.34%  |
| 101-250        | 17       | 9.6%    |
| 1001-2000      | 12       | 6.78%   |
| 501-1000       | 12       | 6.78%   |
| 51-100         | 10       | 5.65%   |
| 251-500        | 8        | 4.52%   |
| More than 3000 | 6        | 3.39%   |
| Unknown        | 5        | 2.82%   |
| 2001-3000      | 3        | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| XrayDisk SSD 256GB                   | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-083CA1 500GB          | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 2      | 4.76%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 1      | 4.76%   |
| WDC WD10EARS-003BB1 1TB              | 1        | 1      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB      | 1        | 1      | 4.76%   |
| Seagate ST500LM000-1EJ162-SSHD 500GB | 1        | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB      | 1        | 1      | 4.76%   |
| Seagate ST3500418AS 500GB            | 1        | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 1TB  | 1        | 1      | 4.76%   |
| Samsung Electronics HD250HJ 250GB    | 1        | 2      | 4.76%   |
| Samsung Electronics HD081GJ 80GB     | 1        | 1      | 4.76%   |
| Kingston SA400S37480G 480GB SSD      | 1        | 1      | 4.76%   |
| Kingston SA400S37240G 240GB SSD      | 1        | 1      | 4.76%   |
| Hitachi HTS547550A9E384 500GB        | 1        | 1      | 4.76%   |
| Hitachi HTS545050B9A300 500GB        | 1        | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB        | 1        | 1      | 4.76%   |
| Hitachi HDS721050CLA660 500GB        | 1        | 1      | 4.76%   |
| Hitachi HDS721032CLA362 320GB        | 1        | 1      | 4.76%   |
| A-DATA Technology SX8100NP 1TB       | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 26.32%  |
| Seagate             | 4        | 4      | 21.05%  |
| Hitachi             | 4        | 5      | 21.05%  |
| Samsung Electronics | 2        | 4      | 10.53%  |
| Kingston            | 2        | 2      | 10.53%  |
| XrayDisk            | 1        | 1      | 5.26%   |
| A-DATA Technology   | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 35.71%  |
| Seagate             | 4        | 4      | 28.57%  |
| Hitachi             | 4        | 5      | 28.57%  |
| Samsung Electronics | 1        | 3      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 18     | 70.59%  |
| SSD  | 4        | 4      | 23.53%  |
| NVMe | 1        | 1      | 5.88%   |

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
| Detected | 119      | 271    | 64.32%  |
| Works    | 49       | 102    | 26.49%  |
| Malfunc  | 16       | 23     | 8.65%   |
| Failed   | 1        | 1      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 95       | 42.99%  |
| AMD                          | 66       | 29.86%  |
| Silicon Motion               | 10       | 4.52%   |
| Sandisk                      | 10       | 4.52%   |
| JMicron Technology           | 7        | 3.17%   |
| Realtek Semiconductor        | 6        | 2.71%   |
| Marvell Technology Group     | 6        | 2.71%   |
| Samsung Electronics          | 4        | 1.81%   |
| Nvidia                       | 4        | 1.81%   |
| ASMedia Technology           | 4        | 1.81%   |
| Micron/Crucial Technology    | 3        | 1.36%   |
| Kingston Technology Company  | 2        | 0.9%    |
| VIA Technologies             | 1        | 0.45%   |
| SK Hynix                     | 1        | 0.45%   |
| Shenzhen Longsys Electronics | 1        | 0.45%   |
| Micron Technology            | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 34       | 11.64%  |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 5.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 4.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 4.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 3.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10       | 3.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 9        | 3.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.4%    |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 6        | 2.05%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 6        | 2.05%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 2.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 1.71%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 1.71%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 1.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.71%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.37%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.37%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.03%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 3        | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 3        | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.03%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 0.68%   |
| Sandisk Non-Volatile memory controller                                                  | 2        | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.68%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.68%   |
| JMicron JMB362 SATA Controller                                                          | 2        | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 0.68%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 0.68%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.68%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.68%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.68%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 0.68%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.68%   |
| AMD FCH IDE Controller                                                                  | 2        | 0.68%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.68%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 1        | 0.34%   |
| VIA VIA VT6420 SATA RAID Controller                                                     | 1        | 0.34%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.34%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.34%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 1        | 0.34%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 0.34%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.34%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.34%   |
| Nvidia MCP79 AHCI Controller                                                            | 1        | 0.34%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 130      | 58.82%  |
| IDE  | 51       | 23.08%  |
| NVMe | 37       | 16.74%  |
| RAID | 3        | 1.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 58.08%  |
| AMD    | 70       | 41.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 5        | 2.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 2.37%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 4        | 2.37%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.78%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 3        | 1.78%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 1.78%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.78%   |
| AMD E-450 APU with Radeon HD Graphics       | 3        | 1.78%   |
| AMD Athlon 3000G with Radeon Vega Graphics  | 3        | 1.78%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 2        | 1.18%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 2        | 1.18%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 1.18%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 1.18%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.18%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 1.18%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 1.18%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.18%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 2        | 1.18%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2        | 1.18%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.18%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 2        | 1.18%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.18%   |
| AMD Ryzen 9 3900XT 12-Core Processor        | 2        | 1.18%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.18%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2        | 1.18%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.18%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.18%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.18%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.18%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2        | 1.18%   |
| AMD Phenom II X6 1090T Processor            | 2        | 1.18%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.18%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 0.59%   |
| Intel Xeon CPU X3220 @ 2.40GHz              | 1        | 0.59%   |
| Intel Xeon CPU W3505 @ 2.53GHz              | 1        | 0.59%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.59%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.59%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 1        | 0.59%   |
| Intel Xeon CPU E5-2670 v2 @ 2.50GHz         | 1        | 0.59%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz         | 1        | 0.59%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 1        | 0.59%   |
| Intel Xeon CPU E31260L @ 2.40GHz            | 1        | 0.59%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz         | 1        | 0.59%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.59%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 0.59%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.59%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 0.59%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 0.59%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1        | 0.59%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 0.59%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1        | 0.59%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.59%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 0.59%   |
| Intel Pentium 4 CPU 2.93GHz                 | 1        | 0.59%   |
| Intel Core i9-10900F CPU @ 2.80GHz          | 1        | 0.59%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 0.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.59%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.59%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.59%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 26       | 15.38%  |
| Intel Xeon              | 15       | 8.88%   |
| Intel Core i7           | 14       | 8.28%   |
| AMD Ryzen 5             | 13       | 7.69%   |
| Intel Core i3           | 12       | 7.1%    |
| Intel Core 2 Duo        | 10       | 5.92%   |
| AMD FX                  | 10       | 5.92%   |
| AMD Ryzen 7             | 9        | 5.33%   |
| Intel Celeron           | 7        | 4.14%   |
| AMD A6                  | 6        | 3.55%   |
| AMD Athlon              | 5        | 2.96%   |
| Intel Pentium           | 4        | 2.37%   |
| AMD Ryzen 9             | 3        | 1.78%   |
| AMD Ryzen 3             | 3        | 1.78%   |
| AMD Phenom              | 3        | 1.78%   |
| AMD E                   | 3        | 1.78%   |
| AMD Athlon II X2        | 3        | 1.78%   |
| Intel Pentium Dual-Core | 2        | 1.18%   |
| Intel Pentium Dual      | 2        | 1.18%   |
| Intel Pentium 4         | 2        | 1.18%   |
| AMD Phenom II X6        | 2        | 1.18%   |
| AMD Athlon 64 X2        | 2        | 1.18%   |
| AMD A10                 | 2        | 1.18%   |
| Intel Pentium Gold      | 1        | 0.59%   |
| Intel Core i9           | 1        | 0.59%   |
| Intel Core 2 Quad       | 1        | 0.59%   |
| Intel Core 2            | 1        | 0.59%   |
| Intel Atom              | 1        | 0.59%   |
| AMD Ryzen Threadripper  | 1        | 0.59%   |
| AMD Phenom II X4        | 1        | 0.59%   |
| AMD Athlon X4           | 1        | 0.59%   |
| AMD Athlon II X4        | 1        | 0.59%   |
| AMD Athlon II           | 1        | 0.59%   |
| AMD A8                  | 1        | 0.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 63       | 37.28%  |
| 2       | 51       | 30.18%  |
| 6       | 17       | 10.06%  |
| 8       | 16       | 9.47%   |
| 3       | 7        | 4.14%   |
| 1       | 6        | 3.55%   |
| 12      | 4        | 2.37%   |
| 16      | 2        | 1.18%   |
| 10      | 2        | 1.18%   |
| Unknown | 1        | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 165      | 98.8%   |
| 2      | 2        | 1.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 88       | 52.38%  |
| 1       | 79       | 47.02%  |
| Unknown | 1        | 0.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 161      | 96.41%  |
| Unknown        | 4        | 2.4%    |
| 64-bit         | 1        | 0.6%    |
| 32-bit         | 1        | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 38       | 21.97%  |
| 0x306c3    | 12       | 6.94%   |
| 0x306a9    | 10       | 5.78%   |
| 0x08701021 | 9        | 5.2%    |
| 0x06000852 | 7        | 4.05%   |
| 0x206a7    | 5        | 2.89%   |
| 0x1067a    | 5        | 2.89%   |
| 0x10676    | 5        | 2.89%   |
| 0x08108109 | 5        | 2.89%   |
| 0xa0653    | 4        | 2.31%   |
| 0x6fd      | 4        | 2.31%   |
| 0x0800820d | 4        | 2.31%   |
| 0x03000027 | 4        | 2.31%   |
| 0x6fb      | 3        | 1.73%   |
| 0x306e4    | 3        | 1.73%   |
| 0x010000c8 | 3        | 1.73%   |
| 0x906ea    | 2        | 1.16%   |
| 0x906e9    | 2        | 1.16%   |
| 0x506e3    | 2        | 1.16%   |
| 0x306f2    | 2        | 1.16%   |
| 0x30678    | 2        | 1.16%   |
| 0x206d7    | 2        | 1.16%   |
| 0x106a5    | 2        | 1.16%   |
| 0x08101016 | 2        | 1.16%   |
| 0x06003106 | 2        | 1.16%   |
| 0x06001119 | 2        | 1.16%   |
| 0x0600063e | 2        | 1.16%   |
| 0x05000119 | 2        | 1.16%   |
| 0x010000bf | 2        | 1.16%   |
| 0x01000095 | 2        | 1.16%   |
| 0xf65      | 1        | 0.58%   |
| 0xf41      | 1        | 0.58%   |
| 0xa0655    | 1        | 0.58%   |
| 0x906ed    | 1        | 0.58%   |
| 0x906eb    | 1        | 0.58%   |
| 0x706a1    | 1        | 0.58%   |
| 0x6f2      | 1        | 0.58%   |
| 0x406c4    | 1        | 0.58%   |
| 0x40651    | 1        | 0.58%   |
| 0x20652    | 1        | 0.58%   |
| 0x10677    | 1        | 0.58%   |
| 0x0a50000c | 1        | 0.58%   |
| 0x0a201016 | 1        | 0.58%   |
| 0x0a201009 | 1        | 0.58%   |
| 0x08701013 | 1        | 0.58%   |
| 0x08108102 | 1        | 0.58%   |
| 0x0810100b | 1        | 0.58%   |
| 0x08001138 | 1        | 0.58%   |
| 0x08001129 | 1        | 0.58%   |
| 0x0700010f | 1        | 0.58%   |
| 0x0600611a | 1        | 0.58%   |
| 0x010000c9 | 1        | 0.58%   |
| 0x010000c7 | 1        | 0.58%   |
| 0x010000b6 | 1        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 20       | 11.9%   |
| IvyBridge     | 16       | 9.52%   |
| Penryn        | 14       | 8.33%   |
| Zen 2         | 12       | 7.14%   |
| Piledriver    | 11       | 6.55%   |
| K10           | 11       | 6.55%   |
| Zen+          | 10       | 5.95%   |
| KabyLake      | 10       | 5.95%   |
| SandyBridge   | 8        | 4.76%   |
| Core          | 8        | 4.76%   |
| Zen           | 7        | 4.17%   |
| CometLake     | 7        | 4.17%   |
| Zen 3         | 4        | 2.38%   |
| Silvermont    | 4        | 2.38%   |
| K10 Llano     | 4        | 2.38%   |
| Skylake       | 3        | 1.79%   |
| Nehalem       | 3        | 1.79%   |
| Bobcat        | 3        | 1.79%   |
| Westmere      | 2        | 1.19%   |
| Steamroller   | 2        | 1.19%   |
| NetBurst      | 2        | 1.19%   |
| K8 Hammer     | 2        | 1.19%   |
| Bulldozer     | 2        | 1.19%   |
| Jaguar        | 1        | 0.6%    |
| Goldmont plus | 1        | 0.6%    |
| Excavator     | 1        | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 62       | 35.23%  |
| AMD                        | 61       | 34.66%  |
| Intel                      | 50       | 28.41%  |
| VIA Technologies           | 1        | 0.57%   |
| Matrox Electronics Systems | 1        | 0.57%   |
| ATI Technologies           | 1        | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 5%      |
| Nvidia GP108 [GeForce GT 1030]                                                           | 6        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5        | 2.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5        | 2.78%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 2.78%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4        | 2.22%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4        | 2.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4        | 2.22%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 3        | 1.67%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3        | 1.67%   |
| Intel HD Graphics 530                                                                    | 3        | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.67%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3        | 1.67%   |
| AMD Sumo [Radeon HD 6530D]                                                               | 3        | 1.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3        | 1.67%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2        | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.11%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2        | 1.11%   |
| Nvidia GK104 [GeForce GTX 770]                                                           | 2        | 1.11%   |
| Nvidia GF106GL [Quadro 2000]                                                             | 2        | 1.11%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2        | 1.11%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 2        | 1.11%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 1.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.11%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 1.11%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 1.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.11%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 2        | 1.11%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 2        | 1.11%   |
| AMD RS780L [Radeon 3000]                                                                 | 2        | 1.11%   |
| AMD RS740 [Radeon 2100]                                                                  | 2        | 1.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.11%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.11%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1        | 0.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1        | 0.56%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1        | 0.56%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.56%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 0.56%   |
| Nvidia GT200b [GeForce GTX 275]                                                          | 1        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 0.56%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1        | 0.56%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1        | 0.56%   |
| Nvidia GM204 [GeForce GTX 980]                                                           | 1        | 0.56%   |
| Nvidia GM107GL [Quadro K620]                                                             | 1        | 0.56%   |
| Nvidia GK208 [GeForce GT 720]                                                            | 1        | 0.56%   |
| Nvidia GK110B [GeForce GTX 780 Ti]                                                       | 1        | 0.56%   |
| Nvidia GK107 [GeForce GT 740]                                                            | 1        | 0.56%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 0.56%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1        | 0.56%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 59       | 35.33%  |
| 1 x AMD      | 52       | 31.14%  |
| 1 x Intel    | 46       | 27.54%  |
| 2 x AMD      | 4        | 2.4%    |
| AMD + Nvidia | 3        | 1.8%    |
| 1 x VIA      | 1        | 0.6%    |
| 1 x Matrox   | 1        | 0.6%    |
| Intel + AMD  | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 125      | 74.4%   |
| Proprietary | 37       | 22.02%  |
| Unknown     | 6        | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 40.48%  |
| 1.01-2.0   | 32       | 19.05%  |
| 0.51-1.0   | 21       | 12.5%   |
| 0.01-0.5   | 17       | 10.12%  |
| 3.01-4.0   | 13       | 7.74%   |
| 5.01-6.0   | 6        | 3.57%   |
| 8.01-16.0  | 5        | 2.98%   |
| 7.01-8.0   | 4        | 2.38%   |
| 2.01-3.0   | 2        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 42       | 25.3%   |
| Goldstar             | 33       | 19.88%  |
| Hewlett-Packard      | 13       | 7.83%   |
| Dell                 | 11       | 6.63%   |
| LG Electronics       | 10       | 6.02%   |
| AOC                  | 8        | 4.82%   |
| Lenovo               | 6        | 3.61%   |
| Unknown              | 4        | 2.41%   |
| Sony                 | 4        | 2.41%   |
| ___                  | 3        | 1.81%   |
| ViewSonic            | 3        | 1.81%   |
| Packard Bell         | 3        | 1.81%   |
| KTC                  | 3        | 1.81%   |
| Acer                 | 3        | 1.81%   |
| SAC                  | 2        | 1.2%    |
| Plain Tree Systems   | 2        | 1.2%    |
| Philips              | 2        | 1.2%    |
| Hitachi              | 2        | 1.2%    |
| Envision             | 2        | 1.2%    |
| Westinghouse         | 1        | 0.6%    |
| SKY                  | 1        | 0.6%    |
| Sharp                | 1        | 0.6%    |
| MSI                  | 1        | 0.6%    |
| HKC                  | 1        | 0.6%    |
| CHR                  | 1        | 0.6%    |
| BenQ                 | 1        | 0.6%    |
| ASUSTek Computer     | 1        | 0.6%    |
| Ancor Communications | 1        | 0.6%    |
| Unknown              | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch                    | 5        | 2.86%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch              | 4        | 2.29%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 520x290mm 23.4-inch              | 3        | 1.71%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                      | 3        | 1.71%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                         | 3        | 1.71%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                       | 3        | 1.71%   |
| ___ LCDTV16 ___0101 1360x768                                                   | 2        | 1.14%   |
| Unknown LCD TV 0101 1920x1080 1600x900mm 72.3-inch                             | 2        | 1.14%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch        | 2        | 1.14%   |
| Philips 190P PHL0831 1280x1024 376x301mm 19.0-inch                             | 2        | 1.14%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                                    | 2        | 1.14%   |
| Lenovo LEN S22e-19 LEN61C9 1920x1080 476x268mm 21.5-inch                       | 2        | 1.14%   |
| Hewlett-Packard TouchSmart HP_touchsmart HWP4211 1920x1080 509x286mm 23.0-inch | 2        | 1.14%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch                      | 2        | 1.14%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                         | 2        | 1.14%   |
| AOC LE24H037 AOC2407 1920x1080 521x293mm 23.5-inch                             | 2        | 1.14%   |
| ___ LCDTV16 ___9000 1360x768                                                   | 1        | 0.57%   |
| Westinghouse LCM-19v5 WDE1905 1280x1024 376x301mm 19.0-inch                    | 1        | 0.57%   |
| ViewSonic VG930m-3 VSC991E 1280x1024 376x301mm 19.0-inch                       | 1        | 0.57%   |
| ViewSonic VA1926wSERIES VSC5920 1440x900 410x256mm 19.0-inch                   | 1        | 0.57%   |
| ViewSonic LCD Monitor VX2370 SERIES 1920x1080                                  | 1        | 0.57%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                           | 1        | 0.57%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                             | 1        | 0.57%   |
| Sony TV SNY4302 1920x1080                                                      | 1        | 0.57%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                                  | 1        | 0.57%   |
| Sony TV SNY1503 1360x768 1600x900mm 72.3-inch                                  | 1        | 0.57%   |
| Sony TV *02 SNYC403 1920x1080 1218x685mm 55.0-inch                             | 1        | 0.57%   |
| SKY TV-monitor SKY0102 1920x1080 885x498mm 40.0-inch                           | 1        | 0.57%   |
| Sharp HDMI SHP101E 1920x540                                                    | 1        | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch              | 1        | 0.57%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch              | 1        | 0.57%   |
| Samsung Electronics T19B300 SAM0926 1366x768 410x230mm 18.5-inch               | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0576 1280x1024 338x270mm 17.0-inch           | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM055F 1920x1080                               | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch            | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch            | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0322 1440x900 428x255mm 19.6-inch            | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch            | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x260mm 19.1-inch            | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch           | 1        | 0.57%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch              | 1        | 0.57%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch              | 1        | 0.57%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch          | 1        | 0.57%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch              | 1        | 0.57%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch              | 1        | 0.57%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch              | 1        | 0.57%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch              | 1        | 0.57%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch               | 1        | 0.57%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch               | 1        | 0.57%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch              | 1        | 0.57%   |
| Samsung Electronics LCD Monitor T22C301 1920x1080                              | 1        | 0.57%   |
| Samsung Electronics LCD Monitor T22B350                                        | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch          | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 700x390mm 31.5-inch          | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768                               | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM067A 1360x768                               | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                              | 1        | 0.57%   |
| Samsung Electronics LCD Monitor S27D590 1920x1080                              | 1        | 0.57%   |
| Samsung Electronics LCD Monitor S22B300 3840x1080                              | 1        | 0.57%   |
| Samsung Electronics LCD Monitor S19C150 1366x768                               | 1        | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 68       | 43.04%  |
| 1366x768 (WXGA)    | 13       | 8.23%   |
| 3840x2160 (4K)     | 11       | 6.96%   |
| 1360x768           | 11       | 6.96%   |
| 1440x900 (WXGA+)   | 9        | 5.7%    |
| 1280x1024 (SXGA)   | 9        | 5.7%    |
| 1600x900 (HD+)     | 8        | 5.06%   |
| 2560x1440 (QHD)    | 7        | 4.43%   |
| 2560x1080          | 6        | 3.8%    |
| Unknown            | 4        | 2.53%   |
| 3840x1080          | 3        | 1.9%    |
| 1680x1050 (WSXGA+) | 3        | 1.9%    |
| 1024x768 (XGA)     | 3        | 1.9%    |
| 5760x1080          | 1        | 0.63%   |
| 3440x1440          | 1        | 0.63%   |
| 1280x768           | 1        | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 26       | 15.95%  |
| 21      | 22       | 13.5%   |
| Unknown | 21       | 12.88%  |
| 18      | 11       | 6.75%   |
| 19      | 10       | 6.13%   |
| 27      | 9        | 5.52%   |
| 24      | 9        | 5.52%   |
| 20      | 8        | 4.91%   |
| 34      | 7        | 4.29%   |
| 15      | 7        | 4.29%   |
| 17      | 6        | 3.68%   |
| 72      | 5        | 3.07%   |
| 31      | 5        | 3.07%   |
| 84      | 4        | 2.45%   |
| 40      | 3        | 1.84%   |
| 54      | 2        | 1.23%   |
| 32      | 2        | 1.23%   |
| 22      | 2        | 1.23%   |
| 55      | 1        | 0.61%   |
| 37      | 1        | 0.61%   |
| 28      | 1        | 0.61%   |
| 13      | 1        | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 46       | 29.11%  |
| 501-600     | 39       | 24.68%  |
| Unknown     | 21       | 13.29%  |
| 301-350     | 11       | 6.96%   |
| 701-800     | 9        | 5.7%    |
| 1501-2000   | 9        | 5.7%    |
| 601-700     | 8        | 5.06%   |
| 351-400     | 7        | 4.43%   |
| 801-900     | 4        | 2.53%   |
| 1001-1500   | 3        | 1.9%    |
| 201-300     | 1        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 100      | 67.11%  |
| Unknown | 17       | 11.41%  |
| 16/10   | 13       | 8.72%   |
| 5/4     | 9        | 6.04%   |
| 21/9    | 7        | 4.7%    |
| 4/3     | 3        | 2.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 48       | 30.38%  |
| 151-200        | 22       | 13.92%  |
| Unknown        | 21       | 13.29%  |
| 351-500        | 15       | 9.49%   |
| 141-150        | 14       | 8.86%   |
| More than 1000 | 12       | 7.59%   |
| 301-350        | 9        | 5.7%    |
| 101-110        | 7        | 4.43%   |
| 501-1000       | 4        | 2.53%   |
| 251-300        | 3        | 1.9%    |
| 131-140        | 2        | 1.27%   |
| 91-100         | 1        | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 93       | 58.86%  |
| 101-120 | 29       | 18.35%  |
| Unknown | 21       | 13.29%  |
| 1-50    | 11       | 6.96%   |
| 121-160 | 3        | 1.9%    |
| 161-240 | 1        | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 126      | 75%     |
| 2     | 27       | 16.07%  |
| 0     | 12       | 7.14%   |
| 3     | 3        | 1.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 124      | 48.63%  |
| Intel                           | 41       | 16.08%  |
| Ralink Technology               | 14       | 5.49%   |
| Qualcomm Atheros                | 13       | 5.1%    |
| Ralink                          | 12       | 4.71%   |
| Broadcom                        | 8        | 3.14%   |
| TP-Link                         | 7        | 2.75%   |
| Xiaomi                          | 5        | 1.96%   |
| D-Link System                   | 4        | 1.57%   |
| Broadcom Limited                | 4        | 1.57%   |
| Qualcomm Atheros Communications | 3        | 1.18%   |
| Nvidia                          | 3        | 1.18%   |
| VIA Technologies                | 2        | 0.78%   |
| Samsung Electronics             | 2        | 0.78%   |
| Motorola PCS                    | 2        | 0.78%   |
| Marvell Technology Group        | 2        | 0.78%   |
| D-Link                          | 2        | 0.78%   |
| Padix (Rockfire)                | 1        | 0.39%   |
| Oculus VR                       | 1        | 0.39%   |
| Microsoft                       | 1        | 0.39%   |
| Manta                           | 1        | 0.39%   |
| ICS Advent                      | 1        | 0.39%   |
| Huawei Technologies             | 1        | 0.39%   |
| HMD Global                      | 1        | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 101      | 36.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 3.6%    |
| Ralink MT7601U Wireless Adapter                                               | 7        | 2.52%   |
| Intel I211 Gigabit Network Connection                                         | 6        | 2.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 5        | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 1.8%    |
| Intel Wi-Fi 6 AX200                                                           | 5        | 1.8%    |
| Intel Ethernet Connection I217-V                                              | 5        | 1.8%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 4        | 1.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 4        | 1.44%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 4        | 1.44%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4        | 1.44%   |
| Intel Wireless 7260                                                           | 4        | 1.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 3        | 1.08%   |
| Nvidia MCP61 Ethernet                                                         | 3        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2        | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 0.72%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 2        | 0.72%   |
| Realtek 802.11ac NIC                                                          | 2        | 0.72%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 0.72%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 0.72%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 2        | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2        | 0.72%   |
| Intel Wireless-AC 9260                                                        | 2        | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 0.72%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 0.72%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 0.72%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 0.72%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 0.72%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]          | 2        | 0.72%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 0.72%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe                       | 2        | 0.72%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 1        | 0.36%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1        | 0.36%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 0.36%   |
| TP-Link Archer T4U ver.3                                                      | 1        | 0.36%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 0.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.36%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 0.36%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.36%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 0.36%   |
| Realtek RTL8187 Wireless Adapter                                              | 1        | 0.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 1        | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1        | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.36%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 0.36%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                     | 1        | 0.36%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1        | 0.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1        | 0.36%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 0.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 18       | 20.22%  |
| Intel                           | 18       | 20.22%  |
| Ralink Technology               | 14       | 15.73%  |
| Ralink                          | 12       | 13.48%  |
| TP-Link                         | 7        | 7.87%   |
| Qualcomm Atheros                | 7        | 7.87%   |
| Qualcomm Atheros Communications | 3        | 3.37%   |
| Broadcom                        | 3        | 3.37%   |
| D-Link System                   | 2        | 2.25%   |
| D-Link                          | 2        | 2.25%   |
| Broadcom Limited                | 2        | 2.25%   |
| Microsoft                       | 1        | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                               | 7        | 7.87%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 5.62%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 4        | 4.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 4        | 4.49%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 4        | 4.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 4        | 4.49%   |
| Intel Wireless 7260                                                           | 4        | 4.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 3        | 3.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3        | 3.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 2        | 2.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 2        | 2.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 2.25%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 2        | 2.25%   |
| Realtek 802.11ac NIC                                                          | 2        | 2.25%   |
| Ralink RT5370 Wireless Adapter                                                | 2        | 2.25%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 2.25%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 2.25%   |
| Intel Wireless-AC 9260                                                        | 2        | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 2.25%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]          | 2        | 2.25%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                         | 1        | 1.12%   |
| TP-Link Archer T4U ver.3                                                      | 1        | 1.12%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 1.12%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1        | 1.12%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1        | 1.12%   |
| Realtek RTL8187 Wireless Adapter                                              | 1        | 1.12%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1        | 1.12%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                     | 1        | 1.12%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1        | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 1.12%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 1.12%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 1.12%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 1        | 1.12%   |
| Microsoft Xbox 360 Wireless Adapter                                           | 1        | 1.12%   |
| Intel Wireless 8260                                                           | 1        | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                               | 1        | 1.12%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                 | 1        | 1.12%   |
| D-Link 802.11ac NIC                                                           | 1        | 1.12%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                       | 1        | 1.12%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                       | 1        | 1.12%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 1.12%   |
| Broadcom BCM43225 802.11b/g/n                                                 | 1        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 118      | 64.84%  |
| Intel                    | 31       | 17.03%  |
| Qualcomm Atheros         | 6        | 3.3%    |
| Xiaomi                   | 5        | 2.75%   |
| Broadcom                 | 5        | 2.75%   |
| Nvidia                   | 3        | 1.65%   |
| VIA Technologies         | 2        | 1.1%    |
| Samsung Electronics      | 2        | 1.1%    |
| Marvell Technology Group | 2        | 1.1%    |
| D-Link System            | 2        | 1.1%    |
| Broadcom Limited         | 2        | 1.1%    |
| Motorola PCS             | 1        | 0.55%   |
| ICS Advent               | 1        | 0.55%   |
| Huawei Technologies      | 1        | 0.55%   |
| HMD Global               | 1        | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101      | 54.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 5.41%   |
| Intel I211 Gigabit Network Connection                             | 6        | 3.24%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 2.7%    |
| Intel Ethernet Connection I217-V                                  | 5        | 2.7%    |
| Nvidia MCP61 Ethernet                                             | 3        | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.08%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 1.08%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.08%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.08%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.08%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 1.08%   |
| Broadcom Limited NetLink BCM57788 Gigabit Ethernet PCIe           | 2        | 1.08%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.54%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.54%   |
| Motorola PCS moto g(30)                                           | 1        | 0.54%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.54%   |
| Intel Ethernet Connection I218-V                                  | 1        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.54%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.54%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.54%   |
| Intel 82566DC Gigabit Network Connection                          | 1        | 0.54%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.54%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1        | 0.54%   |
| Huawei JNY-LX1                                                    | 1        | 0.54%   |
| HMD Global Android                                                | 1        | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 0.54%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.54%   |
| Broadcom NetXtreme BCM5751F Fast Ethernet PCI Express             | 1        | 0.54%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 1        | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 166      | 66.4%   |
| WiFi     | 80       | 32%     |
| Unknown  | 3        | 1.2%    |
| Modem    | 1        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 133      | 71.51%  |
| WiFi     | 53       | 28.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 110      | 65.87%  |
| 2     | 48       | 28.74%  |
| 3     | 7        | 4.19%   |
| 4     | 1        | 0.6%    |
| 0     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 162      | 96.43%  |
| Yes  | 6        | 3.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 17       | 33.33%  |
| Cambridge Silicon Radio         | 16       | 31.37%  |
| Realtek Semiconductor           | 7        | 13.73%  |
| Broadcom                        | 7        | 13.73%  |
| Qualcomm Atheros Communications | 2        | 3.92%   |
| ASUSTek Computer                | 1        | 1.96%   |
| Apple                           | 1        | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 31.37%  |
| Realtek Bluetooth Radio                             | 7        | 13.73%  |
| Intel Bluetooth wireless interface                  | 5        | 9.8%    |
| Intel AX200 Bluetooth                               | 5        | 9.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5.88%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 3        | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 3.92%   |
| Intel AX210 Bluetooth                               | 2        | 3.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 1.96%   |
| Broadcom HP Bluetooth Module                        | 1        | 1.96%   |
| Broadcom HP Bluethunder                             | 1        | 1.96%   |
| Broadcom Bluetooth 3.0 Device                       | 1        | 1.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 1.96%   |
| ASUS BCM20702A0                                     | 1        | 1.96%   |
| Apple Bluetooth HCI                                 | 1        | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 92       | 34.46%  |
| AMD                        | 83       | 31.09%  |
| Nvidia                     | 56       | 20.97%  |
| C-Media Electronics        | 6        | 2.25%   |
| Creative Labs              | 5        | 1.87%   |
| VIA Technologies           | 2        | 0.75%   |
| Texas Instruments          | 2        | 0.75%   |
| Generalplus Technology     | 2        | 0.75%   |
| Arturia                    | 2        | 0.75%   |
| Unknown                    | 1        | 0.37%   |
| Razer USA                  | 1        | 0.37%   |
| PreSonus Audio Electronics | 1        | 0.37%   |
| Native Instruments         | 1        | 0.37%   |
| Logitech                   | 1        | 0.37%   |
| Kingston Technology        | 1        | 0.37%   |
| JMTek                      | 1        | 0.37%   |
| Hewlett-Packard            | 1        | 0.37%   |
| GYROCOM C&C                | 1        | 0.37%   |
| Focusrite-Novation         | 1        | 0.37%   |
| eMPIA Technology           | 1        | 0.37%   |
| Creative Technology        | 1        | 0.37%   |
| Corsair                    | 1        | 0.37%   |
| Blue Microphones           | 1        | 0.37%   |
| ATI Technologies           | 1        | 0.37%   |
| Apple                      | 1        | 0.37%   |
| Afatech                    | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 21       | 6.65%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15       | 4.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 14       | 4.43%   |
| AMD Family 17h/19h HD Audio Controller                                            | 12       | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 3.48%   |
| AMD FCH Azalia Controller                                                         | 10       | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9        | 2.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 9        | 2.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 8        | 2.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7        | 2.22%   |
| Nvidia GP108 High Definition Audio Controller                                     | 6        | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 1.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 6        | 1.9%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 5        | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 1.58%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 1.58%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.27%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4        | 1.27%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4        | 1.27%   |
| Intel 200 Series PCH HD Audio                                                     | 4        | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 1.27%   |
| AMD Navi 10 HDMI Audio                                                            | 4        | 1.27%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 4        | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 0.95%   |
| Nvidia High Definition Audio Controller                                           | 2        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 0.63%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 0.63%   |
| Nvidia GA102 High Definition Audio Controller                                     | 2        | 0.63%   |
| Nvidia Audio device                                                               | 2        | 0.63%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2        | 0.63%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 0.63%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 0.63%   |
| Intel Audio device                                                                | 2        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 0.63%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 0.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2        | 0.63%   |
| Intel 8 Series HD Audio Controller                                                | 2        | 0.63%   |
| Generalplus Technology Usb Audio Device                                           | 2        | 0.63%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                         | 2        | 0.63%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 0.63%   |
| C-Media Electronics Blue Snowball                                                 | 2        | 0.63%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 0.63%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 2        | 0.63%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 0.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 0.63%   |
| AMD Cypress HDMI Audio [Radeon HD 5830/5850/5870 / 6850/6870 Rebrand]             | 2        | 0.63%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1        | 0.32%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 1        | 0.32%   |
| Unknown USB Midi                                                                  | 1        | 0.32%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1        | 0.32%   |
| Texas Instruments PCM2900 Audio Codec                                             | 1        | 0.32%   |
| Razer USA Kraken 7.1 V2                                                           | 1        | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 21       | 25.61%  |
| Crucial             | 15       | 18.29%  |
| Unknown             | 10       | 12.2%   |
| Samsung Electronics | 8        | 9.76%   |
| Corsair             | 8        | 9.76%   |
| Micron Technology   | 4        | 4.88%   |
| SK Hynix            | 3        | 3.66%   |
| G.Skill             | 3        | 3.66%   |
| A-DATA Technology   | 3        | 3.66%   |
| Patriot             | 1        | 1.22%   |
| Nanya Technology    | 1        | 1.22%   |
| Kreton              | 1        | 1.22%   |
| Goldenmars          | 1        | 1.22%   |
| Elpida              | 1        | 1.22%   |
| Atermiter           | 1        | 1.22%   |
| ankowall            | 1        | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s                        | 3        | 3.26%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                                    | 2        | 2.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                      | 2        | 2.17%   |
| Kingston RAM KHX3466C17D4/16GX 16384MB DIMM DDR4 3466MT/s                  | 2        | 2.17%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                          | 2        | 2.17%   |
| Crucial RAM CT4G4DFS6266.C4FJ 4096MB DIMM DDR4 2666MT/s                    | 2        | 2.17%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                  | 1        | 1.09%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                  | 1        | 1.09%   |
| Unknown RAM Module 8192MB DIMM DDR3                                        | 1        | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                                  | 1        | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                                  | 1        | 1.09%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                               | 1        | 1.09%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                    | 1        | 1.09%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                   | 1        | 1.09%   |
| Unknown RAM Module 2GB DIMM                                                | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                | 1        | 1.09%   |
| Unknown RAM Module 2048MB DIMM 1600MT/s                                    | 1        | 1.09%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                            | 1        | 1.09%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1066MT/s                              | 1        | 1.09%   |
| SK Hynix RAM HMT151R7BFR4C 4096MB DIMM DDR3 1333MT/s                       | 1        | 1.09%   |
| Samsung RAM M393B5273CH0-YH9 4GB DIMM DDR3 1333MT/s                        | 1        | 1.09%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1866MT/s                            | 1        | 1.09%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1866MT/s                           | 1        | 1.09%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                        | 1        | 1.09%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s                        | 1        | 1.09%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                        | 1        | 1.09%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s                        | 1        | 1.09%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                       | 1        | 1.09%   |
| Micron RAM M471A3243BB0-CP50 16GB SODIMM DDR4 2667MT/s                     | 1        | 1.09%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                      | 1        | 1.09%   |
| Micron RAM 8JTF25664AZ-1G4D1 2GB DIMM DDR3 1333MT/s                        | 1        | 1.09%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB DIMM DDR3 1066MT/s                     | 1        | 1.09%   |
| Kreton RAM 51525xxxx68x35xxxx 1GB DIMM DDR2 667MT/s                        | 1        | 1.09%   |
| Kingston RAM Module 2GB DIMM DDR 667MT/s                                   | 1        | 1.09%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s                       | 1        | 1.09%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s                  | 1        | 1.09%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2933MT/s                       | 1        | 1.09%   |
| Kingston RAM KHX2666C16D4/16GX 16384MB DIMM DDR4 2667MT/s                  | 1        | 1.09%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                        | 1        | 1.09%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s                      | 1        | 1.09%   |
| Kingston RAM 99U5584-007.A00LF 4096MB DIMM DDR3 1333MT/s                   | 1        | 1.09%   |
| Kingston RAM 99U5469-053.A00LF 4096MB SODIMM DDR3 1333MT/s                 | 1        | 1.09%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s                    | 1        | 1.09%   |
| Kingston RAM 9905474-036.A00LF 2048MB DIMM DDR3 1067MT/s                   | 1        | 1.09%   |
| Kingston RAM 9905474-019.A00LF 2GB DIMM 1333MT/s                           | 1        | 1.09%   |
| Kingston RAM 9905471-011.A00LF 4096MB DIMM DDR3 1600MT/s                   | 1        | 1.09%   |
| Kingston RAM 9905403-038.A00G 4GB DIMM DDR3 1333MT/s                       | 1        | 1.09%   |
| Kingston RAM 9905402-570.A00LF 4GB DIMM DDR3 1333MT/s                      | 1        | 1.09%   |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s                       | 1        | 1.09%   |
| Kingston RAM 32472D5544494D4D00000000000000000000 2048MB DIMM DDR2 667MT/s | 1        | 1.09%   |
| Goldenmars RAM GMT8G04SCL116P-PBA 8GB SODIMM DDR3 1600MT/s                 | 1        | 1.09%   |
| G.Skill RAM F4-2800C17-8GVR 8GB DIMM DDR4 2133MT/s                         | 1        | 1.09%   |
| G.Skill RAM F3-12800CL9-2GBXL 2GB DIMM DDR3 1600MT/s                       | 1        | 1.09%   |
| G.Skill RAM F2-6400CL5-2GBNT 2GB DIMM DDR 667MT/s                          | 1        | 1.09%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB DIMM DDR3 1333MT/s                     | 1        | 1.09%   |
| Crucial RAM Module 4GB DIMM DDR3 1600MT/s                                  | 1        | 1.09%   |
| Crucial RAM CT8G4DFS8266.M8FE 8192MB DIMM DDR4 2667MT/s                    | 1        | 1.09%   |
| Crucial RAM CT8G4DFS8213.M8FB 8GB DIMM DDR4 2133MT/s                       | 1        | 1.09%   |
| Crucial RAM CT8G4DFRA266.C8FP 8192MB DIMM DDR4 2666MT/s                    | 1        | 1.09%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB DIMM DDR3 1600MT/s                      | 1        | 1.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 31       | 43.06%  |
| DDR4    | 30       | 41.67%  |
| DDR2    | 5        | 6.94%   |
| Unknown | 3        | 4.17%   |
| SDRAM   | 2        | 2.78%   |
| DDR     | 1        | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 65       | 91.55%  |
| SODIMM | 6        | 8.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 33.33%  |
| 4096  | 24       | 29.63%  |
| 2048  | 16       | 19.75%  |
| 16384 | 12       | 14.81%  |
| 32768 | 1        | 1.23%   |
| 1024  | 1        | 1.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 19.28%  |
| 1333    | 13       | 15.66%  |
| 2133    | 8        | 9.64%   |
| 3600    | 5        | 6.02%   |
| 3466    | 5        | 6.02%   |
| 2667    | 4        | 4.82%   |
| 667     | 4        | 4.82%   |
| 2400    | 3        | 3.61%   |
| 1866    | 3        | 3.61%   |
| 1066    | 3        | 3.61%   |
| 3200    | 2        | 2.41%   |
| 2666    | 2        | 2.41%   |
| 1334    | 2        | 2.41%   |
| 800     | 2        | 2.41%   |
| Unknown | 2        | 2.41%   |
| 4000    | 1        | 1.2%    |
| 3800    | 1        | 1.2%    |
| 3533    | 1        | 1.2%    |
| 3400    | 1        | 1.2%    |
| 3266    | 1        | 1.2%    |
| 3134    | 1        | 1.2%    |
| 2933    | 1        | 1.2%    |
| 2800    | 1        | 1.2%    |
| 1067    | 1        | 1.2%    |

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


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Brother HL-1200 series     | 2        | 20%     |
| Seiko Epson Printer        | 1        | 10%     |
| Seiko Epson ET-2710 Series | 1        | 10%     |
| QinHeng CH340S             | 1        | 10%     |
| HP Deskjet 4640 series     | 1        | 10%     |
| HP Deskjet 4620 series     | 1        | 10%     |
| Canon PIXMA MP250          | 1        | 10%     |
| Canon G2000 series         | 1        | 10%     |
| Canon G1000 series         | 1        | 10%     |

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
| Logitech                      | 7        | 20%     |
| Chicony Electronics           | 6        | 17.14%  |
| Apple                         | 4        | 11.43%  |
| Generalplus Technology        | 3        | 8.57%   |
| Sunplus Innovation Technology | 2        | 5.71%   |
| Microsoft                     | 2        | 5.71%   |
| Microdia                      | 2        | 5.71%   |
| Z-Star Microelectronics       | 1        | 2.86%   |
| Unknown                       | 1        | 2.86%   |
| OmniVision Technologies       | 1        | 2.86%   |
| MacroSilicon                  | 1        | 2.86%   |
| KYE Systems (Mouse Systems)   | 1        | 2.86%   |
| Jieli Technology              | 1        | 2.86%   |
| AVerMedia Technologies        | 1        | 2.86%   |
| Arkmicro Technologies         | 1        | 2.86%   |
| Alcor Micro                   | 1        | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Logitech C922 Pro Stream Webcam               | 4        | 11.43%  |
| Apple iPhone 5/5C/5S/6/SE                     | 4        | 11.43%  |
| Generalplus GENERAL WEBCAM                    | 3        | 8.57%   |
| Chicony HP 0.3MP Webcam                       | 3        | 8.57%   |
| Sunplus Full HD webcam                        | 2        | 5.71%   |
| Z-Star Integrated Camera                      | 1        | 2.86%   |
| Unknown HD camera                             | 1        | 2.86%   |
| OmniVision OV511+ Webcam                      | 1        | 2.86%   |
| Microsoft MicrosoftÂ LifeCam Studio          | 1        | 2.86%   |
| Microsoft LifeCam VX-800                      | 1        | 2.86%   |
| Microdia Webcam Vitade AF                     | 1        | 2.86%   |
| Microdia USB camera                           | 1        | 2.86%   |
| MacroSilicon MS210x Video Grabber [EasierCAP] | 1        | 2.86%   |
| Logitech Webcam C270                          | 1        | 2.86%   |
| Logitech Webcam C210                          | 1        | 2.86%   |
| Logitech Webcam C170                          | 1        | 2.86%   |
| KYE Systems (Mouse Systems) FaceCam 1000X     | 1        | 2.86%   |
| Jieli USB PHY 2.0                             | 1        | 2.86%   |
| Chicony HP High Definition 1MP Webcam         | 1        | 2.86%   |
| Chicony HP 1.0MP High Definition Webcam       | 1        | 2.86%   |
| Chicony CNF8050 Webcam                        | 1        | 2.86%   |
| AVerMedia Live Streamer CAM 313               | 1        | 2.86%   |
| Arkmicro USB2.0 PC CAMERA                     | 1        | 2.86%   |
| Alcor Micro USB 2.0 PC Camera                 | 1        | 2.86%   |

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
| 0     | 147      | 87.5%   |
| 1     | 19       | 11.31%  |
| 2     | 2        | 1.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 36.36%  |
| Net/wireless             | 7        | 31.82%  |
| Unassigned class         | 2        | 9.09%   |
| Network                  | 1        | 4.55%   |
| Multimedia controller    | 1        | 4.55%   |
| Firewire controller      | 1        | 4.55%   |
| Communication controller | 1        | 4.55%   |
| Bluetooth                | 1        | 4.55%   |

