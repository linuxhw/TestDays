Fedora 37 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 989

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | A320M-H-CF                  | [3d211c5277](https://linux-hardware.org/?probe=3d211c5277) | Oct 24, 2023 |
| HP            | 802F                        | [ed3a09f912](https://linux-hardware.org/?probe=ed3a09f912) | Oct 12, 2023 |
| HP            | 802F                        | [c2b0f9720e](https://linux-hardware.org/?probe=c2b0f9720e) | Oct 12, 2023 |
| HP            | 802E                        | [2d84b83c17](https://linux-hardware.org/?probe=2d84b83c17) | Oct 03, 2023 |
| HP            | 802E                        | [10fcb68621](https://linux-hardware.org/?probe=10fcb68621) | Oct 03, 2023 |
| Supermicro    | H8DM8-2                     | [5386350e20](https://linux-hardware.org/?probe=5386350e20) | Oct 03, 2023 |
| ASRock        | X570 Taichi                 | [7a670fe0ef](https://linux-hardware.org/?probe=7a670fe0ef) | Sep 30, 2023 |
| ASRock        | B150M Pro4/Hyper            | [6bd5055b96](https://linux-hardware.org/?probe=6bd5055b96) | Sep 24, 2023 |
| Dell          | 00010C A00                  | [40d7defca4](https://linux-hardware.org/?probe=40d7defca4) | Sep 23, 2023 |
| Dell          | 0PP150 A00                  | [766815ba45](https://linux-hardware.org/?probe=766815ba45) | Sep 22, 2023 |
| HP            | 84FD                        | [d0845ca4d2](https://linux-hardware.org/?probe=d0845ca4d2) | Sep 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | [172b7a1d48](https://linux-hardware.org/?probe=172b7a1d48) | Sep 13, 2023 |
| Dell          | 0GXM1W A01                  | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| Dell          | 0GM819                      | [f7d8bdb2a3](https://linux-hardware.org/?probe=f7d8bdb2a3) | Sep 10, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [b93e0fc32b](https://linux-hardware.org/?probe=b93e0fc32b) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [44e98cb157](https://linux-hardware.org/?probe=44e98cb157) | Aug 29, 2023 |
| MSI           | Z370-A PRO                  | [d9a6d27a28](https://linux-hardware.org/?probe=d9a6d27a28) | Aug 29, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [7da432892e](https://linux-hardware.org/?probe=7da432892e) | Aug 29, 2023 |
| Dell          | 0GXM1W A01                  | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| MSI           | MS-B9321                    | [07564a2fc4](https://linux-hardware.org/?probe=07564a2fc4) | Aug 25, 2023 |
| Dell          | 0HHV7N A00                  | [1bcc49b615](https://linux-hardware.org/?probe=1bcc49b615) | Aug 25, 2023 |
| MSI           | MS-B9321                    | [df54486a48](https://linux-hardware.org/?probe=df54486a48) | Aug 25, 2023 |
| ASUSTek       | CM6870                      | [05507d2151](https://linux-hardware.org/?probe=05507d2151) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | [b91ffcb2be](https://linux-hardware.org/?probe=b91ffcb2be) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [12c4ed323e](https://linux-hardware.org/?probe=12c4ed323e) | Aug 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8add0a69cc](https://linux-hardware.org/?probe=8add0a69cc) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| ASUSTek       | PRIME B350M-A               | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | [bcfe09b617](https://linux-hardware.org/?probe=bcfe09b617) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| Gigabyte      | H61MS                       | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| Dell          | 00010C A00                  | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| Dell          | 0KRC95 A02                  | [5d0d505ca1](https://linux-hardware.org/?probe=5d0d505ca1) | Jul 07, 2023 |
| MSI           | Z170A KRAIT GAMING          | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| ASRock        | Z87 Extreme6                | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [b07361bc89](https://linux-hardware.org/?probe=b07361bc89) | Jun 22, 2023 |
| Gigabyte      | MZBAYAB-00                  | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| HP            | 212B                        | [134ff203c4](https://linux-hardware.org/?probe=134ff203c4) | Jun 16, 2023 |
| HP            | 212B                        | [b107461bdd](https://linux-hardware.org/?probe=b107461bdd) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| Dell          | 0KRC95 A02                  | [5f9a1aafe0](https://linux-hardware.org/?probe=5f9a1aafe0) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| Gigabyte      | D525TUD                     | [be2c796ab2](https://linux-hardware.org/?probe=be2c796ab2) | Jun 13, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [cf9274f969](https://linux-hardware.org/?probe=cf9274f969) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1c5e1b092a](https://linux-hardware.org/?probe=1c5e1b092a) | Jun 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [212c44c43f](https://linux-hardware.org/?probe=212c44c43f) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f9677c0861](https://linux-hardware.org/?probe=f9677c0861) | Jun 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3c3708dcec](https://linux-hardware.org/?probe=3c3708dcec) | Jun 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79b80daf83](https://linux-hardware.org/?probe=79b80daf83) | Jun 05, 2023 |
| HP            | 212B                        | [15c4a7b64f](https://linux-hardware.org/?probe=15c4a7b64f) | Jun 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [df9086deb4](https://linux-hardware.org/?probe=df9086deb4) | Jun 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a908da319](https://linux-hardware.org/?probe=4a908da319) | May 31, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ffbccb8f47](https://linux-hardware.org/?probe=ffbccb8f47) | May 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8b96413dfd](https://linux-hardware.org/?probe=8b96413dfd) | May 30, 2023 |
| HP            | 8169                        | [4f10a589e7](https://linux-hardware.org/?probe=4f10a589e7) | May 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [38936854c8](https://linux-hardware.org/?probe=38936854c8) | May 29, 2023 |
| HP            | ProLiant ML110 G7           | [fd74c84f0a](https://linux-hardware.org/?probe=fd74c84f0a) | May 28, 2023 |
| Gigabyte      | Z77MX-D3H                   | [3c001962b0](https://linux-hardware.org/?probe=3c001962b0) | May 28, 2023 |
| ASRock        | B450M-HDV R4.0              | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2c31d88fa2](https://linux-hardware.org/?probe=2c31d88fa2) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [efb5aa9bfc](https://linux-hardware.org/?probe=efb5aa9bfc) | May 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec7d8d12e1](https://linux-hardware.org/?probe=ec7d8d12e1) | May 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ecc77ee7a9](https://linux-hardware.org/?probe=ecc77ee7a9) | May 22, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [7b5628af0e](https://linux-hardware.org/?probe=7b5628af0e) | May 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [b59b0160fb](https://linux-hardware.org/?probe=b59b0160fb) | May 19, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [b8ed6a8b77](https://linux-hardware.org/?probe=b8ed6a8b77) | May 18, 2023 |
| Gigabyte      | 990FXA-UD3 R5               | [b3e10fd912](https://linux-hardware.org/?probe=b3e10fd912) | May 17, 2023 |
| Gigabyte      | H170-Gaming 3               | [ae5f06df99](https://linux-hardware.org/?probe=ae5f06df99) | May 16, 2023 |
| MSI           | H170A PC MATE               | [389ab53539](https://linux-hardware.org/?probe=389ab53539) | May 15, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4344603b6](https://linux-hardware.org/?probe=d4344603b6) | May 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bd390995e3](https://linux-hardware.org/?probe=bd390995e3) | May 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [903ece310a](https://linux-hardware.org/?probe=903ece310a) | May 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4243b6a57b](https://linux-hardware.org/?probe=4243b6a57b) | May 13, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [fdf45a81de](https://linux-hardware.org/?probe=fdf45a81de) | May 13, 2023 |
| Dell          | 02YYK5 A00                  | [68213fddbd](https://linux-hardware.org/?probe=68213fddbd) | May 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [35990f19da](https://linux-hardware.org/?probe=35990f19da) | May 12, 2023 |
| ASUSTek       | X79-DELUXE                  | [ad6be5fe7c](https://linux-hardware.org/?probe=ad6be5fe7c) | May 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [e985d1beac](https://linux-hardware.org/?probe=e985d1beac) | May 12, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1b0cd4f3e1](https://linux-hardware.org/?probe=1b0cd4f3e1) | May 11, 2023 |
| Gigabyte      | H77N-WIFI                   | [3dc1af6df9](https://linux-hardware.org/?probe=3dc1af6df9) | May 11, 2023 |
| ASUSTek       | PRIME B560M-K               | [ce0391bdee](https://linux-hardware.org/?probe=ce0391bdee) | May 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [e2bbbffe45](https://linux-hardware.org/?probe=e2bbbffe45) | May 09, 2023 |
| ASRock        | B560M-ITX/ac                | [80b16a8567](https://linux-hardware.org/?probe=80b16a8567) | May 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [53c03d6942](https://linux-hardware.org/?probe=53c03d6942) | May 08, 2023 |
| ASRock        | N68C-GS FX                  | [dcf5cd4ca2](https://linux-hardware.org/?probe=dcf5cd4ca2) | May 08, 2023 |
| Intel         | DP43TF AAE34878-403         | [9d5ca00c7c](https://linux-hardware.org/?probe=9d5ca00c7c) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | [6bea90b569](https://linux-hardware.org/?probe=6bea90b569) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | [6353d110f5](https://linux-hardware.org/?probe=6353d110f5) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | [db0ab14831](https://linux-hardware.org/?probe=db0ab14831) | May 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [513f1e9efb](https://linux-hardware.org/?probe=513f1e9efb) | May 02, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [dc9cb3badc](https://linux-hardware.org/?probe=dc9cb3badc) | May 02, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [961ec7671c](https://linux-hardware.org/?probe=961ec7671c) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [be8b69e1b4](https://linux-hardware.org/?probe=be8b69e1b4) | May 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [c33288abe2](https://linux-hardware.org/?probe=c33288abe2) | Apr 30, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [80ea529a18](https://linux-hardware.org/?probe=80ea529a18) | Apr 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [853016bfe3](https://linux-hardware.org/?probe=853016bfe3) | Apr 27, 2023 |
| Gigabyte      | EX58-EXTREME                | [3b263c29fc](https://linux-hardware.org/?probe=3b263c29fc) | Apr 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [909ad37ab0](https://linux-hardware.org/?probe=909ad37ab0) | Apr 26, 2023 |
| HP            | 0AECh D                     | [c9e99b3f8c](https://linux-hardware.org/?probe=c9e99b3f8c) | Apr 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [373372bf75](https://linux-hardware.org/?probe=373372bf75) | Apr 25, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [9c37fa5192](https://linux-hardware.org/?probe=9c37fa5192) | Apr 24, 2023 |
| Gigabyte      | F2A88X-UP4                  | [06859fe586](https://linux-hardware.org/?probe=06859fe586) | Apr 23, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| MSI           | Z370M MORTAR                | [9ed0395d2c](https://linux-hardware.org/?probe=9ed0395d2c) | Apr 22, 2023 |
| Gigabyte      | H77N-WIFI                   | [80312ab34c](https://linux-hardware.org/?probe=80312ab34c) | Apr 22, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [81334f294e](https://linux-hardware.org/?probe=81334f294e) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [cebfbef6d8](https://linux-hardware.org/?probe=cebfbef6d8) | Apr 20, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | [1383ab9981](https://linux-hardware.org/?probe=1383ab9981) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4fbb42afa0](https://linux-hardware.org/?probe=4fbb42afa0) | Apr 19, 2023 |
| Unknown       | Unknown                     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2a80be40e3](https://linux-hardware.org/?probe=2a80be40e3) | Apr 19, 2023 |
| Intel         | X79M-S                      | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| Alienware     | 0K9TKY A00                  | [22582f8d3e](https://linux-hardware.org/?probe=22582f8d3e) | Apr 19, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [cf13c3781c](https://linux-hardware.org/?probe=cf13c3781c) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| ASRock        | Z170 Gaming K4              | [cbd09f0f67](https://linux-hardware.org/?probe=cbd09f0f67) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| ASUSTek       | B85-PRO GAMER               | [bbe3e437d6](https://linux-hardware.org/?probe=bbe3e437d6) | Apr 17, 2023 |
| ASUSTek       | PRIME B550M-A               | [4b953003cc](https://linux-hardware.org/?probe=4b953003cc) | Apr 17, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [07a49303af](https://linux-hardware.org/?probe=07a49303af) | Apr 17, 2023 |
| MSI           | H310M PRO-VD PLUS           | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [1fa07cd218](https://linux-hardware.org/?probe=1fa07cd218) | Apr 16, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [c228cbe8e1](https://linux-hardware.org/?probe=c228cbe8e1) | Apr 16, 2023 |
| Gigabyte      | B85-HD3                     | [25e7d545ae](https://linux-hardware.org/?probe=25e7d545ae) | Apr 16, 2023 |
| ASRock        | A520M-HVS                   | [a0d799e140](https://linux-hardware.org/?probe=a0d799e140) | Apr 16, 2023 |
| HP            | 212B                        | [c8f86eb8a4](https://linux-hardware.org/?probe=c8f86eb8a4) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [2be395131f](https://linux-hardware.org/?probe=2be395131f) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | [0ca4b7045e](https://linux-hardware.org/?probe=0ca4b7045e) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2e601ecae8](https://linux-hardware.org/?probe=2e601ecae8) | Apr 15, 2023 |
| MSI           | H310M PRO-VD PLUS           | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c7ca0e9fd1](https://linux-hardware.org/?probe=c7ca0e9fd1) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| ASRock        | 970 Pro3 R2.0               | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| MSI           | MS-7388                     | [d7f892b3e2](https://linux-hardware.org/?probe=d7f892b3e2) | Apr 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c279e7b8fe](https://linux-hardware.org/?probe=c279e7b8fe) | Apr 11, 2023 |
| Dell          | 0J3C2F A00                  | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [e8645a51dc](https://linux-hardware.org/?probe=e8645a51dc) | Apr 11, 2023 |
| HP            | 225E                        | [46f665e085](https://linux-hardware.org/?probe=46f665e085) | Apr 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6fe9dfd9a6](https://linux-hardware.org/?probe=6fe9dfd9a6) | Apr 10, 2023 |
| ECS           | H61H2-M12                   | [f3e8f5eb22](https://linux-hardware.org/?probe=f3e8f5eb22) | Apr 10, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87f9a72b18](https://linux-hardware.org/?probe=87f9a72b18) | Apr 09, 2023 |
| Dell          | 0M5DCD A00                  | [f65d106f65](https://linux-hardware.org/?probe=f65d106f65) | Apr 08, 2023 |
| MSI           | B450I GAMING PLUS AC        | [e34683f5f0](https://linux-hardware.org/?probe=e34683f5f0) | Apr 07, 2023 |
| MSI           | B450M MORTAR MAX            | [e9281d0364](https://linux-hardware.org/?probe=e9281d0364) | Apr 06, 2023 |
| HP            | 1495                        | [c0665ecb23](https://linux-hardware.org/?probe=c0665ecb23) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [26e8d46d94](https://linux-hardware.org/?probe=26e8d46d94) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [84c709f5f9](https://linux-hardware.org/?probe=84c709f5f9) | Apr 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [e65532d978](https://linux-hardware.org/?probe=e65532d978) | Apr 03, 2023 |
| Medion        | MS-7728                     | [83f7f01bde](https://linux-hardware.org/?probe=83f7f01bde) | Apr 02, 2023 |
| Gigabyte      | X570S AERO G                | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [f3b1797500](https://linux-hardware.org/?probe=f3b1797500) | Apr 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [94df0605ae](https://linux-hardware.org/?probe=94df0605ae) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| ASRock        | J3160DC-ITX                 | [7735423853](https://linux-hardware.org/?probe=7735423853) | Apr 02, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| Gigabyte      | GA-970A-UD3                 | [30d25bdb17](https://linux-hardware.org/?probe=30d25bdb17) | Apr 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| Intel         | DH77EB AAG39073-304         | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [c512f4cdd9](https://linux-hardware.org/?probe=c512f4cdd9) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [79d44a9e66](https://linux-hardware.org/?probe=79d44a9e66) | Apr 01, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [e615755655](https://linux-hardware.org/?probe=e615755655) | Apr 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a9aebc7f0](https://linux-hardware.org/?probe=4a9aebc7f0) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [acfff71638](https://linux-hardware.org/?probe=acfff71638) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | B550M DS3H AC               | [4693b65922](https://linux-hardware.org/?probe=4693b65922) | Mar 31, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [8d4ef602e5](https://linux-hardware.org/?probe=8d4ef602e5) | Mar 31, 2023 |
| Dell          | 0PP150 A00                  | [fdc879a486](https://linux-hardware.org/?probe=fdc879a486) | Mar 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1417777bbc](https://linux-hardware.org/?probe=1417777bbc) | Mar 30, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [70efcb81e9](https://linux-hardware.org/?probe=70efcb81e9) | Mar 30, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2ac52b4538](https://linux-hardware.org/?probe=2ac52b4538) | Mar 30, 2023 |
| Gigabyte      | J1900M-D2P                  | [881f70cb12](https://linux-hardware.org/?probe=881f70cb12) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bc798d371a](https://linux-hardware.org/?probe=bc798d371a) | Mar 30, 2023 |
| System76      | Thelio Mira thelio-mira-... | [4915a172bd](https://linux-hardware.org/?probe=4915a172bd) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| Acer          | Veriton N4630G              | [fab3140b7b](https://linux-hardware.org/?probe=fab3140b7b) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [7c56c30e23](https://linux-hardware.org/?probe=7c56c30e23) | Mar 29, 2023 |
| Gigabyte      | P55-UD6-C                   | [010ed7a818](https://linux-hardware.org/?probe=010ed7a818) | Mar 29, 2023 |
| MSI           | B450M MORTAR                | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [151a527b35](https://linux-hardware.org/?probe=151a527b35) | Mar 28, 2023 |
| ASUSTek       | PRIME B550M-A               | [4b0ae8033f](https://linux-hardware.org/?probe=4b0ae8033f) | Mar 28, 2023 |
| MSI           | B550-A PRO                  | [999219f420](https://linux-hardware.org/?probe=999219f420) | Mar 28, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| Dell          | 08HPGT A01                  | [451ccd93f2](https://linux-hardware.org/?probe=451ccd93f2) | Mar 27, 2023 |
| Dell          | 08HPGT A01                  | [e38a63e793](https://linux-hardware.org/?probe=e38a63e793) | Mar 27, 2023 |
| Huanan        | X99-F8D V2.6                | [65f96586ec](https://linux-hardware.org/?probe=65f96586ec) | Mar 27, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [14380327b0](https://linux-hardware.org/?probe=14380327b0) | Mar 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [79dc82b50b](https://linux-hardware.org/?probe=79dc82b50b) | Mar 27, 2023 |
| ASUSTek       | Maximus VIII HERO           | [23ee1856bc](https://linux-hardware.org/?probe=23ee1856bc) | Mar 27, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6b00de6bed](https://linux-hardware.org/?probe=6b00de6bed) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| ASRock        | B450M-HDV R4.0              | [e069fb2622](https://linux-hardware.org/?probe=e069fb2622) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a607ac616d](https://linux-hardware.org/?probe=a607ac616d) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3711318620](https://linux-hardware.org/?probe=3711318620) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-K               | [95b0768bfc](https://linux-hardware.org/?probe=95b0768bfc) | Mar 25, 2023 |
| MSI           | 2AE0                        | [43a4a75176](https://linux-hardware.org/?probe=43a4a75176) | Mar 25, 2023 |
| Lenovo        | SHARKBAY No DPK             | [2941abc936](https://linux-hardware.org/?probe=2941abc936) | Mar 25, 2023 |
| ASRock        | AD525PV3                    | [84545fd0ea](https://linux-hardware.org/?probe=84545fd0ea) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| Gigabyte      | J1900M-D2P                  | [5acd2b0492](https://linux-hardware.org/?probe=5acd2b0492) | Mar 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Gigabyte      | H77N-WIFI                   | [1503a33123](https://linux-hardware.org/?probe=1503a33123) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| Itautec       | ST 4265                     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| ASUSTek       | P8P67 PRO                   | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| ASRock        | X79 Extreme6                | [1287699f09](https://linux-hardware.org/?probe=1287699f09) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| MSI           | PRO B650M-A WIFI            | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| ASUSTek       | B85M-G                      | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| ASUSTek       | PRIME B550M-A               | [aede16096d](https://linux-hardware.org/?probe=aede16096d) | Mar 22, 2023 |
| Gigabyte      | X570 AORUS PRO              | [825332bfce](https://linux-hardware.org/?probe=825332bfce) | Mar 21, 2023 |
| NZXT          | N7 B550                     | [8ca9bc3db9](https://linux-hardware.org/?probe=8ca9bc3db9) | Mar 21, 2023 |
| MSI           | X570-A PRO                  | [a9c58c1f47](https://linux-hardware.org/?probe=a9c58c1f47) | Mar 21, 2023 |
| Shuttle       | SH570                       | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [cb21d30b9e](https://linux-hardware.org/?probe=cb21d30b9e) | Mar 20, 2023 |
| MSI           | PRO Z790-P WIFI             | [038bd3a32b](https://linux-hardware.org/?probe=038bd3a32b) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Win elemen... | M600                        | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [53a3d14aa0](https://linux-hardware.org/?probe=53a3d14aa0) | Mar 20, 2023 |
| Dell          | 0YXT71 A00                  | [7a4669a603](https://linux-hardware.org/?probe=7a4669a603) | Mar 19, 2023 |
| ASRock        | FM2A88X Extreme6+           | [93ff9f0891](https://linux-hardware.org/?probe=93ff9f0891) | Mar 19, 2023 |
| ASRock        | B450M-HDV R4.0              | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P                | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| ASUSTek       | PRIME B550M-A               | [b63ad62fc2](https://linux-hardware.org/?probe=b63ad62fc2) | Mar 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [783a968012](https://linux-hardware.org/?probe=783a968012) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [501c72715a](https://linux-hardware.org/?probe=501c72715a) | Mar 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [280e67175b](https://linux-hardware.org/?probe=280e67175b) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [261bcbfc32](https://linux-hardware.org/?probe=261bcbfc32) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [4d82c078c8](https://linux-hardware.org/?probe=4d82c078c8) | Mar 16, 2023 |
| Gigabyte      | G41MT-D3                    | [b4483fd4e2](https://linux-hardware.org/?probe=b4483fd4e2) | Mar 16, 2023 |
| Gigabyte      | H410M H V3                  | [6023b7ce1d](https://linux-hardware.org/?probe=6023b7ce1d) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | [69cb363858](https://linux-hardware.org/?probe=69cb363858) | Mar 16, 2023 |
| Lenovo        | 32E6 SDK0T76530 WIN 3556... | [c9e4cb7c2e](https://linux-hardware.org/?probe=c9e4cb7c2e) | Mar 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [f48398a1e2](https://linux-hardware.org/?probe=f48398a1e2) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [897879b2c7](https://linux-hardware.org/?probe=897879b2c7) | Mar 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [bf303c0c16](https://linux-hardware.org/?probe=bf303c0c16) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| MSI           | B450M MORTAR                | [14a4314e39](https://linux-hardware.org/?probe=14a4314e39) | Mar 15, 2023 |
| Dell          | 0NC2VH A01                  | [e6fd051ae8](https://linux-hardware.org/?probe=e6fd051ae8) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | [b324afc6f8](https://linux-hardware.org/?probe=b324afc6f8) | Mar 14, 2023 |
| ASRock        | H170M Pro4                  | [c34ef2441a](https://linux-hardware.org/?probe=c34ef2441a) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [532c5768ad](https://linux-hardware.org/?probe=532c5768ad) | Mar 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c59a00db09](https://linux-hardware.org/?probe=c59a00db09) | Mar 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | [c3a62d14b3](https://linux-hardware.org/?probe=c3a62d14b3) | Mar 13, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [e245557641](https://linux-hardware.org/?probe=e245557641) | Mar 13, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [532bf1dca2](https://linux-hardware.org/?probe=532bf1dca2) | Mar 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [e45386803e](https://linux-hardware.org/?probe=e45386803e) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5434188010](https://linux-hardware.org/?probe=5434188010) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| ASUSTek       | H170-PRO                    | [c3e0b5bc1d](https://linux-hardware.org/?probe=c3e0b5bc1d) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [b7a4968bcd](https://linux-hardware.org/?probe=b7a4968bcd) | Mar 11, 2023 |
| Gigabyte      | Z170X-UD3 Ultra-CF          | [fa2be7de30](https://linux-hardware.org/?probe=fa2be7de30) | Mar 11, 2023 |
| Unknown       | Unknown                     | [7e7927f2dd](https://linux-hardware.org/?probe=7e7927f2dd) | Mar 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [1d552cfca2](https://linux-hardware.org/?probe=1d552cfca2) | Mar 11, 2023 |
| Lenovo        | SHARKBAY NOK                | [d674283cb0](https://linux-hardware.org/?probe=d674283cb0) | Mar 11, 2023 |
| Acer          | Veriton X4620G v1.0         | [fc27bc474e](https://linux-hardware.org/?probe=fc27bc474e) | Mar 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [0f9de03c50](https://linux-hardware.org/?probe=0f9de03c50) | Mar 11, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | [abebd8a5c2](https://linux-hardware.org/?probe=abebd8a5c2) | Mar 11, 2023 |
| ASUSTek       | PRIME B550M-A               | [e9af5c4cb2](https://linux-hardware.org/?probe=e9af5c4cb2) | Mar 10, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [ca937e17a7](https://linux-hardware.org/?probe=ca937e17a7) | Mar 10, 2023 |
| Gigabyte      | G41MT-D3                    | [e27d91ea6f](https://linux-hardware.org/?probe=e27d91ea6f) | Mar 09, 2023 |
| Gigabyte      | G41MT-D3                    | [790877da61](https://linux-hardware.org/?probe=790877da61) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [9cd2cf85c7](https://linux-hardware.org/?probe=9cd2cf85c7) | Mar 09, 2023 |
| ASRock        | Z370M Pro4                  | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| MSI           | MAG B460M MORTAR            | [233700c52d](https://linux-hardware.org/?probe=233700c52d) | Mar 08, 2023 |
| Gigabyte      | J1900M-D2P                  | [dfe7f75406](https://linux-hardware.org/?probe=dfe7f75406) | Mar 08, 2023 |
| Gigabyte      | H77N-WIFI                   | [ffaa232ea2](https://linux-hardware.org/?probe=ffaa232ea2) | Mar 08, 2023 |
| Gigabyte      | Z77MX-D3H                   | [916862cd66](https://linux-hardware.org/?probe=916862cd66) | Mar 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [62800640af](https://linux-hardware.org/?probe=62800640af) | Mar 07, 2023 |
| AZW           | GTR V02                     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bac7bd817d](https://linux-hardware.org/?probe=bac7bd817d) | Mar 07, 2023 |
| ASUSTek       | PRIME B550M-A               | [5750b514a0](https://linux-hardware.org/?probe=5750b514a0) | Mar 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [6735fc94ae](https://linux-hardware.org/?probe=6735fc94ae) | Mar 06, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| MSI           | MAG B460M MORTAR            | [de44275a2c](https://linux-hardware.org/?probe=de44275a2c) | Mar 06, 2023 |
| Dell          | 0RY007                      | [1aff8f499e](https://linux-hardware.org/?probe=1aff8f499e) | Mar 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d725cc57f0](https://linux-hardware.org/?probe=d725cc57f0) | Mar 06, 2023 |
| ASUSTek       | PRIME X570-P                | [14eb2d295d](https://linux-hardware.org/?probe=14eb2d295d) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| Huanan        | X99-TF                      | [99a3729e53](https://linux-hardware.org/?probe=99a3729e53) | Mar 05, 2023 |
| MSI           | B550M PRO                   | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| HP            | 2B05                        | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| ASUSTek       | P8P67 DELUXE                | [31e4b3ada8](https://linux-hardware.org/?probe=31e4b3ada8) | Mar 05, 2023 |
| Gigabyte      | H77N-WIFI                   | [dfc84acc1a](https://linux-hardware.org/?probe=dfc84acc1a) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [f0b9f4e39f](https://linux-hardware.org/?probe=f0b9f4e39f) | Mar 05, 2023 |
| ASRock        | B560M-ITX/ac                | [0bbfe90659](https://linux-hardware.org/?probe=0bbfe90659) | Mar 05, 2023 |
| ASUSTek       | P7H55-M LX                  | [79e06d188d](https://linux-hardware.org/?probe=79e06d188d) | Mar 04, 2023 |
| ASRock        | X470 Taichi                 | [59392dfa37](https://linux-hardware.org/?probe=59392dfa37) | Mar 04, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [06063736c6](https://linux-hardware.org/?probe=06063736c6) | Mar 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b4110d0e0b](https://linux-hardware.org/?probe=b4110d0e0b) | Mar 04, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [4b9b04ef26](https://linux-hardware.org/?probe=4b9b04ef26) | Mar 03, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [b6535fad6b](https://linux-hardware.org/?probe=b6535fad6b) | Mar 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [7efed287ee](https://linux-hardware.org/?probe=7efed287ee) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | [191bd6ec28](https://linux-hardware.org/?probe=191bd6ec28) | Mar 03, 2023 |
| Dell          | 00V62H A01                  | [391c255a97](https://linux-hardware.org/?probe=391c255a97) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| ASUSTek       | Maximus VII RANGER          | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| ASUSTek       | PRIME B550M-K               | [8ef1c9b71d](https://linux-hardware.org/?probe=8ef1c9b71d) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | [e699d6bb6e](https://linux-hardware.org/?probe=e699d6bb6e) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [883911a8df](https://linux-hardware.org/?probe=883911a8df) | Mar 02, 2023 |
| AZW           | SEi                         | [eb876ab2f4](https://linux-hardware.org/?probe=eb876ab2f4) | Mar 02, 2023 |
| AZW           | SEi                         | [7184a124c7](https://linux-hardware.org/?probe=7184a124c7) | Mar 02, 2023 |
| Dell          | 0KRC95 A02                  | [3bb7b686ec](https://linux-hardware.org/?probe=3bb7b686ec) | Mar 02, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [420e6e6325](https://linux-hardware.org/?probe=420e6e6325) | Mar 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [50520b2cf0](https://linux-hardware.org/?probe=50520b2cf0) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [9d6539b8f6](https://linux-hardware.org/?probe=9d6539b8f6) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-K               | [588ac214ef](https://linux-hardware.org/?probe=588ac214ef) | Mar 01, 2023 |
| HP            | 834F                        | [96631603b3](https://linux-hardware.org/?probe=96631603b3) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [713781f44e](https://linux-hardware.org/?probe=713781f44e) | Mar 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [833b6835b6](https://linux-hardware.org/?probe=833b6835b6) | Mar 01, 2023 |
| Dell          | 0KRC95 A02                  | [5cf1539621](https://linux-hardware.org/?probe=5cf1539621) | Mar 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [48c5c743c9](https://linux-hardware.org/?probe=48c5c743c9) | Feb 28, 2023 |
| ASRock        | H61M-VS                     | [04d5b9593e](https://linux-hardware.org/?probe=04d5b9593e) | Feb 28, 2023 |
| HP            | 158A                        | [64f3590183](https://linux-hardware.org/?probe=64f3590183) | Feb 28, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1b5fd0df61](https://linux-hardware.org/?probe=1b5fd0df61) | Feb 28, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| ASUSTek       | PRIME Q270M-C               | [3a9683fbb7](https://linux-hardware.org/?probe=3a9683fbb7) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| Gigabyte      | Z170MX-Gaming 5             | [1f0e9197f9](https://linux-hardware.org/?probe=1f0e9197f9) | Feb 26, 2023 |
| ASUSTek       | PRIME B550M-A               | [a121d0545a](https://linux-hardware.org/?probe=a121d0545a) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c56cf68cef](https://linux-hardware.org/?probe=c56cf68cef) | Feb 26, 2023 |
| Gigabyte      | EX58-UD5                    | [85ed1d43c7](https://linux-hardware.org/?probe=85ed1d43c7) | Feb 26, 2023 |
| Gigabyte      | H510M S2                    | [24ea8468ca](https://linux-hardware.org/?probe=24ea8468ca) | Feb 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [c204192a4b](https://linux-hardware.org/?probe=c204192a4b) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-A II            | [420520e3ab](https://linux-hardware.org/?probe=420520e3ab) | Feb 25, 2023 |
| Dell          | 0W2F8G A01                  | [1d0d54843b](https://linux-hardware.org/?probe=1d0d54843b) | Feb 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [87c5af58f5](https://linux-hardware.org/?probe=87c5af58f5) | Feb 25, 2023 |
| Gigabyte      | H310M S2 x.x                | [27fa5a62b6](https://linux-hardware.org/?probe=27fa5a62b6) | Feb 24, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [4a0d65f6b5](https://linux-hardware.org/?probe=4a0d65f6b5) | Feb 24, 2023 |
| MSI           | B350M PRO-VDH               | [748d109cb3](https://linux-hardware.org/?probe=748d109cb3) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [5d901ddc4e](https://linux-hardware.org/?probe=5d901ddc4e) | Feb 24, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [2312252934](https://linux-hardware.org/?probe=2312252934) | Feb 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6e57f3a472](https://linux-hardware.org/?probe=6e57f3a472) | Feb 24, 2023 |
| MSI           | Z170A PC MATE               | [5ee58b9271](https://linux-hardware.org/?probe=5ee58b9271) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| ASUSTek       | PRIME B550M-A               | [acdea94715](https://linux-hardware.org/?probe=acdea94715) | Feb 23, 2023 |
| Gateway       | SX2185                      | [32ab171e53](https://linux-hardware.org/?probe=32ab171e53) | Feb 23, 2023 |
| ASRock        | B450M Pro4                  | [193a97dfb1](https://linux-hardware.org/?probe=193a97dfb1) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [eade3920d9](https://linux-hardware.org/?probe=eade3920d9) | Feb 23, 2023 |
| ASUSTek       | P5L-MX                      | [cc19e49d3c](https://linux-hardware.org/?probe=cc19e49d3c) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| ASUSTek       | P5L-MX                      | [9eb9ca3cfb](https://linux-hardware.org/?probe=9eb9ca3cfb) | Feb 22, 2023 |
| Acer          | Veriton N4630G              | [eb6a551e75](https://linux-hardware.org/?probe=eb6a551e75) | Feb 22, 2023 |
| ASRock        | AB350 Pro4                  | [aaad317fe4](https://linux-hardware.org/?probe=aaad317fe4) | Feb 22, 2023 |
| ASRockRack    | X470D4U                     | [162a5279bc](https://linux-hardware.org/?probe=162a5279bc) | Feb 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [67ba988b20](https://linux-hardware.org/?probe=67ba988b20) | Feb 21, 2023 |
| Gigabyte      | J1900M-D2P                  | [edd5640ca7](https://linux-hardware.org/?probe=edd5640ca7) | Feb 21, 2023 |
| MSI           | H410M PRO-VH                | [669d124e33](https://linux-hardware.org/?probe=669d124e33) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | [8fd85f724b](https://linux-hardware.org/?probe=8fd85f724b) | Feb 20, 2023 |
| Lenovo        | ThinkCentre M58 8910B4U     | [03c8e6d135](https://linux-hardware.org/?probe=03c8e6d135) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH X99              | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6eda9f2592](https://linux-hardware.org/?probe=6eda9f2592) | Feb 19, 2023 |
| ASUSTek       | P5Q SE2                     | [37b0d0609f](https://linux-hardware.org/?probe=37b0d0609f) | Feb 18, 2023 |
| ASRock        | H110 Pro BTC+               | [bce117c4dc](https://linux-hardware.org/?probe=bce117c4dc) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| MSI           | H410M PRO-VH                | [ccc1cbf2fa](https://linux-hardware.org/?probe=ccc1cbf2fa) | Feb 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f14a791491](https://linux-hardware.org/?probe=f14a791491) | Feb 18, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| ASUSTek       | PRIME B550M-A               | [f9fb638882](https://linux-hardware.org/?probe=f9fb638882) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [750c0f6337](https://linux-hardware.org/?probe=750c0f6337) | Feb 17, 2023 |
| ASRock        | X470 Taichi                 | [71685845fe](https://linux-hardware.org/?probe=71685845fe) | Feb 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [8c3926e125](https://linux-hardware.org/?probe=8c3926e125) | Feb 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [8e3bad7795](https://linux-hardware.org/?probe=8e3bad7795) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [add68ac711](https://linux-hardware.org/?probe=add68ac711) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | [a19a7a2edd](https://linux-hardware.org/?probe=a19a7a2edd) | Feb 16, 2023 |
| ASUSTek       | EX-H310M-V3 R2.0            | [d42c40dd2e](https://linux-hardware.org/?probe=d42c40dd2e) | Feb 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f4e8b0e952](https://linux-hardware.org/?probe=f4e8b0e952) | Feb 16, 2023 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [a370fca217](https://linux-hardware.org/?probe=a370fca217) | Feb 15, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [ca54397755](https://linux-hardware.org/?probe=ca54397755) | Feb 15, 2023 |
| MSI           | FM2-A75MA-E35               | [a7f2ca398d](https://linux-hardware.org/?probe=a7f2ca398d) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7d8c3e7e48](https://linux-hardware.org/?probe=7d8c3e7e48) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| ASRock        | X370 Gaming X               | [2b9a026876](https://linux-hardware.org/?probe=2b9a026876) | Feb 14, 2023 |
| HP            | 8714                        | [19a66b5101](https://linux-hardware.org/?probe=19a66b5101) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [43dff5bee7](https://linux-hardware.org/?probe=43dff5bee7) | Feb 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | [10c8101c9b](https://linux-hardware.org/?probe=10c8101c9b) | Feb 14, 2023 |
| MSI           | X99A SLI PLUS               | [98447ce3dd](https://linux-hardware.org/?probe=98447ce3dd) | Feb 13, 2023 |
| Dell          | 0R6PCT A01                  | [4126ed8507](https://linux-hardware.org/?probe=4126ed8507) | Feb 13, 2023 |
| Pegatron      | 2AB6                        | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| ASRock        | FM2A88X Extreme6+           | [a5469c55ac](https://linux-hardware.org/?probe=a5469c55ac) | Feb 12, 2023 |
| ASUSTek       | PRIME B550M-A               | [2d63c8d887](https://linux-hardware.org/?probe=2d63c8d887) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| ASUSTek       | Z97-P                       | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASRock        | Z790 Pro RS WiFi            | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| ASRock        | FM2A88X Extreme6+           | [6474c43d80](https://linux-hardware.org/?probe=6474c43d80) | Feb 11, 2023 |
| ASRock        | A300M-STX                   | [79266ec6c7](https://linux-hardware.org/?probe=79266ec6c7) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9a2b8045de](https://linux-hardware.org/?probe=9a2b8045de) | Feb 10, 2023 |
| HP            | 8714                        | [3938395f75](https://linux-hardware.org/?probe=3938395f75) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [70b81f3738](https://linux-hardware.org/?probe=70b81f3738) | Feb 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | [6ced92edc7](https://linux-hardware.org/?probe=6ced92edc7) | Feb 09, 2023 |
| MSI           | H110M PRO-VD PLUS           | [c296dedf74](https://linux-hardware.org/?probe=c296dedf74) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [a12cca2eeb](https://linux-hardware.org/?probe=a12cca2eeb) | Feb 08, 2023 |
| ASUSTek       | PRIME B550M-A               | [b02b8779fc](https://linux-hardware.org/?probe=b02b8779fc) | Feb 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5c5d5d4304](https://linux-hardware.org/?probe=5c5d5d4304) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH X79              | [21910f6687](https://linux-hardware.org/?probe=21910f6687) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Lenovo        | ThinkServer TS140           | [1bac17097f](https://linux-hardware.org/?probe=1bac17097f) | Feb 07, 2023 |
| ASUSTek       | SABERTOOTH X79              | [ace0ce95b9](https://linux-hardware.org/?probe=ace0ce95b9) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | [47153e938c](https://linux-hardware.org/?probe=47153e938c) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e82192ba4c](https://linux-hardware.org/?probe=e82192ba4c) | Feb 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d91fe3e151](https://linux-hardware.org/?probe=d91fe3e151) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31a56f80dd](https://linux-hardware.org/?probe=31a56f80dd) | Feb 06, 2023 |
| ASUSTek       | PRIME B550M-A               | [ff01db5c9a](https://linux-hardware.org/?probe=ff01db5c9a) | Feb 06, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [781dc9da09](https://linux-hardware.org/?probe=781dc9da09) | Feb 06, 2023 |
| Compal        | DIP00                       | [632d4c313a](https://linux-hardware.org/?probe=632d4c313a) | Feb 06, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | [99d0ce5421](https://linux-hardware.org/?probe=99d0ce5421) | Feb 05, 2023 |
| HP            | 1589                        | [1872d63c2b](https://linux-hardware.org/?probe=1872d63c2b) | Feb 05, 2023 |
| HP            | 1589                        | [69c0ab962c](https://linux-hardware.org/?probe=69c0ab962c) | Feb 05, 2023 |
| Intel         | X99                         | [e8790caf8d](https://linux-hardware.org/?probe=e8790caf8d) | Feb 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [9f5df7e4e0](https://linux-hardware.org/?probe=9f5df7e4e0) | Feb 04, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [1c6725b5eb](https://linux-hardware.org/?probe=1c6725b5eb) | Feb 04, 2023 |
| Gigabyte      | Z77MX-D3H                   | [a17959ea9b](https://linux-hardware.org/?probe=a17959ea9b) | Feb 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | [3633683d62](https://linux-hardware.org/?probe=3633683d62) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f2578f11e1](https://linux-hardware.org/?probe=f2578f11e1) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5e9c75d478](https://linux-hardware.org/?probe=5e9c75d478) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [e680a7484e](https://linux-hardware.org/?probe=e680a7484e) | Feb 03, 2023 |
| HP            | 8714                        | [b8abceccbc](https://linux-hardware.org/?probe=b8abceccbc) | Feb 03, 2023 |
| Pegatron      | IPXSB-H61                   | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme6+           | [9b8d82dfcd](https://linux-hardware.org/?probe=9b8d82dfcd) | Feb 02, 2023 |
| Gigabyte      | J1900M-D2P                  | [c7b6222f08](https://linux-hardware.org/?probe=c7b6222f08) | Feb 02, 2023 |
| ASRock        | Z77 Extreme4                | [6598bc47dd](https://linux-hardware.org/?probe=6598bc47dd) | Feb 02, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [15c523ee98](https://linux-hardware.org/?probe=15c523ee98) | Feb 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [f2919f7135](https://linux-hardware.org/?probe=f2919f7135) | Feb 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [d35cf58f46](https://linux-hardware.org/?probe=d35cf58f46) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| MSI           | Z170A PC MATE               | [ff305089b2](https://linux-hardware.org/?probe=ff305089b2) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ffe1cabad7](https://linux-hardware.org/?probe=ffe1cabad7) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [779b723b67](https://linux-hardware.org/?probe=779b723b67) | Feb 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [79c11af9ac](https://linux-hardware.org/?probe=79c11af9ac) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [5f2948351d](https://linux-hardware.org/?probe=5f2948351d) | Feb 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [4f8642280f](https://linux-hardware.org/?probe=4f8642280f) | Feb 01, 2023 |
| AZW           | U59                         | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| AZW           | U59                         | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Gigabyte      | G41MT-D3                    | [99127d4bed](https://linux-hardware.org/?probe=99127d4bed) | Feb 01, 2023 |
| Gigabyte      | H97M-D3H                    | [3ccdc4fa2b](https://linux-hardware.org/?probe=3ccdc4fa2b) | Jan 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [318b0a5ecb](https://linux-hardware.org/?probe=318b0a5ecb) | Jan 31, 2023 |
| ASRock        | FM2A88X Extreme6+           | [73bc9212a3](https://linux-hardware.org/?probe=73bc9212a3) | Jan 31, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6e7d6aae31](https://linux-hardware.org/?probe=6e7d6aae31) | Jan 31, 2023 |
| ASRock        | AD2700-ITX                  | [2f14c18867](https://linux-hardware.org/?probe=2f14c18867) | Jan 31, 2023 |
| ASRock        | 890GM Pro3                  | [b2bb32cbbc](https://linux-hardware.org/?probe=b2bb32cbbc) | Jan 31, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [67262a8155](https://linux-hardware.org/?probe=67262a8155) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [6a4a26884d](https://linux-hardware.org/?probe=6a4a26884d) | Jan 30, 2023 |
| Dell          | 0Y2K8N A01                  | [8e4f1d2ed2](https://linux-hardware.org/?probe=8e4f1d2ed2) | Jan 30, 2023 |
| ASUSTek       | PRIME B550M-A               | [585c3c8f85](https://linux-hardware.org/?probe=585c3c8f85) | Jan 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [24402e3d42](https://linux-hardware.org/?probe=24402e3d42) | Jan 30, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [9b6a9a4ab5](https://linux-hardware.org/?probe=9b6a9a4ab5) | Jan 30, 2023 |
| ASRock        | N68-S UCC                   | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| ASUSTek       | GA15DH                      | [767fe59cb7](https://linux-hardware.org/?probe=767fe59cb7) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-A II            | [104fb04e91](https://linux-hardware.org/?probe=104fb04e91) | Jan 29, 2023 |
| ASUSTek       | PRIME B550M-A               | [ef43edeee5](https://linux-hardware.org/?probe=ef43edeee5) | Jan 29, 2023 |
| ASRock        | FM2A88X Extreme6+           | [f9a823cb38](https://linux-hardware.org/?probe=f9a823cb38) | Jan 29, 2023 |
| ASRock        | X570M Pro4                  | [e72f7f2fb1](https://linux-hardware.org/?probe=e72f7f2fb1) | Jan 29, 2023 |
| Acer          | FMP55                       | [d091fbc8d3](https://linux-hardware.org/?probe=d091fbc8d3) | Jan 29, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [d9f9d4bc89](https://linux-hardware.org/?probe=d9f9d4bc89) | Jan 27, 2023 |
| ASRock        | 970 Pro3 R2.0               | [676f900958](https://linux-hardware.org/?probe=676f900958) | Jan 27, 2023 |
| ASUSTek       | PRIME B550M-A               | [e619db262a](https://linux-hardware.org/?probe=e619db262a) | Jan 27, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [c0ea09ef3c](https://linux-hardware.org/?probe=c0ea09ef3c) | Jan 27, 2023 |
| ASRock        | AD2700-ITX                  | [7b711bee4f](https://linux-hardware.org/?probe=7b711bee4f) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [4213c95d3d](https://linux-hardware.org/?probe=4213c95d3d) | Jan 26, 2023 |
| Gigabyte      | J1900M-D2P                  | [b44aa465bc](https://linux-hardware.org/?probe=b44aa465bc) | Jan 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [415b96672b](https://linux-hardware.org/?probe=415b96672b) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX H370-I GAMING     | [decfe6ab97](https://linux-hardware.org/?probe=decfe6ab97) | Jan 25, 2023 |
| Dell          | 0XFWHV A00                  | [52ee3df163](https://linux-hardware.org/?probe=52ee3df163) | Jan 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82c3a80b93](https://linux-hardware.org/?probe=82c3a80b93) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [8ac6e901d5](https://linux-hardware.org/?probe=8ac6e901d5) | Jan 24, 2023 |
| Lenovo        | 36E9 SDK0T08861 WIN 3305... | [82705366d7](https://linux-hardware.org/?probe=82705366d7) | Jan 24, 2023 |
| ASRock        | FM2A88X Extreme6+           | [43c26544a9](https://linux-hardware.org/?probe=43c26544a9) | Jan 24, 2023 |
| Dell          | 0X30MX A00                  | [c323a1a215](https://linux-hardware.org/?probe=c323a1a215) | Jan 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [1887a95d31](https://linux-hardware.org/?probe=1887a95d31) | Jan 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [2f215e1ce7](https://linux-hardware.org/?probe=2f215e1ce7) | Jan 23, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [aa16eaced0](https://linux-hardware.org/?probe=aa16eaced0) | Jan 23, 2023 |
| ASRock        | FM2A88X Extreme6+           | [279452d293](https://linux-hardware.org/?probe=279452d293) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| Dell          | 0Y56T3 A00                  | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| MSI           | H510M PRO                   | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| MSI           | B450-A PRO                  | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b3d64d2496](https://linux-hardware.org/?probe=b3d64d2496) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6856fa4741](https://linux-hardware.org/?probe=6856fa4741) | Jan 21, 2023 |
| AZW           | GTR V02                     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| ASRock        | FM2A88X Extreme6+           | [20c0f69bb7](https://linux-hardware.org/?probe=20c0f69bb7) | Jan 21, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [2f6bd134ae](https://linux-hardware.org/?probe=2f6bd134ae) | Jan 20, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5bbd614c0f](https://linux-hardware.org/?probe=5bbd614c0f) | Jan 20, 2023 |
| HP            | 0AECh D                     | [b2ea95f507](https://linux-hardware.org/?probe=b2ea95f507) | Jan 20, 2023 |
| ASRock        | FM2A88X Extreme6+           | [5f1447f874](https://linux-hardware.org/?probe=5f1447f874) | Jan 20, 2023 |
| Dell          | 0GY6Y8 A02                  | [33b364ed89](https://linux-hardware.org/?probe=33b364ed89) | Jan 19, 2023 |
| ASRock        | X300M-STX                   | [8303a9c2a0](https://linux-hardware.org/?probe=8303a9c2a0) | Jan 18, 2023 |
| Dell          | 0XFRWW A00                  | [2b96d4b6f6](https://linux-hardware.org/?probe=2b96d4b6f6) | Jan 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [011b9a41cd](https://linux-hardware.org/?probe=011b9a41cd) | Jan 18, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ec05dd5768](https://linux-hardware.org/?probe=ec05dd5768) | Jan 18, 2023 |
| Dell          | 0KRC95 A02                  | [01cf6039d0](https://linux-hardware.org/?probe=01cf6039d0) | Jan 18, 2023 |
| ASRock        | B550 Extreme4               | [e5599ac616](https://linux-hardware.org/?probe=e5599ac616) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [8e21ef4b91](https://linux-hardware.org/?probe=8e21ef4b91) | Jan 17, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [8753bd8277](https://linux-hardware.org/?probe=8753bd8277) | Jan 17, 2023 |
| Gigabyte      | G41MT-D3                    | [16be0552b2](https://linux-hardware.org/?probe=16be0552b2) | Jan 17, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [16c9b323c6](https://linux-hardware.org/?probe=16c9b323c6) | Jan 17, 2023 |
| ASRock        | FM2A88X Extreme6+           | [aeb9ac591c](https://linux-hardware.org/?probe=aeb9ac591c) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d5843b83af](https://linux-hardware.org/?probe=d5843b83af) | Jan 16, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Gigabyte      | 990FXA-UD5 R5               | [dd16b56d30](https://linux-hardware.org/?probe=dd16b56d30) | Jan 16, 2023 |
| Gigabyte      | B550M DS3H                  | [d24e1142ef](https://linux-hardware.org/?probe=d24e1142ef) | Jan 16, 2023 |
| Dell          | 0M863N A01                  | [1dff7cb016](https://linux-hardware.org/?probe=1dff7cb016) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b68ce1375d](https://linux-hardware.org/?probe=b68ce1375d) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK               | [978682daa6](https://linux-hardware.org/?probe=978682daa6) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| AZW           | GTR V02                     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| Gigabyte      | Z77X-D3H                    | [4ef76b2644](https://linux-hardware.org/?probe=4ef76b2644) | Jan 14, 2023 |
| Dell          | 0W2F8G A01                  | [999fcca032](https://linux-hardware.org/?probe=999fcca032) | Jan 14, 2023 |
| ASRock        | FM2A88X Extreme6+           | [03f0709b21](https://linux-hardware.org/?probe=03f0709b21) | Jan 14, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [40acaf3525](https://linux-hardware.org/?probe=40acaf3525) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d4b0530f79](https://linux-hardware.org/?probe=d4b0530f79) | Jan 13, 2023 |
| ASUSTek       | H170 PRO GAMING             | [4cf36f7404](https://linux-hardware.org/?probe=4cf36f7404) | Jan 13, 2023 |
| HP            | 3047h                       | [5eb46c9039](https://linux-hardware.org/?probe=5eb46c9039) | Jan 12, 2023 |
| HP            | 3047h                       | [0c035c1a04](https://linux-hardware.org/?probe=0c035c1a04) | Jan 12, 2023 |
| Gigabyte      | A320M-S2H-CF                | [f38e5f2a4e](https://linux-hardware.org/?probe=f38e5f2a4e) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Unknown       | X79                         | [62bf02da9d](https://linux-hardware.org/?probe=62bf02da9d) | Jan 12, 2023 |
| Unknown       | X79                         | [aed457b56c](https://linux-hardware.org/?probe=aed457b56c) | Jan 12, 2023 |
| MSI           | B550-A PRO                  | [28d13d17ba](https://linux-hardware.org/?probe=28d13d17ba) | Jan 12, 2023 |
| Pegatron      | 2AC3                        | [3cfb7d9e7c](https://linux-hardware.org/?probe=3cfb7d9e7c) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| ASRock        | Z87 Extreme6                | [49e3d87de4](https://linux-hardware.org/?probe=49e3d87de4) | Jan 11, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [18e82e414a](https://linux-hardware.org/?probe=18e82e414a) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [760cc2eaed](https://linux-hardware.org/?probe=760cc2eaed) | Jan 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a5f45ca97](https://linux-hardware.org/?probe=0a5f45ca97) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [7c7c8175c0](https://linux-hardware.org/?probe=7c7c8175c0) | Jan 09, 2023 |
| Gigabyte      | H77N-WIFI                   | [95cfb68187](https://linux-hardware.org/?probe=95cfb68187) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| AZW           | GTR V02                     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| ASRock        | FM2A88X Extreme6+           | [d7820d12e5](https://linux-hardware.org/?probe=d7820d12e5) | Jan 09, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [6fd945d3cd](https://linux-hardware.org/?probe=6fd945d3cd) | Jan 09, 2023 |
| MSI           | MEG X570 ACE                | [853f3c06ce](https://linux-hardware.org/?probe=853f3c06ce) | Jan 08, 2023 |
| MSI           | X570-A PRO                  | [d3e35671cd](https://linux-hardware.org/?probe=d3e35671cd) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [afd852d260](https://linux-hardware.org/?probe=afd852d260) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [5f3e927024](https://linux-hardware.org/?probe=5f3e927024) | Jan 08, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| ASRock        | FM2A88X Extreme6+           | [b0a36f054e](https://linux-hardware.org/?probe=b0a36f054e) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [34259527c2](https://linux-hardware.org/?probe=34259527c2) | Jan 07, 2023 |
| ASUSTek       | PRIME B350M-A               | [df845fe4a9](https://linux-hardware.org/?probe=df845fe4a9) | Jan 07, 2023 |
| Acer          | FMCP7A-ION-LE               | [84a2abec03](https://linux-hardware.org/?probe=84a2abec03) | Jan 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [82052bbfcb](https://linux-hardware.org/?probe=82052bbfcb) | Jan 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [68e299de33](https://linux-hardware.org/?probe=68e299de33) | Jan 06, 2023 |
| MSI           | PRO Z690-A DDR4             | [0b9a54a591](https://linux-hardware.org/?probe=0b9a54a591) | Jan 06, 2023 |
| ASRock        | FM2A88X Extreme6+           | [bcc4cba81a](https://linux-hardware.org/?probe=bcc4cba81a) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e417e45252](https://linux-hardware.org/?probe=e417e45252) | Jan 06, 2023 |
| Dell          | 02YRK5 A02                  | [e7b27ba60c](https://linux-hardware.org/?probe=e7b27ba60c) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [a559464349](https://linux-hardware.org/?probe=a559464349) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| Gigabyte      | B550M DS3H                  | [24d21ee9f1](https://linux-hardware.org/?probe=24d21ee9f1) | Jan 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | [1964dbc8e7](https://linux-hardware.org/?probe=1964dbc8e7) | Jan 05, 2023 |
| Positivo      | POS-PIQ57BQA                | [4453ef0d86](https://linux-hardware.org/?probe=4453ef0d86) | Jan 04, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [5c352967e4](https://linux-hardware.org/?probe=5c352967e4) | Jan 04, 2023 |
| ASUSTek       | PRIME B550M-K               | [0c4e0afd97](https://linux-hardware.org/?probe=0c4e0afd97) | Jan 04, 2023 |
| Gigabyte      | B450M S2H                   | [6d6e710ac3](https://linux-hardware.org/?probe=6d6e710ac3) | Jan 04, 2023 |
| Gigabyte      | Z690 UD DDR4                | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [0968211c5b](https://linux-hardware.org/?probe=0968211c5b) | Jan 04, 2023 |
| Dell          | 0N4YC8 A00                  | [4195800fa5](https://linux-hardware.org/?probe=4195800fa5) | Jan 04, 2023 |
| Gigabyte      | J1900M-D2P                  | [ad776cdf84](https://linux-hardware.org/?probe=ad776cdf84) | Jan 04, 2023 |
| Dell          | 0KRC95 A02                  | [8e30a9a43e](https://linux-hardware.org/?probe=8e30a9a43e) | Jan 04, 2023 |
| Positivo      | POS-PIQ57BQA                | [e03b53cc0e](https://linux-hardware.org/?probe=e03b53cc0e) | Jan 04, 2023 |
| Gigabyte      | H410M H V3                  | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| Positivo      | POS-EIB85CZ                 | [639f5a2bf7](https://linux-hardware.org/?probe=639f5a2bf7) | Jan 03, 2023 |
| ASUSTek       | PRIME X570-P                | [f1962e0076](https://linux-hardware.org/?probe=f1962e0076) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [43ff03b36f](https://linux-hardware.org/?probe=43ff03b36f) | Jan 03, 2023 |
| Dell          | 0KRC95 A02                  | [d7c57c2bae](https://linux-hardware.org/?probe=d7c57c2bae) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-A               | [386eb7bc28](https://linux-hardware.org/?probe=386eb7bc28) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85aeab3e5](https://linux-hardware.org/?probe=f85aeab3e5) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [4e900247e4](https://linux-hardware.org/?probe=4e900247e4) | Jan 02, 2023 |
| ASRock        | Z77 Professional            | [bf09b21dc7](https://linux-hardware.org/?probe=bf09b21dc7) | Jan 02, 2023 |
| ASRock        | FM2A88M-HD+ R2.0            | [8e9080dc74](https://linux-hardware.org/?probe=8e9080dc74) | Jan 01, 2023 |
| ASUSTek       | H81M-PLUS                   | [752fe53b7c](https://linux-hardware.org/?probe=752fe53b7c) | Jan 01, 2023 |
| Intel         | DG41TY AAE47335-300         | [11f3804cb6](https://linux-hardware.org/?probe=11f3804cb6) | Jan 01, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3b6d1593c8](https://linux-hardware.org/?probe=3b6d1593c8) | Jan 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | [54089a466b](https://linux-hardware.org/?probe=54089a466b) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f16b55ea54](https://linux-hardware.org/?probe=f16b55ea54) | Dec 31, 2022 |
| Shuttle       | SH570                       | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| ASRock        | A320M-DVS R4.0              | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c45e0f54fd](https://linux-hardware.org/?probe=c45e0f54fd) | Dec 31, 2022 |
| Shuttle       | SH570                       | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| ASRock        | X79 Extreme6                | [5ea31811b4](https://linux-hardware.org/?probe=5ea31811b4) | Dec 30, 2022 |
| MSI           | H510M-A PRO                 | [4dba3b7c55](https://linux-hardware.org/?probe=4dba3b7c55) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8289d108fb](https://linux-hardware.org/?probe=8289d108fb) | Dec 30, 2022 |
| ASUSTek       | Z87-PRO                     | [eafab9edba](https://linux-hardware.org/?probe=eafab9edba) | Dec 30, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bdc5158ffb](https://linux-hardware.org/?probe=bdc5158ffb) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [4cf9d40c0d](https://linux-hardware.org/?probe=4cf9d40c0d) | Dec 29, 2022 |
| Dell          | 0KRC95 A02                  | [7e53808767](https://linux-hardware.org/?probe=7e53808767) | Dec 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [12c052156c](https://linux-hardware.org/?probe=12c052156c) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [24b822291e](https://linux-hardware.org/?probe=24b822291e) | Dec 28, 2022 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| Dell          | 0N4YC8 A00                  | [fc766b2a1b](https://linux-hardware.org/?probe=fc766b2a1b) | Dec 28, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [7bb247e453](https://linux-hardware.org/?probe=7bb247e453) | Dec 28, 2022 |
| Gigabyte      | B365M D2V                   | [93f7c010a2](https://linux-hardware.org/?probe=93f7c010a2) | Dec 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ac2a0028](https://linux-hardware.org/?probe=f5ac2a0028) | Dec 28, 2022 |
| MSI           | Z97 GAMING 3                | [7aab4546f6](https://linux-hardware.org/?probe=7aab4546f6) | Dec 28, 2022 |
| ASRock        | Z370M-ITX/ac                | [f87fbed6a1](https://linux-hardware.org/?probe=f87fbed6a1) | Dec 28, 2022 |
| Gigabyte      | B650I AORUS ULTRA           | [3c25f43c23](https://linux-hardware.org/?probe=3c25f43c23) | Dec 28, 2022 |
| Itautec       | ST 4265                     | [38e4a07f9a](https://linux-hardware.org/?probe=38e4a07f9a) | Dec 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f2751df7ec](https://linux-hardware.org/?probe=f2751df7ec) | Dec 27, 2022 |
| MSI           | Z390-A PRO                  | [e2feef912f](https://linux-hardware.org/?probe=e2feef912f) | Dec 27, 2022 |
| ASRock        | AD2700-ITX                  | [d4fff49f31](https://linux-hardware.org/?probe=d4fff49f31) | Dec 27, 2022 |
| Itautec       | ST 4265                     | [8323542129](https://linux-hardware.org/?probe=8323542129) | Dec 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8d1181c71b](https://linux-hardware.org/?probe=8d1181c71b) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [4c97c87b61](https://linux-hardware.org/?probe=4c97c87b61) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [628cefc78a](https://linux-hardware.org/?probe=628cefc78a) | Dec 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b6def743ea](https://linux-hardware.org/?probe=b6def743ea) | Dec 25, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [46705eb79f](https://linux-hardware.org/?probe=46705eb79f) | Dec 25, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c7d8ce8f80](https://linux-hardware.org/?probe=c7d8ce8f80) | Dec 24, 2022 |
| ASUSTek       | PRIME Z790-P WIFI           | [e853f645cf](https://linux-hardware.org/?probe=e853f645cf) | Dec 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| MSI           | Z270M MORTAR                | [70564a2846](https://linux-hardware.org/?probe=70564a2846) | Dec 24, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bf8f02ac85](https://linux-hardware.org/?probe=bf8f02ac85) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5fa069144](https://linux-hardware.org/?probe=f5fa069144) | Dec 24, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [926850a516](https://linux-hardware.org/?probe=926850a516) | Dec 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88df914367](https://linux-hardware.org/?probe=88df914367) | Dec 23, 2022 |
| ASUSTek       | B85-PLUS                    | [16b14098bf](https://linux-hardware.org/?probe=16b14098bf) | Dec 22, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb006d2d4](https://linux-hardware.org/?probe=6eb006d2d4) | Dec 22, 2022 |
| ASUSTek       | B85-PLUS                    | [cbad10e284](https://linux-hardware.org/?probe=cbad10e284) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| HP            | 8266                        | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8428e68855](https://linux-hardware.org/?probe=8428e68855) | Dec 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd7ed31b20](https://linux-hardware.org/?probe=bd7ed31b20) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Dell          | 02YRK5 A02                  | [f5f6093483](https://linux-hardware.org/?probe=f5f6093483) | Dec 21, 2022 |
| Intel         | H81                         | [747dd5e27a](https://linux-hardware.org/?probe=747dd5e27a) | Dec 20, 2022 |
| ASRock        | Z790 Pro RS WiFi            | [d54c198ec8](https://linux-hardware.org/?probe=d54c198ec8) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [f7e97a6c6c](https://linux-hardware.org/?probe=f7e97a6c6c) | Dec 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9451dc3035](https://linux-hardware.org/?probe=9451dc3035) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [60dbf09ee4](https://linux-hardware.org/?probe=60dbf09ee4) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [6a964b9d6b](https://linux-hardware.org/?probe=6a964b9d6b) | Dec 19, 2022 |
| Gigabyte      | A520M DS3H                  | [4251c08b5d](https://linux-hardware.org/?probe=4251c08b5d) | Dec 18, 2022 |
| Dell          | 0KRC95 A02                  | [e7bb083869](https://linux-hardware.org/?probe=e7bb083869) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| ASUSTek       | P8H77-V LE                  | [3f76e320c0](https://linux-hardware.org/?probe=3f76e320c0) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | [fed4383ac0](https://linux-hardware.org/?probe=fed4383ac0) | Dec 18, 2022 |
| MSI           | B550-A PRO                  | [53c582a7f6](https://linux-hardware.org/?probe=53c582a7f6) | Dec 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [561aa4411a](https://linux-hardware.org/?probe=561aa4411a) | Dec 18, 2022 |
| ASUSTek       | PRIME B550M-K               | [0c496cdb01](https://linux-hardware.org/?probe=0c496cdb01) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| Gigabyte      | J1900M-D2P                  | [26ecfabc95](https://linux-hardware.org/?probe=26ecfabc95) | Dec 17, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [1bb7d1bffe](https://linux-hardware.org/?probe=1bb7d1bffe) | Dec 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [88d55eced8](https://linux-hardware.org/?probe=88d55eced8) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [54132f7285](https://linux-hardware.org/?probe=54132f7285) | Dec 17, 2022 |
| HP            | 82F2 A01                    | [859d719a2a](https://linux-hardware.org/?probe=859d719a2a) | Dec 16, 2022 |
| Gigabyte      | Z77MX-D3H                   | [50ba321b50](https://linux-hardware.org/?probe=50ba321b50) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [04bbc083d7](https://linux-hardware.org/?probe=04bbc083d7) | Dec 16, 2022 |
| ASUSTek       | PRIME B550M-K               | [5148fddbd1](https://linux-hardware.org/?probe=5148fddbd1) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| Lenovo        | 31900003 STD                | [81dea8d96e](https://linux-hardware.org/?probe=81dea8d96e) | Dec 15, 2022 |
| ASRock        | X670E Steel Legend          | [fec86201de](https://linux-hardware.org/?probe=fec86201de) | Dec 15, 2022 |
| MSI           | B550-A PRO B02              | [3a1ebe10f8](https://linux-hardware.org/?probe=3a1ebe10f8) | Dec 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2e9fac9df4](https://linux-hardware.org/?probe=2e9fac9df4) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [572f0231a5](https://linux-hardware.org/?probe=572f0231a5) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a0d17e1d50](https://linux-hardware.org/?probe=a0d17e1d50) | Dec 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [cb7bfc231e](https://linux-hardware.org/?probe=cb7bfc231e) | Dec 15, 2022 |
| Intel         | DQ67SW AAG12527-309         | [3b826b42e0](https://linux-hardware.org/?probe=3b826b42e0) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [fa4afa166d](https://linux-hardware.org/?probe=fa4afa166d) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| ASUSTek       | Z97-A                       | [5cde0cdcc4](https://linux-hardware.org/?probe=5cde0cdcc4) | Dec 14, 2022 |
| HP            | 18E4                        | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| Dell          | 0M5DCD A00                  | [61c4e63c2d](https://linux-hardware.org/?probe=61c4e63c2d) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [1ccd39b328](https://linux-hardware.org/?probe=1ccd39b328) | Dec 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b20a4554c5](https://linux-hardware.org/?probe=b20a4554c5) | Dec 14, 2022 |
| Dell          | 0YJMC0 A01                  | [59de758672](https://linux-hardware.org/?probe=59de758672) | Dec 14, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1800fc9efb](https://linux-hardware.org/?probe=1800fc9efb) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | [bf6f0c23a2](https://linux-hardware.org/?probe=bf6f0c23a2) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| MSI           | PRO B650M-A WIFI            | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [469dfe26a6](https://linux-hardware.org/?probe=469dfe26a6) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| Gigabyte      | H370M DS3H-CF               | [8c1901e5d6](https://linux-hardware.org/?probe=8c1901e5d6) | Dec 11, 2022 |
| ASRock        | 760GM-HD                    | [03fdf6453b](https://linux-hardware.org/?probe=03fdf6453b) | Dec 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [6bf96cf0fc](https://linux-hardware.org/?probe=6bf96cf0fc) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Lenovo        | ThinkStation S30 056851U    | [8c7b6cfca0](https://linux-hardware.org/?probe=8c7b6cfca0) | Dec 10, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [4f1f6fde97](https://linux-hardware.org/?probe=4f1f6fde97) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [a9351a042f](https://linux-hardware.org/?probe=a9351a042f) | Dec 10, 2022 |
| Gigabyte      | A520I AC                    | [39d35f8e37](https://linux-hardware.org/?probe=39d35f8e37) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| ASRock        | X670E Steel Legend          | [11df680f78](https://linux-hardware.org/?probe=11df680f78) | Dec 09, 2022 |
| Gigabyte      | G31_ICH7                    | [d433eed3f1](https://linux-hardware.org/?probe=d433eed3f1) | Dec 09, 2022 |
| Dell          | 0GU083 A00                  | [1f3f73a41c](https://linux-hardware.org/?probe=1f3f73a41c) | Dec 09, 2022 |
| Gigabyte      | Z77MX-D3H                   | [b77b64cc48](https://linux-hardware.org/?probe=b77b64cc48) | Dec 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bcb55a7e4c](https://linux-hardware.org/?probe=bcb55a7e4c) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bddf744d58](https://linux-hardware.org/?probe=bddf744d58) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [a875eabf3d](https://linux-hardware.org/?probe=a875eabf3d) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [6ab58fe686](https://linux-hardware.org/?probe=6ab58fe686) | Dec 09, 2022 |
| Apple         | Mac-F221BEC8                | [07e4a8072a](https://linux-hardware.org/?probe=07e4a8072a) | Dec 09, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [42f14a38dd](https://linux-hardware.org/?probe=42f14a38dd) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5544994d11](https://linux-hardware.org/?probe=5544994d11) | Dec 08, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [cb246bfc71](https://linux-hardware.org/?probe=cb246bfc71) | Dec 08, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [1b0ddaccb8](https://linux-hardware.org/?probe=1b0ddaccb8) | Dec 08, 2022 |
| Shenzhen M... | HX90G                       | [83a892b661](https://linux-hardware.org/?probe=83a892b661) | Dec 08, 2022 |
| Gigabyte      | A520I AC                    | [cbdee77af1](https://linux-hardware.org/?probe=cbdee77af1) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e40a7efd61](https://linux-hardware.org/?probe=e40a7efd61) | Dec 08, 2022 |
| Gigabyte      | G41MT-S2                    | [f69d93aece](https://linux-hardware.org/?probe=f69d93aece) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [551e0142a8](https://linux-hardware.org/?probe=551e0142a8) | Dec 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [6f715ffe60](https://linux-hardware.org/?probe=6f715ffe60) | Dec 08, 2022 |
| Gigabyte      | B450M AORUS ELITE           | [7f45781139](https://linux-hardware.org/?probe=7f45781139) | Dec 08, 2022 |
| MSI           | B550-A PRO                  | [804710787d](https://linux-hardware.org/?probe=804710787d) | Dec 08, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [61a9d5f84c](https://linux-hardware.org/?probe=61a9d5f84c) | Dec 07, 2022 |
| Gigabyte      | X570 GAMING X               | [811b0e1a71](https://linux-hardware.org/?probe=811b0e1a71) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5be32d156a](https://linux-hardware.org/?probe=5be32d156a) | Dec 06, 2022 |
| HP            | 8767 A                      | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| Acer          | FMP55                       | [78aabc71bf](https://linux-hardware.org/?probe=78aabc71bf) | Dec 05, 2022 |
| Unknown       | HX90                        | [9f3f9dec0b](https://linux-hardware.org/?probe=9f3f9dec0b) | Dec 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| HP            | 8860 A                      | [23fde1381a](https://linux-hardware.org/?probe=23fde1381a) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | 0M017G A00                  | [d6b5487094](https://linux-hardware.org/?probe=d6b5487094) | Dec 05, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cff58a3529](https://linux-hardware.org/?probe=cff58a3529) | Dec 04, 2022 |
| ASRock        | X300-ITX                    | [77d8c41481](https://linux-hardware.org/?probe=77d8c41481) | Dec 04, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| HP            | 158B                        | [5652b24e0d](https://linux-hardware.org/?probe=5652b24e0d) | Dec 04, 2022 |
| HP            | 158B                        | [015085e084](https://linux-hardware.org/?probe=015085e084) | Dec 04, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [0a626fffe5](https://linux-hardware.org/?probe=0a626fffe5) | Dec 04, 2022 |
| Gigabyte      | GA-970A-DS3                 | [8c06e98cf8](https://linux-hardware.org/?probe=8c06e98cf8) | Dec 03, 2022 |
| Dell          | 0N826N A02                  | [e9f0634dd6](https://linux-hardware.org/?probe=e9f0634dd6) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [80bba2043d](https://linux-hardware.org/?probe=80bba2043d) | Dec 03, 2022 |
| Unknown       | HX90                        | [40847bd89b](https://linux-hardware.org/?probe=40847bd89b) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| HP            | 0A98h                       | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [07a15db1a6](https://linux-hardware.org/?probe=07a15db1a6) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [6c18ee8479](https://linux-hardware.org/?probe=6c18ee8479) | Dec 02, 2022 |
| Itautec       | ST 4265                     | [d31a6b4c0f](https://linux-hardware.org/?probe=d31a6b4c0f) | Dec 01, 2022 |
| Positivo      | POS-PIQ57BQA                | [8403658c27](https://linux-hardware.org/?probe=8403658c27) | Dec 01, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [9cd70143b5](https://linux-hardware.org/?probe=9cd70143b5) | Dec 01, 2022 |
| HP            | 0A98h                       | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [42932dd5fd](https://linux-hardware.org/?probe=42932dd5fd) | Dec 01, 2022 |
| ASUSTek       | PRIME X370-PRO              | [aa87dfdc13](https://linux-hardware.org/?probe=aa87dfdc13) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Gigabyte      | X570 GAMING X               | [7ea2de1a3b](https://linux-hardware.org/?probe=7ea2de1a3b) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK S       | [2c5c1d6071](https://linux-hardware.org/?probe=2c5c1d6071) | Nov 30, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASUSTek       | GA15DH                      | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [81a61c4765](https://linux-hardware.org/?probe=81a61c4765) | Nov 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [521f5c20a9](https://linux-hardware.org/?probe=521f5c20a9) | Nov 26, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | [0e35d31780](https://linux-hardware.org/?probe=0e35d31780) | Nov 26, 2022 |
| Gigabyte      | B550 GAMING X               | [b9264b2557](https://linux-hardware.org/?probe=b9264b2557) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [33f5823764](https://linux-hardware.org/?probe=33f5823764) | Nov 25, 2022 |
| ASUSTek       | PRIME B360M-D               | [67a7943b8d](https://linux-hardware.org/?probe=67a7943b8d) | Nov 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6f867d822a](https://linux-hardware.org/?probe=6f867d822a) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bf1722d4d6](https://linux-hardware.org/?probe=bf1722d4d6) | Nov 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| ASUSTek       | GA15DH                      | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee5b760222](https://linux-hardware.org/?probe=ee5b760222) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Dell          | 0J3C2F A02                  | [0cfd78c6bb](https://linux-hardware.org/?probe=0cfd78c6bb) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | [e89ecf8da4](https://linux-hardware.org/?probe=e89ecf8da4) | Nov 23, 2022 |
| MSI           | 2A9C                        | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | 2A9C                        | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [587aa317bd](https://linux-hardware.org/?probe=587aa317bd) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE V2               | [d126214b62](https://linux-hardware.org/?probe=d126214b62) | Nov 22, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| ASUSTek       | PRIME Z270-A                | [540d321764](https://linux-hardware.org/?probe=540d321764) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Gigabyte      | H310M S2H x.x               | [97ea29ed26](https://linux-hardware.org/?probe=97ea29ed26) | Nov 20, 2022 |
| Dell          | 0HY9JP A02                  | [fa0e9792f0](https://linux-hardware.org/?probe=fa0e9792f0) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASRock        | B450 Pro4                   | [cd0f63540b](https://linux-hardware.org/?probe=cd0f63540b) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [ecceccb3b7](https://linux-hardware.org/?probe=ecceccb3b7) | Nov 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d304f26226](https://linux-hardware.org/?probe=d304f26226) | Nov 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [050e6cfd68](https://linux-hardware.org/?probe=050e6cfd68) | Nov 19, 2022 |
| ASUSTek       | Z97-P                       | [75748e49d9](https://linux-hardware.org/?probe=75748e49d9) | Nov 19, 2022 |
| Gigabyte      | M720-US3                    | [299b2cd745](https://linux-hardware.org/?probe=299b2cd745) | Nov 18, 2022 |
| Acer          | FMP55                       | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASRock        | X300-ITX                    | [54f7198f58](https://linux-hardware.org/?probe=54f7198f58) | Nov 18, 2022 |
| ASRock        | X670E Pro RS                | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | H81M-R                      | [cd129bebe1](https://linux-hardware.org/?probe=cd129bebe1) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| Intel         | DX79SR AAG57199-200         | [b12b9ec8d5](https://linux-hardware.org/?probe=b12b9ec8d5) | Nov 16, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [a84e5c2107](https://linux-hardware.org/?probe=a84e5c2107) | Nov 13, 2022 |
| ASUSTek       | PRIME A320M-E               | [2eacb090ee](https://linux-hardware.org/?probe=2eacb090ee) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-E               | [a35ca3673b](https://linux-hardware.org/?probe=a35ca3673b) | Nov 12, 2022 |
| MSI           | Z390-A PRO                  | [e851ddd11a](https://linux-hardware.org/?probe=e851ddd11a) | Nov 10, 2022 |
| ASRock        | H310M-STX                   | [cb421b22a5](https://linux-hardware.org/?probe=cb421b22a5) | Nov 09, 2022 |
| Lenovo        | ThinkCentre A70z 0401G6M    | [f2afc66464](https://linux-hardware.org/?probe=f2afc66464) | Nov 09, 2022 |
| Gigabyte      | B85M-D3V-A                  | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Dell          | 09WH54 A00                  | [c7723a2b2f](https://linux-hardware.org/?probe=c7723a2b2f) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [fa33ccff27](https://linux-hardware.org/?probe=fa33ccff27) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [02104ae91b](https://linux-hardware.org/?probe=02104ae91b) | Nov 05, 2022 |
| ASRock        | X570 Taichi                 | [d9902c03cb](https://linux-hardware.org/?probe=d9902c03cb) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [108df7bc6d](https://linux-hardware.org/?probe=108df7bc6d) | Nov 05, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a2c8fe2afa](https://linux-hardware.org/?probe=a2c8fe2afa) | Nov 05, 2022 |
| MSI           | Z390-A PRO                  | [5cfd4967b0](https://linux-hardware.org/?probe=5cfd4967b0) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | 8459                        | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| ASUSTek       | B150 PRO GAMING             | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| Gigabyte      | B85M-D3V-A                  | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | B450M MORTAR                | [44e8a164d1](https://linux-hardware.org/?probe=44e8a164d1) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | [055062356e](https://linux-hardware.org/?probe=055062356e) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [db4db1b508](https://linux-hardware.org/?probe=db4db1b508) | Oct 25, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| HP            | 2B05                        | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7f855c9b05](https://linux-hardware.org/?probe=7f855c9b05) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [77b57dbe12](https://linux-hardware.org/?probe=77b57dbe12) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [13f4800fa8](https://linux-hardware.org/?probe=13f4800fa8) | Oct 20, 2022 |
| Gigabyte      | 970A-DS3P FX                | [e0c8c2fe15](https://linux-hardware.org/?probe=e0c8c2fe15) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| Dell          | 0WR7PY A02                  | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| Gigabyte      | H610M H DDR4                | [985b192440](https://linux-hardware.org/?probe=985b192440) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Gigabyte      | H610M H DDR4                | [05fa96288f](https://linux-hardware.org/?probe=05fa96288f) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| ASUSTek       | PRIME B660M-A D4            | [f1fcb66794](https://linux-hardware.org/?probe=f1fcb66794) | Oct 12, 2022 |
| MSI           | B450M-A PRO MAX             | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| Dell          | 0RY007                      | [745f69ec3d](https://linux-hardware.org/?probe=745f69ec3d) | Oct 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| Gigabyte      | B550M DS3H                  | [2f8557640c](https://linux-hardware.org/?probe=2f8557640c) | Oct 02, 2022 |
| ASUSTek       | PRIME Z270-A                | [4118e245a3](https://linux-hardware.org/?probe=4118e245a3) | Sep 29, 2022 |
| Intel         | DP35DP AAD81073-208         | [031ff09179](https://linux-hardware.org/?probe=031ff09179) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| Acer          | Aspire X1900                | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [54d3096bb6](https://linux-hardware.org/?probe=54d3096bb6) | Sep 21, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | Z170-A                      | [aad09d3281](https://linux-hardware.org/?probe=aad09d3281) | Sep 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [424e3ded44](https://linux-hardware.org/?probe=424e3ded44) | Sep 19, 2022 |
| HP            | 2B05                        | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| HP            | 3397                        | [637a5570cf](https://linux-hardware.org/?probe=637a5570cf) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| Gigabyte      | B85M-D3V-A                  | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| ASUSTek       | PRIME Z270-A                | [2642647feb](https://linux-hardware.org/?probe=2642647feb) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| HP            | 1998                        | [bf93a500f4](https://linux-hardware.org/?probe=bf93a500f4) | Sep 14, 2022 |
| MSI           | Z370 TOMAHAWK               | [251d227686](https://linux-hardware.org/?probe=251d227686) | Aug 22, 2022 |
| Dell          | 08NPPY A00                  | [93eb00c3c5](https://linux-hardware.org/?probe=93eb00c3c5) | Jun 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [2cd65296c2](https://linux-hardware.org/?probe=2cd65296c2) | May 08, 2022 |
| HP            | 0B54h D                     | [7153ec172b](https://linux-hardware.org/?probe=7153ec172b) | Mar 21, 2022 |
| HP            | 0B54h D                     | [399cc50503](https://linux-hardware.org/?probe=399cc50503) | Mar 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_37/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.0.15-300.fc37.x86_64  | 45       | 6.46%   |
| 6.0.12-300.fc37.x86_64  | 44       | 6.31%   |
| 6.0.7-301.fc37.x86_64   | 37       | 5.31%   |
| 6.1.18-200.fc37.x86_64  | 32       | 4.59%   |
| 6.0.11-300.fc37.x86_64  | 31       | 4.45%   |
| 6.0.9-300.fc37.x86_64   | 27       | 3.87%   |
| 6.0.8-300.fc37.x86_64   | 27       | 3.87%   |
| 6.1.14-200.fc37.x86_64  | 25       | 3.59%   |
| 6.1.8-200.fc37.x86_64   | 22       | 3.16%   |
| 6.1.11-200.fc37.x86_64  | 22       | 3.16%   |
| 6.2.7-200.fc37.x86_64   | 21       | 3.01%   |
| 6.1.9-200.fc37.x86_64   | 21       | 3.01%   |
| 6.0.10-300.fc37.x86_64  | 21       | 3.01%   |
| 6.1.6-200.fc37.x86_64   | 19       | 2.73%   |
| 6.1.7-200.fc37.x86_64   | 18       | 2.58%   |
| 6.1.13-200.fc37.x86_64  | 18       | 2.58%   |
| 6.2.8-200.fc37.x86_64   | 16       | 2.3%    |
| 6.1.15-200.fc37.x86_64  | 16       | 2.3%    |
| 6.2.10-200.fc37.x86_64  | 14       | 2.01%   |
| 6.2.9-200.fc37.x86_64   | 13       | 1.87%   |
| 6.1.10-200.fc37.x86_64  | 13       | 1.87%   |
| 5.19.16-301.fc37.x86_64 | 12       | 1.72%   |
| 6.2.15-200.fc37.x86_64  | 10       | 1.43%   |
| 6.1.5-200.fc37.x86_64   | 10       | 1.43%   |
| 6.1.12-200.fc37.x86_64  | 10       | 1.43%   |
| 6.2.14-200.fc37.x86_64  | 9        | 1.29%   |
| 6.0.17-300.fc37.x86_64  | 9        | 1.29%   |
| 6.0.18-300.fc37.x86_64  | 8        | 1.15%   |
| 6.0.16-300.fc37.x86_64  | 8        | 1.15%   |
| 6.0.14-300.fc37.x86_64  | 8        | 1.15%   |
| 5.19.9-300.fc37.x86_64  | 8        | 1.15%   |
| 5.19.13-300.fc37.x86_64 | 8        | 1.15%   |
| 6.2.12-200.fc37.x86_64  | 5        | 0.72%   |
| 6.2.11-200.fc37.x86_64  | 5        | 0.72%   |
| 6.0.13-300.fc37.x86_64  | 5        | 0.72%   |
| 6.3.8-100.fc37.x86_64   | 4        | 0.57%   |
| 5.19.7-300.fc37.x86_64  | 4        | 0.57%   |
| 6.5.5-100.fc37.x86_64   | 3        | 0.43%   |
| 6.4.4-100.fc37.x86_64   | 3        | 0.43%   |
| 6.4.13-100.fc37.x86_64  | 3        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0.15  | 45       | 6.46%   |
| 6.0.12  | 44       | 6.31%   |
| 6.0.7   | 37       | 5.31%   |
| 6.1.18  | 35       | 5.02%   |
| 6.0.11  | 32       | 4.59%   |
| 6.1.14  | 27       | 3.87%   |
| 6.0.9   | 27       | 3.87%   |
| 6.0.8   | 27       | 3.87%   |
| 6.2.7   | 23       | 3.3%    |
| 6.1.8   | 23       | 3.3%    |
| 6.1.11  | 23       | 3.3%    |
| 6.0.10  | 23       | 3.3%    |
| 6.1.9   | 21       | 3.01%   |
| 6.1.6   | 19       | 2.73%   |
| 6.1.7   | 18       | 2.58%   |
| 6.1.13  | 18       | 2.58%   |
| 6.2.8   | 16       | 2.3%    |
| 6.1.15  | 16       | 2.3%    |
| 6.2.10  | 15       | 2.15%   |
| 5.19.16 | 15       | 2.15%   |
| 6.2.9   | 13       | 1.87%   |
| 6.1.10  | 13       | 1.87%   |
| 6.1.5   | 11       | 1.58%   |
| 6.2.15  | 10       | 1.43%   |
| 6.1.12  | 10       | 1.43%   |
| 6.2.14  | 9        | 1.29%   |
| 6.0.17  | 9        | 1.29%   |
| 6.0.18  | 8        | 1.15%   |
| 6.0.16  | 8        | 1.15%   |
| 6.0.14  | 8        | 1.15%   |
| 5.19.9  | 8        | 1.15%   |
| 5.19.13 | 8        | 1.15%   |
| 6.0.13  | 6        | 0.86%   |
| 6.2.12  | 5        | 0.72%   |
| 6.2.11  | 5        | 0.72%   |
| 6.3.8   | 4        | 0.57%   |
| 5.19.8  | 4        | 0.57%   |
| 5.19.7  | 4        | 0.57%   |
| 6.5.5   | 3        | 0.43%   |
| 6.4.4   | 3        | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.0     | 268      | 40.42%  |
| 6.1     | 223      | 33.63%  |
| 6.2     | 98       | 14.78%  |
| 5.19    | 45       | 6.79%   |
| 6.4     | 14       | 2.11%   |
| 6.3     | 8        | 1.21%   |
| 6.5     | 3        | 0.45%   |
| 5.8     | 1        | 0.15%   |
| 5.18    | 1        | 0.15%   |
| 5.17    | 1        | 0.15%   |
| 5.16    | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 610      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| GNOME                        | 418      | 68.41%  |
| KDE5                         | 122      | 19.97%  |
| Unknown                      | 17       | 2.78%   |
| XFCE                         | 13       | 2.13%   |
| X-Cinnamon                   | 9        | 1.47%   |
| Cinnamon                     | 9        | 1.47%   |
| MATE                         | 6        | 0.98%   |
| GNOME Classic                | 4        | 0.65%   |
| Xpra                         | 3        | 0.49%   |
| sway                         | 2        | 0.33%   |
| LXQt                         | 2        | 0.33%   |
| bspwm                        | 2        | 0.33%   |
| qtile                        | 1        | 0.16%   |
| LXDE                         | 1        | 0.16%   |
| i3                           | 1        | 0.16%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 383      | 62.07%  |
| X11     | 202      | 32.74%  |
| Tty     | 22       | 3.57%   |
| Unknown | 10       | 1.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 347      | 56.42%  |
| GDM     | 168      | 27.32%  |
| SDDM    | 55       | 8.94%   |
| LightDM | 44       | 7.15%   |
| LXDM    | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 307      | 50.16%  |
| en_GB   | 44       | 7.19%   |
| ru_RU   | 40       | 6.54%   |
| pt_BR   | 37       | 6.05%   |
| en_AU   | 24       | 3.92%   |
| de_DE   | 24       | 3.92%   |
| en_CA   | 17       | 2.78%   |
| es_ES   | 14       | 2.29%   |
| pl_PL   | 13       | 2.12%   |
| it_IT   | 13       | 2.12%   |
| fr_FR   | 13       | 2.12%   |
| en_NZ   | 5        | 0.82%   |
| en_IN   | 4        | 0.65%   |
| cs_CZ   | 4        | 0.65%   |
| hu_HU   | 3        | 0.49%   |
| fi_FI   | 3        | 0.49%   |
| es_CL   | 3        | 0.49%   |
| Unknown | 3        | 0.49%   |
| vi_VN   | 2        | 0.33%   |
| tr_TR   | 2        | 0.33%   |
| sv_SE   | 2        | 0.33%   |
| nl_NL   | 2        | 0.33%   |
| ko_KR   | 2        | 0.33%   |
| fr_BE   | 2        | 0.33%   |
| es_MX   | 2        | 0.33%   |
| es_AR   | 2        | 0.33%   |
| en_IL   | 2        | 0.33%   |
| en_IE   | 2        | 0.33%   |
| de_AT   | 2        | 0.33%   |
| C       | 2        | 0.33%   |
| zh_CN   | 1        | 0.16%   |
| th_TH   | 1        | 0.16%   |
| sr_RS   | 1        | 0.16%   |
| ru_UA   | 1        | 0.16%   |
| pt_PT   | 1        | 0.16%   |
| nl_BE   | 1        | 0.16%   |
| nb_NO   | 1        | 0.16%   |
| ja_JP   | 1        | 0.16%   |
| es_UY   | 1        | 0.16%   |
| es_US   | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 433      | 70.41%  |
| BIOS | 182      | 29.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 460      | 75.41%  |
| Ext4  | 126      | 20.66%  |
| Xfs   | 22       | 3.61%   |
| F2fs  | 2        | 0.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 331      | 53.56%  |
| GPT     | 245      | 39.64%  |
| MBR     | 42       | 6.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 530      | 86.18%  |
| Yes       | 85       | 13.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 485      | 78.99%  |
| Yes       | 129      | 21.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 189      | 30.98%  |
| MSI                                  | 106      | 17.38%  |
| Gigabyte Technology                  | 106      | 17.38%  |
| ASRock                               | 60       | 9.84%   |
| Dell                                 | 43       | 7.05%   |
| Hewlett-Packard                      | 28       | 4.59%   |
| Lenovo                               | 16       | 2.62%   |
| Intel                                | 13       | 2.13%   |
| Acer                                 | 7        | 1.15%   |
| Huanan                               | 4        | 0.66%   |
| Unknown                              | 4        | 0.66%   |
| Positivo                             | 3        | 0.49%   |
| Pegatron                             | 3        | 0.49%   |
| Itautec                              | 3        | 0.49%   |
| ECS                                  | 3        | 0.49%   |
| AZW                                  | 3        | 0.49%   |
| Fujitsu                              | 2        | 0.33%   |
| BESSTAR Tech                         | 2        | 0.33%   |
| Apple                                | 2        | 0.33%   |
| Win element                          | 1        | 0.16%   |
| System76                             | 1        | 0.16%   |
| Supermicro                           | 1        | 0.16%   |
| Shuttle                              | 1        | 0.16%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.16%   |
| NZXT                                 | 1        | 0.16%   |
| Medion                               | 1        | 0.16%   |
| MACHINIST                            | 1        | 0.16%   |
| Gateway                              | 1        | 0.16%   |
| GALAX                                | 1        | 0.16%   |
| Compal                               | 1        | 0.16%   |
| ASRockRack                           | 1        | 0.16%   |
| Alienware                            | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 17       | 2.79%   |
| Dell OptiPlex 7010                 | 8        | 1.31%   |
| ASUS TUF Gaming X570-PLUS          | 7        | 1.15%   |
| MSI MS-7C37                        | 6        | 0.98%   |
| ASUS TUF Gaming B550M-PLUS         | 5        | 0.82%   |
| MSI MS-7C91                        | 4        | 0.66%   |
| MSI MS-7C84                        | 4        | 0.66%   |
| MSI MS-7C56                        | 4        | 0.66%   |
| MSI MS-7C02                        | 4        | 0.66%   |
| MSI MS-7B89                        | 4        | 0.66%   |
| MSI MS-7A38                        | 4        | 0.66%   |
| ASUS ROG STRIX B450-F GAMING       | 4        | 0.66%   |
| ASUS ProArt Z690-CREATOR WIFI      | 4        | 0.66%   |
| ASUS ProArt X670E-CREATOR WIFI     | 4        | 0.66%   |
| ASUS PRIME B450M-A II              | 4        | 0.66%   |
| Unknown                            | 4        | 0.66%   |
| MSI MS-7C94                        | 3        | 0.49%   |
| MSI MS-7C52                        | 3        | 0.49%   |
| MSI MS-7971                        | 3        | 0.49%   |
| Gigabyte Z370 AORUS Ultra Gaming   | 3        | 0.49%   |
| Gigabyte B550M DS3H                | 3        | 0.49%   |
| Dell OptiPlex 9020                 | 3        | 0.49%   |
| Dell OptiPlex 790                  | 3        | 0.49%   |
| ASUS Z170 PRO GAMING               | 3        | 0.49%   |
| ASUS ROG STRIX X670E-F GAMING WIFI | 3        | 0.49%   |
| ASUS ROG STRIX X570-E GAMING       | 3        | 0.49%   |
| ASUS ROG STRIX B550-F GAMING       | 3        | 0.49%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI    | 3        | 0.49%   |
| ASUS PRIME X370-PRO                | 3        | 0.49%   |
| ASUS PRIME B550M-A                 | 3        | 0.49%   |
| ASUS PRIME B550-PLUS               | 3        | 0.49%   |
| ASUS PRIME B450M-GAMING/BR         | 3        | 0.49%   |
| ASRock B450M-HDV R4.0              | 3        | 0.49%   |
| Positivo POS-PIQ57BQ               | 2        | 0.33%   |
| MSI MS-7D25                        | 2        | 0.33%   |
| MSI MS-7D22                        | 2        | 0.33%   |
| MSI MS-7C95                        | 2        | 0.33%   |
| MSI MS-7C82                        | 2        | 0.33%   |
| MSI MS-7B98                        | 2        | 0.33%   |
| MSI MS-7B93                        | 2        | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 47       | 7.7%    |
| ASUS ROG           | 40       | 6.56%   |
| ASUS TUF           | 35       | 5.74%   |
| Dell OptiPlex      | 26       | 4.26%   |
| ASUS All           | 17       | 2.79%   |
| Gigabyte X570      | 9        | 1.48%   |
| Lenovo ThinkCentre | 8        | 1.31%   |
| ASUS ProArt        | 8        | 1.31%   |
| Gigabyte B550      | 7        | 1.15%   |
| Dell Precision     | 7        | 1.15%   |
| Dell Inspiron      | 7        | 1.15%   |
| MSI MS-7C37        | 6        | 0.98%   |
| HP Compaq          | 5        | 0.82%   |
| Gigabyte B550M     | 5        | 0.82%   |
| ASRock X570        | 5        | 0.82%   |
| MSI MS-7C91        | 4        | 0.66%   |
| MSI MS-7C84        | 4        | 0.66%   |
| MSI MS-7C56        | 4        | 0.66%   |
| MSI MS-7C02        | 4        | 0.66%   |
| MSI MS-7B89        | 4        | 0.66%   |
| MSI MS-7A38        | 4        | 0.66%   |
| Gigabyte B450M     | 4        | 0.66%   |
| Gigabyte B450      | 4        | 0.66%   |
| ASRock X670E       | 4        | 0.66%   |
| ASRock B450M       | 4        | 0.66%   |
| Acer Aspire        | 4        | 0.66%   |
| Unknown            | 4        | 0.66%   |
| MSI MS-7C94        | 3        | 0.49%   |
| MSI MS-7C52        | 3        | 0.49%   |
| MSI MS-7971        | 3        | 0.49%   |
| HP Pavilion        | 3        | 0.49%   |
| HP EliteDesk       | 3        | 0.49%   |
| Gigabyte Z370      | 3        | 0.49%   |
| Gigabyte X570S     | 3        | 0.49%   |
| Gigabyte B365M     | 3        | 0.49%   |
| Dell XPS           | 3        | 0.49%   |
| ASUS Z170          | 3        | 0.49%   |
| ASUS SABERTOOTH    | 3        | 0.49%   |
| ASUS Pro           | 3        | 0.49%   |
| ASUS P8Z77-V       | 3        | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 85       | 13.93%  |
| 2019    | 79       | 12.95%  |
| 2018    | 70       | 11.48%  |
| 2022    | 56       | 9.18%   |
| 2021    | 52       | 8.52%   |
| 2017    | 47       | 7.7%    |
| 2012    | 42       | 6.89%   |
| 2013    | 38       | 6.23%   |
| 2014    | 28       | 4.59%   |
| 2015    | 24       | 3.93%   |
| 2011    | 21       | 3.44%   |
| 2010    | 19       | 3.11%   |
| 2016    | 16       | 2.62%   |
| 2009    | 16       | 2.62%   |
| 2008    | 9        | 1.48%   |
| 2006    | 4        | 0.66%   |
| 2007    | 2        | 0.33%   |
| 2023    | 1        | 0.16%   |
| Unknown | 1        | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 610      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 552      | 90.2%   |
| Enabled  | 60       | 9.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 610      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 189      | 30.68%  |
| 32.01-64.0      | 164      | 26.62%  |
| 8.01-16.0       | 83       | 13.47%  |
| 64.01-256.0     | 60       | 9.74%   |
| 4.01-8.0        | 46       | 7.47%   |
| 24.01-32.0      | 39       | 6.33%   |
| 3.01-4.0        | 29       | 4.71%   |
| 1.01-2.0        | 3        | 0.49%   |
| More than 256.0 | 2        | 0.32%   |
| 2.01-3.0        | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 222      | 33.59%  |
| 3.01-4.0   | 145      | 21.94%  |
| 2.01-3.0   | 132      | 19.97%  |
| 8.01-16.0  | 73       | 11.04%  |
| 1.01-2.0   | 59       | 8.93%   |
| 0.51-1.0   | 14       | 2.12%   |
| 16.01-24.0 | 9        | 1.36%   |
| 24.01-32.0 | 3        | 0.45%   |
| 32.01-64.0 | 2        | 0.3%    |
| 0.01-0.5   | 2        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 194      | 31.09%  |
| 1      | 166      | 26.6%   |
| 3      | 132      | 21.15%  |
| 4      | 66       | 10.58%  |
| 5      | 34       | 5.45%   |
| 6      | 13       | 2.08%   |
| 7      | 8        | 1.28%   |
| 8      | 3        | 0.48%   |
| 9      | 2        | 0.32%   |
| 410    | 1        | 0.16%   |
| 18     | 1        | 0.16%   |
| 15     | 1        | 0.16%   |
| 12     | 1        | 0.16%   |
| 10     | 1        | 0.16%   |
| 0      | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 436      | 71.24%  |
| Yes       | 176      | 28.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 607      | 99.35%  |
| No        | 4        | 0.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 313      | 50.98%  |
| Yes       | 301      | 49.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 316      | 51.22%  |
| Yes       | 301      | 48.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 147      | 23.9%   |
| Brazil      | 48       | 7.8%    |
| Russia      | 42       | 6.83%   |
| Germany     | 42       | 6.83%   |
| Australia   | 25       | 4.07%   |
| UK          | 24       | 3.9%    |
| Poland      | 22       | 3.58%   |
| Italy       | 21       | 3.41%   |
| Spain       | 19       | 3.09%   |
| France      | 18       | 2.93%   |
| Canada      | 18       | 2.93%   |
| Netherlands | 15       | 2.44%   |
| Sweden      | 10       | 1.63%   |
| Austria     | 9        | 1.46%   |
| Czechia     | 7        | 1.14%   |
| Belgium     | 7        | 1.14%   |
| Turkey      | 6        | 0.98%   |
| Romania     | 6        | 0.98%   |
| Norway      | 6        | 0.98%   |
| New Zealand | 6        | 0.98%   |
| India       | 6        | 0.98%   |
| Colombia    | 6        | 0.98%   |
| Vietnam     | 5        | 0.81%   |
| Switzerland | 5        | 0.81%   |
| Hungary     | 5        | 0.81%   |
| Finland     | 5        | 0.81%   |
| Thailand    | 4        | 0.65%   |
| Portugal    | 4        | 0.65%   |
| Israel      | 4        | 0.65%   |
| Greece      | 4        | 0.65%   |
| Taiwan      | 3        | 0.49%   |
| South Korea | 3        | 0.49%   |
| Mexico      | 3        | 0.49%   |
| Malaysia    | 3        | 0.49%   |
| Latvia      | 3        | 0.49%   |
| Japan       | 3        | 0.49%   |
| Indonesia   | 3        | 0.49%   |
| Chile       | 3        | 0.49%   |
| Belarus     | 3        | 0.49%   |
| Argentina   | 3        | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Sydney           | 14       | 2.19%   |
| Moscow           | 11       | 1.72%   |
| Warsaw           | 6        | 0.94%   |
| Palmas           | 6        | 0.94%   |
| Berlin           | 6        | 0.94%   |
| Seattle          | 5        | 0.78%   |
| Sao Paulo        | 5        | 0.78%   |
| Yekaterinburg    | 4        | 0.63%   |
| Vienna           | 4        | 0.63%   |
| Melbourne        | 4        | 0.63%   |
| London           | 4        | 0.63%   |
| Budapest         | 4        | 0.63%   |
| Auckland         | 4        | 0.63%   |
| Wroclaw          | 3        | 0.47%   |
| Vero Beach       | 3        | 0.47%   |
| Stockholm        | 3        | 0.47%   |
| Riga             | 3        | 0.47%   |
| Porto Alegre     | 3        | 0.47%   |
| Milan            | 3        | 0.47%   |
| Krasnodar        | 3        | 0.47%   |
| Ho Chi Minh City | 3        | 0.47%   |
| Helsinki         | 3        | 0.47%   |
| Hamburg          | 3        | 0.47%   |
| Goiânia         | 3        | 0.47%   |
| Bogotá          | 3        | 0.47%   |
| Belo Horizonte   | 3        | 0.47%   |
| Atlanta          | 3        | 0.47%   |
| Volgograd        | 2        | 0.31%   |
| Verona           | 2        | 0.31%   |
| Vancouver        | 2        | 0.31%   |
| Tokyo            | 2        | 0.31%   |
| Tampa            | 2        | 0.31%   |
| St Petersburg    | 2        | 0.31%   |
| South Bend       | 2        | 0.31%   |
| Singapore        | 2        | 0.31%   |
| Saratov          | 2        | 0.31%   |
| Sarapul          | 2        | 0.31%   |
| Santiago         | 2        | 0.31%   |
| Santa Clara      | 2        | 0.31%   |
| Rome             | 2        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 241      | 410    | 19.25%  |
| WDC                         | 201      | 357    | 16.05%  |
| Seagate                     | 188      | 263    | 15.02%  |
| Kingston                    | 86       | 112    | 6.87%   |
| Sandisk                     | 83       | 111    | 6.63%   |
| Crucial                     | 71       | 96     | 5.67%   |
| Toshiba                     | 65       | 85     | 5.19%   |
| Phison Electronics          | 31       | 37     | 2.48%   |
| Intel                       | 25       | 32     | 2%      |
| Hitachi                     | 21       | 29     | 1.68%   |
| Micron/Crucial Technology   | 15       | 19     | 1.2%    |
| A-DATA Technology           | 15       | 15     | 1.2%    |
| China                       | 14       | 20     | 1.12%   |
| HGST                        | 11       | 27     | 0.88%   |
| Corsair                     | 10       | 15     | 0.8%    |
| Unknown                     | 9        | 13     | 0.72%   |
| Realtek Semiconductor       | 9        | 10     | 0.72%   |
| Apacer                      | 9        | 13     | 0.72%   |
| SK hynix                    | 8        | 8      | 0.64%   |
| Silicon Motion              | 8        | 9      | 0.64%   |
| SPCC                        | 7        | 10     | 0.56%   |
| ADATA Technology            | 7        | 7      | 0.56%   |
| PNY                         | 6        | 7      | 0.48%   |
| Micron Technology           | 5        | 6      | 0.4%    |
| Kingston Technology Company | 5        | 5      | 0.4%    |
| Plextor                     | 4        | 4      | 0.32%   |
| MAXIO Technology (Hangzhou) | 4        | 4      | 0.32%   |
| JMicron Technology          | 4        | 4      | 0.32%   |
| Intenso                     | 4        | 4      | 0.32%   |
| HS-SSD-C100                 | 4        | 4      | 0.32%   |
| ASMT                        | 4        | 5      | 0.32%   |
| Transcend                   | 3        | 3      | 0.24%   |
| Netac                       | 3        | 3      | 0.24%   |
| Maxtor                      | 3        | 4      | 0.24%   |
| Gigabyte Technology         | 3        | 3      | 0.24%   |
| Team                        | 2        | 2      | 0.16%   |
| SABRENT                     | 2        | 2      | 0.16%   |
| Patriot                     | 2        | 2      | 0.16%   |
| Mushkin                     | 2        | 2      | 0.16%   |
| LT                          | 2        | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 46       | 3.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 24       | 1.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 23       | 1.58%   |
| Kingston SA400S37240G 240GB SSD                     | 19       | 1.3%    |
| Samsung SSD 850 EVO 250GB                           | 18       | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB                      | 16       | 1.1%    |
| Phison E12 NVMe Controller 1TB                      | 15       | 1.03%   |
| Crucial CT1000MX500SSD1 1TB                         | 15       | 1.03%   |
| Kingston SA400S37120G 120GB SSD                     | 14       | 0.96%   |
| Seagate ST500DM002-1BD142 500GB                     | 13       | 0.89%   |
| Samsung SSD 860 EVO 500GB                           | 13       | 0.89%   |
| Kingston SA400S37480G 480GB SSD                     | 13       | 0.89%   |
| Samsung SSD 870 EVO 500GB                           | 12       | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 11       | 0.75%   |
| Samsung SSD 850 EVO 500GB                           | 11       | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 11       | 0.75%   |
| Toshiba DT01ACA200 2TB                              | 10       | 0.68%   |
| Samsung SSD 860 EVO 1TB                             | 10       | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB               | 10       | 0.68%   |
| Toshiba HDWD110 1TB                                 | 9        | 0.62%   |
| Samsung SSD 870 QVO 2TB                             | 9        | 0.62%   |
| Samsung SSD 870 EVO 1TB                             | 9        | 0.62%   |
| Samsung SSD 860 EVO 250GB                           | 9        | 0.62%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 9        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 9        | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 8        | 0.55%   |
| Samsung SSD 980 PRO 1TB                             | 8        | 0.55%   |
| Samsung SSD 980 1TB                                 | 8        | 0.55%   |
| Toshiba DT01ACA100 1TB                              | 7        | 0.48%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 7        | 0.48%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 7        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                      | 7        | 0.48%   |
| WDC WD40EZAZ-00SF3B0 4TB                            | 6        | 0.41%   |
| Toshiba HDWD120 2TB                                 | 6        | 0.41%   |
| Seagate ST2000DM008-2UB102 2TB                      | 6        | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB                      | 6        | 0.41%   |
| Seagate ST1000DM003-1SB102 1TB                      | 6        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB                      | 6        | 0.41%   |
| Samsung SSD 970 EVO Plus 2TB                        | 6        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 186      | 259    | 40.09%  |
| WDC                 | 168      | 296    | 36.21%  |
| Toshiba             | 54       | 69     | 11.64%  |
| Hitachi             | 21       | 29     | 4.53%   |
| Samsung Electronics | 14       | 19     | 3.02%   |
| HGST                | 11       | 27     | 2.37%   |
| Unknown             | 3        | 3      | 0.65%   |
| Maxtor              | 3        | 4      | 0.65%   |
| USB3.0              | 1        | 1      | 0.22%   |
| Intenso             | 1        | 1      | 0.22%   |
| IET                 | 1        | 1      | 0.22%   |
| ASMT                | 1        | 2      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 123      | 185    | 27.33%  |
| Crucial             | 67       | 89     | 14.89%  |
| Kingston            | 64       | 80     | 14.22%  |
| SanDisk             | 36       | 40     | 8%      |
| WDC                 | 30       | 40     | 6.67%   |
| Intel               | 14       | 17     | 3.11%   |
| China               | 14       | 20     | 3.11%   |
| A-DATA Technology   | 11       | 11     | 2.44%   |
| Toshiba             | 7        | 8      | 1.56%   |
| Corsair             | 7        | 10     | 1.56%   |
| Apacer              | 7        | 10     | 1.56%   |
| PNY                 | 6        | 7      | 1.33%   |
| SPCC                | 4        | 6      | 0.89%   |
| Transcend           | 3        | 3      | 0.67%   |
| Plextor             | 3        | 3      | 0.67%   |
| Unknown             | 2        | 2      | 0.44%   |
| SK hynix            | 2        | 2      | 0.44%   |
| SABRENT             | 2        | 2      | 0.44%   |
| Patriot             | 2        | 2      | 0.44%   |
| Mushkin             | 2        | 2      | 0.44%   |
| LT                  | 2        | 2      | 0.44%   |
| LITEON              | 2        | 2      | 0.44%   |
| Lexar               | 2        | 3      | 0.44%   |
| KingSpec            | 2        | 2      | 0.44%   |
| KingDian            | 2        | 2      | 0.44%   |
| Intenso             | 2        | 2      | 0.44%   |
| GOODRAM             | 2        | 5      | 0.44%   |
| Gigabyte Technology | 2        | 2      | 0.44%   |
| ASMT                | 2        | 2      | 0.44%   |
| XSTAR               | 1        | 1      | 0.22%   |
| VSP                 | 1        | 1      | 0.22%   |
| Verbatim            | 1        | 1      | 0.22%   |
| Vaseky              | 1        | 1      | 0.22%   |
| Team                | 1        | 1      | 0.22%   |
| Super Talent        | 1        | 1      | 0.22%   |
| Smartbuy            | 1        | 1      | 0.22%   |
| Seagate             | 1        | 1      | 0.22%   |
| OWC                 | 1        | 1      | 0.22%   |
| OCZ                 | 1        | 1      | 0.22%   |
| Netac               | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 365      | 996    | 33.89%  |
| HDD     | 358      | 711    | 33.24%  |
| NVMe    | 332      | 499    | 30.83%  |
| Unknown | 22       | 27     | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 513      | 1667   | 57.38%  |
| NVMe | 329      | 495    | 36.8%   |
| SAS  | 52       | 71     | 5.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 331      | 950    | 41.22%  |
| 0.51-1.0   | 252      | 389    | 31.38%  |
| 1.01-2.0   | 114      | 156    | 14.2%   |
| 3.01-4.0   | 41       | 70     | 5.11%   |
| 2.01-3.0   | 32       | 67     | 3.99%   |
| 4.01-10.0  | 29       | 52     | 3.61%   |
| 10.01-20.0 | 4        | 23     | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 120      | 19.32%  |
| 501-1000       | 112      | 18.04%  |
| More than 3000 | 109      | 17.55%  |
| 251-500        | 77       | 12.4%   |
| 2001-3000      | 63       | 10.14%  |
| 101-250        | 58       | 9.34%   |
| Unknown        | 32       | 5.15%   |
| 1-20           | 29       | 4.67%   |
| 51-100         | 16       | 2.58%   |
| 21-50          | 5        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 105      | 16.33%  |
| 501-1000       | 97       | 15.09%  |
| 101-250        | 83       | 12.91%  |
| 21-50          | 81       | 12.6%   |
| 251-500        | 72       | 11.2%   |
| 1001-2000      | 66       | 10.26%  |
| 51-100         | 52       | 8.09%   |
| Unknown        | 32       | 4.98%   |
| More than 3000 | 29       | 4.51%   |
| 2001-3000      | 26       | 4.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB   | 4        | 4      | 4.21%   |
| WDC WD5000AAKX-603CA0 500GB           | 2        | 2      | 2.11%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 2.11%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2        | 2      | 2.11%   |
| Seagate ST500DM002-1BD142 500GB       | 2        | 2      | 2.11%   |
| Seagate ST3500418AS 500GB             | 2        | 2      | 2.11%   |
| Seagate ST31000524AS 1TB              | 2        | 2      | 2.11%   |
| Intel SSDSC2CT120A3 120GB             | 2        | 5      | 2.11%   |
| Crucial CT275MX300SSD1 275GB          | 2        | 2      | 2.11%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1        | 1      | 1.05%   |
| WDC WD5000AVVS-63H0B1 500GB           | 1        | 1      | 1.05%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 1.05%   |
| WDC WD40PURZ-85AKKY0 4TB              | 1        | 1      | 1.05%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1        | 1      | 1.05%   |
| WDC WD3200BPVT-80JJ5T0 320GB          | 1        | 1      | 1.05%   |
| WDC WD3200AAKS-00V1A0 320GB           | 1        | 1      | 1.05%   |
| WDC WD3200AAKS-00UU3A0 320GB          | 1        | 1      | 1.05%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1        | 1      | 1.05%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1        | 1      | 1.05%   |
| WDC WD2500AAKX-753CA1 250GB           | 1        | 1      | 1.05%   |
| WDC WD20EZRX-22D8PB0 2TB              | 1        | 1      | 1.05%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1        | 1      | 1.05%   |
| WDC WD15EARS-00MVWB0 1TB              | 1        | 1      | 1.05%   |
| WDC WD140EDFZ-11A0VA0 14TB            | 1        | 2      | 1.05%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 2      | 1.05%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1        | 1      | 1.05%   |
| WDC WD10EZEX-00WN4A0 1TB              | 1        | 1      | 1.05%   |
| WDC WD10EFRX-68FYTN0 1TB              | 1        | 1      | 1.05%   |
| WDC WD10EADS-65M2B0 1TB               | 1        | 1      | 1.05%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 1      | 1.05%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1        | 1      | 1.05%   |
| Toshiba MQ01ABD050 500GB              | 1        | 1      | 1.05%   |
| Toshiba MK7559GSXP 752GB              | 1        | 1      | 1.05%   |
| Toshiba MK3263GSX 320GB               | 1        | 1      | 1.05%   |
| SPCC SPCCSolidStateDisk 128GB SSD     | 1        | 1      | 1.05%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1        | 1      | 1.05%   |
| Seagate ST8000NE001-2M7101 8TB        | 1        | 1      | 1.05%   |
| Seagate ST6000DM003-2CY186 6TB        | 1        | 1      | 1.05%   |
| Seagate ST500LM021-1KJ152 500GB       | 1        | 2      | 1.05%   |
| Seagate ST3500320AS 500GB             | 1        | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 30     | 29.21%  |
| Seagate             | 26       | 39     | 29.21%  |
| Samsung Electronics | 12       | 18     | 13.48%  |
| Crucial             | 6        | 6      | 6.74%   |
| Toshiba             | 3        | 3      | 3.37%   |
| Intel               | 3        | 6      | 3.37%   |
| SanDisk             | 2        | 2      | 2.25%   |
| Hitachi             | 2        | 2      | 2.25%   |
| Corsair             | 2        | 2      | 2.25%   |
| SPCC                | 1        | 1      | 1.12%   |
| SK hynix            | 1        | 1      | 1.12%   |
| Maxtor              | 1        | 1      | 1.12%   |
| Kingston            | 1        | 1      | 1.12%   |
| Intenso             | 1        | 1      | 1.12%   |
| AMD                 | 1        | 2      | 1.12%   |
| A-DATA Technology   | 1        | 1      | 1.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 26       | 39     | 41.27%  |
| WDC                 | 25       | 29     | 39.68%  |
| Samsung Electronics | 6        | 11     | 9.52%   |
| Toshiba             | 3        | 3      | 4.76%   |
| Hitachi             | 2        | 2      | 3.17%   |
| Maxtor              | 1        | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 57       | 85     | 68.67%  |
| SSD  | 25       | 30     | 30.12%  |
| NVMe | 1        | 1      | 1.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| SPCC M.2 PCIe SSD 2TB           | 1        | 1      | 33.33%  |
| Seagate ST31000528AS 1TB        | 1        | 2      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SPCC                | 1        | 1      | 33.33%  |
| Seagate             | 1        | 2      | 33.33%  |
| Samsung Electronics | 1        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 372      | 1024   | 52.17%  |
| Works    | 261      | 1088   | 36.61%  |
| Malfunc  | 77       | 116    | 10.8%   |
| Failed   | 3        | 5      | 0.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 331      | 31.67%  |
| AMD                            | 267      | 25.55%  |
| Samsung Electronics            | 141      | 13.49%  |
| SanDisk                        | 64       | 6.12%   |
| ASMedia Technology             | 41       | 3.92%   |
| Phison Electronics             | 39       | 3.73%   |
| Kingston Technology Company    | 32       | 3.06%   |
| Micron/Crucial Technology      | 19       | 1.82%   |
| Marvell Technology Group       | 19       | 1.82%   |
| Silicon Motion                 | 12       | 1.15%   |
| ADATA Technology               | 11       | 1.05%   |
| Realtek Semiconductor          | 10       | 0.96%   |
| JMicron Technology             | 9        | 0.86%   |
| Nvidia                         | 7        | 0.67%   |
| SK hynix                       | 6        | 0.57%   |
| MAXIO Technology (Hangzhou)    | 6        | 0.57%   |
| Toshiba America Info Systems   | 4        | 0.38%   |
| Micron Technology              | 4        | 0.38%   |
| Broadcom / LSI                 | 4        | 0.38%   |
| LSI Logic / Symbios Logic      | 3        | 0.29%   |
| VIA Technologies               | 2        | 0.19%   |
| Solid State Storage Technology | 2        | 0.19%   |
| Lite-On Technology             | 2        | 0.19%   |
| KIOXIA                         | 2        | 0.19%   |
| ULi Electronics                | 1        | 0.1%    |
| Solidigm                       | 1        | 0.1%    |
| Silicon Image                  | 1        | 0.1%    |
| Shenzhen Longsys Electronics   | 1        | 0.1%    |
| Seagate Technology             | 1        | 0.1%    |
| Netac Technology               | 1        | 0.1%    |
| Biwin Storage Technology       | 1        | 0.1%    |
| Adaptec                        | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 157      | 12.88%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 77       | 6.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 61       | 5%      |
| AMD 500 Series Chipset SATA Controller                                                  | 56       | 4.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 42       | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 39       | 3.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34       | 2.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 30       | 2.46%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 29       | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 29       | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 27       | 2.21%   |
| Intel SATA Controller [RAID mode]                                                       | 23       | 1.89%   |
| Phison E12 NVMe Controller                                                              | 20       | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 1.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20       | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 17       | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 17       | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 1.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 13       | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 13       | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 1.07%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 0.98%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 11       | 0.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 11       | 0.9%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 11       | 0.9%    |
| AMD FCH SATA Controller D                                                               | 11       | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 10       | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 10       | 0.82%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 10       | 0.82%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 10       | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 10       | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 10       | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 0.74%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 8        | 0.66%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 8        | 0.66%   |
| AMD X370 Series Chipset SATA Controller                                                 | 8        | 0.66%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 0.66%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 7        | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 540      | 54.33%  |
| NVMe | 324      | 32.6%   |
| IDE  | 69       | 6.94%   |
| RAID | 50       | 5.03%   |
| SAS  | 9        | 0.91%   |
| SCSI | 2        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 330      | 54.1%   |
| AMD    | 280      | 45.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 25       | 4.1%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 2.95%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 15       | 2.46%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 14       | 2.3%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 13       | 2.13%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 12       | 1.97%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 12       | 1.97%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 12       | 1.97%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 11       | 1.8%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 11       | 1.8%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 9        | 1.48%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8        | 1.31%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 8        | 1.31%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 1.31%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 7        | 1.15%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 7        | 1.15%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 7        | 1.15%   |
| AMD Ryzen 5 7600X 6-Core Processor          | 7        | 1.15%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 7        | 1.15%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 6        | 0.98%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 6        | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 5        | 0.82%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 0.82%   |
| Intel 12th Gen Core i9-12900K               | 5        | 0.82%   |
| Intel 12th Gen Core i7-12700                | 5        | 0.82%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 5        | 0.82%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 5        | 0.82%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 4        | 0.66%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 0.66%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.66%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.66%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 4        | 0.66%   |
| Intel 12th Gen Core i7-12700K               | 4        | 0.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.66%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 4        | 0.66%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 0.66%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz         | 3        | 0.49%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 3        | 0.49%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 106      | 17.38%  |
| Intel Core i7           | 104      | 17.05%  |
| Intel Core i5           | 78       | 12.79%  |
| AMD Ryzen 7             | 65       | 10.66%  |
| AMD Ryzen 9             | 48       | 7.87%   |
| Other                   | 44       | 7.21%   |
| Intel Xeon              | 33       | 5.41%   |
| Intel Core i3           | 27       | 4.43%   |
| AMD FX                  | 15       | 2.46%   |
| Intel Core 2 Quad       | 8        | 1.31%   |
| AMD Ryzen 3             | 8        | 1.31%   |
| Intel Pentium           | 7        | 1.15%   |
| Intel Core 2 Duo        | 7        | 1.15%   |
| Intel Core i9           | 6        | 0.98%   |
| Intel Celeron           | 5        | 0.82%   |
| Intel Pentium Dual-Core | 4        | 0.66%   |
| AMD Ryzen Threadripper  | 4        | 0.66%   |
| AMD A8                  | 4        | 0.66%   |
| AMD A6                  | 4        | 0.66%   |
| AMD A10                 | 4        | 0.66%   |
| Intel Atom              | 3        | 0.49%   |
| AMD Phenom II X6        | 3        | 0.49%   |
| AMD Phenom II X4        | 3        | 0.49%   |
| AMD A4                  | 3        | 0.49%   |
| Intel Pentium Gold      | 2        | 0.33%   |
| AMD Ryzen 5 PRO         | 2        | 0.33%   |
| AMD Phenom II X2        | 2        | 0.33%   |
| AMD Athlon 64 X2        | 2        | 0.33%   |
| Intel Pentium Dual      | 1        | 0.16%   |
| Intel Genuine           | 1        | 0.16%   |
| AMD Six-Core Opteron    | 1        | 0.16%   |
| AMD Ryzen 7 PRO         | 1        | 0.16%   |
| AMD Ryzen 3 PRO         | 1        | 0.16%   |
| AMD PRO A10             | 1        | 0.16%   |
| AMD Athlon II X4        | 1        | 0.16%   |
| AMD Athlon II X2        | 1        | 0.16%   |
| AMD Athlon              | 1        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 185      | 30.33%  |
| 6      | 156      | 25.57%  |
| 8      | 102      | 16.72%  |
| 2      | 67       | 10.98%  |
| 12     | 42       | 6.89%   |
| 16     | 32       | 5.25%   |
| 10     | 10       | 1.64%   |
| 24     | 5        | 0.82%   |
| 3      | 5        | 0.82%   |
| 1      | 3        | 0.49%   |
| 14     | 2        | 0.33%   |
| 32     | 1        | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 602      | 98.69%  |
| 2      | 8        | 1.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 456      | 74.75%  |
| 1      | 154      | 25.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 610      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 88       | 14.08%  |
| 0x08701021 | 52       | 8.32%   |
| 0x306c3    | 33       | 5.28%   |
| 0x306a9    | 31       | 4.96%   |
| 0x506e3    | 27       | 4.32%   |
| 0x906ea    | 23       | 3.68%   |
| 0x0a601203 | 20       | 3.2%    |
| 0x0a50000d | 20       | 3.2%    |
| 0x90672    | 18       | 2.88%   |
| 0x0a20120a | 18       | 2.88%   |
| 0x0a201016 | 18       | 2.88%   |
| 0x206a7    | 15       | 2.4%    |
| 0x906ed    | 12       | 1.92%   |
| 0x0a50000c | 12       | 1.92%   |
| 0x08701013 | 12       | 1.92%   |
| 0x0800820d | 12       | 1.92%   |
| 0x906e9    | 11       | 1.76%   |
| 0x206d7    | 11       | 1.76%   |
| 0xa0655    | 9        | 1.44%   |
| 0xa0653    | 9        | 1.44%   |
| 0x1067a    | 9        | 1.44%   |
| 0x06000822 | 8        | 1.28%   |
| 0x306f2    | 7        | 1.12%   |
| 0x0a201205 | 7        | 1.12%   |
| 0x08108109 | 7        | 1.12%   |
| 0x08001138 | 7        | 1.12%   |
| 0x90675    | 6        | 0.96%   |
| 0x0a201009 | 6        | 0.96%   |
| 0xb0671    | 5        | 0.8%    |
| 0xa0671    | 5        | 0.8%    |
| 0x0a50000b | 5        | 0.8%    |
| 0x906ec    | 4        | 0.64%   |
| 0x0a601201 | 4        | 0.64%   |
| 0x08701030 | 4        | 0.64%   |
| 0x08101016 | 4        | 0.64%   |
| 0x06001119 | 4        | 0.64%   |
| 0x6fd      | 3        | 0.48%   |
| 0x6fb      | 3        | 0.48%   |
| 0x106e5    | 3        | 0.48%   |
| 0x0a201204 | 3        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 91       | 14.92%  |
| Zen 2            | 75       | 12.3%   |
| KabyLake         | 66       | 10.82%  |
| Haswell          | 48       | 7.87%   |
| IvyBridge        | 41       | 6.72%   |
| Alderlake Hybrid | 35       | 5.74%   |
| Skylake          | 33       | 5.41%   |
| SandyBridge      | 33       | 5.41%   |
| Unknown          | 29       | 4.75%   |
| Zen+             | 23       | 3.77%   |
| CometLake        | 20       | 3.28%   |
| Zen              | 19       | 3.11%   |
| Piledriver       | 17       | 2.79%   |
| Penryn           | 15       | 2.46%   |
| K10              | 10       | 1.64%   |
| Icelake          | 8        | 1.31%   |
| Core             | 7        | 1.15%   |
| Westmere         | 6        | 0.98%   |
| Nehalem          | 6        | 0.98%   |
| Steamroller      | 4        | 0.66%   |
| Excavator        | 4        | 0.66%   |
| Bonnell          | 4        | 0.66%   |
| Silvermont       | 3        | 0.49%   |
| Bulldozer        | 3        | 0.49%   |
| K8 Hammer        | 2        | 0.33%   |
| Jaguar           | 2        | 0.33%   |
| Broadwell        | 2        | 0.33%   |
| Tremont          | 1        | 0.16%   |
| Puma             | 1        | 0.16%   |
| K10 Llano        | 1        | 0.16%   |
| Goldmont plus    | 1        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 270      | 40.72%  |
| Nvidia                     | 266      | 40.12%  |
| Intel                      | 123      | 18.55%  |
| ASPEED Technology          | 3        | 0.45%   |
| Matrox Electronics Systems | 1        | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 49       | 7.1%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 26       | 3.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 26       | 3.77%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 25       | 3.62%   |
| AMD Raphael                                                                 | 24       | 3.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 13       | 1.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13       | 1.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 13       | 1.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 12       | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 1.74%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 11       | 1.59%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 1.45%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 10       | 1.45%   |
| Intel HD Graphics 530                                                       | 10       | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.3%    |
| Intel AlderLake-S GT1                                                       | 9        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 8        | 1.16%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 8        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 1.16%   |
| Intel HD Graphics 630                                                       | 8        | 1.16%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 8        | 1.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 1.01%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 7        | 1.01%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 7        | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 1.01%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 0.87%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                              | 6        | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 0.87%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 0.72%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 5        | 0.72%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 0.72%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 5        | 0.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 5        | 0.72%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 4        | 0.58%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 4        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x AMD                  | 230      | 37.52%  |
| 1 x Nvidia               | 228      | 37.19%  |
| 1 x Intel                | 88       | 14.36%  |
| 2 x AMD                  | 20       | 3.26%   |
| Intel + Nvidia           | 19       | 3.1%    |
| AMD + Nvidia             | 14       | 2.28%   |
| 2 x Intel                | 3        | 0.49%   |
| Intel + AMD              | 3        | 0.49%   |
| 2 x Nvidia               | 2        | 0.33%   |
| 3 x AMD                  | 1        | 0.16%   |
| 2 x Nvidia + 1 x ASPEED  | 1        | 0.16%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.16%   |
| 1 x ASPEED               | 1        | 0.16%   |
| AMD + Matrox             | 1        | 0.16%   |
| AMD + ASPEED             | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 445      | 72.36%  |
| Proprietary | 149      | 24.23%  |
| Unknown     | 21       | 3.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 175      | 28.04%  |
| 7.01-8.0   | 132      | 21.15%  |
| 1.01-2.0   | 66       | 10.58%  |
| 3.01-4.0   | 62       | 9.94%   |
| 8.01-16.0  | 55       | 8.81%   |
| 0.51-1.0   | 50       | 8.01%   |
| 0.01-0.5   | 42       | 6.73%   |
| 5.01-6.0   | 27       | 4.33%   |
| 2.01-3.0   | 8        | 1.28%   |
| 16.01-24.0 | 7        | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 103      | 14.45%  |
| Samsung Electronics  | 100      | 14.03%  |
| Goldstar             | 90       | 12.62%  |
| Hewlett-Packard      | 52       | 7.29%   |
| AOC                  | 47       | 6.59%   |
| Acer                 | 41       | 5.75%   |
| BenQ                 | 33       | 4.63%   |
| Ancor Communications | 29       | 4.07%   |
| Philips              | 24       | 3.37%   |
| ASUSTek Computer     | 24       | 3.37%   |
| Lenovo               | 22       | 3.09%   |
| Gigabyte Technology  | 12       | 1.68%   |
| ViewSonic            | 11       | 1.54%   |
| Iiyama               | 11       | 1.54%   |
| MSI                  | 10       | 1.4%    |
| Sceptre Tech         | 9        | 1.26%   |
| Sony                 | 7        | 0.98%   |
| Unknown              | 6        | 0.84%   |
| Eizo                 | 5        | 0.7%    |
| Unknown              | 5        | 0.7%    |
| Vizio                | 4        | 0.56%   |
| NEC Computers        | 4        | 0.56%   |
| Mi                   | 4        | 0.56%   |
| Pixio                | 3        | 0.42%   |
| HannStar             | 3        | 0.42%   |
| ONN                  | 2        | 0.28%   |
| Medion               | 2        | 0.28%   |
| KTC                  | 2        | 0.28%   |
| HVR                  | 2        | 0.28%   |
| HUAWEI               | 2        | 0.28%   |
| Hitachi              | 2        | 0.28%   |
| FPT                  | 2        | 0.28%   |
| Denver               | 2        | 0.28%   |
| Belinea              | 2        | 0.28%   |
| AU Optronics         | 2        | 0.28%   |
| YTH                  | 1        | 0.14%   |
| XKX                  | 1        | 0.14%   |
| WIP                  | 1        | 0.14%   |
| Westinghouse         | 1        | 0.14%   |
| USR                  | 1        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                       | 8        | 1.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 6        | 0.78%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 5        | 0.65%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 5        | 0.65%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                      | 5        | 0.65%   |
| Unknown                                                                | 5        | 0.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 4        | 0.52%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 4        | 0.52%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 4        | 0.52%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch      | 3        | 0.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.39%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 3        | 0.39%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 3        | 0.39%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                   | 3        | 0.39%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch               | 3        | 0.39%   |
| Goldstar ULTRAGEAR GSM774B 3440x1440 800x335mm 34.1-inch               | 3        | 0.39%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 3        | 0.39%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                  | 3        | 0.39%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 3        | 0.39%   |
| Goldstar E2011 GSM4ED3 1600x900 443x249mm 20.0-inch                    | 3        | 0.39%   |
| Goldstar 27GL650F GSM5B71 1920x1080 530x300mm 24.0-inch                | 3        | 0.39%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                  | 3        | 0.39%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 3        | 0.39%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 3        | 0.39%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 3        | 0.39%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                        | 3        | 0.39%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                       | 3        | 0.39%   |
| Vizio V705-H3 VIZ1039 3840x2160 1538x865mm 69.5-inch                   | 2        | 0.26%   |
| Sceptre Tech Sceptre M25 SPT0A05 1920x1080 597x336mm 27.0-inch         | 2        | 0.26%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch         | 2        | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.26%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 2        | 0.26%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 2        | 0.26%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 597x336mm 27.0-inch | 2        | 0.26%   |
| Samsung Electronics LCD Monitor SAM7106 1920x1080 530x300mm 24.0-inch  | 2        | 0.26%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2        | 0.26%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 480x270mm 21.7-inch  | 2        | 0.26%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch     | 2        | 0.26%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 2        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 280      | 41.18%  |
| 2560x1440 (QHD)    | 107      | 15.74%  |
| 3840x2160 (4K)     | 101      | 14.85%  |
| 3440x1440          | 39       | 5.74%   |
| 1280x1024 (SXGA)   | 21       | 3.09%   |
| 1600x900 (HD+)     | 18       | 2.65%   |
| 1366x768 (WXGA)    | 18       | 2.65%   |
| 1680x1050 (WSXGA+) | 17       | 2.5%    |
| 2560x1080          | 15       | 2.21%   |
| 1920x1200 (WUXGA)  | 13       | 1.91%   |
| 1440x900 (WXGA+)   | 11       | 1.62%   |
| Unknown            | 6        | 0.88%   |
| 3840x1080          | 5        | 0.74%   |
| 2288x1287          | 5        | 0.74%   |
| 1600x1200          | 4        | 0.59%   |
| 1360x768           | 4        | 0.59%   |
| 2560x1600          | 3        | 0.44%   |
| 5760x1080          | 2        | 0.29%   |
| 2160x1200          | 2        | 0.29%   |
| 4160x1440          | 1        | 0.15%   |
| 3840x2560          | 1        | 0.15%   |
| 3840x1600          | 1        | 0.15%   |
| 3200x1080          | 1        | 0.15%   |
| 3120x1600          | 1        | 0.15%   |
| 2560x2880          | 1        | 0.15%   |
| 1920x540           | 1        | 0.15%   |
| 1920x1440          | 1        | 0.15%   |
| 1024x768 (XGA)     | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 161      | 22.45%  |
| 24      | 121      | 16.88%  |
| 23      | 80       | 11.16%  |
| 21      | 59       | 8.23%   |
| 31      | 54       | 7.53%   |
| 34      | 45       | 6.28%   |
| 19      | 22       | 3.07%   |
| Unknown | 22       | 3.07%   |
| 20      | 20       | 2.79%   |
| 18      | 16       | 2.23%   |
| 22      | 14       | 1.95%   |
| 25      | 11       | 1.53%   |
| 32      | 9        | 1.26%   |
| 84      | 7        | 0.98%   |
| 48      | 7        | 0.98%   |
| 17      | 7        | 0.98%   |
| 54      | 6        | 0.84%   |
| 26      | 6        | 0.84%   |
| 142     | 5        | 0.7%    |
| 29      | 5        | 0.7%    |
| 40      | 4        | 0.56%   |
| 28      | 4        | 0.56%   |
| 72      | 3        | 0.42%   |
| 42      | 3        | 0.42%   |
| 39      | 3        | 0.42%   |
| 35      | 3        | 0.42%   |
| 15      | 3        | 0.42%   |
| 69      | 2        | 0.28%   |
| 65      | 2        | 0.28%   |
| 52      | 2        | 0.28%   |
| 43      | 2        | 0.28%   |
| 36      | 2        | 0.28%   |
| 55      | 1        | 0.14%   |
| 44      | 1        | 0.14%   |
| 41      | 1        | 0.14%   |
| 38      | 1        | 0.14%   |
| 37      | 1        | 0.14%   |
| 33      | 1        | 0.14%   |
| 12      | 1        | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 331      | 48.82%  |
| 401-500        | 115      | 16.96%  |
| 601-700        | 75       | 11.06%  |
| 701-800        | 56       | 8.26%   |
| Unknown        | 22       | 3.24%   |
| 1001-1500      | 18       | 2.65%   |
| 351-400        | 14       | 2.06%   |
| 1501-2000      | 12       | 1.77%   |
| 801-900        | 11       | 1.62%   |
| 301-350        | 9        | 1.33%   |
| 901-1000       | 9        | 1.33%   |
| More than 2000 | 5        | 0.74%   |
| 201-300        | 1        | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 458      | 73.99%  |
| 21/9    | 53       | 8.56%   |
| 16/10   | 53       | 8.56%   |
| 5/4     | 19       | 3.07%   |
| Unknown | 16       | 2.58%   |
| 4/3     | 8        | 1.29%   |
| 1.00    | 5        | 0.81%   |
| 32/9    | 4        | 0.65%   |
| 3/2     | 1        | 0.16%   |
| 1.96    | 1        | 0.16%   |
| 0.89    | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 208      | 29.59%  |
| 301-350        | 164      | 23.33%  |
| 351-500        | 116      | 16.5%   |
| 151-200        | 61       | 8.68%   |
| 251-300        | 56       | 7.97%   |
| More than 1000 | 30       | 4.27%   |
| 501-1000       | 23       | 3.27%   |
| Unknown        | 22       | 3.13%   |
| 141-150        | 19       | 2.7%    |
| 101-110        | 3        | 0.43%   |
| 71-80          | 1        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 360      | 55.13%  |
| 101-120 | 170      | 26.03%  |
| 121-160 | 48       | 7.35%   |
| 161-240 | 28       | 4.29%   |
| 1-50    | 25       | 3.83%   |
| Unknown | 22       | 3.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 405      | 65.64%  |
| 2     | 157      | 25.45%  |
| 3     | 28       | 4.54%   |
| 0     | 24       | 3.89%   |
| 4     | 3        | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 360      | 39.34%  |
| Intel                           | 328      | 35.85%  |
| MediaTek                        | 39       | 4.26%   |
| Qualcomm Atheros                | 37       | 4.04%   |
| Broadcom                        | 28       | 3.06%   |
| TP-Link                         | 24       | 2.62%   |
| Aquantia                        | 12       | 1.31%   |
| Ralink Technology               | 11       | 1.2%    |
| Ralink                          | 9        | 0.98%   |
| Microsoft                       | 7        | 0.77%   |
| D-Link                          | 6        | 0.66%   |
| Google                          | 5        | 0.55%   |
| Xiaomi                          | 4        | 0.44%   |
| Nvidia                          | 4        | 0.44%   |
| Samsung Electronics             | 3        | 0.33%   |
| Mellanox Technologies           | 3        | 0.33%   |
| Qualcomm Atheros Communications | 2        | 0.22%   |
| Qualcomm                        | 2        | 0.22%   |
| OPPO Electronics                | 2        | 0.22%   |
| NetGear                         | 2        | 0.22%   |
| Motorola PCS                    | 2        | 0.22%   |
| Marvell Technology Group        | 2        | 0.22%   |
| InterBiometrics                 | 2        | 0.22%   |
| Huawei Technologies             | 2        | 0.22%   |
| Zoom Telephonics                | 1        | 0.11%   |
| QinHeng Electronics             | 1        | 0.11%   |
| OnePlus Technology (Shenzhen)   | 1        | 0.11%   |
| National Semiconductor          | 1        | 0.11%   |
| Microchip Technology            | 1        | 0.11%   |
| Magic Control Technology        | 1        | 0.11%   |
| Linksys                         | 1        | 0.11%   |
| IMC Networks                    | 1        | 0.11%   |
| ICS Advent                      | 1        | 0.11%   |
| DisplayLink                     | 1        | 0.11%   |
| Conexant Systems                | 1        | 0.11%   |
| Broadcom Limited                | 1        | 0.11%   |
| Bose                            | 1        | 0.11%   |
| ASIX Electronics                | 1        | 0.11%   |
| Arduino SA                      | 1        | 0.11%   |
| American Megatrends             | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 263      | 25.26%  |
| Realtek RTL8125 2.5GbE Controller                                   | 72       | 6.92%   |
| Intel Wi-Fi 6 AX200                                                 | 62       | 5.96%   |
| Intel I211 Gigabit Network Connection                               | 50       | 4.8%    |
| Intel Ethernet Controller I225-V                                    | 43       | 4.13%   |
| Intel Ethernet Connection (2) I219-V                                | 36       | 3.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 24       | 2.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 19       | 1.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 18       | 1.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 16       | 1.54%   |
| Intel Wireless-AC 9260                                              | 14       | 1.34%   |
| Intel Ethernet Connection (7) I219-V                                | 13       | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 12       | 1.15%   |
| Intel Alder Lake-S PCH CNVi WiFi                                    | 12       | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 9        | 0.86%   |
| Intel Ethernet Connection I217-LM                                   | 9        | 0.86%   |
| Intel 82579V Gigabit Network Connection                             | 9        | 0.86%   |
| Intel Ethernet Connection (2) I219-LM                               | 8        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                | 8        | 0.77%   |
| Intel 82574L Gigabit Network Connection                             | 8        | 0.77%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 8        | 0.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 6        | 0.58%   |
| Intel Wireless 7265                                                 | 6        | 0.58%   |
| Realtek 802.11ac NIC                                                | 5        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 5        | 0.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 5        | 0.48%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 5        | 0.48%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter        | 5        | 0.48%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 4        | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 4        | 0.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 4        | 0.38%   |
| Ralink MT7601U Wireless Adapter                                     | 4        | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 4        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                               | 4        | 0.38%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 4        | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 3        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 143      | 44.83%  |
| Realtek Semiconductor           | 41       | 12.85%  |
| MediaTek                        | 39       | 12.23%  |
| TP-Link                         | 23       | 7.21%   |
| Qualcomm Atheros                | 21       | 6.58%   |
| Broadcom                        | 13       | 4.08%   |
| Ralink Technology               | 11       | 3.45%   |
| Ralink                          | 9        | 2.82%   |
| Microsoft                       | 7        | 2.19%   |
| D-Link                          | 4        | 1.25%   |
| Qualcomm Atheros Communications | 2        | 0.63%   |
| NetGear                         | 2        | 0.63%   |
| Linksys                         | 1        | 0.31%   |
| IMC Networks                    | 1        | 0.31%   |
| Broadcom Limited                | 1        | 0.31%   |
| AboCom Systems                  | 1        | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 62       | 19.31%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 19       | 5.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 18       | 5.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 16       | 4.98%   |
| Intel Wireless-AC 9260                                        | 14       | 4.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 12       | 3.74%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 12       | 3.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 6        | 1.87%   |
| Intel Wireless 7265                                           | 6        | 1.87%   |
| Realtek 802.11ac NIC                                          | 5        | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5        | 1.56%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 5        | 1.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 4        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 4        | 1.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 4        | 1.25%   |
| Ralink MT7601U Wireless Adapter                               | 4        | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 4        | 1.25%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 4        | 1.25%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 3        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 3        | 0.93%   |
| TP-Link 802.11ac NIC                                          | 3        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 3        | 0.93%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 3        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 3        | 0.93%   |
| Microsoft Xbox 360 Wireless Adapter                           | 3        | 0.93%   |
| Intel Wireless 7260                                           | 3        | 0.93%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                    | 2        | 0.62%   |
| TP-Link Archer T4U ver.3                                      | 2        | 0.62%   |
| TP-Link 802.11ac WLAN Adapter                                 | 2        | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 0.62%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 2        | 0.62%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 2        | 0.62%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 2        | 0.62%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2        | 0.62%   |
| Ralink RT5370 Wireless Adapter                                | 2        | 0.62%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                     | 2        | 0.62%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 2        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 342      | 50.37%  |
| Intel                         | 254      | 37.41%  |
| Qualcomm Atheros              | 17       | 2.5%    |
| Broadcom                      | 16       | 2.36%   |
| Aquantia                      | 12       | 1.77%   |
| Google                        | 5        | 0.74%   |
| Xiaomi                        | 4        | 0.59%   |
| Nvidia                        | 4        | 0.59%   |
| Samsung Electronics           | 3        | 0.44%   |
| Mellanox Technologies         | 3        | 0.44%   |
| Qualcomm                      | 2        | 0.29%   |
| OPPO Electronics              | 2        | 0.29%   |
| Marvell Technology Group      | 2        | 0.29%   |
| D-Link                        | 2        | 0.29%   |
| TP-Link                       | 1        | 0.15%   |
| OnePlus Technology (Shenzhen) | 1        | 0.15%   |
| National Semiconductor        | 1        | 0.15%   |
| Motorola PCS                  | 1        | 0.15%   |
| Magic Control Technology      | 1        | 0.15%   |
| ICS Advent                    | 1        | 0.15%   |
| Huawei Technologies           | 1        | 0.15%   |
| DisplayLink                   | 1        | 0.15%   |
| ASIX Electronics              | 1        | 0.15%   |
| American Megatrends           | 1        | 0.15%   |
| 3Com                          | 1        | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 263      | 37.09%  |
| Realtek RTL8125 2.5GbE Controller                                   | 72       | 10.16%  |
| Intel I211 Gigabit Network Connection                               | 50       | 7.05%   |
| Intel Ethernet Controller I225-V                                    | 43       | 6.06%   |
| Intel Ethernet Connection (2) I219-V                                | 36       | 5.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 24       | 3.39%   |
| Intel Ethernet Connection (7) I219-V                                | 13       | 1.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 9        | 1.27%   |
| Intel Ethernet Connection I217-LM                                   | 9        | 1.27%   |
| Intel 82579V Gigabit Network Connection                             | 9        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                               | 8        | 1.13%   |
| Intel Ethernet Connection (2) I218-V                                | 8        | 1.13%   |
| Intel 82574L Gigabit Network Connection                             | 8        | 1.13%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 8        | 1.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 5        | 0.71%   |
| Intel Ethernet Connection I217-V                                    | 5        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 5        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4        | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                               | 4        | 0.56%   |
| Intel Ethernet Connection (14) I219-V                               | 4        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 3        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 3        | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 3        | 0.42%   |
| Mellanox MT27500 Family [ConnectX-3]                                | 3        | 0.42%   |
| Intel I210 Gigabit Network Connection                               | 3        | 0.42%   |
| Intel Ethernet Controller X550                                      | 3        | 0.42%   |
| Intel Ethernet Connection (12) I219-V                               | 3        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                               | 3        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                               | 3        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                   | 3        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                    | 3        | 0.42%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                     | 3        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 2        | 0.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.28%   |
| OPPO RMX2027                                                        | 2        | 0.28%   |
| Intel I350 Gigabit Network Connection                               | 2        | 0.28%   |
| Intel Ethernet Connection (17) I219-V                               | 2        | 0.28%   |
| Intel 82578DM Gigabit Network Connection                            | 2        | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 607      | 66.19%  |
| WiFi     | 299      | 32.61%  |
| Modem    | 9        | 0.98%   |
| Unknown  | 2        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 483      | 75%     |
| WiFi     | 161      | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 321      | 52.28%  |
| 2     | 242      | 39.41%  |
| 3     | 39       | 6.35%   |
| 4     | 7        | 1.14%   |
| 5     | 2        | 0.33%   |
| 0     | 2        | 0.33%   |
| 9     | 1        | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 432      | 70.24%  |
| Yes  | 183      | 29.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 133      | 42.77%  |
| Cambridge Silicon Radio         | 60       | 19.29%  |
| Realtek Semiconductor           | 23       | 7.4%    |
| MediaTek                        | 23       | 7.4%    |
| TP-Link                         | 15       | 4.82%   |
| Broadcom                        | 13       | 4.18%   |
| ASUSTek Computer                | 9        | 2.89%   |
| Foxconn / Hon Hai               | 8        | 2.57%   |
| IMC Networks                    | 6        | 1.93%   |
| Qualcomm Atheros Communications | 5        | 1.61%   |
| Belkin Components               | 3        | 0.96%   |
| Apple                           | 3        | 0.96%   |
| Integrated System Solution      | 2        | 0.64%   |
| HTC (High Tech Computer)        | 2        | 0.64%   |
| Edimax Technology               | 2        | 0.64%   |
| Toshiba                         | 1        | 0.32%   |
| SINO WEALTH                     | 1        | 0.32%   |
| Lite-On Technology              | 1        | 0.32%   |
| Dynex                           | 1        | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 60       | 19.17%  |
| Intel AX200 Bluetooth                                                | 58       | 18.53%  |
| MediaTek Wireless_Device                                             | 23       | 7.35%   |
| Realtek Bluetooth Radio                                              | 19       | 6.07%   |
| Intel AX210 Bluetooth                                                | 18       | 5.75%   |
| TP-Link UB500 Adapter                                                | 15       | 4.79%   |
| Intel AX201 Bluetooth                                                | 14       | 4.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 13       | 4.15%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 12       | 3.83%   |
| Intel Bluetooth wireless interface                                   | 11       | 3.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 10       | 3.19%   |
| Foxconn / Hon Hai Wireless_Device                                    | 7        | 2.24%   |
| Intel Bluetooth Device                                               | 5        | 1.6%    |
| ASUS ASUS USB-BT500                                                  | 4        | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3        | 0.96%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 0.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 0.96%   |
| IMC Networks Wireless_Device                                         | 3        | 0.96%   |
| IMC Networks Bluetooth Radio                                         | 3        | 0.96%   |
| Apple Bluetooth Host Controller                                      | 3        | 0.96%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2        | 0.64%   |
| Edimax Bluetooth Adapter                                             | 2        | 0.64%   |
| ASUS Bluetooth Adapter                                               | 2        | 0.64%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 0.32%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 1        | 0.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 1        | 0.32%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.32%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.32%   |
| Lite-On Bluetooth Device                                             | 1        | 0.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.32%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.32%   |
| Integrated System Solution Bluetooth Device                          | 1        | 0.32%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth                          | 1        | 0.32%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.32%   |
| Broadcom HP Portable Valentine                                       | 1        | 0.32%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 1        | 0.32%   |
| Broadcom BCM20702A0 Bluetooth                                        | 1        | 0.32%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.32%   |
| Belkin Components F8T003v2 Bluetooth                                 | 1        | 0.32%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 347      | 29.18%  |
| Intel                                           | 314      | 26.41%  |
| Nvidia                                          | 259      | 21.78%  |
| C-Media Electronics                             | 34       | 2.86%   |
| Logitech                                        | 18       | 1.51%   |
| Creative Labs                                   | 15       | 1.26%   |
| JMTek                                           | 13       | 1.09%   |
| ASUSTek Computer                                | 13       | 1.09%   |
| Razer USA                                       | 12       | 1.01%   |
| Kingston Technology                             | 10       | 0.84%   |
| Focusrite-Novation                              | 9        | 0.76%   |
| Texas Instruments                               | 8        | 0.67%   |
| SteelSeries ApS                                 | 8        | 0.67%   |
| Generalplus Technology                          | 8        | 0.67%   |
| GN Netcom                                       | 7        | 0.59%   |
| Corsair                                         | 6        | 0.5%    |
| Samson Technologies                             | 5        | 0.42%   |
| Sony                                            | 4        | 0.34%   |
| Realtek Semiconductor                           | 4        | 0.34%   |
| Plantronics                                     | 4        | 0.34%   |
| Dell                                            | 4        | 0.34%   |
| XMOS                                            | 3        | 0.25%   |
| VIA Technologies                                | 3        | 0.25%   |
| RODE Microphones                                | 3        | 0.25%   |
| Micro Star International                        | 3        | 0.25%   |
| M-Audio                                         | 3        | 0.25%   |
| Giga-Byte Technology                            | 3        | 0.25%   |
| FiiO Electronics Technology                     | 3        | 0.25%   |
| Creative Technology                             | 3        | 0.25%   |
| Trust                                           | 2        | 0.17%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.17%   |
| Tenx Technology                                 | 2        | 0.17%   |
| Schiit Audio                                    | 2        | 0.17%   |
| Medeli Electronics                              | 2        | 0.17%   |
| Licensed by Sony Computer Entertainment America | 2        | 0.17%   |
| LG Electronics                                  | 2        | 0.17%   |
| KTMicro                                         | 2        | 0.17%   |
| GYROCOM C&C                                     | 2        | 0.17%   |
| FDUCE PRO AUDIO MADE                            | 2        | 0.17%   |
| Cambridge Silicon Radio                         | 2        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 125      | 8.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 76       | 5.36%   |
| AMD Family 17h/19h HD Audio Controller                                     | 75       | 5.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 51       | 3.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 40       | 2.82%   |
| Intel 200 Series PCH HD Audio                                              | 37       | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 33       | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 31       | 2.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 30       | 2.12%   |
| Intel Alder Lake-S HD Audio Controller                                     | 28       | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28       | 1.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28       | 1.98%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 26       | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 23       | 1.62%   |
| Nvidia GP106 High Definition Audio Controller                              | 21       | 1.48%   |
| Nvidia GA104 High Definition Audio Controller                              | 20       | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 1.27%   |
| AMD Navi 10 HDMI Audio                                                     | 18       | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 17       | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                              | 16       | 1.13%   |
| Nvidia TU104 HD Audio Controller                                           | 16       | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                              | 13       | 0.92%   |
| Nvidia GA102 High Definition Audio Controller                              | 13       | 0.92%   |
| AMD FCH Azalia Controller                                                  | 13       | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13       | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 12       | 0.85%   |
| Nvidia GA106 High Definition Audio Controller                              | 12       | 0.85%   |
| JMTek USB PnP Audio Device                                                 | 12       | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 12       | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 11       | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 11       | 0.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 0.78%   |
| ASUSTek Computer USB Audio                                                 | 10       | 0.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 0.64%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 9        | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 9        | 0.64%   |
| C-Media Electronics USB Audio Device                                       | 9        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 62       | 19.38%  |
| G.Skill             | 50       | 15.63%  |
| Corsair             | 49       | 15.31%  |
| Unknown             | 24       | 7.5%    |
| Samsung Electronics | 24       | 7.5%    |
| Crucial             | 23       | 7.19%   |
| SK hynix            | 15       | 4.69%   |
| A-DATA Technology   | 10       | 3.13%   |
| Micron Technology   | 9        | 2.81%   |
| Team                | 7        | 2.19%   |
| Patriot             | 6        | 1.88%   |
| Smart               | 4        | 1.25%   |
| Ramaxel Technology  | 4        | 1.25%   |
| AMD                 | 4        | 1.25%   |
| Nanya Technology    | 3        | 0.94%   |
| GeIL                | 3        | 0.94%   |
| Apacer              | 3        | 0.94%   |
| Unknown             | 3        | 0.94%   |
| Unifosa             | 2        | 0.63%   |
| Gold Key            | 2        | 0.63%   |
| Elpida              | 2        | 0.63%   |
| Unknown (ABCD)      | 1        | 0.31%   |
| Unknown (0x0C97)    | 1        | 0.31%   |
| Transcend           | 1        | 0.31%   |
| Silicon Power       | 1        | 0.31%   |
| Qimonda             | 1        | 0.31%   |
| PNY                 | 1        | 0.31%   |
| Innodisk            | 1        | 0.31%   |
| GOODRAM             | 1        | 0.31%   |
| Golden Empire       | 1        | 0.31%   |
| EVGA                | 1        | 0.31%   |
| Avant               | 1        | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 6        | 1.75%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s   | 6        | 1.75%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 5        | 1.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 4        | 1.17%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 4        | 1.17%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 4        | 1.17%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s             | 4        | 1.17%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s               | 3        | 0.88%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s      | 3        | 0.88%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s     | 3        | 0.88%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s | 3        | 0.88%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 3        | 0.88%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 3        | 0.88%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 3        | 0.88%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 0.88%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s   | 3        | 0.88%   |
| Unknown                                                 | 3        | 0.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 2        | 0.58%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 2        | 0.58%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 2        | 0.58%   |
| Samsung RAM M378B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s  | 2        | 0.58%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s   | 2        | 0.58%   |
| Kingston RAM KF560C40-16 16GB DIMM DDR5 6000MT/s        | 2        | 0.58%   |
| Kingston RAM KF552C40-8 8GB DIMM DDR5 4800MT/s          | 2        | 0.58%   |
| Kingston RAM KF552C40-32 32GB DIMM 5200MT/s             | 2        | 0.58%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s        | 2        | 0.58%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 0.58%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 0.58%   |
| G.Skill RAM F5-5600J3036D16G 16GB DIMM DDR5 4800MT/s    | 2        | 0.58%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 3600MT/s     | 2        | 0.58%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s   | 2        | 0.58%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s   | 2        | 0.58%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 2        | 0.58%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s  | 2        | 0.58%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s   | 2        | 0.58%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s               | 1        | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.29%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR2 533MT/s                | 1        | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR2 266MT/s                | 1        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 162      | 57.65%  |
| DDR3    | 67       | 23.84%  |
| DDR5    | 26       | 9.25%   |
| DDR2    | 15       | 5.34%   |
| Unknown | 6        | 2.14%   |
| SDRAM   | 3        | 1.07%   |
| LPDDR4  | 1        | 0.36%   |
| DDR     | 1        | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 267      | 96.04%  |
| SODIMM  | 8        | 2.88%   |
| FB-DIMM | 2        | 0.72%   |
| RIMM    | 1        | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 117      | 39.8%   |
| 16384 | 70       | 23.81%  |
| 4096  | 53       | 18.03%  |
| 32768 | 26       | 8.84%   |
| 2048  | 25       | 8.5%    |
| 1024  | 3        | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 42       | 13.55%  |
| 1600  | 41       | 13.23%  |
| 3600  | 30       | 9.68%   |
| 1333  | 21       | 6.77%   |
| 2400  | 16       | 5.16%   |
| 2133  | 12       | 3.87%   |
| 2667  | 11       | 3.55%   |
| 800   | 10       | 3.23%   |
| 4800  | 9        | 2.9%    |
| 3866  | 8        | 2.58%   |
| 3733  | 8        | 2.58%   |
| 1800  | 7        | 2.26%   |
| 5200  | 6        | 1.94%   |
| 3533  | 6        | 1.94%   |
| 3466  | 6        | 1.94%   |
| 3000  | 6        | 1.94%   |
| 667   | 6        | 1.94%   |
| 2666  | 5        | 1.61%   |
| 6000  | 4        | 1.29%   |
| 3800  | 4        | 1.29%   |
| 3400  | 4        | 1.29%   |
| 2933  | 4        | 1.29%   |
| 1866  | 4        | 1.29%   |
| 5600  | 3        | 0.97%   |
| 3666  | 3        | 0.97%   |
| 3266  | 2        | 0.65%   |
| 3100  | 2        | 0.65%   |
| 2800  | 2        | 0.65%   |
| 1867  | 2        | 0.65%   |
| 533   | 2        | 0.65%   |
| 400   | 2        | 0.65%   |
| 333   | 2        | 0.65%   |
| 6800  | 1        | 0.32%   |
| 6400  | 1        | 0.32%   |
| 5900  | 1        | 0.32%   |
| 5808  | 1        | 0.32%   |
| 4133  | 1        | 0.32%   |
| 4000  | 1        | 0.32%   |
| 3933  | 1        | 0.32%   |
| 3334  | 1        | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 7        | 28%     |
| Brother Industries    | 6        | 24%     |
| Seiko Epson           | 4        | 16%     |
| Samsung Electronics   | 4        | 16%     |
| Canon                 | 2        | 8%      |
| Prolific Technology   | 1        | 4%      |
| Lexmark International | 1        | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson WP-4020 Series    | 1        | 4%      |
| Seiko Epson WF-2860 Series    | 1        | 4%      |
| Seiko Epson Printer           | 1        | 4%      |
| Seiko Epson L300 Series       | 1        | 4%      |
| Samsung SCX-4623 Series       | 1        | 4%      |
| Samsung SCX-4300 Series       | 1        | 4%      |
| Samsung ML-2855 Series        | 1        | 4%      |
| Samsung M2070 Series          | 1        | 4%      |
| Prolific PL2305 Parallel Port | 1        | 4%      |
| Lexmark International B2236dw | 1        | 4%      |
| HP LaserJet P2055 series      | 1        | 4%      |
| HP LaserJet 1012              | 1        | 4%      |
| HP LaserJet 1010              | 1        | 4%      |
| HP ENVY Photo 7800 series     | 1        | 4%      |
| HP DeskJet F300 series        | 1        | 4%      |
| HP DeskJet 5650c              | 1        | 4%      |
| HP DeskJet 3630 series        | 1        | 4%      |
| Canon TS5100 series           | 1        | 4%      |
| Canon LiDE 400                | 1        | 4%      |
| Brother MFC-7460DN            | 1        | 4%      |
| Brother HL-L2350DW series     | 1        | 4%      |
| Brother HL-L2320D series      | 1        | 4%      |
| Brother HL-L2300D series      | 1        | 4%      |
| Brother HL-2030 Laser Printer | 1        | 4%      |
| Brother DCP-L2510D series     | 1        | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 5        | 71.43%  |
| Canon       | 2        | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 2        | 28.57%  |
| Seiko Epson GT-6600U [Perfection 610]                    | 2        | 28.57%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 14.29%  |
| Canon CanoScan LiDE 210                                  | 1        | 14.29%  |
| Canon CanoScan LiDE 100                                  | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 81       | 46.82%  |
| Microdia                               | 13       | 7.51%   |
| Microsoft                              | 11       | 6.36%   |
| Samsung Electronics                    | 7        | 4.05%   |
| Apple                                  | 7        | 4.05%   |
| Sunplus Innovation Technology          | 5        | 2.89%   |
| KYE Systems (Mouse Systems)            | 5        | 2.89%   |
| Chicony Electronics                    | 4        | 2.31%   |
| LG Electronics                         | 3        | 1.73%   |
| HD 2MP WEBCAM                          | 3        | 1.73%   |
| AVerMedia Technologies                 | 3        | 1.73%   |
| WaveRider Communications               | 2        | 1.16%   |
| Trust                                  | 2        | 1.16%   |
| SunplusIT                              | 2        | 1.16%   |
| Cubeternet                             | 2        | 1.16%   |
| ARC International                      | 2        | 1.16%   |
| Z-Star Microelectronics                | 1        | 0.58%   |
| WCM_USB                                | 1        | 0.58%   |
| Unknown                                | 1        | 0.58%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.58%   |
| Sonix Technology                       | 1        | 0.58%   |
| SN0002                                 | 1        | 0.58%   |
| Smartronix                             | 1        | 0.58%   |
| Realtek Semiconductor                  | 1        | 0.58%   |
| Nikon                                  | 1        | 0.58%   |
| MacroSilicon                           | 1        | 0.58%   |
| Integrated Technology Express          | 1        | 0.58%   |
| Hewlett-Packard                        | 1        | 0.58%   |
| Generalplus Technology                 | 1        | 0.58%   |
| Elecom                                 | 1        | 0.58%   |
| DigitalPersona                         | 1        | 0.58%   |
| ASUSTek Computer                       | 1        | 0.58%   |
| Asuscom Network                        | 1        | 0.58%   |
| Arkmicro Technologies                  | 1        | 0.58%   |
| Anker PowerConf C200                   | 1        | 0.58%   |
| A4Tech                                 | 1        | 0.58%   |
| Unknown                                | 1        | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                     | 15       | 8.62%   |
| Logitech Webcam C270                            | 13       | 7.47%   |
| Logitech HD Webcam C525                         | 9        | 5.17%   |
| Samsung Galaxy series, misc. (MTP mode)         | 7        | 4.02%   |
| Logitech C922 Pro Stream Webcam                 | 7        | 4.02%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                 | 7        | 4.02%   |
| Microdia Webcam Vitade AF                       | 5        | 2.87%   |
| Logitech C920 PRO HD Webcam                     | 5        | 2.87%   |
| Logitech HD Webcam C615                         | 4        | 2.3%    |
| Microsoft MicrosoftÂ LifeCam Cinema            | 3        | 1.72%   |
| Logitech Webcam C930e                           | 3        | 1.72%   |
| Logitech Webcam C310                            | 3        | 1.72%   |
| Logitech BRIO Ultra HD Webcam                   | 3        | 1.72%   |
| HD 2MP WEBCAM HD 2MP WEBCAM                     | 3        | 1.72%   |
| WaveRider USB 2.0 Camera                        | 2        | 1.15%   |
| Sunplus Full HD webcam                          | 2        | 1.15%   |
| Microsoft Xbox NUI Camera                       | 2        | 1.15%   |
| Microsoft LifeCam VX-5000                       | 2        | 1.15%   |
| Microdia USB 2.0 Camera                         | 2        | 1.15%   |
| Microdia Camera                                 | 2        | 1.15%   |
| Logitech Webcam C925e                           | 2        | 1.15%   |
| Logitech Webcam C250                            | 2        | 1.15%   |
| Logitech Webcam C170                            | 2        | 1.15%   |
| Logitech Logi Webcam C920e                      | 2        | 1.15%   |
| LG LG UltraFine Display Camera                  | 2        | 1.15%   |
| KYE Systems (Mouse Systems) Genius WideCam F100 | 2        | 1.15%   |
| AVerMedia Live Streamer CAM 313                 | 2        | 1.15%   |
| ARC International Camera                        | 2        | 1.15%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 0.57%   |
| WCM_USB WEB CAM                                 | 1        | 0.57%   |
| Unknown HD camera                               | 1        | 0.57%   |
| Trust WB-6250X Webcam                           | 1        | 0.57%   |
| Trust Full HD Webcam                            | 1        | 0.57%   |
| SunplusIT USB 2.0 Camera                        | 1        | 0.57%   |
| SunplusIT AEEVISION Camera                      | 1        | 0.57%   |
| Sunplus MTD Camera                              | 1        | 0.57%   |
| Sunplus ezcap U3 capture-04                     | 1        | 0.57%   |
| Sunplus Aukey-PC-LM1E Camera                    | 1        | 0.57%   |
| Sony Ericsson Mobile AB XQ-CC54                 | 1        | 0.57%   |
| Sonix USB Camera                                | 1        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AuthenTec             | 2        | 33.33%  |
| Microsoft             | 1        | 16.67%  |
| LighTuning Technology | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Microsoft Fingerprint Reader                | 1        | 16.67%  |
| LighTuning Fingerprint Sensor               | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200] | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader           | 1        | 16.67%  |
| AuthenTec Fingerprint Sensor                | 1        | 16.67%  |
| AuthenTec AES1600                           | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 33.33%  |
| Realtek Semiconductor    | 1        | 33.33%  |
| Aktiv                    | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 33.33%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 33.33%  |
| Aktiv Rutoken lite                                                         | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 518      | 83.95%  |
| 1     | 84       | 13.61%  |
| 2     | 5        | 0.81%   |
| 4     | 4        | 0.65%   |
| 3     | 4        | 0.65%   |
| 8     | 1        | 0.16%   |
| 5     | 1        | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 37       | 31.36%  |
| Net/wireless             | 24       | 20.34%  |
| Sound                    | 11       | 9.32%   |
| Unassigned class         | 9        | 7.63%   |
| Multimedia controller    | 8        | 6.78%   |
| Camera                   | 7        | 5.93%   |
| Fingerprint reader       | 6        | 5.08%   |
| Communication controller | 5        | 4.24%   |
| Storage/raid             | 3        | 2.54%   |
| Network                  | 3        | 2.54%   |
| Net/ethernet             | 3        | 2.54%   |
| Modem                    | 1        | 0.85%   |
| Bluetooth                | 1        | 0.85%   |

